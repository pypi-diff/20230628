# Comparing `tmp/waivek-0.1.5.tar.gz` & `tmp/waivek-0.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "waivek-0.1.5.tar", last modified: Tue Jun 27 16:39:31 2023, max compression
+gzip compressed data, was "waivek-0.1.6.tar", last modified: Wed Jun 28 10:07:53 2023, max compression
```

## Comparing `waivek-0.1.5.tar` & `waivek-0.1.6.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 16:39:31.875562 waivek-0.1.5/
--rw-rw-rw-   0        0        0     1470 2023-06-27 16:39:31.873567 waivek-0.1.5/PKG-INFO
--rw-rw-rw-   0        0        0     1295 2023-06-27 07:27:31.000000 waivek-0.1.5/README.md
--rw-rw-rw-   0        0        0       42 2023-06-27 16:39:31.875562 waivek-0.1.5/setup.cfg
--rw-rw-rw-   0        0        0     1575 2023-06-27 16:39:28.000000 waivek-0.1.5/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-27 16:39:31.849558 waivek-0.1.5/waivek/
--rw-rw-rw-   0        0        0      377 2023-06-26 17:09:35.000000 waivek-0.1.5/waivek/__init__.py
--rw-rw-rw-   0        0        0     5601 2023-06-26 13:00:33.000000 waivek-0.1.5/waivek/color.py
--rw-rw-rw-   0        0        0    17147 2023-06-26 13:00:47.000000 waivek-0.1.5/waivek/common.py
--rw-rw-rw-   0        0        0    18804 2023-06-26 13:00:50.000000 waivek-0.1.5/waivek/db.py
--rw-rw-rw-   0        0        0    25668 2023-06-26 13:01:04.000000 waivek-0.1.5/waivek/error.py
--rw-rw-rw-   0        0        0     4725 2023-06-26 13:01:06.000000 waivek-0.1.5/waivek/frame.py
--rw-rw-rw-   0        0        0     9044 2023-06-26 13:01:10.000000 waivek-0.1.5/waivek/get.py
--rw-rw-rw-   0        0        0    28068 2023-06-27 06:18:33.000000 waivek-0.1.5/waivek/ic.py
--rw-rw-rw-   0        0        0     6272 2023-06-26 13:01:23.000000 waivek-0.1.5/waivek/print_utils.py
--rw-rw-rw-   0        0        0     1883 2023-06-27 04:31:33.000000 waivek-0.1.5/waivek/reltools.py
--rw-rw-rw-   0        0        0     4431 2023-06-26 16:58:35.000000 waivek-0.1.5/waivek/reqs.py
--rw-rw-rw-   0        0        0     1191 2023-06-26 13:01:34.000000 waivek-0.1.5/waivek/tdd.py
--rw-rw-rw-   0        0        0      395 2023-06-26 13:01:40.000000 waivek-0.1.5/waivek/template.py
--rw-rw-rw-   0        0        0    23039 2023-06-27 07:29:46.000000 waivek-0.1.5/waivek/test.py
--rw-rw-rw-   0        0        0     3668 2023-06-25 06:42:04.000000 waivek-0.1.5/waivek/timer.py
--rw-rw-rw-   0        0        0     5908 2023-06-26 13:02:00.000000 waivek-0.1.5/waivek/trace.py
-drwxrwxrwx   0        0        0        0 2023-06-27 16:39:31.871560 waivek-0.1.5/waivek.egg-info/
--rw-rw-rw-   0        0        0     1470 2023-06-27 16:39:31.000000 waivek-0.1.5/waivek.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      427 2023-06-27 16:39:31.000000 waivek-0.1.5/waivek.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 16:39:31.000000 waivek-0.1.5/waivek.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      119 2023-06-27 16:39:31.000000 waivek-0.1.5/waivek.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-27 16:39:31.000000 waivek-0.1.5/waivek.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 10:07:53.774320 waivek-0.1.6/
+-rw-rw-rw-   0        0        0     1470 2023-06-28 10:07:53.774320 waivek-0.1.6/PKG-INFO
+-rw-rw-rw-   0        0        0     1295 2023-06-27 07:27:31.000000 waivek-0.1.6/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:07:53.774320 waivek-0.1.6/setup.cfg
+-rw-rw-rw-   0        0        0     1575 2023-06-28 09:47:28.000000 waivek-0.1.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:07:53.723655 waivek-0.1.6/waivek/
+-rw-rw-rw-   0        0        0      377 2023-06-26 17:09:35.000000 waivek-0.1.6/waivek/__init__.py
+-rw-rw-rw-   0        0        0     5601 2023-06-26 13:00:33.000000 waivek-0.1.6/waivek/color.py
+-rw-rw-rw-   0        0        0    17147 2023-06-26 13:00:47.000000 waivek-0.1.6/waivek/common.py
+-rw-rw-rw-   0        0        0    18804 2023-06-26 13:00:50.000000 waivek-0.1.6/waivek/db.py
+-rw-rw-rw-   0        0        0    25668 2023-06-26 13:01:04.000000 waivek-0.1.6/waivek/error.py
+-rw-rw-rw-   0        0        0     4725 2023-06-26 13:01:06.000000 waivek-0.1.6/waivek/frame.py
+-rw-rw-rw-   0        0        0     9088 2023-06-28 10:07:34.000000 waivek-0.1.6/waivek/get.py
+-rw-rw-rw-   0        0        0    28068 2023-06-27 06:18:33.000000 waivek-0.1.6/waivek/ic.py
+-rw-rw-rw-   0        0        0     6272 2023-06-26 13:01:23.000000 waivek-0.1.6/waivek/print_utils.py
+-rw-rw-rw-   0        0        0     1883 2023-06-27 04:31:33.000000 waivek-0.1.6/waivek/reltools.py
+-rw-rw-rw-   0        0        0     4431 2023-06-26 16:58:35.000000 waivek-0.1.6/waivek/reqs.py
+-rw-rw-rw-   0        0        0     1191 2023-06-26 13:01:34.000000 waivek-0.1.6/waivek/tdd.py
+-rw-rw-rw-   0        0        0      324 2023-06-28 10:02:01.000000 waivek-0.1.6/waivek/template.py
+-rw-rw-rw-   0        0        0    23039 2023-06-27 07:29:46.000000 waivek-0.1.6/waivek/test.py
+-rw-rw-rw-   0        0        0     3668 2023-06-25 06:42:04.000000 waivek-0.1.6/waivek/timer.py
+-rw-rw-rw-   0        0        0     5908 2023-06-26 13:02:00.000000 waivek-0.1.6/waivek/trace.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:07:53.768254 waivek-0.1.6/waivek.egg-info/
+-rw-rw-rw-   0        0        0     1470 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      427 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      119 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/top_level.txt
```

### Comparing `waivek-0.1.5/PKG-INFO` & `waivek-0.1.6/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: waivek
-Version: 0.1.5
+Version: 0.1.6
 Summary: UNKNOWN
 Home-page: UNKNOWN
 License: UNKNOWN
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
 
 Code - Print colored text
