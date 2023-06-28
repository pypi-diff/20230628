# Comparing `tmp/cardutil-0.6.1.tar.gz` & `tmp/cardutil-0.6.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cardutil-0.6.1.tar", last modified: Fri Feb 17 22:53:51 2023, max compression
+gzip compressed data, was "cardutil-0.6.3.tar", last modified: Wed Jun 28 12:19:56 2023, max compression
```

## Comparing `cardutil-0.6.1.tar` & `cardutil-0.6.3.tar`

### file list

```diff
@@ -1,54 +1,54 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:51.572074 cardutil-0.6.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-02-17 22:53:38.000000 cardutil-0.6.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     3191 2023-02-17 22:53:51.572074 cardutil-0.6.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2522 2023-02-17 22:53:38.000000 cardutil-0.6.1/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:51.564073 cardutil-0.6.1/cardutil/
--rw-r--r--   0 runner    (1001) docker     (123)     1419 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/BitArray.py
--rw-r--r--   0 runner    (1001) docker     (123)      528 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1494 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/card.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:51.568073 cardutil-0.6.1/cardutil/cli/
--rw-r--r--   0 runner    (1001) docker     (123)     2034 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2101 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/mci_csv_to_ipm.py
--rw-r--r--   0 runner    (1001) docker     (123)     2316 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/mci_ipm_encode.py
--rw-r--r--   0 runner    (1001) docker     (123)     2585 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/mci_ipm_param_encode.py
--rw-r--r--   0 runner    (1001) docker     (123)     2042 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/mci_ipm_param_to_csv.py
--rw-r--r--   0 runner    (1001) docker     (123)     3070 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/mci_ipm_to_csv.py
--rw-r--r--   0 runner    (1001) docker     (123)     6348 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/mideu.py
--rw-r--r--   0 runner    (1001) docker     (123)     2779 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/cli/paramconv.py
--rw-r--r--   0 runner    (1001) docker     (123)    12715 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/config.py
--rw-r--r--   0 runner    (1001) docker     (123)    20463 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/iso8583.py
--rw-r--r--   0 runner    (1001) docker     (123)     1956 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/key.py
--rw-r--r--   0 runner    (1001) docker     (123)    22724 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/mciipm.py
--rw-r--r--   0 runner    (1001) docker     (123)    12518 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/pinblock.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:51.568073 cardutil-0.6.1/cardutil/vendor/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/vendor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16848 2023-02-17 22:53:38.000000 cardutil-0.6.1/cardutil/vendor/hexdump.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:51.568073 cardutil-0.6.1/cardutil.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     3191 2023-02-17 22:53:51.000000 cardutil-0.6.1/cardutil.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1142 2023-02-17 22:53:51.000000 cardutil-0.6.1/cardutil.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-02-17 22:53:51.000000 cardutil-0.6.1/cardutil.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      399 2023-02-17 22:53:51.000000 cardutil-0.6.1/cardutil.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      141 2023-02-17 22:53:51.000000 cardutil-0.6.1/cardutil.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-02-17 22:53:51.000000 cardutil-0.6.1/cardutil.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-02-17 22:53:38.000000 cardutil-0.6.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     1625 2023-02-17 22:53:51.576074 cardutil-0.6.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-02-17 22:53:38.000000 cardutil-0.6.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:51.572074 cardutil-0.6.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:51.572074 cardutil-0.6.1/tests/cli/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1930 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_get_config.py
--rw-r--r--   0 runner    (1001) docker     (123)      868 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_init.py
--rw-r--r--   0 runner    (1001) docker     (123)     7399 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_mci_csv_to_ipm.py
--rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_mci_ipm_encode.py
--rw-r--r--   0 runner    (1001) docker     (123)     3624 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_mci_ipm_param_encode.py
--rw-r--r--   0 runner    (1001) docker     (123)     6552 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_mci_ipm_param_to_csv.py
--rw-r--r--   0 runner    (1001) docker     (123)     4360 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_mci_ipm_to_csv.py
--rw-r--r--   0 runner    (1001) docker     (123)     4880 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_mideu.py
--rw-r--r--   0 runner    (1001) docker     (123)     3347 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/cli/test_paramconv.py
--rw-r--r--   0 runner    (1001) docker     (123)      574 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/test_bitarray.py
--rw-r--r--   0 runner    (1001) docker     (123)      608 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/test_card.py
--rw-r--r--   0 runner    (1001) docker     (123)    16518 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/test_iso8583.py
--rw-r--r--   0 runner    (1001) docker     (123)     1059 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/test_key.py
--rw-r--r--   0 runner    (1001) docker     (123)    12182 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/test_mciipm.py
--rw-r--r--   0 runner    (1001) docker     (123)     4110 2023-02-17 22:53:38.000000 cardutil-0.6.1/tests/test_pinblock.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:56.685265 cardutil-0.6.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-06-28 12:19:44.000000 cardutil-0.6.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     3417 2023-06-28 12:19:56.685265 cardutil-0.6.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2747 2023-06-28 12:19:44.000000 cardutil-0.6.3/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:56.681265 cardutil-0.6.3/cardutil/
+-rw-r--r--   0 runner    (1001) docker     (123)     1419 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/BitArray.py
+-rw-r--r--   0 runner    (1001) docker     (123)      528 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1494 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/card.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:56.685265 cardutil-0.6.3/cardutil/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)     2034 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2184 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/mci_csv_to_ipm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2316 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/mci_ipm_encode.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2585 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/mci_ipm_param_encode.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2042 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/mci_ipm_param_to_csv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3070 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/mci_ipm_to_csv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6348 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/mideu.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2779 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/cli/paramconv.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12715 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/config.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20463 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/iso8583.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1956 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/key.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22724 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/mciipm.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12518 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/pinblock.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:56.685265 cardutil-0.6.3/cardutil/vendor/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/vendor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16848 2023-06-28 12:19:44.000000 cardutil-0.6.3/cardutil/vendor/hexdump.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:56.681265 cardutil-0.6.3/cardutil.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3417 2023-06-28 12:19:56.000000 cardutil-0.6.3/cardutil.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1142 2023-06-28 12:19:56.000000 cardutil-0.6.3/cardutil.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 12:19:56.000000 cardutil-0.6.3/cardutil.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      399 2023-06-28 12:19:56.000000 cardutil-0.6.3/cardutil.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      141 2023-06-28 12:19:56.000000 cardutil-0.6.3/cardutil.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-28 12:19:56.000000 cardutil-0.6.3/cardutil.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 12:19:44.000000 cardutil-0.6.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     1626 2023-06-28 12:19:56.689265 cardutil-0.6.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 12:19:44.000000 cardutil-0.6.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:56.685265 cardutil-0.6.3/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:56.685265 cardutil-0.6.3/tests/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1930 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_get_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)      868 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_init.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8179 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_mci_csv_to_ipm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_mci_ipm_encode.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3624 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_mci_ipm_param_encode.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6552 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_mci_ipm_param_to_csv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4360 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_mci_ipm_to_csv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4880 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_mideu.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3347 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/cli/test_paramconv.py
+-rw-r--r--   0 runner    (1001) docker     (123)      574 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/test_bitarray.py
+-rw-r--r--   0 runner    (1001) docker     (123)      608 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/test_card.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16518 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/test_iso8583.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1059 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/test_key.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12182 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/test_mciipm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4110 2023-06-28 12:19:44.000000 cardutil-0.6.3/tests/test_pinblock.py
```

### Comparing `cardutil-0.6.1/LICENSE` & `cardutil-0.6.3/LICENSE`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/PKG-INFO` & `cardutil-0.6.3/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 Metadata-Version: 2.1
 Name: cardutil
-Version: 0.6.1
+Version: 0.6.3
 Summary: 'Python package for working with payment card systems'
 Home-page: https://github.com/adelosa/cardutil
 Author: Anthony Delosa
 Author-email: adelosa@gmail.com
 License: MIT
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: docs
 Provides-Extra: test
 Provides-Extra: crypto
 License-File: LICENSE
 
 ========
 cardutil
@@ -48,17 +48,22 @@
         :target: https://pypi.org/project/cardutil
         :alt: Downloads per month
 
 .. image:: https://img.shields.io/pypi/pyversions/cardutil.svg
         :target: https://pypi.org/project/cardutil
         :alt: Python versions
 
-.. image:: https://readthedocs.org/projects/cardutil/badge/?version=latest
-        :target: https://cardutil.readthedocs.io/en/latest/?badge=latest
-        :alt: Documentation Status
+.. image:: https://img.shields.io/github/actions/workflow/status/adelosa/cardutil/docs.yml?event=push&label=doc%20build
+        :target: https://adelosa.github.io/cardutil
+        :alt: doc build
+
+.. image:: https://snyk.io/advisor/python/cardutil/badge.svg
+        :target: https://snyk.io/advisor/python/cardutil
+        :alt: snyk package health
+
 
 Features
 ========
 * ISO8583 message parsing
 * Mastercard IPM file reader/writer/encoder
 * Check digit calculator
 * Encrypted pin block generator
@@ -75,15 +80,15 @@
 Information
 ===========
 * Supports python 3.7 and later.
 * Pythonic programmer interfaces
 * Core library has **zero** package dependencies.
 * Low memory usage
 * Download from `pypi <https://pypi.org/project/cardutil/>`_
