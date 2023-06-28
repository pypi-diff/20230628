# Comparing `tmp/omron-2jcie-bu01-interact-0.1.0.tar.gz` & `tmp/omron-2jcie-bu01-interact-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "omron-2jcie-bu01-interact-0.1.0.tar", last modified: Wed Jun 28 04:01:27 2023, max compression
+gzip compressed data, was "omron-2jcie-bu01-interact-0.1.1.tar", last modified: Wed Jun 28 04:33:17 2023, max compression
```

## Comparing `omron-2jcie-bu01-interact-0.1.0.tar` & `omron-2jcie-bu01-interact-0.1.1.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 04:01:27.509153 omron-2jcie-bu01-interact-0.1.0/
--rw-rw-rw-   0        0        0     1090 2023-06-28 03:45:37.000000 omron-2jcie-bu01-interact-0.1.0/LICENSE
--rw-rw-rw-   0        0        0       95 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/MANIFEST.in
--rw-rw-rw-   0        0        0     2096 2023-06-28 04:01:27.509153 omron-2jcie-bu01-interact-0.1.0/PKG-INFO
--rw-rw-rw-   0        0        0     5217 2023-06-28 03:52:00.000000 omron-2jcie-bu01-interact-0.1.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 04:01:27.486133 omron-2jcie-bu01-interact-0.1.0/examples/
--rw-rw-rw-   0        0        0      325 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/examples/led_serial.py
--rw-rw-rw-   0        0        0     1523 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/examples/measure_ble.py
--rw-rw-rw-   0        0        0     1784 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/examples/measure_serial.py
--rw-rw-rw-   0        0        0      401 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/examples/notify_ble.py
--rw-rw-rw-   0        0        0     1981 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/examples/scan_ble.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:01:27.489136 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01/
--rw-rw-rw-   0        0        0    10861 2023-06-28 03:53:30.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01/__init__.py
--rw-rw-rw-   0        0        0     9745 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01/ble.py
--rw-rw-rw-   0        0        0     2822 2023-06-28 03:49:30.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01/serial.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:01:27.504149 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/
--rw-rw-rw-   0        0        0     2096 2023-06-28 04:01:27.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      559 2023-06-28 04:01:27.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 04:01:27.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       22 2023-06-28 04:01:27.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/requires.txt
--rw-rw-rw-   0        0        0       17 2023-06-28 04:01:27.000000 omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 04:01:27.509153 omron-2jcie-bu01-interact-0.1.0/setup.cfg
--rw-rw-rw-   0        0        0     1440 2023-06-28 03:55:40.000000 omron-2jcie-bu01-interact-0.1.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 04:01:27.508153 omron-2jcie-bu01-interact-0.1.0/test/
--rw-rw-rw-   0        0        0     1559 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/test/test_connect.py
--rw-rw-rw-   0        0        0      861 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/test/test_notify.py
--rw-rw-rw-   0        0        0     1237 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/test/test_scan.py
--rw-rw-rw-   0        0        0     1518 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.0/test/test_serial.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:33:17.852772 omron-2jcie-bu01-interact-0.1.1/
+-rw-rw-rw-   0        0        0     1090 2023-06-28 03:45:37.000000 omron-2jcie-bu01-interact-0.1.1/LICENSE
+-rw-rw-rw-   0        0        0       95 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.1/MANIFEST.in
+-rw-rw-rw-   0        0        0     2096 2023-06-28 04:33:17.851771 omron-2jcie-bu01-interact-0.1.1/PKG-INFO
+-rw-rw-rw-   0        0        0     5217 2023-06-28 03:52:00.000000 omron-2jcie-bu01-interact-0.1.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 04:33:17.825747 omron-2jcie-bu01-interact-0.1.1/examples/
+-rw-rw-rw-   0        0        0      334 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/examples/led_serial.py
+-rw-rw-rw-   0        0        0     1532 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/examples/measure_ble.py
+-rw-rw-rw-   0        0        0     1793 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/examples/measure_serial.py
+-rw-rw-rw-   0        0        0      410 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/examples/notify_ble.py
+-rw-rw-rw-   0        0        0     1990 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/examples/scan_ble.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:33:17.829751 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact/
+-rw-rw-rw-   0        0        0    10861 2023-06-28 04:30:27.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact/__init__.py
+-rw-rw-rw-   0        0        0     9745 2023-06-28 03:46:29.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact/ble.py
+-rw-rw-rw-   0        0        0     2822 2023-06-28 03:49:30.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact/serial.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:33:17.846766 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/
+-rw-rw-rw-   0        0        0     2096 2023-06-28 04:33:17.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      586 2023-06-28 04:33:17.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 04:33:17.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       22 2023-06-28 04:33:17.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       26 2023-06-28 04:33:17.000000 omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 04:33:17.852772 omron-2jcie-bu01-interact-0.1.1/setup.cfg
+-rw-rw-rw-   0        0        0     1485 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 04:33:17.850769 omron-2jcie-bu01-interact-0.1.1/test/
+-rw-rw-rw-   0        0        0     1568 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/test/test_connect.py
+-rw-rw-rw-   0        0        0      870 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/test/test_notify.py
+-rw-rw-rw-   0        0        0     1246 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/test/test_scan.py
+-rw-rw-rw-   0        0        0     1527 2023-06-28 04:33:04.000000 omron-2jcie-bu01-interact-0.1.1/test/test_serial.py
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/LICENSE` & `omron-2jcie-bu01-interact-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `omron-2jcie-bu01-interact-0.1.0/PKG-INFO` & `omron-2jcie-bu01-interact-0.1.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: omron-2jcie-bu01-interact
-Version: 0.1.0
+Version: 0.1.1
 Summary: API for OMRON 2JCIE-BU01 Environment Sensor
 Home-page: https://github.com/andreastande/omron-2jcie-bu01-interact
 Author: Andreas Tande
 Author-email: andreas.tande@gmail.com
 License: MIT
 Platform: any
 Classifier: Development Status :: 3 - Alpha
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/README.md` & `omron-2jcie-bu01-interact-0.1.1/README.md`

 * *Files identical despite different names*

