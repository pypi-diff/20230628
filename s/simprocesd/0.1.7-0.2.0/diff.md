# Comparing `tmp/simprocesd-0.1.7.tar.gz` & `tmp/simprocesd-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "simprocesd-0.1.7.tar", last modified: Wed Feb  1 18:10:25 2023, max compression
+gzip compressed data, was "simprocesd-0.2.0.tar", last modified: Wed Jun 28 14:12:52 2023, max compression
```

## Comparing `simprocesd-0.1.7.tar` & `simprocesd-0.2.0.tar`

### file list

```diff
@@ -1,61 +1,67 @@
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.552916 simprocesd-0.1.7/
--rw-rw-rw-   0        0        0     1866 2022-10-13 13:28:13.000000 simprocesd-0.1.7/LICENSE.md
--rw-rw-rw-   0        0        0     2129 2023-02-01 18:10:25.549469 simprocesd-0.1.7/PKG-INFO
--rw-rw-rw-   0        0        0     4308 2023-02-01 18:07:29.000000 simprocesd-0.1.7/README.md
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.391090 simprocesd-0.1.7/examples/
--rw-rw-rw-   0        0        0      579 2022-10-13 13:28:13.000000 simprocesd-0.1.7/examples/BufferExample.py
--rw-rw-rw-   0        0        0     2745 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/ConditionBasedMaintenance.py
--rw-rw-rw-   0        0        0     3250 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/DataExploration.py
--rw-rw-rw-   0        0        0     2076 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/ExtendingPartObject.py
--rw-rw-rw-   0        0        0     1409 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/FilterParts.py
--rw-rw-rw-   0        0        0     5218 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/MachineFaultDetection.py
--rw-rw-rw-   0        0        0     5684 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/MaintenanceOptimization.py
--rw-rw-rw-   0        0        0     4327 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/PaperMillCmsEvaluation.py
--rw-rw-rw-   0        0        0      898 2022-10-13 13:28:13.000000 simprocesd-0.1.7/examples/ParallelStations.py
--rw-rw-rw-   0        0        0     1677 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/PartQuality.py
--rw-rw-rw-   0        0        0      974 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/SaveSimulationToFile.py
--rw-rw-rw-   0        0        0      937 2022-11-29 18:12:53.000000 simprocesd-0.1.7/examples/SingleMachine.py
--rw-rw-rw-   0        0        0     1198 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/SingleMachineWithFaults.py
--rw-rw-rw-   0        0        0     1416 2022-12-21 15:23:13.000000 simprocesd-0.1.7/examples/TwoMachinesWithFaults.py
--rw-rw-rw-   0        0        0     1546 2022-10-13 13:28:13.000000 simprocesd-0.1.7/examples/VariousFlows.py
--rw-rw-rw-   0        0        0      115 2023-01-25 19:18:45.000000 simprocesd-0.1.7/examples/__init__.py
--rw-rw-rw-   0        0        0     4944 2023-01-25 19:18:45.000000 simprocesd-0.1.7/examples/machine_with_damage.py
--rw-rw-rw-   0        0        0    12602 2023-01-25 19:18:45.000000 simprocesd-0.1.7/examples/machine_with_faults.py
--rw-rw-rw-   0        0        0       42 2023-02-01 18:10:25.552916 simprocesd-0.1.7/setup.cfg
--rw-rw-rw-   0        0        0     1609 2023-02-01 18:07:29.000000 simprocesd-0.1.7/setup.py
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.397444 simprocesd-0.1.7/simprocesd/
--rw-rw-rw-   0        0        0        0 2022-10-13 13:28:13.000000 simprocesd-0.1.7/simprocesd/__init__.py
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.431981 simprocesd-0.1.7/simprocesd/model/
--rw-rw-rw-   0        0        0       82 2022-10-13 13:28:13.000000 simprocesd-0.1.7/simprocesd/model/__init__.py
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.440735 simprocesd-0.1.7/simprocesd/model/cms/
--rw-rw-rw-   0        0        0       21 2022-10-13 13:28:13.000000 simprocesd-0.1.7/simprocesd/model/cms/__init__.py
--rw-rw-rw-   0        0        0     1593 2023-02-01 18:07:29.000000 simprocesd-0.1.7/simprocesd/model/cms/cms.py
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.499200 simprocesd-0.1.7/simprocesd/model/factory_floor/
--rw-rw-rw-   0        0        0      244 2022-12-21 15:23:13.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/__init__.py
--rw-rw-rw-   0        0        0     3615 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/asset.py
--rw-rw-rw-   0        0        0     2353 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/buffer.py
--rw-rw-rw-   0        0        0     1464 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/decision_gate.py
--rw-rw-rw-   0        0        0     7488 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/device.py
--rw-rw-rw-   0        0        0     9301 2023-02-01 17:59:09.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/machine.py
--rw-rw-rw-   0        0        0     8085 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/maintainer.py
--rw-rw-rw-   0        0        0     1805 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/part.py
--rw-rw-rw-   0        0        0     2529 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/sink.py
--rw-rw-rw-   0        0        0     3573 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/factory_floor/source.py
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.515001 simprocesd-0.1.7/simprocesd/model/sensors/
--rw-rw-rw-   0        0        0      108 2022-10-13 13:28:13.000000 simprocesd-0.1.7/simprocesd/model/sensors/__init__.py
--rw-rw-rw-   0        0        0     1949 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/sensors/part_sensor.py
--rw-rw-rw-   0        0        0     5783 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/sensors/sensor.py
--rw-rw-rw-   0        0        0    12090 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/simulation.py
--rw-rw-rw-   0        0        0     5945 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/model/system.py
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.544681 simprocesd-0.1.7/simprocesd/utils/
--rw-rw-rw-   0        0        0      360 2022-12-21 15:23:13.000000 simprocesd-0.1.7/simprocesd/utils/__init__.py
--rw-rw-rw-   0        0        0      252 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/utils/enums.py
--rw-rw-rw-   0        0        0     1057 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/utils/math_utils.py
--rw-rw-rw-   0        0        0     5670 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/utils/simulation_info_utils.py
--rw-rw-rw-   0        0        0     3841 2023-01-25 19:18:45.000000 simprocesd-0.1.7/simprocesd/utils/utils.py
-drwxrwxrwx   0        0        0        0 2023-02-01 18:10:25.419421 simprocesd-0.1.7/simprocesd.egg-info/
--rw-rw-rw-   0        0        0     2129 2023-02-01 18:10:25.000000 simprocesd-0.1.7/simprocesd.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1599 2023-02-01 18:10:25.000000 simprocesd-0.1.7/simprocesd.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-02-01 18:10:25.000000 simprocesd-0.1.7/simprocesd.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       56 2023-02-01 18:10:25.000000 simprocesd-0.1.7/simprocesd.egg-info/requires.txt
--rw-rw-rw-   0        0        0       20 2023-02-01 18:10:25.000000 simprocesd-0.1.7/simprocesd.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.784916 simprocesd-0.2.0/
+-rw-rw-rw-   0        0        0     1866 2022-10-13 13:28:13.000000 simprocesd-0.2.0/LICENSE.md
+-rw-rw-rw-   0        0        0     2129 2023-06-28 14:12:52.784916 simprocesd-0.2.0/PKG-INFO
+-rw-rw-rw-   0        0        0     4306 2023-05-16 15:09:22.000000 simprocesd-0.2.0/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.747442 simprocesd-0.2.0/examples/
+-rw-rw-rw-   0        0        0     1181 2023-06-27 18:24:35.000000 simprocesd-0.2.0/examples/BatchProcessing.py
+-rw-rw-rw-   0        0        0      579 2022-10-13 13:28:13.000000 simprocesd-0.2.0/examples/BufferExample.py
+-rw-rw-rw-   0        0        0     2745 2022-12-21 15:23:13.000000 simprocesd-0.2.0/examples/ConditionBasedMaintenance.py
+-rw-rw-rw-   0        0        0     3250 2022-12-21 15:23:13.000000 simprocesd-0.2.0/examples/DataExploration.py
+-rw-rw-rw-   0        0        0     2076 2022-12-21 15:23:13.000000 simprocesd-0.2.0/examples/ExtendingPartObject.py
+-rw-rw-rw-   0        0        0     1421 2023-04-25 16:46:22.000000 simprocesd-0.2.0/examples/FilterParts.py
+-rw-rw-rw-   0        0        0     5218 2022-12-21 15:23:13.000000 simprocesd-0.2.0/examples/MachineFaultDetection.py
+-rw-rw-rw-   0        0        0     5684 2022-12-21 15:23:13.000000 simprocesd-0.2.0/examples/MaintenanceOptimization.py
+-rw-rw-rw-   0        0        0      820 2023-06-27 17:11:46.000000 simprocesd-0.2.0/examples/OperatingSchedule.py
+-rw-rw-rw-   0        0        0     4327 2023-04-27 15:04:44.000000 simprocesd-0.2.0/examples/PaperMillCmsEvaluation.py
+-rw-rw-rw-   0        0        0      898 2023-03-21 15:35:49.000000 simprocesd-0.2.0/examples/ParallelStations.py
+-rw-rw-rw-   0        0        0     1677 2023-02-06 17:25:59.000000 simprocesd-0.2.0/examples/PartQuality.py
+-rw-rw-rw-   0        0        0      974 2022-12-21 15:23:13.000000 simprocesd-0.2.0/examples/SaveSimulationToFile.py
+-rw-rw-rw-   0        0        0     1294 2023-06-27 18:24:35.000000 simprocesd-0.2.0/examples/SharedResources.py
+-rw-rw-rw-   0        0        0      937 2023-03-06 20:48:09.000000 simprocesd-0.2.0/examples/SingleMachine.py
+-rw-rw-rw-   0        0        0     1643 2023-06-27 18:24:35.000000 simprocesd-0.2.0/examples/SingleMachineWithFaults.py
+-rw-rw-rw-   0        0        0     1558 2023-04-25 16:46:22.000000 simprocesd-0.2.0/examples/VariousFlows.py
+-rw-rw-rw-   0        0        0      115 2023-02-08 15:06:38.000000 simprocesd-0.2.0/examples/__init__.py
+-rw-rw-rw-   0        0        0     4944 2023-02-08 15:06:38.000000 simprocesd-0.2.0/examples/machine_with_damage.py
+-rw-rw-rw-   0        0        0    12602 2023-02-08 15:06:38.000000 simprocesd-0.2.0/examples/machine_with_faults.py
+-rw-rw-rw-   0        0        0       42 2023-06-28 14:12:52.784916 simprocesd-0.2.0/setup.cfg
+-rw-rw-rw-   0        0        0     1605 2023-06-28 14:12:23.000000 simprocesd-0.2.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.748439 simprocesd-0.2.0/simprocesd/
+-rw-rw-rw-   0        0        0        0 2022-10-13 13:28:13.000000 simprocesd-0.2.0/simprocesd/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.759343 simprocesd-0.2.0/simprocesd/model/
+-rw-rw-rw-   0        0        0      128 2023-04-24 15:59:33.000000 simprocesd-0.2.0/simprocesd/model/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.761341 simprocesd-0.2.0/simprocesd/model/cms/
+-rw-rw-rw-   0        0        0       21 2022-10-13 13:28:13.000000 simprocesd-0.2.0/simprocesd/model/cms/__init__.py
+-rw-rw-rw-   0        0        0     1593 2023-02-08 15:06:38.000000 simprocesd-0.2.0/simprocesd/model/cms/cms.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.775927 simprocesd-0.2.0/simprocesd/model/factory_floor/
+-rw-rw-rw-   0        0        0      382 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/__init__.py
+-rw-rw-rw-   0        0        0     5931 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/action_scheduler.py
+-rw-rw-rw-   0        0        0     3723 2023-05-30 14:10:59.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/asset.py
+-rw-rw-rw-   0        0        0     1902 2023-05-16 15:09:22.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/batch.py
+-rw-rw-rw-   0        0        0     4138 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/buffer.py
+-rw-rw-rw-   0        0        0     1513 2023-04-25 16:46:22.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/decision_gate.py
+-rw-rw-rw-   0        0        0    10443 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/device.py
+-rw-rw-rw-   0        0        0    14193 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/machine.py
+-rw-rw-rw-   0        0        0     8838 2023-04-06 15:26:21.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/maintainer.py
+-rw-rw-rw-   0        0        0     1775 2023-05-16 15:09:22.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/part.py
+-rw-rw-rw-   0        0        0     2923 2023-05-16 15:09:22.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/part_batcher.py
+-rw-rw-rw-   0        0        0     2767 2023-06-27 18:24:35.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/sink.py
+-rw-rw-rw-   0        0        0     3397 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/model/factory_floor/source.py
+-rw-rw-rw-   0        0        0     8964 2023-05-16 15:09:22.000000 simprocesd-0.2.0/simprocesd/model/resource_manager.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.778924 simprocesd-0.2.0/simprocesd/model/sensors/
+-rw-rw-rw-   0        0        0      108 2022-10-13 13:28:13.000000 simprocesd-0.2.0/simprocesd/model/sensors/__init__.py
+-rw-rw-rw-   0        0        0     1949 2023-02-08 15:06:38.000000 simprocesd-0.2.0/simprocesd/model/sensors/part_sensor.py
+-rw-rw-rw-   0        0        0     5783 2023-02-08 15:06:38.000000 simprocesd-0.2.0/simprocesd/model/sensors/sensor.py
+-rw-rw-rw-   0        0        0    12635 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/model/simulation.py
+-rw-rw-rw-   0        0        0     6668 2023-06-27 18:24:35.000000 simprocesd-0.2.0/simprocesd/model/system.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.783915 simprocesd-0.2.0/simprocesd/utils/
+-rw-rw-rw-   0        0        0      360 2022-12-21 15:23:13.000000 simprocesd-0.2.0/simprocesd/utils/__init__.py
+-rw-rw-rw-   0        0        0      252 2023-02-08 15:06:38.000000 simprocesd-0.2.0/simprocesd/utils/enums.py
+-rw-rw-rw-   0        0        0     1057 2023-02-08 15:06:38.000000 simprocesd-0.2.0/simprocesd/utils/math_utils.py
+-rw-rw-rw-   0        0        0     5668 2023-06-27 18:24:35.000000 simprocesd-0.2.0/simprocesd/utils/simulation_info_utils.py
+-rw-rw-rw-   0        0        0     3995 2023-06-27 17:11:46.000000 simprocesd-0.2.0/simprocesd/utils/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:12:52.753433 simprocesd-0.2.0/simprocesd.egg-info/
+-rw-rw-rw-   0        0        0     2129 2023-06-28 14:12:52.000000 simprocesd-0.2.0/simprocesd.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1826 2023-06-28 14:12:52.000000 simprocesd-0.2.0/simprocesd.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:12:52.000000 simprocesd-0.2.0/simprocesd.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       56 2023-06-28 14:12:52.000000 simprocesd-0.2.0/simprocesd.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       20 2023-06-28 14:12:52.000000 simprocesd-0.2.0/simprocesd.egg-info/top_level.txt
```

### Comparing `simprocesd-0.1.7/LICENSE.md` & `simprocesd-0.2.0/LICENSE.md`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/PKG-INFO` & `simprocesd-0.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: simprocesd
-Version: 0.1.7
+Version: 0.2.0
 Summary: Discreet event simulator for manufacturing systems.
 Author: Serghei Drozdov
 Author-email: serghei.drozdov@nist.gov
 License: US Government Open Source
 Project-URL: Source Code, https://github.com/usnistgov/simprocesd
 Classifier: Development Status :: 3 - Alpha
 Classifier: Programming Language :: Python
```

