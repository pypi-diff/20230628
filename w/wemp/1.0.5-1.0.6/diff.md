# Comparing `tmp/wemp-1.0.5-py3-none-any.whl.zip` & `tmp/wemp-1.0.6-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,10 +1,10 @@
-Zip file size: 4938 bytes, number of entries: 8
--rw-rw-r--  2.0 unx     8829 b- defN 23-Jun-27 11:07 wemp/__init__.py
+Zip file size: 4946 bytes, number of entries: 8
+-rw-rw-r--  2.0 unx     8842 b- defN 23-Jun-27 23:35 wemp/__init__.py
 -rw-rw-r--  2.0 unx      120 b- defN 23-Jun-12 14:45 wemp/__main__.py
 -rw-rw-r--  2.0 unx     1086 b- defN 23-Jun-12 15:33 wemp/http.py
--rw-rw-r--  2.0 unx      269 b- defN 23-Jun-27 11:07 wemp-1.0.5.dist-info/METADATA
--rw-rw-r--  2.0 unx       92 b- defN 23-Jun-27 11:07 wemp-1.0.5.dist-info/WHEEL
--rw-rw-r--  2.0 unx       44 b- defN 23-Jun-27 11:07 wemp-1.0.5.dist-info/entry_points.txt
--rw-rw-r--  2.0 unx        5 b- defN 23-Jun-27 11:07 wemp-1.0.5.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      590 b- defN 23-Jun-27 11:07 wemp-1.0.5.dist-info/RECORD
-8 files, 11035 bytes uncompressed, 3914 bytes compressed:  64.5%
+-rw-rw-r--  2.0 unx      269 b- defN 23-Jun-27 23:36 wemp-1.0.6.dist-info/METADATA
+-rw-rw-r--  2.0 unx       92 b- defN 23-Jun-27 23:36 wemp-1.0.6.dist-info/WHEEL
+-rw-rw-r--  2.0 unx       44 b- defN 23-Jun-27 23:36 wemp-1.0.6.dist-info/entry_points.txt
+-rw-rw-r--  2.0 unx        5 b- defN 23-Jun-27 23:36 wemp-1.0.6.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx      590 b- defN 23-Jun-27 23:36 wemp-1.0.6.dist-info/RECORD
+8 files, 11048 bytes uncompressed, 3922 bytes compressed:  64.5%
```

## zipnote {}

```diff
@@ -3,23 +3,23 @@
 
 Filename: wemp/__main__.py
 Comment: 
 
 Filename: wemp/http.py
 Comment: 
 
-Filename: wemp-1.0.5.dist-info/METADATA
+Filename: wemp-1.0.6.dist-info/METADATA
 Comment: 
 
-Filename: wemp-1.0.5.dist-info/WHEEL
+Filename: wemp-1.0.6.dist-info/WHEEL
 Comment: 
 
-Filename: wemp-1.0.5.dist-info/entry_points.txt
+Filename: wemp-1.0.6.dist-info/entry_points.txt
 Comment: 
 
-Filename: wemp-1.0.5.dist-info/top_level.txt
+Filename: wemp-1.0.6.dist-info/top_level.txt
 Comment: 
 
-Filename: wemp-1.0.5.dist-info/RECORD
+Filename: wemp-1.0.6.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## wemp/__init__.py

```diff
@@ -279,15 +279,15 @@
     cfg     = Config()
     actions = Actions(cfg)
 
     global watch_thread
     def watch_fn(token):
         actions.watch(argparse.Namespace(file=file, token=token, pid=None, wait_file=True, noprint=True))
 
-    watch_thread = Thread(target=watch_fn, args=(token,)).start()
+    watch_thread = Thread(target=watch_fn, args=(token,), daemon=True).start()
 
 def stop_watch():
 
     global watch_thread
     if watch_thread is not None:
         watch_thread.join()
```

