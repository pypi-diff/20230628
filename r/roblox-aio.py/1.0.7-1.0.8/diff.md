# Comparing `tmp/roblox-aio.py-1.0.7.tar.gz` & `tmp/roblox-aio.py-1.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "roblox-aio.py-1.0.7.tar", last modified: Wed Jun 28 15:52:47 2023, max compression
+gzip compressed data, was "roblox-aio.py-1.0.8.tar", last modified: Wed Jun 28 15:56:10 2023, max compression
```

## Comparing `roblox-aio.py-1.0.7.tar` & `roblox-aio.py-1.0.8.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:52:47.133618 roblox-aio.py-1.0.7/
--rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:52:47.133618 roblox-aio.py-1.0.7/PKG-INFO
--rw-r--r--   0 jess      (1001) users      (100)      271 2023-06-28 15:46:44.000000 roblox-aio.py-1.0.7/README.md
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:52:47.129619 roblox-aio.py-1.0.7/roblox_aio/
--rw-r--r--   0 jess      (1001) users      (100)      287 2023-06-28 15:52:33.000000 roblox-aio.py-1.0.7/roblox_aio/__init__.py
--rw-r--r--   0 jess      (1001) users      (100)      774 2023-06-28 15:52:06.000000 roblox-aio.py-1.0.7/roblox_aio/auth.py
--rw-r--r--   0 jess      (1001) users      (100)       74 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.7/roblox_aio/endpoints.py
--rw-r--r--   0 jess      (1001) users      (100)      239 2023-06-28 15:36:58.000000 roblox-aio.py-1.0.7/roblox_aio/errors.py
--rw-r--r--   0 jess      (1001) users      (100)     1363 2023-06-28 15:51:45.000000 roblox-aio.py-1.0.7/roblox_aio/user.py
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:52:47.133618 roblox-aio.py-1.0.7/roblox_aio.py.egg-info/
--rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:52:46.000000 roblox-aio.py-1.0.7/roblox_aio.py.egg-info/PKG-INFO
--rw-r--r--   0 jess      (1001) users      (100)      308 2023-06-28 15:52:47.000000 roblox-aio.py-1.0.7/roblox_aio.py.egg-info/SOURCES.txt
--rw-r--r--   0 jess      (1001) users      (100)        1 2023-06-28 15:52:46.000000 roblox-aio.py-1.0.7/roblox_aio.py.egg-info/dependency_links.txt
--rw-r--r--   0 jess      (1001) users      (100)       20 2023-06-28 15:52:46.000000 roblox-aio.py-1.0.7/roblox_aio.py.egg-info/requires.txt
--rw-r--r--   0 jess      (1001) users      (100)       11 2023-06-28 15:52:46.000000 roblox-aio.py-1.0.7/roblox_aio.py.egg-info/top_level.txt
--rw-r--r--   0 jess      (1001) users      (100)       38 2023-06-28 15:52:47.133618 roblox-aio.py-1.0.7/setup.cfg
--rw-r--r--   0 jess      (1001) users      (100)      559 2023-06-28 15:52:26.000000 roblox-aio.py-1.0.7/setup.py
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:56:10.573169 roblox-aio.py-1.0.8/
+-rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:56:10.573169 roblox-aio.py-1.0.8/PKG-INFO
+-rw-r--r--   0 jess      (1001) users      (100)      271 2023-06-28 15:46:44.000000 roblox-aio.py-1.0.8/README.md
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:56:10.569169 roblox-aio.py-1.0.8/roblox_aio/
+-rw-r--r--   0 jess      (1001) users      (100)      287 2023-06-28 15:55:55.000000 roblox-aio.py-1.0.8/roblox_aio/__init__.py
+-rw-r--r--   0 jess      (1001) users      (100)      779 2023-06-28 15:55:38.000000 roblox-aio.py-1.0.8/roblox_aio/auth.py
+-rw-r--r--   0 jess      (1001) users      (100)       74 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.8/roblox_aio/endpoints.py
+-rw-r--r--   0 jess      (1001) users      (100)      239 2023-06-28 15:36:58.000000 roblox-aio.py-1.0.8/roblox_aio/errors.py
+-rw-r--r--   0 jess      (1001) users      (100)     1363 2023-06-28 15:51:45.000000 roblox-aio.py-1.0.8/roblox_aio/user.py
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:56:10.569169 roblox-aio.py-1.0.8/roblox_aio.py.egg-info/
+-rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:56:10.000000 roblox-aio.py-1.0.8/roblox_aio.py.egg-info/PKG-INFO
+-rw-r--r--   0 jess      (1001) users      (100)      308 2023-06-28 15:56:10.000000 roblox-aio.py-1.0.8/roblox_aio.py.egg-info/SOURCES.txt
+-rw-r--r--   0 jess      (1001) users      (100)        1 2023-06-28 15:56:10.000000 roblox-aio.py-1.0.8/roblox_aio.py.egg-info/dependency_links.txt
+-rw-r--r--   0 jess      (1001) users      (100)       20 2023-06-28 15:56:10.000000 roblox-aio.py-1.0.8/roblox_aio.py.egg-info/requires.txt
+-rw-r--r--   0 jess      (1001) users      (100)       11 2023-06-28 15:56:10.000000 roblox-aio.py-1.0.8/roblox_aio.py.egg-info/top_level.txt
+-rw-r--r--   0 jess      (1001) users      (100)       38 2023-06-28 15:56:10.573169 roblox-aio.py-1.0.8/setup.cfg
+-rw-r--r--   0 jess      (1001) users      (100)      559 2023-06-28 15:55:58.000000 roblox-aio.py-1.0.8/setup.py
```

### Comparing `roblox-aio.py-1.0.7/PKG-INFO` & `roblox-aio.py-1.0.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: roblox-aio.py
-Version: 1.0.7
+Version: 1.0.8
 Summary: A Roblox API wrapper used for getting data from Roblox API.
 Home-page: https://github.com/RainzDev/roblox-aio.py
 Author: RainzDev
 Author-email: jessrblx16@gmail.com
 License: MIT
 Description: # roblox-aio.py
         A Python package that uses aiohttp to request Roblox data.
