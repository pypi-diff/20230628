# Comparing `tmp/acore_server_config-0.4.1.tar.gz` & `tmp/acore_server_config-0.4.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "acore_server_config-0.4.1.tar", last modified: Tue Jun 27 02:55:02 2023, max compression
+gzip compressed data, was "acore_server_config-0.4.2.tar", last modified: Wed Jun 28 14:44:57 2023, max compression
```

## Comparing `acore_server_config-0.4.1.tar` & `acore_server_config-0.4.2.tar`

### file list

```diff
@@ -1,49 +1,49 @@
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.952578 acore_server_config-0.4.1/
--rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/AUTHORS.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)     1130 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/LICENSE.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      327 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/MANIFEST.in
--rw-r--r--   0 sanhehu    (501) staff       (20)     5264 2023-06-27 02:55:02.952447 acore_server_config-0.4.1/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     4102 2023-06-26 05:40:34.000000 acore_server_config-0.4.1/README.rst
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.948190 acore_server_config-0.4.1/acore_server_config/
--rw-r--r--   0 sanhehu    (501) staff       (20)      429 2023-06-18 01:38:46.000000 acore_server_config-0.4.1/acore_server_config/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-27 02:46:47.000000 acore_server_config-0.4.1/acore_server_config/_version.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      492 2023-06-19 16:52:37.000000 acore_server_config-0.4.1/acore_server_config/api.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     1149 2023-06-22 03:51:05.000000 acore_server_config-0.4.1/acore_server_config/boto_ses.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      128 2023-06-16 18:25:58.000000 acore_server_config-0.4.1/acore_server_config/compat.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.949390 acore_server_config-0.4.1/acore_server_config/config/
--rw-r--r--   0 sanhehu    (501) staff       (20)       50 2023-06-19 17:13:43.000000 acore_server_config-0.4.1/acore_server_config/config/__init__.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.950410 acore_server_config-0.4.1/acore_server_config/config/define/
--rw-r--r--   0 sanhehu    (501) staff       (20)       98 2023-06-19 17:13:36.000000 acore_server_config-0.4.1/acore_server_config/config/define/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2672 2023-06-27 02:45:02.000000 acore_server_config-0.4.1/acore_server_config/config/define/main.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3688 2023-06-27 02:45:15.000000 acore_server_config-0.4.1/acore_server_config/config/define/server.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     1634 2023-06-18 00:44:26.000000 acore_server_config-0.4.1/acore_server_config/config/init.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     8011 2023-06-27 02:48:07.000000 acore_server_config-0.4.1/acore_server_config/config/loader.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.950635 acore_server_config-0.4.1/acore_server_config/docs/
--rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/acore_server_config/docs/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     4080 2023-06-26 05:35:57.000000 acore_server_config-0.4.1/acore_server_config/in_ec2.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     1180 2023-06-17 20:38:51.000000 acore_server_config-0.4.1/acore_server_config/paths.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2378 2023-06-26 16:46:45.000000 acore_server_config-0.4.1/acore_server_config/runtime.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.951548 acore_server_config-0.4.1/acore_server_config/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/acore_server_config/tests/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      362 2023-06-19 16:31:24.000000 acore_server_config-0.4.1/acore_server_config/tests/dummy_config.py
--rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/acore_server_config/tests/helper.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     2169 2023-06-19 16:26:34.000000 acore_server_config-0.4.1/acore_server_config/tests/mock_aws.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.952013 acore_server_config-0.4.1/acore_server_config/vendor/
--rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/acore_server_config/vendor/__init__.py
--rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/acore_server_config/vendor/pytest_cov_helper.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.948845 acore_server_config-0.4.1/acore_server_config.egg-info/
--rw-r--r--   0 sanhehu    (501) staff       (20)     5264 2023-06-27 02:55:02.000000 acore_server_config-0.4.1/acore_server_config.egg-info/PKG-INFO
--rw-r--r--   0 sanhehu    (501) staff       (20)     1180 2023-06-27 02:55:02.000000 acore_server_config-0.4.1/acore_server_config.egg-info/SOURCES.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-27 02:55:02.000000 acore_server_config-0.4.1/acore_server_config.egg-info/dependency_links.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      315 2023-06-27 02:55:02.000000 acore_server_config-0.4.1/acore_server_config.egg-info/requires.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       20 2023-06-27 02:55:02.000000 acore_server_config-0.4.1/acore_server_config.egg-info/top_level.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)     4058 2023-06-27 02:46:37.000000 acore_server_config-0.4.1/release-history.rst
--rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/requirements-automation.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-18 01:00:08.000000 acore_server_config-0.4.1/requirements-dev.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/requirements-doc.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      188 2023-06-19 16:26:45.000000 acore_server_config-0.4.1/requirements-test.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)      201 2023-06-27 02:14:57.000000 acore_server_config-0.4.1/requirements.txt
--rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-27 02:55:02.952618 acore_server_config-0.4.1/setup.cfg
--rw-r--r--   0 sanhehu    (501) staff       (20)     7568 2023-06-17 19:58:08.000000 acore_server_config-0.4.1/setup.py
-drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-27 02:55:02.952158 acore_server_config-0.4.1/tests/
--rw-r--r--   0 sanhehu    (501) staff       (20)      501 2023-06-19 16:53:17.000000 acore_server_config-0.4.1/tests/test_api.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.637683 acore_server_config-0.4.2/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      670 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/AUTHORS.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1130 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/LICENSE.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      327 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/MANIFEST.in
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5264 2023-06-28 14:44:57.637498 acore_server_config-0.4.2/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4102 2023-06-26 05:40:34.000000 acore_server_config-0.4.2/README.rst
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.633063 acore_server_config-0.4.2/acore_server_config/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      429 2023-06-18 01:38:46.000000 acore_server_config-0.4.2/acore_server_config/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)       93 2023-06-28 14:35:19.000000 acore_server_config-0.4.2/acore_server_config/_version.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      492 2023-06-19 16:52:37.000000 acore_server_config-0.4.2/acore_server_config/api.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1156 2023-06-28 14:35:12.000000 acore_server_config-0.4.2/acore_server_config/boto_ses.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      128 2023-06-16 18:25:58.000000 acore_server_config-0.4.2/acore_server_config/compat.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.634475 acore_server_config-0.4.2/acore_server_config/config/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       50 2023-06-19 17:13:43.000000 acore_server_config-0.4.2/acore_server_config/config/__init__.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.635198 acore_server_config-0.4.2/acore_server_config/config/define/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       98 2023-06-19 17:13:36.000000 acore_server_config-0.4.2/acore_server_config/config/define/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2672 2023-06-27 02:45:02.000000 acore_server_config-0.4.2/acore_server_config/config/define/main.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3688 2023-06-27 02:45:15.000000 acore_server_config-0.4.2/acore_server_config/config/define/server.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1634 2023-06-18 00:44:26.000000 acore_server_config-0.4.2/acore_server_config/config/init.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     8011 2023-06-27 02:48:07.000000 acore_server_config-0.4.2/acore_server_config/config/loader.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.635487 acore_server_config-0.4.2/acore_server_config/docs/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       43 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/acore_server_config/docs/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4080 2023-06-26 05:35:57.000000 acore_server_config-0.4.2/acore_server_config/in_ec2.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1180 2023-06-17 20:38:51.000000 acore_server_config-0.4.2/acore_server_config/paths.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2378 2023-06-26 16:46:45.000000 acore_server_config-0.4.2/acore_server_config/runtime.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.636524 acore_server_config-0.4.2/acore_server_config/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       58 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/acore_server_config/tests/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      362 2023-06-19 16:31:24.000000 acore_server_config-0.4.2/acore_server_config/tests/dummy_config.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)      447 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/acore_server_config/tests/helper.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     2169 2023-06-19 16:26:34.000000 acore_server_config-0.4.2/acore_server_config/tests/mock_aws.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.636988 acore_server_config-0.4.2/acore_server_config/vendor/
+-rw-r--r--   0 sanhehu    (501) staff       (20)       25 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/acore_server_config/vendor/__init__.py
+-rw-r--r--   0 sanhehu    (501) staff       (20)     3572 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/acore_server_config/vendor/pytest_cov_helper.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.633884 acore_server_config-0.4.2/acore_server_config.egg-info/
+-rw-r--r--   0 sanhehu    (501) staff       (20)     5264 2023-06-28 14:44:57.000000 acore_server_config-0.4.2/acore_server_config.egg-info/PKG-INFO
+-rw-r--r--   0 sanhehu    (501) staff       (20)     1180 2023-06-28 14:44:57.000000 acore_server_config-0.4.2/acore_server_config.egg-info/SOURCES.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)        1 2023-06-28 14:44:57.000000 acore_server_config-0.4.2/acore_server_config.egg-info/dependency_links.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      315 2023-06-28 14:44:57.000000 acore_server_config-0.4.2/acore_server_config.egg-info/requires.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       20 2023-06-28 14:44:57.000000 acore_server_config-0.4.2/acore_server_config.egg-info/top_level.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)     4252 2023-06-28 14:43:47.000000 acore_server_config-0.4.2/release-history.rst
+-rw-r--r--   0 sanhehu    (501) staff       (20)      102 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/requirements-automation.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      353 2023-06-18 01:00:08.000000 acore_server_config-0.4.2/requirements-dev.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      563 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/requirements-doc.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      188 2023-06-19 16:26:45.000000 acore_server_config-0.4.2/requirements-test.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)      201 2023-06-28 14:23:11.000000 acore_server_config-0.4.2/requirements.txt
+-rw-r--r--   0 sanhehu    (501) staff       (20)       38 2023-06-28 14:44:57.637740 acore_server_config-0.4.2/setup.cfg
+-rw-r--r--   0 sanhehu    (501) staff       (20)     7568 2023-06-17 19:58:08.000000 acore_server_config-0.4.2/setup.py
+drwxr-xr-x   0 sanhehu    (501) staff       (20)        0 2023-06-28 14:44:57.637164 acore_server_config-0.4.2/tests/
+-rw-r--r--   0 sanhehu    (501) staff       (20)      501 2023-06-19 16:53:17.000000 acore_server_config-0.4.2/tests/test_api.py
```

### Comparing `acore_server_config-0.4.1/AUTHORS.rst` & `acore_server_config-0.4.2/AUTHORS.rst`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/LICENSE.txt` & `acore_server_config-0.4.2/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/PKG-INFO` & `acore_server_config-0.4.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore_server_config
-Version: 0.4.1
+Version: 0.4.2
 Summary: Azerothcore World of Warcraft fleet of Servers configuration management.
 Home-page: https://github.com/MacHu-GWU/acore_server_config-project
-Download-URL: https://pypi.python.org/pypi/acore_server_config/0.4.1#downloads
+Download-URL: https://pypi.python.org/pypi/acore_server_config/0.4.2#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_server_config-0.4.1/README.rst` & `acore_server_config-0.4.2/README.rst`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/boto_ses.py` & `acore_server_config-0.4.2/acore_server_config/boto_ses.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 # -*- coding: utf-8 -*-
 
 import os
 from s3pathlib import context
 from boto_session_manager import BotoSesManager
