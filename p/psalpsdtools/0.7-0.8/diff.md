# Comparing `tmp/psalpsdtools-0.7.tar.gz` & `tmp/psalpsdtools-0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "psalpsdtools-0.7.tar", last modified: Tue Jun 27 23:38:57 2023, max compression
+gzip compressed data, was "psalpsdtools-0.8.tar", last modified: Wed Jun 28 00:51:24 2023, max compression
```

## Comparing `psalpsdtools-0.7.tar` & `psalpsdtools-0.8.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 23:38:57.921017 psalpsdtools-0.7/
--rw-rw-rw-   0        0        0     1802 2023-06-27 23:38:57.921017 psalpsdtools-0.7/PKG-INFO
--rw-rw-rw-   0        0        0     1175 2023-06-27 23:21:24.000000 psalpsdtools-0.7/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 23:38:57.914019 psalpsdtools-0.7/psalpsdtools/
--rw-rw-rw-   0        0        0     7501 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/Edrw.py
--rw-rw-rw-   0        0        0     3556 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/PhRegPrv.py
--rw-rw-rw-   0        0        0       54 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/__init__.py
--rw-rw-rw-   0        0        0      430 2023-06-27 23:11:29.000000 psalpsdtools-0.7/psalpsdtools/usage.py
-drwxrwxrwx   0        0        0        0 2023-06-27 23:38:57.919011 psalpsdtools-0.7/psalpsdtools.egg-info/
--rw-rw-rw-   0        0        0     1802 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      300 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        2 2023-06-27 23:30:13.000000 psalpsdtools-0.7/psalpsdtools.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0       13 2023-06-27 23:38:57.000000 psalpsdtools-0.7/psalpsdtools.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 23:38:57.921017 psalpsdtools-0.7/setup.cfg
--rw-rw-rw-   0        0        0      423 2023-06-27 23:38:55.000000 psalpsdtools-0.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 00:51:24.632434 psalpsdtools-0.8/
+-rw-rw-rw-   0        0        0     2624 2023-06-28 00:51:24.632434 psalpsdtools-0.8/PKG-INFO
+-rw-rw-rw-   0        0        0     1773 2023-06-28 00:50:45.000000 psalpsdtools-0.8/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 00:51:24.625414 psalpsdtools-0.8/psalpsdtools/
+-rw-rw-rw-   0        0        0     7501 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/Edrw.py
+-rw-rw-rw-   0        0        0     3556 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/PhRegPrv.py
+-rw-rw-rw-   0        0        0       54 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/__init__.py
+-rw-rw-rw-   0        0        0      430 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/usage.py
+drwxrwxrwx   0        0        0        0 2023-06-28 00:51:24.632434 psalpsdtools-0.8/psalpsdtools.egg-info/
+-rw-rw-rw-   0        0        0     2624 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      300 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        2 2023-06-27 23:30:13.000000 psalpsdtools-0.8/psalpsdtools.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0       13 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 00:51:24.632434 psalpsdtools-0.8/setup.cfg
+-rw-rw-rw-   0        0        0      423 2023-06-28 00:51:00.000000 psalpsdtools-0.8/setup.py
```

### Comparing `psalpsdtools-0.7/PKG-INFO` & `psalpsdtools-0.8/PKG-INFO`

 * *Files 21% similar despite different names*

```diff
@@ -1,56 +1,84 @@
 Metadata-Version: 2.1
 Name: psalpsdtools
-Version: 0.7
+Version: 0.8
 Summary: PSA-LPSD Tools
 Home-page: https://github.com/tondiaz/psalpsdtools
 Author-email: a.diaziii@psa.gov.ph
 License: MIT
-Description: psalpsdtools
-        psalpsdtools is developed for the processing of PSA’s Livestock and Poultry Statistics Division.
+Description: # psalpsdtools
+        ![LPSD Logo](LPSD%20Logo.png =100x100)
         
-        Features
-        Looking-up of values from the Supply-Disposition file and copying to the EDRW file.
+        _psalpsdtools_ was developed for the processing of PSA’s Livestock and Poultry Statistics Division.
         
-        Creating output files based on user specified:
-        region
+        # Features
         
-        commodity
+        Some of the features include:
         
-        year
+        ####  Electronic Data Review Worksheet (EDRW)
+        - Looking-up and copying of values from the Supply-Disposition file
+        - Pasting copied values to the EDRW output file
+        - Creating output files by province, based on user specified inputs including:
+        	- region
+        	- commodity
+        	- year
         
-        Installation
-        Install psalpsdtools by running:
+        # Requirements
         
