# Comparing `tmp/pyesmda-0.3.3.tar.gz` & `tmp/pyesmda-0.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyesmda-0.3.3.tar", last modified: Mon Dec 12 10:00:00 2022, max compression
+gzip compressed data, was "pyesmda-0.4.0.tar", last modified: Wed Jun 28 14:04:18 2023, max compression
```

## Comparing `pyesmda-0.3.3.tar` & `pyesmda-0.4.0.tar`

### file list

```diff
@@ -1,90 +1,91 @@
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.666368 pyesmda-0.3.3/
--rw-r--r--   0 acollet  (11734) geosciences (10000)      197 2022-03-01 14:30:06.000000 pyesmda-0.3.3/AUTHORS.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     3140 2022-12-12 09:58:51.000000 pyesmda-0.3.3/CHANGELOG.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     6433 2022-08-12 09:15:56.000000 pyesmda-0.3.3/CONTRIBUTING.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1072 2022-03-01 14:30:06.000000 pyesmda-0.3.3/LICENSE
--rw-r--r--   0 acollet  (11734) geosciences (10000)      264 2022-03-01 14:30:06.000000 pyesmda-0.3.3/MANIFEST.in
--rw-r--r--   0 acollet  (11734) geosciences (10000)     7447 2022-12-12 10:00:00.666368 pyesmda-0.3.3/PKG-INFO
--rw-r--r--   0 acollet  (11734) geosciences (10000)     3385 2022-12-12 09:58:13.000000 pyesmda-0.3.3/README.rst
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/
--rw-r--r--   0 acollet  (11734) geosciences (10000)      612 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/Makefile
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.658368 pyesmda-0.3.3/docs/build/
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.658368 pyesmda-0.3.3/docs/build/doctrees/
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/
--rw-r--r--   0 acollet  (11734) geosciences (10000)    11901 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_10_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    12835 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_12_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    13140 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_15_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    17092 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_17_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    13333 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_21_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    12349 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_25_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    14612 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_27_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    13531 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_30_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    15146 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_32_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    15654 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_34_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    12694 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_8_1.png
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.658368 pyesmda-0.3.3/docs/build/html/
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/build/html/_images/
--rw-r--r--   0 acollet  (11734) geosciences (10000)    11901 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_10_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    12835 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_12_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    13140 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_15_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    17092 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_17_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    13333 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_21_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    12349 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_25_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    14612 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_27_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    13531 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_30_2.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    15146 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_32_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    15654 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_34_1.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)    12694 2022-12-12 09:57:08.000000 pyesmda-0.3.3/docs/build/html/_images/tutorials_correlation_matrices_building_8_1.png
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/build/html/_static/
--rw-r--r--   0 acollet  (11734) geosciences (10000)      286 2022-12-06 09:06:20.000000 pyesmda-0.3.3/docs/build/html/_static/file.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)       90 2022-12-06 09:06:20.000000 pyesmda-0.3.3/docs/build/html/_static/minus.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)       90 2022-12-06 09:06:20.000000 pyesmda-0.3.3/docs/build/html/_static/plus.png
--rw-r--r--   0 acollet  (11734) geosciences (10000)      773 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/make.bat
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/source/
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/source/_autosummary/
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1217 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.ESMDA.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1442 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.ESMDA_RS.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      126 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.approximate_cov_mm.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      208 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.approximate_covariance_matrix_from_ensembles.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      149 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.check_nans_in_predictions.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      240 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.compute_ensemble_average_normalized_objective_function.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      185 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.compute_normalized_objective_function.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      172 2022-12-06 10:05:09.000000 pyesmda-0.3.3/docs/source/_autosummary/pyesmda.inflate_ensemble_around_its_mean.rst
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/source/_templates/
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.662368 pyesmda-0.3.3/docs/source/_templates/autosummary/
--rw-r--r--   0 acollet  (11734) geosciences (10000)      106 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/_templates/autosummary/base.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      735 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/_templates/autosummary/class.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1098 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/_templates/autosummary/module.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      735 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/_templates/class.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1079 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/_templates/custom-module-template.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1098 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/_templates/module.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      114 2022-10-07 21:02:34.000000 pyesmda-0.3.3/docs/source/api_reference.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)       31 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/authors.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)       75 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/bibliography.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)       33 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/changelog.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)    14842 2022-10-07 21:02:34.000000 pyesmda-0.3.3/docs/source/conf.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)       36 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/contributing.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      458 2022-08-11 22:32:41.000000 pyesmda-0.3.3/docs/source/index.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1138 2022-08-11 22:32:41.000000 pyesmda-0.3.3/docs/source/installation.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)       30 2022-08-11 22:03:08.000000 pyesmda-0.3.3/docs/source/readme.rst
--rw-r--r--   0 acollet  (11734) geosciences (10000)      288 2022-08-12 09:15:56.000000 pyesmda-0.3.3/docs/source/usage.rst
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.666368 pyesmda-0.3.3/pyesmda/
--rw-r--r--   0 acollet  (11734) geosciences (10000)       96 2022-12-12 09:58:51.000000 pyesmda-0.3.3/pyesmda/__about__.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1527 2022-12-12 09:02:55.000000 pyesmda-0.3.3/pyesmda/__init__.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)    26085 2022-12-12 09:03:00.000000 pyesmda-0.3.3/pyesmda/esmda.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)    16753 2022-12-12 09:02:57.000000 pyesmda-0.3.3/pyesmda/esmda_rs.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)     6949 2022-10-07 21:02:34.000000 pyesmda-0.3.3/pyesmda/utils.py
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.666368 pyesmda-0.3.3/pyesmda.egg-info/
--rw-r--r--   0 acollet  (11734) geosciences (10000)     7447 2022-12-12 10:00:00.000000 pyesmda-0.3.3/pyesmda.egg-info/PKG-INFO
--rw-r--r--   0 acollet  (11734) geosciences (10000)     3272 2022-12-12 10:00:00.000000 pyesmda-0.3.3/pyesmda.egg-info/SOURCES.txt
--rw-r--r--   0 acollet  (11734) geosciences (10000)        1 2022-12-12 10:00:00.000000 pyesmda-0.3.3/pyesmda.egg-info/dependency_links.txt
--rw-r--r--   0 acollet  (11734) geosciences (10000)        1 2022-12-12 10:00:00.000000 pyesmda-0.3.3/pyesmda.egg-info/not-zip-safe
--rw-r--r--   0 acollet  (11734) geosciences (10000)       12 2022-12-12 10:00:00.000000 pyesmda-0.3.3/pyesmda.egg-info/requires.txt
--rw-r--r--   0 acollet  (11734) geosciences (10000)        8 2022-12-12 10:00:00.000000 pyesmda-0.3.3/pyesmda.egg-info/top_level.txt
--rw-r--r--   0 acollet  (11734) geosciences (10000)      470 2022-12-12 10:00:00.666368 pyesmda-0.3.3/setup.cfg
--rw-r--r--   0 acollet  (11734) geosciences (10000)     1713 2022-12-12 09:03:02.000000 pyesmda-0.3.3/setup.py
-drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2022-12-12 10:00:00.666368 pyesmda-0.3.3/tests/
--rw-r--r--   0 acollet  (11734) geosciences (10000)        0 2022-03-01 14:30:06.000000 pyesmda-0.3.3/tests/__init__.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)    11112 2022-10-07 21:02:34.000000 pyesmda-0.3.3/tests/test_esmda.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)     2172 2022-10-07 21:07:45.000000 pyesmda-0.3.3/tests/test_esmda_rs.py
--rw-r--r--   0 acollet  (11734) geosciences (10000)     4780 2022-10-07 21:02:34.000000 pyesmda-0.3.3/tests/test_utils.py
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.046695 pyesmda-0.4.0/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      197 2022-03-01 14:30:06.000000 pyesmda-0.4.0/AUTHORS.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     4337 2023-06-28 13:57:51.000000 pyesmda-0.4.0/CHANGELOG.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     6433 2022-08-12 09:15:56.000000 pyesmda-0.4.0/CONTRIBUTING.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1072 2022-03-01 14:30:06.000000 pyesmda-0.4.0/LICENSE
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      264 2022-03-01 14:30:06.000000 pyesmda-0.4.0/MANIFEST.in
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     9730 2023-06-28 14:04:18.046695 pyesmda-0.4.0/PKG-INFO
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     3385 2023-06-28 13:57:41.000000 pyesmda-0.4.0/README.rst
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.038695 pyesmda-0.4.0/docs/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      612 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/Makefile
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.034695 pyesmda-0.4.0/docs/build/
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.034695 pyesmda-0.4.0/docs/build/doctrees/
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.038695 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    72926 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_10_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    63459 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_12_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    28241 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_16_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    28598 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_21_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    21306 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_25_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    19821 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_29_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    23160 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_31_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    21960 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_34_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    24483 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_36_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    24951 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_38_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    21251 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_8_1.png
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.034695 pyesmda-0.4.0/docs/build/html/
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/docs/build/html/_images/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    72926 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_10_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    63459 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_12_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    28241 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_16_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    28598 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_21_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    21306 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_25_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    19821 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_29_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    23160 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_31_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    21960 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_34_2.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    24483 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_36_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    24951 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_38_1.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    21251 2023-06-28 10:22:23.000000 pyesmda-0.4.0/docs/build/html/_images/tutorials_correlation_matrices_building_8_1.png
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/docs/build/html/_static/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      286 2022-12-06 09:06:20.000000 pyesmda-0.4.0/docs/build/html/_static/file.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       90 2022-12-06 09:06:20.000000 pyesmda-0.4.0/docs/build/html/_static/minus.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       90 2022-12-06 09:06:20.000000 pyesmda-0.4.0/docs/build/html/_static/plus.png
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      773 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/make.bat
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/docs/source/
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/docs/source/_autosummary/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1326 2023-06-28 10:17:43.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.ESMDA.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1563 2023-06-28 10:17:43.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.ESMDA_RS.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      126 2022-12-06 10:05:09.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.approximate_cov_mm.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      208 2022-12-06 10:05:09.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.approximate_covariance_matrix_from_ensembles.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      149 2022-12-06 10:05:09.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.check_nans_in_predictions.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      240 2022-12-06 10:05:09.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.compute_ensemble_average_normalized_objective_function.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      185 2022-12-06 10:05:09.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.compute_normalized_objective_function.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      135 2023-06-28 10:17:43.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.get_ensemble_variance.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      172 2022-12-06 10:05:09.000000 pyesmda-0.4.0/docs/source/_autosummary/pyesmda.inflate_ensemble_around_its_mean.rst
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/docs/source/_templates/
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/docs/source/_templates/autosummary/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      106 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/_templates/autosummary/base.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      735 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/_templates/autosummary/class.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1098 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/_templates/autosummary/module.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      735 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/_templates/class.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1079 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/_templates/custom-module-template.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1098 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/_templates/module.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      114 2022-10-07 21:02:34.000000 pyesmda-0.4.0/docs/source/api_reference.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       31 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/authors.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       75 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/bibliography.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       33 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/changelog.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    14867 2023-06-28 13:57:41.000000 pyesmda-0.4.0/docs/source/conf.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       36 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/contributing.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      458 2022-08-11 22:32:41.000000 pyesmda-0.4.0/docs/source/index.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1138 2022-08-11 22:32:41.000000 pyesmda-0.4.0/docs/source/installation.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       30 2022-08-11 22:03:08.000000 pyesmda-0.4.0/docs/source/readme.rst
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      288 2022-08-12 09:15:56.000000 pyesmda-0.4.0/docs/source/usage.rst
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/pyesmda/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       96 2023-06-28 13:57:51.000000 pyesmda-0.4.0/pyesmda/__about__.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1609 2023-06-28 13:57:41.000000 pyesmda-0.4.0/pyesmda/__init__.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    31881 2023-06-28 13:57:41.000000 pyesmda-0.4.0/pyesmda/esmda.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    16165 2023-06-28 13:57:41.000000 pyesmda-0.4.0/pyesmda/esmda_rs.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     7805 2023-06-28 13:57:41.000000 pyesmda-0.4.0/pyesmda/utils.py
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.042695 pyesmda-0.4.0/pyesmda.egg-info/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     9730 2023-06-28 14:04:17.000000 pyesmda-0.4.0/pyesmda.egg-info/PKG-INFO
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     3337 2023-06-28 14:04:18.000000 pyesmda-0.4.0/pyesmda.egg-info/SOURCES.txt
+-rw-r--r--   0 acollet  (11734) geosciences (10000)        1 2023-06-28 14:04:17.000000 pyesmda-0.4.0/pyesmda.egg-info/dependency_links.txt
+-rw-r--r--   0 acollet  (11734) geosciences (10000)        1 2023-06-28 14:04:17.000000 pyesmda-0.4.0/pyesmda.egg-info/not-zip-safe
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       25 2023-06-28 14:04:17.000000 pyesmda-0.4.0/pyesmda.egg-info/requires.txt
+-rw-r--r--   0 acollet  (11734) geosciences (10000)       14 2023-06-28 14:04:17.000000 pyesmda-0.4.0/pyesmda.egg-info/top_level.txt
+-rw-r--r--   0 acollet  (11734) geosciences (10000)      173 2023-06-28 13:57:51.000000 pyesmda-0.4.0/pyproject.toml
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     1481 2023-06-28 14:04:18.046695 pyesmda-0.4.0/setup.cfg
+drwxr-xr-x   0 acollet  (11734) geosciences (10000)        0 2023-06-28 14:04:18.046695 pyesmda-0.4.0/tests/
+-rw-r--r--   0 acollet  (11734) geosciences (10000)        0 2022-03-01 14:30:06.000000 pyesmda-0.4.0/tests/__init__.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)    14545 2023-06-28 13:57:41.000000 pyesmda-0.4.0/tests/test_esmda.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     2172 2023-06-28 07:47:34.000000 pyesmda-0.4.0/tests/test_esmda_rs.py
+-rw-r--r--   0 acollet  (11734) geosciences (10000)     5136 2023-06-28 13:57:41.000000 pyesmda-0.4.0/tests/test_utils.py
```

### Comparing `pyesmda-0.3.3/CONTRIBUTING.rst` & `pyesmda-0.4.0/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/LICENSE` & `pyesmda-0.4.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/README.rst` & `pyesmda-0.4.0/README.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/Makefile` & `pyesmda-0.4.0/docs/Makefile`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/make.bat` & `pyesmda-0.4.0/docs/make.bat`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/source/_autosummary/pyesmda.ESMDA.rst` & `pyesmda-0.4.0/docs/source/_autosummary/pyesmda.ESMDA.rst`

 * *Files 9% similar despite different names*

```diff
@@ -38,16 +38,20 @@
       ~ESMDA.__sizeof__
       ~ESMDA.__str__
       ~ESMDA.__subclasshook__
       ~ESMDA._analyse
       ~ESMDA._apply_bounds
       ~ESMDA._approximate_covariance_matrices
       ~ESMDA._forecast