-* Documentation available at  `readthedocs <https://cardutil.readthedocs.io/en/latest/>`_
+* Documentation available at `Read The Docs <https://cardutil.readthedocs.io/en/latest/>`_ and `GitHub Pages <https://adelosa.github.io/cardutil>`_
 * Source hosted at `GitHub <https://github.com/adelosa/cardutil>`_
 
 Acknowledgements
 ================
 The python `hexdump` library is embedded in this package. Many thank to Anatoly Techtonik <techtonik@gmail.com>
 This library is a life saver for debugging issues with binary data.
 Available at `Pypi:hexdump <https://pypi.org/project/hexdump/>`_.
```

### Comparing `cardutil-0.6.1/README.rst` & `cardutil-0.6.3/README.rst`

 * *Files 14% similar despite different names*

```diff
@@ -28,17 +28,22 @@
         :target: https://pypi.org/project/cardutil
         :alt: Downloads per month
 
 .. image:: https://img.shields.io/pypi/pyversions/cardutil.svg
         :target: https://pypi.org/project/cardutil
         :alt: Python versions
 
-.. image:: https://readthedocs.org/projects/cardutil/badge/?version=latest
-        :target: https://cardutil.readthedocs.io/en/latest/?badge=latest
-        :alt: Documentation Status
+.. image:: https://img.shields.io/github/actions/workflow/status/adelosa/cardutil/docs.yml?event=push&label=doc%20build
+        :target: https://adelosa.github.io/cardutil
+        :alt: doc build
+
+.. image:: https://snyk.io/advisor/python/cardutil/badge.svg
+        :target: https://snyk.io/advisor/python/cardutil
+        :alt: snyk package health
+
 
 Features
 ========
 * ISO8583 message parsing
 * Mastercard IPM file reader/writer/encoder
 * Check digit calculator
 * Encrypted pin block generator
