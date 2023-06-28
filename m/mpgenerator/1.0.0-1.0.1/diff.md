# Comparing `tmp/mpgenerator-1.0.0.tar.gz` & `tmp/mpgenerator-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mpgenerator-1.0.0.tar", last modified: Tue Jun 27 14:56:03 2023, max compression
+gzip compressed data, was "mpgenerator-1.0.1.tar", last modified: Wed Jun 28 11:16:04 2023, max compression
```

## Comparing `mpgenerator-1.0.0.tar` & `mpgenerator-1.0.1.tar`

### file list

```diff
@@ -1,9 +1,9 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 14:56:03.026736 mpgenerator-1.0.0/
--rw-rw-rw-   0        0        0      128 2023-06-27 14:56:03.025720 mpgenerator-1.0.0/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-27 14:56:03.020721 mpgenerator-1.0.0/mpgenerator.egg-info/
--rw-rw-rw-   0        0        0      128 2023-06-27 14:56:02.000000 mpgenerator-1.0.0/mpgenerator.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      148 2023-06-27 14:56:02.000000 mpgenerator-1.0.0/mpgenerator.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 14:56:02.000000 mpgenerator-1.0.0/mpgenerator.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 14:56:02.000000 mpgenerator-1.0.0/mpgenerator.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 14:56:03.027722 mpgenerator-1.0.0/setup.cfg
--rw-rw-rw-   0        0        0      229 2023-06-27 14:53:48.000000 mpgenerator-1.0.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:16:04.364760 mpgenerator-1.0.1/
+-rw-rw-rw-   0        0        0      128 2023-06-28 11:16:04.363755 mpgenerator-1.0.1/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 11:16:04.361715 mpgenerator-1.0.1/mpgenerator.egg-info/
+-rw-rw-rw-   0        0        0      128 2023-06-28 11:16:04.000000 mpgenerator-1.0.1/mpgenerator.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      148 2023-06-28 11:16:04.000000 mpgenerator-1.0.1/mpgenerator.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 11:16:04.000000 mpgenerator-1.0.1/mpgenerator.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 11:16:04.000000 mpgenerator-1.0.1/mpgenerator.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 11:16:04.366034 mpgenerator-1.0.1/setup.cfg
+-rw-rw-rw-   0        0        0      229 2023-06-28 11:14:13.000000 mpgenerator-1.0.1/setup.py
```

