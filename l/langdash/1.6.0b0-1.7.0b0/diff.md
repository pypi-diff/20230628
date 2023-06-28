# Comparing `tmp/langdash-1.6.0b0.tar.gz` & `tmp/langdash-1.7.0b0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "langdash-1.6.0b0.tar", last modified: Tue Jun 27 20:26:38 2023, max compression
+gzip compressed data, was "langdash-1.7.0b0.tar", last modified: Wed Jun 28 08:04:36 2023, max compression
```

## Comparing `langdash-1.6.0b0.tar` & `langdash-1.7.0b0.tar`

### file list

```diff
@@ -1,52 +1,52 @@
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/
--rw-r--r--   0 user      (1000) user      (1000)    10786 2023-06-06 08:29:05.000000 langdash-1.6.0b0/LICENSE.txt
--rw-r--r--   0 user      (1000) user      (1000)       35 2023-06-06 08:29:05.000000 langdash-1.6.0b0/MANIFEST.in
--rw-r--r--   0 user      (1000) user      (1000)     3726 2023-06-27 20:26:38.106726 langdash-1.6.0b0/PKG-INFO
--rw-r--r--   0 user      (1000) user      (1000)     2788 2023-06-22 20:30:22.000000 langdash-1.6.0b0/README.md
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.103393 langdash-1.6.0b0/langdash/
--rw-r--r--   0 user      (1000) user      (1000)       78 2023-06-27 20:25:25.000000 langdash-1.6.0b0/langdash/__init__.py
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/langdash/chains/
--rw-r--r--   0 user      (1000) user      (1000)      177 2023-06-27 19:02:29.000000 langdash-1.6.0b0/langdash/chains/__init__.py
--rw-r--r--   0 user      (1000) user      (1000)    14993 2023-06-27 20:04:56.000000 langdash-1.6.0b0/langdash/chains/chains.py
--rw-r--r--   0 user      (1000) user      (1000)     9520 2023-06-22 20:30:16.000000 langdash-1.6.0b0/langdash/chains/nodes.py
--rw-r--r--   0 user      (1000) user      (1000)      253 2023-06-11 01:18:11.000000 langdash-1.6.0b0/langdash/chains/typing.py
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/langdash/classify/
--rw-r--r--   0 user      (1000) user      (1000)        0 2023-06-06 08:44:18.000000 langdash-1.6.0b0/langdash/classify/__init__.py
--rw-r--r--   0 user      (1000) user      (1000)     2032 2023-06-12 17:25:45.000000 langdash-1.6.0b0/langdash/classify/token_qa.py
--rw-r--r--   0 user      (1000) user      (1000)     6625 2023-06-22 20:30:16.000000 langdash-1.6.0b0/langdash/core.py
--rw-r--r--   0 user      (1000) user      (1000)     1321 2023-06-22 20:30:16.000000 langdash-1.6.0b0/langdash/infer.py
--rw-r--r--   0 user      (1000) user      (1000)     1555 2023-06-07 00:55:46.000000 langdash-1.6.0b0/langdash/llm.py
--rw-r--r--   0 user      (1000) user      (1000)     8853 2023-06-27 19:06:16.000000 langdash-1.6.0b0/langdash/llm_session.py
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/langdash/models/
--rw-r--r--   0 user      (1000) user      (1000)        0 2023-06-13 06:46:41.000000 langdash-1.6.0b0/langdash/models/__init__.py
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/langdash/models/_mixins/
--rw-r--r--   0 user      (1000) user      (1000)        0 2023-06-13 06:51:30.000000 langdash-1.6.0b0/langdash/models/_mixins/__init__.py
--rw-r--r--   0 user      (1000) user      (1000)     3412 2023-06-22 20:30:16.000000 langdash-1.6.0b0/langdash/models/_mixins/tensor_based_infer_mixin.py
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/langdash/models/_tokenizer/
--rw-r--r--   0 user      (1000) user      (1000)        0 2023-06-13 06:51:39.000000 langdash-1.6.0b0/langdash/models/_tokenizer/__init__.py
--rw-r--r--   0 user      (1000) user      (1000)     1886 2023-06-13 06:51:21.000000 langdash-1.6.0b0/langdash/models/_tokenizer/_bpe.py
--rw-r--r--   0 user      (1000) user      (1000)     1532 2023-06-13 06:51:21.000000 langdash-1.6.0b0/langdash/models/_tokenizer/bytes_dict_tokenizer.py
--rw-r--r--   0 user      (1000) user      (1000)     2269 2023-06-22 20:30:16.000000 langdash-1.6.0b0/langdash/models/_tokenizer/hf_tokenizer.py
--rw-r--r--   0 user      (1000) user      (1000)     1546 2023-06-22 20:30:16.000000 langdash-1.6.0b0/langdash/models/_tokenizer/rwkv_tokenizer.py
--rw-r--r--   0 user      (1000) user      (1000)      664 2023-06-13 06:51:21.000000 langdash-1.6.0b0/langdash/models/_tokenizer/tokenizer.py
--rw-r--r--   0 user      (1000) user      (1000)     5280 2023-06-27 19:02:29.000000 langdash-1.6.0b0/langdash/models/ctransformers.py
--rw-r--r--   0 user      (1000) user      (1000)     4932 2023-06-27 19:02:29.000000 langdash-1.6.0b0/langdash/models/llama_cpp.py
--rw-r--r--   0 user      (1000) user      (1000)      689 2023-06-13 06:46:41.000000 langdash-1.6.0b0/langdash/models/mock.py
--rw-r--r--   0 user      (1000) user      (1000)     8993 2023-06-27 19:05:22.000000 langdash-1.6.0b0/langdash/models/rwkv_cpp.py
--rw-r--r--   0 user      (1000) user      (1000)     1005 2023-06-13 06:46:41.000000 langdash-1.6.0b0/langdash/models/sentence_transformers.py
--rw-r--r--   0 user      (1000) user      (1000)     5632 2023-06-27 19:02:29.000000 langdash-1.6.0b0/langdash/models/transformers.py
--rw-r--r--   0 user      (1000) user      (1000)      837 2023-06-07 00:55:46.000000 langdash-1.6.0b0/langdash/response.py
--rw-r--r--   0 user      (1000) user      (1000)     3450 2023-06-14 22:38:13.000000 langdash-1.6.0b0/langdash/sampling.py
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/langdash/search/
--rw-r--r--   0 user      (1000) user      (1000)        0 2023-06-06 08:44:18.000000 langdash-1.6.0b0/langdash/search/__init__.py
--rw-r--r--   0 user      (1000) user      (1000)     1135 2023-06-12 17:46:13.000000 langdash-1.6.0b0/langdash/search/embedding_search.py
--rw-r--r--   0 user      (1000) user      (1000)     1118 2023-06-09 17:53:33.000000 langdash-1.6.0b0/langdash/search/engine.py
--rw-r--r--   0 user      (1000) user      (1000)     2861 2023-06-22 20:30:16.000000 langdash-1.6.0b0/langdash/search/multichoice_search.py
-drwxr-xr-x   0 user      (1000) user      (1000)        0 2023-06-27 20:26:38.106726 langdash-1.6.0b0/langdash.egg-info/
--rw-r--r--   0 user      (1000) user      (1000)     3726 2023-06-27 20:26:38.000000 langdash-1.6.0b0/langdash.egg-info/PKG-INFO
--rw-r--r--   0 user      (1000) user      (1000)     1188 2023-06-27 20:26:38.000000 langdash-1.6.0b0/langdash.egg-info/SOURCES.txt
--rw-r--r--   0 user      (1000) user      (1000)        1 2023-06-27 20:26:38.000000 langdash-1.6.0b0/langdash.egg-info/dependency_links.txt
--rw-r--r--   0 user      (1000) user      (1000)      199 2023-06-27 20:26:38.000000 langdash-1.6.0b0/langdash.egg-info/requires.txt
--rw-r--r--   0 user      (1000) user      (1000)        9 2023-06-27 20:26:38.000000 langdash-1.6.0b0/langdash.egg-info/top_level.txt
--rw-r--r--   0 user      (1000) user      (1000)       38 2023-06-27 20:26:38.106726 langdash-1.6.0b0/setup.cfg
--rw-r--r--   0 user      (1000) user      (1000)     1604 2023-06-22 20:30:45.000000 langdash-1.6.0b0/setup.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.072261 langdash-1.7.0b0/
+-rw-rw-r--   0 user      (1000) user      (1000)    10786 2023-05-30 02:56:17.000000 langdash-1.7.0b0/LICENSE.txt
+-rw-rw-r--   0 user      (1000) user      (1000)       35 2023-05-31 17:16:19.000000 langdash-1.7.0b0/MANIFEST.in
+-rw-rw-r--   0 user      (1000) user      (1000)     3726 2023-06-28 08:04:36.068261 langdash-1.7.0b0/PKG-INFO
+-rw-rw-r--   0 user      (1000) user      (1000)     2788 2023-06-23 20:18:20.000000 langdash-1.7.0b0/README.md
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.064261 langdash-1.7.0b0/langdash/
+-rw-rw-r--   0 user      (1000) user      (1000)       78 2023-06-28 08:01:09.000000 langdash-1.7.0b0/langdash/__init__.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.068261 langdash-1.7.0b0/langdash/chains/
+-rw-rw-r--   0 user      (1000) user      (1000)      177 2023-06-27 17:54:15.000000 langdash-1.7.0b0/langdash/chains/__init__.py
+-rw-rw-r--   0 user      (1000) user      (1000)    14903 2023-06-28 07:18:05.000000 langdash-1.7.0b0/langdash/chains/chains.py
+-rw-rw-r--   0 user      (1000) user      (1000)     9394 2023-06-28 07:12:18.000000 langdash-1.7.0b0/langdash/chains/nodes.py
+-rw-rw-r--   0 user      (1000) user      (1000)      253 2023-06-11 03:43:22.000000 langdash-1.7.0b0/langdash/chains/typing.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.064261 langdash-1.7.0b0/langdash/classify/
+-rw-rw-r--   0 user      (1000) user      (1000)        0 2023-05-30 02:28:31.000000 langdash-1.7.0b0/langdash/classify/__init__.py
+-rw-rw-r--   0 user      (1000) user      (1000)     2032 2023-06-12 18:40:51.000000 langdash-1.7.0b0/langdash/classify/token_qa.py
+-rw-rw-r--   0 user      (1000) user      (1000)     6738 2023-06-28 07:20:44.000000 langdash-1.7.0b0/langdash/core.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1341 2023-06-28 07:36:19.000000 langdash-1.7.0b0/langdash/infer.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1661 2023-06-28 07:07:44.000000 langdash-1.7.0b0/langdash/llm.py
+-rw-rw-r--   0 user      (1000) user      (1000)     9137 2023-06-28 07:27:22.000000 langdash-1.7.0b0/langdash/llm_session.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.068261 langdash-1.7.0b0/langdash/models/
+-rw-rw-r--   0 user      (1000) user      (1000)        0 2023-06-04 22:40:10.000000 langdash-1.7.0b0/langdash/models/__init__.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.068261 langdash-1.7.0b0/langdash/models/_mixins/
+-rw-rw-r--   0 user      (1000) user      (1000)        0 2023-06-13 06:53:56.000000 langdash-1.7.0b0/langdash/models/_mixins/__init__.py
+-rw-rw-r--   0 user      (1000) user      (1000)     3412 2023-06-21 10:26:00.000000 langdash-1.7.0b0/langdash/models/_mixins/tensor_based_infer_mixin.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.068261 langdash-1.7.0b0/langdash/models/_tokenizer/
+-rw-rw-r--   0 user      (1000) user      (1000)        0 2023-06-13 06:53:56.000000 langdash-1.7.0b0/langdash/models/_tokenizer/__init__.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1886 2023-06-12 18:40:51.000000 langdash-1.7.0b0/langdash/models/_tokenizer/_bpe.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1532 2023-06-13 05:07:37.000000 langdash-1.7.0b0/langdash/models/_tokenizer/bytes_dict_tokenizer.py
+-rw-rw-r--   0 user      (1000) user      (1000)     2269 2023-06-21 10:26:00.000000 langdash-1.7.0b0/langdash/models/_tokenizer/hf_tokenizer.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1546 2023-06-22 00:31:04.000000 langdash-1.7.0b0/langdash/models/_tokenizer/rwkv_tokenizer.py
+-rw-rw-r--   0 user      (1000) user      (1000)      664 2023-06-13 05:07:37.000000 langdash-1.7.0b0/langdash/models/_tokenizer/tokenizer.py
+-rw-rw-r--   0 user      (1000) user      (1000)     5280 2023-06-27 18:43:45.000000 langdash-1.7.0b0/langdash/models/ctransformers.py
+-rw-rw-r--   0 user      (1000) user      (1000)     4932 2023-06-27 18:24:11.000000 langdash-1.7.0b0/langdash/models/llama_cpp.py
+-rw-rw-r--   0 user      (1000) user      (1000)      689 2023-06-06 03:06:05.000000 langdash-1.7.0b0/langdash/models/mock.py
+-rw-rw-r--   0 user      (1000) user      (1000)     8993 2023-06-27 20:26:11.000000 langdash-1.7.0b0/langdash/models/rwkv_cpp.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1005 2023-06-12 18:40:51.000000 langdash-1.7.0b0/langdash/models/sentence_transformers.py
+-rw-rw-r--   0 user      (1000) user      (1000)     5632 2023-06-27 18:22:06.000000 langdash-1.7.0b0/langdash/models/transformers.py
+-rw-rw-r--   0 user      (1000) user      (1000)      837 2023-06-06 03:06:05.000000 langdash-1.7.0b0/langdash/response.py
+-rw-rw-r--   0 user      (1000) user      (1000)     3450 2023-06-14 22:44:24.000000 langdash-1.7.0b0/langdash/sampling.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.064261 langdash-1.7.0b0/langdash/search/
+-rw-rw-r--   0 user      (1000) user      (1000)        0 2023-05-30 02:28:40.000000 langdash-1.7.0b0/langdash/search/__init__.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1135 2023-06-12 18:40:51.000000 langdash-1.7.0b0/langdash/search/embedding_search.py
+-rw-rw-r--   0 user      (1000) user      (1000)     1118 2023-06-09 18:58:51.000000 langdash-1.7.0b0/langdash/search/engine.py
+-rw-rw-r--   0 user      (1000) user      (1000)     2861 2023-06-19 07:37:15.000000 langdash-1.7.0b0/langdash/search/multichoice_search.py
+drwxrwxr-x   0 user      (1000) user      (1000)        0 2023-06-28 08:04:36.064261 langdash-1.7.0b0/langdash.egg-info/
+-rw-rw-r--   0 user      (1000) user      (1000)     3726 2023-06-28 08:04:36.000000 langdash-1.7.0b0/langdash.egg-info/PKG-INFO
+-rw-rw-r--   0 user      (1000) user      (1000)     1654 2023-06-28 08:04:36.000000 langdash-1.7.0b0/langdash.egg-info/SOURCES.txt
+-rw-rw-r--   0 user      (1000) user      (1000)        1 2023-06-28 08:04:36.000000 langdash-1.7.0b0/langdash.egg-info/dependency_links.txt
+-rw-rw-r--   0 user      (1000) user      (1000)      199 2023-06-28 08:04:36.000000 langdash-1.7.0b0/langdash.egg-info/requires.txt
+-rw-rw-r--   0 user      (1000) user      (1000)        9 2023-06-28 08:04:36.000000 langdash-1.7.0b0/langdash.egg-info/top_level.txt
+-rw-rw-r--   0 user      (1000) user      (1000)       38 2023-06-28 08:04:36.072261 langdash-1.7.0b0/setup.cfg
+-rw-rw-r--   0 user      (1000) user      (1000)     1604 2023-06-23 20:18:20.000000 langdash-1.7.0b0/setup.py
```

### Comparing `langdash-1.6.0b0/LICENSE.txt` & `langdash-1.7.0b0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/PKG-INFO` & `langdash-1.7.0b0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: langdash
-Version: 1.6.0b0
+Version: 1.7.0b0
 Summary: A simple library for interfacing with language models.
 Home-page: https://git.mysymphony.jp.net/nana/langdash
 Author: Nana Mochizuki
 Author-email: nana@mysymphony.jp.net
 Project-URL: Source, https://git.mysymphony.jp.net/nana/langdash
 Project-URL: Documentation, https://langdash.readthedocs.io/en/latest/
 Classifier: Development Status :: 4 - Beta
