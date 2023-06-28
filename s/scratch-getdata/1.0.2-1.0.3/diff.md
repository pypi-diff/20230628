# Comparing `tmp/scratch-getdata-1.0.2.tar.gz` & `tmp/scratch-getdata-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "scratch-getdata-1.0.2.tar", last modified: Wed Jun 28 02:49:50 2023, max compression
+gzip compressed data, was "scratch-getdata-1.0.3.tar", last modified: Wed Jun 28 03:02:03 2023, max compression
```

## Comparing `scratch-getdata-1.0.2.tar` & `scratch-getdata-1.0.3.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1000) runner    (1000)        0 2023-06-28 02:49:50.308955 scratch-getdata-1.0.2/
--rw-r--r--   0 runner    (1000) runner    (1000)     2663 2023-06-28 02:49:50.308955 scratch-getdata-1.0.2/PKG-INFO
--rw-r--r--   0 runner    (1000) runner    (1000)     2100 2023-06-23 17:42:16.000000 scratch-getdata-1.0.2/README.md
--rw-r--r--   0 runner    (1000) runner    (1000)      633 2023-06-28 02:48:32.000000 scratch-getdata-1.0.2/pyproject.toml
-drwxr-xr-x   0 runner    (1000) runner    (1000)        0 2023-06-28 02:49:50.308955 scratch-getdata-1.0.2/scratch_getdata/
--rw-r--r--   0 runner    (1000) runner    (1000)      517 2023-06-23 18:37:46.000000 scratch-getdata-1.0.2/scratch_getdata/__init__.py
--rw-r--r--   0 runner    (1000) runner    (1000)     3596 2023-06-28 02:24:20.000000 scratch-getdata-1.0.2/scratch_getdata/api_client.py
-drwxr-xr-x   0 runner    (1000) runner    (1000)        0 2023-06-28 02:49:50.308955 scratch-getdata-1.0.2/scratch_getdata.egg-info/
--rw-r--r--   0 runner    (1000) runner    (1000)     2663 2023-06-28 02:49:50.000000 scratch-getdata-1.0.2/scratch_getdata.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1000) runner    (1000)      285 2023-06-28 02:49:50.000000 scratch-getdata-1.0.2/scratch_getdata.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1000) runner    (1000)        1 2023-06-28 02:49:50.000000 scratch-getdata-1.0.2/scratch_getdata.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1000) runner    (1000)        9 2023-06-28 02:49:50.000000 scratch-getdata-1.0.2/scratch_getdata.egg-info/requires.txt
--rw-r--r--   0 runner    (1000) runner    (1000)       16 2023-06-28 02:49:50.000000 scratch-getdata-1.0.2/scratch_getdata.egg-info/top_level.txt
--rw-r--r--   0 runner    (1000) runner    (1000)       38 2023-06-28 02:49:50.308955 scratch-getdata-1.0.2/setup.cfg
--rw-r--r--   0 runner    (1000) runner    (1000)      404 2023-06-28 02:32:47.000000 scratch-getdata-1.0.2/setup.py
+drwxr-xr-x   0 runner    (1000) runner    (1000)        0 2023-06-28 03:02:03.526544 scratch-getdata-1.0.3/
+-rw-r--r--   0 runner    (1000) runner    (1000)     2663 2023-06-28 03:02:03.526544 scratch-getdata-1.0.3/PKG-INFO
+-rw-r--r--   0 runner    (1000) runner    (1000)     2100 2023-06-23 17:42:16.000000 scratch-getdata-1.0.3/README.md
+-rw-r--r--   0 runner    (1000) runner    (1000)      661 2023-06-28 03:01:53.000000 scratch-getdata-1.0.3/pyproject.toml
+drwxr-xr-x   0 runner    (1000) runner    (1000)        0 2023-06-28 03:02:03.526544 scratch-getdata-1.0.3/scratch_getdata/
+-rw-r--r--   0 runner    (1000) runner    (1000)      517 2023-06-23 18:37:46.000000 scratch-getdata-1.0.3/scratch_getdata/__init__.py
+-rw-r--r--   0 runner    (1000) runner    (1000)     3616 2023-06-28 02:59:54.000000 scratch-getdata-1.0.3/scratch_getdata/api_client.py
+drwxr-xr-x   0 runner    (1000) runner    (1000)        0 2023-06-28 03:02:03.526544 scratch-getdata-1.0.3/scratch_getdata.egg-info/
+-rw-r--r--   0 runner    (1000) runner    (1000)     2663 2023-06-28 03:02:03.000000 scratch-getdata-1.0.3/scratch_getdata.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1000) runner    (1000)      285 2023-06-28 03:02:03.000000 scratch-getdata-1.0.3/scratch_getdata.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1000) runner    (1000)        1 2023-06-28 03:02:03.000000 scratch-getdata-1.0.3/scratch_getdata.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1000) runner    (1000)        9 2023-06-28 03:02:03.000000 scratch-getdata-1.0.3/scratch_getdata.egg-info/requires.txt
+-rw-r--r--   0 runner    (1000) runner    (1000)       16 2023-06-28 03:02:03.000000 scratch-getdata-1.0.3/scratch_getdata.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1000) runner    (1000)       38 2023-06-28 03:02:03.526544 scratch-getdata-1.0.3/setup.cfg
+-rw-r--r--   0 runner    (1000) runner    (1000)      404 2023-06-28 02:32:47.000000 scratch-getdata-1.0.3/setup.py
```

### Comparing `scratch-getdata-1.0.2/PKG-INFO` & `scratch-getdata-1.0.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: scratch-getdata
-Version: 1.0.2
+Version: 1.0.3
 Summary: A Module to fetch scratch things from ScratchGetData
 Author: kokofixcomputers
 Author-email: kokofixcomputers <none@none.com>
 Project-URL: Homepage, https://github.com/kokofixcomputers/Scratch-getdata
 Project-URL: Bug Tracker, https://github.com/kokofixcomputers/Scratch-getdata/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `scratch-getdata-1.0.2/README.md` & `scratch-getdata-1.0.3/README.md`

 * *Files identical despite different names*

