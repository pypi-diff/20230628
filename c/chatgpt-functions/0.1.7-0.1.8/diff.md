# Comparing `tmp/chatgpt_functions-0.1.7.tar.gz` & `tmp/chatgpt_functions-0.1.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chatgpt_functions-0.1.7.tar", last modified: Wed Jun 28 13:43:49 2023, max compression
+gzip compressed data, was "chatgpt_functions-0.1.8.tar", last modified: Wed Jun 28 14:02:07 2023, max compression
```

## Comparing `chatgpt_functions-0.1.7.tar` & `chatgpt_functions-0.1.8.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 13:43:49.497107 chatgpt_functions-0.1.7/
--rw-rw-rw-   0        0        0     1091 2023-06-26 13:13:15.000000 chatgpt_functions-0.1.7/LICENSE
--rw-rw-rw-   0        0        0     1944 2023-06-28 13:43:49.497107 chatgpt_functions-0.1.7/PKG-INFO
--rw-rw-rw-   0        0        0     1385 2023-06-28 13:42:10.000000 chatgpt_functions-0.1.7/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 13:43:49.465113 chatgpt_functions-0.1.7/chatgpt_functions/
--rw-rw-rw-   0        0        0      194 2023-06-28 13:07:13.000000 chatgpt_functions-0.1.7/chatgpt_functions/__init__.py
--rw-rw-rw-   0        0        0     7901 2023-06-28 13:42:10.000000 chatgpt_functions-0.1.7/chatgpt_functions/chatgpt.py
--rw-rw-rw-   0        0        0      724 2023-06-28 12:30:01.000000 chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_function.py
--rw-rw-rw-   0        0        0      789 2023-06-28 13:02:26.000000 chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_types.py
--rw-rw-rw-   0        0        0     1323 2023-06-28 12:34:42.000000 chatgpt_functions-0.1.7/chatgpt_functions/function_parameters.py
-drwxrwxrwx   0        0        0        0 2023-06-28 13:43:49.494593 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/
--rw-rw-rw-   0        0        0     1944 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      428 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       50 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-06-28 13:43:49.000000 chatgpt_functions-0.1.7/chatgpt_functions.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      682 2023-06-26 14:36:57.000000 chatgpt_functions-0.1.7/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-28 13:43:49.498107 chatgpt_functions-0.1.7/setup.cfg
--rw-rw-rw-   0        0        0     1268 2023-06-28 13:43:36.000000 chatgpt_functions-0.1.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:02:07.319677 chatgpt_functions-0.1.8/
+-rw-rw-rw-   0        0        0     1091 2023-06-26 13:13:15.000000 chatgpt_functions-0.1.8/LICENSE
+-rw-rw-rw-   0        0        0     1944 2023-06-28 14:02:07.319677 chatgpt_functions-0.1.8/PKG-INFO
+-rw-rw-rw-   0        0        0     1385 2023-06-28 13:42:10.000000 chatgpt_functions-0.1.8/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 14:02:07.303932 chatgpt_functions-0.1.8/chatgpt_functions/
+-rw-rw-rw-   0        0        0      194 2023-06-28 13:07:13.000000 chatgpt_functions-0.1.8/chatgpt_functions/__init__.py
+-rw-rw-rw-   0        0        0     7979 2023-06-28 13:56:30.000000 chatgpt_functions-0.1.8/chatgpt_functions/chatgpt.py
+-rw-rw-rw-   0        0        0      724 2023-06-28 12:30:01.000000 chatgpt_functions-0.1.8/chatgpt_functions/chatgpt_function.py
+-rw-rw-rw-   0        0        0      789 2023-06-28 13:02:26.000000 chatgpt_functions-0.1.8/chatgpt_functions/chatgpt_types.py
+-rw-rw-rw-   0        0        0     1323 2023-06-28 12:34:42.000000 chatgpt_functions-0.1.8/chatgpt_functions/function_parameters.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:02:07.318676 chatgpt_functions-0.1.8/chatgpt_functions.egg-info/
+-rw-rw-rw-   0        0        0     1944 2023-06-28 14:02:07.000000 chatgpt_functions-0.1.8/chatgpt_functions.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      428 2023-06-28 14:02:07.000000 chatgpt_functions-0.1.8/chatgpt_functions.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:02:07.000000 chatgpt_functions-0.1.8/chatgpt_functions.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       50 2023-06-28 14:02:07.000000 chatgpt_functions-0.1.8/chatgpt_functions.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 14:02:07.000000 chatgpt_functions-0.1.8/chatgpt_functions.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      682 2023-06-26 14:36:57.000000 chatgpt_functions-0.1.8/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 14:02:07.320677 chatgpt_functions-0.1.8/setup.cfg
+-rw-rw-rw-   0        0        0     1268 2023-06-28 14:01:54.000000 chatgpt_functions-0.1.8/setup.py
```

### Comparing `chatgpt_functions-0.1.7/LICENSE` & `chatgpt_functions-0.1.8/LICENSE`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.7/PKG-INFO` & `chatgpt_functions-0.1.8/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: chatgpt_functions
-Version: 0.1.7
+Version: 0.1.8
 Summary: Wrapper over the gpt3.5 model, capable of calling functions
 Home-page: https://github.com/Wellmare/chatgpt-functions
 Author: Wellmare
 Author-email: ivan.kolipov@gmail.com
 Keywords: chatgpt functions gpt
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `chatgpt_functions-0.1.7/README.md` & `chatgpt_functions-0.1.8/README.md`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.7/chatgpt_functions/chatgpt.py` & `chatgpt_functions-0.1.8/chatgpt_functions/chatgpt.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,15 +18,16 @@
     completion_tokens: int
     total_tokens: int
 
 
 @dataclass
 class ChatGPTFunctionsMethodResponse:
     is_function_called: bool
-    function_response: None | typing.Any
+    function_response: typing.Any | None
+    function_args: dict | None
     chatgpt_response_message: Message
     usage_tokens: UsageTokens
 
 
 @dataclass
 class ChatGPTMethodResponse:
     chatgpt_response_message: Message
@@ -191,14 +192,15 @@
                         content=json.dumps(function_response),
                     )
                 )
                 self.messages.append(chatgpt_message)
             return ChatGPTFunctionsMethodResponse(
                 is_function_called=True,
                 function_response=function_response,
+                function_args=function_args,
                 chatgpt_response_message=chatgpt_message,
                 usage_tokens=usage_tokens
             )
         else:
             self.log_info("The function is not called")
             # print(response["choices"][0]["message"])
             # return response["choices"][0]["message"]
```

