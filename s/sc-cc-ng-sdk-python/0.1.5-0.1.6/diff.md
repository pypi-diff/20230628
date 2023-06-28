# Comparing `tmp/sc_cc_ng_sdk_python-0.1.5.tar.gz` & `tmp/sc_cc_ng_sdk_python-0.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sc_cc_ng_sdk_python-0.1.5.tar", max compression
+gzip compressed data, was "sc_cc_ng_sdk_python-0.1.6.tar", max compression
```

## Comparing `sc_cc_ng_sdk_python-0.1.5.tar` & `sc_cc_ng_sdk_python-0.1.6.tar`

### file list

```diff
@@ -1,4 +1,4 @@
--rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.5/README.md
--rw-r--r--   0        0        0      530 2023-06-28 08:39:39.580673 sc_cc_ng_sdk_python-0.1.5/pyproject.toml
--rw-r--r--   0        0        0    14839 2023-06-28 08:39:23.299157 sc_cc_ng_sdk_python-0.1.5/sc_cc_ng_sdk_python/__init__.py
--rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.5/PKG-INFO
+-rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.6/README.md
+-rw-r--r--   0        0        0      530 2023-06-28 09:03:32.529617 sc_cc_ng_sdk_python-0.1.6/pyproject.toml
+-rw-r--r--   0        0        0    14858 2023-06-28 09:05:34.360540 sc_cc_ng_sdk_python-0.1.6/sc_cc_ng_sdk_python/__init__.py
+-rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.6/PKG-INFO
```

### Comparing `sc_cc_ng_sdk_python-0.1.5/pyproject.toml` & `sc_cc_ng_sdk_python-0.1.6/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "sc-cc-ng-sdk-python"
-version = "0.1.5"
+version = "0.1.6"
 description = ""
 authors = ["Rikard Olsson <rikard@thryselius.se>"]
 readme = "README.md"
 packages = [{include = "sc_cc_ng_sdk_python"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
```

### Comparing `sc_cc_ng_sdk_python-0.1.5/sc_cc_ng_sdk_python/__init__.py` & `sc_cc_ng_sdk_python-0.1.6/sc_cc_ng_sdk_python/__init__.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import asyncio
 import aiohttp
 
-from dataclasses import dataclass, asdict
+from dataclasses import dataclass, field
 from requests import post
 from sc_cc_ng_models_python import ContextFilter, BitVal
 from typing import List, Optional, Any
 from enum import Enum
 from itertools import chain
 from more_itertools import batched
 from functools import reduce
@@ -210,53 +210,56 @@
                     )
                 )
             else:
                 return internal_result
         except Exception as e:
             return Result(error=str(e))
 
+
+@dataclass
+class ResultAsync:
+
+    """
+        A result object, containing data if everything was ok else an error.
+    """
+
+    data:   List[Optional[str]]   = field(default_factory=lambda: [])
+    error:  List[Optional[str]]   = field(default_factory=lambda: [])
+
 @dataclass
 class SCNGAsync:
 
     url: str
 
     @staticmethod
-    def _compile_batched_result(results: List[Result]) -> Result:
+    def _compile_batched_result(results: List[Result]) -> ResultAsync:
 
         """"""
 
-        return Result(
+        return ResultAsync(
             data=list(
                 chain(
                     *map(
                         lambda x: x.data, 
-                        filter(
-                            lambda x: x.error is None, 
-                            results
-                        )
+                        results
                     )
                 )
             ),
-            error=", ".join(
-                map(
-                    lambda x: x.error,
-                    filter(
-                        lambda x: x.error is not None,
+            error=list(
+                filter(
+                    lambda x: x is not None,
+                    map(
+                        lambda x: x.error, 
                         results
                     )
                 )
-            ) if any(
-                map(
-                    lambda x: x.error is not None,
-                    results
-                )
-            ) else None
+            ),
         )
 
-    async def _fetch_batch(self, session, data, query_fn, response_keys: list, context_filter: Optional[ContextFilter] = None) -> Result:
+    async def _fetch_batch(self, session, data, query_fn, response_keys: list, context_filter: Optional[ContextFilter] = None) -> ResultAsync:
 
         """
             Fetch single batch of data from the server.
         """
 
         try:
             async with session.post(
@@ -273,15 +276,15 @@
                         response_keys, 
                         result
                     )
                 )
         except Exception as e:
             return Result(error=str(e))
   
-    async def to_dict_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> Result:
+    async def to_dict_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> ResultAsync:
 
         """
             Converts lists of tokens to a list of dicts, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
@@ -314,15 +317,15 @@
                         )
                     )
                 )
             return result
         except Exception as e:
             return Result(error=str(e))
     
-    async def to_bit_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> Result:
+    async def to_bit_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> ResultAsync:
 
         """
             Converts lists of tokens to a list of bits, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
@@ -372,15 +375,15 @@
                     )
                 ),
                 error=result.error,
             )
         except Exception as e:
             return Result(error=str(e))
 
-    async def to_string_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> Result:
+    async def to_string_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> ResultAsync:
 
         """
             Converts lists of tokens to a list of strings, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
```

