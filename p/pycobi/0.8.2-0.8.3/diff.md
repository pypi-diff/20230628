# Comparing `tmp/pycobi-0.8.2.tar.gz` & `tmp/pycobi-0.8.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pycobi-0.8.2.tar", last modified: Mon Jun 26 21:56:40 2023, max compression
+gzip compressed data, was "pycobi-0.8.3.tar", last modified: Wed Jun 28 15:42:51 2023, max compression
```

## Comparing `pycobi-0.8.2.tar` & `pycobi-0.8.3.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 21:56:40.721067 pycobi-0.8.2/
--rw-r--r--   0 runner    (1001) docker     (123)    35149 2023-06-26 21:56:30.000000 pycobi-0.8.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-26 21:56:30.000000 pycobi-0.8.2/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     4222 2023-06-26 21:56:40.717067 pycobi-0.8.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3319 2023-06-26 21:56:30.000000 pycobi-0.8.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 21:56:40.717067 pycobi-0.8.2/pycobi/
--rw-r--r--   0 runner    (1001) docker     (123)     1291 2023-06-26 21:56:30.000000 pycobi-0.8.2/pycobi/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7664 2023-06-26 21:56:30.000000 pycobi-0.8.2/pycobi/automated_continuation.py
--rw-r--r--   0 runner    (1001) docker     (123)    49943 2023-06-26 21:56:30.000000 pycobi-0.8.2/pycobi/pycobi.py
--rw-r--r--   0 runner    (1001) docker     (123)     8829 2023-06-26 21:56:30.000000 pycobi-0.8.2/pycobi/utility.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 21:56:40.717067 pycobi-0.8.2/pycobi.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4222 2023-06-26 21:56:40.000000 pycobi-0.8.2/pycobi.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-26 21:56:40.000000 pycobi-0.8.2/pycobi.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 21:56:40.000000 pycobi-0.8.2/pycobi.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 21:56:40.000000 pycobi-0.8.2/pycobi.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-26 21:56:40.000000 pycobi-0.8.2/pycobi.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-26 21:56:40.000000 pycobi-0.8.2/pycobi.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 21:56:40.717067 pycobi-0.8.2/pycobi_tests/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-26 21:56:30.000000 pycobi-0.8.2/pycobi_tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      196 2023-06-26 21:56:30.000000 pycobi-0.8.2/pycobi_tests/conftest.py
--rw-r--r--   0 runner    (1001) docker     (123)     2775 2023-06-26 21:56:30.000000 pycobi-0.8.2/pycobi_tests/test_odesystem.py
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 21:56:40.721067 pycobi-0.8.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1635 2023-06-26 21:56:30.000000 pycobi-0.8.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:42:51.765730 pycobi-0.8.3/
+-rw-r--r--   0 runner    (1001) docker     (123)    35149 2023-06-28 15:42:26.000000 pycobi-0.8.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 15:42:26.000000 pycobi-0.8.3/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     4222 2023-06-28 15:42:51.761730 pycobi-0.8.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3319 2023-06-28 15:42:26.000000 pycobi-0.8.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:42:51.761730 pycobi-0.8.3/pycobi/
+-rw-r--r--   0 runner    (1001) docker     (123)     1291 2023-06-28 15:42:26.000000 pycobi-0.8.3/pycobi/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7664 2023-06-28 15:42:26.000000 pycobi-0.8.3/pycobi/automated_continuation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    50272 2023-06-28 15:42:26.000000 pycobi-0.8.3/pycobi/pycobi.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8829 2023-06-28 15:42:26.000000 pycobi-0.8.3/pycobi/utility.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:42:51.761730 pycobi-0.8.3/pycobi.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4222 2023-06-28 15:42:51.000000 pycobi-0.8.3/pycobi.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      384 2023-06-28 15:42:51.000000 pycobi-0.8.3/pycobi.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:42:51.000000 pycobi-0.8.3/pycobi.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:42:51.000000 pycobi-0.8.3/pycobi.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-28 15:42:51.000000 pycobi-0.8.3/pycobi.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 15:42:51.000000 pycobi-0.8.3/pycobi.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:42:51.761730 pycobi-0.8.3/pycobi_tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 15:42:26.000000 pycobi-0.8.3/pycobi_tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      196 2023-06-28 15:42:26.000000 pycobi-0.8.3/pycobi_tests/conftest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2775 2023-06-28 15:42:26.000000 pycobi-0.8.3/pycobi_tests/test_odesystem.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:42:51.765730 pycobi-0.8.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1635 2023-06-28 15:42:26.000000 pycobi-0.8.3/setup.py
```

### Comparing `pycobi-0.8.2/LICENSE` & `pycobi-0.8.3/LICENSE`

 * *Files identical despite different names*

### Comparing `pycobi-0.8.2/PKG-INFO` & `pycobi-0.8.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pycobi
-Version: 0.8.2
+Version: 0.8.3
 Summary: Python tool for parameter continuation and bifurcation analysis
 Home-page: UNKNOWN
 Author: Richard Gast
 Author-email: richard.gast@northwestern.edu
 License: GPL v3
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
```

### Comparing `pycobi-0.8.2/README.md` & `pycobi-0.8.3/README.md`

 * *Files identical despite different names*

### Comparing `pycobi-0.8.2/pycobi/__init__.py` & `pycobi-0.8.3/pycobi/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -25,12 +25,12 @@
 # Richard Gast et al., in preparation.
 
 """Python package for parameter continuations and bifurcation analysis via Auto-07p in Python.
 """
 
 __author__ = "Richard Gast"
 __status__ = "Development"
