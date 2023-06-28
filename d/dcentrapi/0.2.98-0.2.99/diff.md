# Comparing `tmp/dcentrapi-0.2.98.tar.gz` & `tmp/dcentrapi-0.2.99.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dcentrapi-0.2.98.tar", last modified: Wed Jun 28 06:35:48 2023, max compression
+gzip compressed data, was "dcentrapi-0.2.99.tar", last modified: Wed Jun 28 07:00:34 2023, max compression
```

## Comparing `dcentrapi-0.2.98.tar` & `dcentrapi-0.2.99.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 06:35:48.361132 dcentrapi-0.2.98/
--rw-r--r--   0 nivshitrit   (501) staff       (20)     1073 2022-10-09 08:58:27.000000 dcentrapi-0.2.98/LICENSE.rst
--rw-r--r--   0 nivshitrit   (501) staff       (20)     6781 2023-06-28 06:35:48.361003 dcentrapi-0.2.98/PKG-INFO
--rw-r--r--   0 nivshitrit   (501) staff       (20)     6211 2022-10-09 08:58:27.000000 dcentrapi-0.2.98/README.md
-drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 06:35:48.360173 dcentrapi-0.2.98/dcentrapi/
--rw-r--r--   0 nivshitrit   (501) staff       (20)      771 2023-06-28 06:35:22.000000 dcentrapi-0.2.98/dcentrapi/Base.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)      397 2023-06-27 14:44:06.000000 dcentrapi-0.2.98/dcentrapi/__init__.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)      130 2023-06-27 13:48:08.000000 dcentrapi-0.2.98/dcentrapi/common.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)     8761 2023-06-27 14:44:57.000000 dcentrapi-0.2.98/dcentrapi/eventPolling.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)      525 2023-06-27 14:44:57.000000 dcentrapi-0.2.98/dcentrapi/gasMonitor.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)      561 2023-06-28 06:33:24.000000 dcentrapi-0.2.98/dcentrapi/hackMitigation.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)     3078 2022-11-22 15:13:50.000000 dcentrapi-0.2.98/dcentrapi/merkleTree.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)      226 2023-06-27 14:44:58.000000 dcentrapi-0.2.98/dcentrapi/requests_dappi.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)     3107 2023-06-27 14:44:58.000000 dcentrapi-0.2.98/dcentrapi/rpcAggregation.py
--rw-r--r--   0 nivshitrit   (501) staff       (20)      837 2023-06-27 14:44:59.000000 dcentrapi-0.2.98/dcentrapi/web3Index.py
-drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 06:35:48.360832 dcentrapi-0.2.98/dcentrapi.egg-info/
--rw-r--r--   0 nivshitrit   (501) staff       (20)     6781 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/PKG-INFO
--rw-r--r--   0 nivshitrit   (501) staff       (20)      435 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/SOURCES.txt
--rw-r--r--   0 nivshitrit   (501) staff       (20)        1 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/dependency_links.txt
--rw-r--r--   0 nivshitrit   (501) staff       (20)        9 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/requires.txt
--rw-r--r--   0 nivshitrit   (501) staff       (20)       10 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/top_level.txt
--rw-r--r--   0 nivshitrit   (501) staff       (20)       38 2023-06-28 06:35:48.361256 dcentrapi-0.2.98/setup.cfg
--rw-r--r--   0 nivshitrit   (501) staff       (20)     1110 2023-06-28 06:35:27.000000 dcentrapi-0.2.98/setup.py
+drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 07:00:34.677385 dcentrapi-0.2.99/
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     1073 2022-10-09 08:58:27.000000 dcentrapi-0.2.99/LICENSE.rst
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     6781 2023-06-28 07:00:34.677235 dcentrapi-0.2.99/PKG-INFO
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     6211 2022-10-09 08:58:27.000000 dcentrapi-0.2.99/README.md
+drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 07:00:34.675855 dcentrapi-0.2.99/dcentrapi/
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      771 2023-06-28 06:59:23.000000 dcentrapi-0.2.99/dcentrapi/Base.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      397 2023-06-27 14:44:06.000000 dcentrapi-0.2.99/dcentrapi/__init__.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      130 2023-06-27 13:48:08.000000 dcentrapi-0.2.99/dcentrapi/common.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     8761 2023-06-27 14:44:57.000000 dcentrapi-0.2.99/dcentrapi/eventPolling.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      525 2023-06-27 14:44:57.000000 dcentrapi-0.2.99/dcentrapi/gasMonitor.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      561 2023-06-28 06:33:24.000000 dcentrapi-0.2.99/dcentrapi/hackMitigation.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     3078 2022-11-22 15:13:50.000000 dcentrapi-0.2.99/dcentrapi/merkleTree.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      246 2023-06-28 07:00:24.000000 dcentrapi-0.2.99/dcentrapi/requests_dappi.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     3107 2023-06-27 14:44:58.000000 dcentrapi-0.2.99/dcentrapi/rpcAggregation.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      837 2023-06-27 14:44:59.000000 dcentrapi-0.2.99/dcentrapi/web3Index.py
+drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 07:00:34.677016 dcentrapi-0.2.99/dcentrapi.egg-info/
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     6781 2023-06-28 07:00:34.000000 dcentrapi-0.2.99/dcentrapi.egg-info/PKG-INFO
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      435 2023-06-28 07:00:34.000000 dcentrapi-0.2.99/dcentrapi.egg-info/SOURCES.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)        1 2023-06-28 07:00:34.000000 dcentrapi-0.2.99/dcentrapi.egg-info/dependency_links.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)        9 2023-06-28 07:00:34.000000 dcentrapi-0.2.99/dcentrapi.egg-info/requires.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)       10 2023-06-28 07:00:34.000000 dcentrapi-0.2.99/dcentrapi.egg-info/top_level.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)       38 2023-06-28 07:00:34.677523 dcentrapi-0.2.99/setup.cfg
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     1110 2023-06-28 06:59:17.000000 dcentrapi-0.2.99/setup.py
```

### Comparing `dcentrapi-0.2.98/LICENSE.rst` & `dcentrapi-0.2.99/LICENSE.rst`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/PKG-INFO` & `dcentrapi-0.2.99/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dcentrapi
-Version: 0.2.98
+Version: 0.2.99
 Summary: Dcentralab Pypi packages
 Home-page: UNKNOWN
 Author: Dcentralab (Niv Shitrit)
 Author-email: <niv@dcentralab.com>
 License: MIT
 Keywords: python
 Platform: UNKNOWN
```