### Comparing `simprocesd-0.1.7/README.md` & `simprocesd-0.2.0/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -25,16 +25,17 @@
 pip install simprocesd[examples]
 ```
 
 
 ### Installation Requirements
 Using SimPROCESD requires:
 - Python ≥ 3.7:
-- matplotlib ≥ 3.5 for using plot functions and running certain examples.
-- [optional] scipy ≥ 1.5.2 and numpy ≥ 1.21 for running certain examples.
+- NumPy ≥ 1.21
+- Matplotlib ≥ 3.5 for using plot functions and running certain examples.
+- [optional] scipy ≥ 1.5.2 for running certain examples.
 
 
 ## Quickstart
 
 The package provides following objects for modeling a manufacturing process:
 - **Source**: Introduces new parts to the system.
 - **Machine**: Retrieves, processes, and relinquishes parts. Can be subject to degradation, failures, and repairs.
```

### Comparing `simprocesd-0.1.7/examples/BufferExample.py` & `simprocesd-0.2.0/examples/BufferExample.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/ConditionBasedMaintenance.py` & `simprocesd-0.2.0/examples/ConditionBasedMaintenance.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/DataExploration.py` & `simprocesd-0.2.0/examples/DataExploration.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/ExtendingPartObject.py` & `simprocesd-0.2.0/examples/ExtendingPartObject.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/FilterParts.py` & `simprocesd-0.2.0/examples/FilterParts.py`

 * *Files 7% similar despite different names*

