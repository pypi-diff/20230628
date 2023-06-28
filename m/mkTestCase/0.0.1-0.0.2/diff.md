# Comparing `tmp/mkTestCase-0.0.1.tar.gz` & `tmp/mkTestCase-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mkTestCase-0.0.1.tar", last modified: Mon Jun 26 06:19:17 2023, max compression
+gzip compressed data, was "mkTestCase-0.0.2.tar", last modified: Wed Jun 28 07:23:35 2023, max compression
```

## Comparing `mkTestCase-0.0.1.tar` & `mkTestCase-0.0.2.tar`

### file list

```diff
@@ -1,15 +1,19 @@
-drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-26 06:19:17.445554 mkTestCase-0.0.1/
--rw-r--r--   0 yangqing   (501) staff       (20)     1066 2023-03-03 07:16:54.000000 mkTestCase-0.0.1/LICENSE
--rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-26 06:19:17.445138 mkTestCase-0.0.1/PKG-INFO
--rw-r--r--   0 yangqing   (501) staff       (20)     1548 2023-06-05 08:46:44.000000 mkTestCase-0.0.1/README.md
-drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-26 06:19:17.441953 mkTestCase-0.0.1/mkTestCase/
--rw-r--r--   0 yangqing   (501) staff       (20)      141 2023-06-26 06:18:54.000000 mkTestCase-0.0.1/mkTestCase/__init__.py
--rw-r--r--   0 yangqing   (501) staff       (20)     2681 2023-06-26 06:08:12.000000 mkTestCase-0.0.1/mkTestCase/mkTestCase.py
-drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-26 06:19:17.444680 mkTestCase-0.0.1/mkTestCase.egg-info/
--rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-26 06:19:17.000000 mkTestCase-0.0.1/mkTestCase.egg-info/PKG-INFO
--rw-r--r--   0 yangqing   (501) staff       (20)      243 2023-06-26 06:19:17.000000 mkTestCase-0.0.1/mkTestCase.egg-info/SOURCES.txt
--rw-r--r--   0 yangqing   (501) staff       (20)        1 2023-06-26 06:19:17.000000 mkTestCase-0.0.1/mkTestCase.egg-info/dependency_links.txt
--rw-r--r--   0 yangqing   (501) staff       (20)        9 2023-06-26 06:19:17.000000 mkTestCase-0.0.1/mkTestCase.egg-info/requires.txt
--rw-r--r--   0 yangqing   (501) staff       (20)       11 2023-06-26 06:19:17.000000 mkTestCase-0.0.1/mkTestCase.egg-info/top_level.txt
--rw-r--r--   0 yangqing   (501) staff       (20)       38 2023-06-26 06:19:17.445676 mkTestCase-0.0.1/setup.cfg
--rw-r--r--   0 yangqing   (501) staff       (20)     1184 2023-06-26 03:20:09.000000 mkTestCase-0.0.1/setup.py
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.850034 mkTestCase-0.0.2/
+-rw-r--r--   0 yangqing   (501) staff       (20)     1066 2023-03-03 07:16:54.000000 mkTestCase-0.0.2/LICENSE
+-rw-r--r--   0 yangqing   (501) staff       (20)       40 2023-06-28 07:23:33.000000 mkTestCase-0.0.2/MANIFEST.in
+-rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-28 07:23:35.849329 mkTestCase-0.0.2/PKG-INFO
+-rw-r--r--   0 yangqing   (501) staff       (20)     1548 2023-06-05 08:46:44.000000 mkTestCase-0.0.2/README.md
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.842480 mkTestCase-0.0.2/mkTestCase/
+-rw-r--r--   0 yangqing   (501) staff       (20)      141 2023-06-26 06:18:54.000000 mkTestCase-0.0.2/mkTestCase/__init__.py
+-rw-r--r--   0 yangqing   (501) staff       (20)     2671 2023-06-28 07:19:56.000000 mkTestCase-0.0.2/mkTestCase/mkTestCase.py
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.846810 mkTestCase-0.0.2/mkTestCase/testcases/
+-rw-r--r--   0 yangqing   (501) staff       (20)      979 2023-06-05 08:41:57.000000 mkTestCase-0.0.2/mkTestCase/testcases/form.yml
+-rw-r--r--   0 yangqing   (501) staff       (20)      794 2023-03-03 08:28:51.000000 mkTestCase-0.0.2/mkTestCase/testcases/page.yml
+drwxr-xr-x   0 yangqing   (501) staff       (20)        0 2023-06-28 07:23:35.845749 mkTestCase-0.0.2/mkTestCase.egg-info/
+-rw-r--r--   0 yangqing   (501) staff       (20)     2209 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/PKG-INFO
+-rw-r--r--   0 yangqing   (501) staff       (20)      315 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/SOURCES.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)        1 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/dependency_links.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)        9 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/requires.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)       11 2023-06-28 07:23:35.000000 mkTestCase-0.0.2/mkTestCase.egg-info/top_level.txt
+-rw-r--r--   0 yangqing   (501) staff       (20)       38 2023-06-28 07:23:35.850200 mkTestCase-0.0.2/setup.cfg
+-rw-r--r--   0 yangqing   (501) staff       (20)     1184 2023-06-28 07:19:56.000000 mkTestCase-0.0.2/setup.py
```

### Comparing `mkTestCase-0.0.1/LICENSE` & `mkTestCase-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `mkTestCase-0.0.1/PKG-INFO` & `mkTestCase-0.0.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mkTestCase
-Version: 0.0.1
+Version: 0.0.2
 Summary: Write test cases like building blocks
 Home-page: https://github.com/yongchin0821/mkTestCase
 Author: Yongchin
 Author-email: yongchin39@qq.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/yongchin0821/mkTestCase/issues
 Keywords: testcase,automatically generate test cases,automated test
```

