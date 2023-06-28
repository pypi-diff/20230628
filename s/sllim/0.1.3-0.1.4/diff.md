# Comparing `tmp/sllim-0.1.3.tar.gz` & `tmp/sllim-0.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sllim-0.1.3.tar", max compression
+gzip compressed data, was "sllim-0.1.4.tar", max compression
```

## Comparing `sllim-0.1.3.tar` & `sllim-0.1.4.tar`

### file list

```diff
@@ -1,5 +1,5 @@
--rw-r--r--   0        0        0     1060 2023-05-15 16:22:10.877704 sllim-0.1.3/LICENSE
--rw-r--r--   0        0        0     1383 2023-05-29 12:04:13.123988 sllim-0.1.3/README.md
--rw-r--r--   0        0        0      322 2023-05-29 12:04:35.638689 sllim-0.1.3/pyproject.toml
--rw-r--r--   0        0        0     9555 2023-05-29 12:04:13.125155 sllim-0.1.3/sllim/__init__.py
--rw-r--r--   0        0        0     1869 1970-01-01 00:00:00.000000 sllim-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0     1060 2023-05-15 16:22:10.877704 sllim-0.1.4/LICENSE
+-rw-r--r--   0        0        0     1383 2023-05-29 12:04:13.123988 sllim-0.1.4/README.md
+-rw-r--r--   0        0        0      322 2023-06-28 15:14:17.567343 sllim-0.1.4/pyproject.toml
+-rw-r--r--   0        0        0    10733 2023-06-28 15:18:02.548828 sllim-0.1.4/sllim/__init__.py
+-rw-r--r--   0        0        0     1869 1970-01-01 00:00:00.000000 sllim-0.1.4/PKG-INFO
```

### Comparing `sllim-0.1.3/LICENSE` & `sllim-0.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `sllim-0.1.3/README.md` & `sllim-0.1.4/README.md`

 * *Files identical despite different names*

### Comparing `sllim-0.1.3/sllim/__init__.py` & `sllim-0.1.4/sllim/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -128,18 +128,64 @@
         if k in default_params and v != default_params[k]
     }
     response = openai.ChatCompletion.create(
         model=model,
         messages=messages,
         max_tokens=max_tokens,
         **kwargs,
-    )
+    ).choices[0].message
 
-    return response.choices[0].message.content
+    if response.get("content"):
+        return response.content
 
+    raise Exception("No content found in response.")
+
+
+@catch
+@cache
+def call(
+    messages,
+    model="gpt-3.5-turbo",
+    max_tokens: int = 256,
+    functions: Optional[list[dict]] = None,
+    temperature: float = 1,
+    top_p: float = 1,
+    n: int = 1,
+    stop: Optional[str | list[str]] = None,
+    presence_penalty: float = 0,
+    frequency_penalty: float = 0,
+    logit_bias: Optional[dict[int, float]] = None,
+    cache_version: Optional[str] = None,
+) -> str:
+    default_params = {
+        "temperature": 1,
+        "top_p": 1,
+        "n": 1,
+        "functions": None,
+        "stop": None,
+        "presence_penalty": 0,
+        "frequency_penalty": 0,
+        "logit_bias": None,
+    }
+    kwargs = {
+        k: v
+        for k, v in locals().items()
+        if k in default_params and v != default_params[k]
+    }
+    response = openai.ChatCompletion.create(
+        model=model,
+        messages=messages,
+        max_tokens=max_tokens,
+        **kwargs,
+    ).choices[0].message
+    
+    if response.get("function_call"):
+        return response.function_call
+    
+    raise Exception("No function call found in response.")
 
 @catch
 @cache
 def complete(
     prompt: str = "<|endoftext|>",
     model: str = "text-davinci-003",
     max_tokens: int = 16,
```

### Comparing `sllim-0.1.3/PKG-INFO` & `sllim-0.1.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 Metadata-Version: 2.1
 Name: sllim
-Version: 0.1.3
+Version: 0.1.4
 Summary: Fixing the openai api
 Author: Kaiser Pister
 Author-email: kaiser@pister.dev
 Requires-Python: >=3.9,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Requires-Dist: openai (>=0.27.7,<0.28.0)
+Requires-Dist: openai (>=0.27.8,<0.28.0)
 Requires-Dist: tiktoken (>=0.4.0,<0.5.0)
 Description-Content-Type: text/markdown
 
 # Simple Large Language Inference Model
 
 `sllim` serves as a quality of life wrapper around the `openai-python` library.
 I found myself writing and rewriting the same helper functions with each new project I began, so now I am working to put these functions together into a easy to use library.
```

