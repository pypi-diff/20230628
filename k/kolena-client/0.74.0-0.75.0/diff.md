# Comparing `tmp/kolena_client-0.74.0.tar.gz` & `tmp/kolena_client-0.75.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kolena_client-0.74.0.tar", max compression
+gzip compressed data, was "kolena_client-0.75.0.tar", max compression
```

## Comparing `kolena_client-0.74.0.tar` & `kolena_client-0.75.0.tar`

### file list

```diff
@@ -1,109 +1,111 @@
--rw-r--r--   0        0        0    11346 2023-06-20 20:05:45.838385 kolena_client-0.74.0/LICENSE
--rw-r--r--   0        0        0      556 2023-06-20 20:05:45.838385 kolena_client-0.74.0/LICENSE_HEADER
--rw-r--r--   0        0        0     2276 2023-06-20 20:05:45.838385 kolena_client-0.74.0/README.md
--rw-r--r--   0        0        0     1356 2023-06-20 20:12:54.023944 kolena_client-0.74.0/kolena/__init__.py
--rw-r--r--   0        0        0      579 2023-06-20 20:05:45.878385 kolena_client-0.74.0/kolena/_api/__init__.py
--rw-r--r--   0        0        0      579 2023-06-20 20:05:45.878385 kolena_client-0.74.0/kolena/_api/v1/__init__.py
--rw-r--r--   0        0        0     1737 2023-06-20 20:05:45.878385 kolena_client-0.74.0/kolena/_api/v1/batched_load.py
--rw-r--r--   0        0        0      878 2023-06-20 20:05:45.878385 kolena_client-0.74.0/kolena/_api/v1/client_log.py
--rw-r--r--   0        0        0     4153 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_api/v1/core.py
--rw-r--r--   0        0        0     5320 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_api/v1/detection.py
--rw-r--r--   0        0        0     7531 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_api/v1/fr.py
--rw-r--r--   0        0        0     5540 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_api/v1/generic.py
--rw-r--r--   0        0        0      778 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_api/v1/repository.py
--rw-r--r--   0        0        0      833 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_api/v1/token.py
--rw-r--r--   0        0        0      738 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_api/v1/workflow.py
--rw-r--r--   0        0        0      579 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_experimental/__init__.py
--rw-r--r--   0        0        0      579 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_experimental/object_detection/__init__.py
--rw-r--r--   0        0        0    10497 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_experimental/object_detection/utils.py
--rw-r--r--   0        0        0      579 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_extras/__init__.py
--rw-r--r--   0        0        0      676 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_extras/metrics/__init__.py
--rw-r--r--   0        0        0      783 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_extras/metrics/sklearn.py
--rw-r--r--   0        0        0      579 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/__init__.py
--rw-r--r--   0        0        0     1616 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/asset_path_mapper.py
--rw-r--r--   0        0        0     5313 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/batched_load.py
--rw-r--r--   0        0        0     5608 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/cli.py
--rw-r--r--   0        0        0      783 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/consts.py
--rw-r--r--   0        0        0      579 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/dataframes/__init__.py
--rw-r--r--   0        0        0     2826 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/dataframes/validators.py
--rw-r--r--   0        0        0     1952 2023-06-20 20:05:45.882385 kolena_client-0.74.0/kolena/_utils/datatypes.py
--rw-r--r--   0        0        0     3403 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/endpoints.py
--rw-r--r--   0        0        0     1690 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/frozen.py
--rw-r--r--   0        0        0     1183 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/geometry.py
--rw-r--r--   0        0        0     1087 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/inference_validators.py
--rw-r--r--   0        0        0     2990 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/instrumentation.py
--rw-r--r--   0        0        0     4970 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/krequests.py
--rw-r--r--   0        0        0     3507 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/log.py
--rw-r--r--   0        0        0     1003 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/repository.py
--rw-r--r--   0        0        0     2494 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/serde.py
--rw-r--r--   0        0        0      889 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/serializable.py
--rw-r--r--   0        0        0     5450 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/state.py
--rw-r--r--   0        0        0     1942 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/uninstantiable.py
--rw-r--r--   0        0        0      852 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/_utils/validators.py
--rw-r--r--   0        0        0     1272 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/__init__.py
--rw-r--r--   0        0        0     1475 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/metadata.py
--rw-r--r--   0        0        0     3512 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/model.py
--rw-r--r--   0        0        0     1213 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/multiclass/__init__.py
--rw-r--r--   0        0        0     3354 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/multiclass/_utils.py
--rw-r--r--   0        0        0    15698 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/multiclass/evaluator.py
--rw-r--r--   0        0        0     3573 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/multiclass/test_run.py
--rw-r--r--   0        0        0     3185 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/multiclass/workflow.py
--rw-r--r--   0        0        0     2694 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/test_case.py
--rw-r--r--   0        0        0     2372 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/test_config.py
--rw-r--r--   0        0        0     4480 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/test_image.py
--rw-r--r--   0        0        0     6013 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/test_run.py
--rw-r--r--   0        0        0     3180 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/classification/test_suite.py
--rw-r--r--   0        0        0     1477 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/__init__.py
--rw-r--r--   0        0        0     6819 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_datatypes.py
--rw-r--r--   0        0        0     1042 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/__init__.py
--rw-r--r--   0        0        0     1922 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/datatypes.py
--rw-r--r--   0        0        0      765 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/ground_truth.py
--rw-r--r--   0        0        0     1035 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/inference.py
--rw-r--r--   0        0        0     5470 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/metadata.py
--rw-r--r--   0        0        0     8851 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/model.py
--rw-r--r--   0        0        0    13920 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/test_case.py
--rw-r--r--   0        0        0     1201 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/test_config.py
--rw-r--r--   0        0        0     1761 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/test_image.py
--rw-r--r--   0        0        0    12390 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/test_run.py
--rw-r--r--   0        0        0    13600 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/_internal/test_suite.py
--rw-r--r--   0        0        0     5867 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/ground_truth.py
--rw-r--r--   0        0        0     5435 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/inference.py
--rw-r--r--   0        0        0     1460 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/metadata.py
--rw-r--r--   0        0        0     3210 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/model.py
--rw-r--r--   0        0        0     2387 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/test_case.py
--rw-r--r--   0        0        0     3199 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/test_config.py
--rw-r--r--   0        0        0     5967 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/test_image.py
--rw-r--r--   0        0        0     5405 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/test_run.py
--rw-r--r--   0        0        0     2854 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/detection/test_suite.py
--rw-r--r--   0        0        0     2681 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/errors.py
--rw-r--r--   0        0        0     1400 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/__init__.py
--rw-r--r--   0        0        0     2171 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/_utils.py
--rw-r--r--   0        0        0    20960 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/datatypes.py
--rw-r--r--   0        0        0    10130 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/model.py
--rw-r--r--   0        0        0    14750 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/test_case.py
--rw-r--r--   0        0        0    12237 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/test_images.py
--rw-r--r--   0        0        0    16943 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/test_run.py
--rw-r--r--   0        0        0    16125 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/fr/test_suite.py
--rw-r--r--   0        0        0     3880 2023-06-20 20:05:45.886385 kolena_client-0.74.0/kolena/initialize.py
--rw-r--r--   0        0        0     2439 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/__init__.py
--rw-r--r--   0        0        0    13877 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/_datatypes.py
--rw-r--r--   0        0        0     6281 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/_validators.py
--rw-r--r--   0        0        0    10397 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/annotation.py
--rw-r--r--   0        0        0     4926 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/asset.py
--rw-r--r--   0        0        0     3469 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/define_workflow.py
--rw-r--r--   0        0        0    13019 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/evaluator.py
--rw-r--r--   0        0        0    11232 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/evaluator_function.py
--rw-r--r--   0        0        0     4421 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/ground_truth.py
--rw-r--r--   0        0        0     4334 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/inference.py
--rw-r--r--   0        0        0     1103 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/metrics/__init__.py
--rw-r--r--   0        0        0     2528 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/metrics/_formula.py
--rw-r--r--   0        0        0    15527 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/metrics/_geometry.py
--rw-r--r--   0        0        0     8265 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/model.py
--rw-r--r--   0        0        0    10261 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/plot.py
--rw-r--r--   0        0        0    14301 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/test_case.py
--rw-r--r--   0        0        0    22734 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/test_run.py
--rw-r--r--   0        0        0    10564 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/test_sample.py
--rw-r--r--   0        0        0    15251 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/test_suite.py
--rw-r--r--   0        0        0     9419 2023-06-20 20:05:45.890385 kolena_client-0.74.0/kolena/workflow/workflow.py
--rw-r--r--   0        0        0     3042 2023-06-20 20:12:54.023944 kolena_client-0.74.0/pyproject.toml
--rw-r--r--   0        0        0     4658 1970-01-01 00:00:00.000000 kolena_client-0.74.0/PKG-INFO
+-rw-r--r--   0        0        0    11346 2023-06-28 00:31:50.503242 kolena_client-0.75.0/LICENSE
+-rw-r--r--   0        0        0      556 2023-06-28 00:31:50.503242 kolena_client-0.75.0/LICENSE_HEADER
+-rw-r--r--   0        0        0     2293 2023-06-28 00:31:50.503242 kolena_client-0.75.0/README.md
+-rw-r--r--   0        0        0     1356 2023-06-28 00:37:17.961604 kolena_client-0.75.0/kolena/__init__.py
+-rw-r--r--   0        0        0      579 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/__init__.py
+-rw-r--r--   0        0        0      579 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/__init__.py
+-rw-r--r--   0        0        0     1737 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/batched_load.py
+-rw-r--r--   0        0        0      878 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/client_log.py
+-rw-r--r--   0        0        0     5111 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/core.py
+-rw-r--r--   0        0        0     5320 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/detection.py
+-rw-r--r--   0        0        0     7531 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/fr.py
+-rw-r--r--   0        0        0     5597 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/generic.py
+-rw-r--r--   0        0        0      778 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/repository.py
+-rw-r--r--   0        0        0      833 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/token.py
+-rw-r--r--   0        0        0      738 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_api/v1/workflow.py
+-rw-r--r--   0        0        0      579 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_experimental/__init__.py
+-rw-r--r--   0        0        0     1052 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_experimental/object_detection/__init__.py
+-rw-r--r--   0        0        0    16345 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_experimental/object_detection/evaluator.py
+-rw-r--r--   0        0        0    13671 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_experimental/object_detection/utils.py
+-rw-r--r--   0        0        0     4297 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_experimental/object_detection/workflow.py
+-rw-r--r--   0        0        0      579 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_extras/__init__.py
+-rw-r--r--   0        0        0      676 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_extras/metrics/__init__.py
+-rw-r--r--   0        0        0      783 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_extras/metrics/sklearn.py
+-rw-r--r--   0        0        0      579 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_utils/__init__.py
+-rw-r--r--   0        0        0     1616 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_utils/asset_path_mapper.py
+-rw-r--r--   0        0        0     5313 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_utils/batched_load.py
+-rw-r--r--   0        0        0     5608 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_utils/cli.py
+-rw-r--r--   0        0        0      783 2023-06-28 00:31:50.555243 kolena_client-0.75.0/kolena/_utils/consts.py
+-rw-r--r--   0        0        0      579 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/dataframes/__init__.py
+-rw-r--r--   0        0        0     2826 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/dataframes/validators.py
+-rw-r--r--   0        0        0     1952 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/datatypes.py
+-rw-r--r--   0        0        0     3403 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/endpoints.py
+-rw-r--r--   0        0        0     1690 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/frozen.py
+-rw-r--r--   0        0        0     1183 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/geometry.py
+-rw-r--r--   0        0        0     1087 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/inference_validators.py
+-rw-r--r--   0        0        0     2990 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/instrumentation.py
+-rw-r--r--   0        0        0     5033 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/krequests.py
+-rw-r--r--   0        0        0     3507 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/log.py
+-rw-r--r--   0        0        0     1003 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/repository.py
+-rw-r--r--   0        0        0     2494 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/serde.py
+-rw-r--r--   0        0        0      889 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/serializable.py
+-rw-r--r--   0        0        0     5450 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/state.py
+-rw-r--r--   0        0        0     1942 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/uninstantiable.py
+-rw-r--r--   0        0        0      852 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/_utils/validators.py
+-rw-r--r--   0        0        0     1272 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/__init__.py
+-rw-r--r--   0        0        0     1475 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/metadata.py
+-rw-r--r--   0        0        0     3512 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/model.py
+-rw-r--r--   0        0        0     1213 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/multiclass/__init__.py
+-rw-r--r--   0        0        0     3354 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/multiclass/_utils.py
+-rw-r--r--   0        0        0    15698 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/multiclass/evaluator.py
+-rw-r--r--   0        0        0     3573 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/multiclass/test_run.py
+-rw-r--r--   0        0        0     3185 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/multiclass/workflow.py
+-rw-r--r--   0        0        0     2694 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/test_case.py
+-rw-r--r--   0        0        0     2372 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/test_config.py
+-rw-r--r--   0        0        0     4480 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/test_image.py
+-rw-r--r--   0        0        0     6013 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/test_run.py
+-rw-r--r--   0        0        0     3180 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/classification/test_suite.py
+-rw-r--r--   0        0        0     1477 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/__init__.py
+-rw-r--r--   0        0        0     6819 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_datatypes.py
+-rw-r--r--   0        0        0     1042 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/__init__.py
+-rw-r--r--   0        0        0     1922 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/datatypes.py
+-rw-r--r--   0        0        0      765 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/ground_truth.py
+-rw-r--r--   0        0        0     1035 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/inference.py
+-rw-r--r--   0        0        0     5470 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/metadata.py
+-rw-r--r--   0        0        0     8851 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/model.py
+-rw-r--r--   0        0        0    13920 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/test_case.py
+-rw-r--r--   0        0        0     1201 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/test_config.py
+-rw-r--r--   0        0        0     1761 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/test_image.py
+-rw-r--r--   0        0        0    12390 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/test_run.py
+-rw-r--r--   0        0        0    13600 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/_internal/test_suite.py
+-rw-r--r--   0        0        0     5867 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/ground_truth.py
+-rw-r--r--   0        0        0     5435 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/inference.py
+-rw-r--r--   0        0        0     1460 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/metadata.py
+-rw-r--r--   0        0        0     3210 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/model.py
+-rw-r--r--   0        0        0     2387 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/test_case.py
+-rw-r--r--   0        0        0     3199 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/test_config.py
+-rw-r--r--   0        0        0     5967 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/test_image.py
+-rw-r--r--   0        0        0     5405 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/test_run.py
+-rw-r--r--   0        0        0     2854 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/detection/test_suite.py
+-rw-r--r--   0        0        0     2681 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/errors.py
+-rw-r--r--   0        0        0     1400 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/__init__.py
+-rw-r--r--   0        0        0     2171 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/_utils.py
+-rw-r--r--   0        0        0    20960 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/datatypes.py
+-rw-r--r--   0        0        0    10130 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/model.py
+-rw-r--r--   0        0        0    14750 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/test_case.py
+-rw-r--r--   0        0        0    12237 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/test_images.py
+-rw-r--r--   0        0        0    16943 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/test_run.py
+-rw-r--r--   0        0        0    16125 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/fr/test_suite.py
+-rw-r--r--   0        0        0     3880 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/initialize.py
+-rw-r--r--   0        0        0     2439 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/__init__.py
+-rw-r--r--   0        0        0    13948 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/_datatypes.py
+-rw-r--r--   0        0        0     6281 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/_validators.py
+-rw-r--r--   0        0        0    10397 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/annotation.py
+-rw-r--r--   0        0        0     4926 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/asset.py
+-rw-r--r--   0        0        0     3469 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/define_workflow.py
+-rw-r--r--   0        0        0    13854 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/evaluator.py
+-rw-r--r--   0        0        0    11232 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/evaluator_function.py
+-rw-r--r--   0        0        0     4421 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/ground_truth.py
+-rw-r--r--   0        0        0     4334 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/inference.py
+-rw-r--r--   0        0        0     1103 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/metrics/__init__.py
+-rw-r--r--   0        0        0     2977 2023-06-28 00:31:50.559243 kolena_client-0.75.0/kolena/workflow/metrics/_formula.py
+-rw-r--r--   0        0        0    16014 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/metrics/_geometry.py
+-rw-r--r--   0        0        0     8265 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/model.py
+-rw-r--r--   0        0        0    10261 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/plot.py
+-rw-r--r--   0        0        0    18116 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/test_case.py
+-rw-r--r--   0        0        0    22734 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/test_run.py
+-rw-r--r--   0        0        0    10564 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/test_sample.py
+-rw-r--r--   0        0        0    15251 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/test_suite.py
+-rw-r--r--   0        0        0     9419 2023-06-28 00:31:50.563243 kolena_client-0.75.0/kolena/workflow/workflow.py
+-rw-r--r--   0        0        0     3042 2023-06-28 00:37:17.961604 kolena_client-0.75.0/pyproject.toml
+-rw-r--r--   0        0        0     4675 1970-01-01 00:00:00.000000 kolena_client-0.75.0/PKG-INFO
```

### Comparing `kolena_client-0.74.0/LICENSE` & `kolena_client-0.75.0/LICENSE`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/LICENSE_HEADER` & `kolena_client-0.75.0/LICENSE_HEADER`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/README.md` & `kolena_client-0.75.0/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 <p align="center">
-  <img src="/docs/assets/images/wordmark-violet.svg" width="400" alt="Kolena" />
+  <img src="https://docs.kolena.io/assets/images/wordmark-violet.svg" width="400" alt="Kolena" />
 </p>
 
 <p align='center'>
   <a href="https://pypi.python.org/pypi/kolena"><img src="https://img.shields.io/pypi/v/kolena" /></a>
   <a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/pypi/l/kolena" /></a>
   <a href="https://github.com/kolenaIO/kolena/actions"><img src="https://img.shields.io/github/checks-status/kolenaIO/kolena/trunk" /></a>
   <a href="https://codecov.io/gh/kolenaIO/kolena" ><img src="https://codecov.io/gh/kolenaIO/kolena/branch/trunk/graph/badge.svg?token=8WOY5I8SF1"/></a>
