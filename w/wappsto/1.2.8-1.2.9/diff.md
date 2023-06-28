# Comparing `tmp/wappsto-1.2.8.tar.gz` & `tmp/wappsto-1.2.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/wappsto-1.2.8.tar", last modified: Mon Mar 15 10:02:22 2021, max compression
+gzip compressed data, was "dist/wappsto-1.2.9.tar", last modified: Tue Jun  1 12:55:32 2021, max compression
```

## Comparing `wappsto-1.2.8.tar` & `wappsto-1.2.9.tar`

### file list

```diff
@@ -1,36 +1,36 @@
-drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-03-15 10:02:22.636150 wappsto-1.2.8/
--rw-rw-r--   0 bach      (1000) bach      (1000)     2244 2021-03-15 10:02:22.636150 wappsto-1.2.8/PKG-INFO
--rw-rw-r--   0 bach      (1000) bach      (1000)     1425 2020-12-18 11:46:05.000000 wappsto-1.2.8/README.md
--rw-rw-r--   0 bach      (1000) bach      (1000)       38 2021-03-15 10:02:22.636150 wappsto-1.2.8/setup.cfg
--rw-rw-r--   0 bach      (1000) bach      (1000)     1261 2020-12-18 11:46:05.000000 wappsto-1.2.8/setup.py
-drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-03-15 10:02:22.632150 wappsto-1.2.8/wappsto/
--rw-rw-r--   0 bach      (1000) bach      (1000)     9602 2021-02-12 11:49:46.000000 wappsto-1.2.8/wappsto/__init__.py
-drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-03-15 10:02:22.636150 wappsto-1.2.8/wappsto/connection/
--rw-rw-r--   0 bach      (1000) bach      (1000)      207 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/connection/__init__.py
--rw-rw-r--   0 bach      (1000) bach      (1000)    13351 2021-02-12 11:49:46.000000 wappsto-1.2.8/wappsto/connection/communication.py
--rw-rw-r--   0 bach      (1000) bach      (1000)    10083 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/connection/event_storage.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     2586 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/connection/message_data.py
--rw-rw-r--   0 bach      (1000) bach      (1000)    14303 2021-02-12 11:49:46.000000 wappsto-1.2.8/wappsto/connection/receive_data.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     6775 2020-12-18 11:58:47.000000 wappsto-1.2.8/wappsto/connection/seluxit_rpc.py
--rw-rw-r--   0 bach      (1000) bach      (1000)    10980 2021-02-12 11:49:46.000000 wappsto-1.2.8/wappsto/connection/send_data.py
-drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-03-15 10:02:22.636150 wappsto-1.2.8/wappsto/data_operation/
--rw-rw-r--   0 bach      (1000) bach      (1000)      250 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/data_operation/__init__.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     6621 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/data_operation/data_manager.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     6658 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/data_operation/decoder.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     5301 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/data_operation/encoder.py
-drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-03-15 10:02:22.636150 wappsto-1.2.8/wappsto/errors/
--rw-rw-r--   0 bach      (1000) bach      (1000)      112 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/errors/__init__.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     1424 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/errors/wappsto_errors.py
-drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-03-15 10:02:22.636150 wappsto-1.2.8/wappsto/modules/
--rw-rw-r--   0 bach      (1000) bach      (1000)      133 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/modules/__init__.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     4995 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/modules/device.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     3247 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/modules/network.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     3420 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/modules/state.py
--rw-rw-r--   0 bach      (1000) bach      (1000)    18252 2021-02-12 11:49:46.000000 wappsto-1.2.8/wappsto/modules/value.py
--rw-rw-r--   0 bach      (1000) bach      (1000)     4452 2020-12-18 11:46:05.000000 wappsto-1.2.8/wappsto/status.py
-drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-03-15 10:02:22.632150 wappsto-1.2.8/wappsto.egg-info/
--rw-rw-r--   0 bach      (1000) bach      (1000)     2244 2021-03-15 10:02:22.000000 wappsto-1.2.8/wappsto.egg-info/PKG-INFO
--rw-rw-r--   0 bach      (1000) bach      (1000)      782 2021-03-15 10:02:22.000000 wappsto-1.2.8/wappsto.egg-info/SOURCES.txt
--rw-rw-r--   0 bach      (1000) bach      (1000)        1 2021-03-15 10:02:22.000000 wappsto-1.2.8/wappsto.egg-info/dependency_links.txt
--rw-rw-r--   0 bach      (1000) bach      (1000)       14 2021-03-15 10:02:22.000000 wappsto-1.2.8/wappsto.egg-info/requires.txt
--rw-rw-r--   0 bach      (1000) bach      (1000)        8 2021-03-15 10:02:22.000000 wappsto-1.2.8/wappsto.egg-info/top_level.txt
+drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-06-01 12:55:32.741884 wappsto-1.2.9/
+-rw-rw-r--   0 bach      (1000) bach      (1000)     2244 2021-06-01 12:55:32.741884 wappsto-1.2.9/PKG-INFO
+-rw-rw-r--   0 bach      (1000) bach      (1000)     1425 2020-12-18 11:46:05.000000 wappsto-1.2.9/README.md
+-rw-rw-r--   0 bach      (1000) bach      (1000)       38 2021-06-01 12:55:32.741884 wappsto-1.2.9/setup.cfg
+-rw-rw-r--   0 bach      (1000) bach      (1000)     1261 2020-12-18 11:46:05.000000 wappsto-1.2.9/setup.py
+drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-06-01 12:55:32.737884 wappsto-1.2.9/wappsto/
+-rw-rw-r--   0 bach      (1000) bach      (1000)     9995 2021-06-01 10:34:06.000000 wappsto-1.2.9/wappsto/__init__.py
+drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-06-01 12:55:32.741884 wappsto-1.2.9/wappsto/connection/
+-rw-rw-r--   0 bach      (1000) bach      (1000)      207 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/connection/__init__.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)    13331 2021-06-01 10:31:29.000000 wappsto-1.2.9/wappsto/connection/communication.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)    10083 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/connection/event_storage.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     2586 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/connection/message_data.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)    14414 2021-06-01 10:31:29.000000 wappsto-1.2.9/wappsto/connection/receive_data.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     6813 2021-06-01 10:31:29.000000 wappsto-1.2.9/wappsto/connection/seluxit_rpc.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)    10980 2021-02-12 11:49:46.000000 wappsto-1.2.9/wappsto/connection/send_data.py
+drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-06-01 12:55:32.741884 wappsto-1.2.9/wappsto/data_operation/
+-rw-rw-r--   0 bach      (1000) bach      (1000)      250 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/data_operation/__init__.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     6720 2021-06-01 10:31:29.000000 wappsto-1.2.9/wappsto/data_operation/data_manager.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     6659 2021-06-01 10:38:19.000000 wappsto-1.2.9/wappsto/data_operation/decoder.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     5301 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/data_operation/encoder.py
+drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-06-01 12:55:32.741884 wappsto-1.2.9/wappsto/errors/
+-rw-rw-r--   0 bach      (1000) bach      (1000)      112 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/errors/__init__.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     1424 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/errors/wappsto_errors.py
+drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-06-01 12:55:32.741884 wappsto-1.2.9/wappsto/modules/
+-rw-rw-r--   0 bach      (1000) bach      (1000)      133 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/modules/__init__.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     4995 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/modules/device.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     3247 2021-06-01 10:38:19.000000 wappsto-1.2.9/wappsto/modules/network.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     3420 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/modules/state.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)    18408 2021-06-01 10:31:29.000000 wappsto-1.2.9/wappsto/modules/value.py
+-rw-rw-r--   0 bach      (1000) bach      (1000)     4452 2020-12-18 11:46:05.000000 wappsto-1.2.9/wappsto/status.py
+drwxrwxr-x   0 bach      (1000) bach      (1000)        0 2021-06-01 12:55:32.741884 wappsto-1.2.9/wappsto.egg-info/
+-rw-rw-r--   0 bach      (1000) bach      (1000)     2244 2021-06-01 12:55:32.000000 wappsto-1.2.9/wappsto.egg-info/PKG-INFO
+-rw-rw-r--   0 bach      (1000) bach      (1000)      782 2021-06-01 12:55:32.000000 wappsto-1.2.9/wappsto.egg-info/SOURCES.txt
+-rw-rw-r--   0 bach      (1000) bach      (1000)        1 2021-06-01 12:55:32.000000 wappsto-1.2.9/wappsto.egg-info/dependency_links.txt
+-rw-rw-r--   0 bach      (1000) bach      (1000)       14 2021-06-01 12:55:32.000000 wappsto-1.2.9/wappsto.egg-info/requires.txt
+-rw-rw-r--   0 bach      (1000) bach      (1000)        8 2021-06-01 12:55:32.000000 wappsto-1.2.9/wappsto.egg-info/top_level.txt
```

### Comparing `wappsto-1.2.8/PKG-INFO` & `wappsto-1.2.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wappsto
-Version: 1.2.8
+Version: 1.2.9
 Summary: Python Package to connect to wappsto.com
 Home-page: https://github.com/wappsto/wappsto-python
 Author: Seluxit A/S
 Author-email: support@seluxit.com
 License: Apache-2.0
 Description: # wappsto-python
