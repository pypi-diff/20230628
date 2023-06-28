# Comparing `tmp/rosetta-ce-1.2.4.tar.gz` & `tmp/rosetta-ce-1.2.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rosetta-ce-1.2.4.tar", last modified: Wed Jun 28 08:23:37 2023, max compression
+gzip compressed data, was "rosetta-ce-1.2.5.tar", last modified: Wed Jun 28 12:26:23 2023, max compression
```

## Comparing `rosetta-ce-1.2.4.tar` & `rosetta-ce-1.2.5.tar`

### file list

```diff
@@ -1,26 +1,26 @@
-drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 08:23:37.281373 rosetta-ce-1.2.4/
--rw-r--r--   0 amahmoud   (502) staff       (20)     1070 2023-04-08 17:22:13.000000 rosetta-ce-1.2.4/LICENSE
--rw-r--r--   0 amahmoud   (502) staff       (20)    11282 2023-06-28 08:23:37.281103 rosetta-ce-1.2.4/PKG-INFO
--rw-r--r--   0 amahmoud   (502) staff       (20)    10750 2023-04-26 16:15:22.000000 rosetta-ce-1.2.4/README.md
-drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 08:23:37.275569 rosetta-ce-1.2.4/rosetta/
--rw-r--r--   0 amahmoud   (502) staff       (20)       92 2023-04-09 08:11:12.000000 rosetta-ce-1.2.4/rosetta/__init__.py
-drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 08:23:37.277263 rosetta-ce-1.2.4/rosetta/constants/
--rw-r--r--   0 amahmoud   (502) staff       (20)        0 2023-04-12 16:36:37.000000 rosetta-ce-1.2.4/rosetta/constants/__init__.py
--rw-r--r--   0 amahmoud   (502) staff       (20)     1936 2023-04-09 13:32:25.000000 rosetta-ce-1.2.4/rosetta/constants/sensors.py
--rw-r--r--   0 amahmoud   (502) staff       (20)     1658 2023-04-25 15:36:11.000000 rosetta-ce-1.2.4/rosetta/constants/sources.py
--rw-r--r--   0 amahmoud   (502) staff       (20)     6697 2023-04-25 15:36:11.000000 rosetta-ce-1.2.4/rosetta/constants/systems.py
--rw-r--r--   0 amahmoud   (502) staff       (20)     3008 2023-04-26 09:01:43.000000 rosetta-ce-1.2.4/rosetta/rconverter.py
--rw-r--r--   0 amahmoud   (502) staff       (20)    32103 2023-06-28 05:19:15.000000 rosetta-ce-1.2.4/rosetta/rfaker.py
--rw-r--r--   0 amahmoud   (502) staff       (20)     8210 2023-06-28 08:18:36.000000 rosetta-ce-1.2.4/rosetta/rsender.py
-drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 08:23:37.279157 rosetta-ce-1.2.4/rosetta_ce.egg-info/
--rw-r--r--   0 amahmoud   (502) staff       (20)    11282 2023-06-28 08:23:37.000000 rosetta-ce-1.2.4/rosetta_ce.egg-info/PKG-INFO
--rw-r--r--   0 amahmoud   (502) staff       (20)      459 2023-06-28 08:23:37.000000 rosetta-ce-1.2.4/rosetta_ce.egg-info/SOURCES.txt
--rw-r--r--   0 amahmoud   (502) staff       (20)        1 2023-06-28 08:23:37.000000 rosetta-ce-1.2.4/rosetta_ce.egg-info/dependency_links.txt
--rw-r--r--   0 amahmoud   (502) staff       (20)       23 2023-06-28 08:23:37.000000 rosetta-ce-1.2.4/rosetta_ce.egg-info/requires.txt
--rw-r--r--   0 amahmoud   (502) staff       (20)        8 2023-06-28 08:23:37.000000 rosetta-ce-1.2.4/rosetta_ce.egg-info/top_level.txt
--rw-r--r--   0 amahmoud   (502) staff       (20)       38 2023-06-28 08:23:37.281421 rosetta-ce-1.2.4/setup.cfg
--rw-r--r--   0 amahmoud   (502) staff       (20)      851 2023-06-28 08:23:22.000000 rosetta-ce-1.2.4/setup.py
-drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 08:23:37.280578 rosetta-ce-1.2.4/tests/
--rw-r--r--   0 amahmoud   (502) staff       (20)     1040 2023-04-26 09:01:43.000000 rosetta-ce-1.2.4/tests/test_rconverter.py
--rw-r--r--   0 amahmoud   (502) staff       (20)     5226 2023-04-25 15:36:11.000000 rosetta-ce-1.2.4/tests/test_rfaker.py
--rw-r--r--   0 amahmoud   (502) staff       (20)     1763 2023-04-26 09:02:44.000000 rosetta-ce-1.2.4/tests/test_rsender.py
+drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 12:26:23.883537 rosetta-ce-1.2.5/
+-rw-r--r--   0 amahmoud   (502) staff       (20)     1070 2023-04-08 17:22:13.000000 rosetta-ce-1.2.5/LICENSE
+-rw-r--r--   0 amahmoud   (502) staff       (20)    11282 2023-06-28 12:26:23.883225 rosetta-ce-1.2.5/PKG-INFO
+-rw-r--r--   0 amahmoud   (502) staff       (20)    10750 2023-04-26 16:15:22.000000 rosetta-ce-1.2.5/README.md
+drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 12:26:23.877298 rosetta-ce-1.2.5/rosetta/
+-rw-r--r--   0 amahmoud   (502) staff       (20)       92 2023-04-09 08:11:12.000000 rosetta-ce-1.2.5/rosetta/__init__.py
+drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 12:26:23.879106 rosetta-ce-1.2.5/rosetta/constants/
+-rw-r--r--   0 amahmoud   (502) staff       (20)        0 2023-04-12 16:36:37.000000 rosetta-ce-1.2.5/rosetta/constants/__init__.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)     1936 2023-04-09 13:32:25.000000 rosetta-ce-1.2.5/rosetta/constants/sensors.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)     1658 2023-04-25 15:36:11.000000 rosetta-ce-1.2.5/rosetta/constants/sources.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)     6697 2023-04-25 15:36:11.000000 rosetta-ce-1.2.5/rosetta/constants/systems.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)     3008 2023-04-26 09:01:43.000000 rosetta-ce-1.2.5/rosetta/rconverter.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)    32103 2023-06-28 05:19:15.000000 rosetta-ce-1.2.5/rosetta/rfaker.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)     8206 2023-06-28 12:25:04.000000 rosetta-ce-1.2.5/rosetta/rsender.py
+drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 12:26:23.881241 rosetta-ce-1.2.5/rosetta_ce.egg-info/
+-rw-r--r--   0 amahmoud   (502) staff       (20)    11282 2023-06-28 12:26:23.000000 rosetta-ce-1.2.5/rosetta_ce.egg-info/PKG-INFO
+-rw-r--r--   0 amahmoud   (502) staff       (20)      459 2023-06-28 12:26:23.000000 rosetta-ce-1.2.5/rosetta_ce.egg-info/SOURCES.txt
+-rw-r--r--   0 amahmoud   (502) staff       (20)        1 2023-06-28 12:26:23.000000 rosetta-ce-1.2.5/rosetta_ce.egg-info/dependency_links.txt
+-rw-r--r--   0 amahmoud   (502) staff       (20)       23 2023-06-28 12:26:23.000000 rosetta-ce-1.2.5/rosetta_ce.egg-info/requires.txt
+-rw-r--r--   0 amahmoud   (502) staff       (20)        8 2023-06-28 12:26:23.000000 rosetta-ce-1.2.5/rosetta_ce.egg-info/top_level.txt
+-rw-r--r--   0 amahmoud   (502) staff       (20)       38 2023-06-28 12:26:23.883599 rosetta-ce-1.2.5/setup.cfg
+-rw-r--r--   0 amahmoud   (502) staff       (20)      851 2023-06-28 12:25:56.000000 rosetta-ce-1.2.5/setup.py
+drwxr-xr-x   0 amahmoud   (502) staff       (20)        0 2023-06-28 12:26:23.882686 rosetta-ce-1.2.5/tests/
+-rw-r--r--   0 amahmoud   (502) staff       (20)     1040 2023-04-26 09:01:43.000000 rosetta-ce-1.2.5/tests/test_rconverter.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)     5226 2023-04-25 15:36:11.000000 rosetta-ce-1.2.5/tests/test_rfaker.py
+-rw-r--r--   0 amahmoud   (502) staff       (20)     1763 2023-04-26 09:02:44.000000 rosetta-ce-1.2.5/tests/test_rsender.py
```

### Comparing `rosetta-ce-1.2.4/LICENSE` & `rosetta-ce-1.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/PKG-INFO` & `rosetta-ce-1.2.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: rosetta-ce
-Version: 1.2.4
+Version: 1.2.5
 Summary: Rosetta is a Python package that can be used to fake security logs and alerts for testing different detection and response use cases.
 Home-page: https://github.com/ayman-m/rosetta
 Author: Ayman Mahmoud
 Author-email: content@ayman.online
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `rosetta-ce-1.2.4/README.md` & `rosetta-ce-1.2.5/README.md`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/rosetta/constants/sensors.py` & `rosetta-ce-1.2.5/rosetta/constants/sensors.py`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/rosetta/constants/sources.py` & `rosetta-ce-1.2.5/rosetta/constants/sources.py`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/rosetta/constants/systems.py` & `rosetta-ce-1.2.5/rosetta/constants/systems.py`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/rosetta/rconverter.py` & `rosetta-ce-1.2.5/rosetta/rconverter.py`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/rosetta/rfaker.py` & `rosetta-ce-1.2.5/rosetta/rfaker.py`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/rosetta/rsender.py` & `rosetta-ce-1.2.5/rosetta/rsender.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-import datetime
+from datetime import datetime
 import time
 import threading
 import socket
 import requests
 import warnings
 from enum import Enum
 from typing import Optional
@@ -62,15 +62,15 @@
             Sends fake data to the destination address.
 
             Returns:
                 None.
     """
 
     def __init__(self, data_type: WorkerTypeEnum, destination: str,
-                 worker_name: Optional[str] = 'worker_'+str(datetime.datetime.now()), count: Optional[int] = 1,
+                 worker_name: Optional[str] = 'worker_'+str(datetime.now()), count: Optional[int] = 1,
                  interval: Optional[int] = 1, observables: Optional[Observables] = None, fields: Optional[str] = None,
                  verify_ssl: Optional[bool] = None, datetime_obj: Optional[datetime] = None):
         """
         Constructor for DataSenderWorker class.
 
         :param data_type: A value from the WorkerTypeEnum indicating the type of data to send. Options include:
             - WorkerTypeEnum.SYSLOG
@@ -91,15 +91,15 @@
         """
         self.thread = None
         self.worker_name = worker_name
         self.data_type = data_type
         self.count = count
         self.interval = interval
         self.destination = destination
-        self.created_at = datetime.datetime.now()
+        self.created_at = datetime.now()
         self.status = "Stopped"
         self.observables = observables
         self.fields = fields
         self.verify_ssl = verify_ssl
         self.datetime_obj = datetime_obj
 
     def start(self) -> str:
```

