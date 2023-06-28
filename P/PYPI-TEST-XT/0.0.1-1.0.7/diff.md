# Comparing `tmp/PYPI_TEST_XT-0.0.1.tar.gz` & `tmp/PYPI_TEST_XT-1.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PYPI_TEST_XT-0.0.1.tar", last modified: Mon Jun 26 14:00:21 2023, max compression
+gzip compressed data, was "PYPI_TEST_XT-1.0.7.tar", last modified: Wed Jun 28 13:51:42 2023, max compression
```

## Comparing `PYPI_TEST_XT-0.0.1.tar` & `PYPI_TEST_XT-1.0.7.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:00:21.942505 PYPI_TEST_XT-0.0.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-06-26 14:00:08.000000 PYPI_TEST_XT-0.0.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-26 14:00:21.938505 PYPI_TEST_XT-0.0.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-26 14:00:08.000000 PYPI_TEST_XT-0.0.1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      444 2023-06-26 14:00:08.000000 PYPI_TEST_XT-0.0.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 14:00:21.942505 PYPI_TEST_XT-0.0.1/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:00:21.934505 PYPI_TEST_XT-0.0.1/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:00:21.938505 PYPI_TEST_XT-0.0.1/src/PYPI_TEST_XT.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-26 14:00:21.000000 PYPI_TEST_XT-0.0.1/src/PYPI_TEST_XT.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-26 14:00:21.000000 PYPI_TEST_XT-0.0.1/src/PYPI_TEST_XT.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 14:00:21.000000 PYPI_TEST_XT-0.0.1/src/PYPI_TEST_XT.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-26 14:00:21.000000 PYPI_TEST_XT-0.0.1/src/PYPI_TEST_XT.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 14:00:21.938505 PYPI_TEST_XT-0.0.1/src/PyPI_test_XT/
--rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-26 14:00:08.000000 PYPI_TEST_XT-0.0.1/src/PyPI_test_XT/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1917 2023-06-26 14:00:08.000000 PYPI_TEST_XT-0.0.1/src/PyPI_test_XT/example.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:51:42.965266 PYPI_TEST_XT-1.0.7/
+-rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-06-28 13:51:31.000000 PYPI_TEST_XT-1.0.7/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      411 2023-06-28 13:51:42.965266 PYPI_TEST_XT-1.0.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 13:51:31.000000 PYPI_TEST_XT-1.0.7/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      444 2023-06-28 13:51:31.000000 PYPI_TEST_XT-1.0.7/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 13:51:42.965266 PYPI_TEST_XT-1.0.7/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:51:42.965266 PYPI_TEST_XT-1.0.7/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:51:42.965266 PYPI_TEST_XT-1.0.7/src/PYPI_TEST_XT.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      411 2023-06-28 13:51:42.000000 PYPI_TEST_XT-1.0.7/src/PYPI_TEST_XT.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      249 2023-06-28 13:51:42.000000 PYPI_TEST_XT-1.0.7/src/PYPI_TEST_XT.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:51:42.000000 PYPI_TEST_XT-1.0.7/src/PYPI_TEST_XT.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 13:51:42.000000 PYPI_TEST_XT-1.0.7/src/PYPI_TEST_XT.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:51:42.965266 PYPI_TEST_XT-1.0.7/src/PyPI_test_XT/
+-rw-r--r--   0 runner    (1001) docker     (123)      664 2023-06-28 13:51:31.000000 PYPI_TEST_XT-1.0.7/src/PyPI_test_XT/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2003 2023-06-28 13:51:31.000000 PYPI_TEST_XT-1.0.7/src/PyPI_test_XT/example.py
```

### Comparing `PYPI_TEST_XT-0.0.1/LICENSE` & `PYPI_TEST_XT-1.0.7/LICENSE`

 * *Files identical despite different names*

### Comparing `PYPI_TEST_XT-0.0.1/src/PyPI_test_XT/__init__.py` & `PYPI_TEST_XT-1.0.7/src/PyPI_test_XT/__init__.py`

 * *Files identical despite different names*

### Comparing `PYPI_TEST_XT-0.0.1/src/PyPI_test_XT/example.py` & `PYPI_TEST_XT-1.0.7/src/PyPI_test_XT/example.py`

 * *Files 3% similar despite different names*

```diff
@@ -80,8 +80,14 @@
 # print(theta)
 theta_0 += np.array(mistake) @ y
 # print(theta_0)
 
 for i in range(10):
      print(y[i] * (theta @ X[i] + theta_0))
      if y[i] * (theta @ X[i] + theta_0) <= 0:
-          print("False")
+          print("False")
+
+def Hello_World():
+    print("Hello World")
+
+def Happy_day():
+    print("Happy day")
```

