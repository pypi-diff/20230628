# Comparing `tmp/python-matter-server-3.6.1.tar.gz` & `tmp/python-matter-server-3.6.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "python-matter-server-3.6.1.tar", last modified: Tue Jun 27 21:21:51 2023, max compression
+gzip compressed data, was "python-matter-server-3.6.2.tar", last modified: Wed Jun 28 15:04:06 2023, max compression
```

## Comparing `python-matter-server-3.6.1.tar` & `python-matter-server-3.6.2.tar`

### file list

```diff
@@ -1,48 +1,48 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/
--rw-r--r--   0 runner    (1001) docker     (123)    11342 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13808 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13210 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.373798 python-matter-server-3.6.1/matter_server/
--rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.373798 python-matter-server-3.6.1/matter_server/client/
--rw-r--r--   0 runner    (1001) docker     (123)       96 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/client/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18345 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/client/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5991 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/client/connection.py
--rw-r--r--   0 runner    (1001) docker     (123)     1621 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/client/exceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.373798 python-matter-server-3.6.1/matter_server/client/models/
--rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/client/models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14062 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/client/models/device_types.py
--rw-r--r--   0 runner    (1001) docker     (123)    13578 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/client/models/node.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/matter_server/common/
--rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/common/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      231 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/common/const.py
--rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/common/errors.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/matter_server/common/helpers/
--rw-r--r--   0 runner    (1001) docker     (123)     2011 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/common/helpers/api.py
--rw-r--r--   0 runner    (1001) docker     (123)     1508 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/common/helpers/json.py
--rw-r--r--   0 runner    (1001) docker     (123)     9240 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/common/helpers/util.py
--rw-r--r--   0 runner    (1001) docker     (123)     3835 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/common/models.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/matter_server/server/
--rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2440 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8572 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/client_handler.py
--rw-r--r--   0 runner    (1001) docker     (123)      602 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/const.py
--rw-r--r--   0 runner    (1001) docker     (123)    35106 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/device_controller.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/matter_server/server/helpers/
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/helpers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5903 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/helpers/paa_certificates.py
--rw-r--r--   0 runner    (1001) docker     (123)     7470 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/server.py
--rw-r--r--   0 runner    (1001) docker     (123)     2604 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/stack.py
--rw-r--r--   0 runner    (1001) docker     (123)     5358 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/storage.py
--rw-r--r--   0 runner    (1001) docker     (123)     3763 2023-06-27 21:21:38.000000 python-matter-server-3.6.1/matter_server/server/vendor_info.py
--rw-r--r--   0 runner    (1001) docker     (123)     2639 2023-06-27 21:21:42.000000 python-matter-server-3.6.1/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/python_matter_server.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13808 2023-06-27 21:21:50.000000 python-matter-server-3.6.1/python_matter_server.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1285 2023-06-27 21:21:51.000000 python-matter-server-3.6.1/python_matter_server.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 21:21:50.000000 python-matter-server-3.6.1/python_matter_server.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-27 21:21:51.000000 python-matter-server-3.6.1/python_matter_server.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 21:21:49.000000 python-matter-server-3.6.1/python_matter_server.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      302 2023-06-27 21:21:51.000000 python-matter-server-3.6.1/python_matter_server.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-27 21:21:51.000000 python-matter-server-3.6.1/python_matter_server.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      168 2023-06-27 21:21:51.377798 python-matter-server-3.6.1/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/
+-rw-r--r--   0 runner    (1001) docker     (123)    11342 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13808 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13210 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.976177 python-matter-server-3.6.2/matter_server/
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/matter_server/client/
+-rw-r--r--   0 runner    (1001) docker     (123)       96 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/client/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18555 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/client/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5991 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/client/connection.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1621 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/client/exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/matter_server/client/models/
+-rw-r--r--   0 runner    (1001) docker     (123)       63 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/client/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14062 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/client/models/device_types.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13578 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/client/models/node.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/matter_server/common/
+-rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/common/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      231 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/common/const.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1902 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/common/errors.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/matter_server/common/helpers/
+-rw-r--r--   0 runner    (1001) docker     (123)     2011 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/common/helpers/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1508 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/common/helpers/json.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9240 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/common/helpers/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3835 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/common/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/matter_server/server/
+-rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2440 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8572 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/client_handler.py
+-rw-r--r--   0 runner    (1001) docker     (123)      602 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/const.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35120 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/device_controller.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/matter_server/server/helpers/
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/helpers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5903 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/helpers/paa_certificates.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7470 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/server.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2604 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/stack.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5358 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/storage.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3763 2023-06-28 15:03:52.000000 python-matter-server-3.6.2/matter_server/server/vendor_info.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2639 2023-06-28 15:03:55.000000 python-matter-server-3.6.2/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/python_matter_server.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13808 2023-06-28 15:04:06.000000 python-matter-server-3.6.2/python_matter_server.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1285 2023-06-28 15:04:06.000000 python-matter-server-3.6.2/python_matter_server.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:04:06.000000 python-matter-server-3.6.2/python_matter_server.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 15:04:06.000000 python-matter-server-3.6.2/python_matter_server.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:04:04.000000 python-matter-server-3.6.2/python_matter_server.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      302 2023-06-28 15:04:06.000000 python-matter-server-3.6.2/python_matter_server.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-28 15:04:06.000000 python-matter-server-3.6.2/python_matter_server.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      168 2023-06-28 15:04:06.980177 python-matter-server-3.6.2/setup.cfg
```

### Comparing `python-matter-server-3.6.1/LICENSE` & `python-matter-server-3.6.2/LICENSE`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/PKG-INFO` & `python-matter-server-3.6.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-matter-server
-Version: 3.6.1
+Version: 3.6.2
 Summary: Python Matter WebSocket Server
 Author-email: The Home Assistant Authors <hello@home-assistant.io>
 License: Apache-2.0
 Platform: any
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Environment :: Console
```