```

### Comparing `kolena_client-0.74.0/kolena/__init__.py` & `kolena_client-0.75.0/kolena/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/__init__.py` & `kolena_client-0.75.0/kolena/_api/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/__init__.py` & `kolena_client-0.75.0/kolena/_api/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/batched_load.py` & `kolena_client-0.75.0/kolena/_api/v1/batched_load.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/client_log.py` & `kolena_client-0.75.0/kolena/_api/v1/client_log.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/core.py` & `kolena_client-0.75.0/kolena/_api/v1/core.py`

 * *Files 25% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 #    http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
+from enum import Enum
 from typing import Any
 from typing import Dict
 from typing import List
 from typing import Optional
 
 from pydantic.dataclasses import dataclass
 
@@ -50,22 +51,48 @@
     name: str
     sample_count: int
     # provided by stratification preview to show what bucket this test-case falls into,
     # e.g. {"count": "low", "gender": "female"}. This info is not available from stratification result.
     membership: Optional[Dict[str, str]] = None
 
 
+class BulkProcessStatus(Enum):
+    CREATED = "created"
+    LOADED = "loaded"
+    EDITED = "edited"
+
+
 class TestCase:
     @dataclass(frozen=True)
     class CreateRequest:
         name: str
         description: str
         workflow: str
 
     @dataclass(frozen=True)
+    class SingleProcessRequest:
+        name: str
+        reset: bool = False
+
+    @dataclass(frozen=True)
+    class SingleProcessResponse:
+        data: "TestCase.EntityData"
+        status: BulkProcessStatus
+
+    @dataclass(frozen=True)
+    class BulkProcessRequest:
+        test_cases: List["TestCase.SingleProcessRequest"]
+        workflow: str
+        uuid: Optional[str] = None
+
+    @dataclass(frozen=True)
+    class BulkProcessResponse:
+        test_cases: List["TestCase.SingleProcessResponse"]
+
+    @dataclass(frozen=True)
     class CreateFromExistingRequest(BatchedLoad.WithLoadUUID):
         test_case_name: str
         test_suite_name: str
         workflow: str
         compute_metrics_where_possible: bool = False
         compute_metrics_models: Optional[List[int]] = None
 
@@ -103,14 +130,19 @@
         reset: bool = False
 
     @dataclass(frozen=True)
     class CompleteEditRequest(EditRequest, BatchedLoad.WithLoadUUID):
         ...
 
 
+TestCase.SingleProcessResponse.__pydantic_model__.update_forward_refs()  # type: ignore[attr-defined]
+TestCase.BulkProcessRequest.__pydantic_model__.update_forward_refs()  # type: ignore[attr-defined]
+TestCase.BulkProcessResponse.__pydantic_model__.update_forward_refs()  # type: ignore[attr-defined]
+
+
 class TestSuite:
     @dataclass(frozen=True)
     class CreateRequest:
         name: str
         description: str
         workflow: str
         tags: Optional[List[str]] = None
```

