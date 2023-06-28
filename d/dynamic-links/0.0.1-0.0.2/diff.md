# Comparing `tmp/dynamic-links-0.0.1.tar.gz` & `tmp/dynamic-links-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dynamic-links-0.0.1.tar", last modified: Wed Jun 28 02:28:53 2023, max compression
+gzip compressed data, was "dynamic-links-0.0.2.tar", last modified: Wed Jun 28 06:04:35 2023, max compression
```

## Comparing `dynamic-links-0.0.1.tar` & `dynamic-links-0.0.2.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 02:28:53.126877 dynamic-links-0.0.1/
--rw-r--r--   0 pic        (501) staff       (20)     1570 2023-06-28 02:28:53.126720 dynamic-links-0.0.1/PKG-INFO
--rw-r--r--   0 pic        (501) staff       (20)     1298 2023-06-27 02:20:37.000000 dynamic-links-0.0.1/README.md
-drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 02:28:53.125610 dynamic-links-0.0.1/dlframe/
--rw-r--r--   0 pic        (501) staff       (20)     2630 2023-06-27 04:59:53.000000 dynamic-links-0.0.1/dlframe/CalculationNode.py
--rw-r--r--   0 pic        (501) staff       (20)     1924 2023-06-27 03:29:25.000000 dynamic-links-0.0.1/dlframe/CalculationNodeManager.py
--rw-r--r--   0 pic        (501) staff       (20)     2048 2023-06-27 04:00:46.000000 dynamic-links-0.0.1/dlframe/ExecutionNode.py
--rw-r--r--   0 pic        (501) staff       (20)      939 2023-06-27 05:19:42.000000 dynamic-links-0.0.1/dlframe/Logger.py
--rw-r--r--   0 pic        (501) staff       (20)     5170 2023-06-27 05:20:48.000000 dynamic-links-0.0.1/dlframe/WebManager.py
--rw-r--r--   0 pic        (501) staff       (20)      141 2023-06-26 17:09:16.000000 dynamic-links-0.0.1/dlframe/__init__.py
-drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 02:28:53.126511 dynamic-links-0.0.1/dynamic_links.egg-info/
--rw-r--r--   0 pic        (501) staff       (20)     1570 2023-06-28 02:28:53.000000 dynamic-links-0.0.1/dynamic_links.egg-info/PKG-INFO
--rw-r--r--   0 pic        (501) staff       (20)      348 2023-06-28 02:28:53.000000 dynamic-links-0.0.1/dynamic_links.egg-info/SOURCES.txt
--rw-r--r--   0 pic        (501) staff       (20)        1 2023-06-28 02:28:53.000000 dynamic-links-0.0.1/dynamic_links.egg-info/dependency_links.txt
--rw-r--r--   0 pic        (501) staff       (20)       30 2023-06-28 02:28:53.000000 dynamic-links-0.0.1/dynamic_links.egg-info/requires.txt
--rw-r--r--   0 pic        (501) staff       (20)        8 2023-06-28 02:28:53.000000 dynamic-links-0.0.1/dynamic_links.egg-info/top_level.txt
--rw-r--r--   0 pic        (501) staff       (20)       38 2023-06-28 02:28:53.126925 dynamic-links-0.0.1/setup.cfg
--rw-r--r--   0 pic        (501) staff       (20)      682 2023-06-28 02:26:15.000000 dynamic-links-0.0.1/setup.py
+drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:04:35.385835 dynamic-links-0.0.2/
+-rw-r--r--   0 pic        (501) staff       (20)     5249 2023-06-28 06:04:35.385686 dynamic-links-0.0.2/PKG-INFO
+-rw-r--r--   0 pic        (501) staff       (20)     4976 2023-06-28 06:02:18.000000 dynamic-links-0.0.2/README.md
+drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:04:35.384705 dynamic-links-0.0.2/dlframe/
+-rw-r--r--   0 pic        (501) staff       (20)     2630 2023-06-27 04:59:53.000000 dynamic-links-0.0.2/dlframe/CalculationNode.py
+-rw-r--r--   0 pic        (501) staff       (20)     1924 2023-06-27 03:29:25.000000 dynamic-links-0.0.2/dlframe/CalculationNodeManager.py
+-rw-r--r--   0 pic        (501) staff       (20)     2048 2023-06-27 04:00:46.000000 dynamic-links-0.0.2/dlframe/ExecutionNode.py
+-rw-r--r--   0 pic        (501) staff       (20)      939 2023-06-27 05:19:42.000000 dynamic-links-0.0.2/dlframe/Logger.py
+-rw-r--r--   0 pic        (501) staff       (20)     5170 2023-06-27 05:20:48.000000 dynamic-links-0.0.2/dlframe/WebManager.py
+-rw-r--r--   0 pic        (501) staff       (20)      141 2023-06-26 17:09:16.000000 dynamic-links-0.0.2/dlframe/__init__.py
+drwxr-xr-x   0 pic        (501) staff       (20)        0 2023-06-28 06:04:35.385468 dynamic-links-0.0.2/dynamic_links.egg-info/
+-rw-r--r--   0 pic        (501) staff       (20)     5249 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/PKG-INFO
+-rw-r--r--   0 pic        (501) staff       (20)      348 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/SOURCES.txt
+-rw-r--r--   0 pic        (501) staff       (20)        1 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/dependency_links.txt
+-rw-r--r--   0 pic        (501) staff       (20)       30 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/requires.txt
+-rw-r--r--   0 pic        (501) staff       (20)        8 2023-06-28 06:04:35.000000 dynamic-links-0.0.2/dynamic_links.egg-info/top_level.txt
+-rw-r--r--   0 pic        (501) staff       (20)       38 2023-06-28 06:04:35.385879 dynamic-links-0.0.2/setup.cfg
+-rw-r--r--   0 pic        (501) staff       (20)      682 2023-06-28 06:04:18.000000 dynamic-links-0.0.2/setup.py
```

### Comparing `dynamic-links-0.0.1/dlframe/CalculationNode.py` & `dynamic-links-0.0.2/dlframe/CalculationNode.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.1/dlframe/CalculationNodeManager.py` & `dynamic-links-0.0.2/dlframe/CalculationNodeManager.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.1/dlframe/ExecutionNode.py` & `dynamic-links-0.0.2/dlframe/ExecutionNode.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.1/dlframe/Logger.py` & `dynamic-links-0.0.2/dlframe/Logger.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.1/dlframe/WebManager.py` & `dynamic-links-0.0.2/dlframe/WebManager.py`

 * *Files identical despite different names*

### Comparing `dynamic-links-0.0.1/setup.py` & `dynamic-links-0.0.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 here = pathlib.Path(__file__).parent.resolve()
 
 with open(os.path.join(here, 'README.md'), 'r',encoding='UTF-8') as mdFile:
     long_description = mdFile.read()
 
 setup(
     name='dynamic-links', 
-    version='0.0.1', 
+    version='0.0.2', 
     packages=['dlframe'], 
     url='https://github.com/picpic2013/dlframe-back', 
     license='MIT', 
     author='PIC', 
     author_email='picpic2019@gmail.com', 
     description='a calculation framework', 
     long_description=long_description,
```

