# Comparing `tmp/bec_scan_bundler-0.6.14.tar.gz` & `tmp/bec_scan_bundler-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bec_scan_bundler-0.6.14.tar", last modified: Tue Jun 27 21:03:24 2023, max compression
+gzip compressed data, was "bec_scan_bundler-0.7.0.tar", last modified: Wed Jun 28 10:26:12 2023, max compression
```

## Comparing `bec_scan_bundler-0.6.14.tar` & `bec_scan_bundler-0.7.0.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:24.271166 bec_scan_bundler-0.6.14/
--rw-r--r--   0 root         (0) root         (0)      471 2023-06-27 21:03:24.271166 bec_scan_bundler-0.6.14/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:24.271166 bec_scan_bundler-0.6.14/bec_scan_bundler.egg-info/
--rw-r--r--   0 root         (0) root         (0)      471 2023-06-27 21:03:24.000000 bec_scan_bundler-0.6.14/bec_scan_bundler.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      365 2023-06-27 21:03:24.000000 bec_scan_bundler-0.6.14/bec_scan_bundler.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 21:03:24.000000 bec_scan_bundler-0.6.14/bec_scan_bundler.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        6 2023-06-27 21:03:24.000000 bec_scan_bundler-0.6.14/bec_scan_bundler.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 21:03:24.000000 bec_scan_bundler-0.6.14/bec_scan_bundler.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:24.270166 bec_scan_bundler-0.6.14/scan_bundler/
--rw-rw-rw-   0 root         (0) root         (0)       38 2023-04-24 15:23:42.000000 bec_scan_bundler-0.6.14/scan_bundler/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     1712 2023-06-19 08:14:59.000000 bec_scan_bundler-0.6.14/scan_bundler/bec_emitter.py
--rw-rw-rw-   0 root         (0) root         (0)     5478 2023-06-19 08:14:59.000000 bec_scan_bundler-0.6.14/scan_bundler/bluesky_emitter.py
--rw-rw-rw-   0 root         (0) root         (0)     1855 2023-06-19 08:14:59.000000 bec_scan_bundler-0.6.14/scan_bundler/emitter.py
--rw-rw-rw-   0 root         (0) root         (0)    14677 2023-06-19 08:14:59.000000 bec_scan_bundler-0.6.14/scan_bundler/scan_bundler.py
--rw-r--r--   0 root         (0) root         (0)      551 2023-06-27 21:03:24.271166 bec_scan_bundler-0.6.14/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      707 2023-06-23 18:57:15.000000 bec_scan_bundler-0.6.14/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:12.651699 bec_scan_bundler-0.7.0/
+-rw-r--r--   0 root         (0) root         (0)      470 2023-06-28 10:26:12.651699 bec_scan_bundler-0.7.0/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:12.651699 bec_scan_bundler-0.7.0/bec_scan_bundler.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      470 2023-06-28 10:26:12.000000 bec_scan_bundler-0.7.0/bec_scan_bundler.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      365 2023-06-28 10:26:12.000000 bec_scan_bundler-0.7.0/bec_scan_bundler.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 10:26:12.000000 bec_scan_bundler-0.7.0/bec_scan_bundler.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        6 2023-06-28 10:26:12.000000 bec_scan_bundler-0.7.0/bec_scan_bundler.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-28 10:26:12.000000 bec_scan_bundler-0.7.0/bec_scan_bundler.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:12.650699 bec_scan_bundler-0.7.0/scan_bundler/
+-rw-rw-rw-   0 root         (0) root         (0)       38 2023-04-24 15:23:42.000000 bec_scan_bundler-0.7.0/scan_bundler/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     1705 2023-06-28 10:25:33.000000 bec_scan_bundler-0.7.0/scan_bundler/bec_emitter.py
+-rw-r--r--   0 root         (0) root         (0)     5470 2023-06-28 10:25:33.000000 bec_scan_bundler-0.7.0/scan_bundler/bluesky_emitter.py
+-rw-r--r--   0 root         (0) root         (0)     1848 2023-06-28 10:25:33.000000 bec_scan_bundler-0.7.0/scan_bundler/emitter.py
+-rw-r--r--   0 root         (0) root         (0)    14649 2023-06-28 10:25:33.000000 bec_scan_bundler-0.7.0/scan_bundler/scan_bundler.py
+-rw-r--r--   0 root         (0) root         (0)      551 2023-06-28 10:26:12.652699 bec_scan_bundler-0.7.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      700 2023-06-28 10:25:33.000000 bec_scan_bundler-0.7.0/setup.py
```

### Comparing `bec_scan_bundler-0.6.14/scan_bundler/bec_emitter.py` & `bec_scan_bundler-0.7.0/scan_bundler/bec_emitter.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from __future__ import annotations
 
 from typing import TYPE_CHECKING
 
