# Comparing `tmp/pvdeg-0.1.0.tar.gz` & `tmp/pvdeg-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pvdeg-0.1.0.tar", last modified: Wed Jun 28 00:16:00 2023, max compression
+gzip compressed data, was "pvdeg-0.1.1.tar", last modified: Wed Jun 28 02:56:05 2023, max compression
```

## Comparing `pvdeg-0.1.0.tar` & `pvdeg-0.1.1.tar`

### file list

```diff
@@ -1,60 +1,60 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 00:16:00.576320 pvdeg-0.1.0/
-drwxrwxrwx   0        0        0        0 2023-06-28 00:16:00.492698 pvdeg-0.1.0/DataLibrary/
--rw-rw-rw-   0        0        0    25844 2023-06-22 17:36:30.000000 pvdeg-0.1.0/DataLibrary/DegradationDatabase.json
--rw-rw-rw-   0        0        0     7220 2023-06-22 17:36:30.000000 pvdeg-0.1.0/DataLibrary/kinetic_parameters.json
--rw-rw-rw-   0        0        0     1521 2023-06-22 17:36:30.000000 pvdeg-0.1.0/DataLibrary/materials.json
--rw-rw-rw-   0        0        0     1683 2023-02-24 22:58:59.000000 pvdeg-0.1.0/LICENSE.md
--rw-rw-rw-   0        0        0      106 2023-06-22 17:36:30.000000 pvdeg-0.1.0/MANIFEST.in
--rw-rw-rw-   0        0        0     5198 2023-06-28 00:16:00.577322 pvdeg-0.1.0/PKG-INFO
--rw-rw-rw-   0        0        0     4143 2023-06-28 00:11:20.000000 pvdeg-0.1.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 00:16:00.578323 pvdeg-0.1.0/pvdeg/
--rw-rw-rw-   0        0        0      545 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/__init__.py
--rw-rw-rw-   0        0        0      518 2023-06-28 00:16:00.579320 pvdeg-0.1.0/pvdeg/_version.py
--rw-rw-rw-   0        0        0      520 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/cli.py
--rw-rw-rw-   0        0        0    10232 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/collection.py
--rw-rw-rw-   0        0        0      614 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/config.py
-drwxrwxrwx   0        0        0        0 2023-06-28 00:16:00.555730 pvdeg-0.1.0/pvdeg/data/
--rw-rw-rw-   0        0        0    68632 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/Degradation Database.xlsm
--rw-rw-rw-   0        0        0    25844 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/DegradationDatabase.json
--rw-rw-rw-   0        0        0    11800 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/OPAL2.pvl
--rw-rw-rw-   0        0        0    11042 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/PVL_GenProfile.xlsx
--rw-rw-rw-   0        0        0     7220 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/kinetic_parameters.json
--rw-rw-rw-   0        0        0     1521 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/materials.json
--rw-rw-rw-   0        0        0      177 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/module test data.csv
--rw-rw-rw-   0        0        0   788988 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/psm3.csv
--rw-rw-rw-   0        0        0   405943 2023-06-22 17:36:30.000000 pvdeg-0.1.0/pvdeg/data/psm3_demo.csv
--rw-rw-rw-   0        0        0     1757 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/data/spectra.csv
--rw-rw-rw-   0        0        0     4300 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/data/wyller data.csv
--rw-rw-rw-   0        0        0    21109 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/degradation.py
--rw-rw-rw-   0        0        0     3291 2023-06-27 21:36:52.000000 pvdeg-0.1.0/pvdeg/design.py
--rw-rw-rw-   0        0        0     6585 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/fatigue.py
--rw-rw-rw-   0        0        0    28538 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/humidity.py
--rw-rw-rw-   0        0        0    46089 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/letid.py
--rw-rw-rw-   0        0        0    12056 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/scenario.py
--rw-rw-rw-   0        0        0     2916 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/spectral.py
--rw-rw-rw-   0        0        0     7292 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/standards.py
--rw-rw-rw-   0        0        0     3126 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/temperature.py
--rw-rw-rw-   0        0        0    10902 2023-06-22 17:36:31.000000 pvdeg-0.1.0/pvdeg/utilities.py
--rw-rw-rw-   0        0        0     8883 2023-06-27 21:36:52.000000 pvdeg-0.1.0/pvdeg/weather.py
-drwxrwxrwx   0        0        0        0 2023-06-28 00:16:00.533700 pvdeg-0.1.0/pvdeg.egg-info/
--rw-rw-rw-   0        0        0     5198 2023-06-28 00:16:00.000000 pvdeg-0.1.0/pvdeg.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1202 2023-06-28 00:16:00.000000 pvdeg-0.1.0/pvdeg.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 00:16:00.000000 pvdeg-0.1.0/pvdeg.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       40 2023-06-28 00:16:00.000000 pvdeg-0.1.0/pvdeg.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0        2 2023-06-28 00:07:10.000000 pvdeg-0.1.0/pvdeg.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0      231 2023-06-28 00:16:00.000000 pvdeg-0.1.0/pvdeg.egg-info/requires.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 00:16:00.000000 pvdeg-0.1.0/pvdeg.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      349 2023-06-28 00:16:00.578323 pvdeg-0.1.0/setup.cfg
--rw-rw-rw-   0        0        0     2739 2023-06-22 17:36:31.000000 pvdeg-0.1.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 00:16:00.575321 pvdeg-0.1.0/tests/
--rw-rw-rw-   0        0        0     1755 2023-06-26 17:16:53.000000 pvdeg-0.1.0/tests/test_collection.py
--rw-rw-rw-   0        0        0     3068 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_degradation.py
--rw-rw-rw-   0        0        0      804 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_design.py
--rw-rw-rw-   0        0        0      443 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_fatigue.py
--rw-rw-rw-   0        0        0     4152 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_humidity.py
--rw-rw-rw-   0        0        0     1801 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_spectral.py
--rw-rw-rw-   0        0        0     1738 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_standards.py
--rw-rw-rw-   0        0        0     1458 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_temperature.py
--rw-rw-rw-   0        0        0      969 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_utilities.py
--rw-rw-rw-   0        0        0     2284 2023-06-22 17:36:31.000000 pvdeg-0.1.0/tests/test_weather.py
--rw-rw-rw-   0        0        0    68611 2020-06-26 16:45:39.000000 pvdeg-0.1.0/versioneer.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:56:05.681613 pvdeg-0.1.1/
+drwxrwxrwx   0        0        0        0 2023-06-28 02:56:05.572213 pvdeg-0.1.1/DataLibrary/
+-rw-rw-rw-   0        0        0    25844 2023-06-22 17:36:30.000000 pvdeg-0.1.1/DataLibrary/DegradationDatabase.json
+-rw-rw-rw-   0        0        0     7220 2023-06-22 17:36:30.000000 pvdeg-0.1.1/DataLibrary/kinetic_parameters.json
+-rw-rw-rw-   0        0        0     1521 2023-06-22 17:36:30.000000 pvdeg-0.1.1/DataLibrary/materials.json
+-rw-rw-rw-   0        0        0     1683 2023-02-24 22:58:59.000000 pvdeg-0.1.1/LICENSE.md
+-rw-rw-rw-   0        0        0      106 2023-06-22 17:36:30.000000 pvdeg-0.1.1/MANIFEST.in
+-rw-rw-rw-   0        0        0     5420 2023-06-28 02:56:05.681613 pvdeg-0.1.1/PKG-INFO
+-rw-rw-rw-   0        0        0     4365 2023-06-28 00:39:55.000000 pvdeg-0.1.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 02:56:05.684613 pvdeg-0.1.1/pvdeg/
+-rw-rw-rw-   0        0        0      545 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/__init__.py
+-rw-rw-rw-   0        0        0      518 2023-06-28 02:56:05.684613 pvdeg-0.1.1/pvdeg/_version.py
+-rw-rw-rw-   0        0        0      520 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/cli.py
+-rw-rw-rw-   0        0        0    10232 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/collection.py
+-rw-rw-rw-   0        0        0      614 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/config.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:56:05.654172 pvdeg-0.1.1/pvdeg/data/
+-rw-rw-rw-   0        0        0    68632 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/Degradation Database.xlsm
+-rw-rw-rw-   0        0        0    25844 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/DegradationDatabase.json
+-rw-rw-rw-   0        0        0    11800 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/OPAL2.pvl
+-rw-rw-rw-   0        0        0    11042 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/PVL_GenProfile.xlsx
+-rw-rw-rw-   0        0        0     7220 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/kinetic_parameters.json
+-rw-rw-rw-   0        0        0     1521 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/materials.json
+-rw-rw-rw-   0        0        0      177 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/module test data.csv
+-rw-rw-rw-   0        0        0   788988 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/psm3.csv
+-rw-rw-rw-   0        0        0   405943 2023-06-22 17:36:30.000000 pvdeg-0.1.1/pvdeg/data/psm3_demo.csv
+-rw-rw-rw-   0        0        0     1757 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/data/spectra.csv
+-rw-rw-rw-   0        0        0     4300 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/data/wyller data.csv
+-rw-rw-rw-   0        0        0    21109 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/degradation.py
+-rw-rw-rw-   0        0        0     3291 2023-06-27 21:36:52.000000 pvdeg-0.1.1/pvdeg/design.py
+-rw-rw-rw-   0        0        0     6585 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/fatigue.py
+-rw-rw-rw-   0        0        0    28538 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/humidity.py
+-rw-rw-rw-   0        0        0    46089 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/letid.py
+-rw-rw-rw-   0        0        0    12056 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/scenario.py
+-rw-rw-rw-   0        0        0     2916 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/spectral.py
+-rw-rw-rw-   0        0        0     7292 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/standards.py
+-rw-rw-rw-   0        0        0     3126 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/temperature.py
+-rw-rw-rw-   0        0        0    10902 2023-06-22 17:36:31.000000 pvdeg-0.1.1/pvdeg/utilities.py
+-rw-rw-rw-   0        0        0     8883 2023-06-27 21:36:52.000000 pvdeg-0.1.1/pvdeg/weather.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:56:05.624173 pvdeg-0.1.1/pvdeg.egg-info/
+-rw-rw-rw-   0        0        0     5420 2023-06-28 02:56:05.000000 pvdeg-0.1.1/pvdeg.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1202 2023-06-28 02:56:05.000000 pvdeg-0.1.1/pvdeg.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:56:05.000000 pvdeg-0.1.1/pvdeg.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       40 2023-06-28 02:56:05.000000 pvdeg-0.1.1/pvdeg.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0        2 2023-06-28 00:07:10.000000 pvdeg-0.1.1/pvdeg.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0      212 2023-06-28 02:56:05.000000 pvdeg-0.1.1/pvdeg.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 02:56:05.000000 pvdeg-0.1.1/pvdeg.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      349 2023-06-28 02:56:05.683620 pvdeg-0.1.1/setup.cfg
+-rw-rw-rw-   0        0        0     2739 2023-06-22 17:36:31.000000 pvdeg-0.1.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:56:05.679614 pvdeg-0.1.1/tests/
+-rw-rw-rw-   0        0        0     1755 2023-06-26 17:16:53.000000 pvdeg-0.1.1/tests/test_collection.py
+-rw-rw-rw-   0        0        0     3068 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_degradation.py
+-rw-rw-rw-   0        0        0      804 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_design.py
+-rw-rw-rw-   0        0        0      443 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_fatigue.py
+-rw-rw-rw-   0        0        0     4152 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_humidity.py
+-rw-rw-rw-   0        0        0     1801 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_spectral.py
+-rw-rw-rw-   0        0        0     1738 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_standards.py
+-rw-rw-rw-   0        0        0     1458 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_temperature.py
+-rw-rw-rw-   0        0        0      969 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_utilities.py
+-rw-rw-rw-   0        0        0     2284 2023-06-22 17:36:31.000000 pvdeg-0.1.1/tests/test_weather.py
+-rw-rw-rw-   0        0        0    68611 2020-06-26 16:45:39.000000 pvdeg-0.1.1/versioneer.py
```

### Comparing `pvdeg-0.1.0/DataLibrary/DegradationDatabase.json` & `pvdeg-0.1.1/DataLibrary/DegradationDatabase.json`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/DataLibrary/kinetic_parameters.json` & `pvdeg-0.1.1/DataLibrary/kinetic_parameters.json`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/DataLibrary/materials.json` & `pvdeg-0.1.1/DataLibrary/materials.json`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/LICENSE.md` & `pvdeg-0.1.1/LICENSE.md`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/PKG-INFO` & `pvdeg-0.1.1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pvdeg
-Version: 0.1.0
+Version: 0.1.1
 Summary: Pvdeg is a python library that supports the calculation ofdegradation related parameters for photovoltaic (PV) modules.
 Home-page: https://github.com/NREL/PVDegradationTools
 Author: Pvdeg Python Developers
 Author-email: Michael.Kempe@nrel.gov
 Maintainer-email: Silvana.Ovaitt@nrel.gov
 License: BSD-3
 Project-URL: Bug Tracker, https://github.com/NREL/PVDegradationTools/issues
