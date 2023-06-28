# Comparing `tmp/SESMG-0.5.0rc4.tar.gz` & `tmp/SESMG-0.5.0rc5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/SESMG-0.5.0rc4.tar", last modified: Wed Jun 28 09:40:00 2023, max compression
+gzip compressed data, was "dist/SESMG-0.5.0rc5.tar", last modified: Wed Jun 28 13:10:05 2023, max compression
```

## Comparing `SESMG-0.5.0rc4.tar` & `SESMG-0.5.0rc5.tar`

### file list

```diff
@@ -1,62 +1,62 @@
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.545503 SESMG-0.5.0rc4/
--rw-r--r--   0 gregor     (501) staff       (20)     7102 2023-06-28 09:40:00.545944 SESMG-0.5.0rc4/PKG-INFO
--rw-r--r--   0 gregor     (501) staff       (20)     5890 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/README.md
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.475642 SESMG-0.5.0rc4/SESMG.egg-info/
--rw-r--r--   0 gregor     (501) staff       (20)     7102 2023-06-28 09:40:00.000000 SESMG-0.5.0rc4/SESMG.egg-info/PKG-INFO
--rw-r--r--   0 gregor     (501) staff       (20)     2434 2023-06-28 09:40:00.000000 SESMG-0.5.0rc4/SESMG.egg-info/SOURCES.txt
--rw-r--r--   0 gregor     (501) staff       (20)        1 2023-06-28 09:40:00.000000 SESMG-0.5.0rc4/SESMG.egg-info/dependency_links.txt
--rw-r--r--   0 gregor     (501) staff       (20)      472 2023-06-28 09:40:00.000000 SESMG-0.5.0rc4/SESMG.egg-info/requires.txt
--rw-r--r--   0 gregor     (501) staff       (20)       14 2023-06-28 09:40:00.000000 SESMG-0.5.0rc4/SESMG.egg-info/top_level.txt
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.476101 SESMG-0.5.0rc4/program_files/
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.478534 SESMG-0.5.0rc4/program_files/GUI_st/
--rw-r--r--   0 gregor     (501) staff       (20)    28081 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/GUI_st/1_Main_Application.py
--rw-r--r--   0 gregor     (501) staff       (20)    13867 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/GUI_st/GUI_st_global_functions.py
--rw-r--r--   0 gregor     (501) staff       (20)       22 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/GUI_st/__init__.py
--rw-r--r--   0 gregor     (501) staff       (20)      294 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/__init__.py
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.486196 SESMG-0.5.0rc4/program_files/postprocessing/
--rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/postprocessing/__init__.py
--rw-r--r--   0 gregor     (501) staff       (20)    10445 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/postprocessing/create_results.py
--rw-r--r--   0 gregor     (501) staff       (20)    21873 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/postprocessing/create_results_collecting_data.py
--rw-r--r--   0 gregor     (501) staff       (20)    11578 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/postprocessing/create_results_prepare_data.py
--rw-r--r--   0 gregor     (501) staff       (20)     9063 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/postprocessing/plotting.py
--rw-r--r--   0 gregor     (501) staff       (20)    24138 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/postprocessing/plotting_elec_amounts.py
--rw-r--r--   0 gregor     (501) staff       (20)    17702 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/postprocessing/plotting_heat_amounts.py
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.495151 SESMG-0.5.0rc4/program_files/preprocessing/
--rw-r--r--   0 gregor     (501) staff       (20)    12768 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/Spreadsheet_Energy_System_Model_Generator.py
--rw-r--r--   0 gregor     (501) staff       (20)       30 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/__init__.py
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.515448 SESMG-0.5.0rc4/program_files/preprocessing/components/
--rwxr-xr-x   0 gregor     (501) staff       (20)     2779 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/Bus.py
--rw-r--r--   0 gregor     (501) staff       (20)     5217 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/Link.py
--rw-r--r--   0 gregor     (501) staff       (20)    20228 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/Sink.py
--rw-r--r--   0 gregor     (501) staff       (20)    22448 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/Source.py
--rw-r--r--   0 gregor     (501) staff       (20)     9470 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/Storage.py
--rw-r--r--   0 gregor     (501) staff       (20)    33502 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/Transformer.py
--rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/__init__.py
--rw-r--r--   0 gregor     (501) staff       (20)    46549 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/district_heating.py
--rw-r--r--   0 gregor     (501) staff       (20)    12347 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/district_heating_calculations.py
--rw-r--r--   0 gregor     (501) staff       (20)    21373 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/components/district_heating_clustering.py
--rwxr-xr-x   0 gregor     (501) staff       (20)     5544 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/create_energy_system.py
--rwxr-xr-x   0 gregor     (501) staff       (20)     5896 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/create_graph.py
--rw-r--r--   0 gregor     (501) staff       (20)    18110 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/data_preparation.py
--rw-r--r--   0 gregor     (501) staff       (20)     3930 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/import_weather_data.py
--rw-r--r--   0 gregor     (501) staff       (20)    14504 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/pareto_optimization.py
--rw-r--r--   0 gregor     (501) staff       (20)    23209 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/preprocessing/pre_model_analysis.py
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.517871 SESMG-0.5.0rc4/program_files/processing/
--rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/processing/__init__.py
--rwxr-xr-x   0 gregor     (501) staff       (20)    15791 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/processing/optimize_model.py
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.523818 SESMG-0.5.0rc4/program_files/urban_district_upscaling/
--rw-r--r--   0 gregor     (501) staff       (20)       26 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/__init__.py
--rw-r--r--   0 gregor     (501) staff       (20)    26293 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/clustering.py
-drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 09:40:00.544816 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/
--rw-r--r--   0 gregor     (501) staff       (20)    13011 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Bus.py
--rw-r--r--   0 gregor     (501) staff       (20)    26420 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Central_components.py
--rw-r--r--   0 gregor     (501) staff       (20)     4680 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Insulation.py
--rw-r--r--   0 gregor     (501) staff       (20)     9633 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Link.py
--rw-r--r--   0 gregor     (501) staff       (20)    19969 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Sink.py
--rw-r--r--   0 gregor     (501) staff       (20)    27358 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Source.py
--rw-r--r--   0 gregor     (501) staff       (20)    10959 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Storage.py
--rw-r--r--   0 gregor     (501) staff       (20)    21845 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Transformer.py
--rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/__init__.py
--rw-r--r--   0 gregor     (501) staff       (20)    25419 2023-06-27 21:50:10.000000 SESMG-0.5.0rc4/program_files/urban_district_upscaling/pre_processing.py
--rw-r--r--   0 gregor     (501) staff       (20)      691 2023-06-28 09:40:00.548365 SESMG-0.5.0rc4/setup.cfg
--rw-r--r--   0 gregor     (501) staff       (20)      935 2023-06-28 09:39:55.000000 SESMG-0.5.0rc4/setup.py
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.205756 SESMG-0.5.0rc5/
+-rw-r--r--   0 gregor     (501) staff       (20)     7102 2023-06-28 13:10:05.206024 SESMG-0.5.0rc5/PKG-INFO
+-rw-r--r--   0 gregor     (501) staff       (20)     5890 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/README.md
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.158800 SESMG-0.5.0rc5/SESMG.egg-info/
+-rw-r--r--   0 gregor     (501) staff       (20)     7102 2023-06-28 13:10:05.000000 SESMG-0.5.0rc5/SESMG.egg-info/PKG-INFO
+-rw-r--r--   0 gregor     (501) staff       (20)     2434 2023-06-28 13:10:05.000000 SESMG-0.5.0rc5/SESMG.egg-info/SOURCES.txt
+-rw-r--r--   0 gregor     (501) staff       (20)        1 2023-06-28 13:10:05.000000 SESMG-0.5.0rc5/SESMG.egg-info/dependency_links.txt
+-rw-r--r--   0 gregor     (501) staff       (20)      485 2023-06-28 13:10:05.000000 SESMG-0.5.0rc5/SESMG.egg-info/requires.txt
+-rw-r--r--   0 gregor     (501) staff       (20)       14 2023-06-28 13:10:05.000000 SESMG-0.5.0rc5/SESMG.egg-info/top_level.txt
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.159972 SESMG-0.5.0rc5/program_files/
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.162220 SESMG-0.5.0rc5/program_files/GUI_st/
+-rw-r--r--   0 gregor     (501) staff       (20)    28081 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/GUI_st/1_Main_Application.py
+-rw-r--r--   0 gregor     (501) staff       (20)    13867 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/GUI_st/GUI_st_global_functions.py
+-rw-r--r--   0 gregor     (501) staff       (20)       22 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/GUI_st/__init__.py
+-rw-r--r--   0 gregor     (501) staff       (20)      294 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/__init__.py
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.167337 SESMG-0.5.0rc5/program_files/postprocessing/
+-rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/postprocessing/__init__.py
+-rw-r--r--   0 gregor     (501) staff       (20)    10445 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/postprocessing/create_results.py
+-rw-r--r--   0 gregor     (501) staff       (20)    21873 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/postprocessing/create_results_collecting_data.py
+-rw-r--r--   0 gregor     (501) staff       (20)    11578 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/postprocessing/create_results_prepare_data.py
+-rw-r--r--   0 gregor     (501) staff       (20)     9063 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/postprocessing/plotting.py
+-rw-r--r--   0 gregor     (501) staff       (20)    24138 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/postprocessing/plotting_elec_amounts.py
+-rw-r--r--   0 gregor     (501) staff       (20)    17702 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/postprocessing/plotting_heat_amounts.py
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.172690 SESMG-0.5.0rc5/program_files/preprocessing/
+-rw-r--r--   0 gregor     (501) staff       (20)    12768 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/Spreadsheet_Energy_System_Model_Generator.py
+-rw-r--r--   0 gregor     (501) staff       (20)       30 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/__init__.py
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.185291 SESMG-0.5.0rc5/program_files/preprocessing/components/
+-rwxr-xr-x   0 gregor     (501) staff       (20)     2779 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/Bus.py
+-rw-r--r--   0 gregor     (501) staff       (20)     5217 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/Link.py
+-rw-r--r--   0 gregor     (501) staff       (20)    20228 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/Sink.py
+-rw-r--r--   0 gregor     (501) staff       (20)    22448 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/Source.py
+-rw-r--r--   0 gregor     (501) staff       (20)     9470 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/Storage.py
+-rw-r--r--   0 gregor     (501) staff       (20)    33502 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/Transformer.py
+-rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/__init__.py
+-rw-r--r--   0 gregor     (501) staff       (20)    46549 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/district_heating.py
+-rw-r--r--   0 gregor     (501) staff       (20)    12347 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/district_heating_calculations.py
+-rw-r--r--   0 gregor     (501) staff       (20)    21373 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/components/district_heating_clustering.py
+-rwxr-xr-x   0 gregor     (501) staff       (20)     5544 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/create_energy_system.py
+-rwxr-xr-x   0 gregor     (501) staff       (20)     5896 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/create_graph.py
+-rw-r--r--   0 gregor     (501) staff       (20)    18110 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/data_preparation.py
+-rw-r--r--   0 gregor     (501) staff       (20)     3930 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/import_weather_data.py
+-rw-r--r--   0 gregor     (501) staff       (20)    14504 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/pareto_optimization.py
+-rw-r--r--   0 gregor     (501) staff       (20)    23209 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/preprocessing/pre_model_analysis.py
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.186952 SESMG-0.5.0rc5/program_files/processing/
+-rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/processing/__init__.py
+-rwxr-xr-x   0 gregor     (501) staff       (20)    15791 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/processing/optimize_model.py
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.189973 SESMG-0.5.0rc5/program_files/urban_district_upscaling/
+-rw-r--r--   0 gregor     (501) staff       (20)       26 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/__init__.py
+-rw-r--r--   0 gregor     (501) staff       (20)    26293 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/clustering.py
+drwxr-xr-x   0 gregor     (501) staff       (20)        0 2023-06-28 13:10:05.205420 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/
+-rw-r--r--   0 gregor     (501) staff       (20)    13011 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Bus.py
+-rw-r--r--   0 gregor     (501) staff       (20)    26420 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Central_components.py
+-rw-r--r--   0 gregor     (501) staff       (20)     4680 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Insulation.py
+-rw-r--r--   0 gregor     (501) staff       (20)     9633 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Link.py
+-rw-r--r--   0 gregor     (501) staff       (20)    19969 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Sink.py
+-rw-r--r--   0 gregor     (501) staff       (20)    27358 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Source.py
+-rw-r--r--   0 gregor     (501) staff       (20)    10959 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Storage.py
+-rw-r--r--   0 gregor     (501) staff       (20)    21845 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Transformer.py
+-rw-r--r--   0 gregor     (501) staff       (20)        0 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/__init__.py
+-rw-r--r--   0 gregor     (501) staff       (20)    25419 2023-06-27 21:50:10.000000 SESMG-0.5.0rc5/program_files/urban_district_upscaling/pre_processing.py
+-rw-r--r--   0 gregor     (501) staff       (20)      706 2023-06-28 13:10:05.207292 SESMG-0.5.0rc5/setup.cfg
+-rw-r--r--   0 gregor     (501) staff       (20)      935 2023-06-28 13:10:00.000000 SESMG-0.5.0rc5/setup.py
```

### Comparing `SESMG-0.5.0rc4/PKG-INFO` & `SESMG-0.5.0rc5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: SESMG
-Version: 0.5.0rc4
+Version: 0.5.0rc5
 Summary: UNKNOWN
 Home-page: https://github.com/SESMG/SESMG
 Author: Christian Klemm
 Author-email: christian.klemm@fh-muenster.de
 License: GPL-3.0-only
 Description: # Spreadsheet Energy System Model Generator (SESMG) 
         [![Generic badge](https://img.shields.io/badge/content-what/why-darkgreen.svg)](https://spreadsheet-energy-system-model-generator.readthedocs.io/en/latest/#)
```

### Comparing `SESMG-0.5.0rc4/README.md` & `SESMG-0.5.0rc5/README.md`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/SESMG.egg-info/PKG-INFO` & `SESMG-0.5.0rc5/SESMG.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: SESMG
-Version: 0.5.0rc4
+Version: 0.5.0rc5
 Summary: UNKNOWN
 Home-page: https://github.com/SESMG/SESMG
 Author: Christian Klemm
 Author-email: christian.klemm@fh-muenster.de
 License: GPL-3.0-only
 Description: # Spreadsheet Energy System Model Generator (SESMG) 
         [![Generic badge](https://img.shields.io/badge/content-what/why-darkgreen.svg)](https://spreadsheet-energy-system-model-generator.readthedocs.io/en/latest/#)
```

### Comparing `SESMG-0.5.0rc4/SESMG.egg-info/SOURCES.txt` & `SESMG-0.5.0rc5/SESMG.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/GUI_st/1_Main_Application.py` & `SESMG-0.5.0rc5/program_files/GUI_st/1_Main_Application.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/GUI_st/GUI_st_global_functions.py` & `SESMG-0.5.0rc5/program_files/GUI_st/GUI_st_global_functions.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/postprocessing/create_results.py` & `SESMG-0.5.0rc5/program_files/postprocessing/create_results.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/postprocessing/create_results_collecting_data.py` & `SESMG-0.5.0rc5/program_files/postprocessing/create_results_collecting_data.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/postprocessing/create_results_prepare_data.py` & `SESMG-0.5.0rc5/program_files/postprocessing/create_results_prepare_data.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/postprocessing/plotting.py` & `SESMG-0.5.0rc5/program_files/postprocessing/plotting.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/postprocessing/plotting_elec_amounts.py` & `SESMG-0.5.0rc5/program_files/postprocessing/plotting_elec_amounts.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/postprocessing/plotting_heat_amounts.py` & `SESMG-0.5.0rc5/program_files/postprocessing/plotting_heat_amounts.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/Spreadsheet_Energy_System_Model_Generator.py` & `SESMG-0.5.0rc5/program_files/preprocessing/Spreadsheet_Energy_System_Model_Generator.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/Bus.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/Bus.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/Link.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/Link.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/Sink.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/Sink.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/Source.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/Source.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/Storage.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/Storage.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/Transformer.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/Transformer.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/district_heating.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/district_heating.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/district_heating_calculations.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/district_heating_calculations.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/components/district_heating_clustering.py` & `SESMG-0.5.0rc5/program_files/preprocessing/components/district_heating_clustering.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/create_energy_system.py` & `SESMG-0.5.0rc5/program_files/preprocessing/create_energy_system.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/create_graph.py` & `SESMG-0.5.0rc5/program_files/preprocessing/create_graph.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/data_preparation.py` & `SESMG-0.5.0rc5/program_files/preprocessing/data_preparation.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/import_weather_data.py` & `SESMG-0.5.0rc5/program_files/preprocessing/import_weather_data.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/pareto_optimization.py` & `SESMG-0.5.0rc5/program_files/preprocessing/pareto_optimization.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/preprocessing/pre_model_analysis.py` & `SESMG-0.5.0rc5/program_files/preprocessing/pre_model_analysis.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/processing/optimize_model.py` & `SESMG-0.5.0rc5/program_files/processing/optimize_model.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/clustering.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/clustering.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Bus.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Bus.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Central_components.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Central_components.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Insulation.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Insulation.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Link.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Link.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Sink.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Sink.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Source.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Source.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Storage.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Storage.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/components/Transformer.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/components/Transformer.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/program_files/urban_district_upscaling/pre_processing.py` & `SESMG-0.5.0rc5/program_files/urban_district_upscaling/pre_processing.py`

 * *Files identical despite different names*

### Comparing `SESMG-0.5.0rc4/setup.cfg` & `SESMG-0.5.0rc5/setup.cfg`

 * *Files 3% similar despite different names*

```diff
@@ -24,13 +24,14 @@
 	dhnx-fork-for-SESMG ==0.0.3.dev0
 	sympy >=1.10.0
 	xlsxwriter >=3.0.0
 	seaborn >=0.11.0
 	dash >=2.4.0
 	dash_canvas >=0.1.0
 	h5py ==3.6.0
+	pandas <2.0.0
 	pytest
 
 [egg_info]
 tag_build = 
 tag_date = 0
```

### Comparing `SESMG-0.5.0rc4/setup.py` & `SESMG-0.5.0rc5/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 #!/usr/bin/env python
 # -*- encoding: utf-8 -*-
 import setuptools
 import re
 
-__version__ = "0.5.0rc4"
+__version__ = "0.5.0rc5"
 with open("README.md", encoding="utf-8") as f:
     long_description = f.read()
 
 
 setuptools.setup(
     name="SESMG",
     version=__version__,
```