```

### Comparing `langdash-1.6.0b0/README.md` & `langdash-1.7.0b0/README.md`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/chains/chains.py` & `langdash-1.7.0b0/langdash/chains/chains.py`

 * *Files 1% similar despite different names*

```diff
@@ -167,23 +167,25 @@
     Stream data generated from the LLM within the specified session.
     
     Args:
       session (Union[str, "LLMGenerationSession"]):
         The name of the model, or an existing LLM generation session.
       args (LDNodeArgs):
         Arguments to pass to the chain. This will be used by any argument or format nodes.
+    
+    Returns:
+      (Generator[Response, None, None]): Generator yielding response events.
     """
     return self._stream(session=self._load_session(ctx), **kwargs)
 
   def _call(
     self,
     session: "LLMGenerationSession",
     args: LDNodeArgs = {},
     return_session: bool = False,
-    set_global_args: bool = False,
   ) -> Union["LDResult", Tuple["LDResult", "LLMGenerationSession"]]:
     result = LDResult()
 
     for node in self._node_pass(session, args):
       generator = node(session, args)
 
       if isinstance(node, LDReturns):
@@ -217,32 +219,28 @@
         for resp in generator:
           if isinstance(resp, RespInject):
             result.prompt_tokens += resp.tokens_counter
           else:
             raise NotImplementedError(resp.__class__.__name__)
 
     if return_session:
-      if set_global_args:
-        session.global_args = args
       return result, session
     return result
 
   def call(self, ctx: Union[str, "LLMGenerationSession"], **kwargs):
     """
     Returns data generated from the LLM within the specified session.
     
     Args:
       ctx (Union[str, "LLMGenerationSession"]):
         The name of the model, or an existing LLM generation session.
       args (LDNodeArgs):
         Arguments to pass to the chain. This will be used by any argument or format nodes.
       return_session (bool):
         Whether or not to return the generation session after generation.
-      set_global_args (bool):
-        Whether or not to set current arguments as global arguments.
     
     Returns:
       (LDResult) The result, or a tuple with (result, session).
     """
     return self._call(session=self._load_session(ctx), **kwargs)
 
 
@@ -307,15 +305,17 @@
     self._skip_nodes = 0
 
   # State cache functions
 
   def load_cache_store(self, cache_store: LDChainCacheStore):
     """
     Loads the cache store from previous inference time.
+    
     Raises `ValueError` if the model names mismatch.
+    
     This function expects that the model data of the parent Langdash instance does not change across session. If it does, a `UserWarning` is raised.
     
     Args:
       cache_store (LDChainCacheStore): The cache store.
     """
     if self._model != cache_store._model:
       raise ValueError("model mismatch for LDChainCacheStore")
```

