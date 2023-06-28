# Comparing `tmp/pybythec-0.9.8.tar.gz` & `tmp/pybythec-0.9.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/pybythec-0.9.8.tar", last modified: Fri Oct  7 17:10:51 2016, max compression
+gzip compressed data, was "dist/pybythec-0.9.9.tar", last modified: Fri Oct  7 17:21:45 2016, max compression
```

## Comparing `pybythec-0.9.8.tar` & `pybythec-0.9.9.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:10:51.000000 pybythec-0.9.8/
--rwxr-xr-x   0 tom       (1000) tom       (1000)     1595 2016-10-07 17:10:48.000000 pybythec-0.9.8/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:10:51.000000 pybythec-0.9.8/test/
--rw-r--r--   0 tom       (1000) tom       (1000)     1648 2016-10-03 16:39:17.000000 pybythec-0.9.8/test/test_pybythec.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:10:51.000000 pybythec-0.9.8/pybythec.egg-info/
--rw-r--r--   0 tom       (1000) tom       (1000)        9 2016-10-07 17:10:51.000000 pybythec-0.9.8/pybythec.egg-info/top_level.txt
--rw-r--r--   0 tom       (1000) tom       (1000)      298 2016-10-07 17:10:51.000000 pybythec-0.9.8/pybythec.egg-info/SOURCES.txt
--rw-r--r--   0 tom       (1000) tom       (1000)     4277 2016-10-07 17:10:51.000000 pybythec-0.9.8/pybythec.egg-info/PKG-INFO
--rw-r--r--   0 tom       (1000) tom       (1000)        1 2016-10-07 17:10:51.000000 pybythec-0.9.8/pybythec.egg-info/dependency_links.txt
--rw-r--r--   0 tom       (1000) tom       (1000)     3230 2016-08-15 18:32:03.000000 pybythec-0.9.8/README.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:10:51.000000 pybythec-0.9.8/pybythec/
--rw-r--r--   0 tom       (1000) tom       (1000)     2162 2016-09-26 23:35:40.000000 pybythec-0.9.8/pybythec/BuildStatus.py
--rwxr-xr-x   0 tom       (1000) tom       (1000)    14144 2016-10-03 16:39:17.000000 pybythec-0.9.8/pybythec/main.py
--rwxr-xr-x   0 tom       (1000) tom       (1000)      341 2016-09-30 20:53:19.000000 pybythec-0.9.8/pybythec/__init__.py
--rw-r--r--   0 tom       (1000) tom       (1000)    16726 2016-10-07 16:58:23.000000 pybythec-0.9.8/pybythec/BuildElements.py
--rw-r--r--   0 tom       (1000) tom       (1000)     4666 2016-10-07 17:10:48.000000 pybythec-0.9.8/pybythec/utils.py
--rw-r--r--   0 root         (0) root         (0)     4277 2016-10-07 17:10:51.000000 pybythec-0.9.8/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      283 2016-10-07 17:10:51.000000 pybythec-0.9.8/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:10:51.000000 pybythec-0.9.8/bin/
--rwxr-xr-x   0 tom       (1000) tom       (1000)      174 2016-10-03 16:39:17.000000 pybythec-0.9.8/bin/pybythec
+drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:21:45.000000 pybythec-0.9.9/
+-rwxr-xr-x   0 tom       (1000) tom       (1000)     8003 2016-10-07 17:21:45.000000 pybythec-0.9.9/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:21:45.000000 pybythec-0.9.9/test/
+-rw-r--r--   0 tom       (1000) tom       (1000)     1648 2016-10-03 16:39:17.000000 pybythec-0.9.9/test/test_pybythec.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:21:45.000000 pybythec-0.9.9/pybythec.egg-info/
+-rw-r--r--   0 tom       (1000) tom       (1000)        9 2016-10-07 17:21:45.000000 pybythec-0.9.9/pybythec.egg-info/top_level.txt
+-rw-r--r--   0 tom       (1000) tom       (1000)      298 2016-10-07 17:21:45.000000 pybythec-0.9.9/pybythec.egg-info/SOURCES.txt
+-rw-r--r--   0 tom       (1000) tom       (1000)     4277 2016-10-07 17:21:45.000000 pybythec-0.9.9/pybythec.egg-info/PKG-INFO
+-rw-r--r--   0 tom       (1000) tom       (1000)        1 2016-10-07 17:21:45.000000 pybythec-0.9.9/pybythec.egg-info/dependency_links.txt
+-rw-r--r--   0 tom       (1000) tom       (1000)     3230 2016-08-15 18:32:03.000000 pybythec-0.9.9/README.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:21:45.000000 pybythec-0.9.9/pybythec/
+-rw-r--r--   0 tom       (1000) tom       (1000)     2162 2016-09-26 23:35:40.000000 pybythec-0.9.9/pybythec/BuildStatus.py
+-rwxr-xr-x   0 tom       (1000) tom       (1000)    14144 2016-10-03 16:39:17.000000 pybythec-0.9.9/pybythec/main.py
+-rwxr-xr-x   0 tom       (1000) tom       (1000)      341 2016-09-30 20:53:19.000000 pybythec-0.9.9/pybythec/__init__.py
+-rw-r--r--   0 tom       (1000) tom       (1000)    16726 2016-10-07 16:58:23.000000 pybythec-0.9.9/pybythec/BuildElements.py
+-rw-r--r--   0 tom       (1000) tom       (1000)     4666 2016-10-07 17:21:45.000000 pybythec-0.9.9/pybythec/utils.py
+-rw-r--r--   0 root         (0) root         (0)     4277 2016-10-07 17:21:45.000000 pybythec-0.9.9/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      283 2016-10-07 17:21:45.000000 pybythec-0.9.9/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2016-10-07 17:21:45.000000 pybythec-0.9.9/bin/
+-rwxr-xr-x   0 tom       (1000) tom       (1000)      174 2016-10-03 16:39:17.000000 pybythec-0.9.9/bin/pybythec
```

### Comparing `pybythec-0.9.8/test/test_pybythec.py` & `pybythec-0.9.9/test/test_pybythec.py`

 * *Files identical despite different names*

### Comparing `pybythec-0.9.8/pybythec.egg-info/PKG-INFO` & `pybythec-0.9.9/pybythec.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.0
 Name: pybythec
