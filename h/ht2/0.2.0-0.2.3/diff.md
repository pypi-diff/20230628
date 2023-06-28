# Comparing `tmp/ht2-0.2.0.tar.gz` & `tmp/ht2-0.2.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ht2-0.2.0.tar", last modified: Wed Jun 21 08:32:56 2023, max compression
+gzip compressed data, was "ht2-0.2.3.tar", last modified: Wed Jun 28 07:20:58 2023, max compression
```

## Comparing `ht2-0.2.0.tar` & `ht2-0.2.3.tar`

### file list

```diff
@@ -1,25 +1,26 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-21 08:32:56.638401 ht2-0.2.0/
--rw-r--r--   0 root         (0) root         (0)     1070 2023-06-12 07:05:14.000000 ht2-0.2.0/LICENSE
--rw-r--r--   0 root         (0) root         (0)      807 2023-06-21 08:32:56.638401 ht2-0.2.0/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      282 2023-06-15 10:51:16.000000 ht2-0.2.0/README.md
--rw-r--r--   0 root         (0) root         (0)      713 2023-06-21 08:30:18.000000 ht2-0.2.0/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-21 08:32:56.638401 ht2-0.2.0/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-21 08:32:56.638401 ht2-0.2.0/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-21 08:32:56.638401 ht2-0.2.0/src/ht2/
--rw-r--r--   0 root         (0) root         (0)      186 2023-06-21 06:44:04.000000 ht2-0.2.0/src/ht2/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-21 08:32:56.638401 ht2-0.2.0/src/ht2/snippets/
--rw-r--r--   0 root         (0) root         (0)      270 2023-06-21 07:20:40.000000 ht2-0.2.0/src/ht2/snippets/scripts.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-21 08:32:56.638401 ht2-0.2.0/src/ht2/utils_dev/
--rw-r--r--   0 root         (0) root         (0)       71 2023-06-12 07:05:14.000000 ht2-0.2.0/src/ht2/utils_dev/example.py
--rw-r--r--   0 root         (0) root         (0)     6341 2023-06-21 08:18:44.000000 ht2-0.2.0/src/ht2/utils_dev/files.py
--rw-r--r--   0 root         (0) root         (0)     1071 2023-06-13 07:59:41.000000 ht2-0.2.0/src/ht2/utils_dev/image.py
--rw-r--r--   0 root         (0) root         (0)      467 2023-06-15 10:31:54.000000 ht2-0.2.0/src/ht2/utils_dev/misc.py
--rw-r--r--   0 root         (0) root         (0)      434 2023-06-12 09:33:27.000000 ht2-0.2.0/src/ht2/utils_dev/os.py
--rw-r--r--   0 root         (0) root         (0)      672 2023-06-12 07:05:14.000000 ht2-0.2.0/src/ht2/utils_dev/text.py
--rw-r--r--   0 root         (0) root         (0)      503 2023-06-12 07:05:14.000000 ht2-0.2.0/src/ht2/utils_dev/visualize.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-21 08:32:56.638401 ht2-0.2.0/src/ht2.egg-info/
--rw-r--r--   0 root         (0) root         (0)      807 2023-06-21 08:32:56.000000 ht2-0.2.0/src/ht2.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      424 2023-06-21 08:32:56.000000 ht2-0.2.0/src/ht2.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-21 08:32:56.000000 ht2-0.2.0/src/ht2.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       63 2023-06-21 08:32:56.000000 ht2-0.2.0/src/ht2.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        4 2023-06-21 08:32:56.000000 ht2-0.2.0/src/ht2.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.174095 ht2-0.2.3/
+-rw-r--r--   0 root         (0) root         (0)     1070 2023-06-25 03:35:59.000000 ht2-0.2.3/LICENSE
+-rw-r--r--   0 root         (0) root         (0)      807 2023-06-28 07:20:58.174095 ht2-0.2.3/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      282 2023-06-25 03:35:59.000000 ht2-0.2.3/README.md
+-rw-r--r--   0 root         (0) root         (0)      722 2023-06-28 07:16:51.000000 ht2-0.2.3/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:20:58.174095 ht2-0.2.3/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.166096 ht2-0.2.3/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.170096 ht2-0.2.3/src/ht2/
+-rw-r--r--   0 root         (0) root         (0)      186 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.170096 ht2-0.2.3/src/ht2/schemas/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/schemas/basic.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.174095 ht2-0.2.3/src/ht2/utils_dev/
+-rw-r--r--   0 root         (0) root         (0)     1556 2023-06-28 03:26:06.000000 ht2-0.2.3/src/ht2/utils_dev/converts.py
+-rw-r--r--   0 root         (0) root         (0)       71 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/example.py
+-rw-r--r--   0 root         (0) root         (0)     6068 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/files.py
+-rw-r--r--   0 root         (0) root         (0)     1071 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/image.py
+-rw-r--r--   0 root         (0) root         (0)      467 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/misc.py
+-rw-r--r--   0 root         (0) root         (0)      434 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/os.py
+-rw-r--r--   0 root         (0) root         (0)      672 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/text.py
+-rw-r--r--   0 root         (0) root         (0)      503 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/visualize.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.170096 ht2-0.2.3/src/ht2.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      807 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      451 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       67 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        4 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/top_level.txt
```

### Comparing `ht2-0.2.0/LICENSE` & `ht2-0.2.3/LICENSE`

 * *Files identical despite different names*

### Comparing `ht2-0.2.0/PKG-INFO` & `ht2-0.2.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ht2
-Version: 0.2.0
+Version: 0.2.3
 Summary: Just a bag of quality of life tools for Machine Learning Engineers
 Author-email: Haotian Zhang <z.haotian@columbia.edu>
 Project-URL: Homepage, https://github.com/htplex/ht2
 Project-URL: Bug Tracker, https://github.com/htplex/ht2/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `ht2-0.2.0/pyproject.toml` & `ht2-0.2.3/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "ht2"
