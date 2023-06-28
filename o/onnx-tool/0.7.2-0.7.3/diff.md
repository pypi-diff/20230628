# Comparing `tmp/onnx-tool-0.7.2.tar.gz` & `tmp/onnx-tool-0.7.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "onnx-tool-0.7.2.tar", last modified: Fri Jun 23 14:11:33 2023, max compression
+gzip compressed data, was "onnx-tool-0.7.3.tar", last modified: Wed Jun 28 15:55:12 2023, max compression
```

## Comparing `onnx-tool-0.7.2.tar` & `onnx-tool-0.7.3.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxrwxrwx   0        0        0        0 2023-06-23 14:11:33.945464 onnx-tool-0.7.2/
--rw-rw-rw-   0        0        0     1092 2022-12-15 10:33:04.000000 onnx-tool-0.7.2/LICENSE
--rw-rw-rw-   0        0        0    10735 2023-06-23 14:11:33.939957 onnx-tool-0.7.2/PKG-INFO
--rw-rw-rw-   0        0        0    10276 2023-06-18 06:46:34.000000 onnx-tool-0.7.2/README.md
-drwxrwxrwx   0        0        0        0 2023-06-23 14:11:33.934868 onnx-tool-0.7.2/onnx_tool/
--rw-rw-rw-   0        0        0     7846 2023-06-19 15:21:47.000000 onnx-tool-0.7.2/onnx_tool/__init__.py
--rw-rw-rw-   0        0        0     3051 2023-06-18 06:46:34.000000 onnx-tool-0.7.2/onnx_tool/__main__.py
--rw-rw-rw-   0        0        0    16079 2023-06-19 15:20:56.000000 onnx-tool-0.7.2/onnx_tool/fusion.py
--rw-rw-rw-   0        0        0    55538 2023-06-23 13:57:22.000000 onnx-tool-0.7.2/onnx_tool/graph.py
--rw-rw-rw-   0        0        0      876 2023-06-19 15:20:56.000000 onnx-tool-0.7.2/onnx_tool/model.py
--rw-rw-rw-   0        0        0    73508 2023-06-18 06:46:34.000000 onnx-tool-0.7.2/onnx_tool/node.py
--rw-rw-rw-   0        0        0     6433 2023-06-18 06:46:34.000000 onnx-tool-0.7.2/onnx_tool/serialization.py
--rw-rw-rw-   0        0        0    15758 2023-06-18 06:46:34.000000 onnx-tool-0.7.2/onnx_tool/tensor.py
--rw-rw-rw-   0        0        0     3685 2023-06-23 14:10:10.000000 onnx-tool-0.7.2/onnx_tool/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-23 14:11:33.939957 onnx-tool-0.7.2/onnx_tool.egg-info/
--rw-rw-rw-   0        0        0    10735 2023-06-23 14:11:33.000000 onnx-tool-0.7.2/onnx_tool.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      404 2023-06-23 14:11:33.000000 onnx-tool-0.7.2/onnx_tool.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-23 14:11:33.000000 onnx-tool-0.7.2/onnx_tool.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       20 2023-06-23 14:11:33.000000 onnx-tool-0.7.2/onnx_tool.egg-info/requires.txt
--rw-rw-rw-   0        0        0       10 2023-06-23 14:11:33.000000 onnx-tool-0.7.2/onnx_tool.egg-info/top_level.txt
--rw-rw-rw-   0        0        0        2 2023-06-20 15:43:33.000000 onnx-tool-0.7.2/onnx_tool.egg-info/zip-safe
--rw-rw-rw-   0        0        0       42 2023-06-23 14:11:33.945464 onnx-tool-0.7.2/setup.cfg
--rw-rw-rw-   0        0        0      988 2023-06-23 14:10:10.000000 onnx-tool-0.7.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:55:11.997973 onnx-tool-0.7.3/
+-rw-rw-rw-   0        0        0     1092 2022-12-15 10:33:04.000000 onnx-tool-0.7.3/LICENSE
+-rw-rw-rw-   0        0        0    10735 2023-06-28 15:55:11.996448 onnx-tool-0.7.3/PKG-INFO
+-rw-rw-rw-   0        0        0    10276 2023-06-18 06:46:34.000000 onnx-tool-0.7.3/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 15:55:11.981558 onnx-tool-0.7.3/onnx_tool/
+-rw-rw-rw-   0        0        0     7846 2023-06-19 15:21:47.000000 onnx-tool-0.7.3/onnx_tool/__init__.py
+-rw-rw-rw-   0        0        0     3051 2023-06-18 06:46:34.000000 onnx-tool-0.7.3/onnx_tool/__main__.py
+-rw-rw-rw-   0        0        0    16079 2023-06-19 15:20:56.000000 onnx-tool-0.7.3/onnx_tool/fusion.py
+-rw-rw-rw-   0        0        0    55538 2023-06-28 09:56:20.000000 onnx-tool-0.7.3/onnx_tool/graph.py
+-rw-rw-rw-   0        0        0      876 2023-06-19 15:20:56.000000 onnx-tool-0.7.3/onnx_tool/model.py
+-rw-rw-rw-   0        0        0    73518 2023-06-28 09:53:51.000000 onnx-tool-0.7.3/onnx_tool/node.py
+-rw-rw-rw-   0        0        0     6433 2023-06-18 06:46:34.000000 onnx-tool-0.7.3/onnx_tool/serialization.py
+-rw-rw-rw-   0        0        0    15758 2023-06-18 06:46:34.000000 onnx-tool-0.7.3/onnx_tool/tensor.py
+-rw-rw-rw-   0        0        0     3685 2023-06-28 15:54:38.000000 onnx-tool-0.7.3/onnx_tool/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:55:11.994489 onnx-tool-0.7.3/onnx_tool.egg-info/
+-rw-rw-rw-   0        0        0    10735 2023-06-28 15:55:11.000000 onnx-tool-0.7.3/onnx_tool.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      404 2023-06-28 15:55:11.000000 onnx-tool-0.7.3/onnx_tool.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 15:55:11.000000 onnx-tool-0.7.3/onnx_tool.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 15:55:11.000000 onnx-tool-0.7.3/onnx_tool.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       10 2023-06-28 15:55:11.000000 onnx-tool-0.7.3/onnx_tool.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0        2 2023-06-20 15:43:33.000000 onnx-tool-0.7.3/onnx_tool.egg-info/zip-safe
+-rw-rw-rw-   0        0        0       42 2023-06-28 15:55:11.997973 onnx-tool-0.7.3/setup.cfg
+-rw-rw-rw-   0        0        0      988 2023-06-28 15:54:38.000000 onnx-tool-0.7.3/setup.py
```

### Comparing `onnx-tool-0.7.2/LICENSE` & `onnx-tool-0.7.3/LICENSE`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/PKG-INFO` & `onnx-tool-0.7.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: onnx-tool
-Version: 0.7.2
+Version: 0.7.3
 Summary: A tool for ONNX model:Rapid shape inference; Profile model; Compute Graph and Shape Engine; OPs fusion;Quantized models and sparse models are supported.
 Home-page: https://github.com/ThanatosShinji/onnx-tool
 Author: Luo Yu
 Author-email: luoyu888888@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Description-Content-Type: text/markdown
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: onnx-tool Version: 0.7.2 Summary: A tool for ONNX
+Metadata-Version: 2.1 Name: onnx-tool Version: 0.7.3 Summary: A tool for ONNX
 model:Rapid shape inference; Profile model; Compute Graph and Shape Engine; OPs
 fusion;Quantized models and sparse models are supported. Home-page: https://
 github.com/ThanatosShinji/onnx-tool Author: Luo Yu Author-email:
 luoyu888888@gmail.com License: MIT Classifier: Programming Language :: Python
 :: 3 Description-Content-Type: text/markdown License-File: LICENSE ç®ä½ä¸­æ
 # onnx-tool **A tool for ONNX model:** * *Rapid shape inference.* * *Profile
 model.* * *Constant_Folding.* * *Compute Graph and Shape Engine.* * *OPs
```

