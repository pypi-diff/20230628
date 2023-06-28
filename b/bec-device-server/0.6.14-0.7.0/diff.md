# Comparing `tmp/bec_device_server-0.6.14.tar.gz` & `tmp/bec_device_server-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bec_device_server-0.6.14.tar", last modified: Tue Jun 27 21:03:20 2023, max compression
+gzip compressed data, was "bec_device_server-0.7.0.tar", last modified: Wed Jun 28 10:26:09 2023, max compression
```

## Comparing `bec_device_server-0.6.14.tar` & `bec_device_server-0.7.0.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:20.290290 bec_device_server-0.6.14/
--rw-r--r--   0 root         (0) root         (0)      496 2023-06-27 21:03:20.290290 bec_device_server-0.6.14/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:20.290290 bec_device_server-0.6.14/bec_device_server.egg-info/
--rw-r--r--   0 root         (0) root         (0)      496 2023-06-27 21:03:20.000000 bec_device_server-0.6.14/bec_device_server.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      454 2023-06-27 21:03:20.000000 bec_device_server-0.6.14/bec_device_server.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 21:03:20.000000 bec_device_server-0.6.14/bec_device_server.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       39 2023-06-27 21:03:20.000000 bec_device_server-0.6.14/bec_device_server.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       14 2023-06-27 21:03:20.000000 bec_device_server-0.6.14/bec_device_server.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:20.288290 bec_device_server-0.6.14/device_server/
--rw-rw-rw-   0 root         (0) root         (0)      168 2023-06-19 08:14:59.000000 bec_device_server-0.6.14/device_server/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    18561 2023-06-19 08:14:59.000000 bec_device_server-0.6.14/device_server/device_server.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:20.289290 bec_device_server-0.6.14/device_server/devices/
--rw-rw-rw-   0 root         (0) root         (0)      166 2023-06-19 08:14:59.000000 bec_device_server-0.6.14/device_server/devices/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     3480 2023-06-19 08:14:59.000000 bec_device_server-0.6.14/device_server/devices/config_update_handler.py
--rw-rw-rw-   0 root         (0) root         (0)     3104 2023-06-19 08:14:59.000000 bec_device_server-0.6.14/device_server/devices/device_serializer.py
--rw-rw-rw-   0 root         (0) root         (0)    13020 2023-06-19 13:49:39.000000 bec_device_server-0.6.14/device_server/devices/devicemanager.py
--rw-r--r--   0 root         (0) root         (0)      576 2023-06-27 21:03:20.291290 bec_device_server-0.6.14/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      879 2023-06-23 18:57:15.000000 bec_device_server-0.6.14/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:09.168806 bec_device_server-0.7.0/
+-rw-r--r--   0 root         (0) root         (0)      495 2023-06-28 10:26:09.168806 bec_device_server-0.7.0/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:09.168806 bec_device_server-0.7.0/bec_device_server.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      495 2023-06-28 10:26:09.000000 bec_device_server-0.7.0/bec_device_server.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      454 2023-06-28 10:26:09.000000 bec_device_server-0.7.0/bec_device_server.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 10:26:09.000000 bec_device_server-0.7.0/bec_device_server.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       39 2023-06-28 10:26:09.000000 bec_device_server-0.7.0/bec_device_server.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       14 2023-06-28 10:26:09.000000 bec_device_server-0.7.0/bec_device_server.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:09.167806 bec_device_server-0.7.0/device_server/
+-rw-r--r--   0 root         (0) root         (0)      161 2023-06-28 10:25:33.000000 bec_device_server-0.7.0/device_server/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    18508 2023-06-28 10:25:33.000000 bec_device_server-0.7.0/device_server/device_server.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:09.167806 bec_device_server-0.7.0/device_server/devices/
+-rw-r--r--   0 root         (0) root         (0)      159 2023-06-28 10:25:33.000000 bec_device_server-0.7.0/device_server/devices/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3473 2023-06-28 10:25:33.000000 bec_device_server-0.7.0/device_server/devices/config_update_handler.py
+-rw-r--r--   0 root         (0) root         (0)     3096 2023-06-28 10:25:33.000000 bec_device_server-0.7.0/device_server/devices/device_serializer.py
+-rw-r--r--   0 root         (0) root         (0)    13006 2023-06-28 10:25:33.000000 bec_device_server-0.7.0/device_server/devices/devicemanager.py
+-rw-r--r--   0 root         (0) root         (0)      576 2023-06-28 10:26:09.169807 bec_device_server-0.7.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      872 2023-06-28 10:25:33.000000 bec_device_server-0.7.0/setup.py
```

### Comparing `bec_device_server-0.6.14/device_server/device_server.py` & `bec_device_server-0.7.0/device_server/device_server.py`

 * *Files 1% similar despite different names*

```diff
@@ -4,27 +4,21 @@
 import time
 import traceback
 from concurrent.futures import ThreadPoolExecutor
 from io import StringIO
 from typing import Any
 
 import ophyd
