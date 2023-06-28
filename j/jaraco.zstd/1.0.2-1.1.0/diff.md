# Comparing `tmp/jaraco.zstd-1.0.2.tar.gz` & `tmp/jaraco.zstd-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jaraco.zstd-1.0.2.tar", last modified: Thu Mar  9 17:47:07 2023, max compression
+gzip compressed data, was "jaraco.zstd-1.1.0.tar", last modified: Tue Jun 27 23:59:53 2023, max compression
```

## Comparing `jaraco.zstd-1.0.2.tar` & `jaraco.zstd-1.1.0.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-09 17:47:07.515952 jaraco.zstd-1.0.2/
--rw-r--r--   0 runner    (1001) docker     (123)      133 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/.coveragerc
--rw-r--r--   0 runner    (1001) docker     (123)      246 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/.editorconfig
--rw-r--r--   0 runner    (1001) docker     (123)      136 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/.flake8
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-09 17:47:07.511952 jaraco.zstd-1.0.2/.github/
--rw-r--r--   0 runner    (1001) docker     (123)      148 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-09 17:47:07.511952 jaraco.zstd-1.0.2/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     3294 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/.github/workflows/main.yml
--rw-r--r--   0 runner    (1001) docker     (123)       81 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      233 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/.readthedocs.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      208 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/CHANGES.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1050 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1737 2023-03-09 17:47:07.515952 jaraco.zstd-1.0.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1209 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-09 17:47:07.511952 jaraco.zstd-1.0.2/docs/
--rw-r--r--   0 runner    (1001) docker     (123)     1125 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)       81 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/docs/history.rst
--rw-r--r--   0 runner    (1001) docker     (123)      295 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/docs/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-09 17:47:07.511952 jaraco.zstd-1.0.2/jaraco/
--rw-r--r--   0 runner    (1001) docker     (123)      681 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/jaraco/zstd.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-09 17:47:07.515952 jaraco.zstd-1.0.2/jaraco.zstd.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1737 2023-03-09 17:47:07.000000 jaraco.zstd-1.0.2/jaraco.zstd.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      443 2023-03-09 17:47:07.000000 jaraco.zstd-1.0.2/jaraco.zstd.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-09 17:47:07.000000 jaraco.zstd-1.0.2/jaraco.zstd.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      306 2023-03-09 17:47:07.000000 jaraco.zstd-1.0.2/jaraco.zstd.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-03-09 17:47:07.000000 jaraco.zstd-1.0.2/jaraco.zstd.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      154 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/mypy.ini
--rw-r--r--   0 runner    (1001) docker     (123)      378 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     1214 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/pytest.ini
--rw-r--r--   0 runner    (1001) docker     (123)     1025 2023-03-09 17:47:07.515952 jaraco.zstd-1.0.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      795 2023-03-09 17:46:48.000000 jaraco.zstd-1.0.2/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:59:53.885017 jaraco.zstd-1.1.0/
+-rw-r--r--   0 runner    (1001) docker     (123)      133 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/.coveragerc
+-rw-r--r--   0 runner    (1001) docker     (123)      246 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/.editorconfig
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:59:53.877017 jaraco.zstd-1.1.0/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      148 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:59:53.877017 jaraco.zstd-1.1.0/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     3167 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/.github/workflows/main.yml
+-rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      188 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/.readthedocs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      275 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/NEWS.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1932 2023-06-27 23:59:53.885017 jaraco.zstd-1.1.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1404 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:59:53.881017 jaraco.zstd-1.1.0/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1122 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/docs/history.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      295 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/docs/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:59:53.881017 jaraco.zstd-1.1.0/jaraco/
+-rw-r--r--   0 runner    (1001) docker     (123)      681 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/jaraco/zstd.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:59:53.881017 jaraco.zstd-1.1.0/jaraco.zstd.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1932 2023-06-27 23:59:53.000000 jaraco.zstd-1.1.0/jaraco.zstd.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      447 2023-06-27 23:59:53.000000 jaraco.zstd-1.1.0/jaraco.zstd.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:59:53.000000 jaraco.zstd-1.1.0/jaraco.zstd.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      260 2023-06-27 23:59:53.000000 jaraco.zstd-1.1.0/jaraco.zstd.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-27 23:59:53.000000 jaraco.zstd-1.1.0/jaraco.zstd.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/mypy.ini
+-rw-r--r--   0 runner    (1001) docker     (123)      186 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      842 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/pytest.ini
+-rw-r--r--   0 runner    (1001) docker     (123)      983 2023-06-27 23:59:53.885017 jaraco.zstd-1.1.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/towncrier.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      814 2023-06-27 23:59:31.000000 jaraco.zstd-1.1.0/tox.ini
```

### Comparing `jaraco.zstd-1.0.2/.github/workflows/main.yml` & `jaraco.zstd-1.1.0/.github/workflows/main.yml`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,14 @@
 name: tests
 
 on: [push, pull_request]
 
+permissions:
+  contents: read
+
 env:
   # Environment variables to support color support (jaraco/skeleton#66):
   # Request colored output from CLI tools supporting it. Different tools
   # interpret the value differently. For some, just being set is sufficient.
   # For others, it must be a non-zero integer. For yet others, being set
   # to a non-empty value is sufficient. For tox, it must be one of
   # <blank>, 0, 1, false, no, off, on, true, yes. The only enabling value
@@ -35,57 +38,51 @@
 
 
 jobs:
   test:
     strategy:
       matrix:
         python:
-        - "3.7"
+        - "3.8"
         - "3.11"
         - "3.12"
-        # Workaround for actions/setup-python#508
-        dev:
-        - -dev
         platform:
         - ubuntu-latest
         - macos-latest
         - windows-latest
         include:
-        - python: "3.8"
-          platform: ubuntu-latest
         - python: "3.9"
           platform: ubuntu-latest
         - python: "3.10"
           platform: ubuntu-latest
         - python: pypy3.9
           platform: ubuntu-latest
     runs-on: ${{ matrix.platform }}
     continue-on-error: ${{ matrix.python == '3.12' }}
     steps:
       - uses: actions/checkout@v3
       - name: Setup Python
         uses: actions/setup-python@v4
         with:
-          python-version: ${{ matrix.python }}${{ matrix.dev }}
+          python-version: ${{ matrix.python }}
+          allow-prereleases: true
       - name: Install tox
         run: |
           python -m pip install tox
       - name: Run tests
         run: tox
 
   docs:
     runs-on: ubuntu-latest
     env:
       TOXENV: docs
     steps:
       - uses: actions/checkout@v3
       - name: Setup Python
         uses: actions/setup-python@v4
-        with:
-          python-version: ${{ matrix.python }}${{ matrix.dev }}
       - name: Install tox
         run: |
           python -m pip install tox
       - name: Run tests
         run: tox
 
   check:  # This job does nothing and is only used for the branch protection
@@ -100,14 +97,16 @@
     steps:
     - name: Decide whether the needed jobs succeeded or failed
       uses: re-actors/alls-green@release/v1
       with:
         jobs: ${{ toJSON(needs) }}
 
   release:
+    permissions:
+      contents: write
     needs:
     - check
     if: github.event_name == 'push' && contains(github.ref, 'refs/tags/')
     runs-on: ubuntu-latest
 
     steps:
       - uses: actions/checkout@v3
```

