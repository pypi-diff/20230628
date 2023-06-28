# Comparing `tmp/lifetimefitting-0.0.27.tar.gz` & `tmp/lifetimefitting-0.0.28.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "lifetimefitting-0.0.27.tar", last modified: Wed Jun 28 03:15:22 2023, max compression
+gzip compressed data, was "lifetimefitting-0.0.28.tar", last modified: Wed Jun 28 03:19:56 2023, max compression
```

## Comparing `lifetimefitting-0.0.27.tar` & `lifetimefitting-0.0.28.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:15:22.542027 lifetimefitting-0.0.27/
--rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/LICENSE.md
--rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 03:15:22.542027 lifetimefitting-0.0.27/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:15:22.542027 lifetimefitting-0.0.27/app/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:15:22.542027 lifetimefitting-0.0.27/app/lifetimefitting/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/app/lifetimefitting/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3710 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/app/lifetimefitting/__main__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:15:22.542027 lifetimefitting-0.0.27/app/lifetimefitting/funcs/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/app/lifetimefitting/funcs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2680 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/app/lifetimefitting/funcs/expFuncs.py
--rw-r--r--   0 runner    (1001) docker     (123)     7173 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/app/lifetimefitting/funcs/fittingFuncs.py
--rw-r--r--   0 runner    (1001) docker     (123)    12735 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/app/lifetimefitting/funcs/gui.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:15:22.542027 lifetimefitting-0.0.27/app/lifetimefitting.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 03:15:22.000000 lifetimefitting-0.0.27/app/lifetimefitting.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 03:15:22.000000 lifetimefitting-0.0.27/app/lifetimefitting.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 03:15:22.000000 lifetimefitting-0.0.27/app/lifetimefitting.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 03:15:22.000000 lifetimefitting-0.0.27/app/lifetimefitting.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-28 03:15:22.000000 lifetimefitting-0.0.27/app/lifetimefitting.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 03:15:22.542027 lifetimefitting-0.0.27/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      890 2023-06-28 03:15:12.000000 lifetimefitting-0.0.27/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:19:56.812430 lifetimefitting-0.0.28/
+-rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/LICENSE.md
+-rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 03:19:56.812430 lifetimefitting-0.0.28/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:19:56.812430 lifetimefitting-0.0.28/app/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:19:56.812430 lifetimefitting-0.0.28/app/lifetimefitting/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/app/lifetimefitting/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3716 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/app/lifetimefitting/__main__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:19:56.812430 lifetimefitting-0.0.28/app/lifetimefitting/funcs/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/app/lifetimefitting/funcs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2680 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/app/lifetimefitting/funcs/expFuncs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7173 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/app/lifetimefitting/funcs/fittingFuncs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12735 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/app/lifetimefitting/funcs/gui.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:19:56.812430 lifetimefitting-0.0.28/app/lifetimefitting.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 03:19:56.000000 lifetimefitting-0.0.28/app/lifetimefitting.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 03:19:56.000000 lifetimefitting-0.0.28/app/lifetimefitting.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 03:19:56.000000 lifetimefitting-0.0.28/app/lifetimefitting.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 03:19:56.000000 lifetimefitting-0.0.28/app/lifetimefitting.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-28 03:19:56.000000 lifetimefitting-0.0.28/app/lifetimefitting.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 03:19:56.812430 lifetimefitting-0.0.28/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      890 2023-06-28 03:19:45.000000 lifetimefitting-0.0.28/setup.py
```

### Comparing `lifetimefitting-0.0.27/LICENSE.md` & `lifetimefitting-0.0.28/LICENSE.md`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.27/PKG-INFO` & `lifetimefitting-0.0.28/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lifetimefitting
-Version: 0.0.27
+Version: 0.0.28
 Summary: PicoHarp TCSPC lifetime fitting tool
 Home-page: https://github.com/adreasnow/LifetimeFittingTool
 Author: Adrea Snow
 Author-email: adrea.snow@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `lifetimefitting-0.0.27/README.md` & `lifetimefitting-0.0.28/README.md`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.27/app/lifetimefitting/__main__.py` & `lifetimefitting-0.0.28/app/lifetimefitting/__main__.py`

 * *Files 0% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 from pathlib import Path
 from .funcs.fittingFuncs import loadAndCull, fitFL
 import sys
 
 class Ui(QMainWindow):
     def __init__(self) -> None:
         super(Ui, self).__init__()
-        uic.loadUi(f'{Path(__file__).parent.resolve()}/lifetimeGui.ui', self)
+        uic.loadUi(f'{Path(__file__).parent.resolve()}/funcs/lifetimeGui.ui', self)
         self.show()
 
 def plotFL() -> None:
     global csv
     plt.close('all')
     for i in ui.axList:
         i.remove()
```

### Comparing `lifetimefitting-0.0.27/app/lifetimefitting/funcs/expFuncs.py` & `lifetimefitting-0.0.28/app/lifetimefitting/funcs/expFuncs.py`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.27/app/lifetimefitting/funcs/fittingFuncs.py` & `lifetimefitting-0.0.28/app/lifetimefitting/funcs/fittingFuncs.py`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.27/app/lifetimefitting/funcs/gui.py` & `lifetimefitting-0.0.28/app/lifetimefitting/funcs/gui.py`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.27/app/lifetimefitting.egg-info/PKG-INFO` & `lifetimefitting-0.0.28/app/lifetimefitting.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lifetimefitting
-Version: 0.0.27
+Version: 0.0.28
 Summary: PicoHarp TCSPC lifetime fitting tool
 Home-page: https://github.com/adreasnow/LifetimeFittingTool
 Author: Adrea Snow
 Author-email: adrea.snow@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `lifetimefitting-0.0.27/setup.py` & `lifetimefitting-0.0.28/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import find_packages, setup
 
 with open("README.md", "r", encoding = "utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name = "lifetimefitting",
-    version = "0.0.27",
+    version = "0.0.28",
     author = "Adrea Snow",
     author_email = "adrea.snow@gmail.com",
     description = "PicoHarp TCSPC lifetime fitting tool",
     long_description = long_description,
     long_description_content_type = "text/markdown",
     url = "https://github.com/adreasnow/LifetimeFittingTool",
     classifiers = [
```

