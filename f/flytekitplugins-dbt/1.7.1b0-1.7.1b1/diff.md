# Comparing `tmp/flytekitplugins-dbt-1.7.1b0.tar.gz` & `tmp/flytekitplugins-dbt-1.7.1b1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "flytekitplugins-dbt-1.7.1b0.tar", last modified: Fri Jun 16 18:14:17 2023, max compression
+gzip compressed data, was "flytekitplugins-dbt-1.7.1b1.tar", last modified: Tue Jun 27 22:00:53 2023, max compression
```

## Comparing `flytekitplugins-dbt-1.7.1b0.tar` & `flytekitplugins-dbt-1.7.1b1.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 18:14:17.806454 flytekitplugins-dbt-1.7.1b0/
--rw-r--r--   0 runner    (1001) docker     (123)     1213 2023-06-16 18:14:17.806454 flytekitplugins-dbt-1.7.1b0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      313 2023-06-16 18:13:54.000000 flytekitplugins-dbt-1.7.1b0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 18:14:17.802454 flytekitplugins-dbt-1.7.1b0/flytekitplugins/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 18:14:17.802454 flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/
--rw-r--r--   0 runner    (1001) docker     (123)      443 2023-06-16 18:13:54.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1132 2023-06-16 18:13:54.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/error.py
--rw-r--r--   0 runner    (1001) docker     (123)     5924 2023-06-16 18:13:54.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/schema.py
--rw-r--r--   0 runner    (1001) docker     (123)    11181 2023-06-16 18:13:54.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/task.py
--rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-16 18:13:54.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-16 18:14:17.802454 flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1213 2023-06-16 18:14:17.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      431 2023-06-16 18:14:17.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-16 18:14:17.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-16 18:14:17.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/namespace_packages.txt
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-16 18:14:17.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-16 18:14:17.000000 flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-16 18:14:17.806454 flytekitplugins-dbt-1.7.1b0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1333 2023-06-16 18:14:14.000000 flytekitplugins-dbt-1.7.1b0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:00:53.144609 flytekitplugins-dbt-1.7.1b1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1213 2023-06-27 22:00:53.144609 flytekitplugins-dbt-1.7.1b1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      313 2023-06-27 22:00:35.000000 flytekitplugins-dbt-1.7.1b1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:00:53.144609 flytekitplugins-dbt-1.7.1b1/flytekitplugins/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:00:53.144609 flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/
+-rw-r--r--   0 runner    (1001) docker     (123)      443 2023-06-27 22:00:35.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1132 2023-06-27 22:00:35.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5924 2023-06-27 22:00:35.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/schema.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11181 2023-06-27 22:00:35.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/task.py
+-rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-27 22:00:35.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:00:53.144609 flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1213 2023-06-27 22:00:53.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      431 2023-06-27 22:00:53.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 22:00:53.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-27 22:00:53.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/namespace_packages.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-27 22:00:53.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-27 22:00:53.000000 flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 22:00:53.144609 flytekitplugins-dbt-1.7.1b1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1333 2023-06-27 22:00:50.000000 flytekitplugins-dbt-1.7.1b1/setup.py
```

### Comparing `flytekitplugins-dbt-1.7.1b0/PKG-INFO` & `flytekitplugins-dbt-1.7.1b1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: flytekitplugins-dbt
-Version: 1.7.1b0
+Version: 1.7.1b1
 Summary: DBT Plugin for Flytekit
 Home-page: https://github.com/flyteorg/flytekit/tree/master/plugins/flytekit-dbt
 Author: flyteorg
 Author-email: admin@flyte.org
 License: apache2
 Classifier: Intended Audience :: Science/Research
 Classifier: Intended Audience :: Developers
```

### Comparing `flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/error.py` & `flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/error.py`

 * *Files identical despite different names*

### Comparing `flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/schema.py` & `flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/schema.py`

 * *Files identical despite different names*

### Comparing `flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/task.py` & `flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/task.py`

 * *Files identical despite different names*

### Comparing `flytekitplugins-dbt-1.7.1b0/flytekitplugins/dbt/util.py` & `flytekitplugins-dbt-1.7.1b1/flytekitplugins/dbt/util.py`

 * *Files identical despite different names*

### Comparing `flytekitplugins-dbt-1.7.1b0/flytekitplugins_dbt.egg-info/PKG-INFO` & `flytekitplugins-dbt-1.7.1b1/flytekitplugins_dbt.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: flytekitplugins-dbt
-Version: 1.7.1b0
+Version: 1.7.1b1
 Summary: DBT Plugin for Flytekit
 Home-page: https://github.com/flyteorg/flytekit/tree/master/plugins/flytekit-dbt
 Author: flyteorg
 Author-email: admin@flyte.org
 License: apache2
 Classifier: Intended Audience :: Science/Research
 Classifier: Intended Audience :: Developers
```

### Comparing `flytekitplugins-dbt-1.7.1b0/setup.py` & `flytekitplugins-dbt-1.7.1b1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 microlib_name = f"flytekitplugins-{PLUGIN_NAME}"
 
 plugin_requires = [
     "flytekit>=1.3.0b2,<2.0.0",
     "dbt-core>=1.0.0",
 ]
 
-__version__ = "1.7.1b0"
+__version__ = "1.7.1b1"
 
 setup(
     name=microlib_name,
     version=__version__,
     author="flyteorg",
     author_email="admin@flyte.org",
     description="DBT Plugin for Flytekit",
```

