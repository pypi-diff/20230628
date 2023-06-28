# Comparing `tmp/revpimodio2-2.6.0rc5.tar.gz` & `tmp/revpimodio2-2.6.0rc6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "revpimodio2-2.6.0rc5.tar", last modified: Sat May 13 09:58:53 2023, max compression
+gzip compressed data, was "revpimodio2-2.6.0rc6.tar", last modified: Thu Jun  8 12:32:07 2023, max compression
```

## Comparing `revpimodio2-2.6.0rc5.tar` & `revpimodio2-2.6.0rc6.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-05-13 09:58:53.303374 revpimodio2-2.6.0rc5/
--rw-r--r--   0 svensager   (501) staff       (20)    18092 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/LICENSE.txt
--rw-r--r--   0 svensager   (501) staff       (20)      174 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/MANIFEST.in
--rw-r--r--   0 svensager   (501) staff       (20)      813 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/Makefile
--rw-r--r--   0 svensager   (501) staff       (20)     4568 2023-05-13 09:58:53.303239 revpimodio2-2.6.0rc5/PKG-INFO
--rw-r--r--   0 svensager   (501) staff       (20)     3646 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/README.md
-drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-05-13 09:58:53.299818 revpimodio2-2.6.0rc5/docs/
--rw-r--r--   0 svensager   (501) staff       (20)      667 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/docs/Makefile
--rw-r--r--   0 svensager   (501) staff       (20)      837 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/docs/conf.py
--rw-r--r--   0 svensager   (501) staff       (20)      447 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/docs/index.rst
--rw-r--r--   0 svensager   (501) staff       (20)       54 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/docs/modules.rst
--rw-r--r--   0 svensager   (501) staff       (20)     1445 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/docs/revpimodio2.rst
--rw-r--r--   0 svensager   (501) staff       (20)       25 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/requirements.txt
--rw-r--r--   0 svensager   (501) staff       (20)       38 2023-05-13 09:58:53.303417 revpimodio2-2.6.0rc5/setup.cfg
--rw-r--r--   0 svensager   (501) staff       (20)     1598 2023-05-13 09:48:25.000000 revpimodio2-2.6.0rc5/setup.py
-drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-05-13 09:58:53.297109 revpimodio2-2.6.0rc5/src/
-drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-05-13 09:58:53.302479 revpimodio2-2.6.0rc5/src/revpimodio2/
--rw-r--r--   0 svensager   (501) staff       (20)      196 2023-05-13 08:22:50.000000 revpimodio2-2.6.0rc5/src/revpimodio2/__about__.py
--rw-r--r--   0 svensager   (501) staff       (20)     1372 2023-05-13 09:56:10.000000 revpimodio2-2.6.0rc5/src/revpimodio2/__init__.py
--rw-r--r--   0 svensager   (501) staff       (20)     1660 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/_internal.py
--rw-r--r--   0 svensager   (501) staff       (20)     1104 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/app.py
--rw-r--r--   0 svensager   (501) staff       (20)    50983 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/device.py
--rw-r--r--   0 svensager   (501) staff       (20)      256 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/errors.py
--rw-r--r--   0 svensager   (501) staff       (20)    23236 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/helper.py
--rw-r--r--   0 svensager   (501) staff       (20)    53076 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/io.py
--rw-r--r--   0 svensager   (501) staff       (20)    53697 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/modio.py
--rw-r--r--   0 svensager   (501) staff       (20)    36670 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/netio.py
--rw-r--r--   0 svensager   (501) staff       (20)     5307 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/pictory.py
--rw-r--r--   0 svensager   (501) staff       (20)      551 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc5/src/revpimodio2/summary.py
-drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-05-13 09:58:53.303034 revpimodio2-2.6.0rc5/src/revpimodio2.egg-info/
--rw-r--r--   0 svensager   (501) staff       (20)     4568 2023-05-13 09:58:53.000000 revpimodio2-2.6.0rc5/src/revpimodio2.egg-info/PKG-INFO
--rw-r--r--   0 svensager   (501) staff       (20)      617 2023-05-13 09:58:53.000000 revpimodio2-2.6.0rc5/src/revpimodio2.egg-info/SOURCES.txt
--rw-r--r--   0 svensager   (501) staff       (20)        1 2023-05-13 09:58:53.000000 revpimodio2-2.6.0rc5/src/revpimodio2.egg-info/dependency_links.txt
--rw-r--r--   0 svensager   (501) staff       (20)       12 2023-05-13 09:58:53.000000 revpimodio2-2.6.0rc5/src/revpimodio2.egg-info/top_level.txt
+drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-06-08 12:32:07.109069 revpimodio2-2.6.0rc6/
+-rw-r--r--   0 svensager   (501) staff       (20)    18092 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/LICENSE.txt
+-rw-r--r--   0 svensager   (501) staff       (20)      174 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/MANIFEST.in
+-rw-r--r--   0 svensager   (501) staff       (20)      813 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/Makefile
+-rw-r--r--   0 svensager   (501) staff       (20)     4568 2023-06-08 12:32:07.108913 revpimodio2-2.6.0rc6/PKG-INFO
+-rw-r--r--   0 svensager   (501) staff       (20)     3646 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/README.md
+drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-06-08 12:32:07.103991 revpimodio2-2.6.0rc6/docs/
+-rw-r--r--   0 svensager   (501) staff       (20)      667 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/docs/Makefile
+-rw-r--r--   0 svensager   (501) staff       (20)      837 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/docs/conf.py
+-rw-r--r--   0 svensager   (501) staff       (20)      447 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/docs/index.rst
+-rw-r--r--   0 svensager   (501) staff       (20)       54 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/docs/modules.rst
+-rw-r--r--   0 svensager   (501) staff       (20)     1445 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/docs/revpimodio2.rst
+-rw-r--r--   0 svensager   (501) staff       (20)       25 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/requirements.txt
+-rw-r--r--   0 svensager   (501) staff       (20)       38 2023-06-08 12:32:07.109119 revpimodio2-2.6.0rc6/setup.cfg
+-rw-r--r--   0 svensager   (501) staff       (20)     1598 2023-05-13 09:48:25.000000 revpimodio2-2.6.0rc6/setup.py
+drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-06-08 12:32:07.101669 revpimodio2-2.6.0rc6/src/
+drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-06-08 12:32:07.107989 revpimodio2-2.6.0rc6/src/revpimodio2/
+-rw-r--r--   0 svensager   (501) staff       (20)      196 2023-06-08 12:30:11.000000 revpimodio2-2.6.0rc6/src/revpimodio2/__about__.py
+-rw-r--r--   0 svensager   (501) staff       (20)     1372 2023-05-13 09:56:10.000000 revpimodio2-2.6.0rc6/src/revpimodio2/__init__.py
+-rw-r--r--   0 svensager   (501) staff       (20)     1660 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/src/revpimodio2/_internal.py
+-rw-r--r--   0 svensager   (501) staff       (20)     1104 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/src/revpimodio2/app.py
+-rw-r--r--   0 svensager   (501) staff       (20)    61024 2023-06-08 12:25:13.000000 revpimodio2-2.6.0rc6/src/revpimodio2/device.py
+-rw-r--r--   0 svensager   (501) staff       (20)      256 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/src/revpimodio2/errors.py
+-rw-r--r--   0 svensager   (501) staff       (20)    23236 2023-06-08 09:44:09.000000 revpimodio2-2.6.0rc6/src/revpimodio2/helper.py
+-rw-r--r--   0 svensager   (501) staff       (20)    53076 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/src/revpimodio2/io.py
+-rw-r--r--   0 svensager   (501) staff       (20)    53970 2023-06-08 12:23:16.000000 revpimodio2-2.6.0rc6/src/revpimodio2/modio.py
+-rw-r--r--   0 svensager   (501) staff       (20)    36670 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/src/revpimodio2/netio.py
+-rw-r--r--   0 svensager   (501) staff       (20)     5333 2023-06-08 12:23:16.000000 revpimodio2-2.6.0rc6/src/revpimodio2/pictory.py
+-rw-r--r--   0 svensager   (501) staff       (20)      551 2023-02-07 09:16:12.000000 revpimodio2-2.6.0rc6/src/revpimodio2/summary.py
+drwxr-xr-x   0 svensager   (501) staff       (20)        0 2023-06-08 12:32:07.108690 revpimodio2-2.6.0rc6/src/revpimodio2.egg-info/
+-rw-r--r--   0 svensager   (501) staff       (20)     4568 2023-06-08 12:32:07.000000 revpimodio2-2.6.0rc6/src/revpimodio2.egg-info/PKG-INFO
+-rw-r--r--   0 svensager   (501) staff       (20)      617 2023-06-08 12:32:07.000000 revpimodio2-2.6.0rc6/src/revpimodio2.egg-info/SOURCES.txt
+-rw-r--r--   0 svensager   (501) staff       (20)        1 2023-06-08 12:32:07.000000 revpimodio2-2.6.0rc6/src/revpimodio2.egg-info/dependency_links.txt
+-rw-r--r--   0 svensager   (501) staff       (20)       12 2023-06-08 12:32:07.000000 revpimodio2-2.6.0rc6/src/revpimodio2.egg-info/top_level.txt
```

### Comparing `revpimodio2-2.6.0rc5/LICENSE.txt` & `revpimodio2-2.6.0rc6/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/Makefile` & `revpimodio2-2.6.0rc6/Makefile`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/PKG-INFO` & `revpimodio2-2.6.0rc6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: revpimodio2
-Version: 2.6.0rc5
+Version: 2.6.0rc6
 Summary: Python3 programming for RevolutionPi of KUNBUS GmbH
 Home-page: https://revpimodio.org/
 Author: Sven Sager
 Author-email: akira@narux.de
 Maintainer: Sven Sager
 Maintainer-email: akira@revpimodio.org
 License: LGPLv2
```

### Comparing `revpimodio2-2.6.0rc5/README.md` & `revpimodio2-2.6.0rc6/README.md`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/docs/Makefile` & `revpimodio2-2.6.0rc6/docs/Makefile`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/docs/conf.py` & `revpimodio2-2.6.0rc6/docs/conf.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/docs/revpimodio2.rst` & `revpimodio2-2.6.0rc6/docs/revpimodio2.rst`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/setup.py` & `revpimodio2-2.6.0rc6/setup.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/__init__.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/__init__.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/_internal.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/_internal.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/app.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/app.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/device.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/io.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,1542 +1,1436 @@
 # -*- coding: utf-8 -*-
-"""Modul fuer die Verwaltung der Devices."""
+"""RevPiModIO Modul fuer die Verwaltung der IOs."""
 __author__ = "Sven Sager"
 __copyright__ = "Copyright (C) 2023 Sven Sager"
 __license__ = "LGPLv2"
 
-import warnings
-from threading import Event, Lock, Thread
+import struct
+from re import match as rematch
+from threading import Event
 
-from ._internal import INP, OUT, MEM, PROCESS_IMAGE_SIZE
-from .helper import ProcimgWriter
-from .io import IOBase, IntIO, IntIOCounter, IntIOReplaceable, MemIO
-from .pictory import ProductType
+from ._internal import consttostr, RISING, FALLING, BOTH, INP, OUT, \
+    MEM, PROCESS_IMAGE_SIZE
 
+try:
+    # Funktioniert nur auf Unix
+    from fcntl import ioctl
+except Exception:
+    ioctl = None
 
-class DeviceList(object):
-    """Basisklasse fuer direkten Zugriff auf Device Objekte."""
+
+class IOEvent(object):
+    """Basisklasse fuer IO-Events."""
+
+    __slots__ = "as_thread", "delay", "edge", "func", "overwrite", "prefire"
+
+    def __init__(self, func, edge, as_thread, delay, overwrite, prefire):
+        """Init IOEvent class."""
+        self.as_thread = as_thread
+        self.delay = delay
+        self.edge = edge
+        self.func = func
+        self.overwrite = overwrite
+        self.prefire = prefire
+
+
+class IOList(object):
+    """Basisklasse fuer direkten Zugriff auf IO Objekte."""
 
     def __init__(self):
-        """Init DeviceList class."""
-        self.__dict_position = {}
+        """Init IOList class."""
+        self.__dict_iobyte = {k: [] for k in range(PROCESS_IMAGE_SIZE)}
+        self.__dict_iorefname = {}
 
     def __contains__(self, key):
         """
-        Prueft ob Device existiert.
+        Prueft ob IO existiert.
 
-        :param key: DeviceName <class 'str'> / Positionsnummer <class 'int'>
-        :return: True, wenn Device vorhanden
+        :param key: IO-Name <class 'str'> oder Bytenummer <class 'int'>
+        :return: True, wenn IO vorhanden / Byte belegt
         """
         if type(key) == int:
-            return key in self.__dict_position
-        elif type(key) == str:
-            return hasattr(self, key)
+            return len(self.__dict_iobyte.get(key, [])) > 0
         else:
-            return key in self.__dict_position.values()
+            return hasattr(self, key) and type(getattr(self, key)) != DeadIO
 
-    def __delattr__(self, key, delcomplete=True):
+    def __delattr__(self, key):
         """
-        Entfernt angegebenes Device.
+        Entfernt angegebenen IO.
 
-        :param key: Device zum entfernen
-        :param delcomplete: Wenn True wird Device komplett entfernt
+        :param key: IO zum entfernen
         """
-        if delcomplete:
-            # Device finden
-            if type(key) == int:
-                dev_del = self.__dict_position[key]
-                key = dev_del._name
-            else:
-                dev_del = getattr(self, key)
+        io_del = object.__getattribute__(self, key)
 
-            # Reinigungsjobs
-            dev_del.autorefresh(False)
-            for io in dev_del:
-                delattr(dev_del._modio.io, io._name)
+        # Alte Events vom Device löschen
+        io_del.unreg_event()
 
-            # Device aus dict löschen
-            del self.__dict_position[dev_del._position]
+        # IO aus Byteliste und Attributen entfernen
+        if io_del._bitshift:
+            self.__dict_iobyte[io_del.address][io_del._bitaddress] = None
 
-        if hasattr(self, key):
-            object.__delattr__(self, key)
+            # Do not use any() because we want to know None, not 0
+            if self.__dict_iobyte[io_del.address] == \
+                    [None, None, None, None, None, None, None, None]:
+                self.__dict_iobyte[io_del.address] = []
+        else:
+            self.__dict_iobyte[io_del.address].remove(io_del)
+
+        object.__delattr__(self, key)
+        io_del._parentdevice._update_my_io_list()
 
-    def __delitem__(self, key):
+    def __getattr__(self, key):
         """
-        Entfernt Device an angegebener Position.
+        Verwaltet geloeschte IOs (Attribute, die nicht existieren).
 
-        :param key: Deviceposition zum entfernen
+        :param key: Name oder Byte eines alten IOs
+        :return: Alten IO, wenn in Ref-Listen
         """
-        if isinstance(key, Device):
-            key = key._position
-        self.__delattr__(key)
+        if key in self.__dict_iorefname:
+            return self.__dict_iorefname[key]
+        else:
+            raise AttributeError("can not find io '{0}'".format(key))
 
     def __getitem__(self, key):
         """
-        Gibt angegebenes Device zurueck.
+        Ruft angegebenen IO ab.
 
-        :param key: DeviceName <class 'str'> / Positionsnummer <class 'int'>
-        :return: Gefundenes <class 'Device'>-Objekt
+        Wenn der Key <class 'str'> ist, wird ein einzelner IO geliefert. Wird
+        der Key als <class 'int'> uebergeben, wird eine <class 'list'>
+        geliefert mit 0, 1 oder 8 Eintraegen.
+        Wird als Key <class 'slice'> gegeben, werden die Listen in einer Liste
+        zurueckgegeben.
+
+        :param key: IO Name als <class 'str> oder Byte als <class 'int'>.
+        :return: IO Objekt oder Liste der IOs
         """
         if type(key) == int:
-            if key not in self.__dict_position:
-                raise IndexError("no device on position {0}".format(key))
-            return self.__dict_position[key]
+            if key not in self.__dict_iobyte:
+                raise IndexError("byte '{0}' does not exist".format(key))
+            return self.__dict_iobyte[key]
+        elif type(key) == slice:
+            return [
+                self.__dict_iobyte[int_io]
+                for int_io in range(
+                    key.start, key.stop, 1 if key.step is None else key.step
+                )
+            ]
         else:
             return getattr(self, key)
 
     def __iter__(self):
         """
-        Gibt Iterator aller Devices zurueck.
-
-        Die Reihenfolge ist nach Position im Prozessabbild sortiert und nicht
-        nach Positionsnummer (Dies entspricht der Positionierung aus piCtory)!
+        Gibt Iterator aller IOs zurueck.
 
-        :return: <class 'iter'> aller Devices
+        :return: Iterator aller IOs
         """
-        for dev in sorted(
-                self.__dict_position,
-                key=lambda key: self.__dict_position[key]._offset):
-            yield self.__dict_position[dev]
+        for int_io in sorted(self.__dict_iobyte):
+            for io in self.__dict_iobyte[int_io]:
+                if io is not None:
+                    yield io
 
     def __len__(self):
         """
-        Gibt Anzahl der Devices zurueck.
-
-        :return: Anzahl der Devices"""
-        return len(self.__dict_position)
+        Gibt die Anzahl aller IOs zurueck.
 
-    def __setattr__(self, key, value):
+        :return: Anzahl aller IOs
         """
-        Setzt Attribute nur wenn Device.
+        int_ios = 0
+        for int_io in self.__dict_iobyte:
+            for io in self.__dict_iobyte[int_io]:
+                if io is not None:
+                    int_ios += 1
+        return int_ios
 
-        :param key: Attributname
-        :param value: Attributobjekt
-        """
-        if isinstance(value, Device):
-            object.__setattr__(self, key, value)
-            self.__dict_position[value._position] = value
-        elif key == "_DeviceList__dict_position":
+    def __setattr__(self, key, value):
+        """Verbietet aus Leistungsguenden das direkte Setzen von Attributen."""
+        if key in (
+                "_IOList__dict_iobyte",
+                "_IOList__dict_iorefname"
+        ):
             object.__setattr__(self, key, value)
+        else:
+            raise AttributeError(
+                "direct assignment is not supported - use .value Attribute"
+            )
 
-
-class Device(object):
-    """
-    Basisklasse fuer alle Device-Objekte.
-
-    Die Basisfunktionalitaet generiert bei Instantiierung alle IOs und
-    erweitert den Prozessabbildpuffer um die benoetigten Bytes. Sie verwaltet
-    ihren Prozessabbildpuffer und sorgt fuer die Aktualisierung der IO-Werte.
-    """
-
-    __slots__ = "__my_io_list", "_ba_devdata", "_ba_datacp", \
-        "_dict_events", "_filelock", "_modio", "_name", \
-        "_offset", "_position", "_producttype", "_selfupdate", \
-        "_slc_devoff", "_slc_inp", "_slc_inpoff", "_slc_mem", \
-        "_slc_memoff", "_slc_out", "_slc_outoff", "_shared_procimg", \
-        "_shared_write", \
-        "bmk", "catalognr", "comment", "extend", \
-        "guid", "id", "inpvariant", "outvariant", "type"
-
-    def __init__(self, parentmodio, dict_device, simulator=False):
-        """
-        Instantiierung der Device-Klasse.
-
-        :param parentmodio: RevpiModIO parent object
-        :param dict_device: <class 'dict'> fuer dieses Device aus piCotry
-        :param simulator: Laedt das Modul als Simulator und vertauscht IOs
-        """
-        self._modio = parentmodio
-
-        self._ba_devdata = bytearray()
-        self._ba_datacp = bytearray()  # Copy for event detection
-        self._dict_events = {}
-        self._filelock = Lock()
-        self.__my_io_list = []
-        self._selfupdate = False
-        self._shared_procimg = False
-        self._shared_write = []
-        self.shared_procimg(parentmodio._shared_procimg)  # Set with register
-
-        # Wertzuweisung aus dict_device
-        self._name = dict_device.get("name")
-        self._offset = int(dict_device.get("offset"))
-        self._position = int(dict_device.get("position"))
-        self._producttype = int(dict_device.get("productType"))
-
-        # Offset-Check for broken piCtory configuration
-        if self._offset < parentmodio.length:
-            warnings.warn(
-                "Device offset ERROR in piCtory configuration! Offset of '{0}' "
-                "must be {1} but is {2} - Overlapping devices overwrite the "
-                "same memory, which has unpredictable effects!!!"
-                "".format(self._name, parentmodio.length, self._offset),
-                Warning
-            )
-        # IOM-Objekte erstellen und Adressen in SLCs speichern
-        if simulator:
-            self._slc_inp = self._buildio(
-                dict_device.get("out"), INP)
-            self._slc_out = self._buildio(
-                dict_device.get("inp"), OUT)
-        else:
-            self._slc_inp = self._buildio(
-                dict_device.get("inp"), INP)
-            self._slc_out = self._buildio(
-                dict_device.get("out"), OUT)
-        self._slc_mem = self._buildio(
-            dict_device.get("mem"), MEM
-        )
-
-        # SLCs mit offset berechnen
-        self._slc_devoff = slice(self._offset, self._offset + self.length)
-        self._slc_inpoff = slice(
-            self._slc_inp.start + self._offset,
-            self._slc_inp.stop + self._offset
-        )
-        self._slc_outoff = slice(
-            self._slc_out.start + self._offset,
-            self._slc_out.stop + self._offset
-        )
-        self._slc_memoff = slice(
-            self._slc_mem.start + self._offset,
-            self._slc_mem.stop + self._offset
-        )
-
-        # Alle restlichen attribute an Klasse anhängen
-        self.bmk = dict_device.get("bmk", "")
-        self.catalognr = dict_device.get("catalogNr", "")
-        self.comment = dict_device.get("comment", "")
-        self.extend = dict_device.get("extend", {})
-        self.guid = dict_device.get("GUID", "")
-        self.id = dict_device.get("id", "")
-        self.inpvariant = dict_device.get("inpVariant", 0)
-        self.outvariant = dict_device.get("outVariant", 0)
-        self.type = dict_device.get("type", "")
-
-        # Spezielle Konfiguration von abgeleiteten Klassen durchführen
-        self._devconfigure()
-
-        # IO Liste aktualisieren für schnellen Indexzugriff
-        self._update_my_io_list()
-
-    def __bytes__(self):
+    def __private_replace_oldio_with_newio(self, io) -> None:
         """
-        Gibt alle Daten des Devices als <class 'bytes'> zurueck.
+        Ersetzt bestehende IOs durch den neu Registrierten.
 
-        :return: Devicedaten als <class 'bytes'>
+        :param io: Neuer IO der eingefuegt werden soll
         """
-        return bytes(self._ba_devdata)
+        # Scanbereich festlegen
+        if io._bitshift:
+            scan_start = io._parentio_address
+            scan_stop = scan_start + io._parentio_length
+        else:
+            scan_start = io.address
+            scan_stop = scan_start + (1 if io._length == 0 else io._length)
+
+        # Defaultvalue über mehrere Bytes sammeln
+        calc_defaultvalue = b''
+
+        for i in range(scan_start, scan_stop):
+            for oldio in self.__dict_iobyte[i]:
+
+                if type(oldio) == StructIO:
+                    # Hier gibt es schon einen neuen IO
+                    if oldio._bitshift:
+                        if io._bitshift == oldio._bitshift \
+                                and io._slc_address == oldio._slc_address:
+                            raise MemoryError(
+                                "bit {0} already assigned to '{1}'".format(
+                                    io._bitaddress, oldio._name
+                                )
+                            )
+                    else:
+                        # Bereits überschriebene bytes sind ungültig
+                        raise MemoryError(
+                            "new io '{0}' overlaps memory of '{1}'".format(
+                                io._name, oldio._name
+                            )
+                        )
+                elif oldio is not None:
+                    # IOs im Speicherbereich des neuen IO merken
+                    if io._bitshift:
+                        # ios für ref bei bitaddress speichern
+                        self.__dict_iorefname[oldio._name] = DeadIO(oldio)
+                    else:
+                        # Defaultwert berechnen
+                        oldio.byteorder = io._byteorder
+                        if io._byteorder == "little":
+                            calc_defaultvalue += oldio._defaultvalue
+                        else:
+                            calc_defaultvalue = \
+                                oldio._defaultvalue + calc_defaultvalue
+
+                    # ios aus listen entfernen
+                    delattr(self, oldio._name)
+
+        if io._defaultvalue is None:
+            # Nur bei StructIO und keiner gegebenen defaultvalue übernehmen
+            if io._bitshift:
+                io_byte_address = io._parentio_address - io.address
+                io._defaultvalue = bool(
+                    io._parentio_defaultvalue[io_byte_address] & io._bitshift
+                )
+            else:
+                io._defaultvalue = calc_defaultvalue
 
-    def __contains__(self, key):
+    def _private_register_new_io_object(self, new_io) -> None:
         """
-        Prueft ob IO auf diesem Device liegt.
+        Registriert neues IO Objekt unabhaenging von __setattr__.
 
-        :param key: IO-Name <class 'str'> / IO-Bytenummer <class 'int'>
-        :return: True, wenn IO auf Device vorhanden
+        :param new_io: Neues IO Objekt
         """
-        if isinstance(key, IOBase):
-            # Umwandlung für key
-            key = key._name
+        if isinstance(new_io, IOBase):
+            if hasattr(self, new_io._name):
+                raise AttributeError(
+                    "attribute {0} already exists - can not set io"
+                    "".format(new_io._name)
+                )
 
-        if type(key) == int:
-            if key in self._modio.io:
-                for io in self._modio.io[key]:
-                    if io is not None and io._parentdevice == self:
-                        return True
-            return False
-        else:
-            return key in self._modio.io \
-                and getattr(self._modio.io, key)._parentdevice == self
+            if type(new_io) is StructIO:
+                self.__private_replace_oldio_with_newio(new_io)
 
-    def __getitem__(self, key):
-        """
-        Gibt IO an angegebener Stelle zurueck.
+            object.__setattr__(self, new_io._name, new_io)
 
-        :param key: Index des IOs auf dem device als <class 'int'>
-        :return: Gefundenes IO-Objekt
-        """
-        return self.__my_io_list[key]
+            # Bytedict für Adresszugriff anpassen
+            if new_io._bitshift:
+                if len(self.__dict_iobyte[new_io.address]) != 8:
+                    # "schnell" 8 Einträge erstellen da es BIT IOs sind
+                    self.__dict_iobyte[new_io.address] += \
+                        [None, None, None, None, None, None, None, None]
+                self.__dict_iobyte[new_io.address][new_io._bitaddress] = new_io
+            else:
+                self.__dict_iobyte[new_io.address].append(new_io)
 
-    def __int__(self):
-        """
-        Gibt die Positon im RevPi Bus zurueck.
+            if type(new_io) is StructIO:
+                new_io._parentdevice._update_my_io_list()
+        else:
+            raise TypeError("io must be <class 'IOBase'> or sub class")
 
-        :return: Positionsnummer
-        """
-        return self._position
 
