# Comparing `tmp/wormcat_batch-1.0.2.tar.gz` & `tmp/wormcat_batch-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "wormcat_batch-1.0.2.tar", last modified: Tue Jun 27 18:15:48 2023, max compression
+gzip compressed data, was "wormcat_batch-1.0.3.tar", last modified: Wed Jun 28 11:45:23 2023, max compression
```

## Comparing `wormcat_batch-1.0.2.tar` & `wormcat_batch-1.0.3.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-27 18:15:48.825627 wormcat_batch-1.0.2/
--rw-r--r--   0 dan        (501) staff       (20)       95 2022-08-16 12:41:26.000000 wormcat_batch-1.0.2/MANIFEST.in
--rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-27 18:15:48.825518 wormcat_batch-1.0.2/PKG-INFO
--rw-r--r--   0 dan        (501) staff       (20)     2178 2023-06-27 18:10:22.000000 wormcat_batch-1.0.2/README.md
--rw-r--r--   0 dan        (501) staff       (20)       38 2023-06-27 18:15:48.825663 wormcat_batch-1.0.2/setup.cfg
--rw-r--r--   0 dan        (501) staff       (20)      685 2023-06-27 18:14:07.000000 wormcat_batch-1.0.2/setup.py
-drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-27 18:15:48.824625 wormcat_batch-1.0.2/wormcat_batch/
--rw-r--r--   0 dan        (501) staff       (20)     2024 2022-08-16 12:41:26.000000 wormcat_batch-1.0.2/wormcat_batch/create_wormcat_xlsx.py
--rw-r--r--   0 dan        (501) staff       (20)     2486 2023-06-27 18:05:20.000000 wormcat_batch-1.0.2/wormcat_batch/execute_r.py
--rwxr-xr-x   0 dan        (501) staff       (20)       46 2022-08-16 12:41:26.000000 wormcat_batch-1.0.2/wormcat_batch/is_wormcat_installed.R
--rwxr-xr-x   0 dan        (501) staff       (20)     7128 2023-06-27 17:51:03.000000 wormcat_batch-1.0.2/wormcat_batch/run_wormcat_batch.py
--rwxr-xr-x   0 dan        (501) staff       (20)     1446 2022-08-16 12:41:26.000000 wormcat_batch-1.0.2/wormcat_batch/worm_cat.R
-drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-27 18:15:48.825374 wormcat_batch-1.0.2/wormcat_batch.egg-info/
--rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-27 18:15:48.000000 wormcat_batch-1.0.2/wormcat_batch.egg-info/PKG-INFO
--rw-r--r--   0 dan        (501) staff       (20)      451 2023-06-27 18:15:48.000000 wormcat_batch-1.0.2/wormcat_batch.egg-info/SOURCES.txt
--rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-27 18:15:48.000000 wormcat_batch-1.0.2/wormcat_batch.egg-info/dependency_links.txt
--rw-r--r--   0 dan        (501) staff       (20)       69 2023-06-27 18:15:48.000000 wormcat_batch-1.0.2/wormcat_batch.egg-info/entry_points.txt
--rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-27 15:34:55.000000 wormcat_batch-1.0.2/wormcat_batch.egg-info/not-zip-safe
--rw-r--r--   0 dan        (501) staff       (20)       23 2023-06-27 18:15:48.000000 wormcat_batch-1.0.2/wormcat_batch.egg-info/requires.txt
--rw-r--r--   0 dan        (501) staff       (20)       14 2023-06-27 18:15:48.000000 wormcat_batch-1.0.2/wormcat_batch.egg-info/top_level.txt
+drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:45:23.333069 wormcat_batch-1.0.3/
+-rw-r--r--   0 dan        (501) staff       (20)       95 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/MANIFEST.in
+-rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-28 11:45:23.332940 wormcat_batch-1.0.3/PKG-INFO
+-rw-r--r--   0 dan        (501) staff       (20)     2228 2023-06-28 11:43:14.000000 wormcat_batch-1.0.3/README.md
+-rw-r--r--   0 dan        (501) staff       (20)       38 2023-06-28 11:45:23.333104 wormcat_batch-1.0.3/setup.cfg
+-rw-r--r--   0 dan        (501) staff       (20)      685 2023-06-28 11:33:56.000000 wormcat_batch-1.0.3/setup.py
+drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:45:23.331923 wormcat_batch-1.0.3/wormcat_batch/
+-rw-r--r--   0 dan        (501) staff       (20)     2024 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/wormcat_batch/create_wormcat_xlsx.py
+-rw-r--r--   0 dan        (501) staff       (20)     2486 2023-06-27 18:05:20.000000 wormcat_batch-1.0.3/wormcat_batch/execute_r.py
+-rwxr-xr-x   0 dan        (501) staff       (20)       46 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/wormcat_batch/is_wormcat_installed.R
+-rwxr-xr-x   0 dan        (501) staff       (20)     7380 2023-06-28 11:39:52.000000 wormcat_batch-1.0.3/wormcat_batch/run_wormcat_batch.py
+-rwxr-xr-x   0 dan        (501) staff       (20)     1446 2022-08-16 12:41:26.000000 wormcat_batch-1.0.3/wormcat_batch/worm_cat.R
+drwxr-xr-x   0 dan        (501) staff       (20)        0 2023-06-28 11:45:23.332766 wormcat_batch-1.0.3/wormcat_batch.egg-info/
+-rw-r--r--   0 dan        (501) staff       (20)      226 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/PKG-INFO
+-rw-r--r--   0 dan        (501) staff       (20)      451 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/SOURCES.txt
+-rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/dependency_links.txt
+-rw-r--r--   0 dan        (501) staff       (20)       69 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/entry_points.txt
+-rw-r--r--   0 dan        (501) staff       (20)        1 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/not-zip-safe
+-rw-r--r--   0 dan        (501) staff       (20)       23 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/requires.txt
+-rw-r--r--   0 dan        (501) staff       (20)       14 2023-06-28 11:45:23.000000 wormcat_batch-1.0.3/wormcat_batch.egg-info/top_level.txt
```

### Comparing `wormcat_batch-1.0.2/README.md` & `wormcat_batch-1.0.3/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -69,14 +69,15 @@
 pip install .
 
 #### Test
 cd /Users/dan/delme #some working directory
 wormcat_cli --input-excel /Users/dan/Code/Python/Wormcat_batch/Example/Murphy_TS.xlsx --output-path ./output  
 
 #### Deploy
