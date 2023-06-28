# Comparing `tmp/rtcshare-0.1.5.tar.gz` & `tmp/rtcshare-0.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rtcshare-0.1.5.tar", last modified: Tue Jun 27 14:23:05 2023, max compression
+gzip compressed data, was "rtcshare-0.1.6.tar", last modified: Wed Jun 28 13:36:22 2023, max compression
```

## Comparing `rtcshare-0.1.5.tar` & `rtcshare-0.1.6.tar`

### file list

```diff
@@ -1,43 +1,43 @@
-drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-27 14:23:05.652415 rtcshare-0.1.5/
--rw-rw-r--   0 magland   (1000) magland   (1000)       95 2023-06-21 16:34:30.000000 rtcshare-0.1.5/MANIFEST.in
--rw-rw-r--   0 magland   (1000) magland   (1000)      393 2023-06-27 14:23:05.652415 rtcshare-0.1.5/PKG-INFO
--rw-rw-r--   0 magland   (1000) magland   (1000)       73 2023-04-18 16:09:09.000000 rtcshare-0.1.5/README.md
-drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-27 14:23:05.644415 rtcshare-0.1.5/rtcshare/
--rw-rw-r--   0 magland   (1000) magland   (1000)      777 2023-04-26 12:03:22.000000 rtcshare-0.1.5/rtcshare/RtcshareContext.py
--rw-rw-r--   0 magland   (1000) magland   (1000)        0 2023-04-18 16:07:48.000000 rtcshare-0.1.5/rtcshare/__init__.py
--rw-rw-r--   0 magland   (1000) magland   (1000)      765 2023-04-24 11:49:33.000000 rtcshare-0.1.5/rtcshare/cli.py
--rw-rw-r--   0 magland   (1000) magland   (1000)     1478 2023-04-27 16:52:05.000000 rtcshare-0.1.5/rtcshare/handle_request.py
--rw-rw-r--   0 magland   (1000) magland   (1000)     3891 2023-06-14 01:52:37.000000 rtcshare-0.1.5/rtcshare/handle_video_query.py
--rw-rw-r--   0 magland   (1000) magland   (1000)     2437 2023-06-14 17:53:06.000000 rtcshare-0.1.5/rtcshare/handle_zarr_query.py
-drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-27 14:23:05.648415 rtcshare-0.1.5/rtcshare/js/
--rw-rw-r--   0 magland   (1000) magland   (1000)   135539 2023-06-27 14:22:01.000000 rtcshare-0.1.5/rtcshare/js/package-lock.json
--rw-rw-r--   0 magland   (1000) magland   (1000)      877 2023-04-18 16:47:58.000000 rtcshare-0.1.5/rtcshare/js/package.json
-drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-27 14:23:05.652415 rtcshare-0.1.5/rtcshare/js/src/
--rw-rw-r--   0 magland   (1000) magland   (1000)     1704 2023-05-12 14:16:51.000000 rtcshare-0.1.5/rtcshare/js/src/ConnectorHttpProxyTypes.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     4350 2023-06-08 19:25:00.000000 rtcshare-0.1.5/rtcshare/js/src/DirManager.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     5740 2023-05-12 14:16:51.000000 rtcshare-0.1.5/rtcshare/js/src/OutgoingProxyConnection.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     7598 2023-05-12 14:16:51.000000 rtcshare-0.1.5/rtcshare/js/src/RemotePeer.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)      953 2023-05-12 14:16:51.000000 rtcshare-0.1.5/rtcshare/js/src/RtcsharePeerRequest.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     5957 2023-04-26 11:55:22.000000 rtcshare-0.1.5/rtcshare/js/src/RtcshareRequest.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     6575 2023-06-14 17:52:51.000000 rtcshare-0.1.5/rtcshare/js/src/Server.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     1924 2023-05-11 21:09:20.000000 rtcshare-0.1.5/rtcshare/js/src/ServiceManager.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     2563 2023-02-15 09:52:10.000000 rtcshare-0.1.5/rtcshare/js/src/SignalCommunicator.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)      309 2023-02-14 17:47:20.000000 rtcshare-0.1.5/rtcshare/js/src/WebsocketMessage.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     1289 2023-02-16 19:46:57.000000 rtcshare-0.1.5/rtcshare/js/src/createMessageWithBinaryPayload.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     1160 2023-04-14 09:02:53.000000 rtcshare-0.1.5/rtcshare/js/src/getIceServers.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     5813 2023-05-12 18:57:29.000000 rtcshare-0.1.5/rtcshare/js/src/handleApiRequest.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)      663 2023-04-26 11:56:12.000000 rtcshare-0.1.5/rtcshare/js/src/handleServiceQueryRequest.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     1728 2023-04-18 16:50:34.000000 rtcshare-0.1.5/rtcshare/js/src/index.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)     5622 2023-02-14 17:47:20.000000 rtcshare-0.1.5/rtcshare/js/src/validateObject.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)       22 2023-02-14 17:47:20.000000 rtcshare-0.1.5/rtcshare/js/src/wrtc.d.ts
--rw-rw-r--   0 magland   (1000) magland   (1000)      186 2023-02-14 17:47:20.000000 rtcshare-0.1.5/rtcshare/js/tsconfig.json
--rw-rw-r--   0 magland   (1000) magland   (1000)     5322 2023-06-27 14:22:21.000000 rtcshare-0.1.5/rtcshare/start.py
-drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-27 14:23:05.648415 rtcshare-0.1.5/rtcshare.egg-info/
--rw-rw-r--   0 magland   (1000) magland   (1000)      393 2023-06-27 14:23:05.000000 rtcshare-0.1.5/rtcshare.egg-info/PKG-INFO
--rw-rw-r--   0 magland   (1000) magland   (1000)     1079 2023-06-27 14:23:05.000000 rtcshare-0.1.5/rtcshare.egg-info/SOURCES.txt
--rw-rw-r--   0 magland   (1000) magland   (1000)        1 2023-06-27 14:23:05.000000 rtcshare-0.1.5/rtcshare.egg-info/dependency_links.txt
--rw-rw-r--   0 magland   (1000) magland   (1000)       51 2023-06-27 14:23:05.000000 rtcshare-0.1.5/rtcshare.egg-info/entry_points.txt
--rw-rw-r--   0 magland   (1000) magland   (1000)       11 2023-06-27 14:23:05.000000 rtcshare-0.1.5/rtcshare.egg-info/requires.txt
--rw-rw-r--   0 magland   (1000) magland   (1000)        9 2023-06-27 14:23:05.000000 rtcshare-0.1.5/rtcshare.egg-info/top_level.txt
--rw-rw-r--   0 magland   (1000) magland   (1000)       38 2023-06-27 14:23:05.652415 rtcshare-0.1.5/setup.cfg
--rw-rw-r--   0 magland   (1000) magland   (1000)     2368 2023-06-27 14:22:38.000000 rtcshare-0.1.5/setup.py
+drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-28 13:36:22.142479 rtcshare-0.1.6/
+-rw-rw-r--   0 magland   (1000) magland   (1000)       95 2023-06-21 16:34:30.000000 rtcshare-0.1.6/MANIFEST.in
+-rw-rw-r--   0 magland   (1000) magland   (1000)      393 2023-06-28 13:36:22.142479 rtcshare-0.1.6/PKG-INFO
+-rw-rw-r--   0 magland   (1000) magland   (1000)       73 2023-04-18 16:09:09.000000 rtcshare-0.1.6/README.md
+drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-28 13:36:22.138479 rtcshare-0.1.6/rtcshare/
+-rw-rw-r--   0 magland   (1000) magland   (1000)      777 2023-04-26 12:03:22.000000 rtcshare-0.1.6/rtcshare/RtcshareContext.py
+-rw-rw-r--   0 magland   (1000) magland   (1000)        0 2023-04-18 16:07:48.000000 rtcshare-0.1.6/rtcshare/__init__.py
+-rw-rw-r--   0 magland   (1000) magland   (1000)      765 2023-04-24 11:49:33.000000 rtcshare-0.1.6/rtcshare/cli.py
+-rw-rw-r--   0 magland   (1000) magland   (1000)     1478 2023-04-27 16:52:05.000000 rtcshare-0.1.6/rtcshare/handle_request.py
+-rw-rw-r--   0 magland   (1000) magland   (1000)     3891 2023-06-14 01:52:37.000000 rtcshare-0.1.6/rtcshare/handle_video_query.py
+-rw-rw-r--   0 magland   (1000) magland   (1000)     2437 2023-06-14 17:53:06.000000 rtcshare-0.1.6/rtcshare/handle_zarr_query.py
+drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-28 13:36:22.138479 rtcshare-0.1.6/rtcshare/js/
+-rw-rw-r--   0 magland   (1000) magland   (1000)   135539 2023-06-27 14:22:01.000000 rtcshare-0.1.6/rtcshare/js/package-lock.json
+-rw-rw-r--   0 magland   (1000) magland   (1000)      877 2023-04-18 16:47:58.000000 rtcshare-0.1.6/rtcshare/js/package.json
+drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-28 13:36:22.142479 rtcshare-0.1.6/rtcshare/js/src/
+-rw-rw-r--   0 magland   (1000) magland   (1000)     1704 2023-05-12 14:16:51.000000 rtcshare-0.1.6/rtcshare/js/src/ConnectorHttpProxyTypes.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     4350 2023-06-08 19:25:00.000000 rtcshare-0.1.6/rtcshare/js/src/DirManager.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     5740 2023-05-12 14:16:51.000000 rtcshare-0.1.6/rtcshare/js/src/OutgoingProxyConnection.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     7598 2023-05-12 14:16:51.000000 rtcshare-0.1.6/rtcshare/js/src/RemotePeer.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)      953 2023-05-12 14:16:51.000000 rtcshare-0.1.6/rtcshare/js/src/RtcsharePeerRequest.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     5957 2023-04-26 11:55:22.000000 rtcshare-0.1.6/rtcshare/js/src/RtcshareRequest.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     6575 2023-06-14 17:52:51.000000 rtcshare-0.1.6/rtcshare/js/src/Server.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     1924 2023-05-11 21:09:20.000000 rtcshare-0.1.6/rtcshare/js/src/ServiceManager.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     2563 2023-02-15 09:52:10.000000 rtcshare-0.1.6/rtcshare/js/src/SignalCommunicator.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)      309 2023-02-14 17:47:20.000000 rtcshare-0.1.6/rtcshare/js/src/WebsocketMessage.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     1289 2023-02-16 19:46:57.000000 rtcshare-0.1.6/rtcshare/js/src/createMessageWithBinaryPayload.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     1160 2023-04-14 09:02:53.000000 rtcshare-0.1.6/rtcshare/js/src/getIceServers.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     5813 2023-05-12 18:57:29.000000 rtcshare-0.1.6/rtcshare/js/src/handleApiRequest.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)      663 2023-04-26 11:56:12.000000 rtcshare-0.1.6/rtcshare/js/src/handleServiceQueryRequest.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     1728 2023-04-18 16:50:34.000000 rtcshare-0.1.6/rtcshare/js/src/index.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)     5622 2023-02-14 17:47:20.000000 rtcshare-0.1.6/rtcshare/js/src/validateObject.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)       22 2023-02-14 17:47:20.000000 rtcshare-0.1.6/rtcshare/js/src/wrtc.d.ts
+-rw-rw-r--   0 magland   (1000) magland   (1000)      186 2023-02-14 17:47:20.000000 rtcshare-0.1.6/rtcshare/js/tsconfig.json
+-rw-rw-r--   0 magland   (1000) magland   (1000)     5687 2023-06-28 13:10:06.000000 rtcshare-0.1.6/rtcshare/start.py
+drwxrwxr-x   0 magland   (1000) magland   (1000)        0 2023-06-28 13:36:22.138479 rtcshare-0.1.6/rtcshare.egg-info/
+-rw-rw-r--   0 magland   (1000) magland   (1000)      393 2023-06-28 13:36:22.000000 rtcshare-0.1.6/rtcshare.egg-info/PKG-INFO
+-rw-rw-r--   0 magland   (1000) magland   (1000)     1079 2023-06-28 13:36:22.000000 rtcshare-0.1.6/rtcshare.egg-info/SOURCES.txt
+-rw-rw-r--   0 magland   (1000) magland   (1000)        1 2023-06-28 13:36:22.000000 rtcshare-0.1.6/rtcshare.egg-info/dependency_links.txt
+-rw-rw-r--   0 magland   (1000) magland   (1000)       51 2023-06-28 13:36:22.000000 rtcshare-0.1.6/rtcshare.egg-info/entry_points.txt
+-rw-rw-r--   0 magland   (1000) magland   (1000)       11 2023-06-28 13:36:22.000000 rtcshare-0.1.6/rtcshare.egg-info/requires.txt
+-rw-rw-r--   0 magland   (1000) magland   (1000)        9 2023-06-28 13:36:22.000000 rtcshare-0.1.6/rtcshare.egg-info/top_level.txt
+-rw-rw-r--   0 magland   (1000) magland   (1000)       38 2023-06-28 13:36:22.142479 rtcshare-0.1.6/setup.cfg
+-rw-rw-r--   0 magland   (1000) magland   (1000)     2368 2023-06-28 13:36:03.000000 rtcshare-0.1.6/setup.py
```

### Comparing `rtcshare-0.1.5/rtcshare/RtcshareContext.py` & `rtcshare-0.1.6/rtcshare/RtcshareContext.py`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/cli.py` & `rtcshare-0.1.6/rtcshare/cli.py`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/handle_request.py` & `rtcshare-0.1.6/rtcshare/handle_request.py`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/handle_video_query.py` & `rtcshare-0.1.6/rtcshare/handle_video_query.py`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/handle_zarr_query.py` & `rtcshare-0.1.6/rtcshare/handle_zarr_query.py`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/package-lock.json` & `rtcshare-0.1.6/rtcshare/js/package-lock.json`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/package.json` & `rtcshare-0.1.6/rtcshare/js/package.json`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/ConnectorHttpProxyTypes.ts` & `rtcshare-0.1.6/rtcshare/js/src/ConnectorHttpProxyTypes.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/DirManager.ts` & `rtcshare-0.1.6/rtcshare/js/src/DirManager.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/OutgoingProxyConnection.ts` & `rtcshare-0.1.6/rtcshare/js/src/OutgoingProxyConnection.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/RemotePeer.ts` & `rtcshare-0.1.6/rtcshare/js/src/RemotePeer.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/RtcsharePeerRequest.ts` & `rtcshare-0.1.6/rtcshare/js/src/RtcsharePeerRequest.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/RtcshareRequest.ts` & `rtcshare-0.1.6/rtcshare/js/src/RtcshareRequest.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/Server.ts` & `rtcshare-0.1.6/rtcshare/js/src/Server.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/ServiceManager.ts` & `rtcshare-0.1.6/rtcshare/js/src/ServiceManager.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/SignalCommunicator.ts` & `rtcshare-0.1.6/rtcshare/js/src/SignalCommunicator.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/createMessageWithBinaryPayload.ts` & `rtcshare-0.1.6/rtcshare/js/src/createMessageWithBinaryPayload.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/getIceServers.ts` & `rtcshare-0.1.6/rtcshare/js/src/getIceServers.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/handleApiRequest.ts` & `rtcshare-0.1.6/rtcshare/js/src/handleApiRequest.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/handleServiceQueryRequest.ts` & `rtcshare-0.1.6/rtcshare/js/src/handleServiceQueryRequest.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/index.ts` & `rtcshare-0.1.6/rtcshare/js/src/index.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/js/src/validateObject.ts` & `rtcshare-0.1.6/rtcshare/js/src/validateObject.ts`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/rtcshare/start.py` & `rtcshare-0.1.6/rtcshare/start.py`

 * *Files 4% similar despite different names*

```diff
@@ -83,36 +83,45 @@
 
     def start(self, *, enable_remote_access: bool = False):
         socket_server_port = self.start_socket_server()
         os.environ["RTCSHARE_SOCKET_PORT"] = str(socket_server_port)  # Pass the port number to the js server
 
         dir0 = os.environ.get('RTCSHARE_DIR')
 
