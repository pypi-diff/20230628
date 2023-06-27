# Comparing `tmp/im_openai-0.1.2.tar.gz` & `tmp/im_openai-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "im_openai-0.1.2.tar", last modified: Fri Jun 23 21:57:33 2023, max compression
+gzip compressed data, was "im_openai-0.2.0.tar", last modified: Tue Jun 27 22:35:32 2023, max compression
```

## Comparing `im_openai-0.1.2.tar` & `im_openai-0.2.0.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-23 21:57:33.822033 im_openai-0.1.2/
--rw-r--r--   0 vscode    (1000) vscode    (1000)      150 2023-06-20 23:30:14.000000 im_openai-0.1.2/AUTHORS.rst
--rw-r--r--   0 vscode    (1000) vscode    (1000)     3560 2023-06-22 20:28:17.000000 im_openai-0.1.2/CONTRIBUTING.rst
--rw-r--r--   0 vscode    (1000) vscode    (1000)     1069 2023-06-20 23:30:14.000000 im_openai-0.1.2/LICENSE
--rw-r--r--   0 vscode    (1000) vscode    (1000)      261 2023-06-22 20:24:41.000000 im_openai-0.1.2/MANIFEST.in
--rw-r--r--   0 vscode    (1000) vscode    (1000)     2555 2023-06-23 21:57:33.823740 im_openai-0.1.2/PKG-INFO
--rw-r--r--   0 vscode    (1000) vscode    (1000)     1560 2023-06-21 23:37:53.000000 im_openai-0.1.2/README.md
-drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-23 21:57:33.784705 im_openai-0.1.2/docs/
--rw-r--r--   0 vscode    (1000) vscode    (1000)      610 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/Makefile
--rw-r--r--   0 vscode    (1000) vscode    (1000)       28 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/authors.rst
--rwxr-xr-x   0 vscode    (1000) vscode    (1000)     4874 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/conf.py
--rw-r--r--   0 vscode    (1000) vscode    (1000)       33 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/contributing.rst
--rw-r--r--   0 vscode    (1000) vscode    (1000)       28 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/history.rst
--rw-r--r--   0 vscode    (1000) vscode    (1000)      325 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/index.rst
--rw-r--r--   0 vscode    (1000) vscode    (1000)     1175 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/installation.rst
--rw-r--r--   0 vscode    (1000) vscode    (1000)      807 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/make.bat
--rw-r--r--   0 vscode    (1000) vscode    (1000)       26 2023-06-22 20:24:52.000000 im_openai-0.1.2/docs/readme.rst
--rw-r--r--   0 vscode    (1000) vscode    (1000)       92 2023-06-20 23:30:14.000000 im_openai-0.1.2/docs/usage.rst
-drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-23 21:57:33.797818 im_openai-0.1.2/im_openai/
--rw-r--r--   0 vscode    (1000) vscode    (1000)      255 2023-06-23 16:59:08.000000 im_openai-0.1.2/im_openai/__init__.py
--rw-r--r--   0 vscode    (1000) vscode    (1000)     1799 2023-06-23 21:48:36.000000 im_openai-0.1.2/im_openai/client.py
--rw-r--r--   0 vscode    (1000) vscode    (1000)     1755 2023-06-21 23:21:08.000000 im_openai-0.1.2/im_openai/patch.py
--rw-r--r--   0 vscode    (1000) vscode    (1000)      423 2023-06-23 21:56:38.000000 im_openai-0.1.2/im_openai/template.py
-drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-23 21:57:33.814635 im_openai-0.1.2/im_openai.egg-info/
--rw-r--r--   0 vscode    (1000) vscode    (1000)     2555 2023-06-23 21:57:33.000000 im_openai-0.1.2/im_openai.egg-info/PKG-INFO
--rw-r--r--   0 vscode    (1000) vscode    (1000)      531 2023-06-23 21:57:33.000000 im_openai-0.1.2/im_openai.egg-info/SOURCES.txt
--rw-r--r--   0 vscode    (1000) vscode    (1000)        1 2023-06-23 21:57:33.000000 im_openai-0.1.2/im_openai.egg-info/dependency_links.txt
--rw-r--r--   0 vscode    (1000) vscode    (1000)        1 2023-06-23 21:57:33.000000 im_openai-0.1.2/im_openai.egg-info/not-zip-safe
--rw-r--r--   0 vscode    (1000) vscode    (1000)       10 2023-06-23 21:57:33.000000 im_openai-0.1.2/im_openai.egg-info/top_level.txt
--rw-r--r--   0 vscode    (1000) vscode    (1000)      426 2023-06-23 21:57:33.826054 im_openai-0.1.2/setup.cfg
--rw-r--r--   0 vscode    (1000) vscode    (1000)     1350 2023-06-23 21:57:20.000000 im_openai-0.1.2/setup.py
-drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-23 21:57:33.819989 im_openai-0.1.2/tests/
--rw-r--r--   0 vscode    (1000) vscode    (1000)       39 2023-06-20 23:30:14.000000 im_openai-0.1.2/tests/__init__.py
--rw-r--r--   0 vscode    (1000) vscode    (1000)      559 2023-06-20 23:30:14.000000 im_openai-0.1.2/tests/test_im_openai.py
+drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-27 22:35:32.829151 im_openai-0.2.0/
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      150 2023-06-20 23:30:14.000000 im_openai-0.2.0/AUTHORS.rst
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     3560 2023-06-22 20:28:17.000000 im_openai-0.2.0/CONTRIBUTING.rst
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     1069 2023-06-20 23:30:14.000000 im_openai-0.2.0/LICENSE
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      261 2023-06-22 20:24:41.000000 im_openai-0.2.0/MANIFEST.in
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     2635 2023-06-27 22:35:32.829688 im_openai-0.2.0/PKG-INFO
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     1553 2023-06-24 00:40:31.000000 im_openai-0.2.0/README.md
+drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-27 22:35:32.784802 im_openai-0.2.0/docs/
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      610 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/Makefile
+-rw-r--r--   0 vscode    (1000) vscode    (1000)       28 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/authors.rst
+-rwxr-xr-x   0 vscode    (1000) vscode    (1000)     4874 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/conf.py
+-rw-r--r--   0 vscode    (1000) vscode    (1000)       33 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/contributing.rst
+-rw-r--r--   0 vscode    (1000) vscode    (1000)       28 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/history.rst
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      325 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/index.rst
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     1175 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/installation.rst
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      807 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/make.bat
+-rw-r--r--   0 vscode    (1000) vscode    (1000)       26 2023-06-22 20:24:52.000000 im_openai-0.2.0/docs/readme.rst
+-rw-r--r--   0 vscode    (1000) vscode    (1000)       92 2023-06-20 23:30:14.000000 im_openai-0.2.0/docs/usage.rst
+drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-27 22:35:32.800505 im_openai-0.2.0/im_openai/
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      255 2023-06-23 16:59:08.000000 im_openai-0.2.0/im_openai/__init__.py
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     2341 2023-06-27 22:34:00.000000 im_openai-0.2.0/im_openai/client.py
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     2498 2023-06-27 22:33:34.000000 im_openai-0.2.0/im_openai/patch.py
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      423 2023-06-23 21:56:38.000000 im_openai-0.2.0/im_openai/template.py
+drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-27 22:35:32.821306 im_openai-0.2.0/im_openai.egg-info/
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     2635 2023-06-27 22:35:32.000000 im_openai-0.2.0/im_openai.egg-info/PKG-INFO
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      531 2023-06-27 22:35:32.000000 im_openai-0.2.0/im_openai.egg-info/SOURCES.txt
+-rw-r--r--   0 vscode    (1000) vscode    (1000)        1 2023-06-27 22:35:32.000000 im_openai-0.2.0/im_openai.egg-info/dependency_links.txt
+-rw-r--r--   0 vscode    (1000) vscode    (1000)        1 2023-06-27 22:35:32.000000 im_openai-0.2.0/im_openai.egg-info/not-zip-safe
+-rw-r--r--   0 vscode    (1000) vscode    (1000)       10 2023-06-27 22:35:32.000000 im_openai-0.2.0/im_openai.egg-info/top_level.txt
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      426 2023-06-27 22:35:32.831410 im_openai-0.2.0/setup.cfg
+-rw-r--r--   0 vscode    (1000) vscode    (1000)     1350 2023-06-26 18:47:51.000000 im_openai-0.2.0/setup.py
+drwxr-xr-x   0 vscode    (1000) vscode    (1000)        0 2023-06-27 22:35:32.827367 im_openai-0.2.0/tests/
+-rw-r--r--   0 vscode    (1000) vscode    (1000)       39 2023-06-20 23:30:14.000000 im_openai-0.2.0/tests/__init__.py
+-rw-r--r--   0 vscode    (1000) vscode    (1000)      559 2023-06-20 23:30:14.000000 im_openai-0.2.0/tests/test_im_openai.py
```

### Comparing `im_openai-0.1.2/CONTRIBUTING.rst` & `im_openai-0.2.0/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `im_openai-0.1.2/LICENSE` & `im_openai-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `im_openai-0.1.2/PKG-INFO` & `im_openai-0.2.0/im_openai.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: im_openai
-Version: 0.1.2
+Name: im-openai
+Version: 0.2.0
 Summary: Wrapper library for openai to send events to the Imaginary Programming monitor
 Home-page: https://github.com/alecf/im_openai
 Author: Alec Flett
 Author-email: alec@thegp.com
 License: MIT license
 Keywords: im_openai
 Classifier: Development Status :: 2 - Pre-Alpha