### Comparing `langdash-1.6.0b0/langdash/chains/nodes.py` & `langdash-1.7.0b0/langdash/chains/nodes.py`

 * *Files 1% similar despite different names*

```diff
@@ -56,17 +56,15 @@
 
   def __repr__(self):
     return f"<FormatArgs>\n{self._text}\n</FormatArgs>"
 
   def __call__(
     self, session: "LLMGenerationSession", args: "LDNodeArgs"
   ) -> "LDNodeGenerator":
-    tokens_counter = session.inject(
-      self._text.format(globals=session.global_args, **args)
-    )
+    tokens_counter = session.inject(self._text.format(**args))
     yield RespInject(tokens_counter=tokens_counter)
 
 
 class LDArg(LDNode):
   """ Argument node """
 
   def __init__(
@@ -81,18 +79,15 @@
     return f"<Arg arg={self._arg}>"
 
   def __call__(
     self, session: "LLMGenerationSession", args: "LDNodeArgs"
   ) -> "LDNodeGenerator":
     s = ""
     s += self._padleft
-    if self._arg in args:
-      s += str(args[self._arg])
-    else:
-      s += str(session.global_args[self._arg])
+    s += str(args[self._arg])
     s += self._padright
     tokens_counter = session.inject(s)
     yield RespInject(tokens_counter=tokens_counter)
 
 
 class LDReturns(LDNode):
   """ Return node """
```

