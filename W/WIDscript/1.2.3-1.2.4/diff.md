# Comparing `tmp/WIDscript-1.2.3.tar.gz` & `tmp/WIDscript-1.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "WIDscript-1.2.3.tar", last modified: Wed Jun 28 00:27:20 2023, max compression
+gzip compressed data, was "WIDscript-1.2.4.tar", last modified: Wed Jun 28 12:04:45 2023, max compression
```

## Comparing `WIDscript-1.2.3.tar` & `WIDscript-1.2.4.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 00:27:20.489576 WIDscript-1.2.3/
--rw-rw-rw-   0        0        0        0 2023-06-19 20:14:16.000000 WIDscript-1.2.3/LICENSE
--rw-rw-rw-   0        0        0      520 2023-06-28 00:27:20.490576 WIDscript-1.2.3/PKG-INFO
--rw-rw-rw-   0        0        0        0 2023-06-19 20:32:17.000000 WIDscript-1.2.3/README.md
--rw-rw-rw-   0        0        0      108 2023-06-21 01:38:12.000000 WIDscript-1.2.3/pyproject.toml
--rw-rw-rw-   0        0        0      661 2023-06-28 00:27:20.491578 WIDscript-1.2.3/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-28 00:27:20.470571 WIDscript-1.2.3/src/
-drwxrwxrwx   0        0        0        0 2023-06-28 00:27:20.475569 WIDscript-1.2.3/src/WIDscript/
--rw-rw-rw-   0        0        0    27258 2023-06-28 00:25:43.000000 WIDscript-1.2.3/src/WIDscript/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 00:27:20.489576 WIDscript-1.2.3/src/WIDscript.egg-info/
--rw-rw-rw-   0        0        0      520 2023-06-28 00:27:20.000000 WIDscript-1.2.3/src/WIDscript.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      216 2023-06-28 00:27:20.000000 WIDscript-1.2.3/src/WIDscript.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 00:27:20.000000 WIDscript-1.2.3/src/WIDscript.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       10 2023-06-28 00:27:20.000000 WIDscript-1.2.3/src/WIDscript.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 12:04:45.253911 WIDscript-1.2.4/
+-rw-rw-rw-   0        0        0        0 2023-06-19 20:14:16.000000 WIDscript-1.2.4/LICENSE
+-rw-rw-rw-   0        0        0      520 2023-06-28 12:04:45.253911 WIDscript-1.2.4/PKG-INFO
+-rw-rw-rw-   0        0        0        0 2023-06-19 20:32:17.000000 WIDscript-1.2.4/README.md
+-rw-rw-rw-   0        0        0      108 2023-06-21 01:38:12.000000 WIDscript-1.2.4/pyproject.toml
+-rw-rw-rw-   0        0        0      661 2023-06-28 12:04:45.254912 WIDscript-1.2.4/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 12:04:45.230905 WIDscript-1.2.4/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 12:04:45.240910 WIDscript-1.2.4/src/WIDscript/
+-rw-rw-rw-   0        0        0    27258 2023-06-28 12:04:13.000000 WIDscript-1.2.4/src/WIDscript/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:04:45.252911 WIDscript-1.2.4/src/WIDscript.egg-info/
+-rw-rw-rw-   0        0        0      520 2023-06-28 12:04:45.000000 WIDscript-1.2.4/src/WIDscript.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      216 2023-06-28 12:04:45.000000 WIDscript-1.2.4/src/WIDscript.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:04:45.000000 WIDscript-1.2.4/src/WIDscript.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       10 2023-06-28 12:04:45.000000 WIDscript-1.2.4/src/WIDscript.egg-info/top_level.txt
```

### Comparing `WIDscript-1.2.3/PKG-INFO` & `WIDscript-1.2.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: WIDscript
-Version: 1.2.3
+Version: 1.2.4
 Summary: A private wrapper made for WIDOWN releases.
 Home-page: https://github.com/pypa/sampleproject
 Author: WIDOWN
 Author-email: widown.ma@gmail.com
 Project-URL: Bug Tracker, https://github.com/pypa/sampleproject/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `WIDscript-1.2.3/setup.cfg` & `WIDscript-1.2.4/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2057 4944 7363 7269 7074 0d0a 7665   = WIDscript..ve
-00000020: 7273 696f 6e20 3d20 312e 322e 330d 0a61  rsion = 1.2.3..a
+00000020: 7273 696f 6e20 3d20 312e 322e 340d 0a61  rsion = 1.2.4..a
 00000030: 7574 686f 7220 3d20 5749 444f 574e 0d0a  uthor = WIDOWN..
 00000040: 6175 7468 6f72 5f65 6d61 696c 203d 2077  author_email = w
 00000050: 6964 6f77 6e2e 6d61 4067 6d61 696c 2e63  idown.ma@gmail.c
 00000060: 6f6d 0d0a 6465 7363 7269 7074 696f 6e20  om..description 
 00000070: 3d20 4120 7072 6976 6174 6520 7772 6170  = A private wrap
 00000080: 7065 7220 6d61 6465 2066 6f72 2057 4944  per made for WID
 00000090: 4f57 4e20 7265 6c65 6173 6573 2e0d 0a6c  OWN releases...l
```

### Comparing `WIDscript-1.2.3/src/WIDscript/__init__.py` & `WIDscript-1.2.4/src/WIDscript/__init__.py`

 * *Files identical despite different names*

### Comparing `WIDscript-1.2.3/src/WIDscript.egg-info/PKG-INFO` & `WIDscript-1.2.4/src/WIDscript.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: WIDscript
-Version: 1.2.3
+Version: 1.2.4
 Summary: A private wrapper made for WIDOWN releases.
 Home-page: https://github.com/pypa/sampleproject
 Author: WIDOWN
 Author-email: widown.ma@gmail.com
 Project-URL: Bug Tracker, https://github.com/pypa/sampleproject/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

