# Comparing `tmp/piwaterflow-1.0.0.tar.gz` & `tmp/piwaterflow-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "piwaterflow-1.0.0.tar", last modified: Tue Jun 27 17:37:08 2023, max compression
+gzip compressed data, was "piwaterflow-1.0.1.tar", last modified: Wed Jun 28 12:28:08 2023, max compression
```

## Comparing `piwaterflow-1.0.0.tar` & `piwaterflow-1.0.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 17:37:08.865872 piwaterflow-1.0.0/
--rw-rw-rw-   0        0        0     1430 2023-06-27 17:37:08.864872 piwaterflow-1.0.0/PKG-INFO
--rw-rw-rw-   0        0        0      793 2023-05-05 10:59:47.000000 piwaterflow-1.0.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 17:37:08.802871 piwaterflow-1.0.0/piwaterflow/
--rw-rw-rw-   0        0        0      122 2023-06-26 12:27:27.000000 piwaterflow-1.0.0/piwaterflow/__init__.py
--rw-rw-rw-   0        0        0      267 2023-06-19 06:30:06.000000 piwaterflow-1.0.0/piwaterflow/__main__.py
--rw-rw-rw-   0        0        0      709 2023-06-19 06:30:06.000000 piwaterflow-1.0.0/piwaterflow/config-template.yml
--rw-rw-rw-   0        0        0     1202 2023-06-19 06:30:06.000000 piwaterflow-1.0.0/piwaterflow/config_waterflow.py
-drwxrwxrwx   0        0        0        0 2023-06-27 17:37:08.849870 piwaterflow-1.0.0/piwaterflow/tests/
--rw-rw-rw-   0        0        0        0 2022-12-20 17:07:56.000000 piwaterflow-1.0.0/piwaterflow/tests/__init__.py
--rw-rw-rw-   0        0        0      724 2023-05-05 10:59:47.000000 piwaterflow-1.0.0/piwaterflow/tests/test_000.py
--rw-rw-rw-   0        0        0    24760 2023-06-26 12:25:04.000000 piwaterflow-1.0.0/piwaterflow/waterflow.py
-drwxrwxrwx   0        0        0        0 2023-06-27 17:37:08.838871 piwaterflow-1.0.0/piwaterflow.egg-info/
--rw-rw-rw-   0        0        0     1430 2023-06-27 17:37:08.000000 piwaterflow-1.0.0/piwaterflow.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      530 2023-06-27 17:37:08.000000 piwaterflow-1.0.0/piwaterflow.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 17:37:08.000000 piwaterflow-1.0.0/piwaterflow.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       93 2023-06-27 17:37:08.000000 piwaterflow-1.0.0/piwaterflow.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-06-27 17:37:08.000000 piwaterflow-1.0.0/piwaterflow.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 17:37:08.865872 piwaterflow-1.0.0/setup.cfg
--rw-rw-rw-   0        0        0     1466 2023-06-27 12:45:14.000000 piwaterflow-1.0.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-27 17:37:08.862872 piwaterflow-1.0.0/tests/
--rw-rw-rw-   0        0        0        0 2023-05-05 10:59:47.000000 piwaterflow-1.0.0/tests/__init__.py
--rw-rw-rw-   0        0        0     4975 2023-06-19 06:30:06.000000 piwaterflow-1.0.0/tests/test_000_loop.py
--rw-rw-rw-   0        0        0     2309 2023-06-19 06:30:06.000000 piwaterflow-1.0.0/tests/test_001_forward.py
--rw-rw-rw-   0        0        0     2531 2023-06-19 06:30:06.000000 piwaterflow-1.0.0/tests/test_002_reverse.py
--rw-rw-rw-   0        0        0     1092 2023-05-31 12:49:45.000000 piwaterflow-1.0.0/tests/test_003_lock.py
--rw-rw-rw-   0        0        0     1100 2023-06-19 06:30:06.000000 piwaterflow-1.0.0/tests/test_004_events.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:08.833527 piwaterflow-1.0.1/
+-rw-rw-rw-   0        0        0     1430 2023-06-28 12:28:08.833527 piwaterflow-1.0.1/PKG-INFO
+-rw-rw-rw-   0        0        0      793 2023-05-05 10:59:47.000000 piwaterflow-1.0.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:08.793524 piwaterflow-1.0.1/piwaterflow/
+-rw-rw-rw-   0        0        0      122 2023-06-28 12:27:56.000000 piwaterflow-1.0.1/piwaterflow/__init__.py
+-rw-rw-rw-   0        0        0      267 2023-06-19 06:30:06.000000 piwaterflow-1.0.1/piwaterflow/__main__.py
+-rw-rw-rw-   0        0        0      709 2023-06-19 06:30:06.000000 piwaterflow-1.0.1/piwaterflow/config-template.yml
+-rw-rw-rw-   0        0        0     1202 2023-06-19 06:30:06.000000 piwaterflow-1.0.1/piwaterflow/config_waterflow.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:08.813526 piwaterflow-1.0.1/piwaterflow/tests/
+-rw-rw-rw-   0        0        0        0 2022-12-20 17:07:56.000000 piwaterflow-1.0.1/piwaterflow/tests/__init__.py
+-rw-rw-rw-   0        0        0      724 2023-05-05 10:59:47.000000 piwaterflow-1.0.1/piwaterflow/tests/test_000.py
+-rw-rw-rw-   0        0        0    24760 2023-06-26 12:25:04.000000 piwaterflow-1.0.1/piwaterflow/waterflow.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:08.813526 piwaterflow-1.0.1/piwaterflow.egg-info/
+-rw-rw-rw-   0        0        0     1430 2023-06-28 12:28:08.000000 piwaterflow-1.0.1/piwaterflow.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      530 2023-06-28 12:28:08.000000 piwaterflow-1.0.1/piwaterflow.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:28:08.000000 piwaterflow-1.0.1/piwaterflow.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       93 2023-06-28 12:28:08.000000 piwaterflow-1.0.1/piwaterflow.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 12:28:08.000000 piwaterflow-1.0.1/piwaterflow.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:28:08.833527 piwaterflow-1.0.1/setup.cfg
+-rw-rw-rw-   0        0        0     1466 2023-06-27 12:45:14.000000 piwaterflow-1.0.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:28:08.833527 piwaterflow-1.0.1/tests/
+-rw-rw-rw-   0        0        0        0 2023-05-05 10:59:47.000000 piwaterflow-1.0.1/tests/__init__.py
+-rw-rw-rw-   0        0        0     4975 2023-06-19 06:30:06.000000 piwaterflow-1.0.1/tests/test_000_loop.py
+-rw-rw-rw-   0        0        0     2309 2023-06-19 06:30:06.000000 piwaterflow-1.0.1/tests/test_001_forward.py
+-rw-rw-rw-   0        0        0     2531 2023-06-19 06:30:06.000000 piwaterflow-1.0.1/tests/test_002_reverse.py
+-rw-rw-rw-   0        0        0     1092 2023-05-31 12:49:45.000000 piwaterflow-1.0.1/tests/test_003_lock.py
+-rw-rw-rw-   0        0        0     1100 2023-06-19 06:30:06.000000 piwaterflow-1.0.1/tests/test_004_events.py
```

### Comparing `piwaterflow-1.0.0/PKG-INFO` & `piwaterflow-1.0.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: piwaterflow
-Version: 1.0.0
+Version: 1.0.1
 Summary: Raspberry Pi Waterflow resilient system
 Home-page: https://github.com/Phornee/piwaterflow
 Author: Ismael Raya
 Author-email: phornee@gmail.com
 License: UNKNOWN
 Description: # PiWaterflow
         This is a resilient watering system, executed in a Raspberry Pi to control irrigation valves using relays.