### Comparing `scratch-getdata-1.0.2/pyproject.toml` & `scratch-getdata-1.0.3/pyproject.toml`

 * *Files 22% similar despite different names*

```diff
@@ -1,17 +1,18 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "scratch-getdata"
-version = "1.0.2"
+version = "1.0.3"
 authors = [
   { name="kokofixcomputers", email="none@none.com" },
 ]
+dependencies = ['requests']
 description = "A Module to fetch scratch things from ScratchGetData"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
```

### Comparing `scratch-getdata-1.0.2/scratch_getdata/__init__.py` & `scratch-getdata-1.0.3/scratch_getdata/__init__.py`

 * *Files identical despite different names*

### Comparing `scratch-getdata-1.0.2/scratch_getdata/api_client.py` & `scratch-getdata-1.0.3/scratch_getdata/api_client.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 import requests
 
 class ScratchAPIClient:
     def __init__(self):
-        print("If you use GetData please credit @kokofixcomputers")
+        print("It may take a while for ScratchForGetData to boot up like 3-10 seconds")
         self.base_url = "https://scratch-get-data.kokoiscool.repl.co"
 
     def get_follower_count(self, username):
         url = f"{self.base_url}/get/follower-count/{username}/"
         response = requests.get(url)
         return response.text.strip()  # Return the follower count as a string
```

### Comparing `scratch-getdata-1.0.2/scratch_getdata.egg-info/PKG-INFO` & `scratch-getdata-1.0.3/scratch_getdata.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: scratch-getdata
-Version: 1.0.2
+Version: 1.0.3
 Summary: A Module to fetch scratch things from ScratchGetData
 Author: kokofixcomputers
 Author-email: kokofixcomputers <none@none.com>
 Project-URL: Homepage, https://github.com/kokofixcomputers/Scratch-getdata
 Project-URL: Bug Tracker, https://github.com/kokofixcomputers/Scratch-getdata/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