-    def __iter__(self):
-        """
-        Gibt Iterator aller IOs zurueck.
+class DeadIO(object):
+    """Klasse, mit der ersetzte IOs verwaltet werden."""
 
-        :return: <class 'iter'> aller IOs
-        """
-        return self.__getioiter(self._slc_devoff, None)
+    __slots__ = "__deadio"
 
-    def __len__(self):
+    def __init__(self, deadio):
         """
-        Gibt Anzahl der Bytes zurueck, die dieses Device belegt.
+        Instantiierung der DeadIO-Klasse.
 
-        :return: <class 'int'>
+        :param deadio: IO, der ersetzt wurde
         """
-        return len(self._ba_devdata)
+        self.__deadio = deadio
 
-    def __str__(self):
+    def replace_io(self, name: str, frm: str, **kwargs) -> None:
         """
-        Gibt den Namen des Devices zurueck.
+        Stellt Funktion fuer weiter Bit-Ersetzungen bereit.
 
-        :return: Devicename
+        :ref: :func:IntIOReplaceable.replace_io()
         """
-        return self._name
+        self.__deadio.replace_io(name, frm, **kwargs)
 
-    def __getioiter(self, ioslc: slice, export):
-        """
-        Gibt <class 'iter'> mit allen IOs zurueck.
+    _parentdevice = property(lambda self: None)
 
-        :param ioslc: IO Abschnitt <class 'slice'>
-        :param export: Filter fuer 'Export' Flag in piCtory
-        :return: IOs als Iterator
-        """
-        for lst_io in self._modio.io[ioslc]:
-            for io in lst_io:
-                if io is not None and (export is None or io.export == export):
-                    yield io
 
-    def _buildio(self, dict_io: dict, iotype: int) -> slice:
-        """
-        Erstellt aus der piCtory-Liste die IOs fuer dieses Device.
+class IOBase(object):
+    """
+    Basisklasse fuer alle IO-Objekte.
+
+    Die Basisfunktionalitaet ermoeglicht das Lesen und Schreiben der Werte
+    als <class bytes'> oder <class 'bool'>. Dies entscheidet sich bei der
+    Instantiierung.
+    Wenn eine Bittadresse angegeben wird, werden <class 'bool'>-Werte erwartet
+    und zurueckgegeben, ansonsten <class bytes'>.
+
+    Diese Klasse dient als Basis fuer andere IO-Klassen mit denen die Werte
+    auch als <class 'int'> verwendet werden koennen.
+    """
 
-        :param dict_io: <class 'dict'>-Objekt aus piCtory Konfiguration
+    __slots__ = "__bit_ioctl_off", "__bit_ioctl_on", "_bitaddress", \
+        "_bitshift", "_bitlength", "_byteorder", "_defaultvalue", \
+        "_export", "_iotype", "_length", "_name", "_parentdevice", \
+        "_read_only_io", "_signed", "_slc_address", "bmk"
+
+    def __init__(self, parentdevice, valuelist: list, iotype: int,
+                 byteorder: str, signed: bool):
+        """
+        Instantiierung der IOBase-Klasse.
+
+        :param parentdevice: Parentdevice auf dem der IO liegt
+        :param valuelist: Datenliste fuer Instantiierung
+            ["name","defval","bitlen","startaddrdev",exp,"idx","bmk","bitaddr"]
         :param iotype: <class 'int'> Wert
-        :return: <class 'slice'> mit Start und Stop Position dieser IOs
+        :param byteorder: Byteorder 'little'/'big' fuer <class 'int'> Berechnung
+        :param signed: Intberechnung mit Vorzeichen durchfuehren
         """
-        if len(dict_io) <= 0:
-            return slice(0, 0)
-
-        int_min, int_max = PROCESS_IMAGE_SIZE, 0
-        for key in sorted(dict_io, key=lambda x: int(x)):
+        # ["name","defval","bitlen","startaddrdev",exp,"idx","bmk","bitaddr"]
+        # [  0   ,   1    ,   2    ,       3      , 4 ,  5  ,  6  ,    7    ]
+        self._parentdevice = parentdevice
+
+        # Bitadressen auf Bytes aufbrechen und umrechnen
+        self._bitaddress = -1 if valuelist[7] == "" else int(valuelist[7]) % 8
+        self._bitshift = None if self._bitaddress == -1 \
+            else 1 << self._bitaddress
+
+        # Längenberechnung
+        self._bitlength = int(valuelist[2])
+        self._length = 1 if self._bitaddress == 0 else int(self._bitlength / 8)
+
+        self.__bit_ioctl_off = None
+        self.__bit_ioctl_on = None
+        self._read_only_io = iotype != OUT
+        self._byteorder = byteorder
+        self._iotype = iotype
+        self._name = valuelist[0]
+        self._signed = signed
+        self.bmk = valuelist[6]
+        self._export = int(valuelist[4]) & 1
+
+        int_startaddress = int(valuelist[3])
+        if self._bitshift:
+            # Höhere Bits als 7 auf nächste Bytes umbrechen
+            int_startaddress += int(int(valuelist[7]) / 8)
+            self._slc_address = slice(
+                int_startaddress, int_startaddress + 1
+            )
 
-            # Neuen IO anlegen
-            if iotype == MEM:
-                # Memory setting
-                io_new = MemIO(
-                    self, dict_io[key],
-                    iotype,
-                    "little",
-                    False
-                )
-            elif bool(dict_io[key][7]):
-                # Bei Bitwerten IOBase verwenden
-                io_new = IOBase(
-                    self, dict_io[key], iotype, "little", False
-                )
-            elif isinstance(self, DioModule) and \
-                    dict_io[key][3] in self._lst_counter:
-                # Counter IO auf einem DI oder DIO
-                io_new = IntIOCounter(
-                    self._lst_counter.index(dict_io[key][3]),
-                    self, dict_io[key],
-                    iotype,
-                    "little",
-                    False
-                )
-            elif isinstance(self, Gateway):
-                # Ersetzbare IOs erzeugen
-                io_new = IntIOReplaceable(
-                    self, dict_io[key],
-                    iotype,
-                    "little",
-                    False
-                )
+            # Defaultvalue ermitteln, sonst False
+            if valuelist[1] is None and type(self) == StructIO:
+                self._defaultvalue = None
             else:
-                io_new = IntIO(
-                    self, dict_io[key],
-                    iotype,
-                    "little",
-                    # Bei AIO (103) signed auf True setzen
-                    self._producttype == ProductType.AIO
-                )
-
-            if io_new.address < self._modio.length:
-                warnings.warn(
-                    "IO {0} is not in the device offset and will be ignored"
-                    "".format(io_new.name),
-                    Warning
+                try:
+                    self._defaultvalue = bool(int(valuelist[1]))
+                except Exception:
+                    self._defaultvalue = False
+
+            # Ioctl für Bitsetzung setzen
+            self.__bit_ioctl_off = struct.pack(
+                "<HB", self._get_address(), self._bitaddress
+            )
+            self.__bit_ioctl_on = self.__bit_ioctl_off + b'\x01'
+        else:
+            self._slc_address = slice(
+                int_startaddress, int_startaddress + self._length
+            )
+            if str(valuelist[1]).isdigit():
+                # Defaultvalue aus Zahl in Bytes umrechnen
+                self._defaultvalue = int(valuelist[1]).to_bytes(
+                    self._length, byteorder=self._byteorder
                 )
+            elif valuelist[1] is None and type(self) == StructIO:
+                # Auf None setzen um später berechnete Werte zu übernehmen
+                self._defaultvalue = None
+            elif type(valuelist[1]) == bytes:
+                # Defaultvalue direkt von bytes übernehmen
+                if len(valuelist[1]) == self._length:
+                    self._defaultvalue = valuelist[1]
+                else:
+                    raise ValueError(
+                        "given bytes for default value must have a length "
+                        "of {0} but {1} was given"
+                        "".format(self._length, len(valuelist[1]))
+                    )
             else:
-                # IO registrieren
-                self._modio.io._private_register_new_io_object(io_new)
+                # Defaultvalue mit leeren Bytes füllen
+                self._defaultvalue = bytes(self._length)
 
-            # Kleinste und größte Speicheradresse ermitteln
-            if io_new._slc_address.start < int_min:
-                int_min = io_new._slc_address.start
-            if io_new._slc_address.stop > int_max:
-                int_max = io_new._slc_address.stop
-
-        self._ba_devdata += bytearray(int_max - int_min)
-        return slice(int_min, int_max)
+                # Versuchen String in ASCII Bytes zu wandeln
+                if type(valuelist[1]) == str:
+                    try:
+                        buff = valuelist[1].encode("ASCII")
+                        if len(buff) <= self._length:
+                            self._defaultvalue = \
+                                buff + bytes(self._length - len(buff))
+                    except Exception:
+                        pass
+
+    def __bool__(self):
+        """
+        <class 'bool'>-Wert der Klasse.
+
+        :return: <class 'bool'> Nur False wenn False oder 0 sonst True
+        """
+        if self._bitshift:
+            return bool(
+                self._parentdevice._ba_devdata[self._slc_address.start]
+                & self._bitshift
+            )
+        else:
+            return any(self._parentdevice._ba_devdata[self._slc_address])
 
-    def _devconfigure(self):
-        """Funktion zum ueberschreiben von abgeleiteten Klassen."""
-        pass
+    def __call__(self, value=None):
+        if value is None:
+            # Inline get_value()
+            if self._bitshift:
+                return bool(
+                    self._parentdevice._ba_devdata[self._slc_address.start]
+                    & self._bitshift
+                )
+            else:
+                return bytes(self._parentdevice._ba_devdata[self._slc_address])
+        else:
+            self.set_value(value)
 
-    def _get_offset(self) -> int:
+    def __len__(self):
         """
-        Gibt den Deviceoffset im Prozessabbild zurueck.
+        Gibt die Bytelaenge des IO zurueck.
 
-        :return: Deviceoffset
+        :return: Bytelaenge des IO - 0 bei BITs
         """
-        return self._offset
+        return 0 if self._bitaddress > 0 else self._length
 
-    def _get_producttype(self) -> int:
+    def __str__(self):
         """
-        Gibt den Produkttypen des device zurueck.
+        <class 'str'>-Wert der Klasse.
 
-        :return: Deviceprodukttyp
+        :return: Namen des IOs
         """
-        return self._producttype
-
-    def _update_my_io_list(self) -> None:
-        """Erzeugt eine neue IO Liste fuer schnellen Zugriff."""
-        self.__my_io_list = list(self.__iter__())
+        return self._name
 
-    def autorefresh(self, activate=True) -> None:
+    def __reg_xevent(self, func, delay: int, edge: int, as_thread: bool,
+                     overwrite: bool, prefire: bool) -> None:
         """
-        Registriert dieses Device fuer die automatische Synchronisierung.
+        Verwaltet reg_event und reg_timerevent.
 
-        :param activate: Default True fuegt Device zur Synchronisierung hinzu
+        :param func: Funktion die bei Aenderung aufgerufen werden soll
+        :param delay: Verzoegerung in ms zum Ausloesen - auch bei Wertaenderung
+        :param edge: Ausfuehren bei RISING, FALLING or BOTH Wertaenderung
+        :param as_thread: Bei True, Funktion als EventCallback-Thread ausfuehren
+        :param overwrite: Wenn True, wird Event bei ueberschrieben
+        :param prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
         """
-        if activate and self not in self._modio._lst_refresh:
-
-            # Daten bei Aufnahme direkt einlesen!
-            self._modio.readprocimg(self)
-
-            # Datenkopie anlegen
-            with self._filelock:
-                self._ba_datacp = self._ba_devdata[:]
-
-            self._selfupdate = True
-
-            # Sicher in Liste einfügen
-            with self._modio._imgwriter.lck_refresh:
-                self._modio._lst_refresh.append(self)
-
-            # Thread starten, wenn er noch nicht läuft
-            if not self._modio._imgwriter.is_alive():
-                # Alte Einstellungen speichern
-                imgrefresh = self._modio._imgwriter.refresh
-
-                # ImgWriter mit alten Einstellungen erstellen
-                self._modio._imgwriter = ProcimgWriter(self._modio)
-                self._modio._imgwriter.refresh = imgrefresh
-                self._modio._imgwriter.start()
-
-        elif not activate and self in self._modio._lst_refresh:
-            # Sicher aus Liste entfernen
-            with self._modio._imgwriter.lck_refresh:
-                self._modio._lst_refresh.remove(self)
-            self._selfupdate = False
-
-            # Beenden, wenn keien Devices mehr in Liste sind
-            if len(self._modio._lst_refresh) == 0:
-                self._modio._imgwriter.stop()
+        # Prüfen ob Funktion callable ist
+        if not callable(func):
+            raise ValueError(
+                "registered function '{0}' is not callable".format(func)
+            )
+        if type(delay) != int or delay < 0:
+            raise ValueError(
+                "'delay' must be <class 'int'> and greater or equal 0"
+            )
+        if edge != BOTH and not self._bitshift:
+            raise ValueError(
+                "parameter 'edge' can be used with bit io objects only"
+            )
+        if prefire and self._parentdevice._modio._looprunning:
+            raise RuntimeError(
+                "prefire can not be used if mainloop is running"
+            )
 
-            # Daten beim Entfernen noch einmal schreiben
-            if not self._modio._monitoring:
-                self._modio.writeprocimg(self)
+        if self not in self._parentdevice._dict_events:
+            with self._parentdevice._filelock:
+                self._parentdevice._dict_events[self] = \
+                    [IOEvent(func, edge, as_thread, delay, overwrite, prefire)]
+        else:
+            # Prüfen ob Funktion schon registriert ist
+            for regfunc in self._parentdevice._dict_events[self]:
+                if regfunc.func != func:
+                    # Nächsten Eintrag testen
+                    continue
+
+                if edge == BOTH or regfunc.edge == BOTH:
+                    if self._bitshift:
+                        raise RuntimeError(
+                            "io '{0}' with function '{1}' already in list "
+                            "with edge '{2}' - edge '{3}' not allowed anymore"
+                            "".format(
+                                self._name, func,
+                                consttostr(regfunc.edge), consttostr(edge)
+                            )
+                        )
+                    else:
+                        raise RuntimeError(
+                            "io '{0}' with function '{1}' already in list."
+                            "".format(self._name, func)
+                        )
+
+                elif regfunc.edge == edge:
+                    raise RuntimeError(
+                        "io '{0}' with function '{1}' for given edge '{2}' "
+                        "already in list".format(
+                            self._name, func, consttostr(edge)
+                        )
+                    )
+
+            # Eventfunktion einfügen
+            with self._parentdevice._filelock:
+                self._parentdevice._dict_events[self].append(
+                    IOEvent(func, edge, as_thread, delay, overwrite, prefire)
+                )
 
-    def get_allios(self, export=None) -> list:
+    def _get_address(self) -> int:
         """
-        Gibt eine Liste aller Inputs und Outputs zurueck, keine MEMs.
+        Gibt die absolute Byteadresse im Prozessabbild zurueck.
 
-        Bleibt Parameter 'export' auf None werden alle Inputs und Outputs
-        zurueckgegeben. Wird 'export' auf True/False gesetzt, werden nur Inputs
-        und Outputs zurueckgegeben, bei denen der Wert 'Export' in piCtory
-        uebereinstimmt.
+        :return: Absolute Byteadresse
+        """
+        return self._parentdevice._offset + self._slc_address.start
 
-        :param export: Nur In-/Outputs mit angegebenen 'Export' Wert in piCtory
-        :return: <class 'list'> Input und Output, keine MEMs
+    def _get_byteorder(self) -> str:
         """
-        return list(self.__getioiter(
-            slice(self._slc_inpoff.start, self._slc_outoff.stop), export
-        ))
+        Gibt konfigurierte Byteorder zurueck.
 
-    def get_inputs(self, export=None) -> list:
+        :return: <class 'str'> Byteorder
         """
-        Gibt eine Liste aller Inputs zurueck.
+        return self._byteorder
 
-        Bleibt Parameter 'export' auf None werden alle Inputs zurueckgegeben.
-        Wird 'export' auf True/False gesetzt, werden nur Inputs zurueckgegeben,
-        bei denen der Wert 'Export' in piCtory uebereinstimmt.
+    def _get_export(self) -> bool:
+        """Return value of export flag."""
+        return bool(self._export & 1)
 
-        :param export: Nur Inputs mit angegebenen 'Export' Wert in piCtory
-        :return: <class 'list'> Inputs
+    def _get_iotype(self) -> int:
         """
-        return list(self.__getioiter(self._slc_inpoff, export))
+        Gibt io type zurueck.
 
-    def get_outputs(self, export=None) -> list:
+        :return: <class 'int'> io type
         """
-        Gibt eine Liste aller Outputs zurueck.
+        return self._iotype
 
-        Bleibt Parameter 'export' auf None werden alle Outputs zurueckgegeben.
-        Wird 'export' auf True/False gesetzt, werden nur Outputs
-        zurueckgegeben, bei denen der Wert 'Export' in piCtory uebereinstimmt.
+    def _set_export(self, value: bool) -> None:
+        """Set value of export flag and remember this change for export."""
+        if type(value) != bool:
+            raise ValueError("Value must be <class 'bool'>")
+        self._export = 2 + int(value)
 
-        :param export: Nur Outputs mit angegebenen 'Export' Wert in piCtory
-        :return: <class 'list'> Outputs
+    def _write_to_procimg(self) -> bool:
         """
-        return list(self.__getioiter(self._slc_outoff, export))
+        Write value of io directly to the process image.
 
-    def get_memories(self, export=None) -> list:
+        :return: True after successful write operation
         """
-        Gibt eine Liste aller Memoryobjekte zurueck.
+        if not self._parentdevice._shared_procimg:
+            raise RuntimeError("device is not marked for shared_procimg")
 
-        Bleibt Parameter 'export' auf None werden alle Mems zurueckgegeben.
-        Wird 'export' auf True/False gesetzt, werden nur Mems zurueckgegeben,
-        bei denen der Wert 'Export' in piCtory uebereinstimmt.
+        # note: Will not be removed from _shared_write on direct call
 
-        :param export: Nur Mems mit angegebenen 'Export' Wert in piCtory
-        :return: <class 'list'> Mems
-        """
-        return list(self.__getioiter(self._slc_memoff, export))
-
-    def readprocimg(self) -> bool:
-        """
-        Alle Inputs fuer dieses Device vom Prozessabbild einlesen.
+        if self._bitshift:
+            # Write single bit to process image
+            value = \
+                self._parentdevice._ba_devdata[self._slc_address.start] & \
+                self._bitshift
+            if self._parentdevice._modio._run_on_pi:
+                # IOCTL auf dem RevPi
+                with self._parentdevice._modio._myfh_lck:
+                    try:
+                        # Set value durchführen (Funktion K+16)
+                        ioctl(
+                            self._parentdevice._modio._myfh,
+                            19216,
+                            self.__bit_ioctl_on if value
+                            else self.__bit_ioctl_off
+                        )
+                    except Exception as e:
+                        self._parentdevice._modio._gotioerror("ioset", e)
+                        return False
 
+            elif hasattr(self._parentdevice._modio._myfh, "ioctl"):
+                # IOCTL über Netzwerk
+                with self._parentdevice._modio._myfh_lck:
+                    try:
+                        self._parentdevice._modio._myfh.ioctl(
+                            19216,
+                            self.__bit_ioctl_on if value
+                            else self.__bit_ioctl_off
+                        )
+                    except Exception as e:
+                        self._parentdevice._modio._gotioerror(
+                            "net_ioset", e)
+                        return False
 
-        Same  see
+            else:
+                # IOCTL in Datei simulieren
+                try:
+                    # Set value durchführen (Funktion K+16)
+                    self._parentdevice._modio._simulate_ioctl(
+                        19216,
+                        self.__bit_ioctl_on if value
+                        else self.__bit_ioctl_off
+                    )
+                except Exception as e:
+                    self._parentdevice._modio._gotioerror("file_ioset", e)
+                    return False
+
+        else:
+            value = bytes(self._parentdevice._ba_devdata[self._slc_address])
+            with self._parentdevice._modio._myfh_lck:
+                try:
+                    self._parentdevice._modio._myfh.seek(
+                        self._get_address()
+                    )
+                    self._parentdevice._modio._myfh.write(value)
+                    if self._parentdevice._modio._buffedwrite:
+                        self._parentdevice._modio._myfh.flush()
+                except IOError as e:
+                    self._parentdevice._modio._gotioerror("ioset", e)
+                    return False
+
+        return True
+
+    def get_defaultvalue(self):
+        """
+        Gibt die Defaultvalue von piCtory zurueck.
+
+        :return: Defaultvalue als <class 'byte'> oder <class 'bool'>
+        """
+        return self._defaultvalue
+
+    def get_value(self):
+        """
+        Gibt den Wert des IOs zurueck.
+
+        :return: IO-Wert als <class 'bytes'> oder <class 'bool'>
+        """
+        if self._bitshift:
+            return bool(
+                self._parentdevice._ba_devdata[self._slc_address.start]
+                & self._bitshift
+            )
+        else:
+            return bytes(self._parentdevice._ba_devdata[self._slc_address])
 
-        :return: True, wenn erfolgreich ausgefuehrt
-        :ref: :func:`revpimodio2.modio.RevPiModIO.readprocimg()`
+    def reg_event(
+            self, func, delay=0, edge=BOTH, as_thread=False, prefire=False):
         """
-        return self._modio.readprocimg(self)
+        Registriert fuer IO ein Event bei der Eventueberwachung.
 
-    def setdefaultvalues(self) -> None:
-        """
-        Alle Outputbuffer fuer dieses Device auf default Werte setzen.
+        Die uebergebene Funktion wird ausgefuehrt, wenn sich der IO Wert
+        aendert. Mit Angabe von optionalen Parametern kann das
+        Ausloeseverhalten gesteuert werden.
+
+        HINWEIS: Die delay-Zeit muss in die .cycletime passen, ist dies nicht
+        der Fall, wird IMMER aufgerundet!
+
+        :param func: Funktion die bei Aenderung aufgerufen werden soll
+        :param delay: Verzoegerung in ms zum Ausloesen wenn Wert gleich bleibt
+        :param edge: Ausfuehren bei RISING, FALLING or BOTH Wertaenderung
+        :param as_thread: Bei True, Funktion als EventCallback-Thread ausfuehren
+        :param prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
+        """
+        self.__reg_xevent(func, delay, edge, as_thread, True, prefire)
+
+    def reg_timerevent(
+            self, func, delay, edge=BOTH, as_thread=False, prefire=False):
+        """
+        Registriert fuer IO einen Timer, welcher nach delay func ausfuehrt.
+
+        Der Timer wird gestartet, wenn sich der IO Wert aendert und fuehrt die
+        uebergebene Funktion aus - auch wenn sich der IO Wert in der
+        zwischenzeit geaendert hat. Sollte der Timer nicht abelaufen sein und
+        die Bedingugn erneut zutreffen, wird der Timer NICHT auf den delay Wert
+        zurueckgesetzt oder ein zweites Mal gestartet. Fuer dieses Verhalten
+        kann .reg_event(..., delay=wert) verwendet werden.
+
+        HINWEIS: Die delay-Zeit muss in die .cycletime passen, ist dies nicht
+        der Fall, wird IMMER aufgerundet!
+
+        :param func: Funktion die bei Aenderung aufgerufen werden soll
+        :param delay: Verzoegerung in ms zum Ausloesen - auch bei Wertaenderung
+        :param edge: Ausfuehren bei RISING, FALLING or BOTH Wertaenderung
+        :param as_thread: Bei True, Funktion als EventCallback-Thread ausfuehren
+        :param prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
+        """
+        self.__reg_xevent(func, delay, edge, as_thread, False, prefire)
+
+    def set_value(self, value) -> None:
+        """
+        Setzt den Wert des IOs.
+
+        :param value: IO-Wert als <class bytes'> oder <class 'bool'>
+        """
+        if self._read_only_io:
+            if self._iotype == INP:
+                if self._parentdevice._modio._simulator:
+                    raise RuntimeError(
+                        "can not write to output '{0}' in simulator mode"
+                        "".format(self._name)
+                    )
+                else:
+                    raise RuntimeError(
+                        "can not write to input '{0}'".format(self._name)
+                    )
+            elif self._iotype == MEM:
+                raise RuntimeError(
+                    "can not write to memory '{0}'".format(self._name)
+                )
+            raise RuntimeError(
+                "the io object '{0}' is read only".format(self._name)
+            )
 
-        :return: True, wenn erfolgreich ausgefuehrt
-        :ref: :func:`revpimodio2.modio.RevPiModIO.setdefaultvalues()`
-        """
-        self._modio.setdefaultvalues(self)
+        if self._bitshift:
+            # Versuchen egal welchen Typ in Bool zu konvertieren
+            value = bool(value)
+
+            # Für Bitoperationen sperren
+            self._parentdevice._filelock.acquire()
+
+            if self._parentdevice._shared_procimg \
+                    and self not in self._parentdevice._shared_write:
+                # Mark this IO for write operations
+                self._parentdevice._shared_write.append(self)
+
+            # Hier gibt es immer nur ein byte, als int holen
+            int_byte = self._parentdevice._ba_devdata[self._slc_address.start]
+
+            # Aktuellen Wert vergleichen und ggf. setzen
+            if not bool(int_byte & self._bitshift) == value:
+                if value:
+                    int_byte += self._bitshift
+                else:
+                    int_byte -= self._bitshift
+
+                # Zurückschreiben wenn verändert
+                self._parentdevice._ba_devdata[self._slc_address.start] = \
+                    int_byte
+
+            self._parentdevice._filelock.release()
+
+        else:
+            if type(value) != bytes:
+                raise TypeError(
+                    "'{0}' requires a <class 'bytes'> object, not {1}".format(
+                        self._name, type(value)
+                    )
+                )
 
-    def shared_procimg(self, activate: bool) -> None:
-        """
-        Activate sharing of process image just for this device.
+            if self._length != len(value):
+                raise ValueError(
+                    "'{0}' requires a <class 'bytes'> object of "
+                    "length {1}, but {2} was given".format(
+                        self._name, self._length, len(value)
+                    )
+                )
 
-        :param activate: Set True to activate process image sharing
-        """
-        with self._filelock:
-            self._shared_write.clear()
-        self._shared_procimg = True if activate else False
-        if self._shared_procimg and self not in self._modio._lst_shared:
-            self._modio._lst_shared.append(self)
-        elif not self._shared_procimg and self in self._modio._lst_shared:
-            self._modio._lst_shared.remove(self)
+            if self._parentdevice._shared_procimg \
+                    and self not in self._parentdevice._shared_write:
+                with self._parentdevice._filelock:
+                    # Mark this IO as changed
+                    self._parentdevice._shared_write.append(self)
 
-    def syncoutputs(self) -> bool:
-        """
-        Lesen aller Outputs im Prozessabbild fuer dieses Device.
+            self._parentdevice._ba_devdata[self._slc_address] = value
 
