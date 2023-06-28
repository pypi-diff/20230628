# Comparing `tmp/EasyDeL-0.0.5.tar.gz` & `tmp/EasyDeL-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "EasyDeL-0.0.5.tar", last modified: Wed Jun 28 07:19:52 2023, max compression
+gzip compressed data, was "EasyDeL-0.0.6.tar", last modified: Wed Jun 28 13:19:05 2023, max compression
```

## Comparing `EasyDeL-0.0.5.tar` & `EasyDeL-0.0.6.tar`

### file list

```diff
@@ -1,53 +1,56 @@
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDeL.egg-info/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/PKG-INFO
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1201 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/SOURCES.txt
--rw-rw-r--   0 erfan     (1000) erfan     (1000)        1 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/dependency_links.txt
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       14 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/requires.txt
--rw-rw-r--   0 erfan     (1000) erfan     (1000)        8 2023-06-28 07:19:52.000000 EasyDeL-0.0.5/EasyDeL.egg-info/top_level.txt
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1502 2023-06-27 07:17:54.000000 EasyDeL-0.0.5/EasyDel/__init__.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1041 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/__init__.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/falcon/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       88 2023-06-15 10:29:08.000000 EasyDeL-0.0.5/EasyDel/modules/falcon/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    18490 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/falcon/modelling_falcon_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/gpt_j/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      130 2023-06-13 13:41:25.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_j/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    31319 2023-06-13 13:41:25.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       94 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    16080 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.986153 EasyDeL-0.0.5/EasyDel/modules/llama/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      150 2023-06-15 07:43:43.000000 EasyDeL-0.0.5/EasyDel/modules/llama/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    34041 2023-06-27 08:27:15.000000 EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_flax.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    17266 2023-06-26 09:30:53.000000 EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_pytorch.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       95 2023-06-12 11:40:22.000000 EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    13472 2023-06-28 07:13:59.000000 EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/modelling_lt_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       76 2023-06-15 07:43:43.000000 EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    17799 2023-06-25 09:09:59.000000 EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/serve/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-17 08:13:44.000000 EasyDeL-0.0.5/EasyDel/serve/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1482 2023-06-17 08:09:33.000000 EasyDeL-0.0.5/EasyDel/serve/serve_utils.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/trainer/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      146 2023-06-27 07:17:54.000000 EasyDeL-0.0.5/EasyDel/trainer/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     8996 2023-06-26 10:53:42.000000 EasyDeL-0.0.5/EasyDel/trainer/config.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    21159 2023-06-28 07:13:59.000000 EasyDeL-0.0.5/EasyDel/trainer/fsdp_train.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/utils/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      402 2023-06-11 11:51:31.000000 EasyDeL-0.0.5/EasyDel/utils/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      389 2023-06-11 11:51:31.000000 EasyDeL-0.0.5/EasyDel/utils/checker.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     4584 2023-06-26 09:09:30.000000 EasyDeL-0.0.5/EasyDel/utils/utils.py
-drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/EasyDel/weight_convertor/
--rw-rw-r--   0 erfan     (1000) erfan     (1000)        0 2023-06-17 06:47:56.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/__init__.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     6215 2023-06-18 09:17:09.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/falcon.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     5077 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/llama.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     9833 2023-06-17 12:12:31.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/mpt.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      858 2023-06-17 10:41:48.000000 EasyDeL-0.0.5/EasyDel/weight_convertor/utils.py
--rw-rw-r--   0 erfan     (1000) erfan     (1000)    11357 2023-06-11 11:51:31.000000 EasyDeL-0.0.5/LICENSE
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/PKG-INFO
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     5386 2023-06-28 07:19:22.000000 EasyDeL-0.0.5/README.md
--rw-rw-r--   0 erfan     (1000) erfan     (1000)      608 2023-06-24 06:51:39.000000 EasyDeL-0.0.5/pyproject.toml
--rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-28 07:19:52.990153 EasyDeL-0.0.5/setup.cfg
--rw-rw-r--   0 erfan     (1000) erfan     (1000)     1124 2023-06-28 07:14:57.000000 EasyDeL-0.0.5/setup.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDeL.egg-info/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-28 13:19:05.000000 EasyDeL-0.0.6/EasyDeL.egg-info/PKG-INFO
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1256 2023-06-28 13:19:05.000000 EasyDeL-0.0.6/EasyDeL.egg-info/SOURCES.txt
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)        1 2023-06-28 13:19:05.000000 EasyDeL-0.0.6/EasyDeL.egg-info/dependency_links.txt
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       14 2023-06-28 13:19:05.000000 EasyDeL-0.0.6/EasyDeL.egg-info/requires.txt
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)        8 2023-06-28 13:19:05.000000 EasyDeL-0.0.6/EasyDeL.egg-info/top_level.txt
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1502 2023-06-27 07:17:54.000000 EasyDeL-0.0.6/EasyDel/__init__.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/configs/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       78 2023-06-28 13:18:01.000000 EasyDeL-0.0.6/EasyDel/configs/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     5646 2023-06-28 13:11:11.000000 EasyDeL-0.0.6/EasyDel/configs/configs.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/modules/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1041 2023-06-24 06:51:39.000000 EasyDeL-0.0.6/EasyDel/modules/__init__.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/modules/falcon/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       88 2023-06-15 10:29:08.000000 EasyDeL-0.0.6/EasyDel/modules/falcon/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    19533 2023-06-28 07:51:37.000000 EasyDeL-0.0.6/EasyDel/modules/falcon/modelling_falcon_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/modules/gpt_j/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      130 2023-06-13 13:41:25.000000 EasyDeL-0.0.6/EasyDel/modules/gpt_j/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    31319 2023-06-13 13:41:25.000000 EasyDeL-0.0.6/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/modules/gpt_neo_x/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       94 2023-06-24 06:51:39.000000 EasyDeL-0.0.6/EasyDel/modules/gpt_neo_x/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    16080 2023-06-24 06:51:39.000000 EasyDeL-0.0.6/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/modules/llama/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      150 2023-06-15 07:43:43.000000 EasyDeL-0.0.6/EasyDel/modules/llama/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    34041 2023-06-27 08:27:15.000000 EasyDeL-0.0.6/EasyDel/modules/llama/modelling_llama_flax.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    17266 2023-06-26 09:30:53.000000 EasyDeL-0.0.6/EasyDel/modules/llama/modelling_llama_pytorch.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/modules/lucid_transformer/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       95 2023-06-12 11:40:22.000000 EasyDeL-0.0.6/EasyDel/modules/lucid_transformer/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    13472 2023-06-28 07:13:59.000000 EasyDeL-0.0.6/EasyDel/modules/lucid_transformer/modelling_lt_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/modules/mosaic_mpt/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       76 2023-06-15 07:43:43.000000 EasyDeL-0.0.6/EasyDel/modules/mosaic_mpt/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    17799 2023-06-25 09:09:59.000000 EasyDeL-0.0.6/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/serve/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-17 08:13:44.000000 EasyDeL-0.0.6/EasyDel/serve/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1482 2023-06-17 08:09:33.000000 EasyDeL-0.0.6/EasyDel/serve/serve_utils.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/trainer/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      146 2023-06-27 07:17:54.000000 EasyDeL-0.0.6/EasyDel/trainer/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     8996 2023-06-26 10:53:42.000000 EasyDeL-0.0.6/EasyDel/trainer/config.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    21478 2023-06-28 13:18:01.000000 EasyDeL-0.0.6/EasyDel/trainer/fsdp_train.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/utils/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      402 2023-06-11 11:51:31.000000 EasyDeL-0.0.6/EasyDel/utils/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      389 2023-06-11 11:51:31.000000 EasyDeL-0.0.6/EasyDel/utils/checker.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     4584 2023-06-26 09:09:30.000000 EasyDeL-0.0.6/EasyDel/utils/utils.py
+drwxrwxr-x   0 erfan     (1000) erfan     (1000)        0 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/EasyDel/weight_convertor/
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)        0 2023-06-17 06:47:56.000000 EasyDeL-0.0.6/EasyDel/weight_convertor/__init__.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     6215 2023-06-18 09:17:09.000000 EasyDeL-0.0.6/EasyDel/weight_convertor/falcon.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     5077 2023-06-24 06:51:39.000000 EasyDeL-0.0.6/EasyDel/weight_convertor/llama.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     9833 2023-06-17 12:12:31.000000 EasyDeL-0.0.6/EasyDel/weight_convertor/mpt.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      858 2023-06-17 10:41:48.000000 EasyDeL-0.0.6/EasyDel/weight_convertor/utils.py
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)    11357 2023-06-11 11:51:31.000000 EasyDeL-0.0.6/LICENSE
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     6280 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/PKG-INFO
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     5386 2023-06-28 07:19:22.000000 EasyDeL-0.0.6/README.md
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)      608 2023-06-24 06:51:39.000000 EasyDeL-0.0.6/pyproject.toml
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)       38 2023-06-28 13:19:05.304205 EasyDeL-0.0.6/setup.cfg
+-rw-rw-r--   0 erfan     (1000) erfan     (1000)     1124 2023-06-28 13:18:01.000000 EasyDeL-0.0.6/setup.py
```

### Comparing `EasyDeL-0.0.5/EasyDeL.egg-info/PKG-INFO` & `EasyDeL-0.0.6/EasyDeL.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: EasyDeL
-Version: 0.0.5
+Version: 0.0.6
 Summary: An open-source library to make training faster and more optimized in Jax/Flax
 Home-page: https://github.com/erfanzar/EasyDeL
 Author: Erfan Zare Chavoshi
 Author-email: erfanzare82@eyahoo.com
 License: UNKNOWN
 Keywords: machine learning,deep learning,pytorch
 Platform: UNKNOWN
