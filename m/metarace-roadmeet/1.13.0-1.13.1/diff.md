# Comparing `tmp/metarace-roadmeet-1.13.0.tar.gz` & `tmp/metarace-roadmeet-1.13.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "metarace-roadmeet-1.13.0.tar", last modified: Wed Jun 28 10:18:38 2023, max compression
+gzip compressed data, was "metarace-roadmeet-1.13.1.tar", last modified: Wed Jun 28 13:24:28 2023, max compression
```

## Comparing `metarace-roadmeet-1.13.0.tar` & `metarace-roadmeet-1.13.1.tar`

### file list

```diff
@@ -1,32 +1,33 @@
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 10:18:38.984586 metarace-roadmeet-1.13.0/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1063 2022-11-24 00:04:20.000000 metarace-roadmeet-1.13.0/LICENSE
--rw-r--r--   0 ndf       (1000) ndf       (1000)       26 2022-11-24 00:09:22.000000 metarace-roadmeet-1.13.0/MANIFEST.in
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1610 2023-06-28 10:18:38.984586 metarace-roadmeet-1.13.0/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1051 2023-06-28 10:18:08.000000 metarace-roadmeet-1.13.0/README.md
--rw-r--r--   0 ndf       (1000) ndf       (1000)      746 2023-06-28 10:13:26.000000 metarace-roadmeet-1.13.0/pyproject.toml
--rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-28 10:18:38.984586 metarace-roadmeet-1.13.0/setup.cfg
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 10:18:38.976586 metarace-roadmeet-1.13.0/src/
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 10:18:38.980586 metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1610 2023-06-28 10:18:38.000000 metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)      710 2023-06-28 10:18:38.000000 metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/SOURCES.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-28 10:18:38.000000 metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/dependency_links.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)       43 2023-06-28 10:18:38.000000 metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/entry_points.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)       16 2023-06-28 10:18:38.000000 metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/requires.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        9 2023-06-28 10:18:38.000000 metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/top_level.txt
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 10:18:38.980586 metarace-roadmeet-1.13.0/src/roadmeet/
--rw-r--r--   0 ndf       (1000) ndf       (1000)    83719 2023-06-27 13:32:59.000000 metarace-roadmeet-1.13.0/src/roadmeet/__init__.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)       79 2022-11-24 06:32:10.000000 metarace-roadmeet-1.13.0/src/roadmeet/__main__.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)   107594 2023-06-23 23:51:59.000000 metarace-roadmeet-1.13.0/src/roadmeet/irtt.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)   179865 2023-06-25 10:23:12.000000 metarace-roadmeet-1.13.0/src/roadmeet/rms.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)    62271 2023-06-23 12:39:08.000000 metarace-roadmeet-1.13.0/src/roadmeet/trtt.py
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 10:18:38.984586 metarace-roadmeet-1.13.0/src/roadmeet/ui/
--rw-------   0 ndf       (1000) ndf       (1000)    13762 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/edit_times.ui
--rw-------   0 ndf       (1000) ndf       (1000)     4496 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/irtt.ui
--rw-------   0 ndf       (1000) ndf       (1000)     7206 2023-06-01 06:00:37.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/new_start.ui
--rw-------   0 ndf       (1000) ndf       (1000)     2356 2023-06-24 03:51:06.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/rider_context.ui
--rw-------   0 ndf       (1000) ndf       (1000)     5625 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/rms.ui
--rw-------   0 ndf       (1000) ndf       (1000)     5657 2023-06-14 12:44:18.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/rms_context.ui
--rw-r--r--   0 ndf       (1000) ndf       (1000)    44070 2023-06-13 02:56:48.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/roadmeet.ui
--rw-------   0 ndf       (1000) ndf       (1000)     8749 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/swap_rider.ui
--rw-------   0 ndf       (1000) ndf       (1000)     4389 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.0/src/roadmeet/ui/tod_context.ui
--rw-r--r--   0 ndf       (1000) ndf       (1000)    37130 2023-06-27 13:33:24.000000 metarace-roadmeet-1.13.0/src/roadmeet/uiutil.py
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:24:28.009016 metarace-roadmeet-1.13.1/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1063 2022-11-24 00:04:20.000000 metarace-roadmeet-1.13.1/LICENSE
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       26 2022-11-24 00:09:22.000000 metarace-roadmeet-1.13.1/MANIFEST.in
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1610 2023-06-28 13:24:28.009016 metarace-roadmeet-1.13.1/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1051 2023-06-28 10:18:08.000000 metarace-roadmeet-1.13.1/README.md
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      746 2023-06-28 13:23:58.000000 metarace-roadmeet-1.13.1/pyproject.toml
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-28 13:24:28.009016 metarace-roadmeet-1.13.1/setup.cfg
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:24:28.005016 metarace-roadmeet-1.13.1/src/
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:24:28.005016 metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1610 2023-06-28 13:24:27.000000 metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      738 2023-06-28 13:24:27.000000 metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/SOURCES.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-28 13:24:27.000000 metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/dependency_links.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       43 2023-06-28 13:24:27.000000 metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/entry_points.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       16 2023-06-28 13:24:27.000000 metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/requires.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        9 2023-06-28 13:24:27.000000 metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/top_level.txt
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:24:28.009016 metarace-roadmeet-1.13.1/src/roadmeet/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    83719 2023-06-28 13:24:12.000000 metarace-roadmeet-1.13.1/src/roadmeet/__init__.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       79 2022-11-24 06:32:10.000000 metarace-roadmeet-1.13.1/src/roadmeet/__main__.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)   107594 2023-06-23 23:51:59.000000 metarace-roadmeet-1.13.1/src/roadmeet/irtt.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)   179865 2023-06-25 10:23:12.000000 metarace-roadmeet-1.13.1/src/roadmeet/rms.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    62271 2023-06-23 12:39:08.000000 metarace-roadmeet-1.13.1/src/roadmeet/trtt.py
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:24:28.009016 metarace-roadmeet-1.13.1/src/roadmeet/ui/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        0 2023-06-28 12:18:14.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/__init__.py
+-rw-------   0 ndf       (1000) ndf       (1000)    13762 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/edit_times.ui
+-rw-------   0 ndf       (1000) ndf       (1000)     4496 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/irtt.ui
+-rw-------   0 ndf       (1000) ndf       (1000)     7206 2023-06-01 06:00:37.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/new_start.ui
+-rw-------   0 ndf       (1000) ndf       (1000)     2356 2023-06-24 03:51:06.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/rider_context.ui
+-rw-------   0 ndf       (1000) ndf       (1000)     5625 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/rms.ui
+-rw-------   0 ndf       (1000) ndf       (1000)     5657 2023-06-14 12:44:18.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/rms_context.ui
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    44070 2023-06-13 02:56:48.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/roadmeet.ui
+-rw-------   0 ndf       (1000) ndf       (1000)     8749 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/swap_rider.ui
+-rw-------   0 ndf       (1000) ndf       (1000)     4389 2023-05-30 11:27:50.000000 metarace-roadmeet-1.13.1/src/roadmeet/ui/tod_context.ui
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    37130 2023-06-27 13:33:24.000000 metarace-roadmeet-1.13.1/src/roadmeet/uiutil.py
```

### Comparing `metarace-roadmeet-1.13.0/LICENSE` & `metarace-roadmeet-1.13.1/LICENSE`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/PKG-INFO` & `metarace-roadmeet-1.13.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: metarace-roadmeet
-Version: 1.13.0
+Version: 1.13.1
 Summary: Timing and result application for road cycling events
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace-roadmeet
 Keywords: roadrace,timetrial,transponder
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
```

