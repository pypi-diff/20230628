# Comparing `tmp/ipo_india-0.0.7.tar.gz` & `tmp/ipo_india-0.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ipo_india-0.0.7.tar", last modified: Wed Jun 28 06:14:02 2023, max compression
+gzip compressed data, was "ipo_india-0.0.8.tar", last modified: Wed Jun 28 06:43:37 2023, max compression
```

## Comparing `ipo_india-0.0.7.tar` & `ipo_india-0.0.8.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:14:02.029928 ipo_india-0.0.7/
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 06:14:02.029928 ipo_india-0.0.7/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:14:02.029928 ipo_india-0.0.7/ipo_india/
--rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1817 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/ipo.py
--rw-r--r--   0 runner    (1001) docker     (123)     5797 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/ipo_scraper.py
--rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-06-28 06:13:53.000000 ipo_india-0.0.7/ipo_india/main.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:14:02.029928 ipo_india-0.0.7/ipo_india.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 06:14:02.000000 ipo_india-0.0.7/ipo_india.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 06:14:01.000000 ipo_india-0.0.7/ipo_india.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 06:14:02.029928 ipo_india-0.0.7/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 06:13:53.000000 ipo_india-0.0.7/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:43:37.477246 ipo_india-0.0.8/
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 06:43:37.477246 ipo_india-0.0.8/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:43:37.473246 ipo_india-0.0.8/ipo_india/
+-rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 06:43:30.000000 ipo_india-0.0.8/ipo_india/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1817 2023-06-28 06:43:30.000000 ipo_india-0.0.8/ipo_india/ipo.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5797 2023-06-28 06:43:30.000000 ipo_india-0.0.8/ipo_india/ipo_scraper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1010 2023-06-28 06:43:30.000000 ipo_india-0.0.8/ipo_india/main.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:43:37.477246 ipo_india-0.0.8/ipo_india.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 06:43:37.000000 ipo_india-0.0.8/ipo_india.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      254 2023-06-28 06:43:37.000000 ipo_india-0.0.8/ipo_india.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:43:37.000000 ipo_india-0.0.8/ipo_india.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 06:43:37.000000 ipo_india-0.0.8/ipo_india.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 06:43:37.000000 ipo_india-0.0.8/ipo_india.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 06:43:37.477246 ipo_india-0.0.8/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      513 2023-06-28 06:43:30.000000 ipo_india-0.0.8/setup.py
```

### Comparing `ipo_india-0.0.7/ipo_india/ipo.py` & `ipo_india-0.0.8/ipo_india/ipo.py`

 * *Files identical despite different names*

### Comparing `ipo_india-0.0.7/ipo_india/ipo_scraper.py` & `ipo_india-0.0.8/ipo_india/ipo_scraper.py`

 * *Files 1% similar despite different names*

```diff
@@ -67,27 +67,27 @@
         qib_subscriptions = []
         rii_subscriptions = []
         ret_subscriptions = []
         total_subscriptions = []
         for row in rows:
             if row.find_all('td'):
                 try:
-                    qib_subscriptions.append(row.find_all('td')[2].text)
+                    qib_subscriptions.append(row.find_all('td')[4].text)
                 except:
                     qib_subscriptions.append("")
                 try:
-                    rii_subscriptions.append(row.find_all('td')[3].text)
+                    rii_subscriptions.append(row.find_all('td')[5].text)
                 except:
                     rii_subscriptions.append("")
                 try:
-                    ret_subscriptions.append(row.find_all('td')[4].text)
+                    ret_subscriptions.append(row.find_all('td')[6].text)
                 except:
                     ret_subscriptions.append("")
                 try:
-                    total_subscriptions.append(row.find_all('td')[5].text)
+                    total_subscriptions.append(row.find_all('td')[7].text)
                 except:
                     total_subscriptions.append("")
 
         ipo_subscriptions = {}
         for name, qib, rii, ret, total in zip(ipo_names, qib_subscriptions, rii_subscriptions, ret_subscriptions, total_subscriptions):
             if name and qib and rii and ret and total:
                 ipo_subscriptions[name] = {'qib': qib, 'rii': rii, 'ret': ret, 'total': total}
```

### Comparing `ipo_india-0.0.7/ipo_india/main.py` & `ipo_india-0.0.8/ipo_india/main.py`

 * *Files identical despite different names*

### Comparing `ipo_india-0.0.7/setup.py` & `ipo_india-0.0.8/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 from setuptools import setup, find_packages
-__version__ = '0.0.7'
+__version__ = '0.0.8'
 setup(
     name='ipo_india',
     version=__version__,
 
     url='https://github.com/MichaelKim0407/tutorial-pip-package',
     author='Aman Agarwal',
     author_email='aman.agarwal150@gmail.com',
```