+      ~ESMDA._get_batch_m_update
+      ~ESMDA._local_analyse
       ~ESMDA._pertrub
       ~ESMDA._set_n_assimilations
+      ~ESMDA._solve
+      ~ESMDA._solve_locally
       ~ESMDA.set_cov_obs_inflation_factors
       ~ESMDA.solve
    
    
    
 
    .. rubric:: Methods definition
```

### Comparing `pyesmda-0.3.3/docs/source/_autosummary/pyesmda.ESMDA_RS.rst` & `pyesmda-0.4.0/docs/source/_autosummary/pyesmda.ESMDA_RS.rst`

 * *Files 12% similar despite different names*

```diff
@@ -39,18 +39,22 @@
       ~ESMDA_RS.__str__
       ~ESMDA_RS.__subclasshook__
       ~ESMDA_RS._analyse
       ~ESMDA_RS._apply_bounds
       ~ESMDA_RS._approximate_covariance_matrices
       ~ESMDA_RS._compute_initial_inflation_factor
       ~ESMDA_RS._forecast
+      ~ESMDA_RS._get_batch_m_update
       ~ESMDA_RS._is_unity_reached
       ~ESMDA_RS._is_valid_parameter_change
+      ~ESMDA_RS._local_analyse
       ~ESMDA_RS._pertrub
       ~ESMDA_RS._set_n_assimilations
