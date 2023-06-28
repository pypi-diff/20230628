# Comparing `tmp/consumableai-1.0.1.tar.gz` & `tmp/consumableai-1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "consumableai-1.0.1.tar", last modified: Tue Jun  6 08:49:20 2023, max compression
+gzip compressed data, was "consumableai-1.0.2.tar", last modified: Wed Jun 28 11:01:16 2023, max compression
```

## Comparing `consumableai-1.0.1.tar` & `consumableai-1.0.2.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 sandeep    (501) staff       (20)        0 2023-06-06 08:49:20.844868 consumableai-1.0.1/
--rw-r--r--   0 sandeep    (501) staff       (20)     1070 2023-06-01 16:21:54.000000 consumableai-1.0.1/LICENSE
--rw-r--r--   0 sandeep    (501) staff       (20)     1744 2023-06-06 08:49:20.844632 consumableai-1.0.1/PKG-INFO
--rw-r--r--   0 sandeep    (501) staff       (20)     1625 2023-06-02 08:23:20.000000 consumableai-1.0.1/README.md
-drwxr-xr-x   0 sandeep    (501) staff       (20)        0 2023-06-06 08:49:20.843411 consumableai-1.0.1/consumableai/
--rw-r--r--   0 sandeep    (501) staff       (20)        0 2023-05-29 10:28:08.000000 consumableai-1.0.1/consumableai/__init__.py
--rw-r--r--   0 sandeep    (501) staff       (20)     6215 2023-06-06 08:45:52.000000 consumableai-1.0.1/consumableai/cli.py
-drwxr-xr-x   0 sandeep    (501) staff       (20)        0 2023-06-06 08:49:20.844375 consumableai-1.0.1/consumableai.egg-info/
--rw-r--r--   0 sandeep    (501) staff       (20)     1744 2023-06-06 08:49:20.000000 consumableai-1.0.1/consumableai.egg-info/PKG-INFO
--rw-r--r--   0 sandeep    (501) staff       (20)      289 2023-06-06 08:49:20.000000 consumableai-1.0.1/consumableai.egg-info/SOURCES.txt
--rw-r--r--   0 sandeep    (501) staff       (20)        1 2023-06-06 08:49:20.000000 consumableai-1.0.1/consumableai.egg-info/dependency_links.txt
--rw-r--r--   0 sandeep    (501) staff       (20)       55 2023-06-06 08:49:20.000000 consumableai-1.0.1/consumableai.egg-info/entry_points.txt
--rw-r--r--   0 sandeep    (501) staff       (20)       46 2023-06-06 08:49:20.000000 consumableai-1.0.1/consumableai.egg-info/requires.txt
--rw-r--r--   0 sandeep    (501) staff       (20)       13 2023-06-06 08:49:20.000000 consumableai-1.0.1/consumableai.egg-info/top_level.txt
--rw-r--r--   0 sandeep    (501) staff       (20)       38 2023-06-06 08:49:20.845046 consumableai-1.0.1/setup.cfg
--rw-r--r--   0 sandeep    (501) staff       (20)      626 2023-06-06 08:48:24.000000 consumableai-1.0.1/setup.py
+drwxr-xr-x   0 sandeep    (501) staff       (20)        0 2023-06-28 11:01:16.968261 consumableai-1.0.2/
+-rw-r--r--   0 sandeep    (501) staff       (20)     1070 2023-06-01 16:21:54.000000 consumableai-1.0.2/LICENSE
+-rw-r--r--   0 sandeep    (501) staff       (20)     1817 2023-06-28 11:01:16.967975 consumableai-1.0.2/PKG-INFO
+-rw-r--r--   0 sandeep    (501) staff       (20)     1625 2023-06-02 08:23:20.000000 consumableai-1.0.2/README.md
+drwxr-xr-x   0 sandeep    (501) staff       (20)        0 2023-06-28 11:01:16.966414 consumableai-1.0.2/consumableai/
+-rw-r--r--   0 sandeep    (501) staff       (20)        0 2023-05-29 10:28:08.000000 consumableai-1.0.2/consumableai/__init__.py
+-rw-r--r--   0 sandeep    (501) staff       (20)     6215 2023-06-06 08:45:52.000000 consumableai-1.0.2/consumableai/cli.py
+drwxr-xr-x   0 sandeep    (501) staff       (20)        0 2023-06-28 11:01:16.967622 consumableai-1.0.2/consumableai.egg-info/
+-rw-r--r--   0 sandeep    (501) staff       (20)     1817 2023-06-28 11:01:16.000000 consumableai-1.0.2/consumableai.egg-info/PKG-INFO
+-rw-r--r--   0 sandeep    (501) staff       (20)      289 2023-06-28 11:01:16.000000 consumableai-1.0.2/consumableai.egg-info/SOURCES.txt
+-rw-r--r--   0 sandeep    (501) staff       (20)        1 2023-06-28 11:01:16.000000 consumableai-1.0.2/consumableai.egg-info/dependency_links.txt
+-rw-r--r--   0 sandeep    (501) staff       (20)       56 2023-06-28 11:01:16.000000 consumableai-1.0.2/consumableai.egg-info/entry_points.txt
+-rw-r--r--   0 sandeep    (501) staff       (20)       53 2023-06-28 11:01:16.000000 consumableai-1.0.2/consumableai.egg-info/requires.txt
+-rw-r--r--   0 sandeep    (501) staff       (20)       13 2023-06-28 11:01:16.000000 consumableai-1.0.2/consumableai.egg-info/top_level.txt
+-rw-r--r--   0 sandeep    (501) staff       (20)       38 2023-06-28 11:01:16.968331 consumableai-1.0.2/setup.cfg
+-rw-r--r--   0 sandeep    (501) staff       (20)      633 2023-06-28 08:58:50.000000 consumableai-1.0.2/setup.py
```

### Comparing `consumableai-1.0.1/LICENSE` & `consumableai-1.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `consumableai-1.0.1/PKG-INFO` & `consumableai-1.0.2/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,13 +1,7 @@
-Metadata-Version: 2.1
-Name: consumableai
-Version: 1.0.1
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 # ConsumableAI
 
 ## Overview
 
 Consumable AI is an SDK that can be easily integrated into the self hosted BI tools which gives enterprises the power to talk to the databases in natural language. This will make exploratory data analyses easy to perform and remove the barrier of acquiring SQL skills and database know-how.
 
 ## Installation
```

