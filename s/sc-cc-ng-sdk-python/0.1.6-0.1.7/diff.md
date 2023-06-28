# Comparing `tmp/sc_cc_ng_sdk_python-0.1.6.tar.gz` & `tmp/sc_cc_ng_sdk_python-0.1.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sc_cc_ng_sdk_python-0.1.6.tar", max compression
+gzip compressed data, was "sc_cc_ng_sdk_python-0.1.7.tar", max compression
```

## Comparing `sc_cc_ng_sdk_python-0.1.6.tar` & `sc_cc_ng_sdk_python-0.1.7.tar`

### file list

```diff
@@ -1,4 +1,4 @@
--rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.6/README.md
--rw-r--r--   0        0        0      530 2023-06-28 09:03:32.529617 sc_cc_ng_sdk_python-0.1.6/pyproject.toml
--rw-r--r--   0        0        0    14858 2023-06-28 09:05:34.360540 sc_cc_ng_sdk_python-0.1.6/sc_cc_ng_sdk_python/__init__.py
--rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.6/PKG-INFO
+-rw-r--r--   0        0        0        0 2023-06-26 13:45:09.675633 sc_cc_ng_sdk_python-0.1.7/README.md
+-rw-r--r--   0        0        0      530 2023-06-28 12:50:48.303281 sc_cc_ng_sdk_python-0.1.7/pyproject.toml
+-rw-r--r--   0        0        0    16277 2023-06-28 12:50:17.041509 sc_cc_ng_sdk_python-0.1.7/sc_cc_ng_sdk_python/__init__.py
+-rw-r--r--   0        0        0      497 1970-01-01 00:00:00.000000 sc_cc_ng_sdk_python-0.1.7/PKG-INFO
```

### Comparing `sc_cc_ng_sdk_python-0.1.6/pyproject.toml` & `sc_cc_ng_sdk_python-0.1.7/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "sc-cc-ng-sdk-python"
-version = "0.1.6"
+version = "0.1.7"
 description = ""
 authors = ["Rikard Olsson <rikard@thryselius.se>"]
 readme = "README.md"
 packages = [{include = "sc_cc_ng_sdk_python"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
```

### Comparing `sc_cc_ng_sdk_python-0.1.6/sc_cc_ng_sdk_python/__init__.py` & `sc_cc_ng_sdk_python-0.1.7/sc_cc_ng_sdk_python/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -275,94 +275,131 @@
                         lambda x,y: x.get(y), 
                         response_keys, 
                         result
                     )
                 )
         except Exception as e:
             return Result(error=str(e))
-  
-    async def to_dict_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> ResultAsync:
+
+    async def to_dict_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 5, seq_size: int = 4) -> ResultAsync:
 
         """
             Converts lists of tokens to a list of dicts, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
             :param context_filter: A context filter object.
             :param batching: The batching mode. Can be 'auto', 'none' or 'manual'.
 
             :return: A result object.
         """
         try:
+            final = []
             async with aiohttp.ClientSession() as session:
