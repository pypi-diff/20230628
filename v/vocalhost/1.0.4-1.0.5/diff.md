# Comparing `tmp/vocalhost-1.0.4.tar.gz` & `tmp/vocalhost-1.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "vocalhost-1.0.4.tar", last modified: Wed Jun 28 10:07:38 2023, max compression
+gzip compressed data, was "vocalhost-1.0.5.tar", last modified: Wed Jun 28 10:26:33 2023, max compression
```

## Comparing `vocalhost-1.0.4.tar` & `vocalhost-1.0.5.tar`

### file list

```diff
@@ -1,13 +1,12 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:38.554431 vocalhost-1.0.4/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:07:38.554431 vocalhost-1.0.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 10:07:28.000000 vocalhost-1.0.4/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-06-28 10:07:28.000000 vocalhost-1.0.4/receiver.py
--rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-28 10:07:28.000000 vocalhost-1.0.4/request.py
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:07:38.554431 vocalhost-1.0.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-28 10:07:28.000000 vocalhost-1.0.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:38.554431 vocalhost-1.0.4/vocalhost.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      205 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:26:33.566243 vocalhost-1.0.5/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:26:33.566243 vocalhost-1.0.5/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 10:26:16.000000 vocalhost-1.0.5/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:26:33.566243 vocalhost-1.0.5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-28 10:26:16.000000 vocalhost-1.0.5/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:26:33.562243 vocalhost-1.0.5/vocalhost.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 10:26:33.000000 vocalhost-1.0.5/vocalhost.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2010 2023-06-28 10:26:16.000000 vocalhost-1.0.5/vocalhost.py
```

### Comparing `vocalhost-1.0.4/PKG-INFO` & `vocalhost-1.0.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.4
+Version: 1.0.5
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

### Comparing `vocalhost-1.0.4/README.md` & `vocalhost-1.0.5/README.md`

 * *Files identical despite different names*

### Comparing `vocalhost-1.0.4/receiver.py` & `vocalhost-1.0.5/vocalhost.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 import asyncio
 import websockets
 import ssl
 import uuid
 import certifi
+import requests
 
 remote_url = 'wss://vocalhost.reiserx.com/'
 
 class Receiver:
     def _generate_unique_id():
         return str(uuid.uuid4())
 
@@ -38,7 +39,25 @@
             # Handle connection closure, if needed
 
         except Exception as e:
             print(f"Error occurred: {e}")
             
     def connect(self):
         asyncio.run(self._connect_to_server())
+
+
+class Request:
+    def __init__(self, api_key, receiver_id=None):
+        self.api_key = api_key
+        self.receiver_id = receiver_id
+        self.url = 'https://vocalhost.reiserx.com/'+ receiver_id +'/'
+        self.headers = {
+            'Timeout': '100',
+            'Authorization': self.api_key
+        }
+
+    def send(self, message):
+        data = {
+            'message': message
+        }
+        response = requests.post(self.url, headers=self.headers, json=data)
+        return response
```

### Comparing `vocalhost-1.0.4/vocalhost.egg-info/PKG-INFO` & `vocalhost-1.0.5/vocalhost.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.4
+Version: 1.0.5
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

