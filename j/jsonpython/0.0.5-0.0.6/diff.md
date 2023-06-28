# Comparing `tmp/jsonpython-0.0.5.tar.gz` & `tmp/jsonpython-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jsonpython-0.0.5.tar", last modified: Thu Jun  2 17:36:56 2022, max compression
+gzip compressed data, was "jsonpython-0.0.6.tar", last modified: Wed Jun 28 07:03:39 2023, max compression
```

## Comparing `jsonpython-0.0.5.tar` & `jsonpython-0.0.6.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0        0        0        0 2022-06-02 17:36:56.110918 jsonpython-0.0.5/
--rw-rw-rw-   0        0        0     1061 2022-06-02 07:30:01.000000 jsonpython-0.0.5/LICENSE
--rw-rw-rw-   0        0        0     1202 2022-06-02 17:36:56.109919 jsonpython-0.0.5/PKG-INFO
--rw-rw-rw-   0        0        0      741 2022-06-02 12:35:34.000000 jsonpython-0.0.5/README.md
--rw-rw-rw-   0        0        0       86 2022-06-02 07:51:40.000000 jsonpython-0.0.5/pyproject.toml
--rw-rw-rw-   0        0        0       42 2022-06-02 17:36:56.110918 jsonpython-0.0.5/setup.cfg
--rw-rw-rw-   0        0        0      768 2022-06-02 17:36:21.000000 jsonpython-0.0.5/setup.py
-drwxrwxrwx   0        0        0        0 2022-06-02 17:36:56.075892 jsonpython-0.0.5/src/
-drwxrwxrwx   0        0        0        0 2022-06-02 17:36:56.087886 jsonpython-0.0.5/src/jsonpython/
--rw-rw-rw-   0        0        0      180 2022-06-02 17:35:37.000000 jsonpython-0.0.5/src/jsonpython/__init__.py
--rw-rw-rw-   0        0        0      663 2022-06-02 17:35:18.000000 jsonpython-0.0.5/src/jsonpython/json.py
--rw-rw-rw-   0        0        0      938 2022-06-02 17:34:17.000000 jsonpython-0.0.5/src/jsonpython/json_core.py
--rw-rw-rw-   0        0        0     3168 2022-06-02 17:14:55.000000 jsonpython-0.0.5/src/jsonpython/parser.py
-drwxrwxrwx   0        0        0        0 2022-06-02 17:36:56.108920 jsonpython-0.0.5/src/jsonpython.egg-info/
--rw-rw-rw-   0        0        0     1202 2022-06-02 17:36:55.000000 jsonpython-0.0.5/src/jsonpython.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      296 2022-06-02 17:36:56.000000 jsonpython-0.0.5/src/jsonpython.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2022-06-02 17:36:55.000000 jsonpython-0.0.5/src/jsonpython.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       11 2022-06-02 17:36:55.000000 jsonpython-0.0.5/src/jsonpython.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 07:03:39.223143 jsonpython-0.0.6/
+-rw-rw-rw-   0        0        0     1061 2022-06-02 07:30:01.000000 jsonpython-0.0.6/LICENSE
+-rw-rw-rw-   0        0        0     1219 2023-06-28 07:03:39.222159 jsonpython-0.0.6/PKG-INFO
+-rw-rw-rw-   0        0        0      737 2023-06-28 06:44:50.000000 jsonpython-0.0.6/README.md
+-rw-rw-rw-   0        0        0       86 2022-06-02 07:51:40.000000 jsonpython-0.0.6/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 07:03:39.223143 jsonpython-0.0.6/setup.cfg
+-rw-rw-rw-   0        0        0      768 2023-06-28 07:01:49.000000 jsonpython-0.0.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:03:39.167515 jsonpython-0.0.6/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 07:03:39.201920 jsonpython-0.0.6/src/jsonpython/
+-rw-rw-rw-   0        0        0      180 2022-06-02 17:35:37.000000 jsonpython-0.0.6/src/jsonpython/__init__.py
+-rw-rw-rw-   0        0        0      962 2023-06-28 07:01:29.000000 jsonpython-0.0.6/src/jsonpython/json.py
+-rw-rw-rw-   0        0        0      938 2022-06-02 17:34:17.000000 jsonpython-0.0.6/src/jsonpython/json_core.py
+-rw-rw-rw-   0        0        0     3170 2023-06-28 06:54:16.000000 jsonpython-0.0.6/src/jsonpython/parser.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:03:39.221144 jsonpython-0.0.6/src/jsonpython.egg-info/
+-rw-rw-rw-   0        0        0     1219 2023-06-28 07:03:39.000000 jsonpython-0.0.6/src/jsonpython.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      296 2023-06-28 07:03:39.000000 jsonpython-0.0.6/src/jsonpython.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:03:39.000000 jsonpython-0.0.6/src/jsonpython.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 07:03:39.000000 jsonpython-0.0.6/src/jsonpython.egg-info/top_level.txt
```

### Comparing `jsonpython-0.0.5/LICENSE` & `jsonpython-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `jsonpython-0.0.5/PKG-INFO` & `jsonpython-0.0.6/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 Metadata-Version: 2.1
 Name: jsonpython
-Version: 0.0.5
+Version: 0.0.6
 Summary: A package to deserialize and serialize json files.
 Home-page: https://github.com/TAFH-debug/jsonpy
 Author: TAFH-debug
 Author-email: aushahman2007@gmail.com
 License: LICENSE
+Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Jsonpython
@@ -37,15 +38,15 @@
   }
 }
 ```
 
 #### main.py
 
 ```python
-from src.jsonpython import *
+from jsonpython import *
 
 jobj = get_json_object("data.json")
 
 print(jobj['name'])  # Alex
 print(jobj['car']['model'])  # Tesla X
 
 
@@ -65,7 +66,8 @@
     car: Car
 
 
 person = get_class(Person, "data.json")
 
 print(person.car.model)  # Tesla X
 ```
