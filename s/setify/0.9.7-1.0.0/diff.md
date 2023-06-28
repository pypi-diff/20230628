# Comparing `tmp/setify-0.9.7.tar.gz` & `tmp/setify-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "setify-0.9.7.tar", last modified: Fri Apr 28 17:03:03 2023, max compression
+gzip compressed data, was "setify-1.0.0.tar", last modified: Wed Jun 28 13:00:31 2023, max compression
```

## Comparing `setify-0.9.7.tar` & `setify-1.0.0.tar`

### file list

```diff
@@ -1,8 +1,8 @@
-drwxr-xr-x   0 mina       (501) staff       (20)        0 2023-04-28 17:03:03.631495 setify-0.9.7/
--rw-r--r--   0 mina       (501) staff       (20)      933 2023-04-28 17:03:03.631605 setify-0.9.7/PKG-INFO
-drwxr-xr-x   0 mina       (501) staff       (20)        0 2023-04-28 17:03:03.631445 setify-0.9.7/setify/
--rw-r--r--   0 mina       (501) staff       (20)       66 2023-04-28 17:00:49.030141 setify-0.9.7/setify/__init__.py
--rw-r--r--   0 mina       (501) staff       (20)     3628 2023-04-28 16:54:07.590625 setify-0.9.7/setify/datasets.py
--rw-r--r--   0 mina       (501) staff       (20)     3334 2023-04-28 16:53:21.208739 setify-0.9.7/setify/utils.py
--rw-r--r--   0 mina       (501) staff       (20)       61 2023-04-28 16:53:21.208820 setify-0.9.7/setup.cfg
--rw-r--r--   0 mina       (501) staff       (20)     1244 2023-04-28 17:02:07.190902 setify-0.9.7/setup.py
+drwxr-xr-x   0 minagabriel   (501) staff       (20)        0 2023-06-28 13:00:31.867102 setify-1.0.0/
+-rw-r--r--   0 minagabriel   (501) staff       (20)      933 2023-06-28 13:00:31.867382 setify-1.0.0/PKG-INFO
+drwxr-xr-x   0 minagabriel   (501) staff       (20)        0 2023-06-28 13:00:31.866980 setify-1.0.0/setify/
+-rw-r--r--   0 minagabriel   (501) staff       (20)       66 2023-06-28 13:00:03.948629 setify-1.0.0/setify/__init__.py
+-rw-r--r--   0 minagabriel   (501) staff       (20)     2035 2023-06-28 12:38:24.914074 setify-1.0.0/setify/datasets.py
+-rw-r--r--   0 minagabriel   (501) staff       (20)     3334 2023-06-28 11:39:50.448823 setify-1.0.0/setify/utils.py
+-rw-r--r--   0 minagabriel   (501) staff       (20)       61 2023-06-28 11:39:50.448963 setify-1.0.0/setup.cfg
+-rw-r--r--   0 minagabriel   (501) staff       (20)     1244 2023-06-28 12:59:23.761554 setify-1.0.0/setup.py
```

### Comparing `setify-0.9.7/PKG-INFO` & `setify-1.0.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 1.1
 Name: setify
-Version: 0.9.7
+Version: 1.0.0
 Summary: Dataset packages
 Home-page: https://github.com/MinaGabriel/setify.git
 Author: Mina Gabriel
 Author-email: developer.mina@gmail.com
 License: MIT