-        :return: True, wenn erfolgreich ausgefuehrt
-        :ref: :func:`revpimodio2.modio.RevPiModIO.syncoutputs()`
+    def unreg_event(self, func=None, edge=None) -> None:
         """
-        return self._modio.syncoutputs(self)
+        Entfernt ein Event aus der Eventueberwachung.
 
-    def writeprocimg(self) -> bool:
+        :param func: Nur Events mit angegebener Funktion
+        :param edge: Nur Events mit angegebener Funktion und angegebener Edge
         """
-        Schreiben aller Outputs dieses Devices ins Prozessabbild.
+        if self in self._parentdevice._dict_events:
+            if func is None:
+                with self._parentdevice._filelock:
+                    del self._parentdevice._dict_events[self]
+            else:
+                newlist = []
+                for regfunc in self._parentdevice._dict_events[self]:
+                    if regfunc.func != func or edge is not None \
+                            and regfunc.edge != edge:
+                        newlist.append(regfunc)
+
+                # Wenn Funktionen übrig bleiben, diese übernehmen
+                with self._parentdevice._filelock:
+                    if len(newlist) > 0:
+                        self._parentdevice._dict_events[self] = newlist
+                    else:
+                        del self._parentdevice._dict_events[self]
+
+    def wait(self, edge=BOTH, exitevent=None, okvalue=None, timeout=0) -> int:
+        """
+        Wartet auf Wertaenderung eines IOs.
+
+        Die Wertaenderung wird immer uerberprueft, wenn fuer Devices
+        mit aktiviertem autorefresh neue Daten gelesen wurden.
+
+        Bei Wertaenderung, wird das Warten mit 0 als Rueckgabewert beendet.
+
+        HINWEIS: Wenn <class 'ProcimgWriter'> keine neuen Daten liefert, wird
+        bis in die Ewigkeit gewartet (nicht bei Angabe von "timeout").
+
+        Wenn edge mit RISING oder FALLING angegeben wird, muss diese Flanke
+        ausgeloest werden. Sollte der Wert 1 sein beim Eintritt mit Flanke
+        RISING, wird das Warten erst bei Aenderung von 0 auf 1 beendet.
+
+        Als exitevent kann ein <class 'threading.Event'>-Objekt uebergeben
+        werden, welches das Warten bei is_set() sofort mit 1 als Rueckgabewert
+        beendet.
+
+        Wenn der Wert okvalue an dem IO fuer das Warten anliegt, wird
+        das Warten sofort mit -1 als Rueckgabewert beendet.
+
+        Der Timeoutwert bricht beim Erreichen das Warten sofort mit
+        Wert 2 Rueckgabewert ab. (Das Timeout wird ueber die Zykluszeit
+        der autorefresh Funktion berechnet, entspricht also nicht exakt den
+        angegeben Millisekunden! Es wird immer nach oben gerundet!)
+
+        :param edge: Flanke RISING, FALLING, BOTH die eintreten muss
+        :param exitevent: <class 'thrading.Event'> fuer vorzeitiges Beenden
+        :param okvalue: IO-Wert, bei dem das Warten sofort beendet wird
+        :param timeout: Zeit in ms nach der abgebrochen wird
+        :return: <class 'int'> erfolgreich Werte <= 0
+
+        - Erfolgreich gewartet
+            - Wert 0: IO hat den Wert gewechselt
+            - Wert -1: okvalue stimmte mit IO ueberein
+        - Fehlerhaft gewartet
+            - Wert 1: exitevent wurde gesetzt
+            - Wert 2: timeout abgelaufen
+            - Wert 100: Devicelist.exit() wurde aufgerufen
 
-        :return: True, wenn erfolgreich ausgefuehrt
-        :ref: :func:`revpimodio2.modio.RevPiModIO.writeprocimg()`
         """
-        return self._modio.writeprocimg(self)
+        # Prüfen ob Device in autorefresh ist
+        if not self._parentdevice._selfupdate:
+            raise RuntimeError(
+                "autorefresh is not activated for device '{0}|{1}' - there "
+                "will never be new data".format(
+                    self._parentdevice._position, self._parentdevice._name
+                )
+            )
+        if not (RISING <= edge <= BOTH):
+            raise ValueError(
+                "parameter 'edge' must be revpimodio2.RISING, "
+                "revpimodio2.FALLING or revpimodio2.BOTH"
+            )
+        if not (exitevent is None or type(exitevent) == Event):
+            raise TypeError(
+                "parameter 'exitevent' must be <class 'threading.Event'>"
+            )
+        if type(timeout) != int or timeout < 0:
+            raise ValueError(
+                "parameter 'timeout' must be <class 'int'> and greater than 0"
+            )
+        if edge != BOTH and not self._bitshift:
+            raise ValueError(
+                "parameter 'edge' can be used with bit Inputs only"
+            )
 
+        # Abbruchwert prüfen
+        if okvalue == self.value:
+            return -1
+
+        # WaitExit Event säubern
+        self._parentdevice._modio._waitexit.clear()
+
+        val_start = self.value
+        timeout = timeout / 1000
+        bool_timecount = timeout > 0
+        if exitevent is None:
+            exitevent = Event()
+
+        flt_timecount = 0 if bool_timecount else -1
+        while not self._parentdevice._modio._waitexit.is_set() \
+                and not exitevent.is_set() \
+                and flt_timecount < timeout:
+
+            if self._parentdevice._modio._imgwriter.newdata.wait(2.5):
+                self._parentdevice._modio._imgwriter.newdata.clear()
+
+                if val_start != self.value:
+                    if edge == BOTH \
+                            or edge == RISING and not val_start \
+                            or edge == FALLING and val_start:
+                        return 0
+                    else:
+                        val_start = not val_start
+                if bool_timecount:
+                    flt_timecount += \
+                        self._parentdevice._modio._imgwriter._refresh
+            elif bool_timecount:
+                flt_timecount += 2.5
+
+        # Abbruchevent wurde gesetzt
+        if exitevent.is_set():
+            return 1
+
+        # RevPiModIO mainloop wurde verlassen
+        if self._parentdevice._modio._waitexit.is_set():
+            return 100
+
+        # Timeout abgelaufen
+        return 2
+
+    address = property(_get_address)
+    byteorder = property(_get_byteorder)
+    defaultvalue = property(get_defaultvalue)
+    export = property(_get_export, _set_export)
     length = property(__len__)
     name = property(__str__)
-    offset = property(_get_offset)
-    position = property(__int__)
-    producttype = property(_get_producttype)
-
-
-class Base(Device):
-    """Klasse fuer alle Base-Devices wie Core / Connect usw."""
-
-    __slots__ = ()
-
-    pass
-
+    type = property(_get_iotype)
+    value = property(get_value, set_value)
 
-class Core(Base):
-    """
-    Klasse fuer den RevPi Core.
 
-    Stellt Funktionen fuer die LEDs und den Status zur Verfuegung.
+class IntIO(IOBase):
     """
+    Klasse fuer den Zugriff auf die Daten mit Konvertierung in int.
 
-    __slots__ = "_slc_cycle", "_slc_errorcnt", "_slc_statusbyte", \
-        "_slc_temperature", "_slc_errorlimit1", "_slc_errorlimit2", \
-        "_slc_frequency", "_slc_led", "a1green", "a1red", \
-        "a2green", "a2red", "wd"
-
-    def __setattr__(self, key, value):
-        """Verhindert Ueberschreibung der LEDs."""
-        if hasattr(self, key) and key in (
-                "a1green", "a1red", "a2green", "a2red", "wd"):
-            raise AttributeError(
-                "direct assignment is not supported - use .value Attribute"
-            )
-        else:
-            object.__setattr__(self, key, value)
+    Diese Klasse erweitert die Funktion von <class 'IOBase'> um Funktionen,
+    ueber die mit <class 'int'> Werten gearbeitet werden kann. Fuer die
+    Umwandlung koennen 'Byteorder' (Default 'little') und 'signed' (Default
+    False) als Parameter gesetzt werden.
 
-    def _devconfigure(self) -> None:
-        """Core-Klasse vorbereiten."""
+    :ref: :class:`IOBase`
+    """
 
-        # Statische IO Verknüpfungen je nach Core-Variante
-        # 2 Byte = Core1.0
-        self._slc_statusbyte = slice(0, 1)
-        self._slc_led = slice(1, 2)
-
-        self._slc_cycle = None
-        self._slc_temperature = None
-        self._slc_frequency = None
-        self._slc_errorcnt = None
-        self._slc_errorlimit1 = None
-        self._slc_errorlimit2 = None
-        if self.length == 9:
-            #  9 Byte = Core1.1
-            self._slc_cycle = slice(1, 2)
-            self._slc_errorcnt = slice(2, 4)
-            self._slc_led = slice(4, 5)
-            self._slc_errorlimit1 = slice(5, 7)
-            self._slc_errorlimit2 = slice(7, 9)
-        elif self.length == 11:
-            # 11 Byte = Core1.2 / Connect
-            self._slc_cycle = slice(1, 2)
-            self._slc_errorcnt = slice(2, 4)
-            self._slc_temperature = slice(4, 5)
-            self._slc_frequency = slice(5, 6)
-            self._slc_led = slice(6, 7)
-            self._slc_errorlimit1 = slice(7, 9)
-            self._slc_errorlimit2 = slice(9, 11)
-
-        # Exportflags prüfen (Byte oder Bit)
-        lst_led = self._modio.io[self._slc_devoff][self._slc_led.start]
-        if len(lst_led) == 8:
-            exp_a1green = lst_led[0].export
-            exp_a1red = lst_led[1].export
-            exp_a2green = lst_led[2].export
-            exp_a2red = lst_led[3].export
-        else:
-            exp_a1green = lst_led[0].export
-            exp_a1red = exp_a1green
-            exp_a2green = exp_a1green
-            exp_a2red = exp_a1green
-
-        # Echte IOs erzeugen
-        self.a1green = IOBase(self, [
-            "core.a1green", 0, 1, self._slc_led.start,
-            exp_a1green, None, "LED_A1_GREEN", "0"
-        ], OUT, "little", False)
-        self.a1red = IOBase(self, [
-            "core.a1red", 0, 1, self._slc_led.start,
-            exp_a1red, None, "LED_A1_RED", "1"
-        ], OUT, "little", False)
-        self.a2green = IOBase(self, [
-            "core.a2green", 0, 1, self._slc_led.start,
-            exp_a2green, None, "LED_A2_GREEN", "2"
-        ], OUT, "little", False)
-        self.a2red = IOBase(self, [
-            "core.a2red", 0, 1, self._slc_led.start,
-            exp_a2red, None, "LED_A2_RED", "3"
-        ], OUT, "little", False)
-
-        # Watchdog einrichten (Core=soft / Connect=soft/hard)
-        self.wd = IOBase(self, [
-            "core.wd", 0, 1, self._slc_led.start,
-            False, None, "WatchDog", "7"
-        ], OUT, "little", False)
-
-    def __errorlimit(self, slc_io: slice, errorlimit: int) -> None:
-        """
-        Verwaltet das Schreiben der ErrorLimits.
-
-        :param slc_io: Byte Slice vom ErrorLimit
-        :return: Aktuellen ErrorLimit oder None wenn nicht verfuegbar
-        """
-        if 0 <= errorlimit <= 65535:
-            self._ba_devdata[slc_io] = \
-                errorlimit.to_bytes(2, byteorder="little")
-        else:
-            raise ValueError(
-                "errorlimit value must be between 0 and 65535"
-            )
+    __slots__ = ()
 
-    def _get_status(self) -> int:
+    def __int__(self):
         """
-        Gibt den RevPi Core Status zurueck.
+        Gibt IO-Wert zurueck mit Beachtung byteorder/signed.
 
-        :return: Status als <class 'int'>
+        :return: IO-Wert als <class 'int'>
         """
         return int.from_bytes(
-            self._ba_devdata[self._slc_statusbyte], byteorder="little"
+            self._parentdevice._ba_devdata[self._slc_address],
+            byteorder=self._byteorder,
+            signed=self._signed
         )
 
-    def _get_leda1(self) -> int:
-        """
-        Gibt den Zustand der LED A1 vom Core zurueck.
-
-        :return: 0=aus, 1=gruen, 2=rot
-        """
-        # 0b00000011 = 3
-        return self._ba_devdata[self._slc_led.start] & 3
-
-    def _get_leda2(self) -> int:
-        """
-        Gibt den Zustand der LED A2 vom Core zurueck.
-
-        :return: 0=aus, 1=gruen, 2=rot
-        """
-        # 0b00001100 = 12
-        return (self._ba_devdata[self._slc_led.start] & 12) >> 2
-
-    def _set_leda1(self, value: int) -> None:
-        """
-        Setzt den Zustand der LED A1 vom Core.
-
-        :param value: 0=aus, 1=gruen, 2=rot
-        """
-        if 0 <= value <= 3:
-            self.a1green(bool(value & 1))
-            self.a1red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
-
-    def _set_leda2(self, value: int) -> None:
-        """
-        Setzt den Zustand der LED A2 vom Core.
-
-        :param value: 0=aus, 1=gruen, 2=rot
-        """
-        if 0 <= value <= 3:
-            self.a2green(bool(value & 1))
-            self.a2red(bool(value & 2))
+    def __call__(self, value=None):
+        if value is None:
+            # Inline get_intvalue()
+            return int.from_bytes(
+                self._parentdevice._ba_devdata[self._slc_address],
+                byteorder=self._byteorder,
+                signed=self._signed
+            )
         else:
-            raise ValueError("led status must be between 0 and 3")
-
-    def wd_toggle(self):
-        """Toggle watchdog bit to prevent a timeout."""
-        self.wd.value = not self.wd.value
-
-    A1 = property(_get_leda1, _set_leda1)
-    A2 = property(_get_leda2, _set_leda2)
-    status = property(_get_status)
-
-    @property
-    def picontrolrunning(self) -> bool:
-        """
-        Statusbit fuer piControl-Treiber laeuft.
-
-        :return: True, wenn Treiber laeuft
-        """
-        return bool(int.from_bytes(
-            self._ba_devdata[self._slc_statusbyte], byteorder="little"
-        ) & 1)
-
-    @property
-    def unconfdevice(self) -> bool:
-        """
-        Statusbit fuer ein IO-Modul nicht mit PiCtory konfiguriert.
-
-        :return: True, wenn IO Modul nicht konfiguriert
-        """
-        return bool(int.from_bytes(
-            self._ba_devdata[self._slc_statusbyte], byteorder="little"
-        ) & 2)
-
-    @property
-    def missingdeviceorgate(self) -> bool:
-        """
-        Statusbit fuer ein IO-Modul fehlt oder piGate konfiguriert.
-
-        :return: True, wenn IO-Modul fehlt oder piGate konfiguriert
-        """
-        return bool(int.from_bytes(
-            self._ba_devdata[self._slc_statusbyte], byteorder="little"
-        ) & 4)
-
-    @property
-    def overunderflow(self) -> bool:
-        """
-        Statusbit Modul belegt mehr oder weniger Speicher als konfiguriert.
-
-        :return: True, wenn falscher Speicher belegt ist
-        """
-        return bool(int.from_bytes(
-            self._ba_devdata[self._slc_statusbyte], byteorder="little"
-        ) & 8)
-
-    @property
-    def leftgate(self) -> bool:
-        """
-        Statusbit links vom RevPi ist ein piGate Modul angeschlossen.
-
-        :return: True, wenn piGate links existiert
-        """
-        return bool(int.from_bytes(
-            self._ba_devdata[self._slc_statusbyte], byteorder="little"
-        ) & 16)
-
-    @property
-    def rightgate(self) -> bool:
-        """
-        Statusbit rechts vom RevPi ist ein piGate Modul angeschlossen.
-
-        :return: True, wenn piGate rechts existiert
-        """
-        return bool(int.from_bytes(
-            self._ba_devdata[self._slc_statusbyte], byteorder="little"
-        ) & 32)
-
-    @property
-    def iocycle(self) -> int:
-        """
-        Gibt Zykluszeit der Prozessabbildsynchronisierung zurueck.
-
-        :return: Zykluszeit in ms ( -1 wenn nicht verfuegbar)
-        """
-        return -1 if self._slc_cycle is None else int.from_bytes(
-            self._ba_devdata[self._slc_cycle], byteorder="little"
-        )
+            # Inline from set_intvalue()
+            if type(value) == int:
+                self.set_value(value.to_bytes(
+                    self._length,
+                    byteorder=self._byteorder,
+                    signed=self._signed
+                ))
+            else:
+                raise TypeError(
+                    "'{0}' need a <class 'int'> value, but {1} was given"
+                    "".format(self._name, type(value))
+                )
 
-    @property
-    def temperature(self) -> int:
+    def _get_signed(self) -> bool:
         """
-        Gibt CPU-Temperatur zurueck.
+        Ruft ab, ob der Wert Vorzeichenbehaftet behandelt werden soll.
 
-        :return: CPU-Temperatur in Celsius (-273 wenn nich verfuegbar)
+        :return: True, wenn Vorzeichenbehaftet
         """
-        return -273 if self._slc_temperature is None else int.from_bytes(
-            self._ba_devdata[self._slc_temperature], byteorder="little"
-        )
+        return self._signed
 
-    @property
-    def frequency(self) -> int:
+    def _set_byteorder(self, value: str) -> None:
         """
-        Gibt CPU Taktfrequenz zurueck.
+        Setzt Byteorder fuer <class 'int'> Umwandlung.
 
-        :return: CPU Taktfrequenz in MHz (-1 wenn nicht verfuegbar)
+        :param value: <class 'str'> 'little' or 'big'
         """
-        return -1 if self._slc_frequency is None else int.from_bytes(
-            self._ba_devdata[self._slc_frequency], byteorder="little"
-        ) * 10
+        if not (value == "little" or value == "big"):
+            raise ValueError("byteorder must be 'little' or 'big'")
+        if self._byteorder != value:
+            self._byteorder = value
+            self._defaultvalue = self._defaultvalue[::-1]
 
-    @property
-    def ioerrorcount(self) -> int:
+    def _set_signed(self, value: bool) -> None:
         """
-        Gibt Fehleranzahl auf RS485 piBridge Bus zurueck.
+        Left fest, ob der Wert Vorzeichenbehaftet behandelt werden soll.
 
-        :return: Fehleranzahl der piBridge (-1 wenn nicht verfuegbar)
+        :param value: True, wenn mit Vorzeichen behandel
         """
-        return -1 if self._slc_errorcnt is None else int.from_bytes(
-            self._ba_devdata[self._slc_errorcnt], byteorder="little"
-        )
+        if type(value) != bool:
+            raise TypeError("signed must be <class 'bool'> True or False")
+        self._signed = value
 
-    @property
-    def errorlimit1(self) -> int:
+    def get_intdefaultvalue(self) -> int:
         """
-        Gibt RS485 ErrorLimit1 Wert zurueck.
+        Gibt die Defaultvalue als <class 'int'> zurueck.
 
-        :return: Aktueller Wert fuer ErrorLimit1 (-1 wenn nicht verfuegbar)
+        :return: <class 'int'> Defaultvalue
         """
-        return -1 if self._slc_errorlimit1 is None else int.from_bytes(
-            self._ba_devdata[self._slc_errorlimit1], byteorder="little"
+        return int.from_bytes(
+            self._defaultvalue, byteorder=self._byteorder, signed=self._signed
         )
 
-    @errorlimit1.setter
-    def errorlimit1(self, value: int) -> None:
+    def get_intvalue(self) -> int:
         """
-        Setzt RS485 ErrorLimit1 auf neuen Wert.
+        Gibt IO-Wert zurueck mit Beachtung byteorder/signed.
 
-        :param value: Neuer ErrorLimit1 Wert
+        :return: IO-Wert als <class 'int'>
         """
-        if self._slc_errorlimit1 is None:
-            raise RuntimeError(
-                "selected core item in piCtory does not support errorlimit1"
-            )
-        else:
-            self.__errorlimit(self._slc_errorlimit1, value)
-
-    @property
-    def errorlimit2(self) -> int:
-        """
-        Gibt RS485 ErrorLimit2 Wert zurueck.
-
-        :return: Aktueller Wert fuer ErrorLimit2 (-1 wenn nicht verfuegbar)
-        """
-        return -1 if self._slc_errorlimit2 is None else int.from_bytes(
-            self._ba_devdata[self._slc_errorlimit2], byteorder="little"
+        return int.from_bytes(
+            self._parentdevice._ba_devdata[self._slc_address],
+            byteorder=self._byteorder,
+            signed=self._signed
         )
 
-    @errorlimit2.setter
-    def errorlimit2(self, value: int) -> None:
+    def set_intvalue(self, value: int) -> None:
         """
-        Setzt RS485 ErrorLimit2 auf neuen Wert.
+        Setzt IO mit Beachtung byteorder/signed.
 
-        :param value: Neuer ErrorLimit2 Wert
+        :param value: <class 'int'> Wert
         """
-        if self._slc_errorlimit2 is None:
-            raise RuntimeError(
-                "selected core item in piCtory does not support errorlimit2"
-            )
-        else:
-            self.__errorlimit(self._slc_errorlimit2, value)
-
-
-class Connect(Core):
-    """Klasse fuer den RevPi Connect.
-
-    Stellt Funktionen fuer die LEDs, Watchdog und den Status zur Verfuegung.
-    """
-
-    __slots__ = "__evt_wdtoggle", "__th_wdtoggle", "a3green", "a3red", \
-        "x2in", "x2out"
-
-    def __setattr__(self, key, value):
-        """Verhindert Ueberschreibung der speziellen IOs."""
-        if hasattr(self, key) and key in (
-                "a3green", "a3red", "x2in", "x2out"):
-            raise AttributeError(
-                "direct assignment is not supported - use .value Attribute"
+        if type(value) == int:
+            self.set_value(value.to_bytes(
+                self._length,
+                byteorder=self._byteorder,
+                signed=self._signed
+            ))
+        else:
+            raise TypeError(
+                "'{0}' need a <class 'int'> value, but {1} was given"
+                "".format(self._name, type(value))
             )
-        super(Connect, self).__setattr__(key, value)
-
-    def __wdtoggle(self) -> None:
-        """WD Ausgang alle 10 Sekunden automatisch toggeln."""
-        while not self.__evt_wdtoggle.wait(10):
-            self.wd.value = not self.wd.value
-
-    def _devconfigure(self) -> None:
-        """Connect-Klasse vorbereiten."""
-        super()._devconfigure()
-
-        self.__evt_wdtoggle = Event()
-        self.__th_wdtoggle = None
 
-        # Exportflags prüfen (Byte oder Bit)
-        lst_myios = self._modio.io[self._slc_devoff]
-        lst_led = lst_myios[self._slc_led.start]
-        if len(lst_led) == 8:
-            exp_a3green = lst_led[4].export
-            exp_a3red = lst_led[5].export
-            exp_x2out = lst_led[6].export
-            exp_wd = lst_led[7].export
-        else:
-            exp_a3green = lst_led[0].export
-            exp_a3red = exp_a3green
-            exp_x2out = exp_a3green
-            exp_wd = exp_a3green
-        lst_status = lst_myios[self._slc_statusbyte.start]
-        if len(lst_status) == 8:
-            exp_x2in = lst_status[6].export
-        else:
-            exp_x2in = lst_status[0].export
-
-        # Echte IOs erzeugen
-        self.a3green = IOBase(self, [
-            "core.a3green", 0, 1, self._slc_led.start,
-            exp_a3green, None, "LED_A3_GREEN", "4"
-        ], OUT, "little", False)
-        self.a3red = IOBase(self, [
-            "core.a3red", 0, 1, self._slc_led.start,
-            exp_a3red, None, "LED_A3_RED", "5"
-        ], OUT, "little", False)
+    byteorder = property(IOBase._get_byteorder, _set_byteorder)
+    defaultvalue = property(get_intdefaultvalue)
+    signed = property(_get_signed, _set_signed)
+    value = property(get_intvalue, set_intvalue)
 
-        # IO Objekte für WD und X2 in/out erzeugen
-        self.x2in = IOBase(self, [
-            "core.x2in", 0, 1, self._slc_statusbyte.start,
-            exp_x2in, None, "Connect_X2_IN", "6"
-        ], INP, "little", False)
-        self.x2out = IOBase(self, [
-            "core.x2out", 0, 1, self._slc_led.start,
-            exp_x2out, None, "Connect_X2_OUT", "6"
-        ], OUT, "little", False)
 
-        # Export hardware watchdog to use it with other systems
-        self.wd._export = int(exp_wd)  # Do this without mrk for export!
+class IntIOCounter(IntIO):
+    """Erweitert die IntIO-Klasse um die .reset() Funktion fuer Counter."""
 
-    def _get_leda3(self) -> int:
-        """
-        Gibt den Zustand der LED A3 vom Connect zurueck.
-
-        :return: 0=aus, 1=gruen, 2=rot
-        """
-        # 0b00110000 = 48
-        return (self._ba_devdata[self._slc_led.start] & 48) >> 4
+    __slots__ = ("__ioctl_arg",)
 
-    def _get_wdtoggle(self) -> bool:
+    def __init__(
+            self, counter_id,
+            parentdevice, valuelist, iotype, byteorder, signed):
         """
-        Ruft den Wert fuer Autowatchdog ab.
+        Instantiierung der IntIOCounter-Klasse.
 
-        :return: True, wenn Autowatchdog aktiv ist
+        :param counter_id: ID fuer den Counter, zu dem der IO gehoert (0-15)
+        :ref: :func:`IOBase.__init__(...)`
         """
-        return self.__th_wdtoggle is not None and self.__th_wdtoggle.is_alive()
+        if not isinstance(counter_id, int):
+            raise TypeError("counter_id must be <class 'int'>")
+        if not 0 <= counter_id <= 15:
+            raise ValueError("counter_id must be 0 - 15")
 
-    def _set_leda3(self, value: int) -> None:
-        """
-        Setzt den Zustand der LED A3 vom Connect.
+        # Deviceposition + leer + Counter_ID
+        # ID-Bits: 7|6|5|4|3|2|1|0|15|14|13|12|11|10|9|8
+        self.__ioctl_arg = \
+            parentdevice._position.to_bytes(1, "little") \
+            + b'\x00' \
+            + (1 << counter_id).to_bytes(2, "little")
 
-        :param: value 0=aus, 1=gruen, 2=rot
         """
-        if 0 <= value <= 3:
-            self.a3green(bool(value & 1))
-            self.a3red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
+        IOCTL fuellt dieses struct, welches durch padding im Speicher nach
+        uint8_t ein byte frei hat. Es muessen also 4 Byte uebergeben werden
+        wobei das Bitfield die Byteorder little hat!!!
 
-    def _set_wdtoggle(self, value: bool) -> None:
+        typedef struct SDIOResetCounterStr
+        {
+            uint8_t     i8uAddress;   // Address of module
+            uint16_t    i16uBitfield; // bitfield, if bit n is 1, reset
+        } SDIOResetCounter;
         """