### Comparing `langdash-1.6.0b0/langdash/classify/token_qa.py` & `langdash-1.7.0b0/langdash/classify/token_qa.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/core.py` & `langdash-1.7.0b0/langdash/core.py`

 * *Files 7% similar despite different names*

```diff
@@ -74,18 +74,22 @@
 
   def session_for_model(self, model: str, **kwargs) -> LLMSession:
     """
     Create a new session for a given model.
     
     Args:
       model (str): The name of the model to be used.
-      default_infer_args (InferArgs): Default inference arguments.
-      track_called_chains (bool): Whether or not to track the nodes called in each chain. Defaults to `True`.
-      token_healing (bool): Whether or not to heal tokens.
-      global_args (LDNodeArgs): Global arguments which can be read by every chain.
+      default_infer_args (InferArgs):
+        Default arguments for the inference.
+      track_called_nodes (bool):
+        Whether to track called nodes. Defaults to `False`.
+      token_healing (bool):
+        Whether to enable token healing. Defaults to `True`.
+      event_handlers (Optional[LLMGenerationSessionEvents]):
+        Event handlers for prompt events. Defaults to `None`.
     
     Returns:
       (LLMSession) The session object.
     """
     return self._models[model].session(ld=self, **kwargs)
 
   def chain(self, *args, **kwargs) -> chains.LDChain:
@@ -109,15 +113,15 @@
     """
     Creates a raw text node.
     
     Args:
       text (str): The raw text.
       add_special_tokens (bool):
         Whether to treat text as containing special tokens or not.
-        Optional. Defaults to False.
+        Defaults to `False`.
       
     Returns:
       The text node.
     """
     return chains.LDText(self, *args, **kwargs)
 
   def format_args(self, *args, **kwargs):
@@ -174,17 +178,17 @@
     
     Args:
       returns (str): The name of the return value.
       choices (Union[str, List[str]]):
         Either the list of choice strings or the name of the argument
         containing the list.
       padleft (str):
-        Left padding for every choice string.
+        Left padding for every choice string. Defaults to empty string.
       padright (str):
-        Right padding for every choice string.
+        Right padding for every choice string. Defaults to empty string.
     
     Returns:
       The choice node.
     """
     return chains.LDChoice(self, *args, **kwargs)
 
   def repeat(self, *args, **kwargs):
```

