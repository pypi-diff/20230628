# Comparing `tmp/dataquality-0.9.2.tar.gz` & `tmp/dataquality-0.9.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dataquality-0.9.2.tar", last modified: Mon Jun 26 20:55:16 2023, max compression
+gzip compressed data, was "dataquality-0.9.3.tar", last modified: Wed Jun 28 15:20:32 2023, max compression
```

## Comparing `dataquality-0.9.2.tar` & `dataquality-0.9.3.tar`

### file list

```diff
@@ -1,161 +1,167 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.920070 dataquality-0.9.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1066 2023-06-26 20:53:47.000000 dataquality-0.9.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     4937 2023-06-26 20:55:16.920070 dataquality-0.9.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     4429 2023-06-26 20:53:47.000000 dataquality-0.9.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.868070 dataquality-0.9.2/dataquality/
--rw-r--r--   0 runner    (1001) docker     (123)     6069 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8300 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/analytics.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.872069 dataquality-0.9.2/dataquality/clients/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/clients/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    33222 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/clients/api.py
--rw-r--r--   0 runner    (1001) docker     (123)     8187 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/clients/objectstore.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.876070 dataquality-0.9.2/dataquality/core/
--rw-r--r--   0 runner    (1001) docker     (123)     1848 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/core/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9495 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/core/_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     3104 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/core/auth.py
--rw-r--r--   0 runner    (1001) docker     (123)     6499 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/core/finish.py
--rw-r--r--   0 runner    (1001) docker     (123)     9615 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/core/init.py
--rw-r--r--   0 runner    (1001) docker     (123)    23390 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/core/log.py
--rw-r--r--   0 runner    (1001) docker     (123)     7039 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/core/report.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.876070 dataquality-0.9.2/dataquality/dq_auto/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10048 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/auto.py
--rw-r--r--   0 runner    (1001) docker     (123)     4699 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/base_data_manager.py
--rw-r--r--   0 runner    (1001) docker     (123)     7430 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/ner.py
--rw-r--r--   0 runner    (1001) docker     (123)     4265 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/ner_trainer.py
--rw-r--r--   0 runner    (1001) docker     (123)     1594 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/notebook.py
--rw-r--r--   0 runner    (1001) docker     (123)     3559 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/tc_trainer.py
--rw-r--r--   0 runner    (1001) docker     (123)    10676 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_auto/text_classification.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.880070 dataquality-0.9.2/dataquality/dq_start/
--rw-r--r--   0 runner    (1001) docker     (123)    11313 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dq_start/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4512 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/dqyolo.py
--rw-r--r--   0 runner    (1001) docker     (123)      293 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/exceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.880070 dataquality-0.9.2/dataquality/integrations/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14966 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/fastai.py
--rw-r--r--   0 runner    (1001) docker     (123)    10024 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/hf.py
--rw-r--r--   0 runner    (1001) docker     (123)    15575 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/keras.py
--rw-r--r--   0 runner    (1001) docker     (123)    14309 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/setfit.py
--rw-r--r--   0 runner    (1001) docker     (123)    13302 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/torch.py
--rw-r--r--   0 runner    (1001) docker     (123)    27174 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/torch_semantic_segmentation.py
--rw-r--r--   0 runner    (1001) docker     (123)    13430 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/transformers_trainer.py
--rw-r--r--   0 runner    (1001) docker     (123)    17147 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/integrations/ultralytics.py
--rw-r--r--   0 runner    (1001) docker     (123)     4165 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/internal.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.884070 dataquality-0.9.2/dataquality/loggers/
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13410 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/base_logger.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.884070 dataquality-0.9.2/dataquality/loggers/data_logger/
--rw-r--r--   0 runner    (1001) docker     (123)      517 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27255 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/base_data_logger.py
--rw-r--r--   0 runner    (1001) docker     (123)    12826 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/image_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)    10355 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/object_detection.py
--rw-r--r--   0 runner    (1001) docker     (123)     5888 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/semantic_segmentation.py
--rw-r--r--   0 runner    (1001) docker     (123)     9864 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/tabular_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)    21106 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/text_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)    14941 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/text_multi_label.py
--rw-r--r--   0 runner    (1001) docker     (123)    31953 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/data_logger/text_ner.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.888069 dataquality-0.9.2/dataquality/loggers/logger_config/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2042 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/base_logger_config.py
--rw-r--r--   0 runner    (1001) docker     (123)      510 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/image_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/object_detection.py
--rw-r--r--   0 runner    (1001) docker     (123)      226 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/semantic_segmentation.py
--rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/tabular_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)      958 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/text_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/text_multi_label.py
--rw-r--r--   0 runner    (1001) docker     (123)     1608 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/logger_config/text_ner.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.892070 dataquality-0.9.2/dataquality/loggers/model_logger/
--rw-r--r--   0 runner    (1001) docker     (123)      420 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7510 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/base_model_logger.py
--rw-r--r--   0 runner    (1001) docker     (123)     3309 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/image_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)     9435 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/object_detection.py
--rw-r--r--   0 runner    (1001) docker     (123)    11827 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/semantic_segmentation.py
--rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/tabular_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)     7555 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/text_classification.py
--rw-r--r--   0 runner    (1001) docker     (123)     9120 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/text_multi_label.py
--rw-r--r--   0 runner    (1001) docker     (123)    32052 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/loggers/model_logger/text_ner.py
--rw-r--r--   0 runner    (1001) docker     (123)    28653 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/metrics.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.900070 dataquality-0.9.2/dataquality/schemas/
--rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8361 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/condition.py
--rw-r--r--   0 runner    (1001) docker     (123)      569 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/dataframe.py
--rw-r--r--   0 runner    (1001) docker     (123)     4382 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/edit.py
--rw-r--r--   0 runner    (1001) docker     (123)      662 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/hf.py
--rw-r--r--   0 runner    (1001) docker     (123)      118 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/job.py
--rw-r--r--   0 runner    (1001) docker     (123)     5241 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/metrics.py
--rw-r--r--   0 runner    (1001) docker     (123)      145 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/model.py
--rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/ner.py
--rw-r--r--   0 runner    (1001) docker     (123)      617 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/report.py
--rw-r--r--   0 runner    (1001) docker     (123)      287 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/request_type.py
--rw-r--r--   0 runner    (1001) docker     (123)     1495 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/route.py
--rw-r--r--   0 runner    (1001) docker     (123)     4366 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/semantic_segmentation.py
--rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/split.py
--rw-r--r--   0 runner    (1001) docker     (123)     1295 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/task_type.py
--rw-r--r--   0 runner    (1001) docker     (123)      740 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/schemas/torch.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.912070 dataquality-0.9.2/dataquality/utils/
--rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/ampli.py
--rw-r--r--   0 runner    (1001) docker     (123)      401 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/auth.py
--rw-r--r--   0 runner    (1001) docker     (123)     8903 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/auto.py
--rw-r--r--   0 runner    (1001) docker     (123)      925 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/auto_trainer.py
--rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/cloud.py
--rw-r--r--   0 runner    (1001) docker     (123)     1229 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/cuda.py
--rw-r--r--   0 runner    (1001) docker     (123)     2082 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/cv.py
--rw-r--r--   0 runner    (1001) docker     (123)     3387 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/dq_logger.py
--rw-r--r--   0 runner    (1001) docker     (123)     3514 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/dqyolo.py
--rw-r--r--   0 runner    (1001) docker     (123)     4898 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/emb.py
--rw-r--r--   0 runner    (1001) docker     (123)     3591 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/file.py
--rw-r--r--   0 runner    (1001) docker     (123)     5685 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/hdf5_store.py
--rw-r--r--   0 runner    (1001) docker     (123)     3784 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)     2163 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/hf_images.py
--rw-r--r--   0 runner    (1001) docker     (123)    10182 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/hf_tokenizer.py
--rw-r--r--   0 runner    (1001) docker     (123)      429 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/imports.py
--rw-r--r--   0 runner    (1001) docker     (123)     8023 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/keras.py
--rw-r--r--   0 runner    (1001) docker     (123)     2408 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/ml.py
--rw-r--r--   0 runner    (1001) docker     (123)    24732 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/name.py
--rw-r--r--   0 runner    (1001) docker     (123)     1661 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/od.py
--rw-r--r--   0 runner    (1001) docker     (123)     3187 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/patcher.py
--rw-r--r--   0 runner    (1001) docker     (123)     5923 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/profiler.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.916070 dataquality-0.9.2/dataquality/utils/semantic_segmentation/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/semantic_segmentation/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/semantic_segmentation/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)    10050 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/semantic_segmentation/errors.py
--rw-r--r--   0 runner    (1001) docker     (123)    11898 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/semantic_segmentation/lm.py
--rw-r--r--   0 runner    (1001) docker     (123)    10144 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/semantic_segmentation/metrics.py
--rw-r--r--   0 runner    (1001) docker     (123)     5309 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/semantic_segmentation/polygons.py
--rw-r--r--   0 runner    (1001) docker     (123)     1914 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/semantic_segmentation/utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    15187 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/setfit.py
--rw-r--r--   0 runner    (1001) docker     (123)      260 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/tf.py
--rw-r--r--   0 runner    (1001) docker     (123)     1987 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/thread_pool.py
--rw-r--r--   0 runner    (1001) docker     (123)    24980 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/torch.py
--rw-r--r--   0 runner    (1001) docker     (123)     5087 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/transformers.py
--rw-r--r--   0 runner    (1001) docker     (123)    12825 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/ultralytics.py
--rw-r--r--   0 runner    (1001) docker     (123)     5597 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/upload.py
--rw-r--r--   0 runner    (1001) docker     (123)    10670 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/vaex.py
--rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-06-26 20:53:47.000000 dataquality-0.9.2/dataquality/utils/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.868070 dataquality-0.9.2/dataquality.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4937 2023-06-26 20:55:16.000000 dataquality-0.9.2/dataquality.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     5079 2023-06-26 20:55:16.000000 dataquality-0.9.2/dataquality.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 20:55:16.000000 dataquality-0.9.2/dataquality.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-26 20:55:16.000000 dataquality-0.9.2/dataquality.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1293 2023-06-26 20:55:16.000000 dataquality-0.9.2/dataquality.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-26 20:55:16.000000 dataquality-0.9.2/dataquality.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     3847 2023-06-26 20:53:47.000000 dataquality-0.9.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      293 2023-06-26 20:55:16.920070 dataquality-0.9.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 20:53:47.000000 dataquality-0.9.2/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.916070 dataquality-0.9.2/tests/
--rw-r--r--   0 runner    (1001) docker     (123)    31396 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_dataquality.py
--rw-r--r--   0 runner    (1001) docker     (123)     1783 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_telemetrics.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 20:55:16.920070 dataquality-0.9.2/tests/test_utils/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6129 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/data_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/hf_datasets_mock.py
--rw-r--r--   0 runner    (1001) docker     (123)    11616 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/hf_integration_constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     8122 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/hf_integration_constants_inference.py
--rw-r--r--   0 runner    (1001) docker     (123)     3695 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/lightning_model.py
--rw-r--r--   0 runner    (1001) docker     (123)     3017 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/mock_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     5594 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/mock_request.py
--rw-r--r--   0 runner    (1001) docker     (123)     2840 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/ner_constants.py
--rw-r--r--   0 runner    (1001) docker     (123)      863 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/pt_datasets_mock.py
--rw-r--r--   0 runner    (1001) docker     (123)     7910 2023-06-26 20:53:47.000000 dataquality-0.9.2/tests/test_utils/tc_constants.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.433193 dataquality-0.9.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1066 2023-06-28 15:19:11.000000 dataquality-0.9.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     4937 2023-06-28 15:20:32.433193 dataquality-0.9.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4429 2023-06-28 15:19:11.000000 dataquality-0.9.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.385192 dataquality-0.9.3/dataquality/
+-rw-r--r--   0 runner    (1001) docker     (123)     6109 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8300 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/analytics.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.385192 dataquality-0.9.3/dataquality/clients/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/clients/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33222 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/clients/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8187 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/clients/objectstore.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.389192 dataquality-0.9.3/dataquality/core/
+-rw-r--r--   0 runner    (1001) docker     (123)     1848 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/core/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9495 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/core/_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3104 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/core/auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6499 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/core/finish.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9615 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/core/init.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24547 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/core/log.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7039 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/core/report.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.393192 dataquality-0.9.3/dataquality/dq_auto/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10048 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/auto.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4699 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/base_data_manager.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7430 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/ner.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4265 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/ner_trainer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1594 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/notebook.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3559 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/tc_trainer.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10676 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_auto/text_classification.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.393192 dataquality-0.9.3/dataquality/dq_start/
+-rw-r--r--   0 runner    (1001) docker     (123)    11313 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dq_start/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4512 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/dqyolo.py
+-rw-r--r--   0 runner    (1001) docker     (123)      293 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.397192 dataquality-0.9.3/dataquality/integrations/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14966 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/fastai.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10024 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/hf.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15575 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/keras.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14309 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/setfit.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13302 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/torch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27174 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/torch_semantic_segmentation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13430 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/transformers_trainer.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17147 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/integrations/ultralytics.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4165 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/internal.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.397192 dataquality-0.9.3/dataquality/loggers/
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13715 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/base_logger.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.401193 dataquality-0.9.3/dataquality/loggers/data_logger/
+-rw-r--r--   0 runner    (1001) docker     (123)      545 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27255 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/base_data_logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12826 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/image_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10355 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/object_detection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5888 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/semantic_segmentation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7833 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/seq2seq.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9864 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/tabular_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21106 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/text_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14941 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/text_multi_label.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31953 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/data_logger/text_ner.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.401193 dataquality-0.9.3/dataquality/loggers/logger_config/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2042 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/base_logger_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      510 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/image_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/object_detection.py
+-rw-r--r--   0 runner    (1001) docker     (123)      226 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/semantic_segmentation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      612 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/seq2seq.py
+-rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/tabular_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)      958 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/text_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1510 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/text_multi_label.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1608 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/logger_config/text_ner.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.405192 dataquality-0.9.3/dataquality/loggers/model_logger/
+-rw-r--r--   0 runner    (1001) docker     (123)      448 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7838 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/base_model_logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3354 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/image_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9435 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/object_detection.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12316 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/semantic_segmentation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5771 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/seq2seq.py
+-rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/tabular_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7600 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/text_classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9165 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/text_multi_label.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32097 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/loggers/model_logger/text_ner.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28653 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/metrics.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.413193 dataquality-0.9.3/dataquality/schemas/
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8361 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/condition.py
+-rw-r--r--   0 runner    (1001) docker     (123)      569 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/dataframe.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4382 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/edit.py
+-rw-r--r--   0 runner    (1001) docker     (123)      662 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/hf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      118 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/job.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5241 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/metrics.py
+-rw-r--r--   0 runner    (1001) docker     (123)      145 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/ner.py
+-rw-r--r--   0 runner    (1001) docker     (123)      617 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/report.py
+-rw-r--r--   0 runner    (1001) docker     (123)      287 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/request_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1495 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/route.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4417 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/semantic_segmentation.py
+-rw-r--r--   0 runner    (1001) docker     (123)      637 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/seq2seq.py
+-rw-r--r--   0 runner    (1001) docker     (123)      992 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/split.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1352 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/task_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      740 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/schemas/torch.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.425193 dataquality-0.9.3/dataquality/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/ampli.py
+-rw-r--r--   0 runner    (1001) docker     (123)      495 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/arrow.py
+-rw-r--r--   0 runner    (1001) docker     (123)      401 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8903 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/auto.py
+-rw-r--r--   0 runner    (1001) docker     (123)      925 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/auto_trainer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/cloud.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1229 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/cuda.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2082 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/cv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3469 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/dq_logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3514 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/dqyolo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4898 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/emb.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3591 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/file.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5685 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/hdf5_store.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3784 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2163 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/hf_images.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10182 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/hf_tokenizer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      429 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/imports.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8023 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/keras.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2408 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/ml.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24732 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/name.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1661 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/od.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3187 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/patcher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5923 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/profiler.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.429193 dataquality-0.9.3/dataquality/utils/semantic_segmentation/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/semantic_segmentation/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/semantic_segmentation/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10050 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/semantic_segmentation/errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11898 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/semantic_segmentation/lm.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10658 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/semantic_segmentation/metrics.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5309 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/semantic_segmentation/polygons.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1914 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/semantic_segmentation/utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11404 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/seq2seq.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15187 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/setfit.py
+-rw-r--r--   0 runner    (1001) docker     (123)      260 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/tf.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1987 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/thread_pool.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24980 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/torch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5087 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/transformers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12825 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/ultralytics.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5597 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/upload.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10670 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/vaex.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-06-28 15:19:11.000000 dataquality-0.9.3/dataquality/utils/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.385192 dataquality-0.9.3/dataquality.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4937 2023-06-28 15:20:32.000000 dataquality-0.9.3/dataquality.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5298 2023-06-28 15:20:32.000000 dataquality-0.9.3/dataquality.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:20:32.000000 dataquality-0.9.3/dataquality.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-28 15:20:32.000000 dataquality-0.9.3/dataquality.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1293 2023-06-28 15:20:32.000000 dataquality-0.9.3/dataquality.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-28 15:20:32.000000 dataquality-0.9.3/dataquality.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     3847 2023-06-28 15:19:11.000000 dataquality-0.9.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      293 2023-06-28 15:20:32.437193 dataquality-0.9.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:19:11.000000 dataquality-0.9.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.429193 dataquality-0.9.3/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)    31396 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_dataquality.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1783 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_telemetrics.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:20:32.433193 dataquality-0.9.3/tests/test_utils/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6129 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/data_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/hf_datasets_mock.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11616 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/hf_integration_constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8122 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/hf_integration_constants_inference.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3695 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/lightning_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3017 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/mock_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5594 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/mock_request.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2840 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/ner_constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)      863 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/pt_datasets_mock.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7910 2023-06-28 15:19:11.000000 dataquality-0.9.3/tests/test_utils/tc_constants.py
```

### Comparing `dataquality-0.9.2/LICENSE` & `dataquality-0.9.3/LICENSE`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/PKG-INFO` & `dataquality-0.9.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dataquality
-Version: 0.9.2
+Version: 0.9.3
 Author-email: "Galileo Technologies, Inc." <devs+dq@rungalileo.io>
 License: See LICENSE
 Project-URL: Homepage, https://github.com/rungalileo/dataquality
 Project-URL: Documentation, https://rungalileo.gitbook.io/galileo
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 Provides-Extra: doc
```

