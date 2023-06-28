# Comparing `tmp/image-reward-1.3.tar.gz` & `tmp/image-reward-1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/image-reward-1.3.tar", last modified: Thu Jun  8 02:03:49 2023, max compression
+gzip compressed data, was "dist/image-reward-1.4.tar", last modified: Wed Jun 28 10:55:00 2023, max compression
```

## Comparing `image-reward-1.3.tar` & `image-reward-1.4.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-08 02:03:49.000000 image-reward-1.3/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-08 02:03:49.000000 image-reward-1.3/ImageReward/
--rw-r--r--   0 root         (0) root         (0)     6969 2023-05-25 09:11:16.000000 image-reward-1.3/ImageReward/ImageReward.py
--rw-r--r--   0 root         (0) root         (0)    36541 2023-06-07 14:04:32.000000 image-reward-1.3/ImageReward/ReFL.py
--rw-r--r--   0 root         (0) root         (0)       62 2023-05-25 08:38:24.000000 image-reward-1.3/ImageReward/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-08 02:03:49.000000 image-reward-1.3/ImageReward/models/
--rw-r--r--   0 root         (0) root         (0)     3167 2023-05-25 08:52:49.000000 image-reward-1.3/ImageReward/models/AestheticScore.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-08 02:03:49.000000 image-reward-1.3/ImageReward/models/BLIP/
--rw-r--r--   0 root         (0) root         (0)       28 2023-05-25 05:25:59.000000 image-reward-1.3/ImageReward/models/BLIP/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3125 2023-05-25 13:23:56.000000 image-reward-1.3/ImageReward/models/BLIP/blip.py
--rw-r--r--   0 root         (0) root         (0)     1502 2023-05-25 05:25:59.000000 image-reward-1.3/ImageReward/models/BLIP/blip_pretrain.py
--rw-r--r--   0 root         (0) root         (0)    41498 2023-05-25 05:25:59.000000 image-reward-1.3/ImageReward/models/BLIP/med.py
--rw-r--r--   0 root         (0) root         (0)    14061 2023-05-25 05:25:59.000000 image-reward-1.3/ImageReward/models/BLIP/vit.py
--rw-r--r--   0 root         (0) root         (0)     3840 2023-05-25 08:53:13.000000 image-reward-1.3/ImageReward/models/BLIPScore.py
--rw-r--r--   0 root         (0) root         (0)     2928 2023-05-25 08:53:34.000000 image-reward-1.3/ImageReward/models/CLIPScore.py
--rw-r--r--   0 root         (0) root         (0)       99 2023-05-25 05:25:59.000000 image-reward-1.3/ImageReward/models/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5923 2023-06-07 13:27:42.000000 image-reward-1.3/ImageReward/utils.py
--rw-r--r--   0 root         (0) root         (0)    11351 2023-05-25 05:25:59.000000 image-reward-1.3/LICENSE
--rw-r--r--   0 root         (0) root         (0)    11883 2023-06-08 02:03:49.000000 image-reward-1.3/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)    11574 2023-06-07 14:30:23.000000 image-reward-1.3/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-08 02:03:49.000000 image-reward-1.3/image_reward.egg-info/
--rw-r--r--   0 root         (0) root         (0)    11883 2023-06-08 02:03:49.000000 image-reward-1.3/image_reward.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      600 2023-06-08 02:03:49.000000 image-reward-1.3/image_reward.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)       46 2023-06-08 02:03:49.000000 image-reward-1.3/image_reward.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      130 2023-06-08 02:03:49.000000 image-reward-1.3/image_reward.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       12 2023-06-08 02:03:49.000000 image-reward-1.3/image_reward.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-08 02:03:49.000000 image-reward-1.3/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1079 2023-06-07 14:30:09.000000 image-reward-1.3/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:55:00.000000 image-reward-1.4/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:55:00.000000 image-reward-1.4/ImageReward/
+-rw-r--r--   0 root         (0) root         (0)     6969 2023-06-28 10:52:22.000000 image-reward-1.4/ImageReward/ImageReward.py
+-rw-r--r--   0 root         (0) root         (0)    36541 2023-06-28 10:52:22.000000 image-reward-1.4/ImageReward/ReFL.py
+-rw-r--r--   0 root         (0) root         (0)       62 2023-06-28 10:52:22.000000 image-reward-1.4/ImageReward/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:55:00.000000 image-reward-1.4/ImageReward/models/
+-rw-r--r--   0 root         (0) root         (0)     3167 2023-06-28 10:52:22.000000 image-reward-1.4/ImageReward/models/AestheticScore.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:55:00.000000 image-reward-1.4/ImageReward/models/BLIP/
+-rw-r--r--   0 root         (0) root         (0)       28 2023-06-28 10:52:22.000000 image-reward-1.4/ImageReward/models/BLIP/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3125 2023-06-28 10:52:22.000000 image-reward-1.4/ImageReward/models/BLIP/blip.py
+-rw-r--r--   0 root         (0) root         (0)     1502 2023-06-28 10:52:22.000000 image-reward-1.4/ImageReward/models/BLIP/blip_pretrain.py
+-rw-r--r--   0 root         (0) root         (0)    41498 2023-06-28 10:52:23.000000 image-reward-1.4/ImageReward/models/BLIP/med.py
+-rw-r--r--   0 root         (0) root         (0)    14061 2023-06-28 10:52:23.000000 image-reward-1.4/ImageReward/models/BLIP/vit.py
+-rw-r--r--   0 root         (0) root         (0)     3840 2023-06-28 10:52:23.000000 image-reward-1.4/ImageReward/models/BLIPScore.py
+-rw-r--r--   0 root         (0) root         (0)     2928 2023-06-28 10:52:23.000000 image-reward-1.4/ImageReward/models/CLIPScore.py
+-rw-r--r--   0 root         (0) root         (0)       99 2023-06-28 10:52:23.000000 image-reward-1.4/ImageReward/models/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5923 2023-06-28 10:52:23.000000 image-reward-1.4/ImageReward/utils.py
+-rw-r--r--   0 root         (0) root         (0)    11351 2023-06-28 10:52:23.000000 image-reward-1.4/LICENSE
+-rw-r--r--   0 root         (0) root         (0)    11974 2023-06-28 10:55:00.000000 image-reward-1.4/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)    11665 2023-06-28 10:52:23.000000 image-reward-1.4/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:55:00.000000 image-reward-1.4/image_reward.egg-info/
+-rw-r--r--   0 root         (0) root         (0)    11974 2023-06-28 10:55:00.000000 image-reward-1.4/image_reward.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      600 2023-06-28 10:55:00.000000 image-reward-1.4/image_reward.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)       46 2023-06-28 10:55:00.000000 image-reward-1.4/image_reward.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      130 2023-06-28 10:55:00.000000 image-reward-1.4/image_reward.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       12 2023-06-28 10:55:00.000000 image-reward-1.4/image_reward.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 10:55:00.000000 image-reward-1.4/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1079 2023-06-28 10:53:55.000000 image-reward-1.4/setup.py
```

### Comparing `image-reward-1.3/ImageReward/ImageReward.py` & `image-reward-1.4/ImageReward/ImageReward.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/ReFL.py` & `image-reward-1.4/ImageReward/ReFL.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/models/AestheticScore.py` & `image-reward-1.4/ImageReward/models/AestheticScore.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/models/BLIP/blip.py` & `image-reward-1.4/ImageReward/models/BLIP/blip.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/models/BLIP/blip_pretrain.py` & `image-reward-1.4/ImageReward/models/BLIP/blip_pretrain.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/models/BLIP/med.py` & `image-reward-1.4/ImageReward/models/BLIP/med.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/models/BLIP/vit.py` & `image-reward-1.4/ImageReward/models/BLIP/vit.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/models/BLIPScore.py` & `image-reward-1.4/ImageReward/models/BLIPScore.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/models/CLIPScore.py` & `image-reward-1.4/ImageReward/models/CLIPScore.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/ImageReward/utils.py` & `image-reward-1.4/ImageReward/utils.py`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/LICENSE` & `image-reward-1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/PKG-INFO` & `image-reward-1.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,23 +1,23 @@
 Metadata-Version: 2.1
 Name: image-reward
-Version: 1.3
+Version: 1.4
 Summary: ImageReward
 Home-page: https://github.com/THUDM/ImageReward
 Author: Jiazheng Xu, et al.
 Author-email: <xjz22@mails.tsinghua.edu.cn>
 License: Apache 2.0 license
 Requires-Python: >=3.5
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # ImageReward
 
 <p align="center">
-   🤗 <a href="https://huggingface.co/THUDM/ImageReward" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/thukeg" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.05977" target="_blank">Paper</a> • 🖼 <a href="https://huggingface.co/datasets/THUDM/ImageRewardDB" target="_blank">Dataset</a> <br>
+   🤗 <a href="https://huggingface.co/THUDM/ImageReward" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/thukeg" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.05977" target="_blank">Paper</a> • 🖼 <a href="https://huggingface.co/datasets/THUDM/ImageRewardDB" target="_blank">Dataset</a> • 🌐 <a href="https://zhuanlan.zhihu.com/p/639494251" target="_blank">中文博客</a> <br>
 </p>
 
 **ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation**
 
 ImageReward is the first general-purpose text-to-image human preference RM, which is trained on in total **137k pairs of expert comparisons**, outperforming existing text-image scoring methods, such as CLIP (by 38.6%), Aesthetic (by 39.6%), and BLIP (by 31.6%), in terms of understanding human preference in text-to-image synthesis.
 
 Additionally, we introduce Reward Feedback Learning (ReFL) for direct optimizing a text-to-image diffusion model using ImageReward. ReFL-tuned Stable Diffusion wins against untuned version by 58.4% in human evaluation.
```

