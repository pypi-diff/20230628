# Comparing `tmp/deeplake-3.6.6.tar.gz` & `tmp/deeplake-3.6.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "deeplake-3.6.6.tar", last modified: Fri Jun 23 15:22:00 2023, max compression
+gzip compressed data, was "deeplake-3.6.7.tar", last modified: Wed Jun 28 11:38:45 2023, max compression
```

## Comparing `deeplake-3.6.6.tar` & `deeplake-3.6.7.tar`

### file list

```diff
@@ -1,398 +1,398 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/
--rw-r--r--   0 root         (0) root         (0)    15975 2023-06-23 15:19:39.000000 deeplake-3.6.6/LICENSE
--rw-r--r--   0 root         (0) root         (0)       36 2023-06-23 15:19:39.000000 deeplake-3.6.6/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)    26080 2023-06-23 15:22:00.243836 deeplake-3.6.6/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)    25351 2023-06-23 15:19:39.000000 deeplake-3.6.6/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.203836 deeplake-3.6.6/deeplake/
--rw-r--r--   0 root         (0) root         (0)     2662 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.203836 deeplake-3.6.6/deeplake/api/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/__init__.py
--rw-r--r--   0 root         (0) root         (0)    99372 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/dataset.py
--rw-r--r--   0 root         (0) root         (0)     4693 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/info.py
--rw-r--r--   0 root         (0) root         (0)     1203 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/link.py
--rw-r--r--   0 root         (0) root         (0)     1698 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/link_tiled.py
--rw-r--r--   0 root         (0) root         (0)     2703 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/read.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/api/tests/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3038 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_access_method.py
--rw-r--r--   0 root         (0) root         (0)     2098 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_agreement.py
--rw-r--r--   0 root         (0) root         (0)    88006 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_api.py
--rw-r--r--   0 root         (0) root         (0)     6968 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_api_tiling.py
--rw-r--r--   0 root         (0) root         (0)    11668 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_api_with_compression.py
--rw-r--r--   0 root         (0) root         (0)     2654 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_chunk_sizes.py
--rw-r--r--   0 root         (0) root         (0)     2490 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_connect_datasets.py
--rw-r--r--   0 root         (0) root         (0)     2997 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_dataset.py
--rw-r--r--   0 root         (0) root         (0)     1500 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_dicom.py
--rw-r--r--   0 root         (0) root         (0)     6192 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_downsample.py
--rw-r--r--   0 root         (0) root         (0)      953 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_events.py
--rw-r--r--   0 root         (0) root         (0)     5056 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_grayscale.py
--rw-r--r--   0 root         (0) root         (0)      247 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_hosted_datasets.py
--rw-r--r--   0 root         (0) root         (0)     6513 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_info.py
--rw-r--r--   0 root         (0) root         (0)     6911 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_insertion_out_of_order.py
--rw-r--r--   0 root         (0) root         (0)     6823 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_json.py
--rw-r--r--   0 root         (0) root         (0)    25678 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_link.py
--rw-r--r--   0 root         (0) root         (0)     3293 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_link_tiled.py
--rw-r--r--   0 root         (0) root         (0)     1789 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_linking.py
--rw-r--r--   0 root         (0) root         (0)     1024 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_mesh.py
--rw-r--r--   0 root         (0) root         (0)     1235 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_meta.py
--rw-r--r--   0 root         (0) root         (0)     4109 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_nifti.py
--rw-r--r--   0 root         (0) root         (0)     7900 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_none.py
--rw-r--r--   0 root         (0) root         (0)      952 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_partial_upload.py
--rw-r--r--   0 root         (0) root         (0)     1605 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_pickle.py
--rw-r--r--   0 root         (0) root         (0)     5680 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_point_cloud.py
--rw-r--r--   0 root         (0) root         (0)     4249 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_polygons.py
--rw-r--r--   0 root         (0) root         (0)    10559 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_pop.py
--rw-r--r--   0 root         (0) root         (0)     1577 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_readonly.py
--rw-r--r--   0 root         (0) root         (0)    18863 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_rechunk.py
--rw-r--r--   0 root         (0) root         (0)     8477 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_reset.py
--rw-r--r--   0 root         (0) root         (0)     4578 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_sample_info.py
--rw-r--r--   0 root         (0) root         (0)     2982 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_text.py
--rw-r--r--   0 root         (0) root         (0)    14556 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_update_samples.py
--rw-r--r--   0 root         (0) root         (0)     7499 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_video.py
--rw-r--r--   0 root         (0) root         (0)     4153 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tests/test_views.py
--rw-r--r--   0 root         (0) root         (0)     1368 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/api/tiled.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/auto/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/auto/structured/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/structured/__init__.py
--rw-r--r--   0 root         (0) root         (0)      635 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/structured/base.py
--rw-r--r--   0 root         (0) root         (0)     7081 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/structured/dataframe.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/auto/tests/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/tests/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7975 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/tests/test_coco_template.py
--rw-r--r--   0 root         (0) root         (0)    13490 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/tests/test_ingestion.py
--rw-r--r--   0 root         (0) root         (0)     5371 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/tests/test_kaggle.py
--rw-r--r--   0 root         (0) root         (0)     5519 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/tests/test_yolo_template.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/auto/unstructured/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/__init__.py
--rw-r--r--   0 root         (0) root         (0)      537 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/base.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/auto/unstructured/coco/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/coco/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7093 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/coco/coco.py
--rw-r--r--   0 root         (0) root         (0)      669 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/coco/constants.py
--rw-r--r--   0 root         (0) root         (0)     1709 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/coco/convert.py
--rw-r--r--   0 root         (0) root         (0)     5237 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/coco/utils.py
--rw-r--r--   0 root         (0) root         (0)     6693 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/image_classification.py
--rw-r--r--   0 root         (0) root         (0)     3533 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/kaggle.py
--rw-r--r--   0 root         (0) root         (0)     4514 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/util.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/auto/unstructured/yolo/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/yolo/__init__.py
--rw-r--r--   0 root         (0) root         (0)      278 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/yolo/constants.py
--rw-r--r--   0 root         (0) root         (0)     7394 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/yolo/utils.py
--rw-r--r--   0 root         (0) root         (0)    12937 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/auto/unstructured/yolo/yolo.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/cli/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/cli/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5913 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/cli/auth.py
--rw-r--r--   0 root         (0) root         (0)      410 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/cli/commands.py
--rw-r--r--   0 root         (0) root         (0)      931 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/cli/test_cli.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/client/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/client/__init__.py
--rw-r--r--   0 root         (0) root         (0)    19099 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/client/client.py
--rw-r--r--   0 root         (0) root         (0)     1301 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/client/config.py
--rw-r--r--   0 root         (0) root         (0)      690 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/client/log.py
--rw-r--r--   0 root         (0) root         (0)     1536 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/client/test_client.py
--rw-r--r--   0 root         (0) root         (0)     3324 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/client/utils.py
--rw-r--r--   0 root         (0) root         (0)     3876 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/compression.py
--rw-r--r--   0 root         (0) root         (0)     7420 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/constants.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/core/
--rw-r--r--   0 root         (0) root         (0)       23 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/core/chunk/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/__init__.py
--rw-r--r--   0 root         (0) root         (0)    24150 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/base_chunk.py
--rw-r--r--   0 root         (0) root         (0)    25311 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/chunk_compressed_chunk.py
--rw-r--r--   0 root         (0) root         (0)     6147 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/sample_compressed_chunk.py
--rw-r--r--   0 root         (0) root         (0)     4926 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/test_chunk_compressed.py
--rw-r--r--   0 root         (0) root         (0)     4494 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/test_sample_compressed.py
--rw-r--r--   0 root         (0) root         (0)     5446 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/test_uncompressed.py
--rw-r--r--   0 root         (0) root         (0)     9633 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk/uncompressed_chunk.py
--rw-r--r--   0 root         (0) root         (0)   117098 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/chunk_engine.py
--rw-r--r--   0 root         (0) root         (0)    39478 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/compression.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/core/compute/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/compute/__init__.py
--rw-r--r--   0 root         (0) root         (0)      911 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/compute/process.py
--rw-r--r--   0 root         (0) root         (0)     2332 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/compute/provider.py
--rw-r--r--   0 root         (0) root         (0)      640 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/compute/ray.py
--rw-r--r--   0 root         (0) root         (0)      806 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/compute/serial.py
--rw-r--r--   0 root         (0) root         (0)      576 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/compute/thread.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/core/dataset/
--rw-r--r--   0 root         (0) root         (0)      903 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/dataset/__init__.py
--rw-r--r--   0 root         (0) root         (0)   172750 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/dataset/dataset.py
--rw-r--r--   0 root         (0) root         (0)    15775 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/dataset/deeplake_cloud_dataset.py
--rw-r--r--   0 root         (0) root         (0)    11965 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/dataset/deeplake_query_dataset.py
--rw-r--r--   0 root         (0) root         (0)     5265 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/dataset/deeplake_query_tensor.py
--rw-r--r--   0 root         (0) root         (0)      760 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/dataset/invalid_view.py
--rw-r--r--   0 root         (0) root         (0)     4769 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/dataset/view_entry.py
--rw-r--r--   0 root         (0) root         (0)     4348 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/fast_forwarding.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/core/index/
--rw-r--r--   0 root         (0) root         (0)      138 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/index/__init__.py
--rw-r--r--   0 root         (0) root         (0)    17507 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/index/index.py
--rw-r--r--   0 root         (0) root         (0)    20369 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/io.py
--rw-r--r--   0 root         (0) root         (0)     4121 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/ipc.py
--rw-r--r--   0 root         (0) root         (0)    13074 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/link_creds.py
--rw-r--r--   0 root         (0) root         (0)    15995 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/linked_chunk_engine.py
--rw-r--r--   0 root         (0) root         (0)     2277 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/linked_sample.py
--rw-r--r--   0 root         (0) root         (0)     2597 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/linked_tiled_sample.py
--rw-r--r--   0 root         (0) root         (0)     8835 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/lock.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.213836 deeplake-3.6.6/deeplake/core/meta/
--rw-r--r--   0 root         (0) root         (0)       97 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3595 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/dataset_meta.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/meta/encode/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/__init__.py
--rw-r--r--   0 root         (0) root         (0)    25591 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/base_encoder.py
--rw-r--r--   0 root         (0) root         (0)     3915 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/byte_positions.py
--rw-r--r--   0 root         (0) root         (0)    13495 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/chunk_id.py
--rw-r--r--   0 root         (0) root         (0)     1551 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/creds.py
--rw-r--r--   0 root         (0) root         (0)     3972 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/pad.py
--rw-r--r--   0 root         (0) root         (0)      941 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/sequence.py
--rw-r--r--   0 root         (0) root         (0)      683 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/shape.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/meta/encode/tests/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tests/__init__.py
--rw-r--r--   0 root         (0) root         (0)      226 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tests/common.py
--rw-r--r--   0 root         (0) root         (0)     2237 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tests/test_byte_positions_encoder.py
--rw-r--r--   0 root         (0) root         (0)     1452 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tests/test_byte_positions_encoder_updates.py
--rw-r--r--   0 root         (0) root         (0)     2114 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tests/test_chunk_id_encoder.py
--rw-r--r--   0 root         (0) root         (0)     3673 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tests/test_shape_encoder.py
--rw-r--r--   0 root         (0) root         (0)     2810 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tests/test_shape_encoder_updates.py
--rw-r--r--   0 root         (0) root         (0)     7515 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/encode/tile.py
--rw-r--r--   0 root         (0) root         (0)      503 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/meta.py
--rw-r--r--   0 root         (0) root         (0)    13344 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/meta/tensor_meta.py
--rw-r--r--   0 root         (0) root         (0)      906 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/partial_reader.py
--rw-r--r--   0 root         (0) root         (0)      961 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/partial_sample.py
--rw-r--r--   0 root         (0) root         (0)     5269 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/polygon.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/query/
--rw-r--r--   0 root         (0) root         (0)       82 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/query/__init__.py
--rw-r--r--   0 root         (0) root         (0)    12021 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/query/autocomplete.py
--rw-r--r--   0 root         (0) root         (0)    14326 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/query/filter.py
--rw-r--r--   0 root         (0) root         (0)     8905 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/query/query.py
--rw-r--r--   0 root         (0) root         (0)    20658 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/sample.py
--rw-r--r--   0 root         (0) root         (0)    22849 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/serialize.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/storage/
--rw-r--r--   0 root         (0) root         (0)      495 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/__init__.py
--rw-r--r--   0 root         (0) root         (0)    13833 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/azure.py
--rw-r--r--   0 root         (0) root         (0)     1053 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/deeplake_memory_object.py
--rw-r--r--   0 root         (0) root         (0)    19080 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/gcs.py
--rw-r--r--   0 root         (0) root         (0)    13053 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/google_drive.py
--rw-r--r--   0 root         (0) root         (0)     8347 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/local.py
--rw-r--r--   0 root         (0) root         (0)    19492 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/lru_cache.py
--rw-r--r--   0 root         (0) root         (0)     3705 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/memory.py
--rw-r--r--   0 root         (0) root         (0)     7111 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/provider.py
--rw-r--r--   0 root         (0) root         (0)    25799 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/storage/s3.py
--rw-r--r--   0 root         (0) root         (0)    50495 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tensor.py
--rw-r--r--   0 root         (0) root         (0)     7485 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tensor_link.py
--rw-r--r--   0 root         (0) root         (0)     5152 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/test_serialize.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/tests/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7602 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/test_compression.py
--rw-r--r--   0 root         (0) root         (0)      692 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/test_compute.py
--rw-r--r--   0 root         (0) root         (0)    12807 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/test_deeplake_indra_dataset.py
--rw-r--r--   0 root         (0) root         (0)      913 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/test_io.py
--rw-r--r--   0 root         (0) root         (0)     4312 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/test_locking.py
--rw-r--r--   0 root         (0) root         (0)      654 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/test_readonly.py
--rw-r--r--   0 root         (0) root         (0)     1425 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tests/test_serialize.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/tiling/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tiling/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4790 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tiling/deserialize.py
--rw-r--r--   0 root         (0) root         (0)     1701 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tiling/optimizer.py
--rw-r--r--   0 root         (0) root         (0)     4731 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tiling/sample_tiles.py
--rw-r--r--   0 root         (0) root         (0)     2893 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tiling/serialize.py
--rw-r--r--   0 root         (0) root         (0)     1950 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tiling/test_optimizer.py
--rw-r--r--   0 root         (0) root         (0)     2367 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/tiling/test_serialize.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/transform/
--rw-r--r--   0 root         (0) root         (0)      111 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/transform/__init__.py
--rw-r--r--   0 root         (0) root         (0)    52250 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/transform/test_transform.py
--rw-r--r--   0 root         (0) root         (0)    29645 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/transform/transform.py
--rw-r--r--   0 root         (0) root         (0)     5860 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/transform/transform_dataset.py
--rw-r--r--   0 root         (0) root         (0)     4391 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/transform/transform_tensor.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/
--rw-r--r--   0 root         (0) root         (0)      682 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/__init__.py
--rw-r--r--   0 root         (0) root         (0)    25913 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/deeplake_vectorstore.py
--rw-r--r--   0 root         (0) root         (0)    37098 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/test_deeplake_vectorstore.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/dataset/
--rw-r--r--   0 root         (0) root         (0)      330 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/dataset/__init__.py
--rw-r--r--   0 root         (0) root         (0)    14017 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/dataset/dataset.py
--rw-r--r--   0 root         (0) root         (0)    10698 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/dataset/test_dataset.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/filter/
--rw-r--r--   0 root         (0) root         (0)      286 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/filter/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3212 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/filter/filter.py
--rw-r--r--   0 root         (0) root         (0)     3542 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/filter/test_filter.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4510 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/query.py
--rw-r--r--   0 root         (0) root         (0)     2562 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/search_algorithm.py
--rw-r--r--   0 root         (0) root         (0)     1795 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/test_indra.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/
--rw-r--r--   0 root         (0) root         (0)      275 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/__init__.py
--rw-r--r--   0 root         (0) root         (0)      781 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/distance_metric.py
--rw-r--r--   0 root         (0) root         (0)      186 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/order.py
--rw-r--r--   0 root         (0) root         (0)     1512 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/vector_search.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/
--rw-r--r--   0 root         (0) root         (0)       93 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/__init__.py
--rw-r--r--   0 root         (0) root         (0)     6564 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/data_ingestion.py
--rw-r--r--   0 root         (0) root         (0)     2047 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/ingest_data.py
--rw-r--r--   0 root         (0) root         (0)     5040 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/test_data_ingestion.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1924 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/search_algorithm.py
--rw-r--r--   0 root         (0) root         (0)     1886 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/test_vector_search.py
--rw-r--r--   0 root         (0) root         (0)     1557 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/vector_search.py
--rw-r--r--   0 root         (0) root         (0)    12156 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/utils.py
--rw-r--r--   0 root         (0) root         (0)     3399 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/vectorstore/vector_search/vector_search.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/core/version_control/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/version_control/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1954 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/version_control/commit_chunk_map.py
--rw-r--r--   0 root         (0) root         (0)     6337 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/version_control/commit_diff.py
--rw-r--r--   0 root         (0) root         (0)     3109 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/version_control/commit_node.py
--rw-r--r--   0 root         (0) root         (0)     4828 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/version_control/dataset_diff.py
--rw-r--r--   0 root         (0) root         (0)    19869 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/version_control/test_merge.py
--rw-r--r--   0 root         (0) root         (0)    84800 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/core/version_control/test_version_control.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/enterprise/
--rw-r--r--   0 root         (0) root         (0)      257 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/__init__.py
--rw-r--r--   0 root         (0) root         (0)     7381 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/convert_to_libdeeplake.py
--rw-r--r--   0 root         (0) root         (0)    29584 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/dataloader.py
--rw-r--r--   0 root         (0) root         (0)     6010 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/dummy_dataloader.py
--rw-r--r--   0 root         (0) root         (0)     4391 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/libdeeplake_query.py
--rw-r--r--   0 root         (0) root         (0)    25897 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/test_pytorch.py
--rw-r--r--   0 root         (0) root         (0)     1622 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/test_query.py
--rw-r--r--   0 root         (0) root         (0)    22353 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/test_tensorflow.py
--rw-r--r--   0 root         (0) root         (0)     1595 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/enterprise/util.py
--rw-r--r--   0 root         (0) root         (0)     1590 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/hooks.py
--rw-r--r--   0 root         (0) root         (0)     5050 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/htype.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/integrations/
--rw-r--r--   0 root         (0) root         (0)       99 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/integrations/huggingface/
--rw-r--r--   0 root         (0) root         (0)       44 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/huggingface/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5503 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/huggingface/huggingface.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.223836 deeplake-3.6.6/deeplake/integrations/mmdet/
--rw-r--r--   0 root         (0) root         (0)      118 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/mmdet/__init__.py
--rw-r--r--   0 root         (0) root         (0)    62754 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/mmdet/mmdet_.py
--rw-r--r--   0 root         (0) root         (0)     4739 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/mmdet/mmdet_runners.py
--rw-r--r--   0 root         (0) root         (0)    19660 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/mmdet/mmdet_utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/integrations/pytorch/
--rw-r--r--   0 root         (0) root         (0)       40 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/pytorch/__init__.py
--rw-r--r--   0 root         (0) root         (0)     9862 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/pytorch/common.py
--rw-r--r--   0 root         (0) root         (0)     7317 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/pytorch/dataset.py
--rw-r--r--   0 root         (0) root         (0)     4424 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/pytorch/pytorch.py
--rw-r--r--   0 root         (0) root         (0)     6919 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/pytorch/shuffle_buffer.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/integrations/tf/
--rw-r--r--   0 root         (0) root         (0)      135 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/tf/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1270 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/tf/common.py
--rw-r--r--   0 root         (0) root         (0)     2453 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/tf/datasettotensorflow.py
--rw-r--r--   0 root         (0) root         (0)     5330 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/tf/deeplake_tensorflow_dataset.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/integrations/wandb/
--rw-r--r--   0 root         (0) root         (0)       21 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/wandb/__init__.py
--rw-r--r--   0 root         (0) root         (0)    12089 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/integrations/wandb/wandb.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/requirements/
--rw-r--r--   0 root         (0) root         (0)      476 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/requirements/common.txt
--rw-r--r--   0 root         (0) root         (0)       71 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/requirements/docs.txt
--rw-r--r--   0 root         (0) root         (0)      381 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/requirements/plugins.txt
--rw-r--r--   0 root         (0) root         (0)      304 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/requirements/tests.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/tests/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/tests/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1404 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/tests/cache_fixtures.py
--rw-r--r--   0 root         (0) root         (0)     2554 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/tests/client_fixtures.py
--rw-r--r--   0 root         (0) root         (0)     4266 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/tests/common.py
--rw-r--r--   0 root         (0) root         (0)     4015 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/tests/dataset_fixtures.py
--rw-r--r--   0 root         (0) root         (0)    16165 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/tests/path_fixtures.py
--rw-r--r--   0 root         (0) root         (0)     2735 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/tests/storage_fixtures.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/util/
--rw-r--r--   0 root         (0) root         (0)       86 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3531 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/access_method.py
--rw-r--r--   0 root         (0) root         (0)     1130 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/agreement.py
--rw-r--r--   0 root         (0) root         (0)     1567 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/array_list.py
--rw-r--r--   0 root         (0) root         (0)      619 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/assert_byte_indexes.py
--rw-r--r--   0 root         (0) root         (0)     2961 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/auto.py
--rw-r--r--   0 root         (0) root         (0)     5740 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/bugout_reporter.py
--rw-r--r--   0 root         (0) root         (0)       54 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/bugout_token.py
--rw-r--r--   0 root         (0) root         (0)     3623 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/cache_chain.py
--rw-r--r--   0 root         (0) root         (0)     4494 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/casting.py
--rw-r--r--   0 root         (0) root         (0)      310 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/check_installation.py
--rw-r--r--   0 root         (0) root         (0)     1197 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/check_latest_version.py
--rw-r--r--   0 root         (0) root         (0)     3172 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/chunk_engine.py
--rw-r--r--   0 root         (0) root         (0)     4597 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/class_label.py
--rw-r--r--   0 root         (0) root         (0)      231 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/compression.py
--rw-r--r--   0 root         (0) root         (0)     1197 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/compute.py
--rw-r--r--   0 root         (0) root         (0)     5404 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/connect_dataset.py
--rw-r--r--   0 root         (0) root         (0)     1170 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/dataset.py
--rw-r--r--   0 root         (0) root         (0)      443 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/delete_entry.py
--rw-r--r--   0 root         (0) root         (0)    15912 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/diff.py
--rw-r--r--   0 root         (0) root         (0)     4945 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/downsample.py
--rw-r--r--   0 root         (0) root         (0)       84 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/empty_sample.py
--rw-r--r--   0 root         (0) root         (0)    15682 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/encoder.py
--rw-r--r--   0 root         (0) root         (0)    34773 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/exceptions.py
--rw-r--r--   0 root         (0) root         (0)     2026 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/exif.py
--rw-r--r--   0 root         (0) root         (0)     1819 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/from_tfds.py
--rw-r--r--   0 root         (0) root         (0)      136 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/generate_id.py
--rw-r--r--   0 root         (0) root         (0)      306 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/hash.py
--rw-r--r--   0 root         (0) root         (0)     2799 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/htype.py
--rw-r--r--   0 root         (0) root         (0)     1517 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/image.py
--rw-r--r--   0 root         (0) root         (0)      873 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/invalid_view_op.py
--rw-r--r--   0 root         (0) root         (0)      135 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/iterable_ordered_dict.py
--rw-r--r--   0 root         (0) root         (0)     1001 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/iteration_warning.py
--rw-r--r--   0 root         (0) root         (0)      507 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/join_chunks.py
--rw-r--r--   0 root         (0) root         (0)     6422 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/json.py
--rw-r--r--   0 root         (0) root         (0)     7261 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/keys.py
--rw-r--r--   0 root         (0) root         (0)     3071 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/link.py
--rw-r--r--   0 root         (0) root         (0)     1646 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/logging.py
--rw-r--r--   0 root         (0) root         (0)    37497 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/merge.py
--rw-r--r--   0 root         (0) root         (0)     2426 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/modified.py
--rw-r--r--   0 root         (0) root         (0)      903 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/notebook.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/util/object_3d/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3374 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/mesh.py
--rw-r--r--   0 root         (0) root         (0)      185 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/mesh_parser.py
--rw-r--r--   0 root         (0) root         (0)      185 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/mesh_reader.py
--rw-r--r--   0 root         (0) root         (0)     1021 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/object_base_3d.py
--rw-r--r--   0 root         (0) root         (0)      695 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/ply_parser.py
--rw-r--r--   0 root         (0) root         (0)     1323 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/ply_parser_base.py
--rw-r--r--   0 root         (0) root         (0)     6188 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/ply_parsers.py
--rw-r--r--   0 root         (0) root         (0)     1663 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/ply_reader.py
--rw-r--r--   0 root         (0) root         (0)     3221 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/ply_reader_base.py
--rw-r--r--   0 root         (0) root         (0)    10213 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/ply_readers.py
--rw-r--r--   0 root         (0) root         (0)     7187 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/point_cloud.py
--rw-r--r--   0 root         (0) root         (0)     1160 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/object_3d/read_3d_data.py
--rw-r--r--   0 root         (0) root         (0)     3986 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/path.py
--rw-r--r--   0 root         (0) root         (0)     3220 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/pretty_print.py
--rw-r--r--   0 root         (0) root         (0)     2763 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/remove_cache.py
--rw-r--r--   0 root         (0) root         (0)     4127 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/scheduling.py
--rw-r--r--   0 root         (0) root         (0)     3140 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/shape_interval.py
--rw-r--r--   0 root         (0) root         (0)      182 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/shuffle.py
--rw-r--r--   0 root         (0) root         (0)     4204 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/spinner.py
--rw-r--r--   0 root         (0) root         (0)     1153 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/split.py
--rw-r--r--   0 root         (0) root         (0)     8767 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/storage.py
--rw-r--r--   0 root         (0) root         (0)     1131 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tag.py
--rw-r--r--   0 root         (0) root         (0)     1390 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tensor_db.py
--rw-r--r--   0 root         (0) root         (0)      951 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/testing.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/util/tests/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1476 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_auto.py
--rw-r--r--   0 root         (0) root         (0)     1757 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_connect_dataset.py
--rw-r--r--   0 root         (0) root         (0)     1239 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_iterable_ordered_dict.py
--rw-r--r--   0 root         (0) root         (0)      892 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_read.py
--rw-r--r--   0 root         (0) root         (0)     1071 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_shape_interval.py
--rw-r--r--   0 root         (0) root         (0)      407 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_shuffle.py
--rw-r--r--   0 root         (0) root         (0)      698 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_split.py
--rw-r--r--   0 root         (0) root         (0)      974 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_tensor_db.py
--rw-r--r--   0 root         (0) root         (0)      266 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_token.py
--rw-r--r--   0 root         (0) root         (0)     2428 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/tests/test_version_control.py
--rw-r--r--   0 root         (0) root         (0)      276 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/threading.py
--rw-r--r--   0 root         (0) root         (0)      381 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/token.py
--rw-r--r--   0 root         (0) root         (0)    25277 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/transform.py
--rw-r--r--   0 root         (0) root         (0)    31615 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/version_control.py
--rw-r--r--   0 root         (0) root         (0)      927 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/video.py
--rw-r--r--   0 root         (0) root         (0)      167 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/util/warnings.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.233836 deeplake-3.6.6/deeplake/visualizer/
--rw-r--r--   0 root         (0) root         (0)       34 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/visualizer/__init__.py
--rw-r--r--   0 root         (0) root         (0)     6466 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/visualizer/video_streaming.py
--rw-r--r--   0 root         (0) root         (0)     6722 2023-06-23 15:19:39.000000 deeplake-3.6.6/deeplake/visualizer/visualizer.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-23 15:22:00.203836 deeplake-3.6.6/deeplake.egg-info/
--rw-r--r--   0 root         (0) root         (0)    26080 2023-06-23 15:22:00.000000 deeplake-3.6.6/deeplake.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)    12677 2023-06-23 15:22:00.000000 deeplake-3.6.6/deeplake.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-23 15:22:00.000000 deeplake-3.6.6/deeplake.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       58 2023-06-23 15:22:00.000000 deeplake-3.6.6/deeplake.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-23 15:22:00.000000 deeplake-3.6.6/deeplake.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)     1075 2023-06-23 15:22:00.000000 deeplake-3.6.6/deeplake.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        9 2023-06-23 15:22:00.000000 deeplake-3.6.6/deeplake.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)      311 2023-06-23 15:22:00.243836 deeplake-3.6.6/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     3357 2023-06-23 15:19:39.000000 deeplake-3.6.6/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.737727 deeplake-3.6.7/
+-rw-r--r--   0 root         (0) root         (0)    15975 2023-06-28 11:36:15.000000 deeplake-3.6.7/LICENSE
+-rw-r--r--   0 root         (0) root         (0)       36 2023-06-28 11:36:15.000000 deeplake-3.6.7/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)    26013 2023-06-28 11:38:45.737727 deeplake-3.6.7/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)    25284 2023-06-28 11:36:15.000000 deeplake-3.6.7/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.707727 deeplake-3.6.7/deeplake/
+-rw-r--r--   0 root         (0) root         (0)     2662 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.707727 deeplake-3.6.7/deeplake/api/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   100616 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/dataset.py
+-rw-r--r--   0 root         (0) root         (0)     4693 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/info.py
+-rw-r--r--   0 root         (0) root         (0)     1203 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/link.py
+-rw-r--r--   0 root         (0) root         (0)     1698 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/link_tiled.py
+-rw-r--r--   0 root         (0) root         (0)     2703 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/read.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/api/tests/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3038 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_access_method.py
+-rw-r--r--   0 root         (0) root         (0)     2098 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_agreement.py
+-rw-r--r--   0 root         (0) root         (0)    89755 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_api.py
+-rw-r--r--   0 root         (0) root         (0)     6968 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_api_tiling.py
+-rw-r--r--   0 root         (0) root         (0)    11668 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_api_with_compression.py
+-rw-r--r--   0 root         (0) root         (0)     2654 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_chunk_sizes.py
+-rw-r--r--   0 root         (0) root         (0)     2490 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_connect_datasets.py
+-rw-r--r--   0 root         (0) root         (0)     2997 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_dataset.py
+-rw-r--r--   0 root         (0) root         (0)     1500 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_dicom.py
+-rw-r--r--   0 root         (0) root         (0)     6192 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_downsample.py
+-rw-r--r--   0 root         (0) root         (0)      953 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_events.py
+-rw-r--r--   0 root         (0) root         (0)     5056 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_grayscale.py
+-rw-r--r--   0 root         (0) root         (0)      247 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_hosted_datasets.py
+-rw-r--r--   0 root         (0) root         (0)     6513 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_info.py
+-rw-r--r--   0 root         (0) root         (0)     6911 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_insertion_out_of_order.py
+-rw-r--r--   0 root         (0) root         (0)     6823 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_json.py
+-rw-r--r--   0 root         (0) root         (0)    25678 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_link.py
+-rw-r--r--   0 root         (0) root         (0)     3293 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_link_tiled.py
+-rw-r--r--   0 root         (0) root         (0)     1789 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_linking.py
+-rw-r--r--   0 root         (0) root         (0)     1024 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_mesh.py
+-rw-r--r--   0 root         (0) root         (0)     1235 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_meta.py
+-rw-r--r--   0 root         (0) root         (0)     4109 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_nifti.py
+-rw-r--r--   0 root         (0) root         (0)     7900 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_none.py
+-rw-r--r--   0 root         (0) root         (0)      952 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_partial_upload.py
+-rw-r--r--   0 root         (0) root         (0)     1605 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_pickle.py
+-rw-r--r--   0 root         (0) root         (0)     5680 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_point_cloud.py
+-rw-r--r--   0 root         (0) root         (0)     4249 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_polygons.py
+-rw-r--r--   0 root         (0) root         (0)    10559 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_pop.py
+-rw-r--r--   0 root         (0) root         (0)     1577 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_readonly.py
+-rw-r--r--   0 root         (0) root         (0)    18861 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_rechunk.py
+-rw-r--r--   0 root         (0) root         (0)     8477 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_reset.py
+-rw-r--r--   0 root         (0) root         (0)     4578 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_sample_info.py
+-rw-r--r--   0 root         (0) root         (0)     2982 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_text.py
+-rw-r--r--   0 root         (0) root         (0)    25050 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_update_samples.py
+-rw-r--r--   0 root         (0) root         (0)     7499 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_video.py
+-rw-r--r--   0 root         (0) root         (0)     4153 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tests/test_views.py
+-rw-r--r--   0 root         (0) root         (0)     1368 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/api/tiled.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/auto/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/auto/structured/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/structured/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      635 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/structured/base.py
+-rw-r--r--   0 root         (0) root         (0)     7081 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/structured/dataframe.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/auto/tests/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/tests/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7975 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/tests/test_coco_template.py
+-rw-r--r--   0 root         (0) root         (0)    13490 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/tests/test_ingestion.py
+-rw-r--r--   0 root         (0) root         (0)     5371 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/tests/test_kaggle.py
+-rw-r--r--   0 root         (0) root         (0)     5519 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/tests/test_yolo_template.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/auto/unstructured/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      537 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/base.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/auto/unstructured/coco/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/coco/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7093 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/coco/coco.py
+-rw-r--r--   0 root         (0) root         (0)      669 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/coco/constants.py
+-rw-r--r--   0 root         (0) root         (0)     1709 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/coco/convert.py
+-rw-r--r--   0 root         (0) root         (0)     5237 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/coco/utils.py
+-rw-r--r--   0 root         (0) root         (0)     6693 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/image_classification.py
+-rw-r--r--   0 root         (0) root         (0)     3533 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/kaggle.py
+-rw-r--r--   0 root         (0) root         (0)     4514 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/util.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/auto/unstructured/yolo/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/yolo/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      278 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/yolo/constants.py
+-rw-r--r--   0 root         (0) root         (0)     7394 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/yolo/utils.py
+-rw-r--r--   0 root         (0) root         (0)    12937 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/auto/unstructured/yolo/yolo.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/cli/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/cli/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5913 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/cli/auth.py
+-rw-r--r--   0 root         (0) root         (0)      410 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/cli/commands.py
+-rw-r--r--   0 root         (0) root         (0)      931 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/cli/test_cli.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/client/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/client/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    19099 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/client/client.py
+-rw-r--r--   0 root         (0) root         (0)     1301 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/client/config.py
+-rw-r--r--   0 root         (0) root         (0)      690 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/client/log.py
+-rw-r--r--   0 root         (0) root         (0)     1536 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/client/test_client.py
+-rw-r--r--   0 root         (0) root         (0)     3324 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/client/utils.py
+-rw-r--r--   0 root         (0) root         (0)     3876 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/compression.py
+-rw-r--r--   0 root         (0) root         (0)     7420 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/constants.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/
+-rw-r--r--   0 root         (0) root         (0)       23 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/chunk/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    24150 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/base_chunk.py
+-rw-r--r--   0 root         (0) root         (0)    25311 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/chunk_compressed_chunk.py
+-rw-r--r--   0 root         (0) root         (0)     6147 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/sample_compressed_chunk.py
+-rw-r--r--   0 root         (0) root         (0)     4926 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/test_chunk_compressed.py
+-rw-r--r--   0 root         (0) root         (0)     4494 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/test_sample_compressed.py
+-rw-r--r--   0 root         (0) root         (0)     5446 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/test_uncompressed.py
+-rw-r--r--   0 root         (0) root         (0)     9633 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk/uncompressed_chunk.py
+-rw-r--r--   0 root         (0) root         (0)   118018 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/chunk_engine.py
+-rw-r--r--   0 root         (0) root         (0)    39478 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/compression.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/compute/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/compute/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      911 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/compute/process.py
+-rw-r--r--   0 root         (0) root         (0)     2332 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/compute/provider.py
+-rw-r--r--   0 root         (0) root         (0)      640 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/compute/ray.py
+-rw-r--r--   0 root         (0) root         (0)      806 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/compute/serial.py
+-rw-r--r--   0 root         (0) root         (0)      576 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/compute/thread.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/dataset/
+-rw-r--r--   0 root         (0) root         (0)      903 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/dataset/__init__.py
+-rw-r--r--   0 root         (0) root         (0)   177242 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/dataset/dataset.py
+-rw-r--r--   0 root         (0) root         (0)    15775 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/dataset/deeplake_cloud_dataset.py
+-rw-r--r--   0 root         (0) root         (0)    11965 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/dataset/deeplake_query_dataset.py
+-rw-r--r--   0 root         (0) root         (0)     5265 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/dataset/deeplake_query_tensor.py
+-rw-r--r--   0 root         (0) root         (0)      760 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/dataset/invalid_view.py
+-rw-r--r--   0 root         (0) root         (0)     4769 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/dataset/view_entry.py
+-rw-r--r--   0 root         (0) root         (0)     4348 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/fast_forwarding.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/index/
+-rw-r--r--   0 root         (0) root         (0)      138 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/index/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    17507 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/index/index.py
+-rw-r--r--   0 root         (0) root         (0)    20369 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/io.py
+-rw-r--r--   0 root         (0) root         (0)     4121 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/ipc.py
+-rw-r--r--   0 root         (0) root         (0)    13074 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/link_creds.py
+-rw-r--r--   0 root         (0) root         (0)    16043 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/linked_chunk_engine.py
+-rw-r--r--   0 root         (0) root         (0)     2277 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/linked_sample.py
+-rw-r--r--   0 root         (0) root         (0)     2597 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/linked_tiled_sample.py
+-rw-r--r--   0 root         (0) root         (0)     8835 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/lock.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/meta/
+-rw-r--r--   0 root         (0) root         (0)       97 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3595 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/dataset_meta.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/meta/encode/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    25591 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/base_encoder.py
+-rw-r--r--   0 root         (0) root         (0)     3915 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/byte_positions.py
+-rw-r--r--   0 root         (0) root         (0)    13495 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/chunk_id.py
+-rw-r--r--   0 root         (0) root         (0)     1551 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/creds.py
+-rw-r--r--   0 root         (0) root         (0)     3972 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/pad.py
+-rw-r--r--   0 root         (0) root         (0)      941 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/sequence.py
+-rw-r--r--   0 root         (0) root         (0)      683 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/shape.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/meta/encode/tests/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tests/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      226 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tests/common.py
+-rw-r--r--   0 root         (0) root         (0)     2237 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tests/test_byte_positions_encoder.py
+-rw-r--r--   0 root         (0) root         (0)     1452 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tests/test_byte_positions_encoder_updates.py
+-rw-r--r--   0 root         (0) root         (0)     2114 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tests/test_chunk_id_encoder.py
+-rw-r--r--   0 root         (0) root         (0)     3673 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tests/test_shape_encoder.py
+-rw-r--r--   0 root         (0) root         (0)     2810 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tests/test_shape_encoder_updates.py
+-rw-r--r--   0 root         (0) root         (0)     7515 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/encode/tile.py
+-rw-r--r--   0 root         (0) root         (0)      503 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/meta.py
+-rw-r--r--   0 root         (0) root         (0)    13344 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/meta/tensor_meta.py
+-rw-r--r--   0 root         (0) root         (0)      906 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/partial_reader.py
+-rw-r--r--   0 root         (0) root         (0)      961 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/partial_sample.py
+-rw-r--r--   0 root         (0) root         (0)     5269 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/polygon.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.717727 deeplake-3.6.7/deeplake/core/query/
+-rw-r--r--   0 root         (0) root         (0)       82 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/query/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12021 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/query/autocomplete.py
+-rw-r--r--   0 root         (0) root         (0)    14326 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/query/filter.py
+-rw-r--r--   0 root         (0) root         (0)     8905 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/query/query.py
+-rw-r--r--   0 root         (0) root         (0)    20658 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/sample.py
+-rw-r--r--   0 root         (0) root         (0)    22849 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/serialize.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/storage/
+-rw-r--r--   0 root         (0) root         (0)      495 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    13833 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/azure.py
+-rw-r--r--   0 root         (0) root         (0)     1053 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/deeplake_memory_object.py
+-rw-r--r--   0 root         (0) root         (0)    19080 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/gcs.py
+-rw-r--r--   0 root         (0) root         (0)    13053 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/google_drive.py
+-rw-r--r--   0 root         (0) root         (0)     8347 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/local.py
+-rw-r--r--   0 root         (0) root         (0)    19492 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/lru_cache.py
+-rw-r--r--   0 root         (0) root         (0)     3705 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/memory.py
+-rw-r--r--   0 root         (0) root         (0)     7111 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/provider.py
+-rw-r--r--   0 root         (0) root         (0)    25799 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/storage/s3.py
+-rw-r--r--   0 root         (0) root         (0)    50495 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tensor.py
+-rw-r--r--   0 root         (0) root         (0)     7485 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tensor_link.py
+-rw-r--r--   0 root         (0) root         (0)     5152 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/test_serialize.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/tests/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7602 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/test_compression.py
+-rw-r--r--   0 root         (0) root         (0)      692 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/test_compute.py
+-rw-r--r--   0 root         (0) root         (0)    12917 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/test_deeplake_indra_dataset.py
+-rw-r--r--   0 root         (0) root         (0)      913 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/test_io.py
+-rw-r--r--   0 root         (0) root         (0)     4312 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/test_locking.py
+-rw-r--r--   0 root         (0) root         (0)      654 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/test_readonly.py
+-rw-r--r--   0 root         (0) root         (0)     1425 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tests/test_serialize.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/tiling/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tiling/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4790 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tiling/deserialize.py
+-rw-r--r--   0 root         (0) root         (0)     1701 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tiling/optimizer.py
+-rw-r--r--   0 root         (0) root         (0)     4731 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tiling/sample_tiles.py
+-rw-r--r--   0 root         (0) root         (0)     2893 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tiling/serialize.py
+-rw-r--r--   0 root         (0) root         (0)     1950 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tiling/test_optimizer.py
+-rw-r--r--   0 root         (0) root         (0)     2367 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/tiling/test_serialize.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/transform/
+-rw-r--r--   0 root         (0) root         (0)      111 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/transform/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    52842 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/transform/test_transform.py
+-rw-r--r--   0 root         (0) root         (0)    29645 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/transform/transform.py
+-rw-r--r--   0 root         (0) root         (0)     5970 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/transform/transform_dataset.py
+-rw-r--r--   0 root         (0) root         (0)     4391 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/transform/transform_tensor.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/
+-rw-r--r--   0 root         (0) root         (0)      682 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    26286 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/deeplake_vectorstore.py
+-rw-r--r--   0 root         (0) root         (0)    38384 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/test_deeplake_vectorstore.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/dataset/
+-rw-r--r--   0 root         (0) root         (0)      330 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/dataset/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    15388 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/dataset/dataset.py
+-rw-r--r--   0 root         (0) root         (0)    11402 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/dataset/test_dataset.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/filter/
+-rw-r--r--   0 root         (0) root         (0)      286 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/filter/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3212 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/filter/filter.py
+-rw-r--r--   0 root         (0) root         (0)     3542 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/filter/test_filter.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4510 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/query.py
+-rw-r--r--   0 root         (0) root         (0)     2562 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/search_algorithm.py
+-rw-r--r--   0 root         (0) root         (0)     1795 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/test_indra.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/
+-rw-r--r--   0 root         (0) root         (0)      275 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      781 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/distance_metric.py
+-rw-r--r--   0 root         (0) root         (0)      186 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/order.py
+-rw-r--r--   0 root         (0) root         (0)     1512 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/vector_search.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/
+-rw-r--r--   0 root         (0) root         (0)       93 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     6949 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/data_ingestion.py
+-rw-r--r--   0 root         (0) root         (0)     2047 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/ingest_data.py
+-rw-r--r--   0 root         (0) root         (0)     5040 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/test_data_ingestion.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1924 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/search_algorithm.py
+-rw-r--r--   0 root         (0) root         (0)     1886 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/test_vector_search.py
+-rw-r--r--   0 root         (0) root         (0)     1557 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/vector_search.py
+-rw-r--r--   0 root         (0) root         (0)    12156 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/utils.py
+-rw-r--r--   0 root         (0) root         (0)     3399 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/vectorstore/vector_search/vector_search.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/core/version_control/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/version_control/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1954 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/version_control/commit_chunk_map.py
+-rw-r--r--   0 root         (0) root         (0)     6337 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/version_control/commit_diff.py
+-rw-r--r--   0 root         (0) root         (0)     3109 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/version_control/commit_node.py
+-rw-r--r--   0 root         (0) root         (0)     4828 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/version_control/dataset_diff.py
+-rw-r--r--   0 root         (0) root         (0)    19869 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/version_control/test_merge.py
+-rw-r--r--   0 root         (0) root         (0)    84800 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/core/version_control/test_version_control.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/enterprise/
+-rw-r--r--   0 root         (0) root         (0)      257 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7381 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/convert_to_libdeeplake.py
+-rw-r--r--   0 root         (0) root         (0)    29584 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/dataloader.py
+-rw-r--r--   0 root         (0) root         (0)     6010 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/dummy_dataloader.py
+-rw-r--r--   0 root         (0) root         (0)     4391 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/libdeeplake_query.py
+-rw-r--r--   0 root         (0) root         (0)    25912 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/test_pytorch.py
+-rw-r--r--   0 root         (0) root         (0)     1671 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/test_query.py
+-rw-r--r--   0 root         (0) root         (0)    22454 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/test_tensorflow.py
+-rw-r--r--   0 root         (0) root         (0)     1595 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/enterprise/util.py
+-rw-r--r--   0 root         (0) root         (0)     1590 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/hooks.py
+-rw-r--r--   0 root         (0) root         (0)     5050 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/htype.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/integrations/
+-rw-r--r--   0 root         (0) root         (0)       99 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/integrations/huggingface/
+-rw-r--r--   0 root         (0) root         (0)       44 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/huggingface/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5503 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/huggingface/huggingface.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/integrations/mmdet/
+-rw-r--r--   0 root         (0) root         (0)      118 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/mmdet/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    62754 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/mmdet/mmdet_.py
+-rw-r--r--   0 root         (0) root         (0)     4739 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/mmdet/mmdet_runners.py
+-rw-r--r--   0 root         (0) root         (0)    19660 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/mmdet/mmdet_utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/integrations/pytorch/
+-rw-r--r--   0 root         (0) root         (0)       40 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/pytorch/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     9862 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/pytorch/common.py
+-rw-r--r--   0 root         (0) root         (0)     7317 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/pytorch/dataset.py
+-rw-r--r--   0 root         (0) root         (0)     4424 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/pytorch/pytorch.py
+-rw-r--r--   0 root         (0) root         (0)     6919 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/pytorch/shuffle_buffer.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/integrations/tf/
+-rw-r--r--   0 root         (0) root         (0)      135 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/tf/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1270 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/tf/common.py
+-rw-r--r--   0 root         (0) root         (0)     2453 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/tf/datasettotensorflow.py
+-rw-r--r--   0 root         (0) root         (0)     5330 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/tf/deeplake_tensorflow_dataset.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/integrations/wandb/
+-rw-r--r--   0 root         (0) root         (0)       21 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/wandb/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    12089 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/integrations/wandb/wandb.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/requirements/
+-rw-r--r--   0 root         (0) root         (0)      476 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/requirements/common.txt
+-rw-r--r--   0 root         (0) root         (0)       71 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/requirements/docs.txt
+-rw-r--r--   0 root         (0) root         (0)      381 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/requirements/plugins.txt
+-rw-r--r--   0 root         (0) root         (0)      304 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/requirements/tests.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.727727 deeplake-3.6.7/deeplake/tests/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/tests/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1404 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/tests/cache_fixtures.py
+-rw-r--r--   0 root         (0) root         (0)     2554 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/tests/client_fixtures.py
+-rw-r--r--   0 root         (0) root         (0)     4266 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/tests/common.py
+-rw-r--r--   0 root         (0) root         (0)     4304 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/tests/dataset_fixtures.py
+-rw-r--r--   0 root         (0) root         (0)    16369 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/tests/path_fixtures.py
+-rw-r--r--   0 root         (0) root         (0)     2735 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/tests/storage_fixtures.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.737727 deeplake-3.6.7/deeplake/util/
+-rw-r--r--   0 root         (0) root         (0)       86 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3531 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/access_method.py
+-rw-r--r--   0 root         (0) root         (0)     1130 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/agreement.py
+-rw-r--r--   0 root         (0) root         (0)     1567 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/array_list.py
+-rw-r--r--   0 root         (0) root         (0)      619 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/assert_byte_indexes.py
+-rw-r--r--   0 root         (0) root         (0)     2961 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/auto.py
+-rw-r--r--   0 root         (0) root         (0)     5740 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/bugout_reporter.py
+-rw-r--r--   0 root         (0) root         (0)       54 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/bugout_token.py
+-rw-r--r--   0 root         (0) root         (0)     3623 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/cache_chain.py
+-rw-r--r--   0 root         (0) root         (0)     4494 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/casting.py
+-rw-r--r--   0 root         (0) root         (0)      310 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/check_installation.py
+-rw-r--r--   0 root         (0) root         (0)     1197 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/check_latest_version.py
+-rw-r--r--   0 root         (0) root         (0)     3151 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/chunk_engine.py
+-rw-r--r--   0 root         (0) root         (0)     4597 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/class_label.py
+-rw-r--r--   0 root         (0) root         (0)      231 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/compression.py
+-rw-r--r--   0 root         (0) root         (0)     1197 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/compute.py
+-rw-r--r--   0 root         (0) root         (0)     5404 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/connect_dataset.py
+-rw-r--r--   0 root         (0) root         (0)     1170 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/dataset.py
+-rw-r--r--   0 root         (0) root         (0)      443 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/delete_entry.py
+-rw-r--r--   0 root         (0) root         (0)    15912 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/diff.py
+-rw-r--r--   0 root         (0) root         (0)     4945 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/downsample.py
+-rw-r--r--   0 root         (0) root         (0)       84 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/empty_sample.py
+-rw-r--r--   0 root         (0) root         (0)    15682 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/encoder.py
+-rw-r--r--   0 root         (0) root         (0)    35113 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/exceptions.py
+-rw-r--r--   0 root         (0) root         (0)     2026 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/exif.py
+-rw-r--r--   0 root         (0) root         (0)     1819 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/from_tfds.py
+-rw-r--r--   0 root         (0) root         (0)      136 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/generate_id.py
+-rw-r--r--   0 root         (0) root         (0)      306 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/hash.py
+-rw-r--r--   0 root         (0) root         (0)     2799 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/htype.py
+-rw-r--r--   0 root         (0) root         (0)     1517 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/image.py
+-rw-r--r--   0 root         (0) root         (0)      873 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/invalid_view_op.py
+-rw-r--r--   0 root         (0) root         (0)      135 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/iterable_ordered_dict.py
+-rw-r--r--   0 root         (0) root         (0)     1001 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/iteration_warning.py
+-rw-r--r--   0 root         (0) root         (0)      507 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/join_chunks.py
+-rw-r--r--   0 root         (0) root         (0)     6422 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/json.py
+-rw-r--r--   0 root         (0) root         (0)     7261 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/keys.py
+-rw-r--r--   0 root         (0) root         (0)     3071 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/link.py
+-rw-r--r--   0 root         (0) root         (0)     1646 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/logging.py
+-rw-r--r--   0 root         (0) root         (0)    37497 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/merge.py
+-rw-r--r--   0 root         (0) root         (0)     2426 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/modified.py
+-rw-r--r--   0 root         (0) root         (0)      903 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/notebook.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.737727 deeplake-3.6.7/deeplake/util/object_3d/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3374 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/mesh.py
+-rw-r--r--   0 root         (0) root         (0)      185 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/mesh_parser.py
+-rw-r--r--   0 root         (0) root         (0)      185 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/mesh_reader.py
+-rw-r--r--   0 root         (0) root         (0)     1021 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/object_base_3d.py
+-rw-r--r--   0 root         (0) root         (0)      695 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/ply_parser.py
+-rw-r--r--   0 root         (0) root         (0)     1323 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/ply_parser_base.py
+-rw-r--r--   0 root         (0) root         (0)     6188 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/ply_parsers.py
+-rw-r--r--   0 root         (0) root         (0)     1663 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/ply_reader.py
+-rw-r--r--   0 root         (0) root         (0)     3221 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/ply_reader_base.py
+-rw-r--r--   0 root         (0) root         (0)    10213 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/ply_readers.py
+-rw-r--r--   0 root         (0) root         (0)     7187 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/point_cloud.py
+-rw-r--r--   0 root         (0) root         (0)     1160 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/object_3d/read_3d_data.py
+-rw-r--r--   0 root         (0) root         (0)     3986 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/path.py
+-rw-r--r--   0 root         (0) root         (0)     3220 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/pretty_print.py
+-rw-r--r--   0 root         (0) root         (0)     2763 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/remove_cache.py
+-rw-r--r--   0 root         (0) root         (0)     4137 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/scheduling.py
+-rw-r--r--   0 root         (0) root         (0)     3140 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/shape_interval.py
+-rw-r--r--   0 root         (0) root         (0)      182 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/shuffle.py
+-rw-r--r--   0 root         (0) root         (0)     4204 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/spinner.py
+-rw-r--r--   0 root         (0) root         (0)     1153 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/split.py
+-rw-r--r--   0 root         (0) root         (0)     8767 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/storage.py
+-rw-r--r--   0 root         (0) root         (0)     1131 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tag.py
+-rw-r--r--   0 root         (0) root         (0)     1390 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tensor_db.py
+-rw-r--r--   0 root         (0) root         (0)      951 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/testing.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.737727 deeplake-3.6.7/deeplake/util/tests/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1476 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_auto.py
+-rw-r--r--   0 root         (0) root         (0)     1757 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_connect_dataset.py
+-rw-r--r--   0 root         (0) root         (0)     1239 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_iterable_ordered_dict.py
+-rw-r--r--   0 root         (0) root         (0)      892 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_read.py
+-rw-r--r--   0 root         (0) root         (0)     1071 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_shape_interval.py
+-rw-r--r--   0 root         (0) root         (0)      407 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_shuffle.py
+-rw-r--r--   0 root         (0) root         (0)      698 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_split.py
+-rw-r--r--   0 root         (0) root         (0)      974 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_tensor_db.py
+-rw-r--r--   0 root         (0) root         (0)      266 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_token.py
+-rw-r--r--   0 root         (0) root         (0)     2428 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/tests/test_version_control.py
+-rw-r--r--   0 root         (0) root         (0)      276 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/threading.py
+-rw-r--r--   0 root         (0) root         (0)      381 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/token.py
+-rw-r--r--   0 root         (0) root         (0)    25277 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/transform.py
+-rw-r--r--   0 root         (0) root         (0)    31615 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/version_control.py
+-rw-r--r--   0 root         (0) root         (0)      927 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/video.py
+-rw-r--r--   0 root         (0) root         (0)      167 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/util/warnings.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.737727 deeplake-3.6.7/deeplake/visualizer/
+-rw-r--r--   0 root         (0) root         (0)       34 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/visualizer/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     6466 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/visualizer/video_streaming.py
+-rw-r--r--   0 root         (0) root         (0)     6722 2023-06-28 11:36:15.000000 deeplake-3.6.7/deeplake/visualizer/visualizer.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:38:45.707727 deeplake-3.6.7/deeplake.egg-info/
+-rw-r--r--   0 root         (0) root         (0)    26013 2023-06-28 11:38:45.000000 deeplake-3.6.7/deeplake.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)    12677 2023-06-28 11:38:45.000000 deeplake-3.6.7/deeplake.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 11:38:45.000000 deeplake-3.6.7/deeplake.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       58 2023-06-28 11:38:45.000000 deeplake-3.6.7/deeplake.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 11:38:45.000000 deeplake-3.6.7/deeplake.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)     1075 2023-06-28 11:38:45.000000 deeplake-3.6.7/deeplake.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        9 2023-06-28 11:38:45.000000 deeplake-3.6.7/deeplake.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)      311 2023-06-28 11:38:45.737727 deeplake-3.6.7/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     3357 2023-06-28 11:36:15.000000 deeplake-3.6.7/setup.py
```

### Comparing `deeplake-3.6.6/LICENSE` & `deeplake-3.6.7/LICENSE`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/PKG-INFO` & `deeplake-3.6.7/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: deeplake
-Version: 3.6.6
+Version: 3.6.7
 Summary: Activeloop Deep Lake
 Home-page: UNKNOWN
 Author: activeloop.ai
 Author-email: support@activeloop.ai
 License: MPL-2.0
 Project-URL: Documentation, https://docs.activeloop.ai/
 Project-URL: Source, https://github.com/activeloopai/deeplake
@@ -28,32 +28,32 @@
 <img src="https://static.scarf.sh/a.png?x-pxid=bc3c57b0-9a65-49fe-b8ea-f711c4d35b82" /><p align="center">
      <img src="https://i.postimg.cc/rsjcWc3S/deeplake-logo.png" width="400"/>
 </h1>
     </br>
     <h1 align="center">Deep Lake: Database for AI
  </h1>
 <p align="center">
-    <a href="https://github.com/activeloopai/Hub/actions/workflows/test-pr-on-label.yml"><img src="https://github.com/activeloopai/Hub/actions/workflows/test-push.yml/badge.svg" alt="PyPI version" height="18"></a>
+    <a href="https://github.com/activeloopai/deeplake/actions/workflows/test-pr-on-label.yml"><img src="https://github.com/activeloopai/deeplake/actions/workflows/test-push.yml/badge.svg" alt="PyPI version" height="18"></a>
     <a href="https://pypi.org/project/deeplake/"><img src="https://badge.fury.io/py/deeplake.svg" alt="PyPI version" height="18"></a>
     <a href='https://docs.deeplake.ai/en/latest/?badge=latest'>
      <img src='https://readthedocs.org/projects/deep-lake/badge/?version=latest' alt='Documentation Status' />
      </a>
     <a href="https://pepy.tech/project/deeplake"><img src="https://static.pepy.tech/badge/deeplake" alt="PyPI version" height="18"></a>
      <a href="https://github.com/activeloopai/deeplake/issues">
     <img alt="GitHub issues" src="https://img.shields.io/github/issues/activeloopai/deeplake"> </a>
     <a href="https://codecov.io/gh/activeloopai/deeplake/branch/main"><img src="https://codecov.io/gh/activeloopai/deeplake/branch/main/graph/badge.svg" alt="codecov" height="18"></a>
   <h3 align="center">
-   <a href="https://docs.activeloop.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Documentation</b></a> &bull;
-   <a href="https://docs.activeloop.ai/getting-started/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Getting Started</b></a> &bull;
+   <a href="https://docs.activeloop.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Docs</b></a> &bull;
+   <a href="https://docs.activeloop.ai/getting-started/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Get Started</b></a> &bull;
    <a href="https://docs.deeplake.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>API Reference</b></a> &bull;  
-   <a href="https://github.com/activeloopai/examples/"><b>Examples</b></a> &bull; 
+   <a href="http://learn.activeloop.ai"><b>LangChain & VectorDBs Course</b></a> &bull;
    <a href="https://www.activeloop.ai/resources/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Blog</b></a> &bull; 
    <a href="https://www.deeplake.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Whitepaper</b></a> &bull;  
-  <a href="http://slack.activeloop.ai"><b>Slack Community</b></a> &bull;
-  <a href="https://twitter.com/intent/tweet?text=The%20dataset%20format%20for%20AI.%20Stream%20data%20to%20PyTorch%20and%20Tensorflow%20datasets&url=https://activeloop.ai/&via=activeloopai&hashtags=opensource,pytorch,tensorflow,data,datascience,datapipelines,activeloop,databaseforAI"><b>Twitter</b></a>
+  <a href="http://slack.activeloop.ai"><b>Slack</b></a> &bull;
+  <a href="https://twitter.com/intent/tweet?url=https%3A%2F%2Factiveloop.ai%2F&via=activeloopai&text=Deep%20Lake%20is%20the%20Database%20for%20all%20AI%20data.%20Check%20it%20out%21&hashtags=DeepLake%2Cactiveloop%2Copensource"><b>Twitter</b></a>
  </h3>
  
 
 *Read this in other languages: [简体中文](README.zh-cn.md)*
 
 ## About Deep Lake
```

