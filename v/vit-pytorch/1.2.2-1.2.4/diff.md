# Comparing `tmp/vit-pytorch-1.2.2.tar.gz` & `tmp/vit-pytorch-1.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "vit-pytorch-1.2.2.tar", last modified: Sat May 20 15:25:21 2023, max compression
+gzip compressed data, was "vit-pytorch-1.2.4.tar", last modified: Wed Jun 28 15:03:13 2023, max compression
```

## Comparing `vit-pytorch-1.2.2.tar` & `vit-pytorch-1.2.4.tar`

### file list

```diff
@@ -1,61 +1,61 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-20 15:25:21.742535 vit-pytorch-1.2.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1066 2023-05-20 15:25:10.000000 vit-pytorch-1.2.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-05-20 15:25:10.000000 vit-pytorch-1.2.2/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)      611 2023-05-20 15:25:21.742535 vit-pytorch-1.2.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    60828 2023-05-20 15:25:10.000000 vit-pytorch-1.2.2/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-20 15:25:21.742535 vit-pytorch-1.2.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-20 15:25:21.738535 vit-pytorch-1.2.2/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      407 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/tests/test.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-20 15:25:21.742535 vit-pytorch-1.2.2/vit_pytorch/
--rw-r--r--   0 runner    (1001) docker     (123)      353 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10258 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/ats_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     5834 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/cait.py
--rw-r--r--   0 runner    (1001) docker     (123)    12001 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/cct.py
--rw-r--r--   0 runner    (1001) docker     (123)    12186 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/cct_3d.py
--rw-r--r--   0 runner    (1001) docker     (123)     9194 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/cross_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     8347 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/crossformer.py
--rw-r--r--   0 runner    (1001) docker     (123)     6085 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/cvt.py
--rw-r--r--   0 runner    (1001) docker     (123)     4636 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/deepvit.py
--rw-r--r--   0 runner    (1001) docker     (123)     9662 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/dino.py
--rw-r--r--   0 runner    (1001) docker     (123)     4466 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/distill.py
--rw-r--r--   0 runner    (1001) docker     (123)     1813 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/efficient.py
--rw-r--r--   0 runner    (1001) docker     (123)    12657 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/es_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     2478 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/extractor.py
--rw-r--r--   0 runner    (1001) docker     (123)     7308 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/learnable_memory_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     6474 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/levit.py
--rw-r--r--   0 runner    (1001) docker     (123)     5056 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/local_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     3936 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/mae.py
--rw-r--r--   0 runner    (1001) docker     (123)     8305 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/max_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     7897 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/mobile_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     6160 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/mp3.py
--rw-r--r--   0 runner    (1001) docker     (123)     5797 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/mpp.py
--rw-r--r--   0 runner    (1001) docker     (123)     6003 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/nest.py
--rw-r--r--   0 runner    (1001) docker     (123)     4697 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/parallel_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     5828 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/pit.py
--rw-r--r--   0 runner    (1001) docker     (123)     1772 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/recorder.py
--rw-r--r--   0 runner    (1001) docker     (123)     9055 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/regionvit.py
--rw-r--r--   0 runner    (1001) docker     (123)     7787 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/rvt.py
--rw-r--r--   0 runner    (1001) docker     (123)     9690 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/scalable_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     8998 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/sep_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     2709 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/simmim.py
--rw-r--r--   0 runner    (1001) docker     (123)     5691 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/simple_flash_attn_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     3913 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/simple_vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     3715 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/simple_vit_1d.py
--rw-r--r--   0 runner    (1001) docker     (123)     4363 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/simple_vit_3d.py
--rw-r--r--   0 runner    (1001) docker     (123)     4671 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/simple_vit_with_patch_dropout.py
--rw-r--r--   0 runner    (1001) docker     (123)     2956 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/t2t.py
--rw-r--r--   0 runner    (1001) docker     (123)     8106 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/twins_svt.py
--rw-r--r--   0 runner    (1001) docker     (123)     4292 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/vit.py
--rw-r--r--   0 runner    (1001) docker     (123)     4043 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/vit_1d.py
--rw-r--r--   0 runner    (1001) docker     (123)     4514 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/vit_3d.py
--rw-r--r--   0 runner    (1001) docker     (123)     4992 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/vit_for_small_dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)     4949 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/vit_with_patch_dropout.py
--rw-r--r--   0 runner    (1001) docker     (123)     4955 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/vit_with_patch_merger.py
--rw-r--r--   0 runner    (1001) docker     (123)     5933 2023-05-20 15:25:11.000000 vit-pytorch-1.2.2/vit_pytorch/vivit.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-20 15:25:21.742535 vit-pytorch-1.2.2/vit_pytorch.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      611 2023-05-20 15:25:21.000000 vit-pytorch-1.2.2/vit_pytorch.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-05-20 15:25:21.000000 vit-pytorch-1.2.2/vit_pytorch.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-20 15:25:21.000000 vit-pytorch-1.2.2/vit_pytorch.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-20 15:25:21.000000 vit-pytorch-1.2.2/vit_pytorch.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-05-20 15:25:21.000000 vit-pytorch-1.2.2/vit_pytorch.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:03:13.737225 vit-pytorch-1.2.4/
+-rw-r--r--   0 runner    (1001) docker     (123)     1066 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)      611 2023-06-28 15:03:13.737225 vit-pytorch-1.2.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    60828 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:03:13.737225 vit-pytorch-1.2.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:03:13.725226 vit-pytorch-1.2.4/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      407 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/tests/test.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:03:13.737225 vit-pytorch-1.2.4/vit_pytorch/
+-rw-r--r--   0 runner    (1001) docker     (123)      353 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10258 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/ats_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5834 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/cait.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12001 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/cct.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12186 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/cct_3d.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9194 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/cross_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8347 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/crossformer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6085 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/cvt.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4636 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/deepvit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9662 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/dino.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4466 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/distill.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1813 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/efficient.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12657 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/es_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2478 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/extractor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7308 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/learnable_memory_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6474 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/levit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5056 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/local_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3936 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/mae.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8305 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/max_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7897 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/mobile_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6160 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/mp3.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5895 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/mpp.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6003 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/nest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4697 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/parallel_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5828 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/pit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1772 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/recorder.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9055 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/regionvit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7787 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/rvt.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9690 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/scalable_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8998 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/sep_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2709 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/simmim.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5691 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/simple_flash_attn_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3913 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/simple_vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3715 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/simple_vit_1d.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4363 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/simple_vit_3d.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4671 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/simple_vit_with_patch_dropout.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2956 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/t2t.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8106 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/twins_svt.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4292 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/vit.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4043 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/vit_1d.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4514 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/vit_3d.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4992 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/vit_for_small_dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4949 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/vit_with_patch_dropout.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4955 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/vit_with_patch_merger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5933 2023-06-28 15:03:04.000000 vit-pytorch-1.2.4/vit_pytorch/vivit.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:03:13.737225 vit-pytorch-1.2.4/vit_pytorch.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      611 2023-06-28 15:03:13.000000 vit-pytorch-1.2.4/vit_pytorch.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1345 2023-06-28 15:03:13.000000 vit-pytorch-1.2.4/vit_pytorch.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:03:13.000000 vit-pytorch-1.2.4/vit_pytorch.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:03:13.000000 vit-pytorch-1.2.4/vit_pytorch.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 15:03:13.000000 vit-pytorch-1.2.4/vit_pytorch.egg-info/top_level.txt
```

### Comparing `vit-pytorch-1.2.2/LICENSE` & `vit-pytorch-1.2.4/LICENSE`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/PKG-INFO` & `vit-pytorch-1.2.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vit-pytorch
-Version: 1.2.2
+Version: 1.2.4
 Summary: Vision Transformer (ViT) - Pytorch
 Home-page: https://github.com/lucidrains/vit-pytorch
 Author: Phil Wang
 Author-email: lucidrains@gmail.com
 License: MIT
 Keywords: artificial intelligence,attention mechanism,image recognition
 Classifier: Development Status :: 4 - Beta
```

