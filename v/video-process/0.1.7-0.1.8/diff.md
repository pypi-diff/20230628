# Comparing `tmp/video_process-0.1.7.tar.gz` & `tmp/video_process-0.1.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "video_process-0.1.7.tar", max compression
+gzip compressed data, was "video_process-0.1.8.tar", max compression
```

## Comparing `video_process-0.1.7.tar` & `video_process-0.1.8.tar`

### file list

```diff
@@ -1,8 +1,8 @@
--rw-r--r--   0        0        0      453 2023-06-26 07:35:58.493388 video_process-0.1.7/pyproject.toml
--rw-r--r--   0        0        0      108 2023-06-21 08:43:34.831508 video_process-0.1.7/video_process/__init__.py
--rw-r--r--   0        0        0     5111 2023-06-26 07:20:21.505280 video_process-0.1.7/video_process/graph_builder.py
--rwxr-xr-x   0        0        0     1310 2023-06-26 06:41:03.502179 video_process-0.1.7/video_process/index.py
--rw-r--r--   0        0        0     1685 2023-06-21 08:58:19.044108 video_process-0.1.7/video_process/lib.py
--rw-r--r--   0        0        0      664 2023-06-21 09:05:03.418463 video_process-0.1.7/video_process/subtitle.py
--rw-r--r--   0        0        0     3384 2023-06-26 06:38:17.094573 video_process-0.1.7/video_process/utils.py
--rw-r--r--   0        0        0      328 1970-01-01 00:00:00.000000 video_process-0.1.7/PKG-INFO
+-rw-r--r--   0        0        0      453 2023-06-28 09:02:00.711048 video_process-0.1.8/pyproject.toml
+-rw-r--r--   0        0        0      125 2023-06-28 09:02:50.789446 video_process-0.1.8/video_process/__init__.py
+-rw-r--r--   0        0        0     5111 2023-06-26 07:20:21.505280 video_process-0.1.8/video_process/graph_builder.py
+-rwxr-xr-x   0        0        0     1472 2023-06-28 09:08:51.256981 video_process-0.1.8/video_process/index.py
+-rw-r--r--   0        0        0     1685 2023-06-21 08:58:19.044108 video_process-0.1.8/video_process/lib.py
+-rw-r--r--   0        0        0     1134 2023-06-28 08:59:43.686218 video_process-0.1.8/video_process/subtitle.py
+-rw-r--r--   0        0        0     3384 2023-06-26 06:38:17.094573 video_process-0.1.8/video_process/utils.py
+-rw-r--r--   0        0        0      328 1970-01-01 00:00:00.000000 video_process-0.1.8/PKG-INFO
```

### Comparing `video_process-0.1.7/video_process/graph_builder.py` & `video_process-0.1.8/video_process/graph_builder.py`

 * *Files identical despite different names*

### Comparing `video_process-0.1.7/video_process/index.py` & `video_process-0.1.8/video_process/index.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 # -*- coding: utf-8 -*-
 import os
 import logging
 import sys
 from video_process.utils import process_data, check_dir, get_video_min
 from video_process.graph_builder import GraphBuilder
 from video_process.lib import upload_file, get_cos_url
+from video_process.subtitle import set_script_info
 
 logging.basicConfig(level=logging.INFO, stream=sys.stdout)
 logger = logging.getLogger()
 logger.setLevel(level=logging.INFO)
 
 
 def video_process(body):
@@ -28,14 +29,16 @@
         for layer in layers:
             gb.add_overlay(layer)
 
     if body.get("enable_bg_music"):
         gb.add_bg_music(body["bg_music"])
 
     if body.get("enable_subtitle"):
+        print("enable_subtitle")
+        set_script_info(body["subtitle"]["script_info"], gb.width, gb.height)
         gb.add_subtitle(body["subtitle"]["subtitle_path"])
     output_path = os.path.join(base_dir, "output.mp4")
     gb.drop_first_frame()
     command = gb.build(output_path)
     gb.run(command)
 
     upload_file(body["key"], output_path)
```

### Comparing `video_process-0.1.7/video_process/lib.py` & `video_process-0.1.8/video_process/lib.py`

 * *Files identical despite different names*

### Comparing `video_process-0.1.7/video_process/subtitle.py` & `video_process-0.1.8/video_process/subtitle.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,26 +1,42 @@
 import ffmpeg
+import pyass
 
 
 def convert_to_ass(input_srt_file, output_ass_file):
     ffmpeg.input(input_srt_file).output(
         output_ass_file, format="ass"
     ).overwrite_output().run()
 
 
 def change_style(input_srt_file, output_ass_file, style):
-    import pyass
-
     tmp_ass_file = "/tmp/tmp.ass"
     convert_to_ass(input_srt_file, tmp_ass_file)
 
     new_style = pyass.Style()
 
     for key, value in style.items():
         setattr(new_style, key, value)
 
     with open(tmp_ass_file, encoding="utf_8_sig") as f:
         script = pyass.load(f)
 
     script.styles[0] = new_style
     with open(output_ass_file, "w", encoding="utf_8_sig") as f:
         pyass.dump(script, f)
+
+
+def set_script_info(filename, w, h):
+    with open(filename, encoding="utf_8_sig") as f:
+        script = pyass.load(f)
+
+    script.scriptInfo = pyass.ScriptInfoSection(
+        [
+            ("ScriptType", "v4.00+"),
+            ("PlayResX", f"{w}"),
+            ("PlayResY", f"{h}"),
+            ("ScaledBorderAndShadow", "yes"),
+            ("YCbCr Matrix", "None"),
+        ]
+    )
+    with open(filename, "w", encoding="utf_8_sig") as f:
+        pyass.dump(script, f)
```

### Comparing `video_process-0.1.7/video_process/utils.py` & `video_process-0.1.8/video_process/utils.py`

 * *Files identical despite different names*

