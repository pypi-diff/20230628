# Comparing `tmp/py_tgb-0.1.2.tar.gz` & `tmp/py_tgb-0.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "py_tgb-0.1.2.tar", max compression
+gzip compressed data, was "py_tgb-0.6.0.tar", max compression
```

## Comparing `py_tgb-0.1.2.tar` & `py_tgb-0.6.0.tar`

### file list

```diff
@@ -1,32 +1,30 @@
--rw-r--r--   0        0        0     2218 2023-06-14 13:49:29.647098 py_tgb-0.1.2/README.md
--rw-r--r--   0        0        0      748 2023-06-14 13:49:29.647098 py_tgb-0.1.2/pyproject.toml
--rw-r--r--   0        0        0      177 2023-06-14 13:49:29.647098 py_tgb-0.1.2/tgb/datasets/MAG/mag.py
--rw-r--r--   0        0        0      820 2023-06-14 13:49:29.647098 py_tgb-0.1.2/tgb/datasets/MAG/old/plot_stats.py
--rw-r--r--   0        0        0     4777 2023-06-14 13:49:29.647098 py_tgb-0.1.2/tgb/datasets/amazonreview/amazonreview.py
--rw-r--r--   0        0        0     2499 2023-06-14 13:49:29.647098 py_tgb-0.1.2/tgb/datasets/amazonreview/amazonreview_neg_generator.py
--rw-r--r--   0        0        0     7781 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/flight_raw/opensky.py
--rw-r--r--   0        0        0    19780 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/lastfmgenre/lastfm.py
--rw-r--r--   0        0        0     2518 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/opensky/opensky_neg_generator.py
--rw-r--r--   0        0        0     6912 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/redditcomments/redditcomments.py
--rw-r--r--   0        0        0     2501 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/redditcomments/redditcomments_neg_generator.py
--rw-r--r--   0        0        0     4740 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/stablecoin/stablecoin.py
--rw-r--r--   0        0        0     2497 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/stablecoin/stablecoin_neg_generator.py
--rw-r--r--   0        0        0    11859 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/subreddits/subreddits.py
--rw-r--r--   0        0        0     5927 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/datasets/un_trade/un_trade.py
--rw-r--r--   0        0        0    14106 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/edgeregression/dataset.py
--rw-r--r--   0        0        0     3992 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/edgeregression/dataset_pyg.py
--rw-r--r--   0        0        0     5087 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/edgeregression/evaluate.py
--rw-r--r--   0        0        0    13856 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/linkproppred/dataset.py
--rw-r--r--   0        0        0     7293 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/linkproppred/dataset_pyg.py
--rw-r--r--   0        0        0     4664 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/linkproppred/evaluate.py
--rw-r--r--   0        0        0    10770 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/linkproppred/negative_generator.py
--rw-r--r--   0        0        0     3903 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/linkproppred/negative_sampler.py
--rw-r--r--   0        0        0    16249 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/nodeproppred/dataset.py
--rw-r--r--   0        0        0     7205 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/nodeproppred/dataset_pyg.py
--rw-r--r--   0        0        0     5334 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/nodeproppred/evaluate.py
--rw-r--r--   0        0        0     8689 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/utils/dataset_stats.py
--rw-r--r--   0        0        0     1683 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/utils/info.py
--rw-r--r--   0        0        0    27787 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/utils/pre_process.py
--rw-r--r--   0        0        0     2970 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/utils/stats.py
--rw-r--r--   0        0        0     2974 2023-06-14 13:49:29.651098 py_tgb-0.1.2/tgb/utils/utils.py
--rw-r--r--   0        0        0     2902 1970-01-01 00:00:00.000000 py_tgb-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0     2404 2023-06-28 16:06:29.349452 py_tgb-0.6.0/README.md
+-rw-r--r--   0        0        0      748 2023-06-28 16:06:29.349452 py_tgb-0.6.0/pyproject.toml
+-rw-r--r--   0        0        0      177 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/MAG/mag.py
+-rw-r--r--   0        0        0      820 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/MAG/old/plot_stats.py
+-rw-r--r--   0        0        0     4740 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-coin.py
+-rw-r--r--   0        0        0     2497 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-coin_neg_generator.py
+-rw-r--r--   0        0        0     6912 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-comment.py
+-rw-r--r--   0        0        0     2499 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-comment_neg_generator.py
+-rw-r--r--   0        0        0     7781 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-flight.py
+-rw-r--r--   0        0        0     2499 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-flight_neg_generator.py
+-rw-r--r--   0        0        0     4777 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-review.py
+-rw-r--r--   0        0        0     2498 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-review_neg_generator.py
+-rw-r--r--   0        0        0     2543 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-wiki_neg_generator.py
+-rw-r--r--   0        0        0    19780 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbn-genre.py
+-rw-r--r--   0        0        0    11859 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbn-reddit.py
+-rw-r--r--   0        0        0     5927 2023-06-28 16:06:29.349452 py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbn-trade.py
+-rw-r--r--   0        0        0    13839 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/linkproppred/dataset.py
+-rw-r--r--   0        0        0     7532 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/linkproppred/dataset_pyg.py
+-rw-r--r--   0        0        0     5869 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/linkproppred/evaluate.py
+-rw-r--r--   0        0        0    14146 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/linkproppred/negative_generator.py
+-rw-r--r--   0        0        0     5123 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/linkproppred/negative_sampler.py
+-rw-r--r--   0        0        0    16181 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/nodeproppred/dataset.py
+-rw-r--r--   0        0        0     7205 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/nodeproppred/dataset_pyg.py
+-rw-r--r--   0        0        0     5336 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/nodeproppred/evaluate.py
+-rw-r--r--   0        0        0     8691 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/utils/dataset_stats.py
+-rw-r--r--   0        0        0     1725 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/utils/info.py
+-rw-r--r--   0        0        0    27787 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/utils/pre_process.py
+-rw-r--r--   0        0        0     2747 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/utils/stats.py
+-rw-r--r--   0        0        0     2974 2023-06-28 16:06:29.353452 py_tgb-0.6.0/tgb/utils/utils.py
+-rw-r--r--   0        0        0     3088 1970-01-01 00:00:00.000000 py_tgb-0.6.0/PKG-INFO
```

### Comparing `py_tgb-0.1.2/README.md` & `py_tgb-0.6.0/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -1,18 +1,22 @@
 # TGB
