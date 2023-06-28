# Comparing `tmp/spark_dummy_tools-0.1.0.tar.gz` & `tmp/spark_dummy_tools-0.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "spark_dummy_tools-0.1.0.tar", last modified: Wed Jun 28 06:07:12 2023, max compression
+gzip compressed data, was "spark_dummy_tools-0.2.1.tar", last modified: Wed Jun 28 06:31:44 2023, max compression
```

## Comparing `spark_dummy_tools-0.1.0.tar` & `spark_dummy_tools-0.2.1.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 06:07:12.660612 spark_dummy_tools-0.1.0/
--rw-rw-rw-   0        0        0     1092 2022-12-01 18:42:47.000000 spark_dummy_tools-0.1.0/LICENSE
--rw-rw-rw-   0        0        0        4 2023-06-26 03:19:39.000000 spark_dummy_tools-0.1.0/MANIFEST.in
--rw-rw-rw-   0        0        0     4266 2023-06-28 06:07:12.660612 spark_dummy_tools-0.1.0/PKG-INFO
--rw-rw-rw-   0        0        0     3507 2023-06-12 03:37:30.000000 spark_dummy_tools-0.1.0/README.md
--rw-rw-rw-   0        0        0      636 2023-06-26 03:37:00.000000 spark_dummy_tools-0.1.0/pyproject.toml
--rw-rw-rw-   0        0        0       86 2023-06-28 06:07:12.661613 spark_dummy_tools-0.1.0/setup.cfg
--rw-rw-rw-   0        0        0     1164 2023-06-26 11:56:52.000000 spark_dummy_tools-0.1.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:07:12.630648 spark_dummy_tools-0.1.0/spark_dummy_tools/
--rw-rw-rw-   0        0        0      215 2023-06-26 03:38:44.000000 spark_dummy_tools-0.1.0/spark_dummy_tools/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:07:12.650610 spark_dummy_tools-0.1.0/spark_dummy_tools/functions/
--rw-rw-rw-   0        0        0        0 2022-12-01 18:42:47.000000 spark_dummy_tools-0.1.0/spark_dummy_tools/functions/__init__.py
--rw-rw-rw-   0        0        0     5449 2023-06-28 06:03:02.000000 spark_dummy_tools-0.1.0/spark_dummy_tools/functions/generator.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:07:12.659613 spark_dummy_tools-0.1.0/spark_dummy_tools/utils/
--rw-rw-rw-   0        0        0       75 2022-12-01 18:42:47.000000 spark_dummy_tools-0.1.0/spark_dummy_tools/utils/__init__.py
--rw-rw-rw-   0        0        0      416 2023-06-04 03:38:46.000000 spark_dummy_tools-0.1.0/spark_dummy_tools/utils/color.py
--rw-rw-rw-   0        0        0     6983 2023-06-26 11:50:04.000000 spark_dummy_tools-0.1.0/spark_dummy_tools/utils/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:07:12.649608 spark_dummy_tools-0.1.0/spark_dummy_tools.egg-info/
--rw-rw-rw-   0        0        0     4266 2023-06-28 06:07:12.000000 spark_dummy_tools-0.1.0/spark_dummy_tools.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      480 2023-06-28 06:07:12.000000 spark_dummy_tools-0.1.0/spark_dummy_tools.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 06:07:12.000000 spark_dummy_tools-0.1.0/spark_dummy_tools.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      191 2023-06-28 06:07:12.000000 spark_dummy_tools-0.1.0/spark_dummy_tools.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-06-28 06:07:12.000000 spark_dummy_tools-0.1.0/spark_dummy_tools.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 06:31:44.188967 spark_dummy_tools-0.2.1/
+-rw-rw-rw-   0        0        0     1092 2022-12-01 18:42:47.000000 spark_dummy_tools-0.2.1/LICENSE
+-rw-rw-rw-   0        0        0        4 2023-06-26 03:19:39.000000 spark_dummy_tools-0.2.1/MANIFEST.in
+-rw-rw-rw-   0        0        0     4254 2023-06-28 06:31:44.188967 spark_dummy_tools-0.2.1/PKG-INFO
+-rw-rw-rw-   0        0        0     3495 2023-06-28 06:31:22.000000 spark_dummy_tools-0.2.1/README.md
+-rw-rw-rw-   0        0        0      636 2023-06-26 03:37:00.000000 spark_dummy_tools-0.2.1/pyproject.toml
+-rw-rw-rw-   0        0        0       86 2023-06-28 06:31:44.192967 spark_dummy_tools-0.2.1/setup.cfg
+-rw-rw-rw-   0        0        0     1164 2023-06-28 06:31:22.000000 spark_dummy_tools-0.2.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:31:44.164986 spark_dummy_tools-0.2.1/spark_dummy_tools/
+-rw-rw-rw-   0        0        0      372 2023-06-28 06:23:48.000000 spark_dummy_tools-0.2.1/spark_dummy_tools/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:31:44.185991 spark_dummy_tools-0.2.1/spark_dummy_tools/functions/
+-rw-rw-rw-   0        0        0        0 2022-12-01 18:42:47.000000 spark_dummy_tools-0.2.1/spark_dummy_tools/functions/__init__.py
+-rw-rw-rw-   0        0        0     9442 2023-06-28 06:23:48.000000 spark_dummy_tools-0.2.1/spark_dummy_tools/functions/generator.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:31:44.187965 spark_dummy_tools-0.2.1/spark_dummy_tools/utils/
+-rw-rw-rw-   0        0        0       75 2022-12-01 18:42:47.000000 spark_dummy_tools-0.2.1/spark_dummy_tools/utils/__init__.py
+-rw-rw-rw-   0        0        0      416 2023-06-04 03:38:46.000000 spark_dummy_tools-0.2.1/spark_dummy_tools/utils/color.py
+-rw-rw-rw-   0        0        0     6983 2023-06-26 11:50:04.000000 spark_dummy_tools-0.2.1/spark_dummy_tools/utils/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:31:44.184992 spark_dummy_tools-0.2.1/spark_dummy_tools.egg-info/
+-rw-rw-rw-   0        0        0     4254 2023-06-28 06:31:44.000000 spark_dummy_tools-0.2.1/spark_dummy_tools.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      480 2023-06-28 06:31:44.000000 spark_dummy_tools-0.2.1/spark_dummy_tools.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 06:31:44.000000 spark_dummy_tools-0.2.1/spark_dummy_tools.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      191 2023-06-28 06:31:44.000000 spark_dummy_tools-0.2.1/spark_dummy_tools.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 06:31:44.000000 spark_dummy_tools-0.2.1/spark_dummy_tools.egg-info/top_level.txt
```

### Comparing `spark_dummy_tools-0.1.0/LICENSE` & `spark_dummy_tools-0.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `spark_dummy_tools-0.1.0/pyproject.toml` & `spark_dummy_tools-0.2.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `spark_dummy_tools-0.1.0/setup.py` & `spark_dummy_tools-0.2.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 from setuptools import find_packages
 
 setuppath = os.path.dirname(os.path.abspath(__file__))
 
 setup(
     name='spark_dummy_tools',
     packages=find_packages(),
-    version='0.1.0',
+    version='0.2.1',
     description='spark_dummy_tools',
     long_description=open(os.path.join(setuppath, 'README.md')).read(),
     long_description_content_type="text/markdown",
     author='Jonathan Quiza',
     author_email='jony327@gmail.com',
     url='https://github.com/jonaqp/spark_dummy_tools/',
     download_url='https://github.com/jonaqp/spark_dummy_tools/archive/main.zip',
```

### Comparing `spark_dummy_tools-0.1.0/spark_dummy_tools/utils/utils.py` & `spark_dummy_tools-0.2.1/spark_dummy_tools/utils/utils.py`

 * *Files identical despite different names*