+      ~ESMDA_RS._solve
+      ~ESMDA_RS._solve_locally
       ~ESMDA_RS.set_cov_obs_inflation_factors
       ~ESMDA_RS.solve
    
    
    
 
    .. rubric:: Methods definition
```

### Comparing `pyesmda-0.3.3/docs/source/_templates/autosummary/class.rst` & `pyesmda-0.4.0/docs/source/_templates/autosummary/class.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/source/_templates/autosummary/module.rst` & `pyesmda-0.4.0/docs/source/_templates/autosummary/module.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/source/_templates/class.rst` & `pyesmda-0.4.0/docs/source/_templates/class.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/source/_templates/custom-module-template.rst` & `pyesmda-0.4.0/docs/source/_templates/custom-module-template.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/source/_templates/module.rst` & `pyesmda-0.4.0/docs/source/_templates/module.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/docs/source/conf.py` & `pyesmda-0.4.0/docs/source/conf.py`

 * *Files 1% similar despite different names*

```diff
@@ -58,22 +58,27 @@
     "sphinx.ext.autodoc",  # Core library for html generation from docstrings
     "sphinx.ext.autosummary",  # Create neat summary tables
     "sphinx.ext.napoleon",  # autodoc understands numpy docstrings
     "sphinx.ext.doctest",  # Test snippets in the documentation
     "sphinx.ext.viewcode",  # Add links to highlighted source code
     "sphinx.ext.intersphinx",  # Link to other projects’ documentation
     "sphinx.ext.autosectionlabel",  # Allow reference sections using its title
-    "sphinxcontrib.bibtex",  # allows BibTeX citations to be inserted into documentation generated by Sphinx
+    # allows BibTeX citations to be inserted into documentation generated by Sphinx
+    "sphinxcontrib.bibtex",
     "sphinx.ext.viewcode",  # Add links to highlighted source code
     "sphinx.ext.intersphinx",  # Link to other projects’ documentation
     "sphinx.ext.autosectionlabel",  # Allow reference sections using its title
     # 'sphinx.ext.mathjax',
     "nbsphinx",  # provides a source parser for *.ipynb files.
-    "nbsphinx_link",  # allows you to include Jupyter notebooks that sit outside your sphinx source directory in your documentation.
-    "jupyter_sphinx",  # enables running code embedded in Sphinx documentation and embedding output of that code into the resulting document
+    # allows you to include Jupyter notebooks that sit outside your sphinx source
+    # directory in your documentation.
+    "nbsphinx_link",
+    # enables running code embedded in Sphinx documentation and embedding output
+    # of that code into the resulting document
+    "jupyter_sphinx",
 ]
 
 # -----------------------------------------------------------------------------
 # Autosummary
 # -----------------------------------------------------------------------------
 
 # autosummaries from source-files
@@ -81,15 +86,16 @@
 # dont show __init__ docstring
 autoclass_content = "class"
 # sort class members
 autodoc_member_order = "groupwise"
 # autodoc_member_order = 'bysource'
 
 autosummary_generate = True  # Turn on sphinx.ext.autosummary
-# numpydoc_show_class_members=False  # This is because numpydoc screew up with autosummary
+# This is because numpydoc screew up with autosummary
+# numpydoc_show_class_members=False
 
 # Napoleon settings
 napoleon_google_docstring = True
 napoleon_numpy_docstring = True
 napoleon_include_init_with_doc = False
 napoleon_include_private_with_doc = True
 napoleon_include_special_with_doc = False
@@ -397,26 +403,28 @@
 # autodoc_default_options = {
 #     "members": True,  #
 #     "member_order": "bysource",
 #     "undoc-members": True,  #
 #     "private-members": True,  #
 #     "special-members": True,  #
 #     "show-inheritance": True,  #
-#     "exclude-members": "__weakref__,__init__,__dict__,__abstractmethods__,__module__,_abc_impl",
+#     "exclude-members": "__weakref__,__init__,__dict__,__abstractmethods__,
+# __module__,_abc_impl",
 # }
 
 # Bibliography
 bibtex_bibfiles = ["./../../bibliography.bib"]
 bibtex_default_style = "unsrt"
 bibtex_reference_style = "author_year"
 suppress_warnings = ["bibtex.duplicate_citation", "autosectionlabel.*"]
 
 # Issue with attributes section, see:
 # https://github.com/sphinx-doc/sphinx/issues/2115
-# Solution: https://michaelgoerz.net/notes/extending-sphinx-napoleon-docstring-sections.html
+# Solution:
+# https://michaelgoerz.net/notes/extending-sphinx-napoleon-docstring-sections.html
 # -- Extensions to the  Napoleon GoogleDocstring class ---------------------
 
 # first, we define new methods for any new sections and add them to the class
 
 
 def parse_keys_section(self, section):
     return self._format_fields("Keys", self._consume_fields())
```

### Comparing `pyesmda-0.3.3/docs/source/installation.rst` & `pyesmda-0.4.0/docs/source/installation.rst`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/pyesmda/esmda.py` & `pyesmda-0.4.0/pyesmda/esmda.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,18 +1,20 @@
 """
 Implement the ES-MDA algorithms.
 
 @author: acollet
 """
-from typing import Any, Callable, Dict, List, Optional, Sequence
+from concurrent.futures import ProcessPoolExecutor
+from typing import Any, Callable, Dict, Iterator, List, Optional, Sequence, Union
 
 import numpy as np
-import numpy.typing as npt
+from scipy.sparse import csr_matrix
 
 from pyesmda.utils import (
+    NDArrayFloat,
     approximate_cov_mm,
     approximate_covariance_matrix_from_ensembles,
     check_nans_in_predictions,
     inflate_ensemble_around_its_mean,
 )
 
 # pylint: disable=C0103 # Does not conform to snake_case naming style
@@ -27,43 +29,43 @@
     emerickHistoryMatchingProductionSeismic2013`.
 
     Attributes
     ----------
     d_dim : int
         Number of observation values :math:`N_{obs}`, and consequently of
         predicted values.
