# Comparing `tmp/acore_soap_app-0.3.2.tar.gz` & `tmp/acore_soap_app-0.3.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "acore_soap_app-0.3.2.tar", last modified: Tue Jun 27 13:53:57 2023, max compression
+gzip compressed data, was "acore_soap_app-0.3.3.tar", last modified: Wed Jun 28 14:57:04 2023, max compression
```

## Comparing `acore_soap_app-0.3.2.tar` & `acore_soap_app-0.3.3.tar`

### file list

```diff
@@ -1,56 +1,56 @@
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.585047 acore_soap_app-0.3.2/
--rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/AUTHORS.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)     1125 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/LICENSE.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      322 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/MANIFEST.in
--rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-27 13:53:57.584884 acore_soap_app-0.3.2/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     4429 2023-06-26 04:04:32.000000 acore_soap_app-0.3.2/README.rst
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.578909 acore_soap_app-0.3.2/acore_soap_app/
--rw-r--r--   0 sanhehu    (501) staff       (20)      413 2023-06-21 15:44:20.000000 acore_soap_app-0.3.2/acore_soap_app/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-27 13:53:17.000000 acore_soap_app-0.3.2/acore_soap_app/_version.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.580751 acore_soap_app-0.3.2/acore_soap_app/agent/
--rw-r--r--   0 sanhehu    (501) staff       (20)      795 2023-06-21 01:55:28.000000 acore_soap_app-0.3.2/acore_soap_app/agent/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      731 2023-06-21 15:11:48.000000 acore_soap_app-0.3.2/acore_soap_app/agent/api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      425 2023-05-10 15:07:05.000000 acore_soap_app-0.3.2/acore_soap_app/agent/execute-command.xml
--rw-r--r--   0 sanhehu    (501) staff       (20)    12691 2023-06-21 15:30:39.000000 acore_soap_app-0.3.2/acore_soap_app/agent/impl.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      314 2023-06-21 15:29:07.000000 acore_soap_app-0.3.2/acore_soap_app/api.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.581544 acore_soap_app-0.3.2/acore_soap_app/cli/
--rw-r--r--   0 sanhehu    (501) staff       (20)       67 2023-06-21 15:12:04.000000 acore_soap_app-0.3.2/acore_soap_app/cli/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     5155 2023-06-26 05:56:16.000000 acore_soap_app-0.3.2/acore_soap_app/cli/impl.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2461 2023-06-26 05:51:01.000000 acore_soap_app-0.3.2/acore_soap_app/cli/main.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.581885 acore_soap_app-0.3.2/acore_soap_app/docs/
--rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/acore_soap_app/docs/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      982 2023-06-21 01:09:10.000000 acore_soap_app-0.3.2/acore_soap_app/exc.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      660 2023-06-20 12:56:41.000000 acore_soap_app-0.3.2/acore_soap_app/paths.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.582785 acore_soap_app-0.3.2/acore_soap_app/sdk/
--rw-r--r--   0 sanhehu    (501) staff       (20)      175 2023-06-21 01:56:33.000000 acore_soap_app-0.3.2/acore_soap_app/sdk/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      271 2023-06-26 03:14:10.000000 acore_soap_app-0.3.2/acore_soap_app/sdk/api.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.583559 acore_soap_app-0.3.2/acore_soap_app/sdk/canned/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-26 03:12:13.000000 acore_soap_app-0.3.2/acore_soap_app/sdk/canned/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      292 2023-06-26 03:14:58.000000 acore_soap_app-0.3.2/acore_soap_app/sdk/canned/api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     4886 2023-06-26 03:14:28.000000 acore_soap_app-0.3.2/acore_soap_app/sdk/canned/impl.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     6272 2023-06-21 15:33:19.000000 acore_soap_app-0.3.2/acore_soap_app/sdk/core.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.584124 acore_soap_app-0.3.2/acore_soap_app/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/acore_soap_app/tests/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/acore_soap_app/tests/helper.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2169 2023-06-21 13:24:48.000000 acore_soap_app-0.3.2/acore_soap_app/tests/mock_aws.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      646 2023-06-21 12:16:28.000000 acore_soap_app-0.3.2/acore_soap_app/utils.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.584518 acore_soap_app-0.3.2/acore_soap_app/vendor/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/acore_soap_app/vendor/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/acore_soap_app/vendor/pytest_cov_helper.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.579878 acore_soap_app-0.3.2/acore_soap_app.egg-info/
--rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-27 13:53:57.000000 acore_soap_app-0.3.2/acore_soap_app.egg-info/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     1189 2023-06-27 13:53:57.000000 acore_soap_app-0.3.2/acore_soap_app.egg-info/SOURCES.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-27 13:53:57.000000 acore_soap_app-0.3.2/acore_soap_app.egg-info/dependency_links.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       55 2023-06-27 13:53:57.000000 acore_soap_app-0.3.2/acore_soap_app.egg-info/entry_points.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      383 2023-06-27 13:53:57.000000 acore_soap_app-0.3.2/acore_soap_app.egg-info/requires.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       15 2023-06-27 13:53:57.000000 acore_soap_app-0.3.2/acore_soap_app.egg-info/top_level.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)     1113 2023-06-27 13:53:36.000000 acore_soap_app-0.3.2/release-history.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/requirements-automation.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/requirements-dev.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/requirements-doc.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      193 2023-06-21 13:24:55.000000 acore_soap_app-0.3.2/requirements-test.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      264 2023-06-27 13:52:01.000000 acore_soap_app-0.3.2/requirements.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-27 13:53:57.585090 acore_soap_app-0.3.2/setup.cfg
--rw-r--r--   0 sanhehu    (501) staff       (20)     7699 2023-06-20 13:22:31.000000 acore_soap_app-0.3.2/setup.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 13:53:57.584660 acore_soap_app-0.3.2/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)      226 2023-06-20 05:17:17.000000 acore_soap_app-0.3.2/tests/test_api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.181917 acore_soap_app-0.3.3/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/AUTHORS.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1125 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/LICENSE.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      322 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/MANIFEST.in
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-28 14:57:04.181773 acore_soap_app-0.3.3/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4429 2023-06-26 04:04:32.000000 acore_soap_app-0.3.3/README.rst
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.176643 acore_soap_app-0.3.3/acore_soap_app/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      413 2023-06-21 15:44:20.000000 acore_soap_app-0.3.3/acore_soap_app/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 14:55:22.000000 acore_soap_app-0.3.3/acore_soap_app/_version.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.178335 acore_soap_app-0.3.3/acore_soap_app/agent/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      795 2023-06-21 01:55:28.000000 acore_soap_app-0.3.3/acore_soap_app/agent/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      642 2023-06-28 14:54:24.000000 acore_soap_app-0.3.3/acore_soap_app/agent/api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      425 2023-05-10 15:07:05.000000 acore_soap_app-0.3.3/acore_soap_app/agent/execute-command.xml
+-rw-r--r--   0 sanhehu    (501) staff       (20)    10936 2023-06-28 14:54:14.000000 acore_soap_app-0.3.3/acore_soap_app/agent/impl.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      314 2023-06-21 15:29:07.000000 acore_soap_app-0.3.3/acore_soap_app/api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.179061 acore_soap_app-0.3.3/acore_soap_app/cli/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       67 2023-06-21 15:12:04.000000 acore_soap_app-0.3.3/acore_soap_app/cli/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5229 2023-06-28 14:55:03.000000 acore_soap_app-0.3.3/acore_soap_app/cli/impl.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2461 2023-06-26 05:51:01.000000 acore_soap_app-0.3.3/acore_soap_app/cli/main.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.179296 acore_soap_app-0.3.3/acore_soap_app/docs/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/docs/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      982 2023-06-21 01:09:10.000000 acore_soap_app-0.3.3/acore_soap_app/exc.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      660 2023-06-20 12:56:41.000000 acore_soap_app-0.3.3/acore_soap_app/paths.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.179827 acore_soap_app-0.3.3/acore_soap_app/sdk/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      175 2023-06-21 01:56:33.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      271 2023-06-26 03:14:10.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.180491 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-26 03:12:13.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      292 2023-06-26 03:14:58.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4886 2023-06-26 03:14:28.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/impl.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     6272 2023-06-28 13:23:00.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/core.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.180994 acore_soap_app-0.3.3/acore_soap_app/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/tests/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/tests/helper.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2169 2023-06-21 13:24:48.000000 acore_soap_app-0.3.3/acore_soap_app/tests/mock_aws.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      646 2023-06-21 12:16:28.000000 acore_soap_app-0.3.3/acore_soap_app/utils.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.181440 acore_soap_app-0.3.3/acore_soap_app/vendor/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/vendor/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/vendor/pytest_cov_helper.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.177484 acore_soap_app-0.3.3/acore_soap_app.egg-info/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1189 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/SOURCES.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/dependency_links.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       55 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/entry_points.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      349 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/requires.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       15 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/top_level.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1289 2023-06-28 14:55:40.000000 acore_soap_app-0.3.3/release-history.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/requirements-automation.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/requirements-dev.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/requirements-doc.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      193 2023-06-21 13:24:55.000000 acore_soap_app-0.3.3/requirements-test.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      230 2023-06-28 14:53:43.000000 acore_soap_app-0.3.3/requirements.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 14:57:04.181967 acore_soap_app-0.3.3/setup.cfg
+-rw-r--r--   0 sanhehu    (501) staff       (20)     7699 2023-06-20 13:22:31.000000 acore_soap_app-0.3.3/setup.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.181576 acore_soap_app-0.3.3/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      226 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/tests/test_api.py
```

### Comparing `acore_soap_app-0.3.2/AUTHORS.rst` & `acore_soap_app-0.3.3/AUTHORS.rst`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/LICENSE.txt` & `acore_soap_app-0.3.3/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/PKG-INFO` & `acore_soap_app-0.3.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore_soap_app
-Version: 0.3.2
+Version: 0.3.3
 Summary: Azerothcore World of Warcraft Soap Remote Access Python Library.
 Home-page: https://github.com/MacHu-GWU/acore_soap_app-project
-Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.2#downloads
+Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.3#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_soap_app-0.3.2/README.rst` & `acore_soap_app-0.3.3/README.rst`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/agent/__init__.py` & `acore_soap_app-0.3.3/acore_soap_app/agent/__init__.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/agent/api.py` & `acore_soap_app-0.3.3/acore_soap_app/agent/api.py`

 * *Files 3% similar despite different names*

```diff
@@ -9,17 +9,15 @@
 
     >>> from acore_soap_app.agent.api import DEFAULT_USERNAME
     >>> from acore_soap_app.agent.api import DEFAULT_PASSWORD
     >>> from acore_soap_app.agent.api import DEFAULT_HOST
     >>> from acore_soap_app.agent.api import DEFAULT_PORT
     >>> from acore_soap_app.agent.api import SOAPRequest
     >>> from acore_soap_app.agent.api import SOAPResponse
