# Comparing `tmp/portend-3.1.0.tar.gz` & `tmp/portend-3.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "portend-3.1.0.tar", last modified: Thu Nov 25 01:16:32 2021, max compression
+gzip compressed data, was "portend-3.2.0.tar", last modified: Tue Jun 27 23:35:11 2023, max compression
```

## Comparing `portend-3.1.0.tar` & `portend-3.2.0.tar`

### file list

```diff
@@ -1,32 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-11-25 01:16:32.846067 portend-3.1.0/
--rw-r--r--   0 runner    (1001) docker     (121)       99 2021-11-25 01:16:13.000000 portend-3.1.0/.coveragerc
--rw-r--r--   0 runner    (1001) docker     (121)      216 2021-11-25 01:16:13.000000 portend-3.1.0/.editorconfig
--rw-r--r--   0 runner    (1001) docker     (121)      136 2021-11-25 01:16:13.000000 portend-3.1.0/.flake8
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-11-25 01:16:32.842067 portend-3.1.0/.github/
--rw-r--r--   0 runner    (1001) docker     (121)      148 2021-11-25 01:16:13.000000 portend-3.1.0/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-11-25 01:16:32.842067 portend-3.1.0/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (121)     1088 2021-11-25 01:16:13.000000 portend-3.1.0/.github/workflows/main.yml
--rw-r--r--   0 runner    (1001) docker     (121)       81 2021-11-25 01:16:13.000000 portend-3.1.0/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (121)       79 2021-11-25 01:16:13.000000 portend-3.1.0/.readthedocs.yml
--rw-r--r--   0 runner    (1001) docker     (121)     2025 2021-11-25 01:16:13.000000 portend-3.1.0/CHANGES.rst
--rw-r--r--   0 runner    (1001) docker     (121)     1050 2021-11-25 01:16:13.000000 portend-3.1.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)     2807 2021-11-25 01:16:32.846067 portend-3.1.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     2229 2021-11-25 01:16:13.000000 portend-3.1.0/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-11-25 01:16:32.842067 portend-3.1.0/docs/
--rw-r--r--   0 runner    (1001) docker     (121)     1011 2021-11-25 01:16:13.000000 portend-3.1.0/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (121)       81 2021-11-25 01:16:13.000000 portend-3.1.0/docs/history.rst
--rw-r--r--   0 runner    (1001) docker     (121)      291 2021-11-25 01:16:13.000000 portend-3.1.0/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (121)       37 2021-11-25 01:16:13.000000 portend-3.1.0/mypy.ini
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-11-25 01:16:32.846067 portend-3.1.0/portend.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     2807 2021-11-25 01:16:32.000000 portend-3.1.0/portend.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      443 2021-11-25 01:16:32.000000 portend-3.1.0/portend.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2021-11-25 01:16:32.000000 portend-3.1.0/portend.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)      240 2021-11-25 01:16:32.000000 portend-3.1.0/portend.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)        8 2021-11-25 01:16:32.000000 portend-3.1.0/portend.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)     6488 2021-11-25 01:16:13.000000 portend-3.1.0/portend.py
--rw-r--r--   0 runner    (1001) docker     (121)      358 2021-11-25 01:16:13.000000 portend-3.1.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (121)      372 2021-11-25 01:16:13.000000 portend-3.1.0/pytest.ini
--rw-r--r--   0 runner    (1001) docker     (121)      991 2021-11-25 01:16:32.846067 portend-3.1.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)       92 2021-11-25 01:16:13.000000 portend-3.1.0/setup.py
--rw-r--r--   0 runner    (1001) docker     (121)     2331 2021-11-25 01:16:13.000000 portend-3.1.0/test_portend.py
--rw-r--r--   0 runner    (1001) docker     (121)      732 2021-11-25 01:16:13.000000 portend-3.1.0/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:35:11.337947 portend-3.2.0/
+-rw-r--r--   0 runner    (1001) docker     (123)      133 2023-06-27 23:34:40.000000 portend-3.2.0/.coveragerc
+-rw-r--r--   0 runner    (1001) docker     (123)      246 2023-06-27 23:34:40.000000 portend-3.2.0/.editorconfig
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:35:11.329946 portend-3.2.0/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      148 2023-06-27 23:34:40.000000 portend-3.2.0/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:35:11.329946 portend-3.2.0/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     3167 2023-06-27 23:34:40.000000 portend-3.2.0/.github/workflows/main.yml
+-rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-27 23:34:40.000000 portend-3.2.0/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      188 2023-06-27 23:34:40.000000 portend-3.2.0/.readthedocs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-27 23:34:40.000000 portend-3.2.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2092 2023-06-27 23:34:40.000000 portend-3.2.0/NEWS.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2905 2023-06-27 23:35:11.337947 portend-3.2.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2364 2023-06-27 23:34:40.000000 portend-3.2.0/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:35:11.333946 portend-3.2.0/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1122 2023-06-27 23:34:40.000000 portend-3.2.0/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-27 23:34:40.000000 portend-3.2.0/docs/history.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      291 2023-06-27 23:34:40.000000 portend-3.2.0/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-27 23:34:40.000000 portend-3.2.0/mypy.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:35:11.337947 portend-3.2.0/portend.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2905 2023-06-27 23:35:11.000000 portend-3.2.0/portend.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      439 2023-06-27 23:35:11.000000 portend-3.2.0/portend.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:35:11.000000 portend-3.2.0/portend.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      263 2023-06-27 23:35:11.000000 portend-3.2.0/portend.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-27 23:35:11.000000 portend-3.2.0/portend.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     6488 2023-06-27 23:34:40.000000 portend-3.2.0/portend.py
+-rw-r--r--   0 runner    (1001) docker     (123)      186 2023-06-27 23:34:40.000000 portend-3.2.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-27 23:34:40.000000 portend-3.2.0/pytest.ini
+-rw-r--r--   0 runner    (1001) docker     (123)     1020 2023-06-27 23:35:11.337947 portend-3.2.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2331 2023-06-27 23:34:40.000000 portend-3.2.0/test_portend.py
+-rw-r--r--   0 runner    (1001) docker     (123)       44 2023-06-27 23:34:40.000000 portend-3.2.0/towncrier.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      814 2023-06-27 23:34:40.000000 portend-3.2.0/tox.ini
```

### Comparing `portend-3.1.0/CHANGES.rst` & `portend-3.2.0/NEWS.rst`

 * *Files 8% similar despite different names*

```diff
@@ -1,7 +1,16 @@
+v3.2.0
+======
+
+Features
+--------
+
+- Require Python 3.8 or later.
+
+
 v3.1.0
 ======
 
 Require Python 3.7 or later.
 
 v3.0.0
 ======