-version = "0.2.0"
+version = "0.2.3"
 authors = [
   { name="Haotian Zhang", email="z.haotian@columbia.edu" },
 ]
 description = "Just a bag of quality of life tools for Machine Learning Engineers"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
@@ -19,13 +19,14 @@
 dependencies = [
   "opencv-python",
   "matplotlib",
   "numpy",
   "lmdb",
   "msgpack",
   "msgpack_numpy",
-  "tqdm"
+  "tqdm",
+  "lz4"
 ]
 
 [project.urls]
 "Homepage" = "https://github.com/htplex/ht2"
 "Bug Tracker" = "https://github.com/htplex/ht2/issues"
```

### Comparing `ht2-0.2.0/src/ht2/utils_dev/files.py` & `ht2-0.2.3/src/ht2/utils_dev/files.py`

 * *Files 13% similar despite different names*

```diff
@@ -117,24 +117,14 @@
 
     return decoded_dict
 
 # generalized encoder/decoder
 
 
 
-def obj_to_bin(obj):
-    pickled_data = pickle.dumps(obj)
-    compressed_pickle = zlib.compress(pickled_data, level = 1)
-    return compressed_pickle
-
-def bin_to_obj(bin):
-    depressed_pickle = zlib.decompress(bin)
-    obj = pickle.loads(depressed_pickle)
-    return obj
-
 
 # msgpack
 import msgpack
 import msgpack_numpy as msg_np
 
 def serialize_message(message):
     ser_message = msgpack.dumps(message)
```

### Comparing `ht2-0.2.0/src/ht2/utils_dev/image.py` & `ht2-0.2.3/src/ht2/utils_dev/image.py`

 * *Files identical despite different names*

### Comparing `ht2-0.2.0/src/ht2/utils_dev/text.py` & `ht2-0.2.3/src/ht2/utils_dev/text.py`

 * *Files identical despite different names*

### Comparing `ht2-0.2.0/src/ht2.egg-info/PKG-INFO` & `ht2-0.2.3/src/ht2.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ht2
-Version: 0.2.0
+Version: 0.2.3
 Summary: Just a bag of quality of life tools for Machine Learning Engineers
 Author-email: Haotian Zhang <z.haotian@columbia.edu>
 Project-URL: Homepage, https://github.com/htplex/ht2
 Project-URL: Bug Tracker, https://github.com/htplex/ht2/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

