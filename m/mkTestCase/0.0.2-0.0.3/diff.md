# Comparing `tmp/mkTestCase-0.0.2.tar.gz` & `tmp/mkTestCase-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mkTestCase-0.0.2.tar", last modified: Wed Jun 28 07:23:35 2023, max compression
+gzip compressed data, was "mkTestCase-0.0.3.tar", last modified: Wed Jun 28 07:42:29 2023, max compression
```

## Comparing `mkTestCase-0.0.2.tar` & `mkTestCase-0.0.3.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.850034 mkTestCase-0.0.2/
--rw-r--r--   0 yangqing   (501) staff       (20)     1066 2023-03-03 07:16:54.000000 mkTestCase-0.0.2/LICENSE
--rw-r--r--   0 yangqing   (501) staff       (20)       40 2023-06-28 07:23:33.000000 mkTestCase-0.0.2/MANIFEST.in
--rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-28 07:23:35.849329 mkTestCase-0.0.2/PKG-INFO
--rw-r--r--   0 yangqing   (501) staff       (20)     1548 2023-06-05 08:46:44.000000 mkTestCase-0.0.2/README.md
-drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.842480 mkTestCase-0.0.2/mkTestCase/
--rw-r--r--   0 yangqing   (501) staff       (20)      141 2023-06-26 06:18:54.000000 mkTestCase-0.0.2/mkTestCase/__init__.py
--rw-r--r--   0 yangqing   (501) staff       (20)     2671 2023-06-28 07:19:56.000000 mkTestCase-0.0.2/mkTestCase/mkTestCase.py
-drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.846810 mkTestCase-0.0.2/mkTestCase/testcases/
--rw-r--r--   0 yangqing   (501) staff       (20)      979 2023-06-05 08:41:57.000000 mkTestCase-0.0.2/mkTestCase/testcases/form.yml
--rw-r--r--   0 yangqing   (501) staff       (20)      794 2023-03-03 08:28:51.000000 mkTestCase-0.0.2/mkTestCase/testcases/page.yml
-drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.845749 mkTestCase-0.0.2/mkTestCase.egg-info/
--rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/PKG-INFO
--rw-r--r--   0 yangqing   (501) staff       (20)      315 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/SOURCES.txt
--rw-r--r--   0 yangqing   (501) staff       (20)        1 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/dependency_links.txt
--rw-r--r--   0 yangqing   (501) staff       (20)        9 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/requires.txt
--rw-r--r--   0 yangqing   (501) staff       (20)       11 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/top_level.txt
--rw-r--r--   0 yangqing   (501) staff       (20)       38 2023-06-28 07:23:35.850200 mkTestCase-0.0.2/setup.cfg
--rw-r--r--   0 yangqing   (501) staff       (20)     1184 2023-06-28 07:19:56.000000 mkTestCase-0.0.2/setup.py
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:42:29.147699 mkTestCase-0.0.3/
+-rw-r--r--   0 yangqing   (501) staff       (20)     1066 2023-03-03 07:16:54.000000 mkTestCase-0.0.3/LICENSE
+-rw-r--r--   0 yangqing   (501) staff       (20)       40 2023-06-28 07:23:33.000000 mkTestCase-0.0.3/MANIFEST.in
+-rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-28 07:42:29.147250 mkTestCase-0.0.3/PKG-INFO
+-rw-r--r--   0 yangqing   (501) staff       (20)     1548 2023-06-05 08:46:44.000000 mkTestCase-0.0.3/README.md
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:42:29.143558 mkTestCase-0.0.3/mkTestCase/
+-rw-r--r--   0 yangqing   (501) staff       (20)      141 2023-06-26 06:18:54.000000 mkTestCase-0.0.3/mkTestCase/__init__.py
+-rw-r--r--   0 yangqing   (501) staff       (20)     2808 2023-06-28 07:40:07.000000 mkTestCase-0.0.3/mkTestCase/mkTestCase.py
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:42:29.146691 mkTestCase-0.0.3/mkTestCase/testcases/
+-rw-r--r--   0 yangqing   (501) staff       (20)      979 2023-06-05 08:41:57.000000 mkTestCase-0.0.3/mkTestCase/testcases/form.yml
+-rw-r--r--   0 yangqing   (501) staff       (20)      794 2023-03-03 08:28:51.000000 mkTestCase-0.0.3/mkTestCase/testcases/page.yml
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:42:29.145981 mkTestCase-0.0.3/mkTestCase.egg-info/
+-rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-28 07:42:29.000000 mkTestCase-0.0.3/mkTestCase.egg-info/PKG-INFO
+-rw-r--r--   0 yangqing   (501) staff       (20)      315 2023-06-28 07:42:29.000000 mkTestCase-0.0.3/mkTestCase.egg-info/SOURCES.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)        1 2023-06-28 07:42:29.000000 mkTestCase-0.0.3/mkTestCase.egg-info/dependency_links.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)        9 2023-06-28 07:42:29.000000 mkTestCase-0.0.3/mkTestCase.egg-info/requires.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)       11 2023-06-28 07:42:29.000000 mkTestCase-0.0.3/mkTestCase.egg-info/top_level.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)       38 2023-06-28 07:42:29.147845 mkTestCase-0.0.3/setup.cfg
+-rw-r--r--   0 yangqing   (501) staff       (20)     1184 2023-06-28 07:42:24.000000 mkTestCase-0.0.3/setup.py
```

### Comparing `mkTestCase-0.0.2/LICENSE` & `mkTestCase-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `mkTestCase-0.0.2/PKG-INFO` & `mkTestCase-0.0.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mkTestCase
-Version: 0.0.2
+Version: 0.0.3
 Summary: Write test cases like building blocks
 Home-page: https://github.com/yongchin0821/mkTestCase
 Author: Yongchin
 Author-email: yongchin39@qq.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/yongchin0821/mkTestCase/issues
 Keywords: testcase,automatically generate test cases,automated test
```

