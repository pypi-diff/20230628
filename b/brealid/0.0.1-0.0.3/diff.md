# Comparing `tmp/brealid-0.0.1.tar.gz` & `tmp/brealid-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "brealid-0.0.1.tar", last modified: Wed Jun 28 14:12:42 2023, max compression
+gzip compressed data, was "brealid-0.0.3.tar", last modified: Wed Jun 28 15:01:40 2023, max compression
```

## Comparing `brealid-0.0.1.tar` & `brealid-0.0.3.tar`

### file list

```diff
@@ -1,17 +1,20 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:12:42.835478 brealid-0.0.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-06-28 14:12:33.000000 brealid-0.0.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      474 2023-06-28 14:12:42.835478 brealid-0.0.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-28 14:12:33.000000 brealid-0.0.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:12:42.835478 brealid-0.0.1/brealid/
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 14:12:33.000000 brealid-0.0.1/brealid/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:12:42.835478 brealid-0.0.1/brealid/ctf/
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 14:12:33.000000 brealid-0.0.1/brealid/ctf/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:12:42.835478 brealid-0.0.1/brealid.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      474 2023-06-28 14:12:42.000000 brealid-0.0.1/brealid.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      239 2023-06-28 14:12:42.000000 brealid-0.0.1/brealid.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:12:42.000000 brealid-0.0.1/brealid.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-28 14:12:42.000000 brealid-0.0.1/brealid.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 14:12:42.000000 brealid-0.0.1/brealid.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-28 14:12:33.000000 brealid-0.0.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:12:42.835478 brealid-0.0.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      777 2023-06-28 14:12:33.000000 brealid-0.0.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-06-28 15:01:24.000000 brealid-0.0.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      913 2023-06-28 15:01:40.737136 brealid-0.0.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      483 2023-06-28 15:01:24.000000 brealid-0.0.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid/
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid/ctf/
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/ctf/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid/ctf/crypto/
+-rw-r--r--   0 runner    (1001) docker     (123)     3780 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/ctf/crypto/GaloisNumber_2n.py
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 15:01:24.000000 brealid-0.0.3/brealid/ctf/crypto/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:40.737136 brealid-0.0.3/brealid.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      913 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      308 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       54 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 15:01:40.000000 brealid-0.0.3/brealid.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-28 15:01:24.000000 brealid-0.0.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:01:40.737136 brealid-0.0.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      778 2023-06-28 15:01:24.000000 brealid-0.0.3/setup.py
```

### Comparing `brealid-0.0.1/LICENSE` & `brealid-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `brealid-0.0.1/setup.py` & `brealid-0.0.3/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="brealid",
-    version="0.0.1",
+    version="v0.0.3",
     author="brealid",
     author_email="brealid@mail.ustc.edu.cn",
     description="brealid's python package",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/brealid/brealid-python-lib",
     classifiers=[
```

