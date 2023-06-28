# Comparing `tmp/lycoris_lora-0.1.7.dev9.tar.gz` & `tmp/lycoris_lora-1.7.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "lycoris_lora-0.1.7.dev9.tar", last modified: Mon Jun 26 04:15:51 2023, max compression
+gzip compressed data, was "lycoris_lora-1.7.1.tar", last modified: Wed Jun 28 12:51:07 2023, max compression
```

## Comparing `lycoris_lora-0.1.7.dev9.tar` & `lycoris_lora-1.7.1.tar`

### file list

```diff
@@ -1,41 +1,25 @@
-drwxrwxrwx   0        0        0        0 2023-06-26 04:15:51.502090 lycoris_lora-0.1.7.dev9/
--rw-rw-rw-   0        0        0     1623 2023-03-09 05:37:07.000000 lycoris_lora-0.1.7.dev9/.gitignore
--rw-rw-rw-   0        0        0     4436 2023-04-09 13:45:45.000000 lycoris_lora-0.1.7.dev9/Algo.md
--rw-rw-rw-   0        0        0      618 2023-06-05 03:31:07.000000 lycoris_lora-0.1.7.dev9/Change.md
--rw-rw-rw-   0        0        0     2828 2023-03-09 12:01:15.000000 lycoris_lora-0.1.7.dev9/Demo.md
--rw-rw-rw-   0        0        0    11545 2023-03-09 05:37:07.000000 lycoris_lora-0.1.7.dev9/LICENSE.md
--rw-rw-rw-   0        0        0      353 2023-06-26 04:15:51.501591 lycoris_lora-0.1.7.dev9/PKG-INFO
--rw-rw-rw-   0        0        0     7396 2023-06-05 03:31:07.000000 lycoris_lora-0.1.7.dev9/README.md
-drwxrwxrwx   0        0        0        0 2023-06-26 04:15:51.491581 lycoris_lora-0.1.7.dev9/experiments/
--rw-rw-rw-   0        0        0     3579 2023-03-12 01:46:48.000000 lycoris_lora-0.1.7.dev9/experiments/better_conv.py
--rw-rw-rw-   0        0        0     1967 2023-03-12 01:46:43.000000 lycoris_lora-0.1.7.dev9/experiments/better_conv_extract.py
--rw-rw-rw-   0        0        0     8783 2023-03-12 03:21:33.000000 lycoris_lora-0.1.7.dev9/experiments/concept_neuron.py
--rw-rw-rw-   0        0        0      894 2023-03-09 14:26:54.000000 lycoris_lora-0.1.7.dev9/experiments/locon_extract_test.py
--rw-rw-rw-   0        0        0      755 2023-03-10 15:36:09.000000 lycoris_lora-0.1.7.dev9/experiments/locon_merge_test.py
--rw-rw-rw-   0        0        0     3411 2023-03-09 05:37:07.000000 lycoris_lora-0.1.7.dev9/experiments/singular_value_test.py
--rw-rw-rw-   0        0        0     2334 2023-03-11 09:28:26.000000 lycoris_lora-0.1.7.dev9/experiments/sparse_bias_test.py
--rw-rw-rw-   0        0        0     2791 2023-03-12 01:46:48.000000 lycoris_lora-0.1.7.dev9/experiments/time_test.py
-drwxrwxrwx   0        0        0        0 2023-06-26 04:15:51.494580 lycoris_lora-0.1.7.dev9/lycoris/
--rw-rw-rw-   0        0        0      113 2023-03-09 05:37:07.000000 lycoris_lora-0.1.7.dev9/lycoris/__init__.py
--rw-rw-rw-   0        0        0     6258 2023-06-25 13:20:45.000000 lycoris_lora-0.1.7.dev9/lycoris/dylora.py
--rw-rw-rw-   0        0        0     2103 2023-04-04 08:21:48.000000 lycoris_lora-0.1.7.dev9/lycoris/ia3.py
--rw-rw-rw-   0        0        0    23863 2023-06-26 04:15:23.000000 lycoris_lora-0.1.7.dev9/lycoris/kohya.py
--rw-rw-rw-   0        0        0    48868 2023-04-09 15:10:02.000000 lycoris_lora-0.1.7.dev9/lycoris/kohya_model_utils.py
--rw-rw-rw-   0        0        0     1512 2023-03-09 05:37:07.000000 lycoris_lora-0.1.7.dev9/lycoris/kohya_utils.py
--rw-rw-rw-   0        0        0     4461 2023-06-25 13:17:36.000000 lycoris_lora-0.1.7.dev9/lycoris/locon.py
--rw-rw-rw-   0        0        0     8827 2023-06-25 13:27:40.000000 lycoris_lora-0.1.7.dev9/lycoris/loha.py
--rw-rw-rw-   0        0        0    10808 2023-06-25 13:27:52.000000 lycoris_lora-0.1.7.dev9/lycoris/lokr.py
--rw-rw-rw-   0        0        0    20963 2023-06-05 03:39:30.000000 lycoris_lora-0.1.7.dev9/lycoris/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-26 04:15:51.500587 lycoris_lora-0.1.7.dev9/lycoris_lora.egg-info/
--rw-rw-rw-   0        0        0      353 2023-06-26 04:15:51.000000 lycoris_lora-0.1.7.dev9/lycoris_lora.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      773 2023-06-26 04:15:51.000000 lycoris_lora-0.1.7.dev9/lycoris_lora.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-26 04:15:51.000000 lycoris_lora-0.1.7.dev9/lycoris_lora.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        2 2023-03-09 13:25:15.000000 lycoris_lora-0.1.7.dev9/lycoris_lora.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0       41 2023-06-26 04:15:51.000000 lycoris_lora-0.1.7.dev9/lycoris_lora.egg-info/requires.txt
--rw-rw-rw-   0        0        0        8 2023-06-26 04:15:51.000000 lycoris_lora-0.1.7.dev9/lycoris_lora.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       43 2023-03-09 05:37:07.000000 lycoris_lora-0.1.7.dev9/requirements.txt
--rw-rw-rw-   0        0        0       42 2023-06-26 04:15:51.502090 lycoris_lora-0.1.7.dev9/setup.cfg
--rw-rw-rw-   0        0        0      547 2023-06-26 04:15:40.000000 lycoris_lora-0.1.7.dev9/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-26 04:15:51.501591 lycoris_lora-0.1.7.dev9/tools/
--rw-rw-rw-   0        0        0     4087 2023-03-12 16:11:52.000000 lycoris_lora-0.1.7.dev9/tools/extract_locon.py
--rw-rw-rw-   0        0        0     2293 2023-06-05 03:39:47.000000 lycoris_lora-0.1.7.dev9/tools/merge.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:51:07.572872 lycoris_lora-1.7.1/
+-rw-rw-rw-   0        0        0    11545 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/LICENSE.md
+-rw-rw-rw-   0        0        0      348 2023-06-28 12:51:07.572872 lycoris_lora-1.7.1/PKG-INFO
+-rw-rw-rw-   0        0        0     7677 2023-06-28 12:51:02.000000 lycoris_lora-1.7.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:51:07.559910 lycoris_lora-1.7.1/lycoris/
+-rw-rw-rw-   0        0        0      113 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/__init__.py
+-rw-rw-rw-   0        0        0     6258 2023-06-28 09:12:31.000000 lycoris_lora-1.7.1/lycoris/dylora.py
+-rw-rw-rw-   0        0        0     4099 2023-06-28 11:53:14.000000 lycoris_lora-1.7.1/lycoris/glora.py
+-rw-rw-rw-   0        0        0     2103 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/ia3.py
+-rw-rw-rw-   0        0        0    23863 2023-06-28 12:48:17.000000 lycoris_lora-1.7.1/lycoris/kohya.py
+-rw-rw-rw-   0        0        0    48868 2023-06-15 09:10:55.000000 lycoris_lora-1.7.1/lycoris/kohya_model_utils.py
+-rw-rw-rw-   0        0        0     1512 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/kohya_utils.py
+-rw-rw-rw-   0        0        0     4468 2023-06-28 12:46:54.000000 lycoris_lora-1.7.1/lycoris/locon.py
+-rw-rw-rw-   0        0        0     8831 2023-06-28 12:47:04.000000 lycoris_lora-1.7.1/lycoris/loha.py
+-rw-rw-rw-   0        0        0    10856 2023-06-28 12:47:14.000000 lycoris_lora-1.7.1/lycoris/lokr.py
+-rw-rw-rw-   0        0        0    20963 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:51:07.570878 lycoris_lora-1.7.1/lycoris_lora.egg-info/
+-rw-rw-rw-   0        0        0      348 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      448 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        2 2023-06-04 13:39:16.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0       41 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        8 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:51:07.572872 lycoris_lora-1.7.1/setup.cfg
+-rw-rw-rw-   0        0        0      542 2023-06-28 12:51:05.000000 lycoris_lora-1.7.1/setup.py
```

### Comparing `lycoris_lora-0.1.7.dev9/LICENSE.md` & `lycoris_lora-1.7.1/LICENSE.md`

 * *Files identical despite different names*

### Comparing `lycoris_lora-0.1.7.dev9/README.md` & `lycoris_lora-1.7.1/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -134,17 +134,22 @@
 ## Example and Comparing for different algo
 see [Demo.md](https://github.com/KohakuBlueleaf/LyCORIS/blob/main/Demo.md) and [Algo.md](https://github.com/KohakuBlueleaf/LyCORIS/blob/main/Algo.md)
 
 
 ## Change Log
 For full log, please see [Change.md](https://github.com/KohakuBlueleaf/LyCORIS/blob/main/Change.md)
 
-### 2023/04/08 Update for 0.1.5
-* Add (IA)^3 algorithm
-* Add lokr algorithm
+### 2023/06/28 update to 1.7.1
+* **rearrange the version format, previous 0.1.7 should be 1.7.0**
+* fix the bug in scale weight norm
+
+### 2023/06/26 Update for 0.1.7
+* Add support for rank_dropout and module_dropout on LoCon/LoHa/LoKr
+* Add support for scale_weight_norms on LoCon/LoHa/LoKr
+* Will support SDXL on 0.1.8 (you can follow the dev branch)
 
 ## Todo list
 - [ ] Module and Document for using LyCORIS in any other model, Not only SD.
 - [x] Proposition3 in [FedPara](https://arxiv.org/abs/2108.06098)
   * also need custom backward to save the vram
 - [ ] Low rank + sparse representation
   - [x] For extraction
```

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/dylora.py` & `lycoris_lora-1.7.1/lycoris/dylora.py`

 * *Files identical despite different names*

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/ia3.py` & `lycoris_lora-1.7.1/lycoris/ia3.py`

 * *Files identical despite different names*

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/kohya.py` & `lycoris_lora-1.7.1/lycoris/kohya.py`

 * *Files identical despite different names*

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/kohya_model_utils.py` & `lycoris_lora-1.7.1/lycoris/kohya_model_utils.py`

 * *Files identical despite different names*

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/kohya_utils.py` & `lycoris_lora-1.7.1/lycoris/kohya_utils.py`

 * *Files identical despite different names*

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/locon.py` & `lycoris_lora-1.7.1/lycoris/locon.py`

 * *Files 0% similar despite different names*

```diff
@@ -83,15 +83,15 @@
     @torch.no_grad()
     def apply_max_norm(self, max_norm, device=None):
         orig_norm = self.make_weight(device).norm()*self.scale
         norm = torch.clamp(orig_norm, max_norm/2)
         desired = torch.clamp(norm, max=max_norm)
         ratio = desired.cpu()/norm.cpu()
         
-        scaled = ratio != 1.0
+        scaled = ratio.item() != 1.0
         if scaled:
             modules = self.cp + 2
             self.lora_up.weight *= ratio**(1/modules)
             self.lora_down.weight *= ratio**(1/modules)
             if self.cp:
                 self.lora_mid.weight *= ratio**(1/modules)
```

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/loha.py` & `lycoris_lora-1.7.1/lycoris/loha.py`

 * *Files 0% similar despite different names*

```diff
@@ -137,16 +137,16 @@
             self.hada_w1_a = nn.Parameter(torch.empty(shape[0], lora_dim))
             self.hada_w1_b = nn.Parameter(torch.empty(lora_dim, shape[1]))
             
             self.hada_w2_a = nn.Parameter(torch.empty(shape[0], lora_dim))
             self.hada_w2_b = nn.Parameter(torch.empty(lora_dim, shape[1]))
         
         self.dropout = dropout
-        if rank_dropout:
-            print("[WARN]LoHa/LoKr haven't implemented rank dropout yet.")
+        if dropout:
+            print("[WARN]LoHa/LoKr haven't implemented normal dropout yet.")
         self.rank_dropout = rank_dropout
         self.module_dropout = module_dropout
         
         if type(alpha) == torch.Tensor:
             alpha = alpha.detach().float().numpy()  # without casting, bf16 causes error
         alpha = lora_dim if alpha is None or alpha == 0 else alpha
         self.scale = alpha / self.lora_dim
@@ -191,15 +191,15 @@
     @torch.no_grad()
     def apply_max_norm(self, max_norm, device=None):
         orig_norm = self.get_weight().norm()
         norm = torch.clamp(orig_norm, max_norm/2)
         desired = torch.clamp(norm, max=max_norm)
         ratio = desired.cpu()/norm.cpu()
         
-        scaled = ratio != 1.0
+        scaled = ratio.item() != 1.0
         if scaled:
             modules = (self.cp + 2)*2
             self.hada_w1_a *= ratio**(1/modules)
             self.hada_w1_b *= ratio**(1/modules)
             self.hada_w2_a *= ratio**(1/modules)
             self.hada_w2_b *= ratio**(1/modules)
```

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/lokr.py` & `lycoris_lora-1.7.1/lycoris/lokr.py`

 * *Files 1% similar despite different names*

```diff
@@ -156,16 +156,17 @@
                 self.use_w2 = True
                 self.lokr_w2 = nn.Parameter(torch.empty(shape[0][1], shape[1][1]))
 
             self.op = F.linear
             self.extra_args = {}
         
         self.dropout = dropout
-        if rank_dropout:
-            print("[WARN]LyCORIS haven't implemented rank dropout yet.")
+        if dropout:
+            print("[WARN]LoHa/LoKr haven't implemented normal dropout yet.")
+        self.rank_dropout = rank_dropout
         self.module_dropout = module_dropout
         
         if isinstance(alpha, torch.Tensor):
             alpha = alpha.detach().float().numpy()  # without casting, bf16 causes error
         alpha = lora_dim if alpha is None or alpha == 0 else alpha
         if self.use_w2 and self.use_w1:
             #use scale = 1
@@ -222,15 +223,15 @@
     @torch.no_grad()
     def apply_max_norm(self, max_norm, device=None):
         orig_norm = self.get_weight().norm()
         norm = torch.clamp(orig_norm, max_norm/2)
         desired = torch.clamp(norm, max=max_norm)
         ratio = desired.cpu()/norm.cpu()
         
-        scaled = ratio != 1.0
+        scaled = ratio.item() != 1.0
         if scaled:
             modules = (4 - self.use_w1 - self.use_w2 + (not self.use_w2 and self.cp))
             if self.use_w1:
                 self.lokr_w1_a *= ratio**(1/modules)
                 self.lokr_w1_b *= ratio**(1/modules)
             else:
                 self.lokr_w1 *= ratio**(1/modules)
```

### Comparing `lycoris_lora-0.1.7.dev9/lycoris/utils.py` & `lycoris_lora-1.7.1/lycoris/utils.py`

 * *Files identical despite different names*

### Comparing `lycoris_lora-0.1.7.dev9/setup.py` & `lycoris_lora-1.7.1/setup.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import setup
 
 setup(
     name='lycoris_lora',
     packages=['lycoris'],
-    version='0.1.7.dev9',
+    version='1.7.1',
     url='https://github.com/KohakuBlueleaf/LyCORIS',
     description='Lora beYond Conventional methods, Other Rank adaptation Implementations for Stable diffusion',
     author='Shih-Ying Yeh(KohakuBlueLeaf), Yu-Guan Hsieh, Zhidong Gao',
     author_email='apolloyeh0123@gmail.com',
     zip_safe=False,
     install_requires=[
         'torch',
```