-                result = self._compile_batched_result(
-                    await asyncio.gather(
-                        *map(
-                            lambda batch: asyncio.ensure_future(
-                                self._fetch_batch(
-                                    session,
-                                    batch,
-                                    SCNG._dict_list_json_query,
-                                    [
-                                        'data',
-                                        'tokensListBasedContentAsDict',
-                                    ],
-                                    context_filter,
-                                )
-                            ),
-                            batched(
-                                tokens_list,
-                                batch_size,
+                for super_batch in map(
+                    lambda super_batch: map(
+                        lambda batch: asyncio.ensure_future(
+                            self._fetch_batch(
+                                session,
+                                batch,
+                                SCNG._dict_list_json_query,
+                                [
+                                    'data',
+                                    'tokensListBasedContentAsDict',
+                                ],
+                                context_filter,
                             )
-                        )
+                        ),
+                        super_batch,
+                    ),
+                    batched(
+                        batched(
+                            tokens_list,
+                            batch_size,
+                        ),
+                        seq_size,
+                    )
+                ):
+                    final.append(
+                        await asyncio.gather(*super_batch)
                     )
+
+            result = self._compile_batched_result(
+                list(
+                    map(
+                        self._compile_batched_result,
+                        final
+                    )
+                )
+            )
+
+            return ResultAsync(
+                data=result.data,
+                error=list(
+                    chain(*result.error),
                 )
-            return result
+            )
         except Exception as e:
             return Result(error=str(e))
     
-    async def to_bit_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> ResultAsync:
+    async def to_bit_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10, seq_size: int = 4) -> ResultAsync:
 
         """
             Converts lists of tokens to a list of bits, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
             :param context_filter: A context filter object.
             :param batching: The batching mode. Can be 'auto', 'none' or 'manual'.
 
             :return: A result object.
         """
         try:
+            final = []
             async with aiohttp.ClientSession() as session:
-                result = self._compile_batched_result(
-                    await asyncio.gather(
-                        *map(
-                            lambda batch: asyncio.ensure_future(
-                                self._fetch_batch(
-                                    session,
-                                    batch,
-                                    SCNG._bit_list_json_query,
-                                    [
-                                        'data',
-                                        'tokenListBasedContent',
-                                    ],
-                                    context_filter,
-                                )
-                            ),
-                            batched(
-                                tokens_list,
-                                batch_size,
+                for super_batch in map(
+                    lambda super_batch: map(
+                        lambda batch: asyncio.ensure_future(
+                            self._fetch_batch(
+                                session,
+                                batch,
+                                SCNG._bit_list_json_query,
+                                [
+                                    'data',
+                                    'tokenListBasedContent',
+                                ],
+                                context_filter,
                             )
-                        )
+                        ),
+                        super_batch,
+                    ),
+                    batched(
+                        batched(
+                            tokens_list,
+                            batch_size,
+                        ),
+                        seq_size,
+                    )
+                ):
+                    final.append(
+                        await asyncio.gather(*super_batch)
+                    )
+
+            result = self._compile_batched_result(
+                list(
+                    map(
+                        self._compile_batched_result,
+                        final
                     )
                 )
-            return Result(
+            )
+
+            return ResultAsync(
                 data=list(
                     map(
                         lambda xs: list(
                             map(
                                 lambda x: BitVal(
                                     context=x['context'],
                                     value=x['value'],
@@ -370,57 +407,76 @@
                                 ),
                                 xs
                             )
                         ),
                         result.data,
                     )
                 ),
-                error=result.error,
+                error=list(
+                    chain(*result.error),
+                )
             )
+
         except Exception as e:
             return Result(error=str(e))
 
-    async def to_string_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10) -> ResultAsync:
+    async def to_string_list(self, tokens_list, context_filter: Optional[ContextFilter] = None, batch_size: int = 10, seq_size: int = 4) -> ResultAsync:
 
         """
             Converts lists of tokens to a list of strings, containing
             all matching meta data to those tokens. If no meta data was found
             for a combination of tokens, the list will be empty.
 
             :param tokens_list: A list of lists of tokens.
             :param context_filter: A context filter object.
             :param batching: The batching mode. Can be 'auto', 'none' or 'manual'.
 
             :return: A result object.
         """
         try:
+            final = []
             async with aiohttp.ClientSession() as session:
-                result = self._compile_batched_result(
-                    await asyncio.gather(
-                        *map(
-                            lambda batch: asyncio.ensure_future(
-                                self._fetch_batch(
-                                    session,
-                                    batch,
-                                    SCNG._bit_list_json_query,
-                                    [
-                                        'data',
-                                        'tokenListBasedContent',
-                                    ],
-                                    context_filter,
-                                )
-                            ),
-                            batched(
-                                tokens_list,
-                                batch_size,
+                for super_batch in map(
+                    lambda super_batch: map(
+                        lambda batch: asyncio.ensure_future(
+                            self._fetch_batch(
+                                session,
+                                batch,
+                                SCNG._bit_list_json_query,
+                                [
+                                    'data',
+                                    'tokenListBasedContent',
+                                ],
+                                context_filter,
                             )
-                        )
+                        ),
+                        super_batch,
+                    ),
+                    batched(
+                        batched(
+                            tokens_list,
+                            batch_size,
+                        ),
+                        seq_size,
+                    )
+                ):
+                    final.append(
+                        await asyncio.gather(*super_batch)
+                    )
+
+            result = self._compile_batched_result(
+                list(
+                    map(
+                        self._compile_batched_result,
+                        final
                     )
                 )
-            return Result(
+            )
+
+            return ResultAsync(
                 data=SCNG._bit_list_to_string_list(
                     map(
                         lambda xs: list(
                             map(
                                 lambda x: BitVal(
                                     context=x['context'],
                                     value=x['value'],
@@ -428,11 +484,14 @@
                                 ),
                                 xs
                             )
                         ),
                         result.data,
                     )
                 ),
-                error=result.error,
+                error=list(
+                    chain(*result.error),
+                )
             )
+
         except Exception as e:
             return Result(error=str(e))
```

