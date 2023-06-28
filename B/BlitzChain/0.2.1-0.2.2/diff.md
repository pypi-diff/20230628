# Comparing `tmp/BlitzChain-0.2.1.tar.gz` & `tmp/BlitzChain-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "BlitzChain-0.2.1.tar", last modified: Wed Jun 28 03:11:46 2023, max compression
+gzip compressed data, was "BlitzChain-0.2.2.tar", last modified: Wed Jun 28 03:21:47 2023, max compression
```

## Comparing `BlitzChain-0.2.1.tar` & `BlitzChain-0.2.2.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.933922 BlitzChain-0.2.1/
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.929178 BlitzChain-0.2.1/BlitzChain.egg-info/
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)      342 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/SOURCES.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/dependency_links.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/requires.txt
--rw-r--r--   0 jackywong   (501) staff       (20)       11 2023-06-28 03:11:46.000000 BlitzChain-0.2.1/BlitzChain.egg-info/top_level.txt
--rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.2.1/LICENSE
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 03:11:46.933549 BlitzChain-0.2.1/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.2.1/README.md
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.930563 BlitzChain-0.2.1/blitzchain/
--rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-28 03:07:44.000000 BlitzChain-0.2.1/blitzchain/__init__.py
--rw-r--r--   0 jackywong   (501) staff       (20)     5364 2023-06-28 03:07:26.000000 BlitzChain-0.2.1/blitzchain/api.py
--rw-r--r--   0 jackywong   (501) staff       (20)     1634 2023-06-28 03:05:46.000000 BlitzChain-0.2.1/blitzchain/document_splitter.py
--rw-r--r--   0 jackywong   (501) staff       (20)      763 2023-06-28 00:10:27.000000 BlitzChain-0.2.1/blitzchain/utils.py
--rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-28 03:11:46.934032 BlitzChain-0.2.1/setup.cfg
--rw-r--r--   0 jackywong   (501) staff       (20)      409 2023-06-26 02:24:27.000000 BlitzChain-0.2.1/setup.py
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:11:46.932733 BlitzChain-0.2.1/tests/
--rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.2.1/tests/test_crud.py
--rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.2.1/tests/test_pdf.py
--rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.2.1/tests/test_qa.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:21:47.305267 BlitzChain-0.2.2/
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:21:47.302096 BlitzChain-0.2.2/BlitzChain.egg-info/
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 03:21:47.000000 BlitzChain-0.2.2/BlitzChain.egg-info/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)      333 2023-06-28 03:21:47.000000 BlitzChain-0.2.2/BlitzChain.egg-info/SOURCES.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-28 03:21:47.000000 BlitzChain-0.2.2/BlitzChain.egg-info/dependency_links.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-28 03:21:47.000000 BlitzChain-0.2.2/BlitzChain.egg-info/requires.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)       11 2023-06-28 03:21:47.000000 BlitzChain-0.2.2/BlitzChain.egg-info/top_level.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.2.2/LICENSE
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 03:21:47.304967 BlitzChain-0.2.2/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.2.2/README.md
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:21:47.303426 BlitzChain-0.2.2/blitzchain/
+-rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-28 03:21:10.000000 BlitzChain-0.2.2/blitzchain/__init__.py
+-rw-r--r--   0 jackywong   (501) staff       (20)     5355 2023-06-28 03:19:55.000000 BlitzChain-0.2.2/blitzchain/api.py
+-rw-r--r--   0 jackywong   (501) staff       (20)     1669 2023-06-28 03:13:29.000000 BlitzChain-0.2.2/blitzchain/splitter.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      763 2023-06-28 00:10:27.000000 BlitzChain-0.2.2/blitzchain/utils.py
+-rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-28 03:21:47.305367 BlitzChain-0.2.2/setup.cfg
+-rw-r--r--   0 jackywong   (501) staff       (20)      409 2023-06-26 02:24:27.000000 BlitzChain-0.2.2/setup.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 03:21:47.304559 BlitzChain-0.2.2/tests/
+-rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.2.2/tests/test_crud.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.2.2/tests/test_pdf.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.2.2/tests/test_qa.py
```

### Comparing `BlitzChain-0.2.1/LICENSE` & `BlitzChain-0.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.1/README.md` & `BlitzChain-0.2.2/README.md`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.1/blitzchain/api.py` & `BlitzChain-0.2.2/blitzchain/api.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 """The API behind BlitzChain
 """
 import requests
-from .document_splitter import WordSplitter
+from .splitter import WordSplitter
 
 class Client:
     def __init__(self, api_key: str):
         self.api_key = api_key
     
     def Collection(self, collection_name: str):
         return Collection(api_key=self.api_key, collection_name=collection_name)
```

### Comparing `BlitzChain-0.2.1/blitzchain/document_splitter.py` & `BlitzChain-0.2.2/blitzchain/splitter.py`

 * *Files 8% similar despite different names*

```diff
@@ -32,14 +32,15 @@
         self,
         dicts: List[Dict],
         key: str,
         max_word_count: int = 200,
         overlap: int = 10,
     ) -> list[dict]:
         """Splits the text of a specified key in a list of dictionaries, creating a new dictionary for each split text segment."""
+        print("splitting text...")
         split_dicts = []
         for d in dicts:
             if key in d:
                 text = d[key]
                 split_text = self.split_text_into_array(text, max_word_count, overlap)
                 for segment in split_text:
                     new_d = d.copy()
```

### Comparing `BlitzChain-0.2.1/blitzchain/utils.py` & `BlitzChain-0.2.2/blitzchain/utils.py`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.1/tests/test_pdf.py` & `BlitzChain-0.2.2/tests/test_pdf.py`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.1/tests/test_qa.py` & `BlitzChain-0.2.2/tests/test_qa.py`

 * *Files identical despite different names*

