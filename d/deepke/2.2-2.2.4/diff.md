# Comparing `tmp/deepke-2.2.tar.gz` & `tmp/deepke-2.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "deepke-2.2.tar", last modified: Tue Apr  4 11:17:11 2023, max compression
+gzip compressed data, was "deepke-2.2.4.tar", last modified: Wed Jun 28 14:41:19 2023, max compression
```

## Comparing `deepke-2.2.tar` & `deepke-2.2.4.tar`

### file list

```diff
@@ -1,255 +1,255 @@
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.601854 deepke-2.2/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      506 2023-04-04 11:17:11.601854 deepke-2.2/PKG-INFO
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    28945 2023-04-04 11:15:57.000000 deepke-2.2/README.md
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       38 2023-04-04 11:17:11.601854 deepke-2.2/setup.cfg
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      923 2023-04-04 11:15:57.000000 deepke-2.2/setup.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.577854 deepke-2.2/src/
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.581854 deepke-2.2/src/deepke/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      171 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/attribution_extraction/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       23 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/attribution_extraction/standard/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       85 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/attribution_extraction/standard/models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      846 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/BasicModule.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      944 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/BiLSTM.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1863 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/Capsule.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1016 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/GCN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      975 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/LM.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2257 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/PCNN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1169 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/Transformer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      192 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/attribution_extraction/standard/models/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/attribution_extraction/standard/module/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5498 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/Attention.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4152 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/CNN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1785 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/Capsule.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1595 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/Embedding.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3759 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/GCN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2144 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/RNN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6206 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/Transformer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      217 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/module/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/attribution_extraction/standard/tools/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      141 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/tools/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2195 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/tools/dataset.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1884 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/tools/metrics.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6298 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/tools/preprocess.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8713 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/tools/serializer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4112 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/tools/trainer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2964 2023-04-04 11:16:10.000000 deepke-2.2/src/deepke/attribution_extraction/standard/tools/vocab.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/attribution_extraction/standard/utils/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       45 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/utils/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4660 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/utils/ioUtils.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2580 2023-04-04 11:16:11.000000 deepke-2.2/src/deepke/attribution_extraction/standard/utils/nnUtils.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/event_extraction/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       23 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/event_extraction/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/event_extraction/standard/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/event_extraction/standard/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/event_extraction/standard/bertcrf/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       94 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/event_extraction/standard/bertcrf/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6972 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/event_extraction/standard/bertcrf/bert_crf.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    14535 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/event_extraction/standard/bertcrf/crf.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    21497 2023-04-04 11:16:27.000000 deepke-2.2/src/deepke/event_extraction/standard/bertcrf/processor_ee.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2698 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/event_extraction/standard/bertcrf/utils_ee.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/event_extraction/standard/degree/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       98 2023-04-04 11:16:27.000000 deepke-2.2/src/deepke/event_extraction/standard/degree/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    11373 2023-04-04 11:16:28.000000 deepke-2.2/src/deepke/event_extraction/standard/degree/data.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1892 2023-04-04 11:16:27.000000 deepke-2.2/src/deepke/event_extraction/standard/degree/model.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)   202461 2023-04-04 11:16:27.000000 deepke-2.2/src/deepke/event_extraction/standard/degree/template_generate_ace.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1309 2023-04-04 11:16:27.000000 deepke-2.2/src/deepke/event_extraction/standard/degree/utils.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/name_entity_re/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       94 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke/name_entity_re/cross/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       75 2023-04-04 11:16:18.000000 deepke-2.2/src/deepke/name_entity_re/cross/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/cross/extraction/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      241 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      941 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/constants.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3829 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/dataset_processer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1946 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/extraction_metrics.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1611 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/label_tree.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/cross/extraction/noiser/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       31 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/noiser/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3691 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/noiser/spot_asoc_noiser.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/cross/extraction/predict_parser/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      302 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/predict_parser/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      434 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/predict_parser/predict_parser.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9819 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/predict_parser/spotasoc_predict_parser.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3151 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/predict_parser/utils.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1912 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/record_schema.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    25324 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/scorer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2567 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/cross/extraction/utils.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/cross/sel2record/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       47 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/sel2record/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    15487 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/sel2record/record.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4805 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/sel2record/sel2record.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      236 2023-04-04 11:16:18.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10957 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constrained_seq2seq.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1059 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2720 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/constraint_decoder.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12011 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/spotasoc_constraint_decoder.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      473 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2430 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/hybird_data_collator.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12194 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/meta_data_collator.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8521 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/t5mlm_data_collator.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3321 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/features.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    84245 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/modeling_t5.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    22273 2023-04-04 11:16:18.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/models.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4186 2023-04-04 11:16:20.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/t5_bert_tokenizer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10220 2023-04-04 11:16:19.000000 deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/trainer_arguments.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/few_shot/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       64 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/few_shot/models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       49 2023-04-04 11:16:18.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/models/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    36320 2023-04-04 11:16:18.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/models/model.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    70505 2023-04-04 11:16:18.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/models/modeling_bart.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/few_shot/module/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       95 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/module/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12200 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/module/datasets.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4886 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/module/mapping_type.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3806 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/module/metrics.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10334 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/module/train.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/few_shot/utils/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       19 2023-04-04 11:16:18.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/utils/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6012 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/name_entity_re/few_shot/utils/util.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/multimodal/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/multimodal/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.589854 deepke-2.2/src/deepke/name_entity_re/multimodal/models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3215 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/multimodal/models/IFA_model.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       52 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/multimodal/models/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    35007 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/multimodal/models/modeling_IFA.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/name_entity_re/multimodal/modules/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/multimodal/modules/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7592 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/name_entity_re/multimodal/modules/dataset.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    16969 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/name_entity_re/multimodal/modules/train.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/name_entity_re/standard/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       42 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/standard/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/name_entity_re/standard/models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1505 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/standard/models/BiLSTM_CRF.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7626 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/standard/models/InferBert.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       50 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/standard/models/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/name_entity_re/standard/tools/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       48 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/standard/tools/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3312 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/standard/tools/dataset.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5625 2023-04-04 11:16:21.000000 deepke-2.2/src/deepke/name_entity_re/standard/tools/preprocess.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/name_entity_re/standard/w2ner/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       68 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/standard/w2ner/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9024 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/standard/w2ner/data_loader.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9471 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/standard/w2ner/model.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3436 2023-04-04 11:16:22.000000 deepke-2.2/src/deepke/name_entity_re/standard/w2ner/utils.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       98 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/document/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      138 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/document/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5962 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/document/evaluation.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1723 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/document/losses.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8509 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/document/model.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3791 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/document/module.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10803 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/document/prepro.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2635 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/document/utils.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/few_shot/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      112 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       23 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2174 2023-04-04 11:16:12.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/base_data_module.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1799 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/dialogue.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    36438 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/processor.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1667 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/generate_k_shot.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1332 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/get_label_word.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       78 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4581 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/base.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9432 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/transformer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6979 2023-04-04 11:16:13.000000 deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/util.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/multimodal/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/multimodal/models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3714 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/models/IFA_model.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       52 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/models/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    35007 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/models/modeling_IFA.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/multimodal/modules/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       66 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/modules/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8659 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/modules/dataset.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1340 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/modules/metrics.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12010 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/relation_extraction/multimodal/modules/train.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.593854 deepke-2.2/src/deepke/relation_extraction/standard/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       85 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/relation_extraction/standard/models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      845 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/BasicModule.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      904 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/BiLSTM.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1819 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/Capsule.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      972 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/GCN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      974 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/LM.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2216 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/PCNN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1128 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/Transformer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      192 2023-04-04 11:16:16.000000 deepke-2.2/src/deepke/relation_extraction/standard/models/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/relation_extraction/standard/module/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4722 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/Attention.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4148 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/CNN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1785 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/Capsule.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1518 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/Embedding.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1482 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/GCN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2143 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/RNN.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6206 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/Transformer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      217 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/module/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/relation_extraction/standard/tools/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      161 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2080 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/dataset.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3708 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/loss.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1884 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/metrics.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9080 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/preprocess.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8714 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/serializer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4112 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/trainer.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2966 2023-04-04 11:16:14.000000 deepke-2.2/src/deepke/relation_extraction/standard/tools/vocab.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/relation_extraction/standard/utils/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       45 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/utils/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4660 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/utils/ioUtils.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2580 2023-04-04 11:16:15.000000 deepke-2.2/src/deepke/relation_extraction/standard/utils/nnUtils.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3671 2023-04-04 11:16:17.000000 deepke-2.2/src/deepke/transform_data.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/triple_extraction/
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/triple_extraction/ASP/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      103 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/triple_extraction/ASP/metrics/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      122 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/metrics/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9746 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/metrics/blanc.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4210 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/metrics/conll.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10783 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/metrics/metrics.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/triple_extraction/ASP/modeling_transformer/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       31 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/modeling_transformer/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1118 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/modeling_transformer/modeling_outputs.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.597854 deepke-2.2/src/deepke/triple_extraction/ASP/models/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      151 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12058 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/model_coref.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    13011 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/model_ere.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10341 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/model_ner.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1118 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/modeling_outputs.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    25647 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/t5_coref.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    27032 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/t5_ere.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    22005 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/ASP/models/t5_ner.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.601854 deepke-2.2/src/deepke/triple_extraction/ASP/util/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       60 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/util/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    16182 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/util/func.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10396 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/util/multigpu_fused_adam.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12983 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/util/runner.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10400 2023-04-04 11:16:23.000000 deepke-2.2/src/deepke/triple_extraction/ASP/util/tensorize_coref.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    13348 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/util/tensorize_ere.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8976 2023-04-04 11:16:24.000000 deepke-2.2/src/deepke/triple_extraction/ASP/util/tensorize_ner.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.601854 deepke-2.2/src/deepke/triple_extraction/PRGC/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      193 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5673 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/dataloader.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7656 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/dataloader_utils.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7072 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/evaluate.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4364 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/metrics.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10925 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/model.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    13225 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/optimization.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5082 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/PRGC/util.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.601854 deepke-2.2/src/deepke/triple_extraction/PURE/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:16:26.000000 deepke-2.2/src/deepke/triple_extraction/PURE/__init__.py
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       62 2023-04-04 11:16:25.000000 deepke-2.2/src/deepke/triple_extraction/__init__.py
-drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-04-04 11:17:11.585854 deepke-2.2/src/deepke.egg-info/
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      506 2023-04-04 11:17:11.000000 deepke-2.2/src/deepke.egg-info/PKG-INFO
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10994 2023-04-04 11:17:11.000000 deepke-2.2/src/deepke.egg-info/SOURCES.txt
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        1 2023-04-04 11:17:11.000000 deepke-2.2/src/deepke.egg-info/dependency_links.txt
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      332 2023-04-04 11:17:11.000000 deepke-2.2/src/deepke.egg-info/requires.txt
--rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        7 2023-04-04 11:17:11.000000 deepke-2.2/src/deepke.egg-info/top_level.txt
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.770013 deepke-2.2.4/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      508 2023-06-28 14:41:19.770013 deepke-2.2.4/PKG-INFO
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    31766 2023-06-28 14:38:37.000000 deepke-2.2.4/README.md
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       38 2023-06-28 14:41:19.770013 deepke-2.2.4/setup.cfg
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      925 2023-06-28 14:41:17.000000 deepke-2.2.4/setup.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.750013 deepke-2.2.4/src/
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      171 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/attribution_extraction/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       23 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/attribution_extraction/standard/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       85 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      846 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/BasicModule.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      944 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/BiLSTM.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1863 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/Capsule.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1016 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/GCN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      975 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/LM.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2257 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/PCNN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1169 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/Transformer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      192 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/models/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5498 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Attention.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4152 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/CNN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1785 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Capsule.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1595 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Embedding.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3759 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/GCN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2144 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/RNN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6206 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Transformer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      217 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/module/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      141 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2195 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/dataset.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1884 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/metrics.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6298 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/preprocess.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8713 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/serializer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4112 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/trainer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2964 2023-06-28 14:38:39.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/vocab.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/attribution_extraction/standard/utils/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       45 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/utils/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4660 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/utils/ioUtils.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2580 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/attribution_extraction/standard/utils/nnUtils.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/event_extraction/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       23 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/event_extraction/standard/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       94 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6972 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/bert_crf.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    14535 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/crf.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    21497 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/processor_ee.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2698 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/utils_ee.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/event_extraction/standard/degree/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       98 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/degree/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    11373 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/degree/data.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1892 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/degree/model.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)   202461 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/degree/template_generate_ace.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1309 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/event_extraction/standard/degree/utils.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke/name_entity_re/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       94 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       75 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      241 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      941 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/constants.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3829 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/dataset_processer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1946 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/extraction_metrics.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1611 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/label_tree.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/noiser/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       31 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/noiser/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3691 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/noiser/spot_asoc_noiser.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/predict_parser/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      302 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/predict_parser/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      434 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/predict_parser/predict_parser.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9819 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/predict_parser/spotasoc_predict_parser.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3151 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/predict_parser/utils.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1912 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/record_schema.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    25324 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/scorer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2567 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/utils.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/sel2record/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       47 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/sel2record/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    15487 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/sel2record/record.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4805 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/sel2record/sel2record.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      236 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10957 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constrained_seq2seq.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1059 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2720 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/constraint_decoder.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12011 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/spotasoc_constraint_decoder.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      398 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2430 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/hybird_data_collator.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12194 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/meta_data_collator.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8521 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/t5mlm_data_collator.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3321 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/features.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    84245 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/modeling_t5.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    22273 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/models.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4186 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/t5_bert_tokenizer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10220 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/trainer_arguments.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/few_shot/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       64 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/few_shot/models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       49 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/models/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    36327 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/models/model.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    70505 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/models/modeling_bart.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       95 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12200 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/datasets.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4886 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/mapping_type.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3806 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/metrics.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10334 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/train.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/few_shot/utils/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       19 2023-06-28 14:38:43.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/utils/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6012 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/name_entity_re/few_shot/utils/util.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/multimodal/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/multimodal/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.758013 deepke-2.2.4/src/deepke/name_entity_re/multimodal/models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3215 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/name_entity_re/multimodal/models/IFA_model.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       52 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/name_entity_re/multimodal/models/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    35007 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/multimodal/models/modeling_IFA.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/name_entity_re/multimodal/modules/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/name_entity_re/multimodal/modules/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7592 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/name_entity_re/multimodal/modules/dataset.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    16969 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/name_entity_re/multimodal/modules/train.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/name_entity_re/standard/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       42 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/name_entity_re/standard/models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1505 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/models/BiLSTM_CRF.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7717 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/models/InferBert.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       50 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/models/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/name_entity_re/standard/tools/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       48 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/tools/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3312 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/tools/dataset.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5625 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/tools/preprocess.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       68 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9024 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/data_loader.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9471 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/model.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3436 2023-06-28 14:38:44.000000 deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/utils.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       98 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/document/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      138 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/document/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5962 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/document/evaluation.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1723 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/document/losses.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8509 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/document/model.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3791 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/document/module.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10803 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/document/prepro.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2635 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/document/utils.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/few_shot/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      112 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       23 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2174 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/base_data_module.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1799 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/dialogue.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    36438 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/processor.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1667 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/generate_k_shot.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1332 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/get_label_word.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       78 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4581 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/base.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9432 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/transformer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6979 2023-06-28 14:38:40.000000 deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/util.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/multimodal/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       44 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/multimodal/models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3714 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/models/IFA_model.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       52 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/models/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    35007 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/models/modeling_IFA.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       66 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8659 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/dataset.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1340 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/metrics.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12010 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/train.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/standard/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       85 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.762013 deepke-2.2.4/src/deepke/relation_extraction/standard/models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      845 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/BasicModule.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      904 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/BiLSTM.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1819 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/Capsule.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      972 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/GCN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      974 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/LM.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2216 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/PCNN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1128 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/Transformer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      192 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/models/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/relation_extraction/standard/module/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4722 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/Attention.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4148 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/CNN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1785 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/Capsule.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1518 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/Embedding.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1482 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/GCN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2143 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/RNN.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     6206 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/Transformer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      217 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/module/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      161 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2080 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/dataset.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3708 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/loss.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1884 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/metrics.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9080 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/preprocess.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8714 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/serializer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4112 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/trainer.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2966 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/tools/vocab.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/relation_extraction/standard/utils/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       45 2023-06-28 14:38:41.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/utils/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4660 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/utils/ioUtils.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     2580 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/relation_extraction/standard/utils/nnUtils.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     3671 2023-06-28 14:38:42.000000 deepke-2.2.4/src/deepke/transform_data.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/triple_extraction/
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/triple_extraction/ASP/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      103 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      122 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     9746 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/blanc.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4210 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/conll.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10783 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/metrics.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/triple_extraction/ASP/modeling_transformer/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       31 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/modeling_transformer/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1118 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/modeling_transformer/modeling_outputs.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      151 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12058 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/model_coref.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    13011 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/model_ere.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10341 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/model_ner.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     1118 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/modeling_outputs.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    25647 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/t5_coref.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    27032 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/t5_ere.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    22005 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/models/t5_ner.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       60 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    16182 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/func.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10396 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/multigpu_fused_adam.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    12983 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/runner.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10400 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/tensorize_coref.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    13348 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/tensorize_ere.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     8976 2023-06-28 14:38:45.000000 deepke-2.2.4/src/deepke/triple_extraction/ASP/util/tensorize_ner.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.766013 deepke-2.2.4/src/deepke/triple_extraction/PRGC/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      173 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5673 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/dataloader.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7656 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/dataloader_utils.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     7072 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/evaluate.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     4364 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/metrics.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10925 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/model.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    13225 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/optimization.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)     5082 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PRGC/util.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.770013 deepke-2.2.4/src/deepke/triple_extraction/PURE/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/PURE/__init__.py
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)       62 2023-06-28 14:38:46.000000 deepke-2.2.4/src/deepke/triple_extraction/__init__.py
+drwxrwxr-x   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        0 2023-06-28 14:41:19.754013 deepke-2.2.4/src/deepke.egg-info/
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      508 2023-06-28 14:41:19.000000 deepke-2.2.4/src/deepke.egg-info/PKG-INFO
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)    10994 2023-06-28 14:41:19.000000 deepke-2.2.4/src/deepke.egg-info/SOURCES.txt
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        1 2023-06-28 14:41:19.000000 deepke-2.2.4/src/deepke.egg-info/dependency_links.txt
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)      343 2023-06-28 14:41:19.000000 deepke-2.2.4/src/deepke.egg-info/requires.txt
+-rw-rw-r--   0 qiaoshuofei  (1005) qiaoshuofei  (1005)        7 2023-06-28 14:41:19.000000 deepke-2.2.4/src/deepke.egg-info/top_level.txt
```

### Comparing `deepke-2.2/README.md` & `deepke-2.2.4/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -26,88 +26,79 @@
 
 <h1 align="center">
     <p>A Deep Learning Based Knowledge Extraction Toolkit<br>for Knowledge Graph Construction</p>
 </h1>
 
 
 [DeepKE](https://arxiv.org/pdf/2201.03335.pdf) is a knowledge extraction toolkit for knowledge graph construction supporting **cnSchema**，**low-resource**, **document-level** and **multimodal** scenarios for *entity*, *relation* and *attribute* extraction. We provide [documents](https://zjunlp.github.io/DeepKE/), [Google Colab tutorials](https://colab.research.google.com/drive/1vS8YJhJltzw3hpJczPt24O0Azcs3ZpRi?usp=sharing), [online demo](http://deepke.zjukg.cn/), [paper](https://arxiv.org/pdf/2201.03335.pdf), [slides](https://drive.google.com/file/d/1IIeIZAbVduemqXc4zD40FUMoPHCJinLy/view?usp=sharing) and [poster](https://drive.google.com/file/d/1vd7xVHlWzoAxivN4T5qKrcqIGDcSM1_7/view?usp=sharing) for beginners.
+- ❗Want to use Large Language Models with DeepKE? Try [DeepKE-LLM](https://github.com/zjunlp/DeepKE/tree/main/example/llm) with [KnowLM](https://github.com/zjunlp/KnowLM), have fun!
+- ❗Want to train supervised models? Try [Quick Start](#quick-start), we provide the NER models (e.g, [LightNER(COLING'22)](https://github.com/zjunlp/DeepKE/tree/main/example/ner/few-shot), [W2NER(AAAI'22)](https://github.com/zjunlp/DeepKE/tree/main/example/ner/standard/w2ner)), relation extraction models (e.g., [KnowPrompt(WWW'22)](https://github.com/zjunlp/DeepKE/tree/main/example/re/few-shot)), relational triple extraction models (e.g., [ASP(EMNLP'22)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/ASP), [PRGC(ACL'21)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/PRGC), [PURE(NAACL'21)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/PURE)), and release off-the-shelf  models at [DeepKE-cnSchema](https://github.com/zjunlp/DeepKE/tree/main/example/triple/cnschema), have fun!
 
-**Reading Materials**:
-
-Data-Efficient Knowledge Graph Construction, 高效知识图谱构建 ([Tutorial on CCKS 2022](http://sigkg.cn/ccks2022/?page_id=24)) \[[slides](https://drive.google.com/drive/folders/1xqeREw3dSiw-Y1rxLDx77r0hGUvHnuuE)\] 
-
-Efficient and Robust Knowledge Graph Construction ([Tutorial on AACL-IJCNLP 2022](https://www.aacl2022.org/Program/tutorials)) \[[slides](https://github.com/NLP-Tutorials/AACL-IJCNLP2022-KGC-Tutorial)\] 
-
-PromptKG Family: a Gallery of Prompt Learning & KG-related Research Works, Toolkits, and Paper-list [[Resources](https://github.com/zjunlp/PromptKG)\] 
-
-Knowledge Extraction in Low-Resource Scenarios: Survey and Perspective \[[Survey](https://arxiv.org/abs/2202.08063)\]\[[Paper-list](https://github.com/zjunlp/Low-resource-KEPapers)\]
-
-Reasoning with Language Model Prompting \[[Survey](https://arxiv.org/abs/2212.09597)\]\[[Paper-list](https://github.com/zjunlp/Prompt4ReasoningPapers)\]\[[ppt](https://github.com/zjunlp/Prompt4ReasoningPapers/blob/main/tutorial.pdf)\]
-
+# Table of Contents
 
+- [Table of Contents](#table-of-contents)
+- [What's New](#whats-new)
+- [Prediction Demo](#prediction-demo)
+- [Model Framework](#model-framework)
+- [Quick Start](#quick-start)
+  - [DeepKE-LLM](#deepke-llm)
+  - [DeepKE](#deepke)
+  - [Requirements](#requirements)
+    - [DeepKE-LLM](#deepke-llm-1)
+    - [DeepKE](#deepke-1)
+  - [Introduction of Three Functions](#introduction-of-three-functions)
+    - [1. Named Entity Recognition](#1-named-entity-recognition)
+    - [2. Relation Extraction](#2-relation-extraction)
+    - [3. Attribute Extraction](#3-attribute-extraction)
+    - [4. Event Extraction](#4-event-extraction)
+- [Notebook Tutorial](#notebook-tutorial)
+- [Tips](#tips)
+- [To do](#to-do)
+- [Reading Materials](#reading-materials)
+- [Related Toolkit](#related-toolkit)
+- [Citation](#citation)
+- [Contributors (Determined by the roll of the dice)](#contributors-determined-by-the-roll-of-the-dice)
+- [Other Knowledge Extraction Open-Source Projects](#other-knowledge-extraction-open-source-projects)
 
-**Related Toolkit**:
+<br>
 
-[Doccano](https://github.com/doccano/doccano)、[MarkTool](https://github.com/FXLP/MarkTool)、[LabelStudio](https://labelstud.io/ ): Data Annotation Toolkits
+# What's New
+* `June, 2023` We update [DeepKE-LLM](https://github.com/zjunlp/DeepKE/tree/main/example/llm) to support **knowledge extraction** with [KnowLM](https://github.com/zjunlp/KnowLM), [ChatGLM](https://github.com/THUDM/ChatGLM-6B), LLaMA-series, GPT-series etc.
+* `Apr, 2023` We have added new models, including [CP-NER(IJCAI'23)](https://github.com/zjunlp/DeepKE/blob/main/example/ner/cross), [ASP(EMNLP'22)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/ASP), [PRGC(ACL'21)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/PRGC), [PURE(NAACL'21)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/PURE), provided [event extraction](https://github.com/zjunlp/DeepKE/tree/main/example/ee/standard) capabilities (Chinese and English), and offered compatibility with higher versions of Python packages (e.g., Transformers).
 
-[LambdaKG](https://github.com/zjunlp/PromptKG/tree/main/lambdaKG): A library and benchmark for PLM-based KG embeddings
+* `Feb, 2023` We have supported using [LLM](https://github.com/zjunlp/DeepKE/tree/main/example/llm) (GPT-3) with in-context learning (based on [EasyInstruct](https://github.com/zjunlp/EasyInstruct)) & data generation, added a NER model [W2NER(AAAI'22)](https://github.com/zjunlp/DeepKE/tree/main/example/ner/standard/w2ner).
 
-[EasyInstruct](https://github.com/zjunlp/EasyInstruct): An easy-to-use framework to instruct Large Language Models
+<details>
+<summary><b>Previous News</b></summary>
+  
+* `Nov, 2022` Add data [annotation instructions](https://github.com/zjunlp/DeepKE/blob/main/README_TAG.md) for entity recognition and relation extraction, automatic labelling of weakly supervised data ([entity extraction](https://github.com/zjunlp/DeepKE/tree/main/example/ner/prepare-data) and [relation extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/prepare-data)), and optimize [multi-GPU training](https://github.com/zjunlp/DeepKE/tree/main/example/re/standard).
+  
+* `Sept, 2022` The paper [DeepKE: A Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population](https://arxiv.org/abs/2201.03335) has been accepted by the EMNLP 2022 System Demonstration Track.
 
+* `Aug, 2022` We have added [data augmentation](https://github.com/zjunlp/DeepKE/tree/main/example/re/few-shot/DA) (Chinese, English) support for [low-resource relation extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/few-shot).
 
-# Table of Contents
+* `June, 2022` We have added multimodal support for [entity](https://github.com/zjunlp/DeepKE/tree/main/example/ner/multimodal) and [relation extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/multimodal).
+ 
+* `May, 2022` We have released [DeepKE-cnschema](https://github.com/zjunlp/DeepKE/blob/main/README_CNSCHEMA.md) with off-the-shelf knowledge extraction models.
 
-* [What's New](#whats-new)
-* [Prediction Demo](#prediction-demo)
-* [Model Framework](#model-framework)
-* [Quick Start](#quick-start)
-   * [Requirements](#requirements)
-   * [Introduction of Three Functions](#introduction-of-three-functions)
-      * [1. Named Entity Recognition](#1-named-entity-recognition)
-      * [2. Relation Extraction](#2-relation-extraction)
-      * [3. Attribute Extraction](#3-attribute-extraction)
-* [Notebook Tutorial](#notebook-tutorial)
-* [Tips](#tips)
-* [To do](#to-do)
-* [Citation](#citation)
-* [Contributors](#contributors)
-* [Other Knowledge Extraction Open-Source Projects](#other-knowledge-extraction-open-source-projects)
+* `Jan, 2022` We have released a paper [DeepKE: A Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population](https://arxiv.org/abs/2201.03335)
 
-<br>
+* `Dec, 2021` We have added `dockerfile` to create the enviroment automatically. 
 
-# What's New
-## Apr, 2023
-* We have added new models, including [CP-NER](https://github.com/zjunlp/DeepKE/blob/main/example/ner/cross), [ASP(EMNLP'22)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/ASP), [PRGC(ACL'21)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/PRGC), [PURE(NAACL'21)](https://github.com/zjunlp/DeepKE/tree/main/example/triple/PURE), provided [event extraction](https://github.com/zjunlp/DeepKE/tree/main/example/ee/standard) capabilities (Chinese and English), and offered compatibility with higher versions of Python packages (e.g., Transformers).
-## Feb, 2023
-* We have supported using [LLM](https://github.com/zjunlp/DeepKE/tree/main/example/llm) (GPT-3) with in-context learning (based on [EasyInstruct](https://github.com/zjunlp/EasyInstruct)) & data generation, added a NER model [W2NER(AAAI'22)](https://github.com/zjunlp/DeepKE/tree/main/example/ner/standard/w2ner).
-## Nov, 2022
-* Add data [annotation instructions](https://github.com/zjunlp/DeepKE/blob/main/README_TAG.md) for entity recognition and relation extraction, automatic labelling of weakly supervised data ([entity extraction](https://github.com/zjunlp/DeepKE/tree/main/example/ner/prepare-data) and [relation extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/prepare-data)), and optimize [multi-GPU training](https://github.com/zjunlp/DeepKE/tree/main/example/re/standard).
-## Sept, 2022
-* The paper [DeepKE: A Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population](https://arxiv.org/abs/2201.03335) has been accepted by the EMNLP 2022 System Demonstration Track.
-## Aug, 2022
-* We have added [data augmentation](https://github.com/zjunlp/DeepKE/tree/main/example/re/few-shot/DA) (Chinese, English) support for [low-resource relation extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/few-shot).
-## June, 2022
-* We have added multimodal support for [entity](https://github.com/zjunlp/DeepKE/tree/main/example/ner/multimodal) and [relation extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/multimodal).
-## May, 2022
-* We have released [DeepKE-cnschema](https://github.com/zjunlp/DeepKE/blob/main/README_CNSCHEMA.md) with off-the-shelf knowledge extraction models.
-## Jan, 2022
-* We have released a paper [DeepKE: A Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population](https://arxiv.org/abs/2201.03335)
-## Dec, 2021
-* We have added `dockerfile` to create the enviroment automatically. 
-## Nov, 2021
-* The demo of DeepKE, supporting real-time extration without deploying and training, has been released.
+* `Nov, 2021` The demo of DeepKE, supporting real-time extration without deploying and training, has been released.
 * The documentation of DeepKE, containing the details of DeepKE such as source codes and datasets, has been released.
-## Oct, 2021
-* `pip install deepke`
+ 
+* `Oct, 2021` `pip install deepke`
 * The codes of deepke-v2.0 have been released.
-## Aug, 2019
-* The codes of deepke-v1.0 have been released.
-## Aug, 2018
-* The project DeepKE startup and codes of deepke-v0.1 have been released.
-<br>
+
+* `Aug, 2019` The codes of deepke-v1.0 have been released.
+
+* `Aug, 2018` The project DeepKE startup and codes of deepke-v0.1 have been released.
+  
+</details>
 
 # Prediction Demo
 
 There is a demonstration of prediction. The GIF file is created by [Terminalizer](https://github.com/faressoft/terminalizer). Get the [code](https://drive.google.com/file/d/1r4tWfAkpvynH3CBSgd-XG79rf-pB-KR3/view?usp=share_link).
 <img src="pics/demo.gif" width="636" height="494" align=center>
 
 <br>
@@ -123,14 +114,29 @@
 - Each task can be implemented in different scenarios. For example, we can achieve relation extraction in **standard**, **low-resource (few-shot)**, **document-level** and **multimodal** settings.
 - Each application scenario comprises of three components: **Data** including Tokenizer, Preprocessor and Loader, **Model** including Module, Encoder and Forwarder, **Core** including Training, Evaluation and Prediction. 
 
 <br>
 
 # Quick Start
 
+## DeepKE-LLM
+
+In the era of large models, DeepKE-LLM utilizes a completely new environment dependency.
+
+```
+conda create -n deepke-llm python=3.9
+conda activate deepke-llm
+
+cd example/llm
+pip install -r requirements.txt
+```
+
+Please note that the `requirements.txt` file is located in the `example/llm` folder.
+
+## DeepKE
 *DeepKE* supports `pip install deepke`. <br>Take the fully supervised relation extraction for example.
 
 **Step1** Download the basic code
 
 ```bash
 git clone --depth 1 https://github.com/zjunlp/DeepKE.git
 ```
@@ -192,24 +198,38 @@
 python predict.py
 ```
 
  - **❗NOTE: if you encounter any errors, please refer to the [Tips](#tips) or submit a GitHub issue.**
 
 ## Requirements
 
+### DeepKE-LLM
+
+> python == 3.9
+
+- torch==1.13.0
+- accelerate==0.17.1
+- transformers==4.28.1
+- bitsandbytes==0.37.2
+- peft==0.2.0
+- gradio
+- datasets
+- sentencepiece
+- fire
+
+### DeepKE
 > python == 3.8
 
 - torch == 1.5
 - hydra-core == 1.0.6
 - tensorboard == 2.4.1
 - matplotlib == 3.4.1
 - transformers == 3.4.0
 - jieba == 0.42.1
 - scikit-learn == 0.24.1
-- pytorch-transformers == 1.2.0
 - seqeval == 1.2.2
 - tqdm == 4.60.0
 - opt-einsum==3.3.0
 - wandb==0.12.7
 - ujson
 
 ## Introduction of Three Functions
@@ -606,62 +626,88 @@
 
 5.It's recommended to install *DeepKE* with source codes. Because user may meet some problems in Windows system with 'pip',and the source code modification will not work,see[issue](https://github.com/zjunlp/DeepKE/issues/117)
 
 6.More related low-resource knowledge extraction  works can be found in [Knowledge Extraction in Low-Resource Scenarios: Survey and Perspective](https://arxiv.org/pdf/2202.08063.pdf).
 
 7.Make sure the exact versions of requirements in `requirements.txt`.
 
+# To do
+In next version, we plan to release a multimodal LLM for KE. 
 
+Meanwhile, we will offer long-term maintenance to **fix bugs**, **solve issues** and meet **new requests**. So if you have any problems, please put issues to us.
 
-<br>
+# Reading Materials
 
-# To do
-In next version, we plan to release a LLM for KE. 
+Data-Efficient Knowledge Graph Construction, 高效知识图谱构建 ([Tutorial on CCKS 2022](http://sigkg.cn/ccks2022/?page_id=24)) \[[slides](https://drive.google.com/drive/folders/1xqeREw3dSiw-Y1rxLDx77r0hGUvHnuuE)\] 
 
-Meanwhile, we will offer long-term maintenance to **fix bugs**, **solve issues** and meet **new requests**. So if you have any problems, please put issues to us.
+Efficient and Robust Knowledge Graph Construction ([Tutorial on AACL-IJCNLP 2022](https://www.aacl2022.org/Program/tutorials)) \[[slides](https://github.com/NLP-Tutorials/AACL-IJCNLP2022-KGC-Tutorial)\] 
 
-<br>
+PromptKG Family: a Gallery of Prompt Learning & KG-related Research Works, Toolkits, and Paper-list [[Resources](https://github.com/zjunlp/PromptKG)\] 
+
+Knowledge Extraction in Low-Resource Scenarios: Survey and Perspective \[[Survey](https://arxiv.org/abs/2202.08063)\]\[[Paper-list](https://github.com/zjunlp/Low-resource-KEPapers)\]
+
+
+# Related Toolkit
+
+[Doccano](https://github.com/doccano/doccano)、[MarkTool](https://github.com/FXLP/MarkTool)、[LabelStudio](https://labelstud.io/ ): Data Annotation Toolkits
+
+[LambdaKG](https://github.com/zjunlp/PromptKG/tree/main/lambdaKG): A library and benchmark for PLM-based KG embeddings
+
+[EasyInstruct](https://github.com/zjunlp/EasyInstruct): An easy-to-use framework to instruct Large Language Models
+
+**Reading Materials**:
+
+Data-Efficient Knowledge Graph Construction, 高效知识图谱构建 ([Tutorial on CCKS 2022](http://sigkg.cn/ccks2022/?page_id=24)) \[[slides](https://drive.google.com/drive/folders/1xqeREw3dSiw-Y1rxLDx77r0hGUvHnuuE)\] 
+
+Efficient and Robust Knowledge Graph Construction ([Tutorial on AACL-IJCNLP 2022](https://www.aacl2022.org/Program/tutorials)) \[[slides](https://github.com/NLP-Tutorials/AACL-IJCNLP2022-KGC-Tutorial)\] 
+
+PromptKG Family: a Gallery of Prompt Learning & KG-related Research Works, Toolkits, and Paper-list [[Resources](https://github.com/zjunlp/PromptKG)\] 
+
+Knowledge Extraction in Low-Resource Scenarios: Survey and Perspective \[[Survey](https://arxiv.org/abs/2202.08063)\]\[[Paper-list](https://github.com/zjunlp/Low-resource-KEPapers)\]
+
+
+**Related Toolkit**:
+
+[Doccano](https://github.com/doccano/doccano)、[MarkTool](https://github.com/FXLP/MarkTool)、[LabelStudio](https://labelstud.io/ ): Data Annotation Toolkits
+
+[LambdaKG](https://github.com/zjunlp/PromptKG/tree/main/lambdaKG): A library and benchmark for PLM-based KG embeddings
+
+[EasyInstruct](https://github.com/zjunlp/EasyInstruct): An easy-to-use framework to instruct Large Language Models
 
 # Citation
 
 Please cite our paper if you use DeepKE in your work
 
 ```bibtex
-@inproceedings{DBLP:conf/emnlp/ZhangXTYYQXCLL22,
+@inproceedings{EMNLP2022_Demo_DeepKE,
   author    = {Ningyu Zhang and
                Xin Xu and
                Liankuan Tao and
                Haiyang Yu and
                Hongbin Ye and
                Shuofei Qiao and
                Xin Xie and
                Xiang Chen and
                Zhoubo Li and
                Lei Li},
   editor    = {Wanxiang Che and
                Ekaterina Shutova},
-  title     = {DeepKE: {A} Deep Learning Based Knowledge Extraction Toolkit for Knowledge
-               Base Population},
-  booktitle = {Proceedings of the The 2022 Conference on Empirical Methods in Natural
-               Language Processing, {EMNLP} 2022 - System Demonstrations, Abu Dhabi,
-               UAE, December 7-11, 2022},
+  title     = {DeepKE: {A} Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population},
+  booktitle = {{EMNLP} (Demos)},
   pages     = {98--108},
   publisher = {Association for Computational Linguistics},
   year      = {2022},
-  url       = {https://aclanthology.org/2022.emnlp-demos.10},
-  timestamp = {Thu, 23 Mar 2023 16:56:00 +0100},
-  biburl    = {https://dblp.org/rec/conf/emnlp/ZhangXTYYQXCLL22.bib},
-  bibsource = {dblp computer science bibliography, https://dblp.org}
+  url       = {https://aclanthology.org/2022.emnlp-demos.10}
 }
 ```
 <br>
 
-# Contributors
+# Contributors (Determined by the roll of the dice)
 
-Zhejiang University: [Ningyu Zhang](https://person.zju.edu.cn/en/ningyu), Liankuan Tao, Xin Xu, Xinrong Li, Haiyang Yu, Hongbin Ye, Shuofei Qiao, Peng Wang, Yuqi Zhu, Xin Xie, Xiang Chen, Zhoubo Li, Lei Li, Xiaozhuan Liang, Yunzhi Yao, Shumin Deng, Wen Zhang, Guozhou Zheng, Huajun Chen
+Zhejiang University: [Ningyu Zhang](https://person.zju.edu.cn/en/ningyu), Liankuan Tao, Xin Xu, Honghao Gui, Xiaohan Wang, Zekun Xi, Xinrong Li, Haiyang Yu, Hongbin Ye, Shuofei Qiao, Peng Wang, Yuqi Zhu, Xin Xie, Xiang Chen, Zhoubo Li, Lei Li, Xiaozhuan Liang, Yunzhi Yao, Jing Chen, Yuqi Zhu, Shumin Deng, Wen Zhang, Guozhou Zheng, Huajun Chen
 
 Community Contributors: [thredreams](https://github.com/thredreams), [eltociear](https://github.com/eltociear)
 
 Alibaba Group: Feiyu Xiong, Qiang Chen
 
 DAMO Academy: Zhenru Zhang, Chuanqi Tan, Fei Huang
```

#### html2text {}

```diff
@@ -9,96 +9,102 @@
 *relation* and *attribute* extraction. We provide [documents](https://
 zjunlp.github.io/DeepKE/), [Google Colab tutorials](https://
 colab.research.google.com/drive/1vS8YJhJltzw3hpJczPt24O0Azcs3ZpRi?usp=sharing),
 [online demo](http://deepke.zjukg.cn/), [paper](https://arxiv.org/pdf/
 2201.03335.pdf), [slides](https://drive.google.com/file/d/
 1IIeIZAbVduemqXc4zD40FUMoPHCJinLy/view?usp=sharing) and [poster](https://
 drive.google.com/file/d/1vd7xVHlWzoAxivN4T5qKrcqIGDcSM1_7/view?usp=sharing) for
-beginners. **Reading Materials**: Data-Efficient Knowledge Graph Construction,
-é«æç¥è¯å¾è°±æå»º ([Tutorial on CCKS 2022](http://sigkg.cn/ccks2022/
-?page_id=24)) \[[slides](https://drive.google.com/drive/folders/1xqeREw3dSiw-
-Y1rxLDx77r0hGUvHnuuE)\] Efficient and Robust Knowledge Graph Construction (
-[Tutorial on AACL-IJCNLP 2022](https://www.aacl2022.org/Program/tutorials)) \[
-[slides](https://github.com/NLP-Tutorials/AACL-IJCNLP2022-KGC-Tutorial)\]
-PromptKG Family: a Gallery of Prompt Learning & KG-related Research Works,
-Toolkits, and Paper-list [[Resources](https://github.com/zjunlp/PromptKG)\]
-Knowledge Extraction in Low-Resource Scenarios: Survey and Perspective \[
-[Survey](https://arxiv.org/abs/2202.08063)\]\[[Paper-list](https://github.com/
-zjunlp/Low-resource-KEPapers)\] Reasoning with Language Model Prompting \[
-[Survey](https://arxiv.org/abs/2212.09597)\]\[[Paper-list](https://github.com/
-zjunlp/Prompt4ReasoningPapers)\]\[[ppt](https://github.com/zjunlp/
-Prompt4ReasoningPapers/blob/main/tutorial.pdf)\] **Related Toolkit**: [Doccano]
-(https://github.com/doccano/doccano)ã[MarkTool](https://github.com/FXLP/
-MarkTool)ã[LabelStudio](https://labelstud.io/ ): Data Annotation Toolkits
-[LambdaKG](https://github.com/zjunlp/PromptKG/tree/main/lambdaKG): A library
-and benchmark for PLM-based KG embeddings [EasyInstruct](https://github.com/
-zjunlp/EasyInstruct): An easy-to-use framework to instruct Large Language
-Models # Table of Contents * [What's New](#whats-new) * [Prediction Demo]
-(#prediction-demo) * [Model Framework](#model-framework) * [Quick Start]
-(#quick-start) * [Requirements](#requirements) * [Introduction of Three
-Functions](#introduction-of-three-functions) * [1. Named Entity Recognition]
-(#1-named-entity-recognition) * [2. Relation Extraction](#2-relation-
-extraction) * [3. Attribute Extraction](#3-attribute-extraction) * [Notebook
-Tutorial](#notebook-tutorial) * [Tips](#tips) * [To do](#to-do) * [Citation]
-(#citation) * [Contributors](#contributors) * [Other Knowledge Extraction Open-
-Source Projects](#other-knowledge-extraction-open-source-projects)
-# What's New ## Apr, 2023 * We have added new models, including [CP-NER](https:
-//github.com/zjunlp/DeepKE/blob/main/example/ner/cross), [ASP(EMNLP'22)](https:
-//github.com/zjunlp/DeepKE/tree/main/example/triple/ASP), [PRGC(ACL'21)](https:
-//github.com/zjunlp/DeepKE/tree/main/example/triple/PRGC), [PURE(NAACL'21)]
-(https://github.com/zjunlp/DeepKE/tree/main/example/triple/PURE), provided
-[event extraction](https://github.com/zjunlp/DeepKE/tree/main/example/ee/
-standard) capabilities (Chinese and English), and offered compatibility with
-higher versions of Python packages (e.g., Transformers). ## Feb, 2023 * We have
-supported using [LLM](https://github.com/zjunlp/DeepKE/tree/main/example/llm)
-(GPT-3) with in-context learning (based on [EasyInstruct](https://github.com/
-zjunlp/EasyInstruct)) & data generation, added a NER model [W2NER(AAAI'22)]
-(https://github.com/zjunlp/DeepKE/tree/main/example/ner/standard/w2ner). ##
-Nov, 2022 * Add data [annotation instructions](https://github.com/zjunlp/
-DeepKE/blob/main/README_TAG.md) for entity recognition and relation extraction,
-automatic labelling of weakly supervised data ([entity extraction](https://
-github.com/zjunlp/DeepKE/tree/main/example/ner/prepare-data) and [relation
-extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/prepare-
-data)), and optimize [multi-GPU training](https://github.com/zjunlp/DeepKE/
-tree/main/example/re/standard). ## Sept, 2022 * The paper [DeepKE: A Deep
-Learning Based Knowledge Extraction Toolkit for Knowledge Base Population]
-(https://arxiv.org/abs/2201.03335) has been accepted by the EMNLP 2022 System
-Demonstration Track. ## Aug, 2022 * We have added [data augmentation](https://
-github.com/zjunlp/DeepKE/tree/main/example/re/few-shot/DA) (Chinese, English)
-support for [low-resource relation extraction](https://github.com/zjunlp/
-DeepKE/tree/main/example/re/few-shot). ## June, 2022 * We have added multimodal
-support for [entity](https://github.com/zjunlp/DeepKE/tree/main/example/ner/
-multimodal) and [relation extraction](https://github.com/zjunlp/DeepKE/tree/
-main/example/re/multimodal). ## May, 2022 * We have released [DeepKE-cnschema]
-(https://github.com/zjunlp/DeepKE/blob/main/README_CNSCHEMA.md) with off-the-
-shelf knowledge extraction models. ## Jan, 2022 * We have released a paper
-[DeepKE: A Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base
-Population](https://arxiv.org/abs/2201.03335) ## Dec, 2021 * We have added
-`dockerfile` to create the enviroment automatically. ## Nov, 2021 * The demo of
-DeepKE, supporting real-time extration without deploying and training, has been
+beginners. - âWant to use Large Language Models with DeepKE? Try [DeepKE-LLM]
+(https://github.com/zjunlp/DeepKE/tree/main/example/llm) with [KnowLM](https://
+github.com/zjunlp/KnowLM), have fun! - âWant to train supervised models? Try
+[Quick Start](#quick-start), we provide the NER models (e.g, [LightNER
+(COLING'22)](https://github.com/zjunlp/DeepKE/tree/main/example/ner/few-shot),
+[W2NER(AAAI'22)](https://github.com/zjunlp/DeepKE/tree/main/example/ner/
+standard/w2ner)), relation extraction models (e.g., [KnowPrompt(WWW'22)](https:
+//github.com/zjunlp/DeepKE/tree/main/example/re/few-shot)), relational triple
+extraction models (e.g., [ASP(EMNLP'22)](https://github.com/zjunlp/DeepKE/tree/
+main/example/triple/ASP), [PRGC(ACL'21)](https://github.com/zjunlp/DeepKE/tree/
+main/example/triple/PRGC), [PURE(NAACL'21)](https://github.com/zjunlp/DeepKE/
+tree/main/example/triple/PURE)), and release off-the-shelf models at [DeepKE-
+cnSchema](https://github.com/zjunlp/DeepKE/tree/main/example/triple/cnschema),
+have fun! # Table of Contents - [Table of Contents](#table-of-contents) -
+[What's New](#whats-new) - [Prediction Demo](#prediction-demo) - [Model
+Framework](#model-framework) - [Quick Start](#quick-start) - [DeepKE-LLM]
+(#deepke-llm) - [DeepKE](#deepke) - [Requirements](#requirements) - [DeepKE-
+LLM](#deepke-llm-1) - [DeepKE](#deepke-1) - [Introduction of Three Functions]
+(#introduction-of-three-functions) - [1. Named Entity Recognition](#1-named-
+entity-recognition) - [2. Relation Extraction](#2-relation-extraction) - [3.
+Attribute Extraction](#3-attribute-extraction) - [4. Event Extraction](#4-
+event-extraction) - [Notebook Tutorial](#notebook-tutorial) - [Tips](#tips) -
+[To do](#to-do) - [Reading Materials](#reading-materials) - [Related Toolkit]
+(#related-toolkit) - [Citation](#citation) - [Contributors (Determined by the
+roll of the dice)](#contributors-determined-by-the-roll-of-the-dice) - [Other
+Knowledge Extraction Open-Source Projects](#other-knowledge-extraction-open-
+source-projects)
+# What's New * `June, 2023` We update [DeepKE-LLM](https://github.com/zjunlp/
+DeepKE/tree/main/example/llm) to support **knowledge extraction** with [KnowLM]
+(https://github.com/zjunlp/KnowLM), [ChatGLM](https://github.com/THUDM/ChatGLM-
+6B), LLaMA-series, GPT-series etc. * `Apr, 2023` We have added new models,
+including [CP-NER(IJCAI'23)](https://github.com/zjunlp/DeepKE/blob/main/
+example/ner/cross), [ASP(EMNLP'22)](https://github.com/zjunlp/DeepKE/tree/main/
+example/triple/ASP), [PRGC(ACL'21)](https://github.com/zjunlp/DeepKE/tree/main/
+example/triple/PRGC), [PURE(NAACL'21)](https://github.com/zjunlp/DeepKE/tree/
+main/example/triple/PURE), provided [event extraction](https://github.com/
+zjunlp/DeepKE/tree/main/example/ee/standard) capabilities (Chinese and
+English), and offered compatibility with higher versions of Python packages
+(e.g., Transformers). * `Feb, 2023` We have supported using [LLM](https://
+github.com/zjunlp/DeepKE/tree/main/example/llm) (GPT-3) with in-context
+learning (based on [EasyInstruct](https://github.com/zjunlp/EasyInstruct)) &
+data generation, added a NER model [W2NER(AAAI'22)](https://github.com/zjunlp/
+DeepKE/tree/main/example/ner/standard/w2ner).  Previous News * `Nov, 2022` Add
+data [annotation instructions](https://github.com/zjunlp/DeepKE/blob/main/
+README_TAG.md) for entity recognition and relation extraction, automatic
+labelling of weakly supervised data ([entity extraction](https://github.com/
+zjunlp/DeepKE/tree/main/example/ner/prepare-data) and [relation extraction]
+(https://github.com/zjunlp/DeepKE/tree/main/example/re/prepare-data)), and
+optimize [multi-GPU training](https://github.com/zjunlp/DeepKE/tree/main/
+example/re/standard). * `Sept, 2022` The paper [DeepKE: A Deep Learning Based
+Knowledge Extraction Toolkit for Knowledge Base Population](https://arxiv.org/
+abs/2201.03335) has been accepted by the EMNLP 2022 System Demonstration Track.
+* `Aug, 2022` We have added [data augmentation](https://github.com/zjunlp/
+DeepKE/tree/main/example/re/few-shot/DA) (Chinese, English) support for [low-
+resource relation extraction](https://github.com/zjunlp/DeepKE/tree/main/
+example/re/few-shot). * `June, 2022` We have added multimodal support for
+[entity](https://github.com/zjunlp/DeepKE/tree/main/example/ner/multimodal) and
+[relation extraction](https://github.com/zjunlp/DeepKE/tree/main/example/re/
+multimodal). * `May, 2022` We have released [DeepKE-cnschema](https://
+github.com/zjunlp/DeepKE/blob/main/README_CNSCHEMA.md) with off-the-shelf
+knowledge extraction models. * `Jan, 2022` We have released a paper [DeepKE: A
+Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population]
+(https://arxiv.org/abs/2201.03335) * `Dec, 2021` We have added `dockerfile` to
+create the enviroment automatically. * `Nov, 2021` The demo of DeepKE,
+supporting real-time extration without deploying and training, has been
 released. * The documentation of DeepKE, containing the details of DeepKE such
-as source codes and datasets, has been released. ## Oct, 2021 * `pip install
-deepke` * The codes of deepke-v2.0 have been released. ## Aug, 2019 * The codes
-of deepke-v1.0 have been released. ## Aug, 2018 * The project DeepKE startup
-and codes of deepke-v0.1 have been released.
-# Prediction Demo There is a demonstration of prediction. The GIF file is
-created by [Terminalizer](https://github.com/faressoft/terminalizer). Get the
-[code](https://drive.google.com/file/d/1r4tWfAkpvynH3CBSgd-XG79rf-pB-KR3/
-view?usp=share_link). [pics/demo.gif]
+as source codes and datasets, has been released. * `Oct, 2021` `pip install
+deepke` * The codes of deepke-v2.0 have been released. * `Aug, 2019` The codes
+of deepke-v1.0 have been released. * `Aug, 2018` The project DeepKE startup and
+codes of deepke-v0.1 have been released.  # Prediction Demo There is a
+demonstration of prediction. The GIF file is created by [Terminalizer](https://
+github.com/faressoft/terminalizer). Get the [code](https://drive.google.com/
+file/d/1r4tWfAkpvynH3CBSgd-XG79rf-pB-KR3/view?usp=share_link). [pics/demo.gif]
 # Model Framework
                       **** [pics/architectures.png] ****
 - DeepKE contains a unified framework for **named entity recognition**,
 **relation extraction** and **attribute extraction**, the three knowledge
 extraction functions. - Each task can be implemented in different scenarios.
 For example, we can achieve relation extraction in **standard**, **low-resource
 (few-shot)**, **document-level** and **multimodal** settings. - Each
 application scenario comprises of three components: **Data** including
 Tokenizer, Preprocessor and Loader, **Model** including Module, Encoder and
 Forwarder, **Core** including Training, Evaluation and Prediction.
-# Quick Start *DeepKE* supports `pip install deepke`.
+# Quick Start ## DeepKE-LLM In the era of large models, DeepKE-LLM utilizes a
+completely new environment dependency. ``` conda create -n deepke-llm
+python=3.9 conda activate deepke-llm cd example/llm pip install -
+r requirements.txt ``` Please note that the `requirements.txt` file is located
+in the `example/llm` folder. ## DeepKE *DeepKE* supports `pip install deepke`.
 Take the fully supervised relation extraction for example. **Step1** Download
 the basic code ```bash git clone --depth 1 https://github.com/zjunlp/DeepKE.git
 ``` **Step2** Create a virtual environment using `Anaconda` and enter it.
 - **âNOTE: We provide a [Dockerfile](https://github.com/zjunlp/DeepKE/tree/
 main/docker) with [tutorials](https://github.com/zjunlp/DeepKE/issues/145)
 please refer to the [Tips](#tips) to speed up installation** ```bash conda
 create -n deepke python=3.8 conda activate deepke ``` 1. Install *DeepKE* with
@@ -112,29 +118,31 @@
 (Parameters for training can be changed in the `conf` folder) We support visual
 parameter tuning by using *[wandb](https://docs.wandb.ai/quickstart)*. ```bash
 python run.py ``` **Step6** Prediction (Parameters for prediction can be
 changed in the `conf` folder) Modify the path of the trained model in
 `predict.yaml`.The absolute path of the model needs to be usedï¼such as `xxx/
 checkpoints/2019-12-03_ 17-35-30/cnn_ epoch21.pth`. ```bash python predict.py
 ``` - **âNOTE: if you encounter any errors, please refer to the [Tips](#tips)
-or submit a GitHub issue.** ## Requirements > python == 3.8 - torch == 1.5 -
-hydra-core == 1.0.6 - tensorboard == 2.4.1 - matplotlib == 3.4.1 - transformers
-== 3.4.0 - jieba == 0.42.1 - scikit-learn == 0.24.1 - pytorch-transformers ==
-1.2.0 - seqeval == 1.2.2 - tqdm == 4.60.0 - opt-einsum==3.3.0 - wandb==0.12.7 -
-ujson ## Introduction of Three Functions ### 1. Named Entity Recognition -
-Named entity recognition seeks to locate and classify named entities mentioned
-in unstructured text into pre-defined categories such as person names,
-organizations, locations, organizations, etc. - The data is stored in `.txt`
-files. Some instances as following (Users can label data based on the tools
-[Doccano](https://github.com/doccano/doccano), [MarkTool](https://github.com/
-FXLP/MarkTool), or they can use the [Weak Supervision](https://github.com/
-zjunlp/DeepKE/blob/main/example/ner/prepare-data) with DeepKE to obtain data
-automatically): | Sentence | Person | Location | Organization | | :------------
-----------------------------------------------: | :------------------------: |
-:------------: | :----------------------------: | |
+or submit a GitHub issue.** ## Requirements ### DeepKE-LLM > python == 3.9 -
+torch==1.13.0 - accelerate==0.17.1 - transformers==4.28.1 -
+bitsandbytes==0.37.2 - peft==0.2.0 - gradio - datasets - sentencepiece - fire
+### DeepKE > python == 3.8 - torch == 1.5 - hydra-core == 1.0.6 - tensorboard
+== 2.4.1 - matplotlib == 3.4.1 - transformers == 3.4.0 - jieba == 0.42.1 -
+scikit-learn == 0.24.1 - seqeval == 1.2.2 - tqdm == 4.60.0 - opt-einsum==3.3.0
+- wandb==0.12.7 - ujson ## Introduction of Three Functions ### 1. Named Entity
+Recognition - Named entity recognition seeks to locate and classify named
+entities mentioned in unstructured text into pre-defined categories such as
+person names, organizations, locations, organizations, etc. - The data is
+stored in `.txt` files. Some instances as following (Users can label data based
+on the tools [Doccano](https://github.com/doccano/doccano), [MarkTool](https://
+github.com/FXLP/MarkTool), or they can use the [Weak Supervision](https://
+github.com/zjunlp/DeepKE/blob/main/example/ner/prepare-data) with DeepKE to
+obtain data automatically): | Sentence | Person | Location | Organization | | :
+----------------------------------------------------------: | :----------------
+--------: | :------------: | :----------------------------: | |
 æ¬æ¥åäº¬9æ4æ¥è®¯è®°èæ¨æ¶æ¥éï¼é¨åçåºäººæ°æ¥æ¥å®£ä¼ åè¡å·¥ä½åº§è°ä¼9æ3æ¥å¨4æ¥å¨äº¬ä¸¾è¡ã
 | æ¨æ¶ | åäº¬ | äººæ°æ¥æ¥ | |
 ãçº¢æ¥¼æ¢¦ãç±çæ¶æå¯¼æ¼ï¼å¨æ±æãçèãå¨å²­ç­å¤ä½ä¸å®¶åä¸å¶ä½ã
 | çæ¶æï¼å¨æ±æï¼çèï¼å¨å²­ | | | |
 ç§¦å§çåµé©¬ä¿ä½äºéè¥¿çè¥¿å®å¸,æ¯ä¸çå«å¤§å¥è¿¹ä¹ä¸ã |
 ç§¦å§ç | éè¥¿çï¼è¥¿å®å¸ | | - Read the detailed process in specific
 README - **[STANDARD (Fully Supervised)](https://github.com/zjunlp/DeepKE/tree/
@@ -312,38 +320,66 @@
 zjunlp/DeepKE/blob/main/example/re/standard/README.md)). 5.It's recommended to
 install *DeepKE* with source codes. Because user may meet some problems in
 Windows system with 'pip',and the source code modification will not work,see
 [issue](https://github.com/zjunlp/DeepKE/issues/117) 6.More related low-
 resource knowledge extraction works can be found in [Knowledge Extraction in
 Low-Resource Scenarios: Survey and Perspective](https://arxiv.org/pdf/
 2202.08063.pdf). 7.Make sure the exact versions of requirements in
-`requirements.txt`.
-# To do In next version, we plan to release a LLM for KE. Meanwhile, we will
-offer long-term maintenance to **fix bugs**, **solve issues** and meet **new
-requests**. So if you have any problems, please put issues to us.
-# Citation Please cite our paper if you use DeepKE in your work ```bibtex
-@inproceedings{DBLP:conf/emnlp/ZhangXTYYQXCLL22, author = {Ningyu Zhang and Xin
+`requirements.txt`. # To do In next version, we plan to release a multimodal
+LLM for KE. Meanwhile, we will offer long-term maintenance to **fix bugs**,
+**solve issues** and meet **new requests**. So if you have any problems, please
+put issues to us. # Reading Materials Data-Efficient Knowledge Graph
+Construction, é«æç¥è¯å¾è°±æå»º ([Tutorial on CCKS 2022](http://
+sigkg.cn/ccks2022/?page_id=24)) \[[slides](https://drive.google.com/drive/
+folders/1xqeREw3dSiw-Y1rxLDx77r0hGUvHnuuE)\] Efficient and Robust Knowledge
+Graph Construction ([Tutorial on AACL-IJCNLP 2022](https://www.aacl2022.org/
+Program/tutorials)) \[[slides](https://github.com/NLP-Tutorials/AACL-
+IJCNLP2022-KGC-Tutorial)\] PromptKG Family: a Gallery of Prompt Learning & KG-
+related Research Works, Toolkits, and Paper-list [[Resources](https://
+github.com/zjunlp/PromptKG)\] Knowledge Extraction in Low-Resource Scenarios:
+Survey and Perspective \[[Survey](https://arxiv.org/abs/2202.08063)\]\[[Paper-
+list](https://github.com/zjunlp/Low-resource-KEPapers)\] # Related Toolkit
+[Doccano](https://github.com/doccano/doccano)ã[MarkTool](https://github.com/
+FXLP/MarkTool)ã[LabelStudio](https://labelstud.io/ ): Data Annotation
+Toolkits [LambdaKG](https://github.com/zjunlp/PromptKG/tree/main/lambdaKG): A
+library and benchmark for PLM-based KG embeddings [EasyInstruct](https://
+github.com/zjunlp/EasyInstruct): An easy-to-use framework to instruct Large
+Language Models **Reading Materials**: Data-Efficient Knowledge Graph
+Construction, é«æç¥è¯å¾è°±æå»º ([Tutorial on CCKS 2022](http://
+sigkg.cn/ccks2022/?page_id=24)) \[[slides](https://drive.google.com/drive/
+folders/1xqeREw3dSiw-Y1rxLDx77r0hGUvHnuuE)\] Efficient and Robust Knowledge
+Graph Construction ([Tutorial on AACL-IJCNLP 2022](https://www.aacl2022.org/
+Program/tutorials)) \[[slides](https://github.com/NLP-Tutorials/AACL-
+IJCNLP2022-KGC-Tutorial)\] PromptKG Family: a Gallery of Prompt Learning & KG-
+related Research Works, Toolkits, and Paper-list [[Resources](https://
+github.com/zjunlp/PromptKG)\] Knowledge Extraction in Low-Resource Scenarios:
+Survey and Perspective \[[Survey](https://arxiv.org/abs/2202.08063)\]\[[Paper-
+list](https://github.com/zjunlp/Low-resource-KEPapers)\] **Related Toolkit**:
+[Doccano](https://github.com/doccano/doccano)ã[MarkTool](https://github.com/
+FXLP/MarkTool)ã[LabelStudio](https://labelstud.io/ ): Data Annotation
+Toolkits [LambdaKG](https://github.com/zjunlp/PromptKG/tree/main/lambdaKG): A
+library and benchmark for PLM-based KG embeddings [EasyInstruct](https://
+github.com/zjunlp/EasyInstruct): An easy-to-use framework to instruct Large
+Language Models # Citation Please cite our paper if you use DeepKE in your work
+```bibtex @inproceedings{EMNLP2022_Demo_DeepKE, author = {Ningyu Zhang and Xin
 Xu and Liankuan Tao and Haiyang Yu and Hongbin Ye and Shuofei Qiao and Xin Xie
 and Xiang Chen and Zhoubo Li and Lei Li}, editor = {Wanxiang Che and Ekaterina
 Shutova}, title = {DeepKE: {A} Deep Learning Based Knowledge Extraction Toolkit
-for Knowledge Base Population}, booktitle = {Proceedings of the The 2022
-Conference on Empirical Methods in Natural Language Processing, {EMNLP} 2022 -
-System Demonstrations, Abu Dhabi, UAE, December 7-11, 2022}, pages = {98--108},
-publisher = {Association for Computational Linguistics}, year = {2022}, url =
-{https://aclanthology.org/2022.emnlp-demos.10}, timestamp = {Thu, 23 Mar 2023
-16:56:00 +0100}, biburl = {https://dblp.org/rec/conf/emnlp/
-ZhangXTYYQXCLL22.bib}, bibsource = {dblp computer science bibliography, https:/
-/dblp.org} } ```
-# Contributors Zhejiang University: [Ningyu Zhang](https://person.zju.edu.cn/
-en/ningyu), Liankuan Tao, Xin Xu, Xinrong Li, Haiyang Yu, Hongbin Ye, Shuofei
-Qiao, Peng Wang, Yuqi Zhu, Xin Xie, Xiang Chen, Zhoubo Li, Lei Li, Xiaozhuan
-Liang, Yunzhi Yao, Shumin Deng, Wen Zhang, Guozhou Zheng, Huajun Chen Community
-Contributors: [thredreams](https://github.com/thredreams), [eltociear](https://
-github.com/eltociear) Alibaba Group: Feiyu Xiong, Qiang Chen DAMO Academy:
-Zhenru Zhang, Chuanqi Tan, Fei Huang Intern: Ziwen Xu, Rui Huang, Xiaolong Weng
-# Other Knowledge Extraction Open-Source Projects - [CogIE](https://github.com/
-jinzhuoran/CogIE) - [OpenNRE](https://github.com/thunlp/OpenNRE) - [OmniEvent]
-(https://github.com/THU-KEG/OmniEvent) - [OpenUE](https://github.com/zjunlp/
-OpenUE) - [OpenIE](https://stanfordnlp.github.io/CoreNLP/openie.html) - [RESIN]
-(https://github.com/RESIN-KAIROS/RESIN-pipeline-public) - [ZShot](https://
-github.com/IBM/zshot) - [ZS4IE](https://github.com/BBN-E/ZS4IE) - [OmniEvent]
-(https://github.com/THU-KEG/OmniEvent)
+for Knowledge Base Population}, booktitle = {{EMNLP} (Demos)}, pages = {98--
+108}, publisher = {Association for Computational Linguistics}, year = {2022},
+url = {https://aclanthology.org/2022.emnlp-demos.10} } ```
+# Contributors (Determined by the roll of the dice) Zhejiang University:
+[Ningyu Zhang](https://person.zju.edu.cn/en/ningyu), Liankuan Tao, Xin Xu,
+Honghao Gui, Xiaohan Wang, Zekun Xi, Xinrong Li, Haiyang Yu, Hongbin Ye,
+Shuofei Qiao, Peng Wang, Yuqi Zhu, Xin Xie, Xiang Chen, Zhoubo Li, Lei Li,
+Xiaozhuan Liang, Yunzhi Yao, Jing Chen, Yuqi Zhu, Shumin Deng, Wen Zhang,
+Guozhou Zheng, Huajun Chen Community Contributors: [thredreams](https://
+github.com/thredreams), [eltociear](https://github.com/eltociear) Alibaba
+Group: Feiyu Xiong, Qiang Chen DAMO Academy: Zhenru Zhang, Chuanqi Tan, Fei
+Huang Intern: Ziwen Xu, Rui Huang, Xiaolong Weng # Other Knowledge Extraction
+Open-Source Projects - [CogIE](https://github.com/jinzhuoran/CogIE) - [OpenNRE]
+(https://github.com/thunlp/OpenNRE) - [OmniEvent](https://github.com/THU-KEG/
+OmniEvent) - [OpenUE](https://github.com/zjunlp/OpenUE) - [OpenIE](https://
+stanfordnlp.github.io/CoreNLP/openie.html) - [RESIN](https://github.com/RESIN-
+KAIROS/RESIN-pipeline-public) - [ZShot](https://github.com/IBM/zshot) - [ZS4IE]
+(https://github.com/BBN-E/ZS4IE) - [OmniEvent](https://github.com/THU-KEG/
+OmniEvent)
```

### Comparing `deepke-2.2/setup.py` & `deepke-2.2.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 
 with open("requirements.txt") as requirements_file:
     requirements = requirements_file.read().splitlines()
     
 setup(
     name='deepke',  # 打包后的包文件名
-    version='2.2',    #版本号
+    version='2.2.4',    #版本号
     keywords=["pip", "RE","NER","AE"],    # 关键字
     description='DeepKE is a knowledge extraction toolkit for knowledge graph construction supporting low-resource, document-level and multimodal scenarios for entity, relation and attribute extraction.',  # 说明
     license="MIT",  # 许可
     url='https://github.com/zjunlp/deepke',
     author='ZJUNLP',
     author_email='zhangningyu@zju.edu.cn',
     include_package_data=True,
```

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/models/BasicModule.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/models/BasicModule.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/models/BiLSTM.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/models/BiLSTM.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/models/Capsule.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/models/Capsule.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/models/GCN.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/models/GCN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/models/LM.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/models/LM.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/models/PCNN.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/models/PCNN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/models/Transformer.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/models/Transformer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/module/Attention.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Attention.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/module/CNN.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/module/CNN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/module/Capsule.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Capsule.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/module/Embedding.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Embedding.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/module/GCN.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/module/GCN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/module/RNN.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/module/RNN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/module/Transformer.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/module/Transformer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/tools/dataset.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/dataset.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/tools/metrics.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/metrics.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/tools/preprocess.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/preprocess.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/tools/serializer.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/serializer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/tools/trainer.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/trainer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/tools/vocab.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/tools/vocab.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/utils/ioUtils.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/utils/ioUtils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/attribution_extraction/standard/utils/nnUtils.py` & `deepke-2.2.4/src/deepke/attribution_extraction/standard/utils/nnUtils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/bertcrf/bert_crf.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/bert_crf.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/bertcrf/crf.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/crf.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/bertcrf/processor_ee.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/processor_ee.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/bertcrf/utils_ee.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/bertcrf/utils_ee.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/degree/data.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/degree/data.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/degree/model.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/degree/model.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/degree/template_generate_ace.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/degree/template_generate_ace.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/event_extraction/standard/degree/utils.py` & `deepke-2.2.4/src/deepke/event_extraction/standard/degree/utils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/constants.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/constants.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/dataset_processer.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/dataset_processer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/extraction_metrics.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/extraction_metrics.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/label_tree.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/label_tree.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/noiser/spot_asoc_noiser.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/noiser/spot_asoc_noiser.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/predict_parser/spotasoc_predict_parser.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/predict_parser/spotasoc_predict_parser.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/predict_parser/utils.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/predict_parser/utils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/record_schema.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/record_schema.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/scorer.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/scorer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/extraction/utils.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/extraction/utils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/sel2record/record.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/sel2record/record.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/sel2record/sel2record.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/sel2record/sel2record.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constrained_seq2seq.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constrained_seq2seq.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/__init__.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/__init__.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/constraint_decoder.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/constraint_decoder.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/spotasoc_constraint_decoder.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/constraint_decoder/spotasoc_constraint_decoder.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/hybird_data_collator.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/hybird_data_collator.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/meta_data_collator.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/meta_data_collator.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/data_collator/t5mlm_data_collator.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/data_collator/t5mlm_data_collator.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/features.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/features.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/modeling_t5.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/modeling_t5.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/models.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/models.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/t5_bert_tokenizer.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/t5_bert_tokenizer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/cross/seq2seq/trainer_arguments.py` & `deepke-2.2.4/src/deepke/name_entity_re/cross/seq2seq/trainer_arguments.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/few_shot/models/model.py` & `deepke-2.2.4/src/deepke/name_entity_re/few_shot/models/model.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 import torch
 from torch import nn
 from torch.nn import functional as F
 from transformers.models.bart.configuration_bart import BartConfig
 from .modeling_bart import BartModel
 
-from .util import avg_token_embeddings, seq_to_mask, get_model_device
+from ..utils.util import avg_token_embeddings, seq_to_mask, get_model_device
 from functools import partial
 from typing import Union
 
 
 class PromptBartEncoder(nn.Module):
     def __init__(self, encoder):
         super(PromptBartEncoder, self).__init__()
```

### Comparing `deepke-2.2/src/deepke/name_entity_re/few_shot/models/modeling_bart.py` & `deepke-2.2.4/src/deepke/name_entity_re/few_shot/models/modeling_bart.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/few_shot/module/datasets.py` & `deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/datasets.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/few_shot/module/mapping_type.py` & `deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/mapping_type.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/few_shot/module/metrics.py` & `deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/metrics.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/few_shot/module/train.py` & `deepke-2.2.4/src/deepke/name_entity_re/few_shot/module/train.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/few_shot/utils/util.py` & `deepke-2.2.4/src/deepke/name_entity_re/few_shot/utils/util.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/multimodal/models/IFA_model.py` & `deepke-2.2.4/src/deepke/name_entity_re/multimodal/models/IFA_model.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/multimodal/models/modeling_IFA.py` & `deepke-2.2.4/src/deepke/name_entity_re/multimodal/models/modeling_IFA.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/multimodal/modules/dataset.py` & `deepke-2.2.4/src/deepke/name_entity_re/multimodal/modules/dataset.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/multimodal/modules/train.py` & `deepke-2.2.4/src/deepke/name_entity_re/multimodal/modules/train.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/standard/models/BiLSTM_CRF.py` & `deepke-2.2.4/src/deepke/name_entity_re/standard/models/BiLSTM_CRF.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/standard/models/InferBert.py` & `deepke-2.2.4/src/deepke/name_entity_re/standard/models/InferBert.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,15 +18,15 @@
     def forward(
         self, 
         input_ids, 
         token_type_ids=None, 
         attention_mask=None, 
         valid_ids=None
     ):
-        sequence_output = self.bert(input_ids, token_type_ids, attention_mask, head_mask=None)[0]
+        sequence_output = self.bert(input_ids=input_ids, token_type_ids=token_type_ids, attention_mask=attention_mask, head_mask=None)[0]
         batch_size,max_len,feat_dim = sequence_output.shape
         valid_output = torch.zeros(batch_size,max_len,feat_dim,dtype=torch.float32,device='cuda' if torch.cuda.is_available() else 'cpu')
         for i in range(batch_size):
             jj = -1
             for j in range(max_len):
                     if valid_ids[i][j].item() == 1:
                         jj += 1
@@ -128,15 +128,15 @@
         elif self.cfg.model_name == 'bert':
             input_ids,input_mask,segment_ids,valid_ids = self.preprocess(text)
             input_ids = torch.tensor([input_ids],dtype=torch.long,device=self.device)
             input_mask = torch.tensor([input_mask],dtype=torch.long,device=self.device)
             segment_ids = torch.tensor([segment_ids],dtype=torch.long,device=self.device)
             valid_ids = torch.tensor([valid_ids],dtype=torch.long,device=self.device)
             with torch.no_grad():
-                logits = self.model(input_ids, segment_ids, input_mask,valid_ids)
+                logits = self.model(input_ids=input_ids, token_type_ids=segment_ids, attention_mask=input_mask, valid_ids=valid_ids)
             logits = F.softmax(logits,dim=2)
             logits_label = torch.argmax(logits,dim=2)
             logits_label = logits_label.detach().cpu().numpy().tolist()[0]
 
             logits_confidence = [values[label].item() for values,label in zip(logits[0],logits_label)]
 
             logits = []
```

### Comparing `deepke-2.2/src/deepke/name_entity_re/standard/tools/dataset.py` & `deepke-2.2.4/src/deepke/name_entity_re/standard/tools/dataset.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/standard/tools/preprocess.py` & `deepke-2.2.4/src/deepke/name_entity_re/standard/tools/preprocess.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/standard/w2ner/data_loader.py` & `deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/data_loader.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/standard/w2ner/model.py` & `deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/model.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/name_entity_re/standard/w2ner/utils.py` & `deepke-2.2.4/src/deepke/name_entity_re/standard/w2ner/utils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/document/evaluation.py` & `deepke-2.2.4/src/deepke/relation_extraction/document/evaluation.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/document/losses.py` & `deepke-2.2.4/src/deepke/relation_extraction/document/losses.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/document/model.py` & `deepke-2.2.4/src/deepke/relation_extraction/document/model.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/document/module.py` & `deepke-2.2.4/src/deepke/relation_extraction/document/module.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/document/prepro.py` & `deepke-2.2.4/src/deepke/relation_extraction/document/prepro.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/document/utils.py` & `deepke-2.2.4/src/deepke/relation_extraction/document/utils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/base_data_module.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/base_data_module.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/dialogue.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/dialogue.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/dataset/processor.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/dataset/processor.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/generate_k_shot.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/generate_k_shot.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/get_label_word.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/get_label_word.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/base.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/base.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/transformer.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/transformer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/few_shot/lit_models/util.py` & `deepke-2.2.4/src/deepke/relation_extraction/few_shot/lit_models/util.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/multimodal/models/IFA_model.py` & `deepke-2.2.4/src/deepke/relation_extraction/multimodal/models/IFA_model.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/multimodal/models/modeling_IFA.py` & `deepke-2.2.4/src/deepke/relation_extraction/multimodal/models/modeling_IFA.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/multimodal/modules/dataset.py` & `deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/dataset.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/multimodal/modules/metrics.py` & `deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/metrics.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/multimodal/modules/train.py` & `deepke-2.2.4/src/deepke/relation_extraction/multimodal/modules/train.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/models/BasicModule.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/models/BasicModule.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/models/BiLSTM.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/models/BiLSTM.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/models/Capsule.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/models/Capsule.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/models/GCN.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/models/GCN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/models/LM.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/models/LM.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/models/PCNN.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/models/PCNN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/models/Transformer.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/models/Transformer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/module/Attention.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/module/Attention.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/module/CNN.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/module/CNN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/module/Capsule.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/module/Capsule.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/module/Embedding.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/module/Embedding.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/module/GCN.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/module/GCN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/module/RNN.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/module/RNN.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/module/Transformer.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/module/Transformer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/tools/dataset.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/tools/dataset.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/tools/loss.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/tools/loss.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/tools/metrics.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/tools/metrics.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/tools/preprocess.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/tools/preprocess.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/tools/serializer.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/tools/serializer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/tools/trainer.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/tools/trainer.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/tools/vocab.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/tools/vocab.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/utils/ioUtils.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/utils/ioUtils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/relation_extraction/standard/utils/nnUtils.py` & `deepke-2.2.4/src/deepke/relation_extraction/standard/utils/nnUtils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/transform_data.py` & `deepke-2.2.4/src/deepke/transform_data.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/metrics/blanc.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/blanc.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/metrics/conll.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/conll.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/metrics/metrics.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/metrics/metrics.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/modeling_transformer/modeling_outputs.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/modeling_transformer/modeling_outputs.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/models/model_coref.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/models/model_coref.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/models/model_ere.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/models/model_ere.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/models/model_ner.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/models/model_ner.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/models/modeling_outputs.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/models/modeling_outputs.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/models/t5_coref.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/models/t5_coref.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/models/t5_ere.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/models/t5_ere.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/models/t5_ner.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/models/t5_ner.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/util/func.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/util/func.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/util/multigpu_fused_adam.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/util/multigpu_fused_adam.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/util/runner.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/util/runner.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/util/tensorize_coref.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/util/tensorize_coref.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/util/tensorize_ere.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/util/tensorize_ere.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/ASP/util/tensorize_ner.py` & `deepke-2.2.4/src/deepke/triple_extraction/ASP/util/tensorize_ner.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/PRGC/dataloader.py` & `deepke-2.2.4/src/deepke/triple_extraction/PRGC/dataloader.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/PRGC/dataloader_utils.py` & `deepke-2.2.4/src/deepke/triple_extraction/PRGC/dataloader_utils.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/PRGC/evaluate.py` & `deepke-2.2.4/src/deepke/triple_extraction/PRGC/evaluate.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/PRGC/metrics.py` & `deepke-2.2.4/src/deepke/triple_extraction/PRGC/metrics.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/PRGC/model.py` & `deepke-2.2.4/src/deepke/triple_extraction/PRGC/model.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/PRGC/optimization.py` & `deepke-2.2.4/src/deepke/triple_extraction/PRGC/optimization.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke/triple_extraction/PRGC/util.py` & `deepke-2.2.4/src/deepke/triple_extraction/PRGC/util.py`

 * *Files identical despite different names*

### Comparing `deepke-2.2/src/deepke.egg-info/SOURCES.txt` & `deepke-2.2.4/src/deepke.egg-info/SOURCES.txt`

 * *Files identical despite different names*

