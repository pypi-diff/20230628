# Comparing `tmp/tarvis-common-0.9.7.tar.gz` & `tmp/tarvis-common-0.9.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tarvis-common-0.9.7.tar", last modified: Thu May 25 11:13:13 2023, max compression
+gzip compressed data, was "tarvis-common-0.9.8.tar", last modified: Wed Jun 28 14:50:34 2023, max compression
```

## Comparing `tarvis-common-0.9.7.tar` & `tarvis-common-0.9.8.tar`

### file list

```diff
@@ -1,36 +1,37 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/
--rw-r--r--   0 root         (0) root         (0)     1067 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/LICENSE.txt
--rw-r--r--   0 root         (0) root         (0)      378 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       24 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/README.md
--rw-r--r--   0 root         (0) root         (0)       38 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/setup.cfg
--rw-r--r--   0 root         (0) root         (0)      751 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.293001 tarvis-common-0.9.7/tarvis/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.293001 tarvis-common-0.9.7/tarvis/common/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.293001 tarvis-common-0.9.7/tarvis/common/asyncio/
--rw-r--r--   0 root         (0) root         (0)      816 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/asyncio/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.293001 tarvis-common-0.9.7/tarvis/common/cache/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.293001 tarvis-common-0.9.7/tarvis/common/cache/local/
--rw-r--r--   0 root         (0) root         (0)     3885 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/cache/local/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis/common/config/
--rw-r--r--   0 root         (0) root         (0)     1698 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/config/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis/common/environ/
--rw-r--r--   0 root         (0) root         (0)     1987 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/environ/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis/common/logging/
--rw-r--r--   0 root         (0) root         (0)     5793 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/logging/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis/common/monitoring/
--rw-r--r--   0 root         (0) root         (0)     4398 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/monitoring/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis/common/secrets/
--rw-r--r--   0 root         (0) root         (0)     2551 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/secrets/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis/common/time/
--rw-r--r--   0 root         (0) root         (0)     6436 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/time/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis/common/trading/
--rw-r--r--   0 root         (0) root         (0)     8864 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/tarvis/common/trading/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/tarvis_common.egg-info/
--rw-r--r--   0 root         (0) root         (0)      378 2023-05-25 11:13:13.000000 tarvis-common-0.9.7/tarvis_common.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      564 2023-05-25 11:13:13.000000 tarvis-common-0.9.7/tarvis_common.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-05-25 11:13:13.000000 tarvis-common-0.9.7/tarvis_common.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      208 2023-05-25 11:13:13.000000 tarvis-common-0.9.7/tarvis_common.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        7 2023-05-25 11:13:13.000000 tarvis-common-0.9.7/tarvis_common.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-25 11:13:13.297001 tarvis-common-0.9.7/test/
--rw-r--r--   0 root         (0) root         (0)      297 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/test/test_config.py
--rw-r--r--   0 root         (0) root         (0)      191 2023-05-25 11:13:02.000000 tarvis-common-0.9.7/test/test_secrets.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/
+-rw-r--r--   0 root         (0) root         (0)     1067 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/LICENSE.txt
+-rw-r--r--   0 root         (0) root         (0)      378 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       24 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/README.md
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)      751 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.184755 tarvis-common-0.9.8/tarvis/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.184755 tarvis-common-0.9.8/tarvis/common/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.184755 tarvis-common-0.9.8/tarvis/common/asyncio/
+-rw-r--r--   0 root         (0) root         (0)      816 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/asyncio/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.184755 tarvis-common-0.9.8/tarvis/common/cache/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/cache/local/
+-rw-r--r--   0 root         (0) root         (0)     3982 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/cache/local/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/config/
+-rw-r--r--   0 root         (0) root         (0)     1698 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/config/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/environ/
+-rw-r--r--   0 root         (0) root         (0)     1987 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/environ/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/logging/
+-rw-r--r--   0 root         (0) root         (0)     6252 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/logging/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/monitoring/
+-rw-r--r--   0 root         (0) root         (0)     4398 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/monitoring/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/secrets/
+-rw-r--r--   0 root         (0) root         (0)     2551 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/secrets/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/time/
+-rw-r--r--   0 root         (0) root         (0)     6436 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/time/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis/common/trading/
+-rw-r--r--   0 root         (0) root         (0)    11112 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/tarvis/common/trading/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/tarvis_common.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      378 2023-06-28 14:50:34.000000 tarvis-common-0.9.8/tarvis_common.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      589 2023-06-28 14:50:34.000000 tarvis-common-0.9.8/tarvis_common.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:50:34.000000 tarvis-common-0.9.8/tarvis_common.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      208 2023-06-28 14:50:34.000000 tarvis-common-0.9.8/tarvis_common.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        7 2023-06-28 14:50:34.000000 tarvis-common-0.9.8/tarvis_common.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:50:34.188756 tarvis-common-0.9.8/test/
+-rw-r--r--   0 root         (0) root         (0)     2450 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/test/test_cache_local.py
+-rw-r--r--   0 root         (0) root         (0)      297 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/test/test_config.py
+-rw-r--r--   0 root         (0) root         (0)      191 2023-06-28 14:50:23.000000 tarvis-common-0.9.8/test/test_secrets.py
```

### Comparing `tarvis-common-0.9.7/LICENSE.txt` & `tarvis-common-0.9.8/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `tarvis-common-0.9.7/setup.py` & `tarvis-common-0.9.8/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -4,15 +4,15 @@
     requirements = requirements_file.read().splitlines()
 
 with open("README.md") as description_file:
     long_description = description_file.read()
 
 setup(
     name="tarvis-common",
-    version="0.9.7",
+    version="0.9.8",
     author="Tarvis Labs",
     author_email="python@tarvislabs.com",
     url="https://tarvislabs.com/",
     description="Tarvis Common Library",
     long_description=long_description,
     long_description_content_type="text/markdown",
     license="MIT",
```

