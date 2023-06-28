# Comparing `tmp/BlitzChain-0.1.4.tar.gz` & `tmp/BlitzChain-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "BlitzChain-0.1.4.tar", last modified: Mon Jun 26 15:31:54 2023, max compression
+gzip compressed data, was "BlitzChain-0.2.0.tar", last modified: Tue Jun 27 11:47:43 2023, max compression
```

## Comparing `BlitzChain-0.1.4.tar` & `BlitzChain-0.2.0.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-26 15:31:54.934707 BlitzChain-0.1.4/
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-26 15:31:54.930494 BlitzChain-0.1.4/BlitzChain.egg-info/
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-26 15:31:54.000000 BlitzChain-0.1.4/BlitzChain.egg-info/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)      310 2023-06-26 15:31:54.000000 BlitzChain-0.1.4/BlitzChain.egg-info/SOURCES.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-26 15:31:54.000000 BlitzChain-0.1.4/BlitzChain.egg-info/dependency_links.txt
--rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-26 15:31:54.000000 BlitzChain-0.1.4/BlitzChain.egg-info/requires.txt
--rw-r--r--   0 jackywong   (501) staff       (20)       11 2023-06-26 15:31:54.000000 BlitzChain-0.1.4/BlitzChain.egg-info/top_level.txt
--rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.1.4/LICENSE
--rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-26 15:31:54.934041 BlitzChain-0.1.4/PKG-INFO
--rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.1.4/README.md
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-26 15:31:54.931559 BlitzChain-0.1.4/blitzchain/
--rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-26 15:30:19.000000 BlitzChain-0.1.4/blitzchain/__init__.py
--rw-r--r--   0 jackywong   (501) staff       (20)     3063 2023-06-26 15:31:41.000000 BlitzChain-0.1.4/blitzchain/api.py
--rw-r--r--   0 jackywong   (501) staff       (20)      177 2023-06-26 02:49:39.000000 BlitzChain-0.1.4/blitzchain/utils.py
--rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-26 15:31:54.934875 BlitzChain-0.1.4/setup.cfg
--rw-r--r--   0 jackywong   (501) staff       (20)      409 2023-06-26 02:24:27.000000 BlitzChain-0.1.4/setup.py
-drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-26 15:31:54.932977 BlitzChain-0.1.4/tests/
--rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.1.4/tests/test_crud.py
--rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.1.4/tests/test_pdf.py
--rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.1.4/tests/test_qa.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.623772 BlitzChain-0.2.0/
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.619748 BlitzChain-0.2.0/BlitzChain.egg-info/
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)      310 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/SOURCES.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        1 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/dependency_links.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)        9 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/requires.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)       11 2023-06-27 11:47:43.000000 BlitzChain-0.2.0/BlitzChain.egg-info/top_level.txt
+-rw-r--r--   0 jackywong   (501) staff       (20)    11357 2023-06-25 04:01:50.000000 BlitzChain-0.2.0/LICENSE
+-rw-r--r--   0 jackywong   (501) staff       (20)      189 2023-06-27 11:47:43.623459 BlitzChain-0.2.0/PKG-INFO
+-rw-r--r--   0 jackywong   (501) staff       (20)     3488 2023-06-25 07:25:46.000000 BlitzChain-0.2.0/README.md
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.621821 BlitzChain-0.2.0/blitzchain/
+-rw-r--r--   0 jackywong   (501) staff       (20)       42 2023-06-27 11:46:30.000000 BlitzChain-0.2.0/blitzchain/__init__.py
+-rw-r--r--   0 jackywong   (501) staff       (20)     5225 2023-06-27 11:46:24.000000 BlitzChain-0.2.0/blitzchain/api.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      177 2023-06-26 02:49:39.000000 BlitzChain-0.2.0/blitzchain/utils.py
+-rw-r--r--   0 jackywong   (501) staff       (20)       38 2023-06-27 11:47:43.623874 BlitzChain-0.2.0/setup.cfg
+-rw-r--r--   0 jackywong   (501) staff       (20)      409 2023-06-26 02:24:27.000000 BlitzChain-0.2.0/setup.py
+drwxr-xr-x   0 jackywong   (501) staff       (20)        0 2023-06-27 11:47:43.622996 BlitzChain-0.2.0/tests/
+-rw-r--r--   0 jackywong   (501) staff       (20)      216 2023-06-25 05:27:46.000000 BlitzChain-0.2.0/tests/test_crud.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      715 2023-06-25 05:08:57.000000 BlitzChain-0.2.0/tests/test_pdf.py
+-rw-r--r--   0 jackywong   (501) staff       (20)      621 2023-06-25 07:10:23.000000 BlitzChain-0.2.0/tests/test_qa.py
```

### Comparing `BlitzChain-0.1.4/LICENSE` & `BlitzChain-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.1.4/README.md` & `BlitzChain-0.2.0/README.md`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.1.4/blitzchain/api.py` & `BlitzChain-0.2.0/blitzchain/api.py`

 * *Files 26% similar despite different names*

```diff
@@ -87,9 +87,74 @@
             url,
             headers={
                 "Content-Type": "application/json",
                 "Authorization": "Bearer " + self.api_key
             },
             json=data
         )
+        return response.json()
+
+    def generative_code_qa(self, user_input: str, answer_fields: list,
+        conversation_id: str=None, limit: int=5, fields: list=None,
+        include_rerank: bool=False, minimum_rerank_score: float=0.7):
+        """Get an answer based on a question that you ask.
+        """
+        url =  self.base_url + "collection/generative-code-qa"
+        print(url)
+        data={
+            "collection": self.collection_name,
+            "userInput": user_input,
+            "answerFields": answer_fields,
+            "limit": limit,
+            "fields": fields,
+            "includeRerank": include_rerank,
+            "minimumRerankScore": minimum_rerank_score
+        }
+        if conversation_id:
+            data["conversationID"] = conversation_id
+        print(data)
+        response = requests.post(
+            url,
+            headers={
+                "Content-Type": "application/json",
+                "Authorization": "Bearer " + self.api_key
+            },
+            json=data
+        )
+        return response.json()
+
+    def list_objects(self, limit: int=5, offset: int=0, fields: list=None,
+                     where=None, sort=list):
+        api_url = self.base_url + "object/list"
+        print(api_url)
+        response = requests.post(
+            api_url,
+            headers={
+                "Content-Type": "application/json",
+                "Authorization": "Bearer " + self.api_key
+            },
+            json={
+                "collection": self.collection_name,
+                "limit": limit,
+                "offset": offset,
+                "fields": fields,
+                "where": where,
+                "sort": sort
+            }
+        )
+        print(response.content.decode())
+        return response.json()
+    
+    def count(self):
+        api_url = self.base_url + "object/count"
+        response = requests.get(
+            api_url,
+            headers={
+                "Content-Type": "application/json",
+                "Authorization": "Bearer " + self.api_key
+            },
+            params={
+                "collection": self.collection_name,
+            }
+        )
         print(response.content.decode())
         return response.json()
```

### Comparing `BlitzChain-0.1.4/tests/test_pdf.py` & `BlitzChain-0.2.0/tests/test_pdf.py`

 * *Files identical despite different names*

### Comparing `BlitzChain-0.1.4/tests/test_qa.py` & `BlitzChain-0.2.0/tests/test_qa.py`

 * *Files identical despite different names*

