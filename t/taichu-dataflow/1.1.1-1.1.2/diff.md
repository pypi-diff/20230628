# Comparing `tmp/taichu-dataflow-1.1.1.tar.gz` & `tmp/taichu-dataflow-1.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/taichu-dataflow-1.1.1.tar", last modified: Wed Jun 28 06:53:32 2023, max compression
+gzip compressed data, was "dist/taichu-dataflow-1.1.2.tar", last modified: Wed Jun 28 07:49:08 2023, max compression
```

## Comparing `taichu-dataflow-1.1.1.tar` & `taichu-dataflow-1.1.2.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/
--rw-r--r--   0 shenli     (501) staff       (20)      258 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/PKG-INFO
-drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/
--rw-r--r--   0 shenli     (501) staff       (20)      258 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/PKG-INFO
--rw-r--r--   0 shenli     (501) staff       (20)      473 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/SOURCES.txt
--rw-r--r--   0 shenli     (501) staff       (20)       64 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/entry_points.txt
--rw-r--r--   0 shenli     (501) staff       (20)       50 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/requires.txt
--rw-r--r--   0 shenli     (501) staff       (20)       16 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/top_level.txt
--rw-r--r--   0 shenli     (501) staff       (20)        1 2023-06-28 06:53:31.000000 taichu-dataflow-1.1.1/taichu_dataflow.egg-info/dependency_links.txt
--rw-r--r--   0 shenli     (501) staff       (20)      194 2023-06-12 03:14:29.000000 taichu-dataflow-1.1.1/README.md
--rw-r--r--   0 shenli     (501) staff       (20)      888 2023-06-28 06:52:56.000000 taichu-dataflow-1.1.1/setup.py
--rw-r--r--   0 shenli     (501) staff       (20)       38 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/setup.cfg
-drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/taichu_dataflow/
--rw-r--r--   0 shenli     (501) staff       (20)     1805 2023-06-26 06:38:12.000000 taichu-dataflow-1.1.1/taichu_dataflow/command.py
--rw-r--r--   0 shenli     (501) staff       (20)     1434 2023-06-28 06:50:26.000000 taichu-dataflow-1.1.1/taichu_dataflow/__init__.py
--rw-r--r--   0 shenli     (501) staff       (20)     3575 2023-06-28 06:51:11.000000 taichu-dataflow-1.1.1/taichu_dataflow/export_back.py
-drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 06:53:32.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/
--rw-r--r--   0 shenli     (501) staff       (20)     1116 2023-06-28 06:51:41.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/env.py
--rw-r--r--   0 shenli     (501) staff       (20)     2169 2023-06-26 06:38:12.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/alluxio.py
--rw-r--r--   0 shenli     (501) staff       (20)     1256 2023-06-28 06:52:15.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/__init__.py
--rw-r--r--   0 shenli     (501) staff       (20)     1034 2023-06-28 06:52:43.000000 taichu-dataflow-1.1.1/taichu_dataflow/storage/obs.py
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/
+-rw-r--r--   0 shenli     (501) staff       (20)      258 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/PKG-INFO
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow.egg-info/
+-rw-r--r--   0 shenli     (501) staff       (20)      258 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow.egg-info/PKG-INFO
+-rw-r--r--   0 shenli     (501) staff       (20)      473 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow.egg-info/SOURCES.txt
+-rw-r--r--   0 shenli     (501) staff       (20)       64 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow.egg-info/entry_points.txt
+-rw-r--r--   0 shenli     (501) staff       (20)       50 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow.egg-info/requires.txt
+-rw-r--r--   0 shenli     (501) staff       (20)       16 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow.egg-info/top_level.txt
+-rw-r--r--   0 shenli     (501) staff       (20)        1 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow.egg-info/dependency_links.txt
+-rw-r--r--   0 shenli     (501) staff       (20)      194 2023-06-12 03:14:29.000000 taichu-dataflow-1.1.2/README.md
+-rw-r--r--   0 shenli     (501) staff       (20)      888 2023-06-28 07:46:30.000000 taichu-dataflow-1.1.2/setup.py
+-rw-r--r--   0 shenli     (501) staff       (20)       38 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/setup.cfg
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow/
+-rw-r--r--   0 shenli     (501) staff       (20)     1805 2023-06-26 06:38:12.000000 taichu-dataflow-1.1.2/taichu_dataflow/command.py
+-rw-r--r--   0 shenli     (501) staff       (20)     1482 2023-06-28 07:45:45.000000 taichu-dataflow-1.1.2/taichu_dataflow/__init__.py
+-rw-r--r--   0 shenli     (501) staff       (20)     3575 2023-06-28 06:51:11.000000 taichu-dataflow-1.1.2/taichu_dataflow/export_back.py
+drwxr-xr-x   0 shenli     (501) staff       (20)        0 2023-06-28 07:49:08.000000 taichu-dataflow-1.1.2/taichu_dataflow/storage/
+-rw-r--r--   0 shenli     (501) staff       (20)     1116 2023-06-28 06:51:41.000000 taichu-dataflow-1.1.2/taichu_dataflow/storage/env.py
+-rw-r--r--   0 shenli     (501) staff       (20)     2169 2023-06-26 06:38:12.000000 taichu-dataflow-1.1.2/taichu_dataflow/storage/alluxio.py
+-rw-r--r--   0 shenli     (501) staff       (20)     1256 2023-06-28 06:52:15.000000 taichu-dataflow-1.1.2/taichu_dataflow/storage/__init__.py
+-rw-r--r--   0 shenli     (501) staff       (20)     1034 2023-06-28 06:52:43.000000 taichu-dataflow-1.1.2/taichu_dataflow/storage/obs.py
```

### Comparing `taichu-dataflow-1.1.1/setup.py` & `taichu-dataflow-1.1.2/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 
     long_description = ''
     # with open('README.md', 'r') as f:
     #     long_description = f.read()
 
     setup(
         name=name,
-        version='1.1.1',
+        version='1.1.2',
         description='taichu serve is a tool for serving dataflow',
         long_description=long_description,
         author='taichu platform team',
         python_requires=">=3.6.0",
         url='',
         keywords='taichu',
         packages=find_packages(),
```

### Comparing `taichu-dataflow-1.1.1/taichu_dataflow/command.py` & `taichu-dataflow-1.1.2/taichu_dataflow/command.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.1/taichu_dataflow/__init__.py` & `taichu-dataflow-1.1.2/taichu_dataflow/__init__.py`

 * *Files 11% similar despite different names*

```diff
@@ -26,15 +26,15 @@
             print(f"Failed to send log entry: {repr(e)}")
 
 
 log_collector_url = 'http://58.48.42.242:8088/log/collector'
 
 
 def init_logger(url):
-    log_dir = f'/tmp/dataflow/'
+    log_dir = '/tmp/dataflow/' if os.name == 'posix' else 'C:\\tmp\\dataflow\\'
     os.makedirs(log_dir, exist_ok=True)
     logging.basicConfig(
         handlers=[
             logging.StreamHandler(sys.stdout),
             logging.FileHandler(f'{log_dir}{datetime.now().strftime("%Y-%m-%d")}.log', mode="a")
         ],
         level=logging.INFO,
```

### Comparing `taichu-dataflow-1.1.1/taichu_dataflow/export_back.py` & `taichu-dataflow-1.1.2/taichu_dataflow/export_back.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.1/taichu_dataflow/storage/env.py` & `taichu-dataflow-1.1.2/taichu_dataflow/storage/env.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.1/taichu_dataflow/storage/alluxio.py` & `taichu-dataflow-1.1.2/taichu_dataflow/storage/alluxio.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.1/taichu_dataflow/storage/__init__.py` & `taichu-dataflow-1.1.2/taichu_dataflow/storage/__init__.py`

 * *Files identical despite different names*

### Comparing `taichu-dataflow-1.1.1/taichu_dataflow/storage/obs.py` & `taichu-dataflow-1.1.2/taichu_dataflow/storage/obs.py`

 * *Files identical despite different names*