### Comparing `kolena_client-0.74.0/kolena/_api/v1/detection.py` & `kolena_client-0.75.0/kolena/_api/v1/detection.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/fr.py` & `kolena_client-0.75.0/kolena/_api/v1/fr.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/generic.py` & `kolena_client-0.75.0/kolena/_api/v1/generic.py`

 * *Files 2% similar despite different names*

```diff
@@ -37,14 +37,15 @@
 
 class TestCase:
     class Path(str, Enum):
         CREATE = "/generic/test-case/create"
         LOAD = "/generic/test-case/load"
         INIT_LOAD_TEST_SAMPLES = "/generic/test-case/load-test-samples"
         COMPLETE_EDIT = "/generic/test-case/edit"
+        BULK_PROCESS = "/generic/test-case/bulk-process"
 
 
 class TestSuite:
     class Path(str, Enum):
         CREATE = "/generic/test-suite/create"
         LOAD = "/generic/test-suite/load"
         LOAD_ALL = "/generic/test-suite/load-all"
```

### Comparing `kolena_client-0.74.0/kolena/_api/v1/repository.py` & `kolena_client-0.75.0/kolena/_api/v1/repository.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/token.py` & `kolena_client-0.75.0/kolena/_api/v1/token.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_api/v1/workflow.py` & `kolena_client-0.75.0/kolena/_api/v1/workflow.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_experimental/__init__.py` & `kolena_client-0.75.0/kolena/_experimental/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_experimental/object_detection/__init__.py` & `kolena_client-0.75.0/kolena/_extras/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_experimental/object_detection/utils.py` & `kolena_client-0.75.0/kolena/_experimental/object_detection/utils.py`

 * *Files 27% similar despite different names*

