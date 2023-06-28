# Comparing `tmp/smartapi-python-1.3.2.tar.gz` & `tmp/smartapi-python-1.3.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "smartapi-python-1.3.2.tar", last modified: Wed Jun 28 12:15:21 2023, max compression
+gzip compressed data, was "smartapi-python-1.3.3.tar", last modified: Wed Jun 28 12:28:19 2023, max compression
```

## Comparing `smartapi-python-1.3.2.tar` & `smartapi-python-1.3.3.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/
--rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/PKG-INFO
--rw-rw-r--   0 rima      (1000) rima      (1000)     4765 2023-06-28 09:06:08.000000 smartapi-python-1.3.2/README.md
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.224074 smartapi-python-1.3.2/SmartApi/
--rw-rw-r--   0 rima      (1000) rima      (1000)      250 2023-06-19 07:12:24.000000 smartapi-python-1.3.2/SmartApi/__init__.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     5937 2023-06-19 07:12:24.000000 smartapi-python-1.3.2/SmartApi/smartApiWebsocket.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    14990 2023-06-28 08:34:24.000000 smartapi-python-1.3.2/SmartApi/smartConnect.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     2176 2023-06-19 07:12:24.000000 smartapi-python-1.3.2/SmartApi/smartExceptions.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    16867 2023-06-26 10:05:44.000000 smartapi-python-1.3.2/SmartApi/smartWebSocketV2.py
--rw-rw-r--   0 rima      (1000) rima      (1000)      541 2023-06-28 12:13:17.000000 smartapi-python-1.3.2/SmartApi/version.py
--rw-rw-r--   0 rima      (1000) rima      (1000)    15272 2023-06-28 08:19:24.000000 smartapi-python-1.3.2/SmartApi/webSocket.py
--rw-rw-r--   0 rima      (1000) rima      (1000)       38 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/setup.cfg
--rw-rw-r--   0 rima      (1000) rima      (1000)     1283 2023-06-28 12:13:03.000000 smartapi-python-1.3.2/setup.py
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.224074 smartapi-python-1.3.2/smartapi_python.egg-info/
--rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/PKG-INFO
--rw-rw-r--   0 rima      (1000) rima      (1000)      417 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/SOURCES.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)        1 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/dependency_links.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)       52 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/requires.txt
--rw-rw-r--   0 rima      (1000) rima      (1000)       14 2023-06-28 12:15:21.000000 smartapi-python-1.3.2/smartapi_python.egg-info/top_level.txt
-drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:15:21.228074 smartapi-python-1.3.2/test/
--rw-rw-r--   0 rima      (1000) rima      (1000)        0 2023-04-19 08:19:43.000000 smartapi-python-1.3.2/test/__init__.py
--rw-rw-r--   0 rima      (1000) rima      (1000)     4436 2023-06-28 09:06:08.000000 smartapi-python-1.3.2/test/test.py
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4765 2023-06-28 10:10:30.000000 smartapi-python-1.3.3/README.md
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/SmartApi/
+-rw-rw-r--   0 rima      (1000) rima      (1000)      250 2023-06-28 12:24:44.000000 smartapi-python-1.3.3/SmartApi/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5937 2023-06-19 07:12:24.000000 smartapi-python-1.3.3/SmartApi/smartApiWebsocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    15069 2023-06-28 11:09:52.000000 smartapi-python-1.3.3/SmartApi/smartConnect.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     2176 2023-06-19 07:12:24.000000 smartapi-python-1.3.3/SmartApi/smartExceptions.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    16867 2023-06-26 10:05:44.000000 smartapi-python-1.3.3/SmartApi/smartWebSocketV2.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)      541 2023-06-28 07:26:25.000000 smartapi-python-1.3.3/SmartApi/version.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    15272 2023-06-28 08:19:24.000000 smartapi-python-1.3.3/SmartApi/webSocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)       38 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/setup.cfg
+-rw-rw-r--   0 rima      (1000) rima      (1000)     1283 2023-06-28 12:26:34.000000 smartapi-python-1.3.3/setup.py
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/smartapi_python.egg-info/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)      417 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/SOURCES.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)        1 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/dependency_links.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       52 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/requires.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       14 2023-06-28 12:28:19.000000 smartapi-python-1.3.3/smartapi_python.egg-info/top_level.txt
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 12:28:19.606932 smartapi-python-1.3.3/test/
+-rw-rw-r--   0 rima      (1000) rima      (1000)        0 2023-04-19 08:19:43.000000 smartapi-python-1.3.3/test/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4436 2023-06-28 10:00:54.000000 smartapi-python-1.3.3/test/test.py
```

### Comparing `smartapi-python-1.3.2/PKG-INFO` & `smartapi-python-1.3.3/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.2
+Version: 1.3.3
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
@@ -36,15 +36,15 @@
 pip install websocket-client
 ```
 
 ## Usage
 
 ```python
 # package import statement