#### html2text {}

```diff
@@ -1,24 +1,24 @@
-Metadata-Version: 2.1 Name: deeplake Version: 3.6.6 Summary: Activeloop Deep
+Metadata-Version: 2.1 Name: deeplake Version: 3.6.7 Summary: Activeloop Deep
 Lake Home-page: UNKNOWN Author: activeloop.ai Author-email:
 support@activeloop.ai License: MPL-2.0 Project-URL: Documentation, https://
 docs.activeloop.ai/ Project-URL: Source, https://github.com/activeloopai/
 deeplake Platform: UNKNOWN Classifier: License :: OSI Approved :: Mozilla
 Public License 2.0 (MPL 2.0) Description-Content-Type: text/markdown Provides-
 Extra: all Provides-Extra: audio Provides-Extra: av Provides-Extra: azure
 Provides-Extra: dicom Provides-Extra: enterprise Provides-Extra: gcp Provides-
 Extra: gdrive Provides-Extra: medical Provides-Extra: point_cloud Provides-
 Extra: video Provides-Extra: visualizer License-File: LICENSE [https://
 static.scarf.sh/a.png?x-pxid=bc3c57b0-9a65-49fe-b8ea-f711c4d35b82]
                [https://i.postimg.cc/rsjcWc3S/deeplake-logo.png]
                    ****** Deep Lake: Database for AI ******
   [PyPI_version] [PyPI_version] [Documentation_Status] [PyPI_version] [GitHub
                                issues] [codecov]
-   **** Documentation • Getting_Started • API_Reference • Examples • Blog •
-                  Whitepaper • Slack_Community • Twitter ****
+**** Docs • Get_Started • API_Reference • LangChain_&_VectorDBs_Course • Blog •
+                       Whitepaper • Slack • Twitter ****
 *Read this in other languages: [ç®ä½ä¸­æ](README.zh-cn.md)* ## About Deep
 Lake Deep Lake is a Database for AI powered by a unique storage format
 optimized for deep-learning and Large Language Model (LLM) based applications.
 It simplifies the deployment of enterprise-grade LLM-based products by offering
 storage for all data types (embeddings, audio, text, videos, images, pdfs,
 annotations, etc.), querying and vector search, data streaming while training
 models at scale, data versioning and lineage for all workloads, and
```

