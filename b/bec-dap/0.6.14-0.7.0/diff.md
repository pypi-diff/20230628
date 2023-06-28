# Comparing `tmp/bec_dap-0.6.14.tar.gz` & `tmp/bec_dap-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bec_dap-0.6.14.tar", last modified: Tue Jun 27 21:03:30 2023, max compression
+gzip compressed data, was "bec_dap-0.7.0.tar", last modified: Wed Jun 28 10:26:18 2023, max compression
```

## Comparing `bec_dap-0.6.14.tar` & `bec_dap-0.7.0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:30.958958 bec_dap-0.6.14/
--rw-r--r--   0 root         (0) root         (0)      441 2023-06-27 21:03:30.958958 bec_dap-0.6.14/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:30.958958 bec_dap-0.6.14/bec_dap.egg-info/
--rw-r--r--   0 root         (0) root         (0)      441 2023-06-27 21:03:30.000000 bec_dap-0.6.14/bec_dap.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      308 2023-06-27 21:03:30.000000 bec_dap-0.6.14/bec_dap.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 21:03:30.000000 bec_dap-0.6.14/bec_dap.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        6 2023-06-27 21:03:30.000000 bec_dap-0.6.14/bec_dap.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       16 2023-06-27 21:03:30.000000 bec_dap-0.6.14/bec_dap.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:30.957959 bec_dap-0.6.14/data_processing/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-20 18:43:13.000000 bec_dap-0.6.14/data_processing/__init__.py
--rw-r--r--   0 root         (0) root         (0)      710 2023-06-20 18:43:13.000000 bec_dap-0.6.14/data_processing/dap_server.py
--rw-r--r--   0 root         (0) root         (0)     8038 2023-06-20 18:43:13.000000 bec_dap-0.6.14/data_processing/stream_processor.py
--rw-r--r--   0 root         (0) root         (0)     3522 2023-06-20 18:43:13.000000 bec_dap-0.6.14/data_processing/worker_manager.py
--rw-r--r--   0 root         (0) root         (0)      521 2023-06-27 21:03:30.959959 bec_dap-0.6.14/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      706 2023-06-23 18:57:15.000000 bec_dap-0.6.14/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:18.613515 bec_dap-0.7.0/
+-rw-r--r--   0 root         (0) root         (0)      440 2023-06-28 10:26:18.613515 bec_dap-0.7.0/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:18.612515 bec_dap-0.7.0/bec_dap.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      440 2023-06-28 10:26:18.000000 bec_dap-0.7.0/bec_dap.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      308 2023-06-28 10:26:18.000000 bec_dap-0.7.0/bec_dap.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 10:26:18.000000 bec_dap-0.7.0/bec_dap.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        6 2023-06-28 10:26:18.000000 bec_dap-0.7.0/bec_dap.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       16 2023-06-28 10:26:18.000000 bec_dap-0.7.0/bec_dap.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:18.612515 bec_dap-0.7.0/data_processing/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-20 18:41:59.000000 bec_dap-0.7.0/data_processing/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      689 2023-06-28 10:25:33.000000 bec_dap-0.7.0/data_processing/dap_server.py
+-rw-r--r--   0 root         (0) root         (0)     8024 2023-06-28 10:25:33.000000 bec_dap-0.7.0/data_processing/stream_processor.py
+-rw-r--r--   0 root         (0) root         (0)     3508 2023-06-28 10:25:33.000000 bec_dap-0.7.0/data_processing/worker_manager.py
+-rw-r--r--   0 root         (0) root         (0)      521 2023-06-28 10:26:18.613515 bec_dap-0.7.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      699 2023-06-28 10:25:33.000000 bec_dap-0.7.0/setup.py
```

### Comparing `bec_dap-0.6.14/data_processing/dap_server.py` & `bec_dap-0.7.0/data_processing/dap_server.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,10 +1,10 @@
-from bec_client_lib.core import BECService
-from bec_client_lib.core.connector import ConnectorBase
-from bec_client_lib.core.service_config import ServiceConfig
+from bec_lib.core import BECService
+from bec_lib.core.connector import ConnectorBase
+from bec_lib.core.service_config import ServiceConfig
 
 from .worker_manager import DAPWorkerManager
 
 
 class DAPServer(BECService):
     """Data processing server class."""
```

### Comparing `bec_dap-0.6.14/data_processing/stream_processor.py` & `bec_dap-0.7.0/data_processing/stream_processor.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,16 +2,16 @@
 
 import time
 from abc import ABC, abstractmethod
 from collections import deque
 from typing import Any, List, Optional, Tuple
 
 import lmfit
-from bec_client_lib.core import BECMessage, MessageEndpoints
-from bec_client_lib.core.redis_connector import MessageObject, RedisConnector
+from bec_lib.core import BECMessage, MessageEndpoints
+from bec_lib.core.redis_connector import MessageObject, RedisConnector
 
 
 def nested_get(data: str, keys, default=None):
     """
     Get a value from a nested dictionary.
 
     Args:
```

### Comparing `bec_dap-0.6.14/data_processing/worker_manager.py` & `bec_dap-0.7.0/data_processing/worker_manager.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from __future__ import annotations
 
 import multiprocessing as mp
 
-from bec_client_lib.core import BECMessage, MessageEndpoints, bec_logger
-from bec_client_lib.core.redis_connector import RedisConnector
+from bec_lib.core import BECMessage, MessageEndpoints, bec_logger
+from bec_lib.core.redis_connector import RedisConnector
 
 from .stream_processor import LmfitProcessor
 
 logger = bec_logger.logger
 
 
 class DAPWorkerManager:
```

### Comparing `bec_dap-0.6.14/setup.cfg` & `bec_dap-0.7.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `bec_dap-0.6.14/setup.py` & `bec_dap-0.7.0/setup.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import os
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