#### html2text {}

```diff
@@ -1,13 +1,14 @@
-Metadata-Version: 2.1 Name: image-reward Version: 1.3 Summary: ImageReward
+Metadata-Version: 2.1 Name: image-reward Version: 1.4 Summary: ImageReward
 Home-page: https://github.com/THUDM/ImageReward Author: Jiazheng Xu, et al.
 Author-email:
 mails.tsinghua.edu.cn> License: Apache 2.0 license Requires-Python: >=3.5
 Description-Content-Type: text/markdown License-File: LICENSE # ImageReward
-        ð¤ HF_Repo â¢ ð¦ Twitter â¢ ð Paper â¢ ð¼ Dataset
+    ð¤ HF_Repo â¢ ð¦ Twitter â¢ ð Paper â¢ ð¼ Dataset â¢ ð
+                                 ä¸­æåå®¢
 **ImageReward: Learning and Evaluating Human Preferences for Text-to-Image
 Generation** ImageReward is the first general-purpose text-to-image human
 preference RM, which is trained on in total **137k pairs of expert
 comparisons**, outperforming existing text-image scoring methods, such as CLIP
 (by 38.6%), Aesthetic (by 39.6%), and BLIP (by 31.6%), in terms of
 understanding human preference in text-to-image synthesis. Additionally, we
 introduce Reward Feedback Learning (ReFL) for direct optimizing a text-to-image
```

