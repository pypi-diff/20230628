# Comparing `tmp/EasyDeL-0.0.4.tar.gz` & `tmp/EasyDeL-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "EasyDeL-0.0.4.tar", last modified: Tue Jun 27 07:33:58 2023, max compression
+gzip compressed data, was "EasyDeL-0.0.5.tar", last modified: Wed Jun 28 07:19:52 2023, max compression
```

## Comparing `EasyDeL-0.0.4.tar` & `EasyDeL-0.0.5.tar`

### file list

```diff
@@ -1,53 +1,53 @@
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDeL.egg-info/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-27 07:33:57.000000 EasyDeL-0.0.4/EasyDeL.egg-info/PKG-INFO
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1201 2023-06-27 07:33:57.000000 EasyDeL-0.0.4/EasyDeL.egg-info/SOURCES.txt
--rw-rw-r--   0 erfan     (1000) erfan     (1000)        1 2023-06-27 07:33:57.000000 EasyDeL-0.0.4/EasyDeL.egg-info/dependency_links.txt
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       14 2023-06-27 07:33:57.000000 EasyDeL-0.0.4/EasyDeL.egg-info/requires.txt
--rw-rw-r--   0 erfan     (1000) erfan     (1000)        8 2023-06-27 07:33:57.000000 EasyDeL-0.0.4/EasyDeL.egg-info/top_level.txt
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1502 2023-06-27 07:17:54.000000 EasyDeL-0.0.4/EasyDel/__init__.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/modules/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1041 2023-06-24 06:51:39.000000 EasyDeL-0.0.4/EasyDel/modules/__init__.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/modules/falcon/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       88 2023-06-15 10:29:08.000000 EasyDeL-0.0.4/EasyDel/modules/falcon/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    18490 2023-06-24 06:51:39.000000 EasyDeL-0.0.4/EasyDel/modules/falcon/modelling_falcon_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/modules/gpt_j/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      130 2023-06-13 13:41:25.000000 EasyDeL-0.0.4/EasyDel/modules/gpt_j/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    31319 2023-06-13 13:41:25.000000 EasyDeL-0.0.4/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/modules/gpt_neo_x/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       94 2023-06-24 06:51:39.000000 EasyDeL-0.0.4/EasyDel/modules/gpt_neo_x/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    16080 2023-06-24 06:51:39.000000 EasyDeL-0.0.4/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/modules/llama/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      150 2023-06-15 07:43:43.000000 EasyDeL-0.0.4/EasyDel/modules/llama/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    34039 2023-06-24 06:51:39.000000 EasyDeL-0.0.4/EasyDel/modules/llama/modelling_llama_flax.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    17266 2023-06-26 09:30:53.000000 EasyDeL-0.0.4/EasyDel/modules/llama/modelling_llama_pytorch.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/modules/lucid_transformer/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       95 2023-06-12 11:40:22.000000 EasyDeL-0.0.4/EasyDel/modules/lucid_transformer/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    13528 2023-06-12 11:39:20.000000 EasyDeL-0.0.4/EasyDel/modules/lucid_transformer/modelling_lt_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/modules/mosaic_mpt/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       76 2023-06-15 07:43:43.000000 EasyDeL-0.0.4/EasyDel/modules/mosaic_mpt/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    17799 2023-06-25 09:09:59.000000 EasyDeL-0.0.4/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/serve/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-17 08:13:44.000000 EasyDeL-0.0.4/EasyDel/serve/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1482 2023-06-17 08:09:33.000000 EasyDeL-0.0.4/EasyDel/serve/serve_utils.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/trainer/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      146 2023-06-27 07:17:54.000000 EasyDeL-0.0.4/EasyDel/trainer/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     8996 2023-06-26 10:53:42.000000 EasyDeL-0.0.4/EasyDel/trainer/config.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    20765 2023-06-27 07:33:07.000000 EasyDeL-0.0.4/EasyDel/trainer/fsdp_train.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/utils/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      402 2023-06-11 11:51:31.000000 EasyDeL-0.0.4/EasyDel/utils/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      389 2023-06-11 11:51:31.000000 EasyDeL-0.0.4/EasyDel/utils/checker.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     4584 2023-06-26 09:09:30.000000 EasyDeL-0.0.4/EasyDel/utils/utils.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/EasyDel/weight_convertor/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)        0 2023-06-17 06:47:56.000000 EasyDeL-0.0.4/EasyDel/weight_convertor/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     6215 2023-06-18 09:17:09.000000 EasyDeL-0.0.4/EasyDel/weight_convertor/falcon.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     5077 2023-06-24 06:51:39.000000 EasyDeL-0.0.4/EasyDel/weight_convertor/llama.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     9833 2023-06-17 12:12:31.000000 EasyDeL-0.0.4/EasyDel/weight_convertor/mpt.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      858 2023-06-17 10:41:48.000000 EasyDeL-0.0.4/EasyDel/weight_convertor/utils.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    11357 2023-06-11 11:51:31.000000 EasyDeL-0.0.4/LICENSE
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/PKG-INFO
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     5386 2023-06-27 07:17:54.000000 EasyDeL-0.0.4/README.md
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      608 2023-06-24 06:51:39.000000 EasyDeL-0.0.4/pyproject.toml
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-27 07:33:57.994799 EasyDeL-0.0.4/setup.cfg
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1124 2023-06-27 07:33:36.000000 EasyDeL-0.0.4/setup.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDeL.egg-info/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/PKG-INFO
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1201 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/SOURCES.txt
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)        1 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/dependency_links.txt
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       14 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/requires.txt
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)        8 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/top_level.txt
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1502 2023-06-27 07:17:54.000000 EasyDeL-0.0.5/EasyDel/__init__.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1041 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/__init__.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/falcon/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       88 2023-06-15 10:29:08.000000 EasyDeL-0.0.5/EasyDel/modules/falcon/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    18490 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/falcon/modelling_falcon_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/gpt_j/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      130 2023-06-13 13:41:25.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_j/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    31319 2023-06-13 13:41:25.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       94 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    16080 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/llama/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      150 2023-06-15 07:43:43.000000 EasyDeL-0.0.5/EasyDel/modules/llama/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    34041 2023-06-27 08:27:15.000000 EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_flax.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    17266 2023-06-26 09:30:53.000000 EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_pytorch.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       95 2023-06-12 11:40:22.000000 EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    13472 2023-06-28 07:13:59.000000 EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/modelling_lt_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       76 2023-06-15 07:43:43.000000 EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    17799 2023-06-25 09:09:59.000000 EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/serve/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-17 08:13:44.000000 EasyDeL-0.0.5/EasyDel/serve/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1482 2023-06-17 08:09:33.000000 EasyDeL-0.0.5/EasyDel/serve/serve_utils.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/trainer/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      146 2023-06-27 07:17:54.000000 EasyDeL-0.0.5/EasyDel/trainer/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     8996 2023-06-26 10:53:42.000000 EasyDeL-0.0.5/EasyDel/trainer/config.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    21159 2023-06-28 07:13:59.000000 EasyDeL-0.0.5/EasyDel/trainer/fsdp_train.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/utils/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      402 2023-06-11 11:51:31.000000 EasyDeL-0.0.5/EasyDel/utils/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      389 2023-06-11 11:51:31.000000 EasyDeL-0.0.5/EasyDel/utils/checker.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     4584 2023-06-26 09:09:30.000000 EasyDeL-0.0.5/EasyDel/utils/utils.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/weight_convertor/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)        0 2023-06-17 06:47:56.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     6215 2023-06-18 09:17:09.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/falcon.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     5077 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/llama.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     9833 2023-06-17 12:12:31.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/mpt.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      858 2023-06-17 10:41:48.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/utils.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    11357 2023-06-11 11:51:31.000000 EasyDeL-0.0.5/LICENSE
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/PKG-INFO
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     5386 2023-06-28 07:19:22.000000 EasyDeL-0.0.5/README.md
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      608 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/pyproject.toml
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/setup.cfg
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1124 2023-06-28 07:14:57.000000 EasyDeL-0.0.5/setup.py
```

### Comparing `EasyDeL-0.0.4/EasyDeL.egg-info/PKG-INFO` & `EasyDeL-0.0.5/EasyDeL.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: EasyDeL
-Version: 0.0.4
+Version: 0.0.5
 Summary: An open-source library to make training faster and more optimized in Jax/Flax
 Home-page: https://github.com/erfanzar/EasyDeL
 Author: Erfan Zare Chavoshi
 Author-email: erfanzare82@eyahoo.com
 License: UNKNOWN
 Keywords: machine learning,deep learning,pytorch
 Platform: UNKNOWN
