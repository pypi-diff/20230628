# Comparing `tmp/capsula-0.0.6.tar.gz` & `tmp/capsula-0.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "capsula-0.0.6.tar", max compression
+gzip compressed data, was "capsula-0.0.7.tar", max compression
```

## Comparing `capsula-0.0.6.tar` & `capsula-0.0.7.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.6/LICENSE
--rw-r--r--   0        0        0     4919 2023-06-28 15:02:08.779507 capsula-0.0.6/README.md
--rw-r--r--   0        0        0       48 2023-06-28 11:47:35.793639 capsula-0.0.6/capsula/__init__.py
--rw-r--r--   0        0        0     2211 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/__main__.py
--rw-r--r--   0        0        0       22 2023-06-28 15:22:24.699507 capsula-0.0.6/capsula/_version.py
--rw-r--r--   0        0        0     2861 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/capture.py
--rw-r--r--   0        0        0     4433 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/context.py
--rw-r--r--   0        0        0      849 2023-06-28 11:47:35.803639 capsula-0.0.6/capsula/hash.py
--rw-r--r--   0        0        0     1690 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/monitor.py
--rw-r--r--   0        0        0     3841 2023-06-28 15:22:24.699507 capsula-0.0.6/pyproject.toml
--rw-r--r--   0        0        0     5483 1970-01-01 00:00:00.000000 capsula-0.0.6/PKG-INFO
+-rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.7/LICENSE
+-rw-r--r--   0        0        0     4919 2023-06-28 15:02:08.779507 capsula-0.0.7/README.md
+-rw-r--r--   0        0        0       48 2023-06-28 11:47:35.793639 capsula-0.0.7/capsula/__init__.py
+-rw-r--r--   0        0        0     2211 2023-06-28 15:02:08.779507 capsula-0.0.7/capsula/__main__.py
+-rw-r--r--   0        0        0       22 2023-06-28 15:25:45.999509 capsula-0.0.7/capsula/_version.py
+-rw-r--r--   0        0        0     2861 2023-06-28 15:02:08.779507 capsula-0.0.7/capsula/capture.py
+-rw-r--r--   0        0        0     4433 2023-06-28 15:02:08.779507 capsula-0.0.7/capsula/context.py
+-rw-r--r--   0        0        0      849 2023-06-28 11:47:35.803639 capsula-0.0.7/capsula/hash.py
+-rw-r--r--   0        0        0     1690 2023-06-28 15:02:08.779507 capsula-0.0.7/capsula/monitor.py
+-rw-r--r--   0        0        0     3832 2023-06-28 15:25:45.999509 capsula-0.0.7/pyproject.toml
+-rw-r--r--   0        0        0     5483 1970-01-01 00:00:00.000000 capsula-0.0.7/PKG-INFO
```

### Comparing `capsula-0.0.6/LICENSE` & `capsula-0.0.7/LICENSE`

 * *Files identical despite different names*

### Comparing `capsula-0.0.6/README.md` & `capsula-0.0.7/README.md`

 * *Files identical despite different names*

### Comparing `capsula-0.0.6/capsula/__main__.py` & `capsula-0.0.7/capsula/__main__.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.6/capsula/capture.py` & `capsula-0.0.7/capsula/capture.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.6/capsula/context.py` & `capsula-0.0.7/capsula/context.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.6/capsula/hash.py` & `capsula-0.0.7/capsula/hash.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.6/capsula/monitor.py` & `capsula-0.0.7/capsula/monitor.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.6/pyproject.toml` & `capsula-0.0.7/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "capsula"
-version = "0.0.6"
+version = "0.0.7"
 description = "A Python package to capture and reproduce command execution contexts"
 authors = ["Shunichiro Nomura <nomura@space.t.u-tokyo.ac.jp>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "capsula"}]
 
 [tool.poetry.dependencies]
@@ -98,15 +98,15 @@
 # ]
 
 [tool.tbump]
 # Uncomment this if your project is hosted on GitHub:
 github_url = "https://github.com/shunichironomura/capsula/"
 
 [tool.tbump.version]
-current = "0.0.6"
+current = "0.0.7"
 
 # Example of a semver regexp.
 # Make sure this matches current_version before
 # using tbump
 regex = '''
   (?P<major>\d+)
   \.
@@ -142,15 +142,15 @@
 # have been pushed:
 [[tool.tbump.after_push]]
 name = "GitHub PR"
 cmd = "gh pr create --fill --base main"
 
 [[tool.tbump.after_push]]
 name = "GitHub PR merge"
-cmd = "gh pr merge --auto --squash --delete-branch"
+cmd = "gh pr merge --auto --delete-branch"
 
 [[tool.tbump.after_push]]
 name = "GitHub release"
 cmd = "gh release create v{new_version} --generate-notes"
 
 [[tool.tbump.after_push]]
 name = "PyPI release"
```

### Comparing `capsula-0.0.6/PKG-INFO` & `capsula-0.0.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: capsula
-Version: 0.0.6
+Version: 0.0.7
 Summary: A Python package to capture and reproduce command execution contexts
 License: MIT
 Author: Shunichiro Nomura
 Author-email: nomura@space.t.u-tokyo.ac.jp
 Requires-Python: >=3.11
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

