# Comparing `tmp/pandasai-0.6.5.tar.gz` & `tmp/pandasai-0.6.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pandasai-0.6.5.tar", max compression
+gzip compressed data, was "pandasai-0.6.6.tar", max compression
```

## Comparing `pandasai-0.6.5.tar` & `pandasai-0.6.6.tar`

### file list

```diff
@@ -1,36 +1,36 @@
--rw-r--r--   0        0        0     1055 2023-06-27 01:10:43.634056 pandasai-0.6.5/LICENSE
--rw-r--r--   0        0        0     7705 2023-06-27 01:10:43.638056 pandasai-0.6.5/README.md
--rw-r--r--   0        0        0    24805 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/__init__.py
--rw-r--r--   0        0        0     1235 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/constants.py
--rw-r--r--   0        0        0     1509 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/exceptions.py
--rw-r--r--   0        0        0        0 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/__init__.py
--rw-r--r--   0        0        0     3814 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/_optional.py
--rw-r--r--   0        0        0     5434 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/anonymizer.py
--rw-r--r--   0        0        0     1742 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/cache.py
--rw-r--r--   0        0        0      566 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/from_excel.py
--rw-r--r--   0        0        0     1493 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/notebook.py
--rw-r--r--   0        0        0     3471 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/save_chart.py
--rw-r--r--   0        0        0     9911 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/helpers/shortcuts.py
--rw-r--r--   0        0        0        0 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/__init__.py
--rw-r--r--   0        0        0     4091 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/azure_openai.py
--rw-r--r--   0        0        0    11077 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/base.py
--rw-r--r--   0        0        0      542 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/fake.py
--rw-r--r--   0        0        0     1213 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/falcon.py
--rw-r--r--   0        0        0     4518 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/google_palm.py
--rw-r--r--   0        0        0      577 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/langchain.py
--rw-r--r--   0        0        0     1482 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/open_assistant.py
--rw-r--r--   0        0        0     2932 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/openai.py
--rw-r--r--   0        0        0     1220 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/llm/starcoder.py
--rw-r--r--   0        0        0        0 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/middlewares/__init__.py
--rw-r--r--   0        0        0      663 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/middlewares/base.py
--rw-r--r--   0        0        0      558 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/middlewares/charts.py
--rw-r--r--   0        0        0      653 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/middlewares/streamlit.py
--rw-r--r--   0        0        0        0 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/prompts/__init__.py
--rw-r--r--   0        0        0      647 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/prompts/base.py
--rw-r--r--   0        0        0     1270 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/prompts/correct_error_prompt.py
--rw-r--r--   0        0        0     1076 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/prompts/correct_multiples_prompt.py
--rw-r--r--   0        0        0     1081 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/prompts/generate_python_code.py
--rw-r--r--   0        0        0      460 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/prompts/generate_response.py
--rw-r--r--   0        0        0     1072 2023-06-27 01:10:43.642057 pandasai-0.6.5/pandasai/prompts/multiple_dataframes.py
--rw-r--r--   0        0        0     1900 2023-06-27 01:10:43.646057 pandasai-0.6.5/pyproject.toml
--rw-r--r--   0        0        0     8919 1970-01-01 00:00:00.000000 pandasai-0.6.5/PKG-INFO
+-rw-r--r--   0        0        0     1055 2023-06-28 12:51:14.901125 pandasai-0.6.6/LICENSE
+-rw-r--r--   0        0        0     7705 2023-06-28 12:51:14.901125 pandasai-0.6.6/README.md
+-rw-r--r--   0        0        0    24846 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/__init__.py
+-rw-r--r--   0        0        0     1235 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/constants.py
+-rw-r--r--   0        0        0     1509 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/exceptions.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/__init__.py
+-rw-r--r--   0        0        0     3814 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/_optional.py
+-rw-r--r--   0        0        0     5434 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/anonymizer.py
+-rw-r--r--   0        0        0     1742 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/cache.py
+-rw-r--r--   0        0        0      566 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/from_excel.py
+-rw-r--r--   0        0        0     1493 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/notebook.py
+-rw-r--r--   0        0        0     3471 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/save_chart.py
+-rw-r--r--   0        0        0     9911 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/helpers/shortcuts.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/__init__.py
+-rw-r--r--   0        0        0     4335 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/azure_openai.py
+-rw-r--r--   0        0        0    11156 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/base.py
+-rw-r--r--   0        0        0      542 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/fake.py
+-rw-r--r--   0        0        0     1213 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/falcon.py
+-rw-r--r--   0        0        0     4440 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/google_palm.py
+-rw-r--r--   0        0        0      577 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/langchain.py
+-rw-r--r--   0        0        0     1482 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/open_assistant.py
+-rw-r--r--   0        0        0     3176 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/openai.py
+-rw-r--r--   0        0        0     1220 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/llm/starcoder.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/middlewares/__init__.py
+-rw-r--r--   0        0        0      663 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/middlewares/base.py
+-rw-r--r--   0        0        0      948 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/middlewares/charts.py
+-rw-r--r--   0        0        0      653 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/middlewares/streamlit.py
+-rw-r--r--   0        0        0        0 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/prompts/__init__.py
+-rw-r--r--   0        0        0      647 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/prompts/base.py
+-rw-r--r--   0        0        0     1270 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/prompts/correct_error_prompt.py
+-rw-r--r--   0        0        0     1076 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/prompts/correct_multiples_prompt.py
+-rw-r--r--   0        0        0     1081 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/prompts/generate_python_code.py
+-rw-r--r--   0        0        0      460 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/prompts/generate_response.py
+-rw-r--r--   0        0        0     1072 2023-06-28 12:51:14.909125 pandasai-0.6.6/pandasai/prompts/multiple_dataframes.py
+-rw-r--r--   0        0        0     1900 2023-06-28 12:51:14.913125 pandasai-0.6.6/pyproject.toml
+-rw-r--r--   0        0        0     8919 1970-01-01 00:00:00.000000 pandasai-0.6.6/PKG-INFO
```

### Comparing `pandasai-0.6.5/LICENSE` & `pandasai-0.6.6/LICENSE`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/README.md` & `pandasai-0.6.6/README.md`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/__init__.py` & `pandasai-0.6.6/pandasai/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -40,14 +40,15 @@
 import re
 import sys
 import uuid
 import time
 from contextlib import redirect_stdout
 from typing import List, Optional, Union, Dict, Type
 import importlib.metadata
