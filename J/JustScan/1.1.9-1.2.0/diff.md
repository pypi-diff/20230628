# Comparing `tmp/JustScan-1.1.9.tar.gz` & `tmp/JustScan-1.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "JustScan-1.1.9.tar", last modified: Wed Jun 21 04:45:37 2023, max compression
+gzip compressed data, was "JustScan-1.2.0.tar", last modified: Wed Jun 28 10:15:52 2023, max compression
```

## Comparing `JustScan-1.1.9.tar` & `JustScan-1.2.0.tar`

### file list

```diff
@@ -1,180 +1,185 @@
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.681148 JustScan-1.1.9/
--rw-r--r--   0 macbook    (501) staff       (20)     2427 2023-06-21 04:45:37.680976 JustScan-1.1.9/PKG-INFO
--rw-r--r--   0 macbook    (501) staff       (20)     2131 2023-04-12 07:19:45.000000 JustScan-1.1.9/README.md
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.654690 JustScan-1.1.9/app/
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.659074 JustScan-1.1.9/app/JustScan/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 17:20:30.000000 JustScan-1.1.9/app/JustScan/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.660386 JustScan-1.1.9/app/JustScan/api/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 09:21:37.000000 JustScan-1.1.9/app/JustScan/api/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)      181 2023-06-20 10:57:02.000000 JustScan-1.1.9/app/JustScan/api/itc_cli.py
--rw-r--r--   0 macbook    (501) staff       (20)     5520 2023-06-20 17:06:38.000000 JustScan-1.1.9/app/JustScan/api/just_scan_api.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.661124 JustScan-1.1.9/app/JustScan/config/
--rw-r--r--   0 macbook    (501) staff       (20)      100 2023-06-20 07:14:31.000000 JustScan-1.1.9/app/JustScan/config/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     1546 2023-06-20 10:29:43.000000 JustScan-1.1.9/app/JustScan/config/config.py
--rw-r--r--   0 macbook    (501) staff       (20)      619 2023-06-20 10:30:42.000000 JustScan-1.1.9/app/JustScan/config/config_db.py
--rw-r--r--   0 macbook    (501) staff       (20)     1872 2023-06-20 10:31:25.000000 JustScan-1.1.9/app/JustScan/config/logger.py
--rw-r--r--   0 macbook    (501) staff       (20)     4337 2023-05-09 09:10:33.000000 JustScan-1.1.9/app/JustScan/config/pydantic_models.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.661735 JustScan-1.1.9/app/JustScan/database/
--rw-r--r--   0 macbook    (501) staff       (20)       71 2023-06-20 07:14:31.000000 JustScan-1.1.9/app/JustScan/database/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     4411 2023-06-21 02:51:05.000000 JustScan-1.1.9/app/JustScan/database/crud.py
--rw-r--r--   0 macbook    (501) staff       (20)      867 2023-06-20 10:35:51.000000 JustScan-1.1.9/app/JustScan/database/data_models.py
--rw-r--r--   0 macbook    (501) staff       (20)      570 2023-06-20 17:06:38.000000 JustScan-1.1.9/app/JustScan/database/database.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.661901 JustScan-1.1.9/app/JustScan/face_id/
--rw-r--r--   0 macbook    (501) staff       (20)       66 2023-06-20 07:09:37.000000 JustScan-1.1.9/app/JustScan/face_id/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.662202 JustScan-1.1.9/app/JustScan/face_id/commons/
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.663443 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/
--rw-r--r--   0 macbook    (501) staff       (20)     2206 2023-06-20 10:35:31.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/CDCN_config.py
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     2037 2023-06-20 10:35:31.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/anti_spoof.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.663993 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/data_io/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/data_io/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)    20275 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/data_io/functional.py
--rw-r--r--   0 macbook    (501) staff       (20)    11469 2023-06-21 02:49:42.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/data_io/transform.py
--rw-r--r--   0 macbook    (501) staff       (20)      802 2023-06-20 10:35:31.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/liveness_check.py
--rw-r--r--   0 macbook    (501) staff       (20)     1402 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/liveness_onnx_check.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.664488 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/model_lib/
--rw-r--r--   0 macbook    (501) staff       (20)    12487 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/model_lib/MiniFASNet.py
--rw-r--r--   0 macbook    (501) staff       (20)     2739 2023-06-20 16:58:59.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/model_lib/MultiFTNet.py
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/model_lib/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)      990 2023-06-20 10:35:31.000000 JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/utility.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.664825 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/
--rw-r--r--   0 macbook    (501) staff       (20)     3004 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/ArcFace_onnx.py
--rw-r--r--   0 macbook    (501) staff       (20)      983 2023-06-21 02:52:02.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.665529 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/
--rw-r--r--   0 macbook    (501) staff       (20)      213 2023-06-20 16:58:59.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     3036 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/layers.py
--rw-r--r--   0 macbook    (501) staff       (20)     4293 2023-06-20 16:58:59.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/models.py
--rw-r--r--   0 macbook    (501) staff       (20)     2436 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/utils.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.666077 JustScan-1.1.9/app/JustScan/face_id/commons/CloseEyes/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/CloseEyes/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     1104 2023-06-20 17:27:59.000000 JustScan-1.1.9/app/JustScan/face_id/commons/CloseEyes/close_eyes_v2.py
--rw-r--r--   0 macbook    (501) staff       (20)     1315 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/face_id/commons/CloseEyes/utils.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.666474 JustScan-1.1.9/app/JustScan/face_id/commons/FaceMask/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/FaceMask/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)      812 2023-06-20 17:27:59.000000 JustScan-1.1.9/app/JustScan/face_id/commons/FaceMask/face_mask_onnx.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.667058 JustScan-1.1.9/app/JustScan/face_id/commons/FaceQuality/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/FaceQuality/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     9974 2023-06-01 06:55:11.000000 JustScan-1.1.9/app/JustScan/face_id/commons/FaceQuality/dom.py
--rw-r--r--   0 macbook    (501) staff       (20)     1855 2023-06-20 08:14:55.000000 JustScan-1.1.9/app/JustScan/face_id/commons/FaceQuality/face_quality_assessment.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.667439 JustScan-1.1.9/app/JustScan/face_id/commons/ScrFd/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ScrFd/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)    12632 2023-06-01 06:55:11.000000 JustScan-1.1.9/app/JustScan/face_id/commons/ScrFd/scrfd.py
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.1.9/app/JustScan/face_id/commons/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     2297 2023-06-19 18:18:48.000000 JustScan-1.1.9/app/JustScan/face_id/commons/config.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.668352 JustScan-1.1.9/app/JustScan/face_id/libraries/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.1.9/app/JustScan/face_id/libraries/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     7235 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/face_id/libraries/face_detection.py
--rw-r--r--   0 macbook    (501) staff       (20)     5325 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/face_id/libraries/face_id.py
--rw-r--r--   0 macbook    (501) staff       (20)      395 2023-06-20 08:01:32.000000 JustScan-1.1.9/app/JustScan/face_id/libraries/face_recognition.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.668820 JustScan-1.1.9/app/JustScan/face_id/tools/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.1.9/app/JustScan/face_id/tools/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     3955 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/face_id/tools/modules.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.669030 JustScan-1.1.9/app/JustScan/ocr/
--rw-r--r--   0 macbook    (501) staff       (20)       19 2023-06-20 07:08:18.000000 JustScan-1.1.9/app/JustScan/ocr/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.669247 JustScan-1.1.9/app/JustScan/ocr/core/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 07:27:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.670391 JustScan-1.1.9/app/JustScan/ocr/core/commons/
--rw-r--r--   0 macbook    (501) staff       (20)      814 2023-06-20 08:24:37.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/SpoofingNID.py
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     5592 2023-06-20 08:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/config.py
--rw-r--r--   0 macbook    (501) staff       (20)      780 2023-05-30 04:20:28.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/id_card_classification.py
--rw-r--r--   0 macbook    (501) staff       (20)     5675 2023-06-20 10:04:38.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/id_card_onnx.py
--rw-r--r--   0 macbook    (501) staff       (20)     1761 2023-06-20 08:22:16.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/merge_model.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.670736 JustScan-1.1.9/app/JustScan/ocr/core/commons/utils/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 07:28:07.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/utils/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     2513 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/commons/utils/utils_onnx.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.670899 JustScan-1.1.9/app/JustScan/ocr/core/modules/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.671346 JustScan-1.1.9/app/JustScan/ocr/core/modules/corner_detection/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/corner_detection/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     1145 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/corner_detection/id_card_aligment.py
--rw-r--r--   0 macbook    (501) staff       (20)     3973 2023-06-19 14:29:56.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/corner_detection/utils.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.671638 JustScan-1.1.9/app/JustScan/ocr/core/modules/id_card_classification/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/id_card_classification/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)      923 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/id_card_classification/classify.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.672078 JustScan-1.1.9/app/JustScan/ocr/core/modules/mrc/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/mrc/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     2938 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/mrc/mrc_detection.py
--rw-r--r--   0 macbook    (501) staff       (20)      627 2023-06-20 08:24:11.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/mrc/utils.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.672707 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-18 03:26:14.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     9072 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/passport.py
--rw-r--r--   0 macbook    (501) staff       (20)      510 2023-06-20 08:24:11.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/passport_detection.py
--rw-r--r--   0 macbook    (501) staff       (20)     2288 2023-06-20 08:30:21.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.673150 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_align_passport/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-18 03:26:14.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_align_passport/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     3248 2023-04-18 08:29:08.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_align_passport/passport_utils.py
--rw-r--r--   0 macbook    (501) staff       (20)     4344 2023-04-18 03:26:14.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_align_passport/utils_align.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.673430 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_detect_passport/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-18 03:26:14.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_detect_passport/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     9668 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_detect_passport/utils_detect.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.673717 JustScan-1.1.9/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-26 09:38:30.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     2936 2023-06-21 02:53:49.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/nid_quality_liveness_check.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.674002 JustScan-1.1.9/app/JustScan/ocr/core/modules/spell_checking/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/spell_checking/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     2350 2023-05-10 09:12:33.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/spell_checking/corrector_v2.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.674283 JustScan-1.1.9/app/JustScan/ocr/core/modules/spoofing_nid/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/spoofing_nid/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)      935 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/spoofing_nid/spoofing.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.674721 JustScan-1.1.9/app/JustScan/ocr/core/modules/text_detection/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/text_detection/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     7020 2023-06-20 08:33:20.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/text_detection/dictionary.py
--rw-r--r--   0 macbook    (501) staff       (20)    11602 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/text_detection/utils.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.675014 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     2511 2023-06-20 08:34:11.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/nlp_onnx.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.675624 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.676266 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     1735 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/aug.py
--rw-r--r--   0 macbook    (501) staff       (20)     6278 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader.py
--rw-r--r--   0 macbook    (501) staff       (20)     5021 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader_v1.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.677027 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/__init__.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.677643 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)      804 2023-06-20 08:38:07.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/cnn.py
--rw-r--r--   0 macbook    (501) staff       (20)     5311 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/resnet.py
--rw-r--r--   0 macbook    (501) staff       (20)     1655 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/vgg.py
--rw-r--r--   0 macbook    (501) staff       (20)     3777 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/beam.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.678246 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)    11634 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/convseq2seq.py
--rw-r--r--   0 macbook    (501) staff       (20)     5731 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/seq2seq.py
--rw-r--r--   0 macbook    (501) staff       (20)     4858 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/transformer.py
--rw-r--r--   0 macbook    (501) staff       (20)    13524 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/trainer.py
--rw-r--r--   0 macbook    (501) staff       (20)     1630 2023-06-20 08:38:07.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/transformerocr.py
--rw-r--r--   0 macbook    (501) staff       (20)      924 2023-05-10 09:12:33.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/vocab.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.678708 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     1006 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/labelsmoothingloss.py
--rw-r--r--   0 macbook    (501) staff       (20)     1798 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/optim.py
--rw-r--r--   0 macbook    (501) staff       (20)      538 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/predict.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.679015 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     1039 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/utest.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.680106 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     1216 2023-06-20 08:39:08.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/config.py
--rw-r--r--   0 macbook    (501) staff       (20)     2754 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/create_dataset.py
--rw-r--r--   0 macbook    (501) staff       (20)      325 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/logger.py
--rw-r--r--   0 macbook    (501) staff       (20)     1445 2023-06-20 16:58:59.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/predictor.py
--rw-r--r--   0 macbook    (501) staff       (20)     7313 2023-06-20 08:38:07.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/translate.py
--rw-r--r--   0 macbook    (501) staff       (20)     2688 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/utils.py
--rw-r--r--   0 macbook    (501) staff       (20)      559 2023-04-12 07:19:46.000000 JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/train.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.680727 JustScan-1.1.9/app/JustScan/ocr/core/tools/
--rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.1.9/app/JustScan/ocr/core/tools/__init__.py
--rw-r--r--   0 macbook    (501) staff       (20)     5552 2023-04-18 03:26:14.000000 JustScan-1.1.9/app/JustScan/ocr/core/tools/api_json.py
--rw-r--r--   0 macbook    (501) staff       (20)     5533 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/tools/dictionaries.py
--rw-r--r--   0 macbook    (501) staff       (20)     2518 2023-06-20 17:16:54.000000 JustScan-1.1.9/app/JustScan/ocr/core/tools/functional.py
-drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-21 04:45:37.659966 JustScan-1.1.9/app/JustScan.egg-info/
--rw-r--r--   0 macbook    (501) staff       (20)     2427 2023-06-21 04:45:37.000000 JustScan-1.1.9/app/JustScan.egg-info/PKG-INFO
--rw-r--r--   0 macbook    (501) staff       (20)     7220 2023-06-21 04:45:37.000000 JustScan-1.1.9/app/JustScan.egg-info/SOURCES.txt
--rw-r--r--   0 macbook    (501) staff       (20)        1 2023-06-21 04:45:37.000000 JustScan-1.1.9/app/JustScan.egg-info/dependency_links.txt
--rw-r--r--   0 macbook    (501) staff       (20)       66 2023-06-21 04:45:37.000000 JustScan-1.1.9/app/JustScan.egg-info/entry_points.txt
--rw-r--r--   0 macbook    (501) staff       (20)      864 2023-06-21 04:45:37.000000 JustScan-1.1.9/app/JustScan.egg-info/requires.txt
--rw-r--r--   0 macbook    (501) staff       (20)        9 2023-06-21 04:45:37.000000 JustScan-1.1.9/app/JustScan.egg-info/top_level.txt
--rw-r--r--   0 macbook    (501) staff       (20)       38 2023-06-21 04:45:37.681221 JustScan-1.1.9/setup.cfg
--rw-r--r--   0 macbook    (501) staff       (20)     1179 2023-06-21 04:42:05.000000 JustScan-1.1.9/setup.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.914670 JustScan-1.2.0/
+-rw-r--r--   0 macbook    (501) staff       (20)     2433 2023-06-28 10:15:52.914502 JustScan-1.2.0/PKG-INFO
+-rw-r--r--   0 macbook    (501) staff       (20)     2131 2023-04-12 07:19:45.000000 JustScan-1.2.0/README.md
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.886718 JustScan-1.2.0/app/
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.891559 JustScan-1.2.0/app/JustScan/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 17:20:30.000000 JustScan-1.2.0/app/JustScan/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.893164 JustScan-1.2.0/app/JustScan/api/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 09:21:37.000000 JustScan-1.2.0/app/JustScan/api/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)      179 2023-06-23 11:19:25.000000 JustScan-1.2.0/app/JustScan/api/itc_cli.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5520 2023-06-20 17:06:38.000000 JustScan-1.2.0/app/JustScan/api/just_scan_api.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.894046 JustScan-1.2.0/app/JustScan/config/
+-rw-r--r--   0 macbook    (501) staff       (20)      100 2023-06-20 07:14:31.000000 JustScan-1.2.0/app/JustScan/config/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1546 2023-06-20 10:29:43.000000 JustScan-1.2.0/app/JustScan/config/config.py
+-rw-r--r--   0 macbook    (501) staff       (20)      619 2023-06-20 10:30:42.000000 JustScan-1.2.0/app/JustScan/config/config_db.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1872 2023-06-20 10:31:25.000000 JustScan-1.2.0/app/JustScan/config/logger.py
+-rw-r--r--   0 macbook    (501) staff       (20)     4337 2023-05-09 09:10:33.000000 JustScan-1.2.0/app/JustScan/config/pydantic_models.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.894780 JustScan-1.2.0/app/JustScan/database/
+-rw-r--r--   0 macbook    (501) staff       (20)       71 2023-06-20 07:14:31.000000 JustScan-1.2.0/app/JustScan/database/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     4411 2023-06-21 02:51:05.000000 JustScan-1.2.0/app/JustScan/database/crud.py
+-rw-r--r--   0 macbook    (501) staff       (20)      867 2023-06-20 10:35:51.000000 JustScan-1.2.0/app/JustScan/database/data_models.py
+-rw-r--r--   0 macbook    (501) staff       (20)      570 2023-06-20 17:06:38.000000 JustScan-1.2.0/app/JustScan/database/database.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.894971 JustScan-1.2.0/app/JustScan/face_id/
+-rw-r--r--   0 macbook    (501) staff       (20)       66 2023-06-20 07:09:37.000000 JustScan-1.2.0/app/JustScan/face_id/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.895298 JustScan-1.2.0/app/JustScan/face_id/commons/
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.896413 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/
+-rw-r--r--   0 macbook    (501) staff       (20)     2206 2023-06-20 10:35:31.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/CDCN_config.py
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2037 2023-06-20 10:35:31.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/anti_spoof.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.897183 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/data_io/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/data_io/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)    20275 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/data_io/functional.py
+-rw-r--r--   0 macbook    (501) staff       (20)    11469 2023-06-21 02:49:42.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/data_io/transform.py
+-rw-r--r--   0 macbook    (501) staff       (20)      802 2023-06-20 10:35:31.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/liveness_check.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1402 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/liveness_onnx_check.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.897896 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/model_lib/
+-rw-r--r--   0 macbook    (501) staff       (20)    12487 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/model_lib/MiniFASNet.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2739 2023-06-20 16:58:59.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/model_lib/MultiFTNet.py
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/model_lib/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)      990 2023-06-20 10:35:31.000000 JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/utility.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.898243 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/
+-rw-r--r--   0 macbook    (501) staff       (20)     3030 2023-06-23 10:15:59.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/ArcFace_onnx.py
+-rw-r--r--   0 macbook    (501) staff       (20)      983 2023-06-21 02:52:02.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.899016 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/
+-rw-r--r--   0 macbook    (501) staff       (20)      213 2023-06-20 16:58:59.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     3036 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/layers.py
+-rw-r--r--   0 macbook    (501) staff       (20)     4293 2023-06-20 16:58:59.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/models.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2436 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/utils.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.899620 JustScan-1.2.0/app/JustScan/face_id/commons/CloseEyes/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/CloseEyes/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1165 2023-06-23 10:15:59.000000 JustScan-1.2.0/app/JustScan/face_id/commons/CloseEyes/close_eyes_v2.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1315 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/face_id/commons/CloseEyes/utils.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.900010 JustScan-1.2.0/app/JustScan/face_id/commons/FaceMask/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/FaceMask/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)      873 2023-06-23 10:15:59.000000 JustScan-1.2.0/app/JustScan/face_id/commons/FaceMask/face_mask_onnx.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.900580 JustScan-1.2.0/app/JustScan/face_id/commons/FaceQuality/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/FaceQuality/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     9974 2023-06-01 06:55:11.000000 JustScan-1.2.0/app/JustScan/face_id/commons/FaceQuality/dom.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1855 2023-06-20 08:14:55.000000 JustScan-1.2.0/app/JustScan/face_id/commons/FaceQuality/face_quality_assessment.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.900936 JustScan-1.2.0/app/JustScan/face_id/commons/ScrFd/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:45.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ScrFd/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)    12656 2023-06-23 10:15:59.000000 JustScan-1.2.0/app/JustScan/face_id/commons/ScrFd/scrfd.py
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.2.0/app/JustScan/face_id/commons/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2297 2023-06-19 18:18:48.000000 JustScan-1.2.0/app/JustScan/face_id/commons/config.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.901701 JustScan-1.2.0/app/JustScan/face_id/libraries/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.2.0/app/JustScan/face_id/libraries/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     7235 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/face_id/libraries/face_detection.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5325 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/face_id/libraries/face_id.py
+-rw-r--r--   0 macbook    (501) staff       (20)      395 2023-06-20 08:01:32.000000 JustScan-1.2.0/app/JustScan/face_id/libraries/face_recognition.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.901984 JustScan-1.2.0/app/JustScan/face_id/tools/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.2.0/app/JustScan/face_id/tools/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     3955 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/face_id/tools/modules.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.902143 JustScan-1.2.0/app/JustScan/ocr/
+-rw-r--r--   0 macbook    (501) staff       (20)       19 2023-06-20 07:08:18.000000 JustScan-1.2.0/app/JustScan/ocr/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.902305 JustScan-1.2.0/app/JustScan/ocr/core/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 07:27:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.903329 JustScan-1.2.0/app/JustScan/ocr/core/commons/
+-rw-r--r--   0 macbook    (501) staff       (20)      851 2023-06-22 07:17:17.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/SpoofingNID.py
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     7951 2023-06-28 09:47:49.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/config.py
+-rw-r--r--   0 macbook    (501) staff       (20)      817 2023-06-22 07:17:17.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/id_card_classification.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5392 2023-06-28 10:15:34.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/id_card_onnx.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5573 2023-06-26 05:02:01.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/id_card_trt.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1651 2023-06-26 06:35:58.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/merge_model.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.903615 JustScan-1.2.0/app/JustScan/ocr/core/commons/utils/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 07:28:07.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/utils/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1887 2023-06-26 04:13:41.000000 JustScan-1.2.0/app/JustScan/ocr/core/commons/utils/utils_onnx.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.903780 JustScan-1.2.0/app/JustScan/ocr/core/modules/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.904188 JustScan-1.2.0/app/JustScan/ocr/core/modules/corner_detection/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/corner_detection/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1145 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/corner_detection/id_card_aligment.py
+-rw-r--r--   0 macbook    (501) staff       (20)     3973 2023-06-19 14:29:56.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/corner_detection/utils.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.904473 JustScan-1.2.0/app/JustScan/ocr/core/modules/id_card_classification/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/id_card_classification/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)      923 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/id_card_classification/classify.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.904907 JustScan-1.2.0/app/JustScan/ocr/core/modules/mrc/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/mrc/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2938 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/mrc/mrc_detection.py
+-rw-r--r--   0 macbook    (501) staff       (20)      627 2023-06-20 08:24:11.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/mrc/utils.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.905512 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-18 03:26:14.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     9072 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/passport.py
+-rw-r--r--   0 macbook    (501) staff       (20)      510 2023-06-20 08:24:11.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/passport_detection.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2288 2023-06-20 08:30:21.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.905960 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_align_passport/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-18 03:26:14.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_align_passport/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     3248 2023-04-18 08:29:08.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_align_passport/passport_utils.py
+-rw-r--r--   0 macbook    (501) staff       (20)     4344 2023-04-18 03:26:14.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_align_passport/utils_align.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.906261 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_detect_passport/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-18 03:26:14.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_detect_passport/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     9668 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_detect_passport/utils_detect.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.906571 JustScan-1.2.0/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-26 09:38:30.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2936 2023-06-21 02:53:49.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/nid_quality_liveness_check.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.906864 JustScan-1.2.0/app/JustScan/ocr/core/modules/spell_checking/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/spell_checking/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2350 2023-05-10 09:12:33.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/spell_checking/corrector_v2.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.907324 JustScan-1.2.0/app/JustScan/ocr/core/modules/spoofing_nid/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/spoofing_nid/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)      935 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/spoofing_nid/spoofing.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.907846 JustScan-1.2.0/app/JustScan/ocr/core/modules/text_detection/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/text_detection/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     7241 2023-06-28 09:47:49.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/text_detection/dictionary.py
+-rw-r--r--   0 macbook    (501) staff       (20)    11602 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/text_detection/utils.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.908311 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.908611 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/exe_backends/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-27 08:50:27.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/exe_backends/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     8899 2023-06-26 11:05:01.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/exe_backends/trt_loader.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2539 2023-06-27 09:39:17.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/nlp_onnx.py
+-rw-r--r--   0 macbook    (501) staff       (20)     3719 2023-06-27 09:48:38.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/nlp_trt.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.909063 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.909699 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1735 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/aug.py
+-rw-r--r--   0 macbook    (501) staff       (20)     6278 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5021 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader_v1.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.910602 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/__init__.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.911240 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)      804 2023-06-20 08:38:07.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/cnn.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5311 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/resnet.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1655 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/vgg.py
+-rw-r--r--   0 macbook    (501) staff       (20)     3777 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/beam.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.911881 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)    11634 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/convseq2seq.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5731 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/seq2seq.py
+-rw-r--r--   0 macbook    (501) staff       (20)     4858 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/transformer.py
+-rw-r--r--   0 macbook    (501) staff       (20)    13524 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/trainer.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1630 2023-06-20 08:38:07.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/transformerocr.py
+-rw-r--r--   0 macbook    (501) staff       (20)      924 2023-05-10 09:12:33.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/vocab.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.912317 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1006 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/labelsmoothingloss.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1798 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/optim.py
+-rw-r--r--   0 macbook    (501) staff       (20)      538 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/predict.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.912598 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1039 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/utest.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.913645 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1216 2023-06-20 08:39:08.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/config.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2754 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/create_dataset.py
+-rw-r--r--   0 macbook    (501) staff       (20)      325 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/logger.py
+-rw-r--r--   0 macbook    (501) staff       (20)     1445 2023-06-20 16:58:59.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/predictor.py
+-rw-r--r--   0 macbook    (501) staff       (20)     8785 2023-06-27 09:40:05.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/translate.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2690 2023-06-27 09:25:01.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/utils.py
+-rw-r--r--   0 macbook    (501) staff       (20)      559 2023-04-12 07:19:46.000000 JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/train.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.914260 JustScan-1.2.0/app/JustScan/ocr/core/tools/
+-rw-r--r--   0 macbook    (501) staff       (20)        0 2023-06-20 06:30:22.000000 JustScan-1.2.0/app/JustScan/ocr/core/tools/__init__.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5552 2023-04-18 03:26:14.000000 JustScan-1.2.0/app/JustScan/ocr/core/tools/api_json.py
+-rw-r--r--   0 macbook    (501) staff       (20)     5533 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/tools/dictionaries.py
+-rw-r--r--   0 macbook    (501) staff       (20)     2518 2023-06-20 17:16:54.000000 JustScan-1.2.0/app/JustScan/ocr/core/tools/functional.py
+drwxr-xr-x   0 macbook    (501) staff       (20)        0 2023-06-28 10:15:52.892653 JustScan-1.2.0/app/JustScan.egg-info/
+-rw-r--r--   0 macbook    (501) staff       (20)     2433 2023-06-28 10:15:52.000000 JustScan-1.2.0/app/JustScan.egg-info/PKG-INFO
+-rw-r--r--   0 macbook    (501) staff       (20)     7463 2023-06-28 10:15:52.000000 JustScan-1.2.0/app/JustScan.egg-info/SOURCES.txt
+-rw-r--r--   0 macbook    (501) staff       (20)        1 2023-06-28 10:15:52.000000 JustScan-1.2.0/app/JustScan.egg-info/dependency_links.txt
+-rw-r--r--   0 macbook    (501) staff       (20)       58 2023-06-28 10:15:52.000000 JustScan-1.2.0/app/JustScan.egg-info/entry_points.txt
+-rw-r--r--   0 macbook    (501) staff       (20)      865 2023-06-28 10:15:52.000000 JustScan-1.2.0/app/JustScan.egg-info/requires.txt
+-rw-r--r--   0 macbook    (501) staff       (20)        9 2023-06-28 10:15:52.000000 JustScan-1.2.0/app/JustScan.egg-info/top_level.txt
+-rw-r--r--   0 macbook    (501) staff       (20)       38 2023-06-28 10:15:52.914724 JustScan-1.2.0/setup.cfg
+-rw-r--r--   0 macbook    (501) staff       (20)     1178 2023-06-28 10:15:42.000000 JustScan-1.2.0/setup.py
```

### Comparing `JustScan-1.1.9/PKG-INFO` & `JustScan-1.2.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 Metadata-Version: 2.1
 Name: JustScan
