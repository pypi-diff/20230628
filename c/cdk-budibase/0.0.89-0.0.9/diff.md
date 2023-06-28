# Comparing `tmp/cdk-budibase-0.0.89.tar.gz` & `tmp/cdk-budibase-0.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cdk-budibase-0.0.89.tar", last modified: Wed Jun 28 00:21:27 2023, max compression
+gzip compressed data, was "cdk-budibase-0.0.9.tar", last modified: Fri Apr  7 09:24:03 2023, max compression
```

## Comparing `cdk-budibase-0.0.89.tar` & `cdk-budibase-0.0.9.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:21:27.675114 cdk-budibase-0.0.89/
--rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     2977 2023-06-28 00:21:27.675114 cdk-budibase-0.0.89/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2052 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      234 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 00:21:27.675114 cdk-budibase-0.0.89/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1759 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:21:27.675114 cdk-budibase-0.0.89/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:21:27.675114 cdk-budibase-0.0.89/src/cdk_budibase/
--rw-r--r--   0 runner    (1001) docker     (123)     4739 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/src/cdk_budibase/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:21:27.675114 cdk-budibase-0.0.89/src/cdk_budibase/_jsii/
--rw-r--r--   0 runner    (1001) docker     (123)      393 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/src/cdk_budibase/_jsii/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)   486660 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/src/cdk_budibase/_jsii/cdk-budibase@0.0.89.jsii.tgz
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:21:11.000000 cdk-budibase-0.0.89/src/cdk_budibase/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:21:27.675114 cdk-budibase-0.0.89/src/cdk_budibase.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2977 2023-06-28 00:21:27.000000 cdk-budibase-0.0.89/src/cdk_budibase.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      394 2023-06-28 00:21:27.000000 cdk-budibase-0.0.89/src/cdk_budibase.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:21:27.000000 cdk-budibase-0.0.89/src/cdk_budibase.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      111 2023-06-28 00:21:27.000000 cdk-budibase-0.0.89/src/cdk_budibase.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 00:21:27.000000 cdk-budibase-0.0.89/src/cdk_budibase.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-07 09:24:03.854759 cdk-budibase-0.0.9/
+-rw-r--r--   0 runner    (1001) docker     (123)    11358 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     2976 2023-04-07 09:24:03.854759 cdk-budibase-0.0.9/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2052 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      234 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-07 09:24:03.854759 cdk-budibase-0.0.9/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1757 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-07 09:24:03.854759 cdk-budibase-0.0.9/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-07 09:24:03.854759 cdk-budibase-0.0.9/src/cdk_budibase/
+-rw-r--r--   0 runner    (1001) docker     (123)     4739 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/src/cdk_budibase/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-07 09:24:03.854759 cdk-budibase-0.0.9/src/cdk_budibase/_jsii/
+-rw-r--r--   0 runner    (1001) docker     (123)      391 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/src/cdk_budibase/_jsii/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   487214 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/src/cdk_budibase/_jsii/cdk-budibase@0.0.9.jsii.tgz
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-07 09:23:52.000000 cdk-budibase-0.0.9/src/cdk_budibase/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-07 09:24:03.854759 cdk-budibase-0.0.9/src/cdk_budibase.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2976 2023-04-07 09:24:03.000000 cdk-budibase-0.0.9/src/cdk_budibase.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      393 2023-04-07 09:24:03.000000 cdk-budibase-0.0.9/src/cdk_budibase.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-07 09:24:03.000000 cdk-budibase-0.0.9/src/cdk_budibase.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      111 2023-04-07 09:24:03.000000 cdk-budibase-0.0.9/src/cdk_budibase.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-04-07 09:24:03.000000 cdk-budibase-0.0.9/src/cdk_budibase.egg-info/top_level.txt
```

### Comparing `cdk-budibase-0.0.89/LICENSE` & `cdk-budibase-0.0.9/LICENSE`

 * *Files identical despite different names*

### Comparing `cdk-budibase-0.0.89/PKG-INFO` & `cdk-budibase-0.0.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cdk-budibase
-Version: 0.0.89
+Version: 0.0.9
 Summary: Use AWS CDK to create budibase server
 Home-page: https://github.com/neilkuan/cdk-budibase.git
 Author: Neil Kuan<guan840912@gmail.com>
 License: Apache-2.0
 Project-URL: Source, https://github.com/neilkuan/cdk-budibase.git
 Classifier: Intended Audience :: Developers
 Classifier: Operating System :: OS Independent
```

### Comparing `cdk-budibase-0.0.89/README.md` & `cdk-budibase-0.0.9/README.md`

 * *Files identical despite different names*

### Comparing `cdk-budibase-0.0.89/setup.py` & `cdk-budibase-0.0.9/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import json
 import setuptools
 
 kwargs = json.loads(
     """
 {
     "name": "cdk-budibase",
-    "version": "0.0.89",
+    "version": "0.0.9",
     "description": "Use AWS CDK to create budibase server",
     "license": "Apache-2.0",
     "url": "https://github.com/neilkuan/cdk-budibase.git",
     "long_description_content_type": "text/markdown",
     "author": "Neil Kuan<guan840912@gmail.com>",
     "bdist_wheel": {
         "universal": true
@@ -22,25 +22,25 @@
     },
     "packages": [
         "cdk_budibase",
         "cdk_budibase._jsii"
     ],
     "package_data": {
         "cdk_budibase._jsii": [
-            "cdk-budibase@0.0.89.jsii.tgz"
+            "cdk-budibase@0.0.9.jsii.tgz"
         ],
         "cdk_budibase": [
             "py.typed"
         ]
     },
     "python_requires": "~=3.7",
     "install_requires": [
         "aws-cdk-lib>=2.63.0, <3.0.0",
         "constructs>=10.0.5, <11.0.0",
-        "jsii>=1.84.0, <2.0.0",
+        "jsii>=1.80.0, <2.0.0",
         "publication>=0.0.3",
         "typeguard~=2.13.3"
     ],
     "classifiers": [
         "Intended Audience :: Developers",
         "Operating System :: OS Independent",
         "Programming Language :: JavaScript",
```

### Comparing `cdk-budibase-0.0.89/src/cdk_budibase/__init__.py` & `cdk-budibase-0.0.9/src/cdk_budibase/__init__.py`

 * *Files identical despite different names*

### Comparing `cdk-budibase-0.0.89/src/cdk_budibase.egg-info/PKG-INFO` & `cdk-budibase-0.0.9/src/cdk_budibase.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cdk-budibase
-Version: 0.0.89
+Version: 0.0.9
 Summary: Use AWS CDK to create budibase server
 Home-page: https://github.com/neilkuan/cdk-budibase.git
 Author: Neil Kuan<guan840912@gmail.com>
 License: Apache-2.0
 Project-URL: Source, https://github.com/neilkuan/cdk-budibase.git
 Classifier: Intended Audience :: Developers
 Classifier: Operating System :: OS Independent
```

