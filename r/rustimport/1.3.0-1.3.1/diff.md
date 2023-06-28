# Comparing `tmp/rustimport-1.3.0.tar.gz` & `tmp/rustimport-1.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "rustimport-1.3.0.tar", last modified: Mon Apr 24 13:07:32 2023, max compression
+gzip compressed data, was "rustimport-1.3.1.tar", last modified: Wed Jun 28 10:30:41 2023, max compression
```

## Comparing `rustimport-1.3.0.tar` & `rustimport-1.3.1.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-24 13:07:32.421646 rustimport-1.3.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-04-24 13:07:11.000000 rustimport-1.3.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       60 2023-04-24 13:07:11.000000 rustimport-1.3.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    13693 2023-04-24 13:07:32.421646 rustimport-1.3.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13070 2023-04-24 13:07:11.000000 rustimport-1.3.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-04-24 13:07:11.000000 rustimport-1.3.0/VERSION
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-24 13:07:32.417646 rustimport-1.3.0/rustimport/
--rw-r--r--   0 runner    (1001) docker     (123)     6949 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6951 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3438 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/checksum.py
--rw-r--r--   0 runner    (1001) docker     (123)     5087 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/compiler.py
--rw-r--r--   0 runner    (1001) docker     (123)      627 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/error_handling.py
--rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/find.py
--rw-r--r--   0 runner    (1001) docker     (123)     2127 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/import_hook.py
--rw-r--r--   0 runner    (1001) docker     (123)    12656 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/importable.py
--rw-r--r--   0 runner    (1001) docker     (123)      942 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/load.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-24 13:07:32.421646 rustimport-1.3.0/rustimport/pre_processing/
--rw-r--r--   0 runner    (1001) docker     (123)     2738 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/pre_processing/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1444 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/pre_processing/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     2640 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/pre_processing/pyo3_template.py
--rw-r--r--   0 runner    (1001) docker     (123)     2596 2023-04-24 13:07:11.000000 rustimport-1.3.0/rustimport/settings.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-24 13:07:32.421646 rustimport-1.3.0/rustimport.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13693 2023-04-24 13:07:32.000000 rustimport-1.3.0/rustimport.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      654 2023-04-24 13:07:32.000000 rustimport-1.3.0/rustimport.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-24 13:07:32.000000 rustimport-1.3.0/rustimport.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-04-24 13:07:32.000000 rustimport-1.3.0/rustimport.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-04-24 13:07:32.000000 rustimport-1.3.0/rustimport.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       11 2023-04-24 13:07:32.000000 rustimport-1.3.0/rustimport.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-04-24 13:07:32.421646 rustimport-1.3.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      912 2023-04-24 13:07:11.000000 rustimport-1.3.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-04-24 13:07:32.421646 rustimport-1.3.0/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      141 2023-04-24 13:07:11.000000 rustimport-1.3.0/tests/run_all.py
--rw-r--r--   0 runner    (1001) docker     (123)     7004 2023-04-24 13:07:11.000000 rustimport-1.3.0/tests/test_cli.py
--rw-r--r--   0 runner    (1001) docker     (123)     2765 2023-04-24 13:07:11.000000 rustimport-1.3.0/tests/test_examples.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:30:41.323500 rustimport-1.3.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1082 2023-06-28 10:30:30.000000 rustimport-1.3.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       60 2023-06-28 10:30:30.000000 rustimport-1.3.1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    13693 2023-06-28 10:30:41.323500 rustimport-1.3.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13070 2023-06-28 10:30:30.000000 rustimport-1.3.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 10:30:30.000000 rustimport-1.3.1/VERSION
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:30:41.323500 rustimport-1.3.1/rustimport/
+-rw-r--r--   0 runner    (1001) docker     (123)     6949 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6951 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3438 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/checksum.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5155 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/compiler.py
+-rw-r--r--   0 runner    (1001) docker     (123)      627 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/error_handling.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/find.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2127 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/import_hook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12656 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/importable.py
+-rw-r--r--   0 runner    (1001) docker     (123)      942 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/load.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:30:41.323500 rustimport-1.3.1/rustimport/pre_processing/
+-rw-r--r--   0 runner    (1001) docker     (123)     2738 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/pre_processing/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1444 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/pre_processing/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2640 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/pre_processing/pyo3_template.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2596 2023-06-28 10:30:30.000000 rustimport-1.3.1/rustimport/settings.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:30:41.323500 rustimport-1.3.1/rustimport.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13693 2023-06-28 10:30:41.000000 rustimport-1.3.1/rustimport.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      654 2023-06-28 10:30:41.000000 rustimport-1.3.1/rustimport.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:30:41.000000 rustimport-1.3.1/rustimport.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:30:41.000000 rustimport-1.3.1/rustimport.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-28 10:30:41.000000 rustimport-1.3.1/rustimport.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-28 10:30:41.000000 rustimport-1.3.1/rustimport.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:30:41.323500 rustimport-1.3.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 10:30:30.000000 rustimport-1.3.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:30:41.323500 rustimport-1.3.1/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      141 2023-06-28 10:30:30.000000 rustimport-1.3.1/tests/run_all.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7004 2023-06-28 10:30:30.000000 rustimport-1.3.1/tests/test_cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2765 2023-06-28 10:30:30.000000 rustimport-1.3.1/tests/test_examples.py
```

### Comparing `rustimport-1.3.0/LICENSE` & `rustimport-1.3.1/LICENSE`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/PKG-INFO` & `rustimport-1.3.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: rustimport
-Version: 1.3.0
+Version: 1.3.1
 Summary: Import Rust files directly from Python!
 Home-page: https://github.com/mityax/rustimport
 Author: mityax
 License: MIT
 Platform: any
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
```

