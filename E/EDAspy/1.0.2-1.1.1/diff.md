# Comparing `tmp/EDAspy-1.0.2.tar.gz` & `tmp/EDAspy-1.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "EDAspy-1.0.2.tar", last modified: Thu Oct 20 09:57:06 2022, max compression
+gzip compressed data, was "EDAspy-1.1.1.tar", last modified: Wed Jun 28 09:36:11 2023, max compression
```

## Comparing `EDAspy-1.0.2.tar` & `EDAspy-1.1.1.tar`

### file list

```diff
@@ -1,58 +1,73 @@
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:06.042637 EDAspy-1.0.2/
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:05.948897 EDAspy-1.0.2/EDAspy/
--rw-rw-rw-   0        0        0       82 2022-09-14 14:14:18.000000 EDAspy-1.0.2/EDAspy/__init__.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:05.964521 EDAspy-1.0.2/EDAspy/benchmarks/
--rw-rw-rw-   0        0        0      135 2022-09-07 14:49:50.000000 EDAspy-1.0.2/EDAspy/benchmarks/__init__.py
--rw-rw-rw-   0        0        0      328 2022-09-14 13:26:35.000000 EDAspy-1.0.2/EDAspy/benchmarks/binary.py
--rw-rw-rw-   0        0        0    13615 2022-09-14 13:41:08.000000 EDAspy-1.0.2/EDAspy/benchmarks/continuous.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:05.964521 EDAspy-1.0.2/EDAspy/optimization/
--rw-rw-rw-   0        0        0      170 2022-09-09 09:20:23.000000 EDAspy-1.0.2/EDAspy/optimization/__init__.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:05.980144 EDAspy-1.0.2/EDAspy/optimization/custom/
--rw-rw-rw-   0        0        0      265 2022-09-09 09:22:46.000000 EDAspy-1.0.2/EDAspy/optimization/custom/__init__.py
--rw-rw-rw-   0        0        0     6162 2022-09-14 11:36:08.000000 EDAspy-1.0.2/EDAspy/optimization/custom/eda_custom.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:05.995767 EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/
--rw-rw-rw-   0        0        0      287 2022-09-13 14:30:44.000000 EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/__init__.py
--rw-rw-rw-   0        0        0      345 2022-09-08 08:18:43.000000 EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/_generation_init.py
--rw-rw-rw-   0        0        0     2016 2022-09-13 14:30:44.000000 EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/multi_gauss_gininit.py
--rw-rw-rw-   0        0        0     1226 2022-09-14 11:34:13.000000 EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/uni_bin_geninit.py
--rw-rw-rw-   0        0        0     2075 2022-09-13 14:30:44.000000 EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/uni_gauss_geninit.py
--rw-rw-rw-   0        0        0     1145 2022-09-13 14:30:44.000000 EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/uniform_geninit.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:06.011390 EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/
--rw-rw-rw-   0        0        0      286 2022-09-13 14:29:45.000000 EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/__init__.py
--rw-rw-rw-   0        0        0      567 2022-09-08 10:10:55.000000 EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/_probabilistic_model.py
--rw-rw-rw-   0        0        0     2411 2022-10-17 10:28:40.000000 EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/gaussian_bayesian_network.py
--rw-rw-rw-   0        0        0     2012 2022-09-14 11:35:38.000000 EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/multivariate_gaussian.py
--rw-rw-rw-   0        0        0     1809 2022-10-06 10:03:09.000000 EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/univariate_binary.py
--rw-rw-rw-   0        0        0     1722 2022-09-13 14:29:45.000000 EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/univariate_gaussian.py
--rw-rw-rw-   0        0        0     6145 2022-09-14 11:36:57.000000 EDAspy-1.0.2/EDAspy/optimization/eda.py
--rw-rw-rw-   0        0        0     1245 2022-09-13 14:11:59.000000 EDAspy-1.0.2/EDAspy/optimization/eda_result.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:06.011390 EDAspy-1.0.2/EDAspy/optimization/multivariate/
--rw-rw-rw-   0        0        0      107 2022-09-08 14:20:39.000000 EDAspy-1.0.2/EDAspy/optimization/multivariate/__init__.py
--rw-rw-rw-   0        0        0     3611 2022-09-13 14:39:52.000000 EDAspy-1.0.2/EDAspy/optimization/multivariate/egna.py
--rw-rw-rw-   0        0        0     3910 2022-09-09 09:09:59.000000 EDAspy-1.0.2/EDAspy/optimization/multivariate/emna.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:06.011390 EDAspy-1.0.2/EDAspy/optimization/univariate/
--rw-rw-rw-   0        0        0      127 2022-09-08 14:20:28.000000 EDAspy-1.0.2/EDAspy/optimization/univariate/__init__.py
--rw-rw-rw-   0        0        0     3933 2022-09-08 09:44:57.000000 EDAspy-1.0.2/EDAspy/optimization/univariate/umda_binary.py
--rw-rw-rw-   0        0        0     4290 2022-09-14 10:23:02.000000 EDAspy-1.0.2/EDAspy/optimization/univariate/umda_continuous.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:06.027013 EDAspy-1.0.2/EDAspy/timeseries/
--rw-rw-rw-   0        0        0     5225 2021-08-23 12:21:42.000000 EDAspy-1.0.2/EDAspy/timeseries/TS_transformations.py
--rw-rw-rw-   0        0        0    12110 2022-09-08 14:33:22.000000 EDAspy-1.0.2/EDAspy/timeseries/TransformationsFeatureSelection.py
--rw-rw-rw-   0        0        0      212 2022-09-14 10:28:48.000000 EDAspy-1.0.2/EDAspy/timeseries/__init__.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:05.948897 EDAspy-1.0.2/EDAspy.egg-info/
--rw-rw-rw-   0        0        0     5815 2022-10-20 09:57:05.000000 EDAspy-1.0.2/EDAspy.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1794 2022-10-20 09:57:05.000000 EDAspy-1.0.2/EDAspy.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2022-10-20 09:57:05.000000 EDAspy-1.0.2/EDAspy.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       44 2022-10-20 09:57:05.000000 EDAspy-1.0.2/EDAspy.egg-info/requires.txt
--rw-rw-rw-   0        0        0       13 2022-10-20 09:57:05.000000 EDAspy-1.0.2/EDAspy.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     1066 2022-09-14 14:33:53.000000 EDAspy-1.0.2/LICENSE
--rw-rw-rw-   0        0        0     5815 2022-10-20 09:57:06.027013 EDAspy-1.0.2/PKG-INFO
--rw-rw-rw-   0        0        0     4062 2022-09-30 13:46:01.000000 EDAspy-1.0.2/README.md
--rw-rw-rw-   0        0        0       42 2022-10-20 09:57:06.042637 EDAspy-1.0.2/setup.cfg
--rw-rw-rw-   0        0        0     1479 2022-10-20 09:55:01.000000 EDAspy-1.0.2/setup.py
-drwxrwxrwx   0        0        0        0 2022-10-20 09:57:06.027013 EDAspy-1.0.2/tests/
--rw-rw-rw-   0        0        0       70 2021-08-23 12:21:42.000000 EDAspy-1.0.2/tests/__init__.py
--rw-rw-rw-   0        0        0     1518 2022-09-08 13:47:48.000000 EDAspy-1.0.2/tests/test_egna.py
--rw-rw-rw-   0        0        0     1518 2022-09-08 13:46:19.000000 EDAspy-1.0.2/tests/test_emna.py
--rw-rw-rw-   0        0        0     1071 2022-09-13 13:34:16.000000 EDAspy-1.0.2/tests/test_geninit.py
--rw-rw-rw-   0        0        0     2650 2022-09-08 11:12:09.000000 EDAspy-1.0.2/tests/test_umdac.py
--rw-rw-rw-   0        0        0     2488 2022-09-08 11:21:48.000000 EDAspy-1.0.2/tests/test_umdad.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.260216 EDAspy-1.1.1/
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.182216 EDAspy-1.1.1/EDAspy/
+-rw-rw-rw-   0        0        0       82 2023-06-28 09:34:02.000000 EDAspy-1.1.1/EDAspy/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.192217 EDAspy-1.1.1/EDAspy/benchmarks/
+-rw-rw-rw-   0        0        0      141 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/benchmarks/__init__.py
+-rw-rw-rw-   0        0        0      328 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/benchmarks/binary.py
+-rw-rw-rw-   0        0        0    13889 2023-03-22 14:02:48.000000 EDAspy-1.1.1/EDAspy/benchmarks/continuous.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.199218 EDAspy-1.1.1/EDAspy/optimization/
+-rw-rw-rw-   0        0        0      255 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.201218 EDAspy-1.1.1/EDAspy/optimization/custom/
+-rw-rw-rw-   0        0        0      286 2023-03-22 11:51:12.000000 EDAspy-1.1.1/EDAspy/optimization/custom/__init__.py
+-rw-rw-rw-   0        0        0     6162 2023-03-22 13:46:56.000000 EDAspy-1.1.1/EDAspy/optimization/custom/eda_custom.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.209223 EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/
+-rw-rw-rw-   0        0        0      287 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/__init__.py
+-rw-rw-rw-   0        0        0      345 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/_generation_init.py
+-rw-rw-rw-   0        0        0     2016 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/multi_gauss_geninit.py
+-rw-rw-rw-   0        0        0     1226 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/uni_bin_geninit.py
+-rw-rw-rw-   0        0        0     2069 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/uni_gauss_geninit.py
+-rw-rw-rw-   0        0        0     1131 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/uniform_geninit.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.219216 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/
+-rw-rw-rw-   0        0        0      414 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/__init__.py
+-rw-rw-rw-   0        0        0      605 2023-05-16 18:02:37.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/_probabilistic_model.py
+-rw-rw-rw-   0        0        0     8579 2023-05-23 10:49:59.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/gaussian_bayesian_network.py
+-rw-rw-rw-   0        0        0     3595 2023-06-28 09:02:13.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/kde_bayesian_network.py
+-rw-rw-rw-   0        0        0     2002 2023-06-28 09:02:13.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/multivariate_gaussian.py
+-rw-rw-rw-   0        0        0     3807 2023-06-28 09:02:13.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/semiparametric_bayesian_network.py
+-rw-rw-rw-   0        0        0     1988 2023-06-28 09:02:13.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/univariate_binary.py
+-rw-rw-rw-   0        0        0     1775 2023-06-28 09:02:13.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/univariate_gaussian.py
+-rw-rw-rw-   0        0        0     1312 2023-06-28 09:02:13.000000 EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/univariate_kde.py
+-rw-rw-rw-   0        0        0     8484 2023-06-28 09:02:13.000000 EDAspy-1.1.1/EDAspy/optimization/eda.py
+-rw-rw-rw-   0        0        0     1400 2023-04-17 15:35:01.000000 EDAspy-1.1.1/EDAspy/optimization/eda_result.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.227217 EDAspy-1.1.1/EDAspy/optimization/multivariate/
+-rw-rw-rw-   0        0        0      169 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/multivariate/__init__.py
+-rw-rw-rw-   0        0        0     4390 2023-03-22 13:46:11.000000 EDAspy-1.1.1/EDAspy/optimization/multivariate/egna.py
+-rw-rw-rw-   0        0        0     4370 2023-03-22 13:45:37.000000 EDAspy-1.1.1/EDAspy/optimization/multivariate/emna.py
+-rw-rw-rw-   0        0        0     5298 2023-03-22 13:45:15.000000 EDAspy-1.1.1/EDAspy/optimization/multivariate/keda.py
+-rw-rw-rw-   0        0        0     5645 2023-03-22 13:44:32.000000 EDAspy-1.1.1/EDAspy/optimization/multivariate/speda.py
+-rw-rw-rw-   0        0        0     4148 2023-03-22 15:59:36.000000 EDAspy-1.1.1/EDAspy/optimization/tools.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.232217 EDAspy-1.1.1/EDAspy/optimization/univariate/
+-rw-rw-rw-   0        0        0      161 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/optimization/univariate/__init__.py
+-rw-rw-rw-   0        0        0     3589 2023-03-22 13:43:52.000000 EDAspy-1.1.1/EDAspy/optimization/univariate/keda.py
+-rw-rw-rw-   0        0        0     4449 2023-03-22 13:43:06.000000 EDAspy-1.1.1/EDAspy/optimization/univariate/umda_binary.py
+-rw-rw-rw-   0        0        0     4811 2023-03-22 15:03:36.000000 EDAspy-1.1.1/EDAspy/optimization/univariate/umda_continuous.py
+-rw-rw-rw-   0        0        0     1500 2023-03-28 13:56:07.000000 EDAspy-1.1.1/EDAspy/optimization/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.236254 EDAspy-1.1.1/EDAspy/timeseries/
+-rw-rw-rw-   0        0        0     5225 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/timeseries/TS_transformations.py
+-rw-rw-rw-   0        0        0    12110 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/timeseries/TransformationsFeatureSelection.py
+-rw-rw-rw-   0        0        0      212 2023-03-22 11:48:09.000000 EDAspy-1.1.1/EDAspy/timeseries/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.188217 EDAspy-1.1.1/EDAspy.egg-info/
+-rw-rw-rw-   0        0        0     9492 2023-06-28 09:36:11.000000 EDAspy-1.1.1/EDAspy.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     2341 2023-06-28 09:36:11.000000 EDAspy-1.1.1/EDAspy.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 09:36:11.000000 EDAspy-1.1.1/EDAspy.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       13 2023-06-28 09:36:11.000000 EDAspy-1.1.1/EDAspy.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     1066 2023-03-22 11:48:09.000000 EDAspy-1.1.1/LICENSE
+-rw-rw-rw-   0        0        0     9492 2023-06-28 09:36:11.260216 EDAspy-1.1.1/PKG-INFO
+-rw-rw-rw-   0        0        0     7427 2023-06-28 09:02:13.000000 EDAspy-1.1.1/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 09:36:11.261218 EDAspy-1.1.1/setup.cfg
+-rw-rw-rw-   0        0        0     1491 2023-06-28 09:35:27.000000 EDAspy-1.1.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:36:11.258217 EDAspy-1.1.1/tests/
+-rw-rw-rw-   0        0        0       70 2023-03-22 14:18:16.000000 EDAspy-1.1.1/tests/__init__.py
+-rw-rw-rw-   0        0        0     5770 2023-06-28 09:02:13.000000 EDAspy-1.1.1/tests/test_egna.py
+-rw-rw-rw-   0        0        0     4035 2023-03-22 14:15:38.000000 EDAspy-1.1.1/tests/test_emna.py
+-rw-rw-rw-   0        0        0      882 2023-03-22 14:36:23.000000 EDAspy-1.1.1/tests/test_gbn.py
+-rw-rw-rw-   0        0        0     1071 2023-03-22 11:48:09.000000 EDAspy-1.1.1/tests/test_geninit.py
+-rw-rw-rw-   0        0        0      889 2023-06-28 09:02:13.000000 EDAspy-1.1.1/tests/test_kdebn.py
+-rw-rw-rw-   0        0        0     4635 2023-03-16 15:58:02.000000 EDAspy-1.1.1/tests/test_keda.py
+-rw-rw-rw-   0        0        0     5076 2023-03-22 11:51:12.000000 EDAspy-1.1.1/tests/test_multivariate_keda.py
+-rw-rw-rw-   0        0        0     4788 2023-03-22 11:48:09.000000 EDAspy-1.1.1/tests/test_pm.py
+-rw-rw-rw-   0        0        0      886 2023-06-28 09:02:13.000000 EDAspy-1.1.1/tests/test_spbn.py
+-rw-rw-rw-   0        0        0     5954 2023-06-28 09:02:13.000000 EDAspy-1.1.1/tests/test_speda.py
+-rw-rw-rw-   0        0        0     5070 2023-03-22 14:13:52.000000 EDAspy-1.1.1/tests/test_umdac.py
+-rw-rw-rw-   0        0        0     4606 2023-06-28 09:02:13.000000 EDAspy-1.1.1/tests/test_umdad.py
+-rw-rw-rw-   0        0        0     3967 2023-06-28 09:02:13.000000 EDAspy-1.1.1/tests/test_univariate_keda.py
```

### Comparing `EDAspy-1.0.2/EDAspy/benchmarks/continuous.py` & `EDAspy-1.1.1/EDAspy/benchmarks/continuous.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,7 +1,10 @@
+#!/usr/bin/env python
+# coding: utf-8
+
 import numpy as np
 import os
 from typing import Union
 
 
 def _mod_sch_f(z_i, dim):
     if abs(z_i) <= 500:
