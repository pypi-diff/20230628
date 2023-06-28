# Comparing `tmp/epdlib-0.6.1.1.tar.gz` & `tmp/epdlib-0.6.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "epdlib-0.6.1.1.tar", last modified: Thu Mar  9 19:18:25 2023, max compression
+gzip compressed data, was "epdlib-0.6.1.2.tar", last modified: Wed Jun 28 15:34:11 2023, max compression
```

## Comparing `epdlib-0.6.1.1.tar` & `epdlib-0.6.1.2.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2023-03-09 19:18:25.406979 epdlib-0.6.1.1/
--rw-r--r--   0 pi        (1000) pi        (1000)    35149 2022-12-07 08:11:06.000000 epdlib-0.6.1.1/LICENSE
--rw-r--r--   0 pi        (1000) pi        (1000)     6615 2023-03-09 19:18:25.406979 epdlib-0.6.1.1/PKG-INFO
--rw-r--r--   0 pi        (1000) pi        (1000)     5842 2023-03-09 19:17:22.000000 epdlib-0.6.1.1/README.md
-drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2023-03-09 19:18:25.406979 epdlib-0.6.1.1/epdlib/
--rw-r--r--   0 pi        (1000) pi        (1000)    46062 2023-03-09 19:17:22.000000 epdlib-0.6.1.1/epdlib/Block.py
--rw-r--r--   0 pi        (1000) pi        (1000)    11475 2023-03-09 19:17:22.000000 epdlib-0.6.1.1/epdlib/Layout.py
--rw-r--r--   0 pi        (1000) pi        (1000)    31202 2023-03-09 19:17:22.000000 epdlib-0.6.1.1/epdlib/Screen.py
--rw-r--r--   0 pi        (1000) pi        (1000)      301 2022-12-07 08:11:06.000000 epdlib-0.6.1.1/epdlib/__init__.py
--rw-r--r--   0 pi        (1000) pi        (1000)    12659 2023-03-09 19:17:22.000000 epdlib-0.6.1.1/epdlib/constants.py
--rw-r--r--   0 pi        (1000) pi        (1000)       22 2023-03-09 19:17:22.000000 epdlib-0.6.1.1/epdlib/version.py
-drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2023-03-09 19:18:25.406979 epdlib-0.6.1.1/epdlib.egg-info/
--rw-r--r--   0 pi        (1000) pi        (1000)     6615 2023-03-09 19:18:25.000000 epdlib-0.6.1.1/epdlib.egg-info/PKG-INFO
--rw-r--r--   0 pi        (1000) pi        (1000)      297 2023-03-09 19:18:25.000000 epdlib-0.6.1.1/epdlib.egg-info/SOURCES.txt
--rw-r--r--   0 pi        (1000) pi        (1000)        1 2023-03-09 19:18:25.000000 epdlib-0.6.1.1/epdlib.egg-info/dependency_links.txt
--rw-r--r--   0 pi        (1000) pi        (1000)       32 2023-03-09 19:18:25.000000 epdlib-0.6.1.1/epdlib.egg-info/requires.txt
--rw-r--r--   0 pi        (1000) pi        (1000)        7 2023-03-09 19:18:25.000000 epdlib-0.6.1.1/epdlib.egg-info/top_level.txt
--rw-r--r--   0 pi        (1000) pi        (1000)      100 2022-12-11 11:07:44.000000 epdlib-0.6.1.1/pyproject.toml
--rw-r--r--   0 pi        (1000) pi        (1000)       38 2023-03-09 19:18:25.406979 epdlib-0.6.1.1/setup.cfg
--rw-r--r--   0 pi        (1000) pi        (1000)      710 2023-02-10 18:13:49.000000 epdlib-0.6.1.1/setup.py
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2023-06-28 15:34:11.753073 epdlib-0.6.1.2/
+-rw-r--r--   0 pi        (1000) pi        (1000)    35149 2022-12-07 08:11:06.000000 epdlib-0.6.1.2/LICENSE
+-rw-r--r--   0 pi        (1000) pi        (1000)     6615 2023-06-28 15:34:11.753073 epdlib-0.6.1.2/PKG-INFO
+-rw-r--r--   0 pi        (1000) pi        (1000)     5842 2023-03-09 19:17:22.000000 epdlib-0.6.1.2/README.md
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2023-06-28 15:34:11.749073 epdlib-0.6.1.2/epdlib/
+-rw-r--r--   0 pi        (1000) pi        (1000)    46062 2023-03-09 19:17:22.000000 epdlib-0.6.1.2/epdlib/Block.py
+-rw-r--r--   0 pi        (1000) pi        (1000)    11475 2023-03-09 19:17:22.000000 epdlib-0.6.1.2/epdlib/Layout.py
+-rw-r--r--   0 pi        (1000) pi        (1000)    31202 2023-05-11 08:11:05.000000 epdlib-0.6.1.2/epdlib/Screen.py
+-rw-r--r--   0 pi        (1000) pi        (1000)      301 2022-12-07 08:11:06.000000 epdlib-0.6.1.2/epdlib/__init__.py
+-rw-r--r--   0 pi        (1000) pi        (1000)    12659 2023-03-09 19:17:22.000000 epdlib-0.6.1.2/epdlib/constants.py
+-rw-r--r--   0 pi        (1000) pi        (1000)       22 2023-06-28 15:33:11.000000 epdlib-0.6.1.2/epdlib/version.py
+drwxr-xr-x   0 pi        (1000) pi        (1000)        0 2023-06-28 15:34:11.753073 epdlib-0.6.1.2/epdlib.egg-info/
+-rw-r--r--   0 pi        (1000) pi        (1000)     6615 2023-06-28 15:34:11.000000 epdlib-0.6.1.2/epdlib.egg-info/PKG-INFO
+-rw-r--r--   0 pi        (1000) pi        (1000)      297 2023-06-28 15:34:11.000000 epdlib-0.6.1.2/epdlib.egg-info/SOURCES.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)        1 2023-06-28 15:34:11.000000 epdlib-0.6.1.2/epdlib.egg-info/dependency_links.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)       23 2023-06-28 15:34:11.000000 epdlib-0.6.1.2/epdlib.egg-info/requires.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)        7 2023-06-28 15:34:11.000000 epdlib-0.6.1.2/epdlib.egg-info/top_level.txt
+-rw-r--r--   0 pi        (1000) pi        (1000)      100 2022-12-11 11:07:44.000000 epdlib-0.6.1.2/pyproject.toml
+-rw-r--r--   0 pi        (1000) pi        (1000)       38 2023-06-28 15:34:11.753073 epdlib-0.6.1.2/setup.cfg
+-rw-r--r--   0 pi        (1000) pi        (1000)      710 2023-02-10 18:13:49.000000 epdlib-0.6.1.2/setup.py
```

### Comparing `epdlib-0.6.1.1/LICENSE` & `epdlib-0.6.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `epdlib-0.6.1.1/PKG-INFO` & `epdlib-0.6.1.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: epdlib
-Version: 0.6.1.1
+Version: 0.6.1.2
 Summary: EpdLib is a library for creating dynamically scaled screen layouts for frame-buffered devices such as e-paper/e-ink displays.
 Home-page: https://github.com/txoof/epdlib
 Author: Aaron Ciuffo
 Author-email: aaron.ciuffo@gmail.com
 Project-URL: Source, https://github.com/txoof/epdlib
 Keywords: graphics e-paper display waveshare
 Classifier: Intended Audience :: Developers
```

