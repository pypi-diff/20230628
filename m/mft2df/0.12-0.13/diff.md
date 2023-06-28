# Comparing `tmp/mft2df-0.12.tar.gz` & `tmp/mft2df-0.13.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mft2df-0.12.tar", last modified: Wed Jun 28 15:28:14 2023, max compression
+gzip compressed data, was "mft2df-0.13.tar", last modified: Wed Jun 28 15:31:04 2023, max compression
```

## Comparing `mft2df-0.12.tar` & `mft2df-0.13.tar`

### file list

```diff
@@ -1,20 +1,20 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 15:28:14.345759 mft2df-0.12/
--rw-rw-rw-   0        0        0     1148 2023-06-28 15:28:07.000000 mft2df-0.12/LICENSE.rst
--rw-rw-rw-   0        0        0      142 2023-06-28 15:28:06.000000 mft2df-0.12/MANIFEST.in
--rw-rw-rw-   0        0        0     7913 2023-06-28 15:28:14.345759 mft2df-0.12/PKG-INFO
--rw-rw-rw-   0        0        0     7217 2023-06-28 15:26:23.000000 mft2df-0.12/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 15:28:14.342767 mft2df-0.12/mft2df/
--rw-rw-rw-   0        0        0     7217 2023-06-28 15:26:23.000000 mft2df-0.12/mft2df/README.MD
--rw-rw-rw-   0        0        0     4944 2023-06-28 15:01:02.000000 mft2df-0.12/mft2df/__init__.py
--rwxrwxrwx   0        0        0    27136 2023-06-28 04:25:18.000000 mft2df-0.12/mft2df/mft.exe
--rwxrwxrwx   0        0        0  1063424 2023-06-28 04:31:47.000000 mft2df-0.12/mft2df/mft_dump.exe
--rw-rw-rw-   0        0        0       27 2023-06-28 15:28:13.000000 mft2df-0.12/mft2df/requirements.txt
--rw-rw-rw-   0        0        0     3002 2023-06-28 15:28:13.000000 mft2df-0.12/mft2df/thirdparty.json
-drwxrwxrwx   0        0        0        0 2023-06-28 15:28:14.344761 mft2df-0.12/mft2df.egg-info/
--rw-rw-rw-   0        0        0     7913 2023-06-28 15:28:14.000000 mft2df-0.12/mft2df.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      319 2023-06-28 15:28:14.000000 mft2df-0.12/mft2df.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 15:28:14.000000 mft2df-0.12/mft2df.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       27 2023-06-28 15:28:14.000000 mft2df-0.12/mft2df.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-28 15:28:14.000000 mft2df-0.12/mft2df.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       85 2023-06-28 15:28:14.347755 mft2df-0.12/setup.cfg
--rw-rw-rw-   0        0        0     1397 2023-06-28 15:28:13.000000 mft2df-0.12/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:31:04.719288 mft2df-0.13/
+-rw-rw-rw-   0        0        0     1148 2023-06-28 15:30:57.000000 mft2df-0.13/LICENSE.rst
+-rw-rw-rw-   0        0        0      142 2023-06-28 15:30:56.000000 mft2df-0.13/MANIFEST.in
+-rw-rw-rw-   0        0        0     7917 2023-06-28 15:31:04.719288 mft2df-0.13/PKG-INFO
+-rw-rw-rw-   0        0        0     7221 2023-06-28 15:30:22.000000 mft2df-0.13/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 15:31:04.712306 mft2df-0.13/mft2df/
+-rw-rw-rw-   0        0        0     7221 2023-06-28 15:30:22.000000 mft2df-0.13/mft2df/README.MD
+-rw-rw-rw-   0        0        0     4944 2023-06-28 15:01:02.000000 mft2df-0.13/mft2df/__init__.py
+-rwxrwxrwx   0        0        0    27136 2023-06-28 04:25:18.000000 mft2df-0.13/mft2df/mft.exe
+-rwxrwxrwx   0        0        0  1063424 2023-06-28 04:31:47.000000 mft2df-0.13/mft2df/mft_dump.exe
+-rw-rw-rw-   0        0        0       27 2023-06-28 15:31:03.000000 mft2df-0.13/mft2df/requirements.txt
+-rw-rw-rw-   0        0        0     3002 2023-06-28 15:31:03.000000 mft2df-0.13/mft2df/thirdparty.json
+drwxrwxrwx   0        0        0        0 2023-06-28 15:31:04.718290 mft2df-0.13/mft2df.egg-info/
+-rw-rw-rw-   0        0        0     7917 2023-06-28 15:31:04.000000 mft2df-0.13/mft2df.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      319 2023-06-28 15:31:04.000000 mft2df-0.13/mft2df.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 15:31:04.000000 mft2df-0.13/mft2df.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       27 2023-06-28 15:31:04.000000 mft2df-0.13/mft2df.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 15:31:04.000000 mft2df-0.13/mft2df.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       85 2023-06-28 15:31:04.720286 mft2df-0.13/setup.cfg
+-rw-rw-rw-   0        0        0     1397 2023-06-28 15:31:03.000000 mft2df-0.13/setup.py
```

### Comparing `mft2df-0.12/LICENSE.rst` & `mft2df-0.13/LICENSE.rst`

 * *Files identical despite different names*

### Comparing `mft2df-0.12/PKG-INFO` & `mft2df-0.13/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mft2df
-Version: 0.12
+Version: 0.13
 Summary: Lists the files on a drive insanely fast (43 seconds for 1,800,000 files - 600 GB) by converting the $MFT to a pandas DataFrame
 Home-page: https://github.com/hansalemaos/mft2df
 Author: Johannes Fischer
 Author-email: aulasparticularesdealemaosp@gmail.com
 License: MIT
 Keywords: mft,windows,pandas
 Classifier: Development Status :: 4 - Beta