@@ -21,90 +24,90 @@
     def __init__(self,
                  dim: int):
 
         """
         :param dim: number of variables to be evaluated in the cost function
         """
 
+        assert dim in [1, 10, 20, 30, 50, 100], 'The benchmarking set is not implemented for such dimension. Try one ' \
+                                                'of 1, 10, 20, 30, 50, 100.'
+
         self.d = dim
         self.package_directory = os.path.dirname(os.path.abspath(__file__))
 
     def _load_shift(self, number):
         text_file = open(os.path.join(self.package_directory, 'input_data', "shift_data_" + str(number) + ".txt"), "r")
         shifts = text_file.read().split()
+        text_file.close()
         return np.array(shifts[:self.d]).astype(float)
 
     def _load_rot(self, number):
         matrix_file = open(os.path.join(self.package_directory, 'input_data', "M_" + str(number) +
                                         "_D" + str(self.d) + ".txt"), "r")
-        matrix_file = matrix_file.read().split()
-        matrix_file = np.array(matrix_file).astype(float)
-        matrix_file = np.reshape(matrix_file, (self.d, self.d))
-        return matrix_file
+        matrix_file_read = matrix_file.read().split()
+        matrix_file.close()
+        matrix_file_read = np.array(matrix_file_read).astype(float)
+        matrix_file_read = np.reshape(matrix_file_read, (self.d, self.d))
+        return matrix_file_read
 
     def bent_cigar_function(self, x: Union[np.array, list]) -> float:
         """
         Bent Cigar function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         result = x[0]**2
         for i in range(1, self.d):
             result += x[i]**2
         result += (result*np.power(10, 6))
         return result
 
     def discuss_function(self, x: Union[np.array, list]) -> float:
         """
         Discuss function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         result = np.power(10, 6)*(x[0]**2)
         for i in range(1, self.d):
             result += x[i]**2
         return result
 
     def rosenbrock_function(self, x: Union[np.array, list]) -> float:
         """
         Rosenbrock’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         result = 0
         for i in range(self.d-1):
             result += (100*(x[i]**2 - x[i+1])**2 + (x[i] - 1)**2)
         return result
 
     def ackley_function(self, x: Union[np.array, list]) -> float:
         """
         Ackley’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum1 = sum([x[i]**2 for i in range(self.d)])
         sum2 = sum([np.cos(x[i]*2*np.pi) for i in range(self.d)])
         return -20*np.exp(-0.2*np.sqrt(sum1/self.d)) - np.exp(sum2/self.d) + 20 + np.e
 
     def weierstrass_function(self, x: Union[np.array, list]) -> float:
         """
         Weierstrass Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         a = 0.5
         b = 3
@@ -121,15 +124,14 @@
             f += aux_f1 - self.d * aux_f2
 
         return f
 
     def griewank_function(self, x: Union[np.array, list]) -> float:
         """
         Griewank’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         f = 0
         for i in range(self.d):
