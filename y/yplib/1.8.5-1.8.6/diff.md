# Comparing `tmp/yplib-1.8.5.tar.gz` & `tmp/yplib-1.8.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\yplib-1.8.5.tar", last modified: Tue Jun 27 08:22:55 2023, max compression
+gzip compressed data, was "dist\yplib-1.8.6.tar", last modified: Wed Jun 28 06:40:35 2023, max compression
```

## Comparing `yplib-1.8.5.tar` & `yplib-1.8.6.tar`

### file list

```diff
@@ -1,21 +1,22 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 08:22:55.408095 yplib-1.8.5/
--rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.8.5/LICENSE
--rw-rw-rw-   0        0        0      352 2023-06-27 08:22:55.407595 yplib-1.8.5/PKG-INFO
--rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.8.5/README.md
--rw-rw-rw-   0        0        0       42 2023-06-27 08:22:55.408095 yplib-1.8.5/setup.cfg
--rw-rw-rw-   0        0        0      513 2023-06-27 08:22:46.000000 yplib-1.8.5/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-27 08:22:55.403867 yplib-1.8.5/yplib/
--rw-rw-rw-   0        0        0      527 2023-06-27 08:04:11.000000 yplib-1.8.5/yplib/__init__.py
--rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.8.5/yplib/chart.py
--rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.8.5/yplib/chart_html.py
--rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.8.5/yplib/db.py
--rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.8.5/yplib/file.py
--rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.8.5/yplib/http_util.py
--rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.8.5/yplib/index.py
--rw-rw-rw-   0        0        0      816 2023-06-27 08:21:57.000000 yplib-1.8.5/yplib/mail.py
--rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.8.5/yplib/temp.py
-drwxrwxrwx   0        0        0        0 2023-06-27 08:22:55.406606 yplib-1.8.5/yplib.egg-info/
--rw-rw-rw-   0        0        0      352 2023-06-27 08:22:55.000000 yplib-1.8.5/yplib.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      283 2023-06-27 08:22:55.000000 yplib-1.8.5/yplib.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 08:22:55.000000 yplib-1.8.5/yplib.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-27 08:22:55.000000 yplib-1.8.5/yplib.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 06:40:35.526707 yplib-1.8.6/
+-rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.8.6/LICENSE
+-rw-rw-rw-   0        0        0      352 2023-06-28 06:40:35.526147 yplib-1.8.6/PKG-INFO
+-rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.8.6/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 06:40:35.526707 yplib-1.8.6/setup.cfg
+-rw-rw-rw-   0        0        0      513 2023-06-28 06:40:21.000000 yplib-1.8.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:40:35.523478 yplib-1.8.6/yplib/
+-rw-rw-rw-   0        0        0      527 2023-06-27 08:04:11.000000 yplib-1.8.6/yplib/__init__.py
+-rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.8.6/yplib/chart.py
+-rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.8.6/yplib/chart_html.py
+-rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.8.6/yplib/db.py
+-rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.8.6/yplib/file.py
+-rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.8.6/yplib/http_util.py
+-rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.8.6/yplib/index.py
+-rw-rw-rw-   0        0        0     2506 2023-06-28 06:40:01.000000 yplib-1.8.6/yplib/mail.py
+-rw-rw-rw-   0        0        0     3520 2023-06-27 09:03:17.000000 yplib-1.8.6/yplib/mail_html.py
+-rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.8.6/yplib/temp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:40:35.525742 yplib-1.8.6/yplib.egg-info/
+-rw-rw-rw-   0        0        0      352 2023-06-28 06:40:35.000000 yplib-1.8.6/yplib.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      302 2023-06-28 06:40:35.000000 yplib-1.8.6/yplib.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 06:40:35.000000 yplib-1.8.6/yplib.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 06:40:35.000000 yplib-1.8.6/yplib.egg-info/top_level.txt
```

### Comparing `yplib-1.8.5/LICENSE` & `yplib-1.8.6/LICENSE`

 * *Files identical despite different names*

### Comparing `yplib-1.8.5/setup.py` & `yplib-1.8.6/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
   long_description = fh.read()
 
 setuptools.setup(
   name="yplib",
-  version="1.8.5",
+  version="1.8.6",
   author="yangpu",
   author_email="wantwaterfish@gmail.com",
   description="util",
   long_description=long_description,
   long_description_content_type="text/markdown",
   packages=setuptools.find_packages(),
   classifiers=[
```

### Comparing `yplib-1.8.5/yplib/__init__.py` & `yplib-1.8.6/yplib/__init__.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.5/yplib/chart.py` & `yplib-1.8.6/yplib/chart.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.5/yplib/chart_html.py` & `yplib-1.8.6/yplib/chart_html.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.5/yplib/db.py` & `yplib-1.8.6/yplib/db.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.5/yplib/file.py` & `yplib-1.8.6/yplib/file.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.5/yplib/http_util.py` & `yplib-1.8.6/yplib/http_util.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.5/yplib/index.py` & `yplib-1.8.6/yplib/index.py`

 * *Files identical despite different names*