### Comparing `omron-2jcie-bu01-interact-0.1.0/examples/measure_ble.py` & `omron-2jcie-bu01-interact-0.1.1/examples/measure_ble.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 #!/usr/bin/env python3
 import sys
 sys.path.insert(0, "../lib-ext")
 sys.path.insert(0, "..")
 
 import time
 from datetime import datetime, timedelta, tzinfo
-from omron_2jcie_bu01 import Omron2JCIE_BU01
+from omron_2jcie_bu01_interact import Omron2JCIE_BU01
 
 CurrentTZ = type(time.tzname[0], (tzinfo,), {
     "tzname": lambda self, dt: time.tzname[0],
     "utcoffset": lambda self, dt: timedelta(seconds=-time.timezone),
     "dst": lambda self, dt: timedelta(seconds=time.timezone - time.altzone),
 })()
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/examples/measure_serial.py` & `omron-2jcie-bu01-interact-0.1.1/examples/measure_serial.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 #!/usr/bin/env python3
 import sys
 sys.path.insert(0, "../lib-ext")
 sys.path.insert(0, "..")
 
 import time
 from datetime import datetime, timedelta, tzinfo
-from omron_2jcie_bu01 import Omron2JCIE_BU01
+from omron_2jcie_bu01_interact import Omron2JCIE_BU01
 
 CurrentTZ = type(time.tzname[0], (tzinfo,), {
     "tzname": lambda self, dt: time.tzname[0],
     "utcoffset": lambda self, dt: timedelta(seconds=-time.timezone),
     "dst": lambda self, dt: timedelta(seconds=time.timezone - time.altzone),
 })()
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/examples/scan_ble.py` & `omron-2jcie-bu01-interact-0.1.1/examples/scan_ble.py`

 * *Files 1% similar despite different names*

```diff
@@ -33,15 +33,15 @@
     On Windows, data can be detected at intervals of 1 second or less.
     And complete data will be obtained about every 1 second.
 """
 import sys
 sys.path.insert(0, "../lib-ext")
 sys.path.insert(0, "..")
 
-from omron_2jcie_bu01 import Omron2JCIE_BU01
+from omron_2jcie_bu01_interact import Omron2JCIE_BU01
 
 #s = Omron2JCIE_BU01.ble("AA:BB:CC:DD:EE:FF")
 s = Omron2JCIE_BU01.ble()
 
 # Scan
 def on_scan(data):
     print(data)
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01/__init__.py` & `omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -44,15 +44,15 @@
 """
 
 import struct
 from collections import namedtuple
 from decimal import Decimal
 
 __author__  = "Andreas Tande"
-__version__ = "0.1.0"
+__version__ = "0.1.1"
 __license__ = "MIT License"
 
 class Omron2JCIE_BU01(object):
     # Base class for Serial/BLE implementation
 
     # Description for Vibration Information
     VI = ["NONE", "During vibration (Earthquake judgment in progress)", "During earthquake"]
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01/ble.py` & `omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact/ble.py`

 * *Files identical despite different names*

### Comparing `omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01/serial.py` & `omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact/serial.py`

 * *Files identical despite different names*

### Comparing `omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/PKG-INFO` & `omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: omron-2jcie-bu01-interact
-Version: 0.1.0
+Version: 0.1.1
 Summary: API for OMRON 2JCIE-BU01 Environment Sensor
 Home-page: https://github.com/andreastande/omron-2jcie-bu01-interact
 Author: Andreas Tande
 Author-email: andreas.tande@gmail.com
 License: MIT
 Platform: any
 Classifier: Development Status :: 3 - Alpha
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/omron_2jcie_bu01_interact.egg-info/SOURCES.txt` & `omron-2jcie-bu01-interact-0.1.1/omron_2jcie_bu01_interact.egg-info/SOURCES.txt`

 * *Files 10% similar despite different names*

```diff
@@ -3,17 +3,17 @@
 README.md
 setup.py
 examples/led_serial.py
 examples/measure_ble.py
 examples/measure_serial.py
 examples/notify_ble.py
 examples/scan_ble.py
