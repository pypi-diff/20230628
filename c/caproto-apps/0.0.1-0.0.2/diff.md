# Comparing `tmp/caproto-apps-0.0.1.tar.gz` & `tmp/caproto-apps-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "caproto-apps-0.0.1.tar", last modified: Wed Jun 28 15:52:49 2023, max compression
+gzip compressed data, was "caproto-apps-0.0.2.tar", last modified: Wed Jun 28 15:54:36 2023, max compression
```

## Comparing `caproto-apps-0.0.1.tar` & `caproto-apps-0.0.2.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:52:49.303151 caproto-apps-0.0.1/
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)     2709 2023-06-28 15:52:49.302150 caproto-apps-0.0.1/PKG-INFO
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)     2150 2023-06-28 15:49:57.000000 caproto-apps-0.0.1/README.md
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)     1033 2023-06-28 15:16:48.000000 caproto-apps-0.0.1/pyproject.toml
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)       38 2023-06-28 15:52:49.304146 caproto-apps-0.0.1/setup.cfg
-drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:52:49.268155 caproto-apps-0.0.1/src/
-drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:52:49.289150 caproto-apps-0.0.1/src/caproto_apps.egg-info/
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)     2709 2023-06-28 15:52:49.000000 caproto-apps-0.0.1/src/caproto_apps.egg-info/PKG-INFO
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)      296 2023-06-28 15:52:49.000000 caproto-apps-0.0.1/src/caproto_apps.egg-info/SOURCES.txt
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)        1 2023-06-28 15:52:49.000000 caproto-apps-0.0.1/src/caproto_apps.egg-info/dependency_links.txt
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)       55 2023-06-28 15:52:49.000000 caproto-apps-0.0.1/src/caproto_apps.egg-info/requires.txt
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)       12 2023-06-28 15:52:49.000000 caproto-apps-0.0.1/src/caproto_apps.egg-info/top_level.txt
-drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:52:49.295160 caproto-apps-0.0.1/src/caprotoapps/
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)       30 2023-06-24 19:50:08.000000 caproto-apps-0.0.1/src/caprotoapps/__init__.py
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)    20766 2023-06-28 04:14:07.000000 caproto-apps-0.0.1/src/caprotoapps/alive.py
-drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:52:49.299149 caproto-apps-0.0.1/tests/
--rw-r--r--   0 b268176   (2319) xsdspc    (1117)    10782 2023-06-28 04:08:59.000000 caproto-apps-0.0.1/tests/test_alive.py
+drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:54:36.173908 caproto-apps-0.0.2/
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)     2760 2023-06-28 15:54:36.171917 caproto-apps-0.0.2/PKG-INFO
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)     2201 2023-06-28 15:54:15.000000 caproto-apps-0.0.2/README.md
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)     1033 2023-06-28 15:54:24.000000 caproto-apps-0.0.2/pyproject.toml
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)       38 2023-06-28 15:54:36.173914 caproto-apps-0.0.2/setup.cfg
+drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:54:36.141926 caproto-apps-0.0.2/src/
+drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:54:36.160923 caproto-apps-0.0.2/src/caproto_apps.egg-info/
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)     2760 2023-06-28 15:54:36.000000 caproto-apps-0.0.2/src/caproto_apps.egg-info/PKG-INFO
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)      296 2023-06-28 15:54:36.000000 caproto-apps-0.0.2/src/caproto_apps.egg-info/SOURCES.txt
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)        1 2023-06-28 15:54:36.000000 caproto-apps-0.0.2/src/caproto_apps.egg-info/dependency_links.txt
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)       55 2023-06-28 15:54:36.000000 caproto-apps-0.0.2/src/caproto_apps.egg-info/requires.txt
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)       12 2023-06-28 15:54:36.000000 caproto-apps-0.0.2/src/caproto_apps.egg-info/top_level.txt
+drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:54:36.166911 caproto-apps-0.0.2/src/caprotoapps/
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)       30 2023-06-24 19:50:08.000000 caproto-apps-0.0.2/src/caprotoapps/__init__.py
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)    20766 2023-06-28 04:14:07.000000 caproto-apps-0.0.2/src/caprotoapps/alive.py
+drwxr-xr-x   0 b268176   (2319) xsdspc    (1117)        0 2023-06-28 15:54:36.169910 caproto-apps-0.0.2/tests/
+-rw-r--r--   0 b268176   (2319) xsdspc    (1117)    10782 2023-06-28 04:08:59.000000 caproto-apps-0.0.2/tests/test_alive.py
```

### Comparing `caproto-apps-0.0.1/PKG-INFO` & `caproto-apps-0.0.2/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,31 +1,37 @@
 Metadata-Version: 2.1
 Name: caproto-apps
