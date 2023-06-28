# Comparing `tmp/bec_scan_server-0.6.14.tar.gz` & `tmp/bec_scan_server-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bec_scan_server-0.6.14.tar", last modified: Tue Jun 27 21:03:17 2023, max compression
+gzip compressed data, was "bec_scan_server-0.7.0.tar", last modified: Wed Jun 28 10:26:06 2023, max compression
```

## Comparing `bec_scan_server-0.6.14.tar` & `bec_scan_server-0.7.0.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:17.454378 bec_scan_server-0.6.14/
--rw-r--r--   0 root         (0) root         (0)     2541 2023-06-27 21:03:17.454378 bec_scan_server-0.6.14/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     2115 2023-06-27 20:50:04.000000 bec_scan_server-0.6.14/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:17.454378 bec_scan_server-0.6.14/bec_scan_server.egg-info/
--rw-r--r--   0 root         (0) root         (0)     2541 2023-06-27 21:03:17.000000 bec_scan_server-0.6.14/bec_scan_server.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      534 2023-06-27 21:03:17.000000 bec_scan_server-0.6.14/bec_scan_server.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 21:03:17.000000 bec_scan_server-0.6.14/bec_scan_server.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       30 2023-06-27 21:03:17.000000 bec_scan_server-0.6.14/bec_scan_server.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       12 2023-06-27 21:03:17.000000 bec_scan_server-0.6.14/bec_scan_server.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:17.453378 bec_scan_server-0.6.14/scan_server/
--rw-rw-rw-   0 root         (0) root         (0)       26 2023-04-24 15:23:42.000000 bec_scan_server-0.6.14/scan_server/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      128 2023-04-24 15:23:42.000000 bec_scan_server-0.6.14/scan_server/errors.py
--rw-rw-rw-   0 root         (0) root         (0)     3489 2023-06-19 08:14:59.000000 bec_scan_server-0.6.14/scan_server/path_optimization.py
--rw-rw-rw-   0 root         (0) root         (0)     1868 2023-06-19 08:14:59.000000 bec_scan_server-0.6.14/scan_server/scan_assembler.py
--rw-r--r--   0 root         (0) root         (0)     6944 2023-06-23 12:59:05.000000 bec_scan_server-0.6.14/scan_server/scan_guard.py
--rw-rw-rw-   0 root         (0) root         (0)     3183 2023-06-19 08:14:59.000000 bec_scan_server-0.6.14/scan_server/scan_manager.py
--rw-r--r--   0 root         (0) root         (0)    30792 2023-06-22 21:26:18.000000 bec_scan_server-0.6.14/scan_server/scan_queue.py
--rw-rw-rw-   0 root         (0) root         (0)     3577 2023-06-19 08:14:59.000000 bec_scan_server-0.6.14/scan_server/scan_server.py
--rw-rw-rw-   0 root         (0) root         (0)    13332 2023-06-19 08:14:59.000000 bec_scan_server-0.6.14/scan_server/scan_stubs.py
--rw-rw-rw-   0 root         (0) root         (0)    26663 2023-06-19 08:14:59.000000 bec_scan_server-0.6.14/scan_server/scan_worker.py
--rw-r--r--   0 root         (0) root         (0)    42739 2023-06-23 12:59:05.000000 bec_scan_server-0.6.14/scan_server/scans.py
--rw-r--r--   0 root         (0) root         (0)      513 2023-06-27 21:03:17.455378 bec_scan_server-0.6.14/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      740 2023-06-23 18:57:15.000000 bec_scan_server-0.6.14/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:06.106901 bec_scan_server-0.7.0/
+-rw-r--r--   0 root         (0) root         (0)     2560 2023-06-28 10:26:06.106901 bec_scan_server-0.7.0/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     2115 2023-06-27 20:41:55.000000 bec_scan_server-0.7.0/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:06.106901 bec_scan_server-0.7.0/bec_scan_server.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     2560 2023-06-28 10:26:06.000000 bec_scan_server-0.7.0/bec_scan_server.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      534 2023-06-28 10:26:06.000000 bec_scan_server-0.7.0/bec_scan_server.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 10:26:06.000000 bec_scan_server-0.7.0/bec_scan_server.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       73 2023-06-28 10:26:06.000000 bec_scan_server-0.7.0/bec_scan_server.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       12 2023-06-28 10:26:06.000000 bec_scan_server-0.7.0/bec_scan_server.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:06.105901 bec_scan_server-0.7.0/scan_server/
+-rw-rw-rw-   0 root         (0) root         (0)       26 2023-04-24 15:23:42.000000 bec_scan_server-0.7.0/scan_server/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      128 2023-04-24 15:23:42.000000 bec_scan_server-0.7.0/scan_server/errors.py
+-rw-rw-rw-   0 root         (0) root         (0)     3489 2023-06-19 08:15:20.000000 bec_scan_server-0.7.0/scan_server/path_optimization.py
+-rw-r--r--   0 root         (0) root         (0)     1861 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scan_assembler.py
+-rw-r--r--   0 root         (0) root         (0)     6937 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scan_guard.py
+-rw-r--r--   0 root         (0) root         (0)     3175 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scan_manager.py
+-rw-r--r--   0 root         (0) root         (0)    30785 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scan_queue.py
+-rw-r--r--   0 root         (0) root         (0)     3549 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scan_server.py
+-rw-r--r--   0 root         (0) root         (0)    13324 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scan_stubs.py
+-rw-r--r--   0 root         (0) root         (0)    26656 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scan_worker.py
+-rw-r--r--   0 root         (0) root         (0)    42711 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/scan_server/scans.py
+-rw-r--r--   0 root         (0) root         (0)      513 2023-06-28 10:26:06.106901 bec_scan_server-0.7.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      835 2023-06-28 10:25:33.000000 bec_scan_server-0.7.0/setup.py
```

### Comparing `bec_scan_server-0.6.14/PKG-INFO` & `bec_scan_server-0.7.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,20 +1,21 @@
 Metadata-Version: 2.1
 Name: bec_scan_server
