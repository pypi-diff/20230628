# Comparing `tmp/frccontrol-2023.29.tar.gz` & `tmp/frccontrol-2023.30.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "frccontrol-2023.29.tar", last modified: Mon Apr 24 20:43:42 2023, max compression
+gzip compressed data, was "frccontrol-2023.30.tar", last modified: Tue Jun 27 22:13:20 2023, max compression
```

## Comparing `frccontrol-2023.29.tar` & `frccontrol-2023.30.tar`

### file list

```diff
@@ -1,31 +1,39 @@
-drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-04-24 20:43:42.328099 frccontrol-2023.29/
--rw-r--r--   0 tav       (1000) users      (100)     1457 2018-07-14 03:19:56.000000 frccontrol-2023.29/LICENSE
--rw-r--r--   0 tav       (1000) users      (100)     1115 2023-04-24 20:43:42.328099 frccontrol-2023.29/PKG-INFO
--rw-r--r--   0 tav       (1000) users      (100)      383 2022-11-10 21:45:34.000000 frccontrol-2023.29/README.rst
-drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-04-24 20:43:42.328099 frccontrol-2023.29/frccontrol/
--rw-r--r--   0 tav       (1000) users      (100)      427 2023-04-24 20:42:51.000000 frccontrol-2023.29/frccontrol/__init__.py
--rw-r--r--   0 tav       (1000) users      (100)     1865 2023-03-17 22:26:57.000000 frccontrol-2023.29/frccontrol/ctrlutil.py
--rw-r--r--   0 tav       (1000) users      (100)     2240 2023-03-19 21:39:39.000000 frccontrol-2023.29/frccontrol/discretization.py
--rw-r--r--   0 tav       (1000) users      (100)     4252 2023-03-26 17:19:21.000000 frccontrol-2023.29/frccontrol/extended_kalman_filter.py
--rw-r--r--   0 tav       (1000) users      (100)     2587 2023-03-17 22:26:57.000000 frccontrol-2023.29/frccontrol/kalman_filter.py
--rw-r--r--   0 tav       (1000) users      (100)     1484 2023-03-17 22:26:57.000000 frccontrol-2023.29/frccontrol/linear_plant_inversion_feedforward.py
--rw-r--r--   0 tav       (1000) users      (100)     2797 2023-03-17 22:26:57.000000 frccontrol-2023.29/frccontrol/linear_quadratic_regulator.py
--rw-r--r--   0 tav       (1000) users      (100)     6150 2023-03-26 01:10:05.000000 frccontrol-2023.29/frccontrol/models.py
--rw-r--r--   0 tav       (1000) users      (100)     3980 2023-03-26 22:28:18.000000 frccontrol-2023.29/frccontrol/numerical_integration.py
--rw-r--r--   0 tav       (1000) users      (100)     1518 2023-03-15 05:59:43.000000 frccontrol-2023.29/frccontrol/numerical_jacobian.py
--rw-r--r--   0 tav       (1000) users      (100)     3193 2023-03-28 17:13:23.000000 frccontrol-2023.29/frccontrol/plotutil.py
--rw-r--r--   0 tav       (1000) users      (100)     4462 2023-03-15 06:00:03.000000 frccontrol-2023.29/frccontrol/profiles.py
-drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-04-24 20:43:42.328099 frccontrol-2023.29/frccontrol/test/
--rw-r--r--   0 tav       (1000) users      (100)        0 2022-10-01 04:59:40.000000 frccontrol-2023.29/frccontrol/test/__init__.py
--rw-r--r--   0 tav       (1000) users      (100)      654 2022-10-01 05:01:04.000000 frccontrol-2023.29/frccontrol/test/test_numerical_jacobian.py
--rw-r--r--   0 tav       (1000) users      (100)     8039 2023-04-24 20:42:51.000000 frccontrol-2023.29/frccontrol/trajectory.py
--rw-r--r--   0 tav       (1000) users      (100)       51 2023-04-24 20:43:42.000000 frccontrol-2023.29/frccontrol/version.py
-drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-04-24 20:43:42.328099 frccontrol-2023.29/frccontrol.egg-info/
--rw-r--r--   0 tav       (1000) users      (100)     1115 2023-04-24 20:43:42.000000 frccontrol-2023.29/frccontrol.egg-info/PKG-INFO
--rw-r--r--   0 tav       (1000) users      (100)      719 2023-04-24 20:43:42.000000 frccontrol-2023.29/frccontrol.egg-info/SOURCES.txt
--rw-r--r--   0 tav       (1000) users      (100)        1 2023-04-24 20:43:42.000000 frccontrol-2023.29/frccontrol.egg-info/dependency_links.txt
--rw-r--r--   0 tav       (1000) users      (100)       23 2023-04-24 20:43:42.000000 frccontrol-2023.29/frccontrol.egg-info/requires.txt
--rw-r--r--   0 tav       (1000) users      (100)       11 2023-04-24 20:43:42.000000 frccontrol-2023.29/frccontrol.egg-info/top_level.txt
--rw-r--r--   0 tav       (1000) users      (100)        1 2018-07-14 02:44:51.000000 frccontrol-2023.29/frccontrol.egg-info/zip-safe
--rw-r--r--   0 tav       (1000) users      (100)       63 2023-04-24 20:43:42.328099 frccontrol-2023.29/setup.cfg
--rw-r--r--   0 tav       (1000) users      (100)     2692 2022-10-01 06:42:46.000000 frccontrol-2023.29/setup.py
+drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-06-27 22:13:20.724995 frccontrol-2023.30/
+-rw-r--r--   0 tav       (1000) users      (100)       66 2023-06-27 21:44:56.000000 frccontrol-2023.30/.gitignore
+-rw-r--r--   0 tav       (1000) users      (100)    21157 2023-03-18 04:18:42.000000 frccontrol-2023.30/.pylintrc
+-rw-r--r--   0 tav       (1000) users      (100)     1457 2023-06-27 21:44:56.000000 frccontrol-2023.30/LICENSE.txt
+-rw-r--r--   0 tav       (1000) users      (100)     1097 2023-06-27 22:13:20.724995 frccontrol-2023.30/PKG-INFO
+-rw-r--r--   0 tav       (1000) users      (100)      383 2022-11-10 21:45:34.000000 frccontrol-2023.30/README.rst
+drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-06-27 22:13:20.721661 frccontrol-2023.30/examples/
+-rwxr-xr-x   0 tav       (1000) users      (100)     3875 2023-03-28 17:13:57.000000 frccontrol-2023.30/examples/differential_drive.py
+-rwxr-xr-x   0 tav       (1000) users      (100)    10415 2023-04-24 20:42:51.000000 frccontrol-2023.30/examples/double_jointed_arm.py
+-rwxr-xr-x   0 tav       (1000) users      (100)     2979 2023-03-28 17:14:28.000000 frccontrol-2023.30/examples/elevator.py
+-rwxr-xr-x   0 tav       (1000) users      (100)     2905 2023-03-28 17:14:37.000000 frccontrol-2023.30/examples/flywheel.py
+-rwxr-xr-x   0 tav       (1000) users      (100)     2989 2023-03-28 17:14:47.000000 frccontrol-2023.30/examples/single_jointed_arm.py
+drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-06-27 22:13:20.724995 frccontrol-2023.30/frccontrol/
+-rw-r--r--   0 tav       (1000) users      (100)      427 2023-04-24 20:42:51.000000 frccontrol-2023.30/frccontrol/__init__.py
+-rw-r--r--   0 tav       (1000) users      (100)     1865 2023-03-17 22:26:57.000000 frccontrol-2023.30/frccontrol/ctrlutil.py
+-rw-r--r--   0 tav       (1000) users      (100)     2240 2023-03-19 21:39:39.000000 frccontrol-2023.30/frccontrol/discretization.py
+-rw-r--r--   0 tav       (1000) users      (100)     4252 2023-03-26 17:19:21.000000 frccontrol-2023.30/frccontrol/extended_kalman_filter.py
+-rw-r--r--   0 tav       (1000) users      (100)     2587 2023-03-17 22:26:57.000000 frccontrol-2023.30/frccontrol/kalman_filter.py
+-rw-r--r--   0 tav       (1000) users      (100)     1484 2023-03-17 22:26:57.000000 frccontrol-2023.30/frccontrol/linear_plant_inversion_feedforward.py
+-rw-r--r--   0 tav       (1000) users      (100)     2797 2023-03-17 22:26:57.000000 frccontrol-2023.30/frccontrol/linear_quadratic_regulator.py
+-rw-r--r--   0 tav       (1000) users      (100)     6150 2023-03-26 01:10:05.000000 frccontrol-2023.30/frccontrol/models.py
+-rw-r--r--   0 tav       (1000) users      (100)     3980 2023-03-26 22:28:18.000000 frccontrol-2023.30/frccontrol/numerical_integration.py
+-rw-r--r--   0 tav       (1000) users      (100)     1518 2023-03-15 05:59:43.000000 frccontrol-2023.30/frccontrol/numerical_jacobian.py
+-rw-r--r--   0 tav       (1000) users      (100)     3193 2023-03-28 17:13:23.000000 frccontrol-2023.30/frccontrol/plotutil.py
+-rw-r--r--   0 tav       (1000) users      (100)     4462 2023-03-15 06:00:03.000000 frccontrol-2023.30/frccontrol/profiles.py
+drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-06-27 22:13:20.724995 frccontrol-2023.30/frccontrol/test/
+-rw-r--r--   0 tav       (1000) users      (100)        0 2022-10-01 04:59:40.000000 frccontrol-2023.30/frccontrol/test/__init__.py
+-rw-r--r--   0 tav       (1000) users      (100)      654 2022-10-01 05:01:04.000000 frccontrol-2023.30/frccontrol/test/test_numerical_jacobian.py
+-rw-r--r--   0 tav       (1000) users      (100)     8039 2023-04-24 20:42:51.000000 frccontrol-2023.30/frccontrol/trajectory.py
+-rw-r--r--   0 tav       (1000) users      (100)      795 2023-06-27 21:44:56.000000 frccontrol-2023.30/frccontrol/version.py
+drwxr-xr-x   0 tav       (1000) users      (100)        0 2023-06-27 22:13:20.724995 frccontrol-2023.30/frccontrol.egg-info/
+-rw-r--r--   0 tav       (1000) users      (100)     1097 2023-06-27 22:13:20.000000 frccontrol-2023.30/frccontrol.egg-info/PKG-INFO
+-rw-r--r--   0 tav       (1000) users      (100)      868 2023-06-27 22:13:20.000000 frccontrol-2023.30/frccontrol.egg-info/SOURCES.txt
+-rw-r--r--   0 tav       (1000) users      (100)        1 2023-06-27 22:13:20.000000 frccontrol-2023.30/frccontrol.egg-info/dependency_links.txt
+-rw-r--r--   0 tav       (1000) users      (100)       23 2023-06-27 22:13:20.000000 frccontrol-2023.30/frccontrol.egg-info/requires.txt
+-rw-r--r--   0 tav       (1000) users      (100)       11 2023-06-27 22:13:20.000000 frccontrol-2023.30/frccontrol.egg-info/top_level.txt
+-rwxr-xr-x   0 tav       (1000) users      (100)      636 2023-06-27 22:12:58.000000 frccontrol-2023.30/publish-frccontrol.sh
+-rw-r--r--   0 tav       (1000) users      (100)     1100 2023-06-27 22:03:49.000000 frccontrol-2023.30/pyproject.toml
+-rw-r--r--   0 tav       (1000) users      (100)       38 2023-06-27 22:13:20.724995 frccontrol-2023.30/setup.cfg
```

### Comparing `frccontrol-2023.29/LICENSE` & `frccontrol-2023.30/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/ctrlutil.py` & `frccontrol-2023.30/frccontrol/ctrlutil.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/discretization.py` & `frccontrol-2023.30/frccontrol/discretization.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/extended_kalman_filter.py` & `frccontrol-2023.30/frccontrol/extended_kalman_filter.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/kalman_filter.py` & `frccontrol-2023.30/frccontrol/kalman_filter.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/linear_plant_inversion_feedforward.py` & `frccontrol-2023.30/frccontrol/linear_plant_inversion_feedforward.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/linear_quadratic_regulator.py` & `frccontrol-2023.30/frccontrol/linear_quadratic_regulator.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/models.py` & `frccontrol-2023.30/frccontrol/models.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/numerical_integration.py` & `frccontrol-2023.30/frccontrol/numerical_integration.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/numerical_jacobian.py` & `frccontrol-2023.30/frccontrol/numerical_jacobian.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/plotutil.py` & `frccontrol-2023.30/frccontrol/plotutil.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/profiles.py` & `frccontrol-2023.30/frccontrol/profiles.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/test/test_numerical_jacobian.py` & `frccontrol-2023.30/frccontrol/test/test_numerical_jacobian.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol/trajectory.py` & `frccontrol-2023.30/frccontrol/trajectory.py`

 * *Files identical despite different names*

### Comparing `frccontrol-2023.29/frccontrol.egg-info/SOURCES.txt` & `frccontrol-2023.30/frccontrol.egg-info/SOURCES.txt`

 * *Files 23% similar despite different names*

```diff
@@ -1,11 +1,18 @@
-LICENSE
+.gitignore
+.pylintrc
+LICENSE.txt
 README.rst
-setup.cfg
-setup.py
+publish-frccontrol.sh
+pyproject.toml
+examples/differential_drive.py
+examples/double_jointed_arm.py
+examples/elevator.py
+examples/flywheel.py
+examples/single_jointed_arm.py
 frccontrol/__init__.py
 frccontrol/ctrlutil.py
 frccontrol/discretization.py
 frccontrol/extended_kalman_filter.py
 frccontrol/kalman_filter.py
 frccontrol/linear_plant_inversion_feedforward.py
 frccontrol/linear_quadratic_regulator.py
@@ -17,10 +24,9 @@
 frccontrol/trajectory.py
 frccontrol/version.py
 frccontrol.egg-info/PKG-INFO
 frccontrol.egg-info/SOURCES.txt
 frccontrol.egg-info/dependency_links.txt
 frccontrol.egg-info/requires.txt
 frccontrol.egg-info/top_level.txt
-frccontrol.egg-info/zip-safe
 frccontrol/test/__init__.py
 frccontrol/test/test_numerical_jacobian.py
```