-Version: 1.1.9
+Version: 1.2.0
 Summary: E-kyc for Industries application
-Home-page: https://github.com/aihackervn
+Home-page: https://gitlab.itcgroup.io/Theodore.vo
 Author: Theodore
-Author-email: tinprocoder0908@gmail.com
+Author-email: theodore.v@itcgroup.io
 License: MIT
 Keywords: ITC,AI,E-kyc,Deep Learning,Computer Vision,Yolov5,Interface
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.9
+Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 
 # EKYC (OCR&FaceID) API 
 <!-- [![My Skills](https://skills.thijs.gg/icons?i=python&theme=light)](https://skills.thijs.gg) -->
 EKYC (OCR&FaceID) API is an API developed to provide Optical Character Recognition (OCR) and Face ID functionalities. The API supports the scanning of national ID cards, motorbike registration certificates, and EVN bills. It utilizes Makesense AI for labeling data, Yolov5 for text detection, and VietOCR for text recognition.
```

### Comparing `JustScan-1.1.9/README.md` & `JustScan-1.2.0/README.md`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/api/just_scan_api.py` & `JustScan-1.2.0/app/JustScan/api/just_scan_api.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/config/config.py` & `JustScan-1.2.0/app/JustScan/config/config.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/config/config_db.py` & `JustScan-1.2.0/app/JustScan/config/config_db.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/config/logger.py` & `JustScan-1.2.0/app/JustScan/config/logger.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/config/pydantic_models.py` & `JustScan-1.2.0/app/JustScan/config/pydantic_models.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/database/crud.py` & `JustScan-1.2.0/app/JustScan/database/crud.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/database/data_models.py` & `JustScan-1.2.0/app/JustScan/database/data_models.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/database/database.py` & `JustScan-1.2.0/app/JustScan/database/database.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/CDCN_config.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/CDCN_config.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/anti_spoof.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/anti_spoof.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/data_io/functional.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/data_io/functional.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/data_io/transform.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/data_io/transform.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/liveness_check.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/liveness_check.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/liveness_onnx_check.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/liveness_onnx_check.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/model_lib/MiniFASNet.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/model_lib/MiniFASNet.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/model_lib/MultiFTNet.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/model_lib/MultiFTNet.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/AntiSpoof/utility.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/AntiSpoof/utility.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/ArcFace_onnx.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/ArcFace_onnx.py`

 * *Files 2% similar despite different names*

```diff
@@ -35,15 +35,15 @@
         else:
             input_mean = 127.5
             input_std = 127.5
         self.input_mean = input_mean
         self.input_std = input_std
         # print('input mean and std:', self.input_mean, self.input_std)
         if self.session is None:
-            self.session = onnxruntime.InferenceSession(self.model_file, providers=['CPUExecutionProvider'])
+            self.session = onnxruntime.InferenceSession(self.model_file, providers=['CUDAExecutionProvider', 'CPUExecutionProvider'])
         input_cfg = self.session.get_inputs()[0]
         input_shape = input_cfg.shape
         input_name = input_cfg.name
         self.input_size = tuple(input_shape[2:4][::-1])
         self.input_shape = input_shape
         outputs = self.session.get_outputs()
         output_names = []
@@ -52,15 +52,15 @@
         self.input_name = input_name
         self.output_names = output_names
         assert len(self.output_names) == 1
         self.output_shape = outputs[0].shape
 
     def prepare(self, ctx_id, **kwargs):
         if ctx_id < 0:
-            self.session.set_providers(['CPUExecutionProvider'])
+            self.session.set_providers(['CUDAExecutionProvider'])
 
     def get(self, img):
         embedding = self.get_feat(img).flatten()
         return embedding
 
     def compute_sim(self, feat1, feat2):
         from numpy.linalg import norm
```

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/__init__.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/__init__.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/layers.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/layers.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/models.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/models.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/ArcFace/lib/utils.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/ArcFace/lib/utils.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/CloseEyes/close_eyes_v2.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/CloseEyes/close_eyes_v2.py`

 * *Files 7% similar despite different names*

```diff
@@ -19,15 +19,15 @@
     return left_eyes, right_eyes
 
 
 class CloseEyes:
     def __init__(self, model_file=config['oce']):
         assert model_file is not None
         self.model_file = model_file
-        self.ort = onnxruntime.InferenceSession(self.model_file)
+        self.ort = onnxruntime.InferenceSession(self.model_file, providers=['CUDAExecutionProvider', 'CPUExecutionProvider'])
 
     def predict(self, image):
         img = preprocessing(image)
         inputs = self.ort.get_inputs()[0].name
         output_names = self.ort.get_outputs()[0].name
         net = self.ort.run([output_names], {inputs: img.astype('float32')})[0]
         ids = np.argmax(net)
```

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/CloseEyes/utils.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/CloseEyes/utils.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/FaceMask/face_mask_onnx.py` & `JustScan-1.2.0/app/JustScan/ocr/core/commons/SpoofingNID.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,25 +1,26 @@
-import onnxruntime
+from ..commons.config import config
 import numpy as np
 import cv2
-from JustScan.face_id.commons.config import config
+import onnxruntime
+
 
+def preprocessing(image):
+    # img = image[:,:,::-1]
+    img = cv2.resize(image, (224, 224))
+    return np.expand_dims(img, axis=0)
 
-class FaceMask:
-    def __init__(self, model_file=config['face_mask'], session=None):
+
+class SpoofingNIDModel:
+    def __init__(self, model_file=config['nid_spoofing'], session=None):
         assert model_file is not None
         self.model_file = model_file
-        self.session = session
+        self.ort = onnxruntime.InferenceSession(self.model_file, providers=["CUDAExecutionProvider"])
 
     def predict(self, image):
-        ort = onnxruntime.InferenceSession(self.model_file)
-        input = ort.get_inputs()[0].name
-        output = ort.get_outputs()
-        output_names = []
-        for out in output:
-            output_names.append(out.name)
-        img = cv2.resize(image, (224, 224))
-        img = np.expand_dims(img, axis=0)
-        net = ort.run(output_names, {input: img.astype('float32')})[0]
-        confidence = np.max(net[0])
-        ids = np.argmax(net[0])
-        return ids, confidence
+        img = preprocessing(image)
+        input = self.ort.get_inputs()[0].name
+        output_names = self.ort.get_outputs()[0].name
+        net = self.ort.run([output_names], {input: img.astype('float32')})[0]
+        return np.argmax(net), np.max(net[0])
+
+    # 0: back_cccd , 1: back_cmnd, 2:front_cccd , 3: front_cmnd
```

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/FaceQuality/dom.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/FaceQuality/dom.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/FaceQuality/face_quality_assessment.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/FaceQuality/face_quality_assessment.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/ScrFd/scrfd.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/ScrFd/scrfd.py`

 * *Files 1% similar despite different names*

```diff
@@ -67,15 +67,15 @@
         self.model_file = model_file
         self.session = session
         self.taskname = 'detection'
         self.batched = False
         if self.session is None:
             assert self.model_file is not None
             assert osp.exists(self.model_file)
-            self.session = onnxruntime.InferenceSession(self.model_file, providers=['CPUExecutionProvider'])
+            self.session = onnxruntime.InferenceSession(self.model_file, providers=['CUDAExecutionProvider','CPUExecutionProvider'])
         self.center_cache = {}
         self.nms_thresh = 0.4
         self.det_thresh = 0.5
         self._init_vars()
 
     def _init_vars(self):
         input_cfg = self.session.get_inputs()[0]
```

### Comparing `JustScan-1.1.9/app/JustScan/face_id/commons/config.py` & `JustScan-1.2.0/app/JustScan/face_id/commons/config.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/libraries/face_detection.py` & `JustScan-1.2.0/app/JustScan/face_id/libraries/face_detection.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/libraries/face_id.py` & `JustScan-1.2.0/app/JustScan/face_id/libraries/face_id.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/face_id/tools/modules.py` & `JustScan-1.2.0/app/JustScan/face_id/tools/modules.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/commons/SpoofingNID.py` & `JustScan-1.2.0/app/JustScan/ocr/core/commons/id_card_classification.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,26 +1,22 @@
-from ..commons.config import config
 import numpy as np
 import cv2
 import onnxruntime
 
 
 def preprocessing(image):
-    # img = image[:,:,::-1]
-    img = cv2.resize(image, (224, 224))
-    return np.expand_dims(img, axis=0)
+    return np.expand_dims(cv2.resize(image, (224, 224)), axis=0)
 
 
-class SpoofingNIDModel:
-    def __init__(self, model_file=config['nid_spoofing'], session=None):
+class idcardclassONNX:
+    def __init__(self, model_file='model.onnx', session=None):
         assert model_file is not None
         self.model_file = model_file
-        self.ort = onnxruntime.InferenceSession(self.model_file)
+        self.ort = onnxruntime.InferenceSession(self.model_file, providers=["CUDAExecutionProvider"])
 
     def predict(self, image):
-        img = preprocessing(image)
         input = self.ort.get_inputs()[0].name
         output_names = self.ort.get_outputs()[0].name
-        net = self.ort.run([output_names], {input: img.astype('float32')})[0]
-        return np.argmax(net), np.max(net[0])
+        return np.argmax(self.ort.run([output_names], {input: preprocessing(image).astype('float32')})[0]), \
+            np.max(self.ort.run([output_names], {input: preprocessing(image).astype('float32')})[0][0])
 
     # 0: back_cccd , 1: back_cmnd, 2:front_cccd , 3: front_cmnd
```

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/commons/id_card_onnx.py` & `JustScan-1.2.0/app/JustScan/ocr/core/commons/id_card_trt.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 import cv2
 import numpy as np
-import onnxruntime
+import onnx
 from .utils.utils_onnx import xywh2xyxy, nms, get_label
 
 
 class ID_CARD:
     def __init__(self, path, conf_thres=0.4, iou_thres=0.5, class_name=None, yolov5=False, official_nms=False):
         self.conf_threshold = conf_thres
         self.iou_threshold = iou_thres
@@ -13,16 +13,16 @@
         self.official_nms = official_nms
         self.initialize_model(path)
 
     def __call__(self, image):
         return self.detect_objects(image)
 
     def initialize_model(self, path):
-        self.session = onnxruntime.InferenceSession(path,
-                                                    providers=['CPUExecutionProvider'])
+        model = onnx.load(path)
+        self.engine = backend.prepare(model, device='CUDA:1')
         self.get_input_details()
         self.get_output_details()
         self.has_postprocess = 'score' in self.output_names or self.official_nms
 
     def detect_objects(self, image):
         input_tensor = self.prepare_input(image)
         # Perform inference on the image
@@ -41,15 +41,15 @@
                np.newaxis, :, :, :].astype(np.float32)
 
     def inference(self, input_tensor):
         # import time
         # start = time.perf_counter()
         # self.session.run(self.output_names, {self.input_names[0]: input_tensor})
         # print(f"Inference time: {(time.perf_counter() - start) * 1000:.2f} ms")
-        return self.session.run(self.output_names, {self.input_names[0]: input_tensor})
+        return self.engine.run(input_tensor)
 
     def process_output(self, output):
         if self.yolov5:
             predictions = np.squeeze(output[0])
             obj_conf = predictions[:, 4]
             mask = obj_conf > self.conf_threshold
             predictions = predictions[mask]
```

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/commons/utils/utils_onnx.py` & `JustScan-1.2.0/app/JustScan/ocr/core/commons/utils/utils_onnx.py`

 * *Files 20% similar despite different names*

```diff
@@ -36,27 +36,14 @@
     y[..., 0] = x[..., 0] - x[..., 2] / 2
     y[..., 1] = x[..., 1] - x[..., 3] / 2
     y[..., 2] = x[..., 0] + x[..., 2] / 2
     y[..., 3] = x[..., 1] + x[..., 3] / 2
     return y
 
 
-# def get_label(scores, class_ids, class_names):
-#     try:
-#         return pd.DataFrame({
-#             'class_name': np.array(class_names)[class_ids.astype(int)],
-#             'confidence': scores.astype(float),
-#             'class_id': class_ids.astype(int)
-#         })
-#     except:
-#         logging.error(f'error at running {get_label.__name__}, Low-quality image. Please try again')
-#         raise HTTPException(status_code=400,
-#                             detail={'status': 400, 'code': 'IMAGE_QUALITY_NOT_GOOD_EXCEPTION',
-#                                     'error': 'Low-quality image. Please try again'})
-
 def get_label(scores, class_ids, class_names):
     try:
         return np.column_stack((
             np.array(class_names)[class_ids.astype(int)],
             scores.astype(float),
             class_ids.astype(int)
         ))
```

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/corner_detection/id_card_aligment.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/corner_detection/id_card_aligment.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/corner_detection/utils.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/corner_detection/utils.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/id_card_classification/classify.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/id_card_classification/classify.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/mrc/mrc_detection.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/mrc/mrc_detection.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/mrc/utils.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/mrc/utils.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/passport.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/passport.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_align_passport/passport_utils.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_align_passport/passport_utils.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_align_passport/utils_align.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_align_passport/utils_align.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/passport/utils_detect_passport/utils_detect.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/passport/utils_detect_passport/utils_detect.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/nid_quality_liveness_check.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/quality_liveness_nid_checking/nid_quality_liveness_check.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/spell_checking/corrector_v2.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/spell_checking/corrector_v2.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/spoofing_nid/spoofing.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/spoofing_nid/spoofing.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/text_detection/dictionary.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/text_detection/dictionary.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,23 @@
 from ...commons.config import config
 from ..text_detection.utils import *
 from ..vietnamese_nlp.nlp_onnx import VietnameseOCR
+# from ..vietnamese_nlp.nlp_trt import TensorRuntimeOCR
 from ..vietnamese_nlp.vietocr.tool.config import Cfg
 from ..spell_checking.corrector_v2 import Correction
 from ..passport.utils_detect_passport.utils_detect import *
 
 
+def config_trt():
+    configs = Cfg.load_config_from_name('vgg_transformer')
+    configs['device'] = 'cuda:0'
+    configs['pretrained'] = False
+    return configs
+
+
 class IDcardPreprocessing(object):
     def __init__(self,
                  encode_path=config['vietnamese_nlp']['encoder'],
                  decode_path=config['vietnamese_nlp']['decoder']):
         self.encode_path = encode_path
         self.decode_path = decode_path
```

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/text_detection/utils.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/text_detection/utils.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/nlp_onnx.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/nlp_onnx.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 import onnxruntime as rt
 import numpy as np
-from ..vietnamese_nlp.vietocr.tool.translate import translate_trt, process_input, process_image
+from ..vietnamese_nlp.vietocr.tool.translate import translate_onnx, process_input, process_image
 from ..vietnamese_nlp.vietocr.model.vocab import Vocab
 
 
 class VietnameseOCR(object):
     def __init__(self, encode_onnx_model, decode_onnx_model, config):
-        session_options = ['CPUExecutionProvider']
+        session_options = ['CUDAExecutionProvider', "CPUExecutionProvider"]
         self.encoder_model = rt.InferenceSession(encode_onnx_model, providers=session_options)
         self.decoder_model = rt.InferenceSession(decode_onnx_model, providers=session_options)
         self.config = config
         self.vocab = Vocab(config['vocab'])
 
     def preprocess_batch(self, list_img):
         """
@@ -38,27 +38,27 @@
             Predict single-line image
             Input:
                 - img: pillow Image
         """
         img = process_input(img, self.config['dataset']['image_height'],
                             self.config['dataset']['image_min_width'], self.config['dataset']['image_max_width'])
 
-        s, prob = translate_trt(img, self.encoder_model, self.decoder_model)
+        s, prob = translate_onnx(img, self.encoder_model, self.decoder_model)
         s = s[0].tolist()
         prob = prob[0]
 
         if return_prob:
             return self.vocab.decode(s), prob
         else:
             return self.vocab.decode(s)
 
     def predict_batch(self, list_img):
         """
             Predict batch of image
             Input:
                 - img: pillow Image
         """
-        translated_sentence, prob = translate_trt(self.preprocess_batch(list_img), self.encoder_model, self.decoder_model)
+        translated_sentence, prob = translate_onnx(self.preprocess_batch(list_img), self.encoder_model, self.decoder_model)
         result = []
         for i, s in enumerate(translated_sentence):
             result.append(self.vocab.decode(translated_sentence[i].tolist()))
         return result
```

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/aug.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/aug.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader_v1.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader_v1.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/cnn.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/cnn.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/resnet.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/resnet.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/vgg.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/backbone/vgg.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/beam.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/beam.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/convseq2seq.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/convseq2seq.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/seq2seq.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/seq2seq.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/transformer.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/seqmodel/transformer.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/trainer.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/trainer.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/transformerocr.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/transformerocr.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/vocab.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/model/vocab.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/labelsmoothingloss.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/labelsmoothingloss.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/optim.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/optim/optim.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/predict.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/predict.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/utest.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tests/utest.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/config.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/config.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/create_dataset.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/create_dataset.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/predictor.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/predictor.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/translate.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/translate.py`

 * *Files 18% similar despite different names*

```diff
@@ -121,15 +121,55 @@
         char_probs = np.asarray(char_probs).T
         char_probs = np.multiply(char_probs, translated_sentence > 3)
         char_probs = np.sum(char_probs, axis=-1) / (char_probs > 0).sum(-1)
 
     return translated_sentence, char_probs
 
 
-def translate_trt(img, encoder_model, decoder_model, max_seq_length=256, sos_token=1, eos_token=2):
+def translate_trt(img, encoder_model, decoder_model, max_seq_length=128, sos_token=1, eos_token=2):
+    memory = encoder_model.run(img)
+
+    translated_sentence = [[sos_token] * len(img)]
+    char_probs = [[1] * len(img)]
+
+    max_length = 0
+    # print(memory.shape)
+    # print(np.any(np.asarray(translated_sentence).T==eos_token, axis=1))
+
+    while max_length <= max_seq_length and not all(np.any(np.asarray(translated_sentence).T == eos_token, axis=1)):
+        # print(np.asarray(translated_sentence))
+        tgt_inp = np.array(translated_sentence).astype('long')
+
+        values, indices = decoder_model.run(tgt_inp, memory)
+
+        indices = indices[:, -1, 0]
+        indices = indices.tolist()
+
+        values = values[:, -1, 0]
+        values = values.tolist()
+        # print(values)
+        # print(translated_sentence)
+        char_probs.append(values)
+        # print(values, indices)
+        translated_sentence.append(indices)
+        max_length += 1
+
+    # Process for each sentence
+    translated_sentence = np.asarray(translated_sentence).T
+    char_probs = np.asarray(char_probs).T
+    # char_probs = np.multiply(char_probs, translated_sentence > 3)
+    # char_probs = np.sum(char_probs, axis=-1)/(char_probs>0).sum(-1)
+    line_probs = []
+    for i in range(len(img)):
+        eos_index = np.where(translated_sentence[i] == eos_token)[0][0]
+        line_probs.append(np.mean(char_probs[i][:eos_index]))
+    return translated_sentence, line_probs
+
+
+def translate_onnx(img, encoder_model, decoder_model, max_seq_length=256, sos_token=1, eos_token=2):
     onnx_inp = {encoder_model.get_inputs()[0].name: img.astype('float32')}
     encoder_output = np.squeeze(encoder_model.run(None, onnx_inp))
     translated_sentence = [[sos_token] * len(img)]
     char_probs = [[1] * len(img)]
 
     max_length = 0
```

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/utils.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/tool/utils.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 import os
 import gdown
 import yaml
 import numpy as np
 import uuid
 import requests
 
+
 def download_weights(id_or_url, cached=None, md5=None, quiet=False):
     if id_or_url.startswith('http'):
         url = id_or_url
     else:
         url = 'https://drive.google.com/uc?id={}'.format(id_or_url)
 
     return gdown.cached_download(url=url, path=cached, md5=md5, quiet=quiet)
@@ -16,14 +17,15 @@
 
 def download_config(id):
     url = 'https://raw.githubusercontent.com/pbcquoc/vietocr/master/config/{}'.format(id)
     r = requests.get(url)
     config = yaml.safe_load(r.text)
     return config
 
+
 def compute_accuracy(ground_truth, predictions, mode='full_sequence'):
     """
     Computes accuracy
     :param ground_truth:
     :param predictions:
     :param display: Whether to print values to stdout
     :param mode: if 'per_char' is selected then
```

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/train.py` & `JustScan-1.2.0/app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/train.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/tools/api_json.py` & `JustScan-1.2.0/app/JustScan/ocr/core/tools/api_json.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/tools/dictionaries.py` & `JustScan-1.2.0/app/JustScan/ocr/core/tools/dictionaries.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan/ocr/core/tools/functional.py` & `JustScan-1.2.0/app/JustScan/ocr/core/tools/functional.py`

 * *Files identical despite different names*

### Comparing `JustScan-1.1.9/app/JustScan.egg-info/PKG-INFO` & `JustScan-1.2.0/app/JustScan.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 Metadata-Version: 2.1
 Name: JustScan
-Version: 1.1.9
+Version: 1.2.0
 Summary: E-kyc for Industries application
-Home-page: https://github.com/aihackervn
+Home-page: https://gitlab.itcgroup.io/Theodore.vo
 Author: Theodore
-Author-email: tinprocoder0908@gmail.com
+Author-email: theodore.v@itcgroup.io
 License: MIT
 Keywords: ITC,AI,E-kyc,Deep Learning,Computer Vision,Yolov5,Interface
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.9
+Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 
 # EKYC (OCR&FaceID) API 
 <!-- [![My Skills](https://skills.thijs.gg/icons?i=python&theme=light)](https://skills.thijs.gg) -->
 EKYC (OCR&FaceID) API is an API developed to provide Optical Character Recognition (OCR) and Face ID functionalities. The API supports the scanning of national ID cards, motorbike registration certificates, and EVN bills. It utilizes Makesense AI for labeling data, Yolov5 for text detection, and VietOCR for text recognition.
```

### Comparing `JustScan-1.1.9/app/JustScan.egg-info/SOURCES.txt` & `JustScan-1.2.0/app/JustScan.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -59,14 +59,15 @@
 app/JustScan/ocr/__init__.py
 app/JustScan/ocr/core/__init__.py
 app/JustScan/ocr/core/commons/SpoofingNID.py
 app/JustScan/ocr/core/commons/__init__.py
 app/JustScan/ocr/core/commons/config.py
 app/JustScan/ocr/core/commons/id_card_classification.py
 app/JustScan/ocr/core/commons/id_card_onnx.py
+app/JustScan/ocr/core/commons/id_card_trt.py
 app/JustScan/ocr/core/commons/merge_model.py
 app/JustScan/ocr/core/commons/utils/__init__.py
 app/JustScan/ocr/core/commons/utils/utils_onnx.py
 app/JustScan/ocr/core/modules/__init__.py
 app/JustScan/ocr/core/modules/corner_detection/__init__.py
 app/JustScan/ocr/core/modules/corner_detection/id_card_aligment.py
 app/JustScan/ocr/core/modules/corner_detection/utils.py
@@ -91,14 +92,17 @@
 app/JustScan/ocr/core/modules/spoofing_nid/__init__.py
 app/JustScan/ocr/core/modules/spoofing_nid/spoofing.py
 app/JustScan/ocr/core/modules/text_detection/__init__.py
 app/JustScan/ocr/core/modules/text_detection/dictionary.py
 app/JustScan/ocr/core/modules/text_detection/utils.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/__init__.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/nlp_onnx.py
+app/JustScan/ocr/core/modules/vietnamese_nlp/nlp_trt.py
+app/JustScan/ocr/core/modules/vietnamese_nlp/exe_backends/__init__.py
+app/JustScan/ocr/core/modules/vietnamese_nlp/exe_backends/trt_loader.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/__init__.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/predict.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/train.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/__init__.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/aug.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader.py
 app/JustScan/ocr/core/modules/vietnamese_nlp/vietocr/loader/dataloader_v1.py
```

### Comparing `JustScan-1.1.9/app/JustScan.egg-info/requires.txt` & `JustScan-1.2.0/app/JustScan.egg-info/requires.txt`

 * *Files 2% similar despite different names*

```diff
@@ -42,13 +42,13 @@
 starlette==0.27.0
 sympy==1.12
 torch==2.0.1
 torchvision==0.15.2
 tqdm==4.65.0
 typing_extensions==4.6.3
 tzdata==2023.3
-urllib3==2.0.3
+urllib3==1.26.6
 uvicorn==0.22.0
 
 [dev]
 pytest>=7.0
 twine>=4.0.2
```

### Comparing `JustScan-1.1.9/setup.py` & `JustScan-1.2.0/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,36 +1,37 @@
 from setuptools import find_packages, setup
+
 with open("app/JustScan/README.md", "r") as f:
     long_description = f.read()
 with open("requirements.txt", "r") as f:
     install_requires = [line.strip() for line in f if line.strip()]
 setup(
     name="JustScan",
-    version="1.1.9",
+    version="1.2.0",
     description="E-kyc for Industries application",
     package_dir={"": "app"},
     packages=find_packages(where="./app"),
     long_description=long_description,
     long_description_content_type="text/markdown",
-    url="https://github.com/aihackervn",
+    url="https://gitlab.itcgroup.io/Theodore.vo",
     author="Theodore",
-    author_email="tinprocoder0908@gmail.com",
+    author_email="theodore.v@itcgroup.io",
     keywords=["ITC", "AI", "E-kyc", "Deep Learning", "Computer Vision", "Yolov5",
               "Interface"],
 
     license="MIT",
     classifiers=[
         "License :: OSI Approved :: MIT License",
         "Programming Language :: Python :: 3.9",
         "Operating System :: OS Independent",
     ],
     install_requires=install_requires,
     entry_points={
         'console_scripts': [
-            'itc_service run api = JustScan.api.itc_cli:main',
+            'itc_service = JustScan.api.itc_cli:main',
         ],
     },
     extras_require={
         "dev": ["pytest>=7.0", "twine>=4.0.2"],
     },
-    python_requires=">=3.9"
+    python_requires=">=3.7"
 )
```