### Comparing `rustimport-1.3.0/README.md` & `rustimport-1.3.1/README.md`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/__init__.py` & `rustimport-1.3.1/rustimport/__init__.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/__main__.py` & `rustimport-1.3.1/rustimport/__main__.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/checksum.py` & `rustimport-1.3.1/rustimport/checksum.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/compiler.py` & `rustimport-1.3.1/rustimport/compiler.py`

 * *Files 2% similar despite different names*

```diff
@@ -98,15 +98,16 @@
         while (exit_code := proc.poll()) is None:
             line = proc.stdout.readline()
 
             if line.strip():
                 messages.append(message := json.loads(line))
 
                 if message.get('reason') == 'compiler-artifact':
-                    if os.path.dirname(message.get('manifest_path')) == abs_crate_path:
+                    manifest_path = os.path.realpath(message.get('manifest_path'))
+                    if os.path.dirname(manifest_path) == abs_crate_path:
                         artifact_path = message['filenames'][0]
                 elif message.get('reason') == 'compiler-message':
                     if not proc.stderr:
                         sys.stderr.write(message['message']['rendered'])
                     else:
                         error_output.append(message['message']['rendered'])
```

### Comparing `rustimport-1.3.0/rustimport/error_handling.py` & `rustimport-1.3.1/rustimport/error_handling.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/find.py` & `rustimport-1.3.1/rustimport/find.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/import_hook.py` & `rustimport-1.3.1/rustimport/import_hook.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/importable.py` & `rustimport-1.3.1/rustimport/importable.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/load.py` & `rustimport-1.3.1/rustimport/load.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/pre_processing/__init__.py` & `rustimport-1.3.1/rustimport/pre_processing/__init__.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/pre_processing/base.py` & `rustimport-1.3.1/rustimport/pre_processing/base.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/pre_processing/pyo3_template.py` & `rustimport-1.3.1/rustimport/pre_processing/pyo3_template.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport/settings.py` & `rustimport-1.3.1/rustimport/settings.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/rustimport.egg-info/PKG-INFO` & `rustimport-1.3.1/rustimport.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: rustimport
-Version: 1.3.0
+Version: 1.3.1
 Summary: Import Rust files directly from Python!
 Home-page: https://github.com/mityax/rustimport
 Author: mityax
 License: MIT
 Platform: any
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
```

### Comparing `rustimport-1.3.0/rustimport.egg-info/SOURCES.txt` & `rustimport-1.3.1/rustimport.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/setup.py` & `rustimport-1.3.1/setup.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/tests/test_cli.py` & `rustimport-1.3.1/tests/test_cli.py`

 * *Files identical despite different names*

### Comparing `rustimport-1.3.0/tests/test_examples.py` & `rustimport-1.3.1/tests/test_examples.py`

 * *Files identical despite different names*

