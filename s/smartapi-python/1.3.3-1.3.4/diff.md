# Comparing `tmp/smartapi-python-1.3.3.tar.gz` & `tmp/smartapi-python-1.3.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "smartapi-python-1.3.3.tar", last modified: Wed Jun 28 12:28:19 2023, max compression
+gzip compressed data, was "smartapi-python-1.3.4.tar", last modified: Wed Jun 28 12:57:17 2023, max compression
```

## Comparing `smartapi-python-1.3.3.tar` & `smartapi-python-1.3.4.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/
--rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/PKG-INFO
--rw-rw-r--   0 rima      (1000) rima      (1000)     4765 2023-06-28 10:10:30.000000 smartapi-python-1.3.3/README.md
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/SmartApi/
--rw-rw-r--   0 rima      (1000) rima      (1000)      250 2023-06-28 12:24:44.000000 smartapi-python-1.3.3/SmartApi/__init__.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     5937 2023-06-19 07:12:24.000000 smartapi-python-1.3.3/SmartApi/smartApiWebsocket.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    15069 2023-06-28 11:09:52.000000 smartapi-python-1.3.3/SmartApi/smartConnect.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     2176 2023-06-19 07:12:24.000000 smartapi-python-1.3.3/SmartApi/smartExceptions.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    16867 2023-06-26 10:05:44.000000 smartapi-python-1.3.3/SmartApi/smartWebSocketV2.py
--rw-rw-r--   0 rima      (1000) rima      (1000)      541 2023-06-28 07:26:25.000000 smartapi-python-1.3.3/SmartApi/version.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    15272 2023-06-28 08:19:24.000000 smartapi-python-1.3.3/SmartApi/webSocket.py
--rw-rw-r--   0 rima      (1000) rima      (1000)       38 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/setup.cfg
--rw-rw-r--   0 rima      (1000) rima      (1000)     1283 2023-06-28 12:26:34.000000 smartapi-python-1.3.3/setup.py
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/smartapi_python.egg-info/
--rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/PKG-INFO
--rw-rw-r--   0 rima      (1000) rima      (1000)      417 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/SOURCES.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)        1 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/dependency_links.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)       52 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/requires.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)       14 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/top_level.txt
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/test/
--rw-rw-r--   0 rima      (1000) rima      (1000)        0 2023-04-19 08:19:43.000000 smartapi-python-1.3.3/test/__init__.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     4436 2023-06-28 10:00:54.000000 smartapi-python-1.3.3/test/test.py
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:57:17.892564 smartapi-python-1.3.4/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:57:17.892564 smartapi-python-1.3.4/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4765 2023-06-28 10:10:30.000000 smartapi-python-1.3.4/README.md
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:57:17.892564 smartapi-python-1.3.4/SmartApi/
+-rw-rw-r--   0 rima      (1000) rima      (1000)      250 2023-06-28 12:24:44.000000 smartapi-python-1.3.4/SmartApi/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5937 2023-06-19 07:12:24.000000 smartapi-python-1.3.4/SmartApi/smartApiWebsocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    15065 2023-06-28 12:39:21.000000 smartapi-python-1.3.4/SmartApi/smartConnect.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     2176 2023-06-19 07:12:24.000000 smartapi-python-1.3.4/SmartApi/smartExceptions.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    16867 2023-06-26 10:05:44.000000 smartapi-python-1.3.4/SmartApi/smartWebSocketV2.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)      541 2023-06-28 12:54:30.000000 smartapi-python-1.3.4/SmartApi/version.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    15272 2023-06-28 08:19:24.000000 smartapi-python-1.3.4/SmartApi/webSocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)       38 2023-06-28 12:57:17.892564 smartapi-python-1.3.4/setup.cfg
+-rw-rw-r--   0 rima      (1000) rima      (1000)     1283 2023-06-28 12:54:18.000000 smartapi-python-1.3.4/setup.py
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:57:17.892564 smartapi-python-1.3.4/smartapi_python.egg-info/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:57:17.000000 smartapi-python-1.3.4/smartapi_python.egg-info/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)      417 2023-06-28 12:57:17.000000 smartapi-python-1.3.4/smartapi_python.egg-info/SOURCES.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)        1 2023-06-28 12:57:17.000000 smartapi-python-1.3.4/smartapi_python.egg-info/dependency_links.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       52 2023-06-28 12:57:17.000000 smartapi-python-1.3.4/smartapi_python.egg-info/requires.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       14 2023-06-28 12:57:17.000000 smartapi-python-1.3.4/smartapi_python.egg-info/top_level.txt
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:57:17.892564 smartapi-python-1.3.4/test/
+-rw-rw-r--   0 rima      (1000) rima      (1000)        0 2023-04-19 08:19:43.000000 smartapi-python-1.3.4/test/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4436 2023-06-28 10:00:54.000000 smartapi-python-1.3.4/test/test.py
```

### Comparing `smartapi-python-1.3.3/PKG-INFO` & `smartapi-python-1.3.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.3
+Version: 1.3.4
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `smartapi-python-1.3.3/README.md` & `smartapi-python-1.3.4/README.md`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.3/SmartApi/smartApiWebsocket.py` & `smartapi-python-1.3.4/SmartApi/smartApiWebsocket.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.3/SmartApi/smartConnect.py` & `smartapi-python-1.3.4/SmartApi/smartConnect.py`

 * *Files 0% similar despite different names*

```diff
@@ -212,15 +212,15 @@
     def _postRequest(self, route, params=None):
         """Alias for sending a POST request."""
         return self._request(route, "POST", params)
     def _getRequest(self, route, params=None):
         """Alias for sending a GET request."""
         return self._request(route, "GET", params)
 