```

### Comparing `wappsto-1.2.8/README.md` & `wappsto-1.2.9/README.md`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/setup.py` & `wappsto-1.2.9/setup.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/__init__.py` & `wappsto-1.2.9/wappsto/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 """
-Rapid Prototyping Python module for wappsto.com
+Rapid Prototyping Python module for wappsto.com.
 
 Stores the Wappsto class functionality.
 """
 
 import inspect
 import logging
 import os
@@ -18,15 +18,15 @@
 from .data_operation import data_manager
 
 
 RETRY_LIMIT = 5
 
 
 class Object_instantiation:
-    """For backward compability. (Deprecated)"""
+    """For backward compability. (Deprecated)."""
     def __init__(self):
         """Initialize Object_instantiation."""
         self.status = status
 
 
 object_instantiation = Object_instantiation()
 
@@ -34,46 +34,64 @@
 class Wappsto:
     """
     The main package classs.
 
     Establishes a connection to the wappsto server, initializes the classes,
     starts a sending/receiving thread.
     """
-    __version__ = "1.2.8"
+    __version__ = "1.2.9"
 
-    def __init__(self, json_file_name=None, load_from_state_file=False,
-                 log_offline=False, log_location="logs",
-                 log_data_limit=10, limit_action=event_storage.REMOVE_OLD,
-                 compression_period=event_storage.DAY_PERIOD):
+    def __init__(
+        self,
+        json_file_name,
+        abs_config_path=None,
+        load_from_state_file=False,
+        log_offline=False,
+        log_location="logs",
+        log_data_limit=10,
+        limit_action=event_storage.REMOVE_OLD,
+        compression_period=event_storage.DAY_PERIOD
+    ):
         """
         Initialize wappsto class.
 
         Creates a wappsto object which methods are exposed for users to use.
         These are: starting and stopping connection with a server and
         retrieving devices. These methods are enough for users to make
         operations on their network.
 
         Args:
             json_file_name: name of a json file containing all information
-                about a network (default: {None})
+                about a network
+            abs_config_path: The absolute path to all the config files.
+                If non is given, it will be set to where it was imported from.
+                (Default: None)
             load_from_state_file: Defines if the data should be loaded from
                 saved files (default: {False})
-            log_offline: boolean indicating if data should be logged (default: {False})
-            log_location: location of the logs (default: {"logs"})
-            log_data_limit: limit of data to be saved in log [in Megabytes] (default: {10})
-            limit_action: action to take when limit is reached (default: {REMOVE_OLD})
-            compression_period: period for compressing data [day, hour] (default: {DAY_PERIOD})
+            log_offline: boolean indicating if data should be logged
+                (default: {False})
+            log_location: location of the logs
+                (default: {"logs"})
+            log_data_limit: limit of data to be saved in log [in Megabytes]
+                (default: {10})
+            limit_action: action to take when limit is reached
+                (default: {REMOVE_OLD})
+            compression_period: period for compressing data [day, hour]
+                (default: {DAY_PERIOD})
 
         """
         self.wapp_log = logging.getLogger(__name__)
         self.wapp_log.addHandler(logging.NullHandler())
 
         # TODO(Dimitar): Comment on this later.
         stack = inspect.stack()[1][1]
-        self.path_to_calling_file = os.path.dirname(os.path.abspath(stack))
+        if abs_config_path:
+            self.path_to_calling_file = abs_config_path
+        else:
+            self.path_to_calling_file = os.path.dirname(os.path.abspath(stack))
 
         self.connecting = True
         self.event_storage = event_storage.OfflineEventStorage(
             log_offline,
             log_location,
             log_data_limit,
             limit_action,
```