### Comparing `mkTestCase-0.0.1/README.md` & `mkTestCase-0.0.2/README.md`

 * *Files identical despite different names*

### Comparing `mkTestCase-0.0.1/mkTestCase/mkTestCase.py` & `mkTestCase-0.0.2/mkTestCase/mkTestCase.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 class Factory:
     def __init__(self):
         self.m_count = 0
         self.model_index = []
         self.rows = []
 
     def load(self):
-        with open("../testcases/form.yml") as f:
+        with open("testcases/form.yml") as f:
             ya = yaml.safe_load(f)
         result = ya["Add"]
         f.close()
 
         return result
 
     def mk_model(self, name_list):
@@ -37,21 +37,20 @@
         for i in rows:
             self.rows.append(i)
 
     def contact(self, datas):
         treeData = []
 
         for i in datas:
-
             if i in ["Add", "Modify", "Delete", "Search"]:
-                with open("../testcases/form.yml") as f:
+                with open("testcases/form.yml") as f:
                     ya = yaml.safe_load(f)
 
             elif i in ["Pagination"]:
-                with open("../testcases/page.yml") as f:
+                with open("testcases/page.yml") as f:
                     ya = yaml.safe_load(f)
 
             else:
                 raise IOError("模块在列表中不存在")
 
             result = ya[i]
             for j in result:
```

### Comparing `mkTestCase-0.0.1/mkTestCase.egg-info/PKG-INFO` & `mkTestCase-0.0.2/mkTestCase.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mkTestCase
-Version: 0.0.1
+Version: 0.0.2
 Summary: Write test cases like building blocks
 Home-page: https://github.com/yongchin0821/mkTestCase
 Author: Yongchin
 Author-email: yongchin39@qq.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/yongchin0821/mkTestCase/issues
 Keywords: testcase,automatically generate test cases,automated test
```

### Comparing `mkTestCase-0.0.1/setup.py` & `mkTestCase-0.0.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 from setuptools import setup, find_packages
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name="mkTestCase",
-    version="0.0.1",
+    version="0.0.2",
     author="Yongchin",
     author_email="yongchin39@qq.com",
     license="MIT",
     description="Write test cases like building blocks",
     long_description=long_description,
     long_description_content_type="text/markdown",
     keywords=["testcase", "automatically generate test cases", "automated test"],
```