+        # apparently shell=True is necessary for Windows, but shell=False is necessary for Linux
+        if os.name == 'nt':
+            shell = True
+        elif os.name == 'posix':
+            shell = False
+        else:
+            print(f'Warning: unrecognized os.name: {os.name}')
+            shell = False
+
         try:
-            npm_version = subprocess.run(["npm", "--version"], stdout=subprocess.PIPE, universal_newlines=True).stdout.strip()
+            npm_version = subprocess.run(["npm", "--version"], stdout=subprocess.PIPE, universal_newlines=True, shell=shell).stdout.strip()
             print(f'npm version: {npm_version}')
         except:
             raise Exception('Unable to run npm.')
         
         try:
-            node_version = subprocess.run(["node", "--version"], stdout=subprocess.PIPE, universal_newlines=True).stdout.strip()
+            node_version = subprocess.run(["node", "--version"], stdout=subprocess.PIPE, universal_newlines=True, shell=shell).stdout.strip()
             print(f'node version: {node_version}')
         except:
             raise Exception('Unable to run node.')
         
         # parse node_version v18.0.0 to get the major version number
         node_major_version = int(node_version.split('.')[0][1:])
         if node_major_version < 16:
             raise Exception('node version must be >= 16.0.0')
 
         # run the command npm install in the js directory