```

### Comparing `EasyDeL-0.0.5/EasyDeL.egg-info/SOURCES.txt` & `EasyDeL-0.0.6/EasyDeL.egg-info/SOURCES.txt`

 * *Files 3% similar despite different names*

```diff
@@ -4,14 +4,16 @@
 setup.py
 EasyDeL.egg-info/PKG-INFO
 EasyDeL.egg-info/SOURCES.txt
 EasyDeL.egg-info/dependency_links.txt
 EasyDeL.egg-info/requires.txt
 EasyDeL.egg-info/top_level.txt
 EasyDel/__init__.py
+EasyDel/configs/__init__.py
+EasyDel/configs/configs.py
 EasyDel/modules/__init__.py
 EasyDel/modules/falcon/__init__.py
 EasyDel/modules/falcon/modelling_falcon_flax.py
 EasyDel/modules/gpt_j/__init__.py
 EasyDel/modules/gpt_j/modelling_gpt_j_flax.py
 EasyDel/modules/gpt_neo_x/__init__.py
 EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py
```

### Comparing `EasyDeL-0.0.5/EasyDel/__init__.py` & `EasyDeL-0.0.6/EasyDel/__init__.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/modules/__init__.py` & `EasyDeL-0.0.6/EasyDel/modules/__init__.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/modules/falcon/modelling_falcon_flax.py` & `EasyDeL-0.0.6/EasyDel/modules/falcon/modelling_falcon_flax.py`

 * *Files 6% similar despite different names*

```diff
@@ -71,14 +71,16 @@
             hidden_dropout=0.0,
             attention_dropout=0.0,
             multi_query=False,
             alibi=False,
             bias=False,
             parallel_attn=False,
             max_seq_len=2048,