### Comparing `langdash-1.6.0b0/langdash/infer.py` & `langdash-1.7.0b0/langdash/infer.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,36 +1,44 @@
 from dataclasses import dataclass
 
 
 @dataclass
 class InferArgs:
+  """ Data class for inference arguments. """
+
+  min_new_tokens: int = 0
   """
-  Data class for inference arguments.
+  Minimum number of new tokens to generate.
   
-  Attributes:
-    min_new_tokens:
-      Minimum number of new tokens to generate.
-      If this is set, the `end` argument passed to the session's infer method
-       will be interpreted as *a single token*. Special tokens count as an end token.
-    max_new_tokens: Maximum number of new tokens to generate
-    temperature: Temperature
-    top_k: Top-K parameter. If set, generation defaults to top-K. Works with top_p
-    top_p: Top-P parameter
-    typical_mass: Mass parameter. If set, generation will use typical sampling
-    max_rep_ctx: Maximum number of tokens to look back for repetition penalty
-    rep_penalty: Repetition penalty, applied to logits for every repeated token
+  If this is set, the `end` argument passed to the session's infer method
+   will be interpreted as *a single token*. Special tokens count as an end token.
   """
-  min_new_tokens: int = 0
+
   max_new_tokens: int = 512
+  """
+  Maximum number of new tokens to generate
+  """
+
   temperature: float = 1.0