### Comparing `deeplake-3.6.6/README.md` & `deeplake-3.6.7/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,32 +1,32 @@
 <img src="https://static.scarf.sh/a.png?x-pxid=bc3c57b0-9a65-49fe-b8ea-f711c4d35b82" /><p align="center">
      <img src="https://i.postimg.cc/rsjcWc3S/deeplake-logo.png" width="400"/>
 </h1>
     </br>
     <h1 align="center">Deep Lake: Database for AI
  </h1>
 <p align="center">
-    <a href="https://github.com/activeloopai/Hub/actions/workflows/test-pr-on-label.yml"><img src="https://github.com/activeloopai/Hub/actions/workflows/test-push.yml/badge.svg" alt="PyPI version" height="18"></a>
+    <a href="https://github.com/activeloopai/deeplake/actions/workflows/test-pr-on-label.yml"><img src="https://github.com/activeloopai/deeplake/actions/workflows/test-push.yml/badge.svg" alt="PyPI version" height="18"></a>
     <a href="https://pypi.org/project/deeplake/"><img src="https://badge.fury.io/py/deeplake.svg" alt="PyPI version" height="18"></a>
     <a href='https://docs.deeplake.ai/en/latest/?badge=latest'>
      <img src='https://readthedocs.org/projects/deep-lake/badge/?version=latest' alt='Documentation Status' />
      </a>
     <a href="https://pepy.tech/project/deeplake"><img src="https://static.pepy.tech/badge/deeplake" alt="PyPI version" height="18"></a>
      <a href="https://github.com/activeloopai/deeplake/issues">
     <img alt="GitHub issues" src="https://img.shields.io/github/issues/activeloopai/deeplake"> </a>
     <a href="https://codecov.io/gh/activeloopai/deeplake/branch/main"><img src="https://codecov.io/gh/activeloopai/deeplake/branch/main/graph/badge.svg" alt="codecov" height="18"></a>
   <h3 align="center">
