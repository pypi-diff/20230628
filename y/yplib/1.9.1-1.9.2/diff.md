# Comparing `tmp/yplib-1.9.1.tar.gz` & `tmp/yplib-1.9.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\yplib-1.9.1.tar", last modified: Wed Jun 28 08:18:57 2023, max compression
+gzip compressed data, was "dist\yplib-1.9.2.tar", last modified: Wed Jun 28 08:32:52 2023, max compression
```

## Comparing `yplib-1.9.1.tar` & `yplib-1.9.2.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 08:18:57.389782 yplib-1.9.1/
--rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.9.1/LICENSE
--rw-rw-rw-   0        0        0      352 2023-06-28 08:18:57.389782 yplib-1.9.1/PKG-INFO
--rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.9.1/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 08:18:57.390642 yplib-1.9.1/setup.cfg
--rw-rw-rw-   0        0        0      513 2023-06-28 08:18:37.000000 yplib-1.9.1/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 08:18:57.386839 yplib-1.9.1/yplib/
--rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.9.1/yplib/__init__.py
--rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.9.1/yplib/chart.py
--rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.9.1/yplib/chart_html.py
--rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.9.1/yplib/db.py
--rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.9.1/yplib/file.py
--rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.9.1/yplib/http_util.py
--rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.9.1/yplib/index.py
--rw-rw-rw-   0        0        0     3805 2023-06-28 08:00:53.000000 yplib-1.9.1/yplib/mail.py
--rw-rw-rw-   0        0        0     3546 2023-06-28 08:18:28.000000 yplib-1.9.1/yplib/mail_html.py
--rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.9.1/yplib/temp.py
-drwxrwxrwx   0        0        0        0 2023-06-28 08:18:57.389442 yplib-1.9.1/yplib.egg-info/
--rw-rw-rw-   0        0        0      352 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      302 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 08:18:57.000000 yplib-1.9.1/yplib.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 08:32:52.314699 yplib-1.9.2/
+-rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.9.2/LICENSE
+-rw-rw-rw-   0        0        0      352 2023-06-28 08:32:52.314581 yplib-1.9.2/PKG-INFO
+-rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.9.2/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:32:52.315200 yplib-1.9.2/setup.cfg
+-rw-rw-rw-   0        0        0      513 2023-06-28 08:32:34.000000 yplib-1.9.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:32:52.311626 yplib-1.9.2/yplib/
+-rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.9.2/yplib/__init__.py
+-rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.9.2/yplib/chart.py
+-rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.9.2/yplib/chart_html.py
+-rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.9.2/yplib/db.py
+-rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.9.2/yplib/file.py
+-rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.9.2/yplib/http_util.py
+-rw-rw-rw-   0        0        0    26766 2023-06-28 08:30:22.000000 yplib-1.9.2/yplib/index.py
+-rw-rw-rw-   0        0        0     3805 2023-06-28 08:00:53.000000 yplib-1.9.2/yplib/mail.py
+-rw-rw-rw-   0        0        0     3546 2023-06-28 08:18:28.000000 yplib-1.9.2/yplib/mail_html.py
+-rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.9.2/yplib/temp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:32:52.313945 yplib-1.9.2/yplib.egg-info/
+-rw-rw-rw-   0        0        0      352 2023-06-28 08:32:52.000000 yplib-1.9.2/yplib.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      302 2023-06-28 08:32:52.000000 yplib-1.9.2/yplib.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:32:52.000000 yplib-1.9.2/yplib.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 08:32:52.000000 yplib-1.9.2/yplib.egg-info/top_level.txt
```

### Comparing `yplib-1.9.1/LICENSE` & `yplib-1.9.2/LICENSE`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/setup.py` & `yplib-1.9.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
   long_description = fh.read()
 
 setuptools.setup(
   name="yplib",
-  version="1.9.1",
+  version="1.9.2",
   author="yangpu",
   author_email="wantwaterfish@gmail.com",
   description="util",
   long_description=long_description,
   long_description_content_type="text/markdown",
   packages=setuptools.find_packages(),
   classifiers=[
```

