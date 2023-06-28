# Comparing `tmp/sc_cc_ng_sdk_python-0.1.4.tar.gz` & `tmp/sc_cc_ng_sdk_python-0.1.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sc_cc_ng_sdk_python-0.1.4.tar", max compression
+gzip compressed data, was "sc_cc_ng_sdk_python-0.1.5.tar", max compression
```

## Comparing `sc_cc_ng_sdk_python-0.1.4.tar` & `sc_cc_ng_sdk_python-0.1.5.tar`

### file list

```diff
@@ -1,4 +1,4 @@
--rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.4/README.md
--rw-r--r--   0        0        0      530 2023-06-28 08:00:59.350471 sc_cc_ng_sdk_python-0.1.4/pyproject.toml
--rw-r--r--   0        0        0    14892 2023-06-28 07:59:21.537546 sc_cc_ng_sdk_python-0.1.4/sc_cc_ng_sdk_python/__init__.py
--rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.4/PKG-INFO
+-rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.5/README.md
+-rw-r--r--   0        0        0      530 2023-06-28 08:39:39.580673 sc_cc_ng_sdk_python-0.1.5/pyproject.toml
+-rw-r--r--   0        0        0    14839 2023-06-28 08:39:23.299157 sc_cc_ng_sdk_python-0.1.5/sc_cc_ng_sdk_python/__init__.py
+-rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.5/PKG-INFO
```

### Comparing `sc_cc_ng_sdk_python-0.1.4/pyproject.toml` & `sc_cc_ng_sdk_python-0.1.5/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "sc-cc-ng-sdk-python"
-version = "0.1.4"
+version = "0.1.5"
 description = ""
 authors = ["Rikard Olsson <rikard@thryselius.se>"]
 readme = "README.md"
 packages = [{include = "sc_cc_ng_sdk_python"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
```

### Comparing `sc_cc_ng_sdk_python-0.1.4/sc_cc_ng_sdk_python/__init__.py` & `sc_cc_ng_sdk_python-0.1.5/sc_cc_ng_sdk_python/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -214,15 +214,14 @@
         except Exception as e:
             return Result(error=str(e))
 
 @dataclass
 class SCNGAsync:
 
     url: str
-    _batch_size: int = 10
 
     @staticmethod
     def _compile_batched_result(results: List[Result]) -> Result:
 
         """"""
 
         return Result(
@@ -273,17 +272,16 @@
                         lambda x,y: x.get(y), 
                         response_keys, 
                         result
                     )
                 )
         except Exception as e:
             return Result(error=str(e))
-
-    
-    async def to_dict_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batching: str = 'auto') -> Result:
+  
+    async def to_dict_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> Result:
 
         """
             Converts lists of tokens to a list of dicts, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
@@ -307,24 +305,24 @@
                                         'tokensListBasedContentAsDict',
                                     ],
                                     context_filter,
                                 )
                             ),
                             batched(
                                 tokens_list,
-                                self._batch_size,
+                                batch_size,
                             )
                         )
                     )
                 )
             return result
         except Exception as e:
             return Result(error=str(e))
     
-    async def to_bit_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batching: str = 'auto') -> Result:
+    async def to_bit_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> Result:
 
         """
             Converts lists of tokens to a list of bits, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
@@ -348,15 +346,15 @@
                                         'tokenListBasedContent',
                                     ],
                                     context_filter,
                                 )
                             ),
                             batched(
                                 tokens_list,
-                                self._batch_size,
+                                batch_size,
                             )
                         )
                     )
                 )
             return Result(
                 data=list(
                     map(
@@ -374,15 +372,15 @@
                     )
                 ),
                 error=result.error,
             )
         except Exception as e:
             return Result(error=str(e))
 
-    async def to_string_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batching: str = 'auto') -> Result:
+    async def to_string_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> Result:
 
         """
             Converts lists of tokens to a list of strings, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
@@ -406,15 +404,15 @@
                                         'tokenListBasedContent',
                                     ],
                                     context_filter,
                                 )
                             ),
                             batched(
                                 tokens_list,
-                                self._batch_size,
+                                batch_size,
                             )
                         )
                     )
                 )
             return Result(
                 data=SCNG._bit_list_to_string_list(
                     map(
```