### Comparing `onnx-tool-0.7.2/README.md` & `onnx-tool-0.7.3/README.md`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/__init__.py` & `onnx-tool-0.7.3/onnx_tool/__init__.py`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/__main__.py` & `onnx-tool-0.7.3/onnx_tool/__main__.py`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/fusion.py` & `onnx-tool-0.7.3/onnx_tool/fusion.py`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/graph.py` & `onnx-tool-0.7.3/onnx_tool/graph.py`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/model.py` & `onnx-tool-0.7.3/onnx_tool/model.py`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/node.py` & `onnx-tool-0.7.3/onnx_tool/node.py`

 * *Files 1% similar despite different names*

```diff
@@ -926,15 +926,15 @@
             roi = intensors[1]
             scales = intensors[2]
             if len(intensors) >= 4:
                 sizes = intensors[3]
 
         newshape = []
         if is_valid_ndarray(sizes):
-            if len(sizes) == 4:
+            if len(sizes) == len(xshape):
                 newshape = sizes
             if len(sizes) == 2:
                 newshape = xshape[:2] + sizes
         else:
             if is_valid_ndarray(scales):
                 newshape = []
                 for src, scale in zip(xshape, scales):
```

### Comparing `onnx-tool-0.7.2/onnx_tool/serialization.py` & `onnx-tool-0.7.3/onnx_tool/serialization.py`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/tensor.py` & `onnx-tool-0.7.3/onnx_tool/tensor.py`

 * *Files identical despite different names*

