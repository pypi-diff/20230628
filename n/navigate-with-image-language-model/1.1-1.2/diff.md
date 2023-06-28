# Comparing `tmp/navigate_with_image_language_model-1.1.tar.gz` & `tmp/navigate_with_image_language_model-1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "navigate_with_image_language_model-1.1.tar", last modified: Mon Jun 26 12:17:33 2023, max compression
+gzip compressed data, was "navigate_with_image_language_model-1.2.tar", last modified: Wed Jun 28 15:09:58 2023, max compression
```

## Comparing `navigate_with_image_language_model-1.1.tar` & `navigate_with_image_language_model-1.2.tar`

### file list

```diff
@@ -1,26 +1,26 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 12:17:33.111589 navigate_with_image_language_model-1.1/
--rw-r--r--   0 root         (0) root         (0)      256 2023-06-26 12:17:33.111589 navigate_with_image_language_model-1.1/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       38 2023-04-07 14:02:00.000000 navigate_with_image_language_model-1.1/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 12:17:33.111589 navigate_with_image_language_model-1.1/navigate_with_image_language_model.egg-info/
--rw-r--r--   0 root         (0) root         (0)      256 2023-06-26 12:17:33.000000 navigate_with_image_language_model-1.1/navigate_with_image_language_model.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      611 2023-06-26 12:17:33.000000 navigate_with_image_language_model-1.1/navigate_with_image_language_model.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-26 12:17:33.000000 navigate_with_image_language_model-1.1/navigate_with_image_language_model.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)     1419 2023-06-26 12:17:33.000000 navigate_with_image_language_model-1.1/navigate_with_image_language_model.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       17 2023-06-26 12:17:33.000000 navigate_with_image_language_model-1.1/navigate_with_image_language_model.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 12:17:33.111589 navigate_with_image_language_model-1.1/pipeline/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 12:17:33.111589 navigate_with_image_language_model-1.1/pipeline/clipseg/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/clipseg/__init__.py
--rwxr-xr-x   0 root         (0) root         (0)     9281 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/clipseg/evaluation_utils.py
--rwxr-xr-x   0 root         (0) root         (0)     9288 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/clipseg/general_utils.py
--rwxr-xr-x   0 root         (0) root         (0)    10606 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/clipseg/metrics.py
--rw-r--r--   0 root         (0) root         (0)    16896 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/clipseg/score.py
--rw-r--r--   0 root         (0) root         (0)      787 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/clipseg/setup.py
--rw-r--r--   0 root         (0) root         (0)    10397 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/clipseg/training.py
--rw-r--r--   0 root         (0) root         (0)     3245 2023-06-26 12:08:04.000000 navigate_with_image_language_model-1.1/pipeline/eval.py
--rw-r--r--   0 root         (0) root         (0)    14016 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/models.py
--rw-r--r--   0 root         (0) root         (0)     6236 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/pipeline/utils.py
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-26 12:17:33.111589 navigate_with_image_language_model-1.1/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     2598 2023-06-26 12:17:30.000000 navigate_with_image_language_model-1.1/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 12:17:33.111589 navigate_with_image_language_model-1.1/weights/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.1/weights/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:09:58.336078 navigate_with_image_language_model-1.2/
+-rw-r--r--   0 root         (0) root         (0)      256 2023-06-28 15:09:58.336078 navigate_with_image_language_model-1.2/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     3410 2023-06-28 14:53:41.000000 navigate_with_image_language_model-1.2/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:09:58.336078 navigate_with_image_language_model-1.2/navigate_with_image_language_model.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      256 2023-06-28 15:09:58.000000 navigate_with_image_language_model-1.2/navigate_with_image_language_model.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      611 2023-06-28 15:09:58.000000 navigate_with_image_language_model-1.2/navigate_with_image_language_model.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 15:09:58.000000 navigate_with_image_language_model-1.2/navigate_with_image_language_model.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      178 2023-06-28 15:09:58.000000 navigate_with_image_language_model-1.2/navigate_with_image_language_model.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       17 2023-06-28 15:09:58.000000 navigate_with_image_language_model-1.2/navigate_with_image_language_model.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:09:58.336078 navigate_with_image_language_model-1.2/pipeline/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:09:58.336078 navigate_with_image_language_model-1.2/pipeline/clipseg/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/clipseg/__init__.py
+-rwxr-xr-x   0 root         (0) root         (0)     9281 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/clipseg/evaluation_utils.py
+-rwxr-xr-x   0 root         (0) root         (0)     9288 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/clipseg/general_utils.py
+-rwxr-xr-x   0 root         (0) root         (0)    10606 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/clipseg/metrics.py
+-rw-r--r--   0 root         (0) root         (0)    16896 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/clipseg/score.py
+-rw-r--r--   0 root         (0) root         (0)      787 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/clipseg/setup.py
+-rw-r--r--   0 root         (0) root         (0)    10397 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/clipseg/training.py
+-rw-r--r--   0 root         (0) root         (0)     3242 2023-06-28 15:05:00.000000 navigate_with_image_language_model-1.2/pipeline/eval.py
+-rw-r--r--   0 root         (0) root         (0)    14004 2023-06-28 14:53:41.000000 navigate_with_image_language_model-1.2/pipeline/models.py
+-rw-r--r--   0 root         (0) root         (0)     6236 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/pipeline/utils.py
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 15:09:58.336078 navigate_with_image_language_model-1.2/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      674 2023-06-28 15:09:55.000000 navigate_with_image_language_model-1.2/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:09:58.336078 navigate_with_image_language_model-1.2/weights/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 09:37:35.000000 navigate_with_image_language_model-1.2/weights/__init__.py
```

### Comparing `navigate_with_image_language_model-1.1/navigate_with_image_language_model.egg-info/SOURCES.txt` & `navigate_with_image_language_model-1.2/navigate_with_image_language_model.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `navigate_with_image_language_model-1.1/pipeline/clipseg/evaluation_utils.py` & `navigate_with_image_language_model-1.2/pipeline/clipseg/evaluation_utils.py`

 * *Files identical despite different names*

