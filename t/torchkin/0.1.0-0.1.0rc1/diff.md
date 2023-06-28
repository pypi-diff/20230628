# Comparing `tmp/torchkin-0.1.0.tar.gz` & `tmp/torchkin-0.1.0rc1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "torchkin-0.1.0.tar", last modified: Wed Jun 28 01:56:48 2023, max compression
+gzip compressed data, was "torchkin-0.1.0rc1.tar", last modified: Mon Jun 26 20:48:03 2023, max compression
```

## Comparing `torchkin-0.1.0.tar` & `torchkin-0.1.0rc1.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-28 01:56:48.231841 torchkin-0.1.0/
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1088 2023-06-27 18:16:27.000000 torchkin-0.1.0/LICENSE
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       68 2023-06-27 18:16:27.000000 torchkin-0.1.0/MANIFEST.in
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     6018 2023-06-28 01:56:48.230418 torchkin-0.1.0/PKG-INFO
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     5474 2023-06-28 01:10:53.000000 torchkin-0.1.0/README.md
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       31 2023-06-27 18:16:27.000000 torchkin-0.1.0/requirements.txt
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       38 2023-06-28 01:56:48.232922 torchkin-0.1.0/setup.cfg
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1397 2023-06-27 18:16:27.000000 torchkin-0.1.0/setup.py
-drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-28 01:56:48.206172 torchkin-0.1.0/torchkin/
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      286 2023-06-28 01:54:15.000000 torchkin-0.1.0/torchkin/__init__.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     6074 2023-06-27 18:16:27.000000 torchkin-0.1.0/torchkin/forward_kinematics.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    15460 2023-06-27 18:16:27.000000 torchkin-0.1.0/torchkin/joint.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     8686 2023-06-27 18:16:27.000000 torchkin-0.1.0/torchkin/robot.py
-drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-28 01:56:48.225247 torchkin-0.1.0/torchkin.egg-info/
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     6018 2023-06-28 01:56:48.000000 torchkin-0.1.0/torchkin.egg-info/PKG-INFO
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      302 2023-06-28 01:56:48.000000 torchkin-0.1.0/torchkin.egg-info/SOURCES.txt
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        1 2023-06-28 01:56:48.000000 torchkin-0.1.0/torchkin.egg-info/dependency_links.txt
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       31 2023-06-28 01:56:48.000000 torchkin-0.1.0/torchkin.egg-info/requires.txt
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        9 2023-06-28 01:56:48.000000 torchkin-0.1.0/torchkin.egg-info/top_level.txt
+drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-26 20:48:03.626120 torchkin-0.1.0rc1/
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1088 2023-06-26 20:17:33.000000 torchkin-0.1.0rc1/LICENSE
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       68 2023-06-26 20:47:55.000000 torchkin-0.1.0rc1/MANIFEST.in
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     2001 2023-06-26 20:48:03.624754 torchkin-0.1.0rc1/PKG-INFO
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1454 2023-06-26 19:49:48.000000 torchkin-0.1.0rc1/README.md
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       31 2023-06-26 19:57:23.000000 torchkin-0.1.0rc1/requirements.txt
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       38 2023-06-26 20:48:03.627099 torchkin-0.1.0rc1/setup.cfg
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1397 2023-06-26 20:47:04.000000 torchkin-0.1.0rc1/setup.py
+drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-26 20:48:03.600827 torchkin-0.1.0rc1/torchkin/
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      289 2023-06-26 20:26:45.000000 torchkin-0.1.0rc1/torchkin/__init__.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     6074 2023-06-26 19:42:33.000000 torchkin-0.1.0rc1/torchkin/forward_kinematics.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    15460 2023-06-26 20:21:58.000000 torchkin-0.1.0rc1/torchkin/joint.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     8686 2023-06-26 20:21:58.000000 torchkin-0.1.0rc1/torchkin/robot.py
+drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-26 20:48:03.620464 torchkin-0.1.0rc1/torchkin.egg-info/
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     2001 2023-06-26 20:48:03.000000 torchkin-0.1.0rc1/torchkin.egg-info/PKG-INFO
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      302 2023-06-26 20:48:03.000000 torchkin-0.1.0rc1/torchkin.egg-info/SOURCES.txt
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        1 2023-06-26 20:48:03.000000 torchkin-0.1.0rc1/torchkin.egg-info/dependency_links.txt
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       31 2023-06-26 20:48:03.000000 torchkin-0.1.0rc1/torchkin.egg-info/requires.txt
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        9 2023-06-26 20:48:03.000000 torchkin-0.1.0rc1/torchkin.egg-info/top_level.txt
```

### Comparing `torchkin-0.1.0/LICENSE` & `torchkin-0.1.0rc1/LICENSE`

 * *Files identical despite different names*

### Comparing `torchkin-0.1.0/setup.py` & `torchkin-0.1.0rc1/setup.py`

 * *Files identical despite different names*

### Comparing `torchkin-0.1.0/torchkin/forward_kinematics.py` & `torchkin-0.1.0rc1/torchkin/forward_kinematics.py`

 * *Files identical despite different names*

### Comparing `torchkin-0.1.0/torchkin/joint.py` & `torchkin-0.1.0rc1/torchkin/joint.py`

 * *Files identical despite different names*

### Comparing `torchkin-0.1.0/torchkin/robot.py` & `torchkin-0.1.0rc1/torchkin/robot.py`

 * *Files identical despite different names*

