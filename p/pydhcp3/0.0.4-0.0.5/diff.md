# Comparing `tmp/pydhcp3-0.0.4.tar.gz` & `tmp/pydhcp3-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pydhcp3-0.0.4.tar", last modified: Sun Jun 25 08:07:51 2023, max compression
+gzip compressed data, was "pydhcp3-0.0.5.tar", last modified: Wed Jun 28 01:51:21 2023, max compression
```

## Comparing `pydhcp3-0.0.4.tar` & `pydhcp3-0.0.5.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:07:51.724495 pydhcp3-0.0.4/
--rw-r--r--   0 andrew    (1000) andrew    (1000)     1075 2023-04-24 00:15:16.000000 pydhcp3-0.0.4/LICENSE
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      720 2023-06-25 08:07:51.724495 pydhcp3-0.0.4/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      249 2023-04-24 00:07:53.000000 pydhcp3-0.0.4/README.md
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:07:51.720495 pydhcp3-0.0.4/pydhcp/
--rw-r--r--   0 andrew    (1000) andrew    (1000)       37 2023-04-21 08:22:54.000000 pydhcp3-0.0.4/pydhcp/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     3818 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/base.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)     2476 2023-04-20 03:29:25.000000 pydhcp3-0.0.4/pydhcp/enum.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)     1735 2023-05-04 21:09:56.000000 pydhcp3-0.0.4/pydhcp/exceptions.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:07:51.720495 pydhcp3-0.0.4/pydhcp/v4/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      758 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v4/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     8923 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v4/enum.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     5219 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v4/message.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     5074 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v4/options.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:07:51.724495 pydhcp3-0.0.4/pydhcp/v4/server/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      350 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v4/server/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     8408 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v4/server/handlers.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)    10219 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v4/server/server.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:07:51.724495 pydhcp3-0.0.4/pydhcp/v6/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      682 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v6/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2372 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v6/duid.py
--rw-r--r--   0 andrew    (1000) andrew    (1000)     1452 2023-04-21 08:20:56.000000 pydhcp3-0.0.4/pydhcp/v6/enum.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     4332 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v6/message.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     5039 2023-06-25 08:07:07.000000 pydhcp3-0.0.4/pydhcp/v6/options.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:07:51.724495 pydhcp3-0.0.4/pydhcp3.egg-info/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      720 2023-06-25 08:07:51.000000 pydhcp3-0.0.4/pydhcp3.egg-info/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      517 2023-06-25 08:07:51.000000 pydhcp3-0.0.4/pydhcp3.egg-info/SOURCES.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-25 08:07:51.000000 pydhcp3-0.0.4/pydhcp3.egg-info/dependency_links.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       48 2023-06-25 08:07:51.000000 pydhcp3-0.0.4/pydhcp3.egg-info/requires.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        7 2023-06-25 08:07:51.000000 pydhcp3-0.0.4/pydhcp3.egg-info/top_level.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-25 08:07:51.724495 pydhcp3-0.0.4/setup.cfg
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      795 2023-06-25 08:07:26.000000 pydhcp3-0.0.4/setup.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:51:21.288904 pydhcp3-0.0.5/
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     1075 2023-04-24 00:15:16.000000 pydhcp3-0.0.5/LICENSE
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      720 2023-06-28 01:51:21.288904 pydhcp3-0.0.5/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      249 2023-04-24 00:07:53.000000 pydhcp3-0.0.5/README.md
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:51:21.284904 pydhcp3-0.0.5/pydhcp/
+-rw-r--r--   0 andrew    (1000) andrew    (1000)       37 2023-04-21 08:22:54.000000 pydhcp3-0.0.5/pydhcp/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     3818 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/base.py
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     2476 2023-04-20 03:29:25.000000 pydhcp3-0.0.5/pydhcp/enum.py
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     1735 2023-05-04 21:09:56.000000 pydhcp3-0.0.5/pydhcp/exceptions.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:51:21.284904 pydhcp3-0.0.5/pydhcp/v4/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      758 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v4/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     8923 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v4/enum.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     5219 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v4/message.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     5432 2023-06-28 01:50:43.000000 pydhcp3-0.0.5/pydhcp/v4/options.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:51:21.284904 pydhcp3-0.0.5/pydhcp/v4/server/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      350 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v4/server/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     8408 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v4/server/handlers.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)    10219 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v4/server/server.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:51:21.284904 pydhcp3-0.0.5/pydhcp/v6/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      682 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v6/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2372 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v6/duid.py
+-rw-r--r--   0 andrew    (1000) andrew    (1000)     1452 2023-04-21 08:20:56.000000 pydhcp3-0.0.5/pydhcp/v6/enum.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     4332 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v6/message.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     5039 2023-06-25 08:07:07.000000 pydhcp3-0.0.5/pydhcp/v6/options.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:51:21.288904 pydhcp3-0.0.5/pydhcp3.egg-info/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      720 2023-06-28 01:51:21.000000 pydhcp3-0.0.5/pydhcp3.egg-info/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      517 2023-06-28 01:51:21.000000 pydhcp3-0.0.5/pydhcp3.egg-info/SOURCES.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-28 01:51:21.000000 pydhcp3-0.0.5/pydhcp3.egg-info/dependency_links.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       48 2023-06-28 01:51:21.000000 pydhcp3-0.0.5/pydhcp3.egg-info/requires.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        7 2023-06-28 01:51:21.000000 pydhcp3-0.0.5/pydhcp3.egg-info/top_level.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-28 01:51:21.288904 pydhcp3-0.0.5/setup.cfg
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      795 2023-06-28 01:51:08.000000 pydhcp3-0.0.5/setup.py
```

### Comparing `pydhcp3-0.0.4/LICENSE` & `pydhcp3-0.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/PKG-INFO` & `pydhcp3-0.0.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydhcp3
-Version: 0.0.4
+Version: 0.0.5
 Summary: Simple Python DHCP Library. DHCP Packet-Parsing/Client/Server
 Home-page: https://github.com/imgurbot12/pydhcp
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pydhcp3-0.0.4/pydhcp/base.py` & `pydhcp3-0.0.5/pydhcp/base.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/enum.py` & `pydhcp3-0.0.5/pydhcp/enum.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/exceptions.py` & `pydhcp3-0.0.5/pydhcp/exceptions.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v4/__init__.py` & `pydhcp3-0.0.5/pydhcp/v4/__init__.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v4/enum.py` & `pydhcp3-0.0.5/pydhcp/v4/enum.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v4/message.py` & `pydhcp3-0.0.5/pydhcp/v4/message.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v4/options.py` & `pydhcp3-0.0.5/pydhcp/v4/options.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 """
 DHCPv4 Option Implementations
 """
 from typing import ClassVar, List, SupportsInt
 from typing_extensions import Annotated