### Comparing `wappsto-1.2.8/wappsto/connection/communication.py` & `wappsto-1.2.9/wappsto/connection/communication.py`

 * *Files 1% similar despite different names*

```diff
@@ -103,15 +103,15 @@
             1
         )
         if (hasattr(socket, "TCP_KEEPIDLE")
                 and hasattr(socket, "TCP_KEEPINTVL")
                 and hasattr(socket, "TCP_KEEPCNT")):
             # After 5 idle minutes, start sending keepalives every 1 minutes.
             # Drop connection after 2 failed keepalives
-            self.wapp_log.debug(f"Setting TCP_KEEPIDLE, TCP_KEEPINTVL & TCP_KEEPCNT.")
+            self.wapp_log.debug("Setting TCP_KEEPIDLE, TCP_KEEPINTVL & TCP_KEEPCNT.")
             self.my_raw_socket.setsockopt(
                 socket.SOL_TCP,
                 socket.TCP_KEEPIDLE,
                 5 * 60
             )
             self.my_raw_socket.setsockopt(
                 socket.IPPROTO_TCP,
@@ -126,15 +126,15 @@
             self.my_raw_socket.setsockopt(
                 socket.IPPROTO_TCP,
                 socket.TCP_KEEPCNT,
                 2
             )
 
         if hasattr(socket, "TCP_USER_TIMEOUT"):
-            self.wapp_log.debug(f"Setting TCP_USER_TIMEOUT to 30_000ms.")
+            self.wapp_log.debug("Setting TCP_USER_TIMEOUT to 30_000ms.")
             self.my_raw_socket.setsockopt(
                 socket.IPPROTO_TCP,
                 socket.TCP_USER_TIMEOUT,
                 30_000
             )
         self.my_socket = self.ssl_wrap()
 
@@ -266,17 +266,15 @@
             del self.packet_timeout_list[_id]
         if _id in self.packet_awaiting_confirm:
             del self.packet_awaiting_confirm[_id]
         self.lock_await.release()
         self.poke_send_thread()
 
     def poke_send_thread(self):
-        """
-        Poke the Send thread, to let it know some thing have changed.
-        """
+        """Poke the Send thread, to let it know some thing have changed."""
         poke_msg = message_data.MessageData(
             message_data.POKE
         )
         self.sending_queue.put(poke_msg)
 
     def request_reconnect(self):
         """Reconnect if it is required (Non Blocking)."""
```

