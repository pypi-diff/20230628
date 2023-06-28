# Comparing `tmp/receptive_field_calculation-0.0.0.dev0.tar.gz` & `tmp/receptive_field_calculation-0.0.0.dev1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "receptive_field_calculation-0.0.0.dev0.tar", last modified: Wed Jun 28 08:54:41 2023, max compression
+gzip compressed data, was "receptive_field_calculation-0.0.0.dev1.tar", last modified: Wed Jun 28 09:01:30 2023, max compression
```

## Comparing `receptive_field_calculation-0.0.0.dev0.tar` & `receptive_field_calculation-0.0.0.dev1.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 08:54:41.578855 receptive_field_calculation-0.0.0.dev0/
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      622 2023-06-28 08:54:41.578855 receptive_field_calculation-0.0.0.dev0/PKG-INFO
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      202 2023-06-28 07:36:10.000000 receptive_field_calculation-0.0.0.dev0/ReadMe.md
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      595 2023-06-28 08:54:14.000000 receptive_field_calculation-0.0.0.dev0/pyproject.toml
-drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 08:54:41.578855 receptive_field_calculation-0.0.0.dev0/receptive_field_calculation.egg-info/
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      622 2023-06-28 08:54:41.000000 receptive_field_calculation-0.0.0.dev0/receptive_field_calculation.egg-info/PKG-INFO
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      341 2023-06-28 08:54:41.000000 receptive_field_calculation-0.0.0.dev0/receptive_field_calculation.egg-info/SOURCES.txt
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)        1 2023-06-28 08:54:41.000000 receptive_field_calculation-0.0.0.dev0/receptive_field_calculation.egg-info/dependency_links.txt
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)       28 2023-06-28 08:54:41.000000 receptive_field_calculation-0.0.0.dev0/receptive_field_calculation.egg-info/requires.txt
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)        8 2023-06-28 08:54:41.000000 receptive_field_calculation-0.0.0.dev0/receptive_field_calculation.egg-info/top_level.txt
-drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 08:54:41.578855 receptive_field_calculation-0.0.0.dev0/rf_calc/
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)       59 2023-06-28 07:44:00.000000 receptive_field_calculation-0.0.0.dev0/rf_calc/__init__.py
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)     1142 2023-06-28 07:14:08.000000 receptive_field_calculation-0.0.0.dev0/rf_calc/search_rf.py
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)       38 2023-06-28 08:54:41.578855 receptive_field_calculation-0.0.0.dev0/setup.cfg
-drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 08:54:41.578855 receptive_field_calculation-0.0.0.dev0/tests/
--rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      540 2023-06-28 07:16:10.000000 receptive_field_calculation-0.0.0.dev0/tests/test_example.py
+drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 09:01:30.371359 receptive_field_calculation-0.0.0.dev1/
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      622 2023-06-28 09:01:30.371359 receptive_field_calculation-0.0.0.dev1/PKG-INFO
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      202 2023-06-28 07:36:10.000000 receptive_field_calculation-0.0.0.dev1/ReadMe.md
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      595 2023-06-28 09:01:16.000000 receptive_field_calculation-0.0.0.dev1/pyproject.toml
+drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 09:01:30.371359 receptive_field_calculation-0.0.0.dev1/receptive_field_calculation.egg-info/
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      622 2023-06-28 09:01:30.000000 receptive_field_calculation-0.0.0.dev1/receptive_field_calculation.egg-info/PKG-INFO
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      341 2023-06-28 09:01:30.000000 receptive_field_calculation-0.0.0.dev1/receptive_field_calculation.egg-info/SOURCES.txt
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)        1 2023-06-28 09:01:30.000000 receptive_field_calculation-0.0.0.dev1/receptive_field_calculation.egg-info/dependency_links.txt
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)       28 2023-06-28 09:01:30.000000 receptive_field_calculation-0.0.0.dev1/receptive_field_calculation.egg-info/requires.txt
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)        8 2023-06-28 09:01:30.000000 receptive_field_calculation-0.0.0.dev1/receptive_field_calculation.egg-info/top_level.txt
+drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 09:01:30.371359 receptive_field_calculation-0.0.0.dev1/rf_calc/
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)       59 2023-06-28 09:01:20.000000 receptive_field_calculation-0.0.0.dev1/rf_calc/__init__.py
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)     1142 2023-06-28 07:14:08.000000 receptive_field_calculation-0.0.0.dev1/rf_calc/search_rf.py
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)       38 2023-06-28 09:01:30.371359 receptive_field_calculation-0.0.0.dev1/setup.cfg
+drwxrwxr-x   0 zhangyi   (1001) zhangyi   (1002)        0 2023-06-28 09:01:30.371359 receptive_field_calculation-0.0.0.dev1/tests/
+-rw-rw-r--   0 zhangyi   (1001) zhangyi   (1002)      540 2023-06-28 07:16:10.000000 receptive_field_calculation-0.0.0.dev1/tests/test_example.py
```

### Comparing `receptive_field_calculation-0.0.0.dev0/pyproject.toml` & `receptive_field_calculation-0.0.0.dev1/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -14,12 +14,12 @@
     "Development Status :: 2 - Pre-Alpha",
     "Programming Language :: Python :: 3",
 ]
 dependencies = [
     "numpy>=1.24.3",
     "torch>=1.13.0"
 ]
-version = "0.0.0.dev0"
+version = "0.0.0.dev1"
 license = {text = "MIT License"}
 
 [project.urls]
-Homepage = "https://gitee.com/ease-zh/rf_calc"
+Homepage = "https://gitee.com/ease_zh/rf_calc"
```

### Comparing `receptive_field_calculation-0.0.0.dev0/rf_calc/search_rf.py` & `receptive_field_calculation-0.0.0.dev1/rf_calc/search_rf.py`

 * *Files identical despite different names*

### Comparing `receptive_field_calculation-0.0.0.dev0/tests/test_example.py` & `receptive_field_calculation-0.0.0.dev1/tests/test_example.py`

 * *Files identical despite different names*