### Comparing `dataquality-0.9.2/README.md` & `dataquality-0.9.3/README.md`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/__init__.py` & `dataquality-0.9.3/dataquality/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -27,15 +27,15 @@
     import dataquality
     with dataquality(labels = ["neg", "pos"],
                      train_data = train_data):
         dataquality.get_insights()
 """
 
 
-__version__ = "v0.9.2"
+__version__ = "v0.9.3"
 
 import sys
 from typing import Any, List, Optional
 
 import dataquality.core._config
 import dataquality.integrations
 
@@ -68,14 +68,15 @@
     log_xgboost,
     set_epoch,
     set_epoch_and_split,
     set_labels_for_run,
     set_split,
     set_tagging_schema,
     set_tasks_for_run,
+    set_tokenizer,
 )
 from dataquality.core.report import build_run_report, register_run_report
 from dataquality.dq_auto.auto import auto
 from dataquality.dq_auto.notebook import auto_notebook
 from dataquality.dq_start import DataQuality
 from dataquality.schemas.condition import (
     AggregateFunction,
@@ -128,14 +129,15 @@
     "disable_galileo",
     "disable_galileo_verbose",
     "enable_galileo_verbose",
     "enable_galileo",
     "auto",
     "DataQuality",
     "auto_notebook",
+    "set_tokenizer",
 ]
 
 try:
     import resource
 
     resource.setrlimit(resource.RLIMIT_NOFILE, (65535, 65535))
 except (ImportError, ValueError):  # The users limit is higher than our max, which is OK
```

### Comparing `dataquality-0.9.2/dataquality/analytics.py` & `dataquality-0.9.3/dataquality/analytics.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/clients/api.py` & `dataquality-0.9.3/dataquality/clients/api.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/clients/objectstore.py` & `dataquality-0.9.3/dataquality/clients/objectstore.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/core/__init__.py` & `dataquality-0.9.3/dataquality/core/__init__.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/core/_config.py` & `dataquality-0.9.3/dataquality/core/_config.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/core/auth.py` & `dataquality-0.9.3/dataquality/core/auth.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/core/finish.py` & `dataquality-0.9.3/dataquality/core/finish.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/core/init.py` & `dataquality-0.9.3/dataquality/core/init.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/core/log.py` & `dataquality-0.9.3/dataquality/core/log.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,16 @@
 from __future__ import annotations
 
 from typing import TYPE_CHECKING, Any, Dict, List, Optional, Tuple, Union
 
 import numpy as np
 import pandas as pd
+from transformers import PreTrainedTokenizerFast
+
+from dataquality.loggers.logger_config.seq2seq import seq2seq_logger_config
 
 if TYPE_CHECKING:
     import xgboost as xgb
 
 from dataquality.analytics import Analytics
 from dataquality.clients.api import ApiClient
 from dataquality.core._config import config
@@ -353,27 +356,28 @@
         **kwargs,
     )
 
 
 @check_noop
 def log_model_outputs(
     *,
-    embs: Optional[Union[List, np.ndarray]],
     ids: Union[List, np.ndarray],
+    embs: Optional[Union[List, np.ndarray]] = None,
     split: Optional[Split] = None,
     epoch: Optional[int] = None,
     logits: Optional[Union[List, np.ndarray]] = None,
     probs: Optional[Union[List, np.ndarray]] = None,
     inference_name: Optional[str] = None,
     exclude_embs: bool = False,
+    labels: Optional[np.ndarray] = None,
 ) -> None:
     """Logs model outputs for model during training/test/validation.
 
