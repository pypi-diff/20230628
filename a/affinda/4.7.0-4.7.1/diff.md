# Comparing `tmp/affinda-4.7.0.tar.gz` & `tmp/affinda-4.7.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "affinda-4.7.0.tar", last modified: Tue Jun 27 11:03:28 2023, max compression
+gzip compressed data, was "affinda-4.7.1.tar", last modified: Wed Jun 28 05:14:36 2023, max compression
```

## Comparing `affinda-4.7.0.tar` & `affinda-4.7.1.tar`

### file list

```diff
@@ -1,50 +1,50 @@
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.555035 affinda-4.7.0/
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     9766 2023-06-27 11:02:19.000000 affinda-4.7.0/CHANGELOG.md
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1069 2023-03-29 10:14:51.000000 affinda-4.7.0/LICENSE
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      484 2023-03-29 10:14:51.000000 affinda-4.7.0/MANIFEST.in
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)    15360 2023-06-27 11:03:28.555035 affinda-4.7.0/PKG-INFO
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     3272 2023-05-23 10:29:20.000000 affinda-4.7.0/README.md
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.547035 affinda-4.7.0/affinda/
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      659 2023-03-29 10:14:51.000000 affinda-4.7.0/affinda/__init__.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)     3516 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/_affinda_api.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)     3230 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/_configuration.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     2229 2023-03-29 10:14:51.000000 affinda-4.7.0/affinda/_patch.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)     1081 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/_vendor.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      384 2023-06-27 11:02:59.000000 affinda-4.7.0/affinda/_version.py
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.551035 affinda-4.7.0/affinda/aio/
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      722 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/aio/__init__.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)     3444 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/aio/_affinda_api.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)     3184 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/aio/_configuration.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      800 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/aio/_patch.py
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.551035 affinda-4.7.0/affinda/aio/operations/
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      716 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/aio/operations/__init__.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)   299470 2023-06-27 11:03:16.000000 affinda-4.7.0/affinda/aio/operations/_affinda_api_operations.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      800 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/aio/operations/_patch.py
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.555035 affinda-4.7.0/affinda/models/
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)    56563 2023-06-27 11:03:12.000000 affinda-4.7.0/affinda/models/__init__.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)    11215 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/models/_affinda_api_enums.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)   826362 2023-06-27 11:03:19.000000 affinda-4.7.0/affinda/models/_models.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)   926762 2023-06-27 11:03:20.000000 affinda-4.7.0/affinda/models/_models_py3.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      800 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/models/_patch.py
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.555035 affinda-4.7.0/affinda/operations/
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      716 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/operations/__init__.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)   393041 2023-06-27 11:03:17.000000 affinda-4.7.0/affinda/operations/_affinda_api_operations.py
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      800 2023-06-27 11:03:11.000000 affinda-4.7.0/affinda/operations/_patch.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)        0 2023-03-29 10:14:51.000000 affinda-4.7.0/affinda/py.typed
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      392 2023-03-29 10:14:51.000000 affinda-4.7.0/affinda/token_credential.py
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.551035 affinda-4.7.0/affinda.egg-info/
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)    15360 2023-06-27 11:03:28.000000 affinda-4.7.0/affinda.egg-info/PKG-INFO
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      999 2023-06-27 11:03:28.000000 affinda-4.7.0/affinda.egg-info/SOURCES.txt
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)        1 2023-06-27 11:03:28.000000 affinda-4.7.0/affinda.egg-info/dependency_links.txt
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)      129 2023-06-27 11:03:28.000000 affinda-4.7.0/affinda.egg-info/requires.txt
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)        8 2023-06-27 11:03:28.000000 affinda-4.7.0/affinda.egg-info/top_level.txt
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)        1 2023-06-27 11:03:28.000000 affinda-4.7.0/affinda.egg-info/zip-safe
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    19865 2023-03-29 10:14:51.000000 affinda-4.7.0/affinda_logo.png
-drwxr-xr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:28.555035 affinda-4.7.0/docs/
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 11:03:10.000000 affinda-4.7.0/docs/exceptions.md
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)   443791 2023-06-27 11:03:10.000000 affinda-4.7.0/docs/models.md
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)    42946 2023-06-27 11:03:00.000000 affinda-4.7.0/docs/samples_python.md
--rw-r--r--   0 ubuntu    (1000) ubuntu    (1000)    73094 2023-06-27 11:03:10.000000 affinda-4.7.0/docs/sync_operations.md
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      211 2023-03-29 10:14:51.000000 affinda-4.7.0/pyproject.toml
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1601 2023-06-27 11:03:28.555035 affinda-4.7.0/setup.cfg
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       38 2023-03-29 10:14:51.000000 affinda-4.7.0/setup.py
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.877944 affinda-4.7.1/
+-rw-rw-r--   0 chris     (1000) chris     (1000)     9886 2023-06-28 05:13:52.000000 affinda-4.7.1/CHANGELOG.md
+-rw-rw-r--   0 chris     (1000) chris     (1000)     1069 2023-04-19 11:04:37.000000 affinda-4.7.1/LICENSE
+-rw-rw-r--   0 chris     (1000) chris     (1000)      484 2023-04-19 11:04:37.000000 affinda-4.7.1/MANIFEST.in
+-rw-r--r--   0 chris     (1000) chris     (1000)    15480 2023-06-28 05:14:36.877944 affinda-4.7.1/PKG-INFO
+-rw-rw-r--   0 chris     (1000) chris     (1000)     3272 2023-05-09 01:22:09.000000 affinda-4.7.1/README.md
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.869944 affinda-4.7.1/affinda/
+-rw-rw-r--   0 chris     (1000) chris     (1000)      659 2023-04-19 11:04:37.000000 affinda-4.7.1/affinda/__init__.py
+-rw-r--r--   0 chris     (1000) chris     (1000)     3516 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/_affinda_api.py
+-rw-r--r--   0 chris     (1000) chris     (1000)     3230 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/_configuration.py
+-rw-rw-r--   0 chris     (1000) chris     (1000)     2229 2023-04-19 11:04:37.000000 affinda-4.7.1/affinda/_patch.py
+-rw-r--r--   0 chris     (1000) chris     (1000)     1081 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/_vendor.py
+-rw-r--r--   0 chris     (1000) chris     (1000)      384 2023-06-28 05:14:19.000000 affinda-4.7.1/affinda/_version.py
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.873944 affinda-4.7.1/affinda/aio/
+-rw-r--r--   0 chris     (1000) chris     (1000)      722 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/aio/__init__.py
+-rw-r--r--   0 chris     (1000) chris     (1000)     3444 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/aio/_affinda_api.py
+-rw-r--r--   0 chris     (1000) chris     (1000)     3184 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/aio/_configuration.py
+-rw-r--r--   0 chris     (1000) chris     (1000)      800 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/aio/_patch.py
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.873944 affinda-4.7.1/affinda/aio/operations/
+-rw-r--r--   0 chris     (1000) chris     (1000)      716 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/aio/operations/__init__.py
+-rw-r--r--   0 chris     (1000) chris     (1000)   299636 2023-06-28 05:14:29.000000 affinda-4.7.1/affinda/aio/operations/_affinda_api_operations.py
+-rw-r--r--   0 chris     (1000) chris     (1000)      800 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/aio/operations/_patch.py
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.873944 affinda-4.7.1/affinda/models/
+-rw-r--r--   0 chris     (1000) chris     (1000)    56563 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/models/__init__.py
+-rw-r--r--   0 chris     (1000) chris     (1000)    11215 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/models/_affinda_api_enums.py
+-rw-r--r--   0 chris     (1000) chris     (1000)   826362 2023-06-28 05:14:32.000000 affinda-4.7.1/affinda/models/_models.py
+-rw-r--r--   0 chris     (1000) chris     (1000)   926762 2023-06-28 05:14:32.000000 affinda-4.7.1/affinda/models/_models_py3.py
+-rw-r--r--   0 chris     (1000) chris     (1000)      800 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/models/_patch.py
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.877944 affinda-4.7.1/affinda/operations/
+-rw-r--r--   0 chris     (1000) chris     (1000)      716 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/operations/__init__.py
+-rw-r--r--   0 chris     (1000) chris     (1000)   393207 2023-06-28 05:14:30.000000 affinda-4.7.1/affinda/operations/_affinda_api_operations.py
+-rw-r--r--   0 chris     (1000) chris     (1000)      800 2023-06-28 05:14:26.000000 affinda-4.7.1/affinda/operations/_patch.py
+-rw-rw-r--   0 chris     (1000) chris     (1000)        0 2023-06-27 10:03:29.000000 affinda-4.7.1/affinda/py.typed
+-rw-rw-r--   0 chris     (1000) chris     (1000)      392 2023-04-19 11:04:37.000000 affinda-4.7.1/affinda/token_credential.py
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.869944 affinda-4.7.1/affinda.egg-info/
+-rw-r--r--   0 chris     (1000) chris     (1000)    15480 2023-06-28 05:14:36.000000 affinda-4.7.1/affinda.egg-info/PKG-INFO
+-rw-r--r--   0 chris     (1000) chris     (1000)      999 2023-06-28 05:14:36.000000 affinda-4.7.1/affinda.egg-info/SOURCES.txt
+-rw-r--r--   0 chris     (1000) chris     (1000)        1 2023-06-28 05:14:36.000000 affinda-4.7.1/affinda.egg-info/dependency_links.txt
+-rw-r--r--   0 chris     (1000) chris     (1000)      129 2023-06-28 05:14:36.000000 affinda-4.7.1/affinda.egg-info/requires.txt
+-rw-r--r--   0 chris     (1000) chris     (1000)        8 2023-06-28 05:14:36.000000 affinda-4.7.1/affinda.egg-info/top_level.txt
+-rw-r--r--   0 chris     (1000) chris     (1000)        1 2023-06-28 05:14:36.000000 affinda-4.7.1/affinda.egg-info/zip-safe
+-rw-rw-r--   0 chris     (1000) chris     (1000)    19865 2023-04-19 11:04:37.000000 affinda-4.7.1/affinda_logo.png
+drwxr-xr-x   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:36.877944 affinda-4.7.1/docs/
+-rw-r--r--   0 chris     (1000) chris     (1000)        0 2023-06-28 05:14:26.000000 affinda-4.7.1/docs/exceptions.md
+-rw-r--r--   0 chris     (1000) chris     (1000)   443791 2023-06-28 05:14:26.000000 affinda-4.7.1/docs/models.md
+-rw-r--r--   0 chris     (1000) chris     (1000)    42946 2023-06-28 05:14:20.000000 affinda-4.7.1/docs/samples_python.md
+-rw-r--r--   0 chris     (1000) chris     (1000)    73094 2023-06-28 05:14:26.000000 affinda-4.7.1/docs/sync_operations.md
+-rw-rw-r--   0 chris     (1000) chris     (1000)      211 2023-06-27 23:08:43.000000 affinda-4.7.1/pyproject.toml
+-rw-rw-r--   0 chris     (1000) chris     (1000)     1601 2023-06-28 05:14:36.877944 affinda-4.7.1/setup.cfg
+-rw-rw-r--   0 chris     (1000) chris     (1000)       38 2023-04-19 11:04:37.000000 affinda-4.7.1/setup.py
```

### Comparing `affinda-4.7.0/CHANGELOG.md` & `affinda-4.7.1/CHANGELOG.md`

 * *Files 2% similar despite different names*

```diff
@@ -2,14 +2,18 @@
 All notable changes to this project will be documented in this file.
 
 The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
 and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
 
 ## [Unreleased]
 
