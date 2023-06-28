# Comparing `tmp/BlitzChain-0.2.0.tar.gz` & `tmp/BlitzChain-0.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "BlitzChain-0.2.0.tar", last modified: Tue Jun 27 11:47:43 2023, max compression
+gzip compressed data, was "BlitzChain-0.2.1.tar", last modified: Wed Jun 28 03:11:46 2023, max compression
```

## Comparing `BlitzChain-0.2.0.tar` & `BlitzChain-0.2.1.tar`

### file list

```diff
@@ -1,20 +1,21 @@
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.623772 BlitzChain-0.2.0/
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.619748 BlitzChain-0.2.0/BlitzChain.egg-info/
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)      310 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/SOURCES.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/dependency_links.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/requires.txt
--rw-r--r--   0 jackywong   (501) staff       (20)       11 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/top_level.txt
--rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.2.0/LICENSE
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-27 11:47:43.623459 BlitzChain-0.2.0/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.2.0/README.md
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.621821 BlitzChain-0.2.0/blitzchain/
--rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-27 11:46:30.000000 BlitzChain-0.2.0/blitzchain/__init__.py
--rw-r--r--   0 jackywong   (501) staff       (20)     5225 2023-06-27 11:46:24.000000 BlitzChain-0.2.0/blitzchain/api.py
--rw-r--r--   0 jackywong   (501) staff       (20)      177 2023-06-26 02:49:39.000000 BlitzChain-0.2.0/blitzchain/utils.py
--rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-27 11:47:43.623874 BlitzChain-0.2.0/setup.cfg
--rw-r--r--   0 jackywong   (501) staff       (20)      409 2023-06-26 02:24:27.000000 BlitzChain-0.2.0/setup.py
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.622996 BlitzChain-0.2.0/tests/
--rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.2.0/tests/test_crud.py
--rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.2.0/tests/test_pdf.py
--rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.2.0/tests/test_qa.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.933922 BlitzChain-0.2.1/
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.929178 BlitzChain-0.2.1/BlitzChain.egg-info/
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)      342 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/SOURCES.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/dependency_links.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/requires.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)       11 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/top_level.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.2.1/LICENSE
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 03:11:46.933549 BlitzChain-0.2.1/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.2.1/README.md
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.930563 BlitzChain-0.2.1/blitzchain/
+-rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-28 03:07:44.000000 BlitzChain-0.2.1/blitzchain/__init__.py
+-rw-r--r--   0 jackywong   (501) staff       (20)     5364 2023-06-28 03:07:26.000000 BlitzChain-0.2.1/blitzchain/api.py
+-rw-r--r--   0 jackywong   (501) staff       (20)     1634 2023-06-28 03:05:46.000000 BlitzChain-0.2.1/blitzchain/document_splitter.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      763 2023-06-28 00:10:27.000000 BlitzChain-0.2.1/blitzchain/utils.py
+-rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-28 03:11:46.934032 BlitzChain-0.2.1/setup.cfg
+-rw-r--r--   0 jackywong   (501) staff       (20)      409 2023-06-26 02:24:27.000000 BlitzChain-0.2.1/setup.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.932733 BlitzChain-0.2.1/tests/
+-rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.2.1/tests/test_crud.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.2.1/tests/test_pdf.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.2.1/tests/test_qa.py
```

### Comparing `BlitzChain-0.2.0/LICENSE` & `BlitzChain-0.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.0/README.md` & `BlitzChain-0.2.1/README.md`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.0/blitzchain/api.py` & `BlitzChain-0.2.1/blitzchain/api.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 """The API behind BlitzChain
 """
 import requests
+from .document_splitter import WordSplitter
 
 class Client:
     def __init__(self, api_key: str):
         self.api_key = api_key
     
     def Collection(self, collection_name: str):
         return Collection(api_key=self.api_key, collection_name=collection_name)
@@ -22,30 +23,34 @@
         field_to_split: str = None,
         wait_to_finish=False
     ):
         if wait_to_finish:
             url = self.base_url + "collection/bulk-insert"
         else:
             url = self.base_url + "collection/async-bulk-insert"
+        
+        if field_to_split:
+            splitter = WordSplitter()
+            objects = splitter.split_dict_text(
+                dicts=objects, key=field_to_split
+            )
 
         response = requests.post(
             url,
             headers={
                 "Content-Type": "application/json", 
                 "Authorization": "Bearer " + self.api_key
             },
             json={
                 "collection": self.collection_name,
                 "objects": objects,
                 "fieldsToVectorize": fields_to_vectorize,
-                "fieldToSplit": field_to_split
             }
 
         )
-        print(response.content.decode())
         if not wait_to_finish:
             return response.status_code == 200, "Request failed - please make sure parameters are correct."
         return response.json()
     
     def insert_pdf(self, url: str):
         api_url = self.base_url + "collection/insert-pdf"
         print(api_url)
@@ -118,16 +123,16 @@
                 "Content-Type": "application/json",
                 "Authorization": "Bearer " + self.api_key
             },
             json=data
         )
         return response.json()
 
-    def list_objects(self, limit: int=5, offset: int=0, fields: list=None,
-                     where=None, sort=list):
+    def list_objects(self, limit: int=5, offset: int=0, 
+            fields: list=None, where=None, sort:list=None):
         api_url = self.base_url + "object/list"
         print(api_url)
         response = requests.post(
             api_url,
             headers={
                 "Content-Type": "application/json",
                 "Authorization": "Bearer " + self.api_key
```

### Comparing `BlitzChain-0.2.0/tests/test_pdf.py` & `BlitzChain-0.2.1/tests/test_pdf.py`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.0/tests/test_qa.py` & `BlitzChain-0.2.1/tests/test_qa.py`

 * *Files identical despite different names*