@@ -26,15 +26,15 @@
 EasyDeL (Easy Deep Learning) is an open-source library designed to accelerate and optimize the training process of
 machine learning models. This library is primarily focused on Jax/Flax and plans to offer easy and fine solutions to
 train Flax/Jax Models on the `TPU/GPU`
 
 ## Installation
 
 To install EasyDeL, you can use pip:
-### Not on PyPi yet!
+### Availalbe on PyPi
 ```bash
 pip install easydel
 ```
 
 ## Available Models Are
 
 - Llama     (Support `FSDP`, `MP`,` DP`)
@@ -44,22 +44,22 @@
 - GPTNeoX   (TODO `FSDP`, `MP`, `DP`)
 - Falcon    (Support `FSDP`, `MP`, `DP`)
 
 you can also tell me the model you want in Flax/Jax version and ill try my best to build it ;)
 
 ## FineTuning
 
-with using EasyDel FineTuning LLM (CausalLanguageModels) are easy as much as possible with using jax and flax
+with using EasyDel FineTuning LLM (CausalLanguageModels) are easy as much as possible with using Jax and Flax
 and having the benefit of TPUs for the best speed here's a simple code to use in order to finetune your own MPT / LLama 
 or any other models supported by EasyDel
 
 #### Step One
 
-download converted model weights in order to finetune or convert the weights of the model you want with using 
-weight_convertor in library example
+download converted model weights in order to finetune or convert the weights of the model you want to use
+weight_convertor in the library example
 
 ```python
 import jax
 from EasyDel.weight_convertor.mpt import convert_pt_to_flax_7b
 from fjutils.utils import save_ckpt
 
 number_of_layers = 32  # its 32 hidden layers for Mpt 7B
```

