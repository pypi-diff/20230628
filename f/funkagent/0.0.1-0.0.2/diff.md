# Comparing `tmp/funkagent-0.0.1.tar.gz` & `tmp/funkagent-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "funkagent-0.0.1.tar", max compression
+gzip compressed data, was "funkagent-0.0.2.tar", max compression
```

## Comparing `funkagent-0.0.1.tar` & `funkagent-0.0.2.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0       12 2023-06-18 00:56:07.670379 funkagent-0.0.1/README.md
--rw-r--r--   0        0        0        0 2023-06-18 11:40:51.943567 funkagent-0.0.1/funkagent/__init__.py
--rw-r--r--   0        0        0     5374 2023-06-20 04:10:41.717528 funkagent-0.0.1/funkagent/agents.py
--rw-r--r--   0        0        0     1969 2023-06-18 12:14:34.335673 funkagent-0.0.1/funkagent/parser.py
--rw-r--r--   0        0        0      330 2023-06-18 11:43:23.465203 funkagent-0.0.1/pyproject.toml
--rw-r--r--   0        0        0      649 1970-01-01 00:00:00.000000 funkagent-0.0.1/setup.py
--rw-r--r--   0        0        0      484 1970-01-01 00:00:00.000000 funkagent-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0       62 2023-06-28 02:20:17.486654 funkagent-0.0.2/README.md
+-rw-r--r--   0        0        0        0 2023-06-18 11:40:51.943567 funkagent-0.0.2/funkagent/__init__.py
+-rw-r--r--   0        0        0     5374 2023-06-20 04:10:41.717528 funkagent-0.0.2/funkagent/agents.py
+-rw-r--r--   0        0        0     2059 2023-06-28 02:32:49.032389 funkagent-0.0.2/funkagent/parser.py
+-rw-r--r--   0        0        0      330 2023-06-28 02:34:15.838360 funkagent-0.0.2/pyproject.toml
+-rw-r--r--   0        0        0      705 1970-01-01 00:00:00.000000 funkagent-0.0.2/setup.py
+-rw-r--r--   0        0        0      534 1970-01-01 00:00:00.000000 funkagent-0.0.2/PKG-INFO
```

### Comparing `funkagent-0.0.1/funkagent/agents.py` & `funkagent-0.0.2/funkagent/agents.py`

 * *Files identical despite different names*

### Comparing `funkagent-0.0.1/funkagent/parser.py` & `funkagent-0.0.2/funkagent/parser.py`

 * *Files 16% similar despite different names*

```diff
@@ -8,26 +8,28 @@
     elif dtype == int:
         return "integer"
     elif dtype == str:
         return "string"
     else:
         return "string"
 
+
 def extract_params(doc_str: str):
     # parse the docstring to get the descriptions for each parameter in dict format
     params_str = doc_str.split("\n\n")[1].split("\n")
     params = {}
     for line in params_str:
         param_match = re.findall(r'(?<=:param )\w+(?=:)', line)
         if param_match != []:
             param_name = param_match[0]
             desc_match = line.replace(f":param {param_name}:", "").strip()
             params[param_name] = desc_match
     return params
 
+
 def func_to_json(func):
     # first we get function name
     func_name = func.__name__
     # then we get the function annotations
     argspec = inspect.getfullargspec(func)
     # get the function docstring
     func_doc = inspect.getdoc(func)
@@ -41,19 +43,22 @@
     param_details = extract_params(func_doc)
     # attach parameter types to params
     for param_name in argspec.args:
         params[param_name] = {
             "description": param_details.get(param_name) or "",
             "type": type_mapping(argspec.annotations[param_name])
         }
-    # get parameters for function including default values (that are optional)
-    len_optional_params = len(inspect.getfullargspec(func).defaults)
+    # calculate required parameters
+    _required = argspec.args
+    if inspect.getfullargspec(func).defaults:
+        _required = [argspec.args[i] for i, a in enumerate(argspec.args) if
+                     i + 1 not in inspect.getfullargspec(func).defaults]
     # then return everything in dict
     return {
         "name": func_name,
         "description": func_description,
         "parameters": {
             "type": "object",
             "properties": params
         },
-        "required": argspec.args[:len_optional_params]
-    }
+        "required": _required
+    }
```

### Comparing `funkagent-0.0.1/setup.py` & `funkagent-0.0.2/setup.py`

 * *Files 23% similar despite different names*

```diff
@@ -8,17 +8,17 @@
 {'': ['*']}
 
 install_requires = \
 ['openai>=0.27.8,<0.28.0']
 
 setup_kwargs = {
     'name': 'funkagent',
-    'version': '0.0.1',
+    'version': '0.0.2',
     'description': 'Minimal agent framework using OpenAI functions',
-    'long_description': '# funkagent\n',
+    'long_description': '# FunkAgent\n\nGet started with:\n\n```\npip install funkagent\n```\n',
     'author': 'James Briggs',
     'author_email': 'james@aurelio.ai',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
     'packages': packages,
     'package_data': package_data,
```