-from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
+from SmartApi import SmartConnect #or from SmartApi.smartConnect import SmartConnect
 import pyotp
 
 api_key = 'Your Api Key'
 clientId = 'Your Client Id'
 pwd = 'Your Pin'
 smartApi = SmartConnect(api_key)
 token = "Your QR code value"
@@ -137,15 +137,15 @@
 ```
 
 
 ## Getting started with SmartAPI Websocket's
 
 ```python
 
-from smartapi import SmartWebSocket
+from SmartApi import SmartWebSocket
 
 # feed_token=092017047
 FEED_TOKEN="YOUR_FEED_TOKEN"
 CLIENT_CODE="YOUR_CLIENT_CODE"
 # token="mcx_fo|224395"
 token="EXCHANGE|TOKEN_SYMBOL"    #SAMPLE: nse_cm|2885&nse_cm|1594&nse_cm|11536&nse_cm|3045
 # token="mcx_fo|226745&mcx_fo|220822&mcx_fo|227182&mcx_fo|221599"
@@ -175,15 +175,15 @@
 ss.connect()
 
 
 ####### Websocket sample code ended here #######
 
 ####### Websocket V2 sample code #######
 
-from smartapi.smartWebSocketV2 import SmartWebSocketV2
+from SmartApi.smartWebSocketV2 import SmartWebSocketV2
 from logzero import logger
 
 AUTH_TOKEN = "Your Auth_Token"
 API_KEY = "Your Api_Key"
 CLIENT_CODE = "Your Client Code"
 FEED_TOKEN = "Your Feed_Token"
 correlation_id = "abc123"
```

### Comparing `smartapi-python-1.3.2/README.md` & `smartapi-python-1.3.3/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 pip install websocket-client
 ```
 
 ## Usage
 
 ```python
 # package import statement
-from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
+from SmartApi import SmartConnect #or from SmartApi.smartConnect import SmartConnect
 import pyotp
 
 api_key = 'Your Api Key'
 clientId = 'Your Client Id'
 pwd = 'Your Pin'
 smartApi = SmartConnect(api_key)
 token = "Your QR code value"
@@ -114,15 +114,15 @@
 ```
 
 
 ## Getting started with SmartAPI Websocket's
 
 ```python
 
-from smartapi import SmartWebSocket
+from SmartApi import SmartWebSocket
 
 # feed_token=092017047
 FEED_TOKEN="YOUR_FEED_TOKEN"
 CLIENT_CODE="YOUR_CLIENT_CODE"
 # token="mcx_fo|224395"
 token="EXCHANGE|TOKEN_SYMBOL"    #SAMPLE: nse_cm|2885&nse_cm|1594&nse_cm|11536&nse_cm|3045
 # token="mcx_fo|226745&mcx_fo|220822&mcx_fo|227182&mcx_fo|221599"
@@ -152,15 +152,15 @@
 ss.connect()
 
 
 ####### Websocket sample code ended here #######
 
 ####### Websocket V2 sample code #######
 
