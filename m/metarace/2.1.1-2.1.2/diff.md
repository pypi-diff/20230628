# Comparing `tmp/metarace-2.1.1.tar.gz` & `tmp/metarace-2.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "metarace-2.1.1.tar", last modified: Wed Jun 28 01:35:08 2023, max compression
+gzip compressed data, was "metarace-2.1.2.tar", last modified: Wed Jun 28 13:21:45 2023, max compression
```

## Comparing `metarace-2.1.1.tar` & `metarace-2.1.2.tar`

### file list

```diff
@@ -1,45 +1,46 @@
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.448818 metarace-2.1.1/
--rw-------   0 ndf       (1000) ndf       (1000)     1092 2022-01-22 06:38:57.000000 metarace-2.1.1/LICENSE
--rw-r--r--   0 ndf       (1000) ndf       (1000)       28 2022-05-31 01:20:37.000000 metarace-2.1.1/MANIFEST.in
--rw-r--r--   0 ndf       (1000) ndf       (1000)     4762 2023-06-28 01:35:08.448818 metarace-2.1.1/PKG-INFO
--rw-------   0 ndf       (1000) ndf       (1000)     4243 2023-06-28 01:33:45.000000 metarace-2.1.1/README.md
--rw-r--r--   0 ndf       (1000) ndf       (1000)      753 2023-06-28 00:30:37.000000 metarace-2.1.1/pyproject.toml
--rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-28 01:35:08.448818 metarace-2.1.1/setup.cfg
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.440818 metarace-2.1.1/src/
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.444818 metarace-2.1.1/src/metarace/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     9466 2023-06-26 09:40:49.000000 metarace-2.1.1/src/metarace/__init__.py
--rw-------   0 ndf       (1000) ndf       (1000)     4268 2023-06-25 00:11:43.000000 metarace-2.1.1/src/metarace/countback.py
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.448818 metarace-2.1.1/src/metarace/data/
--rw-------   0 ndf       (1000) ndf       (1000)     3067 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/IOC_Codes.csv
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_armfin.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_armint.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_armstart.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_idle.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     2369 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_src.svg
--rw-------   0 ndf       (1000) ndf       (1000)      520 2023-06-05 02:11:31.000000 metarace-2.1.1/src/metarace/data/metarace.json
--rw-------   0 ndf       (1000) ndf       (1000)     8729 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/metarace_icon.svg
--rw-------   0 ndf       (1000) ndf       (1000)     2048 2023-06-05 01:23:26.000000 metarace-2.1.1/src/metarace/data/pdf_template.json
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.448818 metarace-2.1.1/src/metarace/decoder/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     5730 2023-05-31 00:29:16.000000 metarace-2.1.1/src/metarace/decoder/__init__.py
--rw-------   0 ndf       (1000) ndf       (1000)    15284 2023-06-27 08:32:43.000000 metarace-2.1.1/src/metarace/decoder/rrs.py
--rw-------   0 ndf       (1000) ndf       (1000)    27311 2023-06-27 08:32:09.000000 metarace-2.1.1/src/metarace/decoder/rru.py
--rw-------   0 ndf       (1000) ndf       (1000)    18916 2023-06-27 13:14:15.000000 metarace-2.1.1/src/metarace/decoder/thbc.py
--rw-------   0 ndf       (1000) ndf       (1000)    11424 2023-06-25 00:11:28.000000 metarace-2.1.1/src/metarace/eventdb.py
--rw-------   0 ndf       (1000) ndf       (1000)     3733 2023-05-31 00:53:46.000000 metarace-2.1.1/src/metarace/export.py
--rw-------   0 ndf       (1000) ndf       (1000)     8787 2023-06-25 00:11:12.000000 metarace-2.1.1/src/metarace/gemini.py
--rw-------   0 ndf       (1000) ndf       (1000)     5970 2023-06-28 00:17:21.000000 metarace-2.1.1/src/metarace/htlib.py
--rw-------   0 ndf       (1000) ndf       (1000)     5636 2023-06-25 00:10:49.000000 metarace-2.1.1/src/metarace/jsonconfig.py
--rw-------   0 ndf       (1000) ndf       (1000)   199422 2023-06-28 00:18:10.000000 metarace-2.1.1/src/metarace/report.py
--rw-------   0 ndf       (1000) ndf       (1000)    24615 2023-06-24 14:16:56.000000 metarace-2.1.1/src/metarace/riderdb.py
--rw-------   0 ndf       (1000) ndf       (1000)    10274 2023-06-25 00:10:28.000000 metarace-2.1.1/src/metarace/sender.py
--rw-------   0 ndf       (1000) ndf       (1000)    17918 2023-06-25 00:09:45.000000 metarace-2.1.1/src/metarace/strops.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)    13652 2022-11-14 06:21:05.000000 metarace-2.1.1/src/metarace/telegraph.py
--rw-------   0 ndf       (1000) ndf       (1000)    15088 2023-06-04 10:37:01.000000 metarace-2.1.1/src/metarace/timy.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)    20914 2023-06-25 00:08:46.000000 metarace-2.1.1/src/metarace/tod.py
--rw-------   0 ndf       (1000) ndf       (1000)     4485 2023-06-25 00:09:26.000000 metarace-2.1.1/src/metarace/unt4.py
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.444818 metarace-2.1.1/src/metarace.egg-info/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     4762 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)      985 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/SOURCES.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/dependency_links.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)       67 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/requires.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        9 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/top_level.txt
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:21:45.296258 metarace-2.1.2/
+-rw-------   0 ndf       (1000) ndf       (1000)     1092 2022-01-22 06:38:57.000000 metarace-2.1.2/LICENSE
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       28 2022-05-31 01:20:37.000000 metarace-2.1.2/MANIFEST.in
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     4762 2023-06-28 13:21:45.296258 metarace-2.1.2/PKG-INFO
+-rw-------   0 ndf       (1000) ndf       (1000)     4243 2023-06-28 01:33:45.000000 metarace-2.1.2/README.md
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      753 2023-06-28 13:21:14.000000 metarace-2.1.2/pyproject.toml
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-28 13:21:45.296258 metarace-2.1.2/setup.cfg
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:21:45.284257 metarace-2.1.2/src/
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:21:45.292257 metarace-2.1.2/src/metarace/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     9466 2023-06-28 13:21:28.000000 metarace-2.1.2/src/metarace/__init__.py
+-rw-------   0 ndf       (1000) ndf       (1000)     4268 2023-06-25 00:11:43.000000 metarace-2.1.2/src/metarace/countback.py
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:21:45.292257 metarace-2.1.2/src/metarace/data/
+-rw-------   0 ndf       (1000) ndf       (1000)     3067 2022-01-22 22:18:40.000000 metarace-2.1.2/src/metarace/data/IOC_Codes.csv
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        0 2023-06-28 11:57:11.000000 metarace-2.1.2/src/metarace/data/__init__.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.2/src/metarace/data/bg_armfin.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.2/src/metarace/data/bg_armint.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.2/src/metarace/data/bg_armstart.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.2/src/metarace/data/bg_idle.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     2369 2022-01-22 22:18:40.000000 metarace-2.1.2/src/metarace/data/bg_src.svg
+-rw-------   0 ndf       (1000) ndf       (1000)      520 2023-06-05 02:11:31.000000 metarace-2.1.2/src/metarace/data/metarace.json
+-rw-------   0 ndf       (1000) ndf       (1000)     8729 2022-01-22 22:18:40.000000 metarace-2.1.2/src/metarace/data/metarace_icon.svg
+-rw-------   0 ndf       (1000) ndf       (1000)     2048 2023-06-05 01:23:26.000000 metarace-2.1.2/src/metarace/data/pdf_template.json
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:21:45.296258 metarace-2.1.2/src/metarace/decoder/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     5730 2023-05-31 00:29:16.000000 metarace-2.1.2/src/metarace/decoder/__init__.py
+-rw-------   0 ndf       (1000) ndf       (1000)    15284 2023-06-27 08:32:43.000000 metarace-2.1.2/src/metarace/decoder/rrs.py
+-rw-------   0 ndf       (1000) ndf       (1000)    27311 2023-06-27 08:32:09.000000 metarace-2.1.2/src/metarace/decoder/rru.py
+-rw-------   0 ndf       (1000) ndf       (1000)    18916 2023-06-27 13:14:15.000000 metarace-2.1.2/src/metarace/decoder/thbc.py
+-rw-------   0 ndf       (1000) ndf       (1000)    11424 2023-06-25 00:11:28.000000 metarace-2.1.2/src/metarace/eventdb.py
+-rw-------   0 ndf       (1000) ndf       (1000)     3733 2023-05-31 00:53:46.000000 metarace-2.1.2/src/metarace/export.py
+-rw-------   0 ndf       (1000) ndf       (1000)     8787 2023-06-25 00:11:12.000000 metarace-2.1.2/src/metarace/gemini.py
+-rw-------   0 ndf       (1000) ndf       (1000)     5970 2023-06-28 00:17:21.000000 metarace-2.1.2/src/metarace/htlib.py
+-rw-------   0 ndf       (1000) ndf       (1000)     5636 2023-06-25 00:10:49.000000 metarace-2.1.2/src/metarace/jsonconfig.py
+-rw-------   0 ndf       (1000) ndf       (1000)   199422 2023-06-28 00:18:10.000000 metarace-2.1.2/src/metarace/report.py
+-rw-------   0 ndf       (1000) ndf       (1000)    24615 2023-06-24 14:16:56.000000 metarace-2.1.2/src/metarace/riderdb.py
+-rw-------   0 ndf       (1000) ndf       (1000)    10274 2023-06-25 00:10:28.000000 metarace-2.1.2/src/metarace/sender.py
+-rw-------   0 ndf       (1000) ndf       (1000)    17918 2023-06-25 00:09:45.000000 metarace-2.1.2/src/metarace/strops.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    13652 2022-11-14 06:21:05.000000 metarace-2.1.2/src/metarace/telegraph.py
+-rw-------   0 ndf       (1000) ndf       (1000)    15088 2023-06-04 10:37:01.000000 metarace-2.1.2/src/metarace/timy.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    20914 2023-06-25 00:08:46.000000 metarace-2.1.2/src/metarace/tod.py
+-rw-------   0 ndf       (1000) ndf       (1000)     4485 2023-06-25 00:09:26.000000 metarace-2.1.2/src/metarace/unt4.py
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 13:21:45.292257 metarace-2.1.2/src/metarace.egg-info/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     4762 2023-06-28 13:21:45.000000 metarace-2.1.2/src/metarace.egg-info/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1015 2023-06-28 13:21:45.000000 metarace-2.1.2/src/metarace.egg-info/SOURCES.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-28 13:21:45.000000 metarace-2.1.2/src/metarace.egg-info/dependency_links.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       67 2023-06-28 13:21:45.000000 metarace-2.1.2/src/metarace.egg-info/requires.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        9 2023-06-28 13:21:45.000000 metarace-2.1.2/src/metarace.egg-info/top_level.txt
```

### Comparing `metarace-2.1.1/LICENSE` & `metarace-2.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/PKG-INFO` & `metarace-2.1.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: metarace
-Version: 2.1.1
+Version: 2.1.2
 Summary: Cyclesport results and timing toolkit
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace
 Keywords: cyclesport,results,timing
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
```

### Comparing `metarace-2.1.1/README.md` & `metarace-2.1.2/README.md`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/pyproject.toml` & `metarace-2.1.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=62"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "metarace"
-version = "2.1.1"
+version = "2.1.2"
 description = "Cyclesport results and timing toolkit"
 readme = "README.md"
 requires-python = ">=3.9"
 license = {text = "MIT"}
 keywords = ["cyclesport", "results", "timing"]
 authors = [
     {email = "ndf-zz@6-v.org", name = "Nathan Fraser"}
```

