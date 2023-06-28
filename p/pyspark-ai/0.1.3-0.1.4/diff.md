# Comparing `tmp/pyspark_ai-0.1.3.tar.gz` & `tmp/pyspark_ai-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyspark_ai-0.1.3.tar", max compression
+gzip compressed data, was "pyspark_ai-0.1.4.tar", max compression
```

## Comparing `pyspark_ai-0.1.3.tar` & `pyspark_ai-0.1.4.tar`

### file list

```diff
@@ -1,13 +1,13 @@
--rw-r--r--   0        0        0    11357 2023-06-09 17:49:03.107485 pyspark_ai-0.1.3/LICENSE
--rw-r--r--   0        0        0     3735 2023-06-24 22:36:00.071711 pyspark_ai-0.1.3/README.md
--rw-r--r--   0        0        0      978 2023-06-25 04:09:18.391176 pyspark_ai-0.1.3/pyproject.toml
--rw-r--r--   0        0        0      101 2023-06-23 22:14:14.484356 pyspark_ai-0.1.3/pyspark_ai/__init__.py
--rw-r--r--   0        0        0     3945 2023-06-23 22:14:14.484674 pyspark_ai-0.1.3/pyspark_ai/ai_utils.py
--rw-r--r--   0        0        0     2718 2023-06-23 22:14:14.484982 pyspark_ai-0.1.3/pyspark_ai/cache.py
--rw-r--r--   0        0        0     1905 2023-06-23 22:14:14.485144 pyspark_ai-0.1.3/pyspark_ai/code_logger.py
--rw-r--r--   0        0        0     5224 2023-06-23 22:14:14.485334 pyspark_ai-0.1.3/pyspark_ai/file_cache.py
--rw-r--r--   0        0        0     1233 2023-06-23 22:14:14.485716 pyspark_ai-0.1.3/pyspark_ai/llm_chain_with_cache.py
--rw-r--r--   0        0        0     8878 2023-06-24 17:39:22.580299 pyspark_ai-0.1.3/pyspark_ai/prompt.py
--rw-r--r--   0        0        0    17498 2023-06-25 04:04:32.148887 pyspark_ai-0.1.3/pyspark_ai/pyspark_ai.py
--rw-r--r--   0        0        0      713 2023-06-23 22:14:14.486408 pyspark_ai-0.1.3/pyspark_ai/search_tool_with_cache.py
--rw-r--r--   0        0        0     4826 1970-01-01 00:00:00.000000 pyspark_ai-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-09 17:49:03.107485 pyspark_ai-0.1.4/LICENSE
+-rw-r--r--   0        0        0     3735 2023-06-24 22:36:00.071711 pyspark_ai-0.1.4/README.md
+-rw-r--r--   0        0        0      978 2023-06-28 00:17:47.823398 pyspark_ai-0.1.4/pyproject.toml
+-rw-r--r--   0        0        0      101 2023-06-23 22:14:14.484356 pyspark_ai-0.1.4/pyspark_ai/__init__.py
+-rw-r--r--   0        0        0     3945 2023-06-23 22:14:14.484674 pyspark_ai-0.1.4/pyspark_ai/ai_utils.py
+-rw-r--r--   0        0        0     2718 2023-06-23 22:14:14.484982 pyspark_ai-0.1.4/pyspark_ai/cache.py
+-rw-r--r--   0        0        0     1905 2023-06-23 22:14:14.485144 pyspark_ai-0.1.4/pyspark_ai/code_logger.py
+-rw-r--r--   0        0        0     5224 2023-06-23 22:14:14.485334 pyspark_ai-0.1.4/pyspark_ai/file_cache.py
+-rw-r--r--   0        0        0     1233 2023-06-23 22:14:14.485716 pyspark_ai-0.1.4/pyspark_ai/llm_chain_with_cache.py
+-rw-r--r--   0        0        0     9237 2023-06-27 23:52:32.149278 pyspark_ai-0.1.4/pyspark_ai/prompt.py
+-rw-r--r--   0        0        0    17498 2023-06-25 04:04:32.148887 pyspark_ai-0.1.4/pyspark_ai/pyspark_ai.py
+-rw-r--r--   0        0        0      713 2023-06-23 22:14:14.486408 pyspark_ai-0.1.4/pyspark_ai/search_tool_with_cache.py
+-rw-r--r--   0        0        0     4826 1970-01-01 00:00:00.000000 pyspark_ai-0.1.4/PKG-INFO
```

### Comparing `pyspark_ai-0.1.3/LICENSE` & `pyspark_ai-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/README.md` & `pyspark_ai-0.1.4/README.md`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/pyproject.toml` & `pyspark_ai-0.1.4/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["poetry-core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
 
 [tool.poetry]
 name = "pyspark-ai"
-version = "0.1.3"
+version = "0.1.4"
 description = "English SDK for Apache Spark"
 authors = ["Gengliang Wang <gengliang@apache.org>"]
 license = "Apache-2.0"
 readme = "README.md"
 homepage = "https://github.com/databrickslabs/pyspark-ai"
 classifiers = [
     "Development Status :: 3 - Alpha",
```

