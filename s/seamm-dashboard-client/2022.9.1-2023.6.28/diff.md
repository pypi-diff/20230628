# Comparing `tmp/seamm_dashboard_client-2022.9.1.tar.gz` & `tmp/seamm_dashboard_client-2023.6.28.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "seamm_dashboard_client-2022.9.1.tar", last modified: Thu Sep  1 10:21:01 2022, max compression
+gzip compressed data, was "seamm_dashboard_client-2023.6.28.tar", last modified: Wed Jun 28 12:35:35 2023, max compression
```

## Comparing `seamm_dashboard_client-2022.9.1.tar` & `seamm_dashboard_client-2023.6.28.tar`

### file list

```diff
@@ -1,44 +1,44 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-01 10:21:01.829234 seamm_dashboard_client-2022.9.1/
--rw-r--r--   0 runner    (1001) docker     (121)      151 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/AUTHORS.rst
--rw-r--r--   0 runner    (1001) docker     (121)     3286 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/CONTRIBUTING.rst
--rw-r--r--   0 runner    (1001) docker     (121)      126 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/HISTORY.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1520 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)      358 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (121)     3211 2022-09-01 10:21:01.829234 seamm_dashboard_client-2022.9.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     2150 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-01 10:21:01.825234 seamm_dashboard_client-2022.9.1/docs/
--rw-r--r--   0 runner    (1001) docker     (121)     6826 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/Makefile
--rw-r--r--   0 runner    (1001) docker     (121)       28 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/authors.rst
--rwxr-xr-x   0 runner    (1001) docker     (121)     8842 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/conf.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-01 10:21:01.825234 seamm_dashboard_client-2022.9.1/docs/developer/
--rw-r--r--   0 runner    (1001) docker     (121)      674 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/developer/cms_plots.rst
--rw-r--r--   0 runner    (1001) docker     (121)       36 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/developer/contributing.rst
--rw-r--r--   0 runner    (1001) docker     (121)      244 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/developer/index.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1219 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/developer/installation.rst
--rw-r--r--   0 runner    (1001) docker     (121)       30 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/developer/readme.rst
--rw-r--r--   0 runner    (1001) docker     (121)       91 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/developer/usage.rst
--rw-r--r--   0 runner    (1001) docker     (121)       28 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/history.rst
--rw-r--r--   0 runner    (1001) docker     (121)      615 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (121)     6491 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/make.bat
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-01 10:21:01.825234 seamm_dashboard_client-2022.9.1/docs/user/
--rw-r--r--   0 runner    (1001) docker     (121)      185 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/user/index.rst
--rw-r--r--   0 runner    (1001) docker     (121)       59 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/docs/user/overview.rst
--rw-r--r--   0 runner    (1001) docker     (121)       29 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (121)      135 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/requirements_dev.txt
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-01 10:21:01.829234 seamm_dashboard_client-2022.9.1/seamm_dashboard_client/
--rw-r--r--   0 runner    (1001) docker     (121)      749 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)      500 2022-09-01 10:21:01.829234 seamm_dashboard_client-2022.9.1/seamm_dashboard_client/_version.py
--rw-r--r--   0 runner    (1001) docker     (121)    27549 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client/dashboard.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-01 10:21:01.825234 seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     3211 2022-09-01 10:21:01.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      862 2022-09-01 10:21:01.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-09-01 10:21:01.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       27 2022-09-01 10:21:01.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)       23 2022-09-01 10:21:01.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-09-01 10:20:47.000000 seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/zip-safe
--rw-r--r--   0 runner    (1001) docker     (121)      396 2022-09-01 10:21:01.829234 seamm_dashboard_client-2022.9.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)     2706 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-01 10:21:01.829234 seamm_dashboard_client-2022.9.1/tests/
--rw-r--r--   0 runner    (1001) docker     (121)       68 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)    31497 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/tests/test_dashboard.py
--rw-r--r--   0 runner    (1001) docker     (121)    68611 2022-09-01 10:20:45.000000 seamm_dashboard_client-2022.9.1/versioneer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:35.796145 seamm_dashboard_client-2023.6.28/
+-rw-r--r--   0 runner    (1001) docker     (123)      151 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/AUTHORS.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     3286 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/CONTRIBUTING.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      184 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/HISTORY.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1520 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     3270 2023-06-28 12:35:35.796145 seamm_dashboard_client-2023.6.28/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2150 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:35.788145 seamm_dashboard_client-2023.6.28/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     6826 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/authors.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)     8842 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/conf.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:35.792145 seamm_dashboard_client-2023.6.28/docs/developer/
+-rw-r--r--   0 runner    (1001) docker     (123)      674 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/developer/cms_plots.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/developer/contributing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      244 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/developer/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1219 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/developer/installation.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/developer/readme.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       91 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/developer/usage.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/history.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      615 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     6491 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/make.bat
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:35.792145 seamm_dashboard_client-2023.6.28/docs/user/
+-rw-r--r--   0 runner    (1001) docker     (123)      185 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/user/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/docs/user/overview.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/requirements_dev.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:35.796145 seamm_dashboard_client-2023.6.28/seamm_dashboard_client/
+-rw-r--r--   0 runner    (1001) docker     (123)      869 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-28 12:35:35.796145 seamm_dashboard_client-2023.6.28/seamm_dashboard_client/_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27896 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client/dashboard.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:35.796145 seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3270 2023-06-28 12:35:35.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      862 2023-06-28 12:35:35.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:35:35.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 12:35:35.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 12:35:35.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:35:18.000000 seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      396 2023-06-28 12:35:35.796145 seamm_dashboard_client-2023.6.28/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2706 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:35:35.796145 seamm_dashboard_client-2023.6.28/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31497 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/tests/test_dashboard.py
+-rw-r--r--   0 runner    (1001) docker     (123)    68611 2023-06-28 12:35:11.000000 seamm_dashboard_client-2023.6.28/versioneer.py
```

### Comparing `seamm_dashboard_client-2022.9.1/CONTRIBUTING.rst` & `seamm_dashboard_client-2023.6.28/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/LICENSE` & `seamm_dashboard_client-2023.6.28/LICENSE`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/PKG-INFO` & `seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: seamm_dashboard_client
-Version: 2022.9.1
+Name: seamm-dashboard-client
+Version: 2023.6.28
 Summary: A Python client for the SEAMM Dashboard RESTful API.
 Home-page: https://github.com/molssi-seamm/seamm_dashboard_client
 Author: Paul Saxe
 Author-email: psaxe@molssi.org
 License: BSD-3-Clause
 Keywords: SEAMM,SEAMMDashboard,RESTful,client
 Platform: Linux
@@ -86,11 +86,13 @@
 .. _MolSSI: https://molssi.org
 
 
 =======
 History
 =======
 
+2023.6.28 -- Improved error messages for login failures.
+
 2022.8.13 (13 August 2022)
 --------------------------
 
 * First release of a working version on PyPI.
```