@@ -138,15 +140,14 @@
         for i in range(1, self.d):
             aux_ *= np.cos(x[i-1]/np.sqrt(i)) + 1
         return f - aux_
 
     def rastrigins_function(self, x: Union[np.array, list]) -> float:
         """
         Rastrigin’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         result = 0
         for i in range(len(x)):
@@ -158,30 +159,28 @@
         for i in range(1, len(x) + 1):
             result += ((10**6)**((i-1)/(len(x)-1)))*x[i-1]**2
         return result
 
     def mod_schwefels_function(self, x: Union[np.array, list]) -> float:
         """
         Modified Schwefel’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         result = 418.9829 * len(x)
         for i in range(1, len(x) + 1):
             z_i = x[i-1] + 4.209687462275036e+002
             result = result - _mod_sch_f(z_i, len(x))
         return result
 
     def katsuura_function(self, x: Union[np.array, list]) -> float:
         """
         Katsuura Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         aux = 1
         for i in range(1, self.d + 1):
@@ -191,253 +190,235 @@
             aux *= (1 + i*aux2)**(10/(self.d**1.2))
         aux = (aux * (10/(self.d**2))) - (10/self.d**2)
         return aux
 
     def happycat_function(self, x: Union[np.array, list]) -> float:
         """
         HappyCat Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         a = sum([x[i-1]**2 for i in range(1, self.d + 1)])
         result = abs(a - self.d)**0.25
         result += (0.5 * a + sum([x[i-1] for i in range(1, self.d + 1)]))/self.d + 0.5
         return result
 
     def hgbat_function(self, x: Union[np.array, list]) -> float:
         """
         HGBat Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         a = sum([x[i-1]**2 for i in range(1, self.d + 1)])
         b = sum([x[i-1] for i in range(1, self.d + 1)])
         result = (abs(a**2 - b**2)**0.5) + (0.5*a + b)/self.d + 0.5
         return result
 
     def expanded_scaffer_f6_function(self, x: Union[np.array, list]):
         """
         Expanded Scaffer’s F6 Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         result = sum([_scaffer_f6_function(x[i - 1], x[i]) for i in range(1, self.d)])
         result += _scaffer_f6_function(x[self.d - 1], x[0])
         return result
 
     def cec14_1(self, x: Union[np.array, list]) -> float:
         """
         Rotated High Conditioned Elliptic Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = np.array(x) - self._load_shift(1)
         mat = self._load_rot(1)
         f1 = self.high_conditioned_elliptic_function(np.dot(mat, sum_vectors)) + 100
         return f1
 
     def cec14_2(self, x: Union[np.array, list]) -> float:
         """
         Rotated Bent Cigar Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = np.array(x) - self._load_shift(2)
         mat = self._load_rot(2)
         f2 = self.bent_cigar_function(np.dot(mat, sum_vectors)) + 200
         return f2
 
     def cec14_3(self, x: Union[np.array, list]) -> float:
         """
         Rotated Discus Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = np.array(x) - self._load_shift(3)
         mat = self._load_rot(3)
         f3 = self.discuss_function(np.dot(mat, sum_vectors)) + 300
         return f3
 
     def cec14_4(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Rosenbrock’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = (2.048/100) * (np.array(x) - self._load_shift(4))
         mat = self._load_rot(4)
         f4 = self.rosenbrock_function(np.dot(mat, sum_vectors) + 1) + 400
         return f4
 
     def cec14_5(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Rosenbrock’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = np.array(x) - self._load_shift(5)
         mat = self._load_rot(5)
         f5 = self.ackley_function(np.dot(mat, sum_vectors)) + 800
         return f5
 
     def cec14_6(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Weierstrass Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = (0.5/100)*(np.array(x) - self._load_shift(6))
         mat = self._load_rot(6)
         f6 = self.ackley_function(np.dot(mat, sum_vectors)) + 600
         return f6
 
     def cec14_7(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Griewank’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = (600 / 100) * (np.array(x) - self._load_shift(7))
         mat = self._load_rot(7)
         f7 = self.griewank_function(np.dot(mat, sum_vectors)) + 700
         return f7
 
     def cec14_8(self, x: Union[np.array, list]) -> float:
         """
         Shifted Rastrigin’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = 5.12 / 100 * (np.array(x) - self._load_shift(8))
         f8 = self.rastrigins_function(sum_vectors) + 800
         return f8
 
     def cec14_9(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Rastrigin’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = (5.12 / 100) * (np.array(x) - self._load_shift(9))
         mat = self._load_rot(9)
 
         f9 = self.rastrigins_function(np.dot(mat, sum_vectors)) + 900
         return f9
 
     def cec14_10(self, x: Union[np.array, list]) -> float:
         """
         Shifted Schwefel’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = 10 * (np.array(x) - self._load_shift(10))
         f10 = self.mod_schwefels_function(sum_vectors) + 1000
         return f10
 
     def cec14_11(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Schwefel’s Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = 10 * (np.array(x) - self._load_shift(11))
         mat = self._load_rot(11)
         f11 = self.mod_schwefels_function(np.dot(mat, sum_vectors)) + 1100
         return f11
 
     def cec14_12(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Katsuura Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = 0.05 * (np.array(x) - self._load_shift(12))
         mat = self._load_rot(12)
         f12 = self.katsuura_function(np.dot(mat, sum_vectors)) + 1200
         return f12
 
     def cec14_13(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated HappyCat Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = 0.05 * (np.array(x) - self._load_shift(13))
         mat = self._load_rot(13)
         f13 = self.happycat_function(np.dot(mat, sum_vectors)) + 1300
         return f13
 
     def cec14_14(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated HGBat Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = 0.05 * (np.array(x) - self._load_shift(14))
         mat = self._load_rot(14)
         f14 = self.hgbat_function(np.dot(mat, sum_vectors)) + 1400
         return f14
 
     def cec14_16(self, x: Union[np.array, list]) -> float:
         """
         Shifted and Rotated Expanded Scaffer’s F6 Function
-
         :param x: solution to be evaluated
         :return: solution evaluation
         :rtype: float
         """
 
         sum_vectors = np.array(x) - self._load_shift(16)
         mat = self._load_rot(16)
         f16 = self.expanded_scaffer_f6_function(np.dot(mat, sum_vectors) + 1) + 1600
-        return f16
+        return f16
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/eda_custom.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/eda_custom.py`

 * *Files identical despite different names*

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/multi_gauss_gininit.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/multi_gauss_geninit.py`

 * *Files 11% similar despite different names*

```diff
@@ -29,16 +29,16 @@
         :param upper_bound: upper bound for the random covariance matrix.
         """
 
         super().__init__(n_variables)
         assert len(means_vector) == len(cov_matrix), "Lengths of means vector and covariance matrix must be the same."
 
         if len(means_vector) == 0:
-            self.means_vector = np.random.randint(low=lower_bound, high=upper_bound, size=n_variables)
-            self.cov_matrix = np.random.randint(low=lower_bound, high=upper_bound, size=(n_variables, n_variables))
+            self.means_vector = np.random.choice(np.arange(lower_bound, upper_bound + 1), n_variables)
+            self.cov_matrix = np.random.choice(np.arange(lower_bound, upper_bound + 1), (n_variables, n_variables))
         else:
             self.means_vector = means_vector
             self.cov_matrix = cov_matrix
 
         self.pm = MultiGauss(list(range(n_variables)), lower_bound, upper_bound)
         self.pm.pm_means = self.means_vector
         self.pm.pm_cov = self.cov_matrix
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/uni_bin_geninit.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/uni_bin_geninit.py`

 * *Files 10% similar despite different names*

```diff
@@ -21,15 +21,15 @@
         super().__init__(n_variables)
 
         if len(means_vector) == 0:
             self.means_vector = np.array([0.5] * self.n_variables)
         else:
             self.means_vector = means_vector
 
-        self.pm = UniBin(list(range(self.n_variables)), lower_bound=0, upper_bound=0)  # dismiss bounds
+        self.pm = UniBin(list(range(self.n_variables)), lower_bound=0, upper_bound=1)  # dismiss bounds
         self.pm.pm = self.means_vector
 
         self.id = 2
 
     def sample(self, size: int) -> np.array:
         """
         Sample several times the initializator.
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/uni_gauss_geninit.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/uni_gauss_geninit.py`

 * *Files 6% similar despite different names*

```diff
@@ -30,17 +30,17 @@
         """
 
         super().__init__(n_variables)
 
         assert len(means_vector) == len(stds_vector), "Lengths of means and stds vector must be the same."
 
         if len(means_vector) == 0:
-            self.means_vector = np.random.randint(low=lower_bound, high=higher_bound, size=n_variables)
+            self.means_vector = np.random.choice(np.arange(lower_bound, higher_bound+1), n_variables)
             # the stds are random but using the lower_bound and higher_bound, minimizing the std
-            self.stds_vector = np.random.randint(low=abs(lower_bound/4), high=abs(higher_bound/2), size=n_variables)
+            self.stds_vector = np.random.choice(np.arange(abs(lower_bound/4), abs(higher_bound/2)), n_variables)
         else:
             self.means_vector = means_vector
             self.stds_vector = stds_vector
 
         self.pm = UniGauss(list(range(self.n_variables)), lower_bound)
         self.pm.pm = np.array([self.means_vector, self.stds_vector])
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/initialization_models/uniform_geninit.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/initialization_models/uniform_geninit.py`

 * *Files 12% similar despite different names*

```diff
@@ -34,8 +34,8 @@
         Sample several times the initializator.
 
         :param size: number of samplings.
         :return: array with the dataset sampled.
         :rtype: np.array.
         """
 
-        return np.random.randint(self.lower_bound, self.upper_bound, (size, self.n_variables)).astype(float)
+        return np.random.uniform(self.lower_bound, self.upper_bound, (size, self.n_variables))
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/_probabilistic_model.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/_probabilistic_model.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 #!/usr/bin/env python
 # coding: utf-8
 
 from abc import ABC, abstractmethod
 import numpy as np
+import pandas as pd
 
 
 class ProbabilisticModel(ABC):
 
     def __init__(self, variables: list):
         self.variables = variables
         self.len_variables = len(variables)
@@ -14,13 +15,13 @@
         self.id = -1
 
     @abstractmethod
     def sample(self, size: int):
         raise Exception("Not implemented method")
 
     @abstractmethod
-    def learn(self, dataset: np.array):
+    def learn(self, dataset: np.array, *args, **kwargs):
         raise Exception("Not implemented method")
 
     def export_settings(self):
         return self.id
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/gaussian_bayesian_network.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/univariate_gaussian.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,71 +1,51 @@
 #!/usr/bin/env python
 # coding: utf-8
 
 import numpy as np
-from pybnesian import GaussianNetwork, hc, GaussianNetworkType
 from ._probabilistic_model import ProbabilisticModel
-import pandas as pd
 
 
-class GBN(ProbabilisticModel):
+class UniGauss(ProbabilisticModel):
 
     """
-    This probabilistic model is  Gaussian Bayesian Network. All the relationships between the variables in
-    the model are defined to be linearly Gaussian, and the variables distributions are assumed to be
-    Gaussian. This is a very common approach when facing to continuous data as it is relatively easy and fast
-    to learn a Gaussian distributions between variables. This implementation uses Pybnesian library [1].
-
-    References:
-
-        [1]: Atienza, D., Bielza, C., & Larrañaga, P. (2022). PyBNesian: an extensible Python package
-        for Bayesian networks. Neurocomputing, 504, 204-209.
+    This class implements the univariate Gaussians. With this implementation we are updating N univariate Gaussians
+    in each iteration. When a dataset is given, each column is updated independently. The implementation involves a
+    matrix with two rows, in which the first row are the means and the second one, are the standard deviations.
     """
 
-    def __init__(self, variables: list):
-
-        """
-        :param variables: Number of variables
-        """
-
+    def __init__(self, variables: list, lower_bound: float):
         super().__init__(variables)
 
-        self.variables = variables
-        self.pm = GaussianNetwork(variables)
-
-        self.id = 4
+        self.pm = np.zeros((2, self.len_variables))
+        self.lower_bound = lower_bound
 
-    def learn(self, dataset: np.array):
-        """
-        Learn a Gaussian Bayesian network from the dataset passed as argument.
+        self.id = 1
 
-        :param dataset: dataset from which learn the GBN.
+    def sample(self, size: int) -> np.array:
         """
+        Samples new solutions from the probabilistic model. In each solution, each variable is sampled
+        from its respective normal distribution.
 
-        self.pm = GaussianNetwork(self.variables)
-        self.pm = hc(pd.DataFrame(dataset), bn_type=GaussianNetworkType())
-        self.pm.fit(pd.DataFrame(dataset))
-
-    def print_structure(self) -> list:
+        :param size: number of samplings of the probabilistic model.
+        :return: array with the dataset sampled
+        :rtype: np.array
         """
-        Prints the arcs between the nodes that represent the variables in the dataset. This function
-        must be used after the learning process.
+        return np.random.normal(
+            self.pm[0, :], self.pm[1, :], (size, self.len_variables)
+        )
 
-        :return: list of arcs between variables
-        :rtype: list
+    def learn(self, dataset: np.array, *args, **kwargs):
         """
+        Estimates the independent Gaussian for each variable.
 
-        return self.pm.arcs()
-
-    def sample(self, size: int) -> np.array:
+        :param dataset: dataset from which learn the probabilistic model.
         """
-        Samples the Gaussian Bayesian network several times defined by the user. The dataset is returned
-        as a numpy matrix. The sampling process is implemented using probabilistic logic sampling.
+        for i in range(len(self.variables)):
+            self.pm[0, i] = np.mean(dataset[:, i])
+            self.pm[1, i] = np.std(dataset[:, i])
 
-        :param size: number of samplings of the Gaussian Bayesian network.
-        :return: array with the dataset sampled.
-        :rtype: np.array
-        """
+            if self.pm[1, i] < self.lower_bound:
+                self.pm[1, i] = self.lower_bound
 
-        dataset = self.pm.sample(size).to_pandas()
-        dataset = dataset[self.variables].to_numpy()
-        return dataset
+    def print_structure(self) -> list:
+        return list()
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/multivariate_gaussian.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/multivariate_gaussian.py`

 * *Files 6% similar despite different names*

```diff
@@ -35,18 +35,17 @@
         is returned as a numpy matrix.
 
         :param size: number of samplings of the Gaussian Bayesian network.
         :return: array with the dataset sampled.
         :rtype: np.array
         """
 
-        dataset = np.random.multivariate_normal(self.pm_means, self.pm_cov, size)
-        return dataset
+        return np.random.multivariate_normal(self.pm_means, self.pm_cov, size)
 
-    def learn(self, dataset: np.array):
+    def learn(self, dataset: np.array, *args, **kwargs):
         """
         Estimates a multivariate Gaussian distribution from the dataset.
 
         :param dataset: dataset from which learn the multivariate Gaussian distribution.
         """
 
         for i in range(self.len_variables):
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/univariate_binary.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/univariate_binary.py`

 * *Files 3% similar despite different names*

```diff
@@ -13,14 +13,16 @@
     When sampling, a random float is sampled [0, 1]. If the float is below the probability, then the sampling
     is a 1. Thus, the probabilities show probabilities of a sampling being 1.
     """
 
     def __init__(self, variables: list, upper_bound: float, lower_bound: float):
         super().__init__(variables)
 
+        assert upper_bound > lower_bound, "The upper bound should be higher than lower bound"
+
         self.upper_bound = upper_bound
         self.lower_bound = lower_bound
 
         self.pm = np.zeros(self.len_variables)
 
         self.id = 2
 
@@ -35,17 +37,20 @@
         """
 
         dataset = np.random.random((size, self.len_variables))
         dataset = dataset < self.pm
         dataset = np.array(dataset, dtype=int)
         return dataset
 
-    def learn(self, dataset: np.array):
+    def learn(self, dataset: np.array, *args, **kwargs):
         """
         Estimates the independent probability of each variable of being 1.
 
         :param dataset: dataset from which learn the probabilistic model.
         """
 
         self.pm = sum(dataset) / len(dataset)
         self.pm[self.pm < self.lower_bound] = self.lower_bound
         self.pm[self.pm > self.upper_bound] = self.upper_bound
+
+    def print_structure(self) -> list:
+        return list()
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/custom/probabilistic_models/univariate_gaussian.py` & `EDAspy-1.1.1/EDAspy/optimization/custom/probabilistic_models/univariate_kde.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,50 +1,42 @@
 #!/usr/bin/env python
 # coding: utf-8
 
 import numpy as np
+from scipy.stats import gaussian_kde
 from ._probabilistic_model import ProbabilisticModel
 
 
-class UniGauss(ProbabilisticModel):
+class UniKDE(ProbabilisticModel):
 
     """
-    This class implements the univariate Gaussians. With this implementation we are updating N univariate Gaussians
-    in each iteration. When a dataset is given, each column is updated independently. The implementation involves a
-    matrix with two rows, in which the first row are the means and the second one, are the standard deviations.
+    This class implements the univariate Kernel Density Estimation. With this implementation we are updating N
+    univariate KDE in each iteration. When a dataset is given, each column is updated independently.
     """
 
-    def __init__(self, variables: list, lower_bound: float):
+    def __init__(self, variables: list):
         super().__init__(variables)
+        self.kernel = None
 
-        self.pm = np.zeros((2, self.len_variables))
-        self.lower_bound = lower_bound
-
-        self.id = 1
+        self.id = 7
 
     def sample(self, size: int) -> np.array:
         """
         Samples new solutions from the probabilistic model. In each solution, each variable is sampled
         from its respective normal distribution.
 
         :param size: number of samplings of the probabilistic model.
         :return: array with the dataset sampled
         :rtype: np.array
         """
+        return self.kernel.resample(size).T
 
-        dataset = np.random.normal(
-            self.pm[0, :], self.pm[1, :], [size, self.len_variables]
-        )
-        return dataset
-
-    def learn(self, dataset: np.array):
+    def learn(self, dataset: np.array, *args, **kwargs):
         """
-        Estimates the independent Gaussian for each variable.
+        Estimates the independent KDE for each variable.
 
         :param dataset: dataset from which learn the probabilistic model.
         """
-        for i in range(len(self.variables)):
-            self.pm[0, i] = np.mean(dataset[:, i])
-            self.pm[1, i] = np.std(dataset[:, i])
+        self.kernel = gaussian_kde(dataset.T)
 
-            if self.pm[1, i] < self.lower_bound:
-                self.pm[1, i] = self.lower_bound
+    def print_structure(self) -> list:
+        return list()
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/eda.py` & `EDAspy-1.1.1/EDAspy/optimization/eda.py`

 * *Files 24% similar despite different names*

```diff
@@ -2,14 +2,16 @@
 # coding: utf-8
 
 import numpy as np
 from abc import ABC
 from .eda_result import EdaResult
 from .custom.probabilistic_models import ProbabilisticModel
 from .custom.initialization_models import GenInit
+from .utils import _parallel_apply_along_axis
+from time import process_time
 
 
 class EDA(ABC):
 
     """
     Abstract class which defines the general performance of the algorithms. The baseline of the EDA
     approach is defined in this object. The specific configurations is defined in the class of each
@@ -22,40 +24,66 @@
     def __init__(self,
                  size_gen: int,
                  max_iter: int,
                  dead_iter: int,
                  n_variables: int,
                  alpha: float = 0.5,
                  elite_factor: float = 0.4,
-                 disp: bool = True):
+                 disp: bool = True,
+                 parallelize: bool = False,
+                 init_data: np.array = None,
+                 *args, **kwargs):
 
         self.disp = disp
         self.size_gen = size_gen
         self.max_iter = max_iter
         self.alpha = alpha
         self.n_variables = n_variables
         self.truncation_length = int(size_gen * alpha)
         self.elite_factor = elite_factor
         self.elite_length = int(size_gen * elite_factor)
+        self.parallelize = parallelize
 
         assert dead_iter <= self.max_iter, 'dead_iter must be lower than max_iter'
         self.dead_iter = dead_iter
 
         self.best_mae_global = 999999999999
-        self.best_ind_global = -1
+        self.best_ind_global = np.array([0]*self.n_variables)
+        # TODO: test if best ind global works
         self.evaluations = np.array(0)
 
         self.generation = None
 
+        if parallelize:
+            self._check_generation = self._check_generation_parallel
+        else:
+            self._check_generation = self._check_generation_no_parallel
+
+        # allow initialize EDA with data
+        if init_data is not None:
+            assert init_data.shape[1] == n_variables, 'The inserted data shape and the number of variables do not match'
+            # assert init_data.shape[0] == size_gen, 'The inserted data shape and the generation size do not match'
+
+            self.init_data = init_data
+            self._initialize_generation = self._initialize_generation_with_data
+        else:
+            self._initialize_generation = self._initialize_generation_with_init
+
     def _new_generation(self):
         self.generation = np.concatenate([self.pm.sample(size=self.size_gen), self.elite_temp])
 
-    def _initialize_generation(self) -> np.array:
+    def _initialize_generation_with_data(self) -> np.array:
+        return self.init_data
+
+    def _initialize_generation_with_init(self) -> np.array:
         return self.init.sample(size=self.size_gen)
 
+    def _initialize_generation(self) -> np.array:
+        raise Exception('Not implemented function')
+
     def _truncation(self):
         """
         Selection of the best individuals of the actual generation.
         """
         ordering = self.evaluations.argsort()
         best_indices_truc = ordering[: self.truncation_length]
         best_indices_elit = ordering[: self.elite_length]
@@ -65,48 +93,61 @@
 
     # check each individual of the generation
     def _check_generation(self, objective_function: callable):
         """
         Check the cost of each individual in the cost function implemented by the user, and updates the
         generation DataFrame.
         """
+        raise Exception('Not implemented function')
+
+    def _check_generation_parallel(self, objective_function: callable):
+        self.evaluations = _parallel_apply_along_axis(objective_function, 1, self.generation)
+
+    def _check_generation_no_parallel(self, objective_function: callable):
         self.evaluations = np.apply_along_axis(objective_function, 1, self.generation)
 
     def _update_pm(self):
         """
         Learn the probabilistic model from the best individuals of previous generation.
         """
         self.pm.learn(dataset=self.generation)
 
     def export_settings(self) -> dict:
         """
         Export the configuration of the algorithm to an object to be loaded in other execution.
-        :return: dict
+
+        :return: configuration dictionary.
+        :rtype: dict
         """
         return {
             "size_gen": self.size_gen,
             "max_iter": self.max_iter,
             "dead_iter": self.dead_iter,
             "n_variables": self.n_variables,
             "alpha": self.alpha,
             "elite_factor": self.elite_factor,
-            "disp": self.disp
+            "disp": self.disp,
+            "parallelize": self.parallelize
         }
 
-    def minimize(self, cost_function: callable, output_runtime: bool = True):
-        r"""
+    def minimize(self, cost_function: callable, output_runtime: bool = True, *args, **kwargs) -> EdaResult:
+        """
+        Minimize function to execute the EDA optimization. By default, the optimizer is designed to minimize a cost
+        function; if maximization is desired, just add a minus sign to your cost function.
+
         :param cost_function: cost function to be optimized and accepts an array as argument.
         :param output_runtime: true if information during runtime is desired.
-        :return: EdaResult object
+        :return: EdaResult object with results and information.
         :rtype: EdaResult
         """
 
         history = []
         not_better = 0
 
+        t1 = process_time()
         self.generation = self._initialize_generation()
 
         for _ in range(self.max_iter):
             self._check_generation(cost_function)
             self._truncation()
             self._update_pm()
 
@@ -129,40 +170,53 @@
 
             self._new_generation()
 
             if output_runtime:
                 print('IT: ', _, '\tBest cost: ', self.best_mae_global)
 
         if self.disp:
-            print("\tNFVALS = " + str(len(history) * self.size_gen) + " F = " + str(self.best_mae_global))
+            print("\tNFEVALS = " + str(len(history) * self.size_gen) + " F = " + str(self.best_mae_global))
             print("\tX = " + str(self.best_ind_global))
 
+        t2 = process_time()
         eda_result = EdaResult(self.best_ind_global, self.best_mae_global, len(history) * self.size_gen,
-                               history, self.export_settings())
+                               history, self.export_settings(), t2-t1)
 
         return eda_result
 
     @property