```

### Comparing `portend-3.1.0/LICENSE` & `portend-3.2.0/LICENSE`

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

### Comparing `portend-3.1.0/PKG-INFO` & `portend-3.2.0/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,46 +1,45 @@
 Metadata-Version: 2.1
 Name: portend
-Version: 3.1.0
+Version: 3.2.0
 Summary: TCP port monitoring and discovery
 Home-page: https://github.com/jaraco/portend
 Author: Jason R. Coombs
 Author-email: jaraco@jaraco.com
-License: UNKNOWN
-Platform: UNKNOWN
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
 
 .. image:: https://img.shields.io/pypi/v/portend.svg
-   :target: `PyPI link`_
+   :target: https://pypi.org/project/portend
 
 .. image:: https://img.shields.io/pypi/pyversions/portend.svg
-   :target: `PyPI link`_
-
-.. _PyPI link: https://pypi.org/project/portend
 
 .. image:: https://github.com/jaraco/portend/workflows/tests/badge.svg
    :target: https://github.com/jaraco/portend/actions?query=workflow%3A%22tests%22
    :alt: tests
 
+.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json
+    :target: https://github.com/astral-sh/ruff
+    :alt: Ruff
+
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code style: Black
 
 .. image:: https://readthedocs.org/projects/portend/badge/?version=latest
    :target: https://portend.readthedocs.io/en/latest/?badge=latest
 
-.. image:: https://img.shields.io/badge/skeleton-2021-informational
+.. image:: https://img.shields.io/badge/skeleton-2023-informational
    :target: https://blog.jaraco.com/skeleton
 
 por·tend
 pôrˈtend/
 verb
 
     be a sign or warning that (something, especially something momentous or calamitous) is likely to happen.
@@ -80,9 +79,7 @@
 method, ``assert_free``::
 
     portend.Checker().assert_free('localhost', 31923)
 
 If assert_free is passed a host/port combination that is occupied by
 a bound listener (i.e. a TCP connection is established to that host/port),
 assert_free will raise a ``PortNotFree`` exception.
-
-
```

### Comparing `portend-3.1.0/README.rst` & `portend-3.2.0/README.rst`

 * *Files 6% similar despite different names*

```diff
@@ -1,27 +1,28 @@
 .. image:: https://img.shields.io/pypi/v/portend.svg
-   :target: `PyPI link`_
+   :target: https://pypi.org/project/portend
 
 .. image:: https://img.shields.io/pypi/pyversions/portend.svg
