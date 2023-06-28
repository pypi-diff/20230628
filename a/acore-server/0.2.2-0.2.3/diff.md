# Comparing `tmp/acore_server-0.2.2.tar.gz` & `tmp/acore_server-0.2.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "acore_server-0.2.2.tar", last modified: Wed Jun 28 13:19:17 2023, max compression
+gzip compressed data, was "acore_server-0.2.3.tar", last modified: Wed Jun 28 14:53:10 2023, max compression
```

## Comparing `acore_server-0.2.2.tar` & `acore_server-0.2.3.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545831 acore_server-0.2.2/
--rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-27 04:12:52.000000 acore_server-0.2.2/AUTHORS.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)     1123 2023-06-27 04:12:52.000000 acore_server-0.2.2/LICENSE.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      320 2023-06-27 04:12:52.000000 acore_server-0.2.2/MANIFEST.in
--rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-28 13:19:17.545673 acore_server-0.2.2/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     3694 2023-06-27 05:07:58.000000 acore_server-0.2.2/README.rst
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.543789 acore_server-0.2.2/acore_server/
--rw-r--r--   0 sanhehu    (501) staff       (20)      393 2023-06-27 04:56:34.000000 acore_server-0.2.2/acore_server/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 13:18:23.000000 acore_server-0.2.2/acore_server/_version.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      145 2023-06-27 04:49:35.000000 acore_server-0.2.2/acore_server/api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      107 2023-06-27 04:26:27.000000 acore_server-0.2.2/acore_server/constants.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.544586 acore_server-0.2.2/acore_server/docs/
--rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/docs/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)    17282 2023-06-27 20:47:28.000000 acore_server-0.2.2/acore_server/fleet.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      936 2023-06-27 04:26:42.000000 acore_server-0.2.2/acore_server/paths.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545001 acore_server-0.2.2/acore_server/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/tests/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/tests/helper.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545270 acore_server-0.2.2/acore_server/vendor/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/vendor/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/vendor/pytest_cov_helper.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3272 2023-06-26 05:55:10.000000 acore_server-0.2.2/acore_server/wserver_infra_exports.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.544479 acore_server-0.2.2/acore_server.egg-info/
--rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)      722 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/SOURCES.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/dependency_links.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      392 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/requires.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       13 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/top_level.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)     1399 2023-06-28 13:18:53.000000 acore_server-0.2.2/release-history.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-automation.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-dev.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-doc.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      183 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-test.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      253 2023-06-28 13:17:07.000000 acore_server-0.2.2/requirements.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 13:19:17.545869 acore_server-0.2.2/setup.cfg
--rw-r--r--   0 sanhehu    (501) staff       (20)     7561 2023-06-27 04:12:52.000000 acore_server-0.2.2/setup.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545401 acore_server-0.2.2/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)     1016 2023-06-27 14:01:20.000000 acore_server-0.2.2/tests/test_api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:53:10.846741 acore_server-0.2.3/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-27 04:12:52.000000 acore_server-0.2.3/AUTHORS.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1123 2023-06-27 04:12:52.000000 acore_server-0.2.3/LICENSE.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      320 2023-06-27 04:12:52.000000 acore_server-0.2.3/MANIFEST.in
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-28 14:53:10.846626 acore_server-0.2.3/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3694 2023-06-27 05:07:58.000000 acore_server-0.2.3/README.rst
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:53:10.844677 acore_server-0.2.3/acore_server/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      393 2023-06-27 04:56:34.000000 acore_server-0.2.3/acore_server/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 14:52:01.000000 acore_server-0.2.3/acore_server/_version.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      145 2023-06-27 04:49:35.000000 acore_server-0.2.3/acore_server/api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      107 2023-06-27 04:26:27.000000 acore_server-0.2.3/acore_server/constants.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:53:10.845481 acore_server-0.2.3/acore_server/docs/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-27 04:12:52.000000 acore_server-0.2.3/acore_server/docs/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)    17282 2023-06-28 14:51:08.000000 acore_server-0.2.3/acore_server/fleet.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      936 2023-06-27 04:26:42.000000 acore_server-0.2.3/acore_server/paths.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:53:10.845956 acore_server-0.2.3/acore_server/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-27 04:12:52.000000 acore_server-0.2.3/acore_server/tests/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-27 04:12:52.000000 acore_server-0.2.3/acore_server/tests/helper.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:53:10.846231 acore_server-0.2.3/acore_server/vendor/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-27 04:12:52.000000 acore_server-0.2.3/acore_server/vendor/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-27 04:12:52.000000 acore_server-0.2.3/acore_server/vendor/pytest_cov_helper.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3272 2023-06-26 05:55:10.000000 acore_server-0.2.3/acore_server/wserver_infra_exports.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:53:10.845372 acore_server-0.2.3/acore_server.egg-info/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-28 14:53:10.000000 acore_server-0.2.3/acore_server.egg-info/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)      722 2023-06-28 14:53:10.000000 acore_server-0.2.3/acore_server.egg-info/SOURCES.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 14:53:10.000000 acore_server-0.2.3/acore_server.egg-info/dependency_links.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      392 2023-06-28 14:53:10.000000 acore_server-0.2.3/acore_server.egg-info/requires.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       13 2023-06-28 14:53:10.000000 acore_server-0.2.3/acore_server.egg-info/top_level.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1542 2023-06-28 14:52:21.000000 acore_server-0.2.3/release-history.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-27 04:12:52.000000 acore_server-0.2.3/requirements-automation.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-27 04:12:52.000000 acore_server-0.2.3/requirements-dev.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-27 04:12:52.000000 acore_server-0.2.3/requirements-doc.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      183 2023-06-27 04:12:52.000000 acore_server-0.2.3/requirements-test.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      253 2023-06-28 14:46:48.000000 acore_server-0.2.3/requirements.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 14:53:10.846775 acore_server-0.2.3/setup.cfg
+-rw-r--r--   0 sanhehu    (501) staff       (20)     7561 2023-06-27 04:12:52.000000 acore_server-0.2.3/setup.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:53:10.846364 acore_server-0.2.3/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1016 2023-06-27 14:01:20.000000 acore_server-0.2.3/tests/test_api.py
```

### Comparing `acore_server-0.2.2/AUTHORS.rst` & `acore_server-0.2.3/AUTHORS.rst`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/LICENSE.txt` & `acore_server-0.2.3/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/PKG-INFO` & `acore_server-0.2.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore_server
-Version: 0.2.2
+Version: 0.2.3
 Summary: AzerothCore World of Warcraft Logic Server Data Model.
 Home-page: https://github.com/MacHu-GWU/acore_server-project
-Download-URL: https://pypi.python.org/pypi/acore_server/0.2.2#downloads
+Download-URL: https://pypi.python.org/pypi/acore_server/0.2.3#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_server-0.2.2/README.rst` & `acore_server-0.2.3/README.rst`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/acore_server/fleet.py` & `acore_server-0.2.3/acore_server/fleet.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/acore_server/paths.py` & `acore_server-0.2.3/acore_server/paths.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/acore_server/vendor/pytest_cov_helper.py` & `acore_server-0.2.3/acore_server/vendor/pytest_cov_helper.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/acore_server/wserver_infra_exports.py` & `acore_server-0.2.3/acore_server/wserver_infra_exports.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/acore_server.egg-info/PKG-INFO` & `acore_server-0.2.3/acore_server.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore-server
-Version: 0.2.2
+Version: 0.2.3
 Summary: AzerothCore World of Warcraft Logic Server Data Model.
 Home-page: https://github.com/MacHu-GWU/acore_server-project
-Download-URL: https://pypi.python.org/pypi/acore_server/0.2.2#downloads
+Download-URL: https://pypi.python.org/pypi/acore_server/0.2.3#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_server-0.2.2/acore_server.egg-info/SOURCES.txt` & `acore_server-0.2.3/acore_server.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/release-history.rst` & `acore_server-0.2.3/release-history.rst`

 * *Files 16% similar despite different names*

```diff
@@ -11,14 +11,21 @@
 **Minor Improvements**
 
 **Bugfixes**
 
 **Miscellaneous**
 
 
+0.2.3 (2023-06-28)
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+**Miscellaneous**
+
+- Upgrade dependencies.
+
+
 0.2.2 (2023-06-28)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Miscellaneous**
 
 - Remove unnecessary dependencies.
```

### Comparing `acore_server-0.2.2/requirements-doc.txt` & `acore_server-0.2.3/requirements-doc.txt`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/setup.py` & `acore_server-0.2.3/setup.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.2/tests/test_api.py` & `acore_server-0.2.3/tests/test_api.py`

 * *Files identical despite different names*