+from warnings import warn
 
 from pystructs import *
 from pyderive import dataclass
 
 from .enum import OptionCode, MessageType
 from ..enum import Arch, StatusCode
 from ..base import DHCPOption, DHCPOptionList, Seconds
@@ -80,14 +81,23 @@
     return OptStruct(option.opcode, content).encode(ctx)
 
 #** Classes **#
 
 class OptStruct(Struct):
     code:  OptionCodeInt
     value: Annotated[bytes, SizedBytes[U8]]
+ 
+    def __post_init__(self):
+        """warn when value is too long and truncate"""
+        if len(self.value) <= 255:
+            return
+        code       = self.code
+        vlen       = len(self.value)
+        self.value = self.value[:252] + b'...'
+        warn(f'{code!r} value too long {vlen}. truncating!', RuntimeWarning)
 
 @dataclass
 class Option(DHCPOption):
     """DHCPv4 BaseClass Option Definition"""
     opcode: ClassVar[OptionCode] = OptionCode.OptionPad
 
 class OptionList(DHCPOptionList):
```

### Comparing `pydhcp3-0.0.4/pydhcp/v4/server/handlers.py` & `pydhcp3-0.0.5/pydhcp/v4/server/handlers.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v4/server/server.py` & `pydhcp3-0.0.5/pydhcp/v4/server/server.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v6/__init__.py` & `pydhcp3-0.0.5/pydhcp/v6/__init__.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v6/duid.py` & `pydhcp3-0.0.5/pydhcp/v6/duid.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v6/enum.py` & `pydhcp3-0.0.5/pydhcp/v6/enum.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v6/message.py` & `pydhcp3-0.0.5/pydhcp/v6/message.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp/v6/options.py` & `pydhcp3-0.0.5/pydhcp/v6/options.py`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/pydhcp3.egg-info/PKG-INFO` & `pydhcp3-0.0.5/pydhcp3.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydhcp3
-Version: 0.0.4
+Version: 0.0.5
 Summary: Simple Python DHCP Library. DHCP Packet-Parsing/Client/Server
 Home-page: https://github.com/imgurbot12/pydhcp
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pydhcp3-0.0.4/pydhcp3.egg-info/SOURCES.txt` & `pydhcp3-0.0.5/pydhcp3.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pydhcp3-0.0.4/setup.py` & `pydhcp3-0.0.5/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages
 
 with open("README.md", "r") as f:
     readme = f.read()
 
 setup(
     name='pydhcp3',
-    version='0.0.4',
+    version='0.0.5',
     license='MIT',
     author='Andrew Scott',
     author_email='imgurbot12@gmail.com',
     url='https://github.com/imgurbot12/pydhcp',
     description="Simple Python DHCP Library. DHCP Packet-Parsing/Client/Server",
     long_description=readme,
     long_description_content_type="text/markdown",
```