@@ -63,15 +63,15 @@
 ```
 
 If you're using langchain, you can set the ip_project_key in the langchain llm setup:
 
 ```python
 llm = OpenAI(
     openai_api_key=os.environ["OPENAI_API_KEY"],
-    model_kwargs={"ip_prompt_project_key": "my_project_key"},
+    model_kwargs={"ip_project_key": "my_project_key"},
 )
 ```
 
 ## Credits
 
 This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.
 
@@ -85,10 +85,14 @@
 
 -   First release on PyPI.
 
 ## 0.1.1 (2023-06-23)
 
 -   add TemplateString helper and support for data / params
 
-## 0.1.2(2023-06-23)
+## 0.1.2 (2023-06-23)
 
 -   add support for original template too
+
+## 0.2.0 (2023-06-26)
+
+- add explicit support for passing the "prompt template text"
```

### Comparing `im_openai-0.1.2/README.md` & `im_openai-0.2.0/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -41,15 +41,15 @@
 ```
 
 If you're using langchain, you can set the ip_project_key in the langchain llm setup:
 
 ```python
 llm = OpenAI(
     openai_api_key=os.environ["OPENAI_API_KEY"],
-    model_kwargs={"ip_prompt_project_key": "my_project_key"},
+    model_kwargs={"ip_project_key": "my_project_key"},
 )
 ```
 
 ## Credits
 
 This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.
```

