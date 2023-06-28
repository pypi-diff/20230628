# Comparing `tmp/thingwala_geyserwala-0.0.2-py3-none-any.whl.zip` & `tmp/thingwala_geyserwala-0.0.3-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,15 +1,15 @@
-Zip file size: 7339 bytes, number of entries: 13
+Zip file size: 7504 bytes, number of entries: 13
 -rw-r--r--  2.0 unx      255 b- defN 23-Feb-21 13:09 thingwala/geyserwala/__init__.py
--rw-r--r--  2.0 unx      599 b- defN 23-Feb-21 13:09 thingwala/geyserwala/const.py
+-rw-r--r--  2.0 unx      664 b- defN 23-Jun-28 11:19 thingwala/geyserwala/const.py
 -rw-r--r--  2.0 unx      564 b- defN 23-Feb-21 13:09 thingwala/geyserwala/errors.py
 -rw-r--r--  2.0 unx      255 b- defN 23-Feb-21 13:09 thingwala/geyserwala/aio/__init__.py
 -rw-r--r--  2.0 unx     2538 b- defN 23-Feb-21 13:09 thingwala/geyserwala/aio/cli.py
--rw-r--r--  2.0 unx     8495 b- defN 23-Mar-09 15:54 thingwala/geyserwala/aio/client.py
+-rw-r--r--  2.0 unx     9283 b- defN 23-Jun-28 12:06 thingwala/geyserwala/aio/client.py
 -rw-r--r--  2.0 unx     1494 b- defN 23-Feb-21 13:09 thingwala/geyserwala/aio/discovery.py
--rw-r--r--  2.0 unx     1066 b- defN 23-Mar-09 15:58 thingwala_geyserwala-0.0.2.dist-info/LICENSE
--rw-r--r--  2.0 unx      294 b- defN 23-Mar-09 15:58 thingwala_geyserwala-0.0.2.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 23-Mar-09 15:58 thingwala_geyserwala-0.0.2.dist-info/WHEEL
--rw-r--r--  2.0 unx       64 b- defN 23-Mar-09 15:58 thingwala_geyserwala-0.0.2.dist-info/entry_points.txt
--rw-r--r--  2.0 unx       10 b- defN 23-Mar-09 15:58 thingwala_geyserwala-0.0.2.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx     1182 b- defN 23-Mar-09 15:58 thingwala_geyserwala-0.0.2.dist-info/RECORD
-13 files, 16908 bytes uncompressed, 5317 bytes compressed:  68.6%
+-rw-r--r--  2.0 unx     1066 b- defN 23-Jun-28 12:31 thingwala_geyserwala-0.0.3.dist-info/LICENSE
+-rw-r--r--  2.0 unx      294 b- defN 23-Jun-28 12:31 thingwala_geyserwala-0.0.3.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 12:31 thingwala_geyserwala-0.0.3.dist-info/WHEEL
+-rw-r--r--  2.0 unx       64 b- defN 23-Jun-28 12:31 thingwala_geyserwala-0.0.3.dist-info/entry_points.txt
+-rw-r--r--  2.0 unx       10 b- defN 23-Jun-28 12:31 thingwala_geyserwala-0.0.3.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx     1182 b- defN 23-Jun-28 12:31 thingwala_geyserwala-0.0.3.dist-info/RECORD
+13 files, 17761 bytes uncompressed, 5482 bytes compressed:  69.1%
```

## zipnote {}

```diff
@@ -15,26 +15,26 @@
 
 Filename: thingwala/geyserwala/aio/client.py
 Comment: 
 
 Filename: thingwala/geyserwala/aio/discovery.py
 Comment: 
 
-Filename: thingwala_geyserwala-0.0.2.dist-info/LICENSE
+Filename: thingwala_geyserwala-0.0.3.dist-info/LICENSE
 Comment: 
 
-Filename: thingwala_geyserwala-0.0.2.dist-info/METADATA
+Filename: thingwala_geyserwala-0.0.3.dist-info/METADATA
 Comment: 
 
-Filename: thingwala_geyserwala-0.0.2.dist-info/WHEEL
+Filename: thingwala_geyserwala-0.0.3.dist-info/WHEEL
 Comment: 
 
-Filename: thingwala_geyserwala-0.0.2.dist-info/entry_points.txt
+Filename: thingwala_geyserwala-0.0.3.dist-info/entry_points.txt
 Comment: 
 
-Filename: thingwala_geyserwala-0.0.2.dist-info/top_level.txt
+Filename: thingwala_geyserwala-0.0.3.dist-info/top_level.txt
 Comment: 
 
-Filename: thingwala_geyserwala-0.0.2.dist-info/RECORD
+Filename: thingwala_geyserwala-0.0.3.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## thingwala/geyserwala/const.py

