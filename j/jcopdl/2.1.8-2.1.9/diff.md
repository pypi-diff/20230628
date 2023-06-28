# Comparing `tmp/jcopdl-2.1.8.tar.gz` & `tmp/jcopdl-2.1.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jcopdl-2.1.8.tar", last modified: Tue Feb 21 07:32:59 2023, max compression
+gzip compressed data, was "jcopdl-2.1.9.tar", last modified: Wed Jun 28 00:47:39 2023, max compression
```

## Comparing `jcopdl-2.1.8.tar` & `jcopdl-2.1.9.tar`

### file list

```diff
@@ -1,49 +1,49 @@
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.182709 jcopdl-2.1.8/
--rw-r--r--   0 bmduser    (501) staff       (20)     1513 2022-11-02 16:57:11.000000 jcopdl-2.1.8/LICENSE
--rw-r--r--   0 bmduser    (501) staff       (20)     1208 2023-02-21 07:32:59.182931 jcopdl-2.1.8/PKG-INFO
--rw-r--r--   0 bmduser    (501) staff       (20)      427 2022-11-02 16:57:11.000000 jcopdl-2.1.8/README.md
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.167724 jcopdl-2.1.8/jcopdl/
--rw-r--r--   0 bmduser    (501) staff       (20)       76 2023-02-21 07:32:30.000000 jcopdl-2.1.8/jcopdl/__init__.py
--rw-r--r--   0 bmduser    (501) staff       (20)    11976 2023-02-17 20:23:33.000000 jcopdl-2.1.8/jcopdl/callback.py
--rw-r--r--   0 bmduser    (501) staff       (20)     1346 2023-02-18 00:58:01.000000 jcopdl-2.1.8/jcopdl/eval.py
--rw-r--r--   0 bmduser    (501) staff       (20)      217 2022-12-16 20:36:07.000000 jcopdl-2.1.8/jcopdl/exception.py
--rw-r--r--   0 bmduser    (501) staff       (20)      225 2023-02-17 20:23:36.000000 jcopdl-2.1.8/jcopdl/io.py
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.171625 jcopdl-2.1.8/jcopdl/layers/
--rw-r--r--   0 bmduser    (501) staff       (20)      123 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/layers/__init__.py
--rw-r--r--   0 bmduser    (501) staff       (20)     2194 2022-12-17 03:10:42.000000 jcopdl-2.1.8/jcopdl/layers/_base.py
--rw-r--r--   0 bmduser    (501) staff       (20)     3329 2022-12-17 03:10:39.000000 jcopdl-2.1.8/jcopdl/layers/_block.py
--rw-r--r--   0 bmduser    (501) staff       (20)      888 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/layers/_layers.py
--rw-r--r--   0 bmduser    (501) staff       (20)     4803 2023-02-21 02:58:56.000000 jcopdl-2.1.8/jcopdl/metrics.py
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.174195 jcopdl-2.1.8/jcopdl/optim/
--rw-r--r--   0 bmduser    (501) staff       (20)       97 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/optim/__init__.py
--rw-r--r--   0 bmduser    (501) staff       (20)     1474 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/optim/_lookahead.py
--rw-r--r--   0 bmduser    (501) staff       (20)      604 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/optim/_optimizer.py
--rw-r--r--   0 bmduser    (501) staff       (20)     4509 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/optim/_radam.py
--rw-r--r--   0 bmduser    (501) staff       (20)     3869 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/optim/_ralamb.py
--rw-r--r--   0 bmduser    (501) staff       (20)    32048 2023-02-18 00:57:42.000000 jcopdl-2.1.8/jcopdl/snippet.py
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.175840 jcopdl-2.1.8/jcopdl/transforms/
--rw-r--r--   0 bmduser    (501) staff       (20)      779 2022-12-18 15:35:38.000000 jcopdl-2.1.8/jcopdl/transforms/__init__.py
--rw-r--r--   0 bmduser    (501) staff       (20)      509 2022-12-18 15:43:31.000000 jcopdl-2.1.8/jcopdl/transforms/augment.py
--rw-r--r--   0 bmduser    (501) staff       (20)     1446 2022-12-18 15:49:06.000000 jcopdl-2.1.8/jcopdl/transforms/sequence.py
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.178881 jcopdl-2.1.8/jcopdl/utils/
--rw-r--r--   0 bmduser    (501) staff       (20)       43 2023-02-17 18:15:13.000000 jcopdl-2.1.8/jcopdl/utils/__init__.py
--rw-r--r--   0 bmduser    (501) staff       (20)      228 2023-02-17 18:15:49.000000 jcopdl-2.1.8/jcopdl/utils/conv_calculator.py
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.182289 jcopdl-2.1.8/jcopdl/utils/dataloader/
--rw-r--r--   0 bmduser    (501) staff       (20)      215 2022-12-18 15:56:58.000000 jcopdl-2.1.8/jcopdl/utils/dataloader/__init__.py
--rw-r--r--   0 bmduser    (501) staff       (20)     4525 2022-12-18 15:49:43.000000 jcopdl-2.1.8/jcopdl/utils/dataloader/char_rnn.py
--rw-r--r--   0 bmduser    (501) staff       (20)     3019 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/utils/dataloader/coco_detection.py
--rw-r--r--   0 bmduser    (501) staff       (20)     1936 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/utils/dataloader/multilabel.py
--rw-r--r--   0 bmduser    (501) staff       (20)     2889 2023-02-17 18:13:42.000000 jcopdl-2.1.8/jcopdl/utils/dataloader/time_series.py
--rw-r--r--   0 bmduser    (501) staff       (20)       92 2023-01-01 04:20:04.000000 jcopdl-2.1.8/jcopdl/utils/helper.py
--rw-r--r--   0 bmduser    (501) staff       (20)      862 2022-12-16 20:39:54.000000 jcopdl-2.1.8/jcopdl/utils/nb_check.py
--rw-r--r--   0 bmduser    (501) staff       (20)      419 2022-11-02 16:57:11.000000 jcopdl-2.1.8/jcopdl/utils/random_state.py
--rw-r--r--   0 bmduser    (501) staff       (20)      997 2022-12-18 15:56:20.000000 jcopdl-2.1.8/jcopdl/utils/sampler.py
--rw-r--r--   0 bmduser    (501) staff       (20)     2195 2023-02-17 02:45:20.000000 jcopdl-2.1.8/jcopdl/visualization.py
-drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-02-21 07:32:59.169823 jcopdl-2.1.8/jcopdl.egg-info/
--rw-r--r--   0 bmduser    (501) staff       (20)     1208 2023-02-21 07:32:58.000000 jcopdl-2.1.8/jcopdl.egg-info/PKG-INFO
--rw-r--r--   0 bmduser    (501) staff       (20)      993 2023-02-21 07:32:58.000000 jcopdl-2.1.8/jcopdl.egg-info/SOURCES.txt
--rw-r--r--   0 bmduser    (501) staff       (20)        1 2023-02-21 07:32:58.000000 jcopdl-2.1.8/jcopdl.egg-info/dependency_links.txt
--rw-r--r--   0 bmduser    (501) staff       (20)       37 2023-02-21 07:32:58.000000 jcopdl-2.1.8/jcopdl.egg-info/requires.txt
--rw-r--r--   0 bmduser    (501) staff       (20)        7 2023-02-21 07:32:58.000000 jcopdl-2.1.8/jcopdl.egg-info/top_level.txt
--rw-r--r--   0 bmduser    (501) staff       (20)       67 2023-02-21 07:32:59.183718 jcopdl-2.1.8/setup.cfg
--rw-r--r--   0 bmduser    (501) staff       (20)     1086 2022-11-02 16:57:11.000000 jcopdl-2.1.8/setup.py
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.231292 jcopdl-2.1.9/
+-rw-r--r--   0 bmduser    (501) staff       (20)     1513 2022-11-02 16:57:11.000000 jcopdl-2.1.9/LICENSE
+-rw-r--r--   0 bmduser    (501) staff       (20)     1208 2023-06-28 00:47:39.231489 jcopdl-2.1.9/PKG-INFO
+-rw-r--r--   0 bmduser    (501) staff       (20)      427 2022-11-02 16:57:11.000000 jcopdl-2.1.9/README.md
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.214013 jcopdl-2.1.9/jcopdl/
+-rw-r--r--   0 bmduser    (501) staff       (20)       76 2023-03-14 10:27:13.000000 jcopdl-2.1.9/jcopdl/__init__.py
+-rw-r--r--   0 bmduser    (501) staff       (20)    12446 2023-06-28 00:38:10.000000 jcopdl-2.1.9/jcopdl/callback.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     1346 2023-02-18 00:58:01.000000 jcopdl-2.1.9/jcopdl/eval.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      217 2022-12-16 20:36:07.000000 jcopdl-2.1.9/jcopdl/exception.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      225 2023-02-17 20:23:36.000000 jcopdl-2.1.9/jcopdl/io.py
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.218237 jcopdl-2.1.9/jcopdl/layers/
+-rw-r--r--   0 bmduser    (501) staff       (20)      123 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/layers/__init__.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     2194 2022-12-17 03:10:42.000000 jcopdl-2.1.9/jcopdl/layers/_base.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     3329 2023-03-14 08:55:49.000000 jcopdl-2.1.9/jcopdl/layers/_block.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      888 2023-03-14 08:55:52.000000 jcopdl-2.1.9/jcopdl/layers/_layers.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     4803 2023-02-21 02:58:56.000000 jcopdl-2.1.9/jcopdl/metrics.py
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.221045 jcopdl-2.1.9/jcopdl/optim/
+-rw-r--r--   0 bmduser    (501) staff       (20)       97 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/optim/__init__.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     1474 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/optim/_lookahead.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      604 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/optim/_optimizer.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     4509 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/optim/_radam.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     3869 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/optim/_ralamb.py
+-rw-r--r--   0 bmduser    (501) staff       (20)    32048 2023-02-18 00:57:42.000000 jcopdl-2.1.9/jcopdl/snippet.py
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.223024 jcopdl-2.1.9/jcopdl/transforms/
+-rw-r--r--   0 bmduser    (501) staff       (20)      779 2022-12-18 15:35:38.000000 jcopdl-2.1.9/jcopdl/transforms/__init__.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      509 2022-12-18 15:43:31.000000 jcopdl-2.1.9/jcopdl/transforms/augment.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     1446 2022-12-18 15:49:06.000000 jcopdl-2.1.9/jcopdl/transforms/sequence.py
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.226852 jcopdl-2.1.9/jcopdl/utils/
+-rw-r--r--   0 bmduser    (501) staff       (20)       43 2023-02-17 18:15:13.000000 jcopdl-2.1.9/jcopdl/utils/__init__.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      228 2023-02-17 18:15:49.000000 jcopdl-2.1.9/jcopdl/utils/conv_calculator.py
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.230672 jcopdl-2.1.9/jcopdl/utils/dataloader/
+-rw-r--r--   0 bmduser    (501) staff       (20)      215 2022-12-18 15:56:58.000000 jcopdl-2.1.9/jcopdl/utils/dataloader/__init__.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     4525 2022-12-18 15:49:43.000000 jcopdl-2.1.9/jcopdl/utils/dataloader/char_rnn.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     3019 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/utils/dataloader/coco_detection.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     1936 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/utils/dataloader/multilabel.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     2889 2023-02-17 18:13:42.000000 jcopdl-2.1.9/jcopdl/utils/dataloader/time_series.py
+-rw-r--r--   0 bmduser    (501) staff       (20)       92 2023-01-01 04:20:04.000000 jcopdl-2.1.9/jcopdl/utils/helper.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      862 2022-12-16 20:39:54.000000 jcopdl-2.1.9/jcopdl/utils/nb_check.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      419 2022-11-02 16:57:11.000000 jcopdl-2.1.9/jcopdl/utils/random_state.py
+-rw-r--r--   0 bmduser    (501) staff       (20)      997 2022-12-18 15:56:20.000000 jcopdl-2.1.9/jcopdl/utils/sampler.py
+-rw-r--r--   0 bmduser    (501) staff       (20)     2195 2023-02-17 02:45:20.000000 jcopdl-2.1.9/jcopdl/visualization.py
+drwxr-xr-x   0 bmduser    (501) staff       (20)        0 2023-06-28 00:47:39.216120 jcopdl-2.1.9/jcopdl.egg-info/
+-rw-r--r--   0 bmduser    (501) staff       (20)     1208 2023-06-28 00:47:39.000000 jcopdl-2.1.9/jcopdl.egg-info/PKG-INFO
+-rw-r--r--   0 bmduser    (501) staff       (20)      993 2023-06-28 00:47:39.000000 jcopdl-2.1.9/jcopdl.egg-info/SOURCES.txt
+-rw-r--r--   0 bmduser    (501) staff       (20)        1 2023-06-28 00:47:39.000000 jcopdl-2.1.9/jcopdl.egg-info/dependency_links.txt
+-rw-r--r--   0 bmduser    (501) staff       (20)       37 2023-06-28 00:47:39.000000 jcopdl-2.1.9/jcopdl.egg-info/requires.txt
+-rw-r--r--   0 bmduser    (501) staff       (20)        7 2023-06-28 00:47:39.000000 jcopdl-2.1.9/jcopdl.egg-info/top_level.txt
+-rw-r--r--   0 bmduser    (501) staff       (20)       67 2023-06-28 00:47:39.232628 jcopdl-2.1.9/setup.cfg
+-rw-r--r--   0 bmduser    (501) staff       (20)     1086 2022-11-02 16:57:11.000000 jcopdl-2.1.9/setup.py
```

### Comparing `jcopdl-2.1.8/LICENSE` & `jcopdl-2.1.9/LICENSE`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/PKG-INFO` & `jcopdl-2.1.9/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jcopdl
-Version: 2.1.8
+Version: 2.1.9
 Summary: J.COp DL is a deep Learning package to complement pytorch workflow
 Home-page: https://github.com/WiraDKP/jcopdl
 Author: Wira Dharma Kencana Putra
 Author-email: wiradharma_kencanaputra@yahoo.com
 Keywords: deep learning dl jcop indonesia
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Intended Audience :: Developers
```