+  """ Temperature """
+
   top_k: int = 0
+  """ Top-K parameter. If set, generation uses top-K sampling method. Works with `top_p`. """
+
   top_p: float = 0.
+  """ Top-P parameter. If set, generation uses top-P sampling method. """
+
   typical_mass: float = 0.
+  """ Typical mass parameter. If set, generation will use typical sampling. """
+
   max_rep_ctx: int = 64
+  """ Maximum number of tokens to look back for repetition penalty. """
+
   rep_penalty: float = 1.0
+  """ Repetition penalty, applied to logits for every repeated token before sampling. """
 
   def __post_init__(self):
     assert self.min_new_tokens >= 0
     assert self.max_new_tokens >= 0
     assert 0.0 <= self.temperature <= 10.0
     assert 0 <= self.top_k
     assert 0.0 <= self.top_p <= 1.0
```

### Comparing `langdash-1.6.0b0/langdash/llm_session.py` & `langdash-1.7.0b0/langdash/llm_session.py`

 * *Files 8% similar despite different names*

```diff
@@ -50,48 +50,48 @@
     Args:
       node (LDNode): The node being added
       args (LDNodeArgs): The arguments of the node
       tokens_used (int): Number of tokens the node used
       session (LLMGenerationSession): The current session
     
     Returns:
-      None or True if node should be appended, otherwise False if node should not be appended.
+      `None` or `True` if node should be appended, otherwise `False` if node should not be appended.
     """
     return None
 
 
 class LLMGenerationSession(LLMSession, Generic[T_LLM, T_LLMState]):
   """ Generation session for a language model. """
 
   default_infer_args: InferArgs
   """ Default inference arguments. """
+
   called_nodes: Optional[List[CalledNode]]
   """
   List of called nodes.
-  If track_called_nodes is set to False in constructor, then this will be None.
+  
+  If `track_called_nodes` is set to `False` in constructor, then this will be `None`.
   """
 
   # Event handlers
   event_handlers: Optional[LLMGenerationSessionEvents]
 
   def __init__(
     self,
     llm: T_LLM,
     ld: "Langdash",
     default_infer_args: InferArgs = InferArgs(),
     track_called_nodes: bool = False,
     token_healing: bool = True,
-    global_args: LDNodeArgs = {},
     event_handlers: Optional[LLMGenerationSessionEvents] = None,
   ):
     super().__init__(llm, ld)
     self.default_infer_args = default_infer_args
     self.called_nodes = ([] if track_called_nodes else None)
     self.token_healing = token_healing
-    self.global_args = global_args
     self._tokens_counter = 0
     self.tokens_used = 0
     self.event_handlers = event_handlers
 
   def set_state(self, state: Optional[T_LLMState]):
     """
     Set the state of the language model.
@@ -101,25 +101,34 @@
         The state of the language model, or None to clear the state.
     """
     raise NotImplementedError("set_state")
 
   def clone_state(self) -> T_LLMState:
     """
     Clone the current state of the language model.
+    
+    Returns:
+      (T_LLMState) The current state as an object.
     """
     raise NotImplementedError("clone_state")
 
   def clone(self) -> "LLMGenerationSession":
+    """
+    Clone the current session.
+    
+    Returns:
+      (LLMGenerationSession) A new generation session with the same arguments.
+    """
     session = self.__class__(
       llm=self._llm,
       ld=self._ld,
       default_infer_args=self.default_infer_args,
       track_called_nodes=False,
       token_healing=self.token_healing,
-      global_args=copy.copy(self.global_args)
+      event_handlers=self.event_handlers,
     )
     session.set_state(self.clone_state())
     if self.called_nodes is not None:
       session.called_nodes = copy.copy(self.called_nodes)
     return session
 
   def _append_called_chain(
@@ -180,23 +189,24 @@
   ) -> Generator[RespInfer, None, None]:
     """
     Infer the next tokens from the input sequence.
 
     Args:
       end (Optional[Union[str, int]]):
         The end of the output sequence.