-from smartapi.smartWebSocketV2 import SmartWebSocketV2
+from SmartApi.smartWebSocketV2 import SmartWebSocketV2
 from logzero import logger
 
 AUTH_TOKEN = "Your Auth_Token"
 API_KEY = "Your Api_Key"
 CLIENT_CODE = "Your Client Code"
 FEED_TOKEN = "Your Feed_Token"
 correlation_id = "abc123"
```

### Comparing `smartapi-python-1.3.2/SmartApi/smartApiWebsocket.py` & `smartapi-python-1.3.3/SmartApi/smartApiWebsocket.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.2/SmartApi/smartConnect.py` & `smartapi-python-1.3.3/SmartApi/smartConnect.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 from six.moves.urllib.parse import urljoin
 import json
 import logging
-import smartapi.smartExceptions as ex
+import SmartApi.smartExceptions as ex
 import requests
 from requests import get
 import re, uuid
 import socket
-from smartapi.version import __version__, __title__
+from SmartApi.version import __version__, __title__
 
 log = logging.getLogger(__name__)
 #user_sys=platform.system()
 #print("the system",user_sys)
 
 class SmartConnect(object):
     #_rootUrl = "https://openapisuat.angelbroking.com"
@@ -212,38 +212,39 @@
     def _postRequest(self, route, params=None):
         """Alias for sending a POST request."""
         return self._request(route, "POST", params)
     def _getRequest(self, route, params=None):
         """Alias for sending a GET request."""
         return self._request(route, "GET", params)
 
-    def generateSession(self,clientCode,password):
-        
-        params={"clientcode":clientCode,"password":password}
-        loginResultObject=self._postRequest("api.login",params)
-        
-        if loginResultObject['status']==True:
-            jwtToken=loginResultObject['data']['jwtToken']
+        def generateSession(self, clientCode, password, totp):
+
+        params = {"clientcode": clientCode, "password": password, "totp": totp}
+        loginResultObject = self._postRequest("api.login", params)
+
+        if loginResultObject['status'] == True:
+            jwtToken = loginResultObject['data']['jwtToken']
             self.setAccessToken(jwtToken)
-            refreshToken=loginResultObject['data']['refreshToken']
-            feedToken=loginResultObject['data']['feedToken']
+            refreshToken = loginResultObject['data']['refreshToken']
+            feedToken = loginResultObject['data']['feedToken']
             self.setRefreshToken(refreshToken)
             self.setFeedToken(feedToken)
-            user=self.getProfile(refreshToken)
-        
-            id=user['data']['clientcode']
-            #id='D88311'
+            user = self.getProfile(refreshToken)
+
+            id = user['data']['clientcode']
+            # id='D88311'
             self.setUserId(id)
-            user['data']['jwtToken']="Bearer "+jwtToken
-            user['data']['refreshToken']=refreshToken
+            user['data']['jwtToken'] = "Bearer " + jwtToken
+            user['data']['refreshToken'] = refreshToken
+            user['data']['feedToken'] = feedToken
 
-            
             return user
         else:
             return loginResultObject
+            
     def terminateSession(self,clientCode):
         logoutResponseObject=self._postRequest("api.logout",{"clientcode":clientCode})
         return logoutResponseObject
 
     def generateToken(self,refresh_token):
         response=self._postRequest('api.token',{"refreshToken":refresh_token})
         jwtToken=response['data']['jwtToken']
```

### Comparing `smartapi-python-1.3.2/SmartApi/smartExceptions.py` & `smartapi-python-1.3.3/SmartApi/smartExceptions.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.2/SmartApi/smartWebSocketV2.py` & `smartapi-python-1.3.3/SmartApi/smartWebSocketV2.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.2/SmartApi/version.py` & `smartapi-python-1.3.3/SmartApi/version.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 __title__ = "smartapi-python"
 __description__ = "Angel Broking openApi integration"
 __url__ = "https://www.angelbroking.com/"
 __download_url__ = "https://github.com/angelbroking-github/smartapi-python"