-from bec_client_lib.core import BECMessage, MessageEndpoints, bec_logger
+from bec_lib.core import BECMessage, MessageEndpoints, bec_logger
 
 from .emitter import EmitterBase
 
 logger = bec_logger.logger
 
 if TYPE_CHECKING:
     from .scan_bundler import ScanBundler
```

### Comparing `bec_scan_bundler-0.6.14/scan_bundler/bluesky_emitter.py` & `bec_scan_bundler-0.7.0/scan_bundler/bluesky_emitter.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,16 +3,15 @@
 import time
 import uuid
 from collections.abc import Iterable
 from typing import TYPE_CHECKING
 
 import msgpack
 import numpy as np
-
-from bec_client_lib.core import MessageEndpoints, bec_logger
+from bec_lib.core import MessageEndpoints, bec_logger
 
 from .emitter import EmitterBase
 
 logger = bec_logger.logger
 
 if TYPE_CHECKING:
     from .scan_bundler import ScanBundler
```

### Comparing `bec_scan_bundler-0.6.14/scan_bundler/emitter.py` & `bec_scan_bundler-0.7.0/scan_bundler/emitter.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 import threading
 import time
 from queue import Queue
 
-from bec_client_lib.core import BECMessage
+from bec_lib.core import BECMessage
 
 
 class EmitterBase:
     def __init__(self, producer) -> None:
         self._send_buffer = Queue()
         self.producer = producer
         self._start_buffered_producer()
```

### Comparing `bec_scan_bundler-0.6.14/scan_bundler/scan_bundler.py` & `bec_scan_bundler-0.7.0/scan_bundler/scan_bundler.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 import collections
 import threading
 import time
 import traceback
 from concurrent.futures import ThreadPoolExecutor
 from typing import Callable
 
-from bec_client_lib.core import BECMessage, BECService
-from bec_client_lib.core import DeviceManagerBase as DeviceManager
-from bec_client_lib.core import MessageEndpoints, bec_logger
-from bec_client_lib.core.connector import ConnectorBase
+from bec_lib.core import BECMessage, BECService
+from bec_lib.core import DeviceManagerBase as DeviceManager
+from bec_lib.core import MessageEndpoints, bec_logger
+from bec_lib.core.connector import ConnectorBase
 
 from .bec_emitter import BECEmitter
 from .bluesky_emitter import BlueskyEmitter
 
 logger = bec_logger.logger
```

### Comparing `bec_scan_bundler-0.6.14/setup.cfg` & `bec_scan_bundler-0.7.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `bec_scan_bundler-0.6.14/setup.py` & `bec_scan_bundler-0.7.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 import pathlib
 import subprocess
 
 from setuptools import setup
 
 current_path = pathlib.Path(__file__).parent.resolve()
 
-utils = f"{current_path}/../bec_client_lib/"
+utils = f"{current_path}/../bec_lib/"
 
 
 def get_version():
     """load the version from the version file"""
     version_file = os.path.join(current_path, "../semantic_release", "__init__.py")
     with open(version_file, "r", encoding="utf-8") as file:
         res = file.readline()
```

