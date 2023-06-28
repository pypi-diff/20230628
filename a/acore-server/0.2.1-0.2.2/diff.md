# Comparing `tmp/acore_server-0.2.1.tar.gz` & `tmp/acore_server-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "acore_server-0.2.1.tar", last modified: Tue Jun 27 20:54:09 2023, max compression
+gzip compressed data, was "acore_server-0.2.2.tar", last modified: Wed Jun 28 13:19:17 2023, max compression
```

## Comparing `acore_server-0.2.1.tar` & `acore_server-0.2.2.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 20:54:09.335142 acore_server-0.2.1/
--rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-27 04:12:52.000000 acore_server-0.2.1/AUTHORS.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)     1123 2023-06-27 04:12:52.000000 acore_server-0.2.1/LICENSE.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      320 2023-06-27 04:12:52.000000 acore_server-0.2.1/MANIFEST.in
--rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-27 20:54:09.334999 acore_server-0.2.1/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     3694 2023-06-27 05:07:58.000000 acore_server-0.2.1/README.rst
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 20:54:09.332809 acore_server-0.2.1/acore_server/
--rw-r--r--   0 sanhehu    (501) staff       (20)      393 2023-06-27 04:56:34.000000 acore_server-0.2.1/acore_server/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-27 20:46:21.000000 acore_server-0.2.1/acore_server/_version.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      145 2023-06-27 04:49:35.000000 acore_server-0.2.1/acore_server/api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      107 2023-06-27 04:26:27.000000 acore_server-0.2.1/acore_server/constants.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 20:54:09.333755 acore_server-0.2.1/acore_server/docs/
--rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-27 04:12:52.000000 acore_server-0.2.1/acore_server/docs/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)    17282 2023-06-27 20:47:28.000000 acore_server-0.2.1/acore_server/fleet.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      936 2023-06-27 04:26:42.000000 acore_server-0.2.1/acore_server/paths.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 20:54:09.334235 acore_server-0.2.1/acore_server/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-27 04:12:52.000000 acore_server-0.2.1/acore_server/tests/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-27 04:12:52.000000 acore_server-0.2.1/acore_server/tests/helper.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 20:54:09.334551 acore_server-0.2.1/acore_server/vendor/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-27 04:12:52.000000 acore_server-0.2.1/acore_server/vendor/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-27 04:12:52.000000 acore_server-0.2.1/acore_server/vendor/pytest_cov_helper.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3272 2023-06-26 05:55:10.000000 acore_server-0.2.1/acore_server/wserver_infra_exports.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 20:54:09.333635 acore_server-0.2.1/acore_server.egg-info/
--rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-27 20:54:09.000000 acore_server-0.2.1/acore_server.egg-info/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)      722 2023-06-27 20:54:09.000000 acore_server-0.2.1/acore_server.egg-info/SOURCES.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-27 20:54:09.000000 acore_server-0.2.1/acore_server.egg-info/dependency_links.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      421 2023-06-27 20:54:09.000000 acore_server-0.2.1/acore_server.egg-info/requires.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       13 2023-06-27 20:54:09.000000 acore_server-0.2.1/acore_server.egg-info/top_level.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)     1244 2023-06-27 20:47:02.000000 acore_server-0.2.1/release-history.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-27 04:12:52.000000 acore_server-0.2.1/requirements-automation.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-27 04:12:52.000000 acore_server-0.2.1/requirements-dev.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-27 04:12:52.000000 acore_server-0.2.1/requirements-doc.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      183 2023-06-27 04:12:52.000000 acore_server-0.2.1/requirements-test.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      282 2023-06-27 20:24:26.000000 acore_server-0.2.1/requirements.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-27 20:54:09.335189 acore_server-0.2.1/setup.cfg
--rw-r--r--   0 sanhehu    (501) staff       (20)     7561 2023-06-27 04:12:52.000000 acore_server-0.2.1/setup.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 20:54:09.334699 acore_server-0.2.1/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)     1016 2023-06-27 14:01:20.000000 acore_server-0.2.1/tests/test_api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545831 acore_server-0.2.2/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-27 04:12:52.000000 acore_server-0.2.2/AUTHORS.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1123 2023-06-27 04:12:52.000000 acore_server-0.2.2/LICENSE.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      320 2023-06-27 04:12:52.000000 acore_server-0.2.2/MANIFEST.in
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-28 13:19:17.545673 acore_server-0.2.2/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3694 2023-06-27 05:07:58.000000 acore_server-0.2.2/README.rst
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.543789 acore_server-0.2.2/acore_server/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      393 2023-06-27 04:56:34.000000 acore_server-0.2.2/acore_server/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 13:18:23.000000 acore_server-0.2.2/acore_server/_version.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      145 2023-06-27 04:49:35.000000 acore_server-0.2.2/acore_server/api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      107 2023-06-27 04:26:27.000000 acore_server-0.2.2/acore_server/constants.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.544586 acore_server-0.2.2/acore_server/docs/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/docs/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)    17282 2023-06-27 20:47:28.000000 acore_server-0.2.2/acore_server/fleet.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      936 2023-06-27 04:26:42.000000 acore_server-0.2.2/acore_server/paths.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545001 acore_server-0.2.2/acore_server/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/tests/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/tests/helper.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545270 acore_server-0.2.2/acore_server/vendor/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/vendor/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-27 04:12:52.000000 acore_server-0.2.2/acore_server/vendor/pytest_cov_helper.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3272 2023-06-26 05:55:10.000000 acore_server-0.2.2/acore_server/wserver_infra_exports.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.544479 acore_server-0.2.2/acore_server.egg-info/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4817 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)      722 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/SOURCES.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/dependency_links.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      392 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/requires.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       13 2023-06-28 13:19:17.000000 acore_server-0.2.2/acore_server.egg-info/top_level.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1399 2023-06-28 13:18:53.000000 acore_server-0.2.2/release-history.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-automation.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-dev.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-doc.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      183 2023-06-27 04:12:52.000000 acore_server-0.2.2/requirements-test.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      253 2023-06-28 13:17:07.000000 acore_server-0.2.2/requirements.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 13:19:17.545869 acore_server-0.2.2/setup.cfg
+-rw-r--r--   0 sanhehu    (501) staff       (20)     7561 2023-06-27 04:12:52.000000 acore_server-0.2.2/setup.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 13:19:17.545401 acore_server-0.2.2/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1016 2023-06-27 14:01:20.000000 acore_server-0.2.2/tests/test_api.py
```

### Comparing `acore_server-0.2.1/AUTHORS.rst` & `acore_server-0.2.2/AUTHORS.rst`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/LICENSE.txt` & `acore_server-0.2.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/PKG-INFO` & `acore_server-0.2.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore_server
-Version: 0.2.1
+Version: 0.2.2
 Summary: AzerothCore World of Warcraft Logic Server Data Model.
 Home-page: https://github.com/MacHu-GWU/acore_server-project
-Download-URL: https://pypi.python.org/pypi/acore_server/0.2.1#downloads
+Download-URL: https://pypi.python.org/pypi/acore_server/0.2.2#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_server-0.2.1/README.rst` & `acore_server-0.2.2/README.rst`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/acore_server/fleet.py` & `acore_server-0.2.2/acore_server/fleet.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/acore_server/paths.py` & `acore_server-0.2.2/acore_server/paths.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/acore_server/vendor/pytest_cov_helper.py` & `acore_server-0.2.2/acore_server/vendor/pytest_cov_helper.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/acore_server/wserver_infra_exports.py` & `acore_server-0.2.2/acore_server/wserver_infra_exports.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/acore_server.egg-info/PKG-INFO` & `acore_server-0.2.2/acore_server.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore-server
-Version: 0.2.1
+Version: 0.2.2
 Summary: AzerothCore World of Warcraft Logic Server Data Model.
 Home-page: https://github.com/MacHu-GWU/acore_server-project