-    obs : npt.NDArray[np.float64]
+    obs : NDArrayFloat
         Obsevrations vector with dimensions (:math:`N_{obs}`).
-    cov_obs: npt.NDArray[np.float64]
+    cov_obs: NDArrayFloat
         Covariance matrix of observed data measurement errors with dimensions
         (:math:`N_{obs}`, :math:`N_{obs}`). Also denoted :math:`R`.
-    d_obs_uc: npt.NDArray[np.float64]
+    d_obs_uc: NDArrayFloat
         Vectors of pertubed observations with dimension
         (:math:`N_{e}`, :math:`N_{obs}`).
-    d_pred: npt.NDArray[np.float64]
+    d_pred: NDArrayFloat
         Vectors of predicted values (one for each ensemble member)
         with dimensions (:math:`N_{e}`, :math:`N_{obs}`).
-    d_history: List[npt.NDArray[np.float64]]
+    d_history: List[NDArrayFloat]
         List of vectors of predicted values obtained at each assimilation step.
     m_prior:
         Vectors of parameter values (one vector for each ensemble member) used in the
         last assimilation step. Dimensions are (:math:`N_{e}`, :math:`N_{m}`).
-    m_bounds : npt.NDArray[np.float64]
+    m_bounds : NDArrayFloat
         Lower and upper bounds for the :math:`N_{m}` parameter values.
         Expected dimensions are (:math:`N_{m}`, 2) with lower bounds on the first
         column and upper on the second one.
-    m_history: List[npt.NDArray[np.float64]]
+    m_history: List[NDArrayFloat]
         List of successive `m_prior`.
-    cov_md: npt.NDArray[np.float64]
+    cov_md: NDArrayFloat
         Cross-covariance matrix between the forecast state vector and predicted data.
         Dimensions are (:math:`N_{m}, N_{obs}`).
-    cov_obsd: npt.NDArray[np.float64]
+    cov_obs: csr_matrix
         Autocovariance matrix of predicted data.
         Dimensions are (:math:`N_{obs}, N_{obs}`).
-    cov_mm: npt.NDArray[np.float64]
+    cov_mm: NDArrayFloat
         Autocovariance matrix of estimated parameters.
         Dimensions are (:math:`N_{m}, N_{m}`).
     forward_model: callable
         Function calling the non-linear observation model (forward model)
         for all ensemble members and returning the predicted data for
         each ensemble member.
     forward_model_args: Tuple[Any]
@@ -77,34 +79,47 @@
         measurement errors.
     cov_mm_inflation_factors: List[float]
         List of factors used to inflate the adjusted parameters covariance among
         iterations:
         Each realization of the ensemble at the end of each update step i,
         is linearly inflated around its mean.
         See :cite:p:`andersonExploringNeedLocalization2007`.
-    dd_correlation_matrix : Optional[npt.NDArray[np.float64]]
+    dd_correlation_matrix : Optional[Union[NDArrayFloat, csr_matrix]]
         Correlation matrix based on spatial and temporal distances between
         observations and observations :math:`\rho_{DD}`. It is used to localize the
         autocovariance matrix of predicted data by applying an elementwise
         multiplication by this matrix.
-        Expected dimensions are (:math:`N_{obs}`, :math:`N_{obs}`).
-    md_correlation_matrix : Optional[npt.NDArray[np.float64]]
+        Expected dimensions are (:math:`N_{obs}`, :math:`N_{obs}`). A sparse matrix
+        format can be provided to save some memory.
+    md_correlation_matrix : Optional[Union[NDArrayFloat, csr_matrix]]
         Correlation matrix based on spatial and temporal distances between
         parameters and observations :math:`\rho_{MD}`. It is used to localize the
         cross-covariance matrix between the forecast state vector (parameters)
         and predicted data by applying an elementwise
         multiplication by this matrix.
-        Expected dimensions are (:math:`N_{m}`, :math:`N_{obs}`).
+        Expected dimensions are (:math:`N_{m}`, :math:`N_{obs}`). . A sparse matrix
+        format can be provided to save some memory.
     save_ensembles_history: bool
         Whether to save the history predictions and parameters over the assimilations.
     rng: np.random.Generator
         The random number generator used in the predictions perturbation step.
     is_forecast_for_last_assimilation: bool
         Whether to compute the predictions for the ensemble obtained at the
         last assimilation step.
+    batch_size: int
+            Number of parameters that are assimilated at once. This option is
+            available to overcome memory limitations when the number of parameters is
+            large. In that case, the size of the covariance matrices tends to explode
+            and the update step must be performed by chunks of parameters.
+    is_parallel_analyse_step: bool, optional
+            Whether to use parallel computing for the analyse step if the number of
+            batch is above one. The default is True.
+    n_batches: int
+            Number of batches required during the update step.
+
     """
     # pylint: disable=R0902 # Too many instance attributes
     __slots__: List[str] = [
         "obs",
         "_cov_obs",
         "d_obs_uc",
         "d_pred",
@@ -122,48 +137,53 @@
         "_cov_obs_inflation_factors",
         "_cov_mm_inflation_factors",
         "_dd_correlation_matrix",
         "_md_correlation_matrix",
         "save_ensembles_history",
         "rng",
         "is_forecast_for_last_assimilation",
+        "batch_size",
+        "is_parallel_analyse_step",
     ]
 
     def __init__(
         self,
-        obs: npt.NDArray[np.float64],
-        m_init: npt.NDArray[np.float64],
-        cov_obs: npt.NDArray[np.float64],
-        forward_model: Callable[..., npt.NDArray[np.float64]],
+        obs: NDArrayFloat,
+        m_init: NDArrayFloat,
+        cov_obs: Union[NDArrayFloat, csr_matrix],
+        forward_model: Callable[..., NDArrayFloat],
         forward_model_args: Sequence[Any] = (),
         forward_model_kwargs: Optional[Dict[str, Any]] = None,
         n_assimilations: int = 4,
         cov_obs_inflation_factors: Optional[Sequence[float]] = None,
         cov_mm_inflation_factors: Optional[Sequence[float]] = None,
-        dd_correlation_matrix: Optional[npt.NDArray[np.float64]] = None,
-        md_correlation_matrix: Optional[npt.NDArray[np.float64]] = None,
-        m_bounds: Optional[npt.NDArray[np.float64]] = None,
+        dd_correlation_matrix: Optional[Union[NDArrayFloat, csr_matrix]] = None,
+        md_correlation_matrix: Optional[Union[NDArrayFloat, csr_matrix]] = None,
+        m_bounds: Optional[NDArrayFloat] = None,
         save_ensembles_history: bool = False,
         seed: Optional[int] = None,
         is_forecast_for_last_assimilation: bool = True,
+        batch_size: int = 5000,
+        is_parallel_analyse_step: bool = True,
     ) -> None:
         # pylint: disable=R0913 # Too many arguments
         # pylint: disable=R0914 # Too many local variables
         r"""Construct the instance.
 
         Parameters
         ----------
