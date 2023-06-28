# Comparing `tmp/angola-0.14.2.tar.gz` & `tmp/angola-0.14.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "angola-0.14.2.tar", last modified: Wed Jun 28 00:52:57 2023, max compression
+gzip compressed data, was "angola-0.14.3.tar", last modified: Wed Jun 28 00:53:32 2023, max compression
```

## Comparing `angola-0.14.2.tar` & `angola-0.14.3.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:52:57.381110 angola-0.14.2/
--rw-r--r--   0 mardix     (501) staff       (20)     1084 2023-03-21 05:31:22.000000 angola-0.14.2/LICENSE
--rw-r--r--   0 mardix     (501) staff       (20)       26 2022-11-28 18:23:44.000000 angola-0.14.2/MANIFEST.in
--rw-r--r--   0 mardix     (501) staff       (20)     1318 2023-06-28 00:52:57.381180 angola-0.14.2/PKG-INFO
--rw-r--r--   0 mardix     (501) staff       (20)      938 2023-06-09 03:27:48.000000 angola-0.14.2/README.md
--rw-r--r--   0 mardix     (501) staff       (20)       79 2023-06-28 00:52:57.381442 angola-0.14.2/setup.cfg
--rw-r--r--   0 mardix     (501) staff       (20)      793 2023-06-28 00:52:45.000000 angola-0.14.2/setup.py
-drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:52:57.374595 angola-0.14.2/src/
-drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:52:57.378326 angola-0.14.2/src/angola/
--rw-r--r--   0 mardix     (501) staff       (20)      428 2023-06-09 03:27:14.000000 angola-0.14.2/src/angola/__init__.py
--rw-r--r--   0 mardix     (501) staff       (20)    50979 2023-06-23 08:06:55.000000 angola-0.14.2/src/angola/database.py
--rw-r--r--   0 mardix     (501) staff       (20)    12956 2023-06-03 04:28:39.000000 angola-0.14.2/src/angola/dict_mutator.py
--rw-r--r--   0 mardix     (501) staff       (20)    18847 2023-02-21 03:11:29.000000 angola-0.14.2/src/angola/dict_query.py
--rw-r--r--   0 mardix     (501) staff       (20)    18669 2023-06-28 00:51:03.000000 angola-0.14.2/src/angola/lib.py
--rw-r--r--   0 mardix     (501) staff       (20)    20084 2023-06-23 04:30:25.000000 angola-0.14.2/src/angola/lib_xql.py
-drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:52:57.379541 angola-0.14.2/src/angola.egg-info/
--rw-r--r--   0 mardix     (501) staff       (20)     1318 2023-06-28 00:52:57.000000 angola-0.14.2/src/angola.egg-info/PKG-INFO
--rw-r--r--   0 mardix     (501) staff       (20)      464 2023-06-28 00:52:57.000000 angola-0.14.2/src/angola.egg-info/SOURCES.txt
--rw-r--r--   0 mardix     (501) staff       (20)        1 2023-06-28 00:52:57.000000 angola-0.14.2/src/angola.egg-info/dependency_links.txt
--rw-r--r--   0 mardix     (501) staff       (20)       53 2023-06-28 00:52:57.000000 angola-0.14.2/src/angola.egg-info/requires.txt
--rw-r--r--   0 mardix     (501) staff       (20)        7 2023-06-28 00:52:57.000000 angola-0.14.2/src/angola.egg-info/top_level.txt
-drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:52:57.381011 angola-0.14.2/tests/
--rw-r--r--   0 mardix     (501) staff       (20)        0 2022-05-28 01:11:45.000000 angola-0.14.2/tests/test_cursor.py
--rw-r--r--   0 mardix     (501) staff       (20)      716 2022-11-28 18:20:13.000000 angola-0.14.2/tests/test_database.py
--rw-r--r--   0 mardix     (501) staff       (20)     1184 2022-11-28 18:20:13.000000 angola-0.14.2/tests/test_dict_mutator.py
--rw-r--r--   0 mardix     (501) staff       (20)     4792 2023-06-23 14:59:38.000000 angola-0.14.2/tests/test_lib.py
--rw-r--r--   0 mardix     (501) staff       (20)        0 2022-05-28 01:11:55.000000 angola-0.14.2/tests/test_query.py
+drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:53:32.025714 angola-0.14.3/
+-rw-r--r--   0 mardix     (501) staff       (20)     1084 2023-03-21 05:31:22.000000 angola-0.14.3/LICENSE
+-rw-r--r--   0 mardix     (501) staff       (20)       26 2022-11-28 18:23:44.000000 angola-0.14.3/MANIFEST.in
+-rw-r--r--   0 mardix     (501) staff       (20)     1318 2023-06-28 00:53:32.025789 angola-0.14.3/PKG-INFO
+-rw-r--r--   0 mardix     (501) staff       (20)      938 2023-06-09 03:27:48.000000 angola-0.14.3/README.md
+-rw-r--r--   0 mardix     (501) staff       (20)       79 2023-06-28 00:53:32.026056 angola-0.14.3/setup.cfg
+-rw-r--r--   0 mardix     (501) staff       (20)      776 2023-06-28 00:53:19.000000 angola-0.14.3/setup.py
+drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:53:32.018880 angola-0.14.3/src/
+drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:53:32.022782 angola-0.14.3/src/angola/
+-rw-r--r--   0 mardix     (501) staff       (20)      428 2023-06-09 03:27:14.000000 angola-0.14.3/src/angola/__init__.py
+-rw-r--r--   0 mardix     (501) staff       (20)    50979 2023-06-23 08:06:55.000000 angola-0.14.3/src/angola/database.py
+-rw-r--r--   0 mardix     (501) staff       (20)    12956 2023-06-03 04:28:39.000000 angola-0.14.3/src/angola/dict_mutator.py
+-rw-r--r--   0 mardix     (501) staff       (20)    18847 2023-02-21 03:11:29.000000 angola-0.14.3/src/angola/dict_query.py
+-rw-r--r--   0 mardix     (501) staff       (20)    18669 2023-06-28 00:51:03.000000 angola-0.14.3/src/angola/lib.py
+-rw-r--r--   0 mardix     (501) staff       (20)    20084 2023-06-23 04:30:25.000000 angola-0.14.3/src/angola/lib_xql.py
+drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:53:32.024237 angola-0.14.3/src/angola.egg-info/
+-rw-r--r--   0 mardix     (501) staff       (20)     1318 2023-06-28 00:53:32.000000 angola-0.14.3/src/angola.egg-info/PKG-INFO
+-rw-r--r--   0 mardix     (501) staff       (20)      464 2023-06-28 00:53:32.000000 angola-0.14.3/src/angola.egg-info/SOURCES.txt
+-rw-r--r--   0 mardix     (501) staff       (20)        1 2023-06-28 00:53:32.000000 angola-0.14.3/src/angola.egg-info/dependency_links.txt
+-rw-r--r--   0 mardix     (501) staff       (20)       47 2023-06-28 00:53:32.000000 angola-0.14.3/src/angola.egg-info/requires.txt
+-rw-r--r--   0 mardix     (501) staff       (20)        7 2023-06-28 00:53:32.000000 angola-0.14.3/src/angola.egg-info/top_level.txt
+drwxr-xr-x   0 mardix     (501) staff       (20)        0 2023-06-28 00:53:32.025586 angola-0.14.3/tests/
+-rw-r--r--   0 mardix     (501) staff       (20)        0 2022-05-28 01:11:45.000000 angola-0.14.3/tests/test_cursor.py
+-rw-r--r--   0 mardix     (501) staff       (20)      716 2022-11-28 18:20:13.000000 angola-0.14.3/tests/test_database.py
+-rw-r--r--   0 mardix     (501) staff       (20)     1184 2022-11-28 18:20:13.000000 angola-0.14.3/tests/test_dict_mutator.py
+-rw-r--r--   0 mardix     (501) staff       (20)     4792 2023-06-23 14:59:38.000000 angola-0.14.3/tests/test_lib.py
+-rw-r--r--   0 mardix     (501) staff       (20)        0 2022-05-28 01:11:55.000000 angola-0.14.3/tests/test_query.py
```

### Comparing `angola-0.14.2/LICENSE` & `angola-0.14.3/LICENSE`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/PKG-INFO` & `angola-0.14.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: angola
-Version: 0.14.2
+Version: 0.14.3
 Summary: angola 
 Home-page: https://github.com/mardix/angola
 Author: Mardix
 Author-email: mardix@blackdevhub.io
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Topic :: Database
```