```diff
@@ -22,16 +22,16 @@
 def main():
     system = System(DataStorageType.MEMORY)
 
     source = Source()
     M1 = Machine('Processor', upstream = [source], cycle_time = 1)
     M1.add_finish_processing_callback(process_part)
 
-    gate1 = DecisionGate(should_pass_part = lambda part: part.quality >= 0.75)
-    gate2 = DecisionGate(should_pass_part = lambda part: part.quality < 0.75)
+    gate1 = DecisionGate(should_pass_part = lambda gate, part: part.quality >= 0.75)
+    gate2 = DecisionGate(should_pass_part = lambda gate, part: part.quality < 0.75)
 
     M2 = Machine('PartFixer', upstream = [gate2], cycle_time = 1)
     M2.add_finish_processing_callback(improve_part)
     gate1.set_upstream([M1, M2])
     gate2.set_upstream([M1, M2])
 
     sink = Sink(upstream = [gate1], collect_parts = True)
```

### Comparing `simprocesd-0.1.7/examples/MachineFaultDetection.py` & `simprocesd-0.2.0/examples/MachineFaultDetection.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/MaintenanceOptimization.py` & `simprocesd-0.2.0/examples/MaintenanceOptimization.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/PaperMillCmsEvaluation.py` & `simprocesd-0.2.0/examples/PaperMillCmsEvaluation.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/ParallelStations.py` & `simprocesd-0.2.0/examples/ParallelStations.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/PartQuality.py` & `simprocesd-0.2.0/examples/PartQuality.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/SaveSimulationToFile.py` & `simprocesd-0.2.0/examples/SaveSimulationToFile.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/SingleMachine.py` & `simprocesd-0.2.0/examples/SingleMachine.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/SingleMachineWithFaults.py` & `simprocesd-0.2.0/examples/SingleMachineWithFaults.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,38 +1,44 @@
 '''
 An example of Markovian degradation of a single machine. Once the
 machine reaches the zero health it will shut down and stop receiving
 and processing parts until maintained. Machine degradation is simulated
 by a periodic fault.
-Expected parts produced: about 8000
+Expected to produce about 4000-4200 parts.
+Expected uptime %: ~80%
+    - average time to break 40, average maintenance duration 10
+Expected productive %: slightly above 50%
 '''
 
-import random
-
 from simprocesd.model import System
 from simprocesd.model.factory_floor import Source, Sink, Maintainer
 from simprocesd.utils import geometric_distribution_sample
 
 from .machine_with_faults import MachineWithFaults
 
 
 def main():
+    schedule_repair = lambda machine, fault: maintainer.create_work_order(machine, fault)
     system = System()
     maintainer = Maintainer()
 
-    source = Source()
+    source = Source(cycle_time = 2)
     M1 = MachineWithFaults('M1', cycle_time = 1, upstream = [source])
     M1.add_recurring_fault('Fault',
         get_time_to_fault = lambda: geometric_distribution_sample(0.1, 4),
-        get_time_to_maintain = lambda: geometric_distribution_sample(0.1, 1))
+        get_time_to_maintain = lambda: geometric_distribution_sample(0.1, 1),
+        failed_callback = schedule_repair)
 
-    on_shutdown_cb = lambda m, is_failure, p: maintainer.create_work_order(m, 'Fault')
-    M1.add_shutdown_callback(on_shutdown_cb)
     sink = Sink(upstream = [M1])
 
-    random.seed(1)
     # If time units are minutes then simulation period is a week.
-    system.simulate(simulation_duration = 60 * 24 * 7)
+    total_time = 60 * 24 * 7
+    system.simulate(simulation_duration = total_time)
+
+    percent_uptime = (M1.uptime / total_time) * 100
+    percent_utilization = (M1.utilization_time / M1.uptime) * 100
+    print(f'Machine {M1.name} uptime % of total simulation time: {percent_uptime:.2f}%')
+    print(f'Machine {M1.name} productive time as % of uptime: {percent_utilization:.2f}%')
 
 
 if __name__ == '__main__':
     main()
```

### Comparing `simprocesd-0.1.7/examples/VariousFlows.py` & `simprocesd-0.2.0/examples/VariousFlows.py`

 * *Files 5% similar despite different names*

```diff
@@ -18,16 +18,16 @@
 
     M1 = Machine('M1', upstream = [source], cycle_time = 2)
     M2 = Machine('M2', upstream = [M1], cycle_time = 5)
     M5 = Machine('M5', upstream = [M1], cycle_time = 5)
     M3 = Machine('M3', upstream = [M2, M5], cycle_time = 0.5)
     # Filters look on the routing history of the part to determine how
     # it got to M2, this determines which way the part is allowed to go.
-    G1 = DecisionGate(lambda part: part.routing_history[-2] == M2, 'G1', [M3])
-    G2 = DecisionGate(lambda part: part.routing_history[-2] == M5, 'G2', [M3])
+    G1 = DecisionGate(lambda gate, part: part.routing_history[-2] == M2, 'G1', [M3])
+    G2 = DecisionGate(lambda gate, part: part.routing_history[-2] == M5, 'G2', [M3])
     M6 = Machine('M6', upstream = [G2], cycle_time = 5)
     M4 = Machine('M4', upstream = [G1, M6], cycle_time = 2)
     machines = [M1, M2, M3, M4, M5, M6]
     sink = Sink(upstream = [M4], collect_parts = True)
 
     system.simulate(simulation_duration = 1000)
     print_produced_parts_and_average_quality(system, machines)
```

### Comparing `simprocesd-0.1.7/examples/machine_with_damage.py` & `simprocesd-0.2.0/examples/machine_with_damage.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/examples/machine_with_faults.py` & `simprocesd-0.2.0/examples/machine_with_faults.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/setup.py` & `simprocesd-0.2.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -5,15 +5,15 @@
     long_description = f.read().split('\n')
 long_description = '\n'.join(long_description[:10])
 long_description = long_description + \
         f'\nSee the project\'s [GitHub page]({source_code_url}) for more information.'
 
 setup(
     name = 'simprocesd',
-    version = '0.1.7',
+    version = '0.2.0',
     author = 'Serghei Drozdov',
     author_email = 'serghei.drozdov@nist.gov',
     description = 'Discreet event simulator for manufacturing systems.',
     long_description = long_description,
     long_description_content_type = 'text/markdown',
     project_urls = {
         'Source Code': source_code_url
@@ -33,17 +33,17 @@
     ],
     packages = find_packages(exclude = [
         'simprocesd.tests',
         'simprocesd.tests.*'
     ]),
     python_requires = ">=3.7",
     install_requires = [
+        'dill',
         'matplotlib >= 3.5',
-        'dill'
+        'numpy >= 1.21'
         ],
     extras_require = {
         "examples": [
-            'numpy >= 1.21',
             'scipy >= 1.7'
         ],
     },
 )
```

### Comparing `simprocesd-0.1.7/simprocesd/model/cms/cms.py` & `simprocesd-0.2.0/simprocesd/model/cms/cms.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/simprocesd/model/factory_floor/asset.py` & `simprocesd-0.2.0/simprocesd/model/factory_floor/asset.py`

 * *Files 4% similar despite different names*

```diff
@@ -30,18 +30,20 @@
         else:
             self._name = name
         self._env = None
         self._value = self._initial_value = value
         self._value_history = []
 
         if is_transitory == False:
+            # Will trigger initialize(env) to be called if simulation is
+            # already in progress.
             System.add_asset(self)
 
     def initialize(self, env):
-        '''Prepare asset for simulation and reset attributes to
+        '''Prepare Asset for simulation and reset attributes to
         starting values.
 
         In most cases this is called automatically by the System. Needs
         to be called manually if the Asset was initialized with
         is_transitory set to True.
 
         Arguments
