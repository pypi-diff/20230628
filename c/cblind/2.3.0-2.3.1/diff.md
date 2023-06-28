# Comparing `tmp/cblind-2.3.0.tar.gz` & `tmp/cblind-2.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/home/wafflarg/cblind/dist/.tmp-ftzpmct0/cblind-2.3.0.tar", last modified: Mon Jun 26 18:06:27 2023, max compression
+gzip compressed data, was "/home/wafflarg/cblind/dist/.tmp-gex2t0yo/cblind-2.3.1.tar", last modified: Wed Jun 28 09:05:12 2023, max compression
```

## Comparing `cblind-2.3.0.tar` & `cblind-2.3.1.tar`

### file list

```diff
@@ -1,31 +1,33 @@
-drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-26 18:06:27.741580 cblind-2.3.0/
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    35149 2021-02-25 19:20:47.000000 cblind-2.3.0/LICENSE
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     5163 2023-06-26 18:06:27.741580 cblind-2.3.0/PKG-INFO
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     4608 2023-06-26 18:02:41.000000 cblind-2.3.0/README.md
-drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-26 18:06:27.737580 cblind-2.3.0/cblind/
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)      395 2023-06-26 16:16:09.000000 cblind-2.3.0/cblind/__init__.py
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       22 2023-06-26 18:02:41.000000 cblind-2.3.0/cblind/__version__.py
--rwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)    28549 2023-06-26 16:16:09.000000 cblind-2.3.0/cblind/cblind.py
-drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-26 18:06:27.737580 cblind-2.3.0/cblind.egg-info/
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     5163 2023-06-26 18:06:27.000000 cblind-2.3.0/cblind.egg-info/PKG-INFO
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)      506 2023-06-26 18:06:27.000000 cblind-2.3.0/cblind.egg-info/SOURCES.txt
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)        1 2023-06-26 18:06:27.000000 cblind-2.3.0/cblind.egg-info/dependency_links.txt
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       48 2023-06-26 18:06:27.000000 cblind-2.3.0/cblind.egg-info/entry_points.txt
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       48 2023-06-26 18:06:27.000000 cblind-2.3.0/cblind.egg-info/requires.txt
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)        7 2023-06-26 18:06:27.000000 cblind-2.3.0/cblind.egg-info/top_level.txt
-drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-26 18:06:27.741580 cblind-2.3.0/imgs/
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    12412 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/bird.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    17820 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/cblind.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    20566 2021-11-30 15:53:40.000000 cblind-2.3.0/imgs/colormaps.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)      619 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/colormaps.py
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     9126 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/contrast.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    26606 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/extreme_rainbow.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    49866 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/huescale.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     1454 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/huescale.py
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    23133 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/monocolor.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    12215 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/pregunta.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    17609 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/rainbow.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    15675 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/rbscale.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    15832 2021-12-01 14:02:06.000000 cblind-2.3.0/imgs/solstice.png
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     1086 2023-06-26 16:16:09.000000 cblind-2.3.0/pyproject.toml
--rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       38 2023-06-26 18:06:27.741580 cblind-2.3.0/setup.cfg
+drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-28 09:05:12.545769 cblind-2.3.1/
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    35149 2021-02-25 19:20:47.000000 cblind-2.3.1/LICENSE
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     5107 2023-06-28 09:05:12.545769 cblind-2.3.1/PKG-INFO
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     4602 2023-06-28 09:04:53.000000 cblind-2.3.1/README.md
+drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-28 09:05:12.541769 cblind-2.3.1/cblind/
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)      395 2023-06-26 16:16:09.000000 cblind-2.3.1/cblind/__init__.py
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       22 2023-06-28 08:57:58.000000 cblind-2.3.1/cblind/__version__.py
+-rwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)    28465 2023-06-28 08:57:58.000000 cblind-2.3.1/cblind/cblind.py
+drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-28 09:05:12.541769 cblind-2.3.1/cblind.egg-info/
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     5107 2023-06-28 09:05:12.000000 cblind-2.3.1/cblind.egg-info/PKG-INFO
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)      527 2023-06-28 09:05:12.000000 cblind-2.3.1/cblind.egg-info/SOURCES.txt
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)        1 2023-06-28 09:05:12.000000 cblind-2.3.1/cblind.egg-info/dependency_links.txt
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       48 2023-06-28 09:05:12.000000 cblind-2.3.1/cblind.egg-info/entry_points.txt
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       60 2023-06-28 09:05:12.000000 cblind-2.3.1/cblind.egg-info/requires.txt
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)        7 2023-06-28 09:05:12.000000 cblind-2.3.1/cblind.egg-info/top_level.txt
+drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-28 09:05:12.545769 cblind-2.3.1/imgs/
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    12412 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/bird.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    17820 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/cblind.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    20566 2021-11-30 15:53:40.000000 cblind-2.3.1/imgs/colormaps.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)      619 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/colormaps.py
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     9126 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/contrast.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    26606 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/extreme_rainbow.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    49866 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/huescale.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     1454 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/huescale.py
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    23133 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/monocolor.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    12215 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/pregunta.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    17609 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/rainbow.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    15675 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/rbscale.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)    15832 2021-12-01 14:02:06.000000 cblind-2.3.1/imgs/solstice.png
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)     1053 2023-06-28 08:57:58.000000 cblind-2.3.1/pyproject.toml
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)       38 2023-06-28 09:05:12.545769 cblind-2.3.1/setup.cfg
+drwxrwxr-x   0 wafflarg  (1001) wafflarg  (1001)        0 2023-06-28 09:05:12.545769 cblind-2.3.1/tests/
+-rw-rw-r--   0 wafflarg  (1001) wafflarg  (1001)      303 2023-06-28 08:57:58.000000 cblind-2.3.1/tests/test_cblind.py
```

### Comparing `cblind-2.3.0/LICENSE` & `cblind-2.3.1/LICENSE`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/PKG-INFO` & `cblind-2.3.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,30 +1,28 @@
 Metadata-Version: 2.1
 Name: cblind
-Version: 2.3.0
+Version: 2.3.1
 Summary: Color schemes for Python plots, from Paul Tol (2012)
 Author: G. Wafflard-Fernandez
 License: GPL-3.0
 Project-URL: Homepage, https://github.com/volodia99/cblind
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: 3.6
-Requires-Python: >=3.6
+Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
 
 # cblind
 [![PyPI](https://img.shields.io/pypi/v/cblind)](https://pypi.org/project/cblind/)
 
 A colorblind-friendly python module that allows color choice for plotting multiple curves  
-Works only with python 3  
+Works only with python $\geq$ 3.7  
 8 colormaps are now available to map 2D fields  
-Version: 2.3.0
 Authors: Gaylor Wafflard-Fernandez, Clément Robert  
 Author-email: gaylor.wafflard@univ-grenoble-alpes.fr
 
 ## Installation
 
 Install with `pip`
```

