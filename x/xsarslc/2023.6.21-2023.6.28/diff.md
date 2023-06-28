# Comparing `tmp/xsarslc-2023.6.21.tar.gz` & `tmp/xsarslc-2023.6.28.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "xsarslc-2023.6.21.tar", last modified: Wed Jun 21 14:07:42 2023, max compression
+gzip compressed data, was "xsarslc-2023.6.28.tar", last modified: Wed Jun 28 15:02:03 2023, max compression
```

## Comparing `xsarslc-2023.6.21.tar` & `xsarslc-2023.6.28.tar`

### file list

```diff
@@ -1,104 +1,104 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.182193 xsarslc-2023.6.21/
--rw-r--r--   0 runner    (1001) docker     (123)      348 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/.flake8
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.170193 xsarslc-2023.6.21/.github/
--rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.170193 xsarslc-2023.6.21/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)      829 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/.github/workflows/publish.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1799 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/.readthedocs.yml
--rw-r--r--   0 runner    (1001) docker     (123)    35149 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      757 2023-06-21 14:07:42.182193 xsarslc-2023.6.21/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      420 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/README.md
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.174193 xsarslc-2023.6.21/auxdata/
--rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_HH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_HV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50600 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_VH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50600 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_VV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW2_VH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW2_VV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_HH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_HV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_VH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_VV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_HH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_HV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50456 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_VH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50456 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_VV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_HH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_HV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50742 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_VH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50742 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_VV.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW3_VH.nc
--rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/auxdata/S1B_IRs_IW3_VV.nc
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.170193 xsarslc-2023.6.21/ci/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.174193 xsarslc-2023.6.21/ci/requirements/
--rw-r--r--   0 runner    (1001) docker     (123)      315 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/ci/requirements/docs.yaml
--rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/ci/requirements/environment.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.178193 xsarslc-2023.6.21/docs/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/.nojekyll
--rw-r--r--   0 runner    (1001) docker     (123)     1235 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/ATBD.rst
--rw-r--r--   0 runner    (1001) docker     (123)    14602 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/ATBD_L1BSLC.tex
--rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/Makefile
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.170193 xsarslc-2023.6.21/docs/_static/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.178193 xsarslc-2023.6.21/docs/_static/css/
--rw-r--r--   0 runner    (1001) docker     (123)      126 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/_static/css/xsarslc.css
--rw-r--r--   0 runner    (1001) docker     (123)      882 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/basic_api.rst
--rw-r--r--   0 runner    (1001) docker     (123)     3397 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)    10850 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/crossspectra.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1560 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/cutoff.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.178193 xsarslc-2023.6.21/docs/examples/
--rw-r--r--   0 runner    (1001) docker     (123)     8310 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/examples/L1B_Sentinel1_variables_explanation.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     4010 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/examples/default_impulseResponse_files_IW.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     8339 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/examples/example_IW_compute_and_correct_from_impulse_response.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    14548 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/examples/example_WV_compute_and_correct_from_impulse_response.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/examples/intro.py
--rw-r--r--   0 runner    (1001) docker     (123)     4620 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/examples/xspec_IW_intra_and_inter_burst.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     6686 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/examples/xspec_WV_example.ipynb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.178193 xsarslc-2023.6.21/docs/figures/
--rw-r--r--   0 runner    (1001) docker     (123)   422190 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/figures/NIRAN_NRCS_VH.png
--rw-r--r--   0 runner    (1001) docker     (123)   447722 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/figures/NIRAN_NRCS_vv.png
--rw-r--r--   0 runner    (1001) docker     (123)    75773 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/figures/S1_azimuth_IR_IW_VV.png
--rw-r--r--   0 runner    (1001) docker     (123)    31463 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/figures/S1_azimuth_IR_WV_VV.png
--rw-r--r--   0 runner    (1001) docker     (123)    97138 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/figures/S1_range_IR_IW_VV.png
--rw-r--r--   0 runner    (1001) docker     (123)    27568 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/figures/S1_range_IR_WV_VV.png
--rw-r--r--   0 runner    (1001) docker     (123)       93 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/figures/index
--rw-r--r--   0 runner    (1001) docker     (123)     3687 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/index.rst
--rw-r--r--   0 runner    (1001) docker     (123)      940 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/installing.rst
--rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/normalizedvariance.rst
--rw-r--r--   0 runner    (1001) docker     (123)    59687 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/oceanspectrumSAR.png
--rw-r--r--   0 runner    (1001) docker     (123)    15942 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/product_description.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2463 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/docs/sigma0.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1144 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      198 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/requirements_doc.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-21 14:07:42.182193 xsarslc-2023.6.21/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.182193 xsarslc-2023.6.21/xsarslc/
--rw-r--r--   0 runner    (1001) docker     (123)      324 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4505 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/burst.py
--rw-r--r--   0 runner    (1001) docker     (123)     2795 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/config.yml
--rw-r--r--   0 runner    (1001) docker     (123)     2356 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/get_config_infos.py
--rw-r--r--   0 runner    (1001) docker     (123)     2612 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/get_test_files.py
--rw-r--r--   0 runner    (1001) docker     (123)    12447 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/interface.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.182193 xsarslc-2023.6.21/xsarslc/processing/
--rw-r--r--   0 runner    (1001) docker     (123)    12974 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/processing/HR_tiles.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/processing/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6935 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/processing/deramping.py
--rw-r--r--   0 runner    (1001) docker     (123)    23045 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/processing/impulseResponse.py
--rw-r--r--   0 runner    (1001) docker     (123)    25197 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/processing/interburst.py
--rw-r--r--   0 runner    (1001) docker     (123)    32271 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/processing/intraburst.py
--rw-r--r--   0 runner    (1001) docker     (123)    33793 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/processing/xspectra.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.182193 xsarslc-2023.6.21/xsarslc/scripts/
--rw-r--r--   0 runner    (1001) docker     (123)    10241 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/scripts/L1B_xspectra_EW_SLC_IFR.py
--rw-r--r--   0 runner    (1001) docker     (123)    10523 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/scripts/L1B_xspectra_IW_SLC_IFR.py
--rw-r--r--   0 runner    (1001) docker     (123)     8839 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/scripts/L1B_xspectra_WV_SLC_IFR.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/scripts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20138 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/tools.py
--rw-r--r--   0 runner    (1001) docker     (123)     8946 2023-06-21 14:07:24.000000 xsarslc-2023.6.21/xsarslc/wallpaper.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-21 14:07:42.182193 xsarslc-2023.6.21/xsarslc.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      757 2023-06-21 14:07:42.000000 xsarslc-2023.6.21/xsarslc.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2388 2023-06-21 14:07:42.000000 xsarslc-2023.6.21/xsarslc.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-21 14:07:42.000000 xsarslc-2023.6.21/xsarslc.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      231 2023-06-21 14:07:42.000000 xsarslc-2023.6.21/xsarslc.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       75 2023-06-21 14:07:42.000000 xsarslc-2023.6.21/xsarslc.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-21 14:07:42.000000 xsarslc-2023.6.21/xsarslc.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.725112 xsarslc-2023.6.28/
+-rw-r--r--   0 runner    (1001) docker     (123)      348 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/.flake8
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.689111 xsarslc-2023.6.28/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.689111 xsarslc-2023.6.28/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)      829 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/.github/workflows/publish.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1799 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/.readthedocs.yml
+-rw-r--r--   0 runner    (1001) docker     (123)    35149 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-28 15:02:03.725112 xsarslc-2023.6.28/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      500 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.697111 xsarslc-2023.6.28/auxdata/
+-rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_HH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_HV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50600 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_VH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50600 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_VV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW2_VH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW2_VV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_HH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50450 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_HV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_VH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_VV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:30.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_HH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_HV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50456 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_VH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50456 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_VV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_HH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_HV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50742 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_VH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50742 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_VV.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW3_VH.nc
+-rw-r--r--   0 runner    (1001) docker     (123)    50314 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/auxdata/S1B_IRs_IW3_VV.nc
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.681111 xsarslc-2023.6.28/ci/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.697111 xsarslc-2023.6.28/ci/requirements/
+-rw-r--r--   0 runner    (1001) docker     (123)      315 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/ci/requirements/docs.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/ci/requirements/environment.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.705111 xsarslc-2023.6.28/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/.nojekyll
+-rw-r--r--   0 runner    (1001) docker     (123)     1235 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/ATBD.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    14602 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/ATBD_L1BSLC.tex
+-rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/Makefile
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.681111 xsarslc-2023.6.28/docs/_static/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.705111 xsarslc-2023.6.28/docs/_static/css/
+-rw-r--r--   0 runner    (1001) docker     (123)      126 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/_static/css/xsarslc.css
+-rw-r--r--   0 runner    (1001) docker     (123)      882 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/basic_api.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     3397 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10850 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/crossspectra.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1560 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/cutoff.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.709111 xsarslc-2023.6.28/docs/examples/
+-rw-r--r--   0 runner    (1001) docker     (123)     8310 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/examples/L1B_Sentinel1_variables_explanation.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     4010 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/examples/default_impulseResponse_files_IW.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     8339 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/examples/example_IW_compute_and_correct_from_impulse_response.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    14548 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/examples/example_WV_compute_and_correct_from_impulse_response.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/examples/intro.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4620 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/examples/xspec_IW_intra_and_inter_burst.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     6686 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/examples/xspec_WV_example.ipynb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.713111 xsarslc-2023.6.28/docs/figures/
+-rw-r--r--   0 runner    (1001) docker     (123)   422190 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/figures/NIRAN_NRCS_VH.png
+-rw-r--r--   0 runner    (1001) docker     (123)   447722 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/figures/NIRAN_NRCS_vv.png
+-rw-r--r--   0 runner    (1001) docker     (123)    75773 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/figures/S1_azimuth_IR_IW_VV.png
+-rw-r--r--   0 runner    (1001) docker     (123)    31463 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/figures/S1_azimuth_IR_WV_VV.png
+-rw-r--r--   0 runner    (1001) docker     (123)    97138 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/figures/S1_range_IR_IW_VV.png
+-rw-r--r--   0 runner    (1001) docker     (123)    27568 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/figures/S1_range_IR_WV_VV.png
+-rw-r--r--   0 runner    (1001) docker     (123)       93 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/figures/index
+-rw-r--r--   0 runner    (1001) docker     (123)     3687 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/index.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      940 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/installing.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      624 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/normalizedvariance.rst
+-rw-r--r--   0 runner    (1001) docker     (123)    59687 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/oceanspectrumSAR.png
+-rw-r--r--   0 runner    (1001) docker     (123)    15942 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/product_description.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2463 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/docs/sigma0.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1144 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      198 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/requirements_doc.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:02:03.725112 xsarslc-2023.6.28/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.717111 xsarslc-2023.6.28/xsarslc/
+-rw-r--r--   0 runner    (1001) docker     (123)      324 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4505 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/burst.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2795 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/config.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     2356 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/get_config_infos.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2612 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/get_test_files.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12478 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/interface.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.721111 xsarslc-2023.6.28/xsarslc/processing/
+-rw-r--r--   0 runner    (1001) docker     (123)    12974 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/processing/HR_tiles.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/processing/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6935 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/processing/deramping.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23045 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/processing/impulseResponse.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25197 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/processing/interburst.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32305 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/processing/intraburst.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33793 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/processing/xspectra.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.725112 xsarslc-2023.6.28/xsarslc/scripts/
+-rw-r--r--   0 runner    (1001) docker     (123)    10241 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/scripts/L1B_xspectra_EW_SLC_IFR.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10523 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/scripts/L1B_xspectra_IW_SLC_IFR.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8839 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/scripts/L1B_xspectra_WV_SLC_IFR.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/scripts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20138 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8946 2023-06-28 15:01:31.000000 xsarslc-2023.6.28/xsarslc/wallpaper.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:02:03.717111 xsarslc-2023.6.28/xsarslc.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-28 15:02:03.000000 xsarslc-2023.6.28/xsarslc.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2388 2023-06-28 15:02:03.000000 xsarslc-2023.6.28/xsarslc.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:02:03.000000 xsarslc-2023.6.28/xsarslc.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      231 2023-06-28 15:02:03.000000 xsarslc-2023.6.28/xsarslc.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       75 2023-06-28 15:02:03.000000 xsarslc-2023.6.28/xsarslc.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-28 15:02:03.000000 xsarslc-2023.6.28/xsarslc.egg-info/top_level.txt
```

### Comparing `xsarslc-2023.6.21/.github/workflows/publish.yml` & `xsarslc-2023.6.28/.github/workflows/publish.yml`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/.gitignore` & `xsarslc-2023.6.28/.gitignore`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/.pre-commit-config.yaml` & `xsarslc-2023.6.28/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/LICENSE` & `xsarslc-2023.6.28/LICENSE`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/PKG-INFO` & `xsarslc-2023.6.28/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,21 +1,22 @@
 Metadata-Version: 2.1
 Name: xsarslc
-Version: 2023.6.21
+Version: 2023.6.28
 Summary: Python library to compute cross spectra from SAR image
 Author: Frederic Nouguier
 License: GPL-3.0
 Keywords: SAR,wave,reseach,cross-spectra
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
-xsarslc
+# xsarslc
 
+![Anaconda-Server Badge](https://img.shields.io/conda/vn/conda-forge/xsarslc)
 
 Functions for Sentinel-1 SLC products 
 
 the main feature of this library is the SAR processor:
 
 
 ```mermaid
