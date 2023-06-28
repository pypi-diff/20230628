# Comparing `tmp/ler-0.1.8-py2.py3-none-any.whl.zip` & `tmp/ler-0.1.9-py2.py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,12 +1,12 @@
-Zip file size: 33742 bytes, number of entries: 10
+Zip file size: 33785 bytes, number of entries: 10
 -rw-r--r--  2.0 unx      315 b- defN 23-Jun-21 13:48 ler/__init__.py
 -rw-r--r--  2.0 unx     5504 b- defN 23-Jun-21 13:48 ler/helperroutines.py
 -rw-r--r--  2.0 unx    43958 b- defN 23-Jun-23 18:18 ler/lens_galaxy_population.py
 -rw-r--r--  2.0 unx    62630 b- defN 23-Jun-26 16:39 ler/ler.py
 -rw-r--r--  2.0 unx    16064 b- defN 23-Jun-21 13:48 ler/multiprocessing_routine.py
 -rw-r--r--  2.0 unx    34396 b- defN 23-Jun-27 11:04 ler/source_population.py
--rw-r--r--  2.0 unx     4419 b- defN 23-Jun-27 15:44 ler-0.1.8.dist-info/METADATA
--rw-r--r--  2.0 unx      110 b- defN 23-Jun-27 15:44 ler-0.1.8.dist-info/WHEEL
--rw-r--r--  2.0 unx        4 b- defN 23-Jun-27 15:44 ler-0.1.8.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      756 b- defN 23-Jun-27 15:44 ler-0.1.8.dist-info/RECORD
-10 files, 168156 bytes uncompressed, 32478 bytes compressed:  80.7%
+-rw-r--r--  2.0 unx     4514 b- defN 23-Jun-28 10:02 ler-0.1.9.dist-info/METADATA
+-rw-r--r--  2.0 unx      110 b- defN 23-Jun-28 10:02 ler-0.1.9.dist-info/WHEEL
+-rw-r--r--  2.0 unx        4 b- defN 23-Jun-28 10:02 ler-0.1.9.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx      756 b- defN 23-Jun-28 10:02 ler-0.1.9.dist-info/RECORD
+10 files, 168251 bytes uncompressed, 32521 bytes compressed:  80.7%
```

## zipnote {}

```diff
@@ -12,20 +12,20 @@
 
 Filename: ler/multiprocessing_routine.py
 Comment: 
 
 Filename: ler/source_population.py
 Comment: 
 
-Filename: ler-0.1.8.dist-info/METADATA
+Filename: ler-0.1.9.dist-info/METADATA
 Comment: 
 
-Filename: ler-0.1.8.dist-info/WHEEL
+Filename: ler-0.1.9.dist-info/WHEEL
 Comment: 
 
-Filename: ler-0.1.8.dist-info/top_level.txt
+Filename: ler-0.1.9.dist-info/top_level.txt
 Comment: 
 
-Filename: ler-0.1.8.dist-info/RECORD
+Filename: ler-0.1.9.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## Comparing `ler-0.1.8.dist-info/METADATA` & `ler-0.1.9.dist-info/METADATA`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ler
-Version: 0.1.8
+Version: 0.1.9
 Summary: Gravitational waves Lensing Rates
 Home-page: https://github.com/hemantaph/ler
 Author: Hemantakumar
 Author-email: hemantaphurailatpam@gmail.com
 License: MIT
 Description-Content-Type: text/markdown
 Requires-Dist: setuptools (>=67.8.0)
@@ -17,14 +17,15 @@
 Requires-Dist: lenstronomy (>=1.10.4)
 Requires-Dist: astropy (>=5.1)
 Requires-Dist: tqdm (>=4.64.1)
 Requires-Dist: pointpats (>=2.3)
 Requires-Dist: shapely (>=2.0.1)
 
 # LeR
+[![DOI](https://zenodo.org/badge/626733473.svg)](https://zenodo.org/badge/latestdoi/626733473)
 
 `LeR` is a statistical based python package whose core function is to calculate detectable rates of both lensing and unlensed GW events. This calculation very much dependent on the other functionality of the package, which can be subdivided into three parts; 1. Sampling of compact binary source properties, 2. Sampling of lens galaxy characteristics and 3. Solving the lens equation to get image properties of the source. The package as a whole relies on `numpy` array operation, `scipy` interpolation and `multiprocessing` functionality of python to increase speed and functionality without compromising on the ease-of-use. The API of `LeR` is structure such that each functionality mentioned stands on this own right for scientific research but also can be used together as needed. Keys features of `LeR` and its dependencies can be summarized as follows,
 
 - Detectable merger rates: 
     * Calculation not only relies on the properties of simulated events but also on detectability provided by the condition of the GW detectors. For this, `LeR` relies on `gwsnr` for the calculation of optimal signl-to-noise ratio (SNR). Due to prowess of `gwsnr`, rate calulation can be done both for present and future detectors with customizable sensitivities. 
     * Merger rates of both the simulated unlensed and lensed events can be calculated and compared. 
 - Sampling GW sources:
```

## Comparing `ler-0.1.8.dist-info/RECORD` & `ler-0.1.9.dist-info/RECORD`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 ler/__init__.py,sha256=-hsS7aG12rYYb8jcWQrK9fN_ideB0dOULBoUeb0wPqc,315
 ler/helperroutines.py,sha256=8gcDcEhAL4Nq25WH3vNr2H5lJKBCzDBkKZ-GnaSvHXQ,5504
 ler/lens_galaxy_population.py,sha256=bLxcvPw0tOM_gTFtHIe9CShgb2bJtsThtoXFPRbXJgM,43958
 ler/ler.py,sha256=x9oXntzK3SqxxO4q4I7JX21d2WrDtcqnHUgRPqhEVzU,62630
 ler/multiprocessing_routine.py,sha256=xazcM5V0w_ACiqo6DuBqP1DkX4-B-rCuTKSXRexxNxA,16064
 ler/source_population.py,sha256=vmUDmiKDkhlMS1KprFm6lmLbnqyWY-U0JxWT011wPxU,34396
-ler-0.1.8.dist-info/METADATA,sha256=zdFUgMLBU2nu660sGPRBGI0SbZ3IKDtz6sA09CAqCwU,4419
-ler-0.1.8.dist-info/WHEEL,sha256=bb2Ot9scclHKMOLDEHY6B2sicWOgugjFKaJsT7vwMQo,110
-ler-0.1.8.dist-info/top_level.txt,sha256=VWeWLF_gNMjzquGmqrLXqp2J5WegY86apTUimMTh68I,4
-ler-0.1.8.dist-info/RECORD,,
+ler-0.1.9.dist-info/METADATA,sha256=HGD7w8u1HHIPJvo1M6BCNcWy-l1LeOfnGXq2SWECiGU,4514
+ler-0.1.9.dist-info/WHEEL,sha256=bb2Ot9scclHKMOLDEHY6B2sicWOgugjFKaJsT7vwMQo,110
+ler-0.1.9.dist-info/top_level.txt,sha256=VWeWLF_gNMjzquGmqrLXqp2J5WegY86apTUimMTh68I,4
+ler-0.1.9.dist-info/RECORD,,
```

