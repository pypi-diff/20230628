# Comparing `tmp/biochatter-0.1.1.tar.gz` & `tmp/biochatter-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "biochatter-0.1.1.tar", max compression
+gzip compressed data, was "biochatter-0.1.2.tar", max compression
```

## Comparing `biochatter-0.1.1.tar` & `biochatter-0.1.2.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0     1066 2023-06-13 11:08:28.958016 biochatter-0.1.1/LICENSE
--rw-r--r--   0        0        0      144 2023-06-13 11:11:07.914635 biochatter-0.1.1/README.md
--rw-r--r--   0        0        0        0 2023-06-13 11:09:32.282374 biochatter-0.1.1/biochatter/__init__.py
--rw-r--r--   0        0        0     2672 2023-06-16 16:39:33.107276 biochatter-0.1.1/biochatter/_stats.py
--rw-r--r--   0        0        0    12406 2023-06-16 16:40:08.854325 biochatter-0.1.1/biochatter/llm_connect.py
--rw-r--r--   0        0        0     5226 2023-06-16 12:53:15.891015 biochatter-0.1.1/biochatter/vectorstore.py
--rw-r--r--   0        0        0      532 2023-06-16 16:53:37.078917 biochatter-0.1.1/pyproject.toml
--rw-r--r--   0        0        0     1022 1970-01-01 00:00:00.000000 biochatter-0.1.1/setup.py
--rw-r--r--   0        0        0      981 1970-01-01 00:00:00.000000 biochatter-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     1066 2023-06-13 11:08:28.958016 biochatter-0.1.2/LICENSE
+-rw-r--r--   0        0        0      453 2023-06-28 13:22:29.968048 biochatter-0.1.2/README.md
+-rw-r--r--   0        0        0        0 2023-06-13 11:09:32.282374 biochatter-0.1.2/biochatter/__init__.py
+-rw-r--r--   0        0        0     2672 2023-06-16 16:39:33.107276 biochatter-0.1.2/biochatter/_stats.py
+-rw-r--r--   0        0        0    12888 2023-06-28 13:06:39.433702 biochatter-0.1.2/biochatter/llm_connect.py
+-rw-r--r--   0        0        0     5226 2023-06-16 12:53:15.891015 biochatter-0.1.2/biochatter/vectorstore.py
+-rw-r--r--   0        0        0      667 2023-06-28 13:22:03.813541 biochatter-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0     1407 1970-01-01 00:00:00.000000 biochatter-0.1.2/setup.py
+-rw-r--r--   0        0        0     1338 1970-01-01 00:00:00.000000 biochatter-0.1.2/PKG-INFO
```

### Comparing `biochatter-0.1.1/LICENSE` & `biochatter-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `biochatter-0.1.1/biochatter/_stats.py` & `biochatter-0.1.2/biochatter/_stats.py`

 * *Files identical despite different names*

### Comparing `biochatter-0.1.1/biochatter/llm_connect.py` & `biochatter-0.1.2/biochatter/llm_connect.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,15 +1,18 @@
 # ChatGSE LLM connectivity
 # connect to API
 # keep track of message history
 # query API
 # correct response
 # update usage stats
 
-import streamlit as st
+try:
+    import streamlit as st
+except ImportError:
+    st = None
 
 from abc import ABC, abstractmethod
 import openai
 
 from langchain.chat_models import ChatOpenAI
 from langchain.schema import AIMessage, HumanMessage, SystemMessage
 from langchain.llms import HuggingFaceHub
@@ -161,37 +164,45 @@
 
         cor_msg = (
             "Correcting (using single sentences) ..."
             if self.split_correction
             else "Correcting ..."
         )
 
-        with st.spinner(cor_msg):
-            corrections = []
-            if self.split_correction:
-                nltk.download("punkt")
-                tokenizer = nltk.data.load("tokenizers/punkt/english.pickle")
-                sentences = tokenizer.tokenize(msg)
-                for sentence in sentences:
-                    correction = self._correct_response(sentence)
-
-                    if not str(correction).lower() in ["ok", "ok."]:
-                        corrections.append(correction)
-            else:
-                correction = self._correct_response(msg)
-
-                if not str(correction).lower() in ["ok", "ok."]:
-                    corrections.append(correction)
+        if st:
+            with st.spinner(cor_msg):
+                corrections = self._correct_query(text)
+        else:
+            corrections = self._correct_query(text)
 
         if not corrections:
             return (msg, token_usage, None)
 
         correction = "\n".join(corrections)
         return (msg, token_usage, correction)
 
