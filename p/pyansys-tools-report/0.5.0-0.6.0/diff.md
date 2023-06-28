# Comparing `tmp/pyansys-tools-report-0.5.0.tar.gz` & `tmp/pyansys_tools_report-0.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyansys-tools-report-0.5.0.tar", last modified: Mon Jan  2 16:03:19 2023, max compression
+gzip compressed data, was "pyansys_tools_report-0.6.0.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
```

## Comparing `pyansys-tools-report-0.5.0.tar` & `pyansys_tools_report-0.6.0.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1089 2023-01-02 16:03:06.370153 pyansys-tools-report-0.5.0/LICENSE
--rw-r--r--   0        0        0     6620 2023-01-02 16:03:06.370153 pyansys-tools-report-0.5.0/README.md
--rw-r--r--   0        0        0     1717 2023-01-02 16:03:06.374153 pyansys-tools-report-0.5.0/pyproject.toml
--rw-r--r--   0        0        0      208 2023-01-02 16:03:06.374153 pyansys-tools-report-0.5.0/src/ansys/tools/report/__init__.py
--rw-r--r--   0        0        0      451 2023-01-02 16:03:06.374153 pyansys-tools-report-0.5.0/src/ansys/tools/report/_version.py
--rw-r--r--   0        0        0     6387 2023-01-02 16:03:06.374153 pyansys-tools-report-0.5.0/src/ansys/tools/report/report.py
--rw-r--r--   0        0        0     7831 1970-01-01 00:00:00.000000 pyansys-tools-report-0.5.0/PKG-INFO
+-rw-r--r--   0        0        0     1089 2023-06-28 06:45:01.107393 pyansys_tools_report-0.6.0/LICENSE
+-rw-r--r--   0        0        0     6908 2023-06-28 06:45:01.107393 pyansys_tools_report-0.6.0/README.md
+-rw-r--r--   0        0        0     1715 2023-06-28 06:45:01.107393 pyansys_tools_report-0.6.0/pyproject.toml
+-rw-r--r--   0        0        0      208 2023-06-28 06:45:01.107393 pyansys_tools_report-0.6.0/src/ansys/tools/report/__init__.py
+-rw-r--r--   0        0        0      451 2023-06-28 06:45:01.107393 pyansys_tools_report-0.6.0/src/ansys/tools/report/_version.py
+-rw-r--r--   0        0        0     6387 2023-06-28 06:45:01.107393 pyansys_tools_report-0.6.0/src/ansys/tools/report/report.py
+-rw-r--r--   0        0        0     8117 1970-01-01 00:00:00.000000 pyansys_tools_report-0.6.0/PKG-INFO
```

### Comparing `pyansys-tools-report-0.5.0/LICENSE` & `pyansys_tools_report-0.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pyansys-tools-report-0.5.0/README.md` & `pyansys_tools_report-0.6.0/README.md`

 * *Files 7% similar despite different names*

```diff
@@ -1,30 +1,34 @@
 # PyAnsys Tools Report
 
 [![PyAnsys](https://img.shields.io/badge/Py-Ansys-ffc107.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAIAAACQkWg2AAABDklEQVQ4jWNgoDfg5mD8vE7q/3bpVyskbW0sMRUwofHD7Dh5OBkZGBgW7/3W2tZpa2tLQEOyOzeEsfumlK2tbVpaGj4N6jIs1lpsDAwMJ278sveMY2BgCA0NFRISwqkhyQ1q/Nyd3zg4OBgYGNjZ2ePi4rB5loGBhZnhxTLJ/9ulv26Q4uVk1NXV/f///////69du4Zdg78lx//t0v+3S88rFISInD59GqIH2esIJ8G9O2/XVwhjzpw5EAam1xkkBJn/bJX+v1365hxxuCAfH9+3b9/+////48cPuNehNsS7cDEzMTAwMMzb+Q2u4dOnT2vWrMHu9ZtzxP9vl/69RVpCkBlZ3N7enoDXBwEAAA+YYitOilMVAAAAAElFTkSuQmCC)](https://docs.pyansys.com/)
 [![Python](https://img.shields.io/pypi/pyversions/pyansys-tools-report?logo=pypi)](https://pypi.org/project/pyansys-tools-report/)
 [![PyPi](https://img.shields.io/pypi/v/pyansys-tools-report.svg?logo=python&logoColor=white)](https://pypi.org/project/pyansys-tools-report)
-[![codecov](https://codecov.io/gh/pyansys/pyansys-tools-report/branch/main/graph/badge.svg)](https://codecov.io/gh/pyansys/pyansys-tools-report)
-[![GH-CI](https://github.com/pyansys/pyansys-tools-report/actions/workflows/ci.yml/badge.svg)](https://github.com/pyansys/pyansys-tools-report/actions/workflows/ci.yml)
+[![codecov](https://codecov.io/gh/ansys/pyansys-tools-report/branch/main/graph/badge.svg)](https://codecov.io/gh/ansys/pyansys-tools-report)
+[![GH-CI](https://github.com/ansys/pyansys-tools-report/actions/workflows/ci.yml/badge.svg)](https://github.com/ansys/pyansys-tools-report/actions/workflows/ci.yml)
 [![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 [![Black](https://img.shields.io/badge/code%20style-black-000000.svg?style=flat)](https://github.com/psf/black)
+[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/ansys/pyansys-tools-report/main.svg)](https://results.pre-commit.ci/latest/github/ansys/pyansys-tools-report/main)
 
 Ansys tool for reporting your Python environment's package versions and hardware resources in a standardized way.
 
 ## Table of contents
 
 <!--ts-->
-   * [Introduction](#introduction)
-   * [Documentation and issues](#documentation-and-issues)
-   * [How does it work?](#how-does-it-work)
-   * [Installation](#installation)
-      * [Offline Installation](#offline-installation)
-   * [Rendering the docs](#rendering-the-docs)
-   * [Running the tests](#running-the-tests)
-   * [Requirements](#requirements)
+- [PyAnsys Tools Report](#pyansys-tools-report)
+  - [Table of contents](#table-of-contents)
+  - [Introduction](#introduction)
+  - [Documentation and issues](#documentation-and-issues)
+  - [How does it work?](#how-does-it-work)
+  - [Installation](#installation)
+    - [Standard installation](#standard-installation)
+    - [Offline installation](#offline-installation)
+  - [Rendering the docs](#rendering-the-docs)
+  - [Running the tests](#running-the-tests)
+  - [Requirements](#requirements)
 <!--te-->
 
 
 ## Introduction
 The PyAnsys Tools Report is a PyAnsys package to homogenize among all the different repositories
 the output of system and environment reports related to Ansys products. Its main goals are:
 
@@ -35,78 +39,78 @@
 any proposal you may have.
 
 ## Documentation and issues
 
 See the [documentation](https://report.tools.docs.pyansys.com/) page for more details.
 
 You are welcome to help contribute to it in any possible way. Please submit
-[here](https://github.com/pyansys/pyansys-tools-report/issues) an issue with
+[here](https://github.com/ansys/pyansys-tools-report/issues) an issue with
 any proposal you may have. This is the best place to post questions and code.
 
 ## How does it work?
 This repository basically contains a simple Python package which you can import as follows
 (once installed):
 
 ```python
-    import ansys.tools.report as pyansys_report
+import ansys.tools.report as pyansys_report
 ```
 
 Once imported, you can then start playing around with it:
 
 ```python
-    # Instantiate a "default" Report
-    rep = pyansys_report.Report()
+# Instantiate a "default" Report
+rep = pyansys_report.Report()
 ```
 
 Refer to the [online documentation](https://report.tools.docs.pyansys.com/) to see the details of the module.
 
 ## Installation
 
 This package may be installed following two procedures: either the pip package manager installation or
 the manual installation. The process to be followed for each of them is shown in the upcoming sections.
 
-The ``pyansys-tools-report`` package currently supports Python >=3.7 on Windows, Mac OS, and Linux.
+The ``pyansys-tools-report`` package currently supports Python >=3.8 on Windows, Mac OS, and Linux.
 
 ### Standard installation
 Install the latest release from [PyPi](https://pypi.org/project/pyansys-tools-report) with:
 
 ```bash
    pip install pyansys-tools-report
 ```
 
 Alternatively, install the latest from GitHub via:
 
 ```bash
-   pip install git+https://github.com/pyansys/pyansys-tools-report.git
+   pip install git+https://github.com/ansys/pyansys-tools-report.git
 ```
 
 For a local "development" version, install with (requires pip >= 22.0):
 
 ```bash
-   git clone https://github.com/pyansys/pyansys-tools-report.git
+   git clone https://github.com/ansys/pyansys-tools-report.git
    cd pyansys-tools-report
    pip install .
 ```
 
 
 ### Offline installation
 
 If you lack an internet connection on your install machine, the recommended way
 of installing PyAnsys Tools Report is downloading the wheelhouse archive from the
-[Releases Page](https://github.com/pyansys/pyansys-tools-report/releases) for your
+[Releases Page](https://github.com/ansys/pyansys-tools-report/releases) for your
 corresponding machine architecture.
 
 Each wheelhouse archive contains all the python wheels necessary to install
-PyAnsys Tools Report from scratch on Windows and Linux for Python >=3.7. You can install
+PyAnsys Tools Report from scratch on Windows and Linux for Python >=3.8. You can install
 this on an isolated system with a fresh python or on a virtual environment.
 
-For example, on Linux with Python 3.7, unzip it and install it with the following:
+For example, on Linux with Python 3.8, unzip it and install it with the following:
 
 ```bash
-   unzip pyansys-tools-report-v0.5.0-wheelhouse-Linux-3.7.zip wheelhouse
+   unzip pyansys-tools-report-v0.6.0-wheelhouse-Linux-3.8.zip wheelhouse
    pip install pyansys-tools-report -f wheelhouse --no-index --upgrade --ignore-installed
 ```
 
 If you're on Windows with Python 3.9, unzip to a ``wheelhouse`` directory and
 install using the same command as before.
 
 Consider installing using a [virtual environment](https://docs.python.org/3/library/venv.html).
@@ -115,15 +119,15 @@
 
 ## Rendering the docs
 
 In case you were interested in rendering the docs locally, you need to clone the repository and
 install the docs requirements first:
 
 ```bash
-   git clone https://github.com/pyansys/pyansys-tools-report.git
+   git clone https://github.com/ansys/pyansys-tools-report.git
    cd pyansys-tools-report
    pip install -e .[doc]
 ```
 
 Once you have the requirements, render the docs by running the following:
 
 ```bash
@@ -144,15 +148,15 @@
 
 ## Running the tests
 
 In case you were interested in running the tests locally, you need to clone the repository and
 install the test requirements first:
 
 ```bash
-   git clone https://github.com/pyansys/pyansys-tools-report.git
+   git clone https://github.com/ansys/pyansys-tools-report.git
    cd pyansys-tools-report
    pip install -e .[test]
 ```
 
 Once you have the requirements, run the tests by running the following:
 
 ```bash
```

### Comparing `pyansys-tools-report-0.5.0/pyproject.toml` & `pyansys_tools_report-0.6.0/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,58 +1,58 @@
 [build-system]
 requires = ["flit_core >=3.2,<4"]
 build-backend = "flit_core.buildapi"
 
 [project]
 # Check https://flit.readthedocs.io/en/latest/pyproject_toml.html for all available sections
 name = "pyansys-tools-report"
-version = "0.5.0"
+version = "0.6.0"
 dynamic = ["description"]
 readme = "README.md"
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
     "scooby>=0.5.12",
     "pyvista>=0.34.1",
 ]
 
 [project.optional-dependencies]
 tests = [
-    "pytest==7.2.0",
-    "pytest-cov==4.0.0",
+    "pytest==7.4.0",
+    "pytest-cov==4.1.0",
 ]
 doc = [
-    "ansys_sphinx_theme==0.8.0",
+    "ansys_sphinx_theme==0.9.9",
     "numpydoc==1.5.0",
-    "Sphinx==5.3.0",
-    "Sphinx-copybutton==0.5.1",
-    "myst-parser==0.18.1",
+    "Sphinx==7.0.1",
+    "Sphinx-copybutton==0.5.2",
+    "myst-parser==2.0.0",
 ]
 
 [tool.flit.module]
 name = "ansys.tools.report"
 
 [project.urls]
-Source = "https://github.com/pyansys/pyansys-tools-report"
+Source = "https://github.com/ansys/pyansys-tools-report"
 
 [tool.black]
 line-length = 100
 
 [tool.isort]
 profile = "black"
 force_sort_within_sections = true
```

### Comparing `pyansys-tools-report-0.5.0/src/ansys/tools/report/report.py` & `pyansys_tools_report-0.6.0/src/ansys/tools/report/report.py`

 * *Files identical despite different names*

### Comparing `pyansys-tools-report-0.5.0/PKG-INFO` & `pyansys_tools_report-0.6.0/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,59 +1,63 @@
 Metadata-Version: 2.1
 Name: pyansys-tools-report
-Version: 0.5.0
+Version: 0.6.0
 Summary: PyAnsys Tools Report package.
 Author-email: "ANSYS, Inc." <pyansys.support@ansys.com>
 Maintainer-email: PyAnsys developers <pyansys.maintainers@ansys.com>
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 Classifier: Development Status :: 4 - Beta
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Dist: importlib-metadata >=4.12.0
 Requires-Dist: scooby>=0.5.12
 Requires-Dist: pyvista>=0.34.1
-Requires-Dist: ansys_sphinx_theme==0.8.0 ; extra == "doc"
+Requires-Dist: ansys_sphinx_theme==0.9.9 ; extra == "doc"
 Requires-Dist: numpydoc==1.5.0 ; extra == "doc"
-Requires-Dist: Sphinx==5.3.0 ; extra == "doc"
-Requires-Dist: Sphinx-copybutton==0.5.1 ; extra == "doc"
-Requires-Dist: myst-parser==0.18.1 ; extra == "doc"
-Requires-Dist: pytest==7.2.0 ; extra == "tests"
-Requires-Dist: pytest-cov==4.0.0 ; extra == "tests"
-Project-URL: Source, https://github.com/pyansys/pyansys-tools-report
+Requires-Dist: Sphinx==7.0.1 ; extra == "doc"
+Requires-Dist: Sphinx-copybutton==0.5.2 ; extra == "doc"
+Requires-Dist: myst-parser==2.0.0 ; extra == "doc"
+Requires-Dist: pytest==7.4.0 ; extra == "tests"
+Requires-Dist: pytest-cov==4.1.0 ; extra == "tests"
+Project-URL: Source, https://github.com/ansys/pyansys-tools-report
 Provides-Extra: doc
 Provides-Extra: tests
 
 # PyAnsys Tools Report
 
 [![PyAnsys](https://img.shields.io/badge/Py-Ansys-ffc107.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAIAAACQkWg2AAABDklEQVQ4jWNgoDfg5mD8vE7q/3bpVyskbW0sMRUwofHD7Dh5OBkZGBgW7/3W2tZpa2tLQEOyOzeEsfumlK2tbVpaGj4N6jIs1lpsDAwMJ278sveMY2BgCA0NFRISwqkhyQ1q/Nyd3zg4OBgYGNjZ2ePi4rB5loGBhZnhxTLJ/9ulv26Q4uVk1NXV/f///////69du4Zdg78lx//t0v+3S88rFISInD59GqIH2esIJ8G9O2/XVwhjzpw5EAam1xkkBJn/bJX+v1365hxxuCAfH9+3b9/+////48cPuNehNsS7cDEzMTAwMMzb+Q2u4dOnT2vWrMHu9ZtzxP9vl/69RVpCkBlZ3N7enoDXBwEAAA+YYitOilMVAAAAAElFTkSuQmCC)](https://docs.pyansys.com/)
 [![Python](https://img.shields.io/pypi/pyversions/pyansys-tools-report?logo=pypi)](https://pypi.org/project/pyansys-tools-report/)
 [![PyPi](https://img.shields.io/pypi/v/pyansys-tools-report.svg?logo=python&logoColor=white)](https://pypi.org/project/pyansys-tools-report)
-[![codecov](https://codecov.io/gh/pyansys/pyansys-tools-report/branch/main/graph/badge.svg)](https://codecov.io/gh/pyansys/pyansys-tools-report)
-[![GH-CI](https://github.com/pyansys/pyansys-tools-report/actions/workflows/ci.yml/badge.svg)](https://github.com/pyansys/pyansys-tools-report/actions/workflows/ci.yml)
+[![codecov](https://codecov.io/gh/ansys/pyansys-tools-report/branch/main/graph/badge.svg)](https://codecov.io/gh/ansys/pyansys-tools-report)
+[![GH-CI](https://github.com/ansys/pyansys-tools-report/actions/workflows/ci.yml/badge.svg)](https://github.com/ansys/pyansys-tools-report/actions/workflows/ci.yml)
 [![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 [![Black](https://img.shields.io/badge/code%20style-black-000000.svg?style=flat)](https://github.com/psf/black)
+[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/ansys/pyansys-tools-report/main.svg)](https://results.pre-commit.ci/latest/github/ansys/pyansys-tools-report/main)
 
 Ansys tool for reporting your Python environment's package versions and hardware resources in a standardized way.
 
 ## Table of contents
 
 <!--ts-->
-   * [Introduction](#introduction)
-   * [Documentation and issues](#documentation-and-issues)
-   * [How does it work?](#how-does-it-work)
-   * [Installation](#installation)
-      * [Offline Installation](#offline-installation)
-   * [Rendering the docs](#rendering-the-docs)
-   * [Running the tests](#running-the-tests)
-   * [Requirements](#requirements)
+- [PyAnsys Tools Report](#pyansys-tools-report)
+  - [Table of contents](#table-of-contents)
+  - [Introduction](#introduction)
+  - [Documentation and issues](#documentation-and-issues)
+  - [How does it work?](#how-does-it-work)
+  - [Installation](#installation)
+    - [Standard installation](#standard-installation)
+    - [Offline installation](#offline-installation)
+  - [Rendering the docs](#rendering-the-docs)
+  - [Running the tests](#running-the-tests)
+  - [Requirements](#requirements)
 <!--te-->
 
 
 ## Introduction
 The PyAnsys Tools Report is a PyAnsys package to homogenize among all the different repositories
 the output of system and environment reports related to Ansys products. Its main goals are:
 
@@ -64,78 +68,78 @@
 any proposal you may have.
 
 ## Documentation and issues
 
 See the [documentation](https://report.tools.docs.pyansys.com/) page for more details.
 
 You are welcome to help contribute to it in any possible way. Please submit
-[here](https://github.com/pyansys/pyansys-tools-report/issues) an issue with
+[here](https://github.com/ansys/pyansys-tools-report/issues) an issue with
 any proposal you may have. This is the best place to post questions and code.
 
 ## How does it work?
 This repository basically contains a simple Python package which you can import as follows
 (once installed):
 
 ```python
-    import ansys.tools.report as pyansys_report
+import ansys.tools.report as pyansys_report
 ```
 
 Once imported, you can then start playing around with it:
 
 ```python
-    # Instantiate a "default" Report
-    rep = pyansys_report.Report()
+# Instantiate a "default" Report
+rep = pyansys_report.Report()
 ```
 
 Refer to the [online documentation](https://report.tools.docs.pyansys.com/) to see the details of the module.
 
 ## Installation
 
 This package may be installed following two procedures: either the pip package manager installation or
 the manual installation. The process to be followed for each of them is shown in the upcoming sections.
 
-The ``pyansys-tools-report`` package currently supports Python >=3.7 on Windows, Mac OS, and Linux.
+The ``pyansys-tools-report`` package currently supports Python >=3.8 on Windows, Mac OS, and Linux.
 
 ### Standard installation
 Install the latest release from [PyPi](https://pypi.org/project/pyansys-tools-report) with:
 
 ```bash
    pip install pyansys-tools-report
 ```
 
 Alternatively, install the latest from GitHub via:
 
 ```bash
-   pip install git+https://github.com/pyansys/pyansys-tools-report.git
+   pip install git+https://github.com/ansys/pyansys-tools-report.git
 ```
 
 For a local "development" version, install with (requires pip >= 22.0):
 
 ```bash
-   git clone https://github.com/pyansys/pyansys-tools-report.git
+   git clone https://github.com/ansys/pyansys-tools-report.git
    cd pyansys-tools-report
    pip install .
 ```
 
 
 ### Offline installation
 
 If you lack an internet connection on your install machine, the recommended way
 of installing PyAnsys Tools Report is downloading the wheelhouse archive from the
-[Releases Page](https://github.com/pyansys/pyansys-tools-report/releases) for your
+[Releases Page](https://github.com/ansys/pyansys-tools-report/releases) for your
 corresponding machine architecture.
 
 Each wheelhouse archive contains all the python wheels necessary to install
-PyAnsys Tools Report from scratch on Windows and Linux for Python >=3.7. You can install
+PyAnsys Tools Report from scratch on Windows and Linux for Python >=3.8. You can install
 this on an isolated system with a fresh python or on a virtual environment.
 
-For example, on Linux with Python 3.7, unzip it and install it with the following:
+For example, on Linux with Python 3.8, unzip it and install it with the following:
 
 ```bash
-   unzip pyansys-tools-report-v0.5.0-wheelhouse-Linux-3.7.zip wheelhouse
+   unzip pyansys-tools-report-v0.6.0-wheelhouse-Linux-3.8.zip wheelhouse
    pip install pyansys-tools-report -f wheelhouse --no-index --upgrade --ignore-installed
 ```
 
 If you're on Windows with Python 3.9, unzip to a ``wheelhouse`` directory and
 install using the same command as before.
 
 Consider installing using a [virtual environment](https://docs.python.org/3/library/venv.html).
@@ -144,15 +148,15 @@
 
 ## Rendering the docs
 
 In case you were interested in rendering the docs locally, you need to clone the repository and
 install the docs requirements first:
 
 ```bash
-   git clone https://github.com/pyansys/pyansys-tools-report.git
+   git clone https://github.com/ansys/pyansys-tools-report.git
    cd pyansys-tools-report
    pip install -e .[doc]
 ```
 
 Once you have the requirements, render the docs by running the following:
 
 ```bash
@@ -173,15 +177,15 @@
 
 ## Running the tests
 
 In case you were interested in running the tests locally, you need to clone the repository and
 install the test requirements first:
 
 ```bash
-   git clone https://github.com/pyansys/pyansys-tools-report.git
+   git clone https://github.com/ansys/pyansys-tools-report.git
    cd pyansys-tools-report
    pip install -e .[test]
 ```
 
 Once you have the requirements, run the tests by running the following:
 
 ```bash
```