### Comparing `angola-0.14.2/README.md` & `angola-0.14.3/README.md`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/setup.py` & `angola-0.14.3/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 
 def long_description():
     with open('README.md', 'r') as file:
         return file.read()
 
-VERSION = "0.14.2"
+VERSION = "0.14.3"
 setuptools.setup(
     name='angola',
     version=VERSION,
     author='Mardix',
     author_email='mardix@blackdevhub.io',
     description='angola ',
     long_description=long_description(),
@@ -21,13 +21,12 @@
         'Topic :: Database',
     ],
     python_requires='>=3.8.0',
     install_requires = [
         "Jinja2 >= 3.0",
         "python-slugify",
         "arrow",
-        "uuid7",
         "python-arango"
     ],
     packages=['angola'],
     package_dir={'':'src'}
 )
```

### Comparing `angola-0.14.2/src/angola/database.py` & `angola-0.14.3/src/angola/database.py`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/src/angola/dict_mutator.py` & `angola-0.14.3/src/angola/dict_mutator.py`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/src/angola/dict_query.py` & `angola-0.14.3/src/angola/dict_query.py`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/src/angola/lib.py` & `angola-0.14.3/src/angola/lib.py`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/src/angola/lib_xql.py` & `angola-0.14.3/src/angola/lib_xql.py`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/src/angola.egg-info/PKG-INFO` & `angola-0.14.3/src/angola.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: angola
-Version: 0.14.2
+Version: 0.14.3
 Summary: angola 
 Home-page: https://github.com/mardix/angola
 Author: Mardix
 Author-email: mardix@blackdevhub.io
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Topic :: Database
```

### Comparing `angola-0.14.2/tests/test_database.py` & `angola-0.14.3/tests/test_database.py`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/tests/test_dict_mutator.py` & `angola-0.14.3/tests/test_dict_mutator.py`

 * *Files identical despite different names*

### Comparing `angola-0.14.2/tests/test_lib.py` & `angola-0.14.3/tests/test_lib.py`

 * *Files identical despite different names*

