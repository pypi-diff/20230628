# Comparing `tmp/markdown-up-1.4.8.tar.gz` & `tmp/markdown-up-1.4.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "markdown-up-1.4.8.tar", last modified: Mon Jul 25 15:41:33 2022, max compression
+gzip compressed data, was "markdown-up-1.4.9.tar", last modified: Thu Aug 18 17:43:29 2022, max compression
```

## Comparing `markdown-up-1.4.8.tar` & `markdown-up-1.4.9.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-07-25 15:41:33.383544 markdown-up-1.4.8/
--rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2022-05-18 22:03:13.000000 markdown-up-1.4.8/LICENSE
--rw-r--r--   0 craighobbs   (501) staff       (20)     2109 2022-07-25 15:41:33.383428 markdown-up-1.4.8/PKG-INFO
--rw-r--r--   0 craighobbs   (501) staff       (20)     1311 2022-07-22 20:01:01.000000 markdown-up-1.4.8/README.md
--rw-r--r--   0 craighobbs   (501) staff       (20)       38 2022-07-25 15:41:33.383584 markdown-up-1.4.8/setup.cfg
--rw-r--r--   0 craighobbs   (501) staff       (20)     1668 2022-07-25 15:39:38.000000 markdown-up-1.4.8/setup.py
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-07-25 15:41:33.381609 markdown-up-1.4.8/src/
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-07-25 15:41:33.382598 markdown-up-1.4.8/src/markdown_up/
--rw-r--r--   0 craighobbs   (501) staff       (20)       99 2022-05-18 22:03:13.000000 markdown-up-1.4.8/src/markdown_up/__init__.py
--rw-r--r--   0 craighobbs   (501) staff       (20)      232 2022-05-18 22:03:13.000000 markdown-up-1.4.8/src/markdown_up/__main__.py
--rw-r--r--   0 craighobbs   (501) staff       (20)     5343 2022-07-25 15:19:33.000000 markdown-up-1.4.8/src/markdown_up/app.py
--rw-r--r--   0 craighobbs   (501) staff       (20)     1860 2022-05-18 22:03:13.000000 markdown-up-1.4.8/src/markdown_up/main.py
-drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-07-25 15:41:33.383276 markdown-up-1.4.8/src/markdown_up.egg-info/
--rw-r--r--   0 craighobbs   (501) staff       (20)     2109 2022-07-25 15:41:33.000000 markdown-up-1.4.8/src/markdown_up.egg-info/PKG-INFO
--rw-r--r--   0 craighobbs   (501) staff       (20)      365 2022-07-25 15:41:33.000000 markdown-up-1.4.8/src/markdown_up.egg-info/SOURCES.txt
--rw-r--r--   0 craighobbs   (501) staff       (20)        1 2022-07-25 15:41:33.000000 markdown-up-1.4.8/src/markdown_up.egg-info/dependency_links.txt
--rw-r--r--   0 craighobbs   (501) staff       (20)       54 2022-07-25 15:41:33.000000 markdown-up-1.4.8/src/markdown_up.egg-info/entry_points.txt
--rw-r--r--   0 craighobbs   (501) staff       (20)       12 2022-07-25 15:41:33.000000 markdown-up-1.4.8/src/markdown_up.egg-info/requires.txt
--rw-r--r--   0 craighobbs   (501) staff       (20)       12 2022-07-25 15:41:33.000000 markdown-up-1.4.8/src/markdown_up.egg-info/top_level.txt
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-08-18 17:43:29.818090 markdown-up-1.4.9/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2022-07-28 23:02:23.000000 markdown-up-1.4.9/LICENSE
+-rw-r--r--   0 craighobbs   (501) staff       (20)     2109 2022-08-18 17:43:29.817986 markdown-up-1.4.9/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1311 2022-07-28 23:02:23.000000 markdown-up-1.4.9/README.md
+-rw-r--r--   0 craighobbs   (501) staff       (20)       38 2022-08-18 17:43:29.818128 markdown-up-1.4.9/setup.cfg
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1668 2022-08-18 17:41:19.000000 markdown-up-1.4.9/setup.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-08-18 17:43:29.816496 markdown-up-1.4.9/src/
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-08-18 17:43:29.817217 markdown-up-1.4.9/src/markdown_up/
+-rw-r--r--   0 craighobbs   (501) staff       (20)       99 2022-07-28 23:02:23.000000 markdown-up-1.4.9/src/markdown_up/__init__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)      245 2022-07-28 23:02:23.000000 markdown-up-1.4.9/src/markdown_up/__main__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     5242 2022-08-18 17:21:07.000000 markdown-up-1.4.9/src/markdown_up/app.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1865 2022-07-28 23:02:23.000000 markdown-up-1.4.9/src/markdown_up/main.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2022-08-18 17:43:29.817842 markdown-up-1.4.9/src/markdown_up.egg-info/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     2109 2022-08-18 17:43:29.000000 markdown-up-1.4.9/src/markdown_up.egg-info/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)      365 2022-08-18 17:43:29.000000 markdown-up-1.4.9/src/markdown_up.egg-info/SOURCES.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        1 2022-08-18 17:43:29.000000 markdown-up-1.4.9/src/markdown_up.egg-info/dependency_links.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       54 2022-08-18 17:43:29.000000 markdown-up-1.4.9/src/markdown_up.egg-info/entry_points.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       12 2022-08-18 17:43:29.000000 markdown-up-1.4.9/src/markdown_up.egg-info/requires.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       12 2022-08-18 17:43:29.000000 markdown-up-1.4.9/src/markdown_up.egg-info/top_level.txt
```

### Comparing `markdown-up-1.4.8/LICENSE` & `markdown-up-1.4.9/LICENSE`

 * *Files identical despite different names*

### Comparing `markdown-up-1.4.8/PKG-INFO` & `markdown-up-1.4.9/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: markdown-up
-Version: 1.4.8
+Version: 1.4.9
 Summary: The MarkdownUp launcher
 Home-page: https://github.com/craigahobbs/markdown-up-py
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: MarkdownUp,Markdown,viewer
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `markdown-up-1.4.8/README.md` & `markdown-up-1.4.9/README.md`

 * *Files identical despite different names*