-        Setzt den Wert fuer Autowatchdog.
-
-        Wird dieser Wert auf True gesetzt, wechselt im Hintergrund das noetige
-        Bit zum toggeln des Watchdogs alle 10 Sekunden zwichen True und False.
-        Dieses Bit wird bei autorefresh=True natuerlich automatisch in das
-        Prozessabbild geschrieben.
 
-        WICHTIG: Sollte autorefresh=False sein, muss zyklisch
-                 .writeprocimg() aufgerufen werden, um den Wert in das
-                 Prozessabbild zu schreiben!!!
+        # Basisklasse laden
+        super().__init__(parentdevice, valuelist, iotype, byteorder, signed)
 
-        :param value: True zum aktivieren, Fals zum beenden
-        """
-        if self._modio._monitoring:
+    def reset(self) -> None:
+        """Setzt den Counter des Inputs zurueck."""
+        if self._parentdevice._modio._monitoring:
             raise RuntimeError(
-                "can not toggle watchdog, while system is in monitoring mode"
+                "can not reset counter, while system is in monitoring mode"
             )
-        if self._modio._simulator:
+        if self._parentdevice._modio._simulator:
             raise RuntimeError(
-                "can not toggle watchdog, while system is in simulator mode"
+                "can not reset counter, while system is in simulator mode"
             )
 
-        if not value:
-            self.__evt_wdtoggle.set()
-
-        elif not self._get_wdtoggle():
-            # Watchdogtoggler erstellen
-            self.__evt_wdtoggle.clear()
-            self.__th_wdtoggle = Thread(target=self.__wdtoggle, daemon=True)
-            self.__th_wdtoggle.start()
-
-    A3 = property(_get_leda3, _set_leda3)
-    wdautotoggle = property(_get_wdtoggle, _set_wdtoggle)
-
-
-class Compact(Base):
-    """
-    Klasse fuer den RevPi Compact.
-
-    Stellt Funktionen fuer die LEDs zur Verfuegung. Auf IOs wird ueber das .io
-    Objekt zugegriffen.
-    """
-
-    __slots__ = "_slc_temperature", "_slc_frequency", "_slc_led", \
-        "a1green", "a1red", "a2green", "a2red", "wd"
-
-    def __setattr__(self, key, value):
-        """Verhindert Ueberschreibung der LEDs."""
-        if hasattr(self, key) and key in (
-                "a1green", "a1red", "a2green", "a2red", "wd"):
-            raise AttributeError(
-                "direct assignment is not supported - use .value Attribute"
-            )
-        else:
-            object.__setattr__(self, key, value)
-
-    def _devconfigure(self) -> None:
-        """Core-Klasse vorbereiten."""
-
-        # Statische IO Verknüpfungen des Compacts
-        self._slc_led = slice(23, 24)
-        self._slc_temperature = slice(0, 1)
-        self._slc_frequency = slice(1, 2)
-
-        # Exportflags prüfen (Byte oder Bit)
-        lst_led = self._modio.io[self._slc_devoff][self._slc_led.start]
-        if len(lst_led) == 8:
-            exp_a1green = lst_led[0].export
-            exp_a1red = lst_led[1].export
-            exp_a2green = lst_led[2].export
-            exp_a2red = lst_led[3].export
-        else:
-            exp_a1green = lst_led[0].export
-            exp_a1red = exp_a1green
-            exp_a2green = exp_a1green
-            exp_a2red = exp_a1green
-
-        # Echte IOs erzeugen
-        self.a1green = IOBase(self, [
-            "core.a1green", 0, 1, self._slc_led.start,
-            exp_a1green, None, "LED_A1_GREEN", "0"
-        ], OUT, "little", False)
-        self.a1red = IOBase(self, [
-            "core.a1red", 0, 1, self._slc_led.start,
-            exp_a1red, None, "LED_A1_RED", "1"
-        ], OUT, "little", False)
-        self.a2green = IOBase(self, [
-            "core.a2green", 0, 1, self._slc_led.start,
-            exp_a2green, None, "LED_A2_GREEN", "2"
-        ], OUT, "little", False)
-        self.a2red = IOBase(self, [
-            "core.a2red", 0, 1, self._slc_led.start,
-            exp_a2red, None, "LED_A2_RED", "3"
-        ], OUT, "little", False)
-
-        # Software watchdog einrichten
-        self.wd = IOBase(self, [
-            "core.wd", 0, 1, self._slc_led.start,
-            False, None, "WatchDog", "7"
-        ], OUT, "little", False)
-
-    def _get_leda1(self) -> int:
-        """
-        Gibt den Zustand der LED A1 vom Compact zurueck.
-
-        :return: 0=aus, 1=gruen, 2=rot
-        """
-        # 0b00000011 = 3
-        return self._ba_devdata[self._slc_led.start] & 3
-
-    def _get_leda2(self) -> int:
-        """
-        Gibt den Zustand der LED A2 vom Compact zurueck.
-
-        :return: 0=aus, 1=gruen, 2=rot
-        """
-        # 0b00001100 = 12
-        return (self._ba_devdata[self._slc_led.start] & 12) >> 2
+        if self._parentdevice._modio._run_on_pi:
+            # IOCTL auf dem RevPi
+            with self._parentdevice._modio._myfh_lck:
+                try:
+                    # Counter reset durchführen (Funktion K+20)
+                    ioctl(
+                        self._parentdevice._modio._myfh,
+                        19220, self.__ioctl_arg
+                    )
+                except Exception as e:
+                    self._parentdevice._modio._gotioerror("iorst", e)
+
+        elif hasattr(self._parentdevice._modio._myfh, "ioctl"):
+            # IOCTL über Netzwerk
+            with self._parentdevice._modio._myfh_lck:
+                try:
+                    self._parentdevice._modio._myfh.ioctl(
+                        19220, self.__ioctl_arg
+                    )
+                except Exception as e:
+                    self._parentdevice._modio._gotioerror("net_iorst", e)
+
+        else:
+            # IOCTL in Datei simulieren
+            try:
+                # Set value durchführen (Funktion K+20)
+                self._parentdevice._modio._simulate_ioctl(
+                    19220, self.__ioctl_arg
+                )
+            except Exception as e:
+                self._parentdevice._modio._gotioerror("file_iorst", e)
 
-    def _set_leda1(self, value: int) -> None:
-        """
-        Setzt den Zustand der LED A1 vom Compact.
 
-        :param value: 0=aus, 1=gruen, 2=rot
-        """
-        if 0 <= value <= 3:
-            self.a1green(bool(value & 1))
-            self.a1red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
+class IntIOReplaceable(IntIO):
+    """Erweitert die IntIO-Klasse um die .replace_io Funktion."""
 
-    def _set_leda2(self, value: int) -> None:
-        """
-        Setzt den Zustand der LED A2 vom Compact.
+    __slots__ = ()
 
-        :param value: 0=aus, 1=gruen, 2=rot
+    def replace_io(self, name: str, frm: str, **kwargs) -> None:
         """
-        if 0 <= value <= 3:
-            self.a2green(bool(value & 1))
-            self.a2red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
-
-    def wd_toggle(self):
-        """Toggle watchdog bit to prevent a timeout."""
-        self.wd.value = not self.wd.value
+        Ersetzt bestehenden IO mit Neuem.
 
-    A1 = property(_get_leda1, _set_leda1)
-    A2 = property(_get_leda2, _set_leda2)
+        Wenn die kwargs fuer byteorder und defaultvalue nicht angegeben werden,
+        uebernimmt das System die Daten aus dem ersetzten IO.
 
-    @property
-    def temperature(self) -> int:
-        """
-        Gibt CPU-Temperatur zurueck.
-
-        :return: CPU-Temperatur in Celsius (-273 wenn nich verfuegbar)
-        """
-        return -273 if self._slc_temperature is None else int.from_bytes(
-            self._ba_devdata[self._slc_temperature], byteorder="little"
+        Es darf nur ein einzelnes Formatzeichen 'frm' uebergeben werden. Daraus
+        wird dann die benoetigte Laenge an Bytes berechnet und der Datentyp
+        festgelegt. Moeglich sind:
+        - Bits / Bytes: ?, c, s
+        - Integer     : bB, hH, iI, lL, qQ
+        - Float       : e, f, d
+
+        Eine Ausnahme ist die Formatierung 's'. Hier koennen mehrere Bytes
+        zu einem langen IO zusammengefasst werden. Die Formatierung muss
+        '8s' fuer z.B. 8 Bytes sein - NICHT 'ssssssss'!
+
+        Wenn durch die Formatierung mehr Bytes benoetigt werden, als
+        der urspruenglige IO hat, werden die nachfolgenden IOs ebenfalls
+        verwendet und entfernt.
+
+        :param name: Name des neuen Inputs
+        :param frm: struct formatierung (1 Zeichen) oder 'ANZAHLs' z.B. '8s'
+        :param kwargs: Weitere Parameter
+
+        - bmk: interne Bezeichnung fuer IO
+        - bit: Registriert IO als <class 'bool'> am angegebenen Bit im Byte
+        - byteorder: Byteorder fuer den IO, Standardwert=little
+        - wordorder: Wordorder wird vor byteorder angewendet
+        - defaultvalue: Standardwert fuer IO
+        - event: Funktion fuer Eventhandling registrieren
+        - delay: Verzoegerung in ms zum Ausloesen wenn Wert gleich bleibt
+        - edge: Event ausfuehren bei RISING, FALLING or BOTH Wertaenderung
+        - as_thread: Fuehrt die event-Funktion als RevPiCallback-Thread aus
+        - prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
+
+        `<https://docs.python.org/3/library/struct.html#format-characters>`_
+        """
+        # StructIO erzeugen
+        io_new = StructIO(
+            self,
+            name,
+            frm,
+            **kwargs
         )
 
-    @property
-    def frequency(self) -> int:
-        """
-        Gibt CPU Taktfrequenz zurueck.
+        # StructIO in IO-Liste einfügen
+        self._parentdevice._modio.io._private_register_new_io_object(io_new)
 
-        :return: CPU Taktfrequenz in MHz (-1 wenn nicht verfuegbar)
-        """
-        return -1 if self._slc_frequency is None else int.from_bytes(
-            self._ba_devdata[self._slc_frequency], byteorder="little"
-        ) * 10
+        # Optional Event eintragen
+        reg_event = kwargs.get("event", None)
+        if reg_event is not None:
+            io_new.reg_event(
+                reg_event,
+                kwargs.get("delay", 0),
+                kwargs.get("edge", BOTH),
+                kwargs.get("as_thread", False)
+            )
 
 
-class Flat(Base):
+class StructIO(IOBase):
     """
-    Klasse fuer den RevPi Flat.
+    Klasse fuer den Zugriff auf Daten ueber ein definierten struct.
 
-    Stellt Funktionen fuer die LEDs zur Verfuegung. Auf IOs wird ueber das .io
-    Objekt zugegriffen.
+    Sie stellt ueber struct die Werte in der gewuenschten Formatierung
+    bereit. Der struct-Formatwert wird bei der Instantiierung festgelegt.
     """
 
-    __slots__ = "_slc_temperature", "_slc_frequency", "_slc_led", \
-        "_slc_switch", "_slc_dout", \
-        "a1green", "a1red", "a2green", "a2red", \
-        "a3green", "a3red", "a4green", "a4red", \
-        "a5green", "a5red", "relais", "switch", "wd"
-
-    def __setattr__(self, key, value):
-        """Verhindert Ueberschreibung der LEDs."""
-        if hasattr(self, key) and key in (
-                "a1green", "a1red", "a2green", "a2red",
-                "a3green", "a3red", "a4green", "a4red",
-                "a5green", "a5red", "relais", "switch", "wd"):
-            raise AttributeError(
-                "direct assignment is not supported - use .value Attribute"
-            )
-        else:
-            object.__setattr__(self, key, value)
-
-    def _devconfigure(self) -> None:
-        """Core-Klasse vorbereiten."""
-
-        # Statische IO Verknüpfungen des Compacts
-        self._slc_led = slice(7, 9)
-        self._slc_temperature = slice(4, 5)
-        self._slc_frequency = slice(5, 6)
-        self._slc_switch = slice(6, 7)
-        self._slc_dout = slice(11, 12)
-
-        # Exportflags prüfen (Byte oder Bit)
-        lst_led = self._modio.io[self._slc_devoff][self._slc_led.start]
-        if len(lst_led) == 8:
-            exp_a1green = lst_led[0].export
-            exp_a1red = lst_led[1].export
-            exp_a2green = lst_led[2].export
-            exp_a2red = lst_led[3].export
-            exp_a3green = lst_led[4].export
-            exp_a3red = lst_led[5].export
-            exp_a4green = lst_led[6].export
-            exp_a4red = lst_led[7].export
-
-            # Next byte
-            lst_led = self._modio.io[self._slc_devoff][self._slc_led.start + 1]
-            exp_a5green = lst_led[0].export
-            exp_a5red = lst_led[1].export
-        else:
-            exp_a1green = lst_led[0].export
-            exp_a1red = exp_a1green
-            exp_a2green = exp_a1green
-            exp_a2red = exp_a1green
-            exp_a3green = exp_a1green
-            exp_a3red = exp_a1green
-            exp_a4green = exp_a1green
-            exp_a4red = exp_a1green
-            exp_a5green = exp_a1green
-            exp_a5red = exp_a1green
-
-        # Echte IOs erzeugen
-        self.a1green = IOBase(self, [
-            "core.a1green", 0, 1, self._slc_led.start,
-            exp_a1green, None, "LED_A1_GREEN", "0"
-        ], OUT, "little", False)
-        self.a1red = IOBase(self, [
-            "core.a1red", 0, 1, self._slc_led.start,
-            exp_a1red, None, "LED_A1_RED", "1"
-        ], OUT, "little", False)
-        self.a2green = IOBase(self, [
-            "core.a2green", 0, 1, self._slc_led.start,
-            exp_a2green, None, "LED_A2_GREEN", "2"
-        ], OUT, "little", False)
-        self.a2red = IOBase(self, [
-            "core.a2red", 0, 1, self._slc_led.start,
-            exp_a2red, None, "LED_A2_RED", "3"
-        ], OUT, "little", False)
-        self.a3green = IOBase(self, [
-            "core.a3green", 0, 1, self._slc_led.start,
-            exp_a3green, None, "LED_A3_GREEN", "4"
-        ], OUT, "little", False)
-        self.a3red = IOBase(self, [
-            "core.a3red", 0, 1, self._slc_led.start,
-            exp_a3red, None, "LED_A3_RED", "5"
-        ], OUT, "little", False)
-        self.a4green = IOBase(self, [
-            "core.a4green", 0, 1, self._slc_led.start,
-            exp_a4green, None, "LED_A4_GREEN", "6"
-        ], OUT, "little", False)
-        self.a4red = IOBase(self, [
-            "core.a4red", 0, 1, self._slc_led.start,
-            exp_a4red, None, "LED_A4_RED", "7"
-        ], OUT, "little", False)
-        self.a5green = IOBase(self, [
-            "core.a5green", 0, 1, self._slc_led.start,
-            exp_a5green, None, "LED_A5_GREEN", "8"
-        ], OUT, "little", False)
-        self.a5red = IOBase(self, [
-            "core.a5red", 0, 1, self._slc_led.start,
-            exp_a5red, None, "LED_A5_RED", "9"
-        ], OUT, "little", False)
-
-        # Real IO for switch
-        lst_io = self._modio.io[self._slc_devoff][self._slc_switch.start]
-        exp_io = lst_io[0].export
-        self.switch = IOBase(self, [
-            "flat.switch", 0, 1, self._slc_switch.start,
-            exp_io, None, "Flat_Switch", "0"
-        ], INP, "little", False)
-
-        # Real IO for relais
-        lst_io = self._modio.io[self._slc_devoff][self._slc_dout.start]
-        exp_io = lst_io[0].export
-        self.relais = IOBase(self, [
-            "flat.relais", 0, 1, self._slc_dout.start,
-            exp_io, None, "Flat_Relais", "0"
-        ], OUT, "little", False)
-
-        # Software watchdog einrichten
-        self.wd = IOBase(self, [
-            "core.wd", 0, 1, self._slc_led.start,
-            False, None, "WatchDog", "15"
-        ], OUT, "little", False)
-
-    def _get_leda1(self) -> int:
-        """
-        Get value of LED A1 from RevPi Flat device.
-
-        :return: 0=off, 1=green, 2=red
-        """
-        return self._ba_devdata[self._slc_led.start] & 0b11
-
-    def _get_leda2(self) -> int:
-        """
-        Get value of LED A2 from RevPi Flat device.
-
-        :return: 0=off, 1=green, 2=red
-        """
-        return (self._ba_devdata[self._slc_led.start] & 0b1100) >> 2
-
-    def _get_leda3(self) -> int:
-        """
-        Get value of LED A3 from RevPi Flat device.
-
-        :return: 0=off, 1=green, 2=red
-        """
-        return (self._ba_devdata[self._slc_led.start] & 0b110000) >> 4
-
-    def _get_leda4(self) -> int:
-        """
-        Get value of LED A4 from RevPi Flat device.
-
-        :return: 0=off, 1=green, 2=red
-        """
-        return (self._ba_devdata[self._slc_led.start] & 0b11000000) >> 6
-
-    def _get_leda5(self) -> int:
-        """
-        Get value of LED A5 from RevPi Flat device.
-
-        :return: 0=off, 1=green, 2=red
-        """
-        return self._ba_devdata[self._slc_led.start + 1] & 0b11
+    __slots__ = "__frm", "_parentio_address", "_parentio_defaultvalue", \
+        "_parentio_length", "_parentio_name", "_wordorder"
 
-    def _set_leda1(self, value: int) -> None:
+    def __init__(self, parentio, name: str, frm: str, **kwargs):
         """
-        Set LED A1 on RevPi Flat device.
+        Erstellt einen IO mit struct-Formatierung.
 
-        :param value: 0=off, 1=green, 2=red
-        """
-        if 0 <= value <= 3:
-            self.a1green(bool(value & 1))
-            self.a1red(bool(value & 2))
+        :param parentio: ParentIO Objekt, welches ersetzt wird
+        :param name: Name des neuen IO
+        :param frm: struct formatierung (1 Zeichen) oder 'ANZAHLs' z.B. '8s'
+        :param kwargs: Weitere Parameter:
+            - bmk: Bezeichnung fuer IO
+            - bit: Registriert IO als <class 'bool'> am angegebenen Bit im Byte
+            - byteorder: Byteorder fuer IO, Standardwert vom ersetzten IO
+            - wordorder: Wordorder wird vor byteorder angewendet
+            - defaultvalue: Standardwert fuer IO, Standard vom ersetzten IO
+        """
+        # Structformatierung prüfen
+        regex = rematch("^([0-9]*s|[cbB?hHiIlLqQefd])$", frm)
+
+        if regex is not None:
+            # Byteorder prüfen und übernehmen
+            byteorder = kwargs.get("byteorder", parentio._byteorder)
+            if byteorder not in ("little", "big"):
+                raise ValueError("byteorder must be 'little' or 'big'")
+            bofrm = "<" if byteorder == "little" else ">"
+            self._wordorder = kwargs.get("wordorder", None)
+
+            # Namen des parent fuer export merken
+            self._parentio_name = parentio._name
+
+            if frm == "?":
+                if self._wordorder:
+                    raise ValueError(
+                        "you can not use wordorder for bit based ios"
+                    )
+                bitaddress = kwargs.get("bit", 0)
+                max_bits = parentio._length * 8
+                if not (0 <= bitaddress < max_bits):
+                    raise ValueError(
+                        "bitaddress must be a value between 0 and {0}"
+                        "".format(max_bits - 1)
+                    )
+                bitlength = 1
+
+                # Bitweise Ersetzung erfordert diese Informationen zusätzlich
+                if parentio._byteorder == byteorder:
+                    self._parentio_defaultvalue = parentio._defaultvalue
+                else:
+                    self._parentio_defaultvalue = parentio._defaultvalue[::-1]
+                self._parentio_address = parentio.address
+                self._parentio_length = parentio._length
+            else:
+                byte_length = struct.calcsize(bofrm + frm)
+                bitaddress = ""
+                bitlength = byte_length * 8
+                self._parentio_address = None
+                self._parentio_defaultvalue = None
+                self._parentio_length = None
+                if self._wordorder:
+                    if self._wordorder not in ("little", "big"):
+                        raise ValueError("wordorder must be 'little' or 'big'")
+                    if byte_length % 2 != 0:
+                        raise ValueError(
+                            "the byte length of new io must must be even to "
+                            "use wordorder"
+                        )
+
+            # [name,default,anzbits,adressbyte,export,adressid,bmk,bitaddress]
+            valuelist = [
+                name,
+                # Darf nur bei StructIO None sein, wird nur dann berechnet
+                kwargs.get("defaultvalue", None),
+                bitlength,
+                parentio._slc_address.start,
+                False,
+                str(parentio._slc_address.start).rjust(4, "0"),
+                kwargs.get("bmk", ""),
+                bitaddress
+            ]
         else:
-            raise ValueError("led status must be between 0 and 3")
+            raise ValueError(
+                "parameter frm has to be a single sign from [cbB?hHiIlLqQefd] "
+                "or 'COUNTs' e.g. '8s'"
+            )
 
-    def _set_leda2(self, value: int) -> None:
-        """
-        Set LED A2 on RevPi Flat device.
+        # Basisklasse instantiieren
+        super().__init__(
+            parentio._parentdevice,
+            valuelist,
+            parentio._iotype,
+            byteorder,
+            frm == frm.lower()
+        )
+        self.__frm = bofrm + frm
+        if "export" in kwargs:
+            # Use export property to remember given value for export
+            self.export = kwargs["export"]
+        else:
+            # User could change parent IO settings before replace to force
+            # export, so use parent settings for the new IO
+            self._export = parentio._export
+
+        # Platz für neuen IO prüfen
+        if not (self._slc_address.start >=
+                parentio._parentdevice._dict_slc[parentio._iotype].start and
+                self._slc_address.stop <=
+                parentio._parentdevice._dict_slc[parentio._iotype].stop):
+            raise BufferError(
+                "registered value does not fit process image scope"
+            )
 
-        :param value: 0=off, 1=green, 2=red
-        """
-        if 0 <= value <= 3:
-            self.a2green(bool(value & 1))
-            self.a2red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
+    def __call__(self, value=None):
+        if value is None:
+            # Inline get_structdefaultvalue()
+            if self._bitshift:
+                return self.get_value()
+            if self._wordorder == "little" and self._length > 2:
+                return struct.unpack(
+                    self.__frm,
+                    self._swap_word_order(self.get_value()),
+                )[0]
+            return struct.unpack(self.__frm, self.get_value())[0]
+        else:
+            # Inline set_structvalue()
+            if self._bitshift:
+                self.set_value(value)
+            elif self._wordorder == "little" and self._length > 2:
+                self.set_value(
+                    self._swap_word_order(struct.pack(self.__frm, value))
+                )
+            else:
+                self.set_value(struct.pack(self.__frm, value))
 
-    def _set_leda3(self, value: int) -> None:
+    def _get_frm(self) -> str:
         """
-        Set LED A3 on RevPi Flat device.
+        Ruft die struct Formatierung ab.
 
-        :param value: 0=off, 1=green, 2=red
+        :return: struct Formatierung
         """
-        if 0 <= value <= 3:
-            self.a3green(bool(value & 1))
-            self.a3red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
+        return self.__frm[1:]
 
-    def _set_leda4(self, value: int) -> None:
+    def _get_signed(self) -> bool:
         """
-        Set LED A4 on RevPi Flat device.
+        Ruft ab, ob der Wert Vorzeichenbehaftet behandelt werden soll.
 
-        :param value: 0=off, 1=green, 2=red
+        :return: True, wenn Vorzeichenbehaftet
         """
-        if 0 <= value <= 3:
-            self.a4green(bool(value & 1))
-            self.a4red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
+        return self._signed
 
-    def _set_leda5(self, value: int) -> None:
+    @staticmethod
+    def _swap_word_order(bytes_to_swap) -> bytes:
         """
-        Set LED A5 on RevPi Flat device.
+        Swap word order of given bytes.
 
-        :param value: 0=off, 1=green, 2=red
+        :param bytes_to_swap: Already length checked bytes to swap words
+        :return: Bytes with swapped word order
         """
-        if 0 <= value <= 3:
-            self.a5green(bool(value & 1))
-            self.a5red(bool(value & 2))
-        else:
-            raise ValueError("led status must be between 0 and 3")
-
-    def wd_toggle(self):
-        """Toggle watchdog bit to prevent a timeout."""
-        self.wd.value = not self.wd.value
+        array_length = len(bytes_to_swap)
+        swap_array = bytearray(bytes_to_swap)
+        for i in range(0, array_length // 2, 2):
+            swap_array[-i - 2:array_length - i], swap_array[i:i + 2] = \
+                swap_array[i:i + 2], swap_array[-i - 2:array_length - i]
+        return bytes(swap_array)
 
-    A1 = property(_get_leda1, _set_leda1)
-    A2 = property(_get_leda2, _set_leda2)
-    A3 = property(_get_leda3, _set_leda3)
-    A4 = property(_get_leda4, _set_leda4)
-    A5 = property(_get_leda5, _set_leda5)
-
-    @property
-    def temperature(self) -> int:
+    def get_structdefaultvalue(self):
         """
-        Gibt CPU-Temperatur zurueck.
+        Gibt die Defaultvalue mit struct Formatierung zurueck.
 
-        :return: CPU-Temperatur in Celsius (-273 wenn nich verfuegbar)
+        :return: Defaultvalue vom Typ der struct-Formatierung
         """
-        return -273 if self._slc_temperature is None else int.from_bytes(
-            self._ba_devdata[self._slc_temperature], byteorder="little"
-        )
+        if self._bitshift:
+            return self._defaultvalue
+        if self._wordorder == "little" and self._length > 2:
+            return struct.unpack(
+                self.__frm,
+                self._swap_word_order(self._defaultvalue),
+            )[0]
+        return struct.unpack(self.__frm, self._defaultvalue)[0]
 
-    @property
-    def frequency(self) -> int:
+    def get_wordorder(self) -> str:
         """
-        Gibt CPU Taktfrequenz zurueck.
+        Gibt die wordorder für diesen IO zurück.
 
-        :return: CPU Taktfrequenz in MHz (-1 wenn nicht verfuegbar)
+        :return: "little", "big" or "ignored"
         """
-        return -1 if self._slc_frequency is None else int.from_bytes(
-            self._ba_devdata[self._slc_frequency], byteorder="little"
-        ) * 10
-
+        return self._wordorder or "ignored"
 
-class DioModule(Device):
-    """Stellt ein DIO / DI / DO Modul dar."""
-
-    __slots__ = "_lst_counter"
-
-    def __init__(self, parentmodio, dict_device, simulator=False):
+    def get_structvalue(self):
         """