### Comparing `metarace-2.1.1/src/metarace/__init__.py` & `metarace-2.1.2/src/metarace/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 from shutil import copyfile
 from metarace import jsonconfig
 try:
     from importlib.resources import files, as_file
 except ImportError:
     print('Python >= 3.9 is required to use this module')
 
-VERSION = '2.1.1'
+VERSION = '2.1.2'
 DATA_PATH = os.path.realpath(
     os.path.expanduser(os.path.join('~', 'Documents', 'metarace')))
 DEFAULTS_PATH = os.path.join(DATA_PATH, 'default')
 RESOURCE_PKG = 'metarace.data'
 LOGO = 'metarace_icon.svg'
 SYSCONF = 'metarace.json'
 PDF_TEMPLATE = 'pdf_template.json'
```

### Comparing `metarace-2.1.1/src/metarace/countback.py` & `metarace-2.1.2/src/metarace/countback.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/IOC_Codes.csv` & `metarace-2.1.2/src/metarace/data/IOC_Codes.csv`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/bg_armfin.svg` & `metarace-2.1.2/src/metarace/data/bg_armfin.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/bg_armint.svg` & `metarace-2.1.2/src/metarace/data/bg_armint.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/bg_armstart.svg` & `metarace-2.1.2/src/metarace/data/bg_armstart.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/bg_idle.svg` & `metarace-2.1.2/src/metarace/data/bg_idle.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/bg_src.svg` & `metarace-2.1.2/src/metarace/data/bg_src.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/metarace.json` & `metarace-2.1.2/src/metarace/data/metarace.json`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/metarace_icon.svg` & `metarace-2.1.2/src/metarace/data/metarace_icon.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/data/pdf_template.json` & `metarace-2.1.2/src/metarace/data/pdf_template.json`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/decoder/__init__.py` & `metarace-2.1.2/src/metarace/decoder/__init__.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/decoder/rrs.py` & `metarace-2.1.2/src/metarace/decoder/rrs.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/decoder/rru.py` & `metarace-2.1.2/src/metarace/decoder/rru.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/decoder/thbc.py` & `metarace-2.1.2/src/metarace/decoder/thbc.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/eventdb.py` & `metarace-2.1.2/src/metarace/eventdb.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/export.py` & `metarace-2.1.2/src/metarace/export.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/gemini.py` & `metarace-2.1.2/src/metarace/gemini.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/htlib.py` & `metarace-2.1.2/src/metarace/htlib.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/jsonconfig.py` & `metarace-2.1.2/src/metarace/jsonconfig.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/report.py` & `metarace-2.1.2/src/metarace/report.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/riderdb.py` & `metarace-2.1.2/src/metarace/riderdb.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/sender.py` & `metarace-2.1.2/src/metarace/sender.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/strops.py` & `metarace-2.1.2/src/metarace/strops.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/telegraph.py` & `metarace-2.1.2/src/metarace/telegraph.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/timy.py` & `metarace-2.1.2/src/metarace/timy.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/tod.py` & `metarace-2.1.2/src/metarace/tod.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace/unt4.py` & `metarace-2.1.2/src/metarace/unt4.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.1/src/metarace.egg-info/PKG-INFO` & `metarace-2.1.2/src/metarace.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: metarace
-Version: 2.1.1
+Version: 2.1.2
 Summary: Cyclesport results and timing toolkit
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace
 Keywords: cyclesport,results,timing
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
```

### Comparing `metarace-2.1.1/src/metarace.egg-info/SOURCES.txt` & `metarace-2.1.2/src/metarace.egg-info/SOURCES.txt`

 * *Files 6% similar despite different names*

```diff
@@ -19,14 +19,15 @@
 src/metarace/unt4.py
 src/metarace.egg-info/PKG-INFO
 src/metarace.egg-info/SOURCES.txt
 src/metarace.egg-info/dependency_links.txt
 src/metarace.egg-info/requires.txt
 src/metarace.egg-info/top_level.txt
 src/metarace/data/IOC_Codes.csv
+src/metarace/data/__init__.py
 src/metarace/data/bg_armfin.svg
 src/metarace/data/bg_armint.svg
 src/metarace/data/bg_armstart.svg
 src/metarace/data/bg_idle.svg
 src/metarace/data/bg_src.svg
 src/metarace/data/metarace.json
 src/metarace/data/metarace_icon.svg
```