-Temporal Graph Benchmark project repo 
+Temporal Graph Benchmark for Machine Learning on Temporal Graphs 
 
 ### Pypi Install
 
 You can install TGB via [pip](https://pypi.org/project/py-tgb/)
 ```
 pip install py-tgb
 ```
 
-### Dataset Download
+### Links and Datasets
+
+The project website can be found [here](https://tgb-website.pages.dev/).
+
+The API documentations can be found [here](https://shenyanghuang.github.io/TGB/).
 
 all dataset download links can be found at [info.py](https://github.com/shenyangHuang/TGB/blob/main/tgb/utils/info.py)
 
 TGB dataloader will also automatically download the dataset
 
 ### Install dependency
 Our implementation works with python >= 3.9 and can be installed as follows
```

### Comparing `py_tgb-0.1.2/pyproject.toml` & `py_tgb-0.6.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "py-tgb"
-version = "0.1.2"
+version = "0.6.0"
 description = "Temporal Graph Benchmark project repo"
 authors = ["shenyang Huang <shenyang.huang@mail.mcgill.ca>", "Farimah Poursafaei", "Emanuele Rossi <emanuele.rossi1909@gmail.com>", "Jacob Danovitch <jacob.danovitch@mila.quebec>"]
 readme = "README.md"
 packages = [{include = "tgb"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
```

### Comparing `py_tgb-0.1.2/tgb/datasets/MAG/old/plot_stats.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/MAG/old/plot_stats.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/datasets/amazonreview/amazonreview.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-review.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/datasets/amazonreview/amazonreview_neg_generator.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-comment_neg_generator.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 
     # setting the required parameters
     num_neg_e_per_pos = 20 #100
     neg_sample_strategy = "hist_rnd" #"rnd"
     rnd_seed = 42
 
 
-    name = "amazonreview"
+    name = "tgbl-comment"
     dataset = PyGLinkPropPredDataset(name=name, root="datasets")
     train_mask = dataset.train_mask
     val_mask = dataset.val_mask
     test_mask = dataset.test_mask
     data = dataset.get_TemporalData()
 
     data_splits = {}
```

### Comparing `py_tgb-0.1.2/tgb/datasets/flight_raw/opensky.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-flight.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/datasets/lastfmgenre/lastfm.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbn-genre.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/datasets/opensky/opensky_neg_generator.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-review_neg_generator.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,16 +14,15 @@
 
     # setting the required parameters
     num_neg_e_per_pos = 20 #100
     neg_sample_strategy = "hist_rnd" #"rnd"
     rnd_seed = 42
 
 
-    # === OpenSky ===
-    name = "opensky"
+    name = "tgbl-review"
     dataset = PyGLinkPropPredDataset(name=name, root="datasets")
     train_mask = dataset.train_mask
     val_mask = dataset.val_mask
     test_mask = dataset.test_mask
     data = dataset.get_TemporalData()
 
     data_splits = {}
@@ -47,15 +46,15 @@
         num_neg_e=num_neg_e_per_pos,
         strategy=neg_sample_strategy,
         rnd_seed=rnd_seed,
         historical_data=historical_data,
     )
 
     # generate evaluation set
-    partial_path = "./"
+    partial_path = "."
     # generate validation negative edge set
     start_time = time.time()
     split_mode = "val"
     print(
         f"INFO: Start generating negative samples: {split_mode} --- {neg_sample_strategy}"
     )
     neg_sampler.generate_negative_samples(
```

### Comparing `py_tgb-0.1.2/tgb/datasets/redditcomments/redditcomments.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-comment.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/datasets/redditcomments/redditcomments_neg_generator.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-coin_neg_generator.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 
     # setting the required parameters
     num_neg_e_per_pos = 20 #100
     neg_sample_strategy = "hist_rnd" #"rnd"
     rnd_seed = 42
 
 
-    name = "redditcomments"
+    name = "stablecoin"
     dataset = PyGLinkPropPredDataset(name=name, root="datasets")
     train_mask = dataset.train_mask
     val_mask = dataset.val_mask
     test_mask = dataset.test_mask
     data = dataset.get_TemporalData()
 
     data_splits = {}
```

### Comparing `py_tgb-0.1.2/tgb/datasets/stablecoin/stablecoin.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-coin.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/datasets/stablecoin/stablecoin_neg_generator.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbl-flight_neg_generator.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 
     # setting the required parameters
     num_neg_e_per_pos = 20 #100
     neg_sample_strategy = "hist_rnd" #"rnd"
     rnd_seed = 42
 
 
-    name = "stablecoin"
+    name = "tgbl-flight"
     dataset = PyGLinkPropPredDataset(name=name, root="datasets")
     train_mask = dataset.train_mask
     val_mask = dataset.val_mask
     test_mask = dataset.test_mask
     data = dataset.get_TemporalData()
 
     data_splits = {}
@@ -46,15 +46,15 @@
         num_neg_e=num_neg_e_per_pos,
         strategy=neg_sample_strategy,
         rnd_seed=rnd_seed,
         historical_data=historical_data,
     )
 
     # generate evaluation set
-    partial_path = "."
+    partial_path = "./"
     # generate validation negative edge set
     start_time = time.time()
     split_mode = "val"
     print(
         f"INFO: Start generating negative samples: {split_mode} --- {neg_sample_strategy}"
     )
     neg_sampler.generate_negative_samples(
```

### Comparing `py_tgb-0.1.2/tgb/datasets/subreddits/subreddits.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbn-reddit.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/datasets/un_trade/un_trade.py` & `py_tgb-0.6.0/tgb/datasets/dataset_scripts/tgbn-trade.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/edgeregression/dataset.py` & `py_tgb-0.6.0/tgb/linkproppred/dataset.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,73 +1,37 @@
 from typing import Optional, Dict, Any, Tuple
 import os
 import os.path as osp
 import numpy as np
 import pandas as pd
-import shutil
 import zipfile
 import requests
 from clint.textui import progress
 
-from tgb.utils.info import PROJ_DIR, DATA_URL_DICT, BColors
-from tgb.utils.pre_process import _to_pd_data, reindex
+from tgb.linkproppred.negative_sampler import NegativeEdgeSampler
+from tgb.utils.info import PROJ_DIR, DATA_URL_DICT, DATA_EVAL_METRIC_DICT, BColors
+from tgb.utils.pre_process import (
+    csv_to_pd_data,
+    process_node_feat,
+    csv_to_pd_data_sc,
+    csv_to_pd_data_rc,
+    load_edgelist_wiki,
+)
+from tgb.utils.utils import save_pkl, load_pkl
 
 
-def gen_src_ts_sum_weight(
-    edgelist_df: pd.DataFrame,
-    src_col_name: str = "u",
-    ts_col_name: str = "ts",
-    w_col_name: str = "w",
-) -> Dict[Tuple[int, int], float]:
-    """
-    generates a dictionary where the keys are (src, ts) and
-    the values are the sum of all edge weights at that timestamp with the same source node
-    """
-    src_ts_sum_w = {}
-    for idx, row in edgelist_df.iterrows():
-        if (row[src_col_name], row[ts_col_name]) not in src_ts_sum_w:
-            src_ts_sum_w[(row[src_col_name], row[ts_col_name])] = row[w_col_name]
-        else:
-            src_ts_sum_w[(row[src_col_name], row[ts_col_name])] += row[w_col_name]
-
-    return src_ts_sum_w
-
-
-def normalize_weight_wtd(
-    edgelist_df: pd.DataFrame,
-    src_ts_sum_w: Dict[Tuple[int, int], float],
-    src_col_name: str = "u",
-    ts_col_name: str = "ts",
-    w_col_name: str = "w",
-) -> pd.DataFrame:
-    """
-    Normalize the edge weights by the weighted temporal degrees
-    """
-    normal_weights = []
-    for idx, row in edgelist_df.iterrows():
-        sum_weight = src_ts_sum_w[(row[src_col_name], row[ts_col_name])]
-        if sum_weight != 0:
-            normal_weights.append(row[w_col_name] / sum_weight)
-        else:
-            normal_weights.append(0)
-
-    edgelist_df[w_col_name] = normal_weights
-
-    return edgelist_df
-
-
-class EdgeRegressionDataset(object):
+class LinkPropPredDataset(object):
     def __init__(
         self,
         name: str,
         root: Optional[str] = "datasets",
         meta_dict: Optional[dict] = None,
         preprocess: Optional[bool] = True,
     ):
-        r"""Dataset class for edge regression tasks. Stores meta information about each dataset such as evaluation metrics etc.
+        r"""Dataset class for link prediction dataset. Stores meta information about each dataset such as evaluation metrics etc.
         also automatically pre-processes the dataset.
         Args:
             name: name of the dataset
             root: root directory to store the dataset folder
             meta_dict: dictionary containing meta information about the dataset, should contain key 'dir_name' which is the name of the dataset folder
             preprocess: whether to pre-process the dataset
         """
@@ -75,46 +39,65 @@
         # check if dataset url exist
         if self.name in DATA_URL_DICT:
             self.url = DATA_URL_DICT[self.name]
         else:
             self.url = None
             print(f"Dataset {self.name} url not found, download not supported yet.")
 
+        
+        # check if the evaluatioin metric are specified
+        if self.name in DATA_EVAL_METRIC_DICT:
+            self.metric = DATA_EVAL_METRIC_DICT[self.name]
+        else:
+            self.metric = None
+            print(
+                f"Dataset {self.name} default evaluation metric not found, it is not supported yet."
+            )
+
+
         root = PROJ_DIR + root
 
         if meta_dict is None:
             self.dir_name = "_".join(name.split("-"))  ## replace hyphen with underline
             meta_dict = {"dir_name": self.dir_name}
         else:
             self.dir_name = meta_dict["dir_name"]
         self.root = osp.join(root, self.dir_name)
         self.meta_dict = meta_dict
         if "fname" not in self.meta_dict:
-            self.meta_dict["fname"] = self.root + "/" + self.name + ".csv"
+            self.meta_dict["fname"] = self.root + "/" + self.name + "_edgelist.csv"
+            self.meta_dict["nodefile"] = None
+
+        # TODO update the logic here to load the filenames from info.py
+        if name == "tgbl-flight":
+            self.meta_dict["nodefile"] = self.root + "/" + "airport_node_feat.csv"
 
         # initialize
         self._node_feat = None
         self._edge_feat = None
         self._full_data = None
         self._train_data = None
         self._val_data = None
         self._test_data = None
 
-        # TODO Andy: add url logic here from info.py to manage the urls in a centralized file
         self.download()
         # check if the root directory exists, if not create it
         if osp.isdir(self.root):
             print("Dataset directory is ", self.root)
         else:
             # os.makedirs(self.root)
             raise FileNotFoundError(f"Directory not found at {self.root}")
 
         if preprocess:
             self.pre_process()
 
+        self.ns_sampler = NegativeEdgeSampler(
+            dataset_name=self.name, strategy="hist_rnd"
+        )
+
     def download(self):
         """
         downloads this dataset from url
         check if files are already downloaded
         """
         # check if the file already exists
         if osp.exists(self.meta_dict["fname"]):
@@ -156,108 +139,103 @@
                     zip_ref.extractall(self.root)
                 print(f"{BColors.OKGREEN}Download completed {BColors.ENDC}")
         else:
             raise Exception(
                 BColors.FAIL + "Data not found error, download " + self.name + " failed"
             )
 
-    def output_ml_files(self):
-        r"""Turns raw data .csv file into TG learning ready format such as for TGN, stores the processed file locally for faster access later
-        'ml_<network>.csv': source, destination, timestamp, state_label, index 	# 'index' is the index of the line in the edgelist
-        'ml_<network>.npy': contains the edge features; this is a numpy array where each element corresponds to the features of the corresponding line specifying one edge. If there are no features, should be initialized by zeros
-        'ml_<network>_node.npy': contains the node features; this is a numpy array that each element specify the features of one node where the node-id is equal to the element index.
-        """
-        # check if path to file is valid
-        if not osp.exists(self.meta_dict["fname"]):
-            raise FileNotFoundError(f"File not found at {self.meta_dict['fname']}")
-
-        # output file names
-        OUT_DF = self.root + "/" + "ml_{}.csv".format(self.name)
-        OUT_FEAT = self.root + "/" + "ml_{}.npy".format(self.name)
-        OUT_NODE_FEAT = self.root + "/" + "ml_{}_node.npy".format(self.name)
-
-        # check if the output files already exist, if so, skip the pre-processing
-        if osp.exists(OUT_DF) and osp.exists(OUT_FEAT) and osp.exists(OUT_NODE_FEAT):
-            print("pre-processed files found, skipping file generation")
-            return df
-        else:
-            df, feat = _to_pd_data(self.meta_dict["fname"])
-            df = reindex(df, bipartite=False)
-            empty = np.zeros(feat.shape[1])[np.newaxis, :]
-            feat = np.vstack([empty, feat])
-
-            max_idx = max(df.u.max(), df.i.max())
-            rand_feat = np.zeros((max_idx + 1, 172))
-
-            df.to_csv(OUT_DF)
-            np.save(OUT_FEAT, feat)
-            np.save(OUT_NODE_FEAT, rand_feat)
-
-    def generate_processed_files(self, fname: str) -> pd.DataFrame:
+    def generate_processed_files(self) -> pd.DataFrame:
         r"""
         turns raw data .csv file into a pandas data frame, stored on disc if not already
-        Parameters:
-            fname: path to raw data file
         Returns:
             df: pandas data frame
         """
-        if not osp.exists(fname):
-            raise FileNotFoundError(f"File not found at {fname}")
+        node_feat = None
+        if not osp.exists(self.meta_dict["fname"]):
+            raise FileNotFoundError(f"File not found at {self.meta_dict['fname']}")
+
+        if self.meta_dict["nodefile"] is not None:
+            if not osp.exists(self.meta_dict["nodefile"]):
+                raise FileNotFoundError(
+                    f"File not found at {self.meta_dict['nodefile']}"
+                )
         OUT_DF = self.root + "/" + "ml_{}.pkl".format(self.name)
+        OUT_EDGE_FEAT = self.root + "/" + "ml_{}.pkl".format(self.name + "_edge")
+        if self.meta_dict["nodefile"] is not None:
+            OUT_NODE_FEAT = self.root + "/" + "ml_{}.pkl".format(self.name + "_node")
 
         if osp.exists(OUT_DF):
             print("loading processed file")
             df = pd.read_pickle(OUT_DF)
-            # df = pd.read_csv(OUT_DF)
+            edge_feat = load_pkl(OUT_EDGE_FEAT)
+            if self.meta_dict["nodefile"] is not None:
+                node_feat = load_pkl(OUT_NODE_FEAT)
+
         else:
-            # TODO Andy write better panda dataloading code, currently the feat is empty
             print("file not processed, generating processed file")
-            df, feat = _to_pd_data(fname)
-            df = reindex(df, bipartite=False)
-            src_ts_sum_w = gen_src_ts_sum_weight(df)
-            df = normalize_weight_wtd(df, src_ts_sum_w)
+            if self.name == "tgbl-flight":
+                df, edge_feat, node_ids = csv_to_pd_data(self.meta_dict["fname"])
+            elif self.name == "tgbl-coin":
+                df, edge_feat, node_ids = csv_to_pd_data_sc(self.meta_dict["fname"])
+            elif self.name == "tgbl-comment":
+                df, edge_feat, node_ids = csv_to_pd_data_rc(self.meta_dict["fname"])
+            elif self.name == "tgbl-review":
+                df, edge_feat, node_ids = csv_to_pd_data_sc(self.meta_dict["fname"])
+            elif self.name == "tgbl-wiki":
+                df, edge_feat, node_ids = load_edgelist_wiki(self.meta_dict["fname"])
+
+            save_pkl(edge_feat, OUT_EDGE_FEAT)
             df.to_pickle(OUT_DF)
-            # df.to_csv(OUT_DF)
-        return df
+            if self.meta_dict["nodefile"] is not None:
+                node_feat = process_node_feat(self.meta_dict["nodefile"], node_ids)
+                save_pkl(node_feat, OUT_NODE_FEAT)
 
-    def pre_process(self, feat_dim=172):
+        return df, edge_feat, node_feat
+
+    def pre_process(self):
         """
         Pre-process the dataset and generates the splits, must be run before dataset properties can be accessed
-        generates self.full_data, self.train_data, self.val_data, self.test_data
-        Parameters:
-            feat_dim: dimension for feature vectors, padded to 172 with zeros
+        generates the edge data and different train, val, test splits
         """
+        # TODO for link prediction, y =1 because these are all true edges, edge feat = weight + edge feat
+
         # check if path to file is valid
-        df = self.generate_processed_files(self.meta_dict["fname"])
-        self._node_feat = np.zeros((df.shape[0], feat_dim))
-        self._edge_feat = np.zeros((df.shape[0], feat_dim))
+        df, edge_feat, node_feat = self.generate_processed_files()
         sources = np.array(df["u"])
         destinations = np.array(df["i"])
         timestamps = np.array(df["ts"])
         edge_idxs = np.array(df["idx"])
-        y = np.array(df["w"])
+        weights = np.array(df["w"])
+
+        edge_label = np.ones(len(df))  # should be 1 for all pos edges
+        self._edge_feat = edge_feat + weights.reshape(
+            -1, 1
+        )  # reshape weights as feature if available
+        self._node_feat = node_feat
 
         full_data = {
             "sources": sources,
             "destinations": destinations,
             "timestamps": timestamps,
             "edge_idxs": edge_idxs,
-            "y": y,
+            "edge_feat": edge_feat,
+            "w": weights,
+            "edge_label": edge_label,
         }
         self._full_data = full_data
         _train_mask, _val_mask, _test_mask = self.generate_splits(full_data)
         self._train_mask = _train_mask
         self._val_mask = _val_mask
         self._test_mask = _test_mask
 
     def generate_splits(
         self,
         full_data: Dict[str, Any],
-        val_ratio=0.15,
-        test_ratio=0.15,
+        val_ratio: float = 0.15,
+        test_ratio: float = 0.15,
     ) -> Tuple[Dict[str, Any], Dict[str, Any], Dict[str, Any]]:
         r"""Generates train, validation, and test splits from the full dataset
         Args:
             full_data: dictionary containing the full dataset
             val_ratio: ratio of validation data
             test_ratio: ratio of test data
         Returns:
@@ -268,24 +246,54 @@
         val_time, test_time = list(
             np.quantile(
                 full_data["timestamps"],
                 [(1 - val_ratio - test_ratio), (1 - test_ratio)],
             )
         )
         timestamps = full_data["timestamps"]
-        sources = full_data["sources"]
-        destinations = full_data["destinations"]
-        edge_idxs = full_data["edge_idxs"]
-        y = full_data["y"]
 
         train_mask = timestamps <= val_time
         val_mask = np.logical_and(timestamps <= test_time, timestamps > val_time)
         test_mask = timestamps > test_time
 
         return train_mask, val_mask, test_mask
+    
+    @property
+    def eval_metric(self) -> str:
+        """
+        the official evaluation metric for the dataset, loaded from info.py
+        Returns:
+            eval_metric: str, the evaluation metric
+        """
+        return self.metric
+
+    @property
+    def negative_sampler(self) -> NegativeEdgeSampler:
+        r"""
+        Returns the negative sampler of the dataset, will load negative samples from disc
+        Returns:
+            negative_sampler: NegativeEdgeSampler
+        """
+        return self.ns_sampler
+
+    def load_val_ns(self) -> None:
+        r"""
+        load the negative samples for the validation set
+        """
+        self.ns_sampler.load_eval_set(
+            fname=self.root + "/" + self.name + "_val_ns.pkl", split_mode="val"
+        )
+
+    def load_test_ns(self) -> None:
+        r"""
+        load the negative samples for the test set
+        """
+        self.ns_sampler.load_eval_set(
+            fname=self.root + "/" + self.name + "_test_ns.pkl", split_mode="test"
+        )
 
     @property
     def node_feat(self) -> Optional[np.ndarray]:
         r"""
         Returns the node features of the dataset with dim [N, feat_dim]
         Returns:
             node_feat: np.ndarray, [N, feat_dim] or None if there is no node feature
@@ -300,73 +308,68 @@
             edge_feat: np.ndarray, [E, feat_dim] or None if there is no edge feature
         """
         return self._edge_feat
 
     @property
     def full_data(self) -> Dict[str, Any]:
         r"""
-        Returns the full data of the dataset as a dictionary with keys:
-            sources, destinations, timestamps, edge_idxs, y (edge weight)
+        the full data of the dataset as a dictionary with keys: 'sources', 'destinations', 'timestamps', 'edge_idxs', 'edge_feat', 'w', 'edge_label',
+
         Returns:
             full_data: Dict[str, Any]
         """
         if self._full_data is None:
             raise ValueError(
                 "dataset has not been processed yet, please call pre_process() first"
             )
         return self._full_data
 
     @property
-    def train_mask(self) -> Dict[str, Any]:
+    def train_mask(self) -> np.ndarray:
         r"""
         Returns the train mask of the dataset
         Returns:
-            train_mask: Dict[str, Any]
+            train_mask: training masks
         """
         if self._train_mask is None:
             raise ValueError("training split hasn't been loaded")
         return self._train_mask
 
     @property
-    def val_mask(self) -> Dict[str, Any]:
+    def val_mask(self) -> np.ndarray:
         r"""
         Returns the validation mask of the dataset
         Returns:
             val_mask: Dict[str, Any]
         """
         if self._val_mask is None:
             raise ValueError("validation split hasn't been loaded")
-
         return self._val_mask
 
     @property
-    def test_mask(self) -> Dict[str, Any]:
+    def test_mask(self) -> np.ndarray:
         r"""
         Returns the test mask of the dataset:
         Returns:
             test_mask: Dict[str, Any]
         """
         if self._test_mask is None:
             raise ValueError("test split hasn't been loaded")
-
         return self._test_mask
 
 
 def main():
-    dataset = EdgeRegressionDataset(name="un_trade", root="datasets", preprocess=True)
+    name = "tgbl-comment" 
+    dataset = LinkPropPredDataset(name=name, root="datasets", preprocess=True)
 
     dataset.node_feat
     dataset.edge_feat  # not the edge weights
     dataset.full_data
     dataset.full_data["edge_idxs"]
     dataset.full_data["sources"]
     dataset.full_data["destinations"]
     dataset.full_data["timestamps"]
-    dataset.full_data["y"]
-
-    train_data = dataset.full_data[dataset.train_mask]
-    val_data = dataset.full_data[dataset.val_mask]
-    test_data = dataset.full_data[dataset.test_mask]
+    dataset.full_data["edge_label"]
 
 
 if __name__ == "__main__":
     main()
```

### Comparing `py_tgb-0.1.2/tgb/edgeregression/evaluate.py` & `py_tgb-0.6.0/tgb/nodeproppred/evaluate.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,31 @@
 import numpy as np
 from sklearn.metrics import mean_squared_error
+from sklearn.metrics import ndcg_score
 import math
 
+from tgb.utils.info import DATA_EVAL_METRIC_DICT
 
 try:
     import torch
 except ImportError:
     torch = None
 
 
 class Evaluator(object):
-    """Evaluator for Edge Regression Task"""
+    """Evaluator for Node Property Prediction"""
 
     def __init__(self, name: str):
         r"""
         Parameters:
             name: name of the dataset
         """
         self.name = name
-        self.valid_metric_list = ["mse", "rmse"]
-        if self.name not in ["un_trade"]:
+        self.valid_metric_list = ["mse", "rmse", "ndcg"]
+        if self.name not in DATA_EVAL_METRIC_DICT:
             raise NotImplementedError("Dataset not supported")
 
     def _parse_and_check_input(self, input_dict):
         """
         check whether the input has the required format
         Parametrers:
             -input_dict: a dictionary containing "y_true", "y_pred", and "eval_metric"
@@ -81,14 +83,17 @@
         perf_dict = {}
         for eval_metric in self.eval_metric:
             if eval_metric == "mse":
                 perf_dict = {
                     "mse": mean_squared_error(y_true, y_pred),
                     "rmse": math.sqrt(mean_squared_error(y_true, y_pred)),
                 }
+            elif eval_metric == "ndcg":
+                k = 10
+                perf_dict = {"ndcg": ndcg_score(y_true, y_pred, k=k)}
         return perf_dict
 
     def eval(self, input_dict, verbose=False):
         """
         evaluation for edge regression task
         """
         y_true, y_pred = self._parse_and_check_input(input_dict)
@@ -122,15 +127,15 @@
         return desc
 
 
 def main():
     """
     simple test for evaluator
     """
-    name = "un_trade"
+    name = "tgbn-trade"
     evaluator = Evaluator(name=name)
     print(evaluator.expected_input_format)
     print(evaluator.expected_output_format)
     input_dict = {"y_true": y_true, "y_pred": y_pred, "eval_metric": ["mse"]}
 
     result_dict = evaluator.eval(input_dict)
     print(result_dict)
```

### Comparing `py_tgb-0.1.2/tgb/linkproppred/dataset_pyg.py` & `py_tgb-0.6.0/tgb/nodeproppred/dataset_pyg.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,82 +1,69 @@
+import os.path as osp
+from typing import Optional, Dict, Any, Optional, Callable
+
+
 import torch
-from typing import Optional, Optional, Callable
 
-from torch_geometric.data import Dataset, TemporalData
-from tgb.linkproppred.dataset import LinkPropPredDataset
-from tgb.linkproppred.negative_sampler import NegativeEdgeSampler
+from torch_geometric.data import InMemoryDataset, TemporalData, download_url
+from tgb.nodeproppred.dataset import NodePropPredDataset
 import warnings
 
 
-class PyGLinkPropPredDataset(Dataset):
+# TODO check https://pytorch-geometric.readthedocs.io/en/latest/_modules/torch_geometric/data/in_memory_dataset.html
+# avoid any overlapping properties
+class PyGNodePropPredDataset(InMemoryDataset):
+    r"""
+    PyG wrapper for the NodePropPredDataset
+    can return pytorch tensors for src,dst,t,msg,label
+    can return Temporal Data object
+    also query the node labels corresponding to a timestamp from edge batch
+    Parameters:
+        name: name of the dataset, passed to `NodePropPredDataset`
+        root (string): Root directory where the dataset should be saved.
+        transform (callable, optional): A function/transform that takes in an
+        pre_transform (callable, optional): A function/transform that takes in
+    """
+
     def __init__(
         self,
         name: str,
         root: str,
         transform: Optional[Callable] = None,
         pre_transform: Optional[Callable] = None,
     ):
-        r"""
-        PyG wrapper for the LinkPropPredDataset
-        can return pytorch tensors for src,dst,t,msg,label
-        can return Temporal Data object
-        Parameters:
-            name: name of the dataset, passed to `LinkPropPredDataset`
-            root (string): Root directory where the dataset should be saved, passed to `LinkPropPredDataset`
-            transform (callable, optional): A function/transform that takes in an, not used in this case
-            pre_transform (callable, optional): A function/transform that takes in, not used in this case
-        """
         self.name = name
         self.root = root
-        self.dataset = LinkPropPredDataset(name=name, root=root)
+        self.dataset = NodePropPredDataset(name=name, root=root)
         self._train_mask = torch.from_numpy(self.dataset.train_mask)
         self._val_mask = torch.from_numpy(self.dataset.val_mask)
         self._test_mask = torch.from_numpy(self.dataset.test_mask)
+        self.__num_classes = self.dataset.num_classes
         super().__init__(root, transform, pre_transform)
-        self._node_feat = self.dataset.node_feat
-
-        if self._node_feat is None:
-            self._node_feat = None
-        else:
-            self._node_feat = torch.from_numpy(self._node_feat).float()
         self.process_data()
 
-        self._ns_sampler = self.dataset.negative_sampler
+    @property
+    def num_classes(self) -> int:
+        """
+        how many classes are in the node label
+        Returns:
+            num_classes: int
+        """
+        return self.__num_classes
 
     @property
     def eval_metric(self) -> str:
         """
         the official evaluation metric for the dataset, loaded from info.py
         Returns:
             eval_metric: str, the evaluation metric
         """
         return self.dataset.eval_metric
 
     @property
-    def negative_sampler(self) -> NegativeEdgeSampler:
-        r"""
-        Returns the negative sampler of the dataset, will load negative samples from disc
-        Returns:
-            negative_sampler: NegativeEdgeSampler
-        """
-        return self._ns_sampler
-
-    def load_val_ns(self) -> None:
-        r"""
-        load the negative samples for the validation set
-        """
-        self.dataset.load_val_ns()
-
-    def load_test_ns(self) -> None:
-        r"""
-        load the negative samples for the test set
-        """
-        self.dataset.load_test_ns()
-
-    @property
     def train_mask(self) -> torch.Tensor:
         r"""
         Returns the train mask of the dataset
         Returns:
             train_mask: the mask for edges in the training set
         """
         if self._train_mask is None:
@@ -102,23 +89,14 @@
             test_mask: the mask for edges in the test set
         """
         if self._test_mask is None:
             raise ValueError("test split hasn't been loaded")
         return self._test_mask
 
     @property
-    def node_feat(self) -> torch.Tensor:
-        r"""
-        Returns the node features of the dataset
-        Returns:
-            node_feat: the node features
-        """
-        return self._node_feat
-
-    @property
     def src(self) -> torch.Tensor:
         r"""
         Returns the source nodes of the dataset
         Returns:
             src: the idx of the source nodes
         """
         return self._src
@@ -151,69 +129,93 @@
         return self._edge_feat
 
     @property
     def edge_label(self) -> torch.Tensor:
         r"""
         Returns the edge labels of the dataset
         Returns:
-            edge_label: the labels of the edges
+            edge_label: the labels of the edges (all one tensor)
         """
         return self._edge_label
 
-    def process_data(self) -> None:
-        r"""
-        convert the numpy arrays from dataset to pytorch tensors
+    def process_data(self):
+        """
+        convert data to pytorch tensors
         """
         src = torch.from_numpy(self.dataset.full_data["sources"])
         dst = torch.from_numpy(self.dataset.full_data["destinations"])
-        ts = torch.from_numpy(self.dataset.full_data["timestamps"])
-        msg = torch.from_numpy(
-            self.dataset.full_data["edge_feat"]
+        t = torch.from_numpy(self.dataset.full_data["timestamps"])
+        edge_label = torch.from_numpy(self.dataset.full_data["edge_label"])
+        msg = torch.from_numpy(self.dataset.full_data["edge_feat"]).reshape(
+            [-1, 1]
         )  # use edge features here if available
-        edge_label = torch.from_numpy(
-            self.dataset.full_data["edge_label"]
-        )  # this is the label indicating if an edge is a true edge, always 1 for true edges
-
-        # * first check typing for all tensors
-        # source tensor must be of type int64
-        # warnings.warn("sources tensor is not of type int64 or int32, forcing conversion")
+
+        # * check typing
         if src.dtype != torch.int64:
             src = src.long()
 
-        # destination tensor must be of type int64
         if dst.dtype != torch.int64:
             dst = dst.long()
 
-        # timestamp tensor must be of type int64
-        if ts.dtype != torch.int64:
-            ts = ts.long()
+        if t.dtype != torch.int64:
+            t = t.long()
 
-        # message tensor must be of type float32
         if msg.dtype != torch.float32:
             msg = msg.float()
 
         self._src = src
         self._dst = dst
-        self._ts = ts
+        self._ts = t
         self._edge_label = edge_label
         self._edge_feat = msg
 
-    def get_TemporalData(self) -> TemporalData:
+    def get_TemporalData(
+        self,
+    ) -> TemporalData:
         """
         return the TemporalData object for the entire dataset
+        Returns:
+            data: TemporalData object storing the edgelist
         """
         data = TemporalData(
             src=self._src,
             dst=self._dst,
             t=self._ts,
             msg=self._edge_feat,
             y=self._edge_label,
         )
         return data
 
+    def reset_label_time(self) -> None:
+        """
+        reset the pointer for the node labels, should be done per epoch
+        """
+        self.dataset.reset_label_time()
+
+    def get_node_label(self, cur_t):
+        """
+        return the node labels for the current timestamp
+        """
+        label_tuple = self.dataset.find_next_labels_batch(cur_t)
+        if label_tuple is None:
+            return None
+        label_ts, label_srcs, labels = label_tuple[0], label_tuple[1], label_tuple[2]
+        label_ts = torch.from_numpy(label_ts).long()
+        label_srcs = torch.from_numpy(label_srcs).long()
+        labels = torch.from_numpy(labels).to(torch.float32)
+        return label_ts, label_srcs, labels
+
+    def get_label_time(self) -> int:
+        """
+        return the timestamps of the current node labels
+        Returns:
+            t: time of the current node labels
+        """
+        return self.dataset.return_label_ts()
+
     def len(self) -> int:
         """
         size of the dataset
         Returns:
             size: int
         """
         return self._src.shape[0]
```

### Comparing `py_tgb-0.1.2/tgb/linkproppred/negative_sampler.py` & `py_tgb-0.6.0/tgb/linkproppred/negative_sampler.py`

 * *Files 17% similar despite different names*

```diff
@@ -14,18 +14,27 @@
 
 
 class NegativeEdgeSampler(object):
     def __init__(
         self,
         dataset_name: str,
         strategy: str = "hist_rnd",
-    ):
+    ) -> None:
         r"""
         Negative Edge Sampler
             Loads and query the negative batches based on the positive batches provided.
+        constructor for the negative edge sampler class
+
+        Parameters:
+            dataset_name: name of the dataset
+            strategy: specifies which set of negatives should be loaded;
+                    can be 'rnd' or 'hist_rnd'
+        
+        Returns:
+            None
         """
         self.dataset_name = dataset_name
         assert strategy in [
             "rnd",
             "hist_rnd",
         ], "The supported strategies are `rnd` or `hist_rnd`!"
         self.strategy = strategy
@@ -37,37 +46,62 @@
         split_mode: str = "val",
     ) -> None:
         r"""
         Load the evaluation set from disk, can be either val or test set ns samples
         Parameters:
             fname: the file name of the evaluation ns on disk
             split_mode: the split mode of the evaluation set, can be either `val` or `test`
+        
+        Returns:
+            None
         """
         assert split_mode in [
             "val",
             "test",
         ], "Invalid split-mode! It should be `val`, `test`"
         if not os.path.exists(fname):
             raise FileNotFoundError(f"File not found at {fname}")
         self.eval_set[split_mode] = load_pkl(fname)
 
-    def reset_eval_set(self, split_mode):
+    def reset_eval_set(self, 
+                       split_mode: str = "test",
+                       ) -> None:
         r"""
         Reset evaluation set
+
+        Parameters:
+            split_mode: specifies whether to generate negative edges for 'validation' or 'test' splits
+
+        Returns:
+            None
         """
         assert split_mode in [
             "val",
             "test",
         ], "Invalid split-mode! It should be `val`, `test`!"
         self.eval_set[split_mode] = None
 
-    def query_batch(self, pos_src, pos_dst, pos_timestamp, split_mode):
+    def query_batch(self, 
+                    pos_src: Tensor, 
+                    pos_dst: Tensor, 
+                    pos_timestamp: Tensor, 
+                    split_mode: str = "test") -> list:
         r"""
         For each positive edge in the `pos_batch`, return a list of negative edges
         `split_mode` specifies whether the valiation or test evaluation set should be retrieved.
+
+        Parameters:
+            pos_src: list of positive source nodes
+            pos_dst: list of positive destination nodes
+            pos_timestamp: list of timestamps of the positive edges
+            split_mode: specifies whether to generate negative edges for 'validation' or 'test' splits
+
+        Returns:
+            neg_samples: a list of list; each internal list contains the set of negative edges that
+                        should be evaluated against each positive edge.
         """
         assert split_mode in [
             "val",
             "test",
         ], "Invalid split-mode! It should be `val`, `test`!"
         if self.eval_set[split_mode] == None:
             raise ValueError(
```

### Comparing `py_tgb-0.1.2/tgb/nodeproppred/dataset.py` & `py_tgb-0.6.0/tgb/nodeproppred/dataset.py`

 * *Files 2% similar despite different names*

```diff
@@ -21,16 +21,15 @@
     load_edgelist_sr,
     load_edgelist_datetime,
     load_trade_label_dict,
     load_edgelist_trade,
 )
 
 
-#! can retire meta_dict as input to the class
-class NodePropertyDataset(object):
+class NodePropPredDataset(object):
     def __init__(
         self,
         name: str,
         root: Optional[str] = "datasets",
         meta_dict: Optional[dict] = None,
         preprocess: Optional[bool] = True,
     ) -> None:
@@ -164,16 +163,16 @@
             df: pandas data frame storing the temporal edge list
             node_label_dict: dictionary with key as timestamp and item as dictionary of node labels
         """
         OUT_DF = self.root + "/" + "ml_{}.pkl".format(self.name)
         OUT_NODE_DF = self.root + "/" + "ml_{}_node.pkl".format(self.name)
         OUT_LABEL_DF = self.root + "/" + "ml_{}_label.pkl".format(self.name)
 
-        # * logic for subreddits, as node label file is too big to store on disc
-        if self.name == "subreddits":
+        # * logic for tgbl-reddit, as node label file is too big to store on disc
+        if self.name == "tgbn-reddit":
             if osp.exists(OUT_DF) and osp.exists(OUT_NODE_DF):
                 df = pd.read_pickle(OUT_DF)
                 node_ids = load_pkl(OUT_NODE_DF)
                 labels_dict = load_pkl(OUT_LABEL_DF)
                 node_label_dict = load_label_dict(
                     self.meta_dict["nodefile"], node_ids, labels_dict
                 )
@@ -182,40 +181,40 @@
         # * load the preprocessed file if possible
         if osp.exists(OUT_DF) and osp.exists(OUT_NODE_DF):
             print("loading processed file")
             df = pd.read_pickle(OUT_DF)
             node_label_dict = load_pkl(OUT_NODE_DF)
         else:  # * process the file
             print("file not processed, generating processed file")
-            if self.name == "subreddits":
+            if self.name == "tgbn-reddit":
                 df, edge_feat, node_ids, labels_dict = load_edgelist_sr(
                     self.meta_dict["fname"], label_size=self._num_classes
                 )
-            elif self.name == "lastfmgenre":
+            elif self.name == "tgbn-genre":
                 df, edge_feat, node_ids, labels_dict = load_edgelist_datetime(
                     self.meta_dict["fname"], label_size=self._num_classes
                 )
-            elif self.name == "un_trade":
+            elif self.name == "tgbn-trade":
                 df, edge_feat, node_ids = load_edgelist_trade(
                     self.meta_dict["fname"], label_size=self._num_classes
                 )
 
             df.to_pickle(OUT_DF)
 
-            if self.name == "un_trade":
+            if self.name == "tgbn-trade":
                 node_label_dict = load_trade_label_dict(
                     self.meta_dict["nodefile"], node_ids
                 )
             else:
                 node_label_dict = load_label_dict(
                     self.meta_dict["nodefile"], node_ids, labels_dict
                 )
 
             if (
-                self.name != "subreddits"
+                self.name != "tgbn-reddit"
             ):  # don't save subreddits on disc, the node label file is too big
                 save_pkl(node_label_dict, OUT_NODE_DF)
             else:
                 save_pkl(node_ids, OUT_NODE_DF)
                 save_pkl(labels_dict, OUT_LABEL_DF)
             
             print("file processed and saved")
@@ -425,16 +424,16 @@
             raise ValueError("test split hasn't been loaded")
 
         return self._test_mask
 
 
 def main():
     # download files
-    name = "un_trade"  # "subreddits" #"lastfmgenre"
-    dataset = NodePropertyDataset(name=name, root="datasets", preprocess=True)
+    name = "tgbn-trade" 
+    dataset = NodePropPredDataset(name=name, root="datasets", preprocess=True)
 
     dataset.node_feat
     dataset.edge_feat  # not the edge weights
     dataset.full_data
     dataset.full_data["edge_idxs"]
     dataset.full_data["sources"]
     dataset.full_data["destinations"]
```

### Comparing `py_tgb-0.1.2/tgb/utils/dataset_stats.py` & `py_tgb-0.6.0/tgb/utils/dataset_stats.py`

 * *Files 6% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 
 import numpy as np
 import pandas as pd
 import networkx as nx
 import argparse
 
 from torch_geometric.loader import TemporalDataLoader
-from tgb.nodeproppred.dataset_pyg import PyGNodePropertyDataset
+from tgb.nodeproppred.dataset_pyg import PyGNodePropPredDataset
 # from tgb.linkproppred.dataset_pyg import PyGLinkPropPredDataset
 from tgb.linkproppred.dataset import LinkPropPredDataset
 
 
 
 
 def get_unique_edges(sources, destination):
@@ -150,24 +150,24 @@
 
 
 def main():
     r"""
     Generate dateset statistics
     """
     parser = argparse.ArgumentParser(description='Dataset statistics')
-    parser.add_argument('-d', '--data', type=str, default='wikipedia', help='random seed to use')
+    parser.add_argument('-d', '--data', type=str, default='tgbl-wiki', help='random seed to use')
     parser.add_argument('--tempstats', action='store_true', default=False, help='whether compute temporal statistics')
     parser.parse_args()
     args = parser.parse_args()
 
     DATA = args.data
     temporal_stats = args.tempstats
 
     # data loading ...
-    if DATA in ['wikipedia', 'amazonreview', 'opensky', 'redditcomments', 'stablecoin']:
+    if DATA in ['tgbl-wiki', 'tgbl-review', 'tgbl-flight', 'tgbl-comment', 'tgbl-coin']:
         # load data: link prop. pred. with `numpy`
         dataset = LinkPropPredDataset(name=DATA, root="datasets", preprocess=True)
         data = dataset.full_data  
 
         # get masks
         train_mask = dataset.train_mask
         val_mask = dataset.val_mask
@@ -185,17 +185,17 @@
                       'destinations': data['destinations'][test_mask],
                       }
         full_data = {'sources': data['sources'], 
                      'destinations': data['destinations'], 
                      'timestamps': data['timestamps'],
                      }
 
-    elif DATA in ['un_trade', 'lastfmgenre', 'subreddits']:
+    elif DATA in ['tgbn-trade', 'tgbn-genre', 'tgbn-reddit']:
         # load data: node prop. pred.
-        dataset = PyGNodePropertyDataset(name=DATA, root="datasets")
+        dataset = PyGNodePropPredDataset(name=DATA, root="datasets")
         data = dataset.get_TemporalData()
         
         # split data
         train_mask = dataset.train_mask
         val_mask = dataset.val_mask
         test_mask = dataset.test_mask
         train_val_mask = np.logical_or(np.array(train_mask), np.array(val_mask))
```

### Comparing `py_tgb-0.1.2/tgb/utils/info.py` & `py_tgb-0.6.0/tgb/utils/info.py`

 * *Files 20% similar despite different names*

```diff
@@ -18,38 +18,37 @@
     OKGREEN = "\033[92m"
     WARNING = "\033[93m"
     FAIL = "\033[91m"
     ENDC = "\033[0m"
     BOLD = "\033[1m"
     UNDERLINE = "\033[4m"
 
-
 DATA_URL_DICT = {
-    "wikipedia": "https://object-arbutus.cloud.computecanada.ca/tgb/wikipedia.zip",
-    "amazonreview": "https://object-arbutus.cloud.computecanada.ca/tgb/amazonreview.zip",
-    "opensky": "https://object-arbutus.cloud.computecanada.ca/tgb/opensky.zip",
-    "stablecoin": "https://object-arbutus.cloud.computecanada.ca/tgb/stablecoin.zip",
-    "redditcomments": "https://object-arbutus.cloud.computecanada.ca/tgb/redditcomments.zip",
-    "un_trade": "https://object-arbutus.cloud.computecanada.ca/tgb/un_trade.zip",
-    "lastfmgenre": "https://object-arbutus.cloud.computecanada.ca/tgb/lastfmgenre.zip",
-    "subreddits": "https://object-arbutus.cloud.computecanada.ca/tgb/subreddits.zip",
-    "MAG": "https://object-arbutus.cloud.computecanada.ca/tgb/mag_cs.zip",
+    "tgbl-wiki": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbl-wiki.zip",
+    "tgbl-review": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbl-review.zip",
+    "tgbl-coin": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbl-coin.zip",
+    "tgbl-flight": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbl-flight.zip",
+    "tgbl-comment": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbl-comment.zip",
+    "tgbn-trade": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbn-trade.zip",
+    "tgbn-genre": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbn-genre.zip",
+    "tgbn-reddit": "https://object-arbutus.cloud.computecanada.ca/tgb/tgbn-reddit.zip",
 }
 
+#"https://object-arbutus.cloud.computecanada.ca/tgb/wiki_neg.zip" for all negative samples of the wiki dataset
 
 DATA_EVAL_METRIC_DICT = {
-    "un_trade": "ndcg",
-    "subreddits": "ndcg",
-    "lastfmgenre": "ndcg",
-    "wikipedia": "mrr",
-    "opensky": "mrr",
-    "stablecoin": "mrr",
-    "redditcomments": "mrr",
-    "amazonreview": "mrr",
+    "tgbl-wiki": "mrr",
+    "tgbl-review": "mrr",
+    "tgbl-coin": "mrr",
+    "tgbl-comment": "mrr",
+    "tgbl-flight": "mrr",
+    "tgbn-trade": "ndcg",
+    "tgbn-genre": "ndcg",
+    "tgbn-reddit": "ndcg",
 }
 
 
 DATA_NUM_CLASSES = {
-    "lastfmgenre": 513,
-    "subreddits": 698,
-    "un_trade": 255,
+    "tgbn-trade": 255,
+    "tgbn-genre": 513,
+    "tgbn-reddit": 698,
 }
```

### Comparing `py_tgb-0.1.2/tgb/utils/pre_process.py` & `py_tgb-0.6.0/tgb/utils/pre_process.py`

 * *Files identical despite different names*

### Comparing `py_tgb-0.1.2/tgb/utils/stats.py` & `py_tgb-0.6.0/tgb/utils/stats.py`

 * *Files 15% similar despite different names*

```diff
@@ -86,16 +86,13 @@
     """
     plt.plot(y, color="#fc4e2a")
     plt.savefig(outname + ".pdf")
     plt.close()
 
 
 def main():
-    # fname = "../datasets/flight_raw/opensky/opensky_edgelist.csv"
-    # fname = "../datasets/lastfmgenre/lastfmgenre_raw/lastfmgenre_edgelist.csv"
-    # fname = "../datasets/redditcomments/redditcomments_edgelist.csv"
-    fname = "tgb/datasets/wikipedia/wikipedia_edgelist.csv"
+    fname = "tgb/datasets/tgbl-wiki/tgbl-wiki_edgelist.csv"
     analyze_csv(fname)
 
 
 if __name__ == "__main__":
     main()
```

### Comparing `py_tgb-0.1.2/tgb/utils/utils.py` & `py_tgb-0.6.0/tgb/utils/utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -39,15 +39,15 @@
     array = np.asarray(array)
     idx = (np.abs(array - value)).argmin()
     return array[idx]
 
 
 def get_args():
     parser = argparse.ArgumentParser('*** TGB ***')
-    parser.add_argument('-d', '--data', type=str, help='Dataset name', default='wikipedia')
+    parser.add_argument('-d', '--data', type=str, help='Dataset name', default='tgbl-wiki')
     parser.add_argument('--lr', type=float, help='Learning rate', default=1e-4)
     parser.add_argument('--bs', type=int, help='Batch size', default=200)
     parser.add_argument('--k_value', type=int, help='k_value for computing ranking metrics', default=10)
     parser.add_argument('--num_epoch', type=int, help='Number of epochs', default=50)
     parser.add_argument('--seed', type=int, help='Random seed', default=1)
     parser.add_argument('--mem_dim', type=int, help='Memory dimension', default=100)
     parser.add_argument('--time_dim', type=int, help='Time dimension', default=100)
```

### Comparing `py_tgb-0.1.2/PKG-INFO` & `py_tgb-0.6.0/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: py-tgb
-Version: 0.1.2
+Version: 0.6.0
 Summary: Temporal Graph Benchmark project repo
 Author: shenyang Huang
 Author-email: shenyang.huang@mail.mcgill.ca
 Requires-Python: >=3.9,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
@@ -14,24 +14,28 @@
 Requires-Dist: requests (>=2.28.2,<3.0.0)
 Requires-Dist: scikit-learn (>=1.2.2,<2.0.0)
 Requires-Dist: torch-geometric (>=2.3.0,<3.0.0)
 Requires-Dist: tqdm (>=4.65.0,<5.0.0)
 Description-Content-Type: text/markdown
 
 # TGB
-Temporal Graph Benchmark project repo 
+Temporal Graph Benchmark for Machine Learning on Temporal Graphs 
 
 ### Pypi Install
 
 You can install TGB via [pip](https://pypi.org/project/py-tgb/)
 ```
 pip install py-tgb
 ```
 
-### Dataset Download
+### Links and Datasets
+
+The project website can be found [here](https://tgb-website.pages.dev/).
+
+The API documentations can be found [here](https://shenyanghuang.github.io/TGB/).
 
 all dataset download links can be found at [info.py](https://github.com/shenyangHuang/TGB/blob/main/tgb/utils/info.py)
 
 TGB dataloader will also automatically download the dataset
 
 ### Install dependency
 Our implementation works with python >= 3.9 and can be installed as follows
```

