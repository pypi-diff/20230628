# Comparing `tmp/nomad_camels_driver_voltcraft_pps-0.1.0.tar.gz` & `tmp/nomad_camels_driver_voltcraft_pps-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nomad_camels_driver_voltcraft_pps-0.1.0.tar", last modified: Wed Jun 28 13:34:38 2023, max compression
+gzip compressed data, was "nomad_camels_driver_voltcraft_pps-0.1.1.tar", last modified: Wed Jun 28 14:32:09 2023, max compression
```

## Comparing `nomad_camels_driver_voltcraft_pps-0.1.0.tar` & `nomad_camels_driver_voltcraft_pps-0.1.1.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 13:34:38.700055 nomad_camels_driver_voltcraft_pps-0.1.0/
--rw-rw-rw-   0        0        0    27028 2023-04-13 14:09:42.000000 nomad_camels_driver_voltcraft_pps-0.1.0/LICENSE.txt
--rw-rw-rw-   0        0        0     1041 2023-06-28 13:34:38.675005 nomad_camels_driver_voltcraft_pps-0.1.0/PKG-INFO
--rw-rw-rw-   0        0        0      436 2023-06-28 09:30:35.000000 nomad_camels_driver_voltcraft_pps-0.1.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 13:34:38.509891 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps/
--rw-rw-rw-   0        0        0     2703 2023-06-28 09:30:35.000000 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps/voltcraft_pps.py
--rw-rw-rw-   0        0        0     1746 2023-06-28 09:30:35.000000 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps/voltcraft_pps_ophyd.py
-drwxrwxrwx   0        0        0        0 2023-06-28 13:34:38.626915 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps.egg-info/
--rw-rw-rw-   0        0        0     1041 2023-06-28 13:34:38.000000 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      428 2023-06-28 13:34:38.000000 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 13:34:38.000000 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       27 2023-06-28 13:34:38.000000 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps.egg-info/requires.txt
--rw-rw-rw-   0        0        0       34 2023-06-28 13:34:38.000000 nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      737 2023-06-28 09:30:35.000000 nomad_camels_driver_voltcraft_pps-0.1.0/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-28 13:34:38.700055 nomad_camels_driver_voltcraft_pps-0.1.0/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 14:32:09.078145 nomad_camels_driver_voltcraft_pps-0.1.1/
+-rw-rw-rw-   0        0        0    27028 2023-04-13 14:09:42.000000 nomad_camels_driver_voltcraft_pps-0.1.1/LICENSE.txt
+-rw-rw-rw-   0        0        0     1063 2023-06-28 14:32:09.078145 nomad_camels_driver_voltcraft_pps-0.1.1/PKG-INFO
+-rw-rw-rw-   0        0        0      447 2023-06-28 14:25:07.000000 nomad_camels_driver_voltcraft_pps-0.1.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 14:32:09.067148 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps/
+-rw-rw-rw-   0        0        0     2703 2023-06-28 09:30:35.000000 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps/voltcraft_pps.py
+-rw-rw-rw-   0        0        0     1746 2023-06-28 09:30:35.000000 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps/voltcraft_pps_ophyd.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:32:09.076146 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps.egg-info/
+-rw-rw-rw-   0        0        0     1063 2023-06-28 14:32:09.000000 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      428 2023-06-28 14:32:09.000000 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:32:09.000000 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 14:32:09.000000 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       34 2023-06-28 14:32:09.000000 nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      717 2023-06-28 14:31:46.000000 nomad_camels_driver_voltcraft_pps-0.1.1/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 14:32:09.079146 nomad_camels_driver_voltcraft_pps-0.1.1/setup.cfg
```

### Comparing `nomad_camels_driver_voltcraft_pps-0.1.0/LICENSE.txt` & `nomad_camels_driver_voltcraft_pps-0.1.1/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `nomad_camels_driver_voltcraft_pps-0.1.0/PKG-INFO` & `nomad_camels_driver_voltcraft_pps-0.1.1/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 Metadata-Version: 2.1
 Name: nomad_camels_driver_voltcraft_pps
-Version: 0.1.0
+Version: 0.1.1
 Summary: Driver for communicating with a Voltcraft PPS power supply.
 Author-email: FAIRmat - HU Berlin <nomad-camels@fau.de>
 Project-URL: GitHub Page, https://github.com/FAU-LAP/NOMAD-CAMELS
-Project-URL: Documentation, https://fau-lap.github.io/NOMAD-CAMELS/docs/instruments.html
+Project-URL: Documentation, https://fau-lap.github.io/NOMAD-CAMELS/doc/instruments/instruments.html
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Lesser General Public License v2 (LGPLv2)
 Requires-Python: >=3.9.6
 Description-Content-Type: text/markdown
 License-File: LICENSE.txt
 
 # NOMAD-CAMELS Driver for Voltcraft PPS
 
 Driver for communicating with a Voltcraft PPS power supply written for the measurement software [NOMAD-CAMELS](https://fau-lap.github.io/NOMAD-CAMELS/).
 
 Implements the `VISA_Device`, `VISA_Signal_RO`, and `VISA_Signal` classes used in many device drivers.
 
 ## Documentation
 
-For more information and documentation visit [this page](https://fau-lap.github.io/NOMAD-CAMELS/docs/instruments.html).
+For more information and documentation visit [this page](https://fau-lap.github.io/NOMAD-CAMELS/doc/instruments/instruments.html).
```

### Comparing `nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps/voltcraft_pps.py` & `nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps/voltcraft_pps.py`

 * *Files identical despite different names*

### Comparing `nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps/voltcraft_pps_ophyd.py` & `nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps/voltcraft_pps_ophyd.py`

 * *Files identical despite different names*

### Comparing `nomad_camels_driver_voltcraft_pps-0.1.0/nomad_camels_driver_voltcraft_pps.egg-info/PKG-INFO` & `nomad_camels_driver_voltcraft_pps-0.1.1/nomad_camels_driver_voltcraft_pps.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 Metadata-Version: 2.1
 Name: nomad-camels-driver-voltcraft-pps
-Version: 0.1.0
+Version: 0.1.1
 Summary: Driver for communicating with a Voltcraft PPS power supply.
 Author-email: FAIRmat - HU Berlin <nomad-camels@fau.de>
 Project-URL: GitHub Page, https://github.com/FAU-LAP/NOMAD-CAMELS
-Project-URL: Documentation, https://fau-lap.github.io/NOMAD-CAMELS/docs/instruments.html
+Project-URL: Documentation, https://fau-lap.github.io/NOMAD-CAMELS/doc/instruments/instruments.html
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: GNU Lesser General Public License v2 (LGPLv2)
 Requires-Python: >=3.9.6
 Description-Content-Type: text/markdown
 License-File: LICENSE.txt
 
 # NOMAD-CAMELS Driver for Voltcraft PPS
 
 Driver for communicating with a Voltcraft PPS power supply written for the measurement software [NOMAD-CAMELS](https://fau-lap.github.io/NOMAD-CAMELS/).
 
 Implements the `VISA_Device`, `VISA_Signal_RO`, and `VISA_Signal` classes used in many device drivers.
 
 ## Documentation
 
-For more information and documentation visit [this page](https://fau-lap.github.io/NOMAD-CAMELS/docs/instruments.html).
+For more information and documentation visit [this page](https://fau-lap.github.io/NOMAD-CAMELS/doc/instruments/instruments.html).
```

