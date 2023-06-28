# Comparing `tmp/recon_lw-2.0.0.dev5391252981.tar.gz` & `tmp/recon_lw-2.0.0.dev5398854918.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/recon_lw-2.0.0.dev5391252981.tar", last modified: Tue Jun 27 14:47:03 2023, max compression
+gzip compressed data, was "dist/recon_lw-2.0.0.dev5398854918.tar", last modified: Wed Jun 28 08:21:42 2023, max compression
```

## Comparing `recon_lw-2.0.0.dev5391252981.tar` & `recon_lw-2.0.0.dev5398854918.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/
--rw-r--r--   0 runner    (1001) docker     (122)       69 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (122)      294 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)       10 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/README.md
--rw-r--r--   0 runner    (1001) docker     (122)       76 2023-06-27 14:46:37.000000 recon_lw-2.0.0.dev5391252981/package_info.json
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/recon_lw/
--rw-r--r--   0 runner    (1001) docker     (122)     1908 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/EventsSaver.py
--rw-r--r--   0 runner    (1001) docker     (122)     4937 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/LastStateMatcher.py
--rw-r--r--   0 runner    (1001) docker     (122)     2507 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/LiveObjectsCache.py
--rw-r--r--   0 runner    (1001) docker     (122)     2916 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/SequenceCache.py
--rw-r--r--   0 runner    (1001) docker     (122)     1108 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/StateSequenceGenerator.py
--rw-r--r--   0 runner    (1001) docker     (122)     3716 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/TimeCacheMatcher.py
--rw-r--r--   0 runner    (1001) docker     (122)        5 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)    13503 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/recon_lw.py
--rw-r--r--   0 runner    (1001) docker     (122)    33431 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/recon_ob.py
--rw-r--r--   0 runner    (1001) docker     (122)    22143 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/recon_ob_cross_stream.py
--rw-r--r--   0 runner    (1001) docker     (122)     6293 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/recon_lw/recon_ob_stats.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/recon_lw.egg-info/
--rw-r--r--   0 runner    (1001) docker     (122)      294 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/recon_lw.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)      542 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/recon_lw.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/recon_lw.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (122)      219 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/recon_lw.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (122)        9 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/recon_lw.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (122)      275 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (122)       38 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (122)     1582 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-27 14:47:03.000000 recon_lw-2.0.0.dev5391252981/test/
--rw-r--r--   0 runner    (1001) docker     (122)     4050 2023-06-27 14:46:07.000000 recon_lw-2.0.0.dev5391252981/test/test_recon_ob.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/
+-rw-r--r--   0 runner    (1001) docker     (122)       69 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (122)      294 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)       10 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/README.md
+-rw-r--r--   0 runner    (1001) docker     (122)       76 2023-06-28 08:21:16.000000 recon_lw-2.0.0.dev5398854918/package_info.json
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/recon_lw/
+-rw-r--r--   0 runner    (1001) docker     (122)     1908 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/EventsSaver.py
+-rw-r--r--   0 runner    (1001) docker     (122)     4937 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/LastStateMatcher.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2507 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/LiveObjectsCache.py
+-rw-r--r--   0 runner    (1001) docker     (122)     2916 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/SequenceCache.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1108 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/StateSequenceGenerator.py
+-rw-r--r--   0 runner    (1001) docker     (122)     3716 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/TimeCacheMatcher.py
+-rw-r--r--   0 runner    (1001) docker     (122)        5 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)    13503 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/recon_lw.py
+-rw-r--r--   0 runner    (1001) docker     (122)    33734 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/recon_ob.py
+-rw-r--r--   0 runner    (1001) docker     (122)    22143 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/recon_ob_cross_stream.py
+-rw-r--r--   0 runner    (1001) docker     (122)     6293 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/recon_lw/recon_ob_stats.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/recon_lw.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (122)      294 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/recon_lw.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)      542 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/recon_lw.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/recon_lw.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (122)      219 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/recon_lw.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        9 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/recon_lw.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (122)      275 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (122)       38 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (122)     1582 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 08:21:42.000000 recon_lw-2.0.0.dev5398854918/test/
+-rw-r--r--   0 runner    (1001) docker     (122)     4050 2023-06-28 08:20:49.000000 recon_lw-2.0.0.dev5398854918/test/test_recon_ob.py
```

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/EventsSaver.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/EventsSaver.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/LastStateMatcher.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/LastStateMatcher.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/LiveObjectsCache.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/LiveObjectsCache.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/SequenceCache.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/SequenceCache.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/StateSequenceGenerator.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/StateSequenceGenerator.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/TimeCacheMatcher.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/TimeCacheMatcher.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/recon_lw.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/recon_lw.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/recon_ob.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/recon_ob.py`

 * *Files 1% similar despite different names*