```diff
@@ -52,21 +52,23 @@
             y_score.append(bbox_inf.score)
     return np.array(y_true), np.array(y_score)
 
 
 def _compute_threshold_curve(
     y_true: np.ndarray,
     y_score: np.ndarray,
-    curve: Literal["pr", "f1"],
+    curve_type: Literal["pr", "f1"],
     curve_label: Optional[str] = None,
 ) -> Optional[Curve]:
     if len(y_score) >= 501:
         thresholds = list(np.linspace(min(abs(y_score)), max(y_score), 501))
-    else:
+    elif len(y_score) > 1:
         thresholds = np.unique(y_score[y_score >= 0.0]).tolist()  # sorts
+    else:
+        return None
 
     precisions: List[float] = []
     recalls: List[float] = []
     f1s: List[float] = []
     for threshold in thresholds:
         y_pred = [1 if score >= threshold else 0 for score in y_score]
         precision, recall, f1, _ = sklearn_metrics.precision_recall_fscore_support(
@@ -80,66 +82,155 @@
         recalls.append(recall)
         f1s.append(f1)
 
     # Omit curves with only one point
     if len(f1s) < 2:
         return None
 
-    if curve == "f1":
+    if curve_type == "f1":
         return Curve(x=thresholds, y=f1s, label=curve_label)
     else:
         return Curve(x=recalls, y=precisions, label=curve_label)
 
 
+def _compute_multiclass_curves(
+    all_matches: List[MulticlassInferenceMatches],
+    curve_type: Literal["pr", "f1"],
+    curve_label: Optional[str] = None,
+) -> Optional[List[Curve]]:
+    curves: List[Curve] = []
+    y_true, y_score = _compute_sklearn_arrays(all_matches)
+    y_true_score_by_label = _compute_sklearn_arrays_by_class(all_matches)
+    curve = _compute_threshold_curve(y_true, y_score, curve_type, curve_label)
+    if curve is None:
+        return None
+    curves.append(curve)
+
+    for label, (y_true, y_score) in sorted(y_true_score_by_label.items(), key=lambda x: x[0]):
+        curve = _compute_threshold_curve(y_true, y_score, curve_type, label)
+        if curve is not None:
+            curves.append(curve)
+    return curves if curves else None
+
+
+def compute_pr_curve(
+    all_matches: List[Union[MulticlassInferenceMatches, InferenceMatches]],
+    curve_label: Optional[str] = None,
+) -> Optional[Curve]:
+    """
+    Creates a PR (precision and recall) curve.
+
+    :param all_matches: A list of multiclass or singleclass matching results.
+    :param curve_label: The label of the curve.
+    :return: :class:`Curve` for the PR curve.
+    """
+    y_true, y_score = _compute_sklearn_arrays(all_matches)
+    return _compute_threshold_curve(y_true, y_score, "pr", curve_label)
+
+
 def compute_pr_plot(
     all_matches: List[Union[MulticlassInferenceMatches, InferenceMatches]],
     curve_label: Optional[str] = None,
 ) -> Optional[CurvePlot]:
     """
     Creates a PR (precision and recall) plot.
 
     :param all_matches: A list of multiclass or singleclass matching results.
     :param curve_label: The label of the curve.
     :return: :class:`CurvePlot` for the PR curve.
     """
-    y_true, y_score = _compute_sklearn_arrays(all_matches)
-    curve = _compute_threshold_curve(y_true, y_score, "pr", curve_label)
+    curve = compute_pr_curve(all_matches, curve_label)
 
-    if curve is None:
-        return None
+    return (
+        CurvePlot(
+            title="Precision vs. Recall",
+            x_label="Recall",
+            y_label="Precision",
+            curves=[curve],
+        )
+        if curve
+        else None
+    )
+
+
+def compute_pr_plot_multiclass(
+    all_matches: List[MulticlassInferenceMatches],
+    curve_label: Optional[str] = None,
+) -> Optional[CurvePlot]:
+    """
+    Creates a PR (precision-recall) curve for the multiclass object detection workflow.
+    For `n` labels, each plot has `n+1` curves. One for the test case, and one per label.
 
-    return CurvePlot(
-        title="Precision vs. Recall",
-        x_label="Recall",
-        y_label="Precision",
-        curves=[curve],
+    :param all_matches: a list of multiclass matching results.
+    :param curve_label: the label of the main curve.
+    :return: :class:`CurvePlot` for the PR curves of the test case and each label.
+    """
+    pr_curves: Optional[List[Curve]] = _compute_multiclass_curves(all_matches, "pr", curve_label)
+
+    return (
+        CurvePlot(
+            title="Precision vs. Recall Per Class",
+            x_label="Recall",
+            y_label="Precision",
+            curves=pr_curves,
+        )
+        if pr_curves
+        else None
     )
 
 
 def compute_f1_plot(
     all_matches: List[Union[MulticlassInferenceMatches, InferenceMatches]],
     curve_label: Optional[str] = None,
-) -> CurvePlot:
+) -> Optional[CurvePlot]:
     """
     Creates a F1-threshold (confidence threshold) plot.
 
     :param all_matches: A list of multiclass or singleclass matching results.
     :param curve_label: The label of the curve.
     :return: :class:`CurvePlot` for the F1-threshold curve.
     """
     y_true, y_score = _compute_sklearn_arrays(all_matches)
     curve = _compute_threshold_curve(y_true, y_score, "f1", curve_label)
-    if curve is None:
-        return None
 
-    return CurvePlot(
-        title="F1-Score vs. Confidence Threshold",
-        x_label="Confidence Threshold",
-        y_label="F1-Score",
-        curves=[curve],
+    return (
+        CurvePlot(
+            title="F1-Score vs. Confidence Threshold",
+            x_label="Confidence Threshold",
+            y_label="F1-Score",
+            curves=[curve],
+        )
+        if curve
+        else None
+    )
+
+
+def compute_f1_plot_multiclass(
+    all_matches: List[MulticlassInferenceMatches],
+    curve_label: Optional[str] = None,
+) -> Optional[CurvePlot]:
+    """
+    Creates a F1-threshold (confidence threshold) curve for the multiclass object detection workflow.
+    For `n` labels, each plot has `n+1` curves. One for the test case, and one per label.
+
+    :param all_matches: a list of multiclass matching results.
+    :param curve_label: the label of the main curve.
+    :return: :class:`CurvePlot` for the F1-threshold curves of the test case and each label.
+    """
+    f1_curves: Optional[List[Curve]] = _compute_multiclass_curves(all_matches, "f1", curve_label)
+
+    return (
+        CurvePlot(
+            title="F1-Score vs. Confidence Threshold Per Class",
+            x_label="Confidence Threshold",
+            y_label="F1-Score",
+            curves=f1_curves,
+        )
+        if f1_curves
+        else None
     )
 
 
 def compute_confusion_matrix_plot(
     all_matches: List[MulticlassInferenceMatches],
     plot_title: str = "Confusion Matrix",
 ) -> Optional[ConfusionMatrix]:
@@ -260,15 +351,15 @@
 
     :param all_matches: A list of multiclass matching results.
     :return: A dictionary with each label and its optimal F1 threshold value, zero where invalid.
     """
     optimal_thresholds: Dict[str, float] = {}
 
     y_true_score_by_label = _compute_sklearn_arrays_by_class(all_matches)
-    for label, (y_true, y_score) in y_true_score_by_label.items():
+    for label, (y_true, y_score) in sorted(y_true_score_by_label.items(), key=lambda x: x[0]):
         optimal_thresholds[label] = _compute_optimal_f1_with_arrays(y_true, y_score)
     return optimal_thresholds
 
 
 def compute_average_precision(precisions: List[float], recalls: List[float]) -> float:
     """
     Computes the average precision given a PR curve with the metrics methodology of PASCAL VOC.
```

### Comparing `kolena_client-0.74.0/kolena/_extras/__init__.py` & `kolena_client-0.75.0/kolena/_utils/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_extras/metrics/__init__.py` & `kolena_client-0.75.0/kolena/_extras/metrics/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_extras/metrics/sklearn.py` & `kolena_client-0.75.0/kolena/_extras/metrics/sklearn.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/__init__.py` & `kolena_client-0.75.0/kolena/_utils/dataframes/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/asset_path_mapper.py` & `kolena_client-0.75.0/kolena/_utils/asset_path_mapper.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/batched_load.py` & `kolena_client-0.75.0/kolena/_utils/batched_load.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/cli.py` & `kolena_client-0.75.0/kolena/_utils/cli.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/consts.py` & `kolena_client-0.75.0/kolena/_utils/consts.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/dataframes/__init__.py` & `kolena_client-0.75.0/kolena/detection/_internal/ground_truth.py`

 * *Files 14% similar despite different names*

```diff
@@ -7,7 +7,14 @@
 #    http://www.apache.org/licenses/LICENSE-2.0
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
+from enum import Enum
+
+
+class GroundTruthType(str, Enum):
+    CLASSIFICATION_LABEL = "CLASSIFICATION_LABEL"
+    BOUNDING_BOX = "BOUNDING_BOX"
+    SEGMENTATION_MASK = "SEGMENTATION_MASK"
```

### Comparing `kolena_client-0.74.0/kolena/_utils/dataframes/validators.py` & `kolena_client-0.75.0/kolena/_utils/dataframes/validators.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/datatypes.py` & `kolena_client-0.75.0/kolena/_utils/datatypes.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/endpoints.py` & `kolena_client-0.75.0/kolena/_utils/endpoints.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/frozen.py` & `kolena_client-0.75.0/kolena/_utils/frozen.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/geometry.py` & `kolena_client-0.75.0/kolena/_utils/geometry.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/inference_validators.py` & `kolena_client-0.75.0/kolena/_utils/inference_validators.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/instrumentation.py` & `kolena_client-0.75.0/kolena/_utils/instrumentation.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/krequests.py` & `kolena_client-0.75.0/kolena/_utils/krequests.py`

 * *Files 5% similar despite different names*

```diff
@@ -8,46 +8,43 @@
 #
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import uuid
+from http import HTTPStatus
 from typing import Any
 from typing import Dict
 
 import requests
 from requests import HTTPError
 from requests_toolbelt import user_agent
 from requests_toolbelt.adapters import socket_options
 from urllib3.util import Retry
 
 from kolena import __name__ as client_name
 from kolena import __version__ as client_version
 from kolena._utils.endpoints import get_endpoint
 from kolena._utils.state import get_client_state
 from kolena._utils.state import kolena_initialized
+from kolena.errors import IncorrectUsageError
 from kolena.errors import NameConflictError
 from kolena.errors import NotFoundError
 from kolena.errors import RemoteError
 from kolena.errors import UnauthenticatedError
 
 __all__ = [
     "get",
     "post",
     "put",
     "delete",
     "raise_for_status",
 ]
 
-STATUS_CODE__BAD_REQUEST = 400
-STATUS_CODE__UNAUTHORIZED = 401
-STATUS_CODE__NOT_FOUND = 404
-STATUS_CODE__CONFLICT = 409
-
 # Give the client 15 seconds to connect to kolena server
 # Slightly more than a multiple of 3, as per https://docs.python-requests.org/en/master/user/advanced/#timeouts
 CONNECTION_CONNECT_TIMEOUT = 15.05
 CONNECTION_READ_TIMEOUT = 60 * 60  # Give kolena server 1 hour to respond to client request
 
 # This only retries for failed DNS lookups, socket connections and connection timeouts.
 # HTTPAdapter sets this to 0 by default. https://requests.readthedocs.io/en/latest/_modules/requests/adapters/
@@ -104,21 +101,23 @@
     url = get_endpoint(endpoint_path=endpoint_path)
     with requests.Session() as s:
         s.mount("https://", socket_options.TCPKeepAliveAdapter(max_retries=MAX_RETRIES))
         return requests.delete(url=url, **_with_default_kwargs(**kwargs))
 
 
 def raise_for_status(response: requests.Response) -> None:
-    if response.status_code == STATUS_CODE__UNAUTHORIZED:
+    if response.status_code == HTTPStatus.UNAUTHORIZED:
         # HTTP 401 is "unauthorized" but used as "unauthenticated"
         raise UnauthenticatedError(response.content)
-    if response.status_code == STATUS_CODE__NOT_FOUND:
+    if response.status_code == HTTPStatus.NOT_FOUND:
         raise NotFoundError(response.content)
-    if response.status_code == STATUS_CODE__CONFLICT:
+    if response.status_code == HTTPStatus.CONFLICT:
         raise NameConflictError(response.content)
+    if response.status_code == HTTPStatus.UNPROCESSABLE_ENTITY:
+        raise IncorrectUsageError(response.content)
 
     try:
         response.raise_for_status()
     except HTTPError:
         raise RemoteError(f"{response.text} ({response.elapsed.total_seconds():0.5f} seconds elapsed)")
```

