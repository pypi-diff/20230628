# Comparing `tmp/pallet_sim-0.0.7.tar.gz` & `tmp/pallet_sim-0.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pallet_sim-0.0.7.tar", last modified: Wed Jun 28 12:55:08 2023, max compression
+gzip compressed data, was "pallet_sim-0.0.8.tar", last modified: Wed Jun 28 12:57:38 2023, max compression
```

## Comparing `pallet_sim-0.0.7.tar` & `pallet_sim-0.0.8.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 12:55:08.697856 pallet_sim-0.0.7/
--rw-rw-rw-   0        0        0        0 2023-06-28 12:17:16.000000 pallet_sim-0.0.7/LICENSE
--rw-rw-rw-   0        0        0      503 2023-06-28 12:55:08.697162 pallet_sim-0.0.7/PKG-INFO
--rw-rw-rw-   0        0        0        0 2023-06-28 12:17:07.000000 pallet_sim-0.0.7/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 12:55:08.656582 pallet_sim-0.0.7/pallet_sim/
--rw-rw-rw-   0        0        0      136 2023-06-28 12:54:43.000000 pallet_sim-0.0.7/pallet_sim/__init__.py
--rw-rw-rw-   0        0        0     3226 2022-12-16 15:46:46.000000 pallet_sim-0.0.7/pallet_sim/mujocoviewer.py
--rw-rw-rw-   0        0        0    22982 2023-05-23 11:27:55.000000 pallet_sim-0.0.7/pallet_sim/order.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:55:08.686736 pallet_sim-0.0.7/pallet_sim/pallet_generator2D/
--rw-rw-rw-   0        0        0        0 2023-06-28 07:21:49.000000 pallet_sim-0.0.7/pallet_sim/pallet_generator2D/__init__.py
--rw-rw-rw-   0        0        0   293781 2022-12-22 15:37:07.000000 pallet_sim-0.0.7/pallet_sim/pallet_generator2D/box_offset.py
--rw-rw-rw-   0        0        0     4228 2022-12-22 15:37:26.000000 pallet_sim-0.0.7/pallet_sim/pallet_generator2D/boxprocessing.py
--rw-rw-rw-   0        0        0     6331 2023-03-17 11:30:24.000000 pallet_sim-0.0.7/pallet_sim/pallet_generator2D/g4algorithm.py
--rw-rw-rw-   0        0        0      945 2022-12-22 15:44:58.000000 pallet_sim-0.0.7/pallet_sim/pallet_generator2D/lists.py
--rw-rw-rw-   0        0        0     5083 2022-12-22 15:37:13.000000 pallet_sim-0.0.7/pallet_sim/pallet_generator2D/overlapp.py
--rw-rw-rw-   0        0        0    40254 2023-05-23 11:23:07.000000 pallet_sim-0.0.7/pallet_sim/pallet_sim.py
--rw-rw-rw-   0        0        0     2049 2023-05-04 01:34:32.000000 pallet_sim-0.0.7/pallet_sim/pallet_visualizer.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:55:08.694941 pallet_sim-0.0.7/pallet_sim/textures/
--rw-rw-rw-   0        0        0   330084 2022-12-08 12:02:12.000000 pallet_sim-0.0.7/pallet_sim/textures/Duesseldorfer_Pallet.stl
--rw-rw-rw-   0        0        0   330084 2022-12-17 14:51:07.000000 pallet_sim-0.0.7/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl
--rw-rw-rw-   0        0        0   300084 2022-12-08 12:02:12.000000 pallet_sim-0.0.7/pallet_sim/textures/Euro_Pallet.stl
--rw-rw-rw-   0        0        0   300084 2022-12-17 14:51:07.000000 pallet_sim-0.0.7/pallet_sim/textures/Euro_Pallet_Rotated.stl
--rw-rw-rw-   0        0        0     6470 2023-03-27 22:24:18.000000 pallet_sim-0.0.7/pallet_sim/xml_obfuscator.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:55:08.676393 pallet_sim-0.0.7/pallet_sim.egg-info/
--rw-rw-rw-   0        0        0      503 2023-06-28 12:55:08.000000 pallet_sim-0.0.7/pallet_sim.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      788 2023-06-28 12:55:08.000000 pallet_sim-0.0.7/pallet_sim.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 12:55:08.000000 pallet_sim-0.0.7/pallet_sim.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       62 2023-06-28 12:55:08.000000 pallet_sim-0.0.7/pallet_sim.egg-info/requires.txt
--rw-rw-rw-   0        0        0       11 2023-06-28 12:55:08.000000 pallet_sim-0.0.7/pallet_sim.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 12:55:08.698543 pallet_sim-0.0.7/setup.cfg
--rw-rw-rw-   0        0        0     1001 2023-06-28 12:55:04.000000 pallet_sim-0.0.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:57:38.862993 pallet_sim-0.0.8/
+-rw-rw-rw-   0        0        0        0 2023-06-28 12:17:16.000000 pallet_sim-0.0.8/LICENSE
+-rw-rw-rw-   0        0        0      503 2023-06-28 12:57:38.862673 pallet_sim-0.0.8/PKG-INFO
+-rw-rw-rw-   0        0        0        0 2023-06-28 12:17:07.000000 pallet_sim-0.0.8/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:57:38.829798 pallet_sim-0.0.8/pallet_sim/
+-rw-rw-rw-   0        0        0       24 2023-06-28 12:56:34.000000 pallet_sim-0.0.8/pallet_sim/__init__.py
+-rw-rw-rw-   0        0        0     3226 2022-12-16 15:46:46.000000 pallet_sim-0.0.8/pallet_sim/mujocoviewer.py
+-rw-rw-rw-   0        0        0    22983 2023-06-28 12:57:24.000000 pallet_sim-0.0.8/pallet_sim/order.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:57:38.851239 pallet_sim-0.0.8/pallet_sim/pallet_generator2D/
+-rw-rw-rw-   0        0        0        0 2023-06-28 07:21:49.000000 pallet_sim-0.0.8/pallet_sim/pallet_generator2D/__init__.py
+-rw-rw-rw-   0        0        0   293781 2022-12-22 15:37:07.000000 pallet_sim-0.0.8/pallet_sim/pallet_generator2D/box_offset.py
+-rw-rw-rw-   0        0        0     4228 2022-12-22 15:37:26.000000 pallet_sim-0.0.8/pallet_sim/pallet_generator2D/boxprocessing.py
+-rw-rw-rw-   0        0        0     6331 2023-03-17 11:30:24.000000 pallet_sim-0.0.8/pallet_sim/pallet_generator2D/g4algorithm.py
+-rw-rw-rw-   0        0        0      945 2022-12-22 15:44:58.000000 pallet_sim-0.0.8/pallet_sim/pallet_generator2D/lists.py
+-rw-rw-rw-   0        0        0     5083 2022-12-22 15:37:13.000000 pallet_sim-0.0.8/pallet_sim/pallet_generator2D/overlapp.py
+-rw-rw-rw-   0        0        0    40257 2023-06-28 12:57:14.000000 pallet_sim-0.0.8/pallet_sim/pallet_sim.py
+-rw-rw-rw-   0        0        0     2049 2023-05-04 01:34:32.000000 pallet_sim-0.0.8/pallet_sim/pallet_visualizer.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:57:38.860119 pallet_sim-0.0.8/pallet_sim/textures/
+-rw-rw-rw-   0        0        0   330084 2022-12-08 12:02:12.000000 pallet_sim-0.0.8/pallet_sim/textures/Duesseldorfer_Pallet.stl
+-rw-rw-rw-   0        0        0   330084 2022-12-17 14:51:07.000000 pallet_sim-0.0.8/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl
+-rw-rw-rw-   0        0        0   300084 2022-12-08 12:02:12.000000 pallet_sim-0.0.8/pallet_sim/textures/Euro_Pallet.stl
+-rw-rw-rw-   0        0        0   300084 2022-12-17 14:51:07.000000 pallet_sim-0.0.8/pallet_sim/textures/Euro_Pallet_Rotated.stl
+-rw-rw-rw-   0        0        0     6470 2023-03-27 22:24:18.000000 pallet_sim-0.0.8/pallet_sim/xml_obfuscator.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:57:38.842446 pallet_sim-0.0.8/pallet_sim.egg-info/
+-rw-rw-rw-   0        0        0      503 2023-06-28 12:57:38.000000 pallet_sim-0.0.8/pallet_sim.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      788 2023-06-28 12:57:38.000000 pallet_sim-0.0.8/pallet_sim.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:57:38.000000 pallet_sim-0.0.8/pallet_sim.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       62 2023-06-28 12:57:38.000000 pallet_sim-0.0.8/pallet_sim.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 12:57:38.000000 pallet_sim-0.0.8/pallet_sim.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:57:38.862993 pallet_sim-0.0.8/setup.cfg
+-rw-rw-rw-   0        0        0     1001 2023-06-28 12:57:35.000000 pallet_sim-0.0.8/setup.py
```

### Comparing `pallet_sim-0.0.7/pallet_sim/mujocoviewer.py` & `pallet_sim-0.0.8/pallet_sim/mujocoviewer.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/order.py` & `pallet_sim-0.0.8/pallet_sim/order.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import copy
 import json
 import os
 import random
 from xml.dom.minidom import parseString
 import numpy as np
 import stl
