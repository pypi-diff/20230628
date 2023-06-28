# Comparing `tmp/ipo_india-0.0.6.tar.gz` & `tmp/ipo_india-0.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ipo_india-0.0.6.tar", last modified: Wed Jun 28 05:54:05 2023, max compression
+gzip compressed data, was "ipo_india-0.0.7.tar", last modified: Wed Jun 28 06:14:02 2023, max compression
```

## Comparing `ipo_india-0.0.6.tar` & `ipo_india-0.0.7.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:54:05.371869 ipo_india-0.0.6/
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 05:54:05.371869 ipo_india-0.0.6/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:54:05.371869 ipo_india-0.0.6/ipo_india/
--rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 05:53:57.000000 ipo_india-0.0.6/ipo_india/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1817 2023-06-28 05:53:57.000000 ipo_india-0.0.6/ipo_india/ipo.py
--rw-r--r--   0 runner    (1001) docker     (123)     5603 2023-06-28 05:53:57.000000 ipo_india-0.0.6/ipo_india/ipo_scraper.py
--rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-06-28 05:53:57.000000 ipo_india-0.0.6/ipo_india/main.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 05:54:05.371869 ipo_india-0.0.6/ipo_india.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 05:54:05.000000 ipo_india-0.0.6/ipo_india.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 05:54:05.000000 ipo_india-0.0.6/ipo_india.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 05:54:05.000000 ipo_india-0.0.6/ipo_india.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 05:54:05.000000 ipo_india-0.0.6/ipo_india.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 05:54:05.000000 ipo_india-0.0.6/ipo_india.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 05:54:05.375869 ipo_india-0.0.6/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 05:53:57.000000 ipo_india-0.0.6/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:14:02.029928 ipo_india-0.0.7/
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 06:14:02.029928 ipo_india-0.0.7/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:14:02.029928 ipo_india-0.0.7/ipo_india/
+-rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1817 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/ipo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5797 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/ipo_scraper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/main.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:14:02.029928 ipo_india-0.0.7/ipo_india.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 06:14:02.000000 ipo_india-0.0.7/ipo_india.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 06:14:02.029928 ipo_india-0.0.7/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 06:13:53.000000 ipo_india-0.0.7/setup.py
```

### Comparing `ipo_india-0.0.6/ipo_india/ipo.py` & `ipo_india-0.0.7/ipo_india/ipo.py`

 * *Files identical despite different names*

### Comparing `ipo_india-0.0.6/ipo_india/ipo_scraper.py` & `ipo_india-0.0.7/ipo_india/ipo_scraper.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,15 @@
     GMP_URL = "https://www.topsharebrokers.com/report/live-ipo-gmp/331/"
     SUBSCRIPTION_URL = "https://www.topsharebrokers.com/report/ipo-subscription-live/333/"
     
     @classmethod
     def _get_ipos_with_gmp(cls):
         rows = cls.__get_report_data_rows(cls.GMP_URL)
 
-        ipo_names = [row.find_all('td')[1].text for row in rows if row.find_all('td')]
+        ipo_names = [row.find_all('td')[0].text for row in rows if row.find_all('td')]
         ipo_open_dates = []
         ipo_close_dates = []
         gmps = []
         ipo_prices = []
         for row in rows:
             if row.find_all('td'):
                 try:
@@ -52,15 +52,22 @@
                 ipos[name] = {'open_date': open_date, 'close_date': close_date, 'gmp': gmp, 'ipo_price': ipo_price}
         return ipos
     
     @classmethod
     def _get_ipos_with_subscription(cls):
         rows = cls.__get_report_data_rows(cls.SUBSCRIPTION_URL)
         
-        ipo_names = [row.find_all('td')[0].text for row in rows if row.find_all('td')]
+        # ipo_names = [row.find_all('td')[1].text for row in rows if row.find_all('td')]
+        ipo_names = []
+        for row in rows:
+          try:
+            if row.find_all('td'):
+              ipo_names.append(row.find_all('td')[1].text)
+          except:
+            pass
         qib_subscriptions = []
         rii_subscriptions = []
         ret_subscriptions = []
         total_subscriptions = []
         for row in rows:
             if row.find_all('td'):
                 try:
```

### Comparing `ipo_india-0.0.6/ipo_india/main.py` & `ipo_india-0.0.7/ipo_india/main.py`

 * *Files identical despite different names*

### Comparing `ipo_india-0.0.6/setup.py` & `ipo_india-0.0.7/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 from setuptools import setup, find_packages
-__version__ = '0.0.6'
+__version__ = '0.0.7'
 setup(
     name='ipo_india',
     version=__version__,
 
     url='https://github.com/MichaelKim0407/tutorial-pip-package',
     author='Aman Agarwal',
     author_email='aman.agarwal150@gmail.com',
```