### Comparing `kolena_client-0.74.0/kolena/_utils/log.py` & `kolena_client-0.75.0/kolena/_utils/log.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/repository.py` & `kolena_client-0.75.0/kolena/_utils/repository.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/serde.py` & `kolena_client-0.75.0/kolena/_utils/serde.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/serializable.py` & `kolena_client-0.75.0/kolena/_utils/serializable.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/state.py` & `kolena_client-0.75.0/kolena/_utils/state.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/uninstantiable.py` & `kolena_client-0.75.0/kolena/_utils/uninstantiable.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/_utils/validators.py` & `kolena_client-0.75.0/kolena/_utils/validators.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/__init__.py` & `kolena_client-0.75.0/kolena/classification/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/metadata.py` & `kolena_client-0.75.0/kolena/classification/metadata.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/model.py` & `kolena_client-0.75.0/kolena/classification/model.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/multiclass/__init__.py` & `kolena_client-0.75.0/kolena/classification/multiclass/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/multiclass/_utils.py` & `kolena_client-0.75.0/kolena/classification/multiclass/_utils.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/multiclass/evaluator.py` & `kolena_client-0.75.0/kolena/classification/multiclass/evaluator.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/multiclass/test_run.py` & `kolena_client-0.75.0/kolena/classification/multiclass/test_run.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/multiclass/workflow.py` & `kolena_client-0.75.0/kolena/classification/multiclass/workflow.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/test_case.py` & `kolena_client-0.75.0/kolena/classification/test_case.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/test_config.py` & `kolena_client-0.75.0/kolena/classification/test_config.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/test_image.py` & `kolena_client-0.75.0/kolena/classification/test_image.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/test_run.py` & `kolena_client-0.75.0/kolena/classification/test_run.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/classification/test_suite.py` & `kolena_client-0.75.0/kolena/classification/test_suite.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/__init__.py` & `kolena_client-0.75.0/kolena/detection/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_datatypes.py` & `kolena_client-0.75.0/kolena/detection/_datatypes.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/__init__.py` & `kolena_client-0.75.0/kolena/detection/_internal/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/datatypes.py` & `kolena_client-0.75.0/kolena/detection/_internal/datatypes.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/inference.py` & `kolena_client-0.75.0/kolena/detection/_internal/inference.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/metadata.py` & `kolena_client-0.75.0/kolena/detection/_internal/metadata.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/model.py` & `kolena_client-0.75.0/kolena/detection/_internal/model.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/test_case.py` & `kolena_client-0.75.0/kolena/detection/_internal/test_case.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/test_config.py` & `kolena_client-0.75.0/kolena/detection/_internal/test_config.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/test_image.py` & `kolena_client-0.75.0/kolena/detection/_internal/test_image.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/test_run.py` & `kolena_client-0.75.0/kolena/detection/_internal/test_run.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/_internal/test_suite.py` & `kolena_client-0.75.0/kolena/detection/_internal/test_suite.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/ground_truth.py` & `kolena_client-0.75.0/kolena/detection/ground_truth.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/inference.py` & `kolena_client-0.75.0/kolena/detection/inference.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/metadata.py` & `kolena_client-0.75.0/kolena/detection/metadata.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/model.py` & `kolena_client-0.75.0/kolena/detection/model.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/test_case.py` & `kolena_client-0.75.0/kolena/detection/test_case.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/test_config.py` & `kolena_client-0.75.0/kolena/detection/test_config.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/test_image.py` & `kolena_client-0.75.0/kolena/detection/test_image.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/test_run.py` & `kolena_client-0.75.0/kolena/detection/test_run.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/detection/test_suite.py` & `kolena_client-0.75.0/kolena/detection/test_suite.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/errors.py` & `kolena_client-0.75.0/kolena/errors.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/__init__.py` & `kolena_client-0.75.0/kolena/fr/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/_utils.py` & `kolena_client-0.75.0/kolena/fr/_utils.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/datatypes.py` & `kolena_client-0.75.0/kolena/fr/datatypes.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/model.py` & `kolena_client-0.75.0/kolena/fr/model.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/test_case.py` & `kolena_client-0.75.0/kolena/fr/test_case.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/test_images.py` & `kolena_client-0.75.0/kolena/fr/test_images.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/test_run.py` & `kolena_client-0.75.0/kolena/fr/test_run.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/fr/test_suite.py` & `kolena_client-0.75.0/kolena/fr/test_suite.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/initialize.py` & `kolena_client-0.75.0/kolena/initialize.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/__init__.py` & `kolena_client-0.75.0/kolena/workflow/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/_datatypes.py` & `kolena_client-0.75.0/kolena/workflow/_datatypes.py`

 * *Files 1% similar despite different names*

```diff
@@ -246,14 +246,15 @@
         serde_function = as_serialized_json if serialize else as_deserialized_json
         df_out = df.copy()
         df_out["test_sample"] = df_out["test_sample"].apply(serde_function)
         return df_out
 
 
 class TestCaseEditorDataFrameSchema(pa.SchemaModel):
+    test_case_name: Series[pa.typing.String] = pa.Field(nullable=True)
     test_sample_type: Series[pa.typing.String] = pa.Field(coerce=True)
     test_sample: Series[JSONObject] = pa.Field(coerce=True)  # TODO: validators?
     test_sample_metadata: Series[JSONObject] = pa.Field(coerce=True)
     ground_truth: Series[JSONObject] = pa.Field(coerce=True, nullable=True)
     remove: Series[pa.typing.Bool] = pa.Field(coerce=True)
```

### Comparing `kolena_client-0.74.0/kolena/workflow/_validators.py` & `kolena_client-0.75.0/kolena/workflow/_validators.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/annotation.py` & `kolena_client-0.75.0/kolena/workflow/annotation.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/asset.py` & `kolena_client-0.75.0/kolena/workflow/asset.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/define_workflow.py` & `kolena_client-0.75.0/kolena/workflow/define_workflow.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/evaluator.py` & `kolena_client-0.75.0/kolena/workflow/evaluator.py`

 * *Files 8% similar despite different names*

```diff
@@ -65,16 +65,19 @@
 @dataclass(frozen=True, config=ValidatorConfig)
 class MetricsTestCase(DataObject, metaclass=ABCMeta):
     """
     Test-case-level metrics produced by an [`Evaluator`][kolena.workflow.Evaluator].
 
     This class should be subclassed with the relevant fields for a given workflow.
 
-    Test-case-level metrics are aggregate metrics like Precision, Recall, and F1 score. Any and all aggregate metrics
-    that fit a workflow should be defined here.
+    Test-case-level metrics are aggregate metrics like [`precision`][kolena.workflow.metrics.precision],
+    [`recall`][kolena.workflow.metrics.recall], and [`f1_score`][kolena.workflow.metrics.f1_score]. Any and all
+    aggregate metrics that fit a workflow should be defined here.
+
+    ## Nesting Aggregate Metrics
 
     `MetricsTestCase` supports nesting metrics objects, for e.g. reporting class-level metrics within a test case that
     contains multiple classes. Example usage:
 
     ```python
     @dataclass(frozen=True)
     class PerClassMetrics(MetricsTestCase):