+
 __version__ = importlib.metadata.version(__package__ or __name__)
 import astor
 import pandas as pd
 from .constants import (
     WHITELISTED_BUILTINS,
     WHITELISTED_LIBRARIES,
 )
@@ -101,15 +102,15 @@
         generated and execution step on the prompt. Default to False
         _is_conversational_answer (bool, optional): Whether to return answer in
         conversational form. Default to False
         _enforce_privacy (bool, optional): Do not display the data on prompt in case of
         Sensitive data. Default to False
         _max_retries (int, optional): max no. of tries to generate code on failure.
         Default to 3
-        _is_notebook (bool, optional): Whether to run code in notebook. Default to False
+        _in_notebook (bool, optional): Whether to run code in notebook. Default to False
         _original_instructions (dict, optional): The dict of instruction to run. Default
         to None
         _cache (Cache, optional): Cache object to store the results. Default to None
         _enable_cache (bool, optional): Whether to enable cache. Default to True
         _prompt_id (str, optional): Unique ID to differentiate calls. Default to None
         _middlewares (List[Middleware], optional): List of middlewares to run. Default
         to [ChartsMiddleware()]
@@ -131,15 +132,15 @@
     """
 
     _llm: LLM
     _verbose: bool = False
     _is_conversational_answer: bool = False
     _enforce_privacy: bool = False
     _max_retries: int = 3
-    _is_notebook: bool = False
+    _in_notebook: bool = False
     _original_instructions: dict = {
         "question": None,
         "df_head": None,
         "num_rows": None,
         "num_columns": None,
     }
     _cache: Cache = None
@@ -307,14 +308,15 @@
 
         Returns (str): Answer to the Input Questions about the DataFrame
 
         """
 
         self._start_time = time.time()
 
+        self.log(f"Question: {prompt}")
         self.log(f"Running PandasAI with {self._llm.type} LLM...")
 
         self._prompt_id = str(uuid.uuid4())
         self.log(f"Prompt ID: {self._prompt_id}")
 
         try:
             if self._enable_cache and self._cache and self._cache.get(prompt):
```

### Comparing `pandasai-0.6.5/pandasai/constants.py` & `pandasai-0.6.6/pandasai/constants.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/exceptions.py` & `pandasai-0.6.6/pandasai/exceptions.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/helpers/_optional.py` & `pandasai-0.6.6/pandasai/helpers/_optional.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/helpers/anonymizer.py` & `pandasai-0.6.6/pandasai/helpers/anonymizer.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/helpers/cache.py` & `pandasai-0.6.6/pandasai/helpers/cache.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/helpers/from_excel.py` & `pandasai-0.6.6/pandasai/helpers/from_excel.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/helpers/notebook.py` & `pandasai-0.6.6/pandasai/helpers/notebook.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/helpers/save_chart.py` & `pandasai-0.6.6/pandasai/helpers/save_chart.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/helpers/shortcuts.py` & `pandasai-0.6.6/pandasai/helpers/shortcuts.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/llm/azure_openai.py` & `pandasai-0.6.6/pandasai/llm/azure_openai.py`

 * *Files 5% similar despite different names*

```diff
@@ -83,14 +83,21 @@
 
         if deployment_name is None:
             raise UnsupportedOpenAIModelError("Model deployment name is required.")
 
         self.is_chat_model = is_chat_model
         self.engine = deployment_name
 
