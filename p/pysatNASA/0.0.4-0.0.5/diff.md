# Comparing `tmp/pysatNASA-0.0.4.tar.gz` & `tmp/pysatNASA-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pysatNASA-0.0.4.tar", last modified: Mon Nov  7 21:07:01 2022, max compression
+gzip compressed data, was "pysatNASA-0.0.5.tar", last modified: Tue Jun 27 22:11:11 2023, max compression
```

## Comparing `pysatNASA-0.0.4.tar` & `pysatNASA-0.0.5.tar`

### file list

```diff
@@ -1,57 +1,70 @@
-drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2022-11-07 21:07:01.024710 pysatNASA-0.0.4/
--rw-r--r--   0 jklenzin   (502) staff       (20)     2741 2022-11-07 21:03:49.000000 pysatNASA-0.0.4/CHANGELOG.md
--rw-r--r--   0 jklenzin   (502) staff       (20)     3234 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/CODE_OF_CONDUCT.md
--rw-r--r--   0 jklenzin   (502) staff       (20)     5861 2022-11-07 17:36:41.000000 pysatNASA-0.0.4/CONTRIBUTING.md
--rw-r--r--   0 jklenzin   (502) staff       (20)     1513 2020-08-14 21:00:53.000000 pysatNASA-0.0.4/LICENSE
--rw-r--r--   0 jklenzin   (502) staff       (20)      225 2020-08-14 21:00:53.000000 pysatNASA-0.0.4/MANIFEST.in
--rw-r--r--   0 jklenzin   (502) staff       (20)     3583 2022-11-07 21:07:01.024862 pysatNASA-0.0.4/PKG-INFO
--rw-r--r--   0 jklenzin   (502) staff       (20)     2690 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/README.md
-drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2022-11-07 21:07:01.010226 pysatNASA-0.0.4/pysatNASA/
--rw-r--r--   0 jklenzin   (502) staff       (20)      562 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/__init__.py
-drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2022-11-07 21:07:01.013291 pysatNASA-0.0.4/pysatNASA/constellations/
--rw-r--r--   0 jklenzin   (502) staff       (20)      657 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/constellations/__init__.py
--rw-r--r--   0 jklenzin   (502) staff       (20)      388 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/constellations/de2.py
--rw-r--r--   0 jklenzin   (502) staff       (20)      670 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/constellations/icon.py
-drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2022-11-07 21:07:01.019985 pysatNASA-0.0.4/pysatNASA/instruments/
--rw-r--r--   0 jklenzin   (502) staff       (20)      568 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/__init__.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     9871 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/cnofs_ivm.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     3963 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/cnofs_plp.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     4198 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/cnofs_vefi.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     3721 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/de2_lang.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     5565 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/de2_nacs.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     4506 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/de2_rpa.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     5375 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/de2_wats.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     3269 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/formosat1_ivm.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     7163 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/icon_euv.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     7075 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/icon_fuv.py
--rw-r--r--   0 jklenzin   (502) staff       (20)    10184 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/icon_ivm.py
--rw-r--r--   0 jklenzin   (502) staff       (20)    13281 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/icon_mighti.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     3779 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/instruments/iss_fpmu.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     3558 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/jpl_gps.py
-drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2022-11-07 21:07:01.024117 pysatNASA-0.0.4/pysatNASA/instruments/methods/
--rw-r--r--   0 jklenzin   (502) staff       (20)      471 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/__init__.py
--rw-r--r--   0 jklenzin   (502) staff       (20)    16730 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/_cdf.py
--rw-r--r--   0 jklenzin   (502) staff       (20)    25751 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/cdaweb.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     1579 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/cnofs.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     1435 2022-11-07 18:55:58.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/de2.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     1171 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/general.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     1601 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/gold.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     1519 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/gps.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     7541 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/icon.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     7218 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/methods/omni.py
--rw-r--r--   0 jklenzin   (502) staff       (20)    11918 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/omni_hro.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     7135 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/ses14_gold.py
-drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2022-11-07 21:07:01.024432 pysatNASA-0.0.4/pysatNASA/instruments/templates/
--rw-r--r--   0 jklenzin   (502) staff       (20)     6899 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/pysatNASA/instruments/templates/template_cdaweb_instrument.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     4017 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/timed_saber.py
--rw-r--r--   0 jklenzin   (502) staff       (20)     3602 2022-11-07 21:03:35.000000 pysatNASA-0.0.4/pysatNASA/instruments/timed_see.py
--rw-r--r--   0 jklenzin   (502) staff       (20)        6 2022-11-07 21:03:42.000000 pysatNASA-0.0.4/pysatNASA/version.txt
-drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2022-11-07 21:07:01.012063 pysatNASA-0.0.4/pysatNASA.egg-info/
--rw-r--r--   0 jklenzin   (502) staff       (20)     3583 2022-11-07 21:07:00.000000 pysatNASA-0.0.4/pysatNASA.egg-info/PKG-INFO
--rw-r--r--   0 jklenzin   (502) staff       (20)     1550 2022-11-07 21:07:01.000000 pysatNASA-0.0.4/pysatNASA.egg-info/SOURCES.txt
--rw-r--r--   0 jklenzin   (502) staff       (20)        1 2022-11-07 21:07:00.000000 pysatNASA-0.0.4/pysatNASA.egg-info/dependency_links.txt
--rw-r--r--   0 jklenzin   (502) staff       (20)        1 2022-10-27 15:28:02.000000 pysatNASA-0.0.4/pysatNASA.egg-info/not-zip-safe
--rw-r--r--   0 jklenzin   (502) staff       (20)       86 2022-11-07 21:07:00.000000 pysatNASA-0.0.4/pysatNASA.egg-info/requires.txt
--rw-r--r--   0 jklenzin   (502) staff       (20)       10 2022-11-07 21:07:00.000000 pysatNASA-0.0.4/pysatNASA.egg-info/top_level.txt
--rw-r--r--   0 jklenzin   (502) staff       (20)     1527 2022-11-07 21:07:01.025633 pysatNASA-0.0.4/setup.cfg
--rw-r--r--   0 jklenzin   (502) staff       (20)      350 2022-11-07 17:36:42.000000 pysatNASA-0.0.4/setup.py
+drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2023-06-27 22:11:11.666201 pysatNASA-0.0.5/
+-rw-r--r--   0 jklenzin   (502) staff       (20)     5474 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/CHANGELOG.md
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3234 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/CODE_OF_CONDUCT.md
+-rw-r--r--   0 jklenzin   (502) staff       (20)     6268 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/CONTRIBUTING.md
+-rw-r--r--   0 jklenzin   (502) staff       (20)     1513 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/LICENSE
+-rw-r--r--   0 jklenzin   (502) staff       (20)      225 2021-12-28 00:53:27.000000 pysatNASA-0.0.5/MANIFEST.in
+-rw-r--r--   0 jklenzin   (502) staff       (20)     6630 2023-06-27 22:11:11.666509 pysatNASA-0.0.5/PKG-INFO
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3603 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/README.md
+-rw-r--r--   0 jklenzin   (502) staff       (20)     1931 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pyproject.toml
+drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2023-06-27 22:11:11.577057 pysatNASA-0.0.5/pysatNASA/
+-rw-r--r--   0 jklenzin   (502) staff       (20)      546 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/__init__.py
+drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2023-06-27 22:11:11.589404 pysatNASA-0.0.5/pysatNASA/constellations/
+-rw-r--r--   0 jklenzin   (502) staff       (20)      657 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/constellations/__init__.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)      717 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/constellations/de2.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     1154 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/constellations/icon.py
+drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2023-06-27 22:11:11.653842 pysatNASA-0.0.5/pysatNASA/instruments/
+-rw-r--r--   0 jklenzin   (502) staff       (20)      756 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/__init__.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3215 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/ace_epam_l2.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     4537 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/ace_mag_l2.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     2965 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/ace_sis_l2.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3179 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/ace_swepam_l2.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     9764 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/cnofs_ivm.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3549 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/cnofs_plp.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     4122 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/cnofs_vefi.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3755 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/de2_fpi.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3580 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/de2_lang.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     5421 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/de2_nacs.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     4124 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/de2_rpa.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3221 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/de2_vefi.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     5231 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/de2_wats.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     4655 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/dmsp_ssusi.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3087 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/formosat1_ivm.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     7224 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/icon_euv.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     7050 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/icon_fuv.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)    10161 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/icon_ivm.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)    13202 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/icon_mighti.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     4905 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/igs_gps.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3261 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/iss_fpmu.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3841 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/jpl_gps.py
+drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2023-06-27 22:11:11.663724 pysatNASA-0.0.5/pysatNASA/instruments/methods/
+-rw-r--r--   0 jklenzin   (502) staff       (20)      774 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/__init__.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)    17674 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/_cdf.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     4145 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/ace.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)    36243 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/cdaweb.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     1579 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/cnofs.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     2236 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/de2.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)      988 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/dmsp.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     2194 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/general.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     1662 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/gps.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     7541 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/icon.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3087 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/igs.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)    13856 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/jhuapl.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     7335 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/omni.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     1640 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/ses14.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     2068 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/methods/timed.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)    10460 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/omni_hro.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)    11404 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/ses14_gold.py
+drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2023-06-27 22:11:11.665022 pysatNASA-0.0.5/pysatNASA/instruments/templates/
+-rw-r--r--   0 jklenzin   (502) staff       (20)     6899 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/templates/template_cdaweb_instrument.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     7346 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/timed_guvi.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     3971 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/timed_saber.py
+-rw-r--r--   0 jklenzin   (502) staff       (20)     2492 2023-06-27 22:10:58.000000 pysatNASA-0.0.5/pysatNASA/instruments/timed_see.py
+drwxr-xr-x   0 jklenzin   (502) staff       (20)        0 2023-06-27 22:11:11.580683 pysatNASA-0.0.5/pysatNASA.egg-info/
+-rw-r--r--   0 jklenzin   (502) staff       (20)     6630 2023-06-27 22:11:11.000000 pysatNASA-0.0.5/pysatNASA.egg-info/PKG-INFO
+-rw-r--r--   0 jklenzin   (502) staff       (20)     2028 2023-06-27 22:11:11.000000 pysatNASA-0.0.5/pysatNASA.egg-info/SOURCES.txt
+-rw-r--r--   0 jklenzin   (502) staff       (20)        1 2023-06-27 22:11:11.000000 pysatNASA-0.0.5/pysatNASA.egg-info/dependency_links.txt
+-rw-r--r--   0 jklenzin   (502) staff       (20)      272 2023-06-27 22:11:11.000000 pysatNASA-0.0.5/pysatNASA.egg-info/requires.txt
+-rw-r--r--   0 jklenzin   (502) staff       (20)       10 2023-06-27 22:11:11.000000 pysatNASA-0.0.5/pysatNASA.egg-info/top_level.txt
+-rw-r--r--   0 jklenzin   (502) staff       (20)      142 2023-06-27 22:11:11.667285 pysatNASA-0.0.5/setup.cfg
+-rw-r--r--   0 jklenzin   (502) staff       (20)      306 2023-06-14 19:11:13.000000 pysatNASA-0.0.5/try_cdflib.py
```

### Comparing `pysatNASA-0.0.4/CODE_OF_CONDUCT.md` & `pysatNASA-0.0.5/CODE_OF_CONDUCT.md`

 * *Files identical despite different names*

### Comparing `pysatNASA-0.0.4/CONTRIBUTING.md` & `pysatNASA-0.0.5/CONTRIBUTING.md`

 * *Files 3% similar despite different names*

```diff
@@ -74,41 +74,52 @@
    are tested in ``pysatNASA/tests/test_omni_hro.py``.  If no test file exists,
    then you should create one.  This testing uses pytest, which will run tests
    on any python file in the test directory that starts with ``test``.  Classes
    must begin with ``Test``, and methods must begin with ``test`` as well.
 
 
 4. When you're done making changes, run all the checks to ensure that nothing
-   is broken on your local system, as well as check for flake8 compliance:
+  is broken on your local system:
 