```

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_HH.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_HH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_HV.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_HV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_VH.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_VH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW1_VV.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW1_VV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW2_VH.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW2_VH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW2_VV.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW2_VV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_HH.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_HH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_HV.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_HV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_VH.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_VH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1A_IRs_IW3_VV.nc` & `xsarslc-2023.6.28/auxdata/S1A_IRs_IW3_VV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_HH.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_HH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_HV.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_HV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_VH.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_VH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW1_VV.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW1_VV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_HH.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_HH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_HV.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_HV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_VH.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_VH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW2_VV.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW2_VV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW3_VH.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW3_VH.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/auxdata/S1B_IRs_IW3_VV.nc` & `xsarslc-2023.6.28/auxdata/S1B_IRs_IW3_VV.nc`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/ATBD.rst` & `xsarslc-2023.6.28/docs/ATBD.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/ATBD_L1BSLC.tex` & `xsarslc-2023.6.28/docs/ATBD_L1BSLC.tex`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/Makefile` & `xsarslc-2023.6.28/docs/Makefile`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/basic_api.rst` & `xsarslc-2023.6.28/docs/basic_api.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/conf.py` & `xsarslc-2023.6.28/docs/conf.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/crossspectra.rst` & `xsarslc-2023.6.28/docs/crossspectra.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/cutoff.rst` & `xsarslc-2023.6.28/docs/cutoff.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/examples/L1B_Sentinel1_variables_explanation.ipynb` & `xsarslc-2023.6.28/docs/examples/L1B_Sentinel1_variables_explanation.ipynb`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/examples/default_impulseResponse_files_IW.ipynb` & `xsarslc-2023.6.28/docs/examples/default_impulseResponse_files_IW.ipynb`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/examples/example_IW_compute_and_correct_from_impulse_response.ipynb` & `xsarslc-2023.6.28/docs/examples/example_IW_compute_and_correct_from_impulse_response.ipynb`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/examples/example_WV_compute_and_correct_from_impulse_response.ipynb` & `xsarslc-2023.6.28/docs/examples/example_WV_compute_and_correct_from_impulse_response.ipynb`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/examples/xspec_IW_intra_and_inter_burst.ipynb` & `xsarslc-2023.6.28/docs/examples/xspec_IW_intra_and_inter_burst.ipynb`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/examples/xspec_WV_example.ipynb` & `xsarslc-2023.6.28/docs/examples/xspec_WV_example.ipynb`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/figures/NIRAN_NRCS_VH.png` & `xsarslc-2023.6.28/docs/figures/NIRAN_NRCS_VH.png`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/figures/NIRAN_NRCS_vv.png` & `xsarslc-2023.6.28/docs/figures/NIRAN_NRCS_vv.png`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/figures/S1_azimuth_IR_IW_VV.png` & `xsarslc-2023.6.28/docs/figures/S1_azimuth_IR_IW_VV.png`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/figures/S1_azimuth_IR_WV_VV.png` & `xsarslc-2023.6.28/docs/figures/S1_azimuth_IR_WV_VV.png`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/figures/S1_range_IR_IW_VV.png` & `xsarslc-2023.6.28/docs/figures/S1_range_IR_IW_VV.png`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/figures/S1_range_IR_WV_VV.png` & `xsarslc-2023.6.28/docs/figures/S1_range_IR_WV_VV.png`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/index.rst` & `xsarslc-2023.6.28/docs/index.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/installing.rst` & `xsarslc-2023.6.28/docs/installing.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/normalizedvariance.rst` & `xsarslc-2023.6.28/docs/normalizedvariance.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/oceanspectrumSAR.png` & `xsarslc-2023.6.28/docs/oceanspectrumSAR.png`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/product_description.rst` & `xsarslc-2023.6.28/docs/product_description.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/docs/sigma0.rst` & `xsarslc-2023.6.28/docs/sigma0.rst`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/pyproject.toml` & `xsarslc-2023.6.28/pyproject.toml`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/burst.py` & `xsarslc-2023.6.28/xsarslc/burst.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/config.yml` & `xsarslc-2023.6.28/xsarslc/config.yml`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/get_config_infos.py` & `xsarslc-2023.6.28/xsarslc/get_config_infos.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/get_test_files.py` & `xsarslc-2023.6.28/xsarslc/get_test_files.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/interface.py` & `xsarslc-2023.6.28/xsarslc/interface.py`

 * *Files 0% similar despite different names*

```diff
@@ -31,15 +31,16 @@
     for mytile in tiles:
         mytile.load()
         if not mytile['land_flag']:
             incidence = mytile['incidence']
             spacing = {'sample':mytile['sampleSpacing']/np.sin(np.radians(incidence)), 'line':mytile['lineSpacing']}
             low_res_tiles.append(compute_low_res_tiles(mytile, spacing = spacing, posting = posting, tile_width=tile_width, window=window, **kwargs))
     res = xr.combine_by_coords([t.expand_dims(['burst', 'tile_sample', 'tile_line']) for t in low_res_tiles])
