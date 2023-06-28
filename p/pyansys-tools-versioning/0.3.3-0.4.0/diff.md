# Comparing `tmp/pyansys-tools-versioning-0.3.3.tar.gz` & `tmp/pyansys_tools_versioning-0.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyansys-tools-versioning-0.3.3.tar", last modified: Wed Jan 18 07:14:33 2023, max compression
+gzip compressed data, was "pyansys_tools_versioning-0.4.0.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
```

## Comparing `pyansys-tools-versioning-0.3.3.tar` & `pyansys_tools_versioning-0.4.0.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1089 2023-01-18 07:14:20.251881 pyansys-tools-versioning-0.3.3/LICENSE
--rw-r--r--   0        0        0     6144 2023-01-18 07:14:20.251881 pyansys-tools-versioning-0.3.3/README.rst
--rw-r--r--   0        0        0     1577 2023-01-18 07:14:20.255882 pyansys-tools-versioning-0.3.3/pyproject.toml
--rw-r--r--   0        0        0      410 2023-01-18 07:14:20.255882 pyansys-tools-versioning-0.3.3/src/ansys/tools/versioning/__init__.py
--rw-r--r--   0        0        0      705 2023-01-18 07:14:20.255882 pyansys-tools-versioning-0.3.3/src/ansys/tools/versioning/exceptions.py
--rw-r--r--   0        0        0    18144 2023-01-18 07:14:20.255882 pyansys-tools-versioning-0.3.3/src/ansys/tools/versioning/utils.py
--rw-r--r--   0        0        0     7350 1970-01-01 00:00:00.000000 pyansys-tools-versioning-0.3.3/PKG-INFO
+-rw-r--r--   0        0        0     1089 2023-06-28 06:34:57.279866 pyansys_tools_versioning-0.4.0/LICENSE
+-rw-r--r--   0        0        0     6130 2023-06-28 06:34:57.279866 pyansys_tools_versioning-0.4.0/README.rst
+-rw-r--r--   0        0        0     1576 2023-06-28 06:34:57.279866 pyansys_tools_versioning-0.4.0/pyproject.toml
+-rw-r--r--   0        0        0      410 2023-06-28 06:34:57.279866 pyansys_tools_versioning-0.4.0/src/ansys/tools/versioning/__init__.py
+-rw-r--r--   0        0        0      705 2023-06-28 06:34:57.279866 pyansys_tools_versioning-0.4.0/src/ansys/tools/versioning/exceptions.py
+-rw-r--r--   0        0        0    18141 2023-06-28 06:34:57.279866 pyansys_tools_versioning-0.4.0/src/ansys/tools/versioning/utils.py
+-rw-r--r--   0        0        0     7335 1970-01-01 00:00:00.000000 pyansys_tools_versioning-0.4.0/PKG-INFO
```

### Comparing `pyansys-tools-versioning-0.3.3/LICENSE` & `pyansys_tools_versioning-0.4.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pyansys-tools-versioning-0.3.3/README.rst` & `pyansys_tools_versioning-0.4.0/README.rst`

 * *Files 2% similar despite different names*

```diff
@@ -10,32 +10,32 @@
    :target: https://pypi.org/project/pyansys-tools-versioning
    :alt: Python
 
 .. |pypi| image:: https://img.shields.io/pypi/v/pyansys-tools-versioning.svg?logo=python&logoColor=white
    :target: https://pypi.org/project/pyansys-tools-versioning
    :alt: PyPI
 
-.. |codecov| image:: https://codecov.io/gh/pyansys/pyansys-tools-versioning/branch/main/graph/badge.svg
-   :target: https://codecov.io/gh/pyansys/pyansys-tools-versioning
+.. |codecov| image:: https://codecov.io/gh/ansys/pyansys-tools-versioning/branch/main/graph/badge.svg
+   :target: https://codecov.io/gh/ansys/pyansys-tools-versioning
    :alt: Codecov
 
-.. |GH-CI| image:: https://github.com/pyansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml/badge.svg
-   :target: https://github.com/pyansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml
+.. |GH-CI| image:: https://github.com/ansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml/badge.svg
+   :target: https://github.com/ansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml
    :alt: GH-CI
 
 .. |MIT| image:: https://img.shields.io/badge/License-MIT-yellow.svg
    :target: https://opensource.org/licenses/MIT
    :alt: MIT
 
 .. |black| image:: https://img.shields.io/badge/code%20style-black-000000.svg?style=flat
    :target: https://github.com/psf/black
    :alt: Black
 
-.. |pre-commit| image:: https://results.pre-commit.ci/badge/github/pyansys/pyansys-tools-versioning/main.svg
-   :target: https://results.pre-commit.ci/latest/github/pyansys/pyansys-tools-versioning/main
+.. |pre-commit| image:: https://results.pre-commit.ci/badge/github/ansys/pyansys-tools-versioning/main.svg
+   :target: https://results.pre-commit.ci/latest/github/ansys/pyansys-tools-versioning/main
    :alt: pre-commit.ci status
 
 Utilities for backwards and forwards server support.
 
 
 How to install
 --------------