### Comparing `im_openai-0.1.2/docs/Makefile` & `im_openai-0.2.0/docs/Makefile`

 * *Files identical despite different names*

### Comparing `im_openai-0.1.2/docs/conf.py` & `im_openai-0.2.0/docs/conf.py`

 * *Files identical despite different names*

### Comparing `im_openai-0.1.2/docs/installation.rst` & `im_openai-0.2.0/docs/installation.rst`

 * *Files identical despite different names*

### Comparing `im_openai-0.1.2/docs/make.bat` & `im_openai-0.2.0/docs/make.bat`

 * *Files identical despite different names*

### Comparing `im_openai-0.1.2/im_openai/client.py` & `im_openai-0.2.0/im_openai/client.py`

 * *Files 15% similar despite different names*

```diff
@@ -4,61 +4,84 @@
 from contextlib import contextmanager
 
 import requests
 
 
 def send_event(
     project_key: str,
+    api_name: str,
     prompt_event_id: str,
-    prompt_text: str = None,
+    prompt_text: str,
+    prompt_params: dict = None,
     response: str = None,
     response_time: float = None,
 ):
     PROMPT_REPORTING_URL = os.environ.get(
         "PROMPT_REPORTING_URL", "https://app.imaginary.dev/api/event"
     )
     event = {
+        "projectKey": project_key,
+        "apiName": api_name,
         "params": {},
         "prompt": {},
-        "projectKey": project_key,
         "promptEventId": prompt_event_id,
     }
     if prompt_text is not None:
-        event["prompt"]["prompt_text"] = prompt_text
-        if getattr(prompt_text, "params", None):
+        # first default template to just the raw text
+        event["promptTemplateText"] = prompt_text
+
+        if prompt_params is None and getattr(prompt_text, "params", None):
             # Can be TemplateString or any other
-            event["params"] = prompt_text.params
+            prompt_params = prompt_text.params
 
         # If the original template is available, send it too
         if getattr(prompt_text, "template", None):
-            event["prompt"]["template"] = prompt_text.template
+            event["promptTemplateText"] = prompt_text.template
 
+    if prompt_params is not None:
+        event["params"] = prompt_params
     if response is not None:
         event["response"] = response
     if response_time is not None:
         event["responseTime"] = response_time
 
     response = requests.post(PROMPT_REPORTING_URL, json=event)
     response.raise_for_status()
 
 
 @contextmanager
-def event_session(project_key: str, prompt_event_id: str = None):
+def event_session(
+    project_key: str,
+    api_name: str,
+    prompt_text: str,
+    prompt_template_params: dict = None,
+    prompt_event_id: str = None,
+):
     """Context manager for sending an event to Imaginary Dev.
 
     Usage::
 
-        with event_session(project_key, prompt_event_id) as complete_event:
+        with event_session(project_key, api_name, prompt_text, prompt_event_id) as complete_event:
             # do something
             complete_event(response)
 
     """
     start = time.time()
     if prompt_event_id is None:
         prompt_event_id = str(uuid.uuid4())
-    send_event(project_key, prompt_event_id)
+    send_event(
+        project_key, api_name, prompt_event_id, prompt_text, prompt_template_params
+    )
 
     def complete_event(response):
         response_time = (time.time() - start) * 1000
-        send_event(project_key, prompt_event_id, response, response_time)
+        send_event(
+            project_key,
+            api_name,
+            prompt_event_id,
+            prompt_text,
+            prompt_template_params,
+            response,
+            response_time,
+        )
 
     yield complete_event
```

