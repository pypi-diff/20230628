# Comparing `tmp/psalpsdtools-0.6.tar.gz` & `tmp/psalpsdtools-0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "psalpsdtools-0.6.tar", last modified: Tue Jun 27 12:31:01 2023, max compression
+gzip compressed data, was "psalpsdtools-0.7.tar", last modified: Tue Jun 27 23:38:57 2023, max compression
```

## Comparing `psalpsdtools-0.6.tar` & `psalpsdtools-0.7.tar`

### file list

```diff
@@ -1,15 +1,16 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 12:31:01.025628 psalpsdtools-0.6/
--rw-rw-rw-   0        0        0      214 2023-06-27 12:31:01.025628 psalpsdtools-0.6/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-27 12:31:01.009624 psalpsdtools-0.6/psalpsdtools/
--rw-rw-rw-   0        0        0     7501 2023-06-27 12:28:30.000000 psalpsdtools-0.6/psalpsdtools/Edrw.py
--rw-rw-rw-   0        0        0     3556 2023-06-26 11:33:05.000000 psalpsdtools-0.6/psalpsdtools/PhRegPrv.py
--rw-rw-rw-   0        0        0       54 2023-06-26 11:33:05.000000 psalpsdtools-0.6/psalpsdtools/__init__.py
--rw-rw-rw-   0        0        0      430 2023-06-27 12:28:30.000000 psalpsdtools-0.6/psalpsdtools/usage.py
-drwxrwxrwx   0        0        0        0 2023-06-27 12:31:01.025628 psalpsdtools-0.6/psalpsdtools.egg-info/
--rw-rw-rw-   0        0        0      214 2023-06-27 12:31:00.000000 psalpsdtools-0.6/psalpsdtools.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      290 2023-06-27 12:31:00.000000 psalpsdtools-0.6/psalpsdtools.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 12:31:00.000000 psalpsdtools-0.6/psalpsdtools.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        2 2023-06-27 12:31:00.000000 psalpsdtools-0.6/psalpsdtools.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0       13 2023-06-27 12:31:00.000000 psalpsdtools-0.6/psalpsdtools.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 12:31:01.025628 psalpsdtools-0.6/setup.cfg
--rw-rw-rw-   0        0        0      220 2023-06-27 12:28:30.000000 psalpsdtools-0.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-27 23:38:57.921017 psalpsdtools-0.7/
+-rw-rw-rw-   0        0        0     1802 2023-06-27 23:38:57.921017 psalpsdtools-0.7/PKG-INFO
+-rw-rw-rw-   0        0        0     1175 2023-06-27 23:21:24.000000 psalpsdtools-0.7/README.md
+drwxrwxrwx   0        0        0        0 2023-06-27 23:38:57.914019 psalpsdtools-0.7/psalpsdtools/
+-rw-rw-rw-   0        0        0     7501 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/Edrw.py
+-rw-rw-rw-   0        0        0     3556 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/PhRegPrv.py
+-rw-rw-rw-   0        0        0       54 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/__init__.py
+-rw-rw-rw-   0        0        0      430 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/usage.py
+drwxrwxrwx   0        0        0        0 2023-06-27 23:38:57.919011 psalpsdtools-0.7/psalpsdtools.egg-info/
+-rw-rw-rw-   0        0        0     1802 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      300 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        2 2023-06-27 23:30:13.000000 psalpsdtools-0.7/psalpsdtools.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0       13 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-27 23:38:57.921017 psalpsdtools-0.7/setup.cfg
+-rw-rw-rw-   0        0        0      423 2023-06-27 23:38:55.000000 psalpsdtools-0.7/setup.py
```

### Comparing `psalpsdtools-0.6/psalpsdtools/Edrw.py` & `psalpsdtools-0.7/psalpsdtools/Edrw.py`

 * *Files identical despite different names*

### Comparing `psalpsdtools-0.6/psalpsdtools/PhRegPrv.py` & `psalpsdtools-0.7/psalpsdtools/PhRegPrv.py`

 * *Files identical despite different names*