### Comparing `jaraco.zstd-1.0.2/LICENSE` & `jaraco.zstd-1.1.0/LICENSE`

 * *Files 16% similar despite different names*

```diff
@@ -1,9 +1,7 @@
-Copyright Jason R. Coombs
-
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to
 deal in the Software without restriction, including without limitation the
 rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
 sell copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

### Comparing `jaraco.zstd-1.0.2/PKG-INFO` & `jaraco.zstd-1.1.0/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,39 +1,43 @@
 Metadata-Version: 2.1
 Name: jaraco.zstd
-Version: 1.0.2
+Version: 1.1.0
 Summary: zstd command
 Home-page: https://github.com/jaraco/jaraco.zstd
 Author: Jason R. Coombs
 Author-email: jaraco@jaraco.com
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Provides-Extra: testing
 Provides-Extra: docs
 License-File: LICENSE
 
 .. image:: https://img.shields.io/pypi/v/jaraco.zstd.svg
    :target: https://pypi.org/project/jaraco.zstd
 
 .. image:: https://img.shields.io/pypi/pyversions/jaraco.zstd.svg
 
 .. image:: https://github.com/jaraco/jaraco.zstd/workflows/tests/badge.svg
    :target: https://github.com/jaraco/jaraco.zstd/actions?query=workflow%3A%22tests%22
    :alt: tests
 
