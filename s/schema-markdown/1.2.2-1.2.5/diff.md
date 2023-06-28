# Comparing `tmp/schema-markdown-1.2.2.tar.gz` & `tmp/schema-markdown-1.2.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "schema-markdown-1.2.2.tar", last modified: Mon Oct 31 17:05:36 2022, max compression
+gzip compressed data, was "schema-markdown-1.2.5.tar", last modified: Wed Jun 28 14:19:13 2023, max compression
```

## Comparing `schema-markdown-1.2.2.tar` & `schema-markdown-1.2.5.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:05:36.166370 schema-markdown-1.2.2/
--rw-r--r--   0       20 dialout     (20)     1081 2022-10-27 21:45:05.000000 schema-markdown-1.2.2/LICENSE
--rw-r--r--   0       20 dialout     (20)     4672 2022-10-31 17:05:36.166999 schema-markdown-1.2.2/PKG-INFO
--rw-r--r--   0       20 dialout     (20)     3896 2022-10-30 14:26:44.000000 schema-markdown-1.2.2/README.rst
--rw-r--r--   0       20 dialout     (20)       50 2022-10-30 14:16:49.000000 schema-markdown-1.2.2/pyproject.toml
--rw-r--r--   0       20 dialout     (20)      789 2022-10-31 17:05:36.168547 schema-markdown-1.2.2/setup.cfg
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:05:36.151735 schema-markdown-1.2.2/src/
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:05:36.162300 schema-markdown-1.2.2/src/schema_markdown/
--rw-r--r--   0       20 dialout     (20)      578 2022-10-27 21:45:05.000000 schema-markdown-1.2.2/src/schema_markdown/__init__.py
--rw-r--r--   0       20 dialout     (20)     6222 2022-10-27 21:45:05.000000 schema-markdown-1.2.2/src/schema_markdown/encode.py
--rw-r--r--   0       20 dialout     (20)    18504 2022-10-30 14:46:39.000000 schema-markdown-1.2.2/src/schema_markdown/parser.py
--rw-r--r--   0       20 dialout     (20)    19055 2022-10-27 21:45:05.000000 schema-markdown-1.2.2/src/schema_markdown/schema.py
--rw-r--r--   0       20 dialout     (20)    11083 2022-10-27 21:45:05.000000 schema-markdown-1.2.2/src/schema_markdown/schema_util.py
--rw-r--r--   0       20 dialout     (20)     4370 2022-10-27 21:45:05.000000 schema-markdown-1.2.2/src/schema_markdown/type_model.py
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:05:36.165658 schema-markdown-1.2.2/src/schema_markdown.egg-info/
--rw-r--r--   0       20 dialout     (20)     4672 2022-10-31 17:05:36.000000 schema-markdown-1.2.2/src/schema_markdown.egg-info/PKG-INFO
--rw-r--r--   0       20 dialout     (20)      406 2022-10-31 17:05:36.000000 schema-markdown-1.2.2/src/schema_markdown.egg-info/SOURCES.txt
--rw-r--r--   0       20 dialout     (20)        1 2022-10-31 17:05:36.000000 schema-markdown-1.2.2/src/schema_markdown.egg-info/dependency_links.txt
--rw-r--r--   0       20 dialout     (20)       16 2022-10-31 17:05:36.000000 schema-markdown-1.2.2/src/schema_markdown.egg-info/top_level.txt
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.270474 schema-markdown-1.2.5/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/LICENSE
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4709 2023-06-28 14:19:13.270709 schema-markdown-1.2.5/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)     3895 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/README.rst
+-rw-r--r--   0 craighobbs   (501) staff       (20)       50 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/pyproject.toml
+-rw-r--r--   0 craighobbs   (501) staff       (20)      833 2023-06-28 14:19:13.270923 schema-markdown-1.2.5/setup.cfg
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.268866 schema-markdown-1.2.5/src/
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.269971 schema-markdown-1.2.5/src/schema_markdown/
+-rw-r--r--   0 craighobbs   (501) staff       (20)      578 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/__init__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     6222 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/encode.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    18551 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/parser.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    19055 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/schema.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    11083 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/schema_util.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4370 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/type_model.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.270385 schema-markdown-1.2.5/src/schema_markdown.egg-info/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4709 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)      406 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/SOURCES.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        1 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/dependency_links.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       16 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/top_level.txt
```

### Comparing `schema-markdown-1.2.2/LICENSE` & `schema-markdown-1.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.2/PKG-INFO` & `schema-markdown-1.2.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,26 +1,27 @@
 Metadata-Version: 2.1
 Name: schema-markdown
-Version: 1.2.2
+Version: 1.2.5
 Summary: A schema definition and validation library
 Home-page: https://github.com/craigahobbs/schema-markdown
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: schema,validate,json
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Utilities
+Description-Content-Type: text/x-rst
 License-File: LICENSE
 
 schema-markdown
 ===============
 
 .. |badge-status| image:: https://img.shields.io/pypi/status/schema-markdown
    :alt: PyPI - Status