### Comparing `dcentrapi-0.2.98/README.md` & `dcentrapi-0.2.99/README.md`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/dcentrapi/Base.py` & `dcentrapi-0.2.99/dcentrapi/Base.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 class Base:
     def __init__(self, stage, username=None, key=None):
-        self.__version__ = "0.2.98"
+        self.__version__ = "0.2.99"
 
         if stage == "develop":
             self.headers = {"Authorization": username + "," + key}
             self.url = "https://test-api.dcentralab.com/"
             self.web3index_url = "https://test-api.web3index.info/"
         if stage == "staging":
             self.headers = {"Authorization": username + "," + key}
```

### Comparing `dcentrapi-0.2.98/dcentrapi/eventPolling.py` & `dcentrapi-0.2.99/dcentrapi/eventPolling.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/dcentrapi/gasMonitor.py` & `dcentrapi-0.2.99/dcentrapi/gasMonitor.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/dcentrapi/hackMitigation.py` & `dcentrapi-0.2.99/dcentrapi/hackMitigation.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/dcentrapi/merkleTree.py` & `dcentrapi-0.2.99/dcentrapi/merkleTree.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/dcentrapi/rpcAggregation.py` & `dcentrapi-0.2.99/dcentrapi/rpcAggregation.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/dcentrapi/web3Index.py` & `dcentrapi-0.2.99/dcentrapi/web3Index.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.98/dcentrapi.egg-info/PKG-INFO` & `dcentrapi-0.2.99/dcentrapi.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dcentrapi
-Version: 0.2.98
+Version: 0.2.99
 Summary: Dcentralab Pypi packages
 Home-page: UNKNOWN
 Author: Dcentralab (Niv Shitrit)
 Author-email: <niv@dcentralab.com>
 License: MIT
 Keywords: python
 Platform: UNKNOWN
```

### Comparing `dcentrapi-0.2.98/setup.py` & `dcentrapi-0.2.99/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -8,15 +8,15 @@
     return result.group(1)
 
 
 DESCRIPTION = 'Dcentralab Pypi packages'
 this_directory = Path(__file__).parent
 LONG_DESCRIPTION = (this_directory / "README.md").read_text()
 project_name = 'dcentrapi'
-VERSION = "0.2.98"
+VERSION = "0.2.99"
 
 
 # Setting up
 setup(
     name="dcentrapi",
     version=VERSION,
     author="Dcentralab (Niv Shitrit)",
```