-        def generateSession(self, clientCode, password, totp):
+    def generateSession(self, clientCode, password, totp):
 
         params = {"clientcode": clientCode, "password": password, "totp": totp}
         loginResultObject = self._postRequest("api.login", params)
 
         if loginResultObject['status'] == True:
             jwtToken = loginResultObject['data']['jwtToken']
             self.setAccessToken(jwtToken)
```

### Comparing `smartapi-python-1.3.3/SmartApi/smartExceptions.py` & `smartapi-python-1.3.4/SmartApi/smartExceptions.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.3/SmartApi/smartWebSocketV2.py` & `smartapi-python-1.3.4/SmartApi/smartWebSocketV2.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.3/SmartApi/version.py` & `smartapi-python-1.3.4/SmartApi/version.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 __title__ = "smartapi-python"
 __description__ = "Angel Broking openApi integration"
 __url__ = "https://www.angelbroking.com/"
 __download_url__ = "https://github.com/angelbroking-github/smartapi-python"
-__version__ = "1.2.9"
+__version__ = "1.3.4"
 __author__ = "ab-smartapi"
 __token__ = "ab-smartapi"
 __author_email__ = "smartapi.sdk@gmail.com"
 
 
 # [pypi]
 # username = __token__
```

### Comparing `smartapi-python-1.3.3/SmartApi/webSocket.py` & `smartapi-python-1.3.4/SmartApi/webSocket.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.3/setup.py` & `smartapi-python-1.3.4/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -8,15 +8,15 @@
         "requests>=2.18.4",
         "six>=1.11.0",
         "python-dateutil>=2.6.1"
     ]
 
 setup(
     name="smartapi-python",
-    version="1.3.3",
+    version="1.3.4",
     author="ab-smartapi",
     author_email="smartapi.sdk@gmail.com",
     description="Angel Broking openApi integration",
     long_description=readme,
     long_description_content_type="text/markdown",
     url="https://github.com/angelbroking-github/smartapi-python",
     packages=find_packages(),
```

### Comparing `smartapi-python-1.3.3/smartapi_python.egg-info/PKG-INFO` & `smartapi-python-1.3.4/smartapi_python.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.3
+Version: 1.3.4
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
```

### Comparing `smartapi-python-1.3.3/test/test.py` & `smartapi-python-1.3.4/test/test.py`

 * *Files identical despite different names*

