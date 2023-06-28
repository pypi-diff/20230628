# Comparing `tmp/chatgpt_functions-0.1.6.tar.gz` & `tmp/chatgpt_functions-0.1.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chatgpt_functions-0.1.6.tar", last modified: Wed Jun 28 13:34:45 2023, max compression
+gzip compressed data, was "chatgpt_functions-0.1.7.tar", last modified: Wed Jun 28 13:43:49 2023, max compression
```

## Comparing `chatgpt_functions-0.1.6.tar` & `chatgpt_functions-0.1.7.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 13:34:45.614275 chatgpt_functions-0.1.6/
--rw-rw-rw-   0        0        0     1091 2023-06-26 13:13:15.000000 chatgpt_functions-0.1.6/LICENSE
--rw-rw-rw-   0        0        0     1935 2023-06-28 13:34:45.614275 chatgpt_functions-0.1.6/PKG-INFO
--rw-rw-rw-   0        0        0     1374 2023-06-26 12:54:41.000000 chatgpt_functions-0.1.6/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 13:34:45.594724 chatgpt_functions-0.1.6/chatgpt_functions/
--rw-rw-rw-   0        0        0      194 2023-06-28 13:07:13.000000 chatgpt_functions-0.1.6/chatgpt_functions/__init__.py
--rw-rw-rw-   0        0        0     7848 2023-06-28 13:31:35.000000 chatgpt_functions-0.1.6/chatgpt_functions/chatgpt.py
--rw-rw-rw-   0        0        0      724 2023-06-28 12:30:01.000000 chatgpt_functions-0.1.6/chatgpt_functions/chatgpt_function.py
--rw-rw-rw-   0        0        0      789 2023-06-28 13:02:26.000000 chatgpt_functions-0.1.6/chatgpt_functions/chatgpt_types.py
--rw-rw-rw-   0        0        0     1323 2023-06-28 12:34:42.000000 chatgpt_functions-0.1.6/chatgpt_functions/function_parameters.py
-drwxrwxrwx   0        0        0        0 2023-06-28 13:34:45.612274 chatgpt_functions-0.1.6/chatgpt_functions.egg-info/
--rw-rw-rw-   0        0        0     1935 2023-06-28 13:34:45.000000 chatgpt_functions-0.1.6/chatgpt_functions.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      428 2023-06-28 13:34:45.000000 chatgpt_functions-0.1.6/chatgpt_functions.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 13:34:45.000000 chatgpt_functions-0.1.6/chatgpt_functions.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       50 2023-06-28 13:34:45.000000 chatgpt_functions-0.1.6/chatgpt_functions.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-06-28 13:34:45.000000 chatgpt_functions-0.1.6/chatgpt_functions.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      682 2023-06-26 14:36:57.000000 chatgpt_functions-0.1.6/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-28 13:34:45.615781 chatgpt_functions-0.1.6/setup.cfg
--rw-rw-rw-   0        0        0     1268 2023-06-28 12:38:45.000000 chatgpt_functions-0.1.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:43:49.497107 chatgpt_functions-0.1.7/
+-rw-rw-rw-   0        0        0     1091 2023-06-26 13:13:15.000000 chatgpt_functions-0.1.7/LICENSE
+-rw-rw-rw-   0        0        0     1944 2023-06-28 13:43:49.497107 chatgpt_functions-0.1.7/PKG-INFO
+-rw-rw-rw-   0        0        0     1385 2023-06-28 13:42:10.000000 chatgpt_functions-0.1.7/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 13:43:49.465113 chatgpt_functions-0.1.7/chatgpt_functions/
+-rw-rw-rw-   0        0        0      194 2023-06-28 13:07:13.000000 chatgpt_functions-0.1.7/chatgpt_functions/__init__.py
+-rw-rw-rw-   0        0        0     7901 2023-06-28 13:42:10.000000 chatgpt_functions-0.1.7/chatgpt_functions/chatgpt.py
+-rw-rw-rw-   0        0        0      724 2023-06-28 12:30:01.000000 chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_function.py
+-rw-rw-rw-   0        0        0      789 2023-06-28 13:02:26.000000 chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_types.py
+-rw-rw-rw-   0        0        0     1323 2023-06-28 12:34:42.000000 chatgpt_functions-0.1.7/chatgpt_functions/function_parameters.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:43:49.494593 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/
+-rw-rw-rw-   0        0        0     1944 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      428 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       50 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      682 2023-06-26 14:36:57.000000 chatgpt_functions-0.1.7/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:43:49.498107 chatgpt_functions-0.1.7/setup.cfg
+-rw-rw-rw-   0        0        0     1268 2023-06-28 13:43:36.000000 chatgpt_functions-0.1.7/setup.py
```

### Comparing `chatgpt_functions-0.1.6/LICENSE` & `chatgpt_functions-0.1.7/LICENSE`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.6/PKG-INFO` & `chatgpt_functions-0.1.7/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,23 +1,24 @@
 Metadata-Version: 2.1
 Name: chatgpt_functions
-Version: 0.1.6
+Version: 0.1.7
 Summary: Wrapper over the gpt3.5 model, capable of calling functions
 Home-page: https://github.com/Wellmare/chatgpt-functions
 Author: Wellmare
 Author-email: ivan.kolipov@gmail.com
 Keywords: chatgpt functions gpt
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Example of usage:
+
 ```python
 import asyncio
 from chatgpt_functions import (
     ChatGPT,
     Message,
     Roles,
     ChatGptFunction,
@@ -51,15 +52,15 @@
                             description="Greeting",
                         ),
                     ]
                 ),
                 function_description="Say hello to user",
             )
         ],
