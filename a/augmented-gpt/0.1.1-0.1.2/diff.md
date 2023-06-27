# Comparing `tmp/augmented_gpt-0.1.1.tar.gz` & `tmp/augmented_gpt-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "augmented_gpt-0.1.1.tar", max compression
+gzip compressed data, was "augmented_gpt-0.1.2.tar", max compression
```

## Comparing `augmented_gpt-0.1.1.tar` & `augmented_gpt-0.1.2.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0     1067 2023-06-26 23:24:16.694298 augmented_gpt-0.1.1/LICENSE
--rw-r--r--   0        0        0      141 2023-06-27 02:31:59.239584 augmented_gpt-0.1.1/README.md
--rw-r--r--   0        0        0      352 2023-06-26 23:24:16.718299 augmented_gpt-0.1.1/augmented_gpt/__init__.py
--rw-r--r--   0        0        0     4278 2023-06-26 23:24:16.722299 augmented_gpt-0.1.1/augmented_gpt/augmented_gpt.py
--rw-r--r--   0        0        0     2563 2023-06-26 23:24:16.714299 augmented_gpt-0.1.1/augmented_gpt/decorators.py
--rw-r--r--   0        0        0     1913 2023-06-26 23:24:16.714299 augmented_gpt-0.1.1/augmented_gpt/message.py
--rw-r--r--   0        0        0     1331 2023-06-26 23:24:16.722299 augmented_gpt-0.1.1/augmented_gpt/plugins/__init__.py
--rw-r--r--   0        0        0      534 2023-06-26 23:24:16.722299 augmented_gpt-0.1.1/augmented_gpt/plugins/calc.py
--rw-r--r--   0        0        0     2847 2023-06-26 23:24:16.722299 augmented_gpt-0.1.1/augmented_gpt/plugins/memory.py
--rw-r--r--   0        0        0      775 2023-06-27 02:39:45.947980 augmented_gpt-0.1.1/pyproject.toml
--rw-r--r--   0        0        0     1110 1970-01-01 00:00:00.000000 augmented_gpt-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     1067 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/LICENSE
+-rw-r--r--   0        0        0      141 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/README.md
+-rw-r--r--   0        0        0      352 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/augmented_gpt/__init__.py
+-rw-r--r--   0        0        0     4583 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/augmented_gpt/augmented_gpt.py
+-rw-r--r--   0        0        0     2563 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/augmented_gpt/decorators.py
+-rw-r--r--   0        0        0     1913 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/augmented_gpt/message.py
+-rw-r--r--   0        0        0     1331 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/augmented_gpt/plugins/__init__.py
+-rw-r--r--   0        0        0      534 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/augmented_gpt/plugins/calc.py
+-rw-r--r--   0        0        0     2847 2023-06-27 22:32:39.726105 augmented_gpt-0.1.2/augmented_gpt/plugins/memory.py
+-rw-r--r--   0        0        0      775 2023-06-27 22:32:39.730105 augmented_gpt-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0     1110 1970-01-01 00:00:00.000000 augmented_gpt-0.1.2/PKG-INFO
```

### Comparing `augmented_gpt-0.1.1/LICENSE` & `augmented_gpt-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `augmented_gpt-0.1.1/augmented_gpt/augmented_gpt.py` & `augmented_gpt-0.1.2/augmented_gpt/augmented_gpt.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,24 +1,36 @@
 from typing import *
 from .message import *
 from dotenv import dotenv_values
 import inspect
 from inspect import Parameter
 import openai
 import logging
+import os
+
+openai_api_key = None
 
 
 class AugmentedGPT:
+    @staticmethod
+    def set_api_key(key: str):
+        global openai_api_key
+        openai_api_key = key
+
     def __init__(
         self,
         functions: List[Callable] = [],
         plugins: List["Plugin"] = [],
         debug=False,
     ):
-        openai.api_key = dotenv_values()["OPENAI_API_KEY"]
+        api_key = dotenv_values().get(
+            "OPENAI_API_KEY", os.environ.get("OPENAI_API_KEY", openai_api_key)
+        )
+        assert api_key is not None, "Missing OPENAI_API_KEY"
+        openai.api_key = api_key
         self.logger = logging.getLogger("AugmentedGPT")
         self.logger.setLevel(logging.DEBUG if debug else logging.INFO)
         self.__functions: Dict[str, Tuple[Any, Callable]] = {}
         for f in functions:
             self.add_function(f)
         self.__plugins = {}
         for p in plugins:
```

### Comparing `augmented_gpt-0.1.1/augmented_gpt/decorators.py` & `augmented_gpt-0.1.2/augmented_gpt/decorators.py`

 * *Files identical despite different names*

### Comparing `augmented_gpt-0.1.1/augmented_gpt/message.py` & `augmented_gpt-0.1.2/augmented_gpt/message.py`

 * *Files identical despite different names*

### Comparing `augmented_gpt-0.1.1/augmented_gpt/plugins/__init__.py` & `augmented_gpt-0.1.2/augmented_gpt/plugins/__init__.py`

 * *Files identical despite different names*

### Comparing `augmented_gpt-0.1.1/augmented_gpt/plugins/calc.py` & `augmented_gpt-0.1.2/augmented_gpt/plugins/calc.py`

 * *Files identical despite different names*

### Comparing `augmented_gpt-0.1.1/augmented_gpt/plugins/memory.py` & `augmented_gpt-0.1.2/augmented_gpt/plugins/memory.py`

 * *Files identical despite different names*

### Comparing `augmented_gpt-0.1.1/pyproject.toml` & `augmented_gpt-0.1.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "augmented_gpt"
-version = "0.1.1"
+version = "0.1.2"
 description = "ChatGPT API wrapper, argumented with functions"
 # documentation = "https://github.com/wenyuzhao/augmented-gpt"
 authors = ["Wenyu Zhao <wenyu.zhao@anu.edu.au>"]
 license = "MIT"
 readme = "README.md"
 repository = "https://github.com/wenyuzhao/augmented-gpt"
 packages = [{include = "augmented_gpt"}]
```

### Comparing `augmented_gpt-0.1.1/PKG-INFO` & `augmented_gpt-0.1.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: augmented-gpt
-Version: 0.1.1
+Version: 0.1.2
 Summary: ChatGPT API wrapper, argumented with functions
 Home-page: https://github.com/wenyuzhao/augmented-gpt
 License: MIT
 Keywords: chatgpt,gpt
 Author: Wenyu Zhao
 Author-email: wenyu.zhao@anu.edu.au
 Requires-Python: >=3.10,<3.13
```