+from bec_lib.core import Alarms, BECMessage, BECService, MessageEndpoints, bec_logger
+from bec_lib.core.BECMessage import BECStatus
+from bec_lib.core.connector import ConnectorBase
+from bec_lib.core.devicemanager import OnFailure
 from ophyd import Staged
 from ophyd.utils import errors as ophyd_errors
 
-from bec_client_lib.core import (
-    Alarms,
-    BECMessage,
-    BECService,
-    MessageEndpoints,
-    bec_logger,
-)
-from bec_client_lib.core.BECMessage import BECStatus
-from bec_client_lib.core.connector import ConnectorBase
-from bec_client_lib.core.devicemanager import OnFailure
 from device_server.devices import is_serializable, rgetattr
 from device_server.devices.devicemanager import DeviceManagerDS
 
 logger = bec_logger.logger
 
 consumer_stop = threading.Event()
```

### Comparing `bec_device_server-0.6.14/device_server/devices/config_update_handler.py` & `bec_device_server-0.7.0/device_server/devices/config_update_handler.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from __future__ import annotations
 
 import traceback
 from typing import TYPE_CHECKING
 
-from bec_client_lib.core import (
+from bec_lib.core import (
     BECMessage,
     BECStatus,
     DeviceConfigError,
     MessageEndpoints,
     bec_logger,
 )
```

### Comparing `bec_device_server-0.6.14/device_server/devices/device_serializer.py` & `bec_device_server-0.7.0/device_server/devices/device_serializer.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,11 @@
 import msgpack
+from bec_lib.core.numpy_encoder import numpy_encode
 from ophyd import Device, PositionerBase, Signal
 
-from bec_client_lib.core.numpy_encoder import numpy_encode
-
 
 def is_serializable(var) -> bool:
     """check if an object is serializable"""
     try:
         msgpack.dumps(var, default=numpy_encode)
         return True
     except (TypeError, OverflowError):
```

### Comparing `bec_device_server-0.6.14/device_server/devices/devicemanager.py` & `bec_device_server-0.7.0/device_server/devices/devicemanager.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,26 +1,26 @@
 import inspect
 import traceback
 from functools import reduce
 
 import ophyd
 import ophyd.sim as ops
 import ophyd_devices as opd
-from ophyd.ophydobj import OphydObject
-from ophyd.signal import EpicsSignalBase
-
-from bec_client_lib.core import (
+from bec_lib.core import (
     BECMessage,
     Device,
     DeviceConfigError,
     DeviceManagerBase,
     MessageEndpoints,
     bec_logger,
 )
-from bec_client_lib.core.connector import ConnectorBase
+from bec_lib.core.connector import ConnectorBase
+from ophyd.ophydobj import OphydObject
+from ophyd.signal import EpicsSignalBase
+
 from device_server.devices.config_update_handler import ConfigUpdateHandler
 from device_server.devices.device_serializer import get_device_info
 
 logger = bec_logger.logger
 
 
 def rgetattr(obj, attr, *args):
```

### Comparing `bec_device_server-0.6.14/setup.cfg` & `bec_device_server-0.7.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `bec_device_server-0.6.14/setup.py` & `bec_device_server-0.7.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 import pathlib
 import subprocess
 
 from setuptools import setup
 
 current_path = pathlib.Path(__file__).parent.resolve()
 
-utils = f"{current_path}/../bec_client_lib/"
+utils = f"{current_path}/../bec_lib/"
 
 ophyd_devices = os.getenv("OPHYD_DEVICES_PATH", f"{current_path}/../../ophyd_devices/")
 
 
 def get_version():
     """load the version from the version file"""
     version_file = os.path.join(current_path, "../semantic_release", "__init__.py")
```