### Comparing `im_openai-0.1.2/im_openai/patch.py` & `im_openai-0.2.0/im_openai/patch.py`

 * *Files 26% similar despite different names*

```diff
@@ -2,26 +2,41 @@
 from typing import Callable
 
 from openai import ChatCompletion, Completion
 
 from .client import event_session
 
 
-def patch_openai_class(cls, get_result: Callable):
+def patch_openai_class(cls, get_prompt_text: Callable, get_result: Callable):
     oldcreate = cls.create
 
     def local_create(
-        cls, *args, ip_project_key=None, ip_event_id=None, ip_template_id=None, **kwargs
+        cls,
+        *args,
+        ip_project_key=None,
+        ip_api_name=None,
+        ip_event_id=None,
+        ip_template_text=None,
+        ip_template_params=None,
+        **kwargs
     ):
         if ip_project_key is None:
             ip_project_key = os.environ.get("PROMPT_PROJECT_KEY")
         if ip_project_key is None:
             return oldcreate(*args, **kwargs)
+        if ip_template_text is None:
+            ip_template_text = get_prompt_text(*args, **kwargs)
 
-        with event_session(ip_project_key, ip_event_id) as complete_event:
+        with event_session(
+            ip_project_key,
+            ip_api_name,
+            ip_template_text,
+            ip_template_params,
+            ip_event_id,
+        ) as complete_event:
             response = oldcreate(*args, **kwargs)
             complete_event(get_result(response))
         return response
 
     oldacreate = cls.acreate
 
     async def local_create_async(cls, *args, template=None, **kwargs):
@@ -46,17 +61,31 @@
     return unpatch
 
 
 def patch_openai():
     """Patch openai APIs to add logging capabilities.
 
     Returns a function which may be called to "unpatch" the APIs."""
-    unpatch_chat = patch_openai_class(Completion, lambda x: x["choices"][0]["text"])
+
+    def get_completion_prompt_text(*args, prompt=None, **kwargs):
+        return prompt
+
     unpatch_completion = patch_openai_class(
-        ChatCompletion, lambda x: x["choices"][0]["message"]["content"]
+        Completion, get_completion_prompt_text, lambda x: x["choices"][0]["text"]
+    )
+
+    def get_chat_prompt_text(*args, messages=None, **kwargs):
+        # TODO: What should we be sending? For now we'll just send the last message
+        prompt_text = messages[-1]["content"]
+        return prompt_text
+
+    unpatch_chat = patch_openai_class(
+        ChatCompletion,
+        get_chat_prompt_text,
+        lambda x: x["choices"][0]["message"]["content"],
     )
 
     def unpatch():
         unpatch_chat()
         unpatch_completion()
 
     return unpatch
```