-        obs : npt.NDArray[np.float64]
+        obs : NDArrayFloat
             Obsevrations vector with dimension :math:`N_{obs}`.
-        m_init : npt.NDArray[np.float64]
+        m_init : NDArrayFloat
             Initial ensemble of parameters vector with dimensions
             (:math:`N_{e}`, :math:`N_{m}`).
-        cov_obs: npt.NDArray[np.float64]
+        cov_obs: NDArrayFloat
             Covariance matrix of observed data measurement errors with dimensions
             (:math:`N_{obs}`, :math:`N_{obs}`). Also denoted :math:`R`.
+            It can be a numpy array or a sparse matrix (scipy.linalg).
         forward_model: callable
             Function calling the non-linear observation model (forward model)
             for all ensemble members and returning the predicted data for
             each ensemble member.
         forward_model_args: Optional[Tuple[Any]]
             Additional args for the callable forward_model. The default is None.
         forward_model_kwargs: Optional[Dict[str, Any]]
@@ -180,82 +200,100 @@
             among iterations:
             Each realization of the ensemble at the end of each update step i,
             is linearly inflated around its mean.
             Must match the number of data assimilations (:math:`N_{a}`).
             See :cite:p:`andersonExploringNeedLocalization2007`.
             If None, the default is 1.0. at each iteration (no inflation).
             The default is None.
-        dd_correlation_matrix : Optional[npt.NDArray[np.float64]]
+        dd_correlation_matrix : Optional[NDArrayFloat]
             Correlation matrix based on spatial and temporal distances between
             observations and observations :math:`\rho_{DD}`. It is used to localize the
             autocovariance matrix of predicted data by applying an elementwise
             multiplication by this matrix.
             Expected dimensions are (:math:`N_{obs}`, :math:`N_{obs}`).
             The default is None.
-        md_correlation_matrix : Optional[npt.NDArray[np.float64]]
+        md_correlation_matrix : Optional[NDArrayFloat]
             Correlation matrix based on spatial and temporal distances between
             parameters and observations :math:`\rho_{MD}`. It is used to localize the
             cross-covariance matrix between the forecast state vector (parameters)
             and predicted data by applying an elementwise
             multiplication by this matrix.
             Expected dimensions are (:math:`N_{m}`, :math:`N_{obs}`).
             The default is None.
-        m_bounds : Optional[npt.NDArray[np.float64]], optional
+        m_bounds : Optional[NDArrayFloat], optional
             Lower and upper bounds for the :math:`N_{m}` parameter values.
             Expected dimensions are (:math:`N_{m}`, 2) with lower bounds on the first
             column and upper on the second one. The default is None.
         save_ensembles_history: bool, optional
             Whether to save the history predictions and parameters over
             the assimilations. The default is False.
         seed: Optional[int]
             Seed for the white noise generator used in the perturbation step.
             If None, the default :func:`numpy.random.default_rng()` is used.
             The default is None.
         is_forecast_for_last_assimilation: bool, optional
             Whether to compute the predictions for the ensemble obtained at the
             last assimilation step. The default is True.
+        batch_size: int
+            Number of parameters that are assimilated at once. This option is
+            available to overcome memory limitations when the number of parameters is
+            large. In that case, the size of the covariance matrices tends to explode
+            and the update step must be performed by chunks of parameters.
+            The default is 5000.
+        is_parallel_analyse_step: bool, optional
+            Whether to use parallel computing for the analyse step if the number of
+            batch is above one. It relies on `concurrent.futures` multiprocessing.
+            The default is True.
 
         """
-        self.obs: npt.NDArray[np.float64] = obs
-        self.m_prior: npt.NDArray[np.float64] = m_init
+        self.obs: NDArrayFloat = obs
+        self.m_prior: NDArrayFloat = m_init
         self.save_ensembles_history: bool = save_ensembles_history
-        self.m_history: list[npt.NDArray[np.float64]] = []
-        self.d_history: list[npt.NDArray[np.float64]] = []
-        self.d_pred: npt.NDArray[np.float64] = np.zeros([self.n_ensemble, self.d_dim])
+        self.m_history: list[NDArrayFloat] = []
+        self.d_history: list[NDArrayFloat] = []
+        self.d_pred: NDArrayFloat = np.zeros([self.n_ensemble, self.d_dim])
         self.cov_obs = cov_obs
-        self.d_obs_uc: npt.NDArray[np.float64] = np.array([])
-        self.cov_md: npt.NDArray[np.float64] = np.array([])
-        self.cov_dd: npt.NDArray[np.float64] = np.array([])
+        self.d_obs_uc: NDArrayFloat = np.array([])
+        self.cov_md: NDArrayFloat = np.array([])
+        self.cov_dd: NDArrayFloat = np.array([])
         self.forward_model: Callable = forward_model
         self.forward_model_args: Sequence[Any] = forward_model_args
         if forward_model_kwargs is None:
             forward_model_kwargs = {}
         self.forward_model_kwargs: Dict[str, Any] = forward_model_kwargs
         self._set_n_assimilations(n_assimilations)
         self._assimilation_step: int = 0
         self.set_cov_obs_inflation_factors(cov_obs_inflation_factors)
         self.cov_mm_inflation_factors = cov_mm_inflation_factors
         self.dd_correlation_matrix = dd_correlation_matrix
         self.md_correlation_matrix = md_correlation_matrix
         self.m_bounds = m_bounds
         self.rng: np.random.Generator = np.random.default_rng(seed)
         self.is_forecast_for_last_assimilation = is_forecast_for_last_assimilation
+        self.batch_size = batch_size
+        self.is_parallel_analyse_step = is_parallel_analyse_step
 
     @property
     def n_assimilations(self) -> int:
         """Return the number of assimilations to perform. Read-only attribute."""
         return self._n_assimilations
 
     def _set_n_assimilations(self, n: int) -> None:
         """Set the number of assimilations to perform."""
-        if not isinstance(n, int):
-            raise TypeError("The number of assimilations must be a positive integer.")
-        if n < 1:
-            raise ValueError("The number of assimilations must be 1 or more.")
-        self._n_assimilations = n
+        try:
+            if int(n) < 1:
+                raise ValueError("The number of assimilations must be 1 or more.")
+            if int(n) != float(n):
+                raise TypeError()
+        except TypeError as e:
+            raise TypeError(
+                "The number of assimilations must be a positive integer."
+            ) from e
+
+        self._n_assimilations = int(n)
 
     @property
     def n_ensemble(self) -> int:
         """Return the number of ensemble members."""
         return self.m_prior.shape[0]
 
     @property
@@ -265,30 +303,30 @@
 
     @property
     def d_dim(self) -> int:
         """Return the number of forecast data."""
         return len(self.obs)
 
     @property
-    def cov_obs(self) -> npt.NDArray[np.float64]:
+    def cov_obs(self) -> csr_matrix:
         """Get the observation errors covariance matrix."""
         return self._cov_obs
 
     @cov_obs.setter
-    def cov_obs(self, s: npt.NDArray[np.float64]) -> None:
+    def cov_obs(self, s: Union[NDArrayFloat, csr_matrix]) -> None:
         """Set the observation errors covariance matrix."""
         if len(s.shape) != 2 or s.shape[0] != s.shape[1] or s.shape[0] != self.d_dim:
             raise ValueError(
                 "cov_obs must be a 2D square matrix with "
                 f"dimensions ({self.d_dim}, {self.d_dim})."
             )
-        self._cov_obs: npt.NDArray[np.float64] = s
+        self._cov_obs: csr_matrix = csr_matrix(s)
 
     @property
-    def cov_mm(self) -> npt.NDArray[np.float64]:
+    def cov_mm(self) -> NDArrayFloat:
         r"""
         Get the estimated parameters autocovariance matrix. It is a read-only attribute.
 
         The covariance matrice :math:`C^{l}_{MM}`
         is approximated from the ensemble in the standard way of EnKF
         :cite:p:`evensenDataAssimilationEnsemble2007,aanonsenEnsembleKalmanFilter2009`:
 