-   :target: `PyPI link`_
-
-.. _PyPI link: https://pypi.org/project/portend
 
 .. image:: https://github.com/jaraco/portend/workflows/tests/badge.svg
    :target: https://github.com/jaraco/portend/actions?query=workflow%3A%22tests%22
    :alt: tests
 
+.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json
+    :target: https://github.com/astral-sh/ruff
+    :alt: Ruff
+
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code style: Black
 
 .. image:: https://readthedocs.org/projects/portend/badge/?version=latest
    :target: https://portend.readthedocs.io/en/latest/?badge=latest
 
-.. image:: https://img.shields.io/badge/skeleton-2021-informational
+.. image:: https://img.shields.io/badge/skeleton-2023-informational
    :target: https://blog.jaraco.com/skeleton
 
 por·tend
 pôrˈtend/
 verb
 
     be a sign or warning that (something, especially something momentous or calamitous) is likely to happen.
```

### Comparing `portend-3.1.0/portend.egg-info/PKG-INFO` & `portend-3.2.0/portend.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,46 +1,45 @@
 Metadata-Version: 2.1
 Name: portend
-Version: 3.1.0
+Version: 3.2.0
 Summary: TCP port monitoring and discovery
 Home-page: https://github.com/jaraco/portend
 Author: Jason R. Coombs
 Author-email: jaraco@jaraco.com
-License: UNKNOWN
-Platform: UNKNOWN
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
 
 .. image:: https://img.shields.io/pypi/v/portend.svg
-   :target: `PyPI link`_
+   :target: https://pypi.org/project/portend
 
 .. image:: https://img.shields.io/pypi/pyversions/portend.svg
-   :target: `PyPI link`_
-
-.. _PyPI link: https://pypi.org/project/portend
 
 .. image:: https://github.com/jaraco/portend/workflows/tests/badge.svg
    :target: https://github.com/jaraco/portend/actions?query=workflow%3A%22tests%22
    :alt: tests
 
+.. image:: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v2.json
+    :target: https://github.com/astral-sh/ruff
+    :alt: Ruff
+
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code style: Black
 
 .. image:: https://readthedocs.org/projects/portend/badge/?version=latest
    :target: https://portend.readthedocs.io/en/latest/?badge=latest
 
-.. image:: https://img.shields.io/badge/skeleton-2021-informational
+.. image:: https://img.shields.io/badge/skeleton-2023-informational
    :target: https://blog.jaraco.com/skeleton
 
 por·tend
 pôrˈtend/
 verb
 
     be a sign or warning that (something, especially something momentous or calamitous) is likely to happen.
@@ -80,9 +79,7 @@
 method, ``assert_free``::
 
     portend.Checker().assert_free('localhost', 31923)
 
 If assert_free is passed a host/port combination that is occupied by
 a bound listener (i.e. a TCP connection is established to that host/port),
 assert_free will raise a ``PortNotFree`` exception.
-
-
```

### Comparing `portend-3.1.0/portend.py` & `portend-3.2.0/portend.py`

 * *Files identical despite different names*

### Comparing `portend-3.1.0/setup.cfg` & `portend-3.2.0/setup.cfg`

 * *Files 5% similar despite different names*

```diff
@@ -12,40 +12,42 @@
 	Programming Language :: Python :: 3
 	Programming Language :: Python :: 3 :: Only
 
 [options]
 packages = find_namespace:
 py_modules = portend
 include_package_data = true
-python_requires = >=3.7
+python_requires = >=3.8
 install_requires = 
 	tempora>=1.8
 
 [options.packages.find]
 exclude = 
 	build*
 	dist*
 	docs*
 	tests*
 
 [options.extras_require]
 testing = 
 	pytest >= 6
 	pytest-checkdocs >= 2.4
-	pytest-flake8
 	pytest-black >= 0.3.7; \
 	python_implementation != "PyPy"
 	pytest-cov
-	pytest-mypy; \
+	pytest-mypy >= 0.9.1; \
 	python_implementation != "PyPy"
-	pytest-enabler >= 1.0.1
+	pytest-enabler >= 2.2
+	pytest-ruff
 docs = 
-	sphinx
-	jaraco.packaging >= 8.2
+	sphinx >= 3.5
+	jaraco.packaging >= 9
 	rst.linker >= 1.9
+	furo
+	sphinx-lint
 
 [options.entry_points]
 
 [egg_info]
 tag_build = 
 tag_date = 0
```

### Comparing `portend-3.1.0/test_portend.py` & `portend-3.2.0/test_portend.py`

 * *Files identical despite different names*

