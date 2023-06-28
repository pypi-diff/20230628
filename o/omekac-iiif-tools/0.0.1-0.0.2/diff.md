# Comparing `tmp/omekac_iiif_tools-0.0.1.tar.gz` & `tmp/omekac_iiif_tools-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "omekac_iiif_tools-0.0.1.tar", last modified: Tue Jun 27 01:29:57 2023, max compression
+gzip compressed data, was "omekac_iiif_tools-0.0.2.tar", last modified: Wed Jun 28 04:12:23 2023, max compression
```

## Comparing `omekac_iiif_tools-0.0.1.tar` & `omekac_iiif_tools-0.0.2.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-27 01:29:57.723245 omekac_iiif_tools-0.0.1/
--rw-rw-r--   0 nakamura   (501) staff       (20)    11337 2023-04-27 10:12:58.000000 omekac_iiif_tools-0.0.1/LICENSE
--rw-rw-r--   0 nakamura   (501) staff       (20)      111 2023-04-27 10:12:58.000000 omekac_iiif_tools-0.0.1/MANIFEST.in
--rw-r--r--   0 nakamura   (501) staff       (20)     1096 2023-06-27 01:29:57.723088 omekac_iiif_tools-0.0.1/PKG-INFO
--rw-r--r--   0 nakamura   (501) staff       (20)      319 2023-06-26 23:39:38.000000 omekac_iiif_tools-0.0.1/README.md
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-27 01:29:57.721489 omekac_iiif_tools-0.0.1/omekac_iiif_tools/
--rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-27 01:26:17.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools/__init__.py
--rw-r--r--   0 nakamura   (501) staff       (20)     3140 2023-06-27 01:26:17.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools/_modidx.py
--rw-r--r--   0 nakamura   (501) staff       (20)    13224 2023-06-27 01:26:17.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools/core.py
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-27 01:29:57.722851 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/
--rw-r--r--   0 nakamura   (501) staff       (20)     1096 2023-06-27 01:29:57.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/PKG-INFO
--rw-r--r--   0 nakamura   (501) staff       (20)      424 2023-06-27 01:29:57.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/SOURCES.txt
--rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-27 01:29:57.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/dependency_links.txt
--rw-r--r--   0 nakamura   (501) staff       (20)       77 2023-06-27 01:29:57.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/entry_points.txt
--rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-26 23:40:36.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/not-zip-safe
--rw-r--r--   0 nakamura   (501) staff       (20)        7 2023-06-27 01:29:57.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/requires.txt
--rw-r--r--   0 nakamura   (501) staff       (20)       18 2023-06-27 01:29:57.000000 omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/top_level.txt
--rw-r--r--   0 nakamura   (501) staff       (20)      931 2023-06-26 23:39:35.000000 omekac_iiif_tools-0.0.1/settings.ini
--rw-r--r--   0 nakamura   (501) staff       (20)       38 2023-06-27 01:29:57.723298 omekac_iiif_tools-0.0.1/setup.cfg
--rw-rw-r--   0 nakamura   (501) staff       (20)     2596 2023-04-27 10:12:58.000000 omekac_iiif_tools-0.0.1/setup.py
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:12:23.434018 omekac_iiif_tools-0.0.2/
+-rw-rw-r--   0 nakamura   (501) staff       (20)    11337 2023-04-27 10:12:58.000000 omekac_iiif_tools-0.0.2/LICENSE
+-rw-rw-r--   0 nakamura   (501) staff       (20)      111 2023-04-27 10:12:58.000000 omekac_iiif_tools-0.0.2/MANIFEST.in
+-rw-r--r--   0 nakamura   (501) staff       (20)     1096 2023-06-28 04:12:23.433758 omekac_iiif_tools-0.0.2/PKG-INFO
+-rw-r--r--   0 nakamura   (501) staff       (20)      319 2023-06-26 23:39:38.000000 omekac_iiif_tools-0.0.2/README.md
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:12:23.432121 omekac_iiif_tools-0.0.2/omekac_iiif_tools/
+-rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-28 04:11:41.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools/__init__.py
+-rw-r--r--   0 nakamura   (501) staff       (20)     3684 2023-06-28 04:11:41.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools/_modidx.py
+-rw-r--r--   0 nakamura   (501) staff       (20)    14004 2023-06-28 04:11:41.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools/core.py
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:12:23.433361 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/
+-rw-r--r--   0 nakamura   (501) staff       (20)     1096 2023-06-28 04:12:23.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/PKG-INFO
+-rw-r--r--   0 nakamura   (501) staff       (20)      424 2023-06-28 04:12:23.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/SOURCES.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-28 04:12:23.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/dependency_links.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)       77 2023-06-28 04:12:23.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/entry_points.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-26 23:40:36.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/not-zip-safe
+-rw-r--r--   0 nakamura   (501) staff       (20)        7 2023-06-28 04:12:23.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/requires.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)       18 2023-06-28 04:12:23.000000 omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/top_level.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)      931 2023-06-28 04:11:51.000000 omekac_iiif_tools-0.0.2/settings.ini
+-rw-r--r--   0 nakamura   (501) staff       (20)       38 2023-06-28 04:12:23.434538 omekac_iiif_tools-0.0.2/setup.cfg
+-rw-rw-r--   0 nakamura   (501) staff       (20)     2596 2023-04-27 10:12:58.000000 omekac_iiif_tools-0.0.2/setup.py
```

### Comparing `omekac_iiif_tools-0.0.1/LICENSE` & `omekac_iiif_tools-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `omekac_iiif_tools-0.0.1/PKG-INFO` & `omekac_iiif_tools-0.0.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: omekac_iiif_tools
-Version: 0.0.1
+Version: 0.0.2
 Summary: UNKNOWN
 Home-page: https://github.com/nakamura196/omekac_iiif_tools
 Author: Satoru
 Author-email: you@example.com
 License: Apache Software License 2.0
 Keywords: nbdev jupyter notebook python
 Platform: UNKNOWN
```

