# Comparing `tmp/pytest-coverage-context-0.7.0.tar.gz` & `tmp/pytest-coverage-context-0.7.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/pytest-coverage-context-0.7.0.tar", last modified: Mon Jan  4 06:39:05 2021, max compression
+gzip compressed data, was "pytest-coverage-context-0.7.1.tar", last modified: Wed Jun 28 14:26:03 2023, max compression
```

## Comparing `pytest-coverage-context-0.7.0.tar` & `pytest-coverage-context-0.7.1.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/
--rw-r--r--   0 vampas    (1000) vampas    (1000)    15786 2019-12-26 14:50:14.000000 pytest-coverage-context-0.7.0/.pylintrc
--rw-r--r--   0 vampas    (1000) vampas    (1000)      154 2020-12-07 10:38:12.000000 pytest-coverage-context-0.7.0/setup.py
--rw-r--r--   0 vampas    (1000) vampas    (1000)      275 2020-12-07 08:36:39.000000 pytest-coverage-context-0.7.0/pyproject.toml
--rw-r--r--   0 vampas    (1000) vampas    (1000)       87 2019-12-26 14:41:10.000000 pytest-coverage-context-0.7.0/README.md
--rw-r--r--   0 vampas    (1000) vampas    (1000)      730 2021-01-04 06:23:22.000000 pytest-coverage-context-0.7.0/.coveragerc
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/tests/
--rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 10:53:44.000000 pytest-coverage-context-0.7.0/tests/__init__.py
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/tests/functional/
--rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 11:01:58.000000 pytest-coverage-context-0.7.0/tests/functional/__init__.py
--rw-r--r--   0 vampas    (1000) vampas    (1000)      869 2021-01-04 06:35:47.000000 pytest-coverage-context-0.7.0/tests/functional/test_cli.py
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/coveragectx/
--rw-r--r--   0 vampas    (1000) vampas    (1000)       21 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/coveragectx/version.py
--rw-r--r--   0 vampas    (1000) vampas    (1000)      644 2020-12-07 15:27:43.000000 pytest-coverage-context-0.7.0/coveragectx/__init__.py
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/coveragectx/pytest/
--rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 09:23:22.000000 pytest-coverage-context-0.7.0/coveragectx/pytest/__init__.py
--rw-r--r--   0 vampas    (1000) vampas    (1000)     3439 2021-01-04 06:36:22.000000 pytest-coverage-context-0.7.0/coveragectx/pytest/plugin.py
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/coveragectx/coverage/
--rw-r--r--   0 vampas    (1000) vampas    (1000)      893 2021-01-04 06:05:09.000000 pytest-coverage-context-0.7.0/coveragectx/coverage/cli.py
--rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 09:23:12.000000 pytest-coverage-context-0.7.0/coveragectx/coverage/__init__.py
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/coveragectx/coverage/site/
--rw-r--r--   0 vampas    (1000) vampas    (1000)      379 2021-01-04 06:28:01.000000 pytest-coverage-context-0.7.0/coveragectx/coverage/site/sitecustomize.py
--rw-r--r--   0 vampas    (1000) vampas    (1000)     1846 2021-01-03 11:07:32.000000 pytest-coverage-context-0.7.0/coveragectx/coverage/plugin.py
-drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/
--rw-r--r--   0 vampas    (1000) vampas    (1000)       41 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/requires.txt
--rw-r--r--   0 vampas    (1000) vampas    (1000)      784 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/SOURCES.txt
--rw-r--r--   0 vampas    (1000) vampas    (1000)        1 2020-12-07 13:05:31.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/not-zip-safe
--rw-r--r--   0 vampas    (1000) vampas    (1000)     1099 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/PKG-INFO
--rw-r--r--   0 vampas    (1000) vampas    (1000)      127 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/entry_points.txt
--rw-r--r--   0 vampas    (1000) vampas    (1000)       12 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/top_level.txt
--rw-r--r--   0 vampas    (1000) vampas    (1000)        1 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/dependency_links.txt
--rw-r--r--   0 vampas    (1000) vampas    (1000)       43 2021-01-03 10:52:31.000000 pytest-coverage-context-0.7.0/requirements.txt
--rw-r--r--   0 vampas    (1000) vampas    (1000)     1471 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/setup.cfg
--rw-r--r--   0 vampas    (1000) vampas    (1000)    11357 2019-12-26 14:41:10.000000 pytest-coverage-context-0.7.0/LICENSE
--rw-r--r--   0 vampas    (1000) vampas    (1000)     1099 2021-01-04 06:39:05.000000 pytest-coverage-context-0.7.0/PKG-INFO
--rw-r--r--   0 vampas    (1000) vampas    (1000)     1892 2021-01-04 06:38:08.000000 pytest-coverage-context-0.7.0/.gitignore
--rw-r--r--   0 vampas    (1000) vampas    (1000)     1489 2021-01-03 10:53:09.000000 pytest-coverage-context-0.7.0/.pre-commit-config.yaml
--rw-r--r--   0 vampas    (1000) vampas    (1000)     9769 2021-01-04 06:36:14.000000 pytest-coverage-context-0.7.0/noxfile.py
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      730 2021-01-04 06:23:22.000000 pytest-coverage-context-0.7.1/.coveragerc
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     1892 2021-01-04 06:38:08.000000 pytest-coverage-context-0.7.1/.gitignore
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     1489 2021-01-03 10:53:09.000000 pytest-coverage-context-0.7.1/.pre-commit-config.yaml
+-rw-r--r--   0 vampas    (1000) vampas    (1000)    15786 2019-12-26 14:50:14.000000 pytest-coverage-context-0.7.1/.pylintrc
+-rw-r--r--   0 vampas    (1000) vampas    (1000)    11357 2019-12-26 14:41:10.000000 pytest-coverage-context-0.7.1/LICENSE
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     1350 2023-06-28 14:26:03.133946 pytest-coverage-context-0.7.1/PKG-INFO
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      209 2023-06-28 14:23:12.000000 pytest-coverage-context-0.7.1/README.md
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/coveragectx/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      644 2020-12-07 15:27:43.000000 pytest-coverage-context-0.7.1/coveragectx/__init__.py
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/coveragectx/coverage/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 09:23:12.000000 pytest-coverage-context-0.7.1/coveragectx/coverage/__init__.py
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      893 2021-01-04 06:05:09.000000 pytest-coverage-context-0.7.1/coveragectx/coverage/cli.py
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     1846 2021-01-03 11:07:32.000000 pytest-coverage-context-0.7.1/coveragectx/coverage/plugin.py
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/coveragectx/coverage/site/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      369 2021-01-04 06:58:35.000000 pytest-coverage-context-0.7.1/coveragectx/coverage/site/sitecustomize.py
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/coveragectx/pytest/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 09:23:22.000000 pytest-coverage-context-0.7.1/coveragectx/pytest/__init__.py
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     3439 2021-01-04 06:36:22.000000 pytest-coverage-context-0.7.1/coveragectx/pytest/plugin.py
+-rw-r--r--   0 vampas    (1000) vampas    (1000)       21 2023-06-28 14:26:03.000000 pytest-coverage-context-0.7.1/coveragectx/version.py
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     9769 2021-01-04 06:36:14.000000 pytest-coverage-context-0.7.1/noxfile.py
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      275 2020-12-07 08:36:39.000000 pytest-coverage-context-0.7.1/pyproject.toml
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     1350 2023-06-28 14:26:03.000000 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/PKG-INFO
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      784 2023-06-28 14:26:03.000000 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/SOURCES.txt
+-rw-r--r--   0 vampas    (1000) vampas    (1000)        1 2023-06-28 14:26:03.000000 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/dependency_links.txt
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      126 2023-06-28 14:26:03.000000 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/entry_points.txt
+-rw-r--r--   0 vampas    (1000) vampas    (1000)        1 2020-12-07 13:05:31.000000 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/not-zip-safe
+-rw-r--r--   0 vampas    (1000) vampas    (1000)       41 2023-06-28 14:26:03.000000 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/requires.txt
+-rw-r--r--   0 vampas    (1000) vampas    (1000)       12 2023-06-28 14:26:03.000000 pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/top_level.txt
+-rw-r--r--   0 vampas    (1000) vampas    (1000)       43 2021-01-03 10:52:31.000000 pytest-coverage-context-0.7.1/requirements.txt
+-rw-r--r--   0 vampas    (1000) vampas    (1000)     1516 2023-06-28 14:26:03.133946 pytest-coverage-context-0.7.1/setup.cfg
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      154 2020-12-07 10:38:12.000000 pytest-coverage-context-0.7.1/setup.py
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/tests/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 10:53:44.000000 pytest-coverage-context-0.7.1/tests/__init__.py
+drwxr-xr-x   0 vampas    (1000) vampas    (1000)        0 2023-06-28 14:26:03.130612 pytest-coverage-context-0.7.1/tests/functional/
+-rw-r--r--   0 vampas    (1000) vampas    (1000)        0 2020-12-07 11:01:58.000000 pytest-coverage-context-0.7.1/tests/functional/__init__.py
+-rw-r--r--   0 vampas    (1000) vampas    (1000)      869 2021-01-04 06:35:47.000000 pytest-coverage-context-0.7.1/tests/functional/test_cli.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `pytest-coverage-context-0.7.0/.pylintrc` & `pytest-coverage-context-0.7.1/.pylintrc`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/.coveragerc` & `pytest-coverage-context-0.7.1/.coveragerc`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/tests/functional/test_cli.py` & `pytest-coverage-context-0.7.1/tests/functional/test_cli.py`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/coveragectx/__init__.py` & `pytest-coverage-context-0.7.1/coveragectx/__init__.py`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/coveragectx/pytest/plugin.py` & `pytest-coverage-context-0.7.1/coveragectx/pytest/plugin.py`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/coveragectx/coverage/cli.py` & `pytest-coverage-context-0.7.1/coveragectx/coverage/cli.py`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/coveragectx/coverage/plugin.py` & `pytest-coverage-context-0.7.1/coveragectx/coverage/plugin.py`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/SOURCES.txt` & `pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/pytest_coverage_context.egg-info/PKG-INFO` & `pytest-coverage-context-0.7.1/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,25 +1,32 @@
-Metadata-Version: 1.2
+Metadata-Version: 2.1
 Name: pytest-coverage-context
