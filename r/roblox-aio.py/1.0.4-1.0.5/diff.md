# Comparing `tmp/roblox-aio.py-1.0.4.tar.gz` & `tmp/roblox-aio.py-1.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "roblox-aio.py-1.0.4.tar", last modified: Wed Jun 28 15:33:38 2023, max compression
+gzip compressed data, was "roblox-aio.py-1.0.5.tar", last modified: Wed Jun 28 15:43:18 2023, max compression
```

## Comparing `roblox-aio.py-1.0.4.tar` & `roblox-aio.py-1.0.5.tar`

### file list

```diff
@@ -1,16 +1,17 @@
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/
--rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/PKG-INFO
--rw-r--r--   0 jess      (1001) users      (100)      271 2023-06-25 16:05:57.000000 roblox-aio.py-1.0.4/README.md
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:33:38.900054 roblox-aio.py-1.0.4/roblox_aio/
--rw-r--r--   0 jess      (1001) users      (100)      287 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.4/roblox_aio/__init__.py
--rw-r--r--   0 jess      (1001) users      (100)      777 2023-06-25 15:19:46.000000 roblox-aio.py-1.0.4/roblox_aio/auth.py
--rw-r--r--   0 jess      (1001) users      (100)       74 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.4/roblox_aio/endpoints.py
--rw-r--r--   0 jess      (1001) users      (100)     1261 2023-06-26 10:39:09.000000 roblox-aio.py-1.0.4/roblox_aio/user.py
-drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/
--rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/PKG-INFO
--rw-r--r--   0 jess      (1001) users      (100)      287 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/SOURCES.txt
--rw-r--r--   0 jess      (1001) users      (100)        1 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/dependency_links.txt
--rw-r--r--   0 jess      (1001) users      (100)       20 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/requires.txt
--rw-r--r--   0 jess      (1001) users      (100)       11 2023-06-28 15:33:38.000000 roblox-aio.py-1.0.4/roblox_aio.py.egg-info/top_level.txt
--rw-r--r--   0 jess      (1001) users      (100)       38 2023-06-28 15:33:38.912054 roblox-aio.py-1.0.4/setup.cfg
--rw-r--r--   0 jess      (1001) users      (100)      559 2023-06-28 15:31:34.000000 roblox-aio.py-1.0.4/setup.py
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:43:18.766857 roblox-aio.py-1.0.5/
+-rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:43:18.762857 roblox-aio.py-1.0.5/PKG-INFO
+-rw-r--r--   0 jess      (1001) users      (100)      271 2023-06-25 16:05:57.000000 roblox-aio.py-1.0.5/README.md
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:43:18.762857 roblox-aio.py-1.0.5/roblox_aio/
+-rw-r--r--   0 jess      (1001) users      (100)      287 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.5/roblox_aio/__init__.py
+-rw-r--r--   0 jess      (1001) users      (100)      777 2023-06-25 15:19:46.000000 roblox-aio.py-1.0.5/roblox_aio/auth.py
+-rw-r--r--   0 jess      (1001) users      (100)       74 2023-04-27 15:19:24.000000 roblox-aio.py-1.0.5/roblox_aio/endpoints.py
+-rw-r--r--   0 jess      (1001) users      (100)      239 2023-06-28 15:36:58.000000 roblox-aio.py-1.0.5/roblox_aio/errors.py
+-rw-r--r--   0 jess      (1001) users      (100)     1372 2023-06-28 15:42:58.000000 roblox-aio.py-1.0.5/roblox_aio/user.py
+drwxr-xr-x   0 jess      (1001) users      (100)        0 2023-06-28 15:43:18.762857 roblox-aio.py-1.0.5/roblox_aio.py.egg-info/
+-rw-r--r--   0 jess      (1001) users      (100)      667 2023-06-28 15:43:18.000000 roblox-aio.py-1.0.5/roblox_aio.py.egg-info/PKG-INFO
+-rw-r--r--   0 jess      (1001) users      (100)      308 2023-06-28 15:43:18.000000 roblox-aio.py-1.0.5/roblox_aio.py.egg-info/SOURCES.txt
+-rw-r--r--   0 jess      (1001) users      (100)        1 2023-06-28 15:43:18.000000 roblox-aio.py-1.0.5/roblox_aio.py.egg-info/dependency_links.txt
+-rw-r--r--   0 jess      (1001) users      (100)       20 2023-06-28 15:43:18.000000 roblox-aio.py-1.0.5/roblox_aio.py.egg-info/requires.txt
+-rw-r--r--   0 jess      (1001) users      (100)       11 2023-06-28 15:43:18.000000 roblox-aio.py-1.0.5/roblox_aio.py.egg-info/top_level.txt
+-rw-r--r--   0 jess      (1001) users      (100)       38 2023-06-28 15:43:18.766857 roblox-aio.py-1.0.5/setup.cfg
+-rw-r--r--   0 jess      (1001) users      (100)      559 2023-06-28 15:43:08.000000 roblox-aio.py-1.0.5/setup.py
```

### Comparing `roblox-aio.py-1.0.4/PKG-INFO` & `roblox-aio.py-1.0.5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: roblox-aio.py
-Version: 1.0.4
+Version: 1.0.5
 Summary: A Roblox API wrapper used for getting data from Roblox API.
 Home-page: https://github.com/RainzDev/roblox-aio.py
 Author: RainzDev
 Author-email: jessrblx16@gmail.com
 License: MIT
 Description: # roblox-aio.py
         A Python package that uses aiohttp to request Roblox data.