```diff
@@ -1,17 +1,19 @@
 ####################################################################################
 # Copyright (c) 2023 ThingWala                                                     #
 ####################################################################################
 GEYSERWALA_MODE_SETPOINT = "SETPOINT"
 GEYSERWALA_MODE_TIMER = "TIMER"
 GEYSERWALA_MODE_SOLAR = "SOLAR"
 GEYSERWALA_MODE_HOLIDAY = "HOLIDAY"
+GEYSERWALA_MODE_STANDBY = "STANDBY"
 
 GEYSERWALA_MODES = [
     GEYSERWALA_MODE_SETPOINT,
     GEYSERWALA_MODE_TIMER,
     GEYSERWALA_MODE_SOLAR,
     GEYSERWALA_MODE_HOLIDAY,
+    GEYSERWALA_MODE_STANDBY,
 ]
 
 GEYSERWALA_SETPOINT_TEMP_MAX = 65
 GEYSERWALA_SETPOINT_TEMP_MIN = 30
```

## thingwala/geyserwala/aio/client.py

```diff
@@ -7,14 +7,19 @@
 from contextlib import asynccontextmanager
 
 import aiohttp
 
 from thingwala.geyserwala.errors import Unauthorized, RequestError
 from thingwala.geyserwala.const import (
     GEYSERWALA_MODES,
+    GEYSERWALA_MODE_SETPOINT,
+    GEYSERWALA_MODE_TIMER,
+    GEYSERWALA_MODE_SOLAR,
+    GEYSERWALA_MODE_HOLIDAY,
+    GEYSERWALA_MODE_STANDBY,
     GEYSERWALA_SETPOINT_TEMP_MAX,
     GEYSERWALA_SETPOINT_TEMP_MIN,
 )
 
 
 logger = logging.getLogger(__name__)
 
@@ -27,14 +32,15 @@
         self._user = username or "admin"
         self._pass = password or ""
         self._rest_timeout = 10
         self._lock = asyncio.Lock()
         self._session = session or aiohttp.ClientSession()
         self._status = {}
         self._status_values = [
+            "features",
             "id",
             "version",
             "name",
             "hostname",
             "time",
             "status",
             "tank-temp",
@@ -50,42 +56,42 @@
         ]
 
     async def close(self):
         await self._session.close()
 
     @property
     def authorized(self):
-        return getattr(self._session, '_jwt', None) is not None
+        return getattr(self._session, '_token', None) is not None
 
     async def _value_callback(self, value):
         if asyncio.iscoroutinefunction(value):
             return await value()
         if callable(value):
             return value()
         return value
 
     async def login(self, username, password):
         self._user = username
         self._pass = password
         password = await self._value_callback(self._pass)
         rsp = await self._json_req('POST', 'api/session', json={'username': self._user, 'password': password})
         if not rsp:
-            self._session._jwt = None
+            self._session._token = None
             return False
         if rsp['success'] is True:
-            self._session._jwt = rsp['jwt']
+            self._session._token = rsp['token']
             return True
         return False
 
     async def logout(self):
         rsp = await self._json_req('DELETE', 'api/session')
         if not rsp:
             return False
         if rsp['success'] is True:
-            self._session._jwt = None
+            self._session._token = None
             return True
         return False
 
     @asynccontextmanager
     async def _auth(self):
         if not self.authorized:
             if not await self.login(self._user, self._pass):
@@ -97,16 +103,16 @@
         logger.debug('req: %s %s %s %s', method, path, params, json)
         try:
             async with self._lock:
                 headers = {
                     "Content-Type": "application/json",
                     "Accept": "application/json"
                 }
-                if hasattr(self._session, '_jwt'):
-                    headers["Authorization"] = f"Bearer {self._session._jwt}"
+                if hasattr(self._session, '_token'):
+                    headers["Authorization"] = f"Bearer {self._session._token}"
 
                 url = f"{self._scheme}://{self._host}:{self._port}/{path}"
                 async with self._session.request(
                     method=method,
                     headers=headers,
                     url=url,
                     params=params,
@@ -131,16 +137,16 @@
             raise RequestError() from ex
         except Exception as ex:
             logger.exception(
                 "Non-aiohttp exception occured:  %s", getattr(ex, "__dict__", {})
             )
             raise RequestError from ex
         if status == 401:
-            if hasattr(self._session, '_jwt'):
-                delattr(self._session, '_jwt')
+            if hasattr(self._session, '_token'):
+                delattr(self._session, '_token')
             raise Unauthorized()
         raise RequestError("Unexpected status: %s", status)
 
     async def update_status(self):
         async with self._auth():
             rsp = await self._json_req("GET", "api/value", params={"f": ','.join(self._status_values)})
             if rsp:
@@ -160,14 +166,20 @@
     def id(self):
         return self._status.get("id", "?")
 
     @property
     def version(self):
         return self._status.get("version", "?")
 
+    def has_feature(self, key):
+        try:
+            return self._status.get("features", {})[key]
+        except KeyError:
+            return False
+
     @property
     def name(self):
         return self._status.get("name", "?")
 
     @property
     def hostname(self):
         return self._status.get("hostname", "?")
@@ -209,14 +221,27 @@
         return False
 
     @property
     def element_demand(self):
         return self._status.get("element-demand", None)
 
     @property
+    def modes(self):
+        modes = []
+        modes.append(GEYSERWALA_MODE_SETPOINT)
+        modes.append(GEYSERWALA_MODE_TIMER)
+        if self.has_feature('f-collector'):
+            modes.append(GEYSERWALA_MODE_SOLAR)
+        if self.has_feature('f-collector'):
+            modes.append(GEYSERWALA_MODE_HOLIDAY)
+        if not self.has_feature('f-collector'):
+            modes.append(GEYSERWALA_MODE_STANDBY)
+        return modes
+
+    @property
     def mode(self):
         return self._status.get("mode", "?")
 
     async def set_mode(self, mode: str):
         if mode in GEYSERWALA_MODES:
             return await self._set_value("mode", mode)
         return False
```

