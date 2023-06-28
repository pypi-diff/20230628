# Comparing `tmp/linear_cli_ai-0.1.1.tar.gz` & `tmp/linear_cli_ai-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "linear_cli_ai-0.1.1.tar", max compression
+gzip compressed data, was "linear_cli_ai-0.1.2.tar", max compression
```

## Comparing `linear_cli_ai-0.1.1.tar` & `linear_cli_ai-0.1.2.tar`

### file list

```diff
@@ -1,13 +1,15 @@
--rw-r--r--   0        0        0    11357 2023-06-19 14:13:31.689313 linear_cli_ai-0.1.1/LICENSE
--rw-r--r--   0        0        0      397 2023-06-28 03:47:31.594600 linear_cli_ai-0.1.1/README.md
--rw-r--r--   0        0        0      543 2023-06-28 08:12:43.272413 linear_cli_ai-0.1.1/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-23 15:09:53.034479 linear_cli_ai-0.1.1/src/__init__.py
--rw-r--r--   0        0        0      101 2023-06-28 05:20:24.733251 linear_cli_ai-0.1.1/src/exceptions.py
--rw-r--r--   0        0        0     1347 2023-06-28 07:36:53.616167 linear_cli_ai-0.1.1/src/function_schema.py
--rw-r--r--   0        0        0     1791 2023-06-28 05:07:54.946635 linear_cli_ai-0.1.1/src/gpt.py
--rw-r--r--   0        0        0     8338 2023-06-28 07:35:34.449550 linear_cli_ai-0.1.1/src/linear.py
--rw-r--r--   0        0        0     1991 2023-06-28 07:46:36.815977 linear_cli_ai-0.1.1/src/linear_ai.py
--rw-r--r--   0        0        0     4833 2023-06-28 06:43:22.960364 linear_cli_ai-0.1.1/src/main.py
--rw-r--r--   0        0        0      297 2023-06-27 16:14:52.685333 linear_cli_ai-0.1.1/src/objectTypes.py
--rw-r--r--   0        0        0     1229 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.1/setup.py
--rw-r--r--   0        0        0      975 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-19 14:13:31.689313 linear_cli_ai-0.1.2/LICENSE
+-rw-r--r--   0        0        0     2052 2023-06-28 11:59:06.189396 linear_cli_ai-0.1.2/README.md
+-rw-r--r--   0        0        0      543 2023-06-28 12:02:42.884638 linear_cli_ai-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-23 15:09:53.034479 linear_cli_ai-0.1.2/src/__init__.py
+-rw-r--r--   0        0        0      491 2023-06-28 10:33:01.304077 linear_cli_ai-0.1.2/src/configure.py
+-rw-r--r--   0        0        0      506 2023-06-28 11:27:59.296189 linear_cli_ai-0.1.2/src/constants.py
+-rw-r--r--   0        0        0      101 2023-06-28 05:20:24.733251 linear_cli_ai-0.1.2/src/exceptions.py
+-rw-r--r--   0        0        0     1347 2023-06-28 07:36:53.616167 linear_cli_ai-0.1.2/src/function_schema.py
+-rw-r--r--   0        0        0     1688 2023-06-28 08:20:48.951813 linear_cli_ai-0.1.2/src/gpt.py
+-rw-r--r--   0        0        0     8207 2023-06-28 09:15:34.167953 linear_cli_ai-0.1.2/src/linear.py
+-rw-r--r--   0        0        0     1991 2023-06-28 07:46:36.815977 linear_cli_ai-0.1.2/src/linear_ai.py
+-rw-r--r--   0        0        0     5923 2023-06-28 11:56:00.654423 linear_cli_ai-0.1.2/src/main.py
+-rw-r--r--   0        0        0      297 2023-06-27 16:14:52.685333 linear_cli_ai-0.1.2/src/objectTypes.py
+-rw-r--r--   0        0        0     2963 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.2/setup.py
+-rw-r--r--   0        0        0     2630 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.2/PKG-INFO
```

### Comparing `linear_cli_ai-0.1.1/LICENSE` & `linear_cli_ai-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `linear_cli_ai-0.1.1/pyproject.toml` & `linear_cli_ai-0.1.2/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "linear-cli-ai"
-version = "0.1.1"
+version = "0.1.2"
 description = "A simple cli for interacting with linear"
 authors = ["scar3crow <rss.holmes@gmail.com>"]
 readme = "README.md"
 packages = [{include = "src"}]
 
 [tool.poetry.dependencies]
 python = "3.8.10"
```

### Comparing `linear_cli_ai-0.1.1/src/function_schema.py` & `linear_cli_ai-0.1.2/src/function_schema.py`

 * *Files identical despite different names*