### Comparing `image-reward-1.3/README.md` & `image-reward-1.4/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 # ImageReward
 
 <p align="center">
-   🤗 <a href="https://huggingface.co/THUDM/ImageReward" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/thukeg" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.05977" target="_blank">Paper</a> • 🖼 <a href="https://huggingface.co/datasets/THUDM/ImageRewardDB" target="_blank">Dataset</a> <br>
+   🤗 <a href="https://huggingface.co/THUDM/ImageReward" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/thukeg" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.05977" target="_blank">Paper</a> • 🖼 <a href="https://huggingface.co/datasets/THUDM/ImageRewardDB" target="_blank">Dataset</a> • 🌐 <a href="https://zhuanlan.zhihu.com/p/639494251" target="_blank">中文博客</a> <br>
 </p>
 
 **ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation**
 
 ImageReward is the first general-purpose text-to-image human preference RM, which is trained on in total **137k pairs of expert comparisons**, outperforming existing text-image scoring methods, such as CLIP (by 38.6%), Aesthetic (by 39.6%), and BLIP (by 31.6%), in terms of understanding human preference in text-to-image synthesis.
 
 Additionally, we introduce Reward Feedback Learning (ReFL) for direct optimizing a text-to-image diffusion model using ImageReward. ReFL-tuned Stable Diffusion wins against untuned version by 58.4% in human evaluation.
```

#### html2text {}

```diff
@@ -1,9 +1,10 @@
 # ImageReward
-        ð¤ HF_Repo â¢ ð¦ Twitter â¢ ð Paper â¢ ð¼ Dataset
+    ð¤ HF_Repo â¢ ð¦ Twitter â¢ ð Paper â¢ ð¼ Dataset â¢ ð
+                                 ä¸­æåå®¢
 **ImageReward: Learning and Evaluating Human Preferences for Text-to-Image
 Generation** ImageReward is the first general-purpose text-to-image human
 preference RM, which is trained on in total **137k pairs of expert
 comparisons**, outperforming existing text-image scoring methods, such as CLIP
 (by 38.6%), Aesthetic (by 39.6%), and BLIP (by 31.6%), in terms of
 understanding human preference in text-to-image synthesis. Additionally, we
 introduce Reward Feedback Learning (ReFL) for direct optimizing a text-to-image
```

### Comparing `image-reward-1.3/image_reward.egg-info/PKG-INFO` & `image-reward-1.4/image_reward.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,23 +1,23 @@
 Metadata-Version: 2.1
 Name: image-reward
