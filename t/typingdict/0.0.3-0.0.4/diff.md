# Comparing `tmp/typingdict-0.0.3.tar.gz` & `tmp/typingdict-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "typingdict-0.0.3.tar", last modified: Tue Jun 27 12:17:51 2023, max compression
+gzip compressed data, was "typingdict-0.0.4.tar", last modified: Wed Jun 28 03:44:57 2023, max compression
```

## Comparing `typingdict-0.0.3.tar` & `typingdict-0.0.4.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:17:51.424486 typingdict-0.0.3/
--rw-r--r--   0 runner    (1001) docker     (123)     1066 2023-06-27 12:17:38.000000 typingdict-0.0.3/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-27 12:17:51.424486 typingdict-0.0.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      494 2023-06-27 12:17:38.000000 typingdict-0.0.3/README.rst
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 12:17:51.424486 typingdict-0.0.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      648 2023-06-27 12:17:38.000000 typingdict-0.0.3/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:17:51.424486 typingdict-0.0.3/typingdict/
--rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-27 12:17:38.000000 typingdict-0.0.3/typingdict/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-27 12:17:38.000000 typingdict-0.0.3/typingdict/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-27 12:17:38.000000 typingdict-0.0.3/typingdict/beautifier.py
--rw-r--r--   0 runner    (1001) docker     (123)     4086 2023-06-27 12:17:38.000000 typingdict-0.0.3/typingdict/typer.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:17:51.424486 typingdict-0.0.3/typingdict.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-27 12:17:51.000000 typingdict-0.0.3/typingdict.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-27 12:17:51.000000 typingdict-0.0.3/typingdict.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 12:17:51.000000 typingdict-0.0.3/typingdict.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-27 12:17:51.000000 typingdict-0.0.3/typingdict.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:44:57.869935 typingdict-0.0.4/
+-rw-r--r--   0 runner    (1001) docker     (123)     1066 2023-06-28 03:44:50.000000 typingdict-0.0.4/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-28 03:44:57.869935 typingdict-0.0.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      494 2023-06-28 03:44:50.000000 typingdict-0.0.4/README.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 03:44:57.869935 typingdict-0.0.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      648 2023-06-28 03:44:50.000000 typingdict-0.0.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:44:57.869935 typingdict-0.0.4/typingdict/
+-rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-28 03:44:50.000000 typingdict-0.0.4/typingdict/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 03:44:50.000000 typingdict-0.0.4/typingdict/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 03:44:50.000000 typingdict-0.0.4/typingdict/beautifier.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4113 2023-06-28 03:44:50.000000 typingdict-0.0.4/typingdict/typer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:44:57.869935 typingdict-0.0.4/typingdict.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-28 03:44:57.000000 typingdict-0.0.4/typingdict.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 03:44:57.000000 typingdict-0.0.4/typingdict.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 03:44:57.000000 typingdict-0.0.4/typingdict.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-28 03:44:57.000000 typingdict-0.0.4/typingdict.egg-info/top_level.txt
```

### Comparing `typingdict-0.0.3/LICENSE` & `typingdict-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `typingdict-0.0.3/PKG-INFO` & `typingdict-0.0.4/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: typingdict
-Version: 0.0.3
+Version: 0.0.4
 Summary: Generate TypedDict Automatically
 Home-page: https://github.com/am230/typingdict
 Author: am230
 License: MIT Licence
 Keywords: Automation,Typing
 Platform: any
 Requires: strinpy
```

### Comparing `typingdict-0.0.3/setup.py` & `typingdict-0.0.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 
 author = 'am230'
 name = 'typingdict'
 py_modules = [name]
 
 setup(
     name=name,
-    version='0.0.3',
+    version='0.0.4',
     keywords=["Automation", "Typing"],
     description="Generate TypedDict Automatically",
     long_description=long_description,
     license="MIT Licence",
     long_description_content_type='text/x-rst',
     packages=find_packages(),
     requires=['strinpy', 'astor'],
```

### Comparing `typingdict-0.0.3/typingdict/typer.py` & `typingdict-0.0.4/typingdict/typer.py`

 * *Files 2% similar despite different names*

```diff
@@ -56,19 +56,20 @@
             if not v.values():
                 return 'Dict'
             attrs = {k: self._typerify(k, v) for k, v in v.items()}
             exist, name = self.is_exists(key, attrs)
             if exist:
                 return name
             if any(self.is_invalid_name(k) for k in v.keys()):
-                self.parts.append(strinpy.build([name, ' = TypedDict("', key, '", {', ', '.join(f'"{k}": "{v}"' for k, v in attrs.items()), '})']))
+                self.parts.append(strinpy.build([name, ' = TypedDict("', key, '", {', ', '.join(f'"{k}": "{v}"' for k, v in attrs.items()), '})', '\n']))
                 return name
             self.parts.append([
                 f'class {name}(TypedDict):\n',
                 [[f'    {k}:"{v}"\n'] for k, v in attrs.items()],
+                '\n'
             ])
             return name
         elif isinstance(v, list):
             types = list(set(self._typerify(f'{key}_item', v) for v in v))
             if types:
                 parts = []
                 optional = 'None' in types
```

### Comparing `typingdict-0.0.3/typingdict.egg-info/PKG-INFO` & `typingdict-0.0.4/typingdict.egg-info/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: typingdict
-Version: 0.0.3
+Version: 0.0.4
 Summary: Generate TypedDict Automatically
 Home-page: https://github.com/am230/typingdict
 Author: am230
 License: MIT Licence
 Keywords: Automation,Typing
 Platform: any
 Requires: strinpy
```