### Comparing `pyspark_ai-0.1.3/pyspark_ai/ai_utils.py` & `pyspark_ai-0.1.4/pyspark_ai/ai_utils.py`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/pyspark_ai/cache.py` & `pyspark_ai-0.1.4/pyspark_ai/cache.py`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/pyspark_ai/code_logger.py` & `pyspark_ai-0.1.4/pyspark_ai/code_logger.py`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/pyspark_ai/file_cache.py` & `pyspark_ai-0.1.4/pyspark_ai/file_cache.py`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/pyspark_ai/llm_chain_with_cache.py` & `pyspark_ai-0.1.4/pyspark_ai/llm_chain_with_cache.py`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/pyspark_ai/prompt.py` & `pyspark_ai-0.1.4/pyspark_ai/prompt.py`

 * *Files 4% similar despite different names*

```diff
@@ -19,15 +19,16 @@
 ```
 {query}
 ```
 I got the following answer from a web page:
 ```
 {web_content}
 ```
-Now help me write a SQL query to store the answer into a temp view.
+Now help me write a SQL query to store the answer into a temp view. 
+Give each column a clearly descriptive name (no abbreviations).
 Here is an example of how to store data into a temp view:
 ```
 CREATE OR REPLACE TEMP VIEW movies AS SELECT * FROM VALUES('Citizen Kane', 1941), ('Schindler\'s List', 1993) AS v1(title, year)
 ```
 {columns}
 The answer MUST contain query only.
 """
@@ -38,15 +39,15 @@
 
 TRANSFORM_TEMPLATE = """
 Given a Spark temp view `{view_name}` with the following columns:
 ```
 {columns}
 ```
 Write a Spark SQL query to retrieve: {desc}
-The answer MUST contain query only.
+The answer MUST contain query only. Ensure your answer is correct.
 """
 
 TRANSFORM_PROMPT = PromptTemplate(
     input_variables=["view_name", "columns", "desc"], template=TRANSFORM_TEMPLATE
 )
 
 EXPLAIN_PREFIX = """You are an Apache Spark SQL expert, who can summary what a dataframe retrieves. Given an analyzed 
@@ -113,26 +114,26 @@
     suffix=EXPLAIN_SUFFIX,
     input_variables=["input"],
     example_separator="\n\n",
 )
 
 PLOT_PROMPT_TEMPLATE = """
 You are an Apache Spark SQL expert programmer.
+It is forbidden to include old deprecated APIs in your code.
+For example, you will not use the pandas method "append" because it is deprecated.
 
-Given a pyspark dataframe `df`.
-
-The output columns of `df`:
+Given a pyspark dataframe `df`, with the output columns:
 {columns}
 
 And an explanation of `df`: {explain}
 
-Write python code to visualize the result of `df` using plotly.
-Your code must NOT include the method 'append'. 
-There is no need to install any package with pip. 
+Write Python code to visualize the result of `df` using plotly. Your code may NOT call "append" on any pandas dataframe.
+There is no need to install any package with pip. Do include any necessary import statements.
 Display the plot directly, instead of saving into an HTML.
+Remember to ensure that your output does NOT include "append" anywhere.
 
 Ensure that your code is correct.
 {instruction}
 """
 
 PLOT_PROMPT = PromptTemplate(
     input_variables=["columns", "explain", "instruction"], template=PLOT_PROMPT_TEMPLATE
```

### Comparing `pyspark_ai-0.1.3/pyspark_ai/pyspark_ai.py` & `pyspark_ai-0.1.4/pyspark_ai/pyspark_ai.py`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/pyspark_ai/search_tool_with_cache.py` & `pyspark_ai-0.1.4/pyspark_ai/search_tool_with_cache.py`

 * *Files identical despite different names*

### Comparing `pyspark_ai-0.1.3/PKG-INFO` & `pyspark_ai-0.1.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyspark-ai
-Version: 0.1.3
+Version: 0.1.4
 Summary: English SDK for Apache Spark
 Home-page: https://github.com/databrickslabs/pyspark-ai
 License: Apache-2.0
 Author: Gengliang Wang
 Author-email: gengliang@apache.org
 Requires-Python: >=3.8.1,<4.0.0
 Classifier: Development Status :: 3 - Alpha
```

