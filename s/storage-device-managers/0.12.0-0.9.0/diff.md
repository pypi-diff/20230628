# Comparing `tmp/storage_device_managers-0.12.0.tar.gz` & `tmp/storage_device_managers-0.9.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "storage_device_managers-0.12.0.tar", max compression
+gzip compressed data, was "storage_device_managers-0.9.0.tar", max compression
```

## Comparing `storage_device_managers-0.12.0.tar` & `storage_device_managers-0.9.0.tar`

### file list

```diff
@@ -1,5 +1,6 @@
--rw-r--r--   0        0        0    35106 2023-06-26 07:28:21.992530 storage_device_managers-0.12.0/LICENSE
--rw-r--r--   0        0        0     1250 2023-06-28 08:44:20.432646 storage_device_managers-0.12.0/pyproject.toml
--rw-r--r--   0        0        0    12973 2023-06-28 08:41:13.499051 storage_device_managers-0.12.0/src/storage_device_managers/__init__.py
--rw-r--r--   0        0        0        0 2023-06-26 07:28:21.996530 storage_device_managers-0.12.0/src/storage_device_managers/py.typed
--rw-r--r--   0        0        0      646 1970-01-01 00:00:00.000000 storage_device_managers-0.12.0/PKG-INFO
+-rw-r--r--   0        0        0    35106 2023-06-15 19:36:56.857826 storage_device_managers-0.9.0/LICENSE
+-rw-r--r--   0        0        0     1249 2023-06-15 21:36:15.761780 storage_device_managers-0.9.0/pyproject.toml
+-rw-r--r--   0        0        0      777 2023-06-15 20:47:57.614397 storage_device_managers-0.9.0/src/storage_device_managers/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-15 20:47:57.614397 storage_device_managers-0.9.0/src/storage_device_managers/py.typed
+-rw-r--r--   0        0        0     8726 2023-06-15 21:31:36.242303 storage_device_managers-0.9.0/src/storage_device_managers/storage_device_managers.py
+-rw-r--r--   0        0        0      645 1970-01-01 00:00:00.000000 storage_device_managers-0.9.0/PKG-INFO
```

### Comparing `storage_device_managers-0.12.0/LICENSE` & `storage_device_managers-0.9.0/LICENSE`

 * *Files identical despite different names*

### Comparing `storage_device_managers-0.12.0/pyproject.toml` & `storage_device_managers-0.9.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "storage-device-managers"
-version = "0.12.0"
+version = "0.9.0"
 description = "Helpful context managers for managing decryption and mounts of storage devices"
 authors = ["Max Görner <max@familie-goerner.eu>"]
 license = "GPL-3.0-or-later"
 
 [tool.poetry.dependencies]
 python = ">=3.8.1,<3.12"
 loguru = "^0.7.0"
```

### Comparing `storage_device_managers-0.12.0/PKG-INFO` & `storage_device_managers-0.9.0/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: storage-device-managers
-Version: 0.12.0
+Version: 0.9.0
 Summary: Helpful context managers for managing decryption and mounts of storage devices
 License: GPL-3.0-or-later
 Author: Max Görner
 Author-email: max@familie-goerner.eu
 Requires-Python: >=3.8.1,<3.12
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Programming Language :: Python :: 3
```

