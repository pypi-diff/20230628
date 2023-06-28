# Comparing `tmp/onecache-0.5.0.tar.gz` & `tmp/onecache-0.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "onecache-0.5.0.tar", last modified: Mon Mar 27 22:13:33 2023, max compression
+gzip compressed data, was "onecache-0.5.1.tar", last modified: Wed Jun 28 08:35:15 2023, max compression
```

## Comparing `onecache-0.5.0.tar` & `onecache-0.5.1.tar`

### file list

```diff
@@ -1,19 +1,18 @@
-drwxr-xr-x   0 sonic182   (501) staff       (20)        0 2023-03-27 22:13:33.062552 onecache-0.5.0/
--rw-r--r--   0 sonic182   (501) staff       (20)       32 2021-07-18 14:24:05.000000 onecache-0.5.0/MANIFEST.in
--rw-r--r--   0 sonic182   (501) staff       (20)     3190 2023-03-27 22:13:33.062721 onecache-0.5.0/PKG-INFO
--rw-r--r--   0 sonic182   (501) staff       (20)     2447 2023-03-27 22:10:17.000000 onecache-0.5.0/README.md
-drwxr-xr-x   0 sonic182   (501) staff       (20)        0 2023-03-27 22:13:33.060278 onecache-0.5.0/onecache/
--rw-r--r--   0 sonic182   (501) staff       (20)     8123 2023-03-27 22:10:17.000000 onecache-0.5.0/onecache/__init__.py
--rw-r--r--   0 sonic182   (501) staff       (20)   243432 2023-03-27 22:13:30.000000 onecache-0.5.0/onecache/cache_value.c
--rw-r--r--   0 sonic182   (501) staff       (20)      881 2023-03-27 22:10:17.000000 onecache-0.5.0/onecache/cache_value.py
--rw-r--r--   0 sonic182   (501) staff       (20)       87 2023-03-27 22:10:17.000000 onecache-0.5.0/onecache/utils.py
-drwxr-xr-x   0 sonic182   (501) staff       (20)        0 2023-03-27 22:13:33.062217 onecache-0.5.0/onecache.egg-info/
--rw-r--r--   0 sonic182   (501) staff       (20)     3190 2023-03-27 22:13:32.000000 onecache-0.5.0/onecache.egg-info/PKG-INFO
--rw-r--r--   0 sonic182   (501) staff       (20)      324 2023-03-27 22:13:32.000000 onecache-0.5.0/onecache.egg-info/SOURCES.txt
--rw-r--r--   0 sonic182   (501) staff       (20)        1 2023-03-27 22:13:32.000000 onecache-0.5.0/onecache.egg-info/dependency_links.txt
--rw-r--r--   0 sonic182   (501) staff       (20)      692 2023-03-27 22:13:32.000000 onecache-0.5.0/onecache.egg-info/requires.txt
--rw-r--r--   0 sonic182   (501) staff       (20)        9 2023-03-27 22:13:32.000000 onecache-0.5.0/onecache.egg-info/top_level.txt
--rw-r--r--   0 sonic182   (501) staff       (20)      132 2021-07-18 14:24:05.000000 onecache-0.5.0/requirements.txt
--rw-r--r--   0 sonic182   (501) staff       (20)      294 2023-03-27 22:13:33.063406 onecache-0.5.0/setup.cfg
--rw-r--r--   0 sonic182   (501) staff       (20)     2806 2023-03-27 22:12:51.000000 onecache-0.5.0/setup.py
--rw-r--r--   0 sonic182   (501) staff       (20)     2030 2023-03-27 22:10:17.000000 onecache-0.5.0/test-requirements.txt
+drwxr-xr-x   0 johanderson  (1000) johanderson  (1000)        0 2023-06-28 08:35:15.058306 onecache-0.5.1/
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)       32 2022-01-25 23:13:17.000000 onecache-0.5.1/MANIFEST.in
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)     3190 2023-06-28 08:35:15.058306 onecache-0.5.1/PKG-INFO
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)     2447 2023-03-29 16:32:11.000000 onecache-0.5.1/README.md
+drwxr-xr-x   0 johanderson  (1000) johanderson  (1000)        0 2023-06-28 08:35:15.058306 onecache-0.5.1/onecache/
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)     8156 2023-06-28 08:24:39.000000 onecache-0.5.1/onecache/__init__.py
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)      881 2023-03-29 16:32:11.000000 onecache-0.5.1/onecache/cache_value.py
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)       87 2023-03-29 16:32:11.000000 onecache-0.5.1/onecache/utils.py
+drwxr-xr-x   0 johanderson  (1000) johanderson  (1000)        0 2023-06-28 08:35:15.058306 onecache-0.5.1/onecache.egg-info/
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)     3190 2023-06-28 08:35:15.000000 onecache-0.5.1/onecache.egg-info/PKG-INFO
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)      301 2023-06-28 08:35:15.000000 onecache-0.5.1/onecache.egg-info/SOURCES.txt
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)        1 2023-06-28 08:35:15.000000 onecache-0.5.1/onecache.egg-info/dependency_links.txt
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)      692 2023-06-28 08:35:15.000000 onecache-0.5.1/onecache.egg-info/requires.txt
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)        9 2023-06-28 08:35:15.000000 onecache-0.5.1/onecache.egg-info/top_level.txt
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)      132 2022-01-25 23:13:17.000000 onecache-0.5.1/requirements.txt
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)      294 2023-06-28 08:35:15.061640 onecache-0.5.1/setup.cfg
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)     2806 2023-06-28 08:24:39.000000 onecache-0.5.1/setup.py
+-rw-r--r--   0 johanderson  (1000) johanderson  (1000)     2030 2023-03-29 16:32:11.000000 onecache-0.5.1/test-requirements.txt
```

### Comparing `onecache-0.5.0/PKG-INFO` & `onecache-0.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: onecache
-Version: 0.5.0
+Version: 0.5.1
 Summary: Python cache for sync and async code
 Home-page: UNKNOWN
 Author: Johanderson Mogollon
 Author-email: johander1822@gmail.com
 License: MIT
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `onecache-0.5.0/README.md` & `onecache-0.5.1/README.md`

 * *Files identical despite different names*