```

### Comparing `roblox-aio.py-1.0.4/roblox_aio/auth.py` & `roblox-aio.py-1.0.5/roblox_aio/auth.py`

 * *Files identical despite different names*

### Comparing `roblox-aio.py-1.0.4/roblox_aio/user.py` & `roblox-aio.py-1.0.5/roblox_aio/user.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,29 +1,30 @@
 import aiohttp
+import inspect
 from .auth import authentication, get_csrf_token
-
-class InvalidDisplay(Exception):
-	def __init__(self, message):
-		self.message = message
-		super().__init__(self.message)
+from .errors import InvalidDisplay, CookieError
 
 class User:
-	def __init__(self, cookie):
+	def __init__(self, cookie: str=None):
 		self.cookie = cookie
 		
+		
 	async def change_display_name(self, name: str):
+		frame = inspect.currentframe()
+		if not self.cookie:
+			raise CookieError(f"Cookie is required for function '{inspect.getframeinfo(frame).function}'")
 		data = {"newDisplayName": name}
 		auth = authentication(cookie=self.cookie)
 		_id = await auth.get_auth()['id']
 		cookies = {
-		'.ROBLOSECURITY': self.cookie 
-	}
-	headers = {"x-csrf-token": await get_csrf_token(cookie=self.cookie)}
+			'.ROBLOSECURITY': self.cookie 
+		}
+		headers = {"x-csrf-token": await get_csrf_token(cookie=self.cookie)}
 		async with aiohttp.ClientSession() as session:
-			async with session.patch(f"https://users.roblox.com/v1/users/{_id}/display-names", json=data) as response:
+			async with session.patch(f"https://users.roblox.com/v1/users/{_id}/display-names", json=data}) as response:
 				r = await response.json()
 				if "errors" in r["data"]:
 					if r["data"]["errors"][0]["code"] == 4:
 						raise InvalidDisplay(f"String '{name}' cannot be displayed as it has been moderated")
 					elif r["data"]["errors"][0]["code"] == 3:
 						raise InvalidDisplay(f"String '{name}' contains invalid characters")
 					elif r["data"]["errors"][0]["code"] == 2:
```

### Comparing `roblox-aio.py-1.0.4/roblox_aio.py.egg-info/PKG-INFO` & `roblox-aio.py-1.0.5/roblox_aio.py.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: roblox-aio.py
-Version: 1.0.4
+Version: 1.0.5
 Summary: A Roblox API wrapper used for getting data from Roblox API.
 Home-page: https://github.com/RainzDev/roblox-aio.py
 Author: RainzDev
 Author-email: jessrblx16@gmail.com
 License: MIT
 Description: # roblox-aio.py
         A Python package that uses aiohttp to request Roblox data.
```

### Comparing `roblox-aio.py-1.0.4/setup.py` & `roblox-aio.py-1.0.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name='roblox-aio.py',
-    version='1.0.4',
+    version='1.0.5',
     url="https://github.com/RainzDev/roblox-aio.py",
     description='A Roblox API wrapper used for getting data from Roblox API.',
     long_description=long_description,
     long_description_content_type="text/markdown",
     author='RainzDev',
     author_email='jessrblx16@gmail.com',
     license='MIT',
```

