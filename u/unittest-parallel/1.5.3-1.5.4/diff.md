# Comparing `tmp/unittest-parallel-1.5.3.tar.gz` & `tmp/unittest-parallel-1.5.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "unittest-parallel-1.5.3.tar", last modified: Mon Oct 31 17:55:42 2022, max compression
+gzip compressed data, was "unittest-parallel-1.5.4.tar", last modified: Wed Jun 28 14:38:03 2023, max compression
```

## Comparing `unittest-parallel-1.5.3.tar` & `unittest-parallel-1.5.4.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:55:42.073454 unittest-parallel-1.5.3/
--rw-r--r--   0       20 dialout     (20)     1081 2022-10-27 21:45:04.000000 unittest-parallel-1.5.3/LICENSE
--rw-r--r--   0       20 dialout     (20)     7693 2022-10-31 17:55:42.073651 unittest-parallel-1.5.3/PKG-INFO
--rw-r--r--   0       20 dialout     (20)     6804 2022-10-27 21:45:04.000000 unittest-parallel-1.5.3/README.md
--rw-r--r--   0       20 dialout     (20)       50 2022-10-29 19:25:24.000000 unittest-parallel-1.5.3/pyproject.toml
--rw-r--r--   0       20 dialout     (20)     1028 2022-10-31 17:55:42.074470 unittest-parallel-1.5.3/setup.cfg
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:55:42.060057 unittest-parallel-1.5.3/src/
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:55:42.067688 unittest-parallel-1.5.3/src/unittest_parallel/
--rw-r--r--   0       20 dialout     (20)      102 2022-10-27 21:45:04.000000 unittest-parallel-1.5.3/src/unittest_parallel/__init__.py
--rw-r--r--   0       20 dialout     (20)      241 2022-10-27 21:45:04.000000 unittest-parallel-1.5.3/src/unittest_parallel/__main__.py
--rw-r--r--   0       20 dialout     (20)    14453 2022-10-28 21:18:31.000000 unittest-parallel-1.5.3/src/unittest_parallel/main.py
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:55:42.072895 unittest-parallel-1.5.3/src/unittest_parallel.egg-info/
--rw-r--r--   0       20 dialout     (20)     7693 2022-10-31 17:55:42.000000 unittest-parallel-1.5.3/src/unittest_parallel.egg-info/PKG-INFO
--rw-r--r--   0       20 dialout     (20)      412 2022-10-31 17:55:42.000000 unittest-parallel-1.5.3/src/unittest_parallel.egg-info/SOURCES.txt
--rw-r--r--   0       20 dialout     (20)        1 2022-10-31 17:55:42.000000 unittest-parallel-1.5.3/src/unittest_parallel.egg-info/dependency_links.txt
--rw-r--r--   0       20 dialout     (20)       66 2022-10-31 17:55:42.000000 unittest-parallel-1.5.3/src/unittest_parallel.egg-info/entry_points.txt
--rw-r--r--   0       20 dialout     (20)       14 2022-10-31 17:55:42.000000 unittest-parallel-1.5.3/src/unittest_parallel.egg-info/requires.txt
--rw-r--r--   0       20 dialout     (20)       18 2022-10-31 17:55:42.000000 unittest-parallel-1.5.3/src/unittest_parallel.egg-info/top_level.txt
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:38:03.982541 unittest-parallel-1.5.4/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2023-06-11 21:05:16.000000 unittest-parallel-1.5.4/LICENSE
+-rw-r--r--   0 craighobbs   (501) staff       (20)     7804 2023-06-28 14:38:03.982591 unittest-parallel-1.5.4/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)     6914 2023-06-11 21:05:16.000000 unittest-parallel-1.5.4/README.md
+-rw-r--r--   0 craighobbs   (501) staff       (20)       50 2023-06-11 21:05:16.000000 unittest-parallel-1.5.4/pyproject.toml
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1029 2023-06-28 14:38:03.982820 unittest-parallel-1.5.4/setup.cfg
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:38:03.981039 unittest-parallel-1.5.4/src/
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:38:03.981807 unittest-parallel-1.5.4/src/unittest_parallel/
+-rw-r--r--   0 craighobbs   (501) staff       (20)      102 2023-06-11 21:05:16.000000 unittest-parallel-1.5.4/src/unittest_parallel/__init__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)      241 2023-06-11 21:05:16.000000 unittest-parallel-1.5.4/src/unittest_parallel/__main__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    14453 2023-06-11 21:05:16.000000 unittest-parallel-1.5.4/src/unittest_parallel/main.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:38:03.982440 unittest-parallel-1.5.4/src/unittest_parallel.egg-info/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     7804 2023-06-28 14:38:03.000000 unittest-parallel-1.5.4/src/unittest_parallel.egg-info/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)      412 2023-06-28 14:38:03.000000 unittest-parallel-1.5.4/src/unittest_parallel.egg-info/SOURCES.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        1 2023-06-28 14:38:03.000000 unittest-parallel-1.5.4/src/unittest_parallel.egg-info/dependency_links.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       66 2023-06-28 14:38:03.000000 unittest-parallel-1.5.4/src/unittest_parallel.egg-info/entry_points.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       14 2023-06-28 14:38:03.000000 unittest-parallel-1.5.4/src/unittest_parallel.egg-info/requires.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       18 2023-06-28 14:38:03.000000 unittest-parallel-1.5.4/src/unittest_parallel.egg-info/top_level.txt
```

### Comparing `unittest-parallel-1.5.3/LICENSE` & `unittest-parallel-1.5.4/LICENSE`

 * *Files identical despite different names*

### Comparing `unittest-parallel-1.5.3/PKG-INFO` & `unittest-parallel-1.5.4/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,54 +1,62 @@
 Metadata-Version: 2.1
 Name: unittest-parallel