### Comparing `consumableai-1.0.1/README.md` & `consumableai-1.0.2/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,7 +1,17 @@
+Metadata-Version: 2.1
+Name: consumableai
+Version: 1.0.2
+Summary: UNKNOWN
+Home-page: UNKNOWN
+License: UNKNOWN
+Platform: UNKNOWN
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 # ConsumableAI
 
 ## Overview
 
 Consumable AI is an SDK that can be easily integrated into the self hosted BI tools which gives enterprises the power to talk to the databases in natural language. This will make exploratory data analyses easy to perform and remove the barrier of acquiring SQL skills and database know-how.
 
 ## Installation
@@ -30,7 +40,9 @@
    This command will prompt you to enter various database-related values. The library will create the table schema for your data. Please note that ConsumableAI does not store your data directly. Instead, it creates the table schema and shares a link to a spreadsheet. You can make changes to the spreadsheet, and when you're ready, inform us to update the schema accordingly.
 
    The spreadsheet link will be provided after initialization.
 
 For more information and documentation, please visit our website at [https://platform.consumableai.com](https://platform.consumableai.com).
 
 Happy data exploration with ConsumableAI!
+
+
```

### Comparing `consumableai-1.0.1/consumableai/cli.py` & `consumableai-1.0.2/consumableai/cli.py`

 * *Files identical despite different names*

### Comparing `consumableai-1.0.1/consumableai.egg-info/PKG-INFO` & `consumableai-1.0.2/consumableai.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,14 @@
 Metadata-Version: 2.1
 Name: consumableai
-Version: 1.0.1
+Version: 1.0.2
+Summary: UNKNOWN
+Home-page: UNKNOWN
+License: UNKNOWN
+Platform: UNKNOWN
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # ConsumableAI
 
 ## Overview
 
@@ -36,7 +40,9 @@
    This command will prompt you to enter various database-related values. The library will create the table schema for your data. Please note that ConsumableAI does not store your data directly. Instead, it creates the table schema and shares a link to a spreadsheet. You can make changes to the spreadsheet, and when you're ready, inform us to update the schema accordingly.
 
    The spreadsheet link will be provided after initialization.
 
 For more information and documentation, please visit our website at [https://platform.consumableai.com](https://platform.consumableai.com).
 
 Happy data exploration with ConsumableAI!
+
+
```

### Comparing `consumableai-1.0.1/setup.py` & `consumableai-1.0.2/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,26 +1,26 @@
 from setuptools import setup
 from pathlib import Path
 this_directory = Path(__file__).parent
 long_description = (this_directory / "README.md").read_text()
 
 setup(
     name='consumableai',
-    version='1.0.1',
+    version='1.0.2',
     packages=['consumableai'],
     entry_points={
         'console_scripts': [
             'consumableai=consumableai.cli:main',
         ],
     },
     scripts=['consumableai/cli.py'],
     install_requires=[
         'pandas',
         'pyyaml',
         "click",
-        "psycopg2",
+        "psycopg2-binary",
         "requests",
         "pathlib"
     ],
     long_description=long_description,
     long_description_content_type='text/markdown',
 )
```