@@ -23,29 +23,28 @@
 Provides-Extra: all
 License-File: LICENSE.md
 
 <img src="pvdeg_tutorials/PVD_logo.png" width="100">
 
 <table>
 <tr>
-  <td>Version</td>
-  <td>
-  <a href="https://zenodo.org/badge/latestdoi/248347431"> FORTHCOMING </a>
-</td>
-</tr>
-
-<tr>
   <td>License</td>
   <td>
     <a href="https://github.com/NREL/PVDegradationTools/blob/master/LICENSE.md">
     <img src="https://img.shields.io/pypi/l/pvlib.svg" alt="license" />
     </a>
 </td>
 </tr>
 <tr>
+  <td>Publications</td>
+  <td>
+	[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8088403.svg)](https://doi.org/10.5281/zenodo.8088403)
+  </td>
+</tr>
+<tr>
   <td>Documentation</td>
   <td>
 	<a href='https://pvdegradationtools.readthedocs.io/en/latest/?badge=latest'>
 	    <img src='https://readthedocs.org/projects/pvdegradationtools/badge/?version=latest' alt='Documentation Status' />
 	</a>
   </td>
 </tr>
@@ -152,8 +151,10 @@
 Citing
 ======
 
 If you use this functions in a published work, please cite:
 
 	Holsapple, Derek, Ayala Pelaez, Silvana, Kempe, Michael. "PV Degradation Tools", NREL Github 2020, Software Record SWR-20-71.
 
-Zenodo reference and OSTI software record information forthcoming.
+And/or the specific release from Zenodo:
+
+	Ovaitt, Silvana, Brown, Matt, Springer, Martin, Karas, Joe, Holsapple, Derek, Kempe, Michael. (2023). NREL/PVDegradationTools: v0.1.0 official release (0.1.0). Zenodo. https://doi.org/10.5281/zenodo.8088403
```

#### html2text {}

```diff
@@ -1,24 +1,25 @@
-Metadata-Version: 2.1 Name: pvdeg Version: 0.1.0 Summary: Pvdeg is a python
+Metadata-Version: 2.1 Name: pvdeg Version: 0.1.1 Summary: Pvdeg is a python
 library that supports the calculation ofdegradation related parameters for
 photovoltaic (PV) modules. Home-page: https://github.com/NREL/
 PVDegradationTools Author: Pvdeg Python Developers Author-email:
 Michael.Kempe@nrel.gov Maintainer-email: Silvana.Ovaitt@nrel.gov License: BSD-
 3 Project-URL: Bug Tracker, https://github.com/NREL/PVDegradationTools/issues
 Project-URL: Documentation, https://pvdegradationtools.readthedocs.io/ Project-
 URL: Source Code, https://github.com/NREL/PVDegradationTools Keywords:
 photovoltaic,solar,degradation,analysis,performance,module,PV Classifier:
 Development Status :: 4 - Beta Classifier: Operating System :: OS Independent
 Classifier: Intended Audience :: Science/Research Classifier: Programming
 Language :: Python :: 3 Classifier: Topic :: Scientific/Engineering Requires-
 Python: >=3.9.0 Description-Content-Type: text/markdown Provides-Extra: doc
 Provides-Extra: test Provides-Extra: all License-File: LICENSE.md
 [pvdeg_tutorials/PVD_logo.png]
-Version       FORTHCOMING
 License       [license]
+Publications  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8088403.svg)]
+              (https://doi.org/10.5281/zenodo.8088403)
 Documentation [Documentation_Status]
 # PV Degradation Tools (pvdeg) This repository contains functions for
 calculating degradation of photovoltaic modules. For example, functions to
 calculate front and rear relative Humidity, as well as Acceleration Factors. A
 degradation calculation function is also being developed, considering humidity
 and spectral irradiances models. Tutorials ========= ### Jupyter Book For in
 depth Tutorials you can run online, see our [jupyter-book](https://
@@ -54,9 +55,11 @@
 please read the copyright license agreement (cla-1.0.md), with instructions on
 signing it in sign-CLA.md. For questions, email us. Getting support
 =============== If you suspect that you may have discovered a bug or if you'd
 like to change something about pvdeg, then please make an issue on our [GitHub
 issues page](hhttps://github.com/NREL/PVDegradationTools/issues). Citing ======
 If you use this functions in a published work, please cite: Holsapple, Derek,
 Ayala Pelaez, Silvana, Kempe, Michael. "PV Degradation Tools", NREL Github
-2020, Software Record SWR-20-71. Zenodo reference and OSTI software record
-information forthcoming.
+2020, Software Record SWR-20-71. And/or the specific release from Zenodo:
+Ovaitt, Silvana, Brown, Matt, Springer, Martin, Karas, Joe, Holsapple, Derek,
+Kempe, Michael. (2023). NREL/PVDegradationTools: v0.1.0 official release
+(0.1.0). Zenodo. https://doi.org/10.5281/zenodo.8088403
```

### Comparing `pvdeg-0.1.0/README.md` & `pvdeg-0.1.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,26 +1,25 @@
 <img src="pvdeg_tutorials/PVD_logo.png" width="100">
 
 <table>
 <tr>
-  <td>Version</td>
-  <td>
-  <a href="https://zenodo.org/badge/latestdoi/248347431"> FORTHCOMING </a>
-</td>
-</tr>
-
-<tr>
   <td>License</td>
   <td>
     <a href="https://github.com/NREL/PVDegradationTools/blob/master/LICENSE.md">
     <img src="https://img.shields.io/pypi/l/pvlib.svg" alt="license" />
     </a>
 </td>
 </tr>
 <tr>
+  <td>Publications</td>
+  <td>
+	[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8088403.svg)](https://doi.org/10.5281/zenodo.8088403)
+  </td>
+</tr>
+<tr>
   <td>Documentation</td>
   <td>
 	<a href='https://pvdegradationtools.readthedocs.io/en/latest/?badge=latest'>
 	    <img src='https://readthedocs.org/projects/pvdegradationtools/badge/?version=latest' alt='Documentation Status' />
 	</a>
   </td>
 </tr>
@@ -127,8 +126,10 @@
 Citing
 ======
 
 If you use this functions in a published work, please cite:
 
 	Holsapple, Derek, Ayala Pelaez, Silvana, Kempe, Michael. "PV Degradation Tools", NREL Github 2020, Software Record SWR-20-71.
 
-Zenodo reference and OSTI software record information forthcoming.
+And/or the specific release from Zenodo:
+
+	Ovaitt, Silvana, Brown, Matt, Springer, Martin, Karas, Joe, Holsapple, Derek, Kempe, Michael. (2023). NREL/PVDegradationTools: v0.1.0 official release (0.1.0). Zenodo. https://doi.org/10.5281/zenodo.8088403
```

#### html2text {}

```diff
@@ -1,10 +1,11 @@
 [pvdeg_tutorials/PVD_logo.png]
-Version       FORTHCOMING
 License       [license]
+Publications  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8088403.svg)]
+              (https://doi.org/10.5281/zenodo.8088403)
 Documentation [Documentation_Status]
 # PV Degradation Tools (pvdeg) This repository contains functions for
 calculating degradation of photovoltaic modules. For example, functions to
 calculate front and rear relative Humidity, as well as Acceleration Factors. A
 degradation calculation function is also being developed, considering humidity
 and spectral irradiances models. Tutorials ========= ### Jupyter Book For in
 depth Tutorials you can run online, see our [jupyter-book](https://
@@ -40,9 +41,11 @@
 please read the copyright license agreement (cla-1.0.md), with instructions on
 signing it in sign-CLA.md. For questions, email us. Getting support
 =============== If you suspect that you may have discovered a bug or if you'd
 like to change something about pvdeg, then please make an issue on our [GitHub
 issues page](hhttps://github.com/NREL/PVDegradationTools/issues). Citing ======
 If you use this functions in a published work, please cite: Holsapple, Derek,
 Ayala Pelaez, Silvana, Kempe, Michael. "PV Degradation Tools", NREL Github
-2020, Software Record SWR-20-71. Zenodo reference and OSTI software record
-information forthcoming.
+2020, Software Record SWR-20-71. And/or the specific release from Zenodo:
+Ovaitt, Silvana, Brown, Matt, Springer, Martin, Karas, Joe, Holsapple, Derek,
+Kempe, Michael. (2023). NREL/PVDegradationTools: v0.1.0 official release
+(0.1.0). Zenodo. https://doi.org/10.5281/zenodo.8088403
```

### Comparing `pvdeg-0.1.0/pvdeg/__init__.py` & `pvdeg-0.1.1/pvdeg/__init__.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/cli.py` & `pvdeg-0.1.1/pvdeg/cli.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/collection.py` & `pvdeg-0.1.1/pvdeg/collection.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/config.py` & `pvdeg-0.1.1/pvdeg/config.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/Degradation Database.xlsm` & `pvdeg-0.1.1/pvdeg/data/Degradation Database.xlsm`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/DegradationDatabase.json` & `pvdeg-0.1.1/pvdeg/data/DegradationDatabase.json`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/OPAL2.pvl` & `pvdeg-0.1.1/pvdeg/data/OPAL2.pvl`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/PVL_GenProfile.xlsx` & `pvdeg-0.1.1/pvdeg/data/PVL_GenProfile.xlsx`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/kinetic_parameters.json` & `pvdeg-0.1.1/pvdeg/data/kinetic_parameters.json`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/materials.json` & `pvdeg-0.1.1/pvdeg/data/materials.json`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/psm3.csv` & `pvdeg-0.1.1/pvdeg/data/psm3.csv`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/psm3_demo.csv` & `pvdeg-0.1.1/pvdeg/data/psm3_demo.csv`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/spectra.csv` & `pvdeg-0.1.1/pvdeg/data/spectra.csv`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/data/wyller data.csv` & `pvdeg-0.1.1/pvdeg/data/wyller data.csv`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/degradation.py` & `pvdeg-0.1.1/pvdeg/degradation.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/design.py` & `pvdeg-0.1.1/pvdeg/design.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/fatigue.py` & `pvdeg-0.1.1/pvdeg/fatigue.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/humidity.py` & `pvdeg-0.1.1/pvdeg/humidity.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/letid.py` & `pvdeg-0.1.1/pvdeg/letid.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/scenario.py` & `pvdeg-0.1.1/pvdeg/scenario.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/spectral.py` & `pvdeg-0.1.1/pvdeg/spectral.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/standards.py` & `pvdeg-0.1.1/pvdeg/standards.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/temperature.py` & `pvdeg-0.1.1/pvdeg/temperature.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/utilities.py` & `pvdeg-0.1.1/pvdeg/utilities.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg/weather.py` & `pvdeg-0.1.1/pvdeg/weather.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/pvdeg.egg-info/PKG-INFO` & `pvdeg-0.1.1/pvdeg.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pvdeg
-Version: 0.1.0
+Version: 0.1.1
 Summary: Pvdeg is a python library that supports the calculation ofdegradation related parameters for photovoltaic (PV) modules.
 Home-page: https://github.com/NREL/PVDegradationTools
 Author: Pvdeg Python Developers
 Author-email: Michael.Kempe@nrel.gov
 Maintainer-email: Silvana.Ovaitt@nrel.gov
 License: BSD-3
 Project-URL: Bug Tracker, https://github.com/NREL/PVDegradationTools/issues
@@ -23,29 +23,28 @@
 Provides-Extra: all
 License-File: LICENSE.md
 
 <img src="pvdeg_tutorials/PVD_logo.png" width="100">
 
 <table>
 <tr>
-  <td>Version</td>
-  <td>
-  <a href="https://zenodo.org/badge/latestdoi/248347431"> FORTHCOMING </a>
-</td>
-</tr>
-
-<tr>
   <td>License</td>
   <td>
     <a href="https://github.com/NREL/PVDegradationTools/blob/master/LICENSE.md">
     <img src="https://img.shields.io/pypi/l/pvlib.svg" alt="license" />
     </a>
 </td>
 </tr>
 <tr>
+  <td>Publications</td>
+  <td>
+	[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8088403.svg)](https://doi.org/10.5281/zenodo.8088403)
+  </td>
+</tr>
+<tr>
   <td>Documentation</td>
   <td>
 	<a href='https://pvdegradationtools.readthedocs.io/en/latest/?badge=latest'>
 	    <img src='https://readthedocs.org/projects/pvdegradationtools/badge/?version=latest' alt='Documentation Status' />
 	</a>
   </td>
 </tr>
@@ -152,8 +151,10 @@
 Citing
 ======
 
 If you use this functions in a published work, please cite:
 
 	Holsapple, Derek, Ayala Pelaez, Silvana, Kempe, Michael. "PV Degradation Tools", NREL Github 2020, Software Record SWR-20-71.
 
-Zenodo reference and OSTI software record information forthcoming.
+And/or the specific release from Zenodo:
+
+	Ovaitt, Silvana, Brown, Matt, Springer, Martin, Karas, Joe, Holsapple, Derek, Kempe, Michael. (2023). NREL/PVDegradationTools: v0.1.0 official release (0.1.0). Zenodo. https://doi.org/10.5281/zenodo.8088403
```

#### html2text {}

```diff
@@ -1,24 +1,25 @@
-Metadata-Version: 2.1 Name: pvdeg Version: 0.1.0 Summary: Pvdeg is a python
+Metadata-Version: 2.1 Name: pvdeg Version: 0.1.1 Summary: Pvdeg is a python
 library that supports the calculation ofdegradation related parameters for
 photovoltaic (PV) modules. Home-page: https://github.com/NREL/
 PVDegradationTools Author: Pvdeg Python Developers Author-email:
 Michael.Kempe@nrel.gov Maintainer-email: Silvana.Ovaitt@nrel.gov License: BSD-
 3 Project-URL: Bug Tracker, https://github.com/NREL/PVDegradationTools/issues
 Project-URL: Documentation, https://pvdegradationtools.readthedocs.io/ Project-
 URL: Source Code, https://github.com/NREL/PVDegradationTools Keywords:
 photovoltaic,solar,degradation,analysis,performance,module,PV Classifier:
 Development Status :: 4 - Beta Classifier: Operating System :: OS Independent
 Classifier: Intended Audience :: Science/Research Classifier: Programming
 Language :: Python :: 3 Classifier: Topic :: Scientific/Engineering Requires-
 Python: >=3.9.0 Description-Content-Type: text/markdown Provides-Extra: doc
 Provides-Extra: test Provides-Extra: all License-File: LICENSE.md
 [pvdeg_tutorials/PVD_logo.png]
-Version       FORTHCOMING
 License       [license]
+Publications  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8088403.svg)]
+              (https://doi.org/10.5281/zenodo.8088403)
 Documentation [Documentation_Status]
 # PV Degradation Tools (pvdeg) This repository contains functions for
 calculating degradation of photovoltaic modules. For example, functions to
 calculate front and rear relative Humidity, as well as Acceleration Factors. A
 degradation calculation function is also being developed, considering humidity
 and spectral irradiances models. Tutorials ========= ### Jupyter Book For in
 depth Tutorials you can run online, see our [jupyter-book](https://
@@ -54,9 +55,11 @@
 please read the copyright license agreement (cla-1.0.md), with instructions on
 signing it in sign-CLA.md. For questions, email us. Getting support
 =============== If you suspect that you may have discovered a bug or if you'd
 like to change something about pvdeg, then please make an issue on our [GitHub
 issues page](hhttps://github.com/NREL/PVDegradationTools/issues). Citing ======
 If you use this functions in a published work, please cite: Holsapple, Derek,
 Ayala Pelaez, Silvana, Kempe, Michael. "PV Degradation Tools", NREL Github
-2020, Software Record SWR-20-71. Zenodo reference and OSTI software record
-information forthcoming.
+2020, Software Record SWR-20-71. And/or the specific release from Zenodo:
+Ovaitt, Silvana, Brown, Matt, Springer, Martin, Karas, Joe, Holsapple, Derek,
+Kempe, Michael. (2023). NREL/PVDegradationTools: v0.1.0 official release
+(0.1.0). Zenodo. https://doi.org/10.5281/zenodo.8088403
```

### Comparing `pvdeg-0.1.0/pvdeg.egg-info/SOURCES.txt` & `pvdeg-0.1.1/pvdeg.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/setup.py` & `pvdeg-0.1.1/setup.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_collection.py` & `pvdeg-0.1.1/tests/test_collection.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_degradation.py` & `pvdeg-0.1.1/tests/test_degradation.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_design.py` & `pvdeg-0.1.1/tests/test_design.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_humidity.py` & `pvdeg-0.1.1/tests/test_humidity.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_spectral.py` & `pvdeg-0.1.1/tests/test_spectral.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_standards.py` & `pvdeg-0.1.1/tests/test_standards.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_temperature.py` & `pvdeg-0.1.1/tests/test_temperature.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_utilities.py` & `pvdeg-0.1.1/tests/test_utilities.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/tests/test_weather.py` & `pvdeg-0.1.1/tests/test_weather.py`

 * *Files identical despite different names*

### Comparing `pvdeg-0.1.0/versioneer.py` & `pvdeg-0.1.1/versioneer.py`

 * *Files identical despite different names*