+## [4.7.1] - 2023-06-28
+### Added
+- Add xml response to api spec to GET /v3/documenets to match existing functionality
+
 ## [4.7.0] - 2023-06-27
 ### Added
 - Allow create/update data point's `parent` and `displayEnumValue` property
 - Allow explicitly set a document as low_priority
 
 ### Changed
 - Make `slug` and `organization` required when creating data point
```

### Comparing `affinda-4.7.0/LICENSE` & `affinda-4.7.1/LICENSE`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/PKG-INFO` & `affinda-4.7.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: affinda
-Version: 4.7.0
+Version: 4.7.1
 Summary: Client library for the Affinda API
 Home-page: https://github.com/affinda/affinda-python
 Author: Affinda
 Author-email: contact@affinda.com
 Maintainer: Affinda
 Maintainer-email: contact@affinda.com
 License: MIT
@@ -124,14 +124,18 @@
 All notable changes to this project will be documented in this file.
 
 The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
 and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
 
 ## [Unreleased]
 
+## [4.7.1] - 2023-06-28
+### Added
+- Add xml response to api spec to GET /v3/documenets to match existing functionality
+
 ## [4.7.0] - 2023-06-27
 ### Added
 - Allow create/update data point's `parent` and `displayEnumValue` property
 - Allow explicitly set a document as low_priority
 
 ### Changed
 - Make `slug` and `organization` required when creating data point
```