### Comparing `markdown-up-1.4.8/setup.py` & `markdown-up-1.4.9/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 
     # Do the setup
     setup(
         name='markdown-up',
         description='The MarkdownUp launcher',
         long_description=long_description,
         long_description_content_type='text/markdown',
-        version='1.4.8',
+        version='1.4.9',
         author='Craig A. Hobbs',
         author_email='craigahobbs@gmail.com',
         keywords='MarkdownUp,Markdown,viewer',
         url='https://github.com/craigahobbs/markdown-up-py',
         license='MIT',
         classifiers=[
             'Development Status :: 5 - Production/Stable',
```

### Comparing `markdown-up-1.4.8/src/markdown_up/app.py` & `markdown-up-1.4.9/src/markdown_up/app.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # Licensed under the MIT License
 # https://github.com/craigahobbs/markdown-up-py/blob/main/LICENSE
 
 """
-The markdown-up back-end API WSGI application
+The MarkdownUp launcher back-end application
 """
 
 from http import HTTPStatus
 import os
 from pathlib import PurePosixPath
 
 import chisel
@@ -85,15 +85,14 @@
 <!DOCTYPE html>
 <html lang="en">
     <head>
         <title>MarkdownUp</title>
         <meta charset="UTF-8">
         <meta name="description" content="MarkdownUp is a Markdown viewer">
         <meta name="viewport" content="width=device-width, initial-scale=1">
-        <link rel="stylesheet" href="https://craigahobbs.github.io/markdown-up/markdown-model.css">
         <link rel="stylesheet" href="https://craigahobbs.github.io/markdown-up/app.css">
     </head>
     <body>
     </body>
     <script type="module">
         import {MarkdownUp} from 'https://craigahobbs.github.io/markdown-up/lib/app.js';
         const app = new MarkdownUp(window, {
```

### Comparing `markdown-up-1.4.8/src/markdown_up/main.py` & `markdown-up-1.4.9/src/markdown_up/main.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # Licensed under the MIT License
 # https://github.com/craigahobbs/markdown-up-py/blob/main/LICENSE
 
 """
-markdown-up command-line script main module
+The MarkdownUp launcher command-line application
 """
 
 import argparse
 import os
 import threading
 import webbrowser
 import wsgiref.simple_server
```

### Comparing `markdown-up-1.4.8/src/markdown_up.egg-info/PKG-INFO` & `markdown-up-1.4.9/src/markdown_up.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: markdown-up
-Version: 1.4.8
+Version: 1.4.9
 Summary: The MarkdownUp launcher
 Home-page: https://github.com/craigahobbs/markdown-up-py
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: MarkdownUp,Markdown,viewer
 Classifier: Development Status :: 5 - Production/Stable
```