@@ -71,36 +71,36 @@
 
 ```
 
 ## Examples
 
 ### Finds all python files on your HDD that contain the string "ctypes" in less than 2 minutes
 
-```
+```python
 import pandas as pd
 from PrettyColorPrinter import add_printer # pip install PrettyColorPrinter
 add_printer(1)
 from mft2df import list_files_from_drive
 from time import perf_counter
 
 start = perf_counter()
 df = list_files_from_drive(drive="c", convert_dates=False)
 print(f"Time needed: {perf_counter() - start} " f"for {len(df)} files")
 
 
-def regex_search(file):
+def get_content(file):
     try:
         with open(file, mode="r", encoding="utf-8") as f:
             data = f.read()
 
     except Exception:
         data = pd.NA
     return data
 
 
 dffi = df.loc[
     (df.FullPath.str.endswith(".py")) & (~df.IsDeleted) & (~df.IsADirectory)
 ].copy()
-dffi["FileContent"] = dffi.FullPath.apply(regex_search)
+dffi["FileContent"] = dffi.FullPath.apply(get_content)
 dffi = dffi.loc[~dffi["FileContent"].isna()]
 ctypesfiles = dffi.loc[dffi.FileContent.str.contains("ctypes")]
 ```
```

### Comparing `mft2df-0.12/README.md` & `mft2df-0.13/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -53,36 +53,36 @@
 
 ```
 
 ## Examples
 
 ### Finds all python files on your HDD that contain the string "ctypes" in less than 2 minutes
 
-```
+```python
 import pandas as pd
 from PrettyColorPrinter import add_printer # pip install PrettyColorPrinter
 add_printer(1)
 from mft2df import list_files_from_drive
 from time import perf_counter
 
 start = perf_counter()
 df = list_files_from_drive(drive="c", convert_dates=False)
 print(f"Time needed: {perf_counter() - start} " f"for {len(df)} files")
 
 
-def regex_search(file):
+def get_content(file):
     try:
         with open(file, mode="r", encoding="utf-8") as f:
             data = f.read()
 
     except Exception:
         data = pd.NA
     return data
 
 
 dffi = df.loc[
     (df.FullPath.str.endswith(".py")) & (~df.IsDeleted) & (~df.IsADirectory)
 ].copy()
-dffi["FileContent"] = dffi.FullPath.apply(regex_search)
+dffi["FileContent"] = dffi.FullPath.apply(get_content)
 dffi = dffi.loc[~dffi["FileContent"].isna()]
 ctypesfiles = dffi.loc[dffi.FileContent.str.contains("ctypes")]
 ```
