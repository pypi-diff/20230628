# Comparing `tmp/OpenDSSDirect.py-0.8.3.tar.gz` & `tmp/OpenDSSDirect.py-0.8.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "OpenDSSDirect.py-0.8.3.tar", last modified: Tue Jun 13 04:36:53 2023, max compression
+gzip compressed data, was "OpenDSSDirect.py-0.8.4.tar", last modified: Wed Jun 28 02:38:44 2023, max compression
```

## Comparing `OpenDSSDirect.py-0.8.3.tar` & `OpenDSSDirect.py-0.8.4.tar`

### file list

```diff
@@ -1,87 +1,87 @@
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.872472 OpenDSSDirect.py-0.8.3/
--rw-r--r--   0 meira     (1000) users      (100)     2442 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/LICENSE
--rw-r--r--   0 meira     (1000) users      (100)      197 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/MANIFEST.in
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.864472 OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/
--rw-r--r--   0 meira     (1000) users      (100)     4055 2023-06-13 04:36:53.000000 OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/PKG-INFO
--rw-r--r--   0 meira     (1000) users      (100)     2006 2023-06-13 04:36:53.000000 OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/SOURCES.txt
--rw-r--r--   0 meira     (1000) users      (100)        1 2023-06-13 04:36:53.000000 OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/dependency_links.txt
--rw-r--r--   0 meira     (1000) users      (100)        1 2023-06-13 04:36:53.000000 OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/not-zip-safe
--rw-r--r--   0 meira     (1000) users      (100)      130 2023-06-13 04:36:53.000000 OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/requires.txt
--rw-r--r--   0 meira     (1000) users      (100)       14 2023-06-13 04:36:53.000000 OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/top_level.txt
--rw-r--r--   0 meira     (1000) users      (100)     4055 2023-06-13 04:36:53.872472 OpenDSSDirect.py-0.8.3/PKG-INFO
--rw-r--r--   0 meira     (1000) users      (100)     3035 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/README.md
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.864472 OpenDSSDirect.py-0.8.3/docs/
--rw-r--r--   0 meira     (1000) users      (100)      909 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/docs/Makefile
--rw-r--r--   0 meira     (1000) users      (100)     5331 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/docs/conf.py
--rw-r--r--   0 meira     (1000) users      (100)      534 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/docs/index.rst
--rw-r--r--   0 meira     (1000) users      (100)      819 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/docs/make.bat
--rw-r--r--   0 meira     (1000) users      (100)     6968 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/docs/opendssdirect.rst
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.872472 OpenDSSDirect.py-0.8.3/opendssdirect/
--rw-r--r--   0 meira     (1000) users      (100)     2417 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/ActiveClass.py
--rw-r--r--   0 meira     (1000) users      (100)     7216 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Basic.py
--rw-r--r--   0 meira     (1000) users      (100)     6752 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Bus.py
--rw-r--r--   0 meira     (1000) users      (100)     5352 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/CNData.py
--rw-r--r--   0 meira     (1000) users      (100)     5846 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/CapControls.py
--rw-r--r--   0 meira     (1000) users      (100)     3527 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Capacitors.py
--rw-r--r--   0 meira     (1000) users      (100)     8072 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Circuit.py
--rw-r--r--   0 meira     (1000) users      (100)    11317 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/CktElement.py
--rw-r--r--   0 meira     (1000) users      (100)     1595 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/CmathLib.py
--rw-r--r--   0 meira     (1000) users      (100)     2173 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/CtrlQueue.py
--rw-r--r--   0 meira     (1000) users      (100)       88 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/DSSCore.py
--rw-r--r--   0 meira     (1000) users      (100)       28 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/DSSEvents.py
--rw-r--r--   0 meira     (1000) users      (100)      323 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/DSSimComs.py
--rw-r--r--   0 meira     (1000) users      (100)     1053 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Element.py
--rw-r--r--   0 meira     (1000) users      (100)     2857 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Error.py
--rw-r--r--   0 meira     (1000) users      (100)     1209 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Executive.py
--rw-r--r--   0 meira     (1000) users      (100)     4306 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Fuses.py
--rw-r--r--   0 meira     (1000) users      (100)     7672 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Generators.py
--rw-r--r--   0 meira     (1000) users      (100)     2082 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Isource.py
--rw-r--r--   0 meira     (1000) users      (100)     5241 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/LineCodes.py
--rw-r--r--   0 meira     (1000) users      (100)     5039 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/LineGeometries.py
--rw-r--r--   0 meira     (1000) users      (100)     2870 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/LineSpacings.py
--rw-r--r--   0 meira     (1000) users      (100)     9279 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Lines.py
--rw-r--r--   0 meira     (1000) users      (100)     4751 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/LoadShape.py
--rw-r--r--   0 meira     (1000) users      (100)    12260 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Loads.py
--rw-r--r--   0 meira     (1000) users      (100)     9461 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Meters.py
--rw-r--r--   0 meira     (1000) users      (100)     5656 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Monitors.py
--rw-r--r--   0 meira     (1000) users      (100)     8426 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/PDElements.py
--rw-r--r--   0 meira     (1000) users      (100)     7270 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/PVsystems.py
--rw-r--r--   0 meira     (1000) users      (100)     2290 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Parallel.py
--rw-r--r--   0 meira     (1000) users      (100)     4475 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Parser.py
--rw-r--r--   0 meira     (1000) users      (100)      601 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Progress.py
--rw-r--r--   0 meira     (1000) users      (100)     1616 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Properties.py
--rw-r--r--   0 meira     (1000) users      (100)     9553 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Reactors.py
--rw-r--r--   0 meira     (1000) users      (100)     4925 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Reclosers.py
--rw-r--r--   0 meira     (1000) users      (100)     2936 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/ReduceCkt.py
--rw-r--r--   0 meira     (1000) users      (100)     8295 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/RegControls.py
--rw-r--r--   0 meira     (1000) users      (100)     2713 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Relays.py
--rw-r--r--   0 meira     (1000) users      (100)     5351 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Sensors.py
--rw-r--r--   0 meira     (1000) users      (100)     7573 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Settings.py
--rw-r--r--   0 meira     (1000) users      (100)    13553 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Solution.py
--rw-r--r--   0 meira     (1000) users      (100)     2271 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Storages.py
--rw-r--r--   0 meira     (1000) users      (100)     3823 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/SwtControls.py
--rw-r--r--   0 meira     (1000) users      (100)     5175 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/TSData.py
--rw-r--r--   0 meira     (1000) users      (100)      569 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Text.py
--rw-r--r--   0 meira     (1000) users      (100)     3816 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Topology.py
--rw-r--r--   0 meira     (1000) users      (100)     8843 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Transformers.py
--rw-r--r--   0 meira     (1000) users      (100)     2555 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/Vsources.py
--rw-r--r--   0 meira     (1000) users      (100)     3665 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/WireData.py
--rw-r--r--   0 meira     (1000) users      (100)     4036 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/XYCurves.py
--rw-r--r--   0 meira     (1000) users      (100)     3087 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/YMatrix.py
--rw-r--r--   0 meira     (1000) users      (100)     2570 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/ZIP.py
--rw-r--r--   0 meira     (1000) users      (100)      883 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/__init__.py
--rw-r--r--   0 meira     (1000) users      (100)      918 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/_utils.py
--rw-r--r--   0 meira     (1000) users      (100)       46 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/_version.py
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.872472 OpenDSSDirect.py-0.8.3/opendssdirect/dss/
--rw-r--r--   0 meira     (1000) users      (100)     1388 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/dss/__init__.py
--rw-r--r--   0 meira     (1000) users      (100)     8286 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/opendssdirect/utils.py
--rw-r--r--   0 meira     (1000) users      (100)       38 2023-06-13 04:36:53.872472 OpenDSSDirect.py-0.8.3/setup.cfg
--rw-r--r--   0 meira     (1000) users      (100)     2697 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/setup.py
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.872472 OpenDSSDirect.py-0.8.3/tests/
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.860472 OpenDSSDirect.py-0.8.3/tests/data/
-drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-13 04:36:53.872472 OpenDSSDirect.py-0.8.3/tests/data/13Bus/
--rw-r--r--   0 meira     (1000) users      (100)      243 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/tests/data/13Bus/IEEE13Node_BusXY.csv
--rw-r--r--   0 meira     (1000) users      (100)     8205 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/tests/data/13Bus/IEEE13Nodeckt.dss
--rw-r--r--   0 meira     (1000) users      (100)    11851 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/tests/data/13Bus/IEEELineCodes.dss
--rw-r--r--   0 meira     (1000) users      (100)      455 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/tests/test_evaluate_expression.py
--rw-r--r--   0 meira     (1000) users      (100)   176569 2023-06-13 04:36:37.000000 OpenDSSDirect.py-0.8.3/tests/test_opendssdirect.py
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.694647 OpenDSSDirect.py-0.8.4/
+-rw-r--r--   0 meira     (1000) users      (100)     2442 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/LICENSE
+-rw-r--r--   0 meira     (1000) users      (100)      197 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/MANIFEST.in
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.686647 OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/
+-rw-r--r--   0 meira     (1000) users      (100)     4055 2023-06-28 02:38:44.000000 OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/PKG-INFO
+-rw-r--r--   0 meira     (1000) users      (100)     2006 2023-06-28 02:38:44.000000 OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/SOURCES.txt
+-rw-r--r--   0 meira     (1000) users      (100)        1 2023-06-28 02:38:44.000000 OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/dependency_links.txt
+-rw-r--r--   0 meira     (1000) users      (100)        1 2023-06-28 02:38:39.000000 OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/not-zip-safe
+-rw-r--r--   0 meira     (1000) users      (100)      130 2023-06-28 02:38:44.000000 OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/requires.txt
+-rw-r--r--   0 meira     (1000) users      (100)       14 2023-06-28 02:38:44.000000 OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/top_level.txt
+-rw-r--r--   0 meira     (1000) users      (100)     4055 2023-06-28 02:38:44.694647 OpenDSSDirect.py-0.8.4/PKG-INFO
+-rw-r--r--   0 meira     (1000) users      (100)     3035 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/README.md
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.686647 OpenDSSDirect.py-0.8.4/docs/
+-rw-r--r--   0 meira     (1000) users      (100)      909 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/docs/Makefile
+-rw-r--r--   0 meira     (1000) users      (100)     5331 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/docs/conf.py
+-rw-r--r--   0 meira     (1000) users      (100)      534 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/docs/index.rst
+-rw-r--r--   0 meira     (1000) users      (100)      819 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/docs/make.bat
+-rw-r--r--   0 meira     (1000) users      (100)     6968 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/docs/opendssdirect.rst
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.694647 OpenDSSDirect.py-0.8.4/opendssdirect/
+-rw-r--r--   0 meira     (1000) users      (100)     2417 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/ActiveClass.py
+-rw-r--r--   0 meira     (1000) users      (100)     7216 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Basic.py
+-rw-r--r--   0 meira     (1000) users      (100)     6752 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Bus.py
+-rw-r--r--   0 meira     (1000) users      (100)     5352 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/CNData.py
+-rw-r--r--   0 meira     (1000) users      (100)     5846 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/CapControls.py
+-rw-r--r--   0 meira     (1000) users      (100)     3527 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Capacitors.py
+-rw-r--r--   0 meira     (1000) users      (100)     8072 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Circuit.py
+-rw-r--r--   0 meira     (1000) users      (100)    11317 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/CktElement.py
+-rw-r--r--   0 meira     (1000) users      (100)     1595 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/CmathLib.py
+-rw-r--r--   0 meira     (1000) users      (100)     2173 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/CtrlQueue.py
+-rw-r--r--   0 meira     (1000) users      (100)       88 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/DSSCore.py
+-rw-r--r--   0 meira     (1000) users      (100)       28 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/DSSEvents.py
+-rw-r--r--   0 meira     (1000) users      (100)      323 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/DSSimComs.py
+-rw-r--r--   0 meira     (1000) users      (100)     1053 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Element.py
+-rw-r--r--   0 meira     (1000) users      (100)     2857 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Error.py
+-rw-r--r--   0 meira     (1000) users      (100)     1209 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Executive.py
+-rw-r--r--   0 meira     (1000) users      (100)     4306 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Fuses.py
+-rw-r--r--   0 meira     (1000) users      (100)     7672 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Generators.py
+-rw-r--r--   0 meira     (1000) users      (100)     2082 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Isource.py
+-rw-r--r--   0 meira     (1000) users      (100)     5241 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/LineCodes.py
+-rw-r--r--   0 meira     (1000) users      (100)     5039 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/LineGeometries.py
+-rw-r--r--   0 meira     (1000) users      (100)     2870 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/LineSpacings.py
+-rw-r--r--   0 meira     (1000) users      (100)     9279 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Lines.py
+-rw-r--r--   0 meira     (1000) users      (100)     4751 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/LoadShape.py
+-rw-r--r--   0 meira     (1000) users      (100)    12260 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Loads.py
+-rw-r--r--   0 meira     (1000) users      (100)     9461 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Meters.py
+-rw-r--r--   0 meira     (1000) users      (100)     5656 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Monitors.py
+-rw-r--r--   0 meira     (1000) users      (100)     8426 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/PDElements.py
+-rw-r--r--   0 meira     (1000) users      (100)     7270 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/PVsystems.py
+-rw-r--r--   0 meira     (1000) users      (100)     2290 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Parallel.py
+-rw-r--r--   0 meira     (1000) users      (100)     4475 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Parser.py
+-rw-r--r--   0 meira     (1000) users      (100)      601 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Progress.py
+-rw-r--r--   0 meira     (1000) users      (100)     1616 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Properties.py
+-rw-r--r--   0 meira     (1000) users      (100)     9553 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Reactors.py
+-rw-r--r--   0 meira     (1000) users      (100)     4925 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Reclosers.py
+-rw-r--r--   0 meira     (1000) users      (100)     2936 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/ReduceCkt.py
+-rw-r--r--   0 meira     (1000) users      (100)     8295 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/RegControls.py
+-rw-r--r--   0 meira     (1000) users      (100)     2713 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Relays.py
+-rw-r--r--   0 meira     (1000) users      (100)     5351 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Sensors.py
+-rw-r--r--   0 meira     (1000) users      (100)     7573 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Settings.py
+-rw-r--r--   0 meira     (1000) users      (100)    13553 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Solution.py
+-rw-r--r--   0 meira     (1000) users      (100)     2271 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Storages.py
+-rw-r--r--   0 meira     (1000) users      (100)     3823 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/SwtControls.py
+-rw-r--r--   0 meira     (1000) users      (100)     5175 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/TSData.py
+-rw-r--r--   0 meira     (1000) users      (100)      569 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Text.py
+-rw-r--r--   0 meira     (1000) users      (100)     3816 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Topology.py
+-rw-r--r--   0 meira     (1000) users      (100)     8843 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Transformers.py
+-rw-r--r--   0 meira     (1000) users      (100)     2555 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/Vsources.py
+-rw-r--r--   0 meira     (1000) users      (100)     3665 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/WireData.py
+-rw-r--r--   0 meira     (1000) users      (100)     4036 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/XYCurves.py
+-rw-r--r--   0 meira     (1000) users      (100)     3087 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/YMatrix.py
+-rw-r--r--   0 meira     (1000) users      (100)     2570 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/ZIP.py
+-rw-r--r--   0 meira     (1000) users      (100)      883 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/__init__.py
+-rw-r--r--   0 meira     (1000) users      (100)      918 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/_utils.py
+-rw-r--r--   0 meira     (1000) users      (100)       46 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/_version.py
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.694647 OpenDSSDirect.py-0.8.4/opendssdirect/dss/
+-rw-r--r--   0 meira     (1000) users      (100)     1388 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/dss/__init__.py
+-rw-r--r--   0 meira     (1000) users      (100)     8286 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/opendssdirect/utils.py
+-rw-r--r--   0 meira     (1000) users      (100)       38 2023-06-28 02:38:44.694647 OpenDSSDirect.py-0.8.4/setup.cfg
+-rw-r--r--   0 meira     (1000) users      (100)     2697 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/setup.py
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.694647 OpenDSSDirect.py-0.8.4/tests/
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.686647 OpenDSSDirect.py-0.8.4/tests/data/
+drwxr-xr-x   0 meira     (1000) users      (100)        0 2023-06-28 02:38:44.694647 OpenDSSDirect.py-0.8.4/tests/data/13Bus/
+-rw-r--r--   0 meira     (1000) users      (100)      243 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/tests/data/13Bus/IEEE13Node_BusXY.csv
+-rw-r--r--   0 meira     (1000) users      (100)     8205 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/tests/data/13Bus/IEEE13Nodeckt.dss
+-rw-r--r--   0 meira     (1000) users      (100)    11851 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/tests/data/13Bus/IEEELineCodes.dss
+-rw-r--r--   0 meira     (1000) users      (100)      455 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/tests/test_evaluate_expression.py
+-rw-r--r--   0 meira     (1000) users      (100)   176818 2023-06-28 02:38:24.000000 OpenDSSDirect.py-0.8.4/tests/test_opendssdirect.py
```

### Comparing `OpenDSSDirect.py-0.8.3/LICENSE` & `OpenDSSDirect.py-0.8.4/LICENSE`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/PKG-INFO` & `OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: OpenDSSDirect.py
-Version: 0.8.3
+Version: 0.8.4
 Summary: Python direct-mode interface to an alternative implementation of OpenDSS
 Home-page: https://github.com/dss-extensions/OpenDSSDirect.py
 Download-URL: https://github.com/dss-extensions/OpenDSSDirect.py
 Author: Dheepak Krishnamurthy
 Author-email: me@kdheepak.com
 License: BSD-compatible
 Keywords: OpenDSS,cffi
```

