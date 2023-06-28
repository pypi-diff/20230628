# Comparing `tmp/smartapi-python-1.3.0.tar.gz` & `tmp/smartapi-python-1.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/Users/ankur.jha/Documents/GitHub/smartapi-python/dist/tmpqz7Ys6/smartapi-python-1.3.0.tar", last modified: Sat Oct  1 13:58:30 2022, max compression
+gzip compressed data, was "smartapi-python-1.3.1.tar", last modified: Wed Jun 28 09:46:13 2023, max compression
```

## Comparing `smartapi-python-1.3.0.tar` & `smartapi-python-1.3.1.tar`

### file list

```diff
@@ -1,20 +1,22 @@
-drwxr-xr-x   0 ankur.jha   (502) staff       (20)        0 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/
--rw-r--r--   0 ankur.jha   (502) staff       (20)     5814 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/PKG-INFO
-drwxr-xr-x   0 ankur.jha   (502) staff       (20)        0 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/test/
--rw-r--r--   0 ankur.jha   (502) staff       (20)     2991 2022-07-19 08:21:18.000000 smartapi-python-1.3.0/test/test.py
--rw-r--r--   0 ankur.jha   (502) staff       (20)     3699 2022-10-01 13:46:30.000000 smartapi-python-1.3.0/README.md
-drwxr-xr-x   0 ankur.jha   (502) staff       (20)        0 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/smartapi_python.egg-info/
--rw-r--r--   0 ankur.jha   (502) staff       (20)     5814 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/smartapi_python.egg-info/PKG-INFO
--rw-r--r--   0 ankur.jha   (502) staff       (20)      371 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/smartapi_python.egg-info/SOURCES.txt
--rw-r--r--   0 ankur.jha   (502) staff       (20)       52 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/smartapi_python.egg-info/requires.txt
--rw-r--r--   0 ankur.jha   (502) staff       (20)        9 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/smartapi_python.egg-info/top_level.txt
--rw-r--r--   0 ankur.jha   (502) staff       (20)        1 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/smartapi_python.egg-info/dependency_links.txt
--rw-r--r--   0 ankur.jha   (502) staff       (20)     1280 2022-10-01 13:58:14.000000 smartapi-python-1.3.0/setup.py
-drwxr-xr-x   0 ankur.jha   (502) staff       (20)        0 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/smartapi/
--rw-r--r--   0 ankur.jha   (502) staff       (20)    15090 2022-09-30 13:39:44.000000 smartapi-python-1.3.0/smartapi/smartConnect.py
--rw-r--r--   0 ankur.jha   (502) staff       (20)      541 2022-07-19 08:21:18.000000 smartapi-python-1.3.0/smartapi/version.py
--rw-r--r--   0 ankur.jha   (502) staff       (20)     2176 2022-07-19 08:21:18.000000 smartapi-python-1.3.0/smartapi/smartExceptions.py
--rw-r--r--   0 ankur.jha   (502) staff       (20)     5937 2022-07-19 08:21:18.000000 smartapi-python-1.3.0/smartapi/smartApiWebsocket.py
--rw-r--r--   0 ankur.jha   (502) staff       (20)      250 2022-09-30 12:08:11.000000 smartapi-python-1.3.0/smartapi/__init__.py
--rw-r--r--   0 ankur.jha   (502) staff       (20)    15273 2022-07-19 08:21:18.000000 smartapi-python-1.3.0/smartapi/webSocket.py
--rw-r--r--   0 ankur.jha   (502) staff       (20)       38 2022-10-01 13:58:30.000000 smartapi-python-1.3.0/setup.cfg
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4765 2023-06-28 09:06:08.000000 smartapi-python-1.3.1/README.md
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/SmartApi/
+-rw-rw-r--   0 rima      (1000) rima      (1000)      250 2023-06-19 07:12:24.000000 smartapi-python-1.3.1/SmartApi/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5937 2023-06-19 07:12:24.000000 smartapi-python-1.3.1/SmartApi/smartApiWebsocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    14990 2023-06-28 08:34:24.000000 smartapi-python-1.3.1/SmartApi/smartConnect.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     2176 2023-06-19 07:12:24.000000 smartapi-python-1.3.1/SmartApi/smartExceptions.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    16867 2023-06-26 10:05:44.000000 smartapi-python-1.3.1/SmartApi/smartWebSocketV2.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)      541 2023-06-28 09:35:39.000000 smartapi-python-1.3.1/SmartApi/version.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)    15272 2023-06-28 08:19:24.000000 smartapi-python-1.3.1/SmartApi/webSocket.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)       38 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/setup.cfg
+-rw-rw-r--   0 rima      (1000) rima      (1000)     1283 2023-06-28 09:45:51.000000 smartapi-python-1.3.1/setup.py
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/smartapi_python.egg-info/
+-rw-rw-r--   0 rima      (1000) rima      (1000)     5709 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/PKG-INFO
+-rw-rw-r--   0 rima      (1000) rima      (1000)      417 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/SOURCES.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)        1 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/dependency_links.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       52 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/requires.txt
+-rw-rw-r--   0 rima      (1000) rima      (1000)       14 2023-06-28 09:46:13.000000 smartapi-python-1.3.1/smartapi_python.egg-info/top_level.txt
+drwxrwxr-x   0 rima      (1000) rima      (1000)        0 2023-06-28 09:46:13.742976 smartapi-python-1.3.1/test/
+-rw-rw-r--   0 rima      (1000) rima      (1000)        0 2023-04-19 08:19:43.000000 smartapi-python-1.3.1/test/__init__.py
+-rw-rw-r--   0 rima      (1000) rima      (1000)     4436 2023-06-28 09:06:08.000000 smartapi-python-1.3.1/test/test.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `smartapi-python-1.3.0/PKG-INFO` & `smartapi-python-1.3.1/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,168 +1,231 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.0
+Version: 1.3.1
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
-Description: # SMARTAPI-PYTHON
-        
-        SMARTAPI-PYTHON is a Python library for dealing AMX,that is a set of REST-like HTTP APIs that expose many capabilities required to build stock market investment and trading platforms. It lets you execute orders in real time.
-        
-        ## Installation
-        
-        Use the package manager [pip](https://pip.pypa.io/en/stable/) to install smartapi-python.
-        
-        ```bash
-        pip install smartapi-python
-        pip install websocket-client
-        ```
-        
-        ## Usage
-        
-        ```python
-        # package import statement
-        from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
-        #import smartapi.smartExceptions(for smartExceptions)
-        
-        #create object of call
-        obj=SmartConnect(api_key="your api key",
-                        #optional
-                        #access_token = "your access token",
-                        #refresh_token = "your refresh_token")
-        
-        #login api call
-        
-        data = obj.generateSession("Your Client ID","Your Password","Your totp")
-        refreshToken= data['data']['refreshToken']
-        
-        #fetch the feedtoken
-        feedToken=obj.getfeedToken()
-        
-        #fetch User Profile
-        userProfile= obj.getProfile(refreshToken)
-        #place order
-        try:
-            orderparams = {
-                "variety": "NORMAL",
-                "tradingsymbol": "SBIN-EQ",
-                "symboltoken": "3045",
-                "transactiontype": "BUY",
-                "exchange": "NSE",
-                "ordertype": "LIMIT",
-                "producttype": "INTRADAY",
-                "duration": "DAY",
-                "price": "19500",
-                "squareoff": "0",
-                "stoploss": "0",
-                "quantity": "1"
-                }
-            orderId=obj.placeOrder(orderparams)
-            print("The order id is: {}".format(orderId))
-        except Exception as e:
-            print("Order placement failed: {}".format(e.message))
-        #gtt rule creation
-        try:
-            gttCreateParams={
-                    "tradingsymbol" : "SBIN-EQ",
-                    "symboltoken" : "3045",
-                    "exchange" : "NSE", 
-                    "producttype" : "MARGIN",
-                    "transactiontype" : "BUY",
-                    "price" : 100000,
-                    "qty" : 10,
-                    "disclosedqty": 10,
-                    "triggerprice" : 200000,
-                    "timeperiod" : 365
-                }
-            rule_id=obj.gttCreateRule(gttCreateParams)
-            print("The GTT rule id is: {}".format(rule_id))
-        except Exception as e:
-            print("GTT Rule creation failed: {}".format(e.message))
-            
-        #gtt rule list
-        try:
-            status=["FORALL"] #should be a list
-            page=1
-            count=10
-            lists=obj.gttLists(status,page,count)
-        except Exception as e:
-            print("GTT Rule List failed: {}".format(e.message))
-        
-        #Historic api
-        try:
-            historicParam={
-            "exchange": "NSE",
-            "symboltoken": "3045",
-            "interval": "ONE_MINUTE",
-            "fromdate": "2021-02-08 09:00", 
-            "todate": "2021-02-08 09:16"
-            }
-            obj.getCandleData(historicParam)
-        except Exception as e:
-            print("Historic Api failed: {}".format(e.message))
-        #logout
-        try:
-            logout=obj.terminateSession('Your Client Id')
-            print("Logout Successfull")
-        except Exception as e:
-            print("Logout failed: {}".format(e.message))
-        ```
-        
-        
-        ## Getting started with SmartAPI Websocket's
-        ```python
-        
-        from smartapi import SmartWebSocket
-        
-        # feed_token=092017047
-        FEED_TOKEN="YOUR_FEED_TOKEN"
-        CLIENT_CODE="YOUR_CLIENT_CODE"
-        # token="mcx_fo|224395"
-        token="EXCHANGE|TOKEN_SYMBOL"    #SAMPLE: nse_cm|2885&nse_cm|1594&nse_cm|11536&nse_cm|3045
-        # token="mcx_fo|226745&mcx_fo|220822&mcx_fo|227182&mcx_fo|221599"
-        task="mw"   # mw|sfi|dp
-        
-        ss = SmartWebSocket(FEED_TOKEN, CLIENT_CODE)
-        
-        def on_message(ws, message):
-            print("Ticks: {}".format(message))
-            
-        def on_open(ws):
-            print("on open")
-            ss.subscribe(task,token)
-            
-        def on_error(ws, error):
-            print(error)
-            
-        def on_close(ws):
-            print("Close")
-        
-        # Assign the callbacks.
-        ss._on_open = on_open
-        ss._on_message = on_message
-        ss._on_error = on_error
-        ss._on_close = on_close
-        
-        ss.connect()
-        ```
-        
-        
-        
-        
-        
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Financial and Insurance Industry
 Classifier: Programming Language :: Python
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 2.7
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Topic :: Office/Business :: Financial :: Investment
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Software Development :: Libraries
 Description-Content-Type: text/markdown
+
+# SMARTAPI-PYTHON
+
+SMARTAPI-PYTHON is a Python library for dealing AMX,that is a set of REST-like HTTP APIs that expose many capabilities required to build stock market investment and trading platforms. It lets you execute orders in real time.
+
+
+
+## Installation
+
+Use the package manager [pip](https://pip.pypa.io/en/stable/) to install smartapi-python.
+
+```bash
+pip install smartapi-python
+pip install websocket-client
+```
+
+## Usage
+
+```python
+# package import statement
+from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
+import pyotp
+
+api_key = 'Your Api Key'
+clientId = 'Your Client Id'
+pwd = 'Your Pin'
+smartApi = SmartConnect(api_key)
+token = "Your QR code value"
+totp=pyotp.TOTP(token).now()
+correlation_id = "abc123"
+
+# login api call
+
+data = smartApi.generateSession(clientId, pwd, totp)
+# print(data)
+authToken = data['data']['jwtToken']
+refreshToken = data['data']['refreshToken']
+
+# fetch the feedtoken
+feedToken = smartApi.getfeedToken()
+
+# fetch User Profile
+res = smartApi.getProfile(refreshToken)
+smartApi.generateToken(refreshToken)
+res=res['data']['exchanges']
+
+
+#place order
+try:
+    orderparams = {
+        "variety": "NORMAL",
+        "tradingsymbol": "SBIN-EQ",
+        "symboltoken": "3045",
+        "transactiontype": "BUY",
+        "exchange": "NSE",
+        "ordertype": "LIMIT",
+        "producttype": "INTRADAY",
+        "duration": "DAY",
+        "price": "19500",
+        "squareoff": "0",
+        "stoploss": "0",
+        "quantity": "1"
+        }
+    orderId=smartApi.placeOrder(orderparams)
+    print("The order id is: {}".format(orderId))
+except Exception as e:
+    print("Order placement failed: {}".format(e.message))
+#gtt rule creation
+try:
+    gttCreateParams={
+            "tradingsymbol" : "SBIN-EQ",
+            "symboltoken" : "3045",
+            "exchange" : "NSE", 
+            "producttype" : "MARGIN",
+            "transactiontype" : "BUY",
+            "price" : 100000,
+            "qty" : 10,
+            "disclosedqty": 10,
+            "triggerprice" : 200000,
+            "timeperiod" : 365
+        }
+    rule_id=smartApi.gttCreateRule(gttCreateParams)
+    print("The GTT rule id is: {}".format(rule_id))
+except Exception as e:
+    print("GTT Rule creation failed: {}".format(e.message))
+    
+#gtt rule list
+try:
+    status=["FORALL"] #should be a list
+    page=1
+    count=10
+    lists=smartApi.gttLists(status,page,count)
+except Exception as e:
+    print("GTT Rule List failed: {}".format(e.message))
+
+#Historic api
+try:
+    historicParam={
+    "exchange": "NSE",
+    "symboltoken": "3045",
+    "interval": "ONE_MINUTE",
+    "fromdate": "2021-02-08 09:00", 
+    "todate": "2021-02-08 09:16"
+    }
+    smartApi.getCandleData(historicParam)
+except Exception as e:
+    print("Historic Api failed: {}".format(e.message))
+#logout
+try:
+    logout=smartApi.terminateSession('Your Client Id')
+    print("Logout Successfull")
+except Exception as e:
+    print("Logout failed: {}".format(e.message))
+
+```
+
+
+## Getting started with SmartAPI Websocket's
+
+```python
+
+from smartapi import SmartWebSocket
+
+# feed_token=092017047
+FEED_TOKEN="YOUR_FEED_TOKEN"
+CLIENT_CODE="YOUR_CLIENT_CODE"
+# token="mcx_fo|224395"
+token="EXCHANGE|TOKEN_SYMBOL"    #SAMPLE: nse_cm|2885&nse_cm|1594&nse_cm|11536&nse_cm|3045
+# token="mcx_fo|226745&mcx_fo|220822&mcx_fo|227182&mcx_fo|221599"
+task="mw"   # mw|sfi|dp
+
+ss = SmartWebSocket(FEED_TOKEN, CLIENT_CODE)
+
+def on_message(ws, message):
+    print("Ticks: {}".format(message))
+    
+def on_open(ws):
+    print("on open")
+    ss.subscribe(task,token)
+    
+def on_error(ws, error):
+    print(error)
+    
+def on_close(ws):
+    print("Close")
+
+# Assign the callbacks.
+ss._on_open = on_open
+ss._on_message = on_message
+ss._on_error = on_error
+ss._on_close = on_close
+
+ss.connect()
+
+
+####### Websocket sample code ended here #######
+
+####### Websocket V2 sample code #######
+
+from smartapi.smartWebSocketV2 import SmartWebSocketV2
+from logzero import logger
+
+AUTH_TOKEN = "Your Auth_Token"
+API_KEY = "Your Api_Key"
+CLIENT_CODE = "Your Client Code"
+FEED_TOKEN = "Your Feed_Token"
+correlation_id = "abc123"
+action = 1
+mode = 1
+token_list = [
+    {
+        "exchangeType": 1,
+        "tokens": ["26009"]
+    }
+]
+sws = SmartWebSocketV2(AUTH_TOKEN, API_KEY, CLIENT_CODE, FEED_TOKEN)
+
+def on_data(wsapp, message):
+    logger.info("Ticks: {}".format(message))
+    # close_connection()
+
+def on_open(wsapp):
+    logger.info("on open")
+    sws.subscribe(correlation_id, mode, token_list)
+
+def on_error(wsapp, error):
+    logger.error(error)
+
+def on_close(wsapp):
+    logger.info("Close")
+
+def close_connection():
+    sws.close_connection()
+
+
+# Assign the callbacks.
+sws.on_open = on_open
+sws.on_data = on_data
+sws.on_error = on_error
+sws.on_close = on_close
+
+sws.connect()
+
+
+```
+
+
+
+
```

### Comparing `smartapi-python-1.3.0/README.md` & `smartapi-python-1.3.1/README.md`

 * *Files 24% similar despite different names*

```diff
@@ -1,43 +1,53 @@
 # SMARTAPI-PYTHON
 
 SMARTAPI-PYTHON is a Python library for dealing AMX,that is a set of REST-like HTTP APIs that expose many capabilities required to build stock market investment and trading platforms. It lets you execute orders in real time.
 
+
+
 ## Installation
 
 Use the package manager [pip](https://pip.pypa.io/en/stable/) to install smartapi-python.
 
 ```bash
 pip install smartapi-python
 pip install websocket-client
 ```
 
 ## Usage
 
 ```python
 # package import statement
 from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
-#import smartapi.smartExceptions(for smartExceptions)
-
-#create object of call
-obj=SmartConnect(api_key="your api key",
-                #optional
-                #access_token = "your access token",
-                #refresh_token = "your refresh_token")
+import pyotp
 
-#login api call
+api_key = 'Your Api Key'
+clientId = 'Your Client Id'
+pwd = 'Your Pin'
+smartApi = SmartConnect(api_key)
+token = "Your QR code value"
+totp=pyotp.TOTP(token).now()
+correlation_id = "abc123"
+
+# login api call
+
+data = smartApi.generateSession(clientId, pwd, totp)
+# print(data)
+authToken = data['data']['jwtToken']
+refreshToken = data['data']['refreshToken']
+
+# fetch the feedtoken
+feedToken = smartApi.getfeedToken()
+
+# fetch User Profile
+res = smartApi.getProfile(refreshToken)
+smartApi.generateToken(refreshToken)
+res=res['data']['exchanges']
 
-data = obj.generateSession("Your Client ID","Your Password","Your totp")
-refreshToken= data['data']['refreshToken']
 
-#fetch the feedtoken
-feedToken=obj.getfeedToken()
-
-#fetch User Profile
-userProfile= obj.getProfile(refreshToken)
 #place order
 try:
     orderparams = {
         "variety": "NORMAL",
         "tradingsymbol": "SBIN-EQ",
         "symboltoken": "3045",
         "transactiontype": "BUY",
@@ -46,15 +56,15 @@
         "producttype": "INTRADAY",
         "duration": "DAY",
         "price": "19500",
         "squareoff": "0",
         "stoploss": "0",
         "quantity": "1"
         }
-    orderId=obj.placeOrder(orderparams)
+    orderId=smartApi.placeOrder(orderparams)
     print("The order id is: {}".format(orderId))
 except Exception as e:
     print("Order placement failed: {}".format(e.message))
 #gtt rule creation
 try:
     gttCreateParams={
             "tradingsymbol" : "SBIN-EQ",
@@ -64,50 +74,52 @@
             "transactiontype" : "BUY",
             "price" : 100000,
             "qty" : 10,
             "disclosedqty": 10,
             "triggerprice" : 200000,
             "timeperiod" : 365
         }
-    rule_id=obj.gttCreateRule(gttCreateParams)
+    rule_id=smartApi.gttCreateRule(gttCreateParams)
     print("The GTT rule id is: {}".format(rule_id))
 except Exception as e:
     print("GTT Rule creation failed: {}".format(e.message))
     
 #gtt rule list
 try:
     status=["FORALL"] #should be a list
     page=1
     count=10
-    lists=obj.gttLists(status,page,count)
+    lists=smartApi.gttLists(status,page,count)
 except Exception as e:
     print("GTT Rule List failed: {}".format(e.message))
 
 #Historic api
 try:
     historicParam={
     "exchange": "NSE",
     "symboltoken": "3045",
     "interval": "ONE_MINUTE",
     "fromdate": "2021-02-08 09:00", 
     "todate": "2021-02-08 09:16"
     }
-    obj.getCandleData(historicParam)
+    smartApi.getCandleData(historicParam)
 except Exception as e:
     print("Historic Api failed: {}".format(e.message))
 #logout
 try:
-    logout=obj.terminateSession('Your Client Id')
+    logout=smartApi.terminateSession('Your Client Id')
     print("Logout Successfull")
 except Exception as e:
     print("Logout failed: {}".format(e.message))
+
 ```
 
 
 ## Getting started with SmartAPI Websocket's
+
 ```python
 
 from smartapi import SmartWebSocket
 
 # feed_token=092017047
 FEED_TOKEN="YOUR_FEED_TOKEN"
 CLIENT_CODE="YOUR_CLIENT_CODE"
@@ -134,12 +146,61 @@
 # Assign the callbacks.
 ss._on_open = on_open
 ss._on_message = on_message
 ss._on_error = on_error
 ss._on_close = on_close
 
 ss.connect()
-```
 
 
+####### Websocket sample code ended here #######
+
+####### Websocket V2 sample code #######
+
+from smartapi.smartWebSocketV2 import SmartWebSocketV2
+from logzero import logger
+
+AUTH_TOKEN = "Your Auth_Token"
+API_KEY = "Your Api_Key"
+CLIENT_CODE = "Your Client Code"
+FEED_TOKEN = "Your Feed_Token"
+correlation_id = "abc123"
+action = 1
+mode = 1
+token_list = [
+    {
+        "exchangeType": 1,
+        "tokens": ["26009"]
+    }
+]
+sws = SmartWebSocketV2(AUTH_TOKEN, API_KEY, CLIENT_CODE, FEED_TOKEN)
+
+def on_data(wsapp, message):
+    logger.info("Ticks: {}".format(message))
+    # close_connection()
+
+def on_open(wsapp):
+    logger.info("on open")
+    sws.subscribe(correlation_id, mode, token_list)
+
+def on_error(wsapp, error):
+    logger.error(error)
+
+def on_close(wsapp):
+    logger.info("Close")
+
+def close_connection():
+    sws.close_connection()
+
+
+# Assign the callbacks.
+sws.on_open = on_open
+sws.on_data = on_data
+sws.on_error = on_error
+sws.on_close = on_close
+
+sws.connect()
+
+
+```
```

### Comparing `smartapi-python-1.3.0/smartapi_python.egg-info/PKG-INFO` & `smartapi-python-1.3.1/smartapi_python.egg-info/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,168 +1,231 @@
 Metadata-Version: 2.1
 Name: smartapi-python
-Version: 1.3.0
+Version: 1.3.1
 Summary: Angel Broking openApi integration
 Home-page: https://github.com/angelbroking-github/smartapi-python
 Author: ab-smartapi
 Author-email: smartapi.sdk@gmail.com
 License: UNKNOWN
-Description: # SMARTAPI-PYTHON
-        
-        SMARTAPI-PYTHON is a Python library for dealing AMX,that is a set of REST-like HTTP APIs that expose many capabilities required to build stock market investment and trading platforms. It lets you execute orders in real time.
-        
-        ## Installation
-        
-        Use the package manager [pip](https://pip.pypa.io/en/stable/) to install smartapi-python.
-        
-        ```bash
-        pip install smartapi-python
-        pip install websocket-client
-        ```
-        
-        ## Usage
-        
-        ```python
-        # package import statement
-        from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
-        #import smartapi.smartExceptions(for smartExceptions)
-        
-        #create object of call
-        obj=SmartConnect(api_key="your api key",
-                        #optional
-                        #access_token = "your access token",
-                        #refresh_token = "your refresh_token")
-        
-        #login api call
-        
-        data = obj.generateSession("Your Client ID","Your Password","Your totp")
-        refreshToken= data['data']['refreshToken']
-        
-        #fetch the feedtoken
-        feedToken=obj.getfeedToken()
-        
-        #fetch User Profile
-        userProfile= obj.getProfile(refreshToken)
-        #place order
-        try:
-            orderparams = {
-                "variety": "NORMAL",
-                "tradingsymbol": "SBIN-EQ",
-                "symboltoken": "3045",
-                "transactiontype": "BUY",
-                "exchange": "NSE",
-                "ordertype": "LIMIT",
-                "producttype": "INTRADAY",
-                "duration": "DAY",
-                "price": "19500",
-                "squareoff": "0",
-                "stoploss": "0",
-                "quantity": "1"
-                }
-            orderId=obj.placeOrder(orderparams)
-            print("The order id is: {}".format(orderId))
-        except Exception as e:
-            print("Order placement failed: {}".format(e.message))
-        #gtt rule creation
-        try:
-            gttCreateParams={
-                    "tradingsymbol" : "SBIN-EQ",
-                    "symboltoken" : "3045",
-                    "exchange" : "NSE", 
-                    "producttype" : "MARGIN",
-                    "transactiontype" : "BUY",
-                    "price" : 100000,
-                    "qty" : 10,
-                    "disclosedqty": 10,
-                    "triggerprice" : 200000,
-                    "timeperiod" : 365
-                }
-            rule_id=obj.gttCreateRule(gttCreateParams)
-            print("The GTT rule id is: {}".format(rule_id))
-        except Exception as e:
-            print("GTT Rule creation failed: {}".format(e.message))
-            
-        #gtt rule list
-        try:
-            status=["FORALL"] #should be a list
-            page=1
-            count=10
-            lists=obj.gttLists(status,page,count)
-        except Exception as e:
-            print("GTT Rule List failed: {}".format(e.message))
-        
-        #Historic api
-        try:
-            historicParam={
-            "exchange": "NSE",
-            "symboltoken": "3045",
-            "interval": "ONE_MINUTE",
-            "fromdate": "2021-02-08 09:00", 
-            "todate": "2021-02-08 09:16"
-            }
-            obj.getCandleData(historicParam)
-        except Exception as e:
-            print("Historic Api failed: {}".format(e.message))
-        #logout
-        try:
-            logout=obj.terminateSession('Your Client Id')
-            print("Logout Successfull")
-        except Exception as e:
-            print("Logout failed: {}".format(e.message))
-        ```
-        
-        
-        ## Getting started with SmartAPI Websocket's
-        ```python
-        
-        from smartapi import SmartWebSocket
-        
-        # feed_token=092017047
-        FEED_TOKEN="YOUR_FEED_TOKEN"
-        CLIENT_CODE="YOUR_CLIENT_CODE"
-        # token="mcx_fo|224395"
-        token="EXCHANGE|TOKEN_SYMBOL"    #SAMPLE: nse_cm|2885&nse_cm|1594&nse_cm|11536&nse_cm|3045
-        # token="mcx_fo|226745&mcx_fo|220822&mcx_fo|227182&mcx_fo|221599"
-        task="mw"   # mw|sfi|dp
-        
-        ss = SmartWebSocket(FEED_TOKEN, CLIENT_CODE)
-        
-        def on_message(ws, message):
-            print("Ticks: {}".format(message))
-            
-        def on_open(ws):
-            print("on open")
-            ss.subscribe(task,token)
-            
-        def on_error(ws, error):
-            print(error)
-            
-        def on_close(ws):
-            print("Close")
-        
-        # Assign the callbacks.
-        ss._on_open = on_open
-        ss._on_message = on_message
-        ss._on_error = on_error
-        ss._on_close = on_close
-        
-        ss.connect()
-        ```
-        
-        
-        
-        
-        
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Financial and Insurance Industry
 Classifier: Programming Language :: Python
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 2.7
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Topic :: Office/Business :: Financial :: Investment
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Software Development :: Libraries
 Description-Content-Type: text/markdown
+
+# SMARTAPI-PYTHON
+
+SMARTAPI-PYTHON is a Python library for dealing AMX,that is a set of REST-like HTTP APIs that expose many capabilities required to build stock market investment and trading platforms. It lets you execute orders in real time.
+
+
+
+## Installation
+
+Use the package manager [pip](https://pip.pypa.io/en/stable/) to install smartapi-python.
+
+```bash
+pip install smartapi-python
+pip install websocket-client
+```
+
+## Usage
+
+```python
+# package import statement
+from smartapi import SmartConnect #or from smartapi.smartConnect import SmartConnect
+import pyotp
+
+api_key = 'Your Api Key'
+clientId = 'Your Client Id'
+pwd = 'Your Pin'
+smartApi = SmartConnect(api_key)
+token = "Your QR code value"
+totp=pyotp.TOTP(token).now()
+correlation_id = "abc123"
+
+# login api call
+
+data = smartApi.generateSession(clientId, pwd, totp)
+# print(data)
+authToken = data['data']['jwtToken']
+refreshToken = data['data']['refreshToken']
+
+# fetch the feedtoken
+feedToken = smartApi.getfeedToken()
+
+# fetch User Profile
+res = smartApi.getProfile(refreshToken)
+smartApi.generateToken(refreshToken)
+res=res['data']['exchanges']
+
+
+#place order
+try:
+    orderparams = {
+        "variety": "NORMAL",
+        "tradingsymbol": "SBIN-EQ",
+        "symboltoken": "3045",
+        "transactiontype": "BUY",
+        "exchange": "NSE",
+        "ordertype": "LIMIT",
+        "producttype": "INTRADAY",
+        "duration": "DAY",
+        "price": "19500",
+        "squareoff": "0",
+        "stoploss": "0",
+        "quantity": "1"
+        }
+    orderId=smartApi.placeOrder(orderparams)
+    print("The order id is: {}".format(orderId))
+except Exception as e:
+    print("Order placement failed: {}".format(e.message))
+#gtt rule creation
+try:
+    gttCreateParams={
+            "tradingsymbol" : "SBIN-EQ",
+            "symboltoken" : "3045",
+            "exchange" : "NSE", 
+            "producttype" : "MARGIN",
+            "transactiontype" : "BUY",
+            "price" : 100000,
+            "qty" : 10,
+            "disclosedqty": 10,
+            "triggerprice" : 200000,
+            "timeperiod" : 365
+        }
+    rule_id=smartApi.gttCreateRule(gttCreateParams)
+    print("The GTT rule id is: {}".format(rule_id))
+except Exception as e:
+    print("GTT Rule creation failed: {}".format(e.message))
+    
+#gtt rule list
+try:
+    status=["FORALL"] #should be a list
+    page=1
+    count=10
+    lists=smartApi.gttLists(status,page,count)
+except Exception as e:
+    print("GTT Rule List failed: {}".format(e.message))
+
+#Historic api
+try:
+    historicParam={
+    "exchange": "NSE",
+    "symboltoken": "3045",
+    "interval": "ONE_MINUTE",
+    "fromdate": "2021-02-08 09:00", 
+    "todate": "2021-02-08 09:16"
+    }
+    smartApi.getCandleData(historicParam)
+except Exception as e:
+    print("Historic Api failed: {}".format(e.message))
+#logout
+try:
+    logout=smartApi.terminateSession('Your Client Id')
+    print("Logout Successfull")
+except Exception as e:
+    print("Logout failed: {}".format(e.message))
+
+```
+
+
+## Getting started with SmartAPI Websocket's
+
+```python
+
+from smartapi import SmartWebSocket
+
+# feed_token=092017047
+FEED_TOKEN="YOUR_FEED_TOKEN"
+CLIENT_CODE="YOUR_CLIENT_CODE"
+# token="mcx_fo|224395"
+token="EXCHANGE|TOKEN_SYMBOL"    #SAMPLE: nse_cm|2885&nse_cm|1594&nse_cm|11536&nse_cm|3045
+# token="mcx_fo|226745&mcx_fo|220822&mcx_fo|227182&mcx_fo|221599"
+task="mw"   # mw|sfi|dp
+
+ss = SmartWebSocket(FEED_TOKEN, CLIENT_CODE)
+
+def on_message(ws, message):
+    print("Ticks: {}".format(message))
+    
+def on_open(ws):
+    print("on open")
+    ss.subscribe(task,token)
+    
+def on_error(ws, error):
+    print(error)
+    
+def on_close(ws):
+    print("Close")
+
+# Assign the callbacks.
+ss._on_open = on_open
+ss._on_message = on_message
+ss._on_error = on_error
+ss._on_close = on_close
+
+ss.connect()
+
+
+####### Websocket sample code ended here #######
+
+####### Websocket V2 sample code #######
+
+from smartapi.smartWebSocketV2 import SmartWebSocketV2
+from logzero import logger
+
+AUTH_TOKEN = "Your Auth_Token"
+API_KEY = "Your Api_Key"
+CLIENT_CODE = "Your Client Code"
+FEED_TOKEN = "Your Feed_Token"
+correlation_id = "abc123"
+action = 1
+mode = 1
+token_list = [
+    {
+        "exchangeType": 1,
+        "tokens": ["26009"]
+    }
+]
+sws = SmartWebSocketV2(AUTH_TOKEN, API_KEY, CLIENT_CODE, FEED_TOKEN)
+
+def on_data(wsapp, message):
+    logger.info("Ticks: {}".format(message))
+    # close_connection()
+
+def on_open(wsapp):
+    logger.info("on open")
+    sws.subscribe(correlation_id, mode, token_list)
+
+def on_error(wsapp, error):
+    logger.error(error)
+
+def on_close(wsapp):
+    logger.info("Close")
+
+def close_connection():
+    sws.close_connection()
+
+
+# Assign the callbacks.
+sws.on_open = on_open
+sws.on_data = on_data
+sws.on_error = on_error
+sws.on_close = on_close
+
+sws.connect()
+
+
+```
+
+
+
+
```

### Comparing `smartapi-python-1.3.0/setup.py` & `smartapi-python-1.3.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,30 +1,29 @@
-
 from setuptools import setup, find_packages
 
 about={}
 with open("README.md", "r") as readme_file:
     readme = readme_file.read()
 
 requirements = [
         "requests>=2.18.4",
         "six>=1.11.0",
         "python-dateutil>=2.6.1"
     ]
 
 setup(
     name="smartapi-python",
-    version="1.3.0",
+    version="1.3.1",
     author="ab-smartapi",
     author_email="smartapi.sdk@gmail.com",
     description="Angel Broking openApi integration",
     long_description=readme,
     long_description_content_type="text/markdown",
     url="https://github.com/angelbroking-github/smartapi-python",
-    packages=["smartapi"],
+    packages=find_packages(),
     install_requires=requirements,
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Intended Audience :: Financial and Insurance Industry",
         "Programming Language :: Python",
         "Natural Language :: English",
@@ -32,8 +31,8 @@
         "Programming Language :: Python :: 3.5",
         "Programming Language :: Python :: 3.6",
         "Programming Language :: Python :: 3.7",
         "Topic :: Office/Business :: Financial :: Investment",
         "Topic :: Software Development :: Libraries :: Python Modules",
         "Topic :: Software Development :: Libraries"
     ],
-)
+)
```

### Comparing `smartapi-python-1.3.0/smartapi/smartConnect.py` & `smartapi-python-1.3.1/SmartApi/smartConnect.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,21 +1,15 @@
 from six.moves.urllib.parse import urljoin
-import sys
-import csv
 import json
-import dateutil.parser
-import hashlib
 import logging
-import datetime
 import smartapi.smartExceptions as ex
 import requests
 from requests import get
 import re, uuid
 import socket
-import platform
 from smartapi.version import __version__, __title__
 
 log = logging.getLogger(__name__)
 #user_sys=platform.system()
 #print("the system",user_sys)
 
 class SmartConnect(object):
@@ -115,16 +109,16 @@
         }
 
     def setSessionExpiryHook(self, method):
         if not callable(method):
             raise TypeError("Invalid input type. Only functions are accepted.")
         self.session_expiry_hook = method
     
-    def getUserId():
-        return userId
+    def getUserId(self):
+        return self.userId
 
     def setUserId(self,id):
         self.userId=id
 
     def setAccessToken(self, access_token):
 
         self.access_token = access_token
@@ -218,17 +212,17 @@
     def _postRequest(self, route, params=None):
         """Alias for sending a POST request."""
         return self._request(route, "POST", params)
     def _getRequest(self, route, params=None):
         """Alias for sending a GET request."""
         return self._request(route, "GET", params)
 
-    def generateSession(self,clientCode,password,totp):
+    def generateSession(self,clientCode,password):
         
-        params={"clientcode":clientCode,"password":password,"totp":totp}
+        params={"clientcode":clientCode,"password":password}
         loginResultObject=self._postRequest("api.login",params)
         
         if loginResultObject['status']==True:
             jwtToken=loginResultObject['data']['jwtToken']
             self.setAccessToken(jwtToken)
             refreshToken=loginResultObject['data']['refreshToken']
             feedToken=loginResultObject['data']['feedToken']
```

### Comparing `smartapi-python-1.3.0/smartapi/version.py` & `smartapi-python-1.3.1/SmartApi/version.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 __title__ = "smartapi-python"
 __description__ = "Angel Broking openApi integration"
 __url__ = "https://www.angelbroking.com/"
 __download_url__ = "https://github.com/angelbroking-github/smartapi-python"
-__version__ = "1.2.6"
+__version__ = "1.3.0"
 __author__ = "ab-smartapi"
 __token__ = "ab-smartapi"
 __author_email__ = "smartapi.sdk@gmail.com"
 
 
 # [pypi]
 # username = __token__
```

### Comparing `smartapi-python-1.3.0/smartapi/smartExceptions.py` & `smartapi-python-1.3.1/SmartApi/smartExceptions.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.0/smartapi/smartApiWebsocket.py` & `smartapi-python-1.3.1/SmartApi/smartApiWebsocket.py`

 * *Files identical despite different names*

### Comparing `smartapi-python-1.3.0/smartapi/webSocket.py` & `smartapi-python-1.3.1/SmartApi/webSocket.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,7 @@
-
 import six
 import sys
 import time
 import json
 import struct
 import logging
 import threading
```

