# Comparing `tmp/BODSDataExtractor-1.2.tar.gz` & `tmp/BODSDataExtractor-1.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "BODSDataExtractor-1.2.tar", last modified: Wed Jun 28 13:21:28 2023, max compression
+gzip compressed data, was "BODSDataExtractor-1.2.1.tar", last modified: Wed Jun 28 15:31:51 2023, max compression
```

## Comparing `BODSDataExtractor-1.2.tar` & `BODSDataExtractor-1.2.1.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.325192 BODSDataExtractor-1.2/
--rw-rw-rw-   0        0        0     1491 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2/LICENCE
--rw-rw-rw-   0        0        0      109 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2/MANIFEST.in
--rw-rw-rw-   0        0        0    38390 2023-06-28 13:21:28.322192 BODSDataExtractor-1.2/PKG-INFO
--rw-rw-rw-   0        0        0    37674 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2/README.md
--rw-rw-rw-   0        0        0     1058 2023-06-28 13:14:56.000000 BODSDataExtractor-1.2/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-28 13:21:28.326191 BODSDataExtractor-1.2/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.153473 BODSDataExtractor-1.2/src/
-drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.257513 BODSDataExtractor-1.2/src/BODSDataExtractor/
--rw-rw-rw-   0        0        0     6320 2023-02-15 16:27:59.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv
--rw-rw-rw-   0        0        0        2 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/__init__.py
--rw-rw-rw-   0        0        0     4676 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/classes.py
--rw-rw-rw-   0        0        0     3807 2023-06-28 13:06:47.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/example.py
--rw-rw-rw-   0        0        0    93029 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/extractor.py
--rw-rw-rw-   0        0        0     2827 2023-03-31 15:04:55.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/otc_db_download.py
-drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.312550 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/
--rw-rw-rw-   0        0        0    38390 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      493 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      127 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 15:31:51.180704 BODSDataExtractor-1.2.1/
+-rw-rw-rw-   0        0        0     1491 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2.1/LICENCE
+-rw-rw-rw-   0        0        0      109 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2.1/MANIFEST.in
+-rw-rw-rw-   0        0        0    38392 2023-06-28 15:31:51.177689 BODSDataExtractor-1.2.1/PKG-INFO
+-rw-rw-rw-   0        0        0    37674 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2.1/README.md
+-rw-rw-rw-   0        0        0     1082 2023-06-28 14:46:04.000000 BODSDataExtractor-1.2.1/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 15:31:51.181688 BODSDataExtractor-1.2.1/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 15:31:51.102629 BODSDataExtractor-1.2.1/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 15:31:51.137711 BODSDataExtractor-1.2.1/src/BODSDataExtractor/
+-rw-rw-rw-   0        0        0     6320 2023-02-15 16:27:59.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv
+-rw-rw-rw-   0        0        0        2 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor/__init__.py
+-rw-rw-rw-   0        0        0     4676 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor/classes.py
+-rw-rw-rw-   0        0        0     3809 2023-06-28 14:32:00.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor/example.py
+-rw-rw-rw-   0        0        0    93045 2023-06-28 15:31:38.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor/extractor.py
+-rw-rw-rw-   0        0        0     2827 2023-03-31 15:04:55.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor/otc_db_download.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:31:51.173689 BODSDataExtractor-1.2.1/src/BODSDataExtractor.egg-info/
+-rw-rw-rw-   0        0        0    38392 2023-06-28 15:31:51.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      493 2023-06-28 15:31:51.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 15:31:51.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      141 2023-06-28 15:31:51.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 15:31:51.000000 BODSDataExtractor-1.2.1/src/BODSDataExtractor.egg-info/top_level.txt
```

### Comparing `BODSDataExtractor-1.2/LICENCE` & `BODSDataExtractor-1.2.1/LICENCE`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.2/PKG-INFO` & `BODSDataExtractor-1.2.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: BODSDataExtractor
-Version: 1.2
+Version: 1.2.1
 Summary: This project was created to lower the barrier to entry for analysis of UK Bus Open Data. It facilitates the fetching and extraction of clean data, currently focussed on Timetables, into tables to be used for analysis or your own projects.
 Author-email: "Ali Partner, Spencer Brittain" <bodshelpdesk@kpmg.co.uk>
 Project-URL: Homepage, https://github.com/department-for-transport-BODS/bods-data-extractor
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.2 Summary: This
+Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.2.1 Summary: This
 project was created to lower the barrier to entry for analysis of UK Bus Open
 Data. It facilitates the fetching and extraction of clean data, currently
 focussed on Timetables, into tables to be used for analysis or your own
 projects. Author-email: "Ali Partner, Spencer Brittain"
 kpmg.co.uk> Project-URL: Homepage, https://github.com/department-for-transport-
 BODS/bods-data-extractor Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License Classifier: Operating System
```

