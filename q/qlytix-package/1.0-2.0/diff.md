# Comparing `tmp/qlytix_package-1.0.tar.gz` & `tmp/qlytix_package-2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "qlytix_package-1.0.tar", last modified: Wed Jun 28 11:38:04 2023, max compression
+gzip compressed data, was "qlytix_package-2.0.tar", last modified: Wed Jun 28 11:41:29 2023, max compression
```

## Comparing `qlytix_package-1.0.tar` & `qlytix_package-2.0.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 11:38:04.875307 qlytix_package-1.0/
--rw-rw-rw-   0        0        0       18 2023-06-28 11:30:35.000000 qlytix_package-1.0/MANIFEST.in
--rw-rw-rw-   0        0        0      300 2023-06-28 11:38:04.872316 qlytix_package-1.0/PKG-INFO
--rw-rw-rw-   0        0        0      150 2023-06-28 11:32:51.000000 qlytix_package-1.0/README.rst
-drwxrwxrwx   0        0        0        0 2023-06-28 11:38:04.834411 qlytix_package-1.0/qlytix_pack/
--rw-rw-rw-   0        0        0      165 2023-06-28 10:54:32.000000 qlytix_package-1.0/qlytix_pack/__init__.py
--rw-rw-rw-   0        0        0    25644 2023-06-28 10:15:45.000000 qlytix_package-1.0/qlytix_pack/datasource.py
--rw-rw-rw-   0        0        0     1292 2023-06-28 06:48:50.000000 qlytix_package-1.0/qlytix_pack/masterdata.py
--rw-rw-rw-   0        0        0    47927 2023-06-28 10:17:51.000000 qlytix_package-1.0/qlytix_pack/user.py
-drwxrwxrwx   0        0        0        0 2023-06-28 11:38:04.869328 qlytix_package-1.0/qlytix_package.egg-info/
--rw-rw-rw-   0        0        0      300 2023-06-28 11:38:04.000000 qlytix_package-1.0/qlytix_package.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      279 2023-06-28 11:38:04.000000 qlytix_package-1.0/qlytix_package.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 11:38:04.000000 qlytix_package-1.0/qlytix_package.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       12 2023-06-28 11:38:04.000000 qlytix_package-1.0/qlytix_package.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 11:38:04.875307 qlytix_package-1.0/setup.cfg
--rw-rw-rw-   0        0        0      397 2023-06-28 11:37:42.000000 qlytix_package-1.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:41:29.441790 qlytix_package-2.0/
+-rw-rw-rw-   0        0        0       18 2023-06-28 11:30:35.000000 qlytix_package-2.0/MANIFEST.in
+-rw-rw-rw-   0        0        0      377 2023-06-28 11:41:29.439794 qlytix_package-2.0/PKG-INFO
+-rw-rw-rw-   0        0        0      227 2023-06-28 11:41:05.000000 qlytix_package-2.0/README.rst
+drwxrwxrwx   0        0        0        0 2023-06-28 11:41:29.414861 qlytix_package-2.0/qlytix_pack/
+-rw-rw-rw-   0        0        0      165 2023-06-28 10:54:32.000000 qlytix_package-2.0/qlytix_pack/__init__.py
+-rw-rw-rw-   0        0        0    25644 2023-06-28 10:15:45.000000 qlytix_package-2.0/qlytix_pack/datasource.py
+-rw-rw-rw-   0        0        0     1292 2023-06-28 06:48:50.000000 qlytix_package-2.0/qlytix_pack/masterdata.py
+-rw-rw-rw-   0        0        0    47927 2023-06-28 10:17:51.000000 qlytix_package-2.0/qlytix_pack/user.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:41:29.437798 qlytix_package-2.0/qlytix_package.egg-info/
+-rw-rw-rw-   0        0        0      377 2023-06-28 11:41:29.000000 qlytix_package-2.0/qlytix_package.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      279 2023-06-28 11:41:29.000000 qlytix_package-2.0/qlytix_package.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 11:41:29.000000 qlytix_package-2.0/qlytix_package.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 11:41:29.000000 qlytix_package-2.0/qlytix_package.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 11:41:29.442786 qlytix_package-2.0/setup.cfg
+-rw-rw-rw-   0        0        0      397 2023-06-28 11:41:15.000000 qlytix_package-2.0/setup.py
```

### Comparing `qlytix_package-1.0/qlytix_pack/datasource.py` & `qlytix_package-2.0/qlytix_pack/datasource.py`

 * *Files identical despite different names*

### Comparing `qlytix_package-1.0/qlytix_pack/masterdata.py` & `qlytix_package-2.0/qlytix_pack/masterdata.py`

 * *Files identical despite different names*

### Comparing `qlytix_package-1.0/qlytix_pack/user.py` & `qlytix_package-2.0/qlytix_pack/user.py`

 * *Files identical despite different names*