### Comparing `EasyDeL-0.0.4/EasyDeL.egg-info/SOURCES.txt` & `EasyDeL-0.0.5/EasyDeL.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/__init__.py` & `EasyDeL-0.0.5/EasyDel/__init__.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/modules/__init__.py` & `EasyDeL-0.0.5/EasyDel/modules/__init__.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/modules/falcon/modelling_falcon_flax.py` & `EasyDeL-0.0.5/EasyDel/modules/falcon/modelling_falcon_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py` & `EasyDeL-0.0.5/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py` & `EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/modules/llama/modelling_llama_flax.py` & `EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_flax.py`

 * *Files 1% similar despite different names*

```diff
@@ -106,15 +106,15 @@
             bos_token_id=bos_token_id,
             eos_token_id=eos_token_id,
             tie_word_embeddings=tie_word_embeddings,
             **kwargs,
         )
 
     @staticmethod
-    def get_partition_rules(fully_fsd: bool = True):
+    def get_partition_rules(fully_fsdp: bool = True):
         return (
 
             ("transformer/wte/embedding", PS("mp", "fsdp")),
 
             ("attention/(wq|wk|wv)/kernel", PS("fsdp", "mp")),
             ("attention/wo/kernel", PS("mp", "fsdp")),
 
@@ -124,15 +124,15 @@
 
             ("attention_norm/kernel", PS(None)),
             ("ffn_norm/kernel", PS(None)),
 
             ("transformer/ln_f/kernel", PS(None)),
             ("lm_head/kernel", PS("fsdp", "mp")),
             ('.*', PS(None)),
-        ) if not fully_fsd else (
+        ) if not fully_fsdp else (
 
             ("transformer/wte/embedding", PS("fsdp")),
 
             ("attention/(wq|wk|wv)/kernel", PS("fsdp")),
             ("attention/wo/kernel", PS("fsdp")),
 
             ("feed_forward/w1/kernel", PS("fsdp")),
```

### Comparing `EasyDeL-0.0.4/EasyDel/modules/llama/modelling_llama_pytorch.py` & `EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_pytorch.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/modules/lucid_transformer/modelling_lt_flax.py` & `EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/modelling_lt_flax.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 import math
 
 import jax.nn.initializers
 from jax import numpy as jnp
-from jax.random import PRNGKey, split
+
 from functools import partial
