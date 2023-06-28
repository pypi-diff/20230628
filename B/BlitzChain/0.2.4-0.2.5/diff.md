# Comparing `tmp/BlitzChain-0.2.4.tar.gz` & `tmp/BlitzChain-0.2.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "BlitzChain-0.2.4.tar", last modified: Wed Jun 28 04:19:00 2023, max compression
+gzip compressed data, was "BlitzChain-0.2.5.tar", last modified: Wed Jun 28 05:29:22 2023, max compression
```

## Comparing `BlitzChain-0.2.4.tar` & `BlitzChain-0.2.5.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 04:19:00.661431 BlitzChain-0.2.4/
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 04:19:00.657256 BlitzChain-0.2.4/BlitzChain.egg-info/
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 04:19:00.000000 BlitzChain-0.2.4/BlitzChain.egg-info/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)      361 2023-06-28 04:19:00.000000 BlitzChain-0.2.4/BlitzChain.egg-info/SOURCES.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-28 04:19:00.000000 BlitzChain-0.2.4/BlitzChain.egg-info/dependency_links.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-28 04:19:00.000000 BlitzChain-0.2.4/BlitzChain.egg-info/requires.txt
--rw-r--r--   0 jackywong   (501) staff       (20)       15 2023-06-28 04:19:00.000000 BlitzChain-0.2.4/BlitzChain.egg-info/top_level.txt
--rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.2.4/LICENSE
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 04:19:00.661101 BlitzChain-0.2.4/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.2.4/README.md
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 04:19:00.658675 BlitzChain-0.2.4/blitzchain/
--rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-28 04:18:50.000000 BlitzChain-0.2.4/blitzchain/__init__.py
--rw-r--r--   0 jackywong   (501) staff       (20)     5357 2023-06-28 03:48:52.000000 BlitzChain-0.2.4/blitzchain/api.py
--rw-r--r--   0 jackywong   (501) staff       (20)     2708 2023-06-28 04:17:40.000000 BlitzChain-0.2.4/blitzchain/splitter.py
--rw-r--r--   0 jackywong   (501) staff       (20)      763 2023-06-28 00:10:27.000000 BlitzChain-0.2.4/blitzchain/utils.py
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 04:19:00.659269 BlitzChain-0.2.4/cli/
--rw-r--r--   0 jackywong   (501) staff       (20)        0 2023-06-28 03:39:00.000000 BlitzChain-0.2.4/cli/__init__.py
--rw-r--r--   0 jackywong   (501) staff       (20)      430 2023-06-28 04:17:43.000000 BlitzChain-0.2.4/cli/main.py
--rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-28 04:19:00.661536 BlitzChain-0.2.4/setup.cfg
--rw-r--r--   0 jackywong   (501) staff       (20)      511 2023-06-28 04:17:42.000000 BlitzChain-0.2.4/setup.py
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 04:19:00.660619 BlitzChain-0.2.4/tests/
--rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.2.4/tests/test_crud.py
--rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.2.4/tests/test_pdf.py
--rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.2.4/tests/test_qa.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 05:29:22.371852 BlitzChain-0.2.5/
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 05:29:22.365597 BlitzChain-0.2.5/BlitzChain.egg-info/
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 05:29:22.000000 BlitzChain-0.2.5/BlitzChain.egg-info/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)      361 2023-06-28 05:29:22.000000 BlitzChain-0.2.5/BlitzChain.egg-info/SOURCES.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-28 05:29:22.000000 BlitzChain-0.2.5/BlitzChain.egg-info/dependency_links.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-28 05:29:22.000000 BlitzChain-0.2.5/BlitzChain.egg-info/requires.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)       15 2023-06-28 05:29:22.000000 BlitzChain-0.2.5/BlitzChain.egg-info/top_level.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.2.5/LICENSE
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-28 05:29:22.371524 BlitzChain-0.2.5/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.2.5/README.md
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 05:29:22.366846 BlitzChain-0.2.5/blitzchain/
+-rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-28 05:28:32.000000 BlitzChain-0.2.5/blitzchain/__init__.py
+-rw-r--r--   0 jackywong   (501) staff       (20)     5224 2023-06-28 05:27:19.000000 BlitzChain-0.2.5/blitzchain/api.py
+-rw-r--r--   0 jackywong   (501) staff       (20)     2138 2023-06-28 05:25:25.000000 BlitzChain-0.2.5/blitzchain/splitter.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      763 2023-06-28 00:10:27.000000 BlitzChain-0.2.5/blitzchain/utils.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 05:29:22.367762 BlitzChain-0.2.5/cli/
+-rw-r--r--   0 jackywong   (501) staff       (20)        0 2023-06-28 03:39:00.000000 BlitzChain-0.2.5/cli/__init__.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      430 2023-06-28 04:17:43.000000 BlitzChain-0.2.5/cli/main.py
+-rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-28 05:29:22.371953 BlitzChain-0.2.5/setup.cfg
+-rw-r--r--   0 jackywong   (501) staff       (20)      485 2023-06-28 05:27:42.000000 BlitzChain-0.2.5/setup.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-28 05:29:22.370691 BlitzChain-0.2.5/tests/
+-rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.2.5/tests/test_crud.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.2.5/tests/test_pdf.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.2.5/tests/test_qa.py
```

### Comparing `BlitzChain-0.2.4/LICENSE` & `BlitzChain-0.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.4/README.md` & `BlitzChain-0.2.5/README.md`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.4/blitzchain/api.py` & `BlitzChain-0.2.5/blitzchain/api.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,30 +24,25 @@
         wait_to_finish=False
     ):
         if wait_to_finish:
             url = self.base_url + "collection/bulk-insert"
         else:
             url = self.base_url + "collection/async-bulk-insert"
         
-        if field_to_split:
-            splitter = WordSplitter()
-            objects = splitter.split_object_text(
-                dicts=objects, key=field_to_split
-            )
-
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
+                "fieldToSplit": field_to_split
             }
 
         )
         if not wait_to_finish:
             return response.status_code == 200, "Request failed - please make sure parameters are correct."
         return response.json()
```