```

### Comparing `waivek-0.1.5/README.md` & `waivek-0.1.6/README.md`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/setup.py` & `waivek-0.1.6/setup.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/color.py` & `waivek-0.1.6/waivek/color.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/common.py` & `waivek-0.1.6/waivek/common.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/db.py` & `waivek-0.1.6/waivek/db.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/error.py` & `waivek-0.1.6/waivek/error.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/frame.py` & `waivek-0.1.6/waivek/frame.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/get.py` & `waivek-0.1.6/waivek/get.py`

 * *Files 1% similar despite different names*

```diff
@@ -221,23 +221,24 @@
 
 # -- END: CACHE --
 
 def aget(urls, cache=True, log=True, limit=100, url2header=lambda url: {}, url2cookie=lambda url: {}):
     # START: Configuration
 
     global DEBUG
+    from .reltools import rel2abs
     DEBUG = False
     Config.cache = cache
     Config.log = log
     Config.url2header = url2header
     Config.url2cookie = url2cookie
     Config.limit = limit
     if Config.cache:
         global connection
-        connection = db_init("aget_cache/cache.db")[1]
+        connection = db_init(rel2abs("aget_cache/cache.db"))[1]
     # END: Configuration
     if DEBUG:
         print(Code.RED + "Debug: True")
     if cache:
         objects = get_yescache(urls)
         return objects
     else:
```

### Comparing `waivek-0.1.5/waivek/ic.py` & `waivek-0.1.6/waivek/ic.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/print_utils.py` & `waivek-0.1.6/waivek/print_utils.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/reltools.py` & `waivek-0.1.6/waivek/reltools.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/reqs.py` & `waivek-0.1.6/waivek/reqs.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/tdd.py` & `waivek-0.1.6/waivek/tdd.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/test.py` & `waivek-0.1.6/waivek/test.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/timer.py` & `waivek-0.1.6/waivek/timer.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek/trace.py` & `waivek-0.1.6/waivek/trace.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.5/waivek.egg-info/PKG-INFO` & `waivek-0.1.6/waivek.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: waivek
-Version: 0.1.5
+Version: 0.1.6
 Summary: UNKNOWN
 Home-page: UNKNOWN
 License: UNKNOWN
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
 
 Code - Print colored text
```