-        Erweitert Device-Klasse zum Erkennen von IntIOCounter.
+        Gibt den Wert mit struct Formatierung zurueck.
 
-        :rev: :func:`Device.__init__()`
+        :return: Wert vom Typ der struct-Formatierung
         """
-        # Stringliste der Byteadressen (alle Module sind gleich)
-        self._lst_counter = list(map(str, range(6, 70, 4)))
-
-        # Basisklasse laden
-        super().__init__(parentmodio, dict_device, simulator=simulator)
-
+        if self._bitshift:
+            return self.get_value()
+        if self._wordorder == "little" and self._length > 2:
+            return struct.unpack(
+                self.__frm,
+                self._swap_word_order(self.get_value()),
+            )[0]
+        return struct.unpack(self.__frm, self.get_value())[0]
 
-class Gateway(Device):
-    """
-    Klasse fuer die RevPi Gateway-Devices.
-
-    Stellt neben den Funktionen von RevPiDevice weitere Funktionen fuer die
-    Gateways bereit. IOs auf diesem Device stellen die replace_io Funktion
-    zur verfuegung, ueber die eigene IOs definiert werden, die ein
-    RevPiStructIO-Objekt abbilden.
-    Dieser IO-Typ kann Werte ueber mehrere Bytes verarbeiten und zurueckgeben.
-
-    :ref: :func:`revpimodio2.io.IntIOReplaceable.replace_io()`
-    """
-
-    __slots__ = "_dict_slc"
-
-    def __init__(self, parent, dict_device, simulator=False):
+    def set_structvalue(self, value):
         """
-        Erweitert Device-Klasse um get_rawbytes-Funktionen.
+        Setzt den Wert mit struct Formatierung.
 
-        :ref: :func:`Device.__init__()`
+        :param value: Wert vom Typ der struct-Formatierung
         """
-        super().__init__(parent, dict_device, simulator)
-
-        self._dict_slc = {
-            INP: self._slc_inp,
-            OUT: self._slc_out,
-            MEM: self._slc_mem
-        }
-
-    def get_rawbytes(self) -> bytes:
-        """
-        Gibt die Bytes aus, die dieses Device verwendet.
+        if self._bitshift:
+            self.set_value(value)
+        elif self._wordorder == "little" and self._length > 2:
+            self.set_value(
+                self._swap_word_order(struct.pack(self.__frm, value))
+            )
+        else:
+            self.set_value(struct.pack(self.__frm, value))
 
-        :return: <class 'bytes'> des Devices
-        """
-        return bytes(self._ba_devdata)
+    defaultvalue = property(get_structdefaultvalue)
+    frm = property(_get_frm)
+    signed = property(_get_signed)
+    value = property(get_structvalue, set_structvalue)
+    wordorder = property(get_wordorder)
 
 
-class Virtual(Gateway):
+class MemIO(IOBase):
     """
-    Klasse fuer die RevPi Virtual-Devices.
-
-    Stellt die selben Funktionen wie Gateway zur Verfuegung. Es koennen
-    ueber die reg_*-Funktionen eigene IOs definiert werden, die ein
-    RevPiStructIO-Objekt abbilden.
-    Dieser IO-Typ kann Werte ueber mehrere Bytes verarbeiten und zurueckgeben.
+    Erstellt einen IO für die Memory Werte in piCtory.
 
-    :ref: :func:`Gateway`
+    Dieser Typ ist nur für lesenden Zugriff vorgesehen und kann verschiedene
+    Datentypen über .value zurückgeben. Damit hat man nun auch Zugriff
+    auf Strings, welche in piCtory vergeben werden.
     """
 
-    __slots__ = ()
-
-    def writeinputdefaults(self):
-        """
-        Schreibt fuer ein virtuelles Device piCtory Defaultinputwerte.
+    def get_variantvalue(self):
+        val = bytes(self._defaultvalue)
 
-        Sollten in piCtory Defaultwerte fuer Inputs eines virtuellen Devices
-        angegeben sein, werden diese nur beim Systemstart oder einem piControl
-        Reset gesetzt. Sollte danach das Prozessabbild mit NULL ueberschrieben,
-        gehen diese Werte verloren.
-        Diese Funktion kann nur auf virtuelle Devices angewendet werden!
+        if self._bitlength > 64:
+            # STRING
+            try:
+                val = val.strip(b'\x00').decode()
+            except Exception:
+                pass
+            return val
 
-        :return: True, wenn Arbeiten am virtuellen Device erfolgreich waren
-        """
-        if self._modio._monitoring:
-            raise RuntimeError(
-                "can not write process image, while system is in monitoring "
-                "mode"
-            )
-
-        workokay = True
-        self._filelock.acquire()
-
-        for io in self.get_inputs():
-            self._ba_devdata[io._slc_address] = io._defaultvalue
-
-        # Inputs auf Bus schreiben
-        self._modio._myfh_lck.acquire()
-        try:
-            self._modio._myfh.seek(self._slc_inpoff.start)
-            self._modio._myfh.write(self._ba_devdata[self._slc_inp])
-            if self._modio._buffedwrite:
-                self._modio._myfh.flush()
-        except IOError as e:
-            self._modio._gotioerror("write_inp_def", e)
-            workokay = False
-        finally:
-            self._modio._myfh_lck.release()
+        else:
+            # INT
+            return int.from_bytes(val, self._byteorder, signed=self._signed)
 
-        self._filelock.release()
-        return workokay
+    defaultvalue = property(get_variantvalue)
+    value = property(get_variantvalue)
```

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/helper.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/helper.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/io.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/modio.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,1436 +1,1476 @@
 # -*- coding: utf-8 -*-
-"""RevPiModIO Modul fuer die Verwaltung der IOs."""
+"""RevPiModIO Hauptklasse fuer piControl0 Zugriff."""
 __author__ = "Sven Sager"
 __copyright__ = "Copyright (C) 2023 Sven Sager"
 __license__ = "LGPLv2"
 
-import struct
-from re import match as rematch
-from threading import Event
+import warnings
+from collections import namedtuple
+from configparser import ConfigParser
+from json import load as jload
+from multiprocessing import cpu_count
+from os import F_OK, R_OK, access
+from os import stat as osstat
+from queue import Empty
+from signal import SIGINT, SIGTERM, SIG_DFL, signal
+from stat import S_ISCHR
+from threading import Event, Lock, Thread
+from timeit import default_timer
+
+from . import app as appmodule
+from . import device as devicemodule
+from . import helper as helpermodule
+from . import summary as summarymodule
+from ._internal import acheck, RISING, FALLING, BOTH
+from .errors import DeviceNotFoundError
+from .io import IOList
+from .io import StructIO
+from .pictory import DeviceType, ProductType
 
-from ._internal import consttostr, RISING, FALLING, BOTH, INP, OUT, \
-    MEM, PROCESS_IMAGE_SIZE
+DevSelect = namedtuple("DevSelect", ["type", "other_device_key", "values"])
+"""Leave type, key empty for auto search name and position depending on type in values."""
 
-try:
-    # Funktioniert nur auf Unix
-    from fcntl import ioctl
-except Exception:
-    ioctl = None
 
+class RevPiModIO(object):
+    """
+    Klasse fuer die Verwaltung der piCtory Konfiguration.
 
-class IOEvent(object):
-    """Basisklasse fuer IO-Events."""
-
-    __slots__ = "as_thread", "delay", "edge", "func", "overwrite", "prefire"
-
-    def __init__(self, func, edge, as_thread, delay, overwrite, prefire):
-        """Init IOEvent class."""
-        self.as_thread = as_thread
-        self.delay = delay
-        self.edge = edge
-        self.func = func
-        self.overwrite = overwrite
-        self.prefire = prefire
+    Diese Klasse uebernimmt die gesamte Konfiguration aus piCtory und
+    laedt die Devices und IOs. Sie uebernimmt die exklusive Verwaltung des
+    Prozessabbilds und stellt sicher, dass die Daten synchron sind.
+    Sollten nur einzelne Devices gesteuert werden, verwendet man
+    RevPiModIOSelected() und uebergibt bei Instantiierung eine Liste mit
+    Device Positionen oder Device Namen.
+    """
 
+    __slots__ = "__cleanupfunc", \
+        "_autorefresh", "_buffedwrite", "_configrsc", "_debug", "_devselect", \
+        "_exit", "_exit_level", "_imgwriter", "_ioerror", \
+        "_length", "_looprunning", "_lst_devselect", "_lst_refresh", \
+        "_lst_shared", \
+        "_maxioerrors", "_monitoring", "_myfh", "_myfh_lck", \
+        "_procimg", "_replace_io_file", "_run_on_pi", \
+        "_set_device_based_cycle_time", "_simulator", "_shared_procimg", \
+        "_syncoutputs", "_th_mainloop", "_waitexit", \
+        "app", "core", "device", "exitsignal", "io", "summary"
 
-class IOList(object):
-    """Basisklasse fuer direkten Zugriff auf IO Objekte."""
+    def __init__(
+            self, autorefresh=False, monitoring=False, syncoutputs=True,
+            procimg=None, configrsc=None, simulator=False, debug=True,
+            replace_io_file=None, shared_procimg=False, direct_output=False):
+        """
+        Instantiiert die Grundfunktionen.
+
+        :param autorefresh: Wenn True, alle Devices zu autorefresh hinzufuegen
+        :param monitoring: In- und Outputs werden gelesen, niemals geschrieben
+        :param syncoutputs: Aktuell gesetzte Outputs vom Prozessabbild einlesen
+        :param procimg: Abweichender Pfad zum Prozessabbild
+        :param configrsc: Abweichender Pfad zur piCtory Konfigurationsdatei
+        :param simulator: Laedt das Modul als Simulator und vertauscht IOs
+        :param debug: Gibt alle Warnungen inkl. Zyklusprobleme aus
+        :param replace_io_file: Replace IO Konfiguration aus Datei laden
+        :param shared_procimg: Share process image with other processes, this
+                               could be insecure for automation
+        :param direct_output: Deprecated, use shared_procimg
+        """
+        # Parameterprüfung
+        acheck(
+            bool, autorefresh=autorefresh, monitoring=monitoring,
+            syncoutputs=syncoutputs, simulator=simulator, debug=debug,
+            shared_procimg=shared_procimg, direct_output=direct_output
+        )
+        acheck(
+            str, procimg_noneok=procimg, configrsc_noneok=configrsc,
+            replace_io_file_noneok=replace_io_file
+        )
 
-    def __init__(self):
-        """Init IOList class."""
-        self.__dict_iobyte = {k: [] for k in range(PROCESS_IMAGE_SIZE)}
-        self.__dict_iorefname = {}
+        # TODO: Remove in next release
+        if direct_output:
+            warnings.warn(DeprecationWarning(
+                "direct_output is deprecated - use shared_procimg instead!"
+            ))
 
-    def __contains__(self, key):
-        """
-        Prueft ob IO existiert.
+        self._autorefresh = autorefresh
+        self._configrsc = configrsc
+        self._monitoring = monitoring
+        self._procimg = "/dev/piControl0" if procimg is None else procimg
+        self._set_device_based_cycle_time = True
+        self._simulator = simulator
+        self._shared_procimg = shared_procimg or direct_output
+        self._syncoutputs = syncoutputs
+
+        # TODO: bei simulator und procimg prüfen ob datei existiert / anlegen?
+
+        # Private Variablen
+        self.__cleanupfunc = None
+        self._buffedwrite = False
+        self._debug = 1
+        self._devselect = DevSelect(DeviceType.IGNORED, "", ())
+        self._exit = Event()
+        self._exit_level = 0
+        self._imgwriter = None
+        self._ioerror = 0
+        self._length = 0
+        self._looprunning = False
+        self._lst_refresh = []
+        self._lst_shared = []
+        self._maxioerrors = 0
+        self._myfh = None
+        self._myfh_lck = Lock()
+        self._replace_io_file = replace_io_file
+        self._th_mainloop = None
+        self._waitexit = Event()
+
+        # Modulvariablen
+        self.core = None
+
+        # piCtory Klassen
+        self.app = None
+        self.device = None
+        self.io = None
+        self.summary = None
+
+        # Event für Benutzeraktionen
+        self.exitsignal = Event()
+
+        # Wert über setter setzen
+        self.debug = debug
+
+        try:
+            self._run_on_pi = S_ISCHR(osstat(self._procimg).st_mode)
+        except Exception:
+            self._run_on_pi = False
+
+        # Nur Konfigurieren, wenn nicht vererbt
+        if type(self) == RevPiModIO:
+            self._configure(self.get_jconfigrsc())
+
+    def __del__(self):
+        """Zerstoert alle Klassen um aufzuraeumen."""
+        if hasattr(self, "_exit"):
+            self.exit(full=True)
+            if self._myfh is not None:
+                self._myfh.close()
+
+    def __evt_exit(self, signum, sigframe) -> None:
+        """
+        Eventhandler fuer Programmende.
+
+        :param signum: Signalnummer
+        :param sigframe: Signalframe
+        """
+        signal(SIGINT, SIG_DFL)
+        signal(SIGTERM, SIG_DFL)
+        self._exit_level |= 4
+        self.exit(full=True)
+
+    def __exit_jobs(self):
+        """Shutdown sub systems."""
+        if self._exit_level & 1:
+            # Nach Ausführung kann System weiter verwendet werden
+            self._exit_level ^= 1
+
+            # ProcimgWriter beenden und darauf warten
+            if self._imgwriter is not None and self._imgwriter.is_alive():
+                self._imgwriter.stop()
+                self._imgwriter.join(2.5)
+
+            # Alle Devices aus Autorefresh entfernen
+            while len(self._lst_refresh) > 0:
+                dev = self._lst_refresh.pop()
+                dev._selfupdate = False
+                if not self._monitoring:
+                    self.writeprocimg(dev)
+
+        # Execute clean up function
+        if self._exit_level & 4 and self.__cleanupfunc is not None:
+            self._exit_level ^= 4
+            self.readprocimg()
+            self.__cleanupfunc()
+            if not self._monitoring:
+                self.writeprocimg()
+
+        if self._exit_level & 2:
+            self._myfh.close()
+            self.app = None
+            self.core = None
+            self.device = None
+            self.io = None
+            self.summary = None
+
+    def _configure(self, jconfigrsc: dict) -> None:
+        """
+        Verarbeitet die piCtory Konfigurationsdatei.
+
+        :param jconfigrsc: Data to build IOs as <class 'dict'> of JSON
+        """
+        # Filehandler konfigurieren, wenn er noch nicht existiert
+        if self._myfh is None:
+            self._myfh = self._create_myfh()
+
+        # App Klasse instantiieren
+        self.app = appmodule.App(jconfigrsc["App"])
+
+        # Apply device filter
+        if self._devselect.values:
+
+            # Check for supported types in values
+            for dev in self._devselect.values:
+                if type(dev) not in (int, str):
+                    raise ValueError(
+                        "need device position as <class 'int'> or "
+                        "device name as <class 'str'>"
+                    )
 
-        :param key: IO-Name <class 'str'> oder Bytenummer <class 'int'>
-        :return: True, wenn IO vorhanden / Byte belegt
-        """
-        if type(key) == int:
-            return len(self.__dict_iobyte.get(key, [])) > 0
-        else:
-            return hasattr(self, key) and type(getattr(self, key)) != DeadIO
+            lst_devices = []
+            for dev in jconfigrsc["Devices"]:
+                if self._devselect.type and self._devselect.type != dev["type"]:
+                    continue
+                if self._devselect.other_device_key:
+                    key_value = str(dev[self._devselect.other_device_key])
+                    if key_value not in self._devselect.values:
+                        # The list is always filled with <class 'str'>
+                        continue
+                else:
+                    # Auto search depending of value item type
+                    if not (dev["name"] in self._devselect.values
+                            or int(dev["position"]) in self._devselect.values):
+                        continue
+
+                lst_devices.append(dev)
+        else:
+            # Devices aus JSON übernehmen
+            lst_devices = jconfigrsc["Devices"]
+
+        # Device und IO Klassen anlegen
+        self.device = devicemodule.DeviceList()
+        self.io = IOList()
+
+        # Devices initialisieren
+        err_names_check = {}
+        for device in sorted(lst_devices, key=lambda x: x["offset"]):
+
+            # VDev alter piCtory Versionen auf KUNBUS-Standard ändern
+            if device["position"] == "adap.":
+                device["position"] = 64
+                while device["position"] in self.device:
+                    device["position"] += 1
+
+            if device["type"] == DeviceType.BASE:
+                # Basedevices
+                pt = int(device["productType"])
+                if pt == ProductType.REVPI_CORE:
+                    # RevPi Core
+                    dev_new = devicemodule.Core(
+                        self, device, simulator=self._simulator
+                    )
+                    self.core = dev_new
+                elif pt == ProductType.REVPI_CONNECT:
+                    # RevPi Connect
+                    dev_new = devicemodule.Connect(
+                        self, device, simulator=self._simulator
+                    )
+                    self.core = dev_new
+                elif pt == ProductType.REVPI_CONNECT_4:
+                    # RevPi Connect 4
+                    dev_new = devicemodule.Connect4(
+                        self, device, simulator=self._simulator
+                    )
+                    self.core = dev_new
+                elif pt == ProductType.REVPI_COMPACT:
+                    # RevPi Compact
+                    dev_new = devicemodule.Compact(
+                        self, device, simulator=self._simulator
+                    )
+                    self.core = dev_new
+                elif pt == ProductType.REVPI_FLAT:
+                    # RevPi Flat
+                    dev_new = devicemodule.Flat(
+                        self, device, simulator=self._simulator
+                    )
+                    self.core = dev_new
+                else:
+                    # Base immer als Fallback verwenden
+                    dev_new = devicemodule.Base(
+                        self, device, simulator=self._simulator
+                    )
+            elif device["type"] == DeviceType.LEFT_RIGHT:
+                # IOs
+                pt = int(device["productType"])
+                if pt == ProductType.DIO \
+                        or pt == ProductType.DI \
+                        or pt == ProductType.DO:
+                    # DIO / DI / DO
+                    dev_new = devicemodule.DioModule(
+                        self, device, simulator=self._simulator
+                    )
+                else:
+                    # Alle anderen IO-Devices
+                    dev_new = devicemodule.Device(
+                        self, device, simulator=self._simulator
+                    )
+            elif device["type"] == DeviceType.VIRTUAL:
+                # Virtuals
+                dev_new = devicemodule.Virtual(
+                    self, device, simulator=self._simulator
+                )
+            elif device["type"] == DeviceType.EDGE:
+                # Gateways
+                dev_new = devicemodule.Gateway(
+                    self, device, simulator=self._simulator
+                )
+            elif device["type"] == DeviceType.RIGHT:
+                # Connectdevice
+                dev_new = None
+            else:
+                # Device-Type nicht gefunden
+                warnings.warn(
+                    "device type '{0}' on position {1} unknown"
+                    "".format(device["type"], device["position"]),
+                    Warning
+                )
+                dev_new = None
 
-    def __delattr__(self, key):
-        """
-        Entfernt angegebenen IO.
+            if dev_new is not None:
+                # Offset prüfen, muss mit Länge übereinstimmen
+                if self._length < dev_new.offset:
+                    self._length = dev_new.offset
+
+                self._length += dev_new.length
+
+                # Build dict with device name and positions and check later
+                if dev_new.name not in err_names_check:
+                    err_names_check[dev_new.name] = []
+                err_names_check[dev_new.name].append(str(dev_new.position))
+
+                # DeviceList für direkten Zugriff aufbauen
+                setattr(self.device, dev_new.name, dev_new)
+
+        # Check equal device names and destroy name attribute of device class
+        for check_dev in err_names_check:
+            if len(err_names_check[check_dev]) == 1:
+                continue
+            self.device.__delattr__(check_dev, False)
+            warnings.warn(
+                "equal device name '{0}' in pictory configuration. you can "
+                "access this devices by position number .device[{1}] only!"
+                "".format(check_dev, "|".join(err_names_check[check_dev])),
+                Warning
+            )
+
+        # ImgWriter erstellen
+        self._imgwriter = helpermodule.ProcimgWriter(self)
+
+        if self._set_device_based_cycle_time:
+            # Refreshzeit CM1 25 Hz / CM3 50 Hz
+            self._imgwriter.refresh = 20 if cpu_count() > 1 else 40
+
+        # Aktuellen Outputstatus von procimg einlesen
+        if self._syncoutputs:
+            self.syncoutputs()
+
+        # Für RS485 errors am core defaults laden sollte procimg NULL sein
+        if isinstance(self.core, devicemodule.Core) and \
+                not (self._monitoring or self._simulator):
+            if self.core._slc_errorlimit1 is not None:
+                io = self.io[
+                    self.core.offset + self.core._slc_errorlimit1.start
+                    ][0]
+                io.set_value(io._defaultvalue)
+            if self.core._slc_errorlimit2 is not None:
+                io = self.io[
+                    self.core.offset + self.core._slc_errorlimit2.start
+                    ][0]
+                io.set_value(io._defaultvalue)
+
+            # RS485 errors schreiben
+            self.writeprocimg(self.core)
+
+        # Set replace IO before autostart to prevent cycle time exhausting
+        self._configure_replace_io(self._get_cpreplaceio())
+
+        # Optional ins autorefresh aufnehmen
+        if self._autorefresh:
+            self.autorefresh_all()
+
+        # Summary Klasse instantiieren
+        self.summary = summarymodule.Summary(jconfigrsc["Summary"])
+
+    def _configure_replace_io(self, creplaceio: ConfigParser) -> None:
+        """
+        Importiert ersetzte IOs in diese Instanz.
+
+        Importiert ersetzte IOs, welche vorher mit .export_replaced_ios(...)
+        in eine Datei exportiert worden sind. Diese IOs werden in dieser
+        Instanz wiederhergestellt.
+
+        :param creplaceio: Data to replace ios as <class 'ConfigParser'>
+        """
+        for io in creplaceio:
+            if io == "DEFAULT":
+                continue
+
+            # IO prüfen
+            parentio = creplaceio[io].get("replace", "")
+
+            # Funktionsaufruf vorbereiten
+            dict_replace = {
+                "frm": creplaceio[io].get("frm"),
+                "byteorder": creplaceio[io].get("byteorder", "little"),
+                "bmk": creplaceio[io].get("bmk", ""),
+            }
 
-        :param key: IO zum entfernen
-        """
-        io_del = object.__getattribute__(self, key)
+            # Get bitaddress from config file
+            if "bit" in creplaceio[io]:
+                try:
+                    dict_replace["bit"] = creplaceio[io].getint("bit")
+                except Exception:
+                    raise ValueError(
+                        "replace_io_file: could not convert '{0}' "
+                        "bit '{1}' to integer"
+                        "".format(io, creplaceio[io]["bit"])
+                    )
 
-        # Alte Events vom Device löschen
-        io_del.unreg_event()
+            if "wordorder" in creplaceio[io]:
+                dict_replace["wordorder"] = creplaceio[io]["wordorder"]
 
-        # IO aus Byteliste und Attributen entfernen
-        if io_del._bitshift:
-            self.__dict_iobyte[io_del.address][io_del._bitaddress] = None
+            if "export" in creplaceio[io]:
+                try:
+                    dict_replace["export"] = creplaceio[io].getboolean("export")
+                except Exception:
+                    raise ValueError(
+                        "replace_io_file: could not convert '{0}' "
+                        "export '{1}' to bool"
+                        "".format(io, creplaceio[io]["export"])
+                    )
 
-            # Do not use any() because we want to know None, not 0
-            if self.__dict_iobyte[io_del.address] == \
-                    [None, None, None, None, None, None, None, None]:
-                self.__dict_iobyte[io_del.address] = []
-        else:
-            self.__dict_iobyte[io_del.address].remove(io_del)
+            # Convert defaultvalue from config file
+            if "defaultvalue" in creplaceio[io]:
+                if dict_replace["frm"] == "?":
+                    try:
+                        dict_replace["defaultvalue"] = \
+                            creplaceio[io].getboolean("defaultvalue")
+                    except Exception:
+                        raise ValueError(
+                            "replace_io_file: could not convert '{0}' "
+                            "defaultvalue '{1}' to boolean"
+                            "".format(io, creplaceio[io]["defaultvalue"])
+                        )
+                elif dict_replace["frm"].find("s") >= 0:
+                    buff = bytearray()
+                    try:
+                        dv_array = creplaceio[io].get("defaultvalue").split(" ")
+                        for byte_int in dv_array:
+                            buff.append(int(byte_int))
+                        dict_replace["defaultvalue"] = bytes(buff)
+                    except Exception as e:
+                        raise ValueError(
+                            "replace_io_file: could not convert '{0}' "
+                            "defaultvalue to bytes | {1}"
+                            "".format(io, e)
+                        )
+                else:
+                    try:
+                        dict_replace["defaultvalue"] = \
+                            creplaceio[io].getint("defaultvalue")
+                    except Exception:
+                        raise ValueError(
+                            "replace_io_file: could not convert '{0}' "
+                            "defaultvalue '{1}' to integer"
+                            "".format(io, creplaceio[io]["defaultvalue"])
+                        )
 
-        object.__delattr__(self, key)
-        io_del._parentdevice._update_my_io_list()
+            # IO ersetzen
+            try:
+                self.io[parentio].replace_io(name=io, **dict_replace)
+            except Exception as e:
+                # NOTE: Bei Selected/Driver kann nicht geprüft werden
+                if len(self._devselect.values) == 0:
+                    raise RuntimeError(
+                        "replace_io_file: can not replace '{0}' with '{1}' "
+                        "| RevPiModIO message: {2}".format(parentio, io, e)
+                    )
 
-    def __getattr__(self, key):
+    def _create_myfh(self):
         """
-        Verwaltet geloeschte IOs (Attribute, die nicht existieren).
+        Erstellt FileObject mit Pfad zum procimg.
 
-        :param key: Name oder Byte eines alten IOs
-        :return: Alten IO, wenn in Ref-Listen
+        :return: FileObject
         """
-        if key in self.__dict_iorefname:
-            return self.__dict_iorefname[key]
-        else:
-            raise AttributeError("can not find io '{0}'".format(key))
+        self._buffedwrite = False
+        return open(self._procimg, "r+b", 0)
 
-    def __getitem__(self, key):
+    def _get_configrsc(self) -> str:
         """
