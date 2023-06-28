# Comparing `tmp/pollination-three-phase-0.2.8.tar.gz` & `tmp/pollination-three-phase-0.2.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/pollination-three-phase-0.2.8.tar", last modified: Tue Dec  6 12:51:07 2022, max compression
+gzip compressed data, was "dist/pollination-three-phase-0.2.9.tar", last modified: Thu Dec  8 13:39:27 2022, max compression
```

## Comparing `pollination-three-phase-0.2.8.tar` & `pollination-three-phase-0.2.9.tar`

### file list

```diff
@@ -1,45 +1,45 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/.github/
--rw-r--r--   0 runner    (1001) docker     (123)      332 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)     3369 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/.github/workflows/ci.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      530 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/.github/workflows/tests.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      174 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      294 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/.releaserc.json
--rw-r--r--   0 runner    (1001) docker     (123)     5748 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      831 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)       69 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      165 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/deploy.sh
--rw-r--r--   0 runner    (1001) docker     (123)       60 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/dev-requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination/three_phase/
--rw-r--r--   0 runner    (1001) docker     (123)       96 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11423 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/entry.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination/three_phase/three_phase/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/three_phase/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1707 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/three_phase/_daylight_matrix.py
--rw-r--r--   0 runner    (1001) docker     (123)     1944 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/three_phase/_multiply_matrix.py
--rw-r--r--   0 runner    (1001) docker     (123)     1957 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/three_phase/_view_matrix.py
--rw-r--r--   0 runner    (1001) docker     (123)     4507 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/three_phase/calculation.py
--rw-r--r--   0 runner    (1001) docker     (123)     3768 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/three_phase/preparation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination/three_phase/two_phase/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination/three_phase/two_phase/dynamic/
--rw-r--r--   0 runner    (1001) docker     (123)     5014 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/two_phase/dynamic/_raytracing.py
--rw-r--r--   0 runner    (1001) docker     (123)     5324 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/pollination/three_phase/two_phase/dynamic/entry.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination_three_phase.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      831 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination_three_phase.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1103 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination_three_phase.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination_three_phase.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2022-12-06 12:50:29.000000 pollination-three-phase-0.2.8/pollination_three_phase.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)      113 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination_three_phase.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/pollination_three_phase.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      113 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      102 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2031 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-06 12:51:07.000000 pollination-three-phase-0.2.8/tests/project_folder/
--rw-r--r--   0 runner    (1001) docker     (123)       58 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/tests/project_folder/inputs.json
--rw-r--r--   0 runner    (1001) docker     (123)   701310 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/tests/project_folder/model.hbjson
--rw-r--r--   0 runner    (1001) docker     (123)   149431 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/tests/project_folder/weather.wea
--rw-r--r--   0 runner    (1001) docker     (123)      244 2022-12-06 12:50:09.000000 pollination-three-phase-0.2.8/tests/validation_test.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      332 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)     3369 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/.github/workflows/ci.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      530 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/.github/workflows/tests.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      174 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      294 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/.releaserc.json
+-rw-r--r--   0 runner    (1001) docker     (123)     5748 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      831 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/deploy.sh
+-rw-r--r--   0 runner    (1001) docker     (123)       60 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/dev-requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination/three_phase/
+-rw-r--r--   0 runner    (1001) docker     (123)       96 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11423 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/entry.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination/three_phase/three_phase/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/three_phase/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1707 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/three_phase/_daylight_matrix.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1952 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/three_phase/_multiply_matrix.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1957 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/three_phase/_view_matrix.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4507 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/three_phase/calculation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3768 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/three_phase/preparation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination/three_phase/two_phase/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination/three_phase/two_phase/dynamic/
+-rw-r--r--   0 runner    (1001) docker     (123)     5014 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/two_phase/dynamic/_raytracing.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5324 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/pollination/three_phase/two_phase/dynamic/entry.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination_three_phase.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      831 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination_three_phase.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1103 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination_three_phase.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination_three_phase.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2022-12-08 13:38:46.000000 pollination-three-phase-0.2.9/pollination_three_phase.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)      113 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination_three_phase.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/pollination_three_phase.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      113 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2031 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2022-12-08 13:39:27.000000 pollination-three-phase-0.2.9/tests/project_folder/
+-rw-r--r--   0 runner    (1001) docker     (123)       58 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/tests/project_folder/inputs.json
+-rw-r--r--   0 runner    (1001) docker     (123)   701310 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/tests/project_folder/model.hbjson
+-rw-r--r--   0 runner    (1001) docker     (123)   149431 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/tests/project_folder/weather.wea
+-rw-r--r--   0 runner    (1001) docker     (123)      244 2022-12-08 13:38:23.000000 pollination-three-phase-0.2.9/tests/validation_test.py
```

### Comparing `pollination-three-phase-0.2.8/.github/workflows/ci.yaml` & `pollination-three-phase-0.2.9/.github/workflows/ci.yaml`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/.github/workflows/tests.yaml` & `pollination-three-phase-0.2.9/.github/workflows/tests.yaml`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/LICENSE` & `pollination-three-phase-0.2.9/LICENSE`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/PKG-INFO` & `pollination-three-phase-0.2.9/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pollination-three-phase
-Version: 0.2.8
+Version: 0.2.9
 Summary: Three phase recipe for Pollination.
 Home-page: https://github.com/pollination/three-phase
 Author: ladybug-tools
 Author-email: info@ladybug.tools
 Maintainer: ladybug-tools
 Maintainer-email: info@ladybug.tools
 License: PolyForm Shield License 1.0.0, https://polyformproject.org/wp-content/uploads/2020/06/PolyForm-Shield-1.0.0.txt
```

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/entry.py` & `pollination-three-phase-0.2.9/pollination/three_phase/entry.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/three_phase/_daylight_matrix.py` & `pollination-three-phase-0.2.9/pollination/three_phase/three_phase/_daylight_matrix.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/three_phase/_multiply_matrix.py` & `pollination-three-phase-0.2.9/pollination/three_phase/three_phase/_multiply_matrix.py`

 * *Files 8% similar despite different names*

```diff
@@ -41,15 +41,15 @@
 
     @task(template=MatrixMultiplicationThreePhase)
     def multiply_threephase_matrix(
         self, identifier=identifier, sky_vector=sky_vector,
         view_matrix=view_matrix, t_matrix=t_matrix,
         daylight_matrix=daylight_matrix,
         output_format='f',
-        conversion='raw',
+        conversion='illuminance',
         header='keep'
     ):
         return [
             {
                 'from': MatrixMultiplicationThreePhase()._outputs.output_matrix,
                 'to': 'temp/{{identifier}}.ill'
             }
```

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/three_phase/_view_matrix.py` & `pollination-three-phase-0.2.9/pollination/three_phase/three_phase/_view_matrix.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/three_phase/calculation.py` & `pollination-three-phase-0.2.9/pollination/three_phase/three_phase/calculation.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/three_phase/preparation.py` & `pollination-three-phase-0.2.9/pollination/three_phase/three_phase/preparation.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/two_phase/dynamic/_raytracing.py` & `pollination-three-phase-0.2.9/pollination/three_phase/two_phase/dynamic/_raytracing.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/pollination/three_phase/two_phase/dynamic/entry.py` & `pollination-three-phase-0.2.9/pollination/three_phase/two_phase/dynamic/entry.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/pollination_three_phase.egg-info/PKG-INFO` & `pollination-three-phase-0.2.9/pollination_three_phase.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pollination-three-phase
-Version: 0.2.8
+Version: 0.2.9
 Summary: Three phase recipe for Pollination.
 Home-page: https://github.com/pollination/three-phase
 Author: ladybug-tools
 Author-email: info@ladybug.tools
 Maintainer: ladybug-tools
 Maintainer-email: info@ladybug.tools
 License: PolyForm Shield License 1.0.0, https://polyformproject.org/wp-content/uploads/2020/06/PolyForm-Shield-1.0.0.txt
```

### Comparing `pollination-three-phase-0.2.8/pollination_three_phase.egg-info/SOURCES.txt` & `pollination-three-phase-0.2.9/pollination_three_phase.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/setup.py` & `pollination-three-phase-0.2.9/setup.py`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/tests/project_folder/model.hbjson` & `pollination-three-phase-0.2.9/tests/project_folder/model.hbjson`

 * *Files identical despite different names*

### Comparing `pollination-three-phase-0.2.8/tests/project_folder/weather.wea` & `pollination-three-phase-0.2.9/tests/project_folder/weather.wea`

 * *Files identical despite different names*

