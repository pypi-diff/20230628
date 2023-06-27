# Comparing `tmp/pyintelx-0.1.2.tar.gz` & `tmp/pyintelx-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyintelx-0.1.2.tar", last modified: Tue Jun 27 21:56:34 2023, max compression
+gzip compressed data, was "pyintelx-0.1.3.tar", last modified: Tue Jun 27 22:01:22 2023, max compression
```

## Comparing `pyintelx-0.1.2.tar` & `pyintelx-0.1.3.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:56:34.077622 pyintelx-0.1.2/
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-27 21:56:24.000000 pyintelx-0.1.2/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-27 21:56:34.077622 pyintelx-0.1.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2031 2023-06-27 21:56:24.000000 pyintelx-0.1.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:56:34.073622 pyintelx-0.1.2/pyintelx/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:56:24.000000 pyintelx-0.1.2/pyintelx/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:56:34.077622 pyintelx-0.1.2/pyintelx/cli/
--rw-r--r--   0 runner    (1001) docker     (123)    10480 2023-06-27 21:56:24.000000 pyintelx-0.1.2/pyintelx/cli/pyintelx
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:56:34.077622 pyintelx-0.1.2/pyintelx.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-27 21:56:34.000000 pyintelx-0.1.2/pyintelx.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      201 2023-06-27 21:56:34.000000 pyintelx-0.1.2/pyintelx.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 21:56:34.000000 pyintelx-0.1.2/pyintelx.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-27 21:56:34.000000 pyintelx-0.1.2/pyintelx.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 21:56:34.077622 pyintelx-0.1.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-27 21:56:24.000000 pyintelx-0.1.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:01:22.495983 pyintelx-0.1.3/
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-27 22:01:12.000000 pyintelx-0.1.3/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-27 22:01:22.495983 pyintelx-0.1.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2031 2023-06-27 22:01:12.000000 pyintelx-0.1.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:01:22.495983 pyintelx-0.1.3/pyintelx/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 22:01:12.000000 pyintelx-0.1.3/pyintelx/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:01:22.495983 pyintelx-0.1.3/pyintelx/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)    10502 2023-06-27 22:01:12.000000 pyintelx-0.1.3/pyintelx/cli/pyintelx
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:01:22.495983 pyintelx-0.1.3/pyintelx.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-27 22:01:22.000000 pyintelx-0.1.3/pyintelx.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      201 2023-06-27 22:01:22.000000 pyintelx-0.1.3/pyintelx.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 22:01:22.000000 pyintelx-0.1.3/pyintelx.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-27 22:01:22.000000 pyintelx-0.1.3/pyintelx.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 22:01:22.495983 pyintelx-0.1.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-27 22:01:12.000000 pyintelx-0.1.3/setup.py
```

### Comparing `pyintelx-0.1.2/PKG-INFO` & `pyintelx-0.1.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyintelx
-Version: 0.1.2
+Version: 0.1.3
 Summary: This lib add support to use the Identity API from Intelx.io
 Home-page: https://github.com/csirtamericas/pyintelxio
 Author: Fermin Baudino, Einar Lanfranco, Federico Carrilao
 License: MIT
 Keywords: python, package, distribution
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Natural Language :: English
```

### Comparing `pyintelx-0.1.2/README.md` & `pyintelx-0.1.3/README.md`

 * *Files identical despite different names*

### Comparing `pyintelx-0.1.2/pyintelx/cli/pyintelx` & `pyintelx-0.1.3/pyintelx/cli/pyintelx`

 * *Files 0% similar despite different names*

```diff
@@ -4,15 +4,16 @@
 import os
 import sys
 import html
 import json
 import time
 import tabulate
 import argparse
-from pyintelx import intelx,IdentityService
+from pyintelx import IdentityService
+from intelxapi import intelx
 from termcolor import colored
 from pygments import highlight
 from pygments.lexers import JsonLexer
 from pygments.formatters import TerminalFormatter
 
 BOLD = '\033[1m'
 END = '\033[0m'
```

### Comparing `pyintelx-0.1.2/pyintelx.egg-info/PKG-INFO` & `pyintelx-0.1.3/pyintelx.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyintelx
-Version: 0.1.2
+Version: 0.1.3
 Summary: This lib add support to use the Identity API from Intelx.io
 Home-page: https://github.com/csirtamericas/pyintelxio
 Author: Fermin Baudino, Einar Lanfranco, Federico Carrilao
 License: MIT
 Keywords: python, package, distribution
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Natural Language :: English
```

### Comparing `pyintelx-0.1.2/setup.py` & `pyintelx-0.1.3/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
     
 
 setup(
     name='pyintelx',
-    version='0.1.2',
+    version='0.1.3',
     description='This lib add support to use the Identity API from Intelx.io',
     license='MIT',
     keywords=['python, package, distribution'],
     long_description=long_description,
     long_description_content_type="text/markdown",
     author='Fermin Baudino, Einar Lanfranco, Federico Carrilao',
     url='https://github.com/csirtamericas/pyintelxio',
```