-        Ruft angegebenen IO ab.
-
-        Wenn der Key <class 'str'> ist, wird ein einzelner IO geliefert. Wird
-        der Key als <class 'int'> uebergeben, wird eine <class 'list'>
-        geliefert mit 0, 1 oder 8 Eintraegen.
-        Wird als Key <class 'slice'> gegeben, werden die Listen in einer Liste
-        zurueckgegeben.
-
-        :param key: IO Name als <class 'str> oder Byte als <class 'int'>.
-        :return: IO Objekt oder Liste der IOs
-        """
-        if type(key) == int:
-            if key not in self.__dict_iobyte:
-                raise IndexError("byte '{0}' does not exist".format(key))
-            return self.__dict_iobyte[key]
-        elif type(key) == slice:
-            return [
-                self.__dict_iobyte[int_io]
-                for int_io in range(
-                    key.start, key.stop, 1 if key.step is None else key.step
-                )
-            ]
-        else:
-            return getattr(self, key)
+        Getter function.
 
-    def __iter__(self):
+        :return: Pfad der verwendeten piCtory Konfiguration
         """
-        Gibt Iterator aller IOs zurueck.
+        return self._configrsc
 
-        :return: Iterator aller IOs
+    def _get_cpreplaceio(self) -> ConfigParser:
         """
-        for int_io in sorted(self.__dict_iobyte):
-            for io in self.__dict_iobyte[int_io]:
-                if io is not None:
-                    yield io
+        Laedt die replace_io_file Konfiguration und verarbeitet sie.
 
-    def __len__(self):
+        :return: <class 'ConfigParser'> der replace io daten
         """
-        Gibt die Anzahl aller IOs zurueck.
+        cp = ConfigParser()
 
-        :return: Anzahl aller IOs
-        """
-        int_ios = 0
-        for int_io in self.__dict_iobyte:
-            for io in self.__dict_iobyte[int_io]:
-                if io is not None:
-                    int_ios += 1
-        return int_ios
+        if self._replace_io_file:
+            try:
+                with open(self._replace_io_file, "r") as fh:
+                    cp.read_file(fh)
+            except Exception as e:
+                raise RuntimeError(
+                    "replace_io_file: could not read/parse file '{0}' | {1}"
+                    "".format(self._replace_io_file, e)
+                )
 
-    def __setattr__(self, key, value):
-        """Verbietet aus Leistungsguenden das direkte Setzen von Attributen."""
-        if key in (
-                "_IOList__dict_iobyte",
-                "_IOList__dict_iorefname"
-        ):
-            object.__setattr__(self, key, value)
-        else:
-            raise AttributeError(
-                "direct assignment is not supported - use .value Attribute"
-            )
+        return cp
 
-    def __private_replace_oldio_with_newio(self, io) -> None:
+    def _get_cycletime(self) -> int:
         """
-        Ersetzt bestehende IOs durch den neu Registrierten.
+        Gibt Aktualisierungsrate in ms der Prozessabbildsynchronisierung aus.
 
-        :param io: Neuer IO der eingefuegt werden soll
+        :return: Millisekunden
         """
-        # Scanbereich festlegen
-        if io._bitshift:
-            scan_start = io._parentio_address
-            scan_stop = scan_start + io._parentio_length
-        else:
-            scan_start = io.address
-            scan_stop = scan_start + (1 if io._length == 0 else io._length)
-
-        # Defaultvalue über mehrere Bytes sammeln
-        calc_defaultvalue = b''
-
-        for i in range(scan_start, scan_stop):
-            for oldio in self.__dict_iobyte[i]:
+        return self._imgwriter.refresh
 
-                if type(oldio) == StructIO:
-                    # Hier gibt es schon einen neuen IO
-                    if oldio._bitshift:
-                        if io._bitshift == oldio._bitshift \
-                                and io._slc_address == oldio._slc_address:
-                            raise MemoryError(
-                                "bit {0} already assigned to '{1}'".format(
-                                    io._bitaddress, oldio._name
-                                )
-                            )
-                    else:
-                        # Bereits überschriebene bytes sind ungültig
-                        raise MemoryError(
-                            "new io '{0}' overlaps memory of '{1}'".format(
-                                io._name, oldio._name
-                            )
-                        )
-                elif oldio is not None:
-                    # IOs im Speicherbereich des neuen IO merken
-                    if io._bitshift:
-                        # ios für ref bei bitaddress speichern
-                        self.__dict_iorefname[oldio._name] = DeadIO(oldio)
-                    else:
-                        # Defaultwert berechnen
-                        oldio.byteorder = io._byteorder
-                        if io._byteorder == "little":
-                            calc_defaultvalue += oldio._defaultvalue
-                        else:
-                            calc_defaultvalue = \
-                                oldio._defaultvalue + calc_defaultvalue
-
-                    # ios aus listen entfernen
-                    delattr(self, oldio._name)
-
-        if io._defaultvalue is None:
-            # Nur bei StructIO und keiner gegebenen defaultvalue übernehmen
-            if io._bitshift:
-                io_byte_address = io._parentio_address - io.address
-                io._defaultvalue = bool(
-                    io._parentio_defaultvalue[io_byte_address] & io._bitshift
-                )
-            else:
-                io._defaultvalue = calc_defaultvalue
-
-    def _private_register_new_io_object(self, new_io) -> None:
+    def _get_debug(self) -> bool:
         """
-        Registriert neues IO Objekt unabhaenging von __setattr__.
+        Gibt Status des Debugflags zurueck.
 
-        :param new_io: Neues IO Objekt
+        :return: Status des Debugflags
         """
-        if isinstance(new_io, IOBase):
-            if hasattr(self, new_io._name):
-                raise AttributeError(
-                    "attribute {0} already exists - can not set io"
-                    "".format(new_io._name)
-                )
+        return self._debug == 1
 
-            if type(new_io) is StructIO:
-                self.__private_replace_oldio_with_newio(new_io)
-
-            object.__setattr__(self, new_io._name, new_io)
-
-            # Bytedict für Adresszugriff anpassen
-            if new_io._bitshift:
-                if len(self.__dict_iobyte[new_io.address]) != 8:
-                    # "schnell" 8 Einträge erstellen da es BIT IOs sind
-                    self.__dict_iobyte[new_io.address] += \
-                        [None, None, None, None, None, None, None, None]
-                self.__dict_iobyte[new_io.address][new_io._bitaddress] = new_io
-            else:
-                self.__dict_iobyte[new_io.address].append(new_io)
-
-            if type(new_io) is StructIO:
-                new_io._parentdevice._update_my_io_list()
-        else:
-            raise TypeError("io must be <class 'IOBase'> or sub class")
-
-
-class DeadIO(object):
-    """Klasse, mit der ersetzte IOs verwaltet werden."""
-
-    __slots__ = "__deadio"
-
-    def __init__(self, deadio):
+    def _get_ioerrors(self) -> int:
         """
-        Instantiierung der DeadIO-Klasse.
+        Getter function.
 
-        :param deadio: IO, der ersetzt wurde
+        :return: Aktuelle Anzahl gezaehlter Fehler
         """
-        self.__deadio = deadio
+        return self._ioerror
 
-    def replace_io(self, name: str, frm: str, **kwargs) -> None:
+    def _get_length(self) -> int:
         """
-        Stellt Funktion fuer weiter Bit-Ersetzungen bereit.
+        Getter function.
 
-        :ref: :func:IntIOReplaceable.replace_io()
+        :return: Laenge in Bytes der Devices
         """
-        self.__deadio.replace_io(name, frm, **kwargs)
-
-    _parentdevice = property(lambda self: None)
-
+        return self._length
 
-class IOBase(object):
-    """
-    Basisklasse fuer alle IO-Objekte.
-
-    Die Basisfunktionalitaet ermoeglicht das Lesen und Schreiben der Werte
-    als <class bytes'> oder <class 'bool'>. Dies entscheidet sich bei der
-    Instantiierung.
-    Wenn eine Bittadresse angegeben wird, werden <class 'bool'>-Werte erwartet
-    und zurueckgegeben, ansonsten <class bytes'>.
-
-    Diese Klasse dient als Basis fuer andere IO-Klassen mit denen die Werte
-    auch als <class 'int'> verwendet werden koennen.
-    """
-
-    __slots__ = "__bit_ioctl_off", "__bit_ioctl_on", "_bitaddress", \
-        "_bitshift", "_bitlength", "_byteorder", "_defaultvalue", \
-        "_export", "_iotype", "_length", "_name", "_parentdevice", \
-        "_read_only_io", "_signed", "_slc_address", "bmk"
-
-    def __init__(self, parentdevice, valuelist: list, iotype: int,
-                 byteorder: str, signed: bool):
-        """
-        Instantiierung der IOBase-Klasse.
-
-        :param parentdevice: Parentdevice auf dem der IO liegt
-        :param valuelist: Datenliste fuer Instantiierung
-            ["name","defval","bitlen","startaddrdev",exp,"idx","bmk","bitaddr"]
-        :param iotype: <class 'int'> Wert
-        :param byteorder: Byteorder 'little'/'big' fuer <class 'int'> Berechnung
-        :param signed: Intberechnung mit Vorzeichen durchfuehren
-        """
-        # ["name","defval","bitlen","startaddrdev",exp,"idx","bmk","bitaddr"]
-        # [  0   ,   1    ,   2    ,       3      , 4 ,  5  ,  6  ,    7    ]
-        self._parentdevice = parentdevice
-
-        # Bitadressen auf Bytes aufbrechen und umrechnen
-        self._bitaddress = -1 if valuelist[7] == "" else int(valuelist[7]) % 8
-        self._bitshift = None if self._bitaddress == -1 \
-            else 1 << self._bitaddress
-
-        # Längenberechnung
-        self._bitlength = int(valuelist[2])
-        self._length = 1 if self._bitaddress == 0 else int(self._bitlength / 8)
-
-        self.__bit_ioctl_off = None
-        self.__bit_ioctl_on = None
-        self._read_only_io = iotype != OUT
-        self._byteorder = byteorder
-        self._iotype = iotype
-        self._name = valuelist[0]
-        self._signed = signed
-        self.bmk = valuelist[6]
-        self._export = int(valuelist[4]) & 1
-
-        int_startaddress = int(valuelist[3])
-        if self._bitshift:
-            # Höhere Bits als 7 auf nächste Bytes umbrechen
-            int_startaddress += int(int(valuelist[7]) / 8)
-            self._slc_address = slice(
-                int_startaddress, int_startaddress + 1
-            )
-
-            # Defaultvalue ermitteln, sonst False
-            if valuelist[1] is None and type(self) == StructIO:
-                self._defaultvalue = None
-            else:
-                try:
-                    self._defaultvalue = bool(int(valuelist[1]))
-                except Exception:
-                    self._defaultvalue = False
-
-            # Ioctl für Bitsetzung setzen
-            self.__bit_ioctl_off = struct.pack(
-                "<HB", self._get_address(), self._bitaddress
-            )
-            self.__bit_ioctl_on = self.__bit_ioctl_off + b'\x01'
-        else:
-            self._slc_address = slice(
-                int_startaddress, int_startaddress + self._length
-            )
-            if str(valuelist[1]).isdigit():
-                # Defaultvalue aus Zahl in Bytes umrechnen
-                self._defaultvalue = int(valuelist[1]).to_bytes(
-                    self._length, byteorder=self._byteorder
-                )
-            elif valuelist[1] is None and type(self) == StructIO:
-                # Auf None setzen um später berechnete Werte zu übernehmen
-                self._defaultvalue = None
-            elif type(valuelist[1]) == bytes:
-                # Defaultvalue direkt von bytes übernehmen
-                if len(valuelist[1]) == self._length:
-                    self._defaultvalue = valuelist[1]
-                else:
-                    raise ValueError(
-                        "given bytes for default value must have a length "
-                        "of {0} but {1} was given"
-                        "".format(self._length, len(valuelist[1]))
-                    )
-            else:
-                # Defaultvalue mit leeren Bytes füllen
-                self._defaultvalue = bytes(self._length)
-
-                # Versuchen String in ASCII Bytes zu wandeln
-                if type(valuelist[1]) == str:
-                    try:
-                        buff = valuelist[1].encode("ASCII")
-                        if len(buff) <= self._length:
-                            self._defaultvalue = \
-                                buff + bytes(self._length - len(buff))
-                    except Exception:
-                        pass
-
-    def __bool__(self):
+    def _get_maxioerrors(self) -> int:
         """
-        <class 'bool'>-Wert der Klasse.
+        Getter function.
 
-        :return: <class 'bool'> Nur False wenn False oder 0 sonst True
+        :return: Anzahl erlaubte Fehler
         """
-        if self._bitshift:
-            return bool(
-                self._parentdevice._ba_devdata[self._slc_address.start]
-                & self._bitshift
-            )
-        else:
-            return any(self._parentdevice._ba_devdata[self._slc_address])
-
-    def __call__(self, value=None):
-        if value is None:
-            # Inline get_value()
-            if self._bitshift:
-                return bool(
-                    self._parentdevice._ba_devdata[self._slc_address.start]
-                    & self._bitshift
-                )
-            else:
-                return bytes(self._parentdevice._ba_devdata[self._slc_address])
-        else:
-            self.set_value(value)
+        return self._maxioerrors
 
-    def __len__(self):
+    def _get_monitoring(self) -> bool:
         """
-        Gibt die Bytelaenge des IO zurueck.
+        Getter function.
 
-        :return: Bytelaenge des IO - 0 bei BITs
+        :return: True, wenn als Monitoring gestartet
         """
-        return 0 if self._bitaddress > 0 else self._length
+        return self._monitoring
 
-    def __str__(self):
+    def _get_procimg(self) -> str:
         """
-        <class 'str'>-Wert der Klasse.
+        Getter function.
 
-        :return: Namen des IOs
+        :return: Pfad des verwendeten Prozessabbilds
         """
-        return self._name
+        return self._procimg
 
-    def __reg_xevent(self, func, delay: int, edge: int, as_thread: bool,
-                     overwrite: bool, prefire: bool) -> None:
+    def _get_replace_io_file(self) -> str:
         """
-        Verwaltet reg_event und reg_timerevent.
+        Gibt Pfad zur verwendeten replace IO Datei aus.
 
-        :param func: Funktion die bei Aenderung aufgerufen werden soll
-        :param delay: Verzoegerung in ms zum Ausloesen - auch bei Wertaenderung
-        :param edge: Ausfuehren bei RISING, FALLING or BOTH Wertaenderung
-        :param as_thread: Bei True, Funktion als EventCallback-Thread ausfuehren
-        :param overwrite: Wenn True, wird Event bei ueberschrieben
-        :param prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
+        :return: Pfad zur replace IO Datei
         """
-        # Prüfen ob Funktion callable ist
-        if not callable(func):
-            raise ValueError(
-                "registered function '{0}' is not callable".format(func)
-            )
-        if type(delay) != int or delay < 0:
-            raise ValueError(
-                "'delay' must be <class 'int'> and greater or equal 0"
-            )
-        if edge != BOTH and not self._bitshift:
-            raise ValueError(
-                "parameter 'edge' can be used with bit io objects only"
-            )
-        if prefire and self._parentdevice._modio._looprunning:
-            raise RuntimeError(
-                "prefire can not be used if mainloop is running"
-            )
-
-        if self not in self._parentdevice._dict_events:
-            with self._parentdevice._filelock:
-                self._parentdevice._dict_events[self] = \
-                    [IOEvent(func, edge, as_thread, delay, overwrite, prefire)]
-        else:
-            # Prüfen ob Funktion schon registriert ist
-            for regfunc in self._parentdevice._dict_events[self]:
-                if regfunc.func != func:
-                    # Nächsten Eintrag testen
-                    continue
-
-                if edge == BOTH or regfunc.edge == BOTH:
-                    if self._bitshift:
-                        raise RuntimeError(
-                            "io '{0}' with function '{1}' already in list "
-                            "with edge '{2}' - edge '{3}' not allowed anymore"
-                            "".format(
-                                self._name, func,
-                                consttostr(regfunc.edge), consttostr(edge)
-                            )
-                        )
-                    else:
-                        raise RuntimeError(
-                            "io '{0}' with function '{1}' already in list."
-                            "".format(self._name, func)
-                        )
-
-                elif regfunc.edge == edge:
-                    raise RuntimeError(
-                        "io '{0}' with function '{1}' for given edge '{2}' "
-                        "already in list".format(
-                            self._name, func, consttostr(edge)
-                        )
-                    )
-
-            # Eventfunktion einfügen
-            with self._parentdevice._filelock:
-                self._parentdevice._dict_events[self].append(
-                    IOEvent(func, edge, as_thread, delay, overwrite, prefire)
-                )
+        return self._replace_io_file
 
-    def _get_address(self) -> int:
+    def _get_simulator(self) -> bool:
         """
-        Gibt die absolute Byteadresse im Prozessabbild zurueck.
+        Getter function.
 
-        :return: Absolute Byteadresse
+        :return: True, wenn als Simulator gestartet
         """
-        return self._parentdevice._offset + self._slc_address.start
+        return self._simulator
 
-    def _get_byteorder(self) -> str:
+    def _gotioerror(self, action: str, e=None, show_warn=True) -> None:
         """
-        Gibt konfigurierte Byteorder zurueck.
+        IOError Verwaltung fuer Prozessabbildzugriff.
 
-        :return: <class 'str'> Byteorder
+        :param action: Zusatzinformationen zum loggen
+        :param e: Exception to log if debug is enabled
+        :param show_warn: Warnung anzeigen
         """
-        return self._byteorder
+        self._ioerror += 1
+        if self._maxioerrors != 0 and self._ioerror >= self._maxioerrors:
+            raise RuntimeError(
+                "reach max io error count {0} on process image"
+                "".format(self._maxioerrors)
+            )
 
-    def _get_export(self) -> bool:
-        """Return value of export flag."""
-        return bool(self._export & 1)
+        if not show_warn or self._debug == -1:
+            return
 
-    def _get_iotype(self) -> int:
-        """
-        Gibt io type zurueck.
+        if self._debug == 0:
+            warnings.warn(
+                "got io error on process image",
+                RuntimeWarning
+            )
+        else:
+            warnings.warn(
+                "got io error during '{0}' and count {1} errors now | {2}"
+                "".format(action, self._ioerror, str(e)),
+                RuntimeWarning
+            )
 
-        :return: <class 'int'> io type
+    def _set_cycletime(self, milliseconds: int) -> None:
         """
-        return self._iotype
-
-    def _set_export(self, value: bool) -> None:
-        """Set value of export flag and remember this change for export."""
-        if type(value) != bool:
-            raise ValueError("Value must be <class 'bool'>")
-        self._export = 2 + int(value)
+        Setzt Aktualisierungsrate der Prozessabbild-Synchronisierung.
 
-    def _write_to_procimg(self) -> bool:
+        :param milliseconds: <class 'int'> in Millisekunden
         """
-        Write value of io directly to the process image.
+        if self._looprunning:
+            raise RuntimeError(
+                "can not change cycletime when cycleloop or mainloop is "
+                "running"
+            )
+        else:
+            self._imgwriter.refresh = milliseconds
 
-        :return: True after successful write operation
+    def _set_debug(self, value: bool) -> None:
         """
-        if not self._parentdevice._shared_procimg:
-            raise RuntimeError("device is not marked for shared_procimg")
-
-        # note: Will not be removed from _shared_write on direct call
+        Setzt debugging Status um mehr Meldungen zu erhalten oder nicht.
 
-        if self._bitshift:
-            # Write single bit to process image
-            value = \
-                self._parentdevice._ba_devdata[self._slc_address.start] & \
-                self._bitshift
-            if self._parentdevice._modio._run_on_pi:
-                # IOCTL auf dem RevPi
-                with self._parentdevice._modio._myfh_lck:
-                    try:
-                        # Set value durchführen (Funktion K+16)
-                        ioctl(
-                            self._parentdevice._modio._myfh,
-                            19216,
-                            self.__bit_ioctl_on if value
-                            else self.__bit_ioctl_off
-                        )
-                    except Exception as e:
-                        self._parentdevice._modio._gotioerror("ioset", e)
-                        return False
+        :param value: Wenn True, werden umfangreiche Medungen angezeigt
+        """
+        if type(value) == bool:
+            value = int(value)
+        if not type(value) == int:
+            # Wert -1 ist zum kompletten deaktivieren versteckt
+            raise TypeError("value must be <class 'bool'> or <class 'int'>")
+        if not -1 <= value <= 1:
+            raise ValueError("value must be True/False or -1, 0, 1")
 
-            elif hasattr(self._parentdevice._modio._myfh, "ioctl"):
-                # IOCTL über Netzwerk
-                with self._parentdevice._modio._myfh_lck:
-                    try:
-                        self._parentdevice._modio._myfh.ioctl(
-                            19216,
-                            self.__bit_ioctl_on if value
-                            else self.__bit_ioctl_off
-                        )
-                    except Exception as e:
-                        self._parentdevice._modio._gotioerror(
-                            "net_ioset", e)
-                        return False
-
-            else:
-                # IOCTL in Datei simulieren
-                try:
-                    # Set value durchführen (Funktion K+16)
-                    self._parentdevice._modio._simulate_ioctl(
-                        19216,
-                        self.__bit_ioctl_on if value
-                        else self.__bit_ioctl_off
-                    )
-                except Exception as e:
-                    self._parentdevice._modio._gotioerror("file_ioset", e)
-                    return False
+        self._debug = value
 
+        if value == -1:
+            warnings.filterwarnings("ignore", module="revpimodio2")
+        elif value == 0:
+            warnings.filterwarnings("default", module="revpimodio2")
         else:
-            value = bytes(self._parentdevice._ba_devdata[self._slc_address])
-            with self._parentdevice._modio._myfh_lck:
-                try:
-                    self._parentdevice._modio._myfh.seek(
-                        self._get_address()
-                    )
-                    self._parentdevice._modio._myfh.write(value)
-                    if self._parentdevice._modio._buffedwrite:
-                        self._parentdevice._modio._myfh.flush()
-                except IOError as e:
-                    self._parentdevice._modio._gotioerror("ioset", e)
-                    return False
+            warnings.filterwarnings("always", module="revpimodio2")
 
-        return True
-
-    def get_defaultvalue(self):
+    def _set_maxioerrors(self, value: int) -> None:
         """
-        Gibt die Defaultvalue von piCtory zurueck.
+        Setzt Anzahl der maximal erlaubten Fehler bei Prozessabbildzugriff.
 
-        :return: Defaultvalue als <class 'byte'> oder <class 'bool'>
+        :param value: Anzahl erlaubte Fehler
         """
-        return self._defaultvalue
-
-    def get_value(self):
-        """
-        Gibt den Wert des IOs zurueck.
+        if type(value) == int and value >= 0:
+            self._maxioerrors = value
+        else:
+            raise ValueError("value must be 0 or a positive integer")
 
-        :return: IO-Wert als <class 'bytes'> oder <class 'bool'>
+    def _simulate_ioctl(self, request: int, arg=b'') -> None:
         """
-        if self._bitshift:
-            return bool(
-                self._parentdevice._ba_devdata[self._slc_address.start]
-                & self._bitshift
-            )
-        else:
-            return bytes(self._parentdevice._ba_devdata[self._slc_address])
+        Simuliert IOCTL Funktionen auf procimg Datei.
 
-    def reg_event(
-            self, func, delay=0, edge=BOTH, as_thread=False, prefire=False):
+        :param request: IO Request
+        :param arg: Request argument
         """
-        Registriert fuer IO ein Event bei der Eventueberwachung.
+        if request == 19216:
+            # Einzelnes Bit setzen
+            byte_address = int.from_bytes(arg[:2], byteorder="little")
+            bit_address = arg[2]
+            new_value = bool(0 if len(arg) <= 3 else arg[3])
 
-        Die uebergebene Funktion wird ausgefuehrt, wenn sich der IO Wert
-        aendert. Mit Angabe von optionalen Parametern kann das
-        Ausloeseverhalten gesteuert werden.
+            # Simulatonsmodus schreibt direkt in Datei
+            with self._myfh_lck:
+                self._myfh.seek(byte_address)
+                int_byte = int.from_bytes(
+                    self._myfh.read(1), byteorder="little"
+                )
+                int_bit = 1 << bit_address
 
-        HINWEIS: Die delay-Zeit muss in die .cycletime passen, ist dies nicht
-        der Fall, wird IMMER aufgerundet!
+                if not bool(int_byte & int_bit) == new_value:
+                    if new_value:
+                        int_byte += int_bit
+                    else:
+                        int_byte -= int_bit
 
-        :param func: Funktion die bei Aenderung aufgerufen werden soll
-        :param delay: Verzoegerung in ms zum Ausloesen wenn Wert gleich bleibt
-        :param edge: Ausfuehren bei RISING, FALLING or BOTH Wertaenderung
-        :param as_thread: Bei True, Funktion als EventCallback-Thread ausfuehren
-        :param prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
+                    self._myfh.seek(byte_address)
+                    self._myfh.write(int_byte.to_bytes(1, byteorder="little"))
+                    if self._buffedwrite:
+                        self._myfh.flush()
+
+        elif request == 19220:
+            # Counterwert auf 0 setzen
+            dev_position = arg[0]
+            bit_field = int.from_bytes(arg[2:], byteorder="little")
+            io_byte = -1
+
+            for i in range(16):
+                if bool(bit_field & 1 << i):
+                    io_byte = self.device[dev_position].offset \
+                              + int(self.device[dev_position]._lst_counter[i])
+                    break
+
+            if io_byte == -1:
+                raise RuntimeError("could not reset counter io in file")
+
+            with self._myfh_lck:
+                self._myfh.seek(io_byte)
+                self._myfh.write(b'\x00\x00\x00\x00')
+                if self._buffedwrite:
+                    self._myfh.flush()
+
+    def autorefresh_all(self) -> None:
+        """Setzt alle Devices in autorefresh Funktion."""
+        for dev in self.device:
+            dev.autorefresh()
+
+    def cleanup(self) -> None:
+        """Beendet autorefresh und alle Threads."""
+        self._exit_level |= 2
+        self.exit(full=True)
+
+    def cycleloop(self, func, cycletime=50, blocking=True):
+        """
+        Startet den Cycleloop.
+
+        Der aktuelle Programmthread wird hier bis Aufruf von
+        .exit() "gefangen". Er fuehrt nach jeder Aktualisierung
+        des Prozessabbilds die uebergebene Funktion "func" aus und arbeitet sie
+        ab. Waehrend der Ausfuehrung der Funktion wird das Prozessabbild nicht
+        weiter aktualisiert. Die Inputs behalten bis zum Ende den aktuellen
+        Wert. Gesetzte Outputs werden nach Ende des Funktionsdurchlaufs in das
+        Prozessabbild geschrieben.
+
+        Verlassen wird der Cycleloop, wenn die aufgerufene Funktion einen
+        Rueckgabewert nicht gleich None liefert (z.B. return True), oder durch
+        Aufruf von .exit().
+
+        HINWEIS: Die Aktualisierungszeit und die Laufzeit der Funktion duerfen
+        die eingestellte autorefresh Zeit, bzw. uebergebene cycletime nicht
+        ueberschreiten!
+
+        Ueber den Parameter cycletime wird die gewuenschte Zukluszeit der
+        uebergebenen Funktion gesetzt. Der Standardwert betraegt
+        50 Millisekunden, in denen das Prozessabild eingelesen, die uebergebene
+        Funktion ausgefuert und das Prozessabbild geschrieben wird.
+
+        :param func: Funktion, die ausgefuehrt werden soll
+        :param cycletime: Zykluszeit in Millisekunden - Standardwert 50 ms
+        :param blocking: Wenn False, blockiert das Programm hier NICHT
+        :return: None or the return value of the cycle function
         """
-        self.__reg_xevent(func, delay, edge, as_thread, True, prefire)
+        # Prüfen ob ein Loop bereits läuft
+        if self._looprunning:
+            raise RuntimeError(
+                "can not start multiple loops mainloop/cycleloop"
+            )
 
-    def reg_timerevent(
-            self, func, delay, edge=BOTH, as_thread=False, prefire=False):
-        """
-        Registriert fuer IO einen Timer, welcher nach delay func ausfuehrt.
+        # Prüfen ob Devices in autorefresh sind
+        if len(self._lst_refresh) == 0:
+            raise RuntimeError(
+                "no device with autorefresh activated - use autorefresh=True "
+                "or call .autorefresh_all() before entering cycleloop"
+            )
 
