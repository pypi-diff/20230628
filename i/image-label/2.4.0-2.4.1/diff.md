# Comparing `tmp/image_label-2.4.0.tar.gz` & `tmp/image_label-2.4.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "image_label-2.4.0.tar", last modified: Wed Jun 28 07:54:00 2023, max compression
+gzip compressed data, was "image_label-2.4.1.tar", last modified: Wed Jun 28 07:55:51 2023, max compression
```

## Comparing `image_label-2.4.0.tar` & `image_label-2.4.1.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.204639 image_label-2.4.0/
--rw-rw-r--   0 sks       (1000) sks       (1000)     1063 2023-06-27 05:51:46.000000 image_label-2.4.0/LICENSE
--rw-rw-r--   0 sks       (1000) sks       (1000)       47 2023-06-27 12:56:47.000000 image_label-2.4.0/MANIFEST.in
--rw-rw-r--   0 sks       (1000) sks       (1000)      345 2023-06-28 07:54:00.204639 image_label-2.4.0/PKG-INFO
--rw-rw-r--   0 sks       (1000) sks       (1000)     3594 2023-06-28 07:51:23.000000 image_label-2.4.0/README.md
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.196639 image_label-2.4.0/image_label/
--rw-rw-r--   0 sks       (1000) sks       (1000)     5768 2023-06-28 06:32:15.000000 image_label-2.4.0/image_label/__init__.py
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.192638 image_label-2.4.0/image_label/frontend/
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.196639 image_label-2.4.0/image_label/frontend/build/
--rw-rw-r--   0 sks       (1000) sks       (1000)      879 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/asset-manifest.json
--rw-rw-r--   0 sks       (1000) sks       (1000)   197459 2023-06-27 20:47:52.000000 image_label-2.4.0/image_label/frontend/build/bootstrap.min.css
--rw-rw-r--   0 sks       (1000) sks       (1000)     2168 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/index.html
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.196639 image_label-2.4.0/image_label/frontend/build/static/
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.200639 image_label-2.4.0/image_label/frontend/build/static/css/
--rw-rw-r--   0 sks       (1000) sks       (1000)     1505 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/css/main.459970d8.chunk.css
--rw-rw-r--   0 sks       (1000) sks       (1000)     3311 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/css/main.459970d8.chunk.css.map
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.204639 image_label-2.4.0/image_label/frontend/build/static/js/
--rw-rw-r--   0 sks       (1000) sks       (1000)   533439 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/js/2.d24733fb.chunk.js
--rw-rw-r--   0 sks       (1000) sks       (1000)     2284 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/js/2.d24733fb.chunk.js.LICENSE.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)  1907895 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/js/2.d24733fb.chunk.js.map
--rw-rw-r--   0 sks       (1000) sks       (1000)     4747 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js
--rw-rw-r--   0 sks       (1000) sks       (1000)    20614 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js.map
--rw-rw-r--   0 sks       (1000) sks       (1000)     1598 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/js/runtime-main.657b0728.js
--rw-rw-r--   0 sks       (1000) sks       (1000)     8383 2023-06-27 20:48:03.000000 image_label-2.4.0/image_label/frontend/build/static/js/runtime-main.657b0728.js.map
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:54:00.196639 image_label-2.4.0/image_label.egg-info/
--rw-rw-r--   0 sks       (1000) sks       (1000)      345 2023-06-28 07:54:00.000000 image_label-2.4.0/image_label.egg-info/PKG-INFO
--rw-rw-r--   0 sks       (1000) sks       (1000)      933 2023-06-28 07:54:00.000000 image_label-2.4.0/image_label.egg-info/SOURCES.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)        1 2023-06-28 07:54:00.000000 image_label-2.4.0/image_label.egg-info/dependency_links.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)       16 2023-06-28 07:54:00.000000 image_label-2.4.0/image_label.egg-info/requires.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)       12 2023-06-28 07:54:00.000000 image_label-2.4.0/image_label.egg-info/top_level.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)       38 2023-06-28 07:54:00.204639 image_label-2.4.0/setup.cfg
--rw-rw-r--   0 sks       (1000) sks       (1000)      716 2023-06-28 07:53:52.000000 image_label-2.4.0/setup.py
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:51.001154 image_label-2.4.1/
+-rw-rw-r--   0 sks       (1000) sks       (1000)     1063 2023-06-27 05:51:46.000000 image_label-2.4.1/LICENSE
+-rw-rw-r--   0 sks       (1000) sks       (1000)       47 2023-06-27 12:56:47.000000 image_label-2.4.1/MANIFEST.in
+-rw-rw-r--   0 sks       (1000) sks       (1000)      599 2023-06-28 07:55:50.997154 image_label-2.4.1/PKG-INFO
+-rw-rw-r--   0 sks       (1000) sks       (1000)     3594 2023-06-28 07:51:23.000000 image_label-2.4.1/README.md
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.989153 image_label-2.4.1/image_label/
+-rw-rw-r--   0 sks       (1000) sks       (1000)     5768 2023-06-28 06:32:15.000000 image_label-2.4.1/image_label/__init__.py
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.989153 image_label-2.4.1/image_label/frontend/
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.993153 image_label-2.4.1/image_label/frontend/build/
+-rw-rw-r--   0 sks       (1000) sks       (1000)      879 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/asset-manifest.json
+-rw-rw-r--   0 sks       (1000) sks       (1000)   197459 2023-06-27 20:47:52.000000 image_label-2.4.1/image_label/frontend/build/bootstrap.min.css
+-rw-rw-r--   0 sks       (1000) sks       (1000)     2168 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/index.html
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.989153 image_label-2.4.1/image_label/frontend/build/static/
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.993153 image_label-2.4.1/image_label/frontend/build/static/css/
+-rw-rw-r--   0 sks       (1000) sks       (1000)     1505 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css
+-rw-rw-r--   0 sks       (1000) sks       (1000)     3311 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css.map
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.997154 image_label-2.4.1/image_label/frontend/build/static/js/
+-rw-rw-r--   0 sks       (1000) sks       (1000)   533439 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js
+-rw-rw-r--   0 sks       (1000) sks       (1000)     2284 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.LICENSE.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)  1907895 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.map
+-rw-rw-r--   0 sks       (1000) sks       (1000)     4747 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js
+-rw-rw-r--   0 sks       (1000) sks       (1000)    20614 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js.map
+-rw-rw-r--   0 sks       (1000) sks       (1000)     1598 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js
+-rw-rw-r--   0 sks       (1000) sks       (1000)     8383 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js.map
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.993153 image_label-2.4.1/image_label.egg-info/
+-rw-rw-r--   0 sks       (1000) sks       (1000)      599 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/PKG-INFO
+-rw-rw-r--   0 sks       (1000) sks       (1000)      933 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/SOURCES.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)        1 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/dependency_links.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)       16 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/requires.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)       12 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/top_level.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)       38 2023-06-28 07:55:51.001154 image_label-2.4.1/setup.cfg
+-rw-rw-r--   0 sks       (1000) sks       (1000)      970 2023-06-28 07:55:39.000000 image_label-2.4.1/setup.py
```

### Comparing `image_label-2.4.0/LICENSE` & `image_label-2.4.1/LICENSE`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/README.md` & `image_label-2.4.1/README.md`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/__init__.py` & `image_label-2.4.1/image_label/__init__.py`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/asset-manifest.json` & `image_label-2.4.1/image_label/frontend/build/asset-manifest.json`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/bootstrap.min.css` & `image_label-2.4.1/image_label/frontend/build/bootstrap.min.css`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/index.html` & `image_label-2.4.1/image_label/frontend/build/index.html`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/css/main.459970d8.chunk.css` & `image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/css/main.459970d8.chunk.css.map` & `image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css.map`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/js/2.d24733fb.chunk.js` & `image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/js/2.d24733fb.chunk.js.LICENSE.txt` & `image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.LICENSE.txt`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/js/2.d24733fb.chunk.js.map` & `image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.map`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js` & `image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js.map` & `image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js.map`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/js/runtime-main.657b0728.js` & `image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label/frontend/build/static/js/runtime-main.657b0728.js.map` & `image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js.map`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/image_label.egg-info/SOURCES.txt` & `image_label-2.4.1/image_label.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `image_label-2.4.0/setup.py` & `image_label-2.4.1/setup.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 import setuptools
 
 setuptools.setup(
     name="image_label",
-    version="2.4.0",
+    version="2.4.1",
     author="sks",
     author_email="shubhaman47@gmail.com",
     description="This is an Image Labeling Component for streamlit",
-    long_description="Please go throught the readme file for more details",
+    long_description="The image_label package provides a custom Streamlit component for image annotation. It allows users to manually annotate images with bounding boxes and labels, making it a great tool for data labeling tasks, especially in machine learning projects. for more info go to https://github.com/SksOp/image_label",
     long_description_content_type="text/plain",
     url="https://github.com/SksOp/image_label",
     packages=setuptools.find_packages(),
     include_package_data=True,
     classifiers=[],
     python_requires=">=3.6",
     install_requires=[
```

