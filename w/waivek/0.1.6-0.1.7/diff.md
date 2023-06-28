# Comparing `tmp/waivek-0.1.6.tar.gz` & `tmp/waivek-0.1.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "waivek-0.1.6.tar", last modified: Wed Jun 28 10:07:53 2023, max compression
+gzip compressed data, was "waivek-0.1.7.tar", last modified: Wed Jun 28 14:43:40 2023, max compression
```

## Comparing `waivek-0.1.6.tar` & `waivek-0.1.7.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 10:07:53.774320 waivek-0.1.6/
--rw-rw-rw-   0        0        0     1470 2023-06-28 10:07:53.774320 waivek-0.1.6/PKG-INFO
--rw-rw-rw-   0        0        0     1295 2023-06-27 07:27:31.000000 waivek-0.1.6/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 10:07:53.774320 waivek-0.1.6/setup.cfg
--rw-rw-rw-   0        0        0     1575 2023-06-28 09:47:28.000000 waivek-0.1.6/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:07:53.723655 waivek-0.1.6/waivek/
--rw-rw-rw-   0        0        0      377 2023-06-26 17:09:35.000000 waivek-0.1.6/waivek/__init__.py
--rw-rw-rw-   0        0        0     5601 2023-06-26 13:00:33.000000 waivek-0.1.6/waivek/color.py
--rw-rw-rw-   0        0        0    17147 2023-06-26 13:00:47.000000 waivek-0.1.6/waivek/common.py
--rw-rw-rw-   0        0        0    18804 2023-06-26 13:00:50.000000 waivek-0.1.6/waivek/db.py
--rw-rw-rw-   0        0        0    25668 2023-06-26 13:01:04.000000 waivek-0.1.6/waivek/error.py
--rw-rw-rw-   0        0        0     4725 2023-06-26 13:01:06.000000 waivek-0.1.6/waivek/frame.py
--rw-rw-rw-   0        0        0     9088 2023-06-28 10:07:34.000000 waivek-0.1.6/waivek/get.py
--rw-rw-rw-   0        0        0    28068 2023-06-27 06:18:33.000000 waivek-0.1.6/waivek/ic.py
--rw-rw-rw-   0        0        0     6272 2023-06-26 13:01:23.000000 waivek-0.1.6/waivek/print_utils.py
--rw-rw-rw-   0        0        0     1883 2023-06-27 04:31:33.000000 waivek-0.1.6/waivek/reltools.py
--rw-rw-rw-   0        0        0     4431 2023-06-26 16:58:35.000000 waivek-0.1.6/waivek/reqs.py
--rw-rw-rw-   0        0        0     1191 2023-06-26 13:01:34.000000 waivek-0.1.6/waivek/tdd.py
--rw-rw-rw-   0        0        0      324 2023-06-28 10:02:01.000000 waivek-0.1.6/waivek/template.py
--rw-rw-rw-   0        0        0    23039 2023-06-27 07:29:46.000000 waivek-0.1.6/waivek/test.py
--rw-rw-rw-   0        0        0     3668 2023-06-25 06:42:04.000000 waivek-0.1.6/waivek/timer.py
--rw-rw-rw-   0        0        0     5908 2023-06-26 13:02:00.000000 waivek-0.1.6/waivek/trace.py
-drwxrwxrwx   0        0        0        0 2023-06-28 10:07:53.768254 waivek-0.1.6/waivek.egg-info/
--rw-rw-rw-   0        0        0     1470 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      427 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      119 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 10:07:53.000000 waivek-0.1.6/waivek.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 14:43:40.920672 waivek-0.1.7/
+-rw-rw-rw-   0        0        0     1470 2023-06-28 14:43:40.920672 waivek-0.1.7/PKG-INFO
+-rw-rw-rw-   0        0        0     1295 2023-06-27 07:27:31.000000 waivek-0.1.7/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 14:43:40.920672 waivek-0.1.7/setup.cfg
+-rw-rw-rw-   0        0        0     1575 2023-06-28 09:47:28.000000 waivek-0.1.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:43:40.886643 waivek-0.1.7/waivek/
+-rw-rw-rw-   0        0        0      377 2023-06-26 17:09:35.000000 waivek-0.1.7/waivek/__init__.py
+-rw-rw-rw-   0        0        0     5601 2023-06-26 13:00:33.000000 waivek-0.1.7/waivek/color.py
+-rw-rw-rw-   0        0        0    17147 2023-06-26 13:00:47.000000 waivek-0.1.7/waivek/common.py
+-rw-rw-rw-   0        0        0    18824 2023-06-28 14:43:11.000000 waivek-0.1.7/waivek/db.py
+-rw-rw-rw-   0        0        0    25668 2023-06-26 13:01:04.000000 waivek-0.1.7/waivek/error.py
+-rw-rw-rw-   0        0        0     4725 2023-06-26 13:01:06.000000 waivek-0.1.7/waivek/frame.py
+-rw-rw-rw-   0        0        0     9088 2023-06-28 10:07:34.000000 waivek-0.1.7/waivek/get.py
+-rw-rw-rw-   0        0        0    28068 2023-06-27 06:18:33.000000 waivek-0.1.7/waivek/ic.py
+-rw-rw-rw-   0        0        0     6272 2023-06-26 13:01:23.000000 waivek-0.1.7/waivek/print_utils.py
+-rw-rw-rw-   0        0        0     3269 2023-06-28 14:31:41.000000 waivek-0.1.7/waivek/reltools.py
+-rw-rw-rw-   0        0        0     4431 2023-06-26 16:58:35.000000 waivek-0.1.7/waivek/reqs.py
+-rw-rw-rw-   0        0        0     1191 2023-06-26 13:01:34.000000 waivek-0.1.7/waivek/tdd.py
+-rw-rw-rw-   0        0        0      324 2023-06-28 10:02:01.000000 waivek-0.1.7/waivek/template.py
+-rw-rw-rw-   0        0        0    23039 2023-06-27 07:29:46.000000 waivek-0.1.7/waivek/test.py
+-rw-rw-rw-   0        0        0     3668 2023-06-25 06:42:04.000000 waivek-0.1.7/waivek/timer.py
+-rw-rw-rw-   0        0        0     5908 2023-06-26 13:02:00.000000 waivek-0.1.7/waivek/trace.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:43:40.920672 waivek-0.1.7/waivek.egg-info/
+-rw-rw-rw-   0        0        0     1470 2023-06-28 14:43:40.000000 waivek-0.1.7/waivek.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      427 2023-06-28 14:43:40.000000 waivek-0.1.7/waivek.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:43:40.000000 waivek-0.1.7/waivek.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      119 2023-06-28 14:43:40.000000 waivek-0.1.7/waivek.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 14:43:40.000000 waivek-0.1.7/waivek.egg-info/top_level.txt
```

### Comparing `waivek-0.1.6/PKG-INFO` & `waivek-0.1.7/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: waivek
-Version: 0.1.6
+Version: 0.1.7
 Summary: UNKNOWN
 Home-page: UNKNOWN
 License: UNKNOWN
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
 
 Code - Print colored text