### Comparing `metarace-roadmeet-1.13.0/README.md` & `metarace-roadmeet-1.13.1/README.md`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/pyproject.toml` & `metarace-roadmeet-1.13.1/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=62"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "metarace-roadmeet"
-version = "1.13.0"
+version = "1.13.1"
 description = "Timing and result application for road cycling events"
 readme = "README.md"
 requires-python = ">=3.9"
 license = {text = "MIT"}
 keywords = ["roadrace", "timetrial", "transponder"]
 authors = [
     {email = "ndf-zz@6-v.org", name = "Nathan Fraser"}
@@ -16,15 +16,15 @@
 classifiers = [
     "Development Status :: 3 - Alpha",
     "Topic :: Other/Nonlisted Topic",
     "Operating System :: OS Independent",
     "Programming Language :: Python :: 3",
 ]
 dependencies = [
-    "metarace>=2.1.1",
+    "metarace>=2.1.2",
 ]
 [project.urls]
 homepage = "https://github.com/ndf-zz/metarace-roadmeet"
 
 [project.scripts]
 roadmeet = "roadmeet:main"
```

### Comparing `metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/PKG-INFO` & `metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: metarace-roadmeet
-Version: 1.13.0
+Version: 1.13.1
 Summary: Timing and result application for road cycling events
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace-roadmeet
 Keywords: roadrace,timetrial,transponder
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
```

### Comparing `metarace-roadmeet-1.13.0/src/metarace_roadmeet.egg-info/SOURCES.txt` & `metarace-roadmeet-1.13.1/src/metarace_roadmeet.egg-info/SOURCES.txt`

 * *Files 17% similar despite different names*

```diff
@@ -10,14 +10,15 @@
 src/metarace_roadmeet.egg-info/top_level.txt
 src/roadmeet/__init__.py
 src/roadmeet/__main__.py
 src/roadmeet/irtt.py
 src/roadmeet/rms.py
 src/roadmeet/trtt.py
 src/roadmeet/uiutil.py
+src/roadmeet/ui/__init__.py
 src/roadmeet/ui/edit_times.ui
 src/roadmeet/ui/irtt.ui
 src/roadmeet/ui/new_start.ui
 src/roadmeet/ui/rider_context.ui
 src/roadmeet/ui/rms.ui
 src/roadmeet/ui/rms_context.ui
 src/roadmeet/ui/roadmeet.ui
```

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/__init__.py` & `metarace-roadmeet-1.13.1/src/roadmeet/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -33,15 +33,15 @@
 from metarace import report
 
 from . import uiutil
 from roadmeet.rms import rms
 from roadmeet.irtt import irtt
 from roadmeet.trtt import trtt
 
-VERSION = '1.13.0'
+VERSION = '1.13.1'
 LOGFILE = 'event.log'
 LOGFILE_LEVEL = logging.DEBUG
 CONFIGFILE = 'config.json'
 ROADMEET_ID = 'roadmeet_3.1'  # configuration versioning
 EXPORTPATH = 'export'
 _log = logging.getLogger('metarace.roadmeet')
 _log.setLevel(logging.DEBUG)
```

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/irtt.py` & `metarace-roadmeet-1.13.1/src/roadmeet/irtt.py`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/rms.py` & `metarace-roadmeet-1.13.1/src/roadmeet/rms.py`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/trtt.py` & `metarace-roadmeet-1.13.1/src/roadmeet/trtt.py`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/edit_times.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/edit_times.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/irtt.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/irtt.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/new_start.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/new_start.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/rider_context.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/rider_context.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/rms.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/rms.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/rms_context.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/rms_context.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/roadmeet.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/roadmeet.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/swap_rider.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/swap_rider.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/ui/tod_context.ui` & `metarace-roadmeet-1.13.1/src/roadmeet/ui/tod_context.ui`

 * *Files identical despite different names*

### Comparing `metarace-roadmeet-1.13.0/src/roadmeet/uiutil.py` & `metarace-roadmeet-1.13.1/src/roadmeet/uiutil.py`

 * *Files identical despite different names*