@@ -299,26 +337,24 @@
 
         with :math:`\overline{m^{l}}`, the parameters
         ensemble means, at iteration :math:`l`.
         """
         return approximate_cov_mm(self.m_prior)
 
     @property
-    def m_bounds(self) -> npt.NDArray[np.float64]:
+    def m_bounds(self) -> NDArrayFloat:
         """Get the parameter errors covariance matrix."""
         return self._m_bounds
 
     @m_bounds.setter
-    def m_bounds(self, mb: Optional[npt.NDArray[np.float64]]) -> None:
+    def m_bounds(self, mb: Optional[NDArrayFloat]) -> None:
         """Set the parameter errors covariance matrix."""
         if mb is None:
             # In that case, create an array of nan.
-            self._m_bounds: npt.NDArray[np.float64] = np.empty(
-                [self.m_dim, 2], dtype=np.float64
-            )
+            self._m_bounds: NDArrayFloat = np.empty([self.m_dim, 2], dtype=np.float64)
             self._m_bounds[:] = np.nan
         elif mb.shape[0] != self.m_dim:
             raise ValueError(
                 f"m_bounds is of shape {mb.shape} while it "
                 f"should be of shape ({self.m_dim}, 2)"
             )
         else:
@@ -390,56 +426,73 @@
             raise ValueError(
                 "The length of cov_mm_inflation_factors should match n_assimilations"
             )
         else:
             self._cov_mm_inflation_factors = list(a)
 
     @property
-    def dd_correlation_matrix(self) -> Optional[npt.NDArray[np.float64]]:
+    def dd_correlation_matrix(self) -> Optional[csr_matrix]:
         """Get the observations-observations localization matrix."""
         return self._dd_correlation_matrix
 
     @dd_correlation_matrix.setter
-    def dd_correlation_matrix(self, s: Optional[npt.NDArray[np.float64]]) -> None:
+    def dd_correlation_matrix(
+        self, s: Optional[Union[NDArrayFloat, csr_matrix]]
+    ) -> None:
         """Set the observations-observations localization matrix."""
         if s is None:
             self._dd_correlation_matrix = None
             return
         if len(s.shape) != 2 or s.shape[0] != s.shape[1] or s.shape[0] != self.d_dim:
             raise ValueError(
                 "dd_correlation_matrix must be a 2D square matrix with "
                 f"dimensions ({self.d_dim}, {self.d_dim})."
             )
-        self._dd_correlation_matrix: Optional[npt.NDArray[np.float64]] = s
+        self._dd_correlation_matrix: Optional[csr_matrix] = csr_matrix(s)
 
     @property
-    def md_correlation_matrix(self) -> Optional[npt.NDArray[np.float64]]:
+    def md_correlation_matrix(self) -> Optional[csr_matrix]:
         """Get the parameters-observations localization matrix."""
         return self._md_correlation_matrix
 
     @md_correlation_matrix.setter
-    def md_correlation_matrix(self, s: Optional[npt.NDArray[np.float64]]) -> None:
+    def md_correlation_matrix(
+        self, s: Optional[Union[NDArrayFloat, csr_matrix]]
+    ) -> None:
         """Set the parameters-observations localization matrix."""
         if s is None:
             self._md_correlation_matrix = None
             return
         if len(s.shape) != 2:
             raise ValueError(
                 "md_correlation_matrix must be a 2D matrix with "
                 f"dimensions ({self.m_dim}, {self.d_dim})."
             )
         if s.shape[0] != self.m_dim or s.shape[1] != self.d_dim:
             raise ValueError(
                 "md_correlation_matrix must be a 2D matrix with "
                 f"dimensions ({self.m_dim}, {self.d_dim})."
             )
-        self._md_correlation_matrix: Optional[npt.NDArray[np.float64]] = s
+        self._md_correlation_matrix: Optional[csr_matrix] = csr_matrix(s)
+
+    @property
+    def n_batches(self) -> int:
+        """Number of batch used in the optimization."""
+        return int(self.m_dim / self.batch_size) + 1
 
     def solve(self) -> None:
         """Solve the optimization problem with ES-MDA algorithm."""
+        if self.n_batches == 1:
+            self._solve()
+        else:
+            # assimilate chunk of parameters rather than everything all at once.
+            self._solve_locally()
+
+    def _solve(self) -> None:
+        """Solve the optimization problem with ES-MDA algorithm."""
         if self.save_ensembles_history:
             self.m_history.append(self.m_prior)  # save m_init
         for self._assimilation_step in range(self.n_assimilations):
             print(f"Assimilation # {self._assimilation_step + 1}")
             self._forecast()
             self._pertrub(self.cov_obs_inflation_factors[self._assimilation_step])
             self._approximate_covariance_matrices()
@@ -455,14 +508,48 @@
             # Saving the parameters history
             if self.save_ensembles_history:
                 self.m_history.append(self.m_prior)
 
         if self.is_forecast_for_last_assimilation:
             self._forecast()
 
+    def _solve_locally(self) -> None:
+        """Solve the optimization problem with ES-MDA algorithm."""
+        if self.save_ensembles_history:
+            self.m_history.append(self.m_prior)  # save m_init
+        for self._assimilation_step in range(self.n_assimilations):
+            print(f"Assimilation # {self._assimilation_step + 1}")
+            self._forecast()
+            self._pertrub(self.cov_obs_inflation_factors[self._assimilation_step])
+
+            # covariance approximation dd
+            self.cov_dd = approximate_covariance_matrix_from_ensembles(
+                self.d_pred, self.d_pred
+            )
+            # Spatial and temporal localization: obs - obs
+            if self.dd_correlation_matrix is not None:
+                self.cov_dd = self.dd_correlation_matrix.multiply(self.cov_dd).toarray()
+
+            # Update the prior parameter for next iteration
+            self.m_prior = self._apply_bounds(
+                inflate_ensemble_around_its_mean(
+                    self._local_analyse(
+                        self.cov_obs_inflation_factors[self._assimilation_step]
+                    ),
+                    self.cov_mm_inflation_factors[self._assimilation_step],
+                )
+            )
+
+            # Saving the parameters history
+            if self.save_ensembles_history:
+                self.m_history.append(self.m_prior)
+
+        if self.is_forecast_for_last_assimilation:
+            self._forecast()
+
     def _forecast(self) -> None:
         r"""
         Forecast step of ES-MDA.
 
         Run the forward model from time zero until the end of the historical
         period from time zero until the end of the historical period to
         compute the vector of predicted data