```

### Comparing `waivek-0.1.6/README.md` & `waivek-0.1.7/README.md`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/setup.py` & `waivek-0.1.7/setup.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/color.py` & `waivek-0.1.7/waivek/color.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/common.py` & `waivek-0.1.7/waivek/common.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/db.py` & `waivek-0.1.7/waivek/db.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 
 # Hello
 # Red
 # Blue
 from .timer import Timer
 timer = Timer()
 from .common import print_red_line, make_string_green, truncate, Timer
-from .reltools import rel2abs
+from .reltools import pathjoin
 from enum import IntEnum
 timer = Timer()
 
 import sys
 
 if sys.platform != "win32":
     import pysqlite3 as sqlite3
@@ -39,15 +39,15 @@
 
 
 def db_init(db_path):
     sqlite3.register_adapter(list, dump_list)
     sqlite3.register_converter("LIST", load_json_bytes)
 
     import os
-    db_path = rel2abs(db_path)
+    db_path = pathjoin(sys._getframe(1), db_path)
     os.makedirs(os.path.dirname(db_path), exist_ok=True)
     connection = sqlite3.connect(db_path, detect_types=sqlite3.PARSE_DECLTYPES)
     # connection = sqlite3.connect(db_path, detect_types=sqlite3.PARSE_COLNAMES)
     connection.row_factory = sqlite3.Row
     cursor = connection.cursor()
     return cursor, connection
```

