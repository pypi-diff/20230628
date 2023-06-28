# Comparing `tmp/szh_toolbox-0.0.1.tar.gz` & `tmp/szh_toolbox-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "szh_toolbox-0.0.1.tar", last modified: Wed Jun 28 08:10:15 2023, max compression
+gzip compressed data, was "szh_toolbox-0.0.2.tar", last modified: Wed Jun 28 08:29:16 2023, max compression
```

## Comparing `szh_toolbox-0.0.1.tar` & `szh_toolbox-0.0.2.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/
--rw-rw-r--   0 szh       (1003) szh       (1003)     1073 2023-06-28 08:01:22.000000 szh_toolbox-0.0.1/LICENSE
--rw-rw-r--   0 szh       (1003) szh       (1003)      501 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/PKG-INFO
--rw-rw-r--   0 szh       (1003) szh       (1003)        0 2023-06-28 07:20:32.000000 szh_toolbox-0.0.1/README.md
--rw-rw-r--   0 szh       (1003) szh       (1003)      573 2023-06-28 08:09:45.000000 szh_toolbox-0.0.1/pyproject.toml
--rw-rw-r--   0 szh       (1003) szh       (1003)       38 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/setup.cfg
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.277653 szh_toolbox-0.0.1/src/
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.277653 szh_toolbox-0.0.1/src/szh_toolbox/
--rw-rw-r--   0 szh       (1003) szh       (1003)       67 2023-06-28 07:17:28.000000 szh_toolbox-0.0.1/src/szh_toolbox/__init__.py
--rw-rw-r--   0 szh       (1003) szh       (1003)       67 2023-06-28 07:18:07.000000 szh_toolbox-0.0.1/src/szh_toolbox/test.py
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/
--rw-rw-r--   0 szh       (1003) szh       (1003)      501 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/PKG-INFO
--rw-rw-r--   0 szh       (1003) szh       (1003)      240 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/SOURCES.txt
--rw-rw-r--   0 szh       (1003) szh       (1003)        1 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/dependency_links.txt
--rw-rw-r--   0 szh       (1003) szh       (1003)       12 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/top_level.txt
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:29:16.870921 szh_toolbox-0.0.2/
+-rw-rw-r--   0 szh       (1003) szh       (1003)     1073 2023-06-28 08:01:22.000000 szh_toolbox-0.0.2/LICENSE
+-rw-rw-r--   0 szh       (1003) szh       (1003)      501 2023-06-28 08:29:16.870921 szh_toolbox-0.0.2/PKG-INFO
+-rw-rw-r--   0 szh       (1003) szh       (1003)        0 2023-06-28 07:20:32.000000 szh_toolbox-0.0.2/README.md
+-rw-rw-r--   0 szh       (1003) szh       (1003)      573 2023-06-28 08:22:30.000000 szh_toolbox-0.0.2/pyproject.toml
+-rw-rw-r--   0 szh       (1003) szh       (1003)       38 2023-06-28 08:29:16.870921 szh_toolbox-0.0.2/setup.cfg
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:29:16.868921 szh_toolbox-0.0.2/src/
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:29:16.869921 szh_toolbox-0.0.2/src/szh_toolbox/
+-rw-rw-r--   0 szh       (1003) szh       (1003)     1862 2023-06-28 08:22:02.000000 szh_toolbox-0.0.2/src/szh_toolbox/__init__.py
+-rw-rw-r--   0 szh       (1003) szh       (1003)       67 2023-06-28 07:18:07.000000 szh_toolbox-0.0.2/src/szh_toolbox/test.py
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:29:16.869921 szh_toolbox-0.0.2/src/szh_toolbox.egg-info/
+-rw-rw-r--   0 szh       (1003) szh       (1003)      501 2023-06-28 08:29:16.000000 szh_toolbox-0.0.2/src/szh_toolbox.egg-info/PKG-INFO
+-rw-rw-r--   0 szh       (1003) szh       (1003)      240 2023-06-28 08:29:16.000000 szh_toolbox-0.0.2/src/szh_toolbox.egg-info/SOURCES.txt
+-rw-rw-r--   0 szh       (1003) szh       (1003)        1 2023-06-28 08:29:16.000000 szh_toolbox-0.0.2/src/szh_toolbox.egg-info/dependency_links.txt
+-rw-rw-r--   0 szh       (1003) szh       (1003)       12 2023-06-28 08:29:16.000000 szh_toolbox-0.0.2/src/szh_toolbox.egg-info/top_level.txt
```

### Comparing `szh_toolbox-0.0.1/LICENSE` & `szh_toolbox-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `szh_toolbox-0.0.1/pyproject.toml` & `szh_toolbox-0.0.2/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=42"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "szh_toolbox"
-version = "0.0.1"
+version = "0.0.2"
 authors = [
   { name="Example Author", email="author@example.com" },
 ]
 description = "A small example package"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

