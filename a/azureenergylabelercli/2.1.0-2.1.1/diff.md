# Comparing `tmp/azureenergylabelercli-2.1.0.tar.gz` & `tmp/azureenergylabelercli-2.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "azureenergylabelercli-2.1.0.tar", last modified: Mon May 15 09:23:40 2023, max compression
+gzip compressed data, was "azureenergylabelercli-2.1.1.tar", last modified: Wed Jun 28 10:39:33 2023, max compression
```

## Comparing `azureenergylabelercli-2.1.0.tar` & `azureenergylabelercli-2.1.1.tar`

### file list

```diff
@@ -1,56 +1,56 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 09:23:40.703066 azureenergylabelercli-2.1.0/
--rwxr-xr-x   0 runner    (1001) docker     (123)        5 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/.VERSION
--rwxr-xr-x   0 runner    (1001) docker     (123)      167 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/AUTHORS.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)     1298 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/CONTRIBUTING.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)     1162 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/HISTORY.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/LICENSE
--rwxr-xr-x   0 runner    (1001) docker     (123)      452 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     9874 2023-05-15 09:23:40.703066 azureenergylabelercli-2.1.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      634 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/Pipfile
--rw-r--r--   0 runner    (1001) docker     (123)   108010 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/Pipfile.lock
--rwxr-xr-x   0 runner    (1001) docker     (123)     8103 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/README.rst
--rw-r--r--   0 runner    (1001) docker     (123)      961 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/USAGE.rst
--rw-r--r--   0 runner    (1001) docker     (123)     4263 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/azure_energy_labeler_cli.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 09:23:40.699066 azureenergylabelercli-2.1.0/azureenergylabelercli/
--rwxr-xr-x   0 runner    (1001) docker     (123)        5 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/.VERSION
--rwxr-xr-x   0 runner    (1001) docker     (123)      167 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/AUTHORS.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)     1298 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/CONTRIBUTING.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)     1162 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/HISTORY.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      634 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/Pipfile
--rw-r--r--   0 runner    (1001) docker     (123)   108010 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/Pipfile.lock
--rwxr-xr-x   0 runner    (1001) docker     (123)     8103 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/README.rst
--rw-r--r--   0 runner    (1001) docker     (123)      961 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/USAGE.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)     2170 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2135 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/_version.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    18592 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/azureenergylabelercli.py
--rw-r--r--   0 runner    (1001) docker     (123)     1913 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/azureenergylabelercliexceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 09:23:40.699066 azureenergylabelercli-2.1.0/azureenergylabelercli/conf/
--rw-r--r--   0 runner    (1001) docker     (123)      824 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/conf/logging.json-example
--rw-r--r--   0 runner    (1001) docker     (123)      588 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/dev-requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      428 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)     4150 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/azureenergylabelercli/validators.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 09:23:40.699066 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     9874 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1335 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       71 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      588 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/dev-requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 09:23:40.703066 azureenergylabelercli-2.1.0/docs/
--rwxr-xr-x   0 runner    (1001) docker     (123)     6822 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/Makefile
--rwxr-xr-x   0 runner    (1001) docker     (123)       28 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/authors.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)     9072 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/conf.py
--rwxr-xr-x   0 runner    (1001) docker     (123)       33 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/contributing.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)       28 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/history.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)      537 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/installation.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)       27 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/readme.rst
--rwxr-xr-x   0 runner    (1001) docker     (123)       26 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/docs/usage.rst
--rw-r--r--   0 runner    (1001) docker     (123)      428 2023-05-15 09:23:40.000000 azureenergylabelercli-2.1.0/requirements.txt
--rwxr-xr-x   0 runner    (1001) docker     (123)      161 2023-05-15 09:23:40.703066 azureenergylabelercli-2.1.0/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     2451 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 09:23:40.703066 azureenergylabelercli-2.1.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)     2286 2023-05-15 09:22:04.000000 azureenergylabelercli-2.1.0/tests/test_azureenergylabelercli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:39:33.188166 azureenergylabelercli-2.1.1/
+-rwxr-xr-x   0 runner    (1001) docker     (123)        5 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/.VERSION
+-rwxr-xr-x   0 runner    (1001) docker     (123)      167 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/AUTHORS.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1298 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/CONTRIBUTING.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1232 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/HISTORY.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/LICENSE
+-rwxr-xr-x   0 runner    (1001) docker     (123)      452 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     9944 2023-06-28 10:39:33.188166 azureenergylabelercli-2.1.1/PKG-INFO
+-rwxr-xr-x   0 runner    (1001) docker     (123)      634 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/Pipfile
+-rw-r--r--   0 runner    (1001) docker     (123)   108860 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/Pipfile.lock
+-rwxr-xr-x   0 runner    (1001) docker     (123)     8103 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/README.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/USAGE.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     4263 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/azure_energy_labeler_cli.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:39:33.184166 azureenergylabelercli-2.1.1/azureenergylabelercli/
+-rwxr-xr-x   0 runner    (1001) docker     (123)        5 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/.VERSION
+-rwxr-xr-x   0 runner    (1001) docker     (123)      167 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/AUTHORS.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1298 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/CONTRIBUTING.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1232 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/HISTORY.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/LICENSE
+-rwxr-xr-x   0 runner    (1001) docker     (123)      634 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/Pipfile
+-rw-r--r--   0 runner    (1001) docker     (123)   108860 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/Pipfile.lock
+-rwxr-xr-x   0 runner    (1001) docker     (123)     8103 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/README.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/USAGE.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2170 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2135 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/_version.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    18592 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/azureenergylabelercli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1913 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/azureenergylabelercliexceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:39:33.188166 azureenergylabelercli-2.1.1/azureenergylabelercli/conf/
+-rw-r--r--   0 runner    (1001) docker     (123)      824 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/conf/logging.json-example
+-rw-r--r--   0 runner    (1001) docker     (123)      588 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/dev-requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      428 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     4150 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/azureenergylabelercli/validators.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:39:33.188166 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     9944 2023-06-28 10:39:33.000000 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1335 2023-06-28 10:39:33.000000 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:39:33.000000 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       71 2023-06-28 10:39:33.000000 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:39:33.000000 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 10:39:33.000000 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 10:39:33.000000 azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      588 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/dev-requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:39:33.188166 azureenergylabelercli-2.1.1/docs/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     6822 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/Makefile
+-rwxr-xr-x   0 runner    (1001) docker     (123)       28 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/authors.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)     9072 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/conf.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)       33 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/contributing.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)       28 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/history.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)      537 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/installation.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)       27 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/readme.rst
+-rwxr-xr-x   0 runner    (1001) docker     (123)       26 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/docs/usage.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      428 2023-06-28 10:39:32.000000 azureenergylabelercli-2.1.1/requirements.txt
+-rwxr-xr-x   0 runner    (1001) docker     (123)      161 2023-06-28 10:39:33.188166 azureenergylabelercli-2.1.1/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2451 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:39:33.188166 azureenergylabelercli-2.1.1/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)     2286 2023-06-28 10:37:19.000000 azureenergylabelercli-2.1.1/tests/test_azureenergylabelercli.py
```

### Comparing `azureenergylabelercli-2.1.0/CONTRIBUTING.rst` & `azureenergylabelercli-2.1.1/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/HISTORY.rst` & `azureenergylabelercli-2.1.1/HISTORY.rst`

 * *Files 3% similar despite different names*

```diff
@@ -60,7 +60,13 @@
 
 
 2.1.0 (15-05-2023)
 ------------------
 
 * Added option to disable banner and spinner
 * Improved filtering of findings
+
+
+2.1.1 (28-06-2023)
+------------------
+
+* Updated library dependency
```

### Comparing `azureenergylabelercli-2.1.0/LICENSE` & `azureenergylabelercli-2.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/PKG-INFO` & `azureenergylabelercli-2.1.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: azureenergylabelercli
-Version: 2.1.0
+Version: 2.1.1
 Summary: A cli to help generate energy label for Azure tenant, subscriptions and resource groups.
 Home-page: https://github.com/schubergphilis/azureenergylabelercli
 Author: Sayantan Khanra
 Author-email: skhanra@schubergphilis.com
 License: MIT
 Keywords: azureenergylabelercli
 Classifier: Development Status :: 1 - Planning
@@ -297,7 +297,13 @@
 
 
 2.1.0 (15-05-2023)
 ------------------
 
 * Added option to disable banner and spinner
 * Improved filtering of findings
+
+
+2.1.1 (28-06-2023)
+------------------
+
+* Updated library dependency
```

### Comparing `azureenergylabelercli-2.1.0/Pipfile` & `azureenergylabelercli-2.1.1/Pipfile`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,14 @@
 twine = ">=4.0,<5.0"
 coloredlogs = ">=15.0,<16.0"
 emoji = ">=2.0,<3.0"
 toml = ">=0.1,<1.0"
 
 [packages]
 coloredlogs = "~=15.0.1"
-azureenergylabelerlib = "~=3.2.0"
+azureenergylabelerlib = "~=3.2.1"
 yaspin = "~=2.3.0"
 terminaltables = "~=3.1.10"
 art = "~=5.8"
 
 [requires]
 python_version = "3.9"
```

