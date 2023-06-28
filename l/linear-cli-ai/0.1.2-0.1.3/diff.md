# Comparing `tmp/linear_cli_ai-0.1.2.tar.gz` & `tmp/linear_cli_ai-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "linear_cli_ai-0.1.2.tar", max compression
+gzip compressed data, was "linear_cli_ai-0.1.3.tar", max compression
```

## Comparing `linear_cli_ai-0.1.2.tar` & `linear_cli_ai-0.1.3.tar`

### file list

```diff
@@ -1,15 +1,15 @@
--rw-r--r--   0        0        0    11357 2023-06-19 14:13:31.689313 linear_cli_ai-0.1.2/LICENSE
--rw-r--r--   0        0        0     2052 2023-06-28 11:59:06.189396 linear_cli_ai-0.1.2/README.md
--rw-r--r--   0        0        0      543 2023-06-28 12:02:42.884638 linear_cli_ai-0.1.2/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-23 15:09:53.034479 linear_cli_ai-0.1.2/src/__init__.py
--rw-r--r--   0        0        0      491 2023-06-28 10:33:01.304077 linear_cli_ai-0.1.2/src/configure.py
--rw-r--r--   0        0        0      506 2023-06-28 11:27:59.296189 linear_cli_ai-0.1.2/src/constants.py
--rw-r--r--   0        0        0      101 2023-06-28 05:20:24.733251 linear_cli_ai-0.1.2/src/exceptions.py
--rw-r--r--   0        0        0     1347 2023-06-28 07:36:53.616167 linear_cli_ai-0.1.2/src/function_schema.py
--rw-r--r--   0        0        0     1688 2023-06-28 08:20:48.951813 linear_cli_ai-0.1.2/src/gpt.py
--rw-r--r--   0        0        0     8207 2023-06-28 09:15:34.167953 linear_cli_ai-0.1.2/src/linear.py
--rw-r--r--   0        0        0     1991 2023-06-28 07:46:36.815977 linear_cli_ai-0.1.2/src/linear_ai.py
--rw-r--r--   0        0        0     5923 2023-06-28 11:56:00.654423 linear_cli_ai-0.1.2/src/main.py
--rw-r--r--   0        0        0      297 2023-06-27 16:14:52.685333 linear_cli_ai-0.1.2/src/objectTypes.py
--rw-r--r--   0        0        0     2963 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.2/setup.py
--rw-r--r--   0        0        0     2630 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-19 14:13:31.689313 linear_cli_ai-0.1.3/LICENSE
+-rw-r--r--   0        0        0     2052 2023-06-28 11:59:06.189396 linear_cli_ai-0.1.3/README.md
+-rw-r--r--   0        0        0      590 2023-06-28 16:00:35.127582 linear_cli_ai-0.1.3/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 15:53:15.300034 linear_cli_ai-0.1.3/src/__init__.py
+-rw-r--r--   0        0        0      491 2023-06-28 10:33:01.304077 linear_cli_ai-0.1.3/src/configure.py
+-rw-r--r--   0        0        0      551 2023-06-28 15:40:01.022333 linear_cli_ai-0.1.3/src/constants.py
+-rw-r--r--   0        0        0      101 2023-06-28 05:20:24.733251 linear_cli_ai-0.1.3/src/exceptions.py
+-rw-r--r--   0        0        0     1347 2023-06-28 07:36:53.616167 linear_cli_ai-0.1.3/src/function_schema.py
+-rw-r--r--   0        0        0     1696 2023-06-28 15:56:19.575319 linear_cli_ai-0.1.3/src/gpt.py
+-rw-r--r--   0        0        0     8211 2023-06-28 15:56:35.746880 linear_cli_ai-0.1.3/src/linear.py
+-rw-r--r--   0        0        0     1995 2023-06-28 15:56:24.562944 linear_cli_ai-0.1.3/src/linear_ai.py
+-rw-r--r--   0        0        0     5944 2023-06-28 15:55:52.256039 linear_cli_ai-0.1.3/src/main.py
+-rw-r--r--   0        0        0      297 2023-06-27 16:14:52.685333 linear_cli_ai-0.1.3/src/objectTypes.py
+-rw-r--r--   0        0        0     3062 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.3/setup.py
+-rw-r--r--   0        0        0     2630 1970-01-01 00:00:00.000000 linear_cli_ai-0.1.3/PKG-INFO
```

### Comparing `linear_cli_ai-0.1.2/LICENSE` & `linear_cli_ai-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `linear_cli_ai-0.1.2/README.md` & `linear_cli_ai-0.1.3/README.md`

 * *Files identical despite different names*

### Comparing `linear_cli_ai-0.1.2/src/function_schema.py` & `linear_cli_ai-0.1.3/src/function_schema.py`

 * *Files identical despite different names*

### Comparing `linear_cli_ai-0.1.2/src/gpt.py` & `linear_cli_ai-0.1.3/src/gpt.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 from typing import Any, Dict, List
 import requests
-from function_schema import functions
-from constants import GPT_MODEL, OPENAI_API_KEY
+from src.function_schema import functions
+from src.constants import GPT_MODEL, OPENAI_API_KEY
 
 def chat_completion_request(
     messages: List[Dict["str", "str"]],
     functions: Any = None,
     model: str = GPT_MODEL,
 ):
     try:
```

### Comparing `linear_cli_ai-0.1.2/src/linear.py` & `linear_cli_ai-0.1.3/src/linear.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 import json
 from typing import Dict, List, Union
 
 import requests
 from requests.exceptions import HTTPError