-from simple_aws_ec2.api import Ec2Instance
+from simple_aws_ec2.api import EC2MetadataCache
 
 
 from .runtime import (
     IS_LOCAL,
     IS_GITHUB_CI,
     IS_EC2,
     IS_CODEBUILD_CI,
@@ -24,15 +24,15 @@
     )
 elif IS_GITHUB_CI:
     bsm = BotoSesManager(
         region_name="us-east-1",  # hard coded region, because we know what we are doing
     )
 elif IS_EC2:
     bsm = BotoSesManager(
-        region_name=Ec2Instance.get_placement_region(),
+        region_name=EC2MetadataCache.load().get_region(),
     )
 elif IS_CODEBUILD_CI:
     bsm = BotoSesManager(
         region_name=os.environ["AWS_REGION"],
     )
 elif IS_LAMBDA:
     bsm = BotoSesManager(
```

### Comparing `acore_server_config-0.4.1/acore_server_config/config/define/main.py` & `acore_server_config-0.4.2/acore_server_config/config/define/main.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/config/define/server.py` & `acore_server_config-0.4.2/acore_server_config/config/define/server.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/config/init.py` & `acore_server_config-0.4.2/acore_server_config/config/init.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/config/loader.py` & `acore_server_config-0.4.2/acore_server_config/config/loader.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/in_ec2.py` & `acore_server_config-0.4.2/acore_server_config/in_ec2.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/paths.py` & `acore_server_config-0.4.2/acore_server_config/paths.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/runtime.py` & `acore_server_config-0.4.2/acore_server_config/runtime.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/tests/mock_aws.py` & `acore_server_config-0.4.2/acore_server_config/tests/mock_aws.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config/vendor/pytest_cov_helper.py` & `acore_server_config-0.4.2/acore_server_config/vendor/pytest_cov_helper.py`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/acore_server_config.egg-info/PKG-INFO` & `acore_server_config-0.4.2/acore_server_config.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: acore-server-config
-Version: 0.4.1
+Version: 0.4.2
 Summary: Azerothcore World of Warcraft fleet of Servers configuration management.
 Home-page: https://github.com/MacHu-GWU/acore_server_config-project
-Download-URL: https://pypi.python.org/pypi/acore_server_config/0.4.1#downloads
+Download-URL: https://pypi.python.org/pypi/acore_server_config/0.4.2#downloads
 Author: Sanhe Hu
 Author-email: husanhe@gmail.com
 Maintainer: Sanhe Hu
 Maintainer-email: husanhe@gmail.com
 License: MIT
 Platform: Windows
 Platform: MacOS
```

### Comparing `acore_server_config-0.4.1/acore_server_config.egg-info/SOURCES.txt` & `acore_server_config-0.4.2/acore_server_config.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/release-history.rst` & `acore_server_config-0.4.2/release-history.rst`

 * *Files 2% similar despite different names*

```diff
@@ -11,14 +11,22 @@
 **Minor Improvements**
 
 **Bugfixes**
 
 **Miscellaneous**
 
 
+0.4.2 (2023-07-28)
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+**Miscellaneous**
+
+- upgrade dependencies, no API changes.
+- improve internal implementation.
+
+
 0.4.1 (2023-06-26)
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 **Features and Improvements**
 
 - merge the following config field from ``wserver_fleet_manager`` project:
     - ``acore_config.config.define.server.Server.ec2_ami_id``
     - ``acore_config.config.define.server.Server.ec2_instance_type``
```

### Comparing `acore_server_config-0.4.1/requirements-doc.txt` & `acore_server_config-0.4.2/requirements-doc.txt`

 * *Files identical despite different names*

### Comparing `acore_server_config-0.4.1/setup.py` & `acore_server_config-0.4.2/setup.py`

 * *Files identical despite different names*