### Comparing `omekac_iiif_tools-0.0.1/omekac_iiif_tools/_modidx.py` & `omekac_iiif_tools-0.0.2/omekac_iiif_tools/_modidx.py`

 * *Files 11% similar despite different names*

```diff
@@ -12,14 +12,18 @@
                                                                                                 'omekac_iiif_tools/core.py'),
                                         'omekac_iiif_tools.core.ApiClient.check_item_exists': ( 'core.html#apiclient.check_item_exists',
                                                                                                 'omekac_iiif_tools/core.py'),
                                         'omekac_iiif_tools.core.ApiClient.check_login': ( 'core.html#apiclient.check_login',
                                                                                           'omekac_iiif_tools/core.py'),
                                         'omekac_iiif_tools.core.ApiClient.convert_iiif3_to_excel': ( 'core.html#apiclient.convert_iiif3_to_excel',
                                                                                                      'omekac_iiif_tools/core.py'),
+                                        'omekac_iiif_tools.core.ApiClient.convert_local_iiif3_to_excel': ( 'core.html#apiclient.convert_local_iiif3_to_excel',
+                                                                                                           'omekac_iiif_tools/core.py'),
+                                        'omekac_iiif_tools.core.ApiClient.convert_main': ( 'core.html#apiclient.convert_main',
+                                                                                           'omekac_iiif_tools/core.py'),
                                         'omekac_iiif_tools.core.ApiClient.create_annotation': ( 'core.html#apiclient.create_annotation',
                                                                                                 'omekac_iiif_tools/core.py'),
                                         'omekac_iiif_tools.core.ApiClient.create_collection': ( 'core.html#apiclient.create_collection',
                                                                                                 'omekac_iiif_tools/core.py'),
                                         'omekac_iiif_tools.core.ApiClient.create_item': ( 'core.html#apiclient.create_item',
                                                                                           'omekac_iiif_tools/core.py'),
                                         'omekac_iiif_tools.core.ApiClient.main': ('core.html#apiclient.main', 'omekac_iiif_tools/core.py'),
```

### Comparing `omekac_iiif_tools-0.0.1/omekac_iiif_tools/core.py` & `omekac_iiif_tools-0.0.2/omekac_iiif_tools/core.py`

 * *Files 4% similar despite different names*

