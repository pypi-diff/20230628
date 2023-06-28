# Comparing `tmp/tskmanager-1.0.0.tar.gz` & `tmp/tskmanager-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tskmanager-1.0.0.tar", last modified: Wed Jun 28 15:15:31 2023, max compression
+gzip compressed data, was "tskmanager-1.0.1.tar", last modified: Wed Jun 28 15:19:50 2023, max compression
```

## Comparing `tskmanager-1.0.0.tar` & `tskmanager-1.0.1.tar`

### file list

```diff
@@ -1,16 +1,17 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:15:31.877414 tskmanager-1.0.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-28 15:15:31.877414 tskmanager-1.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      655 2023-06-28 15:15:17.000000 tskmanager-1.0.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      478 2023-06-28 15:15:17.000000 tskmanager-1.0.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:15:31.877414 tskmanager-1.0.0/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:15:31.873414 tskmanager-1.0.0/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:15:31.877414 tskmanager-1.0.0/src/tasker/
--rw-r--r--   0 runner    (1001) docker     (123)     3110 2023-06-28 15:15:17.000000 tskmanager-1.0.0/src/tasker/attached_stream.py
--rw-r--r--   0 runner    (1001) docker     (123)      862 2023-06-28 15:15:17.000000 tskmanager-1.0.0/src/tasker/instance.py
--rw-r--r--   0 runner    (1001) docker     (123)     1733 2023-06-28 15:15:17.000000 tskmanager-1.0.0/src/tasker/manager.py
--rw-r--r--   0 runner    (1001) docker     (123)     1163 2023-06-28 15:15:17.000000 tskmanager-1.0.0/src/tasker/task.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:15:31.877414 tskmanager-1.0.0/src/tskmanager.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-28 15:15:31.000000 tskmanager-1.0.0/src/tskmanager.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      270 2023-06-28 15:15:31.000000 tskmanager-1.0.0/src/tskmanager.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:15:31.000000 tskmanager-1.0.0/src/tskmanager.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 15:15:31.000000 tskmanager-1.0.0/src/tskmanager.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:50.742783 tskmanager-1.0.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-28 15:19:50.742783 tskmanager-1.0.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      655 2023-06-28 15:19:38.000000 tskmanager-1.0.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      478 2023-06-28 15:19:38.000000 tskmanager-1.0.1/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:19:50.742783 tskmanager-1.0.1/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:50.738783 tskmanager-1.0.1/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:50.742783 tskmanager-1.0.1/src/tasker/
+-rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-28 15:19:38.000000 tskmanager-1.0.1/src/tasker/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3110 2023-06-28 15:19:38.000000 tskmanager-1.0.1/src/tasker/attached_stream.py
+-rw-r--r--   0 runner    (1001) docker     (123)      862 2023-06-28 15:19:38.000000 tskmanager-1.0.1/src/tasker/instance.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1733 2023-06-28 15:19:38.000000 tskmanager-1.0.1/src/tasker/manager.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1163 2023-06-28 15:19:38.000000 tskmanager-1.0.1/src/tasker/task.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:19:50.742783 tskmanager-1.0.1/src/tskmanager.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1127 2023-06-28 15:19:50.000000 tskmanager-1.0.1/src/tskmanager.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      293 2023-06-28 15:19:50.000000 tskmanager-1.0.1/src/tskmanager.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:19:50.000000 tskmanager-1.0.1/src/tskmanager.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 15:19:50.000000 tskmanager-1.0.1/src/tskmanager.egg-info/top_level.txt
```

### Comparing `tskmanager-1.0.0/PKG-INFO` & `tskmanager-1.0.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tskmanager
-Version: 1.0.0
+Version: 1.0.1
 Summary: Task manager for python
 Author-email: Highghlow <highghlow@proton.me>
 Project-URL: Homepage, https://github.com/highghlow/tasker
 Project-URL: Bug Tracker, https://github.com/highghlow/tasker/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `tskmanager-1.0.0/README.md` & `tskmanager-1.0.1/README.md`

 * *Files identical despite different names*

### Comparing `tskmanager-1.0.0/src/tasker/attached_stream.py` & `tskmanager-1.0.1/src/tasker/attached_stream.py`

 * *Files identical despite different names*

### Comparing `tskmanager-1.0.0/src/tasker/instance.py` & `tskmanager-1.0.1/src/tasker/instance.py`

 * *Files identical despite different names*

### Comparing `tskmanager-1.0.0/src/tasker/manager.py` & `tskmanager-1.0.1/src/tasker/manager.py`

 * *Files identical despite different names*

### Comparing `tskmanager-1.0.0/src/tasker/task.py` & `tskmanager-1.0.1/src/tasker/task.py`

 * *Files identical despite different names*

### Comparing `tskmanager-1.0.0/src/tskmanager.egg-info/PKG-INFO` & `tskmanager-1.0.1/src/tskmanager.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tskmanager
-Version: 1.0.0
+Version: 1.0.1
 Summary: Task manager for python
 Author-email: Highghlow <highghlow@proton.me>
 Project-URL: Homepage, https://github.com/highghlow/tasker
 Project-URL: Bug Tracker, https://github.com/highghlow/tasker/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

