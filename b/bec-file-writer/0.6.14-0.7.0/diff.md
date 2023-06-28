# Comparing `tmp/bec_file_writer-0.6.14.tar.gz` & `tmp/bec_file_writer-0.7.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bec_file_writer-0.6.14.tar", last modified: Tue Jun 27 21:03:27 2023, max compression
+gzip compressed data, was "bec_file_writer-0.7.0.tar", last modified: Wed Jun 28 10:26:15 2023, max compression
```

## Comparing `bec_file_writer-0.6.14.tar` & `bec_file_writer-0.7.0.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:27.720059 bec_file_writer-0.6.14/
--rw-r--r--   0 root         (0) root         (0)      456 2023-06-27 21:03:27.720059 bec_file_writer-0.6.14/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:27.720059 bec_file_writer-0.6.14/bec_file_writer.egg-info/
--rw-r--r--   0 root         (0) root         (0)      456 2023-06-27 21:03:27.000000 bec_file_writer-0.6.14/bec_file_writer.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      439 2023-06-27 21:03:27.000000 bec_file_writer-0.6.14/bec_file_writer.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 21:03:27.000000 bec_file_writer-0.6.14/bec_file_writer.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       21 2023-06-27 21:03:27.000000 bec_file_writer-0.6.14/bec_file_writer.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       32 2023-06-27 21:03:27.000000 bec_file_writer-0.6.14/bec_file_writer.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:27.718059 bec_file_writer-0.6.14/file_writer/
--rw-rw-rw-   0 root         (0) root         (0)      112 2023-04-24 15:23:42.000000 bec_file_writer-0.6.14/file_writer/__init__.py
--rw-r--r--   0 root         (0) root         (0)     9259 2023-06-25 19:44:47.000000 bec_file_writer-0.6.14/file_writer/file_writer.py
--rw-r--r--   0 root         (0) root         (0)     8104 2023-06-25 18:29:43.000000 bec_file_writer-0.6.14/file_writer/file_writer_manager.py
--rw-rw-rw-   0 root         (0) root         (0)     1555 2023-06-19 08:14:59.000000 bec_file_writer-0.6.14/file_writer/merged_dicts.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 21:03:27.719059 bec_file_writer-0.6.14/file_writer_plugins/
--rw-rw-rw-   0 root         (0) root         (0)      119 2023-06-19 08:14:59.000000 bec_file_writer-0.6.14/file_writer_plugins/__init__.py
--rw-r--r--   0 root         (0) root         (0)    17058 2023-06-25 18:29:43.000000 bec_file_writer-0.6.14/file_writer_plugins/cSAXS.py
--rw-r--r--   0 root         (0) root         (0)     2274 2023-06-25 18:29:43.000000 bec_file_writer-0.6.14/file_writer_plugins/default_writer.py
--rw-r--r--   0 root         (0) root         (0)      536 2023-06-27 21:03:27.721059 bec_file_writer-0.6.14/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      728 2023-06-23 18:57:15.000000 bec_file_writer-0.6.14/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:15.695605 bec_file_writer-0.7.0/
+-rw-r--r--   0 root         (0) root         (0)      455 2023-06-28 10:26:15.695605 bec_file_writer-0.7.0/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:15.695605 bec_file_writer-0.7.0/bec_file_writer.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      455 2023-06-28 10:26:15.000000 bec_file_writer-0.7.0/bec_file_writer.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      439 2023-06-28 10:26:15.000000 bec_file_writer-0.7.0/bec_file_writer.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 10:26:15.000000 bec_file_writer-0.7.0/bec_file_writer.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       21 2023-06-28 10:26:15.000000 bec_file_writer-0.7.0/bec_file_writer.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       32 2023-06-28 10:26:15.000000 bec_file_writer-0.7.0/bec_file_writer.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:15.693605 bec_file_writer-0.7.0/file_writer/
+-rw-rw-rw-   0 root         (0) root         (0)      112 2023-04-24 15:23:42.000000 bec_file_writer-0.7.0/file_writer/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     9251 2023-06-28 10:25:33.000000 bec_file_writer-0.7.0/file_writer/file_writer.py
+-rw-r--r--   0 root         (0) root         (0)     8083 2023-06-28 10:25:33.000000 bec_file_writer-0.7.0/file_writer/file_writer_manager.py
+-rw-rw-rw-   0 root         (0) root         (0)     1555 2023-06-19 08:15:20.000000 bec_file_writer-0.7.0/file_writer/merged_dicts.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 10:26:15.694605 bec_file_writer-0.7.0/file_writer_plugins/
+-rw-rw-rw-   0 root         (0) root         (0)      119 2023-06-19 08:15:20.000000 bec_file_writer-0.7.0/file_writer_plugins/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    17058 2023-06-25 18:28:27.000000 bec_file_writer-0.7.0/file_writer_plugins/cSAXS.py
+-rw-r--r--   0 root         (0) root         (0)     2274 2023-06-25 18:28:27.000000 bec_file_writer-0.7.0/file_writer_plugins/default_writer.py
+-rw-r--r--   0 root         (0) root         (0)      536 2023-06-28 10:26:15.695605 bec_file_writer-0.7.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      721 2023-06-28 10:25:33.000000 bec_file_writer-0.7.0/setup.py
```

### Comparing `bec_file_writer-0.6.14/file_writer/file_writer.py` & `bec_file_writer-0.7.0/file_writer/file_writer.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,18 +1,17 @@
 import abc
 import datetime
 import json
 import traceback
 import typing
 