-        pip install psalpsdtools
+        Python 3.8 or later with all [requirements.txt](https://github.com/tondiaz/psalpsdtools/blob/main/docs/requirements.txt) dependencies installed. To install run:
         
-        Usage
+        ```bash
+        pip install psalpsdtools
+        ```
+        # Usage
+        ```bash
         from psalpsdtools import Edrw
         
-        # SET REGION TO PROCESS
+        # Specify Region
+        
         regName = “Caraga”
-        # SET QUARTER, ALSO USED IN READING THE S-D FILE
+        
+        # Specify quarter, this used in identifying which worksheet to paste the copied values from the S-D file..
+        
         qtr = “Q1”
-        # SET FOLDER OF SOURCES/FINAL FILES INCLUDING S-D FILE
+        
+        # Specify folder location of Sources and Final files, the S-D file should also be found here.
+        
         baseFolder = “D:/EDRW/Q1”
-        # SET S-D FILE NAME
+        
+        # Specify S-D filename
+        # IMPORTANT! Only .xlsm or .xlsx extensions are accepted
+        
         sdFile = ‘SD Q1 2023.xlsm’
-        # COMMODITY 08=chicken, 09=duck, etc.
+        
+        # Commodity code i.e. 08=chicken, 09=duck, etc.
+        
         commcode = ‘08’
+        
         # Year
+        
         yr = ‘23’
-        # CALL AN INSTANCE OF Edrw
+        
+        # Call an instance of the Edrw package
+        
         myedrw = Edrw()
-        # RUN THE UPDATING
+        
+        # Run update_sources with the parameters
+        
         myedrw.update_sources(regName,qtr,baseFolder,sdFile,commcode,yr)
-        Contribute
+        ```
+        
+        # Contribute
+        
         Issue Tracker: github.com/psalpsdtools/psalpsdtools/issues
         
         Source Code: github.com/psalpsdtools/psalpsdtools
         
-        Support
+        # Support
+        
         If you are having issues, please let us know. We have a mailing list located at: a.diaziii@psa.gov.ph
         
-        License
-        The project is licensed under the BSD license.
+        # License
+        
+        The project is licensed under the MIT license.
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
```

### Comparing `psalpsdtools-0.7/psalpsdtools/Edrw.py` & `psalpsdtools-0.8/psalpsdtools/Edrw.py`

 * *Files identical despite different names*

### Comparing `psalpsdtools-0.7/psalpsdtools/PhRegPrv.py` & `psalpsdtools-0.8/psalpsdtools/PhRegPrv.py`

 * *Files identical despite different names*

### Comparing `psalpsdtools-0.7/psalpsdtools.egg-info/PKG-INFO` & `psalpsdtools-0.8/psalpsdtools.egg-info/PKG-INFO`

 * *Files 21% similar despite different names*

```diff
@@ -1,56 +1,84 @@
 Metadata-Version: 2.1
 Name: psalpsdtools
-Version: 0.7
+Version: 0.8
 Summary: PSA-LPSD Tools
 Home-page: https://github.com/tondiaz/psalpsdtools
 Author-email: a.diaziii@psa.gov.ph
 License: MIT
-Description: psalpsdtools
-        psalpsdtools is developed for the processing of PSA’s Livestock and Poultry Statistics Division.
+Description: # psalpsdtools
+        ![LPSD Logo](LPSD%20Logo.png =100x100)
         
-        Features
-        Looking-up of values from the Supply-Disposition file and copying to the EDRW file.
+        _psalpsdtools_ was developed for the processing of PSA’s Livestock and Poultry Statistics Division.
         
-        Creating output files based on user specified:
-        region
+        # Features
         
-        commodity
+        Some of the features include:
         
-        year
+        ####  Electronic Data Review Worksheet (EDRW)
+        - Looking-up and copying of values from the Supply-Disposition file
+        - Pasting copied values to the EDRW output file
+        - Creating output files by province, based on user specified inputs including:
+        	- region
+        	- commodity
+        	- year
         
-        Installation
-        Install psalpsdtools by running:
+        # Requirements
         
-        pip install psalpsdtools
+        Python 3.8 or later with all [requirements.txt](https://github.com/tondiaz/psalpsdtools/blob/main/docs/requirements.txt) dependencies installed. To install run:
         
-        Usage
+        ```bash
+        pip install psalpsdtools
+        ```
+        # Usage
+        ```bash
         from psalpsdtools import Edrw
         
-        # SET REGION TO PROCESS
+        # Specify Region
+        
         regName = “Caraga”
-        # SET QUARTER, ALSO USED IN READING THE S-D FILE
+        
+        # Specify quarter, this used in identifying which worksheet to paste the copied values from the S-D file..
+        
         qtr = “Q1”
-        # SET FOLDER OF SOURCES/FINAL FILES INCLUDING S-D FILE
+        
+        # Specify folder location of Sources and Final files, the S-D file should also be found here.
+        
         baseFolder = “D:/EDRW/Q1”
-        # SET S-D FILE NAME
+        
+        # Specify S-D filename
+        # IMPORTANT! Only .xlsm or .xlsx extensions are accepted
+        
         sdFile = ‘SD Q1 2023.xlsm’
-        # COMMODITY 08=chicken, 09=duck, etc.
+        
+        # Commodity code i.e. 08=chicken, 09=duck, etc.
+        
         commcode = ‘08’
+        
         # Year
+        
         yr = ‘23’
-        # CALL AN INSTANCE OF Edrw
+        
+        # Call an instance of the Edrw package
+        
         myedrw = Edrw()
-        # RUN THE UPDATING
+        
+        # Run update_sources with the parameters
+        
         myedrw.update_sources(regName,qtr,baseFolder,sdFile,commcode,yr)
-        Contribute
+        ```
+        
+        # Contribute
+        
         Issue Tracker: github.com/psalpsdtools/psalpsdtools/issues
         
         Source Code: github.com/psalpsdtools/psalpsdtools
         
-        Support
+        # Support
+        
         If you are having issues, please let us know. We have a mailing list located at: a.diaziii@psa.gov.ph
         
-        License
-        The project is licensed under the BSD license.
+        # License
+        
+        The project is licensed under the MIT license.
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
```

