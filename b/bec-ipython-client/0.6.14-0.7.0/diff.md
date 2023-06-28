# Comparing `tmp/bec_ipython_client-0.6.14.tar.gz` & `tmp/bec_ipython_client-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bec_ipython_client-0.6.14.tar", last modified: Tue Jun 27 21:02:56 2023, max compression
+gzip compressed data, was "bec_ipython_client-0.7.0.tar", last modified: Wed Jun 28 10:25:47 2023, max compression
```

## Comparing `bec_ipython_client-0.6.14.tar` & `bec_ipython_client-0.7.0.tar`

### file list

```diff
@@ -1,43 +1,43 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.860017 bec_ipython_client-0.6.14/
--rw-r--r--   0 root         (0) root         (0)      439 2023-06-27 21:02:56.860017 bec_ipython_client-0.6.14/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.857017 bec_ipython_client-0.6.14/bec_client/
--rw-rw-rw-   0 root         (0) root         (0)       85 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     1091 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/beamline_mixin.py
--rw-rw-rw-   0 root         (0) root         (0)     4692 2023-06-19 13:49:39.000000 bec_ipython_client-0.6.14/bec_client/bec_client.py
--rw-rw-rw-   0 root         (0) root         (0)     1972 2023-06-19 13:49:39.000000 bec_ipython_client-0.6.14/bec_client/bec_magics.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.859017 bec_ipython_client-0.6.14/bec_client/bin/
--rwxrwxrwx   0 root         (0) root         (0)      176 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/bin/bec
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.858017 bec_ipython_client-0.6.14/bec_client/callbacks/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-04-24 15:23:42.000000 bec_ipython_client-0.6.14/bec_client/callbacks/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     7490 2023-06-19 13:49:39.000000 bec_ipython_client-0.6.14/bec_client/callbacks/ipython_live_updates.py
--rw-rw-rw-   0 root         (0) root         (0)     9277 2023-06-19 13:49:39.000000 bec_ipython_client-0.6.14/bec_client/callbacks/live_table.py
--rw-rw-rw-   0 root         (0) root         (0)     4556 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/callbacks/move_device.py
--rw-rw-rw-   0 root         (0) root         (0)     3750 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/callbacks/utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.858017 bec_ipython_client-0.6.14/bec_client/plugins/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.858017 bec_ipython_client-0.6.14/bec_client/plugins/LamNI/
--rw-rw-rw-   0 root         (0) root         (0)      149 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/LamNI/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     5519 2023-06-19 13:49:39.000000 bec_ipython_client-0.6.14/bec_client/plugins/LamNI/lamni_optics_mixin.py
--rwxrwxrwx   0 root         (0) root         (0)      895 2023-04-24 15:23:42.000000 bec_ipython_client-0.6.14/bec_client/plugins/LamNI/load_additional_correction.py
--rw-rw-rw-   0 root         (0) root         (0)    54664 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/LamNI/x_ray_eye_align.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.859017 bec_ipython_client-0.6.14/bec_client/plugins/SLS/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/SLS/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     4926 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/SLS/sls_info.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.859017 bec_ipython_client-0.6.14/bec_client/plugins/XTreme/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/XTreme/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     3631 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/XTreme/x-treme.py
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-04-24 15:23:42.000000 bec_ipython_client-0.6.14/bec_client/plugins/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.859017 bec_ipython_client-0.6.14/bec_client/plugins/cSAXS/
--rw-rw-rw-   0 root         (0) root         (0)       79 2023-04-24 15:23:42.000000 bec_ipython_client-0.6.14/bec_client/plugins/cSAXS/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     4433 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/cSAXS/beamline_info.py
--rw-rw-rw-   0 root         (0) root         (0)      445 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/plugins/cSAXS/cSAXS_beamline.py
--rw-rw-rw-   0 root         (0) root         (0)     2609 2023-04-24 15:23:42.000000 bec_ipython_client-0.6.14/bec_client/prettytable.py
--rw-rw-rw-   0 root         (0) root         (0)     8455 2023-04-24 15:23:42.000000 bec_ipython_client-0.6.14/bec_client/progressbar.py
--rw-rw-rw-   0 root         (0) root         (0)     4028 2023-06-19 08:14:59.000000 bec_ipython_client-0.6.14/bec_client/signals.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:02:56.860017 bec_ipython_client-0.6.14/bec_ipython_client.egg-info/
--rw-r--r--   0 root         (0) root         (0)      439 2023-06-27 21:02:56.000000 bec_ipython_client-0.6.14/bec_ipython_client.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     1130 2023-06-27 21:02:56.000000 bec_ipython_client-0.6.14/bec_ipython_client.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 21:02:56.000000 bec_ipython_client-0.6.14/bec_ipython_client.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       91 2023-06-27 21:02:56.000000 bec_ipython_client-0.6.14/bec_ipython_client.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       11 2023-06-27 21:02:56.000000 bec_ipython_client-0.6.14/bec_ipython_client.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)      519 2023-06-27 21:02:56.861017 bec_ipython_client-0.6.14/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1113 2023-06-23 18:57:15.000000 bec_ipython_client-0.6.14/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.056488 bec_ipython_client-0.7.0/
+-rw-r--r--   0 root         (0) root         (0)      458 2023-06-28 10:25:47.056488 bec_ipython_client-0.7.0/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.052488 bec_ipython_client-0.7.0/bec_client/
+-rw-rw-rw-   0 root         (0) root         (0)       85 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     1091 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/beamline_mixin.py
+-rw-r--r--   0 root         (0) root         (0)     4664 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/bec_client/bec_client.py
+-rw-rw-rw-   0 root         (0) root         (0)     1972 2023-06-19 13:38:11.000000 bec_ipython_client-0.7.0/bec_client/bec_magics.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.055488 bec_ipython_client-0.7.0/bec_client/bin/
+-rwxrwxrwx   0 root         (0) root         (0)      176 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/bin/bec
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.053488 bec_ipython_client-0.7.0/bec_client/callbacks/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-04-24 15:23:42.000000 bec_ipython_client-0.7.0/bec_client/callbacks/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7462 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/bec_client/callbacks/ipython_live_updates.py
+-rw-r--r--   0 root         (0) root         (0)     9270 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/bec_client/callbacks/live_table.py
+-rw-r--r--   0 root         (0) root         (0)     4549 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/bec_client/callbacks/move_device.py
+-rw-r--r--   0 root         (0) root         (0)     3736 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/bec_client/callbacks/utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.053488 bec_ipython_client-0.7.0/bec_client/plugins/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.054488 bec_ipython_client-0.7.0/bec_client/plugins/LamNI/
+-rw-rw-rw-   0 root         (0) root         (0)      149 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/plugins/LamNI/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     5519 2023-06-19 13:38:11.000000 bec_ipython_client-0.7.0/bec_client/plugins/LamNI/lamni_optics_mixin.py
+-rwxrwxrwx   0 root         (0) root         (0)      895 2023-04-24 15:23:42.000000 bec_ipython_client-0.7.0/bec_client/plugins/LamNI/load_additional_correction.py
+-rw-r--r--   0 root         (0) root         (0)    54643 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/bec_client/plugins/LamNI/x_ray_eye_align.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.054488 bec_ipython_client-0.7.0/bec_client/plugins/SLS/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/plugins/SLS/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     4926 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/plugins/SLS/sls_info.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.054488 bec_ipython_client-0.7.0/bec_client/plugins/XTreme/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/plugins/XTreme/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     3631 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/plugins/XTreme/x-treme.py
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-04-24 15:23:42.000000 bec_ipython_client-0.7.0/bec_client/plugins/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.055488 bec_ipython_client-0.7.0/bec_client/plugins/cSAXS/
+-rw-rw-rw-   0 root         (0) root         (0)       79 2023-04-24 15:23:42.000000 bec_ipython_client-0.7.0/bec_client/plugins/cSAXS/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     4433 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/plugins/cSAXS/beamline_info.py
+-rw-rw-rw-   0 root         (0) root         (0)      445 2023-06-19 08:15:20.000000 bec_ipython_client-0.7.0/bec_client/plugins/cSAXS/cSAXS_beamline.py
+-rw-rw-rw-   0 root         (0) root         (0)     2609 2023-04-24 15:23:42.000000 bec_ipython_client-0.7.0/bec_client/prettytable.py
+-rw-rw-rw-   0 root         (0) root         (0)     8455 2023-04-24 15:23:42.000000 bec_ipython_client-0.7.0/bec_client/progressbar.py
+-rw-r--r--   0 root         (0) root         (0)     4021 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/bec_client/signals.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:25:47.055488 bec_ipython_client-0.7.0/bec_ipython_client.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      458 2023-06-28 10:25:46.000000 bec_ipython_client-0.7.0/bec_ipython_client.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     1130 2023-06-28 10:25:47.000000 bec_ipython_client-0.7.0/bec_ipython_client.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 10:25:46.000000 bec_ipython_client-0.7.0/bec_ipython_client.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      154 2023-06-28 10:25:46.000000 bec_ipython_client-0.7.0/bec_ipython_client.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       11 2023-06-28 10:25:46.000000 bec_ipython_client-0.7.0/bec_ipython_client.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)      519 2023-06-28 10:25:47.056488 bec_ipython_client-0.7.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1157 2023-06-28 10:25:33.000000 bec_ipython_client-0.7.0/setup.py
```

### Comparing `bec_ipython_client-0.6.14/bec_client/beamline_mixin.py` & `bec_ipython_client-0.7.0/bec_client/beamline_mixin.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/bec_client.py` & `bec_ipython_client-0.7.0/bec_client/bec_client.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 from __future__ import print_function
 
 import threading
 import time
 
 import IPython
