# Comparing `tmp/vocalhost-1.0.6.tar.gz` & `tmp/vocalhost-1.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "vocalhost-1.0.6.tar", last modified: Wed Jun 28 11:36:54 2023, max compression
+gzip compressed data, was "vocalhost-1.0.7.tar", last modified: Wed Jun 28 11:43:02 2023, max compression
```

## Comparing `vocalhost-1.0.6.tar` & `vocalhost-1.0.7.tar`

### file list

```diff
@@ -1,12 +1,12 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:36:54.203431 vocalhost-1.0.6/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 11:36:54.203431 vocalhost-1.0.6/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 11:36:44.000000 vocalhost-1.0.6/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:36:54.203431 vocalhost-1.0.6/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-28 11:36:44.000000 vocalhost-1.0.6/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:36:54.203431 vocalhost-1.0.6/vocalhost.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 11:36:54.000000 vocalhost-1.0.6/vocalhost.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2049 2023-06-28 11:36:44.000000 vocalhost-1.0.6/vocalhost.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:43:02.586866 vocalhost-1.0.7/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 11:43:02.586866 vocalhost-1.0.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 11:42:48.000000 vocalhost-1.0.7/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 11:43:02.586866 vocalhost-1.0.7/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-28 11:42:48.000000 vocalhost-1.0.7/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:43:02.586866 vocalhost-1.0.7/vocalhost.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 11:43:02.000000 vocalhost-1.0.7/vocalhost.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 11:43:02.000000 vocalhost-1.0.7/vocalhost.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:43:02.000000 vocalhost-1.0.7/vocalhost.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 11:43:02.000000 vocalhost-1.0.7/vocalhost.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 11:43:02.000000 vocalhost-1.0.7/vocalhost.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2057 2023-06-28 11:42:48.000000 vocalhost-1.0.7/vocalhost.py
```

### Comparing `vocalhost-1.0.6/PKG-INFO` & `vocalhost-1.0.7/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.6
+Version: 1.0.7
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

### Comparing `vocalhost-1.0.6/README.md` & `vocalhost-1.0.7/README.md`

 * *Files identical despite different names*

### Comparing `vocalhost-1.0.6/vocalhost.egg-info/PKG-INFO` & `vocalhost-1.0.7/vocalhost.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.6
+Version: 1.0.7
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

### Comparing `vocalhost-1.0.6/vocalhost.py` & `vocalhost-1.0.7/vocalhost.py`

 * *Files 2% similar despite different names*

```diff
@@ -46,15 +46,15 @@
 
 class Request:
     def __init__(self, api_key):
         self.api_key = api_key
 
     def send(self, message, receiver_id, timeout=60):
         receiver_id = str(receiver_id)
-        self.url = 'https://vocalhost.reiserx.com/'+ receiver_id +'/'
+        self.url = 'https://vocalhost.reiserx.com/connect/'+ receiver_id +'/'
         data = {
             'message': message
         }
         
         self.headers = {
             'Timeout': str(timeout),
             'Authorization': self.api_key
```

