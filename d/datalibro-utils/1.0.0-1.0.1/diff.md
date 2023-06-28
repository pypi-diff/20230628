# Comparing `tmp/datalibro_utils-1.0.0.tar.gz` & `tmp/datalibro_utils-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "datalibro_utils-1.0.0.tar", last modified: Wed Jun 21 02:51:54 2023, max compression
+gzip compressed data, was "datalibro_utils-1.0.1.tar", last modified: Wed Jun 28 06:23:41 2023, max compression
```

## Comparing `datalibro_utils-1.0.0.tar` & `datalibro_utils-1.0.1.tar`

### file list

```diff
@@ -1,14 +1,15 @@
-drwxr-xr-x   0 livid      (501) staff       (20)        0 2023-06-21 02:51:54.415516 datalibro_utils-1.0.0/
--rw-r--r--   0 livid      (501) staff       (20)      194 2023-06-21 02:51:54.415404 datalibro_utils-1.0.0/PKG-INFO
--rw-r--r--   0 livid      (501) staff       (20)       54 2023-06-21 02:26:49.000000 datalibro_utils-1.0.0/README.md
-drwxr-xr-x   0 livid      (501) staff       (20)        0 2023-06-21 02:51:54.414437 datalibro_utils-1.0.0/datalibro_utils/
--rw-r--r--   0 livid      (501) staff       (20)       49 2023-06-21 02:03:49.000000 datalibro_utils-1.0.0/datalibro_utils/__init__.py
--rw-r--r--   0 livid      (501) staff       (20)     2828 2023-06-21 02:19:56.000000 datalibro_utils-1.0.0/datalibro_utils/mapping.py
-drwxr-xr-x   0 livid      (501) staff       (20)        0 2023-06-21 02:51:54.415245 datalibro_utils-1.0.0/datalibro_utils.egg-info/
--rw-r--r--   0 livid      (501) staff       (20)      194 2023-06-21 02:51:54.000000 datalibro_utils-1.0.0/datalibro_utils.egg-info/PKG-INFO
--rw-r--r--   0 livid      (501) staff       (20)      267 2023-06-21 02:51:54.000000 datalibro_utils-1.0.0/datalibro_utils.egg-info/SOURCES.txt
--rw-r--r--   0 livid      (501) staff       (20)        1 2023-06-21 02:51:54.000000 datalibro_utils-1.0.0/datalibro_utils.egg-info/dependency_links.txt
--rw-r--r--   0 livid      (501) staff       (20)       19 2023-06-21 02:51:54.000000 datalibro_utils-1.0.0/datalibro_utils.egg-info/requires.txt
--rw-r--r--   0 livid      (501) staff       (20)       16 2023-06-21 02:51:54.000000 datalibro_utils-1.0.0/datalibro_utils.egg-info/top_level.txt
--rw-r--r--   0 livid      (501) staff       (20)       38 2023-06-21 02:51:54.415553 datalibro_utils-1.0.0/setup.cfg
--rw-r--r--   0 livid      (501) staff       (20)      358 2023-06-21 02:49:36.000000 datalibro_utils-1.0.0/setup.py
+drwxr-xr-x   0 livid      (501) staff       (20)        0 2023-06-28 06:23:41.665716 datalibro_utils-1.0.1/
+-rw-r--r--   0 livid      (501) staff       (20)      194 2023-06-28 06:23:41.665572 datalibro_utils-1.0.1/PKG-INFO
+-rw-r--r--   0 livid      (501) staff       (20)      431 2023-06-21 03:09:04.000000 datalibro_utils-1.0.1/README.md
+drwxr-xr-x   0 livid      (501) staff       (20)        0 2023-06-28 06:23:41.664641 datalibro_utils-1.0.1/datalibro_utils/
+-rw-r--r--   0 livid      (501) staff       (20)       69 2023-06-28 06:17:23.000000 datalibro_utils-1.0.1/datalibro_utils/__init__.py
+-rw-r--r--   0 livid      (501) staff       (20)     2828 2023-06-21 02:19:56.000000 datalibro_utils-1.0.1/datalibro_utils/mapping.py
+-rw-r--r--   0 livid      (501) staff       (20)       80 2023-06-28 06:14:01.000000 datalibro_utils-1.0.1/datalibro_utils/test.py
+drwxr-xr-x   0 livid      (501) staff       (20)        0 2023-06-28 06:23:41.665398 datalibro_utils-1.0.1/datalibro_utils.egg-info/
+-rw-r--r--   0 livid      (501) staff       (20)      194 2023-06-28 06:23:41.000000 datalibro_utils-1.0.1/datalibro_utils.egg-info/PKG-INFO
+-rw-r--r--   0 livid      (501) staff       (20)      291 2023-06-28 06:23:41.000000 datalibro_utils-1.0.1/datalibro_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 livid      (501) staff       (20)        1 2023-06-28 06:23:41.000000 datalibro_utils-1.0.1/datalibro_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 livid      (501) staff       (20)       19 2023-06-28 06:23:41.000000 datalibro_utils-1.0.1/datalibro_utils.egg-info/requires.txt
+-rw-r--r--   0 livid      (501) staff       (20)       16 2023-06-28 06:23:41.000000 datalibro_utils-1.0.1/datalibro_utils.egg-info/top_level.txt
+-rw-r--r--   0 livid      (501) staff       (20)       38 2023-06-28 06:23:41.665776 datalibro_utils-1.0.1/setup.cfg
+-rw-r--r--   0 livid      (501) staff       (20)      358 2023-06-28 06:22:59.000000 datalibro_utils-1.0.1/setup.py
```

### Comparing `datalibro_utils-1.0.0/datalibro_utils/mapping.py` & `datalibro_utils-1.0.1/datalibro_utils/mapping.py`

 * *Files identical despite different names*