## Comparing `thingwala_geyserwala-0.0.2.dist-info/LICENSE` & `thingwala_geyserwala-0.0.3.dist-info/LICENSE`

 * *Files identical despite different names*

## Comparing `thingwala_geyserwala-0.0.2.dist-info/RECORD` & `thingwala_geyserwala-0.0.3.dist-info/RECORD`

 * *Files 24% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 thingwala/geyserwala/__init__.py,sha256=nt1--L6j4xyyFFJdBdahajJRfWZazifXDOPKzzSLzVg,255
-thingwala/geyserwala/const.py,sha256=GD-R-vWJRja-WEPemEmKEnAZXIPEUAuyZL5N5wd0DNc,599
+thingwala/geyserwala/const.py,sha256=gQif4BIyBhNJOQzgFjGFJGAVQ70dH5bAhoaj4dA4qFY,664
 thingwala/geyserwala/errors.py,sha256=kYvz2xvaEBPJV6O42sNgUJA8W87Jg_V92mf3YD1zokg,564
 thingwala/geyserwala/aio/__init__.py,sha256=nt1--L6j4xyyFFJdBdahajJRfWZazifXDOPKzzSLzVg,255
 thingwala/geyserwala/aio/cli.py,sha256=kbMbFmRFrc5lVz3BKpeLhYFlsuxU0d1zseRarIWhM9c,2538
-thingwala/geyserwala/aio/client.py,sha256=sWb30K_4ukO21W0QZbuQo2P25yCHVQOjEJHQJAzQ4Hw,8495
+thingwala/geyserwala/aio/client.py,sha256=xsbvpSljY36G6trw6XiLvQ2JFkxHb-AXV8K_4gNx0og,9283
 thingwala/geyserwala/aio/discovery.py,sha256=PUPQOpEPgp0XVg9Z5-0ab5HD4KHqgKeaErjhi3-G4xM,1494
-thingwala_geyserwala-0.0.2.dist-info/LICENSE,sha256=HqMVmYQiODLCw6T8-LwBDbuq8R-i56VYSWHjBDtfFEY,1066
-thingwala_geyserwala-0.0.2.dist-info/METADATA,sha256=6seqr_NHeoy9eNXvfXHIAWowITbajgnxD1EBXwfj5y0,294
-thingwala_geyserwala-0.0.2.dist-info/WHEEL,sha256=2wepM1nk4DS4eFpYrW1TTqPcoGNfHhhO_i5m4cOimbo,92
-thingwala_geyserwala-0.0.2.dist-info/entry_points.txt,sha256=i-4-nYc2EWKZgp2OkdhunSjYOe7_7pkwsJ5B8bswt_M,64
-thingwala_geyserwala-0.0.2.dist-info/top_level.txt,sha256=n6rcs8stkw-UrgrGzIobTwxPz9yrId1tHNvUkdN94F4,10
-thingwala_geyserwala-0.0.2.dist-info/RECORD,,
+thingwala_geyserwala-0.0.3.dist-info/LICENSE,sha256=HqMVmYQiODLCw6T8-LwBDbuq8R-i56VYSWHjBDtfFEY,1066
+thingwala_geyserwala-0.0.3.dist-info/METADATA,sha256=vHkOCV-cMZINTHGnDruPzjse5DO9JeQz9YxCZtE9XJg,294
+thingwala_geyserwala-0.0.3.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
+thingwala_geyserwala-0.0.3.dist-info/entry_points.txt,sha256=i-4-nYc2EWKZgp2OkdhunSjYOe7_7pkwsJ5B8bswt_M,64
+thingwala_geyserwala-0.0.3.dist-info/top_level.txt,sha256=n6rcs8stkw-UrgrGzIobTwxPz9yrId1tHNvUkdN94F4,10
+thingwala_geyserwala-0.0.3.dist-info/RECORD,,
```