-Version: 1.5.3
+Version: 1.5.4
 Summary: Parallel unit test runner with coverage support
 Home-page: https://github.com/craigahobbs/unittest-parallel
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: test,unittest,coverage,parallel
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Software Development :: Testing
 Classifier: Topic :: Utilities
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # unittest-parallel
 
 [![PyPI - Status](https://img.shields.io/pypi/status/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 [![PyPI](https://img.shields.io/pypi/v/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 [![GitHub](https://img.shields.io/github/license/craigahobbs/unittest-parallel)](https://github.com/craigahobbs/unittest-parallel/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 
 unittest-parallel is a parallel unit test runner for Python with coverage support.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/unittest-parallel)
+
+
+## Run Unit Tests in Parallel
+
 To run unittest-parallel, specify the directory containing your unit tests with the "-s" argument
 and your package's top-level directory using the "-t" argument:
 
-```
+~~~
 unittest-parallel -t . -s tests
-```
+~~~
 
 By default, unittest-parallel runs unit tests on all CPU cores available.
 
 To run your unit tests with coverage, add either the "--coverage" option (for line coverage) or the
 "--coverage-branch" for line and branch coverage.
 
-```
+~~~
 unittest-parallel -t . -s tests --coverage-branch
-```
+~~~
 
 
 ## How it works
 
 unittest-parallel uses Python's built-in unit test discovery to find all test cases in your project.
 It then runs all test cases in a Python multi-processing pool of the requested size.
 
@@ -59,15 +67,15 @@
 Use the "--class-fixtures" option to execute class fixtures correctly. Use the "--module-fixtures"
 option to execute module fixtures correctly. Note that these options reduce the amount of
 parallelism.
 
 
 ## Example output
 
-```
+~~~
 $ unittest-parallel -v -t src -s src/tests --coverage-branch --coverage-fail-under 100
 Running 299 test suites (299 total tests) across 8 processes
 
 test_first_list_then_dict (tests.test_encode.TestDecodeQueryString) ...
 test_first_list_then_dict (tests.test_encode.TestDecodeQueryString) ... ok
 test_compile_stdin (tests.test_main.TestMain) ...
 test_validate_stdin (tests.test_main.TestMain) ...
@@ -100,20 +108,20 @@
 src/tests/test_main.py                 191      0      4      0   100%
 src/tests/test_parser.py               363      0      0      0   100%
 src/tests/test_schema.py               938      0      0      0   100%
 ----------------------------------------------------------------------
 TOTAL                                 2538      0    575      0   100%
 
 Total coverage is 100.00%
-```
+~~~
 
 
 ## Usage
 
-```
+~~~
 usage: unittest-parallel [-h] [-v] [-q] [-f] [-b] [-k TESTNAMEPATTERNS]
                          [-s START] [-p PATTERN] [-t TOP] [-j COUNT]
                          [--class-fixtures] [--module-fixtures]
                          [--disable-process-pooling] [--coverage]
                          [--coverage-branch] [--coverage-rcfile RCFILE]
                          [--coverage-include PAT] [--coverage-omit PAT]
                          [--coverage-source SRC] [--coverage-html DIR]
@@ -155,18 +163,18 @@
   --coverage-source SRC
                         A list of packages or directories of code to be
                         measured
   --coverage-html DIR   Generate coverage HTML report
   --coverage-xml FILE   Generate coverage XML report
   --coverage-fail-under MIN
                         Fail if coverage percentage under min
-```
+~~~
 
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ unittest-parallel/ -k package unittest-parallel -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```

### Comparing `unittest-parallel-1.5.3/README.md` & `unittest-parallel-1.5.4/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -3,29 +3,37 @@
 [![PyPI - Status](https://img.shields.io/pypi/status/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 [![PyPI](https://img.shields.io/pypi/v/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 [![GitHub](https://img.shields.io/github/license/craigahobbs/unittest-parallel)](https://github.com/craigahobbs/unittest-parallel/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 
 unittest-parallel is a parallel unit test runner for Python with coverage support.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/unittest-parallel)
+
+
+## Run Unit Tests in Parallel
+
 To run unittest-parallel, specify the directory containing your unit tests with the "-s" argument
 and your package's top-level directory using the "-t" argument:
 
-```
+~~~
 unittest-parallel -t . -s tests
-```
+~~~
 
 By default, unittest-parallel runs unit tests on all CPU cores available.
 
 To run your unit tests with coverage, add either the "--coverage" option (for line coverage) or the
 "--coverage-branch" for line and branch coverage.
 
-```
+~~~
 unittest-parallel -t . -s tests --coverage-branch
-```
+~~~
 
 
 ## How it works
 
 unittest-parallel uses Python's built-in unit test discovery to find all test cases in your project.
 It then runs all test cases in a Python multi-processing pool of the requested size.
 
@@ -36,15 +44,15 @@
 Use the "--class-fixtures" option to execute class fixtures correctly. Use the "--module-fixtures"
 option to execute module fixtures correctly. Note that these options reduce the amount of
 parallelism.
 
 
 ## Example output
 
-```
+~~~
 $ unittest-parallel -v -t src -s src/tests --coverage-branch --coverage-fail-under 100
 Running 299 test suites (299 total tests) across 8 processes
 
 test_first_list_then_dict (tests.test_encode.TestDecodeQueryString) ...
 test_first_list_then_dict (tests.test_encode.TestDecodeQueryString) ... ok
 test_compile_stdin (tests.test_main.TestMain) ...
 test_validate_stdin (tests.test_main.TestMain) ...
@@ -77,20 +85,20 @@
 src/tests/test_main.py                 191      0      4      0   100%
 src/tests/test_parser.py               363      0      0      0   100%
 src/tests/test_schema.py               938      0      0      0   100%
 ----------------------------------------------------------------------
 TOTAL                                 2538      0    575      0   100%
 
 Total coverage is 100.00%
-```
+~~~
 
 
 ## Usage
 
-```
+~~~
 usage: unittest-parallel [-h] [-v] [-q] [-f] [-b] [-k TESTNAMEPATTERNS]
                          [-s START] [-p PATTERN] [-t TOP] [-j COUNT]
                          [--class-fixtures] [--module-fixtures]
                          [--disable-process-pooling] [--coverage]
                          [--coverage-branch] [--coverage-rcfile RCFILE]
                          [--coverage-include PAT] [--coverage-omit PAT]
                          [--coverage-source SRC] [--coverage-html DIR]
@@ -132,18 +140,18 @@
   --coverage-source SRC
                         A list of packages or directories of code to be
                         measured
   --coverage-html DIR   Generate coverage HTML report
   --coverage-xml FILE   Generate coverage XML report
   --coverage-fail-under MIN
                         Fail if coverage percentage under min
-```
+~~~
 
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ unittest-parallel/ -k package unittest-parallel -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```

### Comparing `unittest-parallel-1.5.3/setup.cfg` & `unittest-parallel-1.5.4/setup.cfg`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 [metadata]
 name = unittest-parallel
-version = 1.5.3
+version = 1.5.4
 url = https://github.com/craigahobbs/unittest-parallel
 author = Craig A. Hobbs
 author_email = craigahobbs@gmail.com
 license = MIT
 description = Parallel unit test runner with coverage support
 long_description = file:README.md
 long_description_content_type = text/markdown
 keywords = test, unittest, coverage, parallel
 classifiers = 
 	Development Status :: 5 - Production/Stable
 	Intended Audience :: Developers
 	License :: OSI Approved :: MIT License
 	Operating System :: OS Independent
-	Programming Language :: Python :: 3.7
 	Programming Language :: Python :: 3.8
 	Programming Language :: Python :: 3.9
 	Programming Language :: Python :: 3.10
 	Programming Language :: Python :: 3.11
+	Programming Language :: Python :: 3.12
 	Topic :: Software Development :: Testing
 	Topic :: Utilities
 
 [options]
 packages = unittest_parallel
 package_dir = 
 	= src
```

### Comparing `unittest-parallel-1.5.3/src/unittest_parallel/main.py` & `unittest-parallel-1.5.4/src/unittest_parallel/main.py`

 * *Files identical despite different names*

### Comparing `unittest-parallel-1.5.3/src/unittest_parallel.egg-info/PKG-INFO` & `unittest-parallel-1.5.4/src/unittest_parallel.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,54 +1,62 @@
 Metadata-Version: 2.1
 Name: unittest-parallel
-Version: 1.5.3
+Version: 1.5.4
 Summary: Parallel unit test runner with coverage support
 Home-page: https://github.com/craigahobbs/unittest-parallel
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: test,unittest,coverage,parallel
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Software Development :: Testing
 Classifier: Topic :: Utilities
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # unittest-parallel
 
 [![PyPI - Status](https://img.shields.io/pypi/status/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 [![PyPI](https://img.shields.io/pypi/v/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 [![GitHub](https://img.shields.io/github/license/craigahobbs/unittest-parallel)](https://github.com/craigahobbs/unittest-parallel/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/unittest-parallel)](https://pypi.org/project/unittest-parallel/)
 
 unittest-parallel is a parallel unit test runner for Python with coverage support.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/unittest-parallel)
+
+
+## Run Unit Tests in Parallel
+
 To run unittest-parallel, specify the directory containing your unit tests with the "-s" argument
 and your package's top-level directory using the "-t" argument:
 
-```
+~~~
 unittest-parallel -t . -s tests
-```
+~~~
 
 By default, unittest-parallel runs unit tests on all CPU cores available.
 
 To run your unit tests with coverage, add either the "--coverage" option (for line coverage) or the
 "--coverage-branch" for line and branch coverage.
 
-```
+~~~
 unittest-parallel -t . -s tests --coverage-branch
-```
+~~~
 
 
 ## How it works
 
 unittest-parallel uses Python's built-in unit test discovery to find all test cases in your project.
 It then runs all test cases in a Python multi-processing pool of the requested size.
 
@@ -59,15 +67,15 @@
 Use the "--class-fixtures" option to execute class fixtures correctly. Use the "--module-fixtures"
 option to execute module fixtures correctly. Note that these options reduce the amount of
 parallelism.
 
 
 ## Example output
 
-```
+~~~
 $ unittest-parallel -v -t src -s src/tests --coverage-branch --coverage-fail-under 100
 Running 299 test suites (299 total tests) across 8 processes
 
 test_first_list_then_dict (tests.test_encode.TestDecodeQueryString) ...
 test_first_list_then_dict (tests.test_encode.TestDecodeQueryString) ... ok
 test_compile_stdin (tests.test_main.TestMain) ...
 test_validate_stdin (tests.test_main.TestMain) ...
@@ -100,20 +108,20 @@
 src/tests/test_main.py                 191      0      4      0   100%
 src/tests/test_parser.py               363      0      0      0   100%
 src/tests/test_schema.py               938      0      0      0   100%
 ----------------------------------------------------------------------
 TOTAL                                 2538      0    575      0   100%
 
 Total coverage is 100.00%
-```
+~~~
 
 
 ## Usage
 
-```
+~~~
 usage: unittest-parallel [-h] [-v] [-q] [-f] [-b] [-k TESTNAMEPATTERNS]
                          [-s START] [-p PATTERN] [-t TOP] [-j COUNT]
                          [--class-fixtures] [--module-fixtures]
                          [--disable-process-pooling] [--coverage]
                          [--coverage-branch] [--coverage-rcfile RCFILE]
                          [--coverage-include PAT] [--coverage-omit PAT]
                          [--coverage-source SRC] [--coverage-html DIR]
@@ -155,18 +163,18 @@
   --coverage-source SRC
                         A list of packages or directories of code to be
                         measured
   --coverage-html DIR   Generate coverage HTML report
   --coverage-xml FILE   Generate coverage XML report
   --coverage-fail-under MIN
                         Fail if coverage percentage under min
-```
+~~~
 
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ unittest-parallel/ -k package unittest-parallel -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```

