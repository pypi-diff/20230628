# Comparing `tmp/InfixToPostfix-1.0.8.tar.gz` & `tmp/InfixToPostfix-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "InfixToPostfix-1.0.8.tar", last modified: Wed Jun 14 04:02:18 2023, max compression
+gzip compressed data, was "InfixToPostfix-1.1.0.tar", last modified: Wed Jun 28 08:25:13 2023, max compression
```

## Comparing `InfixToPostfix-1.0.8.tar` & `InfixToPostfix-1.1.0.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 04:02:18.119079 InfixToPostfix-1.0.8/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 04:02:18.119079 InfixToPostfix-1.0.8/InfixToPostfix/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/InfixToPostfix/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 04:02:18.119079 InfixToPostfix-1.0.8/InfixToPostfix/data/
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/InfixToPostfix/data/conf
--rw-r--r--   0 runner    (1001) docker     (123)      785 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/InfixToPostfix/data/style.qss
--rw-r--r--   0 runner    (1001) docker     (123)     7291 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/InfixToPostfix/infix_to_postfix.py
--rw-r--r--   0 runner    (1001) docker     (123)     3755 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/InfixToPostfix/ui.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-14 04:02:18.119079 InfixToPostfix-1.0.8/InfixToPostfix.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1350 2023-06-14 04:02:18.000000 InfixToPostfix-1.0.8/InfixToPostfix.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      382 2023-06-14 04:02:18.000000 InfixToPostfix-1.0.8/InfixToPostfix.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-14 04:02:18.000000 InfixToPostfix-1.0.8/InfixToPostfix.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-14 04:02:18.000000 InfixToPostfix-1.0.8/InfixToPostfix.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-14 04:02:18.000000 InfixToPostfix-1.0.8/InfixToPostfix.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)    35148 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     1350 2023-06-14 04:02:18.119079 InfixToPostfix-1.0.8/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      985 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-14 04:02:18.119079 InfixToPostfix-1.0.8/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      597 2023-06-14 04:02:09.000000 InfixToPostfix-1.0.8/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:25:13.621576 InfixToPostfix-1.1.0/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:25:13.621576 InfixToPostfix-1.1.0/InfixToPostfix/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/InfixToPostfix/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:25:13.621576 InfixToPostfix-1.1.0/InfixToPostfix/data/
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/InfixToPostfix/data/conf
+-rw-r--r--   0 runner    (1001) docker     (123)      785 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/InfixToPostfix/data/style.qss
+-rw-r--r--   0 runner    (1001) docker     (123)     7583 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/InfixToPostfix/infix_to_postfix.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7106 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/InfixToPostfix/ui.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:25:13.621576 InfixToPostfix-1.1.0/InfixToPostfix.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-28 08:25:13.000000 InfixToPostfix-1.1.0/InfixToPostfix.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      382 2023-06-28 08:25:13.000000 InfixToPostfix-1.1.0/InfixToPostfix.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:25:13.000000 InfixToPostfix-1.1.0/InfixToPostfix.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 08:25:13.000000 InfixToPostfix-1.1.0/InfixToPostfix.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-28 08:25:13.000000 InfixToPostfix-1.1.0/InfixToPostfix.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    35148 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-28 08:25:13.621576 InfixToPostfix-1.1.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1107 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 08:25:13.621576 InfixToPostfix-1.1.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      597 2023-06-28 08:24:59.000000 InfixToPostfix-1.1.0/setup.py
```

### Comparing `InfixToPostfix-1.0.8/InfixToPostfix/data/style.qss` & `InfixToPostfix-1.1.0/InfixToPostfix/data/style.qss`

 * *Files identical despite different names*

### Comparing `InfixToPostfix-1.0.8/InfixToPostfix.egg-info/PKG-INFO` & `InfixToPostfix-1.1.0/InfixToPostfix.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: InfixToPostfix
-Version: 1.0.8
+Version: 1.1.0
 Summary: A python module converts infix expressions to postfix expressions and includes a visual interface.
 Home-page: https://github.com/RoiexLee/InfixToPostfiX
 Author: RoiexLee
 Author-email: luoyixaun1029@gmail.com
 Requires-Python: >=3.11.0
 Description-Content-Type: text/markdown
 License-File: LICENSE
@@ -49,7 +49,9 @@
 window = MainWindow()
 sys.exit(app.exec())
 ```
 
 ![visual_interface_1.png](https://github.com/RoiexLee/InfixToPostfix/blob/main/resource/visual_interface_1.png?raw=true)
 
 ![visual_interface_2.png](https://github.com/RoiexLee/InfixToPostfix/blob/main/resource/visual_interface_2.png?raw=true)
+
+![visual_interface_3.png](https://github.com/RoiexLee/InfixToPostfix/blob/main/resource/visual_interface_3.png?raw=true)
```

### Comparing `InfixToPostfix-1.0.8/LICENSE` & `InfixToPostfix-1.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `InfixToPostfix-1.0.8/PKG-INFO` & `InfixToPostfix-1.1.0/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: InfixToPostfix
-Version: 1.0.8
+Version: 1.1.0
 Summary: A python module converts infix expressions to postfix expressions and includes a visual interface.
 Home-page: https://github.com/RoiexLee/InfixToPostfiX
 Author: RoiexLee
 Author-email: luoyixaun1029@gmail.com
 Requires-Python: >=3.11.0
 Description-Content-Type: text/markdown
 License-File: LICENSE
@@ -49,7 +49,9 @@
 window = MainWindow()
 sys.exit(app.exec())
 ```
 
 ![visual_interface_1.png](https://github.com/RoiexLee/InfixToPostfix/blob/main/resource/visual_interface_1.png?raw=true)
 
 ![visual_interface_2.png](https://github.com/RoiexLee/InfixToPostfix/blob/main/resource/visual_interface_2.png?raw=true)
+
+![visual_interface_3.png](https://github.com/RoiexLee/InfixToPostfix/blob/main/resource/visual_interface_3.png?raw=true)
```

### Comparing `InfixToPostfix-1.0.8/setup.py` & `InfixToPostfix-1.1.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name="InfixToPostfix",
-    version="1.0.8",
+    version="1.1.0",
     author="RoiexLee",
     author_email="luoyixaun1029@gmail.com",
     description="A python module converts infix expressions to postfix expressions and includes a visual interface.",
     long_description_content_type="text/markdown",
     long_description=open("README.md").read(),
     url="https://github.com/RoiexLee/InfixToPostfiX",
     packages=find_packages(),
```

