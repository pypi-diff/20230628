# Comparing `tmp/vision_datasets-0.2.9.tar.gz` & `tmp/vision_datasets-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\vision_datasets-0.2.9.tar", last modified: Thu Mar 24 17:18:07 2022, max compression
+gzip compressed data, was "vision_datasets-1.0.0.tar", last modified: Wed Jun 28 07:31:59 2023, max compression
```

## Comparing `vision_datasets-0.2.9.tar` & `vision_datasets-1.0.0.tar`

### file list

```diff
@@ -1,60 +1,161 @@
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/
--rw-rw-rw-   0        0        0     1340 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/.gitignore
--rw-rw-rw-   0        0        0     3556 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/COCO_DATA_FORMAT.md
--rw-rw-rw-   0        0        0      453 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/CODE_OF_CONDUCT.md
--rw-rw-rw-   0        0        0     3908 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/IRIS_DATA_FORMAT.md
--rw-rw-rw-   0        0        0     1162 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/LICENSE
--rw-rw-rw-   0        0        0     9882 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/PKG-INFO
--rw-rw-rw-   0        0        0     8023 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/README.md
--rw-rw-rw-   0        0        0       42 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/setup.cfg
--rw-rw-rw-   0        0        0     2814 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/setup.py
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/tests/
--rw-rw-rw-   0        0        0     2089 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/tests/test_box_alteration.py
--rw-rw-rw-   0        0        0     4468 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/tests/test_dataset_downloader.py
--rw-rw-rw-   0        0        0    50883 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/tests/test_dataset_manifest.py
--rw-rw-rw-   0        0        0     2111 2022-01-20 20:09:50.000000 vision_datasets-0.2.9/tests/test_dataset_registry.py
--rw-rw-rw-   0        0        0     4151 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/tests/test_detection_as_classification.py
--rw-rw-rw-   0        0        0     3436 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/tests/test_file_reader.py
--rw-rw-rw-   0        0        0     2271 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/tests/test_fixtures.py
--rw-rw-rw-   0        0        0     2926 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/tests/test_manifest_dataset.py
--rw-rw-rw-   0        0        0     1398 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/tests/test_pytorch_dataset.py
--rw-rw-rw-   0        0        0       99 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/tox.ini
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/vision_datasets/
--rw-rw-rw-   0        0        0      449 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/__init__.py
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/vision_datasets/commands/
--rw-rw-rw-   0        0        0        0 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/commands/__init__.py
--rw-rw-rw-   0        0        0     3216 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/commands/convert_local_dir_ic_data.py
--rw-rw-rw-   0        0        0     3879 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/commands/converter_od_to_ic.py
--rw-rw-rw-   0        0        0     5704 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/vision_datasets/commands/converter_tsv_to_coco.py
--rw-rw-rw-   0        0        0     5255 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/vision_datasets/commands/converter_tsv_to_iris.py
--rw-rw-rw-   0        0        0     4854 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/commands/converter_yolo_darknet_to_cvs.py
--rw-rw-rw-   0        0        0     4101 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/commands/dataset_check.py
--rw-rw-rw-   0        0        0     3755 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/commands/download.py
--rw-rw-rw-   0        0        0     1075 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/commands/generate_image_meta_info.py
--rw-rw-rw-   0        0        0     3269 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/commands/merge_datasets.py
--rw-rw-rw-   0        0        0     2517 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/vision_datasets/commands/utils.py
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/vision_datasets/common/
--rw-rw-rw-   0        0        0      504 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/common/__init__.py
--rw-rw-rw-   0        0        0     1090 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/vision_datasets/common/base_dataset.py
--rw-rw-rw-   0        0        0      904 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/common/constants.py
--rw-rw-rw-   0        0        0    32933 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/common/data_manifest.py
--rw-rw-rw-   0        0        0     4562 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/common/dataset_downloader.py
--rw-rw-rw-   0        0        0     4637 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/common/dataset_info.py
--rw-rw-rw-   0        0        0     1690 2022-01-20 20:09:50.000000 vision_datasets-0.2.9/vision_datasets/common/dataset_registry.py
--rw-rw-rw-   0        0        0     1412 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/common/image_loader.py
--rw-rw-rw-   0        0        0    14368 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/common/manifest_dataset.py
--rw-rw-rw-   0        0        0     2162 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/common/util.py
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/vision_datasets/pytorch/
--rw-rw-rw-   0        0        0       71 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/pytorch/__init__.py
--rw-rw-rw-   0        0        0     1290 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/vision_datasets/pytorch/dataset.py
--rw-rw-rw-   0        0        0     1057 2022-02-03 08:25:43.000000 vision_datasets-0.2.9/vision_datasets/pytorch/torch_dataset.py
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/vision_datasets/resources/
--rw-rw-rw-   0        0        0       65 2022-01-06 01:01:48.000000 vision_datasets-0.2.9/vision_datasets/resources/__init__.py
--rw-rw-rw-   0        0        0     7133 2022-03-24 17:18:01.000000 vision_datasets-0.2.9/vision_datasets/resources/dataset_hub.py
-drwxrwxrwx   0        0        0        0 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/vision_datasets.egg-info/
--rw-rw-rw-   0        0        0     9882 2022-03-24 17:18:06.000000 vision_datasets-0.2.9/vision_datasets.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1730 2022-03-24 17:18:07.000000 vision_datasets-0.2.9/vision_datasets.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2022-03-24 17:18:06.000000 vision_datasets-0.2.9/vision_datasets.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      676 2022-03-24 17:18:06.000000 vision_datasets-0.2.9/vision_datasets.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0      105 2022-03-24 17:18:06.000000 vision_datasets-0.2.9/vision_datasets.egg-info/requires.txt
--rw-rw-rw-   0        0        0       16 2022-03-24 17:18:06.000000 vision_datasets-0.2.9/vision_datasets.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.336434 vision_datasets-1.0.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1141 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     9545 2023-06-28 07:31:59.336434 vision_datasets-1.0.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     8876 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 07:31:59.340435 vision_datasets-1.0.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2295 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.304434 vision_datasets-1.0.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.304434 vision_datasets-1.0.0/tests/resources/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/resources/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14081 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/resources/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2032 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_box_alteration.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.308434 vision_datasets-1.0.0/tests/test_coco_adaptor/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1387 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/coco_adaptor_base.py
+-rw-r--r--   0 runner    (1001) docker     (123)      613 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_image_caption_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      615 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_image_matting_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1330 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_image_regression_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      626 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_image_text_matching_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1987 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_multiclass_classification_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      643 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_multilabel_classification_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      433 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_multitask_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1257 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_object_detection_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      629 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_adaptor/test_text_2_image_retrieval_coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15643 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_coco_format_manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4117 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_dataset_downloader.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45616 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_dataset_manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2073 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_dataset_registry.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4519 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_detection_as_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3396 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_file_reader.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_fixtures.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3799 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_ic_od_as_image_text_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8939 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_iris_format_manifest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.308434 vision_datasets-1.0.0/tests/test_manifest/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_manifest/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      616 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_manifest/test_pickleable.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6159 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_manifest_dataset.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.308434 vision_datasets-1.0.0/tests/test_manifest_to_coco/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_manifest_to_coco/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      590 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_manifest_to_coco/test_manifest_to_coco.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.308434 vision_datasets-1.0.0/tests/test_merge_manifest/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_merge_manifest/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3187 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_merge_manifest/test_manifest_merge.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1351 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_pytorch_dataset.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.312434 vision_datasets-1.0.0/tests/test_sample/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_sample/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2351 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_sample/test_sample_manfiest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.312434 vision_datasets-1.0.0/tests/test_spawn/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_spawn/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_spawn/test_spawn.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/tests/test_utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.312434 vision_datasets-1.0.0/vision_datasets/
+-rw-r--r--   0 runner    (1001) docker     (123)     1721 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.316434 vision_datasets-1.0.0/vision_datasets/commands/
+-rw-r--r--   0 runner    (1001) docker     (123)       58 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5634 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/check_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3641 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/converter_od_to_ic.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3344 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/converter_to_aml_coco.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2037 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/converter_to_tsv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6138 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/converter_tsv_to_coco.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2410 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/download_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)      712 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/list_operations_by_data_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7322 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/commands/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.320434 vision_datasets-1.0.0/vision_datasets/common/
+-rw-r--r--   0 runner    (1001) docker     (123)     2598 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      553 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/constants.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.320434 vision_datasets-1.0.0/vision_datasets/common/data_manifest/
+-rw-r--r--   0 runner    (1001) docker     (123)     1527 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4820 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5867 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/data_manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6858 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/iris_data_manifest_adaptor.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.324434 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/
+-rw-r--r--   0 runner    (1001) docker     (123)     1270 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2930 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/balanced_instance_weights_generator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1044 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/filter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/generate_coco.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2803 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/merge.py
+-rw-r--r--   0 runner    (1001) docker     (123)      246 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/operation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1800 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/remove_categories.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4201 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/sample.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2409 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/spawn.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4932 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/operations/split.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1043 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_manifest/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.324434 vision_datasets-1.0.0/vision_datasets/common/data_reader/
+-rw-r--r--   0 runner    (1001) docker     (123)      252 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_reader/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7445 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_reader/dataset_downloader.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1938 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_reader/file_reader.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1371 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/data_reader/image_loader.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.328434 vision_datasets-1.0.0/vision_datasets/common/dataset/
+-rw-r--r--   0 runner    (1001) docker     (123)      180 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1049 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset/base_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1239 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset/dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1088 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset/torch_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7661 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset/vision_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3104 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset_info.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.328434 vision_datasets-1.0.0/vision_datasets/common/dataset_management/
+-rw-r--r--   0 runner    (1001) docker     (123)      128 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset_management/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7277 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset_management/dataset_hub.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1658 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/dataset_management/dataset_registry.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.328434 vision_datasets-1.0.0/vision_datasets/common/factory/
+-rw-r--r--   0 runner    (1001) docker     (123)      589 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      443 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/coco_manifest_adaptor_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1507 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/data_manifest_factory.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.332435 vision_datasets-1.0.0/vision_datasets/common/factory/operations/
+-rw-r--r--   0 runner    (1001) docker     (123)      609 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      881 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/balanced_instance_weights_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      632 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/coco_generator_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      773 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/manifest_merger_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      991 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/sampler_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      767 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/spawn_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/split_factory.py
+-rw-r--r--   0 runner    (1001) docker     (123)      351 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/factory/operations/supported_operations_by_data_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2574 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/common/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.332435 vision_datasets-1.0.0/vision_datasets/image_caption/
+-rw-r--r--   0 runner    (1001) docker     (123)      278 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_caption/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      655 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_caption/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      299 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_caption/manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_caption/operations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.332435 vision_datasets-1.0.0/vision_datasets/image_classification/
+-rw-r--r--   0 runner    (1001) docker     (123)      444 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_classification/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1698 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_classification/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      569 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_classification/manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_classification/operations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.332435 vision_datasets-1.0.0/vision_datasets/image_matting/
+-rw-r--r--   0 runner    (1001) docker     (123)      278 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_matting/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      763 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_matting/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      561 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_matting/manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      905 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_matting/operations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.336434 vision_datasets-1.0.0/vision_datasets/image_object_detection/
+-rw-r--r--   0 runner    (1001) docker     (123)      645 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_object_detection/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1050 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_object_detection/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9097 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_object_detection/detection_as_classification_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)      609 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_object_detection/manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1277 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_object_detection/operations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.336434 vision_datasets-1.0.0/vision_datasets/image_regression/
+-rw-r--r--   0 runner    (1001) docker     (123)      296 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_regression/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      877 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_regression/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      320 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_regression/manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_regression/operations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.336434 vision_datasets-1.0.0/vision_datasets/image_text_matching/
+-rw-r--r--   0 runner    (1001) docker     (123)      403 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_text_matching/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      708 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_text_matching/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      418 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_text_matching/manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      966 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_text_matching/operations.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3013 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/image_text_matching/vision_as_image_text_dataset.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.336434 vision_datasets-1.0.0/vision_datasets/multi_task/
+-rw-r--r--   0 runner    (1001) docker     (123)      166 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/multi_task/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1393 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/multi_task/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1416 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/multi_task/operations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.336434 vision_datasets-1.0.0/vision_datasets/text_2_image_retrieval/
+-rw-r--r--   0 runner    (1001) docker     (123)      320 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/text_2_image_retrieval/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      690 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/text_2_image_retrieval/coco_manifest_adaptor.py
+-rw-r--r--   0 runner    (1001) docker     (123)      304 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/text_2_image_retrieval/manifest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 07:31:45.000000 vision_datasets-1.0.0/vision_datasets/text_2_image_retrieval/operations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:31:59.312434 vision_datasets-1.0.0/vision_datasets.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     9545 2023-06-28 07:31:59.000000 vision_datasets-1.0.0/vision_datasets.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6334 2023-06-28 07:31:59.000000 vision_datasets-1.0.0/vision_datasets.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:31:59.000000 vision_datasets-1.0.0/vision_datasets.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      400 2023-06-28 07:31:59.000000 vision_datasets-1.0.0/vision_datasets.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      116 2023-06-28 07:31:59.000000 vision_datasets-1.0.0/vision_datasets.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 07:31:59.000000 vision_datasets-1.0.0/vision_datasets.egg-info/top_level.txt
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `vision_datasets-0.2.9/LICENSE` & `vision_datasets-1.0.0/LICENSE`

 * *Ordering differences only*

 * *Files 14% similar despite different names*

```diff
@@ -1,21 +1,21 @@
-    MIT License
-
-    Copyright (c) Microsoft Corporation.
-
-    Permission is hereby granted, free of charge, to any person obtaining a copy
-    of this software and associated documentation files (the "Software"), to deal
-    in the Software without restriction, including without limitation the rights
-    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
-    copies of the Software, and to permit persons to whom the Software is
-    furnished to do so, subject to the following conditions:
-
-    The above copyright notice and this permission notice shall be included in all
-    copies or substantial portions of the Software.
-
-    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
-    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
-    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
-    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
-    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
-    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
-    SOFTWARE
+    MIT License
+
+    Copyright (c) Microsoft Corporation.
+
+    Permission is hereby granted, free of charge, to any person obtaining a copy
+    of this software and associated documentation files (the "Software"), to deal
+    in the Software without restriction, including without limitation the rights
+    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
+    copies of the Software, and to permit persons to whom the Software is
+    furnished to do so, subject to the following conditions:
+
+    The above copyright notice and this permission notice shall be included in all
+    copies or substantial portions of the Software.
+
+    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
+    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
+    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
+    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
+    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
+    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
+    SOFTWARE
```