### Comparing `vit-pytorch-1.2.2/README.md` & `vit-pytorch-1.2.4/README.md`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/setup.py` & `vit-pytorch-1.2.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import setup, find_packages
 
 setup(
   name = 'vit-pytorch',
   packages = find_packages(exclude=['examples']),
-  version = '1.2.2',
+  version = '1.2.4',
   license='MIT',
   description = 'Vision Transformer (ViT) - Pytorch',
   long_description_content_type = 'text/markdown',
   author = 'Phil Wang',
   author_email = 'lucidrains@gmail.com',
   url = 'https://github.com/lucidrains/vit-pytorch',
   keywords = [
```

### Comparing `vit-pytorch-1.2.2/vit_pytorch/ats_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/ats_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/cait.py` & `vit-pytorch-1.2.4/vit_pytorch/cait.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/cct.py` & `vit-pytorch-1.2.4/vit_pytorch/cct.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/cct_3d.py` & `vit-pytorch-1.2.4/vit_pytorch/cct_3d.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/cross_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/cross_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/crossformer.py` & `vit-pytorch-1.2.4/vit_pytorch/crossformer.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/cvt.py` & `vit-pytorch-1.2.4/vit_pytorch/cvt.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/deepvit.py` & `vit-pytorch-1.2.4/vit_pytorch/deepvit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/dino.py` & `vit-pytorch-1.2.4/vit_pytorch/dino.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/distill.py` & `vit-pytorch-1.2.4/vit_pytorch/distill.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/efficient.py` & `vit-pytorch-1.2.4/vit_pytorch/efficient.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/es_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/es_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/extractor.py` & `vit-pytorch-1.2.4/vit_pytorch/extractor.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/learnable_memory_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/learnable_memory_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/levit.py` & `vit-pytorch-1.2.4/vit_pytorch/levit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/local_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/local_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/mae.py` & `vit-pytorch-1.2.4/vit_pytorch/mae.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/max_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/max_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/mobile_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/mobile_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/mp3.py` & `vit-pytorch-1.2.4/vit_pytorch/mp3.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/mpp.py` & `vit-pytorch-1.2.4/vit_pytorch/mpp.py`

 * *Files 1% similar despite different names*

```diff
@@ -92,14 +92,17 @@
         std=None
     ):
         super().__init__()
         self.transformer = transformer
         self.loss = MPPLoss(patch_size, channels, output_channel_bits,
                             max_pixel_val, mean, std)
 
+        # extract patching function
+        self.patch_to_emb = nn.Sequential(transformer.to_patch_embedding[1:])
+
         # output transformation
         self.to_bits = nn.Linear(dim, 2**(output_channel_bits * channels))
 
         # vit related dimensions
         self.patch_size = patch_size
 
         # mpp related probabilities
@@ -147,15 +150,15 @@
 
         # [mask] input
         replace_prob = prob_mask_like(input, self.replace_prob).to(mask.device)
         bool_mask_replace = (mask * replace_prob) == True
         masked_input[bool_mask_replace] = self.mask_token
 
         # linear embedding of patches
-        masked_input = transformer.to_patch_embedding[-1](masked_input)
+        masked_input = self.patch_to_emb(masked_input)
 
         # add cls token to input sequence
         b, n, _ = masked_input.shape
         cls_tokens = repeat(transformer.cls_token, '() n d -> b n d', b=b)
         masked_input = torch.cat((cls_tokens, masked_input), dim=1)
 
         # add positional embeddings to input
```

### Comparing `vit-pytorch-1.2.2/vit_pytorch/nest.py` & `vit-pytorch-1.2.4/vit_pytorch/nest.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/parallel_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/parallel_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/pit.py` & `vit-pytorch-1.2.4/vit_pytorch/pit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/recorder.py` & `vit-pytorch-1.2.4/vit_pytorch/recorder.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/regionvit.py` & `vit-pytorch-1.2.4/vit_pytorch/regionvit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/rvt.py` & `vit-pytorch-1.2.4/vit_pytorch/rvt.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/scalable_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/scalable_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/sep_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/sep_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/simmim.py` & `vit-pytorch-1.2.4/vit_pytorch/simmim.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/simple_flash_attn_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/simple_flash_attn_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/simple_vit.py` & `vit-pytorch-1.2.4/vit_pytorch/simple_vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/simple_vit_1d.py` & `vit-pytorch-1.2.4/vit_pytorch/simple_vit_1d.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/simple_vit_3d.py` & `vit-pytorch-1.2.4/vit_pytorch/simple_vit_3d.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/simple_vit_with_patch_dropout.py` & `vit-pytorch-1.2.4/vit_pytorch/simple_vit_with_patch_dropout.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/t2t.py` & `vit-pytorch-1.2.4/vit_pytorch/t2t.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/twins_svt.py` & `vit-pytorch-1.2.4/vit_pytorch/twins_svt.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/vit.py` & `vit-pytorch-1.2.4/vit_pytorch/vit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/vit_1d.py` & `vit-pytorch-1.2.4/vit_pytorch/vit_1d.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/vit_3d.py` & `vit-pytorch-1.2.4/vit_pytorch/vit_3d.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/vit_for_small_dataset.py` & `vit-pytorch-1.2.4/vit_pytorch/vit_for_small_dataset.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/vit_with_patch_dropout.py` & `vit-pytorch-1.2.4/vit_pytorch/vit_with_patch_dropout.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/vit_with_patch_merger.py` & `vit-pytorch-1.2.4/vit_pytorch/vit_with_patch_merger.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch/vivit.py` & `vit-pytorch-1.2.4/vit_pytorch/vivit.py`

 * *Files identical despite different names*

### Comparing `vit-pytorch-1.2.2/vit_pytorch.egg-info/PKG-INFO` & `vit-pytorch-1.2.4/vit_pytorch.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vit-pytorch
-Version: 1.2.2
+Version: 1.2.4
 Summary: Vision Transformer (ViT) - Pytorch
 Home-page: https://github.com/lucidrains/vit-pytorch
 Author: Phil Wang
 Author-email: lucidrains@gmail.com
 License: MIT
 Keywords: artificial intelligence,attention mechanism,image recognition
 Classifier: Development Status :: 4 - Beta
```

### Comparing `vit-pytorch-1.2.2/vit_pytorch.egg-info/SOURCES.txt` & `vit-pytorch-1.2.4/vit_pytorch.egg-info/SOURCES.txt`

 * *Files identical despite different names*