### Comparing `navigate_with_image_language_model-1.1/pipeline/clipseg/general_utils.py` & `navigate_with_image_language_model-1.2/pipeline/clipseg/general_utils.py`

 * *Files identical despite different names*

### Comparing `navigate_with_image_language_model-1.1/pipeline/clipseg/metrics.py` & `navigate_with_image_language_model-1.2/pipeline/clipseg/metrics.py`

 * *Files identical despite different names*

### Comparing `navigate_with_image_language_model-1.1/pipeline/clipseg/score.py` & `navigate_with_image_language_model-1.2/pipeline/clipseg/score.py`

 * *Files identical despite different names*

### Comparing `navigate_with_image_language_model-1.1/pipeline/clipseg/setup.py` & `navigate_with_image_language_model-1.2/pipeline/clipseg/setup.py`

 * *Files identical despite different names*

### Comparing `navigate_with_image_language_model-1.1/pipeline/clipseg/training.py` & `navigate_with_image_language_model-1.2/pipeline/clipseg/training.py`

 * *Files identical despite different names*

### Comparing `navigate_with_image_language_model-1.1/pipeline/eval.py` & `navigate_with_image_language_model-1.2/pipeline/eval.py`

 * *Files 4% similar despite different names*

```diff
@@ -11,15 +11,15 @@
             word_mask='A bright photo of a path through the forest',
             sd_prompt='A bright picture of a narrow footpath',
             obstacle_prompt='A dull photo of bulky or voluminous obstacles that are bigger than 50 centimeters'
         )
 
         files = pipeline.loadData()
         if visualize:
-            images_dir = '../output'
+            images_dir = '/output'
             if not os.path.exists(images_dir):
                 os.makedirs(images_dir)
             else:
                 print("The folder already exists.")
         GT_dir = '../data/GT/GT_hike'
         masks = []
 
@@ -45,15 +45,15 @@
             word_mask='A bright photo of a road to walk on',
             positive_samples=9,
             negative_samples=11
         )
         """ computes and saves metrics for whole dataset """
         files = pipeline.loadData()
         if visualize:
-            images_dir = '../output'
+            images_dir = '/output'
             if not os.path.exists(images_dir):
                 os.makedirs(images_dir)
             else:
                 print("The folder already exists.")
         GT_dir = '../data/GT/GT_hike'
         sam_masks = []
         for file in tqdm(files):
@@ -80,13 +80,13 @@
         print("metric: ", metric)
         # save metric to text file
         with open('metrics.txt', 'a') as f:
             f.write(f"SAM: {metric}\n")
         
 
 if __name__ == '__main__':
-    main('sd', visualize=True)
+    main('sam', visualize=True)
```

### Comparing `navigate_with_image_language_model-1.1/pipeline/models.py` & `navigate_with_image_language_model-1.2/pipeline/models.py`

 * *Files 1% similar despite different names*

```diff
@@ -202,15 +202,15 @@
     Pipeline for a prompting SAM with text prompts
     - Use prompt to segment image using clipseg
     - sample pixel locations from the clipseg mask and pass them to segment anything
     """
 
     def __init__(self, data_path: str, word_mask: str, positive_samples : int, negative_samples : int) -> None:
         super().__init__(data_path, word_mask)
-        sam = sam_model_registry["vit_h"](checkpoint='../checkpoints/sam_vit_h_4b8939.pth').to(self.device)
+        sam = sam_model_registry["vit_h"](checkpoint='../sam_vit_h_4b8939.pth').to(self.device)
         self.sam = SamPredictor(sam)
         self.num_positive_points = positive_samples
         self.num_negative_points = negative_samples
     
     def __call__(self, file, multimask_output, mask_input):
         image = Image.open(os.path.join(self.data_path,file))
```

### Comparing `navigate_with_image_language_model-1.1/pipeline/utils.py` & `navigate_with_image_language_model-1.2/pipeline/utils.py`

 * *Files identical despite different names*

