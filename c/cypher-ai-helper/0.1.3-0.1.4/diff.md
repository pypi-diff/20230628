# Comparing `tmp/cypher_ai_helper-0.1.3.tar.gz` & `tmp/cypher_ai_helper-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cypher_ai_helper-0.1.3.tar", max compression
+gzip compressed data, was "cypher_ai_helper-0.1.4.tar", max compression
```

## Comparing `cypher_ai_helper-0.1.3.tar` & `cypher_ai_helper-0.1.4.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0     1076 2023-06-28 13:18:08.702676 cypher_ai_helper-0.1.3/LICENSE
--rw-r--r--   0        0        0     2487 2023-06-28 13:18:08.702676 cypher_ai_helper-0.1.3/README.md
--rw-r--r--   0        0        0        0 2023-06-28 13:18:08.702676 cypher_ai_helper-0.1.3/cypher_ai_helper/__init__.py
--rw-r--r--   0        0        0     7304 2023-06-28 13:18:08.702676 cypher_ai_helper-0.1.3/cypher_ai_helper/main.py
--rw-r--r--   0        0        0     1008 2023-06-28 13:18:08.702676 cypher_ai_helper-0.1.3/cypher_ai_helper/system_prompt
--rw-r--r--   0        0        0       81 2023-06-28 13:18:08.702676 cypher_ai_helper-0.1.3/cypher_ai_helper/user_prompt
--rw-r--r--   0        0        0     5390 2023-06-28 13:18:08.702676 cypher_ai_helper-0.1.3/cypher_ai_helper/utils.py
--rw-r--r--   0        0        0      916 2023-06-28 13:18:27.918804 cypher_ai_helper-0.1.3/pyproject.toml
--rw-r--r--   0        0        0     3036 1970-01-01 00:00:00.000000 cypher_ai_helper-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0     1076 2023-06-28 13:38:18.205144 cypher_ai_helper-0.1.4/LICENSE
+-rw-r--r--   0        0        0     2487 2023-06-28 13:38:18.205144 cypher_ai_helper-0.1.4/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 13:38:18.205144 cypher_ai_helper-0.1.4/cypher_ai_helper/__init__.py
+-rw-r--r--   0        0        0     7304 2023-06-28 13:38:18.205144 cypher_ai_helper-0.1.4/cypher_ai_helper/main.py
+-rw-r--r--   0        0        0     1008 2023-06-28 13:38:18.205144 cypher_ai_helper-0.1.4/cypher_ai_helper/system_prompt
+-rw-r--r--   0        0        0       81 2023-06-28 13:38:18.205144 cypher_ai_helper-0.1.4/cypher_ai_helper/user_prompt
+-rw-r--r--   0        0        0     5390 2023-06-28 13:38:18.205144 cypher_ai_helper-0.1.4/cypher_ai_helper/utils.py
+-rw-r--r--   0        0        0      941 2023-06-28 13:38:36.541894 cypher_ai_helper-0.1.4/pyproject.toml
+-rw-r--r--   0        0        0     3310 1970-01-01 00:00:00.000000 cypher_ai_helper-0.1.4/PKG-INFO
```

### Comparing `cypher_ai_helper-0.1.3/LICENSE` & `cypher_ai_helper-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `cypher_ai_helper-0.1.3/README.md` & `cypher_ai_helper-0.1.4/README.md`

 * *Files identical despite different names*

### Comparing `cypher_ai_helper-0.1.3/cypher_ai_helper/main.py` & `cypher_ai_helper-0.1.4/cypher_ai_helper/main.py`

 * *Files identical despite different names*

### Comparing `cypher_ai_helper-0.1.3/cypher_ai_helper/system_prompt` & `cypher_ai_helper-0.1.4/cypher_ai_helper/system_prompt`

 * *Files identical despite different names*

### Comparing `cypher_ai_helper-0.1.3/cypher_ai_helper/utils.py` & `cypher_ai_helper-0.1.4/cypher_ai_helper/utils.py`

 * *Files identical despite different names*

### Comparing `cypher_ai_helper-0.1.3/PKG-INFO` & `cypher_ai_helper-0.1.4/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,21 +1,25 @@
 Metadata-Version: 2.1
 Name: cypher-ai-helper
-Version: 0.1.3
+Version: 0.1.4
 Summary: A simple helper to create and execute Cypher queries for Neo4j
 License: MIT
 Author: Trayan Azarov
 Author-email: trayan.azarov@amikos.tech
-Requires-Python: >=3.11,<4.0
+Requires-Python: >=3.10,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: neo4j (>=5.9.0,<6.0.0)
 Requires-Dist: openai (>=0.27.8,<0.28.0)
 Requires-Dist: pydantic (>=1.10.9,<2.0.0)
+Project-URL: Bug Tracker, https://github.com/amikos-tech/cypher-ai-helper/issues
+Project-URL: Homepage, https://github.com/amikos-tech/cypher-ai-helper/
+Project-URL: Source, https://github.com/amikos-tech/cypher-ai-helper/
 Description-Content-Type: text/markdown
 
 # Cypher AI Helper
 
 A helper library for creating Cypher queries with OpenAI API.
 
 ## Installation
```

