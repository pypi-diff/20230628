# Comparing `tmp/motion_python-0.1.68.tar.gz` & `tmp/motion_python-0.1.69.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "motion_python-0.1.68.tar", max compression
+gzip compressed data, was "motion_python-0.1.69.tar", max compression
```

## Comparing `motion_python-0.1.68.tar` & `motion_python-0.1.69.tar`

### file list

```diff
@@ -1,12 +1,13 @@
--rw-r--r--   0        0        0     3344 2023-06-23 21:02:09.332829 motion_python-0.1.68/README.md
--rw-r--r--   0        0        0      276 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/__init__.py
--rw-r--r--   0        0        0     3867 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/cli.py
--rw-r--r--   0        0        0    23926 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/component.py
--rw-r--r--   0        0        0    17652 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/execute.py
--rw-r--r--   0        0        0    12849 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/instance.py
--rw-r--r--   0        0        0    13660 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/res/eff_short_wordlist_1.txt
--rw-r--r--   0        0        0      619 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/route.py
--rw-r--r--   0        0        0     5944 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/server/fit_task.py
--rw-r--r--   0        0        0     9481 2023-06-23 21:02:09.332829 motion_python-0.1.68/motion/utils.py
--rw-r--r--   0        0        0     1736 2023-06-23 21:02:29.961208 motion_python-0.1.68/pyproject.toml
--rw-r--r--   0        0        0     4089 1970-01-01 00:00:00.000000 motion_python-0.1.68/PKG-INFO
+-rw-r--r--   0        0        0     3344 2023-06-28 00:45:17.141307 motion_python-0.1.69/README.md
+-rw-r--r--   0        0        0      338 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/__init__.py
+-rw-r--r--   0        0        0     3867 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/cli.py
+-rw-r--r--   0        0        0    23926 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/component.py
+-rw-r--r--   0        0        0    17609 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/execute.py
+-rw-r--r--   0        0        0    13071 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/instance.py
+-rw-r--r--   0        0        0     4889 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/migrate.py
+-rw-r--r--   0        0        0    13660 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/res/eff_short_wordlist_1.txt
+-rw-r--r--   0        0        0      619 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/route.py
+-rw-r--r--   0        0        0     5944 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/server/fit_task.py
+-rw-r--r--   0        0        0     9481 2023-06-28 00:45:17.141307 motion_python-0.1.69/motion/utils.py
+-rw-r--r--   0        0        0     1736 2023-06-28 00:45:38.445933 motion_python-0.1.69/pyproject.toml
+-rw-r--r--   0        0        0     4089 1970-01-01 00:00:00.000000 motion_python-0.1.69/PKG-INFO
```

### Comparing `motion_python-0.1.68/README.md` & `motion_python-0.1.69/README.md`

 * *Files identical despite different names*

### Comparing `motion_python-0.1.68/motion/cli.py` & `motion_python-0.1.69/motion/cli.py`

 * *Files identical despite different names*

### Comparing `motion_python-0.1.68/motion/component.py` & `motion_python-0.1.69/motion/component.py`

 * *Files identical despite different names*

### Comparing `motion_python-0.1.68/motion/execute.py` & `motion_python-0.1.69/motion/execute.py`

 * *Files 0% similar despite different names*

```diff
@@ -233,16 +233,14 @@
 
         # Acquire a lock
         lock_timeout = 5  # Lock timeout in seconds
         lock = Lock(self._redis_con, self._instance_name, lock_timeout)
 
         acquired_lock = lock.acquire(blocking=True)
         if acquired_lock:
-            self._state.update(new_state)
-
             # Get latest state
             self._state = self._loadState()
             self._state.update(new_state)
 
             # Save state to redis
             saveState(
                 self._state,
```

### Comparing `motion_python-0.1.68/motion/instance.py` & `motion_python-0.1.69/motion/instance.py`

 * *Files 2% similar despite different names*

```diff
@@ -62,18 +62,24 @@
             infer_routes=infer_routes,
             fit_routes=fit_routes,
         )
         self.running = True
 
     @property
     def instance_name(self) -> str:
-        """Component name with a random phrase to represent
+        """Component name with a random phrase or user-defined ID to represent
         the name of this instance."""
         return self._instance_name
 
+    @property
+    def instance_id(self) -> str:
+        """Latter part of the instance name, which is a random phrase
+        or a user-defined ID."""
+        return self._instance_name.split("__")[-1]
+
     def shutdown(self) -> None:
         """Shuts down a Motion component instance, saving state.
         Automatically called when the instance is garbage collected.
 
         Usage:
         ```python
         from motion import Component
```

### Comparing `motion_python-0.1.68/motion/res/eff_short_wordlist_1.txt` & `motion_python-0.1.69/motion/res/eff_short_wordlist_1.txt`

 * *Files identical despite different names*

### Comparing `motion_python-0.1.68/motion/route.py` & `motion_python-0.1.69/motion/route.py`

 * *Files identical despite different names*

### Comparing `motion_python-0.1.68/motion/server/fit_task.py` & `motion_python-0.1.69/motion/server/fit_task.py`

 * *Files identical despite different names*

### Comparing `motion_python-0.1.68/motion/utils.py` & `motion_python-0.1.69/motion/utils.py`

 * *Files identical despite different names*

### Comparing `motion_python-0.1.68/pyproject.toml` & `motion_python-0.1.69/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "motion-python"
-version = "0.1.68"
+version = "0.1.69"
 description = "A trigger-based framework for creating and executing ML pipelines."
 authors = ["Shreya Shankar <shreyashankar@berkeley.edu>"]
 readme = "README.md"
 packages = [{include = "motion"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
```

### Comparing `motion_python-0.1.68/PKG-INFO` & `motion_python-0.1.69/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: motion-python
-Version: 0.1.68
+Version: 0.1.69
 Summary: A trigger-based framework for creating and executing ML pipelines.
 Author: Shreya Shankar
 Author-email: shreyashankar@berkeley.edu
 Requires-Python: >=3.9,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
```