@@ -88,14 +91,24 @@
     class TestCaseMetrics(MetricsTestCase):
         macro_Precision: float
         macro_Recall: float
         macro_F1: float
         mAP: float
         PerClass: List[PerClassMetrics]
     ```
+
+    Any `str`-type fields (e.g. `Class` in the above example) will be used as identifiers when displaying nested metrics
+    on Kolena. For best results, include at least one `str`-type field in nested metrics definitions.
+
+    When comparing nested metrics from multiple models, an `int`-type column with any of the following names will be
+    used for sample size in statistical significance calculations: `N`, `n`, `nTestSamples`, `n_test_samples`,
+    `sampleSize`, `sample_size`, `SampleSize`.
+
+    For a detailed overview of this feature, see the [:kolena-diagram-tree-16: Nesting Test Case
+    Metrics](../../advanced-usage/nesting-test-case-metrics.md) advanced usage guide.
     """
 
     def __init_subclass__(cls, **kwargs: Any) -> None:
         _validate_metrics_test_case_type(cls)
 
 
 @dataclass(frozen=True, config=ValidatorConfig)
```

### Comparing `kolena_client-0.74.0/kolena/workflow/evaluator_function.py` & `kolena_client-0.75.0/kolena/workflow/evaluator_function.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/ground_truth.py` & `kolena_client-0.75.0/kolena/workflow/ground_truth.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/inference.py` & `kolena_client-0.75.0/kolena/workflow/inference.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/metrics/__init__.py` & `kolena_client-0.75.0/kolena/workflow/metrics/__init__.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/metrics/_formula.py` & `kolena_client-0.75.0/kolena/workflow/metrics/_formula.py`

 * *Files 13% similar despite different names*

```diff
@@ -11,56 +11,68 @@
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 
 def precision(true_positives: int, false_positives: int) -> float:
     """
-    Precision represents the proportion of predictions that are correct.
+    Precision represents the proportion of inferences that are correct.
 
     $$
     \\text{Precision} = \\frac{\\text{# True Positives}}{\\text{# True Positives} + \\text{# False Positives}}
     $$
 
-    :param true_positives: Number of true positive predictions.
-    :param false_positives: Number of false positive predictions.
+    <div class="grid cards" markdown>
+    - :kolena-metrics-glossary-16: Metrics Glossary: [Precision ↗](../../metrics/precision.md)
+    </div>
+
+    :param true_positives: Number of true positive inferences.
+    :param false_positives: Number of false positive inferences.
     """
     denominator = true_positives + false_positives
     return true_positives / denominator if denominator > 0 else 0
 
 
 def recall(true_positives: int, false_negatives: int) -> float:
     """
     Recall represents the proportion of ground truths that were successfully predicted.
 
     $$
     \\text{Recall} = \\frac{\\text{# True Positives}}{\\text{# True Positives} + \\text{# False Negatives}}
     $$
 
-    :param true_positives: Number of true positive predictions.
+    <div class="grid cards" markdown>
+    - :kolena-metrics-glossary-16: Metrics Glossary: [Recall ↗](../../metrics/recall.md)
+    </div>
+
+    :param true_positives: Number of true positive inferences.
     :param false_negatives: Number of false negatives.
     """
     denominator = true_positives + false_negatives
     return true_positives / denominator if denominator > 0 else 0
 
 
 def f1_score(true_positives: int, false_positives: int, false_negatives: int) -> float:
     """
-    F1 score is the harmonic mean between [`precision`][kolena.workflow.metrics.precision] and
+    F<sub>1</sub>-score is the harmonic mean between [`precision`][kolena.workflow.metrics.precision] and
     [`recall`][kolena.workflow.metrics.recall].
 
     $$
     \\begin{align}
     \\text{F1}
     &= \\frac{2}{\\frac{1}{\\text{Precision}} + \\frac{1}{\\text{Recall}}} \\\\[1em]
     &= 2 \\times \\frac{\\text{Precision} \\times \\text{Recall}}{\\text{Precision} + \\text{Recall}}
     \\end{align}
     $$
 
-    :param true_positives: Number of true positive predictions.
-    :param false_positives: Number of false positive predictions.
+    <div class="grid cards" markdown>
+    - :kolena-metrics-glossary-16: Metrics Glossary: [F<sub>1</sub>-score ↗](../../metrics/f1-score.md)
+    </div>
+
+    :param true_positives: Number of true positive inferences.
+    :param false_positives: Number of false positive inferences.
     :param false_negatives: Number of false negatives.
     """
     prec = precision(true_positives, false_positives)
     rec = recall(true_positives, false_negatives)
     denominator = prec + rec
     return 2 * prec * rec / denominator if denominator > 0 else 0
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `kolena_client-0.74.0/kolena/workflow/metrics/_geometry.py` & `kolena_client-0.75.0/kolena/workflow/metrics/_geometry.py`

 * *Files 2% similar despite different names*

```diff
@@ -68,19 +68,23 @@
     union = box1_area + box2_area - intersection
     iou = intersection / union if union > 0 else 0.0
     return iou
 
 
 def iou(a: Union[BoundingBox, Polygon], b: Union[BoundingBox, Polygon]) -> float:
     """
-    Compute the Intersection Over Union (IOU) of two geometries.
+    Compute the Intersection Over Union (IoU) of two geometries.
+
+    <div class="grid cards" markdown>
+    - :kolena-metrics-glossary-16: Metrics Glossary: [Intersection over Union (IoU) ↗](../../metrics/iou.md)
+    </div>
 
     :param a: The first geometry in computation.
     :param b: The second geometry in computation.
-    :return: The value of the IOU between geometries `a` and `b`.
+    :return: The value of the IoU between geometries `a` and `b`.
     """
 
     if isinstance(a, BoundingBox) and isinstance(b, BoundingBox):
         return _iou_bbox(a, b)
 
     def as_shapely_polygon(obj: Union[BoundingBox, Polygon]) -> ShapelyPolygon:
         if isinstance(obj, BoundingBox):
@@ -109,15 +113,15 @@
     Objects are of type [`BoundingBox`][kolena.workflow.annotation.BoundingBox] or
     [`Polygon`][kolena.workflow.annotation.Polygon], depending on the type of inputs provided to
     [`match_inferences`][kolena.workflow.metrics.match_inferences].
     """
 
     matched: List[Tuple[GT, Inf]]
     """