-        If set to None, the output sequence will be generated until the maximum number of tokens is reached.
+        If set to `None`, the output sequence will be generated until the maximum number of tokens is reached.
+        
+        Defaults to `None`.
       args (Optional[InferArgs]):
-        Optional inference parameters.
+        Optional inference parameters. Defaults to `None`.
       end_is_token (bool):
-        If set, the end string will be interpreted as a token.
-        Defaults to False.
+        If true, then the end string will be interpreted as a token. Defaults to `False`.
         
     Returns:
-      Inference response
+      (Generator[RespInfer, None, None]) Generator yielding inference events.
     """
     if not args:
       args = self.default_infer_args
     yield from self._infer(end=end, args=args, end_is_token=end_is_token)
 
   def inject(
     self,
@@ -237,16 +247,16 @@
       logits = self._eval(tokid)
     return logits
 
   def flush_token(self):
     """
     Flushes the previous token into the language model if healing is enabled.
     
-    **Warning:** unexpected behavior if the previous token is a "boundary" token
-    like spaces.
+    **Warning:** unexpected behavior if the previous token is a "boundary" token,
+    like the space `' '` token.
     """
     if self._next_token is None:
       return
     self.inject(self._next_token[0])
     self._next_token = None
 
   def next_token_probs(self, *args, **kwargs) -> List[float]:
```

### Comparing `langdash-1.6.0b0/langdash/models/_mixins/tensor_based_infer_mixin.py` & `langdash-1.7.0b0/langdash/models/_mixins/tensor_based_infer_mixin.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/_tokenizer/_bpe.py` & `langdash-1.7.0b0/langdash/models/_tokenizer/_bpe.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/_tokenizer/bytes_dict_tokenizer.py` & `langdash-1.7.0b0/langdash/models/_tokenizer/bytes_dict_tokenizer.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/_tokenizer/hf_tokenizer.py` & `langdash-1.7.0b0/langdash/models/_tokenizer/hf_tokenizer.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/_tokenizer/rwkv_tokenizer.py` & `langdash-1.7.0b0/langdash/models/_tokenizer/rwkv_tokenizer.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/_tokenizer/tokenizer.py` & `langdash-1.7.0b0/langdash/models/_tokenizer/tokenizer.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/ctransformers.py` & `langdash-1.7.0b0/langdash/models/ctransformers.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/llama_cpp.py` & `langdash-1.7.0b0/langdash/models/llama_cpp.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/mock.py` & `langdash-1.7.0b0/langdash/models/mock.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/rwkv_cpp.py` & `langdash-1.7.0b0/langdash/models/rwkv_cpp.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/sentence_transformers.py` & `langdash-1.7.0b0/langdash/models/sentence_transformers.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/models/transformers.py` & `langdash-1.7.0b0/langdash/models/transformers.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/response.py` & `langdash-1.7.0b0/langdash/response.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/sampling.py` & `langdash-1.7.0b0/langdash/sampling.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/search/embedding_search.py` & `langdash-1.7.0b0/langdash/search/embedding_search.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/search/engine.py` & `langdash-1.7.0b0/langdash/search/engine.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash/search/multichoice_search.py` & `langdash-1.7.0b0/langdash/search/multichoice_search.py`

 * *Files identical despite different names*

### Comparing `langdash-1.6.0b0/langdash.egg-info/PKG-INFO` & `langdash-1.7.0b0/langdash.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: langdash
-Version: 1.6.0b0
+Version: 1.7.0b0
 Summary: A simple library for interfacing with language models.
 Home-page: https://git.mysymphony.jp.net/nana/langdash
 Author: Nana Mochizuki
 Author-email: nana@mysymphony.jp.net
 Project-URL: Source, https://git.mysymphony.jp.net/nana/langdash
 Project-URL: Documentation, https://langdash.readthedocs.io/en/latest/
 Classifier: Development Status :: 4 - Beta
```

### Comparing `langdash-1.6.0b0/setup.py` & `langdash-1.7.0b0/setup.py`

 * *Files identical despite different names*

