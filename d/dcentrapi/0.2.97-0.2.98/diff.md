# Comparing `tmp/dcentrapi-0.2.97.tar.gz` & `tmp/dcentrapi-0.2.98.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dcentrapi-0.2.97.tar", last modified: Wed Jun 28 06:20:37 2023, max compression
+gzip compressed data, was "dcentrapi-0.2.98.tar", last modified: Wed Jun 28 06:35:48 2023, max compression
```

## Comparing `dcentrapi-0.2.97.tar` & `dcentrapi-0.2.98.tar`

### file list

```diff
@@ -1,24 +1,23 @@
-drwxr-xr-x   0 oded       (502) staff       (20)        0 2023-06-28 06:20:37.948992 dcentrapi-0.2.97/
--rw-r--r--   0 oded       (502) staff       (20)     1073 2022-09-29 14:45:59.000000 dcentrapi-0.2.97/LICENSE.rst
--rw-r--r--   0 oded       (502) staff       (20)     6742 2023-06-28 06:20:37.948856 dcentrapi-0.2.97/PKG-INFO
--rw-r--r--   0 oded       (502) staff       (20)     6211 2022-09-29 14:45:59.000000 dcentrapi-0.2.97/README.md
-drwxr-xr-x   0 oded       (502) staff       (20)        0 2023-06-28 06:20:37.947890 dcentrapi-0.2.97/dcentrapi/
--rw-r--r--   0 oded       (502) staff       (20)      771 2023-06-28 06:20:27.000000 dcentrapi-0.2.97/dcentrapi/Base.py
--rw-r--r--   0 oded       (502) staff       (20)      397 2023-06-27 14:19:43.000000 dcentrapi-0.2.97/dcentrapi/__init__.py
--rw-r--r--   0 oded       (502) staff       (20)      130 2023-06-27 14:19:42.000000 dcentrapi-0.2.97/dcentrapi/common.py
--rw-r--r--   0 oded       (502) staff       (20)     8761 2023-06-27 14:19:43.000000 dcentrapi-0.2.97/dcentrapi/eventPolling.py
--rw-r--r--   0 oded       (502) staff       (20)      525 2023-06-27 14:19:43.000000 dcentrapi-0.2.97/dcentrapi/gasMonitor.py
--rw-r--r--   0 oded       (502) staff       (20)      404 2023-06-28 06:20:18.000000 dcentrapi-0.2.97/dcentrapi/hackMitigation.py
--rw-r--r--   0 oded       (502) staff       (20)     3078 2022-12-21 09:08:31.000000 dcentrapi-0.2.97/dcentrapi/merkleTree.py
--rw-r--r--   0 oded       (502) staff       (20)      226 2023-06-27 14:19:43.000000 dcentrapi-0.2.97/dcentrapi/requests_dappi.py
--rw-r--r--   0 oded       (502) staff       (20)     3107 2023-06-27 14:19:43.000000 dcentrapi-0.2.97/dcentrapi/rpcAggregation.py
--rw-r--r--   0 oded       (502) staff       (20)      909 2022-11-10 13:20:43.000000 dcentrapi-0.2.97/dcentrapi/test.py
--rw-r--r--   0 oded       (502) staff       (20)      837 2023-06-27 14:19:43.000000 dcentrapi-0.2.97/dcentrapi/web3Index.py
-drwxr-xr-x   0 oded       (502) staff       (20)        0 2023-06-28 06:20:37.948659 dcentrapi-0.2.97/dcentrapi.egg-info/
--rw-r--r--   0 oded       (502) staff       (20)     6742 2023-06-28 06:20:37.000000 dcentrapi-0.2.97/dcentrapi.egg-info/PKG-INFO
--rw-r--r--   0 oded       (502) staff       (20)      453 2023-06-28 06:20:37.000000 dcentrapi-0.2.97/dcentrapi.egg-info/SOURCES.txt
--rw-r--r--   0 oded       (502) staff       (20)        1 2023-06-28 06:20:37.000000 dcentrapi-0.2.97/dcentrapi.egg-info/dependency_links.txt
--rw-r--r--   0 oded       (502) staff       (20)        9 2023-06-28 06:20:37.000000 dcentrapi-0.2.97/dcentrapi.egg-info/requires.txt
--rw-r--r--   0 oded       (502) staff       (20)       10 2023-06-28 06:20:37.000000 dcentrapi-0.2.97/dcentrapi.egg-info/top_level.txt
--rw-r--r--   0 oded       (502) staff       (20)       38 2023-06-28 06:20:37.949029 dcentrapi-0.2.97/setup.cfg
--rw-r--r--   0 oded       (502) staff       (20)     1110 2023-06-28 06:20:18.000000 dcentrapi-0.2.97/setup.py
+drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 06:35:48.361132 dcentrapi-0.2.98/
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     1073 2022-10-09 08:58:27.000000 dcentrapi-0.2.98/LICENSE.rst
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     6781 2023-06-28 06:35:48.361003 dcentrapi-0.2.98/PKG-INFO
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     6211 2022-10-09 08:58:27.000000 dcentrapi-0.2.98/README.md
+drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 06:35:48.360173 dcentrapi-0.2.98/dcentrapi/
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      771 2023-06-28 06:35:22.000000 dcentrapi-0.2.98/dcentrapi/Base.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      397 2023-06-27 14:44:06.000000 dcentrapi-0.2.98/dcentrapi/__init__.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      130 2023-06-27 13:48:08.000000 dcentrapi-0.2.98/dcentrapi/common.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     8761 2023-06-27 14:44:57.000000 dcentrapi-0.2.98/dcentrapi/eventPolling.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      525 2023-06-27 14:44:57.000000 dcentrapi-0.2.98/dcentrapi/gasMonitor.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      561 2023-06-28 06:33:24.000000 dcentrapi-0.2.98/dcentrapi/hackMitigation.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     3078 2022-11-22 15:13:50.000000 dcentrapi-0.2.98/dcentrapi/merkleTree.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      226 2023-06-27 14:44:58.000000 dcentrapi-0.2.98/dcentrapi/requests_dappi.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     3107 2023-06-27 14:44:58.000000 dcentrapi-0.2.98/dcentrapi/rpcAggregation.py
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      837 2023-06-27 14:44:59.000000 dcentrapi-0.2.98/dcentrapi/web3Index.py
+drwxr-xr-x   0 nivshitrit   (501) staff       (20)        0 2023-06-28 06:35:48.360832 dcentrapi-0.2.98/dcentrapi.egg-info/
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     6781 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/PKG-INFO
+-rw-r--r--   0 nivshitrit   (501) staff       (20)      435 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/SOURCES.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)        1 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/dependency_links.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)        9 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/requires.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)       10 2023-06-28 06:35:48.000000 dcentrapi-0.2.98/dcentrapi.egg-info/top_level.txt
+-rw-r--r--   0 nivshitrit   (501) staff       (20)       38 2023-06-28 06:35:48.361256 dcentrapi-0.2.98/setup.cfg
+-rw-r--r--   0 nivshitrit   (501) staff       (20)     1110 2023-06-28 06:35:27.000000 dcentrapi-0.2.98/setup.py
```

### Comparing `dcentrapi-0.2.97/LICENSE.rst` & `dcentrapi-0.2.98/LICENSE.rst`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.97/PKG-INFO` & `dcentrapi-0.2.98/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,17 @@
 Metadata-Version: 2.1
 Name: dcentrapi
-Version: 0.2.97
+Version: 0.2.98
 Summary: Dcentralab Pypi packages
+Home-page: UNKNOWN
 Author: Dcentralab (Niv Shitrit)
 Author-email: <niv@dcentralab.com>
 License: MIT
 Keywords: python
+Platform: UNKNOWN
 Classifier: Development Status :: 1 - Planning
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: Unix
 Classifier: Operating System :: MacOS :: MacOS X
 Classifier: Operating System :: Microsoft :: Windows
 Description-Content-Type: text/markdown
@@ -103,7 +105,9 @@
 Show your appreciation to those who have contributed to the project.
 
 ## License
 For open source projects, say how it is licensed.
 
 ## Project status
 If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
+
+
```

