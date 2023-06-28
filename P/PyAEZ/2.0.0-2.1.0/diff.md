# Comparing `tmp/PyAEZ-2.0.0.tar.gz` & `tmp/PyAEZ-2.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "PyAEZ-2.0.0.tar", last modified: Sun Nov 27 16:20:48 2022, max compression
+gzip compressed data, was "PyAEZ-2.1.0.tar", last modified: Wed Jun 28 07:44:56 2023, max compression
```

## Comparing `PyAEZ-2.0.0.tar` & `PyAEZ-2.1.0.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwx------   0 kb         (501) staff       (20)        0 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/
--rwx------   0 kb         (501) staff       (20)     1090 2022-11-27 15:06:35.000000 PyAEZ-2.0.0/LICENSE
--rwx------   0 kb         (501) staff       (20)     5288 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/PKG-INFO
-drwx------   0 kb         (501) staff       (20)        0 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/PyAEZ.egg-info/
--rwx------   0 kb         (501) staff       (20)     5288 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/PyAEZ.egg-info/PKG-INFO
--rwx------   0 kb         (501) staff       (20)      563 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/PyAEZ.egg-info/SOURCES.txt
--rwx------   0 kb         (501) staff       (20)        1 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/PyAEZ.egg-info/dependency_links.txt
--rwx------   0 kb         (501) staff       (20)       80 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/PyAEZ.egg-info/requires.txt
--rwx------   0 kb         (501) staff       (20)        6 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/PyAEZ.egg-info/top_level.txt
--rwx------   0 kb         (501) staff       (20)     4356 2022-11-27 15:10:28.000000 PyAEZ-2.0.0/README.md
-drwx------   0 kb         (501) staff       (20)        0 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/pyaez/
--rwx------   0 kb         (501) staff       (20)     4282 2022-11-06 13:03:04.000000 PyAEZ-2.0.0/pyaez/ALL_REDUCTION_FACTORS_IRR.py
--rwx------   0 kb         (501) staff       (20)     4282 2022-11-06 13:03:04.000000 PyAEZ-2.0.0/pyaez/ALL_REDUCTION_FACTORS_RAIN.py
--rwx------   0 kb         (501) staff       (20)     9103 2022-11-06 12:39:06.000000 PyAEZ-2.0.0/pyaez/BioMassCalc.py
--rwx------   0 kb         (501) staff       (20)    72578 2022-11-23 03:57:33.000000 PyAEZ-2.0.0/pyaez/ClimateRegime.py
--rwx------   0 kb         (501) staff       (20)     1305 2022-11-27 06:35:07.000000 PyAEZ-2.0.0/pyaez/ClimaticConstraints.py
--rwx------   0 kb         (501) staff       (20)    20515 2022-11-25 14:23:55.000000 PyAEZ-2.0.0/pyaez/CropSimulation.py
--rwx------   0 kb         (501) staff       (20)     5830 2022-11-06 12:39:06.000000 PyAEZ-2.0.0/pyaez/CropWatCalc.py
--rwx------   0 kb         (501) staff       (20)     3442 2022-11-06 12:39:06.000000 PyAEZ-2.0.0/pyaez/ETOCalc.py
--rwx------   0 kb         (501) staff       (20)     4685 2022-11-27 06:36:06.000000 PyAEZ-2.0.0/pyaez/EconomicSuitability.py
--rwx------   0 kb         (501) staff       (20)     8743 2022-11-22 01:57:19.000000 PyAEZ-2.0.0/pyaez/LGPCalc.py
--rwx------   0 kb         (501) staff       (20)    13273 2022-11-09 10:56:52.000000 PyAEZ-2.0.0/pyaez/SoilConstraints.py
--rwx------   0 kb         (501) staff       (20)     1809 2022-11-09 16:14:22.000000 PyAEZ-2.0.0/pyaez/TerrainConstraints.py
--rwx------   0 kb         (501) staff       (20)     7191 2022-11-09 12:27:04.000000 PyAEZ-2.0.0/pyaez/ThermalScreening.py
--rwx------   0 kb         (501) staff       (20)     6959 2022-11-25 14:02:55.000000 PyAEZ-2.0.0/pyaez/UtilitiesCalc.py
--rwx------   0 kb         (501) staff       (20)        0 2022-11-11 19:27:23.000000 PyAEZ-2.0.0/pyaez/__init__.py
--rwx------   0 kb         (501) staff       (20)      381 2022-11-27 16:00:50.000000 PyAEZ-2.0.0/pyaez/__version__.py
--rwx------   0 kb         (501) staff       (20)       38 2022-11-27 16:20:48.000000 PyAEZ-2.0.0/setup.cfg
--rwx------   0 kb         (501) staff       (20)     1761 2022-11-11 19:27:23.000000 PyAEZ-2.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:44:56.564985 PyAEZ-2.1.0/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1090 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     6579 2023-06-28 07:44:56.564985 PyAEZ-2.1.0/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:44:56.556985 PyAEZ-2.1.0/PyAEZ.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6579 2023-06-28 07:44:56.000000 PyAEZ-2.1.0/PyAEZ.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      563 2023-06-28 07:44:56.000000 PyAEZ-2.1.0/PyAEZ.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:44:56.000000 PyAEZ-2.1.0/PyAEZ.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       80 2023-06-28 07:44:56.000000 PyAEZ-2.1.0/PyAEZ.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 07:44:56.000000 PyAEZ-2.1.0/PyAEZ.egg-info/top_level.txt
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5647 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:44:56.560985 PyAEZ-2.1.0/pyaez/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4935 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/ALL_REDUCTION_FACTORS_IRR.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4952 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/ALL_REDUCTION_FACTORS_RAIN.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     9004 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/BioMassCalc.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    82105 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/ClimateRegime.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    10845 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/ClimaticConstraints.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    43303 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/CropSimulation.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5549 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/CropWatCalc.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     6024 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/ETOCalc.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4661 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/EconomicSuitability.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    10090 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/LGPCalc.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    13321 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/SoilConstraints.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1857 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/TerrainConstraints.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    32295 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/ThermalScreening.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     7000 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/UtilitiesCalc.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/__init__.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      381 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/pyaez/__version__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 07:44:56.564985 PyAEZ-2.1.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1761 2023-06-28 07:44:38.000000 PyAEZ-2.1.0/setup.py
```

### Comparing `PyAEZ-2.0.0/LICENSE` & `PyAEZ-2.1.0/LICENSE`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 MIT License
 
-Copyright (c) 2022 GIC-AIT
-Copyright (c) 2022 FAO-UN
+Copyright (c) 2023 GIC-AIT
+Copyright (c) 2023 FAO-UN
 
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

### Comparing `PyAEZ-2.0.0/PKG-INFO` & `PyAEZ-2.1.0/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: PyAEZ
-Version: 2.0.0
+Version: 2.1.0
 Summary: PyAEZ is a python package consisted of many algorithms related to Agro-ecalogical zoning (AEZ) framework.
 Home-page: https://github.com/gicait/PyAEZ
 Author: Geoinformatics Center, Asian Institute of Technology, Thailand
 Author-email: geoinfo@ait.asia
 License: MIT License
 Keywords: AEZ,Python,Agro-ecological Zoning,Climate Regime,Crop Simulations,Climate Constraints,Soil Constraints,Terrain Constraints,Economic Suitability Analysis,Utility Calculation,Biomass Calculations,Evapotranspiration Calculation,CropWat calculations
 Classifier: Programming Language :: Python :: 3