### Comparing `affinda-4.7.0/README.md` & `affinda-4.7.1/README.md`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda/__init__.py` & `affinda-4.7.1/affinda/__init__.py`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda/_affinda_api.py` & `affinda-4.7.1/affinda/_affinda_api.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from copy import deepcopy
 from typing import TYPE_CHECKING
 
 from msrest import Deserializer, Serializer
```

### Comparing `affinda-4.7.0/affinda/_configuration.py` & `affinda-4.7.1/affinda/_configuration.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from typing import TYPE_CHECKING
 
 from azure.core.configuration import Configuration
 from azure.core.pipeline import policies
```

### Comparing `affinda-4.7.0/affinda/_patch.py` & `affinda-4.7.1/affinda/_patch.py`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda/_vendor.py` & `affinda-4.7.1/affinda/_vendor.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from azure.core.pipeline.transport import HttpRequest
 
 
 def _convert_request(request, files=None):
```

### Comparing `affinda-4.7.0/affinda/aio/__init__.py` & `affinda-4.7.1/affinda/aio/__init__.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from ._affinda_api import AffindaAPI
 
 try:
     from ._patch import __all__ as _patch_all
```

### Comparing `affinda-4.7.0/affinda/aio/_affinda_api.py` & `affinda-4.7.1/affinda/aio/_affinda_api.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from copy import deepcopy
 from typing import Any, Awaitable, TYPE_CHECKING, Union
 
 from msrest import Deserializer, Serializer