-        messages=[Message(role=Roles.USER, content='РЎРєР°Р¶Рё РїСЂРёРІРµС‚РёРє РјРёС‡Рµ')]
+        messages_to_set=[Message(role=Roles.USER, content='РЎРєР°Р¶Рё РїСЂРёРІРµС‚РёРє РјРёС‡Рµ')]
     )
 
 
 loop = asyncio.new_event_loop()
 asyncio.set_event_loop(loop)
 loop.run_until_complete(main())
 ```
```

### Comparing `chatgpt_functions-0.1.6/README.md` & `chatgpt_functions-0.1.7/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,9 @@
 # Example of usage:
+
 ```python
 import asyncio
 from chatgpt_functions import (
     ChatGPT,
     Message,
     Roles,
     ChatGptFunction,
@@ -36,15 +37,15 @@
                             description="Greeting",
                         ),
                     ]
                 ),
                 function_description="Say hello to user",
             )
         ],
-        messages=[Message(role=Roles.USER, content='Скажи приветик миче')]
+        messages_to_set=[Message(role=Roles.USER, content='Скажи приветик миче')]
     )
 
 
 loop = asyncio.new_event_loop()
 asyncio.set_event_loop(loop)
 loop.run_until_complete(main())
-```
+```
```

### Comparing `chatgpt_functions-0.1.6/chatgpt_functions/chatgpt.py` & `chatgpt_functions-0.1.7/chatgpt_functions/chatgpt.py`

 * *Files 1% similar despite different names*