### Comparing `mkTestCase-0.0.2/README.md` & `mkTestCase-0.0.3/README.md`

 * *Files identical despite different names*

### Comparing `mkTestCase-0.0.2/mkTestCase/mkTestCase.py` & `mkTestCase-0.0.3/mkTestCase/mkTestCase.py`

 * *Files 10% similar despite different names*

```diff
@@ -3,24 +3,27 @@
 # @Time    : 2023/3/6 10:55 AM
 # @Author  : Yongchin
 
 import yaml
 import copy
 from openpyxl import Workbook
 import string
+import os
+
+BASE_DIR = os.path.dirname(os.path.abspath(__file__))
 
 
 class Factory:
     def __init__(self):
         self.m_count = 0
         self.model_index = []
         self.rows = []
 
     def load(self):
-        with open("testcases/form.yml") as f:
+        with open(os.path.join(BASE_DIR, "testcases/form.yml")) as f:
             ya = yaml.safe_load(f)
         result = ya["Add"]
         f.close()
 
         return result
 
     def mk_model(self, name_list):
@@ -38,19 +41,19 @@
             self.rows.append(i)
 
     def contact(self, datas):
         treeData = []
 
         for i in datas:
             if i in ["Add", "Modify", "Delete", "Search"]:
-                with open("testcases/form.yml") as f:
+                with open(os.path.join(BASE_DIR, "testcases/form.yml")) as f:
                     ya = yaml.safe_load(f)
 
             elif i in ["Pagination"]:
-                with open("testcases/page.yml") as f:
+                with open(os.path.join(BASE_DIR, "testcases/page.yml")) as f:
                     ya = yaml.safe_load(f)
 
             else:
                 raise IOError("模块在列表中不存在")
 
             result = ya[i]
             for j in result:
```

### Comparing `mkTestCase-0.0.2/mkTestCase/testcases/form.yml` & `mkTestCase-0.0.3/mkTestCase/testcases/form.yml`

 * *Files identical despite different names*

### Comparing `mkTestCase-0.0.2/mkTestCase/testcases/page.yml` & `mkTestCase-0.0.3/mkTestCase/testcases/page.yml`

 * *Files identical despite different names*

### Comparing `mkTestCase-0.0.2/mkTestCase.egg-info/PKG-INFO` & `mkTestCase-0.0.3/mkTestCase.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mkTestCase
-Version: 0.0.2
+Version: 0.0.3
 Summary: Write test cases like building blocks
 Home-page: https://github.com/yongchin0821/mkTestCase
 Author: Yongchin
 Author-email: yongchin39@qq.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/yongchin0821/mkTestCase/issues
 Keywords: testcase,automatically generate test cases,automated test
```

### Comparing `mkTestCase-0.0.2/setup.py` & `mkTestCase-0.0.3/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 from setuptools import setup, find_packages
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name="mkTestCase",
-    version="0.0.2",
+    version="0.0.3",
     author="Yongchin",
     author_email="yongchin39@qq.com",
     license="MIT",
     description="Write test cases like building blocks",
     long_description=long_description,
     long_description_content_type="text/markdown",
     keywords=["testcase", "automatically generate test cases", "automated test"],
```

