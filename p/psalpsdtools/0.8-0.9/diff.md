# Comparing `tmp/psalpsdtools-0.8.tar.gz` & `tmp/psalpsdtools-0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "psalpsdtools-0.8.tar", last modified: Wed Jun 28 00:51:24 2023, max compression
+gzip compressed data, was "psalpsdtools-0.9.tar", last modified: Wed Jun 28 01:36:24 2023, max compression
```

## Comparing `psalpsdtools-0.8.tar` & `psalpsdtools-0.9.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 00:51:24.632434 psalpsdtools-0.8/
--rw-rw-rw-   0        0        0     2624 2023-06-28 00:51:24.632434 psalpsdtools-0.8/PKG-INFO
--rw-rw-rw-   0        0        0     1773 2023-06-28 00:50:45.000000 psalpsdtools-0.8/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 00:51:24.625414 psalpsdtools-0.8/psalpsdtools/
--rw-rw-rw-   0        0        0     7501 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/Edrw.py
--rw-rw-rw-   0        0        0     3556 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/PhRegPrv.py
--rw-rw-rw-   0        0        0       54 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/__init__.py
--rw-rw-rw-   0        0        0      430 2023-06-27 23:11:29.000000 psalpsdtools-0.8/psalpsdtools/usage.py
-drwxrwxrwx   0        0        0        0 2023-06-28 00:51:24.632434 psalpsdtools-0.8/psalpsdtools.egg-info/
--rw-rw-rw-   0        0        0     2624 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      300 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        2 2023-06-27 23:30:13.000000 psalpsdtools-0.8/psalpsdtools.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0       13 2023-06-28 00:51:24.000000 psalpsdtools-0.8/psalpsdtools.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 00:51:24.632434 psalpsdtools-0.8/setup.cfg
--rw-rw-rw-   0        0        0      423 2023-06-28 00:51:00.000000 psalpsdtools-0.8/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 01:36:24.980102 psalpsdtools-0.9/
+-rw-rw-rw-   0        0        0     2802 2023-06-28 01:36:24.980102 psalpsdtools-0.9/PKG-INFO
+-rw-rw-rw-   0        0        0     1935 2023-06-28 01:35:03.000000 psalpsdtools-0.9/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 01:36:24.975581 psalpsdtools-0.9/psalpsdtools/
+-rw-rw-rw-   0        0        0     7501 2023-06-27 23:11:29.000000 psalpsdtools-0.9/psalpsdtools/Edrw.py
+-rw-rw-rw-   0        0        0     3556 2023-06-27 23:11:29.000000 psalpsdtools-0.9/psalpsdtools/PhRegPrv.py
+-rw-rw-rw-   0        0        0       54 2023-06-27 23:11:29.000000 psalpsdtools-0.9/psalpsdtools/__init__.py
+-rw-rw-rw-   0        0        0      430 2023-06-27 23:11:29.000000 psalpsdtools-0.9/psalpsdtools/usage.py
+drwxrwxrwx   0        0        0        0 2023-06-28 01:36:24.980102 psalpsdtools-0.9/psalpsdtools.egg-info/
+-rw-rw-rw-   0        0        0     2802 2023-06-28 01:36:24.000000 psalpsdtools-0.9/psalpsdtools.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      300 2023-06-28 01:36:24.000000 psalpsdtools-0.9/psalpsdtools.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 01:36:24.000000 psalpsdtools-0.9/psalpsdtools.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        2 2023-06-27 23:30:13.000000 psalpsdtools-0.9/psalpsdtools.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0       13 2023-06-28 01:36:24.000000 psalpsdtools-0.9/psalpsdtools.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 01:36:24.982602 psalpsdtools-0.9/setup.cfg
+-rw-rw-rw-   0        0        0      423 2023-06-28 01:36:07.000000 psalpsdtools-0.9/setup.py
```

### Comparing `psalpsdtools-0.8/PKG-INFO` & `psalpsdtools-0.9/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,29 @@
 Metadata-Version: 2.1
 Name: psalpsdtools
-Version: 0.8
+Version: 0.9
 Summary: PSA-LPSD Tools
 Home-page: https://github.com/tondiaz/psalpsdtools
 Author-email: a.diaziii@psa.gov.ph
 License: MIT
 Description: # psalpsdtools
