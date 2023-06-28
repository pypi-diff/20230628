# Comparing `tmp/bec_scan_bundler-0.7.1.tar.gz` & `tmp/bec_scan_bundler-0.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bec_scan_bundler-0.7.1.tar", last modified: Wed Jun 28 14:36:10 2023, max compression
+gzip compressed data, was "bec_scan_bundler-0.8.0.tar", last modified: Wed Jun 28 15:24:08 2023, max compression
```

## Comparing `bec_scan_bundler-0.7.1.tar` & `bec_scan_bundler-0.8.0.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:36:10.399505 bec_scan_bundler-0.7.1/
--rw-r--r--   0 root         (0) root         (0)      470 2023-06-28 14:36:10.399505 bec_scan_bundler-0.7.1/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:36:10.399505 bec_scan_bundler-0.7.1/bec_scan_bundler.egg-info/
--rw-r--r--   0 root         (0) root         (0)      470 2023-06-28 14:36:10.000000 bec_scan_bundler-0.7.1/bec_scan_bundler.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      365 2023-06-28 14:36:10.000000 bec_scan_bundler-0.7.1/bec_scan_bundler.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:36:10.000000 bec_scan_bundler-0.7.1/bec_scan_bundler.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       21 2023-06-28 14:36:10.000000 bec_scan_bundler-0.7.1/bec_scan_bundler.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 14:36:10.000000 bec_scan_bundler-0.7.1/bec_scan_bundler.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:36:10.398505 bec_scan_bundler-0.7.1/scan_bundler/
--rw-rw-rw-   0 root         (0) root         (0)       38 2023-04-24 15:23:42.000000 bec_scan_bundler-0.7.1/scan_bundler/__init__.py
--rw-r--r--   0 root         (0) root         (0)     1705 2023-06-28 14:35:35.000000 bec_scan_bundler-0.7.1/scan_bundler/bec_emitter.py
--rw-r--r--   0 root         (0) root         (0)     5470 2023-06-28 14:35:35.000000 bec_scan_bundler-0.7.1/scan_bundler/bluesky_emitter.py
--rw-r--r--   0 root         (0) root         (0)     1848 2023-06-28 14:35:35.000000 bec_scan_bundler-0.7.1/scan_bundler/emitter.py
--rw-r--r--   0 root         (0) root         (0)    14649 2023-06-28 14:35:35.000000 bec_scan_bundler-0.7.1/scan_bundler/scan_bundler.py
--rw-r--r--   0 root         (0) root         (0)      551 2023-06-28 14:36:10.399505 bec_scan_bundler-0.7.1/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      721 2023-06-28 14:35:35.000000 bec_scan_bundler-0.7.1/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:24:08.258579 bec_scan_bundler-0.8.0/
+-rw-r--r--   0 root         (0) root         (0)      470 2023-06-28 15:24:08.258579 bec_scan_bundler-0.8.0/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:24:08.258579 bec_scan_bundler-0.8.0/bec_scan_bundler.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      470 2023-06-28 15:24:08.000000 bec_scan_bundler-0.8.0/bec_scan_bundler.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      365 2023-06-28 15:24:08.000000 bec_scan_bundler-0.8.0/bec_scan_bundler.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 15:24:08.000000 bec_scan_bundler-0.8.0/bec_scan_bundler.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       21 2023-06-28 15:24:08.000000 bec_scan_bundler-0.8.0/bec_scan_bundler.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 15:24:08.000000 bec_scan_bundler-0.8.0/bec_scan_bundler.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:24:08.257579 bec_scan_bundler-0.8.0/scan_bundler/
+-rw-rw-rw-   0 root         (0) root         (0)       38 2023-04-24 15:23:42.000000 bec_scan_bundler-0.8.0/scan_bundler/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1705 2023-06-28 10:41:58.000000 bec_scan_bundler-0.8.0/scan_bundler/bec_emitter.py
+-rw-r--r--   0 root         (0) root         (0)     5491 2023-06-28 15:23:35.000000 bec_scan_bundler-0.8.0/scan_bundler/bluesky_emitter.py
+-rw-r--r--   0 root         (0) root         (0)     1848 2023-06-28 10:41:58.000000 bec_scan_bundler-0.8.0/scan_bundler/emitter.py
+-rw-r--r--   0 root         (0) root         (0)    14743 2023-06-28 15:23:35.000000 bec_scan_bundler-0.8.0/scan_bundler/scan_bundler.py
+-rw-r--r--   0 root         (0) root         (0)      551 2023-06-28 15:24:08.259579 bec_scan_bundler-0.8.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      721 2023-06-28 14:27:03.000000 bec_scan_bundler-0.8.0/setup.py
```

### Comparing `bec_scan_bundler-0.7.1/scan_bundler/bec_emitter.py` & `bec_scan_bundler-0.8.0/scan_bundler/bec_emitter.py`

 * *Files identical despite different names*

### Comparing `bec_scan_bundler-0.7.1/scan_bundler/bluesky_emitter.py` & `bec_scan_bundler-0.8.0/scan_bundler/bluesky_emitter.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,14 +3,15 @@
 import time
 import uuid
 from collections.abc import Iterable
 from typing import TYPE_CHECKING
 
 import msgpack
 import numpy as np