@@ -55,15 +60,15 @@
 Information
 ===========
 * Supports python 3.7 and later.
 * Pythonic programmer interfaces
 * Core library has **zero** package dependencies.
 * Low memory usage
 * Download from `pypi <https://pypi.org/project/cardutil/>`_
-* Documentation available at  `readthedocs <https://cardutil.readthedocs.io/en/latest/>`_
+* Documentation available at `Read The Docs <https://cardutil.readthedocs.io/en/latest/>`_ and `GitHub Pages <https://adelosa.github.io/cardutil>`_
 * Source hosted at `GitHub <https://github.com/adelosa/cardutil>`_
 
 Acknowledgements
 ================
 The python `hexdump` library is embedded in this package. Many thank to Anatoly Techtonik <techtonik@gmail.com>
 This library is a life saver for debugging issues with binary data.
 Available at `Pypi:hexdump <https://pypi.org/project/hexdump/>`_.
```

### Comparing `cardutil-0.6.1/cardutil/BitArray.py` & `cardutil-0.6.3/cardutil/BitArray.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/__init__.py` & `cardutil-0.6.3/cardutil/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-__version__ = '0.6.1'
+__version__ = '0.6.3'
 
 
 class CardutilError(Exception):
 
     binary_context_data = None
     record_number = None
     ex = None