-    >>> from acore_soap_app.agent.api import get_boto_ses
 """
 
 from .impl import DEFAULT_USERNAME
 from .impl import DEFAULT_PASSWORD
 from .impl import DEFAULT_HOST
 from .impl import DEFAULT_PORT
 from .impl import SOAPRequest
 from .impl import SOAPResponse
-from .impl import get_boto_ses
```

### Comparing `acore_soap_app-0.3.2/acore_soap_app/agent/impl.py` & `acore_soap_app-0.3.3/acore_soap_app/agent/impl.py`

 * *Files 18% similar despite different names*

```diff
@@ -3,19 +3,16 @@
 """
 Agent implementation.
 """
 
 import typing as T
 import json
 import dataclasses
-from pathlib import Path
-from datetime import datetime
 import xml.etree.ElementTree as ET
 
-import boto3
 import requests
 
 from ..paths import dir_python_lib
 from ..exc import SOAPResponseParseError
 from ..utils import get_object, put_object
 
 
@@ -301,58 +298,7 @@
         raise SOAPResponseParseError(f"Cannot parse the response: {body!r}")
 
     def print(self):  # pragma: no cover
         """
         Print the dataclass, ignore the raw response body.
         """
         print({"succeeded": self.succeeded, "message": self.message})
-
-
-# ------------------------------------------------------------------------------
-# Create boto3 session on EC2
-# ------------------------------------------------------------------------------
-path_aws_region_cache = Path.home().joinpath(".aws_region_cache.json")
-
-
-def _dump_aws_region_cache(region: str):  # pragma: no cover
-    path_aws_region_cache.write_text(
-        json.dumps({"region": region, "timestamp": int(datetime.utcnow().timestamp())})
-    )
-
-
-def _load_aws_region_cache() -> T.Optional[str]:  # pragma: no cover
-    if not path_aws_region_cache.exists():
-        return None
-    data = json.loads(path_aws_region_cache.read_text())
-    if (datetime.utcnow().timestamp() - data["timestamp"]) > 86400:  # cache expired
-        return None
-    else:
-        return data["region"]
-
-
-def get_ec2_metadata(name: str) -> str:  # pragma: no cover
-    """
-    Get the EC2 instance id from the AWS EC2 metadata API.
-
-    Reference:
-
-    - https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instancedata-data-retrieval.html
-    """
-    url = f"http://169.254.169.254/latest/meta-data/{name}"
-    return requests.get(url).text.strip()
-
-
-def get_ec2_region() -> str:  # pragma: no cover
-    region = _load_aws_region_cache()
-    if region is None:
-        region = get_ec2_metadata("placement/region")
-        _dump_aws_region_cache(region)
-    return region
-
-
-def get_boto_ses() -> boto3.session.Session:  # pragma: no cover
-    """
-    On EC2, we use the IAM role to get the AWS credentials. You only need to
-    specify the region name, however, it is automatically discovered by the
-    EC2 metadata API.
-    """
-    return boto3.session.Session(region_name=get_ec2_region())
```

### Comparing `acore_soap_app-0.3.2/acore_soap_app/cli/impl.py` & `acore_soap_app-0.3.3/acore_soap_app/cli/impl.py`

 * *Files 2% similar despite different names*

```diff
@@ -4,17 +4,18 @@
 Command line low lever implementations.
 """
 
 import typing as T
 import json
 from datetime import datetime, timezone
 