### Comparing `wappsto-1.2.8/wappsto/connection/event_storage.py` & `wappsto-1.2.9/wappsto/connection/event_storage.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/connection/message_data.py` & `wappsto-1.2.9/wappsto/connection/message_data.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/connection/receive_data.py` & `wappsto-1.2.9/wappsto/connection/receive_data.py`

 * *Files 1% similar despite different names*

```diff
@@ -146,14 +146,16 @@
         Performs acction on received message.
 
         Based on the type of message, directs the decoded data to the
         appropriate methods.
 
         Args:
             decoded: the received message
+            fail_on_error: Boolean, if a exception should
+                           be raised on failed post.
 
         """
         if decoded:
             try:
                 if decoded.get('method', False) == 'PUT':
                     self.incoming_put(decoded)
```

### Comparing `wappsto-1.2.8/wappsto/connection/seluxit_rpc.py` & `wappsto-1.2.9/wappsto/connection/seluxit_rpc.py`

 * *Files 0% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 JSONRPC = '2.0'
 
 session_id = "".join(random.choices(string.ascii_letters + string.digits, k=10))
 session_count = 0
 
 
 def id_count(verb):
+    """Keep track of the trace-id."""
     global session_count
     session_count += 1
     return f"{session_id}_{verb}_{session_count}"
 
 
 def create_meta(network, network_id):
     """
```

### Comparing `wappsto-1.2.8/wappsto/connection/send_data.py` & `wappsto-1.2.9/wappsto/connection/send_data.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/data_operation/data_manager.py` & `wappsto-1.2.9/wappsto/data_operation/data_manager.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,15 +38,15 @@
         """
         self.wapp_log = logging.getLogger(__name__)
         self.wapp_log.addHandler(logging.NullHandler())
         self.wappsto_encoder = encoder.WappstoEncoder()
         self.wappsto_decoder = decoder.WappstoDecoder()
 
         self.path_to_calling_file = path_to_calling_file