+        self.openai_proxy = kwargs.get("openai_proxy") or os.getenv("OPENAI_PROXY")
+        if self.openai_proxy:
+            openai.proxy = {
+                "http": self.openai_proxy,
+                "https": self.openai_proxy
+            }
+
         self._set_params(**kwargs)
 
     @property
     def _default_params(self) -> Dict[str, Any]:
         """Get the default parameters for calling OpenAI API
 
         Returns: A dict of Default Params
```

### Comparing `pandasai-0.6.5/pandasai/llm/base.py` & `pandasai-0.6.6/pandasai/llm/base.py`

 * *Files 1% similar despite different names*

```diff
@@ -148,14 +148,16 @@
     api_token: str
     temperature: float = 0
     max_tokens: int = 512
     top_p: float = 1
     frequency_penalty: float = 0
     presence_penalty: float = 0.6
     stop: Optional[str] = None
+    # support explicit proxy for OpenAI
+    openai_proxy: Optional[str] = None
 
     def _set_params(self, **kwargs):
         """
         Set Parameters
         Args:
             **kwargs: ["model", "engine", "deployment_id", "temperature","max_tokens",
             "top_p", "frequency_penalty", "presence_penalty", "stop", ]
```

### Comparing `pandasai-0.6.5/pandasai/llm/fake.py` & `pandasai-0.6.6/pandasai/llm/fake.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/llm/falcon.py` & `pandasai-0.6.6/pandasai/llm/falcon.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/llm/google_palm.py` & `pandasai-0.6.6/pandasai/llm/google_palm.py`

 * *Files 5% similar despite different names*

```diff
@@ -134,16 +134,14 @@
             prompt (str): Prompt
 
         Returns:
             str: LLM response
         """
         self._validate()
 
-        vertexai = self.vertexai  # --fix
-        print(vertexai.__version__)
         from vertexai.preview.language_models import (
             CodeGenerationModel,
             TextGenerationModel,
         )
 
         if self.model == "code-bison@001":
             code_generation = CodeGenerationModel.from_pretrained(self.model)
```

### Comparing `pandasai-0.6.5/pandasai/llm/langchain.py` & `pandasai-0.6.6/pandasai/llm/langchain.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/llm/open_assistant.py` & `pandasai-0.6.6/pandasai/llm/open_assistant.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/llm/openai.py` & `pandasai-0.6.6/pandasai/llm/openai.py`

 * *Files 8% similar despite different names*

```diff
@@ -61,14 +61,21 @@
         """
 
         self.api_token = api_token or os.getenv("OPENAI_API_KEY") or None
         if self.api_token is None:
             raise APIKeyNotFoundError("OpenAI API key is required")
         openai.api_key = self.api_token
 
+        self.openai_proxy = kwargs.get("openai_proxy") or os.getenv("OPENAI_PROXY")
+        if self.openai_proxy:
+            openai.proxy = {
+                "http": self.openai_proxy,
+                "https": self.openai_proxy
+            }
+
         self._set_params(**kwargs)
 
     @property
     def _default_params(self) -> Dict[str, Any]:
         """Get the default parameters for calling OpenAI API"""
         return {
             **super()._default_params,
```

### Comparing `pandasai-0.6.5/pandasai/llm/starcoder.py` & `pandasai-0.6.6/pandasai/llm/starcoder.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/middlewares/base.py` & `pandasai-0.6.6/pandasai/middlewares/base.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/middlewares/streamlit.py` & `pandasai-0.6.6/pandasai/middlewares/streamlit.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/prompts/base.py` & `pandasai-0.6.6/pandasai/prompts/base.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/prompts/correct_error_prompt.py` & `pandasai-0.6.6/pandasai/prompts/correct_error_prompt.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/prompts/correct_multiples_prompt.py` & `pandasai-0.6.6/pandasai/prompts/correct_multiples_prompt.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/prompts/generate_python_code.py` & `pandasai-0.6.6/pandasai/prompts/generate_python_code.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pandasai/prompts/multiple_dataframes.py` & `pandasai-0.6.6/pandasai/prompts/multiple_dataframes.py`

 * *Files identical despite different names*

### Comparing `pandasai-0.6.5/pyproject.toml` & `pandasai-0.6.6/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pandasai"
-version = "0.6.5"
+version = "0.6.6"
 description = "Pandas AI is a Python library that integrates generative artificial intelligence capabilities into Pandas, making dataframes conversational."
 authors = ["Gabriele Venturi"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "pandasai"}]
 
 [tool.poetry.dependencies]
```

### Comparing `pandasai-0.6.5/PKG-INFO` & `pandasai-0.6.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pandasai
-Version: 0.6.5
+Version: 0.6.6
 Summary: Pandas AI is a Python library that integrates generative artificial intelligence capabilities into Pandas, making dataframes conversational.
 License: MIT
 Author: Gabriele Venturi
 Requires-Python: >=3.9, !=2.7.*, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, !=3.4.*, !=3.5.*, !=3.6.*, !=3.7.*, !=3.8.*
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
```

