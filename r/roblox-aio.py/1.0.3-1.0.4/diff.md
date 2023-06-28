# Comparing `tmp/roblox-aio.py-1.0.3.tar.gz` & `tmp/roblox-aio.py-1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "roblox-aio.py-1.0.3.tar", last modified: Mon Jun 26 10:39:23 2023, max compression
+gzip compressed data, was "roblox-aio.py-1.0.4.tar", last modified: Wed Jun 28 15:33:38 2023, max compression
```

## Comparing `roblox-aio.py-1.0.3.tar` & `roblox-aio.py-1.0.4.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-26 10:39:23.870377 roblox-aio.py-1.0.3/
--rw-r--r--   0 jess      (1001) users      (100)      633 2023-06-26 10:39:23.870377 roblox-aio.py-1.0.3/PKG-INFO
--rw-r--r--   0 jess      (1001) users      (100)      271 2023-06-25 16:05:57.000000 roblox-aio.py-1.0.3/README.md
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-26 10:39:23.870377 roblox-aio.py-1.0.3/roblox_aio/
--rw-r--r--   0 jess      (1001) users      (100)      287 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.3/roblox_aio/__init__.py
--rw-r--r--   0 jess      (1001) users      (100)      777 2023-06-25 15:19:46.000000 roblox-aio.py-1.0.3/roblox_aio/auth.py
--rw-r--r--   0 jess      (1001) users      (100)       74 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.3/roblox_aio/endpoints.py
--rw-r--r--   0 jess      (1001) users      (100)     1261 2023-06-26 10:39:09.000000 roblox-aio.py-1.0.3/roblox_aio/user.py
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-26 10:39:23.870377 roblox-aio.py-1.0.3/roblox_aio.py.egg-info/
--rw-r--r--   0 jess      (1001) users      (100)      633 2023-06-26 10:39:23.000000 roblox-aio.py-1.0.3/roblox_aio.py.egg-info/PKG-INFO
--rw-r--r--   0 jess      (1001) users      (100)      287 2023-06-26 10:39:23.000000 roblox-aio.py-1.0.3/roblox_aio.py.egg-info/SOURCES.txt
--rw-r--r--   0 jess      (1001) users      (100)        1 2023-06-26 10:39:23.000000 roblox-aio.py-1.0.3/roblox_aio.py.egg-info/dependency_links.txt
--rw-r--r--   0 jess      (1001) users      (100)       20 2023-06-26 10:39:23.000000 roblox-aio.py-1.0.3/roblox_aio.py.egg-info/requires.txt
--rw-r--r--   0 jess      (1001) users      (100)       11 2023-06-26 10:39:23.000000 roblox-aio.py-1.0.3/roblox_aio.py.egg-info/top_level.txt
--rw-r--r--   0 jess      (1001) users      (100)       38 2023-06-26 10:39:23.870377 roblox-aio.py-1.0.3/setup.cfg
--rw-r--r--   0 jess      (1001) users      (100)      506 2023-06-26 10:37:31.000000 roblox-aio.py-1.0.3/setup.py
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/
+-rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/PKG-INFO
+-rw-r--r--   0 jess      (1001) users      (100)      271 2023-06-25 16:05:57.000000 roblox-aio.py-1.0.4/README.md
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:33:38.900054 roblox-aio.py-1.0.4/roblox_aio/
+-rw-r--r--   0 jess      (1001) users      (100)      287 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.4/roblox_aio/__init__.py
+-rw-r--r--   0 jess      (1001) users      (100)      777 2023-06-25 15:19:46.000000 roblox-aio.py-1.0.4/roblox_aio/auth.py
+-rw-r--r--   0 jess      (1001) users      (100)       74 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.4/roblox_aio/endpoints.py
+-rw-r--r--   0 jess      (1001) users      (100)     1261 2023-06-26 10:39:09.000000 roblox-aio.py-1.0.4/roblox_aio/user.py
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/
+-rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/PKG-INFO
+-rw-r--r--   0 jess      (1001) users      (100)      287 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/SOURCES.txt
+-rw-r--r--   0 jess      (1001) users      (100)        1 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/dependency_links.txt
+-rw-r--r--   0 jess      (1001) users      (100)       20 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/requires.txt
+-rw-r--r--   0 jess      (1001) users      (100)       11 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/top_level.txt
+-rw-r--r--   0 jess      (1001) users      (100)       38 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/setup.cfg
+-rw-r--r--   0 jess      (1001) users      (100)      559 2023-06-28 15:31:34.000000 roblox-aio.py-1.0.4/setup.py
```

### Comparing `roblox-aio.py-1.0.3/PKG-INFO` & `roblox-aio.py-1.0.4/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 Metadata-Version: 2.1
 Name: roblox-aio.py
-Version: 1.0.3
+Version: 1.0.4
 Summary: A Roblox API wrapper used for getting data from Roblox API.
-Home-page: UNKNOWN
+Home-page: https://github.com/RainzDev/roblox-aio.py
 Author: RainzDev
 Author-email: jessrblx16@gmail.com
 License: MIT
 Description: # roblox-aio.py
         A Python package that uses aiohttp to request Roblox data.
         
         # Quick Example
```

### Comparing `roblox-aio.py-1.0.3/roblox_aio/auth.py` & `roblox-aio.py-1.0.4/roblox_aio/auth.py`

 * *Files identical despite different names*

### Comparing `roblox-aio.py-1.0.3/roblox_aio/user.py` & `roblox-aio.py-1.0.4/roblox_aio/user.py`

 * *Files identical despite different names*

### Comparing `roblox-aio.py-1.0.3/roblox_aio.py.egg-info/PKG-INFO` & `roblox-aio.py-1.0.4/roblox_aio.py.egg-info/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 Metadata-Version: 2.1
 Name: roblox-aio.py
-Version: 1.0.3
+Version: 1.0.4
 Summary: A Roblox API wrapper used for getting data from Roblox API.
-Home-page: UNKNOWN
+Home-page: https://github.com/RainzDev/roblox-aio.py
 Author: RainzDev
 Author-email: jessrblx16@gmail.com
 License: MIT
 Description: # roblox-aio.py
         A Python package that uses aiohttp to request Roblox data.
         
         # Quick Example
```