-from bec_client_lib.alarm_handler import AlarmBase
-from bec_client_lib.client import BECClient
-from bec_client_lib.core import ServiceConfig, bec_logger
-from bec_client_lib.core.connector import ConnectorBase
+from bec_lib.alarm_handler import AlarmBase
+from bec_lib.client import BECClient
+from bec_lib.core import ServiceConfig, bec_logger
+from bec_lib.core.connector import ConnectorBase
 from IPython.terminal.prompts import Prompts, Token
 
 from .beamline_mixin import BeamlineMixin
 from .bec_magics import BECMagics
 from .callbacks.ipython_live_updates import IPythonLiveUpdates
 from .signals import ScanInterruption, SigintHandler
```

### Comparing `bec_ipython_client-0.6.14/bec_client/bec_magics.py` & `bec_ipython_client-0.7.0/bec_client/bec_magics.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/callbacks/ipython_live_updates.py` & `bec_ipython_client-0.7.0/bec_client/callbacks/ipython_live_updates.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,24 +1,24 @@
 from __future__ import annotations
 
 import asyncio
 import collections
 import time
 from typing import TYPE_CHECKING
 
-from bec_client_lib.core import bec_logger
-from bec_client_lib.core.bec_errors import ScanInterruption
+from bec_lib.core import bec_logger
+from bec_lib.core.bec_errors import ScanInterruption
 
 from .live_table import LiveUpdatesTable
 from .move_device import LiveUpdatesReadbackProgressbar
 from .utils import ScanRequestMixin, check_alarms
 
 if TYPE_CHECKING:
-    from bec_client_lib.core import BECMessage
-    from bec_client_lib.queue_items import QueueItem
+    from bec_lib.core import BECMessage
+    from bec_lib.queue_items import QueueItem
 
     from bec_client import BECClient
 
 logger = bec_logger.logger
 
 
 class IPythonLiveUpdates:
```

### Comparing `bec_ipython_client-0.6.14/bec_client/callbacks/live_table.py` & `bec_ipython_client-0.7.0/bec_client/callbacks/live_table.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from __future__ import annotations
 
 import asyncio
 from typing import TYPE_CHECKING, Callable, List
 
-from bec_client_lib.core import BECMessage, bec_logger
+from bec_lib.core import BECMessage, bec_logger
 
 from bec_client.prettytable import PrettyTable
 from bec_client.progressbar import ScanProgressBar
 
 from .utils import LiveUpdatesBase, check_alarms
 
 if TYPE_CHECKING:
```

### Comparing `bec_ipython_client-0.6.14/bec_client/callbacks/move_device.py` & `bec_ipython_client-0.7.0/bec_client/callbacks/move_device.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from __future__ import annotations
 
 from typing import TYPE_CHECKING, Callable, List
 
 import numpy as np
+from bec_lib.core import BECMessage, DeviceManagerBase, MessageEndpoints
 
 from bec_client.progressbar import DeviceProgressBar
-from bec_client_lib.core import BECMessage, DeviceManagerBase, MessageEndpoints
 
 from .utils import LiveUpdatesBase, check_alarms
 
 if TYPE_CHECKING:
     from bec_client.bec_client import BECClient
```

### Comparing `bec_ipython_client-0.6.14/bec_client/callbacks/utils.py` & `bec_ipython_client-0.7.0/bec_client/callbacks/utils.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,16 +3,16 @@
 import abc
 import asyncio
 import threading
 import time
 import traceback
 from typing import TYPE_CHECKING, Callable, List
 
