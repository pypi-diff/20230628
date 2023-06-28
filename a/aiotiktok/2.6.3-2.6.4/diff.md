# Comparing `tmp/aiotiktok-2.6.3.tar.gz` & `tmp/aiotiktok-2.6.4.tar.gz`

## Comparing `aiotiktok-2.6.3.tar` & `aiotiktok-2.6.4.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/aiotiktok/__init__.py
--rw-r--r--   0        0        0     6682 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/aiotiktok/client.py
--rw-r--r--   0        0        0     1480 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/aiotiktok/constants.py
--rw-r--r--   0        0        0       94 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/aiotiktok/exceptions.py
--rw-r--r--   0        0        0     2737 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/aiotiktok/extractors.py
--rw-r--r--   0        0        0     1158 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/aiotiktok/types.py
--rw-r--r--   0        0        0     1942 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/.gitignore
--rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/LICENSE
--rw-r--r--   0        0        0     1350 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/README.rst
--rw-r--r--   0        0        0      761 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/pyproject.toml
--rw-r--r--   0        0        0     1765 2020-02-02 00:00:00.000000 aiotiktok-2.6.3/PKG-INFO
+-rw-r--r--   0        0        0       77 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/aiotiktok/__init__.py
+-rw-r--r--   0        0        0     6682 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/aiotiktok/client.py
+-rw-r--r--   0        0        0     1227 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/aiotiktok/constants.py
+-rw-r--r--   0        0        0       94 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/aiotiktok/exceptions.py
+-rw-r--r--   0        0        0     2863 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/aiotiktok/extractors.py
+-rw-r--r--   0        0        0     1811 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/aiotiktok/types.py
+-rw-r--r--   0        0        0     1942 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/.gitignore
+-rw-r--r--   0        0        0     1084 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/LICENSE
+-rw-r--r--   0        0        0     1350 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/README.rst
+-rw-r--r--   0        0        0      761 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/pyproject.toml
+-rw-r--r--   0        0        0     1765 2020-02-02 00:00:00.000000 aiotiktok-2.6.4/PKG-INFO
```

### Comparing `aiotiktok-2.6.3/aiotiktok/client.py` & `aiotiktok-2.6.4/aiotiktok/client.py`

 * *Files identical despite different names*

### Comparing `aiotiktok-2.6.3/aiotiktok/extractors.py` & `aiotiktok-2.6.4/aiotiktok/extractors.py`

 * *Files 8% similar despite different names*

```diff
@@ -15,34 +15,35 @@
 
 def create_url_to_video(username: str, video_id: str):
     return f"https://www.tiktok.com/@{username}/video/{video_id}"
 
 
 def extract_video_data(data: dict) -> VideoData:
     video_type = video_type_codes.get(data["aweme_type"], VideoType.VIDEO)
-    if video_type == VideoType.ALBUM:
-        media = Album(
+    if video_type == VideoType.VIDEO:
+        media = Video(url=data["video"]["play_addr"]["url_list"][0])
+    elif video_type == VideoType.ALBUM:
+        media = Album(  # type: ignore
             urls=[
                 images["display_image"]["url_list"][0]
                 for images in data["image_post_info"]["images"]
             ]
         )
-    elif video_type == VideoType.VIDEO:
-        media = Video(url=data["video"]["play_addr"]["url_list"][0])
     else:
         media = None
     author_data = data.get("author", {})
+    statistics = data.get("statistics", {})
+    music_data = data.get("music", {})
     author = Author(
         id=author_data.get("id"),
         nickname=author_data.get("nickname"),
         unique_id=author_data.get("unique_id"),
         avatar=author_data.get("avatar_larger", {}).get("url_list")[0],
         sec_uid=author_data.get("sec_uid"),
     )
-    statistics = data.get("statistics", {})
     return VideoData(
         url=create_url_to_video(author.unique_id, data.get("aweme_id", "")),
         video_type=video_type,
         media=media,
         cover=data["video"]["cover"]["url_list"][0],
         dynamic_cover=data["video"]["dynamic_cover"]["url_list"][0],
         description=data["desc"],
@@ -53,18 +54,19 @@
             downloads=statistics.get("download_count"),
             shares=statistics.get("share_count"),
             saves=statistics.get("collect_count"),
         ),
         create_time=data["create_time"],
         author=author,
         music=Music(
-            title=data["music"]["title"],
-            author=data["music"]["author"],
-            url=data["music"]["play_url"]["uri"],
-            cover=data["music"]["cover_large"]["url_list"][0],
+            id=music_data.get("id_str"),
+            title=music_data.get("title"),
+            author=music_data.get("author"),
+            url=music_data.get("play_url", {}).get("uri"),
+            cover=music_data.get("cover_large", {}).get("url_list", [None])[0],
         ),
     )
 
 
 def extract_data_from_html(data: str):
     pattern = r'<script id="SIGI_STATE" type="application\/json">(.*?)<\/script>'
     match = re.search(pattern, data, re.S)