+.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json
+    :target: https://github.com/astral-sh/ruff
+    :alt: Ruff
+
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code style: Black
 
-.. .. image:: https://readthedocs.org/projects/skeleton/badge/?version=latest
-..    :target: https://skeleton.readthedocs.io/en/latest/?badge=latest
+.. .. image:: https://readthedocs.org/projects/PROJECT_RTD/badge/?version=latest
+..    :target: https://PROJECT_RTD.readthedocs.io/en/latest/?badge=latest
 
 .. image:: https://img.shields.io/badge/skeleton-2023-informational
    :target: https://blog.jaraco.com/skeleton
 
 Extract files from a ``.tar.zstd``::
 
     python -m jaraco.zstd --extract filename.tar.zstd
```

### Comparing `jaraco.zstd-1.0.2/README.rst` & `jaraco.zstd-1.1.0/README.rst`

 * *Files 21% similar despite different names*

```diff
@@ -3,20 +3,24 @@
 
 .. image:: https://img.shields.io/pypi/pyversions/jaraco.zstd.svg
 
 .. image:: https://github.com/jaraco/jaraco.zstd/workflows/tests/badge.svg
    :target: https://github.com/jaraco/jaraco.zstd/actions?query=workflow%3A%22tests%22
    :alt: tests
 
+.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json
+    :target: https://github.com/astral-sh/ruff
+    :alt: Ruff
+
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code style: Black
 
-.. .. image:: https://readthedocs.org/projects/skeleton/badge/?version=latest
-..    :target: https://skeleton.readthedocs.io/en/latest/?badge=latest
+.. .. image:: https://readthedocs.org/projects/PROJECT_RTD/badge/?version=latest
+..    :target: https://PROJECT_RTD.readthedocs.io/en/latest/?badge=latest
 
 .. image:: https://img.shields.io/badge/skeleton-2023-informational
    :target: https://blog.jaraco.com/skeleton
 
 Extract files from a ``.tar.zstd``::
 
     python -m jaraco.zstd --extract filename.tar.zstd