-   <a href="https://docs.activeloop.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Documentation</b></a> &bull;
-   <a href="https://docs.activeloop.ai/getting-started/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Getting Started</b></a> &bull;
+   <a href="https://docs.activeloop.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Docs</b></a> &bull;
+   <a href="https://docs.activeloop.ai/getting-started/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Get Started</b></a> &bull;
    <a href="https://docs.deeplake.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>API Reference</b></a> &bull;  
-   <a href="https://github.com/activeloopai/examples/"><b>Examples</b></a> &bull; 
+   <a href="http://learn.activeloop.ai"><b>LangChain & VectorDBs Course</b></a> &bull;
    <a href="https://www.activeloop.ai/resources/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Blog</b></a> &bull; 
    <a href="https://www.deeplake.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Whitepaper</b></a> &bull;  
-  <a href="http://slack.activeloop.ai"><b>Slack Community</b></a> &bull;
-  <a href="https://twitter.com/intent/tweet?text=The%20dataset%20format%20for%20AI.%20Stream%20data%20to%20PyTorch%20and%20Tensorflow%20datasets&url=https://activeloop.ai/&via=activeloopai&hashtags=opensource,pytorch,tensorflow,data,datascience,datapipelines,activeloop,databaseforAI"><b>Twitter</b></a>
+  <a href="http://slack.activeloop.ai"><b>Slack</b></a> &bull;
+  <a href="https://twitter.com/intent/tweet?url=https%3A%2F%2Factiveloop.ai%2F&via=activeloopai&text=Deep%20Lake%20is%20the%20Database%20for%20all%20AI%20data.%20Check%20it%20out%21&hashtags=DeepLake%2Cactiveloop%2Copensource"><b>Twitter</b></a>
  </h3>
  
 
 *Read this in other languages: [简体中文](README.zh-cn.md)*
 
 ## About Deep Lake
```

#### html2text {}

```diff
@@ -1,14 +1,14 @@
 [https://static.scarf.sh/a.png?x-pxid=bc3c57b0-9a65-49fe-b8ea-f711c4d35b82]
                [https://i.postimg.cc/rsjcWc3S/deeplake-logo.png]
                    ****** Deep Lake: Database for AI ******
   [PyPI_version] [PyPI_version] [Documentation_Status] [PyPI_version] [GitHub
                                issues] [codecov]
-   **** Documentation • Getting_Started • API_Reference • Examples • Blog •
-                  Whitepaper • Slack_Community • Twitter ****
+**** Docs • Get_Started • API_Reference • LangChain_&_VectorDBs_Course • Blog •
+                       Whitepaper • Slack • Twitter ****
 *Read this in other languages: [ç®ä½ä¸­æ](README.zh-cn.md)* ## About Deep
 Lake Deep Lake is a Database for AI powered by a unique storage format
 optimized for deep-learning and Large Language Model (LLM) based applications.
 It simplifies the deployment of enterprise-grade LLM-based products by offering
 storage for all data types (embeddings, audio, text, videos, images, pdfs,
 annotations, etc.), querying and vector search, data streaming while training
 models at scale, data versioning and lineage for all workloads, and
```

### Comparing `deeplake-3.6.6/deeplake/__init__.py` & `deeplake-3.6.7/deeplake/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -75,15 +75,15 @@
     "config",
     "delete",
     "copy",
     "rename",
 ]
 
 
-__version__ = "3.6.6"
+__version__ = "3.6.7"
 warn_if_update_required(__version__)
 __encoded_version__ = np.array(__version__)
 config = {"s3": Config(max_pool_connections=50, connect_timeout=300, read_timeout=300)}
 
 
 deeplake_reporter.tags.append(f"version:{__version__}")
 deeplake_reporter.system_report(publish=True)
```

### Comparing `deeplake-3.6.6/deeplake/api/dataset.py` & `deeplake-3.6.7/deeplake/api/dataset.py`

 * *Files 0% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 from deeplake.auto.unstructured.kaggle import download_kaggle_dataset
 from deeplake.auto.unstructured.image_classification import ImageClassification
 from deeplake.auto.unstructured.coco.coco import CocoDataset
 from deeplake.auto.unstructured.yolo.yolo import YoloDataset
 from deeplake.client.client import DeepLakeBackendClient
 from deeplake.client.log import logger
 from deeplake.core.dataset import Dataset, dataset_factory
+from deeplake.core.tensor import Tensor
 from deeplake.core.meta.dataset_meta import DatasetMeta
 from deeplake.util.connect_dataset import connect_dataset_entry
 from deeplake.util.version_control import (
     load_version_info,
     rebuild_version_info,
     get_parent_and_reset_commit_ids,
     replace_head,
@@ -966,25 +967,25 @@
     def copy(
         src: Union[str, pathlib.Path, Dataset],
         dest: Union[str, pathlib.Path],
         runtime: Optional[dict] = None,
         tensors: Optional[List[str]] = None,
         overwrite: bool = False,
         src_creds=None,
-        token=None,
         dest_creds=None,
+        token=None,
         num_workers: int = 0,
         scheduler="threaded",
         progressbar=True,
         **kwargs,
     ):
         """Copies dataset at ``src`` to ``dest``. Version control history is not included.
 
         Args:
-            src (Union[str, Dataset, pathlib.Path]): The Dataset or the path to the dataset to be copied.
+            src (str, Dataset, pathlib.Path): The Dataset or the path to the dataset to be copied.
             dest (str, pathlib.Path): Destination path to copy to.
             runtime (dict): Parameters for Activeloop DB Engine. Only applicable for hub:// paths.
             tensors (List[str], optional): Names of tensors (and groups) to be copied. If not specified all tensors are copied.
             overwrite (bool): If True and a dataset exists at ``dest``, it will be overwritten. Defaults to ``False``.
             src_creds (dict, str, optional): The string ``ENV`` or a dictionary containing credentials used to access the dataset at the path.
                 - If 'aws_access_key_id', 'aws_secret_access_key', 'aws_session_token' are present, these take precedence over credentials present in the environment or in credentials file. Currently only works with s3 paths.
                 - It supports 'aws_access_key_id', 'aws_secret_access_key', 'aws_session_token', 'endpoint_url', 'aws_region', 'profile_name' as keys.
@@ -999,28 +1000,39 @@
 
         Returns:
             Dataset: New dataset object.
 
         Raises:
             DatasetHandlerError: If a dataset already exists at destination path and overwrite is False.
             UnsupportedParameterException: If a parameter that is no longer supported is specified.
+            DatasetCorruptError: If loading source dataset fails with DatasetCorruptedError.
         """
         if "src_token" in kwargs:
             raise UnsupportedParameterException(
                 "src_token is now not supported. You should use `token` instead."
             )
 
         if "dest_token" in kwargs:
             raise UnsupportedParameterException(
                 "dest_token is now not supported. You should use `token` instead."
             )
 
         if isinstance(src, (str, pathlib.Path)):
             src = convert_pathlib_to_string_if_needed(src)
-            src_ds = deeplake.load(src, read_only=True, creds=src_creds, token=token)
+            try:
+                src_ds = deeplake.load(
+                    src, read_only=True, creds=src_creds, token=token, verbose=False
+                )
+            except DatasetCorruptError as e:
+                raise DatasetCorruptError(
+                    "The source dataset is corrupted.",
+                    "You can try to fix this by loading the dataset with `reset=True` "
+                    "which will attempt to reset uncommitted HEAD changes and load the previous version.",
+                    e.__cause__,
+                )
         else:
             src_ds = src
             src_ds.path = str(src_ds.path)
 
         dest = convert_pathlib_to_string_if_needed(dest)
 
         return src_ds.copy(
@@ -1033,15 +1045,15 @@
             num_workers=num_workers,
             scheduler=scheduler,
             progressbar=progressbar,
         )
 
     @staticmethod
     def deepcopy(
-        src: Union[str, pathlib.Path],
+        src: Union[str, pathlib.Path, Dataset],
         dest: Union[str, pathlib.Path],
         runtime: Optional[Dict] = None,
         tensors: Optional[List[str]] = None,
         overwrite: bool = False,
         src_creds=None,
         dest_creds=None,
         token=None,
@@ -1051,15 +1063,15 @@
         public: bool = False,
         verbose: bool = True,
         **kwargs,
     ):
         """Copies dataset at ``src`` to ``dest`` including version control history.
 
         Args:
-            src (str, pathlib.Path): Path to the dataset to be copied.
+            src (str, pathlib.Path, Dataset): The Dataset or the path to the dataset to be copied.
             dest (str, pathlib.Path): Destination path to copy to.
             runtime (dict): Parameters for Activeloop DB Engine. Only applicable for hub:// paths.
             tensors (List[str], optional): Names of tensors (and groups) to be copied. If not specified all tensors are copied.
             overwrite (bool): If True and a dataset exists at `destination`, it will be overwritten. Defaults to False.
             src_creds (dict, str, optional): The string ``ENV`` or a dictionary containing credentials used to access the dataset at the path.
                 - If 'aws_access_key_id', 'aws_secret_access_key', 'aws_session_token' are present, these take precedence over credentials present in the environment or in credentials file. Currently only works with s3 paths.
                 - It supports 'aws_access_key_id', 'aws_secret_access_key', 'aws_session_token', 'endpoint_url', 'aws_region', 'profile_name' as keys.
@@ -1075,63 +1087,77 @@
             **kwargs: Additional keyword arguments
 
         Returns:
             Dataset: New dataset object.
 
         Raises:
             DatasetHandlerError: If a dataset already exists at destination path and overwrite is False.
-            TypeError: If source is not a path to a dataset.
+            TypeError: If source is not a dataset.
             UnsupportedParameterException: If parameter that is no longer supported is beeing called.
             DatasetCorruptError: If loading source dataset fails with DatasetCorruptedError
         """
 
         if "src_token" in kwargs:
             raise UnsupportedParameterException(
                 "src_token is now not supported. You should use `token` instead."
             )
 
         if "dest_token" in kwargs:
             raise UnsupportedParameterException(
                 "dest_token is now not supported. You should use `token` instead."
             )
 
-        if not isinstance(src, (str, pathlib.Path)):
-            raise TypeError(
-                f"Source for `deepcopy` should be path to a dataset. Got {type(src)}."
-            )
-
-        src = convert_pathlib_to_string_if_needed(src)
-        dest = convert_pathlib_to_string_if_needed(dest)
-
-        verify_dataset_name(dest)
-
         deeplake_reporter.feature_report(
             feature_name="deepcopy",
             parameters={
                 "tensors": tensors,
                 "overwrite": overwrite,
                 "num_workers": num_workers,
                 "scheduler": scheduler,
                 "progressbar": progressbar,
                 "public": public,
                 "verbose": verbose,
             },
         )
 
-        try:
-            src_ds = deeplake.load(
-                src, read_only=True, creds=src_creds, token=token, verbose=False
-            )
-        except DatasetCorruptError as e:
-            raise DatasetCorruptError(
-                "The source dataset is corrupted.",
-                "You can try to fix this by loading the dataset with `reset=True` "
-                "which will attempt to reset uncommitted HEAD changes and load the previous version.",
-                e.__cause__,
-            )
+        dest = convert_pathlib_to_string_if_needed(dest)
+
+        if isinstance(src, (str, pathlib.Path)):
+            src = convert_pathlib_to_string_if_needed(src)
+            try:
+                src_ds = deeplake.load(
+                    src, read_only=True, creds=src_creds, token=token, verbose=False
+                )
+            except DatasetCorruptError as e:
+                raise DatasetCorruptError(
+                    "The source dataset is corrupted.",
+                    "You can try to fix this by loading the dataset with `reset=True` "
+                    "which will attempt to reset uncommitted HEAD changes and load the previous version.",
+                    e.__cause__,
+                )
+        else:
+            if not isinstance(src, Dataset):
+                raise TypeError(
+                    f"The specified ``src`` is not an allowed type. Please specify a dataset or a materialized dataset view."
+                )
+
+            if not src.index.is_trivial():
+                raise TypeError(
+                    "Deepcopy is not supported for unmaterialized dataset views, i.e. slices of datasets. Please specify a dataset or a materialized dataset view."
+                )
+
+            if not src._is_root():
+                raise TypeError(
+                    "Deepcopy is not supported for individual groups. Please specify a dataset."
+                )
+
+            src_ds = src
+
+        verify_dataset_name(dest)
+
         src_storage = get_base_storage(src_ds.storage)
 
         db_engine = parse_runtime_parameters(dest, runtime)["tensor_db"]
         dest_storage, cache_chain = get_storage_and_cache_chain(
             dest,
             db_engine=db_engine,
             creds=dest_creds,
@@ -1152,15 +1178,15 @@
         metas: Dict[str, DatasetMeta] = {}
 
         def copy_func(keys, progress_callback=None):
             cache = generate_chain(
                 src_storage,
                 memory_cache_size=DEFAULT_MEMORY_CACHE_SIZE,
                 local_cache_size=DEFAULT_LOCAL_CACHE_SIZE,
-                path=src,
+                path=src_ds.path,
             )
             for key in keys:
                 val = metas.get(key) or cache[key]
                 if isinstance(val, DeepLakeMemoryObject):
                     dest_storage[key] = val.tobytes()
                 else:
                     dest_storage[key] = val
```

### Comparing `deeplake-3.6.6/deeplake/api/info.py` & `deeplake-3.6.7/deeplake/api/info.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/link.py` & `deeplake-3.6.7/deeplake/api/link.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/link_tiled.py` & `deeplake-3.6.7/deeplake/api/link_tiled.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/read.py` & `deeplake-3.6.7/deeplake/api/read.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_access_method.py` & `deeplake-3.6.7/deeplake/api/tests/test_access_method.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_agreement.py` & `deeplake-3.6.7/deeplake/api/tests/test_agreement.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_api.py` & `deeplake-3.6.7/deeplake/api/tests/test_api.py`

 * *Files 2% similar despite different names*

```diff
@@ -1006,14 +1006,85 @@
     "path,hub_token",
     [
         ["local_path", "hub_cloud_dev_token"],
         ["hub_cloud_path", "hub_cloud_dev_token"],
     ],
     indirect=True,
 )
+def test_deepcopy(path, hub_token):
+    src_path = "_".join((path, "src"))
+    dest_path = "_".join((path, "dest"))
+
+    src_ds = deeplake.empty(src_path, overwrite=True, token=hub_token)
+    dest_ds = deeplake.empty(dest_path, overwrite=True, token=hub_token)
+
+    with src_ds:
+        src_ds.info.update(key=0)
+
+        src_ds.create_tensor("a", htype="image", sample_compression="png")
+        src_ds.create_tensor("b", htype="class_label")
+        src_ds.create_tensor("c")
+        src_ds.create_tensor("d", dtype=bool)
+        src_ds.create_group("g")
+
+        src_ds.d.info.update(key=1)
+
+        src_ds["a"].append(np.ones((28, 28), dtype="uint8"))
+        src_ds["b"].append(0)
+
+    deeplake.deepcopy(
+        src_ds,
+        dest_path,
+        overwrite=True,
+        token=hub_token,
+        num_workers=0,
+    )
+
+    deeplake.deepcopy(
+        src_path,
+        dest_path,
+        overwrite=True,
+        token=hub_token,
+        num_workers=1,
+    )
+
+    with pytest.raises(TypeError):
+        deeplake.deepcopy(
+            src_ds.a,
+            dest_path,
+            overwrite=True,
+            token=hub_token,
+            num_workers=0,
+        )
+    with pytest.raises(TypeError):
+        deeplake.deepcopy(
+            src_ds.g,
+            dest_path,
+            overwrite=True,
+            token=hub_token,
+            num_workers=0,
+        )
+    with pytest.raises(TypeError):
+        deeplake.deepcopy(
+            src_ds[0],
+            dest_path,
+            overwrite=True,
+            token=hub_token,
+            num_workers=0,
+        )
+
+
+@pytest.mark.parametrize(
+    "path,hub_token",
+    [
+        ["local_path", "hub_cloud_dev_token"],
+        ["hub_cloud_path", "hub_cloud_dev_token"],
+    ],
+    indirect=True,
+)
 def test_deepcopy_errors(path, hub_token):
     src_path = "_".join((path, "src"))
     dest_path = "_".join((path, "dest"))
 
     src_ds = deeplake.empty(src_path, overwrite=True, token=hub_token)
     dest_ds = deeplake.empty(dest_path, overwrite=True, token=hub_token)
```

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_api_tiling.py` & `deeplake-3.6.7/deeplake/api/tests/test_api_tiling.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_api_with_compression.py` & `deeplake-3.6.7/deeplake/api/tests/test_api_with_compression.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_chunk_sizes.py` & `deeplake-3.6.7/deeplake/api/tests/test_chunk_sizes.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_connect_datasets.py` & `deeplake-3.6.7/deeplake/api/tests/test_connect_datasets.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_dataset.py` & `deeplake-3.6.7/deeplake/api/tests/test_dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_dicom.py` & `deeplake-3.6.7/deeplake/api/tests/test_dicom.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_downsample.py` & `deeplake-3.6.7/deeplake/api/tests/test_downsample.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_events.py` & `deeplake-3.6.7/deeplake/api/tests/test_events.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_grayscale.py` & `deeplake-3.6.7/deeplake/api/tests/test_grayscale.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_info.py` & `deeplake-3.6.7/deeplake/api/tests/test_info.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_insertion_out_of_order.py` & `deeplake-3.6.7/deeplake/api/tests/test_insertion_out_of_order.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_json.py` & `deeplake-3.6.7/deeplake/api/tests/test_json.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_link.py` & `deeplake-3.6.7/deeplake/api/tests/test_link.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_link_tiled.py` & `deeplake-3.6.7/deeplake/api/tests/test_link_tiled.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_linking.py` & `deeplake-3.6.7/deeplake/api/tests/test_linking.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_mesh.py` & `deeplake-3.6.7/deeplake/api/tests/test_mesh.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_meta.py` & `deeplake-3.6.7/deeplake/api/tests/test_meta.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_nifti.py` & `deeplake-3.6.7/deeplake/api/tests/test_nifti.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_none.py` & `deeplake-3.6.7/deeplake/api/tests/test_none.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_partial_upload.py` & `deeplake-3.6.7/deeplake/api/tests/test_partial_upload.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_pickle.py` & `deeplake-3.6.7/deeplake/api/tests/test_pickle.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_point_cloud.py` & `deeplake-3.6.7/deeplake/api/tests/test_point_cloud.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_polygons.py` & `deeplake-3.6.7/deeplake/api/tests/test_polygons.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_pop.py` & `deeplake-3.6.7/deeplake/api/tests/test_pop.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_readonly.py` & `deeplake-3.6.7/deeplake/api/tests/test_readonly.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_rechunk.py` & `deeplake-3.6.7/deeplake/api/tests/test_rechunk.py`

 * *Files 0% similar despite different names*

```diff
@@ -331,9 +331,9 @@
     ds.pop()
 
     assert ds.text.chunk_engine.num_chunks == 1
     assert ds.json.chunk_engine.num_chunks == 1
     assert ds.list.chunk_engine.num_chunks == 1
 
     assert ds.text[-1].data()["value"] == "hello world"
-    assert ds.json[-1].data()["value"] == [{"a": 2, "b": 4}]
+    assert ds.json[-1].data()["value"] == {"a": 2, "b": 4}
     assert ds.list[-1].data()["value"] == [4, 5, 6]
```

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_reset.py` & `deeplake-3.6.7/deeplake/api/tests/test_reset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_sample_info.py` & `deeplake-3.6.7/deeplake/api/tests/test_sample_info.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_text.py` & `deeplake-3.6.7/deeplake/api/tests/test_text.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_video.py` & `deeplake-3.6.7/deeplake/api/tests/test_video.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tests/test_views.py` & `deeplake-3.6.7/deeplake/api/tests/test_views.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/api/tiled.py` & `deeplake-3.6.7/deeplake/api/tiled.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/structured/base.py` & `deeplake-3.6.7/deeplake/auto/structured/base.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/structured/dataframe.py` & `deeplake-3.6.7/deeplake/auto/structured/dataframe.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/tests/test_coco_template.py` & `deeplake-3.6.7/deeplake/auto/tests/test_coco_template.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/tests/test_ingestion.py` & `deeplake-3.6.7/deeplake/auto/tests/test_ingestion.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/tests/test_kaggle.py` & `deeplake-3.6.7/deeplake/auto/tests/test_kaggle.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/tests/test_yolo_template.py` & `deeplake-3.6.7/deeplake/auto/tests/test_yolo_template.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/base.py` & `deeplake-3.6.7/deeplake/auto/unstructured/base.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/coco/coco.py` & `deeplake-3.6.7/deeplake/auto/unstructured/coco/coco.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/coco/constants.py` & `deeplake-3.6.7/deeplake/auto/unstructured/coco/constants.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/coco/convert.py` & `deeplake-3.6.7/deeplake/auto/unstructured/coco/convert.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/coco/utils.py` & `deeplake-3.6.7/deeplake/auto/unstructured/coco/utils.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/image_classification.py` & `deeplake-3.6.7/deeplake/auto/unstructured/image_classification.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/kaggle.py` & `deeplake-3.6.7/deeplake/auto/unstructured/kaggle.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/util.py` & `deeplake-3.6.7/deeplake/auto/unstructured/util.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/yolo/utils.py` & `deeplake-3.6.7/deeplake/auto/unstructured/yolo/utils.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/auto/unstructured/yolo/yolo.py` & `deeplake-3.6.7/deeplake/auto/unstructured/yolo/yolo.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/cli/auth.py` & `deeplake-3.6.7/deeplake/cli/auth.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/cli/test_cli.py` & `deeplake-3.6.7/deeplake/cli/test_cli.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/client/client.py` & `deeplake-3.6.7/deeplake/client/client.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/client/config.py` & `deeplake-3.6.7/deeplake/client/config.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/client/log.py` & `deeplake-3.6.7/deeplake/client/log.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/client/test_client.py` & `deeplake-3.6.7/deeplake/client/test_client.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/client/utils.py` & `deeplake-3.6.7/deeplake/client/utils.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/compression.py` & `deeplake-3.6.7/deeplake/compression.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/constants.py` & `deeplake-3.6.7/deeplake/constants.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk/base_chunk.py` & `deeplake-3.6.7/deeplake/core/chunk/base_chunk.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk/chunk_compressed_chunk.py` & `deeplake-3.6.7/deeplake/core/chunk/chunk_compressed_chunk.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk/sample_compressed_chunk.py` & `deeplake-3.6.7/deeplake/core/chunk/sample_compressed_chunk.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk/test_chunk_compressed.py` & `deeplake-3.6.7/deeplake/core/chunk/test_chunk_compressed.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk/test_sample_compressed.py` & `deeplake-3.6.7/deeplake/core/chunk/test_sample_compressed.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk/test_uncompressed.py` & `deeplake-3.6.7/deeplake/core/chunk/test_uncompressed.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk/uncompressed_chunk.py` & `deeplake-3.6.7/deeplake/core/chunk/uncompressed_chunk.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/chunk_engine.py` & `deeplake-3.6.7/deeplake/core/chunk_engine.py`

 * *Files 0% similar despite different names*

```diff
@@ -1305,15 +1305,15 @@
                 operator,
                 link_callback=link_callback,
             )
         except Exception as e:
             raise SampleUpdateError(self.name) from e
 
     def _get_samples_to_move(self, chunk) -> List[Sample]:
-        decompress = isinstance(chunk, ChunkCompressedChunk)
+        decompress = isinstance(chunk, ChunkCompressedChunk) or self.is_text_like
         samples_to_move: List[Sample] = []
         sum_bytes = 0
 
         for idx in range(chunk.num_samples - 1, 1, -1):
             sample_data = chunk.read_sample(idx, decompress=decompress)
             sum_bytes += len(sample_data)
             if sum_bytes > int(RANDOM_MAX_ALLOWED_CHUNK_SIZE / 2):
@@ -1323,15 +1323,15 @@
                 sample_data, sample_shape, chunk.compression, chunk.dtype, decompress
             )
             samples_to_move.append(new_sample)
         samples_to_move.reverse()
         return samples_to_move
 
     def _get_chunk_samples(self, chunk) -> List[Optional[Sample]]:
-        decompress = isinstance(chunk, ChunkCompressedChunk)
+        decompress = isinstance(chunk, ChunkCompressedChunk) or self.is_text_like
         all_samples_in_chunk: List[Optional[Sample]] = []
 
         for idx in range(chunk.num_samples):
             sample_data = chunk.read_sample(idx, decompress=decompress)
             try:
                 sample_shape = chunk.shapes_encoder[idx]
             except IndexError:
@@ -1345,33 +1345,35 @@
         return all_samples_in_chunk
 
     def _get_sample_object(
         self, sample_data, sample_shape, compression, dtype, decompress
     ):
         if isinstance(sample_data, Polygons):
             return sample_data
-        if decompress:
-            if self.is_text_like:
-                byts, shape = text_to_bytes(sample_data, dtype, self.tensor_meta.htype)
-                sample = Sample(buffer=byts, shape=shape)
+
+        if self.is_text_like:
+            if self.tensor_meta.is_link:
+                sample = LinkedSample(sample_data)
             else:
-                sample = Sample(array=sample_data, shape=sample_shape)
+                sample = sample_data
+                if self.tensor_meta.htype == "json" and isinstance(sample, np.ndarray):
+                    sample = sample.squeeze()
+            return sample
+
+        if decompress:
+            sample = Sample(array=sample_data, shape=sample_shape)
         else:
+            # sample data should not be an array here
+            assert not isinstance(sample_data, np.ndarray)
             sample = Sample(
                 buffer=sample_data,
                 shape=sample_shape,
                 compression=compression,
                 dtype=dtype,
             )
-
-        if self.is_text_like:
-            sample.htype = self.tensor_meta.htype
-        if self.tensor_meta.is_link:
-            sample.htype = "text"
-            sample = LinkedSample(sample.array[0])
         return sample
 
     def __rechunk(self, chunk: BaseChunk, chunk_row: int):
         samples_to_move = self._get_samples_to_move(chunk=chunk)
         num_samples = len(samples_to_move)
         if num_samples == 0:
             return
@@ -1557,14 +1559,16 @@
 
         enc = self.chunk_id_encoder
         index_length = index.length(self.num_samples)
         samples = make_sequence(samples, index_length)
         verified_samples = self.check_each_sample(samples)
         if self.tensor_meta.htype == "class_label":
             samples = self._convert_class_labels(samples)
+        if self.tensor_meta.htype == "polygon":
+            samples = [Polygons(sample, self.tensor_meta.dtype) for sample in samples]  # type: ignore
         nbytes_after_updates: List[int] = []
         global_sample_indices = tuple(index.values[0].indices(self.num_samples))
         is_sequence = self.is_sequence
         for i, sample in enumerate(samples):  # type: ignore
             sample = None if is_empty_list(sample) else sample
             global_sample_index = global_sample_indices[i]  # TODO!
             if self._is_tiled_sample(global_sample_index):
@@ -1829,38 +1833,51 @@
             shape_enc_size = num_shape_entries * ENTRY_SIZE
             worst_case_header_size += shape_enc_size
             worst_case_header_size += bytes_enc_size
 
         return chunk_id, row, worst_case_header_size
 
     def get_basic_sample(
-        self, global_sample_index, index, fetch_chunks=False, is_tile=False
+        self,
+        global_sample_index,
+        index,
+        fetch_chunks=False,
+        is_tile=False,
+        decompress=True,
     ):
         enc = self.chunk_id_encoder
         chunk_id, row, worst_case_header_size = self.get_chunk_info(
             global_sample_index, fetch_chunks
         )
         local_sample_index = enc.translate_index_relative_to_chunks(global_sample_index)
         chunk = self.get_chunk_from_chunk_id(
             chunk_id, partial_chunk_bytes=worst_case_header_size
         )
+        decompress = decompress or (
+            isinstance(chunk, ChunkCompressedChunk) or len(index) > 1
+        )
         ret = chunk.read_sample(
             local_sample_index,
             cast=self.tensor_meta.htype != "dicom",
             is_tile=is_tile,
+            decompress=decompress,
         )
         if len(index) > 1:
             ret = ret[tuple(entry.value for entry in index.values[1:])]
         return ret
 
-    def get_non_tiled_sample(self, global_sample_index, index, fetch_chunks=False):
+    def get_non_tiled_sample(
+        self, global_sample_index, index, fetch_chunks=False, decompress=True
+    ):
         if self.is_video:
-            return self.get_video_sample(global_sample_index, index)
+            return self.get_video_sample(
+                global_sample_index, index, decompress=decompress
+            )
         return self.get_basic_sample(
-            global_sample_index, index, fetch_chunks=fetch_chunks
+            global_sample_index, index, fetch_chunks=fetch_chunks, decompress=decompress
         )
 
     def get_full_tiled_sample(self, global_sample_index, fetch_chunks=False):
         chunks = self.get_chunks_for_sample(global_sample_index)
         return combine_chunks(chunks, global_sample_index, self.tile_encoder)
 
     def get_partial_tiled_sample(self, global_sample_index, index, fetch_chunks=False):
@@ -1882,30 +1899,39 @@
             otypes=[object],
         )(required_tile_ids)
         sample = coalesce_tiles(tiles, tile_shape, None, self.tensor_meta.dtype)
         sample = sample[sample_index]
         return sample
 
     def get_single_sample(
-        self, global_sample_index, index, fetch_chunks=False, pad_tensor=False
+        self,
+        global_sample_index,
+        index,
+        fetch_chunks=False,
+        pad_tensor=False,
+        decompress=True,
     ):
         if pad_tensor and global_sample_index >= self.tensor_length:
             sample = self.get_empty_sample()
             try:
                 return sample[tuple(entry.value for entry in index.values[1:])]
             except IndexError:
                 return sample
 
         if not self._is_tiled_sample(global_sample_index):
             sample = self.get_non_tiled_sample(
-                global_sample_index, index, fetch_chunks=fetch_chunks
+                global_sample_index,
+                index,
+                fetch_chunks=fetch_chunks,
+                decompress=decompress,
             )
         elif len(index.values) == 1:
             sample = self.get_full_tiled_sample(
-                global_sample_index, fetch_chunks=fetch_chunks
+                global_sample_index,
+                fetch_chunks=fetch_chunks,
             )
         else:
             sample = self.get_partial_tiled_sample(
                 global_sample_index, index, fetch_chunks=fetch_chunks
             )
 
         return sample
@@ -2436,18 +2462,22 @@
         verified_samples: Optional[List] = None
         if self.tensor_meta.htype == "class_label":
             samples = self._convert_class_labels(samples)
         if flat_verified_samples:
             verified_samples = []
             for sample in samples:  # type: ignore
                 verified_sample = []
-                for _ in sample:  # type: ignore
-                    verified_sample.append(flat_verified_samples[i])
+                if isinstance(sample, Iterable):
+                    for _ in sample:  # type: ignore
+                        verified_sample.append(flat_verified_samples[i])
+                        i += 1
+                    verified_samples.append(verified_sample)
+                else:
+                    verified_samples.append(flat_verified_samples[i])
                     i += 1
-                verified_samples.append(verified_sample)
 
         list(
             map(
                 self.commit_diff.update_data,
                 index.values[0].indices(self._sequence_length),
             )
         )
@@ -2720,19 +2750,20 @@
             not index_0.subscriptable()
             and pad_tensor
             and index_0.value >= self.tensor_length  # type: ignore
         ):
             return self.get_empty_sample().shape
 
         num_samples = index_0.length(self._sequence_length or self.num_samples)
-        if index_0.is_trivial() or num_samples == 0:
-            shape = self.shape_interval(index).astuple()
-            return shape
-        elif self.tensor_meta.min_shape == self.tensor_meta.max_shape:
-            shape = self.shape_interval(index).astuple()[1:]
+        if self.tensor_meta.min_shape == self.tensor_meta.max_shape:
+            if index_0.is_trivial() or num_samples == 0:
+                shape = self.shape_interval(index).astuple()
+                return shape
+            else:
+                shape = self.shape_interval(index).astuple()[1:]
         else:
             shape = None
 
         sample_ndim = tensor_ndim - 1
         sample_shapes = np.zeros((num_samples, sample_ndim), dtype=np.int32)
 
         if shape is None or None in shape or self.tensor_meta.is_link:
```

### Comparing `deeplake-3.6.6/deeplake/core/compression.py` & `deeplake-3.6.7/deeplake/core/compression.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/compute/process.py` & `deeplake-3.6.7/deeplake/core/compute/process.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/compute/provider.py` & `deeplake-3.6.7/deeplake/core/compute/provider.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/compute/ray.py` & `deeplake-3.6.7/deeplake/core/compute/ray.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/compute/serial.py` & `deeplake-3.6.7/deeplake/core/compute/serial.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/compute/thread.py` & `deeplake-3.6.7/deeplake/core/compute/thread.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/dataset/__init__.py` & `deeplake-3.6.7/deeplake/core/dataset/__init__.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/dataset/dataset.py` & `deeplake-3.6.7/deeplake/core/dataset/dataset.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,14 +11,16 @@
 import numpy as np
 from time import time, sleep
 from tqdm import tqdm  # type: ignore
 
 import deeplake
 from deeplake.core.index.index import IndexEntry
 from deeplake.core.link_creds import LinkCreds
+from deeplake.core.sample import Sample
+from deeplake.core.linked_sample import LinkedSample
 from deeplake.util.connect_dataset import connect_dataset_entry
 from deeplake.util.downsample import validate_downsampling
 from deeplake.util.version_control import (
     save_version_info,
     integrity_check,
     save_commit_info,
     rebuild_version_info,
@@ -132,14 +134,15 @@
     replace_head,
     reset_and_checkout,
 )
 from deeplake.util.pretty_print import summary_dataset
 from deeplake.core.dataset.view_entry import ViewEntry
 from deeplake.core.dataset.invalid_view import InvalidView
 from deeplake.hooks import dataset_read
+from collections import defaultdict
 from itertools import chain
 import warnings
 import jwt
 
 
 _LOCKABLE_STORAGES = {S3Provider, GCSProvider, AzureProvider, LocalProvider}
 
@@ -574,14 +577,21 @@
                 )
         else:
             raise InvalidKeyTypeError(item)
         if hasattr(self, "_view_entry"):
             ret._view_entry = self._view_entry
         return ret
 
