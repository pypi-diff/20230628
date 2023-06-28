# Comparing `tmp/vocalhost-1.0.5.tar.gz` & `tmp/vocalhost-1.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "vocalhost-1.0.5.tar", last modified: Wed Jun 28 10:26:33 2023, max compression
+gzip compressed data, was "vocalhost-1.0.6.tar", last modified: Wed Jun 28 11:36:54 2023, max compression
```

## Comparing `vocalhost-1.0.5.tar` & `vocalhost-1.0.6.tar`

### file list

```diff
@@ -1,12 +1,12 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:26:33.566243 vocalhost-1.0.5/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:26:33.566243 vocalhost-1.0.5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 10:26:16.000000 vocalhost-1.0.5/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:26:33.566243 vocalhost-1.0.5/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-28 10:26:16.000000 vocalhost-1.0.5/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:26:33.562243 vocalhost-1.0.5/vocalhost.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2010 2023-06-28 10:26:16.000000 vocalhost-1.0.5/vocalhost.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:36:54.203431 vocalhost-1.0.6/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 11:36:54.203431 vocalhost-1.0.6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 11:36:44.000000 vocalhost-1.0.6/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:36:54.203431 vocalhost-1.0.6/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-28 11:36:44.000000 vocalhost-1.0.6/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:36:54.203431 vocalhost-1.0.6/vocalhost.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2049 2023-06-28 11:36:44.000000 vocalhost-1.0.6/vocalhost.py
```

### Comparing `vocalhost-1.0.5/PKG-INFO` & `vocalhost-1.0.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.5
+Version: 1.0.6
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

### Comparing `vocalhost-1.0.5/README.md` & `vocalhost-1.0.6/README.md`

 * *Files identical despite different names*

### Comparing `vocalhost-1.0.5/vocalhost.egg-info/PKG-INFO` & `vocalhost-1.0.6/vocalhost.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.5
+Version: 1.0.6
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

### Comparing `vocalhost-1.0.5/vocalhost.py` & `vocalhost-1.0.6/vocalhost.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,16 +1,14 @@
 import asyncio
 import websockets
 import ssl
 import uuid
 import certifi
 import requests
 
-remote_url = 'wss://vocalhost.reiserx.com/'
-
 class Receiver:
     def _generate_unique_id():
         return str(uuid.uuid4())
 
     def __init__(self, process_message, client_id, API_KEY):
         self.websocket = None
         self.client_id = client_id if client_id else Receiver._generate_unique_id()
@@ -23,14 +21,15 @@
             received_message = await self.websocket.recv()
             response = self.process_message(received_message)
             await self.websocket.send(response)
 
     async def _connect_to_server(self):
         ssl_context = ssl.create_default_context(cafile=certifi.where())
         ssl_context.verify_mode = ssl.CERT_REQUIRED
+        remote_url = 'wss://vocalhost.reiserx.com/'
 
         try:
             async with websockets.connect(remote_url+'ws/?client_id=' + self.client_id + '&api_key='+self.API_KEY, ssl=ssl_context) as websocket:
                 print("Connected: " + self.client_id)
                 self.websocket = websocket
                 await self.receive_message()
 
@@ -42,22 +41,24 @@
             print(f"Error occurred: {e}")
             
     def connect(self):
         asyncio.run(self._connect_to_server())
 
 
 class Request:
-    def __init__(self, api_key, receiver_id=None):
+    def __init__(self, api_key):
         self.api_key = api_key
-        self.receiver_id = receiver_id
-        self.url = 'https://vocalhost.reiserx.com/'+ receiver_id +'/'
-        self.headers = {
-            'Timeout': '100',
-            'Authorization': self.api_key
-        }
 
-    def send(self, message):
+    def send(self, message, receiver_id, timeout=60):
+        receiver_id = str(receiver_id)
+        self.url = 'https://vocalhost.reiserx.com/'+ receiver_id +'/'
         data = {
             'message': message
         }
+        
+        self.headers = {
+            'Timeout': str(timeout),
+            'Authorization': self.api_key
+        }
+        
         response = requests.post(self.url, headers=self.headers, json=data)
         return response
```