```

### Comparing `simprocesd-0.1.7/simprocesd/model/factory_floor/decision_gate.py` & `simprocesd-0.2.0/simprocesd/model/factory_floor/decision_gate.py`

 * *Files 5% similar despite different names*

```diff
@@ -6,33 +6,34 @@
     upstream and downstream Devices.
 
     DecisionGate does not hold/buffer any parts.
 
     Arguments
     ---------
     should_pass_part: function
-        Function receives one argument: Part to be passed and should
-        return True if the Part can pass or False if it cannot.
+        Function receives two arguments: this DecisionGate and the Part
+        to be passed. Function should return True if the Part can pass
+        and False otherwise.
     name: str, default=None
         Name of the DecisionGate. If name is None then the
         DecisionGate's name will be changed to DecisionGate_<id>
-    upstream: list, default=[]
+    upstream: list, default=None
         A list of upstream Devices.
     '''
 
     def __init__(self,
                  should_pass_part,
                  name = None,
-                 upstream = []):
+                 upstream = None):
         super().__init__(name, upstream, 0)
         self._should_pass_part = should_pass_part
 
     def give_part(self, part):
         assert part != None, 'Part cannot be set to None.'
-        if not self.is_operational() or not self._should_pass_part(part):
+        if not self.is_operational() or not self._should_pass_part(self, part):
             return False
 
         for dwn in self._downstream:
             if dwn.give_part(part):
                 return True
         return False
```

### Comparing `simprocesd-0.1.7/simprocesd/model/factory_floor/device.py` & `simprocesd-0.2.0/simprocesd/model/factory_floor/device.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-from ...utils.utils import assert_is_instance
+from ...utils.utils import assert_is_instance, assert_callable
 from ..simulation import EventType
 from .asset import Asset
 
 
 class Device(Asset):
     ''' Base class for production devices.
 
@@ -10,31 +10,34 @@
     Devices.
 
     Arguments
     ---------
     name: str, default=None
         Name of the Device. If name is None then the Device's name will
         be changed to Device_<id>
-    upstream: list, default=[]
+    upstream: list, default=None
         A list of upstream Device objects.
     value: float, default=0
         Starting value of the Device.
     '''
 
-    def __init__(self, name = None, upstream = [], value = 0):
+    def __init__(self, name = None, upstream = None, value = 0):
         super().__init__(name, value)
 
         self._downstream = []
         self._upstream = []
         self._part = None
         self._output = None
         self._waiting_for_space_availability = False
         self._waiting_for_part_since = 0
-        self._env = None
+        self._received_part_callbacks = []
+        self._block_input = False
 
+        if upstream == None:
+            upstream = []
         self.set_upstream(upstream)
 
     def initialize(self, env):
         if self._env == None:
             # If this is the the first time initialize is called then
             # save the starting upstream list.
             self._initial_upstream = self.upstream
@@ -117,40 +120,91 @@
     def waiting_for_part_start_time(self):
         '''Simulation time of when this device started waiting for the
         next Part. Is set to None if the device is not currently waiting
         for a Part.
         '''
         return self._waiting_for_part_since
 
+    @property
+    def block_input(self):
+        '''When set to True this Device will not accept new Parts from
+        upstream.
+        '''
+        return self._block_input
+
+    @block_input.setter
+    def block_input(self, is_blocked):
+        assert isinstance(is_blocked, bool)
+        if self._block_input == is_blocked:
+            return
+        self._block_input = is_blocked
+        if not is_blocked and self._output == None and self._part == None:
+            self.notify_upstream_of_available_space()
+
     def _add_downstream(self, downstream):
         if downstream not in self._downstream:
             self._downstream.append(downstream)
 
     def _remove_downstream(self, downstream):
         self._downstream.remove(downstream)
 
-    def _schedule_pass_part_downstream(self):
+    def _schedule_pass_part_downstream(self, delay = 0):
         self._waiting_for_space_availability = False
-        self._env.schedule_event(self._env.now, self.id, self._pass_part_downstream,
+        self._env.schedule_event(self._env.now + delay, self.id, self._pass_part_downstream,
                                  EventType.PASS_PART, f'From {self.name}')
 
     def _pass_part_downstream(self):
         if not self.is_operational() or self._output == None: return
 
-        for dwn in self._priority_sorted_downstream():
+        for dwn in self.get_sorted_downstream_list():
             if dwn.give_part(self._output):
                 self._output = None
                 if self._part == None:
                     self.notify_upstream_of_available_space()
+                else:
+                    self._try_move_part_to_output()
                 return
         # Could not pass part downstream
         self._waiting_for_space_availability = True
 
-    def _priority_sorted_downstream(self):
-        return sorted(self._downstream, key = lambda d: d.waiting_for_part_start_time \
+    def get_sorted_downstream_list(self):
+        '''Get the sorted list of downstream Devices.
+
+        Returns
+        -------
+        list
+            A sorted list of downstream devices.
+        '''
+        return Device.downstream_priority_sorter(self.downstream)
+
+    @staticmethod
+    def downstream_priority_sorter(downstream):
+        '''Sort the downstream list in a descending priority of where
+        Parts should be moved to first.
+
+        Default implementation gives higher priority to Devices that
+        have been waiting for a Part the longest.
+
+        Note
+        ----
+        Overwrite this static function to change how all Devices
+        prioritize where Parts are passed.
+
+        Arguments
+        ---------
+        downstream: list
+            A list of downstream Devices.
+
+        Returns
+        -------
+        list
+            A list of downstream devices sorted from highest to lowest
+            priority.
+        '''
+        return sorted(downstream, key = lambda d: d.waiting_for_part_start_time \
                       if d.waiting_for_part_start_time != None else float('inf'))
 
     def _set_waiting_for_part(self, is_waiting = True, reset = False):
         if is_waiting == False:
             self._waiting_for_part_since = None
         else:
             if self._waiting_for_part_since != None and not reset:
@@ -190,31 +244,63 @@
             Part that is being passed.
 
         Returns
         -------
         bool
             True if the Part has been accepted, otherwise False.
         '''
-        assert part != None, 'part should never be None.'
-        if (not self.is_operational() or part == None
-                                      or self._part != None
-                                      or self._output != None):
+        if not self._can_accept_part(part):
             return False
+        self._accept_part(part)
+        return True
+
+    def _can_accept_part(self, part):
+        return (self.is_operational() and part != None
+                                      and self._part == None
+                                      and self._output == None
+                                      and not self._block_input)
 
+    def _accept_part(self, part):
+        assert part != None, 'part cannot be None.'
         self._part = part
-        self._part.routing_history.append(self)
+        self._part.add_routing_history(self)
         self._set_waiting_for_part(False)
         self._on_received_new_part()
-        return True
 
     def _on_received_new_part(self):
+        self._env.add_datapoint('received_part', self.name, (self._env.now,
+                                                              self._part.id,
+                                                              self._part.quality,
+                                                              self._part.value))
+        for c in self._received_part_callbacks:
+            c(self, self._part)
         if self._output == None:
             self._try_move_part_to_output()
 
     def _try_move_part_to_output(self):
         if not self.is_operational() or self._part == None or self._output != None:
             return
         self._output = self._part
         self._part = None
         self._schedule_pass_part_downstream()
         return
 
+    def add_receive_part_callback(self, callback):
+        '''Setup a function to be called when the Machine receives a
+        new Part.
+
+        | Callback signature: callback(machine, part)
+        | machine - Machine to which the callback was added.
+        | part - Part that was lost or None if no Part was lost.
+
+        If Machine cycle time is changed within the callback then it
+        will be used as the processing time for the Part that was just
+        received as well as all the future Parts.
+
+        Arguments
+        ---------
+        callback: function
+            Function to be called.
+        '''
+        assert_callable(callback)
+        self._received_part_callbacks.append(callback)
+
```

### Comparing `simprocesd-0.1.7/simprocesd/model/factory_floor/maintainer.py` & `simprocesd-0.2.0/simprocesd/model/factory_floor/maintainer.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,120 +1,28 @@
 from ...utils import assert_is_instance
 from ..simulation import EventType
 from .asset import Asset
 
 