-    Pairs of matched ground truth and inference objects above the IOU threshold. Considered as true positive
+    Pairs of matched ground truth and inference objects above the IoU threshold. Considered as true positive
     detections after applying some confidence threshold.
     """
 
     unmatched_gt: List[GT]
     """Unmatched ground truth objects. Considered as false negatives."""
 
     unmatched_inf: List[Inf]
@@ -137,21 +141,21 @@
     gt_objects = ground_truths
     if ignored_ground_truths:
         gt_objects = gt_objects + ignored_ground_truths
 
     # sort inferences by highest confidence first
     inferences = sorted(inferences, key=lambda inf: -inf.score)
 
-    # for each inference, find the ground truth with the highest IOU
+    # for each inference, find the ground truth with the highest IoU
     for inf in inferences:
         best_gt = None
         best_gt_iou = -1.0
         for g, gt in enumerate(gt_objects):
             inf_gt_iou = iou(gt, inf)
-            # track the highest iou over the threshold
+            # track the highest IoU over the threshold
             if inf_gt_iou >= iou_threshold and inf_gt_iou > best_gt_iou:
                 best_gt_iou = inf_gt_iou
                 best_gt = g
 
         if best_gt is None or (best_gt in taken_gts and best_gt < len(ground_truths)):
             # if there are no potential matches, or the best non-ignored gt is already taken, this inf has no match
             unmatched_inf.append(inf)
@@ -177,29 +181,33 @@
 
     This matcher does not consider labels, which is appropriate for single class object matching. To match with multiple
     classes (i.e. heeding `label` classifications), use the multiclass matcher
     [`match_inferences_multiclass`][kolena.workflow.metrics.match_inferences_multiclass].
 
     Available modes:
 
-    - `pascal` (PASCAL VOC): For every inference by order of highest confidence, the ground truth of highest IOU is
+    - `pascal` (PASCAL VOC): For every inference by order of highest confidence, the ground truth of highest IoU is
       its match. Multiple inferences are able to match with the same ignored ground truth. See the
       [PASCAL VOC paper](https://homepages.inf.ed.ac.uk/ckiw/postscript/ijcv_voc09.pdf) for more information.
 
+    <div class="grid cards" markdown>
+    - :kolena-metrics-glossary-16: Metrics Glossary: [Geometry Matching ↗](../../metrics/geometry-matching.md)
+    </div>
+
     :param List[Geometry] ground_truths: A list of [`BoundingBox`][kolena.workflow.annotation.BoundingBox] or
         [`Polygon`][kolena.workflow.annotation.Polygon] ground truths.
     :param List[ScoredGeometry] inferences: A list of
         [`ScoredBoundingBox`][kolena.workflow.annotation.ScoredBoundingBox] or
         [`ScoredPolygon`][kolena.workflow.annotation.ScoredPolygon] inferences.
     :param Optional[List[Geometry]] ignored_ground_truths: Optionally specify a list of
         [`BoundingBox`][kolena.workflow.annotation.BoundingBox] or [`Polygon`][kolena.workflow.annotation.Polygon]
         ground truths to ignore. These ignored ground truths and any inferences matched with them are
         omitted from the returned [`InferenceMatches`][kolena.workflow.metrics.InferenceMatches].
     :param mode: The matching methodology to use. See available modes above.
-    :param iou_threshold: The IOU (intersection over union, see [`iou`][kolena.workflow.metrics.iou]) threshold for
+    :param iou_threshold: The IoU (intersection over union, see [`iou`][kolena.workflow.metrics.iou]) threshold for
         valid matches.
     :return: [`InferenceMatches`][kolena.workflow.metrics.InferenceMatches] containing the matches (true positives),
         unmatched ground truths (false negatives) and unmatched inferences (false positives).
     """
 
     if mode == "pascal":
         return _match_inferences_single_class_pascal_voc(
@@ -229,21 +237,21 @@
     Objects are of type [`LabeledBoundingBox`][kolena.workflow.annotation.LabeledBoundingBox] or
     [`LabeledPolygon`][kolena.workflow.annotation.LabeledPolygon], depending on the type of inputs provided to
     [`match_inferences_multiclass`][kolena.workflow.metrics.match_inferences_multiclass].
     """
 
     matched: List[Tuple[GT_Multiclass, Inf_Multiclass]]
     """
-    Pairs of matched ground truth and inference objects above the IOU threshold. Considered as true positive
+    Pairs of matched ground truth and inference objects above the IoU threshold. Considered as true positive
     detections after applying some confidence threshold.
     """
 
     unmatched_gt: List[Tuple[GT_Multiclass, Optional[Inf_Multiclass]]]
     """
-    Pairs of unmatched ground truth objects with its confused inference object (i.e. IOU above threshold with
+    Pairs of unmatched ground truth objects with its confused inference object (i.e. IoU above threshold with
     mismatching `label`), if such an inference exists. Considered as false negatives and "confused" detections.
     """
 
     unmatched_inf: List[Inf_Multiclass]
     """Unmatched inference objects. Considered as false positives after applying some confidence threshold."""
 
 
@@ -256,36 +264,40 @@
     iou_threshold: float = 0.5,
 ) -> MulticlassInferenceMatches[GT_Multiclass, Inf_Multiclass]:
     """
     Matches model inferences with annotated ground truths using the provided configuration.
 
     This matcher considers `label` values matching per class. After matching inferences and ground truths with
     equivalent `label` values, unmatched inferences and unmatched ground truths are matched once more to identify
-    confused matches, where localization succeeded (i.e. IOU above `iou_threshold`) but classification failed (i.e.
+    confused matches, where localization succeeded (i.e. IoU above `iou_threshold`) but classification failed (i.e.
     mismatching `label` values).
 
     Available modes:
 
-    - `pascal` (PASCAL VOC): For every inference by order of highest confidence, the ground truth of highest IOU is
+    - `pascal` (PASCAL VOC): For every inference by order of highest confidence, the ground truth of highest IoU is
       its match. Multiple inferences are able to match with the same ignored ground truth. See the
       [PASCAL VOC paper](https://homepages.inf.ed.ac.uk/ckiw/postscript/ijcv_voc09.pdf) for more information.
 
+    <div class="grid cards" markdown>
+    - :kolena-metrics-glossary-16: Metrics Glossary: [Geometry Matching ↗](../../metrics/geometry-matching.md)
+    </div>
+
     :param List[LabeledGeometry] ground_truths: A list of
         [`LabeledBoundingBox`][kolena.workflow.annotation.LabeledBoundingBox] or
         [`LabeledPolygon`][kolena.workflow.annotation.LabeledPolygon] ground truths.
     :param List[ScoredLabeledGeometry] inferences: A list of
         [`ScoredLabeledBoundingBox`][kolena.workflow.annotation.ScoredLabeledBoundingBox] or
         [`ScoredLabeledPolygon`][kolena.workflow.annotation.ScoredLabeledPolygon] inferences.
     :param Optional[List[LabeledGeometry]] ignored_ground_truths: Optionally specify a list of
         [`LabeledBoundingBox`][kolena.workflow.annotation.LabeledBoundingBox] or
         [`LabeledPolygon`][kolena.workflow.annotation.LabeledPolygon] ground truths to ignore. These ignored ground
         truths and any inferences matched with them are omitted from the returned
         [`MulticlassInferenceMatches`][kolena.workflow.metrics.MulticlassInferenceMatches].
     :param mode: The matching methodology to use. See available modes above.
-    :param iou_threshold: The IOU threshold cutoff for valid matches.
+    :param iou_threshold: The IoU threshold cutoff for valid matches.
     :return:
         [`MulticlassInferenceMatches`][kolena.workflow.metrics.MulticlassInferenceMatches] containing the matches
         (true positives), unmatched ground truths (false negatives), and unmatched inferences (false positives).
     """
     matched: List[Tuple[GT_Multiclass, Inf_Multiclass]] = []
     unmatched_gt: List[GT_Multiclass] = []
     unmatched_inf: List[Inf_Multiclass] = []
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `kolena_client-0.74.0/kolena/workflow/model.py` & `kolena_client-0.75.0/kolena/workflow/model.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/plot.py` & `kolena_client-0.75.0/kolena/workflow/plot.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/test_case.py` & `kolena_client-0.75.0/kolena/workflow/test_case.py`

 * *Files 14% similar despite different names*

```diff
@@ -9,49 +9,80 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 import dataclasses
 import json
+import time
 from abc import ABCMeta
+from collections import defaultdict
 from contextlib import contextmanager
 from typing import Iterator
 from typing import List
 from typing import Optional
 from typing import Tuple
 
 import pandas as pd
 from pydantic import validate_arguments
 from pydantic.dataclasses import dataclass
 
+from kolena._api.v1.core import BulkProcessStatus
 from kolena._api.v1.core import TestCase as CoreAPI
 from kolena._api.v1.generic import TestCase as API
 from kolena._utils import krequests
 from kolena._utils import log
 from kolena._utils.batched_load import _BatchedLoader
 from kolena._utils.batched_load import init_upload
 from kolena._utils.batched_load import upload_data_frame
 from kolena._utils.consts import BatchSize
 from kolena._utils.dataframes.validators import validate_df_schema
 from kolena._utils.frozen import Frozen
 from kolena._utils.instrumentation import telemetry
 from kolena._utils.instrumentation import WithTelemetry
 from kolena._utils.serde import from_dict
 from kolena._utils.validators import ValidatorConfig
+from kolena.errors import IncorrectUsageError
 from kolena.errors import NotFoundError
 from kolena.workflow import GroundTruth
 from kolena.workflow import TestSample
 from kolena.workflow._datatypes import TestCaseEditorDataFrame
 from kolena.workflow._datatypes import TestSampleDataFrame
 from kolena.workflow._validators import assert_workflows_match
 from kolena.workflow.test_sample import _METADATA_KEY
 from kolena.workflow.workflow import Workflow
 
 
+def _to_editor_data_frame(
+    edits: List[Tuple[TestSample, Optional[GroundTruth], bool]],
+    test_case_name: Optional[str] = None,
+) -> TestCaseEditorDataFrame:
+    records = [
+        (
+            test_case_name,
+            test_sample._data_type().value,
+            test_sample._to_dict(),
+            test_sample._to_metadata_dict(),
+            ground_truth._to_dict() if ground_truth is not None else None,
+            remove,
+        )
+        for test_sample, ground_truth, remove, in edits
+    ]
+    columns = [
+        "test_case_name",
+        "test_sample_type",
+        "test_sample",
+        "test_sample_metadata",
+        "ground_truth",
+        "remove",
+    ]
+    df = pd.DataFrame(records, columns=columns)
+    return TestCaseEditorDataFrame(validate_df_schema(df, TestCaseEditorDataFrame.get_schema(), trusted=True))
+
+
 class TestCase(Frozen, WithTelemetry, metaclass=ABCMeta):
     """
     A test case holds a list of [test samples][kolena.workflow.TestSample] paired with
     [ground truths][kolena.workflow.GroundTruth] representing a testing dataset or a slice of a testing dataset.
 
     Rather than importing this class directly, use the `TestCase` type definition returned from
     [`define_workflow`][kolena.workflow.define_workflow.define_workflow].
@@ -270,28 +301,19 @@
             :param test_sample: The test sample to remove.
             """
             self._edits.append(self._Edit(test_sample, remove=True))
 
         def _edited(self) -> bool:
             return len(self._edits) > 0 or self._reset or self._description != self._initial_description
 
-        def _to_data_frame(self) -> TestCaseEditorDataFrame:
-            records = [
-                (
-                    edit.test_sample._data_type().value,
-                    edit.test_sample._to_dict(),
-                    edit.test_sample._to_metadata_dict(),
-                    edit.ground_truth._to_dict() if edit.ground_truth is not None else None,
-                    edit.remove,
-                )
-                for edit in self._edits
-            ]
-            columns = ["test_sample_type", "test_sample", "test_sample_metadata", "ground_truth", "remove"]
-            df = pd.DataFrame(records, columns=columns)
-            return TestCaseEditorDataFrame(validate_df_schema(df, TestCaseEditorDataFrame.get_schema(), trusted=True))
+        def _to_data_frame(self, test_case_name: Optional[str] = None) -> TestCaseEditorDataFrame:
+            return _to_editor_data_frame(
+                [(edit.test_sample, edit.ground_truth, edit.remove) for edit in self._edits],
+                test_case_name,
+            )
 
     @contextmanager
     def edit(self, reset: bool = False) -> Iterator[Editor]:
         """
         Edit this test case in a context:
 
         ```python
@@ -328,7 +350,95 @@
             endpoint_path=API.Path.COMPLETE_EDIT.value,
             data=json.dumps(dataclasses.asdict(request)),
         )
         krequests.raise_for_status(complete_res)
         test_case_data = from_dict(data_class=CoreAPI.EntityData, data=complete_res.json())
         self._populate_from_other(self._create_from_data(test_case_data))
         log.success(f"edited test case '{self.name}' (v{self.version})")
+
+    @classmethod
+    def init_many(
+        cls,
+        data: List[Tuple[str, List[Tuple[TestSample, GroundTruth]]]],
+        reset: bool = False,
+    ) -> List["TestCase"]:
+        """
+        !!! note "Experimental"
+
+            This function is considered **experimental**, so beware that it is subject to changes
+            even in patch releases.
+
+        Create, load or edit multiple test cases.
+
+        ```python
+        test_cases = TestCase.init_many([
+            ("test-case 1", [(test_sample_1, ground_truth_1), ...]),
+            ("test-case 2", [(test_sample_2, ground_truth_2), ...])
+        ])
+
+        test_suite = TestSuite("my test suite", test_cases=test_cases)
+        ```
+
+        Changes are committed to the Kolena platform together. If there is an error, none of the edits would take
+        effect.
+
+        :param data: A list of tuples where each tuple is a test case name and a set of test samples and ground truths
+                     tuples for the test case.
+        :param reset: If a test case of the same name already exists, overwrite with the provided test_samples.
+        :return: The test cases.
+
+
+        """
+
+        if not hasattr(cls, "workflow"):
+            raise NotImplementedError(f"{cls.__name__} must implement class attribute 'workflow'")
+
+        if len({name for name, _ in data}) != len(data):
+            raise IncorrectUsageError("Multiple edits to the same test case")
+
+        for _, test_samples in data:
+            if test_samples:
+                cls._validate_test_samples(test_samples)
+
+        cls._validate_test_samples()
+
+        log.info(f"initializing {len(data)} test cases")
+        start = time.time()
+
+        df_test_samples = [
+            _to_editor_data_frame(
+                [(sample, ground_truth, False) for sample, ground_truth in test_samples],
+                name,
+            ).as_serializable()
+            for name, test_samples in data
+            if test_samples
+        ]
+        df_serialized = pd.concat(df_test_samples) if df_test_samples else pd.DataFrame()
+        if len(df_serialized):
+            load_uuid = init_upload().uuid
+            upload_data_frame(df=df_serialized, batch_size=BatchSize.UPLOAD_RECORDS.value, load_uuid=load_uuid)
+        else:
+            load_uuid = None
+
+        request = CoreAPI.BulkProcessRequest(
+            test_cases=[CoreAPI.SingleProcessRequest(name=name, reset=reset) for name, _ in data],
+            workflow=cls.workflow.name,
+            uuid=load_uuid,
+        )
+        response = krequests.post(
+            endpoint_path=API.Path.BULK_PROCESS.value,
+            data=json.dumps(dataclasses.asdict(request)),
+        )
+        krequests.raise_for_status(response)
+        bulk_response = from_dict(data_class=CoreAPI.BulkProcessResponse, data=response.json())
+
+        test_cases = []
+        statuses = defaultdict(int)
+        for test_case_data in bulk_response.test_cases:
+            test_cases.append(cls._create_from_data(test_case_data.data))
+            statuses[test_case_data.status] += 1
+
+        end = time.time()
+        status_msg = ", ".join([f"{s.value} {statuses[s]}" for s in BulkProcessStatus])
+        log.info(f"initialized {len(data)} test cases: {status_msg} in {end - start:0.3f} seconds")
+
+        return test_cases
```

### Comparing `kolena_client-0.74.0/kolena/workflow/test_run.py` & `kolena_client-0.75.0/kolena/workflow/test_run.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/test_sample.py` & `kolena_client-0.75.0/kolena/workflow/test_sample.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/test_suite.py` & `kolena_client-0.75.0/kolena/workflow/test_suite.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/kolena/workflow/workflow.py` & `kolena_client-0.75.0/kolena/workflow/workflow.py`

 * *Files identical despite different names*

### Comparing `kolena_client-0.74.0/pyproject.toml` & `kolena_client-0.75.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "kolena-client"
-version = "0.74.0"  # version is automatically set to latest git tag during release process
+version = "0.75.0"  # version is automatically set to latest git tag during release process
 description = "Client for Kolena's machine learning (ML) testing and debugging platform."
 authors = ["Kolena Engineering <eng@kolena.io>"]
 homepage = "https://kolena.io"
 documentation = "https://docs.kolena.io"
 readme = "README.md"
 license = "Apache-2.0"
 keywords = ["Kolena", "ML", "testing"]
```

### Comparing `kolena_client-0.74.0/PKG-INFO` & `kolena_client-0.75.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kolena-client
-Version: 0.74.0
+Version: 0.75.0
 Summary: Client for Kolena's machine learning (ML) testing and debugging platform.
 Home-page: https://kolena.io
 License: Apache-2.0
 Keywords: Kolena,ML,testing
 Author: Kolena Engineering
 Author-email: eng@kolena.io
 Requires-Python: >=3.7.1,<3.12
@@ -46,15 +46,15 @@
 Requires-Dist: termcolor (>=1.1.0,<2.0.0)
 Requires-Dist: tqdm (>=4,<5)
 Requires-Dist: typing-extensions (>=4.5.0,<5.0.0) ; python_version < "3.8"
 Project-URL: Documentation, https://docs.kolena.io
 Description-Content-Type: text/markdown
 
 <p align="center">
-  <img src="/docs/assets/images/wordmark-violet.svg" width="400" alt="Kolena" />
+  <img src="https://docs.kolena.io/assets/images/wordmark-violet.svg" width="400" alt="Kolena" />
 </p>
 
 <p align='center'>
   <a href="https://pypi.python.org/pypi/kolena"><img src="https://img.shields.io/pypi/v/kolena" /></a>
   <a href="https://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/pypi/l/kolena" /></a>
   <a href="https://github.com/kolenaIO/kolena/actions"><img src="https://img.shields.io/github/checks-status/kolenaIO/kolena/trunk" /></a>
   <a href="https://codecov.io/gh/kolenaIO/kolena" ><img src="https://codecov.io/gh/kolenaIO/kolena/branch/trunk/graph/badge.svg?token=8WOY5I8SF1"/></a>
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: kolena-client Version: 0.74.0 Summary: Client for
+Metadata-Version: 2.1 Name: kolena-client Version: 0.75.0 Summary: Client for
 Kolena's machine learning (ML) testing and debugging platform. Home-page:
 https://kolena.io License: Apache-2.0 Keywords: Kolena,ML,testing Author:
 Kolena Engineering Author-email: eng@kolena.io Requires-Python: >=3.7.1,<3.12
 Classifier: Development Status :: 4 - Beta Classifier: Intended Audience ::
 Developers Classifier: Intended Audience :: Science/Research Classifier:
 License :: OSI Approved :: Apache Software License Classifier: Natural Language
 :: English Classifier: Programming Language :: Python :: 3 Classifier:
```

