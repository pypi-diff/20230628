# Comparing `tmp/optscale_arcee-0.1.35.tar.gz` & `tmp/optscale_arcee-0.1.36.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "optscale_arcee-0.1.35.tar", last modified: Mon Jun 19 06:55:38 2023, max compression
+gzip compressed data, was "optscale_arcee-0.1.36.tar", last modified: Wed Jun 28 13:01:02 2023, max compression
```

## Comparing `optscale_arcee-0.1.35.tar` & `optscale_arcee-0.1.36.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/
--rw-r--r--   0 runner    (1001) docker     (123)    11336 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1769 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1393 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/optscale_arcee/
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4051 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/arcee.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/optscale_arcee/hw_stat_collector/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/hw_stat_collector/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4195 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/hw_stat_collector/collector.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/optscale_arcee/module_collector/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/module_collector/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2632 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/module_collector/collector.py
--rw-r--r--   0 runner    (1001) docker     (123)     6778 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/name_generator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10124 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/platform.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/optscale_arcee/platforms_meta/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/platforms_meta/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2539 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/platforms_meta/azure.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/optscale_arcee/sender/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/sender/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4576 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/optscale_arcee/sender/sender.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/optscale_arcee.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1769 2023-06-19 06:55:38.000000 optscale_arcee-0.1.35/optscale_arcee.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      687 2023-06-19 06:55:38.000000 optscale_arcee-0.1.35/optscale_arcee.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-19 06:55:38.000000 optscale_arcee-0.1.35/optscale_arcee.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       60 2023-06-19 06:55:38.000000 optscale_arcee-0.1.35/optscale_arcee.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-19 06:55:38.000000 optscale_arcee-0.1.35/optscale_arcee.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      635 2023-06-19 06:55:38.628536 optscale_arcee-0.1.35/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-19 06:55:33.000000 optscale_arcee-0.1.35/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:01:02.867138 optscale_arcee-0.1.36/
+-rw-r--r--   0 runner    (1001) docker     (123)    11336 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1765 2023-06-28 13:01:02.867138 optscale_arcee-0.1.36/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1393 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:01:02.863138 optscale_arcee-0.1.36/optscale_arcee/
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4051 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/arcee.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:01:02.863138 optscale_arcee-0.1.36/optscale_arcee/hw_stat_collector/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/hw_stat_collector/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4195 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/hw_stat_collector/collector.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:01:02.863138 optscale_arcee-0.1.36/optscale_arcee/module_collector/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/module_collector/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2632 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/module_collector/collector.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6778 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/name_generator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10124 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/platform.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:01:02.863138 optscale_arcee-0.1.36/optscale_arcee/platforms_meta/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/platforms_meta/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2539 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/platforms_meta/azure.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:01:02.863138 optscale_arcee-0.1.36/optscale_arcee/sender/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/sender/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4576 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/optscale_arcee/sender/sender.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:01:02.863138 optscale_arcee-0.1.36/optscale_arcee.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1765 2023-06-28 13:01:02.000000 optscale_arcee-0.1.36/optscale_arcee.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      687 2023-06-28 13:01:02.000000 optscale_arcee-0.1.36/optscale_arcee.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:01:02.000000 optscale_arcee-0.1.36/optscale_arcee.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       60 2023-06-28 13:01:02.000000 optscale_arcee-0.1.36/optscale_arcee.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-28 13:01:02.000000 optscale_arcee-0.1.36/optscale_arcee.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      631 2023-06-28 13:01:02.867138 optscale_arcee-0.1.36/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 13:00:58.000000 optscale_arcee-0.1.36/setup.py
```

### Comparing `optscale_arcee-0.1.35/LICENSE` & `optscale_arcee-0.1.36/LICENSE`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/PKG-INFO` & `optscale_arcee-0.1.36/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 Metadata-Version: 2.1
 Name: optscale_arcee
-Version: 0.1.35
+Version: 0.1.36
 Summary: ML profiling tool for OptScale
 Home-page: https://my.optscale.com/
 Author: Hystax
 License: "Apache License 2.0"
-Project-URL: Source, https://github.com/hystax/optscale_arcee_dev
+Project-URL: Source, https://github.com/hystax/optscale_arcee
 Keywords: arcee,ml,optscale,finops,mlops
 Requires-Python: <4,>=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Arcee
 ## *The OptScale ML profiling tool by Hystax*
```

### Comparing `optscale_arcee-0.1.35/README.md` & `optscale_arcee-0.1.36/README.md`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee/arcee.py` & `optscale_arcee-0.1.36/optscale_arcee/arcee.py`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee/hw_stat_collector/collector.py` & `optscale_arcee-0.1.36/optscale_arcee/hw_stat_collector/collector.py`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee/module_collector/collector.py` & `optscale_arcee-0.1.36/optscale_arcee/module_collector/collector.py`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee/name_generator.py` & `optscale_arcee-0.1.36/optscale_arcee/name_generator.py`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee/platform.py` & `optscale_arcee-0.1.36/optscale_arcee/platform.py`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee/platforms_meta/azure.py` & `optscale_arcee-0.1.36/optscale_arcee/platforms_meta/azure.py`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee/sender/sender.py` & `optscale_arcee-0.1.36/optscale_arcee/sender/sender.py`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/optscale_arcee.egg-info/PKG-INFO` & `optscale_arcee-0.1.36/optscale_arcee.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 Metadata-Version: 2.1
 Name: optscale-arcee
-Version: 0.1.35
+Version: 0.1.36
 Summary: ML profiling tool for OptScale
 Home-page: https://my.optscale.com/
 Author: Hystax
 License: "Apache License 2.0"
-Project-URL: Source, https://github.com/hystax/optscale_arcee_dev
+Project-URL: Source, https://github.com/hystax/optscale_arcee
 Keywords: arcee,ml,optscale,finops,mlops
 Requires-Python: <4,>=3.7
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Arcee
 ## *The OptScale ML profiling tool by Hystax*
```

### Comparing `optscale_arcee-0.1.35/optscale_arcee.egg-info/SOURCES.txt` & `optscale_arcee-0.1.36/optscale_arcee.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `optscale_arcee-0.1.35/setup.cfg` & `optscale_arcee-0.1.36/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 [metadata]
 name = optscale_arcee
-version = 0.1.35
+version = 0.1.36
 author = Hystax
 description = ML profiling tool for OptScale
 long_description = file: README.md
 long_description_content_type = text/markdown
 license = "Apache License 2.0"
 url = https://my.optscale.com/
 project_urls = 
-	Source = https://github.com/hystax/optscale_arcee_dev
+	Source = https://github.com/hystax/optscale_arcee
 keywords = arcee, ml, optscale, finops, mlops
 
 [options]
 python_requires = >=3.7, <4
 install_requires = 
 	aiohttp==3.8.4
 	aiofiles==22.1.0
```