-from xml_obfuscator import obfuscate_xml
+from .xml_obfuscator import obfuscate_xml
 
 
 # class for handling an order, loading the data and generating the models in different formats (mujoco,
 # pybullet) initialization requires a path to a .pal.xml file (and there to exists an ord.xml file on the same path)
 # or a json string that contains the following keys: pallet, article an and optinal orderID. the class
 # can be used to generate a mujoco model, a pybullet model and a json string with the model data and article data it
 # is primarily used by the pallet simulator to get the input data for the simulation
```

### Comparing `pallet_sim-0.0.7/pallet_sim/pallet_generator2D/box_offset.py` & `pallet_sim-0.0.8/pallet_sim/pallet_generator2D/box_offset.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/pallet_generator2D/boxprocessing.py` & `pallet_sim-0.0.8/pallet_sim/pallet_generator2D/boxprocessing.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/pallet_generator2D/g4algorithm.py` & `pallet_sim-0.0.8/pallet_sim/pallet_generator2D/g4algorithm.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/pallet_generator2D/lists.py` & `pallet_sim-0.0.8/pallet_sim/pallet_generator2D/lists.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/pallet_generator2D/overlapp.py` & `pallet_sim-0.0.8/pallet_sim/pallet_generator2D/overlapp.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/pallet_sim.py` & `pallet_sim-0.0.8/pallet_sim/pallet_sim.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 import copy
 import os
 import time