### Comparing `dcentrapi-0.2.97/README.md` & `dcentrapi-0.2.98/README.md`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.97/dcentrapi/Base.py` & `dcentrapi-0.2.98/dcentrapi/Base.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 class Base:
     def __init__(self, stage, username=None, key=None):
-        self.__version__ = "0.2.97"
+        self.__version__ = "0.2.98"
 
         if stage == "develop":
             self.headers = {"Authorization": username + "," + key}
             self.url = "https://test-api.dcentralab.com/"
             self.web3index_url = "https://test-api.web3index.info/"
         if stage == "staging":
             self.headers = {"Authorization": username + "," + key}
```

### Comparing `dcentrapi-0.2.97/dcentrapi/eventPolling.py` & `dcentrapi-0.2.98/dcentrapi/eventPolling.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.97/dcentrapi/gasMonitor.py` & `dcentrapi-0.2.98/dcentrapi/gasMonitor.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.97/dcentrapi/merkleTree.py` & `dcentrapi-0.2.98/dcentrapi/merkleTree.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.97/dcentrapi/rpcAggregation.py` & `dcentrapi-0.2.98/dcentrapi/rpcAggregation.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.97/dcentrapi/web3Index.py` & `dcentrapi-0.2.98/dcentrapi/web3Index.py`

 * *Files identical despite different names*

### Comparing `dcentrapi-0.2.97/dcentrapi.egg-info/PKG-INFO` & `dcentrapi-0.2.98/dcentrapi.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,17 @@
 Metadata-Version: 2.1
 Name: dcentrapi
-Version: 0.2.97
+Version: 0.2.98
 Summary: Dcentralab Pypi packages
+Home-page: UNKNOWN
 Author: Dcentralab (Niv Shitrit)
 Author-email: <niv@dcentralab.com>
 License: MIT
 Keywords: python
+Platform: UNKNOWN
 Classifier: Development Status :: 1 - Planning
 Classifier: Intended Audience :: Developers
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: Unix
 Classifier: Operating System :: MacOS :: MacOS X
 Classifier: Operating System :: Microsoft :: Windows
 Description-Content-Type: text/markdown
@@ -103,7 +105,9 @@
 Show your appreciation to those who have contributed to the project.
 
 ## License
 For open source projects, say how it is licensed.
 
 ## Project status
 If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
+
+
```

### Comparing `dcentrapi-0.2.97/setup.py` & `dcentrapi-0.2.98/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -8,15 +8,15 @@
     return result.group(1)
 
 
 DESCRIPTION = 'Dcentralab Pypi packages'
 this_directory = Path(__file__).parent
 LONG_DESCRIPTION = (this_directory / "README.md").read_text()
 project_name = 'dcentrapi'
-VERSION = "0.2.97"
+VERSION = "0.2.98"
 
 
 # Setting up
 setup(
     name="dcentrapi",
     version=VERSION,
     author="Dcentralab (Niv Shitrit)",
```

