# Comparing `tmp/whylogs-1.1.9.dev0.tar.gz` & `tmp/whylogs-1.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "whylogs-1.1.9.dev0.tar", max compression
+gzip compressed data, was "whylogs-1.2.0.tar", max compression
```

## Comparing `whylogs-1.1.9.dev0.tar` & `whylogs-1.2.0.tar`

### file list

```diff
@@ -1,173 +1,215 @@
--rw-r--r--   0        0        0    18554 2022-10-11 21:07:57.570274 whylogs-1.1.9.dev0/README.md
--rw-r--r--   0        0        0     4836 2022-10-19 17:52:35.040274 whylogs-1.1.9.dev0/pyproject.toml
--rw-r--r--   0        0        0     1761 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/__init__.py
--rw-r--r--   0        0        0      347 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/__init__.py
--rw-r--r--   0        0        0      590 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/api/annotations.py
--rw-r--r--   0        0        0       51 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/fugue/__init__.py
--rw-r--r--   0        0        0     5520 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/fugue/profiler.py
--rw-r--r--   0        0        0     3802 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/logger/__init__.py
--rw-r--r--   0        0        0     3375 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/api/logger/logger.py
--rw-r--r--   0        0        0    10269 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/logger/result_set.py
--rw-r--r--   0        0        0     7149 2022-10-19 16:56:58.610274 whylogs-1.1.9.dev0/whylogs/api/logger/rolling.py
--rw-r--r--   0        0        0     5715 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/logger/segment_processing.py
--rw-r--r--   0        0        0      644 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/api/logger/transient.py
--rw-r--r--   0        0        0      317 2022-06-01 15:15:01.442491 whylogs-1.1.9.dev0/whylogs/api/pyspark/experimental/__init__.py
--rw-r--r--   0        0        0     3013 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/pyspark/experimental/profiler.py
--rw-r--r--   0        0        0      465 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/reader/__init__.py
--rw-r--r--   0        0        0      645 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/reader/local.py
--rw-r--r--   0        0        0      617 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/reader/reader.py
--rw-r--r--   0        0        0     1916 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/reader/s3.py
--rw-r--r--   0        0        0      190 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/api/store/__init__.py
--rw-r--r--   0        0        0     4555 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/api/store/local_store.py
--rw-r--r--   0        0        0      904 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/api/store/profile_store.py
--rw-r--r--   0        0        0      518 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/api/store/query.py
--rw-r--r--   0        0        0       97 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/api/store/s3.py
--rw-r--r--   0        0        0     5566 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/usage_stats/__init__.py
--rw-r--r--   0        0        0      947 2022-10-18 14:29:29.390275 whylogs-1.1.9.dev0/whylogs/api/writer/__init__.py
--rw-r--r--   0        0        0     2726 2022-10-18 14:29:29.390275 whylogs-1.1.9.dev0/whylogs/api/writer/gcs.py
--rw-r--r--   0        0        0     1423 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/writer/local.py
--rw-r--r--   0        0        0     1935 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/writer/mlflow.py
--rw-r--r--   0        0        0     3329 2022-10-18 14:29:29.390275 whylogs-1.1.9.dev0/whylogs/api/writer/s3.py
--rw-r--r--   0        0        0    17216 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/api/writer/whylabs.py
--rw-r--r--   0        0        0     1217 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/api/writer/writer.py
--rw-r--r--   0        0        0      818 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/__init__.py
--rw-r--r--   0        0        0     2567 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/column_profile.py
--rw-r--r--   0        0        0      208 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/core/common.py
--rw-r--r--   0        0        0      776 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/core/configs.py
--rw-r--r--   0        0        0      219 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/core/constraints/__init__.py
--rw-r--r--   0        0        0      774 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/constraints/factories/__init__.py
--rw-r--r--   0        0        0     1103 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/constraints/factories/cardinality_metrics.py
--rw-r--r--   0        0        0     2077 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/constraints/factories/count_metrics.py
--rw-r--r--   0        0        0     5477 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/constraints/factories/distribution_metrics.py
--rw-r--r--   0        0        0     2083 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/constraints/factories/frequent_items.py
--rw-r--r--   0        0        0    10380 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/core/constraints/metric_constraints.py
--rw-r--r--   0        0        0    10490 2022-10-19 17:50:04.170275 whylogs-1.1.9.dev0/whylogs/core/dataset_profile.py
--rw-r--r--   0        0        0     4094 2022-10-18 14:29:29.400275 whylogs-1.1.9.dev0/whylogs/core/datatypes.py
--rw-r--r--   0        0        0      518 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/core/errors.py
--rw-r--r--   0        0        0     2426 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/feature_weights.py
--rw-r--r--   0        0        0      806 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/input_resolver.py
--rw-r--r--   0        0        0      984 2022-10-08 17:03:10.597321 whylogs-1.1.9.dev0/whylogs/core/metrics/__init__.py
--rw-r--r--   0        0        0     4086 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/metrics/aggregators.py
--rw-r--r--   0        0        0     3853 2022-10-12 18:40:16.900275 whylogs-1.1.9.dev0/whylogs/core/metrics/column_metrics.py
--rw-r--r--   0        0        0     6459 2022-10-12 18:40:16.900275 whylogs-1.1.9.dev0/whylogs/core/metrics/compound_metric.py
--rw-r--r--   0        0        0     6598 2022-10-12 18:40:16.900275 whylogs-1.1.9.dev0/whylogs/core/metrics/condition_count_metric.py
--rw-r--r--   0        0        0     1597 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/core/metrics/decorators.py
--rw-r--r--   0        0        0     4853 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/metrics/deserializers.py
--rw-r--r--   0        0        0     1361 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/core/metrics/maths.py
--rw-r--r--   0        0        0     6053 2022-10-11 21:07:57.580274 whylogs-1.1.9.dev0/whylogs/core/metrics/metric_components.py
--rw-r--r--   0        0        0    20478 2022-10-12 18:40:16.900275 whylogs-1.1.9.dev0/whylogs/core/metrics/metrics.py
--rw-r--r--   0        0        0     7475 2022-10-12 18:40:16.900275 whylogs-1.1.9.dev0/whylogs/core/metrics/multimetric.py
--rw-r--r--   0        0        0     1666 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/core/metrics/registry.py
--rw-r--r--   0        0        0     4530 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/metrics/serializers.py
--rw-r--r--   0        0        0     5445 2022-10-11 21:07:57.590274 whylogs-1.1.9.dev0/whylogs/core/metrics/unicode_range.py
--rw-r--r--   0        0        0      107 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/model_performance_metrics/__init__.py
--rw-r--r--   0        0        0     8914 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/model_performance_metrics/confusion_matrix.py
--rw-r--r--   0        0        0     7407 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/model_performance_metrics/model_performance_metrics.py
--rw-r--r--   0        0        0     2838 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/model_performance_metrics/regression_metrics.py
--rw-r--r--   0        0        0     8131 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/preprocessing.py
--rw-r--r--   0        0        0      335 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/projectors.py
--rw-r--r--   0        0        0      183 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/core/proto/__init__.py
--rw-r--r--   0        0        0      242 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/core/proto/v0/__init__.py
--rw-r--r--   0        0        0    12534 2022-10-19 17:55:02.210275 whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_constraints_pb2.py
--rw-r--r--   0        0        0    19918 2022-10-19 17:55:01.470275 whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_constraints_pb2.pyi
--rw-r--r--   0        0        0    21343 2022-10-19 17:55:01.470275 whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_messages_pb2.py
--rw-r--r--   0        0        0    29018 2022-10-19 17:55:01.470275 whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_messages_pb2.pyi
--rw-r--r--   0        0        0    18521 2022-10-19 17:55:02.360274 whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_summaries_pb2.py
--rw-r--r--   0        0        0    24057 2022-10-19 17:55:01.470275 whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_summaries_pb2.pyi
--rw-r--r--   0        0        0    18571 2022-10-19 17:55:01.330274 whylogs-1.1.9.dev0/whylogs/core/proto/whylogs_messages_pb2.py
--rw-r--r--   0        0        0    21183 2022-10-19 17:55:01.330274 whylogs-1.1.9.dev0/whylogs/core/proto/whylogs_messages_pb2.pyi
--rw-r--r--   0        0        0     3230 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/resolvers.py
--rw-r--r--   0        0        0     6731 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/schema.py
--rw-r--r--   0        0        0      144 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/segment.py
--rw-r--r--   0        0        0     2138 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/segmentation_partition.py
--rw-r--r--   0        0        0      932 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/stubs.py
--rw-r--r--   0        0        0      278 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/utils/__init__.py
--rw-r--r--   0        0        0     1546 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/core/utils/protobuf_utils.py
--rw-r--r--   0        0        0      742 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/core/utils/stats_calculations.py
--rw-r--r--   0        0        0      130 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/core/utils/timestamp_calculations.py
--rw-r--r--   0        0        0     1054 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/utils/utils.py
--rw-r--r--   0        0        0      126 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/validators/__init__.py
--rw-r--r--   0        0        0     1465 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/validators/condition_validator.py
--rw-r--r--   0        0        0      508 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/validators/validator.py
--rw-r--r--   0        0        0      214 2022-09-09 00:34:16.153342 whylogs-1.1.9.dev0/whylogs/core/view/__init__.py
--rw-r--r--   0        0        0     5609 2022-10-12 18:40:16.900275 whylogs-1.1.9.dev0/whylogs/core/view/column_profile_view.py
--rw-r--r--   0        0        0    11899 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/view/dataset_profile_view.py
--rw-r--r--   0        0        0     7825 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/core/view/segmented_dataset_profile_view.py
--rw-r--r--   0        0        0      150 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/__init__.py
--rw-r--r--   0        0        0     5813 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/base.py
--rw-r--r--   0        0        0     4121 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/configs.py
--rw-r--r--   0        0        0        0 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/descr/__init__.py
--rw-r--r--   0        0        0     6422 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/descr/ecommerce.rst
--rw-r--r--   0        0        0    11285 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/descr/weather.rst
--rw-r--r--   0        0        0    10336 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/ecommerce.py
--rw-r--r--   0        0        0     2349 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/utils.py
--rw-r--r--   0        0        0    11124 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/datasets/weather.py
--rw-r--r--   0        0        0     9980 2022-10-11 21:07:57.590274 whylogs-1.1.9.dev0/whylogs/extras/image_metric.py
--rw-r--r--   0        0        0       52 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/migration/__init__.py
--rw-r--r--   0        0        0    12819 2022-10-17 16:37:19.010275 whylogs-1.1.9.dev0/whylogs/migration/converters.py
--rw-r--r--   0        0        0     3608 2022-10-11 21:07:57.590274 whylogs-1.1.9.dev0/whylogs/migration/uncompound.py
--rw-r--r--   0        0        0      296 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/__init__.py
--rw-r--r--   0        0        0        0 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/enums/__init__.py
--rw-r--r--   0        0        0      901 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/enums/enums.py
--rw-r--r--   0        0        0        0 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/extensions/__init__.py
--rw-r--r--   0        0        0      114 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/extensions/reports/constraints.py
--rw-r--r--   0        0        0      272 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/extensions/reports/histograms.py
--rw-r--r--   0        0        0     2502 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/extensions/reports/html_report.py
--rw-r--r--   0        0        0      975 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/extensions/reports/profile_summary.py
--rw-r--r--   0        0        0     1022 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/extensions/reports/summary_drift.py
--rw-r--r--   0        0        0       38 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/.prettierignore
--rw-r--r--   0        0        0      135 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/.prettierrc.yaml
--rw-r--r--   0        0        0   155568 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/css/bootstrap.min.css
--rw-r--r--   0        0        0    22747 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/css/whylogs-styles.css
--rw-r--r--   0        0        0   160788 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Bold.ttf
--rw-r--r--   0        0        0    50888 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Bold.woff
--rw-r--r--   0        0        0    32180 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Bold.woff2
--rw-r--r--   0        0        0   172144 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-BoldItalic.ttf
--rw-r--r--   0        0        0    55560 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-BoldItalic.woff
--rw-r--r--   0        0        0    35476 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-BoldItalic.woff2
--rw-r--r--   0        0        0   172188 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Italic.ttf
--rw-r--r--   0        0        0    55728 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Italic.woff
--rw-r--r--   0        0        0    35144 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Italic.woff2
--rw-r--r--   0        0        0   161212 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Medium.ttf
--rw-r--r--   0        0        0    53244 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Medium.woff
--rw-r--r--   0        0        0    34516 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Medium.woff2
--rw-r--r--   0        0        0   172380 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-MediumItalic.ttf
--rw-r--r--   0        0        0    59012 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-MediumItalic.woff
--rw-r--r--   0        0        0    38404 2022-05-31 19:33:45.922491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-MediumItalic.woff2
--rw-r--r--   0        0        0   161220 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Regular.ttf
--rw-r--r--   0        0        0    50936 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Regular.woff
--rw-r--r--   0        0        0    32192 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Regular.woff2
--rw-r--r--   0        0        0   161152 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBold.ttf
--rw-r--r--   0        0        0    53296 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBold.woff
--rw-r--r--   0        0        0    34744 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBold.woff2
--rw-r--r--   0        0        0   172396 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.ttf
--rw-r--r--   0        0        0    58892 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff
--rw-r--r--   0        0        0    38500 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff2
--rw-r--r--   0        0        0     3156 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/images/placement-chart.png
--rw-r--r--   0        0        0     9649 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/images/whylabs-favicon.png
--rw-r--r--   0        0        0   270687 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/js/d3.min.js
--rw-r--r--   0        0        0    12606 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/js/handlebars.js
--rw-r--r--   0        0        0    89501 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/js/jquery-3.6.0.min.js
--rw-r--r--   0        0        0    55927 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/js/whylogs-script.js
--rw-r--r--   0        0        0    47279 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-for-jupyter-notebook.html
--rw-r--r--   0        0        0    14235 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-bar-chart.html
--rw-r--r--   0        0        0    24533 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-constraints-report.html
--rw-r--r--   0        0        0    14144 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-differenced-chart.html
--rw-r--r--   0        0        0    14040 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-distribution-chart.html
--rw-r--r--   0        0        0    16125 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-feature-summary-statistics.html
--rw-r--r--   0        0        0    41450 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-profile-summary.html
--rw-r--r--   0        0        0    98500 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in.html
--rw-r--r--   0        0        0   752494 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-library-all-in.html
--rw-r--r--   0        0        0    25371 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs.html
--rw-r--r--   0        0        0    26014 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/html/templates/index.html
--rw-r--r--   0        0        0    18039 2022-10-11 21:07:57.590274 whylogs-1.1.9.dev0/whylogs/viz/notebook_profile_viz.py
--rw-r--r--   0        0        0      410 2022-05-31 19:33:45.932491 whylogs-1.1.9.dev0/whylogs/viz/utils/__init__.py
--rw-r--r--   0        0        0     2422 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/viz/utils/descriptive_stats.py
--rw-r--r--   0        0        0     8654 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/utils/drift_calculations.py
--rw-r--r--   0        0        0     3510 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/utils/frequent_items_calculations.py
--rw-r--r--   0        0        0     2434 2022-07-21 17:22:42.022760 whylogs-1.1.9.dev0/whylogs/viz/utils/histogram_calculations.py
--rw-r--r--   0        0        0     1061 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/utils/html_template_utils.py
--rw-r--r--   0        0        0     9942 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/utils/profile_viz_calculations.py
--rw-r--r--   0        0        0     3480 2022-10-08 17:03:10.607321 whylogs-1.1.9.dev0/whylogs/viz/utils/quantile_stats.py
--rw-r--r--   0        0        0    21582 1970-01-01 00:00:00.000000 whylogs-1.1.9.dev0/setup.py
--rw-r--r--   0        0        0    21013 1970-01-01 00:00:00.000000 whylogs-1.1.9.dev0/PKG-INFO
+-rw-r--r--   0        0        0     3166 2023-06-27 23:30:31.408861 whylogs-1.2.0/DESCRIPTION.md
+-rw-r--r--   0        0        0     5846 2023-06-27 23:31:06.009815 whylogs-1.2.0/pyproject.toml
+-rw-r--r--   0        0        0     1801 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/__init__.py
+-rw-r--r--   0        0        0      347 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/__init__.py
+-rw-r--r--   0        0        0      590 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/annotations.py
+-rw-r--r--   0        0        0      120 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/fugue/__init__.py
+-rw-r--r--   0        0        0     4840 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/fugue/profiler.py
+-rw-r--r--   0        0        0     1997 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/fugue/registry.py
+-rw-r--r--   0        0        0     8157 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/experimental/multi_dataset_logger/__init__.py
+-rw-r--r--   0        0        0      468 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/experimental/multi_dataset_logger/future_util.py
+-rw-r--r--   0        0        0     2119 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/experimental/multi_dataset_logger/message_processor.py
+-rw-r--r--   0        0        0    15693 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/experimental/multi_dataset_logger/multi_dataset_rolling_logger.py
+-rw-r--r--   0        0        0     3964 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/experimental/multi_dataset_logger/time_util.py
+-rw-r--r--   0        0        0     4770 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/logger.py
+-rw-r--r--   0        0        0    19765 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/result_set.py
+-rw-r--r--   0        0        0     9550 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/rolling.py
+-rw-r--r--   0        0        0     2113 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/segment_cache.py
+-rw-r--r--   0        0        0     6333 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/segment_processing.py
+-rw-r--r--   0        0        0      687 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/logger/transient.py
+-rw-r--r--   0        0        0      406 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/pyspark/experimental/__init__.py
+-rw-r--r--   0        0        0     4217 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/pyspark/experimental/profiler.py
+-rw-r--r--   0        0        0     7663 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/pyspark/experimental/segmented_profiler.py
+-rw-r--r--   0        0        0      465 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/reader/__init__.py
+-rw-r--r--   0        0        0      645 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/reader/local.py
+-rw-r--r--   0        0        0      617 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/reader/reader.py
+-rw-r--r--   0        0        0     2073 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/reader/s3.py
+-rw-r--r--   0        0        0      237 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/store/__init__.py
+-rw-r--r--   0        0        0     4566 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/store/local_store.py
+-rw-r--r--   0        0        0     1208 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/store/profile_store.py
+-rw-r--r--   0        0        0      672 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/store/query.py
+-rw-r--r--   0        0        0     5350 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/store/sqlite_store.py
+-rw-r--r--   0        0        0     6128 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/usage_stats/__init__.py
+-rw-r--r--   0        0        0       79 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/whylabs/__init__.py
+-rw-r--r--   0        0        0     7497 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/whylabs/session/config.py
+-rw-r--r--   0        0        0      329 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/whylabs/session/notebook_check.py
+-rw-r--r--   0        0        0     3813 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/whylabs/session/notebook_logger.py
+-rw-r--r--   0        0        0    10646 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/whylabs/session/session_manager.py
+-rw-r--r--   0        0        0      666 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/whylabs/session/session_types.py
+-rw-r--r--   0        0        0      947 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/writer/__init__.py
+-rw-r--r--   0        0        0     2726 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/writer/gcs.py
+-rw-r--r--   0        0        0     1169 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/writer/local.py
+-rw-r--r--   0        0        0     2084 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/writer/mlflow.py
+-rw-r--r--   0        0        0     3408 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/writer/s3.py
+-rw-r--r--   0        0        0    39185 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/writer/whylabs.py
+-rw-r--r--   0        0        0     1217 2023-06-27 23:30:31.460863 whylogs-1.2.0/whylogs/api/writer/writer.py
+-rw-r--r--   0        0        0     1090 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/__init__.py
+-rw-r--r--   0        0        0     3391 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/column_profile.py
+-rw-r--r--   0        0        0      208 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/common.py
+-rw-r--r--   0        0        0     1549 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/configs.py
+-rw-r--r--   0        0        0      455 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/__init__.py
+-rw-r--r--   0        0        0     1798 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/__init__.py
+-rw-r--r--   0        0        0     1103 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/cardinality_metrics.py
+-rw-r--r--   0        0        0     2049 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/condition_counts.py
+-rw-r--r--   0        0        0     2601 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/count_metrics.py
+-rw-r--r--   0        0        0     7063 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/distribution_metrics.py
+-rw-r--r--   0        0        0     2083 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/frequent_items.py
+-rw-r--r--   0        0        0      737 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/multi_metrics.py
+-rw-r--r--   0        0        0     3199 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/factories/types_metrics.py
+-rw-r--r--   0        0        0    30671 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/constraints/metric_constraints.py
+-rw-r--r--   0        0        0    11486 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/dataset_profile.py
+-rw-r--r--   0        0        0     4120 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/datatypes.py
+-rw-r--r--   0        0        0      518 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/errors.py
+-rw-r--r--   0        0        0     2560 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/feature_weights.py
+-rw-r--r--   0        0        0      806 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/input_resolver.py
+-rw-r--r--   0        0        0     1740 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metric_getters.py
+-rw-r--r--   0        0        0      984 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/__init__.py
+-rw-r--r--   0        0        0     4085 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/aggregators.py
+-rw-r--r--   0        0        0     5031 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/column_metrics.py
+-rw-r--r--   0        0        0     6481 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/compound_metric.py
+-rw-r--r--   0        0        0     7615 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/condition_count_metric.py
+-rw-r--r--   0        0        0     1597 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/decorators.py
+-rw-r--r--   0        0        0     4840 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/deserializers.py
+-rw-r--r--   0        0        0     1361 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/maths.py
+-rw-r--r--   0        0        0     6053 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/metric_components.py
+-rw-r--r--   0        0        0    21749 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/metrics.py
+-rw-r--r--   0        0        0     8016 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/multimetric.py
+-rw-r--r--   0        0        0     4517 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/serializers.py
+-rw-r--r--   0        0        0     5504 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/metrics/unicode_range.py
+-rw-r--r--   0        0        0      107 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/model_performance_metrics/__init__.py
+-rw-r--r--   0        0        0     8976 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/model_performance_metrics/confusion_matrix.py
+-rw-r--r--   0        0        0     7445 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/model_performance_metrics/model_performance_metrics.py
+-rw-r--r--   0        0        0     2837 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/model_performance_metrics/regression_metrics.py
+-rw-r--r--   0        0        0     5499 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/predicate_parser.py
+-rw-r--r--   0        0        0    14489 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/preprocessing.py
+-rw-r--r--   0        0        0      335 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/projectors.py
+-rw-r--r--   0        0        0      183 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/proto/__init__.py
+-rw-r--r--   0        0        0      242 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/proto/v0/__init__.py
+-rw-r--r--   0        0        0    12534 2023-06-27 23:31:09.953926 whylogs-1.2.0/whylogs/core/proto/v0/v0_constraints_pb2.py
+-rw-r--r--   0        0        0    20212 2023-06-27 23:31:08.669890 whylogs-1.2.0/whylogs/core/proto/v0/v0_constraints_pb2.pyi
+-rw-r--r--   0        0        0    21343 2023-06-27 23:31:08.669890 whylogs-1.2.0/whylogs/core/proto/v0/v0_messages_pb2.py
+-rw-r--r--   0        0        0    29724 2023-06-27 23:31:08.669890 whylogs-1.2.0/whylogs/core/proto/v0/v0_messages_pb2.pyi
+-rw-r--r--   0        0        0    18521 2023-06-27 23:31:10.129931 whylogs-1.2.0/whylogs/core/proto/v0/v0_summaries_pb2.py
+-rw-r--r--   0        0        0    24739 2023-06-27 23:31:08.669890 whylogs-1.2.0/whylogs/core/proto/v0/v0_summaries_pb2.pyi
+-rw-r--r--   0        0        0    18571 2023-06-27 23:31:08.549886 whylogs-1.2.0/whylogs/core/proto/whylogs_messages_pb2.py
+-rw-r--r--   0        0        0    21840 2023-06-27 23:31:08.549886 whylogs-1.2.0/whylogs/core/proto/whylogs_messages_pb2.pyi
+-rw-r--r--   0        0        0     7350 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/relations.py
+-rw-r--r--   0        0        0    11101 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/resolvers.py
+-rw-r--r--   0        0        0     9526 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/schema.py
+-rw-r--r--   0        0        0      144 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/segment.py
+-rw-r--r--   0        0        0     2343 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/segmentation_partition.py
+-rw-r--r--   0        0        0      826 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/specialized_resolvers.py
+-rw-r--r--   0        0        0     2087 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/stubs.py
+-rw-r--r--   0        0        0      486 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/utils/__init__.py
+-rw-r--r--   0        0        0     3603 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/utils/protobuf_utils.py
+-rw-r--r--   0        0        0     2569 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/utils/stats_calculations.py
+-rw-r--r--   0        0        0      130 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/utils/timestamp_calculations.py
+-rw-r--r--   0        0        0     1602 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/utils/utils.py
+-rw-r--r--   0        0        0      210 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/validators/__init__.py
+-rw-r--r--   0        0        0     4760 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/validators/condition_validator.py
+-rw-r--r--   0        0        0      508 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/validators/validator.py
+-rw-r--r--   0        0        0      214 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/view/__init__.py
+-rw-r--r--   0        0        0     6157 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/view/column_profile_view.py
+-rw-r--r--   0        0        0    17663 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/view/dataset_profile_view.py
+-rw-r--r--   0        0        0     8747 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/core/view/segmented_dataset_profile_view.py
+-rw-r--r--   0        0        0      211 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/__init__.py
+-rw-r--r--   0        0        0     5813 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/base.py
+-rw-r--r--   0        0        0     6087 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/configs.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/descr/__init__.py
+-rw-r--r--   0        0        0     6397 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/descr/ecommerce.rst
+-rw-r--r--   0        0        0     3506 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/descr/employee.rst
+-rw-r--r--   0        0        0    11285 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/descr/weather.rst
+-rw-r--r--   0        0        0    10688 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/ecommerce.py
+-rw-r--r--   0        0        0    10981 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/employee.py
+-rw-r--r--   0        0        0     2349 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/utils.py
+-rw-r--r--   0        0        0    11476 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/datasets/weather.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:30:31.464863 whylogs-1.2.0/whylogs/experimental/__init__.py
+-rw-r--r--   0        0        0     3770 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/constraints_generation/__init__.py
+-rw-r--r--   0        0        0     1105 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/constraints_generation/condition_counts.py
+-rw-r--r--   0        0        0      846 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/constraints_generation/count_metrics.py
+-rw-r--r--   0        0        0     1554 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/constraints_generation/distribution_metrics.py
+-rw-r--r--   0        0        0     1011 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/constraints_generation/frequent_items.py
+-rw-r--r--   0        0        0      685 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/constraints_generation/multi_metrics.py
+-rw-r--r--   0        0        0      973 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/constraints_generation/types_metrics.py
+-rw-r--r--   0        0        0    19692 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/core/metrics/udf_metric.py
+-rw-r--r--   0        0        0    10230 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/core/udf_schema.py
+-rw-r--r--   0        0        0     8861 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/extras/embedding_metric.py
+-rw-r--r--   0        0        0      939 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/extras/matrix_component.py
+-rwxr-xr-x   0        0        0    16737 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/extras/nlp_metric.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/performance_estimation/__init__.py
+-rw-r--r--   0        0        0     1554 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/performance_estimation/estimation_results.py
+-rw-r--r--   0        0        0     8872 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/performance_estimation/estimators.py
+-rw-r--r--   0        0        0     3777 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/experimental/preprocess/embeddings/selectors.py
+-rw-r--r--   0        0        0    10031 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/extras/image_metric.py
+-rw-r--r--   0        0        0       52 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/migration/__init__.py
+-rw-r--r--   0        0        0    15367 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/migration/converters.py
+-rw-r--r--   0        0        0     6959 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/migration/uncompound.py
+-rw-r--r--   0        0        0      296 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/__init__.py
+-rw-r--r--   0        0        0      168 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/configs.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/drift/__init__.py
+-rw-r--r--   0        0        0    21751 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/drift/column_drift_algorithms.py
+-rw-r--r--   0        0        0     1366 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/drift/configs.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/enums/__init__.py
+-rw-r--r--   0        0        0      901 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/enums/enums.py
+-rw-r--r--   0        0        0        0 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/extensions/__init__.py
+-rw-r--r--   0        0        0      114 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/extensions/reports/constraints.py
+-rw-r--r--   0        0        0      272 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/extensions/reports/histograms.py
+-rw-r--r--   0        0        0     2502 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/extensions/reports/html_report.py
+-rw-r--r--   0        0        0      975 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/extensions/reports/profile_summary.py
+-rw-r--r--   0        0        0     3218 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/extensions/reports/summary_drift.py
+-rw-r--r--   0        0        0       38 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/html/.prettierignore
+-rw-r--r--   0        0        0      135 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/html/.prettierrc.yaml
+-rw-r--r--   0        0        0   155568 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/html/css/bootstrap.min.css
+-rw-r--r--   0        0        0    22747 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/html/css/whylogs-styles.css
+-rw-r--r--   0        0        0   160788 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Bold.ttf
+-rw-r--r--   0        0        0    50888 2023-06-27 23:30:31.468863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Bold.woff
+-rw-r--r--   0        0        0    32180 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Bold.woff2
+-rw-r--r--   0        0        0   172144 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-BoldItalic.ttf
+-rw-r--r--   0        0        0    55560 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-BoldItalic.woff
+-rw-r--r--   0        0        0    35476 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-BoldItalic.woff2
+-rw-r--r--   0        0        0   172188 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Italic.ttf
+-rw-r--r--   0        0        0    55728 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Italic.woff
+-rw-r--r--   0        0        0    35144 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Italic.woff2
+-rw-r--r--   0        0        0   161212 2023-06-27 23:30:31.472863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Medium.ttf
+-rw-r--r--   0        0        0    53244 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Medium.woff
+-rw-r--r--   0        0        0    34516 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Medium.woff2
+-rw-r--r--   0        0        0   172380 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-MediumItalic.ttf
+-rw-r--r--   0        0        0    59012 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-MediumItalic.woff
+-rw-r--r--   0        0        0    38404 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-MediumItalic.woff2
+-rw-r--r--   0        0        0   161220 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Regular.ttf
+-rw-r--r--   0        0        0    50936 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Regular.woff
+-rw-r--r--   0        0        0    32192 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Regular.woff2
+-rw-r--r--   0        0        0   161152 2023-06-27 23:30:31.476863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBold.ttf
+-rw-r--r--   0        0        0    53296 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBold.woff
+-rw-r--r--   0        0        0    34744 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBold.woff2
+-rw-r--r--   0        0        0   172396 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.ttf
+-rw-r--r--   0        0        0    58892 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff
+-rw-r--r--   0        0        0    38500 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff2
+-rw-r--r--   0        0        0     3156 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/images/placement-chart.png
+-rw-r--r--   0        0        0     9649 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/images/whylabs-favicon.png
+-rw-r--r--   0        0        0   270687 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/js/d3.min.js
+-rw-r--r--   0        0        0    12606 2023-06-27 23:30:31.480863 whylogs-1.2.0/whylogs/viz/html/js/handlebars.js
+-rw-r--r--   0        0        0    89501 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/js/jquery-3.6.0.min.js
+-rw-r--r--   0        0        0    55927 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/js/whylogs-script.js
+-rw-r--r--   0        0        0    52663 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-for-jupyter-notebook.html
+-rw-r--r--   0        0        0    14235 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-bar-chart.html
+-rw-r--r--   0        0        0    26825 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-constraints-report.html
+-rw-r--r--   0        0        0    14144 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-differenced-chart.html
+-rw-r--r--   0        0        0    15177 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-distribution-chart.html
+-rw-r--r--   0        0        0    18298 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-feature-summary-statistics.html
+-rw-r--r--   0        0        0    41933 2023-06-27 23:30:31.484863 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-profile-summary.html
+-rw-r--r--   0        0        0    98500 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in.html
+-rw-r--r--   0        0        0   752494 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-library-all-in.html
+-rw-r--r--   0        0        0    25371 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/html/templates/index-hbs.html
+-rw-r--r--   0        0        0    26014 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/html/templates/index.html
+-rw-r--r--   0        0        0    21376 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/notebook_profile_viz.py
+-rw-r--r--   0        0        0      410 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/__init__.py
+-rw-r--r--   0        0        0     2466 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/descriptive_stats.py
+-rw-r--r--   0        0        0    12576 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/drift_calculations.py
+-rw-r--r--   0        0        0     3561 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/frequent_items_calculations.py
+-rw-r--r--   0        0        0     2747 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/histogram_calculations.py
+-rw-r--r--   0        0        0     1060 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/html_template_utils.py
+-rw-r--r--   0        0        0    14298 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/profile_viz_calculations.py
+-rw-r--r--   0        0        0     3581 2023-06-27 23:30:31.488864 whylogs-1.2.0/whylogs/viz/utils/quantile_stats.py
+-rw-r--r--   0        0        0     6558 1970-01-01 00:00:00.000000 whylogs-1.2.0/PKG-INFO
```

### Comparing `whylogs-1.1.9.dev0/pyproject.toml` & `whylogs-1.2.0/pyproject.toml`

 * *Files 19% similar despite different names*

```diff
@@ -1,137 +1,170 @@
 [tool.poetry]
 name = "whylogs"
-version = "1.1.9.dev0"
+version = "1.2.0"
 description = "Profile and monitor your ML data pipeline end-to-end"
 authors = ["WhyLabs.ai <support@whylabs.ai>"]
 license = "Apache-2.0"
 homepage = "https://docs.whylabs.ai"
-readme = "README.md"
+readme = "DESCRIPTION.md"
 include = ["whylogs/core/proto/v0/*.py*", "whylogs/core/proto/*.py*"]
 
 
 [tool.poetry.dependencies]
 # core dependencies. Be REALLY mindful when touching this list
 python = ">=3.7.1, <4"
 whylogs-sketching = ">=3.4.1.dev3"
 protobuf = ">=3.19.4"
 importlib-metadata = { version = "<4.3", python = "<3.8" }
-typing-extensions = {version = ">=3.10", markers = "python_version < \"3.11\""}
+typing-extensions = {version = ">=3.10", markers = "python_version < \"4\""}
+whylabs-client = {version = ">=0.5.1, <1"}
+requests = "^2.27"
+types-requests = "^2.30.0.0"
 
 # viz module. Everything after this should be optional
 pybars3 = { version = "^0.9", optional = true }
 ipython = { version = "*", optional = true }
-scipy = { version = ">=1.5", python = "<3.11", optional = true }
+scipy = [
+  { version = ">=1.5", python = "<3.11", optional = true },
+  { version = ">=1.9.2", python = ">=3.11", optional = true }
+]
+numpy = [
+  { version = "*", python = "<3.11", optional = true },
+  { version = ">=1.23.2", python = ">=3.11", optional = true }
+]
 
 # datasets module.
 pandas = { version = "*", optional = true}
 
 # Doc dependencies
 sphinx = { version = "*", optional = true }
 sphinx-autoapi = { version = "*", optional = true }
 sphinx-copybutton = { version = "^0.5.0", optional = true }
 myst-parser = { extras = ["sphinx"], version = "^0.17.2", optional = true }
 furo = { version = "^2022.3.4", optional = true }
 sphinx-autobuild = { version = "^2021.3.14", optional = true }
 sphinxext-opengraph = { version = "^0.6.3", optional = true }
-sphinx-inline-tabs = { version = "*", optional = true }
+sphinx-inline-tabs = { version = "*", python = ">=3.8,<4", optional = true }
 ipython_genutils = {version = "^0.2.0", optional = true}
 nbsphinx = {version = "^0.8.9", optional = true}
 nbconvert = {version = "^7.0.0", optional = true}
 
 # Integrations dependencies
 boto3 = {version = "^1.22.13", optional = true }
-whylabs-client = {version = "0.4.0.dev0", optional = true}
 mlflow-skinny = {version = "^1.26.1", optional = true}
 google-cloud-storage = {version = "^2.5.0", optional = true}
 
 # Pyspark related dependencies
-pyarrow = {version = "^8.0.0", optional = true}
+pyarrow = {version = ">=8.0.0, <13", optional = true}
 pyspark = {version = "^3.0.0", optional = true}
 
 # Image support related dependencies
 Pillow = {version = "^9.2.0", optional = true}
 
+# Embeddings support related dependencies
+scikit-learn = [
+  { version = "^1.0.2", python = "<3.11", optional = true },
+  { version = ">=1.1.2, <2", python = ">=3.11", optional = true }
+]
+
 # Fugue related dependencies
-fugue = {version = "^0.7.3", optional = true}
-requests = "^2.27"
+fugue = {version = "^0.8.1", optional = true}
+platformdirs = "^3.5.0"
 
 [tool.poetry.dev-dependencies]
 2to3 = "^1.0"
-black = { version = "*", allow-prereleases = true }
+black = { version = "^22.10.0", allow-prereleases = true }
 bump2version = "^1.0.1"
 flake8 = "^5"
 isort = "^5.6"
 mypy = ">=0.942,<1"
 pre-commit = "^2.8"
-pytest = "^6.2"
-pytest-cov = "^3"
+pytest = "^7.2.0"
+pytest-cov = ">=3"
 pytest-mock = "^3.3"
+pytest-spark = ">=0.6.0"
 mistune = ">=2.0.4"
 papermill = "^2.4.0"
 autoflake = "^1.4"
 mypy-protobuf = ">=3.2.0"
 types-protobuf = ">=0.1.14"
 pandas = "*"
 pandas-stubs = "*"
 ipykernel = ">=6.11" # for developing in Jupyter notebook
 types-python-dateutil = "^2.8.12"
-moto = "^3.1.9"
+moto = "^4.1.6"
 twine = "^4.0.1"
 gcp-storage-emulator = "^2022.6.11"
+types-urllib3 = "^1.26.25.5"
 
 [tool.poetry.extras]
 docs = [
     "sphinx",
     "sphinx-autoapi",
     "sphinx-autobuild",
     "furo",
     "sphinx-copybutton",
     "myst-parser",
     "sphinx-inline-tabs",
     "sphinxext-opengraph",
-    "sphinx-autodoc",
-    "sphinx-autodoc-typehints",
     "nbsphinx",
     "nbconvert",
     "ipython_genutils",
 ]
 viz = [
     "ipython",
     "pybars3",
+    "numpy",
     "scipy",
     "Pillow",
-    "whylabs-client",
-    "requests",
 ]
 spark = [
     "pyarrow",
     "pyspark",
 ]
 datasets = [
   "pandas",
 ]
 gcs = [
   "google-cloud-storage",
 ]
 s3 = [
   "boto3"
 ]
-whylabs = [
-  "whylabs-client", "requests"
-]
 mlflow = [
   "mlflow-skinny"
 ]
 image = [
   "Pillow"
 ]
 fugue = [
   "fugue",
 ]
+embeddings = [
+  "numpy",
+  "scikit-learn",
+]
+all = [
+  "scikit-learn",
+  "fugue",
+  "Pillow",
+  "mlflow-skinny",
+  "boto3",
+  "google-cloud-storage",
+  "pandas",
+  "pyarrow",
+  "pyspark",
+  "ipython",
+  "pybars3",
+  "numpy",
+  "scipy",
+]
+
+[tool.poetry.group.dev.dependencies]
+types-urllib3 = "^1.26.25.5"
 
 [build-system]
 requires = ["poetry-core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
 
 [tool.isort]
 profile = "black"
@@ -176,14 +209,24 @@
 )
 '''
 
 [tool.pytest.ini_options]
 addopts = "-q"
 minversion = "6.0"
 testpaths = ["tests"]
+spark_options = '''
+  spark.master: local[*]
+  spark.sql.catalogImplementation: in-memory
+  spark.sql.shuffle.partitions: 4
+  spark.default.parallelism: 4
+  spark.executor.cores: 4
+  spark.sql.execution.arrow.pyspark.enabled: true
+  spark.sql.execution.arrow.enabled: false
+  spark.sql.adaptive.enabled: false
+'''
 
 [tool.black]
 line-length = 120
 target-version = ['py37']
 include = '\.pyi?$'
 exclude = '''
 (
```

### Comparing `whylogs-1.1.9.dev0/whylogs/__init__.py` & `whylogs-1.2.0/whylogs/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -23,14 +23,15 @@
     logger,
     profiling,
     read,
     reader,
     write,
 )
 from .api.usage_stats import emit_usage as __emit_usage_stats
+from .api.whylabs import init
 from .core import DatasetProfileView
 from .migration.converters import v0_to_v1_view
 
 
 def package_version(package: str = __package__) -> str:
     """Calculate version number based on pyproject.toml"""
     try:
@@ -58,10 +59,11 @@
     logger,
     read,
     reader,
     write,
     profiling,
     v0_to_v1_view,
     __version__,
+    init,
 ]
 
 __emit_usage_stats("import")
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/annotations.py` & `whylogs-1.2.0/whylogs/api/annotations.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/api/fugue/profiler.py` & `whylogs-1.2.0/whylogs/api/fugue/profiler.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,56 +1,44 @@
-from datetime import datetime
+from datetime import datetime, timezone
 from functools import reduce
 from typing import Any, Dict, Iterable, List, Optional
 
+import fugue.api as fa
 import pandas as pd
-from fugue import (
-    FugueWorkflow,
-    PartitionSpec,
-    Schema,
-    make_execution_engine,
-    transform,
-    transformer,
-)
-from fugue.dataframe.utils import (
-    normalize_dataframe_column_names,
-    rename_dataframe_column_names,
-)
+from fugue import PartitionSpec, Schema, transformer
 
 import whylogs as why
+from whylogs.core import DatasetSchema
 from whylogs.core.view.column_profile_view import ColumnProfileView
 from whylogs.core.view.dataset_profile_view import DatasetProfileView
 
 _COL_NAME_FIELD = "__whylogs_fugue_col_name"
 _COL_PROFILE_FIELD = "__whylogs_fugue_col_profile"
 DF_PROFILE_FIELD = "__whylogs_df_profile_view"
 
 
 def fugue_profile(
     df: Any,
     dataset_timestamp: Optional[datetime] = None,
     creation_timestamp: Optional[datetime] = None,
     partition: Any = None,
     profile_cols: Optional[List[str]] = None,
+    schema: Optional[DatasetSchema] = None,
     as_local: bool = True,
     profile_field: str = DF_PROFILE_FIELD,
     engine: Any = None,
     engine_conf: Any = None,
     **kwargs,
 ) -> Any:
-    if not isinstance(df, str):
-        df, renames = normalize_dataframe_column_names(df)
-    else:
-        renames = {}
     profiler = _FugueProfiler(
         partition,
         profile_cols,
-        renames=renames,
         dataset_timestamp=dataset_timestamp,
         creation_timestamp=creation_timestamp,
+        schema=schema,
         profile_field=profile_field,
     )
     if len(profiler._by) == 0:
         assert len(kwargs) == 0, ValueError("Profiling without partition can not take extra arguments")
         return profiler.transform_no_logical_partition(df, engine=engine, engine_conf=engine_conf)
     return profiler.transform_with_logical_partition(
         df, engine=engine, engine_conf=engine_conf, as_local=as_local, **kwargs
@@ -58,82 +46,74 @@
 
 
 class _FugueProfiler:
     def __init__(
         self,
         partition,
         cols,
-        renames: Dict[str, Any],
         dataset_timestamp: Optional[datetime] = None,
         creation_timestamp: Optional[datetime] = None,
+        schema: Optional[DatasetSchema] = None,
         profile_field: str = DF_PROFILE_FIELD,
     ):
-        now = datetime.utcnow()
+        now = datetime.now(timezone.utc)
 
         self._dataset_timestamp = dataset_timestamp or now
         self._creation_timestamp = creation_timestamp or now
-        self._cols_to_orig = renames
-        self._orig_to_cols = {v: k for k, v in renames.items()}
 
         part = PartitionSpec(partition)
-        self._by = [self._orig_to_cols.get(x, x) for x in part.partition_by]
+        self._by = part.partition_by
         self._partition = PartitionSpec(part, by=self._by)
         self._cols = cols
         self._profile_field = profile_field
         self._profile_schema = Schema([(profile_field, bytes)])
+        self._schema = schema
 
     def to_col_profiles(self, df: pd.DataFrame) -> Iterable[Dict[str, Any]]:
-        if len(self._cols_to_orig) > 0:
-            df = df.rename(columns=self._cols_to_orig)
-        res = why.log(df[self._cols] if self._cols is not None else df)
+        res = why.log(df[self._cols] if self._cols is not None else df, schema=self._schema)
         for col_name, col_profile in res.view().get_columns().items():
             yield {_COL_NAME_FIELD: col_name, _COL_PROFILE_FIELD: col_profile.serialize()}
 
     def merge_col_profiles(self, df: pd.DataFrame) -> pd.DataFrame:
         merged_profile: ColumnProfileView = reduce(
             lambda acc, x: acc.merge(x), df[_COL_PROFILE_FIELD].apply(lambda x: ColumnProfileView.deserialize(x))
         )
         return df.head(1).assign(**{_COL_PROFILE_FIELD: merged_profile.serialize()})
 
-    def merge_to_view(self, col_profiles: List[Dict[str, Any]]) -> Iterable[Dict[str, Any]]:
-        profile_view = DatasetProfileView(
+    def merge_to_view(self, col_profiles: Iterable[Dict[str, Any]]) -> DatasetProfileView:
+        return DatasetProfileView(
             columns={
                 row[_COL_NAME_FIELD]: ColumnProfileView.from_bytes(row[_COL_PROFILE_FIELD]) for row in col_profiles
             },
             dataset_timestamp=self._dataset_timestamp,
             creation_timestamp=self._creation_timestamp,
         )
-        yield {self._profile_field: profile_view.serialize()}
 
     def profile_partition(self, df: pd.DataFrame) -> pd.DataFrame:
-        if len(self._cols_to_orig) > 0:
-            pdf = df.rename(columns=self._cols_to_orig)
-        else:
-            pdf = df
-        res = why.log(pdf[self._cols] if self._cols is not None else pdf).view().serialize()
+        res = why.log(df[self._cols] if self._cols is not None else df, schema=self._schema).view().serialize()
         return df.head(1)[self._by].assign(**{self._profile_field: res})  # type: ignore
 
     # ---------------- Starting Fugue related logic
 
     def transform_no_logical_partition(self, df: Any, engine: Any, engine_conf: Any) -> DatasetProfileView:
-        dag = FugueWorkflow()
-        input_df = dag.load(df) if isinstance(df, str) else dag.df(df)
-        cols = input_df.partition(self._partition).transform(
-            self.to_col_profiles,
-            schema=[(_COL_NAME_FIELD, str), (_COL_PROFILE_FIELD, bytes)],
-        )
-        merged_cols = cols.partition_by(_COL_NAME_FIELD).transform(self.merge_col_profiles, schema="*")
-        result = merged_cols.process(self.merge_to_view, schema=self._profile_schema)
-        result.yield_dataframe_as("result", as_local=True)
-        engine = make_execution_engine(engine, engine_conf)
-        return DatasetProfileView.deserialize(dag.run(engine)["result"].as_array()[0][0])
+        with fa.engine_context(engine, engine_conf):
+            input_df = fa.load(df, as_fugue=True) if isinstance(df, str) else fa.as_fugue_df(df)
+            cols = fa.transform(
+                input_df,
+                self.to_col_profiles,
+                schema=[(_COL_NAME_FIELD, str), (_COL_PROFILE_FIELD, bytes)],
+                partition=self._partition,
+            )
+            merged_cols = fa.transform(
+                cols, self.merge_col_profiles, schema="*", partition=_COL_NAME_FIELD, as_local=True
+            )
+            return self.merge_to_view(fa.as_dict_iterable(merged_cols))
 
     def transform_with_logical_partition(self, df: Any, engine: Any, engine_conf: Any, **kwargs: Any) -> Any:
-        res = transform(
+        return fa.transform(
             df,
             transformer(lambda pdf: pdf.schema.extract(self._by) + self._profile_schema)(self.profile_partition),
             partition=self._partition,
             engine=engine,
             engine_conf=engine_conf,
             **kwargs,
         )
-        return rename_dataframe_column_names(res, self._cols_to_orig)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/logger/logger.py` & `whylogs-1.2.0/whylogs/api/logger/logger.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 
 from whylogs.api.logger.result_set import ProfileResultSet, ResultSet
 from whylogs.api.logger.segment_processing import segment_processing
 from whylogs.api.store import ProfileStore
 from whylogs.api.writer import Writer, Writers
 from whylogs.core import DatasetProfile, DatasetSchema
 from whylogs.core.errors import LoggingError
+from whylogs.core.input_resolver import _pandas_or_dict
 from whylogs.core.stubs import pd
 
 logger = logging.getLogger(__name__)
 
 
 class BasicCache(object):
     _cache: Dict[DatasetSchema, DatasetProfile] = {}
@@ -28,14 +29,16 @@
 class Logger(ABC):
     def __init__(self, schema: Optional[DatasetSchema] = None):
         self._is_closed = False
         self._schema = schema
         self._writers: List[Writer] = []
         atexit.register(self.close)
         self._store_list: List[ProfileStore] = []
+        self._segment_cache = None
+        self._metadata: Optional[Dict[str, str]] = None
 
     def check_writer(self, _: Writer) -> None:
         """Checks if a writer is configured correctly for this class"""
 
     def append_writer(self, name: Optional[str] = None, *, writer: Optional[Writer] = None, **kwargs: Any) -> None:
         if name is None and writer is None:
             raise ValueError("Must specify either the writer name or a Writer object")
@@ -54,42 +57,66 @@
     @abstractmethod
     def _get_matching_profiles(
         self,
         obj: Any = None,
         *,
         pandas: Optional[pd.DataFrame] = None,
         row: Optional[Dict[str, Any]] = None,
+        schema: Optional[DatasetSchema] = None,
     ) -> List[DatasetProfile]:
         pass
 
     def log(
         self,
         obj: Any = None,
         *,
         pandas: Optional[pd.DataFrame] = None,
         row: Optional[Dict[str, Any]] = None,
+        schema: Optional[DatasetSchema] = None,
+        timestamp_ms: Optional[int] = None,  # Not the dataset timestamp, but the timestamp of the data
+        name: Optional[str] = None,
     ) -> ResultSet:
+        """
+        Args:
+            timestamp_ms: The timestamp of the data being logged. This defaults to now if it isn't provided.
+             This is used to determine what the dataset timestamp should be. For an hourly model, the dataset
+             timestamp will end up being the start of the hour of the provided timestamp_ms, UTC.
+        """
         if self._is_closed:
             raise LoggingError("Cannot log to a closed logger")
         if obj is None and pandas is None and row is None:
             # TODO: check for shell environment and emit more verbose error string to let user know how to correct.
             raise LoggingError("log() was called without passing in any input!")
+        if name is not None:
+            if self._metadata is None:
+                self._metadata = dict()
+            self._metadata["name"] = name
+        active_schema = schema or self._schema
+        if active_schema:
+            pandas, row = _pandas_or_dict(obj, pandas, row)
+            obj = None
+            pandas, row = active_schema._run_udfs(pandas, row)
 
         # If segments are defined use segment_processing to return a SegmentedResultSet
-        if self._schema and self._schema.segments:
-            return segment_processing(self._schema, obj, pandas, row)
+        if active_schema and active_schema.segments:
+            return segment_processing(active_schema, obj, pandas, row, self._segment_cache)
 
-        profiles = self._get_matching_profiles(obj, pandas=pandas, row=row)
+        profiles = self._get_matching_profiles(obj, pandas=pandas, row=row, schema=active_schema)
 
         for prof in profiles:
-            prof.track(obj, pandas=pandas, row=row)
+            prof.track(obj, pandas=pandas, row=row, execute_udfs=False)
+            prof._metadata
 
-        return ProfileResultSet(profiles[0])
+        first_profile = profiles[0]
+        if name is not None:
+            if first_profile._metadata is None:
+                first_profile._metadata = dict()
+            first_profile._metadata["name"] = name
+        return ProfileResultSet(first_profile)
 
-    @abstractmethod
     def close(self) -> None:
         self._is_closed = True
 
     def __enter__(self) -> "Logger":
         return self
 
     def __exit__(self, exception_type: Any, exception_value: Any, traceback: Any) -> None:
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/logger/rolling.py` & `whylogs-1.2.0/whylogs/api/logger/rolling.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,34 +1,38 @@
 import atexit
 import logging
 import math
 import os
 import time
-from datetime import datetime
+from datetime import datetime, timezone
 from threading import Timer
-from typing import Any, Callable, Dict, List, Optional
+from typing import Any, Callable, Dict, List, Optional, Type
 
 from typing_extensions import Literal
 
 from whylogs.api.logger.logger import Logger
+from whylogs.api.logger.result_set import ProfileResultSet, ResultSet
+from whylogs.api.logger.segment_cache import SegmentCache
 from whylogs.api.writer import Writer
 from whylogs.core import DatasetProfile, DatasetProfileView, DatasetSchema
 from whylogs.core.stubs import pd
+from whylogs.core.view.segmented_dataset_profile_view import SegmentedDatasetProfileView
 
 logger = logging.getLogger(__name__)
 
 
 class Scheduler(object):
     """
     Multithreading scheduler.
 
     Schedule a function to be called repeatedly based on a schedule.
     """
 
-    _timer: Timer
+    _TIMER: Type = Timer
+    _timer: Any  # Timer
 
     def __init__(self, initial: float, interval: float, function: Callable, *args: Any, **kwargs: Any):
         self.initial = initial
         self._ran_initial = False
         self.interval = interval
         self.function = function
         self.args = args
@@ -43,15 +47,15 @@
 
     def start(self) -> None:
         if not self.is_running:
             interval = self.interval
             if not self._ran_initial:
                 interval = self.initial
                 self._ran_initial = True
-            self._timer = Timer(interval, self._run)
+            self._timer = Scheduler._TIMER(interval, self._run)
             self._timer.start()
             self.is_running = True
 
     def stop(self) -> None:
         self._timer.cancel()
         self.is_running = False
 
@@ -68,26 +72,28 @@
         interval: int = 1,
         when: Literal["S", "M", "H", "D"] = "H",
         utc: bool = False,
         aligned: bool = True,
         fork: bool = False,
         skip_empty: bool = False,
         callback: Optional[Callable[[Writer, DatasetProfileView, str], None]] = None,
+        metadata: Optional[Dict[str, str]] = None,
     ):
         super().__init__(schema)
         if base_name is None:
             base_name = "profile"
         if file_extension is None:
             file_extension = ".bin"
 
         self.file_extension = file_extension
         self.base_name = base_name
         self.aligned = aligned
         self.fork = fork
         self.skip_empty = skip_empty
+        self._metadatay = metadata
 
         # base on TimedRotatingFileHandler
         self.when = when.upper()
         if self.when == "S":
             self.interval = 1  # one second
             self.suffix = "%Y-%m-%d_%H-%M-%S"
         elif self.when == "M":
@@ -100,18 +106,21 @@
             self.interval = 60 * 60 * 24  # one day
             self.suffix = "%Y-%m-%d"
         self.interval = self.interval * interval  # multiply by units requested
         self.utc = utc
 
         now = time.time()
         self._current_batch_timestamp = self._compute_current_batch_timestamp(now)
+        if schema and schema.segments:
+            self._segment_cache = SegmentCache(schema)
 
         self._current_profile: DatasetProfile = DatasetProfile(
             schema=schema,
-            dataset_timestamp=datetime.utcfromtimestamp(self._current_batch_timestamp),
+            dataset_timestamp=datetime.fromtimestamp(self._current_batch_timestamp, timezone.utc),
+            metadata=self._metadata,
         )
 
         initial_run_after = (self._current_batch_timestamp + self.interval) - now
         if initial_run_after <= 0:
             logger.error(
                 "Negative initial run after. This shouldn't happen so something went wrong with the clock here"
             )
@@ -131,31 +140,53 @@
             now = time.time()
         rounded_now = int(now)
         if self.aligned:
             return int(math.floor((rounded_now - 1) / self.interval)) * self.interval + self.interval
         return rounded_now
 
     def _get_matching_profiles(
-        self, obj: Any = None, *, pandas: Optional[pd.DataFrame] = None, row: Optional[Dict[str, Any]] = None
+        self,
+        obj: Any = None,
+        *,
+        pandas: Optional[pd.DataFrame] = None,
+        row: Optional[Dict[str, Any]] = None,
+        schema: Optional[DatasetSchema] = None,
     ) -> List[DatasetProfile]:
+        if schema and schema is not self._schema:
+            raise ValueError(
+                "You cannot pass a DatasetSchema to an instance of TimedRollingLogger.log(),"
+                "because schema is set once when instantiated, please use TimedRollingLogger(schema) instead."
+            )
         return [self._current_profile]
 
     def _do_rollover(self) -> None:
         if self._is_closed:
             return
-        old_profile = self._current_profile
 
         self._current_batch_timestamp = self._compute_current_batch_timestamp()
-        dataset_timestamp = datetime.utcfromtimestamp(self._current_batch_timestamp)
+        dataset_timestamp = datetime.fromtimestamp(self._current_batch_timestamp, tz=timezone.utc)
+
+        if self._segment_cache:
+            self._flush(self._segment_cache.flush(dataset_timestamp))
+            return
+
+        old_profile = self._current_profile
+
         self._current_profile = DatasetProfile(
-            schema=self._schema,
-            dataset_timestamp=dataset_timestamp,
+            schema=self._schema, dataset_timestamp=dataset_timestamp, metadata=self._metadata
         )
 
-        self._flush(old_profile)
+        while old_profile.is_active:
+            time.sleep(1)
+
+        if self.skip_empty and old_profile.is_empty:
+            logger.debug("skip_empty is set for profile. Skipping empty profile.")
+            return
+
+        self._flush(ProfileResultSet(old_profile))
 
     def _get_time_tuple(self) -> time.struct_time:
         if self.utc:
             time_tuple = time.gmtime(self._current_batch_timestamp)
         else:
             time_tuple = time.localtime(self._current_batch_timestamp)
             current_time = int(time.time())
@@ -166,48 +197,66 @@
                 if dst_now:
                     addend = 3600
                 else:
                     addend = -3600
                 time_tuple = time.localtime(self._current_batch_timestamp + addend)
         return time_tuple
 
-    def _flush(self, profile: DatasetProfile) -> None:
-        if profile is None:
+    def _flush(self, results: ResultSet) -> None:
+        if results is None:
+            logger.debug("The result is None, skipping flush of result set.")
+            return
+        if results.count == 0:
+            logger.debug("The result's count is zero, skipping flush of result set.")
             return
-        if self.skip_empty and profile.is_empty:
-            logger.debug("skip_empty is set. Skipping empty profiles")
+        profiles = results.get_writables()
+        if profiles is None:
+            logger.debug("The result set's writable is None, skipping flush of result set.")
             return
+        number_of_profiles = len(profiles)
+        if number_of_profiles == 0:
+            logger.debug("The result set's writable list has length zero, skipping flush of result set.")
+            return
+        logger.debug(f"about to write {number_of_profiles} profiles.")
 
         pid = 0
         if self.fork:
             pid = os.fork()
 
         if pid > 0:
             logger.debug("Forked child process. Child process ID: %d", pid)
         else:
             if self.fork:
                 logger.debug("In child process")
             else:
                 logger.debug("Didn't fork. Writing in the same process")
 
             time_tuple = self._get_time_tuple()
-            timed_filename = f"{self.base_name}.{time.strftime(self.suffix, time_tuple)}{self.file_extension}"
 
-            logging.debug("Writing out put with timed_filename: %s", timed_filename)
+            profile_count = 0
+            for profile in profiles:
+                has_segments = isinstance(profile, SegmentedDatasetProfileView)
+                if has_segments:
+                    timed_filename = f"{self.base_name}.{time.strftime(self.suffix, time_tuple)}_{profile.get_segment_string()}{self.file_extension}"
+                else:
+                    timed_filename = f"{self.base_name}.{time.strftime(self.suffix, time_tuple)}{self.file_extension}"
+                logging.debug("Writing out put with timed_filename: %s", timed_filename)
 
-            while profile.is_active:
-                time.sleep(1)
+                profile_count = profile_count + 1
+                logger.debug(f"Writing profile {profile_count} of {number_of_profiles}")
 
-            for store in self._store_list:
-                store.write(profile_view=profile.view(), profile_name=self.base_name)
+                for store in self._store_list:
+                    store.write(profile_view=profile, dataset_id=self.base_name)
 
-            for w in self._writers:
-                w.write(file=profile.view(), dest=timed_filename)
-                if self._callback and callable(self._callback):
-                    self._callback(w, profile.view(), timed_filename)
+                for w in self._writers:
+                    w.write(file=profile, dest=timed_filename)
+                    if self._callback and callable(self._callback):
+                        self._callback(w, profile, timed_filename)
+                if not self._writers and self._callback and callable(self._callback):
+                    self._callback(None, profile, timed_filename)
 
     def close(self) -> None:
         logging.debug("Closing the writer")
         if not self._is_closed:
             self._scheduler.stop()
             self._do_rollover()
-        self._is_closed: bool = True
+        super(TimedRollingLogger, self).close()
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/logger/segment_processing.py` & `whylogs-1.2.0/whylogs/api/logger/segment_processing.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 import logging
 from typing import Any, Dict, Iterable, Iterator, List, Mapping, Optional, Tuple
 
 from whylogs.api.logger.result_set import SegmentedResultSet
-from whylogs.api.store.profile_store import ProfileStore
+from whylogs.api.logger.segment_cache import SegmentCache
 from whylogs.core import DatasetSchema
 from whylogs.core.dataset_profile import DatasetProfile
 from whylogs.core.input_resolver import _pandas_or_dict
 from whylogs.core.segment import Segment
 from whylogs.core.segmentation_partition import SegmentationPartition, SegmentFilter
 from whylogs.core.stubs import pd
 
@@ -16,53 +16,58 @@
 
 
 def _process_segment(
     segmented_data: Any,
     segment_key: Segment,
     segments: Dict[Segment, Any],
     schema: DatasetSchema,
-    store: Optional[ProfileStore] = None,
+    segment_cache: Optional[SegmentCache] = None,
 ):
     profile = None
-    if store:
-        profile = store.get_matching_profiles(segmented_data, segment=segment_key)
+    if segment_cache:
+        profile = segment_cache.get_or_create_matching_profile(segment_key)
 
     if profile is None:
         profile = DatasetProfile(schema)
 
-    profile.track(segmented_data)
+    profile.track(segmented_data, execute_udfs=False)
     segments[segment_key] = profile
 
 
+def _get_segment_from_group_key(group_key, partition_id) -> Tuple[str, ...]:
+    if isinstance(group_key, str):
+        segment_tuple_key: Tuple[str, ...] = (group_key,)
+    elif isinstance(group_key, (List, Iterable, Iterator)):
+        segment_tuple_key = tuple(str(k) for k in group_key)
+    else:
+        segment_tuple_key = (str(group_key),)
+
+    return Segment(segment_tuple_key, partition_id)
+
+
 def _process_simple_partition(
     partition_id: str,
     schema: DatasetSchema,
     segments: Dict[Segment, Any],
     columns: List[str],
     pandas: Optional[pd.DataFrame] = None,
     row: Optional[Mapping[str, Any]] = None,
-    profile_cache: Optional[ProfileStore] = None,
+    segment_cache: Optional[SegmentCache] = None,
 ):
     if pandas is not None:
         # simple means we can segment on column values
         grouped_data = pandas.groupby(columns)
         for group in grouped_data.groups.keys():
             pandas_segment = grouped_data.get_group(group)
-            if isinstance(group, str):
-                segment_tuple_key: Tuple[str, ...] = (group,)
-            elif isinstance(group, (List, Iterable, Iterator)):
-                segment_tuple_key = tuple(str(k) for k in group)
-            else:
-                segment_tuple_key = (str(group),)
-            segment_key = Segment(segment_tuple_key, partition_id)
-            _process_segment(pandas_segment, segment_key, segments, schema, profile_cache)
+            segment_key = _get_segment_from_group_key(group, partition_id)
+            _process_segment(pandas_segment, segment_key, segments, schema, segment_cache)
     elif row:
         # TODO: consider if we need to combine with the column names
         segment_key = Segment(tuple(str(row[element]) for element in columns), partition_id)
-        _process_segment(row, segment_key, segments, schema, profile_cache)
+        _process_segment(row, segment_key, segments, schema, segment_cache)
 
 
 def _filter_inputs(
     filter: SegmentFilter, pandas: Optional[pd.DataFrame] = None, row: Optional[Mapping[str, Any]] = None
 ) -> Tuple[Optional[pd.DataFrame], Optional[Dict[str, Any]]]:
     assert (
         filter.filter_function or filter.query_string
@@ -80,40 +85,51 @@
         elif filter.query_string:
             raise ValueError(
                 "SegmentFilter query string not supported when logging rows, either don't specify a filter or implement the filter.filter_function"
             )
     return (filtered_pandas, filtered_row)
 
 
+def _grouped_dataframe(partition: SegmentationPartition, pandas: pd.DataFrame):
+    columns = partition.mapper.col_names if partition.mapper else None
+    if not columns:
+        raise ValueError(
+            "Please use column segmentation, there are no columns defined and ColumnMapperFunction not yet supported."
+        )
+    grouped_data = pandas.groupby(columns)
+    return grouped_data
+
+
 def _log_segment(
     partition: SegmentationPartition,
     schema: DatasetSchema,
     obj: Any = None,
     pandas: Optional[pd.DataFrame] = None,
     row: Optional[Mapping[str, Any]] = None,
-    store: Optional[ProfileStore] = None,
+    segment_cache: Optional[SegmentCache] = None,
 ) -> Dict[Segment, Any]:
     segments: Dict[Segment, Any] = {}
     pandas, row = _pandas_or_dict(obj, pandas, row)
     if partition.filter:
         pandas, row = _filter_inputs(partition.filter, pandas, row)
     if partition.simple:
         columns = partition.mapper.col_names if partition.mapper else None
         if columns:
-            _process_simple_partition(partition.id, schema, segments, columns, pandas, row, store)
+            _process_simple_partition(partition.id, schema, segments, columns, pandas, row, segment_cache)
     else:
         raise NotImplementedError("custom mapped segments not yet implemented")
     return segments
 
 
 def segment_processing(
     schema: DatasetSchema,
     obj: Any = None,
     pandas: Optional[pd.DataFrame] = None,
     row: Optional[Dict[str, Any]] = None,
+    segment_cache: Optional[SegmentCache] = None,
 ) -> SegmentedResultSet:
     number_of_partitions = len(schema.segments)
     logger.info(f"The specified schema defines segments with {number_of_partitions} partitions.")
     assert not (
         number_of_partitions > _MAX_SEGMENT_PARTITIONS
     ), f"Attempt to process {number_of_partitions} partitions is larger than the max of {_MAX_SEGMENT_PARTITIONS}, use a lower number of partitions"
     segmented_profiles = dict()
@@ -126,12 +142,12 @@
         if segment_partition.filter:
             # TODO segments filter
             logger.debug(f"{partition_name}: defines filter ({segment_partition.filter})")
         if segment_partition.mapper:
             logger.debug(
                 f"{partition_name}: defines mapper on colums ({segment_partition.mapper.col_names}) and id ({segment_partition.mapper.id})"
             )
-        partition_segments = _log_segment(segment_partition, schema, obj, pandas, row)
+        partition_segments = _log_segment(segment_partition, schema, obj, pandas, row, segment_cache)
         segmented_profiles[segment_partition.id] = partition_segments
         segment_partitions.append(segment_partition)
         logger.debug(f"Done profiling for partition with name({partition_name})")
     return SegmentedResultSet(segments=segmented_profiles, partitions=segment_partitions)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/reader/local.py` & `whylogs-1.2.0/whylogs/api/reader/local.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/api/reader/reader.py` & `whylogs-1.2.0/whylogs/api/reader/reader.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/api/reader/s3.py` & `whylogs-1.2.0/whylogs/api/reader/s3.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 from tempfile import NamedTemporaryFile
 from typing import Optional
 
 import boto3
+from botocore.client import BaseClient
 
 from whylogs import ResultSet
 from whylogs.api.reader.reader import Reader
 
 
 class S3Reader(Reader):
     """
@@ -30,24 +31,30 @@
     ```python
     import whylogs as why
 
     profile = why.reader("s3").option(bucket_name="my_bucket", object_name="my/object.bin").read()
     ```
     """
 
-    def __init__(self, object_name: Optional[str] = None, bucket_name: Optional[str] = None):
-        self.s3_client = boto3.client("s3")
+    def __init__(
+        self,
+        object_name: Optional[str] = None,
+        bucket_name: Optional[str] = None,
+        s3_client: Optional[BaseClient] = None,
+    ):
+        self.s3_client = s3_client or boto3.client("s3")
         self.object_name = object_name or None
         self.bucket_name = bucket_name or ""
 
     def read(self, **kwargs) -> ResultSet:
         with NamedTemporaryFile() as tmp_file:
             self.s3_client.download_file(Bucket=self.bucket_name, Key=self.object_name, Filename=tmp_file.name)
             tmp_file.flush()
             result_set = self.get_file_from_path(path=tmp_file.name)
         return result_set
 
-    def option(self, object_name: Optional[str] = None, bucket_name: Optional[str] = None) -> None:
+    def option(self, object_name: Optional[str] = None, bucket_name: Optional[str] = None) -> "S3Reader":
         if object_name is not None:
             self.object_name = object_name
         if bucket_name is not None:
             self.bucket_name = bucket_name
+        return self
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/store/local_store.py` & `whylogs-1.2.0/whylogs/api/store/local_store.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,31 +1,31 @@
 import logging
 import os
 import uuid
-from datetime import datetime
+from datetime import datetime, timezone
 from functools import reduce
 from glob import glob
 from typing import List, Optional, Union
 
 import whylogs as why
 from whylogs.api.store.profile_store import ProfileStore
-from whylogs.api.store.query import DateQuery, ProfileNameQuery
+from whylogs.api.store.query import DatasetIdQuery, DateQuery
 from whylogs.api.writer.local import LocalWriter
 from whylogs.core import DatasetProfileView
 
 DEFAULT_DIR = "profile_store/"
 logger = logging.getLogger(__name__)
 
 
 class LocalStore(ProfileStore):
     """
     The LocalStore is the implementation of the base :class:ProfileStore
     that will manage reading and writing profiles on the local file system.
 
-    In order to instantiate the object, you will need to define a profile_name,
+    In order to instantiate the object, you will need to define a dataset_id,
     which is related to the name of the model or dataset you're profiling.
     To properly use the LocalStore to generate files, you should append it
     to your existing Rolling Logger, as the below example demonstrates.
 
     ```python
     import whylogs as why
     from whylogs.api.store.local import LocalStore
@@ -44,17 +44,17 @@
     ```python
     from datetime import datetime, timedelta
 
     from whylogs.api.store.date_config import DateConfig
 
     store = LocalStore()
     query = DateQuery(
-        profile_name="my_model",
-        start_date = datetime.utcnow() - timedelta(days=7),
-        end_date = datetime.utcnow()
+        dataset_id="my_model",
+        start_date = datetime.now(timezone.utc) - timedelta(days=7),
+        end_date = datetime.now(timezone.utc)
     )
 
     profile_view = store.get(query=query)
     ```
 
     This will fetch all existing profiles from `my_model` from the past
     7 days in a single merged DatasetProfileView.
@@ -62,56 +62,56 @@
     To list existing profiles on your local ProfileStore, you can do:
 
     ```python
     store = LocalStore()
     store.list()
     ```
 
-    >**NOTE**: The parameter `profile_name` should always use the snake_case pattern,
+    >**NOTE**: The parameter `dataset_id` should always use the snake_case pattern,
     and it must also be **unique** to your existing dataset/ML model.
-    If you use the same `profile_name` to store different profiles,
+    If you use the same `dataset_id` to store different profiles,
     you will end up mixing those profiles and not being able to fetch and get
     them properly again.
     """
 
     def __init__(self):
         self._default_path = os.path.join(os.getcwd(), DEFAULT_DIR)
         logger.debug(f"Default ProfileStore path set to {self._default_path}")
         self._writer = LocalWriter(base_dir=self._default_path)
         if not os.path.isdir(self._default_path):
             os.makedirs(os.path.join(self._default_path))
 
     @staticmethod
     def _get_profile_filename() -> str:
-        now = datetime.utcnow()
+        now = datetime.now(timezone.utc)
         return f"profile_{now.date()}_{now.hour}:{now.minute}:{now.second}_{uuid.uuid4()}.bin"
 
     def list(self) -> List[str]:
         return [listed_file.name for listed_file in os.scandir(self._default_path) if listed_file.is_dir()]
 
-    def get(self, query: Union[DateQuery, ProfileNameQuery]) -> Optional[DatasetProfileView]:
+    def get(self, query: Union[DateQuery, DatasetIdQuery]) -> Optional[DatasetProfileView]:
         logger.debug("Fetching profiles with specified StoreQuery...")
         files_list = []
-        base_directory = os.path.join(self._default_path, query.profile_name)
+        base_directory = os.path.join(self._default_path, query.dataset_id)
         if isinstance(query, DateQuery):
             dates = self._get_dates(query=query)
             for date in dates:
                 files_list.extend(glob(f"{base_directory}/profile_{date.strftime('%Y-%m-%d')}*.bin"))
-        elif isinstance(query, ProfileNameQuery):
+        elif isinstance(query, DatasetIdQuery):
             files_list.extend(glob(f"{base_directory}/profile_*bin"))
         else:
             logger.warning("You must define a proper Query object")
             return None
 
         logger.debug(f"Profiles found! Number of profiles is {len(files_list)}")
         profiles_list = (why.read(file).view() for file in files_list)
         merged_profile = reduce(lambda x, y: x.merge(y), profiles_list)
         return merged_profile
 
-    def write(self, profile_view: DatasetProfileView, profile_name: str) -> None:
-        if not os.path.isdir(os.path.join(self._default_path, profile_name)):
-            logger.debug(f"Creating directory for {profile_name}")
-            os.makedirs(os.path.join(self._default_path, profile_name))
+    def write(self, profile_view: DatasetProfileView, dataset_id: str) -> None:
+        if not os.path.isdir(os.path.join(self._default_path, dataset_id)):
+            logger.debug(f"Creating directory for {dataset_id}")
+            os.makedirs(os.path.join(self._default_path, dataset_id))
 
-        profile_dest = os.path.join(self._default_path, profile_name, self._get_profile_filename())
+        profile_dest = os.path.join(self._default_path, dataset_id, self._get_profile_filename())
         logger.debug("Writing to profile to default store destination...")
         self._writer.write(file=profile_view, dest=profile_dest)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/store/profile_store.py` & `whylogs-1.2.0/whylogs/api/store/profile_store.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,30 +1,36 @@
 from abc import ABC, abstractmethod
 from datetime import datetime, timedelta
-from typing import List, Optional
+from typing import Generator, List
 
-from whylogs.api.store.query import DateQuery
+from whylogs.api.store.query import BaseQuery, DateQuery
 from whylogs.core import DatasetProfileView
 
 
 class ProfileStore(ABC):
     @abstractmethod
     def list(self) -> List[str]:
         pass
 
     @abstractmethod
-    def get(self, query: DateQuery) -> DatasetProfileView:
+    def get(self, query: BaseQuery) -> DatasetProfileView:
         pass
 
+    # TODO this has to be updated to be able to handle more types of things. It might be better to just
+    # accept any Writable instead of the concrete types, like Writer does.
     @abstractmethod
-    def write(self, profile_view: Optional[DatasetProfileView], profile_name: str) -> None:
+    def write(self, profile_view: DatasetProfileView, dataset_id: str) -> None:
         pass
 
     @staticmethod
-    def _get_date_range(query: DateQuery):
+    def _get_date_range(query: DateQuery) -> Generator[datetime, None, None]:
+        if query.end_date is None:
+            yield query.start_date
+            return
+
         for n in range(int((query.end_date - query.start_date).days) + 1):
             yield query.start_date + timedelta(n)
 
     def _get_dates(self, query: DateQuery) -> List[datetime]:
         dates = []
         for single_date in self._get_date_range(query=query):
             dates.append(single_date)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/store/query.py` & `whylogs-1.2.0/whylogs/api/store/query.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,21 +1,26 @@
 from dataclasses import dataclass, field
 from datetime import datetime
-from typing import Optional
+from typing import Optional, Union
 
 
 @dataclass
 class DateQuery:
-    profile_name: str
+    dataset_id: str
     start_date: datetime
     end_date: Optional[datetime] = field(default=None)
+    segment_tag: Optional[str] = field(default=None)
 
     def __post_init__(self):
         if self.end_date is None:
             self.end_date = self.start_date
         if self.end_date < self.start_date:
             self.start_date, self.end_date = self.end_date, self.start_date
 
 
 @dataclass
-class ProfileNameQuery:
-    profile_name: str
+class DatasetIdQuery:
+    dataset_id: str
+    segment_tag: Optional[str] = field(default=None)
+
+
+BaseQuery = Union[DateQuery, DatasetIdQuery]
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/usage_stats/__init__.py` & `whylogs-1.2.0/whylogs/api/usage_stats/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 import os
 import site
 import socket
 import sys
 import uuid
 from datetime import datetime
 from threading import Thread
-from typing import Any, Dict
+from typing import Any, Dict, List, Optional
 from urllib import request
 
 import whylogs
 
 _TELEMETRY_ENDPOINT = "https://stats.whylogs.com/"
 if os.getenv("TELEMETRY_DEV"):
     _TELEMETRY_ENDPOINT = "https://staging-stats.whylogs.com"
@@ -22,16 +22,26 @@
 logger = logging.getLogger(__name__)
 
 ANALYTICS_OPT_OUT = "WHYLOGS_NO_ANALYTICS"
 
 # Flag to disable it internally
 _TELEMETRY_DISABLED = False
 _TRACKED_EVENTS: Dict[str, bool] = {}
+_SITE_PACKAGES: List[str] = []
 
-_SITE_PACKAGES = site.getsitepackages()
+try:
+    # fix for virtualenv lack of definition for getsitepackages
+    if hasattr(site, "getsitepackages"):
+        _SITE_PACKAGES = site.getsitepackages()
+    else:
+        from distutils.sysconfig import get_python_lib
+
+        _SITE_PACKAGES = [get_python_lib()]
+except:  # noqa
+    logger.debug("Encountered exception when checking site packages")
 
 if os.getenv(ANALYTICS_OPT_OUT) is not None:
     logger.debug("Opted out of usage statistics. Skipping.")
     _TELEMETRY_DISABLED = True
 
 try:
     if os.path.exists(os.path.expanduser("~/.whylogs/disable_telemetry")):
@@ -89,15 +99,20 @@
         )
         return uuid.uuid4().hex
 
 
 def _build_metadata() -> Dict[str, Any]:
     """Hash system and project data to send to our stats endpoint."""
 
-    project_version = whylogs.__version__
+    if hasattr(whylogs, "__version__"):
+        project_version = whylogs.__version__
+    else:
+        import whylogs as why
+
+        project_version = why.package_version()
     (major, minor, macro, _, _) = sys.version_info
 
     metadata = {
         "project_version": project_version,
         "python_version": f"{major}.{minor}.{macro}",
         "python_version_full": sys.version,
         "terminal": _get_terminal_mode(),
@@ -114,25 +129,26 @@
         "mlflow": _has_lib("mlflow"),
         "dask": _has_lib("dask"),
         "ray": _has_lib("ray"),
         "airflow": _has_lib("airflow"),
         "pyspark": _has_lib("pyspark"),
         "flyte": _has_lib("flyte"),
         "kafka": _has_lib("kafka"),
+        "langkit": _has_lib("langkit"),
     }
     for k in list(integrations.keys()):
         if integrations.get(k) is False:
             integrations.pop(k)
 
     # add integration metadata
     metadata.update(integrations)
     return metadata
 
 
-def _send_stats_event(event_name: str, identity: str, properties: Dict[str, Any] = None) -> None:
+def _send_stats_event(event_name: str, identity: str, properties: Optional[Dict[str, Any]] = None) -> None:
     data = {
         "identity": identity,
         "event": event_name,
         "timestamp": datetime.utcnow().strftime(_TIMESTAMP_FORMAT),
         "properties": properties or {},
     }
     global _TELEMETRY_DISABLED
@@ -140,19 +156,19 @@
     req = request.Request(_TELEMETRY_ENDPOINT, data=json_data, method="POST")
     req.add_header("Content-Type", "application/json")
 
     resp: http.client.HTTPResponse = None  # type: ignore
     try:
         resp = request.urlopen(req, timeout=3)
         if resp.status != 200:
-            logger.warning("Unable to send usage stats. Disabling stats collection.")
+            logger.info("Unable to send usage stats. Disabling whylogs api usage collection.")
             _TELEMETRY_DISABLED = True
         logger.debug("Response: %s", resp.read())
     except:  # noqa
-        logger.warning("Connection error. Skip stats collection.")
+        logger.info("Connection error. Skip whylogs api usage collection.")
         _TELEMETRY_DISABLED = True
 
     finally:
         if resp is not None:
             resp.close()
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/writer/__init__.py` & `whylogs-1.2.0/whylogs/api/writer/__init__.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/api/writer/gcs.py` & `whylogs-1.2.0/whylogs/api/writer/gcs.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/api/writer/local.py` & `whylogs-1.2.0/whylogs/api/writer/local.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,15 +1,14 @@
 import logging
 import os
 from typing import Any, Optional, Tuple
 
 from whylogs.api.writer import Writer
 from whylogs.api.writer.writer import Writable
 from whylogs.core.utils import deprecated_alias
-from whylogs.core.view.segmented_dataset_profile_view import SegmentedDatasetProfileView
 
 logger = logging.getLogger(__name__)
 
 
 class LocalWriter(Writer):
     def __init__(self, base_dir: Optional[str] = None, base_name: Optional[str] = None) -> None:
         if base_dir is None:
@@ -22,19 +21,15 @@
         self,
         file: Writable,
         dest: Optional[str] = None,
         **kwargs: Any,
     ) -> Tuple[bool, str]:
         dest = dest or self._base_name or file.get_default_path()  # type: ignore
         full_path = os.path.join(self._base_dir, dest)
-        has_segments = isinstance(file, SegmentedDatasetProfileView)
-        if has_segments:
-            file.write(full_path, use_v0=True)
-        else:
-            file.write(full_path)  # type: ignore
+        file.write(full_path, **kwargs)
         return True, full_path
 
     def option(self, base_dir: Optional[str] = None, base_name: Optional[str] = None) -> "LocalWriter":  # type: ignore
         if base_dir is not None:
             self._base_dir = base_dir
         if base_name is not None:
             self._base_name = base_name
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/writer/mlflow.py` & `whylogs-1.2.0/whylogs/api/writer/mlflow.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,42 +1,45 @@
 import logging
 import os
 from tempfile import mkdtemp
 from typing import Any, Optional, Tuple
 
 import mlflow
 
+from whylogs.api.usage_stats import emit_usage
 from whylogs.api.writer import Writer
 from whylogs.api.writer.writer import Writable
 from whylogs.core.utils import deprecated_alias
 
 logger = logging.getLogger(__name__)
 
 
 class MlflowWriter(Writer):
     def __init__(self) -> None:
         self._file_dir = "whylogs"
         self._file_name = None
         self._end_run = True
+        emit_usage("mlflow_writer")
 
     @deprecated_alias(profile="file")
     def write(
         self,
         file: Writable,
         dest: Optional[str] = None,
         **kwargs: Any,
     ) -> Tuple[bool, str]:
-        run = mlflow.active_run() or mlflow.start_run()
+        preexisting_run = mlflow.active_run()
+        run = preexisting_run or mlflow.start_run()
         self._run_id = run.info.run_id
         dest = dest or self._file_name or file.get_default_path()  # dest has a higher priority than file_name
         output = self._get_temp_directory(dest=dest)
         response = file.write(path=output)  # type: ignore
         mlflow.log_artifact(output, artifact_path=self._file_dir)
 
-        if self._end_run is True:
+        if self._end_run is True and not preexisting_run:
             mlflow.end_run()
         return response
 
     @deprecated_alias(profile_dir="file_dir", profile_name="file_name")
     def option(
         self, file_name: Optional[str] = None, file_dir: Optional[str] = None, end_run: Optional[bool] = None
     ) -> None:
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/writer/s3.py` & `whylogs-1.2.0/whylogs/api/writer/s3.py`

 * *Files 3% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 import tempfile
 from typing import Any, Optional, Tuple
 
 import boto3
 from botocore.client import BaseClient
 from botocore.exceptions import ClientError
 
+from whylogs.api.usage_stats import emit_usage
 from whylogs.api.writer import Writer
 from whylogs.api.writer.writer import Writable
 from whylogs.core.utils import deprecated_alias
 
 logger = logging.getLogger(__name__)
 
 
@@ -58,14 +59,15 @@
         bucket_name: Optional[str] = None,
         object_name: Optional[str] = None,
     ):
         self.s3_client = s3_client or boto3.client("s3")
         self.base_prefix = base_prefix or "profile"
         self.bucket_name = bucket_name or ""
         self.object_name = object_name or None
+        emit_usage("s3_writer")
 
     @deprecated_alias(profile="file")
     def write(
         self,
         file: Writable,
         dest: Optional[str] = None,
         **kwargs: Any,
```

### Comparing `whylogs-1.1.9.dev0/whylogs/api/writer/writer.py` & `whylogs-1.2.0/whylogs/api/writer/writer.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/__init__.py` & `whylogs-1.2.0/whylogs/core/__init__.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,27 +1,37 @@
 from .column_profile import ColumnProfile
 from .dataset_profile import DatasetProfile
 from .datatypes import TypeMapper
+from .metric_getters import MetricGetter, ProfileGetter
 from .metrics import MetricConfig
+from .metrics.metrics import CardinalityThresholds
 from .model_performance_metrics import ModelPerformanceMetrics
+from .relations import Not, Predicate, Require
 from .resolvers import Resolver
 from .schema import ColumnSchema, DatasetSchema
 from .segment import Segment
 from .segmentation_partition import SegmentationPartition
 from .view import WHYLOGS_MAGIC_HEADER, ColumnProfileView, DatasetProfileView
 
 __ALL__ = [
     WHYLOGS_MAGIC_HEADER,
+    # predicates
+    Require,
+    MetricGetter,
+    ProfileGetter,
+    Predicate,
+    Not,
     # column
     ColumnProfile,
     DatasetProfile,
     DatasetSchema,
     ColumnSchema,
     # metric config
     MetricConfig,
+    CardinalityThresholds,
     # model perf
     ModelPerformanceMetrics,
     # Typing
     TypeMapper,
     Resolver,
     # Views
     ColumnProfileView,
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/column_profile.py` & `whylogs-1.2.0/whylogs/core/column_profile.py`

 * *Files 18% similar despite different names*

```diff
@@ -45,29 +45,43 @@
         """Force emptying the cache and update the internal metrics."""
 
         logger.debug("Flushing out the cache for col: %s. Cache size: %s", self._name, self._cache_size)
         old_cache = self._cache
         self._cache = []
         self.track_column(old_cache)
 
-    def track_column(self, series: Any) -> None:
-        ex_col = PreprocessedColumn.apply(series)
+    def _process_extracted_column(self, extracted_column: PreprocessedColumn) -> None:
         for metric in self._metrics.values():
-            res = metric.columnar_update(ex_col)
+            res = metric.columnar_update(extracted_column)
             self._failure_count += res.failures
             self._success_count += res.successes
+
+    def track_column(self, series: Any, identity_values: Any = None) -> None:
         for validator in self._column_validators:
-            validator.columnar_validate(ex_col)
+            validator.columnar_validate(series, identity_values=identity_values)
+        ex_col = PreprocessedColumn.apply(series)
+        self._process_extracted_column(ex_col)
+
+    def _track_homogeneous_column(self, series: Any) -> None:
+        ex_col = PreprocessedColumn._process_homogeneous_column(series)
+        self._process_extracted_column(ex_col)
+
+    def _track_datum(self, value: Any, identity_values: Any = None) -> None:
+        ex_col = PreprocessedColumn._process_scalar_value(value)
+        id_col = None
+        if identity_values is not None:
+            id_col = PreprocessedColumn._process_scalar_value(identity_values)
+        for validator in self._column_validators:
+            validator.columnar_validate(ex_col, id_col)
+        self._process_extracted_column(ex_col)
 
     def to_protobuf(self) -> ColumnMessage:
         self.flush()
-
         return self.view().to_protobuf()
 
     def view(self) -> ColumnProfileView:
         self.flush()
-
         return ColumnProfileView(
             metrics=self._metrics.copy(),
             success_count=self._success_count,
             failure_count=self._failure_count,
         )
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/constraints/factories/cardinality_metrics.py` & `whylogs-1.2.0/whylogs/core/constraints/factories/cardinality_metrics.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/constraints/factories/count_metrics.py` & `whylogs-1.2.0/whylogs/core/constraints/factories/count_metrics.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,12 +1,31 @@
+from whylogs.core.relations import Require
+
 from ..metric_constraints import MetricConstraint, MetricsSelector
 
 # TODO implement skip_missing for all methods
 
 
+def no_missing_values(column_name: str) -> MetricConstraint:
+    """Checks that there are no missing values in the column.
+
+    Parameters
+    ----------
+    column_name : str
+        Column the constraint is applied to
+    """
+
+    constraint = MetricConstraint(
+        name=f"{column_name} has no missing values",
+        condition=Require("null").equals(0),
+        metric_selector=MetricsSelector(column_name=column_name, metric_name="counts"),
+    )
+    return constraint
+
+
 def count_below_number(column_name: str, number: int) -> MetricConstraint:
     """Number of elements in a column must be below given number.
 
     Parameters
     ----------
     column_name : str
         Column the constraint is applied to
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/constraints/factories/distribution_metrics.py` & `whylogs-1.2.0/whylogs/core/constraints/factories/distribution_metrics.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,37 +1,32 @@
 from typing import Union
 
 from whylogs.core.constraints import MetricConstraint, MetricsSelector
-from whylogs.core.metrics import DistributionMetric
+from whylogs.core.relations import Require
 
 
 def greater_than_number(column_name: str, number: Union[float, int], skip_missing: bool = True) -> MetricConstraint:
     """Minimum value of given column must be above defined number.
 
     Parameters
     ----------
     column_name : str
         Column the constraint is applied to
     number : float
         reference value for applying the constraint
     skip_missing: bool
         If skip_missing is True, missing distribution metrics will make the check pass.
-        If False, the check will fail on missing metrics
+        If False, the check will fail on missing metrics, such as on an empty dataset
     """
 
-    def is_greater(metric: DistributionMetric) -> bool:
-        if not metric.kll.value.is_empty():
-            return metric.min >= number
-        else:
-            return True if skip_missing else False
-
     constraint = MetricConstraint(
         name=f"{column_name} greater than number {number}",
-        condition=is_greater,
+        condition=Require("min").greater_than(number),
         metric_selector=MetricsSelector(column_name=column_name, metric_name="distribution"),
+        require_column_existence=not skip_missing,
     )
     return constraint
 
 
 def smaller_than_number(column_name: str, number: float, skip_missing: bool = True) -> MetricConstraint:
     """Maximum value of given column must be below defined number.
 
@@ -39,27 +34,71 @@
     ----------
     column_name : str
         Column the constraint is applied to
     number : float
         reference value for applying the constraint
     skip_missing: bool
         If skip_missing is True, missing distribution metrics will make the check pass.
-        If False, the check will fail on missing metrics
+        If False, the check will fail on missing metrics, such as on an empty dataset
     """
 
-    def is_smaller(metric) -> bool:
-        if not metric.kll.value.is_empty():
-            return number >= metric.max
-        else:
-            return True if skip_missing else False
-
     constraint = MetricConstraint(
         name=f"{column_name} smaller than number {number}",
-        condition=is_smaller,
+        condition=lambda x: number > x.max,
+        metric_selector=MetricsSelector(column_name=column_name, metric_name="distribution"),
+        require_column_existence=not skip_missing,
+    )
+    return constraint
+
+
+def is_non_negative(column_name: str, skip_missing: bool = True) -> MetricConstraint:
+    """Checks if a column is non negative
+
+    Parameters
+    ----------
+    column_name : str
+        Column the constraint is applied to
+    skip_missing: bool
+        If skip_missing is True, missing distribution metrics will make the check pass.
+        If False, the check will fail on missing metrics, such as on an empty dataset
+    """
+    constraint = MetricConstraint(
+        name=f"{column_name} is non negative",
+        condition=Require("min").greater_or_equals(0),
+        metric_selector=MetricsSelector(column_name=column_name, metric_name="distribution"),
+        require_column_existence=not skip_missing,
+    )
+    return constraint
+
+
+def is_in_range(
+    column_name: str, lower: Union[float, int], upper: Union[float, int], skip_missing: bool = True
+) -> MetricConstraint:
+    """Checks that all of column's values are in defined range (inclusive).
+
+    For the constraint to pass, the column's minimum value should be higher or equal than `lower` and maximum value should be less than or equal to `upper`.
+
+    Parameters
+    ----------
+    column_name : str
+        Column the constraint is applied to
+    lower : float
+        lower bound of defined range
+    upper : float
+        upper bound of defined range
+    skip_missing: bool
+        If skip_missing is True, missing distribution metrics will make the check pass.
+        If False, the check will fail on missing metrics, such as on an empty dataset
+    """
+
+    constraint = MetricConstraint(
+        name=f"{column_name} is in range [{lower},{upper}]",
+        condition=Require("min").greater_or_equals(lower).and_(Require("max").less_or_equals(upper)),
         metric_selector=MetricsSelector(column_name=column_name, metric_name="distribution"),
+        require_column_existence=not skip_missing,
     )
     return constraint
 
 
 def mean_between_range(column_name: str, lower: float, upper: float, skip_missing: bool = True) -> MetricConstraint:
     """Estimated mean must be between range defined by lower and upper bounds.
 
@@ -69,27 +108,22 @@
         Column the constraint is applied to
     lower : int
         Lower bound of defined range
     upper : int
         Upper bound of the value range
     skip_missing: bool
         If skip_missing is True, missing distribution metrics will make the check pass.
-        If False, the check will fail on missing metrics
+        If False, the check will fail on missing metrics, such as on an empty dataset
     """
 
-    def is_mean_between(metric) -> bool:
-        if not metric.kll.value.is_empty():
-            return lower <= metric.avg <= upper
-        else:
-            return True if skip_missing else False
-
     constraint = MetricConstraint(
         name=f"{column_name} mean between {lower} and {upper} (inclusive)",
-        condition=is_mean_between,
+        condition=Require("mean").greater_or_equals(lower).and_(Require("mean").less_or_equals(upper)),
         metric_selector=MetricsSelector(column_name=column_name, metric_name="distribution"),
+        require_column_existence=not skip_missing,
     )
     return constraint
 
 
 def stddev_between_range(column_name: str, lower: float, upper: float, skip_missing: bool = True):
     """Estimated standard deviation must be between range defined by lower and upper bounds.
 
@@ -99,56 +133,51 @@
         Column the constraint is applied to
     lower: float
         Lower bound of defined range
     upper: float
         Upper bound of the value range
     skip_missing: bool
         If skip_missing is True, missing distribution metrics will make the check pass.
-        If False, the check will fail on missing metrics
+        If False, the check will fail on missing metrics, such as on an empty dataset
     """
 
-    def is_stddev_between_range(metric):
-        if not metric.kll.value.is_empty():
-            return lower <= metric.stddev <= upper
-        else:
-            return True if skip_missing else False
-
     constraint = MetricConstraint(
         name=f"{column_name} standard deviation between {lower} and {upper} (inclusive)",
-        condition=is_stddev_between_range,
+        condition=Require("stddev").greater_or_equals(lower).and_(Require("stddev").less_or_equals(upper)),
         metric_selector=MetricsSelector(column_name=column_name, metric_name="distribution"),
+        require_column_existence=not skip_missing,
     )
     return constraint
 
 
-def quantile_between_range(column_name: str, quantile: float, lower: float, upper: float, skip_missing: bool = True):
+def quantile_between_range(
+    column_name: str, quantile: float, lower: float, upper: float, skip_missing: bool = True
+) -> MetricConstraint:
     """Q-th quantile value must be withing the range defined by lower and upper boundaries.
 
     Parameters
     ----------
     column_name: str
         Column the constraint is applied to
     quantile: float
         Quantile value. E.g. median is equal to quantile_value=0.5
     lower: float
         Lower bound of defined range
     upper: float
         Upper bound of the value range
     skip_missing: bool
         If skip_missing is True, missing distribution metrics will make the check pass.
-        If False, the check will fail on missing metrics
+        If False, the check will fail on missing metrics, such as on an empty dataset
     """
 
-    def quantile_in_range(metric):
-        if not metric.kll.value.is_empty():
-            quantile_value = metric.kll.value.get_quantile(quantile)
-            result: bool = lower <= quantile_value <= upper
-            return result
-        else:
-            return True if skip_missing else False
+    def quantile_in_range(metric) -> bool:
+        quantile_value = metric.kll.value.get_quantile(quantile)
+        result: bool = lower <= quantile_value <= upper
+        return result
 
     constraint = MetricConstraint(
         name=f"{column_name} {quantile}-th quantile value between {lower} and {upper} (inclusive)",
         condition=quantile_in_range,
         metric_selector=MetricsSelector(column_name=column_name, metric_name="distribution"),
+        require_column_existence=not skip_missing,
     )
     return constraint
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/constraints/factories/frequent_items.py` & `whylogs-1.2.0/whylogs/core/constraints/factories/frequent_items.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/dataset_profile.py` & `whylogs-1.2.0/whylogs/core/dataset_profile.py`

 * *Files 9% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 from typing import Any, Dict, Mapping, Optional, Tuple, Union
 
 from whylogs.api.writer.writer import Writable
 from whylogs.core.metrics import Metric
 from whylogs.core.model_performance_metrics.model_performance_metrics import (
     ModelPerformanceMetrics,
 )
+from whylogs.core.preprocessing import ColumnProperties
 from whylogs.core.utils.utils import deprecated_alias
 
 from .column_profile import ColumnProfile
 from .input_resolver import _pandas_or_dict
 from .schema import DatasetSchema
 from .stubs import pd
 from .view import DatasetProfileView
@@ -41,27 +42,29 @@
 
     def __init__(
         self,
         schema: Optional[DatasetSchema] = None,
         dataset_timestamp: Optional[datetime] = None,
         creation_timestamp: Optional[datetime] = None,
         metrics: Optional[Dict[str, Union[Metric, Any]]] = None,
+        metadata: Optional[Dict[str, str]] = None,
     ):
         if schema is None:
             schema = DatasetSchema()
-        now = datetime.utcnow()
+        now = datetime.now(timezone.utc)
         self._dataset_timestamp = dataset_timestamp or now
         self._creation_timestamp = creation_timestamp or now
         self._schema = schema
         self._columns: Dict[str, ColumnProfile] = dict()
         self._is_active = False
         self._track_count = 0
         new_cols = schema.get_col_names()
         self._initialize_new_columns(new_cols)
         self._metrics: Dict[str, Union[Metric, Any]] = metrics or dict()
+        self._metadata = metadata
 
     @property
     def creation_timestamp(self) -> datetime:
         return self._creation_timestamp
 
     @property
     def dataset_timestamp(self) -> datetime:
@@ -102,73 +105,92 @@
 
     def track(
         self,
         obj: Any = None,
         *,
         pandas: Optional[pd.DataFrame] = None,
         row: Optional[Mapping[str, Any]] = None,
+        execute_udfs: bool = True,
     ) -> None:
         try:
             self._is_active = True
             self._track_count += 1
-            self._do_track(obj, pandas=pandas, row=row)
+            self._do_track(obj, pandas=pandas, row=row, execute_udfs=execute_udfs)
         finally:
             self._is_active = False
 
     def _do_track(
         self,
         obj: Any = None,
         *,
         pandas: Optional[pd.DataFrame] = None,
         row: Optional[Mapping[str, Any]] = None,
+        execute_udfs: bool = True,
     ) -> None:
-
         pandas, row = _pandas_or_dict(obj, pandas, row)
+        if execute_udfs:
+            pandas, row = self._schema._run_udfs(pandas, row)
+
+        col_id: Optional[str] = getattr(self._schema.default_configs, "identity_column", None)
 
         # TODO: do this less frequently when operating at row level
         dirty = self._schema.resolve(pandas=pandas, row=row)
         if dirty:
             schema_col_keys = self._schema.get_col_names()
             new_cols = (col for col in schema_col_keys if col not in self._columns)
             self._initialize_new_columns(tuple(new_cols))
 
-        if pandas is not None:
+        if row is not None:
+            for k in row.keys():
+                if col_id:
+                    self._columns[k]._track_datum(row[k], row.get(col_id))
+                else:
+                    self._columns[k]._track_datum(row[k])
+            return
+        elif pandas is not None:
             # TODO: iterating over each column in order assumes single column metrics
             #   but if we instead iterate over a new artifact contained in dataset profile: "MetricProfiles", then
             #   each metric profile can specify which columns its tracks, and we can call like this:
             #   metric_profile.track(pandas)
             if pandas.empty:
                 logger.warning("whylogs was passed an empty pandas DataFrame so nothing to profile in this call.")
                 return
             for k in pandas.keys():
                 column_values = pandas.get(k)
                 if column_values is None:
                     logger.error(
                         f"whylogs was passed a pandas DataFrame with key [{k}] but DataFrame.get({k}) returned nothing!"
                     )
-                else:
-                    self._columns[k].track_column(column_values)
-            return
+                    return
 
-        if row is not None:
-            for k in row.keys():
-                self._columns[k].track_column([row[k]])
+                dtype = self._schema.types.get(k)
+                homogeneous = (
+                    dtype is not None
+                    and isinstance(dtype, tuple)
+                    and len(dtype) == 2
+                    and isinstance(dtype[1], ColumnProperties)
+                    and dtype[1] == ColumnProperties.homogeneous
+                )
+                if homogeneous:
+                    self._columns[k]._track_homogeneous_column(column_values)
+                else:
+                    id_values = pandas.get(col_id)
+                    if col_id is not None and id_values is None:
+                        logger.warning(
+                            f"identity column was passed as {col_id} but column was not found in the dataframe."
+                        )
+                    if col_id is not None and id_values is not None:
+                        self._columns[k].track_column(column_values, id_values)
+                    else:
+                        self._columns[k].track_column(column_values)
             return
 
         raise NotImplementedError
 
-    def _track_classification_metrics(
-        self,
-        targets,
-        predictions,
-        scores=None,
-        target_field=None,
-        prediction_field=None,
-        score_field=None,
-    ) -> None:
+    def _track_classification_metrics(self, targets, predictions, scores=None) -> None:
         """
         Function to track metrics based on validation data.
         user may also pass the associated attribute names associated with
         target, prediction, and/or score.
         Parameters
         ----------
         targets : List[Union[str, bool, float, int]]
@@ -186,32 +208,17 @@
             Description
         target_field : str, optional
         prediction_field : str, optional
         score_field : str, optional
         """
         if not self.model_performance_metrics:
             self.add_model_performance_metrics(ModelPerformanceMetrics())
-        self.model_performance_metrics.compute_confusion_matrix(
-            predictions=predictions,
-            targets=targets,
-            scores=scores,
-            target_field=target_field,
-            prediction_field=prediction_field,
-            score_field=score_field,
-        )
+        self.model_performance_metrics.compute_confusion_matrix(predictions=predictions, targets=targets, scores=scores)
 
-    def _track_regression_metrics(
-        self,
-        targets,
-        predictions,
-        scores=None,
-        target_field=None,
-        prediction_field=None,
-        score_field=None,
-    ) -> None:
+    def _track_regression_metrics(self, targets, predictions, scores=None) -> None:
         """
         Function to track regression metrics based on validation data.
         user may also pass the associated attribute names associated with
         target, prediction, and/or score.
         Parameters
         ----------
         targets : List[Union[str, bool, float, int]]
@@ -230,20 +237,15 @@
         target_field : str, optional
         prediction_field : str, optional
         score_field : str, optional
         """
         if not self.model_performance_metrics:
             self.add_model_performance_metrics(ModelPerformanceMetrics())
         self.model_performance_metrics.compute_regression_metrics(
-            predictions=predictions,
-            targets=targets,
-            scores=scores,
-            target_field=target_field,
-            prediction_field=prediction_field,
-            score_field=score_field,
+            predictions=predictions, targets=targets, scores=scores
         )
 
     def _initialize_new_columns(self, new_cols: tuple) -> None:
         for col in new_cols:
             col_schema = self._schema.get(col)
             if col_schema:
                 self._columns[col] = ColumnProfile(name=col, schema=col_schema, cache_size=self._schema.cache_size)
@@ -255,14 +257,15 @@
         for c_name, c in self._columns.items():
             columns[c_name] = c.view()
         return DatasetProfileView(
             columns=columns,
             dataset_timestamp=self.dataset_timestamp,
             creation_timestamp=self.creation_timestamp,
             metrics=self._metrics,
+            metadata=self._metadata,
         )
 
     def flush(self) -> None:
         for col in self._columns.values():
             col.flush()
 
     @staticmethod
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/datatypes.py` & `whylogs-1.2.0/whylogs/core/datatypes.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from abc import ABC, abstractmethod
 from decimal import Decimal
 from typing import Any, Generic, List, Optional, Type, TypeVar, Union
 
-from whylogs.core.stubs import np
+from whylogs.core.stubs import is_not_stub, np
 
 try:
     from pandas.core.api import CategoricalDtype
 except:  # noqa
     CategoricalDtype = None  # type: ignore
 
 NT = TypeVar("NT")
@@ -51,15 +51,15 @@
         if maybe_type:
             dtype_or_type = maybe_type  # type: ignore
 
         if not isinstance(dtype_or_type, type):
             return False
 
         if issubclass(dtype_or_type, (bool, int, np.number, np.bool_)):
-            if np.issubdtype and np.issubdtype(dtype_or_type, np.floating):
+            if is_not_stub(np.issubdtype) and np.issubdtype(dtype_or_type, np.floating):
                 return False
             if issubclass(dtype_or_type, (np.datetime64, np.timedelta64)):
                 return False
             else:
                 return True
         return False
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/errors.py` & `whylogs-1.2.0/whylogs/core/errors.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/feature_weights.py` & `whylogs-1.2.0/whylogs/core/feature_weights.py`

 * *Files 8% similar despite different names*

```diff
@@ -24,18 +24,18 @@
         self.metadata = metadata
 
     def writer(self, name: str = "local") -> "FeatureWeightWriter":
         writer = Writers.get(name)
         return FeatureWeightWriter(feature_weight=self, writer=writer)
 
     def get_default_path(self) -> str:
-        pass
+        return f"feature_weights_{self.segment}.json"
 
-    def write(self, path: Optional[str] = None, **kwargs: Any) -> None:
-        pass
+    def write(self, path: Optional[str] = None, **kwargs: Any) -> Tuple[bool, str]:
+        return (False, "write() not implemented on feature weights, use with WhyLabsWriter.")
 
     def to_json(self) -> str:
         return json.dumps({"segment": self.segment, "weights": self.weights})
 
     def to_dict(self) -> Dict[str, Union[Optional[Segment], Optional[float]]]:
         return {"segment": self.segment, "weights": self.weights}
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/input_resolver.py` & `whylogs-1.2.0/whylogs/core/input_resolver.py`

 * *Files 14% similar despite different names*

```diff
@@ -8,16 +8,16 @@
 ) -> Tuple[Optional[pd.DataFrame], Optional[Mapping[str, Any]]]:
     if obj is not None:
         if pandas is not None:
             raise ValueError("Cannot pass both obj and pandas params")
         if row is not None:
             raise ValueError("Cannot pass both obj and row params")
 
-        if pd.DataFrame is not None and isinstance(obj, pd.DataFrame):
-            pandas = obj
-        elif isinstance(obj, (dict, Dict, Mapping)):
+        if isinstance(obj, (dict, Dict, Mapping)):
             row = obj
+        elif pd.DataFrame is not None and isinstance(obj, pd.DataFrame):
+            pandas = obj
 
     if pandas is not None and row is not None:
         raise ValueError("Cannot pass both pandas and row params")
 
     return (pandas, row)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/__init__.py` & `whylogs-1.2.0/whylogs/core/metrics/__init__.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/aggregators.py` & `whylogs-1.2.0/whylogs/core/metrics/aggregators.py`

 * *Files 0% similar despite different names*

```diff
@@ -60,29 +60,29 @@
 def _kll_merge(lhs: ds.kll_doubles_sketch, rhs: ds.kll_doubles_sketch) -> ds.kll_doubles_sketch:
     kll_copy = ds.kll_doubles_sketch(lhs)
     kll_copy.merge(rhs)
 
     return kll_copy
 
 
-@_typed_aggregator(mtype=ds.hll_sketch, name="kll")
+@_typed_aggregator(mtype=ds.hll_sketch, name="hll")
 def _hll_merge(lhs: ds.hll_sketch, rhs: ds.hll_sketch) -> ds.hll_sketch:
     lg_k = max(lhs.lg_config_k, rhs.lg_config_k)
     tg_type = lhs.tgt_type
     if tg_type.value < rhs.tgt_type.value:
         tg_type = rhs.tgt_type
 
     copy = ds.hll_union(lg_k)
     copy.update(lhs)
     copy.update(rhs)
 
     return copy.get_result(tg_type)
 
 
-@_typed_aggregator(mtype=ds.frequent_strings_sketch, name="kll")
+@_typed_aggregator(mtype=ds.frequent_strings_sketch, name="fs")
 def _fs_merge(lhs: ds.frequent_strings_sketch, rhs: ds.frequent_strings_sketch) -> ds.frequent_strings_sketch:
     copy = ds.frequent_strings_sketch.deserialize(lhs.serialize())
     copy.merge(rhs)
 
     return copy
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/column_metrics.py` & `whylogs-1.2.0/whylogs/core/metrics/column_metrics.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,117 +1,153 @@
-from dataclasses import dataclass
+from dataclasses import dataclass, field
 from typing import Any, Dict, Optional
 
 from whylogs.core.configs import SummaryConfig
 from whylogs.core.metrics.metric_components import IntegralComponent
-from whylogs.core.metrics.metrics import Metric, MetricConfig, OperationResult
+from whylogs.core.metrics.metrics import (
+    Metric,
+    MetricConfig,
+    OperationResult,
+    register_metric,
+)
 from whylogs.core.preprocessing import PreprocessedColumn
 
 
 @dataclass(frozen=True)
 class TypeCountersMetric(Metric):
     integral: IntegralComponent
     fractional: IntegralComponent
     boolean: IntegralComponent
     string: IntegralComponent
     object: IntegralComponent
+    tensor: IntegralComponent = field(default_factory=lambda: IntegralComponent(0))
 
     @property
     def namespace(self) -> str:
         return "types"
 
     def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Any]:
         return {
             "integral": self.integral.value,
             "fractional": self.fractional.value,
             "boolean": self.boolean.value,
             "string": self.string.value,
             "object": self.object.value,
+            "tensor": self.tensor.value,
         }
 
     def columnar_update(self, data: PreprocessedColumn) -> OperationResult:
         if data.len <= 0:
             return OperationResult.ok(0)
 
         successes = 0
 
         integral_prev = self.integral.value
         integral = 0
         if data.numpy.ints is not None:
             integral += len(data.numpy.ints)
-        elif data.list.ints is not None:
+        if data.list.ints is not None:
             integral += len(data.list.ints)
         successes += integral
         self.integral.set(integral + integral_prev)
 
         fractional = 0
         fractional_prev = self.fractional.value
         if data.numpy.floats is not None:
             fractional += len(data.numpy.floats)
-        elif data.list.floats is not None:
+        if data.list.floats is not None:
             fractional += len(data.list.floats)
         successes += fractional
         self.fractional.set(fractional + fractional_prev)
 
         bool_count = self.boolean.value + data.bool_count
         successes += data.bool_count
         self.boolean.set(bool_count)
 
         string_count = 0
         string_count_prev = self.string.value
         if data.pandas.strings is not None:
             string_count += len(data.pandas.strings)
-        elif data.list.strings is not None:
+        if data.list.strings is not None:
             string_count += len(data.list.strings)
-
+        if data.numpy.strings is not None:
+            string_count += len(data.numpy.strings)
         successes += string_count
         self.string.set(string_count + string_count_prev)
 
+        tensor_count = 0
+        tensor_count_prev = self.tensor.value
+        if data.pandas.tensors is not None:
+            tensor_count += len(data.pandas.tensors)
+        if data.list.tensors is not None:
+            tensor_count += len(data.list.tensors)
+
+        successes += tensor_count
+        self.tensor.set(tensor_count + tensor_count_prev)
+
         objects = 0
         objects_prev = self.object.value
         if data.pandas.objs is not None:
             objects += len(data.pandas.objs)
-        elif data.list.objs is not None:
+        if data.list.objs is not None:
             objects += len(data.list.objs)
 
         successes += objects
         self.object.set(objects + objects_prev)
         return OperationResult.ok(successes)
 
     @classmethod
     def zero(cls, config: Optional[MetricConfig] = None) -> "TypeCountersMetric":
         return TypeCountersMetric(
             integral=IntegralComponent(0),
             fractional=IntegralComponent(0),
             boolean=IntegralComponent(0),
             string=IntegralComponent(0),
             object=IntegralComponent(0),
+            tensor=IntegralComponent(0),
         )
 
 
 @dataclass(frozen=True)
 class ColumnCountsMetric(Metric):
     n: IntegralComponent
     null: IntegralComponent
+    nan: IntegralComponent = field(default_factory=lambda: IntegralComponent(0))
+    inf: IntegralComponent = field(default_factory=lambda: IntegralComponent(0))
 
     @property
     def namespace(self) -> str:
         return "counts"
 
     def columnar_update(self, data: PreprocessedColumn) -> OperationResult:
         n: int = self.n.value
         null: int = self.null.value
+        nan: int = self.nan.value
+        inf: int = self.inf.value
+
         if data.len <= 0:
             return OperationResult.ok(0)
         n += data.len
         self.n.set(n)
 
         null += data.null_count
         self.null.set(null)
+
+        nan += data.nan_count
+        self.nan.set(nan)
+
+        inf += data.inf_count
+        self.inf.set(inf)
+
         return OperationResult.ok(data.len)
 
     def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Any]:
-        return {"n": self.n.value, "null": self.null.value}
+        return {"n": self.n.value, "null": self.null.value, "nan": self.nan.value, "inf": self.inf.value}
 
     @classmethod
     def zero(cls, config: Optional[MetricConfig] = None) -> "ColumnCountsMetric":
-        return ColumnCountsMetric(n=IntegralComponent(0), null=IntegralComponent(0))
+        return ColumnCountsMetric(
+            n=IntegralComponent(0), null=IntegralComponent(0), nan=IntegralComponent(0), inf=IntegralComponent(0)
+        )
+
+
+register_metric([TypeCountersMetric, ColumnCountsMetric])
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/compound_metric.py` & `whylogs-1.2.0/whylogs/core/metrics/compound_metric.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,16 +14,16 @@
 
 class CompoundMetric(Metric, ABC):
     """
     CompoundMetric serves as a base class for custom metrics that consist
     of one or more metrics. It is handy when you need to do some
     processing of the logged values and track serveral metrics on
     the results. The sub-metrics must either be a StandardMetric, or tagged
-    as a @custom_metric or @dataclass. Note that CompoundMetric is neither, so it
-    cannot be nested.
+    as a @custom_metric or registered via register_metric(). Note that
+    CompoundMetric is neither, so it cannot be nested.
 
     Typically you will need to override namespace(); columnar_update(), calling
     it on the submetrics as needed; and the zero() method to return an
     appropriate "empty" instance of your metric. You will need to override from_protobuf()
     and merge() if your subclass __init__() method takes arguments different than
     CompoundMetrtic's. You can use the submetrics_from_protbuf() and merge_submetrics()
     helper methods to implement them. The CompoundMetric class will handle the rest of
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/condition_count_metric.py` & `whylogs-1.2.0/whylogs/core/metrics/condition_count_metric.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,51 +1,49 @@
 import logging
 import re
 from copy import copy
 from dataclasses import dataclass, field
-from enum import Enum
 from itertools import chain
 from typing import Any, Callable, Dict, List, Optional, Set, Union
 
 from whylogs.core.configs import SummaryConfig
 from whylogs.core.metrics.metric_components import IntegralComponent, MetricComponent
-from whylogs.core.metrics.metrics import Metric, MetricConfig, OperationResult
+from whylogs.core.metrics.metrics import (
+    Metric,
+    MetricConfig,
+    OperationResult,
+    register_metric,
+)
 from whylogs.core.preprocessing import PreprocessedColumn
 from whylogs.core.proto import MetricMessage
+from whylogs.core.relations import Relation as Rel
 
 logger = logging.getLogger(__name__)
 
+# For backward compatability
+Relation = Rel  # type: ignore
 
-class Relation(Enum):
-    match = 1
-    fullmatch = 2
-    equal = 3
-    less = 4
-    leq = 5
-    greater = 6
-    geq = 7
-    neq = 8
 
-
-def relation(op: Relation, value: Union[str, int, float]) -> Callable[[Any], bool]:
-    if op == Relation.match:
+# relation() is annoying, use Predicate instead
+def relation(op: Relation, value: Union[str, int, float]) -> Callable[[Any], bool]:  # type: ignore
+    if op == Relation.match:  # type: ignore
         return lambda x: re.compile(value).match(x)  # type: ignore
-    if op == Relation.fullmatch:
+    if op == Relation.fullmatch:  # type: ignore
         return lambda x: re.compile(value).fullmatch(x)  # type: ignore
-    if op == Relation.equal:
+    if op == Relation.equal:  # type: ignore
         return lambda x: x == value  # type: ignore
-    if op == Relation.less:
+    if op == Relation.less:  # type: ignore
         return lambda x: x < value  # type: ignore
-    if op == Relation.leq:
+    if op == Relation.leq:  # type: ignore
         return lambda x: x <= value  # type: ignore
-    if op == Relation.greater:
+    if op == Relation.greater:  # type: ignore
         return lambda x: x > value  # type: ignore
-    if op == Relation.geq:
+    if op == Relation.geq:  # type: ignore
         return lambda x: x >= value  # type: ignore
-    if op == Relation.neq:
+    if op == Relation.neq:  # type: ignore
         return lambda x: x != value  # type: ignore
     raise ValueError("Unknown ConditionCountMetric predicate")
 
 
 def and_relations(left: Callable[[Any], bool], right: Callable[[Any], bool]) -> Callable[[Any], bool]:
     return lambda x: left(x) and right(x)
 
@@ -59,33 +57,39 @@
 
 
 @dataclass(frozen=True)
 class Condition:
     relation: Callable[[Any], bool]
     throw_on_failure: bool = False
     log_on_failure: bool = False
+    actions: List[Callable[[str, str, Any], None]] = field(default_factory=list)
 
 
 @dataclass(frozen=True)
 class ConditionCountConfig(MetricConfig):
     conditions: Dict[str, Condition] = field(default_factory=dict)
+    exclude_from_serialization: bool = False
 
 
 @dataclass(frozen=True)
 class ConditionCountMetric(Metric):
     conditions: Dict[str, Condition]
     total: IntegralComponent
     matches: Dict[str, IntegralComponent] = field(default_factory=dict)
+    hide_from_serialization: bool = False
+
+    @property
+    def exclude_from_serialization(self) -> bool:
+        return self.hide_from_serialization
 
     @property
     def namespace(self) -> str:
         return "condition_count"
 
     def __post_init__(self) -> None:
-        super(type(self), self).__post_init__()
         if "total" in self.conditions.keys():
             raise ValueError("Condition cannot be named 'total'")
 
         for cond_name in self.conditions.keys():
             if cond_name not in self.matches:
                 self.matches[cond_name] = IntegralComponent(0)
 
@@ -97,15 +101,20 @@
         else:
             matches = {
                 cond_name: IntegralComponent(self.matches[cond_name].value + other.matches[cond_name].value)
                 for cond_name in self.matches.keys()
             }
             total = self.total.value + other.total.value
 
-        return ConditionCountMetric(copy(self.conditions), IntegralComponent(total), matches)
+        return ConditionCountMetric(
+            copy(self.conditions),
+            IntegralComponent(total),
+            matches,
+            hide_from_serialization=self.hide_from_serialization or other.hide_from_serialization,
+        )
 
     def add_conditions(self, conditions: Dict[str, Condition]) -> None:
         if "total" in conditions.keys():
             raise ValueError("Condition cannot be named 'total'")
         for cond_name, cond in conditions.items():
             self.conditions[cond_name] = cond
             self.matches[cond_name] = IntegralComponent(0)
@@ -118,43 +127,51 @@
 
     def columnar_update(self, data: PreprocessedColumn) -> OperationResult:
         if data.len <= 0:
             return OperationResult.ok(0)
 
         count = 0
         failed_conditions: Set[str] = set()
-        for x in list(chain.from_iterable(data.raw_iterator())):
+        for datum in list(chain.from_iterable(data.raw_iterator())):
             count += 1
             for cond_name, condition in self.conditions.items():
                 try:
-                    if condition.relation(x):
+                    if condition.relation(datum):
                         self.matches[cond_name].set(self.matches[cond_name].value + 1)
                     else:
                         failed_conditions.add(cond_name)
+                        for action in condition.actions:
+                            action(self.namespace, cond_name, datum)
 
-                except:  # noqa
-                    pass
+                except Exception as e:  # noqa
+                    logger.debug(e)
+                    failed_conditions.add(cond_name)
 
         self.total.set(self.total.value + count)
-        if condition.log_on_failure:
-            logger.warning(f"Condition(s) {', '.join(failed_conditions)} failed")
-        if condition.throw_on_failure:
-            raise ValueError(f"Condition(s) {', '.join(failed_conditions)} failed")
+        if failed_conditions:
+            if condition.log_on_failure:
+                logger.warning(f"Condition(s) {', '.join(failed_conditions)} failed")
+
+            if condition.throw_on_failure:
+                raise ValueError(f"Condition(s) {', '.join(failed_conditions)} failed")
+
         return OperationResult.ok(count)
 
     @classmethod
     def zero(cls, config: Optional[MetricConfig] = None) -> "ConditionCountMetric":
         config = config or ConditionCountConfig()
         if not isinstance(config, ConditionCountConfig):
             raise ValueError("ConditionCountMetric.zero() requires ConditionCountConfig argument")
 
-        return ConditionCountMetric(
+        metric = ConditionCountMetric(
             conditions=copy(config.conditions),
             total=IntegralComponent(0),
+            hide_from_serialization=config.exclude_from_serialization,
         )
+        return metric
 
     def to_protobuf(self) -> MetricMessage:
         msg = {"total": self.total.to_protobuf()}
         for cond_name in self.conditions.keys():
             msg[cond_name] = self.matches[cond_name].to_protobuf()
 
         return MetricMessage(metric_components=msg)
@@ -177,7 +194,11 @@
             cond_name: MetricComponent.from_protobuf(msg.metric_components[cond_name]) for cond_name in cond_names
         }
         return ConditionCountMetric(
             conditions,
             total,
             matches,
         )
+
+
+# Register it so Multimetric and ProfileView can deserialize
+register_metric(ConditionCountMetric)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/decorators.py` & `whylogs-1.2.0/whylogs/core/metrics/decorators.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/deserializers.py` & `whylogs-1.2.0/whylogs/core/metrics/deserializers.py`

 * *Files 4% similar despite different names*

```diff
@@ -86,26 +86,26 @@
     field = msg.WhichOneof("value")
     if field != "kll":
         raise ValueError(f"Unsupported field: {field}")
 
     return ds.kll_doubles_sketch.deserialize(msg.kll.sketch)
 
 
-@_builtin_deserializer(name="kll")
-def _hll_merge(msg: MetricComponentMessage) -> ds.hll_sketch:
+@_builtin_deserializer(name="hll")
+def _hll(msg: MetricComponentMessage) -> ds.hll_sketch:
     field = msg.WhichOneof("value")
     if field != "hll":
         raise ValueError(f"Unsupported field: {field}")
 
     sketch = ds.hll_sketch.deserialize(msg.hll.sketch)
     return sketch
 
 
-@_builtin_deserializer(name="kll")
-def _fs_merge(msg: MetricComponentMessage) -> ds.frequent_strings_sketch:
+@_builtin_deserializer(name="fs")
+def _fs(msg: MetricComponentMessage) -> ds.frequent_strings_sketch:
     field = msg.WhichOneof("value")
     if field != "frequent_items":
         raise ValueError(f"Unsupported field: {field}")
 
     return ds.frequent_strings_sketch.deserialize(msg.frequent_items.sketch)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/maths.py` & `whylogs-1.2.0/whylogs/core/metrics/maths.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/metric_components.py` & `whylogs-1.2.0/whylogs/core/metrics/metric_components.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/metrics.py` & `whylogs-1.2.0/whylogs/core/metrics/metrics.py`

 * *Files 8% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 from abc import ABC, abstractmethod
 from dataclasses import asdict, dataclass, field
 from typing import Any, Dict, List, Optional, Tuple, Type, TypeVar, Union
 
 import whylogs_sketching as ds  # type: ignore
 from google.protobuf.struct_pb2 import Struct
 
-from whylogs.core.configs import SummaryConfig
+import whylogs.core.configs as conf
 from whylogs.core.metrics.maths import (
     VarianceM2Result,
     parallel_variance_m2,
     welford_online_variance_m2,
 )
 from whylogs.core.metrics.metric_components import (
     FractionalComponent,
@@ -33,42 +33,34 @@
 NUM = TypeVar("NUM", float, int)
 
 METRIC = TypeVar("METRIC", bound="Metric")
 
 
 @dataclass(frozen=True)
 class MetricConfig:
-    hll_lg_k: int = 12
-    kll_k: int = 256
-    fi_lg_max_k: int = 10  # 128 entries
-    fi_disabled: bool = False
-    track_unicode_ranges: bool = False
-    large_kll_k: bool = True
-    kll_k_large: int = 1024
-    unicode_ranges: Dict[str, Tuple[int, int]] = field(
-        default_factory=lambda: {
-            "emoticon": (0x1F600, 0x1F64F),
-            "control": (0x00, 0x1F),
-            "digits": (0x30, 0x39),
-            "latin-lower": (0x41, 0x5A),
-            "latin-upper": (0x61, 0x7A),
-            "basic-latin": (0x00, 0x7F),
-            "extended-latin": (0x0080, 0x02AF),
-        }
-    )
-    lower_case: bool = True  # Convert Unicode characters to lower-case before counting Unicode ranges
-    normalize: bool = True  # Unicode normalize strings before counting Unicode ranges
+    hll_lg_k: int = field(default_factory=lambda: conf.hll_lg_k)
+    kll_k: int = field(default_factory=lambda: conf.kll_k)
+    fi_lg_max_k: int = field(default_factory=lambda: conf.fi_lg_max_k)
+    fi_disabled: bool = field(default_factory=lambda: conf.fi_disabled)
+    track_unicode_ranges: bool = field(default_factory=lambda: conf.track_unicode_ranges)
+    large_kll_k: bool = field(default_factory=lambda: conf.large_kll_k)
+    kll_k_large: int = field(default_factory=lambda: conf.kll_k_large)
+    unicode_ranges: Dict[str, Tuple[int, int]] = field(default_factory=lambda: dict(conf.unicode_ranges))
+    lower_case: bool = field(default_factory=lambda: conf.lower_case)
+    normalize: bool = field(default_factory=lambda: conf.normalize)
+    max_frequent_item_size: int = field(default_factory=lambda: conf.max_frequent_item_size)
+    identity_column: Optional[str] = field(default_factory=lambda: conf.identity_column)
 
 
 _METRIC_DESERIALIZER_REGISTRY: Dict[str, Type[METRIC]] = {}  # type: ignore
 
 
-def custom_metric(metric: Type[METRIC], config: MetricConfig = MetricConfig()) -> Type[METRIC]:  # type: ignore
+def custom_metric(metric: Type[METRIC]) -> Type[METRIC]:  # type: ignore
     global _METRIC_DESERIALIZER_REGISTRY
-    _METRIC_DESERIALIZER_REGISTRY[metric.get_namespace(config)] = metric
+    _METRIC_DESERIALIZER_REGISTRY[metric.get_namespace()] = metric
     return metric
 
 
 @dataclass(frozen=True)
 class OperationResult:
     failures: int = 0
     successes: int = 0
@@ -85,28 +77,28 @@
         return OperationResult(
             successes=self.successes + other.successes,
             failures=self.failures + other.failures,
         )
 
 
 class Metric(ABC):
+    @property
+    def exclude_from_serialization(self) -> bool:
+        return False
+
     @classmethod
     # TODO: deprecate config argument
     def get_namespace(cls, config: Optional[MetricConfig] = None) -> str:
         return cls.zero().namespace
 
     @property
     @abstractmethod
     def namespace(self) -> str:
         raise NotImplementedError
 
-    def __post_init__(self):
-        global _METRIC_DESERIALIZER_REGISTRY
-        _METRIC_DESERIALIZER_REGISTRY[self.namespace] = self.__class__
-
     def __add__(self: METRIC, other: METRIC) -> METRIC:
         return self.merge(other)
 
     def merge(self: METRIC, other: METRIC) -> METRIC:
         res: Dict[str, MetricComponent] = {}
         for k, v in self.__dict__.items():
             if isinstance(v, MetricComponent):
@@ -130,15 +122,15 @@
         for k, v in self.__dict__.items():
             if not isinstance(v, MetricComponent):
                 continue
             res.append(k)
         return res
 
     @abstractmethod
-    def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Any]:
+    def to_summary_dict(self, cfg: Optional[conf.SummaryConfig] = None) -> Dict[str, Any]:
         raise NotImplementedError
 
     @abstractmethod
     def columnar_update(self, data: PreprocessedColumn) -> OperationResult:
         raise NotImplementedError
 
     @classmethod
@@ -154,14 +146,23 @@
         components: Dict[str, MetricComponent] = {}
         for k, m in msg.metric_components.items():
             components[k] = MetricComponent.from_protobuf(m)
 
         return cls(**components)
 
 
+def register_metric(metrics: Union[Metric, Type[METRIC], List[Metric], List[Type[METRIC]]]) -> None:
+    global _METRIC_DESERIALIZER_REGISTRY
+    if not isinstance(metrics, list):
+        metrics = [metrics]  # type: ignore
+
+    for metric in metrics:  # type: ignore
+        _METRIC_DESERIALIZER_REGISTRY[metric.get_namespace()] = metric  # type: ignore
+
+
 @dataclass(frozen=True)
 class IntsMetric(Metric):
     max: MaxIntegralComponent
     min: MinIntegralComponent
 
     @property
     def namespace(self) -> str:
@@ -171,57 +172,60 @@
         if data.len <= 0:
             return OperationResult.ok(0)
 
         successes = 0
 
         max_ = self.max.value
         min_ = self.min.value
-        if data.numpy.ints is not None:
+        if data.numpy.ints is not None and len(data.numpy.ints) > 0:
             max_ = max([max_, data.numpy.ints.max()])
             min_ = min([min_, data.numpy.ints.min()])
             successes += len(data.numpy.ints)
 
-        if data.list.ints is not None:
+        if data.list.ints is not None and len(data.list.ints) > 0:
             l_max = max(data.list.ints)
             l_min = min(data.list.ints)
             max_ = max([max_, l_max])
             min_ = min([min_, l_min])
             successes += len(data.list.ints)
 
         self.max.set(max_)
         self.min.set(min_)
         return OperationResult.ok(successes)
 
     @classmethod
     def zero(cls, config: Optional[MetricConfig] = None) -> "IntsMetric":
         return IntsMetric(max=MaxIntegralComponent(-sys.maxsize), min=MinIntegralComponent(sys.maxsize))
 
-    def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Union[int, float, str, None]]:
+    def to_summary_dict(self, cfg: Optional[conf.SummaryConfig] = None) -> Dict[str, Union[int, float, str, None]]:
         return {"max": self.maximum, "min": self.minimum}
 
     @property
     def maximum(self) -> float:
         return self.max.value
 
     @property
     def minimum(self) -> float:
         return self.min.value
 
 
+register_metric(IntsMetric)
+
+
 @dataclass(frozen=True)
 class DistributionMetric(Metric):
     kll: KllComponent
     mean: FractionalComponent
     m2: FractionalComponent
 
     @property
     def namespace(self) -> str:
         return "distribution"
 
-    def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Union[int, float, str, None]]:
+    def to_summary_dict(self, cfg: Optional[conf.SummaryConfig] = None) -> Dict[str, Union[int, float, str, None]]:
         if self.n == 0:
             quantiles = [None, None, None, None, None, None, None, None, None]
         else:
             quantiles = self.kll.value.get_quantiles([0.01, 0.05, 0.1, 0.25, 0.5, 0.75, 0.9, 0.95, 0.99])
         return {
             "mean": self.avg,
             "stddev": self.stddev,
@@ -259,15 +263,15 @@
             for arr in [view.numpy.floats, view.numpy.ints]:
                 if arr is not None:
                     self.kll.value.update(arr)
                     n_b = len(arr)
                     if n_b > 1:
                         n_b = len(arr)
                         mean_b = arr.mean()
-                        m2_b = arr.var() * (n_b - 1)
+                        m2_b = arr.var(ddof=1) * (n_b - 1)
 
                         second = VarianceM2Result(n=n_b, mean=mean_b, m2=m2_b)
                         first = parallel_variance_m2(first=first, second=second)
                     elif n_b == 1:
                         # fall back to https://en.wikipedia.org/wiki/Algorithms_for_calculating_variance
                         # #Weighted_incremental_algorithm
                         if isinstance(arr, pd.Series):
@@ -277,15 +281,15 @@
 
         for lst in [view.list.ints, view.list.floats]:
             if lst is not None and len(lst) > 0:
                 self.kll.value.update_list(lst)
                 n_b = len(lst)
                 if n_b > 1:
                     mean_b = statistics.mean(lst)
-                    m2_b = statistics.pvariance(lst) * (n_b - 1)
+                    m2_b = statistics.variance(lst) * (n_b - 1)
                     second = VarianceM2Result(n=n_b, mean=mean_b, m2=m2_b)
 
                     first = parallel_variance_m2(first=first, second=second)
                 else:
                     first = welford_online_variance_m2(existing=first, new_value=lst[0])
 
         self.mean.set(first.mean)
@@ -315,15 +319,15 @@
 
     @property
     def n(self) -> float:
         return self.kll.value.get_n()
 
     @property
     def variance(self) -> float:
-        """Returns the population variance of the stream.
+        """Returns the sample variance of the stream.
 
         https://en.wikipedia.org/wiki/Algorithms_for_calculating_variance#Welford's_online_algorithm
         """
         if self.n <= 1:
             return float(0)
         return self.m2.value / (self.kll.value.get_n() - 1)
 
@@ -333,76 +337,57 @@
             return float(0)
         return math.sqrt(self.variance)
 
     @property
     def avg(self) -> float:
         return self.mean.value
 
-    @property
-    def median(self) -> Optional[float]:
+    def get_quantile(self, quantile: float) -> Optional[float]:
         result = None
+        if quantile < 0 or quantile > 1:
+            raise ValueError(f"quantile={quantile} is not supported, please specify a value between 0 and 1 inclusive.")
         if self.n > 0:
-            result = self.kll.value.get_quantiles([0.5])[0]
+            result = self.kll.value.get_quantiles([quantile])[0]
         return result
 
     @property
+    def median(self) -> Optional[float]:
+        return self.get_quantile(0.5)
+
+    @property
     def q_01(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.01])[0]
-        return result
+        return self.get_quantile(0.01)
 
     @property
     def q_05(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.05])[0]
-        return result
+        return self.get_quantile(0.05)
 
     @property
     def q_10(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.1])[0]
-        return result
+        return self.get_quantile(0.1)
 
     @property
     def q_25(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.25])[0]
-        return result
+        return self.get_quantile(0.25)
 
     @property
     def q_75(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.75])[0]
-        return result
+        return self.get_quantile(0.75)
 
     @property
     def q_90(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.90])[0]
-        return result
+        return self.get_quantile(0.9)
 
     @property
     def q_95(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.95])[0]
-        return result
+        return self.get_quantile(0.95)
 
     @property
     def q_99(self) -> Optional[float]:
-        result = None
-        if self.n > 0:
-            result = self.kll.value.get_quantiles([0.99])[0]
-        return result
+        return self.get_quantile(0.99)
 
     @property
     def max(self) -> float:
         if self.kll.value.is_empty():
             return -sys.float_info.max
         return self.kll.value.get_max_value()
 
@@ -420,86 +405,99 @@
         return DistributionMetric(
             kll=KllComponent(sk),
             mean=FractionalComponent(0.0),
             m2=FractionalComponent(0.0),
         )
 
 
+register_metric(DistributionMetric)
+
+
 @dataclass(frozen=True)
 class FrequentItem:
     value: str
     est: int
     upper: int
     lower: int
 
 
 @dataclass(frozen=True)
 class FrequentItemsMetric(Metric):
     frequent_strings: FrequentStringsComponent
+    max_frequent_item_size: int = 128
 
     @property
     def namespace(self) -> str:
         return "frequent_items"
 
     def columnar_update(self, view: PreprocessedColumn) -> OperationResult:
         successes = 0
         for arr in [view.numpy.floats, view.numpy.ints]:
             if arr is not None:
-                if isinstance(arr, pd.Series):
-                    arr = arr.to_numpy()
                 self.frequent_strings.value.update_np(arr)
                 successes += len(arr)
+        # TODO: Include strings in above when we update whylogs-sketching fi.update_np to take strings
+        if view.numpy.strings is not None:
+            self.frequent_strings.value.update_str_list(view.numpy.strings.tolist())
+            successes += len(view.numpy.strings)
         if view.pandas.strings is not None:
-            self.frequent_strings.value.update_str_list(view.pandas.strings.to_list())
+            strings = [s[0 : self.max_frequent_item_size] for s in view.pandas.strings.to_list()]
+            self.frequent_strings.value.update_str_list(strings)
             successes += len(view.pandas.strings)
 
         if view.list.ints is not None:
             self.frequent_strings.value.update_int_list(view.list.ints)
             successes += len(view.list.ints)
 
         if view.list.floats is not None:
             self.frequent_strings.value.update_double_list(view.list.floats)
             successes += len(view.list.floats)
 
         if view.list.strings is not None:
-            self.frequent_strings.value.update_str_list(view.list.strings)
+            strings = [s[0 : self.max_frequent_item_size] for s in view.list.strings]
+            self.frequent_strings.value.update_str_list(strings)
             successes += len(view.list.strings)
 
         failures = 0
         if view.list.objs is not None:
             successes += len(view.list.objs)
         if view.pandas.objs is not None:
             successes += len(view.pandas.objs)
 
         return OperationResult(successes=successes, failures=failures)
 
-    def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Any]:
-        cfg = cfg or SummaryConfig()
+    def to_summary_dict(self, cfg: Optional[conf.SummaryConfig] = None) -> Dict[str, Any]:
+        cfg = cfg or conf.SummaryConfig()
         all_freq_items = self.frequent_strings.value.get_frequent_items(
             cfg.frequent_items_error_type.to_datasketches_type()
         )
         if cfg.frequent_items_limit > 0:
             limited_freq_items = all_freq_items[: cfg.frequent_items_limit]
         else:
             limited_freq_items = all_freq_items
-        items = [FrequentItem(value=x[0], est=x[1], upper=x[2], lower=x[3]) for x in limited_freq_items]
+        items = [FrequentItem(value=x[0], est=x[1], lower=x[2], upper=x[3]) for x in limited_freq_items]
         return {"frequent_strings": items}
 
     @property
     def strings(self) -> List[FrequentItem]:
         if self.frequent_strings.value.is_empty():
             return []
         summary = self.to_summary_dict()
         return summary["frequent_strings"]
 
     @classmethod
     def zero(cls, config: Optional[MetricConfig] = None) -> "FrequentItemsMetric":
         config = config or MetricConfig()
         sk = ds.frequent_strings_sketch(lg_max_k=config.fi_lg_max_k)
-        return FrequentItemsMetric(frequent_strings=FrequentStringsComponent(sk))
+        return FrequentItemsMetric(
+            frequent_strings=FrequentStringsComponent(sk), max_frequent_item_size=config.max_frequent_item_size
+        )
+
+
+register_metric(FrequentItemsMetric)
 
 
 @dataclass(frozen=True)
 class CardinalityMetric(Metric):
     hll: HllComponent
 
     @property
@@ -511,14 +509,18 @@
         if view.numpy.len > 0:
             if view.numpy.ints is not None:
                 self.hll.value.update_np(view.numpy.ints)
                 successes += len(view.numpy.ints)
             if view.numpy.floats is not None:
                 self.hll.value.update_np(view.numpy.floats)
                 successes += len(view.numpy.floats)
+            if view.numpy.strings is not None:
+                self.hll.value.update_str_list(view.numpy.strings.tolist())
+                successes += len(view.numpy.strings)
+
         if view.pandas.strings is not None:
             self.hll.value.update_str_list(view.pandas.strings.to_list())
             successes += len(view.pandas.strings)
 
         # update everything in the remaining lists
         if view.list.ints:
             self.hll.value.update_int_list(view.list.ints)
@@ -541,77 +543,93 @@
             successes += view.bool_count
 
         failures = 0
         if view.list.objs:
             failures = len(view.list.objs)
         return OperationResult(successes=successes, failures=failures)
 
-    def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Any]:
-        cfg = cfg or SummaryConfig()
+    def to_summary_dict(self, cfg: Optional[conf.SummaryConfig] = None) -> Dict[str, Any]:
+        cfg = cfg or conf.SummaryConfig()
         return {
             "est": self.hll.value.get_estimate(),
             f"upper_{cfg.hll_stddev}": self.hll.value.get_upper_bound(cfg.hll_stddev),
             f"lower_{cfg.hll_stddev}": self.hll.value.get_lower_bound(cfg.hll_stddev),
         }
 
     @property
     def estimate(self) -> Optional[float]:
         result = None
         if not self.hll.value.is_empty():
             result = self.hll.value.get_estimate()
 
         return result
 
-    @property
-    def upper_1(self) -> Optional[float]:
+    def get_upper_bound(self, number_of_standard_deviations: int) -> Optional[float]:
         result = None
         if not self.hll.value.is_empty():
-            result = self.hll.value.get_upper_bound(1)
+            result = self.hll.value.get_upper_bound(number_of_standard_deviations)
 
         return result
 
-    @property
-    def lower_1(self) -> Optional[float]:
+    def get_lower_bound(self, number_of_standard_deviations: int) -> Optional[float]:
         result = None
         if not self.hll.value.is_empty():
-            result = self.hll.value.get_lower_bound(1)
+            result = self.hll.value.get_lower_bound(number_of_standard_deviations)
 
         return result
 
+    @property
+    def upper_1(self) -> Optional[float]:
+        return self.get_upper_bound(1)
+
+    @property
+    def lower_1(self) -> Optional[float]:
+        return self.get_lower_bound(1)
+
     @classmethod
     def zero(cls, config: Optional[MetricConfig] = None) -> "CardinalityMetric":
         config = config or MetricConfig()
         sk = ds.hll_sketch(config.hll_lg_k)
         return CardinalityMetric(hll=HllComponent(sk))
 
 
+register_metric(CardinalityMetric)
+
+
 def _drop_private_fields(data: List[Tuple[str, Any]]) -> Dict[str, Any]:
     return {k: v for k, v in data if not k.startswith("_")}
 
 
 _STRUCT_NAME = "dataclass_param"
 
 
 class CustomMetricBase(Metric, ABC):
     """
     You can use this as a base class for custom metrics that don't use
     the supplied or custom MetricComponents. Subclasses must be decorated with
     @dataclass. All fields not prefixed with an underscore will be included
     in the summary and will be [de]serialized. Such subclasses will need to
-    implement the namespace, merge, and zero methods.
+    implement the namespace, merge, and zero methods. They should be registered
+    by calling register_metric()
     """
 
     def get_component_paths(self) -> List[str]:
         return [_STRUCT_NAME]  # Assumes everything to be serde'd will be in the Struct
 
-    def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Any]:
+    def to_summary_dict(self, cfg: Optional[conf.SummaryConfig] = None) -> Dict[str, Any]:
         return asdict(self, dict_factory=_drop_private_fields)
 
     def to_protobuf(self) -> MetricMessage:
         mcm = MetricComponentMessage(dataclass_param=Struct())
         mcm.dataclass_param.update(asdict(self, dict_factory=_drop_private_fields))
         return MetricMessage(metric_components={_STRUCT_NAME: mcm})
 
     @classmethod
     def from_protobuf(cls: Type[METRIC], msg: MetricMessage) -> METRIC:
         my_struct = msg.metric_components[_STRUCT_NAME].dataclass_param
         return cls(**my_struct)
+
+
+@dataclass
+class CardinalityThresholds:
+    few: int = 50
+    proportionately_few: float = 0.01
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/multimetric.py` & `whylogs-1.2.0/whylogs/core/metrics/multimetric.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,22 +1,30 @@
 import logging
-from abc import ABC
+from abc import ABC, abstractmethod
 from copy import deepcopy
 from typing import Any, Dict, List, Optional, Type, TypeVar
 
 from whylogs.core.configs import SummaryConfig
+from whylogs.core.datatypes import DataType
 from whylogs.core.errors import DeserializationError, UnsupportedError
 from whylogs.core.metrics import Metric
+from whylogs.core.metrics.metric_components import MetricComponent
 from whylogs.core.metrics.metrics import _METRIC_DESERIALIZER_REGISTRY, OperationResult
 from whylogs.core.preprocessing import PreprocessedColumn
 from whylogs.core.proto import MetricComponentMessage, MetricMessage
 
 logger = logging.getLogger(__name__)
 
 
+class SubmetricSchema(ABC):
+    @abstractmethod
+    def resolve(self, name: str, why_type: DataType, fi_disabled: bool = False) -> Dict[str, Metric]:
+        raise NotImplementedError
+
+
 MULTI_METRIC = TypeVar("MULTI_METRIC", bound="MultiMetric")
 
 
 def _do_submetric_merge(lhs: Dict[str, Metric], rhs: Dict[str, Metric]) -> Dict[str, Metric]:
     namespaces = set(lhs.keys())
     namespaces.update(rhs.keys())
     result: Dict[str, Metric] = {}
@@ -33,16 +41,16 @@
 
 class MultiMetric(Metric, ABC):
     """
     MultiMetric serves as a base class for custom metrics that consist
     of one or more metrics. It is handy when you need to do some
     processing of the logged values and track several metrics on
     the results. The sub-metrics must either be a StandardMetric, or tagged
-    as a @custom_metric or @dataclass. Note that MultiMetric is neither, so it
-    cannot be nested.
+    as a @custom_metric or registered via register_metric(). Note that
+    MultiMetric is neither, so it cannot be nested.
 
     Typically you will need to override namespace(); columnar_update(), calling
     it on the submetrics as needed; and the zero() method to return an
     appropriate "empty" instance of your metric. You will need to override from_protobuf()
     and merge() if your subclass __init__() method takes arguments different than
     MultiMetrtic's. You can use the submetrics_from_protbuf() and merge_submetrics()
     helper methods to implement them. The MultiMetric class will handle the rest of
@@ -71,15 +79,15 @@
             raise ValueError(f"Invalid namespace {self.namespace}")
         for sub_name in submetrics.keys():
             if ":" in sub_name or "/" in sub_name:
                 raise ValueError(f"Invalid submetric name {sub_name}")
 
         self.submetrics = deepcopy(submetrics)
 
-    def merge_submetrics(self: MULTI_METRIC, other: MULTI_METRIC) -> Dict[str, Metric]:
+    def merge_submetrics(self: MULTI_METRIC, other: MULTI_METRIC) -> Dict[str, Dict[str, Metric]]:
         if self.namespace != other.namespace:
             raise ValueError(f"Attempt to merge MultiMetrics {self.namespace} and {other.namespace}")
 
         submetric_names = set(self.submetrics.keys())
         submetric_names.update(other.submetrics.keys())
         submetrics: Dict[str, Dict[str, Metric]] = dict()
         for submetric_name in submetric_names:
@@ -110,14 +118,19 @@
     def get_component_paths(self) -> List[str]:
         res = []
         for sub_name, metrics in self.submetrics.items():
             for namespace, metric in metrics.items():
                 for comp_name in metric.get_component_paths():
                     res.append(f"{sub_name}:{namespace}/{comp_name}")
 
+        for k, v in self.__dict__.items():  # Grab any components that aren't in submetrics
+            if not isinstance(v, MetricComponent):
+                continue
+            res.append(k)
+
         return res
 
     def to_summary_dict(self, cfg: Optional[SummaryConfig] = None) -> Dict[str, Any]:
         cfg = cfg or SummaryConfig()
         summary = {}
         for sub_name, metrics in self.submetrics.items():
             for namespace, metric in metrics.items():
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/serializers.py` & `whylogs-1.2.0/whylogs/core/metrics/serializers.py`

 * *Files 2% similar despite different names*

```diff
@@ -87,21 +87,21 @@
 
 
 @_builtin_serializer(name="kll")
 def _kll(sketch: ds.kll_doubles_sketch) -> MetricComponentMessage:
     return MetricComponentMessage(kll=KllSketchMessage(sketch=sketch.serialize()))
 
 
-@_builtin_serializer(name="kll")
-def _hll_merge(sketch: ds.hll_sketch) -> MetricComponentMessage:
+@_builtin_serializer(name="hll")
+def _hll(sketch: ds.hll_sketch) -> MetricComponentMessage:
     return MetricComponentMessage(hll=HllSketchMessage(sketch=sketch.serialize_compact()))
 
 
-@_builtin_serializer(name="kll")
-def _fs_merge(sketch: ds.frequent_strings_sketch) -> MetricComponentMessage:
+@_builtin_serializer(name="fs")
+def _fs(sketch: ds.frequent_strings_sketch) -> MetricComponentMessage:
     msg = FrequentItemsSketchMessage(sketch=sketch.serialize())
 
     return MetricComponentMessage(frequent_items=msg)
 
 
 class SerializerRegistry:
     def __init__(self) -> None:
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/metrics/unicode_range.py` & `whylogs-1.2.0/whylogs/core/metrics/unicode_range.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 from whylogs.core.metrics.column_metrics import ColumnCountsMetric, TypeCountersMetric
 from whylogs.core.metrics.metrics import (
     CardinalityMetric,
     DistributionMetric,
     IntsMetric,
     MetricConfig,
     OperationResult,
+    register_metric,
 )
 from whylogs.core.metrics.multimetric import MultiMetric
 from whylogs.core.preprocessing import PreprocessedColumn
 from whylogs.core.proto import MetricMessage
 
 _STRING_LENGTH = "string_length"
 
@@ -34,15 +35,14 @@
     """
 
     range_definitions: Dict[str, Tuple[int, int]]
     lower_case: bool = True
     normalize: bool = True
 
     def __post_init__(self):
-        super(type(self), self).__post_init__()
         self.range_definitions["UNKNOWN"] = (0, 0)  # catchall for characters not in a defined range
         for key, range in self.range_definitions.items():
             if range[0] > range[1]:
                 raise ValueError(f"Invalid codepoint range {key}")
             if range[0] < 0 or 0x10FFFF < range[1]:
                 raise ValueError(f"Invalid codepoint range {key}")
             if ":" in key or "/" in key:
@@ -95,21 +95,20 @@
                         found = True
                 if not found:
                     range_counter["UNKNOWN"] += 1
 
             for range_name, range_count in range_counter.items():
                 range_data[range_name].append(range_count)
 
-        submetric_col = PreprocessedColumn()
-        submetric_col.list.ints = lengths
+        submetric_col = PreprocessedColumn.apply(lengths)
         for metric in self.submetrics[_STRING_LENGTH].values():
             metric.columnar_update(submetric_col)
 
         for range_name, range_list in range_data.items():
-            submetric_col.list.ints = range_list
+            submetric_col = PreprocessedColumn.apply(range_list)
             for metric in self.submetrics[range_name].values():
                 metric.columnar_update(submetric_col)
 
         return OperationResult.ok(len(data))
 
     @classmethod
     def zero(cls, config: Optional[MetricConfig] = None) -> "UnicodeRangeMetric":
@@ -122,7 +121,11 @@
         # The MetricMessage doesn't contain the range definitions, so we preserve
         # the range names with empty bounds
         ranges = {sub_name: (0, 0) for sub_name in submetrics.keys()}
         del ranges[_STRING_LENGTH]
         result = cls(ranges)
         result.submetrics = submetrics
         return result
+
+
+# Register it so Multimetric and ProfileView can deserialize
+register_metric(UnicodeRangeMetric)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/model_performance_metrics/confusion_matrix.py` & `whylogs-1.2.0/whylogs/core/model_performance_metrics/confusion_matrix.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,15 +38,15 @@
 
     Attributes:
         labels: list of labels in a sorted order
     """
 
     def __init__(
         self,
-        labels: List[Union[str, int, bool, float]] = None,
+        labels: Optional[List[Union[str, int, bool, float]]] = None,
     ):
         if labels:
             labels_size = len(labels)
             if labels_size > MODEL_METRICS_LABEL_SIZE_WARNING_THRESHOLD:
                 _logger.warning(
                     f"The initialized confusion matrix has {labels_size} labels and the resulting"
                     " confusion matrix will be larger than is recommended with whylogs current"
@@ -142,15 +142,14 @@
         conf_matrix = _merge_CM(self, conf_matrix)
         conf_matrix = _merge_CM(other_cm, conf_matrix)
 
         return conf_matrix
 
     @staticmethod
     def _dist_to_numbers(dist: Optional[DistributionMetric]) -> NumbersMessageV0:
-
         variance_message = VarianceMessage()
 
         if dist is None or dist.kll.value.is_empty():
             return NumbersMessageV0(histogram=EMPTY_KLL, compact_theta=EMPTY_THETA, variance=variance_message)
 
         variance_message = VarianceMessage(count=dist.n, sum=dist.m2.value, mean=dist.mean.value)
         return NumbersMessageV0(
@@ -167,15 +166,15 @@
             kll=KllComponent(doubles_sk),
             mean=FractionalComponent(numbers.variance.mean),
             m2=FractionalComponent(numbers.variance.sum),
         )
 
     def to_protobuf(
         self,
-    ):
+    ) -> ScoreMatrixMessage:
         """
         Convert to protobuf
 
         Returns:
             TYPE: Description
         """
         size = len(self.labels)
@@ -194,15 +193,15 @@
             scores=confusion_matrix_entries,
         )
 
     @classmethod
     def from_protobuf(
         cls,
         message: ScoreMatrixMessage,
-    ):
+    ) -> Optional["ConfusionMatrix"]:
         if message is None or message.ByteSize() == 0:
             return None
         labels = message.labels
         num_labels = len(labels)
         matrix = dict()
         for i in range(num_labels):
             for j in range(num_labels):
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/model_performance_metrics/model_performance_metrics.py` & `whylogs-1.2.0/whylogs/core/model_performance_metrics/model_performance_metrics.py`

 * *Files 1% similar despite different names*

```diff
@@ -32,15 +32,14 @@
         self.regression_metrics = regression_metrics
         self.metrics = metrics
         self.field_metadata = field_metadata
 
     def to_protobuf(
         self,
     ) -> ModelProfileMessage:
-
         model_type = ModelType.UNKNOWN
         if not self.model_type:
             if self.confusion_matrix:
                 model_type = ModelType.CLASSIFICATION
             elif self.regression_metrics:
                 model_type = ModelType.REGRESSION
         else:
@@ -77,15 +76,15 @@
             confusion_matrix=confusion_matrix, regression_metrics=regression_metrics, field_metadata=output_fields
         )
 
     def compute_confusion_matrix(
         self,
         predictions: List[Union[str, int, bool, float]],
         targets: List[Union[str, int, bool, float]],
-        scores: List[float] = None,
+        scores: Optional[List[float]] = None,
     ):
         """
         computes the confusion_matrix, if one is already present merges to old one.
 
         Args:
             predictions (List[Union[str, int, bool]]):
             targets (List[Union[str, int, bool]]):
@@ -140,15 +139,15 @@
                 field_categories = self.field_metadata[column_name]
                 if OUTPUT_FIELD_CATEGORY in field_categories:
                     if output_column_names is None:
                         output_column_names = []
                     output_column_names.append(column_name)
         return output_column_names
 
-    def merge(self, other):
+    def merge(self, other) -> "ModelPerformanceMetrics":
         """
         :type other: ModelMetrics
         """
         if other is None or (other.confusion_matrix is None and other.regression_metrics is None):
             return self
 
         merged_field_metadata: Optional[Dict[str, Set[str]]] = None
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/model_performance_metrics/regression_metrics.py` & `whylogs-1.2.0/whylogs/core/model_performance_metrics/regression_metrics.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,15 +18,14 @@
         Args:
             predictions (List[float]):
             targets (List[float]):
         """
 
         # need to vectorize this
         for idx, target in enumerate(targets):
-
             self.sum_abs_diff += abs(predictions[idx] - target)
             self.sum_diff += predictions[idx] - target
             self.sum2_diff += (predictions[idx] - target) ** 2
             # To add later
             # self.nt_diff.track(predictions[idx] - target)
             self.count += 1
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_constraints_pb2.py` & `whylogs-1.2.0/whylogs/core/proto/v0/v0_constraints_pb2.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_constraints_pb2.pyi` & `whylogs-1.2.0/whylogs/core/proto/v0/v0_constraints_pb2.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -21,15 +21,15 @@
 
 DESCRIPTOR: google.protobuf.descriptor.FileDescriptor
 
 class _Op:
     ValueType = typing.NewType("ValueType", builtins.int)
     V: typing_extensions.TypeAlias = ValueType
 
-class _OpEnumTypeWrapper(google.protobuf.internal.enum_type_wrapper._EnumTypeWrapper[_Op.ValueType], builtins.type):  # noqa: F821
+class _OpEnumTypeWrapper(google.protobuf.internal.enum_type_wrapper._EnumTypeWrapper[_Op.ValueType], builtins.type):
     DESCRIPTOR: google.protobuf.descriptor.EnumDescriptor
     unused: _Op.ValueType  # 0
     LT: _Op.ValueType  # 1
     LE: _Op.ValueType  # 2
     EQ: _Op.ValueType  # 3
     NE: _Op.ValueType  # 4
     GE: _Op.ValueType  # 5
@@ -65,14 +65,15 @@
 APPLY_FUNC: Op.ValueType  # 13
 IN: Op.ValueType  # 14
 CONTAIN: Op.ValueType  # 15
 NOT_IN: Op.ValueType  # 16
 SUM: Op.ValueType  # 17
 global___Op = Op
 
+@typing_extensions.final
 class SummaryConstraintMsg(google.protobuf.message.Message):
     """Summary constraints specify a relationship between a summary field and a literal value,
     or between two summary fields.
     e.g.     'min' < 6
     'std_dev' < 2.17
     'min' > 'avg'
     """
@@ -128,14 +129,15 @@
     @typing.overload
     def WhichOneof(self, oneof_group: typing_extensions.Literal["reference_distribution", b"reference_distribution"]) -> typing_extensions.Literal["continuous_distribution", "discrete_distribution"] | None: ...
     @typing.overload
     def WhichOneof(self, oneof_group: typing_extensions.Literal["second", b"second"]) -> typing_extensions.Literal["second_field", "value", "between", "reference_set", "value_str"] | None: ...
 
 global___SummaryConstraintMsg = SummaryConstraintMsg
 
+@typing_extensions.final
 class ReferenceDistributionContinuousMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     @property
     def sketch(self) -> v0_messages_pb2.KllFloatsSketchMessage: ...
     def __init__(
@@ -144,14 +146,15 @@
         sketch: v0_messages_pb2.KllFloatsSketchMessage | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["sketch", b"sketch"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["sketch", b"sketch"]) -> None: ...
 
 global___ReferenceDistributionContinuousMessage = ReferenceDistributionContinuousMessage
 
+@typing_extensions.final
 class ReferenceDistributionDiscreteMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     FREQUENT_ITEMS_FIELD_NUMBER: builtins.int
     UNIQUE_COUNT_FIELD_NUMBER: builtins.int
     TOTAL_COUNT_FIELD_NUMBER: builtins.int
     @property
@@ -167,14 +170,15 @@
         total_count: builtins.float = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["frequent_items", b"frequent_items", "unique_count", b"unique_count"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["frequent_items", b"frequent_items", "total_count", b"total_count", "unique_count", b"unique_count"]) -> None: ...
 
 global___ReferenceDistributionDiscreteMessage = ReferenceDistributionDiscreteMessage
 
+@typing_extensions.final
 class SummaryBetweenConstraintMsg(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SECOND_FIELD_FIELD_NUMBER: builtins.int
     LOWER_VALUE_FIELD_NUMBER: builtins.int
     THIRD_FIELD_FIELD_NUMBER: builtins.int
     UPPER_VALUE_FIELD_NUMBER: builtins.int
@@ -195,14 +199,15 @@
     @typing.overload
     def WhichOneof(self, oneof_group: typing_extensions.Literal["lower", b"lower"]) -> typing_extensions.Literal["second_field", "lower_value"] | None: ...
     @typing.overload
     def WhichOneof(self, oneof_group: typing_extensions.Literal["upper", b"upper"]) -> typing_extensions.Literal["third_field", "upper_value"] | None: ...
 
 global___SummaryBetweenConstraintMsg = SummaryBetweenConstraintMsg
 
+@typing_extensions.final
 class ApplyFunctionMsg(google.protobuf.message.Message):
     """ValueConstraints express a binary boolean relationship between an implied numeric value and a literal, or between a string value and a regex pattern.
     These are applied to every incoming value that is processed by whylogs.
     """
 
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
@@ -216,14 +221,15 @@
         function: builtins.str = ...,
         reference_value: builtins.str = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["function", b"function", "reference_value", b"reference_value"]) -> None: ...
 
 global___ApplyFunctionMsg = ApplyFunctionMsg
 
+@typing_extensions.final
 class ValueConstraintMsg(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     NAME_FIELD_NUMBER: builtins.int
     VALUE_FIELD_NUMBER: builtins.int
     REGEX_PATTERN_FIELD_NUMBER: builtins.int
     VALUE_SET_FIELD_NUMBER: builtins.int
@@ -258,14 +264,15 @@
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["function", b"function", "regex_pattern", b"regex_pattern", "second_field", b"second_field", "value", b"value", "value_set", b"value_set"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["failures", b"failures", "function", b"function", "name", b"name", "op", b"op", "regex_pattern", b"regex_pattern", "second_field", b"second_field", "total", b"total", "value", b"value", "value_set", b"value_set", "verbose", b"verbose"]) -> None: ...
     def WhichOneof(self, oneof_group: typing_extensions.Literal["second_field", b"second_field"]) -> typing_extensions.Literal["value", "regex_pattern", "value_set", "function"] | None: ...
 
 global___ValueConstraintMsg = ValueConstraintMsg
 
+@typing_extensions.final
 class MultiColumnValueConstraintMsg(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     NAME_FIELD_NUMBER: builtins.int
     DEPENDENT_COLUMNS_FIELD_NUMBER: builtins.int
     DEPENDENT_COLUMN_FIELD_NUMBER: builtins.int
     VALUE_FIELD_NUMBER: builtins.int
@@ -310,14 +317,15 @@
     @typing.overload
     def WhichOneof(self, oneof_group: typing_extensions.Literal["dependent", b"dependent"]) -> typing_extensions.Literal["dependent_columns", "dependent_column"] | None: ...
     @typing.overload
     def WhichOneof(self, oneof_group: typing_extensions.Literal["reference", b"reference"]) -> typing_extensions.Literal["value", "value_set", "reference_columns"] | None: ...
 
 global___MultiColumnValueConstraintMsg = MultiColumnValueConstraintMsg
 
+@typing_extensions.final
 class ValueConstraintMsgs(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     CONSTRAINTS_FIELD_NUMBER: builtins.int
     MULTI_COLUMN_CONSTRAINTS_FIELD_NUMBER: builtins.int
     @property
     def constraints(self) -> google.protobuf.internal.containers.RepeatedCompositeFieldContainer[global___ValueConstraintMsg]: ...
@@ -329,14 +337,15 @@
         constraints: collections.abc.Iterable[global___ValueConstraintMsg] | None = ...,
         multi_column_constraints: collections.abc.Iterable[global___MultiColumnValueConstraintMsg] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["constraints", b"constraints", "multi_column_constraints", b"multi_column_constraints"]) -> None: ...
 
 global___ValueConstraintMsgs = ValueConstraintMsgs
 
+@typing_extensions.final
 class SummaryConstraintMsgs(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     CONSTRAINTS_FIELD_NUMBER: builtins.int
     @property
     def constraints(self) -> google.protobuf.internal.containers.RepeatedCompositeFieldContainer[global___SummaryConstraintMsg]: ...
     def __init__(
@@ -344,17 +353,19 @@
         *,
         constraints: collections.abc.Iterable[global___SummaryConstraintMsg] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["constraints", b"constraints"]) -> None: ...
 
 global___SummaryConstraintMsgs = SummaryConstraintMsgs
 
+@typing_extensions.final
 class DatasetConstraintMsg(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class ValueConstraintsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -364,14 +375,15 @@
             *,
             key: builtins.str = ...,
             value: global___ValueConstraintMsgs | None = ...,
         ) -> None: ...
         def HasField(self, field_name: typing_extensions.Literal["value", b"value"]) -> builtins.bool: ...
         def ClearField(self, field_name: typing_extensions.Literal["key", b"key", "value", b"value"]) -> None: ...
 
+    @typing_extensions.final
     class SummaryConstraintsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_messages_pb2.py` & `whylogs-1.2.0/whylogs/core/proto/v0/v0_messages_pb2.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_messages_pb2.pyi` & `whylogs-1.2.0/whylogs/core/proto/v0/v0_messages_pb2.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -19,15 +19,15 @@
 
 DESCRIPTOR: google.protobuf.descriptor.FileDescriptor
 
 class _ModelType:
     ValueType = typing.NewType("ValueType", builtins.int)
     V: typing_extensions.TypeAlias = ValueType
 
-class _ModelTypeEnumTypeWrapper(google.protobuf.internal.enum_type_wrapper._EnumTypeWrapper[_ModelType.ValueType], builtins.type):  # noqa: F821
+class _ModelTypeEnumTypeWrapper(google.protobuf.internal.enum_type_wrapper._EnumTypeWrapper[_ModelType.ValueType], builtins.type):
     DESCRIPTOR: google.protobuf.descriptor.EnumDescriptor
     UNKNOWN: _ModelType.ValueType  # 0
     CLASSIFICATION: _ModelType.ValueType  # 1
     REGRESSION: _ModelType.ValueType  # 2
     EMBEDDINGS: _ModelType.ValueType  # 3
     NLP: _ModelType.ValueType  # 4
 
@@ -36,14 +36,15 @@
 UNKNOWN: ModelType.ValueType  # 0
 CLASSIFICATION: ModelType.ValueType  # 1
 REGRESSION: ModelType.ValueType  # 2
 EMBEDDINGS: ModelType.ValueType  # 3
 NLP: ModelType.ValueType  # 4
 global___ModelType = ModelType
 
+@typing_extensions.final
 class CountersV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     COUNT_FIELD_NUMBER: builtins.int
     TRUE_COUNT_FIELD_NUMBER: builtins.int
     NULL_COUNT_FIELD_NUMBER: builtins.int
     count: builtins.int
@@ -59,14 +60,15 @@
         null_count: google.protobuf.wrappers_pb2.Int64Value | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["null_count", b"null_count", "true_count", b"true_count"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["count", b"count", "null_count", b"null_count", "true_count", b"true_count"]) -> None: ...
 
 global___CountersV0 = CountersV0
 
+@typing_extensions.final
 class InferredType(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     class _Type:
         ValueType = typing.NewType("ValueType", builtins.int)
         V: typing_extensions.TypeAlias = ValueType
 
@@ -97,14 +99,15 @@
         type: global___InferredType.Type.ValueType = ...,
         ratio: builtins.float = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["ratio", b"ratio", "type", b"type"]) -> None: ...
 
 global___InferredType = InferredType
 
+@typing_extensions.final
 class DoublesMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     COUNT_FIELD_NUMBER: builtins.int
     MIN_FIELD_NUMBER: builtins.int
     MAX_FIELD_NUMBER: builtins.int
     SUM_FIELD_NUMBER: builtins.int
@@ -120,14 +123,15 @@
         max: builtins.float = ...,
         sum: builtins.float = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["count", b"count", "max", b"max", "min", b"min", "sum", b"sum"]) -> None: ...
 
 global___DoublesMessage = DoublesMessage
 
+@typing_extensions.final
 class LongsMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     COUNT_FIELD_NUMBER: builtins.int
     MIN_FIELD_NUMBER: builtins.int
     MAX_FIELD_NUMBER: builtins.int
     SUM_FIELD_NUMBER: builtins.int
@@ -143,14 +147,15 @@
         max: builtins.int = ...,
         sum: builtins.int = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["count", b"count", "max", b"max", "min", b"min", "sum", b"sum"]) -> None: ...
 
 global___LongsMessage = LongsMessage
 
+@typing_extensions.final
 class VarianceMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     COUNT_FIELD_NUMBER: builtins.int
     SUM_FIELD_NUMBER: builtins.int
     MEAN_FIELD_NUMBER: builtins.int
     count: builtins.int
@@ -164,14 +169,15 @@
         sum: builtins.float = ...,
         mean: builtins.float = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["count", b"count", "mean", b"mean", "sum", b"sum"]) -> None: ...
 
 global___VarianceMessage = VarianceMessage
 
+@typing_extensions.final
 class FrequentNumbersSketchMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     LG_MAX_K_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     lg_max_k: builtins.int
@@ -181,14 +187,15 @@
         sketch: builtins.bytes = ...,
         lg_max_k: builtins.int = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["lg_max_k", b"lg_max_k", "sketch", b"sketch"]) -> None: ...
 
 global___FrequentNumbersSketchMessage = FrequentNumbersSketchMessage
 
+@typing_extensions.final
 class FrequentItemsSketchMessageV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     LG_MAX_K_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     lg_max_k: builtins.int
@@ -198,14 +205,15 @@
         sketch: builtins.bytes = ...,
         lg_max_k: builtins.int = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["lg_max_k", b"lg_max_k", "sketch", b"sketch"]) -> None: ...
 
 global___FrequentItemsSketchMessageV0 = FrequentItemsSketchMessageV0
 
+@typing_extensions.final
 class NumbersMessageV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     VARIANCE_FIELD_NUMBER: builtins.int
     DOUBLES_FIELD_NUMBER: builtins.int
     LONGS_FIELD_NUMBER: builtins.int
     HISTOGRAM_FIELD_NUMBER: builtins.int
@@ -237,17 +245,19 @@
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["doubles", b"doubles", "frequent_numbers", b"frequent_numbers", "longs", b"longs", "numbers", b"numbers", "variance", b"variance"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["compact_theta", b"compact_theta", "doubles", b"doubles", "frequent_numbers", b"frequent_numbers", "histogram", b"histogram", "longs", b"longs", "numbers", b"numbers", "theta", b"theta", "variance", b"variance"]) -> None: ...
     def WhichOneof(self, oneof_group: typing_extensions.Literal["numbers", b"numbers"]) -> typing_extensions.Literal["doubles", "longs"] | None: ...
 
 global___NumbersMessageV0 = NumbersMessageV0
 
+@typing_extensions.final
 class CharPosMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class CharPosMapEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -272,14 +282,15 @@
         char_list: builtins.str = ...,
         char_pos_map: collections.abc.Mapping[builtins.str, global___NumbersMessageV0] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["char_list", b"char_list", "char_pos_map", b"char_pos_map"]) -> None: ...
 
 global___CharPosMessage = CharPosMessage
 
+@typing_extensions.final
 class StringsMessageV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     COUNT_FIELD_NUMBER: builtins.int
     THETA_FIELD_NUMBER: builtins.int
     ITEMS_FIELD_NUMBER: builtins.int
     COMPACT_THETA_FIELD_NUMBER: builtins.int
@@ -309,17 +320,19 @@
         char_pos_tracker: global___CharPosMessage | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["char_pos_tracker", b"char_pos_tracker", "length", b"length", "token_length", b"token_length"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["char_pos_tracker", b"char_pos_tracker", "compact_theta", b"compact_theta", "count", b"count", "items", b"items", "length", b"length", "theta", b"theta", "token_length", b"token_length"]) -> None: ...
 
 global___StringsMessageV0 = StringsMessageV0
 
+@typing_extensions.final
 class SchemaMessageV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class TypeCountsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.int
         value: builtins.int
@@ -344,14 +357,15 @@
         inferred_type: global___InferredType | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["inferred_type", b"inferred_type"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["inferred_type", b"inferred_type", "typeCounts", b"typeCounts"]) -> None: ...
 
 global___SchemaMessageV0 = SchemaMessageV0
 
+@typing_extensions.final
 class ColumnMessageV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     NAME_FIELD_NUMBER: builtins.int
     COUNTERS_FIELD_NUMBER: builtins.int
     SCHEMA_FIELD_NUMBER: builtins.int
     NUMBERS_FIELD_NUMBER: builtins.int
@@ -387,17 +401,19 @@
         cardinality_tracker: global___HllSketchMessageV0 | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["cardinality_tracker", b"cardinality_tracker", "counters", b"counters", "frequent_items", b"frequent_items", "inferred_type", b"inferred_type", "numbers", b"numbers", "schema", b"schema", "strings", b"strings"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["cardinality_tracker", b"cardinality_tracker", "counters", b"counters", "frequent_items", b"frequent_items", "inferred_type", b"inferred_type", "name", b"name", "numbers", b"numbers", "schema", b"schema", "strings", b"strings"]) -> None: ...
 
 global___ColumnMessageV0 = ColumnMessageV0
 
+@typing_extensions.final
 class DatasetPropertiesV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class TagsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         value: builtins.str
@@ -405,14 +421,15 @@
             self,
             *,
             key: builtins.str = ...,
             value: builtins.str = ...,
         ) -> None: ...
         def ClearField(self, field_name: typing_extensions.Literal["key", b"key", "value", b"value"]) -> None: ...
 
+    @typing_extensions.final
     class MetadataEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         value: builtins.str
@@ -452,14 +469,15 @@
         tags: collections.abc.Mapping[builtins.str, builtins.str] | None = ...,
         metadata: collections.abc.Mapping[builtins.str, builtins.str] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["data_timestamp", b"data_timestamp", "metadata", b"metadata", "schema_major_version", b"schema_major_version", "schema_minor_version", b"schema_minor_version", "session_id", b"session_id", "session_timestamp", b"session_timestamp", "tags", b"tags"]) -> None: ...
 
 global___DatasetPropertiesV0 = DatasetPropertiesV0
 
+@typing_extensions.final
 class ScoreMatrixMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     LABELS_FIELD_NUMBER: builtins.int
     PREDICTION_FIELD_FIELD_NUMBER: builtins.int
     TARGET_FIELD_FIELD_NUMBER: builtins.int
     SCORE_FIELD_FIELD_NUMBER: builtins.int
@@ -481,14 +499,15 @@
         score_field: builtins.str = ...,
         scores: collections.abc.Iterable[global___NumbersMessageV0] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["labels", b"labels", "prediction_field", b"prediction_field", "score_field", b"score_field", "scores", b"scores", "target_field", b"target_field"]) -> None: ...
 
 global___ScoreMatrixMessage = ScoreMatrixMessage
 
+@typing_extensions.final
 class RegressionMetricsMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     PREDICTION_FIELD_FIELD_NUMBER: builtins.int
     TARGET_FIELD_FIELD_NUMBER: builtins.int
     COUNT_FIELD_NUMBER: builtins.int
     SUM_ABS_DIFF_FIELD_NUMBER: builtins.int
@@ -510,14 +529,15 @@
         sum_diff: builtins.float = ...,
         sum2_diff: builtins.float = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["count", b"count", "prediction_field", b"prediction_field", "sum2_diff", b"sum2_diff", "sum_abs_diff", b"sum_abs_diff", "sum_diff", b"sum_diff", "target_field", b"target_field"]) -> None: ...
 
 global___RegressionMetricsMessage = RegressionMetricsMessage
 
+@typing_extensions.final
 class ModelMetricsMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SCOREMATRIX_FIELD_NUMBER: builtins.int
     MODELTYPE_FIELD_NUMBER: builtins.int
     REGRESSIONMETRICS_FIELD_NUMBER: builtins.int
     @property
@@ -533,14 +553,15 @@
         regressionMetrics: global___RegressionMetricsMessage | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["regressionMetrics", b"regressionMetrics", "scoreMatrix", b"scoreMatrix"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["modelType", b"modelType", "regressionMetrics", b"regressionMetrics", "scoreMatrix", b"scoreMatrix"]) -> None: ...
 
 global___ModelMetricsMessage = ModelMetricsMessage
 
+@typing_extensions.final
 class ModelProfileMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     OUTPUT_FIELDS_FIELD_NUMBER: builtins.int
     METRICS_FIELD_NUMBER: builtins.int
     @property
     def output_fields(self) -> google.protobuf.internal.containers.RepeatedScalarFieldContainer[builtins.str]:
@@ -554,17 +575,19 @@
         metrics: global___ModelMetricsMessage | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["metrics", b"metrics"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["metrics", b"metrics", "output_fields", b"output_fields"]) -> None: ...
 
 global___ModelProfileMessage = ModelProfileMessage
 
+@typing_extensions.final
 class DatasetProfileMessageV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class ColumnsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -596,14 +619,15 @@
         modeProfile: global___ModelProfileMessage | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["modeProfile", b"modeProfile", "properties", b"properties"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["columns", b"columns", "modeProfile", b"modeProfile", "properties", b"properties"]) -> None: ...
 
 global___DatasetProfileMessageV0 = DatasetProfileMessageV0
 
+@typing_extensions.final
 class ColumnsChunkSegment(google.protobuf.message.Message):
     """*
     The follow section is for transmission and reconstruction of the dataset
     in WhyLogs backend
     """
 
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
@@ -622,14 +646,15 @@
         marker: builtins.str = ...,
         columns: collections.abc.Iterable[global___ColumnMessageV0] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["columns", b"columns", "marker", b"marker"]) -> None: ...
 
 global___ColumnsChunkSegment = ColumnsChunkSegment
 
+@typing_extensions.final
 class DatasetMetadataSegment(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     MARKER_FIELD_NUMBER: builtins.int
     PROPERTIES_FIELD_NUMBER: builtins.int
     marker: builtins.str
     @property
@@ -641,14 +666,15 @@
         properties: global___DatasetPropertiesV0 | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["properties", b"properties"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["marker", b"marker", "properties", b"properties"]) -> None: ...
 
 global___DatasetMetadataSegment = DatasetMetadataSegment
 
+@typing_extensions.final
 class MessageSegment(google.protobuf.message.Message):
     """A segment of a dataset profile. This can be used to composed the
     original object back
     """
 
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
@@ -669,14 +695,15 @@
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["columns", b"columns", "item", b"item", "metadata", b"metadata"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["columns", b"columns", "item", b"item", "marker", b"marker", "metadata", b"metadata"]) -> None: ...
     def WhichOneof(self, oneof_group: typing_extensions.Literal["item", b"item"]) -> typing_extensions.Literal["metadata", "columns"] | None: ...
 
 global___MessageSegment = MessageSegment
 
+@typing_extensions.final
 class HllSketchMessageV0(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     LG_K_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     lg_k: builtins.int
@@ -686,14 +713,15 @@
         sketch: builtins.bytes = ...,
         lg_k: builtins.int = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["lg_k", b"lg_k", "sketch", b"sketch"]) -> None: ...
 
 global___HllSketchMessageV0 = HllSketchMessageV0
 
+@typing_extensions.final
 class KllFloatsSketchMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     LG_K_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     lg_k: builtins.int
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_summaries_pb2.py` & `whylogs-1.2.0/whylogs/core/proto/v0/v0_summaries_pb2.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/v0/v0_summaries_pb2.pyi` & `whylogs-1.2.0/whylogs/core/proto/v0/v0_summaries_pb2.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 if sys.version_info >= (3, 8):
     import typing as typing_extensions
 else:
     import typing_extensions
 
 DESCRIPTOR: google.protobuf.descriptor.FileDescriptor
 
+@typing_extensions.final
 class UniqueCountSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     ESTIMATE_FIELD_NUMBER: builtins.int
     UPPER_FIELD_NUMBER: builtins.int
     LOWER_FIELD_NUMBER: builtins.int
     estimate: builtins.float
@@ -34,17 +35,19 @@
         upper: builtins.float = ...,
         lower: builtins.float = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["estimate", b"estimate", "lower", b"lower", "upper", b"upper"]) -> None: ...
 
 global___UniqueCountSummary = UniqueCountSummary
 
+@typing_extensions.final
 class FrequentStringsSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class FrequentItem(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         VALUE_FIELD_NUMBER: builtins.int
         ESTIMATE_FIELD_NUMBER: builtins.int
         value: builtins.str
         estimate: builtins.float
@@ -64,17 +67,19 @@
         *,
         items: collections.abc.Iterable[global___FrequentStringsSummary.FrequentItem] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["items", b"items"]) -> None: ...
 
 global___FrequentStringsSummary = FrequentStringsSummary
 
+@typing_extensions.final
 class FrequentNumbersSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class FrequentDoubleItem(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         ESTIMATE_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         RANK_FIELD_NUMBER: builtins.int
         estimate: builtins.int
@@ -85,14 +90,15 @@
             *,
             estimate: builtins.int = ...,
             value: builtins.float = ...,
             rank: builtins.int = ...,
         ) -> None: ...
         def ClearField(self, field_name: typing_extensions.Literal["estimate", b"estimate", "rank", b"rank", "value", b"value"]) -> None: ...
 
+    @typing_extensions.final
     class FrequentLongItem(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         ESTIMATE_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         RANK_FIELD_NUMBER: builtins.int
         estimate: builtins.int
@@ -119,17 +125,19 @@
         doubles: collections.abc.Iterable[global___FrequentNumbersSummary.FrequentDoubleItem] | None = ...,
         longs: collections.abc.Iterable[global___FrequentNumbersSummary.FrequentLongItem] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["doubles", b"doubles", "longs", b"longs"]) -> None: ...
 
 global___FrequentNumbersSummary = FrequentNumbersSummary
 
+@typing_extensions.final
 class FrequentItemsSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class FrequentItem(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         ESTIMATE_FIELD_NUMBER: builtins.int
         JSON_VALUE_FIELD_NUMBER: builtins.int
         estimate: builtins.int
         json_value: builtins.str
@@ -149,17 +157,19 @@
         *,
         items: collections.abc.Iterable[global___FrequentItemsSummary.FrequentItem] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["items", b"items"]) -> None: ...
 
 global___FrequentItemsSummary = FrequentItemsSummary
 
+@typing_extensions.final
 class CharPosSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class CharPosMapEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -184,14 +194,15 @@
         character_list: builtins.str = ...,
         char_pos_map: collections.abc.Mapping[builtins.str, global___NumberSummary] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["char_pos_map", b"char_pos_map", "character_list", b"character_list"]) -> None: ...
 
 global___CharPosSummary = CharPosSummary
 
+@typing_extensions.final
 class StringsSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     UNIQUE_COUNT_FIELD_NUMBER: builtins.int
     FREQUENT_FIELD_NUMBER: builtins.int
     LENGTH_FIELD_NUMBER: builtins.int
     TOKEN_LENGTH_FIELD_NUMBER: builtins.int
@@ -216,17 +227,19 @@
         char_pos_tracker: global___CharPosSummary | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["char_pos_tracker", b"char_pos_tracker", "frequent", b"frequent", "length", b"length", "token_length", b"token_length", "unique_count", b"unique_count"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["char_pos_tracker", b"char_pos_tracker", "frequent", b"frequent", "length", b"length", "token_length", b"token_length", "unique_count", b"unique_count"]) -> None: ...
 
 global___StringsSummary = StringsSummary
 
+@typing_extensions.final
 class SchemaSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class TypeCountsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         value: builtins.int
@@ -251,14 +264,15 @@
         type_counts: collections.abc.Mapping[builtins.str, builtins.int] | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["inferred_type", b"inferred_type"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["inferred_type", b"inferred_type", "type_counts", b"type_counts"]) -> None: ...
 
 global___SchemaSummary = SchemaSummary
 
+@typing_extensions.final
 class HistogramSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     START_FIELD_NUMBER: builtins.int
     END_FIELD_NUMBER: builtins.int
     WIDTH_FIELD_NUMBER: builtins.int
     COUNTS_FIELD_NUMBER: builtins.int
@@ -288,14 +302,15 @@
         bins: collections.abc.Iterable[builtins.float] | None = ...,
         n: builtins.int = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["bins", b"bins", "counts", b"counts", "end", b"end", "max", b"max", "min", b"min", "n", b"n", "start", b"start", "width", b"width"]) -> None: ...
 
 global___HistogramSummary = HistogramSummary
 
+@typing_extensions.final
 class QuantileSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     QUANTILES_FIELD_NUMBER: builtins.int
     QUANTILE_VALUES_FIELD_NUMBER: builtins.int
     @property
     def quantiles(self) -> google.protobuf.internal.containers.RepeatedScalarFieldContainer[builtins.float]: ...
@@ -307,14 +322,15 @@
         quantiles: collections.abc.Iterable[builtins.float] | None = ...,
         quantile_values: collections.abc.Iterable[builtins.float] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["quantile_values", b"quantile_values", "quantiles", b"quantiles"]) -> None: ...
 
 global___QuantileSummary = QuantileSummary
 
+@typing_extensions.final
 class NumberSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     COUNT_FIELD_NUMBER: builtins.int
     MIN_FIELD_NUMBER: builtins.int
     MAX_FIELD_NUMBER: builtins.int
     MEAN_FIELD_NUMBER: builtins.int
@@ -353,14 +369,15 @@
         is_discrete: builtins.bool = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["frequent_numbers", b"frequent_numbers", "histogram", b"histogram", "quantiles", b"quantiles", "unique_count", b"unique_count"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["count", b"count", "frequent_numbers", b"frequent_numbers", "histogram", b"histogram", "is_discrete", b"is_discrete", "max", b"max", "mean", b"mean", "min", b"min", "quantiles", b"quantiles", "stddev", b"stddev", "unique_count", b"unique_count"]) -> None: ...
 
 global___NumberSummary = NumberSummary
 
+@typing_extensions.final
 class ColumnSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     COUNTERS_FIELD_NUMBER: builtins.int
     SCHEMA_FIELD_NUMBER: builtins.int
     NUMBER_SUMMARY_FIELD_NUMBER: builtins.int
     STRING_SUMMARY_FIELD_NUMBER: builtins.int
@@ -389,17 +406,19 @@
         unique_count: global___UniqueCountSummary | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["counters", b"counters", "frequent_items", b"frequent_items", "number_summary", b"number_summary", "schema", b"schema", "string_summary", b"string_summary", "unique_count", b"unique_count"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["counters", b"counters", "frequent_items", b"frequent_items", "number_summary", b"number_summary", "schema", b"schema", "string_summary", b"string_summary", "unique_count", b"unique_count"]) -> None: ...
 
 global___ColumnSummary = ColumnSummary
 
+@typing_extensions.final
 class DatasetSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class ColumnsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -430,14 +449,15 @@
         model: global___ModelSummary | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["model", b"model", "properties", b"properties"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["columns", b"columns", "model", b"model", "properties", b"properties"]) -> None: ...
 
 global___DatasetSummary = DatasetSummary
 
+@typing_extensions.final
 class ModelSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     METRICS_FIELD_NUMBER: builtins.int
     @property
     def metrics(self) -> global___MetricsSummary: ...
     def __init__(
@@ -446,14 +466,15 @@
         metrics: global___MetricsSummary | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["metrics", b"metrics"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["metrics", b"metrics"]) -> None: ...
 
 global___ModelSummary = ModelSummary
 
+@typing_extensions.final
 class MetricsSummary(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     MODEL_TYPE_FIELD_NUMBER: builtins.int
     ROC_FPR_TPR_FIELD_NUMBER: builtins.int
     RECALL_PREC_FIELD_NUMBER: builtins.int
     CONFUSION_MATRIX_FIELD_NUMBER: builtins.int
@@ -473,14 +494,15 @@
         confusion_matrix: global___ConfusionMatrix | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["confusion_matrix", b"confusion_matrix", "recall_prec", b"recall_prec", "roc_fpr_tpr", b"roc_fpr_tpr"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["confusion_matrix", b"confusion_matrix", "model_type", b"model_type", "recall_prec", b"recall_prec", "roc_fpr_tpr", b"roc_fpr_tpr"]) -> None: ...
 
 global___MetricsSummary = MetricsSummary
 
+@typing_extensions.final
 class ConfusionMatrix(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     LABELS_FIELD_NUMBER: builtins.int
     TARGET_FIELD_FIELD_NUMBER: builtins.int
     PREDICTIONS_FIELD_FIELD_NUMBER: builtins.int
     SCORE_FIELD_FIELD_NUMBER: builtins.int
@@ -502,14 +524,15 @@
         score_field: builtins.str = ...,
         counts: collections.abc.Iterable[google.protobuf.struct_pb2.ListValue] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["counts", b"counts", "labels", b"labels", "predictions_field", b"predictions_field", "score_field", b"score_field", "target_field", b"target_field"]) -> None: ...
 
 global___ConfusionMatrix = ConfusionMatrix
 
+@typing_extensions.final
 class ROCCurve(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     VALUES_FIELD_NUMBER: builtins.int
     @property
     def values(self) -> google.protobuf.internal.containers.RepeatedCompositeFieldContainer[google.protobuf.struct_pb2.ListValue]:
         """e.g.   "values": [ [1, 0.42857],  [1, 0.42857], ... ]"""
@@ -518,14 +541,15 @@
         *,
         values: collections.abc.Iterable[google.protobuf.struct_pb2.ListValue] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["values", b"values"]) -> None: ...
 
 global___ROCCurve = ROCCurve
 
+@typing_extensions.final
 class RecallCurve(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     VALUES_FIELD_NUMBER: builtins.int
     @property
     def values(self) -> google.protobuf.internal.containers.RepeatedCompositeFieldContainer[google.protobuf.struct_pb2.ListValue]:
         """e.g.   "values": [ [1, 1],  [1, 1], ... ]"""
@@ -534,17 +558,19 @@
         *,
         values: collections.abc.Iterable[google.protobuf.struct_pb2.ListValue] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["values", b"values"]) -> None: ...
 
 global___RecallCurve = RecallCurve
 
+@typing_extensions.final
 class DatasetSummaries(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class ProfilesEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/whylogs_messages_pb2.py` & `whylogs-1.2.0/whylogs/core/proto/whylogs_messages_pb2.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/core/proto/whylogs_messages_pb2.pyi` & `whylogs-1.2.0/whylogs/core/proto/whylogs_messages_pb2.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,14 +16,15 @@
 if sys.version_info >= (3, 10):
     import typing as typing_extensions
 else:
     import typing_extensions
 
 DESCRIPTOR: google.protobuf.descriptor.FileDescriptor
 
+@typing_extensions.final
 class DataType(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     class _Type:
         ValueType = typing.NewType("ValueType", builtins.int)
         V: typing_extensions.TypeAlias = ValueType
 
@@ -51,70 +52,75 @@
         *,
         type: global___DataType.Type.ValueType = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["type", b"type"]) -> None: ...
 
 global___DataType = DataType
 
+@typing_extensions.final
 class HllSketchMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     def __init__(
         self,
         *,
         sketch: builtins.bytes = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["sketch", b"sketch"]) -> None: ...
 
 global___HllSketchMessage = HllSketchMessage
 
+@typing_extensions.final
 class FrequentItemsSketchMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     def __init__(
         self,
         *,
         sketch: builtins.bytes = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["sketch", b"sketch"]) -> None: ...
 
 global___FrequentItemsSketchMessage = FrequentItemsSketchMessage
 
+@typing_extensions.final
 class KllSketchMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     def __init__(
         self,
         *,
         sketch: builtins.bytes = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["sketch", b"sketch"]) -> None: ...
 
 global___KllSketchMessage = KllSketchMessage
 
+@typing_extensions.final
 class CpcSketchMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     SKETCH_FIELD_NUMBER: builtins.int
     sketch: builtins.bytes
     def __init__(
         self,
         *,
         sketch: builtins.bytes = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["sketch", b"sketch"]) -> None: ...
 
 global___CpcSketchMessage = CpcSketchMessage
 
+@typing_extensions.final
 class MetricComponentMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     TYPE_ID_FIELD_NUMBER: builtins.int
     N_FIELD_NUMBER: builtins.int
     D_FIELD_NUMBER: builtins.int
     FREQUENT_ITEMS_FIELD_NUMBER: builtins.int
@@ -159,17 +165,19 @@
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["cpc", b"cpc", "d", b"d", "dataclass_param", b"dataclass_param", "frequent_items", b"frequent_items", "hll", b"hll", "kll", b"kll", "msg", b"msg", "n", b"n", "serialized_bytes", b"serialized_bytes", "value", b"value"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["cpc", b"cpc", "d", b"d", "dataclass_param", b"dataclass_param", "frequent_items", b"frequent_items", "hll", b"hll", "kll", b"kll", "msg", b"msg", "n", b"n", "serialized_bytes", b"serialized_bytes", "type_id", b"type_id", "value", b"value"]) -> None: ...
     def WhichOneof(self, oneof_group: typing_extensions.Literal["value", b"value"]) -> typing_extensions.Literal["n", "d", "frequent_items", "hll", "kll", "cpc", "serialized_bytes", "dataclass_param", "msg"] | None: ...
 
 global___MetricComponentMessage = MetricComponentMessage
 
+@typing_extensions.final
 class MetricMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class MetricComponentsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -191,17 +199,19 @@
         *,
         metric_components: collections.abc.Mapping[builtins.str, global___MetricComponentMessage] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["metric_components", b"metric_components"]) -> None: ...
 
 global___MetricMessage = MetricMessage
 
+@typing_extensions.final
 class ColumnMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class MetricComponentsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -223,17 +233,19 @@
         *,
         metric_components: collections.abc.Mapping[builtins.str, global___MetricComponentMessage] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["metric_components", b"metric_components"]) -> None: ...
 
 global___ColumnMessage = ColumnMessage
 
+@typing_extensions.final
 class DatasetProperties(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class TagsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         value: builtins.str
@@ -241,14 +253,15 @@
             self,
             *,
             key: builtins.str = ...,
             value: builtins.str = ...,
         ) -> None: ...
         def ClearField(self, field_name: typing_extensions.Literal["key", b"key", "value", b"value"]) -> None: ...
 
+    @typing_extensions.final
     class MetadataEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         value: builtins.str
@@ -284,14 +297,15 @@
         tags: collections.abc.Mapping[builtins.str, builtins.str] | None = ...,
         metadata: collections.abc.Mapping[builtins.str, builtins.str] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["creation_timestamp", b"creation_timestamp", "dataset_timestamp", b"dataset_timestamp", "metadata", b"metadata", "schema_major_version", b"schema_major_version", "schema_minor_version", b"schema_minor_version", "tags", b"tags"]) -> None: ...
 
 global___DatasetProperties = DatasetProperties
 
+@typing_extensions.final
 class ChunkOffsets(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     OFFSETS_FIELD_NUMBER: builtins.int
     @property
     def offsets(self) -> google.protobuf.internal.containers.RepeatedScalarFieldContainer[builtins.int]: ...
     def __init__(
@@ -299,17 +313,19 @@
         *,
         offsets: collections.abc.Iterable[builtins.int] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["offsets", b"offsets"]) -> None: ...
 
 global___ChunkOffsets = ChunkOffsets
 
+@typing_extensions.final
 class ChunkMessage(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class MetricComponentsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.int
         @property
@@ -331,14 +347,15 @@
         *,
         metric_components: collections.abc.Mapping[builtins.int, global___MetricComponentMessage] | None = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["metric_components", b"metric_components"]) -> None: ...
 
 global___ChunkMessage = ChunkMessage
 
+@typing_extensions.final
 class ChunkHeader(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     class _ChunkType:
         ValueType = typing.NewType("ValueType", builtins.int)
         V: typing_extensions.TypeAlias = ValueType
 
@@ -364,17 +381,19 @@
         tag: builtins.str = ...,
         length: builtins.int = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["length", b"length", "tag", b"tag", "type", b"type"]) -> None: ...
 
 global___ChunkHeader = ChunkHeader
 
+@typing_extensions.final
 class DatasetProfileHeader(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class ColumnOffsetsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.str
         @property
@@ -384,14 +403,15 @@
             *,
             key: builtins.str = ...,
             value: global___ChunkOffsets | None = ...,
         ) -> None: ...
         def HasField(self, field_name: typing_extensions.Literal["value", b"value"]) -> builtins.bool: ...
         def ClearField(self, field_name: typing_extensions.Literal["key", b"key", "value", b"value"]) -> None: ...
 
+    @typing_extensions.final
     class IndexedMetricPathsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.int
         value: builtins.str
@@ -428,14 +448,15 @@
         indexed_metric_paths: collections.abc.Mapping[builtins.int, builtins.str] | None = ...,
     ) -> None: ...
     def HasField(self, field_name: typing_extensions.Literal["properties", b"properties"]) -> builtins.bool: ...
     def ClearField(self, field_name: typing_extensions.Literal["column_offsets", b"column_offsets", "indexed_metric_paths", b"indexed_metric_paths", "length", b"length", "metric_offsets", b"metric_offsets", "properties", b"properties"]) -> None: ...
 
 global___DatasetProfileHeader = DatasetProfileHeader
 
+@typing_extensions.final
 class SegmentTag(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     KEY_FIELD_NUMBER: builtins.int
     VALUE_FIELD_NUMBER: builtins.int
     key: builtins.str
     value: builtins.str
@@ -445,14 +466,15 @@
         key: builtins.str = ...,
         value: builtins.str = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["key", b"key", "value", b"value"]) -> None: ...
 
 global___SegmentTag = SegmentTag
 
+@typing_extensions.final
 class Segment(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     TAGS_FIELD_NUMBER: builtins.int
     PARTITION_ID_FIELD_NUMBER: builtins.int
     @property
     def tags(self) -> google.protobuf.internal.containers.RepeatedCompositeFieldContainer[global___SegmentTag]: ...
@@ -463,14 +485,15 @@
         tags: collections.abc.Iterable[global___SegmentTag] | None = ...,
         partition_id: builtins.str = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["partition_id", b"partition_id", "tags", b"tags"]) -> None: ...
 
 global___Segment = Segment
 
+@typing_extensions.final
 class SegmentationPartition(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
     NAME_FIELD_NUMBER: builtins.int
     ID_FIELD_NUMBER: builtins.int
     name: builtins.str
     id: builtins.str
@@ -480,17 +503,19 @@
         name: builtins.str = ...,
         id: builtins.str = ...,
     ) -> None: ...
     def ClearField(self, field_name: typing_extensions.Literal["id", b"id", "name", b"name"]) -> None: ...
 
 global___SegmentationPartition = SegmentationPartition
 
+@typing_extensions.final
 class DatasetSegmentHeader(google.protobuf.message.Message):
     DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
+    @typing_extensions.final
     class OffsetsEntry(google.protobuf.message.Message):
         DESCRIPTOR: google.protobuf.descriptor.Descriptor
 
         KEY_FIELD_NUMBER: builtins.int
         VALUE_FIELD_NUMBER: builtins.int
         key: builtins.int
         value: builtins.int
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/schema.py` & `whylogs-1.2.0/whylogs/core/schema.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,15 +1,21 @@
 import logging
 from copy import deepcopy
 from dataclasses import dataclass, field
-from typing import Any, Dict, List, Mapping, Optional, TypeVar
+from typing import Any, Dict, List, Mapping, Optional, Tuple, TypeVar
 
+import whylogs.core.resolvers as res
 from whylogs.core.datatypes import StandardTypeMapper, TypeMapper
 from whylogs.core.metrics.metrics import Metric, MetricConfig
-from whylogs.core.resolvers import Resolver, StandardResolver
+from whylogs.core.resolvers import (
+    DeclarativeResolver,
+    MetricSpec,
+    Resolver,
+    ResolverSpec,
+)
 from whylogs.core.segmentation_partition import SegmentationPartition
 from whylogs.core.stubs import pd
 from whylogs.core.validators.validator import Validator
 
 logger = logging.getLogger(__name__)
 
 LARGE_CACHE_SIZE_LIMIT = 1024 * 100
@@ -66,21 +72,21 @@
         types: Optional[Dict[str, Any]] = None,
         default_configs: Optional[MetricConfig] = None,
         type_mapper: Optional[TypeMapper] = None,
         resolvers: Optional[Resolver] = None,
         cache_size: int = 1024,
         schema_based_automerge: bool = False,
         segments: Optional[Dict[str, SegmentationPartition]] = None,
-        validators: Dict[str, List[Validator]] = None,
+        validators: Optional[Dict[str, List[Validator]]] = None,
     ) -> None:
         self._columns = dict()
         self.types = types or dict()
         self.default_configs = default_configs or MetricConfig()
         self.type_mapper = type_mapper or StandardTypeMapper()
-        self.resolvers = resolvers or StandardResolver()
+        self.resolvers = resolvers if resolvers is not None else DeclarativeResolver()
         self.cache_size = cache_size
         self.schema_based_automerge = schema_based_automerge
         self.segments = segments or dict()
         self.validators = validators or dict()
 
         if self.cache_size < 0:
             logger.warning("Negative cache size value. Disabling caching")
@@ -90,16 +96,21 @@
             logger.warning(
                 "Cache size value %s is larger than recommended limit of %s",
                 self.cache_size,
                 LARGE_CACHE_SIZE_LIMIT,
             )
 
         for col, data_type in self.types.items():
+            if isinstance(data_type, tuple):
+                dtype = data_type[0]  # (dtype, property, ...)
+            else:
+                dtype = data_type
+
             self._columns[col] = ColumnSchema(
-                dtype=data_type,
+                dtype=dtype,
                 resolver=self.resolvers,
                 type_mapper=self.type_mapper,
                 cfg=self.default_configs,
                 validators=self.validators,
             )
 
     def copy(self) -> "DatasetSchema":
@@ -109,15 +120,20 @@
         keys = key_dict.keys()
         args = {k: deepcopy(self.__dict__[k]) for k in keys if k not in self.types}
         copy = self.__class__(**args)
         copy._columns = deepcopy(self._columns)
         copy.segments = self.segments.copy()
         return copy
 
-    def resolve(self, *, pandas: Optional[pd.DataFrame] = None, row: Optional[Mapping[str, Any]] = None) -> bool:
+    def resolve(
+        self,
+        *,
+        pandas: Optional[pd.DataFrame] = None,
+        row: Optional[Mapping[str, Any]] = None,
+    ) -> bool:
         if pandas is not None:
             return self._resolve_pdf(pandas)
 
         if row is not None:
             for k, v in row.items():
                 if k in self._columns:
                     continue
@@ -152,14 +168,19 @@
                 validators=self.validators,
                 type_mapper=self.type_mapper,
             )
             dirty = True
 
         return dirty
 
+    def _run_udfs(
+        self, pandas: Optional[pd.DataFrame] = None, row: Optional[Mapping[str, Any]] = None
+    ) -> Tuple[Optional[pd.DataFrame], Optional[Mapping[str, Any]]]:
+        return pandas, row
+
     def get_col_names(self) -> tuple:
         return tuple(self._columns.keys())
 
     def get(self, name: str) -> Optional["ColumnSchema"]:
         return self._columns.get(name)
 
 
@@ -170,19 +191,73 @@
 
     The main goal is to specify the data type.
     On top of that, users can configure their own tracker resolution logic (mapping a type to a list of tracker
     factories) and any additional trackers here.
     """
 
     dtype: Any
-    cfg: MetricConfig = MetricConfig()
-    type_mapper: TypeMapper = StandardTypeMapper()
-    resolver: Resolver = StandardResolver()
+    cfg: MetricConfig = field(default_factory=MetricConfig)
+    type_mapper: TypeMapper = field(default_factory=StandardTypeMapper)
+    resolver: Resolver = field(default_factory=DeclarativeResolver)
     validators: Dict[str, List[Validator]] = field(default_factory=dict)
 
     def get_metrics(self, name: str) -> Dict[str, Metric]:
         return self.resolver.resolve(name=name, why_type=self.type_mapper(self.dtype), column_schema=self)
 
     def get_validators(self, name: str) -> List[Optional[Validator]]:
         if self.validators:
             return self.validators.get(name, [])
         return []
+
+
+class DeclarativeSchema(DatasetSchema):
+    """
+    The DeclarativeSchema allows one to customize the set of metrics
+    tracked for each column in a data set. Pass its constructor a list
+    of ResolverSpecs, which specify the column name or data type to
+    match and the list of MetricSpecs to instantiate for matching columns.
+    Each MetricSpec specifies the Metric class and MetricConfig to
+    instantiate. Omit the MetricSpec::config to use the default MetricConfig.
+
+    For example, DeclarativeSchema(resolvers=STANDARD_RESOLVER) implements
+    the same schema as DatasetSchema(), i.e., using the default MetricConfig,
+    StandardTypeMapper, StandardResolver, etc.  STANDARD_RESOLVER is defined
+    in whylogs/python/whylogs/core/resolvers.py
+    """
+
+    def add_resolver(self, resolver_spec: ResolverSpec):
+        self.resolvers.add_resolver(resolver_spec)
+
+    def add_resolver_spec(
+        self,
+        column_name: Optional[str] = None,
+        column_type: Optional[Any] = None,
+        metrics: Optional[List[MetricSpec]] = None,
+    ):
+        spec = ResolverSpec(column_name=column_name, column_type=column_type, metrics=metrics or [])
+        self.add_resolver(spec)
+
+    def __init__(
+        self,
+        resolvers: List[ResolverSpec],
+        types: Optional[Dict[str, Any]] = None,
+        default_config: Optional[MetricConfig] = None,
+        type_mapper: Optional[TypeMapper] = None,
+        cache_size: int = 1024,
+        schema_based_automerge: bool = False,
+        segments: Optional[Dict[str, SegmentationPartition]] = None,
+        validators: Optional[Dict[str, List[Validator]]] = None,
+    ) -> None:
+        if not resolvers:
+            resolvers = res.DEFAULT_RESOLVERS
+            logger.warning("No columns specified in DeclarativeSchema")
+        resolver = DeclarativeResolver(resolvers, default_config)
+        super().__init__(
+            types=types,
+            default_configs=default_config,
+            type_mapper=type_mapper,
+            resolvers=resolver,
+            cache_size=cache_size,
+            schema_based_automerge=schema_based_automerge,
+            segments=segments,
+            validators=validators,
+        )
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/segmentation_partition.py` & `whylogs-1.2.0/whylogs/core/segmentation_partition.py`

 * *Files 4% similar despite different names*

```diff
@@ -55,10 +55,18 @@
         if self.filter:
             if self.filter.filter_function:
                 return inspect.getsource(self.filter.filter_function)
             if self.filter.query_string:
                 return self.filter.query_string
         return ""
 
+    def __eq__(self, other) -> bool:
+        if isinstance(other, SegmentationPartition):
+            return self.id == other.id
+        return False
+
+    def __hash__(self):
+        return hash(self.id)
+
 
 def segment_on_column(column_name: str) -> Mapping[str, SegmentationPartition]:
     return {column_name: SegmentationPartition(name=column_name, mapper=ColumnMapperFunction(col_names=[column_name]))}
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/stubs.py` & `whylogs-1.2.0/whylogs/core/stubs.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 import logging
 from dataclasses import dataclass
+from typing import Any
 
 logger = logging.getLogger(__name__)
 
 try:
     import pandas as _pd
 except ImportError:  # noqa
     _pd = None  # type: ignore
@@ -11,38 +12,93 @@
 try:
     import numpy as _np
 except ImportError:  # noqa
     _np = None  # type: ignore
     if _pd is not None:
         logger.error("Pandas is installed but numpy is not. Your environment is probably broken.")
 
+try:
+    import scipy as _sp
+except ImportError:  # noqa
+    _sp = None  # type: ignore
+
+try:
+    import sklearn.cluster as _sklc
+    import sklearn.decomposition as _skld
+    import sklearn.metrics.pairwise as _sklp
+except ImportError:  # noqa
+    _sklp = None  # type: ignore
+    _sklc = None  # type: ignore
+    _skld = None  # type: ignore
+
 
 class _StubClass:
     pass
 
 
 @dataclass(frozen=True)
 class NumpyStub:
     dtype: type = _StubClass
     number: type = _StubClass
+    bool_: type = _StubClass
     floating: type = _StubClass
     ndarray: type = _StubClass
     timedelta64: type = _StubClass
     datetime64: type = _StubClass
     unicode_: type = _StubClass
     issubdtype: type = _StubClass
 
 
 @dataclass(frozen=True)
 class PandasStub(object):
     Series: type = _StubClass
     DataFrame: type = _StubClass
 
 
+@dataclass(frozen=True)
+class ScipyStub:
+    sparse: type = _StubClass
+
+
+@dataclass(frozen=True)
+class ScikitLearnStub:
+    cosine_distances: type = _StubClass
+    euclidean_distances: type = _StubClass
+    KMeans: type = _StubClass
+    PCA: type = _StubClass
+
+
+def is_not_stub(stubbed_class: Any) -> bool:
+    if (
+        stubbed_class
+        and stubbed_class is not _StubClass
+        and not isinstance(stubbed_class, (PandasStub, NumpyStub, ScipyStub, ScikitLearnStub))
+    ):
+        return True
+    return False
+
+
 if _np is None:
     _np = NumpyStub()
 
 if _pd is None:
     _pd = PandasStub()
 
+if _sp is None:
+    _sp = ScipyStub()
+
+if _sklp is None:
+    _sklp = ScikitLearnStub()
+
+if _sklc is None:
+    _sklc = ScikitLearnStub()
+
+if _skld is None:
+    _skld = ScikitLearnStub()
+
+
 np = _np
 pd = _pd
+sp = _sp
+sklp = _sklp
+sklc = _sklc
+skld = _skld
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/view/column_profile_view.py` & `whylogs-1.2.0/whylogs/core/view/column_profile_view.py`

 * *Files 5% similar despite different names*

```diff
@@ -64,27 +64,31 @@
     def get_metric(self, m_name: str) -> Optional[METRIC]:
         return self._metrics.get(m_name)
 
     def to_protobuf(self) -> ColumnMessage:
         res: Dict[str, MetricComponentMessage] = {}
         for m_name, m in self._metrics.items():
             for mc_name, mc in m.to_protobuf().metric_components.items():
-                res[f"{m.namespace}/{mc_name}"] = mc
+                if not m.exclude_from_serialization:
+                    res[f"{m.namespace}/{mc_name}"] = mc
         return ColumnMessage(metric_components=res)
 
     def get_metric_component_paths(self) -> List[str]:
         res: List[str] = []
         for m_name, m in self._metrics.items():
             for mc_name in m.get_component_paths():
                 res.append(f"{m.namespace}/{mc_name}")
         return res
 
     def get_metric_names(self) -> List[str]:
         return [name for name in self._metrics]
 
+    def get_metrics(self) -> List[Metric]:
+        return list(self._metrics.values())
+
     def to_summary_dict(
         self, *, column_metric: Optional[str] = None, cfg: Optional[SummaryConfig] = None
     ) -> Dict[str, Any]:
         cfg = cfg or SummaryConfig()
         res = {}
         for metric_name, metric in self._metrics.items():
             if column_metric is not None and metric_name != column_metric:
@@ -103,42 +107,49 @@
 
     @classmethod
     def zero(cls, msg: ColumnMessage) -> "ColumnProfileView":
         return ColumnProfileView(metrics={})
 
     @classmethod
     def from_protobuf(cls, msg: ColumnMessage) -> "ColumnProfileView":
+        # importing to trigger registration of non-standard metrics
+        import whylogs.experimental.core.metrics.udf_metric  # noqa
+        import whylogs.experimental.extras.embedding_metric  # noqa
+        import whylogs.experimental.extras.nlp_metric  # noqa
+        import whylogs.extras.image_metric  # noqa
+
         result_metrics: Dict[str, Metric] = {}
         metric_messages: Dict[str, Dict[str, MetricComponentMessage]] = {}
         for full_path, c_msg in msg.metric_components.items():
             metric_name = full_path.split("/")[0]
             metric_components = metric_messages.get(metric_name)
 
             if metric_components is None:
                 metric_components = {}
             metric_messages[metric_name] = metric_components
 
             c_key = full_path[len(metric_name) + 1 :]
             metric_components[c_key] = c_msg
-
         for m_name, metric_components in metric_messages.items():
             m_enum = StandardMetric.__members__.get(m_name)
             if m_enum is None:
                 if m_name in _METRIC_DESERIALIZER_REGISTRY:
                     metric_class = _METRIC_DESERIALIZER_REGISTRY[m_name]
                 else:
                     raise UnsupportedError(f"Unsupported metric: {m_name}")
             else:
                 metric_class = m_enum.value
 
             m_msg = MetricMessage(metric_components=metric_components)
             try:
-                result_metrics[m_name] = metric_class.from_protobuf(m_msg)
-            except:  # noqa
-                raise DeserializationError(f"Failed to deserialize metric: {m_name}")
+                deserialized_metric = metric_class.from_protobuf(m_msg)
+                result_metrics[m_name] = deserialized_metric
+            except Exception as error:  # noqa
+                raise DeserializationError(f"Failed to deserialize metric: {m_name}:{error}")
+
         return ColumnProfileView(metrics=result_metrics)
 
     @classmethod
     def from_bytes(cls, data: bytes) -> "ColumnProfileView":
         msg = ColumnMessage()
         if isinstance(data, bytearray):
             data = bytes(data)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/core/view/segmented_dataset_profile_view.py` & `whylogs-1.2.0/whylogs/core/view/segmented_dataset_profile_view.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 import tempfile
+from datetime import datetime
 from logging import getLogger
-from typing import Any, Dict, Optional, Tuple
+from typing import IO, Any, Dict, Optional, Tuple
 
 from whylogs.api.writer.writer import Writable
 from whylogs.core.proto import (
     ChunkHeader,
     ChunkMessage,
     ChunkOffsets,
     DatasetProfileHeader,
@@ -56,47 +57,80 @@
         return self._partition
 
     @property
     def profile_view(self) -> DatasetProfileView:
         return self._profile_view
 
     @property
-    def dataset_timestamp(self):
+    def dataset_timestamp(self) -> Optional[datetime]:
         return self.profile_view.dataset_timestamp
 
     @property
-    def creation_timestamp(self):
+    def creation_timestamp(self) -> Optional[datetime]:
         return self.profile_view.creation_timestamp
 
     def get_default_path(self) -> str:
-        return f"profile_{self._profile_view.creation_timestamp}_{self._segment.parent_id}_{'_'.join(self._segment.key)}.bin"
+        return f"profile_{self._profile_view.creation_timestamp}_{self.get_segment_string()}.bin"
+
+    def get_segment_string(self) -> str:
+        return f"{self._segment.parent_id}_{'_'.join(self._segment.key)}"
 
     def _write_as_v0_message(self, path: Optional[str] = None, **kwargs: Any) -> Tuple[bool, str]:
         message_v0 = v1_to_dataset_profile_message_v0(self.profile_view, self.segment, self.partition)
-        path = path or self.get_default_path()
-        with open(path, "w+b") as out_f:
-            write_delimited_protobuf(out_f, message_v0)
+        file_to_write = kwargs.get("file")
+        path = file_to_write.name if file_to_write else path or self.get_default_path()
+        if file_to_write:
+            write_delimited_protobuf(file_to_write, message_v0)
+        else:
+            with open(path, "w+b") as out_f:
+                write_delimited_protobuf(out_f, message_v0)
         return True, path
 
+    def _copy_write(
+        self,
+        source_profile_file: IO[bytes],
+        output_file: IO[bytes],
+        total_len: int,
+        dataset_segment_header: DatasetSegmentHeader,
+        dataset_header: DatasetProfileHeader,
+    ):
+        output_file.write(WHYLOGS_MAGIC_HEADER_BYTES)
+        write_delimited_protobuf(output_file, dataset_segment_header)
+        logger.debug(
+            f"Writing segmented profile file: whylogs file and segment headers wrote {output_file.tell()} bytes"
+        )
+        write_delimited_protobuf(output_file, dataset_header)
+        logger.debug(
+            f"Writing segmented profile file: and with dataset header wrote a total of {output_file.tell()} bytes before writing the chunks."
+        )
+
+        source_profile_file.seek(0)
+        while source_profile_file.tell() < total_len:
+            buffer = source_profile_file.read(_BUFFER_CHUNK)
+            output_file.write(buffer)
+        logger.debug(f"Writing segmented profile file: complete! total of {output_file.tell()} bytes written.")
+
     def _write_v1(self, path: Optional[str] = None, **kwargs: Any) -> Tuple[bool, str]:
         all_metric_component_names = set()
-        path = path or self.get_default_path()
+        file_to_write = kwargs.get("file")
+        path = file_to_write.name if file_to_write else path or self.get_default_path()
 
         # capture the list of all metric component paths
         for col in self.profile_view._columns.values():
             all_metric_component_names.update(col.get_metric_component_paths())
         metric_name_list = list(all_metric_component_names)
         metric_name_list.sort()
         metric_name_indices: Dict[str, int] = {}
         metric_index_to_name: Dict[int, str] = {}
         for i in range(0, len(metric_name_list)):
             metric_name_indices[metric_name_list[i]] = i
             metric_index_to_name[i] = metric_name_list[i]
 
         column_chunk_offsets: Dict[str, ChunkOffsets] = {}
+
         with tempfile.TemporaryFile("w+b") as f:
             for col_name in sorted(self.profile_view._columns.keys()):
                 column_chunk_offsets[col_name] = ChunkOffsets(offsets=[f.tell()])
 
                 col = self.profile_view._columns[col_name]
 
                 # for a given column, turn it into a ChunkMessage.
@@ -133,15 +167,15 @@
             properties = DatasetProperties(
                 dataset_timestamp=to_utc_milliseconds(self.profile_view._dataset_timestamp),
                 creation_timestamp=to_utc_milliseconds(self.profile_view._creation_timestamp),
                 metadata=segment_metadata,
                 tags=segment_message_tags,
             )
 
-            logger.warn(f"constructed DatasetProperties for segmented profile file: {properties}")
+            logger.info(f"Constructed DatasetProperties for segmented profile file: {properties}")
 
             dataset_header = DatasetProfileHeader(
                 column_offsets=column_chunk_offsets,
                 properties=properties,
                 length=total_len,
                 indexed_metric_paths=metric_index_to_name,
             )
@@ -161,30 +195,19 @@
             write_delimited_protobuf(f, dataset_segment_header)
             first_segment_offset = f.tell() - total_len
             dataset_segment_header.offsets[0] = first_segment_offset
 
             # only single segment files at first.
             dataset_segment_header.segments.extend(segments_message_field)
 
-            with open(path, "w+b") as out_f:
-                out_f.write(WHYLOGS_MAGIC_HEADER_BYTES)
-                write_delimited_protobuf(out_f, dataset_segment_header)
-                logger.debug(
-                    f"Writing segmented profile file: whylogs file and segment headers wrote {out_f.tell()} bytes"
-                )
-                write_delimited_protobuf(out_f, dataset_header)
-                logger.debug(
-                    f"Writing segmented profile file: and with dataset header wrote a total of {out_f.tell()} bytes before writing the chunks."
-                )
-
-                f.seek(0)
-                while f.tell() < total_len:
-                    buffer = f.read(_BUFFER_CHUNK)
-                    out_f.write(buffer)
-                logger.debug(f"Writing segmented profile file: complete! total of {out_f.tell()} bytes written.")
+            if file_to_write:
+                self._copy_write(f, file_to_write, total_len, dataset_segment_header, dataset_header)
+            else:
+                with open(path, "w+b") as out_f:
+                    self._copy_write(f, out_f, total_len, dataset_segment_header, dataset_header)
         return True, path
 
     def write(self, path: Optional[str] = None, **kwargs: Any) -> Tuple[bool, str]:
         if kwargs.get("use_v0"):
             return self._write_as_v0_message(path, **kwargs)
         else:
             return self._write_v1(path, **kwargs)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/datasets/base.py` & `whylogs-1.2.0/whylogs/datasets/base.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/datasets/configs.py` & `whylogs-1.2.0/whylogs/datasets/configs.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,24 +1,25 @@
 from dataclasses import dataclass, field
 from datetime import datetime, timezone
-from typing import Dict, List
+from typing import Dict, List, Optional
 
 
 @dataclass
 class BaseConfig:
     data_folder: str = "whylogs_data"
     description_folder: str = "whylogs.datasets.descr"
 
 
 @dataclass
 class DatasetConfig:
     folder_name: str
     url: str
     baseline_start_timestamp: Dict[str, datetime]
-    inference_start_timestamp: Dict[str, datetime]
+    inference_start_timestamp: Optional[Dict[str, datetime]]
+    production_start_timestamp: Optional[Dict[str, datetime]]
     max_interval: int
     base_unit: str
     available_versions: tuple
     target_columns: dict
     prediction_columns: dict
     miscellaneous_columns: dict
     ignore_columns: dict
@@ -37,14 +38,19 @@
         }
     )
     inference_start_timestamp: Dict[str, datetime] = field(
         default_factory=lambda: {
             "base": datetime(year=2022, month=8, day=19, tzinfo=timezone.utc),
         }
     )
+    production_start_timestamp: Dict[str, datetime] = field(
+        default_factory=lambda: {
+            "base": datetime(year=2022, month=8, day=19, tzinfo=timezone.utc),
+        }
+    )
     max_interval: int = 21
     base_unit: str = "D"
     target_columns: Dict[str, List[str]] = field(default_factory=lambda: {"base": ["output_discount"]})
     prediction_columns: Dict[str, List[str]] = field(
         default_factory=lambda: {
             "base": ["output_prediction", "output_score"],
         }
@@ -70,14 +76,55 @@
         default_factory=lambda: {
             "base": ["date"],
         }
     )
 
 
 @dataclass
+class EmployeeConfig(DatasetConfig):
+    folder_name: str = "employee"
+    description_file: str = "employee.rst"
+    available_versions: tuple = ("base",)
+    url: str = "https://whylabs-public.s3.us-west-2.amazonaws.com/whylogs_examples/Employee"
+    baseline_start_timestamp: Dict[str, datetime] = field(
+        default_factory=lambda: {
+            "base": datetime(year=2023, month=1, day=16, tzinfo=timezone.utc),
+        }
+    )
+    inference_start_timestamp: Dict[str, datetime] = field(
+        default_factory=lambda: {
+            "base": datetime(year=2023, month=1, day=17, tzinfo=timezone.utc),
+        }
+    )
+    production_start_timestamp: Dict[str, datetime] = field(
+        default_factory=lambda: {
+            "base": datetime(year=2023, month=1, day=17, tzinfo=timezone.utc),
+        }
+    )
+    max_interval: int = 31
+    base_unit: str = "D"
+    target_columns: Dict[str, List[str]] = field(default_factory=lambda: {"base": []})
+    prediction_columns: Dict[str, List[str]] = field(
+        default_factory=lambda: {
+            "base": [],
+        }
+    )
+    miscellaneous_columns: Dict[str, List[str]] = field(
+        default_factory=lambda: {
+            "base": ["assignment_category"],
+        }
+    )
+    ignore_columns: Dict[str, List[str]] = field(
+        default_factory=lambda: {
+            "base": ["date"],
+        }
+    )
+
+
+@dataclass
 class WeatherConfig(DatasetConfig):
     folder_name: str = "weather_forecast"
     description_file: str = "weather.rst"
     url: str = "https://whylabs-public.s3.us-west-2.amazonaws.com/whylogs_examples/WeatherForecast"
     baseline_start_timestamp: Dict[str, datetime] = field(
         default_factory=lambda: {
             "in_domain": datetime(year=2018, month=9, day=1, tzinfo=timezone.utc),
@@ -86,15 +133,21 @@
     )
     inference_start_timestamp: Dict[str, datetime] = field(
         default_factory=lambda: {
             "in_domain": datetime(year=2019, month=2, day=1, tzinfo=timezone.utc),
             "out_domain": datetime(year=2019, month=5, day=14, tzinfo=timezone.utc),
         }
     )
-
+    production_start_timestamp: Dict[str, datetime] = field(
+        default_factory=lambda: {
+            "in_domain": datetime(year=2019, month=2, day=1, tzinfo=timezone.utc),
+            "out_domain": datetime(year=2019, month=5, day=14, tzinfo=timezone.utc),
+        }
+    )
+    production_start_timestamp = None
     max_interval: int = 30
     base_unit: str = "D"
     available_versions: tuple = ("in_domain", "out_domain")
     target_columns: Dict[str, List[str]] = field(
         default_factory=lambda: {"in_domain": ["temperature"], "out_domain": ["temperature"]}
     )
     prediction_columns: Dict[str, List[str]] = field(
```

### Comparing `whylogs-1.1.9.dev0/whylogs/datasets/descr/ecommerce.rst` & `whylogs-1.2.0/whylogs/datasets/descr/ecommerce.rst`

 * *Files 0% similar despite different names*

```diff
@@ -24,16 +24,14 @@
 
 Currently the dataset contains one version: **base**. The task for the base version is to classify wether an incoming product should be provided a discount, given product features such as history of items sold, user rating, category and market price.
 The **base** version contains two partitions: **Baseline** and **Inference**
 
 base
 ~~~~
 
-This version contains 5
-
 * Baseline
    * Number of instances: 34743
    * Number of features: 19
       * Input Features: 5
       * Target Features: 1
       * Prediction Features: 2
       * Extra Features: 11
```

### Comparing `whylogs-1.1.9.dev0/whylogs/datasets/descr/weather.rst` & `whylogs-1.2.0/whylogs/datasets/descr/weather.rst`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/datasets/ecommerce.py` & `whylogs-1.2.0/whylogs/datasets/ecommerce.py`

 * *Files 2% similar despite different names*

```diff
@@ -35,27 +35,33 @@
     baseline_timestamp: Union[date, datetime] = datetime.now(timezone.utc).replace(
         hour=0, minute=0, second=0, microsecond=0
     )
     inference_start_timestamp: Union[date, datetime] = datetime.now(timezone.utc).replace(
         hour=0, minute=0, second=0, microsecond=0
     ) + timedelta(days=1)
     original: bool = False
-    dataset_config: DatasetConfig = EcommerceConfig()
+    dataset_config: Optional[DatasetConfig] = None
+
+    @classmethod
+    def config(cls) -> DatasetConfig:
+        return EcommerceConfig()
 
     def __init__(self, version: str = "base") -> None:
         """Initializes internal dataframes.
 
         If the files are already present locally, won't try to download from S3.
 
         Parameters
         ----------
         version : str, optional
-            The desired dataset's version, by default "in_domain"
+            The desired dataset's version, by default "base"
 
         """
+        if not self.dataset_config:
+            self.dataset_config = Ecommerce.config()
         if version not in self.dataset_config.available_versions:
             raise ValueError("Version not found in list of available versions.")
         self.version = version
 
         baseline_file = os.path.join(
             _get_dataset_path(self.dataset_config.folder_name), "baseline_dataset_{}.csv".format(self.version)
         )
@@ -74,20 +80,20 @@
             self.inference_df.to_csv(inference_file, index=False)
 
         self.baseline_df = _adjust_df_date(self.baseline_df, new_start_date=self.baseline_timestamp)
         self.inference_df = _adjust_df_date(self.inference_df, new_start_date=self.inference_start_timestamp)
 
     @classmethod
     def describe_versions(cls) -> Tuple[str]:
-        available_versions = cls.dataset_config.available_versions
+        available_versions = cls.config().available_versions
         return available_versions
 
     @classmethod
     def describe(cls) -> Optional[str]:
-        descr = resources.read_text(base_config.description_folder, cls.dataset_config.description_file)
+        descr = resources.read_text(base_config.description_folder, cls.config().description_file)
         return descr
 
     def get_baseline(self) -> Batch:
         data = self.baseline_df
         baseline = Batch(
             timestamp=self.baseline_timestamp, data=data, dataset_config=self.dataset_config, version=self.version
         )
@@ -99,18 +105,21 @@
             timestamp = timestamp.astimezone(tz=timezone.utc)
         timestamp = timestamp.replace(hour=0, minute=0, second=0, microsecond=0)
         return timestamp
 
     def _validate_interval(self, interval: str) -> Tuple[int, str]:
         """Checks if desired interval are of acceptable units and inside maximum duration limits."""
         number_days, unit = _parse_interval(interval)
-        if number_days > self.dataset_config.max_interval:
-            raise ValueError("Maximum allowed interval for this dataset is {}".format(self.dataset_config.max_interval))
+        if self.dataset_config is None:
+            raise ValueError("default_config is unset for this dataset")
+        config: EcommerceConfig = self.dataset_config
+        if number_days > config.max_interval:
+            raise ValueError("Maximum allowed interval for this dataset is {}".format(config.max_interval))
         if unit != "D":
-            raise ValueError("Current accepted unit for this dataset is {}".format(self.dataset_config.base_unit))
+            raise ValueError("Current accepted unit for this dataset is {}".format(config.base_unit))
         return (number_days, unit)
 
     def get_inference_data(
         self, target_date: Optional[Union[date, datetime]] = None, number_batches: Optional[int] = None
     ) -> Union[Batch, Iterable[Batch]]:
         """Get batch(es) from inference dataset.
 
@@ -168,16 +177,18 @@
         original : Optional[bool], optional
             _If true, sets both baseline and inference timestamps to the dataset's original timestamp, by default None
         """
         if inference_interval:
             self.inference_interval = inference_interval
             self.number_days, self.unit = self._validate_interval(self.inference_interval)
         if original:
-            self.baseline_timestamp = self.dataset_config.baseline_start_timestamp[self.version]
-            self.inference_start_timestamp = self.dataset_config.inference_start_timestamp[self.version]
+            assert self.dataset_config is not None
+            config = self.dataset_config
+            self.baseline_timestamp = config.baseline_start_timestamp[self.version]
+            self.inference_start_timestamp = config.inference_start_timestamp[self.version]
             self.inference_df = _adjust_df_date(self.inference_df, self.inference_start_timestamp)
             self.baseline_df = _adjust_df_date(self.baseline_df, new_start_date=self.baseline_timestamp)
 
         if baseline_timestamp:
             if not original:
                 _baseline_date: datetime = _validate_timestamp(baseline_timestamp)
                 _baseline_date = self._truncate_and_check_timezone(_baseline_date)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/datasets/utils.py` & `whylogs-1.2.0/whylogs/datasets/utils.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/datasets/weather.py` & `whylogs-1.2.0/whylogs/datasets/weather.py`

 * *Files 3% similar despite different names*

```diff
@@ -46,27 +46,33 @@
     baseline_timestamp: Union[date, datetime] = datetime.now(timezone.utc).replace(
         hour=0, minute=0, second=0, microsecond=0
     )
     inference_start_timestamp: Union[date, datetime] = datetime.now(timezone.utc).replace(
         hour=0, minute=0, second=0, microsecond=0
     ) + timedelta(days=1)
     original: bool = False
-    dataset_config: DatasetConfig = WeatherConfig()
+    dataset_config: Optional[DatasetConfig] = None
+
+    @classmethod
+    def config(cls) -> DatasetConfig:
+        return WeatherConfig()
 
     def __init__(self, version: str = "in_domain") -> None:
         """Initializes internal dataframes.
 
         If the files are already present locally, won't try to download from S3.
 
         Parameters
         ----------
         version : str, optional
             The desired dataset's version, by default "in_domain"
 
         """
+        if not self.dataset_config:
+            self.dataset_config = WeatherConfig()
         if version not in self.dataset_config.available_versions:
             raise ValueError("Version not found in list of available versions.")
         self.version = version
 
         baseline_file = os.path.join(
             _get_dataset_path(self.dataset_config.folder_name), "baseline_dataset_{}.csv".format(self.version)
         )
@@ -100,18 +106,21 @@
             timestamp = timestamp.astimezone(tz=timezone.utc)
         timestamp = timestamp.replace(hour=0, minute=0, second=0, microsecond=0)
         return timestamp
 
     def _validate_interval(self, interval: str) -> Tuple[int, str]:
         """Checks if desired interval are of acceptable units and inside maximum duration limits."""
         number_days, unit = _parse_interval(interval)
-        if number_days > self.dataset_config.max_interval:
-            raise ValueError("Maximum allowed interval for this dataset is {}".format(self.dataset_config.max_interval))
+        if self.dataset_config is None:
+            raise ValueError("default_config is unset for this dataset")
+        config: WeatherConfig = self.dataset_config
+        if number_days > config.max_interval:
+            raise ValueError("Maximum allowed interval for this dataset is {}".format(config.max_interval))
         if unit != "D":
-            raise ValueError("Current accepted unit for this dataset is {}".format(self.dataset_config.base_unit))
+            raise ValueError("Current accepted unit for this dataset is {}".format(config.base_unit))
         return (number_days, unit)
 
     def get_inference_data(
         self, target_date: Optional[Union[date, datetime]] = None, number_batches: Optional[int] = None
     ) -> Union[Batch, Iterable[Batch]]:
         """Get batch(es) from inference dataset.
 
@@ -169,16 +178,18 @@
         original : Optional[bool], optional
             _If true, sets both baseline and inference timestamps to the dataset's original timestamp, by default None
         """
         if inference_interval:
             self.inference_interval = inference_interval
             self.number_days, self.unit = self._validate_interval(self.inference_interval)
         if original:
-            self.baseline_timestamp = self.dataset_config.baseline_start_timestamp[self.version]
-            self.inference_start_timestamp = self.dataset_config.inference_start_timestamp[self.version]
+            assert self.dataset_config is not None
+            config = self.dataset_config
+            self.baseline_timestamp = config.baseline_start_timestamp[self.version]
+            self.inference_start_timestamp = config.inference_start_timestamp[self.version]
             self.inference_df = _adjust_df_date(self.inference_df, self.inference_start_timestamp)
             self.baseline_df = _adjust_df_date(self.baseline_df, new_start_date=self.baseline_timestamp)
 
         if baseline_timestamp:
             if not original:
                 _baseline_date: datetime = _validate_timestamp(baseline_timestamp)
                 _baseline_date = self._truncate_and_check_timezone(_baseline_date)
@@ -198,20 +209,20 @@
             else:
                 logger.warning(
                     "baseline_timestamp and inference_start_timestamp overriden by original timestamps due to original = True"
                 )
 
     @classmethod
     def describe_versions(cls) -> Tuple[str]:
-        available_versions = cls.dataset_config.available_versions
+        available_versions = cls.config().available_versions
         return available_versions
 
     @classmethod
     def describe(cls) -> Optional[str]:
-        descr = resources.read_text(base_config.description_folder, cls.dataset_config.description_file)
+        descr = resources.read_text(base_config.description_folder, cls.config().description_file)
         return descr
 
 
 class WeatherDatasetIterator:
     """Iterator to retrieve inference batches, when multiple batches are required."""
 
     def __init__(
```

### Comparing `whylogs-1.1.9.dev0/whylogs/extras/image_metric.py` & `whylogs-1.2.0/whylogs/extras/image_metric.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,9 +1,8 @@
 import logging
-from abc import ABC, abstractmethod
 from copy import deepcopy
 from dataclasses import dataclass, field
 from itertools import chain
 from typing import Any, Dict, List, Optional, Set, Union
 
 import whylogs as why
 from whylogs.api.logger.result_set import ResultSet
@@ -12,29 +11,34 @@
     Fractional,
     Integral,
     StandardTypeMapper,
     String,
     TypeMapper,
 )
 from whylogs.core.metrics import StandardMetric
-from whylogs.core.metrics.metrics import Metric, MetricConfig, OperationResult
-from whylogs.core.metrics.multimetric import MultiMetric
+from whylogs.core.metrics.metrics import (
+    Metric,
+    MetricConfig,
+    OperationResult,
+    register_metric,
+)
+from whylogs.core.metrics.multimetric import MultiMetric, SubmetricSchema
 from whylogs.core.preprocessing import PreprocessedColumn
 from whylogs.core.resolvers import Resolver
 from whylogs.core.schema import ColumnSchema, DatasetSchema
 
 logger = logging.getLogger(__name__)
 
 try:
     from PIL.Image import Image as ImageType
     from PIL.ImageStat import Stat
     from PIL.TiffImagePlugin import IFDRational
     from PIL.TiffTags import TAGS
 except ImportError as e:
-    ImageType = None
+    ImageType = None  # type: ignore
     logger.warning(str(e))
     logger.warning("Unable to load PIL; install Pillow for image support")
 
 DEFAULT_IMAGE_FEATURES: List[str] = []
 
 
 _DEFAULT_TAGS_ATTRIBUTES = [
@@ -59,14 +63,16 @@
 
     Returns:
         Dict: of metadata
     """
 
     stats = Stat(img.convert("HSV"))
     metadata = {}
+    if hasattr(img, "entropy"):
+        metadata["entropy"] = img.entropy()
     for index in range(len(channels)):
         for statistic_name in image_stats:
             if hasattr(stats, statistic_name):
                 metadata[channels[index] + "." + statistic_name] = getattr(stats, statistic_name)[index]
 
     return metadata
 
@@ -114,20 +120,14 @@
     """
     metadata = {}
     metadata.update(image_based_metadata(img))
     metadata.update(get_pil_image_statistics(img))
     return metadata
 
 
-class SubmetricSchema(ABC):
-    @abstractmethod
-    def resolve(self, name: str, why_type: DataType, fi_disabled: bool = False) -> Dict[str, Metric]:
-        raise NotImplementedError
-
-
 class ImageSubmetricSchema(SubmetricSchema):
     def resolve(self, name: str, why_type: DataType, fi_disabled: bool = False) -> Dict[str, Metric]:
         metrics: Dict[str, Metric] = {
             "counts": StandardMetric.counts.zero(MetricConfig()),
             "types": StandardMetric.types.zero(MetricConfig()),
             "cardinality": StandardMetric.cardinality.zero(MetricConfig()),
         }
@@ -211,15 +211,15 @@
     def columnar_update(self, view: PreprocessedColumn) -> OperationResult:
         count = 0
         for image in list(chain.from_iterable(view.raw_iterator())):
             if isinstance(image, ImageType):
                 metadata = get_pil_exif_metadata(image)
                 for name, value in metadata.items():
                     self._discover_exif_submetrics(name, value)  # EXIF tag discovery
-                    data = PreprocessedColumn.apply([metadata[name]])
+                    data = PreprocessedColumn.apply([metadata[name]])  # TODO: _process_scalar_value()?
                     self._update_relevant_submetrics(name, data)
 
                 image_data = get_pil_image_metadata(image)
                 for name, value in image_data.items():
                     self._discover_image_submetrics(name, value)
                     data = PreprocessedColumn.apply([image_data[name]])
                     self._update_relevant_submetrics(name, data)
@@ -272,7 +272,11 @@
     schema = schema or DatasetSchema(
         types={key: ImageType for key in images.keys()}, default_configs=ImageMetricConfig(), resolvers=ImageResolver()
     )
     if not isinstance(schema.default_configs, ImageMetricConfig):
         raise ValueError("log_image requires DatasetSchema with an ImageMetricConfig as default_configs")
 
     return why.log(row=images, schema=schema)
+
+
+# Register it so Multimetric and ProfileView can deserialize
+register_metric(ImageMetric)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/migration/converters.py` & `whylogs-1.2.0/whylogs/migration/converters.py`

 * *Files 18% similar despite different names*

```diff
@@ -13,20 +13,22 @@
     IntsMetric,
     StandardMetric,
     TypeCountersMetric,
 )
 from whylogs.core.metrics.metric_components import (
     FractionalComponent,
     FrequentStringsComponent,
+    HllComponent,
     IntegralComponent,
     KllComponent,
     MaxIntegralComponent,
     MinIntegralComponent,
 )
-from whylogs.core.metrics.metrics import CardinalityMetric
+from whylogs.core.metrics.metrics import CardinalityMetric, Metric
+from whylogs.core.model_performance_metrics import ModelPerformanceMetrics
 from whylogs.core.proto import SegmentTag
 from whylogs.core.proto.v0 import (
     ColumnMessageV0,
     CountersV0,
     DatasetProfileMessageV0,
     DatasetPropertiesV0,
     FrequentItemsSketchMessageV0,
@@ -36,14 +38,15 @@
     SchemaMessageV0,
     VarianceMessage,
 )
 from whylogs.core.segment import Segment
 from whylogs.core.segmentation_partition import SegmentationPartition
 from whylogs.core.utils import read_delimited_protobuf
 from whylogs.core.utils.timestamp_calculations import to_utc_milliseconds
+from whylogs.core.view.dataset_profile_view import _TAG_PREFIX
 
 _DEFAULT_V0_LG_MAX_K = 12
 _DEFAULT_V0_KLL_K = 128
 _DEFAULT_V0_FI_LG_K = 10
 
 EMPTY_FI_SKETCH: bytes = ds.frequent_strings_sketch(_DEFAULT_V0_FI_LG_K).serialize()
 EMPTY_HLL: bytes = ds.hll_sketch(_DEFAULT_V0_LG_MAX_K).serialize_compact()
@@ -55,15 +58,14 @@
 logger = getLogger(__name__)
 
 PARTITION_ID = "segp_id"
 PARTITION_NAME = "segp_name"
 PARTITION_HAS_FILTER = "segp_filter"
 SEGMENT_ON_COLUMN = "segp_col"
 SEGMENT_ON_COLUMNS = "segp_cols"
-_TAG_PREFIX = "whylogs.tag."
 
 
 def _generate_segment_tags_metadata(
     segment: Segment, partition: SegmentationPartition
 ) -> Tuple[Dict[str, str], List[SegmentTag], Dict[str, str]]:
     segment_metadata: Optional[Dict[str, str]] = None
     segment_tags: Optional[List[SegmentTag]] = None
@@ -101,56 +103,88 @@
             segment_metadata[SEGMENT_ON_COLUMN] = segment_columns[0]
         elif len(segment_columns) > 1:
             segment_metadata[SEGMENT_ON_COLUMNS] = "".join(["(" + str(col) + ")" for col in segment_columns])
 
     return segment_message_tags, segment_tags, segment_metadata
 
 
-def read_v0_to_view(path: str) -> DatasetProfileView:
+def read_v0_to_view(path: str, allow_partial: bool = False) -> DatasetProfileView:
     with open(path, "r+b") as f:
         v0_msg = read_delimited_protobuf(f, DatasetProfileMessageV0)
         if v0_msg is None:
             raise DeserializationError("Unexpected empty message")
-        return v0_to_v1_view(v0_msg)
+        return v0_to_v1_view(v0_msg, allow_partial)
 
 
-def v0_to_v1_view(msg: DatasetProfileMessageV0) -> DatasetProfileView:
+def v0_to_v1_view(msg: DatasetProfileMessageV0, allow_partial: bool = False) -> DatasetProfileView:
     columns: Dict[str, ColumnProfileView] = {}
 
-    dataset_timestamp = datetime.datetime.fromtimestamp(msg.properties.data_timestamp / 1000.0)
-    creation_timestamp = datetime.datetime.fromtimestamp(msg.properties.session_timestamp / 1000.0)
-
+    dataset_timestamp = datetime.datetime.fromtimestamp(msg.properties.data_timestamp / 1000.0, datetime.timezone.utc)
+    creation_timestamp = datetime.datetime.fromtimestamp(
+        msg.properties.session_timestamp / 1000.0, datetime.timezone.utc
+    )
+    aggregated_errors: Dict[str, Dict[str, str]] = dict()
     for col_name, col_msg in msg.columns.items():
-        dist_metric = _extract_dist_metric(col_msg)
-        fs = FrequentStringsComponent(ds.frequent_strings_sketch.deserialize(col_msg.frequent_items.sketch))
-        fi_metric = FrequentItemsMetric(frequent_strings=fs)
-        count_metrics = _extract_col_counts(col_msg)
-        type_counters_metric = _extract_type_counts_metric(col_msg)
-        int_metric = _extract_ints_metric(col_msg)
-
-        columns[col_name] = ColumnProfileView(
-            metrics={
-                StandardMetric.distribution.name: dist_metric,
-                StandardMetric.frequent_items.name: fi_metric,
-                StandardMetric.counts.name: count_metrics,
-                StandardMetric.types.name: type_counters_metric,
-                StandardMetric.cardinality.name: type_counters_metric,
-                StandardMetric.ints.name: int_metric,
-            }
-        )
+        extracted_metrics: Dict[str, Metric] = dict()
+        failed_metrics: Dict[str, str] = dict()
+        extracted_metrics[StandardMetric.distribution.name] = _extract_dist_metric(col_msg)
+        extracted_metrics[StandardMetric.counts.name] = _extract_col_counts(col_msg)
+        extracted_metrics[StandardMetric.types.name] = _extract_type_counts_metric(col_msg)
+        extracted_metrics[StandardMetric.cardinality.name] = _extract_cardinality_metric(col_msg)
+        extracted_metrics[StandardMetric.ints.name] = _extract_ints_metric(col_msg)
+
+        try:
+            fs = FrequentStringsComponent(ds.frequent_strings_sketch.deserialize(col_msg.frequent_items.sketch))
+            extracted_metrics[StandardMetric.frequent_items.name] = FrequentItemsMetric(frequent_strings=fs)
+        except Exception as e:
+            failure_message = (
+                f"Failed extracting ({StandardMetric.frequent_items.name}) metric from v0 profile. "
+                f"Column: {col_name}: encountered {e}."
+            )
+            logger.error(failure_message)
+            if allow_partial:
+                failed_metrics[StandardMetric.frequent_items.name] = f"{e}"
+            else:
+                raise DeserializationError(failure_message)
+        if failed_metrics:
+            aggregated_errors[col_name] = failed_metrics
+
+        columns[col_name] = ColumnProfileView(metrics=extracted_metrics)
+    if aggregated_errors:
+        warning_message = [f"column: {str(col)}->{aggregated_errors[col]}" for col in aggregated_errors]
+        logger.warning(f"Encountered errors while converting to v1: {warning_message}")
+    else:
+        logger.info("Successfully converted v0 metrics to v1!")
+
+    metadata = None
+
+    if msg.properties.metadata:
+        logger.info(f"Found and copied over metadata from v0 message: {msg.properties.metadata}")
+        metadata = dict(msg.properties.metadata)
 
     if msg.properties.tags:
-        logger.info(
-            f"Found tags in v0 message, ignoring while converting to v1 DatasetProfileView: {msg.properties.tags}"
+        logger.warning(
+            f"Found tags in v0 message, these will be moved to the metadata collection in DatasetProfileView: {msg.properties.tags}"
         )
+        if metadata is None:
+            metadata = dict(msg.properties.tags)
+        else:
+            metadata.update(dict(msg.properties.tags))
 
-    return DatasetProfileView(
-        columns=columns, dataset_timestamp=dataset_timestamp, creation_timestamp=creation_timestamp
+    converted_profile = DatasetProfileView(
+        columns=columns, dataset_timestamp=dataset_timestamp, creation_timestamp=creation_timestamp, metadata=metadata
     )
 
+    if msg.modeProfile:
+        logger.info("Found ModelPerformanceMetrics in v0 message, adding to converted v1 view.")
+        perf_metrics = ModelPerformanceMetrics.from_protobuf(msg.modeProfile)
+        converted_profile.add_model_performance_metrics(perf_metrics)
+
+    return converted_profile
+
 
 def _extract_ints_metric(msg: ColumnMessageV0) -> IntsMetric:
     int_max = msg.numbers.longs.max
     int_min = msg.numbers.longs.min
     return IntsMetric(max=MaxIntegralComponent(int_max), min=MinIntegralComponent(int_min))
 
 
@@ -181,41 +215,62 @@
     string_count = msg.schema.typeCounts.get(InferredType.STRING)
     obj_count = msg.schema.typeCounts.get(InferredType.UNKNOWN)
     return TypeCountersMetric(
         integral=IntegralComponent(int_count or 0),
         fractional=IntegralComponent(frac_count or 0),
         boolean=IntegralComponent(bool_count or 0),
         string=IntegralComponent(string_count or 0),
+        tensor=IntegralComponent(0),
         object=IntegralComponent(obj_count or 0),
     )
 
 
+def _extract_cardinality_metric(msg: ColumnMessageV0) -> CardinalityMetric:
+    sketch_message = msg.cardinality_tracker
+    if sketch_message:
+        hll_bytes = sketch_message.sketch
+        hll = HllComponent(ds.hll_sketch.deserialize(hll_bytes))
+        return CardinalityMetric(hll=hll)
+    else:
+        return CardinalityMetric.zero()
+
+
 def _extract_schema_message_v0(col_prof: ColumnProfileView) -> SchemaMessageV0:
-    metric: TypeCountersMetric = col_prof.get_metric(TypeCountersMetric.get_namespace())
-    if metric is None:
-        return SchemaMessageV0()
+    types: TypeCountersMetric = col_prof.get_metric(TypeCountersMetric.get_namespace())
+    counts: ColumnCountsMetric = col_prof.get_metric(ColumnCountsMetric.get_namespace())
+    if types is None:
+        types = TypeCountersMetric.zero()
+
+    if counts is None:
+        counts = ColumnCountsMetric.zero()
 
     type_counts: Dict[int, int] = {}
-    type_counts[InferredType.INTEGRAL] = metric.integral.value
-    type_counts[InferredType.BOOLEAN] = metric.boolean.value
-    type_counts[InferredType.FRACTIONAL] = metric.fractional.value
-    type_counts[InferredType.STRING] = metric.string.value
-    type_counts[InferredType.UNKNOWN] = metric.object.value
+    type_counts[InferredType.INTEGRAL] = types.integral.value
+    type_counts[InferredType.BOOLEAN] = types.boolean.value
+    type_counts[InferredType.FRACTIONAL] = types.fractional.value
+    type_counts[InferredType.STRING] = types.string.value
+    type_counts[InferredType.UNKNOWN] = types.object.value
+    type_counts[InferredType.NULL] = counts.null.value
 
     msg_v0 = SchemaMessageV0(
         typeCounts=type_counts,
     )
 
     return msg_v0
 
 
 def _extract_col_counts(msg: ColumnMessageV0) -> ColumnCountsMetric:
     count_n = msg.counters.count
     count_null = msg.counters.null_count
-    return ColumnCountsMetric(n=IntegralComponent(count_n or 0), null=IntegralComponent(count_null.value or 0))
+    return ColumnCountsMetric(
+        n=IntegralComponent(count_n or 0),
+        null=IntegralComponent(count_null.value or 0),
+        inf=IntegralComponent(0),
+        nan=IntegralComponent(0),
+    )
 
 
 def _extract_counters_v0(col_prof: ColumnProfileView) -> CountersV0:
     counts_metric: ColumnCountsMetric = col_prof.get_metric(ColumnCountsMetric.get_namespace())
     count_options = dict(count=0)
 
     if counts_metric is None:
@@ -279,15 +334,14 @@
 
 
 def v1_to_dataset_profile_message_v0(
     profile_view: DatasetProfileView,
     segment: Optional[Segment],
     partition: Optional[SegmentationPartition],
 ) -> DatasetProfileMessageV0:
-
     segment_message_tags: Optional[Dict[str, str]] = None
     segment_tags: Optional[List[SegmentTag]] = None
     segment_metadata: Optional[Dict[str, str]] = None
 
     if partition and partition.mapper and partition.mapper.col_names:
         segment_message_tags, segment_tags, segment_metadata = _generate_segment_tags_metadata(segment, partition)
     elif partition:
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/enums/enums.py` & `whylogs-1.2.0/whylogs/viz/enums/enums.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/extensions/reports/html_report.py` & `whylogs-1.2.0/whylogs/viz/extensions/reports/html_report.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/extensions/reports/profile_summary.py` & `whylogs-1.2.0/whylogs/viz/extensions/reports/profile_summary.py`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/css/bootstrap.min.css` & `whylogs-1.2.0/whylogs/viz/html/css/bootstrap.min.css`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/css/whylogs-styles.css` & `whylogs-1.2.0/whylogs/viz/html/css/whylogs-styles.css`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Bold.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Bold.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Bold.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Bold.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Bold.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Bold.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-BoldItalic.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-BoldItalic.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-BoldItalic.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-BoldItalic.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-BoldItalic.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-BoldItalic.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Italic.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Italic.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Italic.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Italic.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Italic.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Italic.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Medium.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Medium.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Medium.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Medium.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Medium.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Medium.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-MediumItalic.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-MediumItalic.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-MediumItalic.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-MediumItalic.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-MediumItalic.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-MediumItalic.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Regular.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Regular.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Regular.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Regular.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-Regular.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-Regular.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBold.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBold.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBold.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBold.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBold.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBold.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.ttf` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.ttf`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff2` & `whylogs-1.2.0/whylogs/viz/html/fonts/Asap-SemiBoldItalic.woff2`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/images/placement-chart.png` & `whylogs-1.2.0/whylogs/viz/html/images/placement-chart.png`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/images/whylabs-favicon.png` & `whylogs-1.2.0/whylogs/viz/html/images/whylabs-favicon.png`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/js/d3.min.js` & `whylogs-1.2.0/whylogs/viz/html/js/d3.min.js`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/js/handlebars.js` & `whylogs-1.2.0/whylogs/viz/html/js/handlebars.js`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/js/jquery-3.6.0.min.js` & `whylogs-1.2.0/whylogs/viz/html/js/jquery-3.6.0.min.js`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/js/whylogs-script.js` & `whylogs-1.2.0/whylogs/viz/html/js/whylogs-script.js`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-for-jupyter-notebook.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-profile-summary.html`

 * *Files 4% similar despite different names*

```diff
@@ -164,15 +164,15 @@
       }
 
       .wl-table-head-wraper {
         background-color: var(--white);
       }
 
       .wl-table-head {
-        position: relative;
+        position: sticky;
         left: 0;
         min-width: 100px;
         border-bottom: 2px solid var(--brandSecondary100);
         font-size: 12px;
         line-height: 1.67;
         white-space: nowrap;
       }
@@ -182,15 +182,15 @@
       }
 
       .wl-table-body {
         display: table-row-group;
       }
 
       .wl-table-row .wl-table-cell:first-child{
-        position: relative;
+        position: sticky;
         left: 0;
         background-color: var(--white);
         border-right-width: 2px;
       }
 
       /* Table custom style */
 
@@ -227,17 +227,17 @@
         border-radius: 20px;
         white-space: nowrap;
       }
 
       /* Property side panel */
 
       .wl-compare-profile {
-        position: relative;
-        left: 0;
-        padding: 18px;
+        z-index: 999;
+        position: absolute;
+        right: 0;
         background: var(--white);;
         border-bottom: 1px solid var(--brandSecondary200);
       }
 
       /* Screen on smaller screens */
       .no-responsive {
         display: none;
@@ -579,15 +579,15 @@
         visibility: hidden;
         background: black;
         color: white;
         border: 1px solid black;
         text-align: start;
         padding: 3px;
         position: absolute;
-        z-index: 1;
+        z-index: 1002;
         top: 0;
         left: 100%;
         margin-left: 5px;
         opacity: 0;
         transition: opacity 0.5s;
         font-size: 13px;
         font-weight: normal;
@@ -659,172 +659,160 @@
         <div class="container-fluid">
           <div class="feature-summary-statistics-wrap">
             <div class="feature-summary-statistics">
               <div class="mb-4">
                   <strong class="header-title">Profile Summary</strong>
               </div>
               <div class="display-flex statistics">
-                  <div class="padding-right-30">
-                    <div class="statistic-number-title">Observations</div>
-                    <div class="statistic-number">{{{observations this}}}</div>
+                <div class="padding-right-30">
+                  <div class="statistic-number-title">Observations
+                    <div class="tooltip-full-number">
+                      <span class="question-mark">?</span>
+                    <span class="tooltiptext">
+                     <div class="mb-1">The sum of counts for each feature. For a single dataframe, it is equal to the number of cells, i.e., rows * columns.</div>
+                    </span>
+                    </div>
+                    </div>
+                  <div class="statistic-number">{{{observations this}}}</div>
+                </div>
+                <div class="padding-right-30">
+                  <div class="statistic-number-title">Missing Cells</div>
+                  <div class="statistic-number">
+                    {{{missingCells this}}}
+                    <div>{{{missingCellsPercentage this}}}</div>
                   </div>
-                  <div class="padding-right-30">
-                    <div class="statistic-number-title">Missing Cells</div>
-                    <div class="statistic-number">
-                      {{{missingCells this}}}
-                      <div>{{{missingCellsPercentage this}}}</div>
+                </div>
+                <div class="wl-compare-profile" id="compare-profile" style="display: flex; justify-content: space-around">
+                  <div class="drift-detection-wrap">
+                    <div class="drift-detection display-flex">
+                      <div class="drift-detection-search-input-wrap display-flex">
+                        <div class="drift-detection-search-input search-input ">
+                          <input type="text" id="wl__feature-search" placeholder="Quick search..."/>
+                          <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAGdSURBVHgBpZK7TkJBEIZnZoVocdTYyQNALxpNKPQBMEaNJsbCRMKhl8ISWwt6AaksCF5iTHgAGhJD4AHkAaAzGiwUsjvOQnO4SYh/cXbPzO43OxcEj9Zy92EiFSXNIfvPyE1kKFfdoxJMENpP6DrvLC0vJoEwCgwto7DWcxoIIHBYbA3NmKwnDltjAeuZhyul1DaTTlfPB6Nt5Z53DOgky4P875+nlctY2+unjZviLklkJhi5bPUa3y/7qJuQUM7PinMy7CdQc1Gh16vnBxPzrMROmlKQEgKNASAHLQCmSIGpS75O+O5pdQAgVXaIqTkNwDDXHmcnW3VmHZoGMLoTsOt88+NrAMCIZdu+iLTyTwKRa1Md6YKfOgXbzO7K8sWku5u5RxcRV5EpPezrzcHGbXEXWaUkgkweZ/UC9YrK3zqggFw5FBZfm8EUavHj7AjAKpIvBDrGn+pNnlcyhYgqbcC41idr1gvB4SdZkDbzQa21gwv0Vj07aPTtL07XdDOyDXohCDNoHIRmAVRie20f+RKybRDQDvxHkXy/7b/DrayncLbMwQAAAABJRU5ErkJggg=="/>
+                        </div>
+                        <div class="wl__dropdown_arrow-icon" >
+                          <div onclick="openFilter()" class="close-filter-button">
+                            <div class="display-flex close-filter-icon d-none">
+                              <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAALCAYAAACprHcmAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAADFSURBVHgBfY+xDcIwEEXvnLQBZQkYAEhDwwKpEEK0CCZgAEjJCEmgjYSAygxAHTZgFRSOsyUjY5mcZFnn/+78PwBXf3+MoKWUPuYjVBPFnTwpr9t/oNJfcTfXsAhRAlDqDhhQIPYgpAqNMDqcUqSAYZT1epr9gAHt6uXshvYme4DYHQJNDKh0dD0m5WXB10Y3Fqjtuh7fROn3oREDWxfeMLyRsMnc0OgDzdduaA0Pi3Plgr7Q2kaAePeBqh6rueSNBVt6fgCwBV1JLF3rlAAAAABJRU5ErkJggg=="/>
+                            </div>
+                            <div class="display-flex filter-icon">
+                              <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAPCAYAAADtc08vAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAACSSURBVHgBrZLBCYAwDEWTUjw7igcdwI1cxkNXUJzBEVzFAbSVKoKmaVrEB6GHJv/w+AACtRk7P9IONv1QOYUl96k0zv61m2tjARoLtSDI3EFsgIJ4uoXrMLazO72CRG2mzg/8BSdVlEjhpGZJjAWdAZJECpWalEhJSs1pHuUlMad5FFai1Lwg4Ckx1TxKIPFL8w55mEWd8VjPGAAAAABJRU5ErkJggg=="/>
+                            </div>
+                          </div>
+                          <span class="notif-circle-container">
+                            <span class="notif-circle"></span>
+                          </span>
+                        </div>
+                      </div>
                     </div>
                   </div>
-              </div>
+                  <div class="dropdown-container flex-direction-colum mb-2 d-none" id="dropdown-container">
+                    <div class="filter-options">
+                      <div class="filter-options-title space-between dropdown">
+                        <p>Filter by type</p>
+                      </div>
+                      <div class="form-check mb-1 mt-2">
+                        <input
+                          class="form-check-input wl__feature-filter-input"
+                          type="checkbox"
+                          name="checkbox"
+                          value="Discrete"
+                          id="inferredDiscrete"
+                          onclick="changeDiscreteValue()"
+                          checked
+                        />
+                        <label class="form-check-label" for="inferredDiscrete">
+                          Inferred discrete (<span class="wl__feature-count--discrete">{{getDiscreteTypeCount}}</span>)
+                        </label>
+                      </div>
+                      <div class="form-check mb-1">
+                        <input
+                          class="form-check-input wl__feature-filter-input"
+                          type="checkbox"
+                          name="checkbox"
+                          value="Non-discrete"
+                          id="inferredNonDiscrete"
+                          onclick="changeNonDiscreteValue()"
+                          checked
+                        />
+                        <label class="form-check-label" for="inferredNonDiscrete">
+                          Inferred non-discrete (<span
+                            class="wl__feature-count--non-discrete"
+                          >{{getNonDiscreteTypeCount}}</span>)
+                        </label>
+                      </div>
+                      <div class="form-check mb-1">
+                        <input
+                          class="form-check-input wl__feature-filter-input"
+                          type="checkbox"
+                          name="checkbox"
+                          value="Unknown"
+                          id="inferredUnknown"
+                          onclick="changeUnknwonValue()"
+                          checked
+                        />
+                        <label class="form-check-label" for="inferredUnknown">
+                          Unknown (<span class="wl__feature-count--unknown">{{getUnknownTypeCount}}</span>)
+                        </label>
+                      </div>
+                    </div>
+                  </div>
+                  </div>
             </div>
           </div>
           <div class="row">
             <div class="main">
-              <div class="wl-compare-profile" id="compare-profile">
-               <div class="drift-detection-wrap">
-                 <div class="drift-detection display-flex">
-                   <div class="drift-detection-info flex-direction-colum">
-                     <div class="drift-detection-info-title-wrap display-flex">
-                       <p class="drift-detection-info-title">
-                         Drift detected in
-                         <span class="drift-count"></span>
-                         of
-                         <span class="all-features"></span>
-                         features
-                       </p>
-                     </div>
-                     <div class="drift-detection-info-drifts display-flex" id="drift-detection-info-drifts">
-                     </div>
-                   </div>
-                   <div class="drift-detection-search-input-wrap display-flex">
-                     <div class="drift-detection-search-input search-input">
-                       <input type="text" id="wl__feature-search" placeholder="Quick search..."/>
-                       <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAGdSURBVHgBpZK7TkJBEIZnZoVocdTYyQNALxpNKPQBMEaNJsbCRMKhl8ISWwt6AaksCF5iTHgAGhJD4AHkAaAzGiwUsjvOQnO4SYh/cXbPzO43OxcEj9Zy92EiFSXNIfvPyE1kKFfdoxJMENpP6DrvLC0vJoEwCgwto7DWcxoIIHBYbA3NmKwnDltjAeuZhyul1DaTTlfPB6Nt5Z53DOgky4P875+nlctY2+unjZviLklkJhi5bPUa3y/7qJuQUM7PinMy7CdQc1Gh16vnBxPzrMROmlKQEgKNASAHLQCmSIGpS75O+O5pdQAgVXaIqTkNwDDXHmcnW3VmHZoGMLoTsOt88+NrAMCIZdu+iLTyTwKRa1Md6YKfOgXbzO7K8sWku5u5RxcRV5EpPezrzcHGbXEXWaUkgkweZ/UC9YrK3zqggFw5FBZfm8EUavHj7AjAKpIvBDrGn+pNnlcyhYgqbcC41idr1gvB4SdZkDbzQa21gwv0Vj07aPTtL07XdDOyDXohCDNoHIRmAVRie20f+RKybRDQDvxHkXy/7b/DrayncLbMwQAAAABJRU5ErkJggg=="/>
-                     </div>
-                     <div class="wl__dropdown_arrow-icon">
-                       <div onclick="openFilter()" class="close-filter-button">
-                         <div class="display-flex close-filter-icon d-none">
-                           <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAALCAYAAACprHcmAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAADFSURBVHgBfY+xDcIwEEXvnLQBZQkYAEhDwwKpEEK0CCZgAEjJCEmgjYSAygxAHTZgFRSOsyUjY5mcZFnn/+78PwBXf3+MoKWUPuYjVBPFnTwpr9t/oNJfcTfXsAhRAlDqDhhQIPYgpAqNMDqcUqSAYZT1epr9gAHt6uXshvYme4DYHQJNDKh0dD0m5WXB10Y3Fqjtuh7fROn3oREDWxfeMLyRsMnc0OgDzdduaA0Pi3Plgr7Q2kaAePeBqh6rueSNBVt6fgCwBV1JLF3rlAAAAABJRU5ErkJggg=="/>
-                         </div>
-                         <div class="display-flex filter-icon">
-                           <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAPCAYAAADtc08vAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAACSSURBVHgBrZLBCYAwDEWTUjw7igcdwI1cxkNXUJzBEVzFAbSVKoKmaVrEB6GHJv/w+AACtRk7P9IONv1QOYUl96k0zv61m2tjARoLtSDI3EFsgIJ4uoXrMLazO72CRG2mzg/8BSdVlEjhpGZJjAWdAZJECpWalEhJSs1pHuUlMad5FFai1Lwg4Ckx1TxKIPFL8w55mEWd8VjPGAAAAABJRU5ErkJggg=="/>
-                         </div>
-                       </div>
-                       <span class="notif-circle-container">
-                         <span class="notif-circle"></span>
-                       </span>
-                     </div>
-                   </div>
-                 </div>
-               </div>
-               <div class="dropdown-container flex-direction-colum mb-2 d-none" id="dropdown-container">
-                 <div class="filter-options">
-                   <div class="filter-options-title space-between dropdown">
-                     <p>Filter by type</p>
-                   </div>
-                   <div class="form-check mb-1 mt-2">
-                     <input
-                       class="form-check-input wl__feature-filter-input"
-                       type="checkbox"
-                       name="checkbox"
-                       value="Discrete"
-                       id="inferredDiscrete"
-                       onclick="changeDiscreteValue()"
-                       checked
-                     />
-                     <label class="form-check-label" for="inferredDiscrete">
-                       Inferred discrete (<span class="wl__feature-count--discrete">{{getDiscreteTypeCount}}</span>)
-                     </label>
-                   </div>
-                   <div class="form-check mb-1">
-                     <input
-                       class="form-check-input wl__feature-filter-input"
-                       type="checkbox"
-                       name="checkbox"
-                       value="Non-discrete"
-                       id="inferredNonDiscrete"
-                       onclick="changeNonDiscreteValue()"
-                       checked
-                     />
-                     <label class="form-check-label" for="inferredNonDiscrete">
-                       Inferred non-discrete (<span
-                         class="wl__feature-count--non-discrete"
-                       >{{getNonDiscreteTypeCount}}</span>)
-                     </label>
-                   </div>
-                   <div class="form-check mb-1">
-                     <input
-                       class="form-check-input wl__feature-filter-input"
-                       type="checkbox"
-                       name="checkbox"
-                       value="Unknown"
-                       id="inferredUnknown"
-                       onclick="changeUnknwonValue()"
-                       checked
-                     />
-                     <label class="form-check-label" for="inferredUnknown">
-                       Unknown (<span class="wl__feature-count--unknown">{{getUnknownTypeCount}}</span>)
-                     </label>
-                   </div>
-                 </div>
-               </div>
-              </div>
               <div class="wl-table-wrap" id="table-content">
                 <div class="wl-table">
                   <div class="wl-table-heading">
                     <div class="wl-table-row wl-table-row--bottom-shadow">
                       <div class="wl-table-head wl-table-head-wraper">
                         <div class="wl-table-head table-border-none graph-table-head">Target</div>
-                        <div class="wl-table-head table-border-none reference-table-head">Reference</div>
-                      </div>
-                      <div class="wl-table-head wl-table-head-wraper text-align-end" style="cursor: pointer;" id="diff-from-ref">
-                        <p id="pvalue" > p-value </p>
-                        <p id="pvalue-asc" style="display: none;"> p-value &#9650 </p>
-                        <p id="pvalue-desc" style="display: none;"> p-value &#9660 </p>
-
-                        <div class="tooltip-full-number">
-                            <span class="question-mark">?</span>
-                          <span class="tooltiptext">
-                           <div class="mb-1">p-values are calculated with K-S test for numerical features and Chi-squared for categorical features.</div>
-                          </span>
-                        </div>
                       </div>
                       <div class="wl-table-head wl-table-head-wraper text-align-end">Total count</div>
+                      <div class="wl-table-head wl-table-head-wraper text-align-end">Missing</div>
                       <div class="wl-table-head wl-table-head-wraper text-align-end">Mean</div>
+                      <div class="wl-table-head wl-table-head-wraper text-align-end">Min</div>
+                      <div class="wl-table-head wl-table-head-wraper text-align-end">Max</div>
+
                     </div>
                   </div>
                   <ul class="wl-table-body wl__table-body" id="table-body">
                     {{#each this.columns}}
                     <li
                     {{#if this.numberSummary}} class="wl-table-row wl-table-row--clickable" {{else}} class="wl-table-row" {{/if}}
                     data-feature-name={{@key}}
                     data-inferred-type={{inferredType this}}
                     data-scroll-to-feature-name={{@key}}
-                    data-p-value={{getpvalue this}}
                   >
                       <div class="wl-table-cell wl-table-cell__graph-wrap">
                         <div class="wl-table-cell__title-wrap">
                           <h4 class="wl-table-cell__title">{{@key}}</h4>
                           <div></div>
                         </div>
                           <div class="display-flex">
                               {{{getGraphHtml this}}}
-                              {{{getReferenceGraphHtml this}}}
                           </div>
                       </div>
                       <div
-                        class="diff-from-ref-table-cell wl-table-cell wl-table-cell--top-spacing align-middle"
-                        style="max-width: 270px; padding-right: 18px"
-                      ><div class="wl-table-cell__bedge-wrap text-align-end">
-                           {{{getDiffFromRef this}}}
-                        </div></div><div
                         class="wl-table-cell wl-table-cell--top-spacing align-middle"
-                      ><div class="text-align-end">{{totalCount this}}</div></div><div
+                      ><div class="text-align-end">{{totalCount this}}</div></div>
+                      <div
+                        class="wl-table-cell wl-table-cell--top-spacing align-middle"
+                      ><div class="text-align-end">{{missing this}}</div></div>
+                      <div
                         class="wl-table-cell wl-table-cell--top-spacing align-middle"
                       ><div class="text-align-end">{{mean this}}</div></div>
+                      <div
+                        class="wl-table-cell wl-table-cell--top-spacing align-middle"
+                      ><div class="text-align-end">{{minimumValue this}}</div></div>
+                      <div
+                        class="wl-table-cell wl-table-cell--top-spacing align-middle"
+                      ><div class="text-align-end">{{maximumValue this}}</div></div>
+
                     </li>
                     {{/each}}
                   </ul>
                 </div>
               </div>
             </div>
           </div>
@@ -844,16 +832,16 @@
   </script>
 
   <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
 
   <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.7.0/d3.min.js" integrity="sha512-cd6CHE+XWDQ33ElJqsi0MdNte3S+bQY819f7p3NUHgwQQLXSKjE4cPZTeGNI+vaxZynk1wVU3hoHmow3m089wA==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
 
   <script>
-    const getReferenceProfile = () => { return {{{reference_profile_from_whylogs}}} }
-    const referenceProfile = getReferenceProfile()
+    const getTargetProfile = () => { return {{{profile_from_whylogs}}} }
+    const targetProfile = getTargetProfile()
 
     function fixNumberTo(number, decimals = 3) {
       const fractionalDigits = String(number % 1).split('').slice(2, 2 + decimals).join('')
       return `${Math.trunc(number)}.${fractionalDigits}`
     }
 
     function registerHandlebarHelperFunctions() {
@@ -985,54 +973,14 @@
 
       function formatLabelDate(timestamp) {
         const date = new Date(timestamp);
         const format = d3.timeFormat("%Y-%m-%d %I:%M:%S %p %Z");
         return format(date);
       }
 
-      const driftCountElement = (driftCount, driftColor, driftName, driftRange) => `
-      <div class="display-flex flex-direction-column">
-        <div class="drift-detection-info-drifts-item display-flex align-items">
-          <div class="drift-detection-info-drifts-item-text display-flex align-items">
-            <p class="drift-detection-info-drifts-item-count mb-0">${driftCount}</p>
-            <p class="drift-detection-info-drifts-item-range display-flex justify-content-center mb-0">${driftRange}</p>
-          </div>
-        </div>
-      </div>
-      `
-
-      const drifts = {
-        severe: {
-          count: 0,
-          range: "with detected drift (0.00 - 0.05)",
-        },
-        moderate: {
-          count: 0,
-          range: "with possible drift (0.05 - 0.15)",
-        },
-        mild: {
-          count: 0,
-          range: "with no evidence of drift (0.15 - 1.0)",
-        }
-      };
-
-      const countOfDrifts = (driftNumber) => {
-        if(driftNumber >= 0 && driftNumber <= 0.05) {
-          Object.values(drifts)[0].count++
-          return 0
-        } else if(driftNumber > 0.05 && driftNumber <= 0.15) {
-          Object.values(drifts)[1].count++
-          return 1
-        } else if(driftNumber > 0.15) {
-          Object.values(drifts)[2].count++
-          return 2
-        }
-
-      }
-
     abbreviate_number = function(value, fixed = 0) {
       value = +value
       if (value === null) { return null; } // terminate early
       if (value === 0) { return '0'; } // terminate early
       fixed = (!fixed || fixed < 0) ? 0 : fixed; // number of decimal places to show
       var b = (value).toPrecision(2).split("e"), // get power
           k = b.length === 1 ? 0 : Math.floor(Math.min(b[1].slice(1), 14) / 3), // floor at decimals, ceiling at trillions
@@ -1073,103 +1021,52 @@
              ${newNumber}
             <div class="statistic-measurement">${suffixe}</div>
           </div>
           <span class="tooltiptext">${number}</span>
         </div>`
 
      Handlebars.registerHelper("observations", function (properties) {
-       const {value, newValue, suffixe} = abbreviate_number(referenceProfile.properties.observations)
+       const {value, newValue, suffixe} = abbreviate_number(targetProfile.properties.observations)
        return numberWithSuffixe(value, valueNumber(newValue), valueNumber(suffixe));
      });
 
      Handlebars.registerHelper("missingCells", function (properties) {
-       const {value, newValue, suffixe} = abbreviate_number(referenceProfile.properties.missing_cells)
+       const {value, newValue, suffixe} = abbreviate_number(targetProfile.properties.missing_cells)
        if (typeof value !== 'undefined' && typeof newValue !== 'undefined'  && typeof suffixe !== 'undefined' ) {
         return numberWithSuffixe(value, valueSuffixe(`${newValue}`), suffixe);
        }
        return numberWithSuffixe(0, valueNumber(0), valueNumber(''));
      });
 
      Handlebars.registerHelper("missingCellsPercentage", function (properties) {
-       const {value, newValue, suffixe} = abbreviate_number(referenceProfile.properties.missing_percentage)
+       const {value, newValue, suffixe} = abbreviate_number(targetProfile.properties.missing_percentage)
        if (typeof value !== 'undefined' && typeof newValue !== 'undefined'  && typeof suffixe !== 'undefined' ) {
         return numberWithSuffixe(value, valueSuffixe(`(${newValue}%)`), suffixe);
        }
        return numberWithSuffixe(0, valueSuffixe(`(${0}%)`), '');
      });
 
      Handlebars.registerHelper("getProfileTimeStamp", function (properties) {
        return formatLabelDate(+properties.properties.dataTimestamp)
      });
 
      Handlebars.registerHelper("getProfileName", function (properties) {
        return properties.properties.tags.name
      });
 
-      let driftCount = 0;
-      const diffFromRefTableElement = (driftFromRefNumber, circleColor) => `
-         <div class="text-color padding-5 text-align-end justify-content-center">
-           ${driftFromRefNumber}
-         </div>
-       `
-
        const cheqValueTypeNumber = (profile, profileValue) => {
          let validValue;
          if (profile && profileValue !== undefined && typeof profileValue === "number") {
            return true
          } else if (profileValue !== undefined && typeof profileValue !== "number") {
            return false
          }
        }
 
 
-       Handlebars.registerHelper("getpvalue", function (column, key) {
-        const columnKey = key.data.key
-        const {drift_from_ref} = referenceProfile.columns[columnKey]
-
-        if (cheqValueTypeNumber(referenceProfile, drift_from_ref)) {
-          const driftFromRefNumber = drift_from_ref.toPrecision(2)
-          return Number(driftFromRefNumber)
-
-        }
-      });
-
-      Handlebars.registerHelper("getDiffFromRef", function (column, key) {
-        const columnKey = key.data.key
-        const {drift_from_ref} = referenceProfile.columns[columnKey]
-
-        if (cheqValueTypeNumber(referenceProfile, drift_from_ref)) {
-          const driftFromRefNumber = drift_from_ref.toPrecision(2)
-          const driftCategory = countOfDrifts(driftFromRefNumber)
-          const circleColor = Object.values(drifts)[driftCategory].colorClass
-          if (driftCategory==0 || driftCategory == 1){
-            driftCount++
-          }
-          $(document).ready(() => {
-             $(".drift-count").html(driftCount)
-             $(".all-features").html(Object.keys(referenceProfile.columns).length)
-           })
-
-          return diffFromRefTableElement(driftFromRefNumber, circleColor)
-
-        } else if (cheqValueTypeNumber(referenceProfile, drift_from_ref) !== undefined) {
-          Object.values(drifts)[0].count++
-          return diffFromRefTableElement("undefined", "severe-drift-circle-color")
-        }
-
-        return '<p style="color: black">-</p>';
-      });
-
-      $(document).ready(() =>
-        Object.values(drifts).map(({count, name, colorClass, range}) =>{
-          $("#drift-detection-info-drifts")
-          .append(driftCountElement(count, colorClass, name, range))
-        })
-      )
-
       Handlebars.registerHelper("inferredType", function (column) {
         let infferedType = "";
 
         if (column.isDiscrete) {
           infferedType = "Discrete";
         } else {
           infferedType = "Non-discrete";
@@ -1195,23 +1092,51 @@
         if (column.featureStats) {
           return column.featureStats.total_count;
         }
 
         return "-";
       });
 
+      Handlebars.registerHelper("missing", function (column) {
+        if (column.featureStats) {
+          return column.featureStats.missing;
+        }
+
+        return "-";
+      });
+
+      Handlebars.registerHelper("minimumValue", function (column) {
+        if (column.featureStats) {
+          if (isNaN(column.featureStats.min)){return "-"}
+          return fixNumberTo(column.featureStats.min);
+        }
+
+        return "-";
+      });
+
+      Handlebars.registerHelper("maximumValue", function (column) {
+        if (column.featureStats) {
+          if (isNaN(column.featureStats.max)){return "-"}
+          return fixNumberTo(column.featureStats.max);
+        }
+
+        return "-";
+      });
+
+
       Handlebars.registerHelper("mean", function (column) {
         if (column.featureStats?.descriptive_statistics) {
+          if (isNaN(column.featureStats.descriptive_statistics.mean)){return "-"}
+          if (column.featureStats.descriptive_statistics.mean==null){return "-"}
           return fixNumberTo(column.featureStats.descriptive_statistics.mean);
         }
         return "-";
       });
 
       Handlebars.registerHelper("getGraphHtml",(column,key) => graph(column, key, null));
-      Handlebars.registerHelper("getReferenceGraphHtml",(column,key) => graph(column, key, referenceProfile));
 
       Handlebars.registerHelper("getDiscreteTypeCount", function () {
         let count = 0;
 
         Object.entries(this.columns).forEach((feature) => {
           if (feature[1].isDiscrete === true) {
             count++;
@@ -1256,29 +1181,21 @@
 
     function initWebsiteScripts() {
       const $featureSearch = document.getElementById("wl__feature-search");
       const $tableBody = document.getElementById("table-body");
       const $discrete = document.getElementById("inferredDiscrete");
       const $nonDiscrete = document.getElementById("inferredNonDiscrete");
       const $unknown = document.getElementById("inferredUnknown");
-      const $diffFromRef = document.getElementById("diff-from-ref");
 
       const activeTypes = {
         discrete: true,
         "non-discrete": true,
         unknown: true,
       };
 
-      var driftOrder = {
-        original: true,
-        descending: false,
-        ascending: false,
-      };
-      var originalColumnOrder;
-
       let searchString = "";
 
       function debounce(func, wait, immediate) {
         let timeout;
 
         return function () {
           const context = this;
@@ -1302,57 +1219,21 @@
         if (item === undefined) {
           $notifCircleContainer.removeClass("d-none")
         } else {
           $notifCircleContainer.addClass("d-none")
         }
       }
 
-
-      function orderByDrift(direction) {
-        var tableBodyChildren = $tableBody.children;
-        if (driftOrder['original']) {
-          driftOrder['original'] = false
-          driftOrder['descending'] = true
-
-          originalColumnOrder = [...tableBodyChildren];
-          tableBodyChildren = [...tableBodyChildren].sort((a,b) => (b.dataset.pValue - a.dataset.pValue))
-          document.getElementById("pvalue").style.display = "none";
-          document.getElementById("pvalue-desc").style.display = "";
-
-        } else if (driftOrder['descending']) {
-          driftOrder['descending'] = false
-          driftOrder['ascending'] = true
-          tableBodyChildren = [...tableBodyChildren].sort((a,b) => (a.dataset.pValue - b.dataset.pValue))
-          document.getElementById("pvalue-desc").style.display = "none";
-          document.getElementById("pvalue-asc").style.display = "";
-
-
-        } else if (driftOrder['ascending']) {
-          driftOrder['ascending'] = false
-          driftOrder['original'] = true
-
-          tableBodyChildren = originalColumnOrder;
-          document.getElementById("pvalue-asc").style.display = "none";
-          document.getElementById("pvalue").style.display = "";
-
-        }
-
-        for (let i = 0; i < tableBodyChildren.length; i++) {
-          console.log(tableBodyChildren[i].dataset.pValue)
-        }
-        for (var i = 0; i < tableBodyChildren.length; i++){$tableBody.append(tableBodyChildren[i])}
-      }
-
-
       function handleSearch() {
         const tableBodyChildren = $tableBody.children;
 
         for (let i = 0; i < tableBodyChildren.length; i++) {
           const type = tableBodyChildren[i].dataset.inferredType.toLowerCase();
           const name = tableBodyChildren[i].dataset.featureName.toLowerCase();
+
           if (activeTypes[type] && name.startsWith(searchString)) {
             tableBodyChildren[i].style.display = "";
           } else {
             tableBodyChildren[i].style.display = "none";
           }
         }
       }
@@ -1361,21 +1242,14 @@
         "keyup",
         debounce((event) => {
           searchString = event.target.value.toLowerCase();
           handleSearch();
         }, 100),
       );
 
-      $diffFromRef.addEventListener(
-        "click",
-        debounce((event) => {
-          orderByDrift();
-        }, 100),
-      );
-
       $discrete.addEventListener("change", (event) => {
         if (event.currentTarget.checked) {
           activeTypes["discrete"] = true;
         } else {
           activeTypes["discrete"] = false;
         }
         handleSearch();
@@ -1398,30 +1272,16 @@
         } else {
           activeTypes["unknown"] = false;
         }
         handleSearch();
         filterNotification()
       });
 
-      function checkCurrentProfile(item, referenceItem) {
-        if (referenceProfile && Object.values(referenceProfile)) {
-          return referenceItem
-        } else {
-          return item
-        }
-      }
 
-      if(checkCurrentProfile(true, false)) {
-        $(".svg-container").css("padding-bottom", "27%")
-        $("#diff-from-ref").addClass("d-none")
-        $(".diff-from-ref-table-cell").addClass("d-none")
-      } else {
-        $("#diff-from-ref").removeClass("d-none")
-        $(".diff-from-ref-table-cell").removeClass("d-none")
-      }
+      $(".svg-container").css("padding-bottom", "27%")
     }
 
     function checkedBoxes() {
       const $boxes = $('input[name=checkbox]:checked');
       const $notifCircleContainer = $(".notif-circle-container")
 
       if ($boxes.length) {
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-bar-chart.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-bar-chart.html`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-constraints-report.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-constraints-report.html`

 * *Files 6% similar despite different names*

```diff
@@ -72,14 +72,44 @@
 
       .header-title {
         font-size: 26px;
         font-weight: 700;
         color: #444444;
       }
 
+      .tooltip-full-number {
+        position: relative;
+        display: inline-block;
+      }
+
+      .tooltip-full-number .tooltiptext {
+        visibility: hidden;
+        background: black;
+        color: white;
+        border: 1px solid black;
+        text-align: start;
+        padding: 3px;
+        position: absolute;
+        z-index: 1;
+        top: 0;
+        left: 100%;
+        margin-left: 5px;
+        opacity: 0;
+        transition: opacity 0.5s;
+        font-size: 13px;
+        font-weight: normal;
+        line-height: 100%;
+      }
+
+      .tooltip-full-number:hover .tooltiptext {
+        visibility: visible;
+        opacity: 1;
+      }
+
+
       .wl-compare-profile {
         position: relative;
         left: 0;
         padding: 30px;
         margin-bottom: 20px;
         background: var(--white);;
         border-bottom: 1px solid #CED4DA;
@@ -505,16 +535,48 @@
         if (status) {
           return passedItem
         } else {
           return failedItem
         }
       }
 
-      const alertListElement = (name, text, status) => {
+      const alertListElement = (name, text, status, summary) => {
+        if (summary == null){
+          return (
+          `<div
+             data-inferred-type=${alertListItemStatus(status, "passed", "failed")}
+             class="alert-list-item display-flex justify-content-space-between align-items-center mb-2"
+           >
+            <div class="alert-list-text">
+              ${
+                name &&
+                alertListItemStatus(
+                  status,
+                  `<mark class="blue-mark">${name}</mark>`,
+                  `<mark class="red-mark">${name}</mark>`
+                )
+              }
+              ${text}
+            </div>
+              ${
+                alertListItemStatus(
+                  status,
+                  `
+                  <div class="turquoise-background-color alert-tag">Passed</div>
+                  `
+                  ,
+                  `
+                  <div class="bordeaux-background-color alert-tag">Failed</div>
+                  `
+                )
+              }
+              </div>`
+        )
 
+        }
         return (
           `<div
              data-inferred-type=${alertListItemStatus(status, "passed", "failed")}
              class="alert-list-item display-flex justify-content-space-between align-items-center mb-2"
            >
             <div class="alert-list-text">
               ${
@@ -526,19 +588,35 @@
                 )
               }
               ${text}
             </div>
               ${
                 alertListItemStatus(
                   status,
-                  `<div class="turquoise-background-color alert-tag">Passed</div>`,
-                  `<div class="bordeaux-background-color alert-tag">Failed</div>`
+                  `
+                  <div class="tooltip-full-number">
+                    <div class="turquoise-background-color alert-tag">Passed
+                      <span class="tooltiptext">
+                          <pre class="mb-1"> ${JSON.stringify(summary, null, 2)} </pre>
+                        </span>
+                    </div>
+                  </div>`
+
+                  ,
+                  `
+                  <div class="tooltip-full-number">
+                    <div class="bordeaux-background-color alert-tag">Failed
+                      <span class="tooltiptext">
+                        <pre class="mb-1"> ${JSON.stringify(summary, null, 2)} </pre>
+                        </span>
+                    </div>
+                  </div>`
                 )
               }
-          </div>`
+              </div>`
         )
       }
 
       let failedConstraints = 0;
 
       Handlebars.registerHelper("getProfileTimeStamp", function (column) {
         return formatLabelDate(+column.properties.dataTimestamp)
@@ -549,19 +627,19 @@
       });
 
 
       Handlebars.registerHelper("alertLIst", function (column) {
         let alertListItem = column.map((value) => {
           if (value[1][0]) {
             let alertListValue = value[1].map((cstr)=>{
-              return alertListElement(value[0],cstr[0],cstr[cstr.length - 1] === 0 || (failedConstraints++, false))
+              return alertListElement(value[0],cstr[0],cstr[cstr.length - 1] === 0 || (failedConstraints++, false), value[3])
             })
             return alertListValue.join(' ')
           } else {
-            return alertListElement('', value[0], value[value.length - 1] === 0 ||  (failedConstraints++, false))
+            return alertListElement('', value[0], value[2] === 0 ||  (failedConstraints++, false), value[3])
           }
         })
          $(document).ready(() => {
            $(".wl__feature-count--discrete").append(failedConstraints)
            $(".wl__feature-count--non-discrete").append(column.length - failedConstraints)
            $(".wl__feature-count--unknown").append(column.length)
          })
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-differenced-chart.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-differenced-chart.html`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-distribution-chart.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-distribution-chart.html`

 * *Files 4% similar despite different names*

```diff
@@ -274,21 +274,34 @@
               `)
             )
           }
 
         return data
       }
 
+      function verticalLine(column) {
+        const line_data = [];
+        if (column?.vertical_line) {
+            line_data.push({
+              axisX: column?.vertical_line || 0,
+            });
+
+        }
+
+        return line_data
+      }
+
       function generateDoubleHistogramChart(targetData, referenceData) {
         let histogramData = [],
             overlappedHistogramData = [];
         let yFormat;
 
         histogramData = chartData(targetData)
         overlappedHistogramData = chartData(referenceData)
+        lineData = verticalLine(targetData)
 
         const sizes = new GenerateChartParams($(window).height()-80, $(window).width(), histogramData, overlappedHistogramData)
         const {
           MARGIN,
           SVG_WIDTH,
           SVG_HEIGHT,
           CHART_WIDTH,
@@ -312,14 +325,37 @@
               .attr("stroke-opacity", 0.1))
           .call(g => g.append("text")
               .attr("x", -MARGIN.LEFT)
               .attr("y", 10)
               .attr("fill", "currentColor")
               .attr("text-anchor", "start"))
 
+        svgEl.append("line")
+          .attr("transform", `translate(${MARGIN.LEFT}, ${MARGIN.BOTTOM})`)
+          .data(lineData)
+          .attr("x1", (d) => xScale(d.axisX))
+          .attr("y1", MARGIN.TOP + MARGIN.TOP)
+          .attr("x2", (d) => xScale(d.axisX))
+          .attr("y2", CHART_HEIGHT + MARGIN.TOP)
+          .style("stroke-width", 2)
+          .style("stroke", "#44C0E7")
+          .style("stroke-dasharray", (3,3))
+          .style("fill", "none");
+
+        svgEl.append("text")
+          .attr("transform", "rotate(-90)")
+          .data(lineData)
+          .attr("y", (d) => xScale(d.axisX) + MARGIN.LEFT)
+          .attr("x", 0 - (SVG_HEIGHT / 2))
+          .attr("dy", "1em")
+          .style("text-anchor", "middle")
+          .text("single value")
+          .style("font-size", "15")
+          .style("opacity", "0.6")
+
         svgEl.append("text")
           .attr("transform",
                 "translate(" + (CHART_WIDTH/2) + " ," +
                                (CHART_HEIGHT + MARGIN.TOP + 75) + ")")
           .style("text-anchor", "middle")
           .text("Values")
           .style("font-size", "15")
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-feature-summary-statistics.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-feature-summary-statistics.html`

 * *Files 20% similar despite different names*

```diff
@@ -303,99 +303,119 @@
       function fixNumberTo(number, decimals = 3) {
         return parseFloat(number).toFixed(decimals);
       }
 
       Handlebars.registerHelper("variance", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.descriptive_statistics && feature.descriptive_statistics.variance) {
+        if (feature.descriptive_statistics && typeof feature.descriptive_statistics.variance === 'number') {
+          if (isNaN(feature.descriptive_statistics.variance)){return "-"}
+          if (feature.descriptive_statistics.variance==null){return "-"}
           return fixNumberTo(feature.descriptive_statistics.variance,2);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("coefficientOfVariation", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.descriptive_statistics && feature.descriptive_statistics.coefficient_of_variation) {
+        if (feature.descriptive_statistics && typeof feature.descriptive_statistics.coefficient_of_variation === 'number') {
+          if (isNaN(feature.descriptive_statistics.coefficient_of_variation)){return "-"}
+          if (feature.descriptive_statistics.coefficient_of_variation==null){return "-"}
           return fixNumberTo(feature.descriptive_statistics.coefficient_of_variation,2);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("median", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.quantile_statistics && feature.quantile_statistics.median) {
+        if (feature.quantile_statistics && typeof feature.quantile_statistics.median === 'number') {
+          if (isNaN(feature.quantile_statistics.median)){return "-"}
+          if (feature.quantile_statistics.median==null){return "-"}
           return fixNumberTo(feature.quantile_statistics.median);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("fifthPercentile", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.quantile_statistics && feature.quantile_statistics.fifth_percentile) {
+        if (feature.quantile_statistics && typeof feature.quantile_statistics.fifth_percentile === 'number') {
+          if (isNaN(feature.quantile_statistics.fifth_percentile)){return "-"}
+          if (feature.quantile_statistics.fifth_percentile==null){return "-"}
           return fixNumberTo(feature.quantile_statistics.fifth_percentile);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("ninetyFifthPercentile", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.quantile_statistics && feature.quantile_statistics.ninety_fifth_percentile) {
+        if (feature.quantile_statistics && typeof feature.quantile_statistics.ninety_fifth_percentile === 'number') {
+          if (isNaN(feature.quantile_statistics.ninety_fifth_percentile)){return "-"}
+          if (feature.quantile_statistics.ninety_fifth_percentile==null){return "-"}
           return fixNumberTo(feature.quantile_statistics.ninety_fifth_percentile);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("range", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.range) {
+        if (feature.range && typeof feature.range === 'number') {
+          if (isNaN(feature.range)){return "-"}
+          if (feature.range==null){return "-"}
           return fixNumberTo(feature.range);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("q3", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.quantile_statistics && feature.quantile_statistics.q3) {
+        if (feature.quantile_statistics && typeof feature.quantile_statistics.q3 === 'number') {
+          if (isNaN(feature.quantile_statistics.q3)){return "-"}
+          if (feature.quantile_statistics.q3==null){return "-"}
           return fixNumberTo(feature.quantile_statistics.q3);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("q1", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.quantile_statistics && feature.quantile_statistics.q1) {
+        if (feature.quantile_statistics && typeof feature.quantile_statistics.q1 === 'number') {
+          if (isNaN(feature.quantile_statistics.q1)){return "-"}
+          if (feature.quantile_statistics.q1==null){return "-"}
           return fixNumberTo(feature.quantile_statistics.q1);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("getSum", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.descriptive_statistics && feature.descriptive_statistics.sum) {
+        if (feature.descriptive_statistics && typeof feature.descriptive_statistics.sum === 'number') {
+          if (isNaN(feature.descriptive_statistics.sum)){return "-"}
+          if (feature.descriptive_statistics.sum==null){return "-"}
           return fixNumberTo(feature.descriptive_statistics.sum,2);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("iqr", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.quantile_statistics && feature.quantile_statistics.iqr) {
+        if (feature.quantile_statistics && typeof feature.quantile_statistics.iqr === 'number' ) {
+          if (isNaN(feature.quantile_statistics.iqr)){return "-"}
+          if (feature.quantile_statistics.iqr==null){return "-"}
           return fixNumberTo(feature.quantile_statistics.iqr);
         }
-        return "0";
+        return "-";
       });
 
 
       Handlebars.registerHelper("distinct", function (column) {
         const feature = Object.values(column)[0]
         const distinct_pct = feature.distinct
 
@@ -409,45 +429,52 @@
         }
         return "0";
       });
 
       Handlebars.registerHelper("mean", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.descriptive_statistics && feature.descriptive_statistics.mean) {
+        if (feature.descriptive_statistics && typeof feature.descriptive_statistics.mean === 'number') {
+          if (isNaN(feature.descriptive_statistics.mean)){return "-"}
+          if (feature.descriptive_statistics.mean==null){return "-"}
           return fixNumberTo(feature.descriptive_statistics.mean);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("stddev", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.descriptive_statistics && feature.descriptive_statistics.stddev) {
+        if (feature.descriptive_statistics && typeof feature.descriptive_statistics.stddev === 'number') {
+          if (isNaN(feature.descriptive_statistics.stddev)){return "-"}
+          if (feature.descriptive_statistics.stddev==null){return "-"}
           return fixNumberTo(feature.descriptive_statistics.stddev);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("minimum", function (column) {
         const feature = Object.values(column)[0]
-
-        if (feature.min) {
+        if (typeof feature.min === 'number') {
+          if (isNaN(feature.min)){return "-"}
+          if (feature.min==null){return "-"}
           return fixNumberTo(feature.min);
         }
-        return "0";
+        return "-";
       });
 
       Handlebars.registerHelper("maximum", function (column) {
         const feature = Object.values(column)[0]
 
-        if (feature.max) {
+        if (typeof feature.max === 'number') {
+          if (isNaN(feature.max)){return "-"}
+          if (feature.max==null){return "-"}
           return fixNumberTo(feature.max);
         }
-        return "0";
+        return "-";
       });
 
       // Handlebars.registerHelper("getProfileTimeStamp", function (column) {
       //   return formatLabelDate(+column.properties.dataTimestamp)
       // });
 
       // Handlebars.registerHelper("getProfileName", function (column) {
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in-jupyter-profile-summary.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in-for-jupyter-notebook.html`

 * *Files 12% similar despite different names*

```diff
@@ -164,15 +164,15 @@
       }
 
       .wl-table-head-wraper {
         background-color: var(--white);
       }
 
       .wl-table-head {
-        position: sticky;
+        position: relative;
         left: 0;
         min-width: 100px;
         border-bottom: 2px solid var(--brandSecondary100);
         font-size: 12px;
         line-height: 1.67;
         white-space: nowrap;
       }
@@ -182,15 +182,15 @@
       }
 
       .wl-table-body {
         display: table-row-group;
       }
 
       .wl-table-row .wl-table-cell:first-child{
-        position: sticky;
+        position: relative;
         left: 0;
         background-color: var(--white);
         border-right-width: 2px;
       }
 
       /* Table custom style */
 
@@ -227,17 +227,17 @@
         border-radius: 20px;
         white-space: nowrap;
       }
 
       /* Property side panel */
 
       .wl-compare-profile {
-        z-index: 999;
-        position: absolute;
-        right: 0;
+        position: relative;
+        left: 0;
+        padding: 18px;
         background: var(--white);;
         border-bottom: 1px solid var(--brandSecondary200);
       }
 
       /* Screen on smaller screens */
       .no-responsive {
         display: none;
@@ -579,15 +579,15 @@
         visibility: hidden;
         background: black;
         color: white;
         border: 1px solid black;
         text-align: start;
         padding: 3px;
         position: absolute;
-        z-index: 1;
+        z-index: 1002;
         top: 0;
         left: 100%;
         margin-left: 5px;
         opacity: 0;
         transition: opacity 0.5s;
         font-size: 13px;
         font-weight: normal;
@@ -659,153 +659,201 @@
         <div class="container-fluid">
           <div class="feature-summary-statistics-wrap">
             <div class="feature-summary-statistics">
               <div class="mb-4">
                   <strong class="header-title">Profile Summary</strong>
               </div>
               <div class="display-flex statistics">
-                <div class="padding-right-30">
-                  <div class="statistic-number-title">Observations</div>
-                  <div class="statistic-number">{{{observations this}}}</div>
-                </div>
-                <div class="padding-right-30">
-                  <div class="statistic-number-title">Missing Cells</div>
-                  <div class="statistic-number">
-                    {{{missingCells this}}}
-                    <div>{{{missingCellsPercentage this}}}</div>
-                  </div>
-                </div>
-                <div class="wl-compare-profile" id="compare-profile" style="display: flex; justify-content: space-around">
-                  <div class="drift-detection-wrap">
-                    <div class="drift-detection display-flex">
-                      <div class="drift-detection-search-input-wrap display-flex">
-                        <div class="drift-detection-search-input search-input ">
-                          <input type="text" id="wl__feature-search" placeholder="Quick search..."/>
-                          <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAGdSURBVHgBpZK7TkJBEIZnZoVocdTYyQNALxpNKPQBMEaNJsbCRMKhl8ISWwt6AaksCF5iTHgAGhJD4AHkAaAzGiwUsjvOQnO4SYh/cXbPzO43OxcEj9Zy92EiFSXNIfvPyE1kKFfdoxJMENpP6DrvLC0vJoEwCgwto7DWcxoIIHBYbA3NmKwnDltjAeuZhyul1DaTTlfPB6Nt5Z53DOgky4P875+nlctY2+unjZviLklkJhi5bPUa3y/7qJuQUM7PinMy7CdQc1Gh16vnBxPzrMROmlKQEgKNASAHLQCmSIGpS75O+O5pdQAgVXaIqTkNwDDXHmcnW3VmHZoGMLoTsOt88+NrAMCIZdu+iLTyTwKRa1Md6YKfOgXbzO7K8sWku5u5RxcRV5EpPezrzcHGbXEXWaUkgkweZ/UC9YrK3zqggFw5FBZfm8EUavHj7AjAKpIvBDrGn+pNnlcyhYgqbcC41idr1gvB4SdZkDbzQa21gwv0Vj07aPTtL07XdDOyDXohCDNoHIRmAVRie20f+RKybRDQDvxHkXy/7b/DrayncLbMwQAAAABJRU5ErkJggg=="/>
-                        </div>
-                        <div class="wl__dropdown_arrow-icon" >
-                          <div onclick="openFilter()" class="close-filter-button">
-                            <div class="display-flex close-filter-icon d-none">
-                              <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAALCAYAAACprHcmAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAADFSURBVHgBfY+xDcIwEEXvnLQBZQkYAEhDwwKpEEK0CCZgAEjJCEmgjYSAygxAHTZgFRSOsyUjY5mcZFnn/+78PwBXf3+MoKWUPuYjVBPFnTwpr9t/oNJfcTfXsAhRAlDqDhhQIPYgpAqNMDqcUqSAYZT1epr9gAHt6uXshvYme4DYHQJNDKh0dD0m5WXB10Y3Fqjtuh7fROn3oREDWxfeMLyRsMnc0OgDzdduaA0Pi3Plgr7Q2kaAePeBqh6rueSNBVt6fgCwBV1JLF3rlAAAAABJRU5ErkJggg=="/>
-                            </div>
-                            <div class="display-flex filter-icon">
-                              <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAPCAYAAADtc08vAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAACSSURBVHgBrZLBCYAwDEWTUjw7igcdwI1cxkNXUJzBEVzFAbSVKoKmaVrEB6GHJv/w+AACtRk7P9IONv1QOYUl96k0zv61m2tjARoLtSDI3EFsgIJ4uoXrMLazO72CRG2mzg/8BSdVlEjhpGZJjAWdAZJECpWalEhJSs1pHuUlMad5FFai1Lwg4Ckx1TxKIPFL8w55mEWd8VjPGAAAAABJRU5ErkJggg=="/>
-                            </div>
-                          </div>
-                          <span class="notif-circle-container">
-                            <span class="notif-circle"></span>
-                          </span>
-                        </div>
-                      </div>
+                  <div class="padding-right-30">
+                    <div class="statistic-number-title">Observations
+                    <div class="tooltip-full-number">
+                      <span class="question-mark">?</span>
+                    <span class="tooltiptext">
+                     <div class="mb-1">The sum of counts for each feature. For a single dataframe, it is equal to the number of cells, i.e., rows * columns.</div>
+                    </span>
                     </div>
-                  </div>
-                  <div class="dropdown-container flex-direction-colum mb-2 d-none" id="dropdown-container">
-                    <div class="filter-options">
-                      <div class="filter-options-title space-between dropdown">
-                        <p>Filter by type</p>
-                      </div>
-                      <div class="form-check mb-1 mt-2">
-                        <input
-                          class="form-check-input wl__feature-filter-input"
-                          type="checkbox"
-                          name="checkbox"
-                          value="Discrete"
-                          id="inferredDiscrete"
-                          onclick="changeDiscreteValue()"
-                          checked
-                        />
-                        <label class="form-check-label" for="inferredDiscrete">
-                          Inferred discrete (<span class="wl__feature-count--discrete">{{getDiscreteTypeCount}}</span>)
-                        </label>
-                      </div>
-                      <div class="form-check mb-1">
-                        <input
-                          class="form-check-input wl__feature-filter-input"
-                          type="checkbox"
-                          name="checkbox"
-                          value="Non-discrete"
-                          id="inferredNonDiscrete"
-                          onclick="changeNonDiscreteValue()"
-                          checked
-                        />
-                        <label class="form-check-label" for="inferredNonDiscrete">
-                          Inferred non-discrete (<span
-                            class="wl__feature-count--non-discrete"
-                          >{{getNonDiscreteTypeCount}}</span>)
-                        </label>
-                      </div>
-                      <div class="form-check mb-1">
-                        <input
-                          class="form-check-input wl__feature-filter-input"
-                          type="checkbox"
-                          name="checkbox"
-                          value="Unknown"
-                          id="inferredUnknown"
-                          onclick="changeUnknwonValue()"
-                          checked
-                        />
-                        <label class="form-check-label" for="inferredUnknown">
-                          Unknown (<span class="wl__feature-count--unknown">{{getUnknownTypeCount}}</span>)
-                        </label>
-                      </div>
                     </div>
+                    <div class="statistic-number">{{{observations this}}}</div>
+
                   </div>
+                  <div class="padding-right-30">
+                    <div class="statistic-number-title">Missing Cells</div>
+                    <div class="statistic-number">
+                      {{{missingCells this}}}
+                      <div>{{{missingCellsPercentage this}}}</div>
+                    </div>
                   </div>
+              </div>
             </div>
           </div>
           <div class="row">
             <div class="main">
+              <div class="wl-compare-profile" id="compare-profile">
+               <div class="drift-detection-wrap">
+                 <div class="drift-detection display-flex">
+                   <div class="drift-detection-info flex-direction-colum">
+                     <div class="drift-detection-info-title-wrap display-flex">
+                       <p class="drift-detection-info-title">
+                         Drift detected in
+                         <span class="drift-count"></span>
+                         of
+                         <span class="all-features"></span>
+                         features
+                       </p>
+                     </div>
+                     <div class="drift-detection-info-drifts display-flex" id="drift-detection-info-drifts">
+                     </div>
+                   </div>
+                   <div class="drift-detection-search-input-wrap display-flex">
+                     <div class="drift-detection-search-input search-input">
+                       <input type="text" id="wl__feature-search" placeholder="Quick search..."/>
+                       <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAGdSURBVHgBpZK7TkJBEIZnZoVocdTYyQNALxpNKPQBMEaNJsbCRMKhl8ISWwt6AaksCF5iTHgAGhJD4AHkAaAzGiwUsjvOQnO4SYh/cXbPzO43OxcEj9Zy92EiFSXNIfvPyE1kKFfdoxJMENpP6DrvLC0vJoEwCgwto7DWcxoIIHBYbA3NmKwnDltjAeuZhyul1DaTTlfPB6Nt5Z53DOgky4P875+nlctY2+unjZviLklkJhi5bPUa3y/7qJuQUM7PinMy7CdQc1Gh16vnBxPzrMROmlKQEgKNASAHLQCmSIGpS75O+O5pdQAgVXaIqTkNwDDXHmcnW3VmHZoGMLoTsOt88+NrAMCIZdu+iLTyTwKRa1Md6YKfOgXbzO7K8sWku5u5RxcRV5EpPezrzcHGbXEXWaUkgkweZ/UC9YrK3zqggFw5FBZfm8EUavHj7AjAKpIvBDrGn+pNnlcyhYgqbcC41idr1gvB4SdZkDbzQa21gwv0Vj07aPTtL07XdDOyDXohCDNoHIRmAVRie20f+RKybRDQDvxHkXy/7b/DrayncLbMwQAAAABJRU5ErkJggg=="/>
+                     </div>
+                     <div class="wl__dropdown_arrow-icon">
+                       <div onclick="openFilter()" class="close-filter-button">
+                         <div class="display-flex close-filter-icon d-none">
+                           <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAALCAYAAACprHcmAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAADFSURBVHgBfY+xDcIwEEXvnLQBZQkYAEhDwwKpEEK0CCZgAEjJCEmgjYSAygxAHTZgFRSOsyUjY5mcZFnn/+78PwBXf3+MoKWUPuYjVBPFnTwpr9t/oNJfcTfXsAhRAlDqDhhQIPYgpAqNMDqcUqSAYZT1epr9gAHt6uXshvYme4DYHQJNDKh0dD0m5WXB10Y3Fqjtuh7fROn3oREDWxfeMLyRsMnc0OgDzdduaA0Pi3Plgr7Q2kaAePeBqh6rueSNBVt6fgCwBV1JLF3rlAAAAABJRU5ErkJggg=="/>
+                         </div>
+                         <div class="display-flex filter-icon">
+                           <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAPCAYAAADtc08vAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAACSSURBVHgBrZLBCYAwDEWTUjw7igcdwI1cxkNXUJzBEVzFAbSVKoKmaVrEB6GHJv/w+AACtRk7P9IONv1QOYUl96k0zv61m2tjARoLtSDI3EFsgIJ4uoXrMLazO72CRG2mzg/8BSdVlEjhpGZJjAWdAZJECpWalEhJSs1pHuUlMad5FFai1Lwg4Ckx1TxKIPFL8w55mEWd8VjPGAAAAABJRU5ErkJggg=="/>
+                         </div>
+                       </div>
+                       <span class="notif-circle-container">
+                         <span class="notif-circle"></span>
+                       </span>
+                     </div>
+                   </div>
+                 </div>
+               </div>
+               <div class="dropdown-container flex-direction-colum mb-2 d-none" id="dropdown-container">
+                 <div class="filter-options">
+                   <div class="filter-options-title space-between dropdown">
+                     <p>Filter by type</p>
+                   </div>
+                   <div class="form-check mb-1 mt-2">
+                     <input
+                       class="form-check-input wl__feature-filter-input"
+                       type="checkbox"
+                       name="checkbox"
+                       value="Nodrift"
+                       id="nodrift"
+                       checked
+                     />
+                     <label class="form-check-label" for="nodrift">
+                       No evidence of drift (<span class="wl__feature-count--nodrift">{{getNoDriftCount}}</span>)
+                     </label>
+                   </div>
+                   <div class="form-check mb-1">
+                     <input
+                       class="form-check-input wl__feature-filter-input"
+                       type="checkbox"
+                       name="checkbox"
+                       value="Possibledrift"
+                       id="possibledrift"
+                       checked
+                     />
+                     <label class="form-check-label" for="possibledrift">
+                       Possible drift (<span
+                         class="wl__feature-count--possibledrift"
+                       >{{getPossibleDriftCount}}</span>)
+                     </label>
+                   </div>
+                   <div class="form-check mb-1">
+                     <input
+                       class="form-check-input wl__feature-filter-input"
+                       type="checkbox"
+                       name="checkbox"
+                       value="Detecteddrift"
+                       id="detecteddrift"
+                       checked
+                     />
+                     <label class="form-check-label" for="detecteddrift">
+                       Detected drift (<span class="wl__feature-count--drift">{{getDriftCount}}</span>)
+                     </label>
+                   </div>
+                   <div class="form-check mb-1">
+                    <input
+                      class="form-check-input wl__feature-filter-input"
+                      type="checkbox"
+                      name="checkbox"
+                      value="Unknowndrift"
+                      id="unknowndrift"
+                      checked
+                    />
+                    <label class="form-check-label" for="unknowndrift">
+                      Unknown (<span
+                        class="wl__feature-count--unknown"
+                      >{{getUnknownDriftCount}}</span>)
+                    </label>
+                  </div>
+
+                 </div>
+               </div>
+              </div>
               <div class="wl-table-wrap" id="table-content">
                 <div class="wl-table">
                   <div class="wl-table-heading">
                     <div class="wl-table-row wl-table-row--bottom-shadow">
                       <div class="wl-table-head wl-table-head-wraper">
                         <div class="wl-table-head table-border-none graph-table-head">Target</div>
+                        <div class="wl-table-head table-border-none reference-table-head">Reference</div>
+                      </div>
+                      <div class="wl-table-head wl-table-head-wraper text-align-center" style="cursor: pointer;" id="diff-from-ref">
+                        <div class="pvalue">Drift Score
+                          <div class="tooltip-full-number">
+                            <span class="question-mark">?</span>
+                          <span class="tooltiptext">
+                           <div class="mb-1">Drift is evaluated against pvalue, if present, and against statistic otherwise.</div>
+                          </span>
+                        </div>
+                        </div>
                       </div>
+                      <div class="wl-table-head wl-table-head-wraper text-align-end">Data Drift</div>
                       <div class="wl-table-head wl-table-head-wraper text-align-end">Total count</div>
-                      <div class="wl-table-head wl-table-head-wraper text-align-end">Missing</div>
-                      <div class="wl-table-head wl-table-head-wraper text-align-end">Mean</div>
-                      <div class="wl-table-head wl-table-head-wraper text-align-end">Min</div>
-                      <div class="wl-table-head wl-table-head-wraper text-align-end">Max</div>
-
                     </div>
                   </div>
                   <ul class="wl-table-body wl__table-body" id="table-body">
                     {{#each this.columns}}
                     <li
                     {{#if this.numberSummary}} class="wl-table-row wl-table-row--clickable" {{else}} class="wl-table-row" {{/if}}
                     data-feature-name={{@key}}
-                    data-inferred-type={{inferredType this}}
+                    data-drift-category={{driftCategory this}}
                     data-scroll-to-feature-name={{@key}}
+                    data-p-value={{getpvalue this}}
                   >
                       <div class="wl-table-cell wl-table-cell__graph-wrap">
                         <div class="wl-table-cell__title-wrap">
                           <h4 class="wl-table-cell__title">{{@key}}</h4>
                           <div></div>
                         </div>
                           <div class="display-flex">
                               {{{getGraphHtml this}}}
+                              {{{getReferenceGraphHtml this}}}
                           </div>
                       </div>
                       <div
+                        class="diff-from-ref-table-cell wl-table-cell wl-table-cell--top-spacing align-middle"
+                        style="max-width: 270px; padding-right: 18px"
+                      ><div class="wl-table-cell__bedge-wrap text-align-end">
+                           {{{getDiffFromRef this}}}
+                        </div></div><div
                         class="wl-table-cell wl-table-cell--top-spacing align-middle"
-                      ><div class="text-align-end">{{totalCount this}}</div></div>
-                      <div
-                        class="wl-table-cell wl-table-cell--top-spacing align-middle"
-                      ><div class="text-align-end">{{missing this}}</div></div>
-                      <div
-                        class="wl-table-cell wl-table-cell--top-spacing align-middle"
-                      ><div class="text-align-end">{{mean this}}</div></div>
-                      <div
-                        class="wl-table-cell wl-table-cell--top-spacing align-middle"
-                      ><div class="text-align-end">{{minimumValue this}}</div></div>
+                      ><div class="text-align-end">{{getDriftCategory this}}
+                        <div class="tooltip-full-number">
+                          <span class="question-mark">?</span>
+                        <span class="tooltiptext">
+                        <div class="mb-1"><pre class="mb-1">{{getThresholds this}}</pre></div>
+                        </span>
+                      </div>
+                      </div>
+
+                      </div>
                       <div
                         class="wl-table-cell wl-table-cell--top-spacing align-middle"
-                      ><div class="text-align-end">{{maximumValue this}}</div></div>
-
+                      ><div class="text-align-end">{{totalCount this}}</div></div>
                     </li>
                     {{/each}}
                   </ul>
                 </div>
               </div>
             </div>
           </div>
@@ -825,16 +873,16 @@
   </script>
 
   <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
 
   <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/6.7.0/d3.min.js" integrity="sha512-cd6CHE+XWDQ33ElJqsi0MdNte3S+bQY819f7p3NUHgwQQLXSKjE4cPZTeGNI+vaxZynk1wVU3hoHmow3m089wA==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
 
   <script>
-    const getTargetProfile = () => { return {{{profile_from_whylogs}}} }
-    const targetProfile = getTargetProfile()
+    const getReferenceProfile = () => { return {{{reference_profile_from_whylogs}}} }
+    const referenceProfile = getReferenceProfile()
 
     function fixNumberTo(number, decimals = 3) {
       const fractionalDigits = String(number % 1).split('').slice(2, 2 + decimals).join('')
       return `${Math.trunc(number)}.${fractionalDigits}`
     }
 
     function registerHandlebarHelperFunctions() {
@@ -966,14 +1014,56 @@
 
       function formatLabelDate(timestamp) {
         const date = new Date(timestamp);
         const format = d3.timeFormat("%Y-%m-%d %I:%M:%S %p %Z");
         return format(date);
       }
 
+      const driftCountElement = (driftCount, driftColor, driftName, driftRange) => `
+      <div class="display-flex flex-direction-column">
+        <div class="drift-detection-info-drifts-item display-flex align-items">
+          <div class="drift-detection-info-drifts-item-text display-flex align-items">
+            <p class="drift-detection-info-drifts-item-count mb-0">${driftCount}</p>
+            <p class="drift-detection-info-drifts-item-range display-flex justify-content-center mb-0">${driftRange}</p>
+          </div>
+        </div>
+      </div>
+      `
+
+      const drifts = {
+        severe: {
+          count: 0,
+          range: "with detected drift",
+        },
+        moderate: {
+          count: 0,
+          range: "with possible drift",
+        },
+        mild: {
+          count: 0,
+          range: "with no evidence of drift",
+        }
+      };
+
+      const countOfDrifts = (drift_from_ref, increment = true) => {
+        drift_class = drift_from_ref.drift_category
+        if (drift_class=="NO_DRIFT") {
+          if (increment){Object.values(drifts)[2].count++}
+          return 0
+        }
+        if (drift_class=="POSSIBLE_DRIFT") {
+          if (increment){Object.values(drifts)[1].count++}
+          return 1
+        }
+        if (drift_class=="DRIFT") {
+          if (increment){Object.values(drifts)[0].count++}
+          return 2
+        }
+      }
+
     abbreviate_number = function(value, fixed = 0) {
       value = +value
       if (value === null) { return null; } // terminate early
       if (value === 0) { return '0'; } // terminate early
       fixed = (!fixed || fixed < 0) ? 0 : fixed; // number of decimal places to show
       var b = (value).toPrecision(2).split("e"), // get power
           k = b.length === 1 ? 0 : Math.floor(Math.min(b[1].slice(1), 14) / 3), // floor at decimals, ceiling at trillions
@@ -1014,63 +1104,207 @@
              ${newNumber}
             <div class="statistic-measurement">${suffixe}</div>
           </div>
           <span class="tooltiptext">${number}</span>
         </div>`
 
      Handlebars.registerHelper("observations", function (properties) {
-       const {value, newValue, suffixe} = abbreviate_number(targetProfile.properties.observations)
+       const {value, newValue, suffixe} = abbreviate_number(referenceProfile.properties.observations)
        return numberWithSuffixe(value, valueNumber(newValue), valueNumber(suffixe));
      });
 
      Handlebars.registerHelper("missingCells", function (properties) {
-       const {value, newValue, suffixe} = abbreviate_number(targetProfile.properties.missing_cells)
+       const {value, newValue, suffixe} = abbreviate_number(referenceProfile.properties.missing_cells)
        if (typeof value !== 'undefined' && typeof newValue !== 'undefined'  && typeof suffixe !== 'undefined' ) {
         return numberWithSuffixe(value, valueSuffixe(`${newValue}`), suffixe);
        }
        return numberWithSuffixe(0, valueNumber(0), valueNumber(''));
      });
 
      Handlebars.registerHelper("missingCellsPercentage", function (properties) {
-       const {value, newValue, suffixe} = abbreviate_number(targetProfile.properties.missing_percentage)
+       const {value, newValue, suffixe} = abbreviate_number(referenceProfile.properties.missing_percentage)
        if (typeof value !== 'undefined' && typeof newValue !== 'undefined'  && typeof suffixe !== 'undefined' ) {
         return numberWithSuffixe(value, valueSuffixe(`(${newValue}%)`), suffixe);
        }
        return numberWithSuffixe(0, valueSuffixe(`(${0}%)`), '');
      });
 
      Handlebars.registerHelper("getProfileTimeStamp", function (properties) {
        return formatLabelDate(+properties.properties.dataTimestamp)
      });
 
      Handlebars.registerHelper("getProfileName", function (properties) {
        return properties.properties.tags.name
      });
 
+      let driftCount = 0;
+      const diffFromRefTableElement = (driftFromRefNumber, circleColor) => `
+         <div class="text-color padding-5 text-align-center justify-content-center">
+          <pre class="mb-1"> ${driftFromRefNumber} </pre>
+         </div>
+       `
+
        const cheqValueTypeNumber = (profile, profileValue) => {
          let validValue;
          if (profile && profileValue !== undefined && typeof profileValue === "number") {
            return true
          } else if (profileValue !== undefined && typeof profileValue !== "number") {
            return false
          }
        }
 
+       const cheqDriftFromRef = (profile, driftFromRef) => {
+        if (profile && driftFromRef){
+          console.log("drift from ref true")
+          return true
+        }
+        else {
+          console.log("drift from ref false")
+          return false
+        }
+       }
+
+       Handlebars.registerHelper("getpvalue", function (column, key) {
+        const columnKey = key.data.key
+        const {drift_from_ref} = referenceProfile.columns[columnKey]
+        if (cheqDriftFromRef(referenceProfile, drift_from_ref)){
+          if (cheqValueTypeNumber(referenceProfile, drift_from_ref.primary_value)) {
+          const driftFromRefNumber = drift_from_ref.primary_value.toPrecision(2)
+          return Number(driftFromRefNumber)
+
+        }
+        }
+        else {
+          return "-"
+        }
+      });
+
+
+      Handlebars.registerHelper("getDriftCategory", function (column, key) {
+        const columnKey = key.data.key
+        const {drift_from_ref} = referenceProfile.columns[columnKey]
+        const categories = {
+          0: "No evidence of drift",
+          1: "Possible drift",
+          2: "Detected drift"
+        }
+        if (cheqDriftFromRef(referenceProfile, drift_from_ref)){
+          if (cheqValueTypeNumber(referenceProfile, drift_from_ref.primary_value)) {
+            const driftFromRefNumber = drift_from_ref.primary_value.toPrecision(2)
+            const driftCategory = countOfDrifts(drift_from_ref, increment=false)
+            const circleColor = Object.values(drifts)[driftCategory].colorClass
+            return categories[driftCategory]
+
+          } else if (cheqValueTypeNumber(referenceProfile, drift_from_ref.primary_value) !== undefined) {
+            Object.values(drifts)[0].count++
+            return diffFromRefTableElement("undefined", "severe-drift-circle-color")
+          }
+        }
+        else {
+          return "Unknown"
+        }
+
+        return '<p style="color: black">-</p>';
+      });
+
+
+
+      Handlebars.registerHelper("getDiffFromRef", function (column, key) {
+        const columnKey = key.data.key
+        const {drift_from_ref} = referenceProfile.columns[columnKey]
+        if (drift_from_ref==null){
+          return diffFromRefTableElement("-", "")
+        }
+        if (cheqValueTypeNumber(referenceProfile, drift_from_ref.primary_value)) {
+          const driftFromRefNumber = drift_from_ref.primary_value.toPrecision(2)
+          const driftCategory = countOfDrifts(drift_from_ref)
+          const circleColor = Object.values(drifts)[driftCategory].colorClass
+          if (cheqValueTypeNumber(referenceProfile, drift_from_ref.pvalue)){
+            stats_string = `using algorithm: ${drift_from_ref.algorithm}\npvalue is: ${drift_from_ref.pvalue.toPrecision(3)}`
+          }
+          else {
+            stats_string = `using algorithm: ${drift_from_ref.algorithm}\nstatistic is: ${drift_from_ref.statistic.toPrecision(3)}`
+          }
+          if (driftCategory==1 || driftCategory == 2){
+            driftCount++
+          }
+          $(document).ready(() => {
+             $(".drift-count").html(driftCount)
+             $(".all-features").html(Object.keys(referenceProfile.columns).length)
+           })
+
+          return diffFromRefTableElement(stats_string, circleColor)
+
+        }
+        return '<p style="color: black">-</p>';
+      });
+
+
+      Handlebars.registerHelper("getThresholds", function (column, key) {
+        const columnKey = key.data.key
+        const {drift_from_ref} = referenceProfile.columns[columnKey]
+        if (drift_from_ref==null) {
+          return "-"
+        }
+        if (cheqValueTypeNumber(referenceProfile, drift_from_ref.primary_value)) {
+          thresholds_map = Object.entries(drift_from_ref.thresholds)
+          let thresholds_string = thresholds_map.map(([key, value]) => `${key}: ${value}`).join('\n')
+          return "thresholds:\n"+thresholds_string
+
+        }
+        return '<p style="color: black">-</p>';
+      });
+
+      $(document).ready(() =>
+        Object.values(drifts).map(({count, name, colorClass, range}) =>{
+          $("#drift-detection-info-drifts")
+          .append(driftCountElement(count, colorClass, name, range))
+        })
+      )
 
       Handlebars.registerHelper("inferredType", function (column) {
         let infferedType = "";
-
+        console.log(column)
         if (column.isDiscrete) {
           infferedType = "Discrete";
         } else {
           infferedType = "Non-discrete";
         }
         return infferedType;
       });
 
+      Handlebars.registerHelper("driftCategory", function (column, key) {
+        const columnKey = key.data.key
+        const {drift_from_ref} = referenceProfile.columns[columnKey]
+        if (drift_from_ref == null){
+          return "unknowndrift"
+        }
+        if (cheqValueTypeNumber(referenceProfile, drift_from_ref.primary_value)) {
+          console.log(drift_from_ref.drift_category)
+          console.log(Number(drift_from_ref.drift_category)==0)
+
+          if (drift_from_ref.drift_category=="NO_DRIFT"){
+            console.log("discrete")
+            return "nodrift"
+          }
+          if (drift_from_ref.drift_category=="POSSIBLE_DRIFT"){
+            console.log("non-discrete")
+            return "possibledrift"
+          }
+          if (drift_from_ref.drift_category=="DRIFT"){
+            console.log("unknown")
+            return "drift"
+          }
+
+          return Number(drift_from_ref.drift_category)
+
+        }
+      });
+
+
       Handlebars.registerHelper("frequentItems", function (column) {
         frequentItemsElemString = "";
         if (column.isDiscrete) {
           const slicedFrequentItems = column.frequentItems.items.slice(0, 5);
           for (let fi = 0; fi < slicedFrequentItems.length; fi++) {
             frequentItemsElemString +=
               '<span class="wl-table-cell__bedge">' + slicedFrequentItems[fi].jsonValue + "</span>";
@@ -1085,50 +1319,25 @@
         if (column.featureStats) {
           return column.featureStats.total_count;
         }
 
         return "-";
       });
 
-      Handlebars.registerHelper("missing", function (column) {
-        if (column.featureStats) {
-          return column.featureStats.missing;
-        }
-
-        return "-";
-      });
-
-      Handlebars.registerHelper("minimumValue", function (column) {
-        if (column.featureStats) {
-          if (isNaN(column.featureStats.min)){return "-"}
-          return fixNumberTo(column.featureStats.min);
-        }
-
-        return "-";
-      });
-
-      Handlebars.registerHelper("maximumValue", function (column) {
-        if (column.featureStats) {
-          if (isNaN(column.featureStats.max)){return "-"}
-          return fixNumberTo(column.featureStats.max);
-        }
-
-        return "-";
-      });
-
-
       Handlebars.registerHelper("mean", function (column) {
         if (column.featureStats?.descriptive_statistics) {
           if (isNaN(column.featureStats.descriptive_statistics.mean)){return "-"}
+          if (column.featureStats.descriptive_statistics.mean==null){return "-"}
           return fixNumberTo(column.featureStats.descriptive_statistics.mean);
         }
         return "-";
       });
 
       Handlebars.registerHelper("getGraphHtml",(column,key) => graph(column, key, null));
+      Handlebars.registerHelper("getReferenceGraphHtml",(column,key) => graph(column, key, referenceProfile));
 
       Handlebars.registerHelper("getDiscreteTypeCount", function () {
         let count = 0;
 
         Object.entries(this.columns).forEach((feature) => {
           if (feature[1].isDiscrete === true) {
             count++;
@@ -1136,22 +1345,85 @@
         });
         return count.toString();
       });
 
       Handlebars.registerHelper("getNonDiscreteTypeCount", function () {
         let count = 0;
 
-        Object.entries(this.columns).forEach((feature) => {
+        Object.entries(referenceProfile.columns).forEach((feature) => {
           if (feature[1].isDiscrete === false) {
             count++;
           }
         });
         return count;
       });
 
+      Handlebars.registerHelper("getDriftCount", function () {
+        let count = 0;
+
+        Object.entries(referenceProfile.columns).forEach((feature) => {
+          if (feature[1].drift_from_ref != null){
+            console.log("drif ref not null")
+            if (feature[1].drift_from_ref.drift_category == "DRIFT") {
+              count++;
+            }
+          }
+          else{
+            console.log("drift ref null")
+          }
+        });
+        return count;
+      });
+
+      Handlebars.registerHelper("getPossibleDriftCount", function () {
+        let count = 0;
+
+        Object.entries(referenceProfile.columns).forEach((feature) => {
+          if (feature[1].drift_from_ref != null){
+            console.log("drif ref not null")
+            if (feature[1].drift_from_ref.drift_category == "POSSIBLE_DRIFT") {
+              count++;
+            }
+          }
+          else{
+            console.log("drift ref null")
+          }
+        });
+        return count;
+      });
+
+
+      Handlebars.registerHelper("getNoDriftCount", function () {
+        let count = 0;
+        Object.entries(referenceProfile.columns).forEach((feature) => {
+          if (feature[1].drift_from_ref != null){
+            console.log("drif ref not null")
+            if (feature[1].drift_from_ref.drift_category == "NO_DRIFT") {
+              count++;
+            }
+          }
+          else{
+            console.log("drift ref null")
+          }
+        });
+        return count;
+      });
+
+      Handlebars.registerHelper("getUnknownDriftCount", function () {
+        let count = 0;
+        Object.entries(referenceProfile.columns).forEach((feature) => {
+          if (feature[1].drift_from_ref == null){
+            console.log("drif ref unknown")
+            count++;
+          }
+        });
+        return count;
+      });
+
+
       Handlebars.registerHelper("getUnknownTypeCount", function () {
         let count = 0;
         return count;
         Object.entries(this.columns).forEach((feature) => {
           if (!feature[1].isDiscrete) {
             count++;
           }
@@ -1170,24 +1442,34 @@
       const target = document.getElementById("generated-html");
       target.innerHTML = html;
     }
 
     function initWebsiteScripts() {
       const $featureSearch = document.getElementById("wl__feature-search");
       const $tableBody = document.getElementById("table-body");
-      const $discrete = document.getElementById("inferredDiscrete");
-      const $nonDiscrete = document.getElementById("inferredNonDiscrete");
-      const $unknown = document.getElementById("inferredUnknown");
+      const $noDrift = document.getElementById("nodrift");
+      const $possibleDrift = document.getElementById("possibledrift");
+      const $drift = document.getElementById("detecteddrift");
+      const $diffFromRef = document.getElementById("diff-from-ref");
+      const $unknownDrift = document.getElementById("unknowndrift");
 
       const activeTypes = {
-        discrete: true,
-        "non-discrete": true,
-        unknown: true,
+        nodrift: true,
+        possibledrift: true,
+        drift: true,
+        unknowndrift: true,
       };
 
+      var driftOrder = {
+        original: true,
+        descending: false,
+        ascending: false,
+      };
+      var originalColumnOrder;
+
       let searchString = "";
 
       function debounce(func, wait, immediate) {
         let timeout;
 
         return function () {
           const context = this;
@@ -1211,21 +1493,21 @@
         if (item === undefined) {
           $notifCircleContainer.removeClass("d-none")
         } else {
           $notifCircleContainer.addClass("d-none")
         }
       }
 
+
       function handleSearch() {
         const tableBodyChildren = $tableBody.children;
 
         for (let i = 0; i < tableBodyChildren.length; i++) {
-          const type = tableBodyChildren[i].dataset.inferredType.toLowerCase();
+          const type = tableBodyChildren[i].dataset.driftCategory.toLowerCase();
           const name = tableBodyChildren[i].dataset.featureName.toLowerCase();
-
           if (activeTypes[type] && name.startsWith(searchString)) {
             tableBodyChildren[i].style.display = "";
           } else {
             tableBodyChildren[i].style.display = "none";
           }
         }
       }
@@ -1234,46 +1516,70 @@
         "keyup",
         debounce((event) => {
           searchString = event.target.value.toLowerCase();
           handleSearch();
         }, 100),
       );
 
-      $discrete.addEventListener("change", (event) => {
+      $noDrift.addEventListener("change", (event) => {
         if (event.currentTarget.checked) {
-          activeTypes["discrete"] = true;
+          activeTypes["nodrift"] = true;
         } else {
-          activeTypes["discrete"] = false;
+          activeTypes["nodrift"] = false;
         }
         handleSearch();
         filterNotification()
       });
 
-      $nonDiscrete.addEventListener("change", (event) => {
+      $possibleDrift.addEventListener("change", (event) => {
         if (event.currentTarget.checked) {
-          activeTypes["non-discrete"] = true;
+          activeTypes["possibledrift"] = true;
         } else {
-          activeTypes["non-discrete"] = false;
+          activeTypes["possibledrift"] = false;
         }
         handleSearch();
         filterNotification()
       });
 
-      $unknown.addEventListener("change", (event) => {
+      $unknownDrift.addEventListener("change", (event) => {
         if (event.currentTarget.checked) {
-          activeTypes["unknown"] = true;
+          activeTypes["unknowndrift"] = true;
         } else {
-          activeTypes["unknown"] = false;
+          activeTypes["unknowndrift"] = false;
         }
         handleSearch();
         filterNotification()
       });
 
+      $drift.addEventListener("change", (event) => {
+        if (event.currentTarget.checked) {
+          activeTypes["drift"] = true;
+        } else {
+          activeTypes["drift"] = false;
+        }
+        handleSearch();
+        filterNotification()
+      });
 
-      $(".svg-container").css("padding-bottom", "27%")
+      function checkCurrentProfile(item, referenceItem) {
+        if (referenceProfile && Object.values(referenceProfile)) {
+          return referenceItem
+        } else {
+          return item
+        }
+      }
+
+      if(checkCurrentProfile(true, false)) {
+        $(".svg-container").css("padding-bottom", "27%")
+        $("#diff-from-ref").addClass("d-none")
+        $(".diff-from-ref-table-cell").addClass("d-none")
+      } else {
+        $("#diff-from-ref").removeClass("d-none")
+        $(".diff-from-ref-table-cell").removeClass("d-none")
+      }
     }
 
     function checkedBoxes() {
       const $boxes = $('input[name=checkbox]:checked');
       const $notifCircleContainer = $(".notif-circle-container")
 
       if ($boxes.length) {
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-cdn-all-in.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-cdn-all-in.html`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs-library-all-in.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs-library-all-in.html`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index-hbs.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index-hbs.html`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/html/templates/index.html` & `whylogs-1.2.0/whylogs/viz/html/templates/index.html`

 * *Files identical despite different names*

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/notebook_profile_viz.py` & `whylogs-1.2.0/whylogs/viz/notebook_profile_viz.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,29 @@
 import html
 import json
 import logging
 import os
-from typing import Any, Dict, Optional
+from typing import Any, Dict, List, Optional
 
 from IPython.core.display import HTML  # type: ignore
 
+import whylogs.viz.drift.column_drift_algorithms as column_drift_algorithms
 from whylogs.api.usage_stats import emit_usage
 from whylogs.core.configs import SummaryConfig
 from whylogs.core.constraints import Constraints
 from whylogs.core.view.dataset_profile_view import DatasetProfileView
 from whylogs.migration.uncompound import _uncompound_dataset_profile
 from whylogs.viz.enums.enums import PageSpec, PageSpecEnum
 from whylogs.viz.utils.frequent_items_calculations import zero_padding_frequent_items
 from whylogs.viz.utils.html_template_utils import _get_compiled_template
 from whylogs.viz.utils.profile_viz_calculations import (
     add_feature_statistics,
     frequent_items_from_view,
     generate_profile_summary,
-    generate_summaries,
+    generate_summaries_with_drift_score,
     histogram_from_view,
 )
 
 logger = logging.getLogger(__name__)
 emit_usage("visualizer")
 
 
@@ -90,26 +91,31 @@
 
         visualization = NotebookProfileVisualizer()
         visualization.set_profiles(target_profile_view=prof_view,reference_profile_view=prof_view_ref)
     """
 
     _ref_view: Optional[DatasetProfileView]
     _target_view: DatasetProfileView
+    _drift_map: Optional[Dict[str, column_drift_algorithms.ColumnDriftAlgorithm]] = None
 
     @staticmethod
     def _display(template: str, page_spec: PageSpec, height: Optional[str]) -> "HTML":
         if not height:
             height = page_spec.height
         iframe = f"""<div></div><iframe srcdoc="{html.escape(template)}" width=100% height={height}
         frameBorder=0></iframe>"""
         display = HTML(iframe)
         return display
 
     def _display_distribution_chart(
-        self, feature_name: str, difference: bool, cell_height: str = None, config: Optional[SummaryConfig] = None
+        self,
+        feature_name: str,
+        difference: bool,
+        cell_height: Optional[str] = None,
+        config: Optional[SummaryConfig] = None,
     ) -> Optional[HTML]:
         if config is None:
             config = SummaryConfig()
         if difference:
             page_spec = PageSpecEnum.DIFFERENCED_CHART.value
         else:
             page_spec = PageSpecEnum.DISTRIBUTION_CHART.value
@@ -156,15 +162,15 @@
             result = self._display(distribution_chart, page_spec, cell_height)
             return result
 
         else:
             logger.warning("This method has to get at least a target profile, with valid feature title")
             return None
 
-    def _display_histogram_chart(self, feature_name: str, cell_height: str = None) -> Optional[HTML]:
+    def _display_histogram_chart(self, feature_name: str, cell_height: Optional[str] = None) -> Optional[HTML]:
         page_spec = PageSpecEnum.DOUBLE_HISTOGRAM.value
         template = _get_compiled_template(page_spec.html)
         if self._target_view:
             target_features: Dict[str, Dict[str, Any]] = {feature_name: {}}
             ref_features: Dict[str, Dict[str, Any]] = {feature_name: {}}
 
             target_col_view = self._target_view.get_column(feature_name)
@@ -182,25 +188,64 @@
                 ref_histogram = target_histogram.copy()
                 ref_histogram["counts"] = [
                     0 for _ in ref_histogram["counts"]
                 ]  # To plot single profile, zero counts for non-existing profile.
 
             ref_features[feature_name]["histogram"] = ref_histogram
             target_features[feature_name]["histogram"] = target_histogram
+            if target_histogram["n"] == 1:
+                # in the degenerate case when the target is a single value, it will be hidden
+                # so here we draw a vertical line, using the max (which is the observed value)
+                target_features[feature_name]["vertical_line"] = target_histogram["max"]
             histogram_chart = template(
                 {
                     "profile_from_whylogs": json.dumps(target_features),
                     "reference_profile_from_whylogs": json.dumps(ref_features),
                 }
             )
             return self._display(histogram_chart, page_spec, height=cell_height)
         else:
             logger.warning("This method has to get at least a target profile, with valid feature title")
             return None
 
+    def add_drift_config(
+        self, column_names: List[str], algorithm: column_drift_algorithms.ColumnDriftAlgorithm
+    ) -> None:
+        """Add drift configuration.
+        The algorithms and thresholds added through this method will be used to calculate drift scores in the `summary_drift_report()` method.
+        If any drift configuration exists, the new configuration will overwrite the standard behavior when appliable.
+        If a column has multiple configurations defined, the last one defined will be used.
+
+        Parameters
+        ----------
+        config: DriftConfig, required
+            Drift configuration.
+
+        """
+        self._drift_map = {} if not self._drift_map else self._drift_map
+        if not isinstance(algorithm, column_drift_algorithms.ColumnDriftAlgorithm):
+            raise ValueError("Algorithm must be of class ColumnDriftAlgorithm.")
+        if not self._target_view or not self._ref_view:
+            logger.error("Set target and reference profiles before adding drift configuration.")
+            raise ValueError
+        if not algorithm:
+            raise ValueError("Drift algorithm cannot be None.")
+        if not column_names:
+            raise ValueError("Drift configuration must have at least one column name.")
+        if column_names:
+            for column_name in column_names:
+                if column_name not in self._target_view.get_columns().keys():
+                    raise ValueError(f"Column {column_name} not found in target profile.")
+                if column_name not in self._target_view.get_columns().keys():
+                    raise ValueError(f"Column {column_name} not found in reference profile.")
+        for column_name in column_names:
+            if column_name in self._drift_map:
+                logger.warning(f"Overwriting existing drift configuration for column {column_name}.")
+            self._drift_map[column_name] = algorithm
+
     def set_profiles(
         self, target_profile_view: DatasetProfileView, reference_profile_view: Optional[DatasetProfileView] = None
     ) -> None:
         """Set profiles for Visualization/Comparison.
 
         Drift calculation is done if both `target_profile` and `reference profile` are passed.
 
@@ -211,32 +256,34 @@
         reference_profile_view: DatasetProfileView, optional
             Reference, or baseline, profile to be compared against the target profile.
 
         """
         self._target_view = _uncompound_dataset_profile(target_profile_view) if target_profile_view else None
         self._ref_view = _uncompound_dataset_profile(reference_profile_view) if reference_profile_view else None
 
-    def profile_summary(self, cell_height: str = None) -> HTML:
+    def profile_summary(self, cell_height: Optional[str] = None) -> HTML:
         page_spec = PageSpecEnum.PROFILE_SUMMARY.value
         template = _get_compiled_template(page_spec.html)
 
         try:
             profile_summary = generate_profile_summary(self._target_view, config=None)
             rendered_template = template(profile_summary)
             return self._display(rendered_template, page_spec, cell_height)
         except ValueError as e:
             logger.error("This method has to get target Dataset Profile View")
             raise e
 
     def summary_drift_report(self, height: Optional[str] = None) -> HTML:
         """Generate drift report between target and reference profiles.
 
-        KS test is applied for continuous variables and ChiSquared test for categorical variables.
+        KS is calculated if distribution metrics exists for said column.
+        If not, Chi2 is calculated if frequent items, cardinality and count metric exists. If not, then no drift value is associated to the column.
         If feature is missing from any profile, it will not be included in the report.
         Both target_profile_view and reference_profile_view must be set previously with `set_profiles`.
+        If custom drift behavior is desired, use `add_drift_config` before calling this method.
 
         Parameters
         ----------
         height: str, optional
             Preferred height, in pixels, for in-notebook visualization. Example:
             `"1000px"`. (Default is None)
 
@@ -247,26 +294,35 @@
 
         Examples
         --------
 
         Generate Summary Drift Report (after setting profiles with `set_profiles`):
 
         .. code-block:: python
+            from whylogs.viz.drift.column_drift_algorithms import Hellinger, ChiSquare
+            from whylogs.viz import NotebookProfileVisualizer
+
+            visualization = NotebookProfileVisualizer()
+            visualization.set_profiles(target_profile_view=target_view, reference_profile_view=ref_view)
+
+            visualization.add_drift_config(column_names=["weight"], algorithm=Hellinger())
+            visualization.add_drift_config(column_names=["legs"], algorithm=ChiSquare())
 
             visualization.summary_drift_report()
 
         """
         if not self._target_view or not self._ref_view:
             logger.error("This method has to get both target and reference profiles")
             raise ValueError
-
         page_spec = PageSpecEnum.SUMMARY_REPORT.value
         template = _get_compiled_template(page_spec.html)
 
-        profiles_summary = generate_summaries(self._target_view, self._ref_view, config=None)
+        profiles_summary = generate_summaries_with_drift_score(
+            self._target_view, self._ref_view, config=None, drift_map=self._drift_map
+        )
         rendered_template = template(profiles_summary)
         summary_drift_report = self._display(rendered_template, page_spec, height)
         return summary_drift_report
 
     def double_histogram(self, feature_name: str, cell_height: Optional[str] = None) -> HTML:
         """Plot overlayed histograms for specified feature present in both `target_profile` and `reference_profile`.
 
@@ -357,15 +413,17 @@
         difference = True
         difference_distribution_chart = self._display_distribution_chart(feature_name, difference, cell_height)
         return difference_distribution_chart
 
     def constraints_report(self, constraints: Constraints, cell_height: Optional[str] = None) -> HTML:
         page_spec = PageSpecEnum.CONSTRAINTS_REPORT.value
         template = _get_compiled_template(page_spec.html)
-        rendered_template = template({"constraints_report": json.dumps(constraints.report())})
+        rendered_template = template(
+            {"constraints_report": json.dumps(constraints.generate_constraints_report(with_summary=True))}
+        )
         constraints_report = self._display(rendered_template, page_spec, cell_height)
         return constraints_report
 
     def feature_statistics(
         self, feature_name: str, profile: str = "reference", cell_height: Optional[str] = None
     ) -> HTML:
         """
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/utils/descriptive_stats.py` & `whylogs-1.2.0/whylogs/viz/utils/descriptive_stats.py`

 * *Files 5% similar despite different names*

```diff
@@ -29,15 +29,15 @@
     return total_count, count_n, count_missing
 
 
 def _get_dist_metrics_from_column_view(
     column_view: ColumnProfileView,
 ) -> Union[Tuple[None, None, None], Tuple[float, float, float]]:
     distribution_metric: Optional[DistributionMetric] = column_view.get_metric("distribution")
-    if distribution_metric is None:
+    if distribution_metric is None or distribution_metric.kll.value.is_empty():
         return None, None, None
     stddev = distribution_metric.stddev
     mean = distribution_metric.mean.value
     variance = distribution_metric.variance
     return stddev, mean, variance
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/utils/frequent_items_calculations.py` & `whylogs-1.2.0/whylogs/viz/utils/frequent_items_calculations.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,14 +30,16 @@
     if target_fi_metric is None:
         return None
 
     target_frequent_items = target_fi_metric.to_summary_dict(config)["frequent_strings"]
     target_cnt_metric = column_view.get_metric("counts")
     target_count = target_cnt_metric.n.value
     target_card_metric = column_view.get_metric("cardinality")
+    if not target_card_metric:
+        return None
     target_unique_count = int(target_card_metric.hll.value.get_estimate())
 
     target_frequent_stats: FrequentStats = {
         "frequent_items": get_frequent_items_estimate(target_frequent_items),
         "total_count": target_count,
         "unique_count": target_unique_count,
     }
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/utils/histogram_calculations.py` & `whylogs-1.2.0/whylogs/viz/utils/histogram_calculations.py`

 * *Files 11% similar despite different names*

```diff
@@ -2,20 +2,23 @@
 from typing import List, Optional
 
 from typing_extensions import TypedDict
 from whylogs_sketching import kll_doubles_sketch  # type: ignore
 
 from whylogs.core.metrics import DistributionMetric
 from whylogs.core.view.column_profile_view import ColumnProfileView
+from whylogs.viz.configs import HistogramConfig
 from whylogs.viz.utils import _calculate_bins
 
 logger = getLogger(__name__)
 
-MAX_HIST_BUCKETS = 30
-HIST_AVG_NUMBER_PER_BUCKET = 4.0
+
+MAX_HIST_BUCKETS = HistogramConfig().max_hist_buckets
+HIST_AVG_NUMBER_PER_BUCKET = HistogramConfig().hist_avg_number_per_bucket
+MIN_N_BUCKETS = HistogramConfig().min_n_buckets
 
 
 class HistogramSummary(TypedDict):
     start: float
     end: float
     width: float
     counts: List[int]
@@ -32,15 +35,18 @@
 
     target_kill = col_dist.kll.value
     target_histogram = _histogram_from_sketch(target_kill)
     return target_histogram
 
 
 def _histogram_from_sketch(
-    sketch: kll_doubles_sketch, max_buckets: int = None, avg_per_bucket: Optional[float] = None
+    sketch: kll_doubles_sketch,
+    max_buckets: Optional[int] = None,
+    avg_per_bucket: Optional[float] = None,
+    min_n_buckets: Optional[int] = None,
 ) -> HistogramSummary:
     """
     Generate a summary of a kll_floats_sketch, including a histogram
 
     Parameters
     ----------
     sketch : kll_floats_sketch
@@ -59,22 +65,24 @@
     start = sketch.get_min_value()
     max_val = sketch.get_max_value()
     end = max_val
     if max_buckets is None:
         max_buckets = MAX_HIST_BUCKETS
     if avg_per_bucket is None:
         avg_per_bucket = HIST_AVG_NUMBER_PER_BUCKET
+    if min_n_buckets is None:
+        min_n_buckets = MIN_N_BUCKETS
 
     if (n < 2) or (start == end):
         dx = abs(start) * 1e-7
         end = start + dx
         bins = [start, end]
         counts = [n]
     else:
-        bins, end = _calculate_bins(end, start, n, avg_per_bucket, max_buckets)
+        bins, end = _calculate_bins(end, start, n, avg_per_bucket, max_buckets, min_n_buckets)
         pmf = sketch.get_pmf(bins)
         counts = [round(p * n) for p in pmf]
         counts = counts[1:-1]
 
     histogram: HistogramSummary = {
         "start": start,
         "end": end,
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/utils/html_template_utils.py` & `whylogs-1.2.0/whylogs/viz/utils/html_template_utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,14 @@
     try:
         from pybars import Compiler  # type: ignore
     except ImportError as e:
         logger.debug(e, exc_info=True)
         logger.warning("Unable to load pybars; install pybars3 to load profile directly from the current session ")
         return lambda _: None  # returns a no-op lambda
 
-    with open(template_path, "r+t") as file_with_template:
+    with open(template_path, "rt") as file_with_template:
         source = file_with_template.read()
     return Compiler().compile(source)
 
 
 def get_compiled_template(template_name: str) -> "Callable":
     return _get_compiled_template(template_name=template_name)
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/utils/profile_viz_calculations.py` & `whylogs-1.2.0/whylogs/viz/utils/profile_viz_calculations.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,16 +1,17 @@
 import json
 from logging import getLogger
 from typing import Any, Dict, List, Optional, Union
 
 from typing_extensions import TypedDict
 
+import whylogs.viz.drift.column_drift_algorithms as column_drift_algorithms
 from whylogs.core.configs import SummaryConfig
 from whylogs.core.metrics import CardinalityMetric
-from whylogs.core.utils import get_distribution_metrics
+from whylogs.core.utils import deprecated, get_distribution_metrics
 from whylogs.core.view.column_profile_view import ColumnProfileView
 from whylogs.core.view.dataset_profile_view import DatasetProfileView
 from whylogs.extras.image_metric import ImageMetric
 from whylogs.viz.utils import (
     DescriptiveStatistics,
     QuantileStats,
     _calculate_descriptive_statistics,
@@ -91,15 +92,15 @@
     missing_cells: int
     missing_percentage: float
 
 
 class ColumnSummary(TypedDict):
     histogram: Optional[HistogramSummary]
     frequentItems: Optional[List[FrequentItemEstimate]]
-    drift_from_ref: Optional[float]
+    drift_from_ref: Optional[Dict[str, Any]]
     isDiscrete: Optional[bool]
     featureStats: Optional[FeatureStats]
 
 
 class DatasetSummary(TypedDict):
     columns: Dict[str, Optional[ColumnSummary]]
     properties: Optional[OverallStats]
@@ -151,14 +152,104 @@
 
 def is_image_compound_metric(col_view: ColumnProfileView) -> bool:
     if isinstance(col_view.get_metric("image"), ImageMetric):
         return True
     return False
 
 
+def generate_summaries_with_drift_score(
+    target_view: DatasetProfileView,
+    ref_view: Optional[DatasetProfileView],
+    config: Optional[SummaryConfig],
+    drift_map: Optional[Dict[str, column_drift_algorithms.ColumnDriftAlgorithm]] = None,
+) -> Optional[Dict[str, Any]]:
+    """Generate summaries for target and reference profiles, with drift calculations."""
+
+    if config is None:
+        config = SummaryConfig()
+
+    if not target_view or not ref_view:
+        raise ValueError("This method has to get both target and reference profiles")
+
+    overall_stats: OverallStats = add_overall_statistics(target_view)
+    drift_values = column_drift_algorithms.calculate_drift_scores(
+        target_view, ref_view, drift_map=drift_map, with_thresholds=True
+    )
+    target_col_views = target_view.get_columns()
+    ref_col_views = ref_view.get_columns()
+    ref_summary: DatasetSummary = {"columns": {}, "properties": overall_stats}
+    target_summary: DatasetSummary = {"columns": {}, "properties": None}
+    for target_col_name in target_col_views:
+        if target_col_name in ref_col_views and not is_image_compound_metric(target_col_views[target_col_name]):
+            target_column_summary: ColumnSummary = {
+                "histogram": None,
+                "frequentItems": None,
+                "drift_from_ref": None,
+                "isDiscrete": None,
+                "featureStats": None,
+            }
+            ref_column_summary: ColumnSummary = {
+                "histogram": None,
+                "frequentItems": None,
+                "drift_from_ref": None,
+                "isDiscrete": None,
+                "featureStats": None,
+            }
+
+            target_col_view = target_col_views[target_col_name]
+            ref_col_view = ref_col_views[target_col_name]
+            if not target_col_view or not ref_col_view:
+                continue
+
+            target_stats = add_feature_statistics(target_col_name, target_col_view)
+            target_column_summary["featureStats"] = target_stats[target_col_name]
+
+            if target_col_name in drift_values:
+                col_drift_value = drift_values[target_col_name]
+                if col_drift_value:
+                    ref_column_summary["drift_from_ref"] = col_drift_value
+                    if ref_column_summary["drift_from_ref"]:
+                        ref_column_summary["drift_from_ref"].update(
+                            {"primary_value": col_drift_value["pvalue"] or col_drift_value["statistic"]}
+                        )
+            target_dist = target_col_view.get_metric("distribution")
+            reference_dist = ref_col_view.get_metric("distribution")
+            if (
+                target_dist
+                and reference_dist
+                and not target_dist.kll.value.is_empty()
+                and not reference_dist.kll.value.is_empty()
+            ):
+                target_column_summary["isDiscrete"] = ref_column_summary["isDiscrete"] = False
+
+                target_histogram = histogram_from_view(target_col_view, target_col_name)
+                target_column_summary["histogram"] = target_histogram
+
+                ref_histogram = histogram_from_view(ref_col_view, target_col_name)
+                ref_column_summary["histogram"] = ref_histogram
+
+            elif target_col_view.get_metric("frequent_items") and ref_col_view.get_metric("frequent_items"):
+                target_column_summary["isDiscrete"] = ref_column_summary["isDiscrete"] = True
+
+                target_frequent_items = frequent_items_from_view(target_col_view, target_col_name, config)
+                target_column_summary["frequentItems"] = target_frequent_items
+
+                ref_frequent_items = frequent_items_from_view(ref_col_view, target_col_name, config)
+                ref_column_summary["frequentItems"] = ref_frequent_items
+            target_summary["columns"][target_col_name] = target_column_summary
+            ref_summary["columns"][target_col_name] = ref_column_summary
+
+    summaries = {
+        "profile_from_whylogs": json.dumps(target_summary),
+        "reference_profile_from_whylogs": json.dumps(ref_summary),
+    }
+    return summaries
+
+
+@deprecated(message="Please use generate_summaries_with_drift_score instead.")
 def generate_summaries(
     target_view: DatasetProfileView, ref_view: Optional[DatasetProfileView], config: Optional[SummaryConfig]
 ) -> Optional[Dict[str, Any]]:
     if config is None:
         config = SummaryConfig()
 
     if not target_view or not ref_view:
```

### Comparing `whylogs-1.1.9.dev0/whylogs/viz/utils/quantile_stats.py` & `whylogs-1.2.0/whylogs/viz/utils/quantile_stats.py`

 * *Files 4% similar despite different names*

```diff
@@ -44,24 +44,25 @@
         "ninety_fifth_percentile": quantiles[4],
     }
     return quantile_statistics
 
 
 def _resize_bins(start: float, end: float, min_interval: float, width: float, n_buckets: int) -> Tuple[int, float]:
     new_buckets = math.floor((end - start) / min_interval)
+    new_buckets = max(new_buckets, 1)
     logger.warning(
         f"A bin width of {width} won't work with values in range of [{start}, {end}] "
         f"because numbers closer to each other than {int(min_interval)} might not be distinct "
         "when passed as float32: avoiding bin edge collisions by resizing from: "
         f"{n_buckets} to: {new_buckets} histogram buckets in summary."
     )
-    n_buckets = max(new_buckets, 1)
-    width = (end - start) / n_buckets
-    logger.info(f"New bin width is: {width} across {n_buckets} buckets")
-    return n_buckets, width
+
+    width = (end - start) / new_buckets
+    logger.info(f"New bin width is: {width} across {new_buckets} buckets")
+    return new_buckets, width
 
 
 def _get_min_interval(abs_start: float, abs_end: float) -> float:
     """
     Figure out the floating point precision at the scale of the bin boundaries
     min_interval is the smallest difference between floats at this scale.
     """
@@ -69,23 +70,24 @@
     log_min_interval = math.floor(math.log2(max_magnitude)) - FLOAT_MANTISSA_BITS
     min_interval = math.pow(2, log_min_interval)
 
     return min_interval
 
 
 def _calculate_bins(
-    end: float, start: float, n: int, avg_per_bucket: float, max_buckets: int
+    end: float, start: float, n: int, avg_per_bucket: float, max_buckets: int, min_n_buckets: int = 2
 ) -> Tuple[List[float], float]:
     # Include the max value in the right-most bin
-    end += abs(end) * 1e-7
+    end += abs(end) * 1e-7 if end != 0 else 1e-7
     abs_end = abs(end)
     abs_start = abs(start)
 
     # Include the right edge in the bin edges
     n_buckets = min(math.ceil(n / avg_per_bucket), max_buckets)
+    n_buckets = max(n_buckets, min_n_buckets)
     width = (end - start) / n_buckets
 
     min_interval = _get_min_interval(abs_start, abs_end)
 
     # If the bin width is smaller than min_interval, we need bigger bins
     if width < min_interval:
         n_buckets, width = _resize_bins(start, end, min_interval, width, n_buckets)
```