+    def __setitem__(self, item: str, value: Any):
+        if not isinstance(item, str):
+            raise TypeError("Datasets do not support item assignment")
+        tensor = self[item]
+        tensor.index = Index()
+        tensor[self.index] = value
+
     @invalid_view_op
     def create_tensor(
         self,
         name: str,
         htype: str = UNSPECIFIED,
         dtype: Union[str, np.dtype] = UNSPECIFIED,
         sample_compression: str = UNSPECIFIED,
@@ -631,15 +641,15 @@
             create_id_tensor (bool): If ``True``, an associated tensor containing unique ids for each sample will be created. This is useful for merge operations.
             verify (bool): Valid only for link htypes. If ``True``, all links will be verified before they are added to the tensor.
                 If ``False``, links will be added without verification but note that ``create_shape_tensor`` and ``create_sample_info_tensor`` will be set to ``False``.
             exist_ok (bool): If ``True``, the group is created if it does not exist. if ``False``, an error is raised if the group already exists.
             verbose (bool): Shows warnings if ``True``.
             downsampling (tuple[int, int]): If not ``None``, the tensor will be downsampled by the provided factors. For example, ``(2, 5)`` will downsample the tensor by a factor of 2 in both dimensions and create 5 layers of downsampled tensors.
                 Only support for image and mask htypes.
-            tiling_threshold (Optional, int): In MB. Tiles large images if their size exceeds this threshold. Set to -1 to disable tiling.
+            tiling_threshold (Optional, int): In bytes. Tiles large images if their size exceeds this threshold. Set to -1 to disable tiling.
             **kwargs:
                 - ``htype`` defaults can be overridden by passing any of the compatible parameters.
                 - To see all htypes and their correspondent arguments, check out :ref:`Htypes`.
 
         Returns:
             Tensor: The new tensor, which can be accessed by ``dataset[name]`` or ``dataset.name``.
 
@@ -2917,14 +2927,113 @@
                             self[k].pop()
                         except Exception as e2:
                             raise Exception(
                                 "Error while attempting to rollback appends"
                             ) from e2
                     raise e
 
+    def update(self, sample: Dict[str, Any]):
+        """Update existing samples in the dataset with new values.
+
+        Examples:
+
+            >>> ds[0].update({"images": deeplake.read("new_image.png"), "labels": 1})
+
+            >>> new_images = [deeplake.read(f"new_image_{i}.png") for i in range(3)]
+            >>> ds[:3].update({"images": new_images, "labels": [1, 2, 3]})
+
+        Args:
+            sample (dict): Dictionary with tensor names as keys and samples as values.
+
+        Raises:
+            ValueError: If partial update of a sample is attempted.
+            Exception: Error while attempting to rollback updates.
+        """
+        if len(self.index) > 1:
+            raise ValueError(
+                "Cannot make partial updates to samples using `ds.update`. Use `ds.tensor[index] = value` instead."
+            )
+
+        def get_sample_from_engine(
+            engine, idx, is_link, compression, dtype, decompress
+        ):
+            # tiled data will always be decompressed
+            decompress = decompress or engine._is_tiled_sample(idx)
+            if is_link:
+                creds_key = engine.creds_key(idx)
+                item = engine.get_path(idx)
+                return LinkedSample(item, creds_key)
+            item = engine.get_single_sample(idx, self.index, decompress=decompress)
+            shape = engine.read_shape_for_sample(idx)
+            return engine._get_sample_object(
+                item, shape, compression, dtype, decompress
+            )
+
+        # remove update hooks from view base so that the view is not invalidated
+        if self._view_base:
+            saved_update_hooks = self._view_base._update_hooks
+            self._view_base._update_hooks = {}
+        idx = self.index.values[0].value
+        with self:
+            saved = defaultdict(list)
+            try:
+                for k, v in sample.items():
+                    tensor_meta = self[k].meta
+                    dtype = tensor_meta.dtype
+                    sample_compression = tensor_meta.sample_compression
+                    chunk_compression = tensor_meta.chunk_compression
+
+                    compression = sample_compression or chunk_compression
+
+                    engine = self[k].chunk_engine
+
+                    decompress = chunk_compression is not None or engine.is_text_like
+
+                    for idx in self.index.values[0].indices(self[k].num_samples):
+                        if tensor_meta.is_sequence:
+                            old_sample = []
+                            for i in range(*engine.sequence_encoder[idx]):
+                                item = get_sample_from_engine(
+                                    engine,
+                                    i,
+                                    tensor_meta.is_link,
+                                    compression,
+                                    dtype,
+                                    decompress,
+                                )
+                                old_sample.append(item)
+                        else:
+                            old_sample = get_sample_from_engine(
+                                engine,
+                                idx,
+                                tensor_meta.is_link,
+                                compression,
+                                dtype,
+                                decompress,
+                            )
+
+                        saved[k].append(old_sample)
+                    self[k] = v
+            except Exception as e:
+                for k, v in saved.items():
+                    # squeeze
+                    if len(v) == 1:
+                        v = v[0]
+                    try:
+                        self[k] = v
+                    except Exception as e2:
+                        raise Exception(
+                            f"Error while attempting to rollback updates"
+                        ) from e2
+                raise e
+            finally:
+                # restore update hooks
+                if self._view_base:
+                    self._view_base._update_hooks = saved_update_hooks
+
     def _view_hash(self) -> str:
         """Generates a unique hash for a filtered dataset view."""
         return hash_inputs(
             self.path,
             *[e.value for e in self.index.values],
             self.pending_commit_id,
             getattr(self, "_query", None),
```

### Comparing `deeplake-3.6.6/deeplake/core/dataset/deeplake_cloud_dataset.py` & `deeplake-3.6.7/deeplake/core/dataset/deeplake_cloud_dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/dataset/deeplake_query_dataset.py` & `deeplake-3.6.7/deeplake/core/dataset/deeplake_query_dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/dataset/deeplake_query_tensor.py` & `deeplake-3.6.7/deeplake/core/dataset/deeplake_query_tensor.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/dataset/invalid_view.py` & `deeplake-3.6.7/deeplake/core/dataset/invalid_view.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/dataset/view_entry.py` & `deeplake-3.6.7/deeplake/core/dataset/view_entry.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/fast_forwarding.py` & `deeplake-3.6.7/deeplake/core/fast_forwarding.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/index/index.py` & `deeplake-3.6.7/deeplake/core/index/index.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/io.py` & `deeplake-3.6.7/deeplake/core/io.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/ipc.py` & `deeplake-3.6.7/deeplake/core/ipc.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/link_creds.py` & `deeplake-3.6.7/deeplake/core/link_creds.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/linked_chunk_engine.py` & `deeplake-3.6.7/deeplake/core/linked_chunk_engine.py`

 * *Files 1% similar despite different names*

```diff
@@ -129,15 +129,15 @@
                 sample_creds_key, provider_type
             )
             url = storage.get_presigned_url(sample_path, full=True)
         else:
             url = sample_path
         return url, sample_path
 
-    def get_video_sample(self, global_sample_index, index):
+    def get_video_sample(self, global_sample_index, index, decompress=True):
         url, path = self.get_video_url(global_sample_index)
         try:
             squeeze = isinstance(index, int)
             shape = _read_video_shape(url)
             sub_index = index.values[1].value if len(index.values) > 1 else None  # type: ignore
             start, stop, step, reverse = normalize_index(sub_index, shape[0])
             video_sample = _decompress_video(
@@ -203,15 +203,17 @@
             ).array,
             otypes=[object],
         )(required_tile_paths)
         sample = coalesce_tiles(tiles, tile_shape, None)
         sample = sample[sample_index]
         return sample
 
-    def get_basic_sample(self, global_sample_index, index, fetch_chunks=False):
+    def get_basic_sample(
+        self, global_sample_index, index, fetch_chunks=False, decompress=True
+    ):
         sample = self.get_deeplake_read_sample(global_sample_index, fetch_chunks)
         if sample is None:
             return np.ones((0,))
         arr = sample.array
         max_shape = self.tensor_meta.max_shape
         if len(arr.shape) == 2 and max_shape and len(max_shape) == 3:
             arr = arr.reshape(arr.shape + (1,))