-        subprocess.run(["npm", "install"], cwd=f'{this_directory}/js')
+        subprocess.run(["npm", "install"], cwd=f'{this_directory}/js', shell=shell)
 
         # run the build command
-        subprocess.run(["npm", "run", "build"], cwd=f'{this_directory}/js')
+        subprocess.run(["npm", "run", "build"], cwd=f'{this_directory}/js', shell=shell)
 
         cmd = ["node", f'{this_directory}/js/dist/index.js', "start", "--dir", dir0, "--verbose"]
         if enable_remote_access:
             cmd.append("--enable-remote-access")
         self.process = subprocess.Popen(
             cmd,
             stdout=subprocess.PIPE,
```

### Comparing `rtcshare-0.1.5/rtcshare.egg-info/SOURCES.txt` & `rtcshare-0.1.6/rtcshare.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `rtcshare-0.1.5/setup.py` & `rtcshare-0.1.6/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 # import subprocess
 
 # read the contents of README.md
 from pathlib import Path
 this_directory = Path(__file__).parent
 long_description = (this_directory / "README.md").read_text()
 
-__version__ = '0.1.5'
+__version__ = '0.1.6'
 
 # # This will be used for both install and develop
 # def npm_install_command(command_subclass):
 #     """A decorator for classes subclassing one of the setuptools commands.
 
 #     It modifies the run() method so that it prints a friendly greeting.
 #     """
```

