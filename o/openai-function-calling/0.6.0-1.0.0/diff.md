# Comparing `tmp/openai_function_calling-0.6.0.tar.gz` & `tmp/openai_function_calling-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "openai_function_calling-0.6.0.tar", max compression
+gzip compressed data, was "openai_function_calling-1.0.0.tar", max compression
```

## Comparing `openai_function_calling-0.6.0.tar` & `openai_function_calling-1.0.0.tar`

### file list

```diff
@@ -1,6 +1,8 @@
--rw-r--r--   0        0        0     2161 2023-06-24 18:57:10.088869 openai_function_calling-0.6.0/README.md
--rw-r--r--   0        0        0      316 2023-06-24 18:07:58.595690 openai_function_calling-0.6.0/openai_function_calling/__init__.py
--rw-r--r--   0        0        0     1756 2023-06-25 17:13:35.402170 openai_function_calling-0.6.0/openai_function_calling/function.py
--rw-r--r--   0        0        0     2115 2023-06-25 18:01:57.838552 openai_function_calling-0.6.0/openai_function_calling/parameter.py
--rw-r--r--   0        0        0      571 2023-06-25 18:02:06.446555 openai_function_calling-0.6.0/pyproject.toml
--rw-r--r--   0        0        0     2624 1970-01-01 00:00:00.000000 openai_function_calling-0.6.0/PKG-INFO
+-rw-r--r--   0        0        0     2210 2023-06-28 04:20:47.915657 openai_function_calling-1.0.0/README.md
+-rw-r--r--   0        0        0      407 2023-06-28 04:20:47.916273 openai_function_calling-1.0.0/openai_function_calling/__init__.py
+-rw-r--r--   0        0        0     2901 2023-06-28 04:20:47.916495 openai_function_calling-1.0.0/openai_function_calling/function.py
+-rw-r--r--   0        0        0      330 2023-06-28 04:20:47.916650 openai_function_calling-1.0.0/openai_function_calling/json_schema_type.py
+-rw-r--r--   0        0        0     3147 2023-06-28 04:20:47.916870 openai_function_calling-1.0.0/openai_function_calling/parameter.py
+-rw-r--r--   0        0        0        0 2023-06-28 04:20:47.916908 openai_function_calling-1.0.0/openai_function_calling/py.typed
+-rw-r--r--   0        0        0      625 2023-06-28 04:21:05.954270 openai_function_calling-1.0.0/pyproject.toml
+-rw-r--r--   0        0        0     2671 1970-01-01 00:00:00.000000 openai_function_calling-1.0.0/PKG-INFO
```

### Comparing `openai_function_calling-0.6.0/README.md` & `openai_function_calling-1.0.0/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -13,41 +13,41 @@
 ```
 
 **The openai-function-calling package does come with the openai package. It must be installed separately with `pip install openai`**
 
 ## Usage
 
 ```python
-from openai_function_calling import Function, FunctionDict, Parameter
+from openai_function_calling import Function, FunctionDict, Parameter, JsonSchemaType
 
 def get_current_weather(location: str, unit: str) -> str:
   # Do some stuff here...
 
 # Define the function parameters.
 location_parameter = Parameter(
     name="location",
-    type="string",
+    type=JsonSchemaType.STRING,
     description="The city and state, e.g. San Francisco, CA"
 )
 unit_parameter = Parameter(
     name="unit",
-    type="string",
+    type=JsonSchemaType.STRING,
     description="The temperature unit to use.",
     enum=["celsius", "fahrenheit"]
 )
 
 # Define the function.
 get_current_weather_function = Function(
     "get_current_weather",
     "Get the current weather",
     [location_parameter, unit_parameter],
 )
 
 # Convert to a JSON schema dict to send to OpenAI.
-get_current_weather_function_dict = get_current_weather_function.to_dict()
+get_current_weather_function_dict = get_current_weather_function.to_json_schema()
 
 # Get the function to call from ChatGPT.
 response = openai.ChatCompletion.create(
     model="gpt-3.5-turbo-0613",
     messages=[
       {"role": "user", "content": "What will the weather be like in Boston, MA tomorrow?"}
     ],
```

### Comparing `openai_function_calling-0.6.0/pyproject.toml` & `openai_function_calling-1.0.0/pyproject.toml`

 * *Files 14% similar despite different names*

```diff
@@ -1,23 +1,24 @@
 [tool.poetry]
 name = "openai-function-calling"
-version = "0.6.0"
+version = "1.0.0"
 description = "Helper functions to generate OpenAI GPT function calling requests."
 authors = ["Jake Cyr <cyrjake@gmail.com>"]
 readme = "README.md"
 packages = [{include = "openai_function_calling"}]
+include = ["openai_function_calling/py.typed"]
 
 [tool.poetry.dependencies]
-python = "^3.10"
-typing-extensions = "^4.6.3"
+python = ">=3.10, <=3.12"
+typing-extensions = "^4.0"
 
 [tool.poetry.group.dev.dependencies]
 openai = "^0.27.8"
 black = "^23.3.0"
 pytest = "^7.4.0"
-ruff = "^0.0.275"
+ruff = "~0.0.275"
 coverage = "^7.2.7"
 build = "^0.10.0"
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `openai_function_calling-0.6.0/PKG-INFO` & `openai_function_calling-1.0.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 Metadata-Version: 2.1
 Name: openai-function-calling
-Version: 0.6.0
+Version: 1.0.0
 Summary: Helper functions to generate OpenAI GPT function calling requests.
 Author: Jake Cyr
 Author-email: cyrjake@gmail.com
-Requires-Python: >=3.10,<4.0
+Requires-Python: >=3.10,<=3.12
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Requires-Dist: typing-extensions (>=4.6.3,<5.0.0)
+Requires-Dist: typing-extensions (>=4.0,<5.0)
 Description-Content-Type: text/markdown
 
 # OpenAI Function Calling
 
 ![GitHub Actions Build Status](https://github.com/jakecyr/openai-function-calling/actions/workflows/test-application.yml/badge.svg)
 
 Helper functions to generate JSON schema dicts for OpenAI ChatGPT function calling requests. See the [official Function Calling reference](https://platform.openai.com/docs/guides/gpt/function-calling) for more information.
@@ -26,41 +26,41 @@
 ```
 
 **The openai-function-calling package does come with the openai package. It must be installed separately with `pip install openai`**
 
 ## Usage
 
 ```python
-from openai_function_calling import Function, FunctionDict, Parameter
+from openai_function_calling import Function, FunctionDict, Parameter, JsonSchemaType
 
 def get_current_weather(location: str, unit: str) -> str:
   # Do some stuff here...
 
 # Define the function parameters.
 location_parameter = Parameter(
     name="location",
-    type="string",
+    type=JsonSchemaType.STRING,
     description="The city and state, e.g. San Francisco, CA"
 )
 unit_parameter = Parameter(
     name="unit",
-    type="string",
+    type=JsonSchemaType.STRING,
     description="The temperature unit to use.",
     enum=["celsius", "fahrenheit"]
 )
 
 # Define the function.
 get_current_weather_function = Function(
     "get_current_weather",
     "Get the current weather",
     [location_parameter, unit_parameter],
 )
 
 # Convert to a JSON schema dict to send to OpenAI.
-get_current_weather_function_dict = get_current_weather_function.to_dict()
+get_current_weather_function_dict = get_current_weather_function.to_json_schema()
 
 # Get the function to call from ChatGPT.
 response = openai.ChatCompletion.create(
     model="gpt-3.5-turbo-0613",
     messages=[
       {"role": "user", "content": "What will the weather be like in Boston, MA tomorrow?"}
     ],
```