-class Maintainable:
-    '''An interface the Maintainer uses to create, prioritize, and
-    execute work orders.
-
-    Maintainer can only perform work orders on classes that use
-    Maintainable as one of their base classes.
-    '''
-
-    def get_work_order_duration(self, tag):
-        '''Called at the beginning of performing a work order to
-        determine how long the work order will take.
-
-        Arguments
-        ---------
-        tag: object
-            Identifier for the work order.
-
-        Returns
-        -------
-        float
-            How long it will take to perform the work order indicated
-            by the tag. Duration is measured in simulation time units.
-        '''
-        return 0
-
-    def get_work_order_capacity(self, tag):
-        ''' Called once when the work order is created to determine how
-        much of the Maintainer's capacity is needed to perform the work
-        order.
-
-        Arguments
-        ---------
-        tag: object
-            Identifier for the work order.
-
-        Returns
-        -------
-        float
-            Needed capacity to perform the work order indicated by the
-            tag.
-        '''
-        return 0
-
-    def get_work_order_cost(self, tag):
-        ''' Called once to get the cost to Maintainer to perform the
-        work order.
-
-        Returned value will be subtracted from Maintainer's value. If
-        the work order cost is tracked elsewhere then this should return
-        0 (default implementation).
-
-        Arguments
-        ---------
-        tag: object
-            Identifier for the work order.
-
-        Returns
-        -------
-        float
-            Needed capacity to perform the work order indicated by the
-            tag.
-        '''
-        return 0
-
-    def start_work(self, tag):
-        ''' Called by Maintainer when it begins working on the work
-        order.
-
-        Arguments
-        ---------
-        tag: object
-            Identifier for the work order.
-        '''
-        pass
-
-    def end_work(self, tag):
-        ''' Called by Maintainer when it finishes working on the work
-        order.
-
-        Arguments
-        ---------
-        tag: object
-            Identifier for the work order.
-        '''
-        pass
-
-
-class WorkOrder:
-
-    def __init__(self, target, tag, needed_capacity):
-        assert_is_instance(target, Maintainable)
-        self.target = target
-        self.tag = tag
-        self.needed_capacity = needed_capacity
-
-
 class Maintainer(Asset):
     '''Asset that is responsible for performing requested work orders.
 
     Requests are generally worked in a first come first serve order
     but a later request may be worked first when available capacity is
     insufficient for the earlier request.
 
     Maintainer can work on multiple work orders at the same time as long
     the the combined needed capacity of the work orders is less than or
     equal to the Maintainer's maximum capacity. Needed capacity is
     determined by Maintainable.get_work_order_capacity
 
+    Maintainer will not perform simultaneous work orders on the same
+    target and will instead perform them sequentially even if there is
+    enough capacity.
+
     Note
     ----
     Capacity units are not defined but need to be consistent across work
     order capacity requirements and Maintainer's maximum capacity.
 
     Arguments
     ---------
@@ -151,44 +59,49 @@
 
     def initialize(self, env):
         super().initialize(env)
         self._utilization = 0
         self._request_queue = []
         self._active_requests = []
 
-    def create_work_order(self, target, tag = None):
+    def create_work_order(self, target, tag = None, info = None):
         '''Request a new work order to be performed.
 
         Creates a new work order and adds it to the back of the queue of
         work orders to be executed.
 
         Arguments
         ---------
         target: Maintainable
             Target of the work order to be performed.
         tag: object, default=None
             Identifier the target uses to differentiate between various
-            work orders that could be performed on it.
+            types of work orders that could be performed on it.
+        info: str, default=None
+            A string to be included with datapoints that track the
+            lifecycle of the order.
+            Example uses: reason for the work order, source of the work
+            order, a unique identifier, etc.
 
         Returns
         -------
         bool
             True if the work order was added to the queue and
             False if it was rejected. Request will be rejected if the
             same work order request is already in the queue or is being
             worked on.
         '''
         assert_is_instance(target, Maintainable)
         if self._is_work_order_requested(target, tag):
             return False
 
         capacity = target.get_work_order_capacity(tag)
-        name = getattr(target, 'name', 'N/A')
-        self._env.add_datapoint('enter_queue', self.name, (self._env.now, name, tag))
-        self._request_queue.append(WorkOrder(target, tag, capacity))
+        request = _WorkOrder(target, tag, capacity, info)
+        self._record_work_order_datapoint('enter_queue', request)
+        self._request_queue.append(request)
         self.try_working_requests()
         return True
 
     def _is_work_order_requested(self, target, tag = None):
         for r in self._request_queue:
             if r.target == target and r.tag == tag:
                 return True
@@ -209,15 +122,19 @@
         This function is called automatically when requests are made
         and when requests are completed. Normally there should be no
         need to call it manually.
         '''
         i = 0
         while i < len(self._request_queue):
             req = self._request_queue[i]
-            if self._utilization <= self._capacity - req.needed_capacity:
+            # Find other active work orders on the same target.
+            other_work_orders = [x for x in self._active_requests if x.target == req.target]
+
+            if self._utilization <= self._capacity - req.needed_capacity \
+                    and len(other_work_orders) == 0:
                 self._request_queue.pop(i)
                 self._active_requests.append(req)
 
                 self._utilization += req.needed_capacity
                 self._env.schedule_event(
                     self._env.now,
                     self.id,
@@ -225,16 +142,15 @@
                     EventType.START_WORK,
                     f'start work order: {req.target.name}')
             else:
                 i += 1
 
     def _start_work_order(self, request):
         ttm = request.target.get_work_order_duration(request.tag)
-        self._env.add_datapoint('start_work_order', self.name,
-                                (self._env.now, request.target.name, request.tag))
+        self._record_work_order_datapoint('start_work_order', request)
 
         cost = request.target.get_work_order_cost(request.tag)
         self.add_cost(f'work order - tag:{request.tag} target:{request.target.name}', cost)
 
         request.target.start_work(request.tag)
         self._env.schedule_event(
             self._env.now + ttm,
@@ -243,12 +159,112 @@
             EventType.FINISH_WORK,
             f'end work order: {request.target.name}')
 
     def _finish_work_order(self, request):
         request.target.end_work(request.tag)
         self._utilization -= request.needed_capacity
         self._active_requests.remove(request)
-        self._env.add_datapoint('finish_work_order', self.name,
-                                (self._env.now, request.target.name, request.tag))
+        self._record_work_order_datapoint('finish_work_order', request)
 
         self.try_working_requests()
 
+    def _record_work_order_datapoint(self, list_label, request):
+        name = getattr(request.target, 'name', 'N/A')
+        self._env.add_datapoint(list_label, self.name,
+                                (self._env.now, name, request.tag, request.info))
+
+
+class _WorkOrder:
+
+    def __init__(self, target, tag, needed_capacity, info):
+        assert_is_instance(target, Maintainable)
+        self.target = target
+        self.tag = tag
+        self.needed_capacity = needed_capacity
+        self.info = info
+
+
+class Maintainable:
+    '''An interface the Maintainer uses to create, prioritize, and
+    execute work orders.
+
+    Maintainer can only perform work orders on classes that use
+    Maintainable as one of their base classes.
+    '''
+
+    def get_work_order_duration(self, tag):
+        '''Called at the beginning of performing a work order to
+        determine how long the work order will take.
+
+        Arguments
+        ---------
+        tag: object
+            Identifier for the work order.
+
+        Returns
+        -------
+        float
+            How long it will take to perform the work order indicated
+            by the tag. Duration is measured in simulation time units.
+        '''
+        return 0
+
+    def get_work_order_capacity(self, tag):
+        ''' Called once when the work order is created to determine how
+        much of the Maintainer's capacity is needed to perform the work
+        order.
+
+        Arguments
+        ---------
+        tag: object
+            Identifier for the work order.
+
+        Returns
+        -------
+        float
+            Needed capacity to perform the work order indicated by the
+            tag.
+        '''
+        return 0
+
+    def get_work_order_cost(self, tag):
+        ''' Called once to get the cost to Maintainer to perform the
+        work order.
+
+        Returned value will be subtracted from Maintainer's value. If
+        the work order cost is tracked elsewhere then this should return
+        0 (default implementation).
+
+        Arguments
+        ---------
+        tag: object
+            Identifier for the work order.
+
+        Returns
+        -------
+        float
+            Needed capacity to perform the work order indicated by the
+            tag.
+        '''
+        return 0
+
+    def start_work(self, tag):
+        ''' Called by Maintainer when it begins working on the work
+        order.
+
+        Arguments
+        ---------
+        tag: object
+            Identifier for the work order.
+        '''
+        pass
+
+    def end_work(self, tag):
+        ''' Called by Maintainer when it finishes working on the work
+        order.
+
+        Arguments
+        ---------
+        tag: object
+            Identifier for the work order.
+        '''
+        pass
```

### Comparing `simprocesd-0.1.7/simprocesd/model/factory_floor/part.py` & `simprocesd-0.2.0/simprocesd/model/factory_floor/part.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,8 +1,10 @@
+from ...utils.utils import assert_is_instance
 from .asset import Asset
