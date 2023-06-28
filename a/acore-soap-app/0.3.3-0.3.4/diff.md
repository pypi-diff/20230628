# Comparing `tmp/acore_soap_app-0.3.3.tar.gz` & `tmp/acore_soap_app-0.3.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "acore_soap_app-0.3.3.tar", last modified: Wed Jun 28 14:57:04 2023, max compression
+gzip compressed data, was "acore_soap_app-0.3.4.tar", last modified: Wed Jun 28 15:33:03 2023, max compression
```

## Comparing `acore_soap_app-0.3.3.tar` & `acore_soap_app-0.3.4.tar`

### file list

```diff
@@ -1,56 +1,56 @@
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.181917 acore_soap_app-0.3.3/
--rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/AUTHORS.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)     1125 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/LICENSE.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      322 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/MANIFEST.in
--rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-28 14:57:04.181773 acore_soap_app-0.3.3/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     4429 2023-06-26 04:04:32.000000 acore_soap_app-0.3.3/README.rst
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.176643 acore_soap_app-0.3.3/acore_soap_app/
--rw-r--r--   0 sanhehu    (501) staff       (20)      413 2023-06-21 15:44:20.000000 acore_soap_app-0.3.3/acore_soap_app/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 14:55:22.000000 acore_soap_app-0.3.3/acore_soap_app/_version.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.178335 acore_soap_app-0.3.3/acore_soap_app/agent/
--rw-r--r--   0 sanhehu    (501) staff       (20)      795 2023-06-21 01:55:28.000000 acore_soap_app-0.3.3/acore_soap_app/agent/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      642 2023-06-28 14:54:24.000000 acore_soap_app-0.3.3/acore_soap_app/agent/api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      425 2023-05-10 15:07:05.000000 acore_soap_app-0.3.3/acore_soap_app/agent/execute-command.xml
--rw-r--r--   0 sanhehu    (501) staff       (20)    10936 2023-06-28 14:54:14.000000 acore_soap_app-0.3.3/acore_soap_app/agent/impl.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      314 2023-06-21 15:29:07.000000 acore_soap_app-0.3.3/acore_soap_app/api.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.179061 acore_soap_app-0.3.3/acore_soap_app/cli/
--rw-r--r--   0 sanhehu    (501) staff       (20)       67 2023-06-21 15:12:04.000000 acore_soap_app-0.3.3/acore_soap_app/cli/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     5229 2023-06-28 14:55:03.000000 acore_soap_app-0.3.3/acore_soap_app/cli/impl.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2461 2023-06-26 05:51:01.000000 acore_soap_app-0.3.3/acore_soap_app/cli/main.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.179296 acore_soap_app-0.3.3/acore_soap_app/docs/
--rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/docs/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      982 2023-06-21 01:09:10.000000 acore_soap_app-0.3.3/acore_soap_app/exc.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      660 2023-06-20 12:56:41.000000 acore_soap_app-0.3.3/acore_soap_app/paths.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.179827 acore_soap_app-0.3.3/acore_soap_app/sdk/
--rw-r--r--   0 sanhehu    (501) staff       (20)      175 2023-06-21 01:56:33.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      271 2023-06-26 03:14:10.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/api.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.180491 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-26 03:12:13.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      292 2023-06-26 03:14:58.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     4886 2023-06-26 03:14:28.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/canned/impl.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     6272 2023-06-28 13:23:00.000000 acore_soap_app-0.3.3/acore_soap_app/sdk/core.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.180994 acore_soap_app-0.3.3/acore_soap_app/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/tests/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/tests/helper.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2169 2023-06-21 13:24:48.000000 acore_soap_app-0.3.3/acore_soap_app/tests/mock_aws.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      646 2023-06-21 12:16:28.000000 acore_soap_app-0.3.3/acore_soap_app/utils.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.181440 acore_soap_app-0.3.3/acore_soap_app/vendor/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/vendor/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/acore_soap_app/vendor/pytest_cov_helper.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.177484 acore_soap_app-0.3.3/acore_soap_app.egg-info/
--rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     1189 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/SOURCES.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/dependency_links.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       55 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/entry_points.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      349 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/requires.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       15 2023-06-28 14:57:04.000000 acore_soap_app-0.3.3/acore_soap_app.egg-info/top_level.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)     1289 2023-06-28 14:55:40.000000 acore_soap_app-0.3.3/release-history.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/requirements-automation.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/requirements-dev.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/requirements-doc.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      193 2023-06-21 13:24:55.000000 acore_soap_app-0.3.3/requirements-test.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      230 2023-06-28 14:53:43.000000 acore_soap_app-0.3.3/requirements.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 14:57:04.181967 acore_soap_app-0.3.3/setup.cfg
--rw-r--r--   0 sanhehu    (501) staff       (20)     7699 2023-06-20 13:22:31.000000 acore_soap_app-0.3.3/setup.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:57:04.181576 acore_soap_app-0.3.3/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)      226 2023-06-20 05:17:17.000000 acore_soap_app-0.3.3/tests/test_api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.734767 acore_soap_app-0.3.4/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/AUTHORS.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1125 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/LICENSE.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      322 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/MANIFEST.in
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-28 15:33:03.734571 acore_soap_app-0.3.4/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4429 2023-06-26 04:04:32.000000 acore_soap_app-0.3.4/README.rst
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.727516 acore_soap_app-0.3.4/acore_soap_app/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      413 2023-06-21 15:44:20.000000 acore_soap_app-0.3.4/acore_soap_app/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 15:25:26.000000 acore_soap_app-0.3.4/acore_soap_app/_version.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.729937 acore_soap_app-0.3.4/acore_soap_app/agent/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      795 2023-06-21 01:55:28.000000 acore_soap_app-0.3.4/acore_soap_app/agent/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      642 2023-06-28 14:54:24.000000 acore_soap_app-0.3.4/acore_soap_app/agent/api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      425 2023-05-10 15:07:05.000000 acore_soap_app-0.3.4/acore_soap_app/agent/execute-command.xml
+-rw-r--r--   0 sanhehu    (501) staff       (20)    10936 2023-06-28 14:54:14.000000 acore_soap_app-0.3.4/acore_soap_app/agent/impl.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      314 2023-06-21 15:29:07.000000 acore_soap_app-0.3.4/acore_soap_app/api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.731030 acore_soap_app-0.3.4/acore_soap_app/cli/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       67 2023-06-21 15:12:04.000000 acore_soap_app-0.3.4/acore_soap_app/cli/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5229 2023-06-28 14:55:03.000000 acore_soap_app-0.3.4/acore_soap_app/cli/impl.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2582 2023-06-28 15:21:53.000000 acore_soap_app-0.3.4/acore_soap_app/cli/main.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.731315 acore_soap_app-0.3.4/acore_soap_app/docs/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/acore_soap_app/docs/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      982 2023-06-21 01:09:10.000000 acore_soap_app-0.3.4/acore_soap_app/exc.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      660 2023-06-20 12:56:41.000000 acore_soap_app-0.3.4/acore_soap_app/paths.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.732161 acore_soap_app-0.3.4/acore_soap_app/sdk/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      175 2023-06-21 01:56:33.000000 acore_soap_app-0.3.4/acore_soap_app/sdk/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      271 2023-06-26 03:14:10.000000 acore_soap_app-0.3.4/acore_soap_app/sdk/api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.733044 acore_soap_app-0.3.4/acore_soap_app/sdk/canned/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-26 03:12:13.000000 acore_soap_app-0.3.4/acore_soap_app/sdk/canned/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      292 2023-06-26 03:14:58.000000 acore_soap_app-0.3.4/acore_soap_app/sdk/canned/api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4886 2023-06-26 03:14:28.000000 acore_soap_app-0.3.4/acore_soap_app/sdk/canned/impl.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     6272 2023-06-28 13:23:00.000000 acore_soap_app-0.3.4/acore_soap_app/sdk/core.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.733654 acore_soap_app-0.3.4/acore_soap_app/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/acore_soap_app/tests/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/acore_soap_app/tests/helper.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2169 2023-06-21 13:24:48.000000 acore_soap_app-0.3.4/acore_soap_app/tests/mock_aws.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      646 2023-06-21 12:16:28.000000 acore_soap_app-0.3.4/acore_soap_app/utils.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.734164 acore_soap_app-0.3.4/acore_soap_app/vendor/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/acore_soap_app/vendor/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/acore_soap_app/vendor/pytest_cov_helper.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.728808 acore_soap_app-0.3.4/acore_soap_app.egg-info/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5568 2023-06-28 15:33:03.000000 acore_soap_app-0.3.4/acore_soap_app.egg-info/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1189 2023-06-28 15:33:03.000000 acore_soap_app-0.3.4/acore_soap_app.egg-info/SOURCES.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 15:33:03.000000 acore_soap_app-0.3.4/acore_soap_app.egg-info/dependency_links.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       55 2023-06-28 15:33:03.000000 acore_soap_app-0.3.4/acore_soap_app.egg-info/entry_points.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      349 2023-06-28 15:33:03.000000 acore_soap_app-0.3.4/acore_soap_app.egg-info/requires.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       15 2023-06-28 15:33:03.000000 acore_soap_app-0.3.4/acore_soap_app.egg-info/top_level.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1446 2023-06-28 15:26:07.000000 acore_soap_app-0.3.4/release-history.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/requirements-automation.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/requirements-dev.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/requirements-doc.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      193 2023-06-21 13:24:55.000000 acore_soap_app-0.3.4/requirements-test.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      230 2023-06-28 14:53:43.000000 acore_soap_app-0.3.4/requirements.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 15:33:03.734829 acore_soap_app-0.3.4/setup.cfg
+-rw-r--r--   0 sanhehu    (501) staff       (20)     7699 2023-06-20 13:22:31.000000 acore_soap_app-0.3.4/setup.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 15:33:03.734323 acore_soap_app-0.3.4/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      226 2023-06-20 05:17:17.000000 acore_soap_app-0.3.4/tests/test_api.py
```

### Comparing `acore_soap_app-0.3.3/AUTHORS.rst` & `acore_soap_app-0.3.4/AUTHORS.rst`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/LICENSE.txt` & `acore_soap_app-0.3.4/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/PKG-INFO` & `acore_soap_app-0.3.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore_soap_app
-Version: 0.3.3
+Version: 0.3.4
 Summary: Azerothcore World of Warcraft Soap Remote Access Python Library.
 Home-page: https://github.com/MacHu-GWU/acore_soap_app-project
-Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.3#downloads
+Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.4#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_soap_app-0.3.3/README.rst` & `acore_soap_app-0.3.4/README.rst`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/agent/__init__.py` & `acore_soap_app-0.3.4/acore_soap_app/agent/__init__.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/agent/api.py` & `acore_soap_app-0.3.4/acore_soap_app/agent/api.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/agent/impl.py` & `acore_soap_app-0.3.4/acore_soap_app/agent/impl.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/cli/impl.py` & `acore_soap_app-0.3.4/acore_soap_app/cli/impl.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/cli/main.py` & `acore_soap_app-0.3.4/acore_soap_app/cli/main.py`

 * *Files 3% similar despite different names*

```diff
@@ -68,14 +68,20 @@
 
     - acsoap
     """
 
     def __init__(self):
         self.canned = Canned()
 
+    def hello(self):
+        """
+        Print welcome message.
+        """
+        print("Hello acore soap app user!")
+
     def gm(
         self,
         cmd: str,
         user: T.Optional[str] = None,
         pwd: T.Optional[str] = None,
         raises: bool = True,
         s3uri: T.Optional[str] = None,
```

### Comparing `acore_soap_app-0.3.3/acore_soap_app/exc.py` & `acore_soap_app-0.3.4/acore_soap_app/exc.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/paths.py` & `acore_soap_app-0.3.4/acore_soap_app/paths.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/sdk/canned/impl.py` & `acore_soap_app-0.3.4/acore_soap_app/sdk/canned/impl.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/sdk/core.py` & `acore_soap_app-0.3.4/acore_soap_app/sdk/core.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/tests/mock_aws.py` & `acore_soap_app-0.3.4/acore_soap_app/tests/mock_aws.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/utils.py` & `acore_soap_app-0.3.4/acore_soap_app/utils.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app/vendor/pytest_cov_helper.py` & `acore_soap_app-0.3.4/acore_soap_app/vendor/pytest_cov_helper.py`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/acore_soap_app.egg-info/PKG-INFO` & `acore_soap_app-0.3.4/acore_soap_app.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore-soap-app
-Version: 0.3.3
+Version: 0.3.4
 Summary: Azerothcore World of Warcraft Soap Remote Access Python Library.
 Home-page: https://github.com/MacHu-GWU/acore_soap_app-project
-Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.3#downloads
+Download-URL: https://pypi.python.org/pypi/acore_soap_app/0.3.4#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_soap_app-0.3.3/acore_soap_app.egg-info/SOURCES.txt` & `acore_soap_app-0.3.4/acore_soap_app.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/release-history.rst` & `acore_soap_app-0.3.4/release-history.rst`

 * *Files 10% similar despite different names*

```diff
@@ -11,48 +11,55 @@
 **Minor Improvements**
 
 **Bugfixes**
 
 **Miscellaneous**
 
 
-0.3.3 (2023-06-27)
+0.3.4 (2023-06-28)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Miscellaneous**
 
-- Upgrade dependencies
-- Improve internal implementation
+- Add ``acsoap hello`` command.
+
+
+0.3.3 (2023-06-28)
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+**Miscellaneous**
+
+- Upgrade dependencies.
+- Improve internal implementation.
 
 
 0.3.2 (2023-06-27)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Miscellaneous**
 
-- upgrade dependencies
+- upgrade dependencies.
 
 
 0.3.1 (2023-06-26)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Features and Improvements**
 
-- add ``acsoap canned measure-server-status`` command
+- add ``acsoap canned measure-server-status`` command.
 
 
 0.2.1 (2023-06-26)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Features and Improvements**
 
-- add ``acsoap canned count-online-players`` command
+- add ``acsoap canned count-online-players`` command.
 
 **Miscellaneous**
 
 - improve documentation.
 
 
 0.1.1 (2023-06-20)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Features and Improvements**
 
-- First release
+- First release.
 - Add SOAP agent CLI module.
 - Add SDK module.
 - Add lots of canned GM command Python functions.
```

### Comparing `acore_soap_app-0.3.3/requirements-doc.txt` & `acore_soap_app-0.3.4/requirements-doc.txt`

 * *Files identical despite different names*

### Comparing `acore_soap_app-0.3.3/setup.py` & `acore_soap_app-0.3.4/setup.py`

 * *Files identical despite different names*