-from bec_client_lib.core import Alarms, BECMessage, bec_logger
-from bec_client_lib.request_items import RequestItem
+from bec_lib.core import Alarms, BECMessage, bec_logger
+from bec_lib.request_items import RequestItem
 
 if TYPE_CHECKING:
     from bec_client.bec_client import BECClient
 
 logger = bec_logger.logger
```

### Comparing `bec_ipython_client-0.6.14/bec_client/plugins/LamNI/lamni_optics_mixin.py` & `bec_ipython_client-0.7.0/bec_client/plugins/LamNI/lamni_optics_mixin.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/plugins/LamNI/load_additional_correction.py` & `bec_ipython_client-0.7.0/bec_client/plugins/LamNI/load_additional_correction.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/plugins/LamNI/x_ray_eye_align.py` & `bec_ipython_client-0.7.0/bec_client/plugins/LamNI/x_ray_eye_align.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,20 +5,20 @@
 import threading
 import time
 from collections import defaultdict
 from pathlib import Path
 
 import h5py
 import numpy as np
+from bec_lib.alarm_handler import AlarmBase
+from bec_lib.core import bec_logger
+from bec_lib.core.pdf_writer import PDFWriter
 from typeguard import typechecked
 
 from bec_client.plugins.cSAXS import epics_get, epics_put, fshclose, fshopen
-from bec_client_lib.alarm_handler import AlarmBase
-from bec_client_lib.core import bec_logger
-from bec_client_lib.core.pdf_writer import PDFWriter
 
 from .lamni_optics_mixin import LamNIOpticsMixin
 
 logger = bec_logger.logger
 bec = builtins.__dict__.get("bec")
```

### Comparing `bec_ipython_client-0.6.14/bec_client/plugins/SLS/sls_info.py` & `bec_ipython_client-0.7.0/bec_client/plugins/SLS/sls_info.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/plugins/XTreme/x-treme.py` & `bec_ipython_client-0.7.0/bec_client/plugins/XTreme/x-treme.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/plugins/cSAXS/beamline_info.py` & `bec_ipython_client-0.7.0/bec_client/plugins/cSAXS/beamline_info.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/prettytable.py` & `bec_ipython_client-0.7.0/bec_client/prettytable.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/progressbar.py` & `bec_ipython_client-0.7.0/bec_client/progressbar.py`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/bec_client/signals.py` & `bec_ipython_client-0.7.0/bec_client/signals.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 import signal
 import threading
 import time
 
-from bec_client_lib.core.bec_errors import ScanInterruption
+from bec_lib.core.bec_errors import ScanInterruption
 
 PAUSE_MSG = """
 The Scan Queue is entering a paused state. These are your options for changing
 the state of the queue:
 
 %resume              Resume the scan.
 %restart             Restart the scan.
```

### Comparing `bec_ipython_client-0.6.14/bec_ipython_client.egg-info/SOURCES.txt` & `bec_ipython_client-0.7.0/bec_ipython_client.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/setup.cfg` & `bec_ipython_client-0.7.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `bec_ipython_client-0.6.14/setup.py` & `bec_ipython_client-0.7.0/setup.py`

 * *Files 18% similar despite different names*

```diff
@@ -2,16 +2,15 @@
 import pathlib
 import subprocess
 
 from setuptools import setup
 
 current_path = pathlib.Path(__file__).parent.resolve()
 
-utils = f"{current_path}/../bec_client_lib/"
-bec_client_lib = f"{current_path}/../bec_client_lib/"
+bec_lib = f"{current_path}/../bec_lib/"
 
 
 def get_version():
     """load the version from the version file"""
     version_file = os.path.join(current_path, "../semantic_release", "__init__.py")
     with open(version_file, "r", encoding="utf-8") as file:
         res = file.readline()
@@ -30,14 +29,16 @@
             "redis",
             "ipython",
             "cytoolz",
             "rich",
             "pyepics",
             "pylint",
             "fpdf",
+            "h5py",
         ],
         scripts=["bec_client/bin/bec"],
         version=get_version(),
+        extras_require={"dev": ["pytest", "pytest-random-order", "pytest-asyncio", "coverage"]},
     )
-    local_deps = [utils, bec_client_lib]
+    local_deps = [bec_lib]
     for dep in local_deps:
         subprocess.run(f"pip install -e {dep}", shell=True, check=True)
```