### Comparing `python-matter-server-3.6.1/README.md` & `python-matter-server-3.6.2/README.md`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/client/client.py` & `python-matter-server-3.6.2/matter_server/client/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 from types import TracebackType
 from typing import TYPE_CHECKING, Any, Callable, Dict, Final, Optional, cast
 import uuid
 
 from aiohttp import ClientSession
 from chip.clusters import Objects as Clusters
 
-from matter_server.common.errors import ERROR_MAP
+from matter_server.common.errors import ERROR_MAP, NodeNotExists
 
 from ..common.helpers.util import dataclass_from_dict, dataclass_to_dict
 from ..common.models import (
     APICommand,
     CommandMessage,
     ErrorResultMessage,
     EventMessage,
@@ -50,15 +50,15 @@
         self._loop: asyncio.AbstractEventLoop | None = None
 
     @property
     def server_info(self) -> ServerInfoMessage | None:
         """Return info of the server we're currently connected to."""
         return self.connection.server_info
 
-    def subscribe(
+    def subscribe_events(
         self,
         callback: Callable[[EventType, Any], None],
         event_filter: Optional[EventType] = None,
         node_filter: Optional[int] = None,
         attr_path_filter: Optional[str] = None,
     ) -> Callable[[], None]:
         """
@@ -99,16 +99,18 @@
         return unsubscribe
 
     def get_nodes(self) -> list[MatterNode]:
         """Return all Matter nodes."""
         return list(self._nodes.values())
 
     def get_node(self, node_id: int) -> MatterNode:
-        """Return Matter node by id."""
-        return self._nodes[node_id]
+        """Return Matter node by id or None if no node exists by that id."""
+        if node := self._nodes.get(node_id):
+            return node
+        raise NodeNotExists(f"Node {node_id} does not exist or is not yet interviewed")
 
     async def commission_with_code(self, code: str) -> MatterNodeData:
         """
         Commission a device using QRCode or ManualPairingCode.
 
         Returns basic MatterNodeData once complete.
         """
@@ -241,14 +243,15 @@
 
         Either supply a single attribute path or a list of paths.
         The given attribute path(s) will be added to the list of attributes that
         are watched for the given node. This is persistent over restarts.
         """
         await self.send_command(
             APICommand.SUBSCRIBE_ATTRIBUTE,
+            require_schema=4,
             node_id=node_id,
             attribute_path=attribute_path,
         )
 
     async def send_command(
         self,
         command: str,
```

### Comparing `python-matter-server-3.6.1/matter_server/client/connection.py` & `python-matter-server-3.6.2/matter_server/client/connection.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/client/exceptions.py` & `python-matter-server-3.6.2/matter_server/client/exceptions.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/client/models/device_types.py` & `python-matter-server-3.6.2/matter_server/client/models/device_types.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/client/models/node.py` & `python-matter-server-3.6.2/matter_server/client/models/node.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/common/errors.py` & `python-matter-server-3.6.2/matter_server/common/errors.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/common/helpers/api.py` & `python-matter-server-3.6.2/matter_server/common/helpers/api.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/common/helpers/json.py` & `python-matter-server-3.6.2/matter_server/common/helpers/json.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/common/helpers/util.py` & `python-matter-server-3.6.2/matter_server/common/helpers/util.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/common/models.py` & `python-matter-server-3.6.2/matter_server/common/models.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/__main__.py` & `python-matter-server-3.6.2/matter_server/server/__main__.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/client_handler.py` & `python-matter-server-3.6.2/matter_server/server/client_handler.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/const.py` & `python-matter-server-3.6.2/matter_server/server/const.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/device_controller.py` & `python-matter-server-3.6.2/matter_server/server/device_controller.py`

 * *Files 0% similar despite different names*

```diff
@@ -140,17 +140,17 @@
             for x in self._nodes.values()
             if x is not None and (x.available or not only_available)
         ]
 
     @api_command(APICommand.GET_NODE)
     def get_node(self, node_id: int) -> MatterNodeData:
         """Return info of a single Node."""
-        node = self._nodes.get(node_id)
-        assert node is not None, "Node does not exist or is not yet interviewed"
-        return node
+        if node := self._nodes.get(node_id):
+            return node
+        raise NodeNotExists(f"Node {node_id} does not exist or is not yet interviewed")
 
     @api_command(APICommand.COMMISSION_WITH_CODE)
     async def commission_with_code(self, code: str) -> MatterNodeData:
         """
         Commission a device using QRCode or ManualPairingCode.
 
         Returns full NodeInfo once complete.
@@ -516,15 +516,15 @@
                 attr_subscriptions.append(cluster)
 
         if len(attr_subscriptions) > 50:
             # prevent memory overload on node and fallback to wildcard sub if too many
             # individual subscriptions (e.g. bridges)
             attr_subscriptions = "*"  # type: ignore[assignment]
 
-        if node.attribute_subscriptions == []:
+        if not node.attribute_subscriptions:
             # temp fix for backwards compatbility with HA releases below 2023.7
             # fallback to wildcard subscriptions if we have no explicit
             # node subscriptions defined.
             # TODO: remove this after HA release 2023.8
             attr_subscriptions = "*"  # type: ignore[assignment]
 
         # check if we already have an subscription for this node,
```

### Comparing `python-matter-server-3.6.1/matter_server/server/helpers/paa_certificates.py` & `python-matter-server-3.6.2/matter_server/server/helpers/paa_certificates.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/server.py` & `python-matter-server-3.6.2/matter_server/server/server.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/stack.py` & `python-matter-server-3.6.2/matter_server/server/stack.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/storage.py` & `python-matter-server-3.6.2/matter_server/server/storage.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/matter_server/server/vendor_info.py` & `python-matter-server-3.6.2/matter_server/server/vendor_info.py`

 * *Files identical despite different names*

### Comparing `python-matter-server-3.6.1/pyproject.toml` & `python-matter-server-3.6.2/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -3,15 +3,15 @@
     "setuptools~=62.3",
     "wheel~=0.37.1",
 ]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "python-matter-server"
-version = "3.6.1"
+version = "3.6.2"
 description = "Python Matter WebSocket Server"
 readme = "README.md"
 requires-python = ">=3.10"
 authors = [
     { name = "The Home Assistant Authors", email = "hello@home-assistant.io" },
 ]
 classifiers = [
```

### Comparing `python-matter-server-3.6.1/python_matter_server.egg-info/PKG-INFO` & `python-matter-server-3.6.2/python_matter_server.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: python-matter-server
-Version: 3.6.1
+Version: 3.6.2
 Summary: Python Matter WebSocket Server
 Author-email: The Home Assistant Authors <hello@home-assistant.io>
 License: Apache-2.0
 Platform: any
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Environment :: Console
```

### Comparing `python-matter-server-3.6.1/python_matter_server.egg-info/SOURCES.txt` & `python-matter-server-3.6.2/python_matter_server.egg-info/SOURCES.txt`

 * *Files identical despite different names*