```diff
@@ -3,33 +3,33 @@
 # %% auto 0
 __all__ = ['ApiClient']
 
 # %% ../nbs/00_core.ipynb 4
 import pandas as pd
 import requests
 import json
-import requests
-import urllib.parse
+import os
 from tqdm import tqdm
 import uuid
 
 # %% ../nbs/00_core.ipynb 5
 class ApiClient():
     def __init__(self, omeka_url, api_key, username, password):
         self.omeka_url = omeka_url
         self.api_key = api_key
         self.username = username
         self.password = password
 
         self.element_id_map = {
             'title': 50,
-            'uuid': 65,
             'display_iiif': 54,
             'json_data': 56,
-            'on_canvas': 62
+            "iiif_type": 58,
+            'on_canvas': 62,
+            'uuid': 65
         }
 
         self.params = {
             "key": self.api_key
         }
 
     def update_element_id(self, element_id_map):
@@ -39,15 +39,15 @@
             _elment_id_map[key] = value
 
         self.element_id_map = _elment_id_map
 
     
 
     @staticmethod
-    def main(omeka_url, api_key, username, password, excel_path, element_id_map = {}, allow_duplicates = False):
+    def main(omeka_url, api_key, username, password, excel_path, element_id_map = {}, allow_duplicates = True):
         client = ApiClient(omeka_url, api_key, username, password)
 
         flg = client.check_login()
 
         if not flg:
             # client.login()
             raise Exception("login failed")
@@ -103,14 +103,18 @@
 
             url = row["manifest_uri"] # "http://example.org"
 
             element_texts_options = [
                 {
                     "text": url,
                     "element": self.element_id_map["title"]
+                },
+                {
+                    "text": "Manifest",
+                    "element": self.element_id_map["iiif_type"]
                 }
             ]
 
             item_json = self._create_item_json(element_texts_options)
 
             endpoint_collection = f"{self.omeka_url}/api/collections"
 
@@ -356,16 +360,22 @@
 
             # print(res.json())
     
     @staticmethod
     def convert_iiif3_to_excel(manifest_uri, output_path, start_index = 0, end_index = -1):
         manifest3 = requests.get(manifest_uri).json()
 
+        ApiClient.convert_main(manifest3, output_path, start_index, end_index)
+
+    @staticmethod
+    def convert_main(manifest3, output_path, start_index = 0, end_index = -1):
         canvases = manifest3["items"]
 
+        manifest_uri = manifest3["id"]
+
         if end_index == -1:
             canvases = canvases[start_index:]
         else:
             canvases = canvases[start_index:end_index]
 
         label = manifest3["label"]["none"][0]
 
@@ -377,15 +387,15 @@
         rows.append(["title", "canvas_uri", "width", "height", "image_url", "manifest_uri"])
 
         rows_annotation = []
         rows_annotation.append(["chars", "x", "y", "w", "h", "canvas_uri", "tag"])
 
         for i in range(len(canvases)):
             # for canvas in canvases:
-            index = start_index + 1
+            index = start_index + i + 1
 
             canvas = canvases[i]
 
             canvas_uri = canvas["id"]
             image_url = canvas["items"][0]["items"][0]["body"]["id"]
 
             title = f"{label} [{index}]"
@@ -408,16 +418,28 @@
                 x, y, w, h = xywh.split(",")
                 rows_annotation.append([chars, x, y, w, h, canvas_uri, ""])
 
             # break
 
         # rows
 
+        os.makedirs(os.path.dirname(output_path), exist_ok=True)
+
         with pd.ExcelWriter(output_path) as writer:
             df0 = pd.DataFrame(rows_collection)
             df0.to_excel(writer, sheet_name='collection', index=False, header=False)
 
             df1 = pd.DataFrame(rows)
             df1.to_excel(writer, sheet_name='item', index=False, header=False)
 
             df2 = pd.DataFrame(rows_annotation)
             df2.to_excel(writer, sheet_name='annotation', index=False, header=False)
+
+    @staticmethod
+    def convert_local_iiif3_to_excel(manifest_json_path, output_path, start_index = 0, end_index = -1):
+        # manifest3 = requests.get(manifest_uri).json()
+        with open(manifest_json_path) as f:
+            manifest3 = json.load(f)
+
+        ApiClient.convert_main(manifest3, output_path, start_index, end_index)
+
+
```

### Comparing `omekac_iiif_tools-0.0.1/omekac_iiif_tools.egg-info/PKG-INFO` & `omekac_iiif_tools-0.0.2/omekac_iiif_tools.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: omekac-iiif-tools
-Version: 0.0.1
+Version: 0.0.2
 Summary: UNKNOWN
 Home-page: https://github.com/nakamura196/omekac_iiif_tools
 Author: Satoru
 Author-email: you@example.com
 License: Apache Software License 2.0
 Keywords: nbdev jupyter notebook python
 Platform: UNKNOWN
```

### Comparing `omekac_iiif_tools-0.0.1/settings.ini` & `omekac_iiif_tools-0.0.2/settings.ini`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 [DEFAULT]
 # All sections below are required unless otherwise specified.
 # See https://github.com/fastai/nbdev/blob/master/settings.ini for examples.
 
 ### Python library ###
 repo = omekac_iiif_tools
 lib_name = %(repo)s
-version = 0.0.1
+version = 0.0.2
 min_python = 3.7
 license = apache2
 black_formatting = False
 
 ### nbdev ###
 doc_path = _docs
 lib_path = omekac_iiif_tools
```

### Comparing `omekac_iiif_tools-0.0.1/setup.py` & `omekac_iiif_tools-0.0.2/setup.py`

 * *Files identical despite different names*

