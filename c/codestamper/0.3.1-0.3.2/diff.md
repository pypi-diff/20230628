# Comparing `tmp/codestamper-0.3.1.tar.gz` & `tmp/codestamper-0.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "codestamper-0.3.1.tar", last modified: Mon Jun 26 09:56:33 2023, max compression
+gzip compressed data, was "codestamper-0.3.2.tar", last modified: Wed Jun 28 08:32:33 2023, max compression
```

## Comparing `codestamper-0.3.1.tar` & `codestamper-0.3.2.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-26 09:56:33.573502 codestamper-0.3.1/
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     1070 2023-06-26 09:38:46.000000 codestamper-0.3.1/LICENSE
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)       42 2023-06-26 09:38:46.000000 codestamper-0.3.1/MANIFEST.in
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     8025 2023-06-26 09:56:33.573502 codestamper-0.3.1/PKG-INFO
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     7578 2023-06-26 09:38:46.000000 codestamper-0.3.1/README.md
-drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-26 09:56:33.573502 codestamper-0.3.1/codestamper/
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)      144 2023-06-26 09:38:46.000000 codestamper-0.3.1/codestamper/__init__.py
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     6379 2023-06-26 09:48:55.000000 codestamper-0.3.1/codestamper/codestamper.py
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     4667 2023-06-26 09:46:03.000000 codestamper-0.3.1/codestamper/gitutils.py
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     3600 2023-06-26 09:47:51.000000 codestamper-0.3.1/codestamper/pythonenv.py
-drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-26 09:56:33.573502 codestamper-0.3.1/codestamper.egg-info/
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     8025 2023-06-26 09:56:33.000000 codestamper-0.3.1/codestamper.egg-info/PKG-INFO
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)      349 2023-06-26 09:56:33.000000 codestamper-0.3.1/codestamper.egg-info/SOURCES.txt
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)        1 2023-06-26 09:56:33.000000 codestamper-0.3.1/codestamper.egg-info/dependency_links.txt
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)       12 2023-06-26 09:56:33.000000 codestamper-0.3.1/codestamper.egg-info/requires.txt
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)       12 2023-06-26 09:56:33.000000 codestamper-0.3.1/codestamper.egg-info/top_level.txt
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)       11 2023-06-26 09:38:46.000000 codestamper-0.3.1/requirements.txt
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)       38 2023-06-26 09:56:33.573502 codestamper-0.3.1/setup.cfg
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)      801 2023-06-26 09:56:17.000000 codestamper-0.3.1/setup.py
-drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-26 09:56:33.573502 codestamper-0.3.1/tests/
--rw-rw-rw-   0 codespace  (1000) codespace  (1000)     2020 2023-06-26 09:38:46.000000 codestamper-0.3.1/tests/test_basic.py
+drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-28 08:32:33.803576 codestamper-0.3.2/
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     1070 2023-06-26 09:38:46.000000 codestamper-0.3.2/LICENSE
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)       42 2023-06-26 09:38:46.000000 codestamper-0.3.2/MANIFEST.in
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     8025 2023-06-28 08:32:33.803576 codestamper-0.3.2/PKG-INFO
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     7578 2023-06-28 08:27:23.000000 codestamper-0.3.2/README.md
+drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-28 08:32:33.803576 codestamper-0.3.2/codestamper/
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)      144 2023-06-26 09:38:46.000000 codestamper-0.3.2/codestamper/__init__.py
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     6379 2023-06-26 09:48:55.000000 codestamper-0.3.2/codestamper/codestamper.py
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     4667 2023-06-26 09:46:03.000000 codestamper-0.3.2/codestamper/gitutils.py
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     3802 2023-06-28 08:31:22.000000 codestamper-0.3.2/codestamper/pythonenv.py
+drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-28 08:32:33.803576 codestamper-0.3.2/codestamper.egg-info/
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     8025 2023-06-28 08:32:33.000000 codestamper-0.3.2/codestamper.egg-info/PKG-INFO
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)      349 2023-06-28 08:32:33.000000 codestamper-0.3.2/codestamper.egg-info/SOURCES.txt
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)        1 2023-06-28 08:32:33.000000 codestamper-0.3.2/codestamper.egg-info/dependency_links.txt
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)       12 2023-06-28 08:32:33.000000 codestamper-0.3.2/codestamper.egg-info/requires.txt
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)       12 2023-06-28 08:32:33.000000 codestamper-0.3.2/codestamper.egg-info/top_level.txt
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)       11 2023-06-26 09:38:46.000000 codestamper-0.3.2/requirements.txt
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)       38 2023-06-28 08:32:33.803576 codestamper-0.3.2/setup.cfg
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)      801 2023-06-28 08:27:45.000000 codestamper-0.3.2/setup.py
+drwxrwxrwx   0 codespace  (1000) codespace  (1000)        0 2023-06-28 08:32:33.803576 codestamper-0.3.2/tests/
+-rw-rw-rw-   0 codespace  (1000) codespace  (1000)     2020 2023-06-26 09:38:46.000000 codestamper-0.3.2/tests/test_basic.py
```

### Comparing `codestamper-0.3.1/LICENSE` & `codestamper-0.3.2/LICENSE`

 * *Files identical despite different names*

### Comparing `codestamper-0.3.1/PKG-INFO` & `codestamper-0.3.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: codestamper
-Version: 0.3.1
+Version: 0.3.2
 Summary: Ensure code traceability in ML experiments
 Home-page: https://github.com/bmsan/codestamper
 Author: Bogdan Sandoi
 Author-email: bogdan.sandoi@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `codestamper-0.3.1/README.md` & `codestamper-0.3.2/README.md`

 * *Files identical despite different names*

