# Comparing `tmp/trimnet-1.0.4.tar.gz` & `tmp/trimnet-1.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "trimnet-1.0.4.tar", last modified: Mon Jun 26 22:27:42 2023, max compression
+gzip compressed data, was "trimnet-1.0.5.tar", last modified: Wed Jun 28 00:24:16 2023, max compression
```

## Comparing `trimnet-1.0.4.tar` & `trimnet-1.0.5.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 22:27:42.419426 trimnet-1.0.4/
--rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-06-26 22:27:12.000000 trimnet-1.0.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      125 2023-06-26 22:27:42.419426 trimnet-1.0.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2458 2023-06-26 22:27:12.000000 trimnet-1.0.4/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 22:27:42.419426 trimnet-1.0.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-26 22:27:12.000000 trimnet-1.0.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 22:27:42.419426 trimnet-1.0.4/trimnet.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      125 2023-06-26 22:27:42.000000 trimnet-1.0.4/trimnet.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      205 2023-06-26 22:27:42.000000 trimnet-1.0.4/trimnet.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 22:27:42.000000 trimnet-1.0.4/trimnet.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       82 2023-06-26 22:27:42.000000 trimnet-1.0.4/trimnet.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-26 22:27:42.000000 trimnet-1.0.4/trimnet.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 22:27:42.419426 trimnet-1.0.4/trimnet_drug/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 22:27:12.000000 trimnet-1.0.4/trimnet_drug/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:24:16.613780 trimnet-1.0.5/
+-rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-06-28 00:23:46.000000 trimnet-1.0.5/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      125 2023-06-28 00:24:16.613780 trimnet-1.0.5/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2458 2023-06-28 00:23:46.000000 trimnet-1.0.5/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 00:24:16.613780 trimnet-1.0.5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-28 00:24:12.000000 trimnet-1.0.5/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:24:16.613780 trimnet-1.0.5/trimnet.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      125 2023-06-28 00:24:16.000000 trimnet-1.0.5/trimnet.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      205 2023-06-28 00:24:16.000000 trimnet-1.0.5/trimnet.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 00:24:16.000000 trimnet-1.0.5/trimnet.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 00:24:16.000000 trimnet-1.0.5/trimnet.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 00:24:16.000000 trimnet-1.0.5/trimnet.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 00:24:16.613780 trimnet-1.0.5/trimnet_drug/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 00:23:46.000000 trimnet-1.0.5/trimnet_drug/__init__.py
```

### Comparing `trimnet-1.0.4/LICENSE` & `trimnet-1.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `trimnet-1.0.4/README.md` & `trimnet-1.0.5/README.md`

 * *Files identical despite different names*