### Comparing `onnx-tool-0.7.2/onnx_tool/utils.py` & `onnx-tool-0.7.3/onnx_tool/utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import time
 import warnings
 
-VERSION = "0.7.2"
+VERSION = "0.7.3"
 
 
 class timer():
     def __init__(self):
         self._startt = time.time()
 
     def start(self):
```

### Comparing `onnx-tool-0.7.2/onnx_tool.egg-info/PKG-INFO` & `onnx-tool-0.7.3/onnx_tool.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: onnx-tool
-Version: 0.7.2
+Version: 0.7.3
 Summary: A tool for ONNX model:Rapid shape inference; Profile model; Compute Graph and Shape Engine; OPs fusion;Quantized models and sparse models are supported.
 Home-page: https://github.com/ThanatosShinji/onnx-tool
 Author: Luo Yu
 Author-email: luoyu888888@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Description-Content-Type: text/markdown
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: onnx-tool Version: 0.7.2 Summary: A tool for ONNX
+Metadata-Version: 2.1 Name: onnx-tool Version: 0.7.3 Summary: A tool for ONNX
 model:Rapid shape inference; Profile model; Compute Graph and Shape Engine; OPs
 fusion;Quantized models and sparse models are supported. Home-page: https://
 github.com/ThanatosShinji/onnx-tool Author: Luo Yu Author-email:
 luoyu888888@gmail.com License: MIT Classifier: Programming Language :: Python
 :: 3 Description-Content-Type: text/markdown License-File: LICENSE ç®ä½ä¸­æ
 # onnx-tool **A tool for ONNX model:** * *Rapid shape inference.* * *Profile
 model.* * *Constant_Folding.* * *Compute Graph and Shape Engine.* * *OPs
```

### Comparing `onnx-tool-0.7.2/setup.py` & `onnx-tool-0.7.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 #!/usr/bin/env python
 
 from setuptools import setup, find_packages
 
 readme = open("README.md", encoding="utf-8").read()
-VERSION = "0.7.2"
+VERSION = "0.7.3"
 
 requirements = [
     "onnx",
     "numpy",
     'tabulate'
 ]
```

