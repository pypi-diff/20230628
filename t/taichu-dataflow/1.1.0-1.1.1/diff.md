# Comparing `tmp/taichu-dataflow-1.1.0.tar.gz` & `tmp/taichu-dataflow-1.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "taichu-dataflow-1.1.0.tar", last modified: Tue Jun 27 01:51:43 2023, max compression
+gzip compressed data, was "dist/taichu-dataflow-1.1.1.tar", last modified: Wed Jun 28 06:53:32 2023, max compression
```

## Comparing `taichu-dataflow-1.1.0.tar` & `taichu-dataflow-1.1.1.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 wangkun    (501) staff       (20)        0 2023-06-27 01:51:43.910223 taichu-dataflow-1.1.0/
--rw-r--r--   0 wangkun    (501) staff       (20)      258 2023-06-27 01:51:43.909976 taichu-dataflow-1.1.0/PKG-INFO
--rw-r--r--   0 wangkun    (501) staff       (20)      194 2023-06-12 02:53:15.000000 taichu-dataflow-1.1.0/README.md
--rw-r--r--   0 wangkun    (501) staff       (20)       38 2023-06-27 01:51:43.910305 taichu-dataflow-1.1.0/setup.cfg
--rw-r--r--   0 wangkun    (501) staff       (20)      888 2023-06-27 01:51:41.000000 taichu-dataflow-1.1.0/setup.py
-drwxr-xr-x   0 wangkun    (501) staff       (20)        0 2023-06-27 01:51:43.906698 taichu-dataflow-1.1.0/taichu_dataflow/
--rw-r--r--   0 wangkun    (501) staff       (20)      618 2023-06-27 01:48:41.000000 taichu-dataflow-1.1.0/taichu_dataflow/__init__.py
--rw-r--r--   0 wangkun    (501) staff       (20)     1805 2023-06-27 01:48:41.000000 taichu-dataflow-1.1.0/taichu_dataflow/command.py
--rw-r--r--   0 wangkun    (501) staff       (20)     3551 2023-06-27 01:48:41.000000 taichu-dataflow-1.1.0/taichu_dataflow/export_back.py
-drwxr-xr-x   0 wangkun    (501) staff       (20)        0 2023-06-27 01:51:43.909619 taichu-dataflow-1.1.0/taichu_dataflow/storage/
--rw-r--r--   0 wangkun    (501) staff       (20)     1280 2023-06-14 03:15:36.000000 taichu-dataflow-1.1.0/taichu_dataflow/storage/__init__.py
--rw-r--r--   0 wangkun    (501) staff       (20)     2169 2023-06-27 01:48:41.000000 taichu-dataflow-1.1.0/taichu_dataflow/storage/alluxio.py
--rw-r--r--   0 wangkun    (501) staff       (20)     1116 2023-06-14 01:52:14.000000 taichu-dataflow-1.1.0/taichu_dataflow/storage/env.py
--rw-r--r--   0 wangkun    (501) staff       (20)     1034 2023-06-14 03:08:02.000000 taichu-dataflow-1.1.0/taichu_dataflow/storage/obs.py
-drwxr-xr-x   0 wangkun    (501) staff       (20)        0 2023-06-27 01:51:43.908528 taichu-dataflow-1.1.0/taichu_dataflow.egg-info/
--rw-r--r--   0 wangkun    (501) staff       (20)      258 2023-06-27 01:51:43.000000 taichu-dataflow-1.1.0/taichu_dataflow.egg-info/PKG-INFO
--rw-r--r--   0 wangkun    (501) staff       (20)      473 2023-06-27 01:51:43.000000 taichu-dataflow-1.1.0/taichu_dataflow.egg-info/SOURCES.txt
--rw-r--r--   0 wangkun    (501) staff       (20)        1 2023-06-27 01:51:43.000000 taichu-dataflow-1.1.0/taichu_dataflow.egg-info/dependency_links.txt
--rw-r--r--   0 wangkun    (501) staff       (20)       64 2023-06-27 01:51:43.000000 taichu-dataflow-1.1.0/taichu_dataflow.egg-info/entry_points.txt
--rw-r--r--   0 wangkun    (501) staff       (20)       50 2023-06-27 01:51:43.000000 taichu-dataflow-1.1.0/taichu_dataflow.egg-info/requires.txt
--rw-r--r--   0 wangkun    (501) staff       (20)       16 2023-06-27 01:51:43.000000 taichu-dataflow-1.1.0/taichu_dataflow.egg-info/top_level.txt
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/
+-rw-r--r--   0 shenli     (501) staff       (20)      258 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/PKG-INFO
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/
+-rw-r--r--   0 shenli     (501) staff       (20)      258 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/PKG-INFO
+-rw-r--r--   0 shenli     (501) staff       (20)      473 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/SOURCES.txt
+-rw-r--r--   0 shenli     (501) staff       (20)       64 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/entry_points.txt
+-rw-r--r--   0 shenli     (501) staff       (20)       50 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/requires.txt
+-rw-r--r--   0 shenli     (501) staff       (20)       16 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/top_level.txt
+-rw-r--r--   0 shenli     (501) staff       (20)        1 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/dependency_links.txt
+-rw-r--r--   0 shenli     (501) staff       (20)      194 2023-06-12 03:14:29.000000 taichu-dataflow-1.1.1/README.md
+-rw-r--r--   0 shenli     (501) staff       (20)      888 2023-06-28 06:52:56.000000 taichu-dataflow-1.1.1/setup.py
+-rw-r--r--   0 shenli     (501) staff       (20)       38 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/setup.cfg
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/taichu_dataflow/
+-rw-r--r--   0 shenli     (501) staff       (20)     1805 2023-06-26 06:38:12.000000 taichu-dataflow-1.1.1/taichu_dataflow/command.py
+-rw-r--r--   0 shenli     (501) staff       (20)     1434 2023-06-28 06:50:26.000000 taichu-dataflow-1.1.1/taichu_dataflow/__init__.py
+-rw-r--r--   0 shenli     (501) staff       (20)     3575 2023-06-28 06:51:11.000000 taichu-dataflow-1.1.1/taichu_dataflow/export_back.py
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/
+-rw-r--r--   0 shenli     (501) staff       (20)     1116 2023-06-28 06:51:41.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/env.py
+-rw-r--r--   0 shenli     (501) staff       (20)     2169 2023-06-26 06:38:12.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/alluxio.py
+-rw-r--r--   0 shenli     (501) staff       (20)     1256 2023-06-28 06:52:15.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/__init__.py
+-rw-r--r--   0 shenli     (501) staff       (20)     1034 2023-06-28 06:52:43.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/obs.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive
+POSIX tar archive (GNU)
```

### Comparing `taichu-dataflow-1.1.0/setup.py` & `taichu-dataflow-1.1.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 
     long_description = ''
     # with open('README.md', 'r') as f:
     #     long_description = f.read()
 
     setup(
         name=name,
-        version='1.1.0',
+        version='1.1.1',
         description='taichu serve is a tool for serving dataflow',
         long_description=long_description,
         author='taichu platform team',
         python_requires=">=3.6.0",
         url='',
         keywords='taichu',
         packages=find_packages(),
```

### Comparing `taichu-dataflow-1.1.0/taichu_dataflow/command.py` & `taichu-dataflow-1.1.1/taichu_dataflow/command.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.0/taichu_dataflow/export_back.py` & `taichu-dataflow-1.1.1/taichu_dataflow/export_back.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+import json
 import logging
 import os.path
 import random
 import threading
 import time
 import uuid
 
@@ -80,25 +81,25 @@
 
 def export_back_file(path_to_file, result_json=None, service=''):
     suffix = os.path.splitext(path_to_file)[-1].lower()
     _export_back_async('file', path_to_file, suffix, result_json, service)
 
 
 def _logfmt(suffix, key):
-    logging.info({
+    logging.info(json.dumps({
         "id": str(uuid.uuid4()),
         "app_name": get_service_name(),
         "create_time": datetime.now().strftime("%Y-%m-%d %H:%M:%S"),
         # "user_id": "1889531xx35",
         "action": "export_back",
         "action_params": {
             "suffix": suffix,
             "key": key
         }
-    })
+    }))
 
 
 if __name__ == "__main__":
     # export_back_string('abc')
     # global base64_string
     export_back('string', 'abc', 'txt', {'back_test': 'abc'}, 'mys_service')
     # export_back('json', {'abc': 123}, 'json')
```

### Comparing `taichu-dataflow-1.1.0/taichu_dataflow/storage/__init__.py` & `taichu-dataflow-1.1.1/taichu_dataflow/storage/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,13 +30,13 @@
         # suffix = os.path.splitext(key)[-1].lower().lstrip('.')
         # tmp_image_path = '{}-{}.{}'.format(str(int(time.time())), rnd_number, suffix)
         # image.save(tmp_image_path)
         # self.write_file(tmp_image_path, key)
 
 
 def create_storage(storage_type):
-    if storage_type == "MINIO":
-        from taichu_dataflow.storage.alluxio import StorageAlluxio
-        return StorageAlluxio()
-    elif storage_type == "OBS":
+    if storage_type == "OBS":
         from taichu_dataflow.storage.obs import StorageObs
         return StorageObs()
+    else:
+        from taichu_dataflow.storage.alluxio import StorageAlluxio
+        return StorageAlluxio()
```

### Comparing `taichu-dataflow-1.1.0/taichu_dataflow/storage/alluxio.py` & `taichu-dataflow-1.1.1/taichu_dataflow/storage/alluxio.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.0/taichu_dataflow/storage/env.py` & `taichu-dataflow-1.1.1/taichu_dataflow/storage/env.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.0/taichu_dataflow/storage/obs.py` & `taichu-dataflow-1.1.1/taichu_dataflow/storage/obs.py`

 * *Files identical despite different names*