+import file_writer_plugins as fwp
 import h5py
 import xmltodict
-from bec_client_lib.core import bec_logger
-
-import file_writer_plugins as fwp
+from bec_lib.core import bec_logger
 
 from .merged_dicts import merge_dicts
 
 logger = bec_logger.logger
 
 
 class NeXusLayoutError(Exception):
```

### Comparing `bec_file_writer-0.6.14/file_writer/file_writer_manager.py` & `bec_file_writer-0.7.0/file_writer/file_writer_manager.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,23 +1,23 @@
 from __future__ import annotations
 
 import os
 import traceback
 from pathlib import Path
 
-from bec_client_lib.core import (
+from bec_lib.core import (
     BECMessage,
     BECService,
     DeviceManagerBase,
     MessageEndpoints,
     ServiceConfig,
     bec_logger,
 )
-from bec_client_lib.core.bec_errors import ServiceConfigError
-from bec_client_lib.core.redis_connector import Alarms, MessageObject, RedisConnector
+from bec_lib.core.bec_errors import ServiceConfigError
+from bec_lib.core.redis_connector import Alarms, MessageObject, RedisConnector
 
 from file_writer.file_writer import NexusFileWriter
 
 logger = bec_logger.logger
 
 
 class ScanStorage:
```

### Comparing `bec_file_writer-0.6.14/file_writer/merged_dicts.py` & `bec_file_writer-0.7.0/file_writer/merged_dicts.py`

 * *Files identical despite different names*

### Comparing `bec_file_writer-0.6.14/file_writer_plugins/cSAXS.py` & `bec_file_writer-0.7.0/file_writer_plugins/cSAXS.py`

 * *Files identical despite different names*

### Comparing `bec_file_writer-0.6.14/file_writer_plugins/default_writer.py` & `bec_file_writer-0.7.0/file_writer_plugins/default_writer.py`

 * *Files identical despite different names*

### Comparing `bec_file_writer-0.6.14/setup.cfg` & `bec_file_writer-0.7.0/setup.cfg`

 * *Files identical despite different names*

### Comparing `bec_file_writer-0.6.14/setup.py` & `bec_file_writer-0.7.0/setup.py`

 * *Files 1% similar despite different names*

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

