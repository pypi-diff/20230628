# Comparing `tmp/checked-exception-0.0.5.tar.gz` & `tmp/checked-exception-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "checked-exception-0.0.5.tar", last modified: Wed Jun 28 09:00:48 2023, max compression
+gzip compressed data, was "checked-exception-0.0.6.tar", last modified: Wed Jun 28 09:08:29 2023, max compression
```

## Comparing `checked-exception-0.0.5.tar` & `checked-exception-0.0.6.tar`

### file list

```diff
@@ -1,13 +1,13 @@
-drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:00:48.334514 checked-exception-0.0.5/
--rw-r--r--   0 j3ymac     (501) staff       (20)     1066 2023-06-28 08:42:14.000000 checked-exception-0.0.5/LICENSE
--rw-r--r--   0 j3ymac     (501) staff       (20)     1477 2023-06-28 09:00:48.334368 checked-exception-0.0.5/PKG-INFO
--rw-r--r--   0 j3ymac     (501) staff       (20)      990 2023-06-28 09:00:35.000000 checked-exception-0.0.5/README.md
-drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:00:48.333429 checked-exception-0.0.5/checked_exception/
--rw-r--r--   0 j3ymac     (501) staff       (20)       83 2023-06-28 08:42:14.000000 checked-exception-0.0.5/checked_exception/__init__.py
-drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:00:48.334141 checked-exception-0.0.5/checked_exception.egg-info/
--rw-r--r--   0 j3ymac     (501) staff       (20)     1477 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/PKG-INFO
--rw-r--r--   0 j3ymac     (501) staff       (20)      220 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/SOURCES.txt
--rw-r--r--   0 j3ymac     (501) staff       (20)        1 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/dependency_links.txt
--rw-r--r--   0 j3ymac     (501) staff       (20)       18 2023-06-28 09:00:48.000000 checked-exception-0.0.5/checked_exception.egg-info/top_level.txt
--rw-r--r--   0 j3ymac     (501) staff       (20)       38 2023-06-28 09:00:48.334565 checked-exception-0.0.5/setup.cfg
--rw-r--r--   0 j3ymac     (501) staff       (20)      677 2023-06-28 08:57:23.000000 checked-exception-0.0.5/setup.py
+drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:08:29.129372 checked-exception-0.0.6/
+-rw-r--r--   0 j3ymac     (501) staff       (20)     1066 2023-06-28 08:42:14.000000 checked-exception-0.0.6/LICENSE
+-rw-r--r--   0 j3ymac     (501) staff       (20)      581 2023-06-28 09:08:29.129243 checked-exception-0.0.6/PKG-INFO
+-rw-r--r--   0 j3ymac     (501) staff       (20)     1077 2023-06-28 09:02:48.000000 checked-exception-0.0.6/README.md
+drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:08:29.128478 checked-exception-0.0.6/checked_exception/
+-rw-r--r--   0 j3ymac     (501) staff       (20)       83 2023-06-28 08:42:14.000000 checked-exception-0.0.6/checked_exception/__init__.py
+drwxr-xr-x   0 j3ymac     (501) staff       (20)        0 2023-06-28 09:08:29.129088 checked-exception-0.0.6/checked_exception.egg-info/
+-rw-r--r--   0 j3ymac     (501) staff       (20)      581 2023-06-28 09:08:29.000000 checked-exception-0.0.6/checked_exception.egg-info/PKG-INFO
+-rw-r--r--   0 j3ymac     (501) staff       (20)      220 2023-06-28 09:08:29.000000 checked-exception-0.0.6/checked_exception.egg-info/SOURCES.txt
+-rw-r--r--   0 j3ymac     (501) staff       (20)        1 2023-06-28 09:08:29.000000 checked-exception-0.0.6/checked_exception.egg-info/dependency_links.txt
+-rw-r--r--   0 j3ymac     (501) staff       (20)       18 2023-06-28 09:08:29.000000 checked-exception-0.0.6/checked_exception.egg-info/top_level.txt
+-rw-r--r--   0 j3ymac     (501) staff       (20)       38 2023-06-28 09:08:29.129411 checked-exception-0.0.6/setup.cfg
+-rw-r--r--   0 j3ymac     (501) staff       (20)      719 2023-06-28 09:07:55.000000 checked-exception-0.0.6/setup.py
```

### Comparing `checked-exception-0.0.5/LICENSE` & `checked-exception-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `checked-exception-0.0.5/README.md` & `checked-exception-0.0.6/README.md`

 * *Files 26% similar despite different names*

```diff
@@ -1,14 +1,16 @@
 # Checked Exception
 
 This is a checked exception library, which tries to implement checked exceptions in Python.
 
 ## Install building tools
-Before publishing, you need to install some tools.
+Before publishing, you need to setup a virtual Python environment and install some tools.
 ```
+python3 -m venv .venv
+source .venv/bin/activate
 pip install wheel twine
 ```
 
 ## Publish to test.pypi.org (for testing purpose)
 This makes you test your package before actually publishing it.
 
 ```python
```

### Comparing `checked-exception-0.0.5/setup.py` & `checked-exception-0.0.6/setup.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,19 +1,21 @@
 import setuptools
 
-with open("README.md", encoding="utf-8") as f:
-    long_description = f.read()
 
 setuptools.setup(
     name="checked-exception",
-    version="0.0.5",
+    version="0.0.6",
     author="thejimmylin",
     author_email="b00502013@gmail.com",
     description="Use checked exceptions in Python.",
-    long_description=long_description,
+    long_description=(
+        "# Use checked exceptions in Python.\n"
+        "\n"
+        "This package makes you use checked exceptions in Python.\n"
+    ),
     long_description_content_type="text/markdown",
     url="https://github.com/thejimmylin/checked-exception",
     packages=setuptools.find_packages(),
     classifiers=[
         "Programming Language :: Python :: 3",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent",
```

