# Comparing `tmp/tagreader-4.1.3.tar.gz` & `tmp/tagreader-4.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tagreader-4.1.3.tar", max compression
+gzip compressed data, was "tagreader-4.1.4.tar", max compression
```

## Comparing `tagreader-4.1.3.tar` & `tagreader-4.1.4.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0     1064 2023-06-06 13:10:02.326221 tagreader-4.1.3/LICENSE
--rw-r--r--   0        0        0     2561 2023-06-15 12:41:41.851734 tagreader-4.1.3/README.md
--rw-r--r--   0        0        0     1633 2023-06-21 14:18:50.115817 tagreader-4.1.3/pyproject.toml
--rw-r--r--   0        0        0      351 2023-06-14 10:40:53.499388 tagreader-4.1.3/tagreader/__init__.py
--rw-r--r--   0        0        0      282 2023-06-09 06:24:33.101915 tagreader-4.1.3/tagreader/__version__.py
--rw-r--r--   0        0        0    12723 2023-06-14 10:40:53.499996 tagreader-4.1.3/tagreader/cache.py
--rw-r--r--   0        0        0    23397 2023-06-21 14:18:50.116275 tagreader-4.1.3/tagreader/clients.py
--rw-r--r--   0        0        0      198 2023-06-09 06:24:33.104271 tagreader-4.1.3/tagreader/logger.py
--rw-r--r--   0        0        0    25164 2023-06-21 08:33:16.577206 tagreader-4.1.3/tagreader/odbc_handlers.py
--rw-r--r--   0        0        0     8215 2023-06-14 13:05:07.541522 tagreader-4.1.3/tagreader/utils.py
--rw-r--r--   0        0        0    32717 2023-06-21 14:05:09.371900 tagreader-4.1.3/tagreader/web_handlers.py
--rw-r--r--   0        0        0     4404 1970-01-01 00:00:00.000000 tagreader-4.1.3/PKG-INFO
+-rw-r--r--   0        0        0     1064 2023-06-06 13:10:02.326221 tagreader-4.1.4/LICENSE
+-rw-r--r--   0        0        0     2561 2023-06-15 12:41:41.851734 tagreader-4.1.4/README.md
+-rw-r--r--   0        0        0     1633 2023-06-28 11:03:37.658388 tagreader-4.1.4/pyproject.toml
+-rw-r--r--   0        0        0      351 2023-06-14 10:40:53.499388 tagreader-4.1.4/tagreader/__init__.py
+-rw-r--r--   0        0        0      282 2023-06-09 06:24:33.101915 tagreader-4.1.4/tagreader/__version__.py
+-rw-r--r--   0        0        0    12723 2023-06-14 10:40:53.499996 tagreader-4.1.4/tagreader/cache.py
+-rw-r--r--   0        0        0    23700 2023-06-28 10:48:44.445290 tagreader-4.1.4/tagreader/clients.py
+-rw-r--r--   0        0        0      198 2023-06-09 06:24:33.104271 tagreader-4.1.4/tagreader/logger.py
+-rw-r--r--   0        0        0    25164 2023-06-21 08:33:16.577206 tagreader-4.1.4/tagreader/odbc_handlers.py
+-rw-r--r--   0        0        0     8215 2023-06-14 13:05:07.541522 tagreader-4.1.4/tagreader/utils.py
+-rw-r--r--   0        0        0    32496 2023-06-28 10:45:36.341065 tagreader-4.1.4/tagreader/web_handlers.py
+-rw-r--r--   0        0        0     4404 1970-01-01 00:00:00.000000 tagreader-4.1.4/PKG-INFO
```

### Comparing `tagreader-4.1.3/LICENSE` & `tagreader-4.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.3/README.md` & `tagreader-4.1.4/README.md`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.3/pyproject.toml` & `tagreader-4.1.4/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "tagreader"
-version = "4.1.3"
+version = "4.1.4"
 description = "Tagreader is a Python package for reading trend data from the OSIsoft PI and Aspen Infoplus.21 IMS systems."
 authors = ["Einar S. Idsø <eiids@equinor.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "tagreader"}]
 keywords=["Aspen InfoPlus.21", "OSIsoft PI"]
 homepage = "https://github.com/equinor/tagreader-python"
```

### Comparing `tagreader-4.1.3/tagreader/cache.py` & `tagreader-4.1.4/tagreader/cache.py`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.3/tagreader/clients.py` & `tagreader-4.1.4/tagreader/clients.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 import os
 from concurrent.futures import ThreadPoolExecutor
 from datetime import datetime, timedelta
 from itertools import groupby
 from operator import itemgetter
 from pathlib import Path
 from typing import Any, Dict, List, Optional, Tuple, Union
+from urllib.error import HTTPError
 
 import pandas as pd
 import pytz
 
 from tagreader.cache import BucketCache, SmartCache
 from tagreader.logger import logger
 from tagreader.utils import (
@@ -209,23 +210,29 @@
     host: Optional[str],
     port: Optional[int],
     options: Dict[str, Union[int, float, str]],
     verifySSL: Optional[bool],
     auth: Optional[Any],
 ):
     if imstype is None:
-        if datasource in list_aspenone_sources(
-            url=None, auth=None, verifySSL=verifySSL
-        ):
-            imstype = IMSType.ASPENONE
-        elif datasource in list_piwebapi_sources(
-            url=None, auth=None, verifySSL=verifySSL
-        ):
-            imstype = IMSType.PIWEBAPI
-
+        try:
+            if datasource in list_aspenone_sources(
+                url=None, auth=None, verifySSL=verifySSL
+            ):
+                imstype = IMSType.ASPENONE
+        except HTTPError as e:
+            logger.debug(f"Could not list Aspenone sources: {e}")
+    if imstype is None:
+        try:
+            if datasource in list_piwebapi_sources(
+                url=None, auth=None, verifySSL=verifySSL
+            ):
+                imstype = IMSType.PIWEBAPI
+        except HTTPError as e:
+            logger.debug(f"Could not list PI sources: {e}")
     if imstype == IMSType.PI:
         if not is_windows():
             raise RuntimeError(
                 "ODBC drivers not available for non-Windows environments. "
                 "Try Web API ('piwebapi') instead."
             )
         if "PI ODBC Driver" not in pyodbc.drivers():
@@ -283,15 +290,15 @@
             url=url,
             options=options,
             verifySSL=verifySSL,
             auth=auth,
         )
 
     raise ValueError(
-        f"Could not infer IMSType for datasource: {datasource}."
+        f"Could not infer IMSType for datasource: {datasource}. "
         f"Please specify correct datasource, imstype or host, or refer to the user docs."
     )
 
 
 class IMSClient:
     def __init__(
         self,
```

### Comparing `tagreader-4.1.3/tagreader/odbc_handlers.py` & `tagreader-4.1.4/tagreader/odbc_handlers.py`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.3/tagreader/utils.py` & `tagreader-4.1.4/tagreader/utils.py`

 * *Files identical despite different names*

### Comparing `tagreader-4.1.3/tagreader/web_handlers.py` & `tagreader-4.1.4/tagreader/web_handlers.py`

 * *Files 3% similar despite different names*

```diff
@@ -58,25 +58,20 @@
     elif verifySSL is None:
         verifySSL = get_verifySSL()
 
     url_ = urljoin(url, "DataSources")
     params = {"service": "ProcessData", "allQuotes": 1}
 
     res = requests.get(url_, params=params, auth=auth, verify=verifySSL)
-    if res.status_code == 200:
-        try:
-            source_list = [r["n"] for r in res.json()["data"] if r["t"] == "IP21"]
-            return source_list
-        except JSONDecodeError:
-            print("Did not return json")
-    elif res.status_code == 404:
-        print("Not found")
-    elif res.status_code == 401:
-        print("Not authorized")
     res.raise_for_status()
+    try:
+        source_list = [r["n"] for r in res.json()["data"] if r["t"] == "IP21"]
+        return source_list
+    except JSONDecodeError as e:
+        logger.error(f"Could not decode JSON response: {e}")
 
 
 def list_piwebapi_sources(
     url: Optional[str],
     auth: Optional[Any],
     verifySSL: Optional[bool],
 ) -> List[str]:
@@ -90,25 +85,20 @@
         urllib3.disable_warnings(urllib3.exceptions.InsecureRequestWarning)
     elif verifySSL is None:
         verifySSL = get_verifySSL()
 
     url_ = urljoin(url, "dataservers")
     res = requests.get(url_, auth=auth, verify=verifySSL)
 
-    if res.status_code == 200:
-        try:
-            source_list = [r["Name"] for r in res.json()["Items"]]
-            return source_list
-        except JSONDecodeError:
-            print("Did not return json")
-    elif res.status_code == 404:
-        print("Not found")
-    elif res.status_code == 401:
-        print("Not authorized")
     res.raise_for_status()
+    try:
+        source_list = [r["Name"] for r in res.json()["Items"]]
+        return source_list
+    except JSONDecodeError as e:
+        logger.error(f"Could not decode JSON response: {e}")
 
 
 class BaseHandlerWeb(ABC):
     def __init__(
         self,
         datasource: Optional[str],
         url: Optional[str],
@@ -509,15 +499,17 @@
 
         data = self.fetch(url, params=params)
 
         if len(data) == 0:  # Normally for timestamps in future
             return pd.DataFrame(columns=[tag])
 
         if "er" in data["data"][0]["samples"][0]:
-            logger.warning(data["data"][0]["samples"][0]["es"])
+            logger.warning(
+                f"API error for {tag}: {data['data'][0]['samples'][0]['es']} params: {params}"
+            )
             return pd.DataFrame(columns=[tag])
         if get_status:
             # The "l" field maps 1:1 to ODBC status field values 0, 1, 2, 4, 5, 6
             df = (
                 pd.DataFrame.from_dict(data["data"][0]["samples"])
                 .drop(labels=["s", "V"], axis="columns")
                 .rename(columns={"t": "Timestamp", "v": "Value", "l": "Status"})
```

### Comparing `tagreader-4.1.3/PKG-INFO` & `tagreader-4.1.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tagreader
-Version: 4.1.3
+Version: 4.1.4
 Summary: Tagreader is a Python package for reading trend data from the OSIsoft PI and Aspen Infoplus.21 IMS systems.
 Home-page: https://github.com/equinor/tagreader-python
 License: MIT
 Keywords: Aspen InfoPlus.21,OSIsoft PI
 Author: Einar S. Idsø
 Author-email: eiids@equinor.com
 Requires-Python: >=3.8,<4.0
```