### Comparing `seamm_dashboard_client-2022.9.1/README.rst` & `seamm_dashboard_client-2023.6.28/README.rst`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/docs/Makefile` & `seamm_dashboard_client-2023.6.28/docs/Makefile`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/docs/conf.py` & `seamm_dashboard_client-2023.6.28/docs/conf.py`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/docs/developer/cms_plots.rst` & `seamm_dashboard_client-2023.6.28/docs/developer/cms_plots.rst`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/docs/developer/installation.rst` & `seamm_dashboard_client-2023.6.28/docs/developer/installation.rst`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/docs/index.rst` & `seamm_dashboard_client-2023.6.28/docs/index.rst`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/docs/make.bat` & `seamm_dashboard_client-2023.6.28/docs/make.bat`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/seamm_dashboard_client/__init__.py` & `seamm_dashboard_client-2023.6.28/seamm_dashboard_client/__init__.py`

 * *Files 26% similar despite different names*

```diff
@@ -7,14 +7,16 @@
 # Bring up the classes so that they appear to be directly in
 # the seamm_dashboard_client
 
 # Main classes
 from .dashboard import Dashboard  # noqa: F401
 from .dashboard import DashboardConnectionError  # noqa: F401
 from .dashboard import DashboardLoginError  # noqa: F401
+from .dashboard import DashboardNotRunningError  # noqa: F401
+from .dashboard import DashboardSubmitError  # noqa: F401
 from .dashboard import DashboardTimeoutError  # noqa: F401
 from .dashboard import DashboardUnknownError  # noqa: F401
 
 # Handle versioneer
 from ._version import get_versions
 
 __author__ = """Paul Saxe"""
```

### Comparing `seamm_dashboard_client-2022.9.1/seamm_dashboard_client/dashboard.py` & `seamm_dashboard_client-2023.6.28/seamm_dashboard_client/dashboard.py`

 * *Files 0% similar despite different names*

```diff
@@ -326,17 +326,27 @@
             )
         except Exception as e:
             raise DashboardConnectionError(
                 self.url,
                 f"Unknown error with the dashboard '{self.name}': ({type(e)}) {str(e)}",
             )
         else:
-            if response.status_code == 403:
+            if response.status_code == 400:
+                try:
+                    result = response.json()["msg"]
+                except Exception:
+                    result = "unknown reason"
+
                 raise DashboardLoginError(
-                    url, f"Could not log in to dashboard {self.name} as {self.username}"
+                    url,
+                    (
+                        f"Could not log in to dashboard {self.name} as "
+                        f"{self.username} / {self.password} ({result}). "
+                        "Check ~/.seammrc for this information."
+                    ),
                 )  # lgtm [py/clear-text-logging-sensitive-data]
             elif response.status_code != 200:
                 raise DashboardLoginError(
                     url,
                     f"The dashboard {self.name} returned an error: code = "
                     f"{response.status_code}",
                 )
```

### Comparing `seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/PKG-INFO` & `seamm_dashboard_client-2023.6.28/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: seamm-dashboard-client
-Version: 2022.9.1
+Name: seamm_dashboard_client
+Version: 2023.6.28
 Summary: A Python client for the SEAMM Dashboard RESTful API.
 Home-page: https://github.com/molssi-seamm/seamm_dashboard_client
 Author: Paul Saxe
 Author-email: psaxe@molssi.org
 License: BSD-3-Clause
 Keywords: SEAMM,SEAMMDashboard,RESTful,client
 Platform: Linux
@@ -86,11 +86,13 @@
 .. _MolSSI: https://molssi.org
 
 
 =======
 History
 =======
 
+2023.6.28 -- Improved error messages for login failures.
+
 2022.8.13 (13 August 2022)
 --------------------------
 
 * First release of a working version on PyPI.
```

### Comparing `seamm_dashboard_client-2022.9.1/seamm_dashboard_client.egg-info/SOURCES.txt` & `seamm_dashboard_client-2023.6.28/seamm_dashboard_client.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/setup.py` & `seamm_dashboard_client-2023.6.28/setup.py`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/tests/test_dashboard.py` & `seamm_dashboard_client-2023.6.28/tests/test_dashboard.py`

 * *Files identical despite different names*

### Comparing `seamm_dashboard_client-2022.9.1/versioneer.py` & `seamm_dashboard_client-2023.6.28/versioneer.py`

 * *Files identical despite different names*

