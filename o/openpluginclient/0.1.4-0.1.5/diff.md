# Comparing `tmp/openpluginclient-0.1.4.tar.gz` & `tmp/openpluginclient-0.1.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "openpluginclient-0.1.4.tar", last modified: Tue Jun 27 17:40:48 2023, max compression
+gzip compressed data, was "openpluginclient-0.1.5.tar", last modified: Tue Jun 27 17:56:53 2023, max compression
```

## Comparing `openpluginclient-0.1.4.tar` & `openpluginclient-0.1.5.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:40:48.754436 openpluginclient-0.1.4/
--rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 17:40:48.754436 openpluginclient-0.1.4/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:40:48.754436 openpluginclient-0.1.4/openpluginclient/
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-27 17:40:37.000000 openpluginclient-0.1.4/openpluginclient/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2328 2023-06-27 17:40:37.000000 openpluginclient-0.1.4/openpluginclient/openpluginclient.py
--rw-r--r--   0 runner    (1001) docker     (123)    18582 2023-06-27 17:40:37.000000 openpluginclient-0.1.4/openpluginclient/plugins.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 17:40:37.000000 openpluginclient-0.1.4/openpluginclient/types.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:40:48.754436 openpluginclient-0.1.4/openpluginclient.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 17:40:48.000000 openpluginclient-0.1.4/openpluginclient.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      372 2023-06-27 17:40:48.000000 openpluginclient-0.1.4/openpluginclient.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 17:40:48.000000 openpluginclient-0.1.4/openpluginclient.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-27 17:40:48.000000 openpluginclient-0.1.4/openpluginclient.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-27 17:40:48.000000 openpluginclient-0.1.4/openpluginclient.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 17:40:48.754436 openpluginclient-0.1.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-27 17:40:37.000000 openpluginclient-0.1.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:40:48.754436 openpluginclient-0.1.4/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 17:40:37.000000 openpluginclient-0.1.4/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1912 2023-06-27 17:40:37.000000 openpluginclient-0.1.4/tests/test_completion.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/
+-rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/openpluginclient/
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2190 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/openpluginclient.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18582 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/plugins.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/types.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/openpluginclient.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      372 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1978 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/tests/test_completion.py
```

### Comparing `openpluginclient-0.1.4/PKG-INFO` & `openpluginclient-0.1.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: openpluginclient
-Version: 0.1.4
+Version: 0.1.5
 Summary: Python package for accessing ChatGPT plugins via API
 Home-page: UNKNOWN
 Author: Sebastian Sosa
 Author-email: 1sebastian1sosa1@gmail.com
 License: UNKNOWN
 Description: Client for accessing ChatGPT plugins via OpenPlugin API
 Keywords: python,openai,chatgpt,chat,plugin
```

### Comparing `openpluginclient-0.1.4/openpluginclient/openpluginclient.py` & `openpluginclient-0.1.5/openpluginclient/openpluginclient.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,16 +1,13 @@
 import json
 import requests
 import os
 from pathlib import Path
 
 SUPPORTED_MODELS = ["gpt-4-0613", "gpt-3.5-turbo-0613"]
-DEVELOPMENT = False
-if (os.getenv("DEVELOPMENT") == "true"):
-    DEVELOPMENT = True
 
 def get_supported_plugins():
     file_path = Path(__file__).parent / "plugins.json"
     with open(file_path, 'r') as f:
         return json.load(f)
 
 def openplugin_completion(early_access_token: str, plugin_name: str = None, fail_silently: bool = False, **chatgpt_args):
@@ -40,18 +37,16 @@
         "plugin_name": plugin_name,
         **chatgpt_args,
         "model": model,
         "messages": chatgpt_args.get("messages"),
     }
 
     try:
-        # make a post request to localhost:3000
         server = "https://openplugin-api-30b78451a615.herokuapp.com"
-        if DEVELOPMENT:
-            server = "http://localhost:3000"
+        # server = "http://localhost:3000" # For local testing
         
         response = requests.post(f"{server}/chat_completion", json=body)
         json_response = response.json()
         if ('error' in json_response):
             raise Exception(f"Error: {json_response['error']}")
     except Exception as e:
         if fail_silently:
```

### Comparing `openpluginclient-0.1.4/openpluginclient/plugins.json` & `openpluginclient-0.1.5/openpluginclient/plugins.json`

 * *Files identical despite different names*

### Comparing `openpluginclient-0.1.4/openpluginclient.egg-info/PKG-INFO` & `openpluginclient-0.1.5/openpluginclient.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: openpluginclient
-Version: 0.1.4
+Version: 0.1.5
 Summary: Python package for accessing ChatGPT plugins via API
 Home-page: UNKNOWN
 Author: Sebastian Sosa
 Author-email: 1sebastian1sosa1@gmail.com
 License: UNKNOWN
 Description: Client for accessing ChatGPT plugins via OpenPlugin API
 Keywords: python,openai,chatgpt,chat,plugin
```

### Comparing `openpluginclient-0.1.4/setup.py` & `openpluginclient-0.1.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from setuptools import setup, find_packages
 
 # Setting up
 setup(
        # the name must match the folder name 'verysimplemodule'
         name='openpluginclient', 
-        version="0.1.4",
+        version="0.1.5",
         author="Sebastian Sosa",
         author_email="1sebastian1sosa1@gmail.com",
         description='Python package for accessing ChatGPT plugins via API',
         long_description='Client for accessing ChatGPT plugins via OpenPlugin API',
         packages=find_packages(),
         package_data={
             "openpluginclient": ["*.json"],  # include all .json files in the openplugin package
```

### Comparing `openpluginclient-0.1.4/tests/test_completion.py` & `openpluginclient-0.1.5/tests/test_completion.py`

 * *Files 12% similar despite different names*

```diff
@@ -6,20 +6,20 @@
 # check if there is an environmental variable set for IS_GITHUB_ACTION
 if "IS_GITHUB_ACTION" in os.environ:
     print("Running in Github Action")
 else:
     sys.path.insert(0, './')
 
 EARLY_ACCESS_TOKEN = os.environ.get("EARLY_ACCESS_TOKEN")
-DEVELOPMENT = os.environ.get("DEVELOPMENT") == "true"
-print("DEVELOPMENT", DEVELOPMENT)
+OPENPLUGIN_DEVELOPMENT = os.environ.get("OPENPLUGIN_DEVELOPMENT") == "true"
+print("OPENPLUGIN_DEVELOPMENT", OPENPLUGIN_DEVELOPMENT)
 
 from openpluginclient import openplugin_completion
 
-@pytest.mark.skipif(not DEVELOPMENT, reason="Skipping test. Not in DEVELOPMENT mode")
+@pytest.mark.skipif(not OPENPLUGIN_DEVELOPMENT, reason="Skipping test. Not in OPENPLUGIN_DEVELOPMENT mode")
 def test_openplugin_completion_todo():
     todo = f'test_chat_completion_{random.randint(0, 100000)}'
 
     completion = openplugin_completion(
         early_access_token = EARLY_ACCESS_TOKEN,
         plugin_name = "__testing__",
         model = "gpt-3.5-turbo-0613",
```