+
```

### Comparing `jsonpython-0.0.5/README.md` & `jsonpython-0.0.6/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -23,15 +23,15 @@
   }
 }
 ```
 
 #### main.py
 
 ```python
-from src.jsonpython import *
+from jsonpython import *
 
 jobj = get_json_object("data.json")
 
 print(jobj['name'])  # Alex
 print(jobj['car']['model'])  # Tesla X
```

### Comparing `jsonpython-0.0.5/setup.py` & `jsonpython-0.0.6/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 with open("README.md", "r") as readme_file:
     readme = readme_file.read()
 
 requirements = []
 
 setup(
     name="jsonpython",
-    version="0.0.5",
+    version="0.0.6",
     author="TAFH-debug",
     author_email="aushahman2007@gmail.com",
     description="A package to deserialize and serialize json files.",
     long_description=readme,
     long_description_content_type="text/markdown",
     url="https://github.com/TAFH-debug/jsonpy",
     packages=["jsonpython"],
```

### Comparing `jsonpython-0.0.5/src/jsonpython/json.py` & `jsonpython-0.0.6/src/jsonpython/json.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,10 +1,27 @@
 from .json_core import *
 
 
+def get_json_object(path: str):
+    """
+    Parameters
+    -------------
+    path: :class 'str':
+        Path to file.
+
+    Returns
+    -------------
+    :class cls:
+        Dict that contains data from file.
+    """
+
+    with open(path, "r") as f:
+        return parse(f.read())
+
+
 def from_file(cls: type, path: str):
     """
     Parameters
     -------------
     cls: :class 'type':
         Class of object.
     path: :class 'str':
```

### Comparing `jsonpython-0.0.5/src/jsonpython/json_core.py` & `jsonpython-0.0.6/src/jsonpython/json_core.py`

 * *Files identical despite different names*

### Comparing `jsonpython-0.0.5/src/jsonpython/parser.py` & `jsonpython-0.0.6/src/jsonpython/parser.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 CLOSING_TOKENS = [",", "}", "]"]
 
+
 class JsonParseError(Exception):
     pass
 
 
 class Tokenizer:
 
     def __init__(self, line: str):
```

### Comparing `jsonpython-0.0.5/src/jsonpython.egg-info/PKG-INFO` & `jsonpython-0.0.6/src/jsonpython.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 Metadata-Version: 2.1
 Name: jsonpython
-Version: 0.0.5
+Version: 0.0.6
 Summary: A package to deserialize and serialize json files.
 Home-page: https://github.com/TAFH-debug/jsonpy
 Author: TAFH-debug
 Author-email: aushahman2007@gmail.com
 License: LICENSE
+Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Jsonpython
@@ -37,15 +38,15 @@
   }
 }
 ```
 
 #### main.py
 
 ```python
-from src.jsonpython import *
+from jsonpython import *
 
 jobj = get_json_object("data.json")
 
 print(jobj['name'])  # Alex
 print(jobj['car']['model'])  # Tesla X
 
 
@@ -65,7 +66,8 @@
     car: Car
 
 
 person = get_class(Person, "data.json")
 
 print(person.car.model)  # Tesla X
 ```
+
```