-        ![LPSD Logo](LPSD%20Logo.png =100x100)
+        ![LPSDLogo_sm](https://github.com/tondiaz/psalpsdtools/assets/3798545/643ce509-132b-47ad-b803-d75a1ffb421a)
         
         _psalpsdtools_ was developed for the processing of PSA’s Livestock and Poultry Statistics Division.
         
         # Features
         
         Some of the features include:
         
         ####  Electronic Data Review Worksheet (EDRW)
         - Looking-up and copying of values from the Supply-Disposition file
         - Pasting copied values to the EDRW output file
         - Creating output files by province, based on user specified inputs including:
-        	- region
+        
+          	- region
         	- commodity
         	- year
         
         # Requirements
         
         Python 3.8 or later with all [requirements.txt](https://github.com/tondiaz/psalpsdtools/blob/main/docs/requirements.txt) dependencies installed. To install run:
         
@@ -65,20 +66,21 @@
         # Run update_sources with the parameters
         
         myedrw.update_sources(regName,qtr,baseFolder,sdFile,commcode,yr)
         ```
         
         # Contribute
         
-        Issue Tracker: github.com/psalpsdtools/psalpsdtools/issues
+        Issue Tracker: [github.com/psalpsdtools/psalpsdtools/issues](github.com/psalpsdtools/psalpsdtools/issues)
         
-        Source Code: github.com/psalpsdtools/psalpsdtools
+        Source Code: [github.com/psalpsdtools/psalpsdtools](github.com/psalpsdtools/psalpsdtools)
         
         # Support
         
         If you are having issues, please let us know. We have a mailing list located at: a.diaziii@psa.gov.ph
         
         # License
         
         The project is licensed under the MIT license.
+        
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
```

### Comparing `psalpsdtools-0.8/psalpsdtools/Edrw.py` & `psalpsdtools-0.9/psalpsdtools/Edrw.py`

 * *Files identical despite different names*

### Comparing `psalpsdtools-0.8/psalpsdtools/PhRegPrv.py` & `psalpsdtools-0.9/psalpsdtools/PhRegPrv.py`

 * *Files identical despite different names*

### Comparing `psalpsdtools-0.8/psalpsdtools.egg-info/PKG-INFO` & `psalpsdtools-0.9/psalpsdtools.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,29 @@
 Metadata-Version: 2.1
 Name: psalpsdtools
-Version: 0.8
+Version: 0.9
 Summary: PSA-LPSD Tools
 Home-page: https://github.com/tondiaz/psalpsdtools
 Author-email: a.diaziii@psa.gov.ph
 License: MIT
 Description: # psalpsdtools
-        ![LPSD Logo](LPSD%20Logo.png =100x100)
+        ![LPSDLogo_sm](https://github.com/tondiaz/psalpsdtools/assets/3798545/643ce509-132b-47ad-b803-d75a1ffb421a)
         
         _psalpsdtools_ was developed for the processing of PSA’s Livestock and Poultry Statistics Division.
         
         # Features
         
         Some of the features include:
         
         ####  Electronic Data Review Worksheet (EDRW)
         - Looking-up and copying of values from the Supply-Disposition file
         - Pasting copied values to the EDRW output file
         - Creating output files by province, based on user specified inputs including:
-        	- region
+        
+          	- region
         	- commodity
         	- year
         
         # Requirements
         
         Python 3.8 or later with all [requirements.txt](https://github.com/tondiaz/psalpsdtools/blob/main/docs/requirements.txt) dependencies installed. To install run:
         
@@ -65,20 +66,21 @@
         # Run update_sources with the parameters
         
         myedrw.update_sources(regName,qtr,baseFolder,sdFile,commcode,yr)
         ```
         
         # Contribute
         
-        Issue Tracker: github.com/psalpsdtools/psalpsdtools/issues
+        Issue Tracker: [github.com/psalpsdtools/psalpsdtools/issues](github.com/psalpsdtools/psalpsdtools/issues)
         
-        Source Code: github.com/psalpsdtools/psalpsdtools
+        Source Code: [github.com/psalpsdtools/psalpsdtools](github.com/psalpsdtools/psalpsdtools)
         
         # Support
         
         If you are having issues, please let us know. We have a mailing list located at: a.diaziii@psa.gov.ph
         
         # License
         
         The project is licensed under the MIT license.
+        
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
```