-        self.json_file_name = json_file_name
+        self.json_file_name = os.path.join(self.path_to_calling_file, json_file_name)
 
         if load_from_state_file:
             json_file_name = self.get_latest_instance()
             if json_file_name is not None:
                 self.json_file_name = json_file_name
         self.read_file()
 
@@ -141,15 +141,16 @@
         """
         encoded_string = str(self.get_encoded_network())
         encoded_string = encoded_string.replace("\'", "\\\"")
         encoded_string = '{{"data":"{}"}}'.format(encoded_string)
 
         path = os.path.join(self.path_to_calling_file, 'saved_instances')
         os.makedirs(path, exist_ok=True)
-        path_open = os.path.join(path, self.json_file_name)
+        json_base_name = os.path.basename(self.json_file_name)
+        path_open = os.path.join(path, json_base_name)
 
         with open(path_open, "w+") as network_file:
             network_file.write(encoded_string)
 
         msg = "Saved {} to {}".format(encoded_string, network_file)
         self.wapp_log.debug(msg)
```

### Comparing `wappsto-1.2.8/wappsto/data_operation/decoder.py` & `wappsto-1.2.9/wappsto/data_operation/decoder.py`

 * *Files 1% similar despite different names*

```diff
@@ -40,15 +40,15 @@
 
         Returns:
             Network object.
 
         """
         network = network_module.Network(
             uuid=json_data.get('meta').get('id'),
-            version=json_data.get('meta').get('version'), # TODO (aeb): Remove? Does not make much sense
+            version=json_data.get('meta').get('version'),  # TODO (aeb): Remove? Does not make much sense
             name=json_data.get('name'),
             devices=[],
             data_manager=data_manager
         )
         network.devices = self.decode_device(json_data, network)
 
         self.wapp_log.debug("Network {} built.".format(network))
