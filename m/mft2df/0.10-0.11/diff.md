# Comparing `tmp/mft2df-0.10.tar.gz` & `tmp/mft2df-0.11.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mft2df-0.10.tar", last modified: Wed Jun 28 06:19:34 2023, max compression
+gzip compressed data, was "mft2df-0.11.tar", last modified: Wed Jun 28 14:57:35 2023, max compression
```

## Comparing `mft2df-0.10.tar` & `mft2df-0.11.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 06:19:34.734369 mft2df-0.10/
--rw-rw-rw-   0        0        0     1148 2023-06-28 06:19:25.000000 mft2df-0.10/LICENSE.rst
--rw-rw-rw-   0        0        0      142 2023-06-28 06:19:25.000000 mft2df-0.10/MANIFEST.in
--rw-rw-rw-   0        0        0     6428 2023-06-28 06:19:34.734369 mft2df-0.10/PKG-INFO
--rw-rw-rw-   0        0        0     5732 2023-06-28 06:18:23.000000 mft2df-0.10/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 06:19:34.731377 mft2df-0.10/mft2df/
--rw-rw-rw-   0        0        0     5732 2023-06-28 06:18:23.000000 mft2df-0.10/mft2df/README.MD
--rw-rw-rw-   0        0        0     4257 2023-06-28 06:08:58.000000 mft2df-0.10/mft2df/__init__.py
--rwxrwxrwx   0        0        0    27136 2023-06-28 04:25:18.000000 mft2df-0.10/mft2df/mft.exe
--rwxrwxrwx   0        0        0  1063424 2023-06-28 04:31:47.000000 mft2df-0.10/mft2df/mft_dump.exe
--rw-rw-rw-   0        0        0       27 2023-06-28 06:19:32.000000 mft2df-0.10/mft2df/requirements.txt
--rw-rw-rw-   0        0        0     3002 2023-06-28 06:19:32.000000 mft2df-0.10/mft2df/thirdparty.json
-drwxrwxrwx   0        0        0        0 2023-06-28 06:19:34.733371 mft2df-0.10/mft2df.egg-info/
--rw-rw-rw-   0        0        0     6428 2023-06-28 06:19:34.000000 mft2df-0.10/mft2df.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      319 2023-06-28 06:19:34.000000 mft2df-0.10/mft2df.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 06:19:34.000000 mft2df-0.10/mft2df.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       27 2023-06-28 06:19:34.000000 mft2df-0.10/mft2df.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 06:19:34.000000 mft2df-0.10/mft2df.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       85 2023-06-28 06:19:34.734369 mft2df-0.10/setup.cfg
--rw-rw-rw-   0        0        0     1397 2023-06-28 06:19:32.000000 mft2df-0.10/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:57:35.533277 mft2df-0.11/
+-rw-rw-rw-   0        0        0     1148 2023-06-28 14:57:29.000000 mft2df-0.11/LICENSE.rst
+-rw-rw-rw-   0        0        0      142 2023-06-28 14:57:28.000000 mft2df-0.11/MANIFEST.in
+-rw-rw-rw-   0        0        0     6975 2023-06-28 14:57:35.533277 mft2df-0.11/PKG-INFO
+-rw-rw-rw-   0        0        0     6279 2023-06-28 14:54:17.000000 mft2df-0.11/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 14:57:35.529289 mft2df-0.11/mft2df/
+-rw-rw-rw-   0        0        0     6279 2023-06-28 14:54:17.000000 mft2df-0.11/mft2df/README.MD
+-rw-rw-rw-   0        0        0     4944 2023-06-28 14:55:33.000000 mft2df-0.11/mft2df/__init__.py
+-rwxrwxrwx   0        0        0    27136 2023-06-28 04:25:18.000000 mft2df-0.11/mft2df/mft.exe
+-rwxrwxrwx   0        0        0  1063424 2023-06-28 04:31:47.000000 mft2df-0.11/mft2df/mft_dump.exe
+-rw-rw-rw-   0        0        0       27 2023-06-28 14:57:34.000000 mft2df-0.11/mft2df/requirements.txt
+-rw-rw-rw-   0        0        0     3002 2023-06-28 14:57:34.000000 mft2df-0.11/mft2df/thirdparty.json
+drwxrwxrwx   0        0        0        0 2023-06-28 14:57:35.532281 mft2df-0.11/mft2df.egg-info/
+-rw-rw-rw-   0        0        0     6975 2023-06-28 14:57:35.000000 mft2df-0.11/mft2df.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      319 2023-06-28 14:57:35.000000 mft2df-0.11/mft2df.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:57:35.000000 mft2df-0.11/mft2df.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       27 2023-06-28 14:57:35.000000 mft2df-0.11/mft2df.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 14:57:35.000000 mft2df-0.11/mft2df.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       85 2023-06-28 14:57:35.533277 mft2df-0.11/setup.cfg
+-rw-rw-rw-   0        0        0     1397 2023-06-28 14:57:34.000000 mft2df-0.11/setup.py
```

### Comparing `mft2df-0.10/LICENSE.rst` & `mft2df-0.11/LICENSE.rst`

 * *Files identical despite different names*

### Comparing `mft2df-0.10/PKG-INFO` & `mft2df-0.11/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,25 +1,7 @@
-Metadata-Version: 2.1
-Name: mft2df
-Version: 0.10
-Summary: Lists the files on a drive insanely fast (43 seconds for 1,800,000 files - 600 GB) by converting the $MFT to a pandas DataFrame
-Home-page: https://github.com/hansalemaos/mft2df
-Author: Johannes Fischer
-Author-email: aulasparticularesdealemaosp@gmail.com
-License: MIT
-Keywords: mft,windows,pandas
-Classifier: Development Status :: 4 - Beta
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Topic :: Software Development :: Libraries :: Python Modules
-Classifier: Topic :: Utilities
-Description-Content-Type: text/markdown
-License-File: LICENSE.rst
-
-
 # Lists the files on a drive insanely fast (43 seconds for 1,800,000 files - 600 GB) by converting the $MFT to a pandas DataFrame 
 
 ## pip install mft2df
 
 ### Tested against Windows 10 / Python 3.10 / Anaconda 
 
 
