# Comparing `tmp/pyintelx-0.1.8.tar.gz` & `tmp/pyintelx-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyintelx-0.1.8.tar", last modified: Wed Jun 28 15:22:02 2023, max compression
+gzip compressed data, was "pyintelx-0.2.0.tar", last modified: Wed Jun 28 15:48:05 2023, max compression
```

## Comparing `pyintelx-0.1.8.tar` & `pyintelx-0.2.0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:22:02.681153 pyintelx-0.1.8/
--rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 15:22:02.681153 pyintelx-0.1.8/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2031 2023-06-28 15:21:51.000000 pyintelx-0.1.8/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:22:02.681153 pyintelx-0.1.8/pyintelx/
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:21:51.000000 pyintelx-0.1.8/pyintelx/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:22:02.681153 pyintelx-0.1.8/pyintelx/cli/
--rw-r--r--   0 runner    (1001) docker     (123)    10502 2023-06-28 15:21:51.000000 pyintelx-0.1.8/pyintelx/cli/pyintelx
--rw-r--r--   0 runner    (1001) docker     (123)     2991 2023-06-28 15:21:51.000000 pyintelx-0.1.8/pyintelx/pyintelx.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:22:02.681153 pyintelx-0.1.8/pyintelx.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 15:22:02.000000 pyintelx-0.1.8/pyintelx.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      210 2023-06-28 15:22:02.000000 pyintelx-0.1.8/pyintelx.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:22:02.000000 pyintelx-0.1.8/pyintelx.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 15:22:02.000000 pyintelx-0.1.8/pyintelx.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:22:02.681153 pyintelx-0.1.8/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-28 15:21:51.000000 pyintelx-0.1.8/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:48:05.280073 pyintelx-0.2.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 15:48:05.280073 pyintelx-0.2.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2031 2023-06-28 15:47:55.000000 pyintelx-0.2.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:48:05.280073 pyintelx-0.2.0/pyintelx/
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:47:55.000000 pyintelx-0.2.0/pyintelx/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:48:05.280073 pyintelx-0.2.0/pyintelx/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)    10502 2023-06-28 15:47:55.000000 pyintelx-0.2.0/pyintelx/cli/pyintelx
+-rw-r--r--   0 runner    (1001) docker     (123)     3055 2023-06-28 15:47:55.000000 pyintelx-0.2.0/pyintelx/pyintelx.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:48:05.280073 pyintelx-0.2.0/pyintelx.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2642 2023-06-28 15:48:05.000000 pyintelx-0.2.0/pyintelx.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      210 2023-06-28 15:48:05.000000 pyintelx-0.2.0/pyintelx.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:48:05.000000 pyintelx-0.2.0/pyintelx.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 15:48:05.000000 pyintelx-0.2.0/pyintelx.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:48:05.280073 pyintelx-0.2.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      884 2023-06-28 15:47:55.000000 pyintelx-0.2.0/setup.py
```

### Comparing `pyintelx-0.1.8/PKG-INFO` & `pyintelx-0.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyintelx
-Version: 0.1.8
+Version: 0.2.0
 Summary: This lib add support to use the Identity API from Intelx.io
 Home-page: https://github.com/csirtamericas/pyintelxio
 Author: Fermin Baudino, Einar Lanfranco, Federico Carrilao
 License: MIT
 Keywords: python, package, distribution
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Natural Language :: English
```

### Comparing `pyintelx-0.1.8/README.md` & `pyintelx-0.2.0/README.md`

 * *Files identical despite different names*

### Comparing `pyintelx-0.1.8/pyintelx/cli/pyintelx` & `pyintelx-0.2.0/pyintelx/cli/pyintelx`

 * *Files identical despite different names*

### Comparing `pyintelx-0.1.8/pyintelx/pyintelx.py` & `pyintelx-0.2.0/pyintelx/pyintelx.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,17 +39,18 @@
             search_id = r.json()['id']
         if (len(str(search_id)) <= 3):
             print(
                 f"[!] intelx.IDENTITY_SEARCH() Received {self.get_error(search_id)}")
         while not done:
             time.sleep(1)
             r = self.get_search_results(search_id, maxresults=maxresults)
-            for a in r['records']:
-                results.append(a)
-            maxresults -= len(r['records'])
+            if (r["status"] == 0 and r["records"]):
+                for a in r['records']:
+                    results.append(a)
+                maxresults -= len(r['records'])
             if (r['status'] == 1 or r['status'] == 2 or maxresults <= 0):
                 if (maxresults <= 0):
                     self.terminate_search(search_id)
                 done = True
         return {'records': results}
 
     def terminate_search(self, id):
```

### Comparing `pyintelx-0.1.8/pyintelx.egg-info/PKG-INFO` & `pyintelx-0.2.0/pyintelx.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyintelx
-Version: 0.1.8
+Version: 0.2.0
 Summary: This lib add support to use the Identity API from Intelx.io
 Home-page: https://github.com/csirtamericas/pyintelxio
 Author: Fermin Baudino, Einar Lanfranco, Federico Carrilao
 License: MIT
 Keywords: python, package, distribution
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Natural Language :: English
```

### Comparing `pyintelx-0.1.8/setup.py` & `pyintelx-0.2.0/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
     
 
 setup(
     name='pyintelx',
-    version='0.1.8',
+    version='0.2.0',
     description='This lib add support to use the Identity API from Intelx.io',
     license='MIT',
     keywords=['python, package, distribution'],
     long_description=long_description,
     long_description_content_type="text/markdown",
     author='Fermin Baudino, Einar Lanfranco, Federico Carrilao',
     url='https://github.com/csirtamericas/pyintelxio',
```