-omron_2jcie_bu01/__init__.py
-omron_2jcie_bu01/ble.py
-omron_2jcie_bu01/serial.py
+omron_2jcie_bu01_interact/__init__.py
+omron_2jcie_bu01_interact/ble.py
+omron_2jcie_bu01_interact/serial.py
 omron_2jcie_bu01_interact.egg-info/PKG-INFO
 omron_2jcie_bu01_interact.egg-info/SOURCES.txt
 omron_2jcie_bu01_interact.egg-info/dependency_links.txt
 omron_2jcie_bu01_interact.egg-info/requires.txt
 omron_2jcie_bu01_interact.egg-info/top_level.txt
 test/test_connect.py
 test/test_notify.py
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/setup.py` & `omron-2jcie-bu01-interact-0.1.1/setup.py`

 * *Files 19% similar despite different names*

```diff
@@ -2,23 +2,23 @@
 # Project: OMRON 2JCIE-BU01
 # Module:
 from setuptools import setup
 import sys
 if sys.version_info < (3, 6):
     raise NotImplementedError("Sorry, you need at least Python 3.6 to use OMRON 2JCIE-BU01.")
 
-import omron_2jcie_bu01
-MODNAME = "omron_2jcie_bu01"
+import omron_2jcie_bu01_interact
+MODNAME = "omron_2jcie_bu01_interact"
 
 setup(
     name                = "omron-2jcie-bu01-interact",
-    version             = omron_2jcie_bu01.__version__,
+    version             = omron_2jcie_bu01_interact.__version__,
     description         = "API for OMRON 2JCIE-BU01 Environment Sensor",
-    long_description    = omron_2jcie_bu01.__doc__,
-    author              = omron_2jcie_bu01.__author__,
+    long_description    = omron_2jcie_bu01_interact.__doc__,
+    author              = omron_2jcie_bu01_interact.__author__,
     author_email        = "andreas.tande@gmail.com",
     url                 = "https://github.com/andreastande/omron-2jcie-bu01-interact",
     py_modules          = [MODNAME, f"{MODNAME}.ble", f"{MODNAME}.serial"],
     scripts             = [f"{MODNAME}/__init__.py", f"{MODNAME}/ble.py", f"{MODNAME}/serial.py"],
     install_requires    = ["pyserial"],
     extras_require      = {"ble": ["bleak"]},
     license             = "MIT",
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/test/test_connect.py` & `omron-2jcie-bu01-interact-0.1.1/test/test_connect.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 #!/usr/bin/env python3
 import sys
 sys.path.insert(0, "../lib-ext")
 sys.path.insert(0, "..")
 
 import unittest
-from omron_2jcie_bu01 import Omron2JCIE_BU01
+from omron_2jcie_bu01_interact import Omron2JCIE_BU01
 
 class BLEConnectionTestCase(unittest.TestCase):
     ADDRESS = None
 
     @classmethod
     def setUpClass(cls):
         sensor = Omron2JCIE_BU01.ble()
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/test/test_notify.py` & `omron-2jcie-bu01-interact-0.1.1/test/test_notify.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 #!/usr/bin/env python3
 import sys
 sys.path.insert(0, "../lib-ext")
 sys.path.insert(0, "..")
 
 import unittest
-from omron_2jcie_bu01 import Omron2JCIE_BU01
+from omron_2jcie_bu01_interact import Omron2JCIE_BU01
 
 class BLENotificationTestCase(unittest.TestCase):
     ADDRESS = None
 
     @classmethod
     def setUpClass(cls):
         sensor = Omron2JCIE_BU01.ble()
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/test/test_scan.py` & `omron-2jcie-bu01-interact-0.1.1/test/test_scan.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 #!/usr/bin/env python3
 import sys
 sys.path.insert(0, "../lib-ext")
 sys.path.insert(0, "..")
 
 import unittest
-from omron_2jcie_bu01 import Omron2JCIE_BU01
+from omron_2jcie_bu01_interact import Omron2JCIE_BU01
 
 class BLEScanTestCase(unittest.TestCase):
     ADDRESS = None
 
     @classmethod
     def setUpClass(cls):
         sensor = Omron2JCIE_BU01.ble()
```

### Comparing `omron-2jcie-bu01-interact-0.1.0/test/test_serial.py` & `omron-2jcie-bu01-interact-0.1.1/test/test_serial.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 #!/usr/bin/env python3
 import sys
 sys.path.insert(0, "../lib-ext")
 sys.path.insert(0, "..")
 
 import unittest
-from omron_2jcie_bu01 import Omron2JCIE_BU01
+from omron_2jcie_bu01_interact import Omron2JCIE_BU01
 
 class BLEConnectionTestCase(unittest.TestCase):
     def setUp(self): pass
     def tearDown(self): pass
 
     def test_connect(self):
         """
```