+from simple_aws_ec2.api import EC2MetadataCache
 from acore_constants.api import TagKey
 
-from ..agent.api import SOAPRequest, SOAPResponse, get_boto_ses
+from ..agent.api import SOAPRequest, SOAPResponse
 from ..sdk.api import canned
 from ..exc import SOAPCommandFailedError
 
 
 def ensure_ec2_environment():
     if not __file__.startswith("/home/ubuntu"):
         raise EnvironmentError("This is not a EC2 environment")
@@ -60,15 +61,15 @@
     :param s3uri_output: 可选参数, 如果为 None, 则将
         :class:`~acore_soap_app.agent.impl.SOAPResponse` 对象转换为 JSON 并打印.
         如果给定, 则将 JSON 保存到 S3 中. 常用于返回结果特别大的情况.
     """
     ensure_ec2_environment()
 
     # handle input
-    boto_ses = get_boto_ses()
+    boto_ses = EC2MetadataCache.load().get_boto_ses_from_ec2_inside()
     s3_client = boto_ses.client("s3")
     requests = SOAPRequest.batch_load(
         request_like=request_like,
         username=username,
         password=password,
         s3_client=s3_client,
     )
```

### Comparing `acore_soap_app-0.3.2/acore_soap_app/cli/main.py` & `acore_soap_app-0.3.3/acore_soap_app/cli/main.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/exc.py` & `acore_soap_app-0.3.3/acore_soap_app/exc.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/paths.py` & `acore_soap_app-0.3.3/acore_soap_app/paths.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/sdk/canned/impl.py` & `acore_soap_app-0.3.3/acore_soap_app/sdk/canned/impl.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/sdk/core.py` & `acore_soap_app-0.3.3/acore_soap_app/sdk/core.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/tests/mock_aws.py` & `acore_soap_app-0.3.3/acore_soap_app/tests/mock_aws.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/utils.py` & `acore_soap_app-0.3.3/acore_soap_app/utils.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app/vendor/pytest_cov_helper.py` & `acore_soap_app-0.3.3/acore_soap_app/vendor/pytest_cov_helper.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/acore_soap_app.egg-info/PKG-INFO` & `acore_soap_app-0.3.3/acore_soap_app.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore-soap-app
-Version: 0.3.2
+Version: 0.3.3
 Summary: Azerothcore World of Warcraft Soap Remote Access Python Library.
 Home-page: https://github.com/MacHu-GWU/acore_soap_app-project
-Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.2#downloads
+Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.3#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_soap_app-0.3.2/acore_soap_app.egg-info/SOURCES.txt` & `acore_soap_app-0.3.3/acore_soap_app.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/release-history.rst` & `acore_soap_app-0.3.3/release-history.rst`

 * *Files 5% similar despite different names*

```diff
@@ -11,14 +11,22 @@
 **Minor Improvements**
 
 **Bugfixes**
 
 **Miscellaneous**
 
 
+0.3.3 (2023-06-27)
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+**Miscellaneous**
+
+- Upgrade dependencies
+- Improve internal implementation
+
+
 0.3.2 (2023-06-27)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Miscellaneous**
 
 - upgrade dependencies
```

### Comparing `acore_soap_app-0.3.2/requirements-doc.txt` & `acore_soap_app-0.3.3/requirements-doc.txt`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.2/setup.py` & `acore_soap_app-0.3.3/setup.py`

 * *Files identical despite different names*