@@ -37,15 +19,24 @@
 - Filters out rows with missing FullPath values to ensure the integrity of the data.
 - Prepends the drive letter to the FullPath column to create a complete file path.
 - Cleans up the temporary MFT dump file after processing.
 - Utilizes efficient memory management by explicitly deleting variables, garbage collection, and low-memory options in the pandas read_csv function.
 
 
 ```python
-
+Args:
+    drive (str): The drive letter to retrieve the files from. Default is "c".
+    convert_dates (bool): Whether to use pd.to_datetime to convert "FileNameLastModified", "FileNameLastAccess",
+                           "FileNameCreated","StandardInfoLastModified","StandardInfoLastAccess","StandardInfoCreated"
+                          (Parsing takes about 2x longer, and the resulting DataFrame is about 30% bigger)
+Returns:
+    pd.DataFrame: A DataFrame containing the list of files retrieved from the drive.
+Raises:
+    None
+    
 # Important: you need admin rights!!!!
 from mft2df import list_files_from_drive
 from time import perf_counter
 start = perf_counter()
 df=list_files_from_drive(drive= "c")
 print(f'Time needed: {perf_counter() - start} for {len(df)} files')
 print(df[200060:200066].to_string())
@@ -56,8 +47,8 @@
 # 200060      FILE   202514         1            0                  0              2  ALLOCATED            672            1024       211         False      False                    False           (empty)  2020-03-04T10:38:59.012552Z  2020-03-04T10:38:59.012552Z  2020-03-04T10:39:00.779040Z  FILE_ATTRIBUTE_ARCHIVE  2020-03-04T10:38:59.012552Z  2020-03-04T10:38:59.012552Z  2020-03-04T10:38:59.012552Z  c:\Windows\WinSxS\Manifests\amd64_bthmtpenum.inf-languagepack_31bf3856ad364e35_10.0.18362.1_de-de_710d1caf8aa9bb19.manifest
 # 200061      FILE   202515         1            0                  0              2  ALLOCATED            664            1024       208         False      False                    False           (empty)  2020-03-04T10:38:59.022586Z  2020-03-04T10:38:59.022586Z  2020-03-04T10:39:00.779040Z  FILE_ATTRIBUTE_ARCHIVE  2020-03-04T10:38:59.022586Z  2020-03-04T10:38:59.022586Z  2020-03-04T10:38:59.022586Z       c:\Windows\WinSxS\Manifests\amd64_c_wpd.inf-languagepack_31bf3856ad364e35_10.0.18362.1_de-de_a4c4bcf7ec41f07e.manifest
 # 200062      FILE   202516         1            0                  0              2  ALLOCATED            672            1024       207         False      False                    False           (empty)  2020-03-04T10:38:59.032170Z  2020-03-04T10:38:59.032170Z  2020-03-04T10:39:00.779040Z  FILE_ATTRIBUTE_ARCHIVE  2020-03-04T10:38:59.032170Z  2020-03-04T10:38:59.032170Z  2020-03-04T10:38:59.022586Z     c:\Windows\WinSxS\Manifests\amd64_wpdcomp.inf-languagepack_31bf3856ad364e35_10.0.18362.1_de-de_78d37c0df7225559.manifest
 # 200063      FILE   202517         1            0                  0              2  ALLOCATED            664            1024       207         False      False                    False           (empty)  2020-03-04T10:38:59.032699Z  2020-03-04T10:38:59.032699Z  2020-03-04T10:39:00.794664Z  FILE_ATTRIBUTE_ARCHIVE  2020-03-04T10:38:59.032699Z  2020-03-04T10:38:59.032699Z  2020-03-04T10:38:59.032699Z       c:\Windows\WinSxS\Manifests\amd64_wpdfs.inf-languagepack_31bf3856ad364e35_10.0.18362.1_de-de_a09f098927b0c6b9.manifest
 # 200064      FILE   202518         1            0                  0              2  ALLOCATED            664            1024       208         False      False                    False           (empty)  2020-03-04T10:38:59.042535Z  2020-03-04T10:38:59.042535Z  2020-03-04T10:39:00.794664Z  FILE_ATTRIBUTE_ARCHIVE  2020-03-04T10:38:59.042535Z  2020-03-04T10:38:59.042535Z  2020-03-04T10:38:59.032699Z      c:\Windows\WinSxS\Manifests\amd64_wpdmtp.inf-languagepack_31bf3856ad364e35_10.0.18362.1_de-de_13d74fb245acf719.manifest
 # 200065      FILE   202519         1            0                  0              2  ALLOCATED            672            1024       211         False      False                    False           (empty)  2020-03-04T10:38:59.042535Z  2020-03-04T10:38:59.042535Z  2020-03-04T10:39:00.794664Z  FILE_ATTRIBUTE_ARCHIVE  2020-03-04T10:38:59.042535Z  2020-03-04T10:38:59.042535Z  2020-03-04T10:38:59.042535Z    c:\Windows\WinSxS\Manifests\amd64_wpdmtphw.inf-languagepack_31bf3856ad364e35_10.0.18362.1_de-de_52e461d8f91111b2.manifest
 
-```
+```
```