+
 from bec_lib.core import MessageEndpoints, bec_logger
 
 from .emitter import EmitterBase
 
 logger = bec_logger.logger
 
 if TYPE_CHECKING:
@@ -43,15 +44,15 @@
             "motors": tuple(dev.name for dev in sb.scan_motors[scanID]),
         }
         return doc
 
     def _get_data_keys(self, scanID):
         sb = self.scan_bundler
         signals = {}
-        for dev in sb.primary_devices[scanID]["devices"]:
+        for dev in sb.monitored_devices[scanID]["devices"]:
             # copied from bluesky/callbacks/stream.py:
             for key, val in dev.signals.items():
                 val = val["value"]
                 # String key
                 if isinstance(val, str):
                     key_desc = {"dtype": "string", "shape": []}
                 # Iterable
@@ -73,15 +74,16 @@
             "configuration": {},
             "name": "primary",
             "hints": {
                 "samx": {"fields": ["samx"]},
                 "samy": {"fields": ["samy"]},
             },
             "object_keys": {
-                dev.name: list(dev.signals.keys()) for dev in sb.primary_devices[scanID]["devices"]
+                dev.name: list(dev.signals.keys())
+                for dev in sb.monitored_devices[scanID]["devices"]
             },
         }
         return doc
 
     def send_descriptor_document(self, scanID) -> None:
         """Bluesky only: send descriptor document"""
         doc = self._get_descriptor_document(scanID)
```

### Comparing `bec_scan_bundler-0.7.1/scan_bundler/emitter.py` & `bec_scan_bundler-0.8.0/scan_bundler/emitter.py`

 * *Files identical despite different names*

### Comparing `bec_scan_bundler-0.7.1/scan_bundler/scan_bundler.py` & `bec_scan_bundler-0.8.0/scan_bundler/scan_bundler.py`

 * *Files 10% similar despite different names*

```diff
@@ -23,15 +23,15 @@
         self.device_manager = None
         self._start_device_manager()
         self._start_device_read_consumer()
         self._start_scan_queue_consumer()
         self._start_scan_status_consumer()
 
         self.sync_storage = {}
-        self.primary_devices = {}
+        self.monitored_devices = {}
         self.monitor_devices = {}
         self.baseline_devices = {}
         self.device_storage = {}
         self.scan_motors = {}
         self.readout_priority = {}
         self.storage_initialized = set()
         self.current_queue = None
@@ -142,16 +142,16 @@
         scanID = scan_msg.content["scanID"]
         scan_info = scan_msg.content["info"]
         scan_motors = list(set(self.device_manager.devices[m] for m in scan_info["scan_motors"]))
         self.scan_motors[scanID] = scan_motors
         self.readout_priority[scanID] = scan_info["readout_priority"]
         if not scanID in self.storage_initialized:
             self.sync_storage[scanID] = {"info": scan_info, "status": "open", "sent": set()}