-Version: 0.7.0
+Version: 0.7.1
 Summary: Coverage dynamic context support for PyTest, including sub-processes
 Home-page: https://github.com/saltstack/pytest-salt-factories
 Author: Pedro Algarvio
 Author-email: pedro@algarvio.me
 License: Apache Software License 2.0
 Project-URL: Source, https://github.com/saltstack/pytest-salt-factories
 Project-URL: Tracker, https://github.com/saltstack/pytest-salt-factories/issues
-Description: UNKNOWN
 Platform: all
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Cython
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: Apache Software License
 Requires-Python: >=3.5
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
+# Project Sunset
+VMware has ended active development of this project, this project/repository will no longer be updated.
+
+# coverage-salt-contexts
+Python Coverage >= 5.0 Plugin To Set Runtime Dynamic Contexts
```

### Comparing `pytest-coverage-context-0.7.0/setup.cfg` & `pytest-coverage-context-0.7.1/setup.cfg`

 * *Files 21% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 [metadata]
 name = pytest-coverage-context
 description = Coverage dynamic context support for PyTest, including sub-processes
-long_description = file: README.rst
+long_description = file: README.md
+long_description_content_type = text/markdown
 author = Pedro Algarvio
 author_email = pedro@algarvio.me
 url = https://github.com/saltstack/pytest-salt-factories
 project_urls = 
 	Source=https://github.com/saltstack/pytest-salt-factories
 	Tracker=https://github.com/saltstack/pytest-salt-factories/issues
 license = Apache Software License 2.0
```