### Comparing `mft2df-0.10/README.md` & `mft2df-0.11/mft2df/README.MD`

 * *Files 18% similar despite different names*

```diff
@@ -19,15 +19,24 @@
 - Filters out rows with missing FullPath values to ensure the integrity of the data.
 - Prepends the drive letter to the FullPath column to create a complete file path.
 - Cleans up the temporary MFT dump file after processing.
 - Utilizes efficient memory management by explicitly deleting variables, garbage collection, and low-memory options in the pandas read_csv function.
 
 
 ```python
-
+Args:
+    drive (str): The drive letter to retrieve the files from. Default is "c".
+    convert_dates (bool): Whether to use pd.to_datetime to convert "FileNameLastModified", "FileNameLastAccess",
+                           "FileNameCreated","StandardInfoLastModified","StandardInfoLastAccess","StandardInfoCreated"
+                          (Parsing takes about 2x longer, and the resulting DataFrame is about 30% bigger)
+Returns:
+    pd.DataFrame: A DataFrame containing the list of files retrieved from the drive.
+Raises:
+    None
+    
 # Important: you need admin rights!!!!
 from mft2df import list_files_from_drive
 from time import perf_counter
 start = perf_counter()
 df=list_files_from_drive(drive= "c")
 print(f'Time needed: {perf_counter() - start} for {len(df)} files')
 print(df[200060:200066].to_string())
