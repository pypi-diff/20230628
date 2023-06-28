# Comparing `tmp/spark_dummy_tools-0.2.3.tar.gz` & `tmp/spark_dummy_tools-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "spark_dummy_tools-0.2.3.tar", last modified: Wed Jun 28 06:48:55 2023, max compression
+gzip compressed data, was "spark_dummy_tools-0.3.0.tar", last modified: Wed Jun 28 07:02:19 2023, max compression
```

## Comparing `spark_dummy_tools-0.2.3.tar` & `spark_dummy_tools-0.3.0.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 06:48:55.702221 spark_dummy_tools-0.2.3/
--rw-rw-rw-   0        0        0     1092 2022-12-01 18:42:47.000000 spark_dummy_tools-0.2.3/LICENSE
--rw-rw-rw-   0        0        0        4 2023-06-26 03:19:39.000000 spark_dummy_tools-0.2.3/MANIFEST.in
--rw-rw-rw-   0        0        0     4254 2023-06-28 06:48:55.702221 spark_dummy_tools-0.2.3/PKG-INFO
--rw-rw-rw-   0        0        0     3495 2023-06-28 06:31:22.000000 spark_dummy_tools-0.2.3/README.md
--rw-rw-rw-   0        0        0      636 2023-06-26 03:37:00.000000 spark_dummy_tools-0.2.3/pyproject.toml
--rw-rw-rw-   0        0        0       86 2023-06-28 06:48:55.703221 spark_dummy_tools-0.2.3/setup.cfg
--rw-rw-rw-   0        0        0     1164 2023-06-28 06:48:36.000000 spark_dummy_tools-0.2.3/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:48:55.685218 spark_dummy_tools-0.2.3/spark_dummy_tools/
--rw-rw-rw-   0        0        0      372 2023-06-28 06:23:48.000000 spark_dummy_tools-0.2.3/spark_dummy_tools/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:48:55.700222 spark_dummy_tools-0.2.3/spark_dummy_tools/functions/
--rw-rw-rw-   0        0        0        0 2022-12-01 18:42:47.000000 spark_dummy_tools-0.2.3/spark_dummy_tools/functions/__init__.py
--rw-rw-rw-   0        0        0     9487 2023-06-28 06:48:36.000000 spark_dummy_tools-0.2.3/spark_dummy_tools/functions/generator.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:48:55.701221 spark_dummy_tools-0.2.3/spark_dummy_tools/utils/
--rw-rw-rw-   0        0        0       75 2022-12-01 18:42:47.000000 spark_dummy_tools-0.2.3/spark_dummy_tools/utils/__init__.py
--rw-rw-rw-   0        0        0      416 2023-06-04 03:38:46.000000 spark_dummy_tools-0.2.3/spark_dummy_tools/utils/color.py
--rw-rw-rw-   0        0        0     6983 2023-06-26 11:50:04.000000 spark_dummy_tools-0.2.3/spark_dummy_tools/utils/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:48:55.699222 spark_dummy_tools-0.2.3/spark_dummy_tools.egg-info/
--rw-rw-rw-   0        0        0     4254 2023-06-28 06:48:55.000000 spark_dummy_tools-0.2.3/spark_dummy_tools.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      480 2023-06-28 06:48:55.000000 spark_dummy_tools-0.2.3/spark_dummy_tools.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 06:48:55.000000 spark_dummy_tools-0.2.3/spark_dummy_tools.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      191 2023-06-28 06:48:55.000000 spark_dummy_tools-0.2.3/spark_dummy_tools.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-06-28 06:48:55.000000 spark_dummy_tools-0.2.3/spark_dummy_tools.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 07:02:19.706833 spark_dummy_tools-0.3.0/
+-rw-rw-rw-   0        0        0     1092 2022-12-01 18:42:47.000000 spark_dummy_tools-0.3.0/LICENSE
+-rw-rw-rw-   0        0        0        4 2023-06-26 03:19:39.000000 spark_dummy_tools-0.3.0/MANIFEST.in
+-rw-rw-rw-   0        0        0     4254 2023-06-28 07:02:19.706833 spark_dummy_tools-0.3.0/PKG-INFO
+-rw-rw-rw-   0        0        0     3495 2023-06-28 06:31:22.000000 spark_dummy_tools-0.3.0/README.md
+-rw-rw-rw-   0        0        0      636 2023-06-26 03:37:00.000000 spark_dummy_tools-0.3.0/pyproject.toml
+-rw-rw-rw-   0        0        0       86 2023-06-28 07:02:19.711834 spark_dummy_tools-0.3.0/setup.cfg
+-rw-rw-rw-   0        0        0     1164 2023-06-28 07:02:05.000000 spark_dummy_tools-0.3.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:02:19.680827 spark_dummy_tools-0.3.0/spark_dummy_tools/
+-rw-rw-rw-   0        0        0      372 2023-06-28 06:23:48.000000 spark_dummy_tools-0.3.0/spark_dummy_tools/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:02:19.702832 spark_dummy_tools-0.3.0/spark_dummy_tools/functions/
+-rw-rw-rw-   0        0        0        0 2022-12-01 18:42:47.000000 spark_dummy_tools-0.3.0/spark_dummy_tools/functions/__init__.py
+-rw-rw-rw-   0        0        0     9556 2023-06-28 07:01:11.000000 spark_dummy_tools-0.3.0/spark_dummy_tools/functions/generator.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:02:19.706833 spark_dummy_tools-0.3.0/spark_dummy_tools/utils/
+-rw-rw-rw-   0        0        0       75 2022-12-01 18:42:47.000000 spark_dummy_tools-0.3.0/spark_dummy_tools/utils/__init__.py
+-rw-rw-rw-   0        0        0      416 2023-06-04 03:38:46.000000 spark_dummy_tools-0.3.0/spark_dummy_tools/utils/color.py
+-rw-rw-rw-   0        0        0     6983 2023-06-26 11:50:04.000000 spark_dummy_tools-0.3.0/spark_dummy_tools/utils/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:02:19.701831 spark_dummy_tools-0.3.0/spark_dummy_tools.egg-info/
+-rw-rw-rw-   0        0        0     4254 2023-06-28 07:02:19.000000 spark_dummy_tools-0.3.0/spark_dummy_tools.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      480 2023-06-28 07:02:19.000000 spark_dummy_tools-0.3.0/spark_dummy_tools.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:02:19.000000 spark_dummy_tools-0.3.0/spark_dummy_tools.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      191 2023-06-28 07:02:19.000000 spark_dummy_tools-0.3.0/spark_dummy_tools.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 07:02:19.000000 spark_dummy_tools-0.3.0/spark_dummy_tools.egg-info/top_level.txt
```

### Comparing `spark_dummy_tools-0.2.3/LICENSE` & `spark_dummy_tools-0.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `spark_dummy_tools-0.2.3/PKG-INFO` & `spark_dummy_tools-0.3.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: spark_dummy_tools
-Version: 0.2.3
+Version: 0.3.0
 Summary: spark_dummy_tools
 Home-page: https://github.com/jonaqp/spark_dummy_tools/
 Author: Jonathan Quiza
 Author-email: jony327@gmail.com
 License: UNKNOWN
 Download-URL: https://github.com/jonaqp/spark_dummy_tools/archive/main.zip
 Keywords: spark,datax,schema
```

