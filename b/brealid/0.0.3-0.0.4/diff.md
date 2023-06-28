# Comparing `tmp/brealid-0.0.3.tar.gz` & `tmp/brealid-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "brealid-0.0.3.tar", last modified: Wed Jun 28 15:01:40 2023, max compression
+gzip compressed data, was "brealid-0.0.4.tar", last modified: Wed Jun 28 15:21:46 2023, max compression
```

## Comparing `brealid-0.0.3.tar` & `brealid-0.0.4.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/
--rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-06-28 15:01:24.000000 brealid-0.0.3/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      913 2023-06-28 15:01:40.737136 brealid-0.0.3/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      483 2023-06-28 15:01:24.000000 brealid-0.0.3/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid/
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid/ctf/
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/ctf/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid/ctf/crypto/
--rw-r--r--   0 runner    (1001) docker     (123)     3780 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/ctf/crypto/GaloisNumber_2n.py
--rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/ctf/crypto/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      913 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      308 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-28 15:01:24.000000 brealid-0.0.3/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:01:40.737136 brealid-0.0.3/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      778 2023-06-28 15:01:24.000000 brealid-0.0.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:46.402645 brealid-0.0.4/
+-rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-06-28 15:21:36.000000 brealid-0.0.4/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      913 2023-06-28 15:21:46.402645 brealid-0.0.4/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      483 2023-06-28 15:21:36.000000 brealid-0.0.4/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:46.402645 brealid-0.0.4/brealid/
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 15:21:36.000000 brealid-0.0.4/brealid/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:46.402645 brealid-0.0.4/brealid/ctf/
+-rw-r--r--   0 runner    (1001) docker     (123)      356 2023-06-28 15:21:36.000000 brealid-0.0.4/brealid/ctf/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:46.402645 brealid-0.0.4/brealid/ctf/crypto/
+-rw-r--r--   0 runner    (1001) docker     (123)     3780 2023-06-28 15:21:36.000000 brealid-0.0.4/brealid/ctf/crypto/GaloisNumber_2n.py
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 15:21:36.000000 brealid-0.0.4/brealid/ctf/crypto/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:46.402645 brealid-0.0.4/brealid.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      913 2023-06-28 15:21:46.000000 brealid-0.0.4/brealid.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      308 2023-06-28 15:21:46.000000 brealid-0.0.4/brealid.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:21:46.000000 brealid-0.0.4/brealid.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:21:46.000000 brealid-0.0.4/brealid.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 15:21:46.000000 brealid-0.0.4/brealid.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-28 15:21:36.000000 brealid-0.0.4/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:21:46.402645 brealid-0.0.4/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      752 2023-06-28 15:21:36.000000 brealid-0.0.4/setup.py
```

### Comparing `brealid-0.0.3/LICENSE` & `brealid-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `brealid-0.0.3/PKG-INFO` & `brealid-0.0.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: brealid
-Version: 0.0.3
+Version: 0.0.4
 Summary: brealid's python package
 Home-page: https://github.com/brealid/brealid-python-lib
 Author: brealid
 Author-email: brealid@mail.ustc.edu.cn
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `brealid-0.0.3/brealid/ctf/crypto/GaloisNumber_2n.py` & `brealid-0.0.4/brealid/ctf/crypto/GaloisNumber_2n.py`

 * *Files identical despite different names*

### Comparing `brealid-0.0.3/brealid.egg-info/PKG-INFO` & `brealid-0.0.4/brealid.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: brealid
-Version: 0.0.3
+Version: 0.0.4
 Summary: brealid's python package
 Home-page: https://github.com/brealid/brealid-python-lib
 Author: brealid
 Author-email: brealid@mail.ustc.edu.cn
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `brealid-0.0.3/setup.py` & `brealid-0.0.4/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="brealid",
-    version="v0.0.3",
+    version="v0.0.4",
     author="brealid",
     author_email="brealid@mail.ustc.edu.cn",
     description="brealid's python package",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/brealid/brealid-python-lib",
     classifiers=[
@@ -18,10 +18,9 @@
         "Operating System :: OS Independent",
     ],
     packages=setuptools.find_packages(),
     python_requires='>=3.6',
     install_requires=[
         "pycryptodome>=3.15.0",
         "requests>=2.24.0",
-        "pwntools>=4.8.0"
     ]
 )
```