+import threading
 
 import mujoco
 import pybullet
-import threading
 import mujoco_viewer
 import pybullet_utils.bullet_client as bc
 
-from mujocoviewer import MujocoViewer
-from order import Order
-import pallet_visualizer
+from .mujocoviewer import MujocoViewer
+from .order import Order
+import .pallet_visualizer
 
 
 # main class to run the simulation and preform the tests passed by the user this class is threadable and can run the
 # simulation and the tests in different threads it supports 2 physics engines: mujoco and pybullet after loading
 # using the load_order function, the user can run the simulation using the run_simulation function. additional
 # functions are available to change the physics engine, the pallets and tests threads,
 # and the callback function for images and loop callback
```

### Comparing `pallet_sim-0.0.7/pallet_sim/pallet_visualizer.py` & `pallet_sim-0.0.8/pallet_sim/pallet_visualizer.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/textures/Duesseldorfer_Pallet.stl` & `pallet_sim-0.0.8/pallet_sim/textures/Duesseldorfer_Pallet.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl` & `pallet_sim-0.0.8/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/textures/Euro_Pallet.stl` & `pallet_sim-0.0.8/pallet_sim/textures/Euro_Pallet.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/textures/Euro_Pallet_Rotated.stl` & `pallet_sim-0.0.8/pallet_sim/textures/Euro_Pallet_Rotated.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim/xml_obfuscator.py` & `pallet_sim-0.0.8/pallet_sim/xml_obfuscator.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/pallet_sim.egg-info/SOURCES.txt` & `pallet_sim-0.0.8/pallet_sim.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.7/setup.py` & `pallet_sim-0.0.8/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name='pallet_sim',
-    version='0.0.7',
+    version='0.0.8',
     author='Rodolfo Verde',
     description='Pallet simulation library developed at THWS',
     long_description=open('README.md').read(),
     long_description_content_type='text/markdown',
     packages=find_packages(),
     package_data={
         'pallet_sim': ['textures/*.stl'],
```