-    def pm(self):
+    def pm(self) -> ProbabilisticModel:
+        """
+        Returns the probabilistic model used in the EDA implementation.
+
+        :return: probabilistic model.
+        :rtype: ProbabilisticModel
+        """
         return self._pm
 
     @pm.setter
     def pm(self, value):
         if isinstance(value, ProbabilisticModel):
             self._pm = value
         else:
             raise ValueError('The object you try to set as a probabilistic model does not extend the '
-                             'class ProbabilisticModel provided by EDAspy')
+                             'class ProbabilisticModel provided by EDAspy.')
 
         if len(value.variables) != self.n_variables:
             raise Exception('The number of variables of the probabilistic model is not equal to the number of '
-                            'variables of the EDA')
+                            'variables of the EDA.')
 
     @property
-    def init(self):
+    def init(self) -> GenInit:
+        """
+        Returns the initializer used in the EDA implementation.
+
+        :return: initializer.
+        :rtype: GenInit
+        """
         return self._init
 
     @init.setter
     def init(self, value):
         if isinstance(value, GenInit):
             self._init = value
         else:
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/eda_result.py` & `EDAspy-1.1.1/EDAspy/optimization/eda_result.py`

 * *Files 9% similar despite different names*

```diff
@@ -11,30 +11,32 @@
     """
 
     def __init__(self,
                  best_ind: np.array,
                  best_cost: float,
                  n_fev: int,
                  history: list,
-                 settings: dict):
+                 settings: dict,
+                 cpu_time: float):
 
         """
 
         :param best_ind: Best result found in the execution.
         :param best_cost: Cost of the best result found.
         :param n_fev: Number of cost function evaluations.
         :param history: Best result found in each iteration of the algorithm.
         :param settings: Configuration of the parameters of the EDA.