```

### Comparing `deeplake-3.6.6/deeplake/core/linked_sample.py` & `deeplake-3.6.7/deeplake/core/linked_sample.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/linked_tiled_sample.py` & `deeplake-3.6.7/deeplake/core/linked_tiled_sample.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/lock.py` & `deeplake-3.6.7/deeplake/core/lock.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/dataset_meta.py` & `deeplake-3.6.7/deeplake/core/meta/dataset_meta.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/base_encoder.py` & `deeplake-3.6.7/deeplake/core/meta/encode/base_encoder.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/byte_positions.py` & `deeplake-3.6.7/deeplake/core/meta/encode/byte_positions.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/chunk_id.py` & `deeplake-3.6.7/deeplake/core/meta/encode/chunk_id.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/creds.py` & `deeplake-3.6.7/deeplake/core/meta/encode/creds.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/pad.py` & `deeplake-3.6.7/deeplake/core/meta/encode/pad.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/sequence.py` & `deeplake-3.6.7/deeplake/core/meta/encode/sequence.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/shape.py` & `deeplake-3.6.7/deeplake/core/meta/encode/shape.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/tests/test_byte_positions_encoder.py` & `deeplake-3.6.7/deeplake/core/meta/encode/tests/test_byte_positions_encoder.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/tests/test_byte_positions_encoder_updates.py` & `deeplake-3.6.7/deeplake/core/meta/encode/tests/test_byte_positions_encoder_updates.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/tests/test_chunk_id_encoder.py` & `deeplake-3.6.7/deeplake/core/meta/encode/tests/test_chunk_id_encoder.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/tests/test_shape_encoder.py` & `deeplake-3.6.7/deeplake/core/meta/encode/tests/test_shape_encoder.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/tests/test_shape_encoder_updates.py` & `deeplake-3.6.7/deeplake/core/meta/encode/tests/test_shape_encoder_updates.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/encode/tile.py` & `deeplake-3.6.7/deeplake/core/meta/encode/tile.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/meta/tensor_meta.py` & `deeplake-3.6.7/deeplake/core/meta/tensor_meta.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/partial_reader.py` & `deeplake-3.6.7/deeplake/core/partial_reader.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/partial_sample.py` & `deeplake-3.6.7/deeplake/core/partial_sample.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/polygon.py` & `deeplake-3.6.7/deeplake/core/polygon.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/query/autocomplete.py` & `deeplake-3.6.7/deeplake/core/query/autocomplete.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/query/filter.py` & `deeplake-3.6.7/deeplake/core/query/filter.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/query/query.py` & `deeplake-3.6.7/deeplake/core/query/query.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/sample.py` & `deeplake-3.6.7/deeplake/core/sample.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/serialize.py` & `deeplake-3.6.7/deeplake/core/serialize.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/azure.py` & `deeplake-3.6.7/deeplake/core/storage/azure.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/deeplake_memory_object.py` & `deeplake-3.6.7/deeplake/core/storage/deeplake_memory_object.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/gcs.py` & `deeplake-3.6.7/deeplake/core/storage/gcs.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/google_drive.py` & `deeplake-3.6.7/deeplake/core/storage/google_drive.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/local.py` & `deeplake-3.6.7/deeplake/core/storage/local.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/lru_cache.py` & `deeplake-3.6.7/deeplake/core/storage/lru_cache.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/memory.py` & `deeplake-3.6.7/deeplake/core/storage/memory.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/provider.py` & `deeplake-3.6.7/deeplake/core/storage/provider.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/storage/s3.py` & `deeplake-3.6.7/deeplake/core/storage/s3.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tensor.py` & `deeplake-3.6.7/deeplake/core/tensor.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tensor_link.py` & `deeplake-3.6.7/deeplake/core/tensor_link.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/test_serialize.py` & `deeplake-3.6.7/deeplake/core/test_serialize.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tests/test_compression.py` & `deeplake-3.6.7/deeplake/core/tests/test_compression.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tests/test_compute.py` & `deeplake-3.6.7/deeplake/core/tests/test_compute.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tests/test_deeplake_indra_dataset.py` & `deeplake-3.6.7/deeplake/core/tests/test_deeplake_indra_dataset.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,18 +9,18 @@
 
 from deeplake.core.dataset.deeplake_query_dataset import DeepLakeQueryDataset
 import random
 import pytest
 
 
 @requires_libdeeplake
-def test_indexing(local_ds_generator):
+def test_indexing(local_auth_ds_generator):
     from deeplake.enterprise.convert_to_libdeeplake import dataset_to_libdeeplake
 
-    deeplake_ds = local_ds_generator()
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         for i in range(1000):
             deeplake_ds.label.append(int(100 * random.uniform(0.0, 1.0)))
 
     indra_ds = dataset_to_libdeeplake(deeplake_ds)
     deeplake_indra_ds = DeepLakeQueryDataset(deeplake_ds=deeplake_ds, indra_ds=indra_ds)
@@ -54,18 +54,18 @@
 
     assert np.all(
         deeplake_indra_ds[(0, 1),].label.numpy() == indra_ds.label[(0, 1),].numpy()
     )
 
 
 @requires_libdeeplake
-def test_save_view(local_ds_generator):
+def test_save_view(local_auth_ds_generator):
     from deeplake.enterprise.convert_to_libdeeplake import dataset_to_libdeeplake
 
-    deeplake_ds = local_ds_generator()
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         for i in range(1000):
             deeplake_ds.label.append(int(100 * random.uniform(0.0, 1.0)))
 
     deeplake_ds.commit("First")
 
@@ -75,31 +75,31 @@
     assert (
         deeplake_indra_ds.base_storage["queries.json"]
         == deeplake_ds.base_storage["queries.json"]
     )
 
 
 @requires_libdeeplake
-def test_empty_token_exception(local_ds):
+def test_empty_token_exception(local_auth_ds):
     from deeplake.enterprise.convert_to_libdeeplake import dataset_to_libdeeplake
 
-    with local_ds:
-        local_ds.create_tensor("label", htype="generic", dtype=np.int32)
+    with local_auth_ds:
+        local_auth_ds.create_tensor("label", htype="generic", dtype=np.int32)
 
-    loaded = deeplake.load(local_ds.path, token="")
+    loaded = deeplake.load(local_auth_ds.path, token="")
 
     with pytest.raises(EmptyTokenException):
         dss = dataset_to_libdeeplake(loaded)
 
 
 @requires_libdeeplake
-def test_load_view(local_ds_generator):
+def test_load_view(local_auth_ds_generator):
     from deeplake.enterprise.convert_to_libdeeplake import dataset_to_libdeeplake
 
-    deeplake_ds = local_ds_generator()
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         deeplake_ds.create_tensor(
             "image", htype="image", dtype=np.uint8, sample_compression="jpg"
         )
         for i in range(100):
             deeplake_ds.label.append(i % 10)
@@ -140,18 +140,18 @@
         iss.append(i)
 
     assert iss == [0, 1, 2]
     assert np.all(indra_ds.image.numpy() == deeplake_indra_ds.image.numpy())
 
 
 @requires_libdeeplake
-def test_query(local_ds_generator):
+def test_query(local_auth_ds_generator):
     from deeplake.enterprise.convert_to_libdeeplake import dataset_to_libdeeplake
 
-    deeplake_ds = local_ds_generator()
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         deeplake_ds.create_tensor(
             "image", htype="image", dtype=np.uint8, sample_compression="jpg"
         )
         for i in range(100):
             deeplake_ds.label.append(int(i / 10))
@@ -174,18 +174,18 @@
     arr = view2.label.numpy()
     assert len(arr) == 10
     for a in arr:
         assert np.all(a == 2)
 
 
 @requires_libdeeplake
-def test_metadata(local_ds_generator):
+def test_metadata(local_auth_ds_generator):
     from deeplake.enterprise.convert_to_libdeeplake import dataset_to_libdeeplake
 