### Comparing `vision_datasets-0.2.9/PKG-INFO` & `vision_datasets-1.0.0/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,159 +1,181 @@
-Metadata-Version: 2.1
-Name: vision_datasets
-Version: 0.2.9
-Summary: A utility repo for vision dataset access and management.
-Home-page: https://github.com/microsoft/vision-datasets
-Author: Ping Jin, Shohei Ono
-License: MIT
-Description: # Vision Datasets
-        
-        ## Introduction
-        
-        This repo
-        
-        - defines unified contract for dataset for purposes such as training, visualization, and exploration, via `DatasetManifest` and `ImageDataManifest`.
-        - provides API for organizing and accessing datasets, via `DatasetHub`
-        
-        Currently, five `basic` types of data are supported: 
-        - `classification_multiclass`: each image can is only with one label.
-        - `classification_multilabel`: each image can is with one or multiple labels (e.g., 'cat', 'animal', 'pet').
-        - `object_detection`: each image is labeled with bounding boxes surrounding the objects of interest.
-        - `image_caption`: each image is labeled with a few texts describing the images.
-        - `image_text_matching`: each image is associated with a collection of texts describing the image, and whether each text description matches the image or not
-        
-        `multitask` type is a composition type, where one set of images has multiple sets of annotations available for different tasks, where each task can be of any basic type.
-        
-        
-        ## Dataset Contracts
-        
-        - `DatasetManifest` wraps the information about a dataset including labelmap, images (width, height, path to image), and annotations. `ImageDataManifest` encapsulates information about each image.
-        - `ImageDataManifest` encapsulates image-specific information, such as image id, path, labels, and width/height. One thing to note here is that the image path can be
-            1. a local path (absolute `c:\images\1.jpg` or relative `images\1.jpg`)
-            2. a local path in a **non-compressed** zip file (absolute `c:\images.zip@1.jpg` or relative `images.zip@1.jpg`) or
-            3. an url
-        - `ManifestDataset` is an iterable dataset class that consumes the information from `DatasetManifest`.
-        
-        `ManifestDataset` is able to load the data from all three kinds of paths. Both 1. and 2. are good for training, as they access data from local disk while the 3rd one is good for data exploration, if you have the data in azure storage.
-        
-        For `multitask` dataset, the labels stored in the `ImageDataManifest` is a `dict` mapping from task name to that task's labels. The labelmap stored in `DatasetManifest` is also a `dict` mapping from task name to that task's labels.
-        
-        ### Creating DatasetManifest
-        
-        In addition to loading a serialized `DatasetManifest` for instantiation, this repo currently supports two formats of data that can instantiates `DatasetManifest`,
-        using `DatasetManifest.create_dataset_manifest(dataset_info, usage, container_sas_or_root_dir)`: `COCO` and `IRIS` (legacy).
-        
-        `DatasetInfo` as the first arg in the arg list wraps the metainfo about the dataset like the name of the dataset, locations of the images, annotation files, etc. See examples in the sections below
-        for different data formats.
-        
-        Once a `DatasetManifest` is created, you can create a `ManifestDataset` for accessing the data in the dataset, especially the image data, for training, visualization, etc:
-        
-        ```{python}
-        dataset = ManifestDataset(dataset_info, dataset_manifest, coordinates='relative')
-        ```
-        
-        #### Coco format
-        
-        Here is an example with explanation of what a `DatasetInfo` looks like for coco format, when it is serialized into json:
-        
-        ```{json}
-            {
-                "name": "sampled-ms-coco",
-                "version": 1,
-                "description": "A sampled ms-coco dataset.",
-                "type": "object_detection",
-                "format": "coco", // indicating the annotation data are stored in coco format
-                "root_folder": "detection/coco2017_20200401", // a root folder for all files listed
-                "train": {
-                    "index_path": "train.json", // coco json file for training, see next section for example
-                    "files_for_local_usage": [ // associated files including data such as images
-                        "images/train_images.zip"
-                    ]
-                },
-                "val": {
-                    "index_path": "val.json",
-                    "files_for_local_usage": [
-                        "images/val_images.zip"
-                    ]
-                },
-                "test": {
-                    "index_path": "test.json",
-                    "files_for_local_usage": [
-                        "images/test_images.zip"
-                    ]
-                }
-            }
-        ```
-        
-        Coco annotation format details w.r.t. `multiclass/label_classification`, `object_detection`, `image_caption`, `image_text_match` and `multitask`  can be found in `COCO_DATA_FORMAT.md`.
-        
-        
-        #### Iris format
-        
-        Iris format is a legacy format which can be found in `IRIS_DATA_FORMAT.md`. Only `multiclass/label_classification`, `object_detection` and `multitask` are supported.
-        
-        ## Dataset management and access
-        
-        Once you have multiple datasets, it is more convenient to have all the `DatasetInfo` in one place and instantiate `DatasetManifest` or even `ManifestDataset` by just using the dataset name, usage (
-        train, val ,test) and version.
-        
-        This repo offers the class `DatasetHub` for this purpose. Once instantiated with a json including the `DatasetInfo` for all datasets, you can retrieve a `ManifestDataset` by
-        
-        ```{python}
-        import pathlib
-        
-        dataset_infos_json_path = 'datasets.json'
-        dataset_hub = DatasetHub(pathlib.Path(dataset_infos_json_path).read_text())
-        stanford_cars = dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage='train')
-        
-        # note that you can pass multiple datasets.json to DatasetHub, it can combine them all
-        # example: DatasetHub([ds_json1, ds_json2, ...])
-        # note that you can specify multiple usages in create_manifest_dataset call
-        # example dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=['train', 'val'])
-        
-        for img, targets, sample_idx_str in stanford_cars:
-            img.show()
-            img.close()
-            print(targets)
-        ```
-        
-        Note that this hub class works with data saved in both Azure Blob container and on local disk.
-        
-        If `local_dir`:
-        
-        1. is provided, the hub will look for the resources locally and **download the data** (files included in "
-           files_for_local_usage", the index files, metadata (if iris format), labelmap (if iris format))
-           from `blob_container_sas` if not present locally
-        2. is NOT provided (i.e. `None`), the hub will create a manifest dataset that directly consumes data from the blob
-           indicated by `blob_container_sas`. Note that this does not work, if data are stored in zipped files. You will have to
-           unzip your data in the azure blob. (Index files requires no update, if image paths are for zip files: "a.zip@1.jpg").
-           This kind of azure-based dataset is good for large dataset exploration, but can be slow for training.
-        
-        When data exists on local disk, `blob_container_sas` can be `None`.
-        
-        ### Training with PyTorch
-        
-        Training with PyTorch is easy. After instantiating a `ManifestDataset`, simply passing it in `vision_datasets.pytorch.torch_dataset.TorchDataset` together with the `transform`, then you are good to go with the PyTorch DataLoader for training.
-        
-        ### Managing datasets with DatasetHub on cloud storage
-        
-        If you are using `DatasetHub` to manage datasets in cloud storage, we recommend zipping (with uncompressed mode) the images into one or multiple zip files before uploading it and update the file path in index files to be like `train.zip@1.jpg` from `train\1.jpg`. You can do it with `7zip` (set compression level to 'store') on Windows or [zip](https://superuser.com/questions/411394/zip-files-without-compression) command on Linux.
-        
-        If you upload folders of images directly to cloud storage:
-        
-        - you will need to list all images in `"files_for_local_usage"`, which can be millions of entries
-        - downloading images one by one (even with multithreading) is much slower than downloading a few zip files
-        
-        One more thing is that sometimes when you create a zip file `train.zip`, you might find out that there is only one `train` folder in the zip. This will fail the file loading if the path is `train.zip@1.jpg`, as the image is actually at `train.zip@train\1.jpg`. It is ok to have this extra layer but please make sure the path is correct.
-        
-Keywords: vision datasets classification detection
-Platform: UNKNOWN
-Classifier: Development Status :: 4 - Beta
-Classifier: Intended Audience :: Developers
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python :: 3.6
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Requires-Python: >=3.6
-Description-Content-Type: text/markdown
-Provides-Extra: run
+Metadata-Version: 2.1
+Name: vision_datasets
+Version: 1.0.0
+Summary: A utility repo for vision dataset access and management.
+Home-page: https://github.com/microsoft/vision-datasets
+Author: Ping Jin, Shohei Ono
+License: MIT
+Keywords: vision datasets classification detection
+Classifier: Development Status :: 4 - Beta
+Classifier: Intended Audience :: Developers
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Requires-Python: >=3.8
+Description-Content-Type: text/markdown
+Provides-Extra: run
+License-File: LICENSE
+
+# Vision Datasets
+
+## Introduction
+
+This repo
+
+- defines unified contract for dataset for purposes such as training, visualization, and exploration, via `DatasetManifest`, `ImageDataManifest`, etc.
+- provides many commonly used dataset operation, such as sample dataset by categories, sample few-shot sub-dataset, sample dataset by ratios, train-test split, merge dataset, etc. (See [Here](#oom))
+- provides API for organizing and accessing datasets, via `DatasetHub`
+
+Currently, seven `basic` types of data are supported:
+
+- `image_classification_multiclass`: each image can is only with one label.
+- `image_classification_multilabel`: each image can is with one or multiple labels (e.g., 'cat', 'animal', 'pet').
+- `image_object_detection`: each image is labeled with bounding boxes surrounding the objects of interest.
+- `image_text_matching`: each image is associated with a collection of texts describing the image, and whether each text description matches the image or not.
+- `image_matting`: each image has a pixel-wise annotation, where each pixel is labeled as 'foreground' or 'background'.
+- `image_regression`: each image is labeled with a real-valued numeric regression target.
+- `image_caption`: each image is labeled with a few texts describing the images.
+- `text_2_image_retrieval`: each image is labeled with a number of text queries describing the image. Optionally, an image is associated with one label.
+
+`multitask` type is a composition type, where one set of images has multiple sets of annotations available for different tasks, where each task can be of any basic type.
+
+**Note that `image_caption` and `text_2_image_retrieval` might be merged into `image_text_matching` in future.**
+
+## Dataset Contracts
+
+- `DatasetManifest` wraps the information about a dataset including labelmap, images (width, height, path to image), and annotations. `ImageDataManifest` encapsulates information about each image.
+- `ImageDataManifest` encapsulates image-specific information, such as image id, path, labels, and width/height. One thing to note here is that the image path can be
+    1. a local path (absolute `c:\images\1.jpg` or relative `images\1.jpg`)
+    2. a local path in a **non-compressed** zip file (absolute `c:\images.zip@1.jpg` or relative `images.zip@1.jpg`) or
+    3. an url
+- `ImageLabelManifest`: encapsulates one single image-level annotation
+- `CategoryManifest`: encapsulates the information about a category, such as its name and super category, if applicable
+- `VisionDataset` is an iterable dataset class that consumes the information from `DatasetManifest`.
+
+`VisionDataset` is able to load the data from all three kinds of paths. Both 1. and 2. are good for training, as they access data from local disk while the 3rd one is good for data exploration, if you have the data in azure storage.
+
+For `multitask` dataset, the labels stored in the `ImageDataManifest` is a `dict` mapping from task name to that task's labels. The labelmap stored in `DatasetManifest` is also a `dict` mapping from task name to that task's labels.
+
+### Creating DatasetManifest
+
+In addition to loading a serialized `DatasetManifest` for instantiation, this repo currently supports two formats of data that can instantiates `DatasetManifest`,
+using `DatasetManifest.create_dataset_manifest(dataset_info, usage, container_sas_or_root_dir)`: `COCO` and `IRIS` (legacy).
+
+`DatasetInfo` as the first arg in the arg list wraps the metainfo about the dataset like the name of the dataset, locations of the images, annotation files, etc. See examples in the sections below
+for different data formats.
+
+Once a `DatasetManifest` is created, you can create a `VisionDataset` for accessing the data in the dataset, especially the image data, for training, visualization, etc:
+
+```{python}
+dataset = VisionDataset(dataset_info, dataset_manifest, coordinates='relative')
+```
+
+#### Coco format
+
+Here is an example with explanation of what a `DatasetInfo` looks like for coco format, when it is serialized into json:
+
+```json
+    {
+        "name": "sampled-ms-coco",
+        "version": 1,
+        "description": "A sampled ms-coco dataset.",
+        "type": "object_detection",
+        "format": "coco", // indicating the annotation data are stored in coco format
+        "root_folder": "detection/coco2017_20200401", // a root folder for all files listed
+        "train": {
+            "index_path": "train.json", // coco json file for training, see next section for example
+            "files_for_local_usage": [ // associated files including data such as images
+                "images/train_images.zip"
+            ]
+        },
+        "val": {
+            "index_path": "val.json",
+            "files_for_local_usage": [
+                "images/val_images.zip"
+            ]
+        },
+        "test": {
+            "index_path": "test.json",
+            "files_for_local_usage": [
+                "images/test_images.zip"
+            ]
+        }
+    }
+```
+
+Coco annotation format details w.r.t. `image_classification_multiclass/label`, `image_object_detection`, `image_caption`, `image_text_match` and `multitask`  can be found in `COCO_DATA_FORMAT.md`.
+
+Index file can be put into a zip file as well (e.g., `annotations.zip@train.json`), no need to add the this zip to "files_for_local_usage" explicitly.
+
+#### Iris format
+
+Iris format is a legacy format which can be found in `IRIS_DATA_FORMAT.md`. Only `multiclass/label_classification`, `object_detection` and `multitask` are supported.
+
+## Dataset management and access
+
+Check [DATA_PREPARATION.md](DATA_PREPARATION.md) for complete guide on how to prepare datasets in steps.
+
+Once you have multiple datasets, it is more convenient to have all the `DatasetInfo` in one place and instantiate `DatasetManifest` or even `VisionDataset` by just using the dataset name, usage (
+train, val ,test) and version.
+
+This repo offers the class `DatasetHub` for this purpose. Once instantiated with a json including the `DatasetInfo` for all datasets, you can retrieve a `VisionDataset` by
+
+```python
+import pathlib
+from vision_datasets.common import Usages, DatasetHub
+
+dataset_infos_json_path = 'datasets.json'
+dataset_hub = DatasetHub(pathlib.Path(dataset_infos_json_path).read_text())
+stanford_cars = dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=Usages.TRAIN)
+
+# note that you can pass multiple datasets.json to DatasetHub, it can combine them all
+# example: DatasetHub([ds_json1, ds_json2, ...])
+# note that you can specify multiple usages in create_manifest_dataset call
+# example dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=[Usages.TRAIN, Usages.VAL])
+
+for img, targets, sample_idx_str in stanford_cars:
+    img.show()
+    img.close()
+    print(targets)
+```
+
+Note that this hub class works with data saved in both Azure Blob container and on local disk.
+
+If `local_dir`:
+
+1. is provided, the hub will look for the resources locally and **download the data** (files included in "
+   files_for_local_usage", the index files, metadata (if iris format), labelmap (if iris format))
+   from `blob_container_sas` if not present locally
+2. is NOT provided (i.e. `None`), the hub will create a manifest dataset that directly consumes data from the blob
+   indicated by `blob_container_sas`. Note that this does not work, if data are stored in zipped files. You will have to
+   unzip your data in the azure blob. (Index files requires no update, if image paths are for zip files: `a.zip@1.jpg`).
+   This kind of azure-based dataset is good for large dataset exploration, but can be slow for training.
+
+When data exists on local disk, `blob_container_sas` can be `None`.
+
+## Operations on manifests {#oom}
+
+There are supported operations on manifests for different data types, such as split, merge, sample, etc. You can run
+
+`vision_list_supported_operations -d {DATA_TYPE}`
+
+to see the supported operations for a specific data type. You can use the factory classes in `vision_datasets.common.factory` to create operations for certain data type.
+
+```python
+from vision_datasets.common import DatasetTypes, SplitFactory, SplitConfig
+
+
+data_manifest = ....
+splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SplitConfig(ratio=0.3))
+manifest_1, manifest_2 = splitter.run(data_manifest)
+```
+
+### Training with PyTorch
+
+Training with PyTorch is easy. After instantiating a `VisionDataset`, simply passing it in `vision_datasets.common.dataset.TorchDataset` together with the `transform`, then you are good to go with the PyTorch DataLoader for training.
+
+
+## Helpful commands
+
+There are a few commands that come with this repo once installed, such as datset check and download, detection conversion to classification dataset, and so on, check [`UTIL_COMMANDS.md`](./UTIL_COMMANDS.md) for details.
```

### Comparing `vision_datasets-0.2.9/README.md` & `vision_datasets-1.0.0/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -1,139 +1,162 @@
-# Vision Datasets
-
-## Introduction
-
-This repo
-
-- defines unified contract for dataset for purposes such as training, visualization, and exploration, via `DatasetManifest` and `ImageDataManifest`.
-- provides API for organizing and accessing datasets, via `DatasetHub`
-
-Currently, five `basic` types of data are supported: 
-- `classification_multiclass`: each image can is only with one label.
-- `classification_multilabel`: each image can is with one or multiple labels (e.g., 'cat', 'animal', 'pet').
-- `object_detection`: each image is labeled with bounding boxes surrounding the objects of interest.
-- `image_caption`: each image is labeled with a few texts describing the images.
-- `image_text_matching`: each image is associated with a collection of texts describing the image, and whether each text description matches the image or not
-
-`multitask` type is a composition type, where one set of images has multiple sets of annotations available for different tasks, where each task can be of any basic type.
-
-
-## Dataset Contracts
-
-- `DatasetManifest` wraps the information about a dataset including labelmap, images (width, height, path to image), and annotations. `ImageDataManifest` encapsulates information about each image.
-- `ImageDataManifest` encapsulates image-specific information, such as image id, path, labels, and width/height. One thing to note here is that the image path can be
-    1. a local path (absolute `c:\images\1.jpg` or relative `images\1.jpg`)
-    2. a local path in a **non-compressed** zip file (absolute `c:\images.zip@1.jpg` or relative `images.zip@1.jpg`) or
-    3. an url
-- `ManifestDataset` is an iterable dataset class that consumes the information from `DatasetManifest`.
-
-`ManifestDataset` is able to load the data from all three kinds of paths. Both 1. and 2. are good for training, as they access data from local disk while the 3rd one is good for data exploration, if you have the data in azure storage.
-
-For `multitask` dataset, the labels stored in the `ImageDataManifest` is a `dict` mapping from task name to that task's labels. The labelmap stored in `DatasetManifest` is also a `dict` mapping from task name to that task's labels.
-
-### Creating DatasetManifest
-
-In addition to loading a serialized `DatasetManifest` for instantiation, this repo currently supports two formats of data that can instantiates `DatasetManifest`,
-using `DatasetManifest.create_dataset_manifest(dataset_info, usage, container_sas_or_root_dir)`: `COCO` and `IRIS` (legacy).
-
-`DatasetInfo` as the first arg in the arg list wraps the metainfo about the dataset like the name of the dataset, locations of the images, annotation files, etc. See examples in the sections below
-for different data formats.
-
-Once a `DatasetManifest` is created, you can create a `ManifestDataset` for accessing the data in the dataset, especially the image data, for training, visualization, etc:
-
-```{python}
-dataset = ManifestDataset(dataset_info, dataset_manifest, coordinates='relative')
-```
-
-#### Coco format
-
-Here is an example with explanation of what a `DatasetInfo` looks like for coco format, when it is serialized into json:
-
-```{json}
-    {
-        "name": "sampled-ms-coco",
-        "version": 1,
-        "description": "A sampled ms-coco dataset.",
-        "type": "object_detection",
-        "format": "coco", // indicating the annotation data are stored in coco format
-        "root_folder": "detection/coco2017_20200401", // a root folder for all files listed
-        "train": {
-            "index_path": "train.json", // coco json file for training, see next section for example
-            "files_for_local_usage": [ // associated files including data such as images
-                "images/train_images.zip"
-            ]
-        },
-        "val": {
-            "index_path": "val.json",
-            "files_for_local_usage": [
-                "images/val_images.zip"
-            ]
-        },
-        "test": {
-            "index_path": "test.json",
-            "files_for_local_usage": [
-                "images/test_images.zip"
-            ]
-        }
-    }
-```
-
-Coco annotation format details w.r.t. `multiclass/label_classification`, `object_detection`, `image_caption`, `image_text_match` and `multitask`  can be found in `COCO_DATA_FORMAT.md`.
-
-
-#### Iris format
-
-Iris format is a legacy format which can be found in `IRIS_DATA_FORMAT.md`. Only `multiclass/label_classification`, `object_detection` and `multitask` are supported.
-
-## Dataset management and access
-
-Once you have multiple datasets, it is more convenient to have all the `DatasetInfo` in one place and instantiate `DatasetManifest` or even `ManifestDataset` by just using the dataset name, usage (
-train, val ,test) and version.
-
-This repo offers the class `DatasetHub` for this purpose. Once instantiated with a json including the `DatasetInfo` for all datasets, you can retrieve a `ManifestDataset` by
-
-```{python}
-import pathlib
-
-dataset_infos_json_path = 'datasets.json'
-dataset_hub = DatasetHub(pathlib.Path(dataset_infos_json_path).read_text())
-stanford_cars = dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage='train')
-
-# note that you can pass multiple datasets.json to DatasetHub, it can combine them all
-# example: DatasetHub([ds_json1, ds_json2, ...])
-# note that you can specify multiple usages in create_manifest_dataset call
-# example dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=['train', 'val'])
-
-for img, targets, sample_idx_str in stanford_cars:
-    img.show()
-    img.close()
-    print(targets)
-```
-
-Note that this hub class works with data saved in both Azure Blob container and on local disk.
-
-If `local_dir`:
-
-1. is provided, the hub will look for the resources locally and **download the data** (files included in "
-   files_for_local_usage", the index files, metadata (if iris format), labelmap (if iris format))
-   from `blob_container_sas` if not present locally
-2. is NOT provided (i.e. `None`), the hub will create a manifest dataset that directly consumes data from the blob
-   indicated by `blob_container_sas`. Note that this does not work, if data are stored in zipped files. You will have to
-   unzip your data in the azure blob. (Index files requires no update, if image paths are for zip files: "a.zip@1.jpg").
-   This kind of azure-based dataset is good for large dataset exploration, but can be slow for training.
-
-When data exists on local disk, `blob_container_sas` can be `None`.
-
-### Training with PyTorch
-
-Training with PyTorch is easy. After instantiating a `ManifestDataset`, simply passing it in `vision_datasets.pytorch.torch_dataset.TorchDataset` together with the `transform`, then you are good to go with the PyTorch DataLoader for training.
-
-### Managing datasets with DatasetHub on cloud storage
-
-If you are using `DatasetHub` to manage datasets in cloud storage, we recommend zipping (with uncompressed mode) the images into one or multiple zip files before uploading it and update the file path in index files to be like `train.zip@1.jpg` from `train\1.jpg`. You can do it with `7zip` (set compression level to 'store') on Windows or [zip](https://superuser.com/questions/411394/zip-files-without-compression) command on Linux.
-
-If you upload folders of images directly to cloud storage:
-
-- you will need to list all images in `"files_for_local_usage"`, which can be millions of entries
-- downloading images one by one (even with multithreading) is much slower than downloading a few zip files
-
-One more thing is that sometimes when you create a zip file `train.zip`, you might find out that there is only one `train` folder in the zip. This will fail the file loading if the path is `train.zip@1.jpg`, as the image is actually at `train.zip@train\1.jpg`. It is ok to have this extra layer but please make sure the path is correct.
+# Vision Datasets
+
+## Introduction
+
+This repo
+
+- defines unified contract for dataset for purposes such as training, visualization, and exploration, via `DatasetManifest`, `ImageDataManifest`, etc.
+- provides many commonly used dataset operation, such as sample dataset by categories, sample few-shot sub-dataset, sample dataset by ratios, train-test split, merge dataset, etc. (See [Here](#oom))
+- provides API for organizing and accessing datasets, via `DatasetHub`
+
+Currently, seven `basic` types of data are supported:
+
+- `image_classification_multiclass`: each image can is only with one label.
+- `image_classification_multilabel`: each image can is with one or multiple labels (e.g., 'cat', 'animal', 'pet').
+- `image_object_detection`: each image is labeled with bounding boxes surrounding the objects of interest.
+- `image_text_matching`: each image is associated with a collection of texts describing the image, and whether each text description matches the image or not.
+- `image_matting`: each image has a pixel-wise annotation, where each pixel is labeled as 'foreground' or 'background'.
+- `image_regression`: each image is labeled with a real-valued numeric regression target.
+- `image_caption`: each image is labeled with a few texts describing the images.
+- `text_2_image_retrieval`: each image is labeled with a number of text queries describing the image. Optionally, an image is associated with one label.
+
+`multitask` type is a composition type, where one set of images has multiple sets of annotations available for different tasks, where each task can be of any basic type.
+
+**Note that `image_caption` and `text_2_image_retrieval` might be merged into `image_text_matching` in future.**
+
+## Dataset Contracts
+
+- `DatasetManifest` wraps the information about a dataset including labelmap, images (width, height, path to image), and annotations. `ImageDataManifest` encapsulates information about each image.
+- `ImageDataManifest` encapsulates image-specific information, such as image id, path, labels, and width/height. One thing to note here is that the image path can be
+    1. a local path (absolute `c:\images\1.jpg` or relative `images\1.jpg`)
+    2. a local path in a **non-compressed** zip file (absolute `c:\images.zip@1.jpg` or relative `images.zip@1.jpg`) or
+    3. an url
+- `ImageLabelManifest`: encapsulates one single image-level annotation
+- `CategoryManifest`: encapsulates the information about a category, such as its name and super category, if applicable
+- `VisionDataset` is an iterable dataset class that consumes the information from `DatasetManifest`.
+
+`VisionDataset` is able to load the data from all three kinds of paths. Both 1. and 2. are good for training, as they access data from local disk while the 3rd one is good for data exploration, if you have the data in azure storage.
+
+For `multitask` dataset, the labels stored in the `ImageDataManifest` is a `dict` mapping from task name to that task's labels. The labelmap stored in `DatasetManifest` is also a `dict` mapping from task name to that task's labels.
+
+### Creating DatasetManifest
+
+In addition to loading a serialized `DatasetManifest` for instantiation, this repo currently supports two formats of data that can instantiates `DatasetManifest`,
+using `DatasetManifest.create_dataset_manifest(dataset_info, usage, container_sas_or_root_dir)`: `COCO` and `IRIS` (legacy).
+
+`DatasetInfo` as the first arg in the arg list wraps the metainfo about the dataset like the name of the dataset, locations of the images, annotation files, etc. See examples in the sections below
+for different data formats.
+
+Once a `DatasetManifest` is created, you can create a `VisionDataset` for accessing the data in the dataset, especially the image data, for training, visualization, etc:
+
+```{python}
+dataset = VisionDataset(dataset_info, dataset_manifest, coordinates='relative')
+```
+
+#### Coco format
+
+Here is an example with explanation of what a `DatasetInfo` looks like for coco format, when it is serialized into json:
+
+```json
+    {
+        "name": "sampled-ms-coco",
+        "version": 1,
+        "description": "A sampled ms-coco dataset.",
+        "type": "object_detection",
+        "format": "coco", // indicating the annotation data are stored in coco format
+        "root_folder": "detection/coco2017_20200401", // a root folder for all files listed
+        "train": {
+            "index_path": "train.json", // coco json file for training, see next section for example
+            "files_for_local_usage": [ // associated files including data such as images
+                "images/train_images.zip"
+            ]
+        },
+        "val": {
+            "index_path": "val.json",
+            "files_for_local_usage": [
+                "images/val_images.zip"
+            ]
+        },
+        "test": {
+            "index_path": "test.json",
+            "files_for_local_usage": [
+                "images/test_images.zip"
+            ]
+        }
+    }
+```
+
+Coco annotation format details w.r.t. `image_classification_multiclass/label`, `image_object_detection`, `image_caption`, `image_text_match` and `multitask`  can be found in `COCO_DATA_FORMAT.md`.
+
+Index file can be put into a zip file as well (e.g., `annotations.zip@train.json`), no need to add the this zip to "files_for_local_usage" explicitly.
+
+#### Iris format
+
+Iris format is a legacy format which can be found in `IRIS_DATA_FORMAT.md`. Only `multiclass/label_classification`, `object_detection` and `multitask` are supported.
+
+## Dataset management and access
+
+Check [DATA_PREPARATION.md](DATA_PREPARATION.md) for complete guide on how to prepare datasets in steps.
+
+Once you have multiple datasets, it is more convenient to have all the `DatasetInfo` in one place and instantiate `DatasetManifest` or even `VisionDataset` by just using the dataset name, usage (
+train, val ,test) and version.
+
+This repo offers the class `DatasetHub` for this purpose. Once instantiated with a json including the `DatasetInfo` for all datasets, you can retrieve a `VisionDataset` by
+
+```python
+import pathlib
+from vision_datasets.common import Usages, DatasetHub
+
+dataset_infos_json_path = 'datasets.json'
+dataset_hub = DatasetHub(pathlib.Path(dataset_infos_json_path).read_text())
+stanford_cars = dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=Usages.TRAIN)
+
+# note that you can pass multiple datasets.json to DatasetHub, it can combine them all
+# example: DatasetHub([ds_json1, ds_json2, ...])
+# note that you can specify multiple usages in create_manifest_dataset call
+# example dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=[Usages.TRAIN, Usages.VAL])
+
+for img, targets, sample_idx_str in stanford_cars:
+    img.show()
+    img.close()
+    print(targets)
+```
+
+Note that this hub class works with data saved in both Azure Blob container and on local disk.
+
+If `local_dir`:
+
+1. is provided, the hub will look for the resources locally and **download the data** (files included in "
+   files_for_local_usage", the index files, metadata (if iris format), labelmap (if iris format))
+   from `blob_container_sas` if not present locally
+2. is NOT provided (i.e. `None`), the hub will create a manifest dataset that directly consumes data from the blob
+   indicated by `blob_container_sas`. Note that this does not work, if data are stored in zipped files. You will have to
+   unzip your data in the azure blob. (Index files requires no update, if image paths are for zip files: `a.zip@1.jpg`).
+   This kind of azure-based dataset is good for large dataset exploration, but can be slow for training.
+
+When data exists on local disk, `blob_container_sas` can be `None`.
+
+## Operations on manifests {#oom}
+
+There are supported operations on manifests for different data types, such as split, merge, sample, etc. You can run
+
+`vision_list_supported_operations -d {DATA_TYPE}`
+
+to see the supported operations for a specific data type. You can use the factory classes in `vision_datasets.common.factory` to create operations for certain data type.
+
+```python
+from vision_datasets.common import DatasetTypes, SplitFactory, SplitConfig
+
+
+data_manifest = ....
+splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SplitConfig(ratio=0.3))
+manifest_1, manifest_2 = splitter.run(data_manifest)
+```
+
+### Training with PyTorch
+
+Training with PyTorch is easy. After instantiating a `VisionDataset`, simply passing it in `vision_datasets.common.dataset.TorchDataset` together with the `transform`, then you are good to go with the PyTorch DataLoader for training.
+
+
+## Helpful commands
+
+There are a few commands that come with this repo once installed, such as datset check and download, detection conversion to classification dataset, and so on, check [`UTIL_COMMANDS.md`](./UTIL_COMMANDS.md) for details.
```

### Comparing `vision_datasets-0.2.9/tests/test_box_alteration.py` & `vision_datasets-1.0.0/tests/test_box_alteration.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,63 +1,62 @@
-import random
-import unittest
-
-from vision_datasets.common.manifest_dataset import BoxAlteration
-
-
-class TestBoxAlteration(unittest.TestCase):
-    def test_zoom_box_out_of_range(self):
-        left, t, r, b = BoxAlteration.zoom_box(10, 10, 20, 20, 100, 100, 50, 51, random.Random(0))
-        assert left == 0
-        assert t == 0
-        assert r == 100
-        assert b == 100
-
-    def test_zoom_box_shrink_to_pt(self):
-        left, t, r, b = BoxAlteration.zoom_box(10, 5, 20, 25, 100, 100, 0, 0, random.Random(0))
-        assert left == 15
-        assert t == 15
-        assert r == 15
-        assert b == 15
-
-    def test_zoom_box_no_change(self):
-        left, t, r, b = BoxAlteration.zoom_box(10, 5, 20, 25, 100, 100, 1, 1, random.Random(0))
-        assert left == 10
-        assert t == 5
-        assert r == 20
-        assert b == 25
-
-    def test_shift_box_no_change(self):
-        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, 0, 0, random.Random(0))
-        assert left == 10
-        assert t == 5
-        assert r == 20
-        assert b == 25
-
-    def test_shift_box_rb_out(self):
-        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, 50, 50, random.Random(0))
-        assert left == 100
-        assert t == 100
-        assert r == 100
-        assert b == 100
-
-    def test_shift_box_lt_out(self):
-        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, -50, -50, random.Random(0))
-        assert left == 0
-        assert t == 0
-        assert r == 0
-        assert b == 0
-
-    def test_shift_box_rb(self):
-        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, 1, 1, random.Random(0))
-        assert left == 20
-        assert t == 25
-        assert r == 30
-        assert b == 45
-
-    def test_shift_box_lt(self):
-        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, -0.1, -0.1, random.Random(0))
-        print(left, t, r, b)
-        assert left == 9
-        assert t == 3
-        assert r == 19
-        assert b == 23
+import random
+import unittest
+
+from vision_datasets.image_object_detection.detection_as_classification_dataset import BoxAlteration
+
+
+class TestBoxAlteration(unittest.TestCase):
+    def test_zoom_box_out_of_range(self):
+        left, t, r, b = BoxAlteration.zoom_box(10, 10, 20, 20, 100, 100, 50, 51, random.Random(0))
+        assert left == 0
+        assert t == 0
+        assert r == 100
+        assert b == 100
+
+    def test_zoom_box_shrink_to_pt(self):
+        left, t, r, b = BoxAlteration.zoom_box(10, 5, 20, 25, 100, 100, 0, 0, random.Random(0))
+        assert left == 15
+        assert t == 15
+        assert r == 15
+        assert b == 15
+
+    def test_zoom_box_no_change(self):
+        left, t, r, b = BoxAlteration.zoom_box(10, 5, 20, 25, 100, 100, 1, 1, random.Random(0))
+        assert left == 10
+        assert t == 5
+        assert r == 20
+        assert b == 25
+
+    def test_shift_box_no_change(self):
+        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, 0, 0, random.Random(0))
+        assert left == 10
+        assert t == 5
+        assert r == 20
+        assert b == 25
+
+    def test_shift_box_rb_out(self):
+        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, 50, 50, random.Random(0))
+        assert left == 100
+        assert t == 100
+        assert r == 100
+        assert b == 100
+
+    def test_shift_box_lt_out(self):
+        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, -50, -50, random.Random(0))
+        assert left == 0
+        assert t == 0
+        assert r == 0
+        assert b == 0
+
+    def test_shift_box_rb(self):
+        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, 1, 1, random.Random(0))
+        assert left == 20
+        assert t == 25
+        assert r == 30
+        assert b == 45
+
+    def test_shift_box_lt(self):
+        left, t, r, b = BoxAlteration.shift_box(10, 5, 20, 25, 100, 100, -0.1, -0.1, random.Random(0))
+        assert left == 9
+        assert t == 3
+        assert r == 19
+        assert b == 23
```

### Comparing `vision_datasets-0.2.9/tests/test_dataset_manifest.py` & `vision_datasets-1.0.0/tests/test_dataset_manifest.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,941 +1,804 @@
-import copy
-import json
-import os
-import pathlib
-import tempfile
-import unittest
-from collections import Counter
-from unittest.mock import patch
-
-from vision_datasets import IrisManifestAdaptor, DatasetInfo, DatasetManifest, CocoManifestAdaptor
-from vision_datasets.common.constants import Usages, DatasetTypes
-from vision_datasets.common.data_manifest import ImageDataManifest
-
-
-def _generate_labelmap(n_classes):
-    return [str(i) for i in range(n_classes)]
-
-
-def _get_instance_count_per_class(manifest):
-    if manifest.is_multitask:
-        return Counter([manifest._get_cid(label, task_name) for image in manifest.images for task_name, task_labels in image.labels.items() for label in task_labels])
-    else:
-        return Counter([manifest._get_cid(label) for image in manifest.images for label in image.labels])
-
-
-def _coco_dict_to_manifest(coco_dict, data_type):
-    with tempfile.TemporaryDirectory() as temp_dir:
-        dm1_path = pathlib.Path(temp_dir) / 'coco.json'
-        dm1_path.write_text(json.dumps(coco_dict))
-        return CocoManifestAdaptor.create_dataset_manifest(str(dm1_path), data_type)
-
-
-class TestCases:
-    ic_manifest_dicts = [
-        {
-            "images": [
-                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "train/1.jpg"},
-                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "train/3.jpg"}],
-            "annotations": [
-                {"id": 1, "category_id": 1, "image_id": 1},
-                {"id": 2, "category_id": 1, "image_id": 2},
-                {"id": 3, "category_id": 2, "image_id": 2}
-            ],
-            "categories": [
-                {"id": 1, "name": "cat"},
-                {"id": 2, "name": "dog"}
-            ]
-        },
-        {
-            "images": [
-                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "test/1.jpg"},
-                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "test/2.jpg"}],
-            "annotations": [
-                {"id": 1, "category_id": 1, "image_id": 1},
-                {"id": 2, "category_id": 1, "image_id": 2},
-                {"id": 3, "category_id": 2, "image_id": 2}
-            ],
-            "categories": [
-                {"id": 1, "name": "tiger"},
-                {"id": 2, "name": "rabbit"}
-            ]
-        },
-        {
-            "images": [
-                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "test/1.jpg"},
-                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "test/2.jpg"}],
-            "annotations": [
-                {"id": 1, "category_id": 1, "image_id": 1},
-                {"id": 2, "category_id": 2, "image_id": 2}
-            ],
-            "categories": [
-                {"id": 1, "name": "cat"},
-                {"id": 2, "name": "dog"}
-            ]
-        }]
-
-    od_manifest_dicts = [
-        {
-            "images": [{"id": 1, "width": 224.0, "height": 224.0, "file_name": "siberian-kitten.jpg"},
-                       {"id": 2, "width": 224.0, "height": 224.0, "file_name": "kitten 3.jpg"}],
-            "annotations": [
-                {"id": 1, "category_id": 1, "image_id": 1, "bbox": [10, 10, 90, 90]},
-                {"id": 2, "category_id": 1, "image_id": 2, "bbox": [100, 100, 100, 100]},
-                {"id": 3, "category_id": 2, "image_id": 2, "bbox": [20, 20, 180, 180]}
-            ],
-            "categories": [
-                {"id": 1, "name": "cat"}, {"id": 2, "name": "dog"}
-            ]
-        },
-        {
-            "images": [{"id": 1, "width": 224.0, "height": 224.0, "file_name": "siberian-kitten.jpg"},
-                       {"id": 2, "width": 224.0, "height": 224.0, "file_name": "kitten 3.jpg"}],
-            "annotations": [
-                {"id": 1, "category_id": 1, "image_id": 1, "bbox": [10, 10, 80, 80]},
-                {"id": 2, "category_id": 1, "image_id": 2, "bbox": [90, 90, 90, 90]},
-                {"id": 3, "category_id": 2, "image_id": 2, "bbox": [20, 20, 180, 180]}
-            ],
-            "categories": [
-                {"id": 1, "name": "tiger"}, {"id": 2, "name": "rabbit"}
-            ]
-        },
-        {
-            "images": [{"id": 1, "width": 224.0, "height": 224.0, "file_name": "siberian-kitten.jpg"},
-                       {"id": 2, "width": 224.0, "height": 224.0, "file_name": "kitten 3.jpg"}],
-            "annotations": [
-                {"id": 1, "category_id": 1, "image_id": 1, "bbox": [10, 10, 80, 80]},
-                {"id": 2, "category_id": 2, "image_id": 2, "bbox": [90, 90, 90, 90]},
-            ],
-            "categories": [
-                {"id": 1, "name": "cat"}, {"id": 2, "name": "dog"}
-            ]
-        }]
-
-    cap_manifest_dicts = [
-        {
-            "images": [{"id": 1, "file_name": "train_images.zip@1.jpg"},
-                       {"id": 2, "file_name": "train_images.zip@2.jpg"}],
-            "annotations": [
-                {"id": 1, "image_id": 1, "caption": "test 1."},
-                {"id": 2, "image_id": 2, "caption": "test 2."},
-            ]
-        },
-        {
-            "images": [{"id": 1, "file_name": "train_images.zip@3.jpg"},
-                       {"id": 2, "file_name": "train_images.zip@4.jpg"}],
-            "annotations": [
-                {"id": 1, "image_id": 1, "caption": "test 3."},
-                {"id": 2, "image_id": 2, "caption": "test 4."},
-            ]
-        },
-        {
-            "images": [{"id": 1, "file_name": "train_images.zip@honda.jpg"},
-                       {"id": 2, "file_name": "train_images.zip@kitchen.jpg"}],
-            "annotations": [
-                {"id": 1, "image_id": 1, "caption": "A black Honda motorcycle parked in front of a garage."},
-                {"id": 2, "image_id": 1, "caption": "A Honda motorcycle parked in a grass driveway."},
-                {"id": 3, "image_id": 1, "caption": "A black Honda motorcycle with a dark burgundy seat."},
-                {"id": 4, "image_id": 1, "caption": "Ma motorcycle parked on the gravel in front of a garage."},
-                {"id": 5, "image_id": 1, "caption": "A motorcycle with its brake extended standing outside."},
-                {"id": 6, "image_id": 2, "caption": "A picture of a modern looking kitchen area.\n"},
-                {"id": 7, "image_id": 2, "caption": "A narrow kitchen ending with a chrome refrigerator."},
-                {"id": 8, "image_id": 2, "caption": "A narrow kitchen is decorated in shades of white, gray, and black."},
-                {"id": 9, "image_id": 2, "caption": "a room that has a stove and a icebox in it"},
-                {"id": 10, "image_id": 2, "caption": "A long empty, minimal modern skylit home kitchen."}
-            ],
-        }]
-
-    image_text_manifest_dicts = [
-        {
-            "images": [{"id": 1, "file_name": "train_images.zip@1.jpg"},
-                       {"id": 2, "file_name": "train_images.zip@2.jpg"}],
-            "annotations": [
-                {"id": 1, "image_id": 1, "text": "test 1.", "match": 0},
-                {"id": 2, "image_id": 2, "text": "test 2.", "match": 0},
-            ]
-        },
-        {
-            "images": [{"id": 1, "file_name": "train_images.zip@3.jpg"},
-                       {"id": 2, "file_name": "train_images.zip@4.jpg"}],
-            "annotations": [
-                {"id": 1, "image_id": 1, "text": "test 3.", "match": 0},
-                {"id": 2, "image_id": 2, "text": "test 4.", "match": 1},
-            ]
-        },
-        {
-            "images": [{"id": 1, "file_name": "train_images.zip@honda.jpg"},
-                       {"id": 2, "file_name": "train_images.zip@kitchen.jpg"}],
-            "annotations": [
-                {"id": 1, "image_id": 1, "text": "A black Honda motorcycle parked in front of a garage.", 'match': 0},
-                {"id": 2, "image_id": 1, "text": "A Honda motorcycle parked in a grass driveway.", 'match': 1},
-                {"id": 3, "image_id": 1, "text": "A black Honda motorcycle with a dark burgundy seat.", 'match': 1},
-                {"id": 4, "image_id": 1, "text": "Ma motorcycle parked on the gravel in front of a garage.", 'match': 0},
-                {"id": 5, "image_id": 1, "text": "A motorcycle with its brake extended standing outside.", 'match': 0},
-                {"id": 6, "image_id": 2, "text": "A picture of a modern looking kitchen area.\n", 'match': 1},
-                {"id": 7, "image_id": 2, "text": "A narrow kitchen ending with a chrome refrigerator.", 'match': 0},
-                {"id": 8, "image_id": 2, "text": "A narrow kitchen is decorated in shades of white, gray, and black.", 'match': 0},
-                {"id": 9, "image_id": 2, "text": "a room that has a stove and a icebox in it", 'match': 0},
-                {"id": 10, "image_id": 2, "text": "A long empty, minimal modern skylit home kitchen.", 'match': 1}
-            ],
-        }]
-
-    manifest_dict_by_data_type = {
-        DatasetTypes.IC_MULTILABEL: ic_manifest_dicts,
-        DatasetTypes.IC_MULTICLASS: ic_manifest_dicts,
-        DatasetTypes.OD: od_manifest_dicts,
-        DatasetTypes.IMCAP: cap_manifest_dicts,
-        DatasetTypes.IMAGE_TEXT_MATCHING: image_text_manifest_dicts
-    }
-
-    @staticmethod
-    def get_manifest(data_type, index):
-        return _coco_dict_to_manifest(TestCases.manifest_dict_by_data_type[data_type][index], data_type)
-
-
-class TestCreateIrisDatasetManifest(unittest.TestCase):
-    DATASET_INFO_DICT = {
-        "name": "dummy",
-        "version": 1,
-        "type": "classification_multiclass",
-        "root_folder": "dummy",
-        "test": {
-            "index_path": "test.txt",
-            "files_for_local_usage": [
-                "Train.zip"
-            ]
-        }
-    }
-
-    def test_detect_object_detection(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write("test.jpg l.txt")
-            with open(os.path.join(tempdir, 'l.txt'), 'w') as f:
-                f.write("0 1 2 3 4")
-            dataset_dict['root_folder'] = str(tempdir)
-            dataset_dict['type'] = 'object_detection'
-            with patch('vision_datasets.common.data_manifest.DatasetManifest') as m:
-                IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-                m.assert_called_once()
-
-    def test_detect_multilabel(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write("test.jpg 2,3")
-            dataset_dict['root_folder'] = str(tempdir)
-            with patch('vision_datasets.common.data_manifest.DatasetManifest') as m:
-                IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-                m.assert_called_once()
-
-    def test_detect_multiclass(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write("test.jpg 2")
-            dataset_dict['root_folder'] = str(tempdir)
-            with patch('vision_datasets.common.data_manifest.DatasetManifest') as m:
-                IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-                m.assert_called_once()
-
-    def test_space_in_image_path(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write("test folder/0.jpg 0\n")
-            dataset_dict['root_folder'] = str(tempdir)
-            dataset_manifest = IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-            self.assertIsInstance(dataset_manifest, DatasetManifest)
-            self.assertEqual(len(dataset_manifest.images), 1)
-            self.assertEqual(len(dataset_manifest.labelmap), 1)
-            self.assertEqual(dataset_manifest.images[0].id, 'test folder/0.jpg')
-            self.assertEqual(dataset_manifest.images[0].labels, [0])
-
-    def test_multiclass(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write("0.jpg 0\n1.jpg 1\n2.jpg 2")
-            dataset_dict['root_folder'] = str(tempdir)
-            dataset_manifest = IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-            self.assertIsInstance(dataset_manifest, DatasetManifest)
-            self.assertEqual(len(dataset_manifest.images), 3)
-            self.assertEqual(len(dataset_manifest.labelmap), 3)
-            self.assertEqual(dataset_manifest.images[0].id, '0.jpg')
-            self.assertEqual(dataset_manifest.images[0].labels, [0])
-            self.assertEqual(dataset_manifest.images[1].id, '1.jpg')
-            self.assertEqual(dataset_manifest.images[1].labels, [1])
-            self.assertEqual(dataset_manifest.images[2].id, '2.jpg')
-            self.assertEqual(dataset_manifest.images[2].labels, [2])
-
-    def test_multilabel(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write("0.jpg 0,1\n1.jpg 1,2\n2.jpg 2")
-            dataset_dict['root_folder'] = str(tempdir)
-            dataset_dict['type'] = 'classification_multilabel'
-            dataset_manifest = IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-
-            self.assertIsInstance(dataset_manifest, DatasetManifest)
-            self.assertEqual(len(dataset_manifest.images), 3)
-            self.assertEqual(len(dataset_manifest.labelmap), 3)
-            self.assertEqual(dataset_manifest.images[0].id, '0.jpg')
-            self.assertEqual(dataset_manifest.images[0].labels, [0, 1])
-            self.assertEqual(dataset_manifest.images[1].id, '1.jpg')
-            self.assertEqual(dataset_manifest.images[1].labels, [1, 2])
-            self.assertEqual(dataset_manifest.images[2].id, '2.jpg')
-            self.assertEqual(dataset_manifest.images[2].labels, [2])
-
-    def test_labelmap_exists(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            file_path = os.path.join(tempdir, 'test.txt')
-            with open(file_path, 'w') as f:
-                f.write("0.jpg 0,1\n1.jpg 1,2\n2.jpg 2")
-            label_file_path = os.path.join(tempdir, 'labels.txt')
-            with open(label_file_path, 'w') as f:
-                f.write('custom_label0\ncustom_label1\ncustom_label2\n')
-            dataset_dict['root_folder'] = str(tempdir)
-            dataset_dict['type'] = 'classification_multilabel'
-            dataset_dict['labelmap'] = label_file_path
-            dataset_manifest = IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-
-            self.assertEqual(dataset_manifest.labelmap, ['custom_label0', 'custom_label1', 'custom_label2'])
-
-    def test_od_manifest(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            dataset_dict['root_folder'] = str(tempdir)
-            dataset_dict['type'] = 'object_detection'
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write('0.jpg 0.txt\n1.jpg 1.txt')
-
-            with open(os.path.join(tempdir, '0.txt'), 'w') as f:
-                f.write('0 0 100 0 100\n1 0 100 0 100')
-
-            with open(os.path.join(tempdir, '1.txt'), 'w') as f:
-                f.write('1 50 50 100 100\n3 0 50 100 100')
-
-            # PIL.Image.new('RGB', (100, 100)).save(os.path.join(tempdir, '0.jpg'))
-            # PIL.Image.new('RGB', (100, 100)).save(os.path.join(tempdir, '1.jpg'))
-
-            dataset_manifest = IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-
-            self.assertIsInstance(dataset_manifest, DatasetManifest)
-            self.assertEqual(len(dataset_manifest.images), 2)
-            self.assertEqual(len(dataset_manifest.labelmap), 4)
-            self.assertEqual(dataset_manifest.images[0].labels, [[0, 0.0, 100.0, 0.0, 100.0], [1, 0.0, 100.0, 0.0, 100.0]])
-            self.assertEqual(dataset_manifest.images[1].labels, [[1, 50.0, 50.0, 100.0, 100.0], [3, 0.0, 50.0, 100.0, 100.0]])
-
-    def test_od_empty_labels(self):
-        dataset_dict = copy.deepcopy(self.DATASET_INFO_DICT)
-        with tempfile.TemporaryDirectory() as tempdir:
-            dataset_dict['root_folder'] = str(tempdir)
-            dataset_dict['type'] = 'object_detection'
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write('0.jpg 0.txt\n1.jpg 1.txt')
-
-            with open(os.path.join(tempdir, '0.txt'), 'w'):
-                pass
-
-            with open(os.path.join(tempdir, '1.txt'), 'w') as f:
-                f.write('1 50 50 100 100\n3 0 50 100 100')
-
-            # PIL.Image.new('RGB', (100, 100)).save(os.path.join(tempdir, '0.jpg'))
-            # PIL.Image.new('RGB', (100, 100)).save(os.path.join(tempdir, '1.jpg'))
-
-            dataset_manifest = IrisManifestAdaptor.create_dataset_manifest(DatasetInfo(dataset_dict), Usages.TEST_PURPOSE)
-
-            self.assertIsInstance(dataset_manifest, DatasetManifest)
-            self.assertEqual(len(dataset_manifest.images), 2)
-            self.assertEqual(len(dataset_manifest.labelmap), 4)
-            self.assertEqual(dataset_manifest.images[0].labels, [])
-            self.assertEqual(dataset_manifest.images[1].labels, [[1, 50.0, 50.0, 100.0, 100.0], [3, 0.0, 50.0, 100.0, 100.0]])
-
-
-class TestCreateCocoDatasetManifest(unittest.TestCase):
-    def test_image_classification(self):
-        dataset_manifest = TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 0)
-
-        self.assertIsInstance(dataset_manifest, DatasetManifest)
-        self.assertEqual(len(dataset_manifest.images), 2)
-        self.assertEqual(len(dataset_manifest.labelmap), 2)
-        self.assertEqual(dataset_manifest.images[0].labels, [0])
-        self.assertEqual(dataset_manifest.images[1].labels, [0, 1])
-
-    def test_index_can_start_from_zero(self):
-        manifest_dict = {
-            "images": [{"id": 0, "width": 224.0, "height": 224.0, "file_name": "siberian-kitten.jpg"},
-                       {"id": 1, "width": 224.0, "height": 224.0, "file_name": "kitten 3.jpg"}],
-            "annotations": [
-                {"id": 0, "category_id": 0, "image_id": 0},
-                {"id": 1, "category_id": 0, "image_id": 1},
-                {"id": 2, "category_id": 1, "image_id": 1}
-            ], "categories": [{"id": 0, "name": "cat"}, {"id": 1, "name": "dog"}]
-        }
-
-        dataset_manifest = _coco_dict_to_manifest(manifest_dict, DatasetTypes.IC_MULTILABEL)
-
-        self.assertIsInstance(dataset_manifest, DatasetManifest)
-        self.assertEqual(len(dataset_manifest.images), 2)
-        self.assertEqual(len(dataset_manifest.labelmap), 2)
-        self.assertEqual(dataset_manifest.images[0].labels, [0])
-        self.assertEqual(dataset_manifest.images[1].labels, [0, 1])
-
-    def test_object_detection_bbox_format_LTWH(self):
-        dataset_manifest = TestCases.get_manifest(DatasetTypes.OD, 0)
-
-        self.assertIsInstance(dataset_manifest, DatasetManifest)
-        self.assertEqual(len(dataset_manifest.images), 2)
-        self.assertEqual(len(dataset_manifest.labelmap), 2)
-        self.assertEqual(dataset_manifest.images[0].labels, [[0, 10, 10, 100, 100]])
-        self.assertEqual(dataset_manifest.images[1].labels, [[0, 100, 100, 200, 200], [1, 20, 20, 200, 200]])
-
-    def test_object_detection_bbox_format_LTRB(self):
-        manifest_dict = copy.deepcopy(TestCases.od_manifest_dicts[0])
-        manifest_dict['bbox_format'] = 'ltrb'
-
-        dataset_manifest = _coco_dict_to_manifest(manifest_dict, DatasetTypes.OD)
-        self.assertIsInstance(dataset_manifest, DatasetManifest)
-        self.assertEqual(len(dataset_manifest.images), 2)
-        self.assertEqual(len(dataset_manifest.labelmap), 2)
-        self.assertEqual(dataset_manifest.images[0].labels, [[0, 10, 10, 90, 90]])
-        self.assertEqual(dataset_manifest.images[1].labels, [[0, 100, 100, 100, 100], [1, 20, 20, 180, 180]])
-
-    def test_image_caption_manifest(self):
-        img_0_caption = ['A black Honda motorcycle parked in front of a garage.',
-                         'A Honda motorcycle parked in a grass driveway.',
-                         'A black Honda motorcycle with a dark burgundy seat.',
-                         'Ma motorcycle parked on the gravel in front of a garage.',
-                         'A motorcycle with its brake extended standing outside.']
-        img_1_caption = ['A picture of a modern looking kitchen area.\n',
-                         'A narrow kitchen ending with a chrome refrigerator.',
-                         'A narrow kitchen is decorated in shades of white, gray, and black.',
-                         'a room that has a stove and a icebox in it',
-                         'A long empty, minimal modern skylit home kitchen.']
-
-        dataset_manifest = TestCases.get_manifest(DatasetTypes.IMCAP, 2)
-        self.assertIsInstance(dataset_manifest, DatasetManifest)
-        self.assertEqual(len(dataset_manifest.images), 2)
-        self.assertEqual(dataset_manifest.images[0].labels, img_0_caption)
-        self.assertEqual(dataset_manifest.images[1].labels, img_1_caption)
-
-    def test_multitask_ic_multilabel_and_image_caption(self):
-        classfication_manifest_dict = TestCases.ic_manifest_dicts[0]
-        imcap_manifest_dict = TestCases.cap_manifest_dicts[2]
-        img_0_caption = ['A black Honda motorcycle parked in front of a garage.',
-                         'A Honda motorcycle parked in a grass driveway.',
-                         'A black Honda motorcycle with a dark burgundy seat.',
-                         'Ma motorcycle parked on the gravel in front of a garage.',
-                         'A motorcycle with its brake extended standing outside.']
-        img_1_caption = ['A picture of a modern looking kitchen area.\n',
-                         'A narrow kitchen ending with a chrome refrigerator.',
-                         'A narrow kitchen is decorated in shades of white, gray, and black.',
-                         'a room that has a stove and a icebox in it',
-                         'A long empty, minimal modern skylit home kitchen.']
-
-        task_types = {'task1': DatasetTypes.IC_MULTILABEL, 'task2': DatasetTypes.IMCAP}
-
-        with tempfile.TemporaryDirectory() as tempdir:
-            classification_coco_file_path = pathlib.Path(tempdir) / 'classification_test.json'
-            classification_coco_file_path.write_text(json.dumps(classfication_manifest_dict))
-            imcap_coco_file_path = pathlib.Path(tempdir) / 'imcap_test.json'
-            imcap_coco_file_path.write_text(json.dumps(imcap_manifest_dict))
-
-            coco_file_path = {'task1': str(classification_coco_file_path), 'task2': str(imcap_coco_file_path)}
-            dataset_manifest = CocoManifestAdaptor.create_dataset_manifest(coco_file_path, task_types)
-
-        self.assertIsInstance(dataset_manifest, DatasetManifest)
-        self.assertEqual(len(dataset_manifest.images), 2)
-        self.assertEqual(len(dataset_manifest.labelmap), 2)
-        self.assertEqual(dataset_manifest.images[0].labels, {'task1': [0], 'task2': img_0_caption})
-        self.assertEqual(dataset_manifest.images[1].labels, {'task1': [0, 1], 'task2': img_1_caption})
-
-    def test_image_text_manifest(self):
-        for i in range(len(TestCases.image_text_manifest_dicts)):
-            dataset_manifest = TestCases.get_manifest(DatasetTypes.IMAGE_TEXT_MATCHING, i)
-            self.assertIsInstance(dataset_manifest, DatasetManifest)
-            self.assertEqual(len(dataset_manifest.images), len(TestCases.image_text_manifest_dicts[i]['images']))
-            self.assertEqual(len([label for image in dataset_manifest.images for label in image.labels]), len(TestCases.image_text_manifest_dicts[i]['annotations']))
-            image_ann = {}
-            for ann in TestCases.image_text_manifest_dicts[i]['annotations']:
-                img_id = ann['image_id']
-                image_ann[img_id] = image_ann.get(img_id, [])
-                image_ann[img_id].append((ann['text'], ann['match']))
-            for image in dataset_manifest.images:
-                assert image.labels == image_ann[image.id]
-
-
-class TestManifestFewShotSample(unittest.TestCase):
-    def test_multiclass_sample_10_out_of_30(self):
-        n_classes = 3
-        n_images_per_class = 30
-        n_images_sample = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i]) for i in range(n_classes)] * n_images_per_class
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(n_classes), DatasetTypes.IC_MULTICLASS)
-        few_shot_manifest = dataset_manifest.sample_few_shot_subset(n_images_sample)
-        assert len(few_shot_manifest.images) == n_images_sample * n_classes
-
-        assert _get_instance_count_per_class(few_shot_manifest) == {0: n_images_sample, 1: n_images_sample, 2: n_images_sample}
-
-    def test_multiclass_sample_10_out_of_5(self):
-        n_classes = 3
-        n_images_per_class = 5
-        n_images_sample = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i]) for i in range(n_classes)] * n_images_per_class
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(n_classes), DatasetTypes.IC_MULTICLASS)
-        few_shot_manifest = dataset_manifest.sample_few_shot_subset(n_images_sample)
-        assert len(few_shot_manifest.images) == n_images_per_class * n_classes
-
-        assert _get_instance_count_per_class(few_shot_manifest) == {0: n_images_per_class, 1: n_images_per_class, 2: n_images_per_class}
-
-    def test_multilabel(self):
-        n_classes = 3
-        n_images_per_class = 30
-        n_images_sample_per_class = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i, (i + 1) % n_classes]) for i in range(n_classes)] * n_images_per_class
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(n_classes), DatasetTypes.IC_MULTILABEL)
-        few_shot_manifest = dataset_manifest.sample_few_shot_subset(n_images_sample_per_class)
-        assert len(few_shot_manifest.images) == 17
-        assert _get_instance_count_per_class(few_shot_manifest) == {0: 11, 1: 10, 2: 13}
-
-    def test_multitask(self):
-        n_classes = 3
-        n_images_per_class = 30
-        n_images_sample_per_class = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, {'a': [i, (i + 1) % n_classes], 'b': [(i + 1) % n_classes, (i + 2) % n_classes]}) for i in range(n_classes)] * n_images_per_class
-        dataset_manifest = DatasetManifest(images, {'a': _generate_labelmap(n_classes), 'b': _generate_labelmap(n_classes)},
-                                           {'a': DatasetTypes.IC_MULTICLASS, 'b': DatasetTypes.IC_MULTICLASS})
-        few_shot_manifest = dataset_manifest.sample_few_shot_subset(n_images_sample_per_class)
-        assert len(few_shot_manifest.images) == 17
-        assert _get_instance_count_per_class(few_shot_manifest) == {2: 13, 3: 13, 0: 11, 4: 11, 1: 10, 5: 10}
-
-
-class TestManifestSubsetByRatio(unittest.TestCase):
-    def test_multiclass_sample(self):
-        num_classes = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i]) for i in range(num_classes)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.IC_MULTICLASS)
-
-        sampled = dataset_manifest.sample_subset_by_ratio(0.5)
-        self.assertEqual(len(sampled.images), 500)
-        self.assertEqual(_get_instance_count_per_class(sampled), {i: 50 for i in range(num_classes)})
-
-    def test_multilabel(self):
-        num_classes = 10
-
-        # All negative images
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.IC_MULTILABEL)
-
-        sampled = dataset_manifest.sample_subset_by_ratio(0.5)
-        self.assertEqual(len(sampled.images), 500)
-        self.assertFalse(_get_instance_count_per_class(sampled))
-
-        # 2 tags per image
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i, i + 1]) for i in range(num_classes - 1)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.IC_MULTILABEL)
-
-        sampled = dataset_manifest.sample_subset_by_ratio(0.5)
-        self.assertGreaterEqual(len(sampled.images), 500)
-        for n in _get_instance_count_per_class(sampled).values():
-            self.assertGreaterEqual(n, 50)
-
-    def test_multitask(self):
-        num_classes = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, {'a': [i, i + 1], 'b': [i, i + 1]}) for i in range(num_classes - 1)] * 100
-        dataset_manifest = DatasetManifest(images, {'a': _generate_labelmap(num_classes), 'b': _generate_labelmap(num_classes)}, {'a': DatasetTypes.IC_MULTICLASS, 'b': DatasetTypes.IC_MULTICLASS})
-
-        sampled = dataset_manifest.sample_subset_by_ratio(0.5)
-        self.assertGreaterEqual(len(sampled.images), 500)
-        for n in _get_instance_count_per_class(sampled).values():
-            self.assertGreaterEqual(n, 50)
-
-    def test_detection(self):
-        num_classes = 10
-
-        # 0 box per image
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.OD)
-
-        sampled = dataset_manifest.sample_subset_by_ratio(0.5)
-        self.assertEqual(len(sampled.images), 500)
-        self.assertFalse(_get_instance_count_per_class(sampled))  # All negative images.
-
-        # 1 box per image
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [[i, 0, 0, 5, 5]]) for i in range(num_classes)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.OD)
-
-        sampled = dataset_manifest.sample_subset_by_ratio(0.5)
-        self.assertEqual(len(sampled.images), 500)
-        self.assertEqual(_get_instance_count_per_class(sampled), {i: 50 for i in range(num_classes)})
-
-        # 2 boxes per image.
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [[i, 0, 0, 5, 5], [i + 1, 0, 0, 5, 5]]) for i in range(num_classes - 1)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.OD)
-
-        sampled = dataset_manifest.sample_subset_by_ratio(0.5)
-        self.assertGreaterEqual(len(sampled.images), 500)
-        for n in _get_instance_count_per_class(sampled).values():
-            self.assertGreaterEqual(n, 50)
-
-
-class TestGreedyFewShotsSampling(unittest.TestCase):
-    def test_multiclass_sample(self):
-        num_classes = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i]) for i in range(num_classes)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.IC_MULTICLASS)
-
-        sampled = dataset_manifest.sample_few_shots_subset_greedy(1)
-        self.assertEqual(len(sampled.images), 10)
-        self.assertEqual(_get_instance_count_per_class(sampled), {i: 1 for i in range(num_classes)})
-
-        sampled = dataset_manifest.sample_few_shots_subset_greedy(100)
-        self.assertEqual(len(sampled.images), 1000)
-        self.assertEqual(_get_instance_count_per_class(sampled), {i: 100 for i in range(num_classes)})
-
-    def test_multilabel(self):
-        num_classes = 10
-
-        # All negative images
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.IC_MULTILABEL)
-
-        with self.assertRaises(RuntimeError):
-            dataset_manifest.sample_few_shots_subset_greedy(10)
-
-        # 2 tags per image
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i, i + 1]) for i in range(num_classes - 1)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.IC_MULTILABEL)
-
-        sampled = dataset_manifest.sample_few_shots_subset_greedy(10)
-        self.assertGreaterEqual(len(sampled.images), 50)
-        self.assertLessEqual(len(sampled.images), 100)
-        for n in _get_instance_count_per_class(sampled).values():
-            self.assertGreaterEqual(n, 10)
-
-    def test_multitask(self):
-        num_classes = 10
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, {'a': [i, i + 1], 'b': [i, i + 1]}) for i in range(num_classes - 1)] * 100
-        dataset_manifest = DatasetManifest(images, {'a': _generate_labelmap(num_classes), 'b': _generate_labelmap(num_classes)}, {'a': DatasetTypes.IC_MULTICLASS, 'b': DatasetTypes.IC_MULTICLASS})
-
-        sampled = dataset_manifest.sample_few_shots_subset_greedy(10)
-        self.assertGreaterEqual(len(sampled.images), 50)
-        self.assertLessEqual(len(sampled.images), 100)
-        for n in _get_instance_count_per_class(sampled).values():
-            self.assertGreaterEqual(n, 10)
-
-    def test_detection(self):
-        num_classes = 10
-
-        # 0 box per image
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.OD)
-
-        with self.assertRaises(RuntimeError):
-            dataset_manifest.sample_few_shots_subset_greedy(10)
-
-        # 1 box per image
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [[i, 0, 0, 5, 5]]) for i in range(num_classes)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.OD)
-
-        sampled = dataset_manifest.sample_few_shots_subset_greedy(10)
-        self.assertEqual(len(sampled.images), 100)
-        self.assertEqual(_get_instance_count_per_class(sampled), {i: 10 for i in range(num_classes)})
-
-        # 2 boxes per image.
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [[i, 0, 0, 5, 5], [i + 1, 0, 0, 5, 5]]) for i in range(num_classes - 1)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.OD)
-
-        sampled = dataset_manifest.sample_few_shots_subset_greedy(10)
-        self.assertGreaterEqual(len(sampled.images), 50)
-        self.assertLessEqual(len(sampled.images), 100)
-        for n in _get_instance_count_per_class(sampled).values():
-            self.assertGreaterEqual(n, 10)
-
-    def test_random_seed(self):
-        num_classes = 100
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i]) for i in range(num_classes)] * 100
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(num_classes), DatasetTypes.IC_MULTICLASS)
-
-        for i in range(10):
-            sampled = dataset_manifest.sample_few_shots_subset_greedy(1, random_seed=i)
-            sampled2 = dataset_manifest.sample_few_shots_subset_greedy(1, random_seed=i)
-            self.assertEqual(sampled.images, sampled2.images)
-
-
-class TestManifestSplit(unittest.TestCase):
-    def test_one_image_multiclass(self):
-        n_classes = 1
-        dataset_manifest = DatasetManifest([ImageDataManifest('1', './1.jpg', 10, 10, [0])], _generate_labelmap(n_classes), DatasetTypes.IC_MULTICLASS)
-        train, val = dataset_manifest.train_val_split(1)
-        assert len(train.images) == 1
-        assert len(val.images) == 0
-
-        dataset_manifest = DatasetManifest([ImageDataManifest('1', './1.jpg', 10, 10, [0])], _generate_labelmap(n_classes), DatasetTypes.IC_MULTICLASS)
-        train, val = dataset_manifest.train_val_split(0)
-        assert len(train.images) == 0
-        assert len(val.images) == 1
-
-    def test_even_multiclass(self):
-        n_classes = 3
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i]) for i in range(n_classes)] * 10
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(n_classes), DatasetTypes.IC_MULTICLASS)
-        train, val = dataset_manifest.train_val_split(0.70)
-        assert len(train.images) == 21
-        assert len(val.images) == 9
-
-        assert _get_instance_count_per_class(train) == {0: 7, 1: 7, 2: 7}
-        assert _get_instance_count_per_class(val) == {0: 3, 1: 3, 2: 3}
-
-        # test deepcopy
-        dataset_copy = copy.deepcopy(dataset_manifest)
-        assert dataset_copy
-
-    def test_even_multilabel(self):
-        n_classes = 3
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [i, (i + 1) % n_classes]) for i in range(n_classes)] * 10
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(n_classes), DatasetTypes.IC_MULTILABEL)
-        train, val = dataset_manifest.train_val_split(0.7001)
-        assert len(train.images) == 21
-        assert len(val.images) == 9
-
-        assert _get_instance_count_per_class(train) == {0: 14, 1: 14, 2: 14}
-        assert _get_instance_count_per_class(val) == {0: 6, 1: 6, 2: 6}
-
-        # test deepcopy
-        dataset_copy = copy.deepcopy(dataset_manifest)
-        assert dataset_copy
-
-    def test_even_detection(self):
-        n_classes = 3
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 20, 20, [[i, 0, 0, 10, 10], [(i + 1) % n_classes, 0, 0, 20, 20]]) for i in range(n_classes)] * 10
-        dataset_manifest = DatasetManifest(images, _generate_labelmap(n_classes), DatasetTypes.OD)
-        train, val = dataset_manifest.train_val_split(0.7001)
-        assert len(train.images) == 21
-        assert len(val.images) == 9
-        assert _get_instance_count_per_class(train) == {0: 14, 1: 14, 2: 14}
-        assert _get_instance_count_per_class(val) == {0: 6, 1: 6, 2: 6}
-
-        # test deepcopy
-        dataset_copy = copy.deepcopy(dataset_manifest)
-        assert dataset_copy
-
-    def test_even_multitask(self):
-        n_classes = 3
-        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, {'a': [i, (i + 1) % n_classes], 'b': [(i + 1) % n_classes, (i + 2) % n_classes]}) for i in range(n_classes)] * 10
-        dataset_manifest = DatasetManifest(images, {'a': _generate_labelmap(n_classes), 'b': _generate_labelmap(n_classes)},
-                                           {'a': DatasetTypes.IC_MULTICLASS, 'b': DatasetTypes.IC_MULTICLASS})
-        train, val = dataset_manifest.train_val_split(0.7001, 3)
-        assert len(train.images) == 21
-        assert len(val.images) == 9
-        assert _get_instance_count_per_class(train) == {0: 14, 1: 14, 2: 14, 3: 14, 4: 14, 5: 14}
-        assert _get_instance_count_per_class(val) == {0: 6, 1: 6, 2: 6, 3: 6, 4: 6, 5: 6}
-
-        # test deepcopy
-        dataset_copy = copy.deepcopy(dataset_manifest)
-        assert dataset_copy
-
-
-class TestSampleByCategories(unittest.TestCase):
-    def test_sample_od_dataset_by_categories(self):
-        images = [
-            ImageDataManifest(0, './0.jpg', 10, 10, []),
-            ImageDataManifest(1, './1.jpg', 10, 10, [[0, 1, 1, 2, 2], [1, 2, 2, 3, 3]]),
-            ImageDataManifest(2, './2.jpg', 10, 10, [[1, 1, 1, 2, 2]]),
-            ImageDataManifest(3, './3.jpg', 10, 10, [[1, 0, 0, 2, 2], [2, 1, 1, 2, 2], [3, 2, 2, 3, 3]]),
-        ]
-        manifest = DatasetManifest(images, ['a', 'b', 'c', 'd'], DatasetTypes.OD)
-        new_manifest = manifest.sample_categories([1, 3])
-        assert len(new_manifest) == len(manifest)
-        assert new_manifest.labelmap == ['b', 'd']
-        assert new_manifest.images[0].labels == []
-        assert new_manifest.images[1].labels == [[0, 2, 2, 3, 3]]
-        assert new_manifest.images[2].labels == [[0, 1, 1, 2, 2]]
-        assert new_manifest.images[3].labels == [[0, 0, 0, 2, 2], [1, 2, 2, 3, 3]]
-
-    def test_sample_ic_dataset_by_categories(self):
-        images = [
-            ImageDataManifest(0, './0.jpg', 10, 10, []),
-            ImageDataManifest(1, './1.jpg', 10, 10, [0, 1]),
-            ImageDataManifest(2, './2.jpg', 10, 10, [1]),
-            ImageDataManifest(3, './3.jpg', 10, 10, [1, 2, 3]),
-        ]
-        manifest = DatasetManifest(images, ['a', 'b', 'c', 'd'], DatasetTypes.IC_MULTILABEL)
-        new_manifest = manifest.sample_categories([1, 3])
-        assert len(new_manifest) == len(manifest)
-        assert new_manifest.labelmap == ['b', 'd']
-        assert new_manifest.images[0].labels == []
-        assert new_manifest.images[1].labels == [0]
-        assert new_manifest.images[2].labels == [0]
-        assert new_manifest.images[3].labels == [0, 1]
-
-
-class TestCocoGeneration(unittest.TestCase):
-    def test_coco_generation(self):
-        for data_type in [DatasetTypes.IC_MULTICLASS, DatasetTypes.IC_MULTILABEL, DatasetTypes.OD, DatasetTypes.IMCAP]:
-            for i in range(len(TestCases.manifest_dict_by_data_type[data_type])):
-                manifest = TestCases.get_manifest(data_type, i)
-                coco_dict = manifest.generate_coco_annotations()
-
-                assert coco_dict == TestCases.manifest_dict_by_data_type[data_type][i], f'fails with {data_type} {i}'
-
-
-class TestDatasetManifestMerge(unittest.TestCase):
-    def test_merge_two_ic_datasets_diff_labelmap(self):
-        merged_manifest = DatasetManifest.merge(TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 0),
-                                                TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 1),
-                                                flavor=1)
-        assert merged_manifest.labelmap == ['cat', 'dog', 'tiger', 'rabbit']
-        assert merged_manifest.images[0].labels == [0]
-        assert merged_manifest.images[1].labels == [0, 1]
-        assert merged_manifest.images[2].labels == [2]
-        assert merged_manifest.images[3].labels == [2, 3]
-
-    def test_merge_two_ic_datasets_same_labelmap(self):
-        merged_manifest = DatasetManifest.merge(TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 0),
-                                                TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 2),
-                                                flavor=0)
-        assert merged_manifest.labelmap == ['cat', 'dog']
-        assert merged_manifest.images[0].labels == [0]
-        assert merged_manifest.images[1].labels == [0, 1]
-        assert merged_manifest.images[2].labels == [0]
-        assert merged_manifest.images[3].labels == [1]
-
-    def test_merge_three_ic_datasets_diff_labelmap(self):
-        md3 = copy.deepcopy(TestCases.ic_manifest_dicts[2])
-        md3['categories'] = [{"id": 1, "name": "human"}, {"id": 2, "name": "snake"}]
-        merged_manifest = DatasetManifest.merge(TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-                                                TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 1),
-                                                _coco_dict_to_manifest(md3, DatasetTypes.IC_MULTICLASS),
-                                                flavor=1)
-        assert merged_manifest.labelmap == ['cat', 'dog', 'tiger', 'rabbit', 'human', 'snake']
-        assert merged_manifest.images[0].labels == [0]
-        assert merged_manifest.images[1].labels == [0, 1]
-        assert merged_manifest.images[2].labels == [2]
-        assert merged_manifest.images[3].labels == [2, 3]
-        assert merged_manifest.images[4].labels == [4]
-        assert merged_manifest.images[5].labels == [5]
-
-    def test_merge_two_od_datasets_diff_labelmap(self):
-        merged_manifest = DatasetManifest.merge(TestCases.get_manifest(DatasetTypes.OD, 0), TestCases.get_manifest(DatasetTypes.OD, 1), flavor=1)
-        assert merged_manifest.labelmap == ['cat', 'dog', 'tiger', 'rabbit']
-        assert merged_manifest.images[0].labels == [[0, 10, 10, 100, 100]]
-        assert merged_manifest.images[1].labels == [[0, 100, 100, 200, 200], [1, 20, 20, 200, 200]]
-        assert merged_manifest.images[2].labels == [[2, 10, 10, 90, 90]]
-        assert merged_manifest.images[3].labels == [[2, 90, 90, 180, 180], [3, 20, 20, 200, 200]]
-
-    def test_merge_two_od_datasets_same_labelmap(self):
-        merged_manifest = DatasetManifest.merge(TestCases.get_manifest(DatasetTypes.OD, 0), TestCases.get_manifest(DatasetTypes.OD, 2), flavor=0)
-        assert merged_manifest.labelmap == ['cat', 'dog']
-        assert merged_manifest.images[0].labels == [[0, 10, 10, 100, 100]]
-        assert merged_manifest.images[1].labels == [[0, 100, 100, 200, 200], [1, 20, 20, 200, 200]]
-        assert merged_manifest.images[2].labels == [[0, 10, 10, 90, 90]]
-        assert merged_manifest.images[3].labels == [[1, 90, 90, 180, 180]]
-
-    def test_merge_two_caption_datasets(self):
-        merged_manifest = DatasetManifest.merge(TestCases.get_manifest(DatasetTypes.IMCAP, 0), TestCases.get_manifest(DatasetTypes.IMCAP, 1), flavor=0)
-
-        assert merged_manifest.labelmap is None
-        assert len(merged_manifest) == 4
-        assert merged_manifest.images[0].labels == ['test 1.']
-        assert merged_manifest.images[1].labels == ['test 2.']
-        assert merged_manifest.images[2].labels == ['test 3.']
-        assert merged_manifest.images[3].labels == ['test 4.']
-
-    def test_merge_multitask_datasets_flavor0_with_same_tasks(self):
-        multitask_manifest_1 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-            'task2': TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 1)
-        })
-
-        multitask_manifest_2 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-            'task2': TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 1),
-        })
-
-        merged_manifest = DatasetManifest.merge(multitask_manifest_1, multitask_manifest_2, flavor=0)
-        assert len(merged_manifest) == 8
-        assert merged_manifest.data_type == {
-            'task1': DatasetTypes.IC_MULTICLASS,
-            'task2': DatasetTypes.IC_MULTILABEL,
-        }
-
-    def test_merge_multitask_datasets_flavor0_with_same_tasks_different_types(self):
-        multitask_manifest_1 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 0),
-            'task2': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 1)
-        })
-
-        multitask_manifest_2 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-            'task2': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 1),
-        })
-
-        self.assertRaises(ValueError, lambda: DatasetManifest.merge(multitask_manifest_1, multitask_manifest_2, flavor=0))
-
-    def test_merge_multitask_datasets_flavor0_with_different_tasks_should_raise(self):
-        multitask_manifest_1 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-            'task3': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 1)
-        })
-
-        multitask_manifest_2 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-            'task2': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 1),
-        })
-
-        self.assertRaises(ValueError, lambda: DatasetManifest.merge(multitask_manifest_1, multitask_manifest_2, flavor=0))
-
-    def test_merge_multitask_datasets_flavor1_with_different_tasks(self):
-        multitask_manifest_1 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-            'task2': TestCases.get_manifest(DatasetTypes.IC_MULTILABEL, 1),
-            'task3': TestCases.get_manifest(DatasetTypes.OD, 2)
-        })
-
-        multitask_manifest_2 = DatasetManifest.create_multitask_manifest({
-            'task4': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 2),
-            'task5': TestCases.get_manifest(DatasetTypes.OD, 0),
-            'task6': TestCases.get_manifest(DatasetTypes.OD, 1)
-        })
-
-        merged_manifest = DatasetManifest.merge(multitask_manifest_1, multitask_manifest_2, flavor=1)
-        assert merged_manifest.labelmap == {
-            'task1': ['cat', 'dog'],
-            'task2': ['tiger', 'rabbit'],
-            'task3': ['cat', 'dog'],
-            'task4': ['cat', 'dog'],
-            'task5': ['cat', 'dog'],
-            'task6': ['tiger', 'rabbit'],
-        }
-
-        assert merged_manifest.data_type == {
-            'task1': DatasetTypes.IC_MULTICLASS,
-            'task2': DatasetTypes.IC_MULTILABEL,
-            'task3': DatasetTypes.OD,
-            'task4': DatasetTypes.IC_MULTICLASS,
-            'task5': DatasetTypes.OD,
-            'task6': DatasetTypes.OD,
-        }
-
-        assert len(merged_manifest.images) == 12
-
-    def test_merge_multitask_datasets_flavor1_with_redundant_task_name_should_raise(self):
-        multitask_manifest_1 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 0),
-            'task3': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 1)
-        })
-
-        multitask_manifest_2 = DatasetManifest.create_multitask_manifest({
-            'task1': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 2),
-            'task2': TestCases.get_manifest(DatasetTypes.IC_MULTICLASS, 1),
-        })
-
-        self.assertRaises(ValueError, lambda: DatasetManifest.merge(multitask_manifest_1, multitask_manifest_2, flavor=1))
-
-
-if __name__ == '__main__':
-    unittest.main()
+import copy
+import json
+import pathlib
+import tempfile
+import unittest
+from collections import Counter
+
+from vision_datasets.common import CategoryManifest, CocoDictGeneratorFactory, CocoManifestAdaptorFactory, DatasetFilter, DatasetManifest, DatasetTypes, ImageDataManifest, ImageNoAnnotationFilter, \
+    ManifestMerger, ManifestMergeStrategyFactory, ManifestSampler, RemoveCategories, RemoveCategoriesConfig, SampleByFewShotConfig, SampleByNumSamplesConfig, \
+    SampleStrategyFactory, SampleStrategyType, SpawnConfig, SpawnFactory, SplitConfig, SplitFactory
+from vision_datasets.common.data_manifest.utils import generate_multitask_dataset_manifest
+from vision_datasets.image_classification.manifest import ImageClassificationLabelManifest
+from vision_datasets.image_object_detection.manifest import ImageObjectDetectionLabelManifest
+
+
+def _generate_categories(n_classes):
+    return [CategoryManifest(i, str(i)) for i in range(n_classes)]
+
+
+def _get_instance_count_per_class(manifest: DatasetManifest):
+    assert not manifest.is_multitask
+    return Counter([label.category_id for image in manifest.images for label in image.labels])
+
+
+def _coco_dict_to_manifest(coco_dict, data_type):
+    with tempfile.TemporaryDirectory() as temp_dir:
+        dm1_path = pathlib.Path(temp_dir) / 'coco.json'
+        dm1_path.write_text(json.dumps(coco_dict))
+        return CocoManifestAdaptorFactory.create(data_type).create_dataset_manifest(str(dm1_path))
+
+
+class TestCases:
+    ic_multiclass_manifest_dicts = [
+        {
+            "images": [
+                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "train/1.jpg"},
+                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "train/3.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1},
+                {"id": 2, "category_id": 2, "image_id": 2}
+            ],
+            "categories": [
+                {"id": 1, "name": "cat"},
+                {"id": 2, "name": "dog"}
+            ]
+        },
+        {
+            "images": [
+                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "test/1.jpg"},
+                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "test/2.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1},
+                {"id": 2, "category_id": 2, "image_id": 2}
+            ],
+            "categories": [
+                {"id": 1, "name": "tiger"},
+                {"id": 2, "name": "rabbit"}
+            ]
+        },
+        {
+            "images": [
+                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "test/1.jpg"},
+                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "test/2.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1},
+                {"id": 2, "category_id": 2, "image_id": 2}
+            ],
+            "categories": [
+                {"id": 1, "name": "cat"},
+                {"id": 2, "name": "dog"}
+            ]
+        }]
+
+    ic_multilabel_manifest_dicts = [
+        {
+            "images": [
+                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "train/1.jpg"},
+                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "train/3.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1},
+                {"id": 2, "category_id": 1, "image_id": 2},
+                {"id": 3, "category_id": 2, "image_id": 2}
+            ],
+            "categories": [
+                {"id": 1, "name": "cat"},
+                {"id": 2, "name": "dog"}
+            ]
+        },
+        {
+            "images": [
+                {"id": 1, "width": 224.0, "height": 224.0, "file_name": "test/1.jpg"},
+                {"id": 2, "width": 224.0, "height": 224.0, "file_name": "test/2.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1},
+                {"id": 2, "category_id": 1, "image_id": 2},
+                {"id": 3, "category_id": 2, "image_id": 2}
+            ],
+            "categories": [
+                {"id": 1, "name": "tiger"},
+                {"id": 2, "name": "rabbit"}
+            ]
+        }]
+
+    od_manifest_dicts = [
+        {
+            "images": [{"id": 1, "width": 224.0, "height": 224.0, "file_name": "siberian-kitten.jpg"},
+                       {"id": 2, "width": 224.0, "height": 224.0, "file_name": "kitten 3.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1, "bbox": [10, 10, 90, 90]},
+                {"id": 2, "category_id": 1, "image_id": 2, "bbox": [100, 100, 100, 100]},
+                {"id": 3, "category_id": 2, "image_id": 2, "bbox": [20, 20, 180, 180]}
+            ],
+            "categories": [
+                {"id": 1, "name": "cat"}, {"id": 2, "name": "dog"}
+            ]
+        },
+        {
+            "images": [{"id": 1, "width": 224.0, "height": 224.0, "file_name": "siberian-kitten.jpg"},
+                       {"id": 2, "width": 224.0, "height": 224.0, "file_name": "kitten 3.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1, "bbox": [10, 10, 80, 80]},
+                {"id": 2, "category_id": 1, "image_id": 2, "bbox": [90, 90, 90, 90]},
+                {"id": 3, "category_id": 2, "image_id": 2, "bbox": [20, 20, 180, 180]}
+            ],
+            "categories": [
+                {"id": 1, "name": "tiger"}, {"id": 2, "name": "rabbit"}
+            ]
+        },
+        {
+            "images": [{"id": 1, "width": 224.0, "height": 224.0, "file_name": "siberian-kitten.jpg"},
+                       {"id": 2, "width": 224.0, "height": 224.0, "file_name": "kitten 3.jpg"}],
+            "annotations": [
+                {"id": 1, "category_id": 1, "image_id": 1, "bbox": [10, 10, 80, 80]},
+                {"id": 2, "category_id": 2, "image_id": 2, "bbox": [90, 90, 90, 90]},
+            ],
+            "categories": [
+                {"id": 1, "name": "cat"}, {"id": 2, "name": "dog"}
+            ]
+        }]
+
+    cap_manifest_dicts = [
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@1.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@2.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "caption": "test 1."},
+                {"id": 2, "image_id": 2, "caption": "test 2."},
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@3.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@4.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "caption": "test 3."},
+                {"id": 2, "image_id": 2, "caption": "test 4."},
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@honda.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@kitchen.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "caption": "A black Honda motorcycle parked in front of a garage."},
+                {"id": 2, "image_id": 1, "caption": "A Honda motorcycle parked in a grass driveway."},
+                {"id": 3, "image_id": 1, "caption": "A black Honda motorcycle with a dark burgundy seat."},
+                {"id": 4, "image_id": 1, "caption": "Ma motorcycle parked on the gravel in front of a garage."},
+                {"id": 5, "image_id": 1, "caption": "A motorcycle with its brake extended standing outside."},
+                {"id": 6, "image_id": 2, "caption": "A picture of a modern looking kitchen area.\n"},
+                {"id": 7, "image_id": 2, "caption": "A narrow kitchen ending with a chrome refrigerator."},
+                {"id": 8, "image_id": 2, "caption": "A narrow kitchen is decorated in shades of white, gray, and black."},
+                {"id": 9, "image_id": 2, "caption": "a room that has a stove and a icebox in it"},
+                {"id": 10, "image_id": 2, "caption": "A long empty, minimal modern skylit home kitchen."}
+            ],
+        }]
+
+    image_text_manifest_dicts = [
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@1.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@2.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "text": "test 1.", "match": 0},
+                {"id": 2, "image_id": 2, "text": "test 2.", "match": 0},
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@3.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@4.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "text": "test 3.", "match": 0},
+                {"id": 2, "image_id": 2, "text": "test 4.", "match": 1},
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@honda.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@kitchen.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "text": "A black Honda motorcycle parked in front of a garage.", 'match': 0},
+                {"id": 2, "image_id": 1, "text": "A Honda motorcycle parked in a grass driveway.", 'match': 1},
+                {"id": 3, "image_id": 1, "text": "A black Honda motorcycle with a dark burgundy seat.", 'match': 1},
+                {"id": 4, "image_id": 1, "text": "Ma motorcycle parked on the gravel in front of a garage.", 'match': 0},
+                {"id": 5, "image_id": 1, "text": "A motorcycle with its brake extended standing outside.", 'match': 0},
+                {"id": 6, "image_id": 2, "text": "A picture of a modern looking kitchen area.\n", 'match': 1},
+                {"id": 7, "image_id": 2, "text": "A narrow kitchen ending with a chrome refrigerator.", 'match': 0},
+                {"id": 8, "image_id": 2, "text": "A narrow kitchen is decorated in shades of white, gray, and black.", 'match': 0},
+                {"id": 9, "image_id": 2, "text": "a room that has a stove and a icebox in it", 'match': 0},
+                {"id": 10, "image_id": 2, "text": "A long empty, minimal modern skylit home kitchen.", 'match': 1}
+            ],
+        }]
+
+    image_matting_manifest_dicts = [
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@image/test_1.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "label": f"{str(pathlib.Path(__file__).resolve().parent)}/image_matting_test_data.zip@mask/test_1.png"}
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@image/test_1.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@image/test_2.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "label": f"{str(pathlib.Path(__file__).resolve().parent)}/image_matting_test_data.zip@mask/test_1.png"},
+                {"id": 2, "image_id": 2, "label": f"{str(pathlib.Path(__file__).resolve().parent)}/image_matting_test_data.zip@mask/test_2.png"},
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@image/test_1.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@image/test_2.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "label": f"{str(pathlib.Path(__file__).resolve().parent)}/image_matting_test_data.zip@mask/test_1.png"},
+                {"id": 2, "image_id": 2, "label": f"{str(pathlib.Path(__file__).resolve().parent)}/image_matting_test_data.zip@mask/test_2.png"},
+            ]
+        }]
+
+    image_regression_manifest_dicts = [
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@1.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@2.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "target": 1.0},
+                {"id": 2, "image_id": 2, "target": 2.0},
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@3.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@4.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "target": 3.0},
+                {"id": 2, "image_id": 2, "target": 4.0},
+            ]
+        },
+        {
+            "images": [{"id": 1, "file_name": "train_images.zip@3.jpg"},
+                       {"id": 2, "file_name": "train_images.zip@4.jpg"}],
+            "annotations": [
+                {"id": 1, "image_id": 1, "target": 5.0},
+                {"id": 2, "image_id": 2, "target": 6.0},
+            ],
+        }]
+
+    image_retrieval_dicts = [
+        {
+            "images": [
+                {"id": 1, "file_name": "test1.zip@test/0/image_1.jpg"}, {"id": 2, "file_name": "test2.zip@test/1/image_2.jpg"}
+            ],
+            "annotations": [
+                {"image_id": 1, "id": 1, "query": "men giving a speech"},
+                {"image_id": 2, "id": 2, "query": "men not giving a speech"}
+            ]
+        },
+        {
+            "images": [
+                {"id": 1, "file_name": "test1.zip@test/0/image_1.jpg"}, {"id": 2, "file_name": "test2.zip@test/1/image_2.jpg"}
+            ],
+            "annotations": [
+                {"image_id": 1, "id": 1, "query": "women giving a speech"},
+                {"image_id": 2, "id": 2, "query": "women not giving a speech"}
+            ]
+        }
+    ]
+
+    manifest_dict_by_data_type = {
+        DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL: ic_multilabel_manifest_dicts,
+        DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS: ic_multiclass_manifest_dicts,
+        DatasetTypes.IMAGE_OBJECT_DETECTION: od_manifest_dicts,
+        DatasetTypes.IMAGE_CAPTION: cap_manifest_dicts,
+        DatasetTypes.IMAGE_TEXT_MATCHING: image_text_manifest_dicts,
+        DatasetTypes.IMAGE_MATTING: image_matting_manifest_dicts,
+        DatasetTypes.IMAGE_REGRESSION: image_regression_manifest_dicts,
+        DatasetTypes.TEXT_2_IMAGE_RETRIEVAL: image_retrieval_dicts
+    }
+
+    @staticmethod
+    def get_manifest(data_type, index):
+        return _coco_dict_to_manifest(TestCases.manifest_dict_by_data_type[data_type][index], data_type)
+
+
+class TestManifestRemoveImagesWithNoLabel(unittest.TestCase):
+    def test_detection(self):
+        num_classes = 10
+        filter = DatasetFilter(ImageNoAnnotationFilter())
+        # 0 box per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+
+        sampled = filter.run(manifest)
+        self.assertEqual(len(sampled.images), 0)
+        self.assertFalse(_get_instance_count_per_class(sampled))  # All negative images.
+
+        # 1 box per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageObjectDetectionLabelManifest([i, 0, 0, 5, 5])])
+                  for i in range(num_classes)] * 100 + [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(100)]
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+
+        sampled = filter.run(manifest)
+        self.assertEqual(len(sampled.images), 1000)
+
+
+class TestSampleManifestByNumSamples(unittest.TestCase):
+    def test_multiclass_sample(self):
+        num_classes = 10
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageClassificationLabelManifest(i)]) for i in range(num_classes)] * 100
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS)
+
+        strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SampleStrategyType.NumSamples, SampleByNumSamplesConfig(0, False, 500))
+        sampler = ManifestSampler(strategy)
+        sampled = sampler.run(manifest)
+        self.assertEqual(len(sampled.images), 500)
+
+    def test_multilabel(self):
+        num_classes = 10
+
+        # All negative images
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+
+        strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SampleStrategyType.NumSamples, SampleByNumSamplesConfig(0, False, 500))
+        sampler = ManifestSampler(strategy)
+        sampled = sampler.run(manifest)
+        self.assertEqual(len(sampled.images), 500)
+        self.assertFalse(_get_instance_count_per_class(sampled))
+
+        # 2 tags per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageClassificationLabelManifest(i), ImageClassificationLabelManifest(i + 1)]) for i in range(num_classes - 1)] * 100
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+
+        sampled = sampler.run(manifest)
+        self.assertGreaterEqual(len(sampled.images), 500)
+        for n in _get_instance_count_per_class(sampled).values():
+            self.assertGreaterEqual(n, 50)
+
+    # def test_multitask(self):
+    #     num_classes = 10
+    #     images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, {'a': [i, i + 1], 'b': [i, i + 1]}) for i in range(num_classes - 1)] * 100
+    #     manifest = DatasetManifest(images, {'a': _generate_categories(num_classes), 'b': _generate_categories(num_classes)}, {
+    #         'a': DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 'b': DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS})
+    #     strategy = SampleStrategyFactory.create(DatasetTypes.MULTITASK, SampleStrategyType.NumSamples, SampleByNumSamplesConfig(0, False, 500))
+    #     sampler = ManifestSampler(strategy)
+    #     sampled = sampler.run(manifest)
+    #     self.assertGreaterEqual(len(sampled.images), 500)
+    #     for n in _get_instance_count_per_class(sampled).values():
+    #         self.assertGreaterEqual(n, 50)
+
+    def test_detection(self):
+        num_classes = 10
+
+        # 0 box per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+        strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_OBJECT_DETECTION, SampleStrategyType.NumSamples, SampleByNumSamplesConfig(0, False, 500))
+        sampler = ManifestSampler(strategy)
+        sampled = sampler.run(manifest)
+        self.assertEqual(len(sampled.images), 500)
+        self.assertFalse(_get_instance_count_per_class(sampled))  # All negative images.
+
+        # 1 box per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageObjectDetectionLabelManifest([i, 0, 0, 5, 5])]) for i in range(num_classes)] * 100
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+
+        sampled = sampler.run(manifest)
+        self.assertEqual(len(sampled.images), 500)
+
+        # 2 boxes per image.
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageObjectDetectionLabelManifest([i, 0, 0, 5, 5]),
+                                    ImageObjectDetectionLabelManifest([i + 1, 0, 0, 5, 5])]) for i in range(num_classes - 1)] * 100
+        manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+
+        sampled = sampler.run(manifest)
+        self.assertGreaterEqual(len(sampled.images), 500)
+        for n in _get_instance_count_per_class(sampled).values():
+            self.assertGreaterEqual(n, 50)
+
+
+class TestGreedyFewShotsSampling(unittest.TestCase):
+    def test_multiclass_sample(self):
+        num_classes = 10
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageClassificationLabelManifest(i)]) for i in range(num_classes)] * 100
+        dataset_manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS)
+
+        strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SampleStrategyType.FewShot, SampleByFewShotConfig(0, 1))
+        sampler = ManifestSampler(strategy)
+        sampled = sampler.run(dataset_manifest)
+        self.assertEqual(len(sampled.images), 10)
+        self.assertEqual(_get_instance_count_per_class(sampled), {i: 1 for i in range(num_classes)})
+
+        strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SampleStrategyType.FewShot, SampleByFewShotConfig(0, 100))
+        sampler = ManifestSampler(strategy)
+        sampled = sampler.run(dataset_manifest)
+        self.assertEqual(len(sampled.images), 1000)
+        self.assertEqual(_get_instance_count_per_class(sampled), {i: 100 for i in range(num_classes)})
+
+    def test_multilabel(self):
+        num_classes = 10
+
+        # All negative images
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
+        dataset_manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+
+        with self.assertRaises(RuntimeError):
+            strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SampleStrategyType.FewShot, SampleByFewShotConfig(0, 10))
+            sampler = ManifestSampler(strategy)
+            sampled = sampler.run(dataset_manifest)
+
+        # 2 tags per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageClassificationLabelManifest(i), ImageClassificationLabelManifest(i + 1)]) for i in range(num_classes - 1)] * 100
+        dataset_manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+
+        sampled = sampler.run(dataset_manifest)
+        self.assertGreaterEqual(len(sampled), 50)
+        self.assertLessEqual(len(sampled), 100)
+        for n in _get_instance_count_per_class(sampled).values():
+            self.assertGreaterEqual(n, 10)
+
+    # def test_multitask(self):
+    #     num_classes = 10
+    #     images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, {
+    #         'a': [ImageClassificationLabelManifest(i), ImageClassificationLabelManifest(i + 1)],
+    #         'b': [ImageClassificationLabelManifest(i), ImageClassificationLabelManifest(i + 1)]
+    #     }) for i in range(num_classes - 1)] * 100
+    #     dataset_manifest = DatasetManifest(images,
+    #                                        {'a': _generate_categories(num_classes), 'b': _generate_categories(num_classes)},
+    #                                        {'a': DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 'b': DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS})
+
+    #     strategy = SampleStrategyFactory.create(DatasetTypes.MULTITASK, SampleStrategyType.FewShot, SampleByFewShotConfig(0, 10))
+    #     sampler = ManifestSampler(strategy)
+    #     sampled = sampler.run(dataset_manifest)
+    #     self.assertGreaterEqual(len(sampled), 50)
+    #     self.assertLessEqual(len(sampled), 100)
+    #     for n in _get_instance_count_per_class(sampled).values():
+    #         self.assertGreaterEqual(n, 10)
+
+    def test_detection(self):
+        num_classes = 10
+
+        # 0 box per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, []) for i in range(1000)]
+        dataset_manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+
+        with self.assertRaises(RuntimeError):
+            strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_OBJECT_DETECTION, SampleStrategyType.FewShot, SampleByFewShotConfig(0, 10))
+            sampler = ManifestSampler(strategy)
+            sampled = sampler.run(dataset_manifest)
+
+        # 1 box per image
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageObjectDetectionLabelManifest([i, 0, 0, 5, 5])]) for i in range(num_classes)] * 100
+        dataset_manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+
+        sampled = sampler.run(dataset_manifest)
+        self.assertEqual(len(sampled.images), 100)
+        self.assertEqual(_get_instance_count_per_class(sampled), {i: 10 for i in range(num_classes)})
+
+        # 2 boxes per image.
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageObjectDetectionLabelManifest([i, 0, 0, 5, 5]),
+                                    ImageObjectDetectionLabelManifest([i + 1, 0, 0, 5, 5])]) for i in range(num_classes - 1)] * 100
+        dataset_manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+
+        sampled = sampler.run(dataset_manifest)
+        self.assertGreaterEqual(len(sampled.images), 50)
+        self.assertLessEqual(len(sampled.images), 100)
+        for n in _get_instance_count_per_class(sampled).values():
+            self.assertGreaterEqual(n, 10)
+
+    def test_consistency_random_seed(self):
+        num_classes = 100
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageClassificationLabelManifest(i)]) for i in range(num_classes)] * 100
+        dataset_manifest = DatasetManifest(images, _generate_categories(num_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS)
+
+        for i in range(10):
+            n_sample_per_class = 1
+            strategy = SampleStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SampleStrategyType.FewShot, SampleByFewShotConfig(i, n_sample_per_class))
+            sampler = ManifestSampler(strategy)
+            sampled = sampler.run(dataset_manifest)
+            sampled2 = sampler.run(dataset_manifest)
+            self.assertEqual(len(sampled), 100)
+            self.assertEqual(len(sampled), len(sampled2))
+            self.assertEqual([x.id for x in sampled.images], [x.id for x in sampled2.images])
+
+
+class TestManifestSplit(unittest.TestCase):
+    def test_one_image_multiclass(self):
+        n_classes = 1
+        dataset_manifest = DatasetManifest([ImageDataManifest('1', './1.jpg', 10, 10, [ImageClassificationLabelManifest(0)])],
+                                           _generate_categories(n_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS)
+        splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SplitConfig(1))
+        first, second = splitter.run(dataset_manifest)
+        assert len(first.images) == 1
+        assert len(second.images) == 0
+
+        splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SplitConfig(0))
+        first, second = splitter.run(dataset_manifest)
+        assert len(first.images) == 0
+        assert len(second.images) == 1
+
+    def test_even_multiclass(self):
+        n_classes = 3
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageClassificationLabelManifest(i)]) for i in range(n_classes)] * 10
+        dataset_manifest = DatasetManifest(images, _generate_categories(n_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS)
+        splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SplitConfig(0.7))
+        first, second = splitter.run(dataset_manifest)
+        assert len(first.images) == 21
+        assert len(second.images) == 9
+
+        assert _get_instance_count_per_class(first) == {0: 7, 1: 7, 2: 7}
+        assert _get_instance_count_per_class(second) == {0: 3, 1: 3, 2: 3}
+
+        # test deepcopy
+        dataset_copy = copy.deepcopy(dataset_manifest)
+        assert dataset_copy
+
+    def test_even_multilabel(self):
+        n_classes = 3
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 10, 10, [ImageClassificationLabelManifest(i), ImageClassificationLabelManifest((i + 1) % n_classes)]) for i in range(n_classes)] * 10
+        dataset_manifest = DatasetManifest(images, _generate_categories(n_classes), DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+        splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, SplitConfig(0.7001))
+        first, second = splitter.run(dataset_manifest)
+        assert len(first.images) == 21
+        assert len(second.images) == 9
+
+        assert _get_instance_count_per_class(first) == {0: 14, 1: 14, 2: 14}
+        assert _get_instance_count_per_class(second) == {0: 6, 1: 6, 2: 6}
+
+        # test deepcopy
+        dataset_copy = copy.deepcopy(dataset_manifest)
+        assert dataset_copy
+
+    def test_even_detection(self):
+        n_classes = 3
+        images = [ImageDataManifest(f'{i}', f'./{i}.jpg', 20, 20, [ImageObjectDetectionLabelManifest([i, 0, 0, 10, 10]),
+                                    ImageObjectDetectionLabelManifest([(i + 1) % n_classes, 0, 0, 20, 20])]) for i in range(n_classes)] * 10
+        dataset_manifest = DatasetManifest(images, _generate_categories(n_classes), DatasetTypes.IMAGE_OBJECT_DETECTION)
+        splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, SplitConfig(0.7001))
+        first, second = splitter.run(dataset_manifest)
+        assert len(first.images) == 21
+        assert len(second.images) == 9
+        assert _get_instance_count_per_class(first) == {0: 14, 1: 14, 2: 14}
+        assert _get_instance_count_per_class(second) == {0: 6, 1: 6, 2: 6}
+
+        # test deepcopy
+        dataset_copy = copy.deepcopy(dataset_manifest)
+        assert dataset_copy
+
+    # def test_even_multitask(self):
+    #     n_classes = 3
+    #     images = [ImageDataManifest(
+    #         str(i),
+    #         f'./{i}.jpg',
+    #         10,
+    #         10,
+    #         {'a': [ImageClassificationLabelManifest(i), ImageClassificationLabelManifest((i + 1) % n_classes)],
+    #             'b': [ImageClassificationLabelManifest((i + 1) % n_classes), ImageClassificationLabelManifest((i + 2) % n_classes)]}) for i in range(n_classes)] * 10
+
+    #     dataset_manifest = DatasetManifest(images, {'a': _generate_categories(n_classes), 'b': _generate_categories(n_classes)},
+    #                                        {'a': DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 'b': DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS})
+    #     splitter = SplitFactory.create(DatasetTypes.MULTITASK, SplitConfig(0.7001))
+    #     first, second = splitter.run(dataset_manifest)
+    #     assert len(first.images) == 21
+    #     assert len(second.images) == 9
+    #     assert _get_instance_count_per_class(first) == {0: 14, 1: 14, 2: 14, 3: 14, 4: 14, 5: 14}
+    #     assert _get_instance_count_per_class(second) == {0: 6, 1: 6, 2: 6, 3: 6, 4: 6, 5: 6}
+
+    #     # test deepcopy
+    #     dataset_copy = copy.deepcopy(dataset_manifest)
+    #     assert dataset_copy
+
+
+class TestSampleByCategories(unittest.TestCase):
+
+    def test_sample_od_dataset_by_categories(self):
+        images = [
+            ImageDataManifest(0, './0.jpg', 10, 10, []),
+            ImageDataManifest(1, './1.jpg', 10, 10, [ImageObjectDetectionLabelManifest([0, 1, 1, 2, 2]), ImageObjectDetectionLabelManifest([1, 2, 2, 3, 3])]),
+            ImageDataManifest(2, './2.jpg', 10, 10, [ImageObjectDetectionLabelManifest([1, 1, 1, 2, 2])]),
+            ImageDataManifest(3, './3.jpg', 10, 10, [ImageObjectDetectionLabelManifest([1, 0, 0, 2, 2]),
+                              ImageObjectDetectionLabelManifest([2, 1, 1, 2, 2]), ImageObjectDetectionLabelManifest([3, 2, 2, 3, 3])]),
+        ]
+        manifest = DatasetManifest(images, [CategoryManifest(i, x) for i, x in enumerate(['a', 'b', 'c', 'd'])], DatasetTypes.IMAGE_OBJECT_DETECTION)
+        remover = RemoveCategories(RemoveCategoriesConfig(['a', 'c']))
+        new_manifest = remover.run(manifest)
+        assert len(new_manifest) == len(manifest)
+        assert [x.name for x in new_manifest.categories] == ['b', 'd']
+        assert new_manifest.images[0].labels == []
+        assert [x.label_data for x in new_manifest.images[1].labels] == [[0, 2, 2, 3, 3]]
+        assert [x.label_data for x in new_manifest.images[2].labels] == [[0, 1, 1, 2, 2]]
+        assert [x.label_data for x in new_manifest.images[3].labels] == [[0, 0, 0, 2, 2], [1, 2, 2, 3, 3]]
+
+    def test_sample_ic_dataset_by_categories(self):
+        images = [
+            ImageDataManifest(0, './0.jpg', 10, 10, []),
+            ImageDataManifest(1, './1.jpg', 10, 10, [ImageClassificationLabelManifest(0), ImageClassificationLabelManifest(1)]),
+            ImageDataManifest(2, './2.jpg', 10, 10, [ImageClassificationLabelManifest(1)]),
+            ImageDataManifest(3, './3.jpg', 10, 10, [ImageClassificationLabelManifest(1), ImageClassificationLabelManifest(2), ImageClassificationLabelManifest(3)]),
+        ]
+        manifest = DatasetManifest(images, [CategoryManifest(i, x) for i, x in enumerate(['a', 'b', 'c', 'd'])], DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+        remover = RemoveCategories(RemoveCategoriesConfig(['a', 'c']))
+        new_manifest = remover.run(manifest)
+        assert len(new_manifest) == len(manifest)
+        assert [x.name for x in new_manifest.categories] == ['b', 'd']
+        assert new_manifest.images[0].labels == []
+        assert [x.label_data for x in new_manifest.images[1].labels] == [0]
+        assert [x.label_data for x in new_manifest.images[2].labels] == [0]
+        assert [x.label_data for x in new_manifest.images[3].labels] == [0, 1]
+
+
+class TestSpawn(unittest.TestCase):
+    def test_spawn_od_manifest(self):
+        images = [
+            ImageDataManifest(0, './0.jpg', 10, 10, []),
+            ImageDataManifest(1, './1.jpg', 10, 10, [ImageObjectDetectionLabelManifest([0, 1, 1, 2, 2]), ImageObjectDetectionLabelManifest([1, 2, 2, 3, 3])]),
+            ImageDataManifest(2, './2.jpg', 10, 10, [ImageObjectDetectionLabelManifest([1, 1, 1, 2, 2])]),
+            ImageDataManifest(3, './3.jpg', 10, 10, [ImageObjectDetectionLabelManifest([1, 0, 0, 2, 2]),
+                              ImageObjectDetectionLabelManifest([2, 1, 1, 2, 2]), ImageObjectDetectionLabelManifest([3, 2, 2, 3, 3])]),
+        ]
+        dst_size = 120
+        manifest = DatasetManifest(images, [CategoryManifest(i, x) for i, x in enumerate(['a', 'b', 'c', 'd'])], DatasetTypes.IMAGE_OBJECT_DETECTION)
+        spawner = SpawnFactory.create(DatasetTypes.IMAGE_OBJECT_DETECTION, SpawnConfig(0, dst_size))
+        new_manifest = spawner.run(manifest)
+        self.assertEqual(len(new_manifest), dst_size)
+
+        spawner = SpawnFactory.create(DatasetTypes.IMAGE_OBJECT_DETECTION, SpawnConfig(0, dst_size, [0., 0.5, 0.5, 1.]))
+        new_manifest = spawner.run(manifest)
+        cnt = self.cnt_multiclass_labels(new_manifest)
+        self.assertEqual(cnt, [30, 120, 60, 60])
+
+    def test_spawn_ic_multilabel_manifest(self):
+        images = [
+            ImageDataManifest(0, './0.jpg', 10, 10, []),
+            ImageDataManifest(1, './1.jpg', 10, 10, [ImageClassificationLabelManifest(0), ImageClassificationLabelManifest(1)]),
+            ImageDataManifest(1, './1.jpg', 10, 10, [ImageClassificationLabelManifest(0), ImageClassificationLabelManifest(1)]),
+            ImageDataManifest(2, './2.jpg', 10, 10, [ImageClassificationLabelManifest(1)]),
+        ]
+        dst_size = 60
+        manifest = DatasetManifest(images, [CategoryManifest(0, 'a'), CategoryManifest(1, 'b')], DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+        spawner = SpawnFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, SpawnConfig(0, dst_size))
+        new_manifest = spawner.run(manifest)
+        self.assertEqual(len(new_manifest), dst_size)
+        spawner = SpawnFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, SpawnConfig(0, dst_size, [20, 10, 10, 20]))
+        new_manifest = spawner.run(manifest)
+        cnt = self.cnt_multiclass_labels(new_manifest)
+        self.assertEqual(cnt, [20, 40])
+
+    def test_spawn_ic_multiclass_manifest(self):
+        images = [
+            ImageDataManifest(0, './0.jpg', 10, 10, [ImageClassificationLabelManifest(0)]),
+            ImageDataManifest(1, './1.jpg', 10, 10, [ImageClassificationLabelManifest(0)]),
+            ImageDataManifest(1, './1.jpg', 10, 10, [ImageClassificationLabelManifest(2)]),
+            ImageDataManifest(2, './2.jpg', 10, 10, [ImageClassificationLabelManifest(1)]),
+        ]
+        manifest = DatasetManifest(images, [CategoryManifest(0, 'a'), CategoryManifest(1, 'b'), CategoryManifest(2, 'c')], DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+        dst_size = 120
+        spawner = SpawnFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, SpawnConfig(0, dst_size))
+        new_manifest = spawner.run(manifest)
+        self.assertEqual(len(new_manifest), dst_size)
+
+        # Generate balanced instance weights, spawn the dataset to balance classes.
+        from vision_datasets.common.data_manifest import BalancedInstanceWeightsGenerator, WeightsGenerationConfig
+        instance_weights = BalancedInstanceWeightsGenerator(WeightsGenerationConfig(False)).run(manifest)
+        spawner = SpawnFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, SpawnConfig(0, dst_size, instance_weights))
+        new_manifest = spawner.run(manifest)
+        cnt = self.cnt_multiclass_labels(new_manifest)
+        self.assertEqual(cnt, [40, 40, 40])
+
+    def cnt_multiclass_labels(self, manifest):
+        n_images_by_classe = [0] * len(manifest.categories) if not manifest.is_multitask else [0] * sum([len(x) for x in manifest.categories.values()])
+        for im in manifest.images:
+            for label in im.labels:
+                n_images_by_classe[label.category_id] += 1
+        return n_images_by_classe
+
+
+class TestCocoGeneration(unittest.TestCase):
+    def test_coco_generation(self):
+        for data_type in [
+                DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, DatasetTypes.IMAGE_OBJECT_DETECTION, DatasetTypes.IMAGE_CAPTION,
+                DatasetTypes.IMAGE_REGRESSION, DatasetTypes.TEXT_2_IMAGE_RETRIEVAL]:
+            for i in range(len(TestCases.manifest_dict_by_data_type[data_type])):
+                manifest = TestCases.get_manifest(data_type, i)
+                coco_dict = CocoDictGeneratorFactory.create(data_type).run(manifest)
+
+                assert coco_dict == TestCases.manifest_dict_by_data_type[data_type][i], f'fails with {data_type} {i}'
+
+
+class TestDatasetManifestMerge(unittest.TestCase):
+    def test_merge_two_ic_datasets_diff_labelmap(self):
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+        merger = ManifestMerger(strategy)
+        merged_manifest = merger.run(TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, 0),
+                                     TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, 1))
+        assert [c.name for c in merged_manifest.categories] == ['cat', 'dog', 'tiger', 'rabbit']
+        assert [x.label_data for x in merged_manifest.images[0].labels] == [0]
+        assert [x.label_data for x in merged_manifest.images[1].labels] == [0, 1]
+        assert [x.label_data for x in merged_manifest.images[2].labels] == [2]
+        assert [x.label_data for x in merged_manifest.images[3].labels] == [2, 3]
+
+    def test_merge_two_ic_datasets_same_labelmap(self):
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+        merger = ManifestMerger(strategy)
+        merged_manifest = merger.run(TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, 0),
+                                     TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, 0))
+        assert [c.name for c in merged_manifest.categories] == ['cat', 'dog']
+        assert [x.label_data for x in merged_manifest.images[0].labels] == [0]
+        assert [x.label_data for x in merged_manifest.images[1].labels] == [0, 1]
+        assert [x.label_data for x in merged_manifest.images[2].labels] == [0]
+        assert [x.label_data for x in merged_manifest.images[3].labels] == [0, 1]
+
+    def test_merge_three_ic_datasets_diff_labelmap(self):
+        md3 = copy.deepcopy(TestCases.ic_multiclass_manifest_dicts[2])
+        md3['categories'] = [{"id": 1, "name": "human"}, {"id": 2, "name": "snake"}]
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS)
+        merger = ManifestMerger(strategy)
+        merged_manifest = merger.run(TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 0),
+                                     TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 1),
+                                     _coco_dict_to_manifest(md3, DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS))
+        assert [c.name for c in merged_manifest.categories] == ['cat', 'dog', 'tiger', 'rabbit', 'human', 'snake']
+        assert [x.label_data for x in merged_manifest.images[0].labels] == [0]
+        assert [x.label_data for x in merged_manifest.images[1].labels] == [1]
+        assert [x.label_data for x in merged_manifest.images[2].labels] == [2]
+        assert [x.label_data for x in merged_manifest.images[3].labels] == [3]
+        assert [x.label_data for x in merged_manifest.images[4].labels] == [4]
+        assert [x.label_data for x in merged_manifest.images[5].labels] == [5]
+
+    def test_merge_two_od_datasets_diff_labelmap(self):
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.IMAGE_OBJECT_DETECTION)
+        merger = ManifestMerger(strategy)
+        merged_manifest = merger.run(TestCases.get_manifest(DatasetTypes.IMAGE_OBJECT_DETECTION, 0),
+                                     TestCases.get_manifest(DatasetTypes.IMAGE_OBJECT_DETECTION, 1))
+        assert [c.name for c in merged_manifest.categories] == ['cat', 'dog', 'tiger', 'rabbit']
+        assert [x.label_data for x in merged_manifest.images[0].labels] == [[0, 10, 10, 100, 100]]
+        assert [x.label_data for x in merged_manifest.images[1].labels] == [[0, 100, 100, 200, 200], [1, 20, 20, 200, 200]]
+        assert [x.label_data for x in merged_manifest.images[2].labels] == [[2, 10, 10, 90, 90]]
+        assert [x.label_data for x in merged_manifest.images[3].labels] == [[2, 90, 90, 180, 180], [3, 20, 20, 200, 200]]
+
+    def test_merge_two_od_datasets_same_labelmap(self):
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.IMAGE_OBJECT_DETECTION)
+        merger = ManifestMerger(strategy)
+        merged_manifest = merger.run(TestCases.get_manifest(DatasetTypes.IMAGE_OBJECT_DETECTION, 0),
+                                     TestCases.get_manifest(DatasetTypes.IMAGE_OBJECT_DETECTION, 2))
+        assert [c.name for c in merged_manifest.categories] == ['cat', 'dog']
+        assert [x.label_data for x in merged_manifest.images[0].labels] == [[0, 10, 10, 100, 100]]
+        assert [x.label_data for x in merged_manifest.images[1].labels] == [[0, 100, 100, 200, 200], [1, 20, 20, 200, 200]]
+        assert [x.label_data for x in merged_manifest.images[2].labels] == [[0, 10, 10, 90, 90]]
+        assert [x.label_data for x in merged_manifest.images[3].labels] == [[1, 90, 90, 180, 180]]
+
+    def test_merge_two_caption_datasets(self):
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.IMAGE_CAPTION)
+        merger = ManifestMerger(strategy)
+        merged_manifest = merger.run(TestCases.get_manifest(DatasetTypes.IMAGE_CAPTION, 0),
+                                     TestCases.get_manifest(DatasetTypes.IMAGE_CAPTION, 1))
+
+        assert not merged_manifest.categories
+        assert len(merged_manifest) == 4
+        assert [x.label_data for x in merged_manifest.images[0].labels] == ['test 1.']
+        assert [x.label_data for x in merged_manifest.images[1].labels] == ['test 2.']
+        assert [x.label_data for x in merged_manifest.images[2].labels] == ['test 3.']
+        assert [x.label_data for x in merged_manifest.images[3].labels] == ['test 4.']
+
+    def test_merge_multitask_datasets_flavor0_with_same_tasks_different_types(self):
+        multitask_manifest_1 = generate_multitask_dataset_manifest({
+            'task1': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL, 0),
+            'task2': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 1)
+        })
+
+        multitask_manifest_2 = generate_multitask_dataset_manifest({
+            'task1': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 0),
+            'task2': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 1),
+        })
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.MULTITASK)
+        merger = ManifestMerger(strategy)
+        self.assertRaises(ValueError, lambda: merger.run(multitask_manifest_1, multitask_manifest_2))
+
+    def test_merge_multitask_datasets_flavor0_with_different_tasks_should_raise(self):
+        multitask_manifest_1 = generate_multitask_dataset_manifest({
+            'task1': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 0),
+            'task3': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 1)
+        })
+
+        multitask_manifest_2 = generate_multitask_dataset_manifest({
+            'task1': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 0),
+            'task2': TestCases.get_manifest(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, 1),
+        })
+        strategy = ManifestMergeStrategyFactory.create(DatasetTypes.MULTITASK)
+        merger = ManifestMerger(strategy)
+        self.assertRaises(ValueError, lambda: merger.run(multitask_manifest_1, multitask_manifest_2))
+
+
+if __name__ == '__main__':
+    unittest.main()
```

### Comparing `vision_datasets-0.2.9/tests/test_file_reader.py` & `vision_datasets-1.0.0/tests/test_file_reader.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,93 +1,94 @@
-import contextlib
-import multiprocessing
-import os
-import pathlib
-import pickle
-import tempfile
-import unittest
-import zipfile
-
-from vision_datasets.common.util import FileReader, MultiProcessZipFile
-
-
-def open_zipfile(zip_file, filename, queue):
-    queue.put(zip_file.open(filename).read())
-
-
-class TestMultiProcessZipFile(unittest.TestCase):
-    def test_single_process(self):
-        with self._with_test_zip({'test.txt': b'contents'}) as zip_filepath:
-            zip_file = MultiProcessZipFile(zip_filepath)
-            with zip_file.open('test.txt') as z:
-                self.assertEqual(z.read(), b'contents')
-            zip_file.close()
-
-    def test_access_from_multiple_process(self):
-        with self._with_test_zip({'test.txt': b'contents'}) as zip_filepath:
-            zip_file = MultiProcessZipFile(zip_filepath)
-            queue = multiprocessing.Queue()
-            processes = [multiprocessing.Process(target=open_zipfile, args=(zip_file, 'test.txt', queue)) for i in
-                         range(5)]
-            [p.start() for p in processes]
-            [p.join() for p in processes]
-
-            self.assertEqual(queue.get(False), b'contents')
-            self.assertEqual(queue.get(False), b'contents')
-            self.assertEqual(queue.get(False), b'contents')
-            self.assertEqual(queue.get(False), b'contents')
-            self.assertEqual(queue.get(False), b'contents')
-            self.assertTrue(queue.empty())
-
-    def test_pickle(self):
-        with self._with_test_zip({'test.txt': b'contents'}) as zip_filepath:
-            zip_file = MultiProcessZipFile(zip_filepath)
-            with zip_file.open('test.txt') as z:
-                self.assertEqual(z.read(), b'contents')
-
-            serialized = pickle.dumps(zip_file)
-            deserialized = pickle.loads(serialized)
-
-            with deserialized.open('test.txt') as z:
-                self.assertEqual(z.read(), b'contents')
-
-            deserialized.close()
-            zip_file.close()
-
-    @staticmethod
-    @contextlib.contextmanager
-    def _with_test_zip(contents):
-        """
-        Args:
-            contents: {filename: binary_contents} Files to be put in the test zip file.
-        """
-
-        with tempfile.TemporaryDirectory() as tempdir:
-            zip_filepath = pathlib.Path(tempdir) / 'test.zip'
-            with zipfile.ZipFile(zip_filepath, 'w') as f:
-                for filename, bin_contents in contents.items():
-                    f.writestr(filename, bin_contents)
-
-            yield zip_filepath
-
-
-class TestFileReader(unittest.TestCase):
-    def test_read(self):
-        with tempfile.TemporaryDirectory() as tempdir:
-            with zipfile.ZipFile(os.path.join(tempdir, 'test.zip'), 'w') as f:
-                f.writestr('test.txt', b'zip_contents')
-            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
-                f.write('txt_contents')
-
-            reader = FileReader()
-            file = reader.open(os.path.join(tempdir, 'test.zip') + '@test.txt')
-            self.assertIsNotNone(file)
-            self.assertEqual(file.read(), b'zip_contents')
-            file.close()
-
-            with reader.open(os.path.join(tempdir, 'test.txt')) as f:
-                self.assertEqual(f.read(), 'txt_contents')
-            reader.close()
-
-
-if __name__ == '__main__':
-    unittest.main()
+import contextlib
+import multiprocessing
+import os
+import pathlib
+import pickle
+import tempfile
+import unittest
+import zipfile
+
+from vision_datasets.common import FileReader
+from vision_datasets.common.data_reader.file_reader import MultiProcessZipFile
+
+
+def open_zipfile(zip_file, filename, queue):
+    queue.put(zip_file.open(filename).read())
+
+
+class TestMultiProcessZipFile(unittest.TestCase):
+    def test_single_process(self):
+        with self._with_test_zip({'test.txt': b'contents'}) as zip_filepath:
+            zip_file = MultiProcessZipFile(zip_filepath)
+            with zip_file.open('test.txt') as z:
+                self.assertEqual(z.read(), b'contents')
+            zip_file.close()
+
+    def test_access_from_multiple_process(self):
+        with self._with_test_zip({'test.txt': b'contents'}) as zip_filepath:
+            zip_file = MultiProcessZipFile(zip_filepath)
+            queue = multiprocessing.Queue()
+            processes = [multiprocessing.Process(target=open_zipfile, args=(zip_file, 'test.txt', queue)) for i in
+                         range(5)]
+            [p.start() for p in processes]
+            [p.join() for p in processes]
+
+            self.assertEqual(queue.get(False), b'contents')
+            self.assertEqual(queue.get(False), b'contents')
+            self.assertEqual(queue.get(False), b'contents')
+            self.assertEqual(queue.get(False), b'contents')
+            self.assertEqual(queue.get(False), b'contents')
+            self.assertTrue(queue.empty())
+
+    def test_pickle(self):
+        with self._with_test_zip({'test.txt': b'contents'}) as zip_filepath:
+            zip_file = MultiProcessZipFile(zip_filepath)
+            with zip_file.open('test.txt') as z:
+                self.assertEqual(z.read(), b'contents')
+
+            serialized = pickle.dumps(zip_file)
+            deserialized = pickle.loads(serialized)
+
+            with deserialized.open('test.txt') as z:
+                self.assertEqual(z.read(), b'contents')
+
+            deserialized.close()
+            zip_file.close()
+
+    @staticmethod
+    @contextlib.contextmanager
+    def _with_test_zip(contents):
+        """
+        Args:
+            contents: {filename: binary_contents} Files to be put in the test zip file.
+        """
+
+        with tempfile.TemporaryDirectory() as tempdir:
+            zip_filepath = pathlib.Path(tempdir) / 'test.zip'
+            with zipfile.ZipFile(zip_filepath, 'w') as f:
+                for filename, bin_contents in contents.items():
+                    f.writestr(filename, bin_contents)
+
+            yield zip_filepath
+
+
+class TestFileReader(unittest.TestCase):
+    def test_read(self):
+        with tempfile.TemporaryDirectory() as tempdir:
+            with zipfile.ZipFile(os.path.join(tempdir, 'test.zip'), 'w') as f:
+                f.writestr('test.txt', b'zip_contents')
+            with open(os.path.join(tempdir, 'test.txt'), 'w') as f:
+                f.write('txt_contents')
+
+            reader = FileReader()
+            file = reader.open(os.path.join(tempdir, 'test.zip') + '@test.txt')
+            self.assertIsNotNone(file)
+            self.assertEqual(file.read(), b'zip_contents')
+            file.close()
+
+            with reader.open(os.path.join(tempdir, 'test.txt')) as f:
+                self.assertEqual(f.read(), 'txt_contents')
+            reader.close()
+
+
+if __name__ == '__main__':
+    unittest.main()
```

### Comparing `vision_datasets-0.2.9/tests/test_pytorch_dataset.py` & `vision_datasets-1.0.0/tests/test_pytorch_dataset.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,46 +1,46 @@
-import pickle
-import unittest
-
-from vision_datasets.pytorch import TorchDataset
-
-
-class FakeDataset:
-    pass
-
-
-def _one_arg_method(x):
-    return x
-
-
-class TestPytorchDataset(unittest.TestCase):
-    def test_picklable(self):
-        dataset = TorchDataset(FakeDataset())
-        serialized = pickle.dumps(dataset)
-        new_dataset = pickle.loads(serialized)
-        self.assertIsInstance(new_dataset, TorchDataset)
-
-        dataset = TorchDataset(FakeDataset(), _one_arg_method)
-        serialized = pickle.dumps(dataset)
-        new_dataset = pickle.loads(serialized)
-        self.assertIsInstance(new_dataset, TorchDataset)
-
-        dataset = TorchDataset(FakeDataset())
-        dataset.transform = None
-        serialized = pickle.dumps(dataset)
-        new_dataset = pickle.loads(serialized)
-        self.assertIsInstance(new_dataset, TorchDataset)
-
-    def test_transform(self):
-        dataset = TorchDataset(FakeDataset(), None)
-        assert dataset.transform(1, 2) == (1, 2)
-        dataset = TorchDataset(FakeDataset(), lambda x: x)
-        assert dataset.transform(1, 2) == (1, 2)
-        dataset = TorchDataset(FakeDataset(), lambda x, y: (x, y))
-        assert dataset.transform(1, 2) == (1, 2)
-
-        dataset.transform = lambda x: x
-        assert dataset.transform(1, 2) == (1, 2)
-
-
-if __name__ == '__main__':
-    unittest.main()
+import pickle
+import unittest
+
+from vision_datasets.common import TorchDataset
+
+
+class FakeDataset:
+    pass
+
+
+def _one_arg_method(x):
+    return x
+
+
+class TestPytorchDataset(unittest.TestCase):
+    def test_picklable(self):
+        dataset = TorchDataset(FakeDataset())
+        serialized = pickle.dumps(dataset)
+        new_dataset = pickle.loads(serialized)
+        self.assertIsInstance(new_dataset, TorchDataset)
+
+        dataset = TorchDataset(FakeDataset(), _one_arg_method)
+        serialized = pickle.dumps(dataset)
+        new_dataset = pickle.loads(serialized)
+        self.assertIsInstance(new_dataset, TorchDataset)
+
+        dataset = TorchDataset(FakeDataset())
+        dataset.transform = None
+        serialized = pickle.dumps(dataset)
+        new_dataset = pickle.loads(serialized)
+        self.assertIsInstance(new_dataset, TorchDataset)
+
+    def test_transform(self):
+        dataset = TorchDataset(FakeDataset(), None)
+        assert dataset.transform(1, 2) == (1, 2)
+        dataset = TorchDataset(FakeDataset(), lambda x: x)
+        assert dataset.transform(1, 2) == (1, 2)
+        dataset = TorchDataset(FakeDataset(), lambda x, y: (x, y))
+        assert dataset.transform(1, 2) == (1, 2)
+
+        dataset.transform = lambda x: x
+        assert dataset.transform(1, 2) == (1, 2)
+
+
+if __name__ == '__main__':
+    unittest.main()
```

### Comparing `vision_datasets-0.2.9/vision_datasets/commands/converter_od_to_ic.py` & `vision_datasets-1.0.0/vision_datasets/commands/converter_od_to_ic.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,85 +1,85 @@
-import json
-import logging
-import multiprocessing
-import os
-import pathlib
-import shutil
-
-from vision_datasets import DatasetHub, Usages
-from vision_datasets.common.manifest_dataset import DetectionAsClassificationByCroppingDataset
-
-logger = logging.getLogger(__name__)
-logging.basicConfig(level=logging.INFO)
-
-
-def create_arg_parser():
-    import argparse
-
-    parser = argparse.ArgumentParser(description='Convert OD dataset to ic dataset.')
-    parser.add_argument('-n', '--name', type=str, required=True, help='dataset name')
-    parser.add_argument('-r', '--reg_json_path', type=str, default=None, help="dataset registration json path.", required=True)
-    parser.add_argument('-k', '--sas', type=str, help="sas url.", required=False, default=None)
-    parser.add_argument('-l', '--local_folder', type=str, help="detection dataset folder.", required=False)
-    parser.add_argument('-o', '--output_folder', type=str, required=True, help='target folder of the converted classification dataset')
-    parser.add_argument('-zb', '--zoom_ratio_bounds', type=str, required=False,
-                        help='lower and bound of the ratio that box height and width can expand (>1) or shrink (0-1), during cropping, e.g, 0.8/1.2')
-    parser.add_argument('-sb', '--shift_relative_bounds', type=str, required=False,
-                        help='lower/upper bounds of relative ratio wrt box width and height that a box can shift, during cropping, e.g., "-0.3/0.1"')
-    parser.add_argument('-np', '--n_copies', type=int, required=False, default=1, help='number of copies per bbox')
-    parser.add_argument('-s', '--rnd_seed', type=int, required=False, help='random see for box expansion/shrink/shifting.', default=0)
-    parser.add_argument('--zip', dest='zip', action='store_true', help='Flag to add zip prefix to the image paths.')
-
-    return parser
-
-
-def process_phase(params):
-    args, aug_params, phase = params
-
-    logger.info(f'download dataset manifest for {args.name}...')
-    dataset_resources = DatasetHub(pathlib.Path(args.reg_json_path).read_text())
-    dataset = dataset_resources.create_manifest_dataset(args.sas, args.local_folder, args.name, usage=phase, coordinates='absolute')
-    if not dataset:
-        logger.info(f'Skipping non-existent phase {phase}.')
-        return
-
-    logger.info(f'start conversion for {args.name}...')
-    ic_dataset = DetectionAsClassificationByCroppingDataset(dataset, aug_params)
-    manifest = ic_dataset.generate_manifest(dir=phase, n_copies=args.n_copies)
-    if args.zip:
-        for img in manifest.images:
-            img.img_path = f'{phase}.zip@{img.img_path}'
-
-    coco = manifest.generate_coco_annotations()
-    with open(f'{args.output_folder}/{phase}.json', 'w') as coco_out:
-        coco_out.write(json.dumps(coco, indent=2))
-    shutil.move(f'{phase}', f'{args.output_folder}/', copy_function=shutil.copytree)
-
-
-def main():
-    arg_parser = create_arg_parser()
-    args = arg_parser.parse_args()
-    aug_params = {}
-    if args.zoom_ratio_bounds:
-        low, up = args.zoom_ratio_bounds.split('/')
-        aug_params['zoom_ratio_bounds'] = (float(low), float(up))
-
-    if args.shift_relative_bounds:
-        low, up = args.shift_relative_bounds.split('/')
-        aug_params['shift_relative_bounds'] = (float(low), float(up))
-
-    if aug_params:
-        aug_params['rnd_seed'] = args.rnd_seed
-
-    if not os.path.exists(args.output_folder):
-        os.makedirs(args.output_folder)
-
-    if args.local_folder and not os.path.exists(args.local_folder):
-        os.makedirs(args.local_folder)
-
-    params = [(args, aug_params, phase) for phase in [Usages.TRAIN_PURPOSE, Usages.VAL_PURPOSE, Usages.TEST_PURPOSE]]
-    with multiprocessing.Pool(3) as pool:
-        pool.map(process_phase, params)
-
-
-if __name__ == '__main__':
-    main()
+"""
+Convert a detection dataset into classification dataset
+"""
+
+import argparse
+import multiprocessing
+import os
+import pathlib
+import shutil
+
+from vision_datasets.common import CocoDictGeneratorFactory, DatasetHub, DatasetTypes
+from vision_datasets.image_object_detection import DetectionAsClassificationByCroppingDataset
+
+from .utils import add_args_to_locate_dataset, get_or_generate_data_reg_json_and_usages, set_up_cmd_logger, write_to_json_file_utf8
+
+logger = set_up_cmd_logger(__name__)
+
+
+def create_arg_parser():
+    parser = argparse.ArgumentParser(description='Convert detection dataset to classification dataset.')
+    add_args_to_locate_dataset(parser)
+    parser.add_argument('-o', '--output_folder', type=pathlib.Path, required=True, help='target folder of the converted classification dataset')
+
+    parser.add_argument('-zb', '--zoom_ratio_bounds', type=str, required=False,
+                        help='lower and bound of the ratio that box height and width can expand (>1) or shrink (0-1), during cropping, e.g, 0.8/1.2')
+    parser.add_argument('-sb', '--shift_relative_bounds', type=str, required=False,
+                        help='lower/upper bounds of relative ratio wrt box width and height that a box can shift, during cropping, e.g., "-0.3/0.1"')
+    parser.add_argument('-np', '--n_copies', type=int, required=False, default=1, help='number of copies per bbox')
+    parser.add_argument('-s', '--rnd_seed', type=int, required=False, help='random see for box expansion/shrink/shifting.', default=0)
+
+    return parser
+
+
+def process_usage(params):
+    args, data_reg_json, aug_params, usage = params
+
+    logger.info(f'download dataset manifest for {args.name}...')
+    dataset_resources = DatasetHub(data_reg_json)
+    dataset = dataset_resources.create_manifest_dataset(args.blob_container, str(args.local_dir.as_posix()), args.name, usage=usage, coordinates='absolute')
+    if not dataset:
+        logger.info(f'Skipping non-existent phase {usage}.')
+        return
+
+    if dataset.dataset_info.type != DatasetTypes.IMAGE_OBJECT_DETECTION:
+        raise ValueError(f'Data type must be {DatasetTypes.IMAGE_OBJECT_DETECTION}')
+    logger.info(f'start conversion for {args.name}...')
+    ic_dataset = DetectionAsClassificationByCroppingDataset(dataset, aug_params)
+    ic_manifest = ic_dataset.generate_manifest(dir=str(usage), n_copies=args.n_copies)
+
+    coco_gen = CocoDictGeneratorFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTILABEL)
+    coco = coco_gen.run(ic_manifest)
+    write_to_json_file_utf8(coco, args.output_folder / f'{usage}.json')
+    shutil.move(f'{usage}', f'{args.output_folder.as_posix()}/', copy_function=shutil.copytree)
+
+
+def main():
+    arg_parser = create_arg_parser()
+    args = arg_parser.parse_args()
+    aug_params = {}
+    if args.zoom_ratio_bounds:
+        low, up = args.zoom_ratio_bounds.split('/')
+        aug_params['zoom_ratio_bounds'] = (float(low), float(up))
+
+    if args.shift_relative_bounds:
+        low, up = args.shift_relative_bounds.split('/')
+        aug_params['shift_relative_bounds'] = (float(low), float(up))
+
+    if aug_params:
+        aug_params['rnd_seed'] = args.rnd_seed
+
+    if not os.path.exists(args.output_folder):
+        os.makedirs(args.output_folder)
+
+    if args.blob_container and args.local_dir:
+        args.local_dir.mkdir(parents=True, exist_ok=True)
+
+    data_reg_json, usages = get_or_generate_data_reg_json_and_usages(args)
+    params = [(args, data_reg_json, aug_params, phase) for phase in usages]
+
+    with multiprocessing.Pool(len(usages)) as pool:
+        pool.map(process_usage, params)
+
+
+if __name__ == '__main__':
+    main()
```

### Comparing `vision_datasets-0.2.9/vision_datasets/common/base_dataset.py` & `vision_datasets-1.0.0/vision_datasets/common/dataset/base_dataset.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,46 +1,46 @@
-from abc import ABC, abstractmethod
-
-from .dataset_info import BaseDatasetInfo
-
-
-class BaseDataset(ABC):
-    def __init__(self, dataset_info: BaseDatasetInfo):
-
-        self.dataset_info = dataset_info
-
-    def __getitem__(self, idx):
-        """ iterate through the dataset
-
-        Args:
-            idx: can be a single index or range
-
-        Returns:
-            requested sample(s)
-        """
-
-        if isinstance(idx, int):
-            if idx >= self.__len__():
-                raise IndexError
-            return self._get_single_item(idx)
-
-        stop = min(self.__len__(), idx.stop)
-        return [self.__getitem__(i) for i in range(idx.start, stop, idx.step)] if idx.step else [self.__getitem__(i) for i in range(idx.start, stop)]
-
-    @property
-    @abstractmethod
-    def labels(self):
-        pass
-
-    @abstractmethod
-    def __len__(self):
-        pass
-
-    @abstractmethod
-    def _get_single_item(self, index):
-        pass
-
-    @abstractmethod
-    def close(self):
-        """ release resources
-        """
-        pass
+from abc import ABC, abstractmethod
+
+from ..dataset_info import BaseDatasetInfo
+
+
+class BaseDataset(ABC):
+    def __init__(self, dataset_info: BaseDatasetInfo):
+
+        self.dataset_info = dataset_info
+
+    def __getitem__(self, idx):
+        """ iterate through the dataset
+
+        Args:
+            idx: can be a single index or range
+
+        Returns:
+            requested sample(s)
+        """
+
+        if isinstance(idx, int):
+            if idx >= self.__len__():
+                raise IndexError
+            return self._get_single_item(idx)
+
+        stop = min(self.__len__(), idx.stop)
+        return [self.__getitem__(i) for i in range(idx.start, stop, idx.step)] if idx.step else [self.__getitem__(i) for i in range(idx.start, stop)]
+
+    @property
+    @abstractmethod
+    def categories(self):
+        pass
+
+    @abstractmethod
+    def __len__(self):
+        pass
+
+    @abstractmethod
+    def _get_single_item(self, index):
+        pass
+
+    @abstractmethod
+    def close(self):
+        """ release resources
+        """
+        pass
```

### Comparing `vision_datasets-0.2.9/vision_datasets/common/dataset_registry.py` & `vision_datasets-1.0.0/vision_datasets/common/dataset_management/dataset_registry.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,42 +1,44 @@
-import copy
-import json
-from .dataset_info import DatasetInfoFactory
-from typing import Union
-
-
-class DatasetRegistry:
-    """
-    A central registry of all available datasets
-    """
-
-    def __init__(self, datasets_json: Union[str, list]):
-        if isinstance(datasets_json, list):
-            self.datasets = [DatasetInfoFactory.create(d) for dj in datasets_json for d in json.loads(dj)]
-        else:
-            self.datasets = [DatasetInfoFactory.create(d) for d in json.loads(datasets_json)]
-
-    def get_dataset_info(self, dataset_name, dataset_version=None):
-        datasets = [d for d in self.datasets if d.name == dataset_name and (not dataset_version or d.version == dataset_version)]
-        if not datasets:
-            return None
-
-        sorted_datasets = sorted(datasets, key=lambda d: d.version)
-        return copy.deepcopy(sorted_datasets[-1])
-
-    def list_data_version_and_types(self):
-        return [{'name': d.name, 'version': d.version, 'type': d.type, 'description': d.description} for d in self.datasets]
-
-    @staticmethod
-    def _get_default_dataset_json(json_file_name):
-        import sys
-        py_version = sys.version_info
-        if py_version.minor >= 7:
-            import importlib.resources as pkg_resources
-            from vision_datasets import resources
-            datasets_json = pkg_resources.read_text(resources, json_file_name)
-        else:
-            import pkgutil
-            resource_package = 'vision_datasets'
-            resource_path = '/'.join(('resources', json_file_name))
-            datasets_json = pkgutil.get_data(resource_package, resource_path)
-        return datasets_json
+import copy
+import json
+from typing import Union
+
+from ..dataset_info import DatasetInfoFactory
+
+
+class DatasetRegistry:
+    """
+    A central registry of all available datasets
+    """
+
+    def __init__(self, datasets_json: Union[str, list]):
+        if isinstance(datasets_json, list):
+            self.datasets = [DatasetInfoFactory.create(d) for dj in datasets_json for d in json.loads(dj)]
+        else:
+            self.datasets = [DatasetInfoFactory.create(d) for d in json.loads(datasets_json)]
+
+    def get_dataset_info(self, dataset_name, dataset_version=None):
+        datasets = [d for d in self.datasets if d.name == dataset_name and (not dataset_version or d.version == dataset_version)]
+        if not datasets:
+            return None
+
+        sorted_datasets = sorted(datasets, key=lambda d: d.version)
+        return copy.deepcopy(sorted_datasets[-1])
+
+    def list_data_version_and_types(self):
+        return [{'name': d.name, 'version': d.version, 'type': d.type, 'description': d.description} for d in self.datasets]
+
+    @staticmethod
+    def _get_default_dataset_json(json_file_name):
+        import sys
+        py_version = sys.version_info
+        if py_version.minor >= 7:
+            import importlib.resources as pkg_resources
+
+            from vision_datasets.common import resources
+            datasets_json = pkg_resources.read_text(resources, json_file_name)
+        else:
+            import pkgutil
+            resource_package = 'vision_datasets'
+            resource_path = '/'.join(('resources', json_file_name))
+            datasets_json = pkgutil.get_data(resource_package, resource_path)
+        return datasets_json
```

### Comparing `vision_datasets-0.2.9/vision_datasets/common/image_loader.py` & `vision_datasets-1.0.0/vision_datasets/common/data_reader/image_loader.py`

 * *Ordering differences only*

 * *Files 22% similar despite different names*

```diff
@@ -1,41 +1,41 @@
-import logging
-
-from PIL import Image
-
-logger = logging.getLogger(__name__)
-
-# see https://exiv2.org/tags.html
-ORIENTATION_EXIF_TAG = 0x0112
-
-
-class PILImageLoader:
-    """Load PIL image and fix image orientation using EXIF"""
-
-    @staticmethod
-    def load_from_stream(f):
-        image = Image.open(f)
-        img_format = image.format
-
-        exif = image.getexif()
-        orientation = exif.get(ORIENTATION_EXIF_TAG) if exif else None
-        if orientation:
-            # orientation is 1 based, shift to zero based and flip/transpose based on 0-based values
-            orientation -= 1
-            if orientation >= 4:
-                image = image.transpose(Image.TRANSPOSE)
-            if orientation == 2 or orientation == 3 or orientation == 6 or orientation == 7:
-                image = image.transpose(Image.FLIP_TOP_BOTTOM)
-            if orientation == 1 or orientation == 2 or orientation == 5 or orientation == 6:
-                image = image.transpose(Image.FLIP_LEFT_RIGHT)
-        image = image.convert('RGB')
-        image.format = img_format
-        return image
-
-    @staticmethod
-    def load_from_file(filepath):
-        try:
-            with open(filepath, 'rb') as f:
-                return PILImageLoader.load_from_stream(f)
-        except Exception:
-            logger.exception(f'Failed to load an image: {filepath}')
-            raise
+import logging
+
+from PIL import Image
+
+logger = logging.getLogger(__name__)
+
+# see https://exiv2.org/tags.html
+ORIENTATION_EXIF_TAG = 0x0112
+
+
+class PILImageLoader:
+    """Load PIL image and fix image orientation using EXIF"""
+
+    @staticmethod
+    def load_from_stream(f):
+        image = Image.open(f)
+        img_format = image.format
+
+        exif = image.getexif()
+        orientation = exif.get(ORIENTATION_EXIF_TAG) if exif else None
+        if orientation:
+            # orientation is 1 based, shift to zero based and flip/transpose based on 0-based values
+            orientation -= 1
+            if orientation >= 4:
+                image = image.transpose(Image.TRANSPOSE)
+            if orientation == 2 or orientation == 3 or orientation == 6 or orientation == 7:
+                image = image.transpose(Image.FLIP_TOP_BOTTOM)
+            if orientation == 1 or orientation == 2 or orientation == 5 or orientation == 6:
+                image = image.transpose(Image.FLIP_LEFT_RIGHT)
+        image = image.convert('RGB')
+        image.format = img_format
+        return image
+
+    @staticmethod
+    def load_from_file(filepath):
+        try:
+            with open(filepath, 'rb') as f:
+                return PILImageLoader.load_from_stream(f)
+        except Exception:
+            logger.exception(f'Failed to load an image: {filepath}')
+            raise
```

### Comparing `vision_datasets-0.2.9/vision_datasets/pytorch/torch_dataset.py` & `vision_datasets-1.0.0/vision_datasets/common/dataset/torch_dataset.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,41 +1,42 @@
-import logging
-
-from .dataset import Dataset
-
-logger = logging.getLogger(__name__)
-
-
-class TorchDataset(Dataset):
-    """
-    Dataset class used for pytorch training
-    """
-
-    def __init__(self, manifest_dataset, transform=None):
-        Dataset.__init__(self, transform)
-        self.dataset = manifest_dataset
-
-    @property
-    def labels(self):
-        return self.dataset.labels
-
-    @property
-    def dataset_resources(self):
-        return self.dataset.dataset_resources
-
-    @property
-    def dataset_info(self):
-        return self.dataset.dataset_info
-
-    def __getitem__(self, index):
-        if isinstance(index, int):
-            image, target, idx_str = self.dataset[index]
-            image, target = self.transform(image, target)
-            return image, target, idx_str
-        else:
-            return [self.transform(img, target) + (idx,) for img, target, idx in self.dataset[index]]
-
-    def __len__(self):
-        return len(self.dataset)
-
-    def close(self):
-        self.dataset.close()
+import logging
+
+from .vision_dataset import VisionDataset
+from .dataset import Dataset
+
+logger = logging.getLogger(__name__)
+
+
+class TorchDataset(Dataset):
+    """
+    Dataset class used for pytorch training
+    """
+
+    def __init__(self, manifest_dataset: VisionDataset, transform=None):
+        Dataset.__init__(self, transform)
+        self.dataset = manifest_dataset
+
+    @property
+    def labels(self):
+        return self.dataset.categories
+
+    @property
+    def dataset_resources(self):
+        return self.dataset.dataset_resources
+
+    @property
+    def dataset_info(self):
+        return self.dataset.dataset_info
+
+    def __getitem__(self, index):
+        if isinstance(index, int):
+            image, target, idx_str = self.dataset[index]
+            image, target = self.transform(image, target.label_data)
+            return image, target, idx_str
+        else:
+            return [self.transform(img, target) + (idx,) for img, target, idx in self.dataset[index]]
+
+    def __len__(self):
+        return len(self.dataset)
+
+    def close(self):
+        self.dataset.close()
```

### Comparing `vision_datasets-0.2.9/vision_datasets/resources/dataset_hub.py` & `vision_datasets-1.0.0/vision_datasets/common/dataset_management/dataset_hub.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,129 +1,134 @@
-import logging
-from typing import Union, List
-
-from ..common import DatasetRegistry, Usages
-from ..common.data_manifest import DatasetManifest
-from ..common.dataset_info import MultiTaskDatasetInfo
-
-logger = logging.getLogger(__name__)
-
-
-class DatasetHub(object):
-    """
-    Hub class for managing vision dataset resources, with a few common utilities for creating a dataset.
-    This hub class works with both resources on local disk or on azure blob.
-    """
-
-    def __init__(self, dataset_json_str: Union[str, list]):
-        """
-
-        Args:
-            dataset_json_str (str, list): dataset registry json, containing multiple dataset_info for different datasets, or a list of dataset reg json
-            retrievable by their names, versions and usages.
-        """
-        assert dataset_json_str
-
-        self.dataset_registry = DatasetRegistry(dataset_json_str)
-
-    def create_manifest_dataset(self, container_sas: str, local_dir: str, name: str, version: int = None, usage: str = Usages.TRAIN_PURPOSE, coordinates: str = 'relative',
-                                few_shot_samples_per_class=None, rnd_seed=0):
-        """Create manifest dataset.
-            If local_dir is provided, manifest_dataset consumes data from local disk. If data not present on local disk, it will be automatically downloaded.
-            if container_sas is provided but local_dir not provided, manifest_dataset consumes data directly from container_sas.
-
-            Note that for data stored in zipped files, they can be consumed locally without unzip. However, in blob they must be stored in unzipped folders. In this case image/label file paths can
-            stay with paths to data in zipped files, as dataset class will automatically look in the folder names same with the zip file names.
-
-        Args:
-            container_sas: sas url to the container where datasets can be found/downloaded from
-            local_dir: local directory where datasets can be found/downloaded to
-            name: dataset name
-            version: dataset version, if not specified, latest version will be returned
-            usage: usage(s) of the dataset, 'train', 'val' or 'test' or a list of usages
-            coordinates: format of the bounding boxes, can be 'relative' or 'absolute'
-            few_shot_samples_per_class (int): get a sampled dataset with N images at most for each class (for detection and multilabel case, not guaranteed.)
-            rnd_seed (int): random seed for few shot sampling
-
-        Returns:
-            an instance of dataset for local usage
-        """
-        result = self.create_dataset_manifest(container_sas, local_dir, name, version, usage, few_shot_samples_per_class, rnd_seed)
-        if result:
-            manifest, dataset_info, downloader_resources = result
-        else:
-            return None
-
-        from vision_datasets import ManifestDataset
-        return ManifestDataset(dataset_info, manifest, coordinates, downloader_resources)
-
-    def create_dataset_manifest(self, container_sas: str, local_dir: str, name: str, version: int = None, usage: Union[str, List] = Usages.TRAIN_PURPOSE, few_shot_samples_per_class=None, rnd_seed=0):
-        """Create dataset manifest.
-            If local_dir is provided, manifest_dataset consumes data from local disk. If data not present on local disk, it will be automatically downloaded.
-            if container_sas is provided but local_dir not provided, manifest_dataset consumes data directly from container_sas.
-
-            Note that for data stored in zipped files, they can be consumed locally without unzip. However, in blob they must be stored in unzipped folders. In this case image/label file paths can
-            stay with paths to data in zipped files, as dataset class will automatically look in the folder names same with the zip file names.
-
-        Args:
-            container_sas: sas url to the container where datasets can be found/downloaded from
-            local_dir: local directory where datasets can be found/downloaded to
-            name: dataset name
-            version: dataset version, if not specified, latest version will be returned
-            usage: usage(s) of the dataset, 'train', 'val' or 'test' or a list of usages
-            few_shot_samples_per_class (int): get a sampled dataset with N images at most for each class (for detection and multilabel case, not guaranteed.)
-            rnd_seed (int): random seed for few shot sampling
-
-        Returns:
-            dataset manifest, dataset_info, downloaded_resources, if dataset exists, else None
-        """
-        assert container_sas or local_dir
-        assert name
-        assert usage
-
-        from ..common.dataset_downloader import DatasetDownloader
-
-        usages = usage if isinstance(usage, list) else [usage]
-
-        manifest = None
-        downloader_resources = None
-        dataset_info = self.dataset_registry.get_dataset_info(name, version)
-        if dataset_info is None:
-            logger.warning(f'Dataset with {name} and version {version} not found.')
-            return None
-
-        if isinstance(dataset_info, MultiTaskDatasetInfo):
-            for task_info in dataset_info.sub_task_infos.values():
-                task_info.index_files = {usage: task_info.index_files[usage] for usage in usages if usage in task_info.index_files}
-        else:
-            dataset_info.index_files = {usage: dataset_info.index_files[usage] for usage in usages if usage in dataset_info.index_files}
-
-        if container_sas and local_dir:
-            downloader = DatasetDownloader(container_sas, self.dataset_registry)
-            downloader_resources_usage = downloader.download(name, version, local_dir, usages)
-        else:
-            downloader_resources_usage = None
-
-        for usage in usages:
-            manifest_usage = DatasetManifest.create_dataset_manifest(dataset_info, usage, local_dir or container_sas)
-            if manifest_usage:
-                manifest = DatasetManifest.merge(manifest, manifest_usage) if manifest else manifest_usage
-
-            if downloader_resources_usage:
-                from ..common.dataset_downloader import DownloadedDatasetsResources
-                downloader_resources = DownloadedDatasetsResources.merge(downloader_resources, downloader_resources_usage) if downloader_resources else downloader_resources_usage
-
-        if manifest is None:
-            return None
-
-        if few_shot_samples_per_class:
-            original_img_cnt = len(manifest.images)
-            manifest = manifest.sample_few_shot_subset(few_shot_samples_per_class, rnd_seed)
-            logger.info(f'Create a few-shot dataset with n samples per class = {few_shot_samples_per_class}. # images: {original_img_cnt} => {len(manifest.images)}')
-
-        return manifest, dataset_info, downloader_resources
-
-    def list_data_version_and_types(self):
-        """List all dataset names, versions and types
-        """
-
-        return self.dataset_registry.list_data_version_and_types()
+import logging
+from typing import List, Union
+
+from ..constants import Usages
+from ..data_manifest import ManifestMerger
+from ..dataset_info import MultiTaskDatasetInfo
+from ..factory import DataManifestFactory, ManifestMergeStrategyFactory
+from ..dataset import VisionDataset
+from ..data_reader import DatasetDownloader, DownloadedDatasetsResources
+from .dataset_registry import DatasetRegistry
+
+logger = logging.getLogger(__name__)
+
+
+class DatasetHub(object):
+    """
+    Hub class for managing vision dataset resources, with a few common utilities for creating a dataset.
+    This hub class works with both resources on local disk or on azure blob.
+    """
+
+    def __init__(self, dataset_json_str: Union[str, list]):
+        """
+
+        Args:
+            dataset_json_str (str, list): dataset registry json, containing multiple dataset_info for different datasets, or a list of dataset reg json
+            retrievable by their names, versions and usages.
+        """
+        if not dataset_json_str:
+            raise ValueError
+
+        self.dataset_registry = DatasetRegistry(dataset_json_str)
+
+    def create_manifest_dataset(self, container_sas: str, local_dir: str, name: str, version: int = None, usage: Union[str, List] = Usages.TRAIN, coordinates: str = 'relative',
+                                few_shot_samples_per_class=None, rnd_seed=0):
+        """Create manifest dataset.
+            If local_dir is provided, manifest_dataset consumes data from local disk. If data not present on local disk, it will be automatically downloaded.
+            if container_sas is provided but local_dir not provided, manifest_dataset consumes data directly from container_sas.
+
+            Note that for data stored in zipped files, they can be consumed locally without unzip. However, in blob they must be stored in unzipped folders. In this case image/label file paths can
+            stay with paths to data in zipped files, as dataset class will automatically look in the folder names same with the zip file names.
+
+        Args:
+            container_sas: sas url to the container where datasets can be found/downloaded from
+            local_dir: local directory where datasets can be found/downloaded to
+            name: dataset name
+            version: dataset version, if not specified, latest version will be returned
+            usage: usage(s) of the dataset, 'train', 'val' or 'test' or a list of usages
+            coordinates: format of the bounding boxes, can be 'relative' or 'absolute'
+            few_shot_samples_per_class (int): get a sampled dataset with N images at most for each class (for detection and multilabel case, not guaranteed.)
+            rnd_seed (int): random seed for few shot sampling
+
+        Returns:
+            an instance of dataset for local usage
+        """
+        result = self.create_dataset_manifest(container_sas, local_dir, name, version, usage, few_shot_samples_per_class, rnd_seed)
+        if result:
+            manifest, dataset_info, downloader_resources = result
+        else:
+            return None
+
+        return VisionDataset(dataset_info, manifest, coordinates, downloader_resources)
+
+    def create_dataset_manifest(self, container_sas: str, local_dir: str, name: str, version: int = None, usage: Union[str, List] = Usages.TRAIN, few_shot_samples_per_class=None, rnd_seed=0):
+        """Create dataset manifest.
+            If local_dir is provided, manifest_dataset consumes data from local disk. If data not present on local disk, it will be automatically downloaded.
+            if container_sas is provided but local_dir not provided, manifest_dataset consumes data directly from container_sas.
+
+            Note that for data stored in zipped files, they can be consumed locally without unzip. However, in blob they must be stored in unzipped folders. In this case image/label file paths can
+            stay with paths to data in zipped files, as dataset class will automatically look in the folder names same with the zip file names.
+
+        Args:
+            container_sas: sas url to the container where datasets can be found/downloaded from
+            local_dir: local directory where datasets can be found/downloaded to
+            name: dataset name
+            version: dataset version, if not specified, latest version will be returned
+            usage: usage(s) of the dataset, 'train', 'val' or 'test' or a list of usages
+            few_shot_samples_per_class (int): get a sampled dataset with N images at most for each class (for detection and multilabel case, not guaranteed.)
+            rnd_seed (int): random seed for few shot sampling
+
+        Returns:
+            dataset manifest, dataset_info, downloaded_resources, if dataset exists, else None
+        """
+        if not container_sas and not local_dir:
+            raise ValueError('either container_sas or local_dir should be provided.')
+        if not name:
+            raise ValueError
+        if not usage:
+            raise ValueError
+
+        usages = usage if isinstance(usage, list) else [usage]
+
+        manifest = None
+        downloader_resources = None
+        dataset_info = self.dataset_registry.get_dataset_info(name, version)
+        if dataset_info is None:
+            logger.warning(f'Dataset with {name} and version {version} not found.')
+            return None
+
+        if isinstance(dataset_info, MultiTaskDatasetInfo):
+            for task_info in dataset_info.sub_task_infos.values():
+                task_info.index_files = {usage: task_info.index_files[usage] for usage in usages if usage in task_info.index_files}
+        else:
+            dataset_info.index_files = {usage: dataset_info.index_files[usage] for usage in usages if usage in dataset_info.index_files}
+
+        if container_sas and local_dir:
+            downloader = DatasetDownloader(container_sas, self.dataset_registry.get_dataset_info(name, version))
+            downloader_resources_usage = downloader.download(local_dir, usages)
+        else:
+            downloader_resources_usage = None
+
+        for usage in usages:
+            manifest_usage = DataManifestFactory.create(dataset_info, usage, local_dir or container_sas)
+            if manifest_usage is not None:
+                merger = ManifestMerger(ManifestMergeStrategyFactory.create(dataset_info.type))
+                manifest = merger.run(manifest, manifest_usage) if manifest else manifest_usage
+
+            if downloader_resources_usage:
+                downloader_resources = DownloadedDatasetsResources.merge(downloader_resources, downloader_resources_usage) if downloader_resources else downloader_resources_usage
+
+        if manifest is None:
+            return None
+
+        if few_shot_samples_per_class:
+            original_img_cnt = len(manifest.images)
+            manifest = manifest.sample_few_shot_subset(few_shot_samples_per_class, rnd_seed)
+            logger.info(f'Create a few-shot dataset with n samples per class = {few_shot_samples_per_class}. # images: {original_img_cnt} => {len(manifest.images)}')
+
+        return manifest, dataset_info, downloader_resources
+
+    def list_data_version_and_types(self):
+        """List all dataset names, versions and types
+        """
+
+        return self.dataset_registry.list_data_version_and_types()
```

### Comparing `vision_datasets-0.2.9/vision_datasets.egg-info/PKG-INFO` & `vision_datasets-1.0.0/vision_datasets.egg-info/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,159 +1,181 @@
-Metadata-Version: 2.1
-Name: vision-datasets
-Version: 0.2.9
-Summary: A utility repo for vision dataset access and management.
-Home-page: https://github.com/microsoft/vision-datasets
-Author: Ping Jin, Shohei Ono
-License: MIT
-Description: # Vision Datasets
-        
-        ## Introduction
-        
-        This repo
-        
-        - defines unified contract for dataset for purposes such as training, visualization, and exploration, via `DatasetManifest` and `ImageDataManifest`.
-        - provides API for organizing and accessing datasets, via `DatasetHub`
-        
-        Currently, five `basic` types of data are supported: 
-        - `classification_multiclass`: each image can is only with one label.
-        - `classification_multilabel`: each image can is with one or multiple labels (e.g., 'cat', 'animal', 'pet').
-        - `object_detection`: each image is labeled with bounding boxes surrounding the objects of interest.
-        - `image_caption`: each image is labeled with a few texts describing the images.
-        - `image_text_matching`: each image is associated with a collection of texts describing the image, and whether each text description matches the image or not
-        
-        `multitask` type is a composition type, where one set of images has multiple sets of annotations available for different tasks, where each task can be of any basic type.
-        
-        
-        ## Dataset Contracts
-        
-        - `DatasetManifest` wraps the information about a dataset including labelmap, images (width, height, path to image), and annotations. `ImageDataManifest` encapsulates information about each image.
-        - `ImageDataManifest` encapsulates image-specific information, such as image id, path, labels, and width/height. One thing to note here is that the image path can be
-            1. a local path (absolute `c:\images\1.jpg` or relative `images\1.jpg`)
-            2. a local path in a **non-compressed** zip file (absolute `c:\images.zip@1.jpg` or relative `images.zip@1.jpg`) or
-            3. an url
-        - `ManifestDataset` is an iterable dataset class that consumes the information from `DatasetManifest`.
-        
-        `ManifestDataset` is able to load the data from all three kinds of paths. Both 1. and 2. are good for training, as they access data from local disk while the 3rd one is good for data exploration, if you have the data in azure storage.
-        
-        For `multitask` dataset, the labels stored in the `ImageDataManifest` is a `dict` mapping from task name to that task's labels. The labelmap stored in `DatasetManifest` is also a `dict` mapping from task name to that task's labels.
-        
-        ### Creating DatasetManifest
-        
-        In addition to loading a serialized `DatasetManifest` for instantiation, this repo currently supports two formats of data that can instantiates `DatasetManifest`,
-        using `DatasetManifest.create_dataset_manifest(dataset_info, usage, container_sas_or_root_dir)`: `COCO` and `IRIS` (legacy).
-        
-        `DatasetInfo` as the first arg in the arg list wraps the metainfo about the dataset like the name of the dataset, locations of the images, annotation files, etc. See examples in the sections below
-        for different data formats.
-        
-        Once a `DatasetManifest` is created, you can create a `ManifestDataset` for accessing the data in the dataset, especially the image data, for training, visualization, etc:
-        
-        ```{python}
-        dataset = ManifestDataset(dataset_info, dataset_manifest, coordinates='relative')
-        ```
-        
-        #### Coco format
-        
-        Here is an example with explanation of what a `DatasetInfo` looks like for coco format, when it is serialized into json:
-        
-        ```{json}
-            {
-                "name": "sampled-ms-coco",
-                "version": 1,
-                "description": "A sampled ms-coco dataset.",
-                "type": "object_detection",
-                "format": "coco", // indicating the annotation data are stored in coco format
-                "root_folder": "detection/coco2017_20200401", // a root folder for all files listed
-                "train": {
-                    "index_path": "train.json", // coco json file for training, see next section for example
-                    "files_for_local_usage": [ // associated files including data such as images
-                        "images/train_images.zip"
-                    ]
-                },
-                "val": {
-                    "index_path": "val.json",
-                    "files_for_local_usage": [
-                        "images/val_images.zip"
-                    ]
-                },
-                "test": {
-                    "index_path": "test.json",
-                    "files_for_local_usage": [
-                        "images/test_images.zip"
-                    ]
-                }
-            }
-        ```
-        
-        Coco annotation format details w.r.t. `multiclass/label_classification`, `object_detection`, `image_caption`, `image_text_match` and `multitask`  can be found in `COCO_DATA_FORMAT.md`.
-        
-        
-        #### Iris format
-        
-        Iris format is a legacy format which can be found in `IRIS_DATA_FORMAT.md`. Only `multiclass/label_classification`, `object_detection` and `multitask` are supported.
-        
-        ## Dataset management and access
-        
-        Once you have multiple datasets, it is more convenient to have all the `DatasetInfo` in one place and instantiate `DatasetManifest` or even `ManifestDataset` by just using the dataset name, usage (
-        train, val ,test) and version.
-        
-        This repo offers the class `DatasetHub` for this purpose. Once instantiated with a json including the `DatasetInfo` for all datasets, you can retrieve a `ManifestDataset` by
-        
-        ```{python}
-        import pathlib
-        
-        dataset_infos_json_path = 'datasets.json'
-        dataset_hub = DatasetHub(pathlib.Path(dataset_infos_json_path).read_text())
-        stanford_cars = dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage='train')
-        
-        # note that you can pass multiple datasets.json to DatasetHub, it can combine them all
-        # example: DatasetHub([ds_json1, ds_json2, ...])
-        # note that you can specify multiple usages in create_manifest_dataset call
-        # example dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=['train', 'val'])
-        
-        for img, targets, sample_idx_str in stanford_cars:
-            img.show()
-            img.close()
-            print(targets)
-        ```
-        
-        Note that this hub class works with data saved in both Azure Blob container and on local disk.
-        
-        If `local_dir`:
-        
-        1. is provided, the hub will look for the resources locally and **download the data** (files included in "
-           files_for_local_usage", the index files, metadata (if iris format), labelmap (if iris format))
-           from `blob_container_sas` if not present locally
-        2. is NOT provided (i.e. `None`), the hub will create a manifest dataset that directly consumes data from the blob
-           indicated by `blob_container_sas`. Note that this does not work, if data are stored in zipped files. You will have to
-           unzip your data in the azure blob. (Index files requires no update, if image paths are for zip files: "a.zip@1.jpg").
-           This kind of azure-based dataset is good for large dataset exploration, but can be slow for training.
-        
-        When data exists on local disk, `blob_container_sas` can be `None`.
-        
-        ### Training with PyTorch
-        
-        Training with PyTorch is easy. After instantiating a `ManifestDataset`, simply passing it in `vision_datasets.pytorch.torch_dataset.TorchDataset` together with the `transform`, then you are good to go with the PyTorch DataLoader for training.
-        
-        ### Managing datasets with DatasetHub on cloud storage
-        
-        If you are using `DatasetHub` to manage datasets in cloud storage, we recommend zipping (with uncompressed mode) the images into one or multiple zip files before uploading it and update the file path in index files to be like `train.zip@1.jpg` from `train\1.jpg`. You can do it with `7zip` (set compression level to 'store') on Windows or [zip](https://superuser.com/questions/411394/zip-files-without-compression) command on Linux.
-        
-        If you upload folders of images directly to cloud storage:
-        
-        - you will need to list all images in `"files_for_local_usage"`, which can be millions of entries
-        - downloading images one by one (even with multithreading) is much slower than downloading a few zip files
-        
-        One more thing is that sometimes when you create a zip file `train.zip`, you might find out that there is only one `train` folder in the zip. This will fail the file loading if the path is `train.zip@1.jpg`, as the image is actually at `train.zip@train\1.jpg`. It is ok to have this extra layer but please make sure the path is correct.
-        
-Keywords: vision datasets classification detection
-Platform: UNKNOWN
-Classifier: Development Status :: 4 - Beta
-Classifier: Intended Audience :: Developers
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python :: 3.6
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Requires-Python: >=3.6
-Description-Content-Type: text/markdown
-Provides-Extra: run
+Metadata-Version: 2.1
+Name: vision-datasets
+Version: 1.0.0
+Summary: A utility repo for vision dataset access and management.
+Home-page: https://github.com/microsoft/vision-datasets
+Author: Ping Jin, Shohei Ono
+License: MIT
+Keywords: vision datasets classification detection
+Classifier: Development Status :: 4 - Beta
+Classifier: Intended Audience :: Developers
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Requires-Python: >=3.8
+Description-Content-Type: text/markdown
+Provides-Extra: run
+License-File: LICENSE
+
+# Vision Datasets
+
+## Introduction
+
+This repo
+
+- defines unified contract for dataset for purposes such as training, visualization, and exploration, via `DatasetManifest`, `ImageDataManifest`, etc.
+- provides many commonly used dataset operation, such as sample dataset by categories, sample few-shot sub-dataset, sample dataset by ratios, train-test split, merge dataset, etc. (See [Here](#oom))
+- provides API for organizing and accessing datasets, via `DatasetHub`
+
+Currently, seven `basic` types of data are supported:
+
+- `image_classification_multiclass`: each image can is only with one label.
+- `image_classification_multilabel`: each image can is with one or multiple labels (e.g., 'cat', 'animal', 'pet').
+- `image_object_detection`: each image is labeled with bounding boxes surrounding the objects of interest.
+- `image_text_matching`: each image is associated with a collection of texts describing the image, and whether each text description matches the image or not.
+- `image_matting`: each image has a pixel-wise annotation, where each pixel is labeled as 'foreground' or 'background'.
+- `image_regression`: each image is labeled with a real-valued numeric regression target.
+- `image_caption`: each image is labeled with a few texts describing the images.
+- `text_2_image_retrieval`: each image is labeled with a number of text queries describing the image. Optionally, an image is associated with one label.
+
+`multitask` type is a composition type, where one set of images has multiple sets of annotations available for different tasks, where each task can be of any basic type.
+
+**Note that `image_caption` and `text_2_image_retrieval` might be merged into `image_text_matching` in future.**
+
+## Dataset Contracts
+
+- `DatasetManifest` wraps the information about a dataset including labelmap, images (width, height, path to image), and annotations. `ImageDataManifest` encapsulates information about each image.
+- `ImageDataManifest` encapsulates image-specific information, such as image id, path, labels, and width/height. One thing to note here is that the image path can be
+    1. a local path (absolute `c:\images\1.jpg` or relative `images\1.jpg`)
+    2. a local path in a **non-compressed** zip file (absolute `c:\images.zip@1.jpg` or relative `images.zip@1.jpg`) or
+    3. an url
+- `ImageLabelManifest`: encapsulates one single image-level annotation
+- `CategoryManifest`: encapsulates the information about a category, such as its name and super category, if applicable
+- `VisionDataset` is an iterable dataset class that consumes the information from `DatasetManifest`.
+
+`VisionDataset` is able to load the data from all three kinds of paths. Both 1. and 2. are good for training, as they access data from local disk while the 3rd one is good for data exploration, if you have the data in azure storage.
+
+For `multitask` dataset, the labels stored in the `ImageDataManifest` is a `dict` mapping from task name to that task's labels. The labelmap stored in `DatasetManifest` is also a `dict` mapping from task name to that task's labels.
+
+### Creating DatasetManifest
+
+In addition to loading a serialized `DatasetManifest` for instantiation, this repo currently supports two formats of data that can instantiates `DatasetManifest`,
+using `DatasetManifest.create_dataset_manifest(dataset_info, usage, container_sas_or_root_dir)`: `COCO` and `IRIS` (legacy).
+
+`DatasetInfo` as the first arg in the arg list wraps the metainfo about the dataset like the name of the dataset, locations of the images, annotation files, etc. See examples in the sections below
+for different data formats.
+
+Once a `DatasetManifest` is created, you can create a `VisionDataset` for accessing the data in the dataset, especially the image data, for training, visualization, etc:
+
+```{python}
+dataset = VisionDataset(dataset_info, dataset_manifest, coordinates='relative')
+```
+
+#### Coco format
+
+Here is an example with explanation of what a `DatasetInfo` looks like for coco format, when it is serialized into json:
+
+```json
+    {
+        "name": "sampled-ms-coco",
+        "version": 1,
+        "description": "A sampled ms-coco dataset.",
+        "type": "object_detection",
+        "format": "coco", // indicating the annotation data are stored in coco format
+        "root_folder": "detection/coco2017_20200401", // a root folder for all files listed
+        "train": {
+            "index_path": "train.json", // coco json file for training, see next section for example
+            "files_for_local_usage": [ // associated files including data such as images
+                "images/train_images.zip"
+            ]
+        },
+        "val": {
+            "index_path": "val.json",
+            "files_for_local_usage": [
+                "images/val_images.zip"
+            ]
+        },
+        "test": {
+            "index_path": "test.json",
+            "files_for_local_usage": [
+                "images/test_images.zip"
+            ]
+        }
+    }
+```
+
+Coco annotation format details w.r.t. `image_classification_multiclass/label`, `image_object_detection`, `image_caption`, `image_text_match` and `multitask`  can be found in `COCO_DATA_FORMAT.md`.
+
+Index file can be put into a zip file as well (e.g., `annotations.zip@train.json`), no need to add the this zip to "files_for_local_usage" explicitly.
+
+#### Iris format
+
+Iris format is a legacy format which can be found in `IRIS_DATA_FORMAT.md`. Only `multiclass/label_classification`, `object_detection` and `multitask` are supported.
+
+## Dataset management and access
+
+Check [DATA_PREPARATION.md](DATA_PREPARATION.md) for complete guide on how to prepare datasets in steps.
+
+Once you have multiple datasets, it is more convenient to have all the `DatasetInfo` in one place and instantiate `DatasetManifest` or even `VisionDataset` by just using the dataset name, usage (
+train, val ,test) and version.
+
+This repo offers the class `DatasetHub` for this purpose. Once instantiated with a json including the `DatasetInfo` for all datasets, you can retrieve a `VisionDataset` by
+
+```python
+import pathlib
+from vision_datasets.common import Usages, DatasetHub
+
+dataset_infos_json_path = 'datasets.json'
+dataset_hub = DatasetHub(pathlib.Path(dataset_infos_json_path).read_text())
+stanford_cars = dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=Usages.TRAIN)
+
+# note that you can pass multiple datasets.json to DatasetHub, it can combine them all
+# example: DatasetHub([ds_json1, ds_json2, ...])
+# note that you can specify multiple usages in create_manifest_dataset call
+# example dataset_hub.create_manifest_dataset(blob_container_sas, local_dir, 'stanford-cars', version=1, usage=[Usages.TRAIN, Usages.VAL])
+
+for img, targets, sample_idx_str in stanford_cars:
+    img.show()
+    img.close()
+    print(targets)
+```
+
+Note that this hub class works with data saved in both Azure Blob container and on local disk.
+
+If `local_dir`:
+
+1. is provided, the hub will look for the resources locally and **download the data** (files included in "
+   files_for_local_usage", the index files, metadata (if iris format), labelmap (if iris format))
+   from `blob_container_sas` if not present locally
+2. is NOT provided (i.e. `None`), the hub will create a manifest dataset that directly consumes data from the blob
+   indicated by `blob_container_sas`. Note that this does not work, if data are stored in zipped files. You will have to
+   unzip your data in the azure blob. (Index files requires no update, if image paths are for zip files: `a.zip@1.jpg`).
+   This kind of azure-based dataset is good for large dataset exploration, but can be slow for training.
+
+When data exists on local disk, `blob_container_sas` can be `None`.
+
+## Operations on manifests {#oom}
+
+There are supported operations on manifests for different data types, such as split, merge, sample, etc. You can run
+
+`vision_list_supported_operations -d {DATA_TYPE}`
+
+to see the supported operations for a specific data type. You can use the factory classes in `vision_datasets.common.factory` to create operations for certain data type.
+
+```python
+from vision_datasets.common import DatasetTypes, SplitFactory, SplitConfig
+
+
+data_manifest = ....
+splitter = SplitFactory.create(DatasetTypes.IMAGE_CLASSIFICATION_MULTICLASS, SplitConfig(ratio=0.3))
+manifest_1, manifest_2 = splitter.run(data_manifest)
+```
+
+### Training with PyTorch
+
+Training with PyTorch is easy. After instantiating a `VisionDataset`, simply passing it in `vision_datasets.common.dataset.TorchDataset` together with the `transform`, then you are good to go with the PyTorch DataLoader for training.
+
+
+## Helpful commands
+
+There are a few commands that come with this repo once installed, such as datset check and download, detection conversion to classification dataset, and so on, check [`UTIL_COMMANDS.md`](./UTIL_COMMANDS.md) for details.
```