-    :param embs: The embeddings per output sample
     :param ids: The ids for each sample. Must match input ids of logged samples
+    :param embs: The embeddings per output sample
     :param split: The current split. Must be set either here or via dq.set_split
     :param epoch: The current epoch. Must be set either here or via dq.set_epoch
     :param logits: The logits for each sample
     :param probs: Deprecated, use logits. If passed in, a softmax will NOT be applied
     :param inference_name: Inference name indicator for this inference split.
         If logging for an inference split, this is required.
     :param exclude_embs: Optional flag to exclude embeddings from logging. If True and
@@ -384,14 +388,18 @@
     """
     assert all(
         [config.task_type, config.current_project_id, config.current_run_id]
     ), "You must call dataquality.init before logging data"
     assert (probs is not None) or (
         logits is not None
     ), "You must provide either logits or probs"
+    # No embeddings ever provided by user in seq2seq
+    if config.task_type == TaskType.seq2seq:
+        exclude_embs = True
+        embs = None
     assert (embs is None and exclude_embs) or (
         embs is not None and not exclude_embs
     ), "embs can be omitted if and only if exclude_embs is True"
     if embs is None and exclude_embs:
         embs = np.random.rand(len(ids), DEFAULT_RANDOM_EMB_DIM)
 
     model_logger = get_model_logger(
@@ -399,14 +407,15 @@
         embs=embs.astype(np.float32) if isinstance(embs, np.ndarray) else embs,
         ids=ids,
         split=Split[split].value if split else "",
         epoch=epoch,
         logits=logits.astype(np.float32) if isinstance(logits, np.ndarray) else logits,
         probs=probs.astype(np.float32) if isinstance(probs, np.ndarray) else probs,
         inference_name=inference_name,
+        labels=labels.astype(np.float32) if isinstance(labels, np.ndarray) else labels,
     )
     model_logger.log()
 
 
 @check_noop
 def log_od_model_outputs(
     *,
@@ -603,7 +612,24 @@
 ) -> None:
     """Set the current epoch and set the current split.
     When set, logging data inputs/model outputs will use this if not logged explicitly
     When setting split to inference, inference_name must be included
     """
     set_epoch(epoch)
     set_split(split, inference_name)
+
+
+@check_noop
+def set_tokenizer(tokenizer: PreTrainedTokenizerFast) -> None:
+    """Seq2seq only. Set the tokenizer for your run
+
+    Must be a fast tokenizer, and must support `decode`, `encode`, `encode_plus`
+    """
+    task_type = _get_task_type()
+    assert task_type == TaskType.seq2seq, "This method is only supported for seq2seq"
+    assert isinstance(
+        tokenizer, PreTrainedTokenizerFast
+    ), "Tokenizer must be an instance of PreTrainedTokenizerFast"
+    assert getattr(tokenizer, "is_fast", False), "Tokenizer must be a fast tokenizer"
+    for attr in ["encode", "decode", "encode_plus", "padding_side"]:
+        assert hasattr(tokenizer, attr), f"Tokenizer must support `{attr}`"
+    seq2seq_logger_config.tokenizer = tokenizer
```

### Comparing `dataquality-0.9.2/dataquality/core/report.py` & `dataquality-0.9.3/dataquality/core/report.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_auto/auto.py` & `dataquality-0.9.3/dataquality/dq_auto/auto.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_auto/base_data_manager.py` & `dataquality-0.9.3/dataquality/dq_auto/base_data_manager.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_auto/ner.py` & `dataquality-0.9.3/dataquality/dq_auto/ner.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_auto/ner_trainer.py` & `dataquality-0.9.3/dataquality/dq_auto/ner_trainer.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_auto/notebook.py` & `dataquality-0.9.3/dataquality/dq_auto/notebook.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_auto/tc_trainer.py` & `dataquality-0.9.3/dataquality/dq_auto/tc_trainer.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_auto/text_classification.py` & `dataquality-0.9.3/dataquality/dq_auto/text_classification.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dq_start/__init__.py` & `dataquality-0.9.3/dataquality/dq_start/__init__.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/dqyolo.py` & `dataquality-0.9.3/dataquality/dqyolo.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/fastai.py` & `dataquality-0.9.3/dataquality/integrations/fastai.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/hf.py` & `dataquality-0.9.3/dataquality/integrations/hf.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/keras.py` & `dataquality-0.9.3/dataquality/integrations/keras.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/setfit.py` & `dataquality-0.9.3/dataquality/integrations/setfit.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/torch.py` & `dataquality-0.9.3/dataquality/integrations/torch.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/torch_semantic_segmentation.py` & `dataquality-0.9.3/dataquality/integrations/torch_semantic_segmentation.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/transformers_trainer.py` & `dataquality-0.9.3/dataquality/integrations/transformers_trainer.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/integrations/ultralytics.py` & `dataquality-0.9.3/dataquality/integrations/ultralytics.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/internal.py` & `dataquality-0.9.3/dataquality/internal.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/base_logger.py` & `dataquality-0.9.3/dataquality/loggers/base_logger.py`

 * *Files 11% similar despite different names*

```diff
@@ -55,14 +55,22 @@
     gold_emb = "gold_emb"
     pred_spans = "pred_spans"
     text_token_indices = "text_token_indices"
     text_token_indices_flat = "text_token_indices_flat"
     log_helper_data = "log_helper_data"
     inference_name = "inference_name"
     image = "image"
+    token_label_positions = "token_label_positions"
+    token_label_offsets = "token_label_offsets"
+    label = "label"
+    token_deps = "token_deps"
+    text = "text"
+    id = "id"
+    token_gold_probs = "token_gold_probs"
+    tokenized_label = "tokenized_label"
 
     @staticmethod
     def get_valid() -> List[str]:
         return list(map(lambda x: x.value, BaseLoggerAttributes))
 
 
 class BaseGalileoLogger:
@@ -202,15 +210,15 @@
             if isinstance(arr, Tensor):
                 arr = arr.detach().cpu().numpy()
         if tf_available():
             import tensorflow as tf
 
             if isinstance(arr, tf.Tensor):
                 if is_tf_2():
-                    with tf.device("/cpu:0"):
+                    with tf.device("cpu"):
                         arr = tf.identity(arr).numpy()
                 else:  # Just for TF1.x
                     arr = arr.numpy()
         if isinstance(arr, np.ndarray):
             if attr == "Embedding":
                 assert (
                     len(arr.shape) == 2
@@ -226,15 +234,15 @@
                     arr = np.array(arr, dtype=object)
                     assert arr.ndim > 1, (
                         f"Probs/logits must have at least 2 dimensions, "
                         f"they have {arr.ndim}"
                     )
             elif attr == "Labels" and config.task_type == TaskType.text_multi_label:
                 arr = np.array(arr, dtype=object)
-        return np.array(arr)
+        return np.array(arr) if not isinstance(arr, np.ndarray) else arr
 
     @staticmethod
     def _convert_tensor_to_py(v: Any) -> Union[str, int]:
         """Converts pytorch and tensorflow tensors to strings or ints"""
         if isinstance(v, (int, str)):
             return v
         if tf_available():
```

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/__init__.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/__init__.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 from dataquality.loggers.data_logger import (
     image_classification,
     object_detection,
     semantic_segmentation,
+    seq2seq,
     tabular_classification,
     text_classification,
     text_multi_label,
     text_ner,
 )
 from dataquality.loggers.data_logger.base_data_logger import BaseGalileoDataLogger
 
@@ -14,8 +15,9 @@
     "semantic_segmentation",
     "text_classification",
     "tabular_classification",
     "text_multi_label",
     "text_ner",
     "object_detection",
     "BaseGalileoDataLogger",
+    "seq2seq",
 ]
```

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/base_data_logger.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/base_data_logger.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/image_classification.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/image_classification.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/object_detection.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/object_detection.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/semantic_segmentation.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/semantic_segmentation.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/tabular_classification.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/tabular_classification.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/text_classification.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/text_classification.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/text_multi_label.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/text_multi_label.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/data_logger/text_ner.py` & `dataquality-0.9.3/dataquality/loggers/data_logger/text_ner.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/logger_config/base_logger_config.py` & `dataquality-0.9.3/dataquality/loggers/logger_config/base_logger_config.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/logger_config/object_detection.py` & `dataquality-0.9.3/dataquality/loggers/logger_config/object_detection.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/logger_config/text_classification.py` & `dataquality-0.9.3/dataquality/loggers/logger_config/text_classification.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/logger_config/text_multi_label.py` & `dataquality-0.9.3/dataquality/loggers/logger_config/text_multi_label.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/logger_config/text_ner.py` & `dataquality-0.9.3/dataquality/loggers/logger_config/text_ner.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/base_model_logger.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/base_model_logger.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,23 +19,26 @@
 from dataquality.utils.hdf5_store import _save_hdf5_file
 from dataquality.utils.thread_pool import ThreadPoolManager
 
 analytics = Analytics(ApiClient, config)  # type: ignore
 
 
 class BaseGalileoModelLogger(BaseGalileoLogger):
+    log_file_ext = "hdf5"
+
     def __init__(
         self,
         embs: Optional[Union[List, np.ndarray]] = None,
         probs: Optional[Union[List, np.ndarray]] = None,
         logits: Optional[Union[List, np.ndarray]] = None,
         ids: Optional[Union[List, np.ndarray]] = None,
         split: str = "",
         epoch: Optional[int] = None,
         inference_name: Optional[str] = None,
+        labels: Optional[np.ndarray] = None,
     ) -> None:
         super().__init__()
         # Need to compare to None because they may be np arrays which cannot be
         # evaluated with bool directly
         self.embs: Union[List, np.ndarray] = embs if embs is not None else []
         self.logits: Union[List, np.ndarray] = logits if logits is not None else []
         self.probs: Union[List, np.ndarray] = probs if probs is not None else []
@@ -112,15 +115,18 @@
         if split == Split.inference:
             inference_name = data["inference_name"][0]
             path = f"{location}/{split}/{inference_name}"
         else:
             epoch = data["epoch"][0]
             path = f"{location}/{split}/{epoch}"
 
-        object_name = f"{str(uuid4()).replace('-', '')[:12]}.hdf5"
+        object_name = f"{str(uuid4()).replace('-', '')[:12]}.{self.log_file_ext}"
+        self._write_dict_to_disk(path, object_name, data)
+
+    def _write_dict_to_disk(self, path: str, object_name: str, data: Dict) -> None:
         _save_hdf5_file(path, object_name, data)
 
     def set_split_epoch(self) -> None:
         super().set_split_epoch()
 
         # Non-inference split must have an epoch
         if self.split != Split.inference and self.epoch is None:
@@ -179,8 +185,10 @@
         # If shape is (num_samples, 1) or (num_samples,) then we have a binary case
         if len(sample_logits.shape) == 1 or sample_logits.shape[-1] == 1:
             if len(sample_logits.shape) > 1:
                 # Remove final empty dimension if it's there
                 sample_logits = sample_logits.reshape(-1)
             return self.convert_logits_to_prob_binary(sample_logits)
 
-        return softmax(np.array(sample_logits), axis=-1)
+        if not isinstance(sample_logits, np.ndarray):
+            sample_logits = np.ndarray(sample_logits)
+        return softmax(sample_logits, axis=-1)
```

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/image_classification.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/image_classification.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,14 +20,15 @@
         embs: Optional[Union[List, np.ndarray]] = None,
         probs: Optional[Union[List, np.ndarray]] = None,
         logits: Optional[Union[List, np.ndarray]] = None,
         ids: Optional[Union[List, np.ndarray]] = None,
         split: str = "",
         epoch: Optional[int] = None,
         inference_name: Optional[str] = None,
+        labels: Optional[np.ndarray] = None,
     ) -> None:
         super().__init__(
             embs=embs,
             probs=probs,
             logits=logits,
             ids=ids,
             split=split,
```

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/object_detection.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/object_detection.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/semantic_segmentation.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/semantic_segmentation.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,22 +8,26 @@
 from dataquality import config
 from dataquality.clients.objectstore import ObjectStore
 from dataquality.loggers.logger_config.semantic_segmentation import (
     SemanticSegmentationLoggerConfig,
     semantic_segmentation_logger_config,
 )
 from dataquality.loggers.model_logger.base_model_logger import BaseGalileoModelLogger
-from dataquality.schemas.semantic_segmentation import IoUType, Polygon, PolygonType
+from dataquality.schemas.semantic_segmentation import (
+    Polygon,
+    PolygonType,
+    SemSegMetricType,
+)
 from dataquality.schemas.split import Split
 from dataquality.utils.semantic_segmentation.errors import (
     add_errors_and_metrics_to_polygons_batch,
 )
 from dataquality.utils.semantic_segmentation.metrics import (
     calculate_and_upload_dep,
-    calculate_batch_iou,
+    calculate_batch_metric,
 )
 from dataquality.utils.semantic_segmentation.polygons import (
     find_polygons_batch,
     write_polygon_contours_to_disk,
 )
 
 object_store = ObjectStore()
@@ -50,14 +54,15 @@
         embs: Optional[Union[List, np.ndarray]] = None,
         probs: Optional[Union[List, np.ndarray]] = None,
         logits: Optional[Union[List, np.ndarray]] = None,
         ids: Optional[Union[List, np.ndarray]] = None,
         split: str = "",
         epoch: Optional[int] = None,
         inference_name: Optional[str] = None,
+        labels: Optional[np.ndarray] = None,
     ) -> None:
         """Takes in SemSeg inputs as a list of batches
 
         Args:
             image_ids: List of image ids
             gold_masks: List of ground truth masks
                 np.ndarray of shape (batch_size, height, width)