### Comparing `spark_dummy_tools-0.2.3/README.md` & `spark_dummy_tools-0.3.0/README.md`

 * *Files identical despite different names*

### Comparing `spark_dummy_tools-0.2.3/pyproject.toml` & `spark_dummy_tools-0.3.0/pyproject.toml`

 * *Files identical despite different names*

### Comparing `spark_dummy_tools-0.2.3/setup.py` & `spark_dummy_tools-0.3.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 from setuptools import find_packages
 
 setuppath = os.path.dirname(os.path.abspath(__file__))
 
 setup(
     name='spark_dummy_tools',
     packages=find_packages(),
-    version='0.2.3',
+    version='0.3.0',
     description='spark_dummy_tools',
     long_description=open(os.path.join(setuppath, 'README.md')).read(),
     long_description_content_type="text/markdown",
     author='Jonathan Quiza',
     author_email='jony327@gmail.com',
     url='https://github.com/jonaqp/spark_dummy_tools/',
     download_url='https://github.com/jonaqp/spark_dummy_tools/archive/main.zip',
```

### Comparing `spark_dummy_tools-0.2.3/spark_dummy_tools/functions/generator.py` & `spark_dummy_tools-0.3.0/spark_dummy_tools/functions/generator.py`

 * *Files 2% similar despite different names*

```diff
@@ -91,17 +91,16 @@
             df3 = df3.withColumn(f"{column_name}", func.col(f"{column_name}").cast(f"{column_type}"))
         elif column_type.startswith("date"):
             df3 = df3.withColumn(f"{column_name}", func.col(f"{column_name}").cast("date"))
         elif column_type.startswith("timestamp"):
             df3 = df3.withColumn(f"{column_name}", func.col(f"{column_name}").cast("timestamp"))
 
     directory_dummy = "DIRECTORY_DUMMY"
-    if os.path.exists(directory_dummy):
+    if os.path.exists(os.path.join(directory_dummy)):
         shutil.rmtree(directory_dummy)
-
     path_directory = os.path.join(directory_dummy, table_name)
     if is_windows:
         path_directory = path_directory.replace("\\", "/")
     if not os.path.exists(path_directory):
         os.makedirs(path_directory)
     df3.coalesce(1).write.partitionBy(partition_colum).mode("overwrite").parquet(path_directory)
 
@@ -175,16 +174,16 @@
             df3 = df3.withColumn(f"{column_name}", func.col(f"{column_name}").cast(f"{column_type}"))
         elif column_type.startswith("date"):
             df3 = df3.withColumn(f"{column_name}", func.col(f"{column_name}").cast("date"))
         elif column_type.startswith("timestamp"):
             df3 = df3.withColumn(f"{column_name}", func.col(f"{column_name}").cast("timestamp"))
 
     directory_dummy = "DIRECTORY_DUMMY"
-    shutil.rmtree(directory_dummy)
-
+    if os.path.exists(os.path.join(directory_dummy)):
+        shutil.rmtree(directory_dummy)
     path_directory = os.path.join(directory_dummy, table_name)
     if is_windows:
         path_directory = path_directory.replace("\\", "/")
     if not os.path.exists(path_directory):
         os.makedirs(path_directory)
     df3.coalesce(1).write.partitionBy(partition_colum).mode("overwrite").parquet(path_directory)
```

### Comparing `spark_dummy_tools-0.2.3/spark_dummy_tools/utils/utils.py` & `spark_dummy_tools-0.3.0/spark_dummy_tools/utils/utils.py`

 * *Files identical despite different names*

### Comparing `spark_dummy_tools-0.2.3/spark_dummy_tools.egg-info/PKG-INFO` & `spark_dummy_tools-0.3.0/spark_dummy_tools.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: spark-dummy-tools
-Version: 0.2.3
+Version: 0.3.0
 Summary: spark_dummy_tools
 Home-page: https://github.com/jonaqp/spark_dummy_tools/
 Author: Jonathan Quiza
 Author-email: jony327@gmail.com
 License: UNKNOWN
 Download-URL: https://github.com/jonaqp/spark_dummy_tools/archive/main.zip
 Keywords: spark,datax,schema
```