+            use_pjit_attention_force: bool = False,
+            gradient_checkpointing: str = 'nothing_saveable',
             **kwargs,
     ):
         self.vocab_size = vocab_size
         n_embed = kwargs.pop("n_embed", None)
         self.hidden_size = hidden_size if n_embed is None else n_embed
         self.n_layer = n_layer
         self.n_head = n_head
@@ -86,18 +88,20 @@
         self.initializer_range = initializer_range
         self.max_seq_len = max_seq_len
         self.use_cache = use_cache
         self.apply_residual_connection_post_layernorm = apply_residual_connection_post_layernorm
         self.hidden_dropout = hidden_dropout
         self.attention_dropout = attention_dropout
         self.bos_token_id = bos_token_id
+        self.use_pjit_attention_force = use_pjit_attention_force
         self.eos_token_id = eos_token_id
         self.multi_query = multi_query
         self.alibi = alibi
         self.bias = bias
+        self.gradient_checkpointing = gradient_checkpointing
         self.parallel_attn = parallel_attn
 
         super().__init__(bos_token_id=bos_token_id, eos_token_id=eos_token_id, **kwargs)
 
     @property
     def head_dim(self):
         return self.hidden_size // self.n_head
@@ -225,35 +229,37 @@
                  attention_mask: jnp.DeviceArray = None,
                  ):
         b, s, d = hidden_states.shape
 
         qkv = self.w_qkv(hidden_states)
         if not self.config.multi_query:
             q, k, v = jnp.split(qkv, 3, -1)