### Comparing `onecache-0.5.0/onecache/__init__.py` & `onecache-0.5.1/onecache/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -149,15 +149,17 @@
 
 class LRUCache(ExpirableCache):
     def get(self, key):
         cache_value = super().get(key, fetch_value=False)
         if cache_value:
             with self._scoped():
                 self._increment(cache_value)
-        return cache_value.value
+            return cache_value.value
+        
+        return None
 
     def _increment(self, val: CacheValue):
         val.increment()
 
     def _pop_one(self):
         ordered_cache = sorted(self.cache.items(), key=lambda item: item[1].access)
         key, _ = ordered_cache[0]
```

### Comparing `onecache-0.5.0/onecache/cache_value.py` & `onecache-0.5.1/onecache/cache_value.py`

 * *Files identical despite different names*

### Comparing `onecache-0.5.0/onecache.egg-info/PKG-INFO` & `onecache-0.5.1/onecache.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: onecache
-Version: 0.5.0
+Version: 0.5.1
 Summary: Python cache for sync and async code
 Home-page: UNKNOWN
 Author: Johanderson Mogollon
 Author-email: johander1822@gmail.com
 License: MIT
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `onecache-0.5.0/onecache.egg-info/requires.txt` & `onecache-0.5.1/onecache.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `onecache-0.5.0/setup.py` & `onecache-0.5.1/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -65,15 +65,15 @@
 def requirements(filename):
     """Parse requirements from file."""
     return [str(req) for req in parse_requirements(read_file(filename))]
 
 
 setup(
     name="onecache",
-    version="0.5.0",
+    version="0.5.1",
     description="Python cache for sync and async code",
     long_description=read_file("README.md"),
     long_description_content_type="text/markdown",
     author="Johanderson Mogollon",
     author_email="johander1822@gmail.com",
     license="MIT",
     packages=["onecache"],
```

### Comparing `onecache-0.5.0/test-requirements.txt` & `onecache-0.5.1/test-requirements.txt`

 * *Files identical despite different names*