```

### Comparing `cardutil-0.6.1/cardutil/card.py` & `cardutil-0.6.3/cardutil/card.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/cli/__init__.py` & `cardutil-0.6.3/cardutil/cli/__init__.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/cli/mci_csv_to_ipm.py` & `cardutil-0.6.3/cardutil/cli/mci_csv_to_ipm.py`

 * *Files 6% similar despite different names*

```diff
@@ -50,12 +50,14 @@
     :param out_encoding: The IPM file encoding. 'cp500' works for EBCDIC
     :param no1014blocking: set True 1014 blocking not required
     :return: None
     """
     blocked = not no1014blocking
     with IpmWriter(out_ipm, encoding=out_encoding, blocked=blocked, iso_config=config.get('bit_config')) as writer:
         reader = DictReader(in_csv)
-        writer.write_many(reader)
+        for row in reader:
+            record = {k: v for k, v in row.items() if v}
+            writer.write(record)
 
 
 if __name__ == '__main__':
     cli_entry()
```

### Comparing `cardutil-0.6.1/cardutil/cli/mci_ipm_encode.py` & `cardutil-0.6.3/cardutil/cli/mci_ipm_encode.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/cli/mci_ipm_param_encode.py` & `cardutil-0.6.3/cardutil/cli/mci_ipm_param_encode.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/cli/mci_ipm_param_to_csv.py` & `cardutil-0.6.3/cardutil/cli/mci_ipm_param_to_csv.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/cli/mci_ipm_to_csv.py` & `cardutil-0.6.3/cardutil/cli/mci_ipm_to_csv.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/cli/mideu.py` & `cardutil-0.6.3/cardutil/cli/mideu.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/cli/paramconv.py` & `cardutil-0.6.3/cardutil/cli/paramconv.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/config.py` & `cardutil-0.6.3/cardutil/config.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/iso8583.py` & `cardutil-0.6.3/cardutil/iso8583.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/key.py` & `cardutil-0.6.3/cardutil/key.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/mciipm.py` & `cardutil-0.6.3/cardutil/mciipm.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/pinblock.py` & `cardutil-0.6.3/cardutil/pinblock.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil/vendor/hexdump.py` & `cardutil-0.6.3/cardutil/vendor/hexdump.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/cardutil.egg-info/PKG-INFO` & `cardutil-0.6.3/cardutil.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 Metadata-Version: 2.1
 Name: cardutil
-Version: 0.6.1
+Version: 0.6.3
 Summary: 'Python package for working with payment card systems'
 Home-page: https://github.com/adelosa/cardutil
 Author: Anthony Delosa
 Author-email: adelosa@gmail.com
 License: MIT
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: docs
 Provides-Extra: test
 Provides-Extra: crypto
 License-File: LICENSE
 
 ========
 cardutil
@@ -48,17 +48,22 @@
         :target: https://pypi.org/project/cardutil
         :alt: Downloads per month
 
 .. image:: https://img.shields.io/pypi/pyversions/cardutil.svg
         :target: https://pypi.org/project/cardutil
         :alt: Python versions
 
-.. image:: https://readthedocs.org/projects/cardutil/badge/?version=latest
-        :target: https://cardutil.readthedocs.io/en/latest/?badge=latest
-        :alt: Documentation Status
+.. image:: https://img.shields.io/github/actions/workflow/status/adelosa/cardutil/docs.yml?event=push&label=doc%20build
+        :target: https://adelosa.github.io/cardutil
+        :alt: doc build
+
+.. image:: https://snyk.io/advisor/python/cardutil/badge.svg
+        :target: https://snyk.io/advisor/python/cardutil
+        :alt: snyk package health
+
 
 Features
 ========
 * ISO8583 message parsing
 * Mastercard IPM file reader/writer/encoder
 * Check digit calculator
 * Encrypted pin block generator
@@ -75,15 +80,15 @@
 Information
 ===========
 * Supports python 3.7 and later.
 * Pythonic programmer interfaces
 * Core library has **zero** package dependencies.
 * Low memory usage
 * Download from `pypi <https://pypi.org/project/cardutil/>`_
-* Documentation available at  `readthedocs <https://cardutil.readthedocs.io/en/latest/>`_
+* Documentation available at `Read The Docs <https://cardutil.readthedocs.io/en/latest/>`_ and `GitHub Pages <https://adelosa.github.io/cardutil>`_
 * Source hosted at `GitHub <https://github.com/adelosa/cardutil>`_
 
 Acknowledgements
 ================
 The python `hexdump` library is embedded in this package. Many thank to Anatoly Techtonik <techtonik@gmail.com>
 This library is a life saver for debugging issues with binary data.
 Available at `Pypi:hexdump <https://pypi.org/project/hexdump/>`_.
```

### Comparing `cardutil-0.6.1/cardutil.egg-info/SOURCES.txt` & `cardutil-0.6.3/cardutil.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/setup.cfg` & `cardutil-0.6.3/setup.cfg`

 * *Files 0% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 [bumpversion]
-current_version = 0.6.1
+current_version = 0.6.3
 tag = True
 commit = True
 tag_name = v{new_version}
 
 [metadata]
 name = cardutil
 version = attr: cardutil.__version__
@@ -13,19 +13,19 @@
 license = MIT
 description = 'Python package for working with payment card systems'
 long_description = file: README.rst
 include_package_data = True
 classifiers = 
 	License :: OSI Approved :: MIT License
 	Programming Language :: Python :: 3
-	Programming Language :: Python :: 3.6
 	Programming Language :: Python :: 3.7
 	Programming Language :: Python :: 3.8
 	Programming Language :: Python :: 3.9
 	Programming Language :: Python :: 3.10
+	Programming Language :: Python :: 3.11
 
 [options]
 packages = find:
 
 [options.extras_require]
 docs = 
 	sphinx
```

### Comparing `cardutil-0.6.1/tests/__init__.py` & `cardutil-0.6.3/tests/__init__.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_get_config.py` & `cardutil-0.6.3/tests/cli/test_get_config.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_init.py` & `cardutil-0.6.3/tests/cli/test_init.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_mci_csv_to_ipm.py` & `cardutil-0.6.3/tests/cli/test_mci_csv_to_ipm.py`

 * *Files 4% similar despite different names*

```diff
@@ -175,10 +175,29 @@
         # perform the checks
         self.assertEqual(len(recs), 1)  # one record returned
         rec = recs[0]
         print(rec)
         # de48 contains all PDS values passed
         self.assertEqual(rec['DE48'], '0122001T01910012')
 
+    def test_csv_to_ipm_exclude_empty(self):
+        """
+        Run mci_csv_to_ipm test with empty fields
+        Check that only provided fields are loaded
+        :return:
+        """
+        in_csv_data = ('MTI,DE2,DE3,DE4,DE12,DE14,DE22,'
+                       'PDS0191,PDS0122\n'
+                       '1644,123,1,,,,,123,')
+        # run the conversion
+        recs = self.run_cli_with_csv(in_csv_data, out_encoding='latin1')
+        # perform the checks
+        self.assertEqual(len(recs), 1)  # one record returned
+        rec = recs[0]
+        print(rec)
+        # de48 contains only PDS fields with values
+        expected_dict = {'MTI': '1644', 'DE2': '123', 'DE3': '1     ', 'DE48': '0191003123', 'PDS0191': '123'}
+        self.assertDictEqual(rec, expected_dict)
+
 
 if __name__ == '__main__':
     unittest.main()
```

### Comparing `cardutil-0.6.1/tests/cli/test_mci_ipm_encode.py` & `cardutil-0.6.3/tests/cli/test_mci_ipm_encode.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_mci_ipm_param_encode.py` & `cardutil-0.6.3/tests/cli/test_mci_ipm_param_encode.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_mci_ipm_param_to_csv.py` & `cardutil-0.6.3/tests/cli/test_mci_ipm_param_to_csv.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_mci_ipm_to_csv.py` & `cardutil-0.6.3/tests/cli/test_mci_ipm_to_csv.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_mideu.py` & `cardutil-0.6.3/tests/cli/test_mideu.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/cli/test_paramconv.py` & `cardutil-0.6.3/tests/cli/test_paramconv.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/test_bitarray.py` & `cardutil-0.6.3/tests/test_bitarray.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/test_card.py` & `cardutil-0.6.3/tests/test_card.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/test_iso8583.py` & `cardutil-0.6.3/tests/test_iso8583.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/test_key.py` & `cardutil-0.6.3/tests/test_key.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/test_mciipm.py` & `cardutil-0.6.3/tests/test_mciipm.py`

 * *Files identical despite different names*

### Comparing `cardutil-0.6.1/tests/test_pinblock.py` & `cardutil-0.6.3/tests/test_pinblock.py`

 * *Files identical despite different names*