-            q = with_sharding_constraint(q, PartitionSpec(('dp', 'fsdp'), None, 'mp'))
-            k = with_sharding_constraint(k, PartitionSpec(('dp', 'fsdp'), None, 'mp'))
-            v = with_sharding_constraint(v, PartitionSpec(('dp', 'fsdp'), None, 'mp'))
+            if self.config.use_pjit_attention_force:
+                q = with_sharding_constraint(q, PartitionSpec(('dp', 'fsdp'), None, 'mp'))
+                k = with_sharding_constraint(k, PartitionSpec(('dp', 'fsdp'), None, 'mp'))
+                v = with_sharding_constraint(v, PartitionSpec(('dp', 'fsdp'), None, 'mp'))
             k = rearrange(k, 'b s (h d) -> b s h d', h=self.config.n_head)
             q = rearrange(q, 'b s (h d) -> b s h d', h=self.config.n_head)
             v = rearrange(v, 'b s (h d) -> b s h d', h=self.config.n_head)
         else:
             qkv = qkv.reshape(
                 b, s, self.config.n_head + 2, -1
             )
             q, k, v = qkv[..., :-2, :], qkv[..., [-2], :], qkv[..., [-1], :]
-
-            q = with_sharding_constraint(q, PartitionSpec(('dp', 'fsdp'), None, None, 'mp'))
-            k = with_sharding_constraint(k, PartitionSpec(('dp', 'fsdp'), None, None, 'mp'))
-            v = with_sharding_constraint(v, PartitionSpec(('dp', 'fsdp'), None, None, 'mp'))
+            if self.config.use_pjit_attention_force:
+                q = with_sharding_constraint(q, PartitionSpec(('dp', 'fsdp'), None, None, 'mp'))
+                k = with_sharding_constraint(k, PartitionSpec(('dp', 'fsdp'), None, None, 'mp'))
+                v = with_sharding_constraint(v, PartitionSpec(('dp', 'fsdp'), None, None, 'mp'))
 
         if not self.config.alibi:
             freq = self.freq[:s].reshape(1, s, -1)
             q, k = apply_rotary_emb(q, k, freq, self.dtype)
         attn = jnp.einsum('...qhd,...khd->...hqk', q, k, precision=self.precision)
-        attn = with_sharding_constraint(attn, PartitionSpec(("dp", "fsdp"), "mp", None, None))
+        if self.config.use_pjit_attention_force:
+            attn = with_sharding_constraint(attn, PartitionSpec(("dp", "fsdp"), "mp", None, None))
 
         if alibi is not None:
             attn += alibi
         attn = attn * self.factor_scale
 
         if attention_mask is not None:
             attn += attention_mask
@@ -333,23 +339,38 @@
 
         mlp_out = self.mlp(hidden_states)
         if self.config.parallel_attn:
             mlp_out += attn
         return mlp_out + residual
 
 