+conda deactivate # twine is installed in base env
 python setup.py sdist
 twine check dist/*
 twine upload --repository pypi dist/*
```

### Comparing `wormcat_batch-1.0.2/setup.py` & `wormcat_batch-1.0.3/setup.py`

 * *Files 20% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 from setuptools import setup
 #python setup.py sdist
 #pip install dist/wormcat_batch-1.0.1.tar.gz
 # twine check dist/*
 # twine upload --repository pypi dist/*
 
 setup(name='wormcat_batch',
-      version='1.0.2',
+      version='1.0.3',
       description='Batch processing for Wormcat data',
       url='https://github.com/dphiggs01/Wormcat_batch',
       author='Dan Higgins',
       author_email='daniel.higgins@yahoo.com',
       license='MIT',
 
       packages=['wormcat_batch'],
```

### Comparing `wormcat_batch-1.0.2/wormcat_batch/create_wormcat_xlsx.py` & `wormcat_batch-1.0.3/wormcat_batch/create_wormcat_xlsx.py`

 * *Files identical despite different names*

### Comparing `wormcat_batch-1.0.2/wormcat_batch/execute_r.py` & `wormcat_batch-1.0.3/wormcat_batch/execute_r.py`

 * *Files identical despite different names*

### Comparing `wormcat_batch-1.0.2/wormcat_batch/run_wormcat_batch.py` & `wormcat_batch-1.0.3/wormcat_batch/run_wormcat_batch.py`

 * *Files 7% similar despite different names*

```diff
@@ -47,15 +47,15 @@
     gene_ids.to_csv(file_nm, index=False)
 
     executeR = ExecuteR()
     executeR.worm_cat_fun(file_nm, dir_nm, title, annotation_file, input_type)
 
     # Clean up
     mv_dir = file_nm.replace(".csv", "")
-    print(f"{mv_dir=}")
+    print(f"{os.getcwd()=} {mv_dir=}")
     os.rename(mv_dir, f"{output_dir}{os.path.sep}{mv_dir}")
     os.remove(file_nm)
     os.remove(f"{dir_nm}.zip")
 
 
 # Process the Input spreadsheet
 def process_spreadsheet(xsl_file_nm, output_dir, annotation_file):
@@ -143,21 +143,14 @@
         return
 
     if not args.output_path:
         print(help_statement)
         print("Output path is missing")
         return
 
-    if args.backup_output_path:
-        create_directory_with_backup(args.output_path)
-    elif is_directory_empty(args.output_path):
-         print(help_statement)
-         print("Output path is not Empty.")
-         return
-
     wormcat_path = get_wormcat_lib()
     annotation_files, path = get_category_files(wormcat_path)
 
     if not args.annotation_file_nm or not args.annotation_file_nm in annotation_files:
         print(help_statement)
         print("Missing or incorrect annotation-file-nm.")
         print("Available names: {}".format(annotation_files))
@@ -165,24 +158,38 @@
  
     # Rest of your program logic goes here
     print("Input Excel:", args.input_excel)
     print("Output Path:", args.output_path)
     print("Backup Path:", args.backup_output_path)
     print("Annotation File Nm:", args.annotation_file_nm)
 
-    process_spreadsheet(args.input_excel, args.output_path, args.annotation_file_nm)
+    # Do all processing in the temp directory
+    work_dir=f"{os.path.sep}tmp{os.path.sep}work"
+    if os.path.exists(work_dir):
+        shutil.rmtree(work_dir)
+    os.makedirs(work_dir)
+    os.chdir(work_dir)
+    print(f"{os.getcwd()=}")
+
+    # Add output to a temp_output director
+    temp_output_path= f".{os.path.sep}temp_output"
+    os.makedirs(temp_output_path, exist_ok=True)
+    print(f"{temp_output_path=}")
+
+    process_spreadsheet(args.input_excel, temp_output_path, args.annotation_file_nm)
     base_input_excel = os.path.basename(args.input_excel)
     input_excel_no_ext = os.path.splitext(base_input_excel)[0]
 
-    out_xsl_file_nm=f"{args.output_path}{os.path.sep}Out_{base_input_excel}"
+    out_xsl_file_nm=f"{temp_output_path}{os.path.sep}Out_{base_input_excel}"
 
     annotation_file =f"{path}{os.path.sep}{args.annotation_file_nm}"
-    df_process = files_to_process(args.output_path)
+    df_process = files_to_process(temp_output_path)
     process_category_files(df_process, annotation_file, out_xsl_file_nm)
-    move_file_to_output_directory(args.input_excel, args.output_path)
+    move_file_to_output_directory(args.input_excel, temp_output_path)
     
     timestamp = datetime.now().strftime("%Y%m%d-%H%M%S")
     zip_dir_nm = f"{input_excel_no_ext}_{timestamp}"
-    output_path = zip_directory(args.output_path, zip_dir_nm)
+    output_zip = zip_directory(temp_output_path, zip_dir_nm)
+    shutil.copy(output_zip, args.output_path)
 
 if __name__ == '__main__':
     main()
```

### Comparing `wormcat_batch-1.0.2/wormcat_batch/worm_cat.R` & `wormcat_batch-1.0.3/wormcat_batch/worm_cat.R`

 * *Files identical despite different names*