@@ -505,15 +592,15 @@
         To get reproducible behavior, use a seed when creating the ESMDA instance.
 
         """
         self.d_obs_uc = np.zeros([self.n_ensemble, self.d_dim])
         for i in range(self.d_dim):
             self.d_obs_uc[:, i] = self.obs[i] + np.sqrt(
                 inflation_factor
-            ) * self.rng.normal(0, np.abs(self.cov_obs[i, i]), self.n_ensemble)
+            ) * self.rng.normal(0, np.abs(self.cov_obs.diagonal()[i]), self.n_ensemble)
 
     def _approximate_covariance_matrices(self) -> None:
         r"""
         Approximate the covariance matrices.
 
         The covariance matrices :math:`C^{l}_{MD}` and :math:`C^{l}_{DD}`
         are approximated from the ensemble in the standard way of EnKF
@@ -552,20 +639,20 @@
         )
         self.cov_dd = approximate_covariance_matrix_from_ensembles(
             self.d_pred, self.d_pred
         )
 
         # Spatial and temporal localization: obs - obs
         if self.dd_correlation_matrix is not None:
-            self.cov_dd *= self.dd_correlation_matrix
+            self.cov_dd = self.dd_correlation_matrix.multiply(self.cov_dd).toarray()
         # Spatial and temporal localization: parameters - obs
         if self.md_correlation_matrix is not None:
-            self.cov_md *= self.md_correlation_matrix
+            self.cov_md = self.md_correlation_matrix.multiply(self.cov_md).toarray()
 
-    def _analyse(self, inflation_factor: float) -> npt.NDArray[np.float64]:
+    def _analyse(self, inflation_factor: float) -> NDArrayFloat:
         r"""
         Analysis step of the ES-MDA.
 
         Update the vector of model parameters using
 
         .. math::
            m^{l+1}_{j} = m^{l}_{j} + C^{l}_{MD}\left(C^{l}_{DD}+\alpha_{l+1}
@@ -578,26 +665,87 @@
         the product :math:`\left(C^{l}_{DD}+\alpha_{l+1} C_{D}\right) ^{-1}
         \left(d^{l}_{uc,j} - d^{l}_{j} \right)`
         is solved linearly as :math:`A^{-1}b = x`
         which is equivalent to solve :math:`Ax = b`.
 
         """
         # predicted parameters
-        m_pred: npt.NDArray[np.float64] = np.zeros([self.n_ensemble, self.m_dim])
-        for j in range(self.n_ensemble):
-            m_pred[j, :] = self.m_prior[j, :] + np.matmul(
-                self.cov_md,
-                np.linalg.solve(
+        return (
+            self.m_prior
+            + (
+                self.cov_md
+                @ np.linalg.solve(
                     self.cov_dd + inflation_factor * self.cov_obs,
-                    self.d_obs_uc[j, :] - self.d_pred[j, :],
-                ),
-            )
+                    (self.d_obs_uc - self.d_pred).T,
+                )
+            ).T
+        )
+
+    def _local_analyse(self, inflation_factor: float) -> NDArrayFloat:
+        r"""
+        Analysis step of the ES-MDA.
+
+        Update the vector of model parameters using
+
+        .. math::
+           m^{l+1}_{j} = m^{l}_{j} + C^{l}_{MD}\left(C^{l}_{DD}+\alpha_{l+1}
+           C_{D}\right)^{-1} \left(d^{l}_{uc,j} - d^{l}_{j} \right),
+           \textrm{for } j=1,2,...,N_{e}.
+
+        Notes
+        -----
+        To avoid the inversion of :math:`\left(C^{l}_{DD}+\alpha_{l+1} C_{D}\right)`,
+        the product :math:`\left(C^{l}_{DD}+\alpha_{l+1} C_{D}\right) ^{-1}
+        \left(d^{l}_{uc,j} - d^{l}_{j} \right)`
+        is solved linearly as :math:`A^{-1}b = x`
+        which is equivalent to solve :math:`Ax = b`.
+
+        """
+        m_pred: NDArrayFloat = np.zeros(self.m_prior.shape)
+
+        if self.is_parallel_analyse_step:
+            with ProcessPoolExecutor() as executor:
+                results: Iterator[NDArrayFloat] = executor.map(
+                    self._get_batch_m_update,
+                    range(self.n_batches),
+                    [inflation_factor] * self.n_batches,
+                )
+                for index, res in enumerate(results):
+                    _slice = slice(
+                        index * self.batch_size, (index + 1) * self.batch_size
+                    )
+                    m_pred[:, _slice] = res
+            # self.simu_n += n_ensemble
+        else:
+            for index in range(self.n_batches):
+                _slice = slice(index * self.batch_size, (index + 1) * self.batch_size)
+                m_pred[:, _slice] = self._get_batch_m_update(index, inflation_factor)
+
         return m_pred
 
-    def _apply_bounds(self, m_pred: npt.NDArray[np.float64]) -> npt.NDArray[np.float64]:
+    def _get_batch_m_update(self, index: int, inflation_factor: float) -> NDArrayFloat:
+        _slice = slice(index * self.batch_size, (index + 1) * self.batch_size)
+        batch_cov_md = approximate_covariance_matrix_from_ensembles(
+            self.m_prior[:, _slice], self.d_pred
+        )
+        # apply localization
+        if self.md_correlation_matrix is not None:
+            batch_cov_md = self.md_correlation_matrix[_slice, :].multiply(batch_cov_md)
+        return (
+            self.m_prior[:, _slice]
+            + (
+                batch_cov_md
+                @ np.linalg.solve(
+                    self.cov_dd + inflation_factor * self.cov_obs,
+                    (self.d_obs_uc - self.d_pred).T,
+                )
+            ).T
+        )
+
+    def _apply_bounds(self, m_pred: NDArrayFloat) -> NDArrayFloat:
         """Apply bounds constraints to the adjusted parameters."""
         m_pred = np.where(
             m_pred < self.m_bounds[:, 0], self.m_bounds[:, 0], m_pred
         )  # lower bounds
         m_pred = np.where(
             m_pred > self.m_bounds[:, 1], self.m_bounds[:, 1], m_pred
         )  # upper bounds
