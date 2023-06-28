# Comparing `tmp/kojo-fan-art-0.1.0.tar.gz` & `tmp/kojo-fan-art-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kojo-fan-art-0.1.0.tar", last modified: Sat Jun 24 10:24:30 2023, max compression
+gzip compressed data, was "kojo-fan-art-0.1.1.tar", last modified: Wed Jun 28 14:40:35 2023, max compression
```

## Comparing `kojo-fan-art-0.1.0.tar` & `kojo-fan-art-0.1.1.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:24:30.751920 kojo-fan-art-0.1.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1063 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1738 2023-06-24 10:24:30.751920 kojo-fan-art-0.1.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      936 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:24:30.751920 kojo-fan-art-0.1.0/kojo_fan_art.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1738 2023-06-24 10:24:30.000000 kojo-fan-art-0.1.0/kojo_fan_art.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-24 10:24:30.000000 kojo-fan-art-0.1.0/kojo_fan_art.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-24 10:24:30.000000 kojo-fan-art-0.1.0/kojo_fan_art.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-24 10:24:30.000000 kojo-fan-art-0.1.0/kojo_fan_art.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-24 10:24:30.000000 kojo-fan-art-0.1.0/kojo_fan_art.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-24 10:24:30.000000 kojo-fan-art-0.1.0/kojo_fan_art.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-24 10:24:30.751920 kojo-fan-art-0.1.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:24:30.751920 kojo-fan-art-0.1.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      495 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/tests/test_core.py
--rw-r--r--   0 runner    (1001) docker     (123)     1431 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/tests/test_date.py
--rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/tests/test_main.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:24:30.751920 kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/
--rw-r--r--   0 runner    (1001) docker     (123)      440 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      758 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2524 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/_date.py
--rw-r--r--   0 runner    (1001) docker     (123)      937 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/_types.py
--rw-r--r--   0 runner    (1001) docker     (123)      627 2023-06-24 10:24:20.000000 kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/core.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:40:35.068988 kojo-fan-art-0.1.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1063 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1810 2023-06-28 14:40:35.068988 kojo-fan-art-0.1.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1008 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:40:35.068988 kojo-fan-art-0.1.1/kojo_fan_art.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1810 2023-06-28 14:40:35.000000 kojo-fan-art-0.1.1/kojo_fan_art.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-28 14:40:35.000000 kojo-fan-art-0.1.1/kojo_fan_art.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:40:35.000000 kojo-fan-art-0.1.1/kojo_fan_art.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 14:40:35.000000 kojo-fan-art-0.1.1/kojo_fan_art.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-28 14:40:35.000000 kojo-fan-art-0.1.1/kojo_fan_art.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 14:40:35.000000 kojo-fan-art-0.1.1/kojo_fan_art.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:40:35.068988 kojo-fan-art-0.1.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:40:35.068988 kojo-fan-art-0.1.1/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      495 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/tests/test_core.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1431 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/tests/test_date.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1390 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/tests/test_main.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:40:35.068988 kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/
+-rw-r--r--   0 runner    (1001) docker     (123)      440 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1420 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2524 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/_date.py
+-rw-r--r--   0 runner    (1001) docker     (123)      937 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/_types.py
+-rw-r--r--   0 runner    (1001) docker     (123)      627 2023-06-28 14:40:22.000000 kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/core.py
```

### Comparing `kojo-fan-art-0.1.0/LICENSE` & `kojo-fan-art-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `kojo-fan-art-0.1.0/PKG-INFO` & `kojo-fan-art-0.1.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kojo-fan-art
-Version: 0.1.0
+Version: 0.1.1
 Summary: Fan art project for "Lonely Castle in the Mirror"(『かがみの孤城』)
 Author-email: nikkie <takuyafjp+develop@gmail.com>
 License: MIT License
 Project-URL: Repository, https://github.com/ftnext/the-solitary-castle-in-the-mirror-cli
 Classifier: Development Status :: 3 - Alpha
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python
@@ -16,15 +16,15 @@
 Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
 
 # kojo-fan-art
 
-[日本語版 (In Japanese)](./README.ja.md)
+[日本語版 (In Japanese)](https://github.com/ftnext/the-solitary-castle-in-the-mirror-cli/blob/main/README.ja.md)
 
 This is a fan art project for "Lonely Castle in the Mirror."
 
 ## Installation
 
 ```sh
 $ pip install kojo-fan-art
```

### Comparing `kojo-fan-art-0.1.0/README.md` & `kojo-fan-art-0.1.1/README.md`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # kojo-fan-art
 
-[日本語版 (In Japanese)](./README.ja.md)
+[日本語版 (In Japanese)](https://github.com/ftnext/the-solitary-castle-in-the-mirror-cli/blob/main/README.ja.md)
 
 This is a fan art project for "Lonely Castle in the Mirror."
 
 ## Installation
 
 ```sh
 $ pip install kojo-fan-art
```

### Comparing `kojo-fan-art-0.1.0/kojo_fan_art.egg-info/PKG-INFO` & `kojo-fan-art-0.1.1/kojo_fan_art.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kojo-fan-art
-Version: 0.1.0
+Version: 0.1.1
 Summary: Fan art project for "Lonely Castle in the Mirror"(『かがみの孤城』)
 Author-email: nikkie <takuyafjp+develop@gmail.com>
 License: MIT License
 Project-URL: Repository, https://github.com/ftnext/the-solitary-castle-in-the-mirror-cli
 Classifier: Development Status :: 3 - Alpha
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python
@@ -16,15 +16,15 @@
 Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 Provides-Extra: dev
 License-File: LICENSE
 
 # kojo-fan-art
 
-[日本語版 (In Japanese)](./README.ja.md)
+[日本語版 (In Japanese)](https://github.com/ftnext/the-solitary-castle-in-the-mirror-cli/blob/main/README.ja.md)
 
 This is a fan art project for "Lonely Castle in the Mirror."
 
 ## Installation
 
 ```sh
 $ pip install kojo-fan-art
```

### Comparing `kojo-fan-art-0.1.0/kojo_fan_art.egg-info/SOURCES.txt` & `kojo-fan-art-0.1.1/kojo_fan_art.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `kojo-fan-art-0.1.0/pyproject.toml` & `kojo-fan-art-0.1.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `kojo-fan-art-0.1.0/tests/test_date.py` & `kojo-fan-art-0.1.1/tests/test_date.py`

 * *Files identical despite different names*

### Comparing `kojo-fan-art-0.1.0/tests/test_main.py` & `kojo-fan-art-0.1.1/tests/test_main.py`

 * *Files identical despite different names*

### Comparing `kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/_date.py` & `kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/_date.py`

 * *Files identical despite different names*

### Comparing `kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/_types.py` & `kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/_types.py`

 * *Files identical despite different names*

### Comparing `kojo-fan-art-0.1.0/the_solitary_castle_in_the_mirror/core.py` & `kojo-fan-art-0.1.1/the_solitary_castle_in_the_mirror/core.py`

 * *Files identical despite different names*

