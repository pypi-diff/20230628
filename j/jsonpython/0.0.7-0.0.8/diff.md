# Comparing `tmp/jsonpython-0.0.7.tar.gz` & `tmp/jsonpython-0.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jsonpython-0.0.7.tar", last modified: Wed Jun 28 07:11:09 2023, max compression
+gzip compressed data, was "jsonpython-0.0.8.tar", last modified: Wed Jun 28 07:15:49 2023, max compression
```

## Comparing `jsonpython-0.0.7.tar` & `jsonpython-0.0.8.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 07:11:09.166713 jsonpython-0.0.7/
--rw-rw-rw-   0        0        0     1061 2022-06-02 07:30:01.000000 jsonpython-0.0.7/LICENSE
--rw-rw-rw-   0        0        0     1216 2023-06-28 07:11:09.166713 jsonpython-0.0.7/PKG-INFO
--rw-rw-rw-   0        0        0      734 2023-06-28 07:07:03.000000 jsonpython-0.0.7/README.md
--rw-rw-rw-   0        0        0       86 2022-06-02 07:51:40.000000 jsonpython-0.0.7/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-28 07:11:09.167714 jsonpython-0.0.7/setup.cfg
--rw-rw-rw-   0        0        0      768 2023-06-28 07:07:35.000000 jsonpython-0.0.7/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 07:11:09.145330 jsonpython-0.0.7/src/
-drwxrwxrwx   0        0        0        0 2023-06-28 07:11:09.156562 jsonpython-0.0.7/src/jsonpython/
--rw-rw-rw-   0        0        0      180 2022-06-02 17:35:37.000000 jsonpython-0.0.7/src/jsonpython/__init__.py
--rw-rw-rw-   0        0        0      962 2023-06-28 07:01:29.000000 jsonpython-0.0.7/src/jsonpython/json.py
--rw-rw-rw-   0        0        0      938 2022-06-02 17:34:17.000000 jsonpython-0.0.7/src/jsonpython/json_core.py
--rw-rw-rw-   0        0        0     3170 2023-06-28 06:54:16.000000 jsonpython-0.0.7/src/jsonpython/parser.py
-drwxrwxrwx   0        0        0        0 2023-06-28 07:11:09.164561 jsonpython-0.0.7/src/jsonpython.egg-info/
--rw-rw-rw-   0        0        0     1216 2023-06-28 07:11:09.000000 jsonpython-0.0.7/src/jsonpython.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      296 2023-06-28 07:11:09.000000 jsonpython-0.0.7/src/jsonpython.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 07:11:09.000000 jsonpython-0.0.7/src/jsonpython.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       11 2023-06-28 07:11:09.000000 jsonpython-0.0.7/src/jsonpython.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 07:15:49.617891 jsonpython-0.0.8/
+-rw-rw-rw-   0        0        0     1061 2022-06-02 07:30:01.000000 jsonpython-0.0.8/LICENSE
+-rw-rw-rw-   0        0        0     1219 2023-06-28 07:15:49.617765 jsonpython-0.0.8/PKG-INFO
+-rw-rw-rw-   0        0        0      737 2023-06-28 07:15:02.000000 jsonpython-0.0.8/README.md
+-rw-rw-rw-   0        0        0       86 2022-06-02 07:51:40.000000 jsonpython-0.0.8/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 07:15:49.617891 jsonpython-0.0.8/setup.cfg
+-rw-rw-rw-   0        0        0      768 2023-06-28 07:15:36.000000 jsonpython-0.0.8/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:15:49.591480 jsonpython-0.0.8/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 07:15:49.601608 jsonpython-0.0.8/src/jsonpython/
+-rw-rw-rw-   0        0        0      180 2022-06-02 17:35:37.000000 jsonpython-0.0.8/src/jsonpython/__init__.py
+-rw-rw-rw-   0        0        0      962 2023-06-28 07:01:29.000000 jsonpython-0.0.8/src/jsonpython/json.py
+-rw-rw-rw-   0        0        0      938 2022-06-02 17:34:17.000000 jsonpython-0.0.8/src/jsonpython/json_core.py
+-rw-rw-rw-   0        0        0     3170 2023-06-28 06:54:16.000000 jsonpython-0.0.8/src/jsonpython/parser.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:15:49.615746 jsonpython-0.0.8/src/jsonpython.egg-info/
+-rw-rw-rw-   0        0        0     1219 2023-06-28 07:15:49.000000 jsonpython-0.0.8/src/jsonpython.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      296 2023-06-28 07:15:49.000000 jsonpython-0.0.8/src/jsonpython.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:15:49.000000 jsonpython-0.0.8/src/jsonpython.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 07:15:49.000000 jsonpython-0.0.8/src/jsonpython.egg-info/top_level.txt
```

### Comparing `jsonpython-0.0.7/LICENSE` & `jsonpython-0.0.8/LICENSE`

 * *Files identical despite different names*

### Comparing `jsonpython-0.0.7/PKG-INFO` & `jsonpython-0.0.8/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jsonpython
-Version: 0.0.7
+Version: 0.0.8
 Summary: A package to deserialize and serialize json files.
 Home-page: https://github.com/TAFH-debug/jsonpy
 Author: TAFH-debug
 Author-email: aushahman2007@gmail.com
 License: LICENSE
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
@@ -62,12 +62,12 @@
 
 class Person:
     age: int
     name: str
     car: Car
 
 