### Comparing `waivek-0.1.6/waivek/error.py` & `waivek-0.1.7/waivek/error.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/frame.py` & `waivek-0.1.7/waivek/frame.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/get.py` & `waivek-0.1.7/waivek/get.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/ic.py` & `waivek-0.1.7/waivek/ic.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/print_utils.py` & `waivek-0.1.7/waivek/print_utils.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/reltools.py` & `waivek-0.1.7/waivek/reltools.py`

 * *Files 23% similar despite different names*

```diff
@@ -8,52 +8,95 @@
 #     reltools:write
 #     reltools:read
 #     db:db_init`
 
 import os
 import sys
 
+def pathjoin(frame, relpath):
+    frame_directory = os.path.dirname(frame.f_code.co_filename)
+    return os.path.realpath(os.path.join(frame_directory, relpath))
+
 def read(relpath):
     import json
-    filepath = relpath if os.path.isabs(relpath) else rel2abs(relpath)
+    from .color import Code
+    filepath = relpath if os.path.isabs(relpath) else pathjoin(sys._getframe(1), relpath)
     filepath = os.path.normpath(filepath)
+    if os.path.exists(filepath) is False:
+        message = "[reltools.py:read()] " + (Code.YELLOW + "File does not exist: ") + (Code.RED + filepath)
+        print(message)
+        return {}
+
     with open(filepath, "r") as f:
         obj = json.load(f)
     return obj
 
 def write(obj, relpath):
     import json
     filepath = os.path.normpath(rel2abs(relpath))
     os.makedirs(os.path.dirname(filepath), exist_ok=True)
     with open(filepath, "w") as f:
         json.dump(obj, f, indent=4)
     return filepath
 
 def get_caller_parent():
+    from .frame import Frame
     self_path = os.path.normpath(os.path.dirname(__file__))
     frame_index = 0
     directories = []
+    frames = []
     while True:
         frame = sys._getframe(frame_index)
+        frames.append(Frame(frame))
         called_path      = frame.f_code.co_filename
         parent_directory = os.path.dirname(os.path.realpath(called_path))
         directories.append(parent_directory)
         if parent_directory.lower() != self_path.lower():
             break
         if frame.f_back == None:
             break
         frame_index = frame_index + 1
 
+
     if frame.f_back is None and len(set(directories)) == 1 and directories[0] == os.path.dirname(__file__): # importing from a python file in same directory as reltools.py
         return directories[0]
 
     return parent_directory
 
+def frame_to_absolute_directory(frame):
+    return os.path.dirname(os.path.realpath(frame.f_code.co_filename))
+
 def rel2abs(relative_path):
-    parent_directory = get_caller_parent()
+    from .ic import ic
+    from .ic import ib
+    ic; ib
+    return pathjoin(sys._getframe(1), relative_path)
+
+    # Implementation 3
+    # ================
+    parent_directory = os.path.dirname(sys._getframe(1).f_globals["__file__"])
+    absolute_path = os.path.realpath(os.path.join(parent_directory, relative_path))
+    ic(absolute_path)
+    return absolute_path
+
+    # self_function_name = sys._getframe(0).f_code.co_name
+
+    # Implementation 2
+    # ================
+    frame = sys._getframe(1)
+    parent_directory = frame_to_absolute_directory(frame)
     absolute_path    = os.path.realpath(os.path.join(parent_directory, relative_path))
+    ic(absolute_path)
+
+
+    # Implementation 1
+    # ================
+    # parent_directory = get_caller_parent()
+    # absolute_path    = os.path.realpath(os.path.join(parent_directory, relative_path))
+    # ic(absolute_path)
+
     return absolute_path
 
 def here():
     # importing pathlib is slow as shit
     from pathlib import Path
     return Path(sys._getframe(1).f_code.co_filename).parent
```

### Comparing `waivek-0.1.6/waivek/reqs.py` & `waivek-0.1.7/waivek/reqs.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/tdd.py` & `waivek-0.1.7/waivek/tdd.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/test.py` & `waivek-0.1.7/waivek/test.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/timer.py` & `waivek-0.1.7/waivek/timer.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek/trace.py` & `waivek-0.1.7/waivek/trace.py`

 * *Files identical despite different names*

### Comparing `waivek-0.1.6/waivek.egg-info/PKG-INFO` & `waivek-0.1.7/waivek.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: waivek
-Version: 0.1.6
+Version: 0.1.7
 Summary: UNKNOWN
 Home-page: UNKNOWN
 License: UNKNOWN
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
 
 Code - Print colored text
```

