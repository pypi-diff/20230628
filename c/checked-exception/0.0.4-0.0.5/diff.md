# Comparing `tmp/checked-exception-0.0.4.tar.gz` & `tmp/checked-exception-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "checked-exception-0.0.4.tar", last modified: Thu Jan 26 15:33:45 2023, max compression
+gzip compressed data, was "checked-exception-0.0.5.tar", last modified: Wed Jun 28 09:00:48 2023, max compression
```

## Comparing `checked-exception-0.0.4.tar` & `checked-exception-0.0.5.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-01-26 15:33:45.203230 checked-exception-0.0.4/
--rw-r--r--   0 j3ymac     (501) staff       (20)     1066 2023-01-26 14:54:10.000000 checked-exception-0.0.4/LICENSE
--rw-r--r--   0 j3ymac     (501) staff       (20)     1047 2023-01-26 15:33:45.203112 checked-exception-0.0.4/PKG-INFO
--rw-r--r--   0 j3ymac     (501) staff       (20)      560 2023-01-26 15:31:50.000000 checked-exception-0.0.4/README.md
-drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-01-26 15:33:45.202563 checked-exception-0.0.4/checked_exception/
--rw-r--r--   0 j3ymac     (501) staff       (20)       83 2023-01-26 15:27:16.000000 checked-exception-0.0.4/checked_exception/__init__.py
-drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-01-26 15:33:45.202974 checked-exception-0.0.4/checked_exception.egg-info/
--rw-r--r--   0 j3ymac     (501) staff       (20)     1047 2023-01-26 15:33:45.000000 checked-exception-0.0.4/checked_exception.egg-info/PKG-INFO
--rw-r--r--   0 j3ymac     (501) staff       (20)      220 2023-01-26 15:33:45.000000 checked-exception-0.0.4/checked_exception.egg-info/SOURCES.txt
--rw-r--r--   0 j3ymac     (501) staff       (20)        1 2023-01-26 15:33:45.000000 checked-exception-0.0.4/checked_exception.egg-info/dependency_links.txt
--rw-r--r--   0 j3ymac     (501) staff       (20)       18 2023-01-26 15:33:45.000000 checked-exception-0.0.4/checked_exception.egg-info/top_level.txt
--rw-r--r--   0 j3ymac     (501) staff       (20)       38 2023-01-26 15:33:45.203265 checked-exception-0.0.4/setup.cfg
--rw-r--r--   0 j3ymac     (501) staff       (20)      677 2023-01-26 15:26:27.000000 checked-exception-0.0.4/setup.py
+drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:00:48.334514 checked-exception-0.0.5/
+-rw-r--r--   0 j3ymac     (501) staff       (20)     1066 2023-06-28 08:42:14.000000 checked-exception-0.0.5/LICENSE
+-rw-r--r--   0 j3ymac     (501) staff       (20)     1477 2023-06-28 09:00:48.334368 checked-exception-0.0.5/PKG-INFO
+-rw-r--r--   0 j3ymac     (501) staff       (20)      990 2023-06-28 09:00:35.000000 checked-exception-0.0.5/README.md
+drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:00:48.333429 checked-exception-0.0.5/checked_exception/
+-rw-r--r--   0 j3ymac     (501) staff       (20)       83 2023-06-28 08:42:14.000000 checked-exception-0.0.5/checked_exception/__init__.py
+drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:00:48.334141 checked-exception-0.0.5/checked_exception.egg-info/
+-rw-r--r--   0 j3ymac     (501) staff       (20)     1477 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/PKG-INFO
+-rw-r--r--   0 j3ymac     (501) staff       (20)      220 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/SOURCES.txt
+-rw-r--r--   0 j3ymac     (501) staff       (20)        1 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/dependency_links.txt
+-rw-r--r--   0 j3ymac     (501) staff       (20)       18 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/top_level.txt
+-rw-r--r--   0 j3ymac     (501) staff       (20)       38 2023-06-28 09:00:48.334565 checked-exception-0.0.5/setup.cfg
+-rw-r--r--   0 j3ymac     (501) staff       (20)      677 2023-06-28 08:57:23.000000 checked-exception-0.0.5/setup.py
```

### Comparing `checked-exception-0.0.4/LICENSE` & `checked-exception-0.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `checked-exception-0.0.4/setup.py` & `checked-exception-0.0.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", encoding="utf-8") as f:
     long_description = f.read()
 
 setuptools.setup(
     name="checked-exception",
-    version="0.0.4",
+    version="0.0.5",
     author="thejimmylin",
     author_email="b00502013@gmail.com",
     description="Use checked exceptions in Python.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/thejimmylin/checked-exception",
     packages=setuptools.find_packages(),
```

