# Comparing `tmp/timemanager-1.0.2.tar.gz` & `tmp/timemanager-1.0.3.tar.gz`

## Comparing `timemanager-1.0.2.tar` & `timemanager-1.0.3.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 timemanager-1.0.2/__init__.py
--rw-r--r--   0        0        0      383 2020-02-02 00:00:00.000000 timemanager-1.0.2/setup.py
--rw-r--r--   0        0        0     2241 2020-02-02 00:00:00.000000 timemanager-1.0.2/stopwatch/__init__.py
--rw-r--r--   0        0        0     1613 2020-02-02 00:00:00.000000 timemanager-1.0.2/README.txt
--rw-r--r--   0        0        0      342 2020-02-02 00:00:00.000000 timemanager-1.0.2/pyproject.toml
--rw-r--r--   0        0        0     1721 2020-02-02 00:00:00.000000 timemanager-1.0.2/PKG-INFO
+-rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 timemanager-1.0.3/__init__.py
+-rw-r--r--   0        0        0      357 2020-02-02 00:00:00.000000 timemanager-1.0.3/setup.py
+-rw-r--r--   0        0        0     2241 2020-02-02 00:00:00.000000 timemanager-1.0.3/stopwatch/__init__.py
+-rw-r--r--   0        0        0     1613 2020-02-02 00:00:00.000000 timemanager-1.0.3/README.md
+-rw-r--r--   0        0        0      341 2020-02-02 00:00:00.000000 timemanager-1.0.3/pyproject.toml
+-rw-r--r--   0        0        0     1724 2020-02-02 00:00:00.000000 timemanager-1.0.3/PKG-INFO
```

### Comparing `timemanager-1.0.2/stopwatch/__init__.py` & `timemanager-1.0.3/stopwatch/__init__.py`

 * *Files identical despite different names*

### Comparing `timemanager-1.0.2/README.txt` & `timemanager-1.0.3/README.md`

 * *Files identical despite different names*

### Comparing `timemanager-1.0.2/PKG-INFO` & `timemanager-1.0.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 Metadata-Version: 2.1
 Name: TimeManager
-Version: 1.0.2
+Version: 1.0.3
 Summary: A python module which helps you manage time related tasks.
-Description-Content-Type: text/plain
+Description-Content-Type: text/markdown
 
 # **TimeManager**
 ## *TimeManager.stopwatch:*
 This package acts like a stopwatch which you can start, pause, gettime, and set the stopwatch.
 ### TimeManager.stopwatch.Stopwatch.start:
 *Starts or unpauses the stopwatch*
 **``Example:``**
```