### Comparing `OpenDSSDirect.py-0.8.3/OpenDSSDirect.py.egg-info/SOURCES.txt` & `OpenDSSDirect.py-0.8.4/OpenDSSDirect.py.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/PKG-INFO` & `OpenDSSDirect.py-0.8.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: OpenDSSDirect.py
-Version: 0.8.3
+Version: 0.8.4
 Summary: Python direct-mode interface to an alternative implementation of OpenDSS
 Home-page: https://github.com/dss-extensions/OpenDSSDirect.py
 Download-URL: https://github.com/dss-extensions/OpenDSSDirect.py
 Author: Dheepak Krishnamurthy
 Author-email: me@kdheepak.com
 License: BSD-compatible
 Keywords: OpenDSS,cffi
```

### Comparing `OpenDSSDirect.py-0.8.3/README.md` & `OpenDSSDirect.py-0.8.4/README.md`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/docs/Makefile` & `OpenDSSDirect.py-0.8.4/docs/Makefile`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/docs/conf.py` & `OpenDSSDirect.py-0.8.4/docs/conf.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/docs/index.rst` & `OpenDSSDirect.py-0.8.4/docs/index.rst`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/docs/make.bat` & `OpenDSSDirect.py-0.8.4/docs/make.bat`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/docs/opendssdirect.rst` & `OpenDSSDirect.py-0.8.4/docs/opendssdirect.rst`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/ActiveClass.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/ActiveClass.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Basic.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Basic.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Bus.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Bus.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/CNData.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/CNData.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/CapControls.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/CapControls.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Capacitors.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Capacitors.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Circuit.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Circuit.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/CktElement.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/CktElement.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/CmathLib.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/CmathLib.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/CtrlQueue.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/CtrlQueue.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Element.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Element.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Error.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Error.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Executive.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Executive.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Fuses.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Fuses.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Generators.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Generators.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Isource.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Isource.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/LineCodes.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/LineCodes.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/LineGeometries.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/LineGeometries.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/LineSpacings.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/LineSpacings.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Lines.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Lines.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/LoadShape.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/LoadShape.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Loads.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Loads.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Meters.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Meters.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Monitors.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Monitors.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/PDElements.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/PDElements.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/PVsystems.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/PVsystems.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Parallel.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Parallel.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Parser.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Parser.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Progress.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Progress.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Properties.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Properties.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Reactors.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Reactors.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Reclosers.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Reclosers.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/ReduceCkt.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/ReduceCkt.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/RegControls.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/RegControls.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Relays.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Relays.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Sensors.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Sensors.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Settings.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Settings.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Solution.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Solution.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Storages.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Storages.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/SwtControls.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/SwtControls.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/TSData.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/TSData.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Text.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Text.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Topology.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Topology.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Transformers.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Transformers.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/Vsources.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/Vsources.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/WireData.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/WireData.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/XYCurves.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/XYCurves.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/YMatrix.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/YMatrix.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/ZIP.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/ZIP.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/__init__.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/__init__.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/_utils.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/_utils.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/dss/__init__.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/dss/__init__.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/opendssdirect/utils.py` & `OpenDSSDirect.py-0.8.4/opendssdirect/utils.py`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/setup.py` & `OpenDSSDirect.py-0.8.4/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -42,15 +42,15 @@
     url="https://github.com/dss-extensions/OpenDSSDirect.py",
     download_url="https://github.com/dss-extensions/OpenDSSDirect.py",
     # Author details
     author="Dheepak Krishnamurthy",
     author_email="me@kdheepak.com",
     license="BSD-compatible",
     packages=find_packages(),