+        :param cpu_time: CPU time invested in the optimization.
         """
 
         self.best_ind = best_ind
         self.best_cost = best_cost
         self.n_fev = n_fev
         self.history = history
         self.settings = settings
+        self.cpu_time = cpu_time
 
     def __str__(self):
-        string = "\tNFVALS = " + str(self.n_fev) + " F = " + str(self.best_cost) + \
-                 "\n\tX = " + str(self.best_ind) + \
-                 "\n\tSettings: " + str(self.settings) + \
+        string = "\tNFVALS = " + str(self.n_fev) + " F = " + str(self.best_cost) + "CPU time (s) = " + \
+                 str(self.cpu_time) + "\n\tX = " + str(self.best_ind) + "\n\tSettings: " + str(self.settings) + \
                  "\n\tHistory best cost per iteration: " + str(self.history)
         return string
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/multivariate/egna.py` & `EDAspy-1.1.1/EDAspy/optimization/univariate/keda.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,74 +1,78 @@
 #!/usr/bin/env python
 # coding: utf-8
+import numpy as np
 
+from ..custom.probabilistic_models import UniKDE
+from ..custom.initialization_models import UniformGenInit
 from ..eda import EDA
-from ..custom.probabilistic_models import GBN
-from ..custom.initialization_models import MultiGaussGenInit
 
 
-class EGNA(EDA):
+class UnivariateKEDA(EDA):
     """
-    Estimation of Gaussian Networks Algorithm. This type of Estimation-of-Distribution Algorithm uses
-    a Gaussian Bayesian Network from where new solutions are sampled. This multivariate probabilistic
-    model is updated in each iteration with the best individuals of the previous generation.
-
-    EGNA [1] has shown to improve the results for more complex optimization problem compared to the
-    univariate EDAs that can be found implemented in this package. Different modifications have been
-    done into this algorithm such as in [2] where some evidences are input to the Gaussian Bayesian
-    Network in order to restrict the search space in the landscape.
+    Univariate Kernel Density Estimation Algorithm (u_KEDA). New individuals are sampled from a KDE model.
+    It can be used for hyper-parameter optimization or to optimize a function.
+
+    u_KEDA [1] is a specific type of Estimation of Distribution Algorithm (EDA) where new individuals
+    are sampled from univariate KDEs and are updated in each iteration of the algorithm by the best individuals
+    found in the previous iteration. In this implementation each individual is an array of real data so new
+    individuals are sampled from a univariate probabilistic model updated in each iteration.
 
     Example:
 
-        This example uses some very well-known benchmarks from CEC14 conference to be solved using
-        an Estimation of Gaussian Networks Algorithm (EGNA).
+        This short example runs UMDAc for a benchmark function optimization problem in the continuous space.
 
         .. code-block:: python
 
-            from EDAspy.optimization import EGNA
             from EDAspy.benchmarks import ContinuousBenchmarkingCEC14
+            from EDAspy.optimization import UnivariateKEDA
 
-            benchmarking = ContinuousBenchmarkingCEC14(10)
-
-            egna = EGNA(size_gen=300, max_iter=100, dead_iter=20, n_variables=10,
-                        landscape_bounds=(-60, 60))
+            n_vars = 10
+            benchmarking = ContinuousBenchmarkingCEC14(n_vars)
 
-            eda_result = egna.minimize(benchmarking.cec14_4, True)
+            keda = UnivariateKEDA(size_gen=100, max_iter=100, dead_iter=10, n_variables=10, alpha=0.5)
+            # We leave bound by default
+            eda_result = keda.minimize(benchmarking.cec4, True)
 
     References:
 
         [1]: Larrañaga, P., & Lozano, J. A. (Eds.). (2001). Estimation of distribution algorithms:
         A new tool for evolutionary computation (Vol. 2). Springer Science & Business Media.
-
-        [2]: Vicente P. Soloviev, Pedro Larrañaga and Concha Bielza (2022). Estimation of distribution
-        algorithms using Gaussian Bayesian networks to solve industrial optimization problems constrained
-        by environment variables. Journal of Combinatorial Optimization.
     """
 
     def __init__(self,
                  size_gen: int,
                  max_iter: int,
                  dead_iter: int,
                  n_variables: int,
-                 landscape_bounds: tuple,
                  alpha: float = 0.5,
+                 landscape_bounds: tuple = (-100, 100),
                  elite_factor: float = 0.4,
-                 disp: bool = True):
+                 disp: bool = True,
+                 parallelize: bool = False,
+                 init_data: np.array = None):
         r"""
-            :param size_gen: Population size. Number of individuals in each generation.
-            :param max_iter: Maximum number of iterations during runtime.
-            :param dead_iter: Stopping criteria. Number of iterations with no improvement after which, the algorithm finish.
-            :param n_variables: Number of variables to be optimized.
-            :param landscape_bounds: Landscape bounds only for initialization. Limits in the search space.
-            :param alpha: Percentage of population selected to update the probabilistic model.
-            :param elite_factor: Percentage of previous population selected to add to new generation (elite approach).
-            :param disp: Set to True to print convergence messages.
+        Args:
+            size_gen: Population size of each generation.
+            max_iter: Maximum number of function evaluations.
+            dead_iter: Stopping criteria. Number of iterations after with no improvement after which EDA stops.
+            n_variables: Number of variables to be optimized.
+            alpha: Percentage of population selected to update the probabilistic model.
+            landscape_bounds: Landscape bounds.
+            elite_factor: Percentage of previous population selected to add to new generation (elite approach).
+            disp: Set to True to print convergence messages.
+            parallelize: True if the evaluation of the solutions is desired to be parallelized in multiple cores.
+            init_data: Numpy array containing the data the EDA is desired to be initialized from. By default, an
+            initializer is used.
         """
 
-        super().__init__(size_gen=size_gen, max_iter=max_iter, dead_iter=dead_iter,
-                         n_variables=n_variables, alpha=alpha, elite_factor=elite_factor, disp=disp)
-
-        self.vars = [str(i) for i in range(n_variables)]
         self.landscape_bounds = landscape_bounds
-        self.pm = GBN(self.vars)
-        self.init = MultiGaussGenInit(self.n_variables, lower_bound=self.landscape_bounds[0],
-                                      upper_bound=self.landscape_bounds[1])
+        self.names_vars = list(range(n_variables))
+
+        super().__init__(size_gen=size_gen, max_iter=max_iter, dead_iter=dead_iter, n_variables=n_variables,
+                         alpha=alpha, elite_factor=elite_factor, disp=disp, parallelize=parallelize,
+                         init_data=init_data)
+
+        self.init = UniformGenInit(n_variables=n_variables,
+                                   lower_bound=landscape_bounds[0], upper_bound=landscape_bounds[1])
+
+        self.pm = UniKDE(self.names_vars)
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/multivariate/emna.py` & `EDAspy-1.1.1/EDAspy/optimization/multivariate/emna.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 #!/usr/bin/env python
 # coding: utf-8
+import numpy as np
 
 from ..eda import EDA
 from ..custom.probabilistic_models import MultiGauss
 from ..custom.initialization_models import MultiGaussGenInit
 
 
 class EMNA(EDA):
@@ -49,29 +50,35 @@
                  dead_iter: int,
                  n_variables: int,
                  landscape_bounds: tuple,
                  alpha: float = 0.5,
                  elite_factor: float = 0.4,
                  disp: bool = True,
                  lower_bound: float = 0.5,
-                 upper_bound: float = 100):
+                 upper_bound: float = 100,
+                 parallelize: bool = False,
+                 init_data: np.array = None):
         r"""
             :param size_gen: Population size. Number of individuals in each generation.
             :param max_iter: Maximum number of iterations during runtime.
             :param dead_iter: Stopping criteria. Number of iterations with no improvement after which, the algorithm finish.
             :param n_variables: Number of variables to be optimized.
             :param landscape_bounds: Landscape bounds only for initialization. Limits in the search space.
             :param alpha: Percentage of population selected to update the probabilistic model.
             :param elite_factor: Percentage of previous population selected to add to new generation (elite approach).
             :param lower_bound: Lower bound imposed in std of the variables to not converge to std=0.
             :param upper_bound: Upper bound imposed in std of the variables.
             :param disp: Set to True to print convergence messages.
