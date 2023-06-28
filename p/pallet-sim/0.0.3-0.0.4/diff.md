# Comparing `tmp/pallet_sim-0.0.3.tar.gz` & `tmp/pallet_sim-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pallet_sim-0.0.3.tar", last modified: Wed Jun 28 12:17:43 2023, max compression
+gzip compressed data, was "pallet_sim-0.0.4.tar", last modified: Wed Jun 28 12:28:34 2023, max compression
```

## Comparing `pallet_sim-0.0.3.tar` & `pallet_sim-0.0.4.tar`

### file list

```diff
@@ -1,23 +1,30 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 12:17:43.701164 pallet_sim-0.0.3/
--rw-rw-rw-   0        0        0        0 2023-06-28 12:17:16.000000 pallet_sim-0.0.3/LICENSE
--rw-rw-rw-   0        0        0      503 2023-06-28 12:17:43.700951 pallet_sim-0.0.3/PKG-INFO
--rw-rw-rw-   0        0        0        0 2023-06-28 12:17:07.000000 pallet_sim-0.0.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 12:17:43.654223 pallet_sim-0.0.3/pallet_sim/
--rw-rw-rw-   0        0        0        0 2023-06-28 07:21:49.000000 pallet_sim-0.0.3/pallet_sim/__init__.py
--rw-rw-rw-   0        0        0     3226 2022-12-16 15:46:46.000000 pallet_sim-0.0.3/pallet_sim/mujocoviewer.py
--rw-rw-rw-   0        0        0    22982 2023-05-23 11:27:55.000000 pallet_sim-0.0.3/pallet_sim/order.py
--rw-rw-rw-   0        0        0    40254 2023-05-23 11:23:07.000000 pallet_sim-0.0.3/pallet_sim/pallet_sim.py
--rw-rw-rw-   0        0        0     2049 2023-05-04 01:34:32.000000 pallet_sim-0.0.3/pallet_sim/pallet_visualizer.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:17:43.698167 pallet_sim-0.0.3/pallet_sim/textures/
--rw-rw-rw-   0        0        0   330084 2022-12-08 12:02:12.000000 pallet_sim-0.0.3/pallet_sim/textures/Duesseldorfer_Pallet.stl
--rw-rw-rw-   0        0        0   330084 2022-12-17 14:51:07.000000 pallet_sim-0.0.3/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl
--rw-rw-rw-   0        0        0   300084 2022-12-08 12:02:12.000000 pallet_sim-0.0.3/pallet_sim/textures/Euro_Pallet.stl
--rw-rw-rw-   0        0        0   300084 2022-12-17 14:51:07.000000 pallet_sim-0.0.3/pallet_sim/textures/Euro_Pallet_Rotated.stl
--rw-rw-rw-   0        0        0     6470 2023-03-27 22:24:18.000000 pallet_sim-0.0.3/pallet_sim/xml_obfuscator.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:17:43.670932 pallet_sim-0.0.3/pallet_sim.egg-info/
--rw-rw-rw-   0        0        0      503 2023-06-28 12:17:43.000000 pallet_sim-0.0.3/pallet_sim.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      496 2023-06-28 12:17:43.000000 pallet_sim-0.0.3/pallet_sim.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 12:17:43.000000 pallet_sim-0.0.3/pallet_sim.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       11 2023-06-28 12:17:43.000000 pallet_sim-0.0.3/pallet_sim.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 12:17:43.701164 pallet_sim-0.0.3/setup.cfg
--rw-rw-rw-   0        0        0      868 2023-06-28 12:14:40.000000 pallet_sim-0.0.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:34.851071 pallet_sim-0.0.4/
+-rw-rw-rw-   0        0        0        0 2023-06-28 12:17:16.000000 pallet_sim-0.0.4/LICENSE
+-rw-rw-rw-   0        0        0      503 2023-06-28 12:28:34.850374 pallet_sim-0.0.4/PKG-INFO
+-rw-rw-rw-   0        0        0        0 2023-06-28 12:17:07.000000 pallet_sim-0.0.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:34.801216 pallet_sim-0.0.4/pallet_sim/
+-rw-rw-rw-   0        0        0        0 2023-06-28 07:21:49.000000 pallet_sim-0.0.4/pallet_sim/__init__.py
+-rw-rw-rw-   0        0        0     3226 2022-12-16 15:46:46.000000 pallet_sim-0.0.4/pallet_sim/mujocoviewer.py
+-rw-rw-rw-   0        0        0    22982 2023-05-23 11:27:55.000000 pallet_sim-0.0.4/pallet_sim/order.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:34.836689 pallet_sim-0.0.4/pallet_sim/pallet_generator2D/
+-rw-rw-rw-   0        0        0        0 2023-06-28 07:21:49.000000 pallet_sim-0.0.4/pallet_sim/pallet_generator2D/__init__.py
+-rw-rw-rw-   0        0        0   293781 2022-12-22 15:37:07.000000 pallet_sim-0.0.4/pallet_sim/pallet_generator2D/box_offset.py
+-rw-rw-rw-   0        0        0     4228 2022-12-22 15:37:26.000000 pallet_sim-0.0.4/pallet_sim/pallet_generator2D/boxprocessing.py
+-rw-rw-rw-   0        0        0     6331 2023-03-17 11:30:24.000000 pallet_sim-0.0.4/pallet_sim/pallet_generator2D/g4algorithm.py
+-rw-rw-rw-   0        0        0      945 2022-12-22 15:44:58.000000 pallet_sim-0.0.4/pallet_sim/pallet_generator2D/lists.py
+-rw-rw-rw-   0        0        0     5083 2022-12-22 15:37:13.000000 pallet_sim-0.0.4/pallet_sim/pallet_generator2D/overlapp.py
+-rw-rw-rw-   0        0        0    40254 2023-05-23 11:23:07.000000 pallet_sim-0.0.4/pallet_sim/pallet_sim.py
+-rw-rw-rw-   0        0        0     2049 2023-05-04 01:34:32.000000 pallet_sim-0.0.4/pallet_sim/pallet_visualizer.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:34.848081 pallet_sim-0.0.4/pallet_sim/textures/
+-rw-rw-rw-   0        0        0   330084 2022-12-08 12:02:12.000000 pallet_sim-0.0.4/pallet_sim/textures/Duesseldorfer_Pallet.stl
+-rw-rw-rw-   0        0        0   330084 2022-12-17 14:51:07.000000 pallet_sim-0.0.4/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl
+-rw-rw-rw-   0        0        0   300084 2022-12-08 12:02:12.000000 pallet_sim-0.0.4/pallet_sim/textures/Euro_Pallet.stl
+-rw-rw-rw-   0        0        0   300084 2022-12-17 14:51:07.000000 pallet_sim-0.0.4/pallet_sim/textures/Euro_Pallet_Rotated.stl
+-rw-rw-rw-   0        0        0     6470 2023-03-27 22:24:18.000000 pallet_sim-0.0.4/pallet_sim/xml_obfuscator.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:34.813675 pallet_sim-0.0.4/pallet_sim.egg-info/
+-rw-rw-rw-   0        0        0      503 2023-06-28 12:28:34.000000 pallet_sim-0.0.4/pallet_sim.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      755 2023-06-28 12:28:34.000000 pallet_sim-0.0.4/pallet_sim.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:28:34.000000 pallet_sim-0.0.4/pallet_sim.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 12:28:34.000000 pallet_sim-0.0.4/pallet_sim.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:28:34.851263 pallet_sim-0.0.4/setup.cfg
+-rw-rw-rw-   0        0        0      868 2023-06-28 12:28:29.000000 pallet_sim-0.0.4/setup.py
```

### Comparing `pallet_sim-0.0.3/pallet_sim/mujocoviewer.py` & `pallet_sim-0.0.4/pallet_sim/mujocoviewer.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/order.py` & `pallet_sim-0.0.4/pallet_sim/order.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/pallet_sim.py` & `pallet_sim-0.0.4/pallet_sim/pallet_sim.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/pallet_visualizer.py` & `pallet_sim-0.0.4/pallet_sim/pallet_visualizer.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/textures/Duesseldorfer_Pallet.stl` & `pallet_sim-0.0.4/pallet_sim/textures/Duesseldorfer_Pallet.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl` & `pallet_sim-0.0.4/pallet_sim/textures/Duesseldorfer_Pallet_Rotated.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/textures/Euro_Pallet.stl` & `pallet_sim-0.0.4/pallet_sim/textures/Euro_Pallet.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/textures/Euro_Pallet_Rotated.stl` & `pallet_sim-0.0.4/pallet_sim/textures/Euro_Pallet_Rotated.stl`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/pallet_sim/xml_obfuscator.py` & `pallet_sim-0.0.4/pallet_sim/xml_obfuscator.py`

 * *Files identical despite different names*

### Comparing `pallet_sim-0.0.3/setup.py` & `pallet_sim-0.0.4/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name='pallet_sim',
-    version='0.0.3',
+    version='0.0.4',
     author='Rodolfo Verde',
     description='Pallet simulation library developed at THWS',
     long_description=open('README.md').read(),
     long_description_content_type='text/markdown',
     packages=find_packages(),
     package_data={
         'pallet_sim': ['textures/*.stl'],
```