-__version__ = "1.3.2"
+__version__ = "1.2.9"
 __author__ = "ab-smartapi"
 __token__ = "ab-smartapi"
 __author_email__ = "smartapi.sdk@gmail.com"
 
 
 # [pypi]
 # username = __token__
```

### Comparing `smartapi-python-1.3.2/SmartApi/webSocket.py` & `smartapi-python-1.3.3/SmartApi/webSocket.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.2/setup.py` & `smartapi-python-1.3.3/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -8,15 +8,15 @@
         "requests>=2.18.4",
         "six>=1.11.0",
         "python-dateutil>=2.6.1"
     ]
 
 setup(
     name="smartapi-python",
-    version="1.3.2",
+    version="1.3.3",
     author="ab-smartapi",
     author_email="smartapi.sdk@gmail.com",
     description="Angel Broking openApi integration",
     long_description=readme,
     long_description_content_type="text/markdown",
     url="https://github.com/angelbroking-github/smartapi-python",
     packages=find_packages(),
```

### Comparing `smartapi-python-1.3.2/smartapi_python.egg-info/PKG-INFO` & `smartapi-python-1.3.3/smartapi_python.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.2
+Version: 1.3.3
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
@@ -36,15 +36,15 @@
 pip install websocket-client
 ```
 
 ## Usage
 
 ```python
 # package import statement
-from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
+from SmartApi import SmartConnect #or from SmartApi.smartConnect import SmartConnect
 import pyotp
 
 api_key = 'Your Api Key'
 clientId = 'Your Client Id'
 pwd = 'Your Pin'
 smartApi = SmartConnect(api_key)
 token = "Your QR code value"
@@ -137,15 +137,15 @@
 ```
 
 
 ## Getting started with SmartAPI Websocket's
 
 ```python
 
-from smartapi import SmartWebSocket
+from SmartApi import SmartWebSocket
 
 # feed_token=092017047
 FEED_TOKEN="YOUR_FEED_TOKEN"
 CLIENT_CODE="YOUR_CLIENT_CODE"
 # token="mcx_fo|224395"
 token="EXCHANGE|TOKEN_SYMBOL"    #SAMPLE: nse_cm|2885&nse_cm|1594&nse_cm|11536&nse_cm|3045
 # token="mcx_fo|226745&mcx_fo|220822&mcx_fo|227182&mcx_fo|221599"
@@ -175,15 +175,15 @@
 ss.connect()
 
 
 ####### Websocket sample code ended here #######
 
 ####### Websocket V2 sample code #######
 
-from smartapi.smartWebSocketV2 import SmartWebSocketV2
+from SmartApi.smartWebSocketV2 import SmartWebSocketV2
 from logzero import logger
 
 AUTH_TOKEN = "Your Auth_Token"
 API_KEY = "Your Api_Key"
 CLIENT_CODE = "Your Client Code"
 FEED_TOKEN = "Your Feed_Token"
 correlation_id = "abc123"
```

### Comparing `smartapi-python-1.3.2/test/test.py` & `smartapi-python-1.3.3/test/test.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 from logzero import logger
-from smartapi.smartConnect import SmartConnect
+from SmartApi.smartConnect import SmartConnect
 import pyotp
 
 api_key = 'Your Api Key'
 username = 'Your client code'
 pwd = 'Your pin'
 smartApi = SmartConnect(api_key)
 token = "Your QR value"
@@ -143,15 +143,15 @@
 print("Historical Data",candledetails)
 
 terminate=smartApi.terminateSession('Your client code')
 print("Connection Close",terminate)
 
 # # Websocket Programming
 
-from smartapi.smartWebSocketV2 import SmartWebSocketV2
+from SmartApi.smartWebSocketV2 import SmartWebSocketV2
 
 AUTH_TOKEN = authToken
 API_KEY = api_key
 CLIENT_CODE = username
 FEED_TOKEN = feedToken
 # correlation_id = "abc123"
 action = 1
```