### Comparing `cblind-2.3.0/README.md` & `cblind-2.3.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,13 @@
 # cblind
 [![PyPI](https://img.shields.io/pypi/v/cblind)](https://pypi.org/project/cblind/)
 
 A colorblind-friendly python module that allows color choice for plotting multiple curves  
-Works only with python 3  
+Works only with python $\geq$ 3.7  
 8 colormaps are now available to map 2D fields  
-Version: 2.3.0
 Authors: Gaylor Wafflard-Fernandez, Clément Robert  
 Author-email: gaylor.wafflard@univ-grenoble-alpes.fr
 
 ## Installation
 
 Install with `pip`
```

### Comparing `cblind-2.3.0/cblind/cblind.py` & `cblind-2.3.1/cblind/cblind.py`

 * *Files 0% similar despite different names*

```diff
@@ -528,32 +528,30 @@
     elif palette_tmp=="cb.iris":
         cmap_iris = ["#FEFBE9", "#FCF7D5", "#F5F3C1", "#EAF0B5", "#DDECBF", "#D0E7CA", "#C2E3D2", "#B5DDD8", "#A8D8DC", "#9BD2E1", "#8DCBE4", "#81C4E7", "#7BBCE7", "#7EB2E4", "#88A5DD", "#9398D2", "#9B8AC4", "#9D7DB2", "#9A709E", "#906388", "#805770", "#684957", "#46353A"]
         cbcmap = mcolors.LinearSegmentedColormap.from_list(f"{palette_tmp}", cmap_iris, N=nbin)
     if palette[-2:]=="_r":
         cbcmap = cbcmap.reversed()
     return(cbcmap)
 
-def cbmap(palette=None, nbin=None):
+def cbmap(palette=None, nbin=256):
     warn(
         "cblind.cbmap is deprecated. "
         "Please use matplotlib.colormaps.get_cmap instead, or "
         "matplotlib.pyplot.get_cmap if you need to specify nbin "
         "(default is 256)",
         category=DeprecationWarning,
         stacklevel=2,
     )
-    if palette not in PALETTES_FULL:
-        if nbin is None:
-            return mcm.get_cmap(palette)
-        else:
-            import matplotlib.pyplot as plt
-
-            return plt.get_cmap(palette, nbin)
-    else:
+    if palette in PALETTES_FULL:
         return _get_cbmap(palette, nbin)
+    else:
+        import matplotlib.pyplot as plt
+
+        return plt.get_cmap(palette, nbin)
+        
 
 def mapping(fig, ax, data2d, palette=None, nbin=None):
     if nbin is None:
         cmap = mcm.get_cmap(palette)
     else:
         import matplotlib.pyplot as plt
```

### Comparing `cblind-2.3.0/cblind.egg-info/PKG-INFO` & `cblind-2.3.1/cblind.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,30 +1,28 @@
 Metadata-Version: 2.1
 Name: cblind
-Version: 2.3.0
+Version: 2.3.1
 Summary: Color schemes for Python plots, from Paul Tol (2012)
 Author: G. Wafflard-Fernandez
 License: GPL-3.0
 Project-URL: Homepage, https://github.com/volodia99/cblind
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: 3.6
-Requires-Python: >=3.6
+Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
 
 # cblind
 [![PyPI](https://img.shields.io/pypi/v/cblind)](https://pypi.org/project/cblind/)
 
 A colorblind-friendly python module that allows color choice for plotting multiple curves  
-Works only with python 3  
+Works only with python $\geq$ 3.7  
 8 colormaps are now available to map 2D fields  
-Version: 2.3.0
 Authors: Gaylor Wafflard-Fernandez, Clément Robert  
 Author-email: gaylor.wafflard@univ-grenoble-alpes.fr
 
 ## Installation
 
 Install with `pip`
```

### Comparing `cblind-2.3.0/imgs/bird.png` & `cblind-2.3.1/imgs/bird.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/cblind.png` & `cblind-2.3.1/imgs/cblind.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/colormaps.png` & `cblind-2.3.1/imgs/colormaps.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/colormaps.py` & `cblind-2.3.1/imgs/colormaps.py`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/contrast.png` & `cblind-2.3.1/imgs/contrast.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/extreme_rainbow.png` & `cblind-2.3.1/imgs/extreme_rainbow.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/huescale.png` & `cblind-2.3.1/imgs/huescale.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/huescale.py` & `cblind-2.3.1/imgs/huescale.py`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/monocolor.png` & `cblind-2.3.1/imgs/monocolor.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/pregunta.png` & `cblind-2.3.1/imgs/pregunta.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/rainbow.png` & `cblind-2.3.1/imgs/rainbow.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/rbscale.png` & `cblind-2.3.1/imgs/rbscale.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/imgs/solstice.png` & `cblind-2.3.1/imgs/solstice.png`

 * *Files identical despite different names*

### Comparing `cblind-2.3.0/pyproject.toml` & `cblind-2.3.1/pyproject.toml`

 * *Files 14% similar despite different names*

```diff
@@ -10,21 +10,20 @@
 authors = [
     { name = "G. Wafflard-Fernandez" },
 ]
 classifiers = [
     "License :: OSI Approved :: GNU General Public License v3 (GPLv3)",
     "Programming Language :: Python :: 3",
     "Programming Language :: Python :: 3 :: Only",
-    "Programming Language :: Python :: 3.6",
 ]
-requires-python = ">=3.6"
+requires-python = ">=3.7"
 dependencies = [
     "matplotlib>=3.5",
-    "cycler",
-    "numpy",
+    "cycler>=0.10",
+    "numpy>=1.17",
 ]
 dynamic = ["version"]
 
 [project.readme]
 file = "README.md"
 content-type = "text/markdown"
```