+def get_gradient_checkpoint_policy(name):
+    return {
+        'everything_saveable': jax.checkpoint_policies.everything_saveable,
+        'nothing_saveable': jax.checkpoint_policies.nothing_saveable,
+        'checkpoint_dots': jax.checkpoint_policies.checkpoint_dots,
+        'checkpoint_dots_with_no_batch_dims': jax.checkpoint_policies.checkpoint_dots_with_no_batch_dims,
+    }[name]
+
+
 class FlaxFalconCollection(nn.Module):
     config: FalconConfig
     dtype: jnp.dtype = jnp.float32
     param_dtype: jnp.dtype = jnp.float32
     precision: Optional[Union[jax.lax.Precision, str]] = None
 
     def setup(self) -> None:
+        block = FlaxFalconBlock
+        if self.config.gradient_checkpointing != '':
+            block = nn.remat(
+                block,
+                policy=get_gradient_checkpoint_policy(self.config.gradient_checkpointing)
+            )
         self.blocks = [
-            FlaxFalconBlock(
+            block(
                 config=self.config,
                 dtype=self.dtype,
                 param_dtype=self.param_dtype,
                 precision=self.precision,
                 name=str(i)
             )
             for i in range(
```

### Comparing `EasyDeL-0.0.5/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py` & `EasyDeL-0.0.6/EasyDel/modules/gpt_j/modelling_gpt_j_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py` & `EasyDeL-0.0.6/EasyDel/modules/gpt_neo_x/modelling_gpt_neo_x_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_flax.py` & `EasyDeL-0.0.6/EasyDel/modules/llama/modelling_llama_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/modules/llama/modelling_llama_pytorch.py` & `EasyDeL-0.0.6/EasyDel/modules/llama/modelling_llama_pytorch.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/modules/lucid_transformer/modelling_lt_flax.py` & `EasyDeL-0.0.6/EasyDel/modules/lucid_transformer/modelling_lt_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py` & `EasyDeL-0.0.6/EasyDel/modules/mosaic_mpt/modelling_mpt_flax.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/serve/serve_utils.py` & `EasyDeL-0.0.6/EasyDel/serve/serve_utils.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/trainer/config.py` & `EasyDeL-0.0.6/EasyDel/trainer/config.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/trainer/fsdp_train.py` & `EasyDeL-0.0.6/EasyDel/trainer/fsdp_train.py`

 * *Files 1% similar despite different names*

```diff
@@ -230,44 +230,47 @@
 
         timer.write(timer.timers.keys(), 0)
         pbar = tqdm(total=max_steps_train)
         i = sharded_train_state_.step.tolist()
         losses = []
         pbar.update(sharded_train_state_.step.tolist())
         learning_rates = []
-        for ep in range(training_arguments.num_train_epochs):
-            for batch in dataloader_train:
-                i += 1
-                if i < max_steps_train:
-
-                    _ = batch.pop('token_type_ids', None)
-                    for i in ids_to_pop_from_dataset:
-                        _ = batch.pop(i, None)
-                    sharded_train_state_, loss = sharded_train_step_fn(sharded_train_state_, batch)
-                    losses.append(loss)
-                    learning_rates.append(scheduler(i).tolist())
-                    pbar.update(1)
-                    # clear_output(True)
-                    if use_wandb:
-                        wandb_runtime.log(
-                            {'loss': loss.tolist(),
-                             'learning_rate': scheduler(sharded_train_state_.step.tolist()).tolist(),
-                             'step': sharded_train_state_.step.tolist()}
-                        )
-                    pbar.set_postfix(loss=loss, learning_rate=scheduler(sharded_train_state_.step.tolist()).tolist(),
-                                     step=sharded_train_state_.step.tolist())
-                else:
-                    break
-                if training_arguments.save_steps is not None and i % training_arguments.save_steps == 0:
-                    filename = f'{training_arguments.model_name}-{sum(losses) / len(losses)}-{i}'
-                    print(f'Saving Model to \033[1;30m{filename}\033[1;0m')
-                    ckpt_streamer.save_checkpoint(sharded_train_state_.params['params'],
-                                                  filename,
-                                                  gather_fns=gather_fns.params['params'])
+        try:
+            for ep in range(training_arguments.num_train_epochs):
+                for batch in dataloader_train:
+                    i += 1
+                    if i < max_steps_train:
 
+                        _ = batch.pop('token_type_ids', None)
+                        for i in ids_to_pop_from_dataset:
+                            _ = batch.pop(i, None)
+                        sharded_train_state_, loss = sharded_train_step_fn(sharded_train_state_, batch)
+                        losses.append(loss)
+                        learning_rates.append(scheduler(i).tolist())
+                        pbar.update(1)
+                        # clear_output(True)
+                        if use_wandb:
+                            wandb_runtime.log(
+                                {'loss': loss.tolist(),
+                                 'learning_rate': scheduler(sharded_train_state_.step.tolist()).tolist(),
+                                 'step': sharded_train_state_.step.tolist()}
+                            )
+                        pbar.set_postfix(loss=loss,
+                                         learning_rate=scheduler(sharded_train_state_.step.tolist()).tolist(),
+                                         step=sharded_train_state_.step.tolist())
+                    else:
+                        break
+                    if training_arguments.save_steps is not None and i % training_arguments.save_steps == 0:
+                        filename = f'{training_arguments.model_name}-{sum(losses) / len(losses)}-{i}'
+                        print(f'Saving Model to \033[1;30m{filename}\033[1;0m')
+                        ckpt_streamer.save_checkpoint(sharded_train_state_.params['params'],
+                                                      filename,
+                                                      gather_fns=gather_fns.params['params'])
+        except KeyboardInterrupt:
+            print('\033[1;30m KeyboardInterrupt At training model Will return current state of the model * \033[1;0m')
         if training_arguments.do_eval:
             if dataset_eval is not None:
                 pbar_eval = tqdm(total=max_steps_eval)
                 for i_eval, batch_eval in enumerate(dataloader_eval):
                     _ = batch_eval.pop('token_type_ids', None)
                     for i in ids_to_pop_from_dataset:
                         _ = batch_eval.pop(i, None)
@@ -292,14 +295,15 @@
         train_state=sharded_train_state_,
         mesh=mesh,
         shard_fns=shard_fns,
         gather_fns=gather_fns,
         ckpt_stream=ckpt_streamer
     )
     wandb.finish()
+
     return output
 
 
 def pre_trainer_or_base_trainer(
         dataset_train,
         training_arguments: TrainArguments,
         use_pjit_attention_force: bool = True,
```

### Comparing `EasyDeL-0.0.5/EasyDel/utils/utils.py` & `EasyDeL-0.0.6/EasyDel/utils/utils.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/weight_convertor/falcon.py` & `EasyDeL-0.0.6/EasyDel/weight_convertor/falcon.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/weight_convertor/llama.py` & `EasyDeL-0.0.6/EasyDel/weight_convertor/llama.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/weight_convertor/mpt.py` & `EasyDeL-0.0.6/EasyDel/weight_convertor/mpt.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/EasyDel/weight_convertor/utils.py` & `EasyDeL-0.0.6/EasyDel/weight_convertor/utils.py`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/LICENSE` & `EasyDeL-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/PKG-INFO` & `EasyDeL-0.0.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: EasyDeL
-Version: 0.0.5
+Version: 0.0.6
 Summary: An open-source library to make training faster and more optimized in Jax/Flax
 Home-page: https://github.com/erfanzar/EasyDeL
 Author: Erfan Zare Chavoshi
 Author-email: erfanzare82@eyahoo.com
 License: UNKNOWN
 Keywords: machine learning,deep learning,pytorch
 Platform: UNKNOWN
```

### Comparing `EasyDeL-0.0.5/README.md` & `EasyDeL-0.0.6/README.md`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/pyproject.toml` & `EasyDeL-0.0.6/pyproject.toml`

 * *Files identical despite different names*

### Comparing `EasyDeL-0.0.5/setup.py` & `EasyDeL-0.0.6/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name='EasyDeL',
-    version='0.0.5',
+    version='0.0.6',
     author='Erfan Zare Chavoshi',
     author_email='erfanzare82@eyahoo.com',
     description='An open-source library to make training faster and more optimized in Jax/Flax',
     url='https://github.com/erfanzar/EasyDeL',
     packages=find_packages(),
     long_description=open('README.md').read(),
     long_description_content_type='text/markdown',
```