+from .device import Device
 
 
 class Part(Asset):
     '''Representation of an item/part that passes between Devices in a
     production line.
 
     Arguments
@@ -32,31 +34,28 @@
         super().initialize(env)
         self.quality = self._initial_quality
         self._routing_history = []
         self.copy_counter = 0
 
     @property
     def routing_history(self):
-        ''' Ordered list of devices that the part passed
-        through. First entry is usually a Source.
-
-        Warning
-        -------
-        Predefined classes (Source, Device, etc) contain code for
-        updating the routing history so a custom subclass is responsible
-        for ensuring those updates still happen or it might not appear
-        in the routing history.
+        '''Ordered list of devices that the part passed through.
+        First entry is usually a Source.
         '''
-        return self._routing_history
+        return self._routing_history.copy()
+
+    def add_routing_history(self, device):
+        assert_is_instance(device, Device)
+        self._routing_history.append(device)
 
     def make_copy(self):
         ''' Create a copy of this Part.
 
         Returns
         -------
         Part
             a copy of this Part with a unique ID and an empty
-            routing_history.
+            routing_history. Returned Part is not initialized.
         '''
         self.copy_counter += 1
         new_part = Part(f'{self.name}_{self.copy_counter}', self.value, self.quality)
         return new_part
```

### Comparing `simprocesd-0.1.7/simprocesd/model/factory_floor/sink.py` & `simprocesd-0.2.0/simprocesd/model/factory_floor/sink.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-from .machine import Machine
+from . import Batch, Machine
 
 
 class Sink(Machine):
     '''A Device that can receive any number of Parts but not pass
     those Parts. It is the end of a production line.
 
     Note
@@ -11,15 +11,15 @@
     Part. This is how Sink tracks the output value of produced Parts.
 
     Arguments
     ----------
     name: str, default=None
         Name of the Sink. If name is None then the Sink's name will
         be changed to Sink_<id>
-    upstream: list, default=[]
+    upstream: list, default=None
         A list of upstream Devices.
     cycle_time: float, default=0
         Minimum time between receiving Parts.
     collect_parts: bool, default=False
         If True then received Parts are stored throughout the simulation
         and can be accessed under 'collected_parts'.
 
@@ -27,15 +27,15 @@
     ----------
     collected_parts: list
         List of received Parts in the order they were received.
     '''
 
     def __init__(self,
                  name = None,
-                 upstream = [],
+                 upstream = None,
                  cycle_time = 0,
                  collect_parts = False):
         super().__init__(name, upstream, cycle_time = cycle_time, value = 0)
 
         self._collect_parts = collect_parts
         self.collected_parts = []
         self._received_parts_count = 0
@@ -49,25 +49,31 @@
 
     def _add_downstream(self, downstream):
         raise RuntimeError('Sink cannot have any downstreams.')
 
     @property
     def received_parts_count(self):
         '''Count of all received Parts.
+
+        When receiving a Batch this will increase by the number of Parts
+        contained within the Batch.
         '''
         return self._received_parts_count
 
     @property
     def value_of_received_parts(self):
         '''Summed value of all received Parts.
         '''
         return self._value_of_received_parts
 
     def _on_received_new_part(self):
-        self._received_parts_count += 1
+        if isinstance(self._part, Batch):
+            self._received_parts_count += len(self._part.parts)
+        else:
+            self._received_parts_count += 1
         self._value_of_received_parts += self._part.value
         self.add_value(f'collected_part', self._part.value)
         if self._collect_parts:
             self.collected_parts.append(self._part)
 
         super()._on_received_new_part()
```

### Comparing `simprocesd-0.1.7/simprocesd/model/factory_floor/source.py` & `simprocesd-0.2.0/simprocesd/model/factory_floor/source.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,11 @@
-from . import Machine, Part
 from .. import EventType
 from ...utils import assert_is_instance
+from .machine import Machine
+from .part import Part
 
 
 class Source(Machine):
     '''A Device that produces Part objects and supplies them to Devices
     downstream. It is the start of a production line.
 
     Source will not start producing a next Part until previous Part is
@@ -29,15 +30,15 @@
         How long it takes to produce a Part.
     max_produced_parts: int, optional
         Maximum number of Parts to produce. No maximum if not set.
     '''
 
     def __init__(self, name = None, sample_part = None, cycle_time = 0.0,
                  max_produced_parts = float('inf')):
-        super().__init__(name, [], cycle_time, value = 0)
+        super().__init__(name, None, cycle_time, value = 0)
 
         if sample_part == None:
             sample_part = Part()
         else:
             assert_is_instance(sample_part, Part)
         self._sample_part = sample_part
 
@@ -47,15 +48,15 @@
 
     def initialize(self, env):
         super().initialize(env)
         self._sample_part.initialize(env)
         self._cost_of_produced_parts = 0
         self._produced_parts = 0
 
-        self._schedule_prepare_next_part()
+        self._schedule_finish_processing_part()
 
     def set_upstream(self, new_upstream_list):
         ''' Source cannot have upstream Devices.
 
         Raises
         ------
         ValueError
@@ -74,35 +75,26 @@
     @property
     def produced_parts(self):
         ''' Returns the count of the parts that have been produced by
         this Source and passed downstream.
         '''
         return self._produced_parts
 
-    def _schedule_prepare_next_part(self):
-        self._env.schedule_event(
-            self._env.now + self._cycle_time,
-            self.id,
-            self._prepare_next_part,
-            EventType.FINISH_PROCESSING,
-            f'By {self.name}'
-        )
-
-    def _prepare_next_part(self):
+    def _finish_processing_part(self):
         self._output = self._sample_part.make_copy()
         self._output.initialize(self._env)
-        self._output.routing_history.append(self)
+        self._output.add_routing_history(self)
 
         self._schedule_pass_part_downstream()
 
     def _pass_part_downstream(self):
-        if self._produced_parts + 1 > self._max_produced_parts: return
-
-        output_before = self._output
+        if self._produced_parts >= self._max_produced_parts or self._output == None:
+            return
+        supplied_part_value = self._output.value
         super()._pass_part_downstream()
-        if output_before != None and self._output == None:
+        if self._output == None:  # Part was passed downstream.
             self._produced_parts += 1
-            self.add_cost('supplied_part', output_before.value)
-            self._cost_of_produced_parts += output_before.value
+            self.add_cost('supplied_part', supplied_part_value)
+            self._cost_of_produced_parts += supplied_part_value
             self._env.add_datapoint('supplied_new_part', self.name, (self._env.now,))
-            self._schedule_prepare_next_part()
+            self._schedule_finish_processing_part()
```

### Comparing `simprocesd-0.1.7/simprocesd/model/sensors/part_sensor.py` & `simprocesd-0.2.0/simprocesd/model/sensors/part_sensor.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/simprocesd/model/sensors/sensor.py` & `simprocesd-0.2.0/simprocesd/model/sensors/sensor.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/simprocesd/model/simulation.py` & `simprocesd-0.2.0/simprocesd/model/simulation.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,24 +19,25 @@
     is slightly higher or lower than another event. For example:
     "event_type = EventType.FAIL - 0.1". An event with this event_type
     will be executed with a slightly lower priority than EventType.FAIL
     '''
     TERMINATE = auto()
 
     OTHER_LOW_PRIORITY = auto()
-    START_WORK = auto()
+    START_WORK = auto()  # Maintainer work order.
     SENSOR = auto()
     FAIL = auto()
+    RELEASE_RESERVED_RESOURCES = auto()
 
     # Order of the next 2 events is required for correct machine throughput.
     PASS_PART = auto()
     FINISH_PROCESSING = auto()
 
     RESTORE = auto()
