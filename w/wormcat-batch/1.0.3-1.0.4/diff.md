# Comparing `tmp/wormcat_batch-1.0.3.tar.gz` & `tmp/wormcat_batch-1.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "wormcat_batch-1.0.3.tar", last modified: Wed Jun 28 11:45:23 2023, max compression
+gzip compressed data, was "wormcat_batch-1.0.4.tar", last modified: Wed Jun 28 11:53:51 2023, max compression
```

## Comparing `wormcat_batch-1.0.3.tar` & `wormcat_batch-1.0.4.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:45:23.333069 wormcat_batch-1.0.3/
--rw-r--r--   0 dan        (501) staff       (20)       95 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/MANIFEST.in
--rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-28 11:45:23.332940 wormcat_batch-1.0.3/PKG-INFO
--rw-r--r--   0 dan        (501) staff       (20)     2228 2023-06-28 11:43:14.000000 wormcat_batch-1.0.3/README.md
--rw-r--r--   0 dan        (501) staff       (20)       38 2023-06-28 11:45:23.333104 wormcat_batch-1.0.3/setup.cfg
--rw-r--r--   0 dan        (501) staff       (20)      685 2023-06-28 11:33:56.000000 wormcat_batch-1.0.3/setup.py
-drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:45:23.331923 wormcat_batch-1.0.3/wormcat_batch/
--rw-r--r--   0 dan        (501) staff       (20)     2024 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/wormcat_batch/create_wormcat_xlsx.py
--rw-r--r--   0 dan        (501) staff       (20)     2486 2023-06-27 18:05:20.000000 wormcat_batch-1.0.3/wormcat_batch/execute_r.py
--rwxr-xr-x   0 dan        (501) staff       (20)       46 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/wormcat_batch/is_wormcat_installed.R
--rwxr-xr-x   0 dan        (501) staff       (20)     7380 2023-06-28 11:39:52.000000 wormcat_batch-1.0.3/wormcat_batch/run_wormcat_batch.py
--rwxr-xr-x   0 dan        (501) staff       (20)     1446 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/wormcat_batch/worm_cat.R
-drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:45:23.332766 wormcat_batch-1.0.3/wormcat_batch.egg-info/
--rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/PKG-INFO
--rw-r--r--   0 dan        (501) staff       (20)      451 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/SOURCES.txt
--rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/dependency_links.txt
--rw-r--r--   0 dan        (501) staff       (20)       69 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/entry_points.txt
--rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/not-zip-safe
--rw-r--r--   0 dan        (501) staff       (20)       23 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/requires.txt
--rw-r--r--   0 dan        (501) staff       (20)       14 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/top_level.txt
+drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:53:51.844210 wormcat_batch-1.0.4/
+-rw-r--r--   0 dan        (501) staff       (20)       95 2022-08-16 12:41:26.000000 wormcat_batch-1.0.4/MANIFEST.in
+-rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-28 11:53:51.844097 wormcat_batch-1.0.4/PKG-INFO
+-rw-r--r--   0 dan        (501) staff       (20)     2346 2023-06-28 11:53:36.000000 wormcat_batch-1.0.4/README.md
+-rw-r--r--   0 dan        (501) staff       (20)       38 2023-06-28 11:53:51.844243 wormcat_batch-1.0.4/setup.cfg
+-rw-r--r--   0 dan        (501) staff       (20)      685 2023-06-28 11:53:33.000000 wormcat_batch-1.0.4/setup.py
+drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:53:51.843138 wormcat_batch-1.0.4/wormcat_batch/
+-rw-r--r--   0 dan        (501) staff       (20)     2024 2022-08-16 12:41:26.000000 wormcat_batch-1.0.4/wormcat_batch/create_wormcat_xlsx.py
+-rw-r--r--   0 dan        (501) staff       (20)     2486 2023-06-27 18:05:20.000000 wormcat_batch-1.0.4/wormcat_batch/execute_r.py
+-rwxr-xr-x   0 dan        (501) staff       (20)       46 2022-08-16 12:41:26.000000 wormcat_batch-1.0.4/wormcat_batch/is_wormcat_installed.R
+-rwxr-xr-x   0 dan        (501) staff       (20)     7382 2023-06-28 11:52:40.000000 wormcat_batch-1.0.4/wormcat_batch/run_wormcat_batch.py
+-rwxr-xr-x   0 dan        (501) staff       (20)     1446 2022-08-16 12:41:26.000000 wormcat_batch-1.0.4/wormcat_batch/worm_cat.R
+drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:53:51.843960 wormcat_batch-1.0.4/wormcat_batch.egg-info/
+-rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-28 11:53:51.000000 wormcat_batch-1.0.4/wormcat_batch.egg-info/PKG-INFO
+-rw-r--r--   0 dan        (501) staff       (20)      451 2023-06-28 11:53:51.000000 wormcat_batch-1.0.4/wormcat_batch.egg-info/SOURCES.txt
+-rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-28 11:53:51.000000 wormcat_batch-1.0.4/wormcat_batch.egg-info/dependency_links.txt
+-rw-r--r--   0 dan        (501) staff       (20)       69 2023-06-28 11:53:51.000000 wormcat_batch-1.0.4/wormcat_batch.egg-info/entry_points.txt
+-rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-28 11:53:51.000000 wormcat_batch-1.0.4/wormcat_batch.egg-info/not-zip-safe
+-rw-r--r--   0 dan        (501) staff       (20)       23 2023-06-28 11:53:51.000000 wormcat_batch-1.0.4/wormcat_batch.egg-info/requires.txt
+-rw-r--r--   0 dan        (501) staff       (20)       14 2023-06-28 11:53:51.000000 wormcat_batch-1.0.4/wormcat_batch.egg-info/top_level.txt
```

### Comparing `wormcat_batch-1.0.3/README.md` & `wormcat_batch-1.0.4/README.md`

 * *Files 7% similar despite different names*

```diff
@@ -70,14 +70,20 @@
 
 #### Test
 cd /Users/dan/delme #some working directory
 wormcat_cli --input-excel /Users/dan/Code/Python/Wormcat_batch/Example/Murphy_TS.xlsx --output-path ./output  
 
 #### Deploy
 conda deactivate # twine is installed in base env