-Version: 0.0.1
+Version: 0.0.2
 Summary: Variety of useful extensions for caproto IOCs.
 Author-email: Mark Wolfman <wolfman@anl.gov>
 Project-URL: Homepage, https://github.com/canismarko/caproto-apps
 Keywords: caproto,controls
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: System :: Hardware
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 
-# caproto-apps
+# Caproto Apps
 
 [![Tests](https://github.com/canismarko/caproto-apps/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/canismarko/caproto-apps/actions/workflows/ci.yml)
 
 Implementations of select EPICS-compatible records in caproto.
 
 Currently the only app available is the **Alive** app.
 
+## Installation
+
+```
+pip install caproto-apps
+```
+
 ## Alive
 
 The AliveGroup provides equivalent functionality to the
 [EPICS alive record](http://epics-modules.github.io/alive/aliveRecord.html)
 and is compatible with existing
 [alive daemons](https://epics-alive-server.github.io/alive-overview.html).
```

### Comparing `caproto-apps-0.0.1/README.md` & `caproto-apps-0.0.2/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,15 +1,21 @@
-# caproto-apps
+# Caproto Apps
 
 [![Tests](https://github.com/canismarko/caproto-apps/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/canismarko/caproto-apps/actions/workflows/ci.yml)
 
 Implementations of select EPICS-compatible records in caproto.
 
 Currently the only app available is the **Alive** app.
 
+## Installation
+
+```
+pip install caproto-apps
+```
+
 ## Alive
 
 The AliveGroup provides equivalent functionality to the
 [EPICS alive record](http://epics-modules.github.io/alive/aliveRecord.html)
 and is compatible with existing
 [alive daemons](https://epics-alive-server.github.io/alive-overview.html).
```

### Comparing `caproto-apps-0.0.1/pyproject.toml` & `caproto-apps-0.0.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 
 # [build-system]
 # requires = ["hatchling"]
 # build-backend = "hatchling.build"
 
 [project]
 name = "caproto-apps"
-version = "0.0.1"
+version = "0.0.2"
 authors = [
   { name="Mark Wolfman", email="wolfman@anl.gov" },
 ]
 description = "Variety of useful extensions for caproto IOCs."
 readme = "README.md"
 requires-python = ">=3.10"
 classifiers = [
```

### Comparing `caproto-apps-0.0.1/src/caproto_apps.egg-info/PKG-INFO` & `caproto-apps-0.0.2/src/caproto_apps.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,31 +1,37 @@
 Metadata-Version: 2.1
 Name: caproto-apps
-Version: 0.0.1
+Version: 0.0.2
 Summary: Variety of useful extensions for caproto IOCs.
 Author-email: Mark Wolfman <wolfman@anl.gov>
 Project-URL: Homepage, https://github.com/canismarko/caproto-apps
 Keywords: caproto,controls
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: System :: Hardware
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 
-# caproto-apps
+# Caproto Apps
 
 [![Tests](https://github.com/canismarko/caproto-apps/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/canismarko/caproto-apps/actions/workflows/ci.yml)
 
 Implementations of select EPICS-compatible records in caproto.
 
 Currently the only app available is the **Alive** app.
 
+## Installation
+
+```
+pip install caproto-apps
+```
+
 ## Alive
 
 The AliveGroup provides equivalent functionality to the
 [EPICS alive record](http://epics-modules.github.io/alive/aliveRecord.html)
 and is compatible with existing
 [alive daemons](https://epics-alive-server.github.io/alive-overview.html).
```

### Comparing `caproto-apps-0.0.1/src/caprotoapps/alive.py` & `caproto-apps-0.0.2/src/caprotoapps/alive.py`

 * *Files identical despite different names*

### Comparing `caproto-apps-0.0.1/tests/test_alive.py` & `caproto-apps-0.0.2/tests/test_alive.py`

 * *Files identical despite different names*