-    FINISH_WORK = auto()
+    FINISH_WORK = auto()  # Maintainer work order.
     OTHER_HIGH_PRIORITY = auto()
 
 
 class Event:
     '''Class used for scheduling actions within the simulation.
 
     | Higher Event priority is determined by:
@@ -57,17 +58,18 @@
         Priority of the event, recommended to use EventType enum.
     message: str, default=''
         Any message to be associated with this Event. Useful as
         debugging information.
     '''
 
     def __init__(self, time, asset_id, action, event_type, message = ''):
-        assert_is_instance(asset_id, int)
-        assert_is_instance(time, (float, int))
-        assert_callable(action, False)
+        if __debug__:
+            assert_is_instance(asset_id, int)
+            assert_is_instance(time, (float, int))
+            assert_callable(action, False)
 
         self.time = time
         self.asset_id = asset_id
         self.action = action
         self.event_type = event_type
         self.message = message
         self.status = ''
@@ -85,26 +87,24 @@
             self.status = 'cancelled'
             return
         if not self.executed:
             self.action()
             self.executed = True
 
     def __lt__(self, other):
-        return (
-            self.time,
-            -self.event_type,
-            self.random_weight,
-            # A reliable tie-breaker because asset IDs are unique
-            self.asset_id
-        ) < (
-            other.time,
-            -other.event_type,
-            other.random_weight,
-            other.asset_id
-        )
+        if self.time != other.time:
+            return self.time < other.time
+        elif self.event_type != other.event_type:
+            # Event type value order is reverse.
+            return self.event_type > other.event_type
+        elif self.random_weight != other.random_weight:
+            return self.random_weight < other.random_weight
+        else:
+            # IDs are reliable tie-breakers because they are unique.
+            return self.asset_id < other.asset_id
 
     def __str__(self):
         return f'Event: time={self.time} asset_id={self.asset_id} action={self.action} ' \
         +f'event_type={self.event_type} message={self.message} status={self.status} ' \
         +f'paused_at={self.paused_at} cancelled={self.cancelled} executed={self.executed} '
 
 
@@ -131,34 +131,40 @@
     ----------
     now: float
         Current time of the simulation, starts at 0.
     simulation_data: list
         Stored datapoints added with Environment.add_datapoint
     '''
 
-    def __init__(self, name = 'environment', simulation_data_storage_type = DataStorageType.NONE):
+    def __init__(self, name = 'environment', simulation_data_storage_type = DataStorageType.NONE,
+                 resource_manager = None):
         self.name = name
         self._simulation_data_storage_type = simulation_data_storage_type
         if self._simulation_data_storage_type == DataStorageType.FILE:
             raise NotImplementedError('Storing to file/disk is not supported yet.')
+        self.resource_manager = resource_manager
         self.reset()
 
+    @property
+    def now(self):
+        return self._now
+
     def reset(self):
         '''Reset the Environment to its initial state.
 
         This will clear out all scheduled and paused events and reset
         the simulation_data table. To preserve the old data save a
         reference to simulation_data before calling reset, the reference
         can then be used to access old data.
         '''
-        self.now = 0
+        self._now = 0
         self.simulation_data = {}
         self._events = []
         self._paused_events = []
-        self._terminated = False
+        self._terminated = True
         self._event_trace = {}
         self._trace = False
         self._event_index = 0
 
     def run(self, simulation_duration, trace = False):
         '''Simulate the system for a limited duration.
 
@@ -170,32 +176,32 @@
         simulation_duration: float
             For how long to run the simulation. Measured in simulation
             time.
         trace: bool, default=False
             If True then executed Events will be recorded and exported
             to a file at: '~/Downloads/{environment.name}_trace.json'
         '''
+        self._terminated = False
         self._trace = trace
 
         self.schedule_event(self.now + simulation_duration, -1, self._terminate, EventType.TERMINATE)
 
         try:
             while self._events and not self._terminated:
                 self.step()
-            self._terminated = False
         finally:
             if self._trace:
                 self._export_trace()
 
     def step(self):
         '''Execute a scheduled Event with the highest priority.
         '''
         next_event = self._events.pop(0)
 
-        self.now = next_event.time
+        self._now = next_event.time
 
         try:
             if self._trace:
                 self._trace_event(next_event)
             next_event.execute()
         except Exception as e:
             print('Failed event:')
@@ -229,14 +235,23 @@
             debugging information.
         '''
         if time < self.now:
             raise ValueError(f'Can not schedule _events in the past: now={self.now}, time={time}')
         new_event = Event(time, asset_id, action, event_type, message)
         bisect.insort(self._events, new_event)
 