### Comparing `BlitzChain-0.2.4/blitzchain/splitter.py` & `BlitzChain-0.2.5/blitzchain/splitter.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,57 +1,37 @@
 """Basic Document Splitter
 """
 from typing import List, Dict
 
-class Splitter:
-    """Base class for splitter
-    """
-
-def split_text_part(args):
-    """Splits a part of the whole text"""
-    words_part, max_word_count, overlap = args
-    word_count = len(words_part)
-
-    if word_count <= max_word_count:
-        return [" ".join(words_part)]
-
-    segments = []
-    start = 0
-    while start < word_count:
-        end = min(start + max_word_count, word_count)
-        segment_words = words_part[start:end]
-        segment_text = " ".join(segment_words)
-        segments.append(segment_text)
-        start = end - overlap
-    return segments
-
-class WordSplitter(Splitter):
+class WordSplitter:
     def split_text_into_array(
         self, text: str, max_word_count: int = 200, overlap: int = 10,
         chunksize: int=20
     ) -> list[str]:
         """Splits the input text into an array of strings with each element not exceeding the specified max_word_count. Allows an overlapping number of words."""
         words = text.split()
         word_count = len(words)
 
         if word_count <= max_word_count:
-            return [text]
+            yield [text]
 
         segments = []
         start = 0
         while start < word_count:
             end = min(start + max_word_count, word_count)
             segment_words = words[start:end]
             segment_text = " ".join(segment_words)
             segments.append(segment_text)
             if len(segments) > chunksize:
                 yield segments
                 segments = []
-            start = end - overlap
-        yield segments
+            start = end if end == word_count else end - overlap
+        # if segments == []:
+        #   return
+        yield segments 
     
     def split_object_text(
         self,
         dicts: List[Dict],
         key: str,
         max_word_count: int = 200,
         overlap: int = 10,
@@ -60,22 +40,23 @@
         """Splits the text of a specified key in a list of dictionaries, creating a new dictionary for each split text segment."""
         print("splitting text...")
         split_dicts = []
         for d in dicts:
             if key in d:
                 text = d[key]
                 print("split array")
-                split_text = self.split_text_into_array(text, max_word_count, overlap)
+                split_text = self.split_text_into_array(
+                    text, max_word_count, overlap
+                )
                 for segment in split_text:
                     new_d = d.copy()
                     new_d[key] = segment
-                    split_dicts.append(new_d)
-                    if len(split_dicts) % chunksize == 0:
-                        yield split_dicts 
-                        split_dicts = []
+                    split_dicts.append(
+                        new_d
+                    )
             else:
                 split_dicts.append(d)
                 if len(chunksize) % chunksize == 0:
                     yield split_dicts 
                     split_dicts = []
         if split_dicts == []:
             yield None
```

### Comparing `BlitzChain-0.2.4/blitzchain/utils.py` & `BlitzChain-0.2.5/blitzchain/utils.py`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.4/tests/test_pdf.py` & `BlitzChain-0.2.5/tests/test_pdf.py`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.2.4/tests/test_qa.py` & `BlitzChain-0.2.5/tests/test_qa.py`

 * *Files identical despite different names*