+            :param parallelize: True if the evaluation of the solutions is desired to be parallelized in multiple cores.
+            :param init_data: Numpy array containing the data the EDA is desired to be initialized from. By default, an
+            initializer is used.
         """
         super().__init__(size_gen=size_gen, max_iter=max_iter, dead_iter=dead_iter,
-                         n_variables=n_variables, alpha=alpha, elite_factor=elite_factor, disp=disp)
+                         n_variables=n_variables, alpha=alpha, elite_factor=elite_factor, disp=disp,
+                         parallelize=parallelize, init_data=init_data)
 
         assert len(landscape_bounds) == 2, "The size of the landscape bounds tuple is different from 2"
         self.landscape_bounds = landscape_bounds
 
         self.lower_bound = lower_bound
         self.upper_bound = upper_bound
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/univariate/umda_binary.py` & `EDAspy-1.1.1/EDAspy/optimization/univariate/umda_binary.py`

 * *Files 6% similar despite different names*

```diff
@@ -52,30 +52,37 @@
                  dead_iter: int,
                  n_variables: int,
                  alpha: float = 0.5,
                  vector: np.array = None,
                  lower_bound: float = 0.2,
                  upper_bound: float = 0.8,
                  elite_factor: float = 0.4,
-                 disp: bool = True):
+                 disp: bool = True,
+                 parallelize: bool = False,
+                 init_data: np.array = None):
         r"""
         Args:
             size_gen: Population size of each generation.
             max_iter: Maximum number of function evaluations.
             dead_iter: Stopping criteria. Number of iterations after with no improvement after which EDA stops.
             n_variables: Number of variables to be optimized.
             alpha: Percentage of population selected to update the probabilistic model.
             vector: Array with shape (n_variables, ) where rows are mean and std of the parameters to be optimized.
             lower_bound: Lower bound imposed to the probabilities of the variables. If not desired, set to 0.
             upper_bound: Upper bound imposed to the probabilities of the variables. If not desired, set to 1.
             elite_factor: Percentage of previous population selected to add to new generation (elite approach).
             disp: Set to True to print convergence messages.
+            parallelize: True if the evaluation of the solutions is desired to be parallelized in multiple cores.
+            init_data: Numpy array containing the data the EDA is desired to be initialized from. By default, an
+            initializer is used.
         """
 
-        super().__init__(size_gen, max_iter, dead_iter, n_variables, alpha, elite_factor, disp)
+        super().__init__(size_gen=size_gen, max_iter=max_iter, dead_iter=dead_iter, n_variables=n_variables,
+                         alpha=alpha, elite_factor=elite_factor, disp=disp, parallelize=parallelize,
+                         init_data=init_data)
 
         self.lower_bound = lower_bound
         self.upper_bound = upper_bound
 
         self.vector = vector
 
         self.names_vars = list(range(self.n_variables))
```

### Comparing `EDAspy-1.0.2/EDAspy/optimization/univariate/umda_continuous.py` & `EDAspy-1.1.1/EDAspy/optimization/univariate/umda_continuous.py`

 * *Files 5% similar despite different names*

```diff
@@ -12,25 +12,25 @@
     Univariate marginal Estimation of Distribution algorithm continuous. New individuals are sampled
     from a univariate normal probabilistic model. It can be used for hyper-parameter optimization
     or to optimize a function.
 
     UMDA [1] is a specific type of Estimation of Distribution Algorithm (EDA) where new individuals
     are sampled from univariate normal distributions and are updated in each iteration of the
     algorithm by the best individuals found in the previous iteration. In this implementation each
-    individual is an array of 0s and 1s so new individuals are sampled from a univariate probabilistic
+    individual is an array of real data so new individuals are sampled from a univariate probabilistic
     model updated in each iteration. Optionally it is possible to set lower bound to the standard
     deviation of the normal distribution for the variables to avoid premature convergence.
 
     This algorithms has been widely used for different applications such as in [2] where it is
     applied to optimize the parameters of a quantum paremetric circuit and is shown how it outperforms
     other approaches in specific situations.
 
     Example:
 
-        This short example runs UMDAc for a toy example of the One-Max problem in the continuous space.
+        This short example runs UMDAc for a benchmark function optimization problem in the continuous space.
 
         .. code-block:: python
 
             from EDAspy.benchmarks import ContinuousBenchmarkingCEC14
             from EDAspy.optimization import UMDAc
 
             n_vars = 10
@@ -55,33 +55,40 @@
                  max_iter: int,
                  dead_iter: int,
                  n_variables: int,
                  alpha: float = 0.5,
                  vector: np.array = None,
                  lower_bound: float = 0.5,
                  elite_factor: float = 0.4,
-                 disp: bool = True):
+                 disp: bool = True,
+                 parallelize: bool = False,
+                 init_data: np.array = None):
         r"""
         Args:
             size_gen: Population size of each generation.
             max_iter: Maximum number of function evaluations.
             dead_iter: Stopping criteria. Number of iterations after with no improvement after which EDA stops.
             n_variables: Number of variables to be optimized.
             alpha: Percentage of population selected to update the probabilistic model.
             vector: Array with shape (2, n_variables) where rows are mean and std of the parameters to be optimized.
             lower_bound: Lower bound imposed in std of the variables to not converge to std=0.
             elite_factor: Percentage of previous population selected to add to new generation (elite approach).
             disp: Set to True to print convergence messages.