-from jax import jit
+
 from jax.experimental.pjit import with_sharding_constraint as _wish_sharding_constraint
 from jax.interpreters import pxla
 from flax import linen as nn
 from transformers import FlaxPreTrainedModel, PretrainedConfig
 from jax.sharding import PartitionSpec
 import flax
 from einops import rearrange
```

### Comparing `EasyDeL-0.0.4/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py` & `EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/serve/serve_utils.py` & `EasyDeL-0.0.5/EasyDel/serve/serve_utils.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/trainer/config.py` & `EasyDeL-0.0.5/EasyDel/trainer/config.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/trainer/fsdp_train.py` & `EasyDeL-0.0.5/EasyDel/trainer/fsdp_train.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,13 @@
 import dataclasses
 import os
 import typing
 
+import wandb
+
 from EasyDel.trainer.config import TrainArguments
 
 import jax
 import flax
 import optax
 from transformers import FlaxAutoModelForCausalLM, AutoConfig
 from IPython.display import clear_output
@@ -86,15 +88,17 @@
         use_wandb: bool = True,
         custom_rule=None,
         extra_configs=None,
         ids_to_pop_from_dataset=[],
         remove_ckpt_after_load: bool = False,
         model_class=None,
         configs_to_init_model_class=None,
-        do_last_save: bool = True
+        do_last_save: bool = True,
+        model_parameters=None,
+        do_shard_fns=True
 ) -> OutputFineTuner:
     if extra_configs is None:
         extra_configs = {}
     timer = Timers(
         use_wandb=False,
         tensorboard_writer=training_arguments.get_board()
     )
@@ -202,17 +206,22 @@
     ).stop()
     timer.log(['creating functions'])
     with mesh:
         timer(
             'loading parameters'
         ).start()
         shard_fns, gather_fns = make_shard_and_gather_fns(train_state_partition_spec, dtype_specs=dtype)
-        _, params = StreamingCheckpointer.load_trainstate_checkpoint(
-            f'params::{ckpt_path}', train_state_shape, shard_fns
-        )
+        if model_parameters is None:
+            _, params = StreamingCheckpointer.load_trainstate_checkpoint(
+                f'params::{ckpt_path}', train_state_shape, shard_fns
+            )
+        else:
+            params = model_parameters if not do_shard_fns else jax.tree_util.tree_map(lambda f, x: f(x), shard_fns,
+                                                                                      model_parameters)
+
         if remove_ckpt_after_load:
             os.remove(ckpt_path)
 
         sharded_train_state_ = sharded_create_from_params_fn(params)
         timer(
             'loading parameters'
         ).stop()
@@ -282,14 +291,15 @@
         predict_fun=sharded_predict,
         train_state=sharded_train_state_,
         mesh=mesh,
         shard_fns=shard_fns,
         gather_fns=gather_fns,
         ckpt_stream=ckpt_streamer
     )
+    wandb.finish()
     return output
 
 
 def pre_trainer_or_base_trainer(
         dataset_train,
         training_arguments: TrainArguments,
         use_pjit_attention_force: bool = True,
@@ -496,8 +506,9 @@
         predict_fun=sharded_predict,
         train_state=sharded_train_state_,
         mesh=mesh,
         shard_fns=shard_fns,
         gather_fns=gather_fns,
         ckpt_stream=ckpt_streamer
     )
+    wandb.finish()
     return output
```

### Comparing `EasyDeL-0.0.4/EasyDel/utils/utils.py` & `EasyDeL-0.0.5/EasyDel/utils/utils.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/weight_convertor/falcon.py` & `EasyDeL-0.0.5/EasyDel/weight_convertor/falcon.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/weight_convertor/llama.py` & `EasyDeL-0.0.5/EasyDel/weight_convertor/llama.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/weight_convertor/mpt.py` & `EasyDeL-0.0.5/EasyDel/weight_convertor/mpt.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/EasyDel/weight_convertor/utils.py` & `EasyDeL-0.0.5/EasyDel/weight_convertor/utils.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/LICENSE` & `EasyDeL-0.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/PKG-INFO` & `EasyDeL-0.0.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: EasyDeL
-Version: 0.0.4
+Version: 0.0.5
 Summary: An open-source library to make training faster and more optimized in Jax/Flax
 Home-page: https://github.com/erfanzar/EasyDeL
 Author: Erfan Zare Chavoshi
 Author-email: erfanzare82@eyahoo.com
 License: UNKNOWN
 Keywords: machine learning,deep learning,pytorch
 Platform: UNKNOWN
