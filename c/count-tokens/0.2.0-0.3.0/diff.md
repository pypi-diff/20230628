# Comparing `tmp/count_tokens-0.2.0.tar.gz` & `tmp/count_tokens-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "count_tokens-0.2.0.tar", max compression
+gzip compressed data, was "count_tokens-0.3.0.tar", max compression
```

## Comparing `count_tokens-0.2.0.tar` & `count_tokens-0.3.0.tar`

### file list

```diff
@@ -1,5 +1,5 @@
--rw-r--r--   0        0        0     1193 2023-06-28 10:30:27.761691 count_tokens-0.2.0/README.md
--rw-r--r--   0        0        0        0 2023-06-28 06:49:18.286368 count_tokens-0.2.0/count_tokens/__init__.py
--rwxr-xr-x   0        0        0     1829 2023-06-28 08:38:37.683411 count_tokens-0.2.0/count_tokens/count.py
--rw-r--r--   0        0        0     1214 2023-06-28 10:04:30.239283 count_tokens-0.2.0/pyproject.toml
--rw-r--r--   0        0        0     2277 1970-01-01 00:00:00.000000 count_tokens-0.2.0/PKG-INFO
+-rw-r--r--   0        0        0     1184 2023-06-28 10:33:37.741280 count_tokens-0.3.0/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 06:49:18.286368 count_tokens-0.3.0/count_tokens/__init__.py
+-rwxr-xr-x   0        0        0     1829 2023-06-28 08:38:37.683411 count_tokens-0.3.0/count_tokens/count.py
+-rw-r--r--   0        0        0     1214 2023-06-28 10:33:47.690258 count_tokens-0.3.0/pyproject.toml
+-rw-r--r--   0        0        0     2268 1970-01-01 00:00:00.000000 count_tokens-0.3.0/PKG-INFO
```

### Comparing `count_tokens-0.2.0/README.md` & `count_tokens-0.3.0/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,14 @@
 
 Simple tool that have one purpose - count tokens in a text file.
 
 ## Requirements
 
 This package is using [tiktoken](https://github.com/openai/tiktoken) library for tokenization.
 
-```shell
 
 ## Installation
 For usage from comman line install the package in isolated environement with pipx:
 
 ```sh
 $ pipx install count-tokens
 ```
```

### Comparing `count_tokens-0.2.0/count_tokens/count.py` & `count_tokens-0.3.0/count_tokens/count.py`

 * *Files identical despite different names*

### Comparing `count_tokens-0.2.0/pyproject.toml` & `count_tokens-0.3.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "count-tokens"
-version = "0.2.0"
+version = "0.3.0"
 description = "Count number of tokens in the text file using toktoken tokenizer from OpenAI."
 authors = ["Krystian Safjan <ksafjan@gmail.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "count_tokens"}]
 
 keywords = ["count", "tokens", "toktoken", "openai", "tokenizer"]
```

### Comparing `count_tokens-0.2.0/PKG-INFO` & `count_tokens-0.3.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: count-tokens
-Version: 0.2.0
+Version: 0.3.0
 Summary: Count number of tokens in the text file using toktoken tokenizer from OpenAI.
 Home-page: https://github.com/izikeros/count_tokens
 License: MIT
 Keywords: count,tokens,toktoken,openai,tokenizer
 Author: Krystian Safjan
 Author-email: ksafjan@gmail.com
 Requires-Python: >=3.9,<4.0
@@ -33,15 +33,14 @@
 
 Simple tool that have one purpose - count tokens in a text file.
 
 ## Requirements
 
 This package is using [tiktoken](https://github.com/openai/tiktoken) library for tokenization.
 
-```shell
 
 ## Installation
 For usage from comman line install the package in isolated environement with pipx:
 
 ```sh
 $ pipx install count-tokens
 ```
```