```

### Comparing `wappsto-1.2.8/wappsto/data_operation/encoder.py` & `wappsto-1.2.9/wappsto/data_operation/encoder.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/errors/wappsto_errors.py` & `wappsto-1.2.9/wappsto/errors/wappsto_errors.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/modules/device.py` & `wappsto-1.2.9/wappsto/modules/device.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/modules/network.py` & `wappsto-1.2.9/wappsto/modules/network.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/modules/state.py` & `wappsto-1.2.9/wappsto/modules/state.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto/modules/value.py` & `wappsto-1.2.9/wappsto/modules/value.py`

 * *Files 2% similar despite different names*

```diff
@@ -10,14 +10,15 @@
 
 from ..connection import message_data
 from ..connection import seluxit_rpc
 from ..errors import wappsto_errors
 
 
 def isNaN(num):
+    """Test if input is a float 'NaN' value."""
     return num != num
 
 
 class Value:
     """
     Value instance.
 
@@ -180,15 +181,15 @@
             self.timer_elapsed = False
             self.timer = threading.Timer(self.period, self.__timer_done)
             self.timer.start()
 
     def __timer_done(self):
         self.__set_timer()
         self.timer_elapsed = True
-        self.handle_refresh()
+        # self.handle_refresh()  # ERROR: Trickered double sampling. Text needed.
 
     def set_delta(self, delta):
         """
         Set the delta to report between.
 
         Sets the delta (range) of change to report in. When a change happens
         in the range of this delta it will be reported.
@@ -322,15 +323,16 @@
             self.wapp_log.error("Error setting callback: {}".format(msg))
             raise wappsto_errors.CallbackNotCallableException
         self.callback = callback
         self.wapp_log.debug("Callback {} has been set.".format(callback))
         return True
 
     def _validate_value_data(self, data_value, err_msg=None):
-        # TODO(MBK): Need refactoring, so it also nicely can be used for control validation, in 'receive_Data/incoming_put'
+        # TODO(MBK): Need refactoring, so it also nicely can be used for
+        #            control validation, in 'receive_Data/incoming_put'
         if err_msg is None:
             err_msg = []
         if self.__is_number_type():
             try:
                 if self._outside_range(data_value):
                     msg = "Invalid number. Range: {}-{}. Yours is: {}".format(
                         self.number_min,
@@ -404,15 +406,15 @@
         Args:
             value: The value to be checked.
 
         Returns:
             True, if invalid step size.
             False if valid step size.
         """
-        x = (float(value)-self.number_min)/self.number_step
+        x = (float(value) - self.number_min) / self.number_step
         return not (abs(round(x) - x) <= 1e-9)
 
     def update(self, data_value, timestamp=None):
         """
         Update value.
 
         Check if value has a state and validates the information in data_value
@@ -481,16 +483,18 @@
                     raise ValueError("Value is NAN!")
                 data_value = float(data_value)
             except ValueError:
                 if not isNaN(self.last_update_of_report):
                     return True
                 return self.check_period(False)
 
-            if (self.last_update_of_report is None or
-               not (abs(data_value - self.last_update_of_report) < self.delta)):
+            if (
+                self.last_update_of_report is None
+                or not (abs(data_value - self.last_update_of_report) < self.delta)
+            ):
                 return True
 
         return self.check_period(False)
 
     def check_period(self, return_value):
         """
         Check if period allows data to be sent.
```

### Comparing `wappsto-1.2.8/wappsto/status.py` & `wappsto-1.2.9/wappsto/status.py`

 * *Files identical despite different names*

### Comparing `wappsto-1.2.8/wappsto.egg-info/PKG-INFO` & `wappsto-1.2.9/wappsto.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wappsto
-Version: 1.2.8
+Version: 1.2.9
 Summary: Python Package to connect to wappsto.com
 Home-page: https://github.com/wappsto/wappsto-python
 Author: Seluxit A/S
 Author-email: support@seluxit.com
 License: Apache-2.0
 Description: # wappsto-python
```

### Comparing `wappsto-1.2.8/wappsto.egg-info/SOURCES.txt` & `wappsto-1.2.9/wappsto.egg-info/SOURCES.txt`

 * *Files identical despite different names*