### Comparing `epdlib-0.6.1.1/README.md` & `epdlib-0.6.1.2/README.md`

 * *Files identical despite different names*

### Comparing `epdlib-0.6.1.1/epdlib/Block.py` & `epdlib-0.6.1.2/epdlib/Block.py`

 * *Files identical despite different names*

### Comparing `epdlib-0.6.1.1/epdlib/Layout.py` & `epdlib-0.6.1.2/epdlib/Layout.py`

 * *Files identical despite different names*

### Comparing `epdlib-0.6.1.1/epdlib/Screen.py` & `epdlib-0.6.1.2/epdlib/Screen.py`

 * *Files identical despite different names*

### Comparing `epdlib-0.6.1.1/epdlib/constants.py` & `epdlib-0.6.1.2/epdlib/constants.py`

 * *Files identical despite different names*

### Comparing `epdlib-0.6.1.1/epdlib.egg-info/PKG-INFO` & `epdlib-0.6.1.2/epdlib.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: epdlib
-Version: 0.6.1.1
+Version: 0.6.1.2
 Summary: EpdLib is a library for creating dynamically scaled screen layouts for frame-buffered devices such as e-paper/e-ink displays.
 Home-page: https://github.com/txoof/epdlib
 Author: Aaron Ciuffo
 Author-email: aaron.ciuffo@gmail.com
 Project-URL: Source, https://github.com/txoof/epdlib
 Keywords: graphics e-paper display waveshare
 Classifier: Intended Audience :: Developers
```

### Comparing `epdlib-0.6.1.1/setup.py` & `epdlib-0.6.1.2/setup.py`

 * *Files identical despite different names*

