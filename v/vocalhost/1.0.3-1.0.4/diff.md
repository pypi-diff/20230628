# Comparing `tmp/vocalhost-1.0.3.tar.gz` & `tmp/vocalhost-1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "vocalhost-1.0.3.tar", last modified: Wed Jun 28 09:40:53 2023, max compression
+gzip compressed data, was "vocalhost-1.0.4.tar", last modified: Wed Jun 28 10:07:38 2023, max compression
```

## Comparing `vocalhost-1.0.3.tar` & `vocalhost-1.0.4.tar`

### file list

```diff
@@ -1,12 +1,13 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:40:53.750968 vocalhost-1.0.3/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 09:40:53.750968 vocalhost-1.0.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 09:40:41.000000 vocalhost-1.0.3/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 09:40:53.750968 vocalhost-1.0.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      356 2023-06-28 09:40:41.000000 vocalhost-1.0.3/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:40:53.750968 vocalhost-1.0.3/vocalhost.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 09:40:53.000000 vocalhost-1.0.3/vocalhost.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      195 2023-06-28 09:40:53.000000 vocalhost-1.0.3/vocalhost.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:40:53.000000 vocalhost-1.0.3/vocalhost.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-28 09:40:53.000000 vocalhost-1.0.3/vocalhost.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 09:40:53.000000 vocalhost-1.0.3/vocalhost.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-06-28 09:40:41.000000 vocalhost-1.0.3/vocalhost.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:38.554431 vocalhost-1.0.4/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:07:38.554431 vocalhost-1.0.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 10:07:28.000000 vocalhost-1.0.4/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1491 2023-06-28 10:07:28.000000 vocalhost-1.0.4/receiver.py
+-rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-28 10:07:28.000000 vocalhost-1.0.4/request.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:07:38.554431 vocalhost-1.0.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-28 10:07:28.000000 vocalhost-1.0.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:07:38.554431 vocalhost-1.0.4/vocalhost.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      998 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      205 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 10:07:38.000000 vocalhost-1.0.4/vocalhost.egg-info/top_level.txt
```

### Comparing `vocalhost-1.0.3/PKG-INFO` & `vocalhost-1.0.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.3
+Version: 1.0.4
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

### Comparing `vocalhost-1.0.3/README.md` & `vocalhost-1.0.4/README.md`

 * *Files identical despite different names*

### Comparing `vocalhost-1.0.3/vocalhost.egg-info/PKG-INFO` & `vocalhost-1.0.4/vocalhost.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: vocalhost
-Version: 1.0.3
+Version: 1.0.4
 Description-Content-Type: text/markdown
 
 # Vocalhost-python
 Vocalhost is a communication solution that enables direct and reliable connections between systems using WebSocket protocol. It comprises a bridge server and a client agent, offering support for a wide range of languages, frameworks, and systems. This versatility allows for seamless interaction and efficient data exchange across diverse environments.
 
 The bridge server acts as a central hub, relaying real-time messages between connected systems over WebSocket connections. The client agent establishes a WebSocket connection with the bridge server, facilitating communication across various platforms.
```

### Comparing `vocalhost-1.0.3/vocalhost.py` & `vocalhost-1.0.4/receiver.py`

 * *Files identical despite different names*