```

#### html2text {}

 * *error from `html2text {}`:*

 * *File "/tmp/diffoscope_4w5rk3bf_/tmpeptrhmtv_TarContainer/0/4.py", line 84, column 0: CDATA terminal not found*

 * *File "/tmp/diffoscope_4w5rk3bf_/tmpeptrhmtv_TarContainer/0/4.py", line 84, column 0: CDATA terminal not found*

```diff
@@ -1,24 +1,25 @@
 import json import re from .types import ( Album, Author, Music, Statistics,
 Video, VideoData, VideoType, video_type_codes, ) def create_url_to_video
 (username: str, video_id: str): return f"https://www.tiktok.com/@{username}/
 video/{video_id}" def extract_video_data(data: dict) -> VideoData: video_type =
 video_type_codes.get(data["aweme_type"], VideoType.VIDEO) if video_type ==
-VideoType.ALBUM: media = Album( urls=[ images["display_image"]["url_list"][0]
-for images in data["image_post_info"]["images"] ] ) elif video_type ==
 VideoType.VIDEO: media = Video(url=data["video"]["play_addr"]["url_list"][0])
-else: media = None author_data = data.get("author", {}) author = Author
-( id=author_data.get("id"), nickname=author_data.get("nickname"),
-unique_id=author_data.get("unique_id"), avatar=author_data.get("avatar_larger",
-{}).get("url_list")[0], sec_uid=author_data.get("sec_uid"), ) statistics =
-data.get("statistics", {}) return VideoData( url=create_url_to_video
-(author.unique_id, data.get("aweme_id", "")), video_type=video_type,
-media=media, cover=data["video"]["cover"]["url_list"][0], dynamic_cover=data
-["video"]["dynamic_cover"]["url_list"][0], description=data["desc"],
-statistics=Statistics( likes=statistics.get("digg_count"), plays=statistics.get
-("play_count"), comments=statistics.get("comment_count"),
-downloads=statistics.get("download_count"), shares=statistics.get
-("share_count"), saves=statistics.get("collect_count"), ), create_time=data
-["create_time"], author=author, music=Music( title=data["music"]["title"],
-author=data["music"]["author"], url=data["music"]["play_url"]["uri"],
-cover=data["music"]["cover_large"]["url_list"][0], ), ) def
+elif video_type == VideoType.ALBUM: media = Album( # type: ignore urls=[ images
+["display_image"]["url_list"][0] for images in data["image_post_info"]
+["images"] ] ) else: media = None author_data = data.get("author", {})
+statistics = data.get("statistics", {}) music_data = data.get("music", {})
+author = Author( id=author_data.get("id"), nickname=author_data.get
+("nickname"), unique_id=author_data.get("unique_id"), avatar=author_data.get
+("avatar_larger", {}).get("url_list")[0], sec_uid=author_data.get("sec_uid"), )
+return VideoData( url=create_url_to_video(author.unique_id, data.get
+("aweme_id", "")), video_type=video_type, media=media, cover=data["video"]
+["cover"]["url_list"][0], dynamic_cover=data["video"]["dynamic_cover"]
+["url_list"][0], description=data["desc"], statistics=Statistics
+( likes=statistics.get("digg_count"), plays=statistics.get("play_count"),
+comments=statistics.get("comment_count"), downloads=statistics.get
+("download_count"), shares=statistics.get("share_count"), saves=statistics.get
+("collect_count"), ), create_time=data["create_time"], author=author,
+music=Music( id=music_data.get("id_str"), title=music_data.get("title"),
+author=music_data.get("author"), url=music_data.get("play_url", {}).get("uri"),
+cover=music_data.get("cover_large", {}).get("url_list", [None])[0], ), ) def
 extract_data_from_html(data: str): pattern = r'
```

### Comparing `aiotiktok-2.6.3/.gitignore` & `aiotiktok-2.6.4/.gitignore`

 * *Files identical despite different names*

### Comparing `aiotiktok-2.6.3/LICENSE` & `aiotiktok-2.6.4/LICENSE`

 * *Files identical despite different names*

### Comparing `aiotiktok-2.6.3/README.rst` & `aiotiktok-2.6.4/README.rst`

 * *Files identical despite different names*

### Comparing `aiotiktok-2.6.3/pyproject.toml` & `aiotiktok-2.6.4/pyproject.toml`

 * *Files identical despite different names*

### Comparing `aiotiktok-2.6.3/PKG-INFO` & `aiotiktok-2.6.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: aiotiktok
-Version: 2.6.3
+Version: 2.6.4
 Summary: Tool for parse tiktok data
 Project-URL: Homepage, https://github.com/sheldygg/aiotiktok
 Author: sheldy
 License-Expression: MIT
 License-File: LICENSE
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
```