### Comparing `rosetta-ce-1.2.4/rosetta_ce.egg-info/PKG-INFO` & `rosetta-ce-1.2.5/rosetta_ce.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: rosetta-ce
-Version: 1.2.4
+Version: 1.2.5
 Summary: Rosetta is a Python package that can be used to fake security logs and alerts for testing different detection and response use cases.
 Home-page: https://github.com/ayman-m/rosetta
 Author: Ayman Mahmoud
 Author-email: content@ayman.online
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `rosetta-ce-1.2.4/setup.py` & `rosetta-ce-1.2.5/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="rosetta-ce",
-    version="1.2.4",
+    version="1.2.5",
     author="Ayman Mahmoud",
     author_email="content@ayman.online",
     description="Rosetta is a Python package that can be used to fake security logs and alerts for testing different "
                 "detection and response use cases.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/ayman-m/rosetta",
```

### Comparing `rosetta-ce-1.2.4/tests/test_rconverter.py` & `rosetta-ce-1.2.5/tests/test_rconverter.py`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/tests/test_rfaker.py` & `rosetta-ce-1.2.5/tests/test_rfaker.py`

 * *Files identical despite different names*

### Comparing `rosetta-ce-1.2.4/tests/test_rsender.py` & `rosetta-ce-1.2.5/tests/test_rsender.py`

 * *Files identical despite different names*