@@ -206,23 +211,26 @@
             self.output_probs,
             self.gold_masks,
             self.image_ids,
             local_folder_path=self.local_dep_path,
         )
         # Calculate metrics - mean IoU and boundary IoU
         n_classes = len(self.logger_config.labels)
-        mean_iou_data = calculate_batch_iou(
-            self.pred_masks, self.gold_masks, IoUType.mean, n_classes
+        mean_iou_data = calculate_batch_metric(
+            self.pred_masks, self.gold_masks, SemSegMetricType.miou, n_classes
         )
-        boundary_iou_data = calculate_batch_iou(
+        boundary_iou_data = calculate_batch_metric(
             self.pred_boundary_masks,
             self.gold_boundary_masks,
-            IoUType.boundary,
+            SemSegMetricType.biou,
             n_classes,
         )
+        dice_data = calculate_batch_metric(
+            self.pred_masks, self.gold_masks, SemSegMetricType.dice, n_classes
+        )
 
         # Image masks
         pred_polygons_batch, gold_polygons_batch = find_polygons_batch(
             self.pred_masks, self.gold_masks
         )
 
         # in the case that both pred and gold polygons are empty, we need to
@@ -263,22 +271,27 @@
 
         image_data = {
             "image": [f"{self.imgs_remote_location}/{pth}" for pth in self.image_paths],
             "id": self.image_ids,
             "height": heights,
             "width": widths,
             "mean_lm_score": [i for i in mean_mislabeled],
-            "mean_iou": [iou.iou for iou in mean_iou_data],
-            "mean_iou_per_class": [iou.iou_per_class for iou in mean_iou_data],
+            "mean_iou": [iou.value for iou in mean_iou_data],
+            "mean_iou_per_class": [iou.value_per_class for iou in mean_iou_data],
             "mean_area_per_class": [iou.area_per_class for iou in mean_iou_data],
-            "boundary_iou": [iou.iou for iou in boundary_iou_data],
-            "boundary_iou_per_class": [iou.iou_per_class for iou in boundary_iou_data],
+            "boundary_iou": [iou.value for iou in boundary_iou_data],
+            "boundary_iou_per_class": [
+                iou.value_per_class for iou in boundary_iou_data
+            ],
             "boundary_area_per_class": [
                 iou.area_per_class for iou in boundary_iou_data
             ],
+            "dice_coefficient": [dice.value for dice in dice_data],
+            "dice_per_class": [dice.value_per_class for dice in dice_data],
+            "dice_area_per_class": [dice.area_per_class for dice in dice_data],
             # "epoch": [self.epoch] * len(self.image_ids),
         }
         not_meta = ["id", "image"]
         meta_keys = [k for k in image_data.keys() if k not in not_meta]
         dq.log_dataset(
             image_data,
             split=Split[self.split],
```

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/tabular_classification.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/tabular_classification.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/text_classification.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/text_classification.py`

 * *Files 1% similar despite different names*

```diff
@@ -77,14 +77,15 @@
         embs: Optional[Union[List, np.ndarray]] = None,
         probs: Optional[Union[List, np.ndarray]] = None,
         logits: Optional[Union[List, np.ndarray]] = None,
         ids: Optional[Union[List, np.ndarray]] = None,
         split: str = "",
         epoch: Optional[int] = None,
         inference_name: Optional[str] = None,
+        labels: Optional[np.ndarray] = None,
     ) -> None:
         super().__init__(
             embs=embs,
             probs=probs,
             logits=logits,
             ids=ids,
             split=split,
```

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/text_multi_label.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/text_multi_label.py`

 * *Files 1% similar despite different names*

```diff
@@ -65,14 +65,15 @@
         embs: Optional[Union[List, np.ndarray]] = None,
         probs: Optional[Union[List[List[List]], List[np.ndarray]]] = None,
         logits: Optional[Union[List[List[List]], List[np.ndarray]]] = None,
         ids: Optional[Union[List, np.ndarray]] = None,
         split: str = "",
         epoch: Optional[int] = None,
         inference_name: Optional[str] = None,
+        labels: Optional[np.ndarray] = None,
     ) -> None:
         super().__init__(
             embs=embs,
             probs=probs,
             logits=logits,
             ids=ids,
             split=split,
```

### Comparing `dataquality-0.9.2/dataquality/loggers/model_logger/text_ner.py` & `dataquality-0.9.3/dataquality/loggers/model_logger/text_ner.py`

 * *Files 0% similar despite different names*

```diff
@@ -98,14 +98,15 @@
         embs: Optional[List[np.ndarray]] = None,
         probs: Optional[List[np.ndarray]] = None,
         logits: Optional[List[np.ndarray]] = None,
         ids: Optional[Union[List, np.ndarray]] = None,
         split: str = "",
         epoch: Optional[int] = None,
         inference_name: Optional[str] = None,
+        labels: Optional[np.ndarray] = None,
     ) -> None:
         super().__init__(
             embs=embs,
             probs=probs,
             logits=logits,
             ids=ids,
             split=split,
```

### Comparing `dataquality-0.9.2/dataquality/metrics.py` & `dataquality-0.9.3/dataquality/metrics.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/condition.py` & `dataquality-0.9.3/dataquality/schemas/condition.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/dataframe.py` & `dataquality-0.9.3/dataquality/schemas/dataframe.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/edit.py` & `dataquality-0.9.3/dataquality/schemas/edit.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/hf.py` & `dataquality-0.9.3/dataquality/schemas/hf.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/metrics.py` & `dataquality-0.9.3/dataquality/schemas/metrics.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/ner.py` & `dataquality-0.9.3/dataquality/schemas/ner.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/report.py` & `dataquality-0.9.3/dataquality/schemas/report.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/route.py` & `dataquality-0.9.3/dataquality/schemas/route.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/semantic_segmentation.py` & `dataquality-0.9.3/dataquality/schemas/semantic_segmentation.py`

 * *Files 7% similar despite different names*

```diff
@@ -26,17 +26,18 @@
 
 class PolygonType(str, Enum):
     gold = "gold"
     pred = "pred"
     dummy = "dummy"
 
 
-class IoUType(str, Enum):
-    mean = "mean"
-    boundary = "boundary"
+class SemSegMetricType(str, Enum):
+    miou = "mean_iou"
+    biou = "boundary_iou"
+    dice = "dice"
 
 
 class ClassificationErrorData(BaseModel):
     """Data needed for determining classification errors on backend
 
     accuracy: no pixels correctly classified / area of polygon
     mislabeled_class: label idx of the class that was most frequently mislabeled
@@ -45,19 +46,19 @@
     """
 
     accuracy: float
     mislabeled_class: int
     mislabeled_class_pct: float
 
 
-class IouData(BaseModel):
-    iou: float
-    iou_per_class: List[float]
+class SemSegMetricData(BaseModel):
+    metric: SemSegMetricType
+    value: float
+    value_per_class: List[float]
     area_per_class: List[int]
-    iou_type: IoUType
 
 
 class Pixel(BaseModel):
     x: int
     y: int
 
     @property
```

### Comparing `dataquality-0.9.2/dataquality/schemas/split.py` & `dataquality-0.9.3/dataquality/schemas/split.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/schemas/task_type.py` & `dataquality-0.9.3/dataquality/schemas/task_type.py`

 * *Files 3% similar despite different names*

```diff
@@ -10,14 +10,15 @@
     text_multi_label = "text_multi_label"
     text_ner = "text_ner"
     image_classification = "image_classification"
     tabular_classification = "tabular_classification"
     object_detection = "object_detection"
     semantic_segmentation = "semantic_segmentation"
     prompt_evaluation = "prompt_evaluation"
+    seq2seq = "seq2seq"
 
     @staticmethod
     def get_valid_tasks() -> List["TaskType"]:
         """Tasks that are valid for dataquality."""
         return [
             task_type
             for task_type in TaskType
@@ -32,8 +33,9 @@
             1: TaskType.text_multi_label,
             2: TaskType.text_ner,
             3: TaskType.image_classification,
             4: TaskType.tabular_classification,
             5: TaskType.object_detection,
             6: TaskType.semantic_segmentation,
             7: TaskType.prompt_evaluation,
+            8: TaskType.seq2seq,
         }[task_int]
```

### Comparing `dataquality-0.9.2/dataquality/schemas/torch.py` & `dataquality-0.9.3/dataquality/schemas/torch.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/ampli.py` & `dataquality-0.9.3/dataquality/utils/ampli.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/auto.py` & `dataquality-0.9.3/dataquality/utils/auto.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/auto_trainer.py` & `dataquality-0.9.3/dataquality/utils/auto_trainer.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/cuda.py` & `dataquality-0.9.3/dataquality/utils/cuda.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/cv.py` & `dataquality-0.9.3/dataquality/utils/cv.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/dq_logger.py` & `dataquality-0.9.3/dataquality/utils/dq_logger.py`

 * *Files 7% similar despite different names*

```diff
@@ -18,16 +18,18 @@
     """
     This adapter appends the split to the message, if found. Otherwise, "None"
 
     Adapted from https://docs.python.org/3/howto/logging-cookbook.html (CustomAdapter)
     """
 
     def process(self, msg: str, kwargs: Any) -> Tuple[str, Any]:
-        split = kwargs.pop("split", self.extra["split"])
-        epoch = kwargs.pop("epoch", self.extra["epoch"])
+        _extras = self.extra or dict()
+        extras = dict(_extras)
+        split = kwargs.pop("split", extras.get("split", None))
+        epoch = kwargs.pop("epoch", extras.get("epoch", None))
         if epoch is not None:
             return "[%s] [epoch:%s]: %s" % (split, str(epoch), msg), kwargs
         return "[%s]: %s" % (split, msg), kwargs
 
 
 log_formatter = logging.Formatter(
     "%(asctime)s [%(levelname)s] [%(threadName)s] %(message)s"
```

### Comparing `dataquality-0.9.2/dataquality/utils/dqyolo.py` & `dataquality-0.9.3/dataquality/utils/dqyolo.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/emb.py` & `dataquality-0.9.3/dataquality/utils/emb.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/file.py` & `dataquality-0.9.3/dataquality/utils/file.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/hdf5_store.py` & `dataquality-0.9.3/dataquality/utils/hdf5_store.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/helpers.py` & `dataquality-0.9.3/dataquality/utils/helpers.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/hf_images.py` & `dataquality-0.9.3/dataquality/utils/hf_images.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/hf_tokenizer.py` & `dataquality-0.9.3/dataquality/utils/hf_tokenizer.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/keras.py` & `dataquality-0.9.3/dataquality/utils/keras.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/ml.py` & `dataquality-0.9.3/dataquality/utils/ml.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/name.py` & `dataquality-0.9.3/dataquality/utils/name.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/od.py` & `dataquality-0.9.3/dataquality/utils/od.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/patcher.py` & `dataquality-0.9.3/dataquality/utils/patcher.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/profiler.py` & `dataquality-0.9.3/dataquality/utils/profiler.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/semantic_segmentation/errors.py` & `dataquality-0.9.3/dataquality/utils/semantic_segmentation/errors.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/semantic_segmentation/lm.py` & `dataquality-0.9.3/dataquality/utils/semantic_segmentation/lm.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/semantic_segmentation/metrics.py` & `dataquality-0.9.3/dataquality/utils/semantic_segmentation/metrics.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,18 +1,22 @@
 import os
 from tempfile import NamedTemporaryFile
-from typing import List, Tuple
+from typing import List
 
 import numpy as np
 import torch
 from PIL import Image, ImageColor
 
 from dataquality import config
 from dataquality.clients.objectstore import ObjectStore
-from dataquality.schemas.semantic_segmentation import IouData, Polygon
+from dataquality.schemas.semantic_segmentation import (
+    Polygon,
+    SemSegMetricData,
+    SemSegMetricType,
+)
 from dataquality.utils.semantic_segmentation.polygons import draw_polygon
 
 object_store = ObjectStore()
 
 MAX_DEP_HEATMAP_SIZE = 128
 
 
@@ -164,86 +168,104 @@
     # Create a PIL Image object from the numpy array as grey-scale
     img = Image.fromarray(dep_heatmap, mode="L")
     if img.size[0] > MAX_DEP_HEATMAP_SIZE or img.size[1] > MAX_DEP_HEATMAP_SIZE:
         img = img.resize((MAX_DEP_HEATMAP_SIZE, MAX_DEP_HEATMAP_SIZE))
     return img
 
 
-def calculate_batch_iou(
-    pred_masks: torch.Tensor, gold_masks: torch.Tensor, iou_type: str, nc: int
-) -> List[IouData]:
-    """Calculates the Mean Intersection Over Union (mIoU) for each image in the batch
-    If boundary masks are passed into this function, we return the
-    boundary IoU (bIoU).
-    :param pred_masks: argmax of the prediction probabilities
-       shape = (bs, height, width)
-    :param gold_masks: ground truth masks
-       shape = (bs, height, width)
-    :param iou_type: mean or boundary
-    :param nc: number of classes
-    :return: list of IoU data for each image in the batch
-       shape = (bs,)
-    """
-    pred_masks_np = pred_masks.numpy()
-    gold_masks_np = gold_masks.numpy()
-    iou_data = []
-
-    # for iou need shape (bs, 1, height, width) to get per mask iou
-    for i in range(len(pred_masks_np)):
-        iou, area_per_class = compute_iou(
-            pred_masks_np[i : i + 1],  # tensor (1, height, width)
-            gold_masks_np[i : i + 1],  # tensor (1, height, width)
-            num_labels=nc,
-        )
-
-        iou_data.append(
-            IouData(
-                iou=np.nanmean(iou),
-                iou_per_class=iou.tolist(),
-                area_per_class=area_per_class.tolist(),
-                iou_type=iou_type,
-            )
-        )
-    return iou_data
-
-
-def compute_iou(
+def compute_metric(
     pred_mask: np.ndarray,
     gold_mask: np.ndarray,
+    metric_type: SemSegMetricType,
     num_labels: int,
-) -> Tuple[np.ndarray, np.ndarray]:
-    """Computes the intersection over union for a single image
+) -> SemSegMetricData:
+    """Computes the SemSeg metric data for a single image
 
-    Computes the iou for a single image as well as returning the total union area
-    per class
+    See 'calculate_batch_metric' for more details on the metrics
 
     Args:
-        pred_mask (np.ndarray): (h, w) pred mask
-        gold_mask (np.ndarray): (h, w) gold mask
-        num_labels (int): total number of labels including background
+        pred_mask (np.ndarray): argmax of the probability predictions
+        gold_mask (np.ndarray): ground truth mask
+        metric_type (SemSegMetricType): type of metric to compute
+        num_labels (int): number of classes
 
     Returns:
-        Tuple[np.ndarray, np.ndarray]: the iou per class and the union area per class
-            in numpy array
+        SemSegMetricData: metric data for the image
     """
     intersection_bool = pred_mask == gold_mask
 
     intersection_pixels = np.histogram(
         pred_mask[intersection_bool], bins=num_labels, range=(0, num_labels)
     )[0]
     pred_pixels = np.histogram(pred_mask, bins=num_labels, range=(0, num_labels))[0]
     gold_pixels = np.histogram(gold_mask, bins=num_labels, range=(0, num_labels))[0]
 
-    union_pixels_per_class = pred_pixels + gold_pixels - intersection_pixels
-    iou_per_class = intersection_pixels / union_pixels_per_class
+    if metric_type == SemSegMetricType.dice:
+        pixels_per_class = pred_pixels + gold_pixels
+        metric_per_class = (2 * intersection_pixels) / pixels_per_class
+    else:
+        pixels_per_class = pred_pixels + gold_pixels - intersection_pixels
+        metric_per_class = intersection_pixels / pixels_per_class
 
     # fill the nans with 0s
-    union_pixels_per_class = np.nan_to_num(union_pixels_per_class)
+    pixels_per_class = np.nan_to_num(pixels_per_class)
+    data = SemSegMetricData(
+        metric=metric_type,
+        value=np.nanmean(metric_per_class),
+        value_per_class=metric_per_class.tolist(),
+        area_per_class=pixels_per_class.tolist(),
+    )
+
+    return data
+
+
+def calculate_batch_metric(
+    pred_masks: torch.Tensor,
+    gold_masks: torch.Tensor,
+    metric_type: SemSegMetricType,
+    num_labels: int,
+) -> List[SemSegMetricData]:
+    """Function to calcuate semseg metrics for each image in a batch
+
+    SemSeg metrics can be one of:
+        - Mean IoU
+        - Boundary IoU
+        - Dice coefficient
+
+    Dice score is the intersection over the total number of pixels per class.
+    We take the 'macro' average where we weight each class's dice score by the
+    amount of pixels in that class, and then after computing each class's dice
+    score we average them together.
+
+    IoU is simply the intersection over union, where boundary IoU is the IoU
+    computed on the boundary masks.
 
-    return iou_per_class, union_pixels_per_class
+    Args:
+        pred_masks (torch.Tensor): argmax of predicted probabilities
+        gold_masks (torch.Tensor): ground truth masks
+        metric_type (SemSegMetricType): type of metric to compute
+        num_labels (int): number of classes
+
+    Returns:
+        List[SemSegMetricData]: A metric data object for each image in the batch
+    """
+    pred_masks_np = pred_masks.numpy()
+    gold_masks_np = gold_masks.numpy()
+
+    metric_data = []
+    for i in range(len(pred_masks)):
+        metric_data.append(
+            compute_metric(
+                pred_masks_np[i : i + 1],
+                gold_masks_np[i : i + 1],
+                metric_type,
+                num_labels,
+            )
+        )
+    return metric_data
 
 
 def calculate_polygon_area(
     polygon: Polygon,
     height: int,
     width: int,
 ) -> int:
```

### Comparing `dataquality-0.9.2/dataquality/utils/semantic_segmentation/polygons.py` & `dataquality-0.9.3/dataquality/utils/semantic_segmentation/polygons.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/semantic_segmentation/utils.py` & `dataquality-0.9.3/dataquality/utils/semantic_segmentation/utils.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/setfit.py` & `dataquality-0.9.3/dataquality/utils/setfit.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/thread_pool.py` & `dataquality-0.9.3/dataquality/utils/thread_pool.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/torch.py` & `dataquality-0.9.3/dataquality/utils/torch.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/transformers.py` & `dataquality-0.9.3/dataquality/utils/transformers.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/ultralytics.py` & `dataquality-0.9.3/dataquality/utils/ultralytics.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/upload.py` & `dataquality-0.9.3/dataquality/utils/upload.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/vaex.py` & `dataquality-0.9.3/dataquality/utils/vaex.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality/utils/version.py` & `dataquality-0.9.3/dataquality/utils/version.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/dataquality.egg-info/PKG-INFO` & `dataquality-0.9.3/dataquality.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dataquality
-Version: 0.9.2
+Version: 0.9.3
 Author-email: "Galileo Technologies, Inc." <devs+dq@rungalileo.io>
 License: See LICENSE
 Project-URL: Homepage, https://github.com/rungalileo/dataquality
 Project-URL: Documentation, https://rungalileo.gitbook.io/galileo
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 Provides-Extra: doc
```

### Comparing `dataquality-0.9.2/dataquality.egg-info/SOURCES.txt` & `dataquality-0.9.3/dataquality.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -47,32 +47,35 @@
 dataquality/loggers/__init__.py
 dataquality/loggers/base_logger.py
 dataquality/loggers/data_logger/__init__.py
 dataquality/loggers/data_logger/base_data_logger.py
 dataquality/loggers/data_logger/image_classification.py
 dataquality/loggers/data_logger/object_detection.py
 dataquality/loggers/data_logger/semantic_segmentation.py
+dataquality/loggers/data_logger/seq2seq.py
 dataquality/loggers/data_logger/tabular_classification.py
 dataquality/loggers/data_logger/text_classification.py
 dataquality/loggers/data_logger/text_multi_label.py
 dataquality/loggers/data_logger/text_ner.py
 dataquality/loggers/logger_config/__init__.py
 dataquality/loggers/logger_config/base_logger_config.py
 dataquality/loggers/logger_config/image_classification.py
 dataquality/loggers/logger_config/object_detection.py
 dataquality/loggers/logger_config/semantic_segmentation.py
+dataquality/loggers/logger_config/seq2seq.py
 dataquality/loggers/logger_config/tabular_classification.py
 dataquality/loggers/logger_config/text_classification.py
 dataquality/loggers/logger_config/text_multi_label.py
 dataquality/loggers/logger_config/text_ner.py
 dataquality/loggers/model_logger/__init__.py
 dataquality/loggers/model_logger/base_model_logger.py
 dataquality/loggers/model_logger/image_classification.py
 dataquality/loggers/model_logger/object_detection.py
 dataquality/loggers/model_logger/semantic_segmentation.py
+dataquality/loggers/model_logger/seq2seq.py
 dataquality/loggers/model_logger/tabular_classification.py
 dataquality/loggers/model_logger/text_classification.py
 dataquality/loggers/model_logger/text_multi_label.py
 dataquality/loggers/model_logger/text_ner.py
 dataquality/schemas/__init__.py
 dataquality/schemas/condition.py
 dataquality/schemas/dataframe.py
@@ -82,19 +85,21 @@
 dataquality/schemas/metrics.py
 dataquality/schemas/model.py
 dataquality/schemas/ner.py
 dataquality/schemas/report.py
 dataquality/schemas/request_type.py
 dataquality/schemas/route.py
 dataquality/schemas/semantic_segmentation.py
+dataquality/schemas/seq2seq.py
 dataquality/schemas/split.py
 dataquality/schemas/task_type.py
 dataquality/schemas/torch.py
 dataquality/utils/__init__.py
 dataquality/utils/ampli.py
+dataquality/utils/arrow.py
 dataquality/utils/auth.py
 dataquality/utils/auto.py
 dataquality/utils/auto_trainer.py
 dataquality/utils/cloud.py
 dataquality/utils/cuda.py
 dataquality/utils/cv.py
 dataquality/utils/dq_logger.py
@@ -108,14 +113,15 @@
 dataquality/utils/imports.py
 dataquality/utils/keras.py
 dataquality/utils/ml.py
 dataquality/utils/name.py
 dataquality/utils/od.py
 dataquality/utils/patcher.py
 dataquality/utils/profiler.py
+dataquality/utils/seq2seq.py
 dataquality/utils/setfit.py
 dataquality/utils/tf.py
 dataquality/utils/thread_pool.py
 dataquality/utils/torch.py
 dataquality/utils/transformers.py
 dataquality/utils/ultralytics.py
 dataquality/utils/upload.py
```

### Comparing `dataquality-0.9.2/dataquality.egg-info/requires.txt` & `dataquality-0.9.3/dataquality.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/pyproject.toml` & `dataquality-0.9.3/pyproject.toml`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_dataquality.py` & `dataquality-0.9.3/tests/test_dataquality.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_telemetrics.py` & `dataquality-0.9.3/tests/test_telemetrics.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/data_utils.py` & `dataquality-0.9.3/tests/test_utils/data_utils.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/hf_datasets_mock.py` & `dataquality-0.9.3/tests/test_utils/hf_datasets_mock.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/hf_integration_constants.py` & `dataquality-0.9.3/tests/test_utils/hf_integration_constants.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/hf_integration_constants_inference.py` & `dataquality-0.9.3/tests/test_utils/hf_integration_constants_inference.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/lightning_model.py` & `dataquality-0.9.3/tests/test_utils/lightning_model.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/mock_data.py` & `dataquality-0.9.3/tests/test_utils/mock_data.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/mock_request.py` & `dataquality-0.9.3/tests/test_utils/mock_request.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/ner_constants.py` & `dataquality-0.9.3/tests/test_utils/ner_constants.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/pt_datasets_mock.py` & `dataquality-0.9.3/tests/test_utils/pt_datasets_mock.py`

 * *Files identical despite different names*

### Comparing `dataquality-0.9.2/tests/test_utils/tc_constants.py` & `dataquality-0.9.3/tests/test_utils/tc_constants.py`

 * *Files identical despite different names*