```

### Comparing `jaraco.zstd-1.0.2/docs/conf.py` & `jaraco.zstd-1.1.0/docs/conf.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 
 master_doc = "index"
 html_theme = "furo"
 
 # Link dates and other references in the changelog
 extensions += ['rst.linker']
 link_files = {
-    '../CHANGES.rst': dict(
+    '../NEWS.rst': dict(
         using=dict(GH='https://github.com'),
         replace=[
             dict(
                 pattern=r'(Issue #|\B#)(?P<issue>\d+)',
                 url='{package_url}/issues/{issue}',
             ),
             dict(
```

### Comparing `jaraco.zstd-1.0.2/jaraco/zstd.py` & `jaraco.zstd-1.1.0/jaraco/zstd.py`

 * *Files identical despite different names*

### Comparing `jaraco.zstd-1.0.2/jaraco.zstd.egg-info/PKG-INFO` & `jaraco.zstd-1.1.0/jaraco.zstd.egg-info/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,39 +1,43 @@
 Metadata-Version: 2.1
 Name: jaraco.zstd
-Version: 1.0.2
+Version: 1.1.0
 Summary: zstd command
 Home-page: https://github.com/jaraco/jaraco.zstd
 Author: Jason R. Coombs
 Author-email: jaraco@jaraco.com
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Provides-Extra: testing
 Provides-Extra: docs
 License-File: LICENSE
 
 .. image:: https://img.shields.io/pypi/v/jaraco.zstd.svg
    :target: https://pypi.org/project/jaraco.zstd
 
 .. image:: https://img.shields.io/pypi/pyversions/jaraco.zstd.svg
 
 .. image:: https://github.com/jaraco/jaraco.zstd/workflows/tests/badge.svg
    :target: https://github.com/jaraco/jaraco.zstd/actions?query=workflow%3A%22tests%22
    :alt: tests
 
+.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json
+    :target: https://github.com/astral-sh/ruff
+    :alt: Ruff
+
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code style: Black
 
-.. .. image:: https://readthedocs.org/projects/skeleton/badge/?version=latest
-..    :target: https://skeleton.readthedocs.io/en/latest/?badge=latest
+.. .. image:: https://readthedocs.org/projects/PROJECT_RTD/badge/?version=latest
+..    :target: https://PROJECT_RTD.readthedocs.io/en/latest/?badge=latest
 
 .. image:: https://img.shields.io/badge/skeleton-2023-informational
    :target: https://blog.jaraco.com/skeleton
 
 Extract files from a ``.tar.zstd``::
 
     python -m jaraco.zstd --extract filename.tar.zstd
```

### Comparing `jaraco.zstd-1.0.2/pytest.ini` & `jaraco.zstd-1.1.0/pytest.ini`

 * *Files 26% similar despite different names*

```diff
@@ -3,30 +3,25 @@
 addopts=--doctest-modules
 filterwarnings=
 	## upstream
 
 	# Ensure ResourceWarnings are emitted
 	default::ResourceWarning
 
-	# Suppress deprecation warning in flake8
-	ignore:SelectableGroups dict interface is deprecated::flake8
-
 	# shopkeep/pytest-black#55
 	ignore:<class 'pytest_black.BlackItem'> is not using a cooperative constructor:pytest.PytestDeprecationWarning
 	ignore:The \(fspath. py.path.local\) argument to BlackItem is deprecated.:pytest.PytestDeprecationWarning
 	ignore:BlackItem is an Item subclass and should not be a collector:pytest.PytestWarning
 
-	# tholo/pytest-flake8#83
-	ignore:<class 'pytest_flake8.Flake8Item'> is not using a cooperative constructor:pytest.PytestDeprecationWarning
-	ignore:The \(fspath. py.path.local\) argument to Flake8Item is deprecated.:pytest.PytestDeprecationWarning
-	ignore:Flake8Item is an Item subclass and should not be a collector:pytest.PytestWarning
-
 	# shopkeep/pytest-black#67
 	ignore:'encoding' argument not specified::pytest_black
 
 	# realpython/pytest-mypy#152
 	ignore:'encoding' argument not specified::pytest_mypy
 
 	# python/cpython#100750
 	ignore:'encoding' argument not specified::platform
 
+	# pypa/build#615
+	ignore:'encoding' argument not specified::build.env
+
 	## end upstream
```

### Comparing `jaraco.zstd-1.0.2/tox.ini` & `jaraco.zstd-1.1.0/tox.ini`

 * *Files 26% similar despite different names*

```diff
@@ -1,12 +1,8 @@
 [tox]
-envlist = python
-minversion = 3.2
-# https://github.com/jaraco/skeleton/issues/6
-tox_pip_extensions_ext_venv_update = true
 toxworkdir={env:TOX_WORK_DIR:.tox}
 
 
 [testenv]
 deps =
 setenv =
 	PYTHONWARNDEFAULTENCODING = 1
@@ -21,14 +17,24 @@
 	docs
 	testing
 changedir = docs
 commands =
 	python -m sphinx -W --keep-going . {toxinidir}/build/html
 	python -m sphinxlint
 
+[testenv:finalize]
+skip_install = True
+deps =
+	towncrier
+	jaraco.develop >= 7.23
+passenv = *
+commands =
+	python -m jaraco.develop.finalize
+
+
 [testenv:release]
 skip_install = True
 deps =
 	build
 	twine>=3
 	jaraco.develop>=7.1
 passenv =
```