@@ -67,15 +67,15 @@
 Before contributing to the project, please refer to the `PyAnsys Developer's guide`_. You will 
 need to follow these steps:
 
 1. Start by cloning this repository:
 
     .. code:: bash
 
-        git clone https://github.com/pyansys/pyansys-tools-versioning
+        git clone https://github.com/ansys/pyansys-tools-versioning
 
 2. Create a fresh-clean Python environment and activate it:
 
     .. code:: bash
 
         # Create a virtual environment
         python -m venv .venv
```

### Comparing `pyansys-tools-versioning-0.3.3/pyproject.toml` & `pyansys_tools_versioning-0.4.0/pyproject.toml`

 * *Files 7% similar despite different names*

```diff
@@ -1,57 +1,57 @@
 [build-system]
 requires = ["flit_core >=3.2,<4"]
 build-backend = "flit_core.buildapi"
 
 [project]
 # Check https://flit.readthedocs.io/en/latest/pyproject_toml.html for all available sections
 name = "pyansys-tools-versioning"
-version = "0.3.3"
+version = "0.4.0"
 dynamic = ["description"]
 readme = "README.rst"
-requires-python = ">=3.7"
+requires-python = ">=3.8"
 license = {file = "LICENSE"}
 authors = [
     {name = "ANSYS, Inc.", email = "pyansys.support@ansys.com"},
 ]
 maintainers = [
     {name = "PyAnsys developers", email = "pyansys.maintainers@ansys.com"},
 ]
 classifiers = [
     "Development Status :: 4 - Beta",
-    "Programming Language :: Python :: 3.7",
     "Programming Language :: Python :: 3.8",
     "Programming Language :: Python :: 3.9",
     "Programming Language :: Python :: 3.10",
+    "Programming Language :: Python :: 3.11",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
 ]
 dependencies = [
     "importlib-metadata >=4.12.0",
 ]
 
 [project.optional-dependencies]
 tests = [
-    "hypothesis==6.62.1",
-    "pytest==7.2.1",
-    "pytest-cov==4.0.0",
+    "hypothesis==6.80.0",
+    "pytest==7.4.0",
+    "pytest-cov==4.1.0",
 ]
 doc = [
-    "ansys_sphinx_theme==0.8.0",
+    "ansys_sphinx_theme==0.9.9",
     "numpydoc==1.5.0",
-    "Sphinx==5.3.0",
-    "sphinx-autoapi==2.0.0",
-    "Sphinx-copybutton==0.5.1",
+    "Sphinx==7.0.1",
+    "sphinx-autoapi==2.1.1",
+    "Sphinx-copybutton==0.5.2",
 ]
 
 [tool.flit.module]
 name = "ansys.tools.versioning"
 
 [project.urls]
-Source = "https://github.com/pyansys/pyansys-tools-versioning"
+Source = "https://github.com/ansys/pyansys-tools-versioning"
 
 [tool.black]
 line-length = 100
 
 [tool.isort]
 profile = "black"
 force_sort_within_sections = true
```

### Comparing `pyansys-tools-versioning-0.3.3/src/ansys/tools/versioning/exceptions.py` & `pyansys_tools_versioning-0.4.0/src/ansys/tools/versioning/exceptions.py`

 * *Files identical despite different names*

### Comparing `pyansys-tools-versioning-0.3.3/src/ansys/tools/versioning/utils.py` & `pyansys_tools_versioning-0.4.0/src/ansys/tools/versioning/utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -205,15 +205,14 @@
         else sanitize_version_tuple(version)
         for version in [server_version, required_version]
     ]
 
     for ith_num, (server_version_number, required_version_number) in enumerate(
         zip(server_version, required_version), start=1
     ):
-
         # Keep comparing if both numbers are the same
         if server_version_number == required_version_number and ith_num != 3:
             continue
 
         # If all numbers are the same, server and required version are exactly
         # the same
         elif server_version_number == required_version_number and ith_num == 3:
@@ -244,15 +243,14 @@
         Decorated class method requires ``_server_version`` attribute.
     VersionError
         Decorated class method is not supported by server version.
 
     """
 
     def decorator(func):
-
         # Sanitize input version
         min_version = (
             sanitize_version_tuple(version)
             if isinstance(version, tuple)
             else version_string_as_tuple(version)
         )
 
@@ -262,15 +260,14 @@
             if not hasattr(self, "_server_version"):
                 raise AttributeError(
                     "Decorated class method must have ``_server_version`` attribute."
                 )
 
             # Raise exceptions if server version is not valid
             if not server_meets_version(self._server_version, min_version):
-
                 # Provide a generic version error message
                 if not VERSION_MAP:
                     raise VersionError(
                         f"Class method ``{func.__name__}`` requires server version >= {version_tuple_as_string(min_version)}."
                     )
 
                 # Provide a better error message if VERSION_MAP is provided
```

### Comparing `pyansys-tools-versioning-0.3.3/PKG-INFO` & `pyansys_tools_versioning-0.4.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,32 +1,32 @@
 Metadata-Version: 2.1
 Name: pyansys-tools-versioning
-Version: 0.3.3
+Version: 0.4.0
 Summary: PyAnsys Tools Versioning.
 Author-email: "ANSYS, Inc." <pyansys.support@ansys.com>
 Maintainer-email: PyAnsys developers <pyansys.maintainers@ansys.com>
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Description-Content-Type: text/x-rst
 Classifier: Development Status :: 4 - Beta
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Dist: importlib-metadata >=4.12.0
-Requires-Dist: ansys_sphinx_theme==0.8.0 ; extra == "doc"
+Requires-Dist: ansys_sphinx_theme==0.9.9 ; extra == "doc"
 Requires-Dist: numpydoc==1.5.0 ; extra == "doc"
-Requires-Dist: Sphinx==5.3.0 ; extra == "doc"
-Requires-Dist: sphinx-autoapi==2.0.0 ; extra == "doc"
-Requires-Dist: Sphinx-copybutton==0.5.1 ; extra == "doc"
-Requires-Dist: hypothesis==6.62.1 ; extra == "tests"
-Requires-Dist: pytest==7.2.1 ; extra == "tests"
-Requires-Dist: pytest-cov==4.0.0 ; extra == "tests"
-Project-URL: Source, https://github.com/pyansys/pyansys-tools-versioning
+Requires-Dist: Sphinx==7.0.1 ; extra == "doc"
+Requires-Dist: sphinx-autoapi==2.1.1 ; extra == "doc"
+Requires-Dist: Sphinx-copybutton==0.5.2 ; extra == "doc"
+Requires-Dist: hypothesis==6.80.0 ; extra == "tests"
+Requires-Dist: pytest==7.4.0 ; extra == "tests"
+Requires-Dist: pytest-cov==4.1.0 ; extra == "tests"
+Project-URL: Source, https://github.com/ansys/pyansys-tools-versioning
 Provides-Extra: doc
 Provides-Extra: tests
 
 PyAnsys Tools Versioning
 ========================
 |pyansys| |python| |pypi| |GH-CI| |codecov| |MIT| |black| |pre-commit|
 
@@ -38,32 +38,32 @@
    :target: https://pypi.org/project/pyansys-tools-versioning
    :alt: Python
 
 .. |pypi| image:: https://img.shields.io/pypi/v/pyansys-tools-versioning.svg?logo=python&logoColor=white
    :target: https://pypi.org/project/pyansys-tools-versioning
    :alt: PyPI
 
-.. |codecov| image:: https://codecov.io/gh/pyansys/pyansys-tools-versioning/branch/main/graph/badge.svg
-   :target: https://codecov.io/gh/pyansys/pyansys-tools-versioning
+.. |codecov| image:: https://codecov.io/gh/ansys/pyansys-tools-versioning/branch/main/graph/badge.svg
+   :target: https://codecov.io/gh/ansys/pyansys-tools-versioning
    :alt: Codecov
 
-.. |GH-CI| image:: https://github.com/pyansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml/badge.svg
-   :target: https://github.com/pyansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml
+.. |GH-CI| image:: https://github.com/ansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml/badge.svg
+   :target: https://github.com/ansys/pyansys-tools-versioning/actions/workflows/ci_cd.yml
    :alt: GH-CI
 
 .. |MIT| image:: https://img.shields.io/badge/License-MIT-yellow.svg
    :target: https://opensource.org/licenses/MIT
    :alt: MIT
 
 .. |black| image:: https://img.shields.io/badge/code%20style-black-000000.svg?style=flat
    :target: https://github.com/psf/black
    :alt: Black
 
-.. |pre-commit| image:: https://results.pre-commit.ci/badge/github/pyansys/pyansys-tools-versioning/main.svg
-   :target: https://results.pre-commit.ci/latest/github/pyansys/pyansys-tools-versioning/main
+.. |pre-commit| image:: https://results.pre-commit.ci/badge/github/ansys/pyansys-tools-versioning/main.svg
+   :target: https://results.pre-commit.ci/latest/github/ansys/pyansys-tools-versioning/main
    :alt: pre-commit.ci status
 
 Utilities for backwards and forwards server support.
 
 
 How to install
 --------------
@@ -95,15 +95,15 @@
 Before contributing to the project, please refer to the `PyAnsys Developer's guide`_. You will 
 need to follow these steps:
 
 1. Start by cloning this repository:
 
     .. code:: bash
 
-        git clone https://github.com/pyansys/pyansys-tools-versioning
+        git clone https://github.com/ansys/pyansys-tools-versioning
 
 2. Create a fresh-clean Python environment and activate it:
 
     .. code:: bash
 
         # Create a virtual environment
         python -m venv .venv
```