-    res['land_flag'] = res['land_flag'].fillna(1).astype(bool)
+    if 'land_flag' in res:
+        res['land_flag'] = res['land_flag'].fillna(1).astype(bool)
     attrs = L1B.attrs.copy()
     attr_to_rm = ['comment','azimuth_time_interval','periodo_width_sample','periodo_width_line','periodo_overlap_sample','periodo_overlap_line']
     [attrs.pop(k,None) for k in attr_to_rm]
     res.attrs.update(attrs)
     return res
 
 def compute_low_res_tiles(tile, spacing, posting, tile_width, resolution=None, window = 'GAUSSIAN'):
```

### Comparing `xsarslc-2023.6.21/xsarslc/processing/HR_tiles.py` & `xsarslc-2023.6.28/xsarslc/processing/HR_tiles.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/processing/deramping.py` & `xsarslc-2023.6.28/xsarslc/processing/deramping.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/processing/impulseResponse.py` & `xsarslc-2023.6.28/xsarslc/processing/impulseResponse.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/processing/interburst.py` & `xsarslc-2023.6.28/xsarslc/processing/interburst.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/processing/intraburst.py` & `xsarslc-2023.6.28/xsarslc/processing/intraburst.py`

 * *Files 0% similar despite different names*

```diff
@@ -441,15 +441,15 @@
     if 'IR' not in kwargs: # No Impulse Response has been provided
         mydop = xrft.fft(slc*np.exp(-1j*2*np.pi*centroid*slc[azimuth_dim]), dim=[azimuth_dim], detrend=None,
                          window=None, shift=True, true_phase=True, true_amplitude=True)
     else: # Provided IR is used to normalize slc spectra
         mydop = xrft.fft(slc*np.exp(-1j*2*np.pi*centroid*slc[azimuth_dim]), dim=[azimuth_dim, range_dim],
                          detrend=None, window=None, shift=True, true_phase=True, true_amplitude=True)
         mydop = (mydop/kwargs.get('IR')).fillna(0.)
