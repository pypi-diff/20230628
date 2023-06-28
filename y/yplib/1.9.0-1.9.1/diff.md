# Comparing `tmp/yplib-1.9.0.tar.gz` & `tmp/yplib-1.9.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\yplib-1.9.0.tar", last modified: Wed Jun 28 08:09:20 2023, max compression
+gzip compressed data, was "dist\yplib-1.9.1.tar", last modified: Wed Jun 28 08:18:57 2023, max compression
```

## Comparing `yplib-1.9.0.tar` & `yplib-1.9.1.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 08:09:20.118804 yplib-1.9.0/
--rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.9.0/LICENSE
--rw-rw-rw-   0        0        0      352 2023-06-28 08:09:20.118098 yplib-1.9.0/PKG-INFO
--rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.9.0/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 08:09:20.119304 yplib-1.9.0/setup.cfg
--rw-rw-rw-   0        0        0      513 2023-06-28 08:08:55.000000 yplib-1.9.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 08:09:20.115405 yplib-1.9.0/yplib/
--rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.9.0/yplib/__init__.py
--rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.9.0/yplib/chart.py
--rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.9.0/yplib/chart_html.py
--rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.9.0/yplib/db.py
--rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.9.0/yplib/file.py
--rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.9.0/yplib/http_util.py
--rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.9.0/yplib/index.py
--rw-rw-rw-   0        0        0     3805 2023-06-28 08:00:53.000000 yplib-1.9.0/yplib/mail.py
--rw-rw-rw-   0        0        0     3557 2023-06-28 08:08:12.000000 yplib-1.9.0/yplib/mail_html.py
--rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.9.0/yplib/temp.py
-drwxrwxrwx   0        0        0        0 2023-06-28 08:09:20.118098 yplib-1.9.0/yplib.egg-info/
--rw-rw-rw-   0        0        0      352 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      302 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 08:18:57.389782 yplib-1.9.1/
+-rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.9.1/LICENSE
+-rw-rw-rw-   0        0        0      352 2023-06-28 08:18:57.389782 yplib-1.9.1/PKG-INFO
+-rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.9.1/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:18:57.390642 yplib-1.9.1/setup.cfg
+-rw-rw-rw-   0        0        0      513 2023-06-28 08:18:37.000000 yplib-1.9.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:18:57.386839 yplib-1.9.1/yplib/
+-rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.9.1/yplib/__init__.py
+-rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.9.1/yplib/chart.py
+-rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.9.1/yplib/chart_html.py
+-rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.9.1/yplib/db.py
+-rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.9.1/yplib/file.py
+-rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.9.1/yplib/http_util.py
+-rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.9.1/yplib/index.py
+-rw-rw-rw-   0        0        0     3805 2023-06-28 08:00:53.000000 yplib-1.9.1/yplib/mail.py
+-rw-rw-rw-   0        0        0     3546 2023-06-28 08:18:28.000000 yplib-1.9.1/yplib/mail_html.py
+-rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.9.1/yplib/temp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:18:57.389442 yplib-1.9.1/yplib.egg-info/
+-rw-rw-rw-   0        0        0      352 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      302 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/top_level.txt
```

### Comparing `yplib-1.9.0/LICENSE` & `yplib-1.9.1/LICENSE`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/setup.py` & `yplib-1.9.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
   long_description = fh.read()
 
 setuptools.setup(
   name="yplib",
-  version="1.9.0",
+  version="1.9.1",
   author="yangpu",
   author_email="wantwaterfish@gmail.com",
   description="util",
   long_description=long_description,
   long_description_content_type="text/markdown",
   packages=setuptools.find_packages(),
   classifiers=[
```

### Comparing `yplib-1.9.0/yplib/__init__.py` & `yplib-1.9.1/yplib/__init__.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/chart.py` & `yplib-1.9.1/yplib/chart.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/chart_html.py` & `yplib-1.9.1/yplib/chart_html.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/db.py` & `yplib-1.9.1/yplib/db.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/file.py` & `yplib-1.9.1/yplib/file.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/http_util.py` & `yplib-1.9.1/yplib/http_util.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/index.py` & `yplib-1.9.1/yplib/index.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/mail.py` & `yplib-1.9.1/yplib/mail.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.0/yplib/mail_html.py` & `yplib-1.9.1/yplib/mail_html.py`

 * *Files 1% similar despite different names*

```diff
@@ -52,15 +52,15 @@
         color_value = color_normal_value
 
     one = ['<div style="padding: 5px;background:#-color_stripe-;border-radius:5px;">',
            '    <span>-key-</span>',
            '</div>']
     key_value = ['<div style="border-radius:5px;padding:2px;background: #-color_stripe-;">',
                  '    <div style="width: 48%;display: inline-block;white-space: normal;word-wrap: break-word;">',
-                 '        <div style="width:calc(100%-15px);display: inline-block;text-align: right;">',
+                 '        <div style="width: 92%;display: inline-block;text-align: right;">',
                  '            <span>-key-</span>',
                  '        </div>',
                  '        <div style="text-align: center;width: 10px;display: inline-block;float: right;border-radius: 3px;background: #-color_colon-;">',
                  '            <span>:</span>',
                  '        </div>',
                  '    </div>',
                  '    <div style="width: 50%;background: #-color_value-;display: inline-block;white-space: normal;word-wrap: break-word;border-radius:5px;">',
```