```diff
@@ -103,32 +103,37 @@
                                             "book_id": book_id},
                                       parentId=parent_event["eventId"])
     for tupl in operations_batch:
         dbg_event["attachedMessageIds"].append(tupl[2]["messageId"])
     events.append(dbg_event)
 
     if len(obs) > 1 and aggregate_batch_updates:
-        top_not_affected = all(ob["aggr_seq"]["top_delta"] == 0 for ob in obs)
-        limit_not_affected = all(ob["aggr_seq"]["limit_delta"] == 0 for ob in obs)
+        top_not_affected = True #all(ob["aggr_seq"]["top_delta"] == 0 for ob in obs)
+        limit_not_affected = True #all(ob["aggr_seq"]["limit_delta"] == 0 for ob in obs)
         updated_v2 = 0
         for i in range(len(obs) - 1):
             if obs[i]["operation"] in ["ob_change_status", "ob_clean_book", "ob_aggr_clean_book", "ob_top_clean_book"]:
                 obs[i]["aggr_seq"]["top_v2"] = updated_v2
                 obs[i]["aggr_seq"]["limit_v2"] = updated_v2
                 updated_v2 += 1
                 continue
+            
+            if obs[i]["aggr_seq"]["top_delta"] == 1:
+                top_not_affected = False
+            if obs[i]["aggr_seq"]["limit_delta"] == 1:
+                limit_not_affected = False
 
             obs[i]["aggr_seq"]["top_delta"] = 0
             obs[i]["aggr_seq"]["top_v2"] = -1
             obs[i]["aggr_seq"]["limit_delta"] = 0
             obs[i]["aggr_seq"]["limit_v2"] = -1
 
-        obs[-1]["aggr_seq"]["top_delta"] = 0 if top_not_affected else 1
+        obs[-1]["aggr_seq"]["top_delta"] = 0 if top_not_affected and obs[-1]["aggr_seq"]["top_delta"] == 0 else 1
         obs[-1]["aggr_seq"]["top_v2"] = updated_v2
-        obs[-1]["aggr_seq"]["limit_delta"] = 0 if limit_not_affected else 1
+        obs[-1]["aggr_seq"]["limit_delta"] = 0 if limit_not_affected and obs[-1]["aggr_seq"]["limit_delta"] == 0 else 1
         obs[-1]["aggr_seq"]["limit_v2"] = updated_v2
     else:
         updated_limit_v2 = 0
         updated_top_v2 = 0
         for i in range(len(obs)):
             if obs[i]["aggr_seq"]["top_delta"] == 1:
                 obs[i]["aggr_seq"]["top_v2"] = updated_top_v2
```

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/recon_ob_cross_stream.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/recon_ob_cross_stream.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw/recon_ob_stats.py` & `recon_lw-2.0.0.dev5398854918/recon_lw/recon_ob_stats.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/recon_lw.egg-info/SOURCES.txt` & `recon_lw-2.0.0.dev5398854918/recon_lw.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/setup.py` & `recon_lw-2.0.0.dev5398854918/setup.py`

 * *Files identical despite different names*

### Comparing `recon_lw-2.0.0.dev5391252981/test/test_recon_ob.py` & `recon_lw-2.0.0.dev5398854918/test/test_recon_ob.py`

 * *Files identical despite different names*