### Comparing `im_openai-0.1.2/im_openai.egg-info/PKG-INFO` & `im_openai-0.2.0/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: im-openai
-Version: 0.1.2
+Name: im_openai
+Version: 0.2.0
 Summary: Wrapper library for openai to send events to the Imaginary Programming monitor
 Home-page: https://github.com/alecf/im_openai
 Author: Alec Flett
 Author-email: alec@thegp.com
 License: MIT license
 Keywords: im_openai
 Classifier: Development Status :: 2 - Pre-Alpha
@@ -63,15 +63,15 @@
 ```
 
 If you're using langchain, you can set the ip_project_key in the langchain llm setup:
 
 ```python
 llm = OpenAI(
     openai_api_key=os.environ["OPENAI_API_KEY"],
-    model_kwargs={"ip_prompt_project_key": "my_project_key"},
+    model_kwargs={"ip_project_key": "my_project_key"},
 )
 ```
 
 ## Credits
 
 This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.
 
@@ -85,10 +85,14 @@
 
 -   First release on PyPI.
 
 ## 0.1.1 (2023-06-23)
 
 -   add TemplateString helper and support for data / params
 
-## 0.1.2(2023-06-23)
+## 0.1.2 (2023-06-23)
 
 -   add support for original template too
+
+## 0.2.0 (2023-06-26)
+
+- add explicit support for passing the "prompt template text"
```

### Comparing `im_openai-0.1.2/im_openai.egg-info/SOURCES.txt` & `im_openai-0.2.0/im_openai.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `im_openai-0.1.2/setup.py` & `im_openai-0.2.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,10 +38,10 @@
     include_package_data=True,
     keywords="im_openai",
     name="im_openai",
     packages=find_packages(include=["im_openai", "im_openai.*"]),
     test_suite="tests",
     tests_require=test_requirements,
     url="https://github.com/alecf/im_openai",
-    version="0.1.2",
+    version="0.2.0",
     zip_safe=False,
 )
```

### Comparing `im_openai-0.1.2/tests/test_im_openai.py` & `im_openai-0.2.0/tests/test_im_openai.py`

 * *Files identical despite different names*

