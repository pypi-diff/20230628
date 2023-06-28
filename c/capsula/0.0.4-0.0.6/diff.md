# Comparing `tmp/capsula-0.0.4.tar.gz` & `tmp/capsula-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "capsula-0.0.4.tar", max compression
+gzip compressed data, was "capsula-0.0.6.tar", max compression
```

## Comparing `capsula-0.0.4.tar` & `capsula-0.0.6.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.4/LICENSE
--rw-r--r--   0        0        0     4919 2023-06-28 15:02:08.779507 capsula-0.0.4/README.md
--rw-r--r--   0        0        0       48 2023-06-28 11:47:35.793639 capsula-0.0.4/capsula/__init__.py
--rw-r--r--   0        0        0     2211 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/__main__.py
--rw-r--r--   0        0        0       22 2023-06-28 15:04:01.839506 capsula-0.0.4/capsula/_version.py
--rw-r--r--   0        0        0     2861 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/capture.py
--rw-r--r--   0        0        0     4433 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/context.py
--rw-r--r--   0        0        0      849 2023-06-28 11:47:35.803639 capsula-0.0.4/capsula/hash.py
--rw-r--r--   0        0        0     1690 2023-06-28 15:02:08.779507 capsula-0.0.4/capsula/monitor.py
--rw-r--r--   0        0        0     3651 2023-06-28 15:04:01.839506 capsula-0.0.4/pyproject.toml
--rw-r--r--   0        0        0     5483 1970-01-01 00:00:00.000000 capsula-0.0.4/PKG-INFO
+-rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.6/LICENSE
+-rw-r--r--   0        0        0     4919 2023-06-28 15:02:08.779507 capsula-0.0.6/README.md
+-rw-r--r--   0        0        0       48 2023-06-28 11:47:35.793639 capsula-0.0.6/capsula/__init__.py
+-rw-r--r--   0        0        0     2211 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/__main__.py
+-rw-r--r--   0        0        0       22 2023-06-28 15:22:24.699507 capsula-0.0.6/capsula/_version.py
+-rw-r--r--   0        0        0     2861 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/capture.py
+-rw-r--r--   0        0        0     4433 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/context.py
+-rw-r--r--   0        0        0      849 2023-06-28 11:47:35.803639 capsula-0.0.6/capsula/hash.py
+-rw-r--r--   0        0        0     1690 2023-06-28 15:02:08.779507 capsula-0.0.6/capsula/monitor.py
+-rw-r--r--   0        0        0     3841 2023-06-28 15:22:24.699507 capsula-0.0.6/pyproject.toml
+-rw-r--r--   0        0        0     5483 1970-01-01 00:00:00.000000 capsula-0.0.6/PKG-INFO
```

### Comparing `capsula-0.0.4/LICENSE` & `capsula-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `capsula-0.0.4/README.md` & `capsula-0.0.6/README.md`

 * *Files identical despite different names*

### Comparing `capsula-0.0.4/capsula/__main__.py` & `capsula-0.0.6/capsula/__main__.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.4/capsula/capture.py` & `capsula-0.0.6/capsula/capture.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.4/capsula/context.py` & `capsula-0.0.6/capsula/context.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.4/capsula/hash.py` & `capsula-0.0.6/capsula/hash.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.4/capsula/monitor.py` & `capsula-0.0.6/capsula/monitor.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.4/pyproject.toml` & `capsula-0.0.6/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "capsula"
-version = "0.0.4"
+version = "0.0.6"
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
-current = "0.0.4"
+current = "0.0.6"
 
 # Example of a semver regexp.
 # Make sure this matches current_version before
 # using tbump
 regex = '''
   (?P<major>\d+)
   \.
@@ -137,13 +137,21 @@
 #  [[tool.tbump.before_commit]]
 #  name = "check changelog"
 #  cmd = "grep -q {new_version} Changelog.rst"
 
 # Or run some commands after the git tag and the branch
 # have been pushed:
 [[tool.tbump.after_push]]
+name = "GitHub PR"
+cmd = "gh pr create --fill --base main"
+
+[[tool.tbump.after_push]]
+name = "GitHub PR merge"
+cmd = "gh pr merge --auto --squash --delete-branch"
+
+[[tool.tbump.after_push]]
 name = "GitHub release"
 cmd = "gh release create v{new_version} --generate-notes"
 
 [[tool.tbump.after_push]]
 name = "PyPI release"
 cmd = "poetry publish --build"
```

### Comparing `capsula-0.0.4/PKG-INFO` & `capsula-0.0.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: capsula
-Version: 0.0.4
+Version: 0.0.6
 Summary: A Python package to capture and reproduce command execution contexts
 License: MIT
 Author: Shunichiro Nomura
 Author-email: nomura@space.t.u-tokyo.ac.jp
 Requires-Python: >=3.11
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