```

### Comparing `affinda-4.7.0/affinda/aio/_configuration.py` & `affinda-4.7.1/affinda/aio/_configuration.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from typing import Any, TYPE_CHECKING, Union
 
 from azure.core.configuration import Configuration
 from azure.core.pipeline import policies
```

### Comparing `affinda-4.7.0/affinda/aio/_patch.py` & `affinda-4.7.1/affinda/aio/_patch.py`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda/aio/operations/__init__.py` & `affinda-4.7.1/affinda/aio/operations/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from ._affinda_api_operations import AffindaAPIOperationsMixin
 
 from ._patch import __all__ as _patch_all
 from ._patch import *  # type: ignore # pylint: disable=unused-wildcard-import
```

### Comparing `affinda-4.7.0/affinda/aio/operations/_affinda_api_operations.py` & `affinda-4.7.1/affinda/aio/operations/_affinda_api_operations.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 # pylint: disable=too-many-lines
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 import datetime
 from typing import Any, Callable, Dict, IO, List, Optional, TypeVar, Union
 
 from azure.core.exceptions import (
     ClientAuthenticationError,
@@ -1427,20 +1427,24 @@
         request.url = self._client.format_url(request.url, **path_format_arguments)  # type: ignore
 
         pipeline_response = await self._client._pipeline.run(  # type: ignore # pylint: disable=protected-access
             request, stream=False, **kwargs
         )
         response = pipeline_response.http_response
 
-        if response.status_code not in [200]:
+        if response.status_code not in [200, 200]:
             map_error(status_code=response.status_code, response=response, error_map=error_map)
             error = self._deserialize.failsafe_deserialize(_models.RequestError, pipeline_response)
             raise HttpResponseError(response=response, model=error)
 
-        deserialized = self._deserialize("Document", pipeline_response)
+        if response.status_code == 200:
+            deserialized = self._deserialize("Document", pipeline_response)
+
+        if response.status_code == 200:
+            deserialized = self._deserialize("Document", pipeline_response)
 
         if cls:
             return cls(pipeline_response, deserialized, {})
 
         return deserialized
 
     get_document.metadata = {"url": "/v3/documents/{identifier}"}  # type: ignore
```

### Comparing `affinda-4.7.0/affinda/aio/operations/_patch.py` & `affinda-4.7.1/affinda/aio/operations/_patch.py`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda/models/__init__.py` & `affinda-4.7.1/affinda/models/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 try:
     from ._models_py3 import Accreditation
     from ._models_py3 import Annotation
     from ._models_py3 import AnnotationBase
```

### Comparing `affinda-4.7.0/affinda/models/_affinda_api_enums.py` & `affinda-4.7.1/affinda/models/_affinda_api_enums.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from enum import Enum
 from azure.core import CaseInsensitiveEnumMeta
```

### Comparing `affinda-4.7.0/affinda/models/_models.py` & `affinda-4.7.1/affinda/models/_models.py`

 * *Files 0% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 00000030: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 00000040: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 00000050: 2d2d 2d2d 2d2d 2d2d 2d2d 2d0a 2320 436f  -----------.# Co
 00000060: 6465 2067 656e 6572 6174 6564 2062 7920  de generated by 
 00000070: 4d69 6372 6f73 6f66 7420 2852 2920 4175  Microsoft (R) Au
 00000080: 746f 5265 7374 2043 6f64 6520 4765 6e65  toRest Code Gene
 00000090: 7261 746f 7220 2861 7574 6f72 6573 743a  rator (autorest:
-000000a0: 2033 2e39 2e35 2c20 6765 6e65 7261 746f   3.9.5, generato
+000000a0: 2033 2e39 2e36 2c20 6765 6e65 7261 746f   3.9.6, generato
 000000b0: 723a 2040 6175 746f 7265 7374 2f70 7974  r: @autorest/pyt
 000000c0: 686f 6e40 352e 3136 2e30 290a 2320 4368  hon@5.16.0).# Ch
 000000d0: 616e 6765 7320 6d61 7920 6361 7573 6520  anges may cause 
 000000e0: 696e 636f 7272 6563 7420 6265 6861 7669  incorrect behavi
 000000f0: 6f72 2061 6e64 2077 696c 6c20 6265 206c  or and will be l
 00000100: 6f73 7420 6966 2074 6865 2063 6f64 6520  ost if the code 
 00000110: 6973 2072 6567 656e 6572 6174 6564 2e0a  is regenerated..
```

### Comparing `affinda-4.7.0/affinda/models/_models_py3.py` & `affinda-4.7.1/affinda/models/_models_py3.py`

 * *Files 0% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 00000030: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 00000040: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 00000050: 2d2d 2d2d 2d2d 2d2d 2d2d 2d0a 2320 436f  -----------.# Co
 00000060: 6465 2067 656e 6572 6174 6564 2062 7920  de generated by 
 00000070: 4d69 6372 6f73 6f66 7420 2852 2920 4175  Microsoft (R) Au
 00000080: 746f 5265 7374 2043 6f64 6520 4765 6e65  toRest Code Gene
 00000090: 7261 746f 7220 2861 7574 6f72 6573 743a  rator (autorest:
-000000a0: 2033 2e39 2e35 2c20 6765 6e65 7261 746f   3.9.5, generato
+000000a0: 2033 2e39 2e36 2c20 6765 6e65 7261 746f   3.9.6, generato
 000000b0: 723a 2040 6175 746f 7265 7374 2f70 7974  r: @autorest/pyt
 000000c0: 686f 6e40 352e 3136 2e30 290a 2320 4368  hon@5.16.0).# Ch
 000000d0: 616e 6765 7320 6d61 7920 6361 7573 6520  anges may cause 
 000000e0: 696e 636f 7272 6563 7420 6265 6861 7669  incorrect behavi
 000000f0: 6f72 2061 6e64 2077 696c 6c20 6265 206c  or and will be l
 00000100: 6f73 7420 6966 2074 6865 2063 6f64 6520  ost if the code 
 00000110: 6973 2072 6567 656e 6572 6174 6564 2e0a  is regenerated..
```

### Comparing `affinda-4.7.0/affinda/models/_patch.py` & `affinda-4.7.1/affinda/models/_patch.py`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda/operations/__init__.py` & `affinda-4.7.1/affinda/operations/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 
 from ._affinda_api_operations import AffindaAPIOperationsMixin
 
 from ._patch import __all__ as _patch_all
 from ._patch import *  # type: ignore # pylint: disable=unused-wildcard-import
```

### Comparing `affinda-4.7.0/affinda/operations/_affinda_api_operations.py` & `affinda-4.7.1/affinda/operations/_affinda_api_operations.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 # pylint: disable=too-many-lines
 # coding=utf-8
 # --------------------------------------------------------------------------
-# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.5, generator: @autorest/python@5.16.0)
+# Code generated by Microsoft (R) AutoRest Code Generator (autorest: 3.9.6, generator: @autorest/python@5.16.0)
 # Changes may cause incorrect behavior and will be lost if the code is regenerated.
 # --------------------------------------------------------------------------
 import datetime
 from typing import TYPE_CHECKING
 
 from msrest import Serializer
 
@@ -4357,20 +4357,24 @@
         request.url = self._client.format_url(request.url, **path_format_arguments)  # type: ignore
 
         pipeline_response = self._client._pipeline.run(  # type: ignore # pylint: disable=protected-access
             request, stream=False, **kwargs
         )
         response = pipeline_response.http_response
 
-        if response.status_code not in [200]:
+        if response.status_code not in [200, 200]:
             map_error(status_code=response.status_code, response=response, error_map=error_map)
             error = self._deserialize.failsafe_deserialize(_models.RequestError, pipeline_response)
             raise HttpResponseError(response=response, model=error)
 
-        deserialized = self._deserialize("Document", pipeline_response)
+        if response.status_code == 200:
+            deserialized = self._deserialize("Document", pipeline_response)
+
+        if response.status_code == 200:
+            deserialized = self._deserialize("Document", pipeline_response)
 
         if cls:
             return cls(pipeline_response, deserialized, {})
 
         return deserialized
 
     get_document.metadata = {"url": "/v3/documents/{identifier}"}  # type: ignore
```

### Comparing `affinda-4.7.0/affinda/operations/_patch.py` & `affinda-4.7.1/affinda/operations/_patch.py`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda.egg-info/PKG-INFO` & `affinda-4.7.1/affinda.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: affinda
-Version: 4.7.0
+Version: 4.7.1
 Summary: Client library for the Affinda API
 Home-page: https://github.com/affinda/affinda-python
 Author: Affinda
 Author-email: contact@affinda.com
 Maintainer: Affinda
 Maintainer-email: contact@affinda.com
 License: MIT
@@ -124,14 +124,18 @@
 All notable changes to this project will be documented in this file.
 
 The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
 and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
 
 ## [Unreleased]
 
+## [4.7.1] - 2023-06-28
+### Added
+- Add xml response to api spec to GET /v3/documenets to match existing functionality
+
 ## [4.7.0] - 2023-06-27
 ### Added
 - Allow create/update data point's `parent` and `displayEnumValue` property
 - Allow explicitly set a document as low_priority
 
 ### Changed
 - Make `slug` and `organization` required when creating data point
```

### Comparing `affinda-4.7.0/affinda.egg-info/SOURCES.txt` & `affinda-4.7.1/affinda.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/affinda_logo.png` & `affinda-4.7.1/affinda_logo.png`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/docs/models.md` & `affinda-4.7.1/docs/models.md`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/docs/samples_python.md` & `affinda-4.7.1/docs/samples_python.md`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/docs/sync_operations.md` & `affinda-4.7.1/docs/sync_operations.md`

 * *Files identical despite different names*

### Comparing `affinda-4.7.0/setup.cfg` & `affinda-4.7.1/setup.cfg`

 * *Files identical despite different names*