### Comparing `azureenergylabelercli-2.1.0/Pipfile.lock` & `azureenergylabelercli-2.1.1/Pipfile.lock`

 * *Files 1% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9778760838878805%*

 * *Differences: {"'_meta'": "{'hash': {'sha256': "*

 * *            "'ca78e85ea73ea3f64c6a1d021f5f0a8b244d235f050aceb29054d202287b325b'}}",*

 * * "'default'": "{'azure-cli-core': {'hashes': "*

 * *              "['sha256:628d1008d80e0459be2a48c5c7c434b713e8e57e5662eacfdd08fe6eb6caa18c', "*

 * *              "'sha256:c8dc31dff20db94f465e3a89ab84edbe28675ba65fc79793673c3d177409fa3f'], "*

 * *              "'version': '==2.49.0'}, 'azure-core': {'hashes': "*

 * *              "['sha256:1b4b19f455eb7b4332c6f92adc2c669353ded07c2722eb436165f0c253737792', "*

 * *  […]*

```diff
@@ -1,11 +1,11 @@
 {
     "_meta": {
         "hash": {
-            "sha256": "9ebe67dc8190e1681e4c386e9b6648d3934e593c5b5a41a3af6565836c604dc0"
+            "sha256": "ca78e85ea73ea3f64c6a1d021f5f0a8b244d235f050aceb29054d202287b325b"
         },
         "pipfile-spec": 6,
         "requires": {
             "python_version": "3.9"
         },
         "sources": [
             {
@@ -44,19 +44,19 @@
                 "sha256:9b02463468fc51c77200dadee970cf02c9576008c4f3b99d7ed02371ec037bd1"
             ],
             "index": "pypi",
             "version": "==5.9"
         },
         "azure-cli-core": {
             "hashes": [
-                "sha256:d70ebe7a59bcb91ab1fdeb5d931a74a04c3def6320bbfdfd506eec18a0de0c3b",
-                "sha256:e9300ca40c4f7cb1c95ac29814045d7faa632f5245a9dae99c7545a743893105"
+                "sha256:628d1008d80e0459be2a48c5c7c434b713e8e57e5662eacfdd08fe6eb6caa18c",
+                "sha256:c8dc31dff20db94f465e3a89ab84edbe28675ba65fc79793673c3d177409fa3f"
             ],
             "markers": "python_full_version >= '3.7.0'",
-            "version": "==2.48.1"
+            "version": "==2.49.0"
         },
         "azure-cli-telemetry": {
             "hashes": [
                 "sha256:502cbd90723a16603822909befd096ca0b1707de1e70cf730e7b4700ddd7a456",
                 "sha256:ca996d162ab689c865f6b60be23b9757c26c3d97928e3319858eea83462df08d"
             ],
             "version": "==1.0.8"
@@ -66,19 +66,19 @@
                 "sha256:4ac0cd3214e36b6a1b6a442686722a5d8cc449603aa833f3f0f40bda836704a3",
                 "sha256:5c12d3dcf4ec20599ca6b0d3e09e86e146353d443e7fcc050c9a19c1f9df20ad"
             ],
             "version": "==1.1.28"
         },
         "azure-core": {
             "hashes": [
-                "sha256:075fe06b74c3007950dd93d49440c2f3430fd9b4a5a2756ec8c79454afc989c6",
-                "sha256:d9664b4bc2675d72fba461a285ac43ae33abb2967014a955bf136d9703a2ab3c"
+                "sha256:1b4b19f455eb7b4332c6f92adc2c669353ded07c2722eb436165f0c253737792",
+                "sha256:5975c20808fa388243f01a8b79021bfbe114f503a27c543f002c5fc8bbdd73dd"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==1.26.4"
+            "version": "==1.27.1"
         },
         "azure-identity": {
             "hashes": [
                 "sha256:bd700cebb80cd9862098587c29d8677e819beca33c62568ced6d5a8e5e332b82",
                 "sha256:c931c27301ffa86b07b4dcf574e29da73e3deba9ab5d1fe4f445bb6a3117e260"
             ],
             "markers": "python_version >= '3.7'",
@@ -90,19 +90,19 @@
                 "sha256:d195208340094f98e5a6661b781cde6f6a051e79ce317caabd8ff97030a9b3ae"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==1.4.0"
         },
         "azure-mgmt-resource": {
             "hashes": [
-                "sha256:b556803a3b8699dbcd1f4c33c8229830225c8c61ba058323d5bae7dc7785d65e",
-                "sha256:e6137abc3244efdecc730feed05b17542ccdaf8735a66b9141ad0a378d872922"
+                "sha256:c2ba6cfd99df95f55f36eadc4245e3dc713257302a1fd0277756d94bd8cb28e0",
+                "sha256:f185eec72bbc39f42bcb83ae6f1bad744f0e3f20a12d9b2b3e70d16c74ad9cc0"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==23.0.0"
+            "version": "==23.0.1"
         },
         "azure-mgmt-resourcegraph": {
             "hashes": [
                 "sha256:0cf55f7ea82dc03e69d0fae0f1606e09b08b80b6ae23bd597d8b62b1ed938ace",
                 "sha256:d25f01dae3897780fb3ddca16d1625b6347c32f1b581c767fba5ef3b24443f11"
             ],
             "markers": "python_version >= '3.7'",
@@ -122,19 +122,19 @@
                 "sha256:91bb192b2a97939c4259c72373bac0f41e30810bbc853d5184f0f45904eacafd"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==12.16.0"
         },
         "azureenergylabelerlib": {
             "hashes": [
-                "sha256:d7197b14424bd3745def7fabb60338891c49f210b79e1a425b912d393f51c389",
-                "sha256:df0fcec873b7978da6bb55af83017ddb40d0d99842f77ac337687fd3338cad13"
+                "sha256:d59c3590b8aab30bad440a220b34bb4ea7bf94ab2504108c91ace2ab00a66951",
+                "sha256:db52c86d7cc165c24ab620488e542f9d834a1a4fb67cf0328f47bebf643a8097"
             ],
             "index": "pypi",
-            "version": "==3.2.0"
+            "version": "==3.2.1"
         },
         "bcrypt": {
             "hashes": [
                 "sha256:089098effa1bc35dc055366740a067a2fc76987e8ec75349eb9484061c54f535",
                 "sha256:08d2947c490093a11416df18043c27abe3921558d2c03e2076ccb28a116cb6d0",
                 "sha256:0eaa47d4661c326bfc9d08d16debbc4edf78778e6aaba29c1bc7ce67214d4410",
                 "sha256:27d375903ac8261cfe4047f6709d16f7d18d39b1ec92aaf72af989552a650ebd",
@@ -157,19 +157,19 @@
                 "sha256:fbdaec13c5105f0c4e5c52614d04f0bca5f5af007910daa8b6b12095edaa67b3"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==4.0.1"
         },
         "cachetools": {
             "hashes": [
-                "sha256:13dfddc7b8df938c21a940dfa6557ce6e94a2f1cdfa58eb90c805721d58f2c14",
-                "sha256:429e1a1e845c008ea6c85aa35d4b98b65d6a9763eeef3e37e92728a12d1de9d4"
+                "sha256:95ef631eeaea14ba2e36f06437f36463aac3a096799e876ee55e5cdccb102590",
+                "sha256:dce83f2d9b4e1f732a8cd44af8e8fab2dbe46201467fc98b3ef8f269092bf62b"
             ],
-            "markers": "python_version ~= '3.7'",
-            "version": "==5.3.0"
+            "markers": "python_version >= '3.7'",
+            "version": "==5.3.1"
         },
         "certifi": {
             "hashes": [
                 "sha256:0f0d56dc5a6ad56fd4ba36484d6cc34451e1c6548c61daad8c320169f91eddc7",
                 "sha256:c6c2e98f5c7869efca1f8916fed228dd91539f9f1b444c314c06eef02980c716"
             ],
             "markers": "python_version >= '3.6'",
@@ -466,19 +466,19 @@
                 "sha256:a392980d2b6cffa644431898be54b0045151319d1e7ec34f0cfed48767dd334f"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==23.1"
         },
         "paramiko": {
             "hashes": [
-                "sha256:6950faca6819acd3219d4ae694a23c7a87ee38d084f70c1724b0c0dbb8b75769",
-                "sha256:f0caa660e797d9cd10db6fc6ae81e2c9b2767af75c3180fcd0e46158cd368d7f"
+                "sha256:93cdce625a8a1dc12204439d45033f3261bdb2c201648cfcdc06f9fd0f94ec29",
+                "sha256:df0f9dd8903bc50f2e10580af687f3015bf592a377cd438d2ec9546467a14eb8"
             ],
             "markers": "python_version >= '3.6'",
-            "version": "==3.1.0"
+            "version": "==3.2.0"
         },
         "pkginfo": {
             "hashes": [
                 "sha256:4b7a555a6d5a22169fcc9cf7bfd78d296b0361adad412a346c1226849af5e546",
                 "sha256:8fd5896e8718a4372f0ea9cc9d96f6417c9b986e23a4d116dda26b62cc29d046"
             ],
             "markers": "python_version >= '3.6'",
@@ -549,19 +549,19 @@
                 "sha256:e46dae94e34b085175f8abb3b0aaa7da40767865ac82c928eeb9e57e1ea8a543"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==1.5.0"
         },
         "pyopenssl": {
             "hashes": [
-                "sha256:841498b9bec61623b1b6c47ebbc02367c07d60e0e195f19790817f10cc8db0b7",
-                "sha256:9e0c526404a210df9d2b18cd33364beadb0dc858a739b885677bc65e105d4a4c"
+                "sha256:24f0dc5227396b3e831f4c7f602b950a5e9833d292c8e4a2e06b709292806ae2",
+                "sha256:276f931f55a452e7dea69c7173e984eb2a4407ce413c918aa34b55f82f9b8bac"
             ],
             "markers": "python_version >= '3.6'",
-            "version": "==23.1.1"
+            "version": "==23.2.0"
         },
         "pysocks": {
             "hashes": [
                 "sha256:08e69f092cc6dbe92a0fdd16eeb9b9ffbc13cadfe5ca4c7bd92ffb078b293299",
                 "sha256:2725bd0a9925919b9b51739eea5f9e2bae91e83288108a9ad338b2e3a4435ee5",
                 "sha256:3f8804571ebe159c380ac6de37643bb4685970655d3bba243530d6558b799aa0"
             ],
@@ -622,19 +622,19 @@
             "version": "==6.0"
         },
         "requests": {
             "extras": [
                 "socks"
             ],
             "hashes": [
-                "sha256:10e94cc4f3121ee6da529d358cdaeaff2f1c409cd377dbc72b825852f2f7e294",
-                "sha256:239d7d4458afcb28a692cdd298d87542235f4ca8d36d03a15bfc128a6559a2f4"
+                "sha256:58cd2187c01e70e6e26505bca751777aa9f2ee0b7f4300988b709f44e013003f",
+                "sha256:942c5a758f98d790eaed1a29cb6eefc7ffb0d1cf7af05c3d2791656dbd6ad1e1"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.30.0"
+            "version": "==2.31.0"
         },
         "requests-oauthlib": {
             "hashes": [
                 "sha256:2577c501a2fb8d05a304c09d090d6e47c306fef15809d102b327cf8364bddab5",
                 "sha256:75beac4a47881eeb94d5ea5d6ad31ef88856affe2332b9aafb52c6452ccf0d7a"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -677,27 +677,27 @@
                 "sha256:e4fdc4179c9e4aab5f674d80f09d76fa436b96fdc698a8505e0a36bf0804a874"
             ],
             "index": "pypi",
             "version": "==3.1.10"
         },
         "typing-extensions": {
             "hashes": [
-                "sha256:5cb5f4a79139d699607b3ef622a1dedafa84e115ab0024e0d9c044a9479ca7cb",
-                "sha256:fb33085c39dd998ac16d1431ebc293a8b3eedd00fd4a32de0ff79002c19511b4"
+                "sha256:88a4153d8505aabbb4e13aacb7c486c2b4a33ca3b3f807914a9b4c844c471c26",
+                "sha256:d91d5919357fe7f681a9f2b5b4cb2a5f1ef0a1e9f59c4d8ff0d3491e05c0ffd5"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==4.5.0"
+            "version": "==4.6.3"
         },
         "urllib3": {
             "hashes": [
-                "sha256:61717a1095d7e155cdb737ac7bb2f4324a858a1e2e6466f6d03ff630ca68d3cc",
-                "sha256:d055c2f9d38dc53c808f6fdc8eab7360b6fdbbde02340ed25cfbcd817c62469e"
+                "sha256:48e7fafa40319d358848e1bc6809b208340fafe2096f1725d05d67443d0483d1",
+                "sha256:bee28b5e56addb8226c96f7f13ac28cb4c301dd5ea8a6ca179c0b9835e032825"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.0.2"
+            "version": "==2.0.3"
         },
         "yaspin": {
             "hashes": [
                 "sha256:17b5548479b3d5b30adec7a87ffcdcddb403d14a2bb86fbcee97f37951e13427",
                 "sha256:547afd1a9700ac3a29a9f5591c70343bef186ed5dfb5e545a9bb0c77e561a1c9"
             ],
             "index": "pypi",
@@ -751,19 +751,19 @@
                 "sha256:33c16e3353dbd13028ab4799a0f89a83f113405c766e9c122df8a06f5b85b3f4"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==6.0.0"
         },
         "cachetools": {
             "hashes": [
-                "sha256:13dfddc7b8df938c21a940dfa6557ce6e94a2f1cdfa58eb90c805721d58f2c14",
-                "sha256:429e1a1e845c008ea6c85aa35d4b98b65d6a9763eeef3e37e92728a12d1de9d4"
+                "sha256:95ef631eeaea14ba2e36f06437f36463aac3a096799e876ee55e5cdccb102590",
+                "sha256:dce83f2d9b4e1f732a8cd44af8e8fab2dbe46201467fc98b3ef8f269092bf62b"
             ],
-            "markers": "python_version ~= '3.7'",
-            "version": "==5.3.0"
+            "markers": "python_version >= '3.7'",
+            "version": "==5.3.1"
         },
         "certifi": {
             "hashes": [
                 "sha256:0f0d56dc5a6ad56fd4ba36484d6cc34451e1c6548c61daad8c320169f91eddc7",
                 "sha256:c6c2e98f5c7869efca1f8916fed228dd91539f9f1b444c314c06eef02980c716"
             ],
             "markers": "python_version >= '3.6'",
@@ -941,68 +941,77 @@
                 "sha256:7c991aa71a4577af2f82600d8f8f3a89f936baeaf9b50a9c197da014e5bf16b0"
             ],
             "index": "pypi",
             "version": "==15.0.1"
         },
         "coverage": {
             "hashes": [
-                "sha256:0342a28617e63ad15d96dca0f7ae9479a37b7d8a295f749c14f3436ea59fdcb3",
-                "sha256:066b44897c493e0dcbc9e6a6d9f8bbb6607ef82367cf6810d387c09f0cd4fe9a",
-                "sha256:10b15394c13544fce02382360cab54e51a9e0fd1bd61ae9ce012c0d1e103c813",
-                "sha256:12580845917b1e59f8a1c2ffa6af6d0908cb39220f3019e36c110c943dc875b0",
-                "sha256:156192e5fd3dbbcb11cd777cc469cf010a294f4c736a2b2c891c77618cb1379a",
-                "sha256:1637253b11a18f453e34013c665d8bf15904c9e3c44fbda34c643fbdc9d452cd",
-                "sha256:292300f76440651529b8ceec283a9370532f4ecba9ad67d120617021bb5ef139",
-                "sha256:30dcaf05adfa69c2a7b9f7dfd9f60bc8e36b282d7ed25c308ef9e114de7fc23b",
-                "sha256:338aa9d9883aaaad53695cb14ccdeb36d4060485bb9388446330bef9c361c252",
-                "sha256:373ea34dca98f2fdb3e5cb33d83b6d801007a8074f992b80311fc589d3e6b790",
-                "sha256:38c0a497a000d50491055805313ed83ddba069353d102ece8aef5d11b5faf045",
-                "sha256:40cc0f91c6cde033da493227797be2826cbf8f388eaa36a0271a97a332bfd7ce",
-                "sha256:4436cc9ba5414c2c998eaedee5343f49c02ca93b21769c5fdfa4f9d799e84200",
-                "sha256:509ecd8334c380000d259dc66feb191dd0a93b21f2453faa75f7f9cdcefc0718",
-                "sha256:5c587f52c81211d4530fa6857884d37f514bcf9453bdeee0ff93eaaf906a5c1b",
-                "sha256:5f3671662dc4b422b15776cdca89c041a6349b4864a43aa2350b6b0b03bbcc7f",
-                "sha256:6599bf92f33ab041e36e06d25890afbdf12078aacfe1f1d08c713906e49a3fe5",
-                "sha256:6e8a95f243d01ba572341c52f89f3acb98a3b6d1d5d830efba86033dd3687ade",
-                "sha256:706ec567267c96717ab9363904d846ec009a48d5f832140b6ad08aad3791b1f5",
-                "sha256:780551e47d62095e088f251f5db428473c26db7829884323e56d9c0c3118791a",
-                "sha256:7ff8f3fb38233035028dbc93715551d81eadc110199e14bbbfa01c5c4a43f8d8",
-                "sha256:828189fcdda99aae0d6bf718ea766b2e715eabc1868670a0a07bf8404bf58c33",
-                "sha256:857abe2fa6a4973f8663e039ead8d22215d31db613ace76e4a98f52ec919068e",
-                "sha256:883123d0bbe1c136f76b56276074b0c79b5817dd4238097ffa64ac67257f4b6c",
-                "sha256:8877d9b437b35a85c18e3c6499b23674684bf690f5d96c1006a1ef61f9fdf0f3",
-                "sha256:8e575a59315a91ccd00c7757127f6b2488c2f914096077c745c2f1ba5b8c0969",
-                "sha256:97072cc90f1009386c8a5b7de9d4fc1a9f91ba5ef2146c55c1f005e7b5c5e068",
-                "sha256:9a22cbb5ede6fade0482111fa7f01115ff04039795d7092ed0db43522431b4f2",
-                "sha256:a063aad9f7b4c9f9da7b2550eae0a582ffc7623dca1c925e50c3fbde7a579771",
-                "sha256:a08c7401d0b24e8c2982f4e307124b671c6736d40d1c39e09d7a8687bddf83ed",
-                "sha256:a0b273fe6dc655b110e8dc89b8ec7f1a778d78c9fd9b4bda7c384c8906072212",
-                "sha256:a2b3b05e22a77bb0ae1a3125126a4e08535961c946b62f30985535ed40e26614",
-                "sha256:a66e055254a26c82aead7ff420d9fa8dc2da10c82679ea850d8feebf11074d88",
-                "sha256:aa387bd7489f3e1787ff82068b295bcaafbf6f79c3dad3cbc82ef88ce3f48ad3",
-                "sha256:ae453f655640157d76209f42c62c64c4d4f2c7f97256d3567e3b439bd5c9b06c",
-                "sha256:b5016e331b75310610c2cf955d9f58a9749943ed5f7b8cfc0bb89c6134ab0a84",
-                "sha256:b9a4ee55174b04f6af539218f9f8083140f61a46eabcaa4234f3c2a452c4ed11",
-                "sha256:bd3b4b8175c1db502adf209d06136c000df4d245105c8839e9d0be71c94aefe1",
-                "sha256:bebea5f5ed41f618797ce3ffb4606c64a5de92e9c3f26d26c2e0aae292f015c1",
-                "sha256:c10fbc8a64aa0f3ed136b0b086b6b577bc64d67d5581acd7cc129af52654384e",
-                "sha256:c2c41c1b1866b670573657d584de413df701f482574bad7e28214a2362cb1fd1",
-                "sha256:cf97ed82ca986e5c637ea286ba2793c85325b30f869bf64d3009ccc1a31ae3fd",
-                "sha256:d1f25ee9de21a39b3a8516f2c5feb8de248f17da7eead089c2e04aa097936b47",
-                "sha256:d2fbc2a127e857d2f8898aaabcc34c37771bf78a4d5e17d3e1f5c30cd0cbc62a",
-                "sha256:dc945064a8783b86fcce9a0a705abd7db2117d95e340df8a4333f00be5efb64c",
-                "sha256:ddc5a54edb653e9e215f75de377354e2455376f416c4378e1d43b08ec50acc31",
-                "sha256:e8834e5f17d89e05697c3c043d3e58a8b19682bf365048837383abfe39adaed5",
-                "sha256:ef9659d1cda9ce9ac9585c045aaa1e59223b143f2407db0eaee0b61a4f266fb6",
-                "sha256:f6f5cab2d7f0c12f8187a376cc6582c477d2df91d63f75341307fcdcb5d60303",
-                "sha256:f81c9b4bd8aa747d417407a7f6f0b1469a43b36a85748145e144ac4e8d303cb5",
-                "sha256:f99ef080288f09ffc687423b8d60978cf3a465d3f404a18d1a05474bd8575a47"
+                "sha256:06a9a2be0b5b576c3f18f1a241f0473575c4a26021b52b2a85263a00f034d51f",
+                "sha256:06fb182e69f33f6cd1d39a6c597294cff3143554b64b9825d1dc69d18cc2fff2",
+                "sha256:0a5f9e1dbd7fbe30196578ca36f3fba75376fb99888c395c5880b355e2875f8a",
+                "sha256:0e1f928eaf5469c11e886fe0885ad2bf1ec606434e79842a879277895a50942a",
+                "sha256:171717c7cb6b453aebac9a2ef603699da237f341b38eebfee9be75d27dc38e01",
+                "sha256:1e9d683426464e4a252bf70c3498756055016f99ddaec3774bf368e76bbe02b6",
+                "sha256:201e7389591af40950a6480bd9edfa8ed04346ff80002cec1a66cac4549c1ad7",
+                "sha256:245167dd26180ab4c91d5e1496a30be4cd721a5cf2abf52974f965f10f11419f",
+                "sha256:2aee274c46590717f38ae5e4650988d1af340fe06167546cc32fe2f58ed05b02",
+                "sha256:2e07b54284e381531c87f785f613b833569c14ecacdcb85d56b25c4622c16c3c",
+                "sha256:31563e97dae5598556600466ad9beea39fb04e0229e61c12eaa206e0aa202063",
+                "sha256:33d6d3ea29d5b3a1a632b3c4e4f4ecae24ef170b0b9ee493883f2df10039959a",
+                "sha256:3d376df58cc111dc8e21e3b6e24606b5bb5dee6024f46a5abca99124b2229ef5",
+                "sha256:419bfd2caae268623dd469eff96d510a920c90928b60f2073d79f8fe2bbc5959",
+                "sha256:48c19d2159d433ccc99e729ceae7d5293fbffa0bdb94952d3579983d1c8c9d97",
+                "sha256:49969a9f7ffa086d973d91cec8d2e31080436ef0fb4a359cae927e742abfaaa6",
+                "sha256:52edc1a60c0d34afa421c9c37078817b2e67a392cab17d97283b64c5833f427f",
+                "sha256:537891ae8ce59ef63d0123f7ac9e2ae0fc8b72c7ccbe5296fec45fd68967b6c9",
+                "sha256:54b896376ab563bd38453cecb813c295cf347cf5906e8b41d340b0321a5433e5",
+                "sha256:58c2ccc2f00ecb51253cbe5d8d7122a34590fac9646a960d1430d5b15321d95f",
+                "sha256:5b7540161790b2f28143191f5f8ec02fb132660ff175b7747b95dcb77ac26562",
+                "sha256:5baa06420f837184130752b7c5ea0808762083bf3487b5038d68b012e5937dbe",
+                "sha256:5e330fc79bd7207e46c7d7fd2bb4af2963f5f635703925543a70b99574b0fea9",
+                "sha256:61b9a528fb348373c433e8966535074b802c7a5d7f23c4f421e6c6e2f1697a6f",
+                "sha256:63426706118b7f5cf6bb6c895dc215d8a418d5952544042c8a2d9fe87fcf09cb",
+                "sha256:6d040ef7c9859bb11dfeb056ff5b3872436e3b5e401817d87a31e1750b9ae2fb",
+                "sha256:6f48351d66575f535669306aa7d6d6f71bc43372473b54a832222803eb956fd1",
+                "sha256:7ee7d9d4822c8acc74a5e26c50604dff824710bc8de424904c0982e25c39c6cb",
+                "sha256:81c13a1fc7468c40f13420732805a4c38a105d89848b7c10af65a90beff25250",
+                "sha256:8d13c64ee2d33eccf7437961b6ea7ad8673e2be040b4f7fd4fd4d4d28d9ccb1e",
+                "sha256:8de8bb0e5ad103888d65abef8bca41ab93721647590a3f740100cd65c3b00511",
+                "sha256:8fa03bce9bfbeeef9f3b160a8bed39a221d82308b4152b27d82d8daa7041fee5",
+                "sha256:924d94291ca674905fe9481f12294eb11f2d3d3fd1adb20314ba89e94f44ed59",
+                "sha256:975d70ab7e3c80a3fe86001d8751f6778905ec723f5b110aed1e450da9d4b7f2",
+                "sha256:976b9c42fb2a43ebf304fa7d4a310e5f16cc99992f33eced91ef6f908bd8f33d",
+                "sha256:9e31cb64d7de6b6f09702bb27c02d1904b3aebfca610c12772452c4e6c21a0d3",
+                "sha256:a342242fe22407f3c17f4b499276a02b01e80f861f1682ad1d95b04018e0c0d4",
+                "sha256:a3d33a6b3eae87ceaefa91ffdc130b5e8536182cd6dfdbfc1aa56b46ff8c86de",
+                "sha256:a895fcc7b15c3fc72beb43cdcbdf0ddb7d2ebc959edac9cef390b0d14f39f8a9",
+                "sha256:afb17f84d56068a7c29f5fa37bfd38d5aba69e3304af08ee94da8ed5b0865833",
+                "sha256:b1c546aca0ca4d028901d825015dc8e4d56aac4b541877690eb76490f1dc8ed0",
+                "sha256:b29019c76039dc3c0fd815c41392a044ce555d9bcdd38b0fb60fb4cd8e475ba9",
+                "sha256:b46517c02ccd08092f4fa99f24c3b83d8f92f739b4657b0f146246a0ca6a831d",
+                "sha256:b7aa5f8a41217360e600da646004f878250a0d6738bcdc11a0a39928d7dc2050",
+                "sha256:b7b4c971f05e6ae490fef852c218b0e79d4e52f79ef0c8475566584a8fb3e01d",
+                "sha256:ba90a9563ba44a72fda2e85302c3abc71c5589cea608ca16c22b9804262aaeb6",
+                "sha256:cb017fd1b2603ef59e374ba2063f593abe0fc45f2ad9abdde5b4d83bd922a353",
+                "sha256:d22656368f0e6189e24722214ed8d66b8022db19d182927b9a248a2a8a2f67eb",
+                "sha256:d2c2db7fd82e9b72937969bceac4d6ca89660db0a0967614ce2481e81a0b771e",
+                "sha256:d39b5b4f2a66ccae8b7263ac3c8170994b65266797fb96cbbfd3fb5b23921db8",
+                "sha256:d62a5c7dad11015c66fbb9d881bc4caa5b12f16292f857842d9d1871595f4495",
+                "sha256:e7d9405291c6928619403db1d10bd07888888ec1abcbd9748fdaa971d7d661b2",
+                "sha256:e84606b74eb7de6ff581a7915e2dab7a28a0517fbe1c9239eb227e1354064dcd",
+                "sha256:eb393e5ebc85245347950143969b241d08b52b88a3dc39479822e073a1a8eb27",
+                "sha256:ebba1cd308ef115925421d3e6a586e655ca5a77b5bf41e02eb0e4562a111f2d1",
+                "sha256:ee57190f24fba796e36bb6d3aa8a8783c643d8fa9760c89f7a98ab5455fbf818",
+                "sha256:f2f67fe12b22cd130d34d0ef79206061bfb5eda52feb6ce0dba0644e20a03cf4",
+                "sha256:f6951407391b639504e3b3be51b7ba5f3528adbf1a8ac3302b687ecababf929e",
+                "sha256:f75f7168ab25dd93110c8a8117a22450c19976afbc44234cbf71481094c1b850",
+                "sha256:fdec9e8cbf13a5bf63290fc6013d216a4c7232efb51548594ca3631a7f13c3a3"
             ],
             "index": "pypi",
-            "version": "==7.2.5"
+            "version": "==7.2.7"
         },
         "cryptography": {
             "hashes": [
                 "sha256:05dc219433b14046c476f6f09d7636b92a1c3e5808b9a6536adf4932b3b2c440",
                 "sha256:0dcca15d3a19a66e63662dc8d30f8036b07be851a8680eda92d079868f106288",
                 "sha256:142bae539ef28a1c76794cca7f49729e7c54423f615cfd9b0b1fa90ebe53244b",
                 "sha256:3daf9b114213f8ba460b829a02896789751626a2a4e7a43a28ee77c04b5e4958",
@@ -1053,26 +1062,26 @@
                 "sha256:28323cbfc9352139fdd3d316fa17f325cc0e9ac74438cbba51d70f9b48f86c3a",
                 "sha256:51f54c0fd886fa3854387f354b19f429d38c04f984f38bc572558b703c0542a6"
             ],
             "version": "==0.2.1"
         },
         "emoji": {
             "hashes": [
-                "sha256:a2986c21e4aba6b9870df40ef487a17be863cb7778dcf1c01e25917b7cd210bb"
+                "sha256:39ad95c9ba270cdfbd141d20c2ebcfc4e295d010b605de66908a098a3ba63a3c"
             ],
             "index": "pypi",
-            "version": "==2.2.0"
+            "version": "==2.6.0"
         },
         "filelock": {
             "hashes": [
-                "sha256:ad98852315c2ab702aeb628412cbf7e95b7ce8c3bf9565670b4eaecf1db370a9",
-                "sha256:fc03ae43288c013d2ea83c8597001b1129db351aad9c57fe2409327916b8e718"
+                "sha256:002740518d8aa59a26b0c76e10fb8c6e15eae825d34b6fdf670333fd7b938d81",
+                "sha256:cbb791cdea2a72f23da6ac5b5269ab0a0d161e9ef0100e653b69049a7706d1ec"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==3.12.0"
+            "version": "==3.12.2"
         },
         "flake8": {
             "hashes": [
                 "sha256:6fbe320aad8d6b95cec8b8e47bc933004678dc63095be98528b7bdd2a9f510db",
                 "sha256:7a1cf6b73744f5806ab95e526f6f0d8c01c66d7bbe349562d22dfca20610b248"
             ],
             "markers": "python_full_version >= '3.6.1'",
@@ -1099,19 +1108,19 @@
                 "sha256:f04893614f6aa713a60cbbe1e6a97403ef633103cdd0ef5eb6efe0deb98dbe8d"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==3.1.31"
         },
         "gitwrapperlib": {
             "hashes": [
-                "sha256:3174bcc0de3fa70f78067cb2bc60a5c9820442d78594fb345bdd56740f64073a",
-                "sha256:97ff470337459649cc3cce39a79622bf36679ec8abc03509d3e1afb1d5360de9"
+                "sha256:2f1c5e0fc69168dde3cd141f56b7714c6841ebe886956c1cd302c5867b640db7",
+                "sha256:90b33ad4568e5ce056d0058b98dd850a6dee2473d3bfc115f35c721e62f95078"
             ],
             "index": "pypi",
-            "version": "==1.0.0"
+            "version": "==1.0.3"
         },
         "humanfriendly": {
             "hashes": [
                 "sha256:1697e1a8a8f550fd43c2865cd84542fc175a61dcb779b6fee18cf6b6ccba1477",
                 "sha256:6b0b831ce8f15f7300721aa49829fc4e83921a9a301cc7f606be6686a2288ddc"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3, 3.4'",
@@ -1131,19 +1140,19 @@
                 "sha256:69150444affb9cb0d5cc5a92b3676f0b2fb7cd9ae39e947a5e11a36b4497cd4a"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
             "version": "==1.4.1"
         },
         "importlib-metadata": {
             "hashes": [
-                "sha256:43dd286a2cd8995d5eaef7fee2066340423b818ed3fd70adf0bad5f1fac53fed",
-                "sha256:92501cdf9cc66ebd3e612f1b4f0c0765dfa42f0fa38ffb319b6bd84dd675d705"
+                "sha256:1aaf550d4f73e5d6783e7acb77aec43d49da8017410afae93822cc9cca98c4d4",
+                "sha256:cb52082e659e97afc5dac71e79de97d8681de3aa07ff18578330904a9d18e5b5"
             ],
             "markers": "python_version < '3.10'",
-            "version": "==6.6.0"
+            "version": "==6.7.0"
         },
         "isort": {
             "hashes": [
                 "sha256:8bef7dde241278824a6d83f44a544709b065191b95b6e50894bdc722fcba0504",
                 "sha256:f84c2818376e66cf843d497486ea8fed8700b340f308f076c6fb1229dff318b6"
             ],
             "markers": "python_full_version >= '3.8.0'",
@@ -1171,19 +1180,19 @@
                 "sha256:6088930bfe239f0e6710546ab9c19c9ef35e29792895fed6e6e31a023a182a61"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==3.1.2"
         },
         "keyring": {
             "hashes": [
-                "sha256:771ed2a91909389ed6148631de678f82ddc73737d85a927f382a8a1b157898cd",
-                "sha256:ba2e15a9b35e21908d0aaf4e0a47acc52d6ae33444df0da2b49d41a46ef6d678"
+                "sha256:4901caaf597bfd3bbd78c9a0c7c4c29fcd8310dab2cffefe749e916b6527acd6",
+                "sha256:ca0746a19ec421219f4d713f848fa297a661a8a8c1504867e55bfb5e09091509"
             ],
-            "markers": "python_version >= '3.7'",
-            "version": "==23.13.1"
+            "markers": "python_version >= '3.8'",
+            "version": "==24.2.0"
         },
         "lazy-object-proxy": {
             "hashes": [
                 "sha256:09763491ce220c0299688940f8dc2c5d05fd1f45af1e42e636b2e8b2303e4382",
                 "sha256:0a891e4e41b54fd5b8313b96399f8b0e173bbbfc03c7631f01efbe29bb0bcf82",
                 "sha256:189bbd5d41ae7a498397287c408617fe5c48633e7755287b21d741f7db2706a9",
                 "sha256:18b78ec83edbbeb69efdc0e9c1cb41a3b1b1ed11ddd8ded602464c3fc6020494",
@@ -1221,75 +1230,75 @@
                 "sha256:f699ac1c768270c9e384e4cbd268d6e67aebcfae6cd623b4d7c3bfde5a35db59"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==1.9.0"
         },
         "markdown-it-py": {
             "hashes": [
-                "sha256:5a35f8d1870171d9acc47b99612dc146129b631baf04970128b568f190d0cc30",
-                "sha256:7c9a5e412688bc771c67432cbfebcdd686c93ce6484913dccf06cb5a0bea35a1"
+                "sha256:355216845c60bd96232cd8d8c40e8f9765cc86f46880e43a8fd22dc1a1a8cab1",
+                "sha256:e3f60a94fa066dc52ec76661e37c851cb232d92f9886b15cb560aaada2df8feb"
             ],
-            "markers": "python_version >= '3.7'",
-            "version": "==2.2.0"
+            "markers": "python_version >= '3.8'",
+            "version": "==3.0.0"
         },
         "markupsafe": {
             "hashes": [
-                "sha256:0576fe974b40a400449768941d5d0858cc624e3249dfd1e0c33674e5c7ca7aed",
-                "sha256:085fd3201e7b12809f9e6e9bc1e5c96a368c8523fad5afb02afe3c051ae4afcc",
-                "sha256:090376d812fb6ac5f171e5938e82e7f2d7adc2b629101cec0db8b267815c85e2",
-                "sha256:0b462104ba25f1ac006fdab8b6a01ebbfbce9ed37fd37fd4acd70c67c973e460",
-                "sha256:137678c63c977754abe9086a3ec011e8fd985ab90631145dfb9294ad09c102a7",
-                "sha256:1bea30e9bf331f3fef67e0a3877b2288593c98a21ccb2cf29b74c581a4eb3af0",
-                "sha256:22152d00bf4a9c7c83960521fc558f55a1adbc0631fbb00a9471e097b19d72e1",
-                "sha256:22731d79ed2eb25059ae3df1dfc9cb1546691cc41f4e3130fe6bfbc3ecbbecfa",
-                "sha256:2298c859cfc5463f1b64bd55cb3e602528db6fa0f3cfd568d3605c50678f8f03",
-                "sha256:28057e985dace2f478e042eaa15606c7efccb700797660629da387eb289b9323",
-                "sha256:2e7821bffe00aa6bd07a23913b7f4e01328c3d5cc0b40b36c0bd81d362faeb65",
-                "sha256:2ec4f2d48ae59bbb9d1f9d7efb9236ab81429a764dedca114f5fdabbc3788013",
-                "sha256:340bea174e9761308703ae988e982005aedf427de816d1afe98147668cc03036",
-                "sha256:40627dcf047dadb22cd25ea7ecfe9cbf3bbbad0482ee5920b582f3809c97654f",
-                "sha256:40dfd3fefbef579ee058f139733ac336312663c6706d1163b82b3003fb1925c4",
-                "sha256:4cf06cdc1dda95223e9d2d3c58d3b178aa5dacb35ee7e3bbac10e4e1faacb419",
-                "sha256:50c42830a633fa0cf9e7d27664637532791bfc31c731a87b202d2d8ac40c3ea2",
-                "sha256:55f44b440d491028addb3b88f72207d71eeebfb7b5dbf0643f7c023ae1fba619",
-                "sha256:608e7073dfa9e38a85d38474c082d4281f4ce276ac0010224eaba11e929dd53a",
-                "sha256:63ba06c9941e46fa389d389644e2d8225e0e3e5ebcc4ff1ea8506dce646f8c8a",
-                "sha256:65608c35bfb8a76763f37036547f7adfd09270fbdbf96608be2bead319728fcd",
-                "sha256:665a36ae6f8f20a4676b53224e33d456a6f5a72657d9c83c2aa00765072f31f7",
-                "sha256:6d6607f98fcf17e534162f0709aaad3ab7a96032723d8ac8750ffe17ae5a0666",
-                "sha256:7313ce6a199651c4ed9d7e4cfb4aa56fe923b1adf9af3b420ee14e6d9a73df65",
-                "sha256:7668b52e102d0ed87cb082380a7e2e1e78737ddecdde129acadb0eccc5423859",
-                "sha256:7df70907e00c970c60b9ef2938d894a9381f38e6b9db73c5be35e59d92e06625",
-                "sha256:7e007132af78ea9df29495dbf7b5824cb71648d7133cf7848a2a5dd00d36f9ff",
-                "sha256:835fb5e38fd89328e9c81067fd642b3593c33e1e17e2fdbf77f5676abb14a156",
-                "sha256:8bca7e26c1dd751236cfb0c6c72d4ad61d986e9a41bbf76cb445f69488b2a2bd",
-                "sha256:8db032bf0ce9022a8e41a22598eefc802314e81b879ae093f36ce9ddf39ab1ba",
-                "sha256:99625a92da8229df6d44335e6fcc558a5037dd0a760e11d84be2260e6f37002f",
-                "sha256:9cad97ab29dfc3f0249b483412c85c8ef4766d96cdf9dcf5a1e3caa3f3661cf1",
-                "sha256:a4abaec6ca3ad8660690236d11bfe28dfd707778e2442b45addd2f086d6ef094",
-                "sha256:a6e40afa7f45939ca356f348c8e23048e02cb109ced1eb8420961b2f40fb373a",
-                "sha256:a6f2fcca746e8d5910e18782f976489939d54a91f9411c32051b4aab2bd7c513",
-                "sha256:a806db027852538d2ad7555b203300173dd1b77ba116de92da9afbc3a3be3eed",
-                "sha256:abcabc8c2b26036d62d4c746381a6f7cf60aafcc653198ad678306986b09450d",
-                "sha256:b8526c6d437855442cdd3d87eede9c425c4445ea011ca38d937db299382e6fa3",
-                "sha256:bb06feb762bade6bf3c8b844462274db0c76acc95c52abe8dbed28ae3d44a147",
-                "sha256:c0a33bc9f02c2b17c3ea382f91b4db0e6cde90b63b296422a939886a7a80de1c",
-                "sha256:c4a549890a45f57f1ebf99c067a4ad0cb423a05544accaf2b065246827ed9603",
-                "sha256:ca244fa73f50a800cf8c3ebf7fd93149ec37f5cb9596aa8873ae2c1d23498601",
-                "sha256:cf877ab4ed6e302ec1d04952ca358b381a882fbd9d1b07cccbfd61783561f98a",
-                "sha256:d9d971ec1e79906046aa3ca266de79eac42f1dbf3612a05dc9368125952bd1a1",
-                "sha256:da25303d91526aac3672ee6d49a2f3db2d9502a4a60b55519feb1a4c7714e07d",
-                "sha256:e55e40ff0cc8cc5c07996915ad367fa47da6b3fc091fdadca7f5403239c5fec3",
-                "sha256:f03a532d7dee1bed20bc4884194a16160a2de9ffc6354b3878ec9682bb623c54",
-                "sha256:f1cd098434e83e656abf198f103a8207a8187c0fc110306691a2e94a78d0abb2",
-                "sha256:f2bfb563d0211ce16b63c7cb9395d2c682a23187f54c3d79bfec33e6705473c6",
-                "sha256:f8ffb705ffcf5ddd0e80b65ddf7bed7ee4f5a441ea7d3419e861a12eaf41af58"
+                "sha256:05fb21170423db021895e1ea1e1f3ab3adb85d1c2333cbc2310f2a26bc77272e",
+                "sha256:0a4e4a1aff6c7ac4cd55792abf96c915634c2b97e3cc1c7129578aa68ebd754e",
+                "sha256:10bbfe99883db80bdbaff2dcf681dfc6533a614f700da1287707e8a5d78a8431",
+                "sha256:134da1eca9ec0ae528110ccc9e48041e0828d79f24121a1a146161103c76e686",
+                "sha256:1577735524cdad32f9f694208aa75e422adba74f1baee7551620e43a3141f559",
+                "sha256:1b40069d487e7edb2676d3fbdb2b0829ffa2cd63a2ec26c4938b2d34391b4ecc",
+                "sha256:282c2cb35b5b673bbcadb33a585408104df04f14b2d9b01d4c345a3b92861c2c",
+                "sha256:2c1b19b3aaacc6e57b7e25710ff571c24d6c3613a45e905b1fde04d691b98ee0",
+                "sha256:2ef12179d3a291be237280175b542c07a36e7f60718296278d8593d21ca937d4",
+                "sha256:338ae27d6b8745585f87218a3f23f1512dbf52c26c28e322dbe54bcede54ccb9",
+                "sha256:3c0fae6c3be832a0a0473ac912810b2877c8cb9d76ca48de1ed31e1c68386575",
+                "sha256:3fd4abcb888d15a94f32b75d8fd18ee162ca0c064f35b11134be77050296d6ba",
+                "sha256:42de32b22b6b804f42c5d98be4f7e5e977ecdd9ee9b660fda1a3edf03b11792d",
+                "sha256:504b320cd4b7eff6f968eddf81127112db685e81f7e36e75f9f84f0df46041c3",
+                "sha256:525808b8019e36eb524b8c68acdd63a37e75714eac50e988180b169d64480a00",
+                "sha256:56d9f2ecac662ca1611d183feb03a3fa4406469dafe241673d521dd5ae92a155",
+                "sha256:5bbe06f8eeafd38e5d0a4894ffec89378b6c6a625ff57e3028921f8ff59318ac",
+                "sha256:65c1a9bcdadc6c28eecee2c119465aebff8f7a584dd719facdd9e825ec61ab52",
+                "sha256:68e78619a61ecf91e76aa3e6e8e33fc4894a2bebe93410754bd28fce0a8a4f9f",
+                "sha256:69c0f17e9f5a7afdf2cc9fb2d1ce6aabdb3bafb7f38017c0b77862bcec2bbad8",
+                "sha256:6b2b56950d93e41f33b4223ead100ea0fe11f8e6ee5f641eb753ce4b77a7042b",
+                "sha256:787003c0ddb00500e49a10f2844fac87aa6ce977b90b0feaaf9de23c22508b24",
+                "sha256:7ef3cb2ebbf91e330e3bb937efada0edd9003683db6b57bb108c4001f37a02ea",
+                "sha256:8023faf4e01efadfa183e863fefde0046de576c6f14659e8782065bcece22198",
+                "sha256:8758846a7e80910096950b67071243da3e5a20ed2546e6392603c096778d48e0",
+                "sha256:8afafd99945ead6e075b973fefa56379c5b5c53fd8937dad92c662da5d8fd5ee",
+                "sha256:8c41976a29d078bb235fea9b2ecd3da465df42a562910f9022f1a03107bd02be",
+                "sha256:8e254ae696c88d98da6555f5ace2279cf7cd5b3f52be2b5cf97feafe883b58d2",
+                "sha256:9402b03f1a1b4dc4c19845e5c749e3ab82d5078d16a2a4c2cd2df62d57bb0707",
+                "sha256:962f82a3086483f5e5f64dbad880d31038b698494799b097bc59c2edf392fce6",
+                "sha256:9dcdfd0eaf283af041973bff14a2e143b8bd64e069f4c383416ecd79a81aab58",
+                "sha256:aa7bd130efab1c280bed0f45501b7c8795f9fdbeb02e965371bbef3523627779",
+                "sha256:ab4a0df41e7c16a1392727727e7998a467472d0ad65f3ad5e6e765015df08636",
+                "sha256:ad9e82fb8f09ade1c3e1b996a6337afac2b8b9e365f926f5a61aacc71adc5b3c",
+                "sha256:af598ed32d6ae86f1b747b82783958b1a4ab8f617b06fe68795c7f026abbdcad",
+                "sha256:b076b6226fb84157e3f7c971a47ff3a679d837cf338547532ab866c57930dbee",
+                "sha256:b7ff0f54cb4ff66dd38bebd335a38e2c22c41a8ee45aa608efc890ac3e3931bc",
+                "sha256:bfce63a9e7834b12b87c64d6b155fdd9b3b96191b6bd334bf37db7ff1fe457f2",
+                "sha256:c011a4149cfbcf9f03994ec2edffcb8b1dc2d2aede7ca243746df97a5d41ce48",
+                "sha256:c9c804664ebe8f83a211cace637506669e7890fec1b4195b505c214e50dd4eb7",
+                "sha256:ca379055a47383d02a5400cb0d110cef0a776fc644cda797db0c5696cfd7e18e",
+                "sha256:cb0932dc158471523c9637e807d9bfb93e06a95cbf010f1a38b98623b929ef2b",
+                "sha256:cd0f502fe016460680cd20aaa5a76d241d6f35a1c3350c474bac1273803893fa",
+                "sha256:ceb01949af7121f9fc39f7d27f91be8546f3fb112c608bc4029aef0bab86a2a5",
+                "sha256:d080e0a5eb2529460b30190fcfcc4199bd7f827663f858a226a81bc27beaa97e",
+                "sha256:dd15ff04ffd7e05ffcb7fe79f1b98041b8ea30ae9234aed2a9168b5797c3effb",
+                "sha256:df0be2b576a7abbf737b1575f048c23fb1d769f267ec4358296f31c2479db8f9",
+                "sha256:e09031c87a1e51556fdcb46e5bd4f59dfb743061cf93c4d6831bf894f125eb57",
+                "sha256:e4dd52d80b8c83fdce44e12478ad2e85c64ea965e75d66dbeafb0a3e77308fcc",
+                "sha256:fec21693218efe39aa7f8599346e90c705afa52c5b31ae019b2e57e8f6542bb2"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.1.2"
+            "version": "==2.1.3"
         },
         "mccabe": {
             "hashes": [
                 "sha256:348e0240c33b60bbdf4e523192ef919f28cb2c3d7d5c7794f74009290f236325",
                 "sha256:6c2d30ab6be0e4a46919781807b4f0d834ebdd6c6e3dca0bda5a15f863427b6e"
             ],
             "markers": "python_version >= '3.6'",
@@ -1349,27 +1358,27 @@
                 "sha256:8fd5896e8718a4372f0ea9cc9d96f6417c9b986e23a4d116dda26b62cc29d046"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==1.9.6"
         },
         "platformdirs": {
             "hashes": [
-                "sha256:412dae91f52a6f84830f39a8078cecd0e866cb72294a5c66808e74d5e88d251f",
-                "sha256:e2378146f1964972c03c085bb5662ae80b2b8c06226c54b2ff4aa9483e8a13a5"
+                "sha256:b0cabcb11063d21a0b261d557acb0a9d2126350e63b70cdf7db6347baea456dc",
+                "sha256:ca9ed98ce73076ba72e092b23d3c93ea6c4e186b3f1c3dad6edd98ff6ffcca2e"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==3.5.1"
+            "version": "==3.8.0"
         },
         "pluggy": {
             "hashes": [
-                "sha256:4224373bacce55f955a878bf9cfa763c1e360858e330072059e10bad68531159",
-                "sha256:74134bbf457f031a36d68416e1509f34bd5ccc019f0bcc952c7b909d06b37bd3"
+                "sha256:c2fd55a7d7a3863cba1a013e4e2414658b1d07b6bc57b3919e0c63c9abb99849",
+                "sha256:d12f0c4b579b15f5e054301bb226ee85eeeba08ffec228092f8defbaa3a4c4b3"
             ],
-            "markers": "python_version >= '3.6'",
-            "version": "==1.0.0"
+            "markers": "python_version >= '3.7'",
+            "version": "==1.2.0"
         },
         "poetry-semver": {
             "hashes": [
                 "sha256:4e6349bd7231cc657f0e1930f7b204e87e33dfd63eef5cac869363969515083a",
                 "sha256:d809b612aa27b39bf2d0fc9d31b4f4809b0e972646c5f19cfa46c725b7638810"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -1455,19 +1464,19 @@
                 "sha256:ce48bc0516ae9415dd5c752c940dfe601b18fe0f48aa249f2386adfa95a004dd"
             ],
             "markers": "python_full_version >= '3.6.2'",
             "version": "==0.7"
         },
         "pyproject-api": {
             "hashes": [
-                "sha256:435f46547a9ff22cf4208ee274fca3e2869aeb062a4834adfc99a4dd64af3cf9",
-                "sha256:4698a3777c2e0f6b624f8a4599131e2a25376d90fe8d146d7ac74c67c6f97c43"
+                "sha256:999f58fa3c92b23ebd31a6bad5d1f87d456744d75e05391be7f5c729015d3d91",
+                "sha256:9cffcbfb64190f207444d7579d315f3278f2c04ba46d685fad93197b5326d348"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==1.5.1"
+            "version": "==1.5.2"
         },
         "pyyaml": {
             "hashes": [
                 "sha256:01b45c0191e6d66c470b6cf1b9531a771a83c1c4208272ead47a3ae4f2f603bf",
                 "sha256:0283c35a6a9fbf047493e3a0ce8d79ef5030852c51e9d911a27badfde0605293",
                 "sha256:055d937d65826939cb044fc8c9b08889e8c743fdc6a32b33e2390f66013e449b",
                 "sha256:07751360502caac1c067a8132d150cf3d61339af5691fe9e87803040dbc5db57",
@@ -1509,30 +1518,30 @@
                 "sha256:f84fbc98b019fef2ee9a1cb3ce93e3187a6df0b2538a651bfb890254ba9f90b5"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==6.0"
         },
         "readme-renderer": {
             "hashes": [
-                "sha256:cd653186dfc73055656f090f227f5cb22a046d7f71a841dfa305f55c9a513273",
-                "sha256:f67a16caedfa71eef48a31b39708637a6f4664c4394801a7b0d6432d13907343"
+                "sha256:9f77b519d96d03d7d7dce44977ba543090a14397c4f60de5b6eb5b8048110aa4",
+                "sha256:e18feb2a1e7706f2865b81ebb460056d93fb29d69daa10b223c00faa7bd9a00a"
             ],
-            "markers": "python_version >= '3.7'",
-            "version": "==37.3"
+            "markers": "python_version >= '3.8'",
+            "version": "==40.0"
         },
         "requests": {
             "extras": [
                 "socks"
             ],
             "hashes": [
-                "sha256:10e94cc4f3121ee6da529d358cdaeaff2f1c409cd377dbc72b825852f2f7e294",
-                "sha256:239d7d4458afcb28a692cdd298d87542235f4ca8d36d03a15bfc128a6559a2f4"
+                "sha256:58cd2187c01e70e6e26505bca751777aa9f2ee0b7f4300988b709f44e013003f",
+                "sha256:942c5a758f98d790eaed1a29cb6eefc7ffb0d1cf7af05c3d2791656dbd6ad1e1"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.30.0"
+            "version": "==2.31.0"
         },
         "requests-toolbelt": {
             "hashes": [
                 "sha256:7681a0a3d047012b5bdc0ee37d7f8f07ebe76ab08caeccfc3921ce23c88d5bc6",
                 "sha256:cccfdd665f0a24fcf4726e690f65639d272bb0637b9b92dfd91a5568ccf6bd06"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -1552,19 +1561,19 @@
                 "sha256:97aacf9dbd4bfd829baad6e6309fa6573aaf1be3f6fa735c8ab05e46cecb261c"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==2.0.0"
         },
         "rich": {
             "hashes": [
-                "sha256:2d11b9b8dd03868f09b4fffadc84a6a8cda574e40dc90821bd845720ebb8e89c",
-                "sha256:69cdf53799e63f38b95b9bf9c875f8c90e78dd62b2f00c13a911c7a3b9fa4704"
+                "sha256:8f87bc7ee54675732fa66a05ebfe489e27264caeeff3728c945d25971b6485ec",
+                "sha256:d653d6bccede5844304c605d5aac802c7cf9621efd700b46c7ec2b51ea914898"
             ],
             "markers": "python_full_version >= '3.7.0'",
-            "version": "==13.3.5"
+            "version": "==13.4.2"
         },
         "secretstorage": {
             "hashes": [
                 "sha256:2403533ef369eca6d2ba81718576c5e0f564d5cca1b58f73a8b23e7d4eeebd77",
                 "sha256:f356e6628222568e3af06f2eba8df495efa13b3b63081dafd4f7d9a7b7bc9f99"
             ],
             "markers": "sys_platform == 'linux'",
@@ -1583,19 +1592,19 @@
                 "sha256:76035d5cd1593d38b9056ae12d460eca3aaa34ad05c315b69145e138ba80a745",
                 "sha256:e0480addd11347ba52f762f3c4d8afa3e10ad0affbc53e3ffddc0ca5f27d5778"
             ],
             "version": "==0.3.1"
         },
         "sh": {
             "hashes": [
-                "sha256:ae3258c5249493cebe73cb4e18253a41ed69262484bad36fdb3efcb8ad8870bb",
-                "sha256:b52bf5833ed01c7b5c5fb73a7f71b3d98d48e9b9b8764236237bdc7ecae850fc"
+                "sha256:14265a4cd1622429edcf300292ec98193530fb143fe642b3437024eca9bee8c5",
+                "sha256:a18920f0839991bc9dfddb6dcc006c360b1064ba96257359f0ea356e9fa75a60"
             ],
-            "markers": "sys_platform != 'win32'",
-            "version": "==1.12.14"
+            "markers": "python_version < '4.0' and python_full_version >= '3.8.1'",
+            "version": "==2.0.4"
         },
         "six": {
             "hashes": [
                 "sha256:1e61c37477a1626458e36f7b1d82aa5c9b094fa4802892072e49de9c60c4c926",
                 "sha256:8abb2f1d86890a2dfb989f9a77cfcfd3e47c2a354b01111771326f8aa26e0254"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -1622,19 +1631,19 @@
                 "sha256:97787ff1fa3256a3eef9eda523a63dbf299f7b47e053cfcf684a1c2a8380c912"
             ],
             "index": "pypi",
             "version": "==6.2.1"
         },
         "sphinx-rtd-theme": {
             "hashes": [
-                "sha256:a0d8bd1a2ed52e0b338cbe19c4b2eef3c5e7a048769753dac6a9f059c7b641b8",
-                "sha256:f823f7e71890abe0ac6aaa6013361ea2696fc8d3e1fa798f463e82bdb77eeff2"
+                "sha256:01c5c5a72e2d025bd23d1f06c59a4831b06e6ce6c01fdd5ebfe9986c0a880fc7",
+                "sha256:6a7e7d8af34eb8fc57d52a09c6b6b9c46ff44aea5951bc831eeb9245378f3689"
             ],
             "index": "pypi",
-            "version": "==1.2.0"
+            "version": "==1.2.2"
         },
         "sphinxcontrib-applehelp": {
             "hashes": [
                 "sha256:29d341f67fb0f6f586b23ad80e072c8e6ad0b48417db2bde114a4c9746feb228",
                 "sha256:828f867945bbe39817c210a1abfd1bc4895c8b73fcaade56d45357a348a07d7e"
             ],
             "markers": "python_version >= '3.8'",
@@ -1657,15 +1666,15 @@
             "version": "==2.0.1"
         },
         "sphinxcontrib-jquery": {
             "hashes": [
                 "sha256:1620739f04e36a2c779f1a131a2dfd49b2fd07351bf1968ced074365933abc7a",
                 "sha256:f936030d7d0147dd026a4f2b5a57343d233f1fc7b363f68b3d4f1cb0993878ae"
             ],
-            "markers": "python_version >= '3.1'",
+            "markers": "python_version >= '2.7'",
             "version": "==4.1"
         },
         "sphinxcontrib-jsmath": {
             "hashes": [
                 "sha256:2ec2eaebfb78f3f2078e73666b1415417a116cc848b72e5172e596c871103178",
                 "sha256:a9925e4a4587247ed2191a22df5f6970656cb8ca2bd6284309578f2153e0c4b8"
             ],
@@ -1726,35 +1735,35 @@
                 "sha256:9e102ef5fdd5a20661eb88fad46338806c3bd32cf1db729603fe3697b1bc83c8"
             ],
             "index": "pypi",
             "version": "==4.0.2"
         },
         "typing-extensions": {
             "hashes": [
-                "sha256:5cb5f4a79139d699607b3ef622a1dedafa84e115ab0024e0d9c044a9479ca7cb",
-                "sha256:fb33085c39dd998ac16d1431ebc293a8b3eedd00fd4a32de0ff79002c19511b4"
+                "sha256:88a4153d8505aabbb4e13aacb7c486c2b4a33ca3b3f807914a9b4c844c471c26",
+                "sha256:d91d5919357fe7f681a9f2b5b4cb2a5f1ef0a1e9f59c4d8ff0d3491e05c0ffd5"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==4.5.0"
+            "version": "==4.6.3"
         },
         "urllib3": {
             "hashes": [
-                "sha256:61717a1095d7e155cdb737ac7bb2f4324a858a1e2e6466f6d03ff630ca68d3cc",
-                "sha256:d055c2f9d38dc53c808f6fdc8eab7360b6fdbbde02340ed25cfbcd817c62469e"
+                "sha256:48e7fafa40319d358848e1bc6809b208340fafe2096f1725d05d67443d0483d1",
+                "sha256:bee28b5e56addb8226c96f7f13ac28cb4c301dd5ea8a6ca179c0b9835e032825"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.0.2"
+            "version": "==2.0.3"
         },
         "virtualenv": {
             "hashes": [
-                "sha256:6abec7670e5802a528357fdc75b26b9f57d5d92f29c5462ba0fbe45feacc685e",
-                "sha256:a85caa554ced0c0afbd0d638e7e2d7b5f92d23478d05d17a76daeac8f279f924"
+                "sha256:34da10f14fea9be20e0fd7f04aba9732f84e593dac291b757ce42e3368a39419",
+                "sha256:8ff19a38c1021c742148edc4f81cb43d7f8c6816d2ede2ab72af5b84c749ade1"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==20.23.0"
+            "version": "==20.23.1"
         },
         "webencodings": {
             "hashes": [
                 "sha256:a0af1213f3c2226497a97e2b3aa01a7e4bee4f403f95be16fc9acd2947514a78",
                 "sha256:b36a1c245f2d304965eb4e0a82848379241dc04b865afcc4aab16748587e1923"
             ],
             "version": "==0.5.1"
```

### Comparing `azureenergylabelercli-2.1.0/README.rst` & `azureenergylabelercli-2.1.1/README.rst`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/USAGE.rst` & `azureenergylabelercli-2.1.1/USAGE.rst`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azure_energy_labeler_cli.py` & `azureenergylabelercli-2.1.1/azure_energy_labeler_cli.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/CONTRIBUTING.rst` & `azureenergylabelercli-2.1.1/azureenergylabelercli/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/HISTORY.rst` & `azureenergylabelercli-2.1.1/azureenergylabelercli/HISTORY.rst`

 * *Files 3% similar despite different names*

```diff
@@ -60,7 +60,13 @@
 
 
 2.1.0 (15-05-2023)
 ------------------
 
 * Added option to disable banner and spinner
 * Improved filtering of findings
+
+
+2.1.1 (28-06-2023)
+------------------
+
+* Updated library dependency
```

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/LICENSE` & `azureenergylabelercli-2.1.1/azureenergylabelercli/LICENSE`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/Pipfile` & `azureenergylabelercli-2.1.1/azureenergylabelercli/Pipfile`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,14 @@
 twine = ">=4.0,<5.0"
 coloredlogs = ">=15.0,<16.0"
 emoji = ">=2.0,<3.0"
 toml = ">=0.1,<1.0"
 
 [packages]
 coloredlogs = "~=15.0.1"
-azureenergylabelerlib = "~=3.2.0"
+azureenergylabelerlib = "~=3.2.1"
 yaspin = "~=2.3.0"
 terminaltables = "~=3.1.10"
 art = "~=5.8"
 
 [requires]
 python_version = "3.9"
```

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/Pipfile.lock` & `azureenergylabelercli-2.1.1/azureenergylabelercli/Pipfile.lock`

 * *Files 1% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9778760838878805%*

 * *Differences: {"'_meta'": "{'hash': {'sha256': "*

 * *            "'ca78e85ea73ea3f64c6a1d021f5f0a8b244d235f050aceb29054d202287b325b'}}",*

 * * "'default'": "{'azure-cli-core': {'hashes': "*

 * *              "['sha256:628d1008d80e0459be2a48c5c7c434b713e8e57e5662eacfdd08fe6eb6caa18c', "*

 * *              "'sha256:c8dc31dff20db94f465e3a89ab84edbe28675ba65fc79793673c3d177409fa3f'], "*

 * *              "'version': '==2.49.0'}, 'azure-core': {'hashes': "*

 * *              "['sha256:1b4b19f455eb7b4332c6f92adc2c669353ded07c2722eb436165f0c253737792', "*

 * *  […]*

```diff
@@ -1,11 +1,11 @@
 {
     "_meta": {
         "hash": {
-            "sha256": "9ebe67dc8190e1681e4c386e9b6648d3934e593c5b5a41a3af6565836c604dc0"
+            "sha256": "ca78e85ea73ea3f64c6a1d021f5f0a8b244d235f050aceb29054d202287b325b"
         },
         "pipfile-spec": 6,
         "requires": {
             "python_version": "3.9"
         },
         "sources": [
             {
@@ -44,19 +44,19 @@
                 "sha256:9b02463468fc51c77200dadee970cf02c9576008c4f3b99d7ed02371ec037bd1"
             ],
             "index": "pypi",
             "version": "==5.9"
         },
         "azure-cli-core": {
             "hashes": [
-                "sha256:d70ebe7a59bcb91ab1fdeb5d931a74a04c3def6320bbfdfd506eec18a0de0c3b",
-                "sha256:e9300ca40c4f7cb1c95ac29814045d7faa632f5245a9dae99c7545a743893105"
+                "sha256:628d1008d80e0459be2a48c5c7c434b713e8e57e5662eacfdd08fe6eb6caa18c",
+                "sha256:c8dc31dff20db94f465e3a89ab84edbe28675ba65fc79793673c3d177409fa3f"
             ],
             "markers": "python_full_version >= '3.7.0'",
-            "version": "==2.48.1"
+            "version": "==2.49.0"
         },
         "azure-cli-telemetry": {
             "hashes": [
                 "sha256:502cbd90723a16603822909befd096ca0b1707de1e70cf730e7b4700ddd7a456",
                 "sha256:ca996d162ab689c865f6b60be23b9757c26c3d97928e3319858eea83462df08d"
             ],
             "version": "==1.0.8"
@@ -66,19 +66,19 @@
                 "sha256:4ac0cd3214e36b6a1b6a442686722a5d8cc449603aa833f3f0f40bda836704a3",
                 "sha256:5c12d3dcf4ec20599ca6b0d3e09e86e146353d443e7fcc050c9a19c1f9df20ad"
             ],
             "version": "==1.1.28"
         },
         "azure-core": {
             "hashes": [
-                "sha256:075fe06b74c3007950dd93d49440c2f3430fd9b4a5a2756ec8c79454afc989c6",
-                "sha256:d9664b4bc2675d72fba461a285ac43ae33abb2967014a955bf136d9703a2ab3c"
+                "sha256:1b4b19f455eb7b4332c6f92adc2c669353ded07c2722eb436165f0c253737792",
+                "sha256:5975c20808fa388243f01a8b79021bfbe114f503a27c543f002c5fc8bbdd73dd"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==1.26.4"
+            "version": "==1.27.1"
         },
         "azure-identity": {
             "hashes": [
                 "sha256:bd700cebb80cd9862098587c29d8677e819beca33c62568ced6d5a8e5e332b82",
                 "sha256:c931c27301ffa86b07b4dcf574e29da73e3deba9ab5d1fe4f445bb6a3117e260"
             ],
             "markers": "python_version >= '3.7'",
@@ -90,19 +90,19 @@
                 "sha256:d195208340094f98e5a6661b781cde6f6a051e79ce317caabd8ff97030a9b3ae"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==1.4.0"
         },
         "azure-mgmt-resource": {
             "hashes": [
-                "sha256:b556803a3b8699dbcd1f4c33c8229830225c8c61ba058323d5bae7dc7785d65e",
-                "sha256:e6137abc3244efdecc730feed05b17542ccdaf8735a66b9141ad0a378d872922"
+                "sha256:c2ba6cfd99df95f55f36eadc4245e3dc713257302a1fd0277756d94bd8cb28e0",
+                "sha256:f185eec72bbc39f42bcb83ae6f1bad744f0e3f20a12d9b2b3e70d16c74ad9cc0"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==23.0.0"
+            "version": "==23.0.1"
         },
         "azure-mgmt-resourcegraph": {
             "hashes": [
                 "sha256:0cf55f7ea82dc03e69d0fae0f1606e09b08b80b6ae23bd597d8b62b1ed938ace",
                 "sha256:d25f01dae3897780fb3ddca16d1625b6347c32f1b581c767fba5ef3b24443f11"
             ],
             "markers": "python_version >= '3.7'",
@@ -122,19 +122,19 @@
                 "sha256:91bb192b2a97939c4259c72373bac0f41e30810bbc853d5184f0f45904eacafd"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==12.16.0"
         },
         "azureenergylabelerlib": {
             "hashes": [
-                "sha256:d7197b14424bd3745def7fabb60338891c49f210b79e1a425b912d393f51c389",
-                "sha256:df0fcec873b7978da6bb55af83017ddb40d0d99842f77ac337687fd3338cad13"
+                "sha256:d59c3590b8aab30bad440a220b34bb4ea7bf94ab2504108c91ace2ab00a66951",
+                "sha256:db52c86d7cc165c24ab620488e542f9d834a1a4fb67cf0328f47bebf643a8097"
             ],
             "index": "pypi",
-            "version": "==3.2.0"
+            "version": "==3.2.1"
         },
         "bcrypt": {
             "hashes": [
                 "sha256:089098effa1bc35dc055366740a067a2fc76987e8ec75349eb9484061c54f535",
                 "sha256:08d2947c490093a11416df18043c27abe3921558d2c03e2076ccb28a116cb6d0",
                 "sha256:0eaa47d4661c326bfc9d08d16debbc4edf78778e6aaba29c1bc7ce67214d4410",
                 "sha256:27d375903ac8261cfe4047f6709d16f7d18d39b1ec92aaf72af989552a650ebd",
@@ -157,19 +157,19 @@
                 "sha256:fbdaec13c5105f0c4e5c52614d04f0bca5f5af007910daa8b6b12095edaa67b3"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==4.0.1"
         },
         "cachetools": {
             "hashes": [
-                "sha256:13dfddc7b8df938c21a940dfa6557ce6e94a2f1cdfa58eb90c805721d58f2c14",
-                "sha256:429e1a1e845c008ea6c85aa35d4b98b65d6a9763eeef3e37e92728a12d1de9d4"
+                "sha256:95ef631eeaea14ba2e36f06437f36463aac3a096799e876ee55e5cdccb102590",
+                "sha256:dce83f2d9b4e1f732a8cd44af8e8fab2dbe46201467fc98b3ef8f269092bf62b"
             ],
-            "markers": "python_version ~= '3.7'",
-            "version": "==5.3.0"
+            "markers": "python_version >= '3.7'",
+            "version": "==5.3.1"
         },
         "certifi": {
             "hashes": [
                 "sha256:0f0d56dc5a6ad56fd4ba36484d6cc34451e1c6548c61daad8c320169f91eddc7",
                 "sha256:c6c2e98f5c7869efca1f8916fed228dd91539f9f1b444c314c06eef02980c716"
             ],
             "markers": "python_version >= '3.6'",
@@ -466,19 +466,19 @@
                 "sha256:a392980d2b6cffa644431898be54b0045151319d1e7ec34f0cfed48767dd334f"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==23.1"
         },
         "paramiko": {
             "hashes": [
-                "sha256:6950faca6819acd3219d4ae694a23c7a87ee38d084f70c1724b0c0dbb8b75769",
-                "sha256:f0caa660e797d9cd10db6fc6ae81e2c9b2767af75c3180fcd0e46158cd368d7f"
+                "sha256:93cdce625a8a1dc12204439d45033f3261bdb2c201648cfcdc06f9fd0f94ec29",
+                "sha256:df0f9dd8903bc50f2e10580af687f3015bf592a377cd438d2ec9546467a14eb8"
             ],
             "markers": "python_version >= '3.6'",
-            "version": "==3.1.0"
+            "version": "==3.2.0"
         },
         "pkginfo": {
             "hashes": [
                 "sha256:4b7a555a6d5a22169fcc9cf7bfd78d296b0361adad412a346c1226849af5e546",
                 "sha256:8fd5896e8718a4372f0ea9cc9d96f6417c9b986e23a4d116dda26b62cc29d046"
             ],
             "markers": "python_version >= '3.6'",
@@ -549,19 +549,19 @@
                 "sha256:e46dae94e34b085175f8abb3b0aaa7da40767865ac82c928eeb9e57e1ea8a543"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==1.5.0"
         },
         "pyopenssl": {
             "hashes": [
-                "sha256:841498b9bec61623b1b6c47ebbc02367c07d60e0e195f19790817f10cc8db0b7",
-                "sha256:9e0c526404a210df9d2b18cd33364beadb0dc858a739b885677bc65e105d4a4c"
+                "sha256:24f0dc5227396b3e831f4c7f602b950a5e9833d292c8e4a2e06b709292806ae2",
+                "sha256:276f931f55a452e7dea69c7173e984eb2a4407ce413c918aa34b55f82f9b8bac"
             ],
             "markers": "python_version >= '3.6'",
-            "version": "==23.1.1"
+            "version": "==23.2.0"
         },
         "pysocks": {
             "hashes": [
                 "sha256:08e69f092cc6dbe92a0fdd16eeb9b9ffbc13cadfe5ca4c7bd92ffb078b293299",
                 "sha256:2725bd0a9925919b9b51739eea5f9e2bae91e83288108a9ad338b2e3a4435ee5",
                 "sha256:3f8804571ebe159c380ac6de37643bb4685970655d3bba243530d6558b799aa0"
             ],
@@ -622,19 +622,19 @@
             "version": "==6.0"
         },
         "requests": {
             "extras": [
                 "socks"
             ],
             "hashes": [
-                "sha256:10e94cc4f3121ee6da529d358cdaeaff2f1c409cd377dbc72b825852f2f7e294",
-                "sha256:239d7d4458afcb28a692cdd298d87542235f4ca8d36d03a15bfc128a6559a2f4"
+                "sha256:58cd2187c01e70e6e26505bca751777aa9f2ee0b7f4300988b709f44e013003f",
+                "sha256:942c5a758f98d790eaed1a29cb6eefc7ffb0d1cf7af05c3d2791656dbd6ad1e1"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.30.0"
+            "version": "==2.31.0"
         },
         "requests-oauthlib": {
             "hashes": [
                 "sha256:2577c501a2fb8d05a304c09d090d6e47c306fef15809d102b327cf8364bddab5",
                 "sha256:75beac4a47881eeb94d5ea5d6ad31ef88856affe2332b9aafb52c6452ccf0d7a"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -677,27 +677,27 @@
                 "sha256:e4fdc4179c9e4aab5f674d80f09d76fa436b96fdc698a8505e0a36bf0804a874"
             ],
             "index": "pypi",
             "version": "==3.1.10"
         },
         "typing-extensions": {
             "hashes": [
-                "sha256:5cb5f4a79139d699607b3ef622a1dedafa84e115ab0024e0d9c044a9479ca7cb",
-                "sha256:fb33085c39dd998ac16d1431ebc293a8b3eedd00fd4a32de0ff79002c19511b4"
+                "sha256:88a4153d8505aabbb4e13aacb7c486c2b4a33ca3b3f807914a9b4c844c471c26",
+                "sha256:d91d5919357fe7f681a9f2b5b4cb2a5f1ef0a1e9f59c4d8ff0d3491e05c0ffd5"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==4.5.0"
+            "version": "==4.6.3"
         },
         "urllib3": {
             "hashes": [
-                "sha256:61717a1095d7e155cdb737ac7bb2f4324a858a1e2e6466f6d03ff630ca68d3cc",
-                "sha256:d055c2f9d38dc53c808f6fdc8eab7360b6fdbbde02340ed25cfbcd817c62469e"
+                "sha256:48e7fafa40319d358848e1bc6809b208340fafe2096f1725d05d67443d0483d1",
+                "sha256:bee28b5e56addb8226c96f7f13ac28cb4c301dd5ea8a6ca179c0b9835e032825"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.0.2"
+            "version": "==2.0.3"
         },
         "yaspin": {
             "hashes": [
                 "sha256:17b5548479b3d5b30adec7a87ffcdcddb403d14a2bb86fbcee97f37951e13427",
                 "sha256:547afd1a9700ac3a29a9f5591c70343bef186ed5dfb5e545a9bb0c77e561a1c9"
             ],
             "index": "pypi",
@@ -751,19 +751,19 @@
                 "sha256:33c16e3353dbd13028ab4799a0f89a83f113405c766e9c122df8a06f5b85b3f4"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==6.0.0"
         },
         "cachetools": {
             "hashes": [
-                "sha256:13dfddc7b8df938c21a940dfa6557ce6e94a2f1cdfa58eb90c805721d58f2c14",
-                "sha256:429e1a1e845c008ea6c85aa35d4b98b65d6a9763eeef3e37e92728a12d1de9d4"
+                "sha256:95ef631eeaea14ba2e36f06437f36463aac3a096799e876ee55e5cdccb102590",
+                "sha256:dce83f2d9b4e1f732a8cd44af8e8fab2dbe46201467fc98b3ef8f269092bf62b"
             ],
-            "markers": "python_version ~= '3.7'",
-            "version": "==5.3.0"
+            "markers": "python_version >= '3.7'",
+            "version": "==5.3.1"
         },
         "certifi": {
             "hashes": [
                 "sha256:0f0d56dc5a6ad56fd4ba36484d6cc34451e1c6548c61daad8c320169f91eddc7",
                 "sha256:c6c2e98f5c7869efca1f8916fed228dd91539f9f1b444c314c06eef02980c716"
             ],
             "markers": "python_version >= '3.6'",
@@ -941,68 +941,77 @@
                 "sha256:7c991aa71a4577af2f82600d8f8f3a89f936baeaf9b50a9c197da014e5bf16b0"
             ],
             "index": "pypi",
             "version": "==15.0.1"
         },
         "coverage": {
             "hashes": [
-                "sha256:0342a28617e63ad15d96dca0f7ae9479a37b7d8a295f749c14f3436ea59fdcb3",
-                "sha256:066b44897c493e0dcbc9e6a6d9f8bbb6607ef82367cf6810d387c09f0cd4fe9a",
-                "sha256:10b15394c13544fce02382360cab54e51a9e0fd1bd61ae9ce012c0d1e103c813",
-                "sha256:12580845917b1e59f8a1c2ffa6af6d0908cb39220f3019e36c110c943dc875b0",
-                "sha256:156192e5fd3dbbcb11cd777cc469cf010a294f4c736a2b2c891c77618cb1379a",
-                "sha256:1637253b11a18f453e34013c665d8bf15904c9e3c44fbda34c643fbdc9d452cd",
-                "sha256:292300f76440651529b8ceec283a9370532f4ecba9ad67d120617021bb5ef139",
-                "sha256:30dcaf05adfa69c2a7b9f7dfd9f60bc8e36b282d7ed25c308ef9e114de7fc23b",
-                "sha256:338aa9d9883aaaad53695cb14ccdeb36d4060485bb9388446330bef9c361c252",
-                "sha256:373ea34dca98f2fdb3e5cb33d83b6d801007a8074f992b80311fc589d3e6b790",
-                "sha256:38c0a497a000d50491055805313ed83ddba069353d102ece8aef5d11b5faf045",
-                "sha256:40cc0f91c6cde033da493227797be2826cbf8f388eaa36a0271a97a332bfd7ce",
-                "sha256:4436cc9ba5414c2c998eaedee5343f49c02ca93b21769c5fdfa4f9d799e84200",
-                "sha256:509ecd8334c380000d259dc66feb191dd0a93b21f2453faa75f7f9cdcefc0718",
-                "sha256:5c587f52c81211d4530fa6857884d37f514bcf9453bdeee0ff93eaaf906a5c1b",
-                "sha256:5f3671662dc4b422b15776cdca89c041a6349b4864a43aa2350b6b0b03bbcc7f",
-                "sha256:6599bf92f33ab041e36e06d25890afbdf12078aacfe1f1d08c713906e49a3fe5",
-                "sha256:6e8a95f243d01ba572341c52f89f3acb98a3b6d1d5d830efba86033dd3687ade",
-                "sha256:706ec567267c96717ab9363904d846ec009a48d5f832140b6ad08aad3791b1f5",
-                "sha256:780551e47d62095e088f251f5db428473c26db7829884323e56d9c0c3118791a",
-                "sha256:7ff8f3fb38233035028dbc93715551d81eadc110199e14bbbfa01c5c4a43f8d8",
-                "sha256:828189fcdda99aae0d6bf718ea766b2e715eabc1868670a0a07bf8404bf58c33",
-                "sha256:857abe2fa6a4973f8663e039ead8d22215d31db613ace76e4a98f52ec919068e",
-                "sha256:883123d0bbe1c136f76b56276074b0c79b5817dd4238097ffa64ac67257f4b6c",
-                "sha256:8877d9b437b35a85c18e3c6499b23674684bf690f5d96c1006a1ef61f9fdf0f3",
-                "sha256:8e575a59315a91ccd00c7757127f6b2488c2f914096077c745c2f1ba5b8c0969",
-                "sha256:97072cc90f1009386c8a5b7de9d4fc1a9f91ba5ef2146c55c1f005e7b5c5e068",
-                "sha256:9a22cbb5ede6fade0482111fa7f01115ff04039795d7092ed0db43522431b4f2",
-                "sha256:a063aad9f7b4c9f9da7b2550eae0a582ffc7623dca1c925e50c3fbde7a579771",
-                "sha256:a08c7401d0b24e8c2982f4e307124b671c6736d40d1c39e09d7a8687bddf83ed",
-                "sha256:a0b273fe6dc655b110e8dc89b8ec7f1a778d78c9fd9b4bda7c384c8906072212",
-                "sha256:a2b3b05e22a77bb0ae1a3125126a4e08535961c946b62f30985535ed40e26614",
-                "sha256:a66e055254a26c82aead7ff420d9fa8dc2da10c82679ea850d8feebf11074d88",
-                "sha256:aa387bd7489f3e1787ff82068b295bcaafbf6f79c3dad3cbc82ef88ce3f48ad3",
-                "sha256:ae453f655640157d76209f42c62c64c4d4f2c7f97256d3567e3b439bd5c9b06c",
-                "sha256:b5016e331b75310610c2cf955d9f58a9749943ed5f7b8cfc0bb89c6134ab0a84",
-                "sha256:b9a4ee55174b04f6af539218f9f8083140f61a46eabcaa4234f3c2a452c4ed11",
-                "sha256:bd3b4b8175c1db502adf209d06136c000df4d245105c8839e9d0be71c94aefe1",
-                "sha256:bebea5f5ed41f618797ce3ffb4606c64a5de92e9c3f26d26c2e0aae292f015c1",
-                "sha256:c10fbc8a64aa0f3ed136b0b086b6b577bc64d67d5581acd7cc129af52654384e",
-                "sha256:c2c41c1b1866b670573657d584de413df701f482574bad7e28214a2362cb1fd1",
-                "sha256:cf97ed82ca986e5c637ea286ba2793c85325b30f869bf64d3009ccc1a31ae3fd",
-                "sha256:d1f25ee9de21a39b3a8516f2c5feb8de248f17da7eead089c2e04aa097936b47",
-                "sha256:d2fbc2a127e857d2f8898aaabcc34c37771bf78a4d5e17d3e1f5c30cd0cbc62a",
-                "sha256:dc945064a8783b86fcce9a0a705abd7db2117d95e340df8a4333f00be5efb64c",
-                "sha256:ddc5a54edb653e9e215f75de377354e2455376f416c4378e1d43b08ec50acc31",
-                "sha256:e8834e5f17d89e05697c3c043d3e58a8b19682bf365048837383abfe39adaed5",
-                "sha256:ef9659d1cda9ce9ac9585c045aaa1e59223b143f2407db0eaee0b61a4f266fb6",
-                "sha256:f6f5cab2d7f0c12f8187a376cc6582c477d2df91d63f75341307fcdcb5d60303",
-                "sha256:f81c9b4bd8aa747d417407a7f6f0b1469a43b36a85748145e144ac4e8d303cb5",
-                "sha256:f99ef080288f09ffc687423b8d60978cf3a465d3f404a18d1a05474bd8575a47"
+                "sha256:06a9a2be0b5b576c3f18f1a241f0473575c4a26021b52b2a85263a00f034d51f",
+                "sha256:06fb182e69f33f6cd1d39a6c597294cff3143554b64b9825d1dc69d18cc2fff2",
+                "sha256:0a5f9e1dbd7fbe30196578ca36f3fba75376fb99888c395c5880b355e2875f8a",
+                "sha256:0e1f928eaf5469c11e886fe0885ad2bf1ec606434e79842a879277895a50942a",
+                "sha256:171717c7cb6b453aebac9a2ef603699da237f341b38eebfee9be75d27dc38e01",
+                "sha256:1e9d683426464e4a252bf70c3498756055016f99ddaec3774bf368e76bbe02b6",
+                "sha256:201e7389591af40950a6480bd9edfa8ed04346ff80002cec1a66cac4549c1ad7",
+                "sha256:245167dd26180ab4c91d5e1496a30be4cd721a5cf2abf52974f965f10f11419f",
+                "sha256:2aee274c46590717f38ae5e4650988d1af340fe06167546cc32fe2f58ed05b02",
+                "sha256:2e07b54284e381531c87f785f613b833569c14ecacdcb85d56b25c4622c16c3c",
+                "sha256:31563e97dae5598556600466ad9beea39fb04e0229e61c12eaa206e0aa202063",
+                "sha256:33d6d3ea29d5b3a1a632b3c4e4f4ecae24ef170b0b9ee493883f2df10039959a",
+                "sha256:3d376df58cc111dc8e21e3b6e24606b5bb5dee6024f46a5abca99124b2229ef5",
+                "sha256:419bfd2caae268623dd469eff96d510a920c90928b60f2073d79f8fe2bbc5959",
+                "sha256:48c19d2159d433ccc99e729ceae7d5293fbffa0bdb94952d3579983d1c8c9d97",
+                "sha256:49969a9f7ffa086d973d91cec8d2e31080436ef0fb4a359cae927e742abfaaa6",
+                "sha256:52edc1a60c0d34afa421c9c37078817b2e67a392cab17d97283b64c5833f427f",
+                "sha256:537891ae8ce59ef63d0123f7ac9e2ae0fc8b72c7ccbe5296fec45fd68967b6c9",
+                "sha256:54b896376ab563bd38453cecb813c295cf347cf5906e8b41d340b0321a5433e5",
+                "sha256:58c2ccc2f00ecb51253cbe5d8d7122a34590fac9646a960d1430d5b15321d95f",
+                "sha256:5b7540161790b2f28143191f5f8ec02fb132660ff175b7747b95dcb77ac26562",
+                "sha256:5baa06420f837184130752b7c5ea0808762083bf3487b5038d68b012e5937dbe",
+                "sha256:5e330fc79bd7207e46c7d7fd2bb4af2963f5f635703925543a70b99574b0fea9",
+                "sha256:61b9a528fb348373c433e8966535074b802c7a5d7f23c4f421e6c6e2f1697a6f",
+                "sha256:63426706118b7f5cf6bb6c895dc215d8a418d5952544042c8a2d9fe87fcf09cb",
+                "sha256:6d040ef7c9859bb11dfeb056ff5b3872436e3b5e401817d87a31e1750b9ae2fb",
+                "sha256:6f48351d66575f535669306aa7d6d6f71bc43372473b54a832222803eb956fd1",
+                "sha256:7ee7d9d4822c8acc74a5e26c50604dff824710bc8de424904c0982e25c39c6cb",
+                "sha256:81c13a1fc7468c40f13420732805a4c38a105d89848b7c10af65a90beff25250",
+                "sha256:8d13c64ee2d33eccf7437961b6ea7ad8673e2be040b4f7fd4fd4d4d28d9ccb1e",
+                "sha256:8de8bb0e5ad103888d65abef8bca41ab93721647590a3f740100cd65c3b00511",
+                "sha256:8fa03bce9bfbeeef9f3b160a8bed39a221d82308b4152b27d82d8daa7041fee5",
+                "sha256:924d94291ca674905fe9481f12294eb11f2d3d3fd1adb20314ba89e94f44ed59",
+                "sha256:975d70ab7e3c80a3fe86001d8751f6778905ec723f5b110aed1e450da9d4b7f2",
+                "sha256:976b9c42fb2a43ebf304fa7d4a310e5f16cc99992f33eced91ef6f908bd8f33d",
+                "sha256:9e31cb64d7de6b6f09702bb27c02d1904b3aebfca610c12772452c4e6c21a0d3",
+                "sha256:a342242fe22407f3c17f4b499276a02b01e80f861f1682ad1d95b04018e0c0d4",
+                "sha256:a3d33a6b3eae87ceaefa91ffdc130b5e8536182cd6dfdbfc1aa56b46ff8c86de",
+                "sha256:a895fcc7b15c3fc72beb43cdcbdf0ddb7d2ebc959edac9cef390b0d14f39f8a9",
+                "sha256:afb17f84d56068a7c29f5fa37bfd38d5aba69e3304af08ee94da8ed5b0865833",
+                "sha256:b1c546aca0ca4d028901d825015dc8e4d56aac4b541877690eb76490f1dc8ed0",
+                "sha256:b29019c76039dc3c0fd815c41392a044ce555d9bcdd38b0fb60fb4cd8e475ba9",
+                "sha256:b46517c02ccd08092f4fa99f24c3b83d8f92f739b4657b0f146246a0ca6a831d",
+                "sha256:b7aa5f8a41217360e600da646004f878250a0d6738bcdc11a0a39928d7dc2050",
+                "sha256:b7b4c971f05e6ae490fef852c218b0e79d4e52f79ef0c8475566584a8fb3e01d",
+                "sha256:ba90a9563ba44a72fda2e85302c3abc71c5589cea608ca16c22b9804262aaeb6",
+                "sha256:cb017fd1b2603ef59e374ba2063f593abe0fc45f2ad9abdde5b4d83bd922a353",
+                "sha256:d22656368f0e6189e24722214ed8d66b8022db19d182927b9a248a2a8a2f67eb",
+                "sha256:d2c2db7fd82e9b72937969bceac4d6ca89660db0a0967614ce2481e81a0b771e",
+                "sha256:d39b5b4f2a66ccae8b7263ac3c8170994b65266797fb96cbbfd3fb5b23921db8",
+                "sha256:d62a5c7dad11015c66fbb9d881bc4caa5b12f16292f857842d9d1871595f4495",
+                "sha256:e7d9405291c6928619403db1d10bd07888888ec1abcbd9748fdaa971d7d661b2",
+                "sha256:e84606b74eb7de6ff581a7915e2dab7a28a0517fbe1c9239eb227e1354064dcd",
+                "sha256:eb393e5ebc85245347950143969b241d08b52b88a3dc39479822e073a1a8eb27",
+                "sha256:ebba1cd308ef115925421d3e6a586e655ca5a77b5bf41e02eb0e4562a111f2d1",
+                "sha256:ee57190f24fba796e36bb6d3aa8a8783c643d8fa9760c89f7a98ab5455fbf818",
+                "sha256:f2f67fe12b22cd130d34d0ef79206061bfb5eda52feb6ce0dba0644e20a03cf4",
+                "sha256:f6951407391b639504e3b3be51b7ba5f3528adbf1a8ac3302b687ecababf929e",
+                "sha256:f75f7168ab25dd93110c8a8117a22450c19976afbc44234cbf71481094c1b850",
+                "sha256:fdec9e8cbf13a5bf63290fc6013d216a4c7232efb51548594ca3631a7f13c3a3"
             ],
             "index": "pypi",
-            "version": "==7.2.5"
+            "version": "==7.2.7"
         },
         "cryptography": {
             "hashes": [
                 "sha256:05dc219433b14046c476f6f09d7636b92a1c3e5808b9a6536adf4932b3b2c440",
                 "sha256:0dcca15d3a19a66e63662dc8d30f8036b07be851a8680eda92d079868f106288",
                 "sha256:142bae539ef28a1c76794cca7f49729e7c54423f615cfd9b0b1fa90ebe53244b",
                 "sha256:3daf9b114213f8ba460b829a02896789751626a2a4e7a43a28ee77c04b5e4958",
@@ -1053,26 +1062,26 @@
                 "sha256:28323cbfc9352139fdd3d316fa17f325cc0e9ac74438cbba51d70f9b48f86c3a",
                 "sha256:51f54c0fd886fa3854387f354b19f429d38c04f984f38bc572558b703c0542a6"
             ],
             "version": "==0.2.1"
         },
         "emoji": {
             "hashes": [
-                "sha256:a2986c21e4aba6b9870df40ef487a17be863cb7778dcf1c01e25917b7cd210bb"
+                "sha256:39ad95c9ba270cdfbd141d20c2ebcfc4e295d010b605de66908a098a3ba63a3c"
             ],
             "index": "pypi",
-            "version": "==2.2.0"
+            "version": "==2.6.0"
         },
         "filelock": {
             "hashes": [
-                "sha256:ad98852315c2ab702aeb628412cbf7e95b7ce8c3bf9565670b4eaecf1db370a9",
-                "sha256:fc03ae43288c013d2ea83c8597001b1129db351aad9c57fe2409327916b8e718"
+                "sha256:002740518d8aa59a26b0c76e10fb8c6e15eae825d34b6fdf670333fd7b938d81",
+                "sha256:cbb791cdea2a72f23da6ac5b5269ab0a0d161e9ef0100e653b69049a7706d1ec"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==3.12.0"
+            "version": "==3.12.2"
         },
         "flake8": {
             "hashes": [
                 "sha256:6fbe320aad8d6b95cec8b8e47bc933004678dc63095be98528b7bdd2a9f510db",
                 "sha256:7a1cf6b73744f5806ab95e526f6f0d8c01c66d7bbe349562d22dfca20610b248"
             ],
             "markers": "python_full_version >= '3.6.1'",
@@ -1099,19 +1108,19 @@
                 "sha256:f04893614f6aa713a60cbbe1e6a97403ef633103cdd0ef5eb6efe0deb98dbe8d"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==3.1.31"
         },
         "gitwrapperlib": {
             "hashes": [
-                "sha256:3174bcc0de3fa70f78067cb2bc60a5c9820442d78594fb345bdd56740f64073a",
-                "sha256:97ff470337459649cc3cce39a79622bf36679ec8abc03509d3e1afb1d5360de9"
+                "sha256:2f1c5e0fc69168dde3cd141f56b7714c6841ebe886956c1cd302c5867b640db7",
+                "sha256:90b33ad4568e5ce056d0058b98dd850a6dee2473d3bfc115f35c721e62f95078"
             ],
             "index": "pypi",
-            "version": "==1.0.0"
+            "version": "==1.0.3"
         },
         "humanfriendly": {
             "hashes": [
                 "sha256:1697e1a8a8f550fd43c2865cd84542fc175a61dcb779b6fee18cf6b6ccba1477",
                 "sha256:6b0b831ce8f15f7300721aa49829fc4e83921a9a301cc7f606be6686a2288ddc"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3, 3.4'",
@@ -1131,19 +1140,19 @@
                 "sha256:69150444affb9cb0d5cc5a92b3676f0b2fb7cd9ae39e947a5e11a36b4497cd4a"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
             "version": "==1.4.1"
         },
         "importlib-metadata": {
             "hashes": [
-                "sha256:43dd286a2cd8995d5eaef7fee2066340423b818ed3fd70adf0bad5f1fac53fed",
-                "sha256:92501cdf9cc66ebd3e612f1b4f0c0765dfa42f0fa38ffb319b6bd84dd675d705"
+                "sha256:1aaf550d4f73e5d6783e7acb77aec43d49da8017410afae93822cc9cca98c4d4",
+                "sha256:cb52082e659e97afc5dac71e79de97d8681de3aa07ff18578330904a9d18e5b5"
             ],
             "markers": "python_version < '3.10'",
-            "version": "==6.6.0"
+            "version": "==6.7.0"
         },
         "isort": {
             "hashes": [
                 "sha256:8bef7dde241278824a6d83f44a544709b065191b95b6e50894bdc722fcba0504",
                 "sha256:f84c2818376e66cf843d497486ea8fed8700b340f308f076c6fb1229dff318b6"
             ],
             "markers": "python_full_version >= '3.8.0'",
@@ -1171,19 +1180,19 @@
                 "sha256:6088930bfe239f0e6710546ab9c19c9ef35e29792895fed6e6e31a023a182a61"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==3.1.2"
         },
         "keyring": {
             "hashes": [
-                "sha256:771ed2a91909389ed6148631de678f82ddc73737d85a927f382a8a1b157898cd",
-                "sha256:ba2e15a9b35e21908d0aaf4e0a47acc52d6ae33444df0da2b49d41a46ef6d678"
+                "sha256:4901caaf597bfd3bbd78c9a0c7c4c29fcd8310dab2cffefe749e916b6527acd6",
+                "sha256:ca0746a19ec421219f4d713f848fa297a661a8a8c1504867e55bfb5e09091509"
             ],
-            "markers": "python_version >= '3.7'",
-            "version": "==23.13.1"
+            "markers": "python_version >= '3.8'",
+            "version": "==24.2.0"
         },
         "lazy-object-proxy": {
             "hashes": [
                 "sha256:09763491ce220c0299688940f8dc2c5d05fd1f45af1e42e636b2e8b2303e4382",
                 "sha256:0a891e4e41b54fd5b8313b96399f8b0e173bbbfc03c7631f01efbe29bb0bcf82",
                 "sha256:189bbd5d41ae7a498397287c408617fe5c48633e7755287b21d741f7db2706a9",
                 "sha256:18b78ec83edbbeb69efdc0e9c1cb41a3b1b1ed11ddd8ded602464c3fc6020494",
@@ -1221,75 +1230,75 @@
                 "sha256:f699ac1c768270c9e384e4cbd268d6e67aebcfae6cd623b4d7c3bfde5a35db59"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==1.9.0"
         },
         "markdown-it-py": {
             "hashes": [
-                "sha256:5a35f8d1870171d9acc47b99612dc146129b631baf04970128b568f190d0cc30",
-                "sha256:7c9a5e412688bc771c67432cbfebcdd686c93ce6484913dccf06cb5a0bea35a1"
+                "sha256:355216845c60bd96232cd8d8c40e8f9765cc86f46880e43a8fd22dc1a1a8cab1",
+                "sha256:e3f60a94fa066dc52ec76661e37c851cb232d92f9886b15cb560aaada2df8feb"
             ],
-            "markers": "python_version >= '3.7'",
-            "version": "==2.2.0"
+            "markers": "python_version >= '3.8'",
+            "version": "==3.0.0"
         },
         "markupsafe": {
             "hashes": [
-                "sha256:0576fe974b40a400449768941d5d0858cc624e3249dfd1e0c33674e5c7ca7aed",
-                "sha256:085fd3201e7b12809f9e6e9bc1e5c96a368c8523fad5afb02afe3c051ae4afcc",
-                "sha256:090376d812fb6ac5f171e5938e82e7f2d7adc2b629101cec0db8b267815c85e2",
-                "sha256:0b462104ba25f1ac006fdab8b6a01ebbfbce9ed37fd37fd4acd70c67c973e460",
-                "sha256:137678c63c977754abe9086a3ec011e8fd985ab90631145dfb9294ad09c102a7",
-                "sha256:1bea30e9bf331f3fef67e0a3877b2288593c98a21ccb2cf29b74c581a4eb3af0",
-                "sha256:22152d00bf4a9c7c83960521fc558f55a1adbc0631fbb00a9471e097b19d72e1",
-                "sha256:22731d79ed2eb25059ae3df1dfc9cb1546691cc41f4e3130fe6bfbc3ecbbecfa",
-                "sha256:2298c859cfc5463f1b64bd55cb3e602528db6fa0f3cfd568d3605c50678f8f03",
-                "sha256:28057e985dace2f478e042eaa15606c7efccb700797660629da387eb289b9323",
-                "sha256:2e7821bffe00aa6bd07a23913b7f4e01328c3d5cc0b40b36c0bd81d362faeb65",
-                "sha256:2ec4f2d48ae59bbb9d1f9d7efb9236ab81429a764dedca114f5fdabbc3788013",
-                "sha256:340bea174e9761308703ae988e982005aedf427de816d1afe98147668cc03036",
-                "sha256:40627dcf047dadb22cd25ea7ecfe9cbf3bbbad0482ee5920b582f3809c97654f",
-                "sha256:40dfd3fefbef579ee058f139733ac336312663c6706d1163b82b3003fb1925c4",
-                "sha256:4cf06cdc1dda95223e9d2d3c58d3b178aa5dacb35ee7e3bbac10e4e1faacb419",
-                "sha256:50c42830a633fa0cf9e7d27664637532791bfc31c731a87b202d2d8ac40c3ea2",
-                "sha256:55f44b440d491028addb3b88f72207d71eeebfb7b5dbf0643f7c023ae1fba619",
-                "sha256:608e7073dfa9e38a85d38474c082d4281f4ce276ac0010224eaba11e929dd53a",
-                "sha256:63ba06c9941e46fa389d389644e2d8225e0e3e5ebcc4ff1ea8506dce646f8c8a",
-                "sha256:65608c35bfb8a76763f37036547f7adfd09270fbdbf96608be2bead319728fcd",
-                "sha256:665a36ae6f8f20a4676b53224e33d456a6f5a72657d9c83c2aa00765072f31f7",
-                "sha256:6d6607f98fcf17e534162f0709aaad3ab7a96032723d8ac8750ffe17ae5a0666",
-                "sha256:7313ce6a199651c4ed9d7e4cfb4aa56fe923b1adf9af3b420ee14e6d9a73df65",
-                "sha256:7668b52e102d0ed87cb082380a7e2e1e78737ddecdde129acadb0eccc5423859",
-                "sha256:7df70907e00c970c60b9ef2938d894a9381f38e6b9db73c5be35e59d92e06625",
-                "sha256:7e007132af78ea9df29495dbf7b5824cb71648d7133cf7848a2a5dd00d36f9ff",
-                "sha256:835fb5e38fd89328e9c81067fd642b3593c33e1e17e2fdbf77f5676abb14a156",
-                "sha256:8bca7e26c1dd751236cfb0c6c72d4ad61d986e9a41bbf76cb445f69488b2a2bd",
-                "sha256:8db032bf0ce9022a8e41a22598eefc802314e81b879ae093f36ce9ddf39ab1ba",
-                "sha256:99625a92da8229df6d44335e6fcc558a5037dd0a760e11d84be2260e6f37002f",
-                "sha256:9cad97ab29dfc3f0249b483412c85c8ef4766d96cdf9dcf5a1e3caa3f3661cf1",
-                "sha256:a4abaec6ca3ad8660690236d11bfe28dfd707778e2442b45addd2f086d6ef094",
-                "sha256:a6e40afa7f45939ca356f348c8e23048e02cb109ced1eb8420961b2f40fb373a",
-                "sha256:a6f2fcca746e8d5910e18782f976489939d54a91f9411c32051b4aab2bd7c513",
-                "sha256:a806db027852538d2ad7555b203300173dd1b77ba116de92da9afbc3a3be3eed",
-                "sha256:abcabc8c2b26036d62d4c746381a6f7cf60aafcc653198ad678306986b09450d",
-                "sha256:b8526c6d437855442cdd3d87eede9c425c4445ea011ca38d937db299382e6fa3",
-                "sha256:bb06feb762bade6bf3c8b844462274db0c76acc95c52abe8dbed28ae3d44a147",
-                "sha256:c0a33bc9f02c2b17c3ea382f91b4db0e6cde90b63b296422a939886a7a80de1c",
-                "sha256:c4a549890a45f57f1ebf99c067a4ad0cb423a05544accaf2b065246827ed9603",
-                "sha256:ca244fa73f50a800cf8c3ebf7fd93149ec37f5cb9596aa8873ae2c1d23498601",
-                "sha256:cf877ab4ed6e302ec1d04952ca358b381a882fbd9d1b07cccbfd61783561f98a",
-                "sha256:d9d971ec1e79906046aa3ca266de79eac42f1dbf3612a05dc9368125952bd1a1",
-                "sha256:da25303d91526aac3672ee6d49a2f3db2d9502a4a60b55519feb1a4c7714e07d",
-                "sha256:e55e40ff0cc8cc5c07996915ad367fa47da6b3fc091fdadca7f5403239c5fec3",
-                "sha256:f03a532d7dee1bed20bc4884194a16160a2de9ffc6354b3878ec9682bb623c54",
-                "sha256:f1cd098434e83e656abf198f103a8207a8187c0fc110306691a2e94a78d0abb2",
-                "sha256:f2bfb563d0211ce16b63c7cb9395d2c682a23187f54c3d79bfec33e6705473c6",
-                "sha256:f8ffb705ffcf5ddd0e80b65ddf7bed7ee4f5a441ea7d3419e861a12eaf41af58"
+                "sha256:05fb21170423db021895e1ea1e1f3ab3adb85d1c2333cbc2310f2a26bc77272e",
+                "sha256:0a4e4a1aff6c7ac4cd55792abf96c915634c2b97e3cc1c7129578aa68ebd754e",
+                "sha256:10bbfe99883db80bdbaff2dcf681dfc6533a614f700da1287707e8a5d78a8431",
+                "sha256:134da1eca9ec0ae528110ccc9e48041e0828d79f24121a1a146161103c76e686",
+                "sha256:1577735524cdad32f9f694208aa75e422adba74f1baee7551620e43a3141f559",
+                "sha256:1b40069d487e7edb2676d3fbdb2b0829ffa2cd63a2ec26c4938b2d34391b4ecc",
+                "sha256:282c2cb35b5b673bbcadb33a585408104df04f14b2d9b01d4c345a3b92861c2c",
+                "sha256:2c1b19b3aaacc6e57b7e25710ff571c24d6c3613a45e905b1fde04d691b98ee0",
+                "sha256:2ef12179d3a291be237280175b542c07a36e7f60718296278d8593d21ca937d4",
+                "sha256:338ae27d6b8745585f87218a3f23f1512dbf52c26c28e322dbe54bcede54ccb9",
+                "sha256:3c0fae6c3be832a0a0473ac912810b2877c8cb9d76ca48de1ed31e1c68386575",
+                "sha256:3fd4abcb888d15a94f32b75d8fd18ee162ca0c064f35b11134be77050296d6ba",
+                "sha256:42de32b22b6b804f42c5d98be4f7e5e977ecdd9ee9b660fda1a3edf03b11792d",
+                "sha256:504b320cd4b7eff6f968eddf81127112db685e81f7e36e75f9f84f0df46041c3",
+                "sha256:525808b8019e36eb524b8c68acdd63a37e75714eac50e988180b169d64480a00",
+                "sha256:56d9f2ecac662ca1611d183feb03a3fa4406469dafe241673d521dd5ae92a155",
+                "sha256:5bbe06f8eeafd38e5d0a4894ffec89378b6c6a625ff57e3028921f8ff59318ac",
+                "sha256:65c1a9bcdadc6c28eecee2c119465aebff8f7a584dd719facdd9e825ec61ab52",
+                "sha256:68e78619a61ecf91e76aa3e6e8e33fc4894a2bebe93410754bd28fce0a8a4f9f",
+                "sha256:69c0f17e9f5a7afdf2cc9fb2d1ce6aabdb3bafb7f38017c0b77862bcec2bbad8",
+                "sha256:6b2b56950d93e41f33b4223ead100ea0fe11f8e6ee5f641eb753ce4b77a7042b",
+                "sha256:787003c0ddb00500e49a10f2844fac87aa6ce977b90b0feaaf9de23c22508b24",
+                "sha256:7ef3cb2ebbf91e330e3bb937efada0edd9003683db6b57bb108c4001f37a02ea",
+                "sha256:8023faf4e01efadfa183e863fefde0046de576c6f14659e8782065bcece22198",
+                "sha256:8758846a7e80910096950b67071243da3e5a20ed2546e6392603c096778d48e0",
+                "sha256:8afafd99945ead6e075b973fefa56379c5b5c53fd8937dad92c662da5d8fd5ee",
+                "sha256:8c41976a29d078bb235fea9b2ecd3da465df42a562910f9022f1a03107bd02be",
+                "sha256:8e254ae696c88d98da6555f5ace2279cf7cd5b3f52be2b5cf97feafe883b58d2",
+                "sha256:9402b03f1a1b4dc4c19845e5c749e3ab82d5078d16a2a4c2cd2df62d57bb0707",
+                "sha256:962f82a3086483f5e5f64dbad880d31038b698494799b097bc59c2edf392fce6",
+                "sha256:9dcdfd0eaf283af041973bff14a2e143b8bd64e069f4c383416ecd79a81aab58",
+                "sha256:aa7bd130efab1c280bed0f45501b7c8795f9fdbeb02e965371bbef3523627779",
+                "sha256:ab4a0df41e7c16a1392727727e7998a467472d0ad65f3ad5e6e765015df08636",
+                "sha256:ad9e82fb8f09ade1c3e1b996a6337afac2b8b9e365f926f5a61aacc71adc5b3c",
+                "sha256:af598ed32d6ae86f1b747b82783958b1a4ab8f617b06fe68795c7f026abbdcad",
+                "sha256:b076b6226fb84157e3f7c971a47ff3a679d837cf338547532ab866c57930dbee",
+                "sha256:b7ff0f54cb4ff66dd38bebd335a38e2c22c41a8ee45aa608efc890ac3e3931bc",
+                "sha256:bfce63a9e7834b12b87c64d6b155fdd9b3b96191b6bd334bf37db7ff1fe457f2",
+                "sha256:c011a4149cfbcf9f03994ec2edffcb8b1dc2d2aede7ca243746df97a5d41ce48",
+                "sha256:c9c804664ebe8f83a211cace637506669e7890fec1b4195b505c214e50dd4eb7",
+                "sha256:ca379055a47383d02a5400cb0d110cef0a776fc644cda797db0c5696cfd7e18e",
+                "sha256:cb0932dc158471523c9637e807d9bfb93e06a95cbf010f1a38b98623b929ef2b",
+                "sha256:cd0f502fe016460680cd20aaa5a76d241d6f35a1c3350c474bac1273803893fa",
+                "sha256:ceb01949af7121f9fc39f7d27f91be8546f3fb112c608bc4029aef0bab86a2a5",
+                "sha256:d080e0a5eb2529460b30190fcfcc4199bd7f827663f858a226a81bc27beaa97e",
+                "sha256:dd15ff04ffd7e05ffcb7fe79f1b98041b8ea30ae9234aed2a9168b5797c3effb",
+                "sha256:df0be2b576a7abbf737b1575f048c23fb1d769f267ec4358296f31c2479db8f9",
+                "sha256:e09031c87a1e51556fdcb46e5bd4f59dfb743061cf93c4d6831bf894f125eb57",
+                "sha256:e4dd52d80b8c83fdce44e12478ad2e85c64ea965e75d66dbeafb0a3e77308fcc",
+                "sha256:fec21693218efe39aa7f8599346e90c705afa52c5b31ae019b2e57e8f6542bb2"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.1.2"
+            "version": "==2.1.3"
         },
         "mccabe": {
             "hashes": [
                 "sha256:348e0240c33b60bbdf4e523192ef919f28cb2c3d7d5c7794f74009290f236325",
                 "sha256:6c2d30ab6be0e4a46919781807b4f0d834ebdd6c6e3dca0bda5a15f863427b6e"
             ],
             "markers": "python_version >= '3.6'",
@@ -1349,27 +1358,27 @@
                 "sha256:8fd5896e8718a4372f0ea9cc9d96f6417c9b986e23a4d116dda26b62cc29d046"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==1.9.6"
         },
         "platformdirs": {
             "hashes": [
-                "sha256:412dae91f52a6f84830f39a8078cecd0e866cb72294a5c66808e74d5e88d251f",
-                "sha256:e2378146f1964972c03c085bb5662ae80b2b8c06226c54b2ff4aa9483e8a13a5"
+                "sha256:b0cabcb11063d21a0b261d557acb0a9d2126350e63b70cdf7db6347baea456dc",
+                "sha256:ca9ed98ce73076ba72e092b23d3c93ea6c4e186b3f1c3dad6edd98ff6ffcca2e"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==3.5.1"
+            "version": "==3.8.0"
         },
         "pluggy": {
             "hashes": [
-                "sha256:4224373bacce55f955a878bf9cfa763c1e360858e330072059e10bad68531159",
-                "sha256:74134bbf457f031a36d68416e1509f34bd5ccc019f0bcc952c7b909d06b37bd3"
+                "sha256:c2fd55a7d7a3863cba1a013e4e2414658b1d07b6bc57b3919e0c63c9abb99849",
+                "sha256:d12f0c4b579b15f5e054301bb226ee85eeeba08ffec228092f8defbaa3a4c4b3"
             ],
-            "markers": "python_version >= '3.6'",
-            "version": "==1.0.0"
+            "markers": "python_version >= '3.7'",
+            "version": "==1.2.0"
         },
         "poetry-semver": {
             "hashes": [
                 "sha256:4e6349bd7231cc657f0e1930f7b204e87e33dfd63eef5cac869363969515083a",
                 "sha256:d809b612aa27b39bf2d0fc9d31b4f4809b0e972646c5f19cfa46c725b7638810"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -1455,19 +1464,19 @@
                 "sha256:ce48bc0516ae9415dd5c752c940dfe601b18fe0f48aa249f2386adfa95a004dd"
             ],
             "markers": "python_full_version >= '3.6.2'",
             "version": "==0.7"
         },
         "pyproject-api": {
             "hashes": [
-                "sha256:435f46547a9ff22cf4208ee274fca3e2869aeb062a4834adfc99a4dd64af3cf9",
-                "sha256:4698a3777c2e0f6b624f8a4599131e2a25376d90fe8d146d7ac74c67c6f97c43"
+                "sha256:999f58fa3c92b23ebd31a6bad5d1f87d456744d75e05391be7f5c729015d3d91",
+                "sha256:9cffcbfb64190f207444d7579d315f3278f2c04ba46d685fad93197b5326d348"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==1.5.1"
+            "version": "==1.5.2"
         },
         "pyyaml": {
             "hashes": [
                 "sha256:01b45c0191e6d66c470b6cf1b9531a771a83c1c4208272ead47a3ae4f2f603bf",
                 "sha256:0283c35a6a9fbf047493e3a0ce8d79ef5030852c51e9d911a27badfde0605293",
                 "sha256:055d937d65826939cb044fc8c9b08889e8c743fdc6a32b33e2390f66013e449b",
                 "sha256:07751360502caac1c067a8132d150cf3d61339af5691fe9e87803040dbc5db57",
@@ -1509,30 +1518,30 @@
                 "sha256:f84fbc98b019fef2ee9a1cb3ce93e3187a6df0b2538a651bfb890254ba9f90b5"
             ],
             "markers": "python_version >= '3.6'",
             "version": "==6.0"
         },
         "readme-renderer": {
             "hashes": [
-                "sha256:cd653186dfc73055656f090f227f5cb22a046d7f71a841dfa305f55c9a513273",
-                "sha256:f67a16caedfa71eef48a31b39708637a6f4664c4394801a7b0d6432d13907343"
+                "sha256:9f77b519d96d03d7d7dce44977ba543090a14397c4f60de5b6eb5b8048110aa4",
+                "sha256:e18feb2a1e7706f2865b81ebb460056d93fb29d69daa10b223c00faa7bd9a00a"
             ],
-            "markers": "python_version >= '3.7'",
-            "version": "==37.3"
+            "markers": "python_version >= '3.8'",
+            "version": "==40.0"
         },
         "requests": {
             "extras": [
                 "socks"
             ],
             "hashes": [
-                "sha256:10e94cc4f3121ee6da529d358cdaeaff2f1c409cd377dbc72b825852f2f7e294",
-                "sha256:239d7d4458afcb28a692cdd298d87542235f4ca8d36d03a15bfc128a6559a2f4"
+                "sha256:58cd2187c01e70e6e26505bca751777aa9f2ee0b7f4300988b709f44e013003f",
+                "sha256:942c5a758f98d790eaed1a29cb6eefc7ffb0d1cf7af05c3d2791656dbd6ad1e1"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.30.0"
+            "version": "==2.31.0"
         },
         "requests-toolbelt": {
             "hashes": [
                 "sha256:7681a0a3d047012b5bdc0ee37d7f8f07ebe76ab08caeccfc3921ce23c88d5bc6",
                 "sha256:cccfdd665f0a24fcf4726e690f65639d272bb0637b9b92dfd91a5568ccf6bd06"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -1552,19 +1561,19 @@
                 "sha256:97aacf9dbd4bfd829baad6e6309fa6573aaf1be3f6fa735c8ab05e46cecb261c"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==2.0.0"
         },
         "rich": {
             "hashes": [
-                "sha256:2d11b9b8dd03868f09b4fffadc84a6a8cda574e40dc90821bd845720ebb8e89c",
-                "sha256:69cdf53799e63f38b95b9bf9c875f8c90e78dd62b2f00c13a911c7a3b9fa4704"
+                "sha256:8f87bc7ee54675732fa66a05ebfe489e27264caeeff3728c945d25971b6485ec",
+                "sha256:d653d6bccede5844304c605d5aac802c7cf9621efd700b46c7ec2b51ea914898"
             ],
             "markers": "python_full_version >= '3.7.0'",
-            "version": "==13.3.5"
+            "version": "==13.4.2"
         },
         "secretstorage": {
             "hashes": [
                 "sha256:2403533ef369eca6d2ba81718576c5e0f564d5cca1b58f73a8b23e7d4eeebd77",
                 "sha256:f356e6628222568e3af06f2eba8df495efa13b3b63081dafd4f7d9a7b7bc9f99"
             ],
             "markers": "sys_platform == 'linux'",
@@ -1583,19 +1592,19 @@
                 "sha256:76035d5cd1593d38b9056ae12d460eca3aaa34ad05c315b69145e138ba80a745",
                 "sha256:e0480addd11347ba52f762f3c4d8afa3e10ad0affbc53e3ffddc0ca5f27d5778"
             ],
             "version": "==0.3.1"
         },
         "sh": {
             "hashes": [
-                "sha256:ae3258c5249493cebe73cb4e18253a41ed69262484bad36fdb3efcb8ad8870bb",
-                "sha256:b52bf5833ed01c7b5c5fb73a7f71b3d98d48e9b9b8764236237bdc7ecae850fc"
+                "sha256:14265a4cd1622429edcf300292ec98193530fb143fe642b3437024eca9bee8c5",
+                "sha256:a18920f0839991bc9dfddb6dcc006c360b1064ba96257359f0ea356e9fa75a60"
             ],
-            "markers": "sys_platform != 'win32'",
-            "version": "==1.12.14"
+            "markers": "python_version < '4.0' and python_full_version >= '3.8.1'",
+            "version": "==2.0.4"
         },
         "six": {
             "hashes": [
                 "sha256:1e61c37477a1626458e36f7b1d82aa5c9b094fa4802892072e49de9c60c4c926",
                 "sha256:8abb2f1d86890a2dfb989f9a77cfcfd3e47c2a354b01111771326f8aa26e0254"
             ],
             "markers": "python_version >= '2.7' and python_version not in '3.0, 3.1, 3.2, 3.3'",
@@ -1622,19 +1631,19 @@
                 "sha256:97787ff1fa3256a3eef9eda523a63dbf299f7b47e053cfcf684a1c2a8380c912"
             ],
             "index": "pypi",
             "version": "==6.2.1"
         },
         "sphinx-rtd-theme": {
             "hashes": [
-                "sha256:a0d8bd1a2ed52e0b338cbe19c4b2eef3c5e7a048769753dac6a9f059c7b641b8",
-                "sha256:f823f7e71890abe0ac6aaa6013361ea2696fc8d3e1fa798f463e82bdb77eeff2"
+                "sha256:01c5c5a72e2d025bd23d1f06c59a4831b06e6ce6c01fdd5ebfe9986c0a880fc7",
+                "sha256:6a7e7d8af34eb8fc57d52a09c6b6b9c46ff44aea5951bc831eeb9245378f3689"
             ],
             "index": "pypi",
-            "version": "==1.2.0"
+            "version": "==1.2.2"
         },
         "sphinxcontrib-applehelp": {
             "hashes": [
                 "sha256:29d341f67fb0f6f586b23ad80e072c8e6ad0b48417db2bde114a4c9746feb228",
                 "sha256:828f867945bbe39817c210a1abfd1bc4895c8b73fcaade56d45357a348a07d7e"
             ],
             "markers": "python_version >= '3.8'",
@@ -1657,15 +1666,15 @@
             "version": "==2.0.1"
         },
         "sphinxcontrib-jquery": {
             "hashes": [
                 "sha256:1620739f04e36a2c779f1a131a2dfd49b2fd07351bf1968ced074365933abc7a",
                 "sha256:f936030d7d0147dd026a4f2b5a57343d233f1fc7b363f68b3d4f1cb0993878ae"
             ],
-            "markers": "python_version >= '3.1'",
+            "markers": "python_version >= '2.7'",
             "version": "==4.1"
         },
         "sphinxcontrib-jsmath": {
             "hashes": [
                 "sha256:2ec2eaebfb78f3f2078e73666b1415417a116cc848b72e5172e596c871103178",
                 "sha256:a9925e4a4587247ed2191a22df5f6970656cb8ca2bd6284309578f2153e0c4b8"
             ],
@@ -1726,35 +1735,35 @@
                 "sha256:9e102ef5fdd5a20661eb88fad46338806c3bd32cf1db729603fe3697b1bc83c8"
             ],
             "index": "pypi",
             "version": "==4.0.2"
         },
         "typing-extensions": {
             "hashes": [
-                "sha256:5cb5f4a79139d699607b3ef622a1dedafa84e115ab0024e0d9c044a9479ca7cb",
-                "sha256:fb33085c39dd998ac16d1431ebc293a8b3eedd00fd4a32de0ff79002c19511b4"
+                "sha256:88a4153d8505aabbb4e13aacb7c486c2b4a33ca3b3f807914a9b4c844c471c26",
+                "sha256:d91d5919357fe7f681a9f2b5b4cb2a5f1ef0a1e9f59c4d8ff0d3491e05c0ffd5"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==4.5.0"
+            "version": "==4.6.3"
         },
         "urllib3": {
             "hashes": [
-                "sha256:61717a1095d7e155cdb737ac7bb2f4324a858a1e2e6466f6d03ff630ca68d3cc",
-                "sha256:d055c2f9d38dc53c808f6fdc8eab7360b6fdbbde02340ed25cfbcd817c62469e"
+                "sha256:48e7fafa40319d358848e1bc6809b208340fafe2096f1725d05d67443d0483d1",
+                "sha256:bee28b5e56addb8226c96f7f13ac28cb4c301dd5ea8a6ca179c0b9835e032825"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==2.0.2"
+            "version": "==2.0.3"
         },
         "virtualenv": {
             "hashes": [
-                "sha256:6abec7670e5802a528357fdc75b26b9f57d5d92f29c5462ba0fbe45feacc685e",
-                "sha256:a85caa554ced0c0afbd0d638e7e2d7b5f92d23478d05d17a76daeac8f279f924"
+                "sha256:34da10f14fea9be20e0fd7f04aba9732f84e593dac291b757ce42e3368a39419",
+                "sha256:8ff19a38c1021c742148edc4f81cb43d7f8c6816d2ede2ab72af5b84c749ade1"
             ],
             "markers": "python_version >= '3.7'",
-            "version": "==20.23.0"
+            "version": "==20.23.1"
         },
         "webencodings": {
             "hashes": [
                 "sha256:a0af1213f3c2226497a97e2b3aa01a7e4bee4f403f95be16fc9acd2947514a78",
                 "sha256:b36a1c245f2d304965eb4e0a82848379241dc04b865afcc4aab16748587e1923"
             ],
             "version": "==0.5.1"
```

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/README.rst` & `azureenergylabelercli-2.1.1/azureenergylabelercli/README.rst`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/USAGE.rst` & `azureenergylabelercli-2.1.1/azureenergylabelercli/USAGE.rst`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/__init__.py` & `azureenergylabelercli-2.1.1/azureenergylabelercli/__init__.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/_version.py` & `azureenergylabelercli-2.1.1/azureenergylabelercli/_version.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/azureenergylabelercli.py` & `azureenergylabelercli-2.1.1/azureenergylabelercli/azureenergylabelercli.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/azureenergylabelercliexceptions.py` & `azureenergylabelercli-2.1.1/azureenergylabelercli/azureenergylabelercliexceptions.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/conf/logging.json-example` & `azureenergylabelercli-2.1.1/azureenergylabelercli/conf/logging.json-example`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/dev-requirements.txt` & `azureenergylabelercli-2.1.1/azureenergylabelercli/dev-requirements.txt`

 * *Files 27% similar despite different names*

```diff
@@ -4,21 +4,21 @@
 #
 # This file is created and managed automatically by the template and it is left
 # here only for backwards compatibility reasons with python's ecosystem.
 #
 # Please use Pipfile to update the requirements.
 #
 sphinx>=6.2.1
-sphinx-rtd-theme>=1.2.0
+sphinx-rtd-theme>=1.2.2
 prospector>=1.9.0
-coverage>=7.2.5
+coverage>=7.2.7
 nose>=1.3.7
 nose-htmloutput>=0.6.0
 tox==4.0.0
 betamax>=0.8.1
 betamax-serializers~=0.2.1
 semver>=2.13.0
-gitwrapperlib>=1.0.0
+gitwrapperlib>=1.0.3
 twine>=4.0.2
 coloredlogs>=15.0.1
-emoji>=2.2.0
+emoji>=2.6.0
 toml>=0.10.2
```

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli/validators.py` & `azureenergylabelercli-2.1.1/azureenergylabelercli/validators.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/PKG-INFO` & `azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: azureenergylabelercli
-Version: 2.1.0
+Version: 2.1.1
 Summary: A cli to help generate energy label for Azure tenant, subscriptions and resource groups.
 Home-page: https://github.com/schubergphilis/azureenergylabelercli
 Author: Sayantan Khanra
 Author-email: skhanra@schubergphilis.com
 License: MIT
 Keywords: azureenergylabelercli
 Classifier: Development Status :: 1 - Planning
@@ -297,7 +297,13 @@
 
 
 2.1.0 (15-05-2023)
 ------------------
 
 * Added option to disable banner and spinner
 * Improved filtering of findings
+
+
+2.1.1 (28-06-2023)
+------------------
+
+* Updated library dependency
```

### Comparing `azureenergylabelercli-2.1.0/azureenergylabelercli.egg-info/SOURCES.txt` & `azureenergylabelercli-2.1.1/azureenergylabelercli.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/dev-requirements.txt` & `azureenergylabelercli-2.1.1/dev-requirements.txt`

 * *Files 27% similar despite different names*

```diff
@@ -4,21 +4,21 @@
 #
 # This file is created and managed automatically by the template and it is left
 # here only for backwards compatibility reasons with python's ecosystem.
 #
 # Please use Pipfile to update the requirements.
 #
 sphinx>=6.2.1
-sphinx-rtd-theme>=1.2.0
+sphinx-rtd-theme>=1.2.2
 prospector>=1.9.0
-coverage>=7.2.5
+coverage>=7.2.7
 nose>=1.3.7
 nose-htmloutput>=0.6.0
 tox==4.0.0
 betamax>=0.8.1
 betamax-serializers~=0.2.1
 semver>=2.13.0
-gitwrapperlib>=1.0.0
+gitwrapperlib>=1.0.3
 twine>=4.0.2
 coloredlogs>=15.0.1
-emoji>=2.2.0
+emoji>=2.6.0
 toml>=0.10.2
```

### Comparing `azureenergylabelercli-2.1.0/docs/Makefile` & `azureenergylabelercli-2.1.1/docs/Makefile`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/docs/conf.py` & `azureenergylabelercli-2.1.1/docs/conf.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/docs/index.rst` & `azureenergylabelercli-2.1.1/docs/index.rst`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/setup.py` & `azureenergylabelercli-2.1.1/setup.py`

 * *Files identical despite different names*

### Comparing `azureenergylabelercli-2.1.0/tests/test_azureenergylabelercli.py` & `azureenergylabelercli-2.1.1/tests/test_azureenergylabelercli.py`

 * *Files identical despite different names*