-    deeplake_ds = local_ds_generator()
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         deeplake_ds.create_tensor(
             "image", htype="image", dtype=np.uint8, sample_compression="jpeg"
         )
         deeplake_ds.create_tensor("none_metadata")
         deeplake_ds.create_tensor(
@@ -205,34 +205,34 @@
     assert deeplake_indra_ds.sequence.sample_compression == None
     assert deeplake_indra_ds.none_metadata.htype == None
     assert deeplake_indra_ds.none_metadata.dtype == None
     assert deeplake_indra_ds.none_metadata.sample_compression == None
 
 
 @requires_libdeeplake
-def test_accessing_data(local_ds_generator):
+def test_accessing_data(local_auth_ds_generator):
     from deeplake.enterprise.convert_to_libdeeplake import dataset_to_libdeeplake
 
-    deeplake_ds = local_ds_generator()
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         for i in range(1000):
             deeplake_ds.label.append(int(100 * random.uniform(0.0, 1.0)))
 
     indra_ds = dataset_to_libdeeplake(deeplake_ds)
     deeplake_indra_ds = DeepLakeQueryDataset(deeplake_ds=deeplake_ds, indra_ds=indra_ds)
 
     assert np.all(
         np.isclose(deeplake_indra_ds.label.numpy(), deeplake_indra_ds["label"].numpy())
     )
 
 
 @requires_libdeeplake
-def test_sequences_accessing_data(local_ds_generator):
-    deeplake_ds = local_ds_generator()
+def test_sequences_accessing_data(local_auth_ds_generator):
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         for i in range(200):
             deeplake_ds.label.append(int(i / 101))
         deeplake_ds.create_tensor(
             "image", htype="image", sample_compression="jpeg", dtype=np.uint8
         )
@@ -251,16 +251,16 @@
     assert deeplake_indra_ds[1, 98].image.shape == [20, 10, 3]
     assert deeplake_indra_ds[1].image.numpy().shape == (99,)
     assert deeplake_indra_ds[1].image.numpy()[0].shape == (10, 10, 3)
     assert deeplake_indra_ds[1].image.numpy()[98].shape == (20, 10, 3)
 
 
 @requires_libdeeplake
-def test_random_split(local_ds_generator):
-    deeplake_ds = local_ds_generator()
+def test_random_split(local_auth_ds_generator):
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         for i in range(1000):
             deeplake_ds.label.append(int(i % 100))
 
     deeplake_indra_ds = deeplake_ds.query("SELECT * GROUP BY label")
 
@@ -294,16 +294,16 @@
     assert len(val) == 10
     l = val.dataloader().pytorch().shuffle()
     for b in l:
         pass
 
 
 @requires_libdeeplake
-def test_virtual_tensors(local_ds_generator):
-    deeplake_ds = local_ds_generator()
+def test_virtual_tensors(local_auth_ds_generator):
+    deeplake_ds = local_auth_ds_generator()
     with deeplake_ds:
         deeplake_ds.create_tensor("label", htype="generic", dtype=np.int32)
         deeplake_ds.create_tensor("embeddings", htype="generic", dtype=np.float32)
         deeplake_ds.create_tensor("text", htype="text")
         deeplake_ds.create_tensor("json", htype="json")
         for i in range(100):
             count = i % 5
```

### Comparing `deeplake-3.6.6/deeplake/core/tests/test_io.py` & `deeplake-3.6.7/deeplake/core/tests/test_io.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tests/test_locking.py` & `deeplake-3.6.7/deeplake/core/tests/test_locking.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tests/test_readonly.py` & `deeplake-3.6.7/deeplake/core/tests/test_readonly.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tests/test_serialize.py` & `deeplake-3.6.7/deeplake/core/tests/test_serialize.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tiling/deserialize.py` & `deeplake-3.6.7/deeplake/core/tiling/deserialize.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tiling/optimizer.py` & `deeplake-3.6.7/deeplake/core/tiling/optimizer.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tiling/sample_tiles.py` & `deeplake-3.6.7/deeplake/core/tiling/sample_tiles.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tiling/serialize.py` & `deeplake-3.6.7/deeplake/core/tiling/serialize.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tiling/test_optimizer.py` & `deeplake-3.6.7/deeplake/core/tiling/test_optimizer.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/tiling/test_serialize.py` & `deeplake-3.6.7/deeplake/core/tiling/test_serialize.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/transform/test_transform.py` & `deeplake-3.6.7/deeplake/core/transform/test_transform.py`

 * *Files 0% similar despite different names*

```diff
@@ -1475,14 +1475,34 @@
         assert len(ds["boxes"]) == 40
         assert ds["boxes"].meta.min_shape == [1, 4]
         assert ds["boxes"].meta.max_shape == [20, 4]
 
         assert ds["labels"].numpy().shape == (40, 10)
 
 
+def test_ds_update(local_ds):
+    @deeplake.compute
+    def update_ds(sample_in, ds):
+        i = sample_in.pop("index")
+        ds[i].update(sample_in)
+
+    with local_ds as ds:
+        ds.create_tensor("abc")
+        ds.create_tensor("xyz")
+
+        ds.abc.extend([1, 2, 3, 4, 5])
+        ds.xyz.extend([1, 2, 3, 4, 5])
+
+    samples = [{"abc": 1, "xyz": 2, "index": 0}, {"abc": 3, "xyz": 4, "index": 1}]
+
+    with pytest.raises(TransformError) as e:
+        update_ds().eval(samples, ds, num_workers=TRANSFORM_TEST_NUM_WORKERS)
+        assert isinstance(e.__cause__, NotImplementedError)
+
+
 def test_all_samples_skipped(local_ds):
     @deeplake.compute
     def upload(stuff, ds):
         if isinstance(stuff["images"], str):
             sample = deeplake.read(stuff["images"])
         else:
             sample = stuff["images"]
```

### Comparing `deeplake-3.6.6/deeplake/core/transform/transform.py` & `deeplake-3.6.7/deeplake/core/transform/transform.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/transform/transform_dataset.py` & `deeplake-3.6.7/deeplake/core/transform/transform_dataset.py`

 * *Files 1% similar despite different names*

```diff
@@ -75,14 +75,17 @@
 
         for k in self.tensors:
             if k in sample:
                 self[k].append(sample[k])
             elif append_empty:
                 self[k].append(None)
 
+    def update(self, sample):
+        raise NotImplementedError("ds.update is not supported in transforms.")
+
     def item_added(self, item):
         if isinstance(item, Sample):
             sizeof_item = len(item.buffer)
         elif isinstance(item, LinkedSample):
             sizeof_item = len(item.path)
         elif isinstance(item, np.ndarray):
             sizeof_item = item.nbytes
```

### Comparing `deeplake-3.6.6/deeplake/core/transform/transform_tensor.py` & `deeplake-3.6.7/deeplake/core/transform/transform_tensor.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/__init__.py` & `deeplake-3.6.7/deeplake/core/vectorstore/__init__.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/deeplake_vectorstore.py` & `deeplake-3.6.7/deeplake/core/vectorstore/deeplake_vectorstore.py`

 * *Files 1% similar despite different names*

```diff
@@ -35,15 +35,16 @@
         embedding_function: Optional[Callable] = None,
         read_only: Optional[bool] = False,
         ingestion_batch_size: int = 1000,
         num_workers: int = 0,
         exec_option: str = "python",
         token: Optional[str] = None,
         overwrite: bool = False,
-        verbose=True,
+        verbose: bool = True,
+        runtime: Optional[Dict] = None,
         **kwargs: Any,
     ) -> None:
         """Creates an empty VectorStore or loads an existing one if it exists at the specified ``path``.
 
         Examples:
             >>> # Create a vector store with default tensors
             >>> data = VectorStore(
@@ -78,18 +79,20 @@
             read_only (bool, optional):  Opens dataset in read-only mode if True. Defaults to False.
             num_workers (int): Number of workers to use for parallel ingestion.
             ingestion_batch_size (int): Batch size to use for parallel ingestion.
             exec_option (str): Default method for search execution. It could be either It could be either ``"python"``, ``"compute_engine"`` or ``"tensor_db"``. Defaults to ``"python"``.
 
                 - ``python`` - Pure-python implementation that runs on the client and can be used for data stored anywhere. WARNING: using this option with big datasets is discouraged because it can lead to memory issues.
                 - ``compute_engine`` - Performant C++ implementation of the Deep Lake Compute Engine that runs on the client and can be used for any data stored in or connected to Deep Lake. It cannot be used with in-memory or local datasets.
-                - ``tensor_db`` - Performant and fully-hosted Managed Tensor Database that is responsible for storage and query execution. Only available for data stored in the Deep Lake Managed Database. Store datasets in this database by specifying runtime = {"db_engine": True} during dataset creation.
+                - ``tensor_db`` - Performant and fully-hosted Managed Tensor Database that is responsible for storage and query execution. Only available for data stored in the Deep Lake Managed Database. Store datasets in this database by specifying runtime = {"tensor_db": True} during dataset creation.
             token (str, optional): Activeloop token, used for fetching user credentials. This is Optional, tokens are normally autogenerated. Defaults to None.
             overwrite (bool): If set to True this overwrites the Vector Store if it already exists. Defaults to False.
             verbose (bool): Whether to print summary of the dataset created. Defaults to True.
+            runtime (Dict, optional): Parameters for creating the Vector Store in Deep Lake's Managed Tensor Database. Not applicable when loading an existing Vector Store. To create a Vector Store in the Managed Tensor Database, set `runtime = {"tensor_db": True}`.
+
             **kwargs (Any): Additional keyword arguments.
 
         ..
             # noqa: DAR101
 
         Danger:
             Setting ``overwrite`` to ``True`` will delete all of your data if the Vector Store exists! Be very careful when setting this parameter.
@@ -105,14 +108,15 @@
                 "num_workers": num_workers,
                 "overwrite": overwrite,
                 "read_only": read_only,
                 "ingestion_batch_size": ingestion_batch_size,
                 "exec_option": exec_option,
                 "token": token,
                 "verbose": verbose,
+                "runtime": runtime,
             },
             token=token,
         )
 
         self.ingestion_batch_size = ingestion_batch_size
         self.num_workers = num_workers
         creds = {"creds": kwargs["creds"]} if "creds" in kwargs else {}
@@ -122,14 +126,15 @@
             token,
             creds,
             logger,
             read_only,
             exec_option,
             embedding_function,
             overwrite,
+            runtime,
             **kwargs,
         )
         self.embedding_function = embedding_function
         self.exec_option = exec_option
         self.verbose = verbose
         self.tensor_params = tensor_params
 
@@ -336,15 +341,15 @@
                 - ``Dict`` - Key-value search on tensors of htype json, evaluated on an AND basis (a sample must satisfy all key-value filters to be True) Dict = {"tensor_name_1": {"key": value}, "tensor_name_2": {"key": value}}
                 - ``Function`` - Any function that is compatible with :meth:`Dataset.filter <deeplake.core.dataset.Dataset.filter>`.
 
             exec_option (Optional[str]): Method for search execution. It could be either ``"python"``, ``"compute_engine"`` or ``"tensor_db"``. Defaults to ``"python"``.
 
                 - ``python`` - Pure-python implementation that runs on the client and can be used for data stored anywhere. WARNING: using this option with big datasets is discouraged because it can lead to memory issues.
                 - ``compute_engine`` - Performant C++ implementation of the Deep Lake Compute Engine that runs on the client and can be used for any data stored in or connected to Deep Lake. It cannot be used with in-memory or local datasets.
-                - ``tensor_db`` - Performant and fully-hosted Managed Tensor Database that is responsible for storage and query execution. Only available for data stored in the Deep Lake Managed Database. Store datasets in this database by specifying runtime = {"db_engine": True} during dataset creation.
+                - ``tensor_db`` - Performant and fully-hosted Managed Tensor Database that is responsible for storage and query execution. Only available for data stored in the Deep Lake Managed Database. Store datasets in this database by specifying runtime = {"tensor_db": True} during dataset creation.
             embedding_tensor (str): Name of tensor with embeddings. Defaults to "embedding".
             return_tensors (Optional[List[str]]): List of tensors to return data for. Defaults to None. If None, all tensors are returned.
             return_view (bool): Return a Deep Lake dataset view that satisfied the search parameters, instead of a dictinary with data. Defaults to False.
 
         ..
             # noqa: DAR101
```

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/test_deeplake_vectorstore.py` & `deeplake-3.6.7/deeplake/core/vectorstore/test_deeplake_vectorstore.py`

 * *Files 2% similar despite different names*

```diff
@@ -7,16 +7,18 @@
     VectorStore,
 )
 from deeplake.core.vectorstore import utils
 from deeplake.tests.common import requires_libdeeplake
 from deeplake.constants import (
     DEFAULT_VECTORSTORE_TENSORS,
 )
+from deeplake.util.exceptions import IncorrectEmbeddingShapeError
 
 from math import isclose
+import uuid
 import os
 
 EMBEDDING_DIM = 100
 NUMBER_OF_DATA = 10
 # create data
 texts, embeddings, ids, metadatas, images = utils.create_data(
     number_of_data=NUMBER_OF_DATA, embedding_dim=EMBEDDING_DIM
@@ -40,14 +42,19 @@
     return [np.zeros(embedding_dim) for i in range(len(text))]
 
 
 def embedding_fn4(text, embedding_dim=EMBEDDING_DIM):
     return np.zeros((1, EMBEDDING_DIM))  # pragma: no cover
 
 
+def embedding_fn5(text, embedding_dim=EMBEDDING_DIM):
+    """Returns embedding in List[np.ndarray] format"""
+    return [np.zeros(i) for i in range(len(text))]
+
+
 def test_id_backward_compatibility(local_path):
     num_of_items = 10
     embedding_dim = 100
 
     ids = [f"{i}" for i in range(num_of_items)]
     embedding = [np.zeros(embedding_dim) for i in range(num_of_items)]
     text = ["aadfv" for i in range(num_of_items)]
@@ -103,14 +110,39 @@
 
     data = vector_store.search(
         embedding=query_embedding, exec_option="python", embedding_tensor="emb_custom"
     )
     assert len(data.keys()) == 3
     assert "texts_custom" in data.keys() and "id" in data.keys()
 
+    vector_store = DeepLakeVectorStore(
+        path=local_path,
+        overwrite=True,
+        tensor_params=[
+            {"name": "texts_custom", "htype": "text"},
+            {"name": "emb_custom", "htype": "embedding"},
+        ],
+        embedding_function=embedding_fn5,
+    )
+
+    with pytest.raises(IncorrectEmbeddingShapeError):
+        vector_store.add(
+            embedding_data=texts,
+            embedding_tensor="emb_custom",
+            texts_custom=texts,
+        )
+
+    texts_extended = texts * 2500
+    with pytest.raises(IncorrectEmbeddingShapeError):
+        vector_store.add(
+            embedding_data=texts_extended,
+            embedding_tensor="emb_custom",
+            texts_custom=texts_extended,
+        )
+
 
 @requires_libdeeplake
 def test_search_basic(local_path, hub_cloud_dev_token):
     """Test basic search features"""
     # Initialize vector store object and add data
     vector_store = DeepLakeVectorStore(
         path=local_path,
@@ -1209,7 +1241,17 @@
     vector_store.add(
         embedding_1=(embedding_fn, texts), embedding_2=(embedding_fn3, texts)
     )
 
     assert len(vector_store.dataset) == 10
     assert len(vector_store.dataset.embedding_1) == 10
     assert len(vector_store.dataset.embedding_2) == 10
+
+
+def test_uuid_fix(local_path):
+    vector_store = VectorStore(local_path, overwrite=True)
+
+    ids = [uuid.uuid4() for _ in range(NUMBER_OF_DATA)]
+
+    vector_store.add(text=texts, id=ids, embedding=embeddings, metadata=metadatas)
+
+    assert vector_store.dataset.id.data()["value"] == list(map(str, ids))
```

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/dataset/dataset.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/dataset/dataset.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,26 +18,28 @@
 from deeplake.core.vectorstore.vector_search.ingestion import ingest_data
 from deeplake.constants import (
     DEFAULT_VECTORSTORE_DEEPLAKE_PATH,
     VECTORSTORE_EXTEND_MAX_SIZE,
     DEFAULT_VECTORSTORE_TENSORS,
     VECTORSTORE_EXTEND_MAX_SIZE_BY_HTYPE,
 )
+from deeplake.util.exceptions import IncorrectEmbeddingShapeError
 
 
 def create_or_load_dataset(
     tensor_params,
     dataset_path,
     token,
     creds,
     logger,
     read_only,
     exec_option,
     embedding_function,
     overwrite,
+    runtime,
     **kwargs,
 ):
     utils.check_indra_installation(
         exec_option=exec_option, indra_installed=_INDRA_INSTALLED
     )
 
     if not overwrite and dataset_exists(dataset_path, token, creds, **kwargs):
@@ -48,25 +50,27 @@
 
         return load_dataset(
             dataset_path,
             token,
             creds,
             logger,
             read_only,
+            runtime,
             **kwargs,
         )
 
     return create_dataset(
         logger,
         tensor_params,
         dataset_path,
         token,
         exec_option,
         embedding_function,
         overwrite,
+        runtime,
         **kwargs,
     )
 
 
 def dataset_exists(dataset_path, token, creds, **kwargs):
     return (
         deeplake.exists(dataset_path, token=token, **creds)
@@ -76,38 +80,47 @@
 
 def load_dataset(
     dataset_path,
     token,
     creds,
     logger,
     read_only,
+    runtime,
     **kwargs,
 ):
     if dataset_path == DEFAULT_VECTORSTORE_DEEPLAKE_PATH:
         logger.warning(
             f"The default deeplake path location is used: {DEFAULT_VECTORSTORE_DEEPLAKE_PATH}"
             " and it is not free. All addtionally added data will be added on"
             " top of already existing deeplake dataset."
         )
-
     dataset = deeplake.load(
         dataset_path,
         token=token,
         read_only=read_only,
         creds=creds,
         verbose=False,
         **kwargs,
     )
-
     check_tensors(dataset)
 
     logger.warning(
         f"Deep Lake Dataset in {dataset_path} already exists, "
         f"loading from the storage"
     )
+
+    if runtime is not None and runtime["tensor_db"] == True:
+        logger.warning(
+            "Specifying runtime option when loading a Vector Store is not supported and this parameter will "
+            "be ignored. If you wanted to create a new Vector Store, please specify a path to a Vector Store "
+            "that does not already exist. To transfer an existing Vector Store to the Managed Tensor Database, "
+            "use the steps in the link below: "
+            "(https://docs.activeloop.ai/enterprise-features/managed-database/migrating-datasets-to-the-tensor-database)."
+        )
+
     return dataset
 
 
 def check_tensors(dataset):
     tensors = dataset.tensors
 
     embedding_tensor_exist = False
@@ -148,19 +161,27 @@
     logger,
     tensor_params,
     dataset_path,
     token,
     exec_option,
     embedding_function,
     overwrite,
+    runtime,
     **kwargs,
 ):
-    runtime = None
-    if exec_option == "tensor_db":
-        runtime = {"tensor_db": True}
+    if exec_option == "tensor_db" and (
+        runtime is None or runtime == {"tensor_db": False}
+    ):
+        raise ValueError(
+            "To execute queries using exec_option = 'tensor_db', "
+            "the Vector Store must be stored in Deep Lake's Managed "
+            "Tensor Database. To create the Vector Store in the Managed "
+            "Tensor Database, specify runtime = {'tensor_db': True} when "
+            "creating the Vector Store."
+        )
 
     dataset = deeplake.empty(
         dataset_path,
         token=token,
         runtime=runtime,
         verbose=False,
         overwrite=overwrite,
@@ -292,15 +313,20 @@
         id = [str(uuid.uuid1()) for _ in range(num_items)]
         tensors[ids_tensor] = id
     else:
         for tensor in not_none_tensors:
             if tensor in ("id", "ids"):
                 break
 
-        tensors[ids_tensor] = not_none_tensors[tensor]
+        tensors[ids_tensor] = list(
+            map(
+                lambda x: str(x) if isinstance(x, uuid.UUID) else x,
+                not_none_tensors[tensor],
+            )
+        )
     return tensors
 
 
 def get_id_tensor(dataset):
     return "ids" if "ids" in dataset.tensors else "id"
 
 
@@ -373,15 +399,19 @@
 
     if len(processed_tensors[first_item]) <= extend_threshold:
         if embedding_function:
             for func, data, tensor in zip(
                 embedding_function, embedding_data, embedding_tensor
             ):
                 embedded_data = func(data)
-                embedded_data = np.array(embedded_data, dtype=np.float32)
+                try:
+                    embedded_data = np.array(embedded_data, dtype=np.float32)
+                except ValueError:
+                    raise IncorrectEmbeddingShapeError()
+
                 if len(embedded_data) == 0:
                     raise ValueError("embedding function returned empty list")
 
                 processed_tensors[tensor] = embedded_data
 
         dataset.extend(processed_tensors)
     else:
```

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/dataset/test_dataset.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/dataset/test_dataset.py`

 * *Files 11% similar despite different names*

```diff
@@ -20,27 +20,27 @@
     model = "random_model"
     deployment = "deployment"
 
     def embed_query(text, embedding_dim=100):
         return [0 for i in range(embedding_dim)]  # pragma: no cover
 
 
-@requires_libdeeplake
 def test_create(caplog, hub_cloud_dev_token):
     # dataset creation
     dataset = dataset_utils.create_or_load_dataset(
         tensor_params=DEFAULT_VECTORSTORE_TENSORS,
         dataset_path="./test-dataset",
         token=None,
         creds={},
         logger=logger,
         read_only=False,
-        exec_option="compute_engine",
         overwrite=True,
         embedding_function=Embedding,
+        runtime=None,
+        exec_option="python",
     )
     assert len(dataset) == 0
     assert set(dataset.tensors.keys()) == {
         "embedding",
         "id",
         "metadata",
         "text",
@@ -57,14 +57,15 @@
         tensor_params=DEFAULT_VECTORSTORE_TENSORS,
         dataset_path="hub://testingacc2/vectorstore_dbengine",
         token=hub_cloud_dev_token,
         creds={},
         logger=logger,
         read_only=False,
         exec_option="tensor_db",
+        runtime={"tensor_db": True},
         overwrite=True,
         embedding_function=Embedding,
     )
     assert len(dataset) == 0
     assert set(dataset.tensors.keys()) == {
         "embedding",
         "id",
@@ -74,28 +75,47 @@
     assert dataset.embedding.info["embedding"] == {
         "model": "random_model",
         "deployment": "deployment",
         "embedding_ctx_length": None,
         "chunk_size": None,
         "max_retries": None,
     }
+    assert (
+        "s3://activeloopai-db-engine"
+        in dataset.storage.__dict__["next_storage"].__dict__["root"]
+    )
+
+    with pytest.raises(ValueError):
+        dataset = dataset_utils.create_or_load_dataset(
+            tensor_params=DEFAULT_VECTORSTORE_TENSORS,
+            dataset_path="hub://testingacc2/vectorstore_dbengine",
+            token=hub_cloud_dev_token,
+            creds={},
+            logger=logger,
+            read_only=False,
+            exec_option="tensor_db",
+            runtime=None,
+            overwrite=True,
+            embedding_function=Embedding,
+        )
 
 
 def test_load(caplog, hub_cloud_dev_token):
     # dataset loading
     dataset = dataset_utils.create_or_load_dataset(
         tensor_params=DEFAULT_VECTORSTORE_TENSORS,
         dataset_path="hub://testingacc2/vectorstore_test",
         creds={},
         logger=logger,
         exec_option="python",
         overwrite=False,
         read_only=True,
         token=hub_cloud_dev_token,
         embedding_function=None,
+        runtime=None,
     )
     assert dataset.max_len == 10
 
     deeplake_vectorstore = DeepLakeVectorStore(
         path=DEFAULT_VECTORSTORE_DEEPLAKE_PATH, overwrite=True
     )
 
@@ -108,14 +128,15 @@
             token=None,
             creds={},
             logger=test_logger,
             read_only=False,
             exec_option="python",
             embedding_function=None,
             overwrite=False,
+            runtime=None,
         )
         assert (
             f"The default deeplake path location is used: {DEFAULT_VECTORSTORE_DEEPLAKE_PATH}"
             " and it is not free. All addtionally added data will be added on"
             " top of already existing deeplake dataset." in caplog.text
         )
 
@@ -126,14 +147,15 @@
             token=None,
             creds={},
             logger=test_logger,
             read_only=False,
             exec_option="python",
             embedding_function=None,
             overwrite=False,
+            runtime=None,
         )
 
     with pytest.raises(ValueError):
         # embedding tensor doesn't exist
         dataset = deeplake.empty("local_ds", overwrite=True)
         dataset.create_tensor("id", htype="text")
```

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/filter/filter.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/filter/filter.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/filter/test_filter.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/filter/test_filter.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/query.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/query.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/search_algorithm.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/search_algorithm.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/test_indra.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/test_indra.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/distance_metric.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/tql_distance_metrics/distance_metric.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/indra/vector_search.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/indra/vector_search.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/data_ingestion.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/data_ingestion.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,15 +1,19 @@
 from typing import Dict, List, Any, Callable, Optional, Union
 
 import numpy as np
 
 import deeplake
 from deeplake.core.dataset import Dataset as DeepLakeDataset
 from deeplake.core.vectorstore.vector_search import utils
-from deeplake.util.exceptions import TransformError, FailedIngestionError
+from deeplake.util.exceptions import (
+    TransformError,
+    FailedIngestionError,
+    IncorrectEmbeddingShapeError,
+)
 from deeplake.constants import (
     MAX_VECTORSTORE_INGESTION_RETRY_ATTEMPTS,
     MAX_CHECKPOINTING_INTERVAL,
 )
 
 
 class DataIngestion:
@@ -103,14 +107,17 @@
                 batched,
                 self.dataset,
                 num_workers=num_workers,
                 checkpoint_interval=checkpoint_interval,
                 verbose=False,
             )
         except Exception as e:
+            if isinstance(e.__cause__, IncorrectEmbeddingShapeError):
+                raise IncorrectEmbeddingShapeError()
+
             self.retry_attempt += 1
             last_checkpoint = self.dataset.version_state["commit_node"].parent
             self.total_samples_processed += (
                 last_checkpoint.total_samples_processed * self.ingestion_batch_size
             )
 
             index = int(self.total_samples_processed / self.ingestion_batch_size)
@@ -156,19 +163,26 @@
 ) -> None:
     embeds: List[Optional[np.ndarray]] = [None] * len(sample_in)
     if embedding_function:
         try:
             for func, tensor in zip(embedding_function, embedding_tensor):
                 embedding_data = [s[tensor] for s in sample_in]
                 embeddings = func(embedding_data)
-        except Exception as e:
+        except Exception as exc:
             raise Exception(
                 "Could not use embedding function. Please try again with a different embedding function."
             )
-        embeds = [np.array(e, dtype=np.float32) for e in embeddings]
+
+        shape = np.array(embeddings[0]).shape
+        embeds = []
+        for e in embeddings:
+            embedding = np.array(e, dtype=np.float32)
+            if shape != embedding.shape:
+                raise IncorrectEmbeddingShapeError()
+            embeds.append(embedding)
 
     for s, emb in zip(sample_in, embeds):
         sample_in_i = {tensor_name: s[tensor_name] for tensor_name in s}
 
         if embedding_function:
             for tensor in embedding_tensor:
                 sample_in_i[tensor] = np.array(emb, dtype=np.float32)
```

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/ingest_data.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/ingest_data.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/ingestion/test_data_ingestion.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/ingestion/test_data_ingestion.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/search_algorithm.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/search_algorithm.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/test_vector_search.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/test_vector_search.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/python/vector_search.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/python/vector_search.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/utils.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/utils.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/vectorstore/vector_search/vector_search.py` & `deeplake-3.6.7/deeplake/core/vectorstore/vector_search/vector_search.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/version_control/commit_chunk_map.py` & `deeplake-3.6.7/deeplake/core/version_control/commit_chunk_map.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/version_control/commit_diff.py` & `deeplake-3.6.7/deeplake/core/version_control/commit_diff.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/version_control/commit_node.py` & `deeplake-3.6.7/deeplake/core/version_control/commit_node.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/version_control/dataset_diff.py` & `deeplake-3.6.7/deeplake/core/version_control/dataset_diff.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/version_control/test_merge.py` & `deeplake-3.6.7/deeplake/core/version_control/test_merge.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/core/version_control/test_version_control.py` & `deeplake-3.6.7/deeplake/core/version_control/test_version_control.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/enterprise/convert_to_libdeeplake.py` & `deeplake-3.6.7/deeplake/enterprise/convert_to_libdeeplake.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/enterprise/dataloader.py` & `deeplake-3.6.7/deeplake/enterprise/dataloader.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/enterprise/dummy_dataloader.py` & `deeplake-3.6.7/deeplake/enterprise/dummy_dataloader.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/enterprise/libdeeplake_query.py` & `deeplake-3.6.7/deeplake/enterprise/libdeeplake_query.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/enterprise/test_pytorch.py` & `deeplake-3.6.7/deeplake/enterprise/test_pytorch.py`

 * *Files 1% similar despite different names*

```diff
@@ -62,15 +62,15 @@
     return sample["index"], sample["xyz"]
 
 
 @requires_torch
 @requires_libdeeplake
 @pytest.mark.parametrize(
     "ds",
-    ["hub_cloud_ds", "local_ds"],
+    ["hub_cloud_ds", "local_auth_ds"],
     indirect=True,
 )
 def test_pytorch_small(ds):
     with ds:
         ds.create_tensor("image", max_chunk_size=PYTORCH_TESTS_MAX_CHUNK_SIZE)
         ds.image.extend(([i * np.ones((i + 1, i + 1)) for i in range(16)]))
         ds.commit()
@@ -695,22 +695,22 @@
         assert "x" in batch.keys()
         assert batch["x"].shape == (1, 10, 10, 3)
 
 
 @patch("deeplake.constants.RETURN_DUMMY_DATA_FOR_DATALOADER", True)
 @requires_torch
 @requires_libdeeplake
-def test_pytorch_dummy_data(local_ds):
+def test_pytorch_dummy_data(local_auth_ds):
     x_data = [
         np.random.randint(0, 255, (100, 100, 3), dtype="uint8"),
         np.random.randint(0, 255, (120, 120, 3), dtype="uint8"),
     ]
     y_data = [np.random.rand(100, 100, 3), np.random.rand(120, 120, 3)]
     z_data = ["hello", "world"]
-    with local_ds as ds:
+    with local_auth_ds as ds:
         ds.create_tensor("x")
         ds.create_tensor("y")
         ds.create_tensor("z")
         ds.x.extend(x_data)
         ds.y.extend(y_data)
         ds.z.extend(z_data)
```

### Comparing `deeplake-3.6.6/deeplake/enterprise/test_query.py` & `deeplake-3.6.7/deeplake/enterprise/test_query.py`

 * *Files 27% similar despite different names*

```diff
@@ -13,45 +13,47 @@
     dsv = hub_cloud_ds.query("SELECT * WHERE CONTAINS(label, 2)")
     assert len(dsv) == 20
     for i in range(20):
         assert dsv.label[i].numpy() == 2
 
 
 @requires_libdeeplake
-def test_sample(local_ds):
-    with local_ds as ds:
+def test_sample(local_auth_ds):
+    with local_auth_ds as ds:
         ds.create_tensor("label")
         for i in range(100):
             ds.label.append(floor(i / 20))
 
-    dsv = local_ds.sample_by(
+    dsv = local_auth_ds.sample_by(
         "max_weight(label == 2: 10, label == 1: 1)", replace=False, size=10
     )
     assert len(dsv) == 10
     for i in range(10):
         assert dsv.label[i].numpy() == 2 or dsv.label[i].numpy() == 1
 
-    dsv = local_ds.sample_by("max_weight(label == 2: 10, label == 1: 1)", replace=True)
+    dsv = local_auth_ds.sample_by(
+        "max_weight(label == 2: 10, label == 1: 1)", replace=True
+    )
     assert len(dsv) == 100
     for i in range(100):
         assert dsv.label[i].numpy() == 2 or dsv.label[i].numpy() == 1
 
-    dsv = local_ds.sample_by("label")
+    dsv = local_auth_ds.sample_by("label")
     assert len(dsv) == 100
 
     weights = list()
     for i in range(100):
         weights.append(1 if floor(i / 20) == 0 else 0)
 
-    dsv = local_ds.sample_by(weights)
+    dsv = local_auth_ds.sample_by(weights)
     assert len(dsv) == 100
     for i in range(100):
         assert dsv.label[i].numpy() == 0
 
     weights = np.ndarray((100), np.int32)
     for i in range(100):
         weights[i] = 1 if floor(i / 10) == 0 else 0
 
-    dsv = local_ds.sample_by(weights)
+    dsv = local_auth_ds.sample_by(weights)
     assert len(dsv) == 100
     for i in range(100):
         assert dsv.label[i].numpy() == 0
```

### Comparing `deeplake-3.6.6/deeplake/enterprise/test_tensorflow.py` & `deeplake-3.6.7/deeplake/enterprise/test_tensorflow.py`

 * *Files 2% similar despite different names*

```diff
@@ -459,27 +459,31 @@
 def test_tensorflow_ddp():
     raise NotImplementedError
 
 
 @requires_tensorflow
 @requires_libdeeplake
 @pytest.mark.parametrize("compression", [None, "jpeg"])
-def test_tensorflow_decode(local_ds, compressed_image_paths, compression):
-    with local_ds:
-        local_ds.create_tensor("image", sample_compression=compression)
-        local_ds.image.extend(
+def test_tensorflow_decode(local_auth_ds, compressed_image_paths, compression):
+    with local_auth_ds:
+        local_auth_ds.create_tensor("image", sample_compression=compression)
+        local_auth_ds.image.extend(
             np.array([i * np.ones((10, 10, 3), dtype=np.uint8) for i in range(5)])
         )
-        local_ds.image.extend([deeplake.read(compressed_image_paths["jpeg"][0])] * 5)
-    if isinstance(get_base_storage(local_ds.storage), (MemoryProvider, GCSProvider)):
+        local_auth_ds.image.extend(
+            [deeplake.read(compressed_image_paths["jpeg"][0])] * 5
+        )
+    if isinstance(
+        get_base_storage(local_auth_ds.storage), (MemoryProvider, GCSProvider)
+    ):
         with pytest.raises(ValueError):
-            dl = local_ds.dataloader()
+            dl = local_auth_ds.dataloader()
         return
 
-    ptds = local_ds.dataloader().tensorflow(
+    ptds = local_auth_ds.dataloader().tensorflow(
         collate_fn=identity_collate, decode_method={"image": "tobytes"}
     )
 
     for i, batch in enumerate(ptds):
         image = batch[0]["image"]
         assert isinstance(image, bytes)
         if i < 5 and not compression:
@@ -488,15 +492,15 @@
                 i * np.ones((10, 10, 3), dtype=np.uint8),
             )
         elif i >= 5 and compression:
             with open(compressed_image_paths["jpeg"][0], "rb") as f:
                 assert f.read() == image
 
     if compression:
-        ptds = local_ds.dataloader().numpy(decode_method={"image": "pil"})
+        ptds = local_auth_ds.dataloader().numpy(decode_method={"image": "pil"})
         for i, batch in enumerate(ptds):
             image = batch[0]["image"]
             assert isinstance(image, Image.Image)
             if i < 5:
                 np.testing.assert_array_equal(
                     np.array(image), i * np.ones((10, 10, 3), dtype=np.uint8)
                 )
@@ -642,31 +646,31 @@
 
     for batch in ptds:
         assert batch.keys() == {"xyz", "index"}
 
 
 @requires_libdeeplake
 @requires_tensorflow
-def test_uneven_iteration(local_ds):
-    with local_ds as ds:
+def test_uneven_iteration(local_auth_ds):
+    with local_auth_ds as ds:
         ds.create_tensor("x")
         ds.create_tensor("y")
         ds.x.extend(list(range(5)))
         ds.y.extend(list(range(10)))
     ptds = ds.dataloader().tensorflow()
     for i, batch in enumerate(ptds):
         x, y = np.array(batch["x"][0]), np.array(batch["y"][0])
         np.testing.assert_equal(x, i)
         np.testing.assert_equal(y, i)
 
 
 @requires_libdeeplake
 @requires_tensorflow
-def test_tensorflow_error_handling(local_ds):
-    with local_ds as ds:
+def test_tensorflow_error_handling(local_auth_ds):
+    with local_auth_ds as ds:
         ds.create_tensor("x")
         ds.create_tensor("y")
         ds.x.extend(list(range(5)))
 
     ptds = ds.dataloader().tensorflow()
     with pytest.raises(EmptyTensorError):
         for _ in ptds:
```

### Comparing `deeplake-3.6.6/deeplake/enterprise/util.py` & `deeplake-3.6.7/deeplake/enterprise/util.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/hooks.py` & `deeplake-3.6.7/deeplake/hooks.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/htype.py` & `deeplake-3.6.7/deeplake/htype.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/huggingface/huggingface.py` & `deeplake-3.6.7/deeplake/integrations/huggingface/huggingface.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/mmdet/mmdet_.py` & `deeplake-3.6.7/deeplake/integrations/mmdet/mmdet_.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/mmdet/mmdet_runners.py` & `deeplake-3.6.7/deeplake/integrations/mmdet/mmdet_runners.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/mmdet/mmdet_utils.py` & `deeplake-3.6.7/deeplake/integrations/mmdet/mmdet_utils.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/pytorch/common.py` & `deeplake-3.6.7/deeplake/integrations/pytorch/common.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/pytorch/dataset.py` & `deeplake-3.6.7/deeplake/integrations/pytorch/dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/pytorch/pytorch.py` & `deeplake-3.6.7/deeplake/integrations/pytorch/pytorch.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/pytorch/shuffle_buffer.py` & `deeplake-3.6.7/deeplake/integrations/pytorch/shuffle_buffer.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/tf/common.py` & `deeplake-3.6.7/deeplake/integrations/tf/common.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/tf/datasettotensorflow.py` & `deeplake-3.6.7/deeplake/integrations/tf/datasettotensorflow.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/tf/deeplake_tensorflow_dataset.py` & `deeplake-3.6.7/deeplake/integrations/tf/deeplake_tensorflow_dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/integrations/wandb/wandb.py` & `deeplake-3.6.7/deeplake/integrations/wandb/wandb.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/tests/cache_fixtures.py` & `deeplake-3.6.7/deeplake/tests/cache_fixtures.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/tests/client_fixtures.py` & `deeplake-3.6.7/deeplake/tests/client_fixtures.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/tests/common.py` & `deeplake-3.6.7/deeplake/tests/common.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/tests/dataset_fixtures.py` & `deeplake-3.6.7/deeplake/tests/dataset_fixtures.py`

 * *Files 4% similar despite different names*

```diff
@@ -66,22 +66,35 @@
 
 @pytest.fixture
 def local_ds(local_ds_generator):
     return local_ds_generator()
 
 
 @pytest.fixture
-def local_ds_generator(local_path, hub_cloud_dev_token):
+def local_auth_ds(local_auth_ds_generator):
+    return local_auth_ds_generator()
+
+
+@pytest.fixture
+def local_ds_generator(local_path):
     def generate_local_ds(**kwargs):
-        return deeplake.dataset(local_path, token=hub_cloud_dev_token, **kwargs)
+        return deeplake.dataset(local_path, **kwargs)
 
     return generate_local_ds
 
 
 @pytest.fixture
+def local_auth_ds_generator(local_path, hub_cloud_dev_token):
+    def generate_local_auth_ds(**kwargs):
+        return deeplake.dataset(local_path, token=hub_cloud_dev_token, **kwargs)
+
+    return generate_local_auth_ds
+
+
+@pytest.fixture
 def s3_ds(s3_ds_generator):
     return s3_ds_generator()
 
 
 @pytest.fixture
 def s3_ds_generator(s3_path):
     def generate_s3_ds(**kwargs):
```

### Comparing `deeplake-3.6.6/deeplake/tests/path_fixtures.py` & `deeplake-3.6.7/deeplake/tests/path_fixtures.py`

 * *Files 2% similar despite different names*

```diff
@@ -423,14 +423,22 @@
     """Path to a cat image in the dummy data folder. Expected shape: (900, 900, 3)"""
 
     path = get_dummy_data_path("images")
     return os.path.join(path, "cat.jpeg")
 
 
 @pytest.fixture
+def dog_path():
+    """Path to a dog image in the dummy data folder. Expected shape: (323, 480, 3)"""
+
+    path = get_dummy_data_path("images")
+    return os.path.join(path, "dog2.jpg")
+
+
+@pytest.fixture
 def flower_path():
     """Path to a flower image in the dummy data folder. Expected shape: (513, 464, 4)"""
 
     path = get_dummy_data_path("images")
     return os.path.join(path, "flower.png")
```

### Comparing `deeplake-3.6.6/deeplake/tests/storage_fixtures.py` & `deeplake-3.6.7/deeplake/tests/storage_fixtures.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/access_method.py` & `deeplake-3.6.7/deeplake/util/access_method.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/agreement.py` & `deeplake-3.6.7/deeplake/util/agreement.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/array_list.py` & `deeplake-3.6.7/deeplake/util/array_list.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/assert_byte_indexes.py` & `deeplake-3.6.7/deeplake/util/assert_byte_indexes.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/auto.py` & `deeplake-3.6.7/deeplake/util/auto.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/bugout_reporter.py` & `deeplake-3.6.7/deeplake/util/bugout_reporter.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/cache_chain.py` & `deeplake-3.6.7/deeplake/util/cache_chain.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/casting.py` & `deeplake-3.6.7/deeplake/util/casting.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/check_latest_version.py` & `deeplake-3.6.7/deeplake/util/check_latest_version.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/chunk_engine.py` & `deeplake-3.6.7/deeplake/util/chunk_engine.py`

 * *Files 1% similar despite different names*

```diff
@@ -56,22 +56,22 @@
                 samples = [samples]
         elif hasattr(samples, "shape"):
             if len(samples.shape) > 0 and samples.shape[0] != 1:  # type: ignore
                 samples = [samples]
         else:
             samples = [samples]
 
-    if hasattr(samples, "__len__"):
-        if index_length != len(samples):  # type: ignore
-            raise ValueError(
-                f"Index length ({index_length}) and length of samples ({len(samples)}) must be equal for updating a tensor."  # type: ignore
-            )
-    else:
+    if not hasattr(samples, "__len__"):
         samples = [samples]
 
+    if index_length != len(samples):  # type: ignore
+        raise ValueError(
+            f"Index length ({index_length}) and length of samples ({len(samples)}) must be equal for updating a tensor."  # type: ignore
+        )
+
     return samples  # type: ignore
 
 
 def check_suboptimal_chunks(
     chunks_nbytes_after_updates: List[int], min_chunk_size: int, max_chunk_size: int
 ):
     upper_warn_threshold = max_chunk_size * (1 + CHUNK_UPDATE_WARN_PORTION)
```

### Comparing `deeplake-3.6.6/deeplake/util/class_label.py` & `deeplake-3.6.7/deeplake/util/class_label.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/compute.py` & `deeplake-3.6.7/deeplake/util/compute.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/connect_dataset.py` & `deeplake-3.6.7/deeplake/util/connect_dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/dataset.py` & `deeplake-3.6.7/deeplake/util/dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/diff.py` & `deeplake-3.6.7/deeplake/util/diff.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/downsample.py` & `deeplake-3.6.7/deeplake/util/downsample.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/encoder.py` & `deeplake-3.6.7/deeplake/util/encoder.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/exceptions.py` & `deeplake-3.6.7/deeplake/util/exceptions.py`

 * *Files 1% similar despite different names*

```diff
@@ -1058,7 +1058,16 @@
             "All samples were skipped during the transform. "
             "Ensure your transform pipeline is correct before you set `ignore_errors=True`."
         )
 
 
 class FailedIngestionError(Exception):
     pass
+
+
+class IncorrectEmbeddingShapeError(Exception):
+    def __init__(self):
+        super().__init__(
+            "The embedding function returned embeddings of different shapes. "
+            "Please either use different embedding function or exclude invalid "
+            "files that are not supported by the embedding function. "
+        )
```

### Comparing `deeplake-3.6.6/deeplake/util/exif.py` & `deeplake-3.6.7/deeplake/util/exif.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/from_tfds.py` & `deeplake-3.6.7/deeplake/util/from_tfds.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/htype.py` & `deeplake-3.6.7/deeplake/util/htype.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/image.py` & `deeplake-3.6.7/deeplake/util/image.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/invalid_view_op.py` & `deeplake-3.6.7/deeplake/util/invalid_view_op.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/iteration_warning.py` & `deeplake-3.6.7/deeplake/util/iteration_warning.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/json.py` & `deeplake-3.6.7/deeplake/util/json.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/keys.py` & `deeplake-3.6.7/deeplake/util/keys.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/link.py` & `deeplake-3.6.7/deeplake/util/link.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/logging.py` & `deeplake-3.6.7/deeplake/util/logging.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/merge.py` & `deeplake-3.6.7/deeplake/util/merge.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/modified.py` & `deeplake-3.6.7/deeplake/util/modified.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/notebook.py` & `deeplake-3.6.7/deeplake/util/notebook.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/mesh.py` & `deeplake-3.6.7/deeplake/util/object_3d/mesh.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/object_base_3d.py` & `deeplake-3.6.7/deeplake/util/object_3d/object_base_3d.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/ply_parser.py` & `deeplake-3.6.7/deeplake/util/object_3d/ply_parser.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/ply_parser_base.py` & `deeplake-3.6.7/deeplake/util/object_3d/ply_parser_base.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/ply_parsers.py` & `deeplake-3.6.7/deeplake/util/object_3d/ply_parsers.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/ply_reader.py` & `deeplake-3.6.7/deeplake/util/object_3d/ply_reader.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/ply_reader_base.py` & `deeplake-3.6.7/deeplake/util/object_3d/ply_reader_base.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/ply_readers.py` & `deeplake-3.6.7/deeplake/util/object_3d/ply_readers.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/point_cloud.py` & `deeplake-3.6.7/deeplake/util/object_3d/point_cloud.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/object_3d/read_3d_data.py` & `deeplake-3.6.7/deeplake/util/object_3d/read_3d_data.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/path.py` & `deeplake-3.6.7/deeplake/util/path.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/pretty_print.py` & `deeplake-3.6.7/deeplake/util/pretty_print.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/remove_cache.py` & `deeplake-3.6.7/deeplake/util/remove_cache.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/scheduling.py` & `deeplake-3.6.7/deeplake/util/scheduling.py`

 * *Files 2% similar despite different names*

```diff
@@ -44,18 +44,18 @@
         last_index = int(enc_array[chunk_idx][1]) + 1
         indexes = np.arange(start_index, last_index)
         if shuffle_within_chunks:
             np.random.shuffle(indexes)
         schedule.extend(indexes)
 
     if isinstance(index_struct, set):
-        schedule = [idx for idx in schedule if idx in index_struct]
+        schedule = [int(idx) for idx in schedule if idx in index_struct]
     elif isinstance(index_struct, dict):
         nested_schedule = [
-            [idx] * index_struct[idx] for idx in schedule if idx in index_struct
+            [int(idx)] * index_struct[idx] for idx in schedule if idx in index_struct
         ]
         schedule = []
         for indexes_list in nested_schedule:
             schedule.extend(indexes_list)
     return schedule
```

### Comparing `deeplake-3.6.6/deeplake/util/shape_interval.py` & `deeplake-3.6.7/deeplake/util/shape_interval.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/spinner.py` & `deeplake-3.6.7/deeplake/util/spinner.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/split.py` & `deeplake-3.6.7/deeplake/util/split.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/storage.py` & `deeplake-3.6.7/deeplake/util/storage.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tag.py` & `deeplake-3.6.7/deeplake/util/tag.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tensor_db.py` & `deeplake-3.6.7/deeplake/util/tensor_db.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/testing.py` & `deeplake-3.6.7/deeplake/util/testing.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_auto.py` & `deeplake-3.6.7/deeplake/util/tests/test_auto.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_connect_dataset.py` & `deeplake-3.6.7/deeplake/util/tests/test_connect_dataset.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_iterable_ordered_dict.py` & `deeplake-3.6.7/deeplake/util/tests/test_iterable_ordered_dict.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_read.py` & `deeplake-3.6.7/deeplake/util/tests/test_read.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_shape_interval.py` & `deeplake-3.6.7/deeplake/util/tests/test_shape_interval.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_split.py` & `deeplake-3.6.7/deeplake/util/tests/test_split.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_tensor_db.py` & `deeplake-3.6.7/deeplake/util/tests/test_tensor_db.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/tests/test_version_control.py` & `deeplake-3.6.7/deeplake/util/tests/test_version_control.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/transform.py` & `deeplake-3.6.7/deeplake/util/transform.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/version_control.py` & `deeplake-3.6.7/deeplake/util/version_control.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/util/video.py` & `deeplake-3.6.7/deeplake/util/video.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/visualizer/video_streaming.py` & `deeplake-3.6.7/deeplake/visualizer/video_streaming.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake/visualizer/visualizer.py` & `deeplake-3.6.7/deeplake/visualizer/visualizer.py`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake.egg-info/PKG-INFO` & `deeplake-3.6.7/deeplake.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: deeplake
-Version: 3.6.6
+Version: 3.6.7
 Summary: Activeloop Deep Lake
 Home-page: UNKNOWN
 Author: activeloop.ai
 Author-email: support@activeloop.ai
 License: MPL-2.0
 Project-URL: Documentation, https://docs.activeloop.ai/
 Project-URL: Source, https://github.com/activeloopai/deeplake
@@ -28,32 +28,32 @@
 <img src="https://static.scarf.sh/a.png?x-pxid=bc3c57b0-9a65-49fe-b8ea-f711c4d35b82" /><p align="center">
      <img src="https://i.postimg.cc/rsjcWc3S/deeplake-logo.png" width="400"/>
 </h1>
     </br>
     <h1 align="center">Deep Lake: Database for AI
  </h1>
 <p align="center">
-    <a href="https://github.com/activeloopai/Hub/actions/workflows/test-pr-on-label.yml"><img src="https://github.com/activeloopai/Hub/actions/workflows/test-push.yml/badge.svg" alt="PyPI version" height="18"></a>
+    <a href="https://github.com/activeloopai/deeplake/actions/workflows/test-pr-on-label.yml"><img src="https://github.com/activeloopai/deeplake/actions/workflows/test-push.yml/badge.svg" alt="PyPI version" height="18"></a>
     <a href="https://pypi.org/project/deeplake/"><img src="https://badge.fury.io/py/deeplake.svg" alt="PyPI version" height="18"></a>
     <a href='https://docs.deeplake.ai/en/latest/?badge=latest'>
      <img src='https://readthedocs.org/projects/deep-lake/badge/?version=latest' alt='Documentation Status' />
      </a>
     <a href="https://pepy.tech/project/deeplake"><img src="https://static.pepy.tech/badge/deeplake" alt="PyPI version" height="18"></a>
      <a href="https://github.com/activeloopai/deeplake/issues">
     <img alt="GitHub issues" src="https://img.shields.io/github/issues/activeloopai/deeplake"> </a>
     <a href="https://codecov.io/gh/activeloopai/deeplake/branch/main"><img src="https://codecov.io/gh/activeloopai/deeplake/branch/main/graph/badge.svg" alt="codecov" height="18"></a>
   <h3 align="center">
-   <a href="https://docs.activeloop.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Documentation</b></a> &bull;
-   <a href="https://docs.activeloop.ai/getting-started/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Getting Started</b></a> &bull;
+   <a href="https://docs.activeloop.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Docs</b></a> &bull;
+   <a href="https://docs.activeloop.ai/getting-started/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Get Started</b></a> &bull;
    <a href="https://docs.deeplake.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>API Reference</b></a> &bull;  
-   <a href="https://github.com/activeloopai/examples/"><b>Examples</b></a> &bull; 
+   <a href="http://learn.activeloop.ai"><b>LangChain & VectorDBs Course</b></a> &bull;
    <a href="https://www.activeloop.ai/resources/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Blog</b></a> &bull; 
    <a href="https://www.deeplake.ai/?utm_source=github&utm_medium=github&utm_campaign=github_readme&utm_id=readme"><b>Whitepaper</b></a> &bull;  
-  <a href="http://slack.activeloop.ai"><b>Slack Community</b></a> &bull;
-  <a href="https://twitter.com/intent/tweet?text=The%20dataset%20format%20for%20AI.%20Stream%20data%20to%20PyTorch%20and%20Tensorflow%20datasets&url=https://activeloop.ai/&via=activeloopai&hashtags=opensource,pytorch,tensorflow,data,datascience,datapipelines,activeloop,databaseforAI"><b>Twitter</b></a>
+  <a href="http://slack.activeloop.ai"><b>Slack</b></a> &bull;
+  <a href="https://twitter.com/intent/tweet?url=https%3A%2F%2Factiveloop.ai%2F&via=activeloopai&text=Deep%20Lake%20is%20the%20Database%20for%20all%20AI%20data.%20Check%20it%20out%21&hashtags=DeepLake%2Cactiveloop%2Copensource"><b>Twitter</b></a>
  </h3>
  
 
 *Read this in other languages: [简体中文](README.zh-cn.md)*
 
 ## About Deep Lake
```

#### html2text {}

```diff
@@ -1,24 +1,24 @@
-Metadata-Version: 2.1 Name: deeplake Version: 3.6.6 Summary: Activeloop Deep
+Metadata-Version: 2.1 Name: deeplake Version: 3.6.7 Summary: Activeloop Deep
 Lake Home-page: UNKNOWN Author: activeloop.ai Author-email:
 support@activeloop.ai License: MPL-2.0 Project-URL: Documentation, https://
 docs.activeloop.ai/ Project-URL: Source, https://github.com/activeloopai/
 deeplake Platform: UNKNOWN Classifier: License :: OSI Approved :: Mozilla
 Public License 2.0 (MPL 2.0) Description-Content-Type: text/markdown Provides-
 Extra: all Provides-Extra: audio Provides-Extra: av Provides-Extra: azure
 Provides-Extra: dicom Provides-Extra: enterprise Provides-Extra: gcp Provides-
 Extra: gdrive Provides-Extra: medical Provides-Extra: point_cloud Provides-
 Extra: video Provides-Extra: visualizer License-File: LICENSE [https://
 static.scarf.sh/a.png?x-pxid=bc3c57b0-9a65-49fe-b8ea-f711c4d35b82]
                [https://i.postimg.cc/rsjcWc3S/deeplake-logo.png]
                    ****** Deep Lake: Database for AI ******
   [PyPI_version] [PyPI_version] [Documentation_Status] [PyPI_version] [GitHub
                                issues] [codecov]
-   **** Documentation • Getting_Started • API_Reference • Examples • Blog •
-                  Whitepaper • Slack_Community • Twitter ****
+**** Docs • Get_Started • API_Reference • LangChain_&_VectorDBs_Course • Blog •
+                       Whitepaper • Slack • Twitter ****
 *Read this in other languages: [ç®ä½ä¸­æ](README.zh-cn.md)* ## About Deep
 Lake Deep Lake is a Database for AI powered by a unique storage format
 optimized for deep-learning and Large Language Model (LLM) based applications.
 It simplifies the deployment of enterprise-grade LLM-based products by offering
 storage for all data types (embeddings, audio, text, videos, images, pdfs,
 annotations, etc.), querying and vector search, data streaming while training
 models at scale, data versioning and lineage for all workloads, and
```

### Comparing `deeplake-3.6.6/deeplake.egg-info/SOURCES.txt` & `deeplake-3.6.7/deeplake.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/deeplake.egg-info/requires.txt` & `deeplake-3.6.7/deeplake.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `deeplake-3.6.6/setup.py` & `deeplake-3.6.7/setup.py`

 * *Files identical despite different names*

