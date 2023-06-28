# Comparing `tmp/yellowdog-python-examples-6.0.5.tar.gz` & `tmp/yellowdog-python-examples-6.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "yellowdog-python-examples-6.0.5.tar", last modified: Tue Jun 27 15:22:09 2023, max compression
+gzip compressed data, was "yellowdog-python-examples-6.0.6.tar", last modified: Wed Jun 28 10:33:47 2023, max compression
```

## Comparing `yellowdog-python-examples-6.0.5.tar` & `yellowdog-python-examples-6.0.6.tar`

### file list

```diff
@@ -1,49 +1,49 @@
-drwxr-xr-x   0 pwt        (501) staff       (20)        0 2023-06-27 15:22:09.155806 yellowdog-python-examples-6.0.5/
--rw-r--r--   0 pwt        (501) staff       (20)    11357 2022-11-18 20:55:26.000000 yellowdog-python-examples-6.0.5/LICENSE
--rw-r--r--   0 pwt        (501) staff       (20)     1418 2023-06-27 15:22:09.155873 yellowdog-python-examples-6.0.5/PKG-INFO
--rw-r--r--   0 pwt        (501) staff       (20)      676 2022-11-22 08:58:59.000000 yellowdog-python-examples-6.0.5/PYPI_README.md
--rw-r--r--   0 pwt        (501) staff       (20)   111863 2023-06-27 08:13:55.000000 yellowdog-python-examples-6.0.5/README.md
--rw-r--r--   0 pwt        (501) staff       (20)     1806 2023-02-20 09:23:16.000000 yellowdog-python-examples-6.0.5/pyproject.toml
--rw-r--r--   0 pwt        (501) staff       (20)       62 2023-06-20 15:23:19.000000 yellowdog-python-examples-6.0.5/requirements.txt
--rw-r--r--   0 pwt        (501) staff       (20)     1366 2023-06-27 15:22:09.156174 yellowdog-python-examples-6.0.5/setup.cfg
--rw-r--r--   0 pwt        (501) staff       (20)      125 2023-02-14 10:40:48.000000 yellowdog-python-examples-6.0.5/setup.py
-drwxr-xr-x   0 pwt        (501) staff       (20)        0 2023-06-27 15:22:09.154988 yellowdog-python-examples-6.0.5/yd_commands/
--rw-r--r--   0 pwt        (501) staff       (20)       22 2023-06-27 15:17:32.000000 yellowdog-python-examples-6.0.5/yd_commands/__init__.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     3415 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/abort.py
--rwxr-xr-x   0 pwt        (501) staff       (20)      982 2023-01-31 15:59:12.000000 yellowdog-python-examples-6.0.5/yd_commands/admin.py
--rwxr-xr-x   0 pwt        (501) staff       (20)    18991 2023-06-27 15:17:32.000000 yellowdog-python-examples-6.0.5/yd_commands/args.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     5114 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/cancel.py
--rw-r--r--   0 pwt        (501) staff       (20)      579 2022-12-12 15:56:41.000000 yellowdog-python-examples-6.0.5/yd_commands/check_imports.py
--rw-r--r--   0 pwt        (501) staff       (20)     3757 2022-11-27 20:53:08.000000 yellowdog-python-examples-6.0.5/yd_commands/compact_json.py
--rw-r--r--   0 pwt        (501) staff       (20)    17539 2023-06-20 15:23:19.000000 yellowdog-python-examples-6.0.5/yd_commands/config.py
--rw-r--r--   0 pwt        (501) staff       (20)     5062 2023-06-20 15:23:19.000000 yellowdog-python-examples-6.0.5/yd_commands/config_keys.py
--rw-r--r--   0 pwt        (501) staff       (20)    12135 2023-06-09 10:27:25.000000 yellowdog-python-examples-6.0.5/yd_commands/csv_data.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     1657 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/delete.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     3626 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/download.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     9251 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/instantiate.py
--rw-r--r--   0 pwt        (501) staff       (20)     3729 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/interactive.py
--rwxr-xr-x   0 pwt        (501) staff       (20)      749 2023-03-28 14:27:45.000000 yellowdog-python-examples-6.0.5/yd_commands/jsonnet2json.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     7938 2023-06-27 15:17:32.000000 yellowdog-python-examples-6.0.5/yd_commands/list.py
--rw-r--r--   0 pwt        (501) staff       (20)     3000 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/object_utilities.py
--rw-r--r--   0 pwt        (501) staff       (20)     9525 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/printing.py
--rwxr-xr-x   0 pwt        (501) staff       (20)    13218 2023-06-09 10:27:25.000000 yellowdog-python-examples-6.0.5/yd_commands/provision.py
--rw-r--r--   0 pwt        (501) staff       (20)     1248 2023-05-03 10:27:28.000000 yellowdog-python-examples-6.0.5/yd_commands/provision_utils.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     1479 2023-02-14 10:40:48.000000 yellowdog-python-examples-6.0.5/yd_commands/reformat_json.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     3232 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/shutdown.py
--rwxr-xr-x   0 pwt        (501) staff       (20)    41866 2023-06-27 08:13:55.000000 yellowdog-python-examples-6.0.5/yd_commands/submit.py
--rw-r--r--   0 pwt        (501) staff       (20)     7560 2023-06-27 15:17:32.000000 yellowdog-python-examples-6.0.5/yd_commands/submit_utils.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     2916 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/terminate.py
--rw-r--r--   0 pwt        (501) staff       (20)     1678 2022-12-07 08:38:57.000000 yellowdog-python-examples-6.0.5/yd_commands/type_check.py
--rw-r--r--   0 pwt        (501) staff       (20)     2545 2023-06-27 08:13:55.000000 yellowdog-python-examples-6.0.5/yd_commands/upload.py
--rw-r--r--   0 pwt        (501) staff       (20)     3621 2023-06-21 15:20:23.000000 yellowdog-python-examples-6.0.5/yd_commands/upload_utils.py
--rw-r--r--   0 pwt        (501) staff       (20)     2177 2023-06-09 10:27:25.000000 yellowdog-python-examples-6.0.5/yd_commands/validate_properties.py
--rw-r--r--   0 pwt        (501) staff       (20)    11037 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.5/yd_commands/variables.py
--rwxr-xr-x   0 pwt        (501) staff       (20)     1247 2023-03-24 08:40:30.000000 yellowdog-python-examples-6.0.5/yd_commands/version.py
--rw-r--r--   0 pwt        (501) staff       (20)     2995 2023-06-21 15:20:23.000000 yellowdog-python-examples-6.0.5/yd_commands/wrapper.py
-drwxr-xr-x   0 pwt        (501) staff       (20)        0 2023-06-27 15:22:09.155706 yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/
--rw-r--r--   0 pwt        (501) staff       (20)     1418 2023-06-27 15:22:09.000000 yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/PKG-INFO
--rw-r--r--   0 pwt        (501) staff       (20)     1187 2023-06-27 15:22:09.000000 yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/SOURCES.txt
--rw-r--r--   0 pwt        (501) staff       (20)        1 2023-06-27 15:22:09.000000 yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/dependency_links.txt
--rw-r--r--   0 pwt        (501) staff       (20)      574 2023-06-27 15:22:09.000000 yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/entry_points.txt
--rw-r--r--   0 pwt        (501) staff       (20)       75 2023-06-27 15:22:09.000000 yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/requires.txt
--rw-r--r--   0 pwt        (501) staff       (20)       12 2023-06-27 15:22:09.000000 yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/top_level.txt
+drwxr-xr-x   0 pwt        (501) staff       (20)        0 2023-06-28 10:33:47.781313 yellowdog-python-examples-6.0.6/
+-rw-r--r--   0 pwt        (501) staff       (20)    11357 2022-11-18 20:55:26.000000 yellowdog-python-examples-6.0.6/LICENSE
+-rw-r--r--   0 pwt        (501) staff       (20)     1418 2023-06-28 10:33:47.781383 yellowdog-python-examples-6.0.6/PKG-INFO
+-rw-r--r--   0 pwt        (501) staff       (20)      676 2022-11-22 08:58:59.000000 yellowdog-python-examples-6.0.6/PYPI_README.md
+-rw-r--r--   0 pwt        (501) staff       (20)   112282 2023-06-28 10:33:03.000000 yellowdog-python-examples-6.0.6/README.md
+-rw-r--r--   0 pwt        (501) staff       (20)     1806 2023-02-20 09:23:16.000000 yellowdog-python-examples-6.0.6/pyproject.toml
+-rw-r--r--   0 pwt        (501) staff       (20)       62 2023-06-20 15:23:19.000000 yellowdog-python-examples-6.0.6/requirements.txt
+-rw-r--r--   0 pwt        (501) staff       (20)     1366 2023-06-28 10:33:47.781694 yellowdog-python-examples-6.0.6/setup.cfg
+-rw-r--r--   0 pwt        (501) staff       (20)      125 2023-02-14 10:40:48.000000 yellowdog-python-examples-6.0.6/setup.py
+drwxr-xr-x   0 pwt        (501) staff       (20)        0 2023-06-28 10:33:47.780401 yellowdog-python-examples-6.0.6/yd_commands/
+-rw-r--r--   0 pwt        (501) staff       (20)       22 2023-06-28 10:33:03.000000 yellowdog-python-examples-6.0.6/yd_commands/__init__.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     3415 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/abort.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)      982 2023-01-31 15:59:12.000000 yellowdog-python-examples-6.0.6/yd_commands/admin.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)    18967 2023-06-28 10:33:03.000000 yellowdog-python-examples-6.0.6/yd_commands/args.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     5114 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/cancel.py
+-rw-r--r--   0 pwt        (501) staff       (20)      579 2022-12-12 15:56:41.000000 yellowdog-python-examples-6.0.6/yd_commands/check_imports.py
+-rw-r--r--   0 pwt        (501) staff       (20)     3757 2022-11-27 20:53:08.000000 yellowdog-python-examples-6.0.6/yd_commands/compact_json.py
+-rw-r--r--   0 pwt        (501) staff       (20)    17539 2023-06-20 15:23:19.000000 yellowdog-python-examples-6.0.6/yd_commands/config.py
+-rw-r--r--   0 pwt        (501) staff       (20)     5062 2023-06-20 15:23:19.000000 yellowdog-python-examples-6.0.6/yd_commands/config_keys.py
+-rw-r--r--   0 pwt        (501) staff       (20)    12135 2023-06-09 10:27:25.000000 yellowdog-python-examples-6.0.6/yd_commands/csv_data.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     1657 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/delete.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     3626 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/download.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     9251 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/instantiate.py
+-rw-r--r--   0 pwt        (501) staff       (20)     4135 2023-06-28 10:33:03.000000 yellowdog-python-examples-6.0.6/yd_commands/interactive.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)      749 2023-03-28 14:27:45.000000 yellowdog-python-examples-6.0.6/yd_commands/jsonnet2json.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     7862 2023-06-28 10:33:03.000000 yellowdog-python-examples-6.0.6/yd_commands/list.py
+-rw-r--r--   0 pwt        (501) staff       (20)     3000 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/object_utilities.py
+-rw-r--r--   0 pwt        (501) staff       (20)     9525 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/printing.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)    13218 2023-06-09 10:27:25.000000 yellowdog-python-examples-6.0.6/yd_commands/provision.py
+-rw-r--r--   0 pwt        (501) staff       (20)     1248 2023-05-03 10:27:28.000000 yellowdog-python-examples-6.0.6/yd_commands/provision_utils.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     1479 2023-02-14 10:40:48.000000 yellowdog-python-examples-6.0.6/yd_commands/reformat_json.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     3232 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/shutdown.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)    41866 2023-06-27 08:13:55.000000 yellowdog-python-examples-6.0.6/yd_commands/submit.py
+-rw-r--r--   0 pwt        (501) staff       (20)     7560 2023-06-27 15:17:32.000000 yellowdog-python-examples-6.0.6/yd_commands/submit_utils.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     2916 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/terminate.py
+-rw-r--r--   0 pwt        (501) staff       (20)     1678 2022-12-07 08:38:57.000000 yellowdog-python-examples-6.0.6/yd_commands/type_check.py
+-rw-r--r--   0 pwt        (501) staff       (20)     2545 2023-06-27 08:13:55.000000 yellowdog-python-examples-6.0.6/yd_commands/upload.py
+-rw-r--r--   0 pwt        (501) staff       (20)     3621 2023-06-21 15:20:23.000000 yellowdog-python-examples-6.0.6/yd_commands/upload_utils.py
+-rw-r--r--   0 pwt        (501) staff       (20)     2177 2023-06-09 10:27:25.000000 yellowdog-python-examples-6.0.6/yd_commands/validate_properties.py
+-rw-r--r--   0 pwt        (501) staff       (20)    11037 2023-05-16 09:40:32.000000 yellowdog-python-examples-6.0.6/yd_commands/variables.py
+-rwxr-xr-x   0 pwt        (501) staff       (20)     1247 2023-03-24 08:40:30.000000 yellowdog-python-examples-6.0.6/yd_commands/version.py
+-rw-r--r--   0 pwt        (501) staff       (20)     2995 2023-06-21 15:20:23.000000 yellowdog-python-examples-6.0.6/yd_commands/wrapper.py
+drwxr-xr-x   0 pwt        (501) staff       (20)        0 2023-06-28 10:33:47.781205 yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/
+-rw-r--r--   0 pwt        (501) staff       (20)     1418 2023-06-28 10:33:47.000000 yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/PKG-INFO
+-rw-r--r--   0 pwt        (501) staff       (20)     1187 2023-06-28 10:33:47.000000 yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/SOURCES.txt
+-rw-r--r--   0 pwt        (501) staff       (20)        1 2023-06-28 10:33:47.000000 yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/dependency_links.txt
+-rw-r--r--   0 pwt        (501) staff       (20)      574 2023-06-28 10:33:47.000000 yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/entry_points.txt
+-rw-r--r--   0 pwt        (501) staff       (20)       75 2023-06-28 10:33:47.000000 yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/requires.txt
+-rw-r--r--   0 pwt        (501) staff       (20)       12 2023-06-28 10:33:47.000000 yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/top_level.txt
```

### Comparing `yellowdog-python-examples-6.0.5/LICENSE` & `yellowdog-python-examples-6.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/PKG-INFO` & `yellowdog-python-examples-6.0.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: yellowdog-python-examples
-Version: 6.0.5
+Version: 6.0.6
 Summary: Example Python commands using the YellowDog Python SDK
 Home-page: https://github.com/yellowdog/python-examples
 Author: YellowDog Limited
 Author-email: YellowDog Limited <support@yellowdog.co>
 Project-URL: Homepage, https://github.com/yellowdog/python-examples
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
```

### Comparing `yellowdog-python-examples-6.0.5/PYPI_README.md` & `yellowdog-python-examples-6.0.6/PYPI_README.md`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/README.md` & `yellowdog-python-examples-6.0.6/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -375,6618 +375,6644 @@
 00001760: 0a20 2020 2020 202a 205b 5465 7374 2d52  .      * [Test-R
 00001770: 756e 6e69 6e67 2061 2044 796e 616d 6963  unning a Dynamic
 00001780: 2054 656d 706c 6174 655d 2823 7465 7374   Template](#test
 00001790: 2d72 756e 6e69 6e67 2d61 2d64 796e 616d  -running-a-dynam
 000017a0: 6963 2d74 656d 706c 6174 6529 0a20 2020  ic-template).   
 000017b0: 2a20 5b79 642d 7465 726d 696e 6174 655d  * [yd-terminate]
 000017c0: 2823 7964 2d74 6572 6d69 6e61 7465 290a  (#yd-terminate).
-000017d0: 0a3c 212d 2d20 4164 6465 6420 6279 3a20  .<!-- Added by: 
-000017e0: 7077 742c 2061 743a 204d 6f6e 204a 756e  pwt, at: Mon Jun
-000017f0: 2032 3620 3135 3a33 393a 3436 2042 5354   26 15:39:46 BST
-00001800: 2032 3032 3320 2d2d 3e0a 0a3c 212d 2d74   2023 -->..<!--t
-00001810: 652d 2d3e 0a0a 2320 4f76 6572 7669 6577  e-->..# Overview
-00001820: 0a0a 5468 6973 2072 6570 6f73 6974 6f72  ..This repositor
-00001830: 7920 636f 6e74 6169 6e73 2061 2073 6574  y contains a set
-00001840: 206f 6620 6578 616d 706c 6520 5079 7468   of example Pyth
-00001850: 6f6e 2073 6372 6970 7473 2066 6f72 2069  on scripts for i
-00001860: 6e74 6572 6163 7469 6e67 2077 6974 6820  nteracting with 
-00001870: 7468 6520 5965 6c6c 6f77 446f 6720 506c  the YellowDog Pl
-00001880: 6174 666f 726d 2e20 5468 6520 7363 7269  atform. The scri
-00001890: 7074 7320 7573 6520 7468 6520 2a2a 5b59  pts use the **[Y
-000018a0: 656c 6c6f 7744 6f67 2050 7974 686f 6e20  ellowDog Python 
-000018b0: 5344 4b5d 2868 7474 7073 3a2f 2f64 6f63  SDK](https://doc
-000018c0: 732e 7965 6c6c 6f77 646f 672e 636f 2f61  s.yellowdog.co/a
-000018d0: 7069 2f70 7974 686f 6e2f 696e 6465 782e  pi/python/index.
-000018e0: 6874 6d6c 292a 2a2c 2074 6865 2063 6f64  html)**, the cod
-000018f0: 6520 666f 7220 7768 6963 6820 6361 6e20  e for which can 
-00001900: 6265 2066 6f75 6e64 205b 6f6e 2047 6974  be found [on Git
-00001910: 4875 625d 2868 7474 7073 3a2f 2f67 6974  Hub](https://git
-00001920: 6875 622e 636f 6d2f 7965 6c6c 6f77 646f  hub.com/yellowdo
-00001930: 672f 7965 6c6c 6f77 646f 672d 7364 6b2d  g/yellowdog-sdk-
-00001940: 7079 7468 6f6e 2d70 7562 6c69 6329 2e0a  python-public)..
-00001950: 0a0a 2a28 4e6f 7465 3a20 7468 6573 6520  ..*(Note: these 
-00001960: 7363 7269 7074 7320 6172 6520 696e 7465  scripts are inte
-00001970: 6e64 6564 2074 6f20 6265 2061 2068 656c  nded to be a hel
-00001980: 7066 756c 2073 7461 7274 696e 6720 706f  pful starting po
-00001990: 696e 7420 666f 7220 6578 7065 7269 6d65  int for experime
-000019a0: 6e74 696e 6720 7769 7468 2074 6865 2059  nting with the Y
-000019b0: 656c 6c6f 7744 6f67 2050 6c61 7466 6f72  ellowDog Platfor
-000019c0: 6d2e 2054 6865 7920 6172 6520 6e6f 7420  m. They are not 
-000019d0: 6173 7375 7265 6420 746f 2062 6520 6f66  assured to be of
-000019e0: 2070 726f 6475 6374 696f 6e20 7175 616c   production qual
-000019f0: 6974 7920 6e6f 7220 646f 2074 6865 7920  ity nor do they 
-00001a00: 7265 7072 6573 656e 7420 6120 7374 616e  represent a stan
-00001a10: 6461 7264 206f 7220 7265 636f 6d6d 656e  dard or recommen
-00001a20: 6465 6420 6d65 7468 6f64 2066 6f72 2075  ded method for u
-00001a30: 7369 6e67 2059 656c 6c6f 7744 6f67 2e29  sing YellowDog.)
-00001a40: 2a0a 0a54 6869 7320 646f 6375 6d65 6e74  *..This document
-00001a50: 6174 696f 6e20 7368 6f75 6c64 2062 6520  ation should be 
-00001a60: 7265 6164 2069 6e20 636f 6e6a 756e 6374  read in conjunct
-00001a70: 696f 6e20 7769 7468 2074 6865 206d 6169  ion with the mai
-00001a80: 6e20 2a2a 5b59 656c 6c6f 7744 6f67 2044  n **[YellowDog D
-00001a90: 6f63 756d 656e 7461 7469 6f6e 5d28 6874  ocumentation](ht
-00001aa0: 7470 733a 2f2f 646f 6373 2e79 656c 6c6f  tps://docs.yello
-00001ab0: 7764 6f67 2e63 6f29 2a2a 2c20 7768 6963  wdog.co)**, whic
-00001ac0: 6820 7072 6f76 6964 6573 2061 2063 6f6d  h provides a com
-00001ad0: 7072 6568 656e 7369 7665 2064 6573 6372  prehensive descr
-00001ae0: 6970 7469 6f6e 206f 6620 7468 6520 636f  iption of the co
-00001af0: 6e63 6570 7473 2061 6e64 206f 7065 7261  ncepts and opera
-00001b00: 7469 6f6e 206f 6620 7468 6520 5965 6c6c  tion of the Yell
-00001b10: 6f77 446f 6720 506c 6174 666f 726d 2e0a  owDog Platform..
-00001b20: 0a54 656d 706c 6174 6520 736f 6c75 7469  .Template soluti
-00001b30: 6f6e 7320 666f 7220 6578 7065 7269 6d65  ons for experime
-00001b40: 6e74 696e 6720 7769 7468 2074 6865 7365  nting with these
-00001b50: 2073 6372 6970 7473 2063 616e 2062 6520   scripts can be 
-00001b60: 666f 756e 6420 696e 2074 6865 202a 2a5b  found in the **[
-00001b70: 7079 7468 6f6e 2d65 7861 6d70 6c65 732d  python-examples-
-00001b80: 7465 6d70 6c61 7465 735d 2868 7474 7073  templates](https
-00001b90: 3a2f 2f67 6974 6875 622e 636f 6d2f 7965  ://github.com/ye
-00001ba0: 6c6c 6f77 646f 672f 7079 7468 6f6e 2d65  llowdog/python-e
-00001bb0: 7861 6d70 6c65 732d 7465 6d70 6c61 7465  xamples-template
-00001bc0: 7329 2a2a 2072 6570 6f73 6974 6f72 792e  s)** repository.
-00001bd0: 0a0a 5468 6520 7363 7269 7074 7320 7072  ..The scripts pr
-00001be0: 6f76 6964 6520 7468 6520 666f 6c6c 6f77  ovide the follow
-00001bf0: 696e 6720 6361 7061 6269 6c69 7469 6573  ing capabilities
-00001c00: 3a0a 0a2d 202a 2a50 726f 7669 7369 6f6e  :..- **Provision
-00001c10: 696e 672a 2a20 576f 726b 6572 2050 6f6f  ing** Worker Poo
-00001c20: 6c73 2077 6974 6820 7468 6520 2a2a 6079  ls with the **`y
-00001c30: 642d 7072 6f76 6973 696f 6e60 2a2a 2063  d-provision`** c
-00001c40: 6f6d 6d61 6e64 0a2d 202a 2a53 7562 6d69  ommand.- **Submi
-00001c50: 7474 696e 672a 2a20 576f 726b 2052 6571  tting** Work Req
-00001c60: 7569 7265 6d65 6e74 7320 7769 7468 2074  uirements with t
-00001c70: 6865 202a 2a60 7964 2d73 7562 6d69 7460  he **`yd-submit`
-00001c80: 2a2a 2063 6f6d 6d61 6e64 0a2d 202a 2a55  ** command.- **U
-00001c90: 706c 6f61 6469 6e67 2a2a 2066 696c 6573  ploading** files
-00001ca0: 2074 6f20 7468 6520 5965 6c6c 6f77 446f   to the YellowDo
-00001cb0: 6720 4f62 6a65 6374 2053 746f 7265 2077  g Object Store w
-00001cc0: 6974 6820 7468 6520 2a2a 6079 642d 7570  ith the **`yd-up
-00001cd0: 6c6f 6164 602a 2a20 636f 6d6d 616e 640a  load`** command.
-00001ce0: 2d20 2a2a 496e 7374 616e 7469 6174 696e  - **Instantiatin
-00001cf0: 672a 2a20 436f 6d70 7574 6520 5265 7175  g** Compute Requ
-00001d00: 6972 656d 656e 7473 2077 6974 6820 7468  irements with th
-00001d10: 6520 2a2a 6079 642d 696e 7374 616e 7469  e **`yd-instanti
-00001d20: 6174 6560 2a2a 2063 6f6d 6d61 6e64 0a2d  ate`** command.-
-00001d30: 202a 2a44 6f77 6e6c 6f61 6469 6e67 2a2a   **Downloading**
-00001d40: 2052 6573 756c 7473 2066 726f 6d20 7468   Results from th
-00001d50: 6520 5965 6c6c 6f77 446f 6720 4f62 6a65  e YellowDog Obje
-00001d60: 6374 2053 746f 7265 2077 6974 6820 7468  ct Store with th
-00001d70: 6520 2a2a 6079 642d 646f 776e 6c6f 6164  e **`yd-download
-00001d80: 602a 2a20 636f 6d6d 616e 640a 2d20 2a2a  `** command.- **
-00001d90: 4162 6f72 7469 6e67 2a2a 2072 756e 6e69  Aborting** runni
-00001da0: 6e67 2054 6173 6b73 2077 6974 6820 7468  ng Tasks with th
-00001db0: 6520 2a2a 6079 642d 6162 6f72 7460 2a2a  e **`yd-abort`**
-00001dc0: 2063 6f6d 6d61 6e64 0a2d 202a 2a43 616e   command.- **Can
-00001dd0: 6365 6c6c 696e 672a 2a20 576f 726b 2052  celling** Work R
-00001de0: 6571 7569 7265 6d65 6e74 7320 7769 7468  equirements with
-00001df0: 2074 6865 202a 2a60 7964 2d63 616e 6365   the **`yd-cance
-00001e00: 6c60 2a2a 2063 6f6d 6d61 6e64 0a2d 202a  l`** command.- *
-00001e10: 2a53 6875 7474 696e 6720 446f 776e 2a2a  *Shutting Down**
-00001e20: 2057 6f72 6b65 7220 506f 6f6c 7320 7769   Worker Pools wi
-00001e30: 7468 2074 6865 202a 2a60 7964 2d73 6875  th the **`yd-shu
-00001e40: 7464 6f77 6e60 2a2a 2063 6f6d 6d61 6e64  tdown`** command
-00001e50: 0a2d 202a 2a54 6572 6d69 6e61 7469 6e67  .- **Terminating
-00001e60: 2a2a 2043 6f6d 7075 7465 2052 6571 7569  ** Compute Requi
-00001e70: 7265 6d65 6e74 7320 7769 7468 2074 6865  rements with the
-00001e80: 202a 2a60 7964 2d74 6572 6d69 6e61 7465   **`yd-terminate
-00001e90: 602a 2a20 636f 6d6d 616e 640a 2d20 2a2a  `** command.- **
-00001ea0: 4465 6c65 7469 6e67 2a2a 206f 626a 6563  Deleting** objec
-00001eb0: 7473 2069 6e20 7468 6520 5965 6c6c 6f77  ts in the Yellow
-00001ec0: 446f 6720 4f62 6a65 6374 2053 746f 7265  Dog Object Store
-00001ed0: 2077 6974 6820 7468 6520 2a2a 6079 642d   with the **`yd-
-00001ee0: 6465 6c65 7465 602a 2a20 636f 6d6d 616e  delete`** comman
-00001ef0: 640a 0a54 6865 206f 7065 7261 7469 6f6e  d..The operation
-00001f00: 206f 6620 7468 6520 636f 6d6d 616e 6473   of the commands
-00001f10: 2069 7320 636f 6e74 726f 6c6c 6564 2075   is controlled u
-00001f20: 7369 6e67 2054 4f4d 4c20 636f 6e66 6967  sing TOML config
-00001f30: 7572 6174 696f 6e20 6669 6c65 732e 2049  uration files. I
-00001f40: 6e20 6164 6469 7469 6f6e 2c20 576f 726b  n addition, Work
-00001f50: 2052 6571 7569 7265 6d65 6e74 7320 616e   Requirements an
-00001f60: 6420 576f 726b 6572 2050 6f6f 6c73 2063  d Worker Pools c
-00001f70: 616e 2062 6520 6465 6669 6e65 6420 7573  an be defined us
-00001f80: 696e 6720 4a53 4f4e 2066 696c 6573 2070  ing JSON files p
-00001f90: 726f 7669 6469 6e67 2065 7874 656e 7369  roviding extensi
-00001fa0: 7665 2063 6f6e 6669 6775 7261 6269 6c69  ve configurabili
-00001fb0: 7479 2e0a 0a23 2059 656c 6c6f 7744 6f67  ty...# YellowDog
-00001fc0: 2050 7265 7265 7175 6973 6974 6573 0a0a   Prerequisites..
-00001fd0: 546f 2073 7562 6d69 7420 2a2a 576f 726b  To submit **Work
-00001fe0: 2052 6571 7569 7265 6d65 6e74 732a 2a20   Requirements** 
-00001ff0: 746f 2059 656c 6c6f 7744 6f67 2066 6f72  to YellowDog for
-00002000: 2070 726f 6365 7373 696e 6720 6279 2043   processing by C
-00002010: 6f6e 6669 6775 7265 6420 576f 726b 6572  onfigured Worker
-00002020: 2050 6f6f 6c73 2028 6f6e 2d70 7265 6d69   Pools (on-premi
-00002030: 7365 2920 616e 642f 6f72 2050 726f 7669  se) and/or Provi
-00002040: 7369 6f6e 6564 2057 6f72 6b65 7220 506f  sioned Worker Po
-00002050: 6f6c 7320 2863 6c6f 7564 2d70 726f 7669  ols (cloud-provi
-00002060: 7369 6f6e 6564 2072 6573 6f75 7263 6573  sioned resources
-00002070: 292c 2079 6f75 276c 6c20 6e65 6564 3a0a  ), you'll need:.
-00002080: 0a31 2e20 4120 5965 6c6c 6f77 446f 6720  .1. A YellowDog 
-00002090: 506c 6174 666f 726d 2041 6363 6f75 6e74  Platform Account
-000020a0: 2e0a 0a0a 322e 2041 6e20 4170 706c 6963  ....2. An Applic
-000020b0: 6174 696f 6e20 4b65 7920 2620 5365 6372  ation Key & Secr
-000020c0: 6574 3a20 696e 2074 6865 202a 2a41 6363  et: in the **Acc
-000020d0: 6f75 6e74 732a 2a20 7365 6374 696f 6e20  ounts** section 
-000020e0: 756e 6465 7220 7468 6520 2a2a 4170 706c  under the **Appl
-000020f0: 6963 6174 696f 6e73 2a2a 2074 6162 2069  ications** tab i
-00002100: 6e20 7468 6520 5b59 656c 6c6f 7744 6f67  n the [YellowDog
-00002110: 2050 6f72 7461 6c5d 2868 7474 7073 3a2f   Portal](https:/
-00002120: 2f70 6f72 7461 6c2e 7965 6c6c 6f77 646f  /portal.yellowdo
-00002130: 672e 636f 2f23 2f61 6363 6f75 6e74 2f61  g.co/#/account/a
-00002140: 7070 6c69 6361 7469 6f6e 7329 2c20 7573  pplications), us
-00002150: 6520 7468 6520 2a2a 4164 6420 4170 706c  e the **Add Appl
-00002160: 6963 6174 696f 6e2a 2a20 6275 7474 6f6e  ication** button
-00002170: 2074 6f20 6372 6561 7465 2061 206e 6577   to create a new
-00002180: 2041 7070 6c69 6361 7469 6f6e 2c20 616e   Application, an
-00002190: 6420 6d61 6b65 2061 206e 6f74 6520 6f66  d make a note of
-000021a0: 2069 7473 202a 2a4b 6579 2a2a 2061 6e64   its **Key** and
-000021b0: 202a 2a53 6563 7265 742a 2a20 2874 6865   **Secret** (the
-000021c0: 7365 2077 696c 6c20 6f6e 6c79 2062 6520  se will only be 
-000021d0: 6469 7370 6c61 7965 6420 6f6e 6365 292e  displayed once).
-000021e0: 0a0a 0a54 6f20 6372 6561 7465 202a 2a50  ...To create **P
-000021f0: 726f 7669 7369 6f6e 6564 2057 6f72 6b65  rovisioned Worke
-00002200: 7220 506f 6f6c 732a 2a2c 2079 6f75 276c  r Pools**, you'l
-00002210: 6c20 6e65 6564 3a0a 0a33 2e20 4120 2a2a  l need:..3. A **
-00002220: 4b65 7972 696e 672a 2a20 6372 6561 7465  Keyring** create
-00002230: 6420 7669 6120 7468 6520 5965 6c6c 6f77  d via the Yellow
-00002240: 446f 6720 506f 7274 616c 2c20 7769 7468  Dog Portal, with
-00002250: 2061 6363 6573 7320 746f 2043 6c6f 7564   access to Cloud
-00002260: 2050 726f 7669 6465 7220 6372 6564 656e   Provider creden
-00002270: 7469 616c 7320 6173 2072 6571 7569 7265  tials as require
-00002280: 642e 2054 6865 2041 7070 6c69 6361 7469  d. The Applicati
-00002290: 6f6e 206d 7573 7420 6265 2067 7261 6e74  on must be grant
-000022a0: 6564 2061 6363 6573 7320 746f 2074 6865  ed access to the
-000022b0: 204b 6579 7269 6e67 2e0a 0a0a 342e 204f   Keyring....4. O
-000022c0: 6e65 206f 7220 6d6f 7265 202a 2a43 6f6d  ne or more **Com
-000022d0: 7075 7465 2053 6f75 7263 6573 2a2a 2064  pute Sources** d
-000022e0: 6566 696e 6564 2c20 616e 6420 6120 2a2a  efined, and a **
-000022f0: 436f 6d70 7574 6520 5265 7175 6972 656d  Compute Requirem
-00002300: 656e 7420 5465 6d70 6c61 7465 2a2a 2063  ent Template** c
-00002310: 7265 6174 6564 2e20 5468 6520 696d 6167  reated. The imag
-00002320: 6573 2075 7365 6420 6279 2069 6e73 7461  es used by insta
-00002330: 6e63 6573 206d 7573 7420 696e 636c 7564  nces must includ
-00002340: 6520 7468 6520 5965 6c6c 6f77 446f 6720  e the YellowDog 
-00002350: 6167 656e 742c 2063 6f6e 6669 6775 7265  agent, configure
-00002360: 6420 7769 7468 2074 6865 2054 6173 6b20  d with the Task 
-00002370: 5479 7065 2873 2920 746f 206d 6174 6368  Type(s) to match
-00002380: 2074 6865 2057 6f72 6b20 5265 7175 6972   the Work Requir
-00002390: 656d 656e 7473 2074 6f20 6265 2073 7562  ements to be sub
-000023a0: 6d69 7474 6564 2e0a 0a54 6f20 7365 7420  mitted...To set 
-000023b0: 7570 202a 2a43 6f6e 6669 6775 7265 6420  up **Configured 
-000023c0: 576f 726b 6572 2050 6f6f 6c73 2a2a 2c20  Worker Pools**, 
-000023d0: 796f 7527 6c6c 206e 6565 643a 0a0a 352e  you'll need:..5.
-000023e0: 2041 2043 6f6e 6669 6775 7265 6420 576f   A Configured Wo
-000023f0: 726b 6572 2050 6f6f 6c20 546f 6b65 6e3a  rker Pool Token:
-00002400: 2066 726f 6d20 7468 6520 2a2a 576f 726b   from the **Work
-00002410: 6572 732a 2a20 7461 6220 696e 2074 6865  ers** tab in the
-00002420: 205b 5965 6c6c 6f77 446f 6720 506f 7274   [YellowDog Port
-00002430: 616c 5d28 6874 7470 733a 2f2f 706f 7274  al](https://port
-00002440: 616c 2e79 656c 6c6f 7764 6f67 2e63 6f2f  al.yellowdog.co/
-00002450: 232f 776f 726b 6572 7329 2c20 7573 6520  #/workers), use 
-00002460: 7468 6520 2a2a 2b41 6464 2043 6f6e 6669  the **+Add Confi
-00002470: 6775 7265 6420 576f 726b 6572 2050 6f6f  gured Worker Poo
-00002480: 6c2a 2a20 6275 7474 6f6e 2074 6f20 6372  l** button to cr
-00002490: 6561 7465 2061 206e 6577 2057 6f72 6b65  eate a new Worke
-000024a0: 7220 506f 6f6c 2061 6e64 2067 656e 6572  r Pool and gener
-000024b0: 6174 6520 6120 746f 6b65 6e2e 0a0a 0a36  ate a token....6
-000024c0: 2e20 4f62 7461 696e 2074 6865 2059 656c  . Obtain the Yel
-000024d0: 6c6f 7744 6f67 2041 6765 6e74 2061 6e64  lowDog Agent and
-000024e0: 2069 6e73 7461 6c6c 2f63 6f6e 6669 6775   install/configu
-000024f0: 7265 2069 7420 6f6e 2079 6f75 7220 6f6e  re it on your on
-00002500: 2d70 7265 6d69 7365 2073 7973 7465 6d73  -premise systems
-00002510: 2075 7369 6e67 2074 6865 2054 6f6b 656e   using the Token
-00002520: 2061 626f 7665 2e0a 0a23 2053 6372 6970   above...# Scrip
-00002530: 7420 496e 7374 616c 6c61 7469 6f6e 2077  t Installation w
-00002540: 6974 6820 5069 700a 0a50 7974 686f 6e20  ith Pip..Python 
-00002550: 7665 7273 696f 6e20 332e 3720 6f72 206c  version 3.7 or l
-00002560: 6174 6572 2069 7320 7265 7175 6972 6564  ater is required
-00002570: 2e20 4974 2773 2072 6563 6f6d 6d65 6e64  . It's recommend
-00002580: 6564 2074 6861 7420 696e 7374 616c 6c61  ed that installa
-00002590: 7469 6f6e 2069 7320 7065 7266 6f72 6d65  tion is performe
-000025a0: 6420 696e 2061 2050 7974 686f 6e20 7669  d in a Python vi
-000025b0: 7274 7561 6c20 656e 7669 726f 6e6d 656e  rtual environmen
-000025c0: 7420 286f 7220 7369 6d69 6c61 7229 2074  t (or similar) t
-000025d0: 6f20 6973 6f6c 6174 6520 7468 6520 696e  o isolate the in
-000025e0: 7374 616c 6c61 7469 6f6e 2066 726f 6d20  stallation from 
-000025f0: 6f74 6865 7220 5079 7468 6f6e 2065 6e76  other Python env
-00002600: 6972 6f6e 6d65 6e74 7320 6f6e 2079 6f75  ironments on you
-00002610: 7220 7379 7374 656d 2e0a 0a49 6e73 7461  r system...Insta
-00002620: 6c6c 6174 696f 6e20 616e 6420 7375 6273  llation and subs
-00002630: 6571 7565 6e74 2075 7064 6174 6520 6172  equent update ar
-00002640: 6520 7669 6120 6070 6970 6020 616e 6420  e via `pip` and 
-00002650: 5079 5049 2075 7369 6e67 3a20 0a0a 6060  PyPI using: ..``
-00002660: 6073 6865 6c6c 0a70 6970 2069 6e73 7461  `shell.pip insta
-00002670: 6c6c 202d 5520 7965 6c6c 6f77 646f 672d  ll -U yellowdog-
-00002680: 7079 7468 6f6e 2d65 7861 6d70 6c65 730a  python-examples.
-00002690: 6060 600a 0a49 6620 796f 7527 7265 2069  ```..If you're i
-000026a0: 6e74 6572 6573 7465 6420 696e 2069 6e63  nterested in inc
-000026b0: 6c75 6469 6e67 202a 2a4a 736f 6e6e 6574  luding **Jsonnet
-000026c0: 2a2a 2073 7570 706f 7274 2c20 706c 6561  ** support, plea
-000026d0: 7365 2073 6565 2074 6865 205b 4a73 6f6e  se see the [Json
-000026e0: 6e65 7420 5375 7070 6f72 745d 2823 6a73  net Support](#js
-000026f0: 6f6e 6e65 742d 7375 7070 6f72 7429 2073  onnet-support) s
-00002700: 6563 7469 6f6e 2062 656c 6f77 2e0a 0a23  ection below...#
-00002710: 2053 6372 6970 7420 496e 7374 616c 6c61   Script Installa
-00002720: 7469 6f6e 2077 6974 6820 5069 7078 0a0a  tion with Pipx..
-00002730: 5468 6520 636f 6d6d 616e 6473 2063 616e  The commands can
-00002740: 2061 6c73 6f20 6265 2069 6e73 7461 6c6c   also be install
-00002750: 6564 2075 7369 6e67 202a 2a5b 7069 7078  ed using **[pipx
-00002760: 5d28 6874 7470 733a 2f2f 7079 7061 2e67  ](https://pypa.g
-00002770: 6974 6875 622e 696f 2f70 6970 782f 292a  ithub.io/pipx/)*
-00002780: 2a2e 0a0a 5468 6973 206d 6574 686f 6420  *...This method 
-00002790: 7265 7175 6972 6573 2050 7974 686f 6e20  requires Python 
-000027a0: 332e 372b 2061 6e64 2070 6970 7820 746f  3.7+ and pipx to
-000027b0: 2062 6520 696e 7374 616c 6c65 642e 2054   be installed. T
-000027c0: 6f20 696e 7374 616c 6c3a 0a60 6060 7368  o install:.```sh
-000027d0: 656c 6c0a 7069 7078 2069 6e73 7461 6c6c  ell.pipx install
-000027e0: 2079 656c 6c6f 7764 6f67 2d70 7974 686f   yellowdog-pytho
-000027f0: 6e2d 6578 616d 706c 6573 0a60 6060 0a0a  n-examples.```..
-00002800: 546f 2075 7064 6174 653a 0a60 6060 7368  To update:.```sh
-00002810: 656c 6c0a 7069 7078 2075 7067 7261 6465  ell.pipx upgrade
-00002820: 2079 656c 6c6f 7764 6f67 2d70 7974 686f   yellowdog-pytho
-00002830: 6e2d 6578 616d 706c 6573 0a60 6060 0a0a  n-examples.```..
-00002840: 2320 5573 6167 650a 0a42 6f74 6820 6f66  # Usage..Both of
-00002850: 2074 6865 2069 6e73 7461 6c6c 6174 696f   the installatio
-00002860: 6e20 6d65 7468 6f64 7320 6162 6f76 6520  n methods above 
-00002870: 7769 6c6c 2069 6e73 7461 6c6c 2061 206e  will install a n
-00002880: 756d 6265 7220 6f66 202a 2a60 7964 2d60  umber of **`yd-`
-00002890: 2a2a 2063 6f6d 6d61 6e64 7320 6f6e 2079  ** commands on y
-000028a0: 6f75 7220 5041 5448 2e0a 0a43 6f6d 6d61  our PATH...Comma
-000028b0: 6e64 7320 6172 6520 7275 6e20 6672 6f6d  nds are run from
-000028c0: 2074 6865 2063 6f6d 6d61 6e64 206c 696e   the command lin
-000028d0: 652e 2049 6e76 6f6b 696e 6720 7468 6520  e. Invoking the 
-000028e0: 636f 6d6d 616e 6420 7769 7468 2074 6865  command with the
-000028f0: 2060 2d2d 6865 6c70 6020 6f72 2060 2d68   `--help` or `-h
-00002900: 6020 6f70 7469 6f6e 2077 696c 6c20 6469  ` option will di
-00002910: 7370 6c61 7920 7468 6520 636f 6d6d 616e  splay the comman
-00002920: 6420 6c69 6e65 206f 7074 696f 6e73 2061  d line options a
-00002930: 7070 6c69 6361 626c 6520 746f 2061 2067  pplicable to a g
-00002940: 6976 656e 2063 6f6d 6d61 6e64 2c20 652e  iven command, e.
-00002950: 672e 3a0a 0a60 6060 7465 7874 0a20 2520  g.:..```text. % 
-00002960: 7964 2d63 616e 6365 6c20 2d2d 6865 6c70  yd-cancel --help
-00002970: 0a75 7361 6765 3a20 7964 2d63 616e 6365  .usage: yd-cance
-00002980: 6c20 5b2d 685d 205b 2d2d 646f 6373 5d20  l [-h] [--docs] 
-00002990: 5b2d 2d63 6f6e 6669 6720 3c63 6f6e 6669  [--config <confi
-000029a0: 675f 6669 6c65 2e74 6f6d 6c3e 5d20 5b2d  g_file.toml>] [-
-000029b0: 2d6b 6579 203c 6170 702d 6b65 793e 5d0a  -key <app-key>].
-000029c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000029d0: 205b 2d2d 7365 6372 6574 203c 6170 702d   [--secret <app-
-000029e0: 7365 6372 6574 3e5d 205b 2d2d 6e61 6d65  secret>] [--name
-000029f0: 7370 6163 6520 3c6e 616d 6573 7061 6365  space <namespace
-00002a00: 3e5d 205b 2d2d 7461 6720 3c74 6167 3e5d  >] [--tag <tag>]
-00002a10: 205b 2d2d 7572 6c20 3c75 726c 3e5d 0a20   [--url <url>]. 
-00002a20: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00002a30: 5b2d 2d76 6172 6961 626c 6520 3c76 6172  [--variable <var
-00002a40: 313d 7631 3e5d 205b 2d2d 7175 6965 745d  1=v1>] [--quiet]
-00002a50: 205b 2d2d 6465 6275 675d 205b 2d2d 7061   [--debug] [--pa
-00002a60: 635d 205b 2d2d 6162 6f72 745d 205b 2d2d  c] [--abort] [--
-00002a70: 666f 6c6c 6f77 5d0a 2020 2020 2020 2020  follow].        
-00002a80: 2020 2020 2020 2020 205b 2d2d 696e 7465           [--inte
-00002a90: 7261 6374 6976 655d 205b 2d2d 7965 735d  ractive] [--yes]
-00002aa0: 0a0a 5965 6c6c 6f77 446f 6720 6578 616d  ..YellowDog exam
-00002ab0: 706c 6520 7574 696c 6974 7920 666f 7220  ple utility for 
-00002ac0: 6361 6e63 656c 6c69 6e67 2057 6f72 6b20  cancelling Work 
-00002ad0: 5265 7175 6972 656d 656e 7473 0a0a 6f70  Requirements..op
-00002ae0: 7469 6f6e 616c 2061 7267 756d 656e 7473  tional arguments
-00002af0: 3a0a 2020 2d68 2c20 2d2d 6865 6c70 2020  :.  -h, --help  
-00002b00: 2020 2020 2020 2020 2020 7368 6f77 2074            show t
-00002b10: 6869 7320 6865 6c70 206d 6573 7361 6765  his help message
-00002b20: 2061 6e64 2065 7869 740a 2020 2d2d 646f   and exit.  --do
-00002b30: 6373 2020 2020 2020 2020 2020 2020 2020  cs              
-00002b40: 2020 7072 6f76 6964 6520 6120 6c69 6e6b    provide a link
-00002b50: 2074 6f20 7468 6520 646f 6375 6d65 6e74   to the document
-00002b60: 6174 696f 6e20 666f 7220 7468 6973 2076  ation for this v
-00002b70: 6572 7369 6f6e 0a20 202d 2d63 6f6e 6669  ersion.  --confi
-00002b80: 6720 3c63 6f6e 6669 675f 6669 6c65 2e74  g <config_file.t
-00002b90: 6f6d 6c3e 2c20 2d63 203c 636f 6e66 6967  oml>, -c <config
-00002ba0: 5f66 696c 652e 746f 6d6c 3e0a 2020 2020  _file.toml>.    
-00002bb0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00002bc0: 2020 2020 636f 6e66 6967 7572 6174 696f      configuratio
-00002bd0: 6e20 6669 6c65 2069 6e20 544f 4d4c 2066  n file in TOML f
-00002be0: 6f72 6d61 743b 2064 6566 6175 6c74 2069  ormat; default i
-00002bf0: 7320 2763 6f6e 6669 672e 746f 6d6c 2720  s 'config.toml' 
-00002c00: 696e 2074 6865 2063 7572 7265 6e74 0a20  in the current. 
-00002c10: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00002c20: 2020 2020 2020 2064 6972 6563 746f 7279         directory
-00002c30: 0a20 202d 2d6b 6579 203c 6170 702d 6b65  .  --key <app-ke
-00002c40: 793e 2c20 2d6b 203c 6170 702d 6b65 793e  y>, -k <app-key>
-00002c50: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
-00002c60: 2020 2020 2020 2020 2074 6865 2059 656c           the Yel
-00002c70: 6c6f 7744 6f67 2041 7070 6c69 6361 7469  lowDog Applicati
-00002c80: 6f6e 206b 6579 0a20 202d 2d73 6563 7265  on key.  --secre
-00002c90: 7420 3c61 7070 2d73 6563 7265 743e 2c20  t <app-secret>, 
-00002ca0: 2d73 203c 6170 702d 7365 6372 6574 3e0a  -s <app-secret>.
+000017d0: 2020 202a 205b 7964 2d6c 6973 745d 2823     * [yd-list](#
+000017e0: 7964 2d6c 6973 7429 0a0a 3c21 2d2d 2041  yd-list)..<!-- A
+000017f0: 6464 6564 2062 793a 2070 7774 2c20 6174  dded by: pwt, at
+00001800: 3a20 5765 6420 4a75 6e20 3238 2031 313a  : Wed Jun 28 11:
+00001810: 3131 3a32 3520 4253 5420 3230 3233 202d  11:25 BST 2023 -
+00001820: 2d3e 0a0a 3c21 2d2d 7465 2d2d 3e0a 0a23  ->..<!--te-->..#
+00001830: 204f 7665 7276 6965 770a 0a54 6869 7320   Overview..This 
+00001840: 7265 706f 7369 746f 7279 2063 6f6e 7461  repository conta
+00001850: 696e 7320 6120 7365 7420 6f66 2065 7861  ins a set of exa
+00001860: 6d70 6c65 2050 7974 686f 6e20 7363 7269  mple Python scri
+00001870: 7074 7320 666f 7220 696e 7465 7261 6374  pts for interact
+00001880: 696e 6720 7769 7468 2074 6865 2059 656c  ing with the Yel
+00001890: 6c6f 7744 6f67 2050 6c61 7466 6f72 6d2e  lowDog Platform.
+000018a0: 2054 6865 2073 6372 6970 7473 2075 7365   The scripts use
+000018b0: 2074 6865 202a 2a5b 5965 6c6c 6f77 446f   the **[YellowDo
+000018c0: 6720 5079 7468 6f6e 2053 444b 5d28 6874  g Python SDK](ht
+000018d0: 7470 733a 2f2f 646f 6373 2e79 656c 6c6f  tps://docs.yello
+000018e0: 7764 6f67 2e63 6f2f 6170 692f 7079 7468  wdog.co/api/pyth
+000018f0: 6f6e 2f69 6e64 6578 2e68 746d 6c29 2a2a  on/index.html)**
+00001900: 2c20 7468 6520 636f 6465 2066 6f72 2077  , the code for w
+00001910: 6869 6368 2063 616e 2062 6520 666f 756e  hich can be foun
+00001920: 6420 5b6f 6e20 4769 7448 7562 5d28 6874  d [on GitHub](ht
+00001930: 7470 733a 2f2f 6769 7468 7562 2e63 6f6d  tps://github.com
+00001940: 2f79 656c 6c6f 7764 6f67 2f79 656c 6c6f  /yellowdog/yello
+00001950: 7764 6f67 2d73 646b 2d70 7974 686f 6e2d  wdog-sdk-python-
+00001960: 7075 626c 6963 292e 0a0a 0a2a 284e 6f74  public)....*(Not
+00001970: 653a 2074 6865 7365 2073 6372 6970 7473  e: these scripts
+00001980: 2061 7265 2069 6e74 656e 6465 6420 746f   are intended to
+00001990: 2062 6520 6120 6865 6c70 6675 6c20 7374   be a helpful st
+000019a0: 6172 7469 6e67 2070 6f69 6e74 2066 6f72  arting point for
+000019b0: 2065 7870 6572 696d 656e 7469 6e67 2077   experimenting w
+000019c0: 6974 6820 7468 6520 5965 6c6c 6f77 446f  ith the YellowDo
+000019d0: 6720 506c 6174 666f 726d 2e20 5468 6579  g Platform. They
+000019e0: 2061 7265 206e 6f74 2061 7373 7572 6564   are not assured
+000019f0: 2074 6f20 6265 206f 6620 7072 6f64 7563   to be of produc
+00001a00: 7469 6f6e 2071 7561 6c69 7479 206e 6f72  tion quality nor
+00001a10: 2064 6f20 7468 6579 2072 6570 7265 7365   do they represe
+00001a20: 6e74 2061 2073 7461 6e64 6172 6420 6f72  nt a standard or
+00001a30: 2072 6563 6f6d 6d65 6e64 6564 206d 6574   recommended met
+00001a40: 686f 6420 666f 7220 7573 696e 6720 5965  hod for using Ye
+00001a50: 6c6c 6f77 446f 672e 292a 0a0a 5468 6973  llowDog.)*..This
+00001a60: 2064 6f63 756d 656e 7461 7469 6f6e 2073   documentation s
+00001a70: 686f 756c 6420 6265 2072 6561 6420 696e  hould be read in
+00001a80: 2063 6f6e 6a75 6e63 7469 6f6e 2077 6974   conjunction wit
+00001a90: 6820 7468 6520 6d61 696e 202a 2a5b 5965  h the main **[Ye
+00001aa0: 6c6c 6f77 446f 6720 446f 6375 6d65 6e74  llowDog Document
+00001ab0: 6174 696f 6e5d 2868 7474 7073 3a2f 2f64  ation](https://d
+00001ac0: 6f63 732e 7965 6c6c 6f77 646f 672e 636f  ocs.yellowdog.co
+00001ad0: 292a 2a2c 2077 6869 6368 2070 726f 7669  )**, which provi
+00001ae0: 6465 7320 6120 636f 6d70 7265 6865 6e73  des a comprehens
+00001af0: 6976 6520 6465 7363 7269 7074 696f 6e20  ive description 
+00001b00: 6f66 2074 6865 2063 6f6e 6365 7074 7320  of the concepts 
+00001b10: 616e 6420 6f70 6572 6174 696f 6e20 6f66  and operation of
+00001b20: 2074 6865 2059 656c 6c6f 7744 6f67 2050   the YellowDog P
+00001b30: 6c61 7466 6f72 6d2e 0a0a 5465 6d70 6c61  latform...Templa
+00001b40: 7465 2073 6f6c 7574 696f 6e73 2066 6f72  te solutions for
+00001b50: 2065 7870 6572 696d 656e 7469 6e67 2077   experimenting w
+00001b60: 6974 6820 7468 6573 6520 7363 7269 7074  ith these script
+00001b70: 7320 6361 6e20 6265 2066 6f75 6e64 2069  s can be found i
+00001b80: 6e20 7468 6520 2a2a 5b70 7974 686f 6e2d  n the **[python-
+00001b90: 6578 616d 706c 6573 2d74 656d 706c 6174  examples-templat
+00001ba0: 6573 5d28 6874 7470 733a 2f2f 6769 7468  es](https://gith
+00001bb0: 7562 2e63 6f6d 2f79 656c 6c6f 7764 6f67  ub.com/yellowdog
+00001bc0: 2f70 7974 686f 6e2d 6578 616d 706c 6573  /python-examples
+00001bd0: 2d74 656d 706c 6174 6573 292a 2a20 7265  -templates)** re
+00001be0: 706f 7369 746f 7279 2e0a 0a54 6865 2073  pository...The s
+00001bf0: 6372 6970 7473 2070 726f 7669 6465 2074  cripts provide t
+00001c00: 6865 2066 6f6c 6c6f 7769 6e67 2063 6170  he following cap
+00001c10: 6162 696c 6974 6965 733a 0a0a 2d20 2a2a  abilities:..- **
+00001c20: 5072 6f76 6973 696f 6e69 6e67 2a2a 2057  Provisioning** W
+00001c30: 6f72 6b65 7220 506f 6f6c 7320 7769 7468  orker Pools with
+00001c40: 2074 6865 202a 2a60 7964 2d70 726f 7669   the **`yd-provi
+00001c50: 7369 6f6e 602a 2a20 636f 6d6d 616e 640a  sion`** command.
+00001c60: 2d20 2a2a 5375 626d 6974 7469 6e67 2a2a  - **Submitting**
+00001c70: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+00001c80: 7473 2077 6974 6820 7468 6520 2a2a 6079  ts with the **`y
+00001c90: 642d 7375 626d 6974 602a 2a20 636f 6d6d  d-submit`** comm
+00001ca0: 616e 640a 2d20 2a2a 5570 6c6f 6164 696e  and.- **Uploadin
+00001cb0: 672a 2a20 6669 6c65 7320 746f 2074 6865  g** files to the
+00001cc0: 2059 656c 6c6f 7744 6f67 204f 626a 6563   YellowDog Objec
+00001cd0: 7420 5374 6f72 6520 7769 7468 2074 6865  t Store with the
+00001ce0: 202a 2a60 7964 2d75 706c 6f61 6460 2a2a   **`yd-upload`**
+00001cf0: 2063 6f6d 6d61 6e64 0a2d 202a 2a49 6e73   command.- **Ins
+00001d00: 7461 6e74 6961 7469 6e67 2a2a 2043 6f6d  tantiating** Com
+00001d10: 7075 7465 2052 6571 7569 7265 6d65 6e74  pute Requirement
+00001d20: 7320 7769 7468 2074 6865 202a 2a60 7964  s with the **`yd
+00001d30: 2d69 6e73 7461 6e74 6961 7465 602a 2a20  -instantiate`** 
+00001d40: 636f 6d6d 616e 640a 2d20 2a2a 446f 776e  command.- **Down
+00001d50: 6c6f 6164 696e 672a 2a20 5265 7375 6c74  loading** Result
+00001d60: 7320 6672 6f6d 2074 6865 2059 656c 6c6f  s from the Yello
+00001d70: 7744 6f67 204f 626a 6563 7420 5374 6f72  wDog Object Stor
+00001d80: 6520 7769 7468 2074 6865 202a 2a60 7964  e with the **`yd
+00001d90: 2d64 6f77 6e6c 6f61 6460 2a2a 2063 6f6d  -download`** com
+00001da0: 6d61 6e64 0a2d 202a 2a41 626f 7274 696e  mand.- **Abortin
+00001db0: 672a 2a20 7275 6e6e 696e 6720 5461 736b  g** running Task
+00001dc0: 7320 7769 7468 2074 6865 202a 2a60 7964  s with the **`yd
+00001dd0: 2d61 626f 7274 602a 2a20 636f 6d6d 616e  -abort`** comman
+00001de0: 640a 2d20 2a2a 4361 6e63 656c 6c69 6e67  d.- **Cancelling
+00001df0: 2a2a 2057 6f72 6b20 5265 7175 6972 656d  ** Work Requirem
+00001e00: 656e 7473 2077 6974 6820 7468 6520 2a2a  ents with the **
+00001e10: 6079 642d 6361 6e63 656c 602a 2a20 636f  `yd-cancel`** co
+00001e20: 6d6d 616e 640a 2d20 2a2a 5368 7574 7469  mmand.- **Shutti
+00001e30: 6e67 2044 6f77 6e2a 2a20 576f 726b 6572  ng Down** Worker
+00001e40: 2050 6f6f 6c73 2077 6974 6820 7468 6520   Pools with the 
+00001e50: 2a2a 6079 642d 7368 7574 646f 776e 602a  **`yd-shutdown`*
+00001e60: 2a20 636f 6d6d 616e 640a 2d20 2a2a 5465  * command.- **Te
+00001e70: 726d 696e 6174 696e 672a 2a20 436f 6d70  rminating** Comp
+00001e80: 7574 6520 5265 7175 6972 656d 656e 7473  ute Requirements
+00001e90: 2077 6974 6820 7468 6520 2a2a 6079 642d   with the **`yd-
+00001ea0: 7465 726d 696e 6174 6560 2a2a 2063 6f6d  terminate`** com
+00001eb0: 6d61 6e64 0a2d 202a 2a44 656c 6574 696e  mand.- **Deletin
+00001ec0: 672a 2a20 6f62 6a65 6374 7320 696e 2074  g** objects in t
+00001ed0: 6865 2059 656c 6c6f 7744 6f67 204f 626a  he YellowDog Obj
+00001ee0: 6563 7420 5374 6f72 6520 7769 7468 2074  ect Store with t
+00001ef0: 6865 202a 2a60 7964 2d64 656c 6574 6560  he **`yd-delete`
+00001f00: 2a2a 2063 6f6d 6d61 6e64 0a2d 202a 2a4c  ** command.- **L
+00001f10: 6973 7469 6e67 2a2a 2059 656c 6c6f 7744  isting** YellowD
+00001f20: 6f67 2069 7465 6d73 2075 7369 6e67 2074  og items using t
+00001f30: 6865 202a 2a60 7964 2d6c 6973 7460 2a2a  he **`yd-list`**
+00001f40: 2063 6f6d 6d61 6e64 0a0a 5468 6520 6f70   command..The op
+00001f50: 6572 6174 696f 6e20 6f66 2074 6865 2063  eration of the c
+00001f60: 6f6d 6d61 6e64 7320 6973 2063 6f6e 7472  ommands is contr
+00001f70: 6f6c 6c65 6420 7573 696e 6720 544f 4d4c  olled using TOML
+00001f80: 2063 6f6e 6669 6775 7261 7469 6f6e 2066   configuration f
+00001f90: 696c 6573 2e20 496e 2061 6464 6974 696f  iles. In additio
+00001fa0: 6e2c 2057 6f72 6b20 5265 7175 6972 656d  n, Work Requirem
+00001fb0: 656e 7473 2061 6e64 2057 6f72 6b65 7220  ents and Worker 
+00001fc0: 506f 6f6c 7320 6361 6e20 6265 2064 6566  Pools can be def
+00001fd0: 696e 6564 2075 7369 6e67 204a 534f 4e20  ined using JSON 
+00001fe0: 6669 6c65 7320 7072 6f76 6964 696e 6720  files providing 
+00001ff0: 6578 7465 6e73 6976 6520 636f 6e66 6967  extensive config
+00002000: 7572 6162 696c 6974 792e 0a0a 2320 5965  urability...# Ye
+00002010: 6c6c 6f77 446f 6720 5072 6572 6571 7569  llowDog Prerequi
+00002020: 7369 7465 730a 0a54 6f20 7375 626d 6974  sites..To submit
+00002030: 202a 2a57 6f72 6b20 5265 7175 6972 656d   **Work Requirem
+00002040: 656e 7473 2a2a 2074 6f20 5965 6c6c 6f77  ents** to Yellow
+00002050: 446f 6720 666f 7220 7072 6f63 6573 7369  Dog for processi
+00002060: 6e67 2062 7920 436f 6e66 6967 7572 6564  ng by Configured
+00002070: 2057 6f72 6b65 7220 506f 6f6c 7320 286f   Worker Pools (o
+00002080: 6e2d 7072 656d 6973 6529 2061 6e64 2f6f  n-premise) and/o
+00002090: 7220 5072 6f76 6973 696f 6e65 6420 576f  r Provisioned Wo
+000020a0: 726b 6572 2050 6f6f 6c73 2028 636c 6f75  rker Pools (clou
+000020b0: 642d 7072 6f76 6973 696f 6e65 6420 7265  d-provisioned re
+000020c0: 736f 7572 6365 7329 2c20 796f 7527 6c6c  sources), you'll
+000020d0: 206e 6565 643a 0a0a 312e 2041 2059 656c   need:..1. A Yel
+000020e0: 6c6f 7744 6f67 2050 6c61 7466 6f72 6d20  lowDog Platform 
+000020f0: 4163 636f 756e 742e 0a0a 0a32 2e20 416e  Account....2. An
+00002100: 2041 7070 6c69 6361 7469 6f6e 204b 6579   Application Key
+00002110: 2026 2053 6563 7265 743a 2069 6e20 7468   & Secret: in th
+00002120: 6520 2a2a 4163 636f 756e 7473 2a2a 2073  e **Accounts** s
+00002130: 6563 7469 6f6e 2075 6e64 6572 2074 6865  ection under the
+00002140: 202a 2a41 7070 6c69 6361 7469 6f6e 732a   **Applications*
+00002150: 2a20 7461 6220 696e 2074 6865 205b 5965  * tab in the [Ye
+00002160: 6c6c 6f77 446f 6720 506f 7274 616c 5d28  llowDog Portal](
+00002170: 6874 7470 733a 2f2f 706f 7274 616c 2e79  https://portal.y
+00002180: 656c 6c6f 7764 6f67 2e63 6f2f 232f 6163  ellowdog.co/#/ac
+00002190: 636f 756e 742f 6170 706c 6963 6174 696f  count/applicatio
+000021a0: 6e73 292c 2075 7365 2074 6865 202a 2a41  ns), use the **A
+000021b0: 6464 2041 7070 6c69 6361 7469 6f6e 2a2a  dd Application**
+000021c0: 2062 7574 746f 6e20 746f 2063 7265 6174   button to creat
+000021d0: 6520 6120 6e65 7720 4170 706c 6963 6174  e a new Applicat
+000021e0: 696f 6e2c 2061 6e64 206d 616b 6520 6120  ion, and make a 
+000021f0: 6e6f 7465 206f 6620 6974 7320 2a2a 4b65  note of its **Ke
+00002200: 792a 2a20 616e 6420 2a2a 5365 6372 6574  y** and **Secret
+00002210: 2a2a 2028 7468 6573 6520 7769 6c6c 206f  ** (these will o
+00002220: 6e6c 7920 6265 2064 6973 706c 6179 6564  nly be displayed
+00002230: 206f 6e63 6529 2e0a 0a0a 546f 2063 7265   once)....To cre
+00002240: 6174 6520 2a2a 5072 6f76 6973 696f 6e65  ate **Provisione
+00002250: 6420 576f 726b 6572 2050 6f6f 6c73 2a2a  d Worker Pools**
+00002260: 2c20 796f 7527 6c6c 206e 6565 643a 0a0a  , you'll need:..
+00002270: 332e 2041 202a 2a4b 6579 7269 6e67 2a2a  3. A **Keyring**
+00002280: 2063 7265 6174 6564 2076 6961 2074 6865   created via the
+00002290: 2059 656c 6c6f 7744 6f67 2050 6f72 7461   YellowDog Porta
+000022a0: 6c2c 2077 6974 6820 6163 6365 7373 2074  l, with access t
+000022b0: 6f20 436c 6f75 6420 5072 6f76 6964 6572  o Cloud Provider
+000022c0: 2063 7265 6465 6e74 6961 6c73 2061 7320   credentials as 
+000022d0: 7265 7175 6972 6564 2e20 5468 6520 4170  required. The Ap
+000022e0: 706c 6963 6174 696f 6e20 6d75 7374 2062  plication must b
+000022f0: 6520 6772 616e 7465 6420 6163 6365 7373  e granted access
+00002300: 2074 6f20 7468 6520 4b65 7972 696e 672e   to the Keyring.
+00002310: 0a0a 0a34 2e20 4f6e 6520 6f72 206d 6f72  ...4. One or mor
+00002320: 6520 2a2a 436f 6d70 7574 6520 536f 7572  e **Compute Sour
+00002330: 6365 732a 2a20 6465 6669 6e65 642c 2061  ces** defined, a
+00002340: 6e64 2061 202a 2a43 6f6d 7075 7465 2052  nd a **Compute R
+00002350: 6571 7569 7265 6d65 6e74 2054 656d 706c  equirement Templ
+00002360: 6174 652a 2a20 6372 6561 7465 642e 2054  ate** created. T
+00002370: 6865 2069 6d61 6765 7320 7573 6564 2062  he images used b
+00002380: 7920 696e 7374 616e 6365 7320 6d75 7374  y instances must
+00002390: 2069 6e63 6c75 6465 2074 6865 2059 656c   include the Yel
+000023a0: 6c6f 7744 6f67 2061 6765 6e74 2c20 636f  lowDog agent, co
+000023b0: 6e66 6967 7572 6564 2077 6974 6820 7468  nfigured with th
+000023c0: 6520 5461 736b 2054 7970 6528 7329 2074  e Task Type(s) t
+000023d0: 6f20 6d61 7463 6820 7468 6520 576f 726b  o match the Work
+000023e0: 2052 6571 7569 7265 6d65 6e74 7320 746f   Requirements to
+000023f0: 2062 6520 7375 626d 6974 7465 642e 0a0a   be submitted...
+00002400: 546f 2073 6574 2075 7020 2a2a 436f 6e66  To set up **Conf
+00002410: 6967 7572 6564 2057 6f72 6b65 7220 506f  igured Worker Po
+00002420: 6f6c 732a 2a2c 2079 6f75 276c 6c20 6e65  ols**, you'll ne
+00002430: 6564 3a0a 0a35 2e20 4120 436f 6e66 6967  ed:..5. A Config
+00002440: 7572 6564 2057 6f72 6b65 7220 506f 6f6c  ured Worker Pool
+00002450: 2054 6f6b 656e 3a20 6672 6f6d 2074 6865   Token: from the
+00002460: 202a 2a57 6f72 6b65 7273 2a2a 2074 6162   **Workers** tab
+00002470: 2069 6e20 7468 6520 5b59 656c 6c6f 7744   in the [YellowD
+00002480: 6f67 2050 6f72 7461 6c5d 2868 7474 7073  og Portal](https
+00002490: 3a2f 2f70 6f72 7461 6c2e 7965 6c6c 6f77  ://portal.yellow
+000024a0: 646f 672e 636f 2f23 2f77 6f72 6b65 7273  dog.co/#/workers
+000024b0: 292c 2075 7365 2074 6865 202a 2a2b 4164  ), use the **+Ad
+000024c0: 6420 436f 6e66 6967 7572 6564 2057 6f72  d Configured Wor
+000024d0: 6b65 7220 506f 6f6c 2a2a 2062 7574 746f  ker Pool** butto
+000024e0: 6e20 746f 2063 7265 6174 6520 6120 6e65  n to create a ne
+000024f0: 7720 576f 726b 6572 2050 6f6f 6c20 616e  w Worker Pool an
+00002500: 6420 6765 6e65 7261 7465 2061 2074 6f6b  d generate a tok
+00002510: 656e 2e0a 0a0a 362e 204f 6274 6169 6e20  en....6. Obtain 
+00002520: 7468 6520 5965 6c6c 6f77 446f 6720 4167  the YellowDog Ag
+00002530: 656e 7420 616e 6420 696e 7374 616c 6c2f  ent and install/
+00002540: 636f 6e66 6967 7572 6520 6974 206f 6e20  configure it on 
+00002550: 796f 7572 206f 6e2d 7072 656d 6973 6520  your on-premise 
+00002560: 7379 7374 656d 7320 7573 696e 6720 7468  systems using th
+00002570: 6520 546f 6b65 6e20 6162 6f76 652e 0a0a  e Token above...
+00002580: 2320 5363 7269 7074 2049 6e73 7461 6c6c  # Script Install
+00002590: 6174 696f 6e20 7769 7468 2050 6970 0a0a  ation with Pip..
+000025a0: 5079 7468 6f6e 2076 6572 7369 6f6e 2033  Python version 3
+000025b0: 2e37 206f 7220 6c61 7465 7220 6973 2072  .7 or later is r
+000025c0: 6571 7569 7265 642e 2049 7427 7320 7265  equired. It's re
+000025d0: 636f 6d6d 656e 6465 6420 7468 6174 2069  commended that i
+000025e0: 6e73 7461 6c6c 6174 696f 6e20 6973 2070  nstallation is p
+000025f0: 6572 666f 726d 6564 2069 6e20 6120 5079  erformed in a Py
+00002600: 7468 6f6e 2076 6972 7475 616c 2065 6e76  thon virtual env
+00002610: 6972 6f6e 6d65 6e74 2028 6f72 2073 696d  ironment (or sim
+00002620: 696c 6172 2920 746f 2069 736f 6c61 7465  ilar) to isolate
+00002630: 2074 6865 2069 6e73 7461 6c6c 6174 696f   the installatio
+00002640: 6e20 6672 6f6d 206f 7468 6572 2050 7974  n from other Pyt
+00002650: 686f 6e20 656e 7669 726f 6e6d 656e 7473  hon environments
+00002660: 206f 6e20 796f 7572 2073 7973 7465 6d2e   on your system.
+00002670: 0a0a 496e 7374 616c 6c61 7469 6f6e 2061  ..Installation a
+00002680: 6e64 2073 7562 7365 7175 656e 7420 7570  nd subsequent up
+00002690: 6461 7465 2061 7265 2076 6961 2060 7069  date are via `pi
+000026a0: 7060 2061 6e64 2050 7950 4920 7573 696e  p` and PyPI usin
+000026b0: 673a 200a 0a60 6060 7368 656c 6c0a 7069  g: ..```shell.pi
+000026c0: 7020 696e 7374 616c 6c20 2d55 2079 656c  p install -U yel
+000026d0: 6c6f 7764 6f67 2d70 7974 686f 6e2d 6578  lowdog-python-ex
+000026e0: 616d 706c 6573 0a60 6060 0a0a 4966 2079  amples.```..If y
+000026f0: 6f75 2772 6520 696e 7465 7265 7374 6564  ou're interested
+00002700: 2069 6e20 696e 636c 7564 696e 6720 2a2a   in including **
+00002710: 4a73 6f6e 6e65 742a 2a20 7375 7070 6f72  Jsonnet** suppor
+00002720: 742c 2070 6c65 6173 6520 7365 6520 7468  t, please see th
+00002730: 6520 5b4a 736f 6e6e 6574 2053 7570 706f  e [Jsonnet Suppo
+00002740: 7274 5d28 236a 736f 6e6e 6574 2d73 7570  rt](#jsonnet-sup
+00002750: 706f 7274 2920 7365 6374 696f 6e20 6265  port) section be
+00002760: 6c6f 772e 0a0a 2320 5363 7269 7074 2049  low...# Script I
+00002770: 6e73 7461 6c6c 6174 696f 6e20 7769 7468  nstallation with
+00002780: 2050 6970 780a 0a54 6865 2063 6f6d 6d61   Pipx..The comma
+00002790: 6e64 7320 6361 6e20 616c 736f 2062 6520  nds can also be 
+000027a0: 696e 7374 616c 6c65 6420 7573 696e 6720  installed using 
+000027b0: 2a2a 5b70 6970 785d 2868 7474 7073 3a2f  **[pipx](https:/
+000027c0: 2f70 7970 612e 6769 7468 7562 2e69 6f2f  /pypa.github.io/
+000027d0: 7069 7078 2f29 2a2a 2e0a 0a54 6869 7320  pipx/)**...This 
+000027e0: 6d65 7468 6f64 2072 6571 7569 7265 7320  method requires 
+000027f0: 5079 7468 6f6e 2033 2e37 2b20 616e 6420  Python 3.7+ and 
+00002800: 7069 7078 2074 6f20 6265 2069 6e73 7461  pipx to be insta
+00002810: 6c6c 6564 2e20 546f 2069 6e73 7461 6c6c  lled. To install
+00002820: 3a0a 6060 6073 6865 6c6c 0a70 6970 7820  :.```shell.pipx 
+00002830: 696e 7374 616c 6c20 7965 6c6c 6f77 646f  install yellowdo
+00002840: 672d 7079 7468 6f6e 2d65 7861 6d70 6c65  g-python-example
+00002850: 730a 6060 600a 0a54 6f20 7570 6461 7465  s.```..To update
+00002860: 3a0a 6060 6073 6865 6c6c 0a70 6970 7820  :.```shell.pipx 
+00002870: 7570 6772 6164 6520 7965 6c6c 6f77 646f  upgrade yellowdo
+00002880: 672d 7079 7468 6f6e 2d65 7861 6d70 6c65  g-python-example
+00002890: 730a 6060 600a 0a23 2055 7361 6765 0a0a  s.```..# Usage..
+000028a0: 426f 7468 206f 6620 7468 6520 696e 7374  Both of the inst
+000028b0: 616c 6c61 7469 6f6e 206d 6574 686f 6473  allation methods
+000028c0: 2061 626f 7665 2077 696c 6c20 696e 7374   above will inst
+000028d0: 616c 6c20 6120 6e75 6d62 6572 206f 6620  all a number of 
+000028e0: 2a2a 6079 642d 602a 2a20 636f 6d6d 616e  **`yd-`** comman
+000028f0: 6473 206f 6e20 796f 7572 2050 4154 482e  ds on your PATH.
+00002900: 0a0a 436f 6d6d 616e 6473 2061 7265 2072  ..Commands are r
+00002910: 756e 2066 726f 6d20 7468 6520 636f 6d6d  un from the comm
+00002920: 616e 6420 6c69 6e65 2e20 496e 766f 6b69  and line. Invoki
+00002930: 6e67 2074 6865 2063 6f6d 6d61 6e64 2077  ng the command w
+00002940: 6974 6820 7468 6520 602d 2d68 656c 7060  ith the `--help`
+00002950: 206f 7220 602d 6860 206f 7074 696f 6e20   or `-h` option 
+00002960: 7769 6c6c 2064 6973 706c 6179 2074 6865  will display the
+00002970: 2063 6f6d 6d61 6e64 206c 696e 6520 6f70   command line op
+00002980: 7469 6f6e 7320 6170 706c 6963 6162 6c65  tions applicable
+00002990: 2074 6f20 6120 6769 7665 6e20 636f 6d6d   to a given comm
+000029a0: 616e 642c 2065 2e67 2e3a 0a0a 6060 6074  and, e.g.:..```t
+000029b0: 6578 740a 2025 2079 642d 6361 6e63 656c  ext. % yd-cancel
+000029c0: 202d 2d68 656c 700a 7573 6167 653a 2079   --help.usage: y
+000029d0: 642d 6361 6e63 656c 205b 2d68 5d20 5b2d  d-cancel [-h] [-
+000029e0: 2d64 6f63 735d 205b 2d2d 636f 6e66 6967  -docs] [--config
+000029f0: 203c 636f 6e66 6967 5f66 696c 652e 746f   <config_file.to
+00002a00: 6d6c 3e5d 205b 2d2d 6b65 7920 3c61 7070  ml>] [--key <app
+00002a10: 2d6b 6579 3e5d 0a20 2020 2020 2020 2020  -key>].         
+00002a20: 2020 2020 2020 2020 5b2d 2d73 6563 7265          [--secre
+00002a30: 7420 3c61 7070 2d73 6563 7265 743e 5d20  t <app-secret>] 
+00002a40: 5b2d 2d6e 616d 6573 7061 6365 203c 6e61  [--namespace <na
+00002a50: 6d65 7370 6163 653e 5d20 5b2d 2d74 6167  mespace>] [--tag
+00002a60: 203c 7461 673e 5d20 5b2d 2d75 726c 203c   <tag>] [--url <
+00002a70: 7572 6c3e 5d0a 2020 2020 2020 2020 2020  url>].          
+00002a80: 2020 2020 2020 205b 2d2d 7661 7269 6162         [--variab
+00002a90: 6c65 203c 7661 7231 3d76 313e 5d20 5b2d  le <var1=v1>] [-
+00002aa0: 2d71 7569 6574 5d20 5b2d 2d64 6562 7567  -quiet] [--debug
+00002ab0: 5d20 5b2d 2d70 6163 5d20 5b2d 2d61 626f  ] [--pac] [--abo
+00002ac0: 7274 5d20 5b2d 2d66 6f6c 6c6f 775d 0a20  rt] [--follow]. 
+00002ad0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00002ae0: 5b2d 2d69 6e74 6572 6163 7469 7665 5d20  [--interactive] 
+00002af0: 5b2d 2d79 6573 5d0a 0a59 656c 6c6f 7744  [--yes]..YellowD
+00002b00: 6f67 2065 7861 6d70 6c65 2075 7469 6c69  og example utili
+00002b10: 7479 2066 6f72 2063 616e 6365 6c6c 696e  ty for cancellin
+00002b20: 6720 576f 726b 2052 6571 7569 7265 6d65  g Work Requireme
+00002b30: 6e74 730a 0a6f 7074 696f 6e61 6c20 6172  nts..optional ar
+00002b40: 6775 6d65 6e74 733a 0a20 202d 682c 202d  guments:.  -h, -
+00002b50: 2d68 656c 7020 2020 2020 2020 2020 2020  -help           
+00002b60: 2073 686f 7720 7468 6973 2068 656c 7020   show this help 
+00002b70: 6d65 7373 6167 6520 616e 6420 6578 6974  message and exit
+00002b80: 0a20 202d 2d64 6f63 7320 2020 2020 2020  .  --docs       
+00002b90: 2020 2020 2020 2020 2070 726f 7669 6465           provide
+00002ba0: 2061 206c 696e 6b20 746f 2074 6865 2064   a link to the d
+00002bb0: 6f63 756d 656e 7461 7469 6f6e 2066 6f72  ocumentation for
+00002bc0: 2074 6869 7320 7665 7273 696f 6e0a 2020   this version.  
+00002bd0: 2d2d 636f 6e66 6967 203c 636f 6e66 6967  --config <config
+00002be0: 5f66 696c 652e 746f 6d6c 3e2c 202d 6320  _file.toml>, -c 
+00002bf0: 3c63 6f6e 6669 675f 6669 6c65 2e74 6f6d  <config_file.tom
+00002c00: 6c3e 0a20 2020 2020 2020 2020 2020 2020  l>.             
+00002c10: 2020 2020 2020 2020 2020 2063 6f6e 6669             confi
+00002c20: 6775 7261 7469 6f6e 2066 696c 6520 696e  guration file in
+00002c30: 2054 4f4d 4c20 666f 726d 6174 3b20 6465   TOML format; de
+00002c40: 6661 756c 7420 6973 2027 636f 6e66 6967  fault is 'config
+00002c50: 2e74 6f6d 6c27 2069 6e20 7468 6520 6375  .toml' in the cu
+00002c60: 7272 656e 740a 2020 2020 2020 2020 2020  rrent.          
+00002c70: 2020 2020 2020 2020 2020 2020 2020 6469                di
+00002c80: 7265 6374 6f72 790a 2020 2d2d 6b65 7920  rectory.  --key 
+00002c90: 3c61 7070 2d6b 6579 3e2c 202d 6b20 3c61  <app-key>, -k <a
+00002ca0: 7070 2d6b 6579 3e0a 2020 2020 2020 2020  pp-key>.        
 00002cb0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00002cc0: 2020 2020 2020 2020 7468 6520 5965 6c6c          the Yell
-00002cd0: 6f77 446f 6720 4170 706c 6963 6174 696f  owDog Applicatio
-00002ce0: 6e20 7365 6372 6574 0a20 202d 2d6e 616d  n secret.  --nam
-00002cf0: 6573 7061 6365 203c 6e61 6d65 7370 6163  espace <namespac
-00002d00: 653e 2c20 2d6e 203c 6e61 6d65 7370 6163  e>, -n <namespac
-00002d10: 653e 0a20 2020 2020 2020 2020 2020 2020  e>.             
-00002d20: 2020 2020 2020 2020 2020 2074 6865 206e             the n
-00002d30: 616d 6573 7061 6365 2074 6f20 7573 6520  amespace to use 
-00002d40: 7768 656e 2063 7265 6174 696e 6720 616e  when creating an
-00002d50: 6420 6964 656e 7469 6679 696e 6720 656e  d identifying en
-00002d60: 7469 7469 6573 0a20 202d 2d74 6167 203c  tities.  --tag <
-00002d70: 7461 673e 2c20 2d74 203c 7461 673e 0a20  tag>, -t <tag>. 
-00002d80: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00002d90: 2020 2020 2020 2074 6865 2074 6167 2074         the tag t
-00002da0: 6f20 7573 6520 666f 7220 7461 6767 696e  o use for taggin
-00002db0: 6720 616e 6420 6e61 6d69 6e67 2065 6e74  g and naming ent
-00002dc0: 6974 6965 730a 2020 2d2d 7572 6c20 3c75  ities.  --url <u
-00002dd0: 726c 3e2c 202d 7520 3c75 726c 3e0a 2020  rl>, -u <url>.  
-00002de0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00002df0: 2020 2020 2020 7468 6520 5552 4c20 6f66        the URL of
-00002e00: 2074 6865 2059 656c 6c6f 7744 6f67 2050   the YellowDog P
-00002e10: 6c61 7466 6f72 6d20 4150 490a 2020 2d2d  latform API.  --
-00002e20: 7661 7269 6162 6c65 203c 7661 7231 3d76  variable <var1=v
-00002e30: 313e 2c20 2d76 203c 7661 7231 3d76 313e  1>, -v <var1=v1>
-00002e40: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
-00002e50: 2020 2020 2020 2020 2075 7365 722d 6465           user-de
-00002e60: 6669 6e65 6420 7661 7269 6162 6c65 2073  fined variable s
-00002e70: 7562 7374 6974 7574 696f 6e73 3b20 6361  ubstitutions; ca
-00002e80: 6e20 6265 2073 7570 706c 6965 6420 6d75  n be supplied mu
-00002e90: 6c74 6970 6c65 2074 696d 6573 0a20 202d  ltiple times.  -
-00002ea0: 2d71 7569 6574 2c20 2d71 2020 2020 2020  -quiet, -q      
-00002eb0: 2020 2020 2073 7570 7072 6573 7320 286e       suppress (n
-00002ec0: 6f6e 2d65 7272 6f72 2c20 6e6f 6e2d 696e  on-error, non-in
-00002ed0: 7465 7261 6374 6976 6529 2073 7461 7475  teractive) statu
-00002ee0: 7320 616e 6420 7072 6f67 7265 7373 206d  s and progress m
-00002ef0: 6573 7361 6765 730a 2020 2d2d 6465 6275  essages.  --debu
-00002f00: 6720 2020 2020 2020 2020 2020 2020 2020  g               
-00002f10: 7072 696e 7420 6120 7374 6163 6b20 7472  print a stack tr
-00002f20: 6163 6520 2865 7463 2e29 206f 6e20 6572  ace (etc.) on er
-00002f30: 726f 720a 2020 2d2d 7061 6320 2020 2020  ror.  --pac     
-00002f40: 2020 2020 2020 2020 2020 2020 656e 6162              enab
-00002f50: 6c65 2050 4143 2028 7072 6f78 7920 6175  le PAC (proxy au
-00002f60: 746f 2d63 6f6e 6669 6775 7261 7469 6f6e  to-configuration
-00002f70: 2920 7375 7070 6f72 740a 2020 2d2d 6162  ) support.  --ab
-00002f80: 6f72 742c 202d 6120 2020 2020 2020 2020  ort, -a         
-00002f90: 2020 6162 6f72 7420 616c 6c20 7275 6e6e    abort all runn
-00002fa0: 696e 6720 7461 736b 7320 7769 7468 2069  ing tasks with i
-00002fb0: 6d6d 6564 6961 7465 2065 6666 6563 740a  mmediate effect.
-00002fc0: 2020 2d2d 666f 6c6c 6f77 2c20 2d66 2020    --follow, -f  
-00002fd0: 2020 2020 2020 2020 7768 656e 2075 7369          when usi
-00002fe0: 6e67 202d 2d61 626f 7274 2c20 706f 6c6c  ng --abort, poll
-00002ff0: 2075 6e74 696c 2061 6c6c 2054 6173 6b73   until all Tasks
-00003000: 2068 6176 6520 6265 656e 2061 626f 7274   have been abort
-00003010: 6564 0a20 202d 2d69 6e74 6572 6163 7469  ed.  --interacti
-00003020: 7665 2c20 2d69 2020 2020 206c 6973 742c  ve, -i     list,
-00003030: 2061 6e64 2069 6e74 6572 6163 7469 7665   and interactive
-00003040: 6c79 2073 656c 6563 742c 2069 7465 6d73  ly select, items
-00003050: 2074 6f20 6163 7420 6f6e 0a20 202d 2d79   to act on.  --y
-00003060: 6573 2c20 2d79 2020 2020 2020 2020 2020  es, -y          
-00003070: 2020 2070 6572 666f 726d 2064 6573 7472     perform destr
-00003080: 7563 7469 7665 2061 6374 696f 6e73 2077  uctive actions w
-00003090: 6974 686f 7574 2072 6571 7569 7269 6e67  ithout requiring
-000030a0: 2075 7365 7220 636f 6e66 6972 6d61 7469   user confirmati
-000030b0: 6f6e 0a60 6060 0a0a 2320 436f 6e66 6967  on.```..# Config
-000030c0: 7572 6174 696f 6e0a 0a42 7920 6465 6661  uration..By defa
-000030d0: 756c 742c 2074 6865 206f 7065 7261 7469  ult, the operati
-000030e0: 6f6e 206f 6620 616c 6c20 636f 6d6d 616e  on of all comman
-000030f0: 6473 2069 7320 636f 6e66 6967 7572 6564  ds is configured
-00003100: 2075 7369 6e67 2061 2054 4f4d 4c20 636f   using a TOML co
-00003110: 6e66 6967 7572 6174 696f 6e20 6669 6c65  nfiguration file
-00003120: 2e0a 0a54 6865 2063 6f6e 6669 6775 7261  ...The configura
-00003130: 7469 6f6e 2066 696c 6520 6861 7320 7468  tion file has th
-00003140: 7265 6520 706f 7373 6962 6c65 2073 6563  ree possible sec
-00003150: 7469 6f6e 733a 0a0a 312e 2041 2060 636f  tions:..1. A `co
-00003160: 6d6d 6f6e 6020 7365 6374 696f 6e20 7468  mmon` section th
-00003170: 6174 2063 6f6e 7461 696e 7320 7265 7175  at contains requ
-00003180: 6972 6564 2073 6563 7572 6974 7920 7072  ired security pr
-00003190: 6f70 6572 7469 6573 2066 6f72 2069 6e74  operties for int
-000031a0: 6572 6163 7469 6e67 2077 6974 6820 7468  eracting with th
-000031b0: 6520 5965 6c6c 6f77 446f 6720 706c 6174  e YellowDog plat
-000031c0: 666f 726d 2c20 7365 7473 2074 6865 204e  form, sets the N
-000031d0: 616d 6573 7061 6365 2069 6e20 7768 6963  amespace in whic
-000031e0: 6820 5965 6c6c 6f77 446f 6720 6173 7365  h YellowDog asse
-000031f0: 7473 2061 6e64 206f 626a 6563 7473 2061  ts and objects a
-00003200: 7265 2063 7265 6174 6564 2c20 616e 6420  re created, and 
-00003210: 6120 5461 6720 7468 6174 2069 7320 7573  a Tag that is us
-00003220: 6564 2066 6f72 2074 6167 6769 6e67 2061  ed for tagging a
-00003230: 6e64 206e 616d 696e 6720 6173 7365 7473  nd naming assets
-00003240: 2061 6e64 206f 626a 6563 7473 2e0a 322e   and objects..2.
-00003250: 2041 2060 776f 726b 5265 7175 6972 656d   A `workRequirem
-00003260: 656e 7460 2073 6563 7469 6f6e 2074 6861  ent` section tha
-00003270: 7420 6465 6669 6e65 7320 7468 6520 7072  t defines the pr
-00003280: 6f70 6572 7469 6573 206f 6620 576f 726b  operties of Work
-00003290: 2052 6571 7569 7265 6d65 6e74 7320 746f   Requirements to
-000032a0: 2062 6520 7375 626d 6974 7465 6420 746f   be submitted to
-000032b0: 2074 6865 2059 656c 6c6f 7744 6f67 2070   the YellowDog p
-000032c0: 6c61 7466 6f72 6d2e 0a33 2e20 4120 6077  latform..3. A `w
-000032d0: 6f72 6b65 7250 6f6f 6c60 2073 6563 7469  orkerPool` secti
-000032e0: 6f6e 2074 6861 7420 6465 6669 6e65 7320  on that defines 
-000032f0: 7468 6520 7072 6f70 6572 7469 6573 206f  the properties o
-00003300: 6620 5072 6f76 6973 6f6e 6564 2057 6f72  f Provisoned Wor
-00003310: 6b65 7220 506f 6f6c 7320 746f 2062 6520  ker Pools to be 
-00003320: 6372 6561 7465 6420 7573 696e 6720 7468  created using th
-00003330: 6520 5965 6c6c 6f77 446f 6720 706c 6174  e YellowDog plat
-00003340: 666f 726d 2e20 0a0a 5468 6572 6520 6973  form. ..There is
-00003350: 2061 2064 6f63 756d 656e 7465 6420 7465   a documented te
-00003360: 6d70 6c61 7465 2054 4f4d 4c20 6669 6c65  mplate TOML file
-00003370: 2070 726f 7669 6465 6420 696e 205b 636f   provided in [co
-00003380: 6e66 6967 2e74 6f6d 6c2e 7465 6d70 6c61  nfig.toml.templa
-00003390: 7465 5d28 636f 6e66 6967 2e74 6f6d 6c2e  te](config.toml.
-000033a0: 7465 6d70 6c61 7465 292c 2063 6f6e 7461  template), conta
-000033b0: 696e 696e 6720 7468 6520 6d61 696e 2070  ining the main p
-000033c0: 726f 7065 7274 6965 7320 7468 6174 2063  roperties that c
-000033d0: 616e 2062 6520 636f 6e66 6967 7572 6564  an be configured
-000033e0: 2e0a 0a54 6865 2063 6f6e 6669 6775 7261  ...The configura
-000033f0: 7469 6f6e 2066 696c 656e 616d 6520 6361  tion filename ca
-00003400: 6e20 6265 2073 7570 706c 6965 6420 696e  n be supplied in
-00003410: 2074 6872 6565 2064 6966 6665 7265 6e74   three different
-00003420: 2077 6179 733a 0a0a 312e 204f 6e20 7468   ways:..1. On th
-00003430: 6520 636f 6d6d 616e 6420 6c69 6e65 2c20  e command line, 
-00003440: 7573 696e 6720 7468 6520 602d 2d63 6f6e  using the `--con
-00003450: 6669 6760 206f 7220 602d 6360 206f 7074  fig` or `-c` opt
-00003460: 696f 6e73 2c20 652e 672e 3a3c 6272 3e60  ions, e.g.:<br>`
-00003470: 7964 2d73 7562 6d69 7420 2d63 206a 6f62  yd-submit -c job
-00003480: 732f 636f 6e66 6967 5f31 2e74 6f6d 6c60  s/config_1.toml`
-00003490: 0a32 2e20 5573 696e 6720 7468 6520 6059  .2. Using the `Y
-000034a0: 445f 434f 4e46 6020 656e 7669 726f 6e6d  D_CONF` environm
-000034b0: 656e 7420 7661 7269 6162 6c65 2c20 652e  ent variable, e.
-000034c0: 672e 3a20 3c62 723e 6065 7870 6f72 7420  g.: <br>`export 
-000034d0: 5944 5f43 4f4e 463d 226a 6f62 732f 636f  YD_CONF="jobs/co
-000034e0: 6e66 6967 5f31 2e74 6f6d 6c22 600a 332e  nfig_1.toml"`.3.
-000034f0: 2049 6620 6e65 6974 6865 7220 6f66 2074   If neither of t
-00003500: 6865 2061 626f 7665 2069 7320 7375 7070  he above is supp
-00003510: 6c69 6564 2c20 7468 6520 636f 6d6d 616e  lied, the comman
-00003520: 6473 206c 6f6f 6b20 666f 7220 6120 6063  ds look for a `c
-00003530: 6f6e 6669 672e 746f 6d6c 6020 6669 6c65  onfig.toml` file
-00003540: 2069 6e20 7468 6520 6375 7272 656e 7420   in the current 
-00003550: 6469 7265 6374 6f72 790a 0a54 6865 206f  directory..The o
-00003560: 7074 696f 6e73 2061 626f 7665 2061 7265  ptions above are
-00003570: 2073 686f 776e 2069 6e20 6f72 6465 7220   shown in order 
-00003580: 6f66 2070 7265 6365 6465 6e63 652c 2069  of precedence, i
-00003590: 2e65 2e2c 2061 2066 696c 656e 616d 6520  .e., a filename 
-000035a0: 7375 7070 6c69 6564 206f 6e20 7468 6520  supplied on the 
-000035b0: 636f 6d6d 616e 6420 6c69 6e65 2073 7570  command line sup
-000035c0: 6572 7365 6465 7320 6f6e 6520 7365 7420  ersedes one set 
-000035d0: 696e 2060 5944 5f43 4f4e 4660 2c20 7768  in `YD_CONF`, wh
-000035e0: 6963 6820 7375 7065 7273 6564 6573 2074  ich supersedes t
-000035f0: 6865 2064 6566 6175 6c74 2e0a 0a23 204e  he default...# N
-00003600: 616d 696e 6720 5275 6c65 730a 0a41 6c6c  aming Rules..All
-00003610: 2065 6e74 6974 7920 6e61 6d65 7320 7573   entity names us
-00003620: 6564 2077 6974 6869 6e20 7468 6520 5965  ed within the Ye
-00003630: 6c6c 6f77 446f 6720 506c 6174 666f 726d  llowDog Platform
-00003640: 206d 7573 7420 636f 6d70 6c79 2077 6974   must comply wit
-00003650: 6820 7468 6520 666f 6c6c 6f77 696e 6720  h the following 
-00003660: 7265 7374 7269 6374 696f 6e73 3a0a 0a2d  restrictions:..-
-00003670: 204e 616d 6573 2063 616e 206f 6e6c 7920   Names can only 
-00003680: 636f 6e74 6169 6e20 7468 6520 666f 6c6c  contain the foll
-00003690: 6f77 696e 673a 206c 6f77 6572 6361 7365  owing: lowercase
-000036a0: 206c 6574 7465 7273 2c20 6469 6769 7473   letters, digits
-000036b0: 2c20 6879 7068 656e 7320 616e 6420 756e  , hyphens and un
-000036c0: 6465 7273 636f 7265 7320 286e 6f74 6520  derscores (note 
-000036d0: 7468 6174 2073 7061 6365 7320 6172 6520  that spaces are 
-000036e0: 6e6f 7420 7065 726d 6974 7465 6429 0a2d  not permitted).-
-000036f0: 204e 616d 6573 206d 7573 7420 7374 6172   Names must star
-00003700: 7420 7769 7468 2061 206c 6574 7465 720a  t with a letter.
-00003710: 2d20 4e61 6d65 7320 6d75 7374 2065 6e64  - Names must end
-00003720: 2077 6974 6820 6120 6c65 7474 6572 206f   with a letter o
-00003730: 7220 6469 6769 740a 2d20 4e61 6d65 206c  r digit.- Name l
-00003740: 656e 6774 6820 6d75 7374 2062 6520 3c3d  ength must be <=
-00003750: 2036 3020 6368 6172 6163 7465 7273 0a0a   60 characters..
-00003760: 5468 6573 6520 7265 7374 7269 6374 696f  These restrictio
-00003770: 6e73 2061 7070 6c79 2074 6f20 656e 7469  ns apply to enti
-00003780: 7469 6573 2069 6e63 6c75 6469 6e67 204e  ties including N
-00003790: 616d 6573 7061 6365 732c 2054 6167 732c  amespaces, Tags,
-000037a0: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
-000037b0: 7473 2c20 5461 736b 2047 726f 7570 732c  ts, Task Groups,
-000037c0: 2054 6173 6b73 2c20 576f 726b 6572 2050   Tasks, Worker P
-000037d0: 6f6f 6c73 2c20 616e 6420 436f 6d70 7574  ools, and Comput
-000037e0: 6520 5265 7175 6972 656d 656e 7473 2c20  e Requirements, 
-000037f0: 616e 6420 616c 736f 2061 7070 6c79 2074  and also apply t
-00003800: 6f20 656e 7469 7469 6573 2074 6861 7420  o entities that 
-00003810: 6172 6520 6375 7272 656e 746c 7920 7573  are currently us
-00003820: 6564 2069 6e64 6972 6563 746c 7920 6279  ed indirectly by
-00003830: 2074 6865 7365 2073 6372 6970 7473 2c20   these scripts, 
-00003840: 696e 636c 7564 696e 6720 5573 6572 6e61  including Userna
-00003850: 6d65 732c 2043 7265 6465 6e74 6961 6c73  mes, Credentials
-00003860: 2c20 4b65 7972 696e 6773 2c20 436f 6d70  , Keyrings, Comp
-00003870: 7574 6520 536f 7572 6365 7320 616e 6420  ute Sources and 
-00003880: 436f 6d70 7574 6520 5465 6d70 6c61 7465  Compute Template
-00003890: 732e 0a0a 2320 436f 6d6d 6f6e 2050 726f  s...# Common Pro
-000038a0: 7065 7274 6965 730a 0a54 6865 2060 5b63  perties..The `[c
-000038b0: 6f6d 6d6f 6e5d 6020 7365 6374 696f 6e20  ommon]` section 
-000038c0: 6f66 2074 6865 2063 6f6e 6669 6775 7261  of the configura
-000038d0: 7469 6f6e 2066 696c 6520 6361 6e20 636f  tion file can co
-000038e0: 6e74 6169 6e20 7468 6520 666f 6c6c 6f77  ntain the follow
-000038f0: 696e 6720 7072 6f70 6572 7469 6573 3a0a  ing properties:.
-00003900: 0a7c 2050 726f 7065 7274 7920 2020 207c  .| Property    |
-00003910: 2044 6573 6372 6970 7469 6f6e 2020 2020   Description    
-00003920: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00003930: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00003940: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00003950: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00003960: 2020 2020 207c 0a7c 3a2d 2d2d 2d2d 2d2d       |.|:-------
-00003970: 2d2d 2d2d 2d7c 3a2d 2d2d 2d2d 2d2d 2d2d  -----|:---------
-00003980: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00003990: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000039a0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000039b0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000039c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c 0a7c 2060  -----------|.| `
-000039d0: 6b65 7960 2020 2020 2020 207c 2054 6865  key`       | The
-000039e0: 202a 2a6b 6579 2a2a 206f 6620 7468 6520   **key** of the 
-000039f0: 5965 6c6c 6f77 446f 6720 4170 706c 6963  YellowDog Applic
-00003a00: 6174 696f 6e20 756e 6465 7220 7768 6963  ation under whic
-00003a10: 6820 7468 6520 636f 6d6d 616e 6473 2077  h the commands w
-00003a20: 696c 6c20 7275 6e20 2020 2020 2020 2020  ill run         
-00003a30: 207c 0a7c 2060 7365 6372 6574 6020 2020   |.| `secret`   
-00003a40: 207c 2054 6865 202a 2a73 6563 7265 742a   | The **secret*
-00003a50: 2a20 6f66 2074 6865 2059 656c 6c6f 7744  * of the YellowD
-00003a60: 6f67 2041 7070 6c69 6361 7469 6f6e 2075  og Application u
-00003a70: 6e64 6572 2077 6869 6368 2074 6865 2063  nder which the c
-00003a80: 6f6d 6d61 6e64 7320 7769 6c6c 2072 756e  ommands will run
-00003a90: 2020 2020 2020 207c 0a7c 2060 6e61 6d65         |.| `name
-00003aa0: 7370 6163 6560 207c 2054 6865 202a 2a6e  space` | The **n
-00003ab0: 616d 6573 7061 6365 2a2a 2074 6f20 6265  amespace** to be
-00003ac0: 2075 7365 6420 666f 7220 6772 6f75 7069   used for groupi
-00003ad0: 6e67 2072 6573 6f75 7263 6573 2020 2020  ng resources    
-00003ae0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00003af0: 2020 2020 2020 2020 2020 2020 207c 0a7c               |.|
-00003b00: 2060 7461 6760 2020 2020 2020 207c 2054   `tag`       | T
-00003b10: 6865 202a 2a74 6167 2a2a 2074 6f20 6265  he **tag** to be
-00003b20: 2075 7365 6420 666f 7220 7461 6767 696e   used for taggin
-00003b30: 6720 7265 736f 7572 6365 7320 616e 6420  g resources and 
-00003b40: 6e61 6d69 6e67 206f 626a 6563 7473 2020  naming objects  
-00003b50: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00003b60: 2020 207c 0a7c 2060 7572 6c60 2020 2020     |.| `url`    
-00003b70: 2020 207c 2054 6865 202a 2a55 524c 2a2a     | The **URL**
-00003b80: 206f 6620 7468 6520 5965 6c6c 6f77 446f   of the YellowDo
-00003b90: 6720 506c 6174 666f 726d 2041 5049 2065  g Platform API e
-00003ba0: 6e64 706f 696e 742c 2069 6620 7468 6520  ndpoint, if the 
-00003bb0: 6465 6661 756c 7420 6973 6e27 7420 746f  default isn't to
-00003bc0: 2062 6520 7573 6564 207c 0a7c 2060 7573   be used |.| `us
-00003bd0: 6550 4143 6020 2020 207c 2055 7365 2050  ePAC`    | Use P
-00003be0: 4143 2028 7072 6f78 7920 6175 746f 636f  AC (proxy autoco
-00003bf0: 6e66 6967 7572 6174 696f 6e29 2069 6620  nfiguration) if 
-00003c00: 7365 7420 746f 2060 7472 7565 6020 2020  set to `true`   
-00003c10: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00003c20: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00003c30: 0a7c 2060 7661 7269 6162 6c65 7360 207c  .| `variables` |
-00003c40: 2041 2074 6162 6c65 2063 6f6e 7461 696e   A table contain
-00003c50: 696e 6720 2a2a 7661 7269 6162 6c65 2073  ing **variable s
-00003c60: 7562 7374 6974 7574 696f 6e73 2a2a 2028  ubstitutions** (
-00003c70: 7365 6520 7468 6520 5661 7269 6162 6c65  see the Variable
-00003c80: 7320 7365 6374 696f 6e20 6265 6c6f 7729  s section below)
-00003c90: 2020 2020 207c 0a0a 416e 2065 7861 6d70       |..An examp
-00003ca0: 6c65 2060 636f 6d6d 6f6e 6020 7365 6374  le `common` sect
-00003cb0: 696f 6e20 6973 2073 686f 776e 2062 656c  ion is shown bel
-00003cc0: 6f77 3a0a 0a60 6060 746f 6d6c 0a5b 636f  ow:..```toml.[co
-00003cd0: 6d6d 6f6e 5d0a 2020 2020 6b65 7920 3d20  mmon].    key = 
-00003ce0: 2261 7364 6667 686a 6b6c 7a78 6376 622d  "asdfghjklzxcvb-
-00003cf0: 3132 3334 3536 3722 0a20 2020 2073 6563  1234567".    sec
-00003d00: 7265 7420 3d20 2271 7765 7274 7975 696f  ret = "qwertyuio
-00003d10: 7061 7364 6667 686a 6b6c 7a78 6376 626e  pasdfghjklzxcvbn
-00003d20: 6d31 3233 3435 3637 3839 3071 7765 7274  m1234567890qwert
-00003d30: 7975 220a 2020 2020 6e61 6d65 7370 6163  yu".    namespac
-00003d40: 6520 3d20 2270 726f 6a65 6374 2d78 220a  e = "project-x".
-00003d50: 2020 2020 7461 6720 3d20 2274 6573 7469      tag = "testi
-00003d60: 6e67 2d7b 7b75 7365 726e 616d 657d 7d22  ng-{{username}}"
-00003d70: 0a60 6060 0a0a 496e 6465 6e74 6174 696f  .```..Indentatio
-00003d80: 6e20 6973 206f 7074 696f 6e61 6c20 696e  n is optional in
-00003d90: 2054 4f4d 4c20 6669 6c65 7320 616e 6420   TOML files and 
-00003da0: 6973 2066 6f72 2072 6561 6461 6269 6c69  is for readabili
-00003db0: 7479 206f 6e6c 792e 0a0a 2323 2048 5454  ty only...## HTT
-00003dc0: 5053 2050 726f 7879 2053 7570 706f 7274  PS Proxy Support
-00003dd0: 0a0a 5468 6520 636f 6d6d 616e 6473 2077  ..The commands w
-00003de0: 696c 6c20 7573 6520 7468 6520 7661 6c75  ill use the valu
-00003df0: 6520 6f66 2074 6865 2065 6e76 6972 6f6e  e of the environ
-00003e00: 6d65 6e74 2076 6172 6961 626c 6520 6048  ment variable `H
-00003e10: 5454 5053 5f50 524f 5859 6020 6966 2072  TTPS_PROXY` if r
-00003e20: 6f75 7469 6e67 2074 6872 6f75 6768 2061  outing through a
-00003e30: 2070 726f 7879 2069 7320 7265 7175 6972   proxy is requir
-00003e40: 6564 2e0a 0a49 6e20 6164 6469 7469 6f6e  ed...In addition
-00003e50: 2c20 7468 6520 636f 6d6d 616e 6473 2063  , the commands c
-00003e60: 616e 2075 7365 2070 726f 7879 2061 7574  an use proxy aut
-00003e70: 6f63 6f6e 6669 6775 7261 7469 6f6e 2028  oconfiguration (
-00003e80: 5041 4329 2069 6620 7468 6520 602d 2d70  PAC) if the `--p
-00003e90: 6163 6020 636f 6d6d 616e 6420 6c69 6e65  ac` command line
-00003ea0: 206f 7074 696f 6e20 6973 2073 7065 6369   option is speci
-00003eb0: 6669 6564 2c20 6f72 2069 6620 7468 6520  fied, or if the 
-00003ec0: 6075 7365 5041 4360 2070 726f 7065 7274  `usePAC` propert
-00003ed0: 7920 6973 2073 6574 2074 6f20 6074 7275  y is set to `tru
-00003ee0: 6560 2069 6e20 7468 6520 605b 636f 6d6d  e` in the `[comm
-00003ef0: 6f6e 5d60 2073 6563 7469 6f6e 206f 6620  on]` section of 
-00003f00: 7468 6520 6063 6f6e 6669 672e 746f 6d6c  the `config.toml
-00003f10: 6020 6669 6c65 2e0a 0a23 2320 5370 6563  ` file...## Spec
-00003f20: 6966 7969 6e67 2043 6f6d 6d6f 6e20 5072  ifying Common Pr
-00003f30: 6f70 6572 7469 6573 2075 7369 6e67 2074  operties using t
-00003f40: 6865 2043 6f6d 6d61 6e64 204c 696e 6520  he Command Line 
-00003f50: 6f72 2045 6e76 6972 6f6e 6d65 6e74 2056  or Environment V
-00003f60: 6172 6961 626c 6573 0a0a 416c 6c20 7468  ariables..All th
-00003f70: 6520 636f 6d6d 6f6e 2070 726f 7065 7274  e common propert
-00003f80: 6965 7320 6361 6e20 6265 2073 6574 2075  ies can be set u
-00003f90: 7369 6e67 2063 6f6d 6d61 6e64 206c 696e  sing command lin
-00003fa0: 6520 6f70 7469 6f6e 732c 206f 7220 696e  e options, or in
-00003fb0: 2065 6e76 6972 6f6e 6d65 6e74 2076 6172   environment var
-00003fc0: 6961 626c 6573 2e0a 0a54 6865 202a 2a63  iables...The **c
-00003fd0: 6f6d 6d61 6e64 206c 696e 6520 6f70 7469  ommand line opti
-00003fe0: 6f6e 732a 2a20 6172 6520 6173 2066 6f6c  ons** are as fol
-00003ff0: 6c6f 7773 3a0a 0a2d 2060 2d2d 6b65 7960  lows:..- `--key`
-00004000: 206f 7220 602d 6b60 0a2d 2060 2d2d 7365   or `-k`.- `--se
-00004010: 6372 6574 6020 6f72 2060 2d73 600a 2d20  cret` or `-s`.- 
-00004020: 602d 2d6e 616d 6573 7061 6365 6020 6f72  `--namespace` or
-00004030: 2060 2d6e 600a 2d20 602d 2d74 6167 6020   `-n`.- `--tag` 
-00004040: 6f72 2060 2d74 600a 2d20 602d 2d75 726c  or `-t`.- `--url
-00004050: 6020 6f72 2060 2d75 600a 2d20 602d 2d70  ` or `-u`.- `--p
-00004060: 6163 600a 0a54 6865 7365 206f 7074 696f  ac`..These optio
-00004070: 6e73 2063 616e 2061 6c73 6f20 6265 206c  ns can also be l
-00004080: 6973 7465 6420 6279 2072 756e 6e69 6e67  isted by running
-00004090: 2061 2063 6f6d 6d61 6e64 2077 6974 6820   a command with 
-000040a0: 7468 6520 602d 2d68 656c 7060 206f 7220  the `--help` or 
-000040b0: 602d 6860 206f 7074 696f 6e2e 0a0a 5468  `-h` option...Th
-000040c0: 6520 2a2a 656e 7669 726f 6e6d 656e 7420  e **environment 
-000040d0: 7661 7269 6162 6c65 732a 2a20 6172 6520  variables** are 
-000040e0: 6173 2066 6f6c 6c6f 7773 3a0a 0a2d 2060  as follows:..- `
-000040f0: 5944 5f4b 4559 600a 2d20 6059 445f 5345  YD_KEY`.- `YD_SE
-00004100: 4352 4554 600a 2d20 6059 445f 4e41 4d45  CRET`.- `YD_NAME
-00004110: 5350 4143 4560 0a2d 2060 5944 5f54 4147  SPACE`.- `YD_TAG
-00004120: 600a 2d20 6059 445f 5552 4c60 0a0a 5768  `.- `YD_URL`..Wh
-00004130: 656e 2073 6574 7469 6e67 2074 6865 2076  en setting the v
-00004140: 616c 7565 206f 6620 7468 6520 6162 6f76  alue of the abov
-00004150: 6520 7072 6f70 6572 7469 6573 2c20 6120  e properties, a 
-00004160: 7072 6f70 6572 7479 2073 6574 206f 6e20  property set on 
-00004170: 7468 6520 636f 6d6d 616e 6420 6c69 6e65  the command line
-00004180: 2074 616b 6573 2070 7265 6365 6465 6e63   takes precedenc
-00004190: 6520 6f76 6572 206f 6e65 2073 6574 2076  e over one set v
-000041a0: 6961 2061 6e20 656e 7669 726f 6e6d 656e  ia an environmen
-000041b0: 7420 7661 7269 6162 6c65 2c20 616e 6420  t variable, and 
-000041c0: 626f 7468 2074 616b 6520 7072 6563 6564  both take preced
-000041d0: 656e 6365 206f 7665 7220 6120 7661 6c75  ence over a valu
-000041e0: 6520 7365 7420 696e 2061 2063 6f6e 6669  e set in a confi
-000041f0: 6775 7261 7469 6f6e 2066 696c 652e 0a0a  guration file...
-00004200: 4966 2061 6c6c 2074 6865 2072 6571 7569  If all the requi
-00004210: 7265 6420 636f 6d6d 6f6e 2070 726f 7065  red common prope
-00004220: 7274 6965 7320 6172 6520 7365 7420 7573  rties are set us
-00004230: 696e 6720 7468 6520 636f 6d6d 616e 6420  ing the command 
-00004240: 6c69 6e65 206f 7220 656e 7669 726f 6e6d  line or environm
-00004250: 656e 7420 7661 7269 6162 6c65 732c 2074  ent variables, t
-00004260: 6865 6e20 7468 6520 656e 7469 7265 2060  hen the entire `
-00004270: 636f 6d6d 6f6e 6020 7365 6374 696f 6e20  common` section 
-00004280: 6f66 2074 6865 2054 4f4d 4c20 6669 6c65  of the TOML file
-00004290: 2063 616e 2062 6520 6f6d 6974 7465 642e   can be omitted.
-000042a0: 0a0a 2323 2056 6172 6961 626c 6520 5375  ..## Variable Su
-000042b0: 6273 7469 7475 7469 6f6e 7320 696e 2043  bstitutions in C
-000042c0: 6f6d 6d6f 6e20 5072 6f70 6572 7469 6573  ommon Properties
-000042d0: 0a0a 4e6f 7465 2074 6865 2075 7365 206f  ..Note the use o
-000042e0: 6620 607b 7b75 7365 726e 616d 657d 7d60  f `{{username}}`
-000042f0: 2069 6e20 7468 6520 7661 6c75 6520 6f66   in the value of
-00004300: 2074 6865 2060 7461 6760 2070 726f 7065   the `tag` prope
-00004310: 7274 793a 2074 6869 7320 6973 2061 202a  rty: this is a *
-00004320: 2a76 6172 6961 626c 6520 7375 6273 7469  *variable substi
-00004330: 7475 7469 6f6e 2a2a 2074 6861 7420 6361  tution** that ca
-00004340: 6e20 6f70 7469 6f6e 616c 6c79 2062 6520  n optionally be 
-00004350: 7573 6564 2074 6f20 696e 7365 7274 2074  used to insert t
-00004360: 6865 206c 6f67 696e 2075 7365 726e 616d  he login usernam
-00004370: 6520 6f66 2074 6865 2075 7365 7220 7275  e of the user ru
-00004380: 6e6e 696e 6720 7468 6520 636f 6d6d 616e  nning the comman
-00004390: 6473 2e20 536f 2c20 666f 7220 7573 6572  ds. So, for user
-000043a0: 6e61 6d65 2060 6162 6360 2c20 7468 6520  name `abc`, the 
-000043b0: 6074 6167 6020 776f 756c 6420 6265 2073  `tag` would be s
-000043c0: 6574 2074 6f20 6074 6573 7469 6e67 2d61  et to `testing-a
-000043d0: 6263 602e 2054 6869 7320 6361 6e20 6265  bc`. This can be
-000043e0: 2068 656c 7066 756c 2074 6f20 6469 7361   helpful to disa
-000043f0: 6d62 6967 7561 7465 206d 756c 7469 706c  mbiguate multipl
-00004400: 6520 7573 6572 7320 7275 6e6e 696e 6720  e users running 
-00004410: 7769 7468 2074 6865 2073 616d 6520 636f  with the same co
-00004420: 6e66 6967 7572 6174 696f 6e20 6461 7461  nfiguration data
-00004430: 2e0a 0a56 6172 6961 626c 6520 7375 6273  ...Variable subs
-00004440: 7469 7475 7469 6f6e 7320 6172 6520 6469  titutions are di
-00004450: 7363 7573 7365 6420 6265 6c6f 772e 0a0a  scussed below...
-00004460: 2320 5661 7269 6162 6c65 2053 7562 7374  # Variable Subst
-00004470: 6974 7574 696f 6e73 0a0a 5661 7269 6162  itutions..Variab
-00004480: 6c65 2073 7562 7374 6974 7574 696f 6e73  le substitutions
-00004490: 2070 726f 7669 6465 2061 2070 6f77 6572   provide a power
-000044a0: 6675 6c20 7761 7920 6f66 2069 6e74 726f  ful way of intro
-000044b0: 6475 6369 6e67 2076 6172 6961 626c 6520  ducing variable 
-000044c0: 7661 6c75 6573 2069 6e74 6f20 544f 4d4c  values into TOML
-000044d0: 2063 6f6e 6669 6775 7261 7469 6f6e 2066   configuration f
-000044e0: 696c 6573 2c20 576f 726b 2052 6571 7569  iles, Work Requi
-000044f0: 7265 6d65 6e74 204a 534f 4e20 6465 6669  rement JSON defi
-00004500: 6e69 7469 6f6e 732c 2061 6e64 2057 6f72  nitions, and Wor
-00004510: 6b65 7220 506f 6f6c 204a 534f 4e20 6465  ker Pool JSON de
-00004520: 6669 6e69 7469 6f6e 732e 2054 6865 7920  finitions. They 
-00004530: 6361 6e20 6265 2069 6e63 6c75 6465 6420  can be included 
-00004540: 696e 2074 6865 2076 616c 7565 206f 6620  in the value of 
-00004550: 616e 7920 7072 6f70 6572 7479 2069 6e20  any property in 
-00004560: 6561 6368 206f 6620 7468 6573 6520 6f62  each of these ob
-00004570: 6a65 6374 732c 2069 6e63 6c75 6469 6e67  jects, including
-00004580: 2069 6e20 7661 6c75 6573 2077 6974 6869   in values withi
-00004590: 6e20 6c69 7374 7320 2865 2e67 2e2c 2066  n lists (e.g., f
-000045a0: 6f72 2074 6865 2060 6172 6775 6d65 6e74  or the `argument
-000045b0: 7360 2070 726f 7065 7274 7929 2061 6e64  s` property) and
-000045c0: 2061 7272 6179 7320 2865 2e67 2e2c 2074   arrays (e.g., t
-000045d0: 6865 2060 656e 7669 726f 6e6d 656e 7460  he `environment`
-000045e0: 2070 726f 7065 7274 7929 2e0a 0a56 6172   property)...Var
-000045f0: 6961 626c 6520 7375 6273 7469 7475 7469  iable substituti
-00004600: 6f6e 7320 6172 6520 6578 7072 6573 7365  ons are expresse
-00004610: 6420 7573 696e 6720 607b 7b76 6172 6961  d using `{{varia
-00004620: 626c 657d 7d60 206e 6f74 6174 696f 6e2c  ble}}` notation,
-00004630: 2077 6865 7265 2074 6865 2065 7870 7265   where the expre
-00004640: 7373 696f 6e20 6973 2072 6570 6c61 6365  ssion is replace
-00004650: 6420 6279 2074 6865 2076 616c 7565 206f  d by the value o
-00004660: 6620 6076 6172 6961 626c 6560 2e0a 0a53  f `variable`...S
-00004670: 7562 7374 6974 7574 696f 6e73 2063 616e  ubstitutions can
-00004680: 2061 6c73 6f20 6265 2070 6572 666f 726d   also be perform
-00004690: 6564 2066 6f72 206e 6f6e 2d73 7472 696e  ed for non-strin
-000046a0: 6720 286e 756d 6265 7220 616e 6420 626f  g (number and bo
-000046b0: 6f6c 6561 6e29 2076 616c 7565 7320 7573  olean) values us
-000046c0: 696e 6720 7468 6520 606e 756d 3a60 2061  ing the `num:` a
-000046d0: 6e64 2060 626f 6f6c 3a60 2070 7265 6669  nd `bool:` prefi
-000046e0: 7865 7320 7769 7468 696e 2074 6865 2076  xes within the v
-000046f0: 6172 6961 626c 6520 7375 6273 7469 7475  ariable substitu
-00004700: 7469 6f6e 3a0a 0a2d 2044 6566 696e 6520  tion:..- Define 
-00004710: 7468 6520 7661 7269 6162 6c65 2073 7562  the variable sub
-00004720: 7374 6974 7574 696f 6e20 7573 696e 6720  stitution using 
-00004730: 6f6e 6520 6f66 2074 6865 2066 6f6c 6c6f  one of the follo
-00004740: 7769 6e67 2070 6174 7465 726e 733a 2060  wing patterns: `
-00004750: 227b 7b6e 756d 3a6d 795f 696e 747d 7d22  "{{num:my_int}}"
-00004760: 602c 2060 227b 7b6e 756d 3a6d 795f 666c  `, `"{{num:my_fl
-00004770: 6f61 747d 7d22 602c 2060 227b 7b62 6f6f  oat}}"`, `"{{boo
-00004780: 6c3a 6d79 5f62 6f6f 6c7d 7d22 600a 2d20  l:my_bool}}"`.- 
-00004790: 5661 7269 6162 6c65 2064 6566 696e 6974  Variable definit
-000047a0: 696f 6e73 2073 7570 706c 6965 6420 6f6e  ions supplied on
-000047b0: 2074 6865 2063 6f6d 6d61 6e64 206c 696e   the command lin
-000047c0: 6520 776f 756c 6420 7468 656e 2062 6520  e would then be 
-000047d0: 6f66 2074 6865 2066 6f72 6d3a 2060 2d6d  of the form: `-m
-000047e0: 206d 795f 696e 743d 3520 2d6d 206d 795f   my_int=5 -m my_
-000047f0: 666c 6f61 743d 322e 3520 2d6d 206d 795f  float=2.5 -m my_
-00004800: 626f 6f6c 3d74 7275 6560 0a2d 2049 6e20  bool=true`.- In 
-00004810: 7468 6520 7072 6f63 6573 7365 6420 4a53  the processed JS
-00004820: 4f4e 206f 7220 544f 4d4c 2c20 7468 6573  ON or TOML, thes
-00004830: 6520 7661 6c75 6573 2077 6f75 6c64 2062  e values would b
-00004840: 6563 6f6d 6520 6035 602c 2060 322e 3560  ecome `5`, `2.5`
-00004850: 2061 6e64 2060 7472 7565 602c 2072 6573   and `true`, res
-00004860: 7065 6374 6976 656c 792c 2063 6f6e 7665  pectively, conve
-00004870: 7274 6564 2066 726f 6d20 7374 7269 6e67  rted from string
-00004880: 7320 746f 2074 6865 6972 2063 6f72 7265  s to their corre
-00004890: 6374 204a 534f 4e20 7479 7065 730a 0a23  ct JSON types..#
-000048a0: 2320 4465 6661 756c 7420 5661 7269 6162  # Default Variab
-000048b0: 6c65 730a 0a54 6865 2066 6f6c 6c6f 7769  les..The followi
-000048c0: 6e67 2073 7562 7374 6974 7574 696f 6e73  ng substitutions
-000048d0: 2061 7265 2061 7574 6f6d 6174 6963 616c   are automatical
-000048e0: 6c79 2063 7265 6174 6564 2061 6e64 2063  ly created and c
-000048f0: 616e 2062 6520 7573 6564 2069 6e20 616e  an be used in an
-00004900: 7920 7365 6374 696f 6e20 6f66 2074 6865  y section of the
-00004910: 2063 6f6e 6669 6775 7261 7469 6f6e 2066   configuration f
-00004920: 696c 652c 206f 7220 696e 2061 6e79 204a  ile, or in any J
-00004930: 534f 4e20 7370 6563 6966 6963 6174 696f  SON specificatio
-00004940: 6e3a 0a0a 7c20 4469 7265 6374 6976 6520  n:..| Directive 
-00004950: 2020 2020 2020 7c20 4465 7363 7269 7074        | Descript
-00004960: 696f 6e20 2020 2020 2020 2020 2020 2020  ion             
-00004970: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004980: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004990: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000049a0: 207c 2045 7861 6d70 6c65 206f 6620 5375   | Example of Su
-000049b0: 6273 7469 7475 7469 6f6e 207c 0a7c 3a2d  bstitution |.|:-
-000049c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c  ---------------|
-000049d0: 3a2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  :---------------
-000049e0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000049f0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00004a00: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00004a10: 2d2d 2d2d 2d2d 2d2d 2d2d 7c3a 2d2d 2d2d  ----------|:----
-00004a20: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00004a30: 2d2d 2d2d 7c0a 7c20 607b 7b75 7365 726e  ----|.| `{{usern
-00004a40: 616d 657d 7d60 2020 7c20 5468 6520 6375  ame}}`  | The cu
-00004a50: 7272 656e 7420 7573 6572 2773 206c 6f67  rrent user's log
-00004a60: 696e 2075 7365 726e 616d 652c 206c 6f77  in username, low
-00004a70: 6572 2063 6173 652c 2073 7061 6365 7320  er case, spaces 
-00004a80: 7265 706c 6163 6564 2020 2020 2020 2020  replaced        
-00004a90: 2020 207c 206a 616e 655f 736d 6974 6820     | jane_smith 
-00004aa0: 2020 2020 2020 2020 2020 2020 207c 0a7c               |.|
-00004ab0: 2060 7b7b 6461 7465 7d7d 6020 2020 2020   `{{date}}`     
-00004ac0: 207c 2054 6865 2063 7572 7265 6e74 2064   | The current d
-00004ad0: 6174 6520 2855 5443 293a 2059 5959 594d  ate (UTC): YYYYM
-00004ae0: 4d44 4420 2020 2020 2020 2020 2020 2020  MDD             
-00004af0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004b00: 2020 2020 2020 2020 2020 2020 7c20 3230              | 20
-00004b10: 3232 3130 3237 2020 2020 2020 2020 2020  221027          
-00004b20: 2020 2020 2020 7c0a 7c20 607b 7b74 696d        |.| `{{tim
-00004b30: 657d 7d60 2020 2020 2020 7c20 5468 6520  e}}`      | The 
-00004b40: 6375 7272 656e 7420 7469 6d65 2028 5554  current time (UT
-00004b50: 4329 3a20 4848 4d4d 5353 2020 2020 2020  C): HHMMSS      
-00004b60: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004b70: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004b80: 2020 2020 207c 2031 3633 3032 3620 2020       | 163026   
-00004b90: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00004ba0: 0a7c 2060 7b7b 6461 7465 7469 6d65 7d7d  .| `{{datetime}}
-00004bb0: 6020 207c 2043 6f6e 6361 7465 6e61 7469  `  | Concatenati
-00004bc0: 6f6e 206f 6620 7468 6520 6461 7465 2061  on of the date a
-00004bd0: 6e64 2074 696d 6520 6162 6f76 652c 2077  nd time above, w
-00004be0: 6974 6820 6120 272d 2720 7365 7061 7261  ith a '-' separa
-00004bf0: 746f 7220 2020 2020 2020 2020 2020 7c20  tor           | 
-00004c00: 3230 3232 3130 3237 2d31 3633 3032 3620  20221027-163026 
-00004c10: 2020 2020 2020 2020 7c0a 7c20 607b 7b72          |.| `{{r
-00004c20: 616e 646f 6d7d 7d60 2020 2020 7c20 4120  andom}}`    | A 
-00004c30: 7261 6e64 6f6d 2c20 7468 7265 6520 6469  random, three di
-00004c40: 6769 7420 6865 7861 6465 6369 6d61 6c20  git hexadecimal 
-00004c50: 6e75 6d62 6572 2028 6c6f 7765 7220 6361  number (lower ca
-00004c60: 7365 2920 2020 2020 2020 2020 2020 2020  se)             
-00004c70: 2020 2020 2020 207c 2061 3163 2020 2020         | a1c    
-00004c80: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004c90: 207c 0a7c 2060 7b7b 6e61 6d65 7370 6163   |.| `{{namespac
-00004ca0: 657d 7d60 207c 2054 6865 2060 6e61 6d65  e}}` | The `name
-00004cb0: 7370 6163 6560 2070 726f 7065 7274 792e  space` property.
-00004cc0: 204e 6f74 6520 7468 6174 2060 6e61 6d65   Note that `name
-00004cd0: 7370 6163 6560 206d 7573 742c 206f 6620  space` must, of 
-00004ce0: 636f 7572 7365 2c20 6265 2073 6574 2e20  course, be set. 
-00004cf0: 7c20 6d79 5f6e 616d 6573 7061 6365 2020  | my_namespace  
-00004d00: 2020 2020 2020 2020 2020 7c0a 7c20 607b            |.| `{
-00004d10: 7b74 6167 7d7d 6020 2020 2020 2020 7c20  {tag}}`       | 
-00004d20: 5468 6520 6074 6167 6020 7072 6f70 6572  The `tag` proper
-00004d30: 7479 2e20 4e6f 7465 2074 6861 7420 6074  ty. Note that `t
-00004d40: 6167 6020 6d75 7374 2062 6520 7365 742e  ag` must be set.
-00004d50: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004d60: 2020 2020 2020 2020 207c 206d 795f 7461           | my_ta
-00004d70: 6720 2020 2020 2020 2020 2020 2020 2020  g               
-00004d80: 2020 207c 0a7c 2060 7b7b 6b65 797d 7d60     |.| `{{key}}`
-00004d90: 2020 2020 2020 207c 2054 6865 2061 7070         | The app
-00004da0: 6c69 6361 7469 6f6e 2060 6b65 7960 2070  lication `key` p
-00004db0: 726f 7065 7274 792e 2020 2020 2020 2020  roperty.        
-00004dc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004dd0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004de0: 2020 7c20 2020 2020 2020 2020 2020 2020    |             
-00004df0: 2020 2020 2020 2020 2020 2020 7c0a 7c20              |.| 
-00004e00: 607b 7b73 6563 7265 747d 7d60 2020 2020  `{{secret}}`    
-00004e10: 7c20 5468 6520 6170 706c 6963 6174 696f  | The applicatio
-00004e20: 6e20 6073 6563 7265 7460 2070 726f 7065  n `secret` prope
-00004e30: 7274 792e 2020 2020 2020 2020 2020 2020  rty.            
+00002cc0: 7468 6520 5965 6c6c 6f77 446f 6720 4170  the YellowDog Ap
+00002cd0: 706c 6963 6174 696f 6e20 6b65 790a 2020  plication key.  
+00002ce0: 2d2d 7365 6372 6574 203c 6170 702d 7365  --secret <app-se
+00002cf0: 6372 6574 3e2c 202d 7320 3c61 7070 2d73  cret>, -s <app-s
+00002d00: 6563 7265 743e 0a20 2020 2020 2020 2020  ecret>.         
+00002d10: 2020 2020 2020 2020 2020 2020 2020 2074                 t
+00002d20: 6865 2059 656c 6c6f 7744 6f67 2041 7070  he YellowDog App
+00002d30: 6c69 6361 7469 6f6e 2073 6563 7265 740a  lication secret.
+00002d40: 2020 2d2d 6e61 6d65 7370 6163 6520 3c6e    --namespace <n
+00002d50: 616d 6573 7061 6365 3e2c 202d 6e20 3c6e  amespace>, -n <n
+00002d60: 616d 6573 7061 6365 3e0a 2020 2020 2020  amespace>.      
+00002d70: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00002d80: 2020 7468 6520 6e61 6d65 7370 6163 6520    the namespace 
+00002d90: 746f 2075 7365 2077 6865 6e20 6372 6561  to use when crea
+00002da0: 7469 6e67 2061 6e64 2069 6465 6e74 6966  ting and identif
+00002db0: 7969 6e67 2065 6e74 6974 6965 730a 2020  ying entities.  
+00002dc0: 2d2d 7461 6720 3c74 6167 3e2c 202d 7420  --tag <tag>, -t 
+00002dd0: 3c74 6167 3e0a 2020 2020 2020 2020 2020  <tag>.          
+00002de0: 2020 2020 2020 2020 2020 2020 2020 7468                th
+00002df0: 6520 7461 6720 746f 2075 7365 2066 6f72  e tag to use for
+00002e00: 2074 6167 6769 6e67 2061 6e64 206e 616d   tagging and nam
+00002e10: 696e 6720 656e 7469 7469 6573 0a20 202d  ing entities.  -
+00002e20: 2d75 726c 203c 7572 6c3e 2c20 2d75 203c  -url <url>, -u <
+00002e30: 7572 6c3e 0a20 2020 2020 2020 2020 2020  url>.           
+00002e40: 2020 2020 2020 2020 2020 2020 2074 6865               the
+00002e50: 2055 524c 206f 6620 7468 6520 5965 6c6c   URL of the Yell
+00002e60: 6f77 446f 6720 506c 6174 666f 726d 2041  owDog Platform A
+00002e70: 5049 0a20 202d 2d76 6172 6961 626c 6520  PI.  --variable 
+00002e80: 3c76 6172 313d 7631 3e2c 202d 7620 3c76  <var1=v1>, -v <v
+00002e90: 6172 313d 7631 3e0a 2020 2020 2020 2020  ar1=v1>.        
+00002ea0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00002eb0: 7573 6572 2d64 6566 696e 6564 2076 6172  user-defined var
+00002ec0: 6961 626c 6520 7375 6273 7469 7475 7469  iable substituti
+00002ed0: 6f6e 733b 2063 616e 2062 6520 7375 7070  ons; can be supp
+00002ee0: 6c69 6564 206d 756c 7469 706c 6520 7469  lied multiple ti
+00002ef0: 6d65 730a 2020 2d2d 7175 6965 742c 202d  mes.  --quiet, -
+00002f00: 7120 2020 2020 2020 2020 2020 7375 7070  q           supp
+00002f10: 7265 7373 2028 6e6f 6e2d 6572 726f 722c  ress (non-error,
+00002f20: 206e 6f6e 2d69 6e74 6572 6163 7469 7665   non-interactive
+00002f30: 2920 7374 6174 7573 2061 6e64 2070 726f  ) status and pro
+00002f40: 6772 6573 7320 6d65 7373 6167 6573 0a20  gress messages. 
+00002f50: 202d 2d64 6562 7567 2020 2020 2020 2020   --debug        
+00002f60: 2020 2020 2020 2070 7269 6e74 2061 2073         print a s
+00002f70: 7461 636b 2074 7261 6365 2028 6574 632e  tack trace (etc.
+00002f80: 2920 6f6e 2065 7272 6f72 0a20 202d 2d70  ) on error.  --p
+00002f90: 6163 2020 2020 2020 2020 2020 2020 2020  ac              
+00002fa0: 2020 2065 6e61 626c 6520 5041 4320 2870     enable PAC (p
+00002fb0: 726f 7879 2061 7574 6f2d 636f 6e66 6967  roxy auto-config
+00002fc0: 7572 6174 696f 6e29 2073 7570 706f 7274  uration) support
+00002fd0: 0a20 202d 2d61 626f 7274 2c20 2d61 2020  .  --abort, -a  
+00002fe0: 2020 2020 2020 2020 2061 626f 7274 2061           abort a
+00002ff0: 6c6c 2072 756e 6e69 6e67 2074 6173 6b73  ll running tasks
+00003000: 2077 6974 6820 696d 6d65 6469 6174 6520   with immediate 
+00003010: 6566 6665 6374 0a20 202d 2d66 6f6c 6c6f  effect.  --follo
+00003020: 772c 202d 6620 2020 2020 2020 2020 2077  w, -f          w
+00003030: 6865 6e20 7573 696e 6720 2d2d 6162 6f72  hen using --abor
+00003040: 742c 2070 6f6c 6c20 756e 7469 6c20 616c  t, poll until al
+00003050: 6c20 5461 736b 7320 6861 7665 2062 6565  l Tasks have bee
+00003060: 6e20 6162 6f72 7465 640a 2020 2d2d 696e  n aborted.  --in
+00003070: 7465 7261 6374 6976 652c 202d 6920 2020  teractive, -i   
+00003080: 2020 6c69 7374 2c20 616e 6420 696e 7465    list, and inte
+00003090: 7261 6374 6976 656c 7920 7365 6c65 6374  ractively select
+000030a0: 2c20 6974 656d 7320 746f 2061 6374 206f  , items to act o
+000030b0: 6e0a 2020 2d2d 7965 732c 202d 7920 2020  n.  --yes, -y   
+000030c0: 2020 2020 2020 2020 2020 7065 7266 6f72            perfor
+000030d0: 6d20 6465 7374 7275 6374 6976 6520 6163  m destructive ac
+000030e0: 7469 6f6e 7320 7769 7468 6f75 7420 7265  tions without re
+000030f0: 7175 6972 696e 6720 7573 6572 2063 6f6e  quiring user con
+00003100: 6669 726d 6174 696f 6e0a 6060 600a 0a23  firmation.```..#
+00003110: 2043 6f6e 6669 6775 7261 7469 6f6e 0a0a   Configuration..
+00003120: 4279 2064 6566 6175 6c74 2c20 7468 6520  By default, the 
+00003130: 6f70 6572 6174 696f 6e20 6f66 2061 6c6c  operation of all
+00003140: 2063 6f6d 6d61 6e64 7320 6973 2063 6f6e   commands is con
+00003150: 6669 6775 7265 6420 7573 696e 6720 6120  figured using a 
+00003160: 544f 4d4c 2063 6f6e 6669 6775 7261 7469  TOML configurati
+00003170: 6f6e 2066 696c 652e 0a0a 5468 6520 636f  on file...The co
+00003180: 6e66 6967 7572 6174 696f 6e20 6669 6c65  nfiguration file
+00003190: 2068 6173 2074 6872 6565 2070 6f73 7369   has three possi
+000031a0: 626c 6520 7365 6374 696f 6e73 3a0a 0a31  ble sections:..1
+000031b0: 2e20 4120 6063 6f6d 6d6f 6e60 2073 6563  . A `common` sec
+000031c0: 7469 6f6e 2074 6861 7420 636f 6e74 6169  tion that contai
+000031d0: 6e73 2072 6571 7569 7265 6420 7365 6375  ns required secu
+000031e0: 7269 7479 2070 726f 7065 7274 6965 7320  rity properties 
+000031f0: 666f 7220 696e 7465 7261 6374 696e 6720  for interacting 
+00003200: 7769 7468 2074 6865 2059 656c 6c6f 7744  with the YellowD
+00003210: 6f67 2070 6c61 7466 6f72 6d2c 2073 6574  og platform, set
+00003220: 7320 7468 6520 4e61 6d65 7370 6163 6520  s the Namespace 
+00003230: 696e 2077 6869 6368 2059 656c 6c6f 7744  in which YellowD
+00003240: 6f67 2061 7373 6574 7320 616e 6420 6f62  og assets and ob
+00003250: 6a65 6374 7320 6172 6520 6372 6561 7465  jects are create
+00003260: 642c 2061 6e64 2061 2054 6167 2074 6861  d, and a Tag tha
+00003270: 7420 6973 2075 7365 6420 666f 7220 7461  t is used for ta
+00003280: 6767 696e 6720 616e 6420 6e61 6d69 6e67  gging and naming
+00003290: 2061 7373 6574 7320 616e 6420 6f62 6a65   assets and obje
+000032a0: 6374 732e 0a32 2e20 4120 6077 6f72 6b52  cts..2. A `workR
+000032b0: 6571 7569 7265 6d65 6e74 6020 7365 6374  equirement` sect
+000032c0: 696f 6e20 7468 6174 2064 6566 696e 6573  ion that defines
+000032d0: 2074 6865 2070 726f 7065 7274 6965 7320   the properties 
+000032e0: 6f66 2057 6f72 6b20 5265 7175 6972 656d  of Work Requirem
+000032f0: 656e 7473 2074 6f20 6265 2073 7562 6d69  ents to be submi
+00003300: 7474 6564 2074 6f20 7468 6520 5965 6c6c  tted to the Yell
+00003310: 6f77 446f 6720 706c 6174 666f 726d 2e0a  owDog platform..
+00003320: 332e 2041 2060 776f 726b 6572 506f 6f6c  3. A `workerPool
+00003330: 6020 7365 6374 696f 6e20 7468 6174 2064  ` section that d
+00003340: 6566 696e 6573 2074 6865 2070 726f 7065  efines the prope
+00003350: 7274 6965 7320 6f66 2050 726f 7669 736f  rties of Proviso
+00003360: 6e65 6420 576f 726b 6572 2050 6f6f 6c73  ned Worker Pools
+00003370: 2074 6f20 6265 2063 7265 6174 6564 2075   to be created u
+00003380: 7369 6e67 2074 6865 2059 656c 6c6f 7744  sing the YellowD
+00003390: 6f67 2070 6c61 7466 6f72 6d2e 200a 0a54  og platform. ..T
+000033a0: 6865 7265 2069 7320 6120 646f 6375 6d65  here is a docume
+000033b0: 6e74 6564 2074 656d 706c 6174 6520 544f  nted template TO
+000033c0: 4d4c 2066 696c 6520 7072 6f76 6964 6564  ML file provided
+000033d0: 2069 6e20 5b63 6f6e 6669 672e 746f 6d6c   in [config.toml
+000033e0: 2e74 656d 706c 6174 655d 2863 6f6e 6669  .template](confi
+000033f0: 672e 746f 6d6c 2e74 656d 706c 6174 6529  g.toml.template)
+00003400: 2c20 636f 6e74 6169 6e69 6e67 2074 6865  , containing the
+00003410: 206d 6169 6e20 7072 6f70 6572 7469 6573   main properties
+00003420: 2074 6861 7420 6361 6e20 6265 2063 6f6e   that can be con
+00003430: 6669 6775 7265 642e 0a0a 5468 6520 636f  figured...The co
+00003440: 6e66 6967 7572 6174 696f 6e20 6669 6c65  nfiguration file
+00003450: 6e61 6d65 2063 616e 2062 6520 7375 7070  name can be supp
+00003460: 6c69 6564 2069 6e20 7468 7265 6520 6469  lied in three di
+00003470: 6666 6572 656e 7420 7761 7973 3a0a 0a31  fferent ways:..1
+00003480: 2e20 4f6e 2074 6865 2063 6f6d 6d61 6e64  . On the command
+00003490: 206c 696e 652c 2075 7369 6e67 2074 6865   line, using the
+000034a0: 2060 2d2d 636f 6e66 6967 6020 6f72 2060   `--config` or `
+000034b0: 2d63 6020 6f70 7469 6f6e 732c 2065 2e67  -c` options, e.g
+000034c0: 2e3a 3c62 723e 6079 642d 7375 626d 6974  .:<br>`yd-submit
+000034d0: 202d 6320 6a6f 6273 2f63 6f6e 6669 675f   -c jobs/config_
+000034e0: 312e 746f 6d6c 600a 322e 2055 7369 6e67  1.toml`.2. Using
+000034f0: 2074 6865 2060 5944 5f43 4f4e 4660 2065   the `YD_CONF` e
+00003500: 6e76 6972 6f6e 6d65 6e74 2076 6172 6961  nvironment varia
+00003510: 626c 652c 2065 2e67 2e3a 203c 6272 3e60  ble, e.g.: <br>`
+00003520: 6578 706f 7274 2059 445f 434f 4e46 3d22  export YD_CONF="
+00003530: 6a6f 6273 2f63 6f6e 6669 675f 312e 746f  jobs/config_1.to
+00003540: 6d6c 2260 0a33 2e20 4966 206e 6569 7468  ml"`.3. If neith
+00003550: 6572 206f 6620 7468 6520 6162 6f76 6520  er of the above 
+00003560: 6973 2073 7570 706c 6965 642c 2074 6865  is supplied, the
+00003570: 2063 6f6d 6d61 6e64 7320 6c6f 6f6b 2066   commands look f
+00003580: 6f72 2061 2060 636f 6e66 6967 2e74 6f6d  or a `config.tom
+00003590: 6c60 2066 696c 6520 696e 2074 6865 2063  l` file in the c
+000035a0: 7572 7265 6e74 2064 6972 6563 746f 7279  urrent directory
+000035b0: 0a0a 5468 6520 6f70 7469 6f6e 7320 6162  ..The options ab
+000035c0: 6f76 6520 6172 6520 7368 6f77 6e20 696e  ove are shown in
+000035d0: 206f 7264 6572 206f 6620 7072 6563 6564   order of preced
+000035e0: 656e 6365 2c20 692e 652e 2c20 6120 6669  ence, i.e., a fi
+000035f0: 6c65 6e61 6d65 2073 7570 706c 6965 6420  lename supplied 
+00003600: 6f6e 2074 6865 2063 6f6d 6d61 6e64 206c  on the command l
+00003610: 696e 6520 7375 7065 7273 6564 6573 206f  ine supersedes o
+00003620: 6e65 2073 6574 2069 6e20 6059 445f 434f  ne set in `YD_CO
+00003630: 4e46 602c 2077 6869 6368 2073 7570 6572  NF`, which super
+00003640: 7365 6465 7320 7468 6520 6465 6661 756c  sedes the defaul
+00003650: 742e 0a0a 2320 4e61 6d69 6e67 2052 756c  t...# Naming Rul
+00003660: 6573 0a0a 416c 6c20 656e 7469 7479 206e  es..All entity n
+00003670: 616d 6573 2075 7365 6420 7769 7468 696e  ames used within
+00003680: 2074 6865 2059 656c 6c6f 7744 6f67 2050   the YellowDog P
+00003690: 6c61 7466 6f72 6d20 6d75 7374 2063 6f6d  latform must com
+000036a0: 706c 7920 7769 7468 2074 6865 2066 6f6c  ply with the fol
+000036b0: 6c6f 7769 6e67 2072 6573 7472 6963 7469  lowing restricti
+000036c0: 6f6e 733a 0a0a 2d20 4e61 6d65 7320 6361  ons:..- Names ca
+000036d0: 6e20 6f6e 6c79 2063 6f6e 7461 696e 2074  n only contain t
+000036e0: 6865 2066 6f6c 6c6f 7769 6e67 3a20 6c6f  he following: lo
+000036f0: 7765 7263 6173 6520 6c65 7474 6572 732c  wercase letters,
+00003700: 2064 6967 6974 732c 2068 7970 6865 6e73   digits, hyphens
+00003710: 2061 6e64 2075 6e64 6572 7363 6f72 6573   and underscores
+00003720: 2028 6e6f 7465 2074 6861 7420 7370 6163   (note that spac
+00003730: 6573 2061 7265 206e 6f74 2070 6572 6d69  es are not permi
+00003740: 7474 6564 290a 2d20 4e61 6d65 7320 6d75  tted).- Names mu
+00003750: 7374 2073 7461 7274 2077 6974 6820 6120  st start with a 
+00003760: 6c65 7474 6572 0a2d 204e 616d 6573 206d  letter.- Names m
+00003770: 7573 7420 656e 6420 7769 7468 2061 206c  ust end with a l
+00003780: 6574 7465 7220 6f72 2064 6967 6974 0a2d  etter or digit.-
+00003790: 204e 616d 6520 6c65 6e67 7468 206d 7573   Name length mus
+000037a0: 7420 6265 203c 3d20 3630 2063 6861 7261  t be <= 60 chara
+000037b0: 6374 6572 730a 0a54 6865 7365 2072 6573  cters..These res
+000037c0: 7472 6963 7469 6f6e 7320 6170 706c 7920  trictions apply 
+000037d0: 746f 2065 6e74 6974 6965 7320 696e 636c  to entities incl
+000037e0: 7564 696e 6720 4e61 6d65 7370 6163 6573  uding Namespaces
+000037f0: 2c20 5461 6773 2c20 576f 726b 2052 6571  , Tags, Work Req
+00003800: 7569 7265 6d65 6e74 732c 2054 6173 6b20  uirements, Task 
+00003810: 4772 6f75 7073 2c20 5461 736b 732c 2057  Groups, Tasks, W
+00003820: 6f72 6b65 7220 506f 6f6c 732c 2061 6e64  orker Pools, and
+00003830: 2043 6f6d 7075 7465 2052 6571 7569 7265   Compute Require
+00003840: 6d65 6e74 732c 2061 6e64 2061 6c73 6f20  ments, and also 
+00003850: 6170 706c 7920 746f 2065 6e74 6974 6965  apply to entitie
+00003860: 7320 7468 6174 2061 7265 2063 7572 7265  s that are curre
+00003870: 6e74 6c79 2075 7365 6420 696e 6469 7265  ntly used indire
+00003880: 6374 6c79 2062 7920 7468 6573 6520 7363  ctly by these sc
+00003890: 7269 7074 732c 2069 6e63 6c75 6469 6e67  ripts, including
+000038a0: 2055 7365 726e 616d 6573 2c20 4372 6564   Usernames, Cred
+000038b0: 656e 7469 616c 732c 204b 6579 7269 6e67  entials, Keyring
+000038c0: 732c 2043 6f6d 7075 7465 2053 6f75 7263  s, Compute Sourc
+000038d0: 6573 2061 6e64 2043 6f6d 7075 7465 2054  es and Compute T
+000038e0: 656d 706c 6174 6573 2e0a 0a23 2043 6f6d  emplates...# Com
+000038f0: 6d6f 6e20 5072 6f70 6572 7469 6573 0a0a  mon Properties..
+00003900: 5468 6520 605b 636f 6d6d 6f6e 5d60 2073  The `[common]` s
+00003910: 6563 7469 6f6e 206f 6620 7468 6520 636f  ection of the co
+00003920: 6e66 6967 7572 6174 696f 6e20 6669 6c65  nfiguration file
+00003930: 2063 616e 2063 6f6e 7461 696e 2074 6865   can contain the
+00003940: 2066 6f6c 6c6f 7769 6e67 2070 726f 7065   following prope
+00003950: 7274 6965 733a 0a0a 7c20 5072 6f70 6572  rties:..| Proper
+00003960: 7479 2020 2020 7c20 4465 7363 7269 7074  ty    | Descript
+00003970: 696f 6e20 2020 2020 2020 2020 2020 2020  ion             
+00003980: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00003990: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000039a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000039b0: 2020 2020 2020 2020 2020 2020 7c0a 7c3a              |.|:
+000039c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 7c3a 2d2d  ------------|:--
+000039d0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000039e0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000039f0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00003a00: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00003a10: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00003a20: 2d2d 7c0a 7c20 606b 6579 6020 2020 2020  --|.| `key`     
+00003a30: 2020 7c20 5468 6520 2a2a 6b65 792a 2a20    | The **key** 
+00003a40: 6f66 2074 6865 2059 656c 6c6f 7744 6f67  of the YellowDog
+00003a50: 2041 7070 6c69 6361 7469 6f6e 2075 6e64   Application und
+00003a60: 6572 2077 6869 6368 2074 6865 2063 6f6d  er which the com
+00003a70: 6d61 6e64 7320 7769 6c6c 2072 756e 2020  mands will run  
+00003a80: 2020 2020 2020 2020 7c0a 7c20 6073 6563          |.| `sec
+00003a90: 7265 7460 2020 2020 7c20 5468 6520 2a2a  ret`    | The **
+00003aa0: 7365 6372 6574 2a2a 206f 6620 7468 6520  secret** of the 
+00003ab0: 5965 6c6c 6f77 446f 6720 4170 706c 6963  YellowDog Applic
+00003ac0: 6174 696f 6e20 756e 6465 7220 7768 6963  ation under whic
+00003ad0: 6820 7468 6520 636f 6d6d 616e 6473 2077  h the commands w
+00003ae0: 696c 6c20 7275 6e20 2020 2020 2020 7c0a  ill run       |.
+00003af0: 7c20 606e 616d 6573 7061 6365 6020 7c20  | `namespace` | 
+00003b00: 5468 6520 2a2a 6e61 6d65 7370 6163 652a  The **namespace*
+00003b10: 2a20 746f 2062 6520 7573 6564 2066 6f72  * to be used for
+00003b20: 2067 726f 7570 696e 6720 7265 736f 7572   grouping resour
+00003b30: 6365 7320 2020 2020 2020 2020 2020 2020  ces             
+00003b40: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00003b50: 2020 2020 7c0a 7c20 6074 6167 6020 2020      |.| `tag`   
+00003b60: 2020 2020 7c20 5468 6520 2a2a 7461 672a      | The **tag*
+00003b70: 2a20 746f 2062 6520 7573 6564 2066 6f72  * to be used for
+00003b80: 2074 6167 6769 6e67 2072 6573 6f75 7263   tagging resourc
+00003b90: 6573 2061 6e64 206e 616d 696e 6720 6f62  es and naming ob
+00003ba0: 6a65 6374 7320 2020 2020 2020 2020 2020  jects           
+00003bb0: 2020 2020 2020 2020 2020 7c0a 7c20 6075            |.| `u
+00003bc0: 726c 6020 2020 2020 2020 7c20 5468 6520  rl`       | The 
+00003bd0: 2a2a 5552 4c2a 2a20 6f66 2074 6865 2059  **URL** of the Y
+00003be0: 656c 6c6f 7744 6f67 2050 6c61 7466 6f72  ellowDog Platfor
+00003bf0: 6d20 4150 4920 656e 6470 6f69 6e74 2c20  m API endpoint, 
+00003c00: 6966 2074 6865 2064 6566 6175 6c74 2069  if the default i
+00003c10: 736e 2774 2074 6f20 6265 2075 7365 6420  sn't to be used 
+00003c20: 7c0a 7c20 6075 7365 5041 4360 2020 2020  |.| `usePAC`    
+00003c30: 7c20 5573 6520 5041 4320 2870 726f 7879  | Use PAC (proxy
+00003c40: 2061 7574 6f63 6f6e 6669 6775 7261 7469   autoconfigurati
+00003c50: 6f6e 2920 6966 2073 6574 2074 6f20 6074  on) if set to `t
+00003c60: 7275 6560 2020 2020 2020 2020 2020 2020  rue`            
+00003c70: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00003c80: 2020 2020 2020 7c0a 7c20 6076 6172 6961        |.| `varia
+00003c90: 626c 6573 6020 7c20 4120 7461 626c 6520  bles` | A table 
+00003ca0: 636f 6e74 6169 6e69 6e67 202a 2a76 6172  containing **var
+00003cb0: 6961 626c 6520 7375 6273 7469 7475 7469  iable substituti
+00003cc0: 6f6e 732a 2a20 2873 6565 2074 6865 2056  ons** (see the V
+00003cd0: 6172 6961 626c 6573 2073 6563 7469 6f6e  ariables section
+00003ce0: 2062 656c 6f77 2920 2020 2020 7c0a 0a41   below)     |..A
+00003cf0: 6e20 6578 616d 706c 6520 6063 6f6d 6d6f  n example `commo
+00003d00: 6e60 2073 6563 7469 6f6e 2069 7320 7368  n` section is sh
+00003d10: 6f77 6e20 6265 6c6f 773a 0a0a 6060 6074  own below:..```t
+00003d20: 6f6d 6c0a 5b63 6f6d 6d6f 6e5d 0a20 2020  oml.[common].   
+00003d30: 206b 6579 203d 2022 6173 6466 6768 6a6b   key = "asdfghjk
+00003d40: 6c7a 7863 7662 2d31 3233 3435 3637 220a  lzxcvb-1234567".
+00003d50: 2020 2020 7365 6372 6574 203d 2022 7177      secret = "qw
+00003d60: 6572 7479 7569 6f70 6173 6466 6768 6a6b  ertyuiopasdfghjk
+00003d70: 6c7a 7863 7662 6e6d 3132 3334 3536 3738  lzxcvbnm12345678
+00003d80: 3930 7177 6572 7479 7522 0a20 2020 206e  90qwertyu".    n
+00003d90: 616d 6573 7061 6365 203d 2022 7072 6f6a  amespace = "proj
+00003da0: 6563 742d 7822 0a20 2020 2074 6167 203d  ect-x".    tag =
+00003db0: 2022 7465 7374 696e 672d 7b7b 7573 6572   "testing-{{user
+00003dc0: 6e61 6d65 7d7d 220a 6060 600a 0a49 6e64  name}}".```..Ind
+00003dd0: 656e 7461 7469 6f6e 2069 7320 6f70 7469  entation is opti
+00003de0: 6f6e 616c 2069 6e20 544f 4d4c 2066 696c  onal in TOML fil
+00003df0: 6573 2061 6e64 2069 7320 666f 7220 7265  es and is for re
+00003e00: 6164 6162 696c 6974 7920 6f6e 6c79 2e0a  adability only..
+00003e10: 0a23 2320 4854 5450 5320 5072 6f78 7920  .## HTTPS Proxy 
+00003e20: 5375 7070 6f72 740a 0a54 6865 2063 6f6d  Support..The com
+00003e30: 6d61 6e64 7320 7769 6c6c 2075 7365 2074  mands will use t
+00003e40: 6865 2076 616c 7565 206f 6620 7468 6520  he value of the 
+00003e50: 656e 7669 726f 6e6d 656e 7420 7661 7269  environment vari
+00003e60: 6162 6c65 2060 4854 5450 535f 5052 4f58  able `HTTPS_PROX
+00003e70: 5960 2069 6620 726f 7574 696e 6720 7468  Y` if routing th
+00003e80: 726f 7567 6820 6120 7072 6f78 7920 6973  rough a proxy is
+00003e90: 2072 6571 7569 7265 642e 0a0a 496e 2061   required...In a
+00003ea0: 6464 6974 696f 6e2c 2074 6865 2063 6f6d  ddition, the com
+00003eb0: 6d61 6e64 7320 6361 6e20 7573 6520 7072  mands can use pr
+00003ec0: 6f78 7920 6175 746f 636f 6e66 6967 7572  oxy autoconfigur
+00003ed0: 6174 696f 6e20 2850 4143 2920 6966 2074  ation (PAC) if t
+00003ee0: 6865 2060 2d2d 7061 6360 2063 6f6d 6d61  he `--pac` comma
+00003ef0: 6e64 206c 696e 6520 6f70 7469 6f6e 2069  nd line option i
+00003f00: 7320 7370 6563 6966 6965 642c 206f 7220  s specified, or 
+00003f10: 6966 2074 6865 2060 7573 6550 4143 6020  if the `usePAC` 
+00003f20: 7072 6f70 6572 7479 2069 7320 7365 7420  property is set 
+00003f30: 746f 2060 7472 7565 6020 696e 2074 6865  to `true` in the
+00003f40: 2060 5b63 6f6d 6d6f 6e5d 6020 7365 6374   `[common]` sect
+00003f50: 696f 6e20 6f66 2074 6865 2060 636f 6e66  ion of the `conf
+00003f60: 6967 2e74 6f6d 6c60 2066 696c 652e 0a0a  ig.toml` file...
+00003f70: 2323 2053 7065 6369 6679 696e 6720 436f  ## Specifying Co
+00003f80: 6d6d 6f6e 2050 726f 7065 7274 6965 7320  mmon Properties 
+00003f90: 7573 696e 6720 7468 6520 436f 6d6d 616e  using the Comman
+00003fa0: 6420 4c69 6e65 206f 7220 456e 7669 726f  d Line or Enviro
+00003fb0: 6e6d 656e 7420 5661 7269 6162 6c65 730a  nment Variables.
+00003fc0: 0a41 6c6c 2074 6865 2063 6f6d 6d6f 6e20  .All the common 
+00003fd0: 7072 6f70 6572 7469 6573 2063 616e 2062  properties can b
+00003fe0: 6520 7365 7420 7573 696e 6720 636f 6d6d  e set using comm
+00003ff0: 616e 6420 6c69 6e65 206f 7074 696f 6e73  and line options
+00004000: 2c20 6f72 2069 6e20 656e 7669 726f 6e6d  , or in environm
+00004010: 656e 7420 7661 7269 6162 6c65 732e 0a0a  ent variables...
+00004020: 5468 6520 2a2a 636f 6d6d 616e 6420 6c69  The **command li
+00004030: 6e65 206f 7074 696f 6e73 2a2a 2061 7265  ne options** are
+00004040: 2061 7320 666f 6c6c 6f77 733a 0a0a 2d20   as follows:..- 
+00004050: 602d 2d6b 6579 6020 6f72 2060 2d6b 600a  `--key` or `-k`.
+00004060: 2d20 602d 2d73 6563 7265 7460 206f 7220  - `--secret` or 
+00004070: 602d 7360 0a2d 2060 2d2d 6e61 6d65 7370  `-s`.- `--namesp
+00004080: 6163 6560 206f 7220 602d 6e60 0a2d 2060  ace` or `-n`.- `
+00004090: 2d2d 7461 6760 206f 7220 602d 7460 0a2d  --tag` or `-t`.-
+000040a0: 2060 2d2d 7572 6c60 206f 7220 602d 7560   `--url` or `-u`
+000040b0: 0a2d 2060 2d2d 7061 6360 0a0a 5468 6573  .- `--pac`..Thes
+000040c0: 6520 6f70 7469 6f6e 7320 6361 6e20 616c  e options can al
+000040d0: 736f 2062 6520 6c69 7374 6564 2062 7920  so be listed by 
+000040e0: 7275 6e6e 696e 6720 6120 636f 6d6d 616e  running a comman
+000040f0: 6420 7769 7468 2074 6865 2060 2d2d 6865  d with the `--he
+00004100: 6c70 6020 6f72 2060 2d68 6020 6f70 7469  lp` or `-h` opti
+00004110: 6f6e 2e0a 0a54 6865 202a 2a65 6e76 6972  on...The **envir
+00004120: 6f6e 6d65 6e74 2076 6172 6961 626c 6573  onment variables
+00004130: 2a2a 2061 7265 2061 7320 666f 6c6c 6f77  ** are as follow
+00004140: 733a 0a0a 2d20 6059 445f 4b45 5960 0a2d  s:..- `YD_KEY`.-
+00004150: 2060 5944 5f53 4543 5245 5460 0a2d 2060   `YD_SECRET`.- `
+00004160: 5944 5f4e 414d 4553 5041 4345 600a 2d20  YD_NAMESPACE`.- 
+00004170: 6059 445f 5441 4760 0a2d 2060 5944 5f55  `YD_TAG`.- `YD_U
+00004180: 524c 600a 0a57 6865 6e20 7365 7474 696e  RL`..When settin
+00004190: 6720 7468 6520 7661 6c75 6520 6f66 2074  g the value of t
+000041a0: 6865 2061 626f 7665 2070 726f 7065 7274  he above propert
+000041b0: 6965 732c 2061 2070 726f 7065 7274 7920  ies, a property 
+000041c0: 7365 7420 6f6e 2074 6865 2063 6f6d 6d61  set on the comma
+000041d0: 6e64 206c 696e 6520 7461 6b65 7320 7072  nd line takes pr
+000041e0: 6563 6564 656e 6365 206f 7665 7220 6f6e  ecedence over on
+000041f0: 6520 7365 7420 7669 6120 616e 2065 6e76  e set via an env
+00004200: 6972 6f6e 6d65 6e74 2076 6172 6961 626c  ironment variabl
+00004210: 652c 2061 6e64 2062 6f74 6820 7461 6b65  e, and both take
+00004220: 2070 7265 6365 6465 6e63 6520 6f76 6572   precedence over
+00004230: 2061 2076 616c 7565 2073 6574 2069 6e20   a value set in 
+00004240: 6120 636f 6e66 6967 7572 6174 696f 6e20  a configuration 
+00004250: 6669 6c65 2e0a 0a49 6620 616c 6c20 7468  file...If all th
+00004260: 6520 7265 7175 6972 6564 2063 6f6d 6d6f  e required commo
+00004270: 6e20 7072 6f70 6572 7469 6573 2061 7265  n properties are
+00004280: 2073 6574 2075 7369 6e67 2074 6865 2063   set using the c
+00004290: 6f6d 6d61 6e64 206c 696e 6520 6f72 2065  ommand line or e
+000042a0: 6e76 6972 6f6e 6d65 6e74 2076 6172 6961  nvironment varia
+000042b0: 626c 6573 2c20 7468 656e 2074 6865 2065  bles, then the e
+000042c0: 6e74 6972 6520 6063 6f6d 6d6f 6e60 2073  ntire `common` s
+000042d0: 6563 7469 6f6e 206f 6620 7468 6520 544f  ection of the TO
+000042e0: 4d4c 2066 696c 6520 6361 6e20 6265 206f  ML file can be o
+000042f0: 6d69 7474 6564 2e0a 0a23 2320 5661 7269  mitted...## Vari
+00004300: 6162 6c65 2053 7562 7374 6974 7574 696f  able Substitutio
+00004310: 6e73 2069 6e20 436f 6d6d 6f6e 2050 726f  ns in Common Pro
+00004320: 7065 7274 6965 730a 0a4e 6f74 6520 7468  perties..Note th
+00004330: 6520 7573 6520 6f66 2060 7b7b 7573 6572  e use of `{{user
+00004340: 6e61 6d65 7d7d 6020 696e 2074 6865 2076  name}}` in the v
+00004350: 616c 7565 206f 6620 7468 6520 6074 6167  alue of the `tag
+00004360: 6020 7072 6f70 6572 7479 3a20 7468 6973  ` property: this
+00004370: 2069 7320 6120 2a2a 7661 7269 6162 6c65   is a **variable
+00004380: 2073 7562 7374 6974 7574 696f 6e2a 2a20   substitution** 
+00004390: 7468 6174 2063 616e 206f 7074 696f 6e61  that can optiona
+000043a0: 6c6c 7920 6265 2075 7365 6420 746f 2069  lly be used to i
+000043b0: 6e73 6572 7420 7468 6520 6c6f 6769 6e20  nsert the login 
+000043c0: 7573 6572 6e61 6d65 206f 6620 7468 6520  username of the 
+000043d0: 7573 6572 2072 756e 6e69 6e67 2074 6865  user running the
+000043e0: 2063 6f6d 6d61 6e64 732e 2053 6f2c 2066   commands. So, f
+000043f0: 6f72 2075 7365 726e 616d 6520 6061 6263  or username `abc
+00004400: 602c 2074 6865 2060 7461 6760 2077 6f75  `, the `tag` wou
+00004410: 6c64 2062 6520 7365 7420 746f 2060 7465  ld be set to `te
+00004420: 7374 696e 672d 6162 6360 2e20 5468 6973  sting-abc`. This
+00004430: 2063 616e 2062 6520 6865 6c70 6675 6c20   can be helpful 
+00004440: 746f 2064 6973 616d 6269 6775 6174 6520  to disambiguate 
+00004450: 6d75 6c74 6970 6c65 2075 7365 7273 2072  multiple users r
+00004460: 756e 6e69 6e67 2077 6974 6820 7468 6520  unning with the 
+00004470: 7361 6d65 2063 6f6e 6669 6775 7261 7469  same configurati
+00004480: 6f6e 2064 6174 612e 0a0a 5661 7269 6162  on data...Variab
+00004490: 6c65 2073 7562 7374 6974 7574 696f 6e73  le substitutions
+000044a0: 2061 7265 2064 6973 6375 7373 6564 2062   are discussed b
+000044b0: 656c 6f77 2e0a 0a23 2056 6172 6961 626c  elow...# Variabl
+000044c0: 6520 5375 6273 7469 7475 7469 6f6e 730a  e Substitutions.
+000044d0: 0a56 6172 6961 626c 6520 7375 6273 7469  .Variable substi
+000044e0: 7475 7469 6f6e 7320 7072 6f76 6964 6520  tutions provide 
+000044f0: 6120 706f 7765 7266 756c 2077 6179 206f  a powerful way o
+00004500: 6620 696e 7472 6f64 7563 696e 6720 7661  f introducing va
+00004510: 7269 6162 6c65 2076 616c 7565 7320 696e  riable values in
+00004520: 746f 2054 4f4d 4c20 636f 6e66 6967 7572  to TOML configur
+00004530: 6174 696f 6e20 6669 6c65 732c 2057 6f72  ation files, Wor
+00004540: 6b20 5265 7175 6972 656d 656e 7420 4a53  k Requirement JS
+00004550: 4f4e 2064 6566 696e 6974 696f 6e73 2c20  ON definitions, 
+00004560: 616e 6420 576f 726b 6572 2050 6f6f 6c20  and Worker Pool 
+00004570: 4a53 4f4e 2064 6566 696e 6974 696f 6e73  JSON definitions
+00004580: 2e20 5468 6579 2063 616e 2062 6520 696e  . They can be in
+00004590: 636c 7564 6564 2069 6e20 7468 6520 7661  cluded in the va
+000045a0: 6c75 6520 6f66 2061 6e79 2070 726f 7065  lue of any prope
+000045b0: 7274 7920 696e 2065 6163 6820 6f66 2074  rty in each of t
+000045c0: 6865 7365 206f 626a 6563 7473 2c20 696e  hese objects, in
+000045d0: 636c 7564 696e 6720 696e 2076 616c 7565  cluding in value
+000045e0: 7320 7769 7468 696e 206c 6973 7473 2028  s within lists (
+000045f0: 652e 672e 2c20 666f 7220 7468 6520 6061  e.g., for the `a
+00004600: 7267 756d 656e 7473 6020 7072 6f70 6572  rguments` proper
+00004610: 7479 2920 616e 6420 6172 7261 7973 2028  ty) and arrays (
+00004620: 652e 672e 2c20 7468 6520 6065 6e76 6972  e.g., the `envir
+00004630: 6f6e 6d65 6e74 6020 7072 6f70 6572 7479  onment` property
+00004640: 292e 0a0a 5661 7269 6162 6c65 2073 7562  )...Variable sub
+00004650: 7374 6974 7574 696f 6e73 2061 7265 2065  stitutions are e
+00004660: 7870 7265 7373 6564 2075 7369 6e67 2060  xpressed using `
+00004670: 7b7b 7661 7269 6162 6c65 7d7d 6020 6e6f  {{variable}}` no
+00004680: 7461 7469 6f6e 2c20 7768 6572 6520 7468  tation, where th
+00004690: 6520 6578 7072 6573 7369 6f6e 2069 7320  e expression is 
+000046a0: 7265 706c 6163 6564 2062 7920 7468 6520  replaced by the 
+000046b0: 7661 6c75 6520 6f66 2060 7661 7269 6162  value of `variab
+000046c0: 6c65 602e 0a0a 5375 6273 7469 7475 7469  le`...Substituti
+000046d0: 6f6e 7320 6361 6e20 616c 736f 2062 6520  ons can also be 
+000046e0: 7065 7266 6f72 6d65 6420 666f 7220 6e6f  performed for no
+000046f0: 6e2d 7374 7269 6e67 2028 6e75 6d62 6572  n-string (number
+00004700: 2061 6e64 2062 6f6f 6c65 616e 2920 7661   and boolean) va
+00004710: 6c75 6573 2075 7369 6e67 2074 6865 2060  lues using the `
+00004720: 6e75 6d3a 6020 616e 6420 6062 6f6f 6c3a  num:` and `bool:
+00004730: 6020 7072 6566 6978 6573 2077 6974 6869  ` prefixes withi
+00004740: 6e20 7468 6520 7661 7269 6162 6c65 2073  n the variable s
+00004750: 7562 7374 6974 7574 696f 6e3a 0a0a 2d20  ubstitution:..- 
+00004760: 4465 6669 6e65 2074 6865 2076 6172 6961  Define the varia
+00004770: 626c 6520 7375 6273 7469 7475 7469 6f6e  ble substitution
+00004780: 2075 7369 6e67 206f 6e65 206f 6620 7468   using one of th
+00004790: 6520 666f 6c6c 6f77 696e 6720 7061 7474  e following patt
+000047a0: 6572 6e73 3a20 6022 7b7b 6e75 6d3a 6d79  erns: `"{{num:my
+000047b0: 5f69 6e74 7d7d 2260 2c20 6022 7b7b 6e75  _int}}"`, `"{{nu
+000047c0: 6d3a 6d79 5f66 6c6f 6174 7d7d 2260 2c20  m:my_float}}"`, 
+000047d0: 6022 7b7b 626f 6f6c 3a6d 795f 626f 6f6c  `"{{bool:my_bool
+000047e0: 7d7d 2260 0a2d 2056 6172 6961 626c 6520  }}"`.- Variable 
+000047f0: 6465 6669 6e69 7469 6f6e 7320 7375 7070  definitions supp
+00004800: 6c69 6564 206f 6e20 7468 6520 636f 6d6d  lied on the comm
+00004810: 616e 6420 6c69 6e65 2077 6f75 6c64 2074  and line would t
+00004820: 6865 6e20 6265 206f 6620 7468 6520 666f  hen be of the fo
+00004830: 726d 3a20 602d 6d20 6d79 5f69 6e74 3d35  rm: `-m my_int=5
+00004840: 202d 6d20 6d79 5f66 6c6f 6174 3d32 2e35   -m my_float=2.5
+00004850: 202d 6d20 6d79 5f62 6f6f 6c3d 7472 7565   -m my_bool=true
+00004860: 600a 2d20 496e 2074 6865 2070 726f 6365  `.- In the proce
+00004870: 7373 6564 204a 534f 4e20 6f72 2054 4f4d  ssed JSON or TOM
+00004880: 4c2c 2074 6865 7365 2076 616c 7565 7320  L, these values 
+00004890: 776f 756c 6420 6265 636f 6d65 2060 3560  would become `5`
+000048a0: 2c20 6032 2e35 6020 616e 6420 6074 7275  , `2.5` and `tru
+000048b0: 6560 2c20 7265 7370 6563 7469 7665 6c79  e`, respectively
+000048c0: 2c20 636f 6e76 6572 7465 6420 6672 6f6d  , converted from
+000048d0: 2073 7472 696e 6773 2074 6f20 7468 6569   strings to thei
+000048e0: 7220 636f 7272 6563 7420 4a53 4f4e 2074  r correct JSON t
+000048f0: 7970 6573 0a0a 2323 2044 6566 6175 6c74  ypes..## Default
+00004900: 2056 6172 6961 626c 6573 0a0a 5468 6520   Variables..The 
+00004910: 666f 6c6c 6f77 696e 6720 7375 6273 7469  following substi
+00004920: 7475 7469 6f6e 7320 6172 6520 6175 746f  tutions are auto
+00004930: 6d61 7469 6361 6c6c 7920 6372 6561 7465  matically create
+00004940: 6420 616e 6420 6361 6e20 6265 2075 7365  d and can be use
+00004950: 6420 696e 2061 6e79 2073 6563 7469 6f6e  d in any section
+00004960: 206f 6620 7468 6520 636f 6e66 6967 7572   of the configur
+00004970: 6174 696f 6e20 6669 6c65 2c20 6f72 2069  ation file, or i
+00004980: 6e20 616e 7920 4a53 4f4e 2073 7065 6369  n any JSON speci
+00004990: 6669 6361 7469 6f6e 3a0a 0a7c 2044 6972  fication:..| Dir
+000049a0: 6563 7469 7665 2020 2020 2020 207c 2044  ective       | D
+000049b0: 6573 6372 6970 7469 6f6e 2020 2020 2020  escription      
+000049c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000049d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000049e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000049f0: 2020 2020 2020 2020 7c20 4578 616d 706c          | Exampl
+00004a00: 6520 6f66 2053 7562 7374 6974 7574 696f  e of Substitutio
+00004a10: 6e20 7c0a 7c3a 2d2d 2d2d 2d2d 2d2d 2d2d  n |.|:----------
+00004a20: 2d2d 2d2d 2d2d 7c3a 2d2d 2d2d 2d2d 2d2d  ------|:--------
+00004a30: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00004a40: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00004a50: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00004a60: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00004a70: 2d7c 3a2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  -|:-------------
+00004a80: 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c 0a7c 2060  -----------|.| `
+00004a90: 7b7b 7573 6572 6e61 6d65 7d7d 6020 207c  {{username}}`  |
+00004aa0: 2054 6865 2063 7572 7265 6e74 2075 7365   The current use
+00004ab0: 7227 7320 6c6f 6769 6e20 7573 6572 6e61  r's login userna
+00004ac0: 6d65 2c20 6c6f 7765 7220 6361 7365 2c20  me, lower case, 
+00004ad0: 7370 6163 6573 2072 6570 6c61 6365 6420  spaces replaced 
+00004ae0: 2020 2020 2020 2020 2020 7c20 6a61 6e65            | jane
+00004af0: 5f73 6d69 7468 2020 2020 2020 2020 2020  _smith          
+00004b00: 2020 2020 7c0a 7c20 607b 7b64 6174 657d      |.| `{{date}
+00004b10: 7d60 2020 2020 2020 7c20 5468 6520 6375  }`      | The cu
+00004b20: 7272 656e 7420 6461 7465 2028 5554 4329  rrent date (UTC)
+00004b30: 3a20 5959 5959 4d4d 4444 2020 2020 2020  : YYYYMMDD      
+00004b40: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004b50: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004b60: 2020 207c 2032 3032 3231 3032 3720 2020     | 20221027   
+00004b70: 2020 2020 2020 2020 2020 2020 207c 0a7c               |.|
+00004b80: 2060 7b7b 7469 6d65 7d7d 6020 2020 2020   `{{time}}`     
+00004b90: 207c 2054 6865 2063 7572 7265 6e74 2074   | The current t
+00004ba0: 696d 6520 2855 5443 293a 2048 484d 4d53  ime (UTC): HHMMS
+00004bb0: 5320 2020 2020 2020 2020 2020 2020 2020  S               
+00004bc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004bd0: 2020 2020 2020 2020 2020 2020 7c20 3136              | 16
+00004be0: 3330 3236 2020 2020 2020 2020 2020 2020  3026            
+00004bf0: 2020 2020 2020 7c0a 7c20 607b 7b64 6174        |.| `{{dat
+00004c00: 6574 696d 657d 7d60 2020 7c20 436f 6e63  etime}}`  | Conc
+00004c10: 6174 656e 6174 696f 6e20 6f66 2074 6865  atenation of the
+00004c20: 2064 6174 6520 616e 6420 7469 6d65 2061   date and time a
+00004c30: 626f 7665 2c20 7769 7468 2061 2027 2d27  bove, with a '-'
+00004c40: 2073 6570 6172 6174 6f72 2020 2020 2020   separator      
+00004c50: 2020 2020 207c 2032 3032 3231 3032 372d       | 20221027-
+00004c60: 3136 3330 3236 2020 2020 2020 2020 207c  163026         |
+00004c70: 0a7c 2060 7b7b 7261 6e64 6f6d 7d7d 6020  .| `{{random}}` 
+00004c80: 2020 207c 2041 2072 616e 646f 6d2c 2074     | A random, t
+00004c90: 6872 6565 2064 6967 6974 2068 6578 6164  hree digit hexad
+00004ca0: 6563 696d 616c 206e 756d 6265 7220 286c  ecimal number (l
+00004cb0: 6f77 6572 2063 6173 6529 2020 2020 2020  ower case)      
+00004cc0: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00004cd0: 6131 6320 2020 2020 2020 2020 2020 2020  a1c             
+00004ce0: 2020 2020 2020 2020 7c0a 7c20 607b 7b6e          |.| `{{n
+00004cf0: 616d 6573 7061 6365 7d7d 6020 7c20 5468  amespace}}` | Th
+00004d00: 6520 606e 616d 6573 7061 6365 6020 7072  e `namespace` pr
+00004d10: 6f70 6572 7479 2e20 4e6f 7465 2074 6861  operty. Note tha
+00004d20: 7420 606e 616d 6573 7061 6365 6020 6d75  t `namespace` mu
+00004d30: 7374 2c20 6f66 2063 6f75 7273 652c 2062  st, of course, b
+00004d40: 6520 7365 742e 207c 206d 795f 6e61 6d65  e set. | my_name
+00004d50: 7370 6163 6520 2020 2020 2020 2020 2020  space           
+00004d60: 207c 0a7c 2060 7b7b 7461 677d 7d60 2020   |.| `{{tag}}`  
+00004d70: 2020 2020 207c 2054 6865 2060 7461 6760       | The `tag`
+00004d80: 2070 726f 7065 7274 792e 204e 6f74 6520   property. Note 
+00004d90: 7468 6174 2060 7461 6760 206d 7573 7420  that `tag` must 
+00004da0: 6265 2073 6574 2e20 2020 2020 2020 2020  be set.         
+00004db0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004dc0: 7c20 6d79 5f74 6167 2020 2020 2020 2020  | my_tag        
+00004dd0: 2020 2020 2020 2020 2020 7c0a 7c20 607b            |.| `{
+00004de0: 7b6b 6579 7d7d 6020 2020 2020 2020 7c20  {key}}`       | 
+00004df0: 5468 6520 6170 706c 6963 6174 696f 6e20  The application 
+00004e00: 606b 6579 6020 7072 6f70 6572 7479 2e20  `key` property. 
+00004e10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004e20: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004e30: 2020 2020 2020 2020 207c 2020 2020 2020           |      
 00004e40: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004e50: 2020 2020 2020 2020 2020 207c 2020 2020             |    
-00004e60: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004e70: 2020 2020 207c 0a7c 2060 7b7b 7572 6c7d       |.| `{{url}
-00004e80: 7d60 2020 2020 2020 207c 2054 6865 2050  }`       | The P
-00004e90: 6c61 7466 6f72 6d20 6075 726c 6020 7072  latform `url` pr
-00004ea0: 6f70 6572 7479 2e20 2020 2020 2020 2020  operty.         
-00004eb0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004ec0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00004ed0: 2020 2020 7c20 2020 2020 2020 2020 2020      |           
-00004ee0: 2020 2020 2020 2020 2020 2020 2020 7c0a                |.
-00004ef0: 0a46 6f72 2074 6865 2060 6461 7465 602c  .For the `date`,
-00004f00: 2060 7469 6d65 602c 2060 6461 7465 7469   `time`, `dateti
-00004f10: 6d65 6020 616e 6420 6072 616e 646f 6d60  me` and `random`
-00004f20: 2064 6972 6563 7469 7665 732c 2074 6865   directives, the
-00004f30: 2073 616d 6520 7661 6c75 6573 2077 696c   same values wil
-00004f40: 6c20 6265 2075 7365 6420 666f 7220 7468  l be used for th
-00004f50: 6520 6475 7261 7469 6f6e 206f 6620 6120  e duration of a 
-00004f60: 636f 6d6d 616e 6420 2d2d 2069 2e65 2e2c  command -- i.e.,
-00004f70: 2069 6620 607b 7b74 696d 657d 7d60 2069   if `{{time}}` i
-00004f80: 7320 7573 6564 2077 6974 6869 6e20 6d75  s used within mu
-00004f90: 6c74 6970 6c65 2070 726f 7065 7274 6965  ltiple propertie
-00004fa0: 732c 2074 6865 2073 616d 6520 7661 6c75  s, the same valu
-00004fb0: 6520 7769 6c6c 2062 6520 7573 6564 2066  e will be used f
-00004fc0: 6f72 2065 6163 6820 7375 6273 7469 7475  or each substitu
-00004fd0: 7469 6f6e 2e0a 0a23 2320 5573 6572 2d44  tion...## User-D
-00004fe0: 6566 696e 6564 2056 6172 6961 626c 6573  efined Variables
-00004ff0: 0a0a 4172 6269 7472 6172 7920 7661 7269  ..Arbitrary vari
-00005000: 6162 6c65 7320 6361 6e20 6265 2073 7570  ables can be sup
-00005010: 706c 6965 6420 7573 696e 6720 636f 6d6d  plied using comm
-00005020: 616e 6420 6c69 6e65 206f 7074 696f 6e73  and line options
-00005030: 2c20 6279 2073 6574 7469 6e67 2065 6e76  , by setting env
-00005040: 6972 6f6e 6d65 6e74 2076 6172 6961 626c  ironment variabl
-00005050: 6573 2070 7265 6669 7865 6420 7769 7468  es prefixed with
-00005060: 2060 5944 5f56 4152 5f60 2c20 6f72 2062   `YD_VAR_`, or b
-00005070: 7920 696e 636c 7564 696e 6720 7468 6520  y including the 
-00005080: 6469 7265 6374 6976 6573 2069 6e20 7468  directives in th
-00005090: 6520 605b 636f 6d6d 6f6e 5d60 2073 6563  e `[common]` sec
-000050a0: 7469 6f6e 206f 6620 7468 6520 544f 4d4c  tion of the TOML
-000050b0: 2063 6f6e 6669 6775 7261 7469 6f6e 2066   configuration f
-000050c0: 696c 652e 0a0a 312e 2054 6865 202a 2a63  ile...1. The **c
-000050d0: 6f6d 6d61 6e64 206c 696e 652a 2a20 6f70  ommand line** op
-000050e0: 7469 6f6e 2069 7320 602d 2d76 6172 6961  tion is `--varia
-000050f0: 626c 6560 2028 6f72 2060 2d76 6029 2e20  ble` (or `-v`). 
-00005100: 466f 7220 6578 616d 706c 652c 2060 7964  For example, `yd
-00005110: 2d73 7562 6d69 7420 2d76 2070 726f 6a65  -submit -v proje
-00005120: 6374 5f63 6f64 653d 7072 2d32 3133 2d61  ct_code=pr-213-a
-00005130: 202d 7620 7275 6e5f 6964 3d31 3233 3460   -v run_id=1234`
-00005140: 2077 696c 6c20 6573 7461 626c 6973 6820   will establish 
-00005150: 7477 6f20 6e65 7720 7661 7269 6162 6c65  two new variable
-00005160: 7320 7468 6174 2063 616e 2062 6520 7573  s that can be us
-00005170: 6564 2061 7320 607b 7b70 726f 6a65 6374  ed as `{{project
-00005180: 5f63 6f64 657d 7d60 2061 6e64 2060 7b7b  _code}}` and `{{
-00005190: 7275 6e5f 6964 7d7d 602c 2077 6869 6368  run_id}}`, which
-000051a0: 2077 696c 6c20 6265 2073 7562 7374 6974   will be substit
-000051b0: 7574 6564 2062 7920 6070 722d 3231 332d  uted by `pr-213-
-000051c0: 6160 2061 6e64 2060 3132 3334 6020 7265  a` and `1234` re
-000051d0: 7370 6563 7469 7665 6c79 2e0a 0a0a 322e  spectively....2.
-000051e0: 2046 6f72 202a 2a65 6e76 6972 6f6e 6d65   For **environme
-000051f0: 6e74 2076 6172 6961 626c 6573 2a2a 2c20  nt variables**, 
-00005200: 7365 7474 696e 6720 7468 6520 7661 7269  setting the vari
-00005210: 6162 6c65 2060 5944 5f56 4152 5f70 726f  able `YD_VAR_pro
-00005220: 6a65 6374 5f63 6f64 653d 2270 722d 3231  ject_code="pr-21
-00005230: 332d 6122 6020 7769 6c6c 2063 7265 6174  3-a"` will creat
-00005240: 6520 6120 6e65 7720 7661 7269 6162 6c65  e a new variable
-00005250: 2074 6861 7420 6361 6e20 6265 2075 7365   that can be use
-00005260: 6420 6173 2060 7b7b 7072 6f6a 6563 745f  d as `{{project_
-00005270: 636f 6465 7d7d 602c 2077 6869 6368 2077  code}}`, which w
-00005280: 696c 6c20 6265 2073 7562 7374 6974 7574  ill be substitut
-00005290: 6564 2062 7920 6070 722d 3231 332d 6160  ed by `pr-213-a`
-000052a0: 2e0a 0a0a 332e 2046 6f72 202a 2a73 6574  ....3. For **set
-000052b0: 7469 6e67 2077 6974 6869 6e20 7468 6520  ting within the 
-000052c0: 544f 4d4c 2066 696c 652a 2a2c 2069 6e63  TOML file**, inc
-000052d0: 6c75 6465 2061 202a 2a60 7661 7269 6162  lude a **`variab
-000052e0: 6c65 7360 2a2a 2074 6162 6c65 2069 6e20  les`** table in 
-000052f0: 7468 6520 605b 636f 6d6d 6f6e 5d60 2073  the `[common]` s
-00005300: 6563 7469 6f6e 206f 6620 7468 6520 6669  ection of the fi
-00005310: 6c65 2e20 452e 672e 2c20 6076 6172 6961  le. E.g., `varia
-00005320: 626c 6573 203d 207b 7072 6f6a 6563 745f  bles = {project_
-00005330: 636f 6465 203d 2022 7072 2d32 3133 6122  code = "pr-213a"
-00005340: 2c20 7275 6e5f 6964 203d 2022 3132 3334  , run_id = "1234
-00005350: 227d 602e 204e 6f74 6520 7468 6174 2074  "}`. Note that t
-00005360: 6869 7320 6361 6e20 616c 736f 2075 7365  his can also use
-00005370: 2074 6865 2066 6f72 6d3a 0a0a 6060 6074   the form:..```t
-00005380: 6f6d 6c0a 5b63 6f6d 6d6f 6e2e 7661 7269  oml.[common.vari
-00005390: 6162 6c65 735d 0a70 726f 6a65 6374 5f63  ables].project_c
-000053a0: 6f64 6520 3d20 2270 722d 3231 3361 220a  ode = "pr-213a".
-000053b0: 7275 6e5f 6964 203d 2022 3132 3334 220a  run_id = "1234".
-000053c0: 6060 600a 0a44 6972 6563 7469 7665 7320  ```..Directives 
-000053d0: 7365 7420 6f6e 2074 6865 2063 6f6d 6d61  set on the comma
-000053e0: 6e64 206c 696e 6520 7461 6b65 2070 7265  nd line take pre
-000053f0: 6365 6465 6e63 6520 6f76 6572 2064 6972  cedence over dir
-00005400: 6563 7469 7665 7320 7365 7420 696e 2065  ectives set in e
-00005410: 6e76 6972 6f6e 6d65 6e74 2076 6172 6961  nvironment varia
-00005420: 626c 6573 2c20 616e 6420 626f 7468 206f  bles, and both o
-00005430: 6620 7468 656d 2074 616b 6520 7072 6563  f them take prec
-00005440: 6564 656e 6365 206f 7665 7220 6469 7265  edence over dire
-00005450: 6374 6976 6573 2073 6574 2069 6e20 6120  ctives set in a 
-00005460: 544f 4d4c 2066 696c 652e 0a0a 5468 6973  TOML file...This
-00005470: 206d 6574 686f 6420 6361 6e20 6265 2075   method can be u
-00005480: 7365 6420 746f 206f 7665 7272 6964 6520  sed to override 
-00005490: 7468 6520 6465 6661 756c 7420 6469 7265  the default dire
-000054a0: 6374 6976 6573 2c20 652e 672e 2c20 7365  ctives, e.g., se
-000054b0: 7474 696e 6720 602d 7620 7573 6572 6e61  tting `-v userna
-000054c0: 6d65 3d22 6f74 6865 722d 7573 6572 2260  me="other-user"`
-000054d0: 2077 696c 6c20 6f76 6572 7269 6465 2074   will override t
-000054e0: 6865 2064 6566 6175 6c74 2060 7b7b 7573  he default `{{us
-000054f0: 6572 6e61 6d65 7d7d 6020 6469 7265 6374  ername}}` direct
-00005500: 6976 652e 0a0a 2323 204e 6573 7465 6420  ive...## Nested 
-00005510: 5661 7269 6162 6c65 730a 0a49 6e20 7468  Variables..In th
-00005520: 6520 6361 7365 206f 6620 2a2a 544f 4d4c  e case of **TOML
-00005530: 2070 726f 7065 7274 6965 7320 6f6e 6c79   properties only
-00005540: 2a2a 2c20 7661 7269 6162 6c65 2073 7562  **, variable sub
-00005550: 7374 6974 7574 696f 6e73 2063 616e 2062  stitutions can b
-00005560: 6520 6e65 7374 6564 2e0a 0a46 6f72 2065  e nested...For e
-00005570: 7861 6d70 6c65 2c20 6966 206f 6e65 2077  xample, if one w
-00005580: 616e 7465 6420 746f 2073 656c 6563 7420  anted to select 
-00005590: 6120 6469 6666 6572 656e 7420 6074 656d  a different `tem
-000055a0: 706c 6174 6549 6460 2066 6f72 2061 2057  plateId` for a W
-000055b0: 6f72 6b65 7220 506f 6f6c 2064 6570 656e  orker Pool depen
-000055c0: 6469 6e67 206f 6e20 7468 6520 7661 6c75  ding on the valu
-000055d0: 6520 6f66 2061 2060 7265 6769 6f6e 6020  e of a `region` 
-000055e0: 7661 7269 6162 6c65 2c20 6f6e 6520 636f  variable, one co
-000055f0: 756c 6420 7573 6520 7468 6520 666f 6c6c  uld use the foll
-00005600: 6f77 696e 673a 0a0a 6060 6074 6f6d 6c0a  owing:..```toml.
-00005610: 5b63 6f6d 6d6f 6e2e 7661 7269 6162 6c65  [common.variable
-00005620: 735d 0a20 2020 2074 656d 706c 6174 655f  s].    template_
-00005630: 6c6f 6e64 6f6e 203d 2022 7964 6964 3a63  london = "ydid:c
-00005640: 7274 3a36 3545 4634 463a 6134 6437 3537  rt:65EF4F:a4d757
-00005650: 6366 2d62 3637 612d 3465 6236 2d62 6433  cf-b67a-4eb6-bd3
-00005660: 392d 3861 3666 6664 3436 6338 6634 220a  9-8a6ffd46c8f4".
-00005670: 2020 2020 7465 6d70 6c61 7465 5f70 686f      template_pho
-00005680: 656e 6978 203d 2022 7964 6964 3a63 7274  enix = "ydid:crt
-00005690: 3a36 3545 4634 463a 6534 3233 3964 6563  :65EF4F:e4239dec
-000056a0: 2d37 3863 322d 3432 3163 2d61 3766 332d  -78c2-421c-a7f3-
-000056b0: 3731 6536 3162 3732 3934 3666 220a 2020  71e61b72946f".  
-000056c0: 2020 7465 6d70 6c61 7465 5f66 7261 6e6b    template_frank
-000056d0: 6675 7274 203d 2022 7964 6964 3a63 7274  furt = "ydid:crt
-000056e0: 3a36 3545 4634 463a 3332 3936 3032 6366  :65EF4F:329602cf
-000056f0: 2d35 3934 352d 3461 6164 2d61 3238 382d  -5945-4aad-a288-
-00005700: 6561 3432 3464 3634 6435 3565 220a 0a5b  ea424d64d55e"..[
-00005710: 776f 726b 6572 506f 6f6c 5d0a 2020 2020  workerPool].    
-00005720: 7465 6d70 6c61 7465 4964 203d 2022 7b7b  templateId = "{{
-00005730: 7465 6d70 6c61 7465 5f7b 7b72 6567 696f  template_{{regio
-00005740: 6e7d 7d7d 7d22 0a60 6060 0a0a 5468 656e  n}}}}".```..Then
-00005750: 2c20 6966 206f 6e65 2075 7365 6420 6079  , if one used `y
-00005760: 642d 7072 6f76 6973 696f 6e20 2d76 2072  d-provision -v r
-00005770: 6567 696f 6e3d 7068 6f65 6e69 7860 2c20  egion=phoenix`, 
-00005780: 7468 6520 6074 656d 706c 6174 6549 6460  the `templateId`
-00005790: 2070 726f 7065 7274 7920 776f 756c 6420   property would 
-000057a0: 6669 7273 7420 7265 736f 6c76 6520 746f  first resolve to
-000057b0: 2060 227b 7b74 656d 706c 6174 655f 7068   `"{{template_ph
-000057c0: 656f 6e69 787d 7d22 602c 2061 6e64 2074  eonix}}"`, and t
-000057d0: 6865 6e20 746f 2060 2279 6469 643a 6372  hen to `"ydid:cr
-000057e0: 743a 3635 4546 3446 3a65 3432 3339 6465  t:65EF4F:e4239de
-000057f0: 632d 3738 6332 2d34 3231 632d 6137 6633  c-78c2-421c-a7f3
-00005800: 2d37 3165 3631 6237 3239 3436 6622 602e  -71e61b72946f"`.
-00005810: 0a0a 4e65 7374 696e 6720 6361 6e20 6265  ..Nesting can be
-00005820: 2075 7020 746f 2074 6872 6565 206c 6576   up to three lev
-00005830: 656c 7320 6465 6570 2069 6e63 6c75 6469  els deep includi
-00005840: 6e67 2074 6865 2074 6f70 206c 6576 656c  ng the top level
-00005850: 2e0a 0a23 2057 6f72 6b20 5265 7175 6972  ...# Work Requir
-00005860: 656d 656e 7420 5072 6f70 6572 7469 6573  ement Properties
-00005870: 0a0a 5468 6520 6077 6f72 6b52 6571 7569  ..The `workRequi
-00005880: 7265 6d65 6e74 6020 7365 6374 696f 6e20  rement` section 
-00005890: 6f66 2074 6865 2063 6f6e 6669 6775 7261  of the configura
-000058a0: 7469 6f6e 2066 696c 6520 6973 206f 7074  tion file is opt
-000058b0: 696f 6e61 6c2e 2049 7427 7320 7573 6564  ional. It's used
-000058c0: 206f 6e6c 7920 6279 2074 6865 2060 7964   only by the `yd
-000058d0: 2d73 7562 6d69 7460 2063 6f6d 6d61 6e64  -submit` command
-000058e0: 2c20 616e 6420 636f 6e74 726f 6c73 2074  , and controls t
-000058f0: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
-00005900: 656e 7420 7468 6174 2069 7320 7375 626d  ent that is subm
-00005910: 6974 7465 6420 746f 2074 6865 2050 6c61  itted to the Pla
-00005920: 7466 6f72 6d2e 0a0a 5468 6520 6465 7461  tform...The deta
-00005930: 696c 7320 6f66 2061 2057 6f72 6b20 5265  ils of a Work Re
-00005940: 7175 6972 656d 656e 7420 746f 2062 6520  quirement to be 
-00005950: 7375 626d 6974 7465 6420 6361 6e20 6265  submitted can be
-00005960: 2063 6170 7475 7265 6420 656e 7469 7265   captured entire
-00005970: 6c79 2077 6974 6869 6e20 7468 6520 544f  ly within the TO
-00005980: 4d4c 2063 6f6e 6669 6775 7261 7469 6f6e  ML configuration
-00005990: 2066 696c 6520 666f 7220 7369 6d70 6c65   file for simple
-000059a0: 2065 7861 6d70 6c65 732e 204d 6f72 6520   examples. More 
-000059b0: 636f 6d70 6c65 7820 6578 616d 706c 6573  complex examples
-000059c0: 2063 6170 7475 7265 2074 6865 2057 6f72   capture the Wor
-000059d0: 6b20 5265 7175 6972 656d 656e 7420 696e  k Requirement in
-000059e0: 2061 2063 6f6d 6269 6e61 7469 6f6e 206f   a combination o
-000059f0: 6620 7468 6520 544f 4d4c 2066 696c 6520  f the TOML file 
-00005a00: 706c 7573 2061 204a 534f 4e20 646f 6375  plus a JSON docu
-00005a10: 6d65 6e74 2c20 6f72 2069 6e20 6120 4a53  ment, or in a JS
-00005a20: 4f4e 2064 6f63 756d 656e 7420 6f6e 6c79  ON document only
-00005a30: 2e0a 0a23 2320 576f 726b 2052 6571 7569  ...## Work Requi
-00005a40: 7265 6d65 6e74 204a 534f 4e20 4669 6c65  rement JSON File
-00005a50: 2053 7472 7563 7475 7265 0a0a 576f 726b   Structure..Work
-00005a60: 2052 6571 7569 7265 6d65 6e74 7320 6172   Requirements ar
-00005a70: 6520 7265 7072 6573 656e 7465 6420 696e  e represented in
-00005a80: 204a 534f 4e20 646f 6375 6d65 6e74 7320   JSON documents 
-00005a90: 7573 696e 6720 6120 636f 6e74 6169 6e6d  using a containm
-00005aa0: 656e 7420 6869 6572 6172 6368 7920 6f66  ent hierarchy of
-00005ab0: 2061 202a 2a57 6f72 6b20 5265 7175 6972   a **Work Requir
-00005ac0: 656d 656e 742a 2a20 636f 6e74 6169 6e69  ement** containi
-00005ad0: 6e67 2061 202a 2a6c 6973 7420 6f66 2054  ng a **list of T
-00005ae0: 6173 6b20 4772 6f75 7073 2a2a 2c20 636f  ask Groups**, co
-00005af0: 6e74 6169 6e69 6e67 2061 202a 2a6c 6973  ntaining a **lis
-00005b00: 7420 6f66 2054 6173 6b73 2a2a 2e0a 0a41  t of Tasks**...A
-00005b10: 2076 6572 7920 7369 6d70 6c65 2065 7861   very simple exa
-00005b20: 6d70 6c65 2064 6f63 756d 656e 7420 6973  mple document is
-00005b30: 2073 686f 776e 2062 656c 6f77 2077 6974   shown below wit
-00005b40: 6820 6120 746f 702d 6c65 7665 6c20 576f  h a top-level Wo
-00005b50: 726b 2052 6571 7569 7265 6d65 6e74 2063  rk Requirement c
-00005b60: 6f6e 7461 696e 696e 6720 7477 6f20 5461  ontaining two Ta
-00005b70: 736b 2047 726f 7570 7320 6561 6368 2063  sk Groups each c
-00005b80: 6f6e 7461 696e 696e 6720 7477 6f20 5461  ontaining two Ta
-00005b90: 736b 732c 2065 6163 6820 7769 7468 2061  sks, each with a
-00005ba0: 2064 6966 6665 7265 6e74 2073 6574 206f   different set o
-00005bb0: 6620 6172 6775 6d65 6e74 7320 746f 2062  f arguments to b
-00005bc0: 6520 7061 7373 6564 2074 6f20 7468 6520  e passed to the 
-00005bd0: 5461 736b 2e0a 0a60 6060 6a73 6f6e 0a7b  Task...```json.{
-00005be0: 0a20 2022 7461 736b 4772 6f75 7073 223a  .  "taskGroups":
-00005bf0: 205b 0a20 2020 207b 0a20 2020 2020 2022   [.    {.      "
-00005c00: 7461 736b 7322 3a20 5b0a 2020 2020 2020  tasks": [.      
-00005c10: 2020 7b0a 2020 2020 2020 2020 2020 2261    {.          "a
-00005c20: 7267 756d 656e 7473 223a 205b 312c 2032  rguments": [1, 2
-00005c30: 2c20 335d 0a20 2020 2020 2020 207d 2c0a  , 3].        },.
-00005c40: 2020 2020 2020 2020 7b0a 2020 2020 2020          {.      
-00005c50: 2020 2020 2261 7267 756d 656e 7473 223a      "arguments":
-00005c60: 205b 342c 2035 2c20 365d 0a20 2020 2020   [4, 5, 6].     
-00005c70: 2020 207d 0a20 2020 2020 205d 0a20 2020     }.      ].   
-00005c80: 207d 2c0a 2020 2020 7b0a 2020 2020 2020   },.    {.      
-00005c90: 2274 6173 6b73 223a 205b 0a20 2020 2020  "tasks": [.     
-00005ca0: 2020 207b 0a20 2020 2020 2020 2020 2022     {.          "
-00005cb0: 6172 6775 6d65 6e74 7322 3a20 5b37 2c20  arguments": [7, 
-00005cc0: 382c 2039 5d0a 2020 2020 2020 2020 7d2c  8, 9].        },
-00005cd0: 0a20 2020 2020 2020 207b 0a20 2020 2020  .        {.     
-00005ce0: 2020 2020 2022 6172 6775 6d65 6e74 7322       "arguments"
-00005cf0: 3a20 5b31 302c 2031 312c 2031 325d 0a20  : [10, 11, 12]. 
-00005d00: 2020 2020 2020 207d 0a20 2020 2020 205d         }.      ]
-00005d10: 0a20 2020 207d 0a20 205d 0a7d 0a0a 6060  .    }.  ].}..``
-00005d20: 600a 0a54 6f20 7370 6563 6966 7920 7468  `..To specify th
-00005d30: 6520 6669 6c65 2063 6f6e 7461 696e 696e  e file containin
-00005d40: 6720 7468 6520 4a53 4f4e 2064 6f63 756d  g the JSON docum
-00005d50: 656e 742c 2065 6974 6865 7220 706f 7075  ent, either popu
-00005d60: 6c61 7465 2074 6865 2060 776f 726b 5265  late the `workRe
-00005d70: 7175 6972 656d 656e 7444 6174 6160 2070  quirementData` p
-00005d80: 726f 7065 7274 7920 696e 2074 6865 2060  roperty in the `
-00005d90: 776f 726b 5265 7175 6972 656d 656e 7460  workRequirement`
-00005da0: 2073 6563 7469 6f6e 206f 6620 7468 6520   section of the 
-00005db0: 544f 4d4c 2063 6f6e 6669 6775 7261 7469  TOML configurati
-00005dc0: 6f6e 2066 696c 6520 7769 7468 2074 6865  on file with the
-00005dd0: 204a 534f 4e20 6669 6c65 6e61 6d65 2c20   JSON filename, 
-00005de0: 6f72 2073 7065 6369 6679 2069 7420 6f6e  or specify it on
-00005df0: 2074 6865 2063 6f6d 6d61 6e64 206c 696e   the command lin
-00005e00: 6520 7573 696e 6720 7468 6520 602d 2d77  e using the `--w
-00005e10: 6f72 6b2d 7265 7175 6972 656d 656e 7460  ork-requirement`
-00005e20: 206f 7220 602d 7260 206f 7074 696f 6e73   or `-r` options
-00005e30: 2028 7768 6963 6820 7769 6c6c 206f 7665   (which will ove
-00005e40: 7272 6964 6520 7468 6520 7072 6f70 6572  rride the proper
-00005e50: 7479 2069 6e20 7468 6520 544f 4d4c 2066  ty in the TOML f
-00005e60: 696c 6529 2c20 652e 672e 0a0a 6079 642d  ile), e.g...`yd-
-00005e70: 7375 626d 6974 202d 2d63 6f6e 6669 6720  submit --config 
-00005e80: 6d79 636f 6e66 6967 2e74 6f6d 6c20 2d2d  myconfig.toml --
-00005e90: 776f 726b 2d72 6571 7569 7265 6d65 6e74  work-requirement
-00005ea0: 206d 795f 776f 726b 7265 712e 6a73 6f6e   my_workreq.json
-00005eb0: 600a 0a23 2320 5072 6f70 6572 7479 2049  `..## Property I
-00005ec0: 6e68 6572 6974 616e 6365 0a0a 546f 2073  nheritance..To s
-00005ed0: 696d 706c 6966 7920 7468 6520 6465 6669  implify the defi
-00005ee0: 6e69 7469 6f6e 206f 6620 576f 726b 2052  nition of Work R
-00005ef0: 6571 7569 7265 6d65 6e74 732c 2074 6865  equirements, the
-00005f00: 7265 2069 7320 6120 7072 6f70 6572 7479  re is a property
-00005f10: 2069 6e68 6572 6974 616e 6365 206d 6563   inheritance mec
-00005f20: 6861 6e69 736d 2e20 5072 6f70 6572 7469  hanism. Properti
-00005f30: 6573 2074 6861 7420 6172 6520 7365 7420  es that are set 
-00005f40: 6174 2061 2068 6967 6865 7220 6c65 7665  at a higher leve
-00005f50: 6c20 696e 2074 6865 2068 6965 7261 7263  l in the hierarc
-00005f60: 6879 2061 7265 2069 6e68 6572 6974 6564  hy are inherited
-00005f70: 2061 7420 6c6f 7765 7220 6c65 7665 6c73   at lower levels
-00005f80: 2c20 756e 6c65 7373 2065 7870 6c69 6369  , unless explici
-00005f90: 746c 7920 6f76 6572 7269 6464 656e 2e0a  tly overridden..
-00005fa0: 0a54 6869 7320 6d65 616e 7320 7468 6174  .This means that
-00005fb0: 2061 2070 726f 7065 7274 7920 7365 7420   a property set 
-00005fc0: 696e 2074 6865 2060 776f 726b 5265 7175  in the `workRequ
-00005fd0: 6972 656d 656e 7460 2073 6563 7469 6f6e  irement` section
-00005fe0: 206f 6620 7468 6520 544f 4d4c 2066 696c   of the TOML fil
-00005ff0: 6520 6361 6e20 6265 2069 6e68 6572 6974  e can be inherit
-00006000: 6564 2073 7563 6365 7373 6976 656c 7920  ed successively 
-00006010: 6279 2074 6865 2057 6f72 6b20 5265 7175  by the Work Requ
-00006020: 6972 656d 656e 742c 2054 6173 6b20 4772  irement, Task Gr
-00006030: 6f75 7073 2061 6e64 2054 6173 6b73 2069  oups and Tasks i
-00006040: 6e20 7468 6520 4a53 4f4e 2064 6f63 756d  n the JSON docum
-00006050: 656e 7420 2861 7373 756d 696e 6720 7468  ent (assuming th
-00006060: 6520 7072 6f70 6572 7479 2069 7320 7661  e property is va
-00006070: 6c69 6420 6174 2065 6163 6820 6c65 7665  lid at each leve
-00006080: 6c29 2e20 2048 656e 6365 2c20 5461 736b  l).  Hence, Task
-00006090: 7320 696e 6865 7269 7420 6672 6f6d 2054  s inherit from T
-000060a0: 6173 6b20 4772 6f75 7073 2c20 7768 6963  ask Groups, whic
-000060b0: 6820 696e 6865 7269 7420 6672 6f6d 2074  h inherit from t
-000060c0: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
-000060d0: 656e 7420 696e 2074 6865 204a 534f 4e20  ent in the JSON 
-000060e0: 646f 6375 6d65 6e74 2c20 7768 6963 6820  document, which 
-000060f0: 696e 6865 7269 7473 2066 726f 6d20 7468  inherits from th
-00006100: 6520 6077 6f72 6b52 6571 7569 7265 6d65  e `workRequireme
-00006110: 6e74 6020 7072 6f70 6572 7469 6573 2069  nt` properties i
-00006120: 6e20 7468 6520 544f 4d4c 2066 696c 652e  n the TOML file.
-00006130: 0a0a 4f76 6572 7269 6464 656e 2070 726f  ..Overridden pro
-00006140: 7065 7274 6965 7320 6172 6520 616c 736f  perties are also
-00006150: 2069 6e68 6572 6974 6564 2e20 452e 672e   inherited. E.g.
-00006160: 2c20 6966 2061 2070 726f 7065 7274 7920  , if a property 
-00006170: 6973 2073 6574 2061 7420 7468 6520 5461  is set at the Ta
-00006180: 736b 2047 726f 7570 206c 6576 656c 2c20  sk Group level, 
-00006190: 6974 2077 696c 6c20 6265 2069 6e68 6572  it will be inher
-000061a0: 6974 6564 2062 7920 7468 6520 5461 736b  ited by the Task
-000061b0: 7320 696e 2074 6861 7420 5461 736b 2047  s in that Task G
-000061c0: 726f 7570 2075 6e6c 6573 7320 6578 706c  roup unless expl
-000061d0: 6963 6974 6c79 206f 7665 7272 6964 6465  icitly overridde
-000061e0: 6e2e 0a0a 2323 2057 6f72 6b20 5265 7175  n...## Work Requ
-000061f0: 6972 656d 656e 7420 5072 6f70 6572 7479  irement Property
-00006200: 2044 6963 7469 6f6e 6172 790a 0a54 6865   Dictionary..The
-00006210: 2066 6f6c 6c6f 7769 6e67 2074 6162 6c65   following table
-00006220: 206f 7574 6c69 6e65 7320 616c 6c20 7468   outlines all th
-00006230: 6520 7072 6f70 6572 7469 6573 2061 7661  e properties ava
-00006240: 696c 6162 6c65 2066 6f72 2064 6566 696e  ilable for defin
-00006250: 696e 6720 576f 726b 2052 6571 7569 7265  ing Work Require
-00006260: 6d65 6e74 732c 2061 6e64 2074 6865 206c  ments, and the l
-00006270: 6576 656c 7320 6174 2077 6869 6368 2074  evels at which t
-00006280: 6865 7920 6172 6520 616c 6c6f 7765 6420  hey are allowed 
-00006290: 746f 2062 6520 7573 6564 2e20 536f 2c20  to be used. So, 
-000062a0: 666f 7220 6578 616d 706c 652c 2074 6865  for example, the
-000062b0: 2060 7072 6f76 6964 6572 6020 7072 6f70   `provider` prop
-000062c0: 6572 7479 2063 616e 2062 6520 7365 7420  erty can be set 
-000062d0: 696e 2074 6865 2054 4f4d 4c20 6669 6c65  in the TOML file
-000062e0: 2c20 6174 2074 6865 2057 6f72 6b20 5265  , at the Work Re
-000062f0: 7175 6972 656d 656e 7420 4c65 7665 6c20  quirement Level 
-00006300: 6f72 2061 7420 7468 6520 5461 736b 2047  or at the Task G
-00006310: 726f 7570 204c 6576 656c 2c20 6275 7420  roup Level, but 
-00006320: 6e6f 7420 6174 2074 6865 2054 6173 6b20  not at the Task 
-00006330: 6c65 7665 6c2c 2061 6e64 2070 726f 7065  level, and prope
-00006340: 7274 7920 6064 6570 656e 6465 6e74 4f6e  rty `dependentOn
-00006350: 6020 6361 6e20 6f6e 6c79 2062 6520 7365  ` can only be se
-00006360: 7420 6174 2074 6865 2054 6173 6b20 4772  t at the Task Gr
-00006370: 6f75 7020 6c65 7665 6c2e 0a0a 416c 6c20  oup level...All 
-00006380: 7072 6f70 6572 7469 6573 2061 7265 206f  properties are o
-00006390: 7074 696f 6e61 6c20 6578 6365 7074 2066  ptional except f
-000063a0: 6f72 202a 2a60 7461 736b 5479 7065 602a  or **`taskType`*
-000063b0: 2a20 286f 7220 2a2a 6074 6173 6b54 7970  * (or **`taskTyp
-000063c0: 6573 602a 2a29 2e0a 0a7c 2050 726f 7065  es`**)...| Prope
-000063d0: 7274 7920 4e61 6d65 2020 2020 2020 2020  rty Name        
-000063e0: 2020 2020 2020 7c20 4465 7363 7269 7074        | Descript
-000063f0: 696f 6e20 2020 2020 2020 2020 2020 2020  ion             
-00006400: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006410: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006420: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006430: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006440: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004e50: 2020 207c 0a7c 2060 7b7b 7365 6372 6574     |.| `{{secret
+00004e60: 7d7d 6020 2020 207c 2054 6865 2061 7070  }}`    | The app
+00004e70: 6c69 6361 7469 6f6e 2060 7365 6372 6574  lication `secret
+00004e80: 6020 7072 6f70 6572 7479 2e20 2020 2020  ` property.     
+00004e90: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004ea0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004eb0: 2020 7c20 2020 2020 2020 2020 2020 2020    |             
+00004ec0: 2020 2020 2020 2020 2020 2020 7c0a 7c20              |.| 
+00004ed0: 607b 7b75 726c 7d7d 6020 2020 2020 2020  `{{url}}`       
+00004ee0: 7c20 5468 6520 506c 6174 666f 726d 2060  | The Platform `
+00004ef0: 7572 6c60 2070 726f 7065 7274 792e 2020  url` property.  
+00004f00: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004f10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004f20: 2020 2020 2020 2020 2020 207c 2020 2020             |    
+00004f30: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00004f40: 2020 2020 207c 0a0a 466f 7220 7468 6520       |..For the 
+00004f50: 6064 6174 6560 2c20 6074 696d 6560 2c20  `date`, `time`, 
+00004f60: 6064 6174 6574 696d 6560 2061 6e64 2060  `datetime` and `
+00004f70: 7261 6e64 6f6d 6020 6469 7265 6374 6976  random` directiv
+00004f80: 6573 2c20 7468 6520 7361 6d65 2076 616c  es, the same val
+00004f90: 7565 7320 7769 6c6c 2062 6520 7573 6564  ues will be used
+00004fa0: 2066 6f72 2074 6865 2064 7572 6174 696f   for the duratio
+00004fb0: 6e20 6f66 2061 2063 6f6d 6d61 6e64 202d  n of a command -
+00004fc0: 2d20 692e 652e 2c20 6966 2060 7b7b 7469  - i.e., if `{{ti
+00004fd0: 6d65 7d7d 6020 6973 2075 7365 6420 7769  me}}` is used wi
+00004fe0: 7468 696e 206d 756c 7469 706c 6520 7072  thin multiple pr
+00004ff0: 6f70 6572 7469 6573 2c20 7468 6520 7361  operties, the sa
+00005000: 6d65 2076 616c 7565 2077 696c 6c20 6265  me value will be
+00005010: 2075 7365 6420 666f 7220 6561 6368 2073   used for each s
+00005020: 7562 7374 6974 7574 696f 6e2e 0a0a 2323  ubstitution...##
+00005030: 2055 7365 722d 4465 6669 6e65 6420 5661   User-Defined Va
+00005040: 7269 6162 6c65 730a 0a41 7262 6974 7261  riables..Arbitra
+00005050: 7279 2076 6172 6961 626c 6573 2063 616e  ry variables can
+00005060: 2062 6520 7375 7070 6c69 6564 2075 7369   be supplied usi
+00005070: 6e67 2063 6f6d 6d61 6e64 206c 696e 6520  ng command line 
+00005080: 6f70 7469 6f6e 732c 2062 7920 7365 7474  options, by sett
+00005090: 696e 6720 656e 7669 726f 6e6d 656e 7420  ing environment 
+000050a0: 7661 7269 6162 6c65 7320 7072 6566 6978  variables prefix
+000050b0: 6564 2077 6974 6820 6059 445f 5641 525f  ed with `YD_VAR_
+000050c0: 602c 206f 7220 6279 2069 6e63 6c75 6469  `, or by includi
+000050d0: 6e67 2074 6865 2064 6972 6563 7469 7665  ng the directive
+000050e0: 7320 696e 2074 6865 2060 5b63 6f6d 6d6f  s in the `[commo
+000050f0: 6e5d 6020 7365 6374 696f 6e20 6f66 2074  n]` section of t
+00005100: 6865 2054 4f4d 4c20 636f 6e66 6967 7572  he TOML configur
+00005110: 6174 696f 6e20 6669 6c65 2e0a 0a31 2e20  ation file...1. 
+00005120: 5468 6520 2a2a 636f 6d6d 616e 6420 6c69  The **command li
+00005130: 6e65 2a2a 206f 7074 696f 6e20 6973 2060  ne** option is `
+00005140: 2d2d 7661 7269 6162 6c65 6020 286f 7220  --variable` (or 
+00005150: 602d 7660 292e 2046 6f72 2065 7861 6d70  `-v`). For examp
+00005160: 6c65 2c20 6079 642d 7375 626d 6974 202d  le, `yd-submit -
+00005170: 7620 7072 6f6a 6563 745f 636f 6465 3d70  v project_code=p
+00005180: 722d 3231 332d 6120 2d76 2072 756e 5f69  r-213-a -v run_i
+00005190: 643d 3132 3334 6020 7769 6c6c 2065 7374  d=1234` will est
+000051a0: 6162 6c69 7368 2074 776f 206e 6577 2076  ablish two new v
+000051b0: 6172 6961 626c 6573 2074 6861 7420 6361  ariables that ca
+000051c0: 6e20 6265 2075 7365 6420 6173 2060 7b7b  n be used as `{{
+000051d0: 7072 6f6a 6563 745f 636f 6465 7d7d 6020  project_code}}` 
+000051e0: 616e 6420 607b 7b72 756e 5f69 647d 7d60  and `{{run_id}}`
+000051f0: 2c20 7768 6963 6820 7769 6c6c 2062 6520  , which will be 
+00005200: 7375 6273 7469 7475 7465 6420 6279 2060  substituted by `
+00005210: 7072 2d32 3133 2d61 6020 616e 6420 6031  pr-213-a` and `1
+00005220: 3233 3460 2072 6573 7065 6374 6976 656c  234` respectivel
+00005230: 792e 0a0a 0a32 2e20 466f 7220 2a2a 656e  y....2. For **en
+00005240: 7669 726f 6e6d 656e 7420 7661 7269 6162  vironment variab
+00005250: 6c65 732a 2a2c 2073 6574 7469 6e67 2074  les**, setting t
+00005260: 6865 2076 6172 6961 626c 6520 6059 445f  he variable `YD_
+00005270: 5641 525f 7072 6f6a 6563 745f 636f 6465  VAR_project_code
+00005280: 3d22 7072 2d32 3133 2d61 2260 2077 696c  ="pr-213-a"` wil
+00005290: 6c20 6372 6561 7465 2061 206e 6577 2076  l create a new v
+000052a0: 6172 6961 626c 6520 7468 6174 2063 616e  ariable that can
+000052b0: 2062 6520 7573 6564 2061 7320 607b 7b70   be used as `{{p
+000052c0: 726f 6a65 6374 5f63 6f64 657d 7d60 2c20  roject_code}}`, 
+000052d0: 7768 6963 6820 7769 6c6c 2062 6520 7375  which will be su
+000052e0: 6273 7469 7475 7465 6420 6279 2060 7072  bstituted by `pr
+000052f0: 2d32 3133 2d61 602e 0a0a 0a33 2e20 466f  -213-a`....3. Fo
+00005300: 7220 2a2a 7365 7474 696e 6720 7769 7468  r **setting with
+00005310: 696e 2074 6865 2054 4f4d 4c20 6669 6c65  in the TOML file
+00005320: 2a2a 2c20 696e 636c 7564 6520 6120 2a2a  **, include a **
+00005330: 6076 6172 6961 626c 6573 602a 2a20 7461  `variables`** ta
+00005340: 626c 6520 696e 2074 6865 2060 5b63 6f6d  ble in the `[com
+00005350: 6d6f 6e5d 6020 7365 6374 696f 6e20 6f66  mon]` section of
+00005360: 2074 6865 2066 696c 652e 2045 2e67 2e2c   the file. E.g.,
+00005370: 2060 7661 7269 6162 6c65 7320 3d20 7b70   `variables = {p
+00005380: 726f 6a65 6374 5f63 6f64 6520 3d20 2270  roject_code = "p
+00005390: 722d 3231 3361 222c 2072 756e 5f69 6420  r-213a", run_id 
+000053a0: 3d20 2231 3233 3422 7d60 2e20 4e6f 7465  = "1234"}`. Note
+000053b0: 2074 6861 7420 7468 6973 2063 616e 2061   that this can a
+000053c0: 6c73 6f20 7573 6520 7468 6520 666f 726d  lso use the form
+000053d0: 3a0a 0a60 6060 746f 6d6c 0a5b 636f 6d6d  :..```toml.[comm
+000053e0: 6f6e 2e76 6172 6961 626c 6573 5d0a 7072  on.variables].pr
+000053f0: 6f6a 6563 745f 636f 6465 203d 2022 7072  oject_code = "pr
+00005400: 2d32 3133 6122 0a72 756e 5f69 6420 3d20  -213a".run_id = 
+00005410: 2231 3233 3422 0a60 6060 0a0a 4469 7265  "1234".```..Dire
+00005420: 6374 6976 6573 2073 6574 206f 6e20 7468  ctives set on th
+00005430: 6520 636f 6d6d 616e 6420 6c69 6e65 2074  e command line t
+00005440: 616b 6520 7072 6563 6564 656e 6365 206f  ake precedence o
+00005450: 7665 7220 6469 7265 6374 6976 6573 2073  ver directives s
+00005460: 6574 2069 6e20 656e 7669 726f 6e6d 656e  et in environmen
+00005470: 7420 7661 7269 6162 6c65 732c 2061 6e64  t variables, and
+00005480: 2062 6f74 6820 6f66 2074 6865 6d20 7461   both of them ta
+00005490: 6b65 2070 7265 6365 6465 6e63 6520 6f76  ke precedence ov
+000054a0: 6572 2064 6972 6563 7469 7665 7320 7365  er directives se
+000054b0: 7420 696e 2061 2054 4f4d 4c20 6669 6c65  t in a TOML file
+000054c0: 2e0a 0a54 6869 7320 6d65 7468 6f64 2063  ...This method c
+000054d0: 616e 2062 6520 7573 6564 2074 6f20 6f76  an be used to ov
+000054e0: 6572 7269 6465 2074 6865 2064 6566 6175  erride the defau
+000054f0: 6c74 2064 6972 6563 7469 7665 732c 2065  lt directives, e
+00005500: 2e67 2e2c 2073 6574 7469 6e67 2060 2d76  .g., setting `-v
+00005510: 2075 7365 726e 616d 653d 226f 7468 6572   username="other
+00005520: 2d75 7365 7222 6020 7769 6c6c 206f 7665  -user"` will ove
+00005530: 7272 6964 6520 7468 6520 6465 6661 756c  rride the defaul
+00005540: 7420 607b 7b75 7365 726e 616d 657d 7d60  t `{{username}}`
+00005550: 2064 6972 6563 7469 7665 2e0a 0a23 2320   directive...## 
+00005560: 4e65 7374 6564 2056 6172 6961 626c 6573  Nested Variables
+00005570: 0a0a 496e 2074 6865 2063 6173 6520 6f66  ..In the case of
+00005580: 202a 2a54 4f4d 4c20 7072 6f70 6572 7469   **TOML properti
+00005590: 6573 206f 6e6c 792a 2a2c 2076 6172 6961  es only**, varia
+000055a0: 626c 6520 7375 6273 7469 7475 7469 6f6e  ble substitution
+000055b0: 7320 6361 6e20 6265 206e 6573 7465 642e  s can be nested.
+000055c0: 0a0a 466f 7220 6578 616d 706c 652c 2069  ..For example, i
+000055d0: 6620 6f6e 6520 7761 6e74 6564 2074 6f20  f one wanted to 
+000055e0: 7365 6c65 6374 2061 2064 6966 6665 7265  select a differe
+000055f0: 6e74 2060 7465 6d70 6c61 7465 4964 6020  nt `templateId` 
+00005600: 666f 7220 6120 576f 726b 6572 2050 6f6f  for a Worker Poo
+00005610: 6c20 6465 7065 6e64 696e 6720 6f6e 2074  l depending on t
+00005620: 6865 2076 616c 7565 206f 6620 6120 6072  he value of a `r
+00005630: 6567 696f 6e60 2076 6172 6961 626c 652c  egion` variable,
+00005640: 206f 6e65 2063 6f75 6c64 2075 7365 2074   one could use t
+00005650: 6865 2066 6f6c 6c6f 7769 6e67 3a0a 0a60  he following:..`
+00005660: 6060 746f 6d6c 0a5b 636f 6d6d 6f6e 2e76  ``toml.[common.v
+00005670: 6172 6961 626c 6573 5d0a 2020 2020 7465  ariables].    te
+00005680: 6d70 6c61 7465 5f6c 6f6e 646f 6e20 3d20  mplate_london = 
+00005690: 2279 6469 643a 6372 743a 3635 4546 3446  "ydid:crt:65EF4F
+000056a0: 3a61 3464 3735 3763 662d 6236 3761 2d34  :a4d757cf-b67a-4
+000056b0: 6562 362d 6264 3339 2d38 6136 6666 6434  eb6-bd39-8a6ffd4
+000056c0: 3663 3866 3422 0a20 2020 2074 656d 706c  6c8f4".    templ
+000056d0: 6174 655f 7068 6f65 6e69 7820 3d20 2279  ate_phoenix = "y
+000056e0: 6469 643a 6372 743a 3635 4546 3446 3a65  did:crt:65EF4F:e
+000056f0: 3432 3339 6465 632d 3738 6332 2d34 3231  4239dec-78c2-421
+00005700: 632d 6137 6633 2d37 3165 3631 6237 3239  c-a7f3-71e61b729
+00005710: 3436 6622 0a20 2020 2074 656d 706c 6174  46f".    templat
+00005720: 655f 6672 616e 6b66 7572 7420 3d20 2279  e_frankfurt = "y
+00005730: 6469 643a 6372 743a 3635 4546 3446 3a33  did:crt:65EF4F:3
+00005740: 3239 3630 3263 662d 3539 3435 2d34 6161  29602cf-5945-4aa
+00005750: 642d 6132 3838 2d65 6134 3234 6436 3464  d-a288-ea424d64d
+00005760: 3535 6522 0a0a 5b77 6f72 6b65 7250 6f6f  55e"..[workerPoo
+00005770: 6c5d 0a20 2020 2074 656d 706c 6174 6549  l].    templateI
+00005780: 6420 3d20 227b 7b74 656d 706c 6174 655f  d = "{{template_
+00005790: 7b7b 7265 6769 6f6e 7d7d 7d7d 220a 6060  {{region}}}}".``
+000057a0: 600a 0a54 6865 6e2c 2069 6620 6f6e 6520  `..Then, if one 
+000057b0: 7573 6564 2060 7964 2d70 726f 7669 7369  used `yd-provisi
+000057c0: 6f6e 202d 7620 7265 6769 6f6e 3d70 686f  on -v region=pho
+000057d0: 656e 6978 602c 2074 6865 2060 7465 6d70  enix`, the `temp
+000057e0: 6c61 7465 4964 6020 7072 6f70 6572 7479  lateId` property
+000057f0: 2077 6f75 6c64 2066 6972 7374 2072 6573   would first res
+00005800: 6f6c 7665 2074 6f20 6022 7b7b 7465 6d70  olve to `"{{temp
+00005810: 6c61 7465 5f70 6865 6f6e 6978 7d7d 2260  late_pheonix}}"`
+00005820: 2c20 616e 6420 7468 656e 2074 6f20 6022  , and then to `"
+00005830: 7964 6964 3a63 7274 3a36 3545 4634 463a  ydid:crt:65EF4F:
+00005840: 6534 3233 3964 6563 2d37 3863 322d 3432  e4239dec-78c2-42
+00005850: 3163 2d61 3766 332d 3731 6536 3162 3732  1c-a7f3-71e61b72
+00005860: 3934 3666 2260 2e0a 0a4e 6573 7469 6e67  946f"`...Nesting
+00005870: 2063 616e 2062 6520 7570 2074 6f20 7468   can be up to th
+00005880: 7265 6520 6c65 7665 6c73 2064 6565 7020  ree levels deep 
+00005890: 696e 636c 7564 696e 6720 7468 6520 746f  including the to
+000058a0: 7020 6c65 7665 6c2e 0a0a 2320 576f 726b  p level...# Work
+000058b0: 2052 6571 7569 7265 6d65 6e74 2050 726f   Requirement Pro
+000058c0: 7065 7274 6965 730a 0a54 6865 2060 776f  perties..The `wo
+000058d0: 726b 5265 7175 6972 656d 656e 7460 2073  rkRequirement` s
+000058e0: 6563 7469 6f6e 206f 6620 7468 6520 636f  ection of the co
+000058f0: 6e66 6967 7572 6174 696f 6e20 6669 6c65  nfiguration file
+00005900: 2069 7320 6f70 7469 6f6e 616c 2e20 4974   is optional. It
+00005910: 2773 2075 7365 6420 6f6e 6c79 2062 7920  's used only by 
+00005920: 7468 6520 6079 642d 7375 626d 6974 6020  the `yd-submit` 
+00005930: 636f 6d6d 616e 642c 2061 6e64 2063 6f6e  command, and con
+00005940: 7472 6f6c 7320 7468 6520 576f 726b 2052  trols the Work R
+00005950: 6571 7569 7265 6d65 6e74 2074 6861 7420  equirement that 
+00005960: 6973 2073 7562 6d69 7474 6564 2074 6f20  is submitted to 
+00005970: 7468 6520 506c 6174 666f 726d 2e0a 0a54  the Platform...T
+00005980: 6865 2064 6574 6169 6c73 206f 6620 6120  he details of a 
+00005990: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+000059a0: 2074 6f20 6265 2073 7562 6d69 7474 6564   to be submitted
+000059b0: 2063 616e 2062 6520 6361 7074 7572 6564   can be captured
+000059c0: 2065 6e74 6972 656c 7920 7769 7468 696e   entirely within
+000059d0: 2074 6865 2054 4f4d 4c20 636f 6e66 6967   the TOML config
+000059e0: 7572 6174 696f 6e20 6669 6c65 2066 6f72  uration file for
+000059f0: 2073 696d 706c 6520 6578 616d 706c 6573   simple examples
+00005a00: 2e20 4d6f 7265 2063 6f6d 706c 6578 2065  . More complex e
+00005a10: 7861 6d70 6c65 7320 6361 7074 7572 6520  xamples capture 
+00005a20: 7468 6520 576f 726b 2052 6571 7569 7265  the Work Require
+00005a30: 6d65 6e74 2069 6e20 6120 636f 6d62 696e  ment in a combin
+00005a40: 6174 696f 6e20 6f66 2074 6865 2054 4f4d  ation of the TOM
+00005a50: 4c20 6669 6c65 2070 6c75 7320 6120 4a53  L file plus a JS
+00005a60: 4f4e 2064 6f63 756d 656e 742c 206f 7220  ON document, or 
+00005a70: 696e 2061 204a 534f 4e20 646f 6375 6d65  in a JSON docume
+00005a80: 6e74 206f 6e6c 792e 0a0a 2323 2057 6f72  nt only...## Wor
+00005a90: 6b20 5265 7175 6972 656d 656e 7420 4a53  k Requirement JS
+00005aa0: 4f4e 2046 696c 6520 5374 7275 6374 7572  ON File Structur
+00005ab0: 650a 0a57 6f72 6b20 5265 7175 6972 656d  e..Work Requirem
+00005ac0: 656e 7473 2061 7265 2072 6570 7265 7365  ents are represe
+00005ad0: 6e74 6564 2069 6e20 4a53 4f4e 2064 6f63  nted in JSON doc
+00005ae0: 756d 656e 7473 2075 7369 6e67 2061 2063  uments using a c
+00005af0: 6f6e 7461 696e 6d65 6e74 2068 6965 7261  ontainment hiera
+00005b00: 7263 6879 206f 6620 6120 2a2a 576f 726b  rchy of a **Work
+00005b10: 2052 6571 7569 7265 6d65 6e74 2a2a 2063   Requirement** c
+00005b20: 6f6e 7461 696e 696e 6720 6120 2a2a 6c69  ontaining a **li
+00005b30: 7374 206f 6620 5461 736b 2047 726f 7570  st of Task Group
+00005b40: 732a 2a2c 2063 6f6e 7461 696e 696e 6720  s**, containing 
+00005b50: 6120 2a2a 6c69 7374 206f 6620 5461 736b  a **list of Task
+00005b60: 732a 2a2e 0a0a 4120 7665 7279 2073 696d  s**...A very sim
+00005b70: 706c 6520 6578 616d 706c 6520 646f 6375  ple example docu
+00005b80: 6d65 6e74 2069 7320 7368 6f77 6e20 6265  ment is shown be
+00005b90: 6c6f 7720 7769 7468 2061 2074 6f70 2d6c  low with a top-l
+00005ba0: 6576 656c 2057 6f72 6b20 5265 7175 6972  evel Work Requir
+00005bb0: 656d 656e 7420 636f 6e74 6169 6e69 6e67  ement containing
+00005bc0: 2074 776f 2054 6173 6b20 4772 6f75 7073   two Task Groups
+00005bd0: 2065 6163 6820 636f 6e74 6169 6e69 6e67   each containing
+00005be0: 2074 776f 2054 6173 6b73 2c20 6561 6368   two Tasks, each
+00005bf0: 2077 6974 6820 6120 6469 6666 6572 656e   with a differen
+00005c00: 7420 7365 7420 6f66 2061 7267 756d 656e  t set of argumen
+00005c10: 7473 2074 6f20 6265 2070 6173 7365 6420  ts to be passed 
+00005c20: 746f 2074 6865 2054 6173 6b2e 0a0a 6060  to the Task...``
+00005c30: 606a 736f 6e0a 7b0a 2020 2274 6173 6b47  `json.{.  "taskG
+00005c40: 726f 7570 7322 3a20 5b0a 2020 2020 7b0a  roups": [.    {.
+00005c50: 2020 2020 2020 2274 6173 6b73 223a 205b        "tasks": [
+00005c60: 0a20 2020 2020 2020 207b 0a20 2020 2020  .        {.     
+00005c70: 2020 2020 2022 6172 6775 6d65 6e74 7322       "arguments"
+00005c80: 3a20 5b31 2c20 322c 2033 5d0a 2020 2020  : [1, 2, 3].    
+00005c90: 2020 2020 7d2c 0a20 2020 2020 2020 207b      },.        {
+00005ca0: 0a20 2020 2020 2020 2020 2022 6172 6775  .          "argu
+00005cb0: 6d65 6e74 7322 3a20 5b34 2c20 352c 2036  ments": [4, 5, 6
+00005cc0: 5d0a 2020 2020 2020 2020 7d0a 2020 2020  ].        }.    
+00005cd0: 2020 5d0a 2020 2020 7d2c 0a20 2020 207b    ].    },.    {
+00005ce0: 0a20 2020 2020 2022 7461 736b 7322 3a20  .      "tasks": 
+00005cf0: 5b0a 2020 2020 2020 2020 7b0a 2020 2020  [.        {.    
+00005d00: 2020 2020 2020 2261 7267 756d 656e 7473        "arguments
+00005d10: 223a 205b 372c 2038 2c20 395d 0a20 2020  ": [7, 8, 9].   
+00005d20: 2020 2020 207d 2c0a 2020 2020 2020 2020       },.        
+00005d30: 7b0a 2020 2020 2020 2020 2020 2261 7267  {.          "arg
+00005d40: 756d 656e 7473 223a 205b 3130 2c20 3131  uments": [10, 11
+00005d50: 2c20 3132 5d0a 2020 2020 2020 2020 7d0a  , 12].        }.
+00005d60: 2020 2020 2020 5d0a 2020 2020 7d0a 2020        ].    }.  
+00005d70: 5d0a 7d0a 0a60 6060 0a0a 546f 2073 7065  ].}..```..To spe
+00005d80: 6369 6679 2074 6865 2066 696c 6520 636f  cify the file co
+00005d90: 6e74 6169 6e69 6e67 2074 6865 204a 534f  ntaining the JSO
+00005da0: 4e20 646f 6375 6d65 6e74 2c20 6569 7468  N document, eith
+00005db0: 6572 2070 6f70 756c 6174 6520 7468 6520  er populate the 
+00005dc0: 6077 6f72 6b52 6571 7569 7265 6d65 6e74  `workRequirement
+00005dd0: 4461 7461 6020 7072 6f70 6572 7479 2069  Data` property i
+00005de0: 6e20 7468 6520 6077 6f72 6b52 6571 7569  n the `workRequi
+00005df0: 7265 6d65 6e74 6020 7365 6374 696f 6e20  rement` section 
+00005e00: 6f66 2074 6865 2054 4f4d 4c20 636f 6e66  of the TOML conf
+00005e10: 6967 7572 6174 696f 6e20 6669 6c65 2077  iguration file w
+00005e20: 6974 6820 7468 6520 4a53 4f4e 2066 696c  ith the JSON fil
+00005e30: 656e 616d 652c 206f 7220 7370 6563 6966  ename, or specif
+00005e40: 7920 6974 206f 6e20 7468 6520 636f 6d6d  y it on the comm
+00005e50: 616e 6420 6c69 6e65 2075 7369 6e67 2074  and line using t
+00005e60: 6865 2060 2d2d 776f 726b 2d72 6571 7569  he `--work-requi
+00005e70: 7265 6d65 6e74 6020 6f72 2060 2d72 6020  rement` or `-r` 
+00005e80: 6f70 7469 6f6e 7320 2877 6869 6368 2077  options (which w
+00005e90: 696c 6c20 6f76 6572 7269 6465 2074 6865  ill override the
+00005ea0: 2070 726f 7065 7274 7920 696e 2074 6865   property in the
+00005eb0: 2054 4f4d 4c20 6669 6c65 292c 2065 2e67   TOML file), e.g
+00005ec0: 2e0a 0a60 7964 2d73 7562 6d69 7420 2d2d  ...`yd-submit --
+00005ed0: 636f 6e66 6967 206d 7963 6f6e 6669 672e  config myconfig.
+00005ee0: 746f 6d6c 202d 2d77 6f72 6b2d 7265 7175  toml --work-requ
+00005ef0: 6972 656d 656e 7420 6d79 5f77 6f72 6b72  irement my_workr
+00005f00: 6571 2e6a 736f 6e60 0a0a 2323 2050 726f  eq.json`..## Pro
+00005f10: 7065 7274 7920 496e 6865 7269 7461 6e63  perty Inheritanc
+00005f20: 650a 0a54 6f20 7369 6d70 6c69 6679 2074  e..To simplify t
+00005f30: 6865 2064 6566 696e 6974 696f 6e20 6f66  he definition of
+00005f40: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+00005f50: 7473 2c20 7468 6572 6520 6973 2061 2070  ts, there is a p
+00005f60: 726f 7065 7274 7920 696e 6865 7269 7461  roperty inherita
+00005f70: 6e63 6520 6d65 6368 616e 6973 6d2e 2050  nce mechanism. P
+00005f80: 726f 7065 7274 6965 7320 7468 6174 2061  roperties that a
+00005f90: 7265 2073 6574 2061 7420 6120 6869 6768  re set at a high
+00005fa0: 6572 206c 6576 656c 2069 6e20 7468 6520  er level in the 
+00005fb0: 6869 6572 6172 6368 7920 6172 6520 696e  hierarchy are in
+00005fc0: 6865 7269 7465 6420 6174 206c 6f77 6572  herited at lower
+00005fd0: 206c 6576 656c 732c 2075 6e6c 6573 7320   levels, unless 
+00005fe0: 6578 706c 6963 6974 6c79 206f 7665 7272  explicitly overr
+00005ff0: 6964 6465 6e2e 0a0a 5468 6973 206d 6561  idden...This mea
+00006000: 6e73 2074 6861 7420 6120 7072 6f70 6572  ns that a proper
+00006010: 7479 2073 6574 2069 6e20 7468 6520 6077  ty set in the `w
+00006020: 6f72 6b52 6571 7569 7265 6d65 6e74 6020  orkRequirement` 
+00006030: 7365 6374 696f 6e20 6f66 2074 6865 2054  section of the T
+00006040: 4f4d 4c20 6669 6c65 2063 616e 2062 6520  OML file can be 
+00006050: 696e 6865 7269 7465 6420 7375 6363 6573  inherited succes
+00006060: 7369 7665 6c79 2062 7920 7468 6520 576f  sively by the Wo
+00006070: 726b 2052 6571 7569 7265 6d65 6e74 2c20  rk Requirement, 
+00006080: 5461 736b 2047 726f 7570 7320 616e 6420  Task Groups and 
+00006090: 5461 736b 7320 696e 2074 6865 204a 534f  Tasks in the JSO
+000060a0: 4e20 646f 6375 6d65 6e74 2028 6173 7375  N document (assu
+000060b0: 6d69 6e67 2074 6865 2070 726f 7065 7274  ming the propert
+000060c0: 7920 6973 2076 616c 6964 2061 7420 6561  y is valid at ea
+000060d0: 6368 206c 6576 656c 292e 2020 4865 6e63  ch level).  Henc
+000060e0: 652c 2054 6173 6b73 2069 6e68 6572 6974  e, Tasks inherit
+000060f0: 2066 726f 6d20 5461 736b 2047 726f 7570   from Task Group
+00006100: 732c 2077 6869 6368 2069 6e68 6572 6974  s, which inherit
+00006110: 2066 726f 6d20 7468 6520 576f 726b 2052   from the Work R
+00006120: 6571 7569 7265 6d65 6e74 2069 6e20 7468  equirement in th
+00006130: 6520 4a53 4f4e 2064 6f63 756d 656e 742c  e JSON document,
+00006140: 2077 6869 6368 2069 6e68 6572 6974 7320   which inherits 
+00006150: 6672 6f6d 2074 6865 2060 776f 726b 5265  from the `workRe
+00006160: 7175 6972 656d 656e 7460 2070 726f 7065  quirement` prope
+00006170: 7274 6965 7320 696e 2074 6865 2054 4f4d  rties in the TOM
+00006180: 4c20 6669 6c65 2e0a 0a4f 7665 7272 6964  L file...Overrid
+00006190: 6465 6e20 7072 6f70 6572 7469 6573 2061  den properties a
+000061a0: 7265 2061 6c73 6f20 696e 6865 7269 7465  re also inherite
+000061b0: 642e 2045 2e67 2e2c 2069 6620 6120 7072  d. E.g., if a pr
+000061c0: 6f70 6572 7479 2069 7320 7365 7420 6174  operty is set at
+000061d0: 2074 6865 2054 6173 6b20 4772 6f75 7020   the Task Group 
+000061e0: 6c65 7665 6c2c 2069 7420 7769 6c6c 2062  level, it will b
+000061f0: 6520 696e 6865 7269 7465 6420 6279 2074  e inherited by t
+00006200: 6865 2054 6173 6b73 2069 6e20 7468 6174  he Tasks in that
+00006210: 2054 6173 6b20 4772 6f75 7020 756e 6c65   Task Group unle
+00006220: 7373 2065 7870 6c69 6369 746c 7920 6f76  ss explicitly ov
+00006230: 6572 7269 6464 656e 2e0a 0a23 2320 576f  erridden...## Wo
+00006240: 726b 2052 6571 7569 7265 6d65 6e74 2050  rk Requirement P
+00006250: 726f 7065 7274 7920 4469 6374 696f 6e61  roperty Dictiona
+00006260: 7279 0a0a 5468 6520 666f 6c6c 6f77 696e  ry..The followin
+00006270: 6720 7461 626c 6520 6f75 746c 696e 6573  g table outlines
+00006280: 2061 6c6c 2074 6865 2070 726f 7065 7274   all the propert
+00006290: 6965 7320 6176 6169 6c61 626c 6520 666f  ies available fo
+000062a0: 7220 6465 6669 6e69 6e67 2057 6f72 6b20  r defining Work 
+000062b0: 5265 7175 6972 656d 656e 7473 2c20 616e  Requirements, an
+000062c0: 6420 7468 6520 6c65 7665 6c73 2061 7420  d the levels at 
+000062d0: 7768 6963 6820 7468 6579 2061 7265 2061  which they are a
+000062e0: 6c6c 6f77 6564 2074 6f20 6265 2075 7365  llowed to be use
+000062f0: 642e 2053 6f2c 2066 6f72 2065 7861 6d70  d. So, for examp
+00006300: 6c65 2c20 7468 6520 6070 726f 7669 6465  le, the `provide
+00006310: 7260 2070 726f 7065 7274 7920 6361 6e20  r` property can 
+00006320: 6265 2073 6574 2069 6e20 7468 6520 544f  be set in the TO
+00006330: 4d4c 2066 696c 652c 2061 7420 7468 6520  ML file, at the 
+00006340: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+00006350: 204c 6576 656c 206f 7220 6174 2074 6865   Level or at the
+00006360: 2054 6173 6b20 4772 6f75 7020 4c65 7665   Task Group Leve
+00006370: 6c2c 2062 7574 206e 6f74 2061 7420 7468  l, but not at th
+00006380: 6520 5461 736b 206c 6576 656c 2c20 616e  e Task level, an
+00006390: 6420 7072 6f70 6572 7479 2060 6465 7065  d property `depe
+000063a0: 6e64 656e 744f 6e60 2063 616e 206f 6e6c  ndentOn` can onl
+000063b0: 7920 6265 2073 6574 2061 7420 7468 6520  y be set at the 
+000063c0: 5461 736b 2047 726f 7570 206c 6576 656c  Task Group level
+000063d0: 2e0a 0a41 6c6c 2070 726f 7065 7274 6965  ...All propertie
+000063e0: 7320 6172 6520 6f70 7469 6f6e 616c 2065  s are optional e
+000063f0: 7863 6570 7420 666f 7220 2a2a 6074 6173  xcept for **`tas
+00006400: 6b54 7970 6560 2a2a 2028 6f72 202a 2a60  kType`** (or **`
+00006410: 7461 736b 5479 7065 7360 2a2a 292e 0a0a  taskTypes`**)...
+00006420: 7c20 5072 6f70 6572 7479 204e 616d 6520  | Property Name 
+00006430: 2020 2020 2020 2020 2020 2020 207c 2044               | D
+00006440: 6573 6372 6970 7469 6f6e 2020 2020 2020  escription      
 00006450: 2020 2020 2020 2020 2020 2020 2020 2020                  
 00006460: 2020 2020 2020 2020 2020 2020 2020 2020                  
 00006470: 2020 2020 2020 2020 2020 2020 2020 2020                  
 00006480: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006490: 207c 2054 4f4d 4c20 7c20 5752 2020 7c20   | TOML | WR  | 
-000064a0: 5447 7270 207c 2054 6173 6b20 7c0a 7c3a  TGrp | Task |.|:
-000064b0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000064c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c 3a2d 2d2d  -----------|:---
-000064d0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000064e0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000064f0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00006500: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00006490: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000064a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000064b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000064c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000064d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000064e0: 2020 2020 2020 2020 7c20 544f 4d4c 207c          | TOML |
+000064f0: 2057 5220 207c 2054 4772 7020 7c20 5461   WR  | TGrp | Ta
+00006500: 736b 207c 0a7c 3a2d 2d2d 2d2d 2d2d 2d2d  sk |.|:---------
 00006510: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00006520: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00006520: 2d2d 7c3a 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  --|:------------
 00006530: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 00006540: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 00006550: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 00006560: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00006570: 2d2d 2d2d 2d2d 7c3a 2d2d 2d2d 2d7c 3a2d  ------|:-----|:-
-00006580: 2d2d 2d7c 3a2d 2d2d 2d2d 7c3a 2d2d 2d2d  ---|:-----|:----
-00006590: 2d7c 0a7c 2060 6172 6775 6d65 6e74 7360  -|.| `arguments`
-000065a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000065b0: 7c20 5468 6520 6c69 7374 206f 6620 6172  | The list of ar
-000065c0: 6775 6d65 6e74 7320 746f 2062 6520 7061  guments to be pa
-000065d0: 7373 6564 2074 6f20 7468 6520 5461 736b  ssed to the Task
-000065e0: 2077 6865 6e20 6974 2069 7320 6578 6563   when it is exec
-000065f0: 7574 6564 2e20 452e 672e 3a20 605b 312c  uted. E.g.: `[1,
-00006600: 2022 5477 6f22 5d60 2e20 2020 2020 2020   "Two"]`.       
-00006610: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006620: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006630: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006640: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006650: 2020 2020 2020 2020 2020 207c 2059 6573             | Yes
-00006660: 2020 7c20 5965 7320 7c20 5965 7320 207c    | Yes | Yes  |
-00006670: 2059 6573 2020 7c0a 7c20 6063 6170 7475   Yes  |.| `captu
-00006680: 7265 5461 736b 4f75 7470 7574 6020 2020  reTaskOutput`   
-00006690: 2020 2020 207c 2057 6865 7468 6572 2074       | Whether t
-000066a0: 6865 2063 6f6e 736f 6c65 206f 7574 7075  he console outpu
-000066b0: 7420 6f66 2061 2054 6173 6b27 7320 7072  t of a Task's pr
-000066c0: 6f63 6573 7320 7368 6f75 6c64 2062 6520  ocess should be 
-000066d0: 7570 6c6f 6164 6564 2074 6f20 7468 6520  uploaded to the 
-000066e0: 5965 6c6c 6f77 446f 6720 4f62 6a65 6374  YellowDog Object
-000066f0: 2053 746f 7265 206f 6e20 5461 736b 2063   Store on Task c
-00006700: 6f6d 706c 6574 696f 6e2e 2044 6566 6175  ompletion. Defau
-00006710: 6c74 3a20 6074 7275 6560 2e20 2020 2020  lt: `true`.     
-00006720: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006730: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006740: 7c20 5965 7320 207c 2059 6573 207c 2059  | Yes  | Yes | Y
-00006750: 6573 2020 7c20 5965 7320 207c 0a7c 2060  es  | Yes  |.| `
-00006760: 636f 6d70 6c65 7465 6454 6173 6b54 746c  completedTaskTtl
-00006770: 6020 2020 2020 2020 2020 7c20 5468 6520  `         | The 
-00006780: 7469 6d65 2028 696e 206d 696e 7574 6573  time (in minutes
-00006790: 2920 746f 206c 6976 6520 666f 7220 636f  ) to live for co
-000067a0: 6d70 6c65 7465 6420 5461 736b 732e 2049  mpleted Tasks. I
-000067b0: 6620 7365 742c 2054 6173 6b73 2074 6861  f set, Tasks tha
-000067c0: 7420 6861 7665 2062 6565 6e20 636f 6d70  t have been comp
-000067d0: 6c65 7465 6420 666f 7220 6c6f 6e67 6572  leted for longer
-000067e0: 2074 6861 6e20 7468 6973 2070 6572 696f   than this perio
-000067f0: 6420 7769 6c6c 2062 6520 6465 6c65 7465  d will be delete
-00006800: 642e 2045 2e67 2e3a 2060 3130 2e30 602e  d. E.g.: `10.0`.
-00006810: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006820: 2020 2020 207c 2059 6573 2020 7c20 5965       | Yes  | Ye
-00006830: 7320 7c20 5965 7320 207c 2020 2020 2020  s | Yes  |      
-00006840: 7c0a 7c20 6063 7376 4669 6c65 6020 2020  |.| `csvFile`   
-00006850: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00006860: 2054 6865 206e 616d 6520 6f66 2074 6865   The name of the
-00006870: 2043 5356 2066 696c 6520 7573 6564 2074   CSV file used t
-00006880: 6f20 6465 7269 7665 2054 6173 6b20 6461  o derive Task da
-00006890: 7461 2e20 416e 2061 6c74 6572 6e61 7469  ta. An alternati
-000068a0: 7665 2074 6f20 6063 7376 4669 6c65 7360  ve to `csvFiles`
-000068b0: 2074 6861 7420 6361 6e20 6265 2075 7365   that can be use
-000068c0: 6420 7768 656e 2074 6865 7265 2773 206f  d when there's o
-000068d0: 6e6c 7920 6120 7369 6e67 6c65 2043 5356  nly a single CSV
-000068e0: 2066 696c 652e 2045 2e67 2e20 6022 6669   file. E.g. `"fi
-000068f0: 6c65 2e63 7376 2260 2e20 2020 2020 2020  le.csv"`.       
-00006900: 2020 2020 2020 2020 2020 7c20 5965 7320            | Yes 
-00006910: 207c 2020 2020 207c 2020 2020 2020 7c20   |     |      | 
-00006920: 2020 2020 207c 0a7c 2060 6373 7646 696c       |.| `csvFil
-00006930: 6573 6020 2020 2020 2020 2020 2020 2020  es`             
-00006940: 2020 2020 7c20 4120 6c69 7374 206f 6620      | A list of 
-00006950: 4353 5620 6669 6c65 7320 7573 6564 2074  CSV files used t
-00006960: 6f20 6465 7269 7665 2054 6173 6b20 6461  o derive Task da
-00006970: 7461 2e20 452e 672e 2060 5b22 6669 6c65  ta. E.g. `["file
-00006980: 2e63 7376 222c 2022 6669 6c65 5f32 2e63  .csv", "file_2.c
-00006990: 7376 3a32 5d60 2e20 2020 2020 2020 2020  sv:2]`.         
-000069a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000069b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000069c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000069d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000069e0: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-000069f0: 2059 6573 2020 7c20 2020 2020 7c20 2020   Yes  |     |   
-00006a00: 2020 207c 2020 2020 2020 7c0a 7c20 6064     |      |.| `d
-00006a10: 6570 656e 6465 6e74 4f6e 6020 2020 2020  ependentOn`     
-00006a20: 2020 2020 2020 2020 207c 2054 6865 206e           | The n
-00006a30: 616d 6520 6f66 2061 6e6f 7468 6572 2054  ame of another T
-00006a40: 6173 6b20 4772 6f75 7020 7769 7468 696e  ask Group within
-00006a50: 2074 6865 2073 616d 6520 576f 726b 2052   the same Work R
-00006a60: 6571 7569 7265 6d65 6e74 2074 6861 7420  equirement that 
-00006a70: 6d75 7374 2062 6520 7375 6363 6573 7366  must be successf
-00006a80: 756c 6c79 2063 6f6d 706c 6574 6564 2062  ully completed b
-00006a90: 6566 6f72 6520 7468 6520 5461 736b 2047  efore the Task G
-00006aa0: 726f 7570 2069 7320 7374 6172 7465 642e  roup is started.
-00006ab0: 2045 2e67 2e20 6022 7461 736b 5f67 726f   E.g. `"task_gro
-00006ac0: 7570 5f31 2260 2e20 2020 2020 2020 2020  up_1"`.         
-00006ad0: 2020 2020 7c20 2020 2020 207c 2020 2020      |      |    
-00006ae0: 207c 2059 6573 2020 7c20 2020 2020 207c   | Yes  |      |
-00006af0: 0a7c 2060 646f 636b 6572 456e 7669 726f  .| `dockerEnviro
-00006b00: 6e6d 656e 7460 2020 2020 2020 2020 7c20  nment`        | 
-00006b10: 5468 6520 656e 7669 726f 6e6d 656e 7420  The environment 
-00006b20: 746f 2062 6520 7061 7373 6564 2074 6f20  to be passed to 
-00006b30: 6120 446f 636b 6572 2063 6f6e 7461 696e  a Docker contain
-00006b40: 6572 2e20 4f6e 6c79 2075 7365 6420 6279  er. Only used by
-00006b50: 2074 6865 2060 646f 636b 6572 6020 5461   the `docker` Ta
-00006b60: 736b 2054 7970 652e 2045 2e67 2e2c 204a  sk Type. E.g., J
-00006b70: 534f 4e3a 2060 7b22 5641 525f 3122 3a20  SON: `{"VAR_1": 
-00006b80: 2261 6263 227d 602c 2054 4f4d 4c3a 2060  "abc"}`, TOML: `
-00006b90: 7b56 4152 5f31 203d 2022 6162 6322 2c20  {VAR_1 = "abc", 
-00006ba0: 5641 525f 3220 3d20 2264 6566 227d 602e  VAR_2 = "def"}`.
-00006bb0: 2020 2020 2020 2020 207c 2059 6573 2020           | Yes  
-00006bc0: 7c20 5965 7320 7c20 5965 7320 207c 2059  | Yes | Yes  | Y
-00006bd0: 6573 2020 7c0a 7c20 6064 6f63 6b65 7250  es  |.| `dockerP
-00006be0: 6173 7377 6f72 6460 2020 2020 2020 2020  assword`        
-00006bf0: 2020 207c 2054 6865 2070 6173 7377 6f72     | The passwor
-00006c00: 6420 666f 7220 446f 636b 6572 4875 622c  d for DockerHub,
-00006c10: 206f 6e6c 7920 7573 6564 2062 7920 7468   only used by th
-00006c20: 6520 6064 6f63 6b65 7260 2054 6173 6b20  e `docker` Task 
-00006c30: 5479 7065 2e20 452c 672e 2c20 6022 6d79  Type. E,g., `"my
-00006c40: 5f70 6173 7377 6f72 6422 602e 2020 2020  _password"`.    
-00006c50: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006c60: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006c70: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006c80: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006c90: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
-00006ca0: 5965 7320 207c 2059 6573 207c 2059 6573  Yes  | Yes | Yes
-00006cb0: 2020 7c20 5965 7320 207c 0a7c 2060 646f    | Yes  |.| `do
-00006cc0: 636b 6572 5573 6572 6e61 6d65 6020 2020  ckerUsername`   
-00006cd0: 2020 2020 2020 2020 7c20 5468 6520 7573          | The us
-00006ce0: 6572 6e61 6d65 2066 6f72 2044 6f63 6b65  ername for Docke
-00006cf0: 7248 7562 2c20 6f6e 6c79 2075 7365 6420  rHub, only used 
-00006d00: 6279 2074 6865 2060 646f 636b 6572 6020  by the `docker` 
-00006d10: 5461 736b 2054 7970 652e 2045 2c67 2e2c  Task Type. E,g.,
-00006d20: 2060 226d 795f 7573 6572 6e61 6d65 2260   `"my_username"`
-00006d30: 2e20 2020 2020 2020 2020 2020 2020 2020  .               
-00006d40: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006d50: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006d60: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006d70: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006d80: 2020 207c 2059 6573 2020 7c20 5965 7320     | Yes  | Yes 
-00006d90: 7c20 5965 7320 207c 2059 6573 2020 7c0a  | Yes  | Yes  |.
-00006da0: 7c20 6065 6e76 6972 6f6e 6d65 6e74 6020  | `environment` 
-00006db0: 2020 2020 2020 2020 2020 2020 207c 2054               | T
-00006dc0: 6865 2065 6e76 6972 6f6e 6d65 6e74 2076  he environment v
-00006dd0: 6172 6961 626c 6573 2074 6f20 7365 7420  ariables to set 
-00006de0: 666f 7220 6120 5461 736b 2077 6865 6e20  for a Task when 
-00006df0: 6974 2773 2065 7865 6375 7465 642e 2045  it's executed. E
-00006e00: 2e67 2e2c 204a 534f 4e3a 2060 7b22 5641  .g., JSON: `{"VA
-00006e10: 525f 3122 3a20 2261 6263 222c 2022 5641  R_1": "abc", "VA
-00006e20: 525f 3222 3a20 2264 6566 227d 602c 2054  R_2": "def"}`, T
-00006e30: 4f4d 4c3a 2060 7b56 4152 5f31 203d 2022  OML: `{VAR_1 = "
-00006e40: 6162 6322 2c20 5641 525f 3220 3d20 2264  abc", VAR_2 = "d
-00006e50: 6566 227d 602e 2020 2020 2020 2020 2020  ef"}`.          
-00006e60: 2020 2020 2020 2020 7c20 5965 7320 207c          | Yes  |
-00006e70: 2059 6573 207c 2059 6573 2020 7c20 5965   Yes | Yes  | Ye
-00006e80: 7320 207c 0a7c 2060 6578 636c 7573 6976  s  |.| `exclusiv
-00006e90: 6557 6f72 6b65 7273 6020 2020 2020 2020  eWorkers`       
-00006ea0: 2020 7c20 4966 2074 7275 652c 2074 6865    | If true, the
-00006eb0: 6e20 646f 206e 6f74 2061 6c6c 6f77 2063  n do not allow c
-00006ec0: 6c61 696d 6564 2057 6f72 6b65 7273 2074  laimed Workers t
-00006ed0: 6f20 6265 2073 6861 7265 6420 7769 7468  o be shared with
-00006ee0: 206f 7468 6572 2054 6173 6b20 4772 6f75   other Task Grou
-00006ef0: 7073 3b20 6f74 6865 7277 6973 652c 2057  ps; otherwise, W
-00006f00: 6f72 6b65 7273 2063 616e 2062 6520 7368  orkers can be sh
-00006f10: 6172 6564 2e20 4465 6661 756c 743a 6066  ared. Default:`f
-00006f20: 616c 7365 602e 2020 2020 2020 2020 2020  alse`.          
-00006f30: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00006f40: 2020 2020 2020 2020 2020 2020 207c 2059               | Y
-00006f50: 6573 2020 7c20 5965 7320 7c20 5965 7320  es  | Yes | Yes 
-00006f60: 207c 2020 2020 2020 7c0a 7c20 6065 7865   |      |.| `exe
-00006f70: 6375 7461 626c 6560 2020 2020 2020 2020  cutable`        
-00006f80: 2020 2020 2020 207c 2054 6865 2027 6578         | The 'ex
-00006f90: 6563 7574 6162 6c65 2720 746f 2072 756e  ecutable' to run
-00006fa0: 2077 6865 6e20 6120 4261 7368 206f 7220   when a Bash or 
-00006fb0: 446f 636b 6572 2054 6173 6b20 6973 2065  Docker Task is e
-00006fc0: 7865 6375 7465 642e 2042 6173 6820 7363  xecuted. Bash sc
-00006fd0: 7269 7074 2066 6f72 2042 6173 682c 2063  ript for Bash, c
-00006fe0: 6f6e 7461 696e 6572 2069 6d61 6765 2066  ontainer image f
-00006ff0: 6f72 2044 6f63 6b65 722e 204f 7074 696f  or Docker. Optio
-00007000: 6e61 6c3a 206f 6d69 7420 746f 2073 7570  nal: omit to sup
-00007010: 7072 6573 7320 6175 746f 6d61 7469 6320  press automatic 
-00007020: 7072 6f63 6573 7369 6e67 2e20 2020 2020  processing.     
-00007030: 2020 7c20 5965 7320 207c 2059 6573 207c    | Yes  | Yes |
-00007040: 2059 6573 2020 7c20 5965 7320 207c 0a7c   Yes  | Yes  |.|
-00007050: 2060 6669 6e69 7368 4966 416c 6c54 6173   `finishIfAllTas
-00007060: 6b73 4669 6e69 7368 6564 6020 7c20 4966  ksFinished` | If
-00007070: 2074 7275 652c 2074 6865 2054 6173 6b20   true, the Task 
-00007080: 4772 6f75 7020 7769 6c6c 2066 696e 6973  Group will finis
-00007090: 6820 6175 746f 6d61 7469 6361 6c6c 7920  h automatically 
-000070a0: 6966 2061 6c6c 2063 6f6e 7461 696e 6564  if all contained
-000070b0: 2074 6173 6b73 2066 696e 6973 682e 2044   tasks finish. D
-000070c0: 6566 6175 6c74 3a60 7472 7565 602e 2020  efault:`true`.  
-000070d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000070e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000070f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007100: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007110: 2020 2020 2020 207c 2059 6573 2020 7c20         | Yes  | 
-00007120: 5965 7320 7c20 5965 7320 207c 2020 2020  Yes | Yes  |    
-00007130: 2020 7c0a 7c20 6066 696e 6973 6849 6641    |.| `finishIfA
-00007140: 6e79 5461 736b 4661 696c 6564 6020 2020  nyTaskFailed`   
-00007150: 207c 2049 6620 7472 7565 2c20 7468 6520   | If true, the 
-00007160: 5461 736b 2047 726f 7570 2077 696c 6c20  Task Group will 
-00007170: 6265 2066 6169 6c65 6420 6175 746f 6d61  be failed automa
-00007180: 7469 6361 6c6c 7920 6966 2061 6e79 2063  tically if any c
-00007190: 6f6e 7461 696e 6564 2074 6173 6b73 2066  ontained tasks f
-000071a0: 6169 6c2e 2044 6566 6175 6c74 3a60 6661  ail. Default:`fa
-000071b0: 6c73 6560 2e20 2020 2020 2020 2020 2020  lse`.           
-000071c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000071d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000071e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000071f0: 2020 2020 2020 2020 2020 2020 7c20 5965              | Ye
-00007200: 7320 207c 2059 6573 207c 2059 6573 2020  s  | Yes | Yes  
-00007210: 7c20 2020 2020 207c 0a7c 2060 666c 6174  |      |.| `flat
-00007220: 7465 6e49 6e70 7574 5061 7468 7360 2020  tenInputPaths`  
-00007230: 2020 2020 2020 7c20 4465 7465 726d 696e        | Determin
-00007240: 6573 2077 6865 7468 6572 2069 6e70 7574  es whether input
-00007250: 206f 626a 6563 7420 7061 7468 7320 7368   object paths sh
-00007260: 6f75 6c64 2062 6520 666c 6174 7465 6e65  ould be flattene
-00007270: 6420 2869 2e65 2e2c 2064 6972 6563 746f  d (i.e., directo
-00007280: 7279 2073 7472 7563 7475 7265 2072 656d  ry structure rem
-00007290: 6f76 6564 2920 7768 656e 2064 6f77 6e6c  oved) when downl
-000072a0: 6f61 6465 6420 746f 2061 206e 6f64 652e  oaded to a node.
-000072b0: 2044 6566 6175 6c74 3a20 6066 616c 7365   Default: `false
-000072c0: 602e 2020 2020 2020 2020 2020 2020 2020  `.              
-000072d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000072e0: 207c 2059 6573 2020 7c20 5965 7320 7c20   | Yes  | Yes | 
-000072f0: 5965 7320 207c 2059 6573 2020 7c0a 7c20  Yes  | Yes  |.| 
-00007300: 6066 6c61 7474 656e 5570 6c6f 6164 5061  `flattenUploadPa
-00007310: 7468 7360 2020 2020 2020 207c 2049 676e  ths`       | Ign
-00007320: 6f72 6520 6c6f 6361 6c20 6469 7265 6374  ore local direct
-00007330: 6f72 7920 7061 7468 7320 7768 656e 2075  ory paths when u
-00007340: 706c 6f61 6469 6e67 2066 696c 6573 2074  ploading files t
-00007350: 6f20 7468 6520 4f62 6a65 6374 2053 746f  o the Object Sto
-00007360: 7265 3b20 706c 6163 6520 696e 2060 3c6e  re; place in `<n
-00007370: 616d 6573 7061 6365 3e3a 3c77 6f72 6b2d  amespace>:<work-
-00007380: 7265 712d 6e61 6d65 3e2f 602e 2044 6566  req-name>/`. Def
-00007390: 6175 6c74 3a20 6066 616c 7365 602e 2020  ault: `false`.  
-000073a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000073b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000073c0: 2020 2020 2020 7c20 5965 7320 207c 2059        | Yes  | Y
-000073d0: 6573 207c 2020 2020 2020 7c20 2020 2020  es |      |     
-000073e0: 207c 0a7c 2060 6675 6c66 696c 4f6e 5375   |.| `fulfilOnSu
-000073f0: 626d 6974 6020 2020 2020 2020 2020 2020  bmit`           
-00007400: 7c20 496e 6469 6361 7465 7320 6966 2074  | Indicates if t
-00007410: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
-00007420: 656e 7420 7368 6f75 6c64 2062 6520 6675  ent should be fu
-00007430: 6c66 696c 6c65 6420 7768 656e 2069 7420  lfilled when it 
-00007440: 6973 2073 7562 6d69 7474 6564 2c20 7261  is submitted, ra
-00007450: 7468 6572 2074 6861 6e20 6265 696e 6720  ther than being 
-00007460: 616c 6c6f 7765 6420 746f 2077 6169 7420  allowed to wait 
-00007470: 696e 2050 454e 4449 4e47 2073 7461 7475  in PENDING statu
-00007480: 732e 2044 6566 6175 6c74 3a60 6661 6c73  s. Default:`fals
-00007490: 6560 2e20 2020 2020 2020 2020 2020 2020  e`.             
-000074a0: 2020 2020 2020 2020 2020 207c 2059 6573             | Yes
-000074b0: 2020 7c20 5965 7320 7c20 2020 2020 207c    | Yes |      |
-000074c0: 2020 2020 2020 7c0a 7c20 6069 6e70 7574        |.| `input
-000074d0: 7360 2020 2020 2020 2020 2020 2020 2020  s`              
-000074e0: 2020 2020 207c 2054 6865 206c 6973 7420       | The list 
-000074f0: 6f66 2069 6e70 7574 2066 696c 6573 2074  of input files t
-00007500: 6f20 6265 2075 706c 6f61 6465 6420 746f  o be uploaded to
-00007510: 2074 6865 2059 656c 6c6f 7744 6f67 204f   the YellowDog O
-00007520: 626a 6563 7420 5374 6f72 652c 2061 6e64  bject Store, and
-00007530: 2072 6571 7569 7265 6420 6279 2074 6865   required by the
-00007540: 2054 6173 6b20 2869 6d70 6c69 6573 2060   Task (implies `
-00007550: 7665 7269 6679 4174 5374 6172 7460 292e  verifyAtStart`).
-00007560: 2045 2e67 2e20 605b 2261 2e73 6822 2c20   E.g. `["a.sh", 
-00007570: 2262 2e73 6822 5d60 206f 7220 605b 222a  "b.sh"]` or `["*
-00007580: 2e73 6822 5d60 2e20 2020 2020 2020 2020  .sh"]`.         
-00007590: 7c20 5965 7320 207c 2059 6573 207c 2059  | Yes  | Yes | Y
-000075a0: 6573 2020 7c20 5965 7320 207c 0a7c 2060  es  | Yes  |.| `
-000075b0: 696e 7075 7473 4f70 7469 6f6e 616c 6020  inputsOptional` 
-000075c0: 2020 2020 2020 2020 2020 7c20 4120 6c69            | A li
-000075d0: 7374 206f 6620 696e 7075 7420 6669 6c65  st of input file
-000075e0: 7320 7265 7175 6972 6564 2062 7920 6120  s required by a 
-000075f0: 5461 736b 2c20 6275 7420 7768 6963 6820  Task, but which 
-00007600: 6172 6520 6e6f 7420 7375 626a 6563 7420  are not subject 
-00007610: 746f 2076 6572 6966 6963 6174 696f 6e2e  to verification.
-00007620: 2043 616e 2063 6f6e 7461 696e 2077 696c   Can contain wil
-00007630: 6463 6172 6473 2e20 452e 672e 3a20 605b  dcards. E.g.: `[
-00007640: 2274 6173 6b5f 6772 6f75 705f 312f 2a2a  "task_group_1/**
-00007650: 2f72 6573 756c 7473 2e74 7874 225d 602e  /results.txt"]`.
-00007660: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007670: 2020 2020 207c 2059 6573 2020 7c20 5965       | Yes  | Ye
-00007680: 7320 7c20 5965 7320 207c 2059 6573 2020  s | Yes  | Yes  
-00007690: 7c0a 7c20 6069 6e73 7461 6e63 6554 7970  |.| `instanceTyp
-000076a0: 6573 6020 2020 2020 2020 2020 2020 207c  es`            |
-000076b0: 2054 6865 206d 6163 6869 6e65 2069 6e73   The machine ins
-000076c0: 7461 6e63 6520 7479 7065 7320 7468 6174  tance types that
-000076d0: 2063 616e 2062 6520 7573 6564 2074 6f20   can be used to 
-000076e0: 6578 6563 7574 6520 5461 736b 732e 2045  execute Tasks. E
-000076f0: 2e67 2e2c 2060 5b22 7433 2e6d 6963 726f  .g., `["t3.micro
-00007700: 222c 2022 7433 612e 6d69 6372 6f22 5d60  ", "t3a.micro"]`
-00007710: 2e20 2020 2020 2020 2020 2020 2020 2020  .               
-00007720: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007730: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007740: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007750: 2020 2020 2020 2020 2020 7c20 5965 7320            | Yes 
-00007760: 207c 2059 6573 207c 2059 6573 2020 7c20   | Yes | Yes  | 
-00007770: 2020 2020 207c 0a7c 2060 6d61 7869 6d75       |.| `maximu
-00007780: 6d54 6173 6b52 6574 7269 6573 6020 2020  mTaskRetries`   
-00007790: 2020 2020 7c20 5468 6520 6d61 7869 6d75      | The maximu
-000077a0: 6d20 6e75 6d62 6572 206f 6620 7469 6d65  m number of time
-000077b0: 7320 6120 5461 736b 2063 616e 2062 6520  s a Task can be 
-000077c0: 7265 7472 6965 6420 6166 7465 7220 6974  retried after it
-000077d0: 2068 6173 2066 6169 6c65 642e 2045 2e67   has failed. E.g
-000077e0: 2e3a 2060 3560 2e20 2020 2020 2020 2020  .: `5`.         
-000077f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007800: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007810: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007820: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007830: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00007840: 2059 6573 2020 7c20 5965 7320 7c20 5965   Yes  | Yes | Ye
-00007850: 7320 207c 2020 2020 2020 7c0a 7c20 606d  s  |      |.| `m
-00007860: 6178 576f 726b 6572 7360 2020 2020 2020  axWorkers`      
-00007870: 2020 2020 2020 2020 207c 2054 6865 206d           | The m
-00007880: 6178 696d 756d 206e 756d 6265 7220 6f66  aximum number of
-00007890: 2057 6f72 6b65 7273 2074 6861 7420 6361   Workers that ca
-000078a0: 6e20 6265 2063 6c61 696d 6564 2066 6f72  n be claimed for
-000078b0: 2074 6865 2061 7373 6f63 6961 7465 6420   the associated 
-000078c0: 5461 736b 2047 726f 7570 2e20 452e 672e  Task Group. E.g.
-000078d0: 2c20 6031 3060 2e20 2020 2020 2020 2020  , `10`.         
-000078e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000078f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007900: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007910: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007920: 2020 2020 7c20 5965 7320 207c 2059 6573      | Yes  | Yes
-00007930: 207c 2059 6573 2020 7c20 2020 2020 207c   | Yes  |      |
-00007940: 0a7c 2060 6d69 6e57 6f72 6b65 7273 6020  .| `minWorkers` 
-00007950: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
-00007960: 5468 6520 6d69 6e69 6d75 6d20 6e75 6d62  The minimum numb
-00007970: 6572 206f 6620 576f 726b 6572 7320 7468  er of Workers th
-00007980: 6174 2074 6865 2061 7373 6f63 6961 7465  at the associate
-00007990: 6420 5461 736b 2047 726f 7570 2072 6571  d Task Group req
-000079a0: 7569 7265 732e 2054 6869 7320 6d61 6e79  uires. This many
-000079b0: 2077 6f72 6b65 7273 206d 7573 7420 6265   workers must be
-000079c0: 2063 6c61 696d 6564 2062 6566 6f72 6520   claimed before 
-000079d0: 7468 6520 6173 736f 6369 6174 6564 2054  the associated T
-000079e0: 6173 6b20 4772 6f75 7020 7769 6c6c 2073  ask Group will s
-000079f0: 7461 7274 2077 6f72 6b69 6e67 2e20 452e  tart working. E.
-00007a00: 672e 2c20 6031 602e 207c 2059 6573 2020  g., `1`. | Yes  
-00007a10: 7c20 5965 7320 7c20 5965 7320 207c 2020  | Yes | Yes  |  
-00007a20: 2020 2020 7c0a 7c20 606e 616d 6560 2020      |.| `name`  
-00007a30: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007a40: 2020 207c 2054 6865 206e 616d 6520 6f66     | The name of
-00007a50: 2074 6865 2057 6f72 6b20 5265 7175 6972   the Work Requir
-00007a60: 656d 656e 742c 2054 6173 6b20 4772 6f75  ement, Task Grou
-00007a70: 7020 6f72 2054 6173 6b2e 2045 2e67 2e2c  p or Task. E.g.,
-00007a80: 2060 2277 725f 6e61 6d65 2260 2e20 4e6f   `"wr_name"`. No
-00007a90: 7465 2074 6861 7420 7468 6520 606e 616d  te that the `nam
-00007aa0: 6560 2070 726f 7065 7274 7920 6973 206e  e` property is n
-00007ab0: 6f74 2069 6e68 6572 6974 6564 2e20 2020  ot inherited.   
-00007ac0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007ad0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007ae0: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
-00007af0: 5965 7320 207c 2059 6573 207c 2059 6573  Yes  | Yes | Yes
-00007b00: 2020 7c20 5965 7320 207c 0a7c 2060 6f75    | Yes  |.| `ou
-00007b10: 7470 7574 7360 2020 2020 2020 2020 2020  tputs`          
-00007b20: 2020 2020 2020 2020 7c20 5468 6520 6669          | The fi
-00007b30: 6c65 7320 746f 2062 6520 7570 6c6f 6164  les to be upload
-00007b40: 6564 2074 6f20 7468 6520 5965 6c6c 6f77  ed to the Yellow
-00007b50: 446f 6720 4f62 6a65 6374 2053 746f 7265  Dog Object Store
-00007b60: 2062 7920 6120 576f 726b 6572 206e 6f64   by a Worker nod
-00007b70: 6520 6f6e 2063 6f6d 706c 6574 696f 6e20  e on completion 
-00007b80: 6f66 2074 6865 2054 6173 6b2e 2045 2e67  of the Task. E.g
-00007b90: 2e2c 2060 5b22 7265 7375 6c74 735f 312e  ., `["results_1.
-00007ba0: 7478 7422 2c20 2272 6573 756c 7473 5f32  txt", "results_2
-00007bb0: 2e74 7874 225d 602e 2020 2020 2020 2020  .txt"]`.        
-00007bc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007bd0: 2020 207c 2059 6573 2020 7c20 5965 7320     | Yes  | Yes 
-00007be0: 7c20 5965 7320 207c 2059 6573 2020 7c0a  | Yes  | Yes  |.
-00007bf0: 7c20 606f 7574 7075 7473 5265 7175 6972  | `outputsRequir
-00007c00: 6564 6020 2020 2020 2020 2020 207c 2054  ed`          | T
-00007c10: 6865 2066 696c 6573 2074 6861 7420 2a6d  he files that *m
-00007c20: 7573 742a 2062 6520 7570 6c6f 6164 6564  ust* be uploaded
-00007c30: 2074 6f20 7468 6520 5965 6c6c 6f77 446f   to the YellowDo
-00007c40: 6720 4f62 6a65 6374 2053 746f 7265 2062  g Object Store b
-00007c50: 7920 6120 576f 726b 6572 206e 6f64 6520  y a Worker node 
-00007c60: 6f6e 2063 6f6d 706c 6574 696f 6e20 6f66  on completion of
-00007c70: 2074 6865 2054 6173 6b2e 2054 6865 2054   the Task. The T
-00007c80: 6173 6b20 7769 6c6c 2066 6169 6c20 6966  ask will fail if
-00007c90: 2061 6e79 206f 7574 7075 7473 2061 7265   any outputs are
-00007ca0: 2075 6e61 7661 696c 6162 6c65 2e20 2020   unavailable.   
-00007cb0: 2020 2020 2020 2020 7c20 5965 7320 207c          | Yes  |
-00007cc0: 2059 6573 207c 2059 6573 2020 7c20 5965   Yes | Yes  | Ye
-00007cd0: 7320 207c 0a7c 2060 7072 696f 7269 7479  s  |.| `priority
-00007ce0: 6020 2020 2020 2020 2020 2020 2020 2020  `               
-00007cf0: 2020 7c20 5468 6520 7072 696f 7269 7479    | The priority
-00007d00: 206f 6620 576f 726b 2052 6571 7569 7265   of Work Require
-00007d10: 6d65 6e74 7320 616e 6420 5461 736b 2047  ments and Task G
-00007d20: 726f 7570 732e 2048 6967 6865 7220 7072  roups. Higher pr
-00007d30: 696f 7269 7479 2061 6371 7569 7265 7320  iority acquires 
-00007d40: 576f 726b 6572 7320 6168 6561 6420 6f66  Workers ahead of
-00007d50: 206c 6f77 6572 2070 7269 6f72 6974 792e   lower priority.
-00007d60: 2045 2e67 2e2c 2060 302e 3060 2e20 2020   E.g., `0.0`.   
-00007d70: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007d80: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007d90: 2020 2020 2020 2020 2020 2020 207c 2059               | Y
-00007da0: 6573 2020 7c20 5965 7320 7c20 5965 7320  es  | Yes | Yes 
-00007db0: 207c 2020 2020 2020 7c0a 7c20 6070 726f   |      |.| `pro
-00007dc0: 7669 6465 7273 6020 2020 2020 2020 2020  viders`         
-00007dd0: 2020 2020 2020 207c 2043 6f6e 7374 7261         | Constra
-00007de0: 696e 7320 7468 6520 5965 6c6c 6f77 446f  ins the YellowDo
-00007df0: 6720 5363 6865 6475 6c65 7220 6f6e 6c79  g Scheduler only
-00007e00: 2074 6f20 6578 6563 7574 6520 7461 736b   to execute task
-00007e10: 7320 6672 6f6d 2074 6865 2061 7373 6f63  s from the assoc
-00007e20: 6961 7465 6420 5461 736b 2047 726f 7570  iated Task Group
-00007e30: 206f 6e20 7468 6520 7370 6563 6966 6965   on the specifie
-00007e40: 6420 7072 6f76 6964 6572 732e 2045 2e67  d providers. E.g
-00007e50: 2e2c 2060 5b22 4157 5322 2c20 2247 4f4f  ., `["AWS", "GOO
-00007e60: 474c 4522 5d60 2e20 2020 2020 2020 2020  GLE"]`.         
-00007e70: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007e80: 2020 7c20 5965 7320 207c 2059 6573 207c    | Yes  | Yes |
-00007e90: 2059 6573 2020 7c20 2020 2020 207c 0a7c   Yes  |      |.|
-00007ea0: 2060 7261 6d60 2020 2020 2020 2020 2020   `ram`          
-00007eb0: 2020 2020 2020 2020 2020 2020 7c20 5261              | Ra
-00007ec0: 6e67 6520 636f 6e73 7472 6169 6e74 206f  nge constraint o
-00007ed0: 6e20 4742 206f 6620 5241 4d20 7468 6174  n GB of RAM that
-00007ee0: 2061 7265 2072 6571 7569 7265 6420 746f   are required to
-00007ef0: 2065 7865 6375 7465 2054 6173 6b73 2e20   execute Tasks. 
-00007f00: 452e 672e 2c20 605b 322e 352c 2034 2e30  E.g., `[2.5, 4.0
-00007f10: 5d60 2e20 2020 2020 2020 2020 2020 2020  ]`.             
-00007f20: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007f30: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007f40: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007f50: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007f60: 2020 2020 2020 207c 2059 6573 2020 7c20         | Yes  | 
-00007f70: 5965 7320 7c20 5965 7320 207c 2020 2020  Yes | Yes  |    
-00007f80: 2020 7c0a 7c20 6072 6567 696f 6e73 6020    |.| `regions` 
+00006570: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00006580: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00006590: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000065a0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000065b0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000065c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c 3a2d  -------------|:-
+000065d0: 2d2d 2d2d 7c3a 2d2d 2d2d 7c3a 2d2d 2d2d  ----|:----|:----
+000065e0: 2d7c 3a2d 2d2d 2d2d 7c0a 7c20 6061 7267  -|:-----|.| `arg
+000065f0: 756d 656e 7473 6020 2020 2020 2020 2020  uments`         
+00006600: 2020 2020 2020 207c 2054 6865 206c 6973         | The lis
+00006610: 7420 6f66 2061 7267 756d 656e 7473 2074  t of arguments t
+00006620: 6f20 6265 2070 6173 7365 6420 746f 2074  o be passed to t
+00006630: 6865 2054 6173 6b20 7768 656e 2069 7420  he Task when it 
+00006640: 6973 2065 7865 6375 7465 642e 2045 2e67  is executed. E.g
+00006650: 2e3a 2060 5b31 2c20 2254 776f 225d 602e  .: `[1, "Two"]`.
+00006660: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006670: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006680: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006690: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000066a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000066b0: 2020 7c20 5965 7320 207c 2059 6573 207c    | Yes  | Yes |
+000066c0: 2059 6573 2020 7c20 5965 7320 207c 0a7c   Yes  | Yes  |.|
+000066d0: 2060 6361 7074 7572 6554 6173 6b4f 7574   `captureTaskOut
+000066e0: 7075 7460 2020 2020 2020 2020 7c20 5768  put`        | Wh
+000066f0: 6574 6865 7220 7468 6520 636f 6e73 6f6c  ether the consol
+00006700: 6520 6f75 7470 7574 206f 6620 6120 5461  e output of a Ta
+00006710: 736b 2773 2070 726f 6365 7373 2073 686f  sk's process sho
+00006720: 756c 6420 6265 2075 706c 6f61 6465 6420  uld be uploaded 
+00006730: 746f 2074 6865 2059 656c 6c6f 7744 6f67  to the YellowDog
+00006740: 204f 626a 6563 7420 5374 6f72 6520 6f6e   Object Store on
+00006750: 2054 6173 6b20 636f 6d70 6c65 7469 6f6e   Task completion
+00006760: 2e20 4465 6661 756c 743a 2060 7472 7565  . Default: `true
+00006770: 602e 2020 2020 2020 2020 2020 2020 2020  `.              
+00006780: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006790: 2020 2020 2020 207c 2059 6573 2020 7c20         | Yes  | 
+000067a0: 5965 7320 7c20 5965 7320 207c 2059 6573  Yes | Yes  | Yes
+000067b0: 2020 7c0a 7c20 6063 6f6d 706c 6574 6564    |.| `completed
+000067c0: 5461 736b 5474 6c60 2020 2020 2020 2020  TaskTtl`        
+000067d0: 207c 2054 6865 2074 696d 6520 2869 6e20   | The time (in 
+000067e0: 6d69 6e75 7465 7329 2074 6f20 6c69 7665  minutes) to live
+000067f0: 2066 6f72 2063 6f6d 706c 6574 6564 2054   for completed T
+00006800: 6173 6b73 2e20 4966 2073 6574 2c20 5461  asks. If set, Ta
+00006810: 736b 7320 7468 6174 2068 6176 6520 6265  sks that have be
+00006820: 656e 2063 6f6d 706c 6574 6564 2066 6f72  en completed for
+00006830: 206c 6f6e 6765 7220 7468 616e 2074 6869   longer than thi
+00006840: 7320 7065 7269 6f64 2077 696c 6c20 6265  s period will be
+00006850: 2064 656c 6574 6564 2e20 452e 672e 3a20   deleted. E.g.: 
+00006860: 6031 302e 3060 2e20 2020 2020 2020 2020  `10.0`.         
+00006870: 2020 2020 2020 2020 2020 2020 7c20 5965              | Ye
+00006880: 7320 207c 2059 6573 207c 2059 6573 2020  s  | Yes | Yes  
+00006890: 7c20 2020 2020 207c 0a7c 2060 6373 7646  |      |.| `csvF
+000068a0: 696c 6560 2020 2020 2020 2020 2020 2020  ile`            
+000068b0: 2020 2020 2020 7c20 5468 6520 6e61 6d65        | The name
+000068c0: 206f 6620 7468 6520 4353 5620 6669 6c65   of the CSV file
+000068d0: 2075 7365 6420 746f 2064 6572 6976 6520   used to derive 
+000068e0: 5461 736b 2064 6174 612e 2041 6e20 616c  Task data. An al
+000068f0: 7465 726e 6174 6976 6520 746f 2060 6373  ternative to `cs
+00006900: 7646 696c 6573 6020 7468 6174 2063 616e  vFiles` that can
+00006910: 2062 6520 7573 6564 2077 6865 6e20 7468   be used when th
+00006920: 6572 6527 7320 6f6e 6c79 2061 2073 696e  ere's only a sin
+00006930: 676c 6520 4353 5620 6669 6c65 2e20 452e  gle CSV file. E.
+00006940: 672e 2060 2266 696c 652e 6373 7622 602e  g. `"file.csv"`.
+00006950: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006960: 207c 2059 6573 2020 7c20 2020 2020 7c20   | Yes  |     | 
+00006970: 2020 2020 207c 2020 2020 2020 7c0a 7c20       |      |.| 
+00006980: 6063 7376 4669 6c65 7360 2020 2020 2020  `csvFiles`      
+00006990: 2020 2020 2020 2020 2020 207c 2041 206c             | A l
+000069a0: 6973 7420 6f66 2043 5356 2066 696c 6573  ist of CSV files
+000069b0: 2075 7365 6420 746f 2064 6572 6976 6520   used to derive 
+000069c0: 5461 736b 2064 6174 612e 2045 2e67 2e20  Task data. E.g. 
+000069d0: 605b 2266 696c 652e 6373 7622 2c20 2266  `["file.csv", "f
+000069e0: 696c 655f 322e 6373 763a 325d 602e 2020  ile_2.csv:2]`.  
+000069f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006a00: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006a10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006a20: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006a30: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006a40: 2020 2020 2020 7c20 5965 7320 207c 2020        | Yes  |  
+00006a50: 2020 207c 2020 2020 2020 7c20 2020 2020     |      |     
+00006a60: 207c 0a7c 2060 6465 7065 6e64 656e 744f   |.| `dependentO
+00006a70: 6e60 2020 2020 2020 2020 2020 2020 2020  n`              
+00006a80: 7c20 5468 6520 6e61 6d65 206f 6620 616e  | The name of an
+00006a90: 6f74 6865 7220 5461 736b 2047 726f 7570  other Task Group
+00006aa0: 2077 6974 6869 6e20 7468 6520 7361 6d65   within the same
+00006ab0: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+00006ac0: 7420 7468 6174 206d 7573 7420 6265 2073  t that must be s
+00006ad0: 7563 6365 7373 6675 6c6c 7920 636f 6d70  uccessfully comp
+00006ae0: 6c65 7465 6420 6265 666f 7265 2074 6865  leted before the
+00006af0: 2054 6173 6b20 4772 6f75 7020 6973 2073   Task Group is s
+00006b00: 7461 7274 6564 2e20 452e 672e 2060 2274  tarted. E.g. `"t
+00006b10: 6173 6b5f 6772 6f75 705f 3122 602e 2020  ask_group_1"`.  
+00006b20: 2020 2020 2020 2020 2020 207c 2020 2020             |    
+00006b30: 2020 7c20 2020 2020 7c20 5965 7320 207c    |     | Yes  |
+00006b40: 2020 2020 2020 7c0a 7c20 6064 6f63 6b65        |.| `docke
+00006b50: 7245 6e76 6972 6f6e 6d65 6e74 6020 2020  rEnvironment`   
+00006b60: 2020 2020 207c 2054 6865 2065 6e76 6972       | The envir
+00006b70: 6f6e 6d65 6e74 2074 6f20 6265 2070 6173  onment to be pas
+00006b80: 7365 6420 746f 2061 2044 6f63 6b65 7220  sed to a Docker 
+00006b90: 636f 6e74 6169 6e65 722e 204f 6e6c 7920  container. Only 
+00006ba0: 7573 6564 2062 7920 7468 6520 6064 6f63  used by the `doc
+00006bb0: 6b65 7260 2054 6173 6b20 5479 7065 2e20  ker` Task Type. 
+00006bc0: 452e 672e 2c20 4a53 4f4e 3a20 607b 2256  E.g., JSON: `{"V
+00006bd0: 4152 5f31 223a 2022 6162 6322 7d60 2c20  AR_1": "abc"}`, 
+00006be0: 544f 4d4c 3a20 607b 5641 525f 3120 3d20  TOML: `{VAR_1 = 
+00006bf0: 2261 6263 222c 2056 4152 5f32 203d 2022  "abc", VAR_2 = "
+00006c00: 6465 6622 7d60 2e20 2020 2020 2020 2020  def"}`.         
+00006c10: 7c20 5965 7320 207c 2059 6573 207c 2059  | Yes  | Yes | Y
+00006c20: 6573 2020 7c20 5965 7320 207c 0a7c 2060  es  | Yes  |.| `
+00006c30: 646f 636b 6572 5061 7373 776f 7264 6020  dockerPassword` 
+00006c40: 2020 2020 2020 2020 2020 7c20 5468 6520            | The 
+00006c50: 7061 7373 776f 7264 2066 6f72 2044 6f63  password for Doc
+00006c60: 6b65 7248 7562 2c20 6f6e 6c79 2075 7365  kerHub, only use
+00006c70: 6420 6279 2074 6865 2060 646f 636b 6572  d by the `docker
+00006c80: 6020 5461 736b 2054 7970 652e 2045 2c67  ` Task Type. E,g
+00006c90: 2e2c 2060 226d 795f 7061 7373 776f 7264  ., `"my_password
+00006ca0: 2260 2e20 2020 2020 2020 2020 2020 2020  "`.             
+00006cb0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006cc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006cd0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006ce0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006cf0: 2020 2020 207c 2059 6573 2020 7c20 5965       | Yes  | Ye
+00006d00: 7320 7c20 5965 7320 207c 2059 6573 2020  s | Yes  | Yes  
+00006d10: 7c0a 7c20 6064 6f63 6b65 7255 7365 726e  |.| `dockerUsern
+00006d20: 616d 6560 2020 2020 2020 2020 2020 207c  ame`           |
+00006d30: 2054 6865 2075 7365 726e 616d 6520 666f   The username fo
+00006d40: 7220 446f 636b 6572 4875 622c 206f 6e6c  r DockerHub, onl
+00006d50: 7920 7573 6564 2062 7920 7468 6520 6064  y used by the `d
+00006d60: 6f63 6b65 7260 2054 6173 6b20 5479 7065  ocker` Task Type
+00006d70: 2e20 452c 672e 2c20 6022 6d79 5f75 7365  . E,g., `"my_use
+00006d80: 726e 616d 6522 602e 2020 2020 2020 2020  rname"`.        
+00006d90: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006da0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006db0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006dc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006dd0: 2020 2020 2020 2020 2020 7c20 5965 7320            | Yes 
+00006de0: 207c 2059 6573 207c 2059 6573 2020 7c20   | Yes | Yes  | 
+00006df0: 5965 7320 207c 0a7c 2060 656e 7669 726f  Yes  |.| `enviro
+00006e00: 6e6d 656e 7460 2020 2020 2020 2020 2020  nment`          
+00006e10: 2020 2020 7c20 5468 6520 656e 7669 726f      | The enviro
+00006e20: 6e6d 656e 7420 7661 7269 6162 6c65 7320  nment variables 
+00006e30: 746f 2073 6574 2066 6f72 2061 2054 6173  to set for a Tas
+00006e40: 6b20 7768 656e 2069 7427 7320 6578 6563  k when it's exec
+00006e50: 7574 6564 2e20 452e 672e 2c20 4a53 4f4e  uted. E.g., JSON
+00006e60: 3a20 607b 2256 4152 5f31 223a 2022 6162  : `{"VAR_1": "ab
+00006e70: 6322 2c20 2256 4152 5f32 223a 2022 6465  c", "VAR_2": "de
+00006e80: 6622 7d60 2c20 544f 4d4c 3a20 607b 5641  f"}`, TOML: `{VA
+00006e90: 525f 3120 3d20 2261 6263 222c 2056 4152  R_1 = "abc", VAR
+00006ea0: 5f32 203d 2022 6465 6622 7d60 2e20 2020  _2 = "def"}`.   
+00006eb0: 2020 2020 2020 2020 2020 2020 2020 207c                 |
+00006ec0: 2059 6573 2020 7c20 5965 7320 7c20 5965   Yes  | Yes | Ye
+00006ed0: 7320 207c 2059 6573 2020 7c0a 7c20 6065  s  | Yes  |.| `e
+00006ee0: 7863 6c75 7369 7665 576f 726b 6572 7360  xclusiveWorkers`
+00006ef0: 2020 2020 2020 2020 207c 2049 6620 7472           | If tr
+00006f00: 7565 2c20 7468 656e 2064 6f20 6e6f 7420  ue, then do not 
+00006f10: 616c 6c6f 7720 636c 6169 6d65 6420 576f  allow claimed Wo
+00006f20: 726b 6572 7320 746f 2062 6520 7368 6172  rkers to be shar
+00006f30: 6564 2077 6974 6820 6f74 6865 7220 5461  ed with other Ta
+00006f40: 736b 2047 726f 7570 733b 206f 7468 6572  sk Groups; other
+00006f50: 7769 7365 2c20 576f 726b 6572 7320 6361  wise, Workers ca
+00006f60: 6e20 6265 2073 6861 7265 642e 2044 6566  n be shared. Def
+00006f70: 6175 6c74 3a60 6661 6c73 6560 2e20 2020  ault:`false`.   
+00006f80: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006f90: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00006fa0: 2020 2020 7c20 5965 7320 207c 2059 6573      | Yes  | Yes
+00006fb0: 207c 2059 6573 2020 7c20 2020 2020 207c   | Yes  |      |
+00006fc0: 0a7c 2060 6578 6563 7574 6162 6c65 6020  .| `executable` 
+00006fd0: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00006fe0: 5468 6520 2765 7865 6375 7461 626c 6527  The 'executable'
+00006ff0: 2074 6f20 7275 6e20 7768 656e 2061 2042   to run when a B
+00007000: 6173 6820 6f72 2044 6f63 6b65 7220 5461  ash or Docker Ta
+00007010: 736b 2069 7320 6578 6563 7574 6564 2e20  sk is executed. 
+00007020: 4261 7368 2073 6372 6970 7420 666f 7220  Bash script for 
+00007030: 4261 7368 2c20 636f 6e74 6169 6e65 7220  Bash, container 
+00007040: 696d 6167 6520 666f 7220 446f 636b 6572  image for Docker
+00007050: 2e20 4f70 7469 6f6e 616c 3a20 6f6d 6974  . Optional: omit
+00007060: 2074 6f20 7375 7070 7265 7373 2061 7574   to suppress aut
+00007070: 6f6d 6174 6963 2070 726f 6365 7373 696e  omatic processin
+00007080: 672e 2020 2020 2020 207c 2059 6573 2020  g.       | Yes  
+00007090: 7c20 5965 7320 7c20 5965 7320 207c 2059  | Yes | Yes  | Y
+000070a0: 6573 2020 7c0a 7c20 6066 696e 6973 6849  es  |.| `finishI
+000070b0: 6641 6c6c 5461 736b 7346 696e 6973 6865  fAllTasksFinishe
+000070c0: 6460 207c 2049 6620 7472 7565 2c20 7468  d` | If true, th
+000070d0: 6520 5461 736b 2047 726f 7570 2077 696c  e Task Group wil
+000070e0: 6c20 6669 6e69 7368 2061 7574 6f6d 6174  l finish automat
+000070f0: 6963 616c 6c79 2069 6620 616c 6c20 636f  ically if all co
+00007100: 6e74 6169 6e65 6420 7461 736b 7320 6669  ntained tasks fi
+00007110: 6e69 7368 2e20 4465 6661 756c 743a 6074  nish. Default:`t
+00007120: 7275 6560 2e20 2020 2020 2020 2020 2020  rue`.           
+00007130: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007140: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007150: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007160: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00007170: 5965 7320 207c 2059 6573 207c 2059 6573  Yes  | Yes | Yes
+00007180: 2020 7c20 2020 2020 207c 0a7c 2060 6669    |      |.| `fi
+00007190: 6e69 7368 4966 416e 7954 6173 6b46 6169  nishIfAnyTaskFai
+000071a0: 6c65 6460 2020 2020 7c20 4966 2074 7275  led`    | If tru
+000071b0: 652c 2074 6865 2054 6173 6b20 4772 6f75  e, the Task Grou
+000071c0: 7020 7769 6c6c 2062 6520 6661 696c 6564  p will be failed
+000071d0: 2061 7574 6f6d 6174 6963 616c 6c79 2069   automatically i
+000071e0: 6620 616e 7920 636f 6e74 6169 6e65 6420  f any contained 
+000071f0: 7461 736b 7320 6661 696c 2e20 4465 6661  tasks fail. Defa
+00007200: 756c 743a 6066 616c 7365 602e 2020 2020  ult:`false`.    
+00007210: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007220: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007230: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007240: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007250: 2020 207c 2059 6573 2020 7c20 5965 7320     | Yes  | Yes 
+00007260: 7c20 5965 7320 207c 2020 2020 2020 7c0a  | Yes  |      |.
+00007270: 7c20 6066 6c61 7474 656e 496e 7075 7450  | `flattenInputP
+00007280: 6174 6873 6020 2020 2020 2020 207c 2044  aths`        | D
+00007290: 6574 6572 6d69 6e65 7320 7768 6574 6865  etermines whethe
+000072a0: 7220 696e 7075 7420 6f62 6a65 6374 2070  r input object p
+000072b0: 6174 6873 2073 686f 756c 6420 6265 2066  aths should be f
+000072c0: 6c61 7474 656e 6564 2028 692e 652e 2c20  lattened (i.e., 
+000072d0: 6469 7265 6374 6f72 7920 7374 7275 6374  directory struct
+000072e0: 7572 6520 7265 6d6f 7665 6429 2077 6865  ure removed) whe
+000072f0: 6e20 646f 776e 6c6f 6164 6564 2074 6f20  n downloaded to 
+00007300: 6120 6e6f 6465 2e20 4465 6661 756c 743a  a node. Default:
+00007310: 2060 6661 6c73 6560 2e20 2020 2020 2020   `false`.       
+00007320: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007330: 2020 2020 2020 2020 7c20 5965 7320 207c          | Yes  |
+00007340: 2059 6573 207c 2059 6573 2020 7c20 5965   Yes | Yes  | Ye
+00007350: 7320 207c 0a7c 2060 666c 6174 7465 6e55  s  |.| `flattenU
+00007360: 706c 6f61 6450 6174 6873 6020 2020 2020  ploadPaths`     
+00007370: 2020 7c20 4967 6e6f 7265 206c 6f63 616c    | Ignore local
+00007380: 2064 6972 6563 746f 7279 2070 6174 6873   directory paths
+00007390: 2077 6865 6e20 7570 6c6f 6164 696e 6720   when uploading 
+000073a0: 6669 6c65 7320 746f 2074 6865 204f 626a  files to the Obj
+000073b0: 6563 7420 5374 6f72 653b 2070 6c61 6365  ect Store; place
+000073c0: 2069 6e20 603c 6e61 6d65 7370 6163 653e   in `<namespace>
+000073d0: 3a3c 776f 726b 2d72 6571 2d6e 616d 653e  :<work-req-name>
+000073e0: 2f60 2e20 4465 6661 756c 743a 2060 6661  /`. Default: `fa
+000073f0: 6c73 6560 2e20 2020 2020 2020 2020 2020  lse`.           
+00007400: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007410: 2020 2020 2020 2020 2020 2020 207c 2059               | Y
+00007420: 6573 2020 7c20 5965 7320 7c20 2020 2020  es  | Yes |     
+00007430: 207c 2020 2020 2020 7c0a 7c20 6066 756c   |      |.| `ful
+00007440: 6669 6c4f 6e53 7562 6d69 7460 2020 2020  filOnSubmit`    
+00007450: 2020 2020 2020 207c 2049 6e64 6963 6174         | Indicat
+00007460: 6573 2069 6620 7468 6520 576f 726b 2052  es if the Work R
+00007470: 6571 7569 7265 6d65 6e74 2073 686f 756c  equirement shoul
+00007480: 6420 6265 2066 756c 6669 6c6c 6564 2077  d be fulfilled w
+00007490: 6865 6e20 6974 2069 7320 7375 626d 6974  hen it is submit
+000074a0: 7465 642c 2072 6174 6865 7220 7468 616e  ted, rather than
+000074b0: 2062 6569 6e67 2061 6c6c 6f77 6564 2074   being allowed t
+000074c0: 6f20 7761 6974 2069 6e20 5045 4e44 494e  o wait in PENDIN
+000074d0: 4720 7374 6174 7573 2e20 4465 6661 756c  G status. Defaul
+000074e0: 743a 6066 616c 7365 602e 2020 2020 2020  t:`false`.      
+000074f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007500: 2020 7c20 5965 7320 207c 2059 6573 207c    | Yes  | Yes |
+00007510: 2020 2020 2020 7c20 2020 2020 207c 0a7c        |      |.|
+00007520: 2060 696e 7075 7473 6020 2020 2020 2020   `inputs`       
+00007530: 2020 2020 2020 2020 2020 2020 7c20 5468              | Th
+00007540: 6520 6c69 7374 206f 6620 696e 7075 7420  e list of input 
+00007550: 6669 6c65 7320 746f 2062 6520 7570 6c6f  files to be uplo
+00007560: 6164 6564 2074 6f20 7468 6520 5965 6c6c  aded to the Yell
+00007570: 6f77 446f 6720 4f62 6a65 6374 2053 746f  owDog Object Sto
+00007580: 7265 2c20 616e 6420 7265 7175 6972 6564  re, and required
+00007590: 2062 7920 7468 6520 5461 736b 2028 696d   by the Task (im
+000075a0: 706c 6965 7320 6076 6572 6966 7941 7453  plies `verifyAtS
+000075b0: 7461 7274 6029 2e20 452e 672e 2060 5b22  tart`). E.g. `["
+000075c0: 612e 7368 222c 2022 622e 7368 225d 6020  a.sh", "b.sh"]` 
+000075d0: 6f72 2060 5b22 2a2e 7368 225d 602e 2020  or `["*.sh"]`.  
+000075e0: 2020 2020 2020 207c 2059 6573 2020 7c20         | Yes  | 
+000075f0: 5965 7320 7c20 5965 7320 207c 2059 6573  Yes | Yes  | Yes
+00007600: 2020 7c0a 7c20 6069 6e70 7574 734f 7074    |.| `inputsOpt
+00007610: 696f 6e61 6c60 2020 2020 2020 2020 2020  ional`          
+00007620: 207c 2041 206c 6973 7420 6f66 2069 6e70   | A list of inp
+00007630: 7574 2066 696c 6573 2072 6571 7569 7265  ut files require
+00007640: 6420 6279 2061 2054 6173 6b2c 2062 7574  d by a Task, but
+00007650: 2077 6869 6368 2061 7265 206e 6f74 2073   which are not s
+00007660: 7562 6a65 6374 2074 6f20 7665 7269 6669  ubject to verifi
+00007670: 6361 7469 6f6e 2e20 4361 6e20 636f 6e74  cation. Can cont
+00007680: 6169 6e20 7769 6c64 6361 7264 732e 2045  ain wildcards. E
+00007690: 2e67 2e3a 2060 5b22 7461 736b 5f67 726f  .g.: `["task_gro
+000076a0: 7570 5f31 2f2a 2a2f 7265 7375 6c74 732e  up_1/**/results.
+000076b0: 7478 7422 5d60 2e20 2020 2020 2020 2020  txt"]`.         
+000076c0: 2020 2020 2020 2020 2020 2020 7c20 5965              | Ye
+000076d0: 7320 207c 2059 6573 207c 2059 6573 2020  s  | Yes | Yes  
+000076e0: 7c20 5965 7320 207c 0a7c 2060 696e 7374  | Yes  |.| `inst
+000076f0: 616e 6365 5479 7065 7360 2020 2020 2020  anceTypes`      
+00007700: 2020 2020 2020 7c20 5468 6520 6d61 6368        | The mach
+00007710: 696e 6520 696e 7374 616e 6365 2074 7970  ine instance typ
+00007720: 6573 2074 6861 7420 6361 6e20 6265 2075  es that can be u
+00007730: 7365 6420 746f 2065 7865 6375 7465 2054  sed to execute T
+00007740: 6173 6b73 2e20 452e 672e 2c20 605b 2274  asks. E.g., `["t
+00007750: 332e 6d69 6372 6f22 2c20 2274 3361 2e6d  3.micro", "t3a.m
+00007760: 6963 726f 225d 602e 2020 2020 2020 2020  icro"]`.        
+00007770: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007780: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007790: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000077a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000077b0: 207c 2059 6573 2020 7c20 5965 7320 7c20   | Yes  | Yes | 
+000077c0: 5965 7320 207c 2020 2020 2020 7c0a 7c20  Yes  |      |.| 
+000077d0: 606d 6178 696d 756d 5461 736b 5265 7472  `maximumTaskRetr
+000077e0: 6965 7360 2020 2020 2020 207c 2054 6865  ies`       | The
+000077f0: 206d 6178 696d 756d 206e 756d 6265 7220   maximum number 
+00007800: 6f66 2074 696d 6573 2061 2054 6173 6b20  of times a Task 
+00007810: 6361 6e20 6265 2072 6574 7269 6564 2061  can be retried a
+00007820: 6674 6572 2069 7420 6861 7320 6661 696c  fter it has fail
+00007830: 6564 2e20 452e 672e 3a20 6035 602e 2020  ed. E.g.: `5`.  
+00007840: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007850: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007860: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007870: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007880: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007890: 2020 2020 2020 7c20 5965 7320 207c 2059        | Yes  | Y
+000078a0: 6573 207c 2059 6573 2020 7c20 2020 2020  es | Yes  |     
+000078b0: 207c 0a7c 2060 6d61 7857 6f72 6b65 7273   |.| `maxWorkers
+000078c0: 6020 2020 2020 2020 2020 2020 2020 2020  `               
+000078d0: 7c20 5468 6520 6d61 7869 6d75 6d20 6e75  | The maximum nu
+000078e0: 6d62 6572 206f 6620 576f 726b 6572 7320  mber of Workers 
+000078f0: 7468 6174 2063 616e 2062 6520 636c 6169  that can be clai
+00007900: 6d65 6420 666f 7220 7468 6520 6173 736f  med for the asso
+00007910: 6369 6174 6564 2054 6173 6b20 4772 6f75  ciated Task Grou
+00007920: 702e 2045 2e67 2e2c 2060 3130 602e 2020  p. E.g., `10`.  
+00007930: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007940: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007950: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007960: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007970: 2020 2020 2020 2020 2020 207c 2059 6573             | Yes
+00007980: 2020 7c20 5965 7320 7c20 5965 7320 207c    | Yes | Yes  |
+00007990: 2020 2020 2020 7c0a 7c20 606d 696e 576f        |.| `minWo
+000079a0: 726b 6572 7360 2020 2020 2020 2020 2020  rkers`          
+000079b0: 2020 2020 207c 2054 6865 206d 696e 696d       | The minim
+000079c0: 756d 206e 756d 6265 7220 6f66 2057 6f72  um number of Wor
+000079d0: 6b65 7273 2074 6861 7420 7468 6520 6173  kers that the as
+000079e0: 736f 6369 6174 6564 2054 6173 6b20 4772  sociated Task Gr
+000079f0: 6f75 7020 7265 7175 6972 6573 2e20 5468  oup requires. Th
+00007a00: 6973 206d 616e 7920 776f 726b 6572 7320  is many workers 
+00007a10: 6d75 7374 2062 6520 636c 6169 6d65 6420  must be claimed 
+00007a20: 6265 666f 7265 2074 6865 2061 7373 6f63  before the assoc
+00007a30: 6961 7465 6420 5461 736b 2047 726f 7570  iated Task Group
+00007a40: 2077 696c 6c20 7374 6172 7420 776f 726b   will start work
+00007a50: 696e 672e 2045 2e67 2e2c 2060 3160 2e20  ing. E.g., `1`. 
+00007a60: 7c20 5965 7320 207c 2059 6573 207c 2059  | Yes  | Yes | Y
+00007a70: 6573 2020 7c20 2020 2020 207c 0a7c 2060  es  |      |.| `
+00007a80: 6e61 6d65 6020 2020 2020 2020 2020 2020  name`           
+00007a90: 2020 2020 2020 2020 2020 7c20 5468 6520            | The 
+00007aa0: 6e61 6d65 206f 6620 7468 6520 576f 726b  name of the Work
+00007ab0: 2052 6571 7569 7265 6d65 6e74 2c20 5461   Requirement, Ta
+00007ac0: 736b 2047 726f 7570 206f 7220 5461 736b  sk Group or Task
+00007ad0: 2e20 452e 672e 2c20 6022 7772 5f6e 616d  . E.g., `"wr_nam
+00007ae0: 6522 602e 204e 6f74 6520 7468 6174 2074  e"`. Note that t
+00007af0: 6865 2060 6e61 6d65 6020 7072 6f70 6572  he `name` proper
+00007b00: 7479 2069 7320 6e6f 7420 696e 6865 7269  ty is not inheri
+00007b10: 7465 642e 2020 2020 2020 2020 2020 2020  ted.            
+00007b20: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007b30: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007b40: 2020 2020 207c 2059 6573 2020 7c20 5965       | Yes  | Ye
+00007b50: 7320 7c20 5965 7320 207c 2059 6573 2020  s | Yes  | Yes  
+00007b60: 7c0a 7c20 606f 7574 7075 7473 6020 2020  |.| `outputs`   
+00007b70: 2020 2020 2020 2020 2020 2020 2020 207c                 |
+00007b80: 2054 6865 2066 696c 6573 2074 6f20 6265   The files to be
+00007b90: 2075 706c 6f61 6465 6420 746f 2074 6865   uploaded to the
+00007ba0: 2059 656c 6c6f 7744 6f67 204f 626a 6563   YellowDog Objec
+00007bb0: 7420 5374 6f72 6520 6279 2061 2057 6f72  t Store by a Wor
+00007bc0: 6b65 7220 6e6f 6465 206f 6e20 636f 6d70  ker node on comp
+00007bd0: 6c65 7469 6f6e 206f 6620 7468 6520 5461  letion of the Ta
+00007be0: 736b 2e20 452e 672e 2c20 605b 2272 6573  sk. E.g., `["res
+00007bf0: 756c 7473 5f31 2e74 7874 222c 2022 7265  ults_1.txt", "re
+00007c00: 7375 6c74 735f 322e 7478 7422 5d60 2e20  sults_2.txt"]`. 
+00007c10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007c20: 2020 2020 2020 2020 2020 7c20 5965 7320            | Yes 
+00007c30: 207c 2059 6573 207c 2059 6573 2020 7c20   | Yes | Yes  | 
+00007c40: 5965 7320 207c 0a7c 2060 6f75 7470 7574  Yes  |.| `output
+00007c50: 7352 6571 7569 7265 6460 2020 2020 2020  sRequired`      
+00007c60: 2020 2020 7c20 5468 6520 6669 6c65 7320      | The files 
+00007c70: 7468 6174 202a 6d75 7374 2a20 6265 2075  that *must* be u
+00007c80: 706c 6f61 6465 6420 746f 2074 6865 2059  ploaded to the Y
+00007c90: 656c 6c6f 7744 6f67 204f 626a 6563 7420  ellowDog Object 
+00007ca0: 5374 6f72 6520 6279 2061 2057 6f72 6b65  Store by a Worke
+00007cb0: 7220 6e6f 6465 206f 6e20 636f 6d70 6c65  r node on comple
+00007cc0: 7469 6f6e 206f 6620 7468 6520 5461 736b  tion of the Task
+00007cd0: 2e20 5468 6520 5461 736b 2077 696c 6c20  . The Task will 
+00007ce0: 6661 696c 2069 6620 616e 7920 6f75 7470  fail if any outp
+00007cf0: 7574 7320 6172 6520 756e 6176 6169 6c61  uts are unavaila
+00007d00: 626c 652e 2020 2020 2020 2020 2020 207c  ble.           |
+00007d10: 2059 6573 2020 7c20 5965 7320 7c20 5965   Yes  | Yes | Ye
+00007d20: 7320 207c 2059 6573 2020 7c0a 7c20 6070  s  | Yes  |.| `p
+00007d30: 7269 6f72 6974 7960 2020 2020 2020 2020  riority`        
+00007d40: 2020 2020 2020 2020 207c 2054 6865 2070           | The p
+00007d50: 7269 6f72 6974 7920 6f66 2057 6f72 6b20  riority of Work 
+00007d60: 5265 7175 6972 656d 656e 7473 2061 6e64  Requirements and
+00007d70: 2054 6173 6b20 4772 6f75 7073 2e20 4869   Task Groups. Hi
+00007d80: 6768 6572 2070 7269 6f72 6974 7920 6163  gher priority ac
+00007d90: 7175 6972 6573 2057 6f72 6b65 7273 2061  quires Workers a
+00007da0: 6865 6164 206f 6620 6c6f 7765 7220 7072  head of lower pr
+00007db0: 696f 7269 7479 2e20 452e 672e 2c20 6030  iority. E.g., `0
+00007dc0: 2e30 602e 2020 2020 2020 2020 2020 2020  .0`.            
+00007dd0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007de0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007df0: 2020 2020 7c20 5965 7320 207c 2059 6573      | Yes  | Yes
+00007e00: 207c 2059 6573 2020 7c20 2020 2020 207c   | Yes  |      |
+00007e10: 0a7c 2060 7072 6f76 6964 6572 7360 2020  .| `providers`  
+00007e20: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00007e30: 436f 6e73 7472 6169 6e73 2074 6865 2059  Constrains the Y
+00007e40: 656c 6c6f 7744 6f67 2053 6368 6564 756c  ellowDog Schedul
+00007e50: 6572 206f 6e6c 7920 746f 2065 7865 6375  er only to execu
+00007e60: 7465 2074 6173 6b73 2066 726f 6d20 7468  te tasks from th
+00007e70: 6520 6173 736f 6369 6174 6564 2054 6173  e associated Tas
+00007e80: 6b20 4772 6f75 7020 6f6e 2074 6865 2073  k Group on the s
+00007e90: 7065 6369 6669 6564 2070 726f 7669 6465  pecified provide
+00007ea0: 7273 2e20 452e 672e 2c20 605b 2241 5753  rs. E.g., `["AWS
+00007eb0: 222c 2022 474f 4f47 4c45 225d 602e 2020  ", "GOOGLE"]`.  
+00007ec0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007ed0: 2020 2020 2020 2020 207c 2059 6573 2020           | Yes  
+00007ee0: 7c20 5965 7320 7c20 5965 7320 207c 2020  | Yes | Yes  |  
+00007ef0: 2020 2020 7c0a 7c20 6072 616d 6020 2020      |.| `ram`   
+00007f00: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007f10: 2020 207c 2052 616e 6765 2063 6f6e 7374     | Range const
+00007f20: 7261 696e 7420 6f6e 2047 4220 6f66 2052  raint on GB of R
+00007f30: 414d 2074 6861 7420 6172 6520 7265 7175  AM that are requ
+00007f40: 6972 6564 2074 6f20 6578 6563 7574 6520  ired to execute 
+00007f50: 5461 736b 732e 2045 2e67 2e2c 2060 5b32  Tasks. E.g., `[2
+00007f60: 2e35 2c20 342e 305d 602e 2020 2020 2020  .5, 4.0]`.      
+00007f70: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007f80: 2020 2020 2020 2020 2020 2020 2020 2020                  
 00007f90: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00007fa0: 207c 2043 6f6e 7374 7261 696e 7320 7468   | Constrains th
-00007fb0: 6520 5965 6c6c 6f77 446f 6720 5363 6865  e YellowDog Sche
-00007fc0: 6475 6c65 7220 6f6e 6c79 2074 6f20 6578  duler only to ex
-00007fd0: 6563 7574 6520 5461 736b 7320 6672 6f6d  ecute Tasks from
-00007fe0: 2074 6865 2061 7373 6f63 6961 7465 6420   the associated 
-00007ff0: 5461 736b 2047 726f 7570 2069 6e20 7468  Task Group in th
-00008000: 6520 7370 6563 6966 6965 6420 7265 6769  e specified regi
-00008010: 6f6e 732e 2045 2e67 2e2c 2060 5b22 6575  ons. E.g., `["eu
-00008020: 2d77 6573 742d 325d 602e 2020 2020 2020  -west-2]`.      
-00008030: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008040: 2020 2020 2020 2020 2020 2020 7c20 5965              | Ye
-00008050: 7320 207c 2059 6573 207c 2059 6573 2020  s  | Yes | Yes  
-00008060: 7c20 2020 2020 207c 0a7c 2060 7461 736b  |      |.| `task
-00008070: 4261 7463 6853 697a 6560 2020 2020 2020  BatchSize`      
-00008080: 2020 2020 2020 7c20 4465 7465 726d 696e        | Determin
-00008090: 6573 2074 6865 2062 6174 6368 2073 697a  es the batch siz
-000080a0: 6520 7573 6564 2074 6f20 6164 6420 5461  e used to add Ta
-000080b0: 736b 7320 746f 2054 6173 6b20 4772 6f75  sks to Task Grou
-000080c0: 7073 2e20 4465 6661 756c 7420 6973 2032  ps. Default is 2
-000080d0: 2c30 3030 2e20 2020 2020 2020 2020 2020  ,000.           
-000080e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000080f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008100: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008110: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008120: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008130: 207c 2059 6573 2020 7c20 2020 2020 7c20   | Yes  |     | 
-00008140: 2020 2020 207c 2020 2020 2020 7c0a 7c20       |      |.| 
-00008150: 6074 6173 6b43 6f75 6e74 6020 2020 2020  `taskCount`     
-00008160: 2020 2020 2020 2020 2020 207c 2054 6865             | The
-00008170: 206e 756d 6265 7220 6f66 2074 696d 6573   number of times
-00008180: 2074 6f20 6578 6563 7574 6520 7468 6520   to execute the 
-00008190: 5461 736b 2e20 4361 6e20 6265 2073 6574  Task. Can be set
-000081a0: 2069 6e20 7468 6520 544f 4d4c 2066 696c   in the TOML fil
-000081b0: 6520 6f72 2069 6e20 616e 7920 4a53 4f4e  e or in any JSON
-000081c0: 2054 6173 6b20 4772 6f75 7020 6465 6669   Task Group defi
-000081d0: 6e69 7469 6f6e 2e20 4e6f 7465 3a20 6e6f  nition. Note: no
-000081e0: 2069 6e68 6572 6974 616e 6365 2066 726f   inheritance fro
-000081f0: 6d20 544f 4d4c 2074 6f20 4a53 4f4e 2e20  m TOML to JSON. 
-00008200: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008210: 2020 2020 2020 7c20 5965 7320 207c 2020        | Yes  |  
-00008220: 2020 207c 2059 6573 2020 7c20 2020 2020     | Yes  |     
-00008230: 207c 0a7c 2060 7461 736b 4461 7461 6020   |.| `taskData` 
-00008240: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008250: 7c20 5468 6520 6461 7461 2074 6f20 6265  | The data to be
-00008260: 2070 6173 7365 6420 746f 2074 6865 2057   passed to the W
-00008270: 6f72 6b65 7220 7768 656e 2074 6865 2054  orker when the T
-00008280: 6173 6b20 6973 2073 7461 7274 6564 2e20  ask is started. 
-00008290: 452e 672e 2c20 6022 6d79 6461 7461 2260  E.g., `"mydata"`
-000082a0: 2e20 4265 636f 6d65 7320 6669 6c65 2060  . Becomes file `
-000082b0: 7461 736b 6461 7461 2e74 7874 6020 696e  taskdata.txt` in
-000082c0: 2074 6865 2054 6173 6b27 7320 776f 726b   the Task's work
-000082d0: 696e 6720 6469 7265 6374 6f72 7920 7768  ing directory wh
-000082e0: 656e 2054 6865 2054 6173 6b20 6578 6563  en The Task exec
-000082f0: 7574 6573 2e20 2020 2020 207c 2059 6573  utes.      | Yes
-00008300: 2020 7c20 5965 7320 7c20 5965 7320 207c    | Yes | Yes  |
-00008310: 2059 6573 2020 7c0a 7c20 6074 6173 6b44   Yes  |.| `taskD
-00008320: 6174 6146 696c 6560 2020 2020 2020 2020  ataFile`        
-00008330: 2020 2020 207c 2050 6f70 756c 6174 6520       | Populate 
-00008340: 7468 6520 6074 6173 6b44 6174 6160 2070  the `taskData` p
-00008350: 726f 7065 7274 7920 6162 6f76 6520 7769  roperty above wi
-00008360: 7468 2074 6865 2063 6f6e 7465 6e74 7320  th the contents 
-00008370: 6f66 2074 6865 2073 7065 6369 6669 6564  of the specified
-00008380: 2066 696c 652e 2045 2e67 2e2c 2060 226d   file. E.g., `"m
-00008390: 795f 7461 736b 5f64 6174 615f 6669 6c65  y_task_data_file
-000083a0: 2e74 7874 2260 2e20 2020 2020 2020 2020  .txt"`.         
-000083b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000083c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000083d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000083e0: 7c20 5965 7320 207c 2059 6573 207c 2059  | Yes  | Yes | Y
-000083f0: 6573 2020 7c20 5965 7320 207c 0a7c 2060  es  | Yes  |.| `
-00008400: 7461 736b 4e61 6d65 6020 2020 2020 2020  taskName`       
-00008410: 2020 2020 2020 2020 2020 7c20 5468 6520            | The 
-00008420: 6e61 6d65 2074 6f20 7573 6520 666f 7220  name to use for 
-00008430: 7468 6520 5461 736b 2e20 4f6e 6c79 2075  the Task. Only u
-00008440: 7361 626c 6520 696e 2074 6865 2054 4f4d  sable in the TOM
-00008450: 4c20 6669 6c65 2e20 4d6f 7374 6c79 2075  L file. Mostly u
-00008460: 7365 6675 6c20 696e 2063 6f6e 6a75 6e63  seful in conjunc
-00008470: 7469 6f6e 2077 6974 6820 4353 5620 5461  tion with CSV Ta
-00008480: 736b 2064 6174 612e 2045 2e67 2e2c 2060  sk data. E.g., `
-00008490: 226d 795f 7461 736b 5f6e 756d 6265 725f  "my_task_number_
-000084a0: 7b7b 7461 736b 5f6e 756d 6265 727d 7d22  {{task_number}}"
-000084b0: 602e 2020 2020 2020 2020 2020 2020 2020  `.              
-000084c0: 2020 2020 207c 2059 6573 2020 7c20 2020       | Yes  |   
-000084d0: 2020 7c20 2020 2020 207c 2020 2020 2020    |      |      
-000084e0: 7c0a 7c20 6074 6173 6b47 726f 7570 4e61  |.| `taskGroupNa
-000084f0: 6d65 6020 2020 2020 2020 2020 2020 207c  me`            |
-00008500: 2054 6865 206e 616d 6520 746f 2075 7365   The name to use
-00008510: 2066 6f72 2074 6865 2054 6173 6b20 4772   for the Task Gr
-00008520: 6f75 702e 204f 6e6c 7920 7573 6162 6c65  oup. Only usable
-00008530: 2069 6e20 7468 6520 544f 4d4c 2066 696c   in the TOML fil
-00008540: 652e 2045 2e67 2e2c 2060 226d 795f 7467  e. E.g., `"my_tg
-00008550: 5f6e 756d 6265 725f 7b7b 7461 736b 5f67  _number_{{task_g
-00008560: 726f 7570 5f6e 756d 6265 727d 7d22 602e  roup_number}}"`.
-00008570: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008580: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008590: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000085a0: 2020 2020 2020 2020 2020 7c20 5965 7320            | Yes 
-000085b0: 207c 2020 2020 207c 2020 2020 2020 7c20   |     |      | 
-000085c0: 2020 2020 207c 0a7c 2060 7461 736b 5479       |.| `taskTy
-000085d0: 7065 6020 2020 2020 2020 2020 2020 2020  pe`             
-000085e0: 2020 2020 7c20 5468 6520 5461 736b 2054      | The Task T
-000085f0: 7970 6520 6f66 2061 2054 6173 6b2e 2045  ype of a Task. E
-00008600: 2e67 2e2c 2060 2264 6f63 6b65 7222 602e  .g., `"docker"`.
-00008610: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008620: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008630: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008640: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008650: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008660: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007fa0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00007fb0: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00007fc0: 5965 7320 207c 2059 6573 207c 2059 6573  Yes  | Yes | Yes
+00007fd0: 2020 7c20 2020 2020 207c 0a7c 2060 7265    |      |.| `re
+00007fe0: 6769 6f6e 7360 2020 2020 2020 2020 2020  gions`          
+00007ff0: 2020 2020 2020 2020 7c20 436f 6e73 7472          | Constr
+00008000: 6169 6e73 2074 6865 2059 656c 6c6f 7744  ains the YellowD
+00008010: 6f67 2053 6368 6564 756c 6572 206f 6e6c  og Scheduler onl
+00008020: 7920 746f 2065 7865 6375 7465 2054 6173  y to execute Tas
+00008030: 6b73 2066 726f 6d20 7468 6520 6173 736f  ks from the asso
+00008040: 6369 6174 6564 2054 6173 6b20 4772 6f75  ciated Task Grou
+00008050: 7020 696e 2074 6865 2073 7065 6369 6669  p in the specifi
+00008060: 6564 2072 6567 696f 6e73 2e20 452e 672e  ed regions. E.g.
+00008070: 2c20 605b 2265 752d 7765 7374 2d32 5d60  , `["eu-west-2]`
+00008080: 2e20 2020 2020 2020 2020 2020 2020 2020  .               
+00008090: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000080a0: 2020 207c 2059 6573 2020 7c20 5965 7320     | Yes  | Yes 
+000080b0: 7c20 5965 7320 207c 2020 2020 2020 7c0a  | Yes  |      |.
+000080c0: 7c20 6074 6173 6b42 6174 6368 5369 7a65  | `taskBatchSize
+000080d0: 6020 2020 2020 2020 2020 2020 207c 2044  `            | D
+000080e0: 6574 6572 6d69 6e65 7320 7468 6520 6261  etermines the ba
+000080f0: 7463 6820 7369 7a65 2075 7365 6420 746f  tch size used to
+00008100: 2061 6464 2054 6173 6b73 2074 6f20 5461   add Tasks to Ta
+00008110: 736b 2047 726f 7570 732e 2044 6566 6175  sk Groups. Defau
+00008120: 6c74 2069 7320 322c 3030 302e 2020 2020  lt is 2,000.    
+00008130: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008140: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008150: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008160: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008170: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008180: 2020 2020 2020 2020 7c20 5965 7320 207c          | Yes  |
+00008190: 2020 2020 207c 2020 2020 2020 7c20 2020       |      |   
+000081a0: 2020 207c 0a7c 2060 7461 736b 436f 756e     |.| `taskCoun
+000081b0: 7460 2020 2020 2020 2020 2020 2020 2020  t`              
+000081c0: 2020 7c20 5468 6520 6e75 6d62 6572 206f    | The number o
+000081d0: 6620 7469 6d65 7320 746f 2065 7865 6375  f times to execu
+000081e0: 7465 2074 6865 2054 6173 6b2e 2043 616e  te the Task. Can
+000081f0: 2062 6520 7365 7420 696e 2074 6865 2054   be set in the T
+00008200: 4f4d 4c20 6669 6c65 206f 7220 696e 2061  OML file or in a
+00008210: 6e79 204a 534f 4e20 5461 736b 2047 726f  ny JSON Task Gro
+00008220: 7570 2064 6566 696e 6974 696f 6e2e 204e  up definition. N
+00008230: 6f74 653a 206e 6f20 696e 6865 7269 7461  ote: no inherita
+00008240: 6e63 6520 6672 6f6d 2054 4f4d 4c20 746f  nce from TOML to
+00008250: 204a 534f 4e2e 2020 2020 2020 2020 2020   JSON.          
+00008260: 2020 2020 2020 2020 2020 2020 207c 2059               | Y
+00008270: 6573 2020 7c20 2020 2020 7c20 5965 7320  es  |     | Yes 
+00008280: 207c 2020 2020 2020 7c0a 7c20 6074 6173   |      |.| `tas
+00008290: 6b44 6174 6160 2020 2020 2020 2020 2020  kData`          
+000082a0: 2020 2020 2020 207c 2054 6865 2064 6174         | The dat
+000082b0: 6120 746f 2062 6520 7061 7373 6564 2074  a to be passed t
+000082c0: 6f20 7468 6520 576f 726b 6572 2077 6865  o the Worker whe
+000082d0: 6e20 7468 6520 5461 736b 2069 7320 7374  n the Task is st
+000082e0: 6172 7465 642e 2045 2e67 2e2c 2060 226d  arted. E.g., `"m
+000082f0: 7964 6174 6122 602e 2042 6563 6f6d 6573  ydata"`. Becomes
+00008300: 2066 696c 6520 6074 6173 6b64 6174 612e   file `taskdata.
+00008310: 7478 7460 2069 6e20 7468 6520 5461 736b  txt` in the Task
+00008320: 2773 2077 6f72 6b69 6e67 2064 6972 6563  's working direc
+00008330: 746f 7279 2077 6865 6e20 5468 6520 5461  tory when The Ta
+00008340: 736b 2065 7865 6375 7465 732e 2020 2020  sk executes.    
+00008350: 2020 7c20 5965 7320 207c 2059 6573 207c    | Yes  | Yes |
+00008360: 2059 6573 2020 7c20 5965 7320 207c 0a7c   Yes  | Yes  |.|
+00008370: 2060 7461 736b 4461 7461 4669 6c65 6020   `taskDataFile` 
+00008380: 2020 2020 2020 2020 2020 2020 7c20 506f              | Po
+00008390: 7075 6c61 7465 2074 6865 2060 7461 736b  pulate the `task
+000083a0: 4461 7461 6020 7072 6f70 6572 7479 2061  Data` property a
+000083b0: 626f 7665 2077 6974 6820 7468 6520 636f  bove with the co
+000083c0: 6e74 656e 7473 206f 6620 7468 6520 7370  ntents of the sp
+000083d0: 6563 6966 6965 6420 6669 6c65 2e20 452e  ecified file. E.
+000083e0: 672e 2c20 6022 6d79 5f74 6173 6b5f 6461  g., `"my_task_da
+000083f0: 7461 5f66 696c 652e 7478 7422 602e 2020  ta_file.txt"`.  
+00008400: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008410: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008420: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008430: 2020 2020 2020 207c 2059 6573 2020 7c20         | Yes  | 
+00008440: 5965 7320 7c20 5965 7320 207c 2059 6573  Yes | Yes  | Yes
+00008450: 2020 7c0a 7c20 6074 6173 6b4e 616d 6560    |.| `taskName`
+00008460: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008470: 207c 2054 6865 206e 616d 6520 746f 2075   | The name to u
+00008480: 7365 2066 6f72 2074 6865 2054 6173 6b2e  se for the Task.
+00008490: 204f 6e6c 7920 7573 6162 6c65 2069 6e20   Only usable in 
+000084a0: 7468 6520 544f 4d4c 2066 696c 652e 204d  the TOML file. M
+000084b0: 6f73 746c 7920 7573 6566 756c 2069 6e20  ostly useful in 
+000084c0: 636f 6e6a 756e 6374 696f 6e20 7769 7468  conjunction with
+000084d0: 2043 5356 2054 6173 6b20 6461 7461 2e20   CSV Task data. 
+000084e0: 452e 672e 2c20 6022 6d79 5f74 6173 6b5f  E.g., `"my_task_
+000084f0: 6e75 6d62 6572 5f7b 7b74 6173 6b5f 6e75  number_{{task_nu
+00008500: 6d62 6572 7d7d 2260 2e20 2020 2020 2020  mber}}"`.       
+00008510: 2020 2020 2020 2020 2020 2020 7c20 5965              | Ye
+00008520: 7320 207c 2020 2020 207c 2020 2020 2020  s  |     |      
+00008530: 7c20 2020 2020 207c 0a7c 2060 7461 736b  |      |.| `task
+00008540: 4772 6f75 704e 616d 6560 2020 2020 2020  GroupName`      
+00008550: 2020 2020 2020 7c20 5468 6520 6e61 6d65        | The name
+00008560: 2074 6f20 7573 6520 666f 7220 7468 6520   to use for the 
+00008570: 5461 736b 2047 726f 7570 2e20 4f6e 6c79  Task Group. Only
+00008580: 2075 7361 626c 6520 696e 2074 6865 2054   usable in the T
+00008590: 4f4d 4c20 6669 6c65 2e20 452e 672e 2c20  OML file. E.g., 
+000085a0: 6022 6d79 5f74 675f 6e75 6d62 6572 5f7b  `"my_tg_number_{
+000085b0: 7b74 6173 6b5f 6772 6f75 705f 6e75 6d62  {task_group_numb
+000085c0: 6572 7d7d 2260 2e20 2020 2020 2020 2020  er}}"`.         
+000085d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000085e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000085f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008600: 207c 2059 6573 2020 7c20 2020 2020 7c20   | Yes  |     | 
+00008610: 2020 2020 207c 2020 2020 2020 7c0a 7c20       |      |.| 
+00008620: 6074 6173 6b54 7970 6560 2020 2020 2020  `taskType`      
+00008630: 2020 2020 2020 2020 2020 207c 2054 6865             | The
+00008640: 2054 6173 6b20 5479 7065 206f 6620 6120   Task Type of a 
+00008650: 5461 736b 2e20 452e 672e 2c20 6022 646f  Task. E.g., `"do
+00008660: 636b 6572 2260 2e20 2020 2020 2020 2020  cker"`.         
 00008670: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008680: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00008690: 2059 6573 2020 7c20 2020 2020 7c20 2020   Yes  |     |   
-000086a0: 2020 207c 2059 6573 2020 7c0a 7c20 6074     | Yes  |.| `t
-000086b0: 6173 6b54 7970 6573 6020 2020 2020 2020  askTypes`       
-000086c0: 2020 2020 2020 2020 207c 2054 6865 206c           | The l
-000086d0: 6973 7420 6f66 2054 6173 6b20 5479 7065  ist of Task Type
-000086e0: 7320 7265 7175 6972 6564 2062 7920 7468  s required by th
-000086f0: 6520 7261 6e67 6520 6f66 2054 6173 6b73  e range of Tasks
-00008700: 2069 6e20 6120 5461 736b 2047 726f 7570   in a Task Group
-00008710: 2e20 452e 672e 2c20 605b 2264 6f63 6b65  . E.g., `["docke
-00008720: 7222 2c20 6261 7368 225d 602e 2020 2020  r", bash"]`.    
-00008730: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008740: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008750: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008760: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008770: 2020 2020 7c20 2020 2020 207c 2059 6573      |      | Yes
-00008780: 207c 2059 6573 2020 7c20 2020 2020 207c   | Yes  |      |
-00008790: 0a7c 2060 7461 736b 7350 6572 576f 726b  .| `tasksPerWork
-000087a0: 6572 6020 2020 2020 2020 2020 2020 7c20  er`           | 
-000087b0: 4465 7465 726d 696e 6573 2074 6865 206e  Determines the n
-000087c0: 756d 6265 7220 6f66 2057 6f72 6b65 7220  umber of Worker 
-000087d0: 636c 6169 6d73 2062 6173 6564 206f 6e20  claims based on 
-000087e0: 7370 6c69 7474 696e 6720 7468 6520 6e75  splitting the nu
-000087f0: 6d62 6572 206f 6620 756e 6669 6e69 7368  mber of unfinish
-00008800: 6564 2054 6173 6b73 2061 6372 6f73 7320  ed Tasks across 
-00008810: 576f 726b 6572 732e 2045 2e67 2e2c 2060  Workers. E.g., `
-00008820: 3160 2e20 2020 2020 2020 2020 2020 2020  1`.             
-00008830: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008840: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008850: 2020 2020 2020 2020 207c 2059 6573 2020           | Yes  
-00008860: 7c20 5965 7320 7c20 5965 7320 207c 2020  | Yes | Yes  |  
-00008870: 2020 2020 7c0a 7c20 6075 706c 6f61 6446      |.| `uploadF
-00008880: 696c 6573 6020 2020 2020 2020 2020 2020  iles`           
-00008890: 2020 207c 2054 6865 206c 6973 7420 6f66     | The list of
-000088a0: 2066 696c 6573 2074 6f20 6265 2075 706c   files to be upl
-000088b0: 6f61 6465 6420 746f 2074 6865 2059 656c  oaded to the Yel
-000088c0: 6c6f 7744 6f67 204f 626a 6563 7420 5374  lowDog Object St
-000088d0: 6f72 652e 2045 2e67 2e2c 2028 4a53 4f4e  ore. E.g., (JSON
-000088e0: 293a 2060 5b7b 226c 6f63 616c 5061 7468  ): `[{"localPath
-000088f0: 223a 2066 696c 655f 312e 7478 7422 2c20  ": file_1.txt", 
-00008900: 2275 706c 6f61 6450 6174 6822 3a20 2266  "uploadPath": "f
-00008910: 696c 655f 312e 7478 7422 7d5d 602e 2020  ile_1.txt"}]`.  
-00008920: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008930: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
-00008940: 5965 7320 207c 2059 6573 207c 2059 6573  Yes  | Yes | Yes
-00008950: 2020 7c20 5965 7320 207c 0a7c 2060 7663    | Yes  |.| `vc
-00008960: 7075 7360 2020 2020 2020 2020 2020 2020  pus`            
-00008970: 2020 2020 2020 2020 7c20 5261 6e67 6520          | Range 
-00008980: 636f 6e73 7472 6169 6e74 206f 6e20 6e75  constraint on nu
-00008990: 6d62 6572 206f 6620 7643 5055 7320 7468  mber of vCPUs th
-000089a0: 6174 2061 7265 2072 6571 7569 7265 6420  at are required 
-000089b0: 746f 2065 7865 6375 7465 2054 6173 6b73  to execute Tasks
-000089c0: 2045 2e67 2e2c 2060 5b32 2e30 2c20 342e   E.g., `[2.0, 4.
-000089d0: 305d 602e 2020 2020 2020 2020 2020 2020  0]`.            
-000089e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000089f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008a00: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008a10: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008a20: 2020 207c 2059 6573 2020 7c20 5965 7320     | Yes  | Yes 
-00008a30: 7c20 5965 7320 207c 2020 2020 2020 7c0a  | Yes  |      |.
-00008a40: 7c20 6076 6572 6966 7941 7453 7461 7274  | `verifyAtStart
-00008a50: 6020 2020 2020 2020 2020 2020 207c 2041  `            | A
-00008a60: 206c 6973 7420 6f66 2066 696c 6573 2072   list of files r
-00008a70: 6571 7569 7265 6420 6279 2061 2054 6173  equired by a Tas
-00008a80: 6b2e 204d 7573 7420 6265 2070 7265 7365  k. Must be prese
-00008a90: 6e74 2077 6865 6e20 7468 6520 5461 736b  nt when the Task
-00008aa0: 2069 7320 7265 6164 7920 746f 2073 7461   is ready to sta
-00008ab0: 7274 206f 7220 7468 6520 5461 736b 2077  rt or the Task w
-00008ac0: 696c 6c20 6661 696c 2e20 452e 672e 3a20  ill fail. E.g.: 
-00008ad0: 605b 2274 6173 6b5f 6772 6f75 705f 312f  `["task_group_1/
-00008ae0: 7461 736b 5f31 2f72 6573 756c 7473 2e74  task_1/results.t
-00008af0: 7874 225d 602e 2020 2020 2020 2020 2020  xt"]`.          
-00008b00: 2020 2020 2020 2020 7c20 5965 7320 207c          | Yes  |
-00008b10: 2059 6573 207c 2059 6573 2020 7c20 5965   Yes | Yes  | Ye
-00008b20: 7320 207c 0a7c 2060 7665 7269 6679 5761  s  |.| `verifyWa
-00008b30: 6974 6020 2020 2020 2020 2020 2020 2020  it`             
-00008b40: 2020 7c20 4120 6c69 7374 206f 6620 6669    | A list of fi
-00008b50: 6c65 7320 7265 7175 6972 6564 2062 7920  les required by 
-00008b60: 6120 5461 736b 2e20 5468 6520 5461 736b  a Task. The Task
-00008b70: 2077 696c 6c20 7761 6974 2075 6e74 696c   will wait until
-00008b80: 2074 6865 2066 696c 6573 2061 7265 2061   the files are a
-00008b90: 7661 696c 6162 6c65 2062 6566 6f72 6520  vailable before 
-00008ba0: 7374 6172 7469 6e67 2e20 452e 672e 3a20  starting. E.g.: 
-00008bb0: 605b 2274 6173 6b5f 6772 6f75 705f 312f  `["task_group_1/
-00008bc0: 7461 736b 5f31 2f72 6573 756c 7473 2e74  task_1/results.t
-00008bd0: 7874 225d 602e 2020 2020 2020 2020 2020  xt"]`.          
-00008be0: 2020 2020 2020 2020 2020 2020 207c 2059               | Y
-00008bf0: 6573 2020 7c20 5965 7320 7c20 5965 7320  es  | Yes | Yes 
-00008c00: 207c 2059 6573 2020 7c0a 7c20 6077 6f72   | Yes  |.| `wor
-00008c10: 6b65 7254 6167 7360 2020 2020 2020 2020  kerTags`        
-00008c20: 2020 2020 2020 207c 2054 6865 206c 6973         | The lis
-00008c30: 7420 6f66 2057 6f72 6b65 7220 5461 6773  t of Worker Tags
-00008c40: 2074 6861 7420 7769 6c6c 2062 6520 7573   that will be us
-00008c50: 6564 2074 6f20 6d61 7463 6820 6167 6169  ed to match agai
-00008c60: 6e73 7420 7468 6520 576f 726b 6572 2054  nst the Worker T
-00008c70: 6167 206f 6620 6120 6361 6e64 6964 6174  ag of a candidat
-00008c80: 6520 576f 726b 6572 2e20 452e 672e 2c20  e Worker. E.g., 
-00008c90: 605b 2274 6167 5f78 222c 2022 7461 675f  `["tag_x", "tag_
-00008ca0: 7922 5d60 2e20 2020 2020 2020 2020 2020  y"]`.           
-00008cb0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008cc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008cd0: 2020 7c20 5965 7320 207c 2059 6573 207c    | Yes  | Yes |
-00008ce0: 2059 6573 2020 7c20 2020 2020 207c 0a7c   Yes  |      |.|
-00008cf0: 2060 776f 726b 5265 7175 6972 656d 656e   `workRequiremen
-00008d00: 7444 6174 6160 2020 2020 2020 7c20 5468  tData`      | Th
-00008d10: 6520 6e61 6d65 206f 6620 7468 6520 6669  e name of the fi
-00008d20: 6c65 2063 6f6e 7461 696e 696e 6720 7468  le containing th
-00008d30: 6520 4a53 4f4e 2064 6f63 756d 656e 7420  e JSON document 
-00008d40: 696e 2077 6869 6368 2074 6865 2057 6f72  in which the Wor
-00008d50: 6b20 5265 7175 6972 656d 656e 7420 6973  k Requirement is
-00008d60: 2064 6566 696e 6564 2e20 452e 672e 2c20   defined. E.g., 
-00008d70: 6022 7465 7374 5f77 6f72 6b72 6571 2e6a  `"test_workreq.j
-00008d80: 736f 6e22 602e 2020 2020 2020 2020 2020  son"`.          
-00008d90: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008da0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00008db0: 2020 2020 2020 207c 2059 6573 2020 7c20         | Yes  | 
-00008dc0: 2020 2020 7c20 2020 2020 207c 2020 2020      |      |    
-00008dd0: 2020 7c0a 0a23 2320 4175 746f 6d61 7469    |..## Automati
-00008de0: 6320 5072 6f70 6572 7469 6573 0a0a 496e  c Properties..In
-00008df0: 2061 6464 6974 696f 6e20 746f 2074 6865   addition to the
-00008e00: 2069 6e68 6572 6974 616e 6365 206d 6563   inheritance mec
-00008e10: 6861 6e69 736d 2c20 736f 6d65 2070 726f  hanism, some pro
-00008e20: 7065 7274 6965 7320 6172 6520 7365 7420  perties are set 
-00008e30: 6175 746f 6d61 7469 6361 6c6c 7920 6279  automatically by
-00008e40: 2074 6865 2060 7964 2d73 7562 6d69 7460   the `yd-submit`
-00008e50: 2063 6f6d 6d61 6e64 2c20 6173 2061 2075   command, as a u
-00008e60: 7361 6765 2063 6f6e 7665 6e69 656e 6365  sage convenience
-00008e70: 2069 6620 7468 6579 2772 6520 6e6f 7420   if they're not 
-00008e80: 6578 706c 6963 6974 6c79 2070 726f 7669  explicitly provi
-00008e90: 6465 642e 0a0a 2323 2320 576f 726b 2052  ded...### Work R
-00008ea0: 6571 7569 7265 6d65 6e74 2c20 5461 736b  equirement, Task
-00008eb0: 2047 726f 7570 2061 6e64 2054 6173 6b20   Group and Task 
-00008ec0: 4e61 6d69 6e67 0a0a 2d20 5468 6520 2a2a  Naming..- The **
-00008ed0: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
-00008ee0: 2a2a 206e 616d 6520 6973 2061 7574 6f6d  ** name is autom
-00008ef0: 6174 6963 616c 6c79 2073 6574 2075 7369  atically set usi
-00008f00: 6e67 2061 2063 6f6e 6361 7465 6e61 7469  ng a concatenati
-00008f10: 6f6e 206f 6620 7468 6520 6074 6167 6020  on of the `tag` 
-00008f20: 7072 6f70 6572 7479 2c20 6120 5554 4320  property, a UTC 
-00008f30: 7469 6d65 7374 616d 702c 2061 6e64 2074  timestamp, and t
-00008f40: 6872 6565 2072 616e 646f 6d20 6865 7820  hree random hex 
-00008f50: 6368 6172 6163 7465 7273 3a20 652c 672c  characters: e,g,
-00008f60: 2e20 606d 7974 6167 5f32 3231 3032 342d  . `mytag_221024-
-00008f70: 3135 3535 3234 2d34 3061 602e 0a2d 202a  155524-40a`..- *
-00008f80: 2a54 6173 6b20 4772 6f75 702a 2a20 6e61  *Task Group** na
-00008f90: 6d65 7320 6172 6520 6175 746f 6d61 7469  mes are automati
-00008fa0: 6361 6c6c 7920 6372 6561 7465 6420 666f  cally created fo
-00008fb0: 7220 616e 7920 5461 736b 2047 726f 7570  r any Task Group
-00008fc0: 2074 6861 7420 6973 206e 6f74 2065 7870   that is not exp
-00008fd0: 6c69 6369 746c 7920 6e61 6d65 642c 2075  licitly named, u
-00008fe0: 7369 6e67 206e 616d 6573 206f 6620 7468  sing names of th
-00008ff0: 6520 666f 726d 2060 7461 736b 5f67 726f  e form `task_gro
-00009000: 7570 5f31 6020 286f 7220 6074 6173 6b5f  up_1` (or `task_
-00009010: 6772 6f75 705f 3031 602c 2065 7463 2e2c  group_01`, etc.,
-00009020: 2066 6f72 206c 6172 6765 7220 6e75 6d62   for larger numb
-00009030: 6572 7320 6f66 2054 6173 6b20 4772 6f75  ers of Task Grou
-00009040: 7073 292e 2054 6173 6b20 4772 6f75 7020  ps). Task Group 
-00009050: 6e75 6d62 6572 7320 6361 6e20 616c 736f  numbers can also
-00009060: 2062 6520 696e 636c 7564 6564 2069 6e20   be included in 
-00009070: 7573 6572 2d64 6566 696e 6564 2054 6173  user-defined Tas
-00009080: 6b20 4772 6f75 7020 6e61 6d65 7320 7573  k Group names us
-00009090: 696e 6720 7468 6520 607b 7b74 6173 6b5f  ing the `{{task_
-000090a0: 6772 6f75 705f 6e75 6d62 6572 7d7d 6020  group_number}}` 
-000090b0: 7661 7269 6162 6c65 2073 7562 7374 6974  variable substit
-000090c0: 7574 696f 6e20 6469 7363 7573 7365 6420  ution discussed 
-000090d0: 6265 6c6f 772e 0a2d 202a 2a54 6173 6b2a  below..- **Task*
-000090e0: 2a20 6e61 6d65 7320 6172 6520 6175 746f  * names are auto
-000090f0: 6d61 7469 6361 6c6c 7920 6372 6561 7465  matically create
-00009100: 6420 666f 7220 616e 7920 5461 736b 2074  d for any Task t
-00009110: 6861 7420 6973 206e 6f74 2065 7870 6c69  hat is not expli
-00009120: 6369 746c 7920 6e61 6d65 642c 2075 7369  citly named, usi
-00009130: 6e67 206e 616d 6573 206f 6620 7468 6520  ng names of the 
-00009140: 666f 726d 2060 7461 736b 5f31 6020 286f  form `task_1` (o
-00009150: 7220 6074 6173 6b5f 3031 602c 2065 7463  r `task_01`, etc
-00009160: 2e2c 2066 6f72 206c 6172 6765 7220 6e75  ., for larger nu
-00009170: 6d62 6572 7320 6f66 2054 6173 6b73 292e  mbers of Tasks).
-00009180: 2054 6865 2054 6173 6b20 636f 756e 7465   The Task counte
-00009190: 7220 7265 7365 7473 2066 6f72 2065 6163  r resets for eac
-000091a0: 6820 6469 6666 6572 656e 7420 5461 736b  h different Task
-000091b0: 2047 726f 7570 2e20 5461 736b 206e 756d   Group. Task num
-000091c0: 6265 7273 2063 616e 2061 6c73 6f20 6265  bers can also be
-000091d0: 2069 6e63 6c75 6465 6420 696e 2075 7365   included in use
-000091e0: 722d 6465 6669 6e65 6420 5461 736b 206e  r-defined Task n
-000091f0: 616d 6573 2075 7369 6e67 2074 6865 2060  ames using the `
-00009200: 7b7b 7461 736b 5f6e 756d 6265 727d 7d60  {{task_number}}`
-00009210: 2076 6172 6961 626c 6520 7375 6273 7469   variable substi
-00009220: 7475 7469 6f6e 2064 6973 6375 7373 6564  tution discussed
-00009230: 2062 656c 6f77 2e0a 0a23 2323 2054 6173   below...### Tas
-00009240: 6b20 5479 7065 730a 0a2d 2049 6620 6074  k Types..- If `t
-00009250: 6173 6b54 7970 6560 2069 7320 7365 7420  askType` is set 
-00009260: 6f6e 6c79 2061 7420 7468 6520 544f 4d4c  only at the TOML
-00009270: 2066 696c 6520 6c65 7665 6c2c 2074 6865   file level, the
-00009280: 6e20 6074 6173 6b54 7970 6573 6020 6973  n `taskTypes` is
-00009290: 2061 7574 6f6d 6174 6963 616c 6c79 2070   automatically p
-000092a0: 6f70 756c 6174 6564 2066 6f72 2054 6173  opulated for Tas
-000092b0: 6b20 4772 6f75 7073 2c20 756e 6c65 7373  k Groups, unless
-000092c0: 206f 7665 7272 6964 6465 6e2e 0a2d 2049   overridden..- I
-000092d0: 6620 6074 6173 6b54 7970 6560 2069 7320  f `taskType` is 
-000092e0: 7365 7420 6174 2074 6865 2054 6173 6b20  set at the Task 
-000092f0: 6c65 7665 6c2c 2074 6865 6e20 6074 6173  level, then `tas
-00009300: 6b54 7970 6573 6020 6973 2061 7574 6f6d  kTypes` is autom
-00009310: 6174 6963 616c 6c79 2070 6f70 756c 6174  atically populat
-00009320: 6564 2066 6f72 2074 6865 2054 6173 6b20  ed for the Task 
-00009330: 4772 6f75 7073 206c 6576 656c 2075 7369  Groups level usi
-00009340: 6e67 2074 6865 2061 6363 756d 756c 6174  ng the accumulat
-00009350: 6564 2054 6173 6b20 5479 7065 7320 6672  ed Task Types fr
-00009360: 6f6d 2074 6865 2054 6173 6b73 2069 6e63  om the Tasks inc
-00009370: 6c75 6465 6420 696e 2065 6163 6820 5461  luded in each Ta
-00009380: 736b 2047 726f 7570 2c20 756e 6c65 7373  sk Group, unless
-00009390: 206f 7665 7272 6964 6465 6e2e 0a2d 2049   overridden..- I
-000093a0: 6620 6074 6173 6b54 7970 6573 6020 6973  f `taskTypes` is
-000093b0: 2073 6574 2061 7420 7468 6520 5461 736b   set at the Task
-000093c0: 2047 726f 7570 204c 6576 656c 2c20 616e   Group Level, an
-000093d0: 6420 6861 7320 6f6e 6c79 206f 6e65 2054  d has only one T
-000093e0: 6173 6b20 5479 7065 2065 6e74 7279 2c20  ask Type entry, 
-000093f0: 7468 656e 2060 7461 736b 5479 7065 6020  then `taskType` 
-00009400: 6973 2061 7574 6f6d 6174 6963 616c 6c79  is automatically
-00009410: 2073 6574 2061 7420 7468 6520 5461 736b   set at the Task
-00009420: 204c 6576 656c 2075 7369 6e67 2074 6865   Level using the
-00009430: 2073 696e 676c 6520 5461 736b 2054 7970   single Task Typ
-00009440: 652c 2075 6e6c 6573 7320 6f76 6572 7269  e, unless overri
-00009450: 6464 656e 2e0a 0a46 6f72 2074 6865 202a  dden...For the *
-00009460: 2a60 6261 7368 602a 2a2c 202a 2a60 706f  *`bash`**, **`po
-00009470: 7765 7273 6865 6c6c 602a 2a2c 202a 2a60  wershell`**, **`
-00009480: 636d 6460 2a2a 2f2a 2a60 6261 7460 2a2a  cmd`**/**`bat`**
-00009490: 2061 6e64 202a 2a60 646f 636b 6572 602a   and **`docker`*
-000094a0: 2a20 7461 736b 2074 7970 6573 2c20 736f  * task types, so
-000094b0: 6d65 2061 7574 6f6d 6174 6963 2070 726f  me automatic pro
-000094c0: 6365 7373 696e 6720 7769 6c6c 2062 6520  cessing will be 
-000094d0: 7065 7266 6f72 6d65 6420 6966 2074 6865  performed if the
-000094e0: 202a 2a60 6578 6563 7574 6162 6c65 602a   **`executable`*
-000094f0: 2a20 7072 6f70 6572 7479 2069 7320 7365  * property is se
-00009500: 742e 0a0a 2323 2323 2042 6173 682c 2050  t...#### Bash, P
-00009510: 7974 686f 6e2c 2050 6f77 6572 5368 656c  ython, PowerShel
-00009520: 6c20 616e 6420 636d 642f 6261 7420 5461  l and cmd/bat Ta
-00009530: 736b 730a 0a41 7320 6120 636f 6e76 656e  sks..As a conven
-00009540: 6965 6e63 652c 2066 6f72 2074 6865 202a  ience, for the *
-00009550: 2a60 6261 7368 602a 2a2c 202a 2a60 7079  *`bash`**, **`py
-00009560: 7468 6f6e 602a 2a2c 202a 2a60 706f 7765  thon`**, **`powe
-00009570: 7273 6865 6c6c 602a 2a2c 2061 6e64 202a  rshell`**, and *
-00009580: 2a60 636d 6460 2a2a 2028 6f72 202a 2a60  *`cmd`** (or **`
-00009590: 6261 7460 2a2a 2920 5461 736b 2054 7970  bat`**) Task Typ
-000095a0: 6573 2c20 7468 6520 7363 7269 7074 206e  es, the script n
-000095b0: 6f6d 696e 6174 6564 2069 6e20 7468 6520  ominated in the 
-000095c0: 2a2a 6065 7865 6375 7461 626c 6560 2a2a  **`executable`**
-000095d0: 2070 726f 7065 7274 7920 6973 2061 7574   property is aut
-000095e0: 6f6d 6174 6963 616c 6c79 2061 6464 6564  omatically added
-000095f0: 2074 6f20 7468 6520 6069 6e70 7574 7360   to the `inputs`
-00009600: 206c 6973 7420 2869 6620 6e6f 7420 616c   list (if not al
-00009610: 7265 6164 7920 7072 6573 656e 7429 2e20  ready present). 
-00009620: 5468 6973 206d 6561 6e73 2074 6865 2073  This means the s
-00009630: 6372 6970 7420 6669 6c65 2077 696c 6c20  cript file will 
-00009640: 6265 2075 706c 6f61 6465 6420 746f 2074  be uploaded to t
-00009650: 6865 204f 626a 6563 7420 5374 6f72 652c  he Object Store,
-00009660: 2061 6e64 206d 6164 6520 6120 7265 7175   and made a requ
-00009670: 6972 656d 656e 7420 6f66 2074 6865 2054  irement of the T
-00009680: 6173 6b20 7768 656e 2069 7420 7275 6e73  ask when it runs
-00009690: 2e0a 0a55 7369 6e67 2061 2042 6173 6820  ...Using a Bash 
-000096a0: 5461 736b 2061 7320 616e 2065 7861 6d70  Task as an examp
-000096b0: 6c65 2028 696e 2054 4f4d 4c20 666f 726d  le (in TOML form
-000096c0: 293a 0a0a 6060 6074 6f6d 6c0a 7461 736b  ):..```toml.task
-000096d0: 5479 7065 203d 2022 6261 7368 220a 6578  Type = "bash".ex
-000096e0: 6563 7574 6162 6c65 203d 2022 6d79 5f62  ecutable = "my_b
-000096f0: 6173 685f 7363 7269 7074 2e73 6822 0a61  ash_script.sh".a
-00009700: 7267 756d 656e 7473 203d 205b 2231 222c  rguments = ["1",
-00009710: 2022 3222 2c20 2233 225d 0a60 6060 0a69   "2", "3"].```.i
-00009720: 7320 6571 7569 7661 6c65 6e74 2074 6f3a  s equivalent to:
-00009730: 0a0a 6060 6074 6f6d 6c0a 7461 736b 5479  ..```toml.taskTy
-00009740: 7065 203d 2022 6261 7368 220a 696e 7075  pe = "bash".inpu
-00009750: 7473 203d 205b 226d 795f 6261 7368 5f73  ts = ["my_bash_s
-00009760: 6372 6970 742e 7368 225d 0a61 7267 756d  cript.sh"].argum
-00009770: 656e 7473 203d 205b 227b 7b77 725f 6e61  ents = ["{{wr_na
-00009780: 6d65 7d7d 2f6d 795f 6261 7368 5f73 6372  me}}/my_bash_scr
-00009790: 6970 742e 7368 222c 2022 3122 2c20 2232  ipt.sh", "1", "2
-000097a0: 222c 2022 3322 5d0a 6060 600a 0a49 6e20  ", "3"].```..In 
-000097b0: 7468 6520 6361 7365 206f 6620 5769 6e64  the case of Wind
-000097c0: 6f77 7320 6261 7463 6820 2860 2e62 6174  ows batch (`.bat
-000097d0: 6029 2066 696c 6573 2c20 6120 602f 6360  `) files, a `/c`
-000097e0: 2066 6c61 6720 6973 2070 7265 7065 6e64   flag is prepend
-000097f0: 6564 2074 6f20 7468 6520 6063 6d64 2e65  ed to the `cmd.e
-00009800: 7865 6020 6172 6775 6d65 6e74 206c 6973  xe` argument lis
-00009810: 7420 746f 2065 6e73 7572 6520 636f 7272  t to ensure corr
-00009820: 6563 7420 6578 6563 7574 696f 6e20 6261  ect execution ba
-00009830: 6861 7669 6f75 722e 2046 6f72 2065 7861  haviour. For exa
-00009840: 6d70 6c65 3a0a 0a60 6060 746f 6d6c 0a74  mple:..```toml.t
-00009850: 6173 6b54 7970 6520 3d20 2263 6d64 2220  askType = "cmd" 
-00009860: 2023 206f 7220 2262 6174 220a 6578 6563   # or "bat".exec
-00009870: 7574 6162 6c65 203d 2022 6d79 5f73 6372  utable = "my_scr
-00009880: 6970 742e 6261 7422 0a61 7267 756d 656e  ipt.bat".argumen
-00009890: 7473 203d 205b 2231 222c 2022 3222 2c20  ts = ["1", "2", 
-000098a0: 2233 225d 0a60 6060 0a0a 6973 2065 7175  "3"].```..is equ
-000098b0: 6976 616c 656e 7420 746f 3a0a 0a60 6060  ivalent to:..```
-000098c0: 746f 6d6c 0a74 6173 6b54 7970 6520 3d20  toml.taskType = 
-000098d0: 2263 6d64 2220 2023 206f 7220 2262 6174  "cmd"  # or "bat
-000098e0: 220a 696e 7075 7473 203d 205b 226d 795f  ".inputs = ["my_
-000098f0: 7363 7269 7074 2e62 6174 225d 0a61 7267  script.bat"].arg
-00009900: 756d 656e 7473 203d 205b 222f 6322 2c20  uments = ["/c", 
-00009910: 227b 7b77 725f 6e61 6d65 7d7d 5c5c 6d79  "{{wr_name}}\\my
-00009920: 5f73 6372 6970 742e 6261 7422 2c20 2231  _script.bat", "1
-00009930: 222c 2022 3222 2c20 2233 225d 0a60 6060  ", "2", "3"].```
-00009940: 0a0a 4e6f 7465 2074 6865 2060 5c5c 6020  ..Note the `\\` 
-00009950: 7265 7175 6972 656d 656e 7420 666f 7220  requirement for 
-00009960: 6469 7265 6374 6f72 7920 7365 7061 7261  directory separa
-00009970: 746f 7273 2077 6865 6e20 6465 6669 6e69  tors when defini
-00009980: 6e67 2054 6173 6b73 206f 6e20 5769 6e64  ng Tasks on Wind
-00009990: 6f77 7320 686f 7374 732e 204e 6f74 6520  ows hosts. Note 
-000099a0: 616c 736f 2074 6861 7420 7468 6520 602f  also that the `/
-000099b0: 6360 2069 7320 7265 7175 6972 6564 2077  c` is required w
-000099c0: 6865 6e20 7275 6e6e 696e 6720 636f 6d6d  hen running comm
-000099d0: 616e 6473 206f 7220 6261 7463 6820 7363  ands or batch sc
-000099e0: 7269 7074 7320 7573 696e 6720 6063 6d64  ripts using `cmd
-000099f0: 2e65 7865 602c 206f 7468 6572 7769 7365  .exe`, otherwise
-00009a00: 2074 6865 2060 636d 642e 6578 6560 2070   the `cmd.exe` p
-00009a10: 726f 6365 7373 2063 7265 6174 6564 2074  rocess created t
-00009a20: 6f20 6578 6563 7574 6520 7468 6520 5461  o execute the Ta
-00009a30: 736b 2077 696c 6c20 6e6f 7420 7465 726d  sk will not term
-00009a40: 696e 6174 652e 0a0a 2323 2323 2044 6f63  inate...#### Doc
-00009a50: 6b65 7220 5461 736b 730a 0a46 6f72 2074  ker Tasks..For t
-00009a60: 6865 202a 2a60 646f 636b 6572 602a 2a20  he **`docker`** 
-00009a70: 5461 736b 2054 7970 652c 2074 6865 2076  Task Type, the v
-00009a80: 6172 6961 626c 6573 2073 7570 706c 6965  ariables supplie
-00009a90: 6420 696e 2074 6865 2060 646f 636b 6572  d in the `docker
-00009aa0: 456e 7669 726f 6e6d 656e 7460 2070 726f  Environment` pro
-00009ab0: 7065 7274 7920 6172 6520 756e 7061 636b  perty are unpack
-00009ac0: 6564 2069 6e74 6f20 7468 6520 6172 6775  ed into the argu
-00009ad0: 6d65 6e74 206c 6973 7420 6173 2060 2d2d  ment list as `--
-00009ae0: 656e 7660 2065 6e74 7269 6573 2c20 7468  env` entries, th
-00009af0: 6520 446f 636b 6572 2063 6f6e 7461 696e  e Docker contain
-00009b00: 6572 206e 616d 6520 7375 7070 6c69 6564  er name supplied
-00009b10: 2069 6e20 7468 6520 6065 7865 6375 7461   in the `executa
-00009b20: 626c 6560 2070 726f 7065 7274 7920 6973  ble` property is
-00009b30: 2074 6865 6e20 6164 6465 6420 746f 2074   then added to t
-00009b40: 6865 2061 7267 756d 656e 7473 206c 6973  he arguments lis
-00009b50: 742c 2066 6f6c 6c6f 7765 6420 6279 2074  t, followed by t
-00009b60: 6865 2061 7267 756d 656e 7473 2073 7570  he arguments sup
-00009b70: 706c 6965 6420 696e 2074 6865 2060 6172  plied in the `ar
-00009b80: 6775 6d65 6e74 7360 2070 726f 7065 7274  guments` propert
-00009b90: 792e 2054 6865 2060 646f 636b 6572 5573  y. The `dockerUs
-00009ba0: 6572 6e61 6d65 6020 616e 6420 6064 6f63  ername` and `doc
-00009bb0: 6b65 7250 6173 7377 6f72 6460 2070 726f  kerPassword` pro
-00009bc0: 7065 7274 6965 732c 2069 6620 7375 7070  perties, if supp
-00009bd0: 6c69 6564 2c20 6172 6520 6164 6465 6420  lied, are added 
-00009be0: 746f 2074 6865 2060 656e 7669 726f 6e6d  to the `environm
-00009bf0: 656e 7460 2070 726f 7065 7274 792e 0a0a  ent` property...
-00009c00: 466f 7220 6578 616d 706c 653a 0a60 6060  For example:.```
-00009c10: 746f 6d6c 0a74 6173 6b54 7970 6520 3d20  toml.taskType = 
-00009c20: 2264 6f63 6b65 7222 0a65 7865 6375 7461  "docker".executa
-00009c30: 626c 6520 3d20 226d 795f 646f 636b 6572  ble = "my_docker
-00009c40: 6875 625f 7265 706f 2f6d 795f 636f 6e74  hub_repo/my_cont
-00009c50: 6169 6e65 725f 696d 6167 6522 0a64 6f63  ainer_image".doc
-00009c60: 6b65 7245 6e76 6972 6f6e 6d65 6e74 203d  kerEnvironment =
-00009c70: 207b 4531 203d 2022 4565 654f 6e65 227d   {E1 = "EeeOne"}
-00009c80: 0a64 6f63 6b65 7255 7365 726e 616d 6520  .dockerUsername 
-00009c90: 3d20 226d 795f 7573 6572 220a 646f 636b  = "my_user".dock
-00009ca0: 6572 5061 7373 776f 7264 203d 2022 6d79  erPassword = "my
-00009cb0: 5f70 6173 7377 6f72 6422 0a61 7267 756d  _password".argum
-00009cc0: 656e 7473 203d 205b 2231 222c 2022 3222  ents = ["1", "2"
-00009cd0: 2c20 2233 225d 0a60 6060 0a0a 6973 2065  , "3"].```..is e
-00009ce0: 7175 6976 616c 656e 7420 746f 2074 6865  quivalent to the
-00009cf0: 2066 6f6c 6c6f 7769 6e67 2062 6569 6e67   following being
-00009d00: 2073 656e 7420 666f 7220 7072 6f63 6573   sent for proces
-00009d10: 7369 6e67 2062 7920 7468 6520 6064 6f63  sing by the `doc
-00009d20: 6b65 7260 2054 6173 6b20 5479 7065 2c20  ker` Task Type, 
-00009d30: 7468 6520 5965 6c6c 6f77 446f 6720 7665  the YellowDog ve
-00009d40: 7273 696f 6e20 6f66 2077 6869 6368 2077  rsion of which w
-00009d50: 696c 6c20 6c6f 6720 696e 2074 6f20 7468  ill log in to th
-00009d60: 6520 446f 636b 6572 2072 6570 6f20 2869  e Docker repo (i
-00009d70: 6620 7265 7175 6972 6564 2920 7468 656e  f required) then
-00009d80: 2069 7373 7565 2061 2060 646f 636b 6572   issue a `docker
-00009d90: 2072 756e 6020 636f 6d6d 616e 6420 7769   run` command wi
-00009da0: 7468 2074 6865 2061 7267 756d 656e 7473  th the arguments
-00009db0: 2073 7570 706c 6965 643a 0a0a 6060 6074   supplied:..```t
-00009dc0: 6f6d 6c0a 7461 736b 5479 7065 203d 2022  oml.taskType = "
-00009dd0: 646f 636b 6572 220a 6172 6775 6d65 6e74  docker".argument
-00009de0: 7320 3d20 5b22 2d2d 656e 7620 4531 3d45  s = ["--env E1=E
-00009df0: 6565 4f6e 6522 2c20 226d 795f 646f 636b  eeOne", "my_dock
-00009e00: 6572 6875 6272 6570 6f2f 6d79 5f63 6f6e  erhubrepo/my_con
-00009e10: 7461 696e 6572 5f69 6d61 6765 222c 2022  tainer_image", "
-00009e20: 3122 2c20 2232 222c 2022 3322 5d0a 656e  1", "2", "3"].en
-00009e30: 7669 726f 6e6d 656e 7420 3d20 7b44 4f43  vironment = {DOC
-00009e40: 4b45 525f 5553 4552 4e41 4d45 203d 2022  KER_USERNAME = "
-00009e50: 6d79 5f75 7365 7222 2c20 444f 434b 4552  my_user", DOCKER
-00009e60: 5f50 4153 5357 4f52 4420 3d20 226d 795f  _PASSWORD = "my_
-00009e70: 7061 7373 776f 7264 227d 0a60 6060 0a0a  password"}.```..
-00009e80: 2323 2323 2042 6173 682c 2050 7974 686f  #### Bash, Pytho
-00009e90: 6e2c 2050 6f77 6572 5368 656c 6c2c 2063  n, PowerShell, c
-00009ea0: 6d64 2e65 7865 2f62 6174 6368 2c20 616e  md.exe/batch, an
-00009eb0: 6420 446f 636b 6572 2077 6974 686f 7574  d Docker without
-00009ec0: 2041 7574 6f6d 6174 6963 2050 726f 6365   Automatic Proce
-00009ed0: 7373 696e 670a 0a49 6620 7468 6520 6065  ssing..If the `e
-00009ee0: 7865 6375 7461 626c 6560 2070 726f 7065  xecutable` prope
-00009ef0: 7274 7920 6973 206e 6f74 2073 7570 706c  rty is not suppl
-00009f00: 6965 642c 2074 6865 2061 7574 6f6d 6174  ied, the automat
-00009f10: 6963 2070 726f 6365 7373 696e 6720 6465  ic processing de
-00009f20: 7363 7269 6265 6420 6162 6f76 6520 666f  scribed above fo
-00009f30: 7220 6062 6173 6860 2c20 6070 7974 686f  r `bash`, `pytho
-00009f40: 6e60 2c20 6070 6f77 6572 7368 656c 6c60  n`, `powershell`
-00009f50: 2c20 6063 6d64 6020 286f 7220 6062 6174  , `cmd` (or `bat
-00009f60: 6029 2061 6e64 2060 646f 636b 6572 6020  `) and `docker` 
-00009f70: 7461 736b 2074 7970 6573 2069 7320 6e6f  task types is no
-00009f80: 7420 6170 706c 6965 642e 0a0a 2323 2320  t applied...### 
-00009f90: 5461 736b 2043 6f75 6e74 730a 0a54 6869  Task Counts..Thi
-00009fa0: 7320 7072 6f70 6572 7479 2077 696c 6c20  s property will 
-00009fb0: 6578 7061 6e64 2074 6865 206e 756d 6265  expand the numbe
-00009fc0: 7220 6f66 2054 6173 6b73 2074 6f20 6d61  r of Tasks to ma
-00009fd0: 7463 6820 6074 6173 6b43 6f75 6e74 602e  tch `taskCount`.
-00009fe0: 0a0a 5468 6520 6074 6173 6b43 6f75 6e74  ..The `taskCount
-00009ff0: 6020 7072 6f70 6572 7479 2063 616e 2062  ` property can b
-0000a000: 6520 7365 7420 6f6e 6c79 2069 6e20 7468  e set only in th
-0000a010: 6520 6077 6f72 6b52 6571 7569 7265 6d65  e `workRequireme
-0000a020: 6e74 6020 7365 6374 696f 6e20 6f66 2074  nt` section of t
-0000a030: 6865 2060 636f 6e66 6967 2e74 6f6d 6c60  he `config.toml`
-0000a040: 2066 696c 652c 206f 7220 696e 2074 6865   file, or in the
-0000a050: 2060 7461 736b 4772 6f75 7060 2073 6563   `taskGroup` sec
-0000a060: 7469 6f6e 2873 2920 6f66 2061 204a 534f  tion(s) of a JSO
-0000a070: 4e20 576f 726b 2052 6571 7569 7265 6d65  N Work Requireme
-0000a080: 6e74 2064 6566 696e 6974 696f 6e2e 0a0a  nt definition...
-0000a090: 496e 2074 6865 2066 6f72 6d65 7220 6361  In the former ca
-0000a0a0: 7365 2c20 7468 6520 6074 6173 6b43 6f75  se, the `taskCou
-0000a0b0: 6e74 6020 6170 706c 6965 7320 6f6e 6c79  nt` applies only
-0000a0c0: 2074 6f20 7468 6520 5461 736b 2073 7065   to the Task spe
-0000a0d0: 6369 6669 6564 2077 6974 6869 6e20 7468  cified within th
-0000a0e0: 6520 6063 6f6e 6669 672e 746f 6d6c 6020  e `config.toml` 
-0000a0f0: 6669 6c65 2061 6e64 2069 7320 6e6f 7420  file and is not 
-0000a100: 696e 6865 7269 7465 6420 6279 204a 534f  inherited by JSO
-0000a110: 4e20 576f 726b 2052 6571 7569 7265 6d65  N Work Requireme
-0000a120: 6e74 2073 7065 6369 6669 6361 7469 6f6e  nt specification
-0000a130: 732e 0a0a 496e 2074 6865 206c 6174 7465  s...In the latte
-0000a140: 7220 6361 7365 2c20 7468 6520 6074 6173  r case, the `tas
-0000a150: 6b43 6f75 6e74 6020 6170 706c 6965 7320  kCount` applies 
-0000a160: 746f 2074 6865 2054 6173 6b20 7370 6563  to the Task spec
-0000a170: 6966 6965 6420 7769 7468 696e 2074 6865  ified within the
-0000a180: 2054 6173 6b20 4772 6f75 702c 2061 6e64   Task Group, and
-0000a190: 2074 6865 7265 206d 7573 7420 6265 207a   there must be z
-0000a1a0: 6572 6f20 6f72 206f 6e65 2054 6173 6b28  ero or one Task(
-0000a1b0: 7329 206c 6973 7465 6420 7769 7468 696e  s) listed within
-0000a1c0: 2074 6865 2067 726f 7570 206f 7220 6074   the group or `t
-0000a1d0: 6173 6b43 6f75 6e74 6020 6973 2069 676e  askCount` is ign
-0000a1e0: 6f72 6564 2e0a 0a23 2320 4578 616d 706c  ored...## Exampl
-0000a1f0: 6573 0a0a 2323 2320 544f 4d4c 2050 726f  es..### TOML Pro
-0000a200: 7065 7274 6965 7320 696e 2074 6865 2060  perties in the `
-0000a210: 776f 726b 5265 7175 6972 656d 656e 7460  workRequirement`
-0000a220: 2053 6563 7469 6f6e 0a0a 4865 7265 2773   Section..Here's
-0000a230: 2061 6e20 6578 616d 706c 6520 6f66 2074   an example of t
-0000a240: 6865 2060 776f 726b 5265 7175 6972 656d  he `workRequirem
-0000a250: 656e 7460 2073 6563 7469 6f6e 206f 6620  ent` section of 
-0000a260: 6120 544f 4d4c 2063 6f6e 6669 6775 7261  a TOML configura
-0000a270: 7469 6f6e 2066 696c 652c 2073 686f 7769  tion file, showi
-0000a280: 6e67 2061 6c6c 2074 6865 2070 6f73 7369  ng all the possi
-0000a290: 626c 6520 7072 6f70 6572 7469 6573 2074  ble properties t
-0000a2a0: 6861 7420 6361 6e20 6265 2073 6574 3a0a  hat can be set:.
-0000a2b0: 0a60 6060 746f 6d6c 0a5b 776f 726b 5265  .```toml.[workRe
-0000a2c0: 7175 6972 656d 656e 745d 0a20 2020 2061  quirement].    a
-0000a2d0: 7267 756d 656e 7473 203d 205b 2231 222c  rguments = ["1",
-0000a2e0: 2022 5457 4f22 5d0a 2020 2020 6361 7074   "TWO"].    capt
-0000a2f0: 7572 6554 6173 6b4f 7574 7075 7420 3d20  ureTaskOutput = 
-0000a300: 7472 7565 0a20 2020 2063 6f6d 706c 6574  true.    complet
-0000a310: 6564 5461 736b 5474 6c20 3d20 3130 0a20  edTaskTtl = 10. 
-0000a320: 2020 2063 7376 4669 6c65 203d 2022 6669     csvFile = "fi
-0000a330: 6c65 312e 6373 7622 0a20 2020 2063 7376  le1.csv".    csv
-0000a340: 4669 6c65 7320 3d20 5b22 6669 6c65 312e  Files = ["file1.
-0000a350: 6373 7622 2c20 2266 696c 6533 2e63 7376  csv", "file3.csv
-0000a360: 3a33 225d 0a20 2020 2064 6f63 6b65 7245  :3"].    dockerE
-0000a370: 6e76 6972 6f6e 6d65 6e74 203d 207b 4d59  nvironment = {MY
-0000a380: 5f44 4f43 4b45 525f 5641 5220 3d20 3130  _DOCKER_VAR = 10
-0000a390: 307d 0a20 2020 2064 6f63 6b65 7250 6173  0}.    dockerPas
-0000a3a0: 7377 6f72 6420 3d20 226d 7950 6173 7377  sword = "myPassw
-0000a3b0: 6f72 6422 0a20 2020 2064 6f63 6b65 7255  ord".    dockerU
-0000a3c0: 7365 726e 616d 6520 3d20 226d 7955 7365  sername = "myUse
-0000a3d0: 726e 616d 6522 0a20 2020 2065 6e76 6972  rname".    envir
-0000a3e0: 6f6e 6d65 6e74 203d 207b 4d59 5f56 4152  onment = {MY_VAR
-0000a3f0: 203d 2031 3030 7d0a 2020 2020 6578 636c   = 100}.    excl
-0000a400: 7573 6976 6557 6f72 6b65 7273 203d 2066  usiveWorkers = f
-0000a410: 616c 7365 0a20 2020 2065 7865 6375 7461  alse.    executa
-0000a420: 626c 6520 3d20 226d 792d 636f 6e74 6169  ble = "my-contai
-0000a430: 6e65 7222 0a20 2020 2066 696e 6973 6849  ner".    finishI
-0000a440: 6641 6c6c 5461 736b 7346 696e 6973 6865  fAllTasksFinishe
-0000a450: 6420 3d20 7472 7565 0a20 2020 2066 696e  d = true.    fin
-0000a460: 6973 6849 6641 6e79 5461 736b 4661 696c  ishIfAnyTaskFail
-0000a470: 6564 203d 2066 616c 7365 0a20 2020 2066  ed = false.    f
-0000a480: 6c61 7474 656e 496e 7075 7450 6174 6873  lattenInputPaths
-0000a490: 203d 2066 616c 7365 0a20 2020 2066 6c61   = false.    fla
-0000a4a0: 7474 656e 5570 6c6f 6164 5061 7468 7320  ttenUploadPaths 
-0000a4b0: 3d20 6661 6c73 650a 2020 2020 6675 6c66  = false.    fulf
-0000a4c0: 696c 4f6e 5375 626d 6974 203d 2066 616c  ilOnSubmit = fal
-0000a4d0: 7365 0a20 2020 2069 6e70 7574 7320 3d20  se.    inputs = 
-0000a4e0: 5b0a 2020 2020 2020 2020 222e 2e2f 6170  [.        "../ap
-0000a4f0: 702f 6d61 696e 2e70 7922 2c0a 2020 2020  p/main.py",.    
-0000a500: 2020 2020 222e 2e2f 6170 702f 7265 7175      "../app/requ
-0000a510: 6972 656d 656e 7473 2e74 7874 220a 2020  irements.txt".  
-0000a520: 2020 5d0a 2020 2020 696e 7075 7473 4f70    ].    inputsOp
-0000a530: 7469 6f6e 616c 203d 205b 226f 7074 696f  tional = ["optio
-0000a540: 6e61 6c2e 7478 7422 5d0a 2020 2020 696e  nal.txt"].    in
-0000a550: 7374 616e 6365 5479 7065 7320 3d20 5b22  stanceTypes = ["
-0000a560: 7433 612e 6d69 6372 6f22 2c20 2274 332e  t3a.micro", "t3.
-0000a570: 6d69 6372 6f22 5d0a 2020 2020 6d61 7857  micro"].    maxW
-0000a580: 6f72 6b65 7273 203d 2031 0a20 2020 206d  orkers = 1.    m
-0000a590: 6178 696d 756d 5461 736b 5265 7472 6965  aximumTaskRetrie
-0000a5a0: 7320 3d20 300a 2020 2020 6d69 6e57 6f72  s = 0.    minWor
-0000a5b0: 6b65 7273 203d 2031 0a20 2020 206e 616d  kers = 1.    nam
-0000a5c0: 6520 3d20 226d 792d 776f 726b 2d72 6571  e = "my-work-req
-0000a5d0: 7569 7265 6d65 6e74 220a 2020 2020 6f75  uirement".    ou
-0000a5e0: 7470 7574 7320 3d20 5b22 7265 7375 6c74  tputs = ["result
-0000a5f0: 732e 7478 7422 5d0a 2020 2020 6f75 7470  s.txt"].    outp
-0000a600: 7574 7352 6571 7569 7265 6420 3d20 5b22  utsRequired = ["
-0000a610: 7265 7375 6c74 735f 7265 7175 6972 6564  results_required
-0000a620: 2e74 7874 225d 0a20 2020 2070 7269 6f72  .txt"].    prior
-0000a630: 6974 7920 3d20 302e 300a 2020 2020 7072  ity = 0.0.    pr
-0000a640: 6f76 6964 6572 7320 3d20 5b22 4157 5322  oviders = ["AWS"
-0000a650: 5d0a 2020 2020 7261 6d20 3d20 5b30 2e35  ].    ram = [0.5
-0000a660: 2c20 322e 305d 0a20 2020 2072 6567 696f  , 2.0].    regio
-0000a670: 6e73 203d 205b 2265 752d 7765 7374 2d32  ns = ["eu-west-2
-0000a680: 225d 0a20 2020 2074 6173 6b42 6174 6368  "].    taskBatch
-0000a690: 5369 7a65 203d 2031 3030 300a 2020 2020  Size = 1000.    
-0000a6a0: 7461 736b 436f 756e 7420 3d20 3130 300a  taskCount = 100.
-0000a6b0: 2020 2020 7461 736b 4461 7461 203d 2022      taskData = "
-0000a6c0: 6d79 5f64 6174 615f 7374 7269 6e67 220a  my_data_string".
-0000a6d0: 2020 2020 7461 736b 4461 7461 4669 6c65      taskDataFile
-0000a6e0: 203d 2022 6d79 5f64 6174 615f 6669 6c65   = "my_data_file
-0000a6f0: 2e74 7874 220a 2020 2020 7461 736b 4e61  .txt".    taskNa
-0000a700: 6d65 203d 2022 6d79 5f74 6173 6b5f 6e75  me = "my_task_nu
-0000a710: 6d62 6572 5f7b 7b74 6173 6b5f 6e75 6d62  mber_{{task_numb
-0000a720: 6572 7d7d 220a 2020 2020 7461 736b 4772  er}}".    taskGr
-0000a730: 6f75 704e 616d 6520 3d20 226d 795f 7461  oupName = "my_ta
-0000a740: 736b 5f67 726f 7570 5f6e 756d 6265 725f  sk_group_number_
-0000a750: 7b7b 7461 736b 5f67 726f 7570 5f6e 756d  {{task_group_num
-0000a760: 6265 727d 7d22 0a20 2020 2074 6173 6b54  ber}}".    taskT
-0000a770: 7970 6520 3d20 2264 6f63 6b65 7222 0a20  ype = "docker". 
-0000a780: 2020 2074 6173 6b73 5065 7257 6f72 6b65     tasksPerWorke
-0000a790: 7220 3d20 310a 2020 2020 7570 6c6f 6164  r = 1.    upload
-0000a7a0: 4669 6c65 7320 3d20 5b7b 6c6f 6361 6c50  Files = [{localP
-0000a7b0: 6174 6820 3d20 2266 696c 655f 312e 7478  ath = "file_1.tx
-0000a7c0: 7422 2c20 7570 6c6f 6164 5061 7468 203d  t", uploadPath =
-0000a7d0: 2022 6669 6c65 5f31 2e74 7874 227d 5d0a   "file_1.txt"}].
-0000a7e0: 2020 2020 7663 7075 7320 3d20 5b31 2c20      vcpus = [1, 
-0000a7f0: 345d 0a20 2020 2076 6572 6966 7941 7453  4].    verifyAtS
-0000a800: 7461 7274 203d 205b 2272 6561 6479 5f72  tart = ["ready_r
-0000a810: 6573 756c 7473 2e74 7874 225d 0a20 2020  esults.txt"].   
-0000a820: 2076 6572 6966 7957 6169 7420 3d20 5b22   verifyWait = ["
-0000a830: 7761 6974 5f66 6f72 5f72 6573 756c 7473  wait_for_results
-0000a840: 2e74 7874 225d 0a20 2020 2077 6f72 6b65  .txt"].    worke
-0000a850: 7254 6167 7320 3d20 5b22 7461 672d 7b7b  rTags = ["tag-{{
-0000a860: 7573 6572 6e61 6d65 7d7d 225d 0a20 2020  username}}"].   
-0000a870: 2077 6f72 6b52 6571 7569 7265 6d65 6e74   workRequirement
-0000a880: 4461 7461 203d 2022 776f 726b 5f72 6571  Data = "work_req
-0000a890: 7569 7265 6d65 6e74 2e6a 736f 6e22 0a60  uirement.json".`
-0000a8a0: 6060 0a0a 2323 2320 4a53 4f4e 2050 726f  ``..### JSON Pro
-0000a8b0: 7065 7274 6965 7320 6174 2074 6865 2057  perties at the W
-0000a8c0: 6f72 6b20 5265 7175 6972 656d 656e 7420  ork Requirement 
-0000a8d0: 4c65 7665 6c0a 0a53 686f 7769 6e67 2061  Level..Showing a
-0000a8e0: 6c6c 2070 6f73 7369 626c 6520 7072 6f70  ll possible prop
-0000a8f0: 6572 7469 6573 2061 7420 7468 6520 576f  erties at the Wo
-0000a900: 726b 2052 6571 7569 7265 6d65 6e74 206c  rk Requirement l
-0000a910: 6576 656c 3a0a 0a60 6060 6a73 6f6e 0a7b  evel:..```json.{
-0000a920: 0a20 2022 6172 6775 6d65 6e74 7322 3a20  .  "arguments": 
-0000a930: 5b31 2c20 2254 574f 225d 2c0a 2020 2263  [1, "TWO"],.  "c
-0000a940: 6170 7475 7265 5461 736b 4f75 7470 7574  aptureTaskOutput
-0000a950: 223a 2074 7275 652c 0a20 2022 636f 6d70  ": true,.  "comp
-0000a960: 6c65 7465 6454 6173 6b54 746c 223a 2031  letedTaskTtl": 1
-0000a970: 302c 0a20 2022 646f 636b 6572 456e 7669  0,.  "dockerEnvi
-0000a980: 726f 6e6d 656e 7422 3a20 7b22 4d59 5f44  ronment": {"MY_D
-0000a990: 4f43 4b45 525f 5641 5222 3a20 3130 307d  OCKER_VAR": 100}
-0000a9a0: 2c0a 2020 2264 6f63 6b65 7250 6173 7377  ,.  "dockerPassw
-0000a9b0: 6f72 6422 3a20 226d 7950 6173 7377 6f72  ord": "myPasswor
-0000a9c0: 6422 2c0a 2020 2264 6f63 6b65 7255 7365  d",.  "dockerUse
-0000a9d0: 726e 616d 6522 3a20 226d 7955 7365 726e  rname": "myUsern
-0000a9e0: 616d 6522 2c0a 2020 2265 6e76 6972 6f6e  ame",.  "environ
-0000a9f0: 6d65 6e74 223a 207b 224d 595f 5641 5222  ment": {"MY_VAR"
-0000aa00: 3a20 3130 307d 2c0a 2020 2265 7863 6c75  : 100},.  "exclu
-0000aa10: 7369 7665 576f 726b 6572 7322 3a20 6661  siveWorkers": fa
-0000aa20: 6c73 652c 0a20 2022 6578 6563 7574 6162  lse,.  "executab
-0000aa30: 6c65 223a 2022 6d79 2d63 6f6e 7461 696e  le": "my-contain
-0000aa40: 6572 222c 0a20 2022 6669 6e69 7368 4966  er",.  "finishIf
-0000aa50: 416c 6c54 6173 6b73 4669 6e69 7368 6564  AllTasksFinished
-0000aa60: 223a 2074 7275 652c 0a20 2022 6669 6e69  ": true,.  "fini
-0000aa70: 7368 4966 416e 7954 6173 6b46 6169 6c65  shIfAnyTaskFaile
-0000aa80: 6422 3a20 6661 6c73 652c 0a20 2022 666c  d": false,.  "fl
-0000aa90: 6174 7465 6e49 6e70 7574 5061 7468 7322  attenInputPaths"
-0000aaa0: 3a20 6661 6c73 652c 0a20 2022 666c 6174  : false,.  "flat
-0000aab0: 7465 6e55 706c 6f61 6450 6174 6873 223a  tenUploadPaths":
-0000aac0: 2066 616c 7365 2c0a 2020 2266 756c 6669   false,.  "fulfi
-0000aad0: 6c4f 6e53 7562 6d69 7422 3a20 6661 6c73  lOnSubmit": fals
-0000aae0: 652c 0a20 2022 696e 7075 7473 223a 205b  e,.  "inputs": [
-0000aaf0: 2261 7070 2f6d 6169 6e2e 7079 222c 2022  "app/main.py", "
-0000ab00: 6170 702f 7265 7175 6972 656d 656e 7473  app/requirements
-0000ab10: 2e74 7874 225d 2c0a 2020 2269 6e70 7574  .txt"],.  "input
-0000ab20: 734f 7074 696f 6e61 6c22 3a20 5b22 6f70  sOptional": ["op
-0000ab30: 7469 6f6e 616c 2e74 7874 225d 2c0a 2020  tional.txt"],.  
-0000ab40: 2269 6e73 7461 6e63 6554 7970 6573 223a  "instanceTypes":
-0000ab50: 205b 2274 3361 2e6d 6963 726f 222c 2022   ["t3a.micro", "
-0000ab60: 7433 2e6d 6963 726f 225d 2c0a 2020 226d  t3.micro"],.  "m
-0000ab70: 6178 576f 726b 6572 7322 3a20 312c 0a20  axWorkers": 1,. 
-0000ab80: 2022 6d61 7869 6d75 6d54 6173 6b52 6574   "maximumTaskRet
-0000ab90: 7269 6573 223a 2030 2c0a 2020 226d 696e  ries": 0,.  "min
-0000aba0: 576f 726b 6572 7322 3a20 312c 0a20 2022  Workers": 1,.  "
-0000abb0: 6e61 6d65 223a 2022 6d79 2d77 6f72 6b2d  name": "my-work-
-0000abc0: 7265 7175 6972 656d 656e 7422 2c0a 2020  requirement",.  
-0000abd0: 226f 7574 7075 7473 223a 205b 2272 6573  "outputs": ["res
-0000abe0: 756c 7473 2e74 7874 225d 2c0a 2020 226f  ults.txt"],.  "o
-0000abf0: 7574 7075 7473 5265 7175 6972 6564 223a  utputsRequired":
-0000ac00: 205b 2272 6573 756c 7473 5f72 6571 7569   ["results_requi
-0000ac10: 7265 642e 7478 7422 5d2c 0a20 2022 7072  red.txt"],.  "pr
-0000ac20: 696f 7269 7479 223a 2030 2e30 2c0a 2020  iority": 0.0,.  
-0000ac30: 2270 726f 7669 6465 7273 223a 205b 2241  "providers": ["A
-0000ac40: 5753 225d 2c0a 2020 2272 616d 223a 205b  WS"],.  "ram": [
-0000ac50: 302e 352c 2032 5d2c 0a20 2022 7265 6769  0.5, 2],.  "regi
-0000ac60: 6f6e 7322 3a20 5b22 6575 2d77 6573 742d  ons": ["eu-west-
-0000ac70: 3222 5d2c 0a20 2022 7461 736b 4461 7461  2"],.  "taskData
-0000ac80: 223a 2022 6d79 5f74 6173 6b5f 6461 7461  ": "my_task_data
-0000ac90: 5f73 7472 696e 6722 2c0a 2020 2274 6173  _string",.  "tas
-0000aca0: 6b44 6174 6146 696c 6522 3a20 226d 795f  kDataFile": "my_
-0000acb0: 6461 7461 5f66 696c 652e 7478 7422 2c0a  data_file.txt",.
-0000acc0: 2020 2274 6173 6b54 7970 6573 223a 205b    "taskTypes": [
-0000acd0: 2264 6f63 6b65 7222 5d2c 0a20 2022 7461  "docker"],.  "ta
-0000ace0: 736b 7350 6572 576f 726b 6572 223a 2031  sksPerWorker": 1
-0000acf0: 2c0a 2020 2275 706c 6f61 6446 696c 6573  ,.  "uploadFiles
-0000ad00: 223a 205b 7b22 6c6f 6361 6c50 6174 6822  ": [{"localPath"
-0000ad10: 3a20 2266 696c 655f 312e 7478 7422 2c20  : "file_1.txt", 
-0000ad20: 2275 706c 6f61 6450 6174 6822 3a20 2266  "uploadPath": "f
-0000ad30: 696c 655f 312e 7478 7422 7d5d 2c0a 2020  ile_1.txt"}],.  
-0000ad40: 2276 6370 7573 223a 205b 312c 2034 5d2c  "vcpus": [1, 4],
-0000ad50: 0a20 2022 7665 7269 6679 4174 5374 6172  .  "verifyAtStar
-0000ad60: 7422 3a20 5b22 7265 6164 795f 7265 7375  t": ["ready_resu
-0000ad70: 6c74 732e 7478 7422 5d2c 0a20 2022 7665  lts.txt"],.  "ve
-0000ad80: 7269 6679 5761 6974 223a 205b 2277 6169  rifyWait": ["wai
-0000ad90: 745f 666f 725f 7265 7375 6c74 732e 7478  t_for_results.tx
-0000ada0: 7422 5d2c 0a20 2022 776f 726b 6572 5461  t"],.  "workerTa
-0000adb0: 6773 223a 205b 5d2c 0a20 2022 7461 736b  gs": [],.  "task
-0000adc0: 4772 6f75 7073 223a 205b 0a20 2020 207b  Groups": [.    {
-0000add0: 0a20 2020 2020 2022 7461 736b 7322 3a20  .      "tasks": 
-0000ade0: 5b0a 2020 2020 2020 2020 7b7d 0a20 2020  [.        {}.   
-0000adf0: 2020 205d 0a20 2020 207d 0a20 205d 0a7d     ].    }.  ].}
-0000ae00: 0a0a 6060 600a 0a23 2323 204a 534f 4e20  ..```..### JSON 
-0000ae10: 5072 6f70 6572 7469 6573 2061 7420 7468  Properties at th
-0000ae20: 6520 5461 736b 2047 726f 7570 204c 6576  e Task Group Lev
-0000ae30: 656c 0a0a 5368 6f77 696e 6720 616c 6c20  el..Showing all 
-0000ae40: 706f 7373 6962 6c65 2070 726f 7065 7274  possible propert
-0000ae50: 6965 7320 6174 2074 6865 2054 6173 6b20  ies at the Task 
-0000ae60: 4772 6f75 7020 6c65 7665 6c3a 0a0a 6060  Group level:..``
-0000ae70: 606a 736f 6e0a 7b0a 2020 2274 6173 6b47  `json.{.  "taskG
-0000ae80: 726f 7570 7322 3a20 5b0a 2020 2020 7b0a  roups": [.    {.
-0000ae90: 2020 2020 2020 2261 7267 756d 656e 7473        "arguments
-0000aea0: 223a 205b 312c 2022 5457 4f22 5d2c 0a20  ": [1, "TWO"],. 
-0000aeb0: 2020 2020 2022 6361 7074 7572 6554 6173       "captureTas
-0000aec0: 6b4f 7574 7075 7422 3a20 7472 7565 2c0a  kOutput": true,.
-0000aed0: 2020 2020 2020 2263 6f6d 706c 6574 6564        "completed
-0000aee0: 5461 736b 5474 6c22 3a20 3130 2c0a 2020  TaskTtl": 10,.  
-0000aef0: 2020 2020 2264 6f63 6b65 7245 6e76 6972      "dockerEnvir
-0000af00: 6f6e 6d65 6e74 223a 207b 224d 595f 444f  onment": {"MY_DO
-0000af10: 434b 4552 5f56 4152 223a 2031 3030 7d2c  CKER_VAR": 100},
-0000af20: 0a20 2020 2020 2022 646f 636b 6572 5061  .      "dockerPa
-0000af30: 7373 776f 7264 223a 2022 6d79 5061 7373  ssword": "myPass
-0000af40: 776f 7264 222c 0a20 2020 2020 2022 646f  word",.      "do
-0000af50: 636b 6572 5573 6572 6e61 6d65 223a 2022  ckerUsername": "
-0000af60: 6d79 5573 6572 6e61 6d65 222c 0a20 2020  myUsername",.   
-0000af70: 2020 2022 656e 7669 726f 6e6d 656e 7422     "environment"
-0000af80: 3a20 7b22 4d59 5f56 4152 223a 2031 3030  : {"MY_VAR": 100
-0000af90: 7d2c 0a20 2020 2020 2022 6578 636c 7573  },.      "exclus
-0000afa0: 6976 6557 6f72 6b65 7273 223a 2066 616c  iveWorkers": fal
-0000afb0: 7365 2c0a 2020 2020 2020 2265 7865 6375  se,.      "execu
-0000afc0: 7461 626c 6522 3a20 226d 792d 636f 6e74  table": "my-cont
-0000afd0: 6169 6e65 7222 2c0a 2020 2020 2020 2266  ainer",.      "f
-0000afe0: 696e 6973 6849 6641 6c6c 5461 736b 7346  inishIfAllTasksF
-0000aff0: 696e 6973 6865 6422 3a20 7472 7565 2c0a  inished": true,.
-0000b000: 2020 2020 2020 2266 696e 6973 6849 6641        "finishIfA
-0000b010: 6e79 5461 736b 4661 696c 6564 223a 2066  nyTaskFailed": f
-0000b020: 616c 7365 2c0a 2020 2020 2020 2266 6c61  alse,.      "fla
-0000b030: 7474 656e 496e 7075 7450 6174 6873 223a  ttenInputPaths":
-0000b040: 2066 616c 7365 2c0a 2020 2020 2020 2269   false,.      "i
-0000b050: 6e70 7574 7322 3a20 5b22 6170 702f 6d61  nputs": ["app/ma
-0000b060: 696e 2e70 7922 2c20 2261 7070 2f72 6571  in.py", "app/req
-0000b070: 7569 7265 6d65 6e74 732e 7478 7422 5d2c  uirements.txt"],
-0000b080: 0a20 2020 2020 2022 696e 7075 7473 4f70  .      "inputsOp
-0000b090: 7469 6f6e 616c 223a 205b 226f 7074 696f  tional": ["optio
-0000b0a0: 6e61 6c2e 7478 7422 5d2c 0a20 2020 2020  nal.txt"],.     
-0000b0b0: 2022 696e 7374 616e 6365 5479 7065 7322   "instanceTypes"
-0000b0c0: 3a20 5b22 7433 612e 6d69 6372 6f22 2c20  : ["t3a.micro", 
-0000b0d0: 2274 332e 6d69 6372 6f22 5d2c 0a20 2020  "t3.micro"],.   
-0000b0e0: 2020 2022 6d61 7869 6d75 6d54 6173 6b52     "maximumTaskR
-0000b0f0: 6574 7269 6573 223a 2030 2c0a 2020 2020  etries": 0,.    
-0000b100: 2020 226d 6178 576f 726b 6572 7322 3a20    "maxWorkers": 
-0000b110: 312c 0a20 2020 2020 2022 6d69 6e57 6f72  1,.      "minWor
-0000b120: 6b65 7273 223a 2031 2c0a 2020 2020 2020  kers": 1,.      
-0000b130: 226e 616d 6522 3a20 2266 6972 7374 2d74  "name": "first-t
-0000b140: 6173 6b2d 6772 6f75 7022 2c0a 2020 2020  ask-group",.    
-0000b150: 2020 226f 7574 7075 7473 223a 205b 2272    "outputs": ["r
-0000b160: 6573 756c 7473 2e74 7874 225d 2c0a 2020  esults.txt"],.  
-0000b170: 2020 2020 226f 7574 7075 7473 5265 7175      "outputsRequ
-0000b180: 6972 6564 223a 205b 2272 6573 756c 7473  ired": ["results
-0000b190: 5f72 6571 7569 7265 642e 7478 7422 5d2c  _required.txt"],
-0000b1a0: 0a20 2020 2020 2022 7072 696f 7269 7479  .      "priority
-0000b1b0: 223a 2030 2e30 2c0a 2020 2020 2020 2270  ": 0.0,.      "p
-0000b1c0: 726f 7669 6465 7273 223a 205b 2241 5753  roviders": ["AWS
-0000b1d0: 225d 2c0a 2020 2020 2020 2272 616d 223a  "],.      "ram":
-0000b1e0: 205b 302e 352c 2032 5d2c 0a20 2020 2020   [0.5, 2],.     
-0000b1f0: 2022 7265 6769 6f6e 7322 3a20 5b22 6575   "regions": ["eu
-0000b200: 2d77 6573 742d 3222 5d2c 0a20 2020 2020  -west-2"],.     
-0000b210: 2022 7461 736b 436f 756e 7422 3a20 352c   "taskCount": 5,
-0000b220: 0a20 2020 2020 2022 7461 736b 4461 7461  .      "taskData
-0000b230: 223a 2022 6d79 5f74 6173 6b5f 6461 7461  ": "my_task_data
-0000b240: 5f73 7472 696e 6722 2c0a 2020 2020 2020  _string",.      
-0000b250: 2274 6173 6b44 6174 6146 696c 6522 3a20  "taskDataFile": 
-0000b260: 226d 795f 6461 7461 5f66 696c 652e 7478  "my_data_file.tx
-0000b270: 7422 2c0a 2020 2020 2020 2274 6173 6b54  t",.      "taskT
-0000b280: 7970 6573 223a 205b 2264 6f63 6b65 7222  ypes": ["docker"
-0000b290: 5d2c 0a20 2020 2020 2022 7461 736b 7350  ],.      "tasksP
-0000b2a0: 6572 576f 726b 6572 223a 2031 2c0a 2020  erWorker": 1,.  
-0000b2b0: 2020 2020 2275 706c 6f61 6446 696c 6573      "uploadFiles
-0000b2c0: 223a 205b 7b22 6c6f 6361 6c50 6174 6822  ": [{"localPath"
-0000b2d0: 3a20 2266 696c 655f 312e 7478 7422 2c20  : "file_1.txt", 
-0000b2e0: 2275 706c 6f61 6450 6174 6822 3a20 2266  "uploadPath": "f
-0000b2f0: 696c 655f 312e 7478 7422 7d5d 2c0a 2020  ile_1.txt"}],.  
-0000b300: 2020 2020 2276 6370 7573 223a 205b 312c      "vcpus": [1,
-0000b310: 2034 5d2c 0a20 2020 2020 2022 7665 7269   4],.      "veri
-0000b320: 6679 4174 5374 6172 7422 3a20 5b22 7265  fyAtStart": ["re
-0000b330: 6164 795f 7265 7375 6c74 732e 7478 7422  ady_results.txt"
-0000b340: 5d2c 0a20 2020 2020 2022 7665 7269 6679  ],.      "verify
-0000b350: 5761 6974 223a 205b 2277 6169 745f 666f  Wait": ["wait_fo
-0000b360: 725f 7265 7375 6c74 732e 7478 7422 5d2c  r_results.txt"],
-0000b370: 0a20 2020 2020 2022 776f 726b 6572 5461  .      "workerTa
-0000b380: 6773 223a 205b 5d2c 0a20 2020 2020 2022  gs": [],.      "
-0000b390: 7461 736b 7322 3a20 5b0a 2020 2020 2020  tasks": [.      
-0000b3a0: 2020 7b7d 0a20 2020 2020 205d 0a20 2020    {}.      ].   
-0000b3b0: 207d 2c0a 2020 2020 7b0a 2020 2020 2020   },.    {.      
-0000b3c0: 226e 616d 6522 3a20 2273 6563 6f6e 642d  "name": "second-
-0000b3d0: 7461 736b 2d67 726f 7570 222c 0a20 2020  task-group",.   
-0000b3e0: 2020 2022 6465 7065 6e64 656e 744f 6e22     "dependentOn"
-0000b3f0: 3a20 2266 6972 7374 2d74 6173 6b2d 6772  : "first-task-gr
-0000b400: 6f75 7022 2c0a 2020 2020 2020 2274 6173  oup",.      "tas
-0000b410: 6b73 223a 205b 0a20 2020 2020 2020 207b  ks": [.        {
-0000b420: 7d0a 2020 2020 2020 5d0a 2020 2020 7d0a  }.      ].    }.
-0000b430: 2020 5d0a 7d0a 6060 600a 0a23 2323 204a    ].}.```..### J
-0000b440: 534f 4e20 5072 6f70 6572 7469 6573 2061  SON Properties a
-0000b450: 7420 7468 6520 5461 736b 204c 6576 656c  t the Task Level
-0000b460: 0a0a 5368 6f77 696e 6720 616c 6c20 706f  ..Showing all po
-0000b470: 7373 6962 6c65 2070 726f 7065 7274 6965  ssible propertie
-0000b480: 7320 6174 2074 6865 2054 6173 6b20 6c65  s at the Task le
-0000b490: 7665 6c3a 0a0a 6060 606a 736f 6e0a 7b0a  vel:..```json.{.
-0000b4a0: 2020 2274 6173 6b47 726f 7570 7322 3a20    "taskGroups": 
-0000b4b0: 5b0a 2020 2020 7b0a 2020 2020 2020 2274  [.    {.      "t
-0000b4c0: 6173 6b73 223a 205b 0a20 2020 2020 2020  asks": [.       
-0000b4d0: 207b 0a20 2020 2020 2020 2020 2022 6172   {.          "ar
-0000b4e0: 6775 6d65 6e74 7322 3a20 5b31 2c20 325d  guments": [1, 2]
-0000b4f0: 2c0a 2020 2020 2020 2020 2020 2263 6170  ,.          "cap
-0000b500: 7475 7265 5461 736b 4f75 7470 7574 223a  tureTaskOutput":
-0000b510: 2074 7275 652c 0a20 2020 2020 2020 2020   true,.         
-0000b520: 2022 646f 636b 6572 456e 7669 726f 6e6d   "dockerEnvironm
-0000b530: 656e 7422 3a20 7b22 4d59 5f44 4f43 4b45  ent": {"MY_DOCKE
-0000b540: 525f 5641 5222 3a20 3130 307d 2c0a 2020  R_VAR": 100},.  
-0000b550: 2020 2020 2020 2020 2264 6f63 6b65 7250          "dockerP
-0000b560: 6173 7377 6f72 6422 3a20 226d 7950 6173  assword": "myPas
-0000b570: 7377 6f72 6422 2c0a 2020 2020 2020 2020  sword",.        
-0000b580: 2020 2264 6f63 6b65 7255 7365 726e 616d    "dockerUsernam
-0000b590: 6522 3a20 226d 7955 7365 726e 616d 6522  e": "myUsername"
-0000b5a0: 2c0a 2020 2020 2020 2020 2020 2265 6e76  ,.          "env
-0000b5b0: 6972 6f6e 6d65 6e74 223a 207b 224d 595f  ironment": {"MY_
-0000b5c0: 5641 5222 3a20 3130 307d 2c0a 2020 2020  VAR": 100},.    
-0000b5d0: 2020 2020 2020 2265 7865 6375 7461 626c        "executabl
-0000b5e0: 6522 3a20 226d 792d 636f 6e74 6169 6e65  e": "my-containe
-0000b5f0: 7222 2c0a 2020 2020 2020 2020 2020 2266  r",.          "f
-0000b600: 6c61 7474 656e 496e 7075 7450 6174 6873  lattenInputPaths
-0000b610: 223a 2066 616c 7365 2c0a 2020 2020 2020  ": false,.      
-0000b620: 2020 2020 2269 6e70 7574 7322 3a20 5b22      "inputs": ["
-0000b630: 6170 702f 6d61 696e 2e70 7922 2c20 2261  app/main.py", "a
-0000b640: 7070 2f72 6571 7569 7265 6d65 6e74 732e  pp/requirements.
-0000b650: 7478 7422 5d2c 0a20 2020 2020 2020 2020  txt"],.         
-0000b660: 2022 696e 7075 7473 4f70 7469 6f6e 616c   "inputsOptional
-0000b670: 223a 205b 226f 7074 696f 6e61 6c2e 7478  ": ["optional.tx
-0000b680: 7422 5d2c 0a20 2020 2020 2020 2020 2022  t"],.          "
-0000b690: 6e61 6d65 223a 2022 6d79 2d74 6173 6b22  name": "my-task"
-0000b6a0: 2c0a 2020 2020 2020 2020 2020 226f 7574  ,.          "out
-0000b6b0: 7075 7473 223a 205b 2272 6573 756c 7473  puts": ["results
-0000b6c0: 2e74 7874 225d 2c0a 2020 2020 2020 2020  .txt"],.        
-0000b6d0: 2020 226f 7574 7075 7473 5265 7175 6972    "outputsRequir
-0000b6e0: 6564 223a 205b 2272 6573 756c 7473 5f72  ed": ["results_r
-0000b6f0: 6571 7569 7265 642e 7478 7422 5d2c 0a20  equired.txt"],. 
-0000b700: 2020 2020 2020 2020 2022 7461 736b 4461           "taskDa
-0000b710: 7461 223a 2022 6d79 5f74 6173 6b5f 6461  ta": "my_task_da
-0000b720: 7461 5f73 7472 696e 6722 2c0a 2020 2020  ta_string",.    
-0000b730: 2020 2020 2020 2274 6173 6b44 6174 6146        "taskDataF
-0000b740: 696c 6522 3a20 226d 795f 6461 7461 5f66  ile": "my_data_f
-0000b750: 696c 652e 7478 7422 2c0a 2020 2020 2020  ile.txt",.      
-0000b760: 2020 2020 2274 6173 6b54 7970 6522 3a20      "taskType": 
-0000b770: 2264 6f63 6b65 7222 2c0a 2020 2020 2020  "docker",.      
-0000b780: 2020 2020 2275 706c 6f61 6446 696c 6573      "uploadFiles
-0000b790: 223a 205b 7b22 6c6f 6361 6c50 6174 6822  ": [{"localPath"
-0000b7a0: 3a20 2266 696c 655f 312e 7478 7422 2c20  : "file_1.txt", 
-0000b7b0: 2275 706c 6f61 6450 6174 6822 3a20 2266  "uploadPath": "f
-0000b7c0: 696c 655f 312e 7478 7422 7d5d 2c0a 2020  ile_1.txt"}],.  
-0000b7d0: 2020 2020 2020 2020 2276 6572 6966 7941          "verifyA
-0000b7e0: 7453 7461 7274 223a 205b 2272 6561 6479  tStart": ["ready
-0000b7f0: 5f72 6573 756c 7473 2e74 7874 225d 2c0a  _results.txt"],.
-0000b800: 2020 2020 2020 2020 2020 2276 6572 6966            "verif
-0000b810: 7957 6169 7422 3a20 5b22 7761 6974 5f66  yWait": ["wait_f
-0000b820: 6f72 5f72 6573 756c 7473 2e74 7874 225d  or_results.txt"]
-0000b830: 0a20 2020 2020 2020 207d 0a20 2020 2020  .        }.     
-0000b840: 205d 0a20 2020 207d 0a20 205d 0a7d 0a60   ].    }.  ].}.`
-0000b850: 6060 0a0a 2323 2056 6172 6961 626c 6520  ``..## Variable 
-0000b860: 5375 6273 7469 7475 7469 6f6e 7320 696e  Substitutions in
-0000b870: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
-0000b880: 7420 5072 6f70 6572 7469 6573 0a0a 5661  t Properties..Va
-0000b890: 7269 6162 6c65 2073 7562 7374 6974 7574  riable substitut
-0000b8a0: 696f 6e73 2063 616e 2062 6520 7573 6564  ions can be used
-0000b8b0: 2077 6974 6869 6e20 616e 7920 7072 6f70   within any prop
-0000b8c0: 6572 7479 2076 616c 7565 2069 6e20 544f  erty value in TO
-0000b8d0: 4d4c 2063 6f6e 6669 6775 7261 7469 6f6e  ML configuration
-0000b8e0: 2066 696c 6573 206f 7220 576f 726b 2052   files or Work R
-0000b8f0: 6571 7569 7265 6d65 6e74 204a 534f 4e20  equirement JSON 
-0000b900: 6669 6c65 732e 2053 6565 2074 6865 2064  files. See the d
-0000b910: 6573 6372 6970 7469 6f6e 205b 6162 6f76  escription [abov
-0000b920: 655d 2823 7661 7269 6162 6c65 2d73 7562  e](#variable-sub
-0000b930: 7374 6974 7574 696f 6e73 2920 666f 7220  stitutions) for 
-0000b940: 6d6f 7265 2064 6574 6169 6c73 206f 6e20  more details on 
-0000b950: 7661 7269 6162 6c65 2073 7562 7374 6974  variable substit
-0000b960: 7574 696f 6e73 2e20 5468 6973 2069 7320  utions. This is 
-0000b970: 6120 706f 7765 7266 756c 2066 6561 7475  a powerful featu
-0000b980: 7265 2074 6861 7420 616c 6c6f 7773 2057  re that allows W
-0000b990: 6f72 6b20 5265 7175 6972 656d 656e 7473  ork Requirements
-0000b9a0: 2074 6f20 6265 2070 6172 616d 6574 6572   to be parameter
-0000b9b0: 6973 6564 2062 7920 7375 7070 6c79 696e  ised by supplyin
-0000b9c0: 6720 7661 6c75 6573 206f 6e20 7468 6520  g values on the 
-0000b9d0: 636f 6d6d 616e 6420 6c69 6e65 2c20 7669  command line, vi
-0000b9e0: 6120 656e 7669 726f 6e6d 656e 7420 7661  a environment va
-0000b9f0: 7269 6162 6c65 7320 6f72 2076 6961 2074  riables or via t
-0000ba00: 6865 2054 4f4d 4c20 6669 6c65 2e0a 0a23  he TOML file...#
-0000ba10: 2323 2054 6173 6b20 616e 6420 5461 736b  ## Task and Task
-0000ba20: 2047 726f 7570 204e 616d 6520 5375 6273   Group Name Subs
-0000ba30: 7469 7475 7469 6f6e 0a0a 5468 6520 666f  titution..The fo
-0000ba40: 6c6c 6f77 696e 6720 6e75 6d62 6572 696e  llowing numberin
-0000ba50: 6720 616e 6420 6e61 6d69 6e67 2073 7562  g and naming sub
-0000ba60: 7374 6974 7574 696f 6e73 2061 7265 2061  stitutions are a
-0000ba70: 7661 696c 6162 6c65 2066 6f72 2075 7365  vailable for use
-0000ba80: 2069 6e20 5461 736b 2061 6e64 2054 6173   in Task and Tas
-0000ba90: 6b20 4772 6f75 7020 6e61 6d69 6e67 2c20  k Group naming, 
-0000baa0: 6f6e 6c79 2077 6865 6e20 7468 6520 576f  only when the Wo
-0000bab0: 726b 2052 6571 7569 7265 6d65 6e74 2069  rk Requirement i
-0000bac0: 7320 7370 6563 6966 6965 6420 6173 2020  s specified as  
-0000bad0: 4a53 4f4e 2064 6f63 756d 656e 742c 2069  JSON document, i
-0000bae0: 2e65 2e2c 2074 6865 7920 6361 6e20 6265  .e., they can be
-0000baf0: 2075 7365 6420 696e 2074 6865 2060 6e61   used in the `na
-0000bb00: 6d65 6020 7072 6f70 6572 7469 6573 2066  me` properties f
-0000bb10: 6f72 2054 6173 6b73 2061 6e64 2054 6173  or Tasks and Tas
-0000bb20: 6b20 4772 6f75 7073 2069 6e20 4a53 4f4e  k Groups in JSON
-0000bb30: 2073 7065 6369 6669 6361 7469 6f6e 732e   specifications.
-0000bb40: 0a0a 5468 6520 666f 6c6c 6f77 696e 6720  ..The following 
-0000bb50: 7461 626c 6520 6465 6669 6e65 7320 7468  table defines th
-0000bb60: 6520 636f 6e74 6578 7428 7329 2069 6e20  e context(s) in 
-0000bb70: 7768 6963 6820 6561 6368 2076 6172 6961  which each varia
-0000bb80: 626c 6520 6361 6e20 6265 2075 7365 643a  ble can be used:
-0000bb90: 0a0a 7c20 4469 7265 6374 6976 6520 2020  ..| Directive   
-0000bba0: 2020 2020 2020 2020 2020 2020 7c20 4465              | De
-0000bbb0: 7363 7269 7074 696f 6e20 2020 2020 2020  scription       
-0000bbc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-0000bbd0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-0000bbe0: 7c20 5461 736b 207c 2054 6173 6b20 4772  | Task | Task Gr
-0000bbf0: 6f75 7020 7c0a 7c3a 2d2d 2d2d 2d2d 2d2d  oup |.|:--------
-0000bc00: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-0000bc10: 7c3a 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  |:--------------
-0000bc20: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-0000bc30: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-0000bc40: 2d2d 2d2d 7c3a 2d2d 2d2d 2d7c 3a2d 2d2d  ----|:-----|:---
-0000bc50: 2d2d 2d2d 2d2d 2d2d 7c0a 7c20 607b 7b74  --------|.| `{{t
-0000bc60: 6173 6b5f 6e75 6d62 6572 7d7d 6020 2020  ask_number}}`   
-0000bc70: 2020 2020 7c20 5468 6520 6375 7272 656e      | The curren
-0000bc80: 7420 5461 736b 206e 756d 6265 7220 2020  t Task number   
-0000bc90: 2020 2020 2020 2020 2020 2020 2020 2020                  
-0000bca0: 2020 2020 2020 2020 7c20 5965 7320 207c          | Yes  |
-0000bcb0: 2020 2020 2020 2020 2020 2020 7c0a 7c20              |.| 
-0000bcc0: 607b 7b74 6173 6b5f 6e61 6d65 7d7d 6020  `{{task_name}}` 
-0000bcd0: 2020 2020 2020 2020 7c20 5468 6520 6375          | The cu
-0000bce0: 7272 656e 7420 5461 736b 206e 616d 6520  rrent Task name 
-0000bcf0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-0000bd00: 2020 2020 2020 2020 2020 2020 7c20 5965              | Ye
-0000bd10: 7320 207c 2020 2020 2020 2020 2020 2020  s  |            
-0000bd20: 7c0a 7c20 607b 7b74 6173 6b5f 6772 6f75  |.| `{{task_grou
-0000bd30: 705f 6e61 6d65 7d7d 6020 2020 7c20 5468  p_name}}`   | Th
-0000bd40: 6520 6375 7272 656e 7420 5461 736b 2047  e current Task G
-0000bd50: 726f 7570 206e 616d 6520 2020 2020 2020  roup name       
-0000bd60: 2020 2020 2020 2020 2020 2020 2020 2020                  
-0000bd70: 7c20 5965 7320 207c 2020 2020 2020 2020  | Yes  |        
-0000bd80: 2020 2020 7c0a 7c20 607b 7b74 6173 6b5f      |.| `{{task_
-0000bd90: 636f 756e 747d 7d60 2020 2020 2020 2020  count}}`        
-0000bda0: 7c20 5468 6520 6e75 6d62 6572 206f 6620  | The number of 
-0000bdb0: 5461 736b 7320 696e 2074 6865 2063 7572  Tasks in the cur
-0000bdc0: 7265 6e74 2054 6173 6b20 4772 6f75 7020  rent Task Group 
-0000bdd0: 2020 2020 7c20 5965 7320 207c 2059 6573      | Yes  | Yes
-0000bde0: 2020 2020 2020 2020 7c0a 7c20 607b 7b74          |.| `{{t
-0000bdf0: 6173 6b5f 6772 6f75 705f 6e75 6d62 6572  ask_group_number
-0000be00: 7d7d 6020 7c20 5468 6520 6375 7272 656e  }}` | The curren
-0000be10: 7420 5461 736b 2047 726f 7570 206e 756d  t Task Group num
-0000be20: 6265 7220 2020 2020 2020 2020 2020 2020  ber             
-0000be30: 2020 2020 2020 2020 7c20 5965 7320 207c          | Yes  |
-0000be40: 2059 6573 2020 2020 2020 2020 7c0a 7c20   Yes        |.| 
-0000be50: 607b 7b74 6173 6b5f 6772 6f75 705f 636f  `{{task_group_co
-0000be60: 756e 747d 7d60 2020 7c20 5468 6520 6e75  unt}}`  | The nu
-0000be70: 6d62 6572 206f 6620 5461 736b 2047 726f  mber of Task Gro
-0000be80: 7570 7320 696e 2074 6865 2057 6f72 6b20  ups in the Work 
-0000be90: 5265 7175 6972 656d 656e 7420 7c20 5965  Requirement | Ye
-0000bea0: 7320 207c 2059 6573 2020 2020 2020 2020  s  | Yes        
-0000beb0: 7c0a 0a49 6e20 6164 6469 7469 6f6e 2c20  |..In addition, 
-0000bec0: 2a2a 5461 736b 732a 2a20 6465 6669 6e65  **Tasks** define
-0000bed0: 6420 696e 204a 534f 4e20 646f 6375 6d65  d in JSON docume
-0000bee0: 6e74 7320 6361 6e20 7573 6520 616e 7920  nts can use any 
-0000bef0: 6f66 2074 6865 2073 7562 7374 6974 7574  of the substitut
-0000bf00: 696f 6e73 2061 626f 7665 2069 6e20 616e  ions above in an
-0000bf10: 7920 6f66 2074 6865 6972 2070 726f 7065  y of their prope
-0000bf20: 7274 6965 732c 206e 6f74 206a 7573 7420  rties, not just 
-0000bf30: 606e 616d 6560 2e0a 0a4e 756d 6265 7273  `name`...Numbers
-0000bf40: 2061 7265 207a 6572 6f2d 7061 6464 6564   are zero-padded
-0000bf50: 2066 6f72 206e 6561 7420 666f 726d 6174   for neat format
-0000bf60: 7469 6e67 2061 6e64 2073 6f72 7469 6e67  ting and sorting
-0000bf70: 2c20 652e 672e 2c20 5461 736b 206e 756d  , e.g., Task num
-0000bf80: 6265 7220 6033 3760 206f 6620 6031 3030  ber `37` of `100
-0000bf90: 3060 2054 6173 6b73 2077 6f75 6c64 2062  0` Tasks would b
-0000bfa0: 6520 7375 6273 7469 7475 7465 6420 6173  e substituted as
-0000bfb0: 2060 3030 3337 602e 0a0a 4173 2061 6e20   `0037`...As an 
-0000bfc0: 6578 616d 706c 652c 2074 6865 2066 6f6c  example, the fol
-0000bfd0: 6c6f 7769 6e67 204a 534f 4e20 576f 726b  lowing JSON Work
-0000bfe0: 2052 6571 7569 7265 6d65 6e74 3a0a 0a60   Requirement:..`
-0000bff0: 6060 6a73 6f6e 0a7b 0a20 2022 7461 736b  ``json.{.  "task
-0000c000: 4772 6f75 7073 223a 205b 0a20 2020 207b  Groups": [.    {
-0000c010: 0a20 2020 2020 2022 6e61 6d65 223a 2022  .      "name": "
-0000c020: 6d79 5f74 6173 6b5f 6772 6f75 705f 7b7b  my_task_group_{{
-0000c030: 7461 736b 5f67 726f 7570 5f6e 756d 6265  task_group_numbe
-0000c040: 727d 7d5f 6131 222c 0a20 2020 2020 2022  r}}_a1",.      "
-0000c050: 6578 6563 7574 6162 6c65 223a 2022 6578  executable": "ex
-0000c060: 312e 7368 222c 0a20 2020 2020 2022 7461  1.sh",.      "ta
-0000c070: 736b 436f 756e 7422 3a20 322c 0a20 2020  skCount": 2,.   
-0000c080: 2020 2022 7461 736b 7322 3a20 5b0a 2020     "tasks": [.  
-0000c090: 2020 2020 2020 7b0a 2020 2020 2020 2020        {.        
-0000c0a0: 2020 226e 616d 6522 3a20 226d 795f 7461    "name": "my_ta
-0000c0b0: 736b 5f7b 7b74 6173 6b5f 6e75 6d62 6572  sk_{{task_number
-0000c0c0: 7d7d 2d6f 662d 7b7b 7461 736b 5f63 6f75  }}-of-{{task_cou
-0000c0d0: 6e74 7d7d 222c 0a20 2020 2020 2020 2020  nt}}",.         
-0000c0e0: 2022 656e 7669 726f 6e6d 656e 7422 3a20   "environment": 
-0000c0f0: 7b22 5441 534b 5f4e 554d 4245 5222 3a20  {"TASK_NUMBER": 
-0000c100: 227b 7b74 6173 6b5f 6e75 6d62 6572 7d7d  "{{task_number}}
-0000c110: 227d 0a20 2020 2020 2020 207d 0a20 2020  "}.        }.   
-0000c120: 2020 205d 0a20 2020 207d 2c0a 2020 2020     ].    },.    
-0000c130: 7b0a 2020 2020 2020 226e 616d 6522 3a20  {.      "name": 
-0000c140: 226d 795f 7461 736b 5f67 726f 7570 5f7b  "my_task_group_{
-0000c150: 7b74 6173 6b5f 6772 6f75 705f 6e75 6d62  {task_group_numb
-0000c160: 6572 7d7d 5f62 3122 2c0a 2020 2020 2020  er}}_b1",.      
-0000c170: 2265 7865 6375 7461 626c 6522 3a20 2265  "executable": "e
-0000c180: 7832 2e73 6822 2c0a 2020 2020 2020 2274  x2.sh",.      "t
-0000c190: 6173 6b43 6f75 6e74 223a 2032 2c0a 2020  askCount": 2,.  
-0000c1a0: 2020 2020 2274 6173 6b73 223a 205b 0a20      "tasks": [. 
-0000c1b0: 2020 2020 2020 207b 0a20 2020 2020 2020         {.       
-0000c1c0: 2020 2022 6e61 6d65 223a 2022 6d79 5f74     "name": "my_t
-0000c1d0: 6173 6b5f 7b7b 7461 736b 5f6e 756d 6265  ask_{{task_numbe
-0000c1e0: 727d 7d2d 6f66 2d7b 7b74 6173 6b5f 636f  r}}-of-{{task_co
-0000c1f0: 756e 747d 7d22 0a20 2020 2020 2020 207d  unt}}".        }
-0000c200: 0a20 2020 2020 205d 0a20 2020 207d 0a20  .      ].    }. 
-0000c210: 205d 0a7d 0a60 6060 0a0a 2e2e 2e20 776f   ].}.```..... wo
-0000c220: 756c 6420 6372 6561 7465 2054 6173 6b20  uld create Task 
-0000c230: 4772 6f75 7073 206e 616d 6564 2060 6d79  Groups named `my
-0000c240: 5f74 6173 6b5f 6772 6f75 705f 315f 6131  _task_group_1_a1
-0000c250: 6020 616e 6420 606d 795f 7461 736b 5f67  ` and `my_task_g
-0000c260: 726f 7570 5f32 5f62 3160 2c20 6561 6368  roup_2_b1`, each
-0000c270: 2063 6f6e 7461 696e 696e 6720 5461 736b   containing Task
-0000c280: 7320 6e61 6d65 6420 606d 795f 7461 736b  s named `my_task
-0000c290: 5f31 2d6f 662d 3260 2c20 606d 795f 7461  _1-of-2`, `my_ta
-0000c2a0: 736b 5f32 2d6f 662d 3260 2e0a 0a23 2323  sk_2-of-2`...###
-0000c2b0: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
-0000c2c0: 7420 4e61 6d65 2053 7562 7374 6974 7574  t Name Substitut
-0000c2d0: 696f 6e0a 0a54 6865 206e 616d 6520 6f66  ion..The name of
-0000c2e0: 2074 6865 2057 6f72 6b20 5265 7175 6972   the Work Requir
-0000c2f0: 656d 656e 7420 6974 7365 6c66 2063 616e  ement itself can
-0000c300: 2062 6520 7573 6564 2076 6961 2074 6865   be used via the
-0000c310: 2076 6172 6961 626c 6520 7375 6273 7469   variable substi
-0000c320: 7475 7469 6f6e 2060 7b7b 7772 5f6e 616d  tution `{{wr_nam
-0000c330: 657d 7d60 2e20 5468 6973 2063 616e 2062  e}}`. This can b
-0000c340: 6520 7573 6564 2061 6e79 7768 6572 6520  e used anywhere 
-0000c350: 696e 2061 2054 4f4d 4c20 636f 6e66 6967  in a TOML config
-0000c360: 7572 6174 696f 6e20 6669 6c65 206f 7220  uration file or 
-0000c370: 696e 2061 204a 534f 4e20 576f 726b 2052  in a JSON Work R
-0000c380: 6571 7569 7265 6d65 6e74 2e0a 0a23 2320  equirement...## 
-0000c390: 4472 792d 5275 6e6e 696e 6720 576f 726b  Dry-Running Work
-0000c3a0: 2052 6571 7569 7265 6d65 6e74 2053 7562   Requirement Sub
-0000c3b0: 6d69 7373 696f 6e73 0a0a 546f 2065 7861  missions..To exa
-0000c3c0: 6d69 6e65 2074 6865 204a 534f 4e20 7468  mine the JSON th
-0000c3d0: 6174 2077 696c 6c20 6163 7475 616c 6c79  at will actually
-0000c3e0: 2062 6520 7365 6e74 2074 6f20 7468 6520   be sent to the 
-0000c3f0: 5965 6c6c 6f77 446f 6720 4150 4920 6166  YellowDog API af
-0000c400: 7465 7220 616c 6c20 7072 6f63 6573 7369  ter all processi
-0000c410: 6e67 2c20 7573 6520 7468 6520 602d 2d64  ng, use the `--d
-0000c420: 7279 2d72 756e 6020 636f 6d6d 616e 6420  ry-run` command 
-0000c430: 6c69 6e65 206f 7074 696f 6e20 7768 656e  line option when
-0000c440: 2072 756e 6e69 6e67 2060 7964 2d73 7562   running `yd-sub
-0000c450: 6d69 7460 2e20 5468 6973 2077 696c 6c20  mit`. This will 
-0000c460: 7072 696e 7420 7468 6520 6675 6c6c 7920  print the fully 
-0000c470: 7072 6f63 6573 7365 6420 4a53 4f4e 2066  processed JSON f
-0000c480: 6f72 2074 6865 2057 6f72 6b20 5265 7175  or the Work Requ
-0000c490: 6972 656d 656e 742e 204e 6f74 6869 6e67  irement. Nothing
-0000c4a0: 2077 696c 6c20 6265 2073 7562 6d69 7474   will be submitt
-0000c4b0: 6564 2074 6f20 7468 6520 506c 6174 666f  ed to the Platfo
-0000c4c0: 726d 2e0a 0a54 6865 2064 7279 2d72 756e  rm...The dry-run
-0000c4d0: 2069 7320 7573 6566 756c 2066 6f72 2069   is useful for i
-0000c4e0: 6e73 7065 6374 696e 6720 7468 6520 7265  nspecting the re
-0000c4f0: 7375 6c74 7320 6f66 2061 6c6c 2074 6865  sults of all the
-0000c500: 2070 726f 6365 7373 696e 6720 7468 6174   processing that
-0000c510: 2773 2062 6565 6e20 7065 7266 6f72 6d65  's been performe
-0000c520: 642e 2054 6f20 7375 7070 7265 7373 2061  d. To suppress a
-0000c530: 6c6c 206f 7574 7075 7420 6578 6365 7074  ll output except
-0000c540: 2066 6f72 2074 6865 204a 534f 4e20 6974   for the JSON it
-0000c550: 7365 6c66 2c20 7573 6520 7468 6520 602d  self, use the `-
-0000c560: 2d71 7569 6574 6020 2860 2d71 6029 2063  -quiet` (`-q`) c
-0000c570: 6f6d 6d61 6e64 206c 696e 6520 6f70 7469  ommand line opti
-0000c580: 6f6e 2e0a 0a4e 6f74 6520 7468 6174 2074  on...Note that t
-0000c590: 6865 2067 656e 6572 6174 6564 204a 534f  he generated JSO
-0000c5a0: 4e20 6973 2061 2063 6f6e 736f 6c69 6461  N is a consolida
-0000c5b0: 7465 6420 666f 726d 206f 6620 7768 6174  ted form of what
-0000c5c0: 2077 6f75 6c64 2062 6520 7375 626d 6974   would be submit
-0000c5d0: 7465 6420 746f 2074 6865 2059 656c 6c6f  ted to the Yello
-0000c5e0: 7744 6f67 2041 5049 2c20 616e 6420 5461  wDog API, and Ta
-0000c5f0: 736b 7320 6172 6520 6465 6669 6e65 6420  sks are defined 
-0000c600: 6469 7265 6374 6c79 2077 6974 6869 6e20  directly within 
-0000c610: 7468 6569 7220 5461 736b 2047 726f 7570  their Task Group
-0000c620: 7320 666f 7220 6561 7365 206f 6620 636f  s for ease of co
-0000c630: 6d70 7265 6865 6e73 696f 6e2e 2049 6e20  mprehension. In 
-0000c640: 6163 7475 616c 2041 5049 2073 7562 6d69  actual API submi
-0000c650: 7373 696f 6e73 2c20 7468 6520 576f 726b  ssions, the Work
-0000c660: 2052 6571 7569 7265 6d65 6e74 2077 6974   Requirement wit
-0000c670: 6820 6974 7320 5461 736b 2047 726f 7570  h its Task Group
-0000c680: 7320 6973 2073 7562 6d69 7474 6564 2066  s is submitted f
-0000c690: 6972 7374 2c20 616e 6420 5461 736b 7320  irst, and Tasks 
-0000c6a0: 6172 6520 7468 656e 2061 6464 6564 2074  are then added t
-0000c6b0: 6f20 5461 736b 2047 726f 7570 7320 7365  o Task Groups se
-0000c6c0: 7061 7261 7465 6c79 2069 6e20 7375 6273  parately in subs
-0000c6d0: 6571 7565 6e74 2041 5049 2063 616c 6c73  equent API calls
-0000c6e0: 2e0a 0a41 2073 696d 706c 6520 6578 616d  ...A simple exam
-0000c6f0: 706c 6520 6f66 2074 6865 204a 534f 4e20  ple of the JSON 
-0000c700: 6f75 7470 7574 2069 7320 7368 6f77 6e20  output is shown 
-0000c710: 6265 6c6f 772c 2073 686f 7769 6e67 2061  below, showing a
-0000c720: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
-0000c730: 7420 7769 7468 2061 2073 696e 676c 6520  t with a single 
-0000c740: 5461 736b 2047 726f 7570 2c20 636f 6e74  Task Group, cont
-0000c750: 6169 6e69 6e67 2061 2073 696e 676c 6520  aining a single 
-0000c760: 5461 736b 2e0a 0a60 2520 7964 2d73 7562  Task...`% yd-sub
-0000c770: 6d69 7420 2d2d 6472 792d 7275 6e20 2d2d  mit --dry-run --
-0000c780: 7175 6965 7460 0a60 6060 6a73 6f6e 0a7b  quiet`.```json.{
-0000c790: 0a20 2022 6675 6c66 696c 4f6e 5375 626d  .  "fulfilOnSubm
-0000c7a0: 6974 223a 2066 616c 7365 2c0a 2020 226e  it": false,.  "n
-0000c7b0: 616d 6522 3a20 2270 7965 782d 6261 7368  ame": "pyex-bash
-0000c7c0: 5f32 3330 3131 342d 3039 3535 3034 2d35  _230114-095504-5
-0000c7d0: 3361 222c 0a20 2022 6e61 6d65 7370 6163  3a",.  "namespac
-0000c7e0: 6522 3a20 2270 7965 7861 6d70 6c65 7322  e": "pyexamples"
-0000c7f0: 2c0a 2020 2270 7269 6f72 6974 7922 3a20  ,.  "priority": 
-0000c800: 302c 0a20 2022 7461 6722 3a20 2270 7965  0,.  "tag": "pye
-0000c810: 782d 6261 7368 222c 0a20 2022 7461 736b  x-bash",.  "task
-0000c820: 4772 6f75 7073 223a 205b 0a20 2020 207b  Groups": [.    {
-0000c830: 0a20 2020 2020 2022 6669 6e69 7368 4966  .      "finishIf
-0000c840: 416c 6c54 6173 6b73 4669 6e69 7368 6564  AllTasksFinished
-0000c850: 223a 2074 7275 652c 0a20 2020 2020 2022  ": true,.      "
-0000c860: 6669 6e69 7368 4966 416e 7954 6173 6b46  finishIfAnyTaskF
-0000c870: 6169 6c65 6422 3a20 6661 6c73 652c 0a20  ailed": false,. 
-0000c880: 2020 2020 2022 6e61 6d65 223a 2022 7461       "name": "ta
-0000c890: 736b 5f67 726f 7570 5f31 222c 0a20 2020  sk_group_1",.   
-0000c8a0: 2020 2022 7072 696f 7269 7479 223a 2030     "priority": 0
-0000c8b0: 2c0a 2020 2020 2020 2272 756e 5370 6563  ,.      "runSpec
-0000c8c0: 6966 6963 6174 696f 6e22 3a20 7b0a 2020  ification": {.  
-0000c8d0: 2020 2020 2020 226d 6178 696d 756d 5461        "maximumTa
-0000c8e0: 736b 5265 7472 6965 7322 3a20 302c 0a20  skRetries": 0,. 
-0000c8f0: 2020 2020 2020 2022 7461 736b 5479 7065         "taskType
-0000c900: 7322 3a20 5b22 6261 7368 225d 2c0a 2020  s": ["bash"],.  
-0000c910: 2020 2020 2020 2277 6f72 6b65 7254 6167        "workerTag
-0000c920: 7322 3a20 5b22 7079 6578 2d62 6173 6822  s": ["pyex-bash"
-0000c930: 5d0a 2020 2020 2020 7d2c 0a20 2020 2020  ].      },.     
-0000c940: 2022 7461 736b 7322 3a20 5b0a 2020 2020   "tasks": [.    
-0000c950: 2020 2020 7b0a 2020 2020 2020 2020 2020      {.          
-0000c960: 2261 7267 756d 656e 7473 223a 205b 2270  "arguments": ["p
-0000c970: 7965 782d 6261 7368 5f32 3330 3131 342d  yex-bash_230114-
-0000c980: 3039 3535 3034 2d35 3361 2f73 6c65 6570  095504-53a/sleep
-0000c990: 5f73 6372 6970 742e 7368 225d 2c0a 2020  _script.sh"],.  
-0000c9a0: 2020 2020 2020 2020 2265 6e76 6972 6f6e          "environ
-0000c9b0: 6d65 6e74 223a 207b 7d2c 0a20 2020 2020  ment": {},.     
-0000c9c0: 2020 2020 2022 696e 7075 7473 223a 205b       "inputs": [
-0000c9d0: 0a20 2020 2020 2020 2020 2020 207b 0a20  .            {. 
-0000c9e0: 2020 2020 2020 2020 2020 2020 2022 6f62               "ob
-0000c9f0: 6a65 6374 4e61 6d65 5061 7474 6572 6e22  jectNamePattern"
-0000ca00: 3a20 2270 7965 782d 6261 7368 5f32 3330  : "pyex-bash_230
-0000ca10: 3131 342d 3039 3535 3034 2d35 3361 2f73  114-095504-53a/s
-0000ca20: 6c65 6570 5f73 6372 6970 742e 7368 222c  leep_script.sh",
-0000ca30: 0a20 2020 2020 2020 2020 2020 2020 2022  .              "
-0000ca40: 736f 7572 6365 223a 2022 5441 534b 5f4e  source": "TASK_N
-0000ca50: 414d 4553 5041 4345 222c 0a20 2020 2020  AMESPACE",.     
-0000ca60: 2020 2020 2020 2020 2022 7665 7269 6669           "verifi
-0000ca70: 6361 7469 6f6e 223a 2022 5645 5249 4659  cation": "VERIFY
-0000ca80: 5f57 4149 5422 0a20 2020 2020 2020 2020  _WAIT".         
-0000ca90: 2020 207d 0a20 2020 2020 2020 2020 205d     }.          ]
-0000caa0: 2c0a 2020 2020 2020 2020 2020 226e 616d  ,.          "nam
-0000cab0: 6522 3a20 2274 6173 6b5f 3031 222c 0a20  e": "task_01",. 
-0000cac0: 2020 2020 2020 2020 2022 6f75 7470 7574           "output
-0000cad0: 7322 3a20 5b0a 2020 2020 2020 2020 2020  s": [.          
-0000cae0: 2020 7b22 616c 7761 7973 5570 6c6f 6164    {"alwaysUpload
-0000caf0: 223a 2074 7275 652c 2022 7265 7175 6972  ": true, "requir
-0000cb00: 6564 223a 2066 616c 7365 2c20 2273 6f75  ed": false, "sou
-0000cb10: 7263 6522 3a20 2250 524f 4345 5353 5f4f  rce": "PROCESS_O
-0000cb20: 5554 5055 5422 7d0a 2020 2020 2020 2020  UTPUT"}.        
-0000cb30: 2020 5d2c 0a20 2020 2020 2020 2020 2022    ],.          "
-0000cb40: 7461 736b 5479 7065 223a 2022 6261 7368  taskType": "bash
-0000cb50: 220a 2020 2020 2020 2020 7d0a 2020 2020  ".        }.    
-0000cb60: 2020 5d0a 2020 2020 7d0a 2020 5d0a 7d0a    ].    }.  ].}.
-0000cb70: 6060 600a 0a23 2323 2053 7562 6d69 7474  ```..### Submitt
-0000cb80: 696e 6720 2752 6177 2720 4a53 4f4e 2057  ing 'Raw' JSON W
-0000cb90: 6f72 6b20 5265 7175 6972 656d 656e 7420  ork Requirement 
-0000cba0: 5370 6563 6966 6963 6174 696f 6e73 0a0a  Specifications..
-0000cbb0: 4974 2773 2070 6f73 7369 626c 6520 746f  It's possible to
-0000cbc0: 2075 7365 2074 6865 204a 534f 4e20 6f75   use the JSON ou
-0000cbd0: 7470 7574 206f 6620 6079 642d 7375 626d  tput of `yd-subm
-0000cbe0: 6974 202d 2d64 7279 2d72 756e 6020 2873  it --dry-run` (s
-0000cbf0: 7563 6820 6173 2074 6865 2065 7861 6d70  uch as the examp
-0000cc00: 6c65 2061 626f 7665 2920 6173 2061 2073  le above) as a s
-0000cc10: 656c 662d 636f 6e74 6169 6e65 642c 2066  elf-contained, f
-0000cc20: 756c 6c79 2d73 7065 6369 6669 6564 2057  ully-specified W
-0000cc30: 6f72 6b20 5265 7175 6972 656d 656e 7420  ork Requirement 
-0000cc40: 7370 6563 6966 6963 6174 696f 6e2c 2075  specification, u
-0000cc50: 7369 6e67 2074 6865 2060 2d2d 6a73 6f6e  sing the `--json
-0000cc60: 2d72 6177 6020 286f 7220 602d 6a60 2920  -raw` (or `-j`) 
-0000cc70: 636f 6d6d 616e 6420 6c69 6e65 206f 7074  command line opt
-0000cc80: 696f 6e2c 2069 2e65 2e3a 2060 7964 2d73  ion, i.e.: `yd-s
-0000cc90: 7562 6d69 7420 2d2d 6a73 6f6e 2d72 6177  ubmit --json-raw
-0000cca0: 203c 6669 6c65 6e61 6d65 2e6a 736f 6e3e   <filename.json>
-0000ccb0: 602e 0a0a 5468 6973 2077 696c 6c20 7375  `...This will su
-0000ccc0: 626d 6974 2074 6865 2057 6f72 6b20 5265  bmit the Work Re
-0000ccd0: 7175 6972 656d 656e 742c 2074 6865 6e20  quirement, then 
-0000cce0: 6164 6420 616c 6c20 7468 6520 7370 6563  add all the spec
-0000ccf0: 6966 6965 6420 5461 736b 732e 0a0a 4e6f  ified Tasks...No
-0000cd00: 7465 2074 6861 7420 7661 7269 6162 6c65  te that variable
-0000cd10: 2073 7562 7374 6974 7574 696f 6e73 202a   substitutions *
-0000cd20: 2a63 616e 2a2a 2062 6520 7573 6564 2069  *can** be used i
-0000cd30: 6e20 7468 6520 7261 7720 4a53 4f4e 2066  n the raw JSON f
-0000cd40: 696c 652c 206a 7573 7420 6173 2069 6e20  ile, just as in 
-0000cd50: 7468 6520 6f74 6865 7220 576f 726b 2052  the other Work R
-0000cd60: 6571 7569 7265 6d65 6e74 204a 534f 4e20  equirement JSON 
-0000cd70: 6578 616d 706c 6573 2c20 6275 7420 7468  examples, but th
-0000cd80: 6572 6520 6973 206e 6f20 7072 6f70 6572  ere is no proper
-0000cd90: 7479 2069 6e68 6572 6974 616e 6365 2c20  ty inheritance, 
-0000cda0: 696e 636c 7564 696e 6720 6672 6f6d 2074  including from t
-0000cdb0: 6865 2060 5b77 6f72 6b52 6571 7569 7265  he `[workRequire
-0000cdc0: 6d65 6e74 5d60 2073 6563 7469 6f6e 206f  ment]` section o
-0000cdd0: 6620 7468 6520 544f 4d4c 2063 6f6e 6669  f the TOML confi
-0000cde0: 6775 7261 7469 6f6e 206f 7220 6672 6f6d  guration or from
-0000cdf0: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
-0000ce00: 7420 7072 6f70 6572 7469 6573 2073 7570  t properties sup
-0000ce10: 706c 6965 6420 6f6e 2074 6865 2063 6f6d  plied on the com
-0000ce20: 6d61 6e64 206c 696e 652e 0a0a 4e6f 7465  mand line...Note
-0000ce30: 2074 6861 7420 7468 6572 6520 6973 206e   that there is n
-0000ce40: 6f20 6175 746f 6d61 7469 6320 6669 6c65  o automatic file
-0000ce50: 2075 706c 6f61 6420 7768 656e 2075 7369   upload when usi
-0000ce60: 6e67 2074 6869 7320 6f70 7469 6f6e 2c20  ng this option, 
-0000ce70: 736f 2061 6e79 2066 696c 6573 2072 6571  so any files req
-0000ce80: 7569 7265 6420 6174 2074 6865 2073 7461  uired at the sta
-0000ce90: 7274 206f 6620 7468 6520 7461 736b 2028  rt of the task (
-0000cea0: 7370 6563 6966 6965 6420 7573 696e 6720  specified using 
-0000ceb0: 6056 4552 4946 595f 4154 5f53 5441 5254  `VERIFY_AT_START
-0000cec0: 6029 206d 7573 7420 6265 2070 7265 7365  `) must be prese
-0000ced0: 6e74 2062 6566 6f72 6520 7468 6520 5461  nt before the Ta
-0000cee0: 736b 7320 6172 6520 7570 6c6f 6164 6564  sks are uploaded
-0000cef0: 2c20 6f72 2074 6865 2054 6173 6b73 2077  , or the Tasks w
-0000cf00: 696c 6c20 6661 696c 2069 6d6d 6564 6961  ill fail immedia
-0000cf10: 7465 6c79 2e20 5468 6520 6079 642d 7570  tely. The `yd-up
-0000cf20: 6c6f 6164 6020 636f 6d6d 616e 6420 6361  load` command ca
-0000cf30: 6e20 6265 2075 7365 6420 746f 2075 706c  n be used to upl
-0000cf40: 6f61 6420 7468 6573 6520 6669 6c65 732c  oad these files,
-0000cf50: 2061 6e64 2060 7964 2d73 7562 6d69 7460   and `yd-submit`
-0000cf60: 2077 696c 6c20 7061 7573 6520 746f 2061   will pause to a
-0000cf70: 6c6c 6f77 2074 6869 7320 746f 2068 6170  llow this to hap
-0000cf80: 7065 6e2e 0a0a 2323 2046 696c 6520 5374  pen...## File St
-0000cf90: 6f72 6167 6520 4c6f 6361 7469 6f6e 7320  orage Locations 
-0000cfa0: 616e 6420 4669 6c65 2055 7361 6765 0a0a  and File Usage..
-0000cfb0: 5468 6973 2073 6563 7469 6f6e 2064 6973  This section dis
-0000cfc0: 6375 7373 6573 2068 6f77 2074 6f20 7570  cusses how to up
-0000cfd0: 6c6f 6164 2066 696c 6573 2066 726f 6d20  load files from 
-0000cfe0: 6c6f 6361 6c20 7374 6f72 6167 6520 746f  local storage to
-0000cff0: 2074 6865 2059 656c 6c6f 7744 6f67 204f   the YellowDog O
-0000d000: 626a 6563 7420 5374 6f72 652c 2068 6f77  bject Store, how
-0000d010: 2074 686f 7365 2066 696c 6573 2061 7265   those files are
-0000d020: 2074 7261 6e73 6665 7272 6564 2074 6f20   transferred to 
-0000d030: 576f 726b 6572 204e 6f64 6573 2066 6f72  Worker Nodes for
-0000d040: 2054 6173 6b20 7072 6f63 6573 7369 6e67   Task processing
-0000d050: 2c20 686f 7720 7468 6520 7265 7375 6c74  , how the result
-0000d060: 7320 6f66 2054 6173 6b20 7072 6f63 6573  s of Task proces
-0000d070: 7369 6e67 2061 7265 2072 6574 7572 6e65  sing are returne
-0000d080: 6420 6279 2057 6f72 6b65 7220 4e6f 6465  d by Worker Node
-0000d090: 732c 2061 6e64 2068 6f77 2066 696c 6573  s, and how files
-0000d0a0: 2061 7265 2074 7261 6e73 6665 7272 6564   are transferred
-0000d0b0: 2062 6163 6b20 6672 6f6d 2074 6865 2059   back from the Y
-0000d0c0: 656c 6c6f 7744 6f67 204f 626a 6563 7420  ellowDog Object 
-0000d0d0: 5374 6f72 6520 746f 206c 6f63 616c 2073  Store to local s
-0000d0e0: 746f 7261 6765 2e0a 0a23 2323 2046 696c  torage...### Fil
-0000d0f0: 6573 2055 706c 6f61 6465 6420 746f 2074  es Uploaded to t
-0000d100: 6865 204f 626a 6563 7420 5374 6f72 6520  he Object Store 
-0000d110: 6672 6f6d 204c 6f63 616c 2053 746f 7261  from Local Stora
-0000d120: 6765 0a0a 2323 2323 2046 696c 6573 2069  ge..#### Files i
-0000d130: 6e20 7468 6520 6069 6e70 7574 7360 204c  n the `inputs` L
-0000d140: 6973 740a 0a57 6865 6e20 6120 576f 726b  ist..When a Work
-0000d150: 2052 6571 7569 7265 6d65 6e74 2069 7320   Requirement is 
-0000d160: 7375 626d 6974 7465 6420 7573 696e 6720  submitted using 
-0000d170: 6079 642d 7375 626d 6974 602c 2066 696c  `yd-submit`, fil
-0000d180: 6573 2061 7265 2075 706c 6f61 6465 6420  es are uploaded 
-0000d190: 746f 2074 6865 2059 656c 6c6f 7744 6f67  to the YellowDog
-0000d1a0: 204f 626a 6563 7420 5374 6f72 6520 6966   Object Store if
-0000d1b0: 2074 6865 7927 7265 2069 6e63 6c75 6465   they're include
-0000d1c0: 6420 696e 2074 6865 206c 6973 7420 6f66  d in the list of
-0000d1d0: 2066 696c 6573 2069 6e20 7468 6520 6069   files in the `i
-0000d1e0: 6e70 7574 7360 2070 726f 7065 7274 792e  nputs` property.
-0000d1f0: 2028 466f 7220 7468 6520 6361 7365 206f   (For the case o
-0000d200: 6620 7468 6520 6062 6173 6860 2054 6173  f the `bash` Tas
-0000d210: 6b20 5479 7065 2c20 7468 6520 7363 7269  k Type, the scri
-0000d220: 7074 2073 7065 6369 6669 6564 2069 6e20  pt specified in 
-0000d230: 7468 6520 6065 7865 6375 7461 626c 6560  the `executable`
-0000d240: 2070 726f 7065 7274 7920 6973 2061 6c73   property is als
-0000d250: 6f20 6175 746f 6d61 7469 6361 6c6c 7920  o automatically 
-0000d260: 7570 6c6f 6164 6564 2061 7320 6120 636f  uploaded as a co
-0000d270: 6e76 656e 6965 6e63 652c 2065 7665 6e20  nvenience, even 
-0000d280: 6966 206e 6f74 2069 6e63 6c75 6465 6420  if not included 
-0000d290: 696e 2074 6865 2060 696e 7075 7473 6020  in the `inputs` 
-0000d2a0: 6c69 7374 2e29 0a0a 5468 6520 6069 6e70  list.)..The `inp
-0000d2b0: 7574 7360 2070 726f 7065 7274 7920 6163  uts` property ac
-0000d2c0: 6365 7074 7320 7769 6c64 6361 7264 2066  cepts wildcard f
-0000d2d0: 696c 656e 616d 6573 2c20 652e 672e 3a20  ilenames, e.g.: 
-0000d2e0: 605b 222a 2e73 6822 2c20 222a 2e74 7874  `["*.sh", "*.txt
-0000d2f0: 225d 602e 2054 6869 7320 6361 6e20 6265  "]`. This can be
-0000d300: 2075 7365 6420 746f 2061 6464 2074 6865   used to add the
-0000d310: 2063 6f6e 7465 6e74 7320 6f66 2064 6972   contents of dir
-0000d320: 6563 746f 7269 6573 2c20 652e 672e 3a20  ectories, e.g.: 
-0000d330: 605b 226d 795f 6469 722f 2a22 2c20 2264  `["my_dir/*", "d
-0000d340: 6174 612a 2f2a 225d 602e 0a0a 4669 6c65  ata*/*"]`...File
-0000d350: 7320 6172 6520 7570 6c6f 6164 6564 2074  s are uploaded t
-0000d360: 6f20 7468 6520 4e61 6d65 7370 6163 6520  o the Namespace 
-0000d370: 7370 6563 6966 6965 6420 696e 2074 6865  specified in the
-0000d380: 2063 6f6e 6669 6775 7261 7469 6f6e 2e20   configuration. 
-0000d390: 5769 7468 696e 2074 6865 204e 616d 6573  Within the Names
-0000d3a0: 7061 6365 2c20 6561 6368 2057 6f72 6b20  pace, each Work 
-0000d3b0: 5265 7175 6972 656d 656e 7420 6861 7320  Requirement has 
-0000d3c0: 6120 7365 7061 7261 7465 2066 6f6c 6465  a separate folde
-0000d3d0: 7220 7468 6174 2073 6861 7265 7320 7468  r that shares th
-0000d3e0: 6520 6e61 6d65 206f 6620 7468 6520 576f  e name of the Wo
-0000d3f0: 726b 2052 6571 7569 7265 6d65 6e74 2c20  rk Requirement, 
-0000d400: 616e 6420 696e 2077 6869 6368 2061 6c6c  and in which all
-0000d410: 2066 696c 6573 2072 656c 6174 6564 2074   files related t
-0000d420: 6f20 7468 6520 576f 726b 2052 6571 7569  o the Work Requi
-0000d430: 7265 6d65 6e74 2061 7265 2073 746f 7265  rement are store
-0000d440: 642e 0a0a 312e 2046 696c 6573 2074 6f20  d...1. Files to 
-0000d450: 6265 2075 706c 6f61 6465 6420 7468 6174  be uploaded that
-0000d460: 2061 7265 2069 6e20 7468 6520 2a2a 7361   are in the **sa
-0000d470: 6d65 2064 6972 6563 746f 7279 2061 7320  me directory as 
-0000d480: 7468 6520 576f 726b 2052 6571 7569 7265  the Work Require
-0000d490: 6d65 6e74 2073 7065 6369 6669 6361 7469  ment specificati
-0000d4a0: 6f6e 2a2a 2028 7468 6520 544f 4d4c 206f  on** (the TOML o
-0000d4b0: 7220 4a53 4f4e 2066 696c 6529 2061 7265  r JSON file) are
-0000d4c0: 2075 706c 6f61 6465 6420 746f 2074 6865   uploaded to the
-0000d4d0: 2072 6f6f 7420 6f66 2074 6865 2057 6f72   root of the Wor
-0000d4e0: 6b20 5265 7175 6972 656d 656e 7420 666f  k Requirement fo
-0000d4f0: 6c64 6572 2e0a 0a0a 322e 2046 696c 6573  lder....2. Files
-0000d500: 2074 6f20 6265 2075 706c 6f61 6465 6420   to be uploaded 
-0000d510: 7468 6174 2061 7265 2069 6e20 2a2a 7375  that are in **su
-0000d520: 6264 6972 6563 746f 7269 6573 2062 656c  bdirectories bel
-0000d530: 6f77 2074 6865 2057 6f72 6b20 5265 7175  ow the Work Requ
-0000d540: 6972 656d 656e 7420 7370 6563 6966 6963  irement specific
-0000d550: 6174 696f 6e2c 206f 7220 7768 6572 6520  ation, or where 
-0000d560: 6162 736f 6c75 7465 2070 6174 686e 616d  absolute pathnam
-0000d570: 6573 2061 7265 2073 7570 706c 6965 642a  es are supplied*
-0000d580: 2a20 6172 6520 706c 6163 6564 2069 6e20  * are placed in 
-0000d590: 7468 6520 4f62 6a65 6374 2053 746f 7265  the Object Store
-0000d5a0: 2069 6e20 6469 7265 6374 6f72 6965 7320   in directories 
-0000d5b0: 7468 6174 206d 6972 726f 7220 7468 6569  that mirror thei
-0000d5c0: 7220 6c6f 6361 6c20 7374 6f72 6167 6520  r local storage 
-0000d5d0: 6c6f 6361 7469 6f6e 732e 0a0a 0a33 2e20  locations....3. 
-0000d5e0: 4669 6c65 7320 746f 2062 6520 7570 6c6f  Files to be uplo
-0000d5f0: 6164 6564 2074 6861 7420 6172 6520 696e  aded that are in
-0000d600: 202a 2a64 6972 6563 746f 7269 6573 2072   **directories r
-0000d610: 656c 6174 6976 6520 746f 2074 6865 2057  elative to the W
-0000d620: 6f72 6b20 5265 7175 6972 656d 656e 7420  ork Requirement 
-0000d630: 7370 6563 6966 6963 6174 696f 6e2c 2075  specification, u
-0000d640: 7369 6e67 2060 2e2e 6020 7265 6c61 7469  sing `..` relati
-0000d650: 7665 2070 6174 6873 2a2a 2061 7265 2070  ve paths** are p
-0000d660: 6c61 6365 6420 696e 204f 626a 6563 7420  laced in Object 
-0000d670: 5374 6f72 6520 6469 7265 6374 6f72 6965  Store directorie
-0000d680: 7320 696e 2077 6869 6368 2074 6865 2060  s in which the `
-0000d690: 2e2e 6020 7061 7274 7320 6f66 2074 6865  ..` parts of the
-0000d6a0: 2070 6174 686e 616d 6520 6172 6520 7265   pathname are re
-0000d6b0: 706c 6163 6564 2077 6974 6820 616e 2069  placed with an i
-0000d6c0: 6e74 6567 6572 2063 6f75 6e74 206f 6620  nteger count of 
-0000d6d0: 7468 6520 6e75 6d62 6572 206f 6620 602e  the number of `.
-0000d6e0: 2e60 2065 6e74 7269 6573 2028 6265 6361  .` entries (beca
-0000d6f0: 7573 6520 7765 2063 616e 2774 2075 7365  use we can't use
-0000d700: 2074 6865 2060 2e2e 6020 7265 6c61 7469   the `..` relati
-0000d710: 7665 2066 6f72 6d20 696e 2074 6865 204f  ve form in the O
-0000d720: 626a 6563 7420 5374 6f72 6529 2e0a 0a41  bject Store)...A
-0000d730: 7373 756d 696e 6720 6120 4e61 6d65 7370  ssuming a Namesp
-0000d740: 6163 6520 6361 6c6c 6564 2060 6465 7665  ace called `deve
-0000d750: 6c6f 706d 656e 7460 2061 6e64 2061 2057  lopment` and a W
-0000d760: 6f72 6b20 5265 7175 6972 656d 656e 7420  ork Requirement 
-0000d770: 6e61 6d65 6420 6074 6573 7472 756e 5f32  named `testrun_2
-0000d780: 3231 3130 382d 3132 3034 3034 2d37 6432  21108-120404-7d2
-0000d790: 602c 2074 6865 2066 6f6c 6c6f 7769 6e67  `, the following
-0000d7a0: 206c 6f63 6174 696f 6e73 2061 7265 2075   locations are u
-0000d7b0: 7365 6420 7768 656e 2075 706c 6f61 6469  sed when uploadi
-0000d7c0: 6e67 2066 696c 6573 2066 6f6c 6c6f 7769  ng files followi
-0000d7d0: 6e67 2074 6865 2070 6174 7465 726e 7320  ng the patterns 
-0000d7e0: 6162 6f76 653a 0a0a 6060 6073 6865 6c6c  above:..```shell
-0000d7f0: 0a22 696e 7075 7473 2220 3a20 5b22 6669  ."inputs" : ["fi
-0000d800: 6c65 5f31 2e74 7874 225d 202d 3e20 6465  le_1.txt"] -> de
-0000d810: 7665 6c6f 706d 656e 743a 3a74 6573 7472  velopment::testr
-0000d820: 756e 5f32 3231 3130 382d 3132 3034 3034  un_221108-120404
-0000d830: 2d37 6432 2f66 696c 655f 312e 7478 740a  -7d2/file_1.txt.
-0000d840: 2269 6e70 7574 7322 203a 205b 2264 6576  "inputs" : ["dev
-0000d850: 2f66 696c 655f 312e 7478 7422 5d20 2d3e  /file_1.txt"] ->
-0000d860: 2064 6576 656c 6f70 6d65 6e74 3a3a 7465   development::te
-0000d870: 7374 7275 6e5f 3232 3131 3038 2d31 3230  strun_221108-120
-0000d880: 3430 342d 3764 322f 6465 762f 6669 6c65  404-7d2/dev/file
+00008680: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008690: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000086a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000086b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000086c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000086d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000086e0: 2020 2020 2020 7c20 5965 7320 207c 2020        | Yes  |  
+000086f0: 2020 207c 2020 2020 2020 7c20 5965 7320     |      | Yes 
+00008700: 207c 0a7c 2060 7461 736b 5479 7065 7360   |.| `taskTypes`
+00008710: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008720: 7c20 5468 6520 6c69 7374 206f 6620 5461  | The list of Ta
+00008730: 736b 2054 7970 6573 2072 6571 7569 7265  sk Types require
+00008740: 6420 6279 2074 6865 2072 616e 6765 206f  d by the range o
+00008750: 6620 5461 736b 7320 696e 2061 2054 6173  f Tasks in a Tas
+00008760: 6b20 4772 6f75 702e 2045 2e67 2e2c 2060  k Group. E.g., `
+00008770: 5b22 646f 636b 6572 222c 2062 6173 6822  ["docker", bash"
+00008780: 5d60 2e20 2020 2020 2020 2020 2020 2020  ]`.             
+00008790: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000087a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000087b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000087c0: 2020 2020 2020 2020 2020 207c 2020 2020             |    
+000087d0: 2020 7c20 5965 7320 7c20 5965 7320 207c    | Yes | Yes  |
+000087e0: 2020 2020 2020 7c0a 7c20 6074 6173 6b73        |.| `tasks
+000087f0: 5065 7257 6f72 6b65 7260 2020 2020 2020  PerWorker`      
+00008800: 2020 2020 207c 2044 6574 6572 6d69 6e65       | Determine
+00008810: 7320 7468 6520 6e75 6d62 6572 206f 6620  s the number of 
+00008820: 576f 726b 6572 2063 6c61 696d 7320 6261  Worker claims ba
+00008830: 7365 6420 6f6e 2073 706c 6974 7469 6e67  sed on splitting
+00008840: 2074 6865 206e 756d 6265 7220 6f66 2075   the number of u
+00008850: 6e66 696e 6973 6865 6420 5461 736b 7320  nfinished Tasks 
+00008860: 6163 726f 7373 2057 6f72 6b65 7273 2e20  across Workers. 
+00008870: 452e 672e 2c20 6031 602e 2020 2020 2020  E.g., `1`.      
+00008880: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008890: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000088a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000088b0: 7c20 5965 7320 207c 2059 6573 207c 2059  | Yes  | Yes | Y
+000088c0: 6573 2020 7c20 2020 2020 207c 0a7c 2060  es  |      |.| `
+000088d0: 7570 6c6f 6164 4669 6c65 7360 2020 2020  uploadFiles`    
+000088e0: 2020 2020 2020 2020 2020 7c20 5468 6520            | The 
+000088f0: 6c69 7374 206f 6620 6669 6c65 7320 746f  list of files to
+00008900: 2062 6520 7570 6c6f 6164 6564 2074 6f20   be uploaded to 
+00008910: 7468 6520 5965 6c6c 6f77 446f 6720 4f62  the YellowDog Ob
+00008920: 6a65 6374 2053 746f 7265 2e20 452e 672e  ject Store. E.g.
+00008930: 2c20 284a 534f 4e29 3a20 605b 7b22 6c6f  , (JSON): `[{"lo
+00008940: 6361 6c50 6174 6822 3a20 6669 6c65 5f31  calPath": file_1
+00008950: 2e74 7874 222c 2022 7570 6c6f 6164 5061  .txt", "uploadPa
+00008960: 7468 223a 2022 6669 6c65 5f31 2e74 7874  th": "file_1.txt
+00008970: 227d 5d60 2e20 2020 2020 2020 2020 2020  "}]`.           
+00008980: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008990: 2020 2020 207c 2059 6573 2020 7c20 5965       | Yes  | Ye
+000089a0: 7320 7c20 5965 7320 207c 2059 6573 2020  s | Yes  | Yes  
+000089b0: 7c0a 7c20 6076 6370 7573 6020 2020 2020  |.| `vcpus`     
+000089c0: 2020 2020 2020 2020 2020 2020 2020 207c                 |
+000089d0: 2052 616e 6765 2063 6f6e 7374 7261 696e   Range constrain
+000089e0: 7420 6f6e 206e 756d 6265 7220 6f66 2076  t on number of v
+000089f0: 4350 5573 2074 6861 7420 6172 6520 7265  CPUs that are re
+00008a00: 7175 6972 6564 2074 6f20 6578 6563 7574  quired to execut
+00008a10: 6520 5461 736b 7320 452e 672e 2c20 605b  e Tasks E.g., `[
+00008a20: 322e 302c 2034 2e30 5d60 2e20 2020 2020  2.0, 4.0]`.     
+00008a30: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008a40: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008a50: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008a60: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008a70: 2020 2020 2020 2020 2020 7c20 5965 7320            | Yes 
+00008a80: 207c 2059 6573 207c 2059 6573 2020 7c20   | Yes | Yes  | 
+00008a90: 2020 2020 207c 0a7c 2060 7665 7269 6679       |.| `verify
+00008aa0: 4174 5374 6172 7460 2020 2020 2020 2020  AtStart`        
+00008ab0: 2020 2020 7c20 4120 6c69 7374 206f 6620      | A list of 
+00008ac0: 6669 6c65 7320 7265 7175 6972 6564 2062  files required b
+00008ad0: 7920 6120 5461 736b 2e20 4d75 7374 2062  y a Task. Must b
+00008ae0: 6520 7072 6573 656e 7420 7768 656e 2074  e present when t
+00008af0: 6865 2054 6173 6b20 6973 2072 6561 6479  he Task is ready
+00008b00: 2074 6f20 7374 6172 7420 6f72 2074 6865   to start or the
+00008b10: 2054 6173 6b20 7769 6c6c 2066 6169 6c2e   Task will fail.
+00008b20: 2045 2e67 2e3a 2060 5b22 7461 736b 5f67   E.g.: `["task_g
+00008b30: 726f 7570 5f31 2f74 6173 6b5f 312f 7265  roup_1/task_1/re
+00008b40: 7375 6c74 732e 7478 7422 5d60 2e20 2020  sults.txt"]`.   
+00008b50: 2020 2020 2020 2020 2020 2020 2020 207c                 |
+00008b60: 2059 6573 2020 7c20 5965 7320 7c20 5965   Yes  | Yes | Ye
+00008b70: 7320 207c 2059 6573 2020 7c0a 7c20 6076  s  | Yes  |.| `v
+00008b80: 6572 6966 7957 6169 7460 2020 2020 2020  erifyWait`      
+00008b90: 2020 2020 2020 2020 207c 2041 206c 6973           | A lis
+00008ba0: 7420 6f66 2066 696c 6573 2072 6571 7569  t of files requi
+00008bb0: 7265 6420 6279 2061 2054 6173 6b2e 2054  red by a Task. T
+00008bc0: 6865 2054 6173 6b20 7769 6c6c 2077 6169  he Task will wai
+00008bd0: 7420 756e 7469 6c20 7468 6520 6669 6c65  t until the file
+00008be0: 7320 6172 6520 6176 6169 6c61 626c 6520  s are available 
+00008bf0: 6265 666f 7265 2073 7461 7274 696e 672e  before starting.
+00008c00: 2045 2e67 2e3a 2060 5b22 7461 736b 5f67   E.g.: `["task_g
+00008c10: 726f 7570 5f31 2f74 6173 6b5f 312f 7265  roup_1/task_1/re
+00008c20: 7375 6c74 732e 7478 7422 5d60 2e20 2020  sults.txt"]`.   
+00008c30: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008c40: 2020 2020 7c20 5965 7320 207c 2059 6573      | Yes  | Yes
+00008c50: 207c 2059 6573 2020 7c20 5965 7320 207c   | Yes  | Yes  |
+00008c60: 0a7c 2060 776f 726b 6572 5461 6773 6020  .| `workerTags` 
+00008c70: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00008c80: 5468 6520 6c69 7374 206f 6620 576f 726b  The list of Work
+00008c90: 6572 2054 6167 7320 7468 6174 2077 696c  er Tags that wil
+00008ca0: 6c20 6265 2075 7365 6420 746f 206d 6174  l be used to mat
+00008cb0: 6368 2061 6761 696e 7374 2074 6865 2057  ch against the W
+00008cc0: 6f72 6b65 7220 5461 6720 6f66 2061 2063  orker Tag of a c
+00008cd0: 616e 6469 6461 7465 2057 6f72 6b65 722e  andidate Worker.
+00008ce0: 2045 2e67 2e2c 2060 5b22 7461 675f 7822   E.g., `["tag_x"
+00008cf0: 2c20 2274 6167 5f79 225d 602e 2020 2020  , "tag_y"]`.    
+00008d00: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008d10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008d20: 2020 2020 2020 2020 207c 2059 6573 2020           | Yes  
+00008d30: 7c20 5965 7320 7c20 5965 7320 207c 2020  | Yes | Yes  |  
+00008d40: 2020 2020 7c0a 7c20 6077 6f72 6b52 6571      |.| `workReq
+00008d50: 7569 7265 6d65 6e74 4461 7461 6020 2020  uirementData`   
+00008d60: 2020 207c 2054 6865 206e 616d 6520 6f66     | The name of
+00008d70: 2074 6865 2066 696c 6520 636f 6e74 6169   the file contai
+00008d80: 6e69 6e67 2074 6865 204a 534f 4e20 646f  ning the JSON do
+00008d90: 6375 6d65 6e74 2069 6e20 7768 6963 6820  cument in which 
+00008da0: 7468 6520 576f 726b 2052 6571 7569 7265  the Work Require
+00008db0: 6d65 6e74 2069 7320 6465 6669 6e65 642e  ment is defined.
+00008dc0: 2045 2e67 2e2c 2060 2274 6573 745f 776f   E.g., `"test_wo
+00008dd0: 726b 7265 712e 6a73 6f6e 2260 2e20 2020  rkreq.json"`.   
+00008de0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008df0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00008e00: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00008e10: 5965 7320 207c 2020 2020 207c 2020 2020  Yes  |     |    
+00008e20: 2020 7c20 2020 2020 207c 0a0a 2323 2041    |      |..## A
+00008e30: 7574 6f6d 6174 6963 2050 726f 7065 7274  utomatic Propert
+00008e40: 6965 730a 0a49 6e20 6164 6469 7469 6f6e  ies..In addition
+00008e50: 2074 6f20 7468 6520 696e 6865 7269 7461   to the inherita
+00008e60: 6e63 6520 6d65 6368 616e 6973 6d2c 2073  nce mechanism, s
+00008e70: 6f6d 6520 7072 6f70 6572 7469 6573 2061  ome properties a
+00008e80: 7265 2073 6574 2061 7574 6f6d 6174 6963  re set automatic
+00008e90: 616c 6c79 2062 7920 7468 6520 6079 642d  ally by the `yd-
+00008ea0: 7375 626d 6974 6020 636f 6d6d 616e 642c  submit` command,
+00008eb0: 2061 7320 6120 7573 6167 6520 636f 6e76   as a usage conv
+00008ec0: 656e 6965 6e63 6520 6966 2074 6865 7927  enience if they'
+00008ed0: 7265 206e 6f74 2065 7870 6c69 6369 746c  re not explicitl
+00008ee0: 7920 7072 6f76 6964 6564 2e0a 0a23 2323  y provided...###
+00008ef0: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+00008f00: 742c 2054 6173 6b20 4772 6f75 7020 616e  t, Task Group an
+00008f10: 6420 5461 736b 204e 616d 696e 670a 0a2d  d Task Naming..-
+00008f20: 2054 6865 202a 2a57 6f72 6b20 5265 7175   The **Work Requ
+00008f30: 6972 656d 656e 742a 2a20 6e61 6d65 2069  irement** name i
+00008f40: 7320 6175 746f 6d61 7469 6361 6c6c 7920  s automatically 
+00008f50: 7365 7420 7573 696e 6720 6120 636f 6e63  set using a conc
+00008f60: 6174 656e 6174 696f 6e20 6f66 2074 6865  atenation of the
+00008f70: 2060 7461 6760 2070 726f 7065 7274 792c   `tag` property,
+00008f80: 2061 2055 5443 2074 696d 6573 7461 6d70   a UTC timestamp
+00008f90: 2c20 616e 6420 7468 7265 6520 7261 6e64  , and three rand
+00008fa0: 6f6d 2068 6578 2063 6861 7261 6374 6572  om hex character
+00008fb0: 733a 2065 2c67 2c2e 2060 6d79 7461 675f  s: e,g,. `mytag_
+00008fc0: 3232 3130 3234 2d31 3535 3532 342d 3430  221024-155524-40
+00008fd0: 6160 2e0a 2d20 2a2a 5461 736b 2047 726f  a`..- **Task Gro
+00008fe0: 7570 2a2a 206e 616d 6573 2061 7265 2061  up** names are a
+00008ff0: 7574 6f6d 6174 6963 616c 6c79 2063 7265  utomatically cre
+00009000: 6174 6564 2066 6f72 2061 6e79 2054 6173  ated for any Tas
+00009010: 6b20 4772 6f75 7020 7468 6174 2069 7320  k Group that is 
+00009020: 6e6f 7420 6578 706c 6963 6974 6c79 206e  not explicitly n
+00009030: 616d 6564 2c20 7573 696e 6720 6e61 6d65  amed, using name
+00009040: 7320 6f66 2074 6865 2066 6f72 6d20 6074  s of the form `t
+00009050: 6173 6b5f 6772 6f75 705f 3160 2028 6f72  ask_group_1` (or
+00009060: 2060 7461 736b 5f67 726f 7570 5f30 3160   `task_group_01`
+00009070: 2c20 6574 632e 2c20 666f 7220 6c61 7267  , etc., for larg
+00009080: 6572 206e 756d 6265 7273 206f 6620 5461  er numbers of Ta
+00009090: 736b 2047 726f 7570 7329 2e20 5461 736b  sk Groups). Task
+000090a0: 2047 726f 7570 206e 756d 6265 7273 2063   Group numbers c
+000090b0: 616e 2061 6c73 6f20 6265 2069 6e63 6c75  an also be inclu
+000090c0: 6465 6420 696e 2075 7365 722d 6465 6669  ded in user-defi
+000090d0: 6e65 6420 5461 736b 2047 726f 7570 206e  ned Task Group n
+000090e0: 616d 6573 2075 7369 6e67 2074 6865 2060  ames using the `
+000090f0: 7b7b 7461 736b 5f67 726f 7570 5f6e 756d  {{task_group_num
+00009100: 6265 727d 7d60 2076 6172 6961 626c 6520  ber}}` variable 
+00009110: 7375 6273 7469 7475 7469 6f6e 2064 6973  substitution dis
+00009120: 6375 7373 6564 2062 656c 6f77 2e0a 2d20  cussed below..- 
+00009130: 2a2a 5461 736b 2a2a 206e 616d 6573 2061  **Task** names a
+00009140: 7265 2061 7574 6f6d 6174 6963 616c 6c79  re automatically
+00009150: 2063 7265 6174 6564 2066 6f72 2061 6e79   created for any
+00009160: 2054 6173 6b20 7468 6174 2069 7320 6e6f   Task that is no
+00009170: 7420 6578 706c 6963 6974 6c79 206e 616d  t explicitly nam
+00009180: 6564 2c20 7573 696e 6720 6e61 6d65 7320  ed, using names 
+00009190: 6f66 2074 6865 2066 6f72 6d20 6074 6173  of the form `tas
+000091a0: 6b5f 3160 2028 6f72 2060 7461 736b 5f30  k_1` (or `task_0
+000091b0: 3160 2c20 6574 632e 2c20 666f 7220 6c61  1`, etc., for la
+000091c0: 7267 6572 206e 756d 6265 7273 206f 6620  rger numbers of 
+000091d0: 5461 736b 7329 2e20 5468 6520 5461 736b  Tasks). The Task
+000091e0: 2063 6f75 6e74 6572 2072 6573 6574 7320   counter resets 
+000091f0: 666f 7220 6561 6368 2064 6966 6665 7265  for each differe
+00009200: 6e74 2054 6173 6b20 4772 6f75 702e 2054  nt Task Group. T
+00009210: 6173 6b20 6e75 6d62 6572 7320 6361 6e20  ask numbers can 
+00009220: 616c 736f 2062 6520 696e 636c 7564 6564  also be included
+00009230: 2069 6e20 7573 6572 2d64 6566 696e 6564   in user-defined
+00009240: 2054 6173 6b20 6e61 6d65 7320 7573 696e   Task names usin
+00009250: 6720 7468 6520 607b 7b74 6173 6b5f 6e75  g the `{{task_nu
+00009260: 6d62 6572 7d7d 6020 7661 7269 6162 6c65  mber}}` variable
+00009270: 2073 7562 7374 6974 7574 696f 6e20 6469   substitution di
+00009280: 7363 7573 7365 6420 6265 6c6f 772e 0a0a  scussed below...
+00009290: 2323 2320 5461 736b 2054 7970 6573 0a0a  ### Task Types..
+000092a0: 2d20 4966 2060 7461 736b 5479 7065 6020  - If `taskType` 
+000092b0: 6973 2073 6574 206f 6e6c 7920 6174 2074  is set only at t
+000092c0: 6865 2054 4f4d 4c20 6669 6c65 206c 6576  he TOML file lev
+000092d0: 656c 2c20 7468 656e 2060 7461 736b 5479  el, then `taskTy
+000092e0: 7065 7360 2069 7320 6175 746f 6d61 7469  pes` is automati
+000092f0: 6361 6c6c 7920 706f 7075 6c61 7465 6420  cally populated 
+00009300: 666f 7220 5461 736b 2047 726f 7570 732c  for Task Groups,
+00009310: 2075 6e6c 6573 7320 6f76 6572 7269 6464   unless overridd
+00009320: 656e 2e0a 2d20 4966 2060 7461 736b 5479  en..- If `taskTy
+00009330: 7065 6020 6973 2073 6574 2061 7420 7468  pe` is set at th
+00009340: 6520 5461 736b 206c 6576 656c 2c20 7468  e Task level, th
+00009350: 656e 2060 7461 736b 5479 7065 7360 2069  en `taskTypes` i
+00009360: 7320 6175 746f 6d61 7469 6361 6c6c 7920  s automatically 
+00009370: 706f 7075 6c61 7465 6420 666f 7220 7468  populated for th
+00009380: 6520 5461 736b 2047 726f 7570 7320 6c65  e Task Groups le
+00009390: 7665 6c20 7573 696e 6720 7468 6520 6163  vel using the ac
+000093a0: 6375 6d75 6c61 7465 6420 5461 736b 2054  cumulated Task T
+000093b0: 7970 6573 2066 726f 6d20 7468 6520 5461  ypes from the Ta
+000093c0: 736b 7320 696e 636c 7564 6564 2069 6e20  sks included in 
+000093d0: 6561 6368 2054 6173 6b20 4772 6f75 702c  each Task Group,
+000093e0: 2075 6e6c 6573 7320 6f76 6572 7269 6464   unless overridd
+000093f0: 656e 2e0a 2d20 4966 2060 7461 736b 5479  en..- If `taskTy
+00009400: 7065 7360 2069 7320 7365 7420 6174 2074  pes` is set at t
+00009410: 6865 2054 6173 6b20 4772 6f75 7020 4c65  he Task Group Le
+00009420: 7665 6c2c 2061 6e64 2068 6173 206f 6e6c  vel, and has onl
+00009430: 7920 6f6e 6520 5461 736b 2054 7970 6520  y one Task Type 
+00009440: 656e 7472 792c 2074 6865 6e20 6074 6173  entry, then `tas
+00009450: 6b54 7970 6560 2069 7320 6175 746f 6d61  kType` is automa
+00009460: 7469 6361 6c6c 7920 7365 7420 6174 2074  tically set at t
+00009470: 6865 2054 6173 6b20 4c65 7665 6c20 7573  he Task Level us
+00009480: 696e 6720 7468 6520 7369 6e67 6c65 2054  ing the single T
+00009490: 6173 6b20 5479 7065 2c20 756e 6c65 7373  ask Type, unless
+000094a0: 206f 7665 7272 6964 6465 6e2e 0a0a 466f   overridden...Fo
+000094b0: 7220 7468 6520 2a2a 6062 6173 6860 2a2a  r the **`bash`**
+000094c0: 2c20 2a2a 6070 6f77 6572 7368 656c 6c60  , **`powershell`
+000094d0: 2a2a 2c20 2a2a 6063 6d64 602a 2a2f 2a2a  **, **`cmd`**/**
+000094e0: 6062 6174 602a 2a20 616e 6420 2a2a 6064  `bat`** and **`d
+000094f0: 6f63 6b65 7260 2a2a 2074 6173 6b20 7479  ocker`** task ty
+00009500: 7065 732c 2073 6f6d 6520 6175 746f 6d61  pes, some automa
+00009510: 7469 6320 7072 6f63 6573 7369 6e67 2077  tic processing w
+00009520: 696c 6c20 6265 2070 6572 666f 726d 6564  ill be performed
+00009530: 2069 6620 7468 6520 2a2a 6065 7865 6375   if the **`execu
+00009540: 7461 626c 6560 2a2a 2070 726f 7065 7274  table`** propert
+00009550: 7920 6973 2073 6574 2e0a 0a23 2323 2320  y is set...#### 
+00009560: 4261 7368 2c20 5079 7468 6f6e 2c20 506f  Bash, Python, Po
+00009570: 7765 7253 6865 6c6c 2061 6e64 2063 6d64  werShell and cmd
+00009580: 2f62 6174 2054 6173 6b73 0a0a 4173 2061  /bat Tasks..As a
+00009590: 2063 6f6e 7665 6e69 656e 6365 2c20 666f   convenience, fo
+000095a0: 7220 7468 6520 2a2a 6062 6173 6860 2a2a  r the **`bash`**
+000095b0: 2c20 2a2a 6070 7974 686f 6e60 2a2a 2c20  , **`python`**, 
+000095c0: 2a2a 6070 6f77 6572 7368 656c 6c60 2a2a  **`powershell`**
+000095d0: 2c20 616e 6420 2a2a 6063 6d64 602a 2a20  , and **`cmd`** 
+000095e0: 286f 7220 2a2a 6062 6174 602a 2a29 2054  (or **`bat`**) T
+000095f0: 6173 6b20 5479 7065 732c 2074 6865 2073  ask Types, the s
+00009600: 6372 6970 7420 6e6f 6d69 6e61 7465 6420  cript nominated 
+00009610: 696e 2074 6865 202a 2a60 6578 6563 7574  in the **`execut
+00009620: 6162 6c65 602a 2a20 7072 6f70 6572 7479  able`** property
+00009630: 2069 7320 6175 746f 6d61 7469 6361 6c6c   is automaticall
+00009640: 7920 6164 6465 6420 746f 2074 6865 2060  y added to the `
+00009650: 696e 7075 7473 6020 6c69 7374 2028 6966  inputs` list (if
+00009660: 206e 6f74 2061 6c72 6561 6479 2070 7265   not already pre
+00009670: 7365 6e74 292e 2054 6869 7320 6d65 616e  sent). This mean
+00009680: 7320 7468 6520 7363 7269 7074 2066 696c  s the script fil
+00009690: 6520 7769 6c6c 2062 6520 7570 6c6f 6164  e will be upload
+000096a0: 6564 2074 6f20 7468 6520 4f62 6a65 6374  ed to the Object
+000096b0: 2053 746f 7265 2c20 616e 6420 6d61 6465   Store, and made
+000096c0: 2061 2072 6571 7569 7265 6d65 6e74 206f   a requirement o
+000096d0: 6620 7468 6520 5461 736b 2077 6865 6e20  f the Task when 
+000096e0: 6974 2072 756e 732e 0a0a 5573 696e 6720  it runs...Using 
+000096f0: 6120 4261 7368 2054 6173 6b20 6173 2061  a Bash Task as a
+00009700: 6e20 6578 616d 706c 6520 2869 6e20 544f  n example (in TO
+00009710: 4d4c 2066 6f72 6d29 3a0a 0a60 6060 746f  ML form):..```to
+00009720: 6d6c 0a74 6173 6b54 7970 6520 3d20 2262  ml.taskType = "b
+00009730: 6173 6822 0a65 7865 6375 7461 626c 6520  ash".executable 
+00009740: 3d20 226d 795f 6261 7368 5f73 6372 6970  = "my_bash_scrip
+00009750: 742e 7368 220a 6172 6775 6d65 6e74 7320  t.sh".arguments 
+00009760: 3d20 5b22 3122 2c20 2232 222c 2022 3322  = ["1", "2", "3"
+00009770: 5d0a 6060 600a 6973 2065 7175 6976 616c  ].```.is equival
+00009780: 656e 7420 746f 3a0a 0a60 6060 746f 6d6c  ent to:..```toml
+00009790: 0a74 6173 6b54 7970 6520 3d20 2262 6173  .taskType = "bas
+000097a0: 6822 0a69 6e70 7574 7320 3d20 5b22 6d79  h".inputs = ["my
+000097b0: 5f62 6173 685f 7363 7269 7074 2e73 6822  _bash_script.sh"
+000097c0: 5d0a 6172 6775 6d65 6e74 7320 3d20 5b22  ].arguments = ["
+000097d0: 7b7b 7772 5f6e 616d 657d 7d2f 6d79 5f62  {{wr_name}}/my_b
+000097e0: 6173 685f 7363 7269 7074 2e73 6822 2c20  ash_script.sh", 
+000097f0: 2231 222c 2022 3222 2c20 2233 225d 0a60  "1", "2", "3"].`
+00009800: 6060 0a0a 496e 2074 6865 2063 6173 6520  ``..In the case 
+00009810: 6f66 2057 696e 646f 7773 2062 6174 6368  of Windows batch
+00009820: 2028 602e 6261 7460 2920 6669 6c65 732c   (`.bat`) files,
+00009830: 2061 2060 2f63 6020 666c 6167 2069 7320   a `/c` flag is 
+00009840: 7072 6570 656e 6465 6420 746f 2074 6865  prepended to the
+00009850: 2060 636d 642e 6578 6560 2061 7267 756d   `cmd.exe` argum
+00009860: 656e 7420 6c69 7374 2074 6f20 656e 7375  ent list to ensu
+00009870: 7265 2063 6f72 7265 6374 2065 7865 6375  re correct execu
+00009880: 7469 6f6e 2062 6168 6176 696f 7572 2e20  tion bahaviour. 
+00009890: 466f 7220 6578 616d 706c 653a 0a0a 6060  For example:..``
+000098a0: 6074 6f6d 6c0a 7461 736b 5479 7065 203d  `toml.taskType =
+000098b0: 2022 636d 6422 2020 2320 6f72 2022 6261   "cmd"  # or "ba
+000098c0: 7422 0a65 7865 6375 7461 626c 6520 3d20  t".executable = 
+000098d0: 226d 795f 7363 7269 7074 2e62 6174 220a  "my_script.bat".
+000098e0: 6172 6775 6d65 6e74 7320 3d20 5b22 3122  arguments = ["1"
+000098f0: 2c20 2232 222c 2022 3322 5d0a 6060 600a  , "2", "3"].```.
+00009900: 0a69 7320 6571 7569 7661 6c65 6e74 2074  .is equivalent t
+00009910: 6f3a 0a0a 6060 6074 6f6d 6c0a 7461 736b  o:..```toml.task
+00009920: 5479 7065 203d 2022 636d 6422 2020 2320  Type = "cmd"  # 
+00009930: 6f72 2022 6261 7422 0a69 6e70 7574 7320  or "bat".inputs 
+00009940: 3d20 5b22 6d79 5f73 6372 6970 742e 6261  = ["my_script.ba
+00009950: 7422 5d0a 6172 6775 6d65 6e74 7320 3d20  t"].arguments = 
+00009960: 5b22 2f63 222c 2022 7b7b 7772 5f6e 616d  ["/c", "{{wr_nam
+00009970: 657d 7d5c 5c6d 795f 7363 7269 7074 2e62  e}}\\my_script.b
+00009980: 6174 222c 2022 3122 2c20 2232 222c 2022  at", "1", "2", "
+00009990: 3322 5d0a 6060 600a 0a4e 6f74 6520 7468  3"].```..Note th
+000099a0: 6520 605c 5c60 2072 6571 7569 7265 6d65  e `\\` requireme
+000099b0: 6e74 2066 6f72 2064 6972 6563 746f 7279  nt for directory
+000099c0: 2073 6570 6172 6174 6f72 7320 7768 656e   separators when
+000099d0: 2064 6566 696e 696e 6720 5461 736b 7320   defining Tasks 
+000099e0: 6f6e 2057 696e 646f 7773 2068 6f73 7473  on Windows hosts
+000099f0: 2e20 4e6f 7465 2061 6c73 6f20 7468 6174  . Note also that
+00009a00: 2074 6865 2060 2f63 6020 6973 2072 6571   the `/c` is req
+00009a10: 7569 7265 6420 7768 656e 2072 756e 6e69  uired when runni
+00009a20: 6e67 2063 6f6d 6d61 6e64 7320 6f72 2062  ng commands or b
+00009a30: 6174 6368 2073 6372 6970 7473 2075 7369  atch scripts usi
+00009a40: 6e67 2060 636d 642e 6578 6560 2c20 6f74  ng `cmd.exe`, ot
+00009a50: 6865 7277 6973 6520 7468 6520 6063 6d64  herwise the `cmd
+00009a60: 2e65 7865 6020 7072 6f63 6573 7320 6372  .exe` process cr
+00009a70: 6561 7465 6420 746f 2065 7865 6375 7465  eated to execute
+00009a80: 2074 6865 2054 6173 6b20 7769 6c6c 206e   the Task will n
+00009a90: 6f74 2074 6572 6d69 6e61 7465 2e0a 0a23  ot terminate...#
+00009aa0: 2323 2320 446f 636b 6572 2054 6173 6b73  ### Docker Tasks
+00009ab0: 0a0a 466f 7220 7468 6520 2a2a 6064 6f63  ..For the **`doc
+00009ac0: 6b65 7260 2a2a 2054 6173 6b20 5479 7065  ker`** Task Type
+00009ad0: 2c20 7468 6520 7661 7269 6162 6c65 7320  , the variables 
+00009ae0: 7375 7070 6c69 6564 2069 6e20 7468 6520  supplied in the 
+00009af0: 6064 6f63 6b65 7245 6e76 6972 6f6e 6d65  `dockerEnvironme
+00009b00: 6e74 6020 7072 6f70 6572 7479 2061 7265  nt` property are
+00009b10: 2075 6e70 6163 6b65 6420 696e 746f 2074   unpacked into t
+00009b20: 6865 2061 7267 756d 656e 7420 6c69 7374  he argument list
+00009b30: 2061 7320 602d 2d65 6e76 6020 656e 7472   as `--env` entr
+00009b40: 6965 732c 2074 6865 2044 6f63 6b65 7220  ies, the Docker 
+00009b50: 636f 6e74 6169 6e65 7220 6e61 6d65 2073  container name s
+00009b60: 7570 706c 6965 6420 696e 2074 6865 2060  upplied in the `
+00009b70: 6578 6563 7574 6162 6c65 6020 7072 6f70  executable` prop
+00009b80: 6572 7479 2069 7320 7468 656e 2061 6464  erty is then add
+00009b90: 6564 2074 6f20 7468 6520 6172 6775 6d65  ed to the argume
+00009ba0: 6e74 7320 6c69 7374 2c20 666f 6c6c 6f77  nts list, follow
+00009bb0: 6564 2062 7920 7468 6520 6172 6775 6d65  ed by the argume
+00009bc0: 6e74 7320 7375 7070 6c69 6564 2069 6e20  nts supplied in 
+00009bd0: 7468 6520 6061 7267 756d 656e 7473 6020  the `arguments` 
+00009be0: 7072 6f70 6572 7479 2e20 5468 6520 6064  property. The `d
+00009bf0: 6f63 6b65 7255 7365 726e 616d 6560 2061  ockerUsername` a
+00009c00: 6e64 2060 646f 636b 6572 5061 7373 776f  nd `dockerPasswo
+00009c10: 7264 6020 7072 6f70 6572 7469 6573 2c20  rd` properties, 
+00009c20: 6966 2073 7570 706c 6965 642c 2061 7265  if supplied, are
+00009c30: 2061 6464 6564 2074 6f20 7468 6520 6065   added to the `e
+00009c40: 6e76 6972 6f6e 6d65 6e74 6020 7072 6f70  nvironment` prop
+00009c50: 6572 7479 2e0a 0a46 6f72 2065 7861 6d70  erty...For examp
+00009c60: 6c65 3a0a 6060 6074 6f6d 6c0a 7461 736b  le:.```toml.task
+00009c70: 5479 7065 203d 2022 646f 636b 6572 220a  Type = "docker".
+00009c80: 6578 6563 7574 6162 6c65 203d 2022 6d79  executable = "my
+00009c90: 5f64 6f63 6b65 7268 7562 5f72 6570 6f2f  _dockerhub_repo/
+00009ca0: 6d79 5f63 6f6e 7461 696e 6572 5f69 6d61  my_container_ima
+00009cb0: 6765 220a 646f 636b 6572 456e 7669 726f  ge".dockerEnviro
+00009cc0: 6e6d 656e 7420 3d20 7b45 3120 3d20 2245  nment = {E1 = "E
+00009cd0: 6565 4f6e 6522 7d0a 646f 636b 6572 5573  eeOne"}.dockerUs
+00009ce0: 6572 6e61 6d65 203d 2022 6d79 5f75 7365  ername = "my_use
+00009cf0: 7222 0a64 6f63 6b65 7250 6173 7377 6f72  r".dockerPasswor
+00009d00: 6420 3d20 226d 795f 7061 7373 776f 7264  d = "my_password
+00009d10: 220a 6172 6775 6d65 6e74 7320 3d20 5b22  ".arguments = ["
+00009d20: 3122 2c20 2232 222c 2022 3322 5d0a 6060  1", "2", "3"].``
+00009d30: 600a 0a69 7320 6571 7569 7661 6c65 6e74  `..is equivalent
+00009d40: 2074 6f20 7468 6520 666f 6c6c 6f77 696e   to the followin
+00009d50: 6720 6265 696e 6720 7365 6e74 2066 6f72  g being sent for
+00009d60: 2070 726f 6365 7373 696e 6720 6279 2074   processing by t
+00009d70: 6865 2060 646f 636b 6572 6020 5461 736b  he `docker` Task
+00009d80: 2054 7970 652c 2074 6865 2059 656c 6c6f   Type, the Yello
+00009d90: 7744 6f67 2076 6572 7369 6f6e 206f 6620  wDog version of 
+00009da0: 7768 6963 6820 7769 6c6c 206c 6f67 2069  which will log i
+00009db0: 6e20 746f 2074 6865 2044 6f63 6b65 7220  n to the Docker 
+00009dc0: 7265 706f 2028 6966 2072 6571 7569 7265  repo (if require
+00009dd0: 6429 2074 6865 6e20 6973 7375 6520 6120  d) then issue a 
+00009de0: 6064 6f63 6b65 7220 7275 6e60 2063 6f6d  `docker run` com
+00009df0: 6d61 6e64 2077 6974 6820 7468 6520 6172  mand with the ar
+00009e00: 6775 6d65 6e74 7320 7375 7070 6c69 6564  guments supplied
+00009e10: 3a0a 0a60 6060 746f 6d6c 0a74 6173 6b54  :..```toml.taskT
+00009e20: 7970 6520 3d20 2264 6f63 6b65 7222 0a61  ype = "docker".a
+00009e30: 7267 756d 656e 7473 203d 205b 222d 2d65  rguments = ["--e
+00009e40: 6e76 2045 313d 4565 654f 6e65 222c 2022  nv E1=EeeOne", "
+00009e50: 6d79 5f64 6f63 6b65 7268 7562 7265 706f  my_dockerhubrepo
+00009e60: 2f6d 795f 636f 6e74 6169 6e65 725f 696d  /my_container_im
+00009e70: 6167 6522 2c20 2231 222c 2022 3222 2c20  age", "1", "2", 
+00009e80: 2233 225d 0a65 6e76 6972 6f6e 6d65 6e74  "3"].environment
+00009e90: 203d 207b 444f 434b 4552 5f55 5345 524e   = {DOCKER_USERN
+00009ea0: 414d 4520 3d20 226d 795f 7573 6572 222c  AME = "my_user",
+00009eb0: 2044 4f43 4b45 525f 5041 5353 574f 5244   DOCKER_PASSWORD
+00009ec0: 203d 2022 6d79 5f70 6173 7377 6f72 6422   = "my_password"
+00009ed0: 7d0a 6060 600a 0a23 2323 2320 4261 7368  }.```..#### Bash
+00009ee0: 2c20 5079 7468 6f6e 2c20 506f 7765 7253  , Python, PowerS
+00009ef0: 6865 6c6c 2c20 636d 642e 6578 652f 6261  hell, cmd.exe/ba
+00009f00: 7463 682c 2061 6e64 2044 6f63 6b65 7220  tch, and Docker 
+00009f10: 7769 7468 6f75 7420 4175 746f 6d61 7469  without Automati
+00009f20: 6320 5072 6f63 6573 7369 6e67 0a0a 4966  c Processing..If
+00009f30: 2074 6865 2060 6578 6563 7574 6162 6c65   the `executable
+00009f40: 6020 7072 6f70 6572 7479 2069 7320 6e6f  ` property is no
+00009f50: 7420 7375 7070 6c69 6564 2c20 7468 6520  t supplied, the 
+00009f60: 6175 746f 6d61 7469 6320 7072 6f63 6573  automatic proces
+00009f70: 7369 6e67 2064 6573 6372 6962 6564 2061  sing described a
+00009f80: 626f 7665 2066 6f72 2060 6261 7368 602c  bove for `bash`,
+00009f90: 2060 7079 7468 6f6e 602c 2060 706f 7765   `python`, `powe
+00009fa0: 7273 6865 6c6c 602c 2060 636d 6460 2028  rshell`, `cmd` (
+00009fb0: 6f72 2060 6261 7460 2920 616e 6420 6064  or `bat`) and `d
+00009fc0: 6f63 6b65 7260 2074 6173 6b20 7479 7065  ocker` task type
+00009fd0: 7320 6973 206e 6f74 2061 7070 6c69 6564  s is not applied
+00009fe0: 2e0a 0a23 2323 2054 6173 6b20 436f 756e  ...### Task Coun
+00009ff0: 7473 0a0a 5468 6973 2070 726f 7065 7274  ts..This propert
+0000a000: 7920 7769 6c6c 2065 7870 616e 6420 7468  y will expand th
+0000a010: 6520 6e75 6d62 6572 206f 6620 5461 736b  e number of Task
+0000a020: 7320 746f 206d 6174 6368 2060 7461 736b  s to match `task
+0000a030: 436f 756e 7460 2e0a 0a54 6865 2060 7461  Count`...The `ta
+0000a040: 736b 436f 756e 7460 2070 726f 7065 7274  skCount` propert
+0000a050: 7920 6361 6e20 6265 2073 6574 206f 6e6c  y can be set onl
+0000a060: 7920 696e 2074 6865 2060 776f 726b 5265  y in the `workRe
+0000a070: 7175 6972 656d 656e 7460 2073 6563 7469  quirement` secti
+0000a080: 6f6e 206f 6620 7468 6520 6063 6f6e 6669  on of the `confi
+0000a090: 672e 746f 6d6c 6020 6669 6c65 2c20 6f72  g.toml` file, or
+0000a0a0: 2069 6e20 7468 6520 6074 6173 6b47 726f   in the `taskGro
+0000a0b0: 7570 6020 7365 6374 696f 6e28 7329 206f  up` section(s) o
+0000a0c0: 6620 6120 4a53 4f4e 2057 6f72 6b20 5265  f a JSON Work Re
+0000a0d0: 7175 6972 656d 656e 7420 6465 6669 6e69  quirement defini
+0000a0e0: 7469 6f6e 2e0a 0a49 6e20 7468 6520 666f  tion...In the fo
+0000a0f0: 726d 6572 2063 6173 652c 2074 6865 2060  rmer case, the `
+0000a100: 7461 736b 436f 756e 7460 2061 7070 6c69  taskCount` appli
+0000a110: 6573 206f 6e6c 7920 746f 2074 6865 2054  es only to the T
+0000a120: 6173 6b20 7370 6563 6966 6965 6420 7769  ask specified wi
+0000a130: 7468 696e 2074 6865 2060 636f 6e66 6967  thin the `config
+0000a140: 2e74 6f6d 6c60 2066 696c 6520 616e 6420  .toml` file and 
+0000a150: 6973 206e 6f74 2069 6e68 6572 6974 6564  is not inherited
+0000a160: 2062 7920 4a53 4f4e 2057 6f72 6b20 5265   by JSON Work Re
+0000a170: 7175 6972 656d 656e 7420 7370 6563 6966  quirement specif
+0000a180: 6963 6174 696f 6e73 2e0a 0a49 6e20 7468  ications...In th
+0000a190: 6520 6c61 7474 6572 2063 6173 652c 2074  e latter case, t
+0000a1a0: 6865 2060 7461 736b 436f 756e 7460 2061  he `taskCount` a
+0000a1b0: 7070 6c69 6573 2074 6f20 7468 6520 5461  pplies to the Ta
+0000a1c0: 736b 2073 7065 6369 6669 6564 2077 6974  sk specified wit
+0000a1d0: 6869 6e20 7468 6520 5461 736b 2047 726f  hin the Task Gro
+0000a1e0: 7570 2c20 616e 6420 7468 6572 6520 6d75  up, and there mu
+0000a1f0: 7374 2062 6520 7a65 726f 206f 7220 6f6e  st be zero or on
+0000a200: 6520 5461 736b 2873 2920 6c69 7374 6564  e Task(s) listed
+0000a210: 2077 6974 6869 6e20 7468 6520 6772 6f75   within the grou
+0000a220: 7020 6f72 2060 7461 736b 436f 756e 7460  p or `taskCount`
+0000a230: 2069 7320 6967 6e6f 7265 642e 0a0a 2323   is ignored...##
+0000a240: 2045 7861 6d70 6c65 730a 0a23 2323 2054   Examples..### T
+0000a250: 4f4d 4c20 5072 6f70 6572 7469 6573 2069  OML Properties i
+0000a260: 6e20 7468 6520 6077 6f72 6b52 6571 7569  n the `workRequi
+0000a270: 7265 6d65 6e74 6020 5365 6374 696f 6e0a  rement` Section.
+0000a280: 0a48 6572 6527 7320 616e 2065 7861 6d70  .Here's an examp
+0000a290: 6c65 206f 6620 7468 6520 6077 6f72 6b52  le of the `workR
+0000a2a0: 6571 7569 7265 6d65 6e74 6020 7365 6374  equirement` sect
+0000a2b0: 696f 6e20 6f66 2061 2054 4f4d 4c20 636f  ion of a TOML co
+0000a2c0: 6e66 6967 7572 6174 696f 6e20 6669 6c65  nfiguration file
+0000a2d0: 2c20 7368 6f77 696e 6720 616c 6c20 7468  , showing all th
+0000a2e0: 6520 706f 7373 6962 6c65 2070 726f 7065  e possible prope
+0000a2f0: 7274 6965 7320 7468 6174 2063 616e 2062  rties that can b
+0000a300: 6520 7365 743a 0a0a 6060 6074 6f6d 6c0a  e set:..```toml.
+0000a310: 5b77 6f72 6b52 6571 7569 7265 6d65 6e74  [workRequirement
+0000a320: 5d0a 2020 2020 6172 6775 6d65 6e74 7320  ].    arguments 
+0000a330: 3d20 5b22 3122 2c20 2254 574f 225d 0a20  = ["1", "TWO"]. 
+0000a340: 2020 2063 6170 7475 7265 5461 736b 4f75     captureTaskOu
+0000a350: 7470 7574 203d 2074 7275 650a 2020 2020  tput = true.    
+0000a360: 636f 6d70 6c65 7465 6454 6173 6b54 746c  completedTaskTtl
+0000a370: 203d 2031 300a 2020 2020 6373 7646 696c   = 10.    csvFil
+0000a380: 6520 3d20 2266 696c 6531 2e63 7376 220a  e = "file1.csv".
+0000a390: 2020 2020 6373 7646 696c 6573 203d 205b      csvFiles = [
+0000a3a0: 2266 696c 6531 2e63 7376 222c 2022 6669  "file1.csv", "fi
+0000a3b0: 6c65 332e 6373 763a 3322 5d0a 2020 2020  le3.csv:3"].    
+0000a3c0: 646f 636b 6572 456e 7669 726f 6e6d 656e  dockerEnvironmen
+0000a3d0: 7420 3d20 7b4d 595f 444f 434b 4552 5f56  t = {MY_DOCKER_V
+0000a3e0: 4152 203d 2031 3030 7d0a 2020 2020 646f  AR = 100}.    do
+0000a3f0: 636b 6572 5061 7373 776f 7264 203d 2022  ckerPassword = "
+0000a400: 6d79 5061 7373 776f 7264 220a 2020 2020  myPassword".    
+0000a410: 646f 636b 6572 5573 6572 6e61 6d65 203d  dockerUsername =
+0000a420: 2022 6d79 5573 6572 6e61 6d65 220a 2020   "myUsername".  
+0000a430: 2020 656e 7669 726f 6e6d 656e 7420 3d20    environment = 
+0000a440: 7b4d 595f 5641 5220 3d20 3130 307d 0a20  {MY_VAR = 100}. 
+0000a450: 2020 2065 7863 6c75 7369 7665 576f 726b     exclusiveWork
+0000a460: 6572 7320 3d20 6661 6c73 650a 2020 2020  ers = false.    
+0000a470: 6578 6563 7574 6162 6c65 203d 2022 6d79  executable = "my
+0000a480: 2d63 6f6e 7461 696e 6572 220a 2020 2020  -container".    
+0000a490: 6669 6e69 7368 4966 416c 6c54 6173 6b73  finishIfAllTasks
+0000a4a0: 4669 6e69 7368 6564 203d 2074 7275 650a  Finished = true.
+0000a4b0: 2020 2020 6669 6e69 7368 4966 416e 7954      finishIfAnyT
+0000a4c0: 6173 6b46 6169 6c65 6420 3d20 6661 6c73  askFailed = fals
+0000a4d0: 650a 2020 2020 666c 6174 7465 6e49 6e70  e.    flattenInp
+0000a4e0: 7574 5061 7468 7320 3d20 6661 6c73 650a  utPaths = false.
+0000a4f0: 2020 2020 666c 6174 7465 6e55 706c 6f61      flattenUploa
+0000a500: 6450 6174 6873 203d 2066 616c 7365 0a20  dPaths = false. 
+0000a510: 2020 2066 756c 6669 6c4f 6e53 7562 6d69     fulfilOnSubmi
+0000a520: 7420 3d20 6661 6c73 650a 2020 2020 696e  t = false.    in
+0000a530: 7075 7473 203d 205b 0a20 2020 2020 2020  puts = [.       
+0000a540: 2022 2e2e 2f61 7070 2f6d 6169 6e2e 7079   "../app/main.py
+0000a550: 222c 0a20 2020 2020 2020 2022 2e2e 2f61  ",.        "../a
+0000a560: 7070 2f72 6571 7569 7265 6d65 6e74 732e  pp/requirements.
+0000a570: 7478 7422 0a20 2020 205d 0a20 2020 2069  txt".    ].    i
+0000a580: 6e70 7574 734f 7074 696f 6e61 6c20 3d20  nputsOptional = 
+0000a590: 5b22 6f70 7469 6f6e 616c 2e74 7874 225d  ["optional.txt"]
+0000a5a0: 0a20 2020 2069 6e73 7461 6e63 6554 7970  .    instanceTyp
+0000a5b0: 6573 203d 205b 2274 3361 2e6d 6963 726f  es = ["t3a.micro
+0000a5c0: 222c 2022 7433 2e6d 6963 726f 225d 0a20  ", "t3.micro"]. 
+0000a5d0: 2020 206d 6178 576f 726b 6572 7320 3d20     maxWorkers = 
+0000a5e0: 310a 2020 2020 6d61 7869 6d75 6d54 6173  1.    maximumTas
+0000a5f0: 6b52 6574 7269 6573 203d 2030 0a20 2020  kRetries = 0.   
+0000a600: 206d 696e 576f 726b 6572 7320 3d20 310a   minWorkers = 1.
+0000a610: 2020 2020 6e61 6d65 203d 2022 6d79 2d77      name = "my-w
+0000a620: 6f72 6b2d 7265 7175 6972 656d 656e 7422  ork-requirement"
+0000a630: 0a20 2020 206f 7574 7075 7473 203d 205b  .    outputs = [
+0000a640: 2272 6573 756c 7473 2e74 7874 225d 0a20  "results.txt"]. 
+0000a650: 2020 206f 7574 7075 7473 5265 7175 6972     outputsRequir
+0000a660: 6564 203d 205b 2272 6573 756c 7473 5f72  ed = ["results_r
+0000a670: 6571 7569 7265 642e 7478 7422 5d0a 2020  equired.txt"].  
+0000a680: 2020 7072 696f 7269 7479 203d 2030 2e30    priority = 0.0
+0000a690: 0a20 2020 2070 726f 7669 6465 7273 203d  .    providers =
+0000a6a0: 205b 2241 5753 225d 0a20 2020 2072 616d   ["AWS"].    ram
+0000a6b0: 203d 205b 302e 352c 2032 2e30 5d0a 2020   = [0.5, 2.0].  
+0000a6c0: 2020 7265 6769 6f6e 7320 3d20 5b22 6575    regions = ["eu
+0000a6d0: 2d77 6573 742d 3222 5d0a 2020 2020 7461  -west-2"].    ta
+0000a6e0: 736b 4261 7463 6853 697a 6520 3d20 3130  skBatchSize = 10
+0000a6f0: 3030 0a20 2020 2074 6173 6b43 6f75 6e74  00.    taskCount
+0000a700: 203d 2031 3030 0a20 2020 2074 6173 6b44   = 100.    taskD
+0000a710: 6174 6120 3d20 226d 795f 6461 7461 5f73  ata = "my_data_s
+0000a720: 7472 696e 6722 0a20 2020 2074 6173 6b44  tring".    taskD
+0000a730: 6174 6146 696c 6520 3d20 226d 795f 6461  ataFile = "my_da
+0000a740: 7461 5f66 696c 652e 7478 7422 0a20 2020  ta_file.txt".   
+0000a750: 2074 6173 6b4e 616d 6520 3d20 226d 795f   taskName = "my_
+0000a760: 7461 736b 5f6e 756d 6265 725f 7b7b 7461  task_number_{{ta
+0000a770: 736b 5f6e 756d 6265 727d 7d22 0a20 2020  sk_number}}".   
+0000a780: 2074 6173 6b47 726f 7570 4e61 6d65 203d   taskGroupName =
+0000a790: 2022 6d79 5f74 6173 6b5f 6772 6f75 705f   "my_task_group_
+0000a7a0: 6e75 6d62 6572 5f7b 7b74 6173 6b5f 6772  number_{{task_gr
+0000a7b0: 6f75 705f 6e75 6d62 6572 7d7d 220a 2020  oup_number}}".  
+0000a7c0: 2020 7461 736b 5479 7065 203d 2022 646f    taskType = "do
+0000a7d0: 636b 6572 220a 2020 2020 7461 736b 7350  cker".    tasksP
+0000a7e0: 6572 576f 726b 6572 203d 2031 0a20 2020  erWorker = 1.   
+0000a7f0: 2075 706c 6f61 6446 696c 6573 203d 205b   uploadFiles = [
+0000a800: 7b6c 6f63 616c 5061 7468 203d 2022 6669  {localPath = "fi
+0000a810: 6c65 5f31 2e74 7874 222c 2075 706c 6f61  le_1.txt", uploa
+0000a820: 6450 6174 6820 3d20 2266 696c 655f 312e  dPath = "file_1.
+0000a830: 7478 7422 7d5d 0a20 2020 2076 6370 7573  txt"}].    vcpus
+0000a840: 203d 205b 312c 2034 5d0a 2020 2020 7665   = [1, 4].    ve
+0000a850: 7269 6679 4174 5374 6172 7420 3d20 5b22  rifyAtStart = ["
+0000a860: 7265 6164 795f 7265 7375 6c74 732e 7478  ready_results.tx
+0000a870: 7422 5d0a 2020 2020 7665 7269 6679 5761  t"].    verifyWa
+0000a880: 6974 203d 205b 2277 6169 745f 666f 725f  it = ["wait_for_
+0000a890: 7265 7375 6c74 732e 7478 7422 5d0a 2020  results.txt"].  
+0000a8a0: 2020 776f 726b 6572 5461 6773 203d 205b    workerTags = [
+0000a8b0: 2274 6167 2d7b 7b75 7365 726e 616d 657d  "tag-{{username}
+0000a8c0: 7d22 5d0a 2020 2020 776f 726b 5265 7175  }"].    workRequ
+0000a8d0: 6972 656d 656e 7444 6174 6120 3d20 2277  irementData = "w
+0000a8e0: 6f72 6b5f 7265 7175 6972 656d 656e 742e  ork_requirement.
+0000a8f0: 6a73 6f6e 220a 6060 600a 0a23 2323 204a  json".```..### J
+0000a900: 534f 4e20 5072 6f70 6572 7469 6573 2061  SON Properties a
+0000a910: 7420 7468 6520 576f 726b 2052 6571 7569  t the Work Requi
+0000a920: 7265 6d65 6e74 204c 6576 656c 0a0a 5368  rement Level..Sh
+0000a930: 6f77 696e 6720 616c 6c20 706f 7373 6962  owing all possib
+0000a940: 6c65 2070 726f 7065 7274 6965 7320 6174  le properties at
+0000a950: 2074 6865 2057 6f72 6b20 5265 7175 6972   the Work Requir
+0000a960: 656d 656e 7420 6c65 7665 6c3a 0a0a 6060  ement level:..``
+0000a970: 606a 736f 6e0a 7b0a 2020 2261 7267 756d  `json.{.  "argum
+0000a980: 656e 7473 223a 205b 312c 2022 5457 4f22  ents": [1, "TWO"
+0000a990: 5d2c 0a20 2022 6361 7074 7572 6554 6173  ],.  "captureTas
+0000a9a0: 6b4f 7574 7075 7422 3a20 7472 7565 2c0a  kOutput": true,.
+0000a9b0: 2020 2263 6f6d 706c 6574 6564 5461 736b    "completedTask
+0000a9c0: 5474 6c22 3a20 3130 2c0a 2020 2264 6f63  Ttl": 10,.  "doc
+0000a9d0: 6b65 7245 6e76 6972 6f6e 6d65 6e74 223a  kerEnvironment":
+0000a9e0: 207b 224d 595f 444f 434b 4552 5f56 4152   {"MY_DOCKER_VAR
+0000a9f0: 223a 2031 3030 7d2c 0a20 2022 646f 636b  ": 100},.  "dock
+0000aa00: 6572 5061 7373 776f 7264 223a 2022 6d79  erPassword": "my
+0000aa10: 5061 7373 776f 7264 222c 0a20 2022 646f  Password",.  "do
+0000aa20: 636b 6572 5573 6572 6e61 6d65 223a 2022  ckerUsername": "
+0000aa30: 6d79 5573 6572 6e61 6d65 222c 0a20 2022  myUsername",.  "
+0000aa40: 656e 7669 726f 6e6d 656e 7422 3a20 7b22  environment": {"
+0000aa50: 4d59 5f56 4152 223a 2031 3030 7d2c 0a20  MY_VAR": 100},. 
+0000aa60: 2022 6578 636c 7573 6976 6557 6f72 6b65   "exclusiveWorke
+0000aa70: 7273 223a 2066 616c 7365 2c0a 2020 2265  rs": false,.  "e
+0000aa80: 7865 6375 7461 626c 6522 3a20 226d 792d  xecutable": "my-
+0000aa90: 636f 6e74 6169 6e65 7222 2c0a 2020 2266  container",.  "f
+0000aaa0: 696e 6973 6849 6641 6c6c 5461 736b 7346  inishIfAllTasksF
+0000aab0: 696e 6973 6865 6422 3a20 7472 7565 2c0a  inished": true,.
+0000aac0: 2020 2266 696e 6973 6849 6641 6e79 5461    "finishIfAnyTa
+0000aad0: 736b 4661 696c 6564 223a 2066 616c 7365  skFailed": false
+0000aae0: 2c0a 2020 2266 6c61 7474 656e 496e 7075  ,.  "flattenInpu
+0000aaf0: 7450 6174 6873 223a 2066 616c 7365 2c0a  tPaths": false,.
+0000ab00: 2020 2266 6c61 7474 656e 5570 6c6f 6164    "flattenUpload
+0000ab10: 5061 7468 7322 3a20 6661 6c73 652c 0a20  Paths": false,. 
+0000ab20: 2022 6675 6c66 696c 4f6e 5375 626d 6974   "fulfilOnSubmit
+0000ab30: 223a 2066 616c 7365 2c0a 2020 2269 6e70  ": false,.  "inp
+0000ab40: 7574 7322 3a20 5b22 6170 702f 6d61 696e  uts": ["app/main
+0000ab50: 2e70 7922 2c20 2261 7070 2f72 6571 7569  .py", "app/requi
+0000ab60: 7265 6d65 6e74 732e 7478 7422 5d2c 0a20  rements.txt"],. 
+0000ab70: 2022 696e 7075 7473 4f70 7469 6f6e 616c   "inputsOptional
+0000ab80: 223a 205b 226f 7074 696f 6e61 6c2e 7478  ": ["optional.tx
+0000ab90: 7422 5d2c 0a20 2022 696e 7374 616e 6365  t"],.  "instance
+0000aba0: 5479 7065 7322 3a20 5b22 7433 612e 6d69  Types": ["t3a.mi
+0000abb0: 6372 6f22 2c20 2274 332e 6d69 6372 6f22  cro", "t3.micro"
+0000abc0: 5d2c 0a20 2022 6d61 7857 6f72 6b65 7273  ],.  "maxWorkers
+0000abd0: 223a 2031 2c0a 2020 226d 6178 696d 756d  ": 1,.  "maximum
+0000abe0: 5461 736b 5265 7472 6965 7322 3a20 302c  TaskRetries": 0,
+0000abf0: 0a20 2022 6d69 6e57 6f72 6b65 7273 223a  .  "minWorkers":
+0000ac00: 2031 2c0a 2020 226e 616d 6522 3a20 226d   1,.  "name": "m
+0000ac10: 792d 776f 726b 2d72 6571 7569 7265 6d65  y-work-requireme
+0000ac20: 6e74 222c 0a20 2022 6f75 7470 7574 7322  nt",.  "outputs"
+0000ac30: 3a20 5b22 7265 7375 6c74 732e 7478 7422  : ["results.txt"
+0000ac40: 5d2c 0a20 2022 6f75 7470 7574 7352 6571  ],.  "outputsReq
+0000ac50: 7569 7265 6422 3a20 5b22 7265 7375 6c74  uired": ["result
+0000ac60: 735f 7265 7175 6972 6564 2e74 7874 225d  s_required.txt"]
+0000ac70: 2c0a 2020 2270 7269 6f72 6974 7922 3a20  ,.  "priority": 
+0000ac80: 302e 302c 0a20 2022 7072 6f76 6964 6572  0.0,.  "provider
+0000ac90: 7322 3a20 5b22 4157 5322 5d2c 0a20 2022  s": ["AWS"],.  "
+0000aca0: 7261 6d22 3a20 5b30 2e35 2c20 325d 2c0a  ram": [0.5, 2],.
+0000acb0: 2020 2272 6567 696f 6e73 223a 205b 2265    "regions": ["e
+0000acc0: 752d 7765 7374 2d32 225d 2c0a 2020 2274  u-west-2"],.  "t
+0000acd0: 6173 6b44 6174 6122 3a20 226d 795f 7461  askData": "my_ta
+0000ace0: 736b 5f64 6174 615f 7374 7269 6e67 222c  sk_data_string",
+0000acf0: 0a20 2022 7461 736b 4461 7461 4669 6c65  .  "taskDataFile
+0000ad00: 223a 2022 6d79 5f64 6174 615f 6669 6c65  ": "my_data_file
+0000ad10: 2e74 7874 222c 0a20 2022 7461 736b 5479  .txt",.  "taskTy
+0000ad20: 7065 7322 3a20 5b22 646f 636b 6572 225d  pes": ["docker"]
+0000ad30: 2c0a 2020 2274 6173 6b73 5065 7257 6f72  ,.  "tasksPerWor
+0000ad40: 6b65 7222 3a20 312c 0a20 2022 7570 6c6f  ker": 1,.  "uplo
+0000ad50: 6164 4669 6c65 7322 3a20 5b7b 226c 6f63  adFiles": [{"loc
+0000ad60: 616c 5061 7468 223a 2022 6669 6c65 5f31  alPath": "file_1
+0000ad70: 2e74 7874 222c 2022 7570 6c6f 6164 5061  .txt", "uploadPa
+0000ad80: 7468 223a 2022 6669 6c65 5f31 2e74 7874  th": "file_1.txt
+0000ad90: 227d 5d2c 0a20 2022 7663 7075 7322 3a20  "}],.  "vcpus": 
+0000ada0: 5b31 2c20 345d 2c0a 2020 2276 6572 6966  [1, 4],.  "verif
+0000adb0: 7941 7453 7461 7274 223a 205b 2272 6561  yAtStart": ["rea
+0000adc0: 6479 5f72 6573 756c 7473 2e74 7874 225d  dy_results.txt"]
+0000add0: 2c0a 2020 2276 6572 6966 7957 6169 7422  ,.  "verifyWait"
+0000ade0: 3a20 5b22 7761 6974 5f66 6f72 5f72 6573  : ["wait_for_res
+0000adf0: 756c 7473 2e74 7874 225d 2c0a 2020 2277  ults.txt"],.  "w
+0000ae00: 6f72 6b65 7254 6167 7322 3a20 5b5d 2c0a  orkerTags": [],.
+0000ae10: 2020 2274 6173 6b47 726f 7570 7322 3a20    "taskGroups": 
+0000ae20: 5b0a 2020 2020 7b0a 2020 2020 2020 2274  [.    {.      "t
+0000ae30: 6173 6b73 223a 205b 0a20 2020 2020 2020  asks": [.       
+0000ae40: 207b 7d0a 2020 2020 2020 5d0a 2020 2020   {}.      ].    
+0000ae50: 7d0a 2020 5d0a 7d0a 0a60 6060 0a0a 2323  }.  ].}..```..##
+0000ae60: 2320 4a53 4f4e 2050 726f 7065 7274 6965  # JSON Propertie
+0000ae70: 7320 6174 2074 6865 2054 6173 6b20 4772  s at the Task Gr
+0000ae80: 6f75 7020 4c65 7665 6c0a 0a53 686f 7769  oup Level..Showi
+0000ae90: 6e67 2061 6c6c 2070 6f73 7369 626c 6520  ng all possible 
+0000aea0: 7072 6f70 6572 7469 6573 2061 7420 7468  properties at th
+0000aeb0: 6520 5461 736b 2047 726f 7570 206c 6576  e Task Group lev
+0000aec0: 656c 3a0a 0a60 6060 6a73 6f6e 0a7b 0a20  el:..```json.{. 
+0000aed0: 2022 7461 736b 4772 6f75 7073 223a 205b   "taskGroups": [
+0000aee0: 0a20 2020 207b 0a20 2020 2020 2022 6172  .    {.      "ar
+0000aef0: 6775 6d65 6e74 7322 3a20 5b31 2c20 2254  guments": [1, "T
+0000af00: 574f 225d 2c0a 2020 2020 2020 2263 6170  WO"],.      "cap
+0000af10: 7475 7265 5461 736b 4f75 7470 7574 223a  tureTaskOutput":
+0000af20: 2074 7275 652c 0a20 2020 2020 2022 636f   true,.      "co
+0000af30: 6d70 6c65 7465 6454 6173 6b54 746c 223a  mpletedTaskTtl":
+0000af40: 2031 302c 0a20 2020 2020 2022 646f 636b   10,.      "dock
+0000af50: 6572 456e 7669 726f 6e6d 656e 7422 3a20  erEnvironment": 
+0000af60: 7b22 4d59 5f44 4f43 4b45 525f 5641 5222  {"MY_DOCKER_VAR"
+0000af70: 3a20 3130 307d 2c0a 2020 2020 2020 2264  : 100},.      "d
+0000af80: 6f63 6b65 7250 6173 7377 6f72 6422 3a20  ockerPassword": 
+0000af90: 226d 7950 6173 7377 6f72 6422 2c0a 2020  "myPassword",.  
+0000afa0: 2020 2020 2264 6f63 6b65 7255 7365 726e      "dockerUsern
+0000afb0: 616d 6522 3a20 226d 7955 7365 726e 616d  ame": "myUsernam
+0000afc0: 6522 2c0a 2020 2020 2020 2265 6e76 6972  e",.      "envir
+0000afd0: 6f6e 6d65 6e74 223a 207b 224d 595f 5641  onment": {"MY_VA
+0000afe0: 5222 3a20 3130 307d 2c0a 2020 2020 2020  R": 100},.      
+0000aff0: 2265 7863 6c75 7369 7665 576f 726b 6572  "exclusiveWorker
+0000b000: 7322 3a20 6661 6c73 652c 0a20 2020 2020  s": false,.     
+0000b010: 2022 6578 6563 7574 6162 6c65 223a 2022   "executable": "
+0000b020: 6d79 2d63 6f6e 7461 696e 6572 222c 0a20  my-container",. 
+0000b030: 2020 2020 2022 6669 6e69 7368 4966 416c       "finishIfAl
+0000b040: 6c54 6173 6b73 4669 6e69 7368 6564 223a  lTasksFinished":
+0000b050: 2074 7275 652c 0a20 2020 2020 2022 6669   true,.      "fi
+0000b060: 6e69 7368 4966 416e 7954 6173 6b46 6169  nishIfAnyTaskFai
+0000b070: 6c65 6422 3a20 6661 6c73 652c 0a20 2020  led": false,.   
+0000b080: 2020 2022 666c 6174 7465 6e49 6e70 7574     "flattenInput
+0000b090: 5061 7468 7322 3a20 6661 6c73 652c 0a20  Paths": false,. 
+0000b0a0: 2020 2020 2022 696e 7075 7473 223a 205b       "inputs": [
+0000b0b0: 2261 7070 2f6d 6169 6e2e 7079 222c 2022  "app/main.py", "
+0000b0c0: 6170 702f 7265 7175 6972 656d 656e 7473  app/requirements
+0000b0d0: 2e74 7874 225d 2c0a 2020 2020 2020 2269  .txt"],.      "i
+0000b0e0: 6e70 7574 734f 7074 696f 6e61 6c22 3a20  nputsOptional": 
+0000b0f0: 5b22 6f70 7469 6f6e 616c 2e74 7874 225d  ["optional.txt"]
+0000b100: 2c0a 2020 2020 2020 2269 6e73 7461 6e63  ,.      "instanc
+0000b110: 6554 7970 6573 223a 205b 2274 3361 2e6d  eTypes": ["t3a.m
+0000b120: 6963 726f 222c 2022 7433 2e6d 6963 726f  icro", "t3.micro
+0000b130: 225d 2c0a 2020 2020 2020 226d 6178 696d  "],.      "maxim
+0000b140: 756d 5461 736b 5265 7472 6965 7322 3a20  umTaskRetries": 
+0000b150: 302c 0a20 2020 2020 2022 6d61 7857 6f72  0,.      "maxWor
+0000b160: 6b65 7273 223a 2031 2c0a 2020 2020 2020  kers": 1,.      
+0000b170: 226d 696e 576f 726b 6572 7322 3a20 312c  "minWorkers": 1,
+0000b180: 0a20 2020 2020 2022 6e61 6d65 223a 2022  .      "name": "
+0000b190: 6669 7273 742d 7461 736b 2d67 726f 7570  first-task-group
+0000b1a0: 222c 0a20 2020 2020 2022 6f75 7470 7574  ",.      "output
+0000b1b0: 7322 3a20 5b22 7265 7375 6c74 732e 7478  s": ["results.tx
+0000b1c0: 7422 5d2c 0a20 2020 2020 2022 6f75 7470  t"],.      "outp
+0000b1d0: 7574 7352 6571 7569 7265 6422 3a20 5b22  utsRequired": ["
+0000b1e0: 7265 7375 6c74 735f 7265 7175 6972 6564  results_required
+0000b1f0: 2e74 7874 225d 2c0a 2020 2020 2020 2270  .txt"],.      "p
+0000b200: 7269 6f72 6974 7922 3a20 302e 302c 0a20  riority": 0.0,. 
+0000b210: 2020 2020 2022 7072 6f76 6964 6572 7322       "providers"
+0000b220: 3a20 5b22 4157 5322 5d2c 0a20 2020 2020  : ["AWS"],.     
+0000b230: 2022 7261 6d22 3a20 5b30 2e35 2c20 325d   "ram": [0.5, 2]
+0000b240: 2c0a 2020 2020 2020 2272 6567 696f 6e73  ,.      "regions
+0000b250: 223a 205b 2265 752d 7765 7374 2d32 225d  ": ["eu-west-2"]
+0000b260: 2c0a 2020 2020 2020 2274 6173 6b43 6f75  ,.      "taskCou
+0000b270: 6e74 223a 2035 2c0a 2020 2020 2020 2274  nt": 5,.      "t
+0000b280: 6173 6b44 6174 6122 3a20 226d 795f 7461  askData": "my_ta
+0000b290: 736b 5f64 6174 615f 7374 7269 6e67 222c  sk_data_string",
+0000b2a0: 0a20 2020 2020 2022 7461 736b 4461 7461  .      "taskData
+0000b2b0: 4669 6c65 223a 2022 6d79 5f64 6174 615f  File": "my_data_
+0000b2c0: 6669 6c65 2e74 7874 222c 0a20 2020 2020  file.txt",.     
+0000b2d0: 2022 7461 736b 5479 7065 7322 3a20 5b22   "taskTypes": ["
+0000b2e0: 646f 636b 6572 225d 2c0a 2020 2020 2020  docker"],.      
+0000b2f0: 2274 6173 6b73 5065 7257 6f72 6b65 7222  "tasksPerWorker"
+0000b300: 3a20 312c 0a20 2020 2020 2022 7570 6c6f  : 1,.      "uplo
+0000b310: 6164 4669 6c65 7322 3a20 5b7b 226c 6f63  adFiles": [{"loc
+0000b320: 616c 5061 7468 223a 2022 6669 6c65 5f31  alPath": "file_1
+0000b330: 2e74 7874 222c 2022 7570 6c6f 6164 5061  .txt", "uploadPa
+0000b340: 7468 223a 2022 6669 6c65 5f31 2e74 7874  th": "file_1.txt
+0000b350: 227d 5d2c 0a20 2020 2020 2022 7663 7075  "}],.      "vcpu
+0000b360: 7322 3a20 5b31 2c20 345d 2c0a 2020 2020  s": [1, 4],.    
+0000b370: 2020 2276 6572 6966 7941 7453 7461 7274    "verifyAtStart
+0000b380: 223a 205b 2272 6561 6479 5f72 6573 756c  ": ["ready_resul
+0000b390: 7473 2e74 7874 225d 2c0a 2020 2020 2020  ts.txt"],.      
+0000b3a0: 2276 6572 6966 7957 6169 7422 3a20 5b22  "verifyWait": ["
+0000b3b0: 7761 6974 5f66 6f72 5f72 6573 756c 7473  wait_for_results
+0000b3c0: 2e74 7874 225d 2c0a 2020 2020 2020 2277  .txt"],.      "w
+0000b3d0: 6f72 6b65 7254 6167 7322 3a20 5b5d 2c0a  orkerTags": [],.
+0000b3e0: 2020 2020 2020 2274 6173 6b73 223a 205b        "tasks": [
+0000b3f0: 0a20 2020 2020 2020 207b 7d0a 2020 2020  .        {}.    
+0000b400: 2020 5d0a 2020 2020 7d2c 0a20 2020 207b    ].    },.    {
+0000b410: 0a20 2020 2020 2022 6e61 6d65 223a 2022  .      "name": "
+0000b420: 7365 636f 6e64 2d74 6173 6b2d 6772 6f75  second-task-grou
+0000b430: 7022 2c0a 2020 2020 2020 2264 6570 656e  p",.      "depen
+0000b440: 6465 6e74 4f6e 223a 2022 6669 7273 742d  dentOn": "first-
+0000b450: 7461 736b 2d67 726f 7570 222c 0a20 2020  task-group",.   
+0000b460: 2020 2022 7461 736b 7322 3a20 5b0a 2020     "tasks": [.  
+0000b470: 2020 2020 2020 7b7d 0a20 2020 2020 205d        {}.      ]
+0000b480: 0a20 2020 207d 0a20 205d 0a7d 0a60 6060  .    }.  ].}.```
+0000b490: 0a0a 2323 2320 4a53 4f4e 2050 726f 7065  ..### JSON Prope
+0000b4a0: 7274 6965 7320 6174 2074 6865 2054 6173  rties at the Tas
+0000b4b0: 6b20 4c65 7665 6c0a 0a53 686f 7769 6e67  k Level..Showing
+0000b4c0: 2061 6c6c 2070 6f73 7369 626c 6520 7072   all possible pr
+0000b4d0: 6f70 6572 7469 6573 2061 7420 7468 6520  operties at the 
+0000b4e0: 5461 736b 206c 6576 656c 3a0a 0a60 6060  Task level:..```
+0000b4f0: 6a73 6f6e 0a7b 0a20 2022 7461 736b 4772  json.{.  "taskGr
+0000b500: 6f75 7073 223a 205b 0a20 2020 207b 0a20  oups": [.    {. 
+0000b510: 2020 2020 2022 7461 736b 7322 3a20 5b0a       "tasks": [.
+0000b520: 2020 2020 2020 2020 7b0a 2020 2020 2020          {.      
+0000b530: 2020 2020 2261 7267 756d 656e 7473 223a      "arguments":
+0000b540: 205b 312c 2032 5d2c 0a20 2020 2020 2020   [1, 2],.       
+0000b550: 2020 2022 6361 7074 7572 6554 6173 6b4f     "captureTaskO
+0000b560: 7574 7075 7422 3a20 7472 7565 2c0a 2020  utput": true,.  
+0000b570: 2020 2020 2020 2020 2264 6f63 6b65 7245          "dockerE
+0000b580: 6e76 6972 6f6e 6d65 6e74 223a 207b 224d  nvironment": {"M
+0000b590: 595f 444f 434b 4552 5f56 4152 223a 2031  Y_DOCKER_VAR": 1
+0000b5a0: 3030 7d2c 0a20 2020 2020 2020 2020 2022  00},.          "
+0000b5b0: 646f 636b 6572 5061 7373 776f 7264 223a  dockerPassword":
+0000b5c0: 2022 6d79 5061 7373 776f 7264 222c 0a20   "myPassword",. 
+0000b5d0: 2020 2020 2020 2020 2022 646f 636b 6572           "docker
+0000b5e0: 5573 6572 6e61 6d65 223a 2022 6d79 5573  Username": "myUs
+0000b5f0: 6572 6e61 6d65 222c 0a20 2020 2020 2020  ername",.       
+0000b600: 2020 2022 656e 7669 726f 6e6d 656e 7422     "environment"
+0000b610: 3a20 7b22 4d59 5f56 4152 223a 2031 3030  : {"MY_VAR": 100
+0000b620: 7d2c 0a20 2020 2020 2020 2020 2022 6578  },.          "ex
+0000b630: 6563 7574 6162 6c65 223a 2022 6d79 2d63  ecutable": "my-c
+0000b640: 6f6e 7461 696e 6572 222c 0a20 2020 2020  ontainer",.     
+0000b650: 2020 2020 2022 666c 6174 7465 6e49 6e70       "flattenInp
+0000b660: 7574 5061 7468 7322 3a20 6661 6c73 652c  utPaths": false,
+0000b670: 0a20 2020 2020 2020 2020 2022 696e 7075  .          "inpu
+0000b680: 7473 223a 205b 2261 7070 2f6d 6169 6e2e  ts": ["app/main.
+0000b690: 7079 222c 2022 6170 702f 7265 7175 6972  py", "app/requir
+0000b6a0: 656d 656e 7473 2e74 7874 225d 2c0a 2020  ements.txt"],.  
+0000b6b0: 2020 2020 2020 2020 2269 6e70 7574 734f          "inputsO
+0000b6c0: 7074 696f 6e61 6c22 3a20 5b22 6f70 7469  ptional": ["opti
+0000b6d0: 6f6e 616c 2e74 7874 225d 2c0a 2020 2020  onal.txt"],.    
+0000b6e0: 2020 2020 2020 226e 616d 6522 3a20 226d        "name": "m
+0000b6f0: 792d 7461 736b 222c 0a20 2020 2020 2020  y-task",.       
+0000b700: 2020 2022 6f75 7470 7574 7322 3a20 5b22     "outputs": ["
+0000b710: 7265 7375 6c74 732e 7478 7422 5d2c 0a20  results.txt"],. 
+0000b720: 2020 2020 2020 2020 2022 6f75 7470 7574           "output
+0000b730: 7352 6571 7569 7265 6422 3a20 5b22 7265  sRequired": ["re
+0000b740: 7375 6c74 735f 7265 7175 6972 6564 2e74  sults_required.t
+0000b750: 7874 225d 2c0a 2020 2020 2020 2020 2020  xt"],.          
+0000b760: 2274 6173 6b44 6174 6122 3a20 226d 795f  "taskData": "my_
+0000b770: 7461 736b 5f64 6174 615f 7374 7269 6e67  task_data_string
+0000b780: 222c 0a20 2020 2020 2020 2020 2022 7461  ",.          "ta
+0000b790: 736b 4461 7461 4669 6c65 223a 2022 6d79  skDataFile": "my
+0000b7a0: 5f64 6174 615f 6669 6c65 2e74 7874 222c  _data_file.txt",
+0000b7b0: 0a20 2020 2020 2020 2020 2022 7461 736b  .          "task
+0000b7c0: 5479 7065 223a 2022 646f 636b 6572 222c  Type": "docker",
+0000b7d0: 0a20 2020 2020 2020 2020 2022 7570 6c6f  .          "uplo
+0000b7e0: 6164 4669 6c65 7322 3a20 5b7b 226c 6f63  adFiles": [{"loc
+0000b7f0: 616c 5061 7468 223a 2022 6669 6c65 5f31  alPath": "file_1
+0000b800: 2e74 7874 222c 2022 7570 6c6f 6164 5061  .txt", "uploadPa
+0000b810: 7468 223a 2022 6669 6c65 5f31 2e74 7874  th": "file_1.txt
+0000b820: 227d 5d2c 0a20 2020 2020 2020 2020 2022  "}],.          "
+0000b830: 7665 7269 6679 4174 5374 6172 7422 3a20  verifyAtStart": 
+0000b840: 5b22 7265 6164 795f 7265 7375 6c74 732e  ["ready_results.
+0000b850: 7478 7422 5d2c 0a20 2020 2020 2020 2020  txt"],.         
+0000b860: 2022 7665 7269 6679 5761 6974 223a 205b   "verifyWait": [
+0000b870: 2277 6169 745f 666f 725f 7265 7375 6c74  "wait_for_result
+0000b880: 732e 7478 7422 5d0a 2020 2020 2020 2020  s.txt"].        
+0000b890: 7d0a 2020 2020 2020 5d0a 2020 2020 7d0a  }.      ].    }.
+0000b8a0: 2020 5d0a 7d0a 6060 600a 0a23 2320 5661    ].}.```..## Va
+0000b8b0: 7269 6162 6c65 2053 7562 7374 6974 7574  riable Substitut
+0000b8c0: 696f 6e73 2069 6e20 576f 726b 2052 6571  ions in Work Req
+0000b8d0: 7569 7265 6d65 6e74 2050 726f 7065 7274  uirement Propert
+0000b8e0: 6965 730a 0a56 6172 6961 626c 6520 7375  ies..Variable su
+0000b8f0: 6273 7469 7475 7469 6f6e 7320 6361 6e20  bstitutions can 
+0000b900: 6265 2075 7365 6420 7769 7468 696e 2061  be used within a
+0000b910: 6e79 2070 726f 7065 7274 7920 7661 6c75  ny property valu
+0000b920: 6520 696e 2054 4f4d 4c20 636f 6e66 6967  e in TOML config
+0000b930: 7572 6174 696f 6e20 6669 6c65 7320 6f72  uration files or
+0000b940: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+0000b950: 7420 4a53 4f4e 2066 696c 6573 2e20 5365  t JSON files. Se
+0000b960: 6520 7468 6520 6465 7363 7269 7074 696f  e the descriptio
+0000b970: 6e20 5b61 626f 7665 5d28 2376 6172 6961  n [above](#varia
+0000b980: 626c 652d 7375 6273 7469 7475 7469 6f6e  ble-substitution
+0000b990: 7329 2066 6f72 206d 6f72 6520 6465 7461  s) for more deta
+0000b9a0: 696c 7320 6f6e 2076 6172 6961 626c 6520  ils on variable 
+0000b9b0: 7375 6273 7469 7475 7469 6f6e 732e 2054  substitutions. T
+0000b9c0: 6869 7320 6973 2061 2070 6f77 6572 6675  his is a powerfu
+0000b9d0: 6c20 6665 6174 7572 6520 7468 6174 2061  l feature that a
+0000b9e0: 6c6c 6f77 7320 576f 726b 2052 6571 7569  llows Work Requi
+0000b9f0: 7265 6d65 6e74 7320 746f 2062 6520 7061  rements to be pa
+0000ba00: 7261 6d65 7465 7269 7365 6420 6279 2073  rameterised by s
+0000ba10: 7570 706c 7969 6e67 2076 616c 7565 7320  upplying values 
+0000ba20: 6f6e 2074 6865 2063 6f6d 6d61 6e64 206c  on the command l
+0000ba30: 696e 652c 2076 6961 2065 6e76 6972 6f6e  ine, via environ
+0000ba40: 6d65 6e74 2076 6172 6961 626c 6573 206f  ment variables o
+0000ba50: 7220 7669 6120 7468 6520 544f 4d4c 2066  r via the TOML f
+0000ba60: 696c 652e 0a0a 2323 2320 5461 736b 2061  ile...### Task a
+0000ba70: 6e64 2054 6173 6b20 4772 6f75 7020 4e61  nd Task Group Na
+0000ba80: 6d65 2053 7562 7374 6974 7574 696f 6e0a  me Substitution.
+0000ba90: 0a54 6865 2066 6f6c 6c6f 7769 6e67 206e  .The following n
+0000baa0: 756d 6265 7269 6e67 2061 6e64 206e 616d  umbering and nam
+0000bab0: 696e 6720 7375 6273 7469 7475 7469 6f6e  ing substitution
+0000bac0: 7320 6172 6520 6176 6169 6c61 626c 6520  s are available 
+0000bad0: 666f 7220 7573 6520 696e 2054 6173 6b20  for use in Task 
+0000bae0: 616e 6420 5461 736b 2047 726f 7570 206e  and Task Group n
+0000baf0: 616d 696e 672c 206f 6e6c 7920 7768 656e  aming, only when
+0000bb00: 2074 6865 2057 6f72 6b20 5265 7175 6972   the Work Requir
+0000bb10: 656d 656e 7420 6973 2073 7065 6369 6669  ement is specifi
+0000bb20: 6564 2061 7320 204a 534f 4e20 646f 6375  ed as  JSON docu
+0000bb30: 6d65 6e74 2c20 692e 652e 2c20 7468 6579  ment, i.e., they
+0000bb40: 2063 616e 2062 6520 7573 6564 2069 6e20   can be used in 
+0000bb50: 7468 6520 606e 616d 6560 2070 726f 7065  the `name` prope
+0000bb60: 7274 6965 7320 666f 7220 5461 736b 7320  rties for Tasks 
+0000bb70: 616e 6420 5461 736b 2047 726f 7570 7320  and Task Groups 
+0000bb80: 696e 204a 534f 4e20 7370 6563 6966 6963  in JSON specific
+0000bb90: 6174 696f 6e73 2e0a 0a54 6865 2066 6f6c  ations...The fol
+0000bba0: 6c6f 7769 6e67 2074 6162 6c65 2064 6566  lowing table def
+0000bbb0: 696e 6573 2074 6865 2063 6f6e 7465 7874  ines the context
+0000bbc0: 2873 2920 696e 2077 6869 6368 2065 6163  (s) in which eac
+0000bbd0: 6820 7661 7269 6162 6c65 2063 616e 2062  h variable can b
+0000bbe0: 6520 7573 6564 3a0a 0a7c 2044 6972 6563  e used:..| Direc
+0000bbf0: 7469 7665 2020 2020 2020 2020 2020 2020  tive            
+0000bc00: 2020 207c 2044 6573 6372 6970 7469 6f6e     | Description
+0000bc10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+0000bc20: 2020 2020 2020 2020 2020 2020 2020 2020                  
+0000bc30: 2020 2020 2020 207c 2054 6173 6b20 7c20         | Task | 
+0000bc40: 5461 736b 2047 726f 7570 207c 0a7c 3a2d  Task Group |.|:-
+0000bc50: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+0000bc60: 2d2d 2d2d 2d2d 2d7c 3a2d 2d2d 2d2d 2d2d  -------|:-------
+0000bc70: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+0000bc80: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+0000bc90: 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c 3a2d 2d2d  -----------|:---
+0000bca0: 2d2d 7c3a 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c  --|:-----------|
+0000bcb0: 0a7c 2060 7b7b 7461 736b 5f6e 756d 6265  .| `{{task_numbe
+0000bcc0: 727d 7d60 2020 2020 2020 207c 2054 6865  r}}`       | The
+0000bcd0: 2063 7572 7265 6e74 2054 6173 6b20 6e75   current Task nu
+0000bce0: 6d62 6572 2020 2020 2020 2020 2020 2020  mber            
+0000bcf0: 2020 2020 2020 2020 2020 2020 2020 207c                 |
+0000bd00: 2059 6573 2020 7c20 2020 2020 2020 2020   Yes  |         
+0000bd10: 2020 207c 0a7c 2060 7b7b 7461 736b 5f6e     |.| `{{task_n
+0000bd20: 616d 657d 7d60 2020 2020 2020 2020 207c  ame}}`         |
+0000bd30: 2054 6865 2063 7572 7265 6e74 2054 6173   The current Tas
+0000bd40: 6b20 6e61 6d65 2020 2020 2020 2020 2020  k name          
+0000bd50: 2020 2020 2020 2020 2020 2020 2020 2020                  
+0000bd60: 2020 207c 2059 6573 2020 7c20 2020 2020     | Yes  |     
+0000bd70: 2020 2020 2020 207c 0a7c 2060 7b7b 7461         |.| `{{ta
+0000bd80: 736b 5f67 726f 7570 5f6e 616d 657d 7d60  sk_group_name}}`
+0000bd90: 2020 207c 2054 6865 2063 7572 7265 6e74     | The current
+0000bda0: 2054 6173 6b20 4772 6f75 7020 6e61 6d65   Task Group name
+0000bdb0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+0000bdc0: 2020 2020 2020 207c 2059 6573 2020 7c20         | Yes  | 
+0000bdd0: 2020 2020 2020 2020 2020 207c 0a7c 2060             |.| `
+0000bde0: 7b7b 7461 736b 5f63 6f75 6e74 7d7d 6020  {{task_count}}` 
+0000bdf0: 2020 2020 2020 207c 2054 6865 206e 756d         | The num
+0000be00: 6265 7220 6f66 2054 6173 6b73 2069 6e20  ber of Tasks in 
+0000be10: 7468 6520 6375 7272 656e 7420 5461 736b  the current Task
+0000be20: 2047 726f 7570 2020 2020 207c 2059 6573   Group     | Yes
+0000be30: 2020 7c20 5965 7320 2020 2020 2020 207c    | Yes        |
+0000be40: 0a7c 2060 7b7b 7461 736b 5f67 726f 7570  .| `{{task_group
+0000be50: 5f6e 756d 6265 727d 7d60 207c 2054 6865  _number}}` | The
+0000be60: 2063 7572 7265 6e74 2054 6173 6b20 4772   current Task Gr
+0000be70: 6f75 7020 6e75 6d62 6572 2020 2020 2020  oup number      
+0000be80: 2020 2020 2020 2020 2020 2020 2020 207c                 |
+0000be90: 2059 6573 2020 7c20 5965 7320 2020 2020   Yes  | Yes     
+0000bea0: 2020 207c 0a7c 2060 7b7b 7461 736b 5f67     |.| `{{task_g
+0000beb0: 726f 7570 5f63 6f75 6e74 7d7d 6020 207c  roup_count}}`  |
+0000bec0: 2054 6865 206e 756d 6265 7220 6f66 2054   The number of T
+0000bed0: 6173 6b20 4772 6f75 7073 2069 6e20 7468  ask Groups in th
+0000bee0: 6520 576f 726b 2052 6571 7569 7265 6d65  e Work Requireme
+0000bef0: 6e74 207c 2059 6573 2020 7c20 5965 7320  nt | Yes  | Yes 
+0000bf00: 2020 2020 2020 207c 0a0a 496e 2061 6464         |..In add
+0000bf10: 6974 696f 6e2c 202a 2a54 6173 6b73 2a2a  ition, **Tasks**
+0000bf20: 2064 6566 696e 6564 2069 6e20 4a53 4f4e   defined in JSON
+0000bf30: 2064 6f63 756d 656e 7473 2063 616e 2075   documents can u
+0000bf40: 7365 2061 6e79 206f 6620 7468 6520 7375  se any of the su
+0000bf50: 6273 7469 7475 7469 6f6e 7320 6162 6f76  bstitutions abov
+0000bf60: 6520 696e 2061 6e79 206f 6620 7468 6569  e in any of thei
+0000bf70: 7220 7072 6f70 6572 7469 6573 2c20 6e6f  r properties, no
+0000bf80: 7420 6a75 7374 2060 6e61 6d65 602e 0a0a  t just `name`...
+0000bf90: 4e75 6d62 6572 7320 6172 6520 7a65 726f  Numbers are zero
+0000bfa0: 2d70 6164 6465 6420 666f 7220 6e65 6174  -padded for neat
+0000bfb0: 2066 6f72 6d61 7474 696e 6720 616e 6420   formatting and 
+0000bfc0: 736f 7274 696e 672c 2065 2e67 2e2c 2054  sorting, e.g., T
+0000bfd0: 6173 6b20 6e75 6d62 6572 2060 3337 6020  ask number `37` 
+0000bfe0: 6f66 2060 3130 3030 6020 5461 736b 7320  of `1000` Tasks 
+0000bff0: 776f 756c 6420 6265 2073 7562 7374 6974  would be substit
+0000c000: 7574 6564 2061 7320 6030 3033 3760 2e0a  uted as `0037`..
+0000c010: 0a41 7320 616e 2065 7861 6d70 6c65 2c20  .As an example, 
+0000c020: 7468 6520 666f 6c6c 6f77 696e 6720 4a53  the following JS
+0000c030: 4f4e 2057 6f72 6b20 5265 7175 6972 656d  ON Work Requirem
+0000c040: 656e 743a 0a0a 6060 606a 736f 6e0a 7b0a  ent:..```json.{.
+0000c050: 2020 2274 6173 6b47 726f 7570 7322 3a20    "taskGroups": 
+0000c060: 5b0a 2020 2020 7b0a 2020 2020 2020 226e  [.    {.      "n
+0000c070: 616d 6522 3a20 226d 795f 7461 736b 5f67  ame": "my_task_g
+0000c080: 726f 7570 5f7b 7b74 6173 6b5f 6772 6f75  roup_{{task_grou
+0000c090: 705f 6e75 6d62 6572 7d7d 5f61 3122 2c0a  p_number}}_a1",.
+0000c0a0: 2020 2020 2020 2265 7865 6375 7461 626c        "executabl
+0000c0b0: 6522 3a20 2265 7831 2e73 6822 2c0a 2020  e": "ex1.sh",.  
+0000c0c0: 2020 2020 2274 6173 6b43 6f75 6e74 223a      "taskCount":
+0000c0d0: 2032 2c0a 2020 2020 2020 2274 6173 6b73   2,.      "tasks
+0000c0e0: 223a 205b 0a20 2020 2020 2020 207b 0a20  ": [.        {. 
+0000c0f0: 2020 2020 2020 2020 2022 6e61 6d65 223a           "name":
+0000c100: 2022 6d79 5f74 6173 6b5f 7b7b 7461 736b   "my_task_{{task
+0000c110: 5f6e 756d 6265 727d 7d2d 6f66 2d7b 7b74  _number}}-of-{{t
+0000c120: 6173 6b5f 636f 756e 747d 7d22 2c0a 2020  ask_count}}",.  
+0000c130: 2020 2020 2020 2020 2265 6e76 6972 6f6e          "environ
+0000c140: 6d65 6e74 223a 207b 2254 4153 4b5f 4e55  ment": {"TASK_NU
+0000c150: 4d42 4552 223a 2022 7b7b 7461 736b 5f6e  MBER": "{{task_n
+0000c160: 756d 6265 727d 7d22 7d0a 2020 2020 2020  umber}}"}.      
+0000c170: 2020 7d0a 2020 2020 2020 5d0a 2020 2020    }.      ].    
+0000c180: 7d2c 0a20 2020 207b 0a20 2020 2020 2022  },.    {.      "
+0000c190: 6e61 6d65 223a 2022 6d79 5f74 6173 6b5f  name": "my_task_
+0000c1a0: 6772 6f75 705f 7b7b 7461 736b 5f67 726f  group_{{task_gro
+0000c1b0: 7570 5f6e 756d 6265 727d 7d5f 6231 222c  up_number}}_b1",
+0000c1c0: 0a20 2020 2020 2022 6578 6563 7574 6162  .      "executab
+0000c1d0: 6c65 223a 2022 6578 322e 7368 222c 0a20  le": "ex2.sh",. 
+0000c1e0: 2020 2020 2022 7461 736b 436f 756e 7422       "taskCount"
+0000c1f0: 3a20 322c 0a20 2020 2020 2022 7461 736b  : 2,.      "task
+0000c200: 7322 3a20 5b0a 2020 2020 2020 2020 7b0a  s": [.        {.
+0000c210: 2020 2020 2020 2020 2020 226e 616d 6522            "name"
+0000c220: 3a20 226d 795f 7461 736b 5f7b 7b74 6173  : "my_task_{{tas
+0000c230: 6b5f 6e75 6d62 6572 7d7d 2d6f 662d 7b7b  k_number}}-of-{{
+0000c240: 7461 736b 5f63 6f75 6e74 7d7d 220a 2020  task_count}}".  
+0000c250: 2020 2020 2020 7d0a 2020 2020 2020 5d0a        }.      ].
+0000c260: 2020 2020 7d0a 2020 5d0a 7d0a 6060 600a      }.  ].}.```.
+0000c270: 0a2e 2e2e 2077 6f75 6c64 2063 7265 6174  .... would creat
+0000c280: 6520 5461 736b 2047 726f 7570 7320 6e61  e Task Groups na
+0000c290: 6d65 6420 606d 795f 7461 736b 5f67 726f  med `my_task_gro
+0000c2a0: 7570 5f31 5f61 3160 2061 6e64 2060 6d79  up_1_a1` and `my
+0000c2b0: 5f74 6173 6b5f 6772 6f75 705f 325f 6231  _task_group_2_b1
+0000c2c0: 602c 2065 6163 6820 636f 6e74 6169 6e69  `, each containi
+0000c2d0: 6e67 2054 6173 6b73 206e 616d 6564 2060  ng Tasks named `
+0000c2e0: 6d79 5f74 6173 6b5f 312d 6f66 2d32 602c  my_task_1-of-2`,
+0000c2f0: 2060 6d79 5f74 6173 6b5f 322d 6f66 2d32   `my_task_2-of-2
+0000c300: 602e 0a0a 2323 2320 576f 726b 2052 6571  `...### Work Req
+0000c310: 7569 7265 6d65 6e74 204e 616d 6520 5375  uirement Name Su
+0000c320: 6273 7469 7475 7469 6f6e 0a0a 5468 6520  bstitution..The 
+0000c330: 6e61 6d65 206f 6620 7468 6520 576f 726b  name of the Work
+0000c340: 2052 6571 7569 7265 6d65 6e74 2069 7473   Requirement its
+0000c350: 656c 6620 6361 6e20 6265 2075 7365 6420  elf can be used 
+0000c360: 7669 6120 7468 6520 7661 7269 6162 6c65  via the variable
+0000c370: 2073 7562 7374 6974 7574 696f 6e20 607b   substitution `{
+0000c380: 7b77 725f 6e61 6d65 7d7d 602e 2054 6869  {wr_name}}`. Thi
+0000c390: 7320 6361 6e20 6265 2075 7365 6420 616e  s can be used an
+0000c3a0: 7977 6865 7265 2069 6e20 6120 544f 4d4c  ywhere in a TOML
+0000c3b0: 2063 6f6e 6669 6775 7261 7469 6f6e 2066   configuration f
+0000c3c0: 696c 6520 6f72 2069 6e20 6120 4a53 4f4e  ile or in a JSON
+0000c3d0: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+0000c3e0: 742e 0a0a 2323 2044 7279 2d52 756e 6e69  t...## Dry-Runni
+0000c3f0: 6e67 2057 6f72 6b20 5265 7175 6972 656d  ng Work Requirem
+0000c400: 656e 7420 5375 626d 6973 7369 6f6e 730a  ent Submissions.
+0000c410: 0a54 6f20 6578 616d 696e 6520 7468 6520  .To examine the 
+0000c420: 4a53 4f4e 2074 6861 7420 7769 6c6c 2061  JSON that will a
+0000c430: 6374 7561 6c6c 7920 6265 2073 656e 7420  ctually be sent 
+0000c440: 746f 2074 6865 2059 656c 6c6f 7744 6f67  to the YellowDog
+0000c450: 2041 5049 2061 6674 6572 2061 6c6c 2070   API after all p
+0000c460: 726f 6365 7373 696e 672c 2075 7365 2074  rocessing, use t
+0000c470: 6865 2060 2d2d 6472 792d 7275 6e60 2063  he `--dry-run` c
+0000c480: 6f6d 6d61 6e64 206c 696e 6520 6f70 7469  ommand line opti
+0000c490: 6f6e 2077 6865 6e20 7275 6e6e 696e 6720  on when running 
+0000c4a0: 6079 642d 7375 626d 6974 602e 2054 6869  `yd-submit`. Thi
+0000c4b0: 7320 7769 6c6c 2070 7269 6e74 2074 6865  s will print the
+0000c4c0: 2066 756c 6c79 2070 726f 6365 7373 6564   fully processed
+0000c4d0: 204a 534f 4e20 666f 7220 7468 6520 576f   JSON for the Wo
+0000c4e0: 726b 2052 6571 7569 7265 6d65 6e74 2e20  rk Requirement. 
+0000c4f0: 4e6f 7468 696e 6720 7769 6c6c 2062 6520  Nothing will be 
+0000c500: 7375 626d 6974 7465 6420 746f 2074 6865  submitted to the
+0000c510: 2050 6c61 7466 6f72 6d2e 0a0a 5468 6520   Platform...The 
+0000c520: 6472 792d 7275 6e20 6973 2075 7365 6675  dry-run is usefu
+0000c530: 6c20 666f 7220 696e 7370 6563 7469 6e67  l for inspecting
+0000c540: 2074 6865 2072 6573 756c 7473 206f 6620   the results of 
+0000c550: 616c 6c20 7468 6520 7072 6f63 6573 7369  all the processi
+0000c560: 6e67 2074 6861 7427 7320 6265 656e 2070  ng that's been p
+0000c570: 6572 666f 726d 6564 2e20 546f 2073 7570  erformed. To sup
+0000c580: 7072 6573 7320 616c 6c20 6f75 7470 7574  press all output
+0000c590: 2065 7863 6570 7420 666f 7220 7468 6520   except for the 
+0000c5a0: 4a53 4f4e 2069 7473 656c 662c 2075 7365  JSON itself, use
+0000c5b0: 2074 6865 2060 2d2d 7175 6965 7460 2028   the `--quiet` (
+0000c5c0: 602d 7160 2920 636f 6d6d 616e 6420 6c69  `-q`) command li
+0000c5d0: 6e65 206f 7074 696f 6e2e 0a0a 4e6f 7465  ne option...Note
+0000c5e0: 2074 6861 7420 7468 6520 6765 6e65 7261   that the genera
+0000c5f0: 7465 6420 4a53 4f4e 2069 7320 6120 636f  ted JSON is a co
+0000c600: 6e73 6f6c 6964 6174 6564 2066 6f72 6d20  nsolidated form 
+0000c610: 6f66 2077 6861 7420 776f 756c 6420 6265  of what would be
+0000c620: 2073 7562 6d69 7474 6564 2074 6f20 7468   submitted to th
+0000c630: 6520 5965 6c6c 6f77 446f 6720 4150 492c  e YellowDog API,
+0000c640: 2061 6e64 2054 6173 6b73 2061 7265 2064   and Tasks are d
+0000c650: 6566 696e 6564 2064 6972 6563 746c 7920  efined directly 
+0000c660: 7769 7468 696e 2074 6865 6972 2054 6173  within their Tas
+0000c670: 6b20 4772 6f75 7073 2066 6f72 2065 6173  k Groups for eas
+0000c680: 6520 6f66 2063 6f6d 7072 6568 656e 7369  e of comprehensi
+0000c690: 6f6e 2e20 496e 2061 6374 7561 6c20 4150  on. In actual AP
+0000c6a0: 4920 7375 626d 6973 7369 6f6e 732c 2074  I submissions, t
+0000c6b0: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
+0000c6c0: 656e 7420 7769 7468 2069 7473 2054 6173  ent with its Tas
+0000c6d0: 6b20 4772 6f75 7073 2069 7320 7375 626d  k Groups is subm
+0000c6e0: 6974 7465 6420 6669 7273 742c 2061 6e64  itted first, and
+0000c6f0: 2054 6173 6b73 2061 7265 2074 6865 6e20   Tasks are then 
+0000c700: 6164 6465 6420 746f 2054 6173 6b20 4772  added to Task Gr
+0000c710: 6f75 7073 2073 6570 6172 6174 656c 7920  oups separately 
+0000c720: 696e 2073 7562 7365 7175 656e 7420 4150  in subsequent AP
+0000c730: 4920 6361 6c6c 732e 0a0a 4120 7369 6d70  I calls...A simp
+0000c740: 6c65 2065 7861 6d70 6c65 206f 6620 7468  le example of th
+0000c750: 6520 4a53 4f4e 206f 7574 7075 7420 6973  e JSON output is
+0000c760: 2073 686f 776e 2062 656c 6f77 2c20 7368   shown below, sh
+0000c770: 6f77 696e 6720 6120 576f 726b 2052 6571  owing a Work Req
+0000c780: 7569 7265 6d65 6e74 2077 6974 6820 6120  uirement with a 
+0000c790: 7369 6e67 6c65 2054 6173 6b20 4772 6f75  single Task Grou
+0000c7a0: 702c 2063 6f6e 7461 696e 696e 6720 6120  p, containing a 
+0000c7b0: 7369 6e67 6c65 2054 6173 6b2e 0a0a 6025  single Task...`%
+0000c7c0: 2079 642d 7375 626d 6974 202d 2d64 7279   yd-submit --dry
+0000c7d0: 2d72 756e 202d 2d71 7569 6574 600a 6060  -run --quiet`.``
+0000c7e0: 606a 736f 6e0a 7b0a 2020 2266 756c 6669  `json.{.  "fulfi
+0000c7f0: 6c4f 6e53 7562 6d69 7422 3a20 6661 6c73  lOnSubmit": fals
+0000c800: 652c 0a20 2022 6e61 6d65 223a 2022 7079  e,.  "name": "py
+0000c810: 6578 2d62 6173 685f 3233 3031 3134 2d30  ex-bash_230114-0
+0000c820: 3935 3530 342d 3533 6122 2c0a 2020 226e  95504-53a",.  "n
+0000c830: 616d 6573 7061 6365 223a 2022 7079 6578  amespace": "pyex
+0000c840: 616d 706c 6573 222c 0a20 2022 7072 696f  amples",.  "prio
+0000c850: 7269 7479 223a 2030 2c0a 2020 2274 6167  rity": 0,.  "tag
+0000c860: 223a 2022 7079 6578 2d62 6173 6822 2c0a  ": "pyex-bash",.
+0000c870: 2020 2274 6173 6b47 726f 7570 7322 3a20    "taskGroups": 
+0000c880: 5b0a 2020 2020 7b0a 2020 2020 2020 2266  [.    {.      "f
+0000c890: 696e 6973 6849 6641 6c6c 5461 736b 7346  inishIfAllTasksF
+0000c8a0: 696e 6973 6865 6422 3a20 7472 7565 2c0a  inished": true,.
+0000c8b0: 2020 2020 2020 2266 696e 6973 6849 6641        "finishIfA
+0000c8c0: 6e79 5461 736b 4661 696c 6564 223a 2066  nyTaskFailed": f
+0000c8d0: 616c 7365 2c0a 2020 2020 2020 226e 616d  alse,.      "nam
+0000c8e0: 6522 3a20 2274 6173 6b5f 6772 6f75 705f  e": "task_group_
+0000c8f0: 3122 2c0a 2020 2020 2020 2270 7269 6f72  1",.      "prior
+0000c900: 6974 7922 3a20 302c 0a20 2020 2020 2022  ity": 0,.      "
+0000c910: 7275 6e53 7065 6369 6669 6361 7469 6f6e  runSpecification
+0000c920: 223a 207b 0a20 2020 2020 2020 2022 6d61  ": {.        "ma
+0000c930: 7869 6d75 6d54 6173 6b52 6574 7269 6573  ximumTaskRetries
+0000c940: 223a 2030 2c0a 2020 2020 2020 2020 2274  ": 0,.        "t
+0000c950: 6173 6b54 7970 6573 223a 205b 2262 6173  askTypes": ["bas
+0000c960: 6822 5d2c 0a20 2020 2020 2020 2022 776f  h"],.        "wo
+0000c970: 726b 6572 5461 6773 223a 205b 2270 7965  rkerTags": ["pye
+0000c980: 782d 6261 7368 225d 0a20 2020 2020 207d  x-bash"].      }
+0000c990: 2c0a 2020 2020 2020 2274 6173 6b73 223a  ,.      "tasks":
+0000c9a0: 205b 0a20 2020 2020 2020 207b 0a20 2020   [.        {.   
+0000c9b0: 2020 2020 2020 2022 6172 6775 6d65 6e74         "argument
+0000c9c0: 7322 3a20 5b22 7079 6578 2d62 6173 685f  s": ["pyex-bash_
+0000c9d0: 3233 3031 3134 2d30 3935 3530 342d 3533  230114-095504-53
+0000c9e0: 612f 736c 6565 705f 7363 7269 7074 2e73  a/sleep_script.s
+0000c9f0: 6822 5d2c 0a20 2020 2020 2020 2020 2022  h"],.          "
+0000ca00: 656e 7669 726f 6e6d 656e 7422 3a20 7b7d  environment": {}
+0000ca10: 2c0a 2020 2020 2020 2020 2020 2269 6e70  ,.          "inp
+0000ca20: 7574 7322 3a20 5b0a 2020 2020 2020 2020  uts": [.        
+0000ca30: 2020 2020 7b0a 2020 2020 2020 2020 2020      {.          
+0000ca40: 2020 2020 226f 626a 6563 744e 616d 6550      "objectNameP
+0000ca50: 6174 7465 726e 223a 2022 7079 6578 2d62  attern": "pyex-b
+0000ca60: 6173 685f 3233 3031 3134 2d30 3935 3530  ash_230114-09550
+0000ca70: 342d 3533 612f 736c 6565 705f 7363 7269  4-53a/sleep_scri
+0000ca80: 7074 2e73 6822 2c0a 2020 2020 2020 2020  pt.sh",.        
+0000ca90: 2020 2020 2020 2273 6f75 7263 6522 3a20        "source": 
+0000caa0: 2254 4153 4b5f 4e41 4d45 5350 4143 4522  "TASK_NAMESPACE"
+0000cab0: 2c0a 2020 2020 2020 2020 2020 2020 2020  ,.              
+0000cac0: 2276 6572 6966 6963 6174 696f 6e22 3a20  "verification": 
+0000cad0: 2256 4552 4946 595f 5741 4954 220a 2020  "VERIFY_WAIT".  
+0000cae0: 2020 2020 2020 2020 2020 7d0a 2020 2020            }.    
+0000caf0: 2020 2020 2020 5d2c 0a20 2020 2020 2020        ],.       
+0000cb00: 2020 2022 6e61 6d65 223a 2022 7461 736b     "name": "task
+0000cb10: 5f30 3122 2c0a 2020 2020 2020 2020 2020  _01",.          
+0000cb20: 226f 7574 7075 7473 223a 205b 0a20 2020  "outputs": [.   
+0000cb30: 2020 2020 2020 2020 207b 2261 6c77 6179           {"alway
+0000cb40: 7355 706c 6f61 6422 3a20 7472 7565 2c20  sUpload": true, 
+0000cb50: 2272 6571 7569 7265 6422 3a20 6661 6c73  "required": fals
+0000cb60: 652c 2022 736f 7572 6365 223a 2022 5052  e, "source": "PR
+0000cb70: 4f43 4553 535f 4f55 5450 5554 227d 0a20  OCESS_OUTPUT"}. 
+0000cb80: 2020 2020 2020 2020 205d 2c0a 2020 2020           ],.    
+0000cb90: 2020 2020 2020 2274 6173 6b54 7970 6522        "taskType"
+0000cba0: 3a20 2262 6173 6822 0a20 2020 2020 2020  : "bash".       
+0000cbb0: 207d 0a20 2020 2020 205d 0a20 2020 207d   }.      ].    }
+0000cbc0: 0a20 205d 0a7d 0a60 6060 0a0a 2323 2320  .  ].}.```..### 
+0000cbd0: 5375 626d 6974 7469 6e67 2027 5261 7727  Submitting 'Raw'
+0000cbe0: 204a 534f 4e20 576f 726b 2052 6571 7569   JSON Work Requi
+0000cbf0: 7265 6d65 6e74 2053 7065 6369 6669 6361  rement Specifica
+0000cc00: 7469 6f6e 730a 0a49 7427 7320 706f 7373  tions..It's poss
+0000cc10: 6962 6c65 2074 6f20 7573 6520 7468 6520  ible to use the 
+0000cc20: 4a53 4f4e 206f 7574 7075 7420 6f66 2060  JSON output of `
+0000cc30: 7964 2d73 7562 6d69 7420 2d2d 6472 792d  yd-submit --dry-
+0000cc40: 7275 6e60 2028 7375 6368 2061 7320 7468  run` (such as th
+0000cc50: 6520 6578 616d 706c 6520 6162 6f76 6529  e example above)
+0000cc60: 2061 7320 6120 7365 6c66 2d63 6f6e 7461   as a self-conta
+0000cc70: 696e 6564 2c20 6675 6c6c 792d 7370 6563  ined, fully-spec
+0000cc80: 6966 6965 6420 576f 726b 2052 6571 7569  ified Work Requi
+0000cc90: 7265 6d65 6e74 2073 7065 6369 6669 6361  rement specifica
+0000cca0: 7469 6f6e 2c20 7573 696e 6720 7468 6520  tion, using the 
+0000ccb0: 602d 2d6a 736f 6e2d 7261 7760 2028 6f72  `--json-raw` (or
+0000ccc0: 2060 2d6a 6029 2063 6f6d 6d61 6e64 206c   `-j`) command l
+0000ccd0: 696e 6520 6f70 7469 6f6e 2c20 692e 652e  ine option, i.e.
+0000cce0: 3a20 6079 642d 7375 626d 6974 202d 2d6a  : `yd-submit --j
+0000ccf0: 736f 6e2d 7261 7720 3c66 696c 656e 616d  son-raw <filenam
+0000cd00: 652e 6a73 6f6e 3e60 2e0a 0a54 6869 7320  e.json>`...This 
+0000cd10: 7769 6c6c 2073 7562 6d69 7420 7468 6520  will submit the 
+0000cd20: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+0000cd30: 2c20 7468 656e 2061 6464 2061 6c6c 2074  , then add all t
+0000cd40: 6865 2073 7065 6369 6669 6564 2054 6173  he specified Tas
+0000cd50: 6b73 2e0a 0a4e 6f74 6520 7468 6174 2076  ks...Note that v
+0000cd60: 6172 6961 626c 6520 7375 6273 7469 7475  ariable substitu
+0000cd70: 7469 6f6e 7320 2a2a 6361 6e2a 2a20 6265  tions **can** be
+0000cd80: 2075 7365 6420 696e 2074 6865 2072 6177   used in the raw
+0000cd90: 204a 534f 4e20 6669 6c65 2c20 6a75 7374   JSON file, just
+0000cda0: 2061 7320 696e 2074 6865 206f 7468 6572   as in the other
+0000cdb0: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+0000cdc0: 7420 4a53 4f4e 2065 7861 6d70 6c65 732c  t JSON examples,
+0000cdd0: 2062 7574 2074 6865 7265 2069 7320 6e6f   but there is no
+0000cde0: 2070 726f 7065 7274 7920 696e 6865 7269   property inheri
+0000cdf0: 7461 6e63 652c 2069 6e63 6c75 6469 6e67  tance, including
+0000ce00: 2066 726f 6d20 7468 6520 605b 776f 726b   from the `[work
+0000ce10: 5265 7175 6972 656d 656e 745d 6020 7365  Requirement]` se
+0000ce20: 6374 696f 6e20 6f66 2074 6865 2054 4f4d  ction of the TOM
+0000ce30: 4c20 636f 6e66 6967 7572 6174 696f 6e20  L configuration 
+0000ce40: 6f72 2066 726f 6d20 576f 726b 2052 6571  or from Work Req
+0000ce50: 7569 7265 6d65 6e74 2070 726f 7065 7274  uirement propert
+0000ce60: 6965 7320 7375 7070 6c69 6564 206f 6e20  ies supplied on 
+0000ce70: 7468 6520 636f 6d6d 616e 6420 6c69 6e65  the command line
+0000ce80: 2e0a 0a4e 6f74 6520 7468 6174 2074 6865  ...Note that the
+0000ce90: 7265 2069 7320 6e6f 2061 7574 6f6d 6174  re is no automat
+0000cea0: 6963 2066 696c 6520 7570 6c6f 6164 2077  ic file upload w
+0000ceb0: 6865 6e20 7573 696e 6720 7468 6973 206f  hen using this o
+0000cec0: 7074 696f 6e2c 2073 6f20 616e 7920 6669  ption, so any fi
+0000ced0: 6c65 7320 7265 7175 6972 6564 2061 7420  les required at 
+0000cee0: 7468 6520 7374 6172 7420 6f66 2074 6865  the start of the
+0000cef0: 2074 6173 6b20 2873 7065 6369 6669 6564   task (specified
+0000cf00: 2075 7369 6e67 2060 5645 5249 4659 5f41   using `VERIFY_A
+0000cf10: 545f 5354 4152 5460 2920 6d75 7374 2062  T_START`) must b
+0000cf20: 6520 7072 6573 656e 7420 6265 666f 7265  e present before
+0000cf30: 2074 6865 2054 6173 6b73 2061 7265 2075   the Tasks are u
+0000cf40: 706c 6f61 6465 642c 206f 7220 7468 6520  ploaded, or the 
+0000cf50: 5461 736b 7320 7769 6c6c 2066 6169 6c20  Tasks will fail 
+0000cf60: 696d 6d65 6469 6174 656c 792e 2054 6865  immediately. The
+0000cf70: 2060 7964 2d75 706c 6f61 6460 2063 6f6d   `yd-upload` com
+0000cf80: 6d61 6e64 2063 616e 2062 6520 7573 6564  mand can be used
+0000cf90: 2074 6f20 7570 6c6f 6164 2074 6865 7365   to upload these
+0000cfa0: 2066 696c 6573 2c20 616e 6420 6079 642d   files, and `yd-
+0000cfb0: 7375 626d 6974 6020 7769 6c6c 2070 6175  submit` will pau
+0000cfc0: 7365 2074 6f20 616c 6c6f 7720 7468 6973  se to allow this
+0000cfd0: 2074 6f20 6861 7070 656e 2e0a 0a23 2320   to happen...## 
+0000cfe0: 4669 6c65 2053 746f 7261 6765 204c 6f63  File Storage Loc
+0000cff0: 6174 696f 6e73 2061 6e64 2046 696c 6520  ations and File 
+0000d000: 5573 6167 650a 0a54 6869 7320 7365 6374  Usage..This sect
+0000d010: 696f 6e20 6469 7363 7573 7365 7320 686f  ion discusses ho
+0000d020: 7720 746f 2075 706c 6f61 6420 6669 6c65  w to upload file
+0000d030: 7320 6672 6f6d 206c 6f63 616c 2073 746f  s from local sto
+0000d040: 7261 6765 2074 6f20 7468 6520 5965 6c6c  rage to the Yell
+0000d050: 6f77 446f 6720 4f62 6a65 6374 2053 746f  owDog Object Sto
+0000d060: 7265 2c20 686f 7720 7468 6f73 6520 6669  re, how those fi
+0000d070: 6c65 7320 6172 6520 7472 616e 7366 6572  les are transfer
+0000d080: 7265 6420 746f 2057 6f72 6b65 7220 4e6f  red to Worker No
+0000d090: 6465 7320 666f 7220 5461 736b 2070 726f  des for Task pro
+0000d0a0: 6365 7373 696e 672c 2068 6f77 2074 6865  cessing, how the
+0000d0b0: 2072 6573 756c 7473 206f 6620 5461 736b   results of Task
+0000d0c0: 2070 726f 6365 7373 696e 6720 6172 6520   processing are 
+0000d0d0: 7265 7475 726e 6564 2062 7920 576f 726b  returned by Work
+0000d0e0: 6572 204e 6f64 6573 2c20 616e 6420 686f  er Nodes, and ho
+0000d0f0: 7720 6669 6c65 7320 6172 6520 7472 616e  w files are tran
+0000d100: 7366 6572 7265 6420 6261 636b 2066 726f  sferred back fro
+0000d110: 6d20 7468 6520 5965 6c6c 6f77 446f 6720  m the YellowDog 
+0000d120: 4f62 6a65 6374 2053 746f 7265 2074 6f20  Object Store to 
+0000d130: 6c6f 6361 6c20 7374 6f72 6167 652e 0a0a  local storage...
+0000d140: 2323 2320 4669 6c65 7320 5570 6c6f 6164  ### Files Upload
+0000d150: 6564 2074 6f20 7468 6520 4f62 6a65 6374  ed to the Object
+0000d160: 2053 746f 7265 2066 726f 6d20 4c6f 6361   Store from Loca
+0000d170: 6c20 5374 6f72 6167 650a 0a23 2323 2320  l Storage..#### 
+0000d180: 4669 6c65 7320 696e 2074 6865 2060 696e  Files in the `in
+0000d190: 7075 7473 6020 4c69 7374 0a0a 5768 656e  puts` List..When
+0000d1a0: 2061 2057 6f72 6b20 5265 7175 6972 656d   a Work Requirem
+0000d1b0: 656e 7420 6973 2073 7562 6d69 7474 6564  ent is submitted
+0000d1c0: 2075 7369 6e67 2060 7964 2d73 7562 6d69   using `yd-submi
+0000d1d0: 7460 2c20 6669 6c65 7320 6172 6520 7570  t`, files are up
+0000d1e0: 6c6f 6164 6564 2074 6f20 7468 6520 5965  loaded to the Ye
+0000d1f0: 6c6c 6f77 446f 6720 4f62 6a65 6374 2053  llowDog Object S
+0000d200: 746f 7265 2069 6620 7468 6579 2772 6520  tore if they're 
+0000d210: 696e 636c 7564 6564 2069 6e20 7468 6520  included in the 
+0000d220: 6c69 7374 206f 6620 6669 6c65 7320 696e  list of files in
+0000d230: 2074 6865 2060 696e 7075 7473 6020 7072   the `inputs` pr
+0000d240: 6f70 6572 7479 2e20 2846 6f72 2074 6865  operty. (For the
+0000d250: 2063 6173 6520 6f66 2074 6865 2060 6261   case of the `ba
+0000d260: 7368 6020 5461 736b 2054 7970 652c 2074  sh` Task Type, t
+0000d270: 6865 2073 6372 6970 7420 7370 6563 6966  he script specif
+0000d280: 6965 6420 696e 2074 6865 2060 6578 6563  ied in the `exec
+0000d290: 7574 6162 6c65 6020 7072 6f70 6572 7479  utable` property
+0000d2a0: 2069 7320 616c 736f 2061 7574 6f6d 6174   is also automat
+0000d2b0: 6963 616c 6c79 2075 706c 6f61 6465 6420  ically uploaded 
+0000d2c0: 6173 2061 2063 6f6e 7665 6e69 656e 6365  as a convenience
+0000d2d0: 2c20 6576 656e 2069 6620 6e6f 7420 696e  , even if not in
+0000d2e0: 636c 7564 6564 2069 6e20 7468 6520 6069  cluded in the `i
+0000d2f0: 6e70 7574 7360 206c 6973 742e 290a 0a54  nputs` list.)..T
+0000d300: 6865 2060 696e 7075 7473 6020 7072 6f70  he `inputs` prop
+0000d310: 6572 7479 2061 6363 6570 7473 2077 696c  erty accepts wil
+0000d320: 6463 6172 6420 6669 6c65 6e61 6d65 732c  dcard filenames,
+0000d330: 2065 2e67 2e3a 2060 5b22 2a2e 7368 222c   e.g.: `["*.sh",
+0000d340: 2022 2a2e 7478 7422 5d60 2e20 5468 6973   "*.txt"]`. This
+0000d350: 2063 616e 2062 6520 7573 6564 2074 6f20   can be used to 
+0000d360: 6164 6420 7468 6520 636f 6e74 656e 7473  add the contents
+0000d370: 206f 6620 6469 7265 6374 6f72 6965 732c   of directories,
+0000d380: 2065 2e67 2e3a 2060 5b22 6d79 5f64 6972   e.g.: `["my_dir
+0000d390: 2f2a 222c 2022 6461 7461 2a2f 2a22 5d60  /*", "data*/*"]`
+0000d3a0: 2e0a 0a46 696c 6573 2061 7265 2075 706c  ...Files are upl
+0000d3b0: 6f61 6465 6420 746f 2074 6865 204e 616d  oaded to the Nam
+0000d3c0: 6573 7061 6365 2073 7065 6369 6669 6564  espace specified
+0000d3d0: 2069 6e20 7468 6520 636f 6e66 6967 7572   in the configur
+0000d3e0: 6174 696f 6e2e 2057 6974 6869 6e20 7468  ation. Within th
+0000d3f0: 6520 4e61 6d65 7370 6163 652c 2065 6163  e Namespace, eac
+0000d400: 6820 576f 726b 2052 6571 7569 7265 6d65  h Work Requireme
+0000d410: 6e74 2068 6173 2061 2073 6570 6172 6174  nt has a separat
+0000d420: 6520 666f 6c64 6572 2074 6861 7420 7368  e folder that sh
+0000d430: 6172 6573 2074 6865 206e 616d 6520 6f66  ares the name of
+0000d440: 2074 6865 2057 6f72 6b20 5265 7175 6972   the Work Requir
+0000d450: 656d 656e 742c 2061 6e64 2069 6e20 7768  ement, and in wh
+0000d460: 6963 6820 616c 6c20 6669 6c65 7320 7265  ich all files re
+0000d470: 6c61 7465 6420 746f 2074 6865 2057 6f72  lated to the Wor
+0000d480: 6b20 5265 7175 6972 656d 656e 7420 6172  k Requirement ar
+0000d490: 6520 7374 6f72 6564 2e0a 0a31 2e20 4669  e stored...1. Fi
+0000d4a0: 6c65 7320 746f 2062 6520 7570 6c6f 6164  les to be upload
+0000d4b0: 6564 2074 6861 7420 6172 6520 696e 2074  ed that are in t
+0000d4c0: 6865 202a 2a73 616d 6520 6469 7265 6374  he **same direct
+0000d4d0: 6f72 7920 6173 2074 6865 2057 6f72 6b20  ory as the Work 
+0000d4e0: 5265 7175 6972 656d 656e 7420 7370 6563  Requirement spec
+0000d4f0: 6966 6963 6174 696f 6e2a 2a20 2874 6865  ification** (the
+0000d500: 2054 4f4d 4c20 6f72 204a 534f 4e20 6669   TOML or JSON fi
+0000d510: 6c65 2920 6172 6520 7570 6c6f 6164 6564  le) are uploaded
+0000d520: 2074 6f20 7468 6520 726f 6f74 206f 6620   to the root of 
+0000d530: 7468 6520 576f 726b 2052 6571 7569 7265  the Work Require
+0000d540: 6d65 6e74 2066 6f6c 6465 722e 0a0a 0a32  ment folder....2
+0000d550: 2e20 4669 6c65 7320 746f 2062 6520 7570  . Files to be up
+0000d560: 6c6f 6164 6564 2074 6861 7420 6172 6520  loaded that are 
+0000d570: 696e 202a 2a73 7562 6469 7265 6374 6f72  in **subdirector
+0000d580: 6965 7320 6265 6c6f 7720 7468 6520 576f  ies below the Wo
+0000d590: 726b 2052 6571 7569 7265 6d65 6e74 2073  rk Requirement s
+0000d5a0: 7065 6369 6669 6361 7469 6f6e 2c20 6f72  pecification, or
+0000d5b0: 2077 6865 7265 2061 6273 6f6c 7574 6520   where absolute 
+0000d5c0: 7061 7468 6e61 6d65 7320 6172 6520 7375  pathnames are su
+0000d5d0: 7070 6c69 6564 2a2a 2061 7265 2070 6c61  pplied** are pla
+0000d5e0: 6365 6420 696e 2074 6865 204f 626a 6563  ced in the Objec
+0000d5f0: 7420 5374 6f72 6520 696e 2064 6972 6563  t Store in direc
+0000d600: 746f 7269 6573 2074 6861 7420 6d69 7272  tories that mirr
+0000d610: 6f72 2074 6865 6972 206c 6f63 616c 2073  or their local s
+0000d620: 746f 7261 6765 206c 6f63 6174 696f 6e73  torage locations
+0000d630: 2e0a 0a0a 332e 2046 696c 6573 2074 6f20  ....3. Files to 
+0000d640: 6265 2075 706c 6f61 6465 6420 7468 6174  be uploaded that
+0000d650: 2061 7265 2069 6e20 2a2a 6469 7265 6374   are in **direct
+0000d660: 6f72 6965 7320 7265 6c61 7469 7665 2074  ories relative t
+0000d670: 6f20 7468 6520 576f 726b 2052 6571 7569  o the Work Requi
+0000d680: 7265 6d65 6e74 2073 7065 6369 6669 6361  rement specifica
+0000d690: 7469 6f6e 2c20 7573 696e 6720 602e 2e60  tion, using `..`
+0000d6a0: 2072 656c 6174 6976 6520 7061 7468 732a   relative paths*
+0000d6b0: 2a20 6172 6520 706c 6163 6564 2069 6e20  * are placed in 
+0000d6c0: 4f62 6a65 6374 2053 746f 7265 2064 6972  Object Store dir
+0000d6d0: 6563 746f 7269 6573 2069 6e20 7768 6963  ectories in whic
+0000d6e0: 6820 7468 6520 602e 2e60 2070 6172 7473  h the `..` parts
+0000d6f0: 206f 6620 7468 6520 7061 7468 6e61 6d65   of the pathname
+0000d700: 2061 7265 2072 6570 6c61 6365 6420 7769   are replaced wi
+0000d710: 7468 2061 6e20 696e 7465 6765 7220 636f  th an integer co
+0000d720: 756e 7420 6f66 2074 6865 206e 756d 6265  unt of the numbe
+0000d730: 7220 6f66 2060 2e2e 6020 656e 7472 6965  r of `..` entrie
+0000d740: 7320 2862 6563 6175 7365 2077 6520 6361  s (because we ca
+0000d750: 6e27 7420 7573 6520 7468 6520 602e 2e60  n't use the `..`
+0000d760: 2072 656c 6174 6976 6520 666f 726d 2069   relative form i
+0000d770: 6e20 7468 6520 4f62 6a65 6374 2053 746f  n the Object Sto
+0000d780: 7265 292e 0a0a 4173 7375 6d69 6e67 2061  re)...Assuming a
+0000d790: 204e 616d 6573 7061 6365 2063 616c 6c65   Namespace calle
+0000d7a0: 6420 6064 6576 656c 6f70 6d65 6e74 6020  d `development` 
+0000d7b0: 616e 6420 6120 576f 726b 2052 6571 7569  and a Work Requi
+0000d7c0: 7265 6d65 6e74 206e 616d 6564 2060 7465  rement named `te
+0000d7d0: 7374 7275 6e5f 3232 3131 3038 2d31 3230  strun_221108-120
+0000d7e0: 3430 342d 3764 3260 2c20 7468 6520 666f  404-7d2`, the fo
+0000d7f0: 6c6c 6f77 696e 6720 6c6f 6361 7469 6f6e  llowing location
+0000d800: 7320 6172 6520 7573 6564 2077 6865 6e20  s are used when 
+0000d810: 7570 6c6f 6164 696e 6720 6669 6c65 7320  uploading files 
+0000d820: 666f 6c6c 6f77 696e 6720 7468 6520 7061  following the pa
+0000d830: 7474 6572 6e73 2061 626f 7665 3a0a 0a60  tterns above:..`
+0000d840: 6060 7368 656c 6c0a 2269 6e70 7574 7322  ``shell."inputs"
+0000d850: 203a 205b 2266 696c 655f 312e 7478 7422   : ["file_1.txt"
+0000d860: 5d20 2d3e 2064 6576 656c 6f70 6d65 6e74  ] -> development
+0000d870: 3a3a 7465 7374 7275 6e5f 3232 3131 3038  ::testrun_221108
+0000d880: 2d31 3230 3430 342d 3764 322f 6669 6c65  -120404-7d2/file
 0000d890: 5f31 2e74 7874 0a22 696e 7075 7473 2220  _1.txt."inputs" 
-0000d8a0: 3a20 5b22 2f68 6f6d 652f 6465 762f 6669  : ["/home/dev/fi
-0000d8b0: 6c65 5f31 2e74 7874 225d 202d 3e20 6465  le_1.txt"] -> de
-0000d8c0: 7665 6c6f 706d 656e 743a 3a74 6573 7472  velopment::testr
-0000d8d0: 756e 5f32 3231 3130 382d 3132 3034 3034  un_221108-120404
-0000d8e0: 2d37 6432 2f68 6f6d 652f 6465 762f 6669  -7d2/home/dev/fi
-0000d8f0: 6c65 5f31 2e74 7874 0a22 696e 7075 7473  le_1.txt."inputs
-0000d900: 2220 3a20 5b22 2e2e 2f64 6576 2f66 696c  " : ["../dev/fil
-0000d910: 655f 312e 7478 7422 5d20 2d3e 2064 6576  e_1.txt"] -> dev
-0000d920: 656c 6f70 6d65 6e74 3a3a 7465 7374 7275  elopment::testru
-0000d930: 6e5f 3232 3131 3038 2d31 3230 3430 342d  n_221108-120404-
-0000d940: 3764 322f 312f 6465 762f 6669 6c65 5f31  7d2/1/dev/file_1
-0000d950: 2e74 7874 0a22 696e 7075 7473 2220 3a20  .txt."inputs" : 
-0000d960: 5b22 2e2e 2f2e 2e2f 6465 762f 6669 6c65  ["../../dev/file
-0000d970: 5f31 2e74 7874 225d 202d 3e20 6465 7665  _1.txt"] -> deve
-0000d980: 6c6f 706d 656e 743a 3a74 6573 7472 756e  lopment::testrun
-0000d990: 5f32 3231 3130 382d 3132 3034 3034 2d37  _221108-120404-7
-0000d9a0: 6432 2f32 2f64 6576 2f66 696c 655f 312e  d2/2/dev/file_1.
-0000d9b0: 7478 740a 6060 600a 0a2a 2a55 7369 6e67  txt.```..**Using
-0000d9c0: 2060 666c 6174 7465 6e55 706c 6f61 6450   `flattenUploadP
-0000d9d0: 6174 6873 602a 2a0a 0a54 6865 2060 666c  aths`**..The `fl
-0000d9e0: 6174 7465 6e55 706c 6f61 6450 6174 6873  attenUploadPaths
-0000d9f0: 6020 7072 6f70 6572 7479 2063 616e 2062  ` property can b
-0000da00: 6520 7573 6564 2074 6f20 7375 7070 7265  e used to suppre
-0000da10: 7373 2074 6865 206d 6972 726f 7269 6e67  ss the mirroring
-0000da20: 206f 6620 616e 7920 6c6f 6361 6c20 6469   of any local di
-0000da30: 7265 6374 6f72 7920 7374 7275 6374 7572  rectory structur
-0000da40: 6520 7768 656e 2075 706c 6f61 6469 6e67  e when uploading
-0000da50: 2066 696c 6573 2074 6f20 7468 6520 4f62   files to the Ob
-0000da60: 6a65 6374 2053 746f 7265 2e20 4966 2073  ject Store. If s
-0000da70: 6574 2074 6f20 6074 7275 6560 2c20 616c  et to `true`, al
-0000da80: 6c20 6669 6c65 7320 7769 6c6c 2062 6520  l files will be 
-0000da90: 7570 6c6f 6164 6564 2074 6f20 7468 6520  uploaded to the 
-0000daa0: 726f 6f74 206f 6620 7468 6520 576f 726b  root of the Work
-0000dab0: 2052 6571 7569 7265 6d65 6e74 2066 6f6c   Requirement fol
-0000dac0: 6465 722e 2046 6f72 2065 7861 6d70 6c65  der. For example
-0000dad0: 3a0a 0a60 6060 7368 656c 6c0a 2269 6e70  :..```shell."inp
-0000dae0: 7574 7322 203a 205b 2266 696c 655f 312e  uts" : ["file_1.
-0000daf0: 7478 7422 5d20 2d3e 2064 6576 656c 6f70  txt"] -> develop
-0000db00: 6d65 6e74 3a3a 7465 7374 7275 6e5f 3232  ment::testrun_22
-0000db10: 3131 3038 2d31 3230 3430 342d 3764 322f  1108-120404-7d2/
-0000db20: 6669 6c65 5f31 2e74 7874 0a22 696e 7075  file_1.txt."inpu
-0000db30: 7473 2220 3a20 5b22 6465 762f 6669 6c65  ts" : ["dev/file
-0000db40: 5f31 2e74 7874 225d 202d 3e20 6465 7665  _1.txt"] -> deve
-0000db50: 6c6f 706d 656e 743a 3a74 6573 7472 756e  lopment::testrun
-0000db60: 5f32 3231 3130 382d 3132 3034 3034 2d37  _221108-120404-7
-0000db70: 6432 2f66 696c 655f 312e 7478 740a 2269  d2/file_1.txt."i
-0000db80: 6e70 7574 7322 203a 205b 222f 686f 6d65  nputs" : ["/home
-0000db90: 2f64 6576 2f66 696c 655f 312e 7478 7422  /dev/file_1.txt"
-0000dba0: 5d20 2d3e 2064 6576 656c 6f70 6d65 6e74  ] -> development
-0000dbb0: 3a3a 7465 7374 7275 6e5f 3232 3131 3038  ::testrun_221108
-0000dbc0: 2d31 3230 3430 342d 3764 322f 6669 6c65  -120404-7d2/file
-0000dbd0: 5f31 2e74 7874 0a22 696e 7075 7473 2220  _1.txt."inputs" 
-0000dbe0: 3a20 5b22 2e2e 2f64 6576 2f66 696c 655f  : ["../dev/file_
-0000dbf0: 312e 7478 7422 5d20 2d3e 2064 6576 656c  1.txt"] -> devel
-0000dc00: 6f70 6d65 6e74 3a3a 7465 7374 7275 6e5f  opment::testrun_
-0000dc10: 3232 3131 3038 2d31 3230 3430 342d 3764  221108-120404-7d
-0000dc20: 322f 6669 6c65 5f31 2e74 7874 0a22 696e  2/file_1.txt."in
-0000dc30: 7075 7473 2220 3a20 5b22 2e2e 2f2e 2e2f  puts" : ["../../
-0000dc40: 6465 762f 6669 6c65 5f31 2e74 7874 225d  dev/file_1.txt"]
-0000dc50: 202d 3e20 6465 7665 6c6f 706d 656e 743a   -> development:
-0000dc60: 3a74 6573 7472 756e 5f32 3231 3130 382d  :testrun_221108-
-0000dc70: 3132 3034 3034 2d37 6432 2f66 696c 655f  120404-7d2/file_
-0000dc80: 312e 7478 740a 6060 600a 0a54 6865 2070  1.txt.```..The p
-0000dc90: 726f 7065 7274 7920 6465 6661 756c 7420  roperty default 
-0000dca0: 6973 2060 6661 6c73 6560 2e20 5468 6973  is `false`. This
-0000dcb0: 2070 726f 7065 7274 7920 2a2a 6361 6e20   property **can 
-0000dcc0: 6f6e 6c79 2062 6520 7365 7420 6174 2074  only be set at t
-0000dcd0: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
-0000dce0: 656e 7420 6c65 7665 6c2a 2a20 616e 6420  ent level** and 
-0000dcf0: 7769 6c6c 2074 6865 7265 666f 7265 2061  will therefore a
-0000dd00: 7070 6c79 2074 6f20 616c 6c20 5461 736b  pply to all Task
-0000dd10: 2047 726f 7570 7320 616e 6420 5461 736b   Groups and Task
-0000dd20: 7320 7769 7468 696e 2061 2057 6f72 6b20  s within a Work 
-0000dd30: 5265 7175 6972 656d 656e 742e 0a0a 5768  Requirement...Wh
-0000dd40: 656e 2066 696c 6573 2061 7070 6561 7220  en files appear 
-0000dd50: 696e 2074 6865 2060 696e 7075 7473 6020  in the `inputs` 
-0000dd60: 6c69 7374 2c20 7468 6579 2061 7265 2061  list, they are a
-0000dd70: 6c73 6f20 6175 746f 6d61 7469 6361 6c6c  lso automaticall
-0000dd80: 7920 6164 6465 6420 746f 2074 6865 206c  y added to the l
-0000dd90: 6973 7420 6f66 2066 696c 6573 2072 6571  ist of files req
-0000dda0: 7569 7265 6420 6279 2074 6865 2072 656c  uired by the rel
-0000ddb0: 6576 616e 7420 5461 736b 2873 2920 6173  evant Task(s) as
-0000ddc0: 2060 5665 7269 6679 4174 5374 6172 7460   `VerifyAtStart`
-0000ddd0: 2064 6570 656e 6465 6e63 6965 732e 0a0a   dependencies...
-0000dde0: 2323 2323 2046 696c 6573 2069 6e20 7468  #### Files in th
-0000ddf0: 6520 6075 706c 6f61 6446 696c 6573 6020  e `uploadFiles` 
-0000de00: 4c69 7374 0a0a 5468 6520 6075 706c 6f61  List..The `uploa
-0000de10: 6446 696c 6573 6020 7072 6f70 6572 7479  dFiles` property
-0000de20: 2061 6c6c 6f77 7320 6d6f 7265 2066 6c65   allows more fle
-0000de30: 7869 626c 6520 636f 6e74 726f 6c20 6f76  xible control ov
-0000de40: 6572 2074 6865 2066 696c 6573 2074 6f20  er the files to 
-0000de50: 6265 2075 706c 6f61 6465 6420 6672 6f6d  be uploaded from
-0000de60: 206c 6f63 616c 2073 746f 7261 6765 2074   local storage t
-0000de70: 6f20 7468 6520 4f62 6a65 6374 2053 746f  o the Object Sto
-0000de80: 7265 2077 6865 6e20 6079 642d 7375 626d  re when `yd-subm
-0000de90: 6974 6020 6973 2072 756e 2e20 5468 6520  it` is run. The 
-0000dea0: 7072 6f70 6572 7479 2063 616e 2062 6520  property can be 
-0000deb0: 7573 6564 2061 7420 616c 6c20 576f 726b  used at all Work
-0000dec0: 2052 6571 7569 7265 6d65 6e74 206c 6576   Requirement lev
-0000ded0: 656c 732c 2066 726f 6d20 7468 6520 544f  els, from the TO
-0000dee0: 4d4c 2066 696c 6520 7468 726f 7567 6820  ML file through 
-0000def0: 746f 2069 6e64 6976 6964 7561 6c20 5461  to individual Ta
-0000df00: 736b 2073 7065 6369 6669 6361 7469 6f6e  sk specification
-0000df10: 732e 0a0a 5468 6520 7072 6f70 6572 7479  s...The property
-0000df20: 2069 7320 7375 7070 6c69 6564 2061 7320   is supplied as 
-0000df30: 6120 6c69 7374 206f 6620 6469 6374 696f  a list of dictio
-0000df40: 6e61 7279 2069 7465 6d73 2c20 6561 6368  nary items, each
-0000df50: 206f 6620 7768 6963 6820 6d75 7374 2069   of which must i
-0000df60: 6e63 6c75 6465 2074 6865 2070 726f 7065  nclude the prope
-0000df70: 7274 6965 7320 606c 6f63 616c 5061 7468  rties `localPath
-0000df80: 6020 616e 6420 6075 706c 6f61 6450 6174  ` and `uploadPat
-0000df90: 6860 2e20 0a0a 2d20 606c 6f63 616c 5061  h`. ..- `localPa
-0000dfa0: 7468 6020 7370 6563 6966 6965 7320 7468  th` specifies th
-0000dfb0: 6520 7061 7468 6e61 6d65 206f 6620 7468  e pathname of th
-0000dfc0: 6520 6669 6c65 206f 6e20 6c6f 6361 6c20  e file on local 
-0000dfd0: 7374 6f72 6167 650a 2d20 6075 706c 6f61  storage.- `uploa
-0000dfe0: 6450 6174 6860 2073 7065 6369 6669 6573  dPath` specifies
-0000dff0: 2074 6865 206e 616d 6520 616e 6420 6c6f   the name and lo
-0000e000: 6361 7469 6f6e 206f 6620 7468 6520 6669  cation of the fi
-0000e010: 6c65 2773 2064 6573 7469 6e61 7469 6f6e  le's destination
-0000e020: 2069 6e20 7468 6520 4f62 6a65 6374 2053   in the Object S
-0000e030: 746f 7265 0a0a 466f 7220 6578 616d 706c  tore..For exampl
-0000e040: 652c 2069 6e20 544f 4d4c 3a0a 6060 6074  e, in TOML:.```t
-0000e050: 6f6d 6c0a 7570 6c6f 6164 4669 6c65 7320  oml.uploadFiles 
-0000e060: 3d20 5b0a 2020 2020 7b6c 6f63 616c 5061  = [.    {localPa
-0000e070: 7468 203d 2022 6669 6c65 5f31 2e74 7874  th = "file_1.txt
-0000e080: 222c 2075 706c 6f61 6450 6174 6820 3d20  ", uploadPath = 
-0000e090: 2266 696c 655f 312e 7478 7422 7d2c 0a20  "file_1.txt"},. 
-0000e0a0: 2020 207b 6c6f 6361 6c50 6174 6820 3d20     {localPath = 
-0000e0b0: 2264 6972 5f32 2f66 696c 655f 322e 7478  "dir_2/file_2.tx
-0000e0c0: 7422 2c20 7570 6c6f 6164 5061 7468 203d  t", uploadPath =
-0000e0d0: 2022 3a3a 6669 6c65 5f32 2e74 7874 227d   "::file_2.txt"}
-0000e0e0: 2c0a 2020 2020 7b6c 6f63 616c 5061 7468  ,.    {localPath
-0000e0f0: 203d 2022 6669 6c65 5f33 2e74 7874 222c   = "file_3.txt",
-0000e100: 2075 706c 6f61 6450 6174 6820 3d20 226f   uploadPath = "o
-0000e110: 7468 6572 5f6e 616d 6573 7061 6365 3a3a  ther_namespace::
-0000e120: 6669 6c65 5f33 2e74 7874 227d 0a5d 0a60  file_3.txt"}.].`
-0000e130: 6060 0a41 6e64 2069 6e20 4a53 4f4e 2c20  ``.And in JSON, 
-0000e140: 7769 7468 2074 6865 2070 726f 7065 7274  with the propert
-0000e150: 7920 7365 7420 6174 2074 6865 2054 6173  y set at the Tas
-0000e160: 6b20 6c65 7665 6c2c 2074 6865 2073 616d  k level, the sam
-0000e170: 6520 7370 6563 6966 6963 6174 696f 6e20  e specification 
-0000e180: 776f 756c 6420 6265 3a0a 6060 606a 736f  would be:.```jso
-0000e190: 6e0a 7b0a 2020 2274 6173 6b47 726f 7570  n.{.  "taskGroup
-0000e1a0: 7322 3a20 5b0a 2020 2020 7b0a 2020 2020  s": [.    {.    
-0000e1b0: 2020 2274 6173 6b73 223a 205b 0a20 2020    "tasks": [.   
-0000e1c0: 2020 2020 207b 0a20 2020 2020 2020 2020       {.         
-0000e1d0: 2022 7570 6c6f 6164 4669 6c65 7322 3a20   "uploadFiles": 
-0000e1e0: 5b0a 2020 2020 2020 2020 2020 2020 7b22  [.            {"
-0000e1f0: 6c6f 6361 6c50 6174 6822 3a20 2266 696c  localPath": "fil
-0000e200: 655f 312e 7478 7422 2c20 2275 706c 6f61  e_1.txt", "uploa
-0000e210: 6450 6174 6822 3a20 2266 696c 655f 312e  dPath": "file_1.
-0000e220: 7478 7422 7d2c 0a20 2020 2020 2020 2020  txt"},.         
-0000e230: 2020 207b 226c 6f63 616c 5061 7468 223a     {"localPath":
-0000e240: 2022 6469 725f 322f 6669 6c65 5f32 2e74   "dir_2/file_2.t
-0000e250: 7874 222c 2022 7570 6c6f 6164 5061 7468  xt", "uploadPath
-0000e260: 223a 2022 3a3a 6669 6c65 5f32 2e74 7874  ": "::file_2.txt
-0000e270: 227d 2c0a 2020 2020 2020 2020 2020 2020  "},.            
-0000e280: 7b22 6c6f 6361 6c50 6174 6822 3a20 2266  {"localPath": "f
-0000e290: 696c 655f 332e 7478 7422 2c20 2275 706c  ile_3.txt", "upl
-0000e2a0: 6f61 6450 6174 6822 3a20 226f 7468 6572  oadPath": "other
-0000e2b0: 5f6e 616d 6573 7061 6365 3a3a 6669 6c65  _namespace::file
-0000e2c0: 5f33 2e74 7874 227d 0a20 2020 2020 2020  _3.txt"}.       
-0000e2d0: 2020 205d 0a20 2020 2020 2020 207d 0a20     ].        }. 
-0000e2e0: 2020 2020 205d 0a20 2020 207d 0a20 205d       ].    }.  ]
-0000e2f0: 0a7d 0a60 6060 0a0a 5768 656e 2072 756e  .}.```..When run
-0000e300: 6e69 6e67 2074 6865 2050 7974 686f 6e20  ning the Python 
-0000e310: 4578 616d 706c 6573 2063 6f6d 6d61 6e64  Examples command
-0000e320: 7320 6f6e 202a 2a57 696e 646f 7773 2a2a  s on **Windows**
-0000e330: 2068 6f73 7473 2c20 6e6f 7465 2074 6861   hosts, note tha
-0000e340: 7420 6569 7468 6572 2057 696e 646f 7773  t either Windows
-0000e350: 206f 7220 556e 6978 2064 6972 6563 746f   or Unix directo
-0000e360: 7279 2073 6570 6172 6174 6f72 7320 6361  ry separators ca
-0000e370: 6e20 6265 2075 7365 6420 666f 7220 7468  n be used for th
-0000e380: 6520 606c 6f63 616c 5061 7468 6020 7061  e `localPath` pa
-0000e390: 7468 6e61 6d65 7320 286f 7220 7468 6520  thnames (or the 
-0000e3a0: 7061 7468 6e61 6d65 7320 696e 2060 696e  pathnames in `in
-0000e3b0: 7075 7473 6029 2c20 6275 7420 7468 6520  puts`), but the 
-0000e3c0: 556e 6978 2063 6f6e 7665 6e74 696f 6e20  Unix convention 
-0000e3d0: 6d75 7374 2062 6520 7573 6564 2066 6f72  must be used for
-0000e3e0: 2074 6865 2060 7570 6c6f 6164 5061 7468   the `uploadPath
-0000e3f0: 6020 6e61 6d65 732c 2065 2e67 2e3a 0a0a  ` names, e.g.:..
-0000e400: 6060 6074 6f6d 6c0a 7570 6c6f 6164 4669  ```toml.uploadFi
-0000e410: 6c65 7320 3d20 5b0a 2020 2020 7b6c 6f63  les = [.    {loc
-0000e420: 616c 5061 7468 203d 2022 6469 725f 325c  alPath = "dir_2\
-0000e430: 5c66 696c 655f 322e 7478 7422 2c20 7570  \file_2.txt", up
-0000e440: 6c6f 6164 5061 7468 203d 2022 3a3a 6d79  loadPath = "::my
-0000e450: 5f64 6972 6563 746f 7279 2f66 696c 655f  _directory/file_
-0000e460: 322e 7478 7422 7d2c 0a5d 0a60 6060 0a0a  2.txt"},.].```..
-0000e470: 5468 6520 6075 706c 6f61 6446 696c 6573  The `uploadFiles
-0000e480: 6020 7072 6f70 6572 7479 2063 616e 2061  ` property can a
-0000e490: 6c73 6f20 6265 2073 6574 2061 7420 7468  lso be set at th
-0000e4a0: 6520 576f 726b 2052 6571 7569 7265 6d65  e Work Requireme
-0000e4b0: 6e74 2061 6e64 2054 6173 6b20 4772 6f75  nt and Task Grou
-0000e4c0: 7020 6c65 7665 6c73 2c20 616e 6420 7072  p levels, and pr
-0000e4d0: 6f70 6572 7479 2069 6e68 6572 6974 616e  operty inheritan
-0000e4e0: 6365 206f 7065 7261 7465 7320 6173 206e  ce operates as n
-0000e4f0: 6f72 6d61 6c2e 0a0a 466f 7220 6075 706c  ormal...For `upl
-0000e500: 6f61 6450 6174 6860 2c20 7468 6520 7361  oadPath`, the sa
-0000e510: 6d65 2060 3a3a 6020 6e61 6d69 6e67 2063  me `::` naming c
-0000e520: 6f6e 7665 6e74 696f 6e20 6973 2061 7661  onvention is ava
-0000e530: 696c 6162 6c65 2061 7320 6973 2075 7365  ilable as is use
-0000e540: 6420 696e 2074 6865 2060 7665 7269 6679  d in the `verify
-0000e550: 4174 5374 6172 7460 2c20 6076 6572 6966  AtStart`, `verif
-0000e560: 7957 6169 7460 2061 6e64 2060 696e 7075  yWait` and `inpu
-0000e570: 7473 4f70 7469 6f6e 616c 6020 7072 6f70  tsOptional` prop
-0000e580: 6572 7469 6573 2064 6973 6375 7373 6564  erties discussed
-0000e590: 2062 656c 6f77 3a0a 0a2d 2049 6620 603a   below:..- If `:
-0000e5a0: 3a60 2069 7320 6e6f 7420 7573 6564 2c20  :` is not used, 
-0000e5b0: 7468 656e 2074 6865 2066 696c 6520 6973  then the file is
-0000e5c0: 2075 706c 6f61 6465 6420 7265 6c61 7469   uploaded relati
-0000e5d0: 7665 2074 6f20 7468 6520 6375 7272 656e  ve to the curren
-0000e5e0: 7420 6e61 6d65 7370 6163 6520 696e 2061  t namespace in a
-0000e5f0: 2064 6972 6563 746f 7279 206e 616d 6564   directory named
-0000e600: 2061 6674 6572 2074 6865 206e 616d 6520   after the name 
-0000e610: 6f66 2074 6865 2057 6f72 6b20 5265 7175  of the Work Requ
-0000e620: 6972 656d 656e 740a 2d20 4966 2060 3a3a  irement.- If `::
-0000e630: 6020 6973 2075 7365 6420 6174 2074 6865  ` is used at the
-0000e640: 2073 7461 7274 206f 6620 7468 6520 6075   start of the `u
-0000e650: 706c 6f61 6450 6174 6860 2c20 7468 6520  ploadPath`, the 
-0000e660: 6669 6c65 2069 7320 7570 6c6f 6164 6564  file is uploaded
-0000e670: 2072 656c 6174 6976 6520 746f 2074 6865   relative to the
-0000e680: 2072 6f6f 7420 6f66 2074 6865 2063 7572   root of the cur
-0000e690: 7265 6e74 206e 616d 6573 7061 6365 0a2d  rent namespace.-
-0000e6a0: 2049 6620 603c 6e61 6d65 7370 6163 653e   If `<namespace>
-0000e6b0: 3a3a 6020 6973 2075 7365 6420 6174 2074  ::` is used at t
-0000e6c0: 6865 2073 7461 7274 206f 6620 6075 706c  he start of `upl
-0000e6d0: 6f61 6450 6174 6860 2c20 7468 6520 6669  oadPath`, the fi
-0000e6e0: 6c65 2069 7320 7570 6c6f 6164 6564 2072  le is uploaded r
-0000e6f0: 656c 6174 6976 6520 746f 2074 6865 2072  elative to the r
-0000e700: 6f6f 7420 6f66 2060 3c6e 616d 6573 7061  oot of `<namespa
-0000e710: 6365 3e60 0a0a 4561 6368 2066 696c 6520  ce>`..Each file 
-0000e720: 7370 6563 6966 6965 6420 696e 2074 6865  specified in the
-0000e730: 2060 7570 6c6f 6164 4669 6c65 7360 206c   `uploadFiles` l
-0000e740: 6973 7473 2077 696c 6c20 6f6e 6c79 2062  ists will only b
-0000e750: 6520 7570 6c6f 6164 6564 206f 6e63 6520  e uploaded once 
-0000e760: 746f 2065 6163 6820 756e 6971 7565 2075  to each unique u
-0000e770: 706c 6f61 6420 6c6f 6361 7469 6f6e 2066  pload location f
-0000e780: 6f72 2061 6e79 2067 6976 656e 2069 6e76  or any given inv
-0000e790: 6f63 6174 696f 6e20 6f66 2060 7964 2d73  ocation of `yd-s
-0000e7a0: 7562 6d69 7460 2e0a 0a49 6620 6120 6669  ubmit`...If a fi
-0000e7b0: 6c65 2069 6e20 7468 6520 6075 706c 6f61  le in the `uploa
-0000e7c0: 6446 696c 6573 6020 6c69 7374 2069 7320  dFiles` list is 
-0000e7d0: 7265 7175 6972 6564 2062 7920 6120 5461  required by a Ta
-0000e7e0: 736b 2c20 6974 206d 7573 7420 7365 7061  sk, it must sepa
-0000e7f0: 7261 7465 6c79 2062 6520 6164 6465 6420  rately be added 
-0000e800: 746f 2074 6865 2060 7665 7269 6679 4174  to the `verifyAt
-0000e810: 5374 6172 7460 206f 7220 6076 6572 6966  Start` or `verif
-0000e820: 7957 6169 7460 206c 6973 7473 2064 6973  yWait` lists dis
-0000e830: 6375 7373 6564 2062 656c 6f77 2e20 5468  cussed below. Th
-0000e840: 6973 2069 7320 6e6f 7420 646f 6e65 2061  is is not done a
-0000e850: 7574 6f6d 6174 6963 616c 6c79 2e20 4e6f  utomatically. No
-0000e860: 7465 2061 6c73 6f20 7468 6174 2074 6865  te also that the
-0000e870: 2060 666c 6174 7465 6e55 706c 6f61 6450   `flattenUploadP
-0000e880: 6174 6873 6020 7072 6f70 6572 7479 2069  aths` property i
-0000e890: 7320 6967 6e6f 7265 6420 666f 7220 6669  s ignored for fi
-0000e8a0: 6c65 7320 696e 2074 6865 2060 7570 6c6f  les in the `uplo
-0000e8b0: 6164 4669 6c65 7360 206c 6973 742e 0a0a  adFiles` list...
-0000e8c0: 2323 2323 2055 7369 6e67 2057 696c 6463  #### Using Wildc
-0000e8d0: 6172 6473 2069 6e20 7468 6520 6075 706c  ards in the `upl
-0000e8e0: 6f61 6446 696c 6573 6020 4c69 7374 0a0a  oadFiles` List..
-0000e8f0: 4669 6c65 2061 6e64 2064 6972 6563 746f  File and directo
-0000e900: 7279 206e 616d 6520 7769 6c64 6361 7264  ry name wildcard
-0000e910: 7320 6361 6e20 6265 2075 7365 6420 696e  s can be used in
-0000e920: 2060 6c6f 6361 6c50 6174 6860 2070 726f   `localPath` pro
-0000e930: 7065 7274 6965 732e 2049 6620 7769 6c64  perties. If wild
-0000e940: 6361 7264 7320 6172 6520 7573 6564 2c20  cards are used, 
-0000e950: 7468 656e 2074 6865 2060 7570 6c6f 6164  then the `upload
-0000e960: 5061 7468 6020 7072 6f70 6572 7479 206d  Path` property m
-0000e970: 7573 7420 656e 6420 7769 7468 2061 2060  ust end with a `
-0000e980: 2a60 2c20 7768 6963 6820 7769 6c6c 2062  *`, which will b
-0000e990: 6520 7265 706c 6163 6564 2077 6974 6820  e replaced with 
-0000e9a0: 7468 6520 6e61 6d65 206f 6620 6561 6368  the name of each
-0000e9b0: 2066 696c 6520 7468 6174 206d 6174 6368   file that match
-0000e9c0: 6573 2074 6865 2077 696c 6463 6172 642c  es the wildcard,
-0000e9d0: 2065 2e67 2e3a 0a0a 6060 6074 6f6d 6c0a   e.g.:..```toml.
-0000e9e0: 7570 6c6f 6164 4669 6c65 7320 3d20 5b0a  uploadFiles = [.
-0000e9f0: 2020 2020 7b6c 6f63 616c 5061 7468 203d      {localPath =
-0000ea00: 2022 2a2e 7368 222c 2075 706c 6f61 6450   "*.sh", uploadP
-0000ea10: 6174 6820 3d20 2273 6372 6970 7473 2f2a  ath = "scripts/*
-0000ea20: 227d 2c0a 2020 2020 7b6c 6f63 616c 5061  "},.    {localPa
-0000ea30: 7468 203d 2022 7465 7874 2f2a 2e74 7874  th = "text/*.txt
-0000ea40: 222c 2075 706c 6f61 6450 6174 6820 3d20  ", uploadPath = 
-0000ea50: 223a 3a74 6f70 2d6c 6576 656c 2f2a 227d  "::top-level/*"}
-0000ea60: 2c0a 2020 2020 7b6c 6f63 616c 5061 7468  ,.    {localPath
-0000ea70: 203d 2022 7372 632f 2a2e 7079 222c 2075   = "src/*.py", u
-0000ea80: 706c 6f61 6450 6174 6820 3d20 226f 7468  ploadPath = "oth
-0000ea90: 6572 2d6e 616d 6573 7061 6365 3a3a 2a22  er-namespace::*"
-0000eaa0: 7d2c 0a5d 0a60 6060 0a0a 5468 6520 602d  },.].```..The `-
-0000eab0: 2d64 7279 2d72 756e 6020 2860 2d44 6029  -dry-run` (`-D`)
-0000eac0: 206f 7074 696f 6e20 6361 6e20 6265 2075   option can be u
-0000ead0: 7365 6420 7769 7468 2060 7964 2d73 7562  sed with `yd-sub
-0000eae0: 6d69 7460 2074 6f20 7072 696e 7420 6f75  mit` to print ou
-0000eaf0: 7420 7468 6520 6669 6c65 7320 7468 6174  t the files that
-0000eb00: 2077 6f75 6c64 2062 6520 7570 6c6f 6164   would be upload
-0000eb10: 6564 2c20 616e 6420 7468 6569 7220 7570  ed, and their up
-0000eb20: 6c6f 6164 206c 6f63 6174 696f 6e73 2e20  load locations. 
-0000eb30: 0a0a 2323 2320 4669 6c65 2044 6570 656e  ..### File Depen
-0000eb40: 6465 6e63 6965 7320 5573 696e 6720 6076  dencies Using `v
-0000eb50: 6572 6966 7941 7453 7461 7274 6020 616e  erifyAtStart` an
-0000eb60: 6420 6076 6572 6966 7957 6169 7460 0a0a  d `verifyWait`..
-0000eb70: 4974 2773 2070 6f73 7369 626c 6520 746f  It's possible to
-0000eb80: 206d 616b 6520 5461 736b 7320 6465 7065   make Tasks depe
-0000eb90: 6e64 656e 7420 6f6e 2074 6865 2070 7265  ndent on the pre
-0000eba0: 7365 6e63 6520 6f66 2066 696c 6573 2069  sence of files i
-0000ebb0: 6e20 7468 6520 4f62 6a65 6374 2053 746f  n the Object Sto
-0000ebc0: 7265 2062 7920 7573 696e 6720 7468 6520  re by using the 
-0000ebd0: 6076 6572 6966 7941 7453 7461 7274 6020  `verifyAtStart` 
-0000ebe0: 616e 6420 6076 6572 6966 7957 6169 7460  and `verifyWait`
-0000ebf0: 206c 6973 7473 2e20 5468 6573 6520 6669   lists. These fi
-0000ec00: 6c65 7320 6172 6520 6e6f 7420 6175 746f  les are not auto
-0000ec10: 6d61 7469 6361 6c6c 7920 7570 6c6f 6164  matically upload
-0000ec20: 6564 2077 6865 6e20 7573 696e 6720 6079  ed when using `y
-0000ec30: 642d 7375 626d 6974 6020 736f 2061 7265  d-submit` so are
-0000ec40: 2075 706c 6f61 6465 6420 6d61 6e75 616c   uploaded manual
-0000ec50: 6c79 2028 652e 672e 2c20 6279 2075 7369  ly (e.g., by usi
-0000ec60: 6e67 2060 7964 2d75 706c 6f61 6460 292c  ng `yd-upload`),
-0000ec70: 2075 706c 6f61 6465 6420 7573 696e 6720   uploaded using 
-0000ec80: 7468 6520 6075 706c 6f61 6446 696c 6573  the `uploadFiles
-0000ec90: 6020 7072 6f70 6572 7479 2c20 6f72 2061  ` property, or a
-0000eca0: 7265 2063 7265 6174 6564 2061 7320 6120  re created as a 
-0000ecb0: 7265 7375 6c74 206f 6620 7468 6520 6578  result of the ex
-0000ecc0: 6563 7574 696f 6e20 6f66 206f 7468 6572  ecution of other
-0000ecd0: 2054 6173 6b73 2e0a 0a4e 6f74 6520 7468   Tasks...Note th
-0000ece0: 6174 2061 2067 6976 656e 2066 696c 6520  at a given file 
-0000ecf0: 6361 6e20 6f6e 6c79 2061 7070 6561 7220  can only appear 
-0000ed00: 696e 202a 6f6e 652a 206f 6620 7468 6520  in *one* of the 
-0000ed10: 6069 6e70 7574 7360 2c20 6076 6572 6966  `inputs`, `verif
-0000ed20: 7941 7453 7461 7274 6020 6f72 2060 7665  yAtStart` or `ve
-0000ed30: 7269 6679 5761 6974 6020 6c69 7374 732e  rifyWait` lists.
-0000ed40: 0a0a 5461 736b 7320 7769 7468 2060 7665  ..Tasks with `ve
-0000ed50: 7269 6679 4174 5374 6172 7460 2064 6570  rifyAtStart` dep
-0000ed60: 656e 6465 6e63 6965 7320 7769 6c6c 2066  endencies will f
-0000ed70: 6169 6c20 696d 6d65 6469 6174 656c 7920  ail immediately 
-0000ed80: 6966 2074 6865 2072 6571 7569 7265 6420  if the required 
-0000ed90: 6669 6c65 7320 6172 6520 6e6f 7420 7072  files are not pr
-0000eda0: 6573 656e 7420 7768 656e 2074 6865 2054  esent when the T
-0000edb0: 6173 6b20 6973 2073 7562 6d69 7474 6564  ask is submitted
-0000edc0: 2e20 5461 736b 7320 7769 7468 2060 7665  . Tasks with `ve
-0000edd0: 7269 6679 5761 6974 6020 6465 7065 6e64  rifyWait` depend
-0000ede0: 656e 6369 6573 2077 696c 6c20 6e6f 7420  encies will not 
-0000edf0: 6265 636f 6d65 2060 5245 4144 5960 2074  become `READY` t
-0000ee00: 6f20 6265 2073 6368 6564 756c 6564 2074  o be scheduled t
-0000ee10: 6f20 576f 726b 6572 7320 756e 7469 6c20  o Workers until 
-0000ee20: 7468 6520 6465 7065 6e64 656e 6369 6573  the dependencies
-0000ee30: 2061 7265 2073 6174 6973 6669 6564 2e0a   are satisfied..
-0000ee40: 0a57 6865 6e20 7370 6563 6966 7969 6e67  .When specifying
-0000ee50: 2066 696c 6573 2069 6e20 7468 6520 6076   files in the `v
-0000ee60: 6572 6966 7941 7453 7461 7274 6020 616e  erifyAtStart` an
-0000ee70: 6420 6076 6572 6966 7957 6169 7460 206c  d `verifyWait` l
-0000ee80: 6973 7473 2c20 6173 2077 6974 6820 7468  ists, as with th
-0000ee90: 6520 6075 706c 6f61 6450 6174 6860 2070  e `uploadPath` p
-0000eea0: 726f 7065 7274 7920 6469 7363 7573 7365  roperty discusse
-0000eeb0: 6420 6162 6f76 652c 2074 6865 2066 696c  d above, the fil
-0000eec0: 6520 6c6f 6361 7469 6f6e 7320 6361 6e20  e locations can 
-0000eed0: 6265 2028 3129 2072 656c 6174 6976 6520  be (1) relative 
-0000eee0: 746f 2074 6865 2057 6f72 6b20 5265 7175  to the Work Requ
-0000eef0: 6972 656d 656e 7420 6e61 6d65 2069 6e20  irement name in 
-0000ef00: 7468 6520 6375 7272 656e 7420 6e61 6d65  the current name
-0000ef10: 7370 6163 6520 2874 6865 2064 6566 6175  space (the defau
-0000ef20: 6c74 292c 2028 3229 2072 656c 6174 6976  lt), (2) relativ
-0000ef30: 6520 746f 2074 6865 2072 6f6f 7420 6f66  e to the root of
-0000ef40: 2074 6865 2063 7572 7265 6e74 206e 616d   the current nam
-0000ef50: 6573 7061 6365 2c20 6f72 2028 3329 2072  espace, or (3) r
-0000ef60: 656c 6174 6976 6520 746f 2074 6865 2072  elative to the r
-0000ef70: 6f6f 7420 6f66 2061 2064 6966 6665 7265  oot of a differe
-0000ef80: 6e74 206e 616d 6573 7061 6365 2069 6e20  nt namespace in 
-0000ef90: 7468 6520 7573 6572 2773 2041 6363 6f75  the user's Accou
-0000efa0: 6e74 2e0a 0a31 2e20 466f 7220 6669 6c65  nt...1. For file
-0000efb0: 7320 7265 6c61 7469 7665 2074 6f20 7468  s relative to th
-0000efc0: 6520 576f 726b 2052 6571 7569 7265 6d65  e Work Requireme
-0000efd0: 6e74 206e 616d 6520 696e 2074 6865 2063  nt name in the c
-0000efe0: 7572 7265 6e74 206e 616d 6573 7061 6365  urrent namespace
-0000eff0: 2c20 6a75 7374 2075 7365 2074 6865 2066  , just use the f
-0000f000: 696c 6520 7061 7468 2c20 652e 672e 0a60  ile path, e.g..`
-0000f010: 6060 7368 656c 6c0a 2276 6572 6966 7957  ``shell."verifyW
-0000f020: 6169 7422 3a20 5b22 6669 6c65 5f31 2e74  ait": ["file_1.t
-0000f030: 7874 225d 202d 3e20 6465 7665 6c6f 706d  xt"] -> developm
-0000f040: 656e 743a 7465 7374 7275 6e5f 3232 3131  ent:testrun_2211
-0000f050: 3038 2d31 3230 3430 342d 3764 322f 6669  08-120404-7d2/fi
-0000f060: 6c65 5f31 2e74 7874 0a60 6060 0a0a 322e  le_1.txt.```..2.
-0000f070: 2046 6f72 2066 696c 6573 2072 656c 6174   For files relat
-0000f080: 6976 6520 746f 2074 6865 2072 6f6f 7420  ive to the root 
-0000f090: 6f66 2074 6865 2063 7572 7265 6e74 206e  of the current n
-0000f0a0: 616d 6573 7061 6365 2c20 7072 6566 6978  amespace, prefix
-0000f0b0: 2074 6865 2066 696c 6520 7061 7468 2077   the file path w
-0000f0c0: 6974 6820 603a 3a60 2c20 652e 672e 0a60  ith `::`, e.g..`
-0000f0d0: 6060 7368 656c 6c0a 2276 6572 6966 7957  ``shell."verifyW
-0000f0e0: 6169 7422 3a20 5b22 3a3a 6669 6c65 5f31  ait": ["::file_1
-0000f0f0: 2e74 7874 225d 202d 3e20 6465 7665 6c6f  .txt"] -> develo
-0000f100: 706d 656e 743a 6669 6c65 5f31 2e74 7874  pment:file_1.txt
-0000f110: 0a60 6060 0a0a 332e 2046 6f72 2066 696c  .```..3. For fil
-0000f120: 6573 2072 656c 6174 6976 6520 746f 2074  es relative to t
-0000f130: 6865 2072 6f6f 7420 6f66 2061 2064 6966  he root of a dif
-0000f140: 6665 7265 6e74 206e 616d 6573 7061 6365  ferent namespace
-0000f150: 2c20 7072 6566 6978 2074 6865 2066 696c  , prefix the fil
-0000f160: 6520 7061 7468 2077 6974 6820 7468 6520  e path with the 
-0000f170: 6e61 6d65 7370 6163 6520 6e61 6d65 2061  namespace name a
-0000f180: 6e64 2060 3a3a 602c 2065 2e67 2e0a 6060  nd `::`, e.g..``
-0000f190: 6073 6865 6c6c 0a22 7665 7269 6679 5761  `shell."verifyWa
-0000f1a0: 6974 223a 205b 226f 7468 6572 5f6e 616d  it": ["other_nam
-0000f1b0: 6573 7061 6365 3a3a 6669 6c65 5f31 2e74  espace::file_1.t
-0000f1c0: 7874 225d 202d 3e20 6f74 6865 725f 6e61  xt"] -> other_na
-0000f1d0: 6d65 7370 6163 653a 6669 6c65 5f31 2e74  mespace:file_1.t
-0000f1e0: 7874 0a60 6060 0a0a 5468 6520 7573 6520  xt.```..The use 
-0000f1f0: 6f66 2074 6865 2074 6872 6565 2064 6966  of the three dif
-0000f200: 6665 7265 6e74 2066 6f72 6d73 2063 616e  ferent forms can
-0000f210: 2062 6520 6d69 7865 6420 7769 7468 696e   be mixed within
-0000f220: 2061 2073 696e 676c 6520 6c69 7374 2c20   a single list, 
-0000f230: 652e 672e 3a0a 6060 6073 6865 6c6c 0a22  e.g.:.```shell."
-0000f240: 7665 7269 6679 4174 5374 6172 7422 3a20  verifyAtStart": 
-0000f250: 5b22 6669 6c65 5f31 2e74 7874 222c 2022  ["file_1.txt", "
-0000f260: 3a3a 6469 725f 322f 6669 6c65 5f32 2e74  ::dir_2/file_2.t
-0000f270: 7874 222c 2022 6f74 6865 725f 6e61 6d65  xt", "other_name
-0000f280: 7370 6163 653a 3a64 6972 5f33 2f66 696c  space::dir_3/fil
-0000f290: 655f 332e 7478 7422 5d0a 6060 600a 0a23  e_3.txt"].```..#
-0000f2a0: 2323 2046 696c 6573 2044 6f77 6e6c 6f61  ## Files Downloa
-0000f2b0: 6465 6420 5573 696e 6720 6069 6e70 7574  ded Using `input
-0000f2c0: 734f 7074 696f 6e61 6c60 0a0a 5468 6520  sOptional`..The 
-0000f2d0: 6069 6e70 7574 734f 7074 696f 6e61 6c60  `inputsOptional`
-0000f2e0: 2070 726f 7065 7274 7920 776f 726b 7320   property works 
-0000f2f0: 696e 2061 2073 696d 696c 6172 2066 6173  in a similar fas
-0000f300: 6869 6f6e 2074 6f20 7468 6520 6076 6572  hion to the `ver
-0000f310: 6966 792a 6020 7072 6f70 6572 7469 6573  ify*` properties
-0000f320: 2061 626f 7665 2c20 6275 7420 7468 6520   above, but the 
-0000f330: 6669 6c65 7320 7370 6563 6966 6965 6420  files specified 
-0000f340: 696e 2074 6869 7320 6c69 7374 2061 7265  in this list are
-0000f350: 206f 7074 696f 6e61 6c2e 2054 6869 7320   optional. This 
-0000f360: 7072 6f70 6572 7479 2061 6c73 6f20 616c  property also al
-0000f370: 6c6f 7773 2066 6f72 2074 6865 2075 7365  lows for the use
-0000f380: 206f 6620 7769 6c64 6361 7264 7320 602a   of wildcards `*
-0000f390: 6020 616e 6420 602a 2a60 2074 6f20 636f  ` and `**` to co
-0000f3a0: 6c6c 6563 7420 6669 6c65 7320 7573 696e  llect files usin
-0000f3b0: 6720 7769 6c64 6361 7264 2070 6174 6873  g wildcard paths
-0000f3c0: 2e20 5468 6520 2a2a 616e 742a 2a20 636f  . The **ant** co
-0000f3d0: 6e76 656e 7469 6f6e 7320 6172 6520 7573  nventions are us
-0000f3e0: 6564 2066 6f72 2074 6865 7365 2077 696c  ed for these wil
-0000f3f0: 6463 6172 6473 2e0a 0a23 2323 2046 696c  dcards...### Fil
-0000f400: 6573 2044 6f77 6e6c 6f61 6465 6420 746f  es Downloaded to
-0000f410: 2061 204e 6f64 6520 666f 7220 7573 6520   a Node for use 
-0000f420: 696e 2054 6173 6b20 4578 6563 7574 696f  in Task Executio
-0000f430: 6e0a 0a57 6865 6e20 6120 5461 736b 2069  n..When a Task i
-0000f440: 7320 6578 6563 7574 6564 2062 7920 6120  s executed by a 
-0000f450: 576f 726b 6572 206f 6e20 6120 4e6f 6465  Worker on a Node
-0000f460: 2c20 6974 7320 7265 7175 6972 6564 2066  , its required f
-0000f470: 696c 6573 2061 7265 2064 6f77 6e6c 6f61  iles are downloa
-0000f480: 6465 6420 6672 6f6d 2074 6865 204f 626a  ded from the Obj
-0000f490: 6563 7420 5374 6f72 6520 7072 696f 7220  ect Store prior 
-0000f4a0: 746f 2054 6173 6b20 6578 6563 7574 696f  to Task executio
-0000f4b0: 6e2e 2041 6e79 2066 696c 6520 6c69 7374  n. Any file list
-0000f4c0: 6564 2069 6e20 7468 6520 6069 6e70 7574  ed in the `input
-0000f4d0: 7360 2066 6f72 2061 2054 6173 6b20 6973  s` for a Task is
-0000f4e0: 2061 7373 756d 6564 2074 6f20 6265 2072   assumed to be r
-0000f4f0: 6571 7569 7265 642c 2061 6c6f 6e67 2077  equired, along w
-0000f500: 6974 6820 616e 7920 6164 6469 7469 6f6e  ith any addition
-0000f510: 616c 2066 696c 6573 2073 7065 6369 6669  al files specifi
-0000f520: 6564 2069 6e20 7468 6520 6076 6572 6966  ed in the `verif
-0000f530: 7941 7453 7461 7274 6020 616e 6420 6076  yAtStart` and `v
-0000f540: 6572 6966 7957 6169 7460 206c 6973 7473  erifyWait` lists
-0000f550: 2e20 4669 6c65 7320 7370 6563 6966 6965  . Files specifie
-0000f560: 6420 7573 696e 6720 7468 6520 6069 6e70  d using the `inp
-0000f570: 7574 734f 7074 696f 6e61 6c60 2070 726f  utsOptional` pro
-0000f580: 7065 7274 7920 6172 6520 6f70 7469 6f6e  perty are option
-0000f590: 616c 6c79 2064 6f77 6e6c 6f61 6465 6420  ally downloaded 
-0000f5a0: 6672 6f6d 2074 6865 204f 626a 6563 7420  from the Object 
-0000f5b0: 5374 6f72 652e 2028 4e6f 7465 2074 6861  Store. (Note tha
-0000f5c0: 7420 6120 6669 6c65 2073 686f 756c 6420  t a file should 
-0000f5d0: 6f6e 6c79 2061 7070 6561 7220 696e 206f  only appear in o
-0000f5e0: 6e65 206f 6620 7468 6573 6520 666f 7572  ne of these four
-0000f5f0: 206c 6973 7473 2c20 6f74 6865 7277 6973   lists, otherwis
-0000f600: 6520 6079 642d 7375 626d 6974 6020 7769  e `yd-submit` wi
-0000f610: 6c6c 2072 6574 7572 6e20 616e 2065 7272  ll return an err
-0000f620: 6f72 2e29 0a0a 5768 656e 2061 2054 6173  or.)..When a Tas
-0000f630: 6b20 6973 2073 7461 7274 6564 2062 7920  k is started by 
-0000f640: 7468 6520 4167 656e 742c 2069 7473 2077  the Agent, its w
-0000f650: 6f72 6b69 6e67 2064 6972 6563 746f 7279  orking directory
-0000f660: 2068 6173 2061 2070 6174 7465 726e 2073   has a pattern s
-0000f670: 6f6d 6574 6869 6e67 206c 696b 653a 0a0a  omething like:..
-0000f680: 602f 7661 722f 6f70 742f 7965 6c6c 6f77  `/var/opt/yellow
-0000f690: 646f 672f 7964 2d61 6765 6e74 2d34 2f64  dog/yd-agent-4/d
-0000f6a0: 6174 612f 776f 726b 6572 732f 312f 7964  ata/workers/1/yd
-0000f6b0: 6964 5f74 6173 6b5f 4430 4430 4430 5f36  id_task_D0D0D0_6
-0000f6c0: 3866 3565 3562 652d 6463 3933 2d34 3965  8f5e5be-dc93-49e
-0000f6d0: 622d 6138 3234 2d31 6663 6462 3532 6639  b-a824-1fcdb52f9
-0000f6e0: 3139 355f 315f 3160 0a0a 2860 7964 6964  195_1_1`..(`ydid
-0000f6f0: 5f74 6173 6b5f 4430 4430 4430 5f36 3866  _task_D0D0D0_68f
-0000f700: 3565 3562 652d 6463 3933 2d34 3965 622d  5e5be-dc93-49eb-
-0000f710: 6138 3234 2d31 6663 6462 3532 6639 3139  a824-1fcdb52f919
-0000f720: 355f 315f 3160 2069 7320 616e 2065 7068  5_1_1` is an eph
-0000f730: 656d 6572 616c 2064 6972 6563 746f 7279  emeral directory
-0000f740: 2074 6861 7420 6973 2072 656d 6f76 6564   that is removed
-0000f750: 2061 6674 6572 2074 6865 2054 6173 6b20   after the Task 
-0000f760: 6669 6e69 7368 6573 2061 6e64 2061 6e79  finishes and any
-0000f770: 206f 7574 7075 7473 2068 6176 6520 6265   outputs have be
-0000f780: 656e 2075 706c 6f61 6465 642e 290a 0a46  en uploaded.)..F
-0000f790: 696c 6573 2074 6861 7420 6172 6520 646f  iles that are do
-0000f7a0: 776e 6c6f 6164 6564 2062 7920 7468 6520  wnloaded by the 
-0000f7b0: 4167 656e 7420 7072 696f 7220 746f 2054  Agent prior to T
-0000f7c0: 6173 6b20 6578 6563 7574 696f 6e20 6172  ask execution ar
-0000f7d0: 6520 6c6f 6361 7465 6420 6173 2066 6f6c  e located as fol
-0000f7e0: 6c6f 7773 3a0a 0a31 2e20 4966 2074 6865  lows:..1. If the
-0000f7f0: 2060 666c 6174 7465 6e49 6e70 7574 5061   `flattenInputPa
-0000f800: 7468 7360 2070 726f 7065 7274 7920 6973  ths` property is
-0000f810: 2073 6574 2074 6f20 7468 6520 6465 6661   set to the defa
-0000f820: 756c 7420 6f66 2060 6661 6c73 6560 2066  ult of `false` f
-0000f830: 6f72 2074 6865 2054 6173 6b2c 2074 6865  or the Task, the
-0000f840: 2064 6f77 6e6c 6f61 6465 6420 6f62 6a65   downloaded obje
-0000f850: 6374 7320 6172 6520 706c 6163 6564 2069  cts are placed i
-0000f860: 6e20 7375 6264 6972 6563 746f 7269 6573  n subdirectories
-0000f870: 2074 6861 7420 6d69 7272 6f72 2074 686f   that mirror tho
-0000f880: 7365 2069 6e20 7468 6520 4f62 6a65 6374  se in the Object
-0000f890: 2053 746f 7265 2c20 696e 636c 7564 696e   Store, includin
-0000f8a0: 6720 7468 6520 576f 726b 2052 6571 7569  g the Work Requi
-0000f8b0: 7265 6d65 6e74 206e 616d 652c 2073 6974  rement name, sit
-0000f8c0: 7561 7465 6420 6265 6e65 6174 6820 7468  uated beneath th
-0000f8d0: 6520 776f 726b 696e 6720 6469 7265 6374  e working direct
-0000f8e0: 6f72 792e 0a0a 0a32 2e20 4966 2074 6865  ory....2. If the
-0000f8f0: 2060 666c 6174 7465 6e49 6e70 7574 5061   `flattenInputPa
-0000f900: 7468 7360 2070 726f 7065 7274 7920 6973  ths` property is
-0000f910: 2073 6574 2074 6f20 6074 7275 6560 2066   set to `true` f
-0000f920: 6f72 2074 6865 2054 6173 6b2c 2074 6865  or the Task, the
-0000f930: 2064 6f77 6e6c 6f61 6465 6420 6f62 6a65   downloaded obje
-0000f940: 6374 7320 6172 6520 616c 6c20 706c 6163  cts are all plac
-0000f950: 6564 2064 6972 6563 746c 7920 696e 2072  ed directly in r
-0000f960: 6f6f 7420 6f66 2074 6865 2054 6173 6b27  oot of the Task'
-0000f970: 7320 776f 726b 696e 6720 6469 7265 6374  s working direct
-0000f980: 6f72 792e 0a0a 466f 7220 6578 616d 706c  ory...For exampl
-0000f990: 653a 0a0a 6060 6073 6865 6c6c 0a49 6620  e:..```shell.If 
-0000f9a0: 7468 6520 7265 7175 6972 6564 206f 626a  the required obj
-0000f9b0: 6563 7420 6973 3a20 6465 7665 6c6f 706d  ect is: developm
-0000f9c0: 656e 743a 3a74 6573 7472 756e 5f32 3231  ent::testrun_221
-0000f9d0: 3130 382d 3132 3034 3034 2d37 6432 2f64  108-120404-7d2/d
-0000f9e0: 6576 2f66 696c 655f 312e 7478 740a 0a74  ev/file_1.txt..t
-0000f9f0: 6865 6e2c 2069 6620 666c 6174 7465 6e49  hen, if flattenI
-0000fa00: 6e70 7574 5061 7468 7320 6973 2066 616c  nputPaths is fal
-0000fa10: 7365 2c20 7468 6520 6669 6c65 2077 696c  se, the file wil
-0000fa20: 6c20 6265 2066 6f75 6e64 2061 743a 0a20  l be found at:. 
-0000fa30: 2d3e 203c 776f 726b 696e 675f 6469 7265  -> <working_dire
-0000fa40: 6374 6f72 793e 2f74 6573 7472 756e 5f32  ctory>/testrun_2
-0000fa50: 3231 3130 382d 3132 3034 3034 2d37 6432  21108-120404-7d2
-0000fa60: 2f64 6576 2f66 696c 655f 312e 7478 740a  /dev/file_1.txt.
-0000fa70: 200a 656c 7365 2c20 6966 2066 6c61 7474   .else, if flatt
-0000fa80: 656e 496e 7075 7450 6174 6873 2069 7320  enInputPaths is 
-0000fa90: 7472 7565 2c20 7468 6520 6669 6c65 2077  true, the file w
-0000faa0: 696c 6c20 6265 2066 6f75 6e64 2061 743a  ill be found at:
-0000fab0: 0a20 2d3e 203c 776f 726b 696e 675f 6469  . -> <working_di
-0000fac0: 7265 6374 6f72 793e 2f66 696c 655f 312e  rectory>/file_1.
-0000fad0: 7478 7420 0a20 0a77 6865 7265 203c 776f  txt . .where <wo
-0000fae0: 726b 696e 675f 6469 7265 6374 6f72 793e  rking_directory>
-0000faf0: 2069 733a 0a20 202f 7661 722f 6f70 742f   is:.  /var/opt/
-0000fb00: 7965 6c6c 6f77 646f 672f 7964 2d61 6765  yellowdog/yd-age
-0000fb10: 6e74 2d34 2f64 6174 612f 776f 726b 6572  nt-4/data/worker
-0000fb20: 732f 312f 7964 6964 5f74 6173 6b5f 4430  s/1/ydid_task_D0
-0000fb30: 4430 4430 5f36 3866 3565 3562 652d 6463  D0D0_68f5e5be-dc
-0000fb40: 3933 2d34 3965 622d 6138 3234 2d31 6663  93-49eb-a824-1fc
-0000fb50: 6462 3532 6639 3139 355f 315f 312f 0a60  db52f9195_1_1/.`
-0000fb60: 6060 0a0a 4e6f 7465 2074 6861 7420 7468  ``..Note that th
-0000fb70: 6520 576f 726b 2052 6571 7569 7265 6d65  e Work Requireme
-0000fb80: 6e74 206e 616d 6520 2865 2e67 2e2c 2060  nt name (e.g., `
-0000fb90: 7465 7374 7275 6e5f 3232 3131 3038 2d31  testrun_221108-1
-0000fba0: 3230 3430 342d 3764 3260 2920 6973 2061  20404-7d2`) is a
-0000fbb0: 7661 696c 6162 6c65 2076 6961 2074 6865  vailable via the
-0000fbc0: 2076 6172 6961 626c 6520 7375 6273 7469   variable substi
-0000fbd0: 7475 7469 6f6e 2060 7772 5f6e 616d 6560  tution `wr_name`
-0000fbe0: 2c20 736f 2074 6869 7320 636f 756c 6420  , so this could 
-0000fbf0: 6265 2073 7570 706c 6965 6420 746f 2074  be supplied to t
-0000fc00: 6865 2054 6173 6b20 746f 2068 656c 7020  he Task to help 
-0000fc10: 6974 206c 6f63 6174 6520 6974 7320 646f  it locate its do
-0000fc20: 776e 6c6f 6164 6564 2066 696c 6573 2e20  wnloaded files. 
-0000fc30: 466f 7220 6578 616d 706c 652c 2069 6e20  For example, in 
-0000fc40: 7468 6520 6077 6f72 6b52 6571 7569 7265  the `workRequire
-0000fc50: 6d65 6e74 6020 7365 6374 696f 6e20 6f66  ment` section of
-0000fc60: 2074 6865 2060 636f 6e66 6967 2e74 6f6d   the `config.tom
-0000fc70: 6c60 2066 696c 652c 2049 2063 6f75 6c64  l` file, I could
-0000fc80: 2073 7065 6369 6679 3a0a 0a60 6060 746f   specify:..```to
-0000fc90: 6d6c 0a65 6e76 6972 6f6e 6d65 6e74 203d  ml.environment =
-0000fca0: 207b 5752 5f44 4952 4543 544f 5259 203d   {WR_DIRECTORY =
-0000fcb0: 2022 7b7b 7772 5f6e 616d 657d 7d22 7d0a   "{{wr_name}}"}.
-0000fcc0: 6060 600a 0a54 6865 2057 6f72 6b20 5265  ```..The Work Re
-0000fcd0: 7175 6972 656d 656e 7420 6e61 6d65 2077  quirement name w
-0000fce0: 6f75 6c64 2074 6865 6e20 6265 2061 7661  ould then be ava
-0000fcf0: 696c 6162 6c65 2074 6f20 7468 6520 5461  ilable to the Ta
-0000fd00: 736b 2069 6e20 7468 6520 656e 7669 726f  sk in the enviro
-0000fd10: 6e6d 656e 7420 7661 7269 6162 6c65 2060  nment variable `
-0000fd20: 2457 525f 4449 5245 4354 4f52 5960 2e0a  $WR_DIRECTORY`..
-0000fd30: 0a23 2323 2046 696c 6573 2055 706c 6f61  .### Files Uploa
-0000fd40: 6465 6420 6672 6f6d 2061 204e 6f64 6520  ded from a Node 
-0000fd50: 746f 2074 6865 204f 626a 6563 7420 5374  to the Object St
-0000fd60: 6f72 6520 6166 7465 7220 5461 736b 2045  ore after Task E
-0000fd70: 7865 6375 7469 6f6e 0a0a 4166 7465 7220  xecution..After 
-0000fd80: 5461 736b 2063 6f6d 706c 6574 696f 6e2c  Task completion,
-0000fd90: 2074 6865 2041 6765 6e74 2077 696c 6c20   the Agent will 
-0000fda0: 7570 6c6f 6164 2073 7065 6369 6669 6564  upload specified
-0000fdb0: 206f 7574 7075 7420 6669 6c65 7320 746f   output files to
-0000fdc0: 2074 6865 204f 626a 6563 7420 5374 6f72   the Object Stor
-0000fdd0: 652e 2054 6865 2066 696c 6573 2074 6f20  e. The files to 
-0000fde0: 6265 2075 706c 6f61 6465 6420 6172 6520  be uploaded are 
-0000fdf0: 7468 6f73 6520 6c69 7374 6564 2069 6e20  those listed in 
-0000fe00: 7468 6520 606f 7574 7075 7473 6020 616e  the `outputs` an
-0000fe10: 6420 606f 7574 7075 7473 5265 7175 6972  d `outputsRequir
-0000fe20: 6564 6020 7072 6f70 6572 7469 6573 2066  ed` properties f
-0000fe30: 6f72 2074 6865 2054 6173 6b2e 0a0a 496e  or the Task...In
-0000fe40: 2061 6464 6974 696f 6e2c 2074 6865 2063   addition, the c
-0000fe50: 6f6e 736f 6c65 206f 7574 7075 7420 6f66  onsole output of
-0000fe60: 2074 6865 2054 6173 6b20 6973 2063 6170   the Task is cap
-0000fe70: 7475 7265 6420 696e 2061 2066 696c 6520  tured in a file 
-0000fe80: 6361 6c6c 6564 2060 7461 736b 6f75 7470  called `taskoutp
-0000fe90: 7574 2e74 7874 6020 696e 2074 6865 2072  ut.txt` in the r
-0000fea0: 6f6f 7420 6f66 2074 6865 2054 6173 6b27  oot of the Task'
-0000feb0: 7320 776f 726b 696e 6720 6469 7265 6374  s working direct
-0000fec0: 6f72 792e 2057 6865 7468 6572 2074 6865  ory. Whether the
-0000fed0: 2060 7461 736b 6f75 7470 7574 2e74 7874   `taskoutput.txt
-0000fee0: 6020 6669 6c65 2069 7320 7570 6c6f 6164  ` file is upload
-0000fef0: 6564 2074 6f20 7468 6520 4f62 6a65 6374  ed to the Object
-0000ff00: 2053 746f 7265 2069 7320 6465 7465 726d   Store is determ
-0000ff10: 696e 6564 2062 7920 7468 6520 6063 6170  ined by the `cap
-0000ff20: 7475 7265 5461 736b 4f75 7470 7574 6020  tureTaskOutput` 
-0000ff30: 7072 6f70 6572 7479 2066 6f72 2074 6865  property for the
-0000ff40: 2054 6173 6b2c 2061 6e64 2074 6869 7320   Task, and this 
-0000ff50: 6973 2073 6574 2074 6f20 2774 7275 6527  is set to 'true'
-0000ff60: 2062 7920 6465 6661 756c 742e 0a0a 4966   by default...If
-0000ff70: 2054 6173 6b20 6f75 7470 7574 7320 6172   Task outputs ar
-0000ff80: 6520 6372 6561 7465 6420 696e 2073 7562  e created in sub
-0000ff90: 6469 7265 6374 6f72 6965 7320 6265 6c6f  directories belo
-0000ffa0: 7720 7468 6520 5461 736b 2773 2077 6f72  w the Task's wor
-0000ffb0: 6b69 6e67 2064 6972 6563 746f 7279 2c20  king directory, 
-0000ffc0: 696e 636c 7564 6520 7468 6520 6469 7265  include the dire
-0000ffd0: 6374 6f72 6965 7320 666f 7220 6669 6c65  ctories for file
-0000ffe0: 7320 696e 2074 6865 2060 6f75 7470 7574  s in the `output
-0000fff0: 7360 2070 726f 7065 7274 792e 2045 2e67  s` property. E.g
-00010000: 2e2c 2069 6620 6120 5461 736b 2063 7265  ., if a Task cre
-00010010: 6174 6573 2066 696c 6573 2060 7265 7375  ates files `resu
-00010020: 6c74 732f 6f70 656e 666f 616d 2e74 6172  lts/openfoam.tar
-00010030: 2e67 7a60 2061 6e64 2060 7265 7375 6c74  .gz` and `result
-00010040: 732f 6f70 656e 666f 616d 2e6c 6f67 602c  s/openfoam.log`,
-00010050: 2074 6865 6e20 7370 6563 6966 7920 7468   then specify th
-00010060: 6573 6520 666f 7220 7570 6c6f 6164 2069  ese for upload i
-00010070: 6e20 7468 6520 606f 7574 7075 7473 6020  n the `outputs` 
-00010080: 7072 6f70 6572 7479 2061 7320 666f 6c6c  property as foll
-00010090: 6f77 733a 0a0a 6022 6f75 7470 7574 7322  ows:..`"outputs"
-000100a0: 3a20 5b22 7265 7375 6c74 732f 6f70 656e  : ["results/open
-000100b0: 666f 616d 2e74 6172 2e67 7a22 2c20 2272  foam.tar.gz", "r
-000100c0: 6573 756c 7473 2f6f 7065 6e66 6f61 6d2e  esults/openfoam.
-000100d0: 6c6f 6722 5d60 0a0a 5768 656e 206f 7574  log"]`..When out
-000100e0: 7075 7420 6669 6c65 7320 6172 6520 7570  put files are up
-000100f0: 6c6f 6164 6564 2074 6f20 7468 6520 4f62  loaded to the Ob
-00010100: 6a65 6374 2053 746f 7265 2c20 7468 6579  ject Store, they
-00010110: 2061 7265 2070 6c61 6365 6420 696e 2061   are placed in a
-00010120: 2054 6173 6b20 4772 6f75 7020 616e 6420   Task Group and 
-00010130: 5461 736b 2073 7065 6369 6669 6320 6469  Task specific di
-00010140: 7265 6374 6f72 792e 2053 6f2c 2069 6620  rectory. So, if 
-00010150: 7468 6520 4e61 6d65 7370 6163 6520 6973  the Namespace is
-00010160: 2060 6465 7665 6c6f 706d 656e 7460 2c20   `development`, 
-00010170: 7468 6520 576f 726b 2052 6571 7569 7265  the Work Require
-00010180: 6d65 6e74 2069 7320 6074 6573 7472 756e  ment is `testrun
-00010190: 5f32 3231 3130 382d 3132 3034 3034 2d37  _221108-120404-7
-000101a0: 6432 602c 2074 6865 2054 6173 6b20 4772  d2`, the Task Gr
-000101b0: 6f75 7020 6973 2060 7461 736b 5f67 726f  oup is `task_gro
-000101c0: 7570 5f31 6020 616e 6420 7468 6520 5461  up_1` and the Ta
-000101d0: 736b 2069 7320 6074 6173 6b5f 3160 2c20  sk is `task_1`, 
-000101e0: 7468 656e 2074 6865 2066 696c 6573 2061  then the files a
-000101f0: 626f 7665 2077 6f75 6c64 2062 6520 7570  bove would be up
-00010200: 6c6f 6164 6564 2074 6f20 7468 6520 4f62  loaded to the Ob
-00010210: 6a65 6374 2053 746f 7265 2061 7320 666f  ject Store as fo
-00010220: 6c6c 6f77 733a 0a0a 6060 6073 6865 6c6c  llows:..```shell
-00010230: 0a64 6576 656c 6f70 6d65 6e74 3a3a 7465  .development::te
-00010240: 7374 7275 6e5f 3232 3131 3038 2d31 3230  strun_221108-120
-00010250: 3430 342d 3764 322f 7461 736b 5f67 726f  404-7d2/task_gro
-00010260: 7570 5f31 2f74 6173 6b5f 312f 7265 7375  up_1/task_1/resu
-00010270: 6c74 732f 6f70 656e 666f 616d 2e74 6172  lts/openfoam.tar
-00010280: 2e67 7a0a 6465 7665 6c6f 706d 656e 743a  .gz.development:
-00010290: 3a74 6573 7472 756e 5f32 3231 3130 382d  :testrun_221108-
-000102a0: 3132 3034 3034 2d37 6432 2f74 6173 6b5f  120404-7d2/task_
-000102b0: 6772 6f75 705f 312f 7461 736b 5f31 2f72  group_1/task_1/r
-000102c0: 6573 756c 7473 2f6f 7065 6e66 6f61 6d2e  esults/openfoam.
-000102d0: 6c6f 670a 6465 7665 6c6f 706d 656e 743a  log.development:
-000102e0: 3a74 6573 7472 756e 5f32 3231 3130 382d  :testrun_221108-
-000102f0: 3132 3034 3034 2d37 6432 2f74 6173 6b5f  120404-7d2/task_
-00010300: 6772 6f75 705f 312f 7461 736b 5f31 2f74  group_1/task_1/t
-00010310: 6173 6b6f 7574 7075 742e 7478 740a 6060  askoutput.txt.``
-00010320: 600a 0a54 6865 202a 2a60 6f75 7470 7574  `..The **`output
-00010330: 7352 6571 7569 7265 6460 2a2a 2070 726f  sRequired`** pro
-00010340: 7065 7274 7920 6361 6e20 6265 2075 7365  perty can be use
-00010350: 6420 696e 7374 6561 6420 6f66 2028 6f72  d instead of (or
-00010360: 2069 6e20 6164 6469 7469 6f6e 2074 6f29   in addition to)
-00010370: 2074 6865 2060 6f75 7470 7574 7360 2070   the `outputs` p
-00010380: 726f 7065 7274 792c 2069 6620 7468 6520  roperty, if the 
-00010390: 6f75 7470 7574 2066 696c 6528 7329 202a  output file(s) *
-000103a0: 2a6d 7573 742a 2a20 6265 2061 7661 696c  *must** be avail
-000103b0: 6162 6c65 2066 6f72 2075 706c 6f61 6420  able for upload 
-000103c0: 746f 2074 6865 204f 626a 6563 7420 5374  to the Object St
-000103d0: 6f72 6520 6174 2074 6865 2063 6f6e 636c  ore at the concl
-000103e0: 7573 696f 6e20 6f66 2074 6865 2054 6173  usion of the Tas
-000103f0: 6b20 6f72 2074 6865 2054 6173 6b20 7769  k or the Task wi
-00010400: 6c6c 2062 6520 6d61 726b 6564 2061 7320  ll be marked as 
-00010410: 6046 6169 6c65 6460 2c20 652e 672e 3a0a  `Failed`, e.g.:.
-00010420: 0a60 226f 7574 7075 7473 5265 7175 6972  .`"outputsRequir
-00010430: 6564 223a 205b 2272 6573 756c 7473 2f70  ed": ["results/p
-00010440: 726f 6365 7373 5f6f 7574 7075 742e 7478  rocess_output.tx
-00010450: 7422 5d60 0a0a 2323 2320 4669 6c65 7320  t"]`..### Files 
-00010460: 446f 776e 6c6f 6164 6564 2066 726f 6d20  Downloaded from 
-00010470: 7468 6520 4f62 6a65 6374 2053 746f 7265  the Object Store
-00010480: 2074 6f20 4c6f 6361 6c20 5374 6f72 6167   to Local Storag
-00010490: 650a 0a54 6865 2060 7964 2d64 6f77 6e6c  e..The `yd-downl
-000104a0: 6f61 6460 2063 6f6d 6d61 6e64 2077 696c  oad` command wil
-000104b0: 6c20 646f 776e 6c6f 6164 2061 6c6c 206f  l download all o
-000104c0: 626a 6563 7473 2066 726f 6d20 7468 6520  bjects from the 
-000104d0: 4f62 6a65 6374 2053 746f 7265 2074 6f20  Object Store to 
-000104e0: 6120 6c6f 6361 6c20 6469 7265 6374 6f72  a local director
-000104f0: 792c 206f 6e20 6120 7065 7220 576f 726b  y, on a per Work
-00010500: 2052 6571 7569 7265 6d65 6e74 2062 6173   Requirement bas
-00010510: 6973 2028 696e 636c 7564 696e 6720 616e  is (including an
-00010520: 7920 6669 6c65 7320 7468 6174 2068 6176  y files that hav
-00010530: 6520 6265 656e 2075 706c 6f61 6465 6429  e been uploaded)
-00010540: 2e20 4120 6c6f 6361 6c20 6469 7265 6374  . A local direct
-00010550: 6f72 7920 6973 2063 7265 6174 6564 2077  ory is created w
-00010560: 6974 6820 7468 6520 7361 6d65 206e 616d  ith the same nam
-00010570: 6520 6173 2074 6865 204e 616d 6573 7061  e as the Namespa
-00010580: 6365 2061 6e64 2063 6f6e 7461 696e 696e  ce and containin
-00010590: 6720 7468 6520 576f 726b 2052 6571 7569  g the Work Requi
-000105a0: 7265 6d65 6e74 2064 6972 6563 746f 7269  rement directori
-000105b0: 6573 2e0a 0a55 7365 2074 6865 2060 2d2d  es...Use the `--
-000105c0: 696e 7465 7261 6374 6976 6560 206f 7074  interactive` opt
-000105d0: 696f 6e20 7769 7468 2060 7964 2d64 6f77  ion with `yd-dow
-000105e0: 6e6c 6f61 6460 2074 6f20 7365 6c65 6374  nload` to select
-000105f0: 2077 6869 6368 2057 6f72 6b20 5265 7175   which Work Requ
-00010600: 6972 656d 656e 7428 7329 2074 6f20 646f  irement(s) to do
-00010610: 776e 6c6f 6164 2e0a 0a46 6f72 2074 6865  wnload...For the
-00010620: 2065 7861 6d70 6c65 2061 626f 7665 2c20   example above, 
-00010630: 6079 642d 646f 776e 6c6f 6164 6020 776f  `yd-download` wo
-00010640: 756c 6420 6372 6561 7465 2061 2064 6972  uld create a dir
-00010650: 6563 746f 7279 2063 616c 6c65 6420 6064  ectory called `d
-00010660: 6576 656c 6f70 6d65 6e74 6020 696e 2074  evelopment` in t
-00010670: 6865 2063 7572 7265 6e74 2077 6f72 6b69  he current worki
-00010680: 6e67 2064 6972 6563 746f 7279 2c20 636f  ng directory, co
-00010690: 6e74 6169 6e69 6e67 2073 6f6d 6574 6869  ntaining somethi
-000106a0: 6e67 206c 696b 653a 0a0a 6060 6073 6865  ng like:..```she
-000106b0: 6c6c 0a64 6576 656c 6f70 6d65 6e74 0ae2  ll.development..
-000106c0: 9494 e294 80e2 9480 2074 6573 7472 756e  ........ testrun
-000106d0: 5f32 3231 3130 382d 3132 3034 3034 2d37  _221108-120404-7
-000106e0: 6432 0a20 2020 20e2 949c e294 80e2 9480  d2.    .........
-000106f0: 2062 6173 685f 7363 7269 7074 2e73 680a   bash_script.sh.
-00010700: 2020 2020 e294 9ce2 9480 e294 8020 6669      ......... fi
-00010710: 6c65 5f31 2e74 7874 0a20 2020 20e2 9494  le_1.txt.    ...
-00010720: e294 80e2 9480 2074 6173 6b5f 6772 6f75  ...... task_grou
-00010730: 705f 310a 2020 2020 2020 2020 e294 94e2  p_1.        ....
-00010740: 9480 e294 8020 7461 736b 5f31 0a20 2020  ..... task_1.   
-00010750: 2020 2020 2020 2020 20e2 949c e294 80e2           .......
-00010760: 9480 2072 6573 756c 7473 0a20 2020 2020  .. results.     
-00010770: 2020 2020 2020 20e2 9482 c2a0 c2a0 20e2         ....... .
-00010780: 949c e294 80e2 9480 206f 7065 6e66 6f61  ........ openfoa
-00010790: 6d2e 6c6f 670a 2020 2020 2020 2020 2020  m.log.          
-000107a0: 2020 e294 82c2 a0c2 a020 e294 94e2 9480    ....... ......
-000107b0: e294 8020 6f70 656e 666f 616d 2e74 6172  ... openfoam.tar
-000107c0: 2e67 7a0a 2020 2020 2020 2020 2020 2020  .gz.            
-000107d0: e294 94e2 9480 e294 8020 7461 736b 6f75  ......... taskou
-000107e0: 7470 7574 2e74 7874 0a60 6060 0a0a 4e6f  tput.txt.```..No
-000107f0: 7465 2074 6861 7420 6576 6572 7974 6869  te that everythi
-00010800: 6e67 2077 6974 6869 6e20 7468 6520 606e  ng within the `n
-00010810: 616d 6573 7061 6365 3a3a 776f 726b 2d72  amespace::work-r
-00010820: 6571 7569 7265 6d65 6e74 6020 6469 7265  equirement` dire
-00010830: 6374 6f72 7920 696e 2074 6865 204f 626a  ctory in the Obj
-00010840: 6563 7420 5374 6f72 6520 6973 2064 6f77  ect Store is dow
-00010850: 6e6c 6f61 6465 642c 2069 6e63 6c75 6469  nloaded, includi
-00010860: 6e67 2061 6e79 2066 696c 6573 2074 6861  ng any files tha
-00010870: 7420 7765 7265 2073 7065 6369 6669 6564  t were specified
-00010880: 2069 6e20 6069 6e70 7574 7360 2061 6e64   in `inputs` and
-00010890: 2075 706c 6f61 6465 6420 6173 2070 6172   uploaded as par
-000108a0: 7420 6f66 2074 6865 2057 6f72 6b20 5265  t of the Work Re
-000108b0: 7175 6972 656d 656e 7420 7375 626d 6973  quirement submis
-000108c0: 7369 6f6e 2e20 4d75 6c74 6970 6c65 2054  sion. Multiple T
-000108d0: 6173 6b20 4772 6f75 7073 2c20 616e 6420  ask Groups, and 
-000108e0: 6d75 6c74 6970 6c65 2054 6173 6b73 2077  multiple Tasks w
-000108f0: 696c 6c20 616c 6c20 6170 7065 6172 2069  ill all appear i
-00010900: 6e20 7468 6520 6469 7265 6374 6f72 7920  n the directory 
-00010910: 7374 7275 6374 7572 652e 0a0a 4966 2074  structure...If t
-00010920: 6865 2060 6465 7665 6c6f 706d 656e 7460  he `development`
-00010930: 2064 6972 6563 746f 7279 2061 6c72 6561   directory alrea
-00010940: 6479 2065 7869 7374 732c 2060 7964 2d64  dy exists, `yd-d
-00010950: 6f77 6e6c 6f61 6460 2077 696c 6c20 7472  ownload` will tr
-00010960: 7920 6064 6576 656c 6f70 6d65 6e74 2e30  y `development.0
-00010970: 3160 2c20 6574 632e 2c20 746f 2061 766f  1`, etc., to avo
-00010980: 6964 206f 7665 7277 7269 7469 6e67 2070  id overwriting p
-00010990: 7265 7669 6f75 7320 646f 776e 6c6f 6164  revious download
-000109a0: 732e 0a0a 2323 2054 6173 6b20 4578 6563  s...## Task Exec
-000109b0: 7574 696f 6e20 436f 6e74 6578 740a 0a54  ution Context..T
-000109c0: 6869 7320 7365 6374 696f 6e20 6469 7363  his section disc
-000109d0: 7573 7365 7320 7468 6520 636f 6e74 6578  usses the contex
-000109e0: 7420 7769 7468 696e 2077 6869 6368 2061  t within which a
-000109f0: 2054 6173 6b20 6f70 6572 6174 6573 2077   Task operates w
-00010a00: 6865 6e20 6974 2773 2065 7865 6375 7465  hen it's execute
-00010a10: 6420 6279 2061 2057 6f72 6b65 7220 6f6e  d by a Worker on
-00010a20: 2061 206e 6f64 652e 2049 7420 6170 706c   a node. It appl
-00010a30: 6965 7320 7370 6563 6966 6963 616c 6c79  ies specifically
-00010a40: 2074 6f20 7468 6520 5965 6c6c 6f77 446f   to the YellowDo
-00010a50: 6720 4167 656e 7420 7275 6e6e 696e 6720  g Agent running 
-00010a60: 6f6e 2061 204c 696e 7578 206e 6f64 652c  on a Linux node,
-00010a70: 2061 6e64 2063 6f6e 6669 6775 7265 6420   and configured 
-00010a80: 7573 696e 6720 7468 6520 6465 6661 756c  using the defaul
-00010a90: 7420 7573 6572 6e61 6d65 2c20 6469 7265  t username, dire
-00010aa0: 6374 6f72 6965 732c 2065 7463 2e20 436f  ctories, etc. Co
-00010ab0: 6e66 6967 7572 6174 696f 6e73 2063 616e  nfigurations can
-00010ac0: 2076 6172 792e 0a0a 2323 2320 5461 736b   vary...### Task
-00010ad0: 2045 7865 6375 7469 6f6e 2053 7465 7073   Execution Steps
-00010ae0: 0a0a 5768 656e 2061 2054 6173 6b20 6973  ..When a Task is
-00010af0: 2061 6c6c 6f63 6174 6564 2074 6f20 6120   allocated to a 
-00010b00: 576f 726b 6572 206f 6e20 6120 6e6f 6465  Worker on a node
-00010b10: 2062 7920 7468 6520 5965 6c6c 6f77 446f   by the YellowDo
-00010b20: 6720 5363 6865 6475 6c65 722c 2074 6865  g Scheduler, the
-00010b30: 2066 6f6c 6c6f 7769 6e67 2073 7465 7073   following steps
-00010b40: 2061 7265 2066 6f6c 6c6f 7765 643a 0a0a   are followed:..
-00010b50: 312e 2054 6865 2041 6765 6e74 2072 756e  1. The Agent run
-00010b60: 6e69 6e67 206f 6e20 7468 6520 6e6f 6465  ning on the node
-00010b70: 2064 6f77 6e6c 6f61 6473 2074 6865 2054   downloads the T
-00010b80: 6173 6b27 7320 7072 6f70 6572 7469 6573  ask's properties
-00010b90: 3a20 6974 7320 6074 6173 6b54 7970 6560  : its `taskType`
-00010ba0: 2c20 2060 6172 6775 6d65 6e74 7360 2c20  ,  `arguments`, 
-00010bb0: 6065 6e76 6972 6f6e 6d65 6e74 602c 2060  `environment`, `
-00010bc0: 7461 736b 6461 7461 602c 2061 6e64 2028  taskdata`, and (
-00010bd0: 6672 6f6d 2074 6865 204f 626a 6563 7420  from the Object 
-00010be0: 5374 6f72 6529 2061 6e79 2066 696c 6573  Store) any files
-00010bf0: 2069 6e20 7468 6520 6069 6e70 7574 7360   in the `inputs`
-00010c00: 206c 6973 7420 616e 6420 616e 7920 6176   list and any av
-00010c10: 6169 6c61 626c 6520 6669 6c65 7320 696e  ailable files in
-00010c20: 2074 6865 2060 696e 7075 7473 4f70 7469   the `inputsOpti
-00010c30: 6f6e 616c 6020 6c69 7374 2e0a 322e 2054  onal` list..2. T
-00010c40: 6865 7365 2066 696c 6573 2061 7265 2070  hese files are p
-00010c50: 6c61 6365 6420 696e 2061 6e20 6570 6865  laced in an ephe
-00010c60: 6d65 7261 6c20 6469 7265 6374 6f72 7920  meral directory 
-00010c70: 6372 6561 7465 6420 666f 7220 7468 6973  created for this
-00010c80: 2054 6173 6b27 7320 6578 6563 7574 696f   Task's executio
-00010c90: 6e2c 2061 6e64 2069 6e74 6f20 7768 6963  n, and into whic
-00010ca0: 6820 616e 7920 6f75 7470 7574 2066 696c  h any output fil
-00010cb0: 6573 2061 7265 2061 6c73 6f20 706c 6163  es are also plac
-00010cc0: 6564 2062 7920 6465 6661 756c 742e 0a32  ed by default..2
-00010cd0: 2e20 5468 6520 4167 656e 7420 7275 6e73  . The Agent runs
-00010ce0: 2074 6865 2063 6f6d 6d61 6e64 2073 7065   the command spe
-00010cf0: 6369 6669 6564 2066 6f72 2074 6865 2060  cified for the `
-00010d00: 7461 736b 5479 7065 6020 696e 2074 6865  taskType` in the
-00010d10: 2041 6765 6e74 2773 2060 6170 706c 6963   Agent's `applic
-00010d20: 6174 696f 6e2e 7961 6d6c 6020 636f 6e66  ation.yaml` conf
-00010d30: 6967 7572 6174 696f 6e20 6669 6c65 2e20  iguration file. 
-00010d40: 5468 6973 2064 6f6e 6520 6173 2061 2073  This done as a s
-00010d50: 696d 706c 6520 6065 7865 6360 206f 6620  imple `exec` of 
-00010d60: 6120 7375 6270 726f 6365 7373 2e0a 332e  a subprocess..3.
-00010d70: 2057 6865 6e20 7468 6520 5461 736b 2063   When the Task c
-00010d80: 6f6e 636c 7564 6573 2c20 7468 6520 4167  oncludes, the Ag
-00010d90: 656e 7420 7573 6573 2074 6865 2065 7869  ent uses the exi
-00010da0: 7420 636f 6465 206f 6620 7468 6520 7375  t code of the su
-00010db0: 6270 726f 6365 7373 2074 6f20 7265 706f  bprocess to repo
-00010dc0: 7274 2073 7563 6365 7373 2028 7a65 726f  rt success (zero
-00010dd0: 2920 6f72 2066 6169 6c75 7265 2028 6e6f  ) or failure (no
-00010de0: 6e2d 7a65 726f 292e 0a34 2e20 5468 6520  n-zero)..4. The 
-00010df0: 4167 656e 7420 7468 656e 2067 6174 6865  Agent then gathe
-00010e00: 7273 2061 6e79 2066 696c 6573 2069 6e20  rs any files in 
-00010e10: 7468 6520 606f 7574 7075 7473 6020 616e  the `outputs` an
-00010e20: 6420 606f 7574 7075 7473 5265 7175 6972  d `outputsRequir
-00010e30: 6564 6020 6c69 7374 7320 616e 6420 7570  ed` lists and up
-00010e40: 6c6f 6164 7320 7468 656d 2074 6f20 7468  loads them to th
-00010e50: 6520 4f62 6a65 6374 2053 746f 7265 2e20  e Object Store. 
-00010e60: 4966 2061 2066 696c 6520 696e 2074 6865  If a file in the
-00010e70: 2060 6f75 7470 7574 7352 6571 7569 7265   `outputsRequire
-00010e80: 6460 206c 6973 7420 6973 206e 6f74 2066  d` list is not f
-00010e90: 6f75 6e64 2c20 7468 6520 5461 736b 2077  ound, the Task w
-00010ea0: 696c 6c20 6265 2072 6570 6f72 7465 6420  ill be reported 
-00010eb0: 6173 2066 6169 6c65 642e 2054 6865 2041  as failed. The A
-00010ec0: 6765 6e74 2077 696c 6c20 616c 736f 206f  gent will also o
-00010ed0: 7074 696f 6e61 6c6c 7920 7570 6c6f 6164  ptionally upload
-00010ee0: 2074 6865 2063 6f6e 736f 6c65 206f 7574   the console out
-00010ef0: 7075 7420 2869 6e63 6c75 6469 6e67 2062  put (including b
-00010f00: 6f74 6820 6073 7464 6f75 7460 2061 6e64  oth `stdout` and
-00010f10: 2060 7374 6465 7272 6029 206f 6620 7468   `stderr`) of th
-00010f20: 6520 5461 736b 2c20 636f 6e74 6169 6e65  e Task, containe
-00010f30: 6420 696e 2074 6865 2060 7461 736b 6f75  d in the `taskou
-00010f40: 7470 7574 2e74 7874 6020 6669 6c65 2e0a  tput.txt` file..
-00010f50: 352e 2054 6865 2065 7068 656d 6572 616c  5. The ephemeral
-00010f60: 2054 6173 6b20 6469 7265 6374 6f72 7920   Task directory 
-00010f70: 6973 2074 6865 6e20 6465 6c65 7465 642e  is then deleted.
-00010f80: 0a0a 4e6f 7465 2074 6861 7420 6966 2061  ..Note that if a
-00010f90: 2054 6173 6b20 6973 2061 626f 7274 6564   Task is aborted
-00010fa0: 2064 7572 696e 6720 6578 6563 7574 696f   during executio
-00010fb0: 6e2c 2074 6865 2054 6173 6b27 7320 7375  n, the Task's su
-00010fc0: 6270 726f 6365 7373 2069 7320 7365 6e74  bprocess is sent
-00010fd0: 2061 2060 5349 4749 4e54 602c 2061 6c6c   a `SIGINT`, all
-00010fe0: 6f77 696e 6720 7468 6520 5461 736b 2061  owing the Task a
-00010ff0: 6e20 6f70 706f 7274 756e 6974 7920 746f  n opportunity to
-00011000: 2074 6572 6d69 6e61 7465 2061 6e79 2063   terminate any c
-00011010: 6869 6c64 2070 726f 6365 7373 6573 206f  hild processes o
-00011020: 7220 6f74 6865 7220 7265 736f 7572 6365  r other resource
-00011030: 7320 2865 2e67 2e2c 2063 6f6e 7461 696e  s (e.g., contain
-00011040: 6572 7329 2074 6861 7420 6d61 7920 6861  ers) that may ha
-00011050: 7665 2062 6565 6e20 7374 6172 7465 6420  ve been started 
-00011060: 6173 2070 6172 7420 6f66 2054 6173 6b20  as part of Task 
-00011070: 6578 6563 7574 696f 6e2e 0a0a 4f6e 6365  execution...Once
-00011080: 2074 6865 2073 7465 7073 2061 626f 7665   the steps above
-00011090: 2068 6176 6520 6265 656e 2063 6f6d 706c   have been compl
-000110a0: 6574 6564 2c20 7468 6520 576f 726b 6572  eted, the Worker
-000110b0: 2069 7320 7265 6164 7920 746f 2061 6363   is ready to acc
-000110c0: 6570 7420 6974 7320 6e65 7874 2054 6173  ept its next Tas
-000110d0: 6b20 6672 6f6d 2074 6865 2059 656c 6c6f  k from the Yello
-000110e0: 7744 6f67 2073 6368 6564 756c 6572 2e0a  wDog scheduler..
-000110f0: 0a4e 6f74 6520 7468 6174 2069 6620 7468  .Note that if th
-00011100: 6520 4167 656e 7420 6f6e 2061 206e 6f64  e Agent on a nod
-00011110: 6520 6861 7320 6d75 6c74 6970 6c65 2057  e has multiple W
-00011120: 6f72 6b65 7273 2c20 7468 656e 2054 6173  orkers, then Tas
-00011130: 6b73 2061 7265 2065 7865 6375 7465 6420  ks are executed 
-00011140: 696e 2070 6172 616c 6c65 6c20 6f6e 2074  in parallel on t
-00011150: 6865 206e 6f64 6520 616e 6420 6361 6e20  he node and can 
-00011160: 7374 6172 7420 616e 6420 7374 6f70 2069  start and stop i
-00011170: 6e64 6570 656e 6465 6e74 6c79 2e0a 0a23  ndependently...#
-00011180: 2323 2054 6865 2055 7365 7220 616e 6420  ## The User and 
-00011190: 4772 6f75 7020 7573 6564 2066 6f72 2054  Group used for T
-000111a0: 6173 6b73 0a0a 4279 2064 6566 6175 6c74  asks..By default
-000111b0: 2c20 7468 6520 4167 656e 7420 7275 6e73  , the Agent runs
-000111c0: 2061 7320 7573 6572 2061 6e64 2067 726f   as user and gro
-000111d0: 7570 2060 7964 2d61 6765 6e74 602c 2061  up `yd-agent`, a
-000111e0: 6e64 2068 656e 6365 2054 6173 6b73 2061  nd hence Tasks a
-000111f0: 6c73 6f20 6578 6563 7574 6520 756e 6465  lso execute unde
-00011200: 7220 7468 6973 2075 7365 722e 0a0a 6079  r this user...`y
-00011210: 642d 6167 656e 7460 2064 6f65 7320 6e6f  d-agent` does no
-00011220: 7420 6861 7665 2060 7375 646f 6020 7072  t have `sudo` pr
-00011230: 6976 696c 6567 6573 2061 7320 7374 616e  ivileges as stan
-00011240: 6461 7264 2c20 6275 7420 7468 6973 2063  dard, but this c
-00011250: 616e 2062 6520 6164 6465 6420 6966 2072  an be added if r
-00011260: 6571 7569 7265 6420 6174 2069 6e73 7461  equired at insta
-00011270: 6e63 6520 626f 6f74 2074 696d 6520 7669  nce boot time vi
-00011280: 6120 7468 6520 6075 7365 7244 6174 6160  a the `userData`
-00011290: 2070 726f 7065 7274 7920 6f66 2061 2070   property of a p
-000112a0: 726f 7669 7369 6f6e 696e 6720 7265 7175  rovisioning requ
-000112b0: 6573 742e 2045 2e67 2e20 2866 6f72 2055  est. E.g. (for U
-000112c0: 6275 6e74 7529 3a0a 0a60 6060 7368 656c  buntu):..```shel
-000112d0: 6c0a 7573 6572 6d6f 6420 2d61 4720 7768  l.usermod -aG wh
-000112e0: 6565 6c20 7964 2d61 6765 6e74 0a65 6368  eel yd-agent.ech
-000112f0: 6f20 2d65 2022 7964 2d61 6765 6e74 5c74  o -e "yd-agent\t
-00011300: 414c 4c3d 2841 4c4c 295c 744e 4f50 4153  ALL=(ALL)\tNOPAS
-00011310: 5357 443a 2041 4c4c 2220 3e20 2f65 7463  SWD: ALL" > /etc
-00011320: 2f73 7564 6f65 7273 2e64 2f30 3230 2d79  /sudoers.d/020-y
-00011330: 642d 6167 656e 740a 6060 600a 0a23 2323  d-agent.```..###
-00011340: 2048 6f6d 6520 4469 7265 6374 6f72 7920   Home Directory 
-00011350: 666f 7220 6079 642d 6167 656e 7460 0a0a  for `yd-agent`..
-00011360: 4279 2064 6566 6175 6c74 2c20 7468 6520  By default, the 
-00011370: 686f 6d65 2064 6972 6563 746f 7279 206f  home directory o
-00011380: 6620 7468 6520 6079 642d 6167 656e 7460  f the `yd-agent`
-00011390: 2075 7365 7220 6973 2060 2f6f 7074 2f79   user is `/opt/y
-000113a0: 656c 6c6f 7764 6f67 2f61 6765 6e74 602e  ellowdog/agent`.
-000113b0: 2054 6869 7320 6469 7265 6374 6f72 7920   This directory 
-000113c0: 7479 7069 6361 6c6c 7920 636f 6e74 6169  typically contai
-000113d0: 6e73 2074 6865 2060 6170 706c 6963 6174  ns the `applicat
-000113e0: 696f 6e2e 7961 6d6c 6020 6669 6c65 2075  ion.yaml` file u
-000113f0: 7365 6420 746f 2063 6f6e 6669 6775 7265  sed to configure
-00011400: 2074 6865 2041 6765 6e74 2c20 6173 2077   the Agent, as w
-00011410: 656c 6c20 6173 2061 6e79 2073 6372 6970  ell as any scrip
-00011420: 7473 2074 6861 7420 6172 6520 7573 6564  ts that are used
-00011430: 2074 6f20 6578 6563 7574 6520 7468 6520   to execute the 
-00011440: 5461 736b 2054 7970 6573 2074 6861 7420  Task Types that 
-00011450: 7468 6520 6e6f 6465 2073 7570 706f 7274  the node support
-00011460: 732e 0a0a 4966 206f 6e65 2077 616e 7473  s...If one wants
-00011470: 2074 6f20 5353 4820 746f 2061 6e20 696e   to SSH to an in
-00011480: 7374 616e 6365 2061 7320 7573 6572 2060  stance as user `
-00011490: 7964 2d61 6765 6e74 602c 2070 6572 6861  yd-agent`, perha
-000114a0: 7073 2066 6f72 2064 6562 7567 6769 6e67  ps for debugging
-000114b0: 2070 7572 706f 7365 732c 2053 5348 206b   purposes, SSH k
-000114c0: 6579 7320 6361 6e20 6265 2069 6e73 6572  eys can be inser
-000114d0: 7465 6420 7669 6120 696e 7374 616e 6365  ted via instance
-000114e0: 2060 7573 6572 4461 7461 602c 2065 2e67   `userData`, e.g
-000114f0: 2e3a 0a0a 6060 6073 6865 6c6c 0a59 4441  .:..```shell.YDA
-00011500: 5f48 4f4d 453d 2f6f 7074 2f79 656c 6c6f  _HOME=/opt/yello
-00011510: 7764 6f67 2f61 6765 6e74 0a6d 6b64 6972  wdog/agent.mkdir
-00011520: 202d 7020 2459 4441 5f48 4f4d 452f 2e73   -p $YDA_HOME/.s
-00011530: 7368 0a63 686d 6f64 206f 672d 7277 7820  sh.chmod og-rwx 
-00011540: 2459 4441 5f48 4f4d 452f 2e73 7368 0a63  $YDA_HOME/.ssh.c
-00011550: 6174 203e 3e20 2459 4441 5f48 4f4d 452f  at >> $YDA_HOME/
-00011560: 2e73 7368 2f61 7574 686f 7269 7a65 645f  .ssh/authorized_
-00011570: 6b65 7973 203c 3c20 454f 460a 3c3c 496e  keys << EOF.<<In
-00011580: 7365 7274 5f50 7562 6c69 635f 6b65 795f  sert_Public_key_
-00011590: 4865 7265 3e3e 0a45 4f46 0a63 686d 6f64  Here>>.EOF.chmod
-000115a0: 206f 672d 7277 2024 5944 415f 484f 4d45   og-rw $YDA_HOME
-000115b0: 2f2e 7373 682f 6175 7468 6f72 697a 6564  /.ssh/authorized
-000115c0: 5f6b 6579 730a 6368 6f77 6e20 2d52 2079  _keys.chown -R y
-000115d0: 642d 6167 656e 743a 7964 2d61 6765 6e74  d-agent:yd-agent
-000115e0: 2024 5944 415f 484f 4d45 2f2e 7373 680a   $YDA_HOME/.ssh.
-000115f0: 6060 600a 0a23 2323 2054 6173 6b20 4578  ```..### Task Ex
-00011600: 6563 7574 696f 6e20 4469 7265 6374 6f72  ecution Director
-00011610: 790a 0a45 7068 656d 6572 616c 2054 6173  y..Ephemeral Tas
-00011620: 6b20 6469 7265 6374 6f72 6965 7320 6172  k directories ar
-00011630: 6520 6279 2064 6566 6175 6c74 2063 7265  e by default cre
-00011640: 6174 6564 2075 6e64 6572 2060 2f76 6172  ated under `/var
-00011650: 2f6f 7074 2f79 656c 6c6f 7764 6f67 2f61  /opt/yellowdog/a
-00011660: 6765 6e74 2f64 6174 612f 776f 726b 6572  gent/data/worker
-00011670: 7360 2e20 5468 6973 2064 6972 6563 746f  s`. This directo
-00011680: 7279 2063 6f6e 7461 696e 7320 6f6e 6520  ry contains one 
-00011690: 6f72 206d 6f72 6520 6e75 6d62 6572 6564  or more numbered
-000116a0: 2073 7562 6469 7265 6374 6f72 6965 7320   subdirectories 
-000116b0: 7768 6572 6520 6561 6368 206e 756d 6265  where each numbe
-000116c0: 7265 6420 6469 7265 6374 6f72 7920 636f  red directory co
-000116d0: 7272 6573 706f 6e64 7320 746f 2061 2057  rresponds to a W
-000116e0: 6f72 6b65 7220 6f6e 2074 6865 206e 6f64  orker on the nod
-000116f0: 652e 0a0a 284f 6e20 5769 6e64 6f77 7320  e...(On Windows 
-00011700: 686f 7374 732c 2074 6865 2054 6173 6b20  hosts, the Task 
-00011710: 6469 7265 6374 6f72 6965 7320 6172 6520  directories are 
-00011720: 666f 756e 6420 756e 6465 7220 6025 4170  found under `%Ap
-00011730: 7044 6174 6125 5c79 656c 6c6f 7764 6f67  pData%\yellowdog
-00011740: 5c61 6765 6e74 5c64 6174 615c 776f 726b  \agent\data\work
-00011750: 6572 7360 2e29 0a0a 5768 656e 2061 2054  ers`.)..When a T
-00011760: 6173 6b20 6973 2061 6c6c 6f63 6174 6564  ask is allocated
-00011770: 2074 6f20 6120 6e6f 6465 2c20 616e 2065   to a node, an e
-00011780: 7068 656d 6572 616c 2064 6972 6563 746f  phemeral directo
-00011790: 7279 2069 7320 6372 6561 7465 6420 756e  ry is created un
-000117a0: 6465 7220 7468 6520 6170 706c 6963 6162  der the applicab
-000117b0: 6c65 2057 6f72 6b65 7220 6469 7265 6374  le Worker direct
-000117c0: 6f72 792c 2077 6974 6820 6120 6e61 6d65  ory, with a name
-000117d0: 2063 6f72 7265 7370 6f6e 6469 6e67 2074   corresponding t
-000117e0: 6865 2059 656c 6c6f 7744 6f67 2049 4420  he YellowDog ID 
-000117f0: 666f 7220 7468 6520 5461 736b 2e20 466f  for the Task. Fo
-00011800: 7220 6578 616d 706c 652c 2074 6869 7320  r example, this 
-00011810: 6973 2061 6e20 6570 6865 6d65 7261 6c20  is an ephemeral 
-00011820: 6469 7265 6374 6f72 7920 6265 696e 6720  directory being 
-00011830: 7573 6564 2062 7920 576f 726b 6572 206e  used by Worker n
-00011840: 756d 6265 7220 6031 603a 0a0a 602f 7661  umber `1`:..`/va
-00011850: 722f 6f70 742f 7965 6c6c 6f77 646f 672f  r/opt/yellowdog/
-00011860: 6167 656e 742f 6461 7461 2f77 6f72 6b65  agent/data/worke
-00011870: 7273 2f31 2f79 6469 645f 7461 736b 5f35  rs/1/ydid_task_5
-00011880: 3539 4542 455f 3734 3934 3933 3336 2d61  59EBE_74949336-a
-00011890: 6332 622d 3438 3131 2d61 3764 352d 6633  c2b-4811-a7d5-f3
-000118a0: 6563 6439 3733 3939 3038 5f31 5f31 600a  ecd9739908_1_1`.
-000118b0: 0a54 6869 7320 6973 2074 6865 2064 6972  .This is the dir
-000118c0: 6563 746f 7279 2069 6e74 6f20 7768 6963  ectory into whic
-000118d0: 6820 646f 776e 6c6f 6164 6564 206f 626a  h downloaded obj
-000118e0: 6563 7473 2061 7265 2070 6c61 6365 642c  ects are placed,
-000118f0: 2061 6e64 2069 6e20 7768 6963 6820 6f75   and in which ou
-00011900: 7470 7574 2066 696c 6573 2061 7265 2063  tput files are c
-00011910: 7265 6174 6564 2062 7920 6465 6661 756c  reated by defaul
-00011920: 742e 2054 6865 2063 6f6e 736f 6c65 206f  t. The console o
-00011930: 7574 7075 7420 6074 6173 6b6f 7574 7075  utput `taskoutpu
-00011940: 742e 7478 7460 2066 696c 6520 7769 6c6c  t.txt` file will
-00011950: 2061 6c73 6f20 6265 2063 7265 6174 6564   also be created
-00011960: 2069 6e20 7468 6973 2064 6972 6563 746f   in this directo
-00011970: 7279 2e0a 0a53 6565 2074 6865 205b 4669  ry...See the [Fi
-00011980: 6c65 7320 446f 776e 6c6f 6164 6564 2074  les Downloaded t
-00011990: 6f20 6120 4e6f 6465 5d28 2366 696c 6573  o a Node](#files
-000119a0: 2d64 6f77 6e6c 6f61 6465 642d 746f 2d61  -downloaded-to-a
-000119b0: 2d6e 6f64 652d 666f 722d 7573 652d 696e  -node-for-use-in
-000119c0: 2d74 6173 6b2d 6578 6563 7574 696f 6e29  -task-execution)
-000119d0: 2073 6563 7469 6f6e 2061 626f 7665 2066   section above f
-000119e0: 6f72 206d 6f72 6520 6465 7461 696c 7320  or more details 
-000119f0: 6f6e 2068 6f77 2066 696c 6573 2069 6e20  on how files in 
-00011a00: 7468 6973 2064 6972 6563 746f 7279 2061  this directory a
-00011a10: 7265 2068 616e 646c 6564 2e0a 0a41 7420  re handled...At 
-00011a20: 7468 6520 636f 6e63 6c75 7369 6f6e 206f  the conclusion o
-00011a30: 6620 7468 6520 5461 736b 2c20 6166 7465  f the Task, afte
-00011a40: 7220 616e 7920 6669 6c65 7320 7265 7175  r any files requ
-00011a50: 6573 7465 6420 666f 7220 7570 6c6f 6164  ested for upload
-00011a60: 2068 6176 6520 6265 656e 2075 706c 6f61   have been uploa
-00011a70: 6465 6420 746f 2074 6865 204f 626a 6563  ded to the Objec
-00011a80: 7420 5374 6f72 6520 2873 6565 2074 6865  t Store (see the
-00011a90: 205b 4669 6c65 7320 5570 6c6f 6164 6564   [Files Uploaded
-00011aa0: 2066 726f 6d20 6120 4e6f 6465 5d28 2366   from a Node](#f
-00011ab0: 696c 6573 2d75 706c 6f61 6465 642d 6672  iles-uploaded-fr
-00011ac0: 6f6d 2d61 2d6e 6f64 652d 746f 2d74 6865  om-a-node-to-the
-00011ad0: 2d6f 626a 6563 742d 7374 6f72 652d 6166  -object-store-af
-00011ae0: 7465 722d 7461 736b 2d65 7865 6375 7469  ter-task-executi
-00011af0: 6f6e 2920 7365 6374 696f 6e20 666f 7220  on) section for 
-00011b00: 6d6f 7265 2069 6e66 6f72 6d61 7469 6f6e  more information
-00011b10: 292c 2074 6865 2060 7964 6964 5f74 6173  ), the `ydid_tas
-00011b20: 6b5f 3535 3945 4245 5f37 3439 3439 3333  k_559EBE_7494933
-00011b30: 362d 6163 3262 2d34 3831 312d 6137 6435  6-ac2b-4811-a7d5
-00011b40: 2d66 3365 6364 3937 3339 3930 385f 315f  -f3ecd9739908_1_
-00011b50: 3160 2077 696c 6c20 6265 2072 656d 6f76  1` will be remov
-00011b60: 6564 2e0a 0a23 2320 5370 6563 6966 7969  ed...## Specifyi
-00011b70: 6e67 2057 6f72 6b20 5265 7175 6972 656d  ng Work Requirem
-00011b80: 656e 7473 2075 7369 6e67 2043 5356 2044  ents using CSV D
-00011b90: 6174 610a 0a43 5356 2064 6174 6120 6669  ata..CSV data fi
-00011ba0: 6c65 7320 6361 6e20 6265 2075 7365 6420  les can be used 
-00011bb0: 746f 2064 7269 7665 2074 6865 2067 656e  to drive the gen
-00011bc0: 6572 6174 696f 6e20 6f66 206c 6973 7473  eration of lists
-00011bd0: 206f 6620 5461 736b 732c 2061 7320 666f   of Tasks, as fo
-00011be0: 6c6c 6f77 733a 0a0a 2d20 4120 2a2a 7072  llows:..- A **pr
-00011bf0: 6f74 6f74 7970 652a 2a20 5461 736b 2073  ototype** Task s
-00011c00: 7065 6369 6669 6361 7469 6f6e 2069 7320  pecification is 
-00011c10: 6372 6561 7465 6420 7769 7468 696e 2061  created within a
-00011c20: 204a 534f 4e20 576f 726b 2052 6571 7569   JSON Work Requi
-00011c30: 7265 6d65 6e74 2073 7065 6369 6669 6361  rement specifica
-00011c40: 7469 6f6e 206f 7220 696e 2074 6865 2060  tion or in the `
-00011c50: 776f 726b 5265 7175 6972 656d 656e 7460  workRequirement`
-00011c60: 2073 6563 7469 6f6e 206f 6620 7468 6520   section of the 
-00011c70: 544f 4d4c 2063 6f6e 6669 6775 7261 7469  TOML configurati
-00011c80: 6f6e 2066 696c 650a 2d20 5468 6520 7072  on file.- The pr
-00011c90: 6f74 6f74 7970 6520 7461 736b 2069 6e63  ototype task inc
-00011ca0: 6c75 6465 7320 6f6e 6520 6f72 206d 6f72  ludes one or mor
-00011cb0: 6520 7661 7269 6162 6c65 2073 7562 7374  e variable subst
-00011cc0: 6974 7574 696f 6e73 0a2d 2041 2043 5356  itutions.- A CSV
-00011cd0: 2066 696c 6520 6973 2063 7265 6174 6564   file is created
-00011ce0: 2c20 7769 7468 2074 6865 202a 2a68 6561  , with the **hea
-00011cf0: 6465 7273 2a2a 2028 6669 7273 7420 726f  ders** (first ro
-00011d00: 7729 206d 6174 6368 696e 6720 7468 6520  w) matching the 
-00011d10: 6e61 6d65 7320 6f66 2074 6865 2076 6172  names of the var
-00011d20: 6961 626c 6520 7375 6273 7469 7475 7469  iable substituti
-00011d30: 6f6e 7320 696e 2074 6865 2054 6173 6b20  ons in the Task 
-00011d40: 7072 6f74 6f74 7970 650a 2d20 4561 6368  prototype.- Each
-00011d50: 2073 7562 7365 7175 656e 7420 726f 7720   subsequent row 
-00011d60: 6f66 2074 6865 2043 5356 2066 696c 6520  of the CSV file 
-00011d70: 7265 7072 6573 656e 7473 2061 206e 6577  represents a new
-00011d80: 2054 6173 6b20 6275 696c 7420 7573 696e   Task built usin
-00011d90: 6720 7468 6520 7072 6f74 6f74 7970 652c  g the prototype,
-00011da0: 2077 6974 6820 7468 6520 7661 7269 6162   with the variab
-00011db0: 6c65 7320 7375 6273 7469 7475 7465 6420  les substituted 
-00011dc0: 6279 2074 6865 2076 616c 7565 7320 696e  by the values in
-00011dd0: 2074 6865 2072 6f77 0a2d 2041 2054 6173   the row.- A Tas
-00011de0: 6b20 7769 6c6c 2062 6520 6372 6561 7465  k will be create
-00011df0: 6420 666f 7220 6561 6368 2064 6174 6120  d for each data 
-00011e00: 726f 770a 0a23 2323 2057 6f72 6b20 5265  row..### Work Re
-00011e10: 7175 6972 656d 656e 7420 4353 5620 4461  quirement CSV Da
-00011e20: 7461 2045 7861 6d70 6c65 0a0a 4173 2061  ta Example..As a
-00011e30: 6e20 6578 616d 706c 652c 2063 6f6e 7369  n example, consi
-00011e40: 6465 7220 7468 6520 666f 6c6c 6f77 696e  der the followin
-00011e50: 6720 4a53 4f4e 2057 6f72 6b20 5265 7175  g JSON Work Requ
-00011e60: 6972 656d 656e 7420 6077 722e 6a73 6f6e  irement `wr.json
-00011e70: 603a 0a0a 6060 606a 736f 6e0a 7b0a 2020  `:..```json.{.  
-00011e80: 2274 6173 6b47 726f 7570 7322 3a20 5b0a  "taskGroups": [.
-00011e90: 2020 2020 7b0a 2020 2020 2020 2274 6173      {.      "tas
-00011ea0: 6b73 223a 205b 0a20 2020 2020 2020 207b  ks": [.        {
-00011eb0: 0a20 2020 2020 2020 2020 2022 6172 6775  .          "argu
-00011ec0: 6d65 6e74 7322 3a20 5b22 7b7b 6172 675f  ments": ["{{arg_
-00011ed0: 317d 7d22 2c20 227b 7b61 7267 5f32 7d7d  1}}", "{{arg_2}}
-00011ee0: 222c 2022 7b7b 6172 675f 337d 7d22 5d2c  ", "{{arg_3}}"],
-00011ef0: 0a20 2020 2020 2020 2020 2022 656e 7669  .          "envi
-00011f00: 726f 6e6d 656e 7422 3a20 7b22 454e 565f  ronment": {"ENV_
-00011f10: 5641 525f 3122 3a20 227b 7b65 6e76 5f31  VAR_1": "{{env_1
-00011f20: 7d7d 227d 0a20 2020 2020 2020 207d 0a20  }}"}.        }. 
-00011f30: 2020 2020 205d 0a20 2020 207d 0a20 205d       ].    }.  ]
-00011f40: 0a7d 0a60 6060 0a0a 4e6f 7465 2074 6861  .}.```..Note tha
-00011f50: 7420 7468 6520 5461 736b 2047 726f 7570  t the Task Group
-00011f60: 206d 7573 7420 636f 6e74 6169 6e20 6f6e   must contain on
-00011f70: 6c79 2061 2073 696e 676c 6520 5461 736b  ly a single Task
-00011f80: 2c20 6163 7469 6e67 2061 7320 7468 6520  , acting as the 
-00011f90: 7072 6f74 6f74 7970 652e 0a0a 4e6f 7720  prototype...Now 
-00011fa0: 636f 6e73 6964 6572 2061 2043 5356 2066  consider a CSV f
-00011fb0: 696c 6520 6077 725f 6461 7461 2e63 7376  ile `wr_data.csv
-00011fc0: 6020 7769 7468 2074 6865 2066 6f6c 6c6f  ` with the follo
-00011fd0: 7769 6e67 2063 6f6e 7465 6e74 733a 0a0a  wing contents:..
-00011fe0: 6060 6074 6578 740a 6172 675f 312c 2061  ```text.arg_1, a
-00011ff0: 7267 5f32 2c20 6172 675f 332c 2065 6e76  rg_2, arg_3, env
-00012000: 5f31 0a41 2c20 2020 2020 422c 2020 2020  _1.A,     B,    
-00012010: 2043 2c20 2020 2020 452d 310a 442c 2020   C,     E-1.D,  
-00012020: 2020 2045 2c20 2020 2020 462c 2020 2020     E,     F,    
-00012030: 2045 2d32 0a47 2c20 2020 2020 482c 2020   E-2.G,     H,  
-00012040: 2020 2049 2c20 2020 2020 452d 330a 6060     I,     E-3.``
-00012050: 600a 0a4e 6f74 6520 7468 6174 2074 6865  `..Note that the
-00012060: 2028 6f70 7469 6f6e 616c 2920 6c65 6164   (optional) lead
-00012070: 696e 6720 7370 6163 6573 2061 6674 6572  ing spaces after
-00012080: 2065 6163 6820 636f 6d6d 6120 6172 6520   each comma are 
-00012090: 6967 6e6f 7265 642c 2062 7574 2074 7261  ignored, but tra
-000120a0: 696c 696e 6720 7370 6163 6573 2061 7265  iling spaces are
-000120b0: 206e 6f74 2061 6e64 2077 696c 6c20 666f   not and will fo
-000120c0: 726d 2070 6172 7420 6f66 2074 6865 2069  rm part of the i
-000120d0: 6d70 6f72 7465 6420 6461 7461 2e0a 0a49  mported data...I
-000120e0: 6620 7468 6573 6520 6669 6c65 7320 6172  f these files ar
-000120f0: 6520 7072 6f63 6573 7365 6420 7573 696e  e processed usin
-00012100: 6720 6079 642d 7375 626d 6974 202d 7220  g `yd-submit -r 
-00012110: 7772 2e6a 736f 6e20 2d56 2077 725f 6461  wr.json -V wr_da
-00012120: 7461 2e63 7376 602c 2074 6865 2066 6f6c  ta.csv`, the fol
-00012130: 6c6f 7769 6e67 2065 7870 616e 6465 6420  lowing expanded 
-00012140: 6c69 7374 206f 6620 7468 7265 6520 5461  list of three Ta
-00012150: 736b 7320 7769 6c6c 2062 6520 6372 6561  sks will be crea
-00012160: 7465 6420 7072 696f 7220 746f 2066 7572  ted prior to fur
-00012170: 7468 6572 2070 726f 6365 7373 696e 6720  ther processing 
-00012180: 6279 2074 6865 2060 7964 2d73 7562 6d69  by the `yd-submi
-00012190: 7460 2073 6372 6970 743a 0a0a 6060 606a  t` script:..```j
-000121a0: 736f 6e0a 7b0a 2020 2274 6173 6b47 726f  son.{.  "taskGro
-000121b0: 7570 7322 3a20 5b0a 2020 2020 7b0a 2020  ups": [.    {.  
-000121c0: 2020 2020 2274 6173 6b73 223a 205b 0a20      "tasks": [. 
-000121d0: 2020 2020 2020 207b 0a20 2020 2020 2020         {.       
-000121e0: 2020 2022 6172 6775 6d65 6e74 7322 3a20     "arguments": 
-000121f0: 5b22 4122 2c20 2242 222c 2022 4322 5d2c  ["A", "B", "C"],
-00012200: 0a20 2020 2020 2020 2020 2022 656e 7669  .          "envi
-00012210: 726f 6e6d 656e 7422 3a20 7b22 454e 565f  ronment": {"ENV_
-00012220: 5641 525f 3122 3a20 2245 2d31 227d 0a20  VAR_1": "E-1"}. 
-00012230: 2020 2020 2020 207d 2c0a 2020 2020 2020         },.      
-00012240: 2020 7b0a 2020 2020 2020 2020 2020 2261    {.          "a
-00012250: 7267 756d 656e 7473 223a 205b 2244 222c  rguments": ["D",
-00012260: 2022 4522 2c20 2246 225d 2c0a 2020 2020   "E", "F"],.    
-00012270: 2020 2020 2020 2265 6e76 6972 6f6e 6d65        "environme
-00012280: 6e74 223a 207b 2245 4e56 5f56 4152 5f31  nt": {"ENV_VAR_1
-00012290: 223a 2022 452d 3222 7d0a 2020 2020 2020  ": "E-2"}.      
-000122a0: 2020 7d2c 0a20 2020 2020 2020 207b 0a20    },.        {. 
-000122b0: 2020 2020 2020 2020 2022 6172 6775 6d65           "argume
-000122c0: 6e74 7322 3a20 5b22 4722 2c20 2248 222c  nts": ["G", "H",
-000122d0: 2022 4922 5d2c 0a20 2020 2020 2020 2020   "I"],.         
-000122e0: 2022 656e 7669 726f 6e6d 656e 7422 3a20   "environment": 
-000122f0: 7b22 454e 565f 5641 525f 3122 3a20 2245  {"ENV_VAR_1": "E
-00012300: 2d33 227d 0a20 2020 2020 2020 207d 0a20  -3"}.        }. 
-00012310: 2020 2020 205d 0a20 2020 207d 0a20 205d       ].    }.  ]
-00012320: 0a7d 0a60 6060 0a0a 2323 2320 4353 5620  .}.```..### CSV 
-00012330: 5661 7269 6162 6c65 2053 7562 7374 6974  Variable Substit
-00012340: 7574 696f 6e73 0a0a 5768 656e 2074 6865  utions..When the
-00012350: 2043 5356 2066 696c 6520 6461 7461 2069   CSV file data i
-00012360: 7320 7072 6f63 6573 7365 642c 2074 6865  s processed, the
-00012370: 206f 6e6c 7920 7375 6273 7469 7475 7469   only substituti
-00012380: 6f6e 7320 6d61 6465 2061 7265 2074 686f  ons made are tho
-00012390: 7365 2077 6869 6368 206d 6174 6368 2074  se which match t
-000123a0: 6865 2076 6172 6961 626c 6520 7375 6273  he variable subs
-000123b0: 7469 7475 7469 6f6e 7320 696e 2074 6865  titutions in the
-000123c0: 2070 726f 746f 7479 7065 2054 6173 6b2e   prototype Task.
-000123d0: 2054 6865 2043 5356 2066 696c 6520 6973   The CSV file is
-000123e0: 2074 6865 202a 2a6f 6e6c 792a 2a20 736f   the **only** so
-000123f0: 7572 6365 206f 6620 7375 6273 7469 7475  urce of substitu
-00012400: 7469 6f6e 7320 7573 6564 2066 6f72 2074  tions used for t
-00012410: 6869 7320 7072 6f63 6573 7369 6e67 2070  his processing p
-00012420: 6861 7365 3b20 616c 6c20 6f74 6865 7220  hase; all other 
-00012430: 7661 7269 6162 6c65 2073 7562 7374 6974  variable substit
-00012440: 7574 696f 6e73 2028 7375 7070 6c69 6564  utions (supplied
-00012450: 206f 6e20 7468 6520 636f 6d6d 616e 6420   on the command 
-00012460: 6c69 6e65 2c20 696e 2074 6865 2054 4f4d  line, in the TOM
-00012470: 4c20 636f 6e66 6967 7572 6174 696f 6e20  L configuration 
-00012480: 6669 6c65 2c20 6f72 2066 726f 6d20 656e  file, or from en
-00012490: 7669 726f 6e6d 656e 7420 7661 7269 6162  vironment variab
-000124a0: 6c65 7329 2061 7265 2069 676e 6f72 6564  les) are ignored
-000124b0: 202d 2d20 692e 652e 2c20 7468 6579 2064   -- i.e., they d
-000124c0: 6f20 6e6f 7420 6f76 6572 7269 6465 2074  o not override t
-000124d0: 6865 2063 6f6e 7465 6e74 7320 6f66 2074  he contents of t
-000124e0: 6865 2043 5356 2066 696c 652e 0a0a 416c  he CSV file...Al
-000124f0: 6c20 7661 7269 6162 6c65 2073 7562 7374  l variable subst
-00012500: 6974 7574 696f 6e73 2075 6e72 656c 6174  itutions unrelat
-00012510: 6564 2074 6f20 7468 6520 4353 5620 6669  ed to the CSV fi
-00012520: 6c65 2064 6174 6120 6172 6520 6c65 6674  le data are left
-00012530: 2075 6e63 6861 6e67 6564 2c20 666f 7220   unchanged, for 
-00012540: 7375 6273 6571 7565 6e74 2070 726f 6365  subsequent proce
-00012550: 7373 696e 6720 6279 2060 7964 2d73 7562  ssing by `yd-sub
-00012560: 6d69 7460 2e0a 0a49 6620 7468 6520 7661  mit`...If the va
-00012570: 6c75 6520 746f 2062 6520 696e 7365 7274  lue to be insert
-00012580: 6564 2069 7320 6120 6e75 6d62 6572 2028  ed is a number (
-00012590: 616e 2069 6e74 6567 6572 206f 7220 666c  an integer or fl
-000125a0: 6f61 7469 6e67 2070 6f69 6e74 2076 616c  oating point val
-000125b0: 7565 2920 6f72 2042 6f6f 6c65 616e 2c20  ue) or Boolean, 
-000125c0: 7468 6520 607b 7b6e 756d 3a6d 795f 6e75  the `{{num:my_nu
-000125d0: 6d62 6572 5f76 6172 7d7d 6020 616e 6420  mber_var}}` and 
-000125e0: 607b 7b62 6f6f 6c3a 6d79 5f62 6f6f 6c65  `{{bool:my_boole
-000125f0: 616e 5f76 6172 7d7d 6020 666f 726d 7320  an_var}}` forms 
-00012600: 6361 6e20 6265 2075 7365 6420 696e 2074  can be used in t
-00012610: 6865 204a 534f 4e20 6669 6c65 2c20 6173  he JSON file, as
-00012620: 2077 6974 6820 7468 6569 7220 7573 6520   with their use 
-00012630: 696e 206f 7468 6572 2070 6172 7473 206f  in other parts o
-00012640: 6620 7468 6520 4a53 4f4e 2057 6f72 6b20  f the JSON Work 
-00012650: 5265 7175 6972 656d 656e 7420 7370 6563  Requirement spec
-00012660: 6966 6963 6174 696f 6e2e 2054 6865 2073  ification. The s
-00012670: 7562 7374 6974 7574 6564 2076 616c 7565  ubstituted value
-00012680: 2077 696c 6c20 6173 7375 6d65 2074 6865   will assume the
-00012690: 206e 6f6d 696e 6174 6564 2074 7970 6520   nominated type 
-000126a0: 7261 7468 6572 2074 6861 6e20 6265 696e  rather than bein
-000126b0: 6720 6120 7374 7269 6e67 2e0a 0a23 2323  g a string...###
-000126c0: 2050 726f 7065 7274 7920 496e 6865 7269   Property Inheri
-000126d0: 7461 6e63 650a 0a41 6c6c 2074 6865 2075  tance..All the u
-000126e0: 7375 616c 2070 726f 7065 7274 7920 696e  sual property in
-000126f0: 6865 7269 7461 6e63 6520 6665 6174 7572  heritance featur
-00012700: 6573 206f 7065 7261 7465 2061 7320 6e6f  es operate as no
-00012710: 726d 616c 2e20 5072 6f70 6572 7469 6573  rmal. Properties
-00012720: 2061 7265 2069 6e68 6572 6974 6564 2066   are inherited f
-00012730: 726f 6d20 7468 6520 6063 6f6e 6669 672e  rom the `config.
-00012740: 746f 6d6c 6020 6669 6c65 2c20 616e 6420  toml` file, and 
-00012750: 6672 6f6d 2074 6865 2072 656c 6576 616e  from the relevan
-00012760: 7420 7365 6374 696f 6e73 206f 6620 7468  t sections of th
-00012770: 6520 4a53 4f4e 2057 6f72 6b20 5265 7175  e JSON Work Requ
-00012780: 6972 656d 656e 7420 6669 6c65 2e20 416e  irement file. An
-00012790: 7920 7072 6f70 6572 7469 6573 2073 6574  y properties set
-000127a0: 2077 6974 6869 6e20 6120 5461 736b 2070   within a Task p
-000127b0: 726f 746f 7479 7065 2061 7265 2063 6f70  rototype are cop
-000127c0: 6965 6420 746f 2061 6c6c 2074 6865 2067  ied to all the g
-000127d0: 656e 6572 6174 6564 2054 6173 6b73 2e0a  enerated Tasks..
-000127e0: 0a23 2323 204d 756c 7469 706c 6520 5461  .### Multiple Ta
-000127f0: 736b 2047 726f 7570 7320 7573 696e 6720  sk Groups using 
-00012800: 4d75 6c74 6970 6c65 2043 5356 2046 696c  Multiple CSV Fil
-00012810: 6573 0a0a 5468 6520 7573 6520 6f66 206d  es..The use of m
-00012820: 756c 7469 706c 6520 5461 736b 2047 726f  ultiple Task Gro
-00012830: 7570 7320 6973 2061 6c73 6f20 7375 7070  ups is also supp
-00012840: 6f72 7465 642c 2062 7920 7573 696e 6720  orted, by using 
-00012850: 6f6e 6520 4353 5620 6669 6c65 2070 6572  one CSV file per
-00012860: 2054 6173 6b20 4772 6f75 702e 2045 6163   Task Group. Eac
-00012870: 6820 5461 736b 2047 726f 7570 206d 7573  h Task Group mus
-00012880: 7420 636f 6e74 6169 6e20 6f6e 6c79 2061  t contain only a
-00012890: 2073 696e 676c 6520 7072 6f74 6f74 7970   single prototyp
-000128a0: 6520 5461 736b 2e0a 0a54 6865 2043 5356  e Task...The CSV
-000128b0: 2066 696c 6573 2061 7265 2073 7570 706c   files are suppl
-000128c0: 6965 6420 6f6e 2074 6865 2063 6f6d 6d61  ied on the comma
-000128d0: 6e64 206c 696e 6520 696e 2074 6865 206f  nd line in the o
-000128e0: 7264 6572 206f 6620 7468 6520 5461 736b  rder of the Task
-000128f0: 2047 726f 7570 7320 746f 2077 6869 6368   Groups to which
-00012900: 2074 6865 7920 6170 706c 792e 2046 6f72   they apply. For
-00012910: 2065 7861 6d70 6c65 2c20 6966 2060 7772   example, if `wr
-00012920: 5f6a 736f 6e60 2063 6f6e 7461 696e 7320  _json` contains 
-00012930: 7477 6f20 5461 736b 2047 726f 7570 732c  two Task Groups,
-00012940: 2061 7320 666f 6c6c 6f77 733a 0a0a 6060   as follows:..``
-00012950: 606a 736f 6e0a 7b0a 2020 2274 6173 6b47  `json.{.  "taskG
-00012960: 726f 7570 7322 3a20 5b0a 2020 2020 7b0a  roups": [.    {.
-00012970: 2020 2020 2020 2274 6173 6b73 223a 205b        "tasks": [
-00012980: 0a20 2020 2020 2020 207b 0a20 2020 2020  .        {.     
-00012990: 2020 2020 2022 6172 6775 6d65 6e74 7322       "arguments"
-000129a0: 3a20 5b22 7b7b 6172 675f 317d 7d22 2c20  : ["{{arg_1}}", 
-000129b0: 227b 7b61 7267 5f32 7d7d 222c 2022 7b7b  "{{arg_2}}", "{{
-000129c0: 6172 675f 337d 7d22 5d2c 0a20 2020 2020  arg_3}}"],.     
-000129d0: 2020 2020 2022 656e 7669 726f 6e6d 656e       "environmen
-000129e0: 7422 3a20 7b22 454e 565f 5641 525f 3122  t": {"ENV_VAR_1"
-000129f0: 3a20 227b 7b65 6e76 5f31 7d7d 227d 0a20  : "{{env_1}}"}. 
-00012a00: 2020 2020 2020 207d 0a20 2020 2020 205d         }.      ]
-00012a10: 0a20 2020 207d 2c0a 2020 2020 7b0a 2020  .    },.    {.  
-00012a20: 2020 2020 2274 6173 6b73 223a 205b 0a20      "tasks": [. 
-00012a30: 2020 2020 2020 207b 0a20 2020 2020 2020         {.       
-00012a40: 2020 2022 6172 6775 6d65 6e74 7322 3a20     "arguments": 
-00012a50: 5b22 7b7b 6172 675f 317d 7d22 2c20 227b  ["{{arg_1}}", "{
-00012a60: 7b61 7267 5f32 7d7d 225d 2c0a 2020 2020  {arg_2}}"],.    
-00012a70: 2020 2020 2020 2265 6e76 6972 6f6e 6d65        "environme
-00012a80: 6e74 223a 207b 2245 4e56 5f56 4152 5f31  nt": {"ENV_VAR_1
-00012a90: 223a 2022 7b7b 656e 765f 317d 7d22 2c20  ": "{{env_1}}", 
-00012aa0: 2245 4e56 5f56 4152 5f32 223a 2022 7b7b  "ENV_VAR_2": "{{
-00012ab0: 656e 765f 327d 7d22 7d0a 2020 2020 2020  env_2}}"}.      
-00012ac0: 2020 7d0a 2020 2020 2020 5d0a 2020 2020    }.      ].    
-00012ad0: 7d0a 2020 5d0a 7d0a 6060 600a 0a54 6865  }.  ].}.```..The
-00012ae0: 2060 7964 2d73 7562 6d69 7460 2063 6f6d   `yd-submit` com
-00012af0: 6d61 6e64 2077 6f75 6c64 2074 6865 6e20  mand would then 
-00012b00: 6265 2069 6e76 6f6b 6564 2077 6974 6820  be invoked with 
-00012b10: 6120 7365 7061 7261 7465 2043 5356 2066  a separate CSV f
-00012b20: 696c 6520 666f 7220 6561 6368 2054 6173  ile for each Tas
-00012b30: 6b20 4772 6f75 702c 2065 2e67 2e3a 0a0a  k Group, e.g.:..
-00012b40: 6060 6073 6865 6c6c 0a79 642d 7375 626d  ```shell.yd-subm
-00012b50: 6974 202d 7220 7772 2e6a 736f 6e20 2d56  it -r wr.json -V
-00012b60: 2077 725f 6461 7461 5f74 6173 6b5f 6772   wr_data_task_gr
-00012b70: 6f75 705f 312e 6373 7620 2d56 2077 725f  oup_1.csv -V wr_
-00012b80: 6461 7461 5f74 6173 6b5f 6772 6f75 705f  data_task_group_
-00012b90: 322e 6373 760a 6060 600a 0a49 6620 7468  2.csv.```..If th
-00012ba0: 6572 6520 6172 6520 2a2a 6665 7765 722a  ere are **fewer*
-00012bb0: 2a20 4353 5620 6669 6c65 7320 7468 616e  * CSV files than
-00012bc0: 2054 6173 6b20 4772 6f75 7073 2061 2077   Task Groups a w
-00012bd0: 6172 6e69 6e67 2077 696c 6c20 6265 2070  arning will be p
-00012be0: 7269 6e74 6564 2061 6e64 2c20 6966 2074  rinted and, if t
-00012bf0: 6865 7265 2061 7265 2027 6e27 2043 5356  here are 'n' CSV
-00012c00: 2066 696c 6573 2c20 4353 5620 6461 7461   files, CSV data
-00012c10: 2070 726f 6365 7373 696e 6720 7769 6c6c   processing will
-00012c20: 2062 6520 6170 706c 6965 6420 746f 2074   be applied to t
-00012c30: 6865 2066 6972 7374 2027 6e27 2054 6173  he first 'n' Tas
-00012c40: 6b20 4772 6f75 7073 2069 6e20 7468 6520  k Groups in the 
-00012c50: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
-00012c60: 2062 7920 6465 6661 756c 742c 2069 6e20   by default, in 
-00012c70: 7468 6520 6f72 6465 7220 696e 2077 6869  the order in whi
-00012c80: 6368 2074 6865 2043 5356 2066 696c 6573  ch the CSV files
-00012c90: 2077 6572 6520 7375 7070 6c69 6564 2e20   were supplied. 
-00012ca0: 4966 2074 6865 7265 2061 7265 202a 2a6d  If there are **m
-00012cb0: 6f72 652a 2a20 4353 5620 6669 6c65 7320  ore** CSV files 
-00012cc0: 7468 616e 2054 6173 6b20 4772 6f75 7073  than Task Groups
-00012cd0: 2c20 616e 2065 7272 6f72 2077 696c 6c20  , an error will 
-00012ce0: 6265 2072 6169 7365 6420 616e 6420 7072  be raised and pr
-00012cf0: 6f63 6573 7369 6e67 2077 696c 6c20 7374  ocessing will st
-00012d00: 6f70 2e0a 0a49 7420 6973 2070 6f73 7369  op...It is possi
-00012d10: 626c 6520 746f 2061 7070 6c79 2043 5356  ble to apply CSV
-00012d20: 2066 696c 6573 2065 7870 6c69 6369 746c   files explicitl
-00012d30: 7920 746f 2073 7065 6369 6669 6320 5461  y to specific Ta
-00012d40: 736b 2047 726f 7570 732c 2062 7920 7573  sk Groups, by us
-00012d50: 696e 6720 616e 206f 7074 696f 6e61 6c20  ing an optional 
-00012d60: 2a2a 696e 6465 7820 706f 7374 6669 782a  **index postfix*
-00012d70: 2a20 2865 2e67 2e2c 2060 3a32 6029 2061  * (e.g., `:2`) a
-00012d80: 7420 7468 6520 656e 6420 6f66 2065 6163  t the end of eac
-00012d90: 6820 4353 5620 6669 6c65 6e61 6d65 2e20  h CSV filename. 
-00012da0: 466f 7220 6578 616d 706c 652c 2069 6620  For example, if 
-00012db0: 7468 6572 6520 6172 6520 7477 6f20 4353  there are two CS
-00012dc0: 5620 6669 6c65 7320 746f 2062 6520 6170  V files to be ap
-00012dd0: 706c 6965 6420 746f 2074 6865 2073 6563  plied to the sec
-00012de0: 6f6e 6420 616e 6420 666f 7572 7468 2054  ond and fourth T
-00012df0: 6173 6b20 4772 6f75 7073 2069 6e20 6120  ask Groups in a 
-00012e00: 4a53 4f4e 2057 6f72 6b20 5265 7175 6972  JSON Work Requir
-00012e10: 656d 656e 742c 2075 7365 2074 6865 2066  ement, use the f
-00012e20: 6f6c 6c6f 7769 6e67 2073 796e 7461 783a  ollowing syntax:
-00012e30: 0a0a 6060 6073 6865 6c6c 0a79 642d 7375  ..```shell.yd-su
-00012e40: 626d 6974 202d 7220 7772 2e6a 736f 6e20  bmit -r wr.json 
-00012e50: 2d56 2077 725f 6461 7461 5f74 6173 6b5f  -V wr_data_task_
-00012e60: 6772 6f75 705f 322e 6373 763a 3220 2d56  group_2.csv:2 -V
-00012e70: 2077 725f 6461 7461 5f74 6173 6b5f 6772   wr_data_task_gr
-00012e80: 6f75 705f 342e 6373 763a 340a 6060 600a  oup_4.csv:4.```.
-00012e90: 0a41 6c74 6572 6e61 7469 7665 6c79 2c20  .Alternatively, 
-00012ea0: 7468 6520 2a2a 5461 736b 2047 726f 7570  the **Task Group
-00012eb0: 206e 616d 652a 2a20 2869 6620 7375 7070   name** (if supp
-00012ec0: 6c69 6564 2069 6e20 7468 6520 4a53 4f4e  lied in the JSON
-00012ed0: 2066 696c 6529 2063 616e 2062 6520 7573   file) can be us
-00012ee0: 6564 2061 7320 7468 6520 706f 7374 6669  ed as the postfi
-00012ef0: 782e 2046 6f72 2065 7861 6d70 6c65 2c20  x. For example, 
-00012f00: 6966 2074 6865 2054 6173 6b20 4772 6f75  if the Task Grou
-00012f10: 7073 2061 626f 7665 2061 7265 206e 616d  ps above are nam
-00012f20: 6564 2060 7467 5f74 776f 6020 616e 6420  ed `tg_two` and 
-00012f30: 6074 675f 666f 7572 602c 2074 6865 2060  `tg_four`, the `
-00012f40: 7964 2d73 7562 6d69 7460 2063 6f6d 6d61  yd-submit` comma
-00012f50: 6e64 2077 6f75 6c64 2062 6563 6f6d 653a  nd would become:
-00012f60: 0a0a 6060 6073 6865 6c6c 0a79 642d 7375  ..```shell.yd-su
-00012f70: 626d 6974 202d 7220 7772 2e6a 736f 6e20  bmit -r wr.json 
-00012f80: 2d56 2077 725f 6461 7461 5f74 6173 6b5f  -V wr_data_task_
-00012f90: 6772 6f75 705f 322e 6373 763a 7467 5f74  group_2.csv:tg_t
-00012fa0: 776f 202d 5620 7772 5f64 6174 615f 7461  wo -V wr_data_ta
-00012fb0: 736b 5f67 726f 7570 5f34 2e63 7376 3a74  sk_group_4.csv:t
-00012fc0: 675f 666f 7572 0a60 6060 0a0a 4e6f 7465  g_four.```..Note
-00012fd0: 2074 6861 7420 6f6e 6c79 206f 6e65 2043   that only one C
-00012fe0: 5356 2066 696c 6520 6361 6e20 6265 2061  SV file can be a
-00012ff0: 7070 6c69 6564 2074 6f20 616e 7920 6769  pplied to any gi
-00013000: 7665 6e20 5461 736b 2047 726f 7570 2e20  ven Task Group. 
-00013010: 4120 7369 6e67 6c65 2043 5356 2066 696c  A single CSV fil
-00013020: 6520 6361 6e2c 2068 6f77 6576 6572 2c20  e can, however, 
-00013030: 6265 2072 6575 7365 6420 666f 7220 6d75  be reused for mu
-00013040: 6c74 6970 6c65 2054 6173 6b20 4772 6f75  ltiple Task Grou
-00013050: 7073 2e0a 0a23 2323 2055 7369 6e67 2043  ps...### Using C
-00013060: 5356 2044 6174 6120 7769 7468 2053 696d  SV Data with Sim
-00013070: 706c 652c 2054 4f4d 4c2d 4f6e 6c79 2057  ple, TOML-Only W
-00013080: 6f72 6b20 5265 7175 6972 656d 656e 7420  ork Requirement 
-00013090: 5370 6563 6966 6963 6174 696f 6e73 0a0a  Specifications..
-000130a0: 4974 2773 2070 6f73 7369 626c 6520 746f  It's possible to
-000130b0: 2075 7365 2054 4f4d 4c20 6578 636c 7573   use TOML exclus
-000130c0: 6976 656c 7920 746f 2064 6572 6976 6520  ively to derive 
-000130d0: 6120 6c69 7374 206f 6620 5461 736b 7320  a list of Tasks 
-000130e0: 6672 6f6d 2043 5356 2064 6174 6120 2d2d  from CSV data --
-000130f0: 2069 2e65 2e2c 2061 204a 534f 4e20 576f   i.e., a JSON Wo
-00013100: 726b 2052 6571 7569 7265 6d65 6e74 2073  rk Requirement s
-00013110: 7065 6369 6669 6361 7469 6f6e 2069 7320  pecification is 
-00013120: 6e6f 7420 7265 7175 6972 6564 2e0a 0a54  not required...T
-00013130: 6f20 6d61 6b65 2075 7365 206f 6620 7468  o make use of th
-00013140: 6973 3a0a 0a31 2e20 456e 7375 7265 2074  is:..1. Ensure t
-00013150: 6861 7420 6e6f 204a 534f 4e20 576f 726b  hat no JSON Work
-00013160: 2052 6571 7569 7265 6d65 6e74 2064 6f63   Requirement doc
-00013170: 756d 656e 7420 6973 2073 7065 6369 6669  ument is specifi
-00013180: 6564 2028 6e6f 2060 776f 726b 5265 7175  ed (no `workRequ
-00013190: 6972 656d 656e 7444 6174 6160 2069 6e20  irementData` in 
-000131a0: 7468 6520 544f 4d4c 2066 696c 652c 206f  the TOML file, o
-000131b0: 7220 602d 2d77 6f72 6b2d 7265 7175 6972  r `--work-requir
-000131c0: 656d 656e 7460 206f 6e20 7468 6520 636f  ement` on the co
-000131d0: 6d6d 616e 6420 6c69 6e65 290a 322e 2049  mmand line).2. I
-000131e0: 6e73 6572 7420 7468 6520 7265 7175 6972  nsert the requir
-000131f0: 6564 2043 5356 2d73 7570 706c 6965 6420  ed CSV-supplied 
-00013200: 7661 7269 6162 6c65 2073 7562 7374 6974  variable substit
-00013210: 7574 696f 6e73 2064 6972 6563 746c 7920  utions directly 
-00013220: 696e 746f 2074 6865 2054 4f4d 4c20 7072  into the TOML pr
-00013230: 6f70 6572 7469 6573 2c20 652e 672e 2060  operties, e.g. `
-00013240: 6172 6775 6d65 6e74 7320 3d20 5b22 7b7b  arguments = ["{{
-00013250: 6172 675f 317d 7d22 2c20 227b 7b61 7267  arg_1}}", "{{arg
-00013260: 5f32 7d7d 225d 600a 332e 2053 7065 6369  _2}}"]`.3. Speci
-00013270: 6679 2061 2073 696e 676c 6520 4353 5620  fy a single CSV 
-00013280: 6669 6c65 2069 6e20 7468 6520 6063 7376  file in the `csv
-00013290: 4669 6c65 7360 2054 4f4d 4c20 7072 6f70  Files` TOML prop
-000132a0: 6572 7479 2c20 652e 672e 2060 6373 7646  erty, e.g. `csvF
-000132b0: 696c 6573 203d 205b 2277 725f 6461 7461  iles = ["wr_data
-000132c0: 2e63 7376 225d 602c 206f 7220 7072 6f76  .csv"]`, or prov
-000132d0: 6964 6520 7468 6520 4353 5620 6669 6c65  ide the CSV file
-000132e0: 206f 6e20 7468 6520 636f 6d6d 616e 6420   on the command 
-000132f0: 6c69 6e65 2060 2d56 2077 725f 6461 7461  line `-V wr_data
-00013300: 2e63 7376 600a 0a57 6865 6e20 6079 642d  .csv`..When `yd-
-00013310: 7375 626d 6974 6020 6973 2072 756e 2c20  submit` is run, 
-00013320: 6974 2077 696c 6c20 6578 7061 6e64 2074  it will expand t
-00013330: 6865 2054 6173 6b20 6c69 7374 2074 6f20  he Task list to 
-00013340: 6d61 7463 6820 7468 6520 6e75 6d62 6572  match the number
-00013350: 206f 6620 6461 7461 2072 6f77 7320 696e   of data rows in
-00013360: 2074 6865 2043 5356 2066 696c 652e 0a0a   the CSV file...
-00013370: 2323 2320 496e 7370 6563 7469 6e67 2074  ### Inspecting t
-00013380: 6865 2052 6573 756c 7473 206f 6620 4353  he Results of CS
-00013390: 5620 5661 7269 6162 6c65 2053 7562 7374  V Variable Subst
-000133a0: 6974 7574 696f 6e0a 0a54 6865 2060 2d2d  itution..The `--
-000133b0: 7072 6f63 6573 732d 6373 762d 6f6e 6c79  process-csv-only
-000133c0: 6020 286f 7220 602d 7060 2920 6f70 7469  ` (or `-p`) opti
-000133d0: 6f6e 2063 616e 2062 6520 7573 6564 2077  on can be used w
-000133e0: 6974 6820 6079 642d 7375 626d 6974 6020  ith `yd-submit` 
-000133f0: 746f 206f 7574 7075 7420 7468 6520 4a53  to output the JS
-00013400: 4f4e 2057 6f72 6b20 5265 7175 6972 656d  ON Work Requirem
-00013410: 656e 7420 6166 7465 7220 4353 5620 7661  ent after CSV va
-00013420: 7269 6162 6c65 2073 7562 7374 6974 7574  riable substitut
-00013430: 696f 6e73 206f 6e6c 792c 2070 7269 6f72  ions only, prior
-00013440: 2074 6f20 616c 6c20 6f74 6865 7220 7375   to all other su
-00013450: 6273 7469 7475 7469 6f6e 7320 616e 6420  bstitutions and 
-00013460: 7072 6f70 6572 7479 2069 6e68 6572 6974  property inherit
-00013470: 616e 6365 2061 7070 6c69 6564 2062 7920  ance applied by 
-00013480: 6079 642d 7375 626d 6974 602e 0a0a 2320  `yd-submit`...# 
-00013490: 576f 726b 6572 2050 6f6f 6c20 5072 6f70  Worker Pool Prop
-000134a0: 6572 7469 6573 0a0a 5468 6520 6077 6f72  erties..The `wor
-000134b0: 6b65 7250 6f6f 6c60 2073 6563 7469 6f6e  kerPool` section
-000134c0: 206f 6620 7468 6520 544f 4d4c 2066 696c   of the TOML fil
-000134d0: 6520 6465 6669 6e65 7320 7468 6520 7072  e defines the pr
-000134e0: 6f70 6572 7469 6573 206f 6620 7468 6520  operties of the 
-000134f0: 576f 726b 6572 2050 6f6f 6c20 746f 2062  Worker Pool to b
-00013500: 6520 6372 6561 7465 642c 2061 6e64 2069  e created, and i
-00013510: 7320 7573 6564 2062 7920 7468 6520 6079  s used by the `y
-00013520: 642d 7072 6f76 6973 696f 6e60 2063 6f6d  d-provision` com
-00013530: 6d61 6e64 2e20 4120 7375 6273 6574 206f  mand. A subset o
-00013540: 6620 7468 6520 7072 6f70 6572 7469 6573  f the properties
-00013550: 2069 7320 616c 736f 2075 7365 6420 6279   is also used by
-00013560: 2074 6865 2060 7964 2d69 6e73 7461 6e74   the `yd-instant
-00013570: 6961 7465 6020 636f 6d6d 616e 642c 2066  iate` command, f
-00013580: 6f72 2063 7265 6174 696e 6720 7374 616e  or creating stan
-00013590: 6461 6c6f 6e65 2043 6f6d 7075 7465 2052  dalone Compute R
-000135a0: 6571 7569 7265 6d65 6e74 7320 7468 6174  equirements that
-000135b0: 2061 7265 206e 6f74 2061 7373 6f63 6961   are not associa
-000135c0: 7465 6420 7769 7468 2057 6f72 6b65 7220  ted with Worker 
-000135d0: 506f 6f6c 732e 0a0a 5468 6520 6f6e 6c79  Pools...The only
-000135e0: 206d 616e 6461 746f 7279 2070 726f 7065   mandatory prope
-000135f0: 7274 7920 6973 2060 7465 6d70 6c61 7465  rty is `template
-00013600: 4964 602e 2041 6c6c 206f 7468 6572 2070  Id`. All other p
-00013610: 726f 7065 7274 6965 7320 6861 7665 2064  roperties have d
-00013620: 6566 6175 6c74 7320 286f 7220 6172 6520  efaults (or are 
-00013630: 6e6f 7420 7265 7175 6972 6564 292e 0a0a  not required)...
-00013640: 5468 6520 666f 6c6c 6f77 696e 6720 7072  The following pr
-00013650: 6f70 6572 7469 6573 2061 7265 2061 7661  operties are ava
-00013660: 696c 6162 6c65 3a0a 0a7c 2050 726f 7065  ilable:..| Prope
-00013670: 7274 7920 2020 2020 2020 2020 2020 2020  rty             
-00013680: 2020 2020 207c 2044 6573 6372 6970 7469       | Descripti
-00013690: 6f6e 2020 2020 2020 2020 2020 2020 2020  on              
-000136a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000136b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000136c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000136d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000136e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000136f0: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00013700: 2044 6566 6175 6c74 2020 2020 2020 2020   Default        
-00013710: 2020 2020 2020 2020 207c 0a7c 3a2d 2d2d           |.|:---
-00013720: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00013730: 2d2d 2d2d 2d2d 2d7c 3a2d 2d2d 2d2d 2d2d  -------|:-------
-00013740: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00013750: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00013760: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00013770: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-00013780: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+0000d8a0: 3a20 5b22 6465 762f 6669 6c65 5f31 2e74  : ["dev/file_1.t
+0000d8b0: 7874 225d 202d 3e20 6465 7665 6c6f 706d  xt"] -> developm
+0000d8c0: 656e 743a 3a74 6573 7472 756e 5f32 3231  ent::testrun_221
+0000d8d0: 3130 382d 3132 3034 3034 2d37 6432 2f64  108-120404-7d2/d
+0000d8e0: 6576 2f66 696c 655f 312e 7478 740a 2269  ev/file_1.txt."i
+0000d8f0: 6e70 7574 7322 203a 205b 222f 686f 6d65  nputs" : ["/home
+0000d900: 2f64 6576 2f66 696c 655f 312e 7478 7422  /dev/file_1.txt"
+0000d910: 5d20 2d3e 2064 6576 656c 6f70 6d65 6e74  ] -> development
+0000d920: 3a3a 7465 7374 7275 6e5f 3232 3131 3038  ::testrun_221108
+0000d930: 2d31 3230 3430 342d 3764 322f 686f 6d65  -120404-7d2/home
+0000d940: 2f64 6576 2f66 696c 655f 312e 7478 740a  /dev/file_1.txt.
+0000d950: 2269 6e70 7574 7322 203a 205b 222e 2e2f  "inputs" : ["../
+0000d960: 6465 762f 6669 6c65 5f31 2e74 7874 225d  dev/file_1.txt"]
+0000d970: 202d 3e20 6465 7665 6c6f 706d 656e 743a   -> development:
+0000d980: 3a74 6573 7472 756e 5f32 3231 3130 382d  :testrun_221108-
+0000d990: 3132 3034 3034 2d37 6432 2f31 2f64 6576  120404-7d2/1/dev
+0000d9a0: 2f66 696c 655f 312e 7478 740a 2269 6e70  /file_1.txt."inp
+0000d9b0: 7574 7322 203a 205b 222e 2e2f 2e2e 2f64  uts" : ["../../d
+0000d9c0: 6576 2f66 696c 655f 312e 7478 7422 5d20  ev/file_1.txt"] 
+0000d9d0: 2d3e 2064 6576 656c 6f70 6d65 6e74 3a3a  -> development::
+0000d9e0: 7465 7374 7275 6e5f 3232 3131 3038 2d31  testrun_221108-1
+0000d9f0: 3230 3430 342d 3764 322f 322f 6465 762f  20404-7d2/2/dev/
+0000da00: 6669 6c65 5f31 2e74 7874 0a60 6060 0a0a  file_1.txt.```..
+0000da10: 2a2a 5573 696e 6720 6066 6c61 7474 656e  **Using `flatten
+0000da20: 5570 6c6f 6164 5061 7468 7360 2a2a 0a0a  UploadPaths`**..
+0000da30: 5468 6520 6066 6c61 7474 656e 5570 6c6f  The `flattenUplo
+0000da40: 6164 5061 7468 7360 2070 726f 7065 7274  adPaths` propert
+0000da50: 7920 6361 6e20 6265 2075 7365 6420 746f  y can be used to
+0000da60: 2073 7570 7072 6573 7320 7468 6520 6d69   suppress the mi
+0000da70: 7272 6f72 696e 6720 6f66 2061 6e79 206c  rroring of any l
+0000da80: 6f63 616c 2064 6972 6563 746f 7279 2073  ocal directory s
+0000da90: 7472 7563 7475 7265 2077 6865 6e20 7570  tructure when up
+0000daa0: 6c6f 6164 696e 6720 6669 6c65 7320 746f  loading files to
+0000dab0: 2074 6865 204f 626a 6563 7420 5374 6f72   the Object Stor
+0000dac0: 652e 2049 6620 7365 7420 746f 2060 7472  e. If set to `tr
+0000dad0: 7565 602c 2061 6c6c 2066 696c 6573 2077  ue`, all files w
+0000dae0: 696c 6c20 6265 2075 706c 6f61 6465 6420  ill be uploaded 
+0000daf0: 746f 2074 6865 2072 6f6f 7420 6f66 2074  to the root of t
+0000db00: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
+0000db10: 656e 7420 666f 6c64 6572 2e20 466f 7220  ent folder. For 
+0000db20: 6578 616d 706c 653a 0a0a 6060 6073 6865  example:..```she
+0000db30: 6c6c 0a22 696e 7075 7473 2220 3a20 5b22  ll."inputs" : ["
+0000db40: 6669 6c65 5f31 2e74 7874 225d 202d 3e20  file_1.txt"] -> 
+0000db50: 6465 7665 6c6f 706d 656e 743a 3a74 6573  development::tes
+0000db60: 7472 756e 5f32 3231 3130 382d 3132 3034  trun_221108-1204
+0000db70: 3034 2d37 6432 2f66 696c 655f 312e 7478  04-7d2/file_1.tx
+0000db80: 740a 2269 6e70 7574 7322 203a 205b 2264  t."inputs" : ["d
+0000db90: 6576 2f66 696c 655f 312e 7478 7422 5d20  ev/file_1.txt"] 
+0000dba0: 2d3e 2064 6576 656c 6f70 6d65 6e74 3a3a  -> development::
+0000dbb0: 7465 7374 7275 6e5f 3232 3131 3038 2d31  testrun_221108-1
+0000dbc0: 3230 3430 342d 3764 322f 6669 6c65 5f31  20404-7d2/file_1
+0000dbd0: 2e74 7874 0a22 696e 7075 7473 2220 3a20  .txt."inputs" : 
+0000dbe0: 5b22 2f68 6f6d 652f 6465 762f 6669 6c65  ["/home/dev/file
+0000dbf0: 5f31 2e74 7874 225d 202d 3e20 6465 7665  _1.txt"] -> deve
+0000dc00: 6c6f 706d 656e 743a 3a74 6573 7472 756e  lopment::testrun
+0000dc10: 5f32 3231 3130 382d 3132 3034 3034 2d37  _221108-120404-7
+0000dc20: 6432 2f66 696c 655f 312e 7478 740a 2269  d2/file_1.txt."i
+0000dc30: 6e70 7574 7322 203a 205b 222e 2e2f 6465  nputs" : ["../de
+0000dc40: 762f 6669 6c65 5f31 2e74 7874 225d 202d  v/file_1.txt"] -
+0000dc50: 3e20 6465 7665 6c6f 706d 656e 743a 3a74  > development::t
+0000dc60: 6573 7472 756e 5f32 3231 3130 382d 3132  estrun_221108-12
+0000dc70: 3034 3034 2d37 6432 2f66 696c 655f 312e  0404-7d2/file_1.
+0000dc80: 7478 740a 2269 6e70 7574 7322 203a 205b  txt."inputs" : [
+0000dc90: 222e 2e2f 2e2e 2f64 6576 2f66 696c 655f  "../../dev/file_
+0000dca0: 312e 7478 7422 5d20 2d3e 2064 6576 656c  1.txt"] -> devel
+0000dcb0: 6f70 6d65 6e74 3a3a 7465 7374 7275 6e5f  opment::testrun_
+0000dcc0: 3232 3131 3038 2d31 3230 3430 342d 3764  221108-120404-7d
+0000dcd0: 322f 6669 6c65 5f31 2e74 7874 0a60 6060  2/file_1.txt.```
+0000dce0: 0a0a 5468 6520 7072 6f70 6572 7479 2064  ..The property d
+0000dcf0: 6566 6175 6c74 2069 7320 6066 616c 7365  efault is `false
+0000dd00: 602e 2054 6869 7320 7072 6f70 6572 7479  `. This property
+0000dd10: 202a 2a63 616e 206f 6e6c 7920 6265 2073   **can only be s
+0000dd20: 6574 2061 7420 7468 6520 576f 726b 2052  et at the Work R
+0000dd30: 6571 7569 7265 6d65 6e74 206c 6576 656c  equirement level
+0000dd40: 2a2a 2061 6e64 2077 696c 6c20 7468 6572  ** and will ther
+0000dd50: 6566 6f72 6520 6170 706c 7920 746f 2061  efore apply to a
+0000dd60: 6c6c 2054 6173 6b20 4772 6f75 7073 2061  ll Task Groups a
+0000dd70: 6e64 2054 6173 6b73 2077 6974 6869 6e20  nd Tasks within 
+0000dd80: 6120 576f 726b 2052 6571 7569 7265 6d65  a Work Requireme
+0000dd90: 6e74 2e0a 0a57 6865 6e20 6669 6c65 7320  nt...When files 
+0000dda0: 6170 7065 6172 2069 6e20 7468 6520 6069  appear in the `i
+0000ddb0: 6e70 7574 7360 206c 6973 742c 2074 6865  nputs` list, the
+0000ddc0: 7920 6172 6520 616c 736f 2061 7574 6f6d  y are also autom
+0000ddd0: 6174 6963 616c 6c79 2061 6464 6564 2074  atically added t
+0000dde0: 6f20 7468 6520 6c69 7374 206f 6620 6669  o the list of fi
+0000ddf0: 6c65 7320 7265 7175 6972 6564 2062 7920  les required by 
+0000de00: 7468 6520 7265 6c65 7661 6e74 2054 6173  the relevant Tas
+0000de10: 6b28 7329 2061 7320 6056 6572 6966 7941  k(s) as `VerifyA
+0000de20: 7453 7461 7274 6020 6465 7065 6e64 656e  tStart` dependen
+0000de30: 6369 6573 2e0a 0a23 2323 2320 4669 6c65  cies...#### File
+0000de40: 7320 696e 2074 6865 2060 7570 6c6f 6164  s in the `upload
+0000de50: 4669 6c65 7360 204c 6973 740a 0a54 6865  Files` List..The
+0000de60: 2060 7570 6c6f 6164 4669 6c65 7360 2070   `uploadFiles` p
+0000de70: 726f 7065 7274 7920 616c 6c6f 7773 206d  roperty allows m
+0000de80: 6f72 6520 666c 6578 6962 6c65 2063 6f6e  ore flexible con
+0000de90: 7472 6f6c 206f 7665 7220 7468 6520 6669  trol over the fi
+0000dea0: 6c65 7320 746f 2062 6520 7570 6c6f 6164  les to be upload
+0000deb0: 6564 2066 726f 6d20 6c6f 6361 6c20 7374  ed from local st
+0000dec0: 6f72 6167 6520 746f 2074 6865 204f 626a  orage to the Obj
+0000ded0: 6563 7420 5374 6f72 6520 7768 656e 2060  ect Store when `
+0000dee0: 7964 2d73 7562 6d69 7460 2069 7320 7275  yd-submit` is ru
+0000def0: 6e2e 2054 6865 2070 726f 7065 7274 7920  n. The property 
+0000df00: 6361 6e20 6265 2075 7365 6420 6174 2061  can be used at a
+0000df10: 6c6c 2057 6f72 6b20 5265 7175 6972 656d  ll Work Requirem
+0000df20: 656e 7420 6c65 7665 6c73 2c20 6672 6f6d  ent levels, from
+0000df30: 2074 6865 2054 4f4d 4c20 6669 6c65 2074   the TOML file t
+0000df40: 6872 6f75 6768 2074 6f20 696e 6469 7669  hrough to indivi
+0000df50: 6475 616c 2054 6173 6b20 7370 6563 6966  dual Task specif
+0000df60: 6963 6174 696f 6e73 2e0a 0a54 6865 2070  ications...The p
+0000df70: 726f 7065 7274 7920 6973 2073 7570 706c  roperty is suppl
+0000df80: 6965 6420 6173 2061 206c 6973 7420 6f66  ied as a list of
+0000df90: 2064 6963 7469 6f6e 6172 7920 6974 656d   dictionary item
+0000dfa0: 732c 2065 6163 6820 6f66 2077 6869 6368  s, each of which
+0000dfb0: 206d 7573 7420 696e 636c 7564 6520 7468   must include th
+0000dfc0: 6520 7072 6f70 6572 7469 6573 2060 6c6f  e properties `lo
+0000dfd0: 6361 6c50 6174 6860 2061 6e64 2060 7570  calPath` and `up
+0000dfe0: 6c6f 6164 5061 7468 602e 200a 0a2d 2060  loadPath`. ..- `
+0000dff0: 6c6f 6361 6c50 6174 6860 2073 7065 6369  localPath` speci
+0000e000: 6669 6573 2074 6865 2070 6174 686e 616d  fies the pathnam
+0000e010: 6520 6f66 2074 6865 2066 696c 6520 6f6e  e of the file on
+0000e020: 206c 6f63 616c 2073 746f 7261 6765 0a2d   local storage.-
+0000e030: 2060 7570 6c6f 6164 5061 7468 6020 7370   `uploadPath` sp
+0000e040: 6563 6966 6965 7320 7468 6520 6e61 6d65  ecifies the name
+0000e050: 2061 6e64 206c 6f63 6174 696f 6e20 6f66   and location of
+0000e060: 2074 6865 2066 696c 6527 7320 6465 7374   the file's dest
+0000e070: 696e 6174 696f 6e20 696e 2074 6865 204f  ination in the O
+0000e080: 626a 6563 7420 5374 6f72 650a 0a46 6f72  bject Store..For
+0000e090: 2065 7861 6d70 6c65 2c20 696e 2054 4f4d   example, in TOM
+0000e0a0: 4c3a 0a60 6060 746f 6d6c 0a75 706c 6f61  L:.```toml.uploa
+0000e0b0: 6446 696c 6573 203d 205b 0a20 2020 207b  dFiles = [.    {
+0000e0c0: 6c6f 6361 6c50 6174 6820 3d20 2266 696c  localPath = "fil
+0000e0d0: 655f 312e 7478 7422 2c20 7570 6c6f 6164  e_1.txt", upload
+0000e0e0: 5061 7468 203d 2022 6669 6c65 5f31 2e74  Path = "file_1.t
+0000e0f0: 7874 227d 2c0a 2020 2020 7b6c 6f63 616c  xt"},.    {local
+0000e100: 5061 7468 203d 2022 6469 725f 322f 6669  Path = "dir_2/fi
+0000e110: 6c65 5f32 2e74 7874 222c 2075 706c 6f61  le_2.txt", uploa
+0000e120: 6450 6174 6820 3d20 223a 3a66 696c 655f  dPath = "::file_
+0000e130: 322e 7478 7422 7d2c 0a20 2020 207b 6c6f  2.txt"},.    {lo
+0000e140: 6361 6c50 6174 6820 3d20 2266 696c 655f  calPath = "file_
+0000e150: 332e 7478 7422 2c20 7570 6c6f 6164 5061  3.txt", uploadPa
+0000e160: 7468 203d 2022 6f74 6865 725f 6e61 6d65  th = "other_name
+0000e170: 7370 6163 653a 3a66 696c 655f 332e 7478  space::file_3.tx
+0000e180: 7422 7d0a 5d0a 6060 600a 416e 6420 696e  t"}.].```.And in
+0000e190: 204a 534f 4e2c 2077 6974 6820 7468 6520   JSON, with the 
+0000e1a0: 7072 6f70 6572 7479 2073 6574 2061 7420  property set at 
+0000e1b0: 7468 6520 5461 736b 206c 6576 656c 2c20  the Task level, 
+0000e1c0: 7468 6520 7361 6d65 2073 7065 6369 6669  the same specifi
+0000e1d0: 6361 7469 6f6e 2077 6f75 6c64 2062 653a  cation would be:
+0000e1e0: 0a60 6060 6a73 6f6e 0a7b 0a20 2022 7461  .```json.{.  "ta
+0000e1f0: 736b 4772 6f75 7073 223a 205b 0a20 2020  skGroups": [.   
+0000e200: 207b 0a20 2020 2020 2022 7461 736b 7322   {.      "tasks"
+0000e210: 3a20 5b0a 2020 2020 2020 2020 7b0a 2020  : [.        {.  
+0000e220: 2020 2020 2020 2020 2275 706c 6f61 6446          "uploadF
+0000e230: 696c 6573 223a 205b 0a20 2020 2020 2020  iles": [.       
+0000e240: 2020 2020 207b 226c 6f63 616c 5061 7468       {"localPath
+0000e250: 223a 2022 6669 6c65 5f31 2e74 7874 222c  ": "file_1.txt",
+0000e260: 2022 7570 6c6f 6164 5061 7468 223a 2022   "uploadPath": "
+0000e270: 6669 6c65 5f31 2e74 7874 227d 2c0a 2020  file_1.txt"},.  
+0000e280: 2020 2020 2020 2020 2020 7b22 6c6f 6361            {"loca
+0000e290: 6c50 6174 6822 3a20 2264 6972 5f32 2f66  lPath": "dir_2/f
+0000e2a0: 696c 655f 322e 7478 7422 2c20 2275 706c  ile_2.txt", "upl
+0000e2b0: 6f61 6450 6174 6822 3a20 223a 3a66 696c  oadPath": "::fil
+0000e2c0: 655f 322e 7478 7422 7d2c 0a20 2020 2020  e_2.txt"},.     
+0000e2d0: 2020 2020 2020 207b 226c 6f63 616c 5061         {"localPa
+0000e2e0: 7468 223a 2022 6669 6c65 5f33 2e74 7874  th": "file_3.txt
+0000e2f0: 222c 2022 7570 6c6f 6164 5061 7468 223a  ", "uploadPath":
+0000e300: 2022 6f74 6865 725f 6e61 6d65 7370 6163   "other_namespac
+0000e310: 653a 3a66 696c 655f 332e 7478 7422 7d0a  e::file_3.txt"}.
+0000e320: 2020 2020 2020 2020 2020 5d0a 2020 2020            ].    
+0000e330: 2020 2020 7d0a 2020 2020 2020 5d0a 2020      }.      ].  
+0000e340: 2020 7d0a 2020 5d0a 7d0a 6060 600a 0a57    }.  ].}.```..W
+0000e350: 6865 6e20 7275 6e6e 696e 6720 7468 6520  hen running the 
+0000e360: 5079 7468 6f6e 2045 7861 6d70 6c65 7320  Python Examples 
+0000e370: 636f 6d6d 616e 6473 206f 6e20 2a2a 5769  commands on **Wi
+0000e380: 6e64 6f77 732a 2a20 686f 7374 732c 206e  ndows** hosts, n
+0000e390: 6f74 6520 7468 6174 2065 6974 6865 7220  ote that either 
+0000e3a0: 5769 6e64 6f77 7320 6f72 2055 6e69 7820  Windows or Unix 
+0000e3b0: 6469 7265 6374 6f72 7920 7365 7061 7261  directory separa
+0000e3c0: 746f 7273 2063 616e 2062 6520 7573 6564  tors can be used
+0000e3d0: 2066 6f72 2074 6865 2060 6c6f 6361 6c50   for the `localP
+0000e3e0: 6174 6860 2070 6174 686e 616d 6573 2028  ath` pathnames (
+0000e3f0: 6f72 2074 6865 2070 6174 686e 616d 6573  or the pathnames
+0000e400: 2069 6e20 6069 6e70 7574 7360 292c 2062   in `inputs`), b
+0000e410: 7574 2074 6865 2055 6e69 7820 636f 6e76  ut the Unix conv
+0000e420: 656e 7469 6f6e 206d 7573 7420 6265 2075  ention must be u
+0000e430: 7365 6420 666f 7220 7468 6520 6075 706c  sed for the `upl
+0000e440: 6f61 6450 6174 6860 206e 616d 6573 2c20  oadPath` names, 
+0000e450: 652e 672e 3a0a 0a60 6060 746f 6d6c 0a75  e.g.:..```toml.u
+0000e460: 706c 6f61 6446 696c 6573 203d 205b 0a20  ploadFiles = [. 
+0000e470: 2020 207b 6c6f 6361 6c50 6174 6820 3d20     {localPath = 
+0000e480: 2264 6972 5f32 5c5c 6669 6c65 5f32 2e74  "dir_2\\file_2.t
+0000e490: 7874 222c 2075 706c 6f61 6450 6174 6820  xt", uploadPath 
+0000e4a0: 3d20 223a 3a6d 795f 6469 7265 6374 6f72  = "::my_director
+0000e4b0: 792f 6669 6c65 5f32 2e74 7874 227d 2c0a  y/file_2.txt"},.
+0000e4c0: 5d0a 6060 600a 0a54 6865 2060 7570 6c6f  ].```..The `uplo
+0000e4d0: 6164 4669 6c65 7360 2070 726f 7065 7274  adFiles` propert
+0000e4e0: 7920 6361 6e20 616c 736f 2062 6520 7365  y can also be se
+0000e4f0: 7420 6174 2074 6865 2057 6f72 6b20 5265  t at the Work Re
+0000e500: 7175 6972 656d 656e 7420 616e 6420 5461  quirement and Ta
+0000e510: 736b 2047 726f 7570 206c 6576 656c 732c  sk Group levels,
+0000e520: 2061 6e64 2070 726f 7065 7274 7920 696e   and property in
+0000e530: 6865 7269 7461 6e63 6520 6f70 6572 6174  heritance operat
+0000e540: 6573 2061 7320 6e6f 726d 616c 2e0a 0a46  es as normal...F
+0000e550: 6f72 2060 7570 6c6f 6164 5061 7468 602c  or `uploadPath`,
+0000e560: 2074 6865 2073 616d 6520 603a 3a60 206e   the same `::` n
+0000e570: 616d 696e 6720 636f 6e76 656e 7469 6f6e  aming convention
+0000e580: 2069 7320 6176 6169 6c61 626c 6520 6173   is available as
+0000e590: 2069 7320 7573 6564 2069 6e20 7468 6520   is used in the 
+0000e5a0: 6076 6572 6966 7941 7453 7461 7274 602c  `verifyAtStart`,
+0000e5b0: 2060 7665 7269 6679 5761 6974 6020 616e   `verifyWait` an
+0000e5c0: 6420 6069 6e70 7574 734f 7074 696f 6e61  d `inputsOptiona
+0000e5d0: 6c60 2070 726f 7065 7274 6965 7320 6469  l` properties di
+0000e5e0: 7363 7573 7365 6420 6265 6c6f 773a 0a0a  scussed below:..
+0000e5f0: 2d20 4966 2060 3a3a 6020 6973 206e 6f74  - If `::` is not
+0000e600: 2075 7365 642c 2074 6865 6e20 7468 6520   used, then the 
+0000e610: 6669 6c65 2069 7320 7570 6c6f 6164 6564  file is uploaded
+0000e620: 2072 656c 6174 6976 6520 746f 2074 6865   relative to the
+0000e630: 2063 7572 7265 6e74 206e 616d 6573 7061   current namespa
+0000e640: 6365 2069 6e20 6120 6469 7265 6374 6f72  ce in a director
+0000e650: 7920 6e61 6d65 6420 6166 7465 7220 7468  y named after th
+0000e660: 6520 6e61 6d65 206f 6620 7468 6520 576f  e name of the Wo
+0000e670: 726b 2052 6571 7569 7265 6d65 6e74 0a2d  rk Requirement.-
+0000e680: 2049 6620 603a 3a60 2069 7320 7573 6564   If `::` is used
+0000e690: 2061 7420 7468 6520 7374 6172 7420 6f66   at the start of
+0000e6a0: 2074 6865 2060 7570 6c6f 6164 5061 7468   the `uploadPath
+0000e6b0: 602c 2074 6865 2066 696c 6520 6973 2075  `, the file is u
+0000e6c0: 706c 6f61 6465 6420 7265 6c61 7469 7665  ploaded relative
+0000e6d0: 2074 6f20 7468 6520 726f 6f74 206f 6620   to the root of 
+0000e6e0: 7468 6520 6375 7272 656e 7420 6e61 6d65  the current name
+0000e6f0: 7370 6163 650a 2d20 4966 2060 3c6e 616d  space.- If `<nam
+0000e700: 6573 7061 6365 3e3a 3a60 2069 7320 7573  espace>::` is us
+0000e710: 6564 2061 7420 7468 6520 7374 6172 7420  ed at the start 
+0000e720: 6f66 2060 7570 6c6f 6164 5061 7468 602c  of `uploadPath`,
+0000e730: 2074 6865 2066 696c 6520 6973 2075 706c   the file is upl
+0000e740: 6f61 6465 6420 7265 6c61 7469 7665 2074  oaded relative t
+0000e750: 6f20 7468 6520 726f 6f74 206f 6620 603c  o the root of `<
+0000e760: 6e61 6d65 7370 6163 653e 600a 0a45 6163  namespace>`..Eac
+0000e770: 6820 6669 6c65 2073 7065 6369 6669 6564  h file specified
+0000e780: 2069 6e20 7468 6520 6075 706c 6f61 6446   in the `uploadF
+0000e790: 696c 6573 6020 6c69 7374 7320 7769 6c6c  iles` lists will
+0000e7a0: 206f 6e6c 7920 6265 2075 706c 6f61 6465   only be uploade
+0000e7b0: 6420 6f6e 6365 2074 6f20 6561 6368 2075  d once to each u
+0000e7c0: 6e69 7175 6520 7570 6c6f 6164 206c 6f63  nique upload loc
+0000e7d0: 6174 696f 6e20 666f 7220 616e 7920 6769  ation for any gi
+0000e7e0: 7665 6e20 696e 766f 6361 7469 6f6e 206f  ven invocation o
+0000e7f0: 6620 6079 642d 7375 626d 6974 602e 0a0a  f `yd-submit`...
+0000e800: 4966 2061 2066 696c 6520 696e 2074 6865  If a file in the
+0000e810: 2060 7570 6c6f 6164 4669 6c65 7360 206c   `uploadFiles` l
+0000e820: 6973 7420 6973 2072 6571 7569 7265 6420  ist is required 
+0000e830: 6279 2061 2054 6173 6b2c 2069 7420 6d75  by a Task, it mu
+0000e840: 7374 2073 6570 6172 6174 656c 7920 6265  st separately be
+0000e850: 2061 6464 6564 2074 6f20 7468 6520 6076   added to the `v
+0000e860: 6572 6966 7941 7453 7461 7274 6020 6f72  erifyAtStart` or
+0000e870: 2060 7665 7269 6679 5761 6974 6020 6c69   `verifyWait` li
+0000e880: 7374 7320 6469 7363 7573 7365 6420 6265  sts discussed be
+0000e890: 6c6f 772e 2054 6869 7320 6973 206e 6f74  low. This is not
+0000e8a0: 2064 6f6e 6520 6175 746f 6d61 7469 6361   done automatica
+0000e8b0: 6c6c 792e 204e 6f74 6520 616c 736f 2074  lly. Note also t
+0000e8c0: 6861 7420 7468 6520 6066 6c61 7474 656e  hat the `flatten
+0000e8d0: 5570 6c6f 6164 5061 7468 7360 2070 726f  UploadPaths` pro
+0000e8e0: 7065 7274 7920 6973 2069 676e 6f72 6564  perty is ignored
+0000e8f0: 2066 6f72 2066 696c 6573 2069 6e20 7468   for files in th
+0000e900: 6520 6075 706c 6f61 6446 696c 6573 6020  e `uploadFiles` 
+0000e910: 6c69 7374 2e0a 0a23 2323 2320 5573 696e  list...#### Usin
+0000e920: 6720 5769 6c64 6361 7264 7320 696e 2074  g Wildcards in t
+0000e930: 6865 2060 7570 6c6f 6164 4669 6c65 7360  he `uploadFiles`
+0000e940: 204c 6973 740a 0a46 696c 6520 616e 6420   List..File and 
+0000e950: 6469 7265 6374 6f72 7920 6e61 6d65 2077  directory name w
+0000e960: 696c 6463 6172 6473 2063 616e 2062 6520  ildcards can be 
+0000e970: 7573 6564 2069 6e20 606c 6f63 616c 5061  used in `localPa
+0000e980: 7468 6020 7072 6f70 6572 7469 6573 2e20  th` properties. 
+0000e990: 4966 2077 696c 6463 6172 6473 2061 7265  If wildcards are
+0000e9a0: 2075 7365 642c 2074 6865 6e20 7468 6520   used, then the 
+0000e9b0: 6075 706c 6f61 6450 6174 6860 2070 726f  `uploadPath` pro
+0000e9c0: 7065 7274 7920 6d75 7374 2065 6e64 2077  perty must end w
+0000e9d0: 6974 6820 6120 602a 602c 2077 6869 6368  ith a `*`, which
+0000e9e0: 2077 696c 6c20 6265 2072 6570 6c61 6365   will be replace
+0000e9f0: 6420 7769 7468 2074 6865 206e 616d 6520  d with the name 
+0000ea00: 6f66 2065 6163 6820 6669 6c65 2074 6861  of each file tha
+0000ea10: 7420 6d61 7463 6865 7320 7468 6520 7769  t matches the wi
+0000ea20: 6c64 6361 7264 2c20 652e 672e 3a0a 0a60  ldcard, e.g.:..`
+0000ea30: 6060 746f 6d6c 0a75 706c 6f61 6446 696c  ``toml.uploadFil
+0000ea40: 6573 203d 205b 0a20 2020 207b 6c6f 6361  es = [.    {loca
+0000ea50: 6c50 6174 6820 3d20 222a 2e73 6822 2c20  lPath = "*.sh", 
+0000ea60: 7570 6c6f 6164 5061 7468 203d 2022 7363  uploadPath = "sc
+0000ea70: 7269 7074 732f 2a22 7d2c 0a20 2020 207b  ripts/*"},.    {
+0000ea80: 6c6f 6361 6c50 6174 6820 3d20 2274 6578  localPath = "tex
+0000ea90: 742f 2a2e 7478 7422 2c20 7570 6c6f 6164  t/*.txt", upload
+0000eaa0: 5061 7468 203d 2022 3a3a 746f 702d 6c65  Path = "::top-le
+0000eab0: 7665 6c2f 2a22 7d2c 0a20 2020 207b 6c6f  vel/*"},.    {lo
+0000eac0: 6361 6c50 6174 6820 3d20 2273 7263 2f2a  calPath = "src/*
+0000ead0: 2e70 7922 2c20 7570 6c6f 6164 5061 7468  .py", uploadPath
+0000eae0: 203d 2022 6f74 6865 722d 6e61 6d65 7370   = "other-namesp
+0000eaf0: 6163 653a 3a2a 227d 2c0a 5d0a 6060 600a  ace::*"},.].```.
+0000eb00: 0a54 6865 2060 2d2d 6472 792d 7275 6e60  .The `--dry-run`
+0000eb10: 2028 602d 4460 2920 6f70 7469 6f6e 2063   (`-D`) option c
+0000eb20: 616e 2062 6520 7573 6564 2077 6974 6820  an be used with 
+0000eb30: 6079 642d 7375 626d 6974 6020 746f 2070  `yd-submit` to p
+0000eb40: 7269 6e74 206f 7574 2074 6865 2066 696c  rint out the fil
+0000eb50: 6573 2074 6861 7420 776f 756c 6420 6265  es that would be
+0000eb60: 2075 706c 6f61 6465 642c 2061 6e64 2074   uploaded, and t
+0000eb70: 6865 6972 2075 706c 6f61 6420 6c6f 6361  heir upload loca
+0000eb80: 7469 6f6e 732e 200a 0a23 2323 2046 696c  tions. ..### Fil
+0000eb90: 6520 4465 7065 6e64 656e 6369 6573 2055  e Dependencies U
+0000eba0: 7369 6e67 2060 7665 7269 6679 4174 5374  sing `verifyAtSt
+0000ebb0: 6172 7460 2061 6e64 2060 7665 7269 6679  art` and `verify
+0000ebc0: 5761 6974 600a 0a49 7427 7320 706f 7373  Wait`..It's poss
+0000ebd0: 6962 6c65 2074 6f20 6d61 6b65 2054 6173  ible to make Tas
+0000ebe0: 6b73 2064 6570 656e 6465 6e74 206f 6e20  ks dependent on 
+0000ebf0: 7468 6520 7072 6573 656e 6365 206f 6620  the presence of 
+0000ec00: 6669 6c65 7320 696e 2074 6865 204f 626a  files in the Obj
+0000ec10: 6563 7420 5374 6f72 6520 6279 2075 7369  ect Store by usi
+0000ec20: 6e67 2074 6865 2060 7665 7269 6679 4174  ng the `verifyAt
+0000ec30: 5374 6172 7460 2061 6e64 2060 7665 7269  Start` and `veri
+0000ec40: 6679 5761 6974 6020 6c69 7374 732e 2054  fyWait` lists. T
+0000ec50: 6865 7365 2066 696c 6573 2061 7265 206e  hese files are n
+0000ec60: 6f74 2061 7574 6f6d 6174 6963 616c 6c79  ot automatically
+0000ec70: 2075 706c 6f61 6465 6420 7768 656e 2075   uploaded when u
+0000ec80: 7369 6e67 2060 7964 2d73 7562 6d69 7460  sing `yd-submit`
+0000ec90: 2073 6f20 6172 6520 7570 6c6f 6164 6564   so are uploaded
+0000eca0: 206d 616e 7561 6c6c 7920 2865 2e67 2e2c   manually (e.g.,
+0000ecb0: 2062 7920 7573 696e 6720 6079 642d 7570   by using `yd-up
+0000ecc0: 6c6f 6164 6029 2c20 7570 6c6f 6164 6564  load`), uploaded
+0000ecd0: 2075 7369 6e67 2074 6865 2060 7570 6c6f   using the `uplo
+0000ece0: 6164 4669 6c65 7360 2070 726f 7065 7274  adFiles` propert
+0000ecf0: 792c 206f 7220 6172 6520 6372 6561 7465  y, or are create
+0000ed00: 6420 6173 2061 2072 6573 756c 7420 6f66  d as a result of
+0000ed10: 2074 6865 2065 7865 6375 7469 6f6e 206f   the execution o
+0000ed20: 6620 6f74 6865 7220 5461 736b 732e 0a0a  f other Tasks...
+0000ed30: 4e6f 7465 2074 6861 7420 6120 6769 7665  Note that a give
+0000ed40: 6e20 6669 6c65 2063 616e 206f 6e6c 7920  n file can only 
+0000ed50: 6170 7065 6172 2069 6e20 2a6f 6e65 2a20  appear in *one* 
+0000ed60: 6f66 2074 6865 2060 696e 7075 7473 602c  of the `inputs`,
+0000ed70: 2060 7665 7269 6679 4174 5374 6172 7460   `verifyAtStart`
+0000ed80: 206f 7220 6076 6572 6966 7957 6169 7460   or `verifyWait`
+0000ed90: 206c 6973 7473 2e0a 0a54 6173 6b73 2077   lists...Tasks w
+0000eda0: 6974 6820 6076 6572 6966 7941 7453 7461  ith `verifyAtSta
+0000edb0: 7274 6020 6465 7065 6e64 656e 6369 6573  rt` dependencies
+0000edc0: 2077 696c 6c20 6661 696c 2069 6d6d 6564   will fail immed
+0000edd0: 6961 7465 6c79 2069 6620 7468 6520 7265  iately if the re
+0000ede0: 7175 6972 6564 2066 696c 6573 2061 7265  quired files are
+0000edf0: 206e 6f74 2070 7265 7365 6e74 2077 6865   not present whe
+0000ee00: 6e20 7468 6520 5461 736b 2069 7320 7375  n the Task is su
+0000ee10: 626d 6974 7465 642e 2054 6173 6b73 2077  bmitted. Tasks w
+0000ee20: 6974 6820 6076 6572 6966 7957 6169 7460  ith `verifyWait`
+0000ee30: 2064 6570 656e 6465 6e63 6965 7320 7769   dependencies wi
+0000ee40: 6c6c 206e 6f74 2062 6563 6f6d 6520 6052  ll not become `R
+0000ee50: 4541 4459 6020 746f 2062 6520 7363 6865  EADY` to be sche
+0000ee60: 6475 6c65 6420 746f 2057 6f72 6b65 7273  duled to Workers
+0000ee70: 2075 6e74 696c 2074 6865 2064 6570 656e   until the depen
+0000ee80: 6465 6e63 6965 7320 6172 6520 7361 7469  dencies are sati
+0000ee90: 7366 6965 642e 0a0a 5768 656e 2073 7065  sfied...When spe
+0000eea0: 6369 6679 696e 6720 6669 6c65 7320 696e  cifying files in
+0000eeb0: 2074 6865 2060 7665 7269 6679 4174 5374   the `verifyAtSt
+0000eec0: 6172 7460 2061 6e64 2060 7665 7269 6679  art` and `verify
+0000eed0: 5761 6974 6020 6c69 7374 732c 2061 7320  Wait` lists, as 
+0000eee0: 7769 7468 2074 6865 2060 7570 6c6f 6164  with the `upload
+0000eef0: 5061 7468 6020 7072 6f70 6572 7479 2064  Path` property d
+0000ef00: 6973 6375 7373 6564 2061 626f 7665 2c20  iscussed above, 
+0000ef10: 7468 6520 6669 6c65 206c 6f63 6174 696f  the file locatio
+0000ef20: 6e73 2063 616e 2062 6520 2831 2920 7265  ns can be (1) re
+0000ef30: 6c61 7469 7665 2074 6f20 7468 6520 576f  lative to the Wo
+0000ef40: 726b 2052 6571 7569 7265 6d65 6e74 206e  rk Requirement n
+0000ef50: 616d 6520 696e 2074 6865 2063 7572 7265  ame in the curre
+0000ef60: 6e74 206e 616d 6573 7061 6365 2028 7468  nt namespace (th
+0000ef70: 6520 6465 6661 756c 7429 2c20 2832 2920  e default), (2) 
+0000ef80: 7265 6c61 7469 7665 2074 6f20 7468 6520  relative to the 
+0000ef90: 726f 6f74 206f 6620 7468 6520 6375 7272  root of the curr
+0000efa0: 656e 7420 6e61 6d65 7370 6163 652c 206f  ent namespace, o
+0000efb0: 7220 2833 2920 7265 6c61 7469 7665 2074  r (3) relative t
+0000efc0: 6f20 7468 6520 726f 6f74 206f 6620 6120  o the root of a 
+0000efd0: 6469 6666 6572 656e 7420 6e61 6d65 7370  different namesp
+0000efe0: 6163 6520 696e 2074 6865 2075 7365 7227  ace in the user'
+0000eff0: 7320 4163 636f 756e 742e 0a0a 312e 2046  s Account...1. F
+0000f000: 6f72 2066 696c 6573 2072 656c 6174 6976  or files relativ
+0000f010: 6520 746f 2074 6865 2057 6f72 6b20 5265  e to the Work Re
+0000f020: 7175 6972 656d 656e 7420 6e61 6d65 2069  quirement name i
+0000f030: 6e20 7468 6520 6375 7272 656e 7420 6e61  n the current na
+0000f040: 6d65 7370 6163 652c 206a 7573 7420 7573  mespace, just us
+0000f050: 6520 7468 6520 6669 6c65 2070 6174 682c  e the file path,
+0000f060: 2065 2e67 2e0a 6060 6073 6865 6c6c 0a22   e.g..```shell."
+0000f070: 7665 7269 6679 5761 6974 223a 205b 2266  verifyWait": ["f
+0000f080: 696c 655f 312e 7478 7422 5d20 2d3e 2064  ile_1.txt"] -> d
+0000f090: 6576 656c 6f70 6d65 6e74 3a74 6573 7472  evelopment:testr
+0000f0a0: 756e 5f32 3231 3130 382d 3132 3034 3034  un_221108-120404
+0000f0b0: 2d37 6432 2f66 696c 655f 312e 7478 740a  -7d2/file_1.txt.
+0000f0c0: 6060 600a 0a32 2e20 466f 7220 6669 6c65  ```..2. For file
+0000f0d0: 7320 7265 6c61 7469 7665 2074 6f20 7468  s relative to th
+0000f0e0: 6520 726f 6f74 206f 6620 7468 6520 6375  e root of the cu
+0000f0f0: 7272 656e 7420 6e61 6d65 7370 6163 652c  rrent namespace,
+0000f100: 2070 7265 6669 7820 7468 6520 6669 6c65   prefix the file
+0000f110: 2070 6174 6820 7769 7468 2060 3a3a 602c   path with `::`,
+0000f120: 2065 2e67 2e0a 6060 6073 6865 6c6c 0a22   e.g..```shell."
+0000f130: 7665 7269 6679 5761 6974 223a 205b 223a  verifyWait": [":
+0000f140: 3a66 696c 655f 312e 7478 7422 5d20 2d3e  :file_1.txt"] ->
+0000f150: 2064 6576 656c 6f70 6d65 6e74 3a66 696c   development:fil
+0000f160: 655f 312e 7478 740a 6060 600a 0a33 2e20  e_1.txt.```..3. 
+0000f170: 466f 7220 6669 6c65 7320 7265 6c61 7469  For files relati
+0000f180: 7665 2074 6f20 7468 6520 726f 6f74 206f  ve to the root o
+0000f190: 6620 6120 6469 6666 6572 656e 7420 6e61  f a different na
+0000f1a0: 6d65 7370 6163 652c 2070 7265 6669 7820  mespace, prefix 
+0000f1b0: 7468 6520 6669 6c65 2070 6174 6820 7769  the file path wi
+0000f1c0: 7468 2074 6865 206e 616d 6573 7061 6365  th the namespace
+0000f1d0: 206e 616d 6520 616e 6420 603a 3a60 2c20   name and `::`, 
+0000f1e0: 652e 672e 0a60 6060 7368 656c 6c0a 2276  e.g..```shell."v
+0000f1f0: 6572 6966 7957 6169 7422 3a20 5b22 6f74  erifyWait": ["ot
+0000f200: 6865 725f 6e61 6d65 7370 6163 653a 3a66  her_namespace::f
+0000f210: 696c 655f 312e 7478 7422 5d20 2d3e 206f  ile_1.txt"] -> o
+0000f220: 7468 6572 5f6e 616d 6573 7061 6365 3a66  ther_namespace:f
+0000f230: 696c 655f 312e 7478 740a 6060 600a 0a54  ile_1.txt.```..T
+0000f240: 6865 2075 7365 206f 6620 7468 6520 7468  he use of the th
+0000f250: 7265 6520 6469 6666 6572 656e 7420 666f  ree different fo
+0000f260: 726d 7320 6361 6e20 6265 206d 6978 6564  rms can be mixed
+0000f270: 2077 6974 6869 6e20 6120 7369 6e67 6c65   within a single
+0000f280: 206c 6973 742c 2065 2e67 2e3a 0a60 6060   list, e.g.:.```
+0000f290: 7368 656c 6c0a 2276 6572 6966 7941 7453  shell."verifyAtS
+0000f2a0: 7461 7274 223a 205b 2266 696c 655f 312e  tart": ["file_1.
+0000f2b0: 7478 7422 2c20 223a 3a64 6972 5f32 2f66  txt", "::dir_2/f
+0000f2c0: 696c 655f 322e 7478 7422 2c20 226f 7468  ile_2.txt", "oth
+0000f2d0: 6572 5f6e 616d 6573 7061 6365 3a3a 6469  er_namespace::di
+0000f2e0: 725f 332f 6669 6c65 5f33 2e74 7874 225d  r_3/file_3.txt"]
+0000f2f0: 0a60 6060 0a0a 2323 2320 4669 6c65 7320  .```..### Files 
+0000f300: 446f 776e 6c6f 6164 6564 2055 7369 6e67  Downloaded Using
+0000f310: 2060 696e 7075 7473 4f70 7469 6f6e 616c   `inputsOptional
+0000f320: 600a 0a54 6865 2060 696e 7075 7473 4f70  `..The `inputsOp
+0000f330: 7469 6f6e 616c 6020 7072 6f70 6572 7479  tional` property
+0000f340: 2077 6f72 6b73 2069 6e20 6120 7369 6d69   works in a simi
+0000f350: 6c61 7220 6661 7368 696f 6e20 746f 2074  lar fashion to t
+0000f360: 6865 2060 7665 7269 6679 2a60 2070 726f  he `verify*` pro
+0000f370: 7065 7274 6965 7320 6162 6f76 652c 2062  perties above, b
+0000f380: 7574 2074 6865 2066 696c 6573 2073 7065  ut the files spe
+0000f390: 6369 6669 6564 2069 6e20 7468 6973 206c  cified in this l
+0000f3a0: 6973 7420 6172 6520 6f70 7469 6f6e 616c  ist are optional
+0000f3b0: 2e20 5468 6973 2070 726f 7065 7274 7920  . This property 
+0000f3c0: 616c 736f 2061 6c6c 6f77 7320 666f 7220  also allows for 
+0000f3d0: 7468 6520 7573 6520 6f66 2077 696c 6463  the use of wildc
+0000f3e0: 6172 6473 2060 2a60 2061 6e64 2060 2a2a  ards `*` and `**
+0000f3f0: 6020 746f 2063 6f6c 6c65 6374 2066 696c  ` to collect fil
+0000f400: 6573 2075 7369 6e67 2077 696c 6463 6172  es using wildcar
+0000f410: 6420 7061 7468 732e 2054 6865 202a 2a61  d paths. The **a
+0000f420: 6e74 2a2a 2063 6f6e 7665 6e74 696f 6e73  nt** conventions
+0000f430: 2061 7265 2075 7365 6420 666f 7220 7468   are used for th
+0000f440: 6573 6520 7769 6c64 6361 7264 732e 0a0a  ese wildcards...
+0000f450: 2323 2320 4669 6c65 7320 446f 776e 6c6f  ### Files Downlo
+0000f460: 6164 6564 2074 6f20 6120 4e6f 6465 2066  aded to a Node f
+0000f470: 6f72 2075 7365 2069 6e20 5461 736b 2045  or use in Task E
+0000f480: 7865 6375 7469 6f6e 0a0a 5768 656e 2061  xecution..When a
+0000f490: 2054 6173 6b20 6973 2065 7865 6375 7465   Task is execute
+0000f4a0: 6420 6279 2061 2057 6f72 6b65 7220 6f6e  d by a Worker on
+0000f4b0: 2061 204e 6f64 652c 2069 7473 2072 6571   a Node, its req
+0000f4c0: 7569 7265 6420 6669 6c65 7320 6172 6520  uired files are 
+0000f4d0: 646f 776e 6c6f 6164 6564 2066 726f 6d20  downloaded from 
+0000f4e0: 7468 6520 4f62 6a65 6374 2053 746f 7265  the Object Store
+0000f4f0: 2070 7269 6f72 2074 6f20 5461 736b 2065   prior to Task e
+0000f500: 7865 6375 7469 6f6e 2e20 416e 7920 6669  xecution. Any fi
+0000f510: 6c65 206c 6973 7465 6420 696e 2074 6865  le listed in the
+0000f520: 2060 696e 7075 7473 6020 666f 7220 6120   `inputs` for a 
+0000f530: 5461 736b 2069 7320 6173 7375 6d65 6420  Task is assumed 
+0000f540: 746f 2062 6520 7265 7175 6972 6564 2c20  to be required, 
+0000f550: 616c 6f6e 6720 7769 7468 2061 6e79 2061  along with any a
+0000f560: 6464 6974 696f 6e61 6c20 6669 6c65 7320  dditional files 
+0000f570: 7370 6563 6966 6965 6420 696e 2074 6865  specified in the
+0000f580: 2060 7665 7269 6679 4174 5374 6172 7460   `verifyAtStart`
+0000f590: 2061 6e64 2060 7665 7269 6679 5761 6974   and `verifyWait
+0000f5a0: 6020 6c69 7374 732e 2046 696c 6573 2073  ` lists. Files s
+0000f5b0: 7065 6369 6669 6564 2075 7369 6e67 2074  pecified using t
+0000f5c0: 6865 2060 696e 7075 7473 4f70 7469 6f6e  he `inputsOption
+0000f5d0: 616c 6020 7072 6f70 6572 7479 2061 7265  al` property are
+0000f5e0: 206f 7074 696f 6e61 6c6c 7920 646f 776e   optionally down
+0000f5f0: 6c6f 6164 6564 2066 726f 6d20 7468 6520  loaded from the 
+0000f600: 4f62 6a65 6374 2053 746f 7265 2e20 284e  Object Store. (N
+0000f610: 6f74 6520 7468 6174 2061 2066 696c 6520  ote that a file 
+0000f620: 7368 6f75 6c64 206f 6e6c 7920 6170 7065  should only appe
+0000f630: 6172 2069 6e20 6f6e 6520 6f66 2074 6865  ar in one of the
+0000f640: 7365 2066 6f75 7220 6c69 7374 732c 206f  se four lists, o
+0000f650: 7468 6572 7769 7365 2060 7964 2d73 7562  therwise `yd-sub
+0000f660: 6d69 7460 2077 696c 6c20 7265 7475 726e  mit` will return
+0000f670: 2061 6e20 6572 726f 722e 290a 0a57 6865   an error.)..Whe
+0000f680: 6e20 6120 5461 736b 2069 7320 7374 6172  n a Task is star
+0000f690: 7465 6420 6279 2074 6865 2041 6765 6e74  ted by the Agent
+0000f6a0: 2c20 6974 7320 776f 726b 696e 6720 6469  , its working di
+0000f6b0: 7265 6374 6f72 7920 6861 7320 6120 7061  rectory has a pa
+0000f6c0: 7474 6572 6e20 736f 6d65 7468 696e 6720  ttern something 
+0000f6d0: 6c69 6b65 3a0a 0a60 2f76 6172 2f6f 7074  like:..`/var/opt
+0000f6e0: 2f79 656c 6c6f 7764 6f67 2f79 642d 6167  /yellowdog/yd-ag
+0000f6f0: 656e 742d 342f 6461 7461 2f77 6f72 6b65  ent-4/data/worke
+0000f700: 7273 2f31 2f79 6469 645f 7461 736b 5f44  rs/1/ydid_task_D
+0000f710: 3044 3044 305f 3638 6635 6535 6265 2d64  0D0D0_68f5e5be-d
+0000f720: 6339 332d 3439 6562 2d61 3832 342d 3166  c93-49eb-a824-1f
+0000f730: 6364 6235 3266 3931 3935 5f31 5f31 600a  cdb52f9195_1_1`.
+0000f740: 0a28 6079 6469 645f 7461 736b 5f44 3044  .(`ydid_task_D0D
+0000f750: 3044 305f 3638 6635 6535 6265 2d64 6339  0D0_68f5e5be-dc9
+0000f760: 332d 3439 6562 2d61 3832 342d 3166 6364  3-49eb-a824-1fcd
+0000f770: 6235 3266 3931 3935 5f31 5f31 6020 6973  b52f9195_1_1` is
+0000f780: 2061 6e20 6570 6865 6d65 7261 6c20 6469   an ephemeral di
+0000f790: 7265 6374 6f72 7920 7468 6174 2069 7320  rectory that is 
+0000f7a0: 7265 6d6f 7665 6420 6166 7465 7220 7468  removed after th
+0000f7b0: 6520 5461 736b 2066 696e 6973 6865 7320  e Task finishes 
+0000f7c0: 616e 6420 616e 7920 6f75 7470 7574 7320  and any outputs 
+0000f7d0: 6861 7665 2062 6565 6e20 7570 6c6f 6164  have been upload
+0000f7e0: 6564 2e29 0a0a 4669 6c65 7320 7468 6174  ed.)..Files that
+0000f7f0: 2061 7265 2064 6f77 6e6c 6f61 6465 6420   are downloaded 
+0000f800: 6279 2074 6865 2041 6765 6e74 2070 7269  by the Agent pri
+0000f810: 6f72 2074 6f20 5461 736b 2065 7865 6375  or to Task execu
+0000f820: 7469 6f6e 2061 7265 206c 6f63 6174 6564  tion are located
+0000f830: 2061 7320 666f 6c6c 6f77 733a 0a0a 312e   as follows:..1.
+0000f840: 2049 6620 7468 6520 6066 6c61 7474 656e   If the `flatten
+0000f850: 496e 7075 7450 6174 6873 6020 7072 6f70  InputPaths` prop
+0000f860: 6572 7479 2069 7320 7365 7420 746f 2074  erty is set to t
+0000f870: 6865 2064 6566 6175 6c74 206f 6620 6066  he default of `f
+0000f880: 616c 7365 6020 666f 7220 7468 6520 5461  alse` for the Ta
+0000f890: 736b 2c20 7468 6520 646f 776e 6c6f 6164  sk, the download
+0000f8a0: 6564 206f 626a 6563 7473 2061 7265 2070  ed objects are p
+0000f8b0: 6c61 6365 6420 696e 2073 7562 6469 7265  laced in subdire
+0000f8c0: 6374 6f72 6965 7320 7468 6174 206d 6972  ctories that mir
+0000f8d0: 726f 7220 7468 6f73 6520 696e 2074 6865  ror those in the
+0000f8e0: 204f 626a 6563 7420 5374 6f72 652c 2069   Object Store, i
+0000f8f0: 6e63 6c75 6469 6e67 2074 6865 2057 6f72  ncluding the Wor
+0000f900: 6b20 5265 7175 6972 656d 656e 7420 6e61  k Requirement na
+0000f910: 6d65 2c20 7369 7475 6174 6564 2062 656e  me, situated ben
+0000f920: 6561 7468 2074 6865 2077 6f72 6b69 6e67  eath the working
+0000f930: 2064 6972 6563 746f 7279 2e0a 0a0a 322e   directory....2.
+0000f940: 2049 6620 7468 6520 6066 6c61 7474 656e   If the `flatten
+0000f950: 496e 7075 7450 6174 6873 6020 7072 6f70  InputPaths` prop
+0000f960: 6572 7479 2069 7320 7365 7420 746f 2060  erty is set to `
+0000f970: 7472 7565 6020 666f 7220 7468 6520 5461  true` for the Ta
+0000f980: 736b 2c20 7468 6520 646f 776e 6c6f 6164  sk, the download
+0000f990: 6564 206f 626a 6563 7473 2061 7265 2061  ed objects are a
+0000f9a0: 6c6c 2070 6c61 6365 6420 6469 7265 6374  ll placed direct
+0000f9b0: 6c79 2069 6e20 726f 6f74 206f 6620 7468  ly in root of th
+0000f9c0: 6520 5461 736b 2773 2077 6f72 6b69 6e67  e Task's working
+0000f9d0: 2064 6972 6563 746f 7279 2e0a 0a46 6f72   directory...For
+0000f9e0: 2065 7861 6d70 6c65 3a0a 0a60 6060 7368   example:..```sh
+0000f9f0: 656c 6c0a 4966 2074 6865 2072 6571 7569  ell.If the requi
+0000fa00: 7265 6420 6f62 6a65 6374 2069 733a 2064  red object is: d
+0000fa10: 6576 656c 6f70 6d65 6e74 3a3a 7465 7374  evelopment::test
+0000fa20: 7275 6e5f 3232 3131 3038 2d31 3230 3430  run_221108-12040
+0000fa30: 342d 3764 322f 6465 762f 6669 6c65 5f31  4-7d2/dev/file_1
+0000fa40: 2e74 7874 0a0a 7468 656e 2c20 6966 2066  .txt..then, if f
+0000fa50: 6c61 7474 656e 496e 7075 7450 6174 6873  lattenInputPaths
+0000fa60: 2069 7320 6661 6c73 652c 2074 6865 2066   is false, the f
+0000fa70: 696c 6520 7769 6c6c 2062 6520 666f 756e  ile will be foun
+0000fa80: 6420 6174 3a0a 202d 3e20 3c77 6f72 6b69  d at:. -> <worki
+0000fa90: 6e67 5f64 6972 6563 746f 7279 3e2f 7465  ng_directory>/te
+0000faa0: 7374 7275 6e5f 3232 3131 3038 2d31 3230  strun_221108-120
+0000fab0: 3430 342d 3764 322f 6465 762f 6669 6c65  404-7d2/dev/file
+0000fac0: 5f31 2e74 7874 0a20 0a65 6c73 652c 2069  _1.txt. .else, i
+0000fad0: 6620 666c 6174 7465 6e49 6e70 7574 5061  f flattenInputPa
+0000fae0: 7468 7320 6973 2074 7275 652c 2074 6865  ths is true, the
+0000faf0: 2066 696c 6520 7769 6c6c 2062 6520 666f   file will be fo
+0000fb00: 756e 6420 6174 3a0a 202d 3e20 3c77 6f72  und at:. -> <wor
+0000fb10: 6b69 6e67 5f64 6972 6563 746f 7279 3e2f  king_directory>/
+0000fb20: 6669 6c65 5f31 2e74 7874 200a 200a 7768  file_1.txt . .wh
+0000fb30: 6572 6520 3c77 6f72 6b69 6e67 5f64 6972  ere <working_dir
+0000fb40: 6563 746f 7279 3e20 6973 3a0a 2020 2f76  ectory> is:.  /v
+0000fb50: 6172 2f6f 7074 2f79 656c 6c6f 7764 6f67  ar/opt/yellowdog
+0000fb60: 2f79 642d 6167 656e 742d 342f 6461 7461  /yd-agent-4/data
+0000fb70: 2f77 6f72 6b65 7273 2f31 2f79 6469 645f  /workers/1/ydid_
+0000fb80: 7461 736b 5f44 3044 3044 305f 3638 6635  task_D0D0D0_68f5
+0000fb90: 6535 6265 2d64 6339 332d 3439 6562 2d61  e5be-dc93-49eb-a
+0000fba0: 3832 342d 3166 6364 6235 3266 3931 3935  824-1fcdb52f9195
+0000fbb0: 5f31 5f31 2f0a 6060 600a 0a4e 6f74 6520  _1_1/.```..Note 
+0000fbc0: 7468 6174 2074 6865 2057 6f72 6b20 5265  that the Work Re
+0000fbd0: 7175 6972 656d 656e 7420 6e61 6d65 2028  quirement name (
+0000fbe0: 652e 672e 2c20 6074 6573 7472 756e 5f32  e.g., `testrun_2
+0000fbf0: 3231 3130 382d 3132 3034 3034 2d37 6432  21108-120404-7d2
+0000fc00: 6029 2069 7320 6176 6169 6c61 626c 6520  `) is available 
+0000fc10: 7669 6120 7468 6520 7661 7269 6162 6c65  via the variable
+0000fc20: 2073 7562 7374 6974 7574 696f 6e20 6077   substitution `w
+0000fc30: 725f 6e61 6d65 602c 2073 6f20 7468 6973  r_name`, so this
+0000fc40: 2063 6f75 6c64 2062 6520 7375 7070 6c69   could be suppli
+0000fc50: 6564 2074 6f20 7468 6520 5461 736b 2074  ed to the Task t
+0000fc60: 6f20 6865 6c70 2069 7420 6c6f 6361 7465  o help it locate
+0000fc70: 2069 7473 2064 6f77 6e6c 6f61 6465 6420   its downloaded 
+0000fc80: 6669 6c65 732e 2046 6f72 2065 7861 6d70  files. For examp
+0000fc90: 6c65 2c20 696e 2074 6865 2060 776f 726b  le, in the `work
+0000fca0: 5265 7175 6972 656d 656e 7460 2073 6563  Requirement` sec
+0000fcb0: 7469 6f6e 206f 6620 7468 6520 6063 6f6e  tion of the `con
+0000fcc0: 6669 672e 746f 6d6c 6020 6669 6c65 2c20  fig.toml` file, 
+0000fcd0: 4920 636f 756c 6420 7370 6563 6966 793a  I could specify:
+0000fce0: 0a0a 6060 6074 6f6d 6c0a 656e 7669 726f  ..```toml.enviro
+0000fcf0: 6e6d 656e 7420 3d20 7b57 525f 4449 5245  nment = {WR_DIRE
+0000fd00: 4354 4f52 5920 3d20 227b 7b77 725f 6e61  CTORY = "{{wr_na
+0000fd10: 6d65 7d7d 227d 0a60 6060 0a0a 5468 6520  me}}"}.```..The 
+0000fd20: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+0000fd30: 206e 616d 6520 776f 756c 6420 7468 656e   name would then
+0000fd40: 2062 6520 6176 6169 6c61 626c 6520 746f   be available to
+0000fd50: 2074 6865 2054 6173 6b20 696e 2074 6865   the Task in the
+0000fd60: 2065 6e76 6972 6f6e 6d65 6e74 2076 6172   environment var
+0000fd70: 6961 626c 6520 6024 5752 5f44 4952 4543  iable `$WR_DIREC
+0000fd80: 544f 5259 602e 0a0a 2323 2320 4669 6c65  TORY`...### File
+0000fd90: 7320 5570 6c6f 6164 6564 2066 726f 6d20  s Uploaded from 
+0000fda0: 6120 4e6f 6465 2074 6f20 7468 6520 4f62  a Node to the Ob
+0000fdb0: 6a65 6374 2053 746f 7265 2061 6674 6572  ject Store after
+0000fdc0: 2054 6173 6b20 4578 6563 7574 696f 6e0a   Task Execution.
+0000fdd0: 0a41 6674 6572 2054 6173 6b20 636f 6d70  .After Task comp
+0000fde0: 6c65 7469 6f6e 2c20 7468 6520 4167 656e  letion, the Agen
+0000fdf0: 7420 7769 6c6c 2075 706c 6f61 6420 7370  t will upload sp
+0000fe00: 6563 6966 6965 6420 6f75 7470 7574 2066  ecified output f
+0000fe10: 696c 6573 2074 6f20 7468 6520 4f62 6a65  iles to the Obje
+0000fe20: 6374 2053 746f 7265 2e20 5468 6520 6669  ct Store. The fi
+0000fe30: 6c65 7320 746f 2062 6520 7570 6c6f 6164  les to be upload
+0000fe40: 6564 2061 7265 2074 686f 7365 206c 6973  ed are those lis
+0000fe50: 7465 6420 696e 2074 6865 2060 6f75 7470  ted in the `outp
+0000fe60: 7574 7360 2061 6e64 2060 6f75 7470 7574  uts` and `output
+0000fe70: 7352 6571 7569 7265 6460 2070 726f 7065  sRequired` prope
+0000fe80: 7274 6965 7320 666f 7220 7468 6520 5461  rties for the Ta
+0000fe90: 736b 2e0a 0a49 6e20 6164 6469 7469 6f6e  sk...In addition
+0000fea0: 2c20 7468 6520 636f 6e73 6f6c 6520 6f75  , the console ou
+0000feb0: 7470 7574 206f 6620 7468 6520 5461 736b  tput of the Task
+0000fec0: 2069 7320 6361 7074 7572 6564 2069 6e20   is captured in 
+0000fed0: 6120 6669 6c65 2063 616c 6c65 6420 6074  a file called `t
+0000fee0: 6173 6b6f 7574 7075 742e 7478 7460 2069  askoutput.txt` i
+0000fef0: 6e20 7468 6520 726f 6f74 206f 6620 7468  n the root of th
+0000ff00: 6520 5461 736b 2773 2077 6f72 6b69 6e67  e Task's working
+0000ff10: 2064 6972 6563 746f 7279 2e20 5768 6574   directory. Whet
+0000ff20: 6865 7220 7468 6520 6074 6173 6b6f 7574  her the `taskout
+0000ff30: 7075 742e 7478 7460 2066 696c 6520 6973  put.txt` file is
+0000ff40: 2075 706c 6f61 6465 6420 746f 2074 6865   uploaded to the
+0000ff50: 204f 626a 6563 7420 5374 6f72 6520 6973   Object Store is
+0000ff60: 2064 6574 6572 6d69 6e65 6420 6279 2074   determined by t
+0000ff70: 6865 2060 6361 7074 7572 6554 6173 6b4f  he `captureTaskO
+0000ff80: 7574 7075 7460 2070 726f 7065 7274 7920  utput` property 
+0000ff90: 666f 7220 7468 6520 5461 736b 2c20 616e  for the Task, an
+0000ffa0: 6420 7468 6973 2069 7320 7365 7420 746f  d this is set to
+0000ffb0: 2027 7472 7565 2720 6279 2064 6566 6175   'true' by defau
+0000ffc0: 6c74 2e0a 0a49 6620 5461 736b 206f 7574  lt...If Task out
+0000ffd0: 7075 7473 2061 7265 2063 7265 6174 6564  puts are created
+0000ffe0: 2069 6e20 7375 6264 6972 6563 746f 7269   in subdirectori
+0000fff0: 6573 2062 656c 6f77 2074 6865 2054 6173  es below the Tas
+00010000: 6b27 7320 776f 726b 696e 6720 6469 7265  k's working dire
+00010010: 6374 6f72 792c 2069 6e63 6c75 6465 2074  ctory, include t
+00010020: 6865 2064 6972 6563 746f 7269 6573 2066  he directories f
+00010030: 6f72 2066 696c 6573 2069 6e20 7468 6520  or files in the 
+00010040: 606f 7574 7075 7473 6020 7072 6f70 6572  `outputs` proper
+00010050: 7479 2e20 452e 672e 2c20 6966 2061 2054  ty. E.g., if a T
+00010060: 6173 6b20 6372 6561 7465 7320 6669 6c65  ask creates file
+00010070: 7320 6072 6573 756c 7473 2f6f 7065 6e66  s `results/openf
+00010080: 6f61 6d2e 7461 722e 677a 6020 616e 6420  oam.tar.gz` and 
+00010090: 6072 6573 756c 7473 2f6f 7065 6e66 6f61  `results/openfoa
+000100a0: 6d2e 6c6f 6760 2c20 7468 656e 2073 7065  m.log`, then spe
+000100b0: 6369 6679 2074 6865 7365 2066 6f72 2075  cify these for u
+000100c0: 706c 6f61 6420 696e 2074 6865 2060 6f75  pload in the `ou
+000100d0: 7470 7574 7360 2070 726f 7065 7274 7920  tputs` property 
+000100e0: 6173 2066 6f6c 6c6f 7773 3a0a 0a60 226f  as follows:..`"o
+000100f0: 7574 7075 7473 223a 205b 2272 6573 756c  utputs": ["resul
+00010100: 7473 2f6f 7065 6e66 6f61 6d2e 7461 722e  ts/openfoam.tar.
+00010110: 677a 222c 2022 7265 7375 6c74 732f 6f70  gz", "results/op
+00010120: 656e 666f 616d 2e6c 6f67 225d 600a 0a57  enfoam.log"]`..W
+00010130: 6865 6e20 6f75 7470 7574 2066 696c 6573  hen output files
+00010140: 2061 7265 2075 706c 6f61 6465 6420 746f   are uploaded to
+00010150: 2074 6865 204f 626a 6563 7420 5374 6f72   the Object Stor
+00010160: 652c 2074 6865 7920 6172 6520 706c 6163  e, they are plac
+00010170: 6564 2069 6e20 6120 5461 736b 2047 726f  ed in a Task Gro
+00010180: 7570 2061 6e64 2054 6173 6b20 7370 6563  up and Task spec
+00010190: 6966 6963 2064 6972 6563 746f 7279 2e20  ific directory. 
+000101a0: 536f 2c20 6966 2074 6865 204e 616d 6573  So, if the Names
+000101b0: 7061 6365 2069 7320 6064 6576 656c 6f70  pace is `develop
+000101c0: 6d65 6e74 602c 2074 6865 2057 6f72 6b20  ment`, the Work 
+000101d0: 5265 7175 6972 656d 656e 7420 6973 2060  Requirement is `
+000101e0: 7465 7374 7275 6e5f 3232 3131 3038 2d31  testrun_221108-1
+000101f0: 3230 3430 342d 3764 3260 2c20 7468 6520  20404-7d2`, the 
+00010200: 5461 736b 2047 726f 7570 2069 7320 6074  Task Group is `t
+00010210: 6173 6b5f 6772 6f75 705f 3160 2061 6e64  ask_group_1` and
+00010220: 2074 6865 2054 6173 6b20 6973 2060 7461   the Task is `ta
+00010230: 736b 5f31 602c 2074 6865 6e20 7468 6520  sk_1`, then the 
+00010240: 6669 6c65 7320 6162 6f76 6520 776f 756c  files above woul
+00010250: 6420 6265 2075 706c 6f61 6465 6420 746f  d be uploaded to
+00010260: 2074 6865 204f 626a 6563 7420 5374 6f72   the Object Stor
+00010270: 6520 6173 2066 6f6c 6c6f 7773 3a0a 0a60  e as follows:..`
+00010280: 6060 7368 656c 6c0a 6465 7665 6c6f 706d  ``shell.developm
+00010290: 656e 743a 3a74 6573 7472 756e 5f32 3231  ent::testrun_221
+000102a0: 3130 382d 3132 3034 3034 2d37 6432 2f74  108-120404-7d2/t
+000102b0: 6173 6b5f 6772 6f75 705f 312f 7461 736b  ask_group_1/task
+000102c0: 5f31 2f72 6573 756c 7473 2f6f 7065 6e66  _1/results/openf
+000102d0: 6f61 6d2e 7461 722e 677a 0a64 6576 656c  oam.tar.gz.devel
+000102e0: 6f70 6d65 6e74 3a3a 7465 7374 7275 6e5f  opment::testrun_
+000102f0: 3232 3131 3038 2d31 3230 3430 342d 3764  221108-120404-7d
+00010300: 322f 7461 736b 5f67 726f 7570 5f31 2f74  2/task_group_1/t
+00010310: 6173 6b5f 312f 7265 7375 6c74 732f 6f70  ask_1/results/op
+00010320: 656e 666f 616d 2e6c 6f67 0a64 6576 656c  enfoam.log.devel
+00010330: 6f70 6d65 6e74 3a3a 7465 7374 7275 6e5f  opment::testrun_
+00010340: 3232 3131 3038 2d31 3230 3430 342d 3764  221108-120404-7d
+00010350: 322f 7461 736b 5f67 726f 7570 5f31 2f74  2/task_group_1/t
+00010360: 6173 6b5f 312f 7461 736b 6f75 7470 7574  ask_1/taskoutput
+00010370: 2e74 7874 0a60 6060 0a0a 5468 6520 2a2a  .txt.```..The **
+00010380: 606f 7574 7075 7473 5265 7175 6972 6564  `outputsRequired
+00010390: 602a 2a20 7072 6f70 6572 7479 2063 616e  `** property can
+000103a0: 2062 6520 7573 6564 2069 6e73 7465 6164   be used instead
+000103b0: 206f 6620 286f 7220 696e 2061 6464 6974   of (or in addit
+000103c0: 696f 6e20 746f 2920 7468 6520 606f 7574  ion to) the `out
+000103d0: 7075 7473 6020 7072 6f70 6572 7479 2c20  puts` property, 
+000103e0: 6966 2074 6865 206f 7574 7075 7420 6669  if the output fi
+000103f0: 6c65 2873 2920 2a2a 6d75 7374 2a2a 2062  le(s) **must** b
+00010400: 6520 6176 6169 6c61 626c 6520 666f 7220  e available for 
+00010410: 7570 6c6f 6164 2074 6f20 7468 6520 4f62  upload to the Ob
+00010420: 6a65 6374 2053 746f 7265 2061 7420 7468  ject Store at th
+00010430: 6520 636f 6e63 6c75 7369 6f6e 206f 6620  e conclusion of 
+00010440: 7468 6520 5461 736b 206f 7220 7468 6520  the Task or the 
+00010450: 5461 736b 2077 696c 6c20 6265 206d 6172  Task will be mar
+00010460: 6b65 6420 6173 2060 4661 696c 6564 602c  ked as `Failed`,
+00010470: 2065 2e67 2e3a 0a0a 6022 6f75 7470 7574   e.g.:..`"output
+00010480: 7352 6571 7569 7265 6422 3a20 5b22 7265  sRequired": ["re
+00010490: 7375 6c74 732f 7072 6f63 6573 735f 6f75  sults/process_ou
+000104a0: 7470 7574 2e74 7874 225d 600a 0a23 2323  tput.txt"]`..###
+000104b0: 2046 696c 6573 2044 6f77 6e6c 6f61 6465   Files Downloade
+000104c0: 6420 6672 6f6d 2074 6865 204f 626a 6563  d from the Objec
+000104d0: 7420 5374 6f72 6520 746f 204c 6f63 616c  t Store to Local
+000104e0: 2053 746f 7261 6765 0a0a 5468 6520 6079   Storage..The `y
+000104f0: 642d 646f 776e 6c6f 6164 6020 636f 6d6d  d-download` comm
+00010500: 616e 6420 7769 6c6c 2064 6f77 6e6c 6f61  and will downloa
+00010510: 6420 616c 6c20 6f62 6a65 6374 7320 6672  d all objects fr
+00010520: 6f6d 2074 6865 204f 626a 6563 7420 5374  om the Object St
+00010530: 6f72 6520 746f 2061 206c 6f63 616c 2064  ore to a local d
+00010540: 6972 6563 746f 7279 2c20 6f6e 2061 2070  irectory, on a p
+00010550: 6572 2057 6f72 6b20 5265 7175 6972 656d  er Work Requirem
+00010560: 656e 7420 6261 7369 7320 2869 6e63 6c75  ent basis (inclu
+00010570: 6469 6e67 2061 6e79 2066 696c 6573 2074  ding any files t
+00010580: 6861 7420 6861 7665 2062 6565 6e20 7570  hat have been up
+00010590: 6c6f 6164 6564 292e 2041 206c 6f63 616c  loaded). A local
+000105a0: 2064 6972 6563 746f 7279 2069 7320 6372   directory is cr
+000105b0: 6561 7465 6420 7769 7468 2074 6865 2073  eated with the s
+000105c0: 616d 6520 6e61 6d65 2061 7320 7468 6520  ame name as the 
+000105d0: 4e61 6d65 7370 6163 6520 616e 6420 636f  Namespace and co
+000105e0: 6e74 6169 6e69 6e67 2074 6865 2057 6f72  ntaining the Wor
+000105f0: 6b20 5265 7175 6972 656d 656e 7420 6469  k Requirement di
+00010600: 7265 6374 6f72 6965 732e 0a0a 5573 6520  rectories...Use 
+00010610: 7468 6520 602d 2d69 6e74 6572 6163 7469  the `--interacti
+00010620: 7665 6020 6f70 7469 6f6e 2077 6974 6820  ve` option with 
+00010630: 6079 642d 646f 776e 6c6f 6164 6020 746f  `yd-download` to
+00010640: 2073 656c 6563 7420 7768 6963 6820 576f   select which Wo
+00010650: 726b 2052 6571 7569 7265 6d65 6e74 2873  rk Requirement(s
+00010660: 2920 746f 2064 6f77 6e6c 6f61 642e 0a0a  ) to download...
+00010670: 466f 7220 7468 6520 6578 616d 706c 6520  For the example 
+00010680: 6162 6f76 652c 2060 7964 2d64 6f77 6e6c  above, `yd-downl
+00010690: 6f61 6460 2077 6f75 6c64 2063 7265 6174  oad` would creat
+000106a0: 6520 6120 6469 7265 6374 6f72 7920 6361  e a directory ca
+000106b0: 6c6c 6564 2060 6465 7665 6c6f 706d 656e  lled `developmen
+000106c0: 7460 2069 6e20 7468 6520 6375 7272 656e  t` in the curren
+000106d0: 7420 776f 726b 696e 6720 6469 7265 6374  t working direct
+000106e0: 6f72 792c 2063 6f6e 7461 696e 696e 6720  ory, containing 
+000106f0: 736f 6d65 7468 696e 6720 6c69 6b65 3a0a  something like:.
+00010700: 0a60 6060 7368 656c 6c0a 6465 7665 6c6f  .```shell.develo
+00010710: 706d 656e 740a e294 94e2 9480 e294 8020  pment.......... 
+00010720: 7465 7374 7275 6e5f 3232 3131 3038 2d31  testrun_221108-1
+00010730: 3230 3430 342d 3764 320a 2020 2020 e294  20404-7d2.    ..
+00010740: 9ce2 9480 e294 8020 6261 7368 5f73 6372  ....... bash_scr
+00010750: 6970 742e 7368 0a20 2020 20e2 949c e294  ipt.sh.    .....
+00010760: 80e2 9480 2066 696c 655f 312e 7478 740a  .... file_1.txt.
+00010770: 2020 2020 e294 94e2 9480 e294 8020 7461      ......... ta
+00010780: 736b 5f67 726f 7570 5f31 0a20 2020 2020  sk_group_1.     
+00010790: 2020 20e2 9494 e294 80e2 9480 2074 6173     ......... tas
+000107a0: 6b5f 310a 2020 2020 2020 2020 2020 2020  k_1.            
+000107b0: e294 9ce2 9480 e294 8020 7265 7375 6c74  ......... result
+000107c0: 730a 2020 2020 2020 2020 2020 2020 e294  s.            ..
+000107d0: 82c2 a0c2 a020 e294 9ce2 9480 e294 8020  ..... ......... 
+000107e0: 6f70 656e 666f 616d 2e6c 6f67 0a20 2020  openfoam.log.   
+000107f0: 2020 2020 2020 2020 20e2 9482 c2a0 c2a0           .......
+00010800: 20e2 9494 e294 80e2 9480 206f 7065 6e66   ......... openf
+00010810: 6f61 6d2e 7461 722e 677a 0a20 2020 2020  oam.tar.gz.     
+00010820: 2020 2020 2020 20e2 9494 e294 80e2 9480         .........
+00010830: 2074 6173 6b6f 7574 7075 742e 7478 740a   taskoutput.txt.
+00010840: 6060 600a 0a4e 6f74 6520 7468 6174 2065  ```..Note that e
+00010850: 7665 7279 7468 696e 6720 7769 7468 696e  verything within
+00010860: 2074 6865 2060 6e61 6d65 7370 6163 653a   the `namespace:
+00010870: 3a77 6f72 6b2d 7265 7175 6972 656d 656e  :work-requiremen
+00010880: 7460 2064 6972 6563 746f 7279 2069 6e20  t` directory in 
+00010890: 7468 6520 4f62 6a65 6374 2053 746f 7265  the Object Store
+000108a0: 2069 7320 646f 776e 6c6f 6164 6564 2c20   is downloaded, 
+000108b0: 696e 636c 7564 696e 6720 616e 7920 6669  including any fi
+000108c0: 6c65 7320 7468 6174 2077 6572 6520 7370  les that were sp
+000108d0: 6563 6966 6965 6420 696e 2060 696e 7075  ecified in `inpu
+000108e0: 7473 6020 616e 6420 7570 6c6f 6164 6564  ts` and uploaded
+000108f0: 2061 7320 7061 7274 206f 6620 7468 6520   as part of the 
+00010900: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+00010910: 2073 7562 6d69 7373 696f 6e2e 204d 756c   submission. Mul
+00010920: 7469 706c 6520 5461 736b 2047 726f 7570  tiple Task Group
+00010930: 732c 2061 6e64 206d 756c 7469 706c 6520  s, and multiple 
+00010940: 5461 736b 7320 7769 6c6c 2061 6c6c 2061  Tasks will all a
+00010950: 7070 6561 7220 696e 2074 6865 2064 6972  ppear in the dir
+00010960: 6563 746f 7279 2073 7472 7563 7475 7265  ectory structure
+00010970: 2e0a 0a49 6620 7468 6520 6064 6576 656c  ...If the `devel
+00010980: 6f70 6d65 6e74 6020 6469 7265 6374 6f72  opment` director
+00010990: 7920 616c 7265 6164 7920 6578 6973 7473  y already exists
+000109a0: 2c20 6079 642d 646f 776e 6c6f 6164 6020  , `yd-download` 
+000109b0: 7769 6c6c 2074 7279 2060 6465 7665 6c6f  will try `develo
+000109c0: 706d 656e 742e 3031 602c 2065 7463 2e2c  pment.01`, etc.,
+000109d0: 2074 6f20 6176 6f69 6420 6f76 6572 7772   to avoid overwr
+000109e0: 6974 696e 6720 7072 6576 696f 7573 2064  iting previous d
+000109f0: 6f77 6e6c 6f61 6473 2e0a 0a23 2320 5461  ownloads...## Ta
+00010a00: 736b 2045 7865 6375 7469 6f6e 2043 6f6e  sk Execution Con
+00010a10: 7465 7874 0a0a 5468 6973 2073 6563 7469  text..This secti
+00010a20: 6f6e 2064 6973 6375 7373 6573 2074 6865  on discusses the
+00010a30: 2063 6f6e 7465 7874 2077 6974 6869 6e20   context within 
+00010a40: 7768 6963 6820 6120 5461 736b 206f 7065  which a Task ope
+00010a50: 7261 7465 7320 7768 656e 2069 7427 7320  rates when it's 
+00010a60: 6578 6563 7574 6564 2062 7920 6120 576f  executed by a Wo
+00010a70: 726b 6572 206f 6e20 6120 6e6f 6465 2e20  rker on a node. 
+00010a80: 4974 2061 7070 6c69 6573 2073 7065 6369  It applies speci
+00010a90: 6669 6361 6c6c 7920 746f 2074 6865 2059  fically to the Y
+00010aa0: 656c 6c6f 7744 6f67 2041 6765 6e74 2072  ellowDog Agent r
+00010ab0: 756e 6e69 6e67 206f 6e20 6120 4c69 6e75  unning on a Linu
+00010ac0: 7820 6e6f 6465 2c20 616e 6420 636f 6e66  x node, and conf
+00010ad0: 6967 7572 6564 2075 7369 6e67 2074 6865  igured using the
+00010ae0: 2064 6566 6175 6c74 2075 7365 726e 616d   default usernam
+00010af0: 652c 2064 6972 6563 746f 7269 6573 2c20  e, directories, 
+00010b00: 6574 632e 2043 6f6e 6669 6775 7261 7469  etc. Configurati
+00010b10: 6f6e 7320 6361 6e20 7661 7279 2e0a 0a23  ons can vary...#
+00010b20: 2323 2054 6173 6b20 4578 6563 7574 696f  ## Task Executio
+00010b30: 6e20 5374 6570 730a 0a57 6865 6e20 6120  n Steps..When a 
+00010b40: 5461 736b 2069 7320 616c 6c6f 6361 7465  Task is allocate
+00010b50: 6420 746f 2061 2057 6f72 6b65 7220 6f6e  d to a Worker on
+00010b60: 2061 206e 6f64 6520 6279 2074 6865 2059   a node by the Y
+00010b70: 656c 6c6f 7744 6f67 2053 6368 6564 756c  ellowDog Schedul
+00010b80: 6572 2c20 7468 6520 666f 6c6c 6f77 696e  er, the followin
+00010b90: 6720 7374 6570 7320 6172 6520 666f 6c6c  g steps are foll
+00010ba0: 6f77 6564 3a0a 0a31 2e20 5468 6520 4167  owed:..1. The Ag
+00010bb0: 656e 7420 7275 6e6e 696e 6720 6f6e 2074  ent running on t
+00010bc0: 6865 206e 6f64 6520 646f 776e 6c6f 6164  he node download
+00010bd0: 7320 7468 6520 5461 736b 2773 2070 726f  s the Task's pro
+00010be0: 7065 7274 6965 733a 2069 7473 2060 7461  perties: its `ta
+00010bf0: 736b 5479 7065 602c 2020 6061 7267 756d  skType`,  `argum
+00010c00: 656e 7473 602c 2060 656e 7669 726f 6e6d  ents`, `environm
+00010c10: 656e 7460 2c20 6074 6173 6b64 6174 6160  ent`, `taskdata`
+00010c20: 2c20 616e 6420 2866 726f 6d20 7468 6520  , and (from the 
+00010c30: 4f62 6a65 6374 2053 746f 7265 2920 616e  Object Store) an
+00010c40: 7920 6669 6c65 7320 696e 2074 6865 2060  y files in the `
+00010c50: 696e 7075 7473 6020 6c69 7374 2061 6e64  inputs` list and
+00010c60: 2061 6e79 2061 7661 696c 6162 6c65 2066   any available f
+00010c70: 696c 6573 2069 6e20 7468 6520 6069 6e70  iles in the `inp
+00010c80: 7574 734f 7074 696f 6e61 6c60 206c 6973  utsOptional` lis
+00010c90: 742e 0a32 2e20 5468 6573 6520 6669 6c65  t..2. These file
+00010ca0: 7320 6172 6520 706c 6163 6564 2069 6e20  s are placed in 
+00010cb0: 616e 2065 7068 656d 6572 616c 2064 6972  an ephemeral dir
+00010cc0: 6563 746f 7279 2063 7265 6174 6564 2066  ectory created f
+00010cd0: 6f72 2074 6869 7320 5461 736b 2773 2065  or this Task's e
+00010ce0: 7865 6375 7469 6f6e 2c20 616e 6420 696e  xecution, and in
+00010cf0: 746f 2077 6869 6368 2061 6e79 206f 7574  to which any out
+00010d00: 7075 7420 6669 6c65 7320 6172 6520 616c  put files are al
+00010d10: 736f 2070 6c61 6365 6420 6279 2064 6566  so placed by def
+00010d20: 6175 6c74 2e0a 322e 2054 6865 2041 6765  ault..2. The Age
+00010d30: 6e74 2072 756e 7320 7468 6520 636f 6d6d  nt runs the comm
+00010d40: 616e 6420 7370 6563 6966 6965 6420 666f  and specified fo
+00010d50: 7220 7468 6520 6074 6173 6b54 7970 6560  r the `taskType`
+00010d60: 2069 6e20 7468 6520 4167 656e 7427 7320   in the Agent's 
+00010d70: 6061 7070 6c69 6361 7469 6f6e 2e79 616d  `application.yam
+00010d80: 6c60 2063 6f6e 6669 6775 7261 7469 6f6e  l` configuration
+00010d90: 2066 696c 652e 2054 6869 7320 646f 6e65   file. This done
+00010da0: 2061 7320 6120 7369 6d70 6c65 2060 6578   as a simple `ex
+00010db0: 6563 6020 6f66 2061 2073 7562 7072 6f63  ec` of a subproc
+00010dc0: 6573 732e 0a33 2e20 5768 656e 2074 6865  ess..3. When the
+00010dd0: 2054 6173 6b20 636f 6e63 6c75 6465 732c   Task concludes,
+00010de0: 2074 6865 2041 6765 6e74 2075 7365 7320   the Agent uses 
+00010df0: 7468 6520 6578 6974 2063 6f64 6520 6f66  the exit code of
+00010e00: 2074 6865 2073 7562 7072 6f63 6573 7320   the subprocess 
+00010e10: 746f 2072 6570 6f72 7420 7375 6363 6573  to report succes
+00010e20: 7320 287a 6572 6f29 206f 7220 6661 696c  s (zero) or fail
+00010e30: 7572 6520 286e 6f6e 2d7a 6572 6f29 2e0a  ure (non-zero)..
+00010e40: 342e 2054 6865 2041 6765 6e74 2074 6865  4. The Agent the
+00010e50: 6e20 6761 7468 6572 7320 616e 7920 6669  n gathers any fi
+00010e60: 6c65 7320 696e 2074 6865 2060 6f75 7470  les in the `outp
+00010e70: 7574 7360 2061 6e64 2060 6f75 7470 7574  uts` and `output
+00010e80: 7352 6571 7569 7265 6460 206c 6973 7473  sRequired` lists
+00010e90: 2061 6e64 2075 706c 6f61 6473 2074 6865   and uploads the
+00010ea0: 6d20 746f 2074 6865 204f 626a 6563 7420  m to the Object 
+00010eb0: 5374 6f72 652e 2049 6620 6120 6669 6c65  Store. If a file
+00010ec0: 2069 6e20 7468 6520 606f 7574 7075 7473   in the `outputs
+00010ed0: 5265 7175 6972 6564 6020 6c69 7374 2069  Required` list i
+00010ee0: 7320 6e6f 7420 666f 756e 642c 2074 6865  s not found, the
+00010ef0: 2054 6173 6b20 7769 6c6c 2062 6520 7265   Task will be re
+00010f00: 706f 7274 6564 2061 7320 6661 696c 6564  ported as failed
+00010f10: 2e20 5468 6520 4167 656e 7420 7769 6c6c  . The Agent will
+00010f20: 2061 6c73 6f20 6f70 7469 6f6e 616c 6c79   also optionally
+00010f30: 2075 706c 6f61 6420 7468 6520 636f 6e73   upload the cons
+00010f40: 6f6c 6520 6f75 7470 7574 2028 696e 636c  ole output (incl
+00010f50: 7564 696e 6720 626f 7468 2060 7374 646f  uding both `stdo
+00010f60: 7574 6020 616e 6420 6073 7464 6572 7260  ut` and `stderr`
+00010f70: 2920 6f66 2074 6865 2054 6173 6b2c 2063  ) of the Task, c
+00010f80: 6f6e 7461 696e 6564 2069 6e20 7468 6520  ontained in the 
+00010f90: 6074 6173 6b6f 7574 7075 742e 7478 7460  `taskoutput.txt`
+00010fa0: 2066 696c 652e 0a35 2e20 5468 6520 6570   file..5. The ep
+00010fb0: 6865 6d65 7261 6c20 5461 736b 2064 6972  hemeral Task dir
+00010fc0: 6563 746f 7279 2069 7320 7468 656e 2064  ectory is then d
+00010fd0: 656c 6574 6564 2e0a 0a4e 6f74 6520 7468  eleted...Note th
+00010fe0: 6174 2069 6620 6120 5461 736b 2069 7320  at if a Task is 
+00010ff0: 6162 6f72 7465 6420 6475 7269 6e67 2065  aborted during e
+00011000: 7865 6375 7469 6f6e 2c20 7468 6520 5461  xecution, the Ta
+00011010: 736b 2773 2073 7562 7072 6f63 6573 7320  sk's subprocess 
+00011020: 6973 2073 656e 7420 6120 6053 4947 494e  is sent a `SIGIN
+00011030: 5460 2c20 616c 6c6f 7769 6e67 2074 6865  T`, allowing the
+00011040: 2054 6173 6b20 616e 206f 7070 6f72 7475   Task an opportu
+00011050: 6e69 7479 2074 6f20 7465 726d 696e 6174  nity to terminat
+00011060: 6520 616e 7920 6368 696c 6420 7072 6f63  e any child proc
+00011070: 6573 7365 7320 6f72 206f 7468 6572 2072  esses or other r
+00011080: 6573 6f75 7263 6573 2028 652e 672e 2c20  esources (e.g., 
+00011090: 636f 6e74 6169 6e65 7273 2920 7468 6174  containers) that
+000110a0: 206d 6179 2068 6176 6520 6265 656e 2073   may have been s
+000110b0: 7461 7274 6564 2061 7320 7061 7274 206f  tarted as part o
+000110c0: 6620 5461 736b 2065 7865 6375 7469 6f6e  f Task execution
+000110d0: 2e0a 0a4f 6e63 6520 7468 6520 7374 6570  ...Once the step
+000110e0: 7320 6162 6f76 6520 6861 7665 2062 6565  s above have bee
+000110f0: 6e20 636f 6d70 6c65 7465 642c 2074 6865  n completed, the
+00011100: 2057 6f72 6b65 7220 6973 2072 6561 6479   Worker is ready
+00011110: 2074 6f20 6163 6365 7074 2069 7473 206e   to accept its n
+00011120: 6578 7420 5461 736b 2066 726f 6d20 7468  ext Task from th
+00011130: 6520 5965 6c6c 6f77 446f 6720 7363 6865  e YellowDog sche
+00011140: 6475 6c65 722e 0a0a 4e6f 7465 2074 6861  duler...Note tha
+00011150: 7420 6966 2074 6865 2041 6765 6e74 206f  t if the Agent o
+00011160: 6e20 6120 6e6f 6465 2068 6173 206d 756c  n a node has mul
+00011170: 7469 706c 6520 576f 726b 6572 732c 2074  tiple Workers, t
+00011180: 6865 6e20 5461 736b 7320 6172 6520 6578  hen Tasks are ex
+00011190: 6563 7574 6564 2069 6e20 7061 7261 6c6c  ecuted in parall
+000111a0: 656c 206f 6e20 7468 6520 6e6f 6465 2061  el on the node a
+000111b0: 6e64 2063 616e 2073 7461 7274 2061 6e64  nd can start and
+000111c0: 2073 746f 7020 696e 6465 7065 6e64 656e   stop independen
+000111d0: 746c 792e 0a0a 2323 2320 5468 6520 5573  tly...### The Us
+000111e0: 6572 2061 6e64 2047 726f 7570 2075 7365  er and Group use
+000111f0: 6420 666f 7220 5461 736b 730a 0a42 7920  d for Tasks..By 
+00011200: 6465 6661 756c 742c 2074 6865 2041 6765  default, the Age
+00011210: 6e74 2072 756e 7320 6173 2075 7365 7220  nt runs as user 
+00011220: 616e 6420 6772 6f75 7020 6079 642d 6167  and group `yd-ag
+00011230: 656e 7460 2c20 616e 6420 6865 6e63 6520  ent`, and hence 
+00011240: 5461 736b 7320 616c 736f 2065 7865 6375  Tasks also execu
+00011250: 7465 2075 6e64 6572 2074 6869 7320 7573  te under this us
+00011260: 6572 2e0a 0a60 7964 2d61 6765 6e74 6020  er...`yd-agent` 
+00011270: 646f 6573 206e 6f74 2068 6176 6520 6073  does not have `s
+00011280: 7564 6f60 2070 7269 7669 6c65 6765 7320  udo` privileges 
+00011290: 6173 2073 7461 6e64 6172 642c 2062 7574  as standard, but
+000112a0: 2074 6869 7320 6361 6e20 6265 2061 6464   this can be add
+000112b0: 6564 2069 6620 7265 7175 6972 6564 2061  ed if required a
+000112c0: 7420 696e 7374 616e 6365 2062 6f6f 7420  t instance boot 
+000112d0: 7469 6d65 2076 6961 2074 6865 2060 7573  time via the `us
+000112e0: 6572 4461 7461 6020 7072 6f70 6572 7479  erData` property
+000112f0: 206f 6620 6120 7072 6f76 6973 696f 6e69   of a provisioni
+00011300: 6e67 2072 6571 7565 7374 2e20 452e 672e  ng request. E.g.
+00011310: 2028 666f 7220 5562 756e 7475 293a 0a0a   (for Ubuntu):..
+00011320: 6060 6073 6865 6c6c 0a75 7365 726d 6f64  ```shell.usermod
+00011330: 202d 6147 2077 6865 656c 2079 642d 6167   -aG wheel yd-ag
+00011340: 656e 740a 6563 686f 202d 6520 2279 642d  ent.echo -e "yd-
+00011350: 6167 656e 745c 7441 4c4c 3d28 414c 4c29  agent\tALL=(ALL)
+00011360: 5c74 4e4f 5041 5353 5744 3a20 414c 4c22  \tNOPASSWD: ALL"
+00011370: 203e 202f 6574 632f 7375 646f 6572 732e   > /etc/sudoers.
+00011380: 642f 3032 302d 7964 2d61 6765 6e74 0a60  d/020-yd-agent.`
+00011390: 6060 0a0a 2323 2320 486f 6d65 2044 6972  ``..### Home Dir
+000113a0: 6563 746f 7279 2066 6f72 2060 7964 2d61  ectory for `yd-a
+000113b0: 6765 6e74 600a 0a42 7920 6465 6661 756c  gent`..By defaul
+000113c0: 742c 2074 6865 2068 6f6d 6520 6469 7265  t, the home dire
+000113d0: 6374 6f72 7920 6f66 2074 6865 2060 7964  ctory of the `yd
+000113e0: 2d61 6765 6e74 6020 7573 6572 2069 7320  -agent` user is 
+000113f0: 602f 6f70 742f 7965 6c6c 6f77 646f 672f  `/opt/yellowdog/
+00011400: 6167 656e 7460 2e20 5468 6973 2064 6972  agent`. This dir
+00011410: 6563 746f 7279 2074 7970 6963 616c 6c79  ectory typically
+00011420: 2063 6f6e 7461 696e 7320 7468 6520 6061   contains the `a
+00011430: 7070 6c69 6361 7469 6f6e 2e79 616d 6c60  pplication.yaml`
+00011440: 2066 696c 6520 7573 6564 2074 6f20 636f   file used to co
+00011450: 6e66 6967 7572 6520 7468 6520 4167 656e  nfigure the Agen
+00011460: 742c 2061 7320 7765 6c6c 2061 7320 616e  t, as well as an
+00011470: 7920 7363 7269 7074 7320 7468 6174 2061  y scripts that a
+00011480: 7265 2075 7365 6420 746f 2065 7865 6375  re used to execu
+00011490: 7465 2074 6865 2054 6173 6b20 5479 7065  te the Task Type
+000114a0: 7320 7468 6174 2074 6865 206e 6f64 6520  s that the node 
+000114b0: 7375 7070 6f72 7473 2e0a 0a49 6620 6f6e  supports...If on
+000114c0: 6520 7761 6e74 7320 746f 2053 5348 2074  e wants to SSH t
+000114d0: 6f20 616e 2069 6e73 7461 6e63 6520 6173  o an instance as
+000114e0: 2075 7365 7220 6079 642d 6167 656e 7460   user `yd-agent`
+000114f0: 2c20 7065 7268 6170 7320 666f 7220 6465  , perhaps for de
+00011500: 6275 6767 696e 6720 7075 7270 6f73 6573  bugging purposes
+00011510: 2c20 5353 4820 6b65 7973 2063 616e 2062  , SSH keys can b
+00011520: 6520 696e 7365 7274 6564 2076 6961 2069  e inserted via i
+00011530: 6e73 7461 6e63 6520 6075 7365 7244 6174  nstance `userDat
+00011540: 6160 2c20 652e 672e 3a0a 0a60 6060 7368  a`, e.g.:..```sh
+00011550: 656c 6c0a 5944 415f 484f 4d45 3d2f 6f70  ell.YDA_HOME=/op
+00011560: 742f 7965 6c6c 6f77 646f 672f 6167 656e  t/yellowdog/agen
+00011570: 740a 6d6b 6469 7220 2d70 2024 5944 415f  t.mkdir -p $YDA_
+00011580: 484f 4d45 2f2e 7373 680a 6368 6d6f 6420  HOME/.ssh.chmod 
+00011590: 6f67 2d72 7778 2024 5944 415f 484f 4d45  og-rwx $YDA_HOME
+000115a0: 2f2e 7373 680a 6361 7420 3e3e 2024 5944  /.ssh.cat >> $YD
+000115b0: 415f 484f 4d45 2f2e 7373 682f 6175 7468  A_HOME/.ssh/auth
+000115c0: 6f72 697a 6564 5f6b 6579 7320 3c3c 2045  orized_keys << E
+000115d0: 4f46 0a3c 3c49 6e73 6572 745f 5075 626c  OF.<<Insert_Publ
+000115e0: 6963 5f6b 6579 5f48 6572 653e 3e0a 454f  ic_key_Here>>.EO
+000115f0: 460a 6368 6d6f 6420 6f67 2d72 7720 2459  F.chmod og-rw $Y
+00011600: 4441 5f48 4f4d 452f 2e73 7368 2f61 7574  DA_HOME/.ssh/aut
+00011610: 686f 7269 7a65 645f 6b65 7973 0a63 686f  horized_keys.cho
+00011620: 776e 202d 5220 7964 2d61 6765 6e74 3a79  wn -R yd-agent:y
+00011630: 642d 6167 656e 7420 2459 4441 5f48 4f4d  d-agent $YDA_HOM
+00011640: 452f 2e73 7368 0a60 6060 0a0a 2323 2320  E/.ssh.```..### 
+00011650: 5461 736b 2045 7865 6375 7469 6f6e 2044  Task Execution D
+00011660: 6972 6563 746f 7279 0a0a 4570 6865 6d65  irectory..Epheme
+00011670: 7261 6c20 5461 736b 2064 6972 6563 746f  ral Task directo
+00011680: 7269 6573 2061 7265 2062 7920 6465 6661  ries are by defa
+00011690: 756c 7420 6372 6561 7465 6420 756e 6465  ult created unde
+000116a0: 7220 602f 7661 722f 6f70 742f 7965 6c6c  r `/var/opt/yell
+000116b0: 6f77 646f 672f 6167 656e 742f 6461 7461  owdog/agent/data
+000116c0: 2f77 6f72 6b65 7273 602e 2054 6869 7320  /workers`. This 
+000116d0: 6469 7265 6374 6f72 7920 636f 6e74 6169  directory contai
+000116e0: 6e73 206f 6e65 206f 7220 6d6f 7265 206e  ns one or more n
+000116f0: 756d 6265 7265 6420 7375 6264 6972 6563  umbered subdirec
+00011700: 746f 7269 6573 2077 6865 7265 2065 6163  tories where eac
+00011710: 6820 6e75 6d62 6572 6564 2064 6972 6563  h numbered direc
+00011720: 746f 7279 2063 6f72 7265 7370 6f6e 6473  tory corresponds
+00011730: 2074 6f20 6120 576f 726b 6572 206f 6e20   to a Worker on 
+00011740: 7468 6520 6e6f 6465 2e0a 0a28 4f6e 2057  the node...(On W
+00011750: 696e 646f 7773 2068 6f73 7473 2c20 7468  indows hosts, th
+00011760: 6520 5461 736b 2064 6972 6563 746f 7269  e Task directori
+00011770: 6573 2061 7265 2066 6f75 6e64 2075 6e64  es are found und
+00011780: 6572 2060 2541 7070 4461 7461 255c 7965  er `%AppData%\ye
+00011790: 6c6c 6f77 646f 675c 6167 656e 745c 6461  llowdog\agent\da
+000117a0: 7461 5c77 6f72 6b65 7273 602e 290a 0a57  ta\workers`.)..W
+000117b0: 6865 6e20 6120 5461 736b 2069 7320 616c  hen a Task is al
+000117c0: 6c6f 6361 7465 6420 746f 2061 206e 6f64  located to a nod
+000117d0: 652c 2061 6e20 6570 6865 6d65 7261 6c20  e, an ephemeral 
+000117e0: 6469 7265 6374 6f72 7920 6973 2063 7265  directory is cre
+000117f0: 6174 6564 2075 6e64 6572 2074 6865 2061  ated under the a
+00011800: 7070 6c69 6361 626c 6520 576f 726b 6572  pplicable Worker
+00011810: 2064 6972 6563 746f 7279 2c20 7769 7468   directory, with
+00011820: 2061 206e 616d 6520 636f 7272 6573 706f   a name correspo
+00011830: 6e64 696e 6720 7468 6520 5965 6c6c 6f77  nding the Yellow
+00011840: 446f 6720 4944 2066 6f72 2074 6865 2054  Dog ID for the T
+00011850: 6173 6b2e 2046 6f72 2065 7861 6d70 6c65  ask. For example
+00011860: 2c20 7468 6973 2069 7320 616e 2065 7068  , this is an eph
+00011870: 656d 6572 616c 2064 6972 6563 746f 7279  emeral directory
+00011880: 2062 6569 6e67 2075 7365 6420 6279 2057   being used by W
+00011890: 6f72 6b65 7220 6e75 6d62 6572 2060 3160  orker number `1`
+000118a0: 3a0a 0a60 2f76 6172 2f6f 7074 2f79 656c  :..`/var/opt/yel
+000118b0: 6c6f 7764 6f67 2f61 6765 6e74 2f64 6174  lowdog/agent/dat
+000118c0: 612f 776f 726b 6572 732f 312f 7964 6964  a/workers/1/ydid
+000118d0: 5f74 6173 6b5f 3535 3945 4245 5f37 3439  _task_559EBE_749
+000118e0: 3439 3333 362d 6163 3262 2d34 3831 312d  49336-ac2b-4811-
+000118f0: 6137 6435 2d66 3365 6364 3937 3339 3930  a7d5-f3ecd973990
+00011900: 385f 315f 3160 0a0a 5468 6973 2069 7320  8_1_1`..This is 
+00011910: 7468 6520 6469 7265 6374 6f72 7920 696e  the directory in
+00011920: 746f 2077 6869 6368 2064 6f77 6e6c 6f61  to which downloa
+00011930: 6465 6420 6f62 6a65 6374 7320 6172 6520  ded objects are 
+00011940: 706c 6163 6564 2c20 616e 6420 696e 2077  placed, and in w
+00011950: 6869 6368 206f 7574 7075 7420 6669 6c65  hich output file
+00011960: 7320 6172 6520 6372 6561 7465 6420 6279  s are created by
+00011970: 2064 6566 6175 6c74 2e20 5468 6520 636f   default. The co
+00011980: 6e73 6f6c 6520 6f75 7470 7574 2060 7461  nsole output `ta
+00011990: 736b 6f75 7470 7574 2e74 7874 6020 6669  skoutput.txt` fi
+000119a0: 6c65 2077 696c 6c20 616c 736f 2062 6520  le will also be 
+000119b0: 6372 6561 7465 6420 696e 2074 6869 7320  created in this 
+000119c0: 6469 7265 6374 6f72 792e 0a0a 5365 6520  directory...See 
+000119d0: 7468 6520 5b46 696c 6573 2044 6f77 6e6c  the [Files Downl
+000119e0: 6f61 6465 6420 746f 2061 204e 6f64 655d  oaded to a Node]
+000119f0: 2823 6669 6c65 732d 646f 776e 6c6f 6164  (#files-download
+00011a00: 6564 2d74 6f2d 612d 6e6f 6465 2d66 6f72  ed-to-a-node-for
+00011a10: 2d75 7365 2d69 6e2d 7461 736b 2d65 7865  -use-in-task-exe
+00011a20: 6375 7469 6f6e 2920 7365 6374 696f 6e20  cution) section 
+00011a30: 6162 6f76 6520 666f 7220 6d6f 7265 2064  above for more d
+00011a40: 6574 6169 6c73 206f 6e20 686f 7720 6669  etails on how fi
+00011a50: 6c65 7320 696e 2074 6869 7320 6469 7265  les in this dire
+00011a60: 6374 6f72 7920 6172 6520 6861 6e64 6c65  ctory are handle
+00011a70: 642e 0a0a 4174 2074 6865 2063 6f6e 636c  d...At the concl
+00011a80: 7573 696f 6e20 6f66 2074 6865 2054 6173  usion of the Tas
+00011a90: 6b2c 2061 6674 6572 2061 6e79 2066 696c  k, after any fil
+00011aa0: 6573 2072 6571 7565 7374 6564 2066 6f72  es requested for
+00011ab0: 2075 706c 6f61 6420 6861 7665 2062 6565   upload have bee
+00011ac0: 6e20 7570 6c6f 6164 6564 2074 6f20 7468  n uploaded to th
+00011ad0: 6520 4f62 6a65 6374 2053 746f 7265 2028  e Object Store (
+00011ae0: 7365 6520 7468 6520 5b46 696c 6573 2055  see the [Files U
+00011af0: 706c 6f61 6465 6420 6672 6f6d 2061 204e  ploaded from a N
+00011b00: 6f64 655d 2823 6669 6c65 732d 7570 6c6f  ode](#files-uplo
+00011b10: 6164 6564 2d66 726f 6d2d 612d 6e6f 6465  aded-from-a-node
+00011b20: 2d74 6f2d 7468 652d 6f62 6a65 6374 2d73  -to-the-object-s
+00011b30: 746f 7265 2d61 6674 6572 2d74 6173 6b2d  tore-after-task-
+00011b40: 6578 6563 7574 696f 6e29 2073 6563 7469  execution) secti
+00011b50: 6f6e 2066 6f72 206d 6f72 6520 696e 666f  on for more info
+00011b60: 726d 6174 696f 6e29 2c20 7468 6520 6079  rmation), the `y
+00011b70: 6469 645f 7461 736b 5f35 3539 4542 455f  did_task_559EBE_
+00011b80: 3734 3934 3933 3336 2d61 6332 622d 3438  74949336-ac2b-48
+00011b90: 3131 2d61 3764 352d 6633 6563 6439 3733  11-a7d5-f3ecd973
+00011ba0: 3939 3038 5f31 5f31 6020 7769 6c6c 2062  9908_1_1` will b
+00011bb0: 6520 7265 6d6f 7665 642e 0a0a 2323 2053  e removed...## S
+00011bc0: 7065 6369 6679 696e 6720 576f 726b 2052  pecifying Work R
+00011bd0: 6571 7569 7265 6d65 6e74 7320 7573 696e  equirements usin
+00011be0: 6720 4353 5620 4461 7461 0a0a 4353 5620  g CSV Data..CSV 
+00011bf0: 6461 7461 2066 696c 6573 2063 616e 2062  data files can b
+00011c00: 6520 7573 6564 2074 6f20 6472 6976 6520  e used to drive 
+00011c10: 7468 6520 6765 6e65 7261 7469 6f6e 206f  the generation o
+00011c20: 6620 6c69 7374 7320 6f66 2054 6173 6b73  f lists of Tasks
+00011c30: 2c20 6173 2066 6f6c 6c6f 7773 3a0a 0a2d  , as follows:..-
+00011c40: 2041 202a 2a70 726f 746f 7479 7065 2a2a   A **prototype**
+00011c50: 2054 6173 6b20 7370 6563 6966 6963 6174   Task specificat
+00011c60: 696f 6e20 6973 2063 7265 6174 6564 2077  ion is created w
+00011c70: 6974 6869 6e20 6120 4a53 4f4e 2057 6f72  ithin a JSON Wor
+00011c80: 6b20 5265 7175 6972 656d 656e 7420 7370  k Requirement sp
+00011c90: 6563 6966 6963 6174 696f 6e20 6f72 2069  ecification or i
+00011ca0: 6e20 7468 6520 6077 6f72 6b52 6571 7569  n the `workRequi
+00011cb0: 7265 6d65 6e74 6020 7365 6374 696f 6e20  rement` section 
+00011cc0: 6f66 2074 6865 2054 4f4d 4c20 636f 6e66  of the TOML conf
+00011cd0: 6967 7572 6174 696f 6e20 6669 6c65 0a2d  iguration file.-
+00011ce0: 2054 6865 2070 726f 746f 7479 7065 2074   The prototype t
+00011cf0: 6173 6b20 696e 636c 7564 6573 206f 6e65  ask includes one
+00011d00: 206f 7220 6d6f 7265 2076 6172 6961 626c   or more variabl
+00011d10: 6520 7375 6273 7469 7475 7469 6f6e 730a  e substitutions.
+00011d20: 2d20 4120 4353 5620 6669 6c65 2069 7320  - A CSV file is 
+00011d30: 6372 6561 7465 642c 2077 6974 6820 7468  created, with th
+00011d40: 6520 2a2a 6865 6164 6572 732a 2a20 2866  e **headers** (f
+00011d50: 6972 7374 2072 6f77 2920 6d61 7463 6869  irst row) matchi
+00011d60: 6e67 2074 6865 206e 616d 6573 206f 6620  ng the names of 
+00011d70: 7468 6520 7661 7269 6162 6c65 2073 7562  the variable sub
+00011d80: 7374 6974 7574 696f 6e73 2069 6e20 7468  stitutions in th
+00011d90: 6520 5461 736b 2070 726f 746f 7479 7065  e Task prototype
+00011da0: 0a2d 2045 6163 6820 7375 6273 6571 7565  .- Each subseque
+00011db0: 6e74 2072 6f77 206f 6620 7468 6520 4353  nt row of the CS
+00011dc0: 5620 6669 6c65 2072 6570 7265 7365 6e74  V file represent
+00011dd0: 7320 6120 6e65 7720 5461 736b 2062 7569  s a new Task bui
+00011de0: 6c74 2075 7369 6e67 2074 6865 2070 726f  lt using the pro
+00011df0: 746f 7479 7065 2c20 7769 7468 2074 6865  totype, with the
+00011e00: 2076 6172 6961 626c 6573 2073 7562 7374   variables subst
+00011e10: 6974 7574 6564 2062 7920 7468 6520 7661  ituted by the va
+00011e20: 6c75 6573 2069 6e20 7468 6520 726f 770a  lues in the row.
+00011e30: 2d20 4120 5461 736b 2077 696c 6c20 6265  - A Task will be
+00011e40: 2063 7265 6174 6564 2066 6f72 2065 6163   created for eac
+00011e50: 6820 6461 7461 2072 6f77 0a0a 2323 2320  h data row..### 
+00011e60: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+00011e70: 2043 5356 2044 6174 6120 4578 616d 706c   CSV Data Exampl
+00011e80: 650a 0a41 7320 616e 2065 7861 6d70 6c65  e..As an example
+00011e90: 2c20 636f 6e73 6964 6572 2074 6865 2066  , consider the f
+00011ea0: 6f6c 6c6f 7769 6e67 204a 534f 4e20 576f  ollowing JSON Wo
+00011eb0: 726b 2052 6571 7569 7265 6d65 6e74 2060  rk Requirement `
+00011ec0: 7772 2e6a 736f 6e60 3a0a 0a60 6060 6a73  wr.json`:..```js
+00011ed0: 6f6e 0a7b 0a20 2022 7461 736b 4772 6f75  on.{.  "taskGrou
+00011ee0: 7073 223a 205b 0a20 2020 207b 0a20 2020  ps": [.    {.   
+00011ef0: 2020 2022 7461 736b 7322 3a20 5b0a 2020     "tasks": [.  
+00011f00: 2020 2020 2020 7b0a 2020 2020 2020 2020        {.        
+00011f10: 2020 2261 7267 756d 656e 7473 223a 205b    "arguments": [
+00011f20: 227b 7b61 7267 5f31 7d7d 222c 2022 7b7b  "{{arg_1}}", "{{
+00011f30: 6172 675f 327d 7d22 2c20 227b 7b61 7267  arg_2}}", "{{arg
+00011f40: 5f33 7d7d 225d 2c0a 2020 2020 2020 2020  _3}}"],.        
+00011f50: 2020 2265 6e76 6972 6f6e 6d65 6e74 223a    "environment":
+00011f60: 207b 2245 4e56 5f56 4152 5f31 223a 2022   {"ENV_VAR_1": "
+00011f70: 7b7b 656e 765f 317d 7d22 7d0a 2020 2020  {{env_1}}"}.    
+00011f80: 2020 2020 7d0a 2020 2020 2020 5d0a 2020      }.      ].  
+00011f90: 2020 7d0a 2020 5d0a 7d0a 6060 600a 0a4e    }.  ].}.```..N
+00011fa0: 6f74 6520 7468 6174 2074 6865 2054 6173  ote that the Tas
+00011fb0: 6b20 4772 6f75 7020 6d75 7374 2063 6f6e  k Group must con
+00011fc0: 7461 696e 206f 6e6c 7920 6120 7369 6e67  tain only a sing
+00011fd0: 6c65 2054 6173 6b2c 2061 6374 696e 6720  le Task, acting 
+00011fe0: 6173 2074 6865 2070 726f 746f 7479 7065  as the prototype
+00011ff0: 2e0a 0a4e 6f77 2063 6f6e 7369 6465 7220  ...Now consider 
+00012000: 6120 4353 5620 6669 6c65 2060 7772 5f64  a CSV file `wr_d
+00012010: 6174 612e 6373 7660 2077 6974 6820 7468  ata.csv` with th
+00012020: 6520 666f 6c6c 6f77 696e 6720 636f 6e74  e following cont
+00012030: 656e 7473 3a0a 0a60 6060 7465 7874 0a61  ents:..```text.a
+00012040: 7267 5f31 2c20 6172 675f 322c 2061 7267  rg_1, arg_2, arg
+00012050: 5f33 2c20 656e 765f 310a 412c 2020 2020  _3, env_1.A,    
+00012060: 2042 2c20 2020 2020 432c 2020 2020 2045   B,     C,     E
+00012070: 2d31 0a44 2c20 2020 2020 452c 2020 2020  -1.D,     E,    
+00012080: 2046 2c20 2020 2020 452d 320a 472c 2020   F,     E-2.G,  
+00012090: 2020 2048 2c20 2020 2020 492c 2020 2020     H,     I,    
+000120a0: 2045 2d33 0a60 6060 0a0a 4e6f 7465 2074   E-3.```..Note t
+000120b0: 6861 7420 7468 6520 286f 7074 696f 6e61  hat the (optiona
+000120c0: 6c29 206c 6561 6469 6e67 2073 7061 6365  l) leading space
+000120d0: 7320 6166 7465 7220 6561 6368 2063 6f6d  s after each com
+000120e0: 6d61 2061 7265 2069 676e 6f72 6564 2c20  ma are ignored, 
+000120f0: 6275 7420 7472 6169 6c69 6e67 2073 7061  but trailing spa
+00012100: 6365 7320 6172 6520 6e6f 7420 616e 6420  ces are not and 
+00012110: 7769 6c6c 2066 6f72 6d20 7061 7274 206f  will form part o
+00012120: 6620 7468 6520 696d 706f 7274 6564 2064  f the imported d
+00012130: 6174 612e 0a0a 4966 2074 6865 7365 2066  ata...If these f
+00012140: 696c 6573 2061 7265 2070 726f 6365 7373  iles are process
+00012150: 6564 2075 7369 6e67 2060 7964 2d73 7562  ed using `yd-sub
+00012160: 6d69 7420 2d72 2077 722e 6a73 6f6e 202d  mit -r wr.json -
+00012170: 5620 7772 5f64 6174 612e 6373 7660 2c20  V wr_data.csv`, 
+00012180: 7468 6520 666f 6c6c 6f77 696e 6720 6578  the following ex
+00012190: 7061 6e64 6564 206c 6973 7420 6f66 2074  panded list of t
+000121a0: 6872 6565 2054 6173 6b73 2077 696c 6c20  hree Tasks will 
+000121b0: 6265 2063 7265 6174 6564 2070 7269 6f72  be created prior
+000121c0: 2074 6f20 6675 7274 6865 7220 7072 6f63   to further proc
+000121d0: 6573 7369 6e67 2062 7920 7468 6520 6079  essing by the `y
+000121e0: 642d 7375 626d 6974 6020 7363 7269 7074  d-submit` script
+000121f0: 3a0a 0a60 6060 6a73 6f6e 0a7b 0a20 2022  :..```json.{.  "
+00012200: 7461 736b 4772 6f75 7073 223a 205b 0a20  taskGroups": [. 
+00012210: 2020 207b 0a20 2020 2020 2022 7461 736b     {.      "task
+00012220: 7322 3a20 5b0a 2020 2020 2020 2020 7b0a  s": [.        {.
+00012230: 2020 2020 2020 2020 2020 2261 7267 756d            "argum
+00012240: 656e 7473 223a 205b 2241 222c 2022 4222  ents": ["A", "B"
+00012250: 2c20 2243 225d 2c0a 2020 2020 2020 2020  , "C"],.        
+00012260: 2020 2265 6e76 6972 6f6e 6d65 6e74 223a    "environment":
+00012270: 207b 2245 4e56 5f56 4152 5f31 223a 2022   {"ENV_VAR_1": "
+00012280: 452d 3122 7d0a 2020 2020 2020 2020 7d2c  E-1"}.        },
+00012290: 0a20 2020 2020 2020 207b 0a20 2020 2020  .        {.     
+000122a0: 2020 2020 2022 6172 6775 6d65 6e74 7322       "arguments"
+000122b0: 3a20 5b22 4422 2c20 2245 222c 2022 4622  : ["D", "E", "F"
+000122c0: 5d2c 0a20 2020 2020 2020 2020 2022 656e  ],.          "en
+000122d0: 7669 726f 6e6d 656e 7422 3a20 7b22 454e  vironment": {"EN
+000122e0: 565f 5641 525f 3122 3a20 2245 2d32 227d  V_VAR_1": "E-2"}
+000122f0: 0a20 2020 2020 2020 207d 2c0a 2020 2020  .        },.    
+00012300: 2020 2020 7b0a 2020 2020 2020 2020 2020      {.          
+00012310: 2261 7267 756d 656e 7473 223a 205b 2247  "arguments": ["G
+00012320: 222c 2022 4822 2c20 2249 225d 2c0a 2020  ", "H", "I"],.  
+00012330: 2020 2020 2020 2020 2265 6e76 6972 6f6e          "environ
+00012340: 6d65 6e74 223a 207b 2245 4e56 5f56 4152  ment": {"ENV_VAR
+00012350: 5f31 223a 2022 452d 3322 7d0a 2020 2020  _1": "E-3"}.    
+00012360: 2020 2020 7d0a 2020 2020 2020 5d0a 2020      }.      ].  
+00012370: 2020 7d0a 2020 5d0a 7d0a 6060 600a 0a23    }.  ].}.```..#
+00012380: 2323 2043 5356 2056 6172 6961 626c 6520  ## CSV Variable 
+00012390: 5375 6273 7469 7475 7469 6f6e 730a 0a57  Substitutions..W
+000123a0: 6865 6e20 7468 6520 4353 5620 6669 6c65  hen the CSV file
+000123b0: 2064 6174 6120 6973 2070 726f 6365 7373   data is process
+000123c0: 6564 2c20 7468 6520 6f6e 6c79 2073 7562  ed, the only sub
+000123d0: 7374 6974 7574 696f 6e73 206d 6164 6520  stitutions made 
+000123e0: 6172 6520 7468 6f73 6520 7768 6963 6820  are those which 
+000123f0: 6d61 7463 6820 7468 6520 7661 7269 6162  match the variab
+00012400: 6c65 2073 7562 7374 6974 7574 696f 6e73  le substitutions
+00012410: 2069 6e20 7468 6520 7072 6f74 6f74 7970   in the prototyp
+00012420: 6520 5461 736b 2e20 5468 6520 4353 5620  e Task. The CSV 
+00012430: 6669 6c65 2069 7320 7468 6520 2a2a 6f6e  file is the **on
+00012440: 6c79 2a2a 2073 6f75 7263 6520 6f66 2073  ly** source of s
+00012450: 7562 7374 6974 7574 696f 6e73 2075 7365  ubstitutions use
+00012460: 6420 666f 7220 7468 6973 2070 726f 6365  d for this proce
+00012470: 7373 696e 6720 7068 6173 653b 2061 6c6c  ssing phase; all
+00012480: 206f 7468 6572 2076 6172 6961 626c 6520   other variable 
+00012490: 7375 6273 7469 7475 7469 6f6e 7320 2873  substitutions (s
+000124a0: 7570 706c 6965 6420 6f6e 2074 6865 2063  upplied on the c
+000124b0: 6f6d 6d61 6e64 206c 696e 652c 2069 6e20  ommand line, in 
+000124c0: 7468 6520 544f 4d4c 2063 6f6e 6669 6775  the TOML configu
+000124d0: 7261 7469 6f6e 2066 696c 652c 206f 7220  ration file, or 
+000124e0: 6672 6f6d 2065 6e76 6972 6f6e 6d65 6e74  from environment
+000124f0: 2076 6172 6961 626c 6573 2920 6172 6520   variables) are 
+00012500: 6967 6e6f 7265 6420 2d2d 2069 2e65 2e2c  ignored -- i.e.,
+00012510: 2074 6865 7920 646f 206e 6f74 206f 7665   they do not ove
+00012520: 7272 6964 6520 7468 6520 636f 6e74 656e  rride the conten
+00012530: 7473 206f 6620 7468 6520 4353 5620 6669  ts of the CSV fi
+00012540: 6c65 2e0a 0a41 6c6c 2076 6172 6961 626c  le...All variabl
+00012550: 6520 7375 6273 7469 7475 7469 6f6e 7320  e substitutions 
+00012560: 756e 7265 6c61 7465 6420 746f 2074 6865  unrelated to the
+00012570: 2043 5356 2066 696c 6520 6461 7461 2061   CSV file data a
+00012580: 7265 206c 6566 7420 756e 6368 616e 6765  re left unchange
+00012590: 642c 2066 6f72 2073 7562 7365 7175 656e  d, for subsequen
+000125a0: 7420 7072 6f63 6573 7369 6e67 2062 7920  t processing by 
+000125b0: 6079 642d 7375 626d 6974 602e 0a0a 4966  `yd-submit`...If
+000125c0: 2074 6865 2076 616c 7565 2074 6f20 6265   the value to be
+000125d0: 2069 6e73 6572 7465 6420 6973 2061 206e   inserted is a n
+000125e0: 756d 6265 7220 2861 6e20 696e 7465 6765  umber (an intege
+000125f0: 7220 6f72 2066 6c6f 6174 696e 6720 706f  r or floating po
+00012600: 696e 7420 7661 6c75 6529 206f 7220 426f  int value) or Bo
+00012610: 6f6c 6561 6e2c 2074 6865 2060 7b7b 6e75  olean, the `{{nu
+00012620: 6d3a 6d79 5f6e 756d 6265 725f 7661 727d  m:my_number_var}
+00012630: 7d60 2061 6e64 2060 7b7b 626f 6f6c 3a6d  }` and `{{bool:m
+00012640: 795f 626f 6f6c 6561 6e5f 7661 727d 7d60  y_boolean_var}}`
+00012650: 2066 6f72 6d73 2063 616e 2062 6520 7573   forms can be us
+00012660: 6564 2069 6e20 7468 6520 4a53 4f4e 2066  ed in the JSON f
+00012670: 696c 652c 2061 7320 7769 7468 2074 6865  ile, as with the
+00012680: 6972 2075 7365 2069 6e20 6f74 6865 7220  ir use in other 
+00012690: 7061 7274 7320 6f66 2074 6865 204a 534f  parts of the JSO
+000126a0: 4e20 576f 726b 2052 6571 7569 7265 6d65  N Work Requireme
+000126b0: 6e74 2073 7065 6369 6669 6361 7469 6f6e  nt specification
+000126c0: 2e20 5468 6520 7375 6273 7469 7475 7465  . The substitute
+000126d0: 6420 7661 6c75 6520 7769 6c6c 2061 7373  d value will ass
+000126e0: 756d 6520 7468 6520 6e6f 6d69 6e61 7465  ume the nominate
+000126f0: 6420 7479 7065 2072 6174 6865 7220 7468  d type rather th
+00012700: 616e 2062 6569 6e67 2061 2073 7472 696e  an being a strin
+00012710: 672e 0a0a 2323 2320 5072 6f70 6572 7479  g...### Property
+00012720: 2049 6e68 6572 6974 616e 6365 0a0a 416c   Inheritance..Al
+00012730: 6c20 7468 6520 7573 7561 6c20 7072 6f70  l the usual prop
+00012740: 6572 7479 2069 6e68 6572 6974 616e 6365  erty inheritance
+00012750: 2066 6561 7475 7265 7320 6f70 6572 6174   features operat
+00012760: 6520 6173 206e 6f72 6d61 6c2e 2050 726f  e as normal. Pro
+00012770: 7065 7274 6965 7320 6172 6520 696e 6865  perties are inhe
+00012780: 7269 7465 6420 6672 6f6d 2074 6865 2060  rited from the `
+00012790: 636f 6e66 6967 2e74 6f6d 6c60 2066 696c  config.toml` fil
+000127a0: 652c 2061 6e64 2066 726f 6d20 7468 6520  e, and from the 
+000127b0: 7265 6c65 7661 6e74 2073 6563 7469 6f6e  relevant section
+000127c0: 7320 6f66 2074 6865 204a 534f 4e20 576f  s of the JSON Wo
+000127d0: 726b 2052 6571 7569 7265 6d65 6e74 2066  rk Requirement f
+000127e0: 696c 652e 2041 6e79 2070 726f 7065 7274  ile. Any propert
+000127f0: 6965 7320 7365 7420 7769 7468 696e 2061  ies set within a
+00012800: 2054 6173 6b20 7072 6f74 6f74 7970 6520   Task prototype 
+00012810: 6172 6520 636f 7069 6564 2074 6f20 616c  are copied to al
+00012820: 6c20 7468 6520 6765 6e65 7261 7465 6420  l the generated 
+00012830: 5461 736b 732e 0a0a 2323 2320 4d75 6c74  Tasks...### Mult
+00012840: 6970 6c65 2054 6173 6b20 4772 6f75 7073  iple Task Groups
+00012850: 2075 7369 6e67 204d 756c 7469 706c 6520   using Multiple 
+00012860: 4353 5620 4669 6c65 730a 0a54 6865 2075  CSV Files..The u
+00012870: 7365 206f 6620 6d75 6c74 6970 6c65 2054  se of multiple T
+00012880: 6173 6b20 4772 6f75 7073 2069 7320 616c  ask Groups is al
+00012890: 736f 2073 7570 706f 7274 6564 2c20 6279  so supported, by
+000128a0: 2075 7369 6e67 206f 6e65 2043 5356 2066   using one CSV f
+000128b0: 696c 6520 7065 7220 5461 736b 2047 726f  ile per Task Gro
+000128c0: 7570 2e20 4561 6368 2054 6173 6b20 4772  up. Each Task Gr
+000128d0: 6f75 7020 6d75 7374 2063 6f6e 7461 696e  oup must contain
+000128e0: 206f 6e6c 7920 6120 7369 6e67 6c65 2070   only a single p
+000128f0: 726f 746f 7479 7065 2054 6173 6b2e 0a0a  rototype Task...
+00012900: 5468 6520 4353 5620 6669 6c65 7320 6172  The CSV files ar
+00012910: 6520 7375 7070 6c69 6564 206f 6e20 7468  e supplied on th
+00012920: 6520 636f 6d6d 616e 6420 6c69 6e65 2069  e command line i
+00012930: 6e20 7468 6520 6f72 6465 7220 6f66 2074  n the order of t
+00012940: 6865 2054 6173 6b20 4772 6f75 7073 2074  he Task Groups t
+00012950: 6f20 7768 6963 6820 7468 6579 2061 7070  o which they app
+00012960: 6c79 2e20 466f 7220 6578 616d 706c 652c  ly. For example,
+00012970: 2069 6620 6077 725f 6a73 6f6e 6020 636f   if `wr_json` co
+00012980: 6e74 6169 6e73 2074 776f 2054 6173 6b20  ntains two Task 
+00012990: 4772 6f75 7073 2c20 6173 2066 6f6c 6c6f  Groups, as follo
+000129a0: 7773 3a0a 0a60 6060 6a73 6f6e 0a7b 0a20  ws:..```json.{. 
+000129b0: 2022 7461 736b 4772 6f75 7073 223a 205b   "taskGroups": [
+000129c0: 0a20 2020 207b 0a20 2020 2020 2022 7461  .    {.      "ta
+000129d0: 736b 7322 3a20 5b0a 2020 2020 2020 2020  sks": [.        
+000129e0: 7b0a 2020 2020 2020 2020 2020 2261 7267  {.          "arg
+000129f0: 756d 656e 7473 223a 205b 227b 7b61 7267  uments": ["{{arg
+00012a00: 5f31 7d7d 222c 2022 7b7b 6172 675f 327d  _1}}", "{{arg_2}
+00012a10: 7d22 2c20 227b 7b61 7267 5f33 7d7d 225d  }", "{{arg_3}}"]
+00012a20: 2c0a 2020 2020 2020 2020 2020 2265 6e76  ,.          "env
+00012a30: 6972 6f6e 6d65 6e74 223a 207b 2245 4e56  ironment": {"ENV
+00012a40: 5f56 4152 5f31 223a 2022 7b7b 656e 765f  _VAR_1": "{{env_
+00012a50: 317d 7d22 7d0a 2020 2020 2020 2020 7d0a  1}}"}.        }.
+00012a60: 2020 2020 2020 5d0a 2020 2020 7d2c 0a20        ].    },. 
+00012a70: 2020 207b 0a20 2020 2020 2022 7461 736b     {.      "task
+00012a80: 7322 3a20 5b0a 2020 2020 2020 2020 7b0a  s": [.        {.
+00012a90: 2020 2020 2020 2020 2020 2261 7267 756d            "argum
+00012aa0: 656e 7473 223a 205b 227b 7b61 7267 5f31  ents": ["{{arg_1
+00012ab0: 7d7d 222c 2022 7b7b 6172 675f 327d 7d22  }}", "{{arg_2}}"
+00012ac0: 5d2c 0a20 2020 2020 2020 2020 2022 656e  ],.          "en
+00012ad0: 7669 726f 6e6d 656e 7422 3a20 7b22 454e  vironment": {"EN
+00012ae0: 565f 5641 525f 3122 3a20 227b 7b65 6e76  V_VAR_1": "{{env
+00012af0: 5f31 7d7d 222c 2022 454e 565f 5641 525f  _1}}", "ENV_VAR_
+00012b00: 3222 3a20 227b 7b65 6e76 5f32 7d7d 227d  2": "{{env_2}}"}
+00012b10: 0a20 2020 2020 2020 207d 0a20 2020 2020  .        }.     
+00012b20: 205d 0a20 2020 207d 0a20 205d 0a7d 0a60   ].    }.  ].}.`
+00012b30: 6060 0a0a 5468 6520 6079 642d 7375 626d  ``..The `yd-subm
+00012b40: 6974 6020 636f 6d6d 616e 6420 776f 756c  it` command woul
+00012b50: 6420 7468 656e 2062 6520 696e 766f 6b65  d then be invoke
+00012b60: 6420 7769 7468 2061 2073 6570 6172 6174  d with a separat
+00012b70: 6520 4353 5620 6669 6c65 2066 6f72 2065  e CSV file for e
+00012b80: 6163 6820 5461 736b 2047 726f 7570 2c20  ach Task Group, 
+00012b90: 652e 672e 3a0a 0a60 6060 7368 656c 6c0a  e.g.:..```shell.
+00012ba0: 7964 2d73 7562 6d69 7420 2d72 2077 722e  yd-submit -r wr.
+00012bb0: 6a73 6f6e 202d 5620 7772 5f64 6174 615f  json -V wr_data_
+00012bc0: 7461 736b 5f67 726f 7570 5f31 2e63 7376  task_group_1.csv
+00012bd0: 202d 5620 7772 5f64 6174 615f 7461 736b   -V wr_data_task
+00012be0: 5f67 726f 7570 5f32 2e63 7376 0a60 6060  _group_2.csv.```
+00012bf0: 0a0a 4966 2074 6865 7265 2061 7265 202a  ..If there are *
+00012c00: 2a66 6577 6572 2a2a 2043 5356 2066 696c  *fewer** CSV fil
+00012c10: 6573 2074 6861 6e20 5461 736b 2047 726f  es than Task Gro
+00012c20: 7570 7320 6120 7761 726e 696e 6720 7769  ups a warning wi
+00012c30: 6c6c 2062 6520 7072 696e 7465 6420 616e  ll be printed an
+00012c40: 642c 2069 6620 7468 6572 6520 6172 6520  d, if there are 
+00012c50: 276e 2720 4353 5620 6669 6c65 732c 2043  'n' CSV files, C
+00012c60: 5356 2064 6174 6120 7072 6f63 6573 7369  SV data processi
+00012c70: 6e67 2077 696c 6c20 6265 2061 7070 6c69  ng will be appli
+00012c80: 6564 2074 6f20 7468 6520 6669 7273 7420  ed to the first 
+00012c90: 276e 2720 5461 736b 2047 726f 7570 7320  'n' Task Groups 
+00012ca0: 696e 2074 6865 2057 6f72 6b20 5265 7175  in the Work Requ
+00012cb0: 6972 656d 656e 7420 6279 2064 6566 6175  irement by defau
+00012cc0: 6c74 2c20 696e 2074 6865 206f 7264 6572  lt, in the order
+00012cd0: 2069 6e20 7768 6963 6820 7468 6520 4353   in which the CS
+00012ce0: 5620 6669 6c65 7320 7765 7265 2073 7570  V files were sup
+00012cf0: 706c 6965 642e 2049 6620 7468 6572 6520  plied. If there 
+00012d00: 6172 6520 2a2a 6d6f 7265 2a2a 2043 5356  are **more** CSV
+00012d10: 2066 696c 6573 2074 6861 6e20 5461 736b   files than Task
+00012d20: 2047 726f 7570 732c 2061 6e20 6572 726f   Groups, an erro
+00012d30: 7220 7769 6c6c 2062 6520 7261 6973 6564  r will be raised
+00012d40: 2061 6e64 2070 726f 6365 7373 696e 6720   and processing 
+00012d50: 7769 6c6c 2073 746f 702e 0a0a 4974 2069  will stop...It i
+00012d60: 7320 706f 7373 6962 6c65 2074 6f20 6170  s possible to ap
+00012d70: 706c 7920 4353 5620 6669 6c65 7320 6578  ply CSV files ex
+00012d80: 706c 6963 6974 6c79 2074 6f20 7370 6563  plicitly to spec
+00012d90: 6966 6963 2054 6173 6b20 4772 6f75 7073  ific Task Groups
+00012da0: 2c20 6279 2075 7369 6e67 2061 6e20 6f70  , by using an op
+00012db0: 7469 6f6e 616c 202a 2a69 6e64 6578 2070  tional **index p
+00012dc0: 6f73 7466 6978 2a2a 2028 652e 672e 2c20  ostfix** (e.g., 
+00012dd0: 603a 3260 2920 6174 2074 6865 2065 6e64  `:2`) at the end
+00012de0: 206f 6620 6561 6368 2043 5356 2066 696c   of each CSV fil
+00012df0: 656e 616d 652e 2046 6f72 2065 7861 6d70  ename. For examp
+00012e00: 6c65 2c20 6966 2074 6865 7265 2061 7265  le, if there are
+00012e10: 2074 776f 2043 5356 2066 696c 6573 2074   two CSV files t
+00012e20: 6f20 6265 2061 7070 6c69 6564 2074 6f20  o be applied to 
+00012e30: 7468 6520 7365 636f 6e64 2061 6e64 2066  the second and f
+00012e40: 6f75 7274 6820 5461 736b 2047 726f 7570  ourth Task Group
+00012e50: 7320 696e 2061 204a 534f 4e20 576f 726b  s in a JSON Work
+00012e60: 2052 6571 7569 7265 6d65 6e74 2c20 7573   Requirement, us
+00012e70: 6520 7468 6520 666f 6c6c 6f77 696e 6720  e the following 
+00012e80: 7379 6e74 6178 3a0a 0a60 6060 7368 656c  syntax:..```shel
+00012e90: 6c0a 7964 2d73 7562 6d69 7420 2d72 2077  l.yd-submit -r w
+00012ea0: 722e 6a73 6f6e 202d 5620 7772 5f64 6174  r.json -V wr_dat
+00012eb0: 615f 7461 736b 5f67 726f 7570 5f32 2e63  a_task_group_2.c
+00012ec0: 7376 3a32 202d 5620 7772 5f64 6174 615f  sv:2 -V wr_data_
+00012ed0: 7461 736b 5f67 726f 7570 5f34 2e63 7376  task_group_4.csv
+00012ee0: 3a34 0a60 6060 0a0a 416c 7465 726e 6174  :4.```..Alternat
+00012ef0: 6976 656c 792c 2074 6865 202a 2a54 6173  ively, the **Tas
+00012f00: 6b20 4772 6f75 7020 6e61 6d65 2a2a 2028  k Group name** (
+00012f10: 6966 2073 7570 706c 6965 6420 696e 2074  if supplied in t
+00012f20: 6865 204a 534f 4e20 6669 6c65 2920 6361  he JSON file) ca
+00012f30: 6e20 6265 2075 7365 6420 6173 2074 6865  n be used as the
+00012f40: 2070 6f73 7466 6978 2e20 466f 7220 6578   postfix. For ex
+00012f50: 616d 706c 652c 2069 6620 7468 6520 5461  ample, if the Ta
+00012f60: 736b 2047 726f 7570 7320 6162 6f76 6520  sk Groups above 
+00012f70: 6172 6520 6e61 6d65 6420 6074 675f 7477  are named `tg_tw
+00012f80: 6f60 2061 6e64 2060 7467 5f66 6f75 7260  o` and `tg_four`
+00012f90: 2c20 7468 6520 6079 642d 7375 626d 6974  , the `yd-submit
+00012fa0: 6020 636f 6d6d 616e 6420 776f 756c 6420  ` command would 
+00012fb0: 6265 636f 6d65 3a0a 0a60 6060 7368 656c  become:..```shel
+00012fc0: 6c0a 7964 2d73 7562 6d69 7420 2d72 2077  l.yd-submit -r w
+00012fd0: 722e 6a73 6f6e 202d 5620 7772 5f64 6174  r.json -V wr_dat
+00012fe0: 615f 7461 736b 5f67 726f 7570 5f32 2e63  a_task_group_2.c
+00012ff0: 7376 3a74 675f 7477 6f20 2d56 2077 725f  sv:tg_two -V wr_
+00013000: 6461 7461 5f74 6173 6b5f 6772 6f75 705f  data_task_group_
+00013010: 342e 6373 763a 7467 5f66 6f75 720a 6060  4.csv:tg_four.``
+00013020: 600a 0a4e 6f74 6520 7468 6174 206f 6e6c  `..Note that onl
+00013030: 7920 6f6e 6520 4353 5620 6669 6c65 2063  y one CSV file c
+00013040: 616e 2062 6520 6170 706c 6965 6420 746f  an be applied to
+00013050: 2061 6e79 2067 6976 656e 2054 6173 6b20   any given Task 
+00013060: 4772 6f75 702e 2041 2073 696e 676c 6520  Group. A single 
+00013070: 4353 5620 6669 6c65 2063 616e 2c20 686f  CSV file can, ho
+00013080: 7765 7665 722c 2062 6520 7265 7573 6564  wever, be reused
+00013090: 2066 6f72 206d 756c 7469 706c 6520 5461   for multiple Ta
+000130a0: 736b 2047 726f 7570 732e 0a0a 2323 2320  sk Groups...### 
+000130b0: 5573 696e 6720 4353 5620 4461 7461 2077  Using CSV Data w
+000130c0: 6974 6820 5369 6d70 6c65 2c20 544f 4d4c  ith Simple, TOML
+000130d0: 2d4f 6e6c 7920 576f 726b 2052 6571 7569  -Only Work Requi
+000130e0: 7265 6d65 6e74 2053 7065 6369 6669 6361  rement Specifica
+000130f0: 7469 6f6e 730a 0a49 7427 7320 706f 7373  tions..It's poss
+00013100: 6962 6c65 2074 6f20 7573 6520 544f 4d4c  ible to use TOML
+00013110: 2065 7863 6c75 7369 7665 6c79 2074 6f20   exclusively to 
+00013120: 6465 7269 7665 2061 206c 6973 7420 6f66  derive a list of
+00013130: 2054 6173 6b73 2066 726f 6d20 4353 5620   Tasks from CSV 
+00013140: 6461 7461 202d 2d20 692e 652e 2c20 6120  data -- i.e., a 
+00013150: 4a53 4f4e 2057 6f72 6b20 5265 7175 6972  JSON Work Requir
+00013160: 656d 656e 7420 7370 6563 6966 6963 6174  ement specificat
+00013170: 696f 6e20 6973 206e 6f74 2072 6571 7569  ion is not requi
+00013180: 7265 642e 0a0a 546f 206d 616b 6520 7573  red...To make us
+00013190: 6520 6f66 2074 6869 733a 0a0a 312e 2045  e of this:..1. E
+000131a0: 6e73 7572 6520 7468 6174 206e 6f20 4a53  nsure that no JS
+000131b0: 4f4e 2057 6f72 6b20 5265 7175 6972 656d  ON Work Requirem
+000131c0: 656e 7420 646f 6375 6d65 6e74 2069 7320  ent document is 
+000131d0: 7370 6563 6966 6965 6420 286e 6f20 6077  specified (no `w
+000131e0: 6f72 6b52 6571 7569 7265 6d65 6e74 4461  orkRequirementDa
+000131f0: 7461 6020 696e 2074 6865 2054 4f4d 4c20  ta` in the TOML 
+00013200: 6669 6c65 2c20 6f72 2060 2d2d 776f 726b  file, or `--work
+00013210: 2d72 6571 7569 7265 6d65 6e74 6020 6f6e  -requirement` on
+00013220: 2074 6865 2063 6f6d 6d61 6e64 206c 696e   the command lin
+00013230: 6529 0a32 2e20 496e 7365 7274 2074 6865  e).2. Insert the
+00013240: 2072 6571 7569 7265 6420 4353 562d 7375   required CSV-su
+00013250: 7070 6c69 6564 2076 6172 6961 626c 6520  pplied variable 
+00013260: 7375 6273 7469 7475 7469 6f6e 7320 6469  substitutions di
+00013270: 7265 6374 6c79 2069 6e74 6f20 7468 6520  rectly into the 
+00013280: 544f 4d4c 2070 726f 7065 7274 6965 732c  TOML properties,
+00013290: 2065 2e67 2e20 6061 7267 756d 656e 7473   e.g. `arguments
+000132a0: 203d 205b 227b 7b61 7267 5f31 7d7d 222c   = ["{{arg_1}}",
+000132b0: 2022 7b7b 6172 675f 327d 7d22 5d60 0a33   "{{arg_2}}"]`.3
+000132c0: 2e20 5370 6563 6966 7920 6120 7369 6e67  . Specify a sing
+000132d0: 6c65 2043 5356 2066 696c 6520 696e 2074  le CSV file in t
+000132e0: 6865 2060 6373 7646 696c 6573 6020 544f  he `csvFiles` TO
+000132f0: 4d4c 2070 726f 7065 7274 792c 2065 2e67  ML property, e.g
+00013300: 2e20 6063 7376 4669 6c65 7320 3d20 5b22  . `csvFiles = ["
+00013310: 7772 5f64 6174 612e 6373 7622 5d60 2c20  wr_data.csv"]`, 
+00013320: 6f72 2070 726f 7669 6465 2074 6865 2043  or provide the C
+00013330: 5356 2066 696c 6520 6f6e 2074 6865 2063  SV file on the c
+00013340: 6f6d 6d61 6e64 206c 696e 6520 602d 5620  ommand line `-V 
+00013350: 7772 5f64 6174 612e 6373 7660 0a0a 5768  wr_data.csv`..Wh
+00013360: 656e 2060 7964 2d73 7562 6d69 7460 2069  en `yd-submit` i
+00013370: 7320 7275 6e2c 2069 7420 7769 6c6c 2065  s run, it will e
+00013380: 7870 616e 6420 7468 6520 5461 736b 206c  xpand the Task l
+00013390: 6973 7420 746f 206d 6174 6368 2074 6865  ist to match the
+000133a0: 206e 756d 6265 7220 6f66 2064 6174 6120   number of data 
+000133b0: 726f 7773 2069 6e20 7468 6520 4353 5620  rows in the CSV 
+000133c0: 6669 6c65 2e0a 0a23 2323 2049 6e73 7065  file...### Inspe
+000133d0: 6374 696e 6720 7468 6520 5265 7375 6c74  cting the Result
+000133e0: 7320 6f66 2043 5356 2056 6172 6961 626c  s of CSV Variabl
+000133f0: 6520 5375 6273 7469 7475 7469 6f6e 0a0a  e Substitution..
+00013400: 5468 6520 602d 2d70 726f 6365 7373 2d63  The `--process-c
+00013410: 7376 2d6f 6e6c 7960 2028 6f72 2060 2d70  sv-only` (or `-p
+00013420: 6029 206f 7074 696f 6e20 6361 6e20 6265  `) option can be
+00013430: 2075 7365 6420 7769 7468 2060 7964 2d73   used with `yd-s
+00013440: 7562 6d69 7460 2074 6f20 6f75 7470 7574  ubmit` to output
+00013450: 2074 6865 204a 534f 4e20 576f 726b 2052   the JSON Work R
+00013460: 6571 7569 7265 6d65 6e74 2061 6674 6572  equirement after
+00013470: 2043 5356 2076 6172 6961 626c 6520 7375   CSV variable su
+00013480: 6273 7469 7475 7469 6f6e 7320 6f6e 6c79  bstitutions only
+00013490: 2c20 7072 696f 7220 746f 2061 6c6c 206f  , prior to all o
+000134a0: 7468 6572 2073 7562 7374 6974 7574 696f  ther substitutio
+000134b0: 6e73 2061 6e64 2070 726f 7065 7274 7920  ns and property 
+000134c0: 696e 6865 7269 7461 6e63 6520 6170 706c  inheritance appl
+000134d0: 6965 6420 6279 2060 7964 2d73 7562 6d69  ied by `yd-submi
+000134e0: 7460 2e0a 0a23 2057 6f72 6b65 7220 506f  t`...# Worker Po
+000134f0: 6f6c 2050 726f 7065 7274 6965 730a 0a54  ol Properties..T
+00013500: 6865 2060 776f 726b 6572 506f 6f6c 6020  he `workerPool` 
+00013510: 7365 6374 696f 6e20 6f66 2074 6865 2054  section of the T
+00013520: 4f4d 4c20 6669 6c65 2064 6566 696e 6573  OML file defines
+00013530: 2074 6865 2070 726f 7065 7274 6965 7320   the properties 
+00013540: 6f66 2074 6865 2057 6f72 6b65 7220 506f  of the Worker Po
+00013550: 6f6c 2074 6f20 6265 2063 7265 6174 6564  ol to be created
+00013560: 2c20 616e 6420 6973 2075 7365 6420 6279  , and is used by
+00013570: 2074 6865 2060 7964 2d70 726f 7669 7369   the `yd-provisi
+00013580: 6f6e 6020 636f 6d6d 616e 642e 2041 2073  on` command. A s
+00013590: 7562 7365 7420 6f66 2074 6865 2070 726f  ubset of the pro
+000135a0: 7065 7274 6965 7320 6973 2061 6c73 6f20  perties is also 
+000135b0: 7573 6564 2062 7920 7468 6520 6079 642d  used by the `yd-
+000135c0: 696e 7374 616e 7469 6174 6560 2063 6f6d  instantiate` com
+000135d0: 6d61 6e64 2c20 666f 7220 6372 6561 7469  mand, for creati
+000135e0: 6e67 2073 7461 6e64 616c 6f6e 6520 436f  ng standalone Co
+000135f0: 6d70 7574 6520 5265 7175 6972 656d 656e  mpute Requiremen
+00013600: 7473 2074 6861 7420 6172 6520 6e6f 7420  ts that are not 
+00013610: 6173 736f 6369 6174 6564 2077 6974 6820  associated with 
+00013620: 576f 726b 6572 2050 6f6f 6c73 2e0a 0a54  Worker Pools...T
+00013630: 6865 206f 6e6c 7920 6d61 6e64 6174 6f72  he only mandator
+00013640: 7920 7072 6f70 6572 7479 2069 7320 6074  y property is `t
+00013650: 656d 706c 6174 6549 6460 2e20 416c 6c20  emplateId`. All 
+00013660: 6f74 6865 7220 7072 6f70 6572 7469 6573  other properties
+00013670: 2068 6176 6520 6465 6661 756c 7473 2028   have defaults (
+00013680: 6f72 2061 7265 206e 6f74 2072 6571 7569  or are not requi
+00013690: 7265 6429 2e0a 0a54 6865 2066 6f6c 6c6f  red)...The follo
+000136a0: 7769 6e67 2070 726f 7065 7274 6965 7320  wing properties 
+000136b0: 6172 6520 6176 6169 6c61 626c 653a 0a0a  are available:..
+000136c0: 7c20 5072 6f70 6572 7479 2020 2020 2020  | Property      
+000136d0: 2020 2020 2020 2020 2020 2020 7c20 4465              | De
+000136e0: 7363 7269 7074 696f 6e20 2020 2020 2020  scription       
+000136f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013700: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013710: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013720: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013730: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013740: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013750: 2020 2020 2020 7c20 4465 6661 756c 7420        | Default 
+00013760: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013770: 7c0a 7c3a 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  |.|:------------
+00013780: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 7c3a  --------------|:
 00013790: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
 000137a0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
-000137b0: 2d7c 3a2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  -|:-------------
-000137c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d7c 0a7c 2060  -----------|.| `
-000137d0: 6964 6c65 4e6f 6465 5368 7574 646f 776e  idleNodeShutdown
-000137e0: 456e 6162 6c65 6460 207c 2057 6865 7468  Enabled` | Wheth
-000137f0: 6572 2074 6f20 7368 7574 2064 6f77 6e20  er to shut down 
-00013800: 6e6f 6465 7320 7468 6174 2068 6176 6520  nodes that have 
-00013810: 6265 656e 2069 646c 6520 666f 7220 6069  been idle for `i
-00013820: 646c 654e 6f64 6553 6875 7464 6f77 6e54  dleNodeShutdownT
-00013830: 696d 656f 7574 6020 6d69 6e75 7465 732e  imeout` minutes.
-00013840: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013850: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013860: 2020 207c 2060 5472 7565 6020 2020 2020     | `True`     
-00013870: 2020 2020 2020 2020 2020 2020 207c 0a7c               |.|
-00013880: 2060 6964 6c65 4e6f 6465 5368 7574 646f   `idleNodeShutdo
-00013890: 776e 5469 6d65 6f75 7460 207c 2054 6865  wnTimeout` | The
-000138a0: 2074 696d 656f 7574 2069 6e20 6d69 6e75   timeout in minu
-000138b0: 7465 7320 6166 7465 7220 7768 6963 6820  tes after which 
-000138c0: 616e 2069 646c 6520 6e6f 6465 2077 696c  an idle node wil
-000138d0: 6c20 6265 2073 6875 7420 646f 776e 2069  l be shut down i
-000138e0: 6620 6069 646c 654e 6f64 6553 6875 7464  f `idleNodeShutd
-000138f0: 6f77 6e45 6e61 626c 6564 6020 6973 2073  ownEnabled` is s
-00013900: 6574 2074 6f20 6054 7275 6560 2e20 2020  et to `True`.   
-00013910: 2020 2020 207c 2060 352e 3060 2020 2020       | `5.0`    
-00013920: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00013930: 0a7c 2060 6964 6c65 506f 6f6c 5368 7574  .| `idlePoolShut
-00013940: 646f 776e 456e 6162 6c65 6460 207c 2057  downEnabled` | W
-00013950: 6865 7468 6572 2074 6f20 7368 7574 2064  hether to shut d
-00013960: 6f77 6e20 7468 6520 576f 726b 6572 2050  own the Worker P
-00013970: 6f6f 6c20 7768 656e 2069 7420 6861 7320  ool when it has 
-00013980: 6265 656e 2069 646c 6520 666f 7220 6069  been idle for `i
-00013990: 646c 6550 6f6f 6c53 6875 7464 6f77 6e54  dlePoolShutdownT
-000139a0: 696d 656f 7574 6020 6d69 6e75 7465 732e  imeout` minutes.
-000139b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000139c0: 2020 2020 2020 207c 2060 5472 7565 6020         | `True` 
-000139d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000139e0: 207c 0a7c 2060 6964 6c65 506f 6f6c 5368   |.| `idlePoolSh
-000139f0: 7574 646f 776e 5469 6d65 6f75 7460 207c  utdownTimeout` |
-00013a00: 2054 6865 2074 696d 656f 7574 2069 6e20   The timeout in 
-00013a10: 6d69 6e75 7465 7320 6166 7465 7220 7768  minutes after wh
-00013a20: 6963 6820 616e 2069 646c 6520 576f 726b  ich an idle Work
-00013a30: 6572 2050 6f6f 6c20 7769 6c6c 2062 6520  er Pool will be 
-00013a40: 7368 7574 2064 6f77 6e20 6966 2060 6964  shut down if `id
-00013a50: 6c65 506f 6f6c 5368 7574 646f 776e 456e  lePoolShutdownEn
-00013a60: 6162 6c65 6460 2069 7320 7365 7420 746f  abled` is set to
-00013a70: 2060 5472 7565 602e 207c 2060 3330 2e30   `True`. | `30.0
-00013a80: 6020 2020 2020 2020 2020 2020 2020 2020  `               
-00013a90: 2020 207c 0a7c 2060 696d 6167 6573 4964     |.| `imagesId
-00013aa0: 6020 2020 2020 2020 2020 2020 2020 2020  `               
-00013ab0: 207c 2054 6865 2069 6d61 6765 7320 4944   | The images ID
-00013ac0: 2074 6f20 7573 6520 7768 656e 2062 6f6f   to use when boo
-00013ad0: 7469 6e67 2069 6e73 7461 6e63 6573 2e20  ting instances. 
-00013ae0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013af0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013b00: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013b10: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013b20: 2020 2020 2020 2020 2020 207c 2020 2020             |    
-00013b30: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013b40: 2020 2020 207c 0a7c 2060 696e 7374 616e       |.| `instan
-00013b50: 6365 5461 6773 6020 2020 2020 2020 2020  ceTags`         
-00013b60: 2020 207c 2054 6865 2064 6963 7469 6f6e     | The diction
-00013b70: 6172 7920 6f66 2069 6e73 7461 6e63 6520  ary of instance 
-00013b80: 7461 6773 2074 6f20 6170 706c 7920 746f  tags to apply to
-00013b90: 2074 6865 2069 6e73 7461 6e63 6573 2e20   the instances. 
-00013ba0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013bb0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013bc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013bd0: 2020 2020 2020 2020 2020 2020 207c 2020               |  
-00013be0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013bf0: 2020 2020 2020 207c 0a7c 2060 6d69 6e4e         |.| `minN
-00013c00: 6f64 6573 6020 2020 2020 2020 2020 2020  odes`           
-00013c10: 2020 2020 207c 2054 6865 206d 696e 696d       | The minim
-00013c20: 756d 206e 756d 6265 7220 6f66 206e 6f64  um number of nod
-00013c30: 6573 2074 6f20 7768 6963 6820 7468 6520  es to which the 
-00013c40: 576f 726b 6572 2050 6f6f 6c20 6361 6e20  Worker Pool can 
-00013c50: 6265 2073 6361 6c65 6420 646f 776e 2e20  be scaled down. 
-00013c60: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013c70: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013c80: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00013c90: 2060 3060 2020 2020 2020 2020 2020 2020   `0`            
-00013ca0: 2020 2020 2020 2020 207c 0a7c 2060 6d61           |.| `ma
-00013cb0: 784e 6f64 6573 6020 2020 2020 2020 2020  xNodes`         
-00013cc0: 2020 2020 2020 207c 2054 6865 206d 6178         | The max
-00013cd0: 696d 756d 206e 756d 6265 7220 6f66 206e  imum number of n
-00013ce0: 6f64 6573 2074 6f20 7768 6963 6820 7468  odes to which th
-00013cf0: 6520 576f 726b 6572 2050 6f6f 6c20 6361  e Worker Pool ca
-00013d00: 6e20 6265 2073 6361 6c65 6420 7570 2e20  n be scaled up. 
-00013d10: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013d20: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013d30: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013d40: 207c 2060 3160 2020 2020 2020 2020 2020   | `1`          
-00013d50: 2020 2020 2020 2020 2020 207c 0a7c 2060             |.| `
-00013d60: 6e61 6d65 6020 2020 2020 2020 2020 2020  name`           
-00013d70: 2020 2020 2020 2020 207c 2054 6865 206e           | The n
-00013d80: 616d 6520 6f66 2074 6865 2057 6f72 6b65  ame of the Worke
-00013d90: 7220 506f 6f6c 2e20 2020 2020 2020 2020  r Pool.         
+000137b0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000137c0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000137d0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000137e0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+000137f0: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00013800: 2d2d 2d2d 2d2d 2d2d 7c3a 2d2d 2d2d 2d2d  --------|:------
+00013810: 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d 2d2d  ----------------
+00013820: 2d2d 7c0a 7c20 6069 646c 654e 6f64 6553  --|.| `idleNodeS
+00013830: 6875 7464 6f77 6e45 6e61 626c 6564 6020  hutdownEnabled` 
+00013840: 7c20 5768 6574 6865 7220 746f 2073 6875  | Whether to shu
+00013850: 7420 646f 776e 206e 6f64 6573 2074 6861  t down nodes tha
+00013860: 7420 6861 7665 2062 6565 6e20 6964 6c65  t have been idle
+00013870: 2066 6f72 2060 6964 6c65 4e6f 6465 5368   for `idleNodeSh
+00013880: 7574 646f 776e 5469 6d65 6f75 7460 206d  utdownTimeout` m
+00013890: 696e 7574 6573 2e20 2020 2020 2020 2020  inutes.         
+000138a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000138b0: 2020 2020 2020 2020 2020 7c20 6054 7275            | `Tru
+000138c0: 6560 2020 2020 2020 2020 2020 2020 2020  e`              
+000138d0: 2020 2020 7c0a 7c20 6069 646c 654e 6f64      |.| `idleNod
+000138e0: 6553 6875 7464 6f77 6e54 696d 656f 7574  eShutdownTimeout
+000138f0: 6020 7c20 5468 6520 7469 6d65 6f75 7420  ` | The timeout 
+00013900: 696e 206d 696e 7574 6573 2061 6674 6572  in minutes after
+00013910: 2077 6869 6368 2061 6e20 6964 6c65 206e   which an idle n
+00013920: 6f64 6520 7769 6c6c 2062 6520 7368 7574  ode will be shut
+00013930: 2064 6f77 6e20 6966 2060 6964 6c65 4e6f   down if `idleNo
+00013940: 6465 5368 7574 646f 776e 456e 6162 6c65  deShutdownEnable
+00013950: 6460 2069 7320 7365 7420 746f 2060 5472  d` is set to `Tr
+00013960: 7565 602e 2020 2020 2020 2020 7c20 6035  ue`.        | `5
+00013970: 2e30 6020 2020 2020 2020 2020 2020 2020  .0`             
+00013980: 2020 2020 2020 7c0a 7c20 6069 646c 6550        |.| `idleP
+00013990: 6f6f 6c53 6875 7464 6f77 6e45 6e61 626c  oolShutdownEnabl
+000139a0: 6564 6020 7c20 5768 6574 6865 7220 746f  ed` | Whether to
+000139b0: 2073 6875 7420 646f 776e 2074 6865 2057   shut down the W
+000139c0: 6f72 6b65 7220 506f 6f6c 2077 6865 6e20  orker Pool when 
+000139d0: 6974 2068 6173 2062 6565 6e20 6964 6c65  it has been idle
+000139e0: 2066 6f72 2060 6964 6c65 506f 6f6c 5368   for `idlePoolSh
+000139f0: 7574 646f 776e 5469 6d65 6f75 7460 206d  utdownTimeout` m
+00013a00: 696e 7574 6573 2e20 2020 2020 2020 2020  inutes.         
+00013a10: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00013a20: 6054 7275 6560 2020 2020 2020 2020 2020  `True`          
+00013a30: 2020 2020 2020 2020 7c0a 7c20 6069 646c          |.| `idl
+00013a40: 6550 6f6f 6c53 6875 7464 6f77 6e54 696d  ePoolShutdownTim
+00013a50: 656f 7574 6020 7c20 5468 6520 7469 6d65  eout` | The time
+00013a60: 6f75 7420 696e 206d 696e 7574 6573 2061  out in minutes a
+00013a70: 6674 6572 2077 6869 6368 2061 6e20 6964  fter which an id
+00013a80: 6c65 2057 6f72 6b65 7220 506f 6f6c 2077  le Worker Pool w
+00013a90: 696c 6c20 6265 2073 6875 7420 646f 776e  ill be shut down
+00013aa0: 2069 6620 6069 646c 6550 6f6f 6c53 6875   if `idlePoolShu
+00013ab0: 7464 6f77 6e45 6e61 626c 6564 6020 6973  tdownEnabled` is
+00013ac0: 2073 6574 2074 6f20 6054 7275 6560 2e20   set to `True`. 
+00013ad0: 7c20 6033 302e 3060 2020 2020 2020 2020  | `30.0`        
+00013ae0: 2020 2020 2020 2020 2020 7c0a 7c20 6069            |.| `i
+00013af0: 6d61 6765 7349 6460 2020 2020 2020 2020  magesId`        
+00013b00: 2020 2020 2020 2020 7c20 5468 6520 696d          | The im
+00013b10: 6167 6573 2049 4420 746f 2075 7365 2077  ages ID to use w
+00013b20: 6865 6e20 626f 6f74 696e 6720 696e 7374  hen booting inst
+00013b30: 616e 6365 732e 2020 2020 2020 2020 2020  ances.          
+00013b40: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013b50: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013b60: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013b70: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013b80: 2020 7c20 2020 2020 2020 2020 2020 2020    |             
+00013b90: 2020 2020 2020 2020 2020 2020 7c0a 7c20              |.| 
+00013ba0: 6069 6e73 7461 6e63 6554 6167 7360 2020  `instanceTags`  
+00013bb0: 2020 2020 2020 2020 2020 7c20 5468 6520            | The 
+00013bc0: 6469 6374 696f 6e61 7279 206f 6620 696e  dictionary of in
+00013bd0: 7374 616e 6365 2074 6167 7320 746f 2061  stance tags to a
+00013be0: 7070 6c79 2074 6f20 7468 6520 696e 7374  pply to the inst
+00013bf0: 616e 6365 732e 2020 2020 2020 2020 2020  ances.          
+00013c00: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013c10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013c20: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013c30: 2020 2020 7c20 2020 2020 2020 2020 2020      |           
+00013c40: 2020 2020 2020 2020 2020 2020 2020 7c0a                |.
+00013c50: 7c20 606d 696e 4e6f 6465 7360 2020 2020  | `minNodes`    
+00013c60: 2020 2020 2020 2020 2020 2020 7c20 5468              | Th
+00013c70: 6520 6d69 6e69 6d75 6d20 6e75 6d62 6572  e minimum number
+00013c80: 206f 6620 6e6f 6465 7320 746f 2077 6869   of nodes to whi
+00013c90: 6368 2074 6865 2057 6f72 6b65 7220 506f  ch the Worker Po
+00013ca0: 6f6c 2063 616e 2062 6520 7363 616c 6564  ol can be scaled
+00013cb0: 2064 6f77 6e2e 2020 2020 2020 2020 2020   down.          
+00013cc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013cd0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013ce0: 2020 2020 2020 7c20 6030 6020 2020 2020        | `0`     
+00013cf0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013d00: 7c0a 7c20 606d 6178 4e6f 6465 7360 2020  |.| `maxNodes`  
+00013d10: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00013d20: 5468 6520 6d61 7869 6d75 6d20 6e75 6d62  The maximum numb
+00013d30: 6572 206f 6620 6e6f 6465 7320 746f 2077  er of nodes to w
+00013d40: 6869 6368 2074 6865 2057 6f72 6b65 7220  hich the Worker 
+00013d50: 506f 6f6c 2063 616e 2062 6520 7363 616c  Pool can be scal
+00013d60: 6564 2075 702e 2020 2020 2020 2020 2020  ed up.          
+00013d70: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013d80: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013d90: 2020 2020 2020 2020 7c20 6031 6020 2020          | `1`   
 00013da0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013db0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013db0: 2020 7c0a 7c20 606e 616d 6560 2020 2020    |.| `name`    
 00013dc0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013dd0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013de0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013df0: 2020 207c 2041 7574 6f6d 6174 6963 616c     | Automatical
-00013e00: 6c79 2047 656e 6572 6174 6564 207c 0a7c  ly Generated |.|
-00013e10: 2060 6e6f 6465 426f 6f74 5469 6d65 6f75   `nodeBootTimeou
-00013e20: 7460 2020 2020 2020 2020 207c 2054 6865  t`         | The
-00013e30: 2074 696d 6520 696e 206d 696e 7574 6573   time in minutes
-00013e40: 2061 6c6c 6f77 6564 2066 6f72 2061 206e   allowed for a n
-00013e50: 6f64 6520 746f 2062 6f6f 7420 616e 6420  ode to boot and 
-00013e60: 7265 6769 7374 6572 2077 6974 6820 7468  register with th
-00013e70: 6520 706c 6174 666f 726d 2c20 6f74 6865  e platform, othe
-00013e80: 7277 6973 6520 6974 2077 696c 6c20 6265  rwise it will be
-00013e90: 2074 6572 6d69 6e61 7465 642e 2020 2020   terminated.    
-00013ea0: 2020 2020 207c 2060 3130 2e30 6020 2020       | `10.0`   
-00013eb0: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00013ec0: 0a7c 2060 7461 7267 6574 496e 7374 616e  .| `targetInstan
-00013ed0: 6365 436f 756e 7460 2020 2020 207c 2054  ceCount`     | T
-00013ee0: 6865 2069 6e69 7469 616c 206e 756d 6265  he initial numbe
-00013ef0: 7220 6f66 206e 6f64 6573 2074 6f20 6372  r of nodes to cr
-00013f00: 6561 7465 2066 6f72 2074 6865 2057 6f72  eate for the Wor
-00013f10: 6b65 7220 506f 6f6c 2e20 2020 2020 2020  ker Pool.       
-00013f20: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013f30: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013f40: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013f50: 2020 2020 2020 207c 2060 3160 2020 2020         | `1`    
-00013f60: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00013f70: 207c 0a7c 2060 7465 6d70 6c61 7465 4964   |.| `templateId
-00013f80: 6020 2020 2020 2020 2020 2020 2020 207c  `              |
-00013f90: 2054 6865 2059 656c 6c6f 7744 6f67 2043   The YellowDog C
-00013fa0: 6f6d 7075 7465 2054 656d 706c 6174 6520  ompute Template 
-00013fb0: 4944 2074 6f20 7573 6520 666f 7220 7072  ID to use for pr
-00013fc0: 6f76 6973 696f 6e69 6e67 2e20 282a 2a52  ovisioning. (**R
-00013fd0: 6571 7569 7265 642a 2a2c 206e 6f20 6465  equired**, no de
-00013fe0: 6661 756c 7420 7072 6f76 6964 6564 2e29  fault provided.)
-00013ff0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014000: 2020 2020 2020 2020 207c 2020 2020 2020           |      
-00014010: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014020: 2020 207c 0a7c 2060 7573 6572 4461 7461     |.| `userData
-00014030: 6020 2020 2020 2020 2020 2020 2020 2020  `               
-00014040: 207c 2055 7365 7220 4461 7461 2074 6f20   | User Data to 
-00014050: 6265 2073 7570 706c 6965 6420 746f 2069  be supplied to i
-00014060: 6e73 7461 6e63 6573 206f 6e20 626f 6f74  nstances on boot
-00014070: 2e20 2020 2020 2020 2020 2020 2020 2020  .               
-00014080: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014090: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000140a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000140b0: 2020 2020 2020 2020 2020 207c 2020 2020             |    
-000140c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000140d0: 2020 2020 207c 0a7c 2060 7573 6572 4461       |.| `userDa
-000140e0: 7461 4669 6c65 6020 2020 2020 2020 2020  taFile`         
-000140f0: 2020 207c 2041 7320 6162 6f76 652c 2062     | As above, b
-00014100: 7574 2072 6561 6420 7468 6520 5573 6572  ut read the User
-00014110: 2044 6174 6120 6672 6f6d 2074 6865 2066   Data from the f
-00014120: 696c 656e 616d 6520 7375 7070 6c69 6564  ilename supplied
-00014130: 2069 6e20 7468 6973 2070 726f 7065 7274   in this propert
-00014140: 792e 2020 2020 2020 2020 2020 2020 2020  y.              
-00014150: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014160: 2020 2020 2020 2020 2020 2020 207c 2020               |  
-00014170: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014180: 2020 2020 2020 207c 0a7c 2060 7573 6572         |.| `user
-00014190: 4461 7461 4669 6c65 7360 2020 2020 2020  DataFiles`      
-000141a0: 2020 2020 207c 2041 7320 6162 6f76 652c       | As above,
-000141b0: 2062 7574 2063 7265 6174 6520 7468 6520   but create the 
-000141c0: 5573 6572 2044 6174 6120 6279 2063 6f6e  User Data by con
-000141d0: 6361 7465 6e61 7469 6e67 2074 6865 2063  catenating the c
-000141e0: 6f6e 7465 6e74 7320 6f66 2074 6865 206c  ontents of the l
-000141f0: 6973 7420 6f66 2066 696c 656e 616d 6573  ist of filenames
-00014200: 2073 7570 706c 6965 6420 696e 2074 6869   supplied in thi
-00014210: 7320 7072 6f70 6572 7479 2e20 2020 207c  s property.    |
-00014220: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014230: 2020 2020 2020 2020 207c 0a7c 2060 776f           |.| `wo
-00014240: 726b 6572 7350 6572 5643 5055 6020 2020  rkersPerVCPU`   
-00014250: 2020 2020 2020 207c 2054 6865 206e 756d         | The num
-00014260: 6265 7220 6f66 2057 6f72 6b65 7273 2074  ber of Workers t
-00014270: 6f20 6573 7461 626c 6973 6820 7065 7220  o establish per 
-00014280: 7643 5055 206f 6e20 6561 6368 206e 6f64  vCPU on each nod
-00014290: 6520 696e 2074 6865 2057 6f72 6b65 7220  e in the Worker 
-000142a0: 506f 6f6c 2e20 284f 7665 7272 6964 6573  Pool. (Overrides
-000142b0: 2060 776f 726b 6572 7350 6572 4e6f 6465   `workersPerNode
-000142c0: 602e 2920 2020 2020 2020 2020 2020 2020  `.)             
-000142d0: 207c 2020 2020 2020 2020 2020 2020 2020   |              
-000142e0: 2020 2020 2020 2020 2020 207c 0a7c 2060             |.| `
-000142f0: 776f 726b 6572 7350 6572 4e6f 6465 6020  workersPerNode` 
-00014300: 2020 2020 2020 2020 207c 2054 6865 206e           | The n
-00014310: 756d 6265 7220 6f66 2057 6f72 6b65 7273  umber of Workers
-00014320: 2074 6f20 6573 7461 626c 6973 6820 6f6e   to establish on
-00014330: 2065 6163 6820 6e6f 6465 2069 6e20 7468   each node in th
-00014340: 6520 576f 726b 6572 2050 6f6f 6c2e 2020  e Worker Pool.  
-00014350: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014360: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014370: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014380: 2020 207c 2060 3160 2020 2020 2020 2020     | `1`        
-00014390: 2020 2020 2020 2020 2020 2020 207c 0a7c               |.|
-000143a0: 2060 776f 726b 6572 506f 6f6c 4461 7461   `workerPoolData
-000143b0: 6020 2020 2020 2020 2020 207c 2054 6865  `          | The
-000143c0: 206e 616d 6520 6f66 2061 2066 696c 6520   name of a file 
-000143d0: 636f 6e74 6169 6e69 6e67 2061 204a 534f  containing a JSO
-000143e0: 4e20 646f 6375 6d65 6e74 2064 6566 696e  N document defin
-000143f0: 696e 6720 6120 576f 726b 6572 2050 6f6f  ing a Worker Poo
-00014400: 6c2e 2020 2020 2020 2020 2020 2020 2020  l.              
-00014410: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014420: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014430: 2020 2020 207c 2020 2020 2020 2020 2020       |          
-00014440: 2020 2020 2020 2020 2020 2020 2020 207c                 |
-00014450: 0a7c 2060 776f 726b 6572 5461 6760 2020  .| `workerTag`  
-00014460: 2020 2020 2020 2020 2020 2020 207c 2054               | T
-00014470: 6865 2057 6f72 6b65 7220 5461 6720 746f  he Worker Tag to
-00014480: 2070 7562 6c69 7368 2066 6f72 2074 6865   publish for the
-00014490: 2061 6c6c 206f 6620 7468 6520 576f 726b   all of the Work
-000144a0: 6572 7320 6f6e 2074 6865 206e 6f64 652e  ers on the node.
-000144b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000144c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000144d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-000144e0: 2020 2020 2020 207c 2020 2020 2020 2020         |        
-000144f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00014500: 207c 0a0a 2323 2041 7574 6f6d 6174 6963   |..## Automatic
-00014510: 2050 726f 7065 7274 6965 730a 0a54 6865   Properties..The
-00014520: 206e 616d 6520 6f66 2074 6865 2057 6f72   name of the Wor
-00014530: 6b65 7220 506f 6f6c 2c20 6966 206e 6f74  ker Pool, if not
-00014540: 2073 7570 706c 6965 642c 2069 7320 6175   supplied, is au
-00014550: 746f 6d61 7469 6361 6c6c 7920 6765 6e65  tomatically gene
-00014560: 7261 7465 6420 7573 696e 6720 6120 636f  rated using a co
-00014570: 6e63 6174 656e 6174 696f 6e20 6f66 2060  ncatenation of `
-00014580: 7770 5f60 2c20 7468 6520 6074 6167 6020  wp_`, the `tag` 
-00014590: 7072 6f70 6572 7479 2c20 6120 5554 4320  property, a UTC 
-000145a0: 7469 6d65 7374 616d 702c 2061 6e64 2074  timestamp, and t
-000145b0: 6872 6565 2072 616e 646f 6d20 6865 7820  hree random hex 
-000145c0: 6368 6172 6163 7465 7273 3a20 652c 672c  characters: e,g,
-000145d0: 2e20 6077 705f 6d79 7461 675f 3232 3130  . `wp_mytag_2210
-000145e0: 3234 2d31 3535 3532 342d 6230 6160 2e0a  24-155524-b0a`..
-000145f0: 0a23 2320 544f 4d4c 2050 726f 7065 7274  .## TOML Propert
-00014600: 6965 7320 696e 2074 6865 2060 776f 726b  ies in the `work
-00014610: 6572 506f 6f6c 6020 5365 6374 696f 6e0a  erPool` Section.
-00014620: 0a48 6572 6527 7320 616e 2065 7861 6d70  .Here's an examp
-00014630: 6c65 206f 6620 7468 6520 6077 6f72 6b65  le of the `worke
-00014640: 7250 6f6f 6c60 2073 6563 7469 6f6e 206f  rPool` section o
-00014650: 6620 6120 544f 4d4c 2063 6f6e 6669 6775  f a TOML configu
-00014660: 7261 7469 6f6e 2066 696c 652c 2073 686f  ration file, sho
-00014670: 7769 6e67 2061 6c6c 2074 6865 2070 6f73  wing all the pos
-00014680: 7369 626c 6520 7072 6f70 6572 7469 6573  sible properties
-00014690: 2074 6861 7420 6361 6e20 6265 2073 6574   that can be set
-000146a0: 3a0a 0a60 6060 746f 6d6c 0a5b 776f 726b  :..```toml.[work
-000146b0: 6572 506f 6f6c 5d0a 2020 2020 6964 6c65  erPool].    idle
-000146c0: 4e6f 6465 5368 7574 646f 776e 456e 6162  NodeShutdownEnab
-000146d0: 6c65 6420 3d20 7472 7565 0a20 2020 2069  led = true.    i
-000146e0: 646c 654e 6f64 6553 6875 7464 6f77 6e54  dleNodeShutdownT
-000146f0: 696d 656f 7574 203d 2031 302e 300a 2020  imeout = 10.0.  
-00014700: 2020 6964 6c65 506f 6f6c 5368 7574 646f    idlePoolShutdo
-00014710: 776e 456e 6162 6c65 6420 3d20 7472 7565  wnEnabled = true
-00014720: 0a20 2020 2069 646c 6550 6f6f 6c53 6875  .    idlePoolShu
-00014730: 7464 6f77 6e54 696d 656f 7574 203d 2036  tdownTimeout = 6
-00014740: 302e 300a 2020 2020 696d 6167 6573 4964  0.0.    imagesId
-00014750: 203d 2022 7964 6964 3a69 6d67 6661 6d3a   = "ydid:imgfam:
-00014760: 3030 3030 3030 3a34 3139 3632 3539 322d  000000:41962592-
-00014770: 3537 3763 2d34 6664 652d 6162 3033 2d64  577c-4fde-ab03-d
-00014780: 3835 3234 3635 6537 6638 6222 0a20 2020  852465e7f8b".   
-00014790: 2069 6e73 7461 6e63 6554 6167 7320 3d20   instanceTags = 
-000147a0: 7b7d 0a20 2020 206d 6178 4e6f 6465 7320  {}.    maxNodes 
-000147b0: 3d20 310a 2020 2020 6d69 6e4e 6f64 6573  = 1.    minNodes
-000147c0: 203d 2031 0a20 2020 206e 616d 6520 3d20   = 1.    name = 
-000147d0: 226d 792d 776f 726b 6572 2d70 6f6f 6c22  "my-worker-pool"
-000147e0: 0a20 2020 206e 6f64 6542 6f6f 7454 696d  .    nodeBootTim
-000147f0: 656f 7574 203d 2035 0a20 2020 2074 6172  eout = 5.    tar
-00014800: 6765 7449 6e73 7461 6e63 6543 6f75 6e74  getInstanceCount
-00014810: 203d 2031 0a20 2020 2074 656d 706c 6174   = 1.    templat
-00014820: 6549 6420 3d20 2279 6469 643a 6372 743a  eId = "ydid:crt:
-00014830: 4439 4335 3438 3a34 3635 6131 3037 632d  D9C548:465a107c-
-00014840: 3763 6561 2d34 3665 332d 3966 6464 2d31  7cea-46e3-9fdd-1
-00014850: 3531 3136 6362 3932 6334 3022 0a20 2020  5116cb92c40".   
-00014860: 2023 204e 6f74 653a 206f 6e6c 7920 6f6e   # Note: only on
-00014870: 6520 6f66 2027 7573 6572 4461 7461 272f  e of 'userData'/
-00014880: 2775 7365 7244 6174 6146 696c 6527 2f27  'userDataFile'/'
-00014890: 7573 6572 4461 7461 4669 6c65 7327 2073  userDataFiles' s
-000148a0: 686f 756c 6420 6265 2073 6574 0a20 2020  hould be set.   
-000148b0: 2075 7365 7244 6174 6120 3d20 2222 0a20   userData = "". 
-000148c0: 2020 2075 7365 7244 6174 6146 696c 6520     userDataFile 
-000148d0: 3d20 226d 7975 7365 7264 6174 612e 7478  = "myuserdata.tx
-000148e0: 7422 0a20 2020 2075 7365 7244 6174 6146  t".    userDataF
-000148f0: 696c 6573 203d 205b 226d 7975 7365 7264  iles = ["myuserd
-00014900: 6174 6131 2e74 7874 222c 2022 6d79 7573  ata1.txt", "myus
-00014910: 6572 6461 7461 322e 7478 7422 5d0a 2020  erdata2.txt"].  
-00014920: 2020 776f 726b 6572 5461 6720 3d20 2274    workerTag = "t
-00014930: 6167 2d7b 7b75 7365 726e 616d 657d 7d22  ag-{{username}}"
-00014940: 0a20 2020 2023 2053 7065 6369 6679 2065  .    # Specify e
-00014950: 6974 6865 7220 776f 726b 6572 7350 6572  ither workersPer
-00014960: 4e6f 6465 206f 7220 776f 726b 6572 7350  Node or workersP
-00014970: 6572 5643 5055 0a20 2020 2077 6f72 6b65  erVCPU.    worke
-00014980: 7273 5065 724e 6f64 6520 3d20 310a 2020  rsPerNode = 1.  
-00014990: 2020 776f 726b 6572 7350 6572 5643 5055    workersPerVCPU
-000149a0: 203d 2031 0a23 2020 2077 6f72 6b65 7250   = 1.#   workerP
-000149b0: 6f6f 6c44 6174 6120 3d20 2277 6f72 6b65  oolData = "worke
-000149c0: 725f 706f 6f6c 2e6a 736f 6e22 0a60 6060  r_pool.json".```
-000149d0: 0a0a 2323 2057 6f72 6b65 7220 506f 6f6c  ..## Worker Pool
-000149e0: 2053 7065 6369 6669 6361 7469 6f6e 2055   Specification U
-000149f0: 7369 6e67 204a 534f 4e20 446f 6375 6d65  sing JSON Docume
-00014a00: 6e74 730a 0a49 7427 7320 616c 736f 2070  nts..It's also p
-00014a10: 6f73 7369 626c 6520 746f 2063 6170 7475  ossible to captu
-00014a20: 7265 2061 2057 6f72 6b65 7220 506f 6f6c  re a Worker Pool
-00014a30: 2064 6566 696e 6974 696f 6e20 6173 2061   definition as a
-00014a40: 204a 534f 4e20 646f 6375 6d65 6e74 2e20   JSON document. 
-00014a50: 5468 6520 4a53 4f4e 2066 696c 656e 616d  The JSON filenam
-00014a60: 6520 6361 6e20 6265 2073 7570 706c 6965  e can be supplie
-00014a70: 6420 6569 7468 6572 2075 7369 6e67 2074  d either using t
-00014a80: 6865 2063 6f6d 6d61 6e64 206c 696e 6520  he command line 
-00014a90: 7769 7468 2074 6865 2060 2d2d 776f 726b  with the `--work
-00014aa0: 6572 2d70 6f6f 6c60 206f 7220 602d 7060  er-pool` or `-p`
-00014ab0: 2070 6172 616d 6574 6572 2077 6974 6820   parameter with 
-00014ac0: 6079 642d 7072 6f76 6973 696f 6e60 2c20  `yd-provision`, 
-00014ad0: 6f72 2062 7920 706f 7075 6c61 7469 6e67  or by populating
-00014ae0: 2074 6865 2060 776f 726b 6572 506f 6f6c   the `workerPool
-00014af0: 4461 7461 6020 7072 6f70 6572 7479 2069  Data` property i
-00014b00: 6e20 7468 6520 544f 4d4c 2063 6f6e 6669  n the TOML confi
-00014b10: 6775 7261 7469 6f6e 2066 696c 6520 7769  guration file wi
-00014b20: 7468 2074 6865 204a 534f 4e20 6669 6c65  th the JSON file
-00014b30: 6e61 6d65 2e20 436f 6d6d 616e 6420 6c69  name. Command li
-00014b40: 6e65 2073 7065 6369 6669 6361 7469 6f6e  ne specification
-00014b50: 2074 616b 6573 2070 7269 6f72 6974 7920   takes priority 
-00014b60: 6f76 6572 2054 4f4d 4c20 7370 6563 6966  over TOML specif
-00014b70: 6963 6174 696f 6e2e 0a0a 5468 6520 4a53  ication...The JS
-00014b80: 4f4e 2073 7065 6369 6669 6361 7469 6f6e  ON specification
-00014b90: 2061 6c6c 6f77 7320 7468 6520 6372 6561   allows the crea
-00014ba0: 7469 6f6e 206f 6620 2a2a 4164 7661 6e63  tion of **Advanc
-00014bb0: 6564 2057 6f72 6b65 7220 506f 6f6c 732a  ed Worker Pools*
-00014bc0: 2a2c 2077 6974 6820 6469 6666 6572 656e  *, with differen
-00014bd0: 7420 6e6f 6465 2074 7970 6573 2061 6e64  t node types and
-00014be0: 2074 6865 2061 6269 6c69 7479 2074 6f20   the ability to 
-00014bf0: 7370 6563 6966 7920 4e6f 6465 2041 6374  specify Node Act
-00014c00: 696f 6e73 2e0a 0a57 6865 6e20 7573 696e  ions...When usin
-00014c10: 6720 6120 4a53 4f4e 2064 6f63 756d 656e  g a JSON documen
-00014c20: 7420 746f 2073 7065 6369 6679 2074 6865  t to specify the
-00014c30: 2057 6f72 6b65 7220 506f 6f6c 2c20 7468   Worker Pool, th
-00014c40: 6520 7363 6865 6d61 206f 6620 7468 6520  e schema of the 
-00014c50: 646f 6375 6d65 6e74 2069 7320 6964 656e  document is iden
-00014c60: 7469 6361 6c20 746f 2074 6861 7420 6578  tical to that ex
-00014c70: 7065 6374 6564 2062 7920 7468 6520 5965  pected by the Ye
-00014c80: 6c6c 6f77 446f 6720 5245 5354 2041 5049  llowDog REST API
-00014c90: 2066 6f72 2057 6f72 6b65 7220 506f 6f6c   for Worker Pool
-00014ca0: 2050 726f 7669 7369 6f6e 696e 672e 0a0a   Provisioning...
-00014cb0: 2323 2320 576f 726b 6572 2050 6f6f 6c20  ### Worker Pool 
-00014cc0: 4a53 4f4e 2045 7861 6d70 6c65 730a 0a54  JSON Examples..T
-00014cd0: 6865 2065 7861 6d70 6c65 2062 656c 6f77  he example below
-00014ce0: 2069 7320 6f66 2061 2073 696d 706c 6520   is of a simple 
-00014cf0: 4a53 4f4e 2073 7065 6369 6669 6361 7469  JSON specificati
-00014d00: 6f6e 206f 6620 6120 576f 726b 6572 2050  on of a Worker P
-00014d10: 6f6f 6c20 7769 7468 206f 6e65 2069 6e69  ool with one ini
-00014d20: 7469 616c 206e 6f64 652c 2057 6f72 6b65  tial node, Worke
-00014d30: 7220 506f 6f6c 2073 6875 7464 6f77 6e2c  r Pool shutdown,
-00014d40: 2065 7463 2e0a 0a60 6060 6a73 6f6e 0a7b   etc...```json.{
-00014d50: 0a20 2022 7265 7175 6972 656d 656e 7454  .  "requirementT
-00014d60: 656d 706c 6174 6555 7361 6765 223a 207b  emplateUsage": {
-00014d70: 0a20 2020 2022 6d61 696e 7461 696e 496e  .    "maintainIn
-00014d80: 7374 616e 6365 436f 756e 7422 3a20 6661  stanceCount": fa
-00014d90: 6c73 652c 0a20 2020 2022 7265 7175 6972  lse,.    "requir
-00014da0: 656d 656e 744e 616d 6522 3a20 2277 705f  ementName": "wp_
-00014db0: 7079 6578 2d70 7269 6d65 735f 3233 3031  pyex-primes_2301
-00014dc0: 3133 2d31 3631 3532 382d 6461 3022 2c0a  13-161528-da0",.
-00014dd0: 2020 2020 2272 6571 7569 7265 6d65 6e74      "requirement
-00014de0: 4e61 6d65 7370 6163 6522 3a20 2270 7965  Namespace": "pye
-00014df0: 7861 6d70 6c65 7322 2c0a 2020 2020 2272  xamples",.    "r
-00014e00: 6571 7569 7265 6d65 6e74 5461 6722 3a20  equirementTag": 
-00014e10: 2270 7965 782d 7072 696d 6573 222c 0a20  "pyex-primes",. 
-00014e20: 2020 2022 7461 7267 6574 496e 7374 616e     "targetInstan
-00014e30: 6365 436f 756e 7422 3a20 312c 0a20 2020  ceCount": 1,.   
-00014e40: 2022 7465 6d70 6c61 7465 4964 223a 2022   "templateId": "
-00014e50: 7964 6964 3a63 7274 3a44 3943 3534 383a  ydid:crt:D9C548:
-00014e60: 3436 3561 3130 3763 2d37 6365 612d 3436  465a107c-7cea-46
-00014e70: 6533 2d39 6664 642d 3135 3131 3663 6239  e3-9fdd-15116cb9
-00014e80: 3263 3430 220a 2020 7d2c 0a20 2022 7072  2c40".  },.  "pr
-00014e90: 6f76 6973 696f 6e65 6450 726f 7065 7274  ovisionedPropert
-00014ea0: 6965 7322 3a20 7b0a 2020 2020 2269 646c  ies": {.    "idl
-00014eb0: 654e 6f64 6553 6875 7464 6f77 6e22 3a20  eNodeShutdown": 
-00014ec0: 7b22 656e 6162 6c65 6422 3a20 7472 7565  {"enabled": true
-00014ed0: 2c20 2274 696d 656f 7574 223a 2022 5054  , "timeout": "PT
-00014ee0: 3130 4d22 7d2c 0a20 2020 2022 6964 6c65  10M"},.    "idle
-00014ef0: 506f 6f6c 5368 7574 646f 776e 223a 207b  PoolShutdown": {
-00014f00: 2265 6e61 626c 6564 223a 2074 7275 652c  "enabled": true,
-00014f10: 2022 7469 6d65 6f75 7422 3a20 2250 5431   "timeout": "PT1
-00014f20: 4822 7d2c 0a20 2020 2022 6372 6561 7465  H"},.    "create
-00014f30: 4e6f 6465 576f 726b 6572 7322 3a20 7b22  NodeWorkers": {"
-00014f40: 7461 7267 6574 436f 756e 7422 3a20 312c  targetCount": 1,
-00014f50: 2022 7461 7267 6574 5479 7065 223a 2022   "targetType": "
-00014f60: 5045 525f 5643 5055 227d 2c0a 2020 2020  PER_VCPU"},.    
-00014f70: 226d 6178 4e6f 6465 7322 3a20 352c 0a20  "maxNodes": 5,. 
-00014f80: 2020 2022 6d69 6e4e 6f64 6573 223a 2030     "minNodes": 0
-00014f90: 2c0a 2020 2020 226e 6f64 6542 6f6f 7454  ,.    "nodeBootT
-00014fa0: 696d 656f 7574 223a 2022 5054 354d 222c  imeout": "PT5M",
-00014fb0: 0a20 2020 2022 6e6f 6465 4964 6c65 4772  .    "nodeIdleGr
-00014fc0: 6163 6550 6572 696f 6422 3a20 2250 5433  acePeriod": "PT3
-00014fd0: 4d22 2c0a 2020 2020 226e 6f64 6549 646c  M",.    "nodeIdl
-00014fe0: 6554 696d 654c 696d 6974 223a 2022 5054  eTimeLimit": "PT
-00014ff0: 334d 222c 0a20 2020 2022 776f 726b 6572  3M",.    "worker
-00015000: 5461 6722 3a20 2270 7965 782d 6261 7368  Tag": "pyex-bash
-00015010: 2d64 6f63 6b65 7222 0a20 207d 0a7d 0a60  -docker".  }.}.`
-00015020: 6060 0a0a 5468 6520 6e65 7874 2065 7861  ``..The next exa
-00015030: 6d70 6c65 2069 7320 6f66 2061 2072 656c  mple is of a rel
-00015040: 6174 6976 656c 7920 7269 6368 204a 534f  atively rich JSO
-00015050: 4e20 7370 6563 6966 6963 6174 696f 6e20  N specification 
-00015060: 6f66 2061 6e20 4164 7661 6e63 6564 2057  of an Advanced W
-00015070: 6f72 6b65 7220 506f 6f6c 2c20 6672 6f6d  orker Pool, from
-00015080: 206f 6e65 206f 6620 7468 6520 5965 6c6c   one of the Yell
-00015090: 6f77 446f 6720 6465 6d6f 732e 2049 7420  owDog demos. It 
-000150a0: 696e 636c 7564 6573 206e 6f64 6520 7370  includes node sp
-000150b0: 6563 6961 6c69 7361 7469 6f6e 2c20 616e  ecialisation, an
-000150c0: 6420 6163 7469 6f6e 2067 726f 7570 7320  d action groups 
-000150d0: 7468 6174 2072 6573 706f 6e64 2074 6f20  that respond to 
-000150e0: 7468 6520 6053 5441 5254 5550 5f4e 4f44  the `STARTUP_NOD
-000150f0: 4553 5f41 4444 4544 6020 616e 6420 604e  ES_ADDED` and `N
-00015100: 4f44 4553 5f41 4444 4544 6020 6576 656e  ODES_ADDED` even
-00015110: 7473 2074 6f20 6472 6976 6520 2a2a 4e6f  ts to drive **No
-00015120: 6465 2041 6374 696f 6e73 2a2a 2e0a 0a60  de Actions**...`
-00015130: 6060 6a73 6f6e 0a7b 0a20 2022 7265 7175  ``json.{.  "requ
-00015140: 6972 656d 656e 7454 656d 706c 6174 6555  irementTemplateU
-00015150: 7361 6765 223a 207b 0a20 2020 2022 6d61  sage": {.    "ma
-00015160: 696e 7461 696e 496e 7374 616e 6365 436f  intainInstanceCo
-00015170: 756e 7422 3a20 6661 6c73 652c 0a20 2020  unt": false,.   
-00015180: 2022 7461 7267 6574 496e 7374 616e 6365   "targetInstance
-00015190: 436f 756e 7422 3a20 362c 0a20 2020 2022  Count": 6,.    "
-000151a0: 7465 6d70 6c61 7465 4964 223a 2022 7964  templateId": "yd
-000151b0: 6964 3a63 7274 3a44 3943 3534 383a 6137  id:crt:D9C548:a7
-000151c0: 6564 6132 3837 2d66 3964 362d 3462 6338  eda287-f9d6-4bc8
-000151d0: 2d62 3264 632d 3435 3533 3434 3035 3732  -b2dc-4553440572
-000151e0: 3537 222c 0a20 2020 2022 7265 7175 6972  57",.    "requir
-000151f0: 656d 656e 744e 616d 6522 3a20 2277 705f  ementName": "wp_
-00015200: 7079 6578 2d73 6c75 726d 5f32 3330 3131  pyex-slurm_23011
-00015210: 332d 3136 3536 3135 2d32 6237 222c 0a20  3-165615-2b7",. 
-00015220: 2020 2022 7265 7175 6972 656d 656e 744e     "requirementN
-00015230: 616d 6573 7061 6365 223a 2022 7079 6578  amespace": "pyex
-00015240: 616d 706c 6573 222c 0a20 2020 2022 7265  amples",.    "re
-00015250: 7175 6972 656d 656e 7454 6167 223a 2022  quirementTag": "
-00015260: 7079 6578 2d73 6c75 726d 220a 2020 7d2c  pyex-slurm".  },
-00015270: 0a20 2022 7072 6f76 6973 696f 6e65 6450  .  "provisionedP
-00015280: 726f 7065 7274 6965 7322 3a20 7b0a 2020  roperties": {.  
-00015290: 2020 2263 7265 6174 654e 6f64 6557 6f72    "createNodeWor
-000152a0: 6b65 7273 223a 207b 2274 6172 6765 7443  kers": {"targetC
-000152b0: 6f75 6e74 223a 2030 2c20 2274 6172 6765  ount": 0, "targe
-000152c0: 7454 7970 6522 3a20 2250 4552 5f4e 4f44  tType": "PER_NOD
-000152d0: 4522 7d2c 0a20 2020 2022 6e6f 6465 436f  E"},.    "nodeCo
-000152e0: 6e66 6967 7572 6174 696f 6e22 3a20 7b0a  nfiguration": {.
-000152f0: 2020 2020 2020 226e 6f64 6554 7970 6573        "nodeTypes
-00015300: 223a 205b 0a20 2020 2020 2020 207b 226e  ": [.        {"n
-00015310: 616d 6522 3a20 2273 6c75 726d 6374 6c64  ame": "slurmctld
-00015320: 222c 2022 636f 756e 7422 3a20 317d 2c0a  ", "count": 1},.
-00015330: 2020 2020 2020 2020 7b22 6e61 6d65 223a          {"name":
-00015340: 2022 736c 7572 6d64 222c 2022 6d69 6e22   "slurmd", "min"
-00015350: 3a20 352c 2022 736c 6f74 4e75 6d62 6572  : 5, "slotNumber
-00015360: 696e 6722 3a20 2252 4555 5341 424c 4522  ing": "REUSABLE"
-00015370: 7d0a 2020 2020 2020 5d2c 0a20 2020 2020  }.      ],.     
-00015380: 2022 6e6f 6465 4576 656e 7473 223a 207b   "nodeEvents": {
-00015390: 0a20 2020 2020 2020 2022 5354 4152 5455  .        "STARTU
-000153a0: 505f 4e4f 4445 535f 4144 4445 4422 3a20  P_NODES_ADDED": 
-000153b0: 5b0a 2020 2020 2020 2020 2020 7b0a 2020  [.          {.  
-000153c0: 2020 2020 2020 2020 2020 2261 6374 696f            "actio
-000153d0: 6e73 223a 205b 0a20 2020 2020 2020 2020  ns": [.         
-000153e0: 2020 2020 207b 0a20 2020 2020 2020 2020       {.         
-000153f0: 2020 2020 2020 2022 6163 7469 6f6e 223a         "action":
-00015400: 2022 5752 4954 455f 4649 4c45 222c 0a20   "WRITE_FILE",. 
-00015410: 2020 2020 2020 2020 2020 2020 2020 2022                 "
-00015420: 7061 7468 223a 2022 6e6f 6465 732e 6a73  path": "nodes.js
-00015430: 6f6e 222c 0a20 2020 2020 2020 2020 2020  on",.           
-00015440: 2020 2020 2022 636f 6e74 656e 7422 3a20       "content": 
-00015450: 227b 5c6e 2020 5c22 6e6f 6465 735c 223a  "{\n  \"nodes\":
-00015460: 205b 5c6e 7b7b 236f 7468 6572 4e6f 6465   [\n{{#otherNode
-00015470: 737d 7d5c 6e20 2020 207b 5c6e 2020 2020  s}}\n    {\n    
-00015480: 2020 5c22 6e61 6d65 5c22 3a20 5c22 736c    \"name\": \"sl
-00015490: 7572 6d64 7b7b 6465 7461 696c 732e 6e6f  urmd{{details.no
-000154a0: 6465 536c 6f74 7d7d 5c22 2c5c 6e20 2020  deSlot}}\",\n   
-000154b0: 2020 205c 2269 705c 223a 205c 227b 7b64     \"ip\": \"{{d
-000154c0: 6574 6169 6c73 2e70 7269 7661 7465 4970  etails.privateIp
-000154d0: 4164 6472 6573 737d 7d5c 225c 6e20 2020  Address}}\"\n   
-000154e0: 207d 7b7b 5e2d 6c61 7374 7d7d 2c7b 7b2f   }{{^-last}},{{/
-000154f0: 2d6c 6173 747d 7d5c 6e7b 7b2f 6f74 6865  -last}}\n{{/othe
-00015500: 724e 6f64 6573 7d7d 5c6e 2020 5d5c 6e7d  rNodes}}\n  ]\n}
-00015510: 222c 0a20 2020 2020 2020 2020 2020 2020  ",.             
-00015520: 2020 2022 6e6f 6465 5479 7065 7322 3a20     "nodeTypes": 
-00015530: 5b22 736c 7572 6d63 746c 6422 5d0a 2020  ["slurmctld"].  
-00015540: 2020 2020 2020 2020 2020 2020 7d2c 0a20              },. 
-00015550: 2020 2020 2020 2020 2020 2020 207b 0a20               {. 
-00015560: 2020 2020 2020 2020 2020 2020 2020 2022                 "
-00015570: 6163 7469 6f6e 223a 2022 5255 4e5f 434f  action": "RUN_CO
-00015580: 4d4d 414e 4422 2c0a 2020 2020 2020 2020  MMAND",.        
-00015590: 2020 2020 2020 2020 2270 6174 6822 3a20          "path": 
-000155a0: 2273 7461 7274 5f73 696d 706c 655f 736c  "start_simple_sl
-000155b0: 7572 6d63 746c 6422 2c0a 2020 2020 2020  urmctld",.      
-000155c0: 2020 2020 2020 2020 2020 2261 7267 756d            "argum
-000155d0: 656e 7473 223a 205b 226e 6f64 6573 2e6a  ents": ["nodes.j
-000155e0: 736f 6e22 5d2c 0a20 2020 2020 2020 2020  son"],.         
-000155f0: 2020 2020 2020 2022 656e 7669 726f 6e6d         "environm
-00015600: 656e 7422 3a20 7b22 4558 414d 504c 4522  ent": {"EXAMPLE"
-00015610: 3a20 2246 4f4f 227d 2c0a 2020 2020 2020  : "FOO"},.      
-00015620: 2020 2020 2020 2020 2020 226e 6f64 6554            "nodeT
-00015630: 7970 6573 223a 205b 2273 6c75 726d 6374  ypes": ["slurmct
-00015640: 6c64 225d 0a20 2020 2020 2020 2020 2020  ld"].           
-00015650: 2020 207d 0a20 2020 2020 2020 2020 2020     }.           
-00015660: 205d 0a20 2020 2020 2020 2020 207d 2c0a   ].          },.
-00015670: 2020 2020 2020 2020 2020 7b0a 2020 2020            {.    
-00015680: 2020 2020 2020 2020 2261 6374 696f 6e73          "actions
-00015690: 223a 205b 0a20 2020 2020 2020 2020 2020  ": [.           
-000156a0: 2020 207b 0a20 2020 2020 2020 2020 2020     {.           
-000156b0: 2020 2020 2022 6163 7469 6f6e 223a 2022       "action": "
-000156c0: 5255 4e5f 434f 4d4d 414e 4422 2c0a 2020  RUN_COMMAND",.  
-000156d0: 2020 2020 2020 2020 2020 2020 2020 2270                "p
-000156e0: 6174 6822 3a20 2273 7461 7274 5f73 696d  ath": "start_sim
-000156f0: 706c 655f 736c 7572 6d64 222c 0a20 2020  ple_slurmd",.   
-00015700: 2020 2020 2020 2020 2020 2020 2022 6172               "ar
-00015710: 6775 6d65 6e74 7322 3a20 5b22 7b7b 6e6f  guments": ["{{no
-00015720: 6465 7342 7954 7970 652e 736c 7572 6d63  desByType.slurmc
-00015730: 746c 642e 302e 6465 7461 696c 732e 7072  tld.0.details.pr
-00015740: 6976 6174 6549 7041 6464 7265 7373 7d7d  ivateIpAddress}}
-00015750: 222c 2022 7b7b 6e6f 6465 2e64 6574 6169  ", "{{node.detai
-00015760: 6c73 2e6e 6f64 6553 6c6f 747d 7d22 5d2c  ls.nodeSlot}}"],
-00015770: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
-00015780: 2022 6e6f 6465 5479 7065 7322 3a20 5b22   "nodeTypes": ["
-00015790: 736c 7572 6d64 225d 0a20 2020 2020 2020  slurmd"].       
-000157a0: 2020 2020 2020 207d 0a20 2020 2020 2020         }.       
-000157b0: 2020 2020 205d 0a20 2020 2020 2020 2020       ].         
-000157c0: 207d 2c0a 2020 2020 2020 2020 2020 7b0a   },.          {.
-000157d0: 2020 2020 2020 2020 2020 2020 2261 6374              "act
-000157e0: 696f 6e73 223a 205b 0a20 2020 2020 2020  ions": [.       
-000157f0: 2020 2020 2020 207b 0a20 2020 2020 2020         {.       
-00015800: 2020 2020 2020 2020 2022 6163 7469 6f6e           "action
-00015810: 223a 2022 4352 4541 5445 5f57 4f52 4b45  ": "CREATE_WORKE
-00015820: 5253 222c 0a20 2020 2020 2020 2020 2020  RS",.           
-00015830: 2020 2020 2022 746f 7461 6c57 6f72 6b65       "totalWorke
-00015840: 7273 223a 2031 2c0a 2020 2020 2020 2020  rs": 1,.        
-00015850: 2020 2020 2020 2020 226e 6f64 6554 7970          "nodeTyp
-00015860: 6573 223a 205b 2273 6c75 726d 6374 6c64  es": ["slurmctld
-00015870: 225d 0a20 2020 2020 2020 2020 2020 2020  "].             
-00015880: 207d 0a20 2020 2020 2020 2020 2020 205d   }.            ]
-00015890: 0a20 2020 2020 2020 2020 207d 0a20 2020  .          }.   
-000158a0: 2020 2020 205d 2c0a 2020 2020 2020 2020       ],.        
-000158b0: 224e 4f44 4553 5f41 4444 4544 223a 205b  "NODES_ADDED": [
-000158c0: 0a20 2020 2020 2020 2020 207b 0a20 2020  .          {.   
-000158d0: 2020 2020 2020 2020 2022 6163 7469 6f6e           "action
-000158e0: 7322 3a20 5b0a 2020 2020 2020 2020 2020  s": [.          
-000158f0: 2020 2020 7b0a 2020 2020 2020 2020 2020      {.          
-00015900: 2020 2020 2020 2261 6374 696f 6e22 3a20        "action": 
-00015910: 2257 5249 5445 5f46 494c 4522 2c0a 2020  "WRITE_FILE",.  
-00015920: 2020 2020 2020 2020 2020 2020 2020 2270                "p
-00015930: 6174 6822 3a20 226e 6f64 6573 2e6a 736f  ath": "nodes.jso
-00015940: 6e22 2c0a 2020 2020 2020 2020 2020 2020  n",.            
-00015950: 2020 2020 2263 6f6e 7465 6e74 223a 2022      "content": "
-00015960: 7b5c 6e20 205c 226e 6f64 6573 5c22 3a20  {\n  \"nodes\": 
-00015970: 5b5c 6e7b 7b23 6669 6c74 6572 6564 4e6f  [\n{{#filteredNo
-00015980: 6465 737d 7d5c 6e20 2020 207b 5c6e 2020  des}}\n    {\n  
-00015990: 2020 2020 5c22 6e61 6d65 5c22 3a20 5c22      \"name\": \"
-000159a0: 736c 7572 6d64 7b7b 6465 7461 696c 732e  slurmd{{details.
-000159b0: 6e6f 6465 536c 6f74 7d7d 5c22 2c5c 6e20  nodeSlot}}\",\n 
-000159c0: 2020 2020 205c 2269 705c 223a 205c 227b       \"ip\": \"{
-000159d0: 7b64 6574 6169 6c73 2e70 7269 7661 7465  {details.private
-000159e0: 4970 4164 6472 6573 737d 7d5c 225c 6e20  IpAddress}}\"\n 
-000159f0: 2020 207d 7b7b 5e2d 6c61 7374 7d7d 2c7b     }{{^-last}},{
-00015a00: 7b2f 2d6c 6173 747d 7d5c 6e7b 7b2f 6669  {/-last}}\n{{/fi
-00015a10: 6c74 6572 6564 4e6f 6465 737d 7d5c 6e20  lteredNodes}}\n 
-00015a20: 205d 5c6e 7d22 2c0a 2020 2020 2020 2020   ]\n}",.        
-00015a30: 2020 2020 2020 2020 226e 6f64 6554 7970          "nodeTyp
-00015a40: 6573 223a 205b 2273 6c75 726d 6374 6c64  es": ["slurmctld
-00015a50: 225d 0a20 2020 2020 2020 2020 2020 2020  "].             
-00015a60: 207d 2c0a 2020 2020 2020 2020 2020 2020   },.            
-00015a70: 2020 7b0a 2020 2020 2020 2020 2020 2020    {.            
-00015a80: 2020 2020 2261 6374 696f 6e22 3a20 2252      "action": "R
-00015a90: 554e 5f43 4f4d 4d41 4e44 222c 0a20 2020  UN_COMMAND",.   
-00015aa0: 2020 2020 2020 2020 2020 2020 2022 7061               "pa
-00015ab0: 7468 223a 2022 6164 645f 6e6f 6465 7322  th": "add_nodes"
-00015ac0: 2c0a 2020 2020 2020 2020 2020 2020 2020  ,.              
-00015ad0: 2020 2261 7267 756d 656e 7473 223a 205b    "arguments": [
-00015ae0: 226e 6f64 6573 2e6a 736f 6e22 5d2c 0a20  "nodes.json"],. 
-00015af0: 2020 2020 2020 2020 2020 2020 2020 2022                 "
-00015b00: 6e6f 6465 5479 7065 7322 3a20 5b22 736c  nodeTypes": ["sl
-00015b10: 7572 6d63 746c 6422 5d0a 2020 2020 2020  urmctld"].      
-00015b20: 2020 2020 2020 2020 7d0a 2020 2020 2020          }.      
-00015b30: 2020 2020 2020 5d0a 2020 2020 2020 2020        ].        
-00015b40: 2020 7d2c 0a20 2020 2020 2020 2020 207b    },.          {
-00015b50: 0a20 2020 2020 2020 2020 2020 2022 6163  .            "ac
-00015b60: 7469 6f6e 7322 3a20 5b0a 2020 2020 2020  tions": [.      
-00015b70: 2020 2020 2020 2020 7b0a 2020 2020 2020          {.      
-00015b80: 2020 2020 2020 2020 2020 2261 6374 696f            "actio
-00015b90: 6e22 3a20 2252 554e 5f43 4f4d 4d41 4e44  n": "RUN_COMMAND
-00015ba0: 222c 0a20 2020 2020 2020 2020 2020 2020  ",.             
-00015bb0: 2020 2022 7061 7468 223a 2022 7374 6172     "path": "star
-00015bc0: 745f 7369 6d70 6c65 5f73 6c75 726d 6422  t_simple_slurmd"
-00015bd0: 2c0a 2020 2020 2020 2020 2020 2020 2020  ,.              
-00015be0: 2020 2261 7267 756d 656e 7473 223a 205b    "arguments": [
-00015bf0: 227b 7b6e 6f64 6573 4279 5479 7065 2e73  "{{nodesByType.s
-00015c00: 6c75 726d 6374 6c64 2e30 2e64 6574 6169  lurmctld.0.detai
-00015c10: 6c73 2e70 7269 7661 7465 4970 4164 6472  ls.privateIpAddr
-00015c20: 6573 737d 7d22 2c20 227b 7b6e 6f64 652e  ess}}", "{{node.
-00015c30: 6465 7461 696c 732e 6e6f 6465 536c 6f74  details.nodeSlot
-00015c40: 7d7d 225d 2c0a 2020 2020 2020 2020 2020  }}"],.          
-00015c50: 2020 2020 2020 226e 6f64 6549 6446 696c        "nodeIdFil
-00015c60: 7465 7222 3a20 2245 5645 4e54 222c 0a20  ter": "EVENT",. 
-00015c70: 2020 2020 2020 2020 2020 2020 2020 2022                 "
-00015c80: 6e6f 6465 5479 7065 7322 3a20 5b22 736c  nodeTypes": ["sl
-00015c90: 7572 6d64 225d 0a20 2020 2020 2020 2020  urmd"].         
-00015ca0: 2020 2020 207d 0a20 2020 2020 2020 2020       }.         
-00015cb0: 2020 205d 0a20 2020 2020 2020 2020 207d     ].          }
-00015cc0: 0a20 2020 2020 2020 205d 0a20 2020 2020  .        ].     
-00015cd0: 207d 0a20 2020 207d 2c0a 2020 2020 2277   }.    },.    "w
-00015ce0: 6f72 6b65 7254 6167 223a 2022 7079 6578  orkerTag": "pyex
-00015cf0: 2d73 6c75 726d 2d63 6c75 7374 6572 220a  -slurm-cluster".
-00015d00: 2020 7d0a 7d0a 6060 600a 0a23 2323 2054    }.}.```..### T
-00015d10: 4f4d 4c20 5072 6f70 6572 7469 6573 2049  OML Properties I
-00015d20: 6e68 6572 6974 6564 2062 7920 576f 726b  nherited by Work
-00015d30: 6572 2050 6f6f 6c20 4a53 4f4e 2053 7065  er Pool JSON Spe
-00015d40: 6369 6669 6361 7469 6f6e 730a 0a57 6865  cifications..Whe
-00015d50: 6e20 6120 4a53 4f4e 2057 6f72 6b65 7220  n a JSON Worker 
-00015d60: 506f 6f6c 2073 7065 6369 6669 6361 7469  Pool specificati
-00015d70: 6f6e 2069 7320 7573 6564 2c20 7468 6520  on is used, the 
-00015d80: 666f 6c6c 6f77 696e 6720 7072 6f70 6572  following proper
-00015d90: 7469 6573 2066 726f 6d20 7468 6520 6063  ties from the `c
-00015da0: 6f6e 6669 672e 746f 6d6c 6020 6669 6c65  onfig.toml` file
-00015db0: 2077 696c 6c20 6265 2069 6e68 6572 6974   will be inherit
-00015dc0: 6564 2069 6620 7468 6520 7661 6c75 6520  ed if the value 
-00015dd0: 6973 2061 6273 656e 7420 696e 2074 6865  is absent in the
-00015de0: 204a 534f 4e20 6669 6c65 3a0a 0a2a 2a50   JSON file:..**P
-00015df0: 726f 7065 7274 6965 7320 496e 6865 7269  roperties Inheri
-00015e00: 7465 6420 7769 7468 696e 2074 6865 2060  ted within the `
-00015e10: 7265 7175 6972 656d 656e 7454 656d 706c  requirementTempl
-00015e20: 6174 6555 7361 6765 6020 7072 6f70 6572  ateUsage` proper
-00015e30: 7479 2a2a 0a0a 2d20 6069 6d61 6765 7349  ty**..- `imagesI
-00015e40: 6460 0a2d 2060 696e 7374 616e 6365 5461  d`.- `instanceTa
-00015e50: 6773 600a 2d20 6072 6571 7569 7265 6d65  gs`.- `requireme
-00015e60: 6e74 4e61 6d65 603a 2064 6572 6976 6564  ntName`: derived
-00015e70: 2066 726f 6d20 7468 6520 606e 616d 6560   from the `name`
-00015e80: 2070 726f 7065 7274 7920 696e 2074 6865   property in the
-00015e90: 2060 544f 4d4c 6020 636f 6e66 6967 7572   `TOML` configur
-00015ea0: 6174 696f 6e2e 2028 5468 6520 6e61 6d65  ation. (The name
-00015eb0: 2077 696c 6c20 6265 2067 656e 6572 6174   will be generat
-00015ec0: 6564 2061 7574 6f6d 6174 6963 616c 6c79  ed automatically
-00015ed0: 2069 6620 6e6f 7420 7375 7070 6c69 6564   if not supplied
-00015ee0: 2069 6e20 6569 7468 6572 2074 6865 2054   in either the T
-00015ef0: 4f4d 4c20 6669 6c65 206f 7220 7468 6520  OML file or the 
-00015f00: 4a53 4f4e 2073 7065 6369 6669 6361 7469  JSON specificati
-00015f10: 6f6e 2e29 0a2d 2060 7265 7175 6972 656d  on.).- `requirem
-00015f20: 656e 744e 616d 6573 7061 6365 603a 2064  entNamespace`: d
-00015f30: 6572 6976 6564 2066 726f 6d20 7468 6520  erived from the 
-00015f40: 606e 616d 6573 7061 6365 6020 7072 6f70  `namespace` prop
-00015f50: 6572 7479 2069 6e20 7468 6520 6054 4f4d  erty in the `TOM
-00015f60: 4c60 2063 6f6e 6669 6775 7261 7469 6f6e  L` configuration
-00015f70: 0a2d 2060 7265 7175 6972 656d 656e 7454  .- `requirementT
-00015f80: 6167 603a 203a 2064 6572 6976 6564 2066  ag`: : derived f
-00015f90: 726f 6d20 7468 6520 6074 6167 6020 7072  rom the `tag` pr
-00015fa0: 6f70 6572 7479 2069 6e20 7468 6520 6054  operty in the `T
-00015fb0: 4f4d 4c60 2063 6f6e 6669 6775 7261 7469  OML` configurati
-00015fc0: 6f6e 0a2d 2060 7461 7267 6574 496e 7374  on.- `targetInst
-00015fd0: 616e 6365 436f 756e 7460 0a2d 2060 7465  anceCount`.- `te
-00015fe0: 6d70 6c61 7465 4964 600a 2d20 6075 7365  mplateId`.- `use
-00015ff0: 7244 6174 6160 0a2d 2060 7573 6572 4461  rData`.- `userDa
-00016000: 7461 4669 6c65 600a 2d20 6075 7365 7244  taFile`.- `userD
-00016010: 6174 6146 696c 6573 600a 0a2a 2a50 726f  ataFiles`..**Pro
-00016020: 7065 7274 6965 7320 496e 6865 7269 7465  perties Inherite
-00016030: 6420 7769 7468 696e 2074 6865 2060 7072  d within the `pr
-00016040: 6f76 6973 696f 6e65 6450 726f 7065 7274  ovisionedPropert
-00016050: 6965 7360 2050 726f 7065 7274 792a 2a0a  ies` Property**.
-00016060: 0a2d 2060 6964 6c65 4e6f 6465 5368 7574  .- `idleNodeShut
-00016070: 646f 776e 456e 6162 6c65 6460 0a2d 2060  downEnabled`.- `
-00016080: 6964 6c65 4e6f 6465 5368 7574 646f 776e  idleNodeShutdown
-00016090: 5469 6d65 6f75 7460 0a2d 2060 6964 6c65  Timeout`.- `idle
-000160a0: 506f 6f6c 5368 7574 646f 776e 456e 6162  PoolShutdownEnab
-000160b0: 6c65 6460 0a2d 2060 6964 6c65 506f 6f6c  led`.- `idlePool
-000160c0: 5368 7574 646f 776e 5469 6d65 6f75 7460  ShutdownTimeout`
-000160d0: 0a2d 2060 6e6f 6465 426f 6f74 5469 6d65  .- `nodeBootTime
-000160e0: 6f75 7460 0a2d 2060 776f 726b 6572 5461  out`.- `workerTa
-000160f0: 6760 0a0a 2323 2056 6172 6961 626c 6520  g`..## Variable 
-00016100: 5375 6273 7469 7475 7469 6f6e 7320 696e  Substitutions in
-00016110: 2057 6f72 6b65 7220 506f 6f6c 2050 726f   Worker Pool Pro
-00016120: 7065 7274 6965 730a 0a56 6172 6961 626c  perties..Variabl
-00016130: 6520 7375 6273 7469 7475 7469 6f6e 7320  e substitutions 
-00016140: 6361 6e20 6265 2075 7365 6420 7769 7468  can be used with
-00016150: 696e 2061 6e79 2070 726f 7065 7274 7920  in any property 
-00016160: 7661 6c75 6520 696e 2054 4f4d 4c20 636f  value in TOML co
-00016170: 6e66 6967 7572 6174 696f 6e20 6669 6c65  nfiguration file
-00016180: 7320 6f72 2057 6f72 6b65 7220 506f 6f6c  s or Worker Pool
-00016190: 204a 534f 4e20 6669 6c65 732e 2053 6565   JSON files. See
-000161a0: 2074 6865 2064 6573 6372 6970 7469 6f6e   the description
-000161b0: 205b 6162 6f76 655d 2823 7661 7269 6162   [above](#variab
-000161c0: 6c65 2d73 7562 7374 6974 7574 696f 6e73  le-substitutions
-000161d0: 2920 666f 7220 6d6f 7265 2064 6574 6169  ) for more detai
-000161e0: 6c73 206f 6e20 7661 7269 6162 6c65 2073  ls on variable s
-000161f0: 7562 7374 6974 7574 696f 6e73 2e20 5468  ubstitutions. Th
-00016200: 6973 2069 7320 6120 706f 7765 7266 756c  is is a powerful
-00016210: 2066 6561 7475 7265 2074 6861 7420 616c   feature that al
-00016220: 6c6f 7773 2057 6f72 6b65 7220 506f 6f6c  lows Worker Pool
-00016230: 7320 746f 2062 6520 7061 7261 6d65 7465  s to be paramete
-00016240: 7269 7365 6420 6279 2073 7570 706c 7969  rised by supplyi
-00016250: 6e67 2076 616c 7565 7320 6f6e 2074 6865  ng values on the
-00016260: 2063 6f6d 6d61 6e64 206c 696e 652c 2076   command line, v
-00016270: 6961 2065 6e76 6972 6f6e 6d65 6e74 2076  ia environment v
-00016280: 6172 6961 626c 6573 2c20 6f72 2076 6961  ariables, or via
-00016290: 2074 6865 2054 4f4d 4c20 6669 6c65 2e0a   the TOML file..
-000162a0: 0a41 6e20 696d 706f 7274 616e 7420 6469  .An important di
-000162b0: 7374 696e 6374 696f 6e20 2a2a 6f6e 6c79  stinction **only
-000162c0: 2a2a 2077 6865 6e20 7573 696e 6720 7661  ** when using va
-000162d0: 7269 6162 6c65 2073 7562 7374 6974 7574  riable substitut
-000162e0: 696f 6e73 2077 6974 6869 6e20 576f 726b  ions within Work
-000162f0: 6572 2050 6f6f 6c20 4a53 4f4e 2064 6f63  er Pool JSON doc
-00016300: 756d 656e 7473 2069 7320 7468 6174 2065  uments is that e
-00016310: 6163 6820 6469 7265 6374 6976 6520 2a2a  ach directive **
-00016320: 6d75 7374 2062 6520 7072 6563 6564 6564  must be preceded
-00016330: 2062 7920 6120 605f 5f60 2028 646f 7562   by a `__` (doub
-00016340: 6c65 2075 6e64 6572 7363 6f72 6529 2a2a  le underscore)**
-00016350: 2074 6f20 6469 7361 6d62 6967 7561 7465   to disambiguate
-00016360: 2069 7420 6672 6f6d 2076 6172 6961 626c   it from variabl
-00016370: 6520 7375 6273 7469 7475 7469 6f6e 7320  e substitutions 
-00016380: 7468 6174 2061 7265 2074 6f20 6265 2070  that are to be p
-00016390: 6173 7365 6420 6469 7265 6374 6c79 2074  assed directly t
-000163a0: 6f20 7468 6520 4150 492e 2046 6f72 2065  o the API. For e
-000163b0: 7861 6d70 6c65 2c20 7573 653a 2060 5f5f  xample, use: `__
-000163c0: 7b7b 7573 6572 6e61 6d65 7d7d 6020 746f  {{username}}` to
-000163d0: 2061 7070 6c79 2061 2073 7562 7374 6974   apply a substit
-000163e0: 7574 696f 6e20 666f 7220 7468 6520 6075  ution for the `u
-000163f0: 7365 726e 616d 6560 2064 6566 6175 6c74  sername` default
-00016400: 2073 7562 7374 6974 7574 696f 6e2e 0a0a   substitution...
-00016410: 2323 2044 7279 2d52 756e 6e69 6e67 2057  ## Dry-Running W
-00016420: 6f72 6b65 7220 506f 6f6c 2050 726f 7669  orker Pool Provi
-00016430: 7369 6f6e 696e 670a 0a54 6f20 6578 616d  sioning..To exam
-00016440: 696e 6520 7468 6520 4a53 4f4e 2074 6861  ine the JSON tha
-00016450: 7420 7769 6c6c 2061 6374 7561 6c6c 7920  t will actually 
-00016460: 6265 2073 656e 7420 746f 2074 6865 2059  be sent to the Y
-00016470: 656c 6c6f 7744 6f67 2041 5049 2061 6674  ellowDog API aft
-00016480: 6572 2061 6c6c 2070 726f 6365 7373 696e  er all processin
-00016490: 672c 2075 7365 2074 6865 2060 2d2d 6472  g, use the `--dr
-000164a0: 792d 7275 6e60 2063 6f6d 6d61 6e64 206c  y-run` command l
-000164b0: 696e 6520 6f70 7469 6f6e 2077 6865 6e20  ine option when 
-000164c0: 7275 6e6e 696e 6720 6079 642d 7072 6f76  running `yd-prov
-000164d0: 6973 696f 6e60 2e20 5468 6973 2077 696c  ision`. This wil
-000164e0: 6c20 7072 696e 7420 7468 6520 4a53 4f4e  l print the JSON
-000164f0: 2073 7065 6369 6669 6361 7469 6f6e 2066   specification f
-00016500: 6f72 2074 6865 2057 6f72 6b65 7220 506f  or the Worker Po
-00016510: 6f6c 2e20 4e6f 7468 696e 6720 7769 6c6c  ol. Nothing will
-00016520: 2062 6520 7375 626d 6974 7465 6420 746f   be submitted to
-00016530: 2074 6865 2070 6c61 7466 6f72 6d2e 0a0a   the platform...
-00016540: 5468 6520 6765 6e65 7261 7465 6420 4a53  The generated JS
-00016550: 4f4e 2069 7320 7072 6f64 7563 6564 2061  ON is produced a
-00016560: 6674 6572 2061 6c6c 2070 726f 6365 7373  fter all process
-00016570: 696e 6720 2869 6e63 6f72 706f 7261 7469  ing (incorporati
-00016580: 6e67 2060 636f 6e66 6967 2e74 6f6d 6c60  ng `config.toml`
-00016590: 2070 726f 7065 7274 6965 732c 2076 6172   properties, var
-000165a0: 6961 626c 6520 7375 6273 7469 7475 7469  iable substituti
-000165b0: 6f6e 732c 2065 7463 2e29 2068 6173 2062  ons, etc.) has b
-000165c0: 6565 6e20 636f 6e63 6c75 6465 642c 2073  een concluded, s
-000165d0: 6f20 7468 6520 6472 792d 7275 6e20 6973  o the dry-run is
-000165e0: 2075 7365 6675 6c20 666f 7220 696e 7370   useful for insp
-000165f0: 6563 7469 6e67 2074 6865 2072 6573 756c  ecting the resul
-00016600: 7473 206f 6620 616c 6c20 7468 6520 7072  ts of all the pr
-00016610: 6f63 6573 7369 6e67 2074 6861 7427 7320  ocessing that's 
-00016620: 6265 656e 2070 6572 666f 726d 6564 2e0a  been performed..
-00016630: 0a54 6f20 7375 7070 7265 7373 2061 6c6c  .To suppress all
-00016640: 206f 7574 7075 7420 6578 6365 7074 2066   output except f
-00016650: 6f72 2074 6865 204a 534f 4e20 6974 7365  or the JSON itse
-00016660: 6c66 2c20 7573 6520 7468 6520 602d 2d71  lf, use the `--q
-00016670: 7569 6574 6020 2860 2d71 6029 2063 6f6d  uiet` (`-q`) com
-00016680: 6d61 6e64 206c 696e 6520 6f70 7469 6f6e  mand line option
-00016690: 2e0a 0a54 6865 204a 534f 4e20 6472 792d  ...The JSON dry-
-000166a0: 7275 6e20 6f75 7470 7574 2063 6f75 6c64  run output could
-000166b0: 2069 7473 656c 6620 6265 2075 7365 6420   itself be used 
-000166c0: 6279 2060 7964 2d70 726f 7669 7369 6f6e  by `yd-provision
-000166d0: 602c 2069 6620 6361 7074 7572 6564 2069  `, if captured i
-000166e0: 6e20 6120 6669 6c65 2c20 652e 672e 3a0a  n a file, e.g.:.
-000166f0: 0a60 6060 7368 656c 6c0a 7964 2d70 726f  .```shell.yd-pro
-00016700: 7669 7369 6f6e 202d 2d64 7279 2d72 756e  vision --dry-run
-00016710: 202d 7120 3e20 6d79 5f77 6f72 6b65 725f   -q > my_worker_
-00016720: 706f 6f6c 2e6a 736f 6e0a 7964 2d70 726f  pool.json.yd-pro
-00016730: 7669 7369 6f6e 202d 7020 6d79 5f77 6f72  vision -p my_wor
-00016740: 6b65 725f 706f 6f6c 2e6a 736f 6e0a 6060  ker_pool.json.``
-00016750: 600a 0a23 204a 736f 6e6e 6574 2053 7570  `..# Jsonnet Sup
-00016760: 706f 7274 0a0a 496e 2061 6c6c 2063 6972  port..In all cir
-00016770: 6375 6d73 7461 6e63 6573 2077 6865 7265  cumstances where
-00016780: 204a 534f 4e20 6669 6c65 7320 6172 6520   JSON files are 
-00016790: 7573 6564 2062 7920 7468 6520 5079 7468  used by the Pyth
-000167a0: 6f6e 2045 7861 6d70 6c65 7320 7363 7269  on Examples scri
-000167b0: 7074 732c 2020 2a2a 5b4a 736f 6e6e 6574  pts,  **[Jsonnet
-000167c0: 5d28 6874 7470 733a 2f2f 6a73 6f6e 6e65  ](https://jsonne
-000167d0: 742e 6f72 6729 2a2a 2066 696c 6573 2063  t.org)** files c
-000167e0: 616e 2062 6520 7573 6564 2069 6e73 7465  an be used inste
-000167f0: 6164 2e20 5468 6973 2061 6c6c 6f77 7320  ad. This allows 
-00016800: 7468 6520 7573 6520 6f66 204a 736f 6e6e  the use of Jsonn
-00016810: 6574 2773 2070 6f77 6572 6675 6c20 4a53  et's powerful JS
-00016820: 4f4e 2065 7874 656e 7369 6f6e 732c 2069  ON extensions, i
-00016830: 6e63 6c75 6469 6e67 2063 6f6d 6d65 6e74  ncluding comment
-00016840: 732c 2076 6172 6961 626c 6573 2c20 6675  s, variables, fu
-00016850: 6e63 7469 6f6e 732c 2065 7463 2e0a 0a41  nctions, etc...A
-00016860: 2073 696d 706c 6520 7573 6167 6520 6578   simple usage ex
-00016870: 616d 706c 6520 6d69 6768 7420 6265 3a0a  ample might be:.
-00016880: 0a60 6060 7368 656c 6c0a 7964 2d73 7562  .```shell.yd-sub
-00016890: 6d69 7420 2d2d 776f 726b 2d72 6571 7569  mit --work-requi
-000168a0: 7265 6d65 6e74 206d 795f 776f 726b 5f72  rement my_work_r
-000168b0: 6571 2e6a 736f 6e6e 6574 0a60 6060 0a0a  eq.jsonnet.```..
-000168c0: 5468 6520 7573 6520 6f66 2074 6865 2066  The use of the f
-000168d0: 696c 656e 616d 6520 6578 7465 6e73 696f  ilename extensio
-000168e0: 6e20 602e 6a73 6f6e 6e65 7460 2077 696c  n `.jsonnet` wil
-000168f0: 6c20 696e 766f 6b65 204a 736f 6e6e 6574  l invoke Jsonnet
-00016900: 2065 7661 6c75 6174 696f 6e2e 2028 4e6f   evaluation. (No
-00016910: 7465 2074 6861 7420 6120 7465 6d70 6f72  te that a tempor
-00016920: 6172 7920 4a53 4f4e 2066 696c 6520 6973  ary JSON file is
-00016930: 2063 7265 6174 6564 2061 7320 7061 7274   created as part
-00016940: 206f 6620 4a73 6f6e 6e65 7420 7072 6f63   of Jsonnet proc
-00016950: 6573 7369 6e67 2c20 7768 6963 6820 796f  essing, which yo
-00016960: 7520 6d61 7920 7365 6520 7265 6665 7272  u may see referr
-00016970: 6564 2074 6f20 696e 2065 7272 6f72 206d  ed to in error m
-00016980: 6573 7361 6765 733a 2074 6869 7320 6669  essages: this fi
-00016990: 6c65 2077 696c 6c20 6861 7665 2062 6565  le will have bee
-000169a0: 6e20 6465 6c65 7465 6420 6265 666f 7265  n deleted before
-000169b0: 2074 6865 2073 6372 6970 7420 7374 6f70   the script stop
-000169c0: 732e 290a 0a23 2320 4a73 6f6e 6e65 7420  s.)..## Jsonnet 
-000169d0: 496e 7374 616c 6c61 7469 6f6e 0a0a 4a73  Installation..Js
-000169e0: 6f6e 6e65 7420 6973 202a 2a6e 6f74 2a2a  onnet is **not**
-000169f0: 2069 6e73 7461 6c6c 6564 2062 7920 6465   installed by de
-00016a00: 6661 756c 7420 7768 656e 2060 7965 6c6c  fault when `yell
-00016a10: 6f77 646f 672d 7079 7468 6f6e 2d65 7861  owdog-python-exa
-00016a20: 6d70 6c65 7360 2069 7320 696e 7374 616c  mples` is instal
-00016a30: 6c65 642c 2062 6563 6175 7365 2074 6865  led, because the
-00016a40: 2070 6163 6b61 6765 2068 6173 2062 696e   package has bin
-00016a50: 6172 7920 636f 6d70 6f6e 656e 7473 2077  ary components w
-00016a60: 6869 6368 2061 7265 206e 6f74 2061 7661  hich are not ava
-00016a70: 696c 6162 6c65 206f 6e20 5079 5049 2066  ilable on PyPI f
-00016a80: 6f72 2061 6c6c 2070 6c61 7466 6f72 6d73  or all platforms
-00016a90: 2e20 4966 2079 6f75 2074 7279 2074 6f20  . If you try to 
-00016aa0: 7573 6520 6120 4a73 6f6e 6e65 7420 6669  use a Jsonnet fi
-00016ab0: 6c65 2069 6e20 7468 6520 6162 7365 6e63  le in the absenc
-00016ac0: 6520 6f66 204a 736f 6e6e 6574 2c20 7468  e of Jsonnet, th
-00016ad0: 6520 7363 7269 7074 7320 7769 6c6c 2070  e scripts will p
-00016ae0: 7269 6e74 2061 6e20 6572 726f 7220 6d65  rint an error me
-00016af0: 7373 6167 652c 2061 6e64 2073 7567 6765  ssage, and sugge
-00016b00: 7374 2061 6e20 696e 7374 616c 6c61 7469  st an installati
-00016b10: 6f6e 206d 6563 6861 6e69 736d 2e0a 0a54  on mechanism...T
-00016b20: 6f20 696e 7374 616c 6c20 4a73 6f6e 6e65  o install Jsonne
-00016b30: 7420 6174 2074 6865 2073 616d 6520 7469  t at the same ti
-00016b40: 6d65 2061 7320 696e 7374 616c 6c69 6e67  me as installing
-00016b50: 206f 7220 7570 6461 7469 6e67 2074 6865   or updating the
-00016b60: 2050 7974 686f 6e20 4578 616d 706c 6573   Python Examples
-00016b70: 2073 6372 6970 7473 2c20 6d6f 6469 6679   scripts, modify
-00016b80: 2074 6865 2069 6e73 7461 6c6c 6174 696f   the installatio
-00016b90: 6e20 6173 2066 6f6c 6c6f 7773 2074 6f20  n as follows to 
-00016ba0: 696e 636c 7564 6520 7468 6520 606a 736f  include the `jso
-00016bb0: 6e6e 6574 6020 6f70 7469 6f6e 3a0a 0a60  nnet` option:..`
-00016bc0: 6060 0a70 6970 2069 6e73 7461 6c6c 202d  ``.pip install -
-00016bd0: 5520 2279 656c 6c6f 7764 6f67 2d70 7974  U "yellowdog-pyt
-00016be0: 686f 6e2d 6578 616d 706c 6573 5b6a 736f  hon-examples[jso
-00016bf0: 6e6e 6574 5d22 0a60 6060 0a0a 546f 2069  nnet]".```..To i
-00016c00: 6e73 7461 6c6c 204a 736f 6e6e 6574 2073  nstall Jsonnet s
-00016c10: 6570 6172 6174 656c 7920 6672 6f6d 2060  eparately from `
-00016c20: 7965 6c6c 6f77 646f 672d 7079 7468 6f6e  yellowdog-python
-00016c30: 2d65 7861 6d70 6c65 7360 2c20 7472 793a  -examples`, try:
-00016c40: 0a0a 6060 6073 6865 6c6c 0a70 6970 2069  ..```shell.pip i
-00016c50: 6e73 7461 6c6c 202d 5520 6a73 6f6e 6e65  nstall -U jsonne
-00016c60: 740a 6060 600a 0a49 6620 7468 6973 2066  t.```..If this f
-00016c70: 6169 6c73 2c20 7472 793a 0a0a 6060 6073  ails, try:..```s
-00016c80: 6865 6c6c 0a70 6970 2069 6e73 7461 6c6c  hell.pip install
-00016c90: 202d 5520 6a73 6f6e 6e65 742d 6269 6e61   -U jsonnet-bina
-00016ca0: 7279 0a60 6060 0a0a 4966 2062 6f74 6820  ry.```..If both 
-00016cb0: 6f66 2074 6865 7365 206d 6574 686f 6473  of these methods
-00016cc0: 2066 6169 6c2c 2079 6f75 276c 6c20 6e65   fail, you'll ne
-00016cd0: 6564 2074 6f20 656e 7375 7265 2074 6861  ed to ensure tha
-00016ce0: 7420 7468 6520 706c 6174 666f 726d 206f  t the platform o
-00016cf0: 6e20 7768 6963 6820 796f 7527 7265 2072  n which you're r
-00016d00: 756e 6e69 6e67 2068 6173 2074 6865 2072  unning has the r
-00016d10: 6571 7569 7265 6420 6275 696c 6420 746f  equired build to
-00016d20: 6f6c 7320 6176 6169 6c61 626c 652c 2073  ols available, s
-00016d30: 6f20 7468 6174 2074 6865 204a 736f 6e6e  o that the Jsonn
-00016d40: 6574 2062 696e 6172 7920 636f 6d70 6f6e  et binary compon
-00016d50: 656e 7473 2063 616e 2062 6520 6275 696c  ents can be buil
-00016d60: 7420 6c6f 6361 6c6c 792e 2054 6865 2072  t locally. The r
-00016d70: 6571 7569 7265 6420 6275 696c 6420 7061  equired build pa
-00016d80: 636b 6167 6573 2076 6172 7920 6279 2070  ckages vary by p
-00016d90: 6c61 7466 6f72 6d20 6275 7420 7573 7561  latform but usua
-00016da0: 6c6c 7920 696e 636c 7564 6520 6765 6e65  lly include gene
-00016db0: 7261 6c20 6465 7665 6c6f 706d 656e 7420  ral development 
-00016dc0: 746f 6f6c 7320 696e 636c 7564 696e 6720  tools including 
-00016dd0: 6120 432b 2b20 636f 6d70 696c 6572 2c20  a C++ compiler, 
-00016de0: 616e 6420 5079 7468 6f6e 2064 6576 656c  and Python devel
-00016df0: 6f70 6d65 6e74 2074 6f6f 6c73 2069 6e63  opment tools inc
-00016e00: 6c75 6469 6e67 2074 6865 2050 7974 686f  luding the Pytho
-00016e10: 6e20 6865 6164 6572 732e 0a0a 506c 6561  n headers...Plea
-00016e20: 7365 2067 6574 2069 6e20 746f 7563 6820  se get in touch 
-00016e30: 7769 7468 2059 656c 6c6f 7744 6f67 2069  with YellowDog i
-00016e40: 6620 796f 7520 6765 7420 7374 7563 6b2e  f you get stuck.
-00016e50: 0a0a 2323 2056 6172 6961 626c 6520 5375  ..## Variable Su
-00016e60: 6273 7469 7475 7469 6f6e 7320 696e 204a  bstitutions in J
-00016e70: 736f 6e6e 6574 2046 696c 6573 0a0a 5468  sonnet Files..Th
-00016e80: 6520 7363 7269 7074 7320 7072 6f76 6964  e scripts provid
-00016e90: 6520 6675 6c6c 2073 7570 706f 7274 2066  e full support f
-00016ea0: 6f72 2076 6172 6961 626c 6520 7375 6273  or variable subs
-00016eb0: 7469 7475 7469 6f6e 7320 696e 204a 736f  titutions in Jso
-00016ec0: 6e6e 6574 2066 696c 6573 2c20 7573 696e  nnet files, usin
-00016ed0: 6720 7468 6520 7361 6d65 2072 756c 6573  g the same rules
-00016ee0: 2061 7320 666f 7220 7468 6520 4a53 4f4e   as for the JSON
-00016ef0: 2073 7065 6369 6669 6361 7469 6f6e 732e   specifications.
-00016f00: 2052 656d 656d 6265 7220 7468 6174 2066   Remember that f
-00016f10: 6f72 202a 2a57 6f72 6b65 7220 506f 6f6c  or **Worker Pool
-00016f20: 2a2a 2073 7065 6369 6669 6361 7469 6f6e  ** specification
-00016f30: 732c 2076 6172 6961 626c 6520 7375 6273  s, variable subs
-00016f40: 7469 7475 7469 6f6e 7320 6d75 7374 2062  titutions must b
-00016f50: 6520 7072 6566 6978 6564 2062 7920 605f  e prefixed by `_
-00016f60: 5f60 2c20 652e 672e 2060 225f 5f7b 7b75  _`, e.g. `"__{{u
-00016f70: 7365 726e 616d 657d 7d7d 2260 2e0a 0a56  sername}}}"`...V
-00016f80: 6172 6961 626c 6520 7375 6273 7469 7475  ariable substitu
-00016f90: 7469 6f6e 2069 7320 7065 7266 6f72 6d65  tion is performe
-00016fa0: 6420 6265 666f 7265 204a 736f 6e6e 6574  d before Jsonnet
-00016fb0: 2065 7870 616e 7369 6f6e 2069 6e74 6f20   expansion into 
-00016fc0: 4a53 4f4e 2c20 616e 6420 6167 6169 6e20  JSON, and again 
-00016fd0: 6166 7465 7220 7468 6520 6578 7061 6e73  after the expans
-00016fe0: 696f 6e2e 0a0a 2323 2043 6865 636b 696e  ion...## Checkin
-00016ff0: 6720 4a73 6f6e 6e65 7420 5072 6f63 6573  g Jsonnet Proces
-00017000: 7369 6e67 0a0a 5468 6572 6520 6172 6520  sing..There are 
-00017010: 7468 7265 6520 706f 7373 6962 696c 6974  three possibilit
-00017020: 6965 7320 666f 7220 7665 7269 6679 696e  ies for verifyin
-00017030: 6720 7468 6174 2061 204a 736f 6e6e 6574  g that a Jsonnet
-00017040: 2073 7065 6369 6669 6361 7469 6f6e 2069   specification i
-00017050: 7320 646f 696e 6720 7768 6174 2069 7320  s doing what is 
-00017060: 696e 7465 6e64 6564 3a0a 0a31 2e20 546f  intended:..1. To
-00017070: 2069 6e73 7065 6374 2074 6865 2062 6173   inspect the bas
-00017080: 6963 2063 6f6e 7665 7273 696f 6e20 6f66  ic conversion of
-00017090: 204a 736f 6e6e 6574 2069 6e74 6f20 4a53   Jsonnet into JS
-000170a0: 4f4e 2c20 7769 7468 6f75 7420 616e 7920  ON, without any 
-000170b0: 6164 6469 7469 6f6e 616c 2070 726f 6365  additional proce
-000170c0: 7373 696e 6720 6279 2074 6865 2050 7974  ssing by the Pyt
-000170d0: 686f 6e20 4578 616d 706c 6573 2073 6372  hon Examples scr
-000170e0: 6970 7473 2c20 7468 6520 6079 642d 6a73  ipts, the `yd-js
-000170f0: 6f6e 6e65 7432 6a73 6f6e 6020 636f 6d6d  onnet2json` comm
-00017100: 616e 6420 6361 6e20 6265 2075 7365 642e  and can be used.
-00017110: 2054 6869 7320 7461 6b65 7320 6120 7369   This takes a si
-00017120: 6e67 6c65 2063 6f6d 6d61 6e64 206c 696e  ngle command lin
-00017130: 6520 6172 6775 6d65 6e74 2077 6869 6368  e argument which
-00017140: 2069 7320 7468 6520 6e61 6d65 206f 6620   is the name of 
-00017150: 7468 6520 6a73 6f6e 6e65 7420 6669 6c65  the jsonnet file
-00017160: 2074 6f20 6265 2070 726f 6365 7373 6564   to be processed
-00017170: 3a0a 0a60 6060 7368 656c 6c0a 7964 2d6a  :..```shell.yd-j
-00017180: 736f 6e6e 6574 326a 736f 6e20 6d79 5f66  sonnet2json my_f
-00017190: 696c 652e 6a73 6f6e 6e65 740a 6060 600a  ile.jsonnet.```.
-000171a0: 0a0a 322e 2054 6865 2060 6a73 6f6e 6e65  ..2. The `jsonne
-000171b0: 742d 6472 792d 7275 6e60 2028 602d 4a60  t-dry-run` (`-J`
-000171c0: 2920 6f70 7469 6f6e 206f 6620 7468 6520  ) option of the 
-000171d0: 6079 642d 7375 626d 6974 602c 2060 7964  `yd-submit`, `yd
-000171e0: 2d70 726f 7669 7369 6f6e 6020 616e 6420  -provision` and 
-000171f0: 6079 642d 696e 7374 616e 7469 6174 6560  `yd-instantiate`
-00017200: 2063 6f6d 6d61 6e64 7320 7769 6c6c 2067   commands will g
-00017210: 656e 6572 6174 6520 4a53 4f4e 206f 7574  enerate JSON out
-00017220: 7075 7420 7265 7072 6573 656e 7469 6e67  put representing
-00017230: 2074 6865 204a 736f 6e6e 6574 2074 6f20   the Jsonnet to 
-00017240: 4a53 4f4e 2070 726f 6365 7373 696e 6720  JSON processing 
-00017250: 6f6e 6c79 2c20 696e 636c 7564 696e 6720  only, including 
-00017260: 6170 706c 6963 6162 6c65 2076 6172 6961  applicable varia
-00017270: 626c 6520 7375 6273 7469 7475 7469 6f6e  ble substitution
-00017280: 732c 2062 7574 2062 6566 6f72 6520 6675  s, but before fu
-00017290: 6c6c 2070 726f 7065 7274 7920 6578 7061  ll property expa
-000172a0: 6e73 696f 6e20 696e 746f 2074 6865 204a  nsion into the J
-000172b0: 534f 4e20 7468 6174 2077 696c 6c20 6265  SON that will be
-000172c0: 2073 7562 6d69 7474 6564 2074 6f20 7468   submitted to th
-000172d0: 6520 506c 6174 666f 726d 2e0a 0a0a 332e  e Platform....3.
-000172e0: 2054 6865 2060 6472 792d 7275 6e60 2028   The `dry-run` (
-000172f0: 602d 4460 2920 6f70 7469 6f6e 2077 696c  `-D`) option wil
-00017300: 6c20 6765 6e65 7261 7465 204a 534f 4e20  l generate JSON 
-00017310: 6f75 7470 7574 2072 6570 7265 7365 6e74  output represent
-00017320: 696e 6720 7468 6520 6675 6c6c 2070 726f  ing the full pro
-00017330: 6365 7373 696e 6720 6f66 2074 6865 204a  cessing of the J
-00017340: 736f 6e6e 6574 2066 696c 6520 696e 746f  sonnet file into
-00017350: 2077 6861 7420 7769 6c6c 2062 6520 7375   what will be su
-00017360: 626d 6974 7465 6420 746f 2074 6865 2041  bmitted to the A
-00017370: 5049 2e20 5468 6973 2061 6c6c 6f77 7320  PI. This allows 
-00017380: 696e 7370 6563 7469 6f6e 2074 6f20 6368  inspection to ch
-00017390: 6563 6b20 7468 6174 2074 6865 206f 7574  eck that the out
-000173a0: 7075 7420 6d61 7463 6865 7320 6578 7065  put matches expe
-000173b0: 6374 6174 696f 6e73 2c20 7072 696f 7220  ctations, prior 
-000173c0: 746f 2073 7562 6d69 7474 696e 6720 746f  to submitting to
-000173d0: 2074 6865 2050 6c61 7466 6f72 6d2e 0a0a   the Platform...
-000173e0: 2323 204a 736f 6e6e 6574 2045 7861 6d70  ## Jsonnet Examp
-000173f0: 6c65 0a0a 4865 7265 2773 2061 6e20 6578  le..Here's an ex
-00017400: 616d 706c 6520 6f66 2061 204a 736f 6e6e  ample of a Jsonn
-00017410: 6574 2066 696c 6520 7468 6174 2067 656e  et file that gen
-00017420: 6572 6174 6573 2061 2057 6f72 6b20 5265  erates a Work Re
-00017430: 7175 6972 656d 656e 7420 7769 7468 2066  quirement with f
-00017440: 6f75 7220 5461 736b 733a 0a0a 6060 606a  our Tasks:..```j
-00017450: 736f 6e6e 6574 0a23 2046 756e 6374 696f  sonnet.# Functio
-00017460: 6e20 666f 7220 7379 6e74 6865 7369 7369  n for synthesisi
-00017470: 6e67 2054 6173 6b73 0a6c 6f63 616c 2054  ng Tasks.local T
-00017480: 6173 6b28 6172 6775 6d65 6e74 733d 5b5d  ask(arguments=[]
-00017490: 2c20 656e 7669 726f 6e6d 656e 743d 7b7d  , environment={}
-000174a0: 2920 3d20 7b0a 2020 2020 6172 6775 6d65  ) = {.    argume
-000174b0: 6e74 733a 2061 7267 756d 656e 7473 2c0a  nts: arguments,.
-000174c0: 2020 2020 656e 7669 726f 6e6d 656e 743a      environment:
-000174d0: 2065 6e76 6972 6f6e 6d65 6e74 2c0a 2020   environment,.  
-000174e0: 2020 6e61 6d65 3a20 226d 795f 7461 736b    name: "my_task
-000174f0: 5f7b 7b74 6173 6b5f 6e75 6d62 6572 7d7d  _{{task_number}}
-00017500: 220a 7d3b 0a0a 2320 576f 726b 2052 6571  ".};..# Work Req
-00017510: 7569 7265 6d65 6e74 0a7b 0a20 2022 6e61  uirement.{.  "na
-00017520: 6d65 223a 2022 776f 726b 7265 715f 7b7b  me": "workreq_{{
-00017530: 6461 7465 7469 6d65 7d7d 222c 0a20 2022  datetime}}",.  "
-00017540: 7461 736b 4772 6f75 7073 223a 205b 0a20  taskGroups": [. 
-00017550: 2020 207b 0a20 2020 2020 2022 7461 736b     {.      "task
-00017560: 7322 3a20 5b0a 2020 2020 2020 2020 5461  s": [.        Ta
-00017570: 736b 285b 2231 225d 2c20 7b41 3a20 2241  sk(["1"], {A: "A
-00017580: 5f31 227d 292c 2020 2320 6172 6775 6d65  _1"}),  # argume
-00017590: 6e74 7320 616e 6420 656e 7669 726f 6e6d  nts and environm
-000175a0: 656e 740a 2020 2020 2020 2020 5461 736b  ent.        Task
-000175b0: 285b 2232 222c 2022 3322 5d2c 207b 7d29  (["2", "3"], {})
-000175c0: 2c20 2020 2020 2320 6172 6775 6d65 6e74  ,     # argument
-000175d0: 7320 616e 6420 656d 7074 7920 656e 7669  s and empty envi
-000175e0: 726f 6e6d 656e 740a 2020 2020 2020 2020  ronment.        
-000175f0: 5461 736b 285b 2234 225d 292c 2020 2020  Task(["4"]),    
-00017600: 2020 2020 2020 2020 2020 2320 6172 6775            # argu
-00017610: 6d65 6e74 7320 616e 6420 6465 6661 756c  ments and defaul
-00017620: 7420 656e 7669 726f 6e6d 656e 740a 2020  t environment.  
-00017630: 2020 2020 2020 5461 736b 2829 2020 2020        Task()    
-00017640: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00017650: 2320 6465 6661 756c 7420 6172 6775 6d65  # default argume
-00017660: 6e74 7320 616e 6420 656e 7669 726f 6e6d  nts and environm
-00017670: 656e 740a 2020 2020 2020 5d0a 2020 2020  ent.      ].    
-00017680: 7d0a 2020 5d0a 7d0a 6060 600a 0a57 6865  }.  ].}.```..Whe
-00017690: 6e20 7468 6973 2069 7320 696e 7370 6563  n this is inspec
-000176a0: 7465 6420 7573 696e 6720 7468 6520 606a  ted using the `j
-000176b0: 736f 6e6e 6574 2d64 7279 2d72 756e 6020  sonnet-dry-run` 
-000176c0: 6f70 7469 6f6e 2028 6079 642d 7375 626d  option (`yd-subm
-000176d0: 6974 202d 4a71 202d 7220 6d79 5f77 6f72  it -Jq -r my_wor
-000176e0: 6b5f 7265 712e 6a73 6f6e 6e65 7460 292c  k_req.jsonnet`),
-000176f0: 2074 6869 7320 6973 2074 6865 2070 726f   this is the pro
-00017700: 6365 7373 6564 206f 7574 7075 743a 0a0a  cessed output:..
-00017710: 6060 606a 736f 6e0a 7b0a 2020 226e 616d  ```json.{.  "nam
-00017720: 6522 3a20 2277 6f72 6b72 6571 5f32 3330  e": "workreq_230
-00017730: 3131 342d 3134 3036 3435 222c 0a20 2022  114-140645",.  "
-00017740: 7461 736b 4772 6f75 7073 223a 205b 0a20  taskGroups": [. 
-00017750: 2020 207b 0a20 2020 2020 2022 7461 736b     {.      "task
-00017760: 7322 3a20 5b0a 2020 2020 2020 2020 7b0a  s": [.        {.
-00017770: 2020 2020 2020 2020 2020 2261 7267 756d            "argum
-00017780: 656e 7473 223a 205b 2231 225d 2c0a 2020  ents": ["1"],.  
-00017790: 2020 2020 2020 2020 2265 6e76 6972 6f6e          "environ
-000177a0: 6d65 6e74 223a 207b 2241 223a 2022 415f  ment": {"A": "A_
-000177b0: 3122 7d2c 0a20 2020 2020 2020 2020 2022  1"},.          "
-000177c0: 6e61 6d65 223a 2022 6d79 5f74 6173 6b5f  name": "my_task_
-000177d0: 7b7b 7461 736b 5f6e 756d 6265 727d 7d22  {{task_number}}"
-000177e0: 0a20 2020 2020 2020 207d 2c0a 2020 2020  .        },.    
-000177f0: 2020 2020 7b0a 2020 2020 2020 2020 2020      {.          
-00017800: 2261 7267 756d 656e 7473 223a 205b 2232  "arguments": ["2
-00017810: 222c 2022 3322 5d2c 0a20 2020 2020 2020  ", "3"],.       
-00017820: 2020 2022 656e 7669 726f 6e6d 656e 7422     "environment"
-00017830: 3a20 7b7d 2c0a 2020 2020 2020 2020 2020  : {},.          
-00017840: 226e 616d 6522 3a20 226d 795f 7461 736b  "name": "my_task
-00017850: 5f7b 7b74 6173 6b5f 6e75 6d62 6572 7d7d  _{{task_number}}
-00017860: 220a 2020 2020 2020 2020 7d2c 0a20 2020  ".        },.   
-00017870: 2020 2020 207b 0a20 2020 2020 2020 2020       {.         
-00017880: 2022 6172 6775 6d65 6e74 7322 3a20 5b22   "arguments": ["
-00017890: 3422 5d2c 0a20 2020 2020 2020 2020 2022  4"],.          "
-000178a0: 656e 7669 726f 6e6d 656e 7422 3a20 7b7d  environment": {}
-000178b0: 2c0a 2020 2020 2020 2020 2020 226e 616d  ,.          "nam
-000178c0: 6522 3a20 226d 795f 7461 736b 5f7b 7b74  e": "my_task_{{t
-000178d0: 6173 6b5f 6e75 6d62 6572 7d7d 220a 2020  ask_number}}".  
-000178e0: 2020 2020 2020 7d2c 0a20 2020 2020 2020        },.       
-000178f0: 207b 0a20 2020 2020 2020 2020 2022 6172   {.          "ar
-00017900: 6775 6d65 6e74 7322 3a20 5b5d 2c0a 2020  guments": [],.  
-00017910: 2020 2020 2020 2020 2265 6e76 6972 6f6e          "environ
-00017920: 6d65 6e74 223a 207b 7d2c 0a20 2020 2020  ment": {},.     
-00017930: 2020 2020 2022 6e61 6d65 223a 2022 6d79       "name": "my
-00017940: 5f74 6173 6b5f 7b7b 7461 736b 5f6e 756d  _task_{{task_num
-00017950: 6265 727d 7d22 0a20 2020 2020 2020 207d  ber}}".        }
-00017960: 0a20 2020 2020 205d 0a20 2020 207d 0a20  .      ].    }. 
-00017970: 205d 0a7d 0a60 6060 0a0a 5768 656e 2074   ].}.```..When t
-00017980: 6869 7320 6973 2069 6e73 7065 6374 6564  his is inspected
-00017990: 2075 7369 6e67 2074 6865 2060 6472 792d   using the `dry-
-000179a0: 7275 6e60 206f 7074 696f 6e20 2860 7964  run` option (`yd
-000179b0: 2d73 7562 6d69 7420 2d44 7120 2d72 206d  -submit -Dq -r m
-000179c0: 795f 776f 726b 5f72 6571 2e6a 736f 6e6e  y_work_req.jsonn
-000179d0: 6574 6029 2c20 7468 6973 2069 7320 7468  et`), this is th
-000179e0: 6520 7072 6f63 6573 7365 6420 6f75 7470  e processed outp
-000179f0: 7574 3a0a 0a60 6060 6a73 6f6e 0a7b 0a20  ut:..```json.{. 
-00017a00: 2022 6675 6c66 696c 4f6e 5375 626d 6974   "fulfilOnSubmit
-00017a10: 223a 2066 616c 7365 2c0a 2020 226e 616d  ": false,.  "nam
-00017a20: 6522 3a20 2277 6f72 6b72 6571 5f32 3330  e": "workreq_230
-00017a30: 3131 342d 3134 3036 3435 222c 0a20 2022  114-140645",.  "
-00017a40: 6e61 6d65 7370 6163 6522 3a20 2270 7965  namespace": "pye
-00017a50: 7861 6d70 6c65 7322 2c0a 2020 2270 7269  xamples",.  "pri
-00017a60: 6f72 6974 7922 3a20 302c 0a20 2022 7461  ority": 0,.  "ta
-00017a70: 6722 3a20 2270 7965 782d 6261 7368 222c  g": "pyex-bash",
-00017a80: 0a20 2022 7461 736b 4772 6f75 7073 223a  .  "taskGroups":
-00017a90: 205b 0a20 2020 207b 0a20 2020 2020 2022   [.    {.      "
-00017aa0: 6669 6e69 7368 4966 416c 6c54 6173 6b73  finishIfAllTasks
-00017ab0: 4669 6e69 7368 6564 223a 2074 7275 652c  Finished": true,
-00017ac0: 0a20 2020 2020 2022 6669 6e69 7368 4966  .      "finishIf
-00017ad0: 416e 7954 6173 6b46 6169 6c65 6422 3a20  AnyTaskFailed": 
-00017ae0: 6661 6c73 652c 0a20 2020 2020 2022 6e61  false,.      "na
-00017af0: 6d65 223a 2022 7461 736b 5f67 726f 7570  me": "task_group
-00017b00: 5f31 222c 0a20 2020 2020 2022 7072 696f  _1",.      "prio
-00017b10: 7269 7479 223a 2030 2c0a 2020 2020 2020  rity": 0,.      
-00017b20: 2272 756e 5370 6563 6966 6963 6174 696f  "runSpecificatio
-00017b30: 6e22 3a20 7b0a 2020 2020 2020 2020 226d  n": {.        "m
-00017b40: 6178 696d 756d 5461 736b 5265 7472 6965  aximumTaskRetrie
-00017b50: 7322 3a20 302c 0a20 2020 2020 2020 2022  s": 0,.        "
-00017b60: 7461 736b 5479 7065 7322 3a20 5b22 6261  taskTypes": ["ba
-00017b70: 7368 225d 2c0a 2020 2020 2020 2020 2277  sh"],.        "w
-00017b80: 6f72 6b65 7254 6167 7322 3a20 5b22 7079  orkerTags": ["py
-00017b90: 6578 2d62 6173 682d 646f 636b 6572 225d  ex-bash-docker"]
-00017ba0: 0a20 2020 2020 207d 2c0a 2020 2020 2020  .      },.      
-00017bb0: 2274 6173 6b73 223a 205b 0a20 2020 2020  "tasks": [.     
-00017bc0: 2020 207b 0a20 2020 2020 2020 2020 2022     {.          "
-00017bd0: 6172 6775 6d65 6e74 7322 3a20 5b22 776f  arguments": ["wo
-00017be0: 726b 7265 715f 3233 3031 3134 2d31 3430  rkreq_230114-140
-00017bf0: 3634 352f 736c 6565 705f 7363 7269 7074  645/sleep_script
-00017c00: 2e73 6822 2c20 2231 225d 2c0a 2020 2020  .sh", "1"],.    
-00017c10: 2020 2020 2020 2265 6e76 6972 6f6e 6d65        "environme
-00017c20: 6e74 223a 207b 2241 223a 2022 415f 3122  nt": {"A": "A_1"
-00017c30: 7d2c 0a20 2020 2020 2020 2020 2022 696e  },.          "in
-00017c40: 7075 7473 223a 205b 0a20 2020 2020 2020  puts": [.       
-00017c50: 2020 2020 207b 0a20 2020 2020 2020 2020       {.         
-00017c60: 2020 2020 2022 6f62 6a65 6374 4e61 6d65       "objectName
-00017c70: 5061 7474 6572 6e22 3a20 2277 6f72 6b72  Pattern": "workr
-00017c80: 6571 5f32 3330 3131 342d 3134 3036 3435  eq_230114-140645
-00017c90: 2f73 6c65 6570 5f73 6372 6970 742e 7368  /sleep_script.sh
-00017ca0: 222c 0a20 2020 2020 2020 2020 2020 2020  ",.             
-00017cb0: 2022 736f 7572 6365 223a 2022 5441 534b   "source": "TASK
-00017cc0: 5f4e 414d 4553 5041 4345 222c 0a20 2020  _NAMESPACE",.   
-00017cd0: 2020 2020 2020 2020 2020 2022 7665 7269             "veri
-00017ce0: 6669 6361 7469 6f6e 223a 2022 5645 5249  fication": "VERI
-00017cf0: 4659 5f41 545f 5354 4152 5422 0a20 2020  FY_AT_START".   
-00017d00: 2020 2020 2020 2020 207d 0a20 2020 2020           }.     
-00017d10: 2020 2020 205d 2c0a 2020 2020 2020 2020       ],.        
-00017d20: 2020 226e 616d 6522 3a20 226d 795f 7461    "name": "my_ta
-00017d30: 736b 5f31 222c 0a20 2020 2020 2020 2020  sk_1",.         
-00017d40: 2022 6f75 7470 7574 7322 3a20 5b0a 2020   "outputs": [.  
-00017d50: 2020 2020 2020 2020 2020 7b22 616c 7761            {"alwa
-00017d60: 7973 5570 6c6f 6164 223a 2074 7275 652c  ysUpload": true,
-00017d70: 2022 7265 7175 6972 6564 223a 2066 616c   "required": fal
-00017d80: 7365 2c20 2273 6f75 7263 6522 3a20 2250  se, "source": "P
-00017d90: 524f 4345 5353 5f4f 5554 5055 5422 7d0a  ROCESS_OUTPUT"}.
-00017da0: 2020 2020 2020 2020 2020 5d2c 0a20 2020            ],.   
-00017db0: 2020 2020 2020 2022 7461 736b 5479 7065         "taskType
-00017dc0: 223a 2022 6261 7368 220a 2020 2020 2020  ": "bash".      
-00017dd0: 2020 7d2c 0a20 2020 2020 2020 207b 0a20    },.        {. 
-00017de0: 2020 2020 2020 2020 2022 6172 6775 6d65           "argume
-00017df0: 6e74 7322 3a20 5b22 776f 726b 7265 715f  nts": ["workreq_
-00017e00: 3233 3031 3134 2d31 3430 3634 352f 736c  230114-140645/sl
-00017e10: 6565 705f 7363 7269 7074 2e73 6822 2c20  eep_script.sh", 
-00017e20: 2232 222c 2022 3322 5d2c 0a20 2020 2020  "2", "3"],.     
-00017e30: 2020 2020 2022 656e 7669 726f 6e6d 656e       "environmen
-00017e40: 7422 3a20 7b7d 2c0a 2020 2020 2020 2020  t": {},.        
-00017e50: 2020 2269 6e70 7574 7322 3a20 5b0a 2020    "inputs": [.  
-00017e60: 2020 2020 2020 2020 2020 7b0a 2020 2020            {.    
-00017e70: 2020 2020 2020 2020 2020 226f 626a 6563            "objec
-00017e80: 744e 616d 6550 6174 7465 726e 223a 2022  tNamePattern": "
-00017e90: 776f 726b 7265 715f 3233 3031 3134 2d31  workreq_230114-1
-00017ea0: 3430 3634 352f 736c 6565 705f 7363 7269  40645/sleep_scri
-00017eb0: 7074 2e73 6822 2c0a 2020 2020 2020 2020  pt.sh",.        
-00017ec0: 2020 2020 2020 2273 6f75 7263 6522 3a20        "source": 
-00017ed0: 2254 4153 4b5f 4e41 4d45 5350 4143 4522  "TASK_NAMESPACE"
-00017ee0: 2c0a 2020 2020 2020 2020 2020 2020 2020  ,.              
-00017ef0: 2276 6572 6966 6963 6174 696f 6e22 3a20  "verification": 
-00017f00: 2256 4552 4946 595f 4154 5f53 5441 5254  "VERIFY_AT_START
-00017f10: 220a 2020 2020 2020 2020 2020 2020 7d0a  ".            }.
-00017f20: 2020 2020 2020 2020 2020 5d2c 0a20 2020            ],.   
-00017f30: 2020 2020 2020 2022 6e61 6d65 223a 2022         "name": "
-00017f40: 6d79 5f74 6173 6b5f 3222 2c0a 2020 2020  my_task_2",.    
-00017f50: 2020 2020 2020 226f 7574 7075 7473 223a        "outputs":
-00017f60: 205b 0a20 2020 2020 2020 2020 2020 207b   [.            {
-00017f70: 2261 6c77 6179 7355 706c 6f61 6422 3a20  "alwaysUpload": 
-00017f80: 7472 7565 2c20 2272 6571 7569 7265 6422  true, "required"
-00017f90: 3a20 6661 6c73 652c 2022 736f 7572 6365  : false, "source
-00017fa0: 223a 2022 5052 4f43 4553 535f 4f55 5450  ": "PROCESS_OUTP
-00017fb0: 5554 227d 0a20 2020 2020 2020 2020 205d  UT"}.          ]
-00017fc0: 2c0a 2020 2020 2020 2020 2020 2274 6173  ,.          "tas
-00017fd0: 6b54 7970 6522 3a20 2262 6173 6822 0a20  kType": "bash". 
-00017fe0: 2020 2020 2020 207d 2c0a 2020 2020 2020         },.      
-00017ff0: 2020 7b0a 2020 2020 2020 2020 2020 2261    {.          "a
-00018000: 7267 756d 656e 7473 223a 205b 2277 6f72  rguments": ["wor
-00018010: 6b72 6571 5f32 3330 3131 342d 3134 3036  kreq_230114-1406
-00018020: 3435 2f73 6c65 6570 5f73 6372 6970 742e  45/sleep_script.
-00018030: 7368 222c 2022 3422 5d2c 0a20 2020 2020  sh", "4"],.     
-00018040: 2020 2020 2022 656e 7669 726f 6e6d 656e       "environmen
-00018050: 7422 3a20 7b7d 2c0a 2020 2020 2020 2020  t": {},.        
-00018060: 2020 2269 6e70 7574 7322 3a20 5b0a 2020    "inputs": [.  
-00018070: 2020 2020 2020 2020 2020 7b0a 2020 2020            {.    
-00018080: 2020 2020 2020 2020 2020 226f 626a 6563            "objec
-00018090: 744e 616d 6550 6174 7465 726e 223a 2022  tNamePattern": "
-000180a0: 776f 726b 7265 715f 3233 3031 3134 2d31  workreq_230114-1
-000180b0: 3430 3634 352f 736c 6565 705f 7363 7269  40645/sleep_scri
-000180c0: 7074 2e73 6822 2c0a 2020 2020 2020 2020  pt.sh",.        
-000180d0: 2020 2020 2020 2273 6f75 7263 6522 3a20        "source": 
-000180e0: 2254 4153 4b5f 4e41 4d45 5350 4143 4522  "TASK_NAMESPACE"
-000180f0: 2c0a 2020 2020 2020 2020 2020 2020 2020  ,.              
-00018100: 2276 6572 6966 6963 6174 696f 6e22 3a20  "verification": 
-00018110: 2256 4552 4946 595f 4154 5f53 5441 5254  "VERIFY_AT_START
-00018120: 220a 2020 2020 2020 2020 2020 2020 7d0a  ".            }.
-00018130: 2020 2020 2020 2020 2020 5d2c 0a20 2020            ],.   
-00018140: 2020 2020 2020 2022 6e61 6d65 223a 2022         "name": "
-00018150: 6d79 5f74 6173 6b5f 3322 2c0a 2020 2020  my_task_3",.    
-00018160: 2020 2020 2020 226f 7574 7075 7473 223a        "outputs":
-00018170: 205b 0a20 2020 2020 2020 2020 2020 207b   [.            {
-00018180: 2261 6c77 6179 7355 706c 6f61 6422 3a20  "alwaysUpload": 
-00018190: 7472 7565 2c20 2272 6571 7569 7265 6422  true, "required"
-000181a0: 3a20 6661 6c73 652c 2022 736f 7572 6365  : false, "source
-000181b0: 223a 2022 5052 4f43 4553 535f 4f55 5450  ": "PROCESS_OUTP
-000181c0: 5554 227d 0a20 2020 2020 2020 2020 205d  UT"}.          ]
-000181d0: 2c0a 2020 2020 2020 2020 2020 2274 6173  ,.          "tas
-000181e0: 6b54 7970 6522 3a20 2262 6173 6822 0a20  kType": "bash". 
-000181f0: 2020 2020 2020 207d 2c0a 2020 2020 2020         },.      
-00018200: 2020 7b0a 2020 2020 2020 2020 2020 2261    {.          "a
-00018210: 7267 756d 656e 7473 223a 205b 2277 6f72  rguments": ["wor
-00018220: 6b72 6571 5f32 3330 3131 342d 3134 3036  kreq_230114-1406
-00018230: 3435 2f73 6c65 6570 5f73 6372 6970 742e  45/sleep_script.
-00018240: 7368 225d 2c0a 2020 2020 2020 2020 2020  sh"],.          
-00018250: 2265 6e76 6972 6f6e 6d65 6e74 223a 207b  "environment": {
-00018260: 7d2c 0a20 2020 2020 2020 2020 2022 696e  },.          "in
-00018270: 7075 7473 223a 205b 0a20 2020 2020 2020  puts": [.       
-00018280: 2020 2020 207b 0a20 2020 2020 2020 2020       {.         
-00018290: 2020 2020 2022 6f62 6a65 6374 4e61 6d65       "objectName
-000182a0: 5061 7474 6572 6e22 3a20 2277 6f72 6b72  Pattern": "workr
-000182b0: 6571 5f32 3330 3131 342d 3134 3036 3435  eq_230114-140645
-000182c0: 2f73 6c65 6570 5f73 6372 6970 742e 7368  /sleep_script.sh
-000182d0: 222c 0a20 2020 2020 2020 2020 2020 2020  ",.             
-000182e0: 2022 736f 7572 6365 223a 2022 5441 534b   "source": "TASK
-000182f0: 5f4e 414d 4553 5041 4345 222c 0a20 2020  _NAMESPACE",.   
-00018300: 2020 2020 2020 2020 2020 2022 7665 7269             "veri
-00018310: 6669 6361 7469 6f6e 223a 2022 5645 5249  fication": "VERI
-00018320: 4659 5f41 545f 5354 4152 5422 0a20 2020  FY_AT_START".   
-00018330: 2020 2020 2020 2020 207d 0a20 2020 2020           }.     
-00018340: 2020 2020 205d 2c0a 2020 2020 2020 2020       ],.        
-00018350: 2020 226e 616d 6522 3a20 226d 795f 7461    "name": "my_ta
-00018360: 736b 5f34 222c 0a20 2020 2020 2020 2020  sk_4",.         
-00018370: 2022 6f75 7470 7574 7322 3a20 5b0a 2020   "outputs": [.  
-00018380: 2020 2020 2020 2020 2020 7b22 616c 7761            {"alwa
-00018390: 7973 5570 6c6f 6164 223a 2074 7275 652c  ysUpload": true,
-000183a0: 2022 7265 7175 6972 6564 223a 2066 616c   "required": fal
-000183b0: 7365 2c20 2273 6f75 7263 6522 3a20 2250  se, "source": "P
-000183c0: 524f 4345 5353 5f4f 5554 5055 5422 7d0a  ROCESS_OUTPUT"}.
-000183d0: 2020 2020 2020 2020 2020 5d2c 0a20 2020            ],.   
-000183e0: 2020 2020 2020 2022 7461 736b 5479 7065         "taskType
-000183f0: 223a 2022 6261 7368 220a 2020 2020 2020  ": "bash".      
-00018400: 2020 7d0a 2020 2020 2020 5d0a 2020 2020    }.      ].    
-00018410: 7d0a 2020 5d0a 7d0a 6060 600a 0a23 2043  }.  ].}.```..# C
-00018420: 6f6d 6d61 6e64 204c 6973 740a 0a48 656c  ommand List..Hel
-00018430: 7020 6973 2061 7661 696c 6162 6c65 2066  p is available f
-00018440: 6f72 2061 6c6c 2063 6f6d 6d61 6e64 7320  or all commands 
-00018450: 6279 2069 6e76 6f6b 696e 6720 6120 636f  by invoking a co
-00018460: 6d6d 616e 6420 7769 7468 2074 6865 2060  mmand with the `
-00018470: 2d2d 6865 6c70 6020 6f72 2060 2d68 6020  --help` or `-h` 
-00018480: 6f70 7469 6f6e 2e20 536f 6d65 2063 6f6d  option. Some com
-00018490: 6d61 6e64 206c 696e 6520 7061 7261 6d65  mand line parame
-000184a0: 7465 7273 2061 7265 2063 6f6d 6d6f 6e20  ters are common 
-000184b0: 746f 2061 6c6c 2063 6f6d 6d61 6e64 732c  to all commands,
-000184c0: 2077 6869 6c65 206f 7468 6572 7320 6172   while others ar
-000184d0: 6520 636f 6d6d 616e 642d 7370 6563 6966  e command-specif
-000184e0: 6963 2e0a 0a41 6c6c 2064 6573 7472 7563  ic...All destruc
-000184f0: 7469 7665 2063 6f6d 6d61 6e64 7320 7265  tive commands re
-00018500: 7175 6972 6520 7573 6572 2063 6f6e 6669  quire user confi
-00018510: 726d 6174 696f 6e20 6265 666f 7265 2074  rmation before t
-00018520: 616b 696e 6720 6566 6665 6374 2e20 5468  aking effect. Th
-00018530: 6973 2063 616e 2062 6520 7375 7070 7265  is can be suppre
-00018540: 7373 6564 2075 7369 6e67 2074 6865 2060  ssed using the `
-00018550: 2d2d 7965 7360 206f 7220 602d 7960 206f  --yes` or `-y` o
-00018560: 7074 696f 6e2c 2069 6e20 7768 6963 6820  ption, in which 
-00018570: 6361 7365 2074 6865 2063 6f6d 6d61 6e64  case the command
-00018580: 2077 696c 6c20 7072 6f63 6565 6420 7769   will proceed wi
-00018590: 7468 6f75 7420 636f 6e66 6972 6d61 7469  thout confirmati
-000185a0: 6f6e 2e0a 0a53 6f6d 6520 636f 6d6d 616e  on...Some comman
-000185b0: 6473 2073 7570 706f 7274 2074 6865 2060  ds support the `
-000185c0: 2d2d 696e 7465 7261 6374 6976 6560 206f  --interactive` o
-000185d0: 7220 602d 6960 206f 7074 696f 6e2c 2061  r `-i` option, a
-000185e0: 6c6c 6f77 696e 6720 7573 6572 2073 656c  llowing user sel
-000185f0: 6563 7469 6f6e 7320 746f 2062 6520 6d61  ections to be ma
-00018600: 6465 2e20 452e 672e 2c20 7468 6973 2063  de. E.g., this c
-00018610: 616e 2062 6520 7573 6564 2074 6f20 7365  an be used to se
-00018620: 6c65 6374 2077 6869 6368 206f 626a 6563  lect which objec
-00018630: 7420 7061 7468 7320 746f 2064 656c 6574  t paths to delet
-00018640: 652e 0a0a 5468 6520 602d 2d71 7569 6574  e...The `--quiet
-00018650: 6020 6f72 2060 2d71 6020 6f70 7469 6f6e  ` or `-q` option
-00018660: 2072 6564 7563 6573 2074 6865 2063 6f6d   reduces the com
-00018670: 6d61 6e64 206f 7574 7075 7420 646f 776e  mand output down
-00018680: 2074 6f20 6573 7365 6e74 6961 6c20 6d65   to essential me
-00018690: 7373 6167 6573 206f 6e6c 792e 2053 6f2c  ssages only. So,
-000186a0: 2066 6f72 2065 7861 6d70 6c65 2c20 6079   for example, `y
-000186b0: 642d 6465 6c65 7465 202d 7971 6020 776f  d-delete -yq` wo
-000186c0: 756c 6420 6465 6c65 7465 2061 6c6c 206d  uld delete all m
-000186d0: 6174 6368 696e 6720 6f62 6a65 6374 2070  atching object p
-000186e0: 6174 6873 2073 696c 656e 746c 792e 0a0a  aths silently...
-000186f0: 4966 2079 6f75 2065 6e63 6f75 6e74 6572  If you encounter
-00018700: 2061 6e20 6572 726f 7220 6974 2063 616e   an error it can
-00018710: 2062 6520 7573 6566 756c 2066 6f72 2073   be useful for s
-00018720: 7570 706f 7274 2070 7572 706f 7365 7320  upport purposes 
-00018730: 746f 2073 6565 2074 6865 2066 756c 6c20  to see the full 
-00018740: 5079 7468 6f6e 2073 7461 636b 2074 7261  Python stack tra
-00018750: 6365 2e20 5468 6973 2063 616e 2062 6520  ce. This can be 
-00018760: 656e 6162 6c65 6420 6279 2072 756e 6e69  enabled by runni
-00018770: 6e67 2074 6865 2063 6f6d 6d61 6e64 2075  ng the command u
-00018780: 7369 6e67 2074 6865 2060 2d2d 6465 6275  sing the `--debu
-00018790: 6760 206f 7074 696f 6e2e 0a0a 2323 2079  g` option...## y
-000187a0: 642d 7375 626d 6974 0a0a 5468 6520 6079  d-submit..The `y
-000187b0: 642d 7375 626d 6974 6020 636f 6d6d 616e  d-submit` comman
-000187c0: 6420 7375 626d 6974 7320 6120 6e65 7720  d submits a new 
-000187d0: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
-000187e0: 2c20 6163 636f 7264 696e 6720 746f 2074  , according to t
-000187f0: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
-00018800: 656e 7420 6465 6669 6e69 7469 6f6e 2066  ent definition f
-00018810: 6f75 6e64 2069 6e20 7468 6520 6077 6f72  ound in the `wor
-00018820: 6b52 6571 7569 7265 6d65 6e74 6020 7365  kRequirement` se
-00018830: 6374 696f 6e20 6f66 2074 6865 2054 4f4d  ction of the TOM
-00018840: 4c20 636f 6e66 6967 7572 6174 696f 6e20  L configuration 
-00018850: 6669 6c65 2061 6e64 2f6f 7220 7468 6520  file and/or the 
-00018860: 7370 6563 6966 6963 6174 696f 6e20 666f  specification fo
-00018870: 756e 6420 696e 2061 2057 6f72 6b20 5265  und in a Work Re
-00018880: 7175 6972 656d 656e 7420 4a53 4f4e 2064  quirement JSON d
-00018890: 6f63 756d 656e 7420 7375 7070 6c69 6564  ocument supplied
-000188a0: 2075 7369 6e67 2074 6865 2060 2d2d 776f   using the `--wo
-000188b0: 726b 2d72 6571 7569 7265 6d65 6e74 6020  rk-requirement` 
-000188c0: 6f70 7469 6f6e 2e0a 0a55 7365 2074 6865  option...Use the
-000188d0: 2060 2d2d 6472 792d 7275 6e60 206f 7074   `--dry-run` opt
-000188e0: 696f 6e20 746f 2069 6e73 7065 6374 2074  ion to inspect t
-000188f0: 6865 2064 6574 6169 6c73 206f 6620 7468  he details of th
-00018900: 6520 576f 726b 2052 6571 7569 7265 6d65  e Work Requireme
-00018910: 6e74 2c20 5461 736b 2047 726f 7570 732c  nt, Task Groups,
-00018920: 2061 6e64 2054 6173 6b73 2074 6861 7420   and Tasks that 
-00018930: 7769 6c6c 2062 6520 7375 626d 6974 7465  will be submitte
-00018940: 642c 2069 6e20 4a53 4f4e 2066 6f72 6d61  d, in JSON forma
-00018950: 742e 0a0a 4f6e 6365 2073 7562 6d69 7474  t...Once submitt
-00018960: 6564 2c20 7468 6520 576f 726b 2052 6571  ed, the Work Req
-00018970: 7569 7265 6d65 6e74 2077 696c 6c20 6170  uirement will ap
-00018980: 7065 6172 2069 6e20 7468 6520 2a2a 576f  pear in the **Wo
-00018990: 726b 2a2a 2074 6162 2069 6e20 7468 6520  rk** tab in the 
-000189a0: 5965 6c6c 6f77 446f 6720 506f 7274 616c  YellowDog Portal
-000189b0: 2e0a 0a54 6865 2057 6f72 6b20 5265 7175  ...The Work Requ
-000189c0: 6972 656d 656e 7427 7320 7072 6f67 7265  irement's progre
-000189d0: 7373 2063 616e 2062 6520 7472 6163 6b65  ss can be tracke
-000189e0: 6420 746f 2063 6f6d 706c 6574 696f 6e20  d to completion 
-000189f0: 6279 2075 7369 6e67 2074 6865 2060 2d2d  by using the `--
-00018a00: 666f 6c6c 6f77 6020 286f 7220 602d 6660  follow` (or `-f`
-00018a10: 2920 6f70 7469 6f6e 2077 6865 6e20 696e  ) option when in
-00018a20: 766f 6b69 6e67 2060 7964 2d73 7562 6d69  voking `yd-submi
-00018a30: 7460 3a20 7468 6520 636f 6d6d 616e 6420  t`: the command 
-00018a40: 7769 6c6c 2072 6570 6f72 7420 6f6e 2054  will report on T
-00018a50: 6173 6b73 2061 7320 7468 6579 2063 6f6e  asks as they con
-00018a60: 636c 7564 6520 616e 6420 776f 6e27 7420  clude and won't 
-00018a70: 7265 7475 726e 2075 6e74 696c 2074 6865  return until the
-00018a80: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
-00018a90: 7420 6861 7320 6669 6e69 7368 6564 2e0a  t has finished..
-00018aa0: 0a23 2320 7964 2d70 726f 7669 7369 6f6e  .## yd-provision
-00018ab0: 0a0a 5468 6520 6079 642d 7072 6f76 6973  ..The `yd-provis
-00018ac0: 696f 6e60 2063 6f6d 6d61 6e64 2070 726f  ion` command pro
-00018ad0: 7669 7369 6f6e 7320 6120 6e65 7720 576f  visions a new Wo
-00018ae0: 726b 6572 2050 6f6f 6c20 6163 636f 7264  rker Pool accord
-00018af0: 696e 6720 746f 2074 6865 2073 7065 6369  ing to the speci
-00018b00: 6669 6361 7469 6f6e 7320 696e 2074 6865  fications in the
-00018b10: 2060 776f 726b 6572 506f 6f6c 6020 7365   `workerPool` se
-00018b20: 6374 696f 6e20 6f66 2074 6865 2054 4f4d  ction of the TOM
-00018b30: 4c20 636f 6e66 6967 7572 6174 696f 6e20  L configuration 
-00018b40: 6669 6c65 2061 6e64 2f6f 7220 696e 2074  file and/or in t
-00018b50: 6865 2073 7065 6369 6669 6361 7469 6f6e  he specification
-00018b60: 2066 6f75 6e64 2069 6e20 6120 576f 726b   found in a Work
-00018b70: 6572 2050 6f6f 6c20 4a53 4f4e 2064 6f63  er Pool JSON doc
-00018b80: 756d 656e 7420 7375 7070 6c69 6564 2075  ument supplied u
-00018b90: 7369 6e67 2074 6865 2060 2d2d 776f 726b  sing the `--work
-00018ba0: 6572 2d70 6f6f 6c60 206f 7074 696f 6e2e  er-pool` option.
-00018bb0: 0a0a 5573 6520 7468 6520 602d 2d64 7279  ..Use the `--dry
-00018bc0: 2d72 756e 6020 6f70 7469 6f6e 2074 6f20  -run` option to 
-00018bd0: 696e 7370 6563 7420 7468 6520 6465 7461  inspect the deta
-00018be0: 696c 7320 6f66 2074 6865 2057 6f72 6b65  ils of the Worke
-00018bf0: 7220 506f 6f6c 2073 7065 6369 6669 6361  r Pool specifica
-00018c00: 7469 6f6e 2074 6861 7420 7769 6c6c 2062  tion that will b
-00018c10: 6520 7375 626d 6974 7465 642c 2069 6e20  e submitted, in 
-00018c20: 4a53 4f4e 2066 6f72 6d61 742e 0a0a 4f6e  JSON format...On
-00018c30: 6365 2070 726f 7669 7369 6f6e 6564 2c20  ce provisioned, 
-00018c40: 7468 6520 576f 726b 6572 2050 6f6f 6c20  the Worker Pool 
-00018c50: 7769 6c6c 2061 7070 6561 7220 696e 2074  will appear in t
-00018c60: 6865 202a 2a57 6f72 6b65 7273 2a2a 2074  he **Workers** t
-00018c70: 6162 2069 6e20 7468 6520 5965 6c6c 6f77  ab in the Yellow
-00018c80: 446f 6720 506f 7274 616c 2c20 616e 6420  Dog Portal, and 
-00018c90: 6974 7320 6173 736f 6369 6174 6564 2043  its associated C
-00018ca0: 6f6d 7075 7465 2052 6571 7569 7265 6d65  ompute Requireme
-00018cb0: 6e74 2077 696c 6c20 6170 7065 6172 2069  nt will appear i
-00018cc0: 6e20 7468 6520 2a2a 436f 6d70 7574 652a  n the **Compute*
-00018cd0: 2a20 7461 622e 0a0a 2323 2079 642d 6361  * tab...## yd-ca
-00018ce0: 6e63 656c 0a0a 5468 6520 6079 642d 6361  ncel..The `yd-ca
-00018cf0: 6e63 656c 6020 636f 6d6d 616e 6420 6361  ncel` command ca
-00018d00: 6e63 656c 7320 616e 7920 6163 7469 7665  ncels any active
-00018d10: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
-00018d20: 7473 2c20 696e 636c 7564 696e 6720 616e  ts, including an
-00018d30: 7920 7065 6e64 696e 6720 5461 736b 2047  y pending Task G
-00018d40: 726f 7570 7320 616e 6420 7468 6520 5461  roups and the Ta
-00018d50: 736b 7320 7468 6579 2063 6f6e 7461 696e  sks they contain
-00018d60: 2e20 0a0a 5468 6520 606e 616d 6573 7061  . ..The `namespa
-00018d70: 6365 6020 616e 6420 6074 6167 6020 7661  ce` and `tag` va
-00018d80: 6c75 6573 2069 6e20 7468 6520 6063 6f6e  lues in the `con
-00018d90: 6669 672e 746f 6d6c 6020 6669 6c65 2061  fig.toml` file a
-00018da0: 7265 2075 7365 6420 746f 2069 6465 6e74  re used to ident
-00018db0: 6966 7920 7768 6963 6820 576f 726b 2052  ify which Work R
-00018dc0: 6571 7569 7265 6d65 6e74 7320 746f 2063  equirements to c
-00018dd0: 616e 6365 6c2e 0a0a 4279 2064 6566 6175  ancel...By defau
-00018de0: 6c74 2c20 616e 7920 5461 736b 7320 7468  lt, any Tasks th
-00018df0: 6174 2061 7265 2063 7572 7265 6e74 6c79  at are currently
-00018e00: 2072 756e 6e69 6e67 206f 6e20 576f 726b   running on Work
-00018e10: 6572 7320 7769 6c6c 2063 6f6e 7469 6e75  ers will continu
-00018e20: 6520 746f 2072 756e 2074 6f20 636f 6d70  e to run to comp
-00018e30: 6c65 7469 6f6e 206f 7220 756e 7469 6c20  letion or until 
-00018e40: 7468 6579 2066 6169 6c2e 2054 6173 6b73  they fail. Tasks
-00018e50: 2063 616e 2062 6520 696e 7374 7275 6374   can be instruct
-00018e60: 6564 2074 6f20 6162 6f72 7420 696d 6d65  ed to abort imme
-00018e70: 6469 6174 656c 7920 6279 2073 7570 706c  diately by suppl
-00018e80: 7969 6e67 2074 6865 2060 2d2d 6162 6f72  ying the `--abor
-00018e90: 7460 206f 7220 602d 6160 206f 7074 696f  t` or `-a` optio
-00018ea0: 6e20 746f 2060 7964 2d63 616e 6365 6c60  n to `yd-cancel`
-00018eb0: 2e0a 0a23 2320 7964 2d61 626f 7274 0a0a  ...## yd-abort..
-00018ec0: 5468 6520 6079 642d 6162 6f72 7460 2063  The `yd-abort` c
-00018ed0: 6f6d 6d61 6e64 2069 7320 7573 6564 2074  ommand is used t
-00018ee0: 6f20 6162 6f72 7420 5461 736b 7320 7468  o abort Tasks th
-00018ef0: 6174 2061 7265 2063 7572 7265 6e74 6c79  at are currently
-00018f00: 2072 756e 6e69 6e67 2e20 5468 6520 7573   running. The us
-00018f10: 6572 2069 6e74 6572 6163 7469 7665 6c79  er interactively
-00018f20: 2073 656c 6563 7473 2074 6865 2057 6f72   selects the Wor
-00018f30: 6b20 5265 7175 6972 656d 656e 7473 2074  k Requirements t
-00018f40: 6f20 7461 7267 6574 2c20 616e 6420 7468  o target, and th
-00018f50: 656e 2077 6869 6368 2054 6173 6b73 2077  en which Tasks w
-00018f60: 6974 6869 6e20 7468 6f73 6520 576f 726b  ithin those Work
-00018f70: 2052 6571 7569 7265 6d65 6e74 7320 746f   Requirements to
-00018f80: 2061 626f 7274 2e20 5468 6520 576f 726b   abort. The Work
-00018f90: 2052 6571 7569 7265 6d65 6e74 7320 6172   Requirements ar
-00018fa0: 6520 6e6f 7420 6361 6e63 656c 6c65 6420  e not cancelled 
-00018fb0: 6173 2070 6172 7420 6f66 2074 6869 7320  as part of this 
-00018fc0: 7072 6f63 6573 732e 0a0a 5468 6520 606e  process...The `n
-00018fd0: 616d 6573 7061 6365 6020 616e 6420 6074  amespace` and `t
-00018fe0: 6167 6020 7661 6c75 6573 2069 6e20 7468  ag` values in th
-00018ff0: 6520 6063 6f6e 6669 672e 746f 6d6c 6020  e `config.toml` 
-00019000: 6669 6c65 2061 7265 2075 7365 6420 746f  file are used to
-00019010: 2069 6465 6e74 6966 7920 7768 6963 6820   identify which 
-00019020: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
-00019030: 7320 746f 206c 6973 7420 666f 7220 7365  s to list for se
-00019040: 6c65 6374 696f 6e2e 0a0a 2323 2079 642d  lection...## yd-
-00019050: 646f 776e 6c6f 6164 0a0a 5468 6520 6079  download..The `y
-00019060: 642d 646f 776e 6c6f 6164 6020 636f 6d6d  d-download` comm
-00019070: 616e 6420 646f 776e 6c6f 6164 7320 616e  and downloads an
-00019080: 7920 6f62 6a65 6374 7320 6372 6561 7465  y objects create
-00019090: 6420 696e 2074 6865 2059 656c 6c6f 7744  d in the YellowD
-000190a0: 6f67 204f 626a 6563 7420 5374 6f72 652e  og Object Store.
-000190b0: 0a0a 5468 6520 606e 616d 6573 7061 6365  ..The `namespace
-000190c0: 6020 616e 6420 6074 6167 6020 7661 6c75  ` and `tag` valu
-000190d0: 6573 2061 7265 2075 7365 6420 746f 2064  es are used to d
-000190e0: 6574 6572 6d69 6e65 2077 6869 6368 206f  etermine which o
-000190f0: 626a 6563 7473 2074 6f20 646f 776e 6c6f  bjects to downlo
-00019100: 6164 2e20 4f62 6a65 6374 7320 7769 6c6c  ad. Objects will
-00019110: 2062 6520 646f 776e 6c6f 6164 6564 2074   be downloaded t
-00019120: 6f20 6120 6469 7265 6374 6f72 7920 7769  o a directory wi
-00019130: 7468 2074 6865 2073 616d 6520 6e61 6d65  th the same name
-00019140: 2061 7320 606e 616d 6573 7061 6365 602e   as `namespace`.
-00019150: 2049 6620 6120 6469 7265 6374 6f72 7920   If a directory 
-00019160: 616c 7265 6164 7920 6578 6973 7473 2c20  already exists, 
-00019170: 6120 6e65 7720 6469 7265 6374 6f72 7920  a new directory 
-00019180: 7769 7468 206e 616d 6520 603c 6e61 6d65  with name `<name
-00019190: 7370 6163 653e 2e30 3160 2028 6574 632e  space>.01` (etc.
-000191a0: 2920 7769 6c6c 2062 6520 6372 6561 7465  ) will be create
-000191b0: 642e 0a0a 2323 2079 642d 6465 6c65 7465  d...## yd-delete
-000191c0: 0a0a 5468 6520 6079 642d 6465 6c65 7465  ..The `yd-delete
-000191d0: 6020 636f 6d6d 616e 6420 6465 6c65 7465  ` command delete
-000191e0: 7320 616e 7920 6f62 6a65 6374 7320 6372  s any objects cr
-000191f0: 6561 7465 6420 696e 2074 6865 2059 656c  eated in the Yel
-00019200: 6c6f 7744 6f67 204f 626a 6563 7420 5374  lowDog Object St
-00019210: 6f72 652e 0a0a 5468 6520 606e 616d 6573  ore...The `names
-00019220: 7061 6365 6020 616e 6420 6074 6167 6020  pace` and `tag` 
-00019230: 7661 6c75 6573 2069 6e20 7468 6520 6063  values in the `c
-00019240: 6f6e 6669 672e 746f 6d6c 6020 6669 6c65  onfig.toml` file
-00019250: 2061 7265 2075 7365 6420 746f 2069 6465   are used to ide
-00019260: 6e74 6966 7920 7768 6963 6820 6f62 6a65  ntify which obje
-00019270: 6374 7320 746f 2064 656c 6574 652e 204e  cts to delete. N
-00019280: 6f74 6520 7468 6174 2069 7427 7320 6561  ote that it's ea
-00019290: 7379 2074 6f20 7573 6520 6079 642d 6465  sy to use `yd-de
-000192a0: 6c65 7465 6020 746f 2063 6c65 6172 2074  lete` to clear t
-000192b0: 6865 2063 6f6e 7465 6e74 7320 6f66 2061  he contents of a
-000192c0: 206e 616d 6573 7061 6365 2062 7920 7573   namespace by us
-000192d0: 696e 6720 616e 2065 6d70 7479 2060 7461  ing an empty `ta
-000192e0: 6760 2c20 6173 2066 6f6c 6c6f 7773 3a0a  g`, as follows:.
-000192f0: 0a60 6060 7368 656c 6c0a 7964 2d64 656c  .```shell.yd-del
-00019300: 6574 6520 2d74 2022 220a 6060 600a 0a54  ete -t "".```..T
-00019310: 6869 7320 6361 6e20 6265 2065 7874 656e  his can be exten
-00019320: 6465 6420 746f 2061 6e79 206f 7468 6572  ded to any other
-00019330: 206e 616d 6573 7061 6365 2062 7920 7573   namespace by us
-00019340: 696e 6720 7468 6520 602d 2d6e 616d 6573  ing the `--names
-00019350: 7061 6365 602f 602d 6e60 206f 7074 696f  pace`/`-n` optio
-00019360: 6e2e 0a0a 2323 2079 642d 7570 6c6f 6164  n...## yd-upload
-00019370: 0a0a 5468 6520 6079 642d 7570 6c6f 6164  ..The `yd-upload
-00019380: 6020 636f 6d6d 616e 6420 7570 6c6f 6164  ` command upload
-00019390: 7320 6669 6c65 7320 6672 6f6d 2074 6865  s files from the
-000193a0: 206c 6f63 616c 2066 696c 6573 7973 7465   local filesyste
-000193b0: 6d20 746f 2074 6865 2059 656c 6c6f 7744  m to the YellowD
-000193c0: 6f67 204f 626a 6563 7420 7374 6f72 652e  og Object store.
-000193d0: 2046 696c 6573 2061 7265 2070 6c61 6365   Files are place
-000193e0: 6420 696e 2074 6865 2063 6f6e 6669 6775  d in the configu
-000193f0: 7265 6420 606e 616d 6573 7061 6365 6020  red `namespace` 
-00019400: 7769 7468 696e 2061 2064 6972 6563 746f  within a directo
-00019410: 7279 2073 7570 706c 6965 6420 7573 696e  ry supplied usin
-00019420: 6720 7468 6520 2872 6571 7569 7265 6429  g the (required)
-00019430: 2060 2d2d 6469 7265 6374 6f72 7960 206f   `--directory` o
-00019440: 7074 696f 6e2c 2065 2e67 2e3a 0a0a 6060  ption, e.g.:..``
-00019450: 6073 6865 6c6c 0a79 642d 7570 6c6f 6164  `shell.yd-upload
-00019460: 202d 2d64 6972 6563 746f 7279 206d 795f   --directory my_
-00019470: 776f 726b 5f72 6571 7569 7265 6d65 6e74  work_requirement
-00019480: 2066 696c 655f 3120 6669 6c65 5f32 206d   file_1 file_2 m
-00019490: 6f72 6566 696c 6573 2f66 696c 6533 0a60  orefiles/file3.`
-000194a0: 6060 0a54 6f20 7375 7070 7265 7373 2074  ``.To suppress t
-000194b0: 6865 206d 6972 726f 7269 6e67 206f 6620  he mirroring of 
-000194c0: 7468 6520 6c6f 6361 6c20 6469 7265 6374  the local direct
-000194d0: 6f72 7920 7374 7275 6374 7572 6520 7769  ory structure wi
-000194e0: 7468 696e 2074 6865 206f 626a 6563 7420  thin the object 
-000194f0: 7374 6f72 652c 2075 7365 2074 6865 2060  store, use the `
-00019500: 2d2d 666c 6174 7465 6e2d 7570 6c6f 6164  --flatten-upload
-00019510: 2d70 6174 6873 6020 6f72 2060 2d66 6020  -paths` or `-f` 
-00019520: 6f70 7469 6f6e 2e20 4e6f 7465 2074 6861  option. Note tha
-00019530: 7420 6966 2074 6869 7320 6372 6561 7465  t if this create
-00019540: 7320 6d75 6c74 6970 6c65 2075 706c 6f61  s multiple uploa
-00019550: 6465 6420 6669 6c65 7320 7769 7468 2074  ded files with t
-00019560: 6865 2073 616d 6520 7061 7468 2069 6e20  he same path in 
-00019570: 7468 6520 4f62 6a65 6374 2053 746f 7265  the Object Store
-00019580: 2066 6f6c 6465 722c 2066 696c 6573 2077   folder, files w
-00019590: 696c 6c20 6265 206f 7665 7277 7269 7474  ill be overwritt
-000195a0: 656e 2e0a 0a46 696c 6573 2069 6e20 6469  en...Files in di
-000195b0: 7265 6374 6f72 6965 7320 6d61 7920 6265  rectories may be
-000195c0: 2072 6563 7572 7369 7665 6c79 2075 706c   recursively upl
-000195d0: 6f61 6465 6420 7573 696e 6720 7468 6520  oaded using the 
-000195e0: 602d 2d72 6563 7572 7369 7665 6020 6f72  `--recursive` or
-000195f0: 2060 2d72 6020 6f70 7469 6f6e 2c20 652e   `-r` option, e.
-00019600: 672e 3a0a 0a60 6060 7368 656c 6c0a 7964  g.:..```shell.yd
-00019610: 2d75 706c 6f61 6420 2d2d 6469 7265 6374  -upload --direct
-00019620: 6f72 7920 6d79 5f77 6f72 6b5f 7265 7175  ory my_work_requ
-00019630: 6972 656d 656e 7420 2d72 206d 7964 6972  irement -r mydir
-00019640: 206d 796f 7468 6572 6469 720a 6060 600a   myotherdir.```.
-00019650: 0a54 6f20 7570 6c6f 6164 2074 6f20 6f74  .To upload to ot
-00019660: 6865 7220 6e61 6d65 7370 6163 6573 2c20  her namespaces, 
-00019670: 7573 6520 7468 6520 602d 2d6e 616d 6573  use the `--names
-00019680: 7061 6365 602f 602d 6e60 206f 7074 696f  pace`/`-n` optio
-00019690: 6e2e 0a0a 2323 2079 642d 7368 7574 646f  n...## yd-shutdo
-000196a0: 776e 0a0a 5468 6520 6079 642d 7368 7574  wn..The `yd-shut
-000196b0: 646f 776e 6020 636f 6d6d 616e 6420 7368  down` command sh
-000196c0: 7574 7320 646f 776e 2057 6f72 6b65 7220  uts down Worker 
-000196d0: 506f 6f6c 7320 7468 6174 206d 6174 6368  Pools that match
-000196e0: 2074 6865 2060 6e61 6d65 7370 6163 6560   the `namespace`
-000196f0: 2061 6e64 2060 7461 6760 2066 6f75 6e64   and `tag` found
-00019700: 2069 6e20 7468 6520 636f 6e66 6967 7572   in the configur
-00019710: 6174 696f 6e20 6669 6c65 2e20 416c 6c20  ation file. All 
-00019720: 7265 6d61 696e 696e 6720 776f 726b 2077  remaining work w
-00019730: 696c 6c20 6265 2063 616e 6365 6c6c 6564  ill be cancelled
-00019740: 2c20 6275 7420 6375 7272 656e 746c 7920  , but currently 
-00019750: 6578 6563 7574 696e 6720 5461 736b 7320  executing Tasks 
-00019760: 7769 6c6c 2062 6520 616c 6c6f 7765 6420  will be allowed 
-00019770: 746f 2063 6f6d 706c 6574 652c 2061 6674  to complete, aft
-00019780: 6572 2077 6869 6368 2074 6865 2043 6f6d  er which the Com
-00019790: 7075 7465 2052 6571 7569 7265 6d65 6e74  pute Requirement
-000197a0: 2077 696c 6c20 6265 2074 6572 6d69 6e61   will be termina
-000197b0: 7465 642e 0a0a 2323 2079 642d 696e 7374  ted...## yd-inst
-000197c0: 616e 7469 6174 650a 0a54 6865 2060 7964  antiate..The `yd
-000197d0: 2d69 6e73 7461 6e74 6961 7465 6020 636f  -instantiate` co
-000197e0: 6d6d 616e 6420 696e 7374 616e 7469 6174  mmand instantiat
-000197f0: 6573 2061 2043 6f6d 7075 7465 2052 6571  es a Compute Req
-00019800: 7569 7265 6d65 6e74 2028 692e 652e 2c20  uirement (i.e., 
-00019810: 6120 7365 7420 6f66 2069 6e73 7461 6e63  a set of instanc
-00019820: 6573 2074 6861 7420 6172 6520 6d61 6e61  es that are mana
-00019830: 6765 6420 6279 2074 6865 6972 2063 7265  ged by their cre
-00019840: 6174 6f72 2061 6e64 2064 6f20 6e6f 7420  ator and do not 
-00019850: 6175 746f 6d61 7469 6361 6c6c 7920 6265  automatically be
-00019860: 636f 6d65 2070 6172 7420 6f66 2061 2059  come part of a Y
-00019870: 656c 6c6f 7744 6f67 2057 6f72 6b65 7220  ellowDog Worker 
-00019880: 506f 6f6c 292e 0a0a 5468 6973 2063 6f6d  Pool)...This com
-00019890: 6d61 6e64 2075 7365 7320 7468 6520 6461  mand uses the da
-000198a0: 7461 2066 726f 6d20 7468 6520 6077 6f72  ta from the `wor
-000198b0: 6b65 7250 6f6f 6c60 2063 6f6e 6669 6775  kerPool` configu
-000198c0: 7261 7469 6f6e 2073 6563 7469 6f6e 2c20  ration section, 
-000198d0: 6275 7420 6f6e 6c79 2075 7365 7320 7468  but only uses th
-000198e0: 6520 606e 616d 6560 2c20 6074 656d 706c  e `name`, `templ
-000198f0: 6174 6549 6460 2c20 6074 6172 6765 7449  ateId`, `targetI
-00019900: 6e73 7461 6e63 6543 6f75 6e74 602c 2060  nstanceCount`, `
-00019910: 696e 7374 616e 6365 5461 6773 602c 2060  instanceTags`, `
-00019920: 7573 6572 4461 7461 602c 2061 6e64 2060  userData`, and `
-00019930: 696d 6167 6573 4964 6020 7072 6f70 6572  imagesId` proper
-00019940: 7469 6573 2e20 496e 2061 6464 6974 696f  ties. In additio
-00019950: 6e2c 2074 6865 2042 6f6f 6c65 616e 2070  n, the Boolean p
-00019960: 726f 7065 7274 7920 606d 6169 6e74 6169  roperty `maintai
-00019970: 6e49 6e73 7461 6e63 6543 6f75 6e74 6020  nInstanceCount` 
-00019980: 2864 6566 6175 6c74 203d 2060 6661 6c73  (default = `fals
-00019990: 6560 2920 6973 2061 7661 696c 6162 6c65  e`) is available
-000199a0: 2066 6f72 2075 7365 2077 6974 6820 6079   for use with `y
-000199b0: 642d 696e 7374 616e 7469 6174 6560 2e0a  d-instantiate`..
-000199c0: 0a43 6f6d 7075 7465 2052 6571 7569 7265  .Compute Require
-000199d0: 6d65 6e74 7320 6361 6e20 6265 2069 6e73  ments can be ins
-000199e0: 7461 6e74 6961 7465 6420 6469 7265 6374  tantiated direct
-000199f0: 6c79 2066 726f 6d20 4a53 4f4e 2028 6f72  ly from JSON (or
-00019a00: 204a 736f 6e6e 6574 2920 7370 6563 6966   Jsonnet) specif
-00019a10: 6963 6174 696f 6e73 2c20 7573 696e 6720  ications, using 
-00019a20: 7468 6520 602d 2d63 6f6d 7075 7465 2d72  the `--compute-r
-00019a30: 6571 7569 7265 6d65 6e74 6020 286f 7220  equirement` (or 
-00019a40: 602d 4360 2920 636f 6d6d 616e 6420 6c69  `-C`) command li
-00019a50: 6e65 206f 7074 696f 6e2c 2066 6f6c 6c6f  ne option, follo
-00019a60: 7765 6420 6279 2074 6865 2066 696c 656e  wed by the filen
-00019a70: 616d 652e 2054 6865 2070 726f 7065 7274  ame. The propert
-00019a80: 6965 7320 6c69 7374 6564 2061 626f 7665  ies listed above
-00019a90: 2077 696c 6c20 6265 2069 6e68 6572 6974   will be inherit
-00019aa0: 6564 2066 726f 6d20 7468 6520 636f 6e66  ed from the conf
-00019ab0: 6967 2e74 6f6d 6c20 6077 6f72 6b65 7250  ig.toml `workerP
-00019ac0: 6f6f 6c60 2073 7065 6369 6669 6361 7469  ool` specificati
-00019ad0: 6f6e 2069 6620 7468 6579 2061 7265 206e  on if they are n
-00019ae0: 6f74 2070 7265 7365 6e74 2069 6e20 7468  ot present in th
-00019af0: 6520 4a53 4f4e 2066 696c 652e 2041 6e20  e JSON file. An 
-00019b00: 6578 616d 706c 6520 4a53 4f4e 2073 7065  example JSON spe
-00019b10: 6369 6669 6361 7469 6f6e 2069 7320 7368  cification is sh
-00019b20: 6f77 6e20 6265 6c6f 773a 0a0a 6060 606a  own below:..```j
-00019b30: 736f 6e0a 7b0a 2020 2269 6d61 6765 7349  son.{.  "imagesI
-00019b40: 6422 3a20 2279 6469 643a 696d 6766 616d  d": "ydid:imgfam
-00019b50: 3a30 3030 3030 303a 3431 3936 3235 3932  :000000:41962592
-00019b60: 2d35 3737 632d 3466 6465 2d61 6230 332d  -577c-4fde-ab03-
-00019b70: 6438 3532 3436 3565 3766 3862 222c 0a20  d852465e7f8b",. 
-00019b80: 2022 696e 7374 616e 6365 5461 6773 223a   "instanceTags":
-00019b90: 207b 2261 3122 3a20 226f 6e65 222c 2022   {"a1": "one", "
-00019ba0: 6132 223a 2022 7477 6f22 7d2c 0a20 2022  a2": "two"},.  "
-00019bb0: 7265 7175 6972 656d 656e 744e 616d 6522  requirementName"
-00019bc0: 3a20 2263 725f 7465 7374 5f7b 7b64 6174  : "cr_test_{{dat
-00019bd0: 6574 696d 657d 7d22 2c0a 2020 2272 6571  etime}}",.  "req
-00019be0: 7569 7265 6d65 6e74 4e61 6d65 7370 6163  uirementNamespac
-00019bf0: 6522 3a20 2270 7965 7861 6d70 6c65 7322  e": "pyexamples"
-00019c00: 2c0a 2020 2272 6571 7569 7265 6d65 6e74  ,.  "requirement
-00019c10: 5461 6722 3a20 2270 7965 7861 6d70 6c65  Tag": "pyexample
-00019c20: 732d 7465 7374 222c 0a20 2022 7465 6d70  s-test",.  "temp
-00019c30: 6c61 7465 4964 223a 2022 7964 6964 3a63  lateId": "ydid:c
-00019c40: 7274 3a30 3030 3030 303a 3233 3065 3961  rt:000000:230e9a
-00019c50: 3432 2d39 3764 622d 3464 3639 2d61 6139  42-97db-4d69-aa9
-00019c60: 312d 3239 6666 3330 3939 3531 6234 222c  1-29ff309951b4",
-00019c70: 0a20 2022 7573 6572 4461 7461 223a 2022  .  "userData": "
-00019c80: 232f 6269 6e2f 6261 7368 5c6e 234f 7468  #/bin/bash\n#Oth
-00019c90: 6572 2073 7475 6666 2e2e 2e22 2c0a 2020  er stuff...",.  
-00019ca0: 2274 6172 6765 7449 6e73 7461 6e63 6543  "targetInstanceC
-00019cb0: 6f75 6e74 223a 2031 2c0a 2020 226d 6169  ount": 1,.  "mai
-00019cc0: 6e74 6169 6e49 6e73 7461 6e63 6543 6f75  ntainInstanceCou
-00019cd0: 6e74 223a 2074 7275 650a 7d0a 6060 600a  nt": true.}.```.
-00019ce0: 0a49 6620 6120 576f 726b 6572 2050 6f6f  .If a Worker Poo
-00019cf0: 6c20 6973 2064 6566 696e 6564 2c20 7573  l is defined, us
-00019d00: 696e 6720 6077 6f72 6b65 7250 6f6f 6c44  ing `workerPoolD
-00019d10: 6174 6160 2069 6e20 7468 6520 636f 6e66  ata` in the conf
-00019d20: 6967 7572 6174 696f 6e20 6669 6c65 206f  iguration file o
-00019d30: 7220 6279 2075 7369 6e67 2074 6865 2060  r by using the `
-00019d40: 2d2d 776f 726b 6572 2d70 6f6f 6c60 2028  --worker-pool` (
-00019d50: 6f72 2060 2d70 6029 206f 7074 696f 6e2c  or `-p`) option,
-00019d60: 2060 7964 2d69 6e73 7461 6e74 6961 7465   `yd-instantiate
-00019d70: 6020 7769 6c6c 2065 7874 7261 6374 2074  ` will extract t
-00019d80: 6865 2043 6f6d 7075 7465 2052 6571 7569  he Compute Requi
-00019d90: 7265 6d65 6e74 2066 726f 6d20 7468 6520  rement from the 
-00019da0: 576f 726b 6572 2050 6f6f 6c20 7370 6563  Worker Pool spec
-00019db0: 6966 6963 6174 696f 6e20 2869 676e 6f72  ification (ignor
-00019dc0: 696e 6720 576f 726b 6572 2d50 6f6f 6c2d  ing Worker-Pool-
-00019dd0: 7370 6563 6966 6963 2064 6174 6129 2c20  specific data), 
-00019de0: 616e 6420 7573 6520 7468 6174 2066 6f72  and use that for
-00019df0: 2069 6e73 7461 6e74 6961 7469 6e67 2074   instantiating t
-00019e00: 6865 2043 6f6d 7075 7465 2052 6571 7569  he Compute Requi
-00019e10: 7265 6d65 6e74 2e0a 0a55 7365 2074 6865  rement...Use the
-00019e20: 2060 2d2d 6472 792d 7275 6e60 206f 7074   `--dry-run` opt
-00019e30: 696f 6e20 746f 2069 6e73 7065 6374 2074  ion to inspect t
-00019e40: 6865 2064 6574 6169 6c73 206f 6620 7468  he details of th
-00019e50: 6520 436f 6d70 7574 6520 5265 7175 6972  e Compute Requir
-00019e60: 656d 656e 7420 7370 6563 6966 6963 6174  ement specificat
-00019e70: 696f 6e20 7468 6174 2077 696c 6c20 6265  ion that will be
-00019e80: 2073 7562 6d69 7474 6564 2c20 696e 204a   submitted, in J
-00019e90: 534f 4e20 666f 726d 6174 2e20 5468 6520  SON format. The 
-00019ea0: 4a53 4f4e 206f 7574 7075 7420 6f66 2074  JSON output of t
-00019eb0: 6869 7320 636f 6d6d 616e 6420 6361 6e20  his command can 
-00019ec0: 6265 2075 7365 6420 7769 7468 2074 6865  be used with the
-00019ed0: 2060 2d43 6020 6f70 7469 6f6e 2061 626f   `-C` option abo
-00019ee0: 7665 2028 6f72 2077 6974 6820 602d 7060  ve (or with `-p`
-00019ef0: 2066 6f72 2057 6f72 6b65 7220 506f 6f6c   for Worker Pool
-00019f00: 2073 7065 6369 6669 6361 7469 6f6e 7329   specifications)
-00019f10: 2e0a 0a23 2323 2054 6573 742d 5275 6e6e  ...### Test-Runn
-00019f20: 696e 6720 6120 4479 6e61 6d69 6320 5465  ing a Dynamic Te
-00019f30: 6d70 6c61 7465 0a0a 5768 656e 2061 2074  mplate..When a t
-00019f40: 6865 2060 7465 6d70 6c61 7465 4964 6020  he `templateId` 
-00019f50: 6f66 2061 2044 796e 616d 6963 2052 6571  of a Dynamic Req
-00019f60: 7569 7265 6d65 6e74 2069 7320 7573 6564  uirement is used
-00019f70: 2c20 7468 6520 6079 642d 696e 7374 616e  , the `yd-instan
-00019f80: 7469 6174 6560 2063 6f6d 6d61 6e64 2063  tiate` command c
-00019f90: 616e 2062 6520 7573 6564 2074 6f20 7265  an be used to re
-00019fa0: 706f 7274 206f 6e20 6120 7465 7374 2072  port on a test r
-00019fb0: 756e 206f 6620 7468 6520 5465 6d70 6c61  un of the Templa
-00019fc0: 7465 2c20 7573 696e 6720 7468 6520 602d  te, using the `-
-00019fd0: 2d72 6570 6f72 7460 2028 6f72 2060 2d72  -report` (or `-r
-00019fe0: 6029 2063 6f6d 6d61 6e64 206c 696e 6520  `) command line 
-00019ff0: 6f70 7469 6f6e 2e20 5468 6973 2063 616e  option. This can
-0001a000: 2062 6520 7573 6564 2077 6974 6820 544f   be used with TO
-0001a010: 4d4c 2d64 6566 696e 6564 2043 6f6d 7075  ML-defined Compu
-0001a020: 7465 2052 6571 7569 7265 6d65 6e74 2073  te Requirement s
-0001a030: 7065 6369 6669 6361 7469 6f6e 732c 2062  pecifications, b
-0001a040: 7574 206e 6f74 2074 686f 7365 2074 6861  ut not those tha
-0001a050: 7420 6172 6520 4a53 4f4e 2d64 6566 696e  t are JSON-defin
-0001a060: 6564 2e0a 0a4e 6f20 696e 7374 616e 6365  ed...No instance
-0001a070: 7320 7769 6c6c 2062 6520 7072 6f76 6973  s will be provis
-0001a080: 696f 6e65 6420 6475 7269 6e67 2074 6865  ioned during the
-0001a090: 2074 6573 7420 7275 6e2e 0a0a 466f 7220   test run...For 
-0001a0a0: 6578 616d 706c 653a 0a0a 6060 6073 6865  example:..```she
-0001a0b0: 6c6c 0a25 2079 642d 696e 7374 616e 7469  ll.% yd-instanti
-0001a0c0: 6174 6520 2d2d 7265 706f 7274 202d 2d71  ate --report --q
-0001a0d0: 7569 6574 0a0a e294 8ce2 9480 e294 80e2  uiet............
-0001a0e0: 9480 e294 80e2 94ac e294 80e2 9480 e294  ................
-0001a0f0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a100: e294 ace2 9480 e294 80e2 9480 e294 80e2  ................
-0001a110: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a120: 80e2 9480 e294 80e2 94ac e294 80e2 9480  ................
-0001a130: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+00013dd0: 7c20 5468 6520 6e61 6d65 206f 6620 7468  | The name of th
+00013de0: 6520 576f 726b 6572 2050 6f6f 6c2e 2020  e Worker Pool.  
+00013df0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013e00: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013e10: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013e20: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013e30: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013e40: 2020 2020 2020 2020 2020 7c20 4175 746f            | Auto
+00013e50: 6d61 7469 6361 6c6c 7920 4765 6e65 7261  matically Genera
+00013e60: 7465 6420 7c0a 7c20 606e 6f64 6542 6f6f  ted |.| `nodeBoo
+00013e70: 7454 696d 656f 7574 6020 2020 2020 2020  tTimeout`       
+00013e80: 2020 7c20 5468 6520 7469 6d65 2069 6e20    | The time in 
+00013e90: 6d69 6e75 7465 7320 616c 6c6f 7765 6420  minutes allowed 
+00013ea0: 666f 7220 6120 6e6f 6465 2074 6f20 626f  for a node to bo
+00013eb0: 6f74 2061 6e64 2072 6567 6973 7465 7220  ot and register 
+00013ec0: 7769 7468 2074 6865 2070 6c61 7466 6f72  with the platfor
+00013ed0: 6d2c 206f 7468 6572 7769 7365 2069 7420  m, otherwise it 
+00013ee0: 7769 6c6c 2062 6520 7465 726d 696e 6174  will be terminat
+00013ef0: 6564 2e20 2020 2020 2020 2020 7c20 6031  ed.         | `1
+00013f00: 302e 3060 2020 2020 2020 2020 2020 2020  0.0`            
+00013f10: 2020 2020 2020 7c0a 7c20 6074 6172 6765        |.| `targe
+00013f20: 7449 6e73 7461 6e63 6543 6f75 6e74 6020  tInstanceCount` 
+00013f30: 2020 2020 7c20 5468 6520 696e 6974 6961      | The initia
+00013f40: 6c20 6e75 6d62 6572 206f 6620 6e6f 6465  l number of node
+00013f50: 7320 746f 2063 7265 6174 6520 666f 7220  s to create for 
+00013f60: 7468 6520 576f 726b 6572 2050 6f6f 6c2e  the Worker Pool.
+00013f70: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013f80: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013f90: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00013fa0: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00013fb0: 6031 6020 2020 2020 2020 2020 2020 2020  `1`             
+00013fc0: 2020 2020 2020 2020 7c0a 7c20 6074 656d          |.| `tem
+00013fd0: 706c 6174 6549 6460 2020 2020 2020 2020  plateId`        
+00013fe0: 2020 2020 2020 7c20 5468 6520 5965 6c6c        | The Yell
+00013ff0: 6f77 446f 6720 436f 6d70 7574 6520 5465  owDog Compute Te
+00014000: 6d70 6c61 7465 2049 4420 746f 2075 7365  mplate ID to use
+00014010: 2066 6f72 2070 726f 7669 7369 6f6e 696e   for provisionin
+00014020: 672e 2028 2a2a 5265 7175 6972 6564 2a2a  g. (**Required**
+00014030: 2c20 6e6f 2064 6566 6175 6c74 2070 726f  , no default pro
+00014040: 7669 6465 642e 2920 2020 2020 2020 2020  vided.)         
+00014050: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014060: 7c20 2020 2020 2020 2020 2020 2020 2020  |               
+00014070: 2020 2020 2020 2020 2020 7c0a 7c20 6075            |.| `u
+00014080: 7365 7244 6174 6160 2020 2020 2020 2020  serData`        
+00014090: 2020 2020 2020 2020 7c20 5573 6572 2044          | User D
+000140a0: 6174 6120 746f 2062 6520 7375 7070 6c69  ata to be suppli
+000140b0: 6564 2074 6f20 696e 7374 616e 6365 7320  ed to instances 
+000140c0: 6f6e 2062 6f6f 742e 2020 2020 2020 2020  on boot.        
+000140d0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000140e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000140f0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014100: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014110: 2020 7c20 2020 2020 2020 2020 2020 2020    |             
+00014120: 2020 2020 2020 2020 2020 2020 7c0a 7c20              |.| 
+00014130: 6075 7365 7244 6174 6146 696c 6560 2020  `userDataFile`  
+00014140: 2020 2020 2020 2020 2020 7c20 4173 2061            | As a
+00014150: 626f 7665 2c20 6275 7420 7265 6164 2074  bove, but read t
+00014160: 6865 2055 7365 7220 4461 7461 2066 726f  he User Data fro
+00014170: 6d20 7468 6520 6669 6c65 6e61 6d65 2073  m the filename s
+00014180: 7570 706c 6965 6420 696e 2074 6869 7320  upplied in this 
+00014190: 7072 6f70 6572 7479 2e20 2020 2020 2020  property.       
+000141a0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000141b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000141c0: 2020 2020 7c20 2020 2020 2020 2020 2020      |           
+000141d0: 2020 2020 2020 2020 2020 2020 2020 7c0a                |.
+000141e0: 7c20 6075 7365 7244 6174 6146 696c 6573  | `userDataFiles
+000141f0: 6020 2020 2020 2020 2020 2020 7c20 4173  `           | As
+00014200: 2061 626f 7665 2c20 6275 7420 6372 6561   above, but crea
+00014210: 7465 2074 6865 2055 7365 7220 4461 7461  te the User Data
+00014220: 2062 7920 636f 6e63 6174 656e 6174 696e   by concatenatin
+00014230: 6720 7468 6520 636f 6e74 656e 7473 206f  g the contents o
+00014240: 6620 7468 6520 6c69 7374 206f 6620 6669  f the list of fi
+00014250: 6c65 6e61 6d65 7320 7375 7070 6c69 6564  lenames supplied
+00014260: 2069 6e20 7468 6973 2070 726f 7065 7274   in this propert
+00014270: 792e 2020 2020 7c20 2020 2020 2020 2020  y.    |         
+00014280: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014290: 7c0a 7c20 6077 6f72 6b65 7273 5065 7256  |.| `workersPerV
+000142a0: 4350 5560 2020 2020 2020 2020 2020 7c20  CPU`          | 
+000142b0: 5468 6520 6e75 6d62 6572 206f 6620 576f  The number of Wo
+000142c0: 726b 6572 7320 746f 2065 7374 6162 6c69  rkers to establi
+000142d0: 7368 2070 6572 2076 4350 5520 6f6e 2065  sh per vCPU on e
+000142e0: 6163 6820 6e6f 6465 2069 6e20 7468 6520  ach node in the 
+000142f0: 576f 726b 6572 2050 6f6f 6c2e 2028 4f76  Worker Pool. (Ov
+00014300: 6572 7269 6465 7320 6077 6f72 6b65 7273  errides `workers
+00014310: 5065 724e 6f64 6560 2e29 2020 2020 2020  PerNode`.)      
+00014320: 2020 2020 2020 2020 7c20 2020 2020 2020          |       
+00014330: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014340: 2020 7c0a 7c20 6077 6f72 6b65 7273 5065    |.| `workersPe
+00014350: 724e 6f64 6560 2020 2020 2020 2020 2020  rNode`          
+00014360: 7c20 5468 6520 6e75 6d62 6572 206f 6620  | The number of 
+00014370: 576f 726b 6572 7320 746f 2065 7374 6162  Workers to estab
+00014380: 6c69 7368 206f 6e20 6561 6368 206e 6f64  lish on each nod
+00014390: 6520 696e 2074 6865 2057 6f72 6b65 7220  e in the Worker 
+000143a0: 506f 6f6c 2e20 2020 2020 2020 2020 2020  Pool.           
+000143b0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000143c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000143d0: 2020 2020 2020 2020 2020 7c20 6031 6020            | `1` 
+000143e0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000143f0: 2020 2020 7c0a 7c20 6077 6f72 6b65 7250      |.| `workerP
+00014400: 6f6f 6c44 6174 6160 2020 2020 2020 2020  oolData`        
+00014410: 2020 7c20 5468 6520 6e61 6d65 206f 6620    | The name of 
+00014420: 6120 6669 6c65 2063 6f6e 7461 696e 696e  a file containin
+00014430: 6720 6120 4a53 4f4e 2064 6f63 756d 656e  g a JSON documen
+00014440: 7420 6465 6669 6e69 6e67 2061 2057 6f72  t defining a Wor
+00014450: 6b65 7220 506f 6f6c 2e20 2020 2020 2020  ker Pool.       
+00014460: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014470: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014480: 2020 2020 2020 2020 2020 2020 7c20 2020              |   
+00014490: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000144a0: 2020 2020 2020 7c0a 7c20 6077 6f72 6b65        |.| `worke
+000144b0: 7254 6167 6020 2020 2020 2020 2020 2020  rTag`           
+000144c0: 2020 2020 7c20 5468 6520 576f 726b 6572      | The Worker
+000144d0: 2054 6167 2074 6f20 7075 626c 6973 6820   Tag to publish 
+000144e0: 666f 7220 7468 6520 616c 6c20 6f66 2074  for the all of t
+000144f0: 6865 2057 6f72 6b65 7273 206f 6e20 7468  he Workers on th
+00014500: 6520 6e6f 6465 2e20 2020 2020 2020 2020  e node.         
+00014510: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014520: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014530: 2020 2020 2020 2020 2020 2020 2020 7c20                | 
+00014540: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00014550: 2020 2020 2020 2020 7c0a 0a23 2320 4175          |..## Au
+00014560: 746f 6d61 7469 6320 5072 6f70 6572 7469  tomatic Properti
+00014570: 6573 0a0a 5468 6520 6e61 6d65 206f 6620  es..The name of 
+00014580: 7468 6520 576f 726b 6572 2050 6f6f 6c2c  the Worker Pool,
+00014590: 2069 6620 6e6f 7420 7375 7070 6c69 6564   if not supplied
+000145a0: 2c20 6973 2061 7574 6f6d 6174 6963 616c  , is automatical
+000145b0: 6c79 2067 656e 6572 6174 6564 2075 7369  ly generated usi
+000145c0: 6e67 2061 2063 6f6e 6361 7465 6e61 7469  ng a concatenati
+000145d0: 6f6e 206f 6620 6077 705f 602c 2074 6865  on of `wp_`, the
+000145e0: 2060 7461 6760 2070 726f 7065 7274 792c   `tag` property,
+000145f0: 2061 2055 5443 2074 696d 6573 7461 6d70   a UTC timestamp
+00014600: 2c20 616e 6420 7468 7265 6520 7261 6e64  , and three rand
+00014610: 6f6d 2068 6578 2063 6861 7261 6374 6572  om hex character
+00014620: 733a 2065 2c67 2c2e 2060 7770 5f6d 7974  s: e,g,. `wp_myt
+00014630: 6167 5f32 3231 3032 342d 3135 3535 3234  ag_221024-155524
+00014640: 2d62 3061 602e 0a0a 2323 2054 4f4d 4c20  -b0a`...## TOML 
+00014650: 5072 6f70 6572 7469 6573 2069 6e20 7468  Properties in th
+00014660: 6520 6077 6f72 6b65 7250 6f6f 6c60 2053  e `workerPool` S
+00014670: 6563 7469 6f6e 0a0a 4865 7265 2773 2061  ection..Here's a
+00014680: 6e20 6578 616d 706c 6520 6f66 2074 6865  n example of the
+00014690: 2060 776f 726b 6572 506f 6f6c 6020 7365   `workerPool` se
+000146a0: 6374 696f 6e20 6f66 2061 2054 4f4d 4c20  ction of a TOML 
+000146b0: 636f 6e66 6967 7572 6174 696f 6e20 6669  configuration fi
+000146c0: 6c65 2c20 7368 6f77 696e 6720 616c 6c20  le, showing all 
+000146d0: 7468 6520 706f 7373 6962 6c65 2070 726f  the possible pro
+000146e0: 7065 7274 6965 7320 7468 6174 2063 616e  perties that can
+000146f0: 2062 6520 7365 743a 0a0a 6060 6074 6f6d   be set:..```tom
+00014700: 6c0a 5b77 6f72 6b65 7250 6f6f 6c5d 0a20  l.[workerPool]. 
+00014710: 2020 2069 646c 654e 6f64 6553 6875 7464     idleNodeShutd
+00014720: 6f77 6e45 6e61 626c 6564 203d 2074 7275  ownEnabled = tru
+00014730: 650a 2020 2020 6964 6c65 4e6f 6465 5368  e.    idleNodeSh
+00014740: 7574 646f 776e 5469 6d65 6f75 7420 3d20  utdownTimeout = 
+00014750: 3130 2e30 0a20 2020 2069 646c 6550 6f6f  10.0.    idlePoo
+00014760: 6c53 6875 7464 6f77 6e45 6e61 626c 6564  lShutdownEnabled
+00014770: 203d 2074 7275 650a 2020 2020 6964 6c65   = true.    idle
+00014780: 506f 6f6c 5368 7574 646f 776e 5469 6d65  PoolShutdownTime
+00014790: 6f75 7420 3d20 3630 2e30 0a20 2020 2069  out = 60.0.    i
+000147a0: 6d61 6765 7349 6420 3d20 2279 6469 643a  magesId = "ydid:
+000147b0: 696d 6766 616d 3a30 3030 3030 303a 3431  imgfam:000000:41
+000147c0: 3936 3235 3932 2d35 3737 632d 3466 6465  962592-577c-4fde
+000147d0: 2d61 6230 332d 6438 3532 3436 3565 3766  -ab03-d852465e7f
+000147e0: 3862 220a 2020 2020 696e 7374 616e 6365  8b".    instance
+000147f0: 5461 6773 203d 207b 7d0a 2020 2020 6d61  Tags = {}.    ma
+00014800: 784e 6f64 6573 203d 2031 0a20 2020 206d  xNodes = 1.    m
+00014810: 696e 4e6f 6465 7320 3d20 310a 2020 2020  inNodes = 1.    
+00014820: 6e61 6d65 203d 2022 6d79 2d77 6f72 6b65  name = "my-worke
+00014830: 722d 706f 6f6c 220a 2020 2020 6e6f 6465  r-pool".    node
+00014840: 426f 6f74 5469 6d65 6f75 7420 3d20 350a  BootTimeout = 5.
+00014850: 2020 2020 7461 7267 6574 496e 7374 616e      targetInstan
+00014860: 6365 436f 756e 7420 3d20 310a 2020 2020  ceCount = 1.    
+00014870: 7465 6d70 6c61 7465 4964 203d 2022 7964  templateId = "yd
+00014880: 6964 3a63 7274 3a44 3943 3534 383a 3436  id:crt:D9C548:46
+00014890: 3561 3130 3763 2d37 6365 612d 3436 6533  5a107c-7cea-46e3
+000148a0: 2d39 6664 642d 3135 3131 3663 6239 3263  -9fdd-15116cb92c
+000148b0: 3430 220a 2020 2020 2320 4e6f 7465 3a20  40".    # Note: 
+000148c0: 6f6e 6c79 206f 6e65 206f 6620 2775 7365  only one of 'use
+000148d0: 7244 6174 6127 2f27 7573 6572 4461 7461  rData'/'userData
+000148e0: 4669 6c65 272f 2775 7365 7244 6174 6146  File'/'userDataF
+000148f0: 696c 6573 2720 7368 6f75 6c64 2062 6520  iles' should be 
+00014900: 7365 740a 2020 2020 7573 6572 4461 7461  set.    userData
+00014910: 203d 2022 220a 2020 2020 7573 6572 4461   = "".    userDa
+00014920: 7461 4669 6c65 203d 2022 6d79 7573 6572  taFile = "myuser
+00014930: 6461 7461 2e74 7874 220a 2020 2020 7573  data.txt".    us
+00014940: 6572 4461 7461 4669 6c65 7320 3d20 5b22  erDataFiles = ["
+00014950: 6d79 7573 6572 6461 7461 312e 7478 7422  myuserdata1.txt"
+00014960: 2c20 226d 7975 7365 7264 6174 6132 2e74  , "myuserdata2.t
+00014970: 7874 225d 0a20 2020 2077 6f72 6b65 7254  xt"].    workerT
+00014980: 6167 203d 2022 7461 672d 7b7b 7573 6572  ag = "tag-{{user
+00014990: 6e61 6d65 7d7d 220a 2020 2020 2320 5370  name}}".    # Sp
+000149a0: 6563 6966 7920 6569 7468 6572 2077 6f72  ecify either wor
+000149b0: 6b65 7273 5065 724e 6f64 6520 6f72 2077  kersPerNode or w
+000149c0: 6f72 6b65 7273 5065 7256 4350 550a 2020  orkersPerVCPU.  
+000149d0: 2020 776f 726b 6572 7350 6572 4e6f 6465    workersPerNode
+000149e0: 203d 2031 0a20 2020 2077 6f72 6b65 7273   = 1.    workers
+000149f0: 5065 7256 4350 5520 3d20 310a 2320 2020  PerVCPU = 1.#   
+00014a00: 776f 726b 6572 506f 6f6c 4461 7461 203d  workerPoolData =
+00014a10: 2022 776f 726b 6572 5f70 6f6f 6c2e 6a73   "worker_pool.js
+00014a20: 6f6e 220a 6060 600a 0a23 2320 576f 726b  on".```..## Work
+00014a30: 6572 2050 6f6f 6c20 5370 6563 6966 6963  er Pool Specific
+00014a40: 6174 696f 6e20 5573 696e 6720 4a53 4f4e  ation Using JSON
+00014a50: 2044 6f63 756d 656e 7473 0a0a 4974 2773   Documents..It's
+00014a60: 2061 6c73 6f20 706f 7373 6962 6c65 2074   also possible t
+00014a70: 6f20 6361 7074 7572 6520 6120 576f 726b  o capture a Work
+00014a80: 6572 2050 6f6f 6c20 6465 6669 6e69 7469  er Pool definiti
+00014a90: 6f6e 2061 7320 6120 4a53 4f4e 2064 6f63  on as a JSON doc
+00014aa0: 756d 656e 742e 2054 6865 204a 534f 4e20  ument. The JSON 
+00014ab0: 6669 6c65 6e61 6d65 2063 616e 2062 6520  filename can be 
+00014ac0: 7375 7070 6c69 6564 2065 6974 6865 7220  supplied either 
+00014ad0: 7573 696e 6720 7468 6520 636f 6d6d 616e  using the comman
+00014ae0: 6420 6c69 6e65 2077 6974 6820 7468 6520  d line with the 
+00014af0: 602d 2d77 6f72 6b65 722d 706f 6f6c 6020  `--worker-pool` 
+00014b00: 6f72 2060 2d70 6020 7061 7261 6d65 7465  or `-p` paramete
+00014b10: 7220 7769 7468 2060 7964 2d70 726f 7669  r with `yd-provi
+00014b20: 7369 6f6e 602c 206f 7220 6279 2070 6f70  sion`, or by pop
+00014b30: 756c 6174 696e 6720 7468 6520 6077 6f72  ulating the `wor
+00014b40: 6b65 7250 6f6f 6c44 6174 6160 2070 726f  kerPoolData` pro
+00014b50: 7065 7274 7920 696e 2074 6865 2054 4f4d  perty in the TOM
+00014b60: 4c20 636f 6e66 6967 7572 6174 696f 6e20  L configuration 
+00014b70: 6669 6c65 2077 6974 6820 7468 6520 4a53  file with the JS
+00014b80: 4f4e 2066 696c 656e 616d 652e 2043 6f6d  ON filename. Com
+00014b90: 6d61 6e64 206c 696e 6520 7370 6563 6966  mand line specif
+00014ba0: 6963 6174 696f 6e20 7461 6b65 7320 7072  ication takes pr
+00014bb0: 696f 7269 7479 206f 7665 7220 544f 4d4c  iority over TOML
+00014bc0: 2073 7065 6369 6669 6361 7469 6f6e 2e0a   specification..
+00014bd0: 0a54 6865 204a 534f 4e20 7370 6563 6966  .The JSON specif
+00014be0: 6963 6174 696f 6e20 616c 6c6f 7773 2074  ication allows t
+00014bf0: 6865 2063 7265 6174 696f 6e20 6f66 202a  he creation of *
+00014c00: 2a41 6476 616e 6365 6420 576f 726b 6572  *Advanced Worker
+00014c10: 2050 6f6f 6c73 2a2a 2c20 7769 7468 2064   Pools**, with d
+00014c20: 6966 6665 7265 6e74 206e 6f64 6520 7479  ifferent node ty
+00014c30: 7065 7320 616e 6420 7468 6520 6162 696c  pes and the abil
+00014c40: 6974 7920 746f 2073 7065 6369 6679 204e  ity to specify N
+00014c50: 6f64 6520 4163 7469 6f6e 732e 0a0a 5768  ode Actions...Wh
+00014c60: 656e 2075 7369 6e67 2061 204a 534f 4e20  en using a JSON 
+00014c70: 646f 6375 6d65 6e74 2074 6f20 7370 6563  document to spec
+00014c80: 6966 7920 7468 6520 576f 726b 6572 2050  ify the Worker P
+00014c90: 6f6f 6c2c 2074 6865 2073 6368 656d 6120  ool, the schema 
+00014ca0: 6f66 2074 6865 2064 6f63 756d 656e 7420  of the document 
+00014cb0: 6973 2069 6465 6e74 6963 616c 2074 6f20  is identical to 
+00014cc0: 7468 6174 2065 7870 6563 7465 6420 6279  that expected by
+00014cd0: 2074 6865 2059 656c 6c6f 7744 6f67 2052   the YellowDog R
+00014ce0: 4553 5420 4150 4920 666f 7220 576f 726b  EST API for Work
+00014cf0: 6572 2050 6f6f 6c20 5072 6f76 6973 696f  er Pool Provisio
+00014d00: 6e69 6e67 2e0a 0a23 2323 2057 6f72 6b65  ning...### Worke
+00014d10: 7220 506f 6f6c 204a 534f 4e20 4578 616d  r Pool JSON Exam
+00014d20: 706c 6573 0a0a 5468 6520 6578 616d 706c  ples..The exampl
+00014d30: 6520 6265 6c6f 7720 6973 206f 6620 6120  e below is of a 
+00014d40: 7369 6d70 6c65 204a 534f 4e20 7370 6563  simple JSON spec
+00014d50: 6966 6963 6174 696f 6e20 6f66 2061 2057  ification of a W
+00014d60: 6f72 6b65 7220 506f 6f6c 2077 6974 6820  orker Pool with 
+00014d70: 6f6e 6520 696e 6974 6961 6c20 6e6f 6465  one initial node
+00014d80: 2c20 576f 726b 6572 2050 6f6f 6c20 7368  , Worker Pool sh
+00014d90: 7574 646f 776e 2c20 6574 632e 0a0a 6060  utdown, etc...``
+00014da0: 606a 736f 6e0a 7b0a 2020 2272 6571 7569  `json.{.  "requi
+00014db0: 7265 6d65 6e74 5465 6d70 6c61 7465 5573  rementTemplateUs
+00014dc0: 6167 6522 3a20 7b0a 2020 2020 226d 6169  age": {.    "mai
+00014dd0: 6e74 6169 6e49 6e73 7461 6e63 6543 6f75  ntainInstanceCou
+00014de0: 6e74 223a 2066 616c 7365 2c0a 2020 2020  nt": false,.    
+00014df0: 2272 6571 7569 7265 6d65 6e74 4e61 6d65  "requirementName
+00014e00: 223a 2022 7770 5f70 7965 782d 7072 696d  ": "wp_pyex-prim
+00014e10: 6573 5f32 3330 3131 332d 3136 3135 3238  es_230113-161528
+00014e20: 2d64 6130 222c 0a20 2020 2022 7265 7175  -da0",.    "requ
+00014e30: 6972 656d 656e 744e 616d 6573 7061 6365  irementNamespace
+00014e40: 223a 2022 7079 6578 616d 706c 6573 222c  ": "pyexamples",
+00014e50: 0a20 2020 2022 7265 7175 6972 656d 656e  .    "requiremen
+00014e60: 7454 6167 223a 2022 7079 6578 2d70 7269  tTag": "pyex-pri
+00014e70: 6d65 7322 2c0a 2020 2020 2274 6172 6765  mes",.    "targe
+00014e80: 7449 6e73 7461 6e63 6543 6f75 6e74 223a  tInstanceCount":
+00014e90: 2031 2c0a 2020 2020 2274 656d 706c 6174   1,.    "templat
+00014ea0: 6549 6422 3a20 2279 6469 643a 6372 743a  eId": "ydid:crt:
+00014eb0: 4439 4335 3438 3a34 3635 6131 3037 632d  D9C548:465a107c-
+00014ec0: 3763 6561 2d34 3665 332d 3966 6464 2d31  7cea-46e3-9fdd-1
+00014ed0: 3531 3136 6362 3932 6334 3022 0a20 207d  5116cb92c40".  }
+00014ee0: 2c0a 2020 2270 726f 7669 7369 6f6e 6564  ,.  "provisioned
+00014ef0: 5072 6f70 6572 7469 6573 223a 207b 0a20  Properties": {. 
+00014f00: 2020 2022 6964 6c65 4e6f 6465 5368 7574     "idleNodeShut
+00014f10: 646f 776e 223a 207b 2265 6e61 626c 6564  down": {"enabled
+00014f20: 223a 2074 7275 652c 2022 7469 6d65 6f75  ": true, "timeou
+00014f30: 7422 3a20 2250 5431 304d 227d 2c0a 2020  t": "PT10M"},.  
+00014f40: 2020 2269 646c 6550 6f6f 6c53 6875 7464    "idlePoolShutd
+00014f50: 6f77 6e22 3a20 7b22 656e 6162 6c65 6422  own": {"enabled"
+00014f60: 3a20 7472 7565 2c20 2274 696d 656f 7574  : true, "timeout
+00014f70: 223a 2022 5054 3148 227d 2c0a 2020 2020  ": "PT1H"},.    
+00014f80: 2263 7265 6174 654e 6f64 6557 6f72 6b65  "createNodeWorke
+00014f90: 7273 223a 207b 2274 6172 6765 7443 6f75  rs": {"targetCou
+00014fa0: 6e74 223a 2031 2c20 2274 6172 6765 7454  nt": 1, "targetT
+00014fb0: 7970 6522 3a20 2250 4552 5f56 4350 5522  ype": "PER_VCPU"
+00014fc0: 7d2c 0a20 2020 2022 6d61 784e 6f64 6573  },.    "maxNodes
+00014fd0: 223a 2035 2c0a 2020 2020 226d 696e 4e6f  ": 5,.    "minNo
+00014fe0: 6465 7322 3a20 302c 0a20 2020 2022 6e6f  des": 0,.    "no
+00014ff0: 6465 426f 6f74 5469 6d65 6f75 7422 3a20  deBootTimeout": 
+00015000: 2250 5435 4d22 2c0a 2020 2020 226e 6f64  "PT5M",.    "nod
+00015010: 6549 646c 6547 7261 6365 5065 7269 6f64  eIdleGracePeriod
+00015020: 223a 2022 5054 334d 222c 0a20 2020 2022  ": "PT3M",.    "
+00015030: 6e6f 6465 4964 6c65 5469 6d65 4c69 6d69  nodeIdleTimeLimi
+00015040: 7422 3a20 2250 5433 4d22 2c0a 2020 2020  t": "PT3M",.    
+00015050: 2277 6f72 6b65 7254 6167 223a 2022 7079  "workerTag": "py
+00015060: 6578 2d62 6173 682d 646f 636b 6572 220a  ex-bash-docker".
+00015070: 2020 7d0a 7d0a 6060 600a 0a54 6865 206e    }.}.```..The n
+00015080: 6578 7420 6578 616d 706c 6520 6973 206f  ext example is o
+00015090: 6620 6120 7265 6c61 7469 7665 6c79 2072  f a relatively r
+000150a0: 6963 6820 4a53 4f4e 2073 7065 6369 6669  ich JSON specifi
+000150b0: 6361 7469 6f6e 206f 6620 616e 2041 6476  cation of an Adv
+000150c0: 616e 6365 6420 576f 726b 6572 2050 6f6f  anced Worker Poo
+000150d0: 6c2c 2066 726f 6d20 6f6e 6520 6f66 2074  l, from one of t
+000150e0: 6865 2059 656c 6c6f 7744 6f67 2064 656d  he YellowDog dem
+000150f0: 6f73 2e20 4974 2069 6e63 6c75 6465 7320  os. It includes 
+00015100: 6e6f 6465 2073 7065 6369 616c 6973 6174  node specialisat
+00015110: 696f 6e2c 2061 6e64 2061 6374 696f 6e20  ion, and action 
+00015120: 6772 6f75 7073 2074 6861 7420 7265 7370  groups that resp
+00015130: 6f6e 6420 746f 2074 6865 2060 5354 4152  ond to the `STAR
+00015140: 5455 505f 4e4f 4445 535f 4144 4445 4460  TUP_NODES_ADDED`
+00015150: 2061 6e64 2060 4e4f 4445 535f 4144 4445   and `NODES_ADDE
+00015160: 4460 2065 7665 6e74 7320 746f 2064 7269  D` events to dri
+00015170: 7665 202a 2a4e 6f64 6520 4163 7469 6f6e  ve **Node Action
+00015180: 732a 2a2e 0a0a 6060 606a 736f 6e0a 7b0a  s**...```json.{.
+00015190: 2020 2272 6571 7569 7265 6d65 6e74 5465    "requirementTe
+000151a0: 6d70 6c61 7465 5573 6167 6522 3a20 7b0a  mplateUsage": {.
+000151b0: 2020 2020 226d 6169 6e74 6169 6e49 6e73      "maintainIns
+000151c0: 7461 6e63 6543 6f75 6e74 223a 2066 616c  tanceCount": fal
+000151d0: 7365 2c0a 2020 2020 2274 6172 6765 7449  se,.    "targetI
+000151e0: 6e73 7461 6e63 6543 6f75 6e74 223a 2036  nstanceCount": 6
+000151f0: 2c0a 2020 2020 2274 656d 706c 6174 6549  ,.    "templateI
+00015200: 6422 3a20 2279 6469 643a 6372 743a 4439  d": "ydid:crt:D9
+00015210: 4335 3438 3a61 3765 6461 3238 372d 6639  C548:a7eda287-f9
+00015220: 6436 2d34 6263 382d 6232 6463 2d34 3535  d6-4bc8-b2dc-455
+00015230: 3334 3430 3537 3235 3722 2c0a 2020 2020  344057257",.    
+00015240: 2272 6571 7569 7265 6d65 6e74 4e61 6d65  "requirementName
+00015250: 223a 2022 7770 5f70 7965 782d 736c 7572  ": "wp_pyex-slur
+00015260: 6d5f 3233 3031 3133 2d31 3635 3631 352d  m_230113-165615-
+00015270: 3262 3722 2c0a 2020 2020 2272 6571 7569  2b7",.    "requi
+00015280: 7265 6d65 6e74 4e61 6d65 7370 6163 6522  rementNamespace"
+00015290: 3a20 2270 7965 7861 6d70 6c65 7322 2c0a  : "pyexamples",.
+000152a0: 2020 2020 2272 6571 7569 7265 6d65 6e74      "requirement
+000152b0: 5461 6722 3a20 2270 7965 782d 736c 7572  Tag": "pyex-slur
+000152c0: 6d22 0a20 207d 2c0a 2020 2270 726f 7669  m".  },.  "provi
+000152d0: 7369 6f6e 6564 5072 6f70 6572 7469 6573  sionedProperties
+000152e0: 223a 207b 0a20 2020 2022 6372 6561 7465  ": {.    "create
+000152f0: 4e6f 6465 576f 726b 6572 7322 3a20 7b22  NodeWorkers": {"
+00015300: 7461 7267 6574 436f 756e 7422 3a20 302c  targetCount": 0,
+00015310: 2022 7461 7267 6574 5479 7065 223a 2022   "targetType": "
+00015320: 5045 525f 4e4f 4445 227d 2c0a 2020 2020  PER_NODE"},.    
+00015330: 226e 6f64 6543 6f6e 6669 6775 7261 7469  "nodeConfigurati
+00015340: 6f6e 223a 207b 0a20 2020 2020 2022 6e6f  on": {.      "no
+00015350: 6465 5479 7065 7322 3a20 5b0a 2020 2020  deTypes": [.    
+00015360: 2020 2020 7b22 6e61 6d65 223a 2022 736c      {"name": "sl
+00015370: 7572 6d63 746c 6422 2c20 2263 6f75 6e74  urmctld", "count
+00015380: 223a 2031 7d2c 0a20 2020 2020 2020 207b  ": 1},.        {
+00015390: 226e 616d 6522 3a20 2273 6c75 726d 6422  "name": "slurmd"
+000153a0: 2c20 226d 696e 223a 2035 2c20 2273 6c6f  , "min": 5, "slo
+000153b0: 744e 756d 6265 7269 6e67 223a 2022 5245  tNumbering": "RE
+000153c0: 5553 4142 4c45 227d 0a20 2020 2020 205d  USABLE"}.      ]
+000153d0: 2c0a 2020 2020 2020 226e 6f64 6545 7665  ,.      "nodeEve
+000153e0: 6e74 7322 3a20 7b0a 2020 2020 2020 2020  nts": {.        
+000153f0: 2253 5441 5254 5550 5f4e 4f44 4553 5f41  "STARTUP_NODES_A
+00015400: 4444 4544 223a 205b 0a20 2020 2020 2020  DDED": [.       
+00015410: 2020 207b 0a20 2020 2020 2020 2020 2020     {.           
+00015420: 2022 6163 7469 6f6e 7322 3a20 5b0a 2020   "actions": [.  
+00015430: 2020 2020 2020 2020 2020 2020 7b0a 2020              {.  
+00015440: 2020 2020 2020 2020 2020 2020 2020 2261                "a
+00015450: 6374 696f 6e22 3a20 2257 5249 5445 5f46  ction": "WRITE_F
+00015460: 494c 4522 2c0a 2020 2020 2020 2020 2020  ILE",.          
+00015470: 2020 2020 2020 2270 6174 6822 3a20 226e        "path": "n
+00015480: 6f64 6573 2e6a 736f 6e22 2c0a 2020 2020  odes.json",.    
+00015490: 2020 2020 2020 2020 2020 2020 2263 6f6e              "con
+000154a0: 7465 6e74 223a 2022 7b5c 6e20 205c 226e  tent": "{\n  \"n
+000154b0: 6f64 6573 5c22 3a20 5b5c 6e7b 7b23 6f74  odes\": [\n{{#ot
+000154c0: 6865 724e 6f64 6573 7d7d 5c6e 2020 2020  herNodes}}\n    
+000154d0: 7b5c 6e20 2020 2020 205c 226e 616d 655c  {\n      \"name\
+000154e0: 223a 205c 2273 6c75 726d 647b 7b64 6574  ": \"slurmd{{det
+000154f0: 6169 6c73 2e6e 6f64 6553 6c6f 747d 7d5c  ails.nodeSlot}}\
+00015500: 222c 5c6e 2020 2020 2020 5c22 6970 5c22  ",\n      \"ip\"
+00015510: 3a20 5c22 7b7b 6465 7461 696c 732e 7072  : \"{{details.pr
+00015520: 6976 6174 6549 7041 6464 7265 7373 7d7d  ivateIpAddress}}
+00015530: 5c22 5c6e 2020 2020 7d7b 7b5e 2d6c 6173  \"\n    }{{^-las
+00015540: 747d 7d2c 7b7b 2f2d 6c61 7374 7d7d 5c6e  t}},{{/-last}}\n
+00015550: 7b7b 2f6f 7468 6572 4e6f 6465 737d 7d5c  {{/otherNodes}}\
+00015560: 6e20 205d 5c6e 7d22 2c0a 2020 2020 2020  n  ]\n}",.      
+00015570: 2020 2020 2020 2020 2020 226e 6f64 6554            "nodeT
+00015580: 7970 6573 223a 205b 2273 6c75 726d 6374  ypes": ["slurmct
+00015590: 6c64 225d 0a20 2020 2020 2020 2020 2020  ld"].           
+000155a0: 2020 207d 2c0a 2020 2020 2020 2020 2020     },.          
+000155b0: 2020 2020 7b0a 2020 2020 2020 2020 2020      {.          
+000155c0: 2020 2020 2020 2261 6374 696f 6e22 3a20        "action": 
+000155d0: 2252 554e 5f43 4f4d 4d41 4e44 222c 0a20  "RUN_COMMAND",. 
+000155e0: 2020 2020 2020 2020 2020 2020 2020 2022                 "
+000155f0: 7061 7468 223a 2022 7374 6172 745f 7369  path": "start_si
+00015600: 6d70 6c65 5f73 6c75 726d 6374 6c64 222c  mple_slurmctld",
+00015610: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
+00015620: 2022 6172 6775 6d65 6e74 7322 3a20 5b22   "arguments": ["
+00015630: 6e6f 6465 732e 6a73 6f6e 225d 2c0a 2020  nodes.json"],.  
+00015640: 2020 2020 2020 2020 2020 2020 2020 2265                "e
+00015650: 6e76 6972 6f6e 6d65 6e74 223a 207b 2245  nvironment": {"E
+00015660: 5841 4d50 4c45 223a 2022 464f 4f22 7d2c  XAMPLE": "FOO"},
+00015670: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
+00015680: 2022 6e6f 6465 5479 7065 7322 3a20 5b22   "nodeTypes": ["
+00015690: 736c 7572 6d63 746c 6422 5d0a 2020 2020  slurmctld"].    
+000156a0: 2020 2020 2020 2020 2020 7d0a 2020 2020            }.    
+000156b0: 2020 2020 2020 2020 5d0a 2020 2020 2020          ].      
+000156c0: 2020 2020 7d2c 0a20 2020 2020 2020 2020      },.         
+000156d0: 207b 0a20 2020 2020 2020 2020 2020 2022   {.            "
+000156e0: 6163 7469 6f6e 7322 3a20 5b0a 2020 2020  actions": [.    
+000156f0: 2020 2020 2020 2020 2020 7b0a 2020 2020            {.    
+00015700: 2020 2020 2020 2020 2020 2020 2261 6374              "act
+00015710: 696f 6e22 3a20 2252 554e 5f43 4f4d 4d41  ion": "RUN_COMMA
+00015720: 4e44 222c 0a20 2020 2020 2020 2020 2020  ND",.           
+00015730: 2020 2020 2022 7061 7468 223a 2022 7374       "path": "st
+00015740: 6172 745f 7369 6d70 6c65 5f73 6c75 726d  art_simple_slurm
+00015750: 6422 2c0a 2020 2020 2020 2020 2020 2020  d",.            
+00015760: 2020 2020 2261 7267 756d 656e 7473 223a      "arguments":
+00015770: 205b 227b 7b6e 6f64 6573 4279 5479 7065   ["{{nodesByType
+00015780: 2e73 6c75 726d 6374 6c64 2e30 2e64 6574  .slurmctld.0.det
+00015790: 6169 6c73 2e70 7269 7661 7465 4970 4164  ails.privateIpAd
+000157a0: 6472 6573 737d 7d22 2c20 227b 7b6e 6f64  dress}}", "{{nod
+000157b0: 652e 6465 7461 696c 732e 6e6f 6465 536c  e.details.nodeSl
+000157c0: 6f74 7d7d 225d 2c0a 2020 2020 2020 2020  ot}}"],.        
+000157d0: 2020 2020 2020 2020 226e 6f64 6554 7970          "nodeTyp
+000157e0: 6573 223a 205b 2273 6c75 726d 6422 5d0a  es": ["slurmd"].
+000157f0: 2020 2020 2020 2020 2020 2020 2020 7d0a                }.
+00015800: 2020 2020 2020 2020 2020 2020 5d0a 2020              ].  
+00015810: 2020 2020 2020 2020 7d2c 0a20 2020 2020          },.     
+00015820: 2020 2020 207b 0a20 2020 2020 2020 2020       {.         
+00015830: 2020 2022 6163 7469 6f6e 7322 3a20 5b0a     "actions": [.
+00015840: 2020 2020 2020 2020 2020 2020 2020 7b0a                {.
+00015850: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00015860: 2261 6374 696f 6e22 3a20 2243 5245 4154  "action": "CREAT
+00015870: 455f 574f 524b 4552 5322 2c0a 2020 2020  E_WORKERS",.    
+00015880: 2020 2020 2020 2020 2020 2020 2274 6f74              "tot
+00015890: 616c 576f 726b 6572 7322 3a20 312c 0a20  alWorkers": 1,. 
+000158a0: 2020 2020 2020 2020 2020 2020 2020 2022                 "
+000158b0: 6e6f 6465 5479 7065 7322 3a20 5b22 736c  nodeTypes": ["sl
+000158c0: 7572 6d63 746c 6422 5d0a 2020 2020 2020  urmctld"].      
+000158d0: 2020 2020 2020 2020 7d0a 2020 2020 2020          }.      
+000158e0: 2020 2020 2020 5d0a 2020 2020 2020 2020        ].        
+000158f0: 2020 7d0a 2020 2020 2020 2020 5d2c 0a20    }.        ],. 
+00015900: 2020 2020 2020 2022 4e4f 4445 535f 4144         "NODES_AD
+00015910: 4445 4422 3a20 5b0a 2020 2020 2020 2020  DED": [.        
+00015920: 2020 7b0a 2020 2020 2020 2020 2020 2020    {.            
+00015930: 2261 6374 696f 6e73 223a 205b 0a20 2020  "actions": [.   
+00015940: 2020 2020 2020 2020 2020 207b 0a20 2020             {.   
+00015950: 2020 2020 2020 2020 2020 2020 2022 6163               "ac
+00015960: 7469 6f6e 223a 2022 5752 4954 455f 4649  tion": "WRITE_FI
+00015970: 4c45 222c 0a20 2020 2020 2020 2020 2020  LE",.           
+00015980: 2020 2020 2022 7061 7468 223a 2022 6e6f       "path": "no
+00015990: 6465 732e 6a73 6f6e 222c 0a20 2020 2020  des.json",.     
+000159a0: 2020 2020 2020 2020 2020 2022 636f 6e74             "cont
+000159b0: 656e 7422 3a20 227b 5c6e 2020 5c22 6e6f  ent": "{\n  \"no
+000159c0: 6465 735c 223a 205b 5c6e 7b7b 2366 696c  des\": [\n{{#fil
+000159d0: 7465 7265 644e 6f64 6573 7d7d 5c6e 2020  teredNodes}}\n  
+000159e0: 2020 7b5c 6e20 2020 2020 205c 226e 616d    {\n      \"nam
+000159f0: 655c 223a 205c 2273 6c75 726d 647b 7b64  e\": \"slurmd{{d
+00015a00: 6574 6169 6c73 2e6e 6f64 6553 6c6f 747d  etails.nodeSlot}
+00015a10: 7d5c 222c 5c6e 2020 2020 2020 5c22 6970  }\",\n      \"ip
+00015a20: 5c22 3a20 5c22 7b7b 6465 7461 696c 732e  \": \"{{details.
+00015a30: 7072 6976 6174 6549 7041 6464 7265 7373  privateIpAddress
+00015a40: 7d7d 5c22 5c6e 2020 2020 7d7b 7b5e 2d6c  }}\"\n    }{{^-l
+00015a50: 6173 747d 7d2c 7b7b 2f2d 6c61 7374 7d7d  ast}},{{/-last}}
+00015a60: 5c6e 7b7b 2f66 696c 7465 7265 644e 6f64  \n{{/filteredNod
+00015a70: 6573 7d7d 5c6e 2020 5d5c 6e7d 222c 0a20  es}}\n  ]\n}",. 
+00015a80: 2020 2020 2020 2020 2020 2020 2020 2022                 "
+00015a90: 6e6f 6465 5479 7065 7322 3a20 5b22 736c  nodeTypes": ["sl
+00015aa0: 7572 6d63 746c 6422 5d0a 2020 2020 2020  urmctld"].      
+00015ab0: 2020 2020 2020 2020 7d2c 0a20 2020 2020          },.     
+00015ac0: 2020 2020 2020 2020 207b 0a20 2020 2020           {.     
+00015ad0: 2020 2020 2020 2020 2020 2022 6163 7469             "acti
+00015ae0: 6f6e 223a 2022 5255 4e5f 434f 4d4d 414e  on": "RUN_COMMAN
+00015af0: 4422 2c0a 2020 2020 2020 2020 2020 2020  D",.            
+00015b00: 2020 2020 2270 6174 6822 3a20 2261 6464      "path": "add
+00015b10: 5f6e 6f64 6573 222c 0a20 2020 2020 2020  _nodes",.       
+00015b20: 2020 2020 2020 2020 2022 6172 6775 6d65           "argume
+00015b30: 6e74 7322 3a20 5b22 6e6f 6465 732e 6a73  nts": ["nodes.js
+00015b40: 6f6e 225d 2c0a 2020 2020 2020 2020 2020  on"],.          
+00015b50: 2020 2020 2020 226e 6f64 6554 7970 6573        "nodeTypes
+00015b60: 223a 205b 2273 6c75 726d 6374 6c64 225d  ": ["slurmctld"]
+00015b70: 0a20 2020 2020 2020 2020 2020 2020 207d  .              }
+00015b80: 0a20 2020 2020 2020 2020 2020 205d 0a20  .            ]. 
+00015b90: 2020 2020 2020 2020 207d 2c0a 2020 2020           },.    
+00015ba0: 2020 2020 2020 7b0a 2020 2020 2020 2020        {.        
+00015bb0: 2020 2020 2261 6374 696f 6e73 223a 205b      "actions": [
+00015bc0: 0a20 2020 2020 2020 2020 2020 2020 207b  .              {
+00015bd0: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
+00015be0: 2022 6163 7469 6f6e 223a 2022 5255 4e5f   "action": "RUN_
+00015bf0: 434f 4d4d 414e 4422 2c0a 2020 2020 2020  COMMAND",.      
+00015c00: 2020 2020 2020 2020 2020 2270 6174 6822            "path"
+00015c10: 3a20 2273 7461 7274 5f73 696d 706c 655f  : "start_simple_
+00015c20: 736c 7572 6d64 222c 0a20 2020 2020 2020  slurmd",.       
+00015c30: 2020 2020 2020 2020 2022 6172 6775 6d65           "argume
+00015c40: 6e74 7322 3a20 5b22 7b7b 6e6f 6465 7342  nts": ["{{nodesB
+00015c50: 7954 7970 652e 736c 7572 6d63 746c 642e  yType.slurmctld.
+00015c60: 302e 6465 7461 696c 732e 7072 6976 6174  0.details.privat
+00015c70: 6549 7041 6464 7265 7373 7d7d 222c 2022  eIpAddress}}", "
+00015c80: 7b7b 6e6f 6465 2e64 6574 6169 6c73 2e6e  {{node.details.n
+00015c90: 6f64 6553 6c6f 747d 7d22 5d2c 0a20 2020  odeSlot}}"],.   
+00015ca0: 2020 2020 2020 2020 2020 2020 2022 6e6f               "no
+00015cb0: 6465 4964 4669 6c74 6572 223a 2022 4556  deIdFilter": "EV
+00015cc0: 454e 5422 2c0a 2020 2020 2020 2020 2020  ENT",.          
+00015cd0: 2020 2020 2020 226e 6f64 6554 7970 6573        "nodeTypes
+00015ce0: 223a 205b 2273 6c75 726d 6422 5d0a 2020  ": ["slurmd"].  
+00015cf0: 2020 2020 2020 2020 2020 2020 7d0a 2020              }.  
+00015d00: 2020 2020 2020 2020 2020 5d0a 2020 2020            ].    
+00015d10: 2020 2020 2020 7d0a 2020 2020 2020 2020        }.        
+00015d20: 5d0a 2020 2020 2020 7d0a 2020 2020 7d2c  ].      }.    },
+00015d30: 0a20 2020 2022 776f 726b 6572 5461 6722  .    "workerTag"
+00015d40: 3a20 2270 7965 782d 736c 7572 6d2d 636c  : "pyex-slurm-cl
+00015d50: 7573 7465 7222 0a20 207d 0a7d 0a60 6060  uster".  }.}.```
+00015d60: 0a0a 2323 2320 544f 4d4c 2050 726f 7065  ..### TOML Prope
+00015d70: 7274 6965 7320 496e 6865 7269 7465 6420  rties Inherited 
+00015d80: 6279 2057 6f72 6b65 7220 506f 6f6c 204a  by Worker Pool J
+00015d90: 534f 4e20 5370 6563 6966 6963 6174 696f  SON Specificatio
+00015da0: 6e73 0a0a 5768 656e 2061 204a 534f 4e20  ns..When a JSON 
+00015db0: 576f 726b 6572 2050 6f6f 6c20 7370 6563  Worker Pool spec
+00015dc0: 6966 6963 6174 696f 6e20 6973 2075 7365  ification is use
+00015dd0: 642c 2074 6865 2066 6f6c 6c6f 7769 6e67  d, the following
+00015de0: 2070 726f 7065 7274 6965 7320 6672 6f6d   properties from
+00015df0: 2074 6865 2060 636f 6e66 6967 2e74 6f6d   the `config.tom
+00015e00: 6c60 2066 696c 6520 7769 6c6c 2062 6520  l` file will be 
+00015e10: 696e 6865 7269 7465 6420 6966 2074 6865  inherited if the
+00015e20: 2076 616c 7565 2069 7320 6162 7365 6e74   value is absent
+00015e30: 2069 6e20 7468 6520 4a53 4f4e 2066 696c   in the JSON fil
+00015e40: 653a 0a0a 2a2a 5072 6f70 6572 7469 6573  e:..**Properties
+00015e50: 2049 6e68 6572 6974 6564 2077 6974 6869   Inherited withi
+00015e60: 6e20 7468 6520 6072 6571 7569 7265 6d65  n the `requireme
+00015e70: 6e74 5465 6d70 6c61 7465 5573 6167 6560  ntTemplateUsage`
+00015e80: 2070 726f 7065 7274 792a 2a0a 0a2d 2060   property**..- `
+00015e90: 696d 6167 6573 4964 600a 2d20 6069 6e73  imagesId`.- `ins
+00015ea0: 7461 6e63 6554 6167 7360 0a2d 2060 7265  tanceTags`.- `re
+00015eb0: 7175 6972 656d 656e 744e 616d 6560 3a20  quirementName`: 
+00015ec0: 6465 7269 7665 6420 6672 6f6d 2074 6865  derived from the
+00015ed0: 2060 6e61 6d65 6020 7072 6f70 6572 7479   `name` property
+00015ee0: 2069 6e20 7468 6520 6054 4f4d 4c60 2063   in the `TOML` c
+00015ef0: 6f6e 6669 6775 7261 7469 6f6e 2e20 2854  onfiguration. (T
+00015f00: 6865 206e 616d 6520 7769 6c6c 2062 6520  he name will be 
+00015f10: 6765 6e65 7261 7465 6420 6175 746f 6d61  generated automa
+00015f20: 7469 6361 6c6c 7920 6966 206e 6f74 2073  tically if not s
+00015f30: 7570 706c 6965 6420 696e 2065 6974 6865  upplied in eithe
+00015f40: 7220 7468 6520 544f 4d4c 2066 696c 6520  r the TOML file 
+00015f50: 6f72 2074 6865 204a 534f 4e20 7370 6563  or the JSON spec
+00015f60: 6966 6963 6174 696f 6e2e 290a 2d20 6072  ification.).- `r
+00015f70: 6571 7569 7265 6d65 6e74 4e61 6d65 7370  equirementNamesp
+00015f80: 6163 6560 3a20 6465 7269 7665 6420 6672  ace`: derived fr
+00015f90: 6f6d 2074 6865 2060 6e61 6d65 7370 6163  om the `namespac
+00015fa0: 6560 2070 726f 7065 7274 7920 696e 2074  e` property in t
+00015fb0: 6865 2060 544f 4d4c 6020 636f 6e66 6967  he `TOML` config
+00015fc0: 7572 6174 696f 6e0a 2d20 6072 6571 7569  uration.- `requi
+00015fd0: 7265 6d65 6e74 5461 6760 3a20 3a20 6465  rementTag`: : de
+00015fe0: 7269 7665 6420 6672 6f6d 2074 6865 2060  rived from the `
+00015ff0: 7461 6760 2070 726f 7065 7274 7920 696e  tag` property in
+00016000: 2074 6865 2060 544f 4d4c 6020 636f 6e66   the `TOML` conf
+00016010: 6967 7572 6174 696f 6e0a 2d20 6074 6172  iguration.- `tar
+00016020: 6765 7449 6e73 7461 6e63 6543 6f75 6e74  getInstanceCount
+00016030: 600a 2d20 6074 656d 706c 6174 6549 6460  `.- `templateId`
+00016040: 0a2d 2060 7573 6572 4461 7461 600a 2d20  .- `userData`.- 
+00016050: 6075 7365 7244 6174 6146 696c 6560 0a2d  `userDataFile`.-
+00016060: 2060 7573 6572 4461 7461 4669 6c65 7360   `userDataFiles`
+00016070: 0a0a 2a2a 5072 6f70 6572 7469 6573 2049  ..**Properties I
+00016080: 6e68 6572 6974 6564 2077 6974 6869 6e20  nherited within 
+00016090: 7468 6520 6070 726f 7669 7369 6f6e 6564  the `provisioned
+000160a0: 5072 6f70 6572 7469 6573 6020 5072 6f70  Properties` Prop
+000160b0: 6572 7479 2a2a 0a0a 2d20 6069 646c 654e  erty**..- `idleN
+000160c0: 6f64 6553 6875 7464 6f77 6e45 6e61 626c  odeShutdownEnabl
+000160d0: 6564 600a 2d20 6069 646c 654e 6f64 6553  ed`.- `idleNodeS
+000160e0: 6875 7464 6f77 6e54 696d 656f 7574 600a  hutdownTimeout`.
+000160f0: 2d20 6069 646c 6550 6f6f 6c53 6875 7464  - `idlePoolShutd
+00016100: 6f77 6e45 6e61 626c 6564 600a 2d20 6069  ownEnabled`.- `i
+00016110: 646c 6550 6f6f 6c53 6875 7464 6f77 6e54  dlePoolShutdownT
+00016120: 696d 656f 7574 600a 2d20 606e 6f64 6542  imeout`.- `nodeB
+00016130: 6f6f 7454 696d 656f 7574 600a 2d20 6077  ootTimeout`.- `w
+00016140: 6f72 6b65 7254 6167 600a 0a23 2320 5661  orkerTag`..## Va
+00016150: 7269 6162 6c65 2053 7562 7374 6974 7574  riable Substitut
+00016160: 696f 6e73 2069 6e20 576f 726b 6572 2050  ions in Worker P
+00016170: 6f6f 6c20 5072 6f70 6572 7469 6573 0a0a  ool Properties..
+00016180: 5661 7269 6162 6c65 2073 7562 7374 6974  Variable substit
+00016190: 7574 696f 6e73 2063 616e 2062 6520 7573  utions can be us
+000161a0: 6564 2077 6974 6869 6e20 616e 7920 7072  ed within any pr
+000161b0: 6f70 6572 7479 2076 616c 7565 2069 6e20  operty value in 
+000161c0: 544f 4d4c 2063 6f6e 6669 6775 7261 7469  TOML configurati
+000161d0: 6f6e 2066 696c 6573 206f 7220 576f 726b  on files or Work
+000161e0: 6572 2050 6f6f 6c20 4a53 4f4e 2066 696c  er Pool JSON fil
+000161f0: 6573 2e20 5365 6520 7468 6520 6465 7363  es. See the desc
+00016200: 7269 7074 696f 6e20 5b61 626f 7665 5d28  ription [above](
+00016210: 2376 6172 6961 626c 652d 7375 6273 7469  #variable-substi
+00016220: 7475 7469 6f6e 7329 2066 6f72 206d 6f72  tutions) for mor
+00016230: 6520 6465 7461 696c 7320 6f6e 2076 6172  e details on var
+00016240: 6961 626c 6520 7375 6273 7469 7475 7469  iable substituti
+00016250: 6f6e 732e 2054 6869 7320 6973 2061 2070  ons. This is a p
+00016260: 6f77 6572 6675 6c20 6665 6174 7572 6520  owerful feature 
+00016270: 7468 6174 2061 6c6c 6f77 7320 576f 726b  that allows Work
+00016280: 6572 2050 6f6f 6c73 2074 6f20 6265 2070  er Pools to be p
+00016290: 6172 616d 6574 6572 6973 6564 2062 7920  arameterised by 
+000162a0: 7375 7070 6c79 696e 6720 7661 6c75 6573  supplying values
+000162b0: 206f 6e20 7468 6520 636f 6d6d 616e 6420   on the command 
+000162c0: 6c69 6e65 2c20 7669 6120 656e 7669 726f  line, via enviro
+000162d0: 6e6d 656e 7420 7661 7269 6162 6c65 732c  nment variables,
+000162e0: 206f 7220 7669 6120 7468 6520 544f 4d4c   or via the TOML
+000162f0: 2066 696c 652e 0a0a 416e 2069 6d70 6f72   file...An impor
+00016300: 7461 6e74 2064 6973 7469 6e63 7469 6f6e  tant distinction
+00016310: 202a 2a6f 6e6c 792a 2a20 7768 656e 2075   **only** when u
+00016320: 7369 6e67 2076 6172 6961 626c 6520 7375  sing variable su
+00016330: 6273 7469 7475 7469 6f6e 7320 7769 7468  bstitutions with
+00016340: 696e 2057 6f72 6b65 7220 506f 6f6c 204a  in Worker Pool J
+00016350: 534f 4e20 646f 6375 6d65 6e74 7320 6973  SON documents is
+00016360: 2074 6861 7420 6561 6368 2064 6972 6563   that each direc
+00016370: 7469 7665 202a 2a6d 7573 7420 6265 2070  tive **must be p
+00016380: 7265 6365 6465 6420 6279 2061 2060 5f5f  receded by a `__
+00016390: 6020 2864 6f75 626c 6520 756e 6465 7273  ` (double unders
+000163a0: 636f 7265 292a 2a20 746f 2064 6973 616d  core)** to disam
+000163b0: 6269 6775 6174 6520 6974 2066 726f 6d20  biguate it from 
+000163c0: 7661 7269 6162 6c65 2073 7562 7374 6974  variable substit
+000163d0: 7574 696f 6e73 2074 6861 7420 6172 6520  utions that are 
+000163e0: 746f 2062 6520 7061 7373 6564 2064 6972  to be passed dir
+000163f0: 6563 746c 7920 746f 2074 6865 2041 5049  ectly to the API
+00016400: 2e20 466f 7220 6578 616d 706c 652c 2075  . For example, u
+00016410: 7365 3a20 605f 5f7b 7b75 7365 726e 616d  se: `__{{usernam
+00016420: 657d 7d60 2074 6f20 6170 706c 7920 6120  e}}` to apply a 
+00016430: 7375 6273 7469 7475 7469 6f6e 2066 6f72  substitution for
+00016440: 2074 6865 2060 7573 6572 6e61 6d65 6020   the `username` 
+00016450: 6465 6661 756c 7420 7375 6273 7469 7475  default substitu
+00016460: 7469 6f6e 2e0a 0a23 2320 4472 792d 5275  tion...## Dry-Ru
+00016470: 6e6e 696e 6720 576f 726b 6572 2050 6f6f  nning Worker Poo
+00016480: 6c20 5072 6f76 6973 696f 6e69 6e67 0a0a  l Provisioning..
+00016490: 546f 2065 7861 6d69 6e65 2074 6865 204a  To examine the J
+000164a0: 534f 4e20 7468 6174 2077 696c 6c20 6163  SON that will ac
+000164b0: 7475 616c 6c79 2062 6520 7365 6e74 2074  tually be sent t
+000164c0: 6f20 7468 6520 5965 6c6c 6f77 446f 6720  o the YellowDog 
+000164d0: 4150 4920 6166 7465 7220 616c 6c20 7072  API after all pr
+000164e0: 6f63 6573 7369 6e67 2c20 7573 6520 7468  ocessing, use th
+000164f0: 6520 602d 2d64 7279 2d72 756e 6020 636f  e `--dry-run` co
+00016500: 6d6d 616e 6420 6c69 6e65 206f 7074 696f  mmand line optio
+00016510: 6e20 7768 656e 2072 756e 6e69 6e67 2060  n when running `
+00016520: 7964 2d70 726f 7669 7369 6f6e 602e 2054  yd-provision`. T
+00016530: 6869 7320 7769 6c6c 2070 7269 6e74 2074  his will print t
+00016540: 6865 204a 534f 4e20 7370 6563 6966 6963  he JSON specific
+00016550: 6174 696f 6e20 666f 7220 7468 6520 576f  ation for the Wo
+00016560: 726b 6572 2050 6f6f 6c2e 204e 6f74 6869  rker Pool. Nothi
+00016570: 6e67 2077 696c 6c20 6265 2073 7562 6d69  ng will be submi
+00016580: 7474 6564 2074 6f20 7468 6520 706c 6174  tted to the plat
+00016590: 666f 726d 2e0a 0a54 6865 2067 656e 6572  form...The gener
+000165a0: 6174 6564 204a 534f 4e20 6973 2070 726f  ated JSON is pro
+000165b0: 6475 6365 6420 6166 7465 7220 616c 6c20  duced after all 
+000165c0: 7072 6f63 6573 7369 6e67 2028 696e 636f  processing (inco
+000165d0: 7270 6f72 6174 696e 6720 6063 6f6e 6669  rporating `confi
+000165e0: 672e 746f 6d6c 6020 7072 6f70 6572 7469  g.toml` properti
+000165f0: 6573 2c20 7661 7269 6162 6c65 2073 7562  es, variable sub
+00016600: 7374 6974 7574 696f 6e73 2c20 6574 632e  stitutions, etc.
+00016610: 2920 6861 7320 6265 656e 2063 6f6e 636c  ) has been concl
+00016620: 7564 6564 2c20 736f 2074 6865 2064 7279  uded, so the dry
+00016630: 2d72 756e 2069 7320 7573 6566 756c 2066  -run is useful f
+00016640: 6f72 2069 6e73 7065 6374 696e 6720 7468  or inspecting th
+00016650: 6520 7265 7375 6c74 7320 6f66 2061 6c6c  e results of all
+00016660: 2074 6865 2070 726f 6365 7373 696e 6720   the processing 
+00016670: 7468 6174 2773 2062 6565 6e20 7065 7266  that's been perf
+00016680: 6f72 6d65 642e 0a0a 546f 2073 7570 7072  ormed...To suppr
+00016690: 6573 7320 616c 6c20 6f75 7470 7574 2065  ess all output e
+000166a0: 7863 6570 7420 666f 7220 7468 6520 4a53  xcept for the JS
+000166b0: 4f4e 2069 7473 656c 662c 2075 7365 2074  ON itself, use t
+000166c0: 6865 2060 2d2d 7175 6965 7460 2028 602d  he `--quiet` (`-
+000166d0: 7160 2920 636f 6d6d 616e 6420 6c69 6e65  q`) command line
+000166e0: 206f 7074 696f 6e2e 0a0a 5468 6520 4a53   option...The JS
+000166f0: 4f4e 2064 7279 2d72 756e 206f 7574 7075  ON dry-run outpu
+00016700: 7420 636f 756c 6420 6974 7365 6c66 2062  t could itself b
+00016710: 6520 7573 6564 2062 7920 6079 642d 7072  e used by `yd-pr
+00016720: 6f76 6973 696f 6e60 2c20 6966 2063 6170  ovision`, if cap
+00016730: 7475 7265 6420 696e 2061 2066 696c 652c  tured in a file,
+00016740: 2065 2e67 2e3a 0a0a 6060 6073 6865 6c6c   e.g.:..```shell
+00016750: 0a79 642d 7072 6f76 6973 696f 6e20 2d2d  .yd-provision --
+00016760: 6472 792d 7275 6e20 2d71 203e 206d 795f  dry-run -q > my_
+00016770: 776f 726b 6572 5f70 6f6f 6c2e 6a73 6f6e  worker_pool.json
+00016780: 0a79 642d 7072 6f76 6973 696f 6e20 2d70  .yd-provision -p
+00016790: 206d 795f 776f 726b 6572 5f70 6f6f 6c2e   my_worker_pool.
+000167a0: 6a73 6f6e 0a60 6060 0a0a 2320 4a73 6f6e  json.```..# Json
+000167b0: 6e65 7420 5375 7070 6f72 740a 0a49 6e20  net Support..In 
+000167c0: 616c 6c20 6369 7263 756d 7374 616e 6365  all circumstance
+000167d0: 7320 7768 6572 6520 4a53 4f4e 2066 696c  s where JSON fil
+000167e0: 6573 2061 7265 2075 7365 6420 6279 2074  es are used by t
+000167f0: 6865 2050 7974 686f 6e20 4578 616d 706c  he Python Exampl
+00016800: 6573 2073 6372 6970 7473 2c20 202a 2a5b  es scripts,  **[
+00016810: 4a73 6f6e 6e65 745d 2868 7474 7073 3a2f  Jsonnet](https:/
+00016820: 2f6a 736f 6e6e 6574 2e6f 7267 292a 2a20  /jsonnet.org)** 
+00016830: 6669 6c65 7320 6361 6e20 6265 2075 7365  files can be use
+00016840: 6420 696e 7374 6561 642e 2054 6869 7320  d instead. This 
+00016850: 616c 6c6f 7773 2074 6865 2075 7365 206f  allows the use o
+00016860: 6620 4a73 6f6e 6e65 7427 7320 706f 7765  f Jsonnet's powe
+00016870: 7266 756c 204a 534f 4e20 6578 7465 6e73  rful JSON extens
+00016880: 696f 6e73 2c20 696e 636c 7564 696e 6720  ions, including 
+00016890: 636f 6d6d 656e 7473 2c20 7661 7269 6162  comments, variab
+000168a0: 6c65 732c 2066 756e 6374 696f 6e73 2c20  les, functions, 
+000168b0: 6574 632e 0a0a 4120 7369 6d70 6c65 2075  etc...A simple u
+000168c0: 7361 6765 2065 7861 6d70 6c65 206d 6967  sage example mig
+000168d0: 6874 2062 653a 0a0a 6060 6073 6865 6c6c  ht be:..```shell
+000168e0: 0a79 642d 7375 626d 6974 202d 2d77 6f72  .yd-submit --wor
+000168f0: 6b2d 7265 7175 6972 656d 656e 7420 6d79  k-requirement my
+00016900: 5f77 6f72 6b5f 7265 712e 6a73 6f6e 6e65  _work_req.jsonne
+00016910: 740a 6060 600a 0a54 6865 2075 7365 206f  t.```..The use o
+00016920: 6620 7468 6520 6669 6c65 6e61 6d65 2065  f the filename e
+00016930: 7874 656e 7369 6f6e 2060 2e6a 736f 6e6e  xtension `.jsonn
+00016940: 6574 6020 7769 6c6c 2069 6e76 6f6b 6520  et` will invoke 
+00016950: 4a73 6f6e 6e65 7420 6576 616c 7561 7469  Jsonnet evaluati
+00016960: 6f6e 2e20 284e 6f74 6520 7468 6174 2061  on. (Note that a
+00016970: 2074 656d 706f 7261 7279 204a 534f 4e20   temporary JSON 
+00016980: 6669 6c65 2069 7320 6372 6561 7465 6420  file is created 
+00016990: 6173 2070 6172 7420 6f66 204a 736f 6e6e  as part of Jsonn
+000169a0: 6574 2070 726f 6365 7373 696e 672c 2077  et processing, w
+000169b0: 6869 6368 2079 6f75 206d 6179 2073 6565  hich you may see
+000169c0: 2072 6566 6572 7265 6420 746f 2069 6e20   referred to in 
+000169d0: 6572 726f 7220 6d65 7373 6167 6573 3a20  error messages: 
+000169e0: 7468 6973 2066 696c 6520 7769 6c6c 2068  this file will h
+000169f0: 6176 6520 6265 656e 2064 656c 6574 6564  ave been deleted
+00016a00: 2062 6566 6f72 6520 7468 6520 7363 7269   before the scri
+00016a10: 7074 2073 746f 7073 2e29 0a0a 2323 204a  pt stops.)..## J
+00016a20: 736f 6e6e 6574 2049 6e73 7461 6c6c 6174  sonnet Installat
+00016a30: 696f 6e0a 0a4a 736f 6e6e 6574 2069 7320  ion..Jsonnet is 
+00016a40: 2a2a 6e6f 742a 2a20 696e 7374 616c 6c65  **not** installe
+00016a50: 6420 6279 2064 6566 6175 6c74 2077 6865  d by default whe
+00016a60: 6e20 6079 656c 6c6f 7764 6f67 2d70 7974  n `yellowdog-pyt
+00016a70: 686f 6e2d 6578 616d 706c 6573 6020 6973  hon-examples` is
+00016a80: 2069 6e73 7461 6c6c 6564 2c20 6265 6361   installed, beca
+00016a90: 7573 6520 7468 6520 7061 636b 6167 6520  use the package 
+00016aa0: 6861 7320 6269 6e61 7279 2063 6f6d 706f  has binary compo
+00016ab0: 6e65 6e74 7320 7768 6963 6820 6172 6520  nents which are 
+00016ac0: 6e6f 7420 6176 6169 6c61 626c 6520 6f6e  not available on
+00016ad0: 2050 7950 4920 666f 7220 616c 6c20 706c   PyPI for all pl
+00016ae0: 6174 666f 726d 732e 2049 6620 796f 7520  atforms. If you 
+00016af0: 7472 7920 746f 2075 7365 2061 204a 736f  try to use a Jso
+00016b00: 6e6e 6574 2066 696c 6520 696e 2074 6865  nnet file in the
+00016b10: 2061 6273 656e 6365 206f 6620 4a73 6f6e   absence of Json
+00016b20: 6e65 742c 2074 6865 2073 6372 6970 7473  net, the scripts
+00016b30: 2077 696c 6c20 7072 696e 7420 616e 2065   will print an e
+00016b40: 7272 6f72 206d 6573 7361 6765 2c20 616e  rror message, an
+00016b50: 6420 7375 6767 6573 7420 616e 2069 6e73  d suggest an ins
+00016b60: 7461 6c6c 6174 696f 6e20 6d65 6368 616e  tallation mechan
+00016b70: 6973 6d2e 0a0a 546f 2069 6e73 7461 6c6c  ism...To install
+00016b80: 204a 736f 6e6e 6574 2061 7420 7468 6520   Jsonnet at the 
+00016b90: 7361 6d65 2074 696d 6520 6173 2069 6e73  same time as ins
+00016ba0: 7461 6c6c 696e 6720 6f72 2075 7064 6174  talling or updat
+00016bb0: 696e 6720 7468 6520 5079 7468 6f6e 2045  ing the Python E
+00016bc0: 7861 6d70 6c65 7320 7363 7269 7074 732c  xamples scripts,
+00016bd0: 206d 6f64 6966 7920 7468 6520 696e 7374   modify the inst
+00016be0: 616c 6c61 7469 6f6e 2061 7320 666f 6c6c  allation as foll
+00016bf0: 6f77 7320 746f 2069 6e63 6c75 6465 2074  ows to include t
+00016c00: 6865 2060 6a73 6f6e 6e65 7460 206f 7074  he `jsonnet` opt
+00016c10: 696f 6e3a 0a0a 6060 600a 7069 7020 696e  ion:..```.pip in
+00016c20: 7374 616c 6c20 2d55 2022 7965 6c6c 6f77  stall -U "yellow
+00016c30: 646f 672d 7079 7468 6f6e 2d65 7861 6d70  dog-python-examp
+00016c40: 6c65 735b 6a73 6f6e 6e65 745d 220a 6060  les[jsonnet]".``
+00016c50: 600a 0a54 6f20 696e 7374 616c 6c20 4a73  `..To install Js
+00016c60: 6f6e 6e65 7420 7365 7061 7261 7465 6c79  onnet separately
+00016c70: 2066 726f 6d20 6079 656c 6c6f 7764 6f67   from `yellowdog
+00016c80: 2d70 7974 686f 6e2d 6578 616d 706c 6573  -python-examples
+00016c90: 602c 2074 7279 3a0a 0a60 6060 7368 656c  `, try:..```shel
+00016ca0: 6c0a 7069 7020 696e 7374 616c 6c20 2d55  l.pip install -U
+00016cb0: 206a 736f 6e6e 6574 0a60 6060 0a0a 4966   jsonnet.```..If
+00016cc0: 2074 6869 7320 6661 696c 732c 2074 7279   this fails, try
+00016cd0: 3a0a 0a60 6060 7368 656c 6c0a 7069 7020  :..```shell.pip 
+00016ce0: 696e 7374 616c 6c20 2d55 206a 736f 6e6e  install -U jsonn
+00016cf0: 6574 2d62 696e 6172 790a 6060 600a 0a49  et-binary.```..I
+00016d00: 6620 626f 7468 206f 6620 7468 6573 6520  f both of these 
+00016d10: 6d65 7468 6f64 7320 6661 696c 2c20 796f  methods fail, yo
+00016d20: 7527 6c6c 206e 6565 6420 746f 2065 6e73  u'll need to ens
+00016d30: 7572 6520 7468 6174 2074 6865 2070 6c61  ure that the pla
+00016d40: 7466 6f72 6d20 6f6e 2077 6869 6368 2079  tform on which y
+00016d50: 6f75 2772 6520 7275 6e6e 696e 6720 6861  ou're running ha
+00016d60: 7320 7468 6520 7265 7175 6972 6564 2062  s the required b
+00016d70: 7569 6c64 2074 6f6f 6c73 2061 7661 696c  uild tools avail
+00016d80: 6162 6c65 2c20 736f 2074 6861 7420 7468  able, so that th
+00016d90: 6520 4a73 6f6e 6e65 7420 6269 6e61 7279  e Jsonnet binary
+00016da0: 2063 6f6d 706f 6e65 6e74 7320 6361 6e20   components can 
+00016db0: 6265 2062 7569 6c74 206c 6f63 616c 6c79  be built locally
+00016dc0: 2e20 5468 6520 7265 7175 6972 6564 2062  . The required b
+00016dd0: 7569 6c64 2070 6163 6b61 6765 7320 7661  uild packages va
+00016de0: 7279 2062 7920 706c 6174 666f 726d 2062  ry by platform b
+00016df0: 7574 2075 7375 616c 6c79 2069 6e63 6c75  ut usually inclu
+00016e00: 6465 2067 656e 6572 616c 2064 6576 656c  de general devel
+00016e10: 6f70 6d65 6e74 2074 6f6f 6c73 2069 6e63  opment tools inc
+00016e20: 6c75 6469 6e67 2061 2043 2b2b 2063 6f6d  luding a C++ com
+00016e30: 7069 6c65 722c 2061 6e64 2050 7974 686f  piler, and Pytho
+00016e40: 6e20 6465 7665 6c6f 706d 656e 7420 746f  n development to
+00016e50: 6f6c 7320 696e 636c 7564 696e 6720 7468  ols including th
+00016e60: 6520 5079 7468 6f6e 2068 6561 6465 7273  e Python headers
+00016e70: 2e0a 0a50 6c65 6173 6520 6765 7420 696e  ...Please get in
+00016e80: 2074 6f75 6368 2077 6974 6820 5965 6c6c   touch with Yell
+00016e90: 6f77 446f 6720 6966 2079 6f75 2067 6574  owDog if you get
+00016ea0: 2073 7475 636b 2e0a 0a23 2320 5661 7269   stuck...## Vari
+00016eb0: 6162 6c65 2053 7562 7374 6974 7574 696f  able Substitutio
+00016ec0: 6e73 2069 6e20 4a73 6f6e 6e65 7420 4669  ns in Jsonnet Fi
+00016ed0: 6c65 730a 0a54 6865 2073 6372 6970 7473  les..The scripts
+00016ee0: 2070 726f 7669 6465 2066 756c 6c20 7375   provide full su
+00016ef0: 7070 6f72 7420 666f 7220 7661 7269 6162  pport for variab
+00016f00: 6c65 2073 7562 7374 6974 7574 696f 6e73  le substitutions
+00016f10: 2069 6e20 4a73 6f6e 6e65 7420 6669 6c65   in Jsonnet file
+00016f20: 732c 2075 7369 6e67 2074 6865 2073 616d  s, using the sam
+00016f30: 6520 7275 6c65 7320 6173 2066 6f72 2074  e rules as for t
+00016f40: 6865 204a 534f 4e20 7370 6563 6966 6963  he JSON specific
+00016f50: 6174 696f 6e73 2e20 5265 6d65 6d62 6572  ations. Remember
+00016f60: 2074 6861 7420 666f 7220 2a2a 576f 726b   that for **Work
+00016f70: 6572 2050 6f6f 6c2a 2a20 7370 6563 6966  er Pool** specif
+00016f80: 6963 6174 696f 6e73 2c20 7661 7269 6162  ications, variab
+00016f90: 6c65 2073 7562 7374 6974 7574 696f 6e73  le substitutions
+00016fa0: 206d 7573 7420 6265 2070 7265 6669 7865   must be prefixe
+00016fb0: 6420 6279 2060 5f5f 602c 2065 2e67 2e20  d by `__`, e.g. 
+00016fc0: 6022 5f5f 7b7b 7573 6572 6e61 6d65 7d7d  `"__{{username}}
+00016fd0: 7d22 602e 0a0a 5661 7269 6162 6c65 2073  }"`...Variable s
+00016fe0: 7562 7374 6974 7574 696f 6e20 6973 2070  ubstitution is p
+00016ff0: 6572 666f 726d 6564 2062 6566 6f72 6520  erformed before 
+00017000: 4a73 6f6e 6e65 7420 6578 7061 6e73 696f  Jsonnet expansio
+00017010: 6e20 696e 746f 204a 534f 4e2c 2061 6e64  n into JSON, and
+00017020: 2061 6761 696e 2061 6674 6572 2074 6865   again after the
+00017030: 2065 7870 616e 7369 6f6e 2e0a 0a23 2320   expansion...## 
+00017040: 4368 6563 6b69 6e67 204a 736f 6e6e 6574  Checking Jsonnet
+00017050: 2050 726f 6365 7373 696e 670a 0a54 6865   Processing..The
+00017060: 7265 2061 7265 2074 6872 6565 2070 6f73  re are three pos
+00017070: 7369 6269 6c69 7469 6573 2066 6f72 2076  sibilities for v
+00017080: 6572 6966 7969 6e67 2074 6861 7420 6120  erifying that a 
+00017090: 4a73 6f6e 6e65 7420 7370 6563 6966 6963  Jsonnet specific
+000170a0: 6174 696f 6e20 6973 2064 6f69 6e67 2077  ation is doing w
+000170b0: 6861 7420 6973 2069 6e74 656e 6465 643a  hat is intended:
+000170c0: 0a0a 312e 2054 6f20 696e 7370 6563 7420  ..1. To inspect 
+000170d0: 7468 6520 6261 7369 6320 636f 6e76 6572  the basic conver
+000170e0: 7369 6f6e 206f 6620 4a73 6f6e 6e65 7420  sion of Jsonnet 
+000170f0: 696e 746f 204a 534f 4e2c 2077 6974 686f  into JSON, witho
+00017100: 7574 2061 6e79 2061 6464 6974 696f 6e61  ut any additiona
+00017110: 6c20 7072 6f63 6573 7369 6e67 2062 7920  l processing by 
+00017120: 7468 6520 5079 7468 6f6e 2045 7861 6d70  the Python Examp
+00017130: 6c65 7320 7363 7269 7074 732c 2074 6865  les scripts, the
+00017140: 2060 7964 2d6a 736f 6e6e 6574 326a 736f   `yd-jsonnet2jso
+00017150: 6e60 2063 6f6d 6d61 6e64 2063 616e 2062  n` command can b
+00017160: 6520 7573 6564 2e20 5468 6973 2074 616b  e used. This tak
+00017170: 6573 2061 2073 696e 676c 6520 636f 6d6d  es a single comm
+00017180: 616e 6420 6c69 6e65 2061 7267 756d 656e  and line argumen
+00017190: 7420 7768 6963 6820 6973 2074 6865 206e  t which is the n
+000171a0: 616d 6520 6f66 2074 6865 206a 736f 6e6e  ame of the jsonn
+000171b0: 6574 2066 696c 6520 746f 2062 6520 7072  et file to be pr
+000171c0: 6f63 6573 7365 643a 0a0a 6060 6073 6865  ocessed:..```she
+000171d0: 6c6c 0a79 642d 6a73 6f6e 6e65 7432 6a73  ll.yd-jsonnet2js
+000171e0: 6f6e 206d 795f 6669 6c65 2e6a 736f 6e6e  on my_file.jsonn
+000171f0: 6574 0a60 6060 0a0a 0a32 2e20 5468 6520  et.```...2. The 
+00017200: 606a 736f 6e6e 6574 2d64 7279 2d72 756e  `jsonnet-dry-run
+00017210: 6020 2860 2d4a 6029 206f 7074 696f 6e20  ` (`-J`) option 
+00017220: 6f66 2074 6865 2060 7964 2d73 7562 6d69  of the `yd-submi
+00017230: 7460 2c20 6079 642d 7072 6f76 6973 696f  t`, `yd-provisio
+00017240: 6e60 2061 6e64 2060 7964 2d69 6e73 7461  n` and `yd-insta
+00017250: 6e74 6961 7465 6020 636f 6d6d 616e 6473  ntiate` commands
+00017260: 2077 696c 6c20 6765 6e65 7261 7465 204a   will generate J
+00017270: 534f 4e20 6f75 7470 7574 2072 6570 7265  SON output repre
+00017280: 7365 6e74 696e 6720 7468 6520 4a73 6f6e  senting the Json
+00017290: 6e65 7420 746f 204a 534f 4e20 7072 6f63  net to JSON proc
+000172a0: 6573 7369 6e67 206f 6e6c 792c 2069 6e63  essing only, inc
+000172b0: 6c75 6469 6e67 2061 7070 6c69 6361 626c  luding applicabl
+000172c0: 6520 7661 7269 6162 6c65 2073 7562 7374  e variable subst
+000172d0: 6974 7574 696f 6e73 2c20 6275 7420 6265  itutions, but be
+000172e0: 666f 7265 2066 756c 6c20 7072 6f70 6572  fore full proper
+000172f0: 7479 2065 7870 616e 7369 6f6e 2069 6e74  ty expansion int
+00017300: 6f20 7468 6520 4a53 4f4e 2074 6861 7420  o the JSON that 
+00017310: 7769 6c6c 2062 6520 7375 626d 6974 7465  will be submitte
+00017320: 6420 746f 2074 6865 2050 6c61 7466 6f72  d to the Platfor
+00017330: 6d2e 0a0a 0a33 2e20 5468 6520 6064 7279  m....3. The `dry
+00017340: 2d72 756e 6020 2860 2d44 6029 206f 7074  -run` (`-D`) opt
+00017350: 696f 6e20 7769 6c6c 2067 656e 6572 6174  ion will generat
+00017360: 6520 4a53 4f4e 206f 7574 7075 7420 7265  e JSON output re
+00017370: 7072 6573 656e 7469 6e67 2074 6865 2066  presenting the f
+00017380: 756c 6c20 7072 6f63 6573 7369 6e67 206f  ull processing o
+00017390: 6620 7468 6520 4a73 6f6e 6e65 7420 6669  f the Jsonnet fi
+000173a0: 6c65 2069 6e74 6f20 7768 6174 2077 696c  le into what wil
+000173b0: 6c20 6265 2073 7562 6d69 7474 6564 2074  l be submitted t
+000173c0: 6f20 7468 6520 4150 492e 2054 6869 7320  o the API. This 
+000173d0: 616c 6c6f 7773 2069 6e73 7065 6374 696f  allows inspectio
+000173e0: 6e20 746f 2063 6865 636b 2074 6861 7420  n to check that 
+000173f0: 7468 6520 6f75 7470 7574 206d 6174 6368  the output match
+00017400: 6573 2065 7870 6563 7461 7469 6f6e 732c  es expectations,
+00017410: 2070 7269 6f72 2074 6f20 7375 626d 6974   prior to submit
+00017420: 7469 6e67 2074 6f20 7468 6520 506c 6174  ting to the Plat
+00017430: 666f 726d 2e0a 0a23 2320 4a73 6f6e 6e65  form...## Jsonne
+00017440: 7420 4578 616d 706c 650a 0a48 6572 6527  t Example..Here'
+00017450: 7320 616e 2065 7861 6d70 6c65 206f 6620  s an example of 
+00017460: 6120 4a73 6f6e 6e65 7420 6669 6c65 2074  a Jsonnet file t
+00017470: 6861 7420 6765 6e65 7261 7465 7320 6120  hat generates a 
+00017480: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+00017490: 2077 6974 6820 666f 7572 2054 6173 6b73   with four Tasks
+000174a0: 3a0a 0a60 6060 6a73 6f6e 6e65 740a 2320  :..```jsonnet.# 
+000174b0: 4675 6e63 7469 6f6e 2066 6f72 2073 796e  Function for syn
+000174c0: 7468 6573 6973 696e 6720 5461 736b 730a  thesising Tasks.
+000174d0: 6c6f 6361 6c20 5461 736b 2861 7267 756d  local Task(argum
+000174e0: 656e 7473 3d5b 5d2c 2065 6e76 6972 6f6e  ents=[], environ
+000174f0: 6d65 6e74 3d7b 7d29 203d 207b 0a20 2020  ment={}) = {.   
+00017500: 2061 7267 756d 656e 7473 3a20 6172 6775   arguments: argu
+00017510: 6d65 6e74 732c 0a20 2020 2065 6e76 6972  ments,.    envir
+00017520: 6f6e 6d65 6e74 3a20 656e 7669 726f 6e6d  onment: environm
+00017530: 656e 742c 0a20 2020 206e 616d 653a 2022  ent,.    name: "
+00017540: 6d79 5f74 6173 6b5f 7b7b 7461 736b 5f6e  my_task_{{task_n
+00017550: 756d 6265 727d 7d22 0a7d 3b0a 0a23 2057  umber}}".};..# W
+00017560: 6f72 6b20 5265 7175 6972 656d 656e 740a  ork Requirement.
+00017570: 7b0a 2020 226e 616d 6522 3a20 2277 6f72  {.  "name": "wor
+00017580: 6b72 6571 5f7b 7b64 6174 6574 696d 657d  kreq_{{datetime}
+00017590: 7d22 2c0a 2020 2274 6173 6b47 726f 7570  }",.  "taskGroup
+000175a0: 7322 3a20 5b0a 2020 2020 7b0a 2020 2020  s": [.    {.    
+000175b0: 2020 2274 6173 6b73 223a 205b 0a20 2020    "tasks": [.   
+000175c0: 2020 2020 2054 6173 6b28 5b22 3122 5d2c       Task(["1"],
+000175d0: 207b 413a 2022 415f 3122 7d29 2c20 2023   {A: "A_1"}),  #
+000175e0: 2061 7267 756d 656e 7473 2061 6e64 2065   arguments and e
+000175f0: 6e76 6972 6f6e 6d65 6e74 0a20 2020 2020  nvironment.     
+00017600: 2020 2054 6173 6b28 5b22 3222 2c20 2233     Task(["2", "3
+00017610: 225d 2c20 7b7d 292c 2020 2020 2023 2061  "], {}),     # a
+00017620: 7267 756d 656e 7473 2061 6e64 2065 6d70  rguments and emp
+00017630: 7479 2065 6e76 6972 6f6e 6d65 6e74 0a20  ty environment. 
+00017640: 2020 2020 2020 2054 6173 6b28 5b22 3422         Task(["4"
+00017650: 5d29 2c20 2020 2020 2020 2020 2020 2020  ]),             
+00017660: 2023 2061 7267 756d 656e 7473 2061 6e64   # arguments and
+00017670: 2064 6566 6175 6c74 2065 6e76 6972 6f6e   default environ
+00017680: 6d65 6e74 0a20 2020 2020 2020 2054 6173  ment.        Tas
+00017690: 6b28 2920 2020 2020 2020 2020 2020 2020  k()             
+000176a0: 2020 2020 2020 2023 2064 6566 6175 6c74         # default
+000176b0: 2061 7267 756d 656e 7473 2061 6e64 2065   arguments and e
+000176c0: 6e76 6972 6f6e 6d65 6e74 0a20 2020 2020  nvironment.     
+000176d0: 205d 0a20 2020 207d 0a20 205d 0a7d 0a60   ].    }.  ].}.`
+000176e0: 6060 0a0a 5768 656e 2074 6869 7320 6973  ``..When this is
+000176f0: 2069 6e73 7065 6374 6564 2075 7369 6e67   inspected using
+00017700: 2074 6865 2060 6a73 6f6e 6e65 742d 6472   the `jsonnet-dr
+00017710: 792d 7275 6e60 206f 7074 696f 6e20 2860  y-run` option (`
+00017720: 7964 2d73 7562 6d69 7420 2d4a 7120 2d72  yd-submit -Jq -r
+00017730: 206d 795f 776f 726b 5f72 6571 2e6a 736f   my_work_req.jso
+00017740: 6e6e 6574 6029 2c20 7468 6973 2069 7320  nnet`), this is 
+00017750: 7468 6520 7072 6f63 6573 7365 6420 6f75  the processed ou
+00017760: 7470 7574 3a0a 0a60 6060 6a73 6f6e 0a7b  tput:..```json.{
+00017770: 0a20 2022 6e61 6d65 223a 2022 776f 726b  .  "name": "work
+00017780: 7265 715f 3233 3031 3134 2d31 3430 3634  req_230114-14064
+00017790: 3522 2c0a 2020 2274 6173 6b47 726f 7570  5",.  "taskGroup
+000177a0: 7322 3a20 5b0a 2020 2020 7b0a 2020 2020  s": [.    {.    
+000177b0: 2020 2274 6173 6b73 223a 205b 0a20 2020    "tasks": [.   
+000177c0: 2020 2020 207b 0a20 2020 2020 2020 2020       {.         
+000177d0: 2022 6172 6775 6d65 6e74 7322 3a20 5b22   "arguments": ["
+000177e0: 3122 5d2c 0a20 2020 2020 2020 2020 2022  1"],.          "
+000177f0: 656e 7669 726f 6e6d 656e 7422 3a20 7b22  environment": {"
+00017800: 4122 3a20 2241 5f31 227d 2c0a 2020 2020  A": "A_1"},.    
+00017810: 2020 2020 2020 226e 616d 6522 3a20 226d        "name": "m
+00017820: 795f 7461 736b 5f7b 7b74 6173 6b5f 6e75  y_task_{{task_nu
+00017830: 6d62 6572 7d7d 220a 2020 2020 2020 2020  mber}}".        
+00017840: 7d2c 0a20 2020 2020 2020 207b 0a20 2020  },.        {.   
+00017850: 2020 2020 2020 2022 6172 6775 6d65 6e74         "argument
+00017860: 7322 3a20 5b22 3222 2c20 2233 225d 2c0a  s": ["2", "3"],.
+00017870: 2020 2020 2020 2020 2020 2265 6e76 6972            "envir
+00017880: 6f6e 6d65 6e74 223a 207b 7d2c 0a20 2020  onment": {},.   
+00017890: 2020 2020 2020 2022 6e61 6d65 223a 2022         "name": "
+000178a0: 6d79 5f74 6173 6b5f 7b7b 7461 736b 5f6e  my_task_{{task_n
+000178b0: 756d 6265 727d 7d22 0a20 2020 2020 2020  umber}}".       
+000178c0: 207d 2c0a 2020 2020 2020 2020 7b0a 2020   },.        {.  
+000178d0: 2020 2020 2020 2020 2261 7267 756d 656e          "argumen
+000178e0: 7473 223a 205b 2234 225d 2c0a 2020 2020  ts": ["4"],.    
+000178f0: 2020 2020 2020 2265 6e76 6972 6f6e 6d65        "environme
+00017900: 6e74 223a 207b 7d2c 0a20 2020 2020 2020  nt": {},.       
+00017910: 2020 2022 6e61 6d65 223a 2022 6d79 5f74     "name": "my_t
+00017920: 6173 6b5f 7b7b 7461 736b 5f6e 756d 6265  ask_{{task_numbe
+00017930: 727d 7d22 0a20 2020 2020 2020 207d 2c0a  r}}".        },.
+00017940: 2020 2020 2020 2020 7b0a 2020 2020 2020          {.      
+00017950: 2020 2020 2261 7267 756d 656e 7473 223a      "arguments":
+00017960: 205b 5d2c 0a20 2020 2020 2020 2020 2022   [],.          "
+00017970: 656e 7669 726f 6e6d 656e 7422 3a20 7b7d  environment": {}
+00017980: 2c0a 2020 2020 2020 2020 2020 226e 616d  ,.          "nam
+00017990: 6522 3a20 226d 795f 7461 736b 5f7b 7b74  e": "my_task_{{t
+000179a0: 6173 6b5f 6e75 6d62 6572 7d7d 220a 2020  ask_number}}".  
+000179b0: 2020 2020 2020 7d0a 2020 2020 2020 5d0a        }.      ].
+000179c0: 2020 2020 7d0a 2020 5d0a 7d0a 6060 600a      }.  ].}.```.
+000179d0: 0a57 6865 6e20 7468 6973 2069 7320 696e  .When this is in
+000179e0: 7370 6563 7465 6420 7573 696e 6720 7468  spected using th
+000179f0: 6520 6064 7279 2d72 756e 6020 6f70 7469  e `dry-run` opti
+00017a00: 6f6e 2028 6079 642d 7375 626d 6974 202d  on (`yd-submit -
+00017a10: 4471 202d 7220 6d79 5f77 6f72 6b5f 7265  Dq -r my_work_re
+00017a20: 712e 6a73 6f6e 6e65 7460 292c 2074 6869  q.jsonnet`), thi
+00017a30: 7320 6973 2074 6865 2070 726f 6365 7373  s is the process
+00017a40: 6564 206f 7574 7075 743a 0a0a 6060 606a  ed output:..```j
+00017a50: 736f 6e0a 7b0a 2020 2266 756c 6669 6c4f  son.{.  "fulfilO
+00017a60: 6e53 7562 6d69 7422 3a20 6661 6c73 652c  nSubmit": false,
+00017a70: 0a20 2022 6e61 6d65 223a 2022 776f 726b  .  "name": "work
+00017a80: 7265 715f 3233 3031 3134 2d31 3430 3634  req_230114-14064
+00017a90: 3522 2c0a 2020 226e 616d 6573 7061 6365  5",.  "namespace
+00017aa0: 223a 2022 7079 6578 616d 706c 6573 222c  ": "pyexamples",
+00017ab0: 0a20 2022 7072 696f 7269 7479 223a 2030  .  "priority": 0
+00017ac0: 2c0a 2020 2274 6167 223a 2022 7079 6578  ,.  "tag": "pyex
+00017ad0: 2d62 6173 6822 2c0a 2020 2274 6173 6b47  -bash",.  "taskG
+00017ae0: 726f 7570 7322 3a20 5b0a 2020 2020 7b0a  roups": [.    {.
+00017af0: 2020 2020 2020 2266 696e 6973 6849 6641        "finishIfA
+00017b00: 6c6c 5461 736b 7346 696e 6973 6865 6422  llTasksFinished"
+00017b10: 3a20 7472 7565 2c0a 2020 2020 2020 2266  : true,.      "f
+00017b20: 696e 6973 6849 6641 6e79 5461 736b 4661  inishIfAnyTaskFa
+00017b30: 696c 6564 223a 2066 616c 7365 2c0a 2020  iled": false,.  
+00017b40: 2020 2020 226e 616d 6522 3a20 2274 6173      "name": "tas
+00017b50: 6b5f 6772 6f75 705f 3122 2c0a 2020 2020  k_group_1",.    
+00017b60: 2020 2270 7269 6f72 6974 7922 3a20 302c    "priority": 0,
+00017b70: 0a20 2020 2020 2022 7275 6e53 7065 6369  .      "runSpeci
+00017b80: 6669 6361 7469 6f6e 223a 207b 0a20 2020  fication": {.   
+00017b90: 2020 2020 2022 6d61 7869 6d75 6d54 6173       "maximumTas
+00017ba0: 6b52 6574 7269 6573 223a 2030 2c0a 2020  kRetries": 0,.  
+00017bb0: 2020 2020 2020 2274 6173 6b54 7970 6573        "taskTypes
+00017bc0: 223a 205b 2262 6173 6822 5d2c 0a20 2020  ": ["bash"],.   
+00017bd0: 2020 2020 2022 776f 726b 6572 5461 6773       "workerTags
+00017be0: 223a 205b 2270 7965 782d 6261 7368 2d64  ": ["pyex-bash-d
+00017bf0: 6f63 6b65 7222 5d0a 2020 2020 2020 7d2c  ocker"].      },
+00017c00: 0a20 2020 2020 2022 7461 736b 7322 3a20  .      "tasks": 
+00017c10: 5b0a 2020 2020 2020 2020 7b0a 2020 2020  [.        {.    
+00017c20: 2020 2020 2020 2261 7267 756d 656e 7473        "arguments
+00017c30: 223a 205b 2277 6f72 6b72 6571 5f32 3330  ": ["workreq_230
+00017c40: 3131 342d 3134 3036 3435 2f73 6c65 6570  114-140645/sleep
+00017c50: 5f73 6372 6970 742e 7368 222c 2022 3122  _script.sh", "1"
+00017c60: 5d2c 0a20 2020 2020 2020 2020 2022 656e  ],.          "en
+00017c70: 7669 726f 6e6d 656e 7422 3a20 7b22 4122  vironment": {"A"
+00017c80: 3a20 2241 5f31 227d 2c0a 2020 2020 2020  : "A_1"},.      
+00017c90: 2020 2020 2269 6e70 7574 7322 3a20 5b0a      "inputs": [.
+00017ca0: 2020 2020 2020 2020 2020 2020 7b0a 2020              {.  
+00017cb0: 2020 2020 2020 2020 2020 2020 226f 626a              "obj
+00017cc0: 6563 744e 616d 6550 6174 7465 726e 223a  ectNamePattern":
+00017cd0: 2022 776f 726b 7265 715f 3233 3031 3134   "workreq_230114
+00017ce0: 2d31 3430 3634 352f 736c 6565 705f 7363  -140645/sleep_sc
+00017cf0: 7269 7074 2e73 6822 2c0a 2020 2020 2020  ript.sh",.      
+00017d00: 2020 2020 2020 2020 2273 6f75 7263 6522          "source"
+00017d10: 3a20 2254 4153 4b5f 4e41 4d45 5350 4143  : "TASK_NAMESPAC
+00017d20: 4522 2c0a 2020 2020 2020 2020 2020 2020  E",.            
+00017d30: 2020 2276 6572 6966 6963 6174 696f 6e22    "verification"
+00017d40: 3a20 2256 4552 4946 595f 4154 5f53 5441  : "VERIFY_AT_STA
+00017d50: 5254 220a 2020 2020 2020 2020 2020 2020  RT".            
+00017d60: 7d0a 2020 2020 2020 2020 2020 5d2c 0a20  }.          ],. 
+00017d70: 2020 2020 2020 2020 2022 6e61 6d65 223a           "name":
+00017d80: 2022 6d79 5f74 6173 6b5f 3122 2c0a 2020   "my_task_1",.  
+00017d90: 2020 2020 2020 2020 226f 7574 7075 7473          "outputs
+00017da0: 223a 205b 0a20 2020 2020 2020 2020 2020  ": [.           
+00017db0: 207b 2261 6c77 6179 7355 706c 6f61 6422   {"alwaysUpload"
+00017dc0: 3a20 7472 7565 2c20 2272 6571 7569 7265  : true, "require
+00017dd0: 6422 3a20 6661 6c73 652c 2022 736f 7572  d": false, "sour
+00017de0: 6365 223a 2022 5052 4f43 4553 535f 4f55  ce": "PROCESS_OU
+00017df0: 5450 5554 227d 0a20 2020 2020 2020 2020  TPUT"}.         
+00017e00: 205d 2c0a 2020 2020 2020 2020 2020 2274   ],.          "t
+00017e10: 6173 6b54 7970 6522 3a20 2262 6173 6822  askType": "bash"
+00017e20: 0a20 2020 2020 2020 207d 2c0a 2020 2020  .        },.    
+00017e30: 2020 2020 7b0a 2020 2020 2020 2020 2020      {.          
+00017e40: 2261 7267 756d 656e 7473 223a 205b 2277  "arguments": ["w
+00017e50: 6f72 6b72 6571 5f32 3330 3131 342d 3134  orkreq_230114-14
+00017e60: 3036 3435 2f73 6c65 6570 5f73 6372 6970  0645/sleep_scrip
+00017e70: 742e 7368 222c 2022 3222 2c20 2233 225d  t.sh", "2", "3"]
+00017e80: 2c0a 2020 2020 2020 2020 2020 2265 6e76  ,.          "env
+00017e90: 6972 6f6e 6d65 6e74 223a 207b 7d2c 0a20  ironment": {},. 
+00017ea0: 2020 2020 2020 2020 2022 696e 7075 7473           "inputs
+00017eb0: 223a 205b 0a20 2020 2020 2020 2020 2020  ": [.           
+00017ec0: 207b 0a20 2020 2020 2020 2020 2020 2020   {.             
+00017ed0: 2022 6f62 6a65 6374 4e61 6d65 5061 7474   "objectNamePatt
+00017ee0: 6572 6e22 3a20 2277 6f72 6b72 6571 5f32  ern": "workreq_2
+00017ef0: 3330 3131 342d 3134 3036 3435 2f73 6c65  30114-140645/sle
+00017f00: 6570 5f73 6372 6970 742e 7368 222c 0a20  ep_script.sh",. 
+00017f10: 2020 2020 2020 2020 2020 2020 2022 736f               "so
+00017f20: 7572 6365 223a 2022 5441 534b 5f4e 414d  urce": "TASK_NAM
+00017f30: 4553 5041 4345 222c 0a20 2020 2020 2020  ESPACE",.       
+00017f40: 2020 2020 2020 2022 7665 7269 6669 6361         "verifica
+00017f50: 7469 6f6e 223a 2022 5645 5249 4659 5f41  tion": "VERIFY_A
+00017f60: 545f 5354 4152 5422 0a20 2020 2020 2020  T_START".       
+00017f70: 2020 2020 207d 0a20 2020 2020 2020 2020       }.         
+00017f80: 205d 2c0a 2020 2020 2020 2020 2020 226e   ],.          "n
+00017f90: 616d 6522 3a20 226d 795f 7461 736b 5f32  ame": "my_task_2
+00017fa0: 222c 0a20 2020 2020 2020 2020 2022 6f75  ",.          "ou
+00017fb0: 7470 7574 7322 3a20 5b0a 2020 2020 2020  tputs": [.      
+00017fc0: 2020 2020 2020 7b22 616c 7761 7973 5570        {"alwaysUp
+00017fd0: 6c6f 6164 223a 2074 7275 652c 2022 7265  load": true, "re
+00017fe0: 7175 6972 6564 223a 2066 616c 7365 2c20  quired": false, 
+00017ff0: 2273 6f75 7263 6522 3a20 2250 524f 4345  "source": "PROCE
+00018000: 5353 5f4f 5554 5055 5422 7d0a 2020 2020  SS_OUTPUT"}.    
+00018010: 2020 2020 2020 5d2c 0a20 2020 2020 2020        ],.       
+00018020: 2020 2022 7461 736b 5479 7065 223a 2022     "taskType": "
+00018030: 6261 7368 220a 2020 2020 2020 2020 7d2c  bash".        },
+00018040: 0a20 2020 2020 2020 207b 0a20 2020 2020  .        {.     
+00018050: 2020 2020 2022 6172 6775 6d65 6e74 7322       "arguments"
+00018060: 3a20 5b22 776f 726b 7265 715f 3233 3031  : ["workreq_2301
+00018070: 3134 2d31 3430 3634 352f 736c 6565 705f  14-140645/sleep_
+00018080: 7363 7269 7074 2e73 6822 2c20 2234 225d  script.sh", "4"]
+00018090: 2c0a 2020 2020 2020 2020 2020 2265 6e76  ,.          "env
+000180a0: 6972 6f6e 6d65 6e74 223a 207b 7d2c 0a20  ironment": {},. 
+000180b0: 2020 2020 2020 2020 2022 696e 7075 7473           "inputs
+000180c0: 223a 205b 0a20 2020 2020 2020 2020 2020  ": [.           
+000180d0: 207b 0a20 2020 2020 2020 2020 2020 2020   {.             
+000180e0: 2022 6f62 6a65 6374 4e61 6d65 5061 7474   "objectNamePatt
+000180f0: 6572 6e22 3a20 2277 6f72 6b72 6571 5f32  ern": "workreq_2
+00018100: 3330 3131 342d 3134 3036 3435 2f73 6c65  30114-140645/sle
+00018110: 6570 5f73 6372 6970 742e 7368 222c 0a20  ep_script.sh",. 
+00018120: 2020 2020 2020 2020 2020 2020 2022 736f               "so
+00018130: 7572 6365 223a 2022 5441 534b 5f4e 414d  urce": "TASK_NAM
+00018140: 4553 5041 4345 222c 0a20 2020 2020 2020  ESPACE",.       
+00018150: 2020 2020 2020 2022 7665 7269 6669 6361         "verifica
+00018160: 7469 6f6e 223a 2022 5645 5249 4659 5f41  tion": "VERIFY_A
+00018170: 545f 5354 4152 5422 0a20 2020 2020 2020  T_START".       
+00018180: 2020 2020 207d 0a20 2020 2020 2020 2020       }.         
+00018190: 205d 2c0a 2020 2020 2020 2020 2020 226e   ],.          "n
+000181a0: 616d 6522 3a20 226d 795f 7461 736b 5f33  ame": "my_task_3
+000181b0: 222c 0a20 2020 2020 2020 2020 2022 6f75  ",.          "ou
+000181c0: 7470 7574 7322 3a20 5b0a 2020 2020 2020  tputs": [.      
+000181d0: 2020 2020 2020 7b22 616c 7761 7973 5570        {"alwaysUp
+000181e0: 6c6f 6164 223a 2074 7275 652c 2022 7265  load": true, "re
+000181f0: 7175 6972 6564 223a 2066 616c 7365 2c20  quired": false, 
+00018200: 2273 6f75 7263 6522 3a20 2250 524f 4345  "source": "PROCE
+00018210: 5353 5f4f 5554 5055 5422 7d0a 2020 2020  SS_OUTPUT"}.    
+00018220: 2020 2020 2020 5d2c 0a20 2020 2020 2020        ],.       
+00018230: 2020 2022 7461 736b 5479 7065 223a 2022     "taskType": "
+00018240: 6261 7368 220a 2020 2020 2020 2020 7d2c  bash".        },
+00018250: 0a20 2020 2020 2020 207b 0a20 2020 2020  .        {.     
+00018260: 2020 2020 2022 6172 6775 6d65 6e74 7322       "arguments"
+00018270: 3a20 5b22 776f 726b 7265 715f 3233 3031  : ["workreq_2301
+00018280: 3134 2d31 3430 3634 352f 736c 6565 705f  14-140645/sleep_
+00018290: 7363 7269 7074 2e73 6822 5d2c 0a20 2020  script.sh"],.   
+000182a0: 2020 2020 2020 2022 656e 7669 726f 6e6d         "environm
+000182b0: 656e 7422 3a20 7b7d 2c0a 2020 2020 2020  ent": {},.      
+000182c0: 2020 2020 2269 6e70 7574 7322 3a20 5b0a      "inputs": [.
+000182d0: 2020 2020 2020 2020 2020 2020 7b0a 2020              {.  
+000182e0: 2020 2020 2020 2020 2020 2020 226f 626a              "obj
+000182f0: 6563 744e 616d 6550 6174 7465 726e 223a  ectNamePattern":
+00018300: 2022 776f 726b 7265 715f 3233 3031 3134   "workreq_230114
+00018310: 2d31 3430 3634 352f 736c 6565 705f 7363  -140645/sleep_sc
+00018320: 7269 7074 2e73 6822 2c0a 2020 2020 2020  ript.sh",.      
+00018330: 2020 2020 2020 2020 2273 6f75 7263 6522          "source"
+00018340: 3a20 2254 4153 4b5f 4e41 4d45 5350 4143  : "TASK_NAMESPAC
+00018350: 4522 2c0a 2020 2020 2020 2020 2020 2020  E",.            
+00018360: 2020 2276 6572 6966 6963 6174 696f 6e22    "verification"
+00018370: 3a20 2256 4552 4946 595f 4154 5f53 5441  : "VERIFY_AT_STA
+00018380: 5254 220a 2020 2020 2020 2020 2020 2020  RT".            
+00018390: 7d0a 2020 2020 2020 2020 2020 5d2c 0a20  }.          ],. 
+000183a0: 2020 2020 2020 2020 2022 6e61 6d65 223a           "name":
+000183b0: 2022 6d79 5f74 6173 6b5f 3422 2c0a 2020   "my_task_4",.  
+000183c0: 2020 2020 2020 2020 226f 7574 7075 7473          "outputs
+000183d0: 223a 205b 0a20 2020 2020 2020 2020 2020  ": [.           
+000183e0: 207b 2261 6c77 6179 7355 706c 6f61 6422   {"alwaysUpload"
+000183f0: 3a20 7472 7565 2c20 2272 6571 7569 7265  : true, "require
+00018400: 6422 3a20 6661 6c73 652c 2022 736f 7572  d": false, "sour
+00018410: 6365 223a 2022 5052 4f43 4553 535f 4f55  ce": "PROCESS_OU
+00018420: 5450 5554 227d 0a20 2020 2020 2020 2020  TPUT"}.         
+00018430: 205d 2c0a 2020 2020 2020 2020 2020 2274   ],.          "t
+00018440: 6173 6b54 7970 6522 3a20 2262 6173 6822  askType": "bash"
+00018450: 0a20 2020 2020 2020 207d 0a20 2020 2020  .        }.     
+00018460: 205d 0a20 2020 207d 0a20 205d 0a7d 0a60   ].    }.  ].}.`
+00018470: 6060 0a0a 2320 436f 6d6d 616e 6420 4c69  ``..# Command Li
+00018480: 7374 0a0a 4865 6c70 2069 7320 6176 6169  st..Help is avai
+00018490: 6c61 626c 6520 666f 7220 616c 6c20 636f  lable for all co
+000184a0: 6d6d 616e 6473 2062 7920 696e 766f 6b69  mmands by invoki
+000184b0: 6e67 2061 2063 6f6d 6d61 6e64 2077 6974  ng a command wit
+000184c0: 6820 7468 6520 602d 2d68 656c 7060 206f  h the `--help` o
+000184d0: 7220 602d 6860 206f 7074 696f 6e2e 2053  r `-h` option. S
+000184e0: 6f6d 6520 636f 6d6d 616e 6420 6c69 6e65  ome command line
+000184f0: 2070 6172 616d 6574 6572 7320 6172 6520   parameters are 
+00018500: 636f 6d6d 6f6e 2074 6f20 616c 6c20 636f  common to all co
+00018510: 6d6d 616e 6473 2c20 7768 696c 6520 6f74  mmands, while ot
+00018520: 6865 7273 2061 7265 2063 6f6d 6d61 6e64  hers are command
+00018530: 2d73 7065 6369 6669 632e 0a0a 416c 6c20  -specific...All 
+00018540: 6465 7374 7275 6374 6976 6520 636f 6d6d  destructive comm
+00018550: 616e 6473 2072 6571 7569 7265 2075 7365  ands require use
+00018560: 7220 636f 6e66 6972 6d61 7469 6f6e 2062  r confirmation b
+00018570: 6566 6f72 6520 7461 6b69 6e67 2065 6666  efore taking eff
+00018580: 6563 742e 2054 6869 7320 6361 6e20 6265  ect. This can be
+00018590: 2073 7570 7072 6573 7365 6420 7573 696e   suppressed usin
+000185a0: 6720 7468 6520 602d 2d79 6573 6020 6f72  g the `--yes` or
+000185b0: 2060 2d79 6020 6f70 7469 6f6e 2c20 696e   `-y` option, in
+000185c0: 2077 6869 6368 2063 6173 6520 7468 6520   which case the 
+000185d0: 636f 6d6d 616e 6420 7769 6c6c 2070 726f  command will pro
+000185e0: 6365 6564 2077 6974 686f 7574 2063 6f6e  ceed without con
+000185f0: 6669 726d 6174 696f 6e2e 0a0a 536f 6d65  firmation...Some
+00018600: 2063 6f6d 6d61 6e64 7320 7375 7070 6f72   commands suppor
+00018610: 7420 7468 6520 602d 2d69 6e74 6572 6163  t the `--interac
+00018620: 7469 7665 6020 6f72 2060 2d69 6020 6f70  tive` or `-i` op
+00018630: 7469 6f6e 2c20 616c 6c6f 7769 6e67 2075  tion, allowing u
+00018640: 7365 7220 7365 6c65 6374 696f 6e73 2074  ser selections t
+00018650: 6f20 6265 206d 6164 652e 2045 2e67 2e2c  o be made. E.g.,
+00018660: 2074 6869 7320 6361 6e20 6265 2075 7365   this can be use
+00018670: 6420 746f 2073 656c 6563 7420 7768 6963  d to select whic
+00018680: 6820 6f62 6a65 6374 2070 6174 6873 2074  h object paths t
+00018690: 6f20 6465 6c65 7465 2e0a 0a54 6865 2060  o delete...The `
+000186a0: 2d2d 7175 6965 7460 206f 7220 602d 7160  --quiet` or `-q`
+000186b0: 206f 7074 696f 6e20 7265 6475 6365 7320   option reduces 
+000186c0: 7468 6520 636f 6d6d 616e 6420 6f75 7470  the command outp
+000186d0: 7574 2064 6f77 6e20 746f 2065 7373 656e  ut down to essen
+000186e0: 7469 616c 206d 6573 7361 6765 7320 6f6e  tial messages on
+000186f0: 6c79 2e20 536f 2c20 666f 7220 6578 616d  ly. So, for exam
+00018700: 706c 652c 2060 7964 2d64 656c 6574 6520  ple, `yd-delete 
+00018710: 2d79 7160 2077 6f75 6c64 2064 656c 6574  -yq` would delet
+00018720: 6520 616c 6c20 6d61 7463 6869 6e67 206f  e all matching o
+00018730: 626a 6563 7420 7061 7468 7320 7369 6c65  bject paths sile
+00018740: 6e74 6c79 2e0a 0a49 6620 796f 7520 656e  ntly...If you en
+00018750: 636f 756e 7465 7220 616e 2065 7272 6f72  counter an error
+00018760: 2069 7420 6361 6e20 6265 2075 7365 6675   it can be usefu
+00018770: 6c20 666f 7220 7375 7070 6f72 7420 7075  l for support pu
+00018780: 7270 6f73 6573 2074 6f20 7365 6520 7468  rposes to see th
+00018790: 6520 6675 6c6c 2050 7974 686f 6e20 7374  e full Python st
+000187a0: 6163 6b20 7472 6163 652e 2054 6869 7320  ack trace. This 
+000187b0: 6361 6e20 6265 2065 6e61 626c 6564 2062  can be enabled b
+000187c0: 7920 7275 6e6e 696e 6720 7468 6520 636f  y running the co
+000187d0: 6d6d 616e 6420 7573 696e 6720 7468 6520  mmand using the 
+000187e0: 602d 2d64 6562 7567 6020 6f70 7469 6f6e  `--debug` option
+000187f0: 2e0a 0a23 2320 7964 2d73 7562 6d69 740a  ...## yd-submit.
+00018800: 0a54 6865 2060 7964 2d73 7562 6d69 7460  .The `yd-submit`
+00018810: 2063 6f6d 6d61 6e64 2073 7562 6d69 7473   command submits
+00018820: 2061 206e 6577 2057 6f72 6b20 5265 7175   a new Work Requ
+00018830: 6972 656d 656e 742c 2061 6363 6f72 6469  irement, accordi
+00018840: 6e67 2074 6f20 7468 6520 576f 726b 2052  ng to the Work R
+00018850: 6571 7569 7265 6d65 6e74 2064 6566 696e  equirement defin
+00018860: 6974 696f 6e20 666f 756e 6420 696e 2074  ition found in t
+00018870: 6865 2060 776f 726b 5265 7175 6972 656d  he `workRequirem
+00018880: 656e 7460 2073 6563 7469 6f6e 206f 6620  ent` section of 
+00018890: 7468 6520 544f 4d4c 2063 6f6e 6669 6775  the TOML configu
+000188a0: 7261 7469 6f6e 2066 696c 6520 616e 642f  ration file and/
+000188b0: 6f72 2074 6865 2073 7065 6369 6669 6361  or the specifica
+000188c0: 7469 6f6e 2066 6f75 6e64 2069 6e20 6120  tion found in a 
+000188d0: 576f 726b 2052 6571 7569 7265 6d65 6e74  Work Requirement
+000188e0: 204a 534f 4e20 646f 6375 6d65 6e74 2073   JSON document s
+000188f0: 7570 706c 6965 6420 7573 696e 6720 7468  upplied using th
+00018900: 6520 602d 2d77 6f72 6b2d 7265 7175 6972  e `--work-requir
+00018910: 656d 656e 7460 206f 7074 696f 6e2e 0a0a  ement` option...
+00018920: 5573 6520 7468 6520 602d 2d64 7279 2d72  Use the `--dry-r
+00018930: 756e 6020 6f70 7469 6f6e 2074 6f20 696e  un` option to in
+00018940: 7370 6563 7420 7468 6520 6465 7461 696c  spect the detail
+00018950: 7320 6f66 2074 6865 2057 6f72 6b20 5265  s of the Work Re
+00018960: 7175 6972 656d 656e 742c 2054 6173 6b20  quirement, Task 
+00018970: 4772 6f75 7073 2c20 616e 6420 5461 736b  Groups, and Task
+00018980: 7320 7468 6174 2077 696c 6c20 6265 2073  s that will be s
+00018990: 7562 6d69 7474 6564 2c20 696e 204a 534f  ubmitted, in JSO
+000189a0: 4e20 666f 726d 6174 2e0a 0a4f 6e63 6520  N format...Once 
+000189b0: 7375 626d 6974 7465 642c 2074 6865 2057  submitted, the W
+000189c0: 6f72 6b20 5265 7175 6972 656d 656e 7420  ork Requirement 
+000189d0: 7769 6c6c 2061 7070 6561 7220 696e 2074  will appear in t
+000189e0: 6865 202a 2a57 6f72 6b2a 2a20 7461 6220  he **Work** tab 
+000189f0: 696e 2074 6865 2059 656c 6c6f 7744 6f67  in the YellowDog
+00018a00: 2050 6f72 7461 6c2e 0a0a 5468 6520 576f   Portal...The Wo
+00018a10: 726b 2052 6571 7569 7265 6d65 6e74 2773  rk Requirement's
+00018a20: 2070 726f 6772 6573 7320 6361 6e20 6265   progress can be
+00018a30: 2074 7261 636b 6564 2074 6f20 636f 6d70   tracked to comp
+00018a40: 6c65 7469 6f6e 2062 7920 7573 696e 6720  letion by using 
+00018a50: 7468 6520 602d 2d66 6f6c 6c6f 7760 2028  the `--follow` (
+00018a60: 6f72 2060 2d66 6029 206f 7074 696f 6e20  or `-f`) option 
+00018a70: 7768 656e 2069 6e76 6f6b 696e 6720 6079  when invoking `y
+00018a80: 642d 7375 626d 6974 603a 2074 6865 2063  d-submit`: the c
+00018a90: 6f6d 6d61 6e64 2077 696c 6c20 7265 706f  ommand will repo
+00018aa0: 7274 206f 6e20 5461 736b 7320 6173 2074  rt on Tasks as t
+00018ab0: 6865 7920 636f 6e63 6c75 6465 2061 6e64  hey conclude and
+00018ac0: 2077 6f6e 2774 2072 6574 7572 6e20 756e   won't return un
+00018ad0: 7469 6c20 7468 6520 576f 726b 2052 6571  til the Work Req
+00018ae0: 7569 7265 6d65 6e74 2068 6173 2066 696e  uirement has fin
+00018af0: 6973 6865 642e 0a0a 2323 2079 642d 7072  ished...## yd-pr
+00018b00: 6f76 6973 696f 6e0a 0a54 6865 2060 7964  ovision..The `yd
+00018b10: 2d70 726f 7669 7369 6f6e 6020 636f 6d6d  -provision` comm
+00018b20: 616e 6420 7072 6f76 6973 696f 6e73 2061  and provisions a
+00018b30: 206e 6577 2057 6f72 6b65 7220 506f 6f6c   new Worker Pool
+00018b40: 2061 6363 6f72 6469 6e67 2074 6f20 7468   according to th
+00018b50: 6520 7370 6563 6966 6963 6174 696f 6e73  e specifications
+00018b60: 2069 6e20 7468 6520 6077 6f72 6b65 7250   in the `workerP
+00018b70: 6f6f 6c60 2073 6563 7469 6f6e 206f 6620  ool` section of 
+00018b80: 7468 6520 544f 4d4c 2063 6f6e 6669 6775  the TOML configu
+00018b90: 7261 7469 6f6e 2066 696c 6520 616e 642f  ration file and/
+00018ba0: 6f72 2069 6e20 7468 6520 7370 6563 6966  or in the specif
+00018bb0: 6963 6174 696f 6e20 666f 756e 6420 696e  ication found in
+00018bc0: 2061 2057 6f72 6b65 7220 506f 6f6c 204a   a Worker Pool J
+00018bd0: 534f 4e20 646f 6375 6d65 6e74 2073 7570  SON document sup
+00018be0: 706c 6965 6420 7573 696e 6720 7468 6520  plied using the 
+00018bf0: 602d 2d77 6f72 6b65 722d 706f 6f6c 6020  `--worker-pool` 
+00018c00: 6f70 7469 6f6e 2e0a 0a55 7365 2074 6865  option...Use the
+00018c10: 2060 2d2d 6472 792d 7275 6e60 206f 7074   `--dry-run` opt
+00018c20: 696f 6e20 746f 2069 6e73 7065 6374 2074  ion to inspect t
+00018c30: 6865 2064 6574 6169 6c73 206f 6620 7468  he details of th
+00018c40: 6520 576f 726b 6572 2050 6f6f 6c20 7370  e Worker Pool sp
+00018c50: 6563 6966 6963 6174 696f 6e20 7468 6174  ecification that
+00018c60: 2077 696c 6c20 6265 2073 7562 6d69 7474   will be submitt
+00018c70: 6564 2c20 696e 204a 534f 4e20 666f 726d  ed, in JSON form
+00018c80: 6174 2e0a 0a4f 6e63 6520 7072 6f76 6973  at...Once provis
+00018c90: 696f 6e65 642c 2074 6865 2057 6f72 6b65  ioned, the Worke
+00018ca0: 7220 506f 6f6c 2077 696c 6c20 6170 7065  r Pool will appe
+00018cb0: 6172 2069 6e20 7468 6520 2a2a 576f 726b  ar in the **Work
+00018cc0: 6572 732a 2a20 7461 6220 696e 2074 6865  ers** tab in the
+00018cd0: 2059 656c 6c6f 7744 6f67 2050 6f72 7461   YellowDog Porta
+00018ce0: 6c2c 2061 6e64 2069 7473 2061 7373 6f63  l, and its assoc
+00018cf0: 6961 7465 6420 436f 6d70 7574 6520 5265  iated Compute Re
+00018d00: 7175 6972 656d 656e 7420 7769 6c6c 2061  quirement will a
+00018d10: 7070 6561 7220 696e 2074 6865 202a 2a43  ppear in the **C
+00018d20: 6f6d 7075 7465 2a2a 2074 6162 2e0a 0a23  ompute** tab...#
+00018d30: 2320 7964 2d63 616e 6365 6c0a 0a54 6865  # yd-cancel..The
+00018d40: 2060 7964 2d63 616e 6365 6c60 2063 6f6d   `yd-cancel` com
+00018d50: 6d61 6e64 2063 616e 6365 6c73 2061 6e79  mand cancels any
+00018d60: 2061 6374 6976 6520 576f 726b 2052 6571   active Work Req
+00018d70: 7569 7265 6d65 6e74 732c 2069 6e63 6c75  uirements, inclu
+00018d80: 6469 6e67 2061 6e79 2070 656e 6469 6e67  ding any pending
+00018d90: 2054 6173 6b20 4772 6f75 7073 2061 6e64   Task Groups and
+00018da0: 2074 6865 2054 6173 6b73 2074 6865 7920   the Tasks they 
+00018db0: 636f 6e74 6169 6e2e 200a 0a54 6865 2060  contain. ..The `
+00018dc0: 6e61 6d65 7370 6163 6560 2061 6e64 2060  namespace` and `
+00018dd0: 7461 6760 2076 616c 7565 7320 696e 2074  tag` values in t
+00018de0: 6865 2060 636f 6e66 6967 2e74 6f6d 6c60  he `config.toml`
+00018df0: 2066 696c 6520 6172 6520 7573 6564 2074   file are used t
+00018e00: 6f20 6964 656e 7469 6679 2077 6869 6368  o identify which
+00018e10: 2057 6f72 6b20 5265 7175 6972 656d 656e   Work Requiremen
+00018e20: 7473 2074 6f20 6361 6e63 656c 2e0a 0a42  ts to cancel...B
+00018e30: 7920 6465 6661 756c 742c 2061 6e79 2054  y default, any T
+00018e40: 6173 6b73 2074 6861 7420 6172 6520 6375  asks that are cu
+00018e50: 7272 656e 746c 7920 7275 6e6e 696e 6720  rrently running 
+00018e60: 6f6e 2057 6f72 6b65 7273 2077 696c 6c20  on Workers will 
+00018e70: 636f 6e74 696e 7565 2074 6f20 7275 6e20  continue to run 
+00018e80: 746f 2063 6f6d 706c 6574 696f 6e20 6f72  to completion or
+00018e90: 2075 6e74 696c 2074 6865 7920 6661 696c   until they fail
+00018ea0: 2e20 5461 736b 7320 6361 6e20 6265 2069  . Tasks can be i
+00018eb0: 6e73 7472 7563 7465 6420 746f 2061 626f  nstructed to abo
+00018ec0: 7274 2069 6d6d 6564 6961 7465 6c79 2062  rt immediately b
+00018ed0: 7920 7375 7070 6c79 696e 6720 7468 6520  y supplying the 
+00018ee0: 602d 2d61 626f 7274 6020 6f72 2060 2d61  `--abort` or `-a
+00018ef0: 6020 6f70 7469 6f6e 2074 6f20 6079 642d  ` option to `yd-
+00018f00: 6361 6e63 656c 602e 0a0a 2323 2079 642d  cancel`...## yd-
+00018f10: 6162 6f72 740a 0a54 6865 2060 7964 2d61  abort..The `yd-a
+00018f20: 626f 7274 6020 636f 6d6d 616e 6420 6973  bort` command is
+00018f30: 2075 7365 6420 746f 2061 626f 7274 2054   used to abort T
+00018f40: 6173 6b73 2074 6861 7420 6172 6520 6375  asks that are cu
+00018f50: 7272 656e 746c 7920 7275 6e6e 696e 672e  rrently running.
+00018f60: 2054 6865 2075 7365 7220 696e 7465 7261   The user intera
+00018f70: 6374 6976 656c 7920 7365 6c65 6374 7320  ctively selects 
+00018f80: 7468 6520 576f 726b 2052 6571 7569 7265  the Work Require
+00018f90: 6d65 6e74 7320 746f 2074 6172 6765 742c  ments to target,
+00018fa0: 2061 6e64 2074 6865 6e20 7768 6963 6820   and then which 
+00018fb0: 5461 736b 7320 7769 7468 696e 2074 686f  Tasks within tho
+00018fc0: 7365 2057 6f72 6b20 5265 7175 6972 656d  se Work Requirem
+00018fd0: 656e 7473 2074 6f20 6162 6f72 742e 2054  ents to abort. T
+00018fe0: 6865 2057 6f72 6b20 5265 7175 6972 656d  he Work Requirem
+00018ff0: 656e 7473 2061 7265 206e 6f74 2063 616e  ents are not can
+00019000: 6365 6c6c 6564 2061 7320 7061 7274 206f  celled as part o
+00019010: 6620 7468 6973 2070 726f 6365 7373 2e0a  f this process..
+00019020: 0a54 6865 2060 6e61 6d65 7370 6163 6560  .The `namespace`
+00019030: 2061 6e64 2060 7461 6760 2076 616c 7565   and `tag` value
+00019040: 7320 696e 2074 6865 2060 636f 6e66 6967  s in the `config
+00019050: 2e74 6f6d 6c60 2066 696c 6520 6172 6520  .toml` file are 
+00019060: 7573 6564 2074 6f20 6964 656e 7469 6679  used to identify
+00019070: 2077 6869 6368 2057 6f72 6b20 5265 7175   which Work Requ
+00019080: 6972 656d 656e 7473 2074 6f20 6c69 7374  irements to list
+00019090: 2066 6f72 2073 656c 6563 7469 6f6e 2e0a   for selection..
+000190a0: 0a23 2320 7964 2d64 6f77 6e6c 6f61 640a  .## yd-download.
+000190b0: 0a54 6865 2060 7964 2d64 6f77 6e6c 6f61  .The `yd-downloa
+000190c0: 6460 2063 6f6d 6d61 6e64 2064 6f77 6e6c  d` command downl
+000190d0: 6f61 6473 2061 6e79 206f 626a 6563 7473  oads any objects
+000190e0: 2063 7265 6174 6564 2069 6e20 7468 6520   created in the 
+000190f0: 5965 6c6c 6f77 446f 6720 4f62 6a65 6374  YellowDog Object
+00019100: 2053 746f 7265 2e0a 0a54 6865 2060 6e61   Store...The `na
+00019110: 6d65 7370 6163 6560 2061 6e64 2060 7461  mespace` and `ta
+00019120: 6760 2076 616c 7565 7320 6172 6520 7573  g` values are us
+00019130: 6564 2074 6f20 6465 7465 726d 696e 6520  ed to determine 
+00019140: 7768 6963 6820 6f62 6a65 6374 7320 746f  which objects to
+00019150: 2064 6f77 6e6c 6f61 642e 204f 626a 6563   download. Objec
+00019160: 7473 2077 696c 6c20 6265 2064 6f77 6e6c  ts will be downl
+00019170: 6f61 6465 6420 746f 2061 2064 6972 6563  oaded to a direc
+00019180: 746f 7279 2077 6974 6820 7468 6520 7361  tory with the sa
+00019190: 6d65 206e 616d 6520 6173 2060 6e61 6d65  me name as `name
+000191a0: 7370 6163 6560 2e20 4966 2061 2064 6972  space`. If a dir
+000191b0: 6563 746f 7279 2061 6c72 6561 6479 2065  ectory already e
+000191c0: 7869 7374 732c 2061 206e 6577 2064 6972  xists, a new dir
+000191d0: 6563 746f 7279 2077 6974 6820 6e61 6d65  ectory with name
+000191e0: 2060 3c6e 616d 6573 7061 6365 3e2e 3031   `<namespace>.01
+000191f0: 6020 2865 7463 2e29 2077 696c 6c20 6265  ` (etc.) will be
+00019200: 2063 7265 6174 6564 2e0a 0a23 2320 7964   created...## yd
+00019210: 2d64 656c 6574 650a 0a54 6865 2060 7964  -delete..The `yd
+00019220: 2d64 656c 6574 6560 2063 6f6d 6d61 6e64  -delete` command
+00019230: 2064 656c 6574 6573 2061 6e79 206f 626a   deletes any obj
+00019240: 6563 7473 2063 7265 6174 6564 2069 6e20  ects created in 
+00019250: 7468 6520 5965 6c6c 6f77 446f 6720 4f62  the YellowDog Ob
+00019260: 6a65 6374 2053 746f 7265 2e0a 0a54 6865  ject Store...The
+00019270: 2060 6e61 6d65 7370 6163 6560 2061 6e64   `namespace` and
+00019280: 2060 7461 6760 2076 616c 7565 7320 696e   `tag` values in
+00019290: 2074 6865 2060 636f 6e66 6967 2e74 6f6d   the `config.tom
+000192a0: 6c60 2066 696c 6520 6172 6520 7573 6564  l` file are used
+000192b0: 2074 6f20 6964 656e 7469 6679 2077 6869   to identify whi
+000192c0: 6368 206f 626a 6563 7473 2074 6f20 6465  ch objects to de
+000192d0: 6c65 7465 2e20 4e6f 7465 2074 6861 7420  lete. Note that 
+000192e0: 6974 2773 2065 6173 7920 746f 2075 7365  it's easy to use
+000192f0: 2060 7964 2d64 656c 6574 6560 2074 6f20   `yd-delete` to 
+00019300: 636c 6561 7220 7468 6520 636f 6e74 656e  clear the conten
+00019310: 7473 206f 6620 6120 6e61 6d65 7370 6163  ts of a namespac
+00019320: 6520 6279 2075 7369 6e67 2061 6e20 656d  e by using an em
+00019330: 7074 7920 6074 6167 602c 2061 7320 666f  pty `tag`, as fo
+00019340: 6c6c 6f77 733a 0a0a 6060 6073 6865 6c6c  llows:..```shell
+00019350: 0a79 642d 6465 6c65 7465 202d 7420 2222  .yd-delete -t ""
+00019360: 0a60 6060 0a0a 5468 6973 2063 616e 2062  .```..This can b
+00019370: 6520 6578 7465 6e64 6564 2074 6f20 616e  e extended to an
+00019380: 7920 6f74 6865 7220 6e61 6d65 7370 6163  y other namespac
+00019390: 6520 6279 2075 7369 6e67 2074 6865 2060  e by using the `
+000193a0: 2d2d 6e61 6d65 7370 6163 6560 2f60 2d6e  --namespace`/`-n
+000193b0: 6020 6f70 7469 6f6e 2e0a 0a23 2320 7964  ` option...## yd
+000193c0: 2d75 706c 6f61 640a 0a54 6865 2060 7964  -upload..The `yd
+000193d0: 2d75 706c 6f61 6460 2063 6f6d 6d61 6e64  -upload` command
+000193e0: 2075 706c 6f61 6473 2066 696c 6573 2066   uploads files f
+000193f0: 726f 6d20 7468 6520 6c6f 6361 6c20 6669  rom the local fi
+00019400: 6c65 7379 7374 656d 2074 6f20 7468 6520  lesystem to the 
+00019410: 5965 6c6c 6f77 446f 6720 4f62 6a65 6374  YellowDog Object
+00019420: 2073 746f 7265 2e20 4669 6c65 7320 6172   store. Files ar
+00019430: 6520 706c 6163 6564 2069 6e20 7468 6520  e placed in the 
+00019440: 636f 6e66 6967 7572 6564 2060 6e61 6d65  configured `name
+00019450: 7370 6163 6560 2077 6974 6869 6e20 6120  space` within a 
+00019460: 6469 7265 6374 6f72 7920 7375 7070 6c69  directory suppli
+00019470: 6564 2075 7369 6e67 2074 6865 2028 7265  ed using the (re
+00019480: 7175 6972 6564 2920 602d 2d64 6972 6563  quired) `--direc
+00019490: 746f 7279 6020 6f70 7469 6f6e 2c20 652e  tory` option, e.
+000194a0: 672e 3a0a 0a60 6060 7368 656c 6c0a 7964  g.:..```shell.yd
+000194b0: 2d75 706c 6f61 6420 2d2d 6469 7265 6374  -upload --direct
+000194c0: 6f72 7920 6d79 5f77 6f72 6b5f 7265 7175  ory my_work_requ
+000194d0: 6972 656d 656e 7420 6669 6c65 5f31 2066  irement file_1 f
+000194e0: 696c 655f 3220 6d6f 7265 6669 6c65 732f  ile_2 morefiles/
+000194f0: 6669 6c65 330a 6060 600a 546f 2073 7570  file3.```.To sup
+00019500: 7072 6573 7320 7468 6520 6d69 7272 6f72  press the mirror
+00019510: 696e 6720 6f66 2074 6865 206c 6f63 616c  ing of the local
+00019520: 2064 6972 6563 746f 7279 2073 7472 7563   directory struc
+00019530: 7475 7265 2077 6974 6869 6e20 7468 6520  ture within the 
+00019540: 6f62 6a65 6374 2073 746f 7265 2c20 7573  object store, us
+00019550: 6520 7468 6520 602d 2d66 6c61 7474 656e  e the `--flatten
+00019560: 2d75 706c 6f61 642d 7061 7468 7360 206f  -upload-paths` o
+00019570: 7220 602d 6660 206f 7074 696f 6e2e 204e  r `-f` option. N
+00019580: 6f74 6520 7468 6174 2069 6620 7468 6973  ote that if this
+00019590: 2063 7265 6174 6573 206d 756c 7469 706c   creates multipl
+000195a0: 6520 7570 6c6f 6164 6564 2066 696c 6573  e uploaded files
+000195b0: 2077 6974 6820 7468 6520 7361 6d65 2070   with the same p
+000195c0: 6174 6820 696e 2074 6865 204f 626a 6563  ath in the Objec
+000195d0: 7420 5374 6f72 6520 666f 6c64 6572 2c20  t Store folder, 
+000195e0: 6669 6c65 7320 7769 6c6c 2062 6520 6f76  files will be ov
+000195f0: 6572 7772 6974 7465 6e2e 0a0a 4669 6c65  erwritten...File
+00019600: 7320 696e 2064 6972 6563 746f 7269 6573  s in directories
+00019610: 206d 6179 2062 6520 7265 6375 7273 6976   may be recursiv
+00019620: 656c 7920 7570 6c6f 6164 6564 2075 7369  ely uploaded usi
+00019630: 6e67 2074 6865 2060 2d2d 7265 6375 7273  ng the `--recurs
+00019640: 6976 6560 206f 7220 602d 7260 206f 7074  ive` or `-r` opt
+00019650: 696f 6e2c 2065 2e67 2e3a 0a0a 6060 6073  ion, e.g.:..```s
+00019660: 6865 6c6c 0a79 642d 7570 6c6f 6164 202d  hell.yd-upload -
+00019670: 2d64 6972 6563 746f 7279 206d 795f 776f  -directory my_wo
+00019680: 726b 5f72 6571 7569 7265 6d65 6e74 202d  rk_requirement -
+00019690: 7220 6d79 6469 7220 6d79 6f74 6865 7264  r mydir myotherd
+000196a0: 6972 0a60 6060 0a0a 546f 2075 706c 6f61  ir.```..To uploa
+000196b0: 6420 746f 206f 7468 6572 206e 616d 6573  d to other names
+000196c0: 7061 6365 732c 2075 7365 2074 6865 2060  paces, use the `
+000196d0: 2d2d 6e61 6d65 7370 6163 6560 2f60 2d6e  --namespace`/`-n
+000196e0: 6020 6f70 7469 6f6e 2e0a 0a23 2320 7964  ` option...## yd
+000196f0: 2d73 6875 7464 6f77 6e0a 0a54 6865 2060  -shutdown..The `
+00019700: 7964 2d73 6875 7464 6f77 6e60 2063 6f6d  yd-shutdown` com
+00019710: 6d61 6e64 2073 6875 7473 2064 6f77 6e20  mand shuts down 
+00019720: 576f 726b 6572 2050 6f6f 6c73 2074 6861  Worker Pools tha
+00019730: 7420 6d61 7463 6820 7468 6520 606e 616d  t match the `nam
+00019740: 6573 7061 6365 6020 616e 6420 6074 6167  espace` and `tag
+00019750: 6020 666f 756e 6420 696e 2074 6865 2063  ` found in the c
+00019760: 6f6e 6669 6775 7261 7469 6f6e 2066 696c  onfiguration fil
+00019770: 652e 2041 6c6c 2072 656d 6169 6e69 6e67  e. All remaining
+00019780: 2077 6f72 6b20 7769 6c6c 2062 6520 6361   work will be ca
+00019790: 6e63 656c 6c65 642c 2062 7574 2063 7572  ncelled, but cur
+000197a0: 7265 6e74 6c79 2065 7865 6375 7469 6e67  rently executing
+000197b0: 2054 6173 6b73 2077 696c 6c20 6265 2061   Tasks will be a
+000197c0: 6c6c 6f77 6564 2074 6f20 636f 6d70 6c65  llowed to comple
+000197d0: 7465 2c20 6166 7465 7220 7768 6963 6820  te, after which 
+000197e0: 7468 6520 436f 6d70 7574 6520 5265 7175  the Compute Requ
+000197f0: 6972 656d 656e 7420 7769 6c6c 2062 6520  irement will be 
+00019800: 7465 726d 696e 6174 6564 2e0a 0a23 2320  terminated...## 
+00019810: 7964 2d69 6e73 7461 6e74 6961 7465 0a0a  yd-instantiate..
+00019820: 5468 6520 6079 642d 696e 7374 616e 7469  The `yd-instanti
+00019830: 6174 6560 2063 6f6d 6d61 6e64 2069 6e73  ate` command ins
+00019840: 7461 6e74 6961 7465 7320 6120 436f 6d70  tantiates a Comp
+00019850: 7574 6520 5265 7175 6972 656d 656e 7420  ute Requirement 
+00019860: 2869 2e65 2e2c 2061 2073 6574 206f 6620  (i.e., a set of 
+00019870: 696e 7374 616e 6365 7320 7468 6174 2061  instances that a
+00019880: 7265 206d 616e 6167 6564 2062 7920 7468  re managed by th
+00019890: 6569 7220 6372 6561 746f 7220 616e 6420  eir creator and 
+000198a0: 646f 206e 6f74 2061 7574 6f6d 6174 6963  do not automatic
+000198b0: 616c 6c79 2062 6563 6f6d 6520 7061 7274  ally become part
+000198c0: 206f 6620 6120 5965 6c6c 6f77 446f 6720   of a YellowDog 
+000198d0: 576f 726b 6572 2050 6f6f 6c29 2e0a 0a54  Worker Pool)...T
+000198e0: 6869 7320 636f 6d6d 616e 6420 7573 6573  his command uses
+000198f0: 2074 6865 2064 6174 6120 6672 6f6d 2074   the data from t
+00019900: 6865 2060 776f 726b 6572 506f 6f6c 6020  he `workerPool` 
+00019910: 636f 6e66 6967 7572 6174 696f 6e20 7365  configuration se
+00019920: 6374 696f 6e2c 2062 7574 206f 6e6c 7920  ction, but only 
+00019930: 7573 6573 2074 6865 2060 6e61 6d65 602c  uses the `name`,
+00019940: 2060 7465 6d70 6c61 7465 4964 602c 2060   `templateId`, `
+00019950: 7461 7267 6574 496e 7374 616e 6365 436f  targetInstanceCo
+00019960: 756e 7460 2c20 6069 6e73 7461 6e63 6554  unt`, `instanceT
+00019970: 6167 7360 2c20 6075 7365 7244 6174 6160  ags`, `userData`
+00019980: 2c20 616e 6420 6069 6d61 6765 7349 6460  , and `imagesId`
+00019990: 2070 726f 7065 7274 6965 732e 2049 6e20   properties. In 
+000199a0: 6164 6469 7469 6f6e 2c20 7468 6520 426f  addition, the Bo
+000199b0: 6f6c 6561 6e20 7072 6f70 6572 7479 2060  olean property `
+000199c0: 6d61 696e 7461 696e 496e 7374 616e 6365  maintainInstance
+000199d0: 436f 756e 7460 2028 6465 6661 756c 7420  Count` (default 
+000199e0: 3d20 6066 616c 7365 6029 2069 7320 6176  = `false`) is av
+000199f0: 6169 6c61 626c 6520 666f 7220 7573 6520  ailable for use 
+00019a00: 7769 7468 2060 7964 2d69 6e73 7461 6e74  with `yd-instant
+00019a10: 6961 7465 602e 0a0a 436f 6d70 7574 6520  iate`...Compute 
+00019a20: 5265 7175 6972 656d 656e 7473 2063 616e  Requirements can
+00019a30: 2062 6520 696e 7374 616e 7469 6174 6564   be instantiated
+00019a40: 2064 6972 6563 746c 7920 6672 6f6d 204a   directly from J
+00019a50: 534f 4e20 286f 7220 4a73 6f6e 6e65 7429  SON (or Jsonnet)
+00019a60: 2073 7065 6369 6669 6361 7469 6f6e 732c   specifications,
+00019a70: 2075 7369 6e67 2074 6865 2060 2d2d 636f   using the `--co
+00019a80: 6d70 7574 652d 7265 7175 6972 656d 656e  mpute-requiremen
+00019a90: 7460 2028 6f72 2060 2d43 6029 2063 6f6d  t` (or `-C`) com
+00019aa0: 6d61 6e64 206c 696e 6520 6f70 7469 6f6e  mand line option
+00019ab0: 2c20 666f 6c6c 6f77 6564 2062 7920 7468  , followed by th
+00019ac0: 6520 6669 6c65 6e61 6d65 2e20 5468 6520  e filename. The 
+00019ad0: 7072 6f70 6572 7469 6573 206c 6973 7465  properties liste
+00019ae0: 6420 6162 6f76 6520 7769 6c6c 2062 6520  d above will be 
+00019af0: 696e 6865 7269 7465 6420 6672 6f6d 2074  inherited from t
+00019b00: 6865 2063 6f6e 6669 672e 746f 6d6c 2060  he config.toml `
+00019b10: 776f 726b 6572 506f 6f6c 6020 7370 6563  workerPool` spec
+00019b20: 6966 6963 6174 696f 6e20 6966 2074 6865  ification if the
+00019b30: 7920 6172 6520 6e6f 7420 7072 6573 656e  y are not presen
+00019b40: 7420 696e 2074 6865 204a 534f 4e20 6669  t in the JSON fi
+00019b50: 6c65 2e20 416e 2065 7861 6d70 6c65 204a  le. An example J
+00019b60: 534f 4e20 7370 6563 6966 6963 6174 696f  SON specificatio
+00019b70: 6e20 6973 2073 686f 776e 2062 656c 6f77  n is shown below
+00019b80: 3a0a 0a60 6060 6a73 6f6e 0a7b 0a20 2022  :..```json.{.  "
+00019b90: 696d 6167 6573 4964 223a 2022 7964 6964  imagesId": "ydid
+00019ba0: 3a69 6d67 6661 6d3a 3030 3030 3030 3a34  :imgfam:000000:4
+00019bb0: 3139 3632 3539 322d 3537 3763 2d34 6664  1962592-577c-4fd
+00019bc0: 652d 6162 3033 2d64 3835 3234 3635 6537  e-ab03-d852465e7
+00019bd0: 6638 6222 2c0a 2020 2269 6e73 7461 6e63  f8b",.  "instanc
+00019be0: 6554 6167 7322 3a20 7b22 6131 223a 2022  eTags": {"a1": "
+00019bf0: 6f6e 6522 2c20 2261 3222 3a20 2274 776f  one", "a2": "two
+00019c00: 227d 2c0a 2020 2272 6571 7569 7265 6d65  "},.  "requireme
+00019c10: 6e74 4e61 6d65 223a 2022 6372 5f74 6573  ntName": "cr_tes
+00019c20: 745f 7b7b 6461 7465 7469 6d65 7d7d 222c  t_{{datetime}}",
+00019c30: 0a20 2022 7265 7175 6972 656d 656e 744e  .  "requirementN
+00019c40: 616d 6573 7061 6365 223a 2022 7079 6578  amespace": "pyex
+00019c50: 616d 706c 6573 222c 0a20 2022 7265 7175  amples",.  "requ
+00019c60: 6972 656d 656e 7454 6167 223a 2022 7079  irementTag": "py
+00019c70: 6578 616d 706c 6573 2d74 6573 7422 2c0a  examples-test",.
+00019c80: 2020 2274 656d 706c 6174 6549 6422 3a20    "templateId": 
+00019c90: 2279 6469 643a 6372 743a 3030 3030 3030  "ydid:crt:000000
+00019ca0: 3a32 3330 6539 6134 322d 3937 6462 2d34  :230e9a42-97db-4
+00019cb0: 6436 392d 6161 3931 2d32 3966 6633 3039  d69-aa91-29ff309
+00019cc0: 3935 3162 3422 2c0a 2020 2275 7365 7244  951b4",.  "userD
+00019cd0: 6174 6122 3a20 2223 2f62 696e 2f62 6173  ata": "#/bin/bas
+00019ce0: 685c 6e23 4f74 6865 7220 7374 7566 662e  h\n#Other stuff.
+00019cf0: 2e2e 222c 0a20 2022 7461 7267 6574 496e  ..",.  "targetIn
+00019d00: 7374 616e 6365 436f 756e 7422 3a20 312c  stanceCount": 1,
+00019d10: 0a20 2022 6d61 696e 7461 696e 496e 7374  .  "maintainInst
+00019d20: 616e 6365 436f 756e 7422 3a20 7472 7565  anceCount": true
+00019d30: 0a7d 0a60 6060 0a0a 4966 2061 2057 6f72  .}.```..If a Wor
+00019d40: 6b65 7220 506f 6f6c 2069 7320 6465 6669  ker Pool is defi
+00019d50: 6e65 642c 2075 7369 6e67 2060 776f 726b  ned, using `work
+00019d60: 6572 506f 6f6c 4461 7461 6020 696e 2074  erPoolData` in t
+00019d70: 6865 2063 6f6e 6669 6775 7261 7469 6f6e  he configuration
+00019d80: 2066 696c 6520 6f72 2062 7920 7573 696e   file or by usin
+00019d90: 6720 7468 6520 602d 2d77 6f72 6b65 722d  g the `--worker-
+00019da0: 706f 6f6c 6020 286f 7220 602d 7060 2920  pool` (or `-p`) 
+00019db0: 6f70 7469 6f6e 2c20 6079 642d 696e 7374  option, `yd-inst
+00019dc0: 616e 7469 6174 6560 2077 696c 6c20 6578  antiate` will ex
+00019dd0: 7472 6163 7420 7468 6520 436f 6d70 7574  tract the Comput
+00019de0: 6520 5265 7175 6972 656d 656e 7420 6672  e Requirement fr
+00019df0: 6f6d 2074 6865 2057 6f72 6b65 7220 506f  om the Worker Po
+00019e00: 6f6c 2073 7065 6369 6669 6361 7469 6f6e  ol specification
+00019e10: 2028 6967 6e6f 7269 6e67 2057 6f72 6b65   (ignoring Worke
+00019e20: 722d 506f 6f6c 2d73 7065 6369 6669 6320  r-Pool-specific 
+00019e30: 6461 7461 292c 2061 6e64 2075 7365 2074  data), and use t
+00019e40: 6861 7420 666f 7220 696e 7374 616e 7469  hat for instanti
+00019e50: 6174 696e 6720 7468 6520 436f 6d70 7574  ating the Comput
+00019e60: 6520 5265 7175 6972 656d 656e 742e 0a0a  e Requirement...
+00019e70: 5573 6520 7468 6520 602d 2d64 7279 2d72  Use the `--dry-r
+00019e80: 756e 6020 6f70 7469 6f6e 2074 6f20 696e  un` option to in
+00019e90: 7370 6563 7420 7468 6520 6465 7461 696c  spect the detail
+00019ea0: 7320 6f66 2074 6865 2043 6f6d 7075 7465  s of the Compute
+00019eb0: 2052 6571 7569 7265 6d65 6e74 2073 7065   Requirement spe
+00019ec0: 6369 6669 6361 7469 6f6e 2074 6861 7420  cification that 
+00019ed0: 7769 6c6c 2062 6520 7375 626d 6974 7465  will be submitte
+00019ee0: 642c 2069 6e20 4a53 4f4e 2066 6f72 6d61  d, in JSON forma
+00019ef0: 742e 2054 6865 204a 534f 4e20 6f75 7470  t. The JSON outp
+00019f00: 7574 206f 6620 7468 6973 2063 6f6d 6d61  ut of this comma
+00019f10: 6e64 2063 616e 2062 6520 7573 6564 2077  nd can be used w
+00019f20: 6974 6820 7468 6520 602d 4360 206f 7074  ith the `-C` opt
+00019f30: 696f 6e20 6162 6f76 6520 286f 7220 7769  ion above (or wi
+00019f40: 7468 2060 2d70 6020 666f 7220 576f 726b  th `-p` for Work
+00019f50: 6572 2050 6f6f 6c20 7370 6563 6966 6963  er Pool specific
+00019f60: 6174 696f 6e73 292e 0a0a 2323 2320 5465  ations)...### Te
+00019f70: 7374 2d52 756e 6e69 6e67 2061 2044 796e  st-Running a Dyn
+00019f80: 616d 6963 2054 656d 706c 6174 650a 0a57  amic Template..W
+00019f90: 6865 6e20 6120 7468 6520 6074 656d 706c  hen a the `templ
+00019fa0: 6174 6549 6460 206f 6620 6120 4479 6e61  ateId` of a Dyna
+00019fb0: 6d69 6320 5265 7175 6972 656d 656e 7420  mic Requirement 
+00019fc0: 6973 2075 7365 642c 2074 6865 2060 7964  is used, the `yd
+00019fd0: 2d69 6e73 7461 6e74 6961 7465 6020 636f  -instantiate` co
+00019fe0: 6d6d 616e 6420 6361 6e20 6265 2075 7365  mmand can be use
+00019ff0: 6420 746f 2072 6570 6f72 7420 6f6e 2061  d to report on a
+0001a000: 2074 6573 7420 7275 6e20 6f66 2074 6865   test run of the
+0001a010: 2054 656d 706c 6174 652c 2075 7369 6e67   Template, using
+0001a020: 2074 6865 2060 2d2d 7265 706f 7274 6020   the `--report` 
+0001a030: 286f 7220 602d 7260 2920 636f 6d6d 616e  (or `-r`) comman
+0001a040: 6420 6c69 6e65 206f 7074 696f 6e2e 2054  d line option. T
+0001a050: 6869 7320 6361 6e20 6265 2075 7365 6420  his can be used 
+0001a060: 7769 7468 2054 4f4d 4c2d 6465 6669 6e65  with TOML-define
+0001a070: 6420 436f 6d70 7574 6520 5265 7175 6972  d Compute Requir
+0001a080: 656d 656e 7420 7370 6563 6966 6963 6174  ement specificat
+0001a090: 696f 6e73 2c20 6275 7420 6e6f 7420 7468  ions, but not th
+0001a0a0: 6f73 6520 7468 6174 2061 7265 204a 534f  ose that are JSO
+0001a0b0: 4e2d 6465 6669 6e65 642e 0a0a 4e6f 2069  N-defined...No i
+0001a0c0: 6e73 7461 6e63 6573 2077 696c 6c20 6265  nstances will be
+0001a0d0: 2070 726f 7669 7369 6f6e 6564 2064 7572   provisioned dur
+0001a0e0: 696e 6720 7468 6520 7465 7374 2072 756e  ing the test run
+0001a0f0: 2e0a 0a46 6f72 2065 7861 6d70 6c65 3a0a  ...For example:.
+0001a100: 0a60 6060 7368 656c 6c0a 2520 7964 2d69  .```shell.% yd-i
+0001a110: 6e73 7461 6e74 6961 7465 202d 2d72 6570  nstantiate --rep
+0001a120: 6f72 7420 2d2d 7175 6965 740a 0ae2 948c  ort --quiet.....
+0001a130: e294 80e2 9480 e294 80e2 9480 e294 ace2  ................
 0001a140: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a150: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a160: e294 80e2 9480 e294 80e2 9480 e294 ace2  ................
+0001a150: 80e2 9480 e294 80e2 94ac e294 80e2 9480  ................
+0001a160: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001a170: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a180: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a190: e294 ace2 9480 e294 80e2 9480 e294 80e2  ................
+0001a180: ace2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a190: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001a1a0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001a1b0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001a1c0: e294 80e2 94ac e294 80e2 9480 e294 80e2  ................
 0001a1d0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a1e0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a1e0: 80e2 9480 e294 80e2 94ac e294 80e2 9480  ................
 0001a1f0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a200: 9490 0ae2 9482 2020 2020 e294 8220 2020  ......    ...   
-0001a210: 5261 6e6b 20e2 9482 2050 726f 7669 6465  Rank ... Provide
-0001a220: 7220 2020 e294 8220 5479 7065 2020 2020  r   ... Type    
-0001a230: 2020 2020 2020 2020 2020 2020 20e2 9482               ...
-0001a240: 2052 6567 696f 6e20 2020 20e2 9482 2049   Region    ... I
-0001a250: 6e73 7461 6e63 6554 7970 6520 2020 e294  nstanceType   ..
-0001a260: 8220 536f 7572 6365 204e 616d 6520 2020  . Source Name   
-0001a270: 2020 2020 e294 820a e294 9ce2 9480 e294      ............
-0001a280: 80e2 9480 e294 80e2 94bc e294 80e2 9480  ................
-0001a290: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a2a0: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
-0001a2b0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a2c0: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
-0001a2d0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a2e0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a2f0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a200: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a210: 80e2 9480 e294 80e2 9480 e294 ace2 9480  ................
+0001a220: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a230: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a240: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a250: e294 80e2 9480 e294 900a e294 8220 2020  .............   
+0001a260: 20e2 9482 2020 2052 616e 6b20 e294 8220   ...   Rank ... 
+0001a270: 5072 6f76 6964 6572 2020 20e2 9482 2054  Provider   ... T
+0001a280: 7970 6520 2020 2020 2020 2020 2020 2020  ype             
+0001a290: 2020 2020 e294 8220 5265 6769 6f6e 2020      ... Region  
+0001a2a0: 2020 e294 8220 496e 7374 616e 6365 5479    ... InstanceTy
+0001a2b0: 7065 2020 20e2 9482 2053 6f75 7263 6520  pe   ... Source 
+0001a2c0: 4e61 6d65 2020 2020 2020 20e2 9482 0ae2  Name       .....
+0001a2d0: 949c e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a2e0: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a2f0: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
 0001a300: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a310: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a320: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a330: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
+0001a310: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a320: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
+0001a330: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001a340: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001a350: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001a360: 9480 e294 80e2 94bc e294 80e2 9480 e294  ................
 0001a370: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a380: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a380: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
 0001a390: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a3a0: 80e2 94a4 0ae2 9482 2020 3120 e294 8220  ........  1 ... 
-0001a3b0: 2020 2020 2031 20e2 9482 2041 5753 2020       1 ... AWS  
-0001a3c0: 2020 2020 2020 e294 8220 4177 7353 706f        ... AwsSpo
-0001a3d0: 7443 6f6d 7075 7465 536f 7572 6365 20e2  tComputeSource .
-0001a3e0: 9482 2065 752d 7765 7374 2d32 20e2 9482  .. eu-west-2 ...
-0001a3f0: 2074 3361 2e6e 616e 6f20 2020 2020 2020   t3a.nano       
-0001a400: e294 8220 6177 7373 706f 742d 6575 2d77  ... awsspot-eu-w
-0001a410: 6573 742d 3220 e294 820a e294 9ce2 9480  est-2 ..........
-0001a420: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
-0001a430: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a440: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
-0001a450: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a460: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
-0001a470: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a480: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a490: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a3a0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a3b0: e294 80e2 9480 e294 80e2 9480 e294 bce2  ................
+0001a3c0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a3d0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a3e0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a3f0: 9480 e294 80e2 9480 e294 a40a e294 8220  ............... 
+0001a400: 2031 20e2 9482 2020 2020 2020 3120 e294   1 ...      1 ..
+0001a410: 8220 4157 5320 2020 2020 2020 20e2 9482  . AWS        ...
+0001a420: 2041 7773 5370 6f74 436f 6d70 7574 6553   AwsSpotComputeS
+0001a430: 6f75 7263 6520 e294 8220 6575 2d77 6573  ource ... eu-wes
+0001a440: 742d 3220 e294 8220 7433 612e 6e61 6e6f  t-2 ... t3a.nano
+0001a450: 2020 2020 2020 20e2 9482 2061 7773 7370         ... awssp
+0001a460: 6f74 2d65 752d 7765 7374 2d32 20e2 9482  ot-eu-west-2 ...
+0001a470: 0ae2 949c e294 80e2 9480 e294 80e2 9480  ................
+0001a480: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
+0001a490: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
 0001a4a0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a4b0: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
-0001a4c0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a4d0: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
+0001a4b0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a4c0: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
+0001a4d0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001a4e0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001a4f0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001a500: 80e2 9480 e294 80e2 94bc e294 80e2 9480  ................
 0001a510: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a520: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a520: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
 0001a530: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a540: e294 80e2 94a4 0ae2 9482 2020 3220 e294  ..........  2 ..
-0001a550: 8220 2020 2020 2032 20e2 9482 2041 5753  .      2 ... AWS
-0001a560: 2020 2020 2020 2020 e294 8220 4177 7353          ... AwsS
-0001a570: 706f 7443 6f6d 7075 7465 536f 7572 6365  potComputeSource
-0001a580: 20e2 9482 2065 752d 7765 7374 2d32 20e2   ... eu-west-2 .
-0001a590: 9482 2074 3361 2e6d 6963 726f 2020 2020  .. t3a.micro    
-0001a5a0: 2020 e294 8220 6177 7373 706f 742d 6575    ... awsspot-eu
-0001a5b0: 2d77 6573 742d 3220 e294 820a e294 9ce2  -west-2 ........
-0001a5c0: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
-0001a5d0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a5e0: e294 80e2 9480 e294 bce2 9480 e294 80e2  ................
-0001a5f0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a600: 80e2 9480 e294 80e2 9480 e294 80e2 94bc  ................
-0001a610: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a620: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a630: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a540: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a550: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a560: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a570: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a580: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a590: 80e2 9480 e294 80e2 9480 e294 a40a e294  ................
+0001a5a0: 8220 2032 20e2 9482 2020 2020 2020 3220  .  2 ...      2 
+0001a5b0: e294 8220 4157 5320 2020 2020 2020 20e2  ... AWS        .
+0001a5c0: 9482 2041 7773 5370 6f74 436f 6d70 7574  .. AwsSpotComput
+0001a5d0: 6553 6f75 7263 6520 e294 8220 6575 2d77  eSource ... eu-w
+0001a5e0: 6573 742d 3220 e294 8220 7433 612e 6d69  est-2 ... t3a.mi
+0001a5f0: 6372 6f20 2020 2020 20e2 9482 2061 7773  cro      ... aws
+0001a600: 7370 6f74 2d65 752d 7765 7374 2d32 20e2  spot-eu-west-2 .
+0001a610: 9482 0ae2 949c e294 80e2 9480 e294 80e2  ................
+0001a620: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
+0001a630: 80e2 9480 e294 80e2 9480 e294 80e2 94bc  ................
 0001a640: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a650: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
-0001a660: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a670: e294 80e2 9480 e294 bce2 9480 e294 80e2  ................
+0001a650: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a660: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
+0001a670: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001a680: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001a690: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001a6a0: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
 0001a6b0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a6c0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a6c0: 80e2 9480 e294 80e2 9480 e294 80e2 94bc  ................
 0001a6d0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a6e0: 9480 e294 80e2 94a4 0ae2 9482 2020 3320  ............  3 
-0001a6f0: e294 8220 2020 2020 2033 20e2 9482 2041  ...      3 ... A
-0001a700: 5753 2020 2020 2020 2020 e294 8220 4177  WS        ... Aw
-0001a710: 7353 706f 7443 6f6d 7075 7465 536f 7572  sSpotComputeSour
-0001a720: 6365 20e2 9482 2065 752d 7765 7374 2d32  ce ... eu-west-2
-0001a730: 20e2 9482 2074 3361 2e73 6d61 6c6c 2020   ... t3a.small  
-0001a740: 2020 2020 e294 8220 6177 7373 706f 742d      ... awsspot-
-0001a750: 6575 2d77 6573 742d 3220 e294 820a e294  eu-west-2 ......
-0001a760: 9ce2 9480 e294 80e2 9480 e294 80e2 94bc  ................
-0001a770: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a780: 9480 e294 80e2 9480 e294 bce2 9480 e294  ................
-0001a790: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a7a0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a7b0: 94bc e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a7c0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a6e0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a6f0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a700: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
+0001a710: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a720: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a730: e294 80e2 9480 e294 80e2 9480 e294 a40a  ................
+0001a740: e294 8220 2033 20e2 9482 2020 2020 2020  ...  3 ...      
+0001a750: 3320 e294 8220 4157 5320 2020 2020 2020  3 ... AWS       
+0001a760: 20e2 9482 2041 7773 5370 6f74 436f 6d70   ... AwsSpotComp
+0001a770: 7574 6553 6f75 7263 6520 e294 8220 6575  uteSource ... eu
+0001a780: 2d77 6573 742d 3220 e294 8220 7433 612e  -west-2 ... t3a.
+0001a790: 736d 616c 6c20 2020 2020 20e2 9482 2061  small      ... a
+0001a7a0: 7773 7370 6f74 2d65 752d 7765 7374 2d32  wsspot-eu-west-2
+0001a7b0: 20e2 9482 0ae2 949c e294 80e2 9480 e294   ...............
+0001a7c0: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
 0001a7d0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a7e0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a7f0: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
-0001a800: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a810: 9480 e294 80e2 9480 e294 bce2 9480 e294  ................
+0001a7e0: 94bc e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a7f0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a800: e294 80e2 9480 e294 bce2 9480 e294 80e2  ................
+0001a810: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001a820: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001a830: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001a840: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
 0001a850: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001a860: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a870: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a880: 80e2 9480 e294 80e2 94a4 0ae2 9482 2020  ..............  
-0001a890: 3420 e294 8220 2020 2020 2034 20e2 9482  4 ...      4 ...
-0001a8a0: 2041 5753 2020 2020 2020 2020 e294 8220   AWS        ... 
-0001a8b0: 4177 7353 706f 7443 6f6d 7075 7465 536f  AwsSpotComputeSo
-0001a8c0: 7572 6365 20e2 9482 2065 752d 7765 7374  urce ... eu-west
-0001a8d0: 2d32 20e2 9482 2063 3561 2e6c 6172 6765  -2 ... c5a.large
-0001a8e0: 2020 2020 2020 e294 8220 6177 7373 706f        ... awsspo
-0001a8f0: 742d 6575 2d77 6573 742d 3220 e294 820a  t-eu-west-2 ....
-0001a900: e294 9ce2 9480 e294 80e2 9480 e294 80e2  ................
-0001a910: 94bc e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a920: 80e2 9480 e294 80e2 9480 e294 bce2 9480  ................
-0001a930: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001a940: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a950: 80e2 94bc e294 80e2 9480 e294 80e2 9480  ................
-0001a960: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a870: 94bc e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a880: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a890: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a8a0: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
+0001a8b0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001a8c0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a8d0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001a8e0: a40a e294 8220 2034 20e2 9482 2020 2020  .....  4 ...    
+0001a8f0: 2020 3420 e294 8220 4157 5320 2020 2020    4 ... AWS     
+0001a900: 2020 20e2 9482 2041 7773 5370 6f74 436f     ... AwsSpotCo
+0001a910: 6d70 7574 6553 6f75 7263 6520 e294 8220  mputeSource ... 
+0001a920: 6575 2d77 6573 742d 3220 e294 8220 6335  eu-west-2 ... c5
+0001a930: 612e 6c61 7267 6520 2020 2020 20e2 9482  a.large      ...
+0001a940: 2061 7773 7370 6f74 2d65 752d 7765 7374   awsspot-eu-west
+0001a950: 2d32 20e2 9482 0ae2 949c e294 80e2 9480  -2 .............
+0001a960: e294 80e2 9480 e294 bce2 9480 e294 80e2  ................
 0001a970: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a980: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001a990: e294 80e2 9480 e294 bce2 9480 e294 80e2  ................
-0001a9a0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001a9b0: 80e2 9480 e294 80e2 9480 e294 bce2 9480  ................
+0001a980: 80e2 94bc e294 80e2 9480 e294 80e2 9480  ................
+0001a990: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001a9a0: 9480 e294 80e2 9480 e294 bce2 9480 e294  ................
+0001a9b0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001a9c0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001a9d0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001a9e0: 80e2 9480 e294 80e2 9480 e294 80e2 94bc  ................
 0001a9f0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001aa00: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001aa10: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001aa20: e294 80e2 9480 e294 80e2 94a4 0ae2 9482  ................
-0001aa30: 2020 3520 e294 8220 2020 2020 2034 20e2    5 ...      4 .
-0001aa40: 9482 2041 5753 2020 2020 2020 2020 e294  .. AWS        ..
-0001aa50: 8220 4177 7353 706f 7443 6f6d 7075 7465  . AwsSpotCompute
-0001aa60: 536f 7572 6365 20e2 9482 2065 752d 7765  Source ... eu-we
-0001aa70: 7374 2d32 20e2 9482 2063 3661 2e6c 6172  st-2 ... c6a.lar
-0001aa80: 6765 2020 2020 2020 e294 8220 6177 7373  ge      ... awss
-0001aa90: 706f 742d 6575 2d77 6573 742d 3220 e294  pot-eu-west-2 ..
-0001aaa0: 820a e294 9ce2 9480 e294 80e2 9480 e294  ................
-0001aab0: 80e2 94bc e294 80e2 9480 e294 80e2 9480  ................
-0001aac0: e294 80e2 9480 e294 80e2 9480 e294 bce2  ................
-0001aad0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001aae0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001aaf0: e294 80e2 94bc e294 80e2 9480 e294 80e2  ................
-0001ab00: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001aa10: 80e2 94bc e294 80e2 9480 e294 80e2 9480  ................
+0001aa20: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001aa30: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001aa40: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
+0001aa50: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001aa60: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001aa70: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001aa80: e294 a40a e294 8220 2035 20e2 9482 2020  .......  5 ...  
+0001aa90: 2020 2020 3420 e294 8220 4157 5320 2020      4 ... AWS   
+0001aaa0: 2020 2020 20e2 9482 2041 7773 5370 6f74       ... AwsSpot
+0001aab0: 436f 6d70 7574 6553 6f75 7263 6520 e294  ComputeSource ..
+0001aac0: 8220 6575 2d77 6573 742d 3220 e294 8220  . eu-west-2 ... 
+0001aad0: 6336 612e 6c61 7267 6520 2020 2020 20e2  c6a.large      .
+0001aae0: 9482 2061 7773 7370 6f74 2d65 752d 7765  .. awsspot-eu-we
+0001aaf0: 7374 2d32 20e2 9482 0ae2 949c e294 80e2  st-2 ...........
+0001ab00: 9480 e294 80e2 9480 e294 bce2 9480 e294  ................
 0001ab10: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001ab20: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001ab30: 9480 e294 80e2 9480 e294 bce2 9480 e294  ................
-0001ab40: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001ab50: e294 80e2 9480 e294 80e2 9480 e294 bce2  ................
+0001ab20: e294 80e2 94bc e294 80e2 9480 e294 80e2  ................
+0001ab30: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001ab40: 80e2 9480 e294 80e2 9480 e294 bce2 9480  ................
+0001ab50: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001ab60: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001ab70: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001ab80: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001ab90: 94bc e294 80e2 9480 e294 80e2 9480 e294  ................
 0001aba0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001abb0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001abc0: 9480 e294 80e2 9480 e294 80e2 94a4 0ae2  ................
-0001abd0: 9482 2020 3620 e294 8220 2020 2020 2034  ..  6 ...      4
-0001abe0: 20e2 9482 2041 5753 2020 2020 2020 2020   ... AWS        
-0001abf0: e294 8220 4177 7353 706f 7443 6f6d 7075  ... AwsSpotCompu
-0001ac00: 7465 536f 7572 6365 20e2 9482 2065 752d  teSource ... eu-
-0001ac10: 7765 7374 2d32 20e2 9482 2074 3361 2e6d  west-2 ... t3a.m
-0001ac20: 6564 6975 6d20 2020 2020 e294 8220 6177  edium     ... aw
-0001ac30: 7373 706f 742d 6575 2d77 6573 742d 3220  sspot-eu-west-2 
-0001ac40: e294 820a e294 9ce2 9480 e294 80e2 9480  ................
-0001ac50: e294 80e2 94bc e294 80e2 9480 e294 80e2  ................
-0001ac60: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001ac70: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001ac80: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001ac90: 9480 e294 80e2 94bc e294 80e2 9480 e294  ................
-0001aca0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001abb0: e294 80e2 94bc e294 80e2 9480 e294 80e2  ................
+0001abc0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001abd0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001abe0: e294 80e2 9480 e294 bce2 9480 e294 80e2  ................
+0001abf0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001ac00: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001ac10: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001ac20: 9480 e294 a40a e294 8220 2036 20e2 9482  .........  6 ...
+0001ac30: 2020 2020 2020 3420 e294 8220 4157 5320        4 ... AWS 
+0001ac40: 2020 2020 2020 20e2 9482 2041 7773 5370         ... AwsSp
+0001ac50: 6f74 436f 6d70 7574 6553 6f75 7263 6520  otComputeSource 
+0001ac60: e294 8220 6575 2d77 6573 742d 3220 e294  ... eu-west-2 ..
+0001ac70: 8220 7433 612e 6d65 6469 756d 2020 2020  . t3a.medium    
+0001ac80: 20e2 9482 2061 7773 7370 6f74 2d65 752d   ... awsspot-eu-
+0001ac90: 7765 7374 2d32 20e2 9482 0ae2 949c e294  west-2 .........
+0001aca0: 80e2 9480 e294 80e2 9480 e294 bce2 9480  ................
 0001acb0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001acc0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001acd0: 80e2 9480 e294 80e2 9480 e294 bce2 9480  ................
-0001ace0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001acc0: 9480 e294 80e2 94bc e294 80e2 9480 e294  ................
+0001acd0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001ace0: e294 80e2 9480 e294 80e2 9480 e294 bce2  ................
 0001acf0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001ad00: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001ad00: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001ad10: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001ad20: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001ad30: 80e2 94bc e294 80e2 9480 e294 80e2 9480  ................
 0001ad40: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001ad50: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001ad60: 80e2 9480 e294 80e2 9480 e294 80e2 94a4  ................
-0001ad70: 0ae2 9482 2020 3720 e294 8220 2020 2020  ....  7 ...     
-0001ad80: 2035 20e2 9482 2041 5753 2020 2020 2020   5 ... AWS      
-0001ad90: 2020 e294 8220 4177 7353 706f 7443 6f6d    ... AwsSpotCom
-0001ada0: 7075 7465 536f 7572 6365 20e2 9482 2065  puteSource ... e
-0001adb0: 752d 7765 7374 2d32 20e2 9482 206d 3561  u-west-2 ... m5a
-0001adc0: 2e6c 6172 6765 2020 2020 2020 e294 8220  .large      ... 
-0001add0: 6177 7373 706f 742d 6575 2d77 6573 742d  awsspot-eu-west-
-0001ade0: 3220 e294 820a e294 9ce2 9480 e294 80e2  2 ..............
-0001adf0: 9480 e294 80e2 94bc e294 80e2 9480 e294  ................
-0001ae00: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001ae10: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
-0001ae20: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001ae30: 80e2 9480 e294 80e2 94bc e294 80e2 9480  ................
-0001ae40: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001ad50: 9480 e294 80e2 94bc e294 80e2 9480 e294  ................
+0001ad60: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001ad70: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001ad80: 9480 e294 80e2 9480 e294 bce2 9480 e294  ................
+0001ad90: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001ada0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001adb0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001adc0: 80e2 9480 e294 a40a e294 8220 2037 20e2  ...........  7 .
+0001add0: 9482 2020 2020 2020 3520 e294 8220 4157  ..      5 ... AW
+0001ade0: 5320 2020 2020 2020 20e2 9482 2041 7773  S        ... Aws
+0001adf0: 5370 6f74 436f 6d70 7574 6553 6f75 7263  SpotComputeSourc
+0001ae00: 6520 e294 8220 6575 2d77 6573 742d 3220  e ... eu-west-2 
+0001ae10: e294 8220 6d35 612e 6c61 7267 6520 2020  ... m5a.large   
+0001ae20: 2020 20e2 9482 2061 7773 7370 6f74 2d65     ... awsspot-e
+0001ae30: 752d 7765 7374 2d32 20e2 9482 0ae2 949c  u-west-2 .......
+0001ae40: e294 80e2 9480 e294 80e2 9480 e294 bce2  ................
 0001ae50: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001ae60: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001ae70: e294 80e2 9480 e294 80e2 9480 e294 bce2  ................
+0001ae60: 80e2 9480 e294 80e2 94bc e294 80e2 9480  ................
+0001ae70: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001ae80: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001ae90: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001aea0: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
+0001ae90: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001aea0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001aeb0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001aec0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001aed0: e294 80e2 94bc e294 80e2 9480 e294 80e2  ................
 0001aee0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001aef0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001aef0: 80e2 9480 e294 80e2 94bc e294 80e2 9480  ................
 0001af00: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001af10: 94a4 0ae2 9482 2020 3820 e294 8220 2020  ......  8 ...   
-0001af20: 2020 2035 20e2 9482 2041 5753 2020 2020     5 ... AWS    
-0001af30: 2020 2020 e294 8220 4177 7353 706f 7443      ... AwsSpotC
-0001af40: 6f6d 7075 7465 536f 7572 6365 20e2 9482  omputeSource ...
-0001af50: 2065 752d 7765 7374 2d32 20e2 9482 206d   eu-west-2 ... m
-0001af60: 3561 642e 6c61 7267 6520 2020 2020 e294  5ad.large     ..
-0001af70: 8220 6177 7373 706f 742d 6575 2d77 6573  . awsspot-eu-wes
-0001af80: 742d 3220 e294 820a e294 9ce2 9480 e294  t-2 ............
-0001af90: 80e2 9480 e294 80e2 94bc e294 80e2 9480  ................
-0001afa0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001afb0: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
-0001afc0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001afd0: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
-0001afe0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001aff0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b000: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001af10: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001af20: 80e2 9480 e294 80e2 9480 e294 bce2 9480  ................
+0001af30: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001af40: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001af50: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001af60: e294 80e2 9480 e294 a40a e294 8220 2038  .............  8
+0001af70: 20e2 9482 2020 2020 2020 3520 e294 8220   ...      5 ... 
+0001af80: 4157 5320 2020 2020 2020 20e2 9482 2041  AWS        ... A
+0001af90: 7773 5370 6f74 436f 6d70 7574 6553 6f75  wsSpotComputeSou
+0001afa0: 7263 6520 e294 8220 6575 2d77 6573 742d  rce ... eu-west-
+0001afb0: 3220 e294 8220 6d35 6164 2e6c 6172 6765  2 ... m5ad.large
+0001afc0: 2020 2020 20e2 9482 2061 7773 7370 6f74       ... awsspot
+0001afd0: 2d65 752d 7765 7374 2d32 20e2 9482 0ae2  -eu-west-2 .....
+0001afe0: 949c e294 80e2 9480 e294 80e2 9480 e294  ................
+0001aff0: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b000: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
 0001b010: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001b020: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b030: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001b040: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
+0001b020: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b030: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
+0001b040: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001b050: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001b060: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001b070: 9480 e294 80e2 94bc e294 80e2 9480 e294  ................
 0001b080: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b090: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001b090: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
 0001b0a0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001b0b0: 80e2 94a4 0ae2 9482 2020 3920 e294 8220  ........  9 ... 
-0001b0c0: 2020 2020 2035 20e2 9482 2041 5753 2020       5 ... AWS  
-0001b0d0: 2020 2020 2020 e294 8220 4177 7353 706f        ... AwsSpo
-0001b0e0: 7443 6f6d 7075 7465 536f 7572 6365 20e2  tComputeSource .
-0001b0f0: 9482 2065 752d 7765 7374 2d32 20e2 9482  .. eu-west-2 ...
-0001b100: 206d 3661 2e6c 6172 6765 2020 2020 2020   m6a.large      
-0001b110: e294 8220 6177 7373 706f 742d 6575 2d77  ... awsspot-eu-w
-0001b120: 6573 742d 3220 e294 820a e294 9ce2 9480  est-2 ..........
-0001b130: e294 80e2 9480 e294 80e2 94bc e294 80e2  ................
-0001b140: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001b150: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
-0001b160: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001b170: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
-0001b180: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b190: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001b1a0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b0b0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b0c0: e294 80e2 9480 e294 80e2 9480 e294 bce2  ................
+0001b0d0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b0e0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b0f0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001b100: 9480 e294 80e2 9480 e294 a40a e294 8220  ............... 
+0001b110: 2039 20e2 9482 2020 2020 2020 3520 e294   9 ...      5 ..
+0001b120: 8220 4157 5320 2020 2020 2020 20e2 9482  . AWS        ...
+0001b130: 2041 7773 5370 6f74 436f 6d70 7574 6553   AwsSpotComputeS
+0001b140: 6f75 7263 6520 e294 8220 6575 2d77 6573  ource ... eu-wes
+0001b150: 742d 3220 e294 8220 6d36 612e 6c61 7267  t-2 ... m6a.larg
+0001b160: 6520 2020 2020 20e2 9482 2061 7773 7370  e      ... awssp
+0001b170: 6f74 2d65 752d 7765 7374 2d32 20e2 9482  ot-eu-west-2 ...
+0001b180: 0ae2 949c e294 80e2 9480 e294 80e2 9480  ................
+0001b190: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
+0001b1a0: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
 0001b1b0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b1c0: e294 bce2 9480 e294 80e2 9480 e294 80e2  ................
-0001b1d0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001b1e0: 80e2 9480 e294 bce2 9480 e294 80e2 9480  ................
+0001b1c0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001b1d0: 9480 e294 bce2 9480 e294 80e2 9480 e294  ................
+0001b1e0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001b1f0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001b200: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001b210: 80e2 9480 e294 80e2 94bc e294 80e2 9480  ................
 0001b220: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001b230: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b230: 9480 e294 80e2 9480 e294 80e2 94bc e294  ................
 0001b240: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b250: e294 80e2 94a4 0ae2 9482 2031 3020 e294  .......... 10 ..
-0001b260: 8220 2020 2020 2035 20e2 9482 2041 5753  .      5 ... AWS
-0001b270: 2020 2020 2020 2020 e294 8220 4177 7353          ... AwsS
-0001b280: 706f 7443 6f6d 7075 7465 536f 7572 6365  potComputeSource
-0001b290: 20e2 9482 2065 752d 7765 7374 2d32 20e2   ... eu-west-2 .
-0001b2a0: 9482 2074 3361 2e6c 6172 6765 2020 2020  .. t3a.large    
-0001b2b0: 2020 e294 8220 6177 7373 706f 742d 6575    ... awsspot-eu
-0001b2c0: 2d77 6573 742d 3220 e294 820a e294 94e2  -west-2 ........
-0001b2d0: 9480 e294 80e2 9480 e294 80e2 94b4 e294  ................
-0001b2e0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b2f0: e294 80e2 9480 e294 b4e2 9480 e294 80e2  ................
-0001b300: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001b310: 80e2 9480 e294 80e2 9480 e294 80e2 94b4  ................
-0001b320: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001b330: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001b340: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b250: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001b260: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b270: bce2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b280: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
+0001b290: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b2a0: 80e2 9480 e294 80e2 9480 e294 a40a e294  ................
+0001b2b0: 8220 3130 20e2 9482 2020 2020 2020 3520  . 10 ...      5 
+0001b2c0: e294 8220 4157 5320 2020 2020 2020 20e2  ... AWS        .
+0001b2d0: 9482 2041 7773 5370 6f74 436f 6d70 7574  .. AwsSpotComput
+0001b2e0: 6553 6f75 7263 6520 e294 8220 6575 2d77  eSource ... eu-w
+0001b2f0: 6573 742d 3220 e294 8220 7433 612e 6c61  est-2 ... t3a.la
+0001b300: 7267 6520 2020 2020 20e2 9482 2061 7773  rge      ... aws
+0001b310: 7370 6f74 2d65 752d 7765 7374 2d32 20e2  spot-eu-west-2 .
+0001b320: 9482 0ae2 9494 e294 80e2 9480 e294 80e2  ................
+0001b330: 9480 e294 b4e2 9480 e294 80e2 9480 e294  ................
+0001b340: 80e2 9480 e294 80e2 9480 e294 80e2 94b4  ................
 0001b350: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001b360: 9480 e294 b4e2 9480 e294 80e2 9480 e294  ................
-0001b370: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
-0001b380: e294 80e2 9480 e294 b4e2 9480 e294 80e2  ................
+0001b360: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b370: 80e2 9480 e294 b4e2 9480 e294 80e2 9480  ................
+0001b380: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
 0001b390: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
 0001b3a0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
 0001b3b0: e294 80e2 9480 e294 80e2 94b4 e294 80e2  ................
 0001b3c0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
-0001b3d0: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b3d0: 80e2 9480 e294 80e2 9480 e294 80e2 94b4  ................
 0001b3e0: e294 80e2 9480 e294 80e2 9480 e294 80e2  ................
-0001b3f0: 9480 e294 80e2 9498 0a60 6060 0a0a 2323  .........```..##
-0001b400: 2079 642d 7465 726d 696e 6174 650a 0a54   yd-terminate..T
-0001b410: 6865 2060 7964 2d74 6572 6d69 6e61 7465  he `yd-terminate
-0001b420: 6020 636f 6d6d 616e 6420 696d 6d65 6469  ` command immedi
-0001b430: 6174 656c 7920 7465 726d 696e 6174 6573  ately terminates
-0001b440: 2043 6f6d 7075 7465 2052 6571 7569 7265   Compute Require
-0001b450: 6d65 6e74 7320 7468 6174 206d 6174 6368  ments that match
-0001b460: 2074 6865 2060 6e61 6d65 7370 6163 6560   the `namespace`
-0001b470: 2061 6e64 2060 7461 6760 2066 6f75 6e64   and `tag` found
-0001b480: 2069 6e20 7468 6520 636f 6e66 6967 7572   in the configur
-0001b490: 6174 696f 6e20 6669 6c65 2e20 416e 7920  ation file. Any 
-0001b4a0: 6578 6563 7574 696e 6720 5461 736b 7320  executing Tasks 
-0001b4b0: 7769 6c6c 2062 6520 7465 726d 696e 6174  will be terminat
-0001b4c0: 6564 2069 6d6d 6564 6961 7465 6c79 2c20  ed immediately, 
-0001b4d0: 616e 6420 7468 6520 576f 726b 6572 2050  and the Worker P
-0001b4e0: 6f6f 6c20 7769 6c6c 2062 6520 7368 7574  ool will be shut
-0001b4f0: 2064 6f77 6e2e 0a                         down..
+0001b3f0: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b400: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b410: e294 b4e2 9480 e294 80e2 9480 e294 80e2  ................
+0001b420: 9480 e294 80e2 9480 e294 80e2 9480 e294  ................
+0001b430: 80e2 9480 e294 80e2 9480 e294 80e2 9480  ................
+0001b440: e294 80e2 9480 e294 80e2 9480 e294 980a  ................
+0001b450: 6060 600a 0a23 2320 7964 2d74 6572 6d69  ```..## yd-termi
+0001b460: 6e61 7465 0a0a 5468 6520 6079 642d 7465  nate..The `yd-te
+0001b470: 726d 696e 6174 6560 2063 6f6d 6d61 6e64  rminate` command
+0001b480: 2069 6d6d 6564 6961 7465 6c79 2074 6572   immediately ter
+0001b490: 6d69 6e61 7465 7320 436f 6d70 7574 6520  minates Compute 
+0001b4a0: 5265 7175 6972 656d 656e 7473 2074 6861  Requirements tha
+0001b4b0: 7420 6d61 7463 6820 7468 6520 606e 616d  t match the `nam
+0001b4c0: 6573 7061 6365 6020 616e 6420 6074 6167  espace` and `tag
+0001b4d0: 6020 666f 756e 6420 696e 2074 6865 2063  ` found in the c
+0001b4e0: 6f6e 6669 6775 7261 7469 6f6e 2066 696c  onfiguration fil
+0001b4f0: 652e 2041 6e79 2065 7865 6375 7469 6e67  e. Any executing
+0001b500: 2054 6173 6b73 2077 696c 6c20 6265 2074   Tasks will be t
+0001b510: 6572 6d69 6e61 7465 6420 696d 6d65 6469  erminated immedi
+0001b520: 6174 656c 792c 2061 6e64 2074 6865 2057  ately, and the W
+0001b530: 6f72 6b65 7220 506f 6f6c 2077 696c 6c20  orker Pool will 
+0001b540: 6265 2073 6875 7420 646f 776e 2e0a 0a23  be shut down...#
+0001b550: 2320 7964 2d6c 6973 740a 0a54 6865 2060  # yd-list..The `
+0001b560: 7964 2d6c 6973 7460 2063 6f6d 6d61 6e64  yd-list` command
+0001b570: 2063 616e 2062 6520 7573 6564 2074 6f20   can be used to 
+0001b580: 6c69 7374 2076 6172 696f 7573 2059 656c  list various Yel
+0001b590: 6c6f 7744 6f67 2069 7465 6d73 2c20 7573  lowDog items, us
+0001b5a0: 696e 6720 7468 6520 606e 616d 6573 7061  ing the `namespa
+0001b5b0: 6365 6020 616e 6420 6074 6167 6020 7072  ce` and `tag` pr
+0001b5c0: 6f70 6572 7469 6573 2074 6f20 7461 7267  operties to targ
+0001b5d0: 6574 2074 6865 2073 636f 7065 206f 6620  et the scope of 
+0001b5e0: 7768 6174 2074 6f20 6c69 7374 3a0a 0a2d  what to list:..-
+0001b5f0: 2043 6f6d 7075 7465 2052 6571 7569 7265   Compute Require
+0001b600: 6d65 6e74 730a 2d20 576f 726b 6572 2050  ments.- Worker P
+0001b610: 6f6f 6c73 0a2d 204f 626a 6563 7473 2069  ools.- Objects i
+0001b620: 6e20 7468 6520 4f62 6a65 6374 2053 746f  n the Object Sto
+0001b630: 7265 0a2d 2057 6f72 6b20 5265 7175 6972  re.- Work Requir
+0001b640: 656d 656e 7473 0a2d 2054 6173 6b20 4772  ements.- Task Gr
+0001b650: 6f75 7073 0a2d 2054 6173 6b73 0a0a 506c  oups.- Tasks..Pl
+0001b660: 6561 7365 2075 7365 2060 7964 2d6c 6973  ease use `yd-lis
+0001b670: 7420 2d2d 6865 6c70 6020 746f 2069 6e73  t --help` to ins
+0001b680: 7065 6374 2074 6865 2076 6172 696f 7573  pect the various
+0001b690: 206f 7074 696f 6e73 2e0a                  options..
```

### Comparing `yellowdog-python-examples-6.0.5/pyproject.toml` & `yellowdog-python-examples-6.0.6/pyproject.toml`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/setup.cfg` & `yellowdog-python-examples-6.0.6/setup.cfg`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/abort.py` & `yellowdog-python-examples-6.0.6/yd_commands/abort.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/admin.py` & `yellowdog-python-examples-6.0.6/yd_commands/admin.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/args.py` & `yellowdog-python-examples-6.0.6/yd_commands/args.py`

 * *Files 0% similar despite different names*

```diff
@@ -228,15 +228,14 @@
 
         if any(
             module in sys.argv[0]
             for module in [
                 "cancel",
                 "delete",
                 "download",
-                "list",
                 "shutdown",
                 "terminate",
             ]
         ):
             parser.add_argument(
                 "--interactive",
                 "-i",
```

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/cancel.py` & `yellowdog-python-examples-6.0.6/yd_commands/cancel.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/check_imports.py` & `yellowdog-python-examples-6.0.6/yd_commands/check_imports.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/compact_json.py` & `yellowdog-python-examples-6.0.6/yd_commands/compact_json.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/config.py` & `yellowdog-python-examples-6.0.6/yd_commands/config.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/config_keys.py` & `yellowdog-python-examples-6.0.6/yd_commands/config_keys.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/csv_data.py` & `yellowdog-python-examples-6.0.6/yd_commands/csv_data.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/delete.py` & `yellowdog-python-examples-6.0.6/yd_commands/delete.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/download.py` & `yellowdog-python-examples-6.0.6/yd_commands/download.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/instantiate.py` & `yellowdog-python-examples-6.0.6/yd_commands/instantiate.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/interactive.py` & `yellowdog-python-examples-6.0.6/yd_commands/interactive.py`

 * *Files 7% similar despite different names*

```diff
@@ -28,20 +28,25 @@
 
 
 def select(
     client: PlatformClient,
     objects: List[Item],
     parent: Optional[Item] = None,
     override_quiet: bool = False,
+    single_result: bool = False,
 ) -> List[Item]:
     """
     Print a numbered list of objects.
     Manually select objects from a list if --interactive is set.
     Return the list of objects.
     """
+
+    if len(objects) == 0:
+        return objects
+
     objects = sorted_objects(objects)
 
     if not ARGS_PARSER.quiet or override_quiet or ARGS_PARSER.interactive:
         print_numbered_object_list(
             client, objects, parent, override_quiet=override_quiet
         )
 
@@ -52,19 +57,21 @@
         if 1 <= num <= len(objects):
             return True
         else:
             print_error(f"'{num}' is out of range")
             return False
 
     while True:
-        selector_string = input(
-            print_string(
+        if single_result:
+            input_string = "Please select item number or press <Return> to cancel: "
+        else:
+            input_string = (
                 "Please select items (e.g.: 1,2,4-7) or press <Return> for none: "
             )
-        )
+        selector_string = input(print_string(input_string))
         selector_list = selector_string.split(",")
         selector_set: Set[int] = set()
         error_flag = False
         for selector in selector_list:
             try:
                 if "-" in selector:
                     low_s, high_s = selector.split("-")
@@ -80,18 +87,23 @@
                 elif not (selector.isspace() or len(selector) == 0):
                     i = int(selector)
                     if in_range(i):
                         selector_set.add(i)
                     else:
                         error_flag = True
             except ValueError:
-                print(print_string(f"Error: '{selector}' is not a valid selection"))
+                print_error(f"'{selector}' is not a valid selection")
                 error_flag = True
         if error_flag:
             continue
+        elif len(selector_set) == 0:
+            break
+        elif single_result and len(selector_set) != 1:
+            print_error("please enter a single item number")
+            continue
         else:
             break
 
     selected_list = sorted(list(selector_set))
     if len(selected_list) > 0:
         print(
             print_string(
```

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/jsonnet2json.py` & `yellowdog-python-examples-6.0.6/yd_commands/jsonnet2json.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/list.py` & `yellowdog-python-examples-6.0.6/yd_commands/list.py`

 * *Files 11% similar despite different names*

```diff
@@ -81,15 +81,14 @@
     options chosen.
     """
     print_log(
         (
             f"Listing Work Requirements in 'namespace={CONFIG_COMMON.namespace}' "
             f"and names starting with 'tag={CONFIG_COMMON.name_tag}'"
         ),
-        override_quiet=True,
     )
     exclude_filter = (
         [
             WorkRequirementStatus.COMPLETED,
             WorkRequirementStatus.CANCELLED,
             WorkRequirementStatus.FAILED,
         ]
@@ -102,52 +101,54 @@
             namespace=CONFIG_COMMON.namespace,
             tag=CONFIG_COMMON.name_tag,
             exclude_filter=exclude_filter,
         )
     )
     work_requirement_summaries = sorted_objects(work_requirement_summaries)
     if not (ARGS_PARSER.task_groups or ARGS_PARSER.tasks):
-        print_numbered_object_list(
-            CLIENT, work_requirement_summaries, override_quiet=True
-        )
+        print_numbered_object_list(CLIENT, work_requirement_summaries)
     else:
-        selected_work_summaries = select(CLIENT, work_requirement_summaries)
+        selected_work_summaries = select(
+            CLIENT, work_requirement_summaries, single_result=True
+        )
         for work_summary in selected_work_summaries:
-            print_log(f"Work Requirement {work_summary.name}", override_quiet=True)
+            print_log(f"Work Requirement {work_summary.name}")
             list_task_groups(work_summary)
 
 
 def list_task_groups(work_summary: WorkRequirementSummary):
     task_groups: List[TaskGroup] = get_task_groups_from_wr_summary(
         CLIENT, work_summary.id
     )
     task_groups = sorted_objects(task_groups)
     if not ARGS_PARSER.tasks:
-        print_numbered_object_list(CLIENT, task_groups, override_quiet=True)
+        print_numbered_object_list(CLIENT, task_groups)
     else:
-        task_groups = select(CLIENT, task_groups, override_quiet=True)
+        task_groups = select(CLIENT, task_groups, single_result=True)
         for task_group in task_groups:
             list_tasks(task_group, work_summary)
 
 
 def list_tasks(task_group: TaskGroup, work_summary: WorkRequirementSummary):
     task_search = TaskSearch(
         workRequirementId=work_summary.id,
         taskGroupId=task_group.id,
     )
     tasks: List[Task] = CLIENT.work_client.find_tasks(task_search)
     tasks = sorted_objects(tasks)
-    print_numbered_object_list(CLIENT, tasks, parent=work_summary, override_quiet=True)
+    print_numbered_object_list(CLIENT, tasks, parent=work_summary)
 
 
 def list_object_paths():
     print_log(
         f"Listing Object Paths in namespace '{CONFIG_COMMON.namespace}' and "
         f"names starting with '{CONFIG_COMMON.name_tag}'"
     )
+    if ARGS_PARSER.object_tree:
+        print_log("Listing complete Object tree")
     object_paths: List[ObjectPath] = (
         CLIENT.object_store_client.get_namespace_object_paths(
             ObjectPathsRequest(
                 CONFIG_COMMON.namespace,
                 prefix=CONFIG_COMMON.name_tag,
                 flat=ARGS_PARSER.object_tree,
             )
@@ -194,17 +195,15 @@
                     and compute_requirement.namespace == CONFIG_COMMON.namespace
                 ):
                     selected_worker_pool_summaries.append(worker_pool_summary)
             else:
                 selected_worker_pool_summaries.append(worker_pool_summary)
 
     selected_worker_pool_summaries = sorted_objects(selected_worker_pool_summaries)
-    print_numbered_object_list(
-        CLIENT, selected_worker_pool_summaries, override_quiet=True
-    )
+    print_numbered_object_list(CLIENT, selected_worker_pool_summaries)
 
 
 def list_compute_requirements():
     print_log(
         "Listing Compute Requirements in "
         f"namespace '{CONFIG_COMMON.namespace}' and "
         f" names starting with '{CONFIG_COMMON.name_tag}'"
@@ -234,14 +233,13 @@
             and compute_requirement.status not in excluded_states
         ):
             filtered_compute_requirements.append(compute_requirement)
 
     print_numbered_object_list(
         CLIENT,
         sorted_objects(filtered_compute_requirements),
-        override_quiet=True,
     )
 
 
 # Entry point
 if __name__ == "__main__":
     main()
```

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/object_utilities.py` & `yellowdog-python-examples-6.0.6/yd_commands/object_utilities.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/printing.py` & `yellowdog-python-examples-6.0.6/yd_commands/printing.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/provision.py` & `yellowdog-python-examples-6.0.6/yd_commands/provision.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/provision_utils.py` & `yellowdog-python-examples-6.0.6/yd_commands/provision_utils.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/reformat_json.py` & `yellowdog-python-examples-6.0.6/yd_commands/reformat_json.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/shutdown.py` & `yellowdog-python-examples-6.0.6/yd_commands/shutdown.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/submit.py` & `yellowdog-python-examples-6.0.6/yd_commands/submit.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/submit_utils.py` & `yellowdog-python-examples-6.0.6/yd_commands/submit_utils.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/terminate.py` & `yellowdog-python-examples-6.0.6/yd_commands/terminate.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/type_check.py` & `yellowdog-python-examples-6.0.6/yd_commands/type_check.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/upload.py` & `yellowdog-python-examples-6.0.6/yd_commands/upload.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/upload_utils.py` & `yellowdog-python-examples-6.0.6/yd_commands/upload_utils.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/validate_properties.py` & `yellowdog-python-examples-6.0.6/yd_commands/validate_properties.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/variables.py` & `yellowdog-python-examples-6.0.6/yd_commands/variables.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/version.py` & `yellowdog-python-examples-6.0.6/yd_commands/version.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yd_commands/wrapper.py` & `yellowdog-python-examples-6.0.6/yd_commands/wrapper.py`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/PKG-INFO` & `yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: yellowdog-python-examples
-Version: 6.0.5
+Version: 6.0.6
 Summary: Example Python commands using the YellowDog Python SDK
 Home-page: https://github.com/yellowdog/python-examples
 Author: YellowDog Limited
 Author-email: YellowDog Limited <support@yellowdog.co>
 Project-URL: Homepage, https://github.com/yellowdog/python-examples
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
```

### Comparing `yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/SOURCES.txt` & `yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `yellowdog-python-examples-6.0.5/yellowdog_python_examples.egg-info/entry_points.txt` & `yellowdog-python-examples-6.0.6/yellowdog_python_examples.egg-info/entry_points.txt`

 * *Files identical despite different names*

