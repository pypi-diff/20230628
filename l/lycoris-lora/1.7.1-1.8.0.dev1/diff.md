# Comparing `tmp/lycoris_lora-1.7.1.tar.gz` & `tmp/lycoris_lora-1.8.0.dev1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "lycoris_lora-1.7.1.tar", last modified: Wed Jun 28 12:51:07 2023, max compression
+gzip compressed data, was "lycoris_lora-1.8.0.dev1.tar", last modified: Wed Jun 28 16:02:07 2023, max compression
```

## Comparing `lycoris_lora-1.7.1.tar` & `lycoris_lora-1.8.0.dev1.tar`

### file list

```diff
@@ -1,25 +1,16 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 12:51:07.572872 lycoris_lora-1.7.1/
--rw-rw-rw-   0        0        0    11545 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/LICENSE.md
--rw-rw-rw-   0        0        0      348 2023-06-28 12:51:07.572872 lycoris_lora-1.7.1/PKG-INFO
--rw-rw-rw-   0        0        0     7677 2023-06-28 12:51:02.000000 lycoris_lora-1.7.1/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 12:51:07.559910 lycoris_lora-1.7.1/lycoris/
--rw-rw-rw-   0        0        0      113 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/__init__.py
--rw-rw-rw-   0        0        0     6258 2023-06-28 09:12:31.000000 lycoris_lora-1.7.1/lycoris/dylora.py
--rw-rw-rw-   0        0        0     4099 2023-06-28 11:53:14.000000 lycoris_lora-1.7.1/lycoris/glora.py
--rw-rw-rw-   0        0        0     2103 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/ia3.py
--rw-rw-rw-   0        0        0    23863 2023-06-28 12:48:17.000000 lycoris_lora-1.7.1/lycoris/kohya.py
--rw-rw-rw-   0        0        0    48868 2023-06-15 09:10:55.000000 lycoris_lora-1.7.1/lycoris/kohya_model_utils.py
--rw-rw-rw-   0        0        0     1512 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/kohya_utils.py
--rw-rw-rw-   0        0        0     4468 2023-06-28 12:46:54.000000 lycoris_lora-1.7.1/lycoris/locon.py
--rw-rw-rw-   0        0        0     8831 2023-06-28 12:47:04.000000 lycoris_lora-1.7.1/lycoris/loha.py
--rw-rw-rw-   0        0        0    10856 2023-06-28 12:47:14.000000 lycoris_lora-1.7.1/lycoris/lokr.py
--rw-rw-rw-   0        0        0    20963 2023-06-04 13:36:43.000000 lycoris_lora-1.7.1/lycoris/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:51:07.570878 lycoris_lora-1.7.1/lycoris_lora.egg-info/
--rw-rw-rw-   0        0        0      348 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      448 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        2 2023-06-04 13:39:16.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0       41 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/requires.txt
--rw-rw-rw-   0        0        0        8 2023-06-28 12:51:07.000000 lycoris_lora-1.7.1/lycoris_lora.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 12:51:07.572872 lycoris_lora-1.7.1/setup.cfg
--rw-rw-rw-   0        0        0      542 2023-06-28 12:51:05.000000 lycoris_lora-1.7.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 16:02:07.801101 lycoris_lora-1.8.0.dev1/
+-rw-rw-rw-   0        0        0    11545 2023-06-04 13:36:43.000000 lycoris_lora-1.8.0.dev1/LICENSE.md
+-rw-rw-rw-   0        0        0      353 2023-06-28 16:02:07.801101 lycoris_lora-1.8.0.dev1/PKG-INFO
+-rw-rw-rw-   0        0        0     7677 2023-06-28 12:51:02.000000 lycoris_lora-1.8.0.dev1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 16:02:07.785065 lycoris_lora-1.8.0.dev1/lycoris/
+-rw-rw-rw-   0        0        0       62 2023-06-28 13:25:50.000000 lycoris_lora-1.8.0.dev1/lycoris/__init__.py
+-rw-rw-rw-   0        0        0    20963 2023-06-04 13:36:43.000000 lycoris_lora-1.8.0.dev1/lycoris/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 16:02:07.800101 lycoris_lora-1.8.0.dev1/lycoris_lora.egg-info/
+-rw-rw-rw-   0        0        0      353 2023-06-28 16:02:07.000000 lycoris_lora-1.8.0.dev1/lycoris_lora.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      280 2023-06-28 16:02:07.000000 lycoris_lora-1.8.0.dev1/lycoris_lora.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 16:02:07.000000 lycoris_lora-1.8.0.dev1/lycoris_lora.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        2 2023-06-04 13:39:16.000000 lycoris_lora-1.8.0.dev1/lycoris_lora.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0       41 2023-06-28 16:02:07.000000 lycoris_lora-1.8.0.dev1/lycoris_lora.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        8 2023-06-28 16:02:07.000000 lycoris_lora-1.8.0.dev1/lycoris_lora.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 16:02:07.802101 lycoris_lora-1.8.0.dev1/setup.cfg
+-rw-rw-rw-   0        0        0      547 2023-06-28 13:21:49.000000 lycoris_lora-1.8.0.dev1/setup.py
```

### Comparing `lycoris_lora-1.7.1/LICENSE.md` & `lycoris_lora-1.8.0.dev1/LICENSE.md`

 * *Files identical despite different names*

### Comparing `lycoris_lora-1.7.1/README.md` & `lycoris_lora-1.8.0.dev1/README.md`

 * *Files identical despite different names*

### Comparing `lycoris_lora-1.7.1/lycoris/utils.py` & `lycoris_lora-1.8.0.dev1/lycoris/utils.py`

 * *Files identical despite different names*

### Comparing `lycoris_lora-1.7.1/setup.py` & `lycoris_lora-1.8.0.dev1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import setup
 
 setup(
     name='lycoris_lora',
     packages=['lycoris'],
-    version='1.7.1',
+    version='1.8.0.dev1',
     url='https://github.com/KohakuBlueleaf/LyCORIS',
     description='Lora beYond Conventional methods, Other Rank adaptation Implementations for Stable diffusion',
     author='Shih-Ying Yeh(KohakuBlueLeaf), Yu-Guan Hsieh, Zhidong Gao',
     author_email='apolloyeh0123@gmail.com',
     zip_safe=False,
     install_requires=[
         'torch',
```