-Version: 0.9.8
+Version: 0.9.9
 Summary: A lightweight cross-platform build system for c/c++, written in python
 Home-page: https://github.com/glowtree/pybythec
 Author: glowtree
 Author-email: tom@glowtree.com
 License: LICENSE
 Description: ===============================
         pybythec
```

### Comparing `pybythec-0.9.8/README.rst` & `pybythec-0.9.9/README.rst`

 * *Files identical despite different names*

### Comparing `pybythec-0.9.8/pybythec/BuildStatus.py` & `pybythec-0.9.9/pybythec/BuildStatus.py`

 * *Files identical despite different names*

### Comparing `pybythec-0.9.8/pybythec/main.py` & `pybythec-0.9.9/pybythec/main.py`

 * *Files identical despite different names*

### Comparing `pybythec-0.9.8/pybythec/BuildElements.py` & `pybythec-0.9.9/pybythec/BuildElements.py`

 * *Files identical despite different names*

### Comparing `pybythec-0.9.8/pybythec/utils.py` & `pybythec-0.9.9/pybythec/utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 import json
 import shutil
 import logging
 import subprocess
 
 __author__ = 'glowtree'
 __email__ = 'tom@glowtree.com'
-__version__ = '0.9.8'
+__version__ = '0.9.9'
 
 log = logging.getLogger('pybythec')
 
 
 def srcNewer(srcPath, dstPath):
   if int(os.stat(srcPath).st_mtime) > int(os.stat(dstPath).st_mtime):
     return True
```

### Comparing `pybythec-0.9.8/PKG-INFO` & `pybythec-0.9.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.0
 Name: pybythec
-Version: 0.9.8
+Version: 0.9.9
 Summary: A lightweight cross-platform build system for c/c++, written in python
 Home-page: https://github.com/glowtree/pybythec
 Author: glowtree
 Author-email: tom@glowtree.com
 License: LICENSE
 Description: ===============================
         pybythec
```

