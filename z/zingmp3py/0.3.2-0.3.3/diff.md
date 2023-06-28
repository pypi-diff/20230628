# Comparing `tmp/zingmp3py-0.3.2.tar.gz` & `tmp/zingmp3py-0.3.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "zingmp3py-0.3.2.tar", last modified: Sun Jun 25 15:35:03 2023, max compression
+gzip compressed data, was "zingmp3py-0.3.3.tar", last modified: Wed Jun 28 07:29:20 2023, max compression
```

## Comparing `zingmp3py-0.3.2.tar` & `zingmp3py-0.3.3.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-25 15:35:03.154270 zingmp3py-0.3.2/
--rw-r--r--   0 runner    (1001) docker     (123)    10751 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1485 2023-06-25 15:35:03.154270 zingmp3py-0.3.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1256 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-25 15:35:03.154270 zingmp3py-0.3.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-25 15:35:03.154270 zingmp3py-0.3.2/zingmp3py/
--rw-r--r--   0 runner    (1001) docker     (123)      184 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/zingmp3py/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3173 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/zingmp3py/sobj.py
--rw-r--r--   0 runner    (1001) docker     (123)      986 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/zingmp3py/util.py
--rw-r--r--   0 runner    (1001) docker     (123)     3823 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/zingmp3py/zasync.py
--rw-r--r--   0 runner    (1001) docker     (123)     2650 2023-06-25 15:34:53.000000 zingmp3py-0.3.2/zingmp3py/zsync.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-25 15:35:03.154270 zingmp3py-0.3.2/zingmp3py.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1485 2023-06-25 15:35:03.000000 zingmp3py-0.3.2/zingmp3py.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      287 2023-06-25 15:35:03.000000 zingmp3py-0.3.2/zingmp3py.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-25 15:35:03.000000 zingmp3py-0.3.2/zingmp3py.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-25 15:35:03.000000 zingmp3py-0.3.2/zingmp3py.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-25 15:35:03.000000 zingmp3py-0.3.2/zingmp3py.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:29:20.356288 zingmp3py-0.3.3/
+-rw-r--r--   0 runner    (1001) docker     (123)    10751 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1820 2023-06-28 07:29:20.356288 zingmp3py-0.3.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1591 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 07:29:20.356288 zingmp3py-0.3.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:29:20.356288 zingmp3py-0.3.3/zingmp3py/
+-rw-r--r--   0 runner    (1001) docker     (123)      184 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/zingmp3py/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3173 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/zingmp3py/sobj.py
+-rw-r--r--   0 runner    (1001) docker     (123)      986 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/zingmp3py/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5158 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/zingmp3py/zasync.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3843 2023-06-28 07:29:10.000000 zingmp3py-0.3.3/zingmp3py/zsync.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:29:20.356288 zingmp3py-0.3.3/zingmp3py.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1820 2023-06-28 07:29:20.000000 zingmp3py-0.3.3/zingmp3py.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      287 2023-06-28 07:29:20.000000 zingmp3py-0.3.3/zingmp3py.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:29:20.000000 zingmp3py-0.3.3/zingmp3py.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 07:29:20.000000 zingmp3py-0.3.3/zingmp3py.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 07:29:20.000000 zingmp3py-0.3.3/zingmp3py.egg-info/top_level.txt
```

### Comparing `zingmp3py-0.3.2/LICENSE` & `zingmp3py-0.3.3/LICENSE`

 * *Files identical despite different names*

### Comparing `zingmp3py-0.3.2/PKG-INFO` & `zingmp3py-0.3.3/README.md`

 * *Files 18% similar despite different names*

```diff
@@ -1,16 +1,7 @@
-Metadata-Version: 2.1
-Name: zingmp3py
-Version: 0.3.2
-Summary: A light weight Python library for the ZingMp3 API
-Author: The DT
-Author-email: duongtuan30306@gmail.com
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 # zingmp3py
 [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
 #### A light weight Python library for the ZingMp3 API
 ##### *all functions are return dict or ZingMp3 Object
 
 # install 
 
@@ -26,14 +17,16 @@
 
 
 # Sync :
 ```py
 from zingmp3py import ZingMp3
 
 zi = ZingMp3()
+# login is not required 
+zi.login("zpsid cookies")
 zi.getDetailPlaylist("67ZFO8DZ")
 zi.getDetailArtist("Cammie")
 zi.getRadioInfo("IWZ979CW")
 zi.getSongInfo("ZWAF6UFD")
 zi.getSongStreaming("ZWAF6UFD")
 zi.getTop100()
 zi.search("rick roll")
@@ -42,25 +35,32 @@
 # Async
 ```py
 import asyncio
 from zingmp3py import ZingMp3Async
 
 async def main():
     zi = ZingMp3Async()
+    # login is not required 
+    await zi.login("zpsid cookies")
     await zi.getDetailPlaylist("67ZFO8DZ")
     await zi.getDetailArtist("Cammie")
     await zi.getSongInfo("ZWAF6UFD")
     await zi.getSongStreaming("ZWAF6UFD")
     await zi.getTop100()
     await zi.search("rick roll")
 
-loop = asyncio.get_event_loop()
-loop.run_until_complete(main())
+asyncio.run(main())
 ```
 
+## how to get zpsid cookies
+
+go to https://id.zalo.me/account/logininfo then check f12 go to tab application go to cookies and check for cookie name zpsid
+
+note: please check check you are login or not by check key  `logged` in json return in that url is `true`
+
 ## Get Type And ID
 
 ```py
 from zingmp3py import getUrlTypeAndID
 
 getUrlTypeAndID("https://zingmp3.vn/liveradio/IWZ979CW.html")
 ```
```

### Comparing `zingmp3py-0.3.2/zingmp3py/sobj.py` & `zingmp3py-0.3.3/zingmp3py/sobj.py`

 * *Files identical despite different names*

### Comparing `zingmp3py-0.3.2/zingmp3py/util.py` & `zingmp3py-0.3.3/zingmp3py/util.py`

 * *Files identical despite different names*

### Comparing `zingmp3py-0.3.2/zingmp3py/zasync.py` & `zingmp3py-0.3.3/zingmp3py/zsync.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,108 +1,102 @@
-import aiohttp
-import time
 import re
+from requests.cookies import RequestsCookieJar
 from .util import *
-from .zsync import ZingMp3
 from .sobj import *
 
-cooke = {"cookies": {}, "last_updated": 0}
-apikey = {}
-async def get_ck(request: aiohttp.ClientSession):
-    if int(cooke["last_updated"] + 60) < int(time.time()):
-        async with request.get("https://zingmp3.vn") as r:
-            cooke["cookies"] = r.cookies
-            cooke["last_updated"] = int(time.time())
-            return cooke["cookies"]
-    else:
-        return cooke["cookies"]
-
-async def get_key():
-    if not apikey:
-        async with aiohttp.ClientSession() as s:
-            async with s.get("https://zjs.zmdcdn.me/zmp3-desktop/releases/v1.7.34/static/js/main.min.js") as r:
-                data = await r.text()
-            key = re.findall(r',h="(.*?)",p=\["ctime","id","type","page","count","version"\]', data)[0]
-            skey = re.findall(r"return d\(\)\(t\+r,\"(.*?)\"\)", data)[0]
-            apikey.update({"data": [key, skey]})
-            return [key, skey]
-    else:
-        return apikey["data"]
-
-async def requestZing(path, qs={}, haveParam=0):
-    apikey, skey = await get_key()
-    param = "&".join([f"{i}={k}" for i,k in qs.items()])
-    sig = hashParam(skey, path, param, haveParam)
-    qs.update({"apiKey": apikey})
-    qs.update({"ctime": sig[1]})
-    qs.update({"sig": sig[0]})
-    url = "https://zingmp3.vn" + path
-    async with aiohttp.ClientSession() as s:
-        ck = await get_ck(s)
-        async with s.get(url, params=qs, cookies=ck) as r:
-            data = await r.json()
-            if data['err'] != 0:
-                raise ZingMp3Error(data)
-            return data
-
-class Stream(Stream):
-    async def download(self, *args, **kwargs):
-        if not self.isVIP:
-            async with aiohttp.ClientSession() as s:
-                async with s.get(self.url, raise_for_status=True) as r:
-                    kwargs["mode"] = "wb"
-                    with open(*args, **kwargs) as streamfile:
-                        streamfile.write(await r.content.read())
+
+class ZingMp3:
+    cooke = RequestsCookieJar()
+    apikey = {}
+    zpsid = None
+    last_updated = 0
+
+    def __init__(self):
+        pass
+
+    def get_ck(self, request: requests.Session):
+        if int(self.last_updated - 60) < int(time.time()):
+            if self.zpsid:
+                ck = {"zpsid": self.zpsid}
+                with request.get("https://id.zalo.me/account?continue=https%3A%2F%2Fzingmp3.vn", cookies=ck) as r:
+                    if str(r.url) != "https://zingmp3.vn":
+                        raise Exception("zpsid is invalid cookie")
+            with request.get("https://zingmp3.vn") as r:
+                pass
+            self.cooke.update(r.cookies)
+            self.last_updated = int(time.time())
+            request.cookies.update(self.cooke)
+        else:
+            request.cookies.update(self.cooke)
+
+    def get_key(self):
+        if not self.apikey:
+            with requests.Session() as s:
+                with s.get("https://zingmp3.vn/") as r:
+                    data = r.text
+                outs = re.findall(r"<script type=\"text/javascript\" src=\"(https://zjs.zmdcdn.me/zmp3-desktop/releases/.*?/static/js/main\.min\.js)\"></script>", data)
+                with s.get(outs[0]) as r:
+                    data = r.text
+                outs = re.findall(r"\"([a-zA-Z0-9]{32})\"", data)
+                key = outs[0]
+                skey = outs[1]
+                self.apikey.update({"data": [key, skey]})
+                return [key, skey]
         else:
-            print("VIP Video Can Not Download")
+            return self.apikey["data"]
 
-class Song(Song):
-    async def getStreaming(self):
-        return await self.client.getSongStreaming(self.id)
-
-class Playlist(Playlist):
-    __slots__ = [
-        "id",
-        "title",
-        "indata",
-        "client"
-    ]
-
-    def __init__(self, indata, client):
-        self.id = indata["encodeId"]
-        self.indata = indata
-        self.title = indata['title']
-        self.client = client
-
-    @property
-    def songs(self):
-        return [Song(song, self.client) for song in self.indata['song']["items"]]
-
-class ZingMp3Async(ZingMp3):
-    async def getDetailPlaylist(self, id):
-        data = await requestZing("/api/v2/page/get/playlist", {"id": id})
+    def requestZing(self, path, qs={}, haveParam=0):
+        apikey, skey = self.get_key()
+        param = "&".join([f"{i}={k}" for i, k in qs.items()])
+        sig = hashParam(skey, path, param, haveParam)
+        qs.update({"apiKey": apikey})
+        qs.update({"ctime": sig[1]})
+        qs.update({"sig": sig[0]})
+        url = "https://zingmp3.vn" + path
+        with requests.Session() as s:
+            self.get_ck(s)
+            with s.get(url, params=qs) as r:
+                data = r.json()
+                if data['err'] != 0:
+                    raise ZingMp3Error(data)
+                return data
+
+    def login(self, zpsid):
+        with requests.Session() as s:
+            with s.get("https://id.zalo.me/account/logininfo", cookies={"zpsid": zpsid}) as r:
+                out = r.json()
+            if out["error_code"] != 0:
+                raise ZingMp3Error({"msg": f"Login Error: {out['error_message']}"})
+            elif not out["data"]["logged"]:
+                raise ZingMp3Error({"msg": f"zpsid is invalid"})
+        self.zpsid = zpsid
+
+    def getDetailPlaylist(self, id):
+        data = self.requestZing("/api/v2/page/get/playlist", {"id": id})
         return Playlist(data["data"], client=self)
 
-    async def getDetailArtist(self, alias):
-        data = await requestZing("/api/v2/page/get/artist", {"alias": alias}, 1)
+    def getDetailArtist(self, alias):
+        data = self.requestZing("/api/v2/page/get/artist", {"alias": alias}, 1)
         return Artist(data["data"])
 
-    async def getRadioInfo(self, id):
-        data = await requestZing("/api/v2/livestream/get/info", {"id": id})
+    def getRadioInfo(self, id):
+        data = self.requestZing("/api/v2/livestream/get/info", {"id": id})
         return LiveRadio(data["data"])
 
-    async def getSongInfo(self, id):
-        data = await requestZing("/api/v2/song/get/info", {"id": id})
+    def getSongInfo(self, id):
+        data = self.requestZing("/api/v2/song/get/info", {"id": id})
         return Song(data["data"], client=self)
 
-    async def getSongStreaming(self, id):
-        data = await requestZing("/api/v2/song/get/streaming", {"id": id})
+    def getSongStreaming(self, id):
+        data = self.requestZing("/api/v2/song/get/streaming", {"id": id})
         return [Stream(i, c) for i, c in data["data"].items()]
 
-    async def getTop100(self):
-        data = await requestZing("/api/v2/page/get/top-100", haveParam=1)
+    def getTop100(self):
+        data = self.requestZing("/api/v2/page/get/top-100", haveParam=1)
         dat = data["data"]
         return [Playlist(j, client=self) for i in dat for j in i["items"]]
 
-    async def search(self, search):
-        data = await requestZing("/api/v2/search/multi", {"q": search}, 1)
+    def search(self, search):
+        data = self.requestZing("/api/v2/search/multi", {"q": search}, 1)
         return Search(data["data"], client=self)
+
+
```