-        mydop = xrft.ifft(mydop, dim='freq_'+range_dim, true_phase=True, true_amplitude=True)
+        mydop = xrft.ifft(mydop, dim='freq_'+range_dim, true_phase=True, true_amplitude=True) # IFFT IS DONE IN RANGE ONLY HERE
         mydop = mydop.drop(['k_az', 'k_srg'])
 
     # Extracting the useful part of azimuthal Doppler spectrum
     # It removes points on each side to be sure that tiling will operate correctly
     Nused = nlooks * nperlook - (nlooks - 1) * noverlap
     left = (Np - Nused) // 2  # useless points on left side
     mydop = mydop[{freq_azi_dim: slice(left, left + Nused)}]
```

### Comparing `xsarslc-2023.6.21/xsarslc/processing/xspectra.py` & `xsarslc-2023.6.28/xsarslc/processing/xspectra.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/scripts/L1B_xspectra_EW_SLC_IFR.py` & `xsarslc-2023.6.28/xsarslc/scripts/L1B_xspectra_EW_SLC_IFR.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/scripts/L1B_xspectra_IW_SLC_IFR.py` & `xsarslc-2023.6.28/xsarslc/scripts/L1B_xspectra_IW_SLC_IFR.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/scripts/L1B_xspectra_WV_SLC_IFR.py` & `xsarslc-2023.6.28/xsarslc/scripts/L1B_xspectra_WV_SLC_IFR.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/tools.py` & `xsarslc-2023.6.28/xsarslc/tools.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc/wallpaper.py` & `xsarslc-2023.6.28/xsarslc/wallpaper.py`

 * *Files identical despite different names*

### Comparing `xsarslc-2023.6.21/xsarslc.egg-info/PKG-INFO` & `xsarslc-2023.6.28/xsarslc.egg-info/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,21 +1,22 @@
 Metadata-Version: 2.1
 Name: xsarslc
-Version: 2023.6.21
+Version: 2023.6.28
 Summary: Python library to compute cross spectra from SAR image
 Author: Frederic Nouguier
 License: GPL-3.0
 Keywords: SAR,wave,reseach,cross-spectra
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
-xsarslc
+# xsarslc
 
+![Anaconda-Server Badge](https://img.shields.io/conda/vn/conda-forge/xsarslc)
 
 Functions for Sentinel-1 SLC products 
 
 the main feature of this library is the SAR processor:
 
 
 ```mermaid
```

### Comparing `xsarslc-2023.6.21/xsarslc.egg-info/SOURCES.txt` & `xsarslc-2023.6.28/xsarslc.egg-info/SOURCES.txt`

 * *Files identical despite different names*

