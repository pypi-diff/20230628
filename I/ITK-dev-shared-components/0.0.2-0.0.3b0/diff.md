# Comparing `tmp/ITK_dev_shared_components-0.0.2.tar.gz` & `tmp/ITK_dev_shared_components-0.0.3b0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ITK_dev_shared_components-0.0.2.tar", last modified: Wed Jun 28 09:05:36 2023, max compression
+gzip compressed data, was "ITK_dev_shared_components-0.0.3b0.tar", last modified: Wed Jun 28 10:16:32 2023, max compression
```

## Comparing `ITK_dev_shared_components-0.0.2.tar` & `ITK_dev_shared_components-0.0.3b0.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      656 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.619444 ITK_dev_shared_components-0.0.2/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/
--rw-r--r--   0 runner    (1001) docker     (123)     3610 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/multi_session.py
--rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/sap_login.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:24.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:05:36.623444 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 09:05:36.000000 ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:16:32.215279 ITK_dev_shared_components-0.0.3b0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 10:16:22.000000 ITK_dev_shared_components-0.0.3b0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-28 10:16:32.215279 ITK_dev_shared_components-0.0.3b0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)       82 2023-06-28 10:16:22.000000 ITK_dev_shared_components-0.0.3b0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      657 2023-06-28 10:16:22.000000 ITK_dev_shared_components-0.0.3b0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:16:32.215279 ITK_dev_shared_components-0.0.3b0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:16:32.211279 ITK_dev_shared_components-0.0.3b0/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:16:32.211279 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:16:32.215279 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components/SAP/
+-rw-r--r--   0 runner    (1001) docker     (123)     3839 2023-06-28 10:16:22.000000 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components/SAP/multi_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1397 2023-06-28 10:16:22.000000 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components/SAP/sap_login.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 10:16:22.000000 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:16:32.215279 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      665 2023-06-28 10:16:32.000000 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 10:16:32.000000 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:16:32.000000 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 10:16:32.000000 ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components.egg-info/top_level.txt
```

### Comparing `ITK_dev_shared_components-0.0.2/LICENSE` & `ITK_dev_shared_components-0.0.3b0/LICENSE`

 * *Files identical despite different names*

### Comparing `ITK_dev_shared_components-0.0.2/PKG-INFO` & `ITK_dev_shared_components-0.0.3b0/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,17 +1,19 @@
 Metadata-Version: 2.1
 Name: ITK_dev_shared_components
-Version: 0.0.2
+Version: 0.0.3b0
 Summary: Shared components to use in RPA projects
 Author-email: ITK Development <itk-rpa@mkb.aarhus.dk>
 Project-URL: Homepage, https://github.com/itk-dev-rpa/itk-dev-shared-components
 Project-URL: Bug Tracker, https://github.com/itk-dev-rpa/itk-dev-shared-components/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: Microsoft :: Windows
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # itk-dev-shared-components
 
+pip install ITK-dev-shared-components
+
 Version 0.0.2
```

### Comparing `ITK_dev_shared_components-0.0.2/pyproject.toml` & `ITK_dev_shared_components-0.0.3b0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=65.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "ITK_dev_shared_components"
-version = "0.0.2"
+version = "0.0.3b"
 authors = [
   { name="ITK Development", email="itk-rpa@mkb.aarhus.dk" },
 ]
 description = "Shared components to use in RPA projects"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/multi_session.py` & `ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components/SAP/multi_session.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,16 +1,18 @@
 import pythoncom
 import win32com.client
 import win32gui
 import threading
+from typing import Callable
 
-def run_with_session(session_index:int, func:function, args:tuple) -> None:
+def run_with_session(session_index:int, func:Callable, args:tuple) -> None:
     """Run a function in a sepcific session based on the sessions index.
     
     This function is meant to be run inside a seperate thread.
+    The function must take a session object as its first argument.
     Note that this function will not spawn the sessions before running,
     use spawn_sessions to do that.
     """
 
     pythoncom.CoInitialize()
 
     SAP = win32com.client.GetObject("SAPGUI")
@@ -18,18 +20,19 @@
     connection = app.Connections(0)
     session = connection.Sessions(session_index)
 
     func(session, *args)
 
     pythoncom.CoUninitialize()
 
-def run_batch(func:function, args:tuple[tuple], num_sessions=6) -> None:
+def run_batch(func:Callable, args:tuple[tuple], num_sessions=6) -> None:
     """Run a function in parallel sessions.
     
     The function will be run {num_sessions} times with args[i] as input.
+    The function must take a session object as its first argument.
     Note that this function will not spawn the sessions before running,
     use spawn_sessions to do that.
     """
 
     threads = []
     for i in range(num_sessions):
         t = ExThread(target=run_with_session, args=(i, func, args[i]))
@@ -39,19 +42,20 @@
         t.start()
     for t in threads:
         t.join()
     for t in threads:
         if t.error:
             raise t.error
 
-def run_batches(func:function, args:tuple[tuple], num_sessions=6):
+def run_batches(func:Callable, args:tuple[tuple], num_sessions=6):
     """Run a function in parallel batches.
     
     This function runs the input function for each set of arguments in args.
     The function will be run in parallel batches of size {num_sessions}.
+    The function must take a session object as its first argument.
     Note that this function will not spawn the sessions before running,
     use spawn_sessions to do that.
     """
 
     for b in range(0, len(args), num_sessions):
         batch = args[b:b+num_sessions]
         run_batch(func, args, len(batch))
```

### Comparing `ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components/SAP/sap_login.py` & `ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components/SAP/sap_login.py`

 * *Files identical despite different names*

### Comparing `ITK_dev_shared_components-0.0.2/src/ITK_dev_shared_components.egg-info/PKG-INFO` & `ITK_dev_shared_components-0.0.3b0/src/ITK_dev_shared_components.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,17 +1,19 @@
 Metadata-Version: 2.1
 Name: ITK-dev-shared-components
-Version: 0.0.2
+Version: 0.0.3b0
 Summary: Shared components to use in RPA projects
 Author-email: ITK Development <itk-rpa@mkb.aarhus.dk>
 Project-URL: Homepage, https://github.com/itk-dev-rpa/itk-dev-shared-components
 Project-URL: Bug Tracker, https://github.com/itk-dev-rpa/itk-dev-shared-components/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: Microsoft :: Windows
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # itk-dev-shared-components
 
+pip install ITK-dev-shared-components
+
 Version 0.0.2
```