-            self.primary_devices[scanID] = {
-                "devices": self.device_manager.devices.primary_devices(
+            self.monitored_devices[scanID] = {
+                "devices": self.device_manager.devices.monitored_devices(
                     readout_priority=self.readout_priority[scanID]
                 ),
                 "pointID": {},
             }
             self.monitor_devices[scanID] = self.device_manager.devices.acquisition_group("monitor")
             self.baseline_devices[scanID] = {
                 "devices": self.device_manager.devices.baseline_devices(
@@ -170,35 +170,38 @@
 
     def _step_scan_update(self, scanID, device, signal, metadata):
         if "pointID" not in metadata:
             return
         with self._lock:
             dev = {device: signal}
             pointID = metadata["pointID"]
-            primary_devices = self.primary_devices[scanID]
+            monitored_devices = self.monitored_devices[scanID]
 
             self.sync_storage[scanID][pointID] = {
                 **self.sync_storage[scanID].get(pointID, {}),
                 **dev,
             }
 
-            if primary_devices["pointID"].get(pointID) is None:
-                primary_devices["pointID"][pointID] = {
-                    dev.name: False for dev in primary_devices["devices"]
+            if monitored_devices["pointID"].get(pointID) is None:
+                monitored_devices["pointID"][pointID] = {
+                    dev.name: False for dev in monitored_devices["devices"]
                 }
-            primary_devices["pointID"][pointID][device] = True
+            monitored_devices["pointID"][pointID][device] = True
 
-            primary_devices_completed = list(primary_devices["pointID"][pointID].values())
+            monitored_devices_completed = list(monitored_devices["pointID"][pointID].values())
 
-            all_primary_devices_completed = bool(
-                all(primary_devices_completed)
-                and (len(primary_devices_completed) == len(self.primary_devices[scanID]["devices"]))
+            all_monitored_devices_completed = bool(
+                all(monitored_devices_completed)
+                and (
+                    len(monitored_devices_completed)
+                    == len(self.monitored_devices[scanID]["devices"])
+                )
             )
 
-            if all_primary_devices_completed and self.sync_storage[scanID].get(pointID):
+            if all_monitored_devices_completed and self.sync_storage[scanID].get(pointID):
                 self._update_monitor_signals(scanID, pointID)
                 self._send_scan_point(scanID, pointID)
 
     def _fly_scan_update(self, scanID, device, signal, metadata):
         if "pointID" not in metadata:
             return
         with self._lock:
@@ -302,15 +305,15 @@
 
             elif stream == "baseline":
                 self._baseline_update(scanID, device, signal)
 
     def _update_monitor_signals(self, scanID, pointID) -> None:
         if self.sync_storage[scanID]["info"]["scan_type"] == "fly":
             # for fly scans, take all primary and monitor signals
-            devices = self.primary_devices[scanID]["devices"]
+            devices = self.monitored_devices[scanID]["devices"]
 
             readings = self._get_last_device_readback(devices)
 
             for read, dev in zip(readings, devices):
                 self.sync_storage[scanID][pointID][dev.name] = read
 
     def _get_last_device_readback(self, devices: list) -> list:
@@ -330,15 +333,15 @@
             if scanID in self.scanID_history:
                 continue
             remove_scanIDs.append(scanID)
 
         for scanID in remove_scanIDs:
             for storage in [
                 "sync_storage",
-                "primary_devices",
+                "monitored_devices",
                 "monitor_devices",
                 "baseline_devices",
                 "scan_motors",
                 "readout_priority",
             ]:
                 try:
                     getattr(self, storage).pop(scanID)
```

### Comparing `bec_scan_bundler-0.7.1/setup.cfg` & `bec_scan_bundler-0.8.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `bec_scan_bundler-0.7.1/setup.py` & `bec_scan_bundler-0.8.0/setup.py`

 * *Files identical despite different names*