-    install_requires=["dss_python>=0.14.3,<0.15"],
+    install_requires=["dss_python>=0.14.4,<0.15"],
     extras_require={
         "extras": ["pandas", "matplotlib", "networkx"],
         "dev": [
             "pytest",
             "pytest-cov",
             "sphinx-rtd-theme",
             "nbsphinx",
```

### Comparing `OpenDSSDirect.py-0.8.3/tests/data/13Bus/IEEE13Nodeckt.dss` & `OpenDSSDirect.py-0.8.4/tests/data/13Bus/IEEE13Nodeckt.dss`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/tests/data/13Bus/IEEELineCodes.dss` & `OpenDSSDirect.py-0.8.4/tests/data/13Bus/IEEELineCodes.dss`

 * *Files identical despite different names*

### Comparing `OpenDSSDirect.py-0.8.3/tests/test_opendssdirect.py` & `OpenDSSDirect.py-0.8.4/tests/test_opendssdirect.py`

 * *Files 0% similar despite different names*

```diff
@@ -204,16 +204,24 @@
 
     # Test toggling the console output using AllowForms.
     # Note COM's AllowForms can only be disabled and it ignores
     # the user's command to reallow forms if they were previously
     # disabled.
     assert not dss.Basic.AllowForms(), "Allow forms should be disabled by default"
 
-    dss.Basic.AllowForms(True)
-    assert dss.Basic.AllowForms()
+    check_if_true = True
+    try:
+        dss.Basic.AllowForms(True)
+    except:
+        # On Windows, without a console, we cannot activate this.
+        # Users can use the callback mechanism to integrate to GUIs though.
+        check_if_true = False
+
+    if check_if_true:
+        assert dss.Basic.AllowForms()
 
     dss.Basic.AllowForms(False)
     assert not dss.Basic.AllowForms()
 
 
 def test_13Node(dss):
```