```diff
@@ -57,15 +57,15 @@
         return wrapper
 
     return decorator
 
 
 class ChatGPT:
     AVAILABLE_FUNCTIONS = {}
-    message: list[Message] = []
+    messages: list[Message] = []
 
     def __init__(
             self,
             openai_api_key: str,
             messages: list[Message] | None = None,
             model: str = "gpt-3.5-turbo",
             is_log: bool = False,
@@ -89,20 +89,20 @@
             self.logger.error(message)
 
     def log_debug(self, message):
         if self.is_log:
             self.logger.debug(message)
 
     @retry_decorator(tries=3, delay=2)
-    async def get_chatgpt_response(self, messages: list[Message] | None = None, temperature: float = 0.5,
+    async def get_chatgpt_response(self, messages_to_set: list[Message] | None = None, temperature: float = 0.5,
                                    max_tokens: int = 1024, ) -> ChatGPTMethodResponse:
-        if messages is not None:
-            self.messages = messages
+        if messages_to_set is not None:
+            self.messages = messages_to_set
 
-        self.log_debug(f"messages: {messages}")
+        self.log_debug(f"messages: {self.messages}")
         response = await openai.ChatCompletion.acreate(
             model=self.model,
             messages=[message.__dict__() for message in self.messages],
             temperature=temperature,
             max_tokens=max_tokens,
         )
 
@@ -123,24 +123,24 @@
             usage_tokens=usage_tokens,
         )
 
     @retry_decorator(tries=3, delay=2)
     async def get_chatgpt_response_with_functions(
             self,
             functions: list[ChatGptFunction],
-            messages: list[Message] | None = None,
+            messages_to_set: list[Message] | None = None,
             temperature: float = 0.5,
             max_tokens: int = 1024,
             is_add_function_output: bool = False,
     ) -> ChatGPTFunctionsMethodResponse:
         # try:
-        if messages is not None:
-            self.messages = messages
+        if messages_to_set is not None:
+            self.messages = messages_to_set
 
-        self.log_debug(f"messages: {messages}")
+        self.log_debug(f"messages: {self.messages}")
 
         functions_to_chatgpt = [
             function.append_available_functions(self.AVAILABLE_FUNCTIONS)
             or function.__dict__()
             for function in functions
         ]
         self.log_debug(f"functions_to_chatgpt: {functions_to_chatgpt}")
```

### Comparing `chatgpt_functions-0.1.6/chatgpt_functions/chatgpt_function.py` & `chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_function.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.6/chatgpt_functions/chatgpt_types.py` & `chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_types.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.6/chatgpt_functions/function_parameters.py` & `chatgpt_functions-0.1.7/chatgpt_functions/function_parameters.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.6/chatgpt_functions.egg-info/PKG-INFO` & `chatgpt_functions-0.1.7/chatgpt_functions.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,23 +1,24 @@
 Metadata-Version: 2.1
 Name: chatgpt-functions
-Version: 0.1.6
+Version: 0.1.7
 Summary: Wrapper over the gpt3.5 model, capable of calling functions
 Home-page: https://github.com/Wellmare/chatgpt-functions
 Author: Wellmare
 Author-email: ivan.kolipov@gmail.com
 Keywords: chatgpt functions gpt
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Example of usage:
+
 ```python
 import asyncio
 from chatgpt_functions import (
     ChatGPT,
     Message,
     Roles,
     ChatGptFunction,
@@ -51,15 +52,15 @@
                             description="Greeting",
                         ),
                     ]
                 ),
                 function_description="Say hello to user",
             )
         ],
-        messages=[Message(role=Roles.USER, content='РЎРєР°Р¶Рё РїСЂРёРІРµС‚РёРє РјРёС‡Рµ')]
+        messages_to_set=[Message(role=Roles.USER, content='РЎРєР°Р¶Рё РїСЂРёРІРµС‚РёРє РјРёС‡Рµ')]
     )
 
 
 loop = asyncio.new_event_loop()
 asyncio.set_event_loop(loop)
 loop.run_until_complete(main())
 ```
```

### Comparing `chatgpt_functions-0.1.6/pyproject.toml` & `chatgpt_functions-0.1.7/pyproject.toml`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.6/setup.py` & `chatgpt_functions-0.1.7/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 #     lines = content.splitlines()
 #     lines = [line.strip() for line in lines if line.strip()]
 #     return lines
 
 
 setup(
     name="chatgpt_functions",
-    version="0.1.6",
+    version="0.1.7",
     author="Wellmare",
     author_email="ivan.kolipov@gmail.com",
     description="Wrapper over the gpt3.5 model, capable of calling functions",
     long_description=readme(),
     long_description_content_type="text/markdown",
     url="https://github.com/Wellmare/chatgpt-functions",
     packages=find_packages(),
```