### Comparing `tarvis-common-0.9.7/tarvis/common/asyncio/__init__.py` & `tarvis-common-0.9.8/tarvis/common/asyncio/__init__.py`

 * *Files identical despite different names*

### Comparing `tarvis-common-0.9.7/tarvis/common/cache/local/__init__.py` & `tarvis-common-0.9.8/tarvis/common/cache/local/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 from collections import OrderedDict
 from dependency_injector.wiring import Provide, inject
 import marshal
-import objsize
+from objsize import get_deep_size
 import sys
 from tarvis.common import time
 from threading import Lock
 
 
 class LocalCacheEntry:
     def __init__(self, value, ttl: float | None, size: int):
@@ -14,15 +14,15 @@
         if ttl is None:
             self.expiration = None
         else:
             self.expiration = time.time() + ttl
 
     def is_expired(self) -> bool:
         if self.expiration is not None:
-            return time.time() < self.expiration
+            return time.time() > self.expiration
         return False
 
 
 class LocalCache:
     def __init__(
         self,
         default_ttl: float | None = None,
@@ -56,15 +56,18 @@
                 entry = self._cache.pop(key)
                 self._size -= entry.size
                 self._item_count -= 1
             except KeyError:
                 pass
             if ttl is None:
                 ttl = self._default_ttl
-            entry_size = len(key) + objsize.get_deep_size(value)
+            if self._max_size is None:
+                entry_size = 0
+            else:
+                entry_size = get_deep_size(key, value)
             entry = LocalCacheEntry(value, ttl, entry_size)
             self._cache[key] = entry
             self._size += entry.size
             self._item_count += 1
             if self._item_count > self._max_items:
                 key, entry = self._cache.popitem(last=False)
                 self._size -= entry.size
```

### Comparing `tarvis-common-0.9.7/tarvis/common/config/__init__.py` & `tarvis-common-0.9.8/tarvis/common/config/__init__.py`

 * *Files identical despite different names*

### Comparing `tarvis-common-0.9.7/tarvis/common/environ/__init__.py` & `tarvis-common-0.9.8/tarvis/common/environ/__init__.py`

 * *Files identical despite different names*

### Comparing `tarvis-common-0.9.7/tarvis/common/logging/__init__.py` & `tarvis-common-0.9.8/tarvis/common/logging/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,8 +1,9 @@
 import copy
+from decimal import Decimal
 from dependency_injector.wiring import Provide, inject
 import io
 import json
 import logging
 from logging import Handler, StreamHandler
 import os
 from pendulum.tz import UTC
@@ -47,15 +48,28 @@
         super().__init__(fmt="%(asctime)s %(levelname)s %(name)s %(message)s")
 
     def formatTime(self, record, datefmt=None):
         ct = datetime.fromtimestamp(record.created, UTC)
         return ct.to_iso8601_string()
 
 
-# Workaround for GCP's structured logging throwing away the extra dictionary
+# Workaround for GCP's structured logging throwing exceptions when logging
+# tuples and Decimals
+def _fix_elements(data):
+    if isinstance(data, dict):
+        return {_fix_elements(k): _fix_elements(v) for k, v in data.items()}
+    elif isinstance(data, (list, tuple)):
+        return [_fix_elements(item) for item in data]
+    elif isinstance(data, Decimal):
+        return str(data)
+    else:
+        return data
+
+
+# Workaround for GCP's structured logging ignoring the extra dictionary
 def _gcp_log(
     self,
     level,
     msg,
     args,
     exc_info=None,
     extra=None,
@@ -63,18 +77,20 @@
     stacklevel=1,
 ):
     if _gcp_extra:
         if extra is not None:
             extra = _gcp_extra | extra
         else:
             extra = _gcp_extra
+
     # GCP library will log a text-only message and discard the extra structured
     # logging if the extra is not packaged in their special format
     if extra is not None:
-        extra = {"json_fields": extra}
+        extra = {"json_fields": _fix_elements(extra)}
+
     _original_logger_log(
         self,
         level,
         msg,
         args,
         exc_info=exc_info,
         extra=extra,
```

### Comparing `tarvis-common-0.9.7/tarvis/common/monitoring/__init__.py` & `tarvis-common-0.9.8/tarvis/common/monitoring/__init__.py`

 * *Files identical despite different names*

### Comparing `tarvis-common-0.9.7/tarvis/common/secrets/__init__.py` & `tarvis-common-0.9.8/tarvis/common/secrets/__init__.py`

 * *Files identical despite different names*

### Comparing `tarvis-common-0.9.7/tarvis/common/time/__init__.py` & `tarvis-common-0.9.8/tarvis/common/time/__init__.py`

 * *Files identical despite different names*

### Comparing `tarvis-common-0.9.7/tarvis_common.egg-info/SOURCES.txt` & `tarvis-common-0.9.8/tarvis_common.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -11,9 +11,10 @@
 tarvis/common/time/__init__.py
 tarvis/common/trading/__init__.py
 tarvis_common.egg-info/PKG-INFO
 tarvis_common.egg-info/SOURCES.txt
 tarvis_common.egg-info/dependency_links.txt
 tarvis_common.egg-info/requires.txt
 tarvis_common.egg-info/top_level.txt
+test/test_cache_local.py
 test/test_config.py
 test/test_secrets.py
```

