# Comparing `tmp/pyintelx-0.1.6.tar.gz` & `tmp/pyintelx-0.1.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyintelx-0.1.6.tar", last modified: Wed Jun 28 13:53:45 2023, max compression
+gzip compressed data, was "pyintelx-0.1.7.tar", last modified: Wed Jun 28 14:05:37 2023, max compression
```

## Comparing `pyintelx-0.1.6.tar` & `pyintelx-0.1.7.tar`

### file list

```diff
@@ -1,15 +1,14 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:53:45.109538 pyintelx-0.1.6/
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-28 13:53:13.000000 pyintelx-0.1.6/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 13:53:45.109538 pyintelx-0.1.6/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2031 2023-06-28 13:53:13.000000 pyintelx-0.1.6/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:53:45.105538 pyintelx-0.1.6/pyintelx/
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:53:13.000000 pyintelx-0.1.6/pyintelx/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:53:45.109538 pyintelx-0.1.6/pyintelx/cli/
--rw-r--r--   0 runner    (1001) docker     (123)    10502 2023-06-28 13:53:13.000000 pyintelx-0.1.6/pyintelx/cli/pyintelx
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:53:45.109538 pyintelx-0.1.6/pyintelx.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 13:53:45.000000 pyintelx-0.1.6/pyintelx.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      201 2023-06-28 13:53:45.000000 pyintelx-0.1.6/pyintelx.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:53:45.000000 pyintelx-0.1.6/pyintelx.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 13:53:45.000000 pyintelx-0.1.6/pyintelx.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:53:45.109538 pyintelx-0.1.6/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-28 13:53:13.000000 pyintelx-0.1.6/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:05:37.005396 pyintelx-0.1.7/
+-rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 14:05:37.005396 pyintelx-0.1.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2031 2023-06-28 14:05:25.000000 pyintelx-0.1.7/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:05:37.001396 pyintelx-0.1.7/pyintelx/
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:05:25.000000 pyintelx-0.1.7/pyintelx/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:05:37.005396 pyintelx-0.1.7/pyintelx/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)    10502 2023-06-28 14:05:25.000000 pyintelx-0.1.7/pyintelx/cli/pyintelx
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:05:37.005396 pyintelx-0.1.7/pyintelx.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 14:05:36.000000 pyintelx-0.1.7/pyintelx.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      189 2023-06-28 14:05:37.000000 pyintelx-0.1.7/pyintelx.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:05:36.000000 pyintelx-0.1.7/pyintelx.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 14:05:36.000000 pyintelx-0.1.7/pyintelx.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:05:37.005396 pyintelx-0.1.7/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-28 14:05:25.000000 pyintelx-0.1.7/setup.py
```

### Comparing `pyintelx-0.1.6/PKG-INFO` & `pyintelx-0.1.7/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyintelx
-Version: 0.1.6
+Version: 0.1.7
 Summary: This lib add support to use the Identity API from Intelx.io
 Home-page: https://github.com/csirtamericas/pyintelxio
 Author: Fermin Baudino, Einar Lanfranco, Federico Carrilao
 License: MIT
 Keywords: python, package, distribution
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Natural Language :: English
```

### Comparing `pyintelx-0.1.6/README.md` & `pyintelx-0.1.7/README.md`

 * *Files identical despite different names*

### Comparing `pyintelx-0.1.6/pyintelx/cli/pyintelx` & `pyintelx-0.1.7/pyintelx/cli/pyintelx`

 * *Files identical despite different names*

### Comparing `pyintelx-0.1.6/pyintelx.egg-info/PKG-INFO` & `pyintelx-0.1.7/pyintelx.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyintelx
-Version: 0.1.6
+Version: 0.1.7
 Summary: This lib add support to use the Identity API from Intelx.io
 Home-page: https://github.com/csirtamericas/pyintelxio
 Author: Fermin Baudino, Einar Lanfranco, Federico Carrilao
 License: MIT
 Keywords: python, package, distribution
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Natural Language :: English
```

### Comparing `pyintelx-0.1.6/setup.py` & `pyintelx-0.1.7/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
     
 
 setup(
     name='pyintelx',
-    version='0.1.6',
+    version='0.1.7',
     description='This lib add support to use the Identity API from Intelx.io',
     license='MIT',
     keywords=['python, package, distribution'],
     long_description=long_description,
     long_description_content_type="text/markdown",
     author='Fermin Baudino, Einar Lanfranco, Federico Carrilao',
     url='https://github.com/csirtamericas/pyintelxio',
```