+            parallelize: True if the evaluation of the solutions is desired to be parallelized in multiple cores.
+            init_data: Numpy array containing the data the EDA is desired to be initialized from. By default, an
+            initializer is used.
         """
 
         self.vector = vector
         self.lower_bound = lower_bound
         self.names_vars = list(range(n_variables))
 
-        super().__init__(size_gen, max_iter, dead_iter, n_variables, alpha, elite_factor, disp)
+        super().__init__(size_gen=size_gen, max_iter=max_iter, dead_iter=dead_iter, n_variables=n_variables,
+                         alpha=alpha, elite_factor=elite_factor, disp=disp, parallelize=parallelize,
+                         init_data=init_data)
 
         if self.vector is None:
             self.vector = np.zeros((2, n_variables))
             self.vector[0, :] = [0] * n_variables
             self.vector[1, :] = [100] * n_variables  # high value to ensure variance
         else:
             assert self.vector.shape == (2, n_variables)
```

### Comparing `EDAspy-1.0.2/EDAspy/timeseries/TS_transformations.py` & `EDAspy-1.1.1/EDAspy/timeseries/TS_transformations.py`

 * *Files identical despite different names*

### Comparing `EDAspy-1.0.2/EDAspy/timeseries/TransformationsFeatureSelection.py` & `EDAspy-1.1.1/EDAspy/timeseries/TransformationsFeatureSelection.py`

 * *Files identical despite different names*

### Comparing `EDAspy-1.0.2/EDAspy.egg-info/PKG-INFO` & `EDAspy-1.1.1/EDAspy.egg-info/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 Metadata-Version: 2.1
 Name: EDAspy
-Version: 1.0.2
+Version: 1.1.1
 Summary: EDAspy is a Python package that implements Estimation of Distribution Algorithms. EDAspy allows toeither use already existing implementations or customize the EDAs baseline easily building it bymodules so new research can be easily developed. It also has several benchmarks for comparisons.
 Home-page: https://github.com/VicentePerezSoloviev/EDAspy
 Author: Vicente P. Soloviev
 Author-email: vicente.perez.soloviev@gmail.com
 License: MIT
-Download-URL: https://github.com/VicentePerezSoloviev/EDAspy/archive/1.0.0.tar.gz
+Download-URL: https://github.com/VicentePerezSoloviev/EDAspy/archive/1.1.1.tar.gz
 Description: # <img src='https://raw.githubusercontent.com/VicentePerezSoloviev/EDAspy/master/Logo%20EDAspy.png' align="right" height="150"/>
         
         [![PyPI](https://img.shields.io/pypi/v/edaspy)](https://pypi.python.org/pypi/EDAspy/)
         [![PyPI license](https://img.shields.io/pypi/l/EDAspy.svg)](https://pypi.python.org/pypi/EDAspy/)
         [![Downloads](https://static.pepy.tech/personalized-badge/edaspy?period=total&units=none&left_color=grey&right_color=blue&left_text=downloads)](https://pepy.tech/project/edaspy)
         [![Documentation Status](https://readthedocs.org/projects/edaspy/badge/?version=latest)](https://edaspy.readthedocs.io/en/latest/?badge=latest)
         
         # EDAspy
         
         ## Introduction
         
-        EDAspy presents some implementations of the Estimation of Distribution Algorithms (EDAs). EDAs are a type of
+        EDAspy presents some implementations of the Estimation of Distribution Algorithms (EDAs) [1]. EDAs are a type of
         evolutionary algorithms. Depending on the type of the probabilistic model embedded in the EDA, and the type of
         variables considered, we will use a different EDA implementation.
         
         The pseudocode of EDAs is the following:
         
         1. Random initialization of the population.
         
@@ -38,28 +38,45 @@
         
         EDAspy allows to create a custom version of the EDA. Using the modular probabilistic models and the initializators, this can be embedded into the EDA baseline and used for different purposes. If this fits you, take a look on the examples section to the EDACustom example.
         
         EDAspy also incorporates a set of benchmarks in order to compare the algorithms trying to minimize these cost functions.
         
         The following implementations are available in EDAspy:
         
-        * UMDAd: Univariate Marginal Distribution Algorithm binary. It can be used as a simple example of EDA where the variables are binary and there are not dependencies between variables. Some usages include feature selection, for example.
+        * UMDAd: Univariate Marginal Distribution Algorithm binary [2]. It can be used as a simple example of EDA where the variables are binary and there are not dependencies between variables. Some usages include feature selection, for example.
         
         
-        * UMDAc: Univariate Marginal Distribution Algorithm continuous. In this EDA all the variables assume a Gaussian distribution and there are not dependencies considered between the variables. Some usages include hyperparameter optimization, for example.
+        * UMDAc: Univariate Marginal Distribution Algorithm continuous [3]. In this EDA all the variables assume a Gaussian distribution and there are not dependencies considered between the variables. Some usages include hyperparameter optimization, for example.
         
         
-        * EGNA: Estimation of Gaussian Distribution Algorithm. This is a complex implementation in which dependencies between the variables are considered during the optimization. In each iteration, a Gaussian Bayesian network is learned and sampled. The variables in the model are assumed to be Gaussian and also de dependencies between them. This implementation is focused in continuous optimization.
+        * UnivariateKEDA: Univariate Kernel Estimation of Distribution Algorithm [4]. Each variables distribution is estimated using Kernel Density Estimation. 
         
         
-        * EMNA: Estimation of Multivariate Normal Algorithm. This is a similar implementation to EGNA, in which instead of using a Gaussian Bayesian network, a multivariate Gaussian distribution is iteratively learned and sampled. As in EGNA, the dependencies between variables are considered and assumed to be linear Gaussian. This implementation is focused in continuous optimization.
+        * EGNA: Estimation of Gaussian Distribution Algorithm [5][6]. This is a complex implementation in which dependencies between the variables are considered during the optimization. In each iteration, a Gaussian Bayesian network is learned and sampled. The variables in the model are assumed to be Gaussian and also de dependencies between them. This implementation is focused in continuous optimization.
+        
+        
+        * EMNA: Estimation of Multivariate Normal Algorithm [1]. This is a similar implementation to EGNA, in which instead of using a Gaussian Bayesian network, a multivariate Gaussian distribution is iteratively learned and sampled. As in EGNA, the dependencies between variables are considered and assumed to be linear Gaussian. This implementation is focused in continuous optimization.
+        
+        
+        * SPEDA: Semiparametric Estimation of Distribution Algorithm [7]. This multivariate EDA allows estimating the density of a variable using either KDE or Gaussians, and allow dependencies between both types of variables. It is an archive-based approach where the probabilistic model is updated given the best individuals of l previous generations.
+        
+        
+        * MultivariateKEDA: Special case of SPEDA approach in which all nodes are restricted to be estimated using KDE (Gaussian nodes are forbidden) [7]. It is also an archive-based approach.
         
         
         * Categorical EDA. In this implementation we consider some independent categorical variables. Some usages include portfolio optimization, for exampled.
         
+        
+        Some tools are also available in EDAspy such as the Bayesian network structure plotting, for visualizing the graph learnt in some of the implementations, if needed.
+        
+        
+        Although some categorical EDAs are implemented, the package is focused in continuous optimization. Below, we show a CPU time analysis for the different approaches implemented for continuous optimization. Note that the CPU time can be reduced using parallelization (available as a parameter in the EDA initialization). Reference [7] shows a comparison about the performance of the algorithms in terms of cost function minimization. 
+        
+        <img src='cpu_comparison_continuous_opt.jpeg' alt="CPU time comparison for continuous optimization" title="CPU time comparison for continuous optimization"/>
+        
         ## Examples
         
         Some examples are available in https://github.com/VicentePerezSoloviev/EDAspy/tree/master/notebooks
         
         ## Getting started
         
         For installing EDAspy from Pypi execute the following command using pip:
@@ -68,15 +85,15 @@
             pip install EDAspy
         ```
         
         ## Build from Source
         
         ### Prerequisites
         
-        - Python 3.6, 3.7, 3.8 or 3.9.
+        - Python >= 3.0
         - Pybnesian, numpy, pandas.
         
         ### Building
         
         Clone the repository:
         
         ```bash
@@ -96,14 +113,31 @@
         
         Run the tests with:
         
         ```bash
           pytest
         ```
         
+        ## Bibliography
+        
+        [1] LarraÃ±aga, P., & Lozano, J. A. (Eds.). (2001). Estimation of distribution algorithms: A new tool for evolutionary computation (Vol. 2). Springer Science & Business Media.
+        
+        [2] MÃ¼hlenbein, H., & Paass, G. (1996). From recombination of genes to the estimation of distributions I. Binary parameters. In Parallel Problem Solving from Natureâ€”PPSN IV: International Conference on Evolutionary Computationâ€”The 4th International Conference on Parallel Problem Solving from Nature Berlin, Germany, September 22â€“26, 1996 Proceedings 4 (pp. 178-187). Springer Berlin Heidelberg.
+        
+        [3] MÃ¼hlenbein, H., Bendisch, J., & Voigt, H. M. (1996). From recombination of genes to the estimation of distributions II. Continuous parameters. In Parallel Problem Solving from Natureâ€”PPSN IV: International Conference on Evolutionary Computationâ€”The 4th International Conference on Parallel Problem Solving from Nature Berlin, Germany, September 22â€“26, 1996 Proceedings 4 (pp. 188-197). Springer Berlin Heidelberg.
+        
+        [4] Luo, N., & Qian, F. (2009, August). Evolutionary algorithm using kernel density estimation model in continuous domain. In 2009 7th Asian Control Conference (pp. 1526-1531). IEEE.
+        
+        [5] Larranaga, P. (2000). Optimization in continuous domains by learning and simulation of Gaussian networks. In Proc. of the 2000 Genetic and Evolutionary Computation Conference Workshop Program.
+        
+        [6] Soloviev, V. P., LarraÃ±aga, P., & Bielza, C. (2022). Estimation of distribution algorithms using Gaussian Bayesian networks to solve industrial optimization problems constrained by environment variables. Journal of Combinatorial Optimization, 44(2), 1077-1098.
+        
+        [7] Soloviev, Vicente P.& Bielza, Concha & LarraÃ±aga, Pedro (2023). Semiparametric Estimation of Distribution Algorithms for continuous optimization. IEEE Transactions on Evolutionary Computation.
+        
+        
 Keywords: EDA,estimation,bayesian,evolutionary,algorithm,optimization,time_series,feature,selection,semiparametric,Gaussian
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.0
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `EDAspy-1.0.2/EDAspy.egg-info/SOURCES.txt` & `EDAspy-1.1.1/EDAspy.egg-info/SOURCES.txt`

 * *Files 14% similar despite different names*

```diff
@@ -1,44 +1,59 @@
 LICENSE
 README.md
 setup.py
 EDAspy/__init__.py
 EDAspy.egg-info/PKG-INFO
 EDAspy.egg-info/SOURCES.txt
 EDAspy.egg-info/dependency_links.txt
-EDAspy.egg-info/requires.txt
 EDAspy.egg-info/top_level.txt
 EDAspy/benchmarks/__init__.py
 EDAspy/benchmarks/binary.py
 EDAspy/benchmarks/continuous.py
 EDAspy/optimization/__init__.py
 EDAspy/optimization/eda.py
 EDAspy/optimization/eda_result.py
+EDAspy/optimization/tools.py
+EDAspy/optimization/utils.py
 EDAspy/optimization/custom/__init__.py
 EDAspy/optimization/custom/eda_custom.py
 EDAspy/optimization/custom/initialization_models/__init__.py
 EDAspy/optimization/custom/initialization_models/_generation_init.py
-EDAspy/optimization/custom/initialization_models/multi_gauss_gininit.py
+EDAspy/optimization/custom/initialization_models/multi_gauss_geninit.py
 EDAspy/optimization/custom/initialization_models/uni_bin_geninit.py
 EDAspy/optimization/custom/initialization_models/uni_gauss_geninit.py
 EDAspy/optimization/custom/initialization_models/uniform_geninit.py
 EDAspy/optimization/custom/probabilistic_models/__init__.py
 EDAspy/optimization/custom/probabilistic_models/_probabilistic_model.py
 EDAspy/optimization/custom/probabilistic_models/gaussian_bayesian_network.py
+EDAspy/optimization/custom/probabilistic_models/kde_bayesian_network.py
 EDAspy/optimization/custom/probabilistic_models/multivariate_gaussian.py
+EDAspy/optimization/custom/probabilistic_models/semiparametric_bayesian_network.py
 EDAspy/optimization/custom/probabilistic_models/univariate_binary.py
 EDAspy/optimization/custom/probabilistic_models/univariate_gaussian.py
+EDAspy/optimization/custom/probabilistic_models/univariate_kde.py
 EDAspy/optimization/multivariate/__init__.py
 EDAspy/optimization/multivariate/egna.py
 EDAspy/optimization/multivariate/emna.py
+EDAspy/optimization/multivariate/keda.py
+EDAspy/optimization/multivariate/speda.py
 EDAspy/optimization/univariate/__init__.py
+EDAspy/optimization/univariate/keda.py
 EDAspy/optimization/univariate/umda_binary.py
 EDAspy/optimization/univariate/umda_continuous.py
 EDAspy/timeseries/TS_transformations.py
 EDAspy/timeseries/TransformationsFeatureSelection.py
 EDAspy/timeseries/__init__.py
 tests/__init__.py
 tests/test_egna.py
 tests/test_emna.py
+tests/test_gbn.py
 tests/test_geninit.py
+tests/test_kdebn.py
+tests/test_keda.py
+tests/test_multivariate_keda.py
+tests/test_pm.py
+tests/test_spbn.py
+tests/test_speda.py
 tests/test_umdac.py
-tests/test_umdad.py
+tests/test_umdad.py
+tests/test_univariate_keda.py
```

### Comparing `EDAspy-1.0.2/LICENSE` & `EDAspy-1.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `EDAspy-1.0.2/PKG-INFO` & `EDAspy-1.1.1/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 Metadata-Version: 2.1
 Name: EDAspy
-Version: 1.0.2
+Version: 1.1.1
 Summary: EDAspy is a Python package that implements Estimation of Distribution Algorithms. EDAspy allows toeither use already existing implementations or customize the EDAs baseline easily building it bymodules so new research can be easily developed. It also has several benchmarks for comparisons.
 Home-page: https://github.com/VicentePerezSoloviev/EDAspy
 Author: Vicente P. Soloviev
 Author-email: vicente.perez.soloviev@gmail.com
 License: MIT
-Download-URL: https://github.com/VicentePerezSoloviev/EDAspy/archive/1.0.0.tar.gz
+Download-URL: https://github.com/VicentePerezSoloviev/EDAspy/archive/1.1.1.tar.gz
 Description: # <img src='https://raw.githubusercontent.com/VicentePerezSoloviev/EDAspy/master/Logo%20EDAspy.png' align="right" height="150"/>
         
         [![PyPI](https://img.shields.io/pypi/v/edaspy)](https://pypi.python.org/pypi/EDAspy/)
         [![PyPI license](https://img.shields.io/pypi/l/EDAspy.svg)](https://pypi.python.org/pypi/EDAspy/)
         [![Downloads](https://static.pepy.tech/personalized-badge/edaspy?period=total&units=none&left_color=grey&right_color=blue&left_text=downloads)](https://pepy.tech/project/edaspy)
         [![Documentation Status](https://readthedocs.org/projects/edaspy/badge/?version=latest)](https://edaspy.readthedocs.io/en/latest/?badge=latest)
         
         # EDAspy
         
         ## Introduction
         
-        EDAspy presents some implementations of the Estimation of Distribution Algorithms (EDAs). EDAs are a type of
+        EDAspy presents some implementations of the Estimation of Distribution Algorithms (EDAs) [1]. EDAs are a type of
         evolutionary algorithms. Depending on the type of the probabilistic model embedded in the EDA, and the type of
         variables considered, we will use a different EDA implementation.
         
         The pseudocode of EDAs is the following:
         
         1. Random initialization of the population.
         
@@ -38,28 +38,45 @@
         
         EDAspy allows to create a custom version of the EDA. Using the modular probabilistic models and the initializators, this can be embedded into the EDA baseline and used for different purposes. If this fits you, take a look on the examples section to the EDACustom example.
         
         EDAspy also incorporates a set of benchmarks in order to compare the algorithms trying to minimize these cost functions.
         
         The following implementations are available in EDAspy:
         
-        * UMDAd: Univariate Marginal Distribution Algorithm binary. It can be used as a simple example of EDA where the variables are binary and there are not dependencies between variables. Some usages include feature selection, for example.
+        * UMDAd: Univariate Marginal Distribution Algorithm binary [2]. It can be used as a simple example of EDA where the variables are binary and there are not dependencies between variables. Some usages include feature selection, for example.
         
         
-        * UMDAc: Univariate Marginal Distribution Algorithm continuous. In this EDA all the variables assume a Gaussian distribution and there are not dependencies considered between the variables. Some usages include hyperparameter optimization, for example.
+        * UMDAc: Univariate Marginal Distribution Algorithm continuous [3]. In this EDA all the variables assume a Gaussian distribution and there are not dependencies considered between the variables. Some usages include hyperparameter optimization, for example.
         
         
-        * EGNA: Estimation of Gaussian Distribution Algorithm. This is a complex implementation in which dependencies between the variables are considered during the optimization. In each iteration, a Gaussian Bayesian network is learned and sampled. The variables in the model are assumed to be Gaussian and also de dependencies between them. This implementation is focused in continuous optimization.
+        * UnivariateKEDA: Univariate Kernel Estimation of Distribution Algorithm [4]. Each variables distribution is estimated using Kernel Density Estimation. 
         
         
-        * EMNA: Estimation of Multivariate Normal Algorithm. This is a similar implementation to EGNA, in which instead of using a Gaussian Bayesian network, a multivariate Gaussian distribution is iteratively learned and sampled. As in EGNA, the dependencies between variables are considered and assumed to be linear Gaussian. This implementation is focused in continuous optimization.
+        * EGNA: Estimation of Gaussian Distribution Algorithm [5][6]. This is a complex implementation in which dependencies between the variables are considered during the optimization. In each iteration, a Gaussian Bayesian network is learned and sampled. The variables in the model are assumed to be Gaussian and also de dependencies between them. This implementation is focused in continuous optimization.
+        
+        
+        * EMNA: Estimation of Multivariate Normal Algorithm [1]. This is a similar implementation to EGNA, in which instead of using a Gaussian Bayesian network, a multivariate Gaussian distribution is iteratively learned and sampled. As in EGNA, the dependencies between variables are considered and assumed to be linear Gaussian. This implementation is focused in continuous optimization.
+        
+        
+        * SPEDA: Semiparametric Estimation of Distribution Algorithm [7]. This multivariate EDA allows estimating the density of a variable using either KDE or Gaussians, and allow dependencies between both types of variables. It is an archive-based approach where the probabilistic model is updated given the best individuals of l previous generations.
+        
+        
+        * MultivariateKEDA: Special case of SPEDA approach in which all nodes are restricted to be estimated using KDE (Gaussian nodes are forbidden) [7]. It is also an archive-based approach.
         
         
         * Categorical EDA. In this implementation we consider some independent categorical variables. Some usages include portfolio optimization, for exampled.
         
+        
+        Some tools are also available in EDAspy such as the Bayesian network structure plotting, for visualizing the graph learnt in some of the implementations, if needed.
+        
+        
+        Although some categorical EDAs are implemented, the package is focused in continuous optimization. Below, we show a CPU time analysis for the different approaches implemented for continuous optimization. Note that the CPU time can be reduced using parallelization (available as a parameter in the EDA initialization). Reference [7] shows a comparison about the performance of the algorithms in terms of cost function minimization. 
+        
+        <img src='cpu_comparison_continuous_opt.jpeg' alt="CPU time comparison for continuous optimization" title="CPU time comparison for continuous optimization"/>
+        
         ## Examples
         
         Some examples are available in https://github.com/VicentePerezSoloviev/EDAspy/tree/master/notebooks
         
         ## Getting started
         
         For installing EDAspy from Pypi execute the following command using pip:
@@ -68,15 +85,15 @@
             pip install EDAspy
         ```
         
         ## Build from Source
         
         ### Prerequisites
         
-        - Python 3.6, 3.7, 3.8 or 3.9.
+        - Python >= 3.0
         - Pybnesian, numpy, pandas.
         
         ### Building
         
         Clone the repository:
         
         ```bash
@@ -96,14 +113,31 @@
         
         Run the tests with:
         
         ```bash
           pytest
         ```
         
+        ## Bibliography
+        
+        [1] LarraÃ±aga, P., & Lozano, J. A. (Eds.). (2001). Estimation of distribution algorithms: A new tool for evolutionary computation (Vol. 2). Springer Science & Business Media.
+        
+        [2] MÃ¼hlenbein, H., & Paass, G. (1996). From recombination of genes to the estimation of distributions I. Binary parameters. In Parallel Problem Solving from Natureâ€”PPSN IV: International Conference on Evolutionary Computationâ€”The 4th International Conference on Parallel Problem Solving from Nature Berlin, Germany, September 22â€“26, 1996 Proceedings 4 (pp. 178-187). Springer Berlin Heidelberg.
+        
+        [3] MÃ¼hlenbein, H., Bendisch, J., & Voigt, H. M. (1996). From recombination of genes to the estimation of distributions II. Continuous parameters. In Parallel Problem Solving from Natureâ€”PPSN IV: International Conference on Evolutionary Computationâ€”The 4th International Conference on Parallel Problem Solving from Nature Berlin, Germany, September 22â€“26, 1996 Proceedings 4 (pp. 188-197). Springer Berlin Heidelberg.
+        
+        [4] Luo, N., & Qian, F. (2009, August). Evolutionary algorithm using kernel density estimation model in continuous domain. In 2009 7th Asian Control Conference (pp. 1526-1531). IEEE.
+        
+        [5] Larranaga, P. (2000). Optimization in continuous domains by learning and simulation of Gaussian networks. In Proc. of the 2000 Genetic and Evolutionary Computation Conference Workshop Program.
+        
+        [6] Soloviev, V. P., LarraÃ±aga, P., & Bielza, C. (2022). Estimation of distribution algorithms using Gaussian Bayesian networks to solve industrial optimization problems constrained by environment variables. Journal of Combinatorial Optimization, 44(2), 1077-1098.
+        
+        [7] Soloviev, Vicente P.& Bielza, Concha & LarraÃ±aga, Pedro (2023). Semiparametric Estimation of Distribution Algorithms for continuous optimization. IEEE Transactions on Evolutionary Computation.
+        
+        
 Keywords: EDA,estimation,bayesian,evolutionary,algorithm,optimization,time_series,feature,selection,semiparametric,Gaussian
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.0
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `EDAspy-1.0.2/setup.py` & `EDAspy-1.1.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,32 +1,33 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
-__version__ = '1.0.2'  # also defined in EDAspy/__init__.py
+__version__ = '1.1.1'  # also defined in EDAspy/__init__.py
 
 setuptools.setup(
     name="EDAspy",
     version=__version__,
     author="Vicente P. Soloviev",
     author_email="vicente.perez.soloviev@gmail.com",
     description="EDAspy is a Python package that implements Estimation of Distribution Algorithms. EDAspy allows to"
                 "either use already existing implementations or customize the EDAs baseline easily building it by"
                 "modules so new research can be easily developed. It also has several benchmarks for comparisons.",
     long_description=long_description,
     long_description_content_type="text/markdown",
-    download_url="https://github.com/VicentePerezSoloviev/EDAspy/archive/1.0.0.tar.gz",
+    download_url="https://github.com/VicentePerezSoloviev/EDAspy/archive/1.1.1.tar.gz",
     url="https://github.com/VicentePerezSoloviev/EDAspy",
     packages=setuptools.find_packages(),
     classifiers=[
         'Development Status :: 5 - Production/Stable',
         "Programming Language :: Python :: 3",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent",
     ],
     keywords=['EDA', 'estimation', 'bayesian', 'evolutionary', 'algorithm', 'optimization', 'time_series', 'feature',
               'selection', 'semiparametric', 'Gaussian'],
     python_requires='>=3.0',
     license="MIT",
-    install_requires=["pandas>=1.2.0", "numpy>1.15.0", "pybnesian>=0.3.4"]
+    include_package_data=True,
+    package_data={'': ['benchmarks/input_data/*.txt']}
 )
```

### Comparing `EDAspy-1.0.2/tests/test_geninit.py` & `EDAspy-1.1.1/tests/test_geninit.py`

 * *Files identical despite different names*