```

### Comparing `pyesmda-0.3.3/pyesmda/esmda_rs.py` & `pyesmda-0.4.0/pyesmda/esmda_rs.py`

 * *Files 2% similar despite different names*

```diff
@@ -106,39 +106,15 @@
         The random number generator used in the predictions perturbation step.
     is_forecast_for_last_assimilation: bool
         Whether to compute the predictions for the ensemble obtained at the
         last assimilation step.
     """
 
     # pylint: disable=R0902 # Too many instance attributes
-    __slots__: List[str] = [
-        "obs",
-        "_cov_obs",
-        "std_m_prior",
-        "d_obs_uc",
-        "d_pred",
-        "d_history",
-        "m_prior",
-        "_m_bounds",
-        "m_history",
-        "cov_md",
-        "cov_dd",
-        "forward_model",
-        "forward_model_args",
-        "forward_model_kwargs",
-        "_n_assimilations",
-        "_assimilation_step",
-        "_cov_obs_inflation_factors",
-        "_cov_mm_inflation_factors",
-        "_dd_correlation_matrix",
-        "_md_correlation_matrix",
-        "save_ensembles_history",
-        "rng",
-        "is_forecast_for_last_assimilation",
-    ]
+    __slots__: List[str] = ["std_m_prior"]
 
     def __init__(
         self,
         obs: npt.NDArray[np.float64],
         m_init: npt.NDArray[np.float64],
         cov_obs: npt.NDArray[np.float64],
         std_m_prior: npt.NDArray[np.float64],
```

### Comparing `pyesmda-0.3.3/pyesmda.egg-info/SOURCES.txt` & `pyesmda-0.4.0/pyesmda.egg-info/SOURCES.txt`

 * *Files 6% similar despite different names*

```diff
@@ -1,38 +1,38 @@
 AUTHORS.rst
 CHANGELOG.rst
 CONTRIBUTING.rst
 LICENSE
 MANIFEST.in
 README.rst
+pyproject.toml
 setup.cfg
-setup.py
 docs/Makefile
 docs/make.bat
 docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_10_1.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_12_2.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_15_2.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_17_1.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_21_2.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_12_1.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_16_2.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_21_1.png
 docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_25_2.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_27_1.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_30_2.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_32_1.png
-docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_34_1.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_29_2.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_31_1.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_34_2.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_36_1.png
+docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_38_1.png
 docs/build/doctrees/nbsphinx/tutorials_correlation_matrices_building_8_1.png
 docs/build/html/_images/tutorials_correlation_matrices_building_10_1.png
-docs/build/html/_images/tutorials_correlation_matrices_building_12_2.png
-docs/build/html/_images/tutorials_correlation_matrices_building_15_2.png
-docs/build/html/_images/tutorials_correlation_matrices_building_17_1.png
-docs/build/html/_images/tutorials_correlation_matrices_building_21_2.png
+docs/build/html/_images/tutorials_correlation_matrices_building_12_1.png
+docs/build/html/_images/tutorials_correlation_matrices_building_16_2.png
+docs/build/html/_images/tutorials_correlation_matrices_building_21_1.png
 docs/build/html/_images/tutorials_correlation_matrices_building_25_2.png
-docs/build/html/_images/tutorials_correlation_matrices_building_27_1.png
-docs/build/html/_images/tutorials_correlation_matrices_building_30_2.png
-docs/build/html/_images/tutorials_correlation_matrices_building_32_1.png
-docs/build/html/_images/tutorials_correlation_matrices_building_34_1.png
+docs/build/html/_images/tutorials_correlation_matrices_building_29_2.png
+docs/build/html/_images/tutorials_correlation_matrices_building_31_1.png
+docs/build/html/_images/tutorials_correlation_matrices_building_34_2.png
+docs/build/html/_images/tutorials_correlation_matrices_building_36_1.png
+docs/build/html/_images/tutorials_correlation_matrices_building_38_1.png
 docs/build/html/_images/tutorials_correlation_matrices_building_8_1.png
 docs/build/html/_static/file.png
 docs/build/html/_static/minus.png
 docs/build/html/_static/plus.png
 docs/source/api_reference.rst
 docs/source/authors.rst
 docs/source/bibliography.rst
@@ -46,14 +46,15 @@
 docs/source/_autosummary/pyesmda.ESMDA.rst
 docs/source/_autosummary/pyesmda.ESMDA_RS.rst
 docs/source/_autosummary/pyesmda.approximate_cov_mm.rst
 docs/source/_autosummary/pyesmda.approximate_covariance_matrix_from_ensembles.rst
 docs/source/_autosummary/pyesmda.check_nans_in_predictions.rst
 docs/source/_autosummary/pyesmda.compute_ensemble_average_normalized_objective_function.rst
 docs/source/_autosummary/pyesmda.compute_normalized_objective_function.rst
+docs/source/_autosummary/pyesmda.get_ensemble_variance.rst
 docs/source/_autosummary/pyesmda.inflate_ensemble_around_its_mean.rst
 docs/source/_templates/class.rst
 docs/source/_templates/custom-module-template.rst
 docs/source/_templates/module.rst
 docs/source/_templates/autosummary/base.rst
 docs/source/_templates/autosummary/class.rst
 docs/source/_templates/autosummary/module.rst
```

### Comparing `pyesmda-0.3.3/tests/test_esmda_rs.py` & `pyesmda-0.4.0/tests/test_esmda_rs.py`

 * *Files identical despite different names*

### Comparing `pyesmda-0.3.3/tests/test_utils.py` & `pyesmda-0.4.0/tests/test_utils.py`

 * *Files 11% similar despite different names*

```diff
@@ -9,36 +9,35 @@
 import pytest
 
 from pyesmda.utils import (
     approximate_covariance_matrix_from_ensembles,
     check_nans_in_predictions,
     compute_ensemble_average_normalized_objective_function,
     compute_normalized_objective_function,
+    get_ensemble_variance,
     inflate_ensemble_around_its_mean,
 )
 
 
 @contextmanager
 def does_not_raise():
     yield
 
 
 def test_normalized_objective_function():
-
     pred = np.ones((20))
     obs = np.ones((20)) * 2.0
     obs_cov = np.diag(np.ones((20)) * 0.5)
     assert compute_normalized_objective_function(pred, obs, obs_cov) == 1.0
 
     obs_cov = np.diag(np.ones((20)) * 2.0)
     assert compute_normalized_objective_function(pred, obs, obs_cov) == 0.25
 
 
 def test_ensemble_average_normalized_objective_function():
-
     pred = np.ones((10, 20))
     obs = np.ones((20)) * 2
     obs_cov = np.diag(np.ones((20)) * 0.5)
     assert (
         compute_ensemble_average_normalized_objective_function(pred, obs, obs_cov)
         == 1.0
     )
@@ -88,24 +87,35 @@
 ) -> None:
     with expected_exception:
         np.testing.assert_almost_equal(
             approximate_covariance_matrix_from_ensembles(ens1, ens2), expected
         )
 
 
-def test_inflate_ensemble_around_its_mean_factor_1() -> None:
+def test_get_ensemble_variance():
+    ens = np.random.random((6, 6)) * 4.0
+
+    np.testing.assert_almost_equal(
+        approximate_covariance_matrix_from_ensembles(ens, ens).diagonal(),
+        get_ensemble_variance(ens),
+    )
 
+    # must be 2D !
+    with pytest.raises(ValueError):
+        get_ensemble_variance(np.array((3.0)))
+
+
+def test_inflate_ensemble_around_its_mean_factor_1() -> None:
     ensemble = np.ones((10, 10))
     inflated = inflate_ensemble_around_its_mean(ensemble, 1.0)
 
     np.testing.assert_equal(ensemble, inflated)
 
 
 def test_inflate_ensemble_around_its_mean_random() -> None:
-
     rng = np.random.default_rng(0)
     ensemble = rng.normal(1.0, 2.0, size=(10, 10))
     inflated = inflate_ensemble_around_its_mean(ensemble, 2.0)
 
     # std * 2
     np.testing.assert_allclose(np.std(ensemble, axis=0) * 2.0, np.std(inflated, axis=0))
     # the mean does not change
@@ -161,10 +171,9 @@
                     r"NaN values are found in predictions for members \[0, 2\] !"
                 ),
             ),
         ),
     ],
 )
 def test_check_nans_in_predictions(d_pred, assimilation_step, expected_exception):
-
     with expected_exception:
         check_nans_in_predictions(d_pred, assimilation_step)
```