-Version: 0.6.14
+Version: 0.7.0
 Summary: BEC scan server
 Home-page: https://gitlab.psi.ch/bec/bec
 License: UNKNOWN
 Project-URL: Bug Tracker, https://gitlab.psi.ch/bec/bec/issues
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Scientific/Engineering
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
+Provides-Extra: dev
 
 # BEC scan server
 
 bec-scan-server is a core Python service for the [Beamline and Experiment Control (BEC)](https://gitlab.psi.ch/bec/bec) server, tasked with the handling and orchestrating the data acquisition. 
 
 ## Installation
```

### Comparing `bec_scan_server-0.6.14/README.md` & `bec_scan_server-0.7.0/README.md`

 * *Files identical despite different names*

### Comparing `bec_scan_server-0.6.14/bec_scan_server.egg-info/PKG-INFO` & `bec_scan_server-0.7.0/bec_scan_server.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,20 +1,21 @@
 Metadata-Version: 2.1
 Name: bec-scan-server
-Version: 0.6.14
+Version: 0.7.0
 Summary: BEC scan server
 Home-page: https://gitlab.psi.ch/bec/bec
 License: UNKNOWN
 Project-URL: Bug Tracker, https://gitlab.psi.ch/bec/bec/issues
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Scientific/Engineering
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
+Provides-Extra: dev
 
 # BEC scan server
 
 bec-scan-server is a core Python service for the [Beamline and Experiment Control (BEC)](https://gitlab.psi.ch/bec/bec) server, tasked with the handling and orchestrating the data acquisition. 
 
 ## Installation
```

### Comparing `bec_scan_server-0.6.14/bec_scan_server.egg-info/SOURCES.txt` & `bec_scan_server-0.7.0/bec_scan_server.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `bec_scan_server-0.6.14/scan_server/path_optimization.py` & `bec_scan_server-0.7.0/scan_server/path_optimization.py`

 * *Files identical despite different names*

### Comparing `bec_scan_server-0.6.14/scan_server/scan_assembler.py` & `bec_scan_server-0.7.0/scan_server/scan_assembler.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 import traceback
 
-from bec_client_lib.core import BECMessage, bec_logger
+from bec_lib.core import BECMessage, bec_logger
 
 from .errors import ScanAbortion
 from .scans import RequestBase
 
 logger = bec_logger.logger
```

### Comparing `bec_scan_server-0.6.14/scan_server/scan_guard.py` & `bec_scan_server-0.7.0/scan_server/scan_guard.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import traceback
 
 import msgpack
-from bec_client_lib.core import BECMessage, MessageEndpoints, bec_logger
+from bec_lib.core import BECMessage, MessageEndpoints, bec_logger
 
 logger = bec_logger.logger
 
 
 class ScanRejection(Exception):
     pass
```

### Comparing `bec_scan_server-0.6.14/scan_server/scan_manager.py` & `bec_scan_server-0.7.0/scan_server/scan_manager.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,16 +2,15 @@
 import importlib
 import importlib.util
 import inspect
 import os
 from pathlib import Path
 
 import msgpack
-
-from bec_client_lib.core import MessageEndpoints, bec_logger
+from bec_lib.core import MessageEndpoints, bec_logger
 
 from . import scans as ScanServerScans
 
 logger = bec_logger.logger
 
 
 class ScanManager:
```

### Comparing `bec_scan_server-0.6.14/scan_server/scan_queue.py` & `bec_scan_server-0.7.0/scan_server/scan_queue.py`

 * *Files 0% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 import threading
 import time
 import traceback
 import uuid
 from enum import Enum
 from typing import List, Optional, Union
 
-from bec_client_lib.core import (
+from bec_lib.core import (
     Alarms,
     BECMessage,
     MessageEndpoints,
     bec_logger,
     threadlocked,
     timeout,
 )
```

### Comparing `bec_scan_server-0.6.14/scan_server/scan_server.py` & `bec_scan_server-0.7.0/scan_server/scan_server.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from __future__ import annotations
 
-from bec_client_lib.core import Alarms, BECMessage, BECService, BECStatus
-from bec_client_lib.core import DeviceManagerBase as DeviceManager
-from bec_client_lib.core import MessageEndpoints, ServiceConfig, bec_logger
-from bec_client_lib.core.connector import ConnectorBase
+from bec_lib.core import Alarms, BECMessage, BECService, BECStatus
+from bec_lib.core import DeviceManagerBase as DeviceManager
+from bec_lib.core import MessageEndpoints, ServiceConfig, bec_logger
+from bec_lib.core.connector import ConnectorBase
 
 from .scan_assembler import ScanAssembler
 from .scan_guard import ScanGuard
 from .scan_manager import ScanManager
 from .scan_queue import QueueManager
 from .scan_worker import ScanWorker
```

### Comparing `bec_scan_server-0.6.14/scan_server/scan_stubs.py` & `bec_scan_server-0.7.0/scan_server/scan_stubs.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,14 +1,13 @@
 import time
 import uuid
 from typing import Callable, List, Union
 
 import numpy as np
-
-from bec_client_lib.core import (
+from bec_lib.core import (
     BECMessage,
     MessageEndpoints,
     ProducerConnector,
     Status,
     bec_logger,
 )
```

### Comparing `bec_scan_server-0.6.14/scan_server/scan_worker.py` & `bec_scan_server-0.7.0/scan_server/scan_worker.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import datetime
 import threading
 import time
 import traceback
 from asyncio.log import logger
 from typing import List
 
-from bec_client_lib.core import (
+from bec_lib.core import (
     Alarms,
     BECMessage,
     Device,
     DeviceStatus,
     MessageEndpoints,
     bec_logger,
 )
```

### Comparing `bec_scan_server-0.6.14/scan_server/scans.py` & `bec_scan_server-0.7.0/scan_server/scans.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,20 +1,15 @@
 import ast
 import enum
 import time
 from abc import ABC, abstractmethod
 from typing import List, Tuple
 
 import numpy as np
-from bec_client_lib.core import (
-    BECMessage,
-    DeviceManagerBase,
-    MessageEndpoints,
-    bec_logger,
-)
+from bec_lib.core import BECMessage, DeviceManagerBase, MessageEndpoints, bec_logger
 from cytoolz import partition
 
 from .errors import LimitError, ScanAbortion
 from .path_optimization import PathOptimizerMixin
 from .scan_stubs import ScanStubs
 
 DeviceMsg = BECMessage.DeviceInstructionMessage
```

### Comparing `bec_scan_server-0.6.14/setup.cfg` & `bec_scan_server-0.7.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `bec_scan_server-0.6.14/setup.py` & `bec_scan_server-0.7.0/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -2,24 +2,28 @@
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
         version = res.split("=")[1]
     return version.strip().strip('"')
 
 
 if __name__ == "__main__":
-    setup(install_requires=["numpy", "cytoolz", "rich", "matplotlib"], version=get_version())
+    setup(
+        install_requires=["numpy", "cytoolz", "rich", "matplotlib"],
+        version=get_version(),
+        extras_require={"dev": ["pytest", "pytest-random-order", "coverage"]},
+    )
     local_deps = [utils]
     for dep in local_deps:
         subprocess.run(f"pip install -e {dep}", shell=True, check=True)
```