-Download-URL: https://github.com/MinaGabriel/setify/archive/refs/tags/v0.9.7.tar.gz
+Download-URL: https://github.com/MinaGabriel/setify/archive/refs/tags/v1.0.0.tar.gz
 Description: Setify is an open-source dataset package manager written in Python and designed to enable fast experimentation for Machine Learning, Setify allows you to reach hundreds of datasets with one command.
 Keywords: Dataset,Data
 Platform: UNKNOWN
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Build Tools
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `setify-0.9.7/setify/datasets.py` & `setify-1.0.0/setify/datasets.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,23 +1,15 @@
-import json
-import urllib.request
 import pandas as pd
 from setify import utils
 
 
 
 def _get_server():
-    #return 'https://setify-server.herokuapp.com'
-    return 'http://159.223.176.152:5000'
-
-
-def hazardous_materials():
-    fpath = utils.load_data(
-        _get_server() + "/hazardous_materials", 'hazardous_materials.h5')
-    return pd.read_hdf(fpath)
+    # return 'https://setify-server.herokuapp.com'
+    return 'http://159.223.176.152:8080'
 
 
 def walmart_store_location():
     fpath = utils.load_data(
         _get_server() + "/walmart_store_location", 'walmart_store_location.h5')
     return pd.read_hdf(fpath)
 
@@ -29,48 +21,26 @@
 
 
 def titanic():
     fpath = utils.load_data(_get_server() + "/titanic", 'titanic.h5')
     return pd.read_hdf(fpath)
 
 
-def netflix_titles():
-    fpath = utils.load_data(
-        _get_server() + "/netflix_titles", 'netflix_titles.h5')
-    return pd.read_hdf(fpath)
-
 
 def wine_quality():
     fpath = utils.load_data(_get_server() + "/wine_quality", 'wine_quality.h5')
     return pd.read_hdf(fpath)
 
 
-def country_birth_rate():
-    fpath = utils.load_data(
-        _get_server() + "/country_birth_rate", 'country_birth_rate.h5')
-    return pd.read_hdf(fpath)
-
-
-def country_death_rate():
-    fpath = utils.load_data(
-        _get_server() + "/country_death_rate", 'country_death_rate.h5')
-    return pd.read_hdf(fpath)
-
 
 def iris():
     fpath = utils.load_data(_get_server() + "/iris", 'iris.h5')
     return pd.read_hdf(fpath)
 
 
-def country_name_code():
-    fpath = utils.load_data(
-        _get_server() + "/country_name_code", 'country_name_code.h5')
-    return pd.read_hdf(fpath)
-
-
 def logic_gate_not():
     fpath = utils.load_data(
         _get_server() + "/logic_gate_not", 'logic_gate_not.h5')
     return pd.read_hdf(fpath)
 
 
 def logic_gate_and():
@@ -105,40 +75,11 @@
 
 def logic_gate_xnor():
     fpath = utils.load_data(
         _get_server() + "/logic_gate_xnor", 'logic_gate_xnor.h5')
     return pd.read_hdf(fpath)
 
 
-def temperatures_daily_min():
-    fpath = utils.load_data(
-        _get_server() + "/temperatures_daily_min", 'temperatures_daily_min.h5')
-    return pd.read_hdf(fpath)
-
-
-def shampoo_sales():
-    fpath = utils.load_data(
-        _get_server() + "/shampoo_sales", 'shampoo_sales.h5')
-    return pd.read_hdf(fpath)
-
-
-def monthly_sunspot():
-    fpath = utils.load_data(
-        _get_server() + "/monthly_sunspot", 'monthly_sunspot.h5')
-    return pd.read_hdf(fpath)
-
-
-def daily_female_births():
-    fpath = utils.load_data(
-        _get_server() + "/daily_female_births", 'daily_female_births.h5')
-    return pd.read_hdf(fpath)
-
-
-def occupancy_detection():
-    fpath = utils.load_data(
-        _get_server() + "/occupancy_detection", 'occupancy_detection.h5')
-    return pd.read_hdf(fpath)
-
-def superheroes():
+def boston_housing():
     fpath = utils.load_data(
-        _get_server() + "/superheroes", 'superheroes.h5')
+        _get_server() + "/boston_housing", 'boston_housing.h5')
     return pd.read_hdf(fpath)
```

### Comparing `setify-0.9.7/setify/utils.py` & `setify-1.0.0/setify/utils.py`

 * *Files identical despite different names*

### Comparing `setify-0.9.7/setup.py` & `setify-1.0.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 from distutils.core import setup
 
 setup(
     name='setify',
     packages=['setify'],
-    version='0.9.7',
+    version='1.0.0',
     license='MIT',
     description='Dataset packages',
     author='Mina Gabriel',
     author_email='developer.mina@gmail.com',
     url='https://github.com/MinaGabriel/setify.git',
-    download_url='https://github.com/MinaGabriel/setify/archive/refs/tags/v0.9.7.tar.gz',
+    download_url='https://github.com/MinaGabriel/setify/archive/refs/tags/v1.0.0.tar.gz',
     keywords=['Dataset', 'Data'],
     install_requires=[
         'pandas',
         'numpy',
         'tqdm',
         'colorama',
         'tables'
```

