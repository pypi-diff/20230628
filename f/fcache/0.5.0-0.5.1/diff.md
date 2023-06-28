# Comparing `tmp/fcache-0.5.0.tar.gz` & `tmp/fcache-0.5.1.tar.gz`

## Comparing `fcache-0.5.0.tar` & `fcache-0.5.1.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 fcache-0.5.0/src/fcache/__init__.py
--rw-r--r--   0        0        0    11459 2020-02-02 00:00:00.000000 fcache-0.5.0/src/fcache/cache.py
--rw-r--r--   0        0        0     3748 2020-02-02 00:00:00.000000 fcache-0.5.0/src/fcache/posixemulation.py
--rw-r--r--   0        0        0       12 2020-02-02 00:00:00.000000 fcache-0.5.0/.gitignore
--rw-r--r--   0        0        0      373 2020-02-02 00:00:00.000000 fcache-0.5.0/AUTHORS.txt
--rw-r--r--   0        0        0     1056 2020-02-02 00:00:00.000000 fcache-0.5.0/LICENSE.txt
--rw-r--r--   0        0        0     1653 2020-02-02 00:00:00.000000 fcache-0.5.0/README.rst
--rw-r--r--   0        0        0     2271 2020-02-02 00:00:00.000000 fcache-0.5.0/pyproject.toml
--rw-r--r--   0        0        0     2781 2020-02-02 00:00:00.000000 fcache-0.5.0/PKG-INFO
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 fcache-0.5.1/src/fcache/__init__.py
+-rw-r--r--   0        0        0    11480 2020-02-02 00:00:00.000000 fcache-0.5.1/src/fcache/cache.py
+-rw-r--r--   0        0        0     3748 2020-02-02 00:00:00.000000 fcache-0.5.1/src/fcache/posixemulation.py
+-rw-r--r--   0        0        0       12 2020-02-02 00:00:00.000000 fcache-0.5.1/.gitignore
+-rw-r--r--   0        0        0      398 2020-02-02 00:00:00.000000 fcache-0.5.1/AUTHORS.rst
+-rw-r--r--   0        0        0     1056 2020-02-02 00:00:00.000000 fcache-0.5.1/LICENSE.txt
+-rw-r--r--   0        0        0     1653 2020-02-02 00:00:00.000000 fcache-0.5.1/README.rst
+-rw-r--r--   0        0        0     2536 2020-02-02 00:00:00.000000 fcache-0.5.1/pyproject.toml
+-rw-r--r--   0        0        0     2927 2020-02-02 00:00:00.000000 fcache-0.5.1/PKG-INFO
```

### Comparing `fcache-0.5.0/src/fcache/cache.py` & `fcache-0.5.1/src/fcache/cache.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,25 +2,25 @@
 from collections.abc import MutableMapping
 import logging
 import os
 import pickle
 import shutil
 import tempfile
 
