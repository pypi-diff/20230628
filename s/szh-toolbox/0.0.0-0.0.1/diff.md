# Comparing `tmp/szh_toolbox-0.0.0.tar.gz` & `tmp/szh_toolbox-0.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "szh_toolbox-0.0.0.tar", last modified: Wed Jun 28 07:23:26 2023, max compression
+gzip compressed data, was "szh_toolbox-0.0.1.tar", last modified: Wed Jun 28 08:10:15 2023, max compression
```

## Comparing `szh_toolbox-0.0.0.tar` & `szh_toolbox-0.0.1.tar`

### file list

```diff
@@ -1,16 +1,15 @@
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 07:23:26.626559 szh_toolbox-0.0.0/
--rw-rw-r--   0 szh       (1003) szh       (1003)        0 2023-06-28 07:16:19.000000 szh_toolbox-0.0.0/LICENSE
--rw-rw-r--   0 szh       (1003) szh       (1003)      492 2023-06-28 07:23:26.626559 szh_toolbox-0.0.0/PKG-INFO
--rw-rw-r--   0 szh       (1003) szh       (1003)        0 2023-06-28 07:20:32.000000 szh_toolbox-0.0.0/README.md
--rw-rw-r--   0 szh       (1003) szh       (1003)       84 2023-06-28 07:19:11.000000 szh_toolbox-0.0.0/pyproject.toml
--rw-rw-r--   0 szh       (1003) szh       (1003)       38 2023-06-28 07:23:26.626559 szh_toolbox-0.0.0/setup.cfg
--rw-rw-r--   0 szh       (1003) szh       (1003)      791 2023-06-28 07:23:10.000000 szh_toolbox-0.0.0/setup.py
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 07:23:26.623559 szh_toolbox-0.0.0/src/
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 07:23:26.625559 szh_toolbox-0.0.0/src/szh_toolbox/
--rw-rw-r--   0 szh       (1003) szh       (1003)       67 2023-06-28 07:17:28.000000 szh_toolbox-0.0.0/src/szh_toolbox/__init__.py
--rw-rw-r--   0 szh       (1003) szh       (1003)       67 2023-06-28 07:18:07.000000 szh_toolbox-0.0.0/src/szh_toolbox/test.py
-drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 07:23:26.625559 szh_toolbox-0.0.0/src/szh_toolbox.egg-info/
--rw-rw-r--   0 szh       (1003) szh       (1003)      492 2023-06-28 07:23:26.000000 szh_toolbox-0.0.0/src/szh_toolbox.egg-info/PKG-INFO
--rw-rw-r--   0 szh       (1003) szh       (1003)      249 2023-06-28 07:23:26.000000 szh_toolbox-0.0.0/src/szh_toolbox.egg-info/SOURCES.txt
--rw-rw-r--   0 szh       (1003) szh       (1003)        1 2023-06-28 07:23:26.000000 szh_toolbox-0.0.0/src/szh_toolbox.egg-info/dependency_links.txt
--rw-rw-r--   0 szh       (1003) szh       (1003)       12 2023-06-28 07:23:26.000000 szh_toolbox-0.0.0/src/szh_toolbox.egg-info/top_level.txt
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/
+-rw-rw-r--   0 szh       (1003) szh       (1003)     1073 2023-06-28 08:01:22.000000 szh_toolbox-0.0.1/LICENSE
+-rw-rw-r--   0 szh       (1003) szh       (1003)      501 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/PKG-INFO
+-rw-rw-r--   0 szh       (1003) szh       (1003)        0 2023-06-28 07:20:32.000000 szh_toolbox-0.0.1/README.md
+-rw-rw-r--   0 szh       (1003) szh       (1003)      573 2023-06-28 08:09:45.000000 szh_toolbox-0.0.1/pyproject.toml
+-rw-rw-r--   0 szh       (1003) szh       (1003)       38 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/setup.cfg
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.277653 szh_toolbox-0.0.1/src/
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.277653 szh_toolbox-0.0.1/src/szh_toolbox/
+-rw-rw-r--   0 szh       (1003) szh       (1003)       67 2023-06-28 07:17:28.000000 szh_toolbox-0.0.1/src/szh_toolbox/__init__.py
+-rw-rw-r--   0 szh       (1003) szh       (1003)       67 2023-06-28 07:18:07.000000 szh_toolbox-0.0.1/src/szh_toolbox/test.py
+drwxrwxr-x   0 szh       (1003) szh       (1003)        0 2023-06-28 08:10:15.278653 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/
+-rw-rw-r--   0 szh       (1003) szh       (1003)      501 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/PKG-INFO
+-rw-rw-r--   0 szh       (1003) szh       (1003)      240 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/SOURCES.txt
+-rw-rw-r--   0 szh       (1003) szh       (1003)        1 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/dependency_links.txt
+-rw-rw-r--   0 szh       (1003) szh       (1003)       12 2023-06-28 08:10:15.000000 szh_toolbox-0.0.1/src/szh_toolbox.egg-info/top_level.txt
```

