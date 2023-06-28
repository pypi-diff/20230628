# Comparing `tmp/schema-markdown-1.2.5.tar.gz` & `tmp/schema-markdown-1.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "schema-markdown-1.2.5.tar", last modified: Wed Jun 28 14:19:13 2023, max compression
+gzip compressed data, was "schema-markdown-1.2.6.tar", last modified: Wed Jun 28 14:43:46 2023, max compression
```

## Comparing `schema-markdown-1.2.5.tar` & `schema-markdown-1.2.6.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.270474 schema-markdown-1.2.5/
--rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/LICENSE
--rw-r--r--   0 craighobbs   (501) staff       (20)     4709 2023-06-28 14:19:13.270709 schema-markdown-1.2.5/PKG-INFO
--rw-r--r--   0 craighobbs   (501) staff       (20)     3895 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/README.rst
--rw-r--r--   0 craighobbs   (501) staff       (20)       50 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/pyproject.toml
--rw-r--r--   0 craighobbs   (501) staff       (20)      833 2023-06-28 14:19:13.270923 schema-markdown-1.2.5/setup.cfg
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.268866 schema-markdown-1.2.5/src/
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.269971 schema-markdown-1.2.5/src/schema_markdown/
--rw-r--r--   0 craighobbs   (501) staff       (20)      578 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/__init__.py
--rw-r--r--   0 craighobbs   (501) staff       (20)     6222 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/encode.py
--rw-r--r--   0 craighobbs   (501) staff       (20)    18551 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/parser.py
--rw-r--r--   0 craighobbs   (501) staff       (20)    19055 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/schema.py
--rw-r--r--   0 craighobbs   (501) staff       (20)    11083 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/schema_util.py
--rw-r--r--   0 craighobbs   (501) staff       (20)     4370 2023-06-11 21:05:18.000000 schema-markdown-1.2.5/src/schema_markdown/type_model.py
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:19:13.270385 schema-markdown-1.2.5/src/schema_markdown.egg-info/
--rw-r--r--   0 craighobbs   (501) staff       (20)     4709 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/PKG-INFO
--rw-r--r--   0 craighobbs   (501) staff       (20)      406 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/SOURCES.txt
--rw-r--r--   0 craighobbs   (501) staff       (20)        1 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/dependency_links.txt
--rw-r--r--   0 craighobbs   (501) staff       (20)       16 2023-06-28 14:19:13.000000 schema-markdown-1.2.5/src/schema_markdown.egg-info/top_level.txt
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:43:46.566714 schema-markdown-1.2.6/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/LICENSE
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4709 2023-06-28 14:43:46.566763 schema-markdown-1.2.6/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)     3895 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/README.rst
+-rw-r--r--   0 craighobbs   (501) staff       (20)       50 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/pyproject.toml
+-rw-r--r--   0 craighobbs   (501) staff       (20)      833 2023-06-28 14:43:46.566977 schema-markdown-1.2.6/setup.cfg
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:43:46.565076 schema-markdown-1.2.6/src/
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:43:46.566200 schema-markdown-1.2.6/src/schema_markdown/
+-rw-r--r--   0 craighobbs   (501) staff       (20)      578 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/src/schema_markdown/__init__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     6222 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/src/schema_markdown/encode.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    18551 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/src/schema_markdown/parser.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    19055 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/src/schema_markdown/schema.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    11083 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/src/schema_markdown/schema_util.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4370 2023-06-28 14:21:25.000000 schema-markdown-1.2.6/src/schema_markdown/type_model.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:43:46.566623 schema-markdown-1.2.6/src/schema_markdown.egg-info/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     4709 2023-06-28 14:43:46.000000 schema-markdown-1.2.6/src/schema_markdown.egg-info/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)      406 2023-06-28 14:43:46.000000 schema-markdown-1.2.6/src/schema_markdown.egg-info/SOURCES.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        1 2023-06-28 14:43:46.000000 schema-markdown-1.2.6/src/schema_markdown.egg-info/dependency_links.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       16 2023-06-28 14:43:46.000000 schema-markdown-1.2.6/src/schema_markdown.egg-info/top_level.txt
```

### Comparing `schema-markdown-1.2.5/LICENSE` & `schema-markdown-1.2.6/LICENSE`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/PKG-INFO` & `schema-markdown-1.2.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: schema-markdown
-Version: 1.2.5
+Version: 1.2.6
 Summary: A schema definition and validation library
 Home-page: https://github.com/craigahobbs/schema-markdown
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: schema,validate,json
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `schema-markdown-1.2.5/README.rst` & `schema-markdown-1.2.6/README.rst`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/setup.cfg` & `schema-markdown-1.2.6/setup.cfg`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = schema-markdown
-version = 1.2.5
+version = 1.2.6
 url = https://github.com/craigahobbs/schema-markdown
 author = Craig A. Hobbs
 author_email = craigahobbs@gmail.com
 license = MIT
 description = A schema definition and validation library
 long_description = file:README.rst
 long_description_content_type = text/x-rst
```

### Comparing `schema-markdown-1.2.5/src/schema_markdown/__init__.py` & `schema-markdown-1.2.6/src/schema_markdown/__init__.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/src/schema_markdown/encode.py` & `schema-markdown-1.2.6/src/schema_markdown/encode.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/src/schema_markdown/parser.py` & `schema-markdown-1.2.6/src/schema_markdown/parser.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/src/schema_markdown/schema.py` & `schema-markdown-1.2.6/src/schema_markdown/schema.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/src/schema_markdown/schema_util.py` & `schema-markdown-1.2.6/src/schema_markdown/schema_util.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/src/schema_markdown/type_model.py` & `schema-markdown-1.2.6/src/schema_markdown/type_model.py`

 * *Files identical despite different names*

### Comparing `schema-markdown-1.2.5/src/schema_markdown.egg-info/PKG-INFO` & `schema-markdown-1.2.6/src/schema_markdown.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: schema-markdown
-Version: 1.2.5
+Version: 1.2.6
 Summary: A schema definition and validation library
 Home-page: https://github.com/craigahobbs/schema-markdown
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: schema,validate,json
 Classifier: Development Status :: 5 - Production/Stable
```