-__version__ = "0.8.2"
+__version__ = "0.8.3"
 
 from .pycobi import ODESystem
 from .utility import get_lyapunov_exponents, get_solution_eigenvalues, fractal_dimension
 from .automated_continuation import continue_period_doubling_bf, codim2_search
```

### Comparing `pycobi-0.8.2/pycobi/automated_continuation.py` & `pycobi-0.8.3/pycobi/automated_continuation.py`

 * *Files identical despite different names*

### Comparing `pycobi-0.8.2/pycobi/pycobi.py` & `pycobi-0.8.3/pycobi/pycobi.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,14 +15,16 @@
 
 class ODESystem:
 
     __slots__ = ["auto_solutions", "results", "_orig_dir", "dir", "_auto", "_last_cont", "_cont_num", "_results_map",
                  "_branches", "_bifurcation_styles", "_temp", "additional_attributes", "_eq", "_var_map",
                  "_var_map_inv"]
 
+    blocked_indices = (10, 15)
+
     def __init__(self, eq_file: str, working_dir: str = None, auto_dir: str = None, init_cont: bool = True,
                  params: list = None, state_vars: list = None, **kwargs) -> None:
         """
 
         Parameters
         ----------
         eq_file
@@ -88,16 +90,22 @@
                                     }
         self._temp = kwargs.pop("template", None)
 
         # create a map that links variable/parameter indices to string-based keys
         self._var_map = {"t": {"cont": 14, "plot": "PAR(14)"}}
         self._var_map_inv = {}
         if params:
+            increment = 1
             for i, key in enumerate(params):
-                self._var_map[key] = {"cont": i+1, "plot": f"PAR({i+1})"}
+                idx = i + increment
+                if self.blocked_indices[0] <= idx <= self.blocked_indices[1]:
+                    idx -= increment
+                    increment += self.blocked_indices[1] - self.blocked_indices[0]
+                    idx += increment
+                self._var_map[key] = {"cont": idx, "plot": f"PAR({idx})"}
         if state_vars:
             for i, key in enumerate(state_vars):
                 self._var_map[key] = {"cont": i+1, "plot": f"U({i+1})"}
         for key, val in self._var_map.items():
             self._var_map_inv[val["cont"]] = key
             self._var_map_inv[val["plot"]] = key
```

### Comparing `pycobi-0.8.2/pycobi/utility.py` & `pycobi-0.8.3/pycobi/utility.py`

 * *Files identical despite different names*

### Comparing `pycobi-0.8.2/pycobi.egg-info/PKG-INFO` & `pycobi-0.8.3/pycobi.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pycobi
-Version: 0.8.2
+Version: 0.8.3
 Summary: Python tool for parameter continuation and bifurcation analysis
 Home-page: UNKNOWN
 Author: Richard Gast
 Author-email: richard.gast@northwestern.edu
 License: GPL v3
 Platform: UNKNOWN
 Classifier: Programming Language :: Python :: 3
```

### Comparing `pycobi-0.8.2/pycobi_tests/__init__.py` & `pycobi-0.8.3/pycobi_tests/__init__.py`

 * *Files identical despite different names*

### Comparing `pycobi-0.8.2/pycobi_tests/test_odesystem.py` & `pycobi-0.8.3/pycobi_tests/test_odesystem.py`

 * *Files identical despite different names*

### Comparing `pycobi-0.8.2/setup.py` & `pycobi-0.8.3/setup.py`

 * *Files identical despite different names*