-   ```
-    pytest -vs --flake8 pysatNASA
-   ```
-
-5. Update/add documentation (in ``docs``), if relevant
-
-6. Add your name to the .zenodo.json file as an author
-
-7. Commit your changes:
-   ```
-   git add .
-   git commit -m "AAA: Brief description of your changes"
-   ```
-   Where AAA is a standard shorthand for the type of change (eg, BUG or DOC).
-   `pysat` follows the [numpy development workflow](https://numpy.org/doc/stable/dev/development_workflow.html),
-   see the discussion there for a full list of this shorthand notation.  
-
-8. Once you are happy with the local changes, push to Github:
-   ```
-   git push origin name-of-your-bugfix-or-feature
-   ```
-   Note that each push will trigger the Continuous Integration workflow.
+  ```
+  pytest pysatNASA
+  ```
 
-9. Submit a pull request through the GitHub website. Pull requests should be
-   made to the ``develop`` branch.
+5. You should also check for flake8 style compliance:
+
+  ```
+  flake8 . --count --select=D,E,F,H,W --show-source --statistics
+  ```
+
+  Note that pysat uses the `flake-docstrings` and `hacking` packages to ensure
+  standards in docstring formatting.
+
+
+6. Update/add documentation (in ``docs``), if relevant
+
+7. Add your name to the .zenodo.json file as an author
+
+8. Commit your changes:
+  ```
+  git add .
+  git commit -m "AAA: Brief description of your changes"
+  ```
+  Where AAA is a standard shorthand for the type of change (eg, BUG or DOC).
+  `pysat` follows the [numpy development workflow](https://numpy.org/doc/stable/dev/development_workflow.html),
+  see the discussion there for a full list of this shorthand notation.  
+
+9. Once you are happy with the local changes, push to Github:
+  ```
+  git push origin name-of-your-bugfix-or-feature
+  ```
+  Note that each push will trigger the Continuous Integration workflow.
+
+10. Submit a pull request through the GitHub website. Pull requests should be
+   made to the ``develop`` branch.  Note that automated tests will be run on
+   github actions, but these must be initialized by a member of the pysat team.
 
 Pull Request Guidelines
 -----------------------
 
 If you need some code review or feedback while you're developing the code, just
 make a pull request. Pull requests should be made to the ``develop`` branch.
 
@@ -156,7 +167,9 @@
 * Use setup and teardown in test classes
 * Use pytest parametrize in test classes when appropriate
 * Provide testing class methods with informative failure statements and
   descriptive, one-line docstrings
 * Block and inline comments should use proper English grammar and punctuation
   with the exception of single sentences in a block, which may then omit the
   final period
+* When casting is necessary, use `np.int64` and `np.float64` to ensure operating
+  system agnosticism
```

### Comparing `pysatNASA-0.0.4/LICENSE` & `pysatNASA-0.0.5/LICENSE`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 BSD 3-Clause License
 
-Copyright (c) 2020, pysat
+Copyright (c) 2023, pysat
 All rights reserved.
 
 Redistribution and use in source and binary forms, with or without
 modification, are permitted provided that the following conditions are met:
 
 1. Redistributions of source code must retain the above copyright notice, this
    list of conditions and the following disclaimer.
```

### Comparing `pysatNASA-0.0.4/PKG-INFO` & `pysatNASA-0.0.5/README.md`

 * *Files 22% similar despite different names*

```diff
@@ -1,34 +1,10 @@
-Metadata-Version: 2.1
-Name: pysatNASA
-Version: 0.0.4
-Summary: 'pysat support for NASA Instruments'
-Home-page: https://github.com/pysat/pysatNASA
-Author: Jeff Klenzing
-Author-email: jeffrey.klenzing@nasa.gov
-Keywords: pysat,ionosphere
-Classifier: Development Status :: 3 - Alpha
-Classifier: Topic :: Scientific/Engineering :: Physics
-Classifier: Topic :: Scientific/Engineering :: Atmospheric Science
-Classifier: Intended Audience :: Science/Research
-Classifier: License :: OSI Approved :: BSD License
-Classifier: Natural Language :: English
-Classifier: Programming Language :: Python :: 3.5
-Classifier: Programming Language :: Python :: 3.6
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Operating System :: MacOS :: MacOS X
-Classifier: Operating System :: POSIX :: Linux
-Requires-Python: >=3.5
-Description-Content-Type: text/markdown
-Provides-Extra: all
-License-File: LICENSE
-
 <div align="left">
         <img height="0" width="0px">
-        <img width="20%" src="https://raw.githubusercontent.com/pysat/pysatNASA/main/docs/figures/logo.png" alt="pysatNASA" title="pysatNASA" </img>
+        <img width="20%" src="https://raw.githubusercontent.com/pysat/pysatNASA/main/docs/figures/pysatnasa_logo.png" alt="pysatNASA" title="pysatNASA" </img>
 </div>
 
 # pysatNASA: pysat support for NASA Space Science instruments
 [![PyPI Package latest release](https://img.shields.io/pypi/v/pysatNASA.svg)](https://pypi.python.org/pypi/pysatNASA)
 [![Build Status](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)
 [![Coverage Status](https://coveralls.io/repos/github/pysat/pysatNASA/badge.svg?branch=main)](https://coveralls.io/github/pysat/pysatNASA?branch=main)
 
@@ -40,57 +16,79 @@
 The following instructions provide a guide for installing pysatNASA and give
 some examples on how to use the routines
 
 ### Prerequisites
 
 pysatNASA uses common Python modules, as well as modules developed by
 and for the Space Physics community.  This module officially supports
-Python 3.8+.
+Python 3.6+.
 
-| Common modules   | Community modules |
-| ---------------- | ----------------- |
-| beautifulsoup4   | cdflib            |
-| lxml             | pysat>=3.0.4      |
-| netCDF4          |                   |
-| numpy            |                   |
-| pandas           |                   |
-| requests         |                   |
-| xarray<2022.11   |                   |
+| Common modules   | Community modules | Optional Modules |
+| ---------------- | ----------------- |------------------|
+| beautifulsoup4   | cdflib>=0.4.4     | pysatCDF         |
+| lxml             | pysat>=3.1.0      |                  |
+| netCDF4          |                   |                  |
+| numpy            |                   |                  |
+| pandas           |                   |                  |
+| requests         |                   |                  |
+| xarray           |                   |                  |
 
-## GitHub Installation
+## PyPi Installation
+```
+pip install pysatNASA
+```
 
-Currently, the main way to get pysatNASA is through github.
+## GitHub Installation
 
 ```
 git clone https://github.com/pysat/pysatNASA.git
 ```
 
-Change directories into the repository folder and run the setup.py file.  For
+Change directories into the repository folder and build the project.  For
 a local install use the "--user" flag after "install".
 
 ```
 cd pysatNASA/
-python setup.py install
+pip install .
 ```
 
 Note: pre-1.0.0 version
 -----------------------
-pysatNASA is currently in an initial development phase and requires pysat 3.0.4.  
+pysatNASA is currently in an initial development phase and requires pysat 3.1.0.  
+Feedback and contributions are appreciated.
 
 # Using with pysat
 
 The instrument modules are portable and designed to be run like any pysat instrument.
 
 ```
 import pysat
 from pysatNASA.instruments import icon_ivm
 
 ivm = pysat.Instrument(inst_module=icon_ivm, inst_id='a')
 ```
-Another way to use the instruments in an external repository is to register the instruments.  This only needs to be done the first time you load an instrument.  Afterward, pysat will identify them using the `platform` and `name` keywords.
+Another way to use the instruments in an external repository is to register the
+instruments.  This only needs to be done the first time you load an instrument.  
+Afterward, pysat will identify them using the `platform` and `name` keywords.
 
 ```
 import pysat
 
 pysat.utils.registry.register(['pysatNASA.instruments.icon_ivm'])
 ivm = pysat.Instrument('icon', 'ivm', inst_id='a')
 ```
+
+# CDF Integration
+For data products stored as CDF files, this package can use either `cdflib` or
+`pysatCDF`.  Note that `cdflib` is a pure python package and more readily
+deployable across systems, whereas `pysatCDF` interfaces with the fortran.  
+This is a faster approach for loading data, but may not install on all systems.  
+There are known issues with `numpy`>=1.24. Therefore, `pysatCDF` is optional
+rather than required.  
+
+You can specify which load routine to use via the optional `use_cdflib` kwarg.
+If no kwarg is specified, `pysatNASA` will default to `pysatCDF` if it is
+successfully installed, and default to `cdflib` otherwise.
+
+```
+ivm = pysat.Instrument('cnofs', 'ivm', use_cdflib=True)
+```
```

### Comparing `pysatNASA-0.0.4/pysatNASA/constellations/__init__.py` & `pysatNASA-0.0.5/pysatNASA/constellations/__init__.py`

 * *Files identical despite different names*

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/cnofs_ivm.py` & `pysatNASA-0.0.5/pysatNASA/instruments/cnofs_ivm.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,50 +12,52 @@
 direction of satellite motion. By fitting these measurements
 to a theoretical description of plasma the number density, plasma
 composition, plasma temperature, and plasma motion may be determined.
 The DM directly measures the arrival angle of plasma. Using the reported
 motion of the satellite the angle is converted into ion motion along
 two orthogonal directions, perpendicular to the satellite track.
 
-References
-----------
-A brief discussion of the C/NOFS mission and instruments can be found at
-de La Beaujardière, O., et al. (2004), C/NOFS: A mission to forecast
-scintillations, J. Atmos. Sol. Terr. Phys., 66, 1573–1591,
-doi:10.1016/j.jastp.2004.07.030.
-
-Discussion of cleaning parameters for ion drifts can be found in:
-Burrell, Angeline G., Equatorial topside magnetic field-aligned ion drifts
-at solar minimum, The University of Texas at Dallas, ProQuest
-Dissertations Publishing, 2012. 3507604.
-
-Discussion of cleaning parameters for ion temperature can be found in:
-Hairston, M. R., W. R. Coley, and R. A. Heelis (2010), Mapping the
-duskside topside ionosphere with CINDI and DMSP, J. Geophys. Res.,115,
-A08324, doi:10.1029/2009JA015051.
-
 
 Properties
 ----------
 platform
     'cnofs'
 name
     'ivm'
 tag
     None supported
 inst_id
     None supported
 
+
 Warnings
 --------
 - The sampling rate of the instrument changes on July 29th, 2010.
   The rate is attached to the instrument object as .sample_rate.
 
 - The cleaning parameters for the instrument are still under development.
 
+
+References
+----------
+A brief discussion of the C/NOFS mission and instruments can be found at
+de La Beaujardière, O., et al. (2004), C/NOFS: A mission to forecast
+scintillations, J. Atmos. Sol. Terr. Phys., 66, 1573–1591,
+doi:10.1016/j.jastp.2004.07.030.
+
+Discussion of cleaning parameters for ion drifts can be found in:
+Burrell, Angeline G., Equatorial topside magnetic field-aligned ion drifts
+at solar minimum, The University of Texas at Dallas, ProQuest
+Dissertations Publishing, 2012. 3507604.
+
+Discussion of cleaning parameters for ion temperature can be found in:
+Hairston, M. R., W. R. Coley, and R. A. Heelis (2010), Mapping the
+duskside topside ionosphere with CINDI and DMSP, J. Geophys. Res.,115,
+A08324, doi:10.1029/2009JA015051.
+
 """
 
 import datetime as dt
 import functools
 
 import numpy as np
 
@@ -241,16 +243,13 @@
 supported_tags = {'': {'': fname}}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
 load = cdw.load
 
-# Set the download routine
-basic_tag = {'remote_dir': '/pub/data/cnofs/cindi/ivm_500ms_cdf/{year:4d}/',
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'CNOFS_CINDI_IVM_500MS'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/cnofs_plp.py` & `pysatNASA-0.0.5/pysatNASA/instruments/de2_lang.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,129 +1,105 @@
 # -*- coding: utf-8 -*-
-"""Module for the C/NOFS PLP instrument.
+"""Module for the DE2 LANG instrument.
 
-Supports the Planar Langmuir Probe (PLP) onboard the Communication
-and Navigation Outage Forecasting System (C/NOFS) satellite. Downloads
-data from the NASA Coordinated Data Analysis Web (CDAWeb).
+Supports the Langmuir Probe (LANG) instrument on Dynamics Explorer 2 (DE2).
 
-Description from CDAWeb:
+From CDAWeb:
 
-The Planar Langmuir Probe on C/NOFS is a suite of 2 current measuring sensors
-mounted on the ram facing surface of the spacecraft.  The primary sensor is an
-Ion Trap (conceptually similar to RPAs flown on many other spacecraft) capable
-of measuring ion densities as low as 1 cm-3 with a 12 bit log electrometer.
-The secondary senor is a swept bias planar Langmuir probe (Surface Probe)
-capable of measuring Ne, Te, and spacecraft potential.
+The Langmuir Probe Instrument (LANG) was a cylindrical electrostatic probe that
+obtained measurements of electron temperature, Te, and electron or ion
+concentration, Ne or Ni, respectively, and spacecraft potential.  Data from
+this investigation were used to provide temperature and density measurements
+along magnetic field lines related to thermal energy and particle flows within
+the magnetosphere-ionosphere system, to provide thermal plasma conditions for
+wave-particle interactions, and to measure large-scale and fine-structure
+ionospheric effects of energy deposition in the ionosphere.  The Langmuir Probe
+instrument was identical to that used on the AE satellites and the Pioneer
+Venus Orbiter. Two independent sensors were connected to individual adaptive
+sweep voltage circuits which continuously tracked the changing electron
+temperature and spacecraft potential, while autoranging electrometers adjusted
+their gain in response to the changing plasma density. The control signals used
+to achieve this automatic tracking provided a continuous monitor of the
+ionospheric parameters without telemetering each volt-ampere (V-I) curve.
+Furthermore, internal data storage circuits permitted high resolution, high
+data rate sampling of selected V-I curves for transmission to ground to verify
+or correct the inflight processed data. Time resolution was 0.5 seconds.
 
-The ion number density is the one second average of the ion density sampled at
-either 32, 256, 512, or 1024 Hz (depending on the mode).
-
-The ion density standard deviation is the standard deviation of the samples
-used to produce the one second average number density.
-
-DeltaN/N is the detrened ion number density 1 second standard deviation divided
-by the mean 1 sec density.
-
-The electron density, electron temperature, and spacecraft potential are all
-derived from a least squares fit to the current-bias curve from the Surface
-Probe.
-
-The data is PRELIMINARY, and as such, is intended for BROWSE PURPOSES ONLY.
-
-References
-----------
-A brief discussion of the C/NOFS mission and instruments can be found at
-de La Beaujardière, O., et al. (2004), C/NOFS: A mission to forecast
-scintillations, J. Atmos. Sol. Terr. Phys., 66, 1573–1591,
-doi:10.1016/j.jastp.2004.07.030.
 
 Properties
 ----------
 platform
-    'cnofs'
+    'de2'
 name
-    'plp'
+    'lang'
 tag
-    None supported
+    None Supported
 inst_id
-    None supported
+    None Supported
 
 
 Warnings
 --------
-- The data are PRELIMINARY, and as such, are intended for BROWSE PURPOSES ONLY.
 - Currently no cleaning routine.
-- Module not written by PLP team.
+
+
+References
+----------
+J. P. Krehbiel, L. H. Brace, R. F. Theis, W. H. Pinkus, and R. B. Kaplan,
+"The Dynamics Explorer 2 Langmuir Probe (LANG)", Space Sci. Instrum., 5,
+493-502, 1981.
 
 """
 
 import datetime as dt
 import functools
-import numpy as np
 
 from pysat.instruments.methods import general as mm_gen
 
 from pysatNASA.instruments.methods import cdaweb as cdw
-from pysatNASA.instruments.methods import cnofs as mm_cnofs
+from pysatNASA.instruments.methods import de2 as mm_de2
 from pysatNASA.instruments.methods import general as mm_nasa
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
-platform = 'cnofs'
-name = 'plp'
-tags = {'': ''}
-inst_ids = {'': ['']}
+platform = 'de2'
+name = 'lang'
+tags = {'': '500 ms cadence Langmuir Probe data'}
+inst_ids = {'': [tag for tag in tags.keys()]}
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
-_test_dates = {'': {'': dt.datetime(2009, 1, 1)}}
+_test_dates = {'': {tag: dt.datetime(1983, 1, 1) for tag in tags.keys()}}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
-# Use standard init routine
-init = functools.partial(mm_nasa.init, module=mm_cnofs, name=name)
-
 
-def clean(self):
-    """Clean C/NOFS PLP data to the specified level.
-
-    Note
-    ----
-    Basic cleaning to find valid Epoch values
-
-    """
-
-    for key in self.data.columns:
-        if key != 'Epoch':
-            fill = self.meta[key, self.meta.labels.fill_val]
-            idx, = np.where(self[key] == fill)
-            self[idx, key] = np.nan
-    return
+# Use standard init routine
+init = functools.partial(mm_nasa.init, module=mm_de2, name=name)
 
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
-fname = ''.join(('cnofs_plp_plasma_1sec_{year:04d}{month:02d}{day:02d}',
-                 '_v{version:02d}.cdf'))
+fname = 'de2_plasma500ms_lang_{year:04d}{month:02d}{day:02d}_v{version:02d}.cdf'
 supported_tags = {'': {'': fname}}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
 load = cdw.load
 
 # Set the download routine
-basic_tag = {'remote_dir': '/pub/data/cnofs/plp/plasma_1sec/{year:4d}/',
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'DE2_PLASMA500MS_LANG'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/cnofs_vefi.py` & `pysatNASA-0.0.5/pysatNASA/instruments/cnofs_vefi.py`

 * *Files 3% similar despite different names*

```diff
@@ -22,20 +22,14 @@
 magnetic field data file currently contains the following variables:
 B_north   Magnetic field in the north direction
 B_up      Magnetic field in the up direction
 B_west    Magnetic field in the west direction
 
 The data is PRELIMINARY, and as such, is intended for BROWSE PURPOSES ONLY.
 
-References
-----------
-A brief discussion of the C/NOFS mission and instruments can be found at
-de La Beaujardière, O., et al. (2004), C/NOFS: A mission to forecast
-scintillations, J. Atmos. Sol. Terr. Phys., 66, 1573–1591,
-doi:10.1016/j.jastp.2004.07.030.
 
 Properties
 ----------
 platform
     'cnofs'
 name
     'vefi'
@@ -52,14 +46,22 @@
 
 Warnings
 --------
 - The data is PRELIMINARY, and as such, is intended for BROWSE PURPOSES ONLY.
 - Limited cleaning routine.
 - Module not written by VEFI team.
 
+
+References
+----------
+A brief discussion of the C/NOFS mission and instruments can be found at
+de La Beaujardière, O., et al. (2004), C/NOFS: A mission to forecast
+scintillations, J. Atmos. Sol. Terr. Phys., 66, 1573–1591,
+doi:10.1016/j.jastp.2004.07.030.
+
 """
 
 import datetime as dt
 import functools
 import numpy as np
 
 from pysat.instruments.methods import general as mm_gen
@@ -118,15 +120,13 @@
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
 load = cdw.load
 
 # Set the download routine
-basic_tag = {'remote_dir': '/pub/data/cnofs/vefi/bfield_1sec/{year:4d}/',
-             'fname': fname}
-download_tags = {'': {'dc_b': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'dc_b': 'CNOFS_VEFI_BFIELD_1SEC'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/de2_lang.py` & `pysatNASA-0.0.5/pysatNASA/instruments/de2_fpi.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,57 +1,59 @@
 # -*- coding: utf-8 -*-
-"""Module for the DE2 LANG instrument.
+"""The DE2 FPI instrument.
 
-Supports the Langmuir Probe (LANG) instrument on Dynamics Explorer 2 (DE2).
+Supports the Fabry-Perot Interferometer (FPI) instrument on Dynamics Explorer 2
+(DE2).
 
 From CDAWeb:
 
-The Langmuir Probe Instrument (LANG) was a cylindrical electrostatic probe that
-obtained measurements of electron temperature, Te, and electron or ion
-concentration, Ne or Ni, respectively, and spacecraft potential.  Data from
-this investigation were used to provide temperature and density measurements
-along magnetic field lines related to thermal energy and particle flows within
-the magnetosphere-ionosphere system, to provide thermal plasma conditions for
-wave-particle interactions, and to measure large-scale and fine-structure
-ionospheric effects of energy deposition in the ionosphere.  The Langmuir Probe
-instrument was identical to that used on the AE satellites and the Pioneer
-Venus Orbiter. Two independent sensors were connected to individual adaptive
-sweep voltage circuits which continuously tracked the changing electron
-temperature and spacecraft potential, while autoranging electrometers adjusted
-their gain in response to the changing plasma density. The control signals used
-to achieve this automatic tracking provided a continuous monitor of the
-ionospheric parameters without telemetering each volt-ampere (V-I) curve.
-Furthermore, internal data storage circuits permitted high resolution, high
-data rate sampling of selected V-I curves for transmission to ground to verify
-or correct the inflight processed data. Time resolution was 0.5 seconds.
-
-
-References
-----------
-J. P. Krehbiel, L. H. Brace, R. F. Theis, W. H. Pinkus, and R. B. Kaplan,
-"The Dynamics Explorer 2 Langmuir Probe (LANG)", Space Sci. Instrum., 5,
-493-502, 1981.
+The Fabry-Perot Interferometer (FPI) was a high-resolution remote sensing
+instrument designed to measure the thermospheric temperature, meridional wind,
+and density of the following metastable atoms: atomic oxygen (singlet S and D)
+and the 2P state of ionic atomic oxygen. The FPI performed a wavelength analysis
+on the light detected from the thermospheric emission features by spatially
+scanning the interference fringe plane with a multichannel array detector. The
+wavelength analysis characterized the Doppler line profile of the emitting
+species. A sequential altitude scan performed by a commandable horizon scan
+mirror provided a cross-sectional view of the thermodynamic and dynamic state of
+the thermosphere below the DE 2 orbit. The information obtained from this
+investigation was used to study the dynamic response of the thermosphere to the
+energy sources caused by magnetospheric electric fields and the absorption of
+solar ultraviolet light in the thermosphere. The instrument was based on the
+visible airglow experiment (VAE) used in the AE program. The addition of a
+scanning mirror, the Fabry-Perot etalon, an image plane detector, and a
+calibration lamp were the principal differences. Interference filters isolated
+lines at (in Angstroms) 5577, 6300, 7320, 5896, and 5200. The FPI had a field of
+view of 0.53 deg (half-cone angle). More details are found in P. B. Hays et al.,
+Space Sci. Instrum., v. 5, n. 4, p. 395, 1981. From February 16, 1982 to
+September 11, 1982 the DE satellite was inverted and the FPI measured galactic
+emissions.
 
 Properties
 ----------
 platform
     'de2'
 name
-    'lang'
-inst_id
-    None Supported
+    'fpi'
 tag
     None Supported
+inst_id
+    None Supported
 
 
 Warnings
 --------
 - Currently no cleaning routine.
 
 
+References
+----------
+Hays, P B, Killeen, T L, and Kennedy, B C. "Fabry-Perot interferometer on
+Dynamics Explorer". Space Sci. Instrum., 5, 395-416, 1981.
+
 """
 
 import datetime as dt
 import functools
 
 from pysat.instruments.methods import general as mm_gen
 
@@ -59,50 +61,47 @@
 from pysatNASA.instruments.methods import de2 as mm_de2
 from pysatNASA.instruments.methods import general as mm_nasa
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
 platform = 'de2'
-name = 'lang'
-tags = {'': '500 ms cadence Langmuir Probe data'}
-inst_ids = {'': ['']}
+name = 'fpi'
+tags = {'': '8 s cadence Fabry-Perot Interferometer data'}
+inst_ids = {'': [tag for tag in tags.keys()]}
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
-_test_dates = {'': {'': dt.datetime(1983, 1, 1)}}
+_test_dates = {'': {tag: dt.datetime(1983, 1, 1) for tag in tags.keys()}}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
 
 # Use standard init routine
 init = functools.partial(mm_nasa.init, module=mm_de2, name=name)
 
-# No cleaning, use standard warning function instead
-clean = mm_nasa.clean_warn
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
-fname = 'de2_plasma500ms_lang_{year:04d}{month:02d}{day:02d}_v{version:02d}.cdf'
+fname = 'de2_neutral8s_fpi_{year:04d}{month:02d}{day:02d}_v{version:02d}.cdf'
 supported_tags = {'': {'': fname}}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
-# Set the load routine
+# Use the default CDAWeb method
 load = cdw.load
 
-# Set the download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/de/de2/plasma_lang',
-                                    '/plasma500ms_lang_cdaweb/{year:4d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+# Support download routine
+download_tags = {'': {'': 'DE2_NEUTRAL8S_FPI'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
-# Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+# Support listing files currently on CDAWeb
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/de2_nacs.py` & `pysatNASA-0.0.5/pysatNASA/instruments/de2_nacs.py`

 * *Files 11% similar despite different names*

```diff
@@ -46,35 +46,37 @@
 their background values (which could only be determined from infrequent
 spinning orbits) and the count rate for Ar becomes very low. The difference
 between minimum (background) and maximum count rate for atomic nitrogen
 (estimated from mass 30) was so small that results are generally poor.  Data
 were lost between 12 March 1982 and 31 March 1982 when the counter overflowed.
 
 
-References
-----------
-G. R. Carrignan, B. P. Block, J. C. Maurer,  A. E. Hedin, C. A. Reber,
-N. W. Spencer, "The neutral mass spectrometer on Dynamics Explorer B",
-Space Sci. Instrum., 5, 429-441, 1981.
-
 Properties
 ----------
 platform
     'de2'
 name
     'nacs'
-inst_id
-    None Supported
 tag
     None Supported
+inst_id
+    None Supported
+
 
 Warnings
 --------
 - Currently no cleaning routine.
 
+
+References
+----------
+G. R. Carrignan, B. P. Block, J. C. Maurer,  A. E. Hedin, C. A. Reber,
+N. W. Spencer, "The neutral mass spectrometer on Dynamics Explorer B",
+Space Sci. Instrum., 5, 429-441, 1981.
+
 """
 
 import datetime as dt
 import functools
 
 from pysat.instruments.methods import general as mm_gen
 
@@ -84,30 +86,30 @@
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
 platform = 'de2'
 name = 'nacs'
 tags = {'': '1 s cadence Neutral Atmosphere Composition Spectrometer data'}
-inst_ids = {'': ['']}
+inst_ids = {'': [tag for tag in tags.keys()]}
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
-_test_dates = {'': {'': dt.datetime(1983, 1, 1)}}
+_test_dates = {'': {tag: dt.datetime(1983, 1, 1) for tag in tags.keys()}}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
 
 # Use standard init routine
 init = functools.partial(mm_nasa.init, module=mm_de2, name=name)
 
-# No cleaning, use standard warning function instead
-clean = mm_nasa.clean_warn
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
@@ -116,16 +118,13 @@
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Use the default CDAWeb method
 load = cdw.load
 
 # Support download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/de/de2/neutral_gas_nacs',
-                                    '/neutral1s_nacs_cdaweb/{year:4d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'DE2_NEUTRAL1S_NACS'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Support listing files currently on CDAWeb
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/de2_rpa.py` & `pysatNASA-0.0.5/pysatNASA/instruments/de2_rpa.py`

 * *Files 11% similar despite different names*

```diff
@@ -22,45 +22,43 @@
 The details of this voltage trace, and whether it was continuous or stepped,
 depended on the operating mode of the instrument. Specific parameters deduced
 from these measurements were ion temperature; vehicle potential; ram component
 of the ion drift velocity; the ion and electron concentration irregularity
 spectrum; and the concentration of H+, He+, O+, and Fe+, and of molecular ions
 near perigee.
 
-It includes the DUCT portion of the high resolutiondata from the Dynamics
-Explorer 2 (DE-2) Retarding Potential Analyzer (RPA) for the whole DE-2 mission
-time period in ASCII format. This version was generated at NSSDC from the
-PI-provided binary data (SPIO-00232). The DUCT files include RPA measurements
-ofthe total ion concentration every 64 times per second. Due to a failure in
-the instrument memory system RPA data are not available from 81317 06:26:40 UT
-to 82057 13:16:00 UT. This data set is based on the revised version of the RPA
-files that was submitted by the PI team in June of 1995. The revised RPA data
-include a correction to the spacecraft potential.
+Due to a failure in the instrument memory system RPA data are not available
+from 81317 06:26:40 UT to 82057 13:16:00 UT. This data set is based on the
+revised version of the RPA files that was submitted by the PI team in June of
+1995. The revised RPA data include a correction to the spacecraft potential.
 
-References
-----------
-W. B. Hanson, R. A. Heelis, R. A. Power, C. R. Lippincott, D. R. Zuccaro,
-B. J. Holt, L. H. Harmon, and S. Sanatani, “The retarding potential analyzer
-for dynamics explorer-B,” Space Sci. Instrum. 5, 503–510 (1981).
 
 Properties
 ----------
 platform
     'de2'
 name
     'rpa'
-inst_id
-    None Supported
 tag
     None Supported
+inst_id
+    None Supported
+
 
 Warnings
 --------
 - Currently no cleaning routine.
 
+
+References
+----------
+W. B. Hanson, R. A. Heelis, R. A. Power, C. R. Lippincott, D. R. Zuccaro,
+B. J. Holt, L. H. Harmon, and S. Sanatani, “The retarding potential analyzer
+for dynamics explorer-B,” Space Sci. Instrum. 5, 503–510 (1981).
+
 """
 
 import datetime as dt
 import functools
 
 from pysat.instruments.methods import general as mm_gen
 
@@ -69,49 +67,49 @@
 from pysatNASA.instruments.methods import general as mm_nasa
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
 platform = 'de2'
 name = 'rpa'
-tags = {'': '2 sec cadence RPA data'}  # this is the default cadence
-inst_ids = {'': ['']}
+tags = {'': '2 sec cadence RPA data'}
+inst_ids = {'': [tag for tag in tags.keys()]}
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
-_test_dates = {'': {'': dt.datetime(1983, 1, 1)}}
+_test_dates = {'': {tag: dt.datetime(1983, 1, 1) for tag in tags.keys()}}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
 
 # Use standard init routine
 init = functools.partial(mm_nasa.init, module=mm_de2, name=name)
 
-# No cleaning, use standard warning function instead
-clean = mm_nasa.clean_warn
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
-fname = 'de2_ion2s_rpa_{year:04d}{month:02d}{day:02d}_v{version:02d}.cdf'
-supported_tags = {'': {'': fname}}
+datestr = '{year:04d}{month:02d}{day:02d}_v{version:02d}'
+dataproduct = {'': 'ion2s'}
+fname = 'de2_{dp:s}_rpa_{datestr:s}.cdf'
+supported_tags = {'': {tag: fname.format(dp=dataproduct[tag], datestr=datestr)
+                       for tag in tags.keys()}}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
 load = cdw.load
 
 # Set the download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/de/de2/plasma_rpa',
-                                    '/ion2s_cdaweb/{year:4d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'DE2_ION2S_RPA'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/de2_wats.py` & `pysatNASA-0.0.5/pysatNASA/instruments/de2_wats.py`

 * *Files 6% similar despite different names*

```diff
@@ -43,35 +43,37 @@
 NSSDC-developed software was used to add the orbit parameters, to convert the
 binary into ASCII format and to combine the (PI-provided) orbital files into
 daily files. For more on DE-2, WATS, and the binary data, see the
 WATS_VOLDESC_SFDU_DE.DOC and WATS_FORMAT_SFDU_DE.DOC files. More information
 about the processing done at NSSDC is given in WATS_NSSDC_PRO_DE.DOC.
 
 
-References
-----------
-N. W. Spencer, L. E. Wharton, H. B. Niemann, A. E. Hedin, G. R. Carrignan,
-J. C. Maurer, "The Dynamics Explorer Wind and Temperature Spectrometer",
-Space Sci. Instrum., 5, 417-428, 1981.
-
 Properties
 ----------
 platform
     'de2'
 name
     'wats'
-inst_id
-    None Supported
 tag
     None Supported
+inst_id
+    None Supported
+
 
 Warnings
 --------
 - Currently no cleaning routine.
 
+
+References
+----------
+N. W. Spencer, L. E. Wharton, H. B. Niemann, A. E. Hedin, G. R. Carrignan,
+J. C. Maurer, "The Dynamics Explorer Wind and Temperature Spectrometer",
+Space Sci. Instrum., 5, 417-428, 1981.
+
 """
 
 import datetime as dt
 import functools
 
 from pysat.instruments.methods import general as mm_gen
 
@@ -81,30 +83,30 @@
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
 platform = 'de2'
 name = 'wats'
 tags = {'': '2 s cadence Wind and Temperature Spectrometer data'}
-inst_ids = {'': ['']}
+inst_ids = {'': [tag for tag in tags.keys()]}
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
-_test_dates = {'': {'': dt.datetime(1983, 1, 1)}}
+_test_dates = {'': {tag: dt.datetime(1983, 1, 1) for tag in tags.keys()}}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
 
 # Use standard init routine
 init = functools.partial(mm_nasa.init, module=mm_de2, name=name)
 
-# No cleaning, use standard warning function instead
-clean = mm_nasa.clean_warn
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
@@ -113,16 +115,13 @@
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
 load = cdw.load
 
 # Set the download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/de/de2/neutral_gas_wats',
-                                    '/wind2s_wats_cdaweb/{year:4d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'DE2_WIND2S_WATS'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/formosat1_ivm.py` & `pysatNASA-0.0.5/pysatNASA/instruments/formosat1_ivm.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 # -*- coding: utf-8 -*-
-"""Module for the ICON EUV instrument.
+"""Module for the Formosat-1 IVM instrument.
 
 Supports the Ion Velocity Meter (IVM) onboard the Formosat-1 (formerly
 ROCSAT-1) mission. Downloads data from the NASA Coordinated Data Analysis
 Web (CDAWeb).
 
 Properties
 ----------
@@ -70,16 +70,16 @@
                                 'Terr. Atmos. Ocean. Sci., 10, 805,',
                                 '1999b.'))
     logger.info(self.acknowledgements)
 
     return
 
 
-# No cleaning, use standard warning function instead
-clean = mm_nasa.clean_warn
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
@@ -88,16 +88,13 @@
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
 load = cdw.load
 
 # Set the download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/formosat-rocsat/formosat-1',
-                                    '/ipei/{year:4d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'RS_K0_IPEI'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/icon_euv.py` & `pysatNASA-0.0.5/pysatNASA/instruments/icon_euv.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,14 +9,16 @@
 ----------
 platform
     'icon'
 name
     'euv'
 tag
     None supported
+inst_id
+    None Supported
 
 Warnings
 --------
 - The cleaning parameters for the instrument are still under development.
 - Only supports level-2 data.
 
 
@@ -123,21 +125,19 @@
 fname = ''.join(('icon_l2-6_euv_{year:04d}{month:02d}{day:02d}_',
                  'v{version:02d}r{revision:03d}.nc'))
 supported_tags = {'': {'': fname}}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the download routine
-basic_tag = {'remote_dir': '/pub/data/icon/l2/l2-6_euv/{year:04d}/',
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'ICON_L2-6_EUV'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
 
 
 def filter_metadata(meta_dict):
     """Filter EUV metadata to remove warnings during loading.
 
     Parameters
@@ -210,25 +210,27 @@
 
         inst = pysat.Instrument('icon', 'euv', tag='', inst_id='a')
         inst.load(2020, 1)
 
     """
     labels = {'units': ('Units', str), 'name': ('Long_Name', str),
               'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
-              'min_val': ('ValidMin', float),
-              'max_val': ('ValidMax', float), 'fill_val': ('FillVal', float)}
+              'min_val': ('ValidMin', (int, float)),
+              'max_val': ('ValidMax', (int, float)),
+              'fill_val': ('FillVal', (int, float))}
 
     meta_translation = {'FieldNam': 'plot'}
 
     data, meta = pysat.utils.io.load_netcdf(fnames, epoch_name='Epoch',
                                             pandas_format=pandas_format,
-                                            labels=labels,
+                                            meta_kwargs={'labels': labels},
                                             meta_processor=filter_metadata,
                                             meta_translation=meta_translation,
                                             drop_meta_labels=['Valid_Max',
                                                               'Valid_Min',
-                                                              '_FillValue'])
+                                                              '_FillValue'],
+                                            decode_times=False)
 
     # xarray can't merge if variable and dim names are the same
     if 'Altitude' in data.dims:
         data = data.rename_dims(dims_dict={'Altitude': 'Alt'})
     return data, meta
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/icon_fuv.py` & `pysatNASA-0.0.5/pysatNASA/instruments/icon_fuv.py`

 * *Files 6% similar despite different names*

```diff
@@ -9,14 +9,16 @@
 ----------
 platform
     'icon'
 name
     'fuv'
 tag
     None supported
+inst_id
+    None Supported
 
 Warnings
 --------
 - The cleaning parameters for the instrument are still under development.
 - Only supports level-2 data.
 
 Example
@@ -115,24 +117,21 @@
                    'v{version:02d}r{revision:03d}.nc'))
 supported_tags = {'': {'day': fname24, 'night': fname25}}
 
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the download routine
-basic_tag24 = {'remote_dir': '/pub/data/icon/l2/l2-4_fuv_day/{year:04d}/',
-               'fname': fname24}
-basic_tag25 = {'remote_dir': '/pub/data/icon/l2/l2-5_fuv_night/{year:04d}/',
-               'fname': fname25}
-download_tags = {'': {'day': basic_tag24, 'night': basic_tag25}}
+download_tags = {'': {'day': 'ICON_L2-4_FUV_DAY',
+                      'night': 'ICON_L2-5_FUV_NIGHT'}}
 
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
 
 
 def filter_metadata(meta_dict):
     """Filter FUV metadata to remove warnings during loading.
 
     Parameters
@@ -207,24 +206,26 @@
 
         inst = pysat.Instrument('icon', 'fuv')
         inst.load(2020, 1)
 
     """
     labels = {'units': ('Units', str), 'name': ('Long_Name', str),
               'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
-              'min_val': ('ValidMin', float),
-              'max_val': ('ValidMax', float), 'fill_val': ('FillVal', float)}
+              'min_val': ('ValidMin', (int, float)),
+              'max_val': ('ValidMax', (int, float)),
+              'fill_val': ('FillVal', (int, float))}
 
     meta_translation = {'FieldNam': 'plot', 'LablAxis': 'axis',
                         'FIELDNAM': 'plot', 'LABLAXIS': 'axis',
                         'Bin_Location': 'bin_loc'}
 
     drop_labels = ['Valid_Max', 'Valid_Min', 'Valid_Range', 'SCALETYP',
                    'TYPE', 'CONTENT']
 
     data, meta = pysat.utils.io.load_netcdf(fnames, epoch_name='Epoch',
                                             pandas_format=pandas_format,
-                                            labels=labels,
+                                            meta_kwargs={'labels': labels},
                                             meta_processor=filter_metadata,
                                             meta_translation=meta_translation,
-                                            drop_meta_labels=drop_labels)
+                                            drop_meta_labels=drop_labels,
+                                            decode_times=False)
     return data, meta
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/icon_ivm.py` & `pysatNASA-0.0.5/pysatNASA/instruments/icon_ivm.py`

 * *Files 1% similar despite different names*

```diff
@@ -188,21 +188,20 @@
                   for id in ['a', 'b']}
 
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the download routine
 dirstr = '/pub/data/icon/l2/l2-7_ivm-{id:s}/{{year:4d}}/'
-download_tags = {id: {'': {'remote_dir': dirstr.format(id=id),
-                           'fname': supported_tags[id]['']}}
-                 for id in ['a', 'b']}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'a': {'': 'ICON_L2-7_IVM-A'}, 'b': {'': 'ICON_L2-7_IVM-B'}}
+
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
 
 
 def filter_metadata(meta_dict):
     """Filter IVM metadata to remove warnings during loading.
 
     Parameters
@@ -269,22 +268,23 @@
         inst = pysat.Instrument('icon', 'ivm', inst_id='a', tag='')
         inst.load(2020, 1)
 
     """
 
     labels = {'units': ('Units', str), 'name': ('Long_Name', str),
               'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
-              'min_val': ('ValidMin', float),
-              'max_val': ('ValidMax', float), 'fill_val': ('FillVal', float)}
+              'min_val': ('ValidMin', (int, float)),
+              'max_val': ('ValidMax', (int, float)),
+              'fill_val': ('FillVal', (int, float))}
 
     meta_translation = {'FieldNam': 'plot', 'LablAxis': 'axis',
                         'ScaleTyp': 'scale',
                         '_FillValue': 'FillVal'}
 
     data, meta = pysat.utils.io.load_netcdf(fnames, epoch_name='Epoch',
-                                            labels=labels,
+                                            meta_kwargs={'labels': labels},
                                             meta_processor=filter_metadata,
                                             meta_translation=meta_translation,
                                             drop_meta_labels=['Valid_Max',
                                                               'Valid_Min'])
 
     return data, meta
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/icon_mighti.py` & `pysatNASA-0.0.5/pysatNASA/instruments/icon_mighti.py`

 * *Files 9% similar despite different names*

```diff
@@ -222,38 +222,31 @@
                                                       date=datestr),
                         'temperature': fname3.format(id='b', date=datestr)}}
 
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the download routine
-dirstr1 = '/pub/data/icon/l2/l2-1_mighti-{{id:s}}_los-wind-{color:s}/'
-dirstr2 = '/pub/data/icon/l2/l2-2_mighti_vector-wind-{color:s}/'
-dirstr3 = '/pub/data/icon/l2/l2-3_mighti-{id:s}_temperature/'
-dirnames = {'los_wind_green': dirstr1.format(color='green'),
-            'los_wind_red': dirstr1.format(color='red'),
-            'vector_wind_green': dirstr2.format(color='green'),
-            'vector_wind_red': dirstr2.format(color='red'),
-            'temperature': dirstr3}
-
-download_tags = {}
-for inst_id in supported_tags.keys():
-    download_tags[inst_id] = {}
-    for tag in supported_tags[inst_id].keys():
-        fname = supported_tags[inst_id][tag]
-
-        download_tags[inst_id][tag] = {
-            'remote_dir': ''.join((dirnames[tag].format(id=inst_id),
-                                   '{year:04d}/')),
-            'fname': fname}
+download_tags = {'vector':
+                 {'vector_wind_green': 'ICON_L2-2_MIGHTI_VECTOR-WIND-GREEN',
+                  'vector_wind_red': 'ICON_L2-2_MIGHTI_VECTOR-WIND-RED'},
+                 'a':
+                 {'los_wind_green': 'ICON_L2-1_MIGHTI-A_LOS-WIND-GREEN',
+                  'los_wind_red': 'ICON_L2-1_MIGHTI-A_LOS-WIND-RED',
+                  'temperature': 'ICON_L2-3_MIGHTI-A_TEMPERATURE'},
+                 'b':
+                 {'los_wind_green': 'ICON_L2-1_MIGHTI-B_LOS-WIND-GREEN',
+                  'los_wind_red': 'ICON_L2-1_MIGHTI-B_LOS-WIND-RED',
+                  'temperature': 'ICON_L2-3_MIGHTI-B_TEMPERATURE'}}
 
-download = functools.partial(cdw.download, supported_tags=download_tags)
+
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
 
 
 def filter_metadata(meta_dict):
     """Filter FUV metadata to remove warnings during loading.
 
     Parameters
@@ -321,31 +314,33 @@
 
         inst = pysat.Instrument('icon', 'fuv')
         inst.load(2020, 1)
 
     """
     labels = {'units': ('Units', str), 'name': ('Long_Name', str),
               'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
-              'min_val': ('ValidMin', float),
-              'max_val': ('ValidMax', float), 'fill_val': ('FillVal', float)}
+              'min_val': ('ValidMin', (int, float)),
+              'max_val': ('ValidMax', (int, float)),
+              'fill_val': ('FillVal', (int, float))}
 
     meta_translation = {'FieldNam': 'plot', 'LablAxis': 'axis',
                         'FIELDNAM': 'plot', 'LABLAXIS': 'axis',
                         'Bin_Location': 'bin_loc',
                         'Bin_location': 'bin_loc'}
 
     data, meta = pysat.utils.io.load_netcdf(fnames, epoch_name='Epoch',
                                             pandas_format=pandas_format,
-                                            labels=labels,
+                                            meta_kwargs={'labels': labels},
                                             meta_processor=filter_metadata,
                                             meta_translation=meta_translation,
                                             drop_meta_labels=['Valid_Max',
                                                               'Valid_Min',
                                                               'Valid_Range',
                                                               '_Fillvalue',
-                                                              'ScaleTyp'])
+                                                              'ScaleTyp'],
+                                            decode_times=False)
 
     # xarray can't merge if variable and dim names are the same
     if 'Altitude' in data.dims:
         data = data.rename_dims(dims_dict={'Altitude': 'Alt'})
 
     return data, meta
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/iss_fpmu.py` & `pysatNASA-0.0.5/pysatNASA/instruments/iss_fpmu.py`

 * *Files 9% similar despite different names*

```diff
@@ -22,20 +22,20 @@
 - Currently clean only replaces fill values with Nans.
 - Module not written by FPMU team.
 
 """
 
 import datetime as dt
 import functools
-import numpy as np
 
 from pysat.instruments.methods import general as mm_gen
 from pysat import logger
 
 from pysatNASA.instruments.methods import cdaweb as cdw
+from pysatNASA.instruments.methods import general as mm_nasa
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
 platform = 'iss'
 name = 'fpmu'
 tags = {'': ''}
@@ -75,33 +75,16 @@
                                 'International Space Station, Rev. Sci.',
                                 'Instrum. 80, 041301 (2009),',
                                 'https://doi.org/10.1063/1.3116085'))
 
     return
 
 
-def clean(self):
-    """Clean ISS FPMU data to the specified level.
-
-    Note
-    ----
-    'clean' - Replace Te and Ni fill values with NaN
-    'dusty' - Same as clean
-    'dirty' - Same as clean
-    'none'  - Not applied, default fill values are preserved
-
-    """
-
-    # Replace Te data fill
-    self.data.replace(-999., np.nan, inplace=True)
-
-    # Replace Ne data fill
-    self.data.replace(-9.9999998e+30, np.nan, inplace=True)
-
-    return
+# Use default clean
+clean = mm_nasa.clean
 
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
@@ -111,16 +94,13 @@
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
 load = cdw.load
 
 # Set the download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/international_space_station_iss',
-                                    '/sp_fpmu/{year:4d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'ISS_SP_FPMU'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/jpl_gps.py` & `pysatNASA-0.0.5/pysatNASA/instruments/jpl_gps.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,15 @@
 # -*- coding: utf-8 -*-
 """Module for the JPL GPS data products.
 
+.. deprecated:: 0.0.5
+    This module is now included in igs_gps.py.
+    This instrument will be removed in 0.1.0+ to reduce redundancy.
+
+
 Supports ROTI data produced at JPL from International
 GNSS Service Total Electron Content (TEC)
 
 The rate of TEC index (ROTI) characterizes TEC fluctuations observed along
 receiver-to-satellite line of sight links over a 5-minute interval.
 The measurement is obtained by processing GNSS dual-frequency phase data and
 computing the standard deviation of the rate of TEC change over that interval
@@ -12,44 +17,47 @@
 
 ROTI data are provided as global maps using a 2.5 x 5 degree (geographic
 latitude x longitude) grid. The median ROTI value is calculated in each bin.
 GNSS data contributing to the ROTI computation are primarily collected from
 the global network of International GNSS Service and the regional network of
 Continuous Operating Reference Station (CORS).
 
-References
-----------
-Pi, X., A. J. Mannucci, U. J. Lindqwister, and C. M. Ho, Monitoring of global
-ionospheric irregularities using the worldwide GPS network, Geophys. Res.
-Lett., 24, 2283, 1997.
-
-Pi, X., F. J. Meyer, K. Chotoo, Anthony Freeman, R. G. Caton, and C. T.
-Bridgwood, Impact of ionospheric scintillation on Spaceborne SAR observations
-studied using GNSS, Proc. ION-GNSS, pp.1998-2006, 2012.
-
 
 Properties
 ----------
 platform
     'jpl'
 name
     'gps'
 tag
     ['roti']
 inst_id
     None supported
 
+
 Warnings
 --------
 - The cleaning parameters for the instrument are still under development.
 
+
+References
+----------
+Pi, X., A. J. Mannucci, U. J. Lindqwister, and C. M. Ho, Monitoring of global
+ionospheric irregularities using the worldwide GPS network, Geophys. Res.
+Lett., 24, 2283, 1997.
+
+Pi, X., F. J. Meyer, K. Chotoo, Anthony Freeman, R. G. Caton, and C. T.
+Bridgwood, Impact of ionospheric scintillation on Spaceborne SAR observations
+studied using GNSS, Proc. ION-GNSS, pp.1998-2006, 2012.
+
 """
 
 import datetime as dt
 import functools
+import warnings
 
 import pysat
 from pysat.instruments.methods import general as mm_gen
 
 from pysatNASA.instruments.methods import cdaweb as cdw
 from pysatNASA.instruments.methods import general as mm_nasa
 from pysatNASA.instruments.methods import gps as mm_gps
@@ -74,41 +82,44 @@
 def init(self):
     """Initialize the Instrument object with instrument specific values.
 
     Runs once upon instantiation.
 
     """
 
+    warnings.warn(" ".join(["The instrument module `jpl_gps` has",
+                            "been deprecated and will be removed in 0.1.0+."]),
+                  DeprecationWarning, stacklevel=2)
+
     pysat.logger.info('')
     self.acknowledgements = mm_gps.ackn_str
     self.references = '\n'.join((mm_gps.refs['mission'],
                                  mm_gps.refs['roti15min_jpl']))
 
     return
 
 
-# No cleaning, use standard warning function instead
-clean = mm_nasa.clean_warn
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
 fname = 'gps_roti15min_jpl_{year:4d}{month:02d}{day:02d}_v{version:02d}.cdf'
 supported_tags = {'': {'roti': fname}}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
 # Set the load routine
-load = functools.partial(cdw.load, pandas_format=pandas_format)
+load = functools.partial(cdw.load, pandas_format=pandas_format,
+                         use_cdflib=True)
 
 # Set the download routine
-basic_tag = {'remote_dir': '/pub/data/gps/roti15min_jpl/{year:4d}/',
-             'fname': fname}
-download_tags = {'': {'roti': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'roti': 'GPS_ROTI15MIN_JPL'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/_cdf.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/_cdf.py`

 * *Files 3% similar despite different names*

```diff
@@ -83,20 +83,26 @@
         # Registration names map from file params to kamodo-compatible names
         if regnames is None:
             regnames = {}
         self._regnames = regnames
 
         self._cdf_file = cdflib.CDF(self._filename)
         self._cdf_info = self._cdf_file.cdf_info()
+        self.global_attrs = self._cdf_file.globalattsget()
         self.data = {}
         self.meta = {}
         self._dependencies = {}
 
-        self._variable_names = (self._cdf_info['rVariables']
-                                + self._cdf_info['zVariables'])
+        if hasattr(self._cdf_info, 'rVariables'):
+            self._variable_names = (self._cdf_info.rVariables
+                                    + self._cdf_info.zVariables)
+        else:
+            # cdflib < 1.0 stores info as a dict
+            self._variable_names = (self._cdf_info['rVariables']
+                                    + self._cdf_info['zVariables'])
 
         self.load_variables()
 
     def __enter__(self):
         """Enter runtime context related to this object.
 
         The with statement will bind this method’s return value
@@ -152,16 +158,21 @@
         Parameters
         ----------
         x_axis_var : str
             name of variable
 
         """
 
-        data_type_description = self._cdf_file.varinq(
-            x_axis_var)['Data_Type_Description']
+        if hasattr(self._cdf_file.varinq(x_axis_var), 'Data_Type_Description'):
+            data_type_description = self._cdf_file.varinq(
+                x_axis_var).Data_Type_Description
+        else:
+            # cdflib < 1.0 stores this as a dict
+            data_type_description = self._cdf_file.varinq(
+                x_axis_var)['Data_Type_Description']
 
         center_measurement = self._center_measurement
         cdf_file = self._cdf_file
         if self.get_dependency(x_axis_var) is None:
             delta_plus_var = 0.0
             delta_minus_var = 0.0
             has_plus_minus = [False, False]
@@ -294,15 +305,20 @@
         varformat = varformat.replace("*", ".*")
         var_regex = re.compile(varformat)
 
         for variable_name in self._variable_names:
             if not re.match(var_regex, variable_name):
                 # Skip this variable
                 continue
-            var_atts = self._cdf_file.varattsget(variable_name, to_np=True)
+            try:
+                var_atts = self._cdf_file.varattsget(variable_name, to_np=True)
+            except TypeError:
+                # cdflib 1.0+ drops to_np kwarg, assumes True
+                var_atts = self._cdf_file.varattsget(variable_name)
+
             for k in var_atts:
                 var_atts[k] = var_atts[k]  # [0]
 
             if 'VAR_TYPE' not in var_atts:
                 continue
 
             if var_atts['VAR_TYPE'] not in self._var_types:
@@ -315,21 +331,22 @@
             except (TypeError):
                 continue
 
             if ydata is None:
                 continue
 
             if "FILLVAL" in var_atts:
-                if (var_properties['Data_Type_Description'] == 'CDF_FLOAT'
-                    or var_properties['Data_Type_Description']
-                    == 'CDF_REAL4'
-                    or var_properties['Data_Type_Description']
-                    == 'CDF_DOUBLE'
-                    or var_properties['Data_Type_Description']
-                        == 'CDF_REAL8'):
+                if hasattr(var_properties, 'Data_Type_Description'):
+                    data_type_desc = var_properties.Data_Type_Description
+                else:
+                    # cdflib < 1.0 stores this as a dict
+                    data_type_desc = var_properties['Data_Type_Description']
+
+                if data_type_desc in ['CDF_FLOAT', 'CDF_REAL4', 'CDF_DOUBLE',
+                                      'CDF_REAL8']:
 
                     if ydata[ydata == var_atts["FILLVAL"]].size != 0:
                         ydata[ydata == var_atts["FILLVAL"]] = np.nan
 
             index = self.get_index(variable_name)
 
             try:
@@ -356,17 +373,17 @@
                     raise
 
             self.meta[variable_name] = var_atts
 
     def to_pysat(self, flatten_twod=True,
                  labels={'units': ('Units', str), 'name': ('Long_Name', str),
                          'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
-                         'min_val': ('ValidMin', float),
-                         'max_val': ('ValidMax', float),
-                         'fill_val': ('FillVal', float)}):
+                         'min_val': ('ValidMin', (float, int, str)),
+                         'max_val': ('ValidMax', (float, int, str)),
+                         'fill_val': ('FillVal', (float, int, str))}):
         """Export loaded CDF data into data, meta for pysat module.
 
         Parameters
         ----------
         flatten_twod : bool
             If True, then two dimensional data is flattened across
             columns. Name mangling is used to group data, first column
@@ -378,17 +395,17 @@
 
         labels : dict
             Dict where keys are the label attribute names and the values
             are tuples that have the label values and value types in
             that order.
             (default={'units': ('units', str), 'name': ('long_name', str),
                       'notes': ('notes', str), 'desc': ('desc', str),
-                      'min_val': ('value_min', float),
-                      'max_val': ('value_max', float)
-                      'fill_val': ('fill', float)})
+                      'min_val': ('value_min', (float, int, str)),
+                      'max_val': ('value_max', (float, int, str))
+                      'fill_val': ('fill', (float, int, str))})
 
         Returns
         -------
         pandas.DataFrame, pysat.Meta
             Data and Metadata suitable for attachment to a pysat.Instrument
             object.
 
@@ -403,15 +420,15 @@
         in *_labels even if the case does not match.
 
         """
         # Create pysat.Meta object using data above
         # and utilizing the attribute labels provided by the user
         meta = pysat.Meta(pds.DataFrame.from_dict(self.meta, orient='index'),
                           labels=labels)
-
+        meta.header = pysat.MetaHeader(header_data=self.global_attrs)
         cdata = self.data.copy()
         lower_names = [name.lower() for name in meta.keys()]
         for name, true_name in zip(lower_names, meta.keys()):
             if name == 'epoch':
                 meta.data.rename(index={true_name: 'epoch'}, inplace=True)
                 epoch = cdata.pop(true_name)
                 cdata['Epoch'] = epoch
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/cdaweb.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/cdaweb.py`

 * *Files 15% similar despite different names*

```diff
@@ -3,42 +3,79 @@
 
 Note
 ----
 Adding new CDAWeb datasets should only require mininal user intervention.
 
 """
 
-import cdflib
 import datetime as dt
+import numpy as np
 import os
 import pandas as pds
 import requests
-import warnings
+from time import sleep
 import xarray as xr
 
 from bs4 import BeautifulSoup
+from cdasws import CdasWs
 
 import pysat
 from pysat.instruments.methods import general
 from pysat import logger
 from pysat.utils import files as futils
 from pysat.utils import io
 from pysatNASA.instruments.methods import CDF as libCDF
 
 try:
+    # cdflib 1.0 syntax
+    from cdflib.xarray import cdf_to_xarray
+except ModuleNotFoundError:
+    # cdflib 0.4 syntax required for backwards compatibility
+    from cdflib import cdf_to_xarray
+
+try:
     import pysatCDF
     auto_CDF = pysatCDF.CDF
 except ImportError:
     auto_CDF = libCDF
 
 
+def try_inst_dict(inst_id, tag, supported_tags):
+    """Check that the inst_id and tag combination is valid.
+
+    Parameters
+    ----------
+    tag : str
+        Data product tag (default='')
+    inst_id : str
+        Instrument ID (default='')
+    supported_tags : dict
+        dict of dicts. Keys are supported tag names for download. Value is
+        a dict with 'remote_dir', 'fname'. Inteded to be
+        pre-set with functools.partial then assigned to new instrument code.
+        (default=None)
+
+    Returns
+    -------
+    inst_dict : dict or str
+        dictionary containing file location in spdf archive, or dataset ID for
+        cdasws
+    """
+    try:
+        inst_dict = supported_tags[inst_id][tag]
+    except KeyError:
+        raise ValueError('inst_id / tag combo unknown.')
+
+    return inst_dict
+
+
 def load(fnames, tag='', inst_id='', file_cadence=dt.timedelta(days=1),
          flatten_twod=True, pandas_format=True, epoch_name='Epoch',
-         meta_processor=None, meta_translation=None, drop_meta_labels=None,
-         use_cdflib=None):
+         drop_dims=None, var_translation=None, meta_processor=None,
+         meta_translation=None, drop_meta_labels=None, use_cdflib=None):
     """Load NASA CDAWeb CDF files.
 
     Parameters
     ----------
     fnames : pandas.Series
         Series of filenames
     tag : str
@@ -58,14 +95,21 @@
         xarray Dataset (False). (default=True)
     epoch_name : str or NoneType
         Data key for epoch variable.  The epoch variable is expected to be an
         array of integer or float values denoting time elapsed from an origin
         specified by `epoch_origin` with units specified by `epoch_unit`. This
         epoch variable will be converted to a `DatetimeIndex` for consistency
         across pysat instruments.  (default='Epoch')
+    drop_dims : list or NoneType
+        List of variable dimensions that should be dropped. Applied
+        to data as loaded from the file. Used only from xarray Dataset.
+        (default=None)
+    var_translation : dict or NoneType
+        Variables that should be renamed. Applied to data as loaded
+        from the file. Used only from xarray Dataset. (default=None)
     meta_processor : function or NoneType
         If not None, a dict containing all of the loaded metadata will be
         passed to `meta_processor` which should return a filtered version
         of the input dict. The returned dict is loaded into a pysat.Meta
         instance and returned as `meta`. (default=None)
     meta_translation : dict or NoneType
         Translation table used to map metadata labels in the file to
@@ -89,31 +133,36 @@
     data : pandas.DataFrame
         Object containing satellite data
     meta : pysat.Meta
         Object containing metadata such as column names and units
 
     Note
     ----
-    This routine is intended to be used by pysat instrument modules supporting
-    a particular NASA CDAWeb dataset
+    - This routine is intended to be used by pysat instrument modules supporting
+      a particular NASA CDAWeb dataset
+    - pysatCDF (as of v0.3.2) does not support numpy>=1.24.  Load errors may
+      arise.  See https://github.com/pysat/pysatCDF/issues/46
 
     """
 
     if pandas_format:
         data, meta = load_pandas(fnames, tag=tag, inst_id=inst_id,
                                  file_cadence=file_cadence,
                                  flatten_twod=flatten_twod,
                                  use_cdflib=use_cdflib)
     else:
         if not use_cdflib:
             estr = 'The `use_cdflib` option is not currently enabled for xarray'
-            warnings.warn(estr)
+            pysat.logger.warn(estr)
 
         data, meta = load_xarray(fnames, tag=tag, inst_id=inst_id,
                                  epoch_name=epoch_name,
+                                 drop_dims=drop_dims,
+                                 var_translation=var_translation,
+                                 file_cadence=file_cadence,
                                  meta_processor=meta_processor,
                                  meta_translation=meta_translation,
                                  drop_meta_labels=drop_meta_labels)
     return data, meta
 
 
 def load_pandas(fnames, tag='', inst_id='', file_cadence=dt.timedelta(days=1),
@@ -220,47 +269,58 @@
         if len(ldata) > 0:
             data = pds.concat(ldata)
 
         return data, meta
 
 
 def load_xarray(fnames, tag='', inst_id='',
-                labels={'units': ('units', str), 'name': ('long_name', str),
-                        'notes': ('notes', str), 'desc': ('desc', str),
-                        'plot': ('plot_label', str), 'axis': ('axis', str),
-                        'scale': ('scale', str),
-                        'min_val': ('value_min', float),
-                        'max_val': ('value_max', float),
-                        'fill_val': ('fill', float)},
-                epoch_name='Epoch', meta_processor=None,
-                meta_translation=None, drop_meta_labels=None):
+                file_cadence=dt.timedelta(days=1),
+                labels={'units': ('Units', str), 'name': ('Long_Name', str),
+                        'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
+                        'min_val': ('ValidMin', (float, int, str)),
+                        'max_val': ('ValidMax', (float, int, str)),
+                        'fill_val': ('FillVal', (float, int, str))},
+                epoch_name='Epoch', drop_dims=None, var_translation=None,
+                meta_processor=None, meta_translation=None,
+                drop_meta_labels=None):
     """Load NASA CDAWeb CDF files into an xarray Dataset.
 
     Parameters
     ----------
     fnames : pandas.Series
         Series of filenames
     tag : str
         Data product tag (default='')
     inst_id : str
         Instrument ID (default='')
+    file_cadence : dt.timedelta or pds.DateOffset
+        pysat assumes a daily file cadence, but some instrument data files
+        contain longer periods of time.  This parameter allows the specification
+        of regular file cadences greater than or equal to a day (e.g., weekly,
+        monthly, or yearly). (default=dt.timedelta(days=1))
     labels : dict
         Dict where keys are the label attribute names and the values are tuples
         that have the label values and value types in that order.
-        (default={'units': ('units', str), 'name': ('long_name', str),
-        'notes': ('notes', str), 'desc': ('desc', str),
-        'min_val': ('value_min', np.float64),
-        'max_val': ('value_max', np.float64),
-        'fill_val': ('fill', np.float64)})
+        (default={'units': ('Units', str), 'name': ('Long_Name', str),
+        'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
+        'min_val': ('ValidMin', (float, int, str)),
+        'max_val': ('ValidMax', (float, int, str)),
+        'fill_val': ('FillVal', (float, int, str))})
     epoch_name : str
         Data key for epoch variable.  The epoch variable is expected to be an
         array of integer or float values denoting time elapsed from an origin
         specified by `epoch_origin` with units specified by `epoch_unit`. This
         epoch variable will be converted to a `DatetimeIndex` for consistency
         across pysat instruments.  (default='Epoch')
+    drop_dims : list or NoneType
+        List of variable dimensions that should be dropped. Applied
+        to data as loaded from the file. (default=None)
+    var_translation : dict or NoneType
+        Variables that should be renamed. Applied to data as loaded
+        from the file. Used only from xarray Dataset. (default=None)
     meta_processor : function or NoneType
         If not None, a dict containing all of the loaded metadata will be
         passed to `meta_processor` which should return a filtered version
         of the input dict. The returned dict is loaded into a pysat.Meta
         instance and returned as `meta`. (default=None)
     meta_translation : dict or NoneType
         Translation table used to map metadata labels in the file to
@@ -304,41 +364,35 @@
     if len(fnames) <= 0:
         return xr.Dataset()
     else:
         # Using cdflib wrapper to load the CDF and format data and
         # metadata for pysat using some assumptions. Depending upon your needs
         # the resulting pandas DataFrame may need modification.
         ldata = []
-        for lfname in fnames:
-            temp_data = cdflib.cdf_to_xarray(lfname, to_datetime=True)
-            ldata.append(temp_data)
-
-        # Combine individual files together
-        if len(ldata) > 0:
-            data = xr.combine_by_coords(ldata)
 
-    all_vars = io.xarray_all_vars(data)
+        # Find unique files for monthly / yearly cadence.
+        # Arbitrary timestamp needed for comparison.
+        t0 = dt.datetime(2009, 1, 1)
+        if (t0 + file_cadence) > (t0 + dt.timedelta(days=1)):
+            lfnames = list(np.unique([fname[:-11] for fname in fnames]))
+        else:
+            lfnames = fnames
 
-    # Convert output epoch name to 'time' for pysat consistency
-    if epoch_name != 'time':
-        if 'time' not in all_vars:
-            if epoch_name in data.dims:
-                data = data.rename({epoch_name: 'time'})
-            elif epoch_name in all_vars:
-                data = data.rename({epoch_name: 'time'})
-                wstr = ''.join(['Epoch label: "', epoch_name, '"',
-                                ' is not a dimension.'])
-                pysat.logger.warning(wstr)
-            else:
-                estr = ''.join(['Epoch label: "', epoch_name, '"',
-                                ' not found in loaded data, ',
-                                repr(all_vars)])
-                raise ValueError(estr)
+        for lfname in lfnames:
+            temp_data = cdf_to_xarray(lfname, to_datetime=True)
+            if drop_dims:
+                temp_data = temp_data.drop_dims(drop_dims)
+            if var_translation:
+                temp_data = temp_data.rename(var_translation)
+            ldata.append(temp_data)
 
-        epoch_name = 'time'
+        # Combine individual files together, concat along epoch
+        if len(ldata) > 0:
+            data = xr.combine_nested(ldata, epoch_name,
+                                     combine_attrs='override')
 
     all_vars = io.xarray_all_vars(data)
 
     meta = pysat.Meta(labels=labels)
 
     full_mdict = {}
 
@@ -386,87 +440,112 @@
     # labels
     filt_mdict = io.meta_array_expander(filt_mdict)
 
     # Assign filtered metadata to pysat.Meta instance
     for key in filt_mdict:
         meta[key] = filt_mdict[key]
 
+    # Convert output epoch name to 'time' for pysat consistency
+    # This needs to be done last so that meta is updated properly
+    if epoch_name != 'time':
+        if 'time' not in all_vars:
+            if epoch_name in data.dims:
+                data = data.rename({epoch_name: 'time'})
+            elif epoch_name in all_vars:
+                data = data.rename({epoch_name: 'time'})
+                wstr = ''.join(['Epoch label: "', epoch_name, '"',
+                                ' is not a dimension.'])
+                pysat.logger.warning(wstr)
+            else:
+                estr = ''.join(['Epoch label: "', epoch_name, '"',
+                                ' not found in loaded data, ',
+                                repr(all_vars)])
+                raise ValueError(estr)
+
+        epoch_name = 'time'
+
     # Remove attributes from the data object
     data.attrs = {}
 
     return data, meta
 
 
-def download(date_array, tag='', inst_id='', supported_tags=None,
-             remote_url='https://cdaweb.gsfc.nasa.gov', data_path=None):
-    """Download NASA CDAWeb CDF data.
+# TODO(#103): Include support to unzip / untar files after download.
+def download(date_array, data_path, tag='', inst_id='', supported_tags=None,
+             remote_url='https://cdaweb.gsfc.nasa.gov'):
+    """Download NASA CDAWeb data.
 
     This routine is intended to be used by pysat instrument modules supporting
     a particular NASA CDAWeb dataset.
 
     Parameters
     ----------
     date_array : array-like
         Array of datetimes to download data for. Provided by pysat.
+    data_path : str
+        Path to data directory.
     tag : str
         Data product tag (default='')
     inst_id : str
         Instrument ID (default='')
     supported_tags : dict
         dict of dicts. Keys are supported tag names for download. Value is
         a dict with 'remote_dir', 'fname'. Inteded to be pre-set with
         functools.partial then assigned to new instrument code.
         (default=None)
     remote_url : str
         Remote site to download data from
         (default='https://cdaweb.gsfc.nasa.gov')
-    data_path : str or NoneType
-        Path to data directory.  If None is specified, the value previously
-        set in Instrument.files.data_path is used.  (default=None)
 
     Examples
     --------
     ::
 
-        # download support added to cnofs_vefi.py using code below
+        # Download support added to cnofs_vefi.py using code below
         fn = 'cnofs_vefi_bfield_1sec_{year:4d}{month:02d}{day:02d}_v05.cdf'
         dc_b_tag = {'remote_dir': ''.join(('/pub/data/cnofs/vefi/bfield_1sec',
                                             '/{year:4d}/')),
                     'fname': fn}
         supported_tags = {'dc_b': dc_b_tag}
 
         download = functools.partial(nasa_cdaweb.download,
                                      supported_tags=supported_tags)
 
     """
 
-    try:
-        inst_dict = supported_tags[inst_id][tag]
-    except KeyError:
-        raise ValueError('inst_id / tag combo unknown.')
+    inst_dict = try_inst_dict(inst_id, tag, supported_tags)
 
     # Naming scheme for files on the CDAWeb server
     remote_dir = inst_dict['remote_dir']
 
     # Get list of files from server
     remote_files = list_remote_files(tag=tag, inst_id=inst_id,
                                      remote_url=remote_url,
                                      supported_tags=supported_tags,
                                      start=date_array[0],
                                      stop=date_array[-1])
 
     # Download only requested files that exist remotely
     for date, fname in remote_files.items():
         # Format files for specific dates and download location
-        formatted_remote_dir = remote_dir.format(year=date.year,
-                                                 month=date.month,
-                                                 day=date.day,
-                                                 hour=date.hour,
-                                                 min=date.minute,
-                                                 sec=date.second)
+        # Year and day found in remote_dir: day is assumed to be day of year
+        if 'day' in remote_dir and 'month' not in remote_dir:
+            doy = date.timetuple().tm_yday
+            formatted_remote_dir = remote_dir.format(year=date.year,
+                                                     day=doy,
+                                                     hour=date.hour,
+                                                     min=date.minute,
+                                                     sec=date.second)
+        else:
+            formatted_remote_dir = remote_dir.format(year=date.year,
+                                                     month=date.month,
+                                                     day=date.day,
+                                                     hour=date.hour,
+                                                     min=date.minute,
+                                                     sec=date.second)
         remote_path = '/'.join((remote_url.strip('/'),
                                 formatted_remote_dir.strip('/'),
                                 fname))
 
         saved_local_fname = os.path.join(data_path, fname)
 
         # Perform download
@@ -481,14 +560,112 @@
                         saved_local_fname))
                 else:
                     logger.info(' '.join(('File not available for',
                                           date.strftime('%d %B %Y'))))
         except requests.exceptions.RequestException as exception:
             logger.info(' '.join((str(exception), '- File not available for',
                                   date.strftime('%d %B %Y'))))
+        # Pause to avoid excessive pings to server
+        sleep(0.2)
+    return
+
+
+def cdas_download(date_array, data_path, tag='', inst_id='',
+                  supported_tags=None):
+    """Download NASA CDAWeb CDF data using cdasws.
+
+    This routine is intended to be used by pysat instrument modules supporting
+    a particular NASA CDAWeb dataset.
+
+    Parameters
+    ----------
+    date_array : array-like
+        Array of datetimes to download data for. Provided by pysat.
+    data_path : str
+        Path to data directory.
+    tag : str
+        Data product tag (default='')
+    inst_id : str
+        Instrument ID (default='')
+    supported_tags : dict
+        dict of dicts. Keys are supported tag names for download. Value is
+        a dict with 'remote_dir', 'fname'. Inteded to be pre-set with
+        functools.partial then assigned to new instrument code.
+        (default=None)
+
+    Note
+    ----
+    Supported tags for this function use the cdaweb dataset naming convention.
+    You can find the data set names on CDAWeb or you can use cdasws.
+
+    Starting from scratch using cdasws
+    ::
+        from cdasws import CdasWs
+        cdas = CdasWs()
+
+        # Get list of available observatories/platforms.
+        cdas.get_observatories()
+
+        # Once your observatory is located, list the available instruments.
+        cdas.get_instruments(observatory=‘observatory_name’)
+
+        # Now list the available data sets for one instrument.
+        cdas.get_datasets(observatory=‘observatory_name’,
+                          instrument=‘instrument_name’)
+
+        # You can also list all of the datasets for an observatory.
+        cdas.get_datasets(observatory=‘observatory_name’)
+
+    Alternatively
+    ::
+        Visit https://cdaweb.gsfc.nasa.gov/
+        Select the observatory you want from the list and press submit.
+        The following page will have a list of the data sets.
+        The bolded names are in the format that cdasws uses.
+
+    Examples
+    --------
+    ::
+        # Download support added to cnofs_vefi.py using code below
+        download_tags = {'': {'dc_b': 'CNOFS_VEFI_BFIELD_1SEC'}}
+        download = functools.partial(cdw.cdas_download,
+                                     supported_tags=download_tags)
+
+    """
+
+    start = date_array[0]
+    stop = date_array[-1]
+    remote_files = cdas_list_remote_files(tag=tag, inst_id=inst_id,
+                                          start=start, stop=stop,
+                                          supported_tags=supported_tags,
+                                          series_out=False)
+
+    for file in remote_files:
+
+        fname = file.split('/')[-1]
+        saved_local_fname = os.path.join(data_path, fname)
+
+        # Perform download
+        logger.info(' '.join(('Attempting to download file: ',
+                              file)))
+        try:
+            with requests.get(file) as req:
+                if req.status_code != 404:
+                    with open(saved_local_fname, 'wb') as open_f:
+                        open_f.write(req.content)
+                    logger.info('Successfully downloaded {:}.'.format(
+                        saved_local_fname))
+                else:
+                    logger.info(' '.join(('File: "', file,
+                                          '" is not available')))
+        except requests.exceptions.RequestException as exception:
+            logger.info(' '.join((str(exception), '- File: "', file,
+                                  '" Is not available')))
+        # Pause to avoid excessive pings to server
+        sleep(0.2)
     return
 
 
 def list_remote_files(tag='', inst_id='', start=None, stop=None,
                       remote_url='https://cdaweb.gsfc.nasa.gov',
                       supported_tags=None, two_digit_year_break=None,
                       delimiter=None):
@@ -547,18 +724,15 @@
         supported_tags = {'': fname}
         list_remote_files = \
             functools.partial(cdw.list_remote_files,
                               supported_tags=supported_tags)
 
     """
 
-    try:
-        inst_dict = supported_tags[inst_id][tag]
-    except KeyError:
-        raise ValueError('inst_id / tag combo unknown.')
+    inst_dict = try_inst_dict(inst_id, tag, supported_tags)
 
     # Naming scheme for files on the CDAWeb server
     format_str = '/'.join((inst_dict['remote_dir'].strip('/'),
                            inst_dict['fname']))
 
     # Break string format into path and filename
     dir_split = os.path.split(format_str)
@@ -595,26 +769,35 @@
         # Use the topmost directory without variables
         url_list = ['/'.join((remote_url,
                               search_dir['string_blocks'][0]))]
     elif start is not None:
         stop = dt.datetime.now() if (stop is None) else stop
 
         if 'year' in search_dir['keys']:
+            url_list = []
             if 'month' in search_dir['keys']:
                 search_times = pds.date_range(start,
                                               stop + pds.DateOffset(months=1),
                                               freq='M')
+                for time in search_times:
+                    subdir = format_dir.format(year=time.year, month=time.month)
+                    url_list.append('/'.join((remote_url, subdir)))
             else:
-                search_times = pds.date_range(start,
-                                              stop + pds.DateOffset(years=1),
-                                              freq='Y')
-            url_list = []
-            for time in search_times:
-                subdir = format_dir.format(year=time.year, month=time.month)
-                url_list.append('/'.join((remote_url, subdir)))
+                if 'day' in search_dir['keys']:
+                    search_times = pds.date_range(start, stop
+                                                  + pds.DateOffset(days=1),
+                                                  freq='D')
+                else:
+                    search_times = pds.date_range(start, stop
+                                                  + pds.DateOffset(years=1),
+                                                  freq='Y')
+                for time in search_times:
+                    doy = int(time.strftime('%j'))
+                    subdir = format_dir.format(year=time.year, day=doy)
+                    url_list.append('/'.join((remote_url, subdir)))
     try:
         for top_url in url_list:
             for level in range(n_layers + 1):
                 for directory in remote_dirs[level]:
                     temp_url = '/'.join((top_url.strip('/'), directory))
                     soup = BeautifulSoup(requests.get(temp_url).content,
                                          "lxml")
@@ -650,7 +833,86 @@
         mask = (stored_list.index >= start)
         if stop is not None:
             stop_point = (stop + pds.DateOffset(days=1))
             mask = mask & (stored_list.index < stop_point)
         stored_list = stored_list[mask]
 
     return stored_list
+
+
+def cdas_list_remote_files(tag='', inst_id='', start=None, stop=None,
+                           supported_tags=None, series_out=True):
+    """Return a list of every file for chosen remote data.
+
+    This routine is intended to be used by pysat instrument modules supporting
+    a particular NASA CDAWeb dataset.
+
+    Parameters
+    ----------
+    tag : str
+        Data product tag (default='')
+    inst_id : str
+        Instrument ID (default='')
+    start : dt.datetime or NoneType
+        Starting time for file list. A None value will start with the first
+        file found.
+        (default=None)
+    stop : dt.datetime or NoneType
+        Ending time for the file list.  A None value will stop with the last
+        file found.
+        (default=None)
+    supported_tags : dict
+        dict of dicts. Keys are supported tag names for download. Value is
+        a dict with 'remote_dir', 'fname'. Inteded to be
+        pre-set with functools.partial then assigned to new instrument code.
+        (default=None)
+    series_out : bool
+        boolean to determine output type. True for pandas series of file names,
+        and False for a list of the full web address.
+
+    Returns
+    -------
+    file_list : list
+        A list containing the verified available files
+
+    Note
+    ----
+    Supported tags for this function use the cdaweb dataset naming convention.
+    You can find the dataset names on cdaweb or you can use cdasws.
+
+    Examples
+    --------
+    ::
+        download_tags = {'': {'dc_b': 'CNOFS_VEFI_BFIELD_1SEC'}}
+        list_remote_files = functools.partial(cdw.cdas_list_remote_files,
+                                              supported_tags=download_tags)
+
+        download_tags = {'': {'': 'CNOFS_CINDI_IVM_500MS'}}
+        list_remote_files = functools.partial(cdw.cdas_list_remote_files,
+                                              supported_tags=download_tags)
+    """
+    cdas = CdasWs()
+    dataset = try_inst_dict(inst_id, tag, supported_tags)
+
+    if start is None and stop is None:
+        # Use the topmost directory without variables
+        start = cdas.get_inventory(identifier=dataset)[0].start
+        stop = cdas.get_inventory(identifier=dataset)[-1].end
+    elif stop is None:
+        stop = start + dt.timedelta(days=1)
+    elif start == stop:
+        stop = start + dt.timedelta(days=1)
+
+    if isinstance(start, pds._libs.tslibs.timestamps.Timestamp):
+        start = start.tz_localize('utc')
+        stop = stop.tz_localize('utc')
+
+    og_files = cdas.get_original_files(dataset=dataset, start=start, end=stop)
+
+    if series_out:
+        name_list = [os.path.basename(f['Name']) for f in og_files[1]]
+        t_stamp = [pds.Timestamp(f['StartTime'][:10]) for f in og_files[1]]
+        file_list = pds.Series(data=name_list, index=t_stamp)
+    else:
+        file_list = [f['Name'] for f in og_files[1]]
+
+    return file_list
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/cnofs.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/cnofs.py`

 * *Files identical despite different names*

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/de2.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/de2.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,23 +1,34 @@
 # -*- coding: utf-8 -*-
 """Provides non-instrument specific routines for DE2 data."""
 
 ackn_str = "The Dynamics Explorer 2 satellite data is provided through CDAWeb"
 
-refs = {'lang': ' '.join(('J. P. Krehbiel, L. H. Brace, R. F. Theis, W. H.',
+refs = {'fpi': ' '.join(('Hays, P B, Killeen, T L, and Kennedy, B C.',
+                         '"Fabry-Perot interferometer on Dynamics Explorer".',
+                         'Space Sci. Instrum., v. 5, p. 395-416, 1981.')),
+        'lang': ' '.join(('J. P. Krehbiel, L. H. Brace, R. F. Theis, W. H.',
                           'Pinkus, and R. B. Kaplan, The Dynamics Explorer 2',
                           'Langmuir Probe (LANG), Space Sci. Instrum., v. 5,',
                           'n. 4, p. 493, 1981.')),
         'nacs': ' '.join(('G. R. Carrignan, B. P. Block, J. C. Maurer,  A. E.',
                           'Hedin, C. A. Reber, N. W. Spencer, The neutral mass',
                           'spectrometer on Dynamics Explorer B, Space Sci.',
                           'Instrum., v. 5, n. 4, p. 429, 1981.')),
         'rpa': ' '.join(('W. B. Hanson, R. A. Heelis, R. A. Power, C. R.',
                          'Lippincott, D. R. Zuccaro, B. J. Holt, L. H. Harmon,',
                          'and S. Sanatani, The retarding potential analyzer',
                          'for dynamics explorer-B, Space Sci. Instrum. 5,',
-                         '503–510 (1981).')),
+                         '503–510 (1981).\n',
+                         'Heelis, R. A., W. B. Hanson, C. R. Lippincott, D. R.',
+                         'Zuccaro, L. L. Harmon, B. J. Holt, J. E. Doherty, R.',
+                         'A. Power, The ion drift meter for Dynamics',
+                         'Explorer-B, Space Sci. Instrum., 5, 511, 1981.')),
         'wats': ' '.join(('N. W. Spencer, L. E. Wharton, H. B. Niemann, A. E.',
                           'Hedin, G. R. Carrignan, J. C. Maurer, The',
                           'Dynamics Explorer Wind and Temperature Spectrometer',
-                          'Space Sci. Instrum., v. 5, n. 4, p. 417, 1981.'))
+                          'Space Sci. Instrum., v. 5, n. 4, p. 417, 1981.')),
+        'vefi': ' '.join(('Maynard, N. C., E. A. Bielecki, H. G. Burdick,',
+                          'Instrumentation for vector electric field',
+                          'measurements from DE-B, Space Sci. Instrum., 5,',
+                          '523, 1981.'))
         }
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/gold.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/ses14.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,24 +1,24 @@
 # -*- coding: utf-8 -*-
-"""Provides non-instrument specific routines for GOLD data."""
+"""Provides non-instrument specific routines for SES14 instruments."""
 
-ack_str = ' '.join(('This is a data product from the NASA Global-scale',
-                    'Observations of the Limb and Disk (GOLD) mission, an',
-                    'Heliophysics Explorer mission of opportunity launched',
-                    'in January 2018.\n Responsibility of the mission',
-                    'science falls to the Principal Investigator, Dr.',
-                    'Richard Eastes at University of Colorado/LASP.\n',
-                    'Validation of the L1B data products falls to the',
-                    'instrument lead investigators/scientists.\n* EUV',
-                    'Dr. Bill McClintock\nValidation of the L2 data',
-                    'products falls to Computational Physics, Inc.\n* Dr.',
-                    'Jerry Lumpe\n (https://gold.cs.ucf.edu/).\nOverall',
-                    'validation of the products is overseen by the GOLD',
-                    'Project Scientist Dr. Alan Burns.\nUsers of these',
-                    'data should contact and acknowledge the Principal',
-                    'Investigator Dr. Richard Eastes and the party',
-                    'directly responsible for the data product and the',
-                    'NASA Explorers Project Office.'))
-ref_str = ' '.join(('Eastes, R.W., McClintock, W.E., Burns, A.G. et al.',
-                    'The Global-Scale Observations of the Limb and Disk',
-                    '(GOLD) Mission. Space Sci Rev 212, 383–408 (2017).',
-                    'https://doi.org/10.1007/s11214-017-0392-2'))
+ackn_str = ' '.join(('This is a data product from the NASA Global-scale',
+                     'Observations of the Limb and Disk (GOLD) mission, an',
+                     'Heliophysics Explorer mission of opportunity launched',
+                     'in January 2018.\n Responsibility of the mission',
+                     'science falls to the Principal Investigator, Dr.',
+                     'Richard Eastes at University of Colorado/LASP.\n',
+                     'Validation of the L1B data products falls to the',
+                     'instrument lead investigators/scientists.\n* EUV',
+                     'Dr. Bill McClintock\nValidation of the L2 data',
+                     'products falls to Computational Physics, Inc.\n* Dr.',
+                     'Jerry Lumpe\n (https://gold.cs.ucf.edu/).\nOverall',
+                     'validation of the products is overseen by the GOLD',
+                     'Project Scientist Dr. Alan Burns.\nUsers of these',
+                     'data should contact and acknowledge the Principal',
+                     'Investigator Dr. Richard Eastes and the party',
+                     'directly responsible for the data product and the',
+                     'NASA Explorers Project Office.'))
+refs = {'gold': ' '.join(('Eastes, R.W., McClintock, W.E., Burns, A.G. et',
+                          'al., The Global-Scale Observations of the Limb',
+                          'and Disk (GOLD) Mission. Space Sci Rev 212,',
+                          '383–408 (2017). doi:10.1007/s11214-017-0392-2'))}
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/gps.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/gps.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,9 +1,15 @@
 # -*- coding: utf-8 -*-
-"""Provides non-instrument specific routines for JPL ROTI data."""
+"""Provides non-instrument specific routines for JPL ROTI data.
+
+.. deprecated:: 0.0.5
+    This module is now included in `methods.igs`.
+    This instrument will be removed in 0.1.0+ to reduce redundancy.
+
+"""
 
 ackn_str = ' '.join(("The GPS Total Electron Content (TEC) data",
                      "produced by the International Global Navigation",
                      "Satellite Systems Service (IGS) Ionosphere Working",
                      "Group is provided through CDAWeb"))
 
 refs = {'mission': ' '.join(('Feltens J, Schaer S (1998) IGS Products for the',
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/icon.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/icon.py`

 * *Files identical despite different names*

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/methods/omni.py` & `pysatNASA-0.0.5/pysatNASA/instruments/methods/omni.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 # -*- coding: utf-8 -*-
 """Module for the OMNI HRO supporting functions."""
 
 
 import numpy as np
 import pandas as pds
 from scipy import stats
-import warnings
 
-from pysat import logger
+import pysat
 
 
 def time_shift_to_magnetic_poles(inst):
     """Shift OMNI times to intersection with the magnetic pole.
 
     Parameters
     ----------
@@ -42,16 +41,16 @@
 
     # Make sure there are no gaps larger than a minute.
     inst.data = inst.data.resample('1T').interpolate('time')
 
     time_x = inst['BSN_x'] * 6371.2 / -inst['Vx']
     idx, = np.where(np.isnan(time_x))
     if len(idx) > 0:
-        logger.info(time_x[idx])
-        logger.info(time_x)
+        pysat.logger.info(time_x[idx])
+        pysat.logger.info(time_x)
     time_x_offset = [pds.DateOffset(seconds=time)
                      for time in time_x.astype(int)]
     new_index = []
     for i, time in enumerate(time_x_offset):
         new_index.append(inst.data.index[i] + time)
     inst.data.index = new_index
     inst.data = inst.data.sort_index()
@@ -111,16 +110,18 @@
 
     # We are not going to interpolate through missing values
     rates = {'': 1, '1min': 1, '5min': 5}
     sample_rate = int(rates[inst.tag])
     max_wnum = np.floor(steady_window / sample_rate)
     if max_wnum != steady_window / sample_rate:
         steady_window = max_wnum * sample_rate
-        logger.warning("sample rate is not a factor of the statistical window")
-        logger.warning("new statistical window is {:.1f}".format(steady_window))
+        pysat.logger.warning(" ".join(("sample rate is not a factor of the",
+                                       "statistical window")))
+        pysat.logger.warning(" ".join(("new statistical window is",
+                                       "{:.1f}".format(steady_window))))
 
     min_wnum = int(np.ceil(max_wnum * min_window_frac))
 
     # Calculate the running coefficient of variation of the BYZ magnitude
     byz_mean = inst['BYZ_GSM'].rolling(min_periods=min_wnum, center=True,
                                        window=steady_window).mean()
     byz_std = inst['BYZ_GSM'].rolling(min_periods=min_wnum, center=True,
@@ -133,17 +134,17 @@
         ca_std = \
             inst['clock_angle'].rolling(min_periods=min_wnum,
                                         window=steady_window,
                                         center=True).apply(stats.circstd,
                                                            kwargs=circ_kwargs,
                                                            raw=True)
     except TypeError:
-        warnings.warn(' '.join(['To automatically remove NaNs from the',
-                                'calculation, please upgrade to scipy 1.4 or',
-                                'newer']))
+        pysat.logger.warn(' '.join(['To automatically remove NaNs from the',
+                                    'calculation, please upgrade to scipy 1.4',
+                                    'or newer.']))
         circ_kwargs.pop('nan_policy')
         ca_std = \
             inst['clock_angle'].rolling(min_periods=min_wnum,
                                         window=steady_window,
                                         center=True).apply(stats.circstd,
                                                            kwargs=circ_kwargs,
                                                            raw=True)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/omni_hro.py` & `pysatNASA-0.0.5/pysatNASA/instruments/omni_hro.py`

 * *Files 11% similar despite different names*

```diff
@@ -40,17 +40,16 @@
 
 import datetime as dt
 import functools
 import numpy as np
 import pandas as pds
 import warnings
 
+import pysat
 from pysat.instruments.methods import general as mm_gen
-from pysat import logger
-from pysat.utils import time as pysat_time
 
 from pysatNASA.instruments.methods import cdaweb as cdw
 from pysatNASA.instruments.methods import omni as mm_omni
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
@@ -82,15 +81,15 @@
     self.acknowledgements = ackn_str
     self.references = ' '.join(('J.H. King and N.E. Papitashvili, Solar',
                                 'wind spatial scales in and comparisons',
                                 'of hourly Wind and ACE plasma and',
                                 'magnetic field data, J. Geophys. Res.,',
                                 'Vol. 110, No. A2, A02209,',
                                 '10.1029/2004JA010649.'))
-    logger.info(ackn_str)
+    pysat.logger.info(ackn_str)
     return
 
 
 def clean(self):
     """Clean OMNI HRO data to the specified level.
 
     Note
@@ -136,67 +135,20 @@
 supported_tags = {inst_id: {tag: fname.format(tag=tag) for tag in tags.keys()}
                   for inst_id in inst_ids.keys()}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags,
                                file_cadence=pds.DateOffset(months=1))
 
 # Set the list_remote_files routine
-remote_dir = '/pub/data/omni/omni_cdaweb/hro_{tag:s}/{{year:4d}}/'
-download_tags = {inst_id: {tag: {'remote_dir': remote_dir.format(tag=tag),
-                                 'fname': supported_tags[inst_id][tag]}
-                           for tag in tags.keys()}
-                 for inst_id in inst_ids.keys()}
-list_remote_files = functools.partial(cdw.list_remote_files,
-                                      supported_tags=download_tags)
-
-
-# Set the download routine
-def download(date_array, tag, inst_id, data_path, update_files=False):
-    """Download OMNI HRO data from CDAWeb.
-
-    Parameters
-    ----------
-    date_array : array-like
-        Sequence of dates for which files will be downloaded.
-    tag : str
-        Denotes type of file to load.
-    inst_id : str
-        Specifies the satellite ID for a constellation.
-    data_path : str
-        Path to data directory.
-    update_files : bool
-        Re-download data for files that already exist if True (default=False)
-
-    Raises
-    ------
-    IOError
-        If a problem is encountered connecting to the gateway or retrieving
-        data from the repository.
-
-    Warnings
-    --------
-    Only able to download current forecast data, not archived forecasts.
-
-    Note
-    ----
-    Called by pysat. Not intended for direct use by user.
+download_tags = {'': {'1min': 'OMNI_HRO_1MIN', '5min': 'OMNI_HRO_5MIN'}}
+download = functools.partial(cdw.cdas_download,
+                             supported_tags=download_tags)
 
-    """
-
-    # Set the download tags
-
-    # Adjust the date_array for monthly downloads
-    if date_array.freq != 'MS':
-        date_array = pysat_time.create_date_range(
-            dt.datetime(date_array[0].year, date_array[0].month, 1),
-            date_array[-1], freq='MS')
-
-    cdw.download(date_array, tag=tag, inst_id=inst_id,
-                 supported_tags=download_tags, data_path=data_path)
-    return
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
+                                      supported_tags=download_tags)
 
 
 # Set the load routine
 def load(fnames, tag='', inst_id='', file_cadence=pds.DateOffset(months=1),
          flatten_twod=True, use_cdflib=None):
     """Load data and fix meta data.
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/ses14_gold.py` & `pysatNASA-0.0.5/pysatNASA/instruments/timed_guvi.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,203 +1,199 @@
-"""Module for the SES14 GOLD instrument.
+# -*- coding: utf-8 -*-
+"""Module for the TIMED GUVI instrument.
 
-Supports the Nmax data product from the Global Observations of the Limb and
-Disk (GOLD) satellite.  Accesses data in netCDF format.
+Supports the Global UltraViolet Imager (GUVI) instrument on the Thermosphere
+Ionosphere Mesosphere Energetics Dynamics (TIMED) satellite data from the
+NASA Coordinated Data Analysis Web (CDAWeb).
+
+From JHU APL:
+
+The Global Ultraviolet Imager (GUVI) is one of four instruments that constitute
+the TIMED spacecraft, the first mission of the NASA Solar Connections program.
+The TIMED spacecraft is being built by Johns Hopkins University Applied Physics
+Laboratory and GUVI is a joint collaboration between JHU/APL and the Aerospace
+Corporation. TIMED will be used to study the energetics and dynamics of the
+Mesosphere and lower Thermosphere between an altitude of approximately 60 to 180
+kilometers.
+
+References
+----------
+Larry J. Paxton, Andrew B. Christensen, David C. Humm, Bernard S. Ogorzalek, C.
+Thompson Pardoe, Daniel Morrison, Michele B. Weiss, W. Crain, Patricia H. Lew,
+Dan J. Mabry, John O. Goldsten, Stephen A. Gary, David F. Persons, Mark J.
+Harold, E. Brian Alvarez, Carl J. Ercol, Douglas J. Strickland, and Ching-I.
+Meng "Global ultraviolet imager (GUVI): measuring composition and energy inputs
+for the NASA Thermosphere Ionosphere Mesosphere Energetics and Dynamics (TIMED)
+mission", Proc. SPIE 3756, Optical Spectroscopic Techniques and Instrumentation
+for Atmospheric and Space Research III, (20 October 1999);
+https://doi.org/10.1117/12.366380
 
 Properties
 ----------
 platform
-    'ses14'
+    'timed'
 name
-    'gold'
+    'guvi'
 tag
-    'nmax'
+    'edr-aur'
+    'sdr-imaging'
+    'sdr-spectrograph'
+inst_id
+    ''
+    'high_res'
+    'low_res'
 
 Warnings
 --------
-- The cleaning parameters for the instrument are still under development.
-- strict_time_flag must be set to False
-
+- Currently no cleaning routine.
 
-Examples
---------
+Example
+-------
 ::
 
-    import datetime as dt
     import pysat
-    nmax = pysat.Instrument(platform='ses14', name='gold', tag='nmax'
-                            strict_time_flag=False)
-    nmax.download(dt.datetime(2020, 1, 1), dt.datetime(2020, 1, 31))
-    nmax.load(2020, 1)
+    guvi = pysat.Instrument(platform='timed', name='guvi',
+                            inst_id='sdr-imaging', tag='low_res')
+    guvi.download(dt.datetime(2005, 6, 28), dt.datetime(2005, 6, 29))
+    guvi.load(date=dt.datetime(2005, 6, 28))
 
 """
 
 import datetime as dt
 import functools
-import numpy as np
 
-from pysat.instruments.methods import general as ps_gen
-from pysat import logger
-from pysat.utils.io import load_netcdf
+from pysat.instruments.methods import general as mm_gen
 
 from pysatNASA.instruments.methods import cdaweb as cdw
 from pysatNASA.instruments.methods import general as mm_nasa
-from pysatNASA.instruments.methods import gold as mm_gold
+from pysatNASA.instruments.methods import jhuapl
+from pysatNASA.instruments.methods import timed as mm_timed
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
-platform = 'ses14'
-name = 'gold'
-tags = {'nmax': 'Level 2 Nmax data for the GOLD instrument'}
-inst_ids = {'': ['nmax']}
+platform = 'timed'
+name = 'guvi'
+tags = {'edr-aur': 'Level 2 Auroral disk imaging mode',
+        'sdr-imaging': 'Level 1C imaging data',
+        'sdr-spectrograph': 'Level 1C spectrograph data'}
+inst_ids = {'': ['edr-aur'],
+            'high_res': ['sdr-imaging', 'sdr-spectrograph'],
+            'low_res': ['sdr-imaging', 'sdr-spectrograph']}
 
 pandas_format = False
+multi_file_day = True
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
-_test_dates = {'': {'nmax': dt.datetime(2020, 1, 1)}}
+_test_dates = {iid: {tag: dt.datetime(2005, 6, 28) for tag in inst_ids[iid]}
+               for iid in inst_ids.keys()}
+_test_load_opt = {iid: {tag: {'combine_times': True}
+                        for tag in inst_ids[iid]} for iid in ['high_res',
+                                                              'low_res']}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
-
-def init(self):
-    """Initialize the Instrument object with instrument specific values.
-
-    Runs once upon instantiation.
-
-    Parameters
-    -----------
-    self : pysat.Instrument
-        Instrument class object
-
-    """
-
-    logger.info(mm_gold.ack_str)
-    logger.warning(' '.join(('Time stamps may be non-unique because Channel A',
-                             'and B are different instruments.  An upgrade to',
-                             'the pysat.Constellation object is required to',
-                             'solve this issue. See pysat issue #614 for more',
-                             'info.')))
-    self.acknowledgements = mm_gold.ack_str
-    self.references = mm_gold.ref_str
-
-    return
-
+# Use standard init routine
+init = functools.partial(mm_nasa.init, module=mm_timed, name=name)
 
 # No cleaning, use standard warning function instead
 clean = mm_nasa.clean_warn
 
-
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
-# Use the pysat and CDAWeb methods
+# Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
-fname = ''.join(('gold_l2_{tag:s}_{{year:04d}}_{{day:03d}}_v{{version:02d}}',
-                 '_r{{revision:02d}}_c{{cycle:02d}}.nc'))
-supported_tags = {inst_id: {tag: fname.format(tag=tag) for tag in tags.keys()}
+fname = ''.join(('TIMED_GUVI_{lvl:s}{mode:s}_{{year:04d}}{{day:03d}}',
+                 '{{hour:02d}}{{minute:02d}}{{second:02d}}-?????????????_REV',
+                 '??????_Av{{version:02d}}-??r{{revision:03d}}.nc'))
+file_lvl = {'low_res': 'L1C-2-disk', 'high_res': 'L1C-disk', '': 'L2B'}
+mode = {'sdr-imaging': '-IMG', 'sdr-spectrograph': '-SPECT',
+        'edr-aur': '-edr-aur-IMG'}
+supported_tags = {inst_id: {tag: fname.format(lvl=file_lvl[inst_id],
+                                              mode=mode[tag])
+                            for tag in tags.keys()}
                   for inst_id in inst_ids.keys()}
-list_files = functools.partial(ps_gen.list_files,
-                               supported_tags=supported_tags)
+list_files = functools.partial(mm_gen.list_files, supported_tags=supported_tags)
 
 # Set the download routine
-download_tags = {inst_id:
-                 {tag: {'remote_dir': ''.join(('/pub/data/gold/level2/', tag,
-                                               '/{year:4d}/')),
-                        'fname': supported_tags[''][tag]}
-                  for tag in tags.keys()} for inst_id in inst_ids.keys()}
+url = ''.join(('/pub/data/timed/guvi/levels_v13/{lvl:s}/{mode:s}/',
+               '{{year:4d}}/{{day:03d}}/'))
+url_lvl = {'sdr-imaging': 'level1c', 'sdr-spectrograph': 'level1c',
+           'edr-aur': 'level2b'}
+url_mode = {tag: 'imaging/edr-aur' if tag == 'edr-aur' else tag.split('-')[1]
+            for tag in tags.keys()}
+download_tags = {iid: {tag: {'remote_dir': url.format(lvl=url_lvl[tag],
+                                                      mode=url_mode[tag]),
+                             'fname': fname.format(lvl=file_lvl[iid],
+                                                   mode=mode[tag])}
+                       for tag in tags.keys()} for iid in inst_ids.keys()}
 download = functools.partial(cdw.download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
 list_remote_files = functools.partial(cdw.list_remote_files,
                                       supported_tags=download_tags)
 
 
-def load(fnames, tag='', inst_id=''):
-    """Load GOLD NMAX data into `xarray.Dataset` and `pysat.Meta` objects.
+# Set the load routine
+def load(fnames, tag='', inst_id='', combine_times=False):
+    """Load TIMED GUVI data into `xarray.DataSet` and `pysat.Meta` objects.
 
     This routine is called as needed by pysat. It is not intended
     for direct user interaction.
 
     Parameters
     ----------
     fnames : array-like
         iterable of filename strings, full path, to data files to be loaded.
         This input is nominally provided by pysat itself.
     tag : str
-        Tag name used to identify particular data set to be loaded.
-        This input is nominally provided by pysat itself. (default='')
+        tag name used to identify particular data set to be loaded.
+        This input is nominally provided by pysat itself.
     inst_id : str
-        Instrument ID used to identify particular data set to be loaded.
-        This input is nominally provided by pysat itself. (default='')
-    **kwargs : extra keywords
-        Passthrough for additional keyword arguments specified when
-        instantiating an Instrument object. These additional keywords
-        are passed through to this routine by pysat.
+        Satellite ID used to identify particular data set to be loaded.
+        This input is nominally provided by pysat itself.
+    combine_times : bool
+        For SDR data, optionally combine the different datetime coordinates
+        into a single time coordinate (default=False)
 
     Returns
     -------
-    data : xr.Dataset
-        An xarray Dataset with data prepared for the pysat.Instrument
+    data : xr.DataSet
+        A xarray DataSet with data prepared for the pysat.Instrument
     meta : pysat.Meta
         Metadata formatted for a pysat.Instrument object.
 
+    Raises
+    ------
+    ValueError
+        If temporal dimensions are not consistent
+
     Note
     ----
-    - Any additional keyword arguments passed to pysat.Instrument
-      upon instantiation are passed along to this routine.
-    - Using scan_start_time as time dimesion for pysat compatibility, renames
-      ``nscans`` dimension as ``time``.
+    Any additional keyword arguments passed to pysat.Instrument
+    upon instantiation are passed along to this routine.
 
     Examples
     --------
     ::
 
-        inst = pysat.Instrument('ses14', 'gold', tag='nmax')
-        inst.load(2019, 1)
+        inst = pysat.Instrument('timed', 'guvi',
+                                inst_id='high_res', tag='sdr-imaging')
+        inst.load(2005, 179)
 
     """
-
-    labels = {'units': ('Units', str), 'name': ('Long_Name', str),
-              'notes': ('Var_Notes', str), 'desc': ('CatDesc', str),
-              'plot': ('plot', str), 'axis': ('axis', str),
-              'scale': ('scale', str),
-              'min_val': ('Valid_Min', np.float64),
-              'max_val': ('Valid_Max', np.float64),
-              'fill_val': ('fill', np.float64)}
-
-    # Generate custom meta translation table. When left unspecified the default
-    # table handles the multiple values for fill. We must recreate that
-    # functionality in our table. The targets for meta_translation should
-    # map to values in `labels` above.
-    meta_translation = {'FIELDNAM': 'plot', 'LABLAXIS': 'axis',
-                        'ScaleTyp': 'scale', 'VALIDMIN': 'Valid_Min',
-                        'Valid_Min': 'Valid_Min', 'VALIDMAX': 'Valid_Max',
-                        'Valid_Max': 'Valid_Max', '_FillValue': 'fill',
-                        'FillVal': 'fill', 'TIME_BASE': 'time_base'}
-
-    data, meta = load_netcdf(fnames, pandas_format=pandas_format,
-                             epoch_name='nscans', labels=labels,
-                             meta_translation=meta_translation,
-                             drop_meta_labels='FILLVAL')
-
-    if tag == 'nmax':
-        # Add time coordinate from scan_start_time
-        data['time'] = [dt.datetime.strptime(str(val), "b'%Y-%m-%dT%H:%M:%SZ'")
-                        for val in data['scan_start_time'].values]
-
-        # Update coordinates with dimensional data
-        data = data.assign_coords({'nlats': data['nlats'],
-                                   'nlons': data['nlons'],
-                                   'nmask': data['nmask'],
-                                   'channel': data['channel'],
-                                   'hemisphere': data['hemisphere']})
-        meta['time'] = {meta.labels.notes: 'Converted from scan_start_time'}
-        meta['nlats'] = {meta.labels.notes: 'Index for latitude values'}
-        meta['nlons'] = {meta.labels.notes: 'Index for longitude values'}
-        meta['nmask'] = {meta.labels.notes: 'Index for mask values'}
+    if tag == 'edr-aur':
+        data, meta = jhuapl.load_edr_aurora(fnames, tag, inst_id,
+                                            pandas_format=pandas_format,
+                                            strict_dim_check=False)
+    else:
+        data, meta = jhuapl.load_sdr_aurora(fnames, tag, inst_id,
+                                            pandas_format=pandas_format,
+                                            strict_dim_check=False,
+                                            combine_times=combine_times)
 
     return data, meta
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/templates/template_cdaweb_instrument.py` & `pysatNASA-0.0.5/pysatNASA/instruments/templates/template_cdaweb_instrument.py`

 * *Files identical despite different names*

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/timed_saber.py` & `pysatNASA-0.0.5/pysatNASA/instruments/timed_saber.py`

 * *Files 12% similar despite different names*

```diff
@@ -46,83 +46,69 @@
 """
 
 import datetime as dt
 import functools
 
 # CDAWeb methods prewritten for pysat
 from pysat.instruments.methods import general as mm_gen
-from pysat import logger
 
 from pysatNASA.instruments.methods import cdaweb as cdw
 from pysatNASA.instruments.methods import general as mm_nasa
+from pysatNASA.instruments.methods import timed as mm_timed
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
 platform = 'timed'
 name = 'saber'
 tags = {'': ''}
 inst_ids = {'': ['']}
 
 # let pysat know that data is spread across more than one file
 multi_file_day = True
 
 # Set to False to specify using xarray (not using pandas)
 # Set to True if data will be returned via a pandas DataFrame
-pandas_format = True
+pandas_format = False
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
 _test_dates = {'': {'': dt.datetime(2019, 1, 1)}}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
-
-def init(self):
-    """Initialize the Instrument object with instrument specific values.
-
-    Runs once upon instantiation.
-
-    """
-
-    rules_url = 'https://saber.gats-inc.com/data_services.php'
-    ackn_str = ' '.join(('Please see the Rules of the Road at', rules_url))
-
-    logger.info(ackn_str)
-    self.acknowledgements = ackn_str
-    self.references = ''
-
-    return
-
+init = functools.partial(mm_nasa.init, module=mm_timed, name=name)
 
 # No cleaning, use standard warning function instead
 clean = mm_nasa.clean_warn
 
-
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
 # Use the default CDAWeb and pysat methods
 
+# TODO(#104): Switch to netCDF4 files once unzip (#103) is supported.
+
 # Set the list_files routine
 fname = ''.join(('timed_l2a_saber_{year:04d}{month:02d}{day:02d}',
                  '{hour:02d}{minute:02d}_v{version:02d}-{revision:02d}-',
                  '{cycle:02d}.cdf'))
 supported_tags = {'': {'': fname}}
 list_files = functools.partial(mm_gen.list_files,
                                supported_tags=supported_tags)
 
-# Set the load routine
-load = cdw.load
+# Set the load routine. Note that the time variable associated with
+# tpaltitude is renamed to avoid conflict with renaming Epoch.
+load = functools.partial(cdw.load, pandas_format=pandas_format,
+                         drop_dims='record0',
+                         var_translation={'time': 'tp_time'},
+                         use_cdflib=True)
 
 # Set the download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/timed/saber/level2a_cdf',
-                                    '/{year:4d}/{month:02d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'': {'': 'TIMED_L2A_SABER'}}
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

### Comparing `pysatNASA-0.0.4/pysatNASA/instruments/timed_see.py` & `pysatNASA-0.0.5/pysatNASA/instruments/ace_epam_l2.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,118 +1,101 @@
 # -*- coding: utf-8 -*-
-"""Supports the SEE instrument on TIMED.
-
-Downloads data from the NASA Coordinated Data
-Analysis Web (CDAWeb).
-
-Supports two options for loading that may be
-specified at instantiation.
+"""Module for the Advanced Composition Explorer (ACE) EPAM instrument.
 
 Properties
 ----------
 platform
-    'timed'
+    'ace'
 name
-    'see'
+    'epam_l2'
 tag
-    None
+    'base' or 'key'
 inst_id
-    None supported
-flatten_twod
-    If True, then two dimensional data is flattened across
-    columns. Name mangling is used to group data, first column
-    is 'name', last column is 'name_end'. In between numbers are
-    appended 'name_1', 'name_2', etc. All data for a given 2D array
-    may be accessed via, data.loc[:, 'item':'item_end']
-    If False, then 2D data is stored as a series of DataFrames,
-    indexed by Epoch. data.loc[0, 'item']
-    (default=True)
+    '12sec', '5min', '1hr'
+
+References
+----------
+- Stone, E., Frandsen, A., Mewaldt, R. et al. The Advanced Composition Explorer.
+  Space Science Reviews 86, 1–22 (1998). https://doi.org/10.1023/A:1005082526237
+- Gold, R., Krimigis, S., Hawkins, S. et al. Electron, Proton, and Alpha Monitor
+  on the Advanced Composition Explorer spacecraft. Space Science Reviews 86,
+  541–562 (1998). https://doi.org/10.1023/A:1005088115759
 
 Note
 ----
-- no tag required
+- Level 1 ACE data is maintained at pysatSpaceWeather.
+- Release notes at
+  https://cdaweb.gsfc.nasa.gov/pub/data/ace/epam/epam_level2_release_notes.txt
 
 Warnings
 --------
-- Currently no cleaning routine.
+- The cleaning parameters for the instrument are still under development.
 
 """
 
 import datetime as dt
 import functools
-import pandas as pds
 
 from pysat.instruments.methods import general as mm_gen
-from pysat import logger
 
+from pysatNASA.instruments.methods import ace as mm_ace
 from pysatNASA.instruments.methods import cdaweb as cdw
 from pysatNASA.instruments.methods import general as mm_nasa
 
 # ----------------------------------------------------------------------------
 # Instrument attributes
 
-platform = 'timed'
-name = 'see'
-tags = {'': ''}
-inst_ids = {'': [tag for tag in tags.keys()]}
+platform = 'ace'
+name = 'epam_l2'
+tags = {'base': 'ACE/EPAM Solar Energetic Particle Base Data',
+        'key': 'ACE/EPAM Solar Energetic Particle Key Parameters'}
+inst_ids = {'12sec': ['base'],
+            '5min': ['key', 'base'],
+            '1hr': ['key', 'base']}
 
 # ----------------------------------------------------------------------------
 # Instrument test attributes
 
-_test_dates = {'': {'': dt.datetime(2009, 1, 1)}}
+_test_dates = {id: {tag: dt.datetime(2022, 1, 1) for tag in inst_ids[id]}
+               for id in inst_ids.keys()}
 
 # ----------------------------------------------------------------------------
 # Instrument methods
 
 
-def init(self):
-    """Initialize the Instrument object with instrument specific values.
-
-    Runs once upon instantiation.
-
-    """
-
-    rules_url = 'https://www.timed.jhuapl.edu/WWW/scripts/mdc_rules.pl'
-    ackn_str = ' '.join(('Please see the Rules of the Road at', rules_url))
-    logger.info(ackn_str)
-    self.acknowledgements = ackn_str
-    self.references = ' '.join(('Woods, T. N., Eparvier, F. G., Bailey,',
-                                'S. M., Chamberlin, P. C., Lean, J.,',
-                                'Rottman, G. J., Solomon, S. C., Tobiska,',
-                                'W. K., and Woodraska, D. L. (2005),',
-                                'Solar EUV Experiment (SEE): Mission',
-                                'overview and first results, J. Geophys.',
-                                'Res., 110, A01312,',
-                                'doi:10.1029/2004JA010765.'))
-
-    return
-
-
-# No cleaning, use standard warning function instead
-clean = mm_nasa.clean_warn
+# Use standard init routine
+init = functools.partial(mm_nasa.init, module=mm_ace, name=name)
 
+# Use default clean
+clean = mm_nasa.clean
 
 # ----------------------------------------------------------------------------
 # Instrument functions
 #
+
 # Use the default CDAWeb and pysat methods
 
 # Set the list_files routine
-fname = 'timed_l3a_see_{year:04d}{month:02d}{day:02d}_v{version:02d}.cdf'
-supported_tags = {'': {'': fname}}
+strid = {'12sec': {'base': 'h3'},
+         '5min': {'base': 'h1', 'key': 'k0'},
+         '1hr': {'base': 'h2', 'key': 'k1'}}
+fname = ''.join(('ac_{sid:s}_epm_{{year:4d}}{{month:02d}}{{day:02d}}_',
+                 'v{{version:02d}}.cdf'))
+supported_tags = {id: {tag: fname.format(sid=strid[id][tag])
+                       for tag in inst_ids[id]}
+                  for id in inst_ids.keys()}
 list_files = functools.partial(mm_gen.list_files,
-                               supported_tags=supported_tags,
-                               file_cadence=pds.DateOffset(months=1))
+                               supported_tags=supported_tags)
 
 # Set the load routine
-load = functools.partial(cdw.load, file_cadence=pds.DateOffset(months=1))
+load = functools.partial(mm_ace.load, to_pandas=True)
 
 # Set the download routine
-basic_tag = {'remote_dir': ''.join(('/pub/data/timed/see/data/level3a_cdf',
-                                    '/{year:4d}/{month:02d}/')),
-             'fname': fname}
-download_tags = {'': {'': basic_tag}}
-download = functools.partial(cdw.download, supported_tags=download_tags)
+download_tags = {'12sec': {'base': 'AC_H3_EPM'},
+                 '5min': {'base': 'AC_H1_EPM', 'key': 'AC_K0_EPM'},
+                 '1hr': {'base': 'AC_H2_EPM', 'key': 'AC_K1_EPM'}}
+
+download = functools.partial(cdw.cdas_download, supported_tags=download_tags)
 
 # Set the list_remote_files routine
-list_remote_files = functools.partial(cdw.list_remote_files,
+list_remote_files = functools.partial(cdw.cdas_list_remote_files,
                                       supported_tags=download_tags)
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `pysatNASA-0.0.4/pysatNASA.egg-info/SOURCES.txt` & `pysatNASA-0.0.5/pysatNASA.egg-info/SOURCES.txt`

 * *Files 23% similar despite different names*

```diff
@@ -1,49 +1,62 @@
 CHANGELOG.md
 CODE_OF_CONDUCT.md
 CONTRIBUTING.md
 LICENSE
 MANIFEST.in
 README.md
+pyproject.toml
 setup.cfg
-setup.py
+try_cdflib.py
 pysatNASA/__init__.py
-pysatNASA/version.txt
 pysatNASA.egg-info/PKG-INFO
 pysatNASA.egg-info/SOURCES.txt
 pysatNASA.egg-info/dependency_links.txt
-pysatNASA.egg-info/not-zip-safe
 pysatNASA.egg-info/requires.txt
 pysatNASA.egg-info/top_level.txt
 pysatNASA/constellations/__init__.py
 pysatNASA/constellations/de2.py
 pysatNASA/constellations/icon.py
 pysatNASA/instruments/__init__.py
+pysatNASA/instruments/ace_epam_l2.py
+pysatNASA/instruments/ace_mag_l2.py
+pysatNASA/instruments/ace_sis_l2.py
+pysatNASA/instruments/ace_swepam_l2.py
 pysatNASA/instruments/cnofs_ivm.py
 pysatNASA/instruments/cnofs_plp.py
 pysatNASA/instruments/cnofs_vefi.py
+pysatNASA/instruments/de2_fpi.py
 pysatNASA/instruments/de2_lang.py
 pysatNASA/instruments/de2_nacs.py
 pysatNASA/instruments/de2_rpa.py
+pysatNASA/instruments/de2_vefi.py
 pysatNASA/instruments/de2_wats.py
+pysatNASA/instruments/dmsp_ssusi.py
 pysatNASA/instruments/formosat1_ivm.py
 pysatNASA/instruments/icon_euv.py
 pysatNASA/instruments/icon_fuv.py
 pysatNASA/instruments/icon_ivm.py
 pysatNASA/instruments/icon_mighti.py
+pysatNASA/instruments/igs_gps.py
 pysatNASA/instruments/iss_fpmu.py
 pysatNASA/instruments/jpl_gps.py
 pysatNASA/instruments/omni_hro.py
 pysatNASA/instruments/ses14_gold.py
+pysatNASA/instruments/timed_guvi.py
 pysatNASA/instruments/timed_saber.py
 pysatNASA/instruments/timed_see.py
 pysatNASA/instruments/methods/__init__.py
 pysatNASA/instruments/methods/_cdf.py
+pysatNASA/instruments/methods/ace.py
 pysatNASA/instruments/methods/cdaweb.py
 pysatNASA/instruments/methods/cnofs.py
 pysatNASA/instruments/methods/de2.py
+pysatNASA/instruments/methods/dmsp.py
 pysatNASA/instruments/methods/general.py
-pysatNASA/instruments/methods/gold.py
 pysatNASA/instruments/methods/gps.py
 pysatNASA/instruments/methods/icon.py
+pysatNASA/instruments/methods/igs.py
+pysatNASA/instruments/methods/jhuapl.py
 pysatNASA/instruments/methods/omni.py
+pysatNASA/instruments/methods/ses14.py
+pysatNASA/instruments/methods/timed.py
 pysatNASA/instruments/templates/template_cdaweb_instrument.py
```

