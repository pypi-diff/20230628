# Comparing `tmp/funasr-0.6.5.tar.gz` & `tmp/funasr-0.6.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "funasr-0.6.5.tar", last modified: Mon Jun 26 14:54:41 2023, max compression
+gzip compressed data, was "funasr-0.6.6.tar", last modified: Wed Jun 28 08:08:12 2023, max compression
```

## Comparing `funasr-0.6.5.tar` & `funasr-0.6.6.tar`

### file list

```diff
@@ -1,439 +1,441 @@
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.582851 funasr-0.6.5/
--rw-r--r--   0 zhifu      (502) staff       (20)     9910 2023-06-26 14:54:41.582390 funasr-0.6.5/PKG-INFO
--rw-r--r--   0 zhifu      (502) staff       (20)     8910 2023-06-26 13:46:26.000000 funasr-0.6.5/README.md
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:40.957994 funasr-0.6.5/funasr/
--rw-r--r--   0 zhifu      (502) staff       (20)      203 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/__init__.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.081375 funasr-0.6.5/funasr/bin/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/bin/__init__.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     3798 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/bin/aggregate_stats_dirs.py
--rw-r--r--   0 zhifu      (502) staff       (20)    69796 2023-06-26 06:18:54.000000 funasr-0.6.5/funasr/bin/asr_infer.py
--rw-r--r--   0 zhifu      (502) staff       (20)    70759 2023-06-26 13:46:26.000000 funasr-0.6.5/funasr/bin/asr_inference_launch.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     1715 2023-05-24 02:58:26.000000 funasr-0.6.5/funasr/bin/asr_train.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5416 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/bin/build_trainer.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     1012 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/bin/data2vec_train.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)    11802 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/diar_infer.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)    17893 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/diar_inference_launch.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     1180 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/bin/diar_train.py
--rw-r--r--   0 zhifu      (502) staff       (20)    14489 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/lm_inference_launch.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     1189 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/bin/lm_train.py
--rw-r--r--   0 zhifu      (502) staff       (20)    12057 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/punc_infer.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     8085 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/punc_inference_launch.py
--rw-r--r--   0 zhifu      (502) staff       (20)      999 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/bin/punc_train.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     1241 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/bin/sa_asr_train.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     4991 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/sv_infer.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)    10058 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/sv_inference_launch.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     8449 2023-02-11 09:29:33.000000 funasr-0.6.5/funasr/bin/tokenize_text.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3458 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/tp_infer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     9526 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/tp_inference_launch.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)    17849 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/train.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6614 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/vad_infer.py
--rw-r--r--   0 zhifu      (502) staff       (20)    12260 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/bin/vad_inference_launch.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.115802 funasr-0.6.5/funasr/build_utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-05-18 12:04:14.000000 funasr-0.6.5/funasr/build_utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3987 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_args.py
--rw-r--r--   0 zhifu      (502) staff       (20)    16711 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_asr_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)      672 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/build_utils/build_dataloader.py
--rw-r--r--   0 zhifu      (502) staff       (20)     9680 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_diar_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1552 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/build_utils/build_distributed.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1693 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_lm_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1099 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8714 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_model_from_file.py
--rw-r--r--   0 zhifu      (502) staff       (20)      810 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/build_utils/build_optimizer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2993 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/build_utils/build_pretrain_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2211 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/build_utils/build_punc_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1531 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/build_utils/build_scheduler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1907 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_streaming_iterator.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7941 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_sv_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)    35626 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/build_utils/build_trainer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2324 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/build_utils/build_vad_model.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.119647 funasr-0.6.5/funasr/datasets/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/datasets/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4338 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/datasets/collate_fn.py
--rw-r--r--   0 zhifu      (502) staff       (20)    15174 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/datasets/dataset.py
--rw-r--r--   0 zhifu      (502) staff       (20)    15704 2023-06-26 13:46:26.000000 funasr-0.6.5/funasr/datasets/iterable_dataset.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.122530 funasr-0.6.5/funasr/datasets/large_datasets/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/datasets/large_datasets/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3794 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/datasets/large_datasets/build_dataloader.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.124451 funasr-0.6.5/funasr/datasets/large_datasets/datapipes/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/datasets/large_datasets/datapipes/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8298 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/datasets/large_datasets/datapipes/batch.py
--rw-r--r--   0 zhifu      (502) staff       (20)      519 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/datasets/large_datasets/datapipes/filter.py
--rw-r--r--   0 zhifu      (502) staff       (20)      453 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/datasets/large_datasets/datapipes/map.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10677 2023-06-26 13:46:26.000000 funasr-0.6.5/funasr/datasets/large_datasets/dataset.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.156356 funasr-0.6.5/funasr/datasets/large_datasets/utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/datasets/large_datasets/utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1382 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/datasets/large_datasets/utils/clipping.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1013 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/datasets/large_datasets/utils/filter.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1566 2023-05-07 09:22:42.000000 funasr-0.6.5/funasr/datasets/large_datasets/utils/hotword_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)      948 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/datasets/large_datasets/utils/low_frame_rate.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3303 2023-05-07 09:22:42.000000 funasr-0.6.5/funasr/datasets/large_datasets/utils/padding.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2582 2023-05-25 08:06:43.000000 funasr-0.6.5/funasr/datasets/large_datasets/utils/tokenize.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1281 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/datasets/ms_dataset.py
--rw-r--r--   0 zhifu      (502) staff       (20)    31032 2023-04-27 08:40:56.000000 funasr-0.6.5/funasr/datasets/preprocessor.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.174917 funasr-0.6.5/funasr/datasets/small_datasets/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-06-26 13:41:22.000000 funasr-0.6.5/funasr/datasets/small_datasets/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2825 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/datasets/small_datasets/collate_fn.py
--rw-r--r--   0 zhifu      (502) staff       (20)     9834 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/datasets/small_datasets/dataset.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5168 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/datasets/small_datasets/length_batch_sampler.py
--rw-r--r--   0 zhifu      (502) staff       (20)    33183 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/datasets/small_datasets/preprocessor.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7439 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/datasets/small_datasets/sequence_iter_factory.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.175874 funasr-0.6.5/funasr/export/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10882 2023-06-20 02:01:53.000000 funasr-0.6.5/funasr/export/export_model.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.178126 funasr-0.6.5/funasr/export/models/
--rw-r--r--   0 zhifu      (502) staff       (20)     5127 2023-05-07 09:22:42.000000 funasr-0.6.5/funasr/export/models/CT_Transformer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1540 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/models/__init__.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.182206 funasr-0.6.5/funasr/export/models/decoder/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/models/decoder/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6326 2023-04-14 02:11:18.000000 funasr-0.6.5/funasr/export/models/decoder/sanm_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5470 2023-03-10 07:21:13.000000 funasr-0.6.5/funasr/export/models/decoder/transformer_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8441 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/models/e2e_asr_paraformer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2047 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/models/e2e_vad.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.191814 funasr-0.6.5/funasr/export/models/encoder/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/models/encoder/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3881 2023-03-29 08:06:18.000000 funasr-0.6.5/funasr/export/models/encoder/conformer_encoder.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     9141 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/models/encoder/fsmn_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7524 2023-05-05 07:04:25.000000 funasr-0.6.5/funasr/export/models/encoder/sanm_encoder.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.194892 funasr-0.6.5/funasr/export/models/modules/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/models/modules/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1931 2023-03-29 08:06:18.000000 funasr-0.6.5/funasr/export/models/modules/decoder_layer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2354 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/export/models/modules/encoder_layer.py
--rw-r--r--   0 zhifu      (502) staff       (20)      658 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/models/modules/feedforward.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8644 2023-04-14 02:11:18.000000 funasr-0.6.5/funasr/export/models/modules/multihead_att.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.196829 funasr-0.6.5/funasr/export/models/predictor/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/models/predictor/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     9917 2023-04-14 02:11:18.000000 funasr-0.6.5/funasr/export/models/predictor/cif.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.210637 funasr-0.6.5/funasr/export/test/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/test/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      785 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/test/test_onnx.py
--rw-r--r--   0 zhifu      (502) staff       (20)      702 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/test/test_onnx_punc.py
--rw-r--r--   0 zhifu      (502) staff       (20)      927 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/export/test/test_onnx_punc_vadrealtime.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1046 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/export/test/test_onnx_vad.py
--rw-r--r--   0 zhifu      (502) staff       (20)      477 2023-05-24 08:36:46.000000 funasr-0.6.5/funasr/export/test/test_torchscripts.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.217662 funasr-0.6.5/funasr/export/utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2620 2023-02-08 11:34:59.000000 funasr-0.6.5/funasr/export/utils/torch_function.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.225832 funasr-0.6.5/funasr/fileio/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/fileio/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2383 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/fileio/datadir_writer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2357 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/fileio/npy_scp.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2361 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/fileio/rand_gen_dataset.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2273 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/fileio/read_text.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4050 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/fileio/sound_scp.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.227242 funasr-0.6.5/funasr/iterators/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/iterators/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      234 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/iterators/abs_iter_factory.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7808 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/iterators/chunk_iter_factory.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1140 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/iterators/multiple_iter_factory.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5236 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/iterators/sequence_iter_factory.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.233535 funasr-0.6.5/funasr/layers/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      358 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/layers/abs_normalize.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6717 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/complex_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3499 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/layers/global_mvn.py
--rw-r--r--   0 zhifu      (502) staff       (20)      348 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/layers/inversible_interface.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2539 2023-03-10 07:21:13.000000 funasr-0.6.5/funasr/layers/label_aggregation.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2564 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/log_mel.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10488 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/mask_along_axis.py
--rw-r--r--   0 zhifu      (502) staff       (20)     9033 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/sinc_conv.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8436 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/stft.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2513 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/time_warp.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2309 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/layers/utterance_mvn.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.234172 funasr-0.6.5/funasr/losses/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/losses/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4320 2023-05-09 03:02:42.000000 funasr-0.6.5/funasr/losses/label_smoothing_loss.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.236110 funasr-0.6.5/funasr/main_funcs/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/main_funcs/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4687 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/main_funcs/average_nbest_models.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5599 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/main_funcs/calculate_all_attentions.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5018 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/main_funcs/collect_stats.py
--rw-r--r--   0 zhifu      (502) staff       (20)     9906 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/main_funcs/pack_funcs.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.281275 funasr-0.6.5/funasr/models/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      319 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/base_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6541 2023-02-11 09:29:22.000000 funasr-0.6.5/funasr/models/ctc.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5285 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/data2vec.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.300754 funasr-0.6.5/funasr/models/decoder/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/decoder/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      473 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/decoder/abs_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    40834 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/models/decoder/contextual_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    12133 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/decoder/rnn_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8355 2023-05-09 09:17:41.000000 funasr-0.6.5/funasr/models/decoder/rnnt_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    75478 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/models/decoder/sanm_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1389 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/decoder/sv_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    43192 2023-05-09 03:02:42.000000 funasr-0.6.5/funasr/models/decoder/transformer_decoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    16699 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/e2e_asr.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8572 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/e2e_asr_common.py
--rw-r--r--   0 zhifu      (502) staff       (20)    15723 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/models/e2e_asr_contextual_paraformer.py
--rw-r--r--   0 zhifu      (502) staff       (20)    11845 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/models/e2e_asr_mfcca.py
--rw-r--r--   0 zhifu      (502) staff       (20)   100491 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/models/e2e_asr_paraformer.py
--rw-r--r--   0 zhifu      (502) staff       (20)    35111 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/models/e2e_asr_transducer.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10226 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/e2e_diar_eend_ola.py
--rw-r--r--   0 zhifu      (502) staff       (20)    20567 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/e2e_diar_sond.py
--rw-r--r--   0 zhifu      (502) staff       (20)    18965 2023-06-19 09:03:43.000000 funasr-0.6.5/funasr/models/e2e_sa_asr.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10084 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/e2e_sv.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6682 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/e2e_tp.py
--rw-r--r--   0 zhifu      (502) staff       (20)    51733 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/models/e2e_uni_asr.py
--rw-r--r--   0 zhifu      (502) staff       (20)    31909 2023-06-20 01:57:45.000000 funasr-0.6.5/funasr/models/e2e_vad.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.347884 funasr-0.6.5/funasr/models/encoder/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/encoder/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      502 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/encoder/abs_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    43621 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/models/encoder/conformer_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    20992 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/encoder/data2vec_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    19855 2023-03-10 07:21:13.000000 funasr-0.6.5/funasr/models/encoder/ecapa_tdnn_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10164 2023-02-16 09:30:51.000000 funasr-0.6.5/funasr/models/encoder/encoder_layer_mfcca.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     9281 2023-03-10 07:21:13.000000 funasr-0.6.5/funasr/models/encoder/fsmn_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    17681 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/encoder/mfcca_encoder.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.354194 funasr-0.6.5/funasr/models/encoder/opennmt_encoders/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-11 09:30:01.000000 funasr-0.6.5/funasr/models/encoder/opennmt_encoders/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      909 2023-02-11 09:30:01.000000 funasr-0.6.5/funasr/models/encoder/opennmt_encoders/ci_scorers.py
--rw-r--r--   0 zhifu      (502) staff       (20)    11046 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/models/encoder/opennmt_encoders/conv_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    13971 2023-02-11 09:30:01.000000 funasr-0.6.5/funasr/models/encoder/opennmt_encoders/fsmn_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    21170 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/models/encoder/opennmt_encoders/self_attention_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    41076 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/encoder/resnet34_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3633 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/encoder/rnn_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    56364 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/models/encoder/sanm_encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)    26890 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/encoder/transformer_encoder.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.363540 funasr-0.6.5/funasr/models/frontend/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/frontend/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      399 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/frontend/abs_frontend.py
--rw-r--r--   0 zhifu      (502) staff       (20)    12621 2023-06-21 03:15:06.000000 funasr-0.6.5/funasr/models/frontend/default.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1405 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/models/frontend/eend_ola_feature.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5758 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/frontend/fused.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4989 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/frontend/s3prl.py
--rw-r--r--   0 zhifu      (502) staff       (20)    20537 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/models/frontend/wav_frontend.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2321 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/frontend/wav_frontend_kaldifeat.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2811 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/frontend/windowing.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.365217 funasr-0.6.5/funasr/models/joint_net/
--rw-r--r--   0 zhifu      (502) staff       (20)        1 2023-04-25 03:22:30.000000 funasr-0.6.5/funasr/models/joint_net/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1855 2023-04-25 03:22:30.000000 funasr-0.6.5/funasr/models/joint_net/joint_network.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.366081 funasr-0.6.5/funasr/models/pooling/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/pooling/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3550 2023-05-09 03:02:42.000000 funasr-0.6.5/funasr/models/pooling/statistic_pooling.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.367162 funasr-0.6.5/funasr/models/postencoder/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/postencoder/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      403 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/postencoder/abs_postencoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3626 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/postencoder/hugging_face_transformers_postencoder.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.367853 funasr-0.6.5/funasr/models/predictor/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/predictor/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)    35747 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/models/predictor/cif.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.384021 funasr-0.6.5/funasr/models/preencoder/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/preencoder/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      402 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/preencoder/abs_preencoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1042 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/preencoder/linear.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10296 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/preencoder/sinc.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5906 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/models/seq_rnn_lm.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.385290 funasr-0.6.5/funasr/models/specaug/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/specaug/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      424 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/specaug/abs_specaug.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6607 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/models/specaug/specaug.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4476 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/target_delay_transformer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4246 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/models/transformer_lm.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4666 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/models/vad_realtime_transformer.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.416732 funasr-0.6.5/funasr/modules/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      940 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/add_sos_eos.py
--rw-r--r--   0 zhifu      (502) staff       (20)    38235 2023-05-09 03:02:42.000000 funasr-0.6.5/funasr/modules/attention.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.422755 funasr-0.6.5/funasr/modules/beam_search/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/beam_search/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)    13305 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/beam_search/batch_beam_search.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10175 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/beam_search/batch_beam_search_online_sim.py
--rw-r--r--   0 zhifu      (502) staff       (20)    53592 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/beam_search/beam_search.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)    20115 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/modules/beam_search/beam_search_sa_asr.py
--rw-r--r--   0 zhifu      (502) staff       (20)    23002 2023-04-25 03:22:30.000000 funasr-0.6.5/funasr/modules/beam_search/beam_search_transducer.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.427679 funasr-0.6.5/funasr/modules/data2vec/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5831 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/data_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4474 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/ema_module.py
--rw-r--r--   0 zhifu      (502) staff       (20)      442 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/grad_multiply.py
--rw-r--r--   0 zhifu      (502) staff       (20)    26458 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/multihead_attention.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4021 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/quant_noise.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4858 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)    12734 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/data2vec/wav2vec2.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4244 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/dynamic_conv.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4863 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/dynamic_conv2d.py
--rw-r--r--   0 zhifu      (502) staff       (20)    13662 2023-04-27 08:40:56.000000 funasr-0.6.5/funasr/modules/e2e_asr_common.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.428634 funasr-0.6.5/funasr/modules/eend_ola/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-03-29 08:06:18.000000 funasr-0.6.5/funasr/modules/eend_ola/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5287 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/modules/eend_ola/encoder.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2768 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/modules/eend_ola/encoder_decoder_attractor.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.430053 funasr-0.6.5/funasr/modules/eend_ola/utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-06-26 14:53:13.000000 funasr-0.6.5/funasr/modules/eend_ola/utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2761 2023-03-29 08:06:18.000000 funasr-0.6.5/funasr/modules/eend_ola/utils/losses.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3386 2023-03-29 08:06:18.000000 funasr-0.6.5/funasr/modules/eend_ola/utils/power.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7317 2023-03-29 08:06:18.000000 funasr-0.6.5/funasr/modules/eend_ola/utils/report.py
--rw-r--r--   0 zhifu      (502) staff       (20)    17767 2023-04-27 09:38:10.000000 funasr-0.6.5/funasr/modules/embedding.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.434959 funasr-0.6.5/funasr/modules/frontends/
--rw-r--r--   0 zhifu      (502) staff       (20)       30 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/frontends/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2731 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/frontends/beamformer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5540 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/frontends/dnn_beamformer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2825 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/frontends/dnn_wpe.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7958 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/frontends/feature_transform.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4585 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/frontends/frontend.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2648 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/frontends/mask_estimator.py
--rw-r--r--   0 zhifu      (502) staff       (20)      958 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/layer_norm.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3590 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/lightconv.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4230 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/lightconv2d.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1654 2023-03-28 05:50:14.000000 funasr-0.6.5/funasr/modules/mask.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4800 2023-02-11 09:30:01.000000 funasr-0.6.5/funasr/modules/multi_layer_conv.py
--rw-r--r--   0 zhifu      (502) staff       (20)    22963 2023-05-09 09:17:41.000000 funasr-0.6.5/funasr/modules/nets_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1936 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/positionwise_feed_forward.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3687 2023-05-09 09:17:41.000000 funasr-0.6.5/funasr/modules/repeat.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.438771 funasr-0.6.5/funasr/modules/rnn/
--rw-r--r--   0 zhifu      (502) staff       (20)       30 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/rnn/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4080 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/rnn/argument.py
--rw-r--r--   0 zhifu      (502) staff       (20)    66987 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/rnn/attentions.py
--rw-r--r--   0 zhifu      (502) staff       (20)    49387 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/rnn/decoders.py
--rw-r--r--   0 zhifu      (502) staff       (20)    14180 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/rnn/encoders.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.440014 funasr-0.6.5/funasr/modules/scorers/
--rw-r--r--   0 zhifu      (502) staff       (20)       30 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/scorers/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5026 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/scorers/ctc.py
--rw-r--r--   0 zhifu      (502) staff       (20)    13951 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/scorers/ctc_prefix_score.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1787 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/scorers/length_bonus.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5938 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/scorers/scorer_interface.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.441827 funasr-0.6.5/funasr/modules/streaming_utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/streaming_utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)    17409 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/modules/streaming_utils/chunk_utilis.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1809 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/streaming_utils/load_fr_tf.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2399 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/streaming_utils/utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)    21445 2023-05-25 08:06:43.000000 funasr-0.6.5/funasr/modules/subsampling.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1898 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/modules/subsampling_without_posenc.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.447010 funasr-0.6.5/funasr/optimizers/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/optimizers/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5643 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/optimizers/fairseq_adam.py
--rw-r--r--   0 zhifu      (502) staff       (20)      828 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/optimizers/sgd.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.447264 funasr-0.6.5/funasr/runtime/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-16 09:30:51.000000 funasr-0.6.5/funasr/runtime/__init__.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.447404 funasr-0.6.5/funasr/runtime/python/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-16 09:30:51.000000 funasr-0.6.5/funasr/runtime/python/__init__.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.448244 funasr-0.6.5/funasr/runtime/python/libtorch/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-03-29 08:06:19.000000 funasr-0.6.5/funasr/runtime/python/libtorch/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      544 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/libtorch/demo.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.449185 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/
--rw-r--r--   0 zhifu      (502) staff       (20)       65 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8172 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/paraformer_bin.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.463704 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/__init__.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     5123 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/compute_wer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7040 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/frontend.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7566 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/postprocess_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2762 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/timestamp_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4845 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1443 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/runtime/python/libtorch/setup.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.468169 funasr-0.6.5/funasr/runtime/python/onnxruntime/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-16 09:30:51.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      679 2023-05-12 03:37:01.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_paraformer_offline.py
--rw-r--r--   0 zhifu      (502) staff       (20)      724 2023-05-12 03:39:34.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_punc_offline.py
--rw-r--r--   0 zhifu      (502) staff       (20)      916 2023-05-12 03:39:34.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_punc_online.py
--rw-r--r--   0 zhifu      (502) staff       (20)      316 2023-05-12 03:39:34.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_vad_offline.py
--rw-r--r--   0 zhifu      (502) staff       (20)      930 2023-05-12 03:39:34.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_vad_online.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.470644 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/
--rw-r--r--   0 zhifu      (502) staff       (20)      218 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     8855 2023-05-12 03:03:13.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/paraformer_bin.py
--rw-r--r--   0 zhifu      (502) staff       (20)    13034 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/punc_bin.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.478267 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-04-12 07:23:40.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)    29216 2023-05-07 09:22:42.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/e2e_vad.py
--rw-r--r--   0 zhifu      (502) staff       (20)    15848 2023-04-23 09:14:56.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/frontend.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7686 2023-04-25 07:21:40.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/postprocess_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2933 2023-04-25 07:21:40.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/timestamp_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     9221 2023-05-12 02:56:06.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10950 2023-05-12 03:03:13.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/vad_bin.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1588 2023-06-19 11:16:01.000000 funasr-0.6.5/funasr/runtime/python/onnxruntime/setup.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.502395 funasr-0.6.5/funasr/samplers/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      425 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/abs_sampler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6231 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/build_batch_sampler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5716 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/folded_batch_sampler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5168 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/length_batch_sampler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5680 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/num_elements_batch_sampler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3144 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/sorted_batch_sampler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2940 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/samplers/unsorted_batch_sampler.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.506226 funasr-0.6.5/funasr/schedulers/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/schedulers/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1679 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/schedulers/abs_scheduler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2067 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/schedulers/noam_lr.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3658 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/schedulers/tri_stage_scheduler.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1494 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/schedulers/warmup_lr.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.514841 funasr-0.6.5/funasr/tasks/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/tasks/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)    73166 2023-05-24 02:58:26.000000 funasr-0.6.5/funasr/tasks/abs_task.py
--rw-r--r--   0 zhifu      (502) staff       (20)    58550 2023-06-19 09:03:43.000000 funasr-0.6.5/funasr/tasks/asr.py
--rw-r--r--   0 zhifu      (502) staff       (20)    12089 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/tasks/data2vec.py
--rw-r--r--   0 zhifu      (502) staff       (20)    32440 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/tasks/diar.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6755 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/tasks/lm.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7948 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/tasks/punctuation.py
--rw-r--r--   0 zhifu      (502) staff       (20)    21358 2023-06-19 09:03:43.000000 funasr-0.6.5/funasr/tasks/sa_asr.py
--rw-r--r--   0 zhifu      (502) staff       (20)    18791 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/tasks/sv.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10644 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/tasks/vad.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.524058 funasr-0.6.5/funasr/text/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      347 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/abs_tokenizer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2205 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/build_tokenizer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2230 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/char_tokenizer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1479 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/cleaner.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1968 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/korean_cleaner.py
--rw-r--r--   0 zhifu      (502) staff       (20)    16601 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/phoneme_tokenizer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1294 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/sentencepiece_tokenizer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2100 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/token_id_converter.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2074 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/text/word_tokenizer.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.542432 funasr-0.6.5/funasr/torch_utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)      987 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/add_gradient_noise.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2681 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/device_funcs.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1052 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/forward_adaptor.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3788 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/initialize.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3817 2023-05-07 09:22:42.000000 funasr-0.6.5/funasr/torch_utils/load_pretrained_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2498 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/model_summary.py
--rw-r--r--   0 zhifu      (502) staff       (20)      468 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/pytorch_version.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1615 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/recursive_op.py
--rw-r--r--   0 zhifu      (502) staff       (20)      167 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/torch_utils/set_all_random_seed.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.552929 funasr-0.6.5/funasr/train/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/train/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)    11513 2023-05-22 05:06:44.000000 funasr-0.6.5/funasr/train/abs_model.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3017 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/train/class_choices.py
--rw-r--r--   0 zhifu      (502) staff       (20)    14493 2023-03-29 08:06:19.000000 funasr-0.6.5/funasr/train/distributed_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)    18344 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/train/reporter.py
--rw-r--r--   0 zhifu      (502) staff       (20)    38665 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/train/trainer.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.576572 funasr-0.6.5/funasr/utils/
--rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/__init__.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2664 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/asr_env_checking.py
--rw-r--r--   0 zhifu      (502) staff       (20)    11744 2023-06-26 13:46:26.000000 funasr-0.6.5/funasr/utils/asr_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)      582 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/build_dataclass.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1380 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/cli_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2078 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/compute_eer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     6714 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/compute_min_dcf.py
--rwxr-xr-x   0 zhifu      (502) staff       (20)     5189 2023-04-17 03:36:48.000000 funasr-0.6.5/funasr/utils/compute_wer.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1760 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/config_argparse.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1830 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/get_default_kwargs.py
--rw-r--r--   0 zhifu      (502) staff       (20)     5632 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/griffin_lim.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4001 2023-02-11 09:30:01.000000 funasr-0.6.5/funasr/utils/job_runner.py
--rw-r--r--   0 zhifu      (502) staff       (20)      426 2023-06-06 13:50:59.000000 funasr-0.6.5/funasr/utils/kwargs2args.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1607 2023-02-11 09:30:01.000000 funasr-0.6.5/funasr/utils/misc.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1357 2023-02-09 08:39:15.000000 funasr-0.6.5/funasr/utils/modelscope_param.py
--rw-r--r--   0 zhifu      (502) staff       (20)      571 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/utils/modelscope_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)     3598 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/nested_dict_action.py
--rw-r--r--   0 zhifu      (502) staff       (20)     7734 2023-05-09 03:02:42.000000 funasr-0.6.5/funasr/utils/postprocess_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)    10247 2023-06-26 13:46:26.000000 funasr-0.6.5/funasr/utils/prepare_data.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2027 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/sized_dict.py
--rw-r--r--   0 zhifu      (502) staff       (20)    13380 2023-05-10 06:41:10.000000 funasr-0.6.5/funasr/utils/timestamp_tools.py
--rw-r--r--   0 zhifu      (502) staff       (20)     4185 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/types.py
--rw-r--r--   0 zhifu      (502) staff       (20)      638 2023-05-22 05:05:02.000000 funasr-0.6.5/funasr/utils/vad_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)    12078 2023-06-26 13:46:26.000000 funasr-0.6.5/funasr/utils/wav_utils.py
--rw-r--r--   0 zhifu      (502) staff       (20)      380 2023-02-07 07:13:39.000000 funasr-0.6.5/funasr/utils/yaml_no_alias_safe_dump.py
--rw-r--r--   0 zhifu      (502) staff       (20)        6 2023-06-26 14:54:07.000000 funasr-0.6.5/funasr/version.txt
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.014698 funasr-0.6.5/funasr.egg-info/
--rw-r--r--   0 zhifu      (502) staff       (20)     9910 2023-06-26 14:54:40.000000 funasr-0.6.5/funasr.egg-info/PKG-INFO
--rw-r--r--   0 zhifu      (502) staff       (20)    13940 2023-06-26 14:54:40.000000 funasr-0.6.5/funasr.egg-info/SOURCES.txt
--rw-r--r--   0 zhifu      (502) staff       (20)        1 2023-06-26 14:54:40.000000 funasr-0.6.5/funasr.egg-info/dependency_links.txt
--rw-r--r--   0 zhifu      (502) staff       (20)      857 2023-06-26 14:54:40.000000 funasr-0.6.5/funasr.egg-info/requires.txt
--rw-r--r--   0 zhifu      (502) staff       (20)        7 2023-06-26 14:54:40.000000 funasr-0.6.5/funasr.egg-info/top_level.txt
--rw-r--r--   0 zhifu      (502) staff       (20)       38 2023-06-26 14:54:41.582935 funasr-0.6.5/setup.cfg
--rw-r--r--   0 zhifu      (502) staff       (20)     4626 2023-06-26 13:46:26.000000 funasr-0.6.5/setup.py
-drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-26 14:54:41.581796 funasr-0.6.5/tests/
--rw-r--r--   0 zhifu      (502) staff       (20)    26773 2023-06-15 09:10:12.000000 funasr-0.6.5/tests/test_asr_inference_pipeline.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1310 2023-06-15 09:10:12.000000 funasr-0.6.5/tests/test_asr_vad_punc_inference_pipeline.py
--rw-r--r--   0 zhifu      (502) staff       (20)      804 2023-03-29 08:06:19.000000 funasr-0.6.5/tests/test_lm_pipeline.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2055 2023-04-17 03:36:48.000000 funasr-0.6.5/tests/test_punctuation_pipeline.py
--rw-r--r--   0 zhifu      (502) staff       (20)     1583 2023-06-20 01:57:45.000000 funasr-0.6.5/tests/test_sv_inference_pipeline.py
--rw-r--r--   0 zhifu      (502) staff       (20)     2298 2023-06-20 01:57:45.000000 funasr-0.6.5/tests/test_vad_inference_pipeline.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.286918 funasr-0.6.6/
+-rw-r--r--   0 zhifu      (502) staff       (20)     9951 2023-06-28 08:08:12.286351 funasr-0.6.6/PKG-INFO
+-rw-r--r--   0 zhifu      (502) staff       (20)     8951 2023-06-27 04:52:41.000000 funasr-0.6.6/README.md
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:10.250689 funasr-0.6.6/funasr/
+-rw-r--r--   0 zhifu      (502) staff       (20)      203 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/__init__.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:10.345993 funasr-0.6.6/funasr/bin/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/bin/__init__.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     3798 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/bin/aggregate_stats_dirs.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    69796 2023-06-26 06:18:54.000000 funasr-0.6.6/funasr/bin/asr_infer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    70907 2023-06-27 08:57:43.000000 funasr-0.6.6/funasr/bin/asr_inference_launch.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     1715 2023-05-24 02:58:26.000000 funasr-0.6.6/funasr/bin/asr_train.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5416 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/bin/build_trainer.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     1012 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/bin/data2vec_train.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)    11802 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/diar_infer.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)    17893 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/diar_inference_launch.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     1180 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/bin/diar_train.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    14489 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/lm_inference_launch.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     1189 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/bin/lm_train.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    12057 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/punc_infer.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     8085 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/punc_inference_launch.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      999 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/bin/punc_train.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     1241 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/bin/sa_asr_train.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     4991 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/sv_infer.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)    10058 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/sv_inference_launch.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     8449 2023-02-11 09:29:33.000000 funasr-0.6.6/funasr/bin/tokenize_text.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3458 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/tp_infer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     9526 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/tp_inference_launch.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)    17849 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/train.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6614 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/vad_infer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    12260 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/bin/vad_inference_launch.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.600920 funasr-0.6.6/funasr/build_utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-05-18 12:04:14.000000 funasr-0.6.6/funasr/build_utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3987 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_args.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    16902 2023-06-28 08:07:26.000000 funasr-0.6.6/funasr/build_utils/build_asr_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      672 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/build_utils/build_dataloader.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     9680 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_diar_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1552 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/build_utils/build_distributed.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1693 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_lm_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1099 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8714 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_model_from_file.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      810 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/build_utils/build_optimizer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2993 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/build_utils/build_pretrain_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2211 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/build_utils/build_punc_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1531 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/build_utils/build_scheduler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1907 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_streaming_iterator.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7941 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_sv_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    35626 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/build_utils/build_trainer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2324 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/build_utils/build_vad_model.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.603512 funasr-0.6.6/funasr/datasets/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/datasets/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4338 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/datasets/collate_fn.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    15174 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/datasets/dataset.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    15818 2023-06-27 08:57:43.000000 funasr-0.6.6/funasr/datasets/iterable_dataset.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.605248 funasr-0.6.6/funasr/datasets/large_datasets/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/datasets/large_datasets/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3794 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/datasets/large_datasets/build_dataloader.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.643055 funasr-0.6.6/funasr/datasets/large_datasets/datapipes/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/datasets/large_datasets/datapipes/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8298 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/datasets/large_datasets/datapipes/batch.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      519 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/datasets/large_datasets/datapipes/filter.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      453 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/datasets/large_datasets/datapipes/map.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10803 2023-06-27 08:57:43.000000 funasr-0.6.6/funasr/datasets/large_datasets/dataset.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.688556 funasr-0.6.6/funasr/datasets/large_datasets/utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/datasets/large_datasets/utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1382 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/datasets/large_datasets/utils/clipping.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1013 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/datasets/large_datasets/utils/filter.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1566 2023-05-07 09:22:42.000000 funasr-0.6.6/funasr/datasets/large_datasets/utils/hotword_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      948 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/datasets/large_datasets/utils/low_frame_rate.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3303 2023-05-07 09:22:42.000000 funasr-0.6.6/funasr/datasets/large_datasets/utils/padding.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2582 2023-05-25 08:06:43.000000 funasr-0.6.6/funasr/datasets/large_datasets/utils/tokenize.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1281 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/datasets/ms_dataset.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    31032 2023-04-27 08:40:56.000000 funasr-0.6.6/funasr/datasets/preprocessor.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.692982 funasr-0.6.6/funasr/datasets/small_datasets/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-06-26 13:41:22.000000 funasr-0.6.6/funasr/datasets/small_datasets/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2825 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/datasets/small_datasets/collate_fn.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     9834 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/datasets/small_datasets/dataset.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5168 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/datasets/small_datasets/length_batch_sampler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    33183 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/datasets/small_datasets/preprocessor.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7439 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/datasets/small_datasets/sequence_iter_factory.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.693627 funasr-0.6.6/funasr/export/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    11128 2023-06-28 06:45:37.000000 funasr-0.6.6/funasr/export/export_model.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.730580 funasr-0.6.6/funasr/export/models/
+-rw-r--r--   0 zhifu      (502) staff       (20)     5127 2023-05-07 09:22:42.000000 funasr-0.6.6/funasr/export/models/CT_Transformer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1540 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/models/__init__.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.731804 funasr-0.6.6/funasr/export/models/decoder/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/models/decoder/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6326 2023-04-14 02:11:18.000000 funasr-0.6.6/funasr/export/models/decoder/sanm_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5470 2023-03-10 07:21:13.000000 funasr-0.6.6/funasr/export/models/decoder/transformer_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8441 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/models/e2e_asr_paraformer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2047 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/models/e2e_vad.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.733550 funasr-0.6.6/funasr/export/models/encoder/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/models/encoder/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3881 2023-03-29 08:06:18.000000 funasr-0.6.6/funasr/export/models/encoder/conformer_encoder.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     9141 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/models/encoder/fsmn_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7524 2023-05-05 07:04:25.000000 funasr-0.6.6/funasr/export/models/encoder/sanm_encoder.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.764625 funasr-0.6.6/funasr/export/models/modules/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/models/modules/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1931 2023-03-29 08:06:18.000000 funasr-0.6.6/funasr/export/models/modules/decoder_layer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2354 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/export/models/modules/encoder_layer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      658 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/models/modules/feedforward.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8644 2023-04-14 02:11:18.000000 funasr-0.6.6/funasr/export/models/modules/multihead_att.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.765410 funasr-0.6.6/funasr/export/models/predictor/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/models/predictor/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     9917 2023-04-14 02:11:18.000000 funasr-0.6.6/funasr/export/models/predictor/cif.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.768162 funasr-0.6.6/funasr/export/test/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/test/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      785 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/test/test_onnx.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      702 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/test/test_onnx_punc.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      927 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/export/test/test_onnx_punc_vadrealtime.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1046 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/export/test/test_onnx_vad.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      477 2023-05-24 08:36:46.000000 funasr-0.6.6/funasr/export/test/test_torchscripts.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.794872 funasr-0.6.6/funasr/export/utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2620 2023-02-08 11:34:59.000000 funasr-0.6.6/funasr/export/utils/torch_function.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.797366 funasr-0.6.6/funasr/fileio/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/fileio/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2383 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/fileio/datadir_writer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2357 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/fileio/npy_scp.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2361 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/fileio/rand_gen_dataset.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2273 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/fileio/read_text.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6006 2023-06-27 03:21:23.000000 funasr-0.6.6/funasr/fileio/sound_scp.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.799193 funasr-0.6.6/funasr/iterators/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/iterators/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      234 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/iterators/abs_iter_factory.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7808 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/iterators/chunk_iter_factory.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1140 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/iterators/multiple_iter_factory.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5236 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/iterators/sequence_iter_factory.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.834041 funasr-0.6.6/funasr/layers/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      358 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/layers/abs_normalize.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6717 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/complex_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3499 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/layers/global_mvn.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      348 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/layers/inversible_interface.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2539 2023-03-10 07:21:13.000000 funasr-0.6.6/funasr/layers/label_aggregation.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2564 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/log_mel.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10488 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/mask_along_axis.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     9033 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/sinc_conv.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8436 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/stft.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2513 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/time_warp.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2309 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/layers/utterance_mvn.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.834402 funasr-0.6.6/funasr/losses/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/losses/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4320 2023-05-09 03:02:42.000000 funasr-0.6.6/funasr/losses/label_smoothing_loss.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.873008 funasr-0.6.6/funasr/main_funcs/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/main_funcs/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4687 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/main_funcs/average_nbest_models.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5599 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/main_funcs/calculate_all_attentions.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5018 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/main_funcs/collect_stats.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     9906 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/main_funcs/pack_funcs.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.941084 funasr-0.6.6/funasr/models/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      319 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/base_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6541 2023-02-11 09:29:22.000000 funasr-0.6.6/funasr/models/ctc.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5285 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/data2vec.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:11.999058 funasr-0.6.6/funasr/models/decoder/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/decoder/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      473 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/decoder/abs_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    40834 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/models/decoder/contextual_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    12133 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/decoder/rnn_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8355 2023-05-09 09:17:41.000000 funasr-0.6.6/funasr/models/decoder/rnnt_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    75478 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/models/decoder/sanm_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1389 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/decoder/sv_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    43192 2023-05-09 03:02:42.000000 funasr-0.6.6/funasr/models/decoder/transformer_decoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    16699 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/e2e_asr.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8572 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/e2e_asr_common.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    15723 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/models/e2e_asr_contextual_paraformer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    11845 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/models/e2e_asr_mfcca.py
+-rw-r--r--   0 zhifu      (502) staff       (20)   100491 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/models/e2e_asr_paraformer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    35111 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/models/e2e_asr_transducer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10226 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/e2e_diar_eend_ola.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    20567 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/e2e_diar_sond.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    18965 2023-06-19 09:03:43.000000 funasr-0.6.6/funasr/models/e2e_sa_asr.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10084 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/e2e_sv.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6682 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/e2e_tp.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    51733 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/models/e2e_uni_asr.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    31909 2023-06-20 01:57:45.000000 funasr-0.6.6/funasr/models/e2e_vad.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.007419 funasr-0.6.6/funasr/models/encoder/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/encoder/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      502 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/encoder/abs_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    45056 2023-06-27 03:21:23.000000 funasr-0.6.6/funasr/models/encoder/conformer_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    20992 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/encoder/data2vec_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    19855 2023-03-10 07:21:13.000000 funasr-0.6.6/funasr/models/encoder/ecapa_tdnn_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10164 2023-02-16 09:30:51.000000 funasr-0.6.6/funasr/models/encoder/encoder_layer_mfcca.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     9281 2023-03-10 07:21:13.000000 funasr-0.6.6/funasr/models/encoder/fsmn_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    17681 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/encoder/mfcca_encoder.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.009093 funasr-0.6.6/funasr/models/encoder/opennmt_encoders/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-11 09:30:01.000000 funasr-0.6.6/funasr/models/encoder/opennmt_encoders/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      909 2023-02-11 09:30:01.000000 funasr-0.6.6/funasr/models/encoder/opennmt_encoders/ci_scorers.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    11046 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/models/encoder/opennmt_encoders/conv_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    13971 2023-02-11 09:30:01.000000 funasr-0.6.6/funasr/models/encoder/opennmt_encoders/fsmn_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    21170 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/models/encoder/opennmt_encoders/self_attention_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    41076 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/encoder/resnet34_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3633 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/encoder/rnn_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    56364 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/models/encoder/sanm_encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    26890 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/encoder/transformer_encoder.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.046747 funasr-0.6.6/funasr/models/frontend/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/frontend/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      399 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/frontend/abs_frontend.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    12621 2023-06-21 03:15:06.000000 funasr-0.6.6/funasr/models/frontend/default.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1405 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/models/frontend/eend_ola_feature.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5758 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/frontend/fused.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4989 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/frontend/s3prl.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    20537 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/models/frontend/wav_frontend.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2321 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/frontend/wav_frontend_kaldifeat.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2811 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/frontend/windowing.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.047622 funasr-0.6.6/funasr/models/joint_net/
+-rw-r--r--   0 zhifu      (502) staff       (20)        1 2023-04-25 03:22:30.000000 funasr-0.6.6/funasr/models/joint_net/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1855 2023-04-25 03:22:30.000000 funasr-0.6.6/funasr/models/joint_net/joint_network.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.048439 funasr-0.6.6/funasr/models/pooling/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/pooling/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3550 2023-05-09 03:02:42.000000 funasr-0.6.6/funasr/models/pooling/statistic_pooling.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.049823 funasr-0.6.6/funasr/models/postencoder/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/postencoder/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      403 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/postencoder/abs_postencoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3626 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/postencoder/hugging_face_transformers_postencoder.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.050359 funasr-0.6.6/funasr/models/predictor/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/predictor/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    35747 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/models/predictor/cif.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.051606 funasr-0.6.6/funasr/models/preencoder/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/preencoder/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      402 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/preencoder/abs_preencoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1042 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/preencoder/linear.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10296 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/preencoder/sinc.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5906 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/models/seq_rnn_lm.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.052275 funasr-0.6.6/funasr/models/specaug/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/specaug/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      424 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/specaug/abs_specaug.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6607 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/models/specaug/specaug.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4476 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/target_delay_transformer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4246 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/models/transformer_lm.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4666 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/models/vad_realtime_transformer.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.074601 funasr-0.6.6/funasr/modules/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      940 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/add_sos_eos.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    38235 2023-05-09 03:02:42.000000 funasr-0.6.6/funasr/modules/attention.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.076483 funasr-0.6.6/funasr/modules/beam_search/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/beam_search/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    13305 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/beam_search/batch_beam_search.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10175 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/beam_search/batch_beam_search_online_sim.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    53592 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/beam_search/beam_search.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)    20115 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/modules/beam_search/beam_search_sa_asr.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    23002 2023-04-25 03:22:30.000000 funasr-0.6.6/funasr/modules/beam_search/beam_search_transducer.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.113122 funasr-0.6.6/funasr/modules/data2vec/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5831 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/data_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4474 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/ema_module.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      442 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/grad_multiply.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    26458 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/multihead_attention.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4021 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/quant_noise.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4858 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    12734 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/data2vec/wav2vec2.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4244 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/dynamic_conv.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4863 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/dynamic_conv2d.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    13662 2023-04-27 08:40:56.000000 funasr-0.6.6/funasr/modules/e2e_asr_common.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.113827 funasr-0.6.6/funasr/modules/eend_ola/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-03-29 08:06:18.000000 funasr-0.6.6/funasr/modules/eend_ola/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5287 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/modules/eend_ola/encoder.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2768 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/modules/eend_ola/encoder_decoder_attractor.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.189530 funasr-0.6.6/funasr/modules/eend_ola/utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-06-26 14:53:13.000000 funasr-0.6.6/funasr/modules/eend_ola/utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2761 2023-03-29 08:06:18.000000 funasr-0.6.6/funasr/modules/eend_ola/utils/losses.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3386 2023-03-29 08:06:18.000000 funasr-0.6.6/funasr/modules/eend_ola/utils/power.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7317 2023-03-29 08:06:18.000000 funasr-0.6.6/funasr/modules/eend_ola/utils/report.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    17767 2023-04-27 09:38:10.000000 funasr-0.6.6/funasr/modules/embedding.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.191529 funasr-0.6.6/funasr/modules/frontends/
+-rw-r--r--   0 zhifu      (502) staff       (20)       30 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/frontends/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2731 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/frontends/beamformer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5540 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/frontends/dnn_beamformer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2825 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/frontends/dnn_wpe.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7958 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/frontends/feature_transform.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4585 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/frontends/frontend.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2648 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/frontends/mask_estimator.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      958 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/layer_norm.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3590 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/lightconv.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4230 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/lightconv2d.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1654 2023-03-28 05:50:14.000000 funasr-0.6.6/funasr/modules/mask.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4800 2023-02-11 09:30:01.000000 funasr-0.6.6/funasr/modules/multi_layer_conv.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    22963 2023-05-09 09:17:41.000000 funasr-0.6.6/funasr/modules/nets_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1936 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/positionwise_feed_forward.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3687 2023-05-09 09:17:41.000000 funasr-0.6.6/funasr/modules/repeat.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.197030 funasr-0.6.6/funasr/modules/rnn/
+-rw-r--r--   0 zhifu      (502) staff       (20)       30 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/rnn/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4080 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/rnn/argument.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    66987 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/rnn/attentions.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    49387 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/rnn/decoders.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    14180 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/rnn/encoders.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.198279 funasr-0.6.6/funasr/modules/scorers/
+-rw-r--r--   0 zhifu      (502) staff       (20)       30 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/scorers/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5026 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/scorers/ctc.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    13951 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/scorers/ctc_prefix_score.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1787 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/scorers/length_bonus.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5938 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/scorers/scorer_interface.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.199443 funasr-0.6.6/funasr/modules/streaming_utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/streaming_utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    17409 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/modules/streaming_utils/chunk_utilis.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1809 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/streaming_utils/load_fr_tf.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2399 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/streaming_utils/utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    21806 2023-06-27 03:21:23.000000 funasr-0.6.6/funasr/modules/subsampling.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1898 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/modules/subsampling_without_posenc.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.200695 funasr-0.6.6/funasr/optimizers/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/optimizers/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5643 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/optimizers/fairseq_adam.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      828 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/optimizers/sgd.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.200965 funasr-0.6.6/funasr/runtime/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-16 09:30:51.000000 funasr-0.6.6/funasr/runtime/__init__.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.201134 funasr-0.6.6/funasr/runtime/python/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-16 09:30:51.000000 funasr-0.6.6/funasr/runtime/python/__init__.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.201860 funasr-0.6.6/funasr/runtime/python/libtorch/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-03-29 08:06:19.000000 funasr-0.6.6/funasr/runtime/python/libtorch/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      544 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/libtorch/demo.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.202920 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/
+-rw-r--r--   0 zhifu      (502) staff       (20)       65 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8172 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/paraformer_bin.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.208150 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/__init__.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     5123 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/compute_wer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7040 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/frontend.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7566 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/postprocess_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2762 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/timestamp_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4845 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1443 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/runtime/python/libtorch/setup.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.228646 funasr-0.6.6/funasr/runtime/python/onnxruntime/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-16 09:30:51.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      679 2023-05-12 03:37:01.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_paraformer_offline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      724 2023-05-12 03:39:34.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_punc_offline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      916 2023-05-12 03:39:34.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_punc_online.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      316 2023-05-12 03:39:34.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_vad_offline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      930 2023-05-12 03:39:34.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_vad_online.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.244720 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/
+-rw-r--r--   0 zhifu      (502) staff       (20)      218 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     8855 2023-05-12 03:03:13.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/paraformer_bin.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    13034 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/punc_bin.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.247409 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-04-12 07:23:40.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    29216 2023-05-07 09:22:42.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/e2e_vad.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    15848 2023-04-23 09:14:56.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/frontend.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7686 2023-04-25 07:21:40.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/postprocess_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2933 2023-04-25 07:21:40.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/timestamp_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     9221 2023-05-12 02:56:06.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10950 2023-06-27 11:42:15.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/vad_bin.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1588 2023-06-19 11:16:01.000000 funasr-0.6.6/funasr/runtime/python/onnxruntime/setup.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.249576 funasr-0.6.6/funasr/samplers/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      425 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/abs_sampler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6231 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/build_batch_sampler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5716 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/folded_batch_sampler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5168 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/length_batch_sampler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5680 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/num_elements_batch_sampler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3144 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/sorted_batch_sampler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2940 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/samplers/unsorted_batch_sampler.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.250927 funasr-0.6.6/funasr/schedulers/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/schedulers/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1679 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/schedulers/abs_scheduler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2067 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/schedulers/noam_lr.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3658 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/schedulers/tri_stage_scheduler.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1494 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/schedulers/warmup_lr.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.267213 funasr-0.6.6/funasr/tasks/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/tasks/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    73166 2023-05-24 02:58:26.000000 funasr-0.6.6/funasr/tasks/abs_task.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    58550 2023-06-19 09:03:43.000000 funasr-0.6.6/funasr/tasks/asr.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    12089 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/tasks/data2vec.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    32440 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/tasks/diar.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6755 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/tasks/lm.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7948 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/tasks/punctuation.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    21358 2023-06-19 09:03:43.000000 funasr-0.6.6/funasr/tasks/sa_asr.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    18791 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/tasks/sv.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10644 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/tasks/vad.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.269879 funasr-0.6.6/funasr/text/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      347 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/abs_tokenizer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2205 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/build_tokenizer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2230 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/char_tokenizer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1479 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/cleaner.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1968 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/korean_cleaner.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    16601 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/phoneme_tokenizer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1294 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/sentencepiece_tokenizer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2100 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/token_id_converter.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2074 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/text/word_tokenizer.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.272199 funasr-0.6.6/funasr/torch_utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      987 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/add_gradient_noise.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2681 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/device_funcs.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1052 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/forward_adaptor.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3788 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/initialize.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3817 2023-05-07 09:22:42.000000 funasr-0.6.6/funasr/torch_utils/load_pretrained_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2498 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/model_summary.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      468 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/pytorch_version.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1615 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/recursive_op.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      167 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/torch_utils/set_all_random_seed.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.273856 funasr-0.6.6/funasr/train/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/train/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    11513 2023-05-22 05:06:44.000000 funasr-0.6.6/funasr/train/abs_model.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3017 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/train/class_choices.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    14493 2023-03-29 08:06:19.000000 funasr-0.6.6/funasr/train/distributed_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    18344 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/train/reporter.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    38665 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/train/trainer.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.283127 funasr-0.6.6/funasr/utils/
+-rw-r--r--   0 zhifu      (502) staff       (20)        0 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/__init__.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2664 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/asr_env_checking.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    11744 2023-06-26 13:46:26.000000 funasr-0.6.6/funasr/utils/asr_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      582 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/build_dataclass.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1380 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/cli_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2078 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/compute_eer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     6714 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/compute_min_dcf.py
+-rwxr-xr-x   0 zhifu      (502) staff       (20)     5189 2023-04-17 03:36:48.000000 funasr-0.6.6/funasr/utils/compute_wer.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1760 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/config_argparse.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1830 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/get_default_kwargs.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     5632 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/griffin_lim.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4001 2023-02-11 09:30:01.000000 funasr-0.6.6/funasr/utils/job_runner.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      426 2023-06-06 13:50:59.000000 funasr-0.6.6/funasr/utils/kwargs2args.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1607 2023-02-11 09:30:01.000000 funasr-0.6.6/funasr/utils/misc.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1357 2023-02-09 08:39:15.000000 funasr-0.6.6/funasr/utils/modelscope_param.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      571 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/utils/modelscope_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     3598 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/nested_dict_action.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     7734 2023-05-09 03:02:42.000000 funasr-0.6.6/funasr/utils/postprocess_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    10247 2023-06-26 13:46:26.000000 funasr-0.6.6/funasr/utils/prepare_data.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1665 2023-06-28 06:44:46.000000 funasr-0.6.6/funasr/utils/runtime_sdk_download_tool.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2027 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/sized_dict.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    13380 2023-05-10 06:41:10.000000 funasr-0.6.6/funasr/utils/timestamp_tools.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     4185 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/types.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      638 2023-05-22 05:05:02.000000 funasr-0.6.6/funasr/utils/vad_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)    12182 2023-06-27 08:57:43.000000 funasr-0.6.6/funasr/utils/wav_utils.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      380 2023-02-07 07:13:39.000000 funasr-0.6.6/funasr/utils/yaml_no_alias_safe_dump.py
+-rw-r--r--   0 zhifu      (502) staff       (20)        6 2023-06-28 08:07:53.000000 funasr-0.6.6/funasr/version.txt
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:10.252357 funasr-0.6.6/funasr.egg-info/
+-rw-r--r--   0 zhifu      (502) staff       (20)     9951 2023-06-28 08:08:09.000000 funasr-0.6.6/funasr.egg-info/PKG-INFO
+-rw-r--r--   0 zhifu      (502) staff       (20)    14008 2023-06-28 08:08:10.000000 funasr-0.6.6/funasr.egg-info/SOURCES.txt
+-rw-r--r--   0 zhifu      (502) staff       (20)        1 2023-06-28 08:08:09.000000 funasr-0.6.6/funasr.egg-info/dependency_links.txt
+-rw-r--r--   0 zhifu      (502) staff       (20)      857 2023-06-28 08:08:09.000000 funasr-0.6.6/funasr.egg-info/requires.txt
+-rw-r--r--   0 zhifu      (502) staff       (20)        7 2023-06-28 08:08:10.000000 funasr-0.6.6/funasr.egg-info/top_level.txt
+-rw-r--r--   0 zhifu      (502) staff       (20)       38 2023-06-28 08:08:12.287008 funasr-0.6.6/setup.cfg
+-rw-r--r--   0 zhifu      (502) staff       (20)     4626 2023-06-26 13:46:26.000000 funasr-0.6.6/setup.py
+drwxr-xr-x   0 zhifu      (502) staff       (20)        0 2023-06-28 08:08:12.285676 funasr-0.6.6/tests/
+-rw-r--r--   0 zhifu      (502) staff       (20)    26773 2023-06-15 09:10:12.000000 funasr-0.6.6/tests/test_asr_inference_pipeline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1310 2023-06-15 09:10:12.000000 funasr-0.6.6/tests/test_asr_vad_punc_inference_pipeline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)      804 2023-03-29 08:06:19.000000 funasr-0.6.6/tests/test_lm_pipeline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2055 2023-04-17 03:36:48.000000 funasr-0.6.6/tests/test_punctuation_pipeline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1583 2023-06-20 01:57:45.000000 funasr-0.6.6/tests/test_sv_inference_pipeline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     1741 2023-06-28 08:07:26.000000 funasr-0.6.6/tests/test_tp_pipeline.py
+-rw-r--r--   0 zhifu      (502) staff       (20)     2298 2023-06-20 01:57:45.000000 funasr-0.6.6/tests/test_vad_inference_pipeline.py
```

### Comparing `funasr-0.6.5/PKG-INFO` & `funasr-0.6.6/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: funasr
-Version: 0.6.5
+Version: 0.6.6
 Summary: FunASR: A Fundamental End-to-End Speech Recognition Toolkit
 Home-page: https://github.com/alibaba-damo-academy/FunASR.git
 Author: Speech Lab of DAMO Academy, Alibaba Group
 Author-email: funasr@list.alibaba-inc.com
 License: The MIT License
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
@@ -56,17 +56,17 @@
 - We have released a vast collection of academic and industrial pretrained models on the [ModelScope](https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition), which can be accessed through our [Model Zoo](https://github.com/alibaba-damo-academy/FunASR/blob/main/docs/model_zoo/modelscope_models.md). The representative [Paraformer-large](https://www.modelscope.cn/models/damo/speech_paraformer-large_asr_nat-zh-cn-16k-common-vocab8404-pytorch/summary) model has achieved SOTA performance in many speech recognition tasks. 
 - FunASR offers a user-friendly pipeline for fine-tuning pretrained models from the [ModelScope](https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition). Additionally, the optimized dataloader in FunASR enables faster training speeds for large-scale datasets. This feature enhances the efficiency of the speech recognition process for researchers and practitioners.
 
 ## Installation
 
 Install from pip
 ```shell
-pip install -U funasr
+pip3 install -U funasr
 # For the users in China, you could install with the command:
-# pip install -U funasr -i https://mirror.sjtu.edu.cn/pypi/web/simple
+# pip3 install -U funasr -i https://mirror.sjtu.edu.cn/pypi/web/simple
 ```
 
 Or install from source code
 
 
 ``` sh
 git clone https://github.com/alibaba/FunASR.git && cd FunASR
@@ -121,21 +121,22 @@
 
 ### runtime
 
 An example with websocket:
 
 For the server:
 ```shell
+cd funasr/runtime/python/websocket
 python wss_srv_asr.py --port 10095
 ```
 
 For the client:
 ```shell
-python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --chunk_size "5,10,5"
-#python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results"
+python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size "5,10,5"
+#python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results"
 ```
 More examples could be found in [docs](https://alibaba-damo-academy.github.io/FunASR/en/runtime/websocket_python.html#id2)
 ## Contact
 
 If you have any questions about FunASR, please contact us by
 
 - email: [funasr@list.alibaba-inc.com](funasr@list.alibaba-inc.com)
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: funasr Version: 0.6.5 Summary: FunASR: A
+Metadata-Version: 2.1 Name: funasr Version: 0.6.6 Summary: FunASR: A
 Fundamental End-to-End Speech Recognition Toolkit Home-page: https://
 github.com/alibaba-damo-academy/FunASR.git Author: Speech Lab of DAMO Academy,
 Alibaba Group Author-email: funasr@list.alibaba-inc.com License: The MIT
 License Classifier: Programming Language :: Python Classifier: Programming
 Language :: Python :: 3 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8 Classifier: Programming
 Language :: Python :: 3.9 Classifier: Development Status :: 5 - Production/
@@ -52,16 +52,16 @@
 large_asr_nat-zh-cn-16k-common-vocab8404-pytorch/summary) model has achieved
 SOTA performance in many speech recognition tasks. - FunASR offers a user-
 friendly pipeline for fine-tuning pretrained models from the [ModelScope]
 (https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition).
 Additionally, the optimized dataloader in FunASR enables faster training speeds
 for large-scale datasets. This feature enhances the efficiency of the speech
 recognition process for researchers and practitioners. ## Installation Install
-from pip ```shell pip install -U funasr # For the users in China, you could
-install with the command: # pip install -U funasr -i https://
+from pip ```shell pip3 install -U funasr # For the users in China, you could
+install with the command: # pip3 install -U funasr -i https://
 mirror.sjtu.edu.cn/pypi/web/simple ``` Or install from source code ``` sh git
 clone https://github.com/alibaba/FunASR.git && cd FunASR pip3 install -e ./ #
 For the users in China, you could install with the command: # pip3 install -
 e ./ -i https://mirror.sjtu.edu.cn/pypi/web/simple ``` If you want to use the
 pretrained models in ModelScope, you should install the modelscope: ```shell
 pip3 install -U modelscope # For the users in China, you could install with the
 command: # pip3 install -U modelscope -f https://modelscope.oss-cn-
@@ -80,24 +80,24 @@
 ( task=Tasks.auto_speech_recognition, model='damo/speech_paraformer-
 large_asr_nat-zh-cn-16k-common-vocab8404-pytorch', ) rec_result =
 inference_pipeline(audio_in='https://isv-data.oss-cn-hangzhou.aliyuncs.com/ics/
 MaaS/ASR/test_audio/asr_example_zh.wav') print(rec_result) # {'text':
 'æ¬¢è¿å¤§å®¶æ¥ä½éªè¾¾æ©é¢æ¨åºçè¯­é³è¯å«æ¨¡å'} ``` More examples
 could be found in [docs](https://alibaba-damo-academy.github.io/FunASR/en/
 modelscope_pipeline/quick_start.html) ### runtime An example with websocket:
-For the server: ```shell python wss_srv_asr.py --port 10095 ``` For the client:
-```shell python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --
-chunk_size "5,10,5" #python wss_client_asr.py --host "0.0.0.0" --port 10095 --
-mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./
-results" ``` More examples could be found in [docs](https://alibaba-damo-
-academy.github.io/FunASR/en/runtime/websocket_python.html#id2) ## Contact If
-you have any questions about FunASR, please contact us by - email:
-[funasr@list.alibaba-inc.com](funasr@list.alibaba-inc.com) |Dingding group |
-Wechat group | |:---:|:-----------------------------------------------------:
-| |
+For the server: ```shell cd funasr/runtime/python/websocket python
+wss_srv_asr.py --port 10095 ``` For the client: ```shell python
+wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size
+"5,10,5" #python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass
+--chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results" ```
+More examples could be found in [docs](https://alibaba-damo-academy.github.io/
+FunASR/en/runtime/websocket_python.html#id2) ## Contact If you have any
+questions about FunASR, please contact us by - email: [funasr@list.alibaba-
+inc.com](funasr@list.alibaba-inc.com) |Dingding group | Wechat group | |:---:|:
+-----------------------------------------------------:| |
 [docs/images/dingding.jpg] | [docs/images/wechat.png]
 | ## Contributors |
 [docs/images/damo.png] |
 [docs/images/nwpu.png] | [docs/images/China_Telecom.png]
 | [docs/images/RapidAI.png]
 | [docs/images/aihealthx.png]
 | |:---------------------------------------------------------------:|:---------
```

### Comparing `funasr-0.6.5/README.md` & `funasr-0.6.6/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -30,17 +30,17 @@
 - We have released a vast collection of academic and industrial pretrained models on the [ModelScope](https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition), which can be accessed through our [Model Zoo](https://github.com/alibaba-damo-academy/FunASR/blob/main/docs/model_zoo/modelscope_models.md). The representative [Paraformer-large](https://www.modelscope.cn/models/damo/speech_paraformer-large_asr_nat-zh-cn-16k-common-vocab8404-pytorch/summary) model has achieved SOTA performance in many speech recognition tasks. 
 - FunASR offers a user-friendly pipeline for fine-tuning pretrained models from the [ModelScope](https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition). Additionally, the optimized dataloader in FunASR enables faster training speeds for large-scale datasets. This feature enhances the efficiency of the speech recognition process for researchers and practitioners.
 
 ## Installation
 
 Install from pip
 ```shell
-pip install -U funasr
+pip3 install -U funasr
 # For the users in China, you could install with the command:
-# pip install -U funasr -i https://mirror.sjtu.edu.cn/pypi/web/simple
+# pip3 install -U funasr -i https://mirror.sjtu.edu.cn/pypi/web/simple
 ```
 
 Or install from source code
 
 
 ``` sh
 git clone https://github.com/alibaba/FunASR.git && cd FunASR
@@ -95,21 +95,22 @@
 
 ### runtime
 
 An example with websocket:
 
 For the server:
 ```shell
+cd funasr/runtime/python/websocket
 python wss_srv_asr.py --port 10095
 ```
 
 For the client:
 ```shell
-python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --chunk_size "5,10,5"
-#python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results"
+python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size "5,10,5"
+#python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results"
 ```
 More examples could be found in [docs](https://alibaba-damo-academy.github.io/FunASR/en/runtime/websocket_python.html#id2)
 ## Contact
 
 If you have any questions about FunASR, please contact us by
 
 - email: [funasr@list.alibaba-inc.com](funasr@list.alibaba-inc.com)
```

#### html2text {}

```diff
@@ -39,16 +39,16 @@
 large_asr_nat-zh-cn-16k-common-vocab8404-pytorch/summary) model has achieved
 SOTA performance in many speech recognition tasks. - FunASR offers a user-
 friendly pipeline for fine-tuning pretrained models from the [ModelScope]
 (https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition).
 Additionally, the optimized dataloader in FunASR enables faster training speeds
 for large-scale datasets. This feature enhances the efficiency of the speech
 recognition process for researchers and practitioners. ## Installation Install
-from pip ```shell pip install -U funasr # For the users in China, you could
-install with the command: # pip install -U funasr -i https://
+from pip ```shell pip3 install -U funasr # For the users in China, you could
+install with the command: # pip3 install -U funasr -i https://
 mirror.sjtu.edu.cn/pypi/web/simple ``` Or install from source code ``` sh git
 clone https://github.com/alibaba/FunASR.git && cd FunASR pip3 install -e ./ #
 For the users in China, you could install with the command: # pip3 install -
 e ./ -i https://mirror.sjtu.edu.cn/pypi/web/simple ``` If you want to use the
 pretrained models in ModelScope, you should install the modelscope: ```shell
 pip3 install -U modelscope # For the users in China, you could install with the
 command: # pip3 install -U modelscope -f https://modelscope.oss-cn-
@@ -67,24 +67,24 @@
 ( task=Tasks.auto_speech_recognition, model='damo/speech_paraformer-
 large_asr_nat-zh-cn-16k-common-vocab8404-pytorch', ) rec_result =
 inference_pipeline(audio_in='https://isv-data.oss-cn-hangzhou.aliyuncs.com/ics/
 MaaS/ASR/test_audio/asr_example_zh.wav') print(rec_result) # {'text':
 'æ¬¢è¿å¤§å®¶æ¥ä½éªè¾¾æ©é¢æ¨åºçè¯­é³è¯å«æ¨¡å'} ``` More examples
 could be found in [docs](https://alibaba-damo-academy.github.io/FunASR/en/
 modelscope_pipeline/quick_start.html) ### runtime An example with websocket:
-For the server: ```shell python wss_srv_asr.py --port 10095 ``` For the client:
-```shell python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --
-chunk_size "5,10,5" #python wss_client_asr.py --host "0.0.0.0" --port 10095 --
-mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./
-results" ``` More examples could be found in [docs](https://alibaba-damo-
-academy.github.io/FunASR/en/runtime/websocket_python.html#id2) ## Contact If
-you have any questions about FunASR, please contact us by - email:
-[funasr@list.alibaba-inc.com](funasr@list.alibaba-inc.com) |Dingding group |
-Wechat group | |:---:|:-----------------------------------------------------:
-| |
+For the server: ```shell cd funasr/runtime/python/websocket python
+wss_srv_asr.py --port 10095 ``` For the client: ```shell python
+wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size
+"5,10,5" #python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass
+--chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results" ```
+More examples could be found in [docs](https://alibaba-damo-academy.github.io/
+FunASR/en/runtime/websocket_python.html#id2) ## Contact If you have any
+questions about FunASR, please contact us by - email: [funasr@list.alibaba-
+inc.com](funasr@list.alibaba-inc.com) |Dingding group | Wechat group | |:---:|:
+-----------------------------------------------------:| |
 [docs/images/dingding.jpg] | [docs/images/wechat.png]
 | ## Contributors |
 [docs/images/damo.png] |
 [docs/images/nwpu.png] | [docs/images/China_Telecom.png]
 | [docs/images/RapidAI.png]
 | [docs/images/aihealthx.png]
 | |:---------------------------------------------------------------:|:---------
```

### Comparing `funasr-0.6.5/funasr/bin/aggregate_stats_dirs.py` & `funasr-0.6.6/funasr/bin/aggregate_stats_dirs.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/asr_infer.py` & `funasr-0.6.6/funasr/bin/asr_infer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/asr_inference_launch.py` & `funasr-0.6.6/funasr/bin/asr_inference_launch.py`

 * *Files 0% similar despite different names*

```diff
@@ -863,15 +863,18 @@
         if data_path_and_name_and_type is not None and data_path_and_name_and_type[2] == "bytes":
             raw_inputs = _load_bytes(data_path_and_name_and_type[0])
             raw_inputs = torch.tensor(raw_inputs)
         if data_path_and_name_and_type is not None and data_path_and_name_and_type[2] == "sound":
             try:
                 raw_inputs = torchaudio.load(data_path_and_name_and_type[0])[0][0]
             except:
-                raw_inputs = torch.tensor(soundfile.read(data_path_and_name_and_type[0])[0])
+                raw_inputs = soundfile.read(data_path_and_name_and_type[0], dtype='float32')[0]
+                if raw_inputs.ndim == 2:
+                    raw_inputs = raw_inputs[:, 0]
+                raw_inputs = torch.tensor(raw_inputs)
         if data_path_and_name_and_type is None and raw_inputs is not None:
             if isinstance(raw_inputs, np.ndarray):
                 raw_inputs = torch.tensor(raw_inputs)
         is_final = False
         cache = {}
         chunk_size = [5, 10, 5]
         if param_dict is not None and "cache" in param_dict:
```

### Comparing `funasr-0.6.5/funasr/bin/asr_train.py` & `funasr-0.6.6/funasr/bin/asr_train.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/build_trainer.py` & `funasr-0.6.6/funasr/bin/build_trainer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/data2vec_train.py` & `funasr-0.6.6/funasr/bin/data2vec_train.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/diar_infer.py` & `funasr-0.6.6/funasr/bin/diar_infer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/diar_inference_launch.py` & `funasr-0.6.6/funasr/bin/diar_inference_launch.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/diar_train.py` & `funasr-0.6.6/funasr/bin/diar_train.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/lm_inference_launch.py` & `funasr-0.6.6/funasr/bin/lm_inference_launch.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/lm_train.py` & `funasr-0.6.6/funasr/bin/lm_train.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/punc_infer.py` & `funasr-0.6.6/funasr/bin/punc_infer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/punc_inference_launch.py` & `funasr-0.6.6/funasr/bin/punc_inference_launch.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/punc_train.py` & `funasr-0.6.6/funasr/bin/punc_train.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/sa_asr_train.py` & `funasr-0.6.6/funasr/bin/sa_asr_train.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/sv_infer.py` & `funasr-0.6.6/funasr/bin/sv_infer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/sv_inference_launch.py` & `funasr-0.6.6/funasr/bin/sv_inference_launch.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/tokenize_text.py` & `funasr-0.6.6/funasr/bin/tokenize_text.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/tp_infer.py` & `funasr-0.6.6/funasr/bin/tp_infer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/tp_inference_launch.py` & `funasr-0.6.6/funasr/bin/tp_inference_launch.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/train.py` & `funasr-0.6.6/funasr/bin/train.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/vad_infer.py` & `funasr-0.6.6/funasr/bin/vad_infer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/bin/vad_inference_launch.py` & `funasr-0.6.6/funasr/bin/vad_inference_launch.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_args.py` & `funasr-0.6.6/funasr/build_utils/build_args.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_asr_model.py` & `funasr-0.6.6/funasr/build_utils/build_asr_model.py`

 * *Files 2% similar despite different names*

```diff
@@ -404,18 +404,23 @@
             encoder2=encoder2,
             decoder2=decoder2,
             predictor2=predictor2,
             stride_conv=stride_conv,
             **args.model_conf,
         )
     elif args.model == "timestamp_prediction":
+        # predictor
+        predictor_class = predictor_choices.get_class(args.predictor)
+        predictor = predictor_class(**args.predictor_conf)
+        
         model_class = model_choices.get_class(args.model)
         model = model_class(
             frontend=frontend,
             encoder=encoder,
+            predictor=predictor,
             token_list=token_list,
             **args.model_conf,
         )
     elif args.model == "rnnt" or args.model == "rnnt_unified":
         # 5. Decoder
         encoder_output_size = encoder.output_size()
```

### Comparing `funasr-0.6.5/funasr/build_utils/build_dataloader.py` & `funasr-0.6.6/funasr/build_utils/build_dataloader.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_diar_model.py` & `funasr-0.6.6/funasr/build_utils/build_diar_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_distributed.py` & `funasr-0.6.6/funasr/build_utils/build_distributed.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_lm_model.py` & `funasr-0.6.6/funasr/build_utils/build_lm_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_model.py` & `funasr-0.6.6/funasr/build_utils/build_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_model_from_file.py` & `funasr-0.6.6/funasr/build_utils/build_model_from_file.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_optimizer.py` & `funasr-0.6.6/funasr/build_utils/build_optimizer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_pretrain_model.py` & `funasr-0.6.6/funasr/build_utils/build_pretrain_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_punc_model.py` & `funasr-0.6.6/funasr/build_utils/build_punc_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_scheduler.py` & `funasr-0.6.6/funasr/build_utils/build_scheduler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_streaming_iterator.py` & `funasr-0.6.6/funasr/build_utils/build_streaming_iterator.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_sv_model.py` & `funasr-0.6.6/funasr/build_utils/build_sv_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_trainer.py` & `funasr-0.6.6/funasr/build_utils/build_trainer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/build_utils/build_vad_model.py` & `funasr-0.6.6/funasr/build_utils/build_vad_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/collate_fn.py` & `funasr-0.6.6/funasr/datasets/collate_fn.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/dataset.py` & `funasr-0.6.6/funasr/datasets/dataset.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/iterable_dataset.py` & `funasr-0.6.6/funasr/datasets/iterable_dataset.py`

 * *Files 2% similar despite different names*

```diff
@@ -67,15 +67,18 @@
         bytes = f.read()
     return load_bytes(bytes)
 
 def load_wav(input):
     try:
         return torchaudio.load(input)[0].numpy()
     except:
-        return np.expand_dims(soundfile.read(input)[0], axis=0)
+        waveform, _ = soundfile.read(input, dtype='float32')
+        if waveform.ndim == 2:
+            waveform = waveform[:, 0]
+        return np.expand_dims(waveform, axis=0)
 
 DATA_TYPES = {
     "sound": load_wav,
     "pcm": load_pcm,
     "kaldi_ark": load_kaldi,
     "bytes": load_bytes,
     "waveform": lambda x: x,
```

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/build_dataloader.py` & `funasr-0.6.6/funasr/datasets/large_datasets/build_dataloader.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/datapipes/batch.py` & `funasr-0.6.6/funasr/datasets/large_datasets/datapipes/batch.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/datapipes/filter.py` & `funasr-0.6.6/funasr/datasets/large_datasets/datapipes/filter.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/dataset.py` & `funasr-0.6.6/funasr/datasets/large_datasets/dataset.py`

 * *Files 2% similar despite different names*

```diff
@@ -124,15 +124,17 @@
                         if data_name == "speech":
                             sample_dict["key"] = key
                     elif data_type == "sound":
                         key, path = item.strip().split()
                         try:
                             waveform, sampling_rate = torchaudio.load(path)
                         except:
-                            waveform, sampling_rate = soundfile.read(path)
+                            waveform, sampling_rate = soundfile.read(path, dtype='float32')
+                            if waveform.ndim == 2:
+                                waveform = waveform[:, 0]
                             waveform = np.expand_dims(waveform, axis=0)
                             waveform = torch.tensor(waveform)
                         if self.frontend_conf is not None:
                             if sampling_rate != self.frontend_conf["fs"]:
                                 waveform = torchaudio.transforms.Resample(orig_freq=sampling_rate,
                                                                           new_freq=self.frontend_conf["fs"])(waveform)
                                 sampling_rate = self.frontend_conf["fs"]
```

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/utils/clipping.py` & `funasr-0.6.6/funasr/datasets/large_datasets/utils/clipping.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/utils/filter.py` & `funasr-0.6.6/funasr/datasets/large_datasets/utils/filter.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/utils/hotword_utils.py` & `funasr-0.6.6/funasr/datasets/large_datasets/utils/hotword_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/utils/low_frame_rate.py` & `funasr-0.6.6/funasr/datasets/large_datasets/utils/low_frame_rate.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/utils/padding.py` & `funasr-0.6.6/funasr/datasets/large_datasets/utils/padding.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/large_datasets/utils/tokenize.py` & `funasr-0.6.6/funasr/datasets/large_datasets/utils/tokenize.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/ms_dataset.py` & `funasr-0.6.6/funasr/datasets/ms_dataset.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/preprocessor.py` & `funasr-0.6.6/funasr/datasets/preprocessor.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/small_datasets/collate_fn.py` & `funasr-0.6.6/funasr/datasets/small_datasets/collate_fn.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/small_datasets/dataset.py` & `funasr-0.6.6/funasr/datasets/small_datasets/dataset.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/small_datasets/length_batch_sampler.py` & `funasr-0.6.6/funasr/datasets/small_datasets/length_batch_sampler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/small_datasets/preprocessor.py` & `funasr-0.6.6/funasr/datasets/small_datasets/preprocessor.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/datasets/small_datasets/sequence_iter_factory.py` & `funasr-0.6.6/funasr/datasets/small_datasets/sequence_iter_factory.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/export_model.py` & `funasr-0.6.6/funasr/export/export_model.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,14 +20,15 @@
         cache_dir: Union[Path, str] = None,
         onnx: bool = True,
         device: str = "cpu",
         quant: bool = True,
         fallback_num: int = 0,
         audio_in: str = None,
         calib_num: int = 200,
+        model_revision: str = None,
     ):
         assert check_argument_types()
         self.set_all_random_seed(0)
 
         self.cache_dir = cache_dir
         self.export_config = dict(
             feats_dim=560,
@@ -37,14 +38,15 @@
         self.onnx = onnx
         self.device = device
         self.quant = quant
         self.fallback_num = fallback_num
         self.frontend = None
         self.audio_in = audio_in
         self.calib_num = calib_num
+        self.model_revision = model_revision
         
 
     def _export(
         self,
         model,
         tag_name: str = None,
         verbose: bool = False,
@@ -167,15 +169,15 @@
                tag_name: str = 'damo/speech_paraformer-large_asr_nat-zh-cn-16k-common-vocab8404-pytorch',
                mode: str = None,
                ):
         
         model_dir = tag_name
         if model_dir.startswith('damo'):
             from modelscope.hub.snapshot_download import snapshot_download
-            model_dir = snapshot_download(model_dir, cache_dir=self.cache_dir)
+            model_dir = snapshot_download(model_dir, cache_dir=self.cache_dir, revision=self.model_revision)
         self.cache_dir = model_dir
 
         if mode is None:
             import json
             json_file = os.path.join(model_dir, 'configuration.json')
             with open(json_file, 'r') as f:
                 config_data = json.load(f)
@@ -267,19 +269,21 @@
     parser.add_argument('--export-dir', type=str, required=True)
     parser.add_argument('--type', type=str, default='onnx', help='["onnx", "torch"]')
     parser.add_argument('--device', type=str, default='cpu', help='["cpu", "cuda"]')
     parser.add_argument('--quantize', type=str2bool, default=False, help='export quantized model')
     parser.add_argument('--fallback-num', type=int, default=0, help='amp fallback number')
     parser.add_argument('--audio_in', type=str, default=None, help='["wav", "wav.scp"]')
     parser.add_argument('--calib_num', type=int, default=200, help='calib max num')
+    parser.add_argument('--model_revision', type=str, default=None, help='model_revision')
     args = parser.parse_args()
 
     export_model = ModelExport(
         cache_dir=args.export_dir,
         onnx=args.type == 'onnx',
         device=args.device,
         quant=args.quantize,
         fallback_num=args.fallback_num,
         audio_in=args.audio_in,
         calib_num=args.calib_num,
+        model_revision=args.model_revision,
     )
     export_model.export(args.model_name)
```

### Comparing `funasr-0.6.5/funasr/export/models/CT_Transformer.py` & `funasr-0.6.6/funasr/export/models/CT_Transformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/__init__.py` & `funasr-0.6.6/funasr/export/models/__init__.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/decoder/sanm_decoder.py` & `funasr-0.6.6/funasr/export/models/decoder/sanm_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/decoder/transformer_decoder.py` & `funasr-0.6.6/funasr/export/models/decoder/transformer_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/e2e_asr_paraformer.py` & `funasr-0.6.6/funasr/export/models/e2e_asr_paraformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/e2e_vad.py` & `funasr-0.6.6/funasr/export/models/e2e_vad.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/encoder/conformer_encoder.py` & `funasr-0.6.6/funasr/export/models/encoder/conformer_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/encoder/fsmn_encoder.py` & `funasr-0.6.6/funasr/export/models/encoder/fsmn_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/encoder/sanm_encoder.py` & `funasr-0.6.6/funasr/export/models/encoder/sanm_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/modules/decoder_layer.py` & `funasr-0.6.6/funasr/export/models/modules/decoder_layer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/modules/encoder_layer.py` & `funasr-0.6.6/funasr/export/models/modules/encoder_layer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/modules/feedforward.py` & `funasr-0.6.6/funasr/export/models/modules/feedforward.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/modules/multihead_att.py` & `funasr-0.6.6/funasr/export/models/modules/multihead_att.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/models/predictor/cif.py` & `funasr-0.6.6/funasr/export/models/predictor/cif.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/test/test_onnx.py` & `funasr-0.6.6/funasr/export/test/test_onnx.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/test/test_onnx_punc.py` & `funasr-0.6.6/funasr/export/test/test_onnx_punc.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/test/test_onnx_punc_vadrealtime.py` & `funasr-0.6.6/funasr/export/test/test_onnx_punc_vadrealtime.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/test/test_onnx_vad.py` & `funasr-0.6.6/funasr/export/test/test_onnx_vad.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/export/utils/torch_function.py` & `funasr-0.6.6/funasr/export/utils/torch_function.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/fileio/datadir_writer.py` & `funasr-0.6.6/funasr/fileio/datadir_writer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/fileio/npy_scp.py` & `funasr-0.6.6/funasr/fileio/npy_scp.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/fileio/rand_gen_dataset.py` & `funasr-0.6.6/funasr/fileio/rand_gen_dataset.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/fileio/read_text.py` & `funasr-0.6.6/funasr/fileio/read_text.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/iterators/chunk_iter_factory.py` & `funasr-0.6.6/funasr/iterators/chunk_iter_factory.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/iterators/multiple_iter_factory.py` & `funasr-0.6.6/funasr/iterators/multiple_iter_factory.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/iterators/sequence_iter_factory.py` & `funasr-0.6.6/funasr/iterators/sequence_iter_factory.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/complex_utils.py` & `funasr-0.6.6/funasr/layers/complex_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/global_mvn.py` & `funasr-0.6.6/funasr/layers/global_mvn.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/label_aggregation.py` & `funasr-0.6.6/funasr/layers/label_aggregation.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/log_mel.py` & `funasr-0.6.6/funasr/layers/log_mel.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/mask_along_axis.py` & `funasr-0.6.6/funasr/layers/mask_along_axis.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/sinc_conv.py` & `funasr-0.6.6/funasr/layers/sinc_conv.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/stft.py` & `funasr-0.6.6/funasr/layers/stft.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/time_warp.py` & `funasr-0.6.6/funasr/layers/time_warp.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/layers/utterance_mvn.py` & `funasr-0.6.6/funasr/layers/utterance_mvn.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/losses/label_smoothing_loss.py` & `funasr-0.6.6/funasr/losses/label_smoothing_loss.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/main_funcs/average_nbest_models.py` & `funasr-0.6.6/funasr/main_funcs/average_nbest_models.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/main_funcs/calculate_all_attentions.py` & `funasr-0.6.6/funasr/main_funcs/calculate_all_attentions.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/main_funcs/collect_stats.py` & `funasr-0.6.6/funasr/main_funcs/collect_stats.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/main_funcs/pack_funcs.py` & `funasr-0.6.6/funasr/main_funcs/pack_funcs.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/ctc.py` & `funasr-0.6.6/funasr/models/ctc.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/data2vec.py` & `funasr-0.6.6/funasr/models/data2vec.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/decoder/contextual_decoder.py` & `funasr-0.6.6/funasr/models/decoder/contextual_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/decoder/rnn_decoder.py` & `funasr-0.6.6/funasr/models/decoder/rnn_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/decoder/rnnt_decoder.py` & `funasr-0.6.6/funasr/models/decoder/rnnt_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/decoder/sanm_decoder.py` & `funasr-0.6.6/funasr/models/decoder/sanm_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/decoder/sv_decoder.py` & `funasr-0.6.6/funasr/models/decoder/sv_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/decoder/transformer_decoder.py` & `funasr-0.6.6/funasr/models/decoder/transformer_decoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_asr.py` & `funasr-0.6.6/funasr/models/e2e_asr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_asr_common.py` & `funasr-0.6.6/funasr/models/e2e_asr_common.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_asr_contextual_paraformer.py` & `funasr-0.6.6/funasr/models/e2e_asr_contextual_paraformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_asr_mfcca.py` & `funasr-0.6.6/funasr/models/e2e_asr_mfcca.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_asr_paraformer.py` & `funasr-0.6.6/funasr/models/e2e_asr_paraformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_asr_transducer.py` & `funasr-0.6.6/funasr/models/e2e_asr_transducer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_diar_eend_ola.py` & `funasr-0.6.6/funasr/models/e2e_diar_eend_ola.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_diar_sond.py` & `funasr-0.6.6/funasr/models/e2e_diar_sond.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_sa_asr.py` & `funasr-0.6.6/funasr/models/e2e_sa_asr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_sv.py` & `funasr-0.6.6/funasr/models/e2e_sv.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_tp.py` & `funasr-0.6.6/funasr/models/e2e_tp.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_uni_asr.py` & `funasr-0.6.6/funasr/models/e2e_uni_asr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/e2e_vad.py` & `funasr-0.6.6/funasr/models/e2e_vad.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/conformer_encoder.py` & `funasr-0.6.6/funasr/models/encoder/conformer_encoder.py`

 * *Files 2% similar despite different names*

```diff
@@ -1077,15 +1077,18 @@
                 x.size(1),
                 limit_size,
             )
 
         mask = make_source_mask(x_len).to(x.device)
 
         if self.unified_model_training:
-            chunk_size = self.default_chunk_size + torch.randint(-self.jitter_range, self.jitter_range+1, (1,)).item()
+            if self.training:
+                chunk_size = self.default_chunk_size + torch.randint(-self.jitter_range, self.jitter_range+1, (1,)).item()
+            else:
+                chunk_size = self.default_chunk_size
             x, mask = self.embed(x, mask, chunk_size)
             pos_enc = self.pos_enc(x)
             chunk_mask = make_chunk_mask(
                 x.size(1),
                 chunk_size,
                 left_chunk_size=self.left_chunk_size,
                 device=x.device,
@@ -1109,20 +1112,23 @@
                 x_chunk = x_chunk[:,::self.time_reduction_factor,:]
                 olens = torch.floor_divide(olens-1, self.time_reduction_factor) + 1
 
             return x_utt, x_chunk, olens
 
         elif self.dynamic_chunk_training:
             max_len = x.size(1)
-            chunk_size = torch.randint(1, max_len, (1,)).item()
+            if self.training:
+                chunk_size = torch.randint(1, max_len, (1,)).item()
 
-            if chunk_size > (max_len * self.short_chunk_threshold):
-                chunk_size = max_len
+                if chunk_size > (max_len * self.short_chunk_threshold):
+                    chunk_size = max_len
+                else:
+                    chunk_size = (chunk_size % self.short_chunk_size) + 1
             else:
-                chunk_size = (chunk_size % self.short_chunk_size) + 1
+                chunk_size = self.default_chunk_size
 
             x, mask = self.embed(x, mask, chunk_size)
             pos_enc = self.pos_enc(x)
 
             chunk_mask = make_chunk_mask(
                 x.size(1),
                 chunk_size,
@@ -1143,14 +1149,53 @@
         olens = mask.eq(0).sum(1)
         if self.time_reduction_factor > 1:
             x = x[:,::self.time_reduction_factor,:]
             olens = torch.floor_divide(olens-1, self.time_reduction_factor) + 1
 
         return x, olens, None
 
+    def full_utt_forward(
+        self,
+        x: torch.Tensor,
+        x_len: torch.Tensor,
+    ) -> Tuple[torch.Tensor, torch.Tensor]:
+        """Encode input sequences.
+        Args:
+            x: Encoder input features. (B, T_in, F)
+            x_len: Encoder input features lengths. (B,)
+        Returns:
+           x: Encoder outputs. (B, T_out, D_enc)
+           x_len: Encoder outputs lenghts. (B,)
+        """
+        short_status, limit_size = check_short_utt(
+            self.embed.subsampling_factor, x.size(1)
+        )
+
+        if short_status:
+            raise TooShortUttError(
+                f"has {x.size(1)} frames and is too short for subsampling "
+                + f"(it needs more than {limit_size} frames), return empty results",
+                x.size(1),
+                limit_size,
+            )
+
+        mask = make_source_mask(x_len).to(x.device)
+        x, mask = self.embed(x, mask, None)
+        pos_enc = self.pos_enc(x)
+        x_utt = self.encoders(
+            x,
+            pos_enc,
+            mask,
+            chunk_mask=None,
+        )
+
+        if self.time_reduction_factor > 1:
+            x_utt = x_utt[:,::self.time_reduction_factor,:]
+        return x_utt
+
     def simu_chunk_forward(
         self,
         x: torch.Tensor,
         x_len: torch.Tensor,
         chunk_size: int = 16,
         left_context: int = 32,
         right_context: int = 0,
```

### Comparing `funasr-0.6.5/funasr/models/encoder/data2vec_encoder.py` & `funasr-0.6.6/funasr/models/encoder/data2vec_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/ecapa_tdnn_encoder.py` & `funasr-0.6.6/funasr/models/encoder/ecapa_tdnn_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/encoder_layer_mfcca.py` & `funasr-0.6.6/funasr/models/encoder/encoder_layer_mfcca.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/fsmn_encoder.py` & `funasr-0.6.6/funasr/models/encoder/fsmn_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/mfcca_encoder.py` & `funasr-0.6.6/funasr/models/encoder/mfcca_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/opennmt_encoders/ci_scorers.py` & `funasr-0.6.6/funasr/models/encoder/opennmt_encoders/ci_scorers.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/opennmt_encoders/conv_encoder.py` & `funasr-0.6.6/funasr/models/encoder/opennmt_encoders/conv_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/opennmt_encoders/fsmn_encoder.py` & `funasr-0.6.6/funasr/models/encoder/opennmt_encoders/fsmn_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/opennmt_encoders/self_attention_encoder.py` & `funasr-0.6.6/funasr/models/encoder/opennmt_encoders/self_attention_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/resnet34_encoder.py` & `funasr-0.6.6/funasr/models/encoder/resnet34_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/rnn_encoder.py` & `funasr-0.6.6/funasr/models/encoder/rnn_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/sanm_encoder.py` & `funasr-0.6.6/funasr/models/encoder/sanm_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/encoder/transformer_encoder.py` & `funasr-0.6.6/funasr/models/encoder/transformer_encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/frontend/default.py` & `funasr-0.6.6/funasr/models/frontend/default.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/frontend/eend_ola_feature.py` & `funasr-0.6.6/funasr/models/frontend/eend_ola_feature.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/frontend/fused.py` & `funasr-0.6.6/funasr/models/frontend/fused.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/frontend/s3prl.py` & `funasr-0.6.6/funasr/models/frontend/s3prl.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/frontend/wav_frontend.py` & `funasr-0.6.6/funasr/models/frontend/wav_frontend.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/frontend/wav_frontend_kaldifeat.py` & `funasr-0.6.6/funasr/models/frontend/wav_frontend_kaldifeat.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/frontend/windowing.py` & `funasr-0.6.6/funasr/models/frontend/windowing.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/joint_net/joint_network.py` & `funasr-0.6.6/funasr/models/joint_net/joint_network.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/pooling/statistic_pooling.py` & `funasr-0.6.6/funasr/models/pooling/statistic_pooling.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/postencoder/hugging_face_transformers_postencoder.py` & `funasr-0.6.6/funasr/models/postencoder/hugging_face_transformers_postencoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/predictor/cif.py` & `funasr-0.6.6/funasr/models/predictor/cif.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/preencoder/linear.py` & `funasr-0.6.6/funasr/models/preencoder/linear.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/preencoder/sinc.py` & `funasr-0.6.6/funasr/models/preencoder/sinc.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/seq_rnn_lm.py` & `funasr-0.6.6/funasr/models/seq_rnn_lm.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/specaug/specaug.py` & `funasr-0.6.6/funasr/models/specaug/specaug.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/target_delay_transformer.py` & `funasr-0.6.6/funasr/models/target_delay_transformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/transformer_lm.py` & `funasr-0.6.6/funasr/models/transformer_lm.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/models/vad_realtime_transformer.py` & `funasr-0.6.6/funasr/models/vad_realtime_transformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/add_sos_eos.py` & `funasr-0.6.6/funasr/modules/add_sos_eos.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/attention.py` & `funasr-0.6.6/funasr/modules/attention.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/beam_search/batch_beam_search.py` & `funasr-0.6.6/funasr/modules/beam_search/batch_beam_search.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/beam_search/batch_beam_search_online_sim.py` & `funasr-0.6.6/funasr/modules/beam_search/batch_beam_search_online_sim.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/beam_search/beam_search.py` & `funasr-0.6.6/funasr/modules/beam_search/beam_search.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/beam_search/beam_search_sa_asr.py` & `funasr-0.6.6/funasr/modules/beam_search/beam_search_sa_asr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/beam_search/beam_search_transducer.py` & `funasr-0.6.6/funasr/modules/beam_search/beam_search_transducer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/data2vec/data_utils.py` & `funasr-0.6.6/funasr/modules/data2vec/data_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/data2vec/ema_module.py` & `funasr-0.6.6/funasr/modules/data2vec/ema_module.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/data2vec/multihead_attention.py` & `funasr-0.6.6/funasr/modules/data2vec/multihead_attention.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/data2vec/quant_noise.py` & `funasr-0.6.6/funasr/modules/data2vec/quant_noise.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/data2vec/utils.py` & `funasr-0.6.6/funasr/modules/data2vec/utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/data2vec/wav2vec2.py` & `funasr-0.6.6/funasr/modules/data2vec/wav2vec2.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/dynamic_conv.py` & `funasr-0.6.6/funasr/modules/dynamic_conv.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/dynamic_conv2d.py` & `funasr-0.6.6/funasr/modules/dynamic_conv2d.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/e2e_asr_common.py` & `funasr-0.6.6/funasr/modules/e2e_asr_common.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/eend_ola/encoder.py` & `funasr-0.6.6/funasr/modules/eend_ola/encoder.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/eend_ola/encoder_decoder_attractor.py` & `funasr-0.6.6/funasr/modules/eend_ola/encoder_decoder_attractor.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/eend_ola/utils/losses.py` & `funasr-0.6.6/funasr/modules/eend_ola/utils/losses.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/eend_ola/utils/power.py` & `funasr-0.6.6/funasr/modules/eend_ola/utils/power.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/eend_ola/utils/report.py` & `funasr-0.6.6/funasr/modules/eend_ola/utils/report.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/embedding.py` & `funasr-0.6.6/funasr/modules/embedding.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/frontends/beamformer.py` & `funasr-0.6.6/funasr/modules/frontends/beamformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/frontends/dnn_beamformer.py` & `funasr-0.6.6/funasr/modules/frontends/dnn_beamformer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/frontends/dnn_wpe.py` & `funasr-0.6.6/funasr/modules/frontends/dnn_wpe.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/frontends/feature_transform.py` & `funasr-0.6.6/funasr/modules/frontends/feature_transform.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/frontends/frontend.py` & `funasr-0.6.6/funasr/modules/frontends/frontend.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/frontends/mask_estimator.py` & `funasr-0.6.6/funasr/modules/frontends/mask_estimator.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/layer_norm.py` & `funasr-0.6.6/funasr/modules/layer_norm.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/lightconv.py` & `funasr-0.6.6/funasr/modules/lightconv.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/lightconv2d.py` & `funasr-0.6.6/funasr/modules/lightconv2d.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/mask.py` & `funasr-0.6.6/funasr/modules/mask.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/multi_layer_conv.py` & `funasr-0.6.6/funasr/modules/multi_layer_conv.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/nets_utils.py` & `funasr-0.6.6/funasr/modules/nets_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/positionwise_feed_forward.py` & `funasr-0.6.6/funasr/modules/positionwise_feed_forward.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/repeat.py` & `funasr-0.6.6/funasr/modules/repeat.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/rnn/argument.py` & `funasr-0.6.6/funasr/modules/rnn/argument.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/rnn/attentions.py` & `funasr-0.6.6/funasr/modules/rnn/attentions.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/rnn/decoders.py` & `funasr-0.6.6/funasr/modules/rnn/decoders.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/rnn/encoders.py` & `funasr-0.6.6/funasr/modules/rnn/encoders.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/scorers/ctc.py` & `funasr-0.6.6/funasr/modules/scorers/ctc.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/scorers/ctc_prefix_score.py` & `funasr-0.6.6/funasr/modules/scorers/ctc_prefix_score.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/scorers/length_bonus.py` & `funasr-0.6.6/funasr/modules/scorers/length_bonus.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/scorers/scorer_interface.py` & `funasr-0.6.6/funasr/modules/scorers/scorer_interface.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/streaming_utils/chunk_utilis.py` & `funasr-0.6.6/funasr/modules/streaming_utils/chunk_utilis.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/streaming_utils/load_fr_tf.py` & `funasr-0.6.6/funasr/modules/streaming_utils/load_fr_tf.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/streaming_utils/utils.py` & `funasr-0.6.6/funasr/modules/streaming_utils/utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/modules/subsampling.py` & `funasr-0.6.6/funasr/modules/subsampling.py`

 * *Files 4% similar despite different names*

```diff
@@ -423,31 +423,32 @@
 
     def __init__(
         self,
         input_size: int,
         conv_size: Union[int, Tuple],
         subsampling_factor: int = 4,
         vgg_like: bool = True,
+        conv_kernel_size: int = 3,
         output_size: Optional[int] = None,
     ) -> None:
         """Construct a ConvInput object."""
         super().__init__()
         if vgg_like:
             if subsampling_factor == 1:
                 conv_size1, conv_size2 = conv_size
 
                 self.conv = torch.nn.Sequential(
-                    torch.nn.Conv2d(1, conv_size1, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(1, conv_size1, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
-                    torch.nn.Conv2d(conv_size1, conv_size1, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(conv_size1, conv_size1, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
                     torch.nn.MaxPool2d((1, 2)),
-                    torch.nn.Conv2d(conv_size1, conv_size2, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(conv_size1, conv_size2, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
-                    torch.nn.Conv2d(conv_size2, conv_size2, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(conv_size2, conv_size2, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
                     torch.nn.MaxPool2d((1, 2)),
                 )
 
                 output_proj = conv_size2 * ((input_size // 2) // 2)
 
                 self.subsampling_factor = 1
@@ -458,22 +459,22 @@
 
             else:
                 conv_size1, conv_size2 = conv_size
 
                 kernel_1 = int(subsampling_factor / 2)
 
                 self.conv = torch.nn.Sequential(
-                    torch.nn.Conv2d(1, conv_size1, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(1, conv_size1, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
-                    torch.nn.Conv2d(conv_size1, conv_size1, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(conv_size1, conv_size1, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
                     torch.nn.MaxPool2d((kernel_1, 2)),
-                    torch.nn.Conv2d(conv_size1, conv_size2, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(conv_size1, conv_size2, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
-                    torch.nn.Conv2d(conv_size2, conv_size2, 3, stride=1, padding=1),
+                    torch.nn.Conv2d(conv_size2, conv_size2, conv_kernel_size, stride=1, padding=(conv_kernel_size-1)//2),
                     torch.nn.ReLU(),
                     torch.nn.MaxPool2d((2, 2)),
                 )
 
                 output_proj = conv_size2 * ((input_size // 2) // 2)
 
                 self.subsampling_factor = subsampling_factor
@@ -483,22 +484,22 @@
                 self.stride_1 = kernel_1
 
         else:
             if subsampling_factor == 1:
                 self.conv = torch.nn.Sequential(
                     torch.nn.Conv2d(1, conv_size, 3, [1,2], [1,0]),
                     torch.nn.ReLU(),
-                    torch.nn.Conv2d(conv_size, conv_size, 3, [1,2], [1,0]),
+                    torch.nn.Conv2d(conv_size, conv_size, conv_kernel_size, [1,2], [1,0]),
                     torch.nn.ReLU(),
                 )
 
                 output_proj = conv_size * (((input_size - 1) // 2 - 1) // 2)
 
                 self.subsampling_factor = subsampling_factor
-                self.kernel_2 = 3
+                self.kernel_2 = conv_kernel_size
                 self.stride_2 = 1
 
                 self.create_new_mask = self.create_new_conv2d_mask
 
             else:
                 kernel_2, stride_2, conv_2_output_size = sub_factor_to_params(
                     subsampling_factor,
```

### Comparing `funasr-0.6.5/funasr/modules/subsampling_without_posenc.py` & `funasr-0.6.6/funasr/modules/subsampling_without_posenc.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/optimizers/fairseq_adam.py` & `funasr-0.6.6/funasr/optimizers/fairseq_adam.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/optimizers/sgd.py` & `funasr-0.6.6/funasr/optimizers/sgd.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/demo.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/demo.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/paraformer_bin.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/paraformer_bin.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/compute_wer.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/compute_wer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/frontend.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/frontend.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/postprocess_utils.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/postprocess_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/timestamp_utils.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/timestamp_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/funasr_torch/utils/utils.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/funasr_torch/utils/utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/libtorch/setup.py` & `funasr-0.6.6/funasr/runtime/python/libtorch/setup.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_paraformer_offline.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_paraformer_offline.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_punc_offline.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_punc_offline.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_punc_online.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_punc_online.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/demo_vad_online.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/demo_vad_online.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/paraformer_bin.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/paraformer_bin.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/punc_bin.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/punc_bin.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/e2e_vad.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/e2e_vad.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/frontend.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/frontend.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/postprocess_utils.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/postprocess_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/timestamp_utils.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/timestamp_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/utils/utils.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/utils/utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/funasr_onnx/vad_bin.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/funasr_onnx/vad_bin.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/runtime/python/onnxruntime/setup.py` & `funasr-0.6.6/funasr/runtime/python/onnxruntime/setup.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/samplers/build_batch_sampler.py` & `funasr-0.6.6/funasr/samplers/build_batch_sampler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/samplers/folded_batch_sampler.py` & `funasr-0.6.6/funasr/samplers/folded_batch_sampler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/samplers/length_batch_sampler.py` & `funasr-0.6.6/funasr/samplers/length_batch_sampler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/samplers/num_elements_batch_sampler.py` & `funasr-0.6.6/funasr/samplers/num_elements_batch_sampler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/samplers/sorted_batch_sampler.py` & `funasr-0.6.6/funasr/samplers/sorted_batch_sampler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/samplers/unsorted_batch_sampler.py` & `funasr-0.6.6/funasr/samplers/unsorted_batch_sampler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/schedulers/abs_scheduler.py` & `funasr-0.6.6/funasr/schedulers/abs_scheduler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/schedulers/noam_lr.py` & `funasr-0.6.6/funasr/schedulers/noam_lr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/schedulers/tri_stage_scheduler.py` & `funasr-0.6.6/funasr/schedulers/tri_stage_scheduler.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/schedulers/warmup_lr.py` & `funasr-0.6.6/funasr/schedulers/warmup_lr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/abs_task.py` & `funasr-0.6.6/funasr/tasks/abs_task.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/asr.py` & `funasr-0.6.6/funasr/tasks/asr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/data2vec.py` & `funasr-0.6.6/funasr/tasks/data2vec.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/diar.py` & `funasr-0.6.6/funasr/tasks/diar.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/lm.py` & `funasr-0.6.6/funasr/tasks/lm.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/punctuation.py` & `funasr-0.6.6/funasr/tasks/punctuation.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/sa_asr.py` & `funasr-0.6.6/funasr/tasks/sa_asr.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/sv.py` & `funasr-0.6.6/funasr/tasks/sv.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/tasks/vad.py` & `funasr-0.6.6/funasr/tasks/vad.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/build_tokenizer.py` & `funasr-0.6.6/funasr/text/build_tokenizer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/char_tokenizer.py` & `funasr-0.6.6/funasr/text/char_tokenizer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/cleaner.py` & `funasr-0.6.6/funasr/text/cleaner.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/korean_cleaner.py` & `funasr-0.6.6/funasr/text/korean_cleaner.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/phoneme_tokenizer.py` & `funasr-0.6.6/funasr/text/phoneme_tokenizer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/sentencepiece_tokenizer.py` & `funasr-0.6.6/funasr/text/sentencepiece_tokenizer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/token_id_converter.py` & `funasr-0.6.6/funasr/text/token_id_converter.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/text/word_tokenizer.py` & `funasr-0.6.6/funasr/text/word_tokenizer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/torch_utils/add_gradient_noise.py` & `funasr-0.6.6/funasr/torch_utils/add_gradient_noise.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/torch_utils/device_funcs.py` & `funasr-0.6.6/funasr/torch_utils/device_funcs.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/torch_utils/forward_adaptor.py` & `funasr-0.6.6/funasr/torch_utils/forward_adaptor.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/torch_utils/initialize.py` & `funasr-0.6.6/funasr/torch_utils/initialize.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/torch_utils/load_pretrained_model.py` & `funasr-0.6.6/funasr/torch_utils/load_pretrained_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/torch_utils/model_summary.py` & `funasr-0.6.6/funasr/torch_utils/model_summary.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/torch_utils/recursive_op.py` & `funasr-0.6.6/funasr/torch_utils/recursive_op.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/train/abs_model.py` & `funasr-0.6.6/funasr/train/abs_model.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/train/class_choices.py` & `funasr-0.6.6/funasr/train/class_choices.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/train/distributed_utils.py` & `funasr-0.6.6/funasr/train/distributed_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/train/reporter.py` & `funasr-0.6.6/funasr/train/reporter.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/train/trainer.py` & `funasr-0.6.6/funasr/train/trainer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/asr_env_checking.py` & `funasr-0.6.6/funasr/utils/asr_env_checking.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/asr_utils.py` & `funasr-0.6.6/funasr/utils/asr_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/build_dataclass.py` & `funasr-0.6.6/funasr/utils/build_dataclass.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/cli_utils.py` & `funasr-0.6.6/funasr/utils/cli_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/compute_eer.py` & `funasr-0.6.6/funasr/utils/compute_eer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/compute_min_dcf.py` & `funasr-0.6.6/funasr/utils/compute_min_dcf.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/compute_wer.py` & `funasr-0.6.6/funasr/utils/compute_wer.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/config_argparse.py` & `funasr-0.6.6/funasr/utils/config_argparse.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/get_default_kwargs.py` & `funasr-0.6.6/funasr/utils/get_default_kwargs.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/griffin_lim.py` & `funasr-0.6.6/funasr/utils/griffin_lim.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/job_runner.py` & `funasr-0.6.6/funasr/utils/job_runner.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/misc.py` & `funasr-0.6.6/funasr/utils/misc.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/modelscope_param.py` & `funasr-0.6.6/funasr/utils/modelscope_param.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/modelscope_utils.py` & `funasr-0.6.6/funasr/utils/modelscope_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/nested_dict_action.py` & `funasr-0.6.6/funasr/utils/nested_dict_action.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/postprocess_utils.py` & `funasr-0.6.6/funasr/utils/postprocess_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/prepare_data.py` & `funasr-0.6.6/funasr/utils/prepare_data.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/sized_dict.py` & `funasr-0.6.6/funasr/utils/sized_dict.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/timestamp_tools.py` & `funasr-0.6.6/funasr/utils/timestamp_tools.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/types.py` & `funasr-0.6.6/funasr/utils/types.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/vad_utils.py` & `funasr-0.6.6/funasr/utils/vad_utils.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/funasr/utils/wav_utils.py` & `funasr-0.6.6/funasr/utils/wav_utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -162,15 +162,17 @@
         waveform = ndarray_resample(waveform, audio_sr, model_sr)
         waveform = torch.from_numpy(waveform.reshape(1, -1))
     else:
         # load pcm from wav, and resample
         try:
             waveform, audio_sr = torchaudio.load(wav_file)
         except:
-            waveform, audio_sr = soundfile.read(wav_file)
+            waveform, audio_sr = soundfile.read(wav_file, dtype='float32')
+            if waveform.ndim == 2:
+                waveform = waveform[:, 0]
             waveform = torch.tensor(np.expand_dims(waveform, axis=0))
         waveform = waveform * (1 << 15)
         waveform = torch_resample(waveform, audio_sr, model_sr)
 
     mat = kaldi.fbank(waveform,
                       num_mel_bins=num_mel_bins,
                       frame_length=frame_length,
@@ -183,17 +185,17 @@
     input_feats = mat
 
     return input_feats
 
 
 def wav2num_frame(wav_path, frontend_conf):
     try:
-        waveform, audio_sr = torchaudio.load(wav_file)
+        waveform, sampling_rate = torchaudio.load(wav_path)
     except:
-        waveform, audio_sr = soundfile.read(wav_file)
+        waveform, sampling_rate = soundfile.read(wav_path)
         waveform = torch.tensor(np.expand_dims(waveform, axis=0))
     speech_length = (waveform.shape[1] / sampling_rate) * 1000.
     n_frames = (waveform.shape[1] * 1000.0) / (sampling_rate * frontend_conf["frame_shift"] * frontend_conf["lfr_n"])
     feature_dim = frontend_conf["n_mels"] * frontend_conf["lfr_m"]
     return n_frames, feature_dim, speech_length
```

### Comparing `funasr-0.6.5/funasr.egg-info/PKG-INFO` & `funasr-0.6.6/funasr.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: funasr
-Version: 0.6.5
+Version: 0.6.6
 Summary: FunASR: A Fundamental End-to-End Speech Recognition Toolkit
 Home-page: https://github.com/alibaba-damo-academy/FunASR.git
 Author: Speech Lab of DAMO Academy, Alibaba Group
 Author-email: funasr@list.alibaba-inc.com
 License: The MIT License
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
@@ -56,17 +56,17 @@
 - We have released a vast collection of academic and industrial pretrained models on the [ModelScope](https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition), which can be accessed through our [Model Zoo](https://github.com/alibaba-damo-academy/FunASR/blob/main/docs/model_zoo/modelscope_models.md). The representative [Paraformer-large](https://www.modelscope.cn/models/damo/speech_paraformer-large_asr_nat-zh-cn-16k-common-vocab8404-pytorch/summary) model has achieved SOTA performance in many speech recognition tasks. 
 - FunASR offers a user-friendly pipeline for fine-tuning pretrained models from the [ModelScope](https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition). Additionally, the optimized dataloader in FunASR enables faster training speeds for large-scale datasets. This feature enhances the efficiency of the speech recognition process for researchers and practitioners.
 
 ## Installation
 
 Install from pip
 ```shell
-pip install -U funasr
+pip3 install -U funasr
 # For the users in China, you could install with the command:
-# pip install -U funasr -i https://mirror.sjtu.edu.cn/pypi/web/simple
+# pip3 install -U funasr -i https://mirror.sjtu.edu.cn/pypi/web/simple
 ```
 
 Or install from source code
 
 
 ``` sh
 git clone https://github.com/alibaba/FunASR.git && cd FunASR
@@ -121,21 +121,22 @@
 
 ### runtime
 
 An example with websocket:
 
 For the server:
 ```shell
+cd funasr/runtime/python/websocket
 python wss_srv_asr.py --port 10095
 ```
 
 For the client:
 ```shell
-python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --chunk_size "5,10,5"
-#python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results"
+python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size "5,10,5"
+#python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results"
 ```
 More examples could be found in [docs](https://alibaba-damo-academy.github.io/FunASR/en/runtime/websocket_python.html#id2)
 ## Contact
 
 If you have any questions about FunASR, please contact us by
 
 - email: [funasr@list.alibaba-inc.com](funasr@list.alibaba-inc.com)
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: funasr Version: 0.6.5 Summary: FunASR: A
+Metadata-Version: 2.1 Name: funasr Version: 0.6.6 Summary: FunASR: A
 Fundamental End-to-End Speech Recognition Toolkit Home-page: https://
 github.com/alibaba-damo-academy/FunASR.git Author: Speech Lab of DAMO Academy,
 Alibaba Group Author-email: funasr@list.alibaba-inc.com License: The MIT
 License Classifier: Programming Language :: Python Classifier: Programming
 Language :: Python :: 3 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8 Classifier: Programming
 Language :: Python :: 3.9 Classifier: Development Status :: 5 - Production/
@@ -52,16 +52,16 @@
 large_asr_nat-zh-cn-16k-common-vocab8404-pytorch/summary) model has achieved
 SOTA performance in many speech recognition tasks. - FunASR offers a user-
 friendly pipeline for fine-tuning pretrained models from the [ModelScope]
 (https://www.modelscope.cn/models?page=1&tasks=auto-speech-recognition).
 Additionally, the optimized dataloader in FunASR enables faster training speeds
 for large-scale datasets. This feature enhances the efficiency of the speech
 recognition process for researchers and practitioners. ## Installation Install
-from pip ```shell pip install -U funasr # For the users in China, you could
-install with the command: # pip install -U funasr -i https://
+from pip ```shell pip3 install -U funasr # For the users in China, you could
+install with the command: # pip3 install -U funasr -i https://
 mirror.sjtu.edu.cn/pypi/web/simple ``` Or install from source code ``` sh git
 clone https://github.com/alibaba/FunASR.git && cd FunASR pip3 install -e ./ #
 For the users in China, you could install with the command: # pip3 install -
 e ./ -i https://mirror.sjtu.edu.cn/pypi/web/simple ``` If you want to use the
 pretrained models in ModelScope, you should install the modelscope: ```shell
 pip3 install -U modelscope # For the users in China, you could install with the
 command: # pip3 install -U modelscope -f https://modelscope.oss-cn-
@@ -80,24 +80,24 @@
 ( task=Tasks.auto_speech_recognition, model='damo/speech_paraformer-
 large_asr_nat-zh-cn-16k-common-vocab8404-pytorch', ) rec_result =
 inference_pipeline(audio_in='https://isv-data.oss-cn-hangzhou.aliyuncs.com/ics/
 MaaS/ASR/test_audio/asr_example_zh.wav') print(rec_result) # {'text':
 'æ¬¢è¿å¤§å®¶æ¥ä½éªè¾¾æ©é¢æ¨åºçè¯­é³è¯å«æ¨¡å'} ``` More examples
 could be found in [docs](https://alibaba-damo-academy.github.io/FunASR/en/
 modelscope_pipeline/quick_start.html) ### runtime An example with websocket:
-For the server: ```shell python wss_srv_asr.py --port 10095 ``` For the client:
-```shell python wss_client_asr.py --host "0.0.0.0" --port 10095 --mode 2pass --
-chunk_size "5,10,5" #python wss_client_asr.py --host "0.0.0.0" --port 10095 --
-mode 2pass --chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./
-results" ``` More examples could be found in [docs](https://alibaba-damo-
-academy.github.io/FunASR/en/runtime/websocket_python.html#id2) ## Contact If
-you have any questions about FunASR, please contact us by - email:
-[funasr@list.alibaba-inc.com](funasr@list.alibaba-inc.com) |Dingding group |
-Wechat group | |:---:|:-----------------------------------------------------:
-| |
+For the server: ```shell cd funasr/runtime/python/websocket python
+wss_srv_asr.py --port 10095 ``` For the client: ```shell python
+wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass --chunk_size
+"5,10,5" #python wss_client_asr.py --host "127.0.0.1" --port 10095 --mode 2pass
+--chunk_size "8,8,4" --audio_in "./data/wav.scp" --output_dir "./results" ```
+More examples could be found in [docs](https://alibaba-damo-academy.github.io/
+FunASR/en/runtime/websocket_python.html#id2) ## Contact If you have any
+questions about FunASR, please contact us by - email: [funasr@list.alibaba-
+inc.com](funasr@list.alibaba-inc.com) |Dingding group | Wechat group | |:---:|:
+-----------------------------------------------------:| |
 [docs/images/dingding.jpg] | [docs/images/wechat.png]
 | ## Contributors |
 [docs/images/damo.png] |
 [docs/images/nwpu.png] | [docs/images/China_Telecom.png]
 | [docs/images/RapidAI.png]
 | [docs/images/aihealthx.png]
 | |:---------------------------------------------------------------:|:---------
```

### Comparing `funasr-0.6.5/funasr.egg-info/SOURCES.txt` & `funasr-0.6.6/funasr.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -359,19 +359,21 @@
 funasr/utils/kwargs2args.py
 funasr/utils/misc.py
 funasr/utils/modelscope_param.py
 funasr/utils/modelscope_utils.py
 funasr/utils/nested_dict_action.py
 funasr/utils/postprocess_utils.py
 funasr/utils/prepare_data.py
+funasr/utils/runtime_sdk_download_tool.py
 funasr/utils/sized_dict.py
 funasr/utils/timestamp_tools.py
 funasr/utils/types.py
 funasr/utils/vad_utils.py
 funasr/utils/wav_utils.py
 funasr/utils/yaml_no_alias_safe_dump.py
 tests/test_asr_inference_pipeline.py
 tests/test_asr_vad_punc_inference_pipeline.py
 tests/test_lm_pipeline.py
 tests/test_punctuation_pipeline.py
 tests/test_sv_inference_pipeline.py
+tests/test_tp_pipeline.py
 tests/test_vad_inference_pipeline.py
```

### Comparing `funasr-0.6.5/funasr.egg-info/requires.txt` & `funasr-0.6.6/funasr.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/setup.py` & `funasr-0.6.6/setup.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/tests/test_asr_inference_pipeline.py` & `funasr-0.6.6/tests/test_asr_inference_pipeline.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/tests/test_asr_vad_punc_inference_pipeline.py` & `funasr-0.6.6/tests/test_asr_vad_punc_inference_pipeline.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/tests/test_lm_pipeline.py` & `funasr-0.6.6/tests/test_lm_pipeline.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/tests/test_punctuation_pipeline.py` & `funasr-0.6.6/tests/test_punctuation_pipeline.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/tests/test_sv_inference_pipeline.py` & `funasr-0.6.6/tests/test_sv_inference_pipeline.py`

 * *Files identical despite different names*

### Comparing `funasr-0.6.5/tests/test_vad_inference_pipeline.py` & `funasr-0.6.6/tests/test_vad_inference_pipeline.py`

 * *Files identical despite different names*