### Comparing `jcopdl-2.1.8/jcopdl/callback.py` & `jcopdl-2.1.9/jcopdl/callback.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,10 @@
 import torch
 import numpy as np
 import pandas as pd
-from copy import deepcopy
 from PIL import Image
 from pathlib import Path
 from warnings import warn
 
 from jcopdl.utils.nb_check import IN_NOTEBOOK
 from jcopdl.utils.helper import listify
 from jcopdl.exception import NotLoggedError, InvalidScaleValue, InvalidSenseValue, ModelError
@@ -103,15 +102,15 @@
         self._graph_axes = None        
         self._graph_metrics = []
         self._graph_scales = []
 
         self._image_nb = None
         self._image_metrics = []
 
-    def early_stopping(self, sense, monitor, load_best_when_stop=True, plot=True, plot_image=True, figsize="auto"):
+    def early_stopping(self, sense, monitor, load_best_when_stop=True, n_row=10, plot=True, plot_image=True, figsize="auto"):
         """
         sense: {"maximize", "minimize"}
             Sense of the metric's.
             - use "minimize" if lower is better
             - use "maximize" if higher is better
 
         monitor: str
@@ -123,15 +122,15 @@
         
         if monitor not in self.logs:
             raise NotLoggedError(f'Metric {monitor} is not logged. Please use callback.log("{monitor}", value).')
 
         # Show report
         self.log("epoch", self.epoch)
         if IN_NOTEBOOK:
-            report_table = HTML(pd.DataFrame(self.logs).set_index("epoch").to_html())
+            report_table = HTML(pd.DataFrame(self.logs).set_index("epoch").tail(n_row).to_html())
             if self._report_nb is None:
                 self._report_nb = display(report_table, display_id=True)
             else:
                 self._report_nb.update(report_table)
         else:
             report = f'Epoch {self.epoch:5}\n'
             report += " | ".join([f'{k.title():10} = {v[-1]:.4f}' for k, v in self.logs.items() if k != "epoch"])
@@ -152,15 +151,15 @@
         last_metric = self.logs[monitor][-1]
         is_improve = last_metric > self.best_metric if sense == "maximize" else last_metric < self.best_metric
             
         stop = False
         if is_improve:
             self.best_metric = last_metric
             self.best_epoch = self.epoch
-            self.reset_early_stop()
+            self.early_stop = 0
             self._save_best()
         else:
             self.early_stop += 1
             if not IN_NOTEBOOK:
                 print(f"\x1b[31m==> EarlyStop patience = {self.early_stop:2} | Best {monitor}: {self.best_metric:.4f}\x1b[0m")
 
             if self.early_stop == self.max_epoch:
@@ -260,16 +259,18 @@
     def log_image(self, name, pil_image):
         if name not in self.logs:
             self.logs[name] = []
         log_path = self.outdir / "image_logs" / name / f"{self.epoch}.png"
         pil_image.save(log_path)
         self.logs[name].append(log_path)
 
-    def reset_early_stop(self):
-        self.early_stop = 0
+    def reset_nb(self):
+        self._report_nb = None
+        self._graph_nb = None        
+        self._image_nb = None
         
     def change_early_stop_patience(self, patience):
         self.early_stop_patience = patience
 
     def _save_best(self):
         torch.save(self.model, self.outdir / f'model_best.pth')
         torch.save(self.optimizer, self.outdir / f'optimizer_best.pth')
@@ -278,22 +279,35 @@
         except:
             torch.save(self.logs, self.outdir / "logs.pth")
 
     def _save_ckpt(self):
         ckpt_path = self.outdir / "checkpoint"
         ckpt_path.mkdir(parents=True, exist_ok=True)
         
-        callback = deepcopy(self)
-        callback._report_nb = None
-        callback._graph_nb = None
-        callback._image_nb = None
-        callback._graph_fig = None
-        callback._graph_axes = None
-        torch.save(callback, ckpt_path / f'epoch_{self.epoch}.pth')
-        del(callback)
+        metadata = {
+            "report_nb": self._report_nb,
+            "graph_nb": self._graph_nb,
+            "image_nb": self._image_nb,
+            "graph_fig": self._graph_fig,
+            "graph_axes": self._graph_axes
+        }
+
+        self._report_nb = None
+        self._graph_nb = None
+        self._image_nb = None
+        self._graph_fig = None
+        self._graph_axes = None
+        torch.save(self, ckpt_path / f'epoch_{self.epoch}.pth')
+        
+        self._report_nb = metadata["report_nb"]
+        self._graph_nb = metadata["graph_nb"]
+        self._image_nb = metadata["image_nb"]
+        self._graph_fig = metadata["graph_fig"]
+        self._graph_axes = metadata["graph_axes"]
+        
 
     def _check_value(self, model, model_config, optimizer_config, metadata, max_epoch):
         self.max_epoch = max_epoch if max_epoch is not None else np.inf
         
         if (model_config is not None) and isinstance(model_config, dict):
             torch.save(model_config, self.outdir / "model_configs.pth")
```

### Comparing `jcopdl-2.1.8/jcopdl/eval.py` & `jcopdl-2.1.9/jcopdl/eval.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/layers/_base.py` & `jcopdl-2.1.9/jcopdl/layers/_base.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/layers/_block.py` & `jcopdl-2.1.9/jcopdl/layers/_block.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/layers/_layers.py` & `jcopdl-2.1.9/jcopdl/layers/_layers.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/metrics.py` & `jcopdl-2.1.9/jcopdl/metrics.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/optim/_lookahead.py` & `jcopdl-2.1.9/jcopdl/optim/_lookahead.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/optim/_optimizer.py` & `jcopdl-2.1.9/jcopdl/optim/_optimizer.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/optim/_radam.py` & `jcopdl-2.1.9/jcopdl/optim/_radam.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/optim/_ralamb.py` & `jcopdl-2.1.9/jcopdl/optim/_ralamb.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/snippet.py` & `jcopdl-2.1.9/jcopdl/snippet.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/transforms/__init__.py` & `jcopdl-2.1.9/jcopdl/transforms/__init__.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/transforms/sequence.py` & `jcopdl-2.1.9/jcopdl/transforms/sequence.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/utils/dataloader/char_rnn.py` & `jcopdl-2.1.9/jcopdl/utils/dataloader/char_rnn.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/utils/dataloader/coco_detection.py` & `jcopdl-2.1.9/jcopdl/utils/dataloader/coco_detection.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/utils/dataloader/multilabel.py` & `jcopdl-2.1.9/jcopdl/utils/dataloader/multilabel.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/utils/dataloader/time_series.py` & `jcopdl-2.1.9/jcopdl/utils/dataloader/time_series.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/utils/nb_check.py` & `jcopdl-2.1.9/jcopdl/utils/nb_check.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/utils/sampler.py` & `jcopdl-2.1.9/jcopdl/utils/sampler.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl/visualization.py` & `jcopdl-2.1.9/jcopdl/visualization.py`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/jcopdl.egg-info/PKG-INFO` & `jcopdl-2.1.9/jcopdl.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jcopdl
-Version: 2.1.8
+Version: 2.1.9
 Summary: J.COp DL is a deep Learning package to complement pytorch workflow
 Home-page: https://github.com/WiraDKP/jcopdl
 Author: Wira Dharma Kencana Putra
 Author-email: wiradharma_kencanaputra@yahoo.com
 Keywords: deep learning dl jcop indonesia
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Intended Audience :: Developers
```

### Comparing `jcopdl-2.1.8/jcopdl.egg-info/SOURCES.txt` & `jcopdl-2.1.9/jcopdl.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `jcopdl-2.1.8/setup.py` & `jcopdl-2.1.9/setup.py`

 * *Files identical despite different names*