-person = to_cls(Person, "data.json")
+person = from_file(Person, "data.json")
 
 print(person.car.model)  # Tesla X
 ```
```

### Comparing `jsonpython-0.0.7/README.md` & `jsonpython-0.0.8/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -47,11 +47,11 @@
 
 class Person:
     age: int
     name: str
     car: Car
 
 
-person = to_cls(Person, "data.json")
+person = from_file(Person, "data.json")
 
 print(person.car.model)  # Tesla X
 ```
```

### Comparing `jsonpython-0.0.7/setup.py` & `jsonpython-0.0.8/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 with open("README.md", "r") as readme_file:
     readme = readme_file.read()
 
 requirements = []
 
 setup(
     name="jsonpython",
-    version="0.0.7",
+    version="0.0.8",
     author="TAFH-debug",
     author_email="aushahman2007@gmail.com",
     description="A package to deserialize and serialize json files.",
     long_description=readme,
     long_description_content_type="text/markdown",
     url="https://github.com/TAFH-debug/jsonpy",
     packages=["jsonpython"],
```

### Comparing `jsonpython-0.0.7/src/jsonpython/json.py` & `jsonpython-0.0.8/src/jsonpython/json.py`

 * *Files identical despite different names*

### Comparing `jsonpython-0.0.7/src/jsonpython/json_core.py` & `jsonpython-0.0.8/src/jsonpython/json_core.py`

 * *Files identical despite different names*

### Comparing `jsonpython-0.0.7/src/jsonpython/parser.py` & `jsonpython-0.0.8/src/jsonpython/parser.py`

 * *Files identical despite different names*

### Comparing `jsonpython-0.0.7/src/jsonpython.egg-info/PKG-INFO` & `jsonpython-0.0.8/src/jsonpython.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jsonpython
-Version: 0.0.7
+Version: 0.0.8
 Summary: A package to deserialize and serialize json files.
 Home-page: https://github.com/TAFH-debug/jsonpy
 Author: TAFH-debug
 Author-email: aushahman2007@gmail.com
 License: LICENSE
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
@@ -62,12 +62,12 @@
 
 class Person:
     age: int
     name: str
     car: Car
 
 
-person = to_cls(Person, "data.json")
+person = from_file(Person, "data.json")
 
 print(person.car.model)  # Tesla X
 ```
```