### Comparing `pytest-coverage-context-0.7.0/LICENSE` & `pytest-coverage-context-0.7.1/LICENSE`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/PKG-INFO` & `pytest-coverage-context-0.7.1/pytest_coverage_context.egg-info/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,25 +1,32 @@
-Metadata-Version: 1.2
+Metadata-Version: 2.1
 Name: pytest-coverage-context
-Version: 0.7.0
+Version: 0.7.1
 Summary: Coverage dynamic context support for PyTest, including sub-processes
 Home-page: https://github.com/saltstack/pytest-salt-factories
 Author: Pedro Algarvio
 Author-email: pedro@algarvio.me
 License: Apache Software License 2.0
 Project-URL: Source, https://github.com/saltstack/pytest-salt-factories
 Project-URL: Tracker, https://github.com/saltstack/pytest-salt-factories/issues
-Description: UNKNOWN
 Platform: all
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Cython
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: Apache Software License
 Requires-Python: >=3.5
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
+# Project Sunset
+VMware has ended active development of this project, this project/repository will no longer be updated.
+
+# coverage-salt-contexts
+Python Coverage >= 5.0 Plugin To Set Runtime Dynamic Contexts
```

### Comparing `pytest-coverage-context-0.7.0/.gitignore` & `pytest-coverage-context-0.7.1/.gitignore`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/.pre-commit-config.yaml` & `pytest-coverage-context-0.7.1/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `pytest-coverage-context-0.7.0/noxfile.py` & `pytest-coverage-context-0.7.1/noxfile.py`

 * *Files identical despite different names*

