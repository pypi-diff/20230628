# Comparing `tmp/molgenis_emx2_pyclient-8.198.3.tar.gz` & `tmp/molgenis_emx2_pyclient-8.198.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "molgenis_emx2_pyclient-8.198.3.tar", last modified: Tue Jun 27 10:05:56 2023, max compression
+gzip compressed data, was "molgenis_emx2_pyclient-8.198.4.tar", last modified: Wed Jun 28 09:47:54 2023, max compression
```

## Comparing `molgenis_emx2_pyclient-8.198.3.tar` & `molgenis_emx2_pyclient-8.198.4.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 10:05:56.871680 molgenis_emx2_pyclient-8.198.3/
--rw-r--r--   0 root         (0) root         (0)     7631 2023-06-27 09:58:36.000000 molgenis_emx2_pyclient-8.198.3/LICENSE
--rw-r--r--   0 root         (0) root         (0)     1337 2023-06-27 10:05:56.871680 molgenis_emx2_pyclient-8.198.3/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      953 2023-06-27 09:58:37.000000 molgenis_emx2_pyclient-8.198.3/README.md
--rw-r--r--   0 root         (0) root         (0)      634 2023-06-27 09:58:37.000000 molgenis_emx2_pyclient-8.198.3/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)       16 2023-06-27 09:58:37.000000 molgenis_emx2_pyclient-8.198.3/requirements.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-27 10:05:56.871680 molgenis_emx2_pyclient-8.198.3/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 10:05:56.871680 molgenis_emx2_pyclient-8.198.3/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 10:05:56.871680 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_client/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 09:58:37.000000 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_client/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2781 2023-06-27 09:58:37.000000 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_client/client.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 10:05:56.871680 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_pyclient.egg-info/
--rw-r--r--   0 root         (0) root         (0)     1337 2023-06-27 10:05:56.000000 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_pyclient.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      382 2023-06-27 10:05:56.000000 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_pyclient.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 10:05:56.000000 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_pyclient.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       17 2023-06-27 10:05:56.000000 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_pyclient.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       21 2023-06-27 10:05:56.000000 molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_pyclient.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)        7 2023-06-27 10:00:04.000000 molgenis_emx2_pyclient-8.198.3/version.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:47:54.078861 molgenis_emx2_pyclient-8.198.4/
+-rw-r--r--   0 root         (0) root         (0)     7631 2023-06-28 09:39:23.000000 molgenis_emx2_pyclient-8.198.4/LICENSE
+-rw-r--r--   0 root         (0) root         (0)     1337 2023-06-28 09:47:54.078861 molgenis_emx2_pyclient-8.198.4/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      953 2023-06-28 09:39:23.000000 molgenis_emx2_pyclient-8.198.4/README.md
+-rw-r--r--   0 root         (0) root         (0)      634 2023-06-28 09:39:23.000000 molgenis_emx2_pyclient-8.198.4/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)       16 2023-06-28 09:39:23.000000 molgenis_emx2_pyclient-8.198.4/requirements.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 09:47:54.078861 molgenis_emx2_pyclient-8.198.4/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:47:54.074861 molgenis_emx2_pyclient-8.198.4/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:47:54.078861 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_client/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-28 09:39:23.000000 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_client/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2781 2023-06-28 09:39:23.000000 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_client/client.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:47:54.078861 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_pyclient.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     1337 2023-06-28 09:47:54.000000 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_pyclient.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      382 2023-06-28 09:47:54.000000 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_pyclient.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 09:47:54.000000 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_pyclient.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       17 2023-06-28 09:47:54.000000 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_pyclient.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       21 2023-06-28 09:47:54.000000 molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_pyclient.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)        7 2023-06-28 09:41:02.000000 molgenis_emx2_pyclient-8.198.4/version.txt
```

### Comparing `molgenis_emx2_pyclient-8.198.3/LICENSE` & `molgenis_emx2_pyclient-8.198.4/LICENSE`

 * *Files identical despite different names*

### Comparing `molgenis_emx2_pyclient-8.198.3/PKG-INFO` & `molgenis_emx2_pyclient-8.198.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: molgenis_emx2_pyclient
-Version: 8.198.3
+Version: 8.198.4
 Summary: Python client for the Molgenis EMX2 API
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Lesser General Public License v3 (LGPLv3)
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 License-File: LICENSE
```

### Comparing `molgenis_emx2_pyclient-8.198.3/README.md` & `molgenis_emx2_pyclient-8.198.4/README.md`

 * *Files identical despite different names*

### Comparing `molgenis_emx2_pyclient-8.198.3/pyproject.toml` & `molgenis_emx2_pyclient-8.198.4/pyproject.toml`

 * *Files identical despite different names*

### Comparing `molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_client/client.py` & `molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_client/client.py`

 * *Files identical despite different names*

### Comparing `molgenis_emx2_pyclient-8.198.3/src/molgenis_emx2_pyclient.egg-info/PKG-INFO` & `molgenis_emx2_pyclient-8.198.4/src/molgenis_emx2_pyclient.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: molgenis-emx2-pyclient
-Version: 8.198.3
+Version: 8.198.4
 Summary: Python client for the Molgenis EMX2 API
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Lesser General Public License v3 (LGPLv3)
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.10
 Description-Content-Type: text/markdown
 License-File: LICENSE
```