-Version: 1.3
+Version: 1.4
 Summary: ImageReward
 Home-page: https://github.com/THUDM/ImageReward
 Author: Jiazheng Xu, et al.
 Author-email: <xjz22@mails.tsinghua.edu.cn>
 License: Apache 2.0 license
 Requires-Python: >=3.5
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # ImageReward
 
 <p align="center">
-   🤗 <a href="https://huggingface.co/THUDM/ImageReward" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/thukeg" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.05977" target="_blank">Paper</a> • 🖼 <a href="https://huggingface.co/datasets/THUDM/ImageRewardDB" target="_blank">Dataset</a> <br>
+   🤗 <a href="https://huggingface.co/THUDM/ImageReward" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/thukeg" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.05977" target="_blank">Paper</a> • 🖼 <a href="https://huggingface.co/datasets/THUDM/ImageRewardDB" target="_blank">Dataset</a> • 🌐 <a href="https://zhuanlan.zhihu.com/p/639494251" target="_blank">中文博客</a> <br>
 </p>
 
 **ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation**
 
 ImageReward is the first general-purpose text-to-image human preference RM, which is trained on in total **137k pairs of expert comparisons**, outperforming existing text-image scoring methods, such as CLIP (by 38.6%), Aesthetic (by 39.6%), and BLIP (by 31.6%), in terms of understanding human preference in text-to-image synthesis.
 
 Additionally, we introduce Reward Feedback Learning (ReFL) for direct optimizing a text-to-image diffusion model using ImageReward. ReFL-tuned Stable Diffusion wins against untuned version by 58.4% in human evaluation.
```

#### html2text {}

```diff
@@ -1,13 +1,14 @@
-Metadata-Version: 2.1 Name: image-reward Version: 1.3 Summary: ImageReward
+Metadata-Version: 2.1 Name: image-reward Version: 1.4 Summary: ImageReward
 Home-page: https://github.com/THUDM/ImageReward Author: Jiazheng Xu, et al.
 Author-email:
 mails.tsinghua.edu.cn> License: Apache 2.0 license Requires-Python: >=3.5
 Description-Content-Type: text/markdown License-File: LICENSE # ImageReward
-        ð¤ HF_Repo â¢ ð¦ Twitter â¢ ð Paper â¢ ð¼ Dataset
+    ð¤ HF_Repo â¢ ð¦ Twitter â¢ ð Paper â¢ ð¼ Dataset â¢ ð
+                                 ä¸­æåå®¢
 **ImageReward: Learning and Evaluating Human Preferences for Text-to-Image
 Generation** ImageReward is the first general-purpose text-to-image human
 preference RM, which is trained on in total **137k pairs of expert
 comparisons**, outperforming existing text-image scoring methods, such as CLIP
 (by 38.6%), Aesthetic (by 39.6%), and BLIP (by 31.6%), in terms of
 understanding human preference in text-to-image synthesis. Additionally, we
 introduce Reward Feedback Learning (ReFL) for direct optimizing a text-to-image
```

### Comparing `image-reward-1.3/image_reward.egg-info/SOURCES.txt` & `image-reward-1.4/image_reward.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `image-reward-1.3/setup.py` & `image-reward-1.4/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -6,30 +6,30 @@
 long_description = (Path(__file__).parent / "README.md").read_text()
 DESCRIPTION = 'ImageReward'
 
 # 配置
 setup(
         name="image-reward", 
         py_modules = ["ImageReward"],
-        version="1.3",
+        version="1.4",
         author="Jiazheng Xu, et al.",
         author_email="<xjz22@mails.tsinghua.edu.cn>",
         url="https://github.com/THUDM/ImageReward",
         description=DESCRIPTION,
         long_description=long_description,
         long_description_content_type='text/markdown',
         packages=find_packages(exclude=["tests*"]),
         install_requires=[
             'timm==0.6.13',
-            'transformers==4.27.4',
+            'transformers>=4.27.4',
             'fairscale==0.4.13',
-            'huggingface_hub==0.13.4',
-            'diffusers==0.16.0',
-            'accelerate==0.16.0',
-            'datasets==2.11.0',
+            'huggingface_hub>=0.13.4',
+            'diffusers>=0.16.0',
+            'accelerate>=0.16.0',
+            'datasets>=2.11.0',
         ],
         dependency_links = [
             "clip @ git+https://github.com/openai/CLIP.git",
         ],
         python_requires=">=3.5",
         license="Apache 2.0 license"
 )
```