### Comparing `yplib-1.9.1/yplib/__init__.py` & `yplib-1.9.2/yplib/__init__.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/yplib/chart.py` & `yplib-1.9.2/yplib/chart.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/yplib/chart_html.py` & `yplib-1.9.2/yplib/chart_html.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/yplib/db.py` & `yplib-1.9.2/yplib/db.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/yplib/file.py` & `yplib-1.9.2/yplib/file.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/yplib/http_util.py` & `yplib-1.9.2/yplib/http_util.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/yplib/index.py` & `yplib-1.9.2/yplib/index.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,19 +1,19 @@
+import hashlib
 import json
 import os
+import random
+import re
+import time
 import uuid
 from datetime import datetime
 from datetime import timedelta
 
 import xlrd
 import xlwt
-import time
-import re
-import random
-import hashlib
 
 
 # 记录日志, 如果是对象会转化为 json
 def to_log(a1='tag', a2='', a3='', a4='', a5='', a6='', a7='', a8='', a9='', a10='', a11='', a12='',
            a13='', a14='', a15='', a16='', a17='', a18='', a19='', a20=''):
     l = [a1, a2, a3, a4, a5, a6, a7, a8, a9, a10,
          a11, a12, a13, a14, a15, a16, a17, a18, a19, a20]
@@ -179,32 +179,28 @@
 # 去掉 str 中的 非数字字符, 然后, 再转化为 int
 def to_int(s):
     if s is None or s == '':
         return 0
     if isinstance(s, float):
         return int(s)
     s = ''.join(filter(lambda ch: ch in '0123456789', str(s)))
-    if s == '':
-        return 0
-    return int(s)
+    return 0 if s == '' else int(s)
 
 
 # 去掉 str 中的 非数字字符, 然后, 再转化为 float
 def to_float(s):
     if s is None or s == '':
         return 0.0
     s = ''.join(filter(lambda ch: ch in '0123456789.', str(s)))
-    if s == '':
-        return 0.0
-    return float(s)
+    return 0.0 if s == '' else float(s)
 
 
-def to_datetime(s=None, return_str=False):
+def to_datetime(s=None, r_str=False):
     if s is None or s == '':
-        return datetime.today()
+        return str(datetime.today()) if r_str else datetime.today()
     s = str(s)
     r = None
     m_s = {
         "^\\d{4}$": "%Y",
         "^\\d{4}-\\d{1,2}$": "%Y-%m",
         "^\\d{4}-\\d{1,2}-\\d{1,2}$": "%Y-%m-%d",
         "^\\d{4}-\\d{1,2}-\\d{1,2} {1}\\d{1,2}$": "%Y-%m-%d %H",
@@ -220,17 +216,15 @@
         if len(s) > 10:
             s_int = int(s_int / 1000)
         time_arr = time.localtime(s_int)
         time_str = time.strftime("%Y-%m-%d %H:%M:%S", time_arr)
         r = datetime.strptime(time_str, "%Y-%m-%d %H:%M:%S")
     if r is None:
         r = datetime.today()
-    if return_str:
-        return str(r)
-    return r
+    return str(r) if r_str else r
 
 
 # 时间加几天
 def to_datetime_add(s=None, days=0, seconds=0, microseconds=0, milliseconds=0, minutes=0, hours=0, weeks=0):
     return to_datetime(s) + timedelta(days=days, seconds=seconds, microseconds=microseconds,
                                       milliseconds=milliseconds, minutes=minutes, hours=hours,
                                       weeks=weeks)
```

### Comparing `yplib-1.9.1/yplib/mail.py` & `yplib-1.9.2/yplib/mail.py`

 * *Files identical despite different names*

### Comparing `yplib-1.9.1/yplib/mail_html.py` & `yplib-1.9.2/yplib/mail_html.py`

 * *Files identical despite different names*

