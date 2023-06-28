# Comparing `tmp/count_tokens-0.1.0.tar.gz` & `tmp/count_tokens-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "count_tokens-0.1.0.tar", max compression
+gzip compressed data, was "count_tokens-0.2.0.tar", max compression
```

## Comparing `count_tokens-0.1.0.tar` & `count_tokens-0.2.0.tar`

### file list

```diff
@@ -1,5 +1,5 @@
--rw-r--r--   0        0        0     1024 2023-06-28 08:27:50.829257 count_tokens-0.1.0/README.md
--rw-r--r--   0        0        0        0 2023-06-28 06:49:18.286368 count_tokens-0.1.0/count_tokens/__init__.py
--rwxr-xr-x   0        0        0     1454 2023-06-28 06:59:03.349100 count_tokens-0.1.0/count_tokens/count.py
--rw-r--r--   0        0        0      586 2023-06-28 07:34:02.793057 count_tokens-0.1.0/pyproject.toml
--rw-r--r--   0        0        0     1598 1970-01-01 00:00:00.000000 count_tokens-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0     1193 2023-06-28 10:30:27.761691 count_tokens-0.2.0/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 06:49:18.286368 count_tokens-0.2.0/count_tokens/__init__.py
+-rwxr-xr-x   0        0        0     1829 2023-06-28 08:38:37.683411 count_tokens-0.2.0/count_tokens/count.py
+-rw-r--r--   0        0        0     1214 2023-06-28 10:04:30.239283 count_tokens-0.2.0/pyproject.toml
+-rw-r--r--   0        0        0     2277 1970-01-01 00:00:00.000000 count_tokens-0.2.0/PKG-INFO
```

### Comparing `count_tokens-0.1.0/README.md` & `count_tokens-0.2.0/README.md`

 * *Files 15% similar despite different names*

```diff
@@ -1,33 +1,38 @@
 # Count tokens
 
-Simple tools that have one purpose - count tokens in a text file.
+![img](https://img.shields.io/pypi/v/count-tokens.svg)
+![](https://img.shields.io/pypi/pyversions/count-tokens.svg)
+![](https://img.shields.io/pypi/dm/count-tokens.svg)
+
+
+Simple tool that have one purpose - count tokens in a text file.
 
 ## Requirements
 
 This package is using [tiktoken](https://github.com/openai/tiktoken) library for tokenization.
 
 ```shell
 
 ## Installation
 For usage from comman line install the package in isolated environement with pipx:
 
 ```sh
-$ pipx install count_tokens
+$ pipx install count-tokens
 ```
 
 or install it in your current environment with pip.
 
 
 ## Usage
 Open terminal and run:
 
 ```shell
 $ count-tokens document.txt
-``` 
+```
 
 You should see something like this:
 
 ```shell
 File: document.txt
 Encoding: cl100k_base
 Number of tokens: 67
```

### Comparing `count_tokens-0.1.0/count_tokens/count.py` & `count_tokens-0.2.0/count_tokens/count.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,39 @@
 #!/usr/bin/env python3
 import argparse
 
+import pathlib
 import tiktoken
 
 
 def num_tokens_from_string(string: str, encoding_name: str = "cl100k_base") -> int:
-    """Returns the number of tokens in a text string."""
+    """Return the number of tokens in a text string.
+
+    Args:
+        string: The text string to count the tokens in.
+        encoding_name: The name of the encoding to use.
+
+    Returns:
+        The number of tokens in the text string.
+    """
     encoding = tiktoken.get_encoding(encoding_name)
-    num_tokens = len(encoding.encode(string))
-    return num_tokens
+    return len(encoding.encode(string))
 
 
-num_tokens_from_string(
-    "tiktoken is great!",
-)
+def count_tokens(file_path: str, encoding_name: str):
+    """Return the number of tokens in a text file.
 
+    Args:
+        file_path: The path to the text file to count the tokens in.
+        encoding_name: The name of the encoding to use.
 
-def count_tokens(file_path, encoding_name):
-    with open(file_path) as file:
-        text = file.read()
+    Returns:
+        The number of tokens in the text file.
+    """
+    text = pathlib.Path(file_path).read_text()
     return num_tokens_from_string(text, encoding_name)
 
 
 def main():
     parser = argparse.ArgumentParser(
         description="Count the number of tokens in a text file."
     )
```

### Comparing `count_tokens-0.1.0/PKG-INFO` & `count_tokens-0.2.0/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,49 +1,64 @@
 Metadata-Version: 2.1
 Name: count-tokens
-Version: 0.1.0
-Summary: count number of tokens in the text file using toktoken tokenizer from OpenAI
+Version: 0.2.0
+Summary: Count number of tokens in the text file using toktoken tokenizer from OpenAI.
+Home-page: https://github.com/izikeros/count_tokens
 License: MIT
+Keywords: count,tokens,toktoken,openai,tokenizer
 Author: Krystian Safjan
 Author-email: ksafjan@gmail.com
 Requires-Python: >=3.9,<4.0
+Classifier: Development Status :: 3 - Alpha
+Classifier: Environment :: Console
+Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
+Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Topic :: Software Development :: Libraries :: Python Modules
+Classifier: Topic :: Utilities
 Requires-Dist: tiktoken (>=0.4.0,<0.5.0)
+Project-URL: Documentation, https://github.com/izikeros/count_tokens
+Project-URL: Repository, https://github.com/izikeros/count_tokens
 Description-Content-Type: text/markdown
 
 # Count tokens
 
-Simple tools that have one purpose - count tokens in a text file.
+![img](https://img.shields.io/pypi/v/count-tokens.svg)
+![](https://img.shields.io/pypi/pyversions/count-tokens.svg)
+![](https://img.shields.io/pypi/dm/count-tokens.svg)
+
+
+Simple tool that have one purpose - count tokens in a text file.
 
 ## Requirements
 
 This package is using [tiktoken](https://github.com/openai/tiktoken) library for tokenization.
 
 ```shell
 
 ## Installation
 For usage from comman line install the package in isolated environement with pipx:
 
 ```sh
-$ pipx install count_tokens
+$ pipx install count-tokens
 ```
 
 or install it in your current environment with pip.
 
 
 ## Usage
 Open terminal and run:
 
 ```shell
 $ count-tokens document.txt
-``` 
+```
 
 You should see something like this:
 
 ```shell
 File: document.txt
 Encoding: cl100k_base
 Number of tokens: 67
```