```

### Comparing `mft2df-0.12/mft2df/README.MD` & `mft2df-0.13/mft2df/README.MD`

 * *Files 3% similar despite different names*

```diff
@@ -53,36 +53,36 @@
 
 ```
 
 ## Examples
 
 ### Finds all python files on your HDD that contain the string "ctypes" in less than 2 minutes
 
-```
+```python
 import pandas as pd
 from PrettyColorPrinter import add_printer # pip install PrettyColorPrinter
 add_printer(1)
 from mft2df import list_files_from_drive
 from time import perf_counter
 
 start = perf_counter()
 df = list_files_from_drive(drive="c", convert_dates=False)
 print(f"Time needed: {perf_counter() - start} " f"for {len(df)} files")
 
 
-def regex_search(file):
+def get_content(file):
     try:
         with open(file, mode="r", encoding="utf-8") as f:
             data = f.read()
 
     except Exception:
         data = pd.NA
     return data
 
 
 dffi = df.loc[
     (df.FullPath.str.endswith(".py")) & (~df.IsDeleted) & (~df.IsADirectory)
 ].copy()
-dffi["FileContent"] = dffi.FullPath.apply(regex_search)
+dffi["FileContent"] = dffi.FullPath.apply(get_content)
 dffi = dffi.loc[~dffi["FileContent"].isna()]
 ctypesfiles = dffi.loc[dffi.FileContent.str.contains("ctypes")]
 ```
```

### Comparing `mft2df-0.12/mft2df/__init__.py` & `mft2df-0.13/mft2df/__init__.py`

 * *Files identical despite different names*

### Comparing `mft2df-0.12/mft2df/mft.exe` & `mft2df-0.13/mft2df/mft.exe`

 * *Files identical despite different names*

### Comparing `mft2df-0.12/mft2df/mft_dump.exe` & `mft2df-0.13/mft2df/mft_dump.exe`

 * *Files identical despite different names*

### Comparing `mft2df-0.12/mft2df/thirdparty.json` & `mft2df-0.13/mft2df/thirdparty.json`

 * *Files identical despite different names*

### Comparing `mft2df-0.12/mft2df.egg-info/PKG-INFO` & `mft2df-0.13/mft2df.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mft2df
-Version: 0.12
+Version: 0.13
 Summary: Lists the files on a drive insanely fast (43 seconds for 1,800,000 files - 600 GB) by converting the $MFT to a pandas DataFrame
 Home-page: https://github.com/hansalemaos/mft2df
 Author: Johannes Fischer
 Author-email: aulasparticularesdealemaosp@gmail.com
 License: MIT
 Keywords: mft,windows,pandas
 Classifier: Development Status :: 4 - Beta
@@ -71,36 +71,36 @@
 
 ```
 
 ## Examples
 
 ### Finds all python files on your HDD that contain the string "ctypes" in less than 2 minutes
 
-```
+```python
 import pandas as pd
 from PrettyColorPrinter import add_printer # pip install PrettyColorPrinter
 add_printer(1)
 from mft2df import list_files_from_drive
 from time import perf_counter
 
 start = perf_counter()
 df = list_files_from_drive(drive="c", convert_dates=False)
 print(f"Time needed: {perf_counter() - start} " f"for {len(df)} files")
 
 
-def regex_search(file):
+def get_content(file):
     try:
         with open(file, mode="r", encoding="utf-8") as f:
             data = f.read()
 
     except Exception:
         data = pd.NA
     return data
 
 
 dffi = df.loc[
     (df.FullPath.str.endswith(".py")) & (~df.IsDeleted) & (~df.IsADirectory)
 ].copy()
-dffi["FileContent"] = dffi.FullPath.apply(regex_search)
+dffi["FileContent"] = dffi.FullPath.apply(get_content)
 dffi = dffi.loc[~dffi["FileContent"].isna()]
 ctypesfiles = dffi.loc[dffi.FileContent.str.contains("ctypes")]
 ```
```

### Comparing `mft2df-0.12/setup.py` & `mft2df-0.13/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 with open(os.path.join(os.path.abspath(os.path.dirname(__file__)),'README.md'), encoding="utf-8") as fh:
     long_description = "\n" + fh.read()\
 
 from pathlib import Path
 this_directory = Path(__file__).parent
 #long_description = (this_directory / "README.md").read_text()
 
-VERSION = '''0.12'''
+VERSION = '''0.13'''
 DESCRIPTION = '''Lists the files on a drive insanely fast (43 seconds for 1,800,000 files - 600 GB) by converting the $MFT to a pandas DataFrame'''
 
 # Setting up
 setup(
     name="mft2df",
     version=VERSION,
     license='MIT',
```