@@ -36,15 +37,14 @@
 
 .. |badge-python| image:: https://img.shields.io/pypi/pyversions/schema-markdown
    :alt: PyPI - Python Version
    :target: https://www.python.org/downloads/
 
 |badge-status| |badge-version| |badge-license| |badge-python|
 
-
 schema-markdown is a schema definition and validation library.
 
 
 Links
 -----
 
 - `The Schema Markdown Language <https://craigahobbs.github.io/schema-markdown-js/language/>`__
```

### Comparing `schema-markdown-1.2.2/README.rst` & `schema-markdown-1.2.5/README.rst`

 * *Files 1% similar despite different names*

```diff
@@ -15,15 +15,14 @@
 
 .. |badge-python| image:: https://img.shields.io/pypi/pyversions/schema-markdown
    :alt: PyPI - Python Version
    :target: https://www.python.org/downloads/
 
 |badge-status| |badge-version| |badge-license| |badge-python|
 
-
 schema-markdown is a schema definition and validation library.
 
 
 Links
 -----
 
 - `The Schema Markdown Language <https://craigahobbs.github.io/schema-markdown-js/language/>`__
```

### Comparing `schema-markdown-1.2.2/setup.cfg` & `schema-markdown-1.2.5/setup.cfg`

 * *Files 10% similar despite different names*

```diff
@@ -1,27 +1,28 @@
 [metadata]
 name = schema-markdown
-version = 1.2.2
+version = 1.2.5
 url = https://github.com/craigahobbs/schema-markdown
 author = Craig A. Hobbs
 author_email = craigahobbs@gmail.com
 license = MIT
 description = A schema definition and validation library
 long_description = file:README.rst
+long_description_content_type = text/x-rst
 keywords = schema, validate, json
 classifiers = 
 	Development Status :: 5 - Production/Stable
 	Intended Audience :: Developers
 	License :: OSI Approved :: MIT License
 	Operating System :: OS Independent
-	Programming Language :: Python :: 3.7
 	Programming Language :: Python :: 3.8
 	Programming Language :: Python :: 3.9
 	Programming Language :: Python :: 3.10
 	Programming Language :: Python :: 3.11
+	Programming Language :: Python :: 3.12
 	Topic :: Utilities
 
 [options]
 packages = schema_markdown
 package_dir = 
 	= src
```

### Comparing `schema-markdown-1.2.2/src/schema_markdown/__init__.py` & `schema-markdown-1.2.5/src/schema_markdown/__init__.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.2/src/schema_markdown/encode.py` & `schema-markdown-1.2.5/src/schema_markdown/encode.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.2/src/schema_markdown/parser.py` & `schema-markdown-1.2.5/src/schema_markdown/parser.py`

 * *Files 2% similar despite different names*

```diff
@@ -321,15 +321,16 @@
             if method != '*':
                 action_url['method'] = method
             if path is not None:
                 action_url['path'] = path
 
             # Duplicate URL?
             if action_url in urls:
-                add_error(f'Duplicate URL: {method} {"" if path is None else path}', filename, linenum)
+                padded_path = "" if path is None else f' {path}'
+                add_error(f'Duplicate URL: {method}{padded_path}', filename, linenum)
 
             # Add the URL
             if 'urls' not in action:
                 action['urls'] = urls
             urls.append(action_url)
 
         # Typedef?
```

### Comparing `schema-markdown-1.2.2/src/schema_markdown/schema.py` & `schema-markdown-1.2.5/src/schema_markdown/schema.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.2/src/schema_markdown/schema_util.py` & `schema-markdown-1.2.5/src/schema_markdown/schema_util.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.2/src/schema_markdown/type_model.py` & `schema-markdown-1.2.5/src/schema_markdown/type_model.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.2/src/schema_markdown.egg-info/PKG-INFO` & `schema-markdown-1.2.5/src/schema_markdown.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,26 +1,27 @@
 Metadata-Version: 2.1
 Name: schema-markdown
-Version: 1.2.2
+Version: 1.2.5
 Summary: A schema definition and validation library
 Home-page: https://github.com/craigahobbs/schema-markdown
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: schema,validate,json
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Utilities
+Description-Content-Type: text/x-rst
 License-File: LICENSE
 
 schema-markdown
 ===============
 
 .. |badge-status| image:: https://img.shields.io/pypi/status/schema-markdown
    :alt: PyPI - Status
@@ -36,15 +37,14 @@
 
 .. |badge-python| image:: https://img.shields.io/pypi/pyversions/schema-markdown
    :alt: PyPI - Python Version
    :target: https://www.python.org/downloads/
 
 |badge-status| |badge-version| |badge-license| |badge-python|
 
-
 schema-markdown is a schema definition and validation library.
 
 
 Links
 -----
 
 - `The Schema Markdown Language <https://craigahobbs.github.io/schema-markdown-js/language/>`__
```