### Comparing `BODSDataExtractor-1.2/README.md` & `BODSDataExtractor-1.2.1/README.md`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.2/pyproject.toml` & `BODSDataExtractor-1.2.1/pyproject.toml`

 * *Files 7% similar despite different names*

```diff
@@ -3,15 +3,15 @@
     "setuptools>=42"
 ]
 build-backend = "setuptools.build_meta"
 
 
 [project]
 name = "BODSDataExtractor"
-version = "1.2"
+version = "1.2.1"
 authors = [
   { name="Ali Partner, Spencer Brittain", email="bodshelpdesk@kpmg.co.uk" }
 ]
 description = "This project was created to lower the barrier to entry for analysis of UK Bus Open Data. It facilitates the fetching and extraction of clean data, currently focussed on Timetables, into tables to be used for analysis or your own projects."
 readme = "README.md"
 license = { file="LICENSE" }
 requires-python = ">=3.8"
@@ -26,13 +26,14 @@
     ,"bods-client>=0.11.0"
     ,"protobuf==3.20"
     ,"lxml==4.9.1"
     ,"xmltodict==0.13.0"
     ,"shapely>=1.8.5"
     ,"geopandas>=0.12.1"
     ,"plotly<=5.13.1"
+    ,"dacite>=1.8.1"
 ]
 
 [project.urls]
 "Homepage" = "https://github.com/department-for-transport-BODS/bods-data-extractor"
```

### Comparing `BODSDataExtractor-1.2/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv` & `BODSDataExtractor-1.2.1/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.2/src/BODSDataExtractor/classes.py` & `BODSDataExtractor-1.2.1/src/BODSDataExtractor/classes.py`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.2/src/BODSDataExtractor/example.py` & `BODSDataExtractor-1.2.1/src/BODSDataExtractor/example.py`

 * *Files 0% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 # In this example, we are interested in 2 particular noc codes (BPTR and RBTS),
 # that have been flagged as in need of further investigation from previous manual analysis.
 # 
 # All that is needed is to enter your api key in the variable 'api', and run the code!
 # =============================================================================
 
 try:
-  from BODSDataExtractor.extractor import TimetableExtractor
+    from BODSDataExtractor.extractor import TimetableExtractor
 except:
   from extractor import TimetableExtractor
   
 import os
 
 #retrieve api key from environment variables
 api = os.environ.get('BODS_API_KEY')
```

### Comparing `BODSDataExtractor-1.2/src/BODSDataExtractor/extractor.py` & `BODSDataExtractor-1.2.1/src/BODSDataExtractor/extractor.py`

 * *Files 0% similar despite different names*

```diff
@@ -9,29 +9,28 @@
 import lxml.etree as ET
 import itertools
 from itertools import zip_longest
 from pathlib import Path
 from sys import platform
 import re
 import concurrent.futures
-
 try:
     import BODSDataExtractor.otc_db_download as otc_db_download
 except:
     import otc_db_download
 from datetime import date
 from collections import Counter
 import importlib.resources
 from shapely.geometry import Point
 from geopandas import GeoDataFrame
 import pandas as pd
 from dacite import from_dict
 import xmltodict
 import datetime
-from classes import *
+from BODSDataExtractor.classes import *
 
 
 class TimetableExtractor:
     error_list = []
 
     def __init__(self, api_key, limit=10_000, offset=0, nocs=None, status='published',
                  search=None, bods_compliant=True, atco_code=None, service_line_level=False,
```

### Comparing `BODSDataExtractor-1.2/src/BODSDataExtractor/otc_db_download.py` & `BODSDataExtractor-1.2.1/src/BODSDataExtractor/otc_db_download.py`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/PKG-INFO` & `BODSDataExtractor-1.2.1/src/BODSDataExtractor.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: BODSDataExtractor
-Version: 1.2
+Version: 1.2.1
 Summary: This project was created to lower the barrier to entry for analysis of UK Bus Open Data. It facilitates the fetching and extraction of clean data, currently focussed on Timetables, into tables to be used for analysis or your own projects.
 Author-email: "Ali Partner, Spencer Brittain" <bodshelpdesk@kpmg.co.uk>
 Project-URL: Homepage, https://github.com/department-for-transport-BODS/bods-data-extractor
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.2 Summary: This
+Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.2.1 Summary: This
 project was created to lower the barrier to entry for analysis of UK Bus Open
 Data. It facilitates the fetching and extraction of clean data, currently
 focussed on Timetables, into tables to be used for analysis or your own
 projects. Author-email: "Ali Partner, Spencer Brittain"
 kpmg.co.uk> Project-URL: Homepage, https://github.com/department-for-transport-
 BODS/bods-data-extractor Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License Classifier: Operating System
```