```

### Comparing `mft2df-0.10/mft2df/__init__.py` & `mft2df-0.11/mft2df/__init__.py`

 * *Files 13% similar despite different names*

```diff
@@ -33,27 +33,30 @@
     """
     tfp = tempfile.NamedTemporaryFile(delete=True, suffix=suffix)
     filename = os.path.normpath(tfp.name)
     tfp.close()
     return filename
 
 
-def list_files_from_drive(drive: str = "c") -> pd.DataFrame:
+def list_files_from_drive(drive: str = "c", convert_dates: bool = True) -> pd.DataFrame:
     """
-        Retrieves a list of files from a specified drive and returns the results as a pandas DataFrame.
+    Retrieves a list of files from a specified drive and returns the results as a pandas DataFrame.
 
-        Args:
-            drive (str): The drive letter to retrieve the files from. Default is "c".
+    Args:
+        drive (str): The drive letter to retrieve the files from. Default is "c".
+        convert_dates (bool): Whether to use pd.to_datetime to convert "FileNameLastModified", "FileNameLastAccess",
+                               "FileNameCreated","StandardInfoLastModified","StandardInfoLastAccess","StandardInfoCreated"
+                              (Parsing takes about 2x longer, and the resulting DataFrame is about 30% bigger)
 
-        Returns:
-            pd.DataFrame: A DataFrame containing the list of files retrieved from the drive.
+    Returns:
+        pd.DataFrame: A DataFrame containing the list of files retrieved from the drive.
 
-        Raises:
-            None
-        """
+    Raises:
+        None
+    """
     drive_re = re.findall(r"[a-z]+", drive, flags=re.I)[0].lower()
     mfttmpfile = get_tmpfile(".file")
     dumpcommand = [createdump, "dump", drive_re, f"{mfttmpfile}"]
     parsecommand = [parasedump, "-o", "csv", mfttmpfile]
     _ = subprocess.run(dumpcommand, capture_output=True, **invisibledict)
     opu = subprocess.run(parsecommand, capture_output=True, **invisibledict)
     tmpstring = io.StringIO(opu.stdout.decode("utf-8"))
@@ -88,16 +91,14 @@
             "StandardInfoCreated",
             "FileNameFlags",
             "FileNameLastModified",
             "FileNameLastAccess",
             "FileNameCreated",
             "FullPath",
         ],
-        parse_dates=["FileNameLastModified", "FileNameLastAccess", "FileNameCreated"],
-        date_format="%Y-%m-%dT%H:%M:%S.%fZ",
         dtype={
             "Signature": "category",
             "EntryId": "uint32",
             "Sequence": "uint16",
             "BaseEntryId": "uint32",
             "BaseEntrySequence": "uint16",
             "HardLinkCount": "uint16",
@@ -109,29 +110,41 @@
             "IsDeleted": "bool",
             "HasAlternateDataStreams": "bool",
             "StandardInfoFlags": "category",
             "StandardInfoLastModified": "string",
             "StandardInfoLastAccess": "string",
             "StandardInfoCreated": "string",
             "FileNameFlags": "category",
-            # "FileNameLastModified":"string",
-            # "FileNameLastAccess":"string",
-            # "FileNameCreated":"string",
+            "FileNameLastModified": "string",
+            "FileNameLastAccess": "string",
+            "FileNameCreated": "string",
             "FullPath": "string",
         },
         engine="c",