-Download-URL: https://pypi.python.org/pypi/acore_server/0.2.1#downloads
+Download-URL: https://pypi.python.org/pypi/acore_server/0.2.2#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_server-0.2.1/acore_server.egg-info/SOURCES.txt` & `acore_server-0.2.2/acore_server.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/release-history.rst` & `acore_server-0.2.2/release-history.rst`

 * *Files 20% similar despite different names*

```diff
@@ -11,19 +11,26 @@
 **Minor Improvements**
 
 **Bugfixes**
 
 **Miscellaneous**
 
 
+0.2.2 (2023-06-28)
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+**Miscellaneous**
+
+- Remove unnecessary dependencies.
+
+
 0.2.1 (2023-06-27)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Features and Improvements**
 
-- Add ``acore_server.api.Server.from_ec2_insid``
+- Add ``acore_server.api.Server.from_ec2_inside``
 
 
 0.1.2 (2023-06-27)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Minor Improvements**
 
 - Add ``acore_soap_app_version``, ``acore_server_bootstrap_version`` arguments to ``acore_server.api.Server.bootstrap`` method.
```

### Comparing `acore_server-0.2.1/requirements-doc.txt` & `acore_server-0.2.2/requirements-doc.txt`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/setup.py` & `acore_server-0.2.2/setup.py`

 * *Files identical despite different names*

### Comparing `acore_server-0.2.1/tests/test_api.py` & `acore_server-0.2.2/tests/test_api.py`

 * *Files identical despite different names*