-from constants import LINEAR_GRAPHQL_ENDPOINT, LINEAR_TOKEN
+from src.constants import LINEAR_GRAPHQL_ENDPOINT, LINEAR_TOKEN
 
 
 def make_linear_call(
     query: str,
 ) -> Dict[str, Dict[str, Dict[str, List[Dict[str, str]]]]]:
     """
     Function to make a call to linear
```

### Comparing `linear_cli_ai-0.1.2/src/linear_ai.py` & `linear_cli_ai-0.1.3/src/linear_ai.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from typing import List, Set
 
-from linear import (
+from src.linear import (
     check_and_extract_assignee,
     check_and_extract_labels,
     check_and_extract_project,
     check_and_extract_team,
     create_issue,
 )
```

### Comparing `linear_cli_ai-0.1.2/src/main.py` & `linear_cli_ai-0.1.3/src/main.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,24 +1,24 @@
 import json
 from typing import Dict, List, cast
 
 import typer
 from PyInquirer import prompt  # type: ignore
 from rich import print as rprint
 
-from configure import configure_system
-from gpt import ask_question, setup_ai_system
-from linear import (
+from src.configure import configure_system
+from src.gpt import ask_question, setup_ai_system
+from src.linear import (
     create_issue,
     get_label_list,
     get_project_list,
     get_team_list,
     get_user_list,
 )
-from linear_ai import create_issue_ai, get_team_list_ai
+from src.linear_ai import create_issue_ai, get_team_list_ai
 
 app = typer.Typer()
 
 
 @app.command("configure")
 def configure():
     gpt_models_list = [
@@ -183,9 +183,10 @@
             print("There was an error while calling function")
             print(e)
             user_message = (
                 f"""Encountered an error during creating issue. Error is {e}"""
             )
 
 
-if __name__ == "__main__":
-    app()
+# if __name__ == "__main__":
+
+#     app()
```

### Comparing `linear_cli_ai-0.1.2/setup.py` & `linear_cli_ai-0.1.3/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -12,25 +12,29 @@
  'pyinquirer>=1.0.3,<2.0.0',
  'python-dotenv>=1.0.0,<2.0.0',
  'requests>=2.31.0,<3.0.0',
  'rich>=13.4.2,<14.0.0',
  'textual[dev]>=0.28.0,<0.29.0',
  'typer[all]>=0.9.0,<0.10.0']
 
+entry_points = \
+{'console_scripts': ['linear = src.main:app']}
+
 setup_kwargs = {
     'name': 'linear-cli-ai',
-    'version': '0.1.2',
+    'version': '0.1.3',
     'description': 'A simple cli for interacting with linear',
     'long_description': "# linear-cli\nAn AI based CLI for the linear app\n\n# Installation\n\nInstallation of linear-cli-ai and its dependencies require ``python`` and ``pip``. To ensure smooth installation,\nit's recommended to use:\n\n- ``python``: 3.8.10 or greater\n- ``pip``: 9.0.2 or greater\n\nThe safest way to install globally is to use\n\n```\n\n   $ python -m pip install linear-cli-ai\n\n```\n\nor for your user:\n\n```\n\n   $ python -m pip install --user linear-cli-ai\n\n```\n\nIf you have the linear-cli-ai package installed and want to upgrade to the\nlatest version, you can run:\n\n```\n\n   $ python -m pip install --upgrade linear-cli-ai\n\n```\n\n# Configuration\n\nBefore using linear-cli-ai, you need to configure a few keys.\nYou can do this in several ways:\n\n-  Configuration command\n-  Environment variables\n-  Config file\n\nThe quickest way to get started is to run the ``linear-cli-ai configure`` command:\n\n```\n$ linear-cli-ai configure\n  Provide the following details : \n   Linear API Token : MY_LINEAR_TOKEN\n   OpenAI API Key : MY_OPENAI_KEY\n   Select the model you will use : gpt4 or gpt-3.5-turbo-0613\n\n```\n\nTo use environment variables, do the following:\n\n```\n\n   $ export LINEAR_TOKEN=<linear_token>\n   $ export GPT_MODEL=<gpt_model>\n   $ export OPENAI_API_KEY=<openai_api_key>\n\n```\n\nTo use a config file, create an INI formatted file like this:\n\n```\n\n  [linear]\n  token = <linear_token>\n  \n  [gpt]\n  token = <openai_api_key>\n  model = <gpt_model>\n\n```\nand place it in ``~/.linear-cli-ai.ini`` (or in ``%UserProfile%\\.linear-cli-ai.ini``\non Windows).\n\n# Sample Usage\n\nTo view help documentation type :\n\n```\n$ linear-cli-ai help\n```\n\nTo use ai to perform actions on linear:\n\n```\n$ linear-cli-ai ai\n```\n\nTo create an issue via options on linear :\n\n```\n$ linear-cli-ai create-issue\n```\n### Sample ai prompt for creating an issue on linear\nCreate an issue with description 'Rewrite the print service with queue system'\nand title as 'Print Service v2.0' and team as 'engineering' and assign it to 'Rohan'\nand add labels 'bug' and 'high priority' and add it to project 'Print Service'\n\n\n",
     'author': 'scar3crow',
     'author_email': 'rss.holmes@gmail.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
     'packages': packages,
     'package_data': package_data,
     'install_requires': install_requires,
+    'entry_points': entry_points,
     'python_requires': '==3.8.10',
 }
 
 
 setup(**setup_kwargs)
```

### Comparing `linear_cli_ai-0.1.2/PKG-INFO` & `linear_cli_ai-0.1.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: linear-cli-ai
-Version: 0.1.2
+Version: 0.1.3
 Summary: A simple cli for interacting with linear
 Author: scar3crow
 Author-email: rss.holmes@gmail.com
 Requires-Python: ==3.8.10
 Classifier: Programming Language :: Python :: 3
 Requires-Dist: openai (>=0.27.8,<0.28.0)
 Requires-Dist: pyinquirer (>=1.0.3,<2.0.0)
```