+    def _correct_query(self, msg: str):
+        corrections = []
+        if self.split_correction:
+            nltk.download("punkt")
+            tokenizer = nltk.data.load("tokenizers/punkt/english.pickle")
+            sentences = tokenizer.tokenize(msg)
+            for sentence in sentences:
+                correction = self._correct_response(sentence)
+
+                if not str(correction).lower() in ["ok", "ok."]:
+                    corrections.append(correction)
+        else:
+            correction = self._correct_response(msg)
+
+            if not str(correction).lower() in ["ok", "ok."]:
+                corrections.append(correction)
+
+        return corrections
+
     @abstractmethod
     def _primary_query(self, text: str):
         pass
 
     @abstractmethod
     def _correct_response(self, msg: str):
         pass
@@ -205,22 +216,32 @@
             return
 
         sim_msg = (
             f"Performing similarity search to inject {self.docsum.n_results}"
             " fragments ..."
         )
 
-        with st.spinner(sim_msg):
+        if st:
+            with st.spinner(sim_msg):
+                statements = [
+                    doc.page_content
+                    for doc in self.docsum.similarity_search(
+                        text,
+                        self.docsum.n_results,
+                    )
+                ]
+        else:
             statements = [
                 doc.page_content
                 for doc in self.docsum.similarity_search(
                     text,
                     self.docsum.n_results,
                 )
             ]
+
         prompts = self.prompts["docsum_prompts"]
         if statements:
             self.current_statements = statements
             for i, prompt in enumerate(prompts):
                 if i == len(prompts) - 1:
                     self.append_system_message(
                         prompt.format(statements=statements)
```

### Comparing `biochatter-0.1.1/biochatter/vectorstore.py` & `biochatter-0.1.2/biochatter/vectorstore.py`

 * *Files identical despite different names*

### Comparing `biochatter-0.1.1/pyproject.toml` & `biochatter-0.1.2/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -1,24 +1,30 @@
 [tool.poetry]
 name = "biochatter"
-version = "0.1.1"
+version = "0.1.2"
 description = "Backend library for conversational AI in biomedicine"
 authors = ["Sebastian Lobentanzer <sebastian.lobentanzer@gmail.com>"]
 license = "MIT"
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.10"
 langchain = "^0.0.146"
 openai = "^0.27.8"
 pymupdf = "^1.22.3"
 pymilvus = "2.2.8"
 tiktoken = "^0.4.0"
-streamlit = "^1.23.1"
 nltk = "^3.8.1"
 redis = "^4.5.5"
 retry = "^0.9.2"
+streamlit = { version = "^1.23.1", optional = true }
 
+[tool.poetry.extras]
+streamlit = ["streamlit"]
+
+
+[tool.poetry.group.dev.dependencies]
+pytest = "^7.4.0"
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `biochatter-0.1.1/PKG-INFO` & `biochatter-0.1.2/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,26 +1,30 @@
 Metadata-Version: 2.1
 Name: biochatter
-Version: 0.1.1
+Version: 0.1.2
 Summary: Backend library for conversational AI in biomedicine
 License: MIT
 Author: Sebastian Lobentanzer
 Author-email: sebastian.lobentanzer@gmail.com
 Requires-Python: >=3.10,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Provides-Extra: streamlit
 Requires-Dist: langchain (>=0.0.146,<0.0.147)
 Requires-Dist: nltk (>=3.8.1,<4.0.0)
 Requires-Dist: openai (>=0.27.8,<0.28.0)
 Requires-Dist: pymilvus (==2.2.8)
 Requires-Dist: pymupdf (>=1.22.3,<2.0.0)
 Requires-Dist: redis (>=4.5.5,<5.0.0)
 Requires-Dist: retry (>=0.9.2,<0.10.0)
-Requires-Dist: streamlit (>=1.23.1,<2.0.0)
+Requires-Dist: streamlit (>=1.23.1,<2.0.0); extra == "streamlit"
 Requires-Dist: tiktoken (>=0.4.0,<0.5.0)
 Description-Content-Type: text/markdown
 
 # biochatter
-This repository will become a backend library for the connection of biomedical applications to conversational AI. Check back soon.
+This repository contains the `biochatter` Python package, a generic backend library for the connection of biomedical applications to conversational AI. Used in [ChatGSE](https://chat.biocypher.org), which is being developed at https://github.com/biocypher/ChatGSE. More to come, so stay tuned!
+
+## Installation
+To use the package, install it from PyPI, for instance using pip (`pip install biochatter`) or Poetry (`poetry add biochatter`).
```