-        Der Timer wird gestartet, wenn sich der IO Wert aendert und fuehrt die
-        uebergebene Funktion aus - auch wenn sich der IO Wert in der
-        zwischenzeit geaendert hat. Sollte der Timer nicht abelaufen sein und
-        die Bedingugn erneut zutreffen, wird der Timer NICHT auf den delay Wert
-        zurueckgesetzt oder ein zweites Mal gestartet. Fuer dieses Verhalten
-        kann .reg_event(..., delay=wert) verwendet werden.
+        # Prüfen ob Funktion callable ist
+        if not callable(func):
+            raise RuntimeError(
+                "registered function '{0}' ist not callable".format(func)
+            )
 
-        HINWEIS: Die delay-Zeit muss in die .cycletime passen, ist dies nicht
-        der Fall, wird IMMER aufgerundet!
+        # Thread erstellen, wenn nicht blockieren soll
+        if not blocking:
+            self._th_mainloop = Thread(
+                target=self.cycleloop,
+                args=(func,),
+                kwargs={"cycletime": cycletime, "blocking": True}
+            )
+            self._th_mainloop.start()
+            return
+
+        # Zykluszeit übernehmen
+        old_cycletime = self._imgwriter.refresh
+        if not cycletime == self._imgwriter.refresh:
+            # Set new cycle time and wait one imgwriter cycle to sync fist cycle
+            self._imgwriter.refresh = cycletime
+            self._imgwriter.newdata.clear()
+            self._imgwriter.newdata.wait(self._imgwriter._refresh)
+
+        # Benutzerevent
+        self.exitsignal.clear()
+
+        # Cycleloop starten
+        self._exit.clear()
+        self._looprunning = True
+        cycleinfo = helpermodule.Cycletools(self._imgwriter.refresh, self)
+        e = None  # Exception
+        ec = None  # Return value of cycle_function
+        self._imgwriter.newdata.clear()
+        try:
+            while ec is None and not cycleinfo.last:
+                # Auf neue Daten warten und nur ausführen wenn set()
+                if not self._imgwriter.newdata.wait(2.5):
+                    if not self._imgwriter.is_alive():
+                        self.exit(full=False)
+                        e = RuntimeError("autorefresh thread not running")
+                        break
+
+                    # Just warn, user has to use maxioerrors to kill program
+                    warnings.warn(RuntimeWarning(
+                        "no new io data in cycle loop for 2500 milliseconds"
+                    ))
+                    cycleinfo.last = self._exit.is_set()
+                    continue
 
-        :param func: Funktion die bei Aenderung aufgerufen werden soll
-        :param delay: Verzoegerung in ms zum Ausloesen - auch bei Wertaenderung
-        :param edge: Ausfuehren bei RISING, FALLING or BOTH Wertaenderung
-        :param as_thread: Bei True, Funktion als EventCallback-Thread ausfuehren
-        :param prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
-        """
-        self.__reg_xevent(func, delay, edge, as_thread, False, prefire)
+                self._imgwriter.newdata.clear()
 
-    def set_value(self, value) -> None:
-        """
-        Setzt den Wert des IOs.
+                # Vor Aufruf der Funktion autorefresh sperren
+                self._imgwriter.lck_refresh.acquire()
 
-        :param value: IO-Wert als <class bytes'> oder <class 'bool'>
-        """
-        if self._read_only_io:
-            if self._iotype == INP:
-                if self._parentdevice._modio._simulator:
-                    raise RuntimeError(
-                        "can not write to output '{0}' in simulator mode"
-                        "".format(self._name)
-                    )
-                else:
-                    raise RuntimeError(
-                        "can not write to input '{0}'".format(self._name)
-                    )
-            elif self._iotype == MEM:
-                raise RuntimeError(
-                    "can not write to memory '{0}'".format(self._name)
-                )
+                # Vorbereitung für cycleinfo
+                cycleinfo._start_timer = default_timer()
+                cycleinfo.last = self._exit.is_set()
+
+                # Funktion aufrufen und auswerten
+                ec = func(cycleinfo)
+                cycleinfo._docycle()
+
+                # autorefresh freigeben
+                self._imgwriter.lck_refresh.release()
+        except Exception as ex:
+            if self._imgwriter.lck_refresh.locked():
+                self._imgwriter.lck_refresh.release()
+            if self._th_mainloop is None:
+                self.exit(full=False)
+            e = ex
+        finally:
+            # Cycleloop beenden
+            self._looprunning = False
+            self._th_mainloop = None
+
+        # Alte autorefresh Zeit setzen
+        self._imgwriter.refresh = old_cycletime
+
+        # Exitstrategie ausführen
+        self.__exit_jobs()
+
+        # Auf Fehler prüfen die im loop geworfen wurden
+        if e is not None:
+            raise e
+
+        return ec
+
+    def exit(self, full=True) -> None:
+        """
+        Beendet mainloop() und optional autorefresh.
+
+        Wenn sich das Programm im mainloop() befindet, wird durch Aufruf
+        von exit() die Kontrolle wieder an das Hauptprogramm zurueckgegeben.
+
+        Der Parameter full ist mit True vorbelegt und entfernt alle Devices aus
+        dem autorefresh. Der Thread fuer die Prozessabbildsynchronisierung
+        wird dann gestoppt und das Programm kann sauber beendet werden.
+
+        :param full: Entfernt auch alle Devices aus autorefresh
+        """
+        self._exit_level |= 1 if full else 0
+
+        # Echten Loopwert vor Events speichern
+        full = full and not self._looprunning
+
+        # Benutzerevent
+        self.exitsignal.set()
+
+        self._exit.set()
+        self._waitexit.set()
+
+        # Auf beenden von mainloop thread warten
+        if self._th_mainloop is not None and self._th_mainloop.is_alive():
+            self._th_mainloop.join(2.5)
+
+        if full:
+            self.__exit_jobs()
+
+    def export_replaced_ios(self, filename="replace_ios.conf") -> None:
+        """
+        Exportiert ersetzte IOs dieser Instanz.
+
+        Exportiert alle ersetzten IOs, welche mit .replace_io(...) angelegt
+        wurden. Die Datei kann z.B. fuer RevPiPyLoad verwendet werden um Daten
+        in den neuen Formaten per MQTT zu uebertragen oder mit RevPiPyControl
+        anzusehen.
+
+        @param filename Dateiname fuer Exportdatei
+        """
+        acheck(str, filename=filename)
+
+        cp = ConfigParser()
+        for io in self.io:
+            if isinstance(io, StructIO):
+
+                # Required values
+                cp.add_section(io.name)
+                cp[io.name]["replace"] = io._parentio_name
+                cp[io.name]["frm"] = io.frm
+
+                # Optional values
+                if io._bitshift:
+                    cp[io.name]["bit"] = str(io._bitaddress)
+                if io._byteorder != "little":
+                    cp[io.name]["byteorder"] = io._byteorder
+                if io._wordorder:
+                    cp[io.name]["wordorder"] = io._wordorder
+                if type(io.defaultvalue) is bytes:
+                    if any(io.defaultvalue):
+                        # Convert each byte to an integer
+                        cp[io.name]["defaultvalue"] = \
+                            " ".join(map(str, io.defaultvalue))
+                elif io.defaultvalue != 0:
+                    cp[io.name]["defaultvalue"] = str(io.defaultvalue)
+                if io.bmk != "":
+                    cp[io.name]["bmk"] = io.bmk
+                if io._export & 2:
+                    cp[io.name]["export"] = str(io._export & 1)
+
+        try:
+            with open(filename, "w") as fh:
+                cp.write(fh)
+        except Exception as e:
             raise RuntimeError(
-                "the io object '{0}' is read only".format(self._name)
+                "could not write export file '{0}' | {1}"
+                "".format(filename, e)
             )
 
-        if self._bitshift:
-            # Versuchen egal welchen Typ in Bool zu konvertieren
-            value = bool(value)
-
-            # Für Bitoperationen sperren
-            self._parentdevice._filelock.acquire()
-
-            if self._parentdevice._shared_procimg \
-                    and self not in self._parentdevice._shared_write:
-                # Mark this IO for write operations
-                self._parentdevice._shared_write.append(self)
-
-            # Hier gibt es immer nur ein byte, als int holen
-            int_byte = self._parentdevice._ba_devdata[self._slc_address.start]
-
-            # Aktuellen Wert vergleichen und ggf. setzen
-            if not bool(int_byte & self._bitshift) == value:
-                if value:
-                    int_byte += self._bitshift
-                else:
-                    int_byte -= self._bitshift
-
-                # Zurückschreiben wenn verändert
-                self._parentdevice._ba_devdata[self._slc_address.start] = \
-                    int_byte
-
-            self._parentdevice._filelock.release()
+    def get_jconfigrsc(self) -> dict:
+        """
+        Laedt die piCtory Konfiguration und erstellt ein <class 'dict'>.
 
+        :return: <class 'dict'> der piCtory Konfiguration
+        """
+        # piCtory Konfiguration prüfen
+        if self._configrsc is not None:
+            if not access(self._configrsc, F_OK | R_OK):
+                raise RuntimeError(
+                    "can not access pictory configuration at {0}".format(
+                        self._configrsc))
         else:
-            if type(value) != bytes:
-                raise TypeError(
-                    "'{0}' requires a <class 'bytes'> object, not {1}".format(
-                        self._name, type(value)
-                    )
+            # piCtory Konfiguration an bekannten Stellen prüfen
+            lst_rsc = ["/etc/revpi/config.rsc", "/opt/KUNBUS/config.rsc"]
+            for rscfile in lst_rsc:
+                if access(rscfile, F_OK | R_OK):
+                    self._configrsc = rscfile
+                    break
+            if self._configrsc is None:
+                raise RuntimeError(
+                    "can not access known pictory configurations at {0} - "
+                    "use 'configrsc' parameter so specify location"
+                    "".format(", ".join(lst_rsc))
                 )
 
-            if self._length != len(value):
-                raise ValueError(
-                    "'{0}' requires a <class 'bytes'> object of "
-                    "length {1}, but {2} was given".format(
-                        self._name, self._length, len(value)
-                    )
+        with open(self._configrsc, "r") as fhconfigrsc:
+            try:
+                jdata = jload(fhconfigrsc)
+            except Exception:
+                raise RuntimeError(
+                    "can not read piCtory configuration - check your hardware "
+                    "configuration http://revpi_ip/"
                 )
+            return jdata
 
-            if self._parentdevice._shared_procimg \
-                    and self not in self._parentdevice._shared_write:
-                with self._parentdevice._filelock:
-                    # Mark this IO as changed
-                    self._parentdevice._shared_write.append(self)
-
-            self._parentdevice._ba_devdata[self._slc_address] = value
-
-    def unreg_event(self, func=None, edge=None) -> None:
-        """
-        Entfernt ein Event aus der Eventueberwachung.
-
-        :param func: Nur Events mit angegebener Funktion
-        :param edge: Nur Events mit angegebener Funktion und angegebener Edge
+    def handlesignalend(self, cleanupfunc=None) -> None:
         """
-        if self in self._parentdevice._dict_events:
-            if func is None:
-                with self._parentdevice._filelock:
-                    del self._parentdevice._dict_events[self]
-            else:
-                newlist = []
-                for regfunc in self._parentdevice._dict_events[self]:
-                    if regfunc.func != func or edge is not None \
-                            and regfunc.edge != edge:
-                        newlist.append(regfunc)
-
-                # Wenn Funktionen übrig bleiben, diese übernehmen
-                with self._parentdevice._filelock:
-                    if len(newlist) > 0:
-                        self._parentdevice._dict_events[self] = newlist
-                    else:
-                        del self._parentdevice._dict_events[self]
-
-    def wait(self, edge=BOTH, exitevent=None, okvalue=None, timeout=0) -> int:
-        """
-        Wartet auf Wertaenderung eines IOs.
-
-        Die Wertaenderung wird immer uerberprueft, wenn fuer Devices
-        mit aktiviertem autorefresh neue Daten gelesen wurden.
+        Signalhandler fuer Programmende verwalten.
 
-        Bei Wertaenderung, wird das Warten mit 0 als Rueckgabewert beendet.
+        Wird diese Funktion aufgerufen, uebernimmt RevPiModIO die SignalHandler
+        fuer SIGINT und SIGTERM. Diese werden Empfangen, wenn das
+        Betriebssystem oder der Benutzer das Steuerungsprogramm sauber beenden
+        will.
 
-        HINWEIS: Wenn <class 'ProcimgWriter'> keine neuen Daten liefert, wird
-        bis in die Ewigkeit gewartet (nicht bei Angabe von "timeout").
+        Die optionale Funktion "cleanupfunc" wird als letztes nach dem letzten
+        Einlesen der Inputs ausgefuehrt. Dort gesetzte Outputs werden nach
+        Ablauf der Funktion ein letztes Mal geschrieben.
+        Gedacht ist dies fuer Aufraeumarbeiten, wie z.B. das abschalten der
+        LEDs am RevPi-Core.
 
-        Wenn edge mit RISING oder FALLING angegeben wird, muss diese Flanke
-        ausgeloest werden. Sollte der Wert 1 sein beim Eintritt mit Flanke
-        RISING, wird das Warten erst bei Aenderung von 0 auf 1 beendet.
+        Nach einmaligem Empfangen eines der Signale und dem Beenden der
+        RevPiModIO Thrads / Funktionen werden die SignalHandler wieder
+        freigegeben.
 
-        Als exitevent kann ein <class 'threading.Event'>-Objekt uebergeben
-        werden, welches das Warten bei is_set() sofort mit 1 als Rueckgabewert
-        beendet.
-
-        Wenn der Wert okvalue an dem IO fuer das Warten anliegt, wird
-        das Warten sofort mit -1 als Rueckgabewert beendet.
+        :param cleanupfunc: Funktion wird nach dem Beenden ausgefuehrt
+        """
+        # Prüfen ob Funktion callable ist
+        if not (cleanupfunc is None or callable(cleanupfunc)):
+            raise RuntimeError(
+                "registered function '{0}' ist not callable"
+                "".format(cleanupfunc)
+            )
+        self.__cleanupfunc = cleanupfunc
+        signal(SIGINT, self.__evt_exit)
+        signal(SIGTERM, self.__evt_exit)
 
-        Der Timeoutwert bricht beim Erreichen das Warten sofort mit
-        Wert 2 Rueckgabewert ab. (Das Timeout wird ueber die Zykluszeit
-        der autorefresh Funktion berechnet, entspricht also nicht exakt den
-        angegeben Millisekunden! Es wird immer nach oben gerundet!)
+    def mainloop(self, blocking=True) -> None:
+        """
+        Startet den Mainloop mit Eventueberwachung.
 
-        :param edge: Flanke RISING, FALLING, BOTH die eintreten muss
-        :param exitevent: <class 'thrading.Event'> fuer vorzeitiges Beenden
-        :param okvalue: IO-Wert, bei dem das Warten sofort beendet wird
-        :param timeout: Zeit in ms nach der abgebrochen wird
-        :return: <class 'int'> erfolgreich Werte <= 0
+        Der aktuelle Programmthread wird hier bis Aufruf von
+        RevPiDevicelist.exit() "gefangen" (es sei denn blocking=False). Er
+        durchlaeuft die Eventueberwachung und prueft Aenderungen der, mit
+        einem Event registrierten, IOs. Wird eine Veraenderung erkannt,
+        fuert das Programm die dazugehoerigen Funktionen der Reihe nach aus.
 
-        - Erfolgreich gewartet
-            - Wert 0: IO hat den Wert gewechselt
-            - Wert -1: okvalue stimmte mit IO ueberein
-        - Fehlerhaft gewartet
-            - Wert 1: exitevent wurde gesetzt
-            - Wert 2: timeout abgelaufen
-            - Wert 100: Devicelist.exit() wurde aufgerufen
+        Wenn der Parameter "blocking" mit False angegeben wird, aktiviert
+        dies die Eventueberwachung und blockiert das Programm NICHT an der
+        Stelle des Aufrufs. Eignet sich gut fuer die GUI Programmierung, wenn
+        Events vom RevPi benoetigt werden, aber das Programm weiter ausgefuehrt
+        werden soll.
 
+        :param blocking: Wenn False, blockiert das Programm hier NICHT
         """
-        # Prüfen ob Device in autorefresh ist
-        if not self._parentdevice._selfupdate:
+        # Prüfen ob ein Loop bereits läuft
+        if self._looprunning:
             raise RuntimeError(
-                "autorefresh is not activated for device '{0}|{1}' - there "
-                "will never be new data".format(
-                    self._parentdevice._position, self._parentdevice._name
-                )
-            )
-        if not (RISING <= edge <= BOTH):
-            raise ValueError(
-                "parameter 'edge' must be revpimodio2.RISING, "
-                "revpimodio2.FALLING or revpimodio2.BOTH"
-            )
-        if not (exitevent is None or type(exitevent) == Event):
-            raise TypeError(
-                "parameter 'exitevent' must be <class 'threading.Event'>"
+                "can not start multiple loops mainloop/cycleloop"
             )
-        if type(timeout) != int or timeout < 0:
-            raise ValueError(
-                "parameter 'timeout' must be <class 'int'> and greater than 0"
-            )
-        if edge != BOTH and not self._bitshift:
-            raise ValueError(
-                "parameter 'edge' can be used with bit Inputs only"
+
+        # Prüfen ob Devices in autorefresh sind
+        if len(self._lst_refresh) == 0:
+            raise RuntimeError(
+                "no device with autorefresh activated - use autorefresh=True "
+                "or call .autorefresh_all() before entering mainloop"
             )
 
-        # Abbruchwert prüfen
-        if okvalue == self.value:
-            return -1
-
-        # WaitExit Event säubern
-        self._parentdevice._modio._waitexit.clear()
-
-        val_start = self.value
-        timeout = timeout / 1000
-        bool_timecount = timeout > 0
-        if exitevent is None:
-            exitevent = Event()
-
-        flt_timecount = 0 if bool_timecount else -1
-        while not self._parentdevice._modio._waitexit.is_set() \
-                and not exitevent.is_set() \
-                and flt_timecount < timeout:
-
-            if self._parentdevice._modio._imgwriter.newdata.wait(2.5):
-                self._parentdevice._modio._imgwriter.newdata.clear()
-
-                if val_start != self.value:
-                    if edge == BOTH \
-                            or edge == RISING and not val_start \
-                            or edge == FALLING and val_start:
-                        return 0
-                    else:
-                        val_start = not val_start
-                if bool_timecount:
-                    flt_timecount += \
-                        self._parentdevice._modio._imgwriter._refresh
-            elif bool_timecount:
-                flt_timecount += 2.5
-
-        # Abbruchevent wurde gesetzt
-        if exitevent.is_set():
-            return 1
-
-        # RevPiModIO mainloop wurde verlassen
-        if self._parentdevice._modio._waitexit.is_set():
-            return 100
-
-        # Timeout abgelaufen
-        return 2
-
-    address = property(_get_address)
-    byteorder = property(_get_byteorder)
-    defaultvalue = property(get_defaultvalue)
-    export = property(_get_export, _set_export)
-    length = property(__len__)
-    name = property(__str__)
-    type = property(_get_iotype)
-    value = property(get_value, set_value)
+        # Thread erstellen, wenn nicht blockieren soll
+        if not blocking:
+            self._th_mainloop = Thread(
+                target=self.mainloop, kwargs={"blocking": True}
+            )
+            self._th_mainloop.start()
+            return
+
+        # Benutzerevent
+        self.exitsignal.clear()
+
+        # Event säubern vor Eintritt in Mainloop
+        self._exit.clear()
+        self._looprunning = True
+
+        # Beim Eintritt in mainloop Bytecopy erstellen und prefire anhängen
+        for dev in self._lst_refresh:
+            with dev._filelock:
+                dev._ba_datacp = dev._ba_devdata[:]
+
+                # Prefire Events vorbereiten
+                for io in dev._dict_events:
+                    for regfunc in dev._dict_events[io]:
+                        if not regfunc.prefire:
+                            continue
+
+                        if regfunc.edge == BOTH \
+                                or regfunc.edge == RISING and io.value \
+                                or regfunc.edge == FALLING and not io.value:
+                            if regfunc.as_thread:
+                                self._imgwriter._eventqth.put(
+                                    (regfunc, io._name, io.value), False
+                                )
+                            else:
+                                self._imgwriter._eventq.put(
+                                    (regfunc, io._name, io.value), False
+                                )
 
+        # ImgWriter mit Eventüberwachung aktivieren
+        self._imgwriter._collect_events(True)
+        e = None
+        runtime = -1 if self._debug == -1 else 0
+
+        while not self._exit.is_set():
+
+            # Laufzeit der Eventqueue auf 0 setzen
+            if self._imgwriter._eventq.qsize() == 0:
+                runtime = -1 if self._debug == -1 else 0
 
-class IntIO(IOBase):
-    """
-    Klasse fuer den Zugriff auf die Daten mit Konvertierung in int.
+            try:
+                tup_fire = self._imgwriter._eventq.get(timeout=1)
 
-    Diese Klasse erweitert die Funktion von <class 'IOBase'> um Funktionen,
-    ueber die mit <class 'int'> Werten gearbeitet werden kann. Fuer die
-    Umwandlung koennen 'Byteorder' (Default 'little') und 'signed' (Default
-    False) als Parameter gesetzt werden.
+                # Messung Laufzeit der Queue starten
+                if runtime == 0:
+                    runtime = default_timer()
+
+                # Direct callen da Prüfung in io.IOBase.reg_event ist
+                tup_fire[0].func(tup_fire[1], tup_fire[2])
+                self._imgwriter._eventq.task_done()
+
+                # Laufzeitprüfung
+                if runtime != -1 and \
+                        default_timer() - runtime > self._imgwriter._refresh:
+                    runtime = -1
+                    warnings.warn(
+                        "can not execute all event functions in one cycle - "
+                        "optimize your event functions or rise .cycletime",
+                        RuntimeWarning
+                    )
+            except Empty:
+                if not self._exit.is_set() and not self._imgwriter.is_alive():
+                    e = RuntimeError("autorefresh thread not running")
+                    break
+            except Exception as ex:
+                e = ex
+                break
 
-    :ref: :class:`IOBase`
-    """
+        # Mainloop verlassen
+        self._imgwriter._collect_events(False)
+        self._looprunning = False
+        self._th_mainloop = None
 
-    __slots__ = ()
+        # Auf Fehler prüfen die im loop geworfen wurden
+        if e is not None:
+            self.exit(full=False)
+            self.__exit_jobs()
+            raise e
 
-    def __int__(self):
-        """
-        Gibt IO-Wert zurueck mit Beachtung byteorder/signed.
+        # Exitstrategie ausführen
+        self.__exit_jobs()
 
-        :return: IO-Wert als <class 'int'>
+    def readprocimg(self, device=None) -> bool:
         """
-        return int.from_bytes(
-            self._parentdevice._ba_devdata[self._slc_address],
-            byteorder=self._byteorder,
-            signed=self._signed
-        )
+        Einlesen aller Inputs aller/eines Devices vom Prozessabbild.
 
-    def __call__(self, value=None):
-        if value is None:
-            # Inline get_intvalue()
-            return int.from_bytes(
-                self._parentdevice._ba_devdata[self._slc_address],
-                byteorder=self._byteorder,
-                signed=self._signed
-            )
-        else:
-            # Inline from set_intvalue()
-            if type(value) == int:
-                self.set_value(value.to_bytes(
-                    self._length,
-                    byteorder=self._byteorder,
-                    signed=self._signed
-                ))
-            else:
-                raise TypeError(
-                    "'{0}' need a <class 'int'> value, but {1} was given"
-                    "".format(self._name, type(value))
-                )
+        Devices mit aktiverem autorefresh werden ausgenommen!
 
-    def _get_signed(self) -> bool:
+        :param device: nur auf einzelnes Device anwenden
+        :return: True, wenn Arbeiten an allen Devices erfolgreich waren
         """
-        Ruft ab, ob der Wert Vorzeichenbehaftet behandelt werden soll.
+        if device is None:
+            mylist = self.device
+        else:
+            dev = device if isinstance(device, devicemodule.Device) \
+                else self.device.__getitem__(device)
 
-        :return: True, wenn Vorzeichenbehaftet
-        """
-        return self._signed
+            if dev._selfupdate:
+                raise RuntimeError(
+                    "can not read process image, while device '{0}|{1}'"
+                    "is in autorefresh mode".format(dev._position, dev._name)
+                )
+            mylist = [dev]
 
-    def _set_byteorder(self, value: str) -> None:
-        """
-        Setzt Byteorder fuer <class 'int'> Umwandlung.
+        # Daten komplett einlesen
+        self._myfh_lck.acquire()
+        try:
+            self._myfh.seek(0)
+            bytesbuff = self._myfh.read(self._length)
+        except IOError as e:
+            self._gotioerror("readprocimg", e)
+            return False
+        finally:
+            self._myfh_lck.release()
+
+        for dev in mylist:
+            if not dev._selfupdate:
+
+                # FileHandler sperren
+                dev._filelock.acquire()
+
+                if self._monitoring or dev._shared_procimg:
+                    # Alles vom Bus einlesen
+                    dev._ba_devdata[:] = bytesbuff[dev._slc_devoff]
+                else:
+                    # Inputs vom Bus einlesen
+                    dev._ba_devdata[dev._slc_inp] = bytesbuff[dev._slc_inpoff]
 
-        :param value: <class 'str'> 'little' or 'big'
-        """
-        if not (value == "little" or value == "big"):
-            raise ValueError("byteorder must be 'little' or 'big'")
-        if self._byteorder != value:
-            self._byteorder = value
-            self._defaultvalue = self._defaultvalue[::-1]
+                dev._filelock.release()
 
-    def _set_signed(self, value: bool) -> None:
-        """
-        Left fest, ob der Wert Vorzeichenbehaftet behandelt werden soll.
+        return True
 