+cd in project directory
+rm -rf ./dist
+rm -rf ./wormcat_batch.egg-info
 python setup.py sdist
 twine check dist/*
 twine upload --repository pypi dist/*
+git add .
+git commit -m "some comment"
+git push
```

### Comparing `wormcat_batch-1.0.3/setup.py` & `wormcat_batch-1.0.4/setup.py`

 * *Files 19% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 from setuptools import setup
 #python setup.py sdist
 #pip install dist/wormcat_batch-1.0.1.tar.gz
 # twine check dist/*
 # twine upload --repository pypi dist/*
 
 setup(name='wormcat_batch',
-      version='1.0.3',
+      version='1.0.4',
       description='Batch processing for Wormcat data',
       url='https://github.com/dphiggs01/Wormcat_batch',
       author='Dan Higgins',
       author_email='daniel.higgins@yahoo.com',
       license='MIT',
 
       packages=['wormcat_batch'],
```

### Comparing `wormcat_batch-1.0.3/wormcat_batch/create_wormcat_xlsx.py` & `wormcat_batch-1.0.4/wormcat_batch/create_wormcat_xlsx.py`

 * *Files identical despite different names*

### Comparing `wormcat_batch-1.0.3/wormcat_batch/execute_r.py` & `wormcat_batch-1.0.4/wormcat_batch/execute_r.py`

 * *Files identical despite different names*

### Comparing `wormcat_batch-1.0.3/wormcat_batch/run_wormcat_batch.py` & `wormcat_batch-1.0.4/wormcat_batch/run_wormcat_batch.py`

 * *Files 1% similar despite different names*

```diff
@@ -49,16 +49,16 @@
     executeR = ExecuteR()
     executeR.worm_cat_fun(file_nm, dir_nm, title, annotation_file, input_type)
 
     # Clean up
     mv_dir = file_nm.replace(".csv", "")
     print(f"{os.getcwd()=} {mv_dir=}")
     os.rename(mv_dir, f"{output_dir}{os.path.sep}{mv_dir}")
-    os.remove(file_nm)
-    os.remove(f"{dir_nm}.zip")
+    #os.remove(file_nm)
+    #os.remove(f"{dir_nm}.zip")
 
 
 # Process the Input spreadsheet
 def process_spreadsheet(xsl_file_nm, output_dir, annotation_file):
     xl = pd.ExcelFile(xsl_file_nm)
     print("Processing Excel sheets")
     for sheet in xl.sheet_names:
```

### Comparing `wormcat_batch-1.0.3/wormcat_batch/worm_cat.R` & `wormcat_batch-1.0.4/wormcat_batch/worm_cat.R`

 * *Files identical despite different names*