```

### Comparing `roblox-aio.py-1.0.7/roblox_aio/auth.py` & `roblox-aio.py-1.0.8/roblox_aio/auth.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,12 +12,12 @@
 class authentication:
 	def __init__(self, cookie):
 		self.cookie = cookie
 		
 	async def get_auth(self):
 		cookies = {
 		'.ROBLOSECURITY': self.cookie 
-	}
-	headers = {"x-csrf-token": await get_csrf_token(cookie=self.cookie)}
-	async with aiohttp.ClientSession() as session:
-		async with session.get(f"https://users.roblox.com/v1/users/authenticated", cookies=cookies, headers=headers) as response:
-			return await response.json()
+		}
+		headers = {"x-csrf-token": await get_csrf_token(cookie=self.cookie)}
+		async with aiohttp.ClientSession() as session:
+			async with session.get(f"https://users.roblox.com/v1/users/authenticated", cookies=cookies, headers=headers) as response:
+				return await response.json()
```

### Comparing `roblox-aio.py-1.0.7/roblox_aio/user.py` & `roblox-aio.py-1.0.8/roblox_aio/user.py`

 * *Files identical despite different names*

### Comparing `roblox-aio.py-1.0.7/roblox_aio.py.egg-info/PKG-INFO` & `roblox-aio.py-1.0.8/roblox_aio.py.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: roblox-aio.py
-Version: 1.0.7
+Version: 1.0.8
 Summary: A Roblox API wrapper used for getting data from Roblox API.
 Home-page: https://github.com/RainzDev/roblox-aio.py
 Author: RainzDev
 Author-email: jessrblx16@gmail.com
 License: MIT
 Description: # roblox-aio.py
         A Python package that uses aiohttp to request Roblox data.
```

### Comparing `roblox-aio.py-1.0.7/setup.py` & `roblox-aio.py-1.0.8/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name='roblox-aio.py',
-    version='1.0.7',
+    version='1.0.8',
     url="https://github.com/RainzDev/roblox-aio.py",
     description='A Roblox API wrapper used for getting data from Roblox API.',
     long_description=long_description,
     long_description_content_type="text/markdown",
     author='RainzDev',
     author_email='jessrblx16@gmail.com',
     license='MIT',
```