-        :param value: True, wenn mit Vorzeichen behandel
-        """
-        if type(value) != bool:
-            raise TypeError("signed must be <class 'bool'> True or False")
-        self._signed = value
+    def resetioerrors(self) -> None:
+        """Setzt aktuellen IOError-Zaehler auf 0 zurueck."""
+        self._ioerror = 0
 
-    def get_intdefaultvalue(self) -> int:
+    def setdefaultvalues(self, device=None) -> None:
         """
-        Gibt die Defaultvalue als <class 'int'> zurueck.
+        Alle Outputbuffer werden auf die piCtory default Werte gesetzt.
 
-        :return: <class 'int'> Defaultvalue
+        :param device: nur auf einzelnes Device anwenden
         """
-        return int.from_bytes(
-            self._defaultvalue, byteorder=self._byteorder, signed=self._signed
-        )
+        if self._monitoring:
+            raise RuntimeError(
+                "can not set default values, while system is in monitoring "
+                "mode"
+            )
 
-    def get_intvalue(self) -> int:
-        """
-        Gibt IO-Wert zurueck mit Beachtung byteorder/signed.
+        if device is None:
+            mylist = self.device
+        else:
+            dev = device if isinstance(device, devicemodule.Device) \
+                else self.device.__getitem__(device)
+            mylist = [dev]
 
-        :return: IO-Wert als <class 'int'>
-        """
-        return int.from_bytes(
-            self._parentdevice._ba_devdata[self._slc_address],
-            byteorder=self._byteorder,
-            signed=self._signed
-        )
+        for dev in mylist:
+            for io in dev.get_outputs():
+                io.set_value(io._defaultvalue)
 
-    def set_intvalue(self, value: int) -> None:
+    def syncoutputs(self, device=None) -> bool:
         """
-        Setzt IO mit Beachtung byteorder/signed.
+        Lesen aller aktuell gesetzten Outputs im Prozessabbild.
 
-        :param value: <class 'int'> Wert
+        Devices mit aktiverem autorefresh werden ausgenommen!
+
+        :param device: nur auf einzelnes Device anwenden
+        :return: True, wenn Arbeiten an allen Devices erfolgreich waren
         """
-        if type(value) == int:
-            self.set_value(value.to_bytes(
-                self._length,
-                byteorder=self._byteorder,
-                signed=self._signed
-            ))
+        if device is None:
+            mylist = self.device
         else:
-            raise TypeError(
-                "'{0}' need a <class 'int'> value, but {1} was given"
-                "".format(self._name, type(value))
-            )
-
-    byteorder = property(IOBase._get_byteorder, _set_byteorder)
-    defaultvalue = property(get_intdefaultvalue)
-    signed = property(_get_signed, _set_signed)
-    value = property(get_intvalue, set_intvalue)
-
+            dev = device if isinstance(device, devicemodule.Device) \
+                else self.device.__getitem__(device)
 
-class IntIOCounter(IntIO):
-    """Erweitert die IntIO-Klasse um die .reset() Funktion fuer Counter."""
+            if dev._selfupdate:
+                raise RuntimeError(
+                    "can not sync outputs, while device '{0}|{1}'"
+                    "is in autorefresh mode".format(dev._position, dev._name)
+                )
+            mylist = [dev]
 
-    __slots__ = ("__ioctl_arg",)
+        self._myfh_lck.acquire()
+        try:
+            self._myfh.seek(0)
+            bytesbuff = self._myfh.read(self._length)
+        except IOError as e:
+            self._gotioerror("syncoutputs", e)
+            return False
+        finally:
+            self._myfh_lck.release()
+
+        for dev in mylist:
+            if not dev._selfupdate:
+                dev._filelock.acquire()
+                dev._ba_devdata[dev._slc_out] = bytesbuff[dev._slc_outoff]
+                dev._filelock.release()
 
-    def __init__(
-            self, counter_id,
-            parentdevice, valuelist, iotype, byteorder, signed):
-        """
-        Instantiierung der IntIOCounter-Klasse.
+        return True
 
-        :param counter_id: ID fuer den Counter, zu dem der IO gehoert (0-15)
-        :ref: :func:`IOBase.__init__(...)`
+    def writeprocimg(self, device=None) -> bool:
         """
-        if not isinstance(counter_id, int):
-            raise TypeError("counter_id must be <class 'int'>")
-        if not 0 <= counter_id <= 15:
-            raise ValueError("counter_id must be 0 - 15")
+        Schreiben aller Outputs aller Devices ins Prozessabbild.
 
-        # Deviceposition + leer + Counter_ID
-        # ID-Bits: 7|6|5|4|3|2|1|0|15|14|13|12|11|10|9|8
-        self.__ioctl_arg = \
-            parentdevice._position.to_bytes(1, "little") \
-            + b'\x00' \
-            + (1 << counter_id).to_bytes(2, "little")
+        Devices mit aktiverem autorefresh werden ausgenommen!
 
+        :param device: nur auf einzelnes Device anwenden
+        :return: True, wenn Arbeiten an allen Devices erfolgreich waren
         """
-        IOCTL fuellt dieses struct, welches durch padding im Speicher nach
-        uint8_t ein byte frei hat. Es muessen also 4 Byte uebergeben werden
-        wobei das Bitfield die Byteorder little hat!!!
-
-        typedef struct SDIOResetCounterStr
-        {
-            uint8_t     i8uAddress;   // Address of module
-            uint16_t    i16uBitfield; // bitfield, if bit n is 1, reset
-        } SDIOResetCounter;
-        """
-
-        # Basisklasse laden
-        super().__init__(parentdevice, valuelist, iotype, byteorder, signed)
-
-    def reset(self) -> None:
-        """Setzt den Counter des Inputs zurueck."""
-        if self._parentdevice._modio._monitoring:
-            raise RuntimeError(
-                "can not reset counter, while system is in monitoring mode"
-            )
-        if self._parentdevice._modio._simulator:
+        if self._monitoring:
             raise RuntimeError(
-                "can not reset counter, while system is in simulator mode"
+                "can not write process image, while system is in monitoring "
+                "mode"
             )
 
-        if self._parentdevice._modio._run_on_pi:
-            # IOCTL auf dem RevPi
-            with self._parentdevice._modio._myfh_lck:
-                try:
-                    # Counter reset durchführen (Funktion K+20)
-                    ioctl(
-                        self._parentdevice._modio._myfh,
-                        19220, self.__ioctl_arg
-                    )
-                except Exception as e:
-                    self._parentdevice._modio._gotioerror("iorst", e)
-
-        elif hasattr(self._parentdevice._modio._myfh, "ioctl"):
-            # IOCTL über Netzwerk
-            with self._parentdevice._modio._myfh_lck:
-                try:
-                    self._parentdevice._modio._myfh.ioctl(
-                        19220, self.__ioctl_arg
-                    )
-                except Exception as e:
-                    self._parentdevice._modio._gotioerror("net_iorst", e)
-
+        if device is None:
+            mylist = self.device
         else:
-            # IOCTL in Datei simulieren
-            try:
-                # Set value durchführen (Funktion K+20)
-                self._parentdevice._modio._simulate_ioctl(
-                    19220, self.__ioctl_arg
-                )
-            except Exception as e:
-                self._parentdevice._modio._gotioerror("file_iorst", e)
+            dev = device if isinstance(device, devicemodule.Device) \
+                else self.device.__getitem__(device)
 
+            if dev._selfupdate:
+                raise RuntimeError(
+                    "can not write process image, while device '{0}|{1}'"
+                    "is in autorefresh mode".format(dev._position, dev._name)
+                )
+            mylist = [dev]
 
-class IntIOReplaceable(IntIO):
-    """Erweitert die IntIO-Klasse um die .replace_io Funktion."""
-
-    __slots__ = ()
-
-    def replace_io(self, name: str, frm: str, **kwargs) -> None:
-        """
-        Ersetzt bestehenden IO mit Neuem.
+        global_ex = None
+        for dev in mylist:
+            if dev._selfupdate:
+                # Do not update this device
+                continue
+
+            dev._filelock.acquire()
+
+            if dev._shared_procimg:
+                for io in dev._shared_write:
+                    if not io._write_to_procimg():
+                        global_ex = IOError(
+                            "error on shared procimg while write"
+                        )
+                dev._shared_write.clear()
+            else:
+                # Outpus auf Bus schreiben
+                self._myfh_lck.acquire()
+                try:
+                    self._myfh.seek(dev._slc_outoff.start)
+                    self._myfh.write(dev._ba_devdata[dev._slc_out])
+                except IOError as e:
+                    global_ex = e
+                finally:
+                    self._myfh_lck.release()
 
-        Wenn die kwargs fuer byteorder und defaultvalue nicht angegeben werden,
-        uebernimmt das System die Daten aus dem ersetzten IO.
+            dev._filelock.release()
 
-        Es darf nur ein einzelnes Formatzeichen 'frm' uebergeben werden. Daraus
-        wird dann die benoetigte Laenge an Bytes berechnet und der Datentyp
-        festgelegt. Moeglich sind:
-        - Bits / Bytes: ?, c, s
-        - Integer     : bB, hH, iI, lL, qQ
-        - Float       : e, f, d
-
-        Eine Ausnahme ist die Formatierung 's'. Hier koennen mehrere Bytes
-        zu einem langen IO zusammengefasst werden. Die Formatierung muss
-        '8s' fuer z.B. 8 Bytes sein - NICHT 'ssssssss'!
-
-        Wenn durch die Formatierung mehr Bytes benoetigt werden, als
-        der urspruenglige IO hat, werden die nachfolgenden IOs ebenfalls
-        verwendet und entfernt.
-
-        :param name: Name des neuen Inputs
-        :param frm: struct formatierung (1 Zeichen) oder 'ANZAHLs' z.B. '8s'
-        :param kwargs: Weitere Parameter
-
-        - bmk: interne Bezeichnung fuer IO
-        - bit: Registriert IO als <class 'bool'> am angegebenen Bit im Byte
-        - byteorder: Byteorder fuer den IO, Standardwert=little
-        - wordorder: Wordorder wird vor byteorder angewendet
-        - defaultvalue: Standardwert fuer IO
-        - event: Funktion fuer Eventhandling registrieren
-        - delay: Verzoegerung in ms zum Ausloesen wenn Wert gleich bleibt
-        - edge: Event ausfuehren bei RISING, FALLING or BOTH Wertaenderung
-        - as_thread: Fuehrt die event-Funktion als RevPiCallback-Thread aus
-        - prefire: Ausloesen mit aktuellem Wert, wenn mainloop startet
-
-        `<https://docs.python.org/3/library/struct.html#format-characters>`_
-        """
-        # StructIO erzeugen
-        io_new = StructIO(
-            self,
-            name,
-            frm,
-            **kwargs
-        )
+        if self._buffedwrite:
+            try:
+                self._myfh.flush()
+            except IOError as e:
+                global_ex = e
+
+        if global_ex:
+            self._gotioerror("writeprocimg", global_ex)
+            return False
 
-        # StructIO in IO-Liste einfügen
-        self._parentdevice._modio.io._private_register_new_io_object(io_new)
+        return True
 
-        # Optional Event eintragen
-        reg_event = kwargs.get("event", None)
-        if reg_event is not None:
-            io_new.reg_event(
-                reg_event,
-                kwargs.get("delay", 0),
-                kwargs.get("edge", BOTH),
-                kwargs.get("as_thread", False)
-            )
+    debug = property(_get_debug, _set_debug)
+    configrsc = property(_get_configrsc)
+    cycletime = property(_get_cycletime, _set_cycletime)
+    ioerrors = property(_get_ioerrors)
+    length = property(_get_length)
+    maxioerrors = property(_get_maxioerrors, _set_maxioerrors)
+    monitoring = property(_get_monitoring)
+    procimg = property(_get_procimg)
+    replace_io_file = property(_get_replace_io_file)
+    simulator = property(_get_simulator)
 
 
-class StructIO(IOBase):
+class RevPiModIOSelected(RevPiModIO):
     """
-    Klasse fuer den Zugriff auf Daten ueber ein definierten struct.
+    Klasse fuer die Verwaltung einzelner Devices aus piCtory.
 
-    Sie stellt ueber struct die Werte in der gewuenschten Formatierung
-    bereit. Der struct-Formatwert wird bei der Instantiierung festgelegt.
+    Diese Klasse uebernimmt nur angegebene Devices der piCtory Konfiguration
+    und bildet sie inkl. IOs ab. Sie uebernimmt die exklusive Verwaltung des
+    Adressbereichs im Prozessabbild an dem sich die angegebenen Devices
+    befinden und stellt sicher, dass die Daten synchron sind.
     """
 
-    __slots__ = "__frm", "_parentio_address", "_parentio_defaultvalue", \
-        "_parentio_length", "_parentio_name", "_wordorder"
-
-    def __init__(self, parentio, name: str, frm: str, **kwargs):
-        """
-        Erstellt einen IO mit struct-Formatierung.
+    __slots__ = ()
 
-        :param parentio: ParentIO Objekt, welches ersetzt wird
-        :param name: Name des neuen IO
-        :param frm: struct formatierung (1 Zeichen) oder 'ANZAHLs' z.B. '8s'
-        :param kwargs: Weitere Parameter:
-            - bmk: Bezeichnung fuer IO
-            - bit: Registriert IO als <class 'bool'> am angegebenen Bit im Byte
-            - byteorder: Byteorder fuer IO, Standardwert vom ersetzten IO
-            - wordorder: Wordorder wird vor byteorder angewendet
-            - defaultvalue: Standardwert fuer IO, Standard vom ersetzten IO
-        """
-        # Structformatierung prüfen
-        regex = rematch("^([0-9]*s|[cbB?hHiIlLqQefd])$", frm)
-
-        if regex is not None:
-            # Byteorder prüfen und übernehmen
-            byteorder = kwargs.get("byteorder", parentio._byteorder)
-            if byteorder not in ("little", "big"):
-                raise ValueError("byteorder must be 'little' or 'big'")
-            bofrm = "<" if byteorder == "little" else ">"
-            self._wordorder = kwargs.get("wordorder", None)
+    def __init__(
+            self, deviceselection, autorefresh=False, monitoring=False,
+            syncoutputs=True, procimg=None, configrsc=None,
+            simulator=False, debug=True, replace_io_file=None,
+            shared_procimg=False, direct_output=False):
+        """
+        Instantiiert nur fuer angegebene Devices die Grundfunktionen.
+
+        Der Parameter deviceselection kann eine einzelne
+        Device Position / einzelner Device Name sein oder eine Liste mit
+        mehreren Positionen / Namen
 
-            # Namen des parent fuer export merken
-            self._parentio_name = parentio._name
+        :param deviceselection: Positionsnummer oder Devicename
+        :ref: :func:`RevPiModIO.__init__(...)`
+        """
+        super().__init__(
+            autorefresh, monitoring, syncoutputs, procimg, configrsc,
+            simulator, debug, replace_io_file, shared_procimg, direct_output
+        )
 
-            if frm == "?":
-                if self._wordorder:
-                    raise ValueError(
-                        "you can not use wordorder for bit based ios"
-                    )
-                bitaddress = kwargs.get("bit", 0)
-                max_bits = parentio._length * 8
-                if not (0 <= bitaddress < max_bits):
-                    raise ValueError(
-                        "bitaddress must be a value between 0 and {0}"
-                        "".format(max_bits - 1)
-                    )
-                bitlength = 1
+        if type(deviceselection) is not DevSelect:
+            # Convert to tuple
+            if type(deviceselection) not in (list, tuple):
+                deviceselection = (deviceselection,)
 
-                # Bitweise Ersetzung erfordert diese Informationen zusätzlich
-                if parentio._byteorder == byteorder:
-                    self._parentio_defaultvalue = parentio._defaultvalue
-                else:
-                    self._parentio_defaultvalue = parentio._defaultvalue[::-1]
-                self._parentio_address = parentio.address
-                self._parentio_length = parentio._length
-            else:
-                byte_length = struct.calcsize(bofrm + frm)
-                bitaddress = ""
-                bitlength = byte_length * 8
-                self._parentio_address = None
-                self._parentio_defaultvalue = None
-                self._parentio_length = None
-                if self._wordorder:
-                    if self._wordorder not in ("little", "big"):
-                        raise ValueError("wordorder must be 'little' or 'big'")
-                    if byte_length % 2 != 0:
-                        raise ValueError(
-                            "the byte length of new io must must be even to "
-                            "use wordorder"
-                        )
+            # Automatic search for name and position depends on type int / str
+            self._devselect = DevSelect(DeviceType.IGNORED, "", deviceselection)
 
-            # [name,default,anzbits,adressbyte,export,adressid,bmk,bitaddress]
-            valuelist = [
-                name,
-                # Darf nur bei StructIO None sein, wird nur dann berechnet
-                kwargs.get("defaultvalue", None),
-                bitlength,
-                parentio._slc_address.start,
-                False,
-                str(parentio._slc_address.start).rjust(4, "0"),
-                kwargs.get("bmk", ""),
-                bitaddress
-            ]
         else:
-            raise ValueError(
-                "parameter frm has to be a single sign from [cbB?hHiIlLqQefd] "
-                "or 'COUNTs' e.g. '8s'"
-            )
+            self._devselect = deviceselection
 
-        # Basisklasse instantiieren
-        super().__init__(
-            parentio._parentdevice,
-            valuelist,
-            parentio._iotype,
-            byteorder,
-            frm == frm.lower()
-        )
-        self.__frm = bofrm + frm
-        if "export" in kwargs:
-            # Use export property to remember given value for export
-            self.export = kwargs["export"]
-        else:
-            # User could change parent IO settings before replace to force
-            # export, so use parent settings for the new IO
-            self._export = parentio._export
-
-        # Platz für neuen IO prüfen
-        if not (self._slc_address.start >=
-                parentio._parentdevice._dict_slc[parentio._iotype].start and
-                self._slc_address.stop <=
-                parentio._parentdevice._dict_slc[parentio._iotype].stop):
-            raise BufferError(
-                "registered value does not fit process image scope"
-            )
+        self._configure(self.get_jconfigrsc())
 
-    def __call__(self, value=None):
-        if value is None:
-            # Inline get_structdefaultvalue()
-            if self._bitshift:
-                return self.get_value()
-            if self._wordorder == "little" and self._length > 2:
-                return struct.unpack(
-                    self.__frm,
-                    self._swap_word_order(self.get_value()),
-                )[0]
-            return struct.unpack(self.__frm, self.get_value())[0]
-        else:
-            # Inline set_structvalue()
-            if self._bitshift:
-                self.set_value(value)
-            elif self._wordorder == "little" and self._length > 2:
-                self.set_value(
-                    self._swap_word_order(struct.pack(self.__frm, value))
+        if len(self.device) == 0:
+            if self._devselect.type:
+                raise DeviceNotFoundError(
+                    "could not find ANY given {0} devices in config"
+                    "".format(self._devselect.type)
                 )
             else:
-                self.set_value(struct.pack(self.__frm, value))
-
-    def _get_frm(self) -> str:
-        """
-        Ruft die struct Formatierung ab.
-
-        :return: struct Formatierung
-        """
-        return self.__frm[1:]
-
-    def _get_signed(self) -> bool:
-        """
-        Ruft ab, ob der Wert Vorzeichenbehaftet behandelt werden soll.
-
-        :return: True, wenn Vorzeichenbehaftet
-        """
-        return self._signed
-
-    @staticmethod
-    def _swap_word_order(bytes_to_swap) -> bytes:
-        """
-        Swap word order of given bytes.
-
-        :param bytes_to_swap: Already length checked bytes to swap words
-        :return: Bytes with swapped word order
-        """
-        array_length = len(bytes_to_swap)
-        swap_array = bytearray(bytes_to_swap)
-        for i in range(0, array_length // 2, 2):
-            swap_array[-i - 2:array_length - i], swap_array[i:i + 2] = \
-                swap_array[i:i + 2], swap_array[-i - 2:array_length - i]
-        return bytes(swap_array)
-
-    def get_structdefaultvalue(self):
-        """
-        Gibt die Defaultvalue mit struct Formatierung zurueck.
-
-        :return: Defaultvalue vom Typ der struct-Formatierung
-        """
-        if self._bitshift:
-            return self._defaultvalue
-        if self._wordorder == "little" and self._length > 2:
-            return struct.unpack(
-                self.__frm,
-                self._swap_word_order(self._defaultvalue),
-            )[0]
-        return struct.unpack(self.__frm, self._defaultvalue)[0]
-
-    def get_wordorder(self) -> str:
-        """
-        Gibt die wordorder für diesen IO zurück.
-
-        :return: "little", "big" or "ignored"
-        """
-        return self._wordorder or "ignored"
+                raise DeviceNotFoundError(
+                    "could not find ANY given devices in config"
+                )
+        elif not self._devselect.other_device_key \
+                and len(self.device) != len(self._devselect.values):
+            if self._devselect.type:
+                raise DeviceNotFoundError(
+                    "could not find ALL given {0} devices in config"
+                    "".format(self._devselect.type)
+                )
+            else:
+                raise DeviceNotFoundError(
+                    "could not find ALL given devices in config"
+                )
 
-    def get_structvalue(self):
-        """
-        Gibt den Wert mit struct Formatierung zurueck.
 
-        :return: Wert vom Typ der struct-Formatierung
-        """
-        if self._bitshift:
-            return self.get_value()
-        if self._wordorder == "little" and self._length > 2:
-            return struct.unpack(
-                self.__frm,
-                self._swap_word_order(self.get_value()),
-            )[0]
-        return struct.unpack(self.__frm, self.get_value())[0]
+class RevPiModIODriver(RevPiModIOSelected):
+    """
+    Klasse um eigene Treiber fuer die virtuellen Devices zu erstellen.
 
-    def set_structvalue(self, value):
-        """
-        Setzt den Wert mit struct Formatierung.
+    Mit dieser Klasse werden nur angegebene Virtuelle Devices mit RevPiModIO
+    verwaltet. Bei Instantiierung werden automatisch die Inputs und Outputs
+    verdreht, um das Schreiben der Inputs zu ermoeglichen. Die Daten koennen
+    dann ueber logiCAD an den Devices abgerufen werden.
+    """
 
-        :param value: Wert vom Typ der struct-Formatierung
-        """
-        if self._bitshift:
-            self.set_value(value)
-        elif self._wordorder == "little" and self._length > 2:
-            self.set_value(
-                self._swap_word_order(struct.pack(self.__frm, value))
-            )
-        else:
-            self.set_value(struct.pack(self.__frm, value))
+    __slots__ = ()
 
-    defaultvalue = property(get_structdefaultvalue)
-    frm = property(_get_frm)
-    signed = property(_get_signed)
-    value = property(get_structvalue, set_structvalue)
-    wordorder = property(get_wordorder)
+    def __init__(
+            self, virtdev, autorefresh=False,
+            syncoutputs=True, procimg=None, configrsc=None, debug=True,
+            replace_io_file=None, shared_procimg=False, direct_output=False):
+        """
+        Instantiiert die Grundfunktionen.
+
+        Parameter 'monitoring' und 'simulator' stehen hier nicht zur
+        Verfuegung, da diese automatisch gesetzt werden.
+
+        :param virtdev: Virtuelles Device oder mehrere als <class 'list'>
+        :ref: :func:`RevPiModIO.__init__()`
+        """
+        # Parent mit monitoring=False und simulator=True laden
+        if type(virtdev) not in (list, tuple):
+            virtdev = (virtdev,)
+        dev_select = DevSelect(DeviceType.VIRTUAL, "", virtdev)
+        super().__init__(
+            dev_select, autorefresh, False, syncoutputs, procimg, configrsc,
+            True, debug, replace_io_file, shared_procimg, direct_output
+        )
 
 
-class MemIO(IOBase):
+def run_plc(
+        func, cycletime=50, replace_io_file=None, debug=True,
+        procimg=None, configrsc=None):
     """
-    Erstellt einen IO für die Memory Werte in piCtory.
+    Run Revoluton Pi as real plc with cycle loop and exclusive IO access.
 
-    Dieser Typ ist nur für lesenden Zugriff vorgesehen und kann verschiedene
-    Datentypen über .value zurückgeben. Damit hat man nun auch Zugriff
-    auf Strings, welche in piCtory vergeben werden.
+    This function is just a shortcut to run the module in cycle loop mode and
+    handle the program exit signal. You will access the .io, .core, .device
+    via the cycletools in your cycle function.
+
+    Shortcut for this source code:
+        rpi = RevPiModIO(autorefresh=True, replace_io_file=..., debug=...)
+        rpi.handlesignalend()
+        return rpi.cycleloop(func, cycletime)
+
+    :param func: Function to run every set milliseconds
+    :param cycletime: Cycle time in milliseconds
+    :param replace_io_file: Load replace IO configuration from file
+    :param debug: Print all warnings and detailed error messages
+    :param procimg: Use different process image
+    :param configrsc: Use different piCtory configuration
+    :return: None or the return value of the cycle function
     """
-
-    def get_variantvalue(self):
-        val = bytes(self._defaultvalue)
-
-        if self._bitlength > 64:
-            # STRING
-            try:
-                val = val.strip(b'\x00').decode()
-            except Exception:
-                pass
-            return val
-
-        else:
-            # INT
-            return int.from_bytes(val, self._byteorder, signed=self._signed)
-
-    defaultvalue = property(get_variantvalue)
-    value = property(get_variantvalue)
+    rpi = RevPiModIO(
+        autorefresh=True,
+        replace_io_file=replace_io_file,
+        debug=debug,
+        procimg=procimg,
+        configrsc=configrsc,
+    )
+    rpi.handlesignalend()
+    return rpi.cycleloop(func, cycletime)
```

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/netio.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/netio.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/pictory.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/pictory.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,14 +39,15 @@
     AIO = 103
     MIO = 118
 
     REVPI_CORE = 95
     REVPI_COMPACT = 104
     REVPI_CONNECT = 105
     REVPI_FLAT = 135
+    REVPI_CONNECT_4 = 136
 
 
 class DeviceType:
     """Module key "type" in piCtory file."""
     IGNORED = ""
     BASE = "BASE"  # Core devices
     EDGE = "EDGE"  # Gateways
```

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2/summary.py` & `revpimodio2-2.6.0rc6/src/revpimodio2/summary.py`

 * *Files identical despite different names*

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2.egg-info/PKG-INFO` & `revpimodio2-2.6.0rc6/src/revpimodio2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: revpimodio2
-Version: 2.6.0rc5
+Version: 2.6.0rc6
 Summary: Python3 programming for RevolutionPi of KUNBUS GmbH
 Home-page: https://revpimodio.org/
 Author: Sven Sager
 Author-email: akira@narux.de
 Maintainer: Sven Sager
 Maintainer-email: akira@revpimodio.org
 License: LGPLv2
```

### Comparing `revpimodio2-2.6.0rc5/src/revpimodio2.egg-info/SOURCES.txt` & `revpimodio2-2.6.0rc6/src/revpimodio2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