### Comparing `linear_cli_ai-0.1.1/src/gpt.py` & `linear_cli_ai-0.1.2/src/gpt.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,19 +1,11 @@
-import os
 from typing import Any, Dict, List
-
 import requests
-from dotenv import load_dotenv
-
 from function_schema import functions
-
-load_dotenv()
-
-GPT_MODEL = os.getenv("GPT_MODEL") or ""
-OPENAI_API_KEY = os.getenv("OPENAI_API_KEY") or ""
+from constants import GPT_MODEL, OPENAI_API_KEY
 
 def chat_completion_request(
     messages: List[Dict["str", "str"]],
     functions: Any = None,
     model: str = GPT_MODEL,
 ):
     try:
```

### Comparing `linear_cli_ai-0.1.1/src/linear.py` & `linear_cli_ai-0.1.2/src/linear.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,32 +1,26 @@
 import json
-import os
 from typing import Dict, List, Union
 
 import requests
-from dotenv import load_dotenv
 from requests.exceptions import HTTPError
-
-load_dotenv()
-
-LINEAR_GRAPHQL_ENDPOINT = os.getenv("LINEAR_GRAPHQL_ENDPOINT") or ""
-LINEAR_HEADER_AUTH = os.getenv("LINEAR_HEADER_AUTH") or ""
+from constants import LINEAR_GRAPHQL_ENDPOINT, LINEAR_TOKEN
 
 
 def make_linear_call(
     query: str,
 ) -> Dict[str, Dict[str, Dict[str, List[Dict[str, str]]]]]:
     """
     Function to make a call to linear
     """
 
     response = requests.post(
         LINEAR_GRAPHQL_ENDPOINT,
         json={"query": query},
-        headers={"Authorization": LINEAR_HEADER_AUTH},
+        headers={"Authorization": LINEAR_TOKEN},
     )
 
     if response.status_code != 200:
         raise HTTPError(
             f"Linear API returned status code {response.status_code} with message {response.text}"
         )
```

### Comparing `linear_cli_ai-0.1.1/src/linear_ai.py` & `linear_cli_ai-0.1.2/src/linear_ai.py`

 * *Files identical despite different names*

### Comparing `linear_cli_ai-0.1.1/src/main.py` & `linear_cli_ai-0.1.2/src/main.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,25 +1,69 @@
+import json
+from typing import Dict, List, cast
+
 import typer
-# from PyInquirer import Separator, prompt
+from PyInquirer import prompt  # type: ignore
 from rich import print as rprint
-from typing import Dict, List
-import json
-from gpt import ask_question, setup_ai_system
-from linear_ai import create_issue_ai, get_team_list_ai
 
+from configure import configure_system
+from gpt import ask_question, setup_ai_system
 from linear import (
     create_issue,
     get_label_list,
     get_project_list,
     get_team_list,
     get_user_list,
 )
+from linear_ai import create_issue_ai, get_team_list_ai
 
 app = typer.Typer()
 
+
+@app.command("configure")
+def configure():
+    gpt_models_list = [
+        {
+            "name": "gpt-3.5-turbo-0613",
+        },
+        {
+            "name": "gpt4",
+        },
+    ]
+
+    rprint("[yellow]Provide the following details : [yellow]")
+
+    config_input_list: List[Dict[str, str]] = [
+        {
+            "type": "input",
+            "name": "linear_api_token",
+            "message": "Linear API Token : ",
+        },
+        {
+            "type": "input",
+            "name": "openai_api_key",
+            "message": "OpenAI API Key : ",
+        },
+        {
+            "type": "list",
+            "name": "gpt_model",
+            "message": "Select the model you will use : ",
+            "choices": gpt_models_list,
+        },
+    ]
+
+    config_data = cast(Dict[str, str], prompt(config_input_list))
+
+    linear_api_token: str = config_data["linear_api_token"]
+    openai_api_key: str = config_data["openai_api_key"]
+    gpt_model: str = config_data["gpt_model"]
+
+    configure_system(linear_api_token, openai_api_key, gpt_model)
+
+
 @app.command("create-issue")
 def create_issue_interface():
     rprint("[yellow]Provide the following details : [yellow]")
 
     team_list = get_team_list()
     user_list = get_user_list()
     project_list = get_project_list()
@@ -104,15 +148,16 @@
         if issue_created:
             rprint("[green bold]Issue created successfully [green bold]")
         else:
             rprint("[red bold]Error while creating the issue [red bold]")
     else:
         rprint("[red bold]Issue creation cancelled. [red bold]")
 
-@app.command("create-issue-ai")
+
+@app.command("ai")
 def create_issue_ai_interface():
     running = 1
     message_history: List[Dict[str, str]] = []
     setup_ai_system(message_history)
     user_message = input("What would you like to do on linear : ")
 
     while running:
```