-import appdirs
+import platformdirs
 
 from .posixemulation import rename
 
 logger = logging.getLogger(__name__)
 
 
 class FileCache(MutableMapping):
     """A persistent file cache that is dictionary-like and has a write buffer.
 
-    *appname* is passed to `appdirs <https://pypi.python.org/pypi/appdirs/>`_
+    *appname* is passed to `platformdirs <https://pypi.org/project/platformdirs/>`_
     to determine a system-appropriate location for the cache files. The cache
     directory used is available via :data:`cache_dir`.
 
     By default, a write buffer is used, so writing to cache files is not done
     until :meth:`sync` is explicitly called. This behavior can be changed using
     the optional *flag* argument.
 
@@ -36,15 +36,15 @@
         permissions.
     :param str keyencoding: The encoding the keys use, defaults to 'utf-8'.
         This is used if *serialize* is ``False``; the keys are treated as
         :class:`bytes` objects.
     :param bool serialize: Whether or not to (de)serialize the values. If a
         cache is used with a :class:`~shelve.Shelf`, set this to ``False``.
     :param str app_cache_dir: absolute path to root cache directory to be
-        used in place of system-appropriate location determined by appdirs
+        used in place of system-appropriate location determined by platformdirs
 
     The optional *flag* argument can be:
 
     +---------+-------------------------------------------+
     | Value   | Meaning                                   |
     +=========+===========================================+
     | ``'r'`` | Open existing cache for reading only      |
@@ -102,15 +102,15 @@
 
         appname, subcache = self._parse_appname(appname)
         if "cache" in subcache:
             raise ValueError("invalid subcache name: 'cache'.")
         self._is_subcache = bool(subcache)
 
         if not app_cache_dir:
-            app_cache_dir = appdirs.user_cache_dir(appname, appname)
+            app_cache_dir = platformdirs.user_cache_dir(appname, appname)
         subcache_dir = os.path.join(app_cache_dir, *subcache)
         self.cache_dir = os.path.join(subcache_dir, "cache")
         exists = os.path.exists(self.cache_dir)
 
         if len(flag) > 1 and flag[1] == "s":
             self._sync = True
         else:
```

### Comparing `fcache-0.5.0/src/fcache/posixemulation.py` & `fcache-0.5.1/src/fcache/posixemulation.py`

 * *Files identical despite different names*

### Comparing `fcache-0.5.0/LICENSE.txt` & `fcache-0.5.1/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `fcache-0.5.0/README.rst` & `fcache-0.5.1/README.rst`

 * *Files identical despite different names*

### Comparing `fcache-0.5.0/pyproject.toml` & `fcache-0.5.1/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -29,20 +29,22 @@
     "Programming Language :: Python :: 3.9",
     "Programming Language :: Python :: 3.10",
     "Programming Language :: Python :: 3.11",
     "Topic :: Software Development :: Libraries :: Python Modules",
     "Topic :: System :: Filesystems",
 ]
 dependencies = [
-    "appdirs",
+    "platformdirs ~= 3.0",
 ]
 
 [project.urls]
-Documentation = "https://tsroten.github.io/fcache/"
-"Source code" = "https://github.com/tsroten/fcache"
+Documentation = "https://tsroten.github.io/fcache"
+Changes = "https://tsroten.github.io/fcache/history.html"
+"Issue Tracker" = "https://github.com/tsroten/fcache/issues"
+"Source Code" = "https://github.com/tsroten/fcache"
 
 [tool.hatch.version]
 path = "src/fcache/__init__.py"
 
 [tool.hatch.build.targets.sdist]
 include = [
     "/src",
@@ -69,15 +71,20 @@
     "clean",
     "generate",
     "check",
     "view"
 ]
 
 [tool.hatch.envs.test.scripts]
-run = "python3 -m unittest"
+clean = "find . -type f -name '*.py[co]' -delete -o -type d -name __pycache__ -delete"
+test = "python3 -Wdefault -m unittest -v"
+run = [
+    "clean",
+    "test"
+]
 
 [[tool.hatch.envs.test.matrix]]
 python = ["3.7", "3.8", "3.9", "3.10", "3.11"]
 
 [tool.hatch.envs.style]
 detached = true
 dependencies = [
```

### Comparing `fcache-0.5.0/PKG-INFO` & `fcache-0.5.1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,16 +1,18 @@
 Metadata-Version: 2.1
 Name: fcache
-Version: 0.5.0
+Version: 0.5.1
 Summary: a dictionary-like, file-based cache module for Python
-Project-URL: Documentation, https://tsroten.github.io/fcache/
-Project-URL: Source code, https://github.com/tsroten/fcache
+Project-URL: Documentation, https://tsroten.github.io/fcache
+Project-URL: Changes, https://tsroten.github.io/fcache/history.html
+Project-URL: Issue Tracker, https://github.com/tsroten/fcache/issues
+Project-URL: Source Code, https://github.com/tsroten/fcache
 Author-email: Thomas Roten <thomas@roten.us>
 License-Expression: MIT
-License-File: AUTHORS.txt
+License-File: AUTHORS.rst
 License-File: LICENSE.txt
 Keywords: cache,file,serialize
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
@@ -19,15 +21,15 @@
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: System :: Filesystems
 Requires-Python: >=3.7
-Requires-Dist: appdirs
+Requires-Dist: platformdirs~=3.0
 Description-Content-Type: text/x-rst
 
 fcache
 ======
 
 .. image:: https://badge.fury.io/py/fcache.svg
     :target: https://pypi.org/project/fcache
```