@@ -26,15 +26,15 @@
 PyAEZ is a python package consisted of many algorithms related to Agro-ecalogical zoning (AEZ) framework. PyAEZ tries to encapsulate all complex calculations in AEZ and try to provide user friendly, and intuitive ways to input data and output results after calculations.
 
 # Installation
 
 Now the package can be installed using `pip` command as below,
 
 ```shell
-pip install pyaez==2.0.0
+pip install pyaez==2.1.0
 ```
 
 Alternatively, can be installed using using `conda` command as below,
 
 ```shell
 conda install -c conda-forge pyaez
 ```
@@ -62,38 +62,58 @@
 - numpy
 - scipy
 - gdal
 - numba 
 
 ### Step-by-step Process
 
-Following 6 Jupyter notebooks in the repository can be used as worked full example for PyAEZ 6 major modules.
+Following 6 Jupyter notebooks in the GitHub repository can be used as worked full example for PyAEZ 6 major modules.
 
 - NB1_ClimateRegime.ipynb
 - NB2_CropSimulation.ipynb
 - NB3_ClimaticConstraints.ipynb
 - NB4_SoilConstraints.ipynb
 - NB5_TerrainConstraints.ipynb
 - NB6_EconomicSuitability.ipynb
 
 **Note**: _NB2_CropSimulation.ipynb_ takes a huge amount of time due to automatic crop calendar calculations. Hence, we have rewritten core parts of PyAEZ (_CropWatCalc.py_, _BioMassCalc.py_ and _ETOCalc.py_) with [Numba](http://numba.pydata.org/) compatible manner as well. Numba translates Python functions to optimized machine code at runtime, allowing calculation speeds close to C or FORTRAN.
 
+### Release Note PyAEZv2.1
+The goal of this release is to improve the overall accuracy and reliability of the AEZ methodology in Module 1, 2, and 3. The key updates are as follows:
+
+**Module 1**:
+- Major improvements in the Length of Growing Period (LGP) calculation routine through the implementation of Numba (a Python package to speed up the calculation) and cross-checking the methodology with the Global AEZ from IIASA. 
+- All the climatic indicators had been thoroughly cross-checked and verified with the Global AEZ outputs. 
+
+**Module 2**:
+- Reading crop/crop cycle parameters from excel sheet.
+- Updated algorithm for TSUM screening and parameter settings.
+- New thermal screening logics: permafrost screening, crop-specific rule screening.
+- Updated algorithm for perennial crop simulations.
+- New outputs: thermal reduction factor maps (fc1), yield reduction due to moisture deficit (fc2) and optimum starting date, for both rainfed and irrigated conditions.
+
+**Module 3**:
+- New look-up table setting for agro-climatic reduction factors for both rainfed and irrigated conditions.
+- Updated algorithm related to agro-climatic constraints calculation.
+- New outputs: Adjusted Length of Growing Period for agro-climatic constraints, agro-climatic constraint map (fc3).
+
+
 ### Documentation
 
 API Documentation is located in "docs" folder.
 
 ### Citation
 
 Use this bibtex to cite us.
 
 ```
-@misc{PyAEZ_2022,
+@misc{PyAEZ(v2.1.0),
   title={PyAEZ Python Package for Agro-ecological zoning (AEZ)},
-  author={N. Lakmal Deshapriya, Swun Wunna Htet, Kittiphon Boonma, Thaileng Thol, Kavinda Gunasekara, Rajendra Shrestha, Gianluca Franceschini, Freddy Nachtergaele, Monica Petri, Beau Damen},
-  year={2022},
+  author={Swun Wunna Htet, Kittiphon Boonma, Gianluca Franceschini, N. Lakmal Deshapriya, Thaileng Thol, Kavinda Gunasekara, Rajendra Shrestha,  Freddy Nachtergaele, Monica Petri, Beau Damen},
+  year={2023},
   publisher={Github},
   journal={GitHub repository},
   howpublished={\url{https://github.com/gicait/PyAEZ}},
 }
 ```
 
 ### Developed by
```

### Comparing `PyAEZ-2.0.0/PyAEZ.egg-info/PKG-INFO` & `PyAEZ-2.1.0/PyAEZ.egg-info/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: PyAEZ
-Version: 2.0.0
+Version: 2.1.0
 Summary: PyAEZ is a python package consisted of many algorithms related to Agro-ecalogical zoning (AEZ) framework.
 Home-page: https://github.com/gicait/PyAEZ
 Author: Geoinformatics Center, Asian Institute of Technology, Thailand
 Author-email: geoinfo@ait.asia
 License: MIT License
 Keywords: AEZ,Python,Agro-ecological Zoning,Climate Regime,Crop Simulations,Climate Constraints,Soil Constraints,Terrain Constraints,Economic Suitability Analysis,Utility Calculation,Biomass Calculations,Evapotranspiration Calculation,CropWat calculations
 Classifier: Programming Language :: Python :: 3
@@ -26,15 +26,15 @@
 PyAEZ is a python package consisted of many algorithms related to Agro-ecalogical zoning (AEZ) framework. PyAEZ tries to encapsulate all complex calculations in AEZ and try to provide user friendly, and intuitive ways to input data and output results after calculations.
 
 # Installation
 
 Now the package can be installed using `pip` command as below,
 
 ```shell
-pip install pyaez==2.0.0
+pip install pyaez==2.1.0
 ```
 
 Alternatively, can be installed using using `conda` command as below,
 
 ```shell
 conda install -c conda-forge pyaez
 ```
@@ -62,38 +62,58 @@
 - numpy
 - scipy
 - gdal
 - numba 
 
 ### Step-by-step Process
 
-Following 6 Jupyter notebooks in the repository can be used as worked full example for PyAEZ 6 major modules.
+Following 6 Jupyter notebooks in the GitHub repository can be used as worked full example for PyAEZ 6 major modules.
 
 - NB1_ClimateRegime.ipynb
 - NB2_CropSimulation.ipynb
 - NB3_ClimaticConstraints.ipynb
 - NB4_SoilConstraints.ipynb
 - NB5_TerrainConstraints.ipynb
 - NB6_EconomicSuitability.ipynb
 
 **Note**: _NB2_CropSimulation.ipynb_ takes a huge amount of time due to automatic crop calendar calculations. Hence, we have rewritten core parts of PyAEZ (_CropWatCalc.py_, _BioMassCalc.py_ and _ETOCalc.py_) with [Numba](http://numba.pydata.org/) compatible manner as well. Numba translates Python functions to optimized machine code at runtime, allowing calculation speeds close to C or FORTRAN.
 
+### Release Note PyAEZv2.1
+The goal of this release is to improve the overall accuracy and reliability of the AEZ methodology in Module 1, 2, and 3. The key updates are as follows:
+
+**Module 1**:
+- Major improvements in the Length of Growing Period (LGP) calculation routine through the implementation of Numba (a Python package to speed up the calculation) and cross-checking the methodology with the Global AEZ from IIASA. 
+- All the climatic indicators had been thoroughly cross-checked and verified with the Global AEZ outputs. 
+
+**Module 2**:
+- Reading crop/crop cycle parameters from excel sheet.
+- Updated algorithm for TSUM screening and parameter settings.
+- New thermal screening logics: permafrost screening, crop-specific rule screening.
+- Updated algorithm for perennial crop simulations.
+- New outputs: thermal reduction factor maps (fc1), yield reduction due to moisture deficit (fc2) and optimum starting date, for both rainfed and irrigated conditions.
+
+**Module 3**:
+- New look-up table setting for agro-climatic reduction factors for both rainfed and irrigated conditions.
+- Updated algorithm related to agro-climatic constraints calculation.
+- New outputs: Adjusted Length of Growing Period for agro-climatic constraints, agro-climatic constraint map (fc3).
+
+
 ### Documentation
 
 API Documentation is located in "docs" folder.
 
 ### Citation
 
 Use this bibtex to cite us.
 
 ```
-@misc{PyAEZ_2022,
+@misc{PyAEZ(v2.1.0),
   title={PyAEZ Python Package for Agro-ecological zoning (AEZ)},
-  author={N. Lakmal Deshapriya, Swun Wunna Htet, Kittiphon Boonma, Thaileng Thol, Kavinda Gunasekara, Rajendra Shrestha, Gianluca Franceschini, Freddy Nachtergaele, Monica Petri, Beau Damen},
-  year={2022},
+  author={Swun Wunna Htet, Kittiphon Boonma, Gianluca Franceschini, N. Lakmal Deshapriya, Thaileng Thol, Kavinda Gunasekara, Rajendra Shrestha,  Freddy Nachtergaele, Monica Petri, Beau Damen},
+  year={2023},
   publisher={Github},
   journal={GitHub repository},
   howpublished={\url{https://github.com/gicait/PyAEZ}},
 }
 ```
 
 ### Developed by
```

### Comparing `PyAEZ-2.0.0/PyAEZ.egg-info/SOURCES.txt` & `PyAEZ-2.1.0/PyAEZ.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `PyAEZ-2.0.0/README.md` & `PyAEZ-2.1.0/README.md`

 * *Files 17% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 PyAEZ is a python package consisted of many algorithms related to Agro-ecalogical zoning (AEZ) framework. PyAEZ tries to encapsulate all complex calculations in AEZ and try to provide user friendly, and intuitive ways to input data and output results after calculations.
 
 # Installation
 
 Now the package can be installed using `pip` command as below,
 
 ```shell
-pip install pyaez==2.0.0
+pip install pyaez==2.1.0
 ```
 
 Alternatively, can be installed using using `conda` command as below,
 
 ```shell
 conda install -c conda-forge pyaez
 ```
@@ -43,38 +43,58 @@
 - numpy
 - scipy
 - gdal
 - numba 
 
 ### Step-by-step Process
 
-Following 6 Jupyter notebooks in the repository can be used as worked full example for PyAEZ 6 major modules.
+Following 6 Jupyter notebooks in the GitHub repository can be used as worked full example for PyAEZ 6 major modules.
 
 - NB1_ClimateRegime.ipynb
 - NB2_CropSimulation.ipynb
 - NB3_ClimaticConstraints.ipynb
 - NB4_SoilConstraints.ipynb
 - NB5_TerrainConstraints.ipynb
 - NB6_EconomicSuitability.ipynb
 
 **Note**: _NB2_CropSimulation.ipynb_ takes a huge amount of time due to automatic crop calendar calculations. Hence, we have rewritten core parts of PyAEZ (_CropWatCalc.py_, _BioMassCalc.py_ and _ETOCalc.py_) with [Numba](http://numba.pydata.org/) compatible manner as well. Numba translates Python functions to optimized machine code at runtime, allowing calculation speeds close to C or FORTRAN.
 
+### Release Note PyAEZv2.1
+The goal of this release is to improve the overall accuracy and reliability of the AEZ methodology in Module 1, 2, and 3. The key updates are as follows:
+
+**Module 1**:
+- Major improvements in the Length of Growing Period (LGP) calculation routine through the implementation of Numba (a Python package to speed up the calculation) and cross-checking the methodology with the Global AEZ from IIASA. 
+- All the climatic indicators had been thoroughly cross-checked and verified with the Global AEZ outputs. 
+
+**Module 2**:
+- Reading crop/crop cycle parameters from excel sheet.
+- Updated algorithm for TSUM screening and parameter settings.
+- New thermal screening logics: permafrost screening, crop-specific rule screening.
+- Updated algorithm for perennial crop simulations.
+- New outputs: thermal reduction factor maps (fc1), yield reduction due to moisture deficit (fc2) and optimum starting date, for both rainfed and irrigated conditions.
+
+**Module 3**:
+- New look-up table setting for agro-climatic reduction factors for both rainfed and irrigated conditions.
+- Updated algorithm related to agro-climatic constraints calculation.
+- New outputs: Adjusted Length of Growing Period for agro-climatic constraints, agro-climatic constraint map (fc3).
+
+
 ### Documentation
 
 API Documentation is located in "docs" folder.
 
 ### Citation
 
 Use this bibtex to cite us.
 
 ```
-@misc{PyAEZ_2022,
+@misc{PyAEZ(v2.1.0),
   title={PyAEZ Python Package for Agro-ecological zoning (AEZ)},
-  author={N. Lakmal Deshapriya, Swun Wunna Htet, Kittiphon Boonma, Thaileng Thol, Kavinda Gunasekara, Rajendra Shrestha, Gianluca Franceschini, Freddy Nachtergaele, Monica Petri, Beau Damen},
-  year={2022},
+  author={Swun Wunna Htet, Kittiphon Boonma, Gianluca Franceschini, N. Lakmal Deshapriya, Thaileng Thol, Kavinda Gunasekara, Rajendra Shrestha,  Freddy Nachtergaele, Monica Petri, Beau Damen},
+  year={2023},
   publisher={Github},
   journal={GitHub repository},
   howpublished={\url{https://github.com/gicait/PyAEZ}},
 }
 ```
 
 ### Developed by
```

### Comparing `PyAEZ-2.0.0/pyaez/ALL_REDUCTION_FACTORS_IRR.py` & `PyAEZ-2.1.0/pyaez/ALL_REDUCTION_FACTORS_IRR.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,18 +1,31 @@
+"""
+PyAEZ version 2.1.0 (June 2023)
+"""
 '''--------------------------------------------------------'''
 '''Reduction Factors for Climatic Constraints'''
 '''--------------------------------------------------------'''
 
 #defining yield reduction factors based of LGP Equivalent class
-lgp_eq_class = [[0,29],[30,59],[60,89],[90,119],[120,149],[150,179],[180,209],[210,239],[240,269],[270,299],[300,329],[330,366]]
-lgp_eq_red_fr = [[25,25,25,25,25,25,25,50,50,50,75,75],
-                 [100,100,100,100,100,100,100,100,100,100,100,100],
-                 [50,50,50,50,50,75,75,100,100,100,100,75],
-                 [100,100,100,100,100,100,100,100,100,100,100,75]]
+# This part now corresponds to wetness indicators LPGagc.
+lgp_eq_class = [[0,29],[30,59],[60,89],[90,119],[120,149],[150,179],[180,209],[210,239],[240,269],[270,299],[300,329],[330,364], [365, 366]] # 13
+lgpt10_class = [[0,29],[30,59],[60,89],[90,119],[120,149],[150,179],[180,209],[210,239],[240,269],[270,299],[300,329],[330,364], [365, 366]] # 13
 
+# Lookup table when mean annual temperature greater than 20 deg Celsius
+lgp_eq_red_fr_gt_20deg = [[0,0,0,0,0,0,0,0,25,25,25,25,50], # b
+                          [0,0,0,0,0,0,0,0,0,0,0,25,50], # c
+                          [0,0,0,0,0,0,0,10,30,30,30,30,30]] #d
+
+# Lookup table when mean annual temperature less than 10 deg Celsius
+lgp_eq_red_fr_lt_10deg = [[0,0,0,0,0,0,0,0,10,10,10,10,30], # b
+                          [0,0,0,0,0,0,0,0,0,0,0,10,30],# c
+                          [0,0,0,0,0,0,0,10,30,30,30,30,30]]# d
+
+# Look-up table for frost-free period for each day interval
+lgpt10 = [0, 0, 0, 0, 0 , 0, 0, 0, 0, 0, 0, 0, 0]
 '''--------------------------------------------------------'''
 '''Reduction Factors for Soil Constraints'''
 '''--------------------------------------------------------'''
 
 # value - values of soil characteristics (mush be ascending order)
 # factor - yield reduction factors corresponding to each value
```

### Comparing `PyAEZ-2.0.0/pyaez/ALL_REDUCTION_FACTORS_RAIN.py` & `PyAEZ-2.1.0/pyaez/ALL_REDUCTION_FACTORS_RAIN.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,18 +1,31 @@
+"""
+PyAEZ version 2.1.0 (June 2023)
+"""
 '''--------------------------------------------------------'''
 '''Reduction Factors for Climatic Constraints'''
 '''--------------------------------------------------------'''
 
 #defining yield reduction factors based of LGP Equivalent class
-lgp_eq_class = [[0,29],[30,59],[60,89],[90,119],[120,149],[150,179],[180,209],[210,239],[240,269],[270,299],[300,329],[330,366]]
-lgp_eq_red_fr = [[25,25,25,25,25,25,25,50,50,50,75,75],
-                 [100,100,100,100,100,100,100,100,100,100,100,100],
-                 [50,50,50,50,50,75,75,100,100,100,100,75],
-                 [100,100,100,100,100,100,100,100,100,100,100,75]]
+# This part now corresponds to wetness indicators LPGagc.
+lgp_eq_class = [[0,29],[30,59],[60,89],[90,119],[120,149],[150,179],[180,209],[210,239],[240,269],[270,299],[300,329],[330,364], [365, 366]] # Total 13
+lgpt10_class = [[0,29],[30,59],[60,89],[90,119],[120,149],[150,179],[180,209],[210,239],[240,269],[270,299],[300,329],[330,364], [365, 366]] # 13
 
+# Lookup table when mean annual temperature greater than 20 deg Celsius
+lgp_eq_red_fr_gt_20deg = [[0,0,0,0,0,0,0,0,25,25,25,25,50], #13
+                          [50,50,50,25,0,0,0,0,0,0,0,25,50], # 13
+                          [0,0,0,0,0,0,0,10,30,30,30,30,30]] # 13
+
+# Lookup table when mean annual temperature less than 10 deg Celsius
+lgp_eq_red_fr_lt_10deg = [[0,0,0,0,0,0,0,0,10,10,10,10,30], # 13
+                          [30,30,30,10,0,0,0,0,0,0,0,10,30], # 13
+                          [0,0,0,0,0,0,0,10,30,30,30,30,30]]
+
+# Look-up table for frost-free period for each day interval
+lgpt10 = [0, 0, 0, 0, 0 , 0, 0, 0, 0, 0, 0, 0, 0]
 '''--------------------------------------------------------'''
 '''Reduction Factors for Soil Constraints'''
 '''--------------------------------------------------------'''
 
 # value - values of soil characteristics (mush be ascending order)
 # factor - yield reduction factors corresponding to each value
```

### Comparing `PyAEZ-2.0.0/pyaez/BioMassCalc.py` & `PyAEZ-2.1.0/pyaez/BioMassCalc.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,17 +1,60 @@
 """
-PyAEZ
-Written by N. Lakmal Deshapriya
+PyAEZ version 2.1.0 (June 2023)
+Biomass Calculation
+2020: N. Lakmal Deshapriya
 """
 
 import numpy as np
-import numba as nb
 
 class BioMassCalc(object):
 
+    '''Max Radiation'''
+    Ac = np.array([[343,360,369,364,349,337,342,357,368,365,349,337],
+        [299,332,359,375,377,374,375,377,369,345,311,291],
+        [249,293,337,375,394,400,399,386,357,313,264,238],
+        [191,245,303,363,400,417,411,384,333,270,210,179],
+        [131,190,260,339,396,422,413,369,298,220,151,118],
+         [73,131,207,304,380,418,405,344,254,163, 92, 61],
+         [22, 72,149,260,356,408,389,309,201,103, 37, 14],
+          [0, 20, 89,209,331,408,380,269,142, 45,  2,  0],
+          [0,  0, 28,162,334,424,393,248, 81,  3,  0,  0],
+          [0,  0,  0,154,339,428,397,252, 40,  0,  0,  0]]);
+
+    '''Biomass in open day'''
+    bc = np.array([[413,424,429,426,417,410,413,422,429,427,418,410],
+        [376,401,422,437,440,440,440,439,431,411,385,370],
+        [334,371,407,439,460,468,465,451,425,387,348,325],
+        [281,333,385,437,471,489,483,456,412,356,299,269],
+        [218,283,353,427,480,506,497,455,390,314,241,204],
+        [147,223,310,409,484,522,509,488,358,260,173,130],
+         [66,151,254,383,487,544,523,436,316,195, 94, 49],
+          [0, 65,185,350,506,612,575,427,262,114,  7,  0],
+          [0,  0, 94,333,571,663,632,474,195, 11,  0,  0],
+          [0,  0,  0,371,588, 67,646,497,167,  0,  0,  0]]);
+
+    ''' Biomass in cloudy day '''
+    bo = np.array([[219,226,230,228,221,216,218,225,230,228,222,216],
+        [197,212,225,234,236,235,236,235,230,218,203,193],
+        [170,193,215,235,246,250,249,242,226,203,178,164],
+        [137,168,200,232,251,261,258,243,216,182,148,130],
+         [99,137,178,223,253,268,263,239,200,155,112, 91],
+         [60,100,150,207,251,273,265,230,178,121, 73, 51],
+         [19, 60,114,187,245,276,265,216,148, 82, 31, 11],
+          [0, 16, 74,158,241,291,273,200,112, 38,  1,  0],
+          [0,  0, 24,133,257,318,297,196, 69,  2,  0,  0],
+          [0,  0,  0,131,269,319,302,215, 35,  0,  0,  0]]);
+
+    '''Pm values table'''
+    PmIndexExtDtTemp = np.array([5,10,15,20,25,30,35]);
+    PmIndexExt = np.array([[0,15,20,20,  15, 5, 0],
+        [0, 0,15,32.5,35,35,35],
+        [0, 0, 5,45,65,65,65],
+        [0, 5,45,65, 65,65,65]]);
+
     def __init__(self, cycle_begin, cycle_end, latitude):
         self.cycle_begin = cycle_begin
         self.cycle_end = cycle_end
         self.cycle_len = cycle_end - cycle_begin + 1
 
         self.lat = np.abs(latitude)
         self.lat_index1 = np.floor(np.abs(latitude)/10);
@@ -61,137 +104,95 @@
                 self.dT_daily[i_count] = 0.1156+ 0.3476*self.minT_daily[i_count] + 0.6571*self.maxT_daily[i_count];
             else:
                 self.dT_daily[i_count] = -0.0617+ 0.3462*self.minT_daily[i_count] + 0.6649*self.maxT_daily[i_count];
 
             i_count = i_count + 1
 
     def setCropParameters(self, LAI, HI, legume, adaptability):
+        """Set the crop parameters
+
+        Args:
+            LAI (int): Leaf Area Index
+            HI (int): Harvest Index
+            legume (bool): _description_
+            adaptability (int): Crop adaptability class (1-4)
+        """        
         self.LAi = LAI # leaf area index
         self.HI = HI # harvest index
         self.legume = legume # binary value
         self.adaptability = adaptability-1  #one of [1,2,3,4] classes
 
-    @staticmethod
-    @nb.jit(nopython=True)
-    def calculateBioMassNumba(cycle_begin, cycle_end, cycle_len, lat, lat_index1, lat_index2, minT_daily, maxT_daily, shortRad_daily, meanT_daily, dT_daily, LAi, HI, legume, adaptability):
-
-        '''Max Radiation'''
-        Ac = np.array([[343,360,369,364,349,337,342,357,368,365,349,337],
-            [299,332,359,375,377,374,375,377,369,345,311,291],
-            [249,293,337,375,394,400,399,386,357,313,264,238],
-            [191,245,303,363,400,417,411,384,333,270,210,179],
-            [131,190,260,339,396,422,413,369,298,220,151,118],
-             [73,131,207,304,380,418,405,344,254,163, 92, 61],
-             [22, 72,149,260,356,408,389,309,201,103, 37, 14],
-              [0, 20, 89,209,331,408,380,269,142, 45,  2,  0],
-              [0,  0, 28,162,334,424,393,248, 81,  3,  0,  0],
-              [0,  0,  0,154,339,428,397,252, 40,  0,  0,  0]]);
-
-        '''Biomass in open day'''
-        bc = np.array([[413,424,429,426,417,410,413,422,429,427,418,410],
-            [376,401,422,437,440,440,440,439,431,411,385,370],
-            [334,371,407,439,460,468,465,451,425,387,348,325],
-            [281,333,385,437,471,489,483,456,412,356,299,269],
-            [218,283,353,427,480,506,497,455,390,314,241,204],
-            [147,223,310,409,484,522,509,488,358,260,173,130],
-             [66,151,254,383,487,544,523,436,316,195, 94, 49],
-              [0, 65,185,350,506,612,575,427,262,114,  7,  0],
-              [0,  0, 94,333,571,663,632,474,195, 11,  0,  0],
-              [0,  0,  0,371,588, 67,646,497,167,  0,  0,  0]]);
-
-        ''' Biomass in cloudy day '''
-        bo = np.array([[219,226,230,228,221,216,218,225,230,228,222,216],
-            [197,212,225,234,236,235,236,235,230,218,203,193],
-            [170,193,215,235,246,250,249,242,226,203,178,164],
-            [137,168,200,232,251,261,258,243,216,182,148,130],
-             [99,137,178,223,253,268,263,239,200,155,112, 91],
-             [60,100,150,207,251,273,265,230,178,121, 73, 51],
-             [19, 60,114,187,245,276,265,216,148, 82, 31, 11],
-              [0, 16, 74,158,241,291,273,200,112, 38,  1,  0],
-              [0,  0, 24,133,257,318,297,196, 69,  2,  0,  0],
-              [0,  0,  0,131,269,319,302,215, 35,  0,  0,  0]]);
-
-        '''Pm values table'''
-        PmIndexExtDtTemp = np.array([5.0,10.0,15.0,20.0,25.0,30.0,35.0]);
-        PmIndexExt = np.array([[0.0,15.0,20.0,20.0,  15.0, 5.0, 0.0],
-            [0.0, 0.0,15.0,32.5,35.0,35.0,35.0],
-            [0.0, 0.0, 5.0,45.0,65.0,65.0,65.0],
-            [0.0, 5.0,45.0,65.0, 65.0,65.0,65.0]]);
-
+    def calculateBioMass(self):
         ''' Calculate average values of Ac, bc, bo, meanT, dT  in the season '''
 
         doy_middle_of_month = np.arange(0,12)*30 + 15 # Calculate doy of middle of month
 
-        Ac_interp1 = np.interp(np.arange(cycle_begin, cycle_end+1), doy_middle_of_month, Ac[int(lat_index1),:])
-        bc_interp1 = np.interp(np.arange(cycle_begin, cycle_end+1), doy_middle_of_month, bc[int(lat_index1),:])
-        bo_interp1 = np.interp(np.arange(cycle_begin, cycle_end+1), doy_middle_of_month, bo[int(lat_index1),:])
-        Ac_interp2 = np.interp(np.arange(cycle_begin, cycle_end+1), doy_middle_of_month, Ac[int(lat_index2),:])
-        bc_interp2 = np.interp(np.arange(cycle_begin, cycle_end+1), doy_middle_of_month, bc[int(lat_index2),:])
-        bo_interp2 = np.interp(np.arange(cycle_begin, cycle_end+1), doy_middle_of_month, bo[int(lat_index2),:])
-
-        Ac_interp = Ac_interp1 + (int(lat)-int(lat_index1)*10)*((Ac_interp2-Ac_interp1)/10)
-        bc_interp = bc_interp1 + (int(lat)-int(lat_index1)*10)*((bc_interp2-bc_interp1)/10)
-        bo_interp = bo_interp1 + (int(lat)-int(lat_index1)*10)*((bo_interp2-bo_interp1)/10)
-
-        Ac_mean = np.mean( Ac_interp );
-        bc_mean = np.mean( bc_interp );
-        bo_mean = np.mean( bo_interp );
-
-        meanT_mean = np.mean( meanT_daily );
-        dT_mean = np.mean( dT_daily );
-        shortRad_mean = np.mean( shortRad_daily );
+        Ac_interp1 = np.interp(np.arange(self.cycle_begin, self.cycle_end+1), doy_middle_of_month, BioMassCalc.Ac[int(self.lat_index1),:])
+        bc_interp1 = np.interp(np.arange(self.cycle_begin, self.cycle_end+1), doy_middle_of_month, BioMassCalc.bc[int(self.lat_index1),:])
+        bo_interp1 = np.interp(np.arange(self.cycle_begin, self.cycle_end+1), doy_middle_of_month, BioMassCalc.bo[int(self.lat_index1),:])
+        Ac_interp2 = np.interp(np.arange(self.cycle_begin, self.cycle_end+1), doy_middle_of_month, BioMassCalc.Ac[int(self.lat_index2),:])
+        bc_interp2 = np.interp(np.arange(self.cycle_begin, self.cycle_end+1), doy_middle_of_month, BioMassCalc.bc[int(self.lat_index2),:])
+        bo_interp2 = np.interp(np.arange(self.cycle_begin, self.cycle_end+1), doy_middle_of_month, BioMassCalc.bo[int(self.lat_index2),:])
+
+        Ac_interp = Ac_interp1 + (int(self.lat)-int(self.lat_index1)*10)*((Ac_interp2-Ac_interp1)/10)
+        bc_interp = bc_interp1 + (int(self.lat)-int(self.lat_index1)*10)*((bc_interp2-bc_interp1)/10)
+        bo_interp = bo_interp1 + (int(self.lat)-int(self.lat_index1)*10)*((bo_interp2-bo_interp1)/10)
+
+        self.Ac_mean = np.mean( Ac_interp );
+        self.bc_mean = np.mean( bc_interp );
+        self.bo_mean = np.mean( bo_interp );
+
+        self.meanT_mean = np.mean( self.meanT_daily );
+        self.dT_mean = np.mean( self.dT_daily );
+        self.shortRad_mean = np.mean( self.shortRad_daily );
 
         '''the Fraction of the Daytime the Sky is Clouded'''
 
-        Rg = shortRad_mean;
-        f_day_clouded = (Ac_mean - (0.5 * Rg))/(0.8 * (Ac_mean));
+        Rg = self.shortRad_mean;
+        f_day_clouded = (self.Ac_mean - (0.5 * Rg))/(0.8 * (self.Ac_mean));
 
         '''Maximum net Rate of CO 2 Exchange of Leaves'''
 
-        PmIndexExt_1Row = PmIndexExt[adaptability,:];
-        iPm = np.interp(dT_mean,PmIndexExtDtTemp,PmIndexExt_1Row);
+        PmIndexExt_1Row = BioMassCalc.PmIndexExt[self.adaptability,:];
+        iPm = np.interp(self.dT_mean,BioMassCalc.PmIndexExtDtTemp,PmIndexExt_1Row);
 
         '''Adjust for Temperature and LAI'''
         # Calculate Ct
-        if legume == 1:
+        if self.legume == 1:
             c = 0.0283;
         else:
             c = 0.0108;
 
-        Ct = c*(0.0044 + 0.0019*meanT_mean + 0.0010*np.power(meanT_mean,2));
+        Ct = c*(0.0044 + 0.0019*self.meanT_mean + 0.0010*np.power(self.meanT_mean,2));
 
-        if(1 <= LAi and LAi < 2):
+        if(1 <= self.LAi and self.LAi < 2):
             l = 0.4;
-        elif(LAi < 3):
+        elif(self.LAi < 3):
             l = 0.6;
-        elif(LAi < 4):
+        elif(self.LAi < 4):
             l = 0.8;
-        elif(LAi < 5):
+        elif(self.LAi < 5):
             l = 0.9;
-        elif(5 <= LAi):
+        elif(5 <= self.LAi):
             l = 1;
         elif(LAi < 1):
             print("LAI too Low")
             return
 
         '''Maximum Rate of Gross Biomass Production'''
 
         if iPm > 20:
-            bgm = f_day_clouded * (.8 + 0.01 * iPm) * bo_mean + (1-f_day_clouded) * (.5 + .025 * iPm) * bc_mean;
+            bgm = f_day_clouded * (.8 + 0.01 * iPm) * self.bo_mean + (1-f_day_clouded) * (.5 + .025 * iPm) * self.bc_mean;
         elif iPm < 20:
-            bgm = f_day_clouded * (.5 + .025 * iPm) * bo_mean + (1-f_day_clouded) * (.05 * iPm) * bc_mean;
+            bgm = f_day_clouded * (.5 + .025 * iPm) * self.bo_mean + (1-f_day_clouded) * (.05 * iPm) * self.bc_mean;
         else:
-            bgm = f_day_clouded*bo_mean + (1 - f_day_clouded)*bc_mean;
+            bgm = f_day_clouded*self.bo_mean + (1 - f_day_clouded)*self.bc_mean;
 
         '''net biomass production '''
 
-        Bn = (0.36 * bgm * l) / ( (1/cycle_len) + 0.25*Ct );
+        self.Bn = (0.36 * bgm * l) / ( (1/self.cycle_len) + 0.25*Ct );
 
-        return Bn
-
-
-    def calculateBioMass(self):
-        self.Bn = BioMassCalc.calculateBioMassNumba(self.cycle_begin, self.cycle_end, self.cycle_len, self.lat, self.lat_index1, self.lat_index2, self.minT_daily, self.maxT_daily, self.shortRad_daily, self.meanT_daily, self.dT_daily, self.LAi, self.HI, self.legume, self.adaptability)
+        return self.Bn
 
     def calculateYield(self):
         self.PYield = self.Bn * self.HI;
         return self.PYield
```

### Comparing `PyAEZ-2.0.0/pyaez/ClimaticConstraints.py` & `PyAEZ-2.1.0/pyaez/TerrainConstraints.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,40 +1,59 @@
 """
-PyAEZ: Climate Constraints on the attainable crop yield
+PyAEZ version 2.1.0 (June 2023)
 2020: N. Lakmal Deshapriya
-2022: Swun Wunna Htet, K. Boonma
-
 """
 
 import numpy as np
 
-import ALL_REDUCTION_FACTORS_IRR as crop_P_IRR
-import ALL_REDUCTION_FACTORS_RAIN as crop_P_RAIN
+from pyaez import ALL_REDUCTION_FACTORS_IRR as crop_P_IRR
+from pyaez import ALL_REDUCTION_FACTORS_RAIN as crop_P_RAIN
+
+class TerrainConstraints(object):
+
+    def setClimateTerrainData(self, precipitation, slope):
+        self.prec_monthly = precipitation
+        self.slope = slope # Percentage Slope
+
+        self.im_height = slope.shape[0]
+        self.im_width = slope.shape[1]
+
+    def calculateFI(self):
+        # calculation of Fournier index
+
+        sum_Psquare = np.sum(np.square(self.prec_monthly), axis=2)
+        sum_P = np.sum(self.prec_monthly, axis=2)
 
-class ClimaticConstraints(object):
+        self.FI = 12 * (sum_Psquare / sum_P)
 
-    def applyClimaticConstraints(self, lgp_eq, yield_in, irr_or_rain):
+    def getFI(self):
+        # returning Fournier index
+
+        return self.FI
+
+    def applyTerrainConstraints(self, yield_in, irr_or_rain):
 
         if irr_or_rain == 'I':
             crop_P = crop_P_IRR
         elif irr_or_rain == 'R':
             crop_P = crop_P_RAIN
 
-        class_break = np.array(crop_P.lgp_eq_class)
-        reduction_fact = np.array(crop_P.lgp_eq_red_fr)
-
         yield_final = np.copy(yield_in)
-        lgp_eq = np.round(lgp_eq)
-        lgp_eq[np.isnan(lgp_eq)] = -99 # This suppresses warning with NaN values
 
-        '''min is replaced by product based on GAEZ doc, still keeping commented min code also just in case'''
-        # min_yield_fact = np.min(reduction_fact, axis=0) / 100
-        min_yield_fact = np.prod(reduction_fact/100, axis=0)
-
-        for class_num in range(class_break.shape[0]):
-            temp_idx = np.logical_and(class_break[class_num,0]<=lgp_eq, lgp_eq<=class_break[class_num,1])
-            yield_final[temp_idx] = yield_in[temp_idx] * min_yield_fact[class_num]
+        self.FI[np.isnan(self.FI)] = -99 # This suppresses warning with NaN values
+        self.slope[np.isnan(self.slope)] = -99 # This suppresses warning with NaN values
 
-        return yield_final
-    
+        FI_count = -1
+        for FI_cls1 in crop_P.FI_class:
+            FI_count = FI_count + 1
+
+            slope_count = -1
+            for slope_cls1 in crop_P.Slope_class:
+                slope_count = slope_count + 1
+
+                FI_idx = np.logical_and(FI_cls1[0]<=self.FI, self.FI<=FI_cls1[1])
+                slope_idx = np.logical_and(slope_cls1[0]<=self.slope, self.slope<=slope_cls1[1])
+                temp_idx = np.logical_and(FI_idx, slope_idx)
+
+                yield_final[temp_idx] = yield_in[temp_idx] * (crop_P.Terrain_factor[FI_count][slope_count] / 100)
 
-    
+        return yield_final
```

### Comparing `PyAEZ-2.0.0/pyaez/CropWatCalc.py` & `PyAEZ-2.1.0/pyaez/CropWatCalc.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,16 +1,15 @@
 """
-PyAEZ
-Written by N. Lakmal Deshapriya and Thaileng Thol
-
+PyAEZ version 2.1.0 (June 2023)
+Crop Water Calculation
+2020: N. Lakmal Deshapriya and Thaileng Thol
 Reference: http://oar.icrisat.org/198/1/316_2009_GTAE_55_Poten_obt_yield_in_SAT.pdf
 """
 
 import numpy as np
-import numba as nb
 
 class CropWatCalc(object):
 
     def __init__(self, cycle_begin, cycle_end):
         self.cycle_begin = cycle_begin
         self.cycle_end = cycle_end
         self.cycle_len = cycle_end - cycle_begin + 1
@@ -27,119 +26,115 @@
         self.yloss_f_all = yloss_f_all  # yield loss for entire growth cycle
         self.y_potential = est_yield  # potential yield
         self.D1 = D1  # rooting depth (m)
         self.D2 = D2  # rooting depth (m)
         self.Sa = Sa  # available soil moisture holding capacity (mm/m) , usually assume as 100
         self.pc = pc  # soil water depletion fraction below which ETa < ETo (from literature)
 
-    @staticmethod
-    @nb.jit(nopython=True)
-    def calculateMoistureLimitedYieldNumba(cycle_begin, cycle_end, cycle_len, peto, Prec, d_per, kc, kc_all, yloss_f, yloss_f_all, y_potential, D1, D2, Sa, pc):
+    def calculateMoistureLimitedYield(self):
+
         '''Convert Percentage of stage in the crop cycle to cumulative number of days'''
 
-        d_days = (cycle_len * (np.cumsum(d_per)/100)).astype(np.int_)
-        #d_days = np.round( cycle_len * (np.cumsum(d_per)/100) ).astype(np.int_)
+        d_days = np.round( self.cycle_len * (np.cumsum(self.d_per)/100) ).astype('int')
 
         '''Interpolate Rotting Depth (D)'''
-        D = np.zeros(peto.size)
-        D[d_days[1]:] = D2
-        D[:d_days[1]] = D1 + ((D2-D1)/(d_days[1])) * np.arange(d_days[1])
+        D = np.zeros(self.peto.size)
+        D[d_days[1]:] = self.D2
+        D[:d_days[1]] = self.D1 + ((self.D2-self.D1)/(d_days[1])) * np.arange(d_days[1])
 
         '''Lets calculate crop specific PET for each stage'''
 
-        petc_stage = np.zeros(peto.size)
-        petc_all = np.zeros(peto.size)
+        petc_stage = np.zeros(self.peto.size)
+        petc_all = np.zeros(self.peto.size)
 
-        for ii in range(cycle_len):
+        for ii in range(self.cycle_len):
 
             ## each growing stage
             if ii <= d_days[0]:
-                petc_stage[ii] = kc[0] * peto[ii]
+                petc_stage[ii] = self.kc[0] * self.peto[ii]
             elif ii <= d_days[1]:
-                kc_temp = kc[0] + (ii-d_days[0]) * ( (kc[1]-kc[0])/(d_days[1]-d_days[0]) )
-                petc_stage[ii] = kc_temp * peto[ii]
+                kc_temp = self.kc[0] + (ii-d_days[0]) * ( (self.kc[1]-self.kc[0])/(d_days[1]-d_days[0]) )
+                petc_stage[ii] = kc_temp * self.peto[ii]
             elif ii <= d_days[2]:
-                petc_stage[ii] = kc[1] * peto[ii]
+                petc_stage[ii] = self.kc[1] * self.peto[ii]
             else:
-                kc_temp = kc[1] + (ii-d_days[2]) * ( (kc[2]-kc[1])/(d_days[3]-d_days[2]) )
-                petc_stage[ii] = kc_temp * peto[ii]
+                kc_temp = self.kc[1] + (ii-d_days[2]) * ( (self.kc[2]-self.kc[1])/(d_days[3]-d_days[2]) )
+                petc_stage[ii] = kc_temp * self.peto[ii]
 
             ## entire gorwing season
-            petc_all[ii] = kc_all * peto[ii]
+            petc_all[ii] = self.kc_all * self.peto[ii]
+
 
         '''Lets calculate Actual ET for each stage'''
 
-        peta_stage = np.zeros(peto.size)
-        peta_all = np.zeros(peto.size)
+        peta_stage = np.zeros(self.peto.size)
+        peta_all = np.zeros(self.peto.size)
 
         ## each growing stage
-        W = Sa*D[0]
-        for ii in range(cycle_len):
+        W = self.Sa*D[0] 
+        for ii in range(self.cycle_len):
 
-            if Prec[ii] >= petc_stage[ii]:
+            if self.Prec[ii] >= petc_stage[ii]:
                 peta_stage[ii] = petc_stage[ii]
-            elif Prec[ii] + W >= Sa*D[ii]*(1-pc):
+            elif self.Prec[ii] + W >= self.Sa*D[ii]*(1-self.pc):
                 peta_stage[ii] = petc_stage[ii]
             else:
-                kk = (W+Prec[ii]) / (Sa*D[ii]*(1-pc))
+                kk = (W+self.Prec[ii]) / (self.Sa*D[ii]*(1-self.pc))
                 peta_stage[ii] = kk * petc_stage[ii]
 
-            W = np.min(np.array([W+Prec[ii]-peta_stage[ii], Sa*D[ii]]))
+            W = np.min([W+self.Prec[ii]-peta_stage[ii], self.Sa*D[ii]])
             if W<0: W=0
 
         ## entire gorwing season
-        W = Sa*D[0]
-        for ii in range(cycle_len):
+        W = self.Sa*D[0] 
+        for ii in range(self.cycle_len):
 
-            if Prec[ii] >= petc_all[ii]:
+            if self.Prec[ii] >= petc_all[ii]:
                 peta_all[ii] = petc_all[ii]
-            elif Prec[ii] + W >= Sa*D[ii]*(1-pc):
+            elif self.Prec[ii] + W >= self.Sa*D[ii]*(1-self.pc):
                 peta_all[ii] = petc_all[ii]
             else:
-                kk = (W+Prec[ii]) / (Sa*D[ii]*(1-pc))
+                kk = (W+self.Prec[ii]) / (self.Sa*D[ii]*(1-self.pc))
                 peta_all[ii] = kk * petc_all[ii]
 
-            W = np.min(np.array([W+Prec[ii]-peta_all[ii], Sa*D[ii]]))
+            W = np.min([W+self.Prec[ii]-peta_all[ii], self.Sa*D[ii]])
             if W<0: W=0
 
         '''Assess Yield Loss in entire growth cycle'''
 
         peta_all_sum = np.sum( peta_all )
         petc_all_sum = np.sum( petc_all )
 
-        f0 = 1 - yloss_f_all * ( 1 - (peta_all_sum/petc_all_sum) )
+        f0 = 1 - self.yloss_f_all * ( 1 - (peta_all_sum/petc_all_sum) )
 
         '''Assess Yield Loss in individual growth stages separately'''
 
         peta_d1 = np.sum( peta_stage[0:d_days[0]] )
         peta_d2 = np.sum( peta_stage[d_days[0]:d_days[1]] )
         peta_d3 = np.sum( peta_stage[d_days[1]:d_days[2]] )
         peta_d4 = np.sum( peta_stage[d_days[2]:d_days[3]] )
 
         petc_d1 = np.sum( petc_stage[0:d_days[0]] )
         petc_d2 = np.sum( petc_stage[d_days[0]:d_days[1]] )
         petc_d3 = np.sum( petc_stage[d_days[1]:d_days[2]] )
         petc_d4 = np.sum( petc_stage[d_days[2]:d_days[3]] )
 
-        f1_d1 = 1 - yloss_f[0] * ( 1 - (peta_d1/petc_d1) )
-        f1_d2 = 1 - yloss_f[1] * ( 1 - (peta_d2/petc_d2) )
-        f1_d3 = 1 - yloss_f[2] * ( 1 - (peta_d3/petc_d3) )
-        f1_d4 = 1 - yloss_f[3] * ( 1 - (peta_d4/petc_d4) )
+        f1_d1 = 1 - self.yloss_f[0] * ( 1 - (peta_d1/petc_d1) )
+        f1_d2 = 1 - self.yloss_f[1] * ( 1 - (peta_d2/petc_d2) )
+        f1_d3 = 1 - self.yloss_f[2] * ( 1 - (peta_d3/petc_d3) )
+        f1_d4 = 1 - self.yloss_f[3] * ( 1 - (peta_d4/petc_d4) )
 
-        f1 = np.min(np.array([f1_d1,f1_d2,f1_d3,f1_d4])) # some references use product, some use minimum. here we use minimum as in Thailand report
+        f1 = np.min([f1_d1,f1_d2,f1_d3,f1_d4]) # some references use product, some use minimum. here we use minimum as in Thailand report
 
         '''Use more severe of above two conditions determines final yield'''
 
-        f_final = np.min(np.array([f0,f1]))
+        f_final = np.min([f0,f1])
 
         # to avoid, possible error
         if f_final < 0:
             f_final = 0
         if f_final > 1:
             f_final = 1
 
-        y_water_limited = f_final * y_potential
+        y_water_limited = f_final * self.y_potential
 
         return y_water_limited
-
-    def calculateMoistureLimitedYield(self):
-        return CropWatCalc.calculateMoistureLimitedYieldNumba(self.cycle_begin, self.cycle_end, self.cycle_len, self.peto, self.Prec, self.d_per, self.kc, self.kc_all, self.yloss_f, self.yloss_f_all, self.y_potential, self.D1, self.D2, self.Sa, self.pc)
```

### Comparing `PyAEZ-2.0.0/pyaez/EconomicSuitability.py` & `PyAEZ-2.1.0/pyaez/EconomicSuitability.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 """
-PyAEZ: Economic Suitability
+PyAEZ version 2.1.0 (June 2023)
 2020: Thaileng Thol
+
 """
 
 import numpy as np
 from scipy import stats
 
 class EconomicSuitability(object):
 
@@ -74,15 +75,15 @@
         net_revenue_class[ np.all([net_revenue_75P<net_revenue], axis=0)] = 7 # very high
 
         return net_revenue_class
 
     def getNormalizedNetRevenue(self, crop_name):
 
         net_revenue = self.net_revenue_list[self.crop_name_list.index(crop_name)]
-        net_revenue_max = self.net_revenue_list[0].max()#np.max(np.array(self.net_revenue_list), axis=0)
+        net_revenue_max =  np.max(np.array(self.net_revenue_list), axis=0)
 
         net_revenue_norm = np.zeros(net_revenue.shape)
 
         net_revenue_norm[net_revenue_max>0] = np.divide(net_revenue[net_revenue_max>0], net_revenue_max[net_revenue_max>0])
 
         net_revenue_norm_class = np.zeros(net_revenue.shape)
```

### Comparing `PyAEZ-2.0.0/pyaez/SoilConstraints.py` & `PyAEZ-2.1.0/pyaez/SoilConstraints.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,17 +1,18 @@
 """
-PyAEZ: Biomass Calculation
+PyAEZ version 2.1.0 (June 2023)
+Biomass Calculation
 2020: N. Lakmal Deshapriya
 """
 
 import numpy as np
 import csv
 
-import ALL_REDUCTION_FACTORS_IRR as crop_P_IRR
-import ALL_REDUCTION_FACTORS_RAIN as crop_P_RAIN
+from pyaez import ALL_REDUCTION_FACTORS_IRR as crop_P_IRR
+from pyaez import ALL_REDUCTION_FACTORS_RAIN as crop_P_RAIN
 
 class SoilConstraints(object):
 
     '''functions for soil qualities'''
 
     def soil_qty_1_top(self, TXT_val, OC_val, pH_val, TEB_val):
```

### Comparing `PyAEZ-2.0.0/pyaez/UtilitiesCalc.py` & `PyAEZ-2.1.0/pyaez/UtilitiesCalc.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 """
-PyAEZ: Additional calculations used throughout AEZ modules
+PyAEZ version 2.1.0 (June 2023)
+Additional calculations used throughout AEZ modules
 2020: N. Lakmal Deshapriya
-2022: Swun Wunna Htet, K. Boonma
+2022/2023: Swun Wunna Htet, K. Boonma
 """
 
 import numpy as np
 from scipy.interpolate import interp1d
-#try:
-#import gdal
-#
-from osgeo import gdal
+try:
+    import gdal
+except:
+    from osgeo import gdal
 
 class UtilitiesCalc(object):
 
     def interpMonthlyToDaily(self, monthly_vector, cycle_begin, cycle_end, no_minus_values=False):
         """Interpolate monthly climate data to daily climate data
 
         Args:
@@ -107,15 +108,14 @@
         est_yield_class[ np.all([est_yield_20P<est_yield, est_yield<=est_yield_40P], axis=0) ] = 2 # marginally suitable
         est_yield_class[ np.all([est_yield_40P<est_yield, est_yield<=est_yield_60P], axis=0) ] = 3 # moderately suitable
         est_yield_class[ np.all([est_yield_60P<est_yield, est_yield<=est_yield_80P], axis=0) ] = 4 # suitable
         est_yield_class[ np.all([est_yield_80P<est_yield], axis=0)] = 5 # very suitable
 
         return est_yield_class
 
-
     def saveRaster(self, ref_raster_path, out_path, numpy_raster):
         """Save NumPy arrays/matrices to GeoTIFF files
 
         Args:
             ref_raster_path (string): File path to referece GeoTIFF for geo-tagged info.
             out_path (string): Path for the created GeoTIFF to be saved as/to
             numpy_raster (2D NumPy): the arrays to be saveda as GeoTIFF
```

### Comparing `PyAEZ-2.0.0/setup.py` & `PyAEZ-2.1.0/setup.py`

 * *Files identical despite different names*