```

### Comparing `piwaterflow-1.0.0/README.md` & `piwaterflow-1.0.1/README.md`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/piwaterflow/config-template.yml` & `piwaterflow-1.0.1/piwaterflow/config-template.yml`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/piwaterflow/config_waterflow.py` & `piwaterflow-1.0.1/piwaterflow/config_waterflow.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/piwaterflow/tests/test_000.py` & `piwaterflow-1.0.1/piwaterflow/tests/test_000.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/piwaterflow/waterflow.py` & `piwaterflow-1.0.1/piwaterflow/waterflow.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/piwaterflow.egg-info/PKG-INFO` & `piwaterflow-1.0.1/piwaterflow.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: piwaterflow
-Version: 1.0.0
+Version: 1.0.1
 Summary: Raspberry Pi Waterflow resilient system
 Home-page: https://github.com/Phornee/piwaterflow
 Author: Ismael Raya
 Author-email: phornee@gmail.com
 License: UNKNOWN
 Description: # PiWaterflow
         This is a resilient watering system, executed in a Raspberry Pi to control irrigation valves using relays.
```

### Comparing `piwaterflow-1.0.0/piwaterflow.egg-info/SOURCES.txt` & `piwaterflow-1.0.1/piwaterflow.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/setup.py` & `piwaterflow-1.0.1/setup.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/tests/test_000_loop.py` & `piwaterflow-1.0.1/tests/test_000_loop.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/tests/test_001_forward.py` & `piwaterflow-1.0.1/tests/test_001_forward.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/tests/test_002_reverse.py` & `piwaterflow-1.0.1/tests/test_002_reverse.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/tests/test_003_lock.py` & `piwaterflow-1.0.1/tests/test_003_lock.py`

 * *Files identical despite different names*

### Comparing `piwaterflow-1.0.0/tests/test_004_events.py` & `piwaterflow-1.0.1/tests/test_004_events.py`

 * *Files identical despite different names*