-        cache_dates=True,
         low_memory=True,
     )
+
     df = df.dropna(subset="FullPath")
     gc.collect()
     df.loc[df.index, "FullPath"] = f"{drive_re}:\\" + df.FullPath
     df = df.reset_index(drop=True)
     gc.collect()
-
+    if convert_dates:
+        dateformat = "%Y-%m-%dT%H:%M:%S.%fZ"
+        datecols = [
+            "FileNameLastModified",
+            "FileNameLastAccess",
+            "FileNameCreated",
+            "StandardInfoLastModified",
+            "StandardInfoLastAccess",
+            "StandardInfoCreated",
+        ]
+        for datecol in datecols:
+            df[datecol] = pd.to_datetime(
+                df[datecol], errors="coerce", format=dateformat
+            )
+            gc.collect()
     try:
         os.remove(mfttmpfile)
     except Exception as fe:
         print(fe)
     return df
-
-
```

### Comparing `mft2df-0.10/mft2df/mft.exe` & `mft2df-0.11/mft2df/mft.exe`

 * *Files identical despite different names*

### Comparing `mft2df-0.10/mft2df/mft_dump.exe` & `mft2df-0.11/mft2df/mft_dump.exe`

 * *Files identical despite different names*

### Comparing `mft2df-0.10/mft2df/thirdparty.json` & `mft2df-0.11/mft2df/thirdparty.json`

 * *Files identical despite different names*

### Comparing `mft2df-0.10/mft2df.egg-info/PKG-INFO` & `mft2df-0.11/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mft2df
-Version: 0.10
+Version: 0.11
 Summary: Lists the files on a drive insanely fast (43 seconds for 1,800,000 files - 600 GB) by converting the $MFT to a pandas DataFrame
 Home-page: https://github.com/hansalemaos/mft2df
 Author: Johannes Fischer
 Author-email: aulasparticularesdealemaosp@gmail.com
 License: MIT
 Keywords: mft,windows,pandas
 Classifier: Development Status :: 4 - Beta
@@ -37,15 +37,24 @@
 - Filters out rows with missing FullPath values to ensure the integrity of the data.
 - Prepends the drive letter to the FullPath column to create a complete file path.
 - Cleans up the temporary MFT dump file after processing.
 - Utilizes efficient memory management by explicitly deleting variables, garbage collection, and low-memory options in the pandas read_csv function.
 
 
 ```python
-
+Args:
+    drive (str): The drive letter to retrieve the files from. Default is "c".
+    convert_dates (bool): Whether to use pd.to_datetime to convert "FileNameLastModified", "FileNameLastAccess",
+                           "FileNameCreated","StandardInfoLastModified","StandardInfoLastAccess","StandardInfoCreated"
+                          (Parsing takes about 2x longer, and the resulting DataFrame is about 30% bigger)
+Returns:
+    pd.DataFrame: A DataFrame containing the list of files retrieved from the drive.
+Raises:
+    None
+    
 # Important: you need admin rights!!!!
 from mft2df import list_files_from_drive
 from time import perf_counter
 start = perf_counter()
 df=list_files_from_drive(drive= "c")
 print(f'Time needed: {perf_counter() - start} for {len(df)} files')
 print(df[200060:200066].to_string())
```

### Comparing `mft2df-0.10/setup.py` & `mft2df-0.11/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 with open(os.path.join(os.path.abspath(os.path.dirname(__file__)),'README.md'), encoding="utf-8") as fh:
     long_description = "\n" + fh.read()\
 
 from pathlib import Path
 this_directory = Path(__file__).parent
 #long_description = (this_directory / "README.md").read_text()
 
-VERSION = '''0.10'''
+VERSION = '''0.11'''
 DESCRIPTION = '''Lists the files on a drive insanely fast (43 seconds for 1,800,000 files - 600 GB) by converting the $MFT to a pandas DataFrame'''
 
 # Setting up
 setup(
     name="mft2df",
     version=VERSION,
     license='MIT',
```