### Comparing `codestamper-0.3.1/codestamper/codestamper.py` & `codestamper-0.3.2/codestamper/codestamper.py`

 * *Files identical despite different names*

### Comparing `codestamper-0.3.1/codestamper/gitutils.py` & `codestamper-0.3.2/codestamper/gitutils.py`

 * *Files identical despite different names*

### Comparing `codestamper-0.3.1/codestamper/pythonenv.py` & `codestamper-0.3.2/codestamper/pythonenv.py`

 * *Files 20% similar despite different names*

```diff
@@ -49,14 +49,19 @@
             return
         cmd = ["conda", "env", "export"]
         try:
             data = subprocess.check_output(cmd).decode("utf-8")
         except FileNotFoundError:
             # On Windows conda command is seen only for shell=True
             data = subprocess.check_output(' '.join(cmd), shell=True).decode("utf-8")
+        # workaround for pycharm terminal on windows which adds extra non-printable chars
+        escape_char = '\x1b'
+        if escape_char in data:
+            data = data[:data.index(escape_char)]
+
         self.raw = data
         self.parsed = yaml.safe_load(data)
         self._interpret_deps(self.parsed["dependencies"])
 
     def _interpret_deps(self, data):
         conda_deps = {}
         pip_deps = {}
```

### Comparing `codestamper-0.3.1/codestamper.egg-info/PKG-INFO` & `codestamper-0.3.2/codestamper.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: codestamper
-Version: 0.3.1
+Version: 0.3.2
 Summary: Ensure code traceability in ML experiments
 Home-page: https://github.com/bmsan/codestamper
 Author: Bogdan Sandoi
 Author-email: bogdan.sandoi@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `codestamper-0.3.1/setup.py` & `codestamper-0.3.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -4,15 +4,15 @@
     long_description = fh.read()
 
 with open("requirements.txt", "r") as f:
     requirements = f.read().splitlines()
 
 setuptools.setup(
     name="codestamper",
-    version="0.3.1",
+    version="0.3.2",
     author="Bogdan Sandoi",
     author_email="bogdan.sandoi@gmail.com",
     description=("Ensure code traceability in ML experiments"),
     long_description=long_description,
     long_description_content_type="text/markdown",
     packages=setuptools.find_packages(exclude=("tests",)),
     classifiers=[
```

### Comparing `codestamper-0.3.1/tests/test_basic.py` & `codestamper-0.3.2/tests/test_basic.py`

 * *Files identical despite different names*