+    def is_simulation_in_progress(self):
+        '''Indicates whether a simulation is in progress or not.
+
+        Returns
+        -------
+        True if the simulation is currently in progress, otherwise False.
+        '''
+        return not self._terminated
+
     def _terminate(self):
         self._terminated = True
 
     def _trace_event(self, event):
         self._event_trace[self._event_index] = {'time': self.now,
                                                 'asset_id': event.asset_id,
                                                 'action': event.action.__name__,
@@ -321,18 +336,16 @@
         '''
         if self._simulation_data_storage_type == DataStorageType.NONE:
             return
         elif self._simulation_data_storage_type == DataStorageType.MEMORY:
             try:
                 table_dictionary = self.simulation_data[list_label]
             except KeyError:
-                # Using KeyError to indicate dictionary entry needs
-                # initialization for better overall performance.
                 table_dictionary = {}
                 self.simulation_data[list_label] = table_dictionary
 
             try:
                 table_dictionary[sub_label].append(datapoint)
             except KeyError:
                 table_dictionary[sub_label] = [datapoint]
         elif self._simulation_data_storage_type == DataStorageType.FILE:
-            raise NotImplementedError('Storing to file/disk is not supported yet.')
+            raise NotImplementedError('Storing to file/disk is not supported.')
```

### Comparing `simprocesd-0.1.7/simprocesd/model/system.py` & `simprocesd-0.2.0/simprocesd/model/system.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 import time
 
-from . import Environment
+from . import Environment, ResourceManager
 from ..utils import DataStorageType
 
 
 class System:
     '''A required class that helps setup and run simulations.
 
     System handles Asset initialization and manages the Environment
@@ -19,23 +19,28 @@
     System.
 
     Arguments
     ---------
     simulation_data_storage_type: DataStorageType, default=DataStorageType.MEMORY
         How to store <simulation_data>. Does not currently support
         DataStorageType.FILE
+    resource_manager: ResourceManager, default=None
+        A ResourceManager instance to use for this simulation. If None
+        then the default ResourceManager will be used.
     '''
 
     _instance = None  # Last initialized System.
 
     @staticmethod
     def add_asset(new_asset):
         '''Register an Asset with the active System.
 
-        Automatically called by newly created Assets.
+        Automatically called by newly created Assets. If the simulation
+        is already in progress then the new_asset will be initialized
+        immediately.
 
         Note: System will keep a reference to this Asset so transitory
         assets should not be added here or they will remain loaded into
         memory. For example, Parts are not added here and parts are
         initialized by the Source that created them.
 
         Arguments
@@ -48,34 +53,42 @@
         RuntimeError
             System object must be created before non-transitory Assets.
         '''
         if System._instance == None:
             raise RuntimeError('A System object must be initialized before creating any asset.')
         if new_asset not in System._instance._assets:
             System._instance._assets.append(new_asset)
+            if System._instance._simulation_is_initialized:
+                new_asset.initialize(System._instance._env)
 
-    def __init__(self, simulation_data_storage_type = DataStorageType.MEMORY):
+    def __init__(self, simulation_data_storage_type = DataStorageType.MEMORY, resource_manager = None):
         self._assets = []
-        self._env = Environment(simulation_data_storage_type = simulation_data_storage_type)
+        if resource_manager == None:
+            resource_manager = ResourceManager()
+        self._env = Environment(simulation_data_storage_type = simulation_data_storage_type,
+                                resource_manager = resource_manager)
         self._simulation_is_initialized = False
 
         System._instance = self
 
     @property
     def simulation_data(self):
         '''Stored datapoints added with
-        environment.add_datapoint(list_label, sub_label, datapoint)
+        Environment.add_datapoint(list_label, sub_label, datapoint)
 
         | To retrieving a list of datapoints call:
         | system.simulation_data[list_label][sub_label]
         '''
-        if self._env is not None:
-            return self._env.simulation_data
-        else:
-            return None
+        return self._env.simulation_data
+
+    @property
+    def resource_manager(self):
+        '''ResourceManager instance.
+        '''
+        return self._env.resource_manager
 
     def simulate(self, simulation_duration, reset = True, trace = False, print_summary = True):
         '''Run the simulation for the specified duration.
 
         Ensures objects are initialized or re-initialized as needed.
 
         Arguments
@@ -98,14 +111,15 @@
         '''
         if System._instance != self:
             raise RuntimeError('This System can no longer simulate because a new one was created.')
         start = time.time()
 
         if not self._simulation_is_initialized or reset == True:
             self._env.reset()
+            self.resource_manager.initialize(self._env)
             for asset in self._assets:
                 asset.initialize(self._env)
             self._simulation_is_initialized = True
 
         produced_parts_before = self._get_part_count_in_sinks()
         self._env.run(simulation_duration, trace = trace)
         produced_parts_after = self._get_part_count_in_sinks()
@@ -113,15 +127,15 @@
         stop = time.time()
         if print_summary:
             print(f'Simulation finished in {stop-start:.2f}s')
             print(f'Parts received by sink/s: {produced_parts_after - produced_parts_before}')
 
     def _get_part_count_in_sinks(self):
         from .factory_floor.sink import Sink  # Late import to avoid circular dependency.
-        return sum(x.received_parts_count for x in self._assets if isinstance(x, Sink))
+        return sum(sink.received_parts_count for sink in self.find_assets(type_ = Sink))
 
     def get_net_value_of_assets(self):
         '''Calculate the net value of all Assets which are registered
         with the System.
 
         Returns
         -------
```

### Comparing `simprocesd-0.1.7/simprocesd/utils/math_utils.py` & `simprocesd-0.2.0/simprocesd/utils/math_utils.py`

 * *Files identical despite different names*

### Comparing `simprocesd-0.1.7/simprocesd/utils/simulation_info_utils.py` & `simprocesd-0.2.0/simprocesd/utils/simulation_info_utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -13,20 +13,20 @@
     Arguments
     ---------
     system: System
         System object used in the simulation.
     machines: list
         List of Machines to consider.
     '''
-    all_production_data = system.simulation_data.get('produced_parts', {})
+    all_production_data = system.simulation_data.get('produced_part', {})
     for machine in machines:
         machine_production_data = all_production_data.get(machine.name, [])
         quality_sum = 0
         for d in machine_production_data:
-            quality_sum += d[1]
+            quality_sum += d[2]
         try:
             average_quality = round(quality_sum / len(machine_production_data), 4)
         except ZeroDivisionError:
             average_quality = 'N/A'
         print(f'Machine {machine.name} produced {len(machine_production_data)} parts with average '
               +f'quality of {average_quality}')
 
@@ -73,15 +73,15 @@
     ---------
     system: System
         System object used in the simulation.
     machines: list
         List of Machines to plot.
     '''
     figure, graph = pyplot.subplots()
-    all_production_data = system.simulation_data.get('produced_parts', {})
+    all_production_data = system.simulation_data.get('produced_part', {})
     for machine in machines:
         machine_production_data = all_production_data.get(machine.name, [])
         # Make a list of tuples: (time, parts_produced_so_far)
         production_data = [(machine_production_data[i][0], i + 1)
                            for i in range(len(machine_production_data))]
         throughput = [
             parts_produced / time
```

### Comparing `simprocesd-0.1.7/simprocesd/utils/utils.py` & `simprocesd-0.2.0/simprocesd/utils/utils.py`

 * *Files 3% similar despite different names*

```diff
@@ -4,55 +4,63 @@
 
 import dill as dill
 
 
 def assert_is_instance(obj, class_type, message = None):
     '''Check if an object is an instance of a specific class type.
 
+    Returns immediately if not in debug mode.
+
     Arguments
     ---------
     obj: object
         Object that will be checked.
     class_type: type
         Class type that the object needs to be.
     message: str, optional
         Error message if object is not an instance of <class_type>.
 
     Raises
     ------
     TypeError
         If <obj> is not an instance of <class_type>
     '''
+    if not __debug__: return
+
     if not isinstance(obj, class_type):
         if message == None:
             message = f'Object, {type(obj)}, does not implement {class_type}'
         raise TypeError(message)
 
 
 def assert_callable(obj, none_allowed = False, message = None):
     '''Check if an object appears callable.
 
     The check is done using the built-in 'callable()' function. In some
     cases it is possible the function not to raise an error even if
     <obj> cannot be called like a function.
 
+    Returns immediately if not in debug mode.
+
     Arguments
     ---------
     obj: object
         Object that will be checked.
     none_allowed: bool, default=False
         If the value of None is allowed.
     message: str, optional
         Error message if object is not callable.
 
     Raises
     ------
     TypeError
         If object is not callable.
     '''
+    if not __debug__: return
+
     if obj == None:
         if not none_allowed:
             message = f'obj can not be None.'
             raise TypeError(message)
     elif not callable(obj):
         if none_allowed:
             message = f'Object, {type(obj)}, must be a callable or None.'
```

### Comparing `simprocesd-0.1.7/simprocesd.egg-info/PKG-INFO` & `simprocesd-0.2.0/simprocesd.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: simprocesd
-Version: 0.1.7
+Version: 0.2.0
 Summary: Discreet event simulator for manufacturing systems.
 Author: Serghei Drozdov
 Author-email: serghei.drozdov@nist.gov
 License: US Government Open Source
 Project-URL: Source Code, https://github.com/usnistgov/simprocesd
 Classifier: Development Status :: 3 - Alpha
 Classifier: Programming Language :: Python
```

### Comparing `simprocesd-0.1.7/simprocesd.egg-info/SOURCES.txt` & `simprocesd-0.2.0/simprocesd.egg-info/SOURCES.txt`

 * *Files 12% similar despite different names*

```diff
@@ -1,47 +1,53 @@
 LICENSE.md
 README.md
 setup.py
+examples/BatchProcessing.py
 examples/BufferExample.py
 examples/ConditionBasedMaintenance.py
 examples/DataExploration.py
 examples/ExtendingPartObject.py
 examples/FilterParts.py
 examples/MachineFaultDetection.py
 examples/MaintenanceOptimization.py
+examples/OperatingSchedule.py
 examples/PaperMillCmsEvaluation.py
 examples/ParallelStations.py
 examples/PartQuality.py
 examples/SaveSimulationToFile.py
+examples/SharedResources.py
 examples/SingleMachine.py
 examples/SingleMachineWithFaults.py
-examples/TwoMachinesWithFaults.py
 examples/VariousFlows.py
 examples/__init__.py
 examples/machine_with_damage.py
 examples/machine_with_faults.py
 simprocesd/__init__.py
 simprocesd.egg-info/PKG-INFO
 simprocesd.egg-info/SOURCES.txt
 simprocesd.egg-info/dependency_links.txt
 simprocesd.egg-info/requires.txt
 simprocesd.egg-info/top_level.txt
 simprocesd/model/__init__.py
+simprocesd/model/resource_manager.py
 simprocesd/model/simulation.py
 simprocesd/model/system.py
 simprocesd/model/cms/__init__.py
 simprocesd/model/cms/cms.py
 simprocesd/model/factory_floor/__init__.py
+simprocesd/model/factory_floor/action_scheduler.py
 simprocesd/model/factory_floor/asset.py
+simprocesd/model/factory_floor/batch.py
 simprocesd/model/factory_floor/buffer.py
 simprocesd/model/factory_floor/decision_gate.py
 simprocesd/model/factory_floor/device.py
 simprocesd/model/factory_floor/machine.py
 simprocesd/model/factory_floor/maintainer.py
 simprocesd/model/factory_floor/part.py
+simprocesd/model/factory_floor/part_batcher.py
 simprocesd/model/factory_floor/sink.py
 simprocesd/model/factory_floor/source.py
 simprocesd/model/sensors/__init__.py
 simprocesd/model/sensors/part_sensor.py
 simprocesd/model/sensors/sensor.py
 simprocesd/utils/__init__.py
 simprocesd/utils/enums.py
```