### Comparing `chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_function.py` & `chatgpt_functions-0.1.8/chatgpt_functions/chatgpt_function.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.7/chatgpt_functions/chatgpt_types.py` & `chatgpt_functions-0.1.8/chatgpt_functions/chatgpt_types.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.7/chatgpt_functions/function_parameters.py` & `chatgpt_functions-0.1.8/chatgpt_functions/function_parameters.py`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.7/chatgpt_functions.egg-info/PKG-INFO` & `chatgpt_functions-0.1.8/chatgpt_functions.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: chatgpt-functions
-Version: 0.1.7
+Version: 0.1.8
 Summary: Wrapper over the gpt3.5 model, capable of calling functions
 Home-page: https://github.com/Wellmare/chatgpt-functions
 Author: Wellmare
 Author-email: ivan.kolipov@gmail.com
 Keywords: chatgpt functions gpt
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `chatgpt_functions-0.1.7/pyproject.toml` & `chatgpt_functions-0.1.8/pyproject.toml`

 * *Files identical despite different names*

### Comparing `chatgpt_functions-0.1.7/setup.py` & `chatgpt_functions-0.1.8/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 #     lines = content.splitlines()
 #     lines = [line.strip() for line in lines if line.strip()]
 #     return lines
 
 
 setup(
     name="chatgpt_functions",
-    version="0.1.7",
+    version="0.1.8",
     author="Wellmare",
     author_email="ivan.kolipov@gmail.com",
     description="Wrapper over the gpt3.5 model, capable of calling functions",
     long_description=readme(),
     long_description_content_type="text/markdown",
     url="https://github.com/Wellmare/chatgpt-functions",
     packages=find_packages(),
```