@@ -26,15 +26,15 @@
 EasyDeL (Easy Deep Learning) is an open-source library designed to accelerate and optimize the training process of
 machine learning models. This library is primarily focused on Jax/Flax and plans to offer easy and fine solutions to
 train Flax/Jax Models on the `TPU/GPU`
 
 ## Installation
 
 To install EasyDeL, you can use pip:
-### Not on PyPi yet!
+### Availalbe on PyPi
 ```bash
 pip install easydel
 ```
 
 ## Available Models Are
 
 - Llama     (Support `FSDP`, `MP`,` DP`)
@@ -44,22 +44,22 @@
 - GPTNeoX   (TODO `FSDP`, `MP`, `DP`)
 - Falcon    (Support `FSDP`, `MP`, `DP`)
 
 you can also tell me the model you want in Flax/Jax version and ill try my best to build it ;)
 
 ## FineTuning
 
-with using EasyDel FineTuning LLM (CausalLanguageModels) are easy as much as possible with using jax and flax
+with using EasyDel FineTuning LLM (CausalLanguageModels) are easy as much as possible with using Jax and Flax
 and having the benefit of TPUs for the best speed here's a simple code to use in order to finetune your own MPT / LLama 
 or any other models supported by EasyDel
 
 #### Step One
 
-download converted model weights in order to finetune or convert the weights of the model you want with using 
-weight_convertor in library example
+download converted model weights in order to finetune or convert the weights of the model you want to use
+weight_convertor in the library example
 
 ```python
 import jax
 from EasyDel.weight_convertor.mpt import convert_pt_to_flax_7b
 from fjutils.utils import save_ckpt
 
 number_of_layers = 32  # its 32 hidden layers for Mpt 7B
```

### Comparing `EasyDeL-0.0.4/README.md` & `EasyDeL-0.0.5/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 EasyDeL (Easy Deep Learning) is an open-source library designed to accelerate and optimize the training process of
 machine learning models. This library is primarily focused on Jax/Flax and plans to offer easy and fine solutions to
 train Flax/Jax Models on the `TPU/GPU`
 
 ## Installation
 
 To install EasyDeL, you can use pip:
-### Not on PyPi yet!
+### Availalbe on PyPi
 ```bash
 pip install easydel
 ```
 
 ## Available Models Are
 
 - Llama     (Support `FSDP`, `MP`,` DP`)
@@ -21,22 +21,22 @@
 - GPTNeoX   (TODO `FSDP`, `MP`, `DP`)
 - Falcon    (Support `FSDP`, `MP`, `DP`)
 
 you can also tell me the model you want in Flax/Jax version and ill try my best to build it ;)
 
 ## FineTuning
 
-with using EasyDel FineTuning LLM (CausalLanguageModels) are easy as much as possible with using jax and flax
+with using EasyDel FineTuning LLM (CausalLanguageModels) are easy as much as possible with using Jax and Flax
 and having the benefit of TPUs for the best speed here's a simple code to use in order to finetune your own MPT / LLama 
 or any other models supported by EasyDel
 
 #### Step One
 
-download converted model weights in order to finetune or convert the weights of the model you want with using 
-weight_convertor in library example
+download converted model weights in order to finetune or convert the weights of the model you want to use
+weight_convertor in the library example
 
 ```python
 import jax
 from EasyDel.weight_convertor.mpt import convert_pt_to_flax_7b
 from fjutils.utils import save_ckpt
 
 number_of_layers = 32  # its 32 hidden layers for Mpt 7B
```

### Comparing `EasyDeL-0.0.4/pyproject.toml` & `EasyDeL-0.0.5/pyproject.toml`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.4/setup.py` & `EasyDeL-0.0.5/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name='EasyDeL',
-    version='0.0.4',
+    version='0.0.5',
     author='Erfan Zare Chavoshi',
     author_email='erfanzare82@eyahoo.com',
     description='An open-source library to make training faster and more optimized in Jax/Flax',
     url='https://github.com/erfanzar/EasyDeL',
     packages=find_packages(),
     long_description=open('README.md').read(),
     long_description_content_type='text/markdown',
```

